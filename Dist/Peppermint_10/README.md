Peppermint 10 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Peppermint 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Peppermint_10/Desktop/README.md) and [notebooks](/Dist/Peppermint_10/Notebook/README.md).

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

Total: 353

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | AOA110                      | Notebook    | [560aa745c1](https://linux-hardware.org/?probe=560aa745c1) | Dec 14, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [2e1f6c73da](https://linux-hardware.org/?probe=2e1f6c73da) | Nov 22, 2022 |
| Lenovo        | ThinkPad T60 1952CTO        | Notebook    | [f84f14587b](https://linux-hardware.org/?probe=f84f14587b) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7177bb644a](https://linux-hardware.org/?probe=7177bb644a) | Jul 15, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [36851c847b](https://linux-hardware.org/?probe=36851c847b) | Jul 08, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [4b63d98b33](https://linux-hardware.org/?probe=4b63d98b33) | May 16, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [2f6fdef961](https://linux-hardware.org/?probe=2f6fdef961) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [bedf7835b0](https://linux-hardware.org/?probe=bedf7835b0) | Feb 08, 2022 |
| Dell          | Latitude D630               | Notebook    | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Dell          | Latitude D630               | Notebook    | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [a7209bb34a](https://linux-hardware.org/?probe=a7209bb34a) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [5f7c38d0d5](https://linux-hardware.org/?probe=5f7c38d0d5) | Jan 22, 2022 |
| Medion        | WIM2160                     | Notebook    | [5e529f33bc](https://linux-hardware.org/?probe=5e529f33bc) | Jan 15, 2022 |
| Medion        | WIM2160                     | Notebook    | [758e2a7717](https://linux-hardware.org/?probe=758e2a7717) | Jan 15, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [3cdc62c355](https://linux-hardware.org/?probe=3cdc62c355) | Jan 05, 2022 |
| Acer          | AOA110                      | Notebook    | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASUSTek       | 1000H                       | Notebook    | [7b25815657](https://linux-hardware.org/?probe=7b25815657) | Dec 29, 2021 |
| Lenovo        | G575 4383                   | Notebook    | [ef4143d3b6](https://linux-hardware.org/?probe=ef4143d3b6) | Dec 22, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | Notebook    | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [1a2930b22b](https://linux-hardware.org/?probe=1a2930b22b) | Dec 02, 2021 |
| Intel         | D865GSA AAD52278-203        | Desktop     | [9b874becf9](https://linux-hardware.org/?probe=9b874becf9) | Dec 01, 2021 |
| Intel         | D865GSA AAD52278-203        | Desktop     | [ae2963be56](https://linux-hardware.org/?probe=ae2963be56) | Dec 01, 2021 |
| Acer          | Aspire 4810T                | Notebook    | [2f0aa07be8](https://linux-hardware.org/?probe=2f0aa07be8) | Nov 26, 2021 |
| Positivo      | Mobile                      | Notebook    | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Positivo      | Mobile                      | Notebook    | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| ECS           | Nettle3                     | Desktop     | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [def67fa4e7](https://linux-hardware.org/?probe=def67fa4e7) | Nov 16, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [58d4a2dd00](https://linux-hardware.org/?probe=58d4a2dd00) | Nov 10, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | Notebook    | [15f9885d1f](https://linux-hardware.org/?probe=15f9885d1f) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| Intel         | H61                         | Desktop     | [f1d3a975c0](https://linux-hardware.org/?probe=f1d3a975c0) | Oct 26, 2021 |
| Toshiba       | Satellite L750D             | Notebook    | [e24684255d](https://linux-hardware.org/?probe=e24684255d) | Oct 26, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | Notebook    | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| ECS           | MCP61PM-GM                  | Desktop     | [1d13b80285](https://linux-hardware.org/?probe=1d13b80285) | Oct 13, 2021 |
| ASRock        | P4VM8                       | Desktop     | [5797c27ef8](https://linux-hardware.org/?probe=5797c27ef8) | Oct 10, 2021 |
| ASRock        | P4VM8                       | Desktop     | [84c50aca4b](https://linux-hardware.org/?probe=84c50aca4b) | Oct 10, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [7f51bdb2d1](https://linux-hardware.org/?probe=7f51bdb2d1) | Oct 08, 2021 |
| HP            | 2000                        | Notebook    | [00f01e8929](https://linux-hardware.org/?probe=00f01e8929) | Oct 08, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [be79dd5979](https://linux-hardware.org/?probe=be79dd5979) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [c5492b6d2f](https://linux-hardware.org/?probe=c5492b6d2f) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [522a137a4e](https://linux-hardware.org/?probe=522a137a4e) | Oct 05, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| HP            | 15                          | Notebook    | [a976f1d357](https://linux-hardware.org/?probe=a976f1d357) | Sep 28, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [b54d6779c8](https://linux-hardware.org/?probe=b54d6779c8) | Sep 19, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [b1f8d57cae](https://linux-hardware.org/?probe=b1f8d57cae) | Sep 09, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| ASUSTek       | K52F                        | Notebook    | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| Sony          | VGN-S55B_S                  | Notebook    | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [830eaafeac](https://linux-hardware.org/?probe=830eaafeac) | Aug 08, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [0a9b2f9147](https://linux-hardware.org/?probe=0a9b2f9147) | Aug 08, 2021 |
| HP            | 2AE3                        | Desktop     | [6780c45f7c](https://linux-hardware.org/?probe=6780c45f7c) | Aug 02, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [113c8ab052](https://linux-hardware.org/?probe=113c8ab052) | Jul 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [827993d9c3](https://linux-hardware.org/?probe=827993d9c3) | Jul 17, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| Dell          | Precision M4600             | Notebook    | [0242a479d2](https://linux-hardware.org/?probe=0242a479d2) | Jul 13, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [9ba35acb61](https://linux-hardware.org/?probe=9ba35acb61) | Jun 24, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [399e422d5b](https://linux-hardware.org/?probe=399e422d5b) | Jun 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09171395a9](https://linux-hardware.org/?probe=09171395a9) | Jun 22, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [cdbc4c8c02](https://linux-hardware.org/?probe=cdbc4c8c02) | Jun 22, 2021 |
| Toshiba       | NB500                       | Notebook    | [e5095d1545](https://linux-hardware.org/?probe=e5095d1545) | Jun 21, 2021 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [6d6430f8ff](https://linux-hardware.org/?probe=6d6430f8ff) | Jun 18, 2021 |
| Acer          | AOA150                      | Notebook    | [7cbadcfcce](https://linux-hardware.org/?probe=7cbadcfcce) | Jun 13, 2021 |
| Toshiba       | NB500                       | Notebook    | [0a57436b83](https://linux-hardware.org/?probe=0a57436b83) | Jun 13, 2021 |
| Toshiba       | NB500                       | Notebook    | [be659779e6](https://linux-hardware.org/?probe=be659779e6) | Jun 13, 2021 |
| HP            | Mini 110-1100               | Notebook    | [dcaac9d2ce](https://linux-hardware.org/?probe=dcaac9d2ce) | Jun 04, 2021 |
| HP            | Mini 110-1100               | Notebook    | [d919b139c6](https://linux-hardware.org/?probe=d919b139c6) | Jun 04, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [9c2c0af05f](https://linux-hardware.org/?probe=9c2c0af05f) | May 27, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [0a5e45a21e](https://linux-hardware.org/?probe=0a5e45a21e) | May 27, 2021 |
| HP            | Presario C500 (RZ343UA#A... | Notebook    | [d37099a83d](https://linux-hardware.org/?probe=d37099a83d) | May 25, 2021 |
| HP            | Presario C500 (RZ343UA#A... | Notebook    | [4aef9f472c](https://linux-hardware.org/?probe=4aef9f472c) | May 17, 2021 |
| JPSaCouto     | Intel powered classmate ... | Notebook    | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | Notebook    | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| Acer          | Extensa 5510                | Notebook    | [8e9e536486](https://linux-hardware.org/?probe=8e9e536486) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | Notebook    | [12b76c8bca](https://linux-hardware.org/?probe=12b76c8bca) | Apr 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [d54424038e](https://linux-hardware.org/?probe=d54424038e) | Apr 18, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [562d38cca5](https://linux-hardware.org/?probe=562d38cca5) | Apr 18, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | Notebook    | [87befc0401](https://linux-hardware.org/?probe=87befc0401) | Apr 16, 2021 |
| Pegatron      | Benicia                     | Desktop     | [7b1f7c7edf](https://linux-hardware.org/?probe=7b1f7c7edf) | Apr 15, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [a23936a0de](https://linux-hardware.org/?probe=a23936a0de) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [56c5cc70d1](https://linux-hardware.org/?probe=56c5cc70d1) | Apr 07, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [71e906faa3](https://linux-hardware.org/?probe=71e906faa3) | Apr 07, 2021 |
| Dell          | Latitude 7410               | Notebook    | [a72bb094fd](https://linux-hardware.org/?probe=a72bb094fd) | Mar 26, 2021 |
| ASUSTek       | P4VP-MX                     | Desktop     | [ce116189a9](https://linux-hardware.org/?probe=ce116189a9) | Mar 19, 2021 |
| ASUSTek       | P4VP-MX                     | Desktop     | [1f7de7a842](https://linux-hardware.org/?probe=1f7de7a842) | Mar 19, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [ebd077e7f4](https://linux-hardware.org/?probe=ebd077e7f4) | Mar 16, 2021 |
| HP            | Pavilion g6                 | Notebook    | [6079cacf9b](https://linux-hardware.org/?probe=6079cacf9b) | Mar 14, 2021 |
| Samsung       | R530/R730/R540              | Notebook    | [a9fd173c51](https://linux-hardware.org/?probe=a9fd173c51) | Mar 13, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | Desktop     | [efab4d96e9](https://linux-hardware.org/?probe=efab4d96e9) | Mar 10, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | Desktop     | [514d4c99a1](https://linux-hardware.org/?probe=514d4c99a1) | Mar 10, 2021 |
| Dell          | Dimension E521              | Desktop     | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | 0C522T A01                  | Desktop     | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| Dell          | Inspiron 1012               | Notebook    | [4c4bb4bd4a](https://linux-hardware.org/?probe=4c4bb4bd4a) | Mar 04, 2021 |
| HP            | 3032h                       | Desktop     | [50914ba2f5](https://linux-hardware.org/?probe=50914ba2f5) | Mar 04, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [b0cdfde6d1](https://linux-hardware.org/?probe=b0cdfde6d1) | Mar 02, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [492714801f](https://linux-hardware.org/?probe=492714801f) | Mar 02, 2021 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [236a4d5753](https://linux-hardware.org/?probe=236a4d5753) | Feb 23, 2021 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [27f148966a](https://linux-hardware.org/?probe=27f148966a) | Feb 23, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| Lenovo        | ThinkPad R60 94566FG        | Notebook    | [f0eb3f1d77](https://linux-hardware.org/?probe=f0eb3f1d77) | Feb 19, 2021 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [3ae1e824ed](https://linux-hardware.org/?probe=3ae1e824ed) | Feb 13, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [003b1f0799](https://linux-hardware.org/?probe=003b1f0799) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [a642972ffa](https://linux-hardware.org/?probe=a642972ffa) | Feb 12, 2021 |
| Dell          | Dimension E521              | Desktop     | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Dimension E521              | Desktop     | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f7fc4d663b](https://linux-hardware.org/?probe=f7fc4d663b) | Feb 08, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e4d417012f](https://linux-hardware.org/?probe=e4d417012f) | Feb 08, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [cf6b92a979](https://linux-hardware.org/?probe=cf6b92a979) | Feb 07, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Dell          | 0TP406                      | Desktop     | [0980bfcfe9](https://linux-hardware.org/?probe=0980bfcfe9) | Jan 28, 2021 |
| Dell          | 0K216C                      | Desktop     | [c1cf70d814](https://linux-hardware.org/?probe=c1cf70d814) | Jan 19, 2021 |
| Sony          | VPCZ21V9E                   | Notebook    | [f0e8428fc2](https://linux-hardware.org/?probe=f0e8428fc2) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [b0aa1bff61](https://linux-hardware.org/?probe=b0aa1bff61) | Jan 12, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [b0f061dfba](https://linux-hardware.org/?probe=b0f061dfba) | Jan 08, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [da98de1775](https://linux-hardware.org/?probe=da98de1775) | Jan 08, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5494aa2859](https://linux-hardware.org/?probe=5494aa2859) | Jan 04, 2021 |
| Acer          | AOD255                      | Notebook    | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
| Lenovo        | ThinkPad T450 20BUS3CF00    | Notebook    | [4dde602ff6](https://linux-hardware.org/?probe=4dde602ff6) | Jan 01, 2021 |
| Acer          | Extensa 5630                | Notebook    | [eed68dd316](https://linux-hardware.org/?probe=eed68dd316) | Dec 30, 2020 |
| Sony          | VPCZ21V9E                   | Notebook    | [b34a53e0e2](https://linux-hardware.org/?probe=b34a53e0e2) | Dec 29, 2020 |
| Acer          | Extensa 5510                | Notebook    | [efd4fce381](https://linux-hardware.org/?probe=efd4fce381) | Dec 29, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [56f8292d5b](https://linux-hardware.org/?probe=56f8292d5b) | Dec 23, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| MSI           | MS-7211                     | Desktop     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Acer          | Extensa 5220                | Notebook    | [3dfca3a90f](https://linux-hardware.org/?probe=3dfca3a90f) | Dec 12, 2020 |
| Acer          | Extensa 5220                | Notebook    | [9b67134373](https://linux-hardware.org/?probe=9b67134373) | Dec 12, 2020 |
| Dell          | Precision M4700             | Notebook    | [58d2d0e8d4](https://linux-hardware.org/?probe=58d2d0e8d4) | Dec 11, 2020 |
| Dell          | Precision M4700             | Notebook    | [379e1a461c](https://linux-hardware.org/?probe=379e1a461c) | Dec 09, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [ac934f7ac7](https://linux-hardware.org/?probe=ac934f7ac7) | Dec 07, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [8f2d17e846](https://linux-hardware.org/?probe=8f2d17e846) | Dec 07, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [7499600f8c](https://linux-hardware.org/?probe=7499600f8c) | Dec 02, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Nvidia        | MCP7A 2                     | Desktop     | [c18fd136a9](https://linux-hardware.org/?probe=c18fd136a9) | Nov 24, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [ff9f1e3bc5](https://linux-hardware.org/?probe=ff9f1e3bc5) | Nov 22, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [41517af8ad](https://linux-hardware.org/?probe=41517af8ad) | Nov 22, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [c0c9898136](https://linux-hardware.org/?probe=c0c9898136) | Nov 19, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [f19c7014be](https://linux-hardware.org/?probe=f19c7014be) | Nov 19, 2020 |
| Dell          | Latitude E7440              | Notebook    | [222b0a563a](https://linux-hardware.org/?probe=222b0a563a) | Nov 15, 2020 |
| Gigabyte      | J1800M-D3P                  | Desktop     | [9ab6ea275f](https://linux-hardware.org/?probe=9ab6ea275f) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | J1800M-D3P                  | Desktop     | [ae71ad880b](https://linux-hardware.org/?probe=ae71ad880b) | Nov 10, 2020 |
| HP            | Pavilion dv8000 (EZ590UA... | Notebook    | [1e64c078af](https://linux-hardware.org/?probe=1e64c078af) | Nov 04, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [c02b06f51f](https://linux-hardware.org/?probe=c02b06f51f) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [808224d57c](https://linux-hardware.org/?probe=808224d57c) | Oct 30, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [f7fc9c9932](https://linux-hardware.org/?probe=f7fc9c9932) | Oct 20, 2020 |
| Google        | Gnawty                      | Notebook    | [6bb50a022d](https://linux-hardware.org/?probe=6bb50a022d) | Oct 10, 2020 |
| Toshiba       | QOSMIO F755                 | Notebook    | [defa9c775a](https://linux-hardware.org/?probe=defa9c775a) | Oct 01, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [37cf119697](https://linux-hardware.org/?probe=37cf119697) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [d822785861](https://linux-hardware.org/?probe=d822785861) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [b0a785eecd](https://linux-hardware.org/?probe=b0a785eecd) | Sep 30, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [64da7044cf](https://linux-hardware.org/?probe=64da7044cf) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [e45ead8de9](https://linux-hardware.org/?probe=e45ead8de9) | Sep 20, 2020 |
| Samsung       | R610                        | Notebook    | [db61c853a2](https://linux-hardware.org/?probe=db61c853a2) | Sep 17, 2020 |
| ASUSTek       | T101HA                      | Notebook    | [036f4f2304](https://linux-hardware.org/?probe=036f4f2304) | Sep 15, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [7a9366d7a0](https://linux-hardware.org/?probe=7a9366d7a0) | Sep 04, 2020 |
| ASUSTek       | P53E                        | Notebook    | [75d3fa4178](https://linux-hardware.org/?probe=75d3fa4178) | Sep 04, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [06dd4aecb5](https://linux-hardware.org/?probe=06dd4aecb5) | Sep 01, 2020 |
| Acer          | TravelMate B115-M           | Notebook    | [d3395dca0c](https://linux-hardware.org/?probe=d3395dca0c) | Aug 30, 2020 |
| Itautec       | W7655                       | Notebook    | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| HP            | 8265                        | Desktop     | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Samsung       | N150P                       | Notebook    | [17e2e411da](https://linux-hardware.org/?probe=17e2e411da) | Aug 07, 2020 |
| Toshiba       | Satellite L310              | Notebook    | [bf2bd8711e](https://linux-hardware.org/?probe=bf2bd8711e) | Aug 03, 2020 |
| HP            | 0A54h                       | Desktop     | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| Samsung       | N150/N210/N220              | Notebook    | [304d7ac49d](https://linux-hardware.org/?probe=304d7ac49d) | Aug 02, 2020 |
| ASRock        | N68-S3 FX                   | Desktop     | [cbf919cfd5](https://linux-hardware.org/?probe=cbf919cfd5) | Jul 30, 2020 |
| HP            | 18E7                        | Desktop     | [4b13141bdb](https://linux-hardware.org/?probe=4b13141bdb) | Jul 30, 2020 |
| HP            | EliteBook 2740p             | Notebook    | [b87f4916b6](https://linux-hardware.org/?probe=b87f4916b6) | Jul 27, 2020 |
| HP            | Compaq Presario CQ40        | Notebook    | [aaf338c454](https://linux-hardware.org/?probe=aaf338c454) | Jul 24, 2020 |
| Dell          | Latitude E6420              | Notebook    | [1db19a0158](https://linux-hardware.org/?probe=1db19a0158) | Jul 24, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [bd697a03f8](https://linux-hardware.org/?probe=bd697a03f8) | Jul 19, 2020 |
| Itautec       | W7655                       | Notebook    | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [dc82f8cf6b](https://linux-hardware.org/?probe=dc82f8cf6b) | Jul 15, 2020 |
| Positivo      | N1103                       | Notebook    | [3cdb7fc95e](https://linux-hardware.org/?probe=3cdb7fc95e) | Jul 13, 2020 |
| Toshiba       | PORTEGE R500                | Notebook    | [e7c5c010bd](https://linux-hardware.org/?probe=e7c5c010bd) | Jul 12, 2020 |
| Toshiba       | PORTEGE R500                | Notebook    | [fd50b5e2a7](https://linux-hardware.org/?probe=fd50b5e2a7) | Jul 12, 2020 |
| Dell          | Latitude E6420              | Notebook    | [52d11b26d3](https://linux-hardware.org/?probe=52d11b26d3) | Jul 09, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [dbecc119b2](https://linux-hardware.org/?probe=dbecc119b2) | Jul 08, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| HP            | Notebook                    | Notebook    | [841b43ba94](https://linux-hardware.org/?probe=841b43ba94) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [a514be4e22](https://linux-hardware.org/?probe=a514be4e22) | Jun 06, 2020 |
| Lenovo        | B490 37722SP                | Notebook    | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| MSI           | MS-7267                     | Desktop     | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Mini 110-1000               | Notebook    | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | Notebook    | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [94839129c9](https://linux-hardware.org/?probe=94839129c9) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [adf1cefbf5](https://linux-hardware.org/?probe=adf1cefbf5) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [6782b31a2e](https://linux-hardware.org/?probe=6782b31a2e) | May 17, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Clevo         | W55xEU                      | Notebook    | [f1ad04bd23](https://linux-hardware.org/?probe=f1ad04bd23) | May 16, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [4fa188ca3e](https://linux-hardware.org/?probe=4fa188ca3e) | May 15, 2020 |
| ECS           | Alhena5                     | Desktop     | [be2ff7b4dc](https://linux-hardware.org/?probe=be2ff7b4dc) | May 15, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a0112b2478](https://linux-hardware.org/?probe=a0112b2478) | May 14, 2020 |
| Toshiba       | Satellite M70               | Notebook    | [c9e02a940d](https://linux-hardware.org/?probe=c9e02a940d) | May 13, 2020 |
| ASUSTek       | Q400A                       | Notebook    | [075d494ee2](https://linux-hardware.org/?probe=075d494ee2) | May 10, 2020 |
| Lenovo        | B575 1450A7U                | Notebook    | [b781397fa7](https://linux-hardware.org/?probe=b781397fa7) | May 05, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [39798ff3d6](https://linux-hardware.org/?probe=39798ff3d6) | May 05, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [3d10f5b306](https://linux-hardware.org/?probe=3d10f5b306) | May 03, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [0e91d35b8e](https://linux-hardware.org/?probe=0e91d35b8e) | May 03, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [8aad1d7bfc](https://linux-hardware.org/?probe=8aad1d7bfc) | May 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [c948d7fd76](https://linux-hardware.org/?probe=c948d7fd76) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [595c810650](https://linux-hardware.org/?probe=595c810650) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [f1fc9b4580](https://linux-hardware.org/?probe=f1fc9b4580) | Apr 29, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [131e2c31a9](https://linux-hardware.org/?probe=131e2c31a9) | Apr 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [f9944d9361](https://linux-hardware.org/?probe=f9944d9361) | Apr 25, 2020 |
| Toshiba       | Satellite Pro C850          | Notebook    | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
| Dell          | 0WF810                      | Desktop     | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [79e6fc40f4](https://linux-hardware.org/?probe=79e6fc40f4) | Apr 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5ddee791c7](https://linux-hardware.org/?probe=5ddee791c7) | Apr 20, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [15b2fb3807](https://linux-hardware.org/?probe=15b2fb3807) | Apr 20, 2020 |
| ASUSTek       | X45U                        | Notebook    | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [e6b8191910](https://linux-hardware.org/?probe=e6b8191910) | Apr 16, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [20e7fea349](https://linux-hardware.org/?probe=20e7fea349) | Apr 08, 2020 |
| Lenovo        | 433328G                     | Notebook    | [3c5b9e3703](https://linux-hardware.org/?probe=3c5b9e3703) | Apr 07, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [0c74c17c24](https://linux-hardware.org/?probe=0c74c17c24) | Apr 07, 2020 |
| Gigabyte      | VM900M                      | Desktop     | [8554ccddc2](https://linux-hardware.org/?probe=8554ccddc2) | Apr 03, 2020 |
| HP            | 2133 (FU346EA)              | Notebook    | [499f685a66](https://linux-hardware.org/?probe=499f685a66) | Mar 31, 2020 |
| HP            | 2133 (FU346EA)              | Notebook    | [2c6f9bf922](https://linux-hardware.org/?probe=2c6f9bf922) | Mar 31, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [8fae01eff8](https://linux-hardware.org/?probe=8fae01eff8) | Mar 31, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| HP            | 255 G2                      | Notebook    | [7cfb9e5a0e](https://linux-hardware.org/?probe=7cfb9e5a0e) | Mar 25, 2020 |
| Clevo         | W55xEU                      | Notebook    | [09d70e49b4](https://linux-hardware.org/?probe=09d70e49b4) | Mar 23, 2020 |
| Unknown       | G41 Series                  | Desktop     | [597b5edb76](https://linux-hardware.org/?probe=597b5edb76) | Mar 20, 2020 |
| ASUSTek       | F3E                         | Notebook    | [e01cca6624](https://linux-hardware.org/?probe=e01cca6624) | Mar 18, 2020 |
| ASUSTek       | F3E                         | Notebook    | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | 0AA8h                       | Desktop     | [881008d596](https://linux-hardware.org/?probe=881008d596) | Mar 11, 2020 |
| Acer          | MCP73PV NVIDIA MCP73        | Desktop     | [97b8e03710](https://linux-hardware.org/?probe=97b8e03710) | Mar 04, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [8b516d50ef](https://linux-hardware.org/?probe=8b516d50ef) | Mar 03, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [c67fe8542c](https://linux-hardware.org/?probe=c67fe8542c) | Mar 01, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| ECS           | Alhena5                     | Desktop     | [89c17f438e](https://linux-hardware.org/?probe=89c17f438e) | Feb 28, 2020 |
| eMachines     | E520 V1.06                  | Notebook    | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| Toshiba       | Satellite C850-F117         | Notebook    | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| HP            | 0AA8h                       | Desktop     | [c5721d223f](https://linux-hardware.org/?probe=c5721d223f) | Feb 05, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Toshiba       | NB520                       | Notebook    | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | Notebook    | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [0244fb9c97](https://linux-hardware.org/?probe=0244fb9c97) | Feb 01, 2020 |
| ASUSTek       | S500CA                      | Notebook    | [4f82008cac](https://linux-hardware.org/?probe=4f82008cac) | Jan 29, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Lenovo        | 31900058 STD                | Desktop     | [4d8db6ee1f](https://linux-hardware.org/?probe=4d8db6ee1f) | Jan 22, 2020 |
| Lenovo        | 31900058 STD                | Desktop     | [6320c5f50f](https://linux-hardware.org/?probe=6320c5f50f) | Jan 22, 2020 |
| Sony          | VPCCW21FX                   | Notebook    | [78ac20109b](https://linux-hardware.org/?probe=78ac20109b) | Jan 21, 2020 |
| ASUSTek       | P8H61-MX                    | Desktop     | [c7c5cc3339](https://linux-hardware.org/?probe=c7c5cc3339) | Jan 17, 2020 |
| ASUSTek       | P8H61-MX                    | Desktop     | [4e6cff6c0e](https://linux-hardware.org/?probe=4e6cff6c0e) | Jan 17, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [75648daef1](https://linux-hardware.org/?probe=75648daef1) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | Desktop     | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d87b9779d7](https://linux-hardware.org/?probe=d87b9779d7) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c6595736b8](https://linux-hardware.org/?probe=c6595736b8) | Jan 14, 2020 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [db8eaef3e7](https://linux-hardware.org/?probe=db8eaef3e7) | Jan 09, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [847cb4544c](https://linux-hardware.org/?probe=847cb4544c) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [cf7e7bc433](https://linux-hardware.org/?probe=cf7e7bc433) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [d7442beee0](https://linux-hardware.org/?probe=d7442beee0) | Dec 23, 2019 |
| HP            | 0A54h                       | Desktop     | [3a37dfd543](https://linux-hardware.org/?probe=3a37dfd543) | Dec 05, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [f30cd368d8](https://linux-hardware.org/?probe=f30cd368d8) | Dec 02, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [86b1a4acd7](https://linux-hardware.org/?probe=86b1a4acd7) | Dec 02, 2019 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [f2817e5306](https://linux-hardware.org/?probe=f2817e5306) | Nov 29, 2019 |
| Biostar       | A68N-5600E                  | Desktop     | [d91042148c](https://linux-hardware.org/?probe=d91042148c) | Nov 27, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [5b8f68dbc9](https://linux-hardware.org/?probe=5b8f68dbc9) | Nov 26, 2019 |
| Toshiba       | Satellite C55D-B            | Notebook    | [0d1bbd1e60](https://linux-hardware.org/?probe=0d1bbd1e60) | Nov 25, 2019 |
| Toshiba       | Satellite C55D-B            | Notebook    | [98653dbce0](https://linux-hardware.org/?probe=98653dbce0) | Nov 25, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                     | Desktop     | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [c27bae21b0](https://linux-hardware.org/?probe=c27bae21b0) | Nov 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [afb3948882](https://linux-hardware.org/?probe=afb3948882) | Nov 15, 2019 |
| Acer          | Aspire F5-573G              | Notebook    | [db302aa54d](https://linux-hardware.org/?probe=db302aa54d) | Nov 14, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [00c8d1e4e7](https://linux-hardware.org/?probe=00c8d1e4e7) | Nov 11, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [b7c0226ab5](https://linux-hardware.org/?probe=b7c0226ab5) | Nov 10, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cc352f0876](https://linux-hardware.org/?probe=cc352f0876) | Nov 10, 2019 |
| ASUSTek       | X99-A/USB                   | Desktop     | [40ea4505b9](https://linux-hardware.org/?probe=40ea4505b9) | Nov 09, 2019 |
| eMachines     | EL1850                      | Desktop     | [c2b6c642fb](https://linux-hardware.org/?probe=c2b6c642fb) | Nov 09, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a4bd90bb25](https://linux-hardware.org/?probe=a4bd90bb25) | Nov 09, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [2ac11dfe68](https://linux-hardware.org/?probe=2ac11dfe68) | Nov 02, 2019 |
| ASUSTek       | 1005PXD                     | Notebook    | [d0afcbe081](https://linux-hardware.org/?probe=d0afcbe081) | Oct 26, 2019 |
| ASUSTek       | 1005PXD                     | Notebook    | [1e57ee0116](https://linux-hardware.org/?probe=1e57ee0116) | Oct 26, 2019 |
| Lenovo        | 31900058 STD                | Desktop     | [ee0395fcb1](https://linux-hardware.org/?probe=ee0395fcb1) | Oct 25, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [14784cf228](https://linux-hardware.org/?probe=14784cf228) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Gigabyte      | H61M-S1                     | Desktop     | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                     | Desktop     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                     | Desktop     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | Desktop     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [6e3970fc39](https://linux-hardware.org/?probe=6e3970fc39) | Sep 17, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [20f7841be1](https://linux-hardware.org/?probe=20f7841be1) | Sep 17, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [f29f057c97](https://linux-hardware.org/?probe=f29f057c97) | Sep 16, 2019 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [dee3d2bdaa](https://linux-hardware.org/?probe=dee3d2bdaa) | Sep 04, 2019 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [cfaaae942a](https://linux-hardware.org/?probe=cfaaae942a) | Aug 27, 2019 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [85ac9b2b53](https://linux-hardware.org/?probe=85ac9b2b53) | Aug 20, 2019 |
| Foxconn       | 2AB7                        | Desktop     | [f1f1f7133a](https://linux-hardware.org/?probe=f1f1f7133a) | Aug 18, 2019 |
| ASUSTek       | P5K-VM                      | Desktop     | [e2d3942d30](https://linux-hardware.org/?probe=e2d3942d30) | Jul 25, 2019 |
| Unknown       | Unknown                     | Notebook    | [0a9618f99e](https://linux-hardware.org/?probe=0a9618f99e) | Jul 10, 2019 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [d1b680dc39](https://linux-hardware.org/?probe=d1b680dc39) | Jul 05, 2019 |
| Dell          | 0C2KJT A00                  | Desktop     | [986146d6eb](https://linux-hardware.org/?probe=986146d6eb) | Jul 01, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| Dell          | 0C2KJT A00                  | Desktop     | [ee64cbe6b5](https://linux-hardware.org/?probe=ee64cbe6b5) | Jun 28, 2019 |
| HP            | Pavilion dv7                | Notebook    | [24128291a4](https://linux-hardware.org/?probe=24128291a4) | Jun 25, 2019 |
| Unknown       | Unknown                     | Notebook    | [583ec484b5](https://linux-hardware.org/?probe=583ec484b5) | Jun 24, 2019 |
| Unknown       | Unknown                     | Notebook    | [c0eb7dc5f0](https://linux-hardware.org/?probe=c0eb7dc5f0) | Jun 24, 2019 |
| ASUSTek       | Q501LA                      | Notebook    | [ad06395996](https://linux-hardware.org/?probe=ad06395996) | Jun 23, 2019 |
| Toshiba       | Satellite M70               | Notebook    | [c31329a508](https://linux-hardware.org/?probe=c31329a508) | Jun 19, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | Notebook    | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | Notebook    | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.0.0-37-generic  | 39        | 15.18%  |
| 4.18.0-18-generic | 11        | 4.28%   |
| 5.4.0-42-generic  | 10        | 3.89%   |
| 5.3.0-51-generic  | 10        | 3.89%   |
| 5.3.0-62-generic  | 8         | 3.11%   |
| 5.4.0-65-generic  | 7         | 2.72%   |
| 5.3.0-46-generic  | 7         | 2.72%   |
| 5.0.0-36-generic  | 7         | 2.72%   |
| 5.0.0-32-generic  | 7         | 2.72%   |
| 5.4.0-87-generic  | 6         | 2.33%   |
| 5.4.0-66-generic  | 6         | 2.33%   |
| 5.4.0-58-generic  | 6         | 2.33%   |
| 5.4.0-91-generic  | 5         | 1.95%   |
| 5.4.0-52-generic  | 5         | 1.95%   |
| 5.3.0-40-generic  | 5         | 1.95%   |
| 5.3.0-28-generic  | 5         | 1.95%   |
| 5.4.0-90-generic  | 4         | 1.56%   |
| 5.4.0-80-generic  | 4         | 1.56%   |
| 5.4.0-72-generic  | 4         | 1.56%   |
| 5.4.0-67-generic  | 4         | 1.56%   |
| 5.4.0-54-generic  | 4         | 1.56%   |
| 5.4.0-48-generic  | 4         | 1.56%   |
| 5.4.0-45-generic  | 4         | 1.56%   |
| 5.3.0-59-generic  | 4         | 1.56%   |
| 4.18.0-25-generic | 4         | 1.56%   |
| 5.4.0-81-generic  | 3         | 1.17%   |
| 5.4.0-77-generic  | 3         | 1.17%   |
| 5.4.0-70-generic  | 3         | 1.17%   |
| 5.4.0-56-generic  | 3         | 1.17%   |
| 5.4.0-47-generic  | 3         | 1.17%   |
| 5.3.0-47-generic  | 3         | 1.17%   |
| 5.3.0-42-generic  | 3         | 1.17%   |
| 5.0.0-29-generic  | 3         | 1.17%   |
| 5.4.0-97-generic  | 2         | 0.78%   |
| 5.4.0-84-generic  | 2         | 0.78%   |
| 5.4.0-74-generic  | 2         | 0.78%   |
| 5.4.0-62-generic  | 2         | 0.78%   |
| 5.4.0-60-generic  | 2         | 0.78%   |
| 5.4.0-49-generic  | 2         | 0.78%   |
| 5.3.0-45-generic  | 2         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 112       | 46.28%  |
| 5.0.0   | 57        | 23.55%  |
| 5.3.0   | 47        | 19.42%  |
| 4.18.0  | 20        | 8.26%   |
| 5.7.1   | 1         | 0.41%   |
| 5.6.7   | 1         | 0.41%   |
| 5.4.95  | 1         | 0.41%   |
| 5.3.9   | 1         | 0.41%   |
| 5.3.6   | 1         | 0.41%   |
| 5.1.11  | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 113       | 46.69%  |
| 5.0     | 57        | 23.55%  |
| 5.3     | 49        | 20.25%  |
| 4.18    | 20        | 8.26%   |
| 5.7     | 1         | 0.41%   |
| 5.6     | 1         | 0.41%   |
| 5.1     | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 154       | 66.96%  |
| i686   | 76        | 33.04%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXDE       | 188       | 80.34%  |
| Unknown    | 35        | 14.96%  |
| GNOME      | 9         | 3.85%   |
| X-Cinnamon | 1         | 0.43%   |
| Peppermint | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 229       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 207       | 89.22%  |
| LightDM | 14        | 6.03%   |
| TDM     | 10        | 4.31%   |
| SDDM    | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 78        | 33.33%  |
| Unknown | 26        | 11.11%  |
| it_IT   | 15        | 6.41%   |
| en_GB   | 15        | 6.41%   |
| pt_BR   | 13        | 5.56%   |
| de_DE   | 13        | 5.56%   |
| C       | 7         | 2.99%   |
| pl_PL   | 6         | 2.56%   |
| en_IN   | 6         | 2.56%   |
| ru_RU   | 5         | 2.14%   |
| nl_NL   | 5         | 2.14%   |
| fr_FR   | 5         | 2.14%   |
| en_CA   | 5         | 2.14%   |
| es_AR   | 4         | 1.71%   |
| ro_RO   | 3         | 1.28%   |
| fi_FI   | 3         | 1.28%   |
| es_MX   | 3         | 1.28%   |
| ja_JP   | 2         | 0.85%   |
| es_PE   | 2         | 0.85%   |
| es_ES   | 2         | 0.85%   |
| en_PH   | 2         | 0.85%   |
| en_AU   | 2         | 0.85%   |
| tr_TR   | 1         | 0.43%   |
| sv_SE   | 1         | 0.43%   |
| pt_PT   | 1         | 0.43%   |
| lv_LV   | 1         | 0.43%   |
| es_PA   | 1         | 0.43%   |
| es_EC   | 1         | 0.43%   |
| es_CR   | 1         | 0.43%   |
| es_BO   | 1         | 0.43%   |
| en_ZA   | 1         | 0.43%   |
| en_NZ   | 1         | 0.43%   |
| en_IE   | 1         | 0.43%   |
| cs_CZ   | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 181       | 78.7%   |
| EFI  | 49        | 21.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 197       | 84.19%  |
| Unknown  | 19        | 8.12%   |
| Overlay  | 8         | 3.42%   |
| Btrfs    | 4         | 1.71%   |
| Ext2     | 3         | 1.28%   |
| Xfs      | 1         | 0.43%   |
| Reiserfs | 1         | 0.43%   |
| Ext3     | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 214       | 93.04%  |
| GPT     | 9         | 3.91%   |
| MBR     | 7         | 3.04%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 92.67%  |
| Yes       | 17        | 7.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 201       | 87.01%  |
| Yes       | 30        | 12.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 40        | 17.47%  |
| ASUSTek Computer    | 35        | 15.28%  |
| Dell                | 26        | 11.35%  |
| Lenovo              | 24        | 10.48%  |
| Toshiba             | 16        | 6.99%   |
| Acer                | 15        | 6.55%   |
| Gigabyte Technology | 11        | 4.8%    |
| Samsung Electronics | 7         | 3.06%   |
| Fujitsu Siemens     | 7         | 3.06%   |
| Intel               | 6         | 2.62%   |
| Sony                | 4         | 1.75%   |
| eMachines           | 3         | 1.31%   |
| ECS                 | 3         | 1.31%   |
| ASRock              | 3         | 1.31%   |
| Unknown             | 3         | 1.31%   |
| Positivo            | 2         | 0.87%   |
| Pegatron            | 2         | 0.87%   |
| Packard Bell        | 2         | 0.87%   |
| MSI                 | 2         | 0.87%   |
| Medion              | 2         | 0.87%   |
| Gateway             | 2         | 0.87%   |
| Fujitsu             | 2         | 0.87%   |
| Apple               | 2         | 0.87%   |
| Olivetti            | 1         | 0.44%   |
| Nvidia              | 1         | 0.44%   |
| JPSaCouto           | 1         | 0.44%   |
| Itautec             | 1         | 0.44%   |
| IBM                 | 1         | 0.44%   |
| Google              | 1         | 0.44%   |
| Foxconn             | 1         | 0.44%   |
| Clevo               | 1         | 0.44%   |
| Biostar             | 1         | 0.44%   |
| AAEON               | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad 2in1 14 81CW                | 3         | 1.31%   |
| Lenovo G500 20236                          | 3         | 1.31%   |
| Unknown                                    | 3         | 1.31%   |
| Toshiba Satellite M70                      | 2         | 0.87%   |
| Toshiba Satellite L500                     | 2         | 0.87%   |
| Samsung N150P/N210P/N220P                  | 2         | 0.87%   |
| HP Compaq dc7900 Convertible Minitower     | 2         | 0.87%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.87%   |
| Fujitsu Siemens D1931                      | 2         | 0.87%   |
| Dell Inspiron N5050                        | 2         | 0.87%   |
| Acer Extensa 5630                          | 2         | 0.87%   |
| Toshiba Satellite Pro C850                 | 1         | 0.44%   |
| Toshiba Satellite L750D                    | 1         | 0.44%   |
| Toshiba Satellite L310                     | 1         | 0.44%   |
| Toshiba Satellite L300                     | 1         | 0.44%   |
| Toshiba Satellite C850-F117                | 1         | 0.44%   |
| Toshiba Satellite C660                     | 1         | 0.44%   |
| Toshiba Satellite C55D-B                   | 1         | 0.44%   |
| Toshiba QOSMIO F755                        | 1         | 0.44%   |
| Toshiba PORTEGE R500                       | 1         | 0.44%   |
| Toshiba NB520                              | 1         | 0.44%   |
| Toshiba NB500                              | 1         | 0.44%   |
| Toshiba dynabook Satellite B552/H          | 1         | 0.44%   |
| Sony VPCZ21V9E                             | 1         | 0.44%   |
| Sony VPCCW21FX                             | 1         | 0.44%   |
| Sony VGN-S55B_S                            | 1         | 0.44%   |
| Sony VGN-FW140E                            | 1         | 0.44%   |
| Samsung R610                               | 1         | 0.44%   |
| Samsung R530/R730/R540                     | 1         | 0.44%   |
| Samsung N150P                              | 1         | 0.44%   |
| Samsung N150/N210/N220                     | 1         | 0.44%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.44%   |
| Positivo N1103                             | 1         | 0.44%   |
| Positivo Mobile                            | 1         | 0.44%   |
| Pegatron FR502AA-ABZ m9355.it              | 1         | 0.44%   |
| Pegatron CQ1506LA                          | 1         | 0.44%   |
| Packard Bell EasyNote_MX45                 | 1         | 0.44%   |
| Packard Bell EasyNote TK85                 | 1         | 0.44%   |
| Olivetti CL133A                            | 1         | 0.44%   |
| Nvidia MCP7A                               | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Toshiba Satellite       | 11        | 4.8%    |
| Dell Inspiron           | 11        | 4.8%    |
| HP Compaq               | 10        | 4.37%   |
| HP Pavilion             | 8         | 3.49%   |
| Lenovo ThinkPad         | 7         | 3.06%   |
| Acer Aspire             | 7         | 3.06%   |
| Lenovo IdeaPad          | 6         | 2.62%   |
| HP EliteBook            | 5         | 2.18%   |
| Dell OptiPlex           | 5         | 2.18%   |
| Dell Latitude           | 4         | 1.75%   |
| Acer Extensa            | 4         | 1.75%   |
| Samsung N150P           | 3         | 1.31%   |
| Lenovo G500             | 3         | 1.31%   |
| HP Laptop               | 3         | 1.31%   |
| Fujitsu Siemens AMILO   | 3         | 1.31%   |
| Dell Precision          | 3         | 1.31%   |
| Unknown                 | 3         | 1.31%   |
| Packard Bell EasyNote   | 2         | 0.87%   |
| HP Stream               | 2         | 0.87%   |
| HP Mini                 | 2         | 0.87%   |
| HP 255                  | 2         | 0.87%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.87%   |
| Fujitsu Siemens D1931   | 2         | 0.87%   |
| ASUS ROG                | 2         | 0.87%   |
| Toshiba QOSMIO          | 1         | 0.44%   |
| Toshiba PORTEGE         | 1         | 0.44%   |
| Toshiba NB520           | 1         | 0.44%   |
| Toshiba NB500           | 1         | 0.44%   |
| Toshiba dynabook        | 1         | 0.44%   |
| Sony VPCZ21V9E          | 1         | 0.44%   |
| Sony VPCCW21FX          | 1         | 0.44%   |
| Sony VGN-S55B           | 1         | 0.44%   |
| Sony VGN-FW140E         | 1         | 0.44%   |
| Samsung R610            | 1         | 0.44%   |
| Samsung R530            | 1         | 0.44%   |
| Samsung N150            | 1         | 0.44%   |
| Samsung 300E4A          | 1         | 0.44%   |
| Positivo N1103          | 1         | 0.44%   |
| Positivo Mobile         | 1         | 0.44%   |
| Pegatron FR502AA-ABZ    | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 30        | 13.1%   |
| 2007    | 25        | 10.92%  |
| 2011    | 24        | 10.48%  |
| 2009    | 22        | 9.61%   |
| 2010    | 20        | 8.73%   |
| 2013    | 19        | 8.3%    |
| 2012    | 16        | 6.99%   |
| 2006    | 14        | 6.11%   |
| 2005    | 10        | 4.37%   |
| 2015    | 9         | 3.93%   |
| 2017    | 8         | 3.49%   |
| 2016    | 7         | 3.06%   |
| 2018    | 6         | 2.62%   |
| 2014    | 6         | 2.62%   |
| 2020    | 5         | 2.18%   |
| 2019    | 5         | 2.18%   |
| 2004    | 2         | 0.87%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 146       | 63.76%  |
| Desktop     | 79        | 34.5%   |
| Convertible | 3         | 1.31%   |
| Tablet      | 1         | 0.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 221       | 96.51%  |
| Enabled  | 8         | 3.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 99.56%  |
| Yes  | 1         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 72        | 30.9%   |
| 1.01-2.0   | 61        | 26.18%  |
| 4.01-8.0   | 29        | 12.45%  |
| 8.01-16.0  | 22        | 9.44%   |
| 0.51-1.0   | 17        | 7.3%    |
| 2.01-3.0   | 16        | 6.87%   |
| 16.01-24.0 | 11        | 4.72%   |
| 32.01-64.0 | 4         | 1.72%   |
| 24.01-32.0 | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 95        | 37.85%  |
| 1.01-2.0  | 94        | 37.45%  |
| 2.01-3.0  | 31        | 12.35%  |
| 0.01-0.5  | 18        | 7.17%   |
| 3.01-4.0  | 6         | 2.39%   |
| 4.01-8.0  | 5         | 1.99%   |
| 8.01-16.0 | 2         | 0.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 171       | 72.77%  |
| 2      | 48        | 20.43%  |
| 3      | 10        | 4.26%   |
| 0      | 2         | 0.85%   |
| 7      | 1         | 0.43%   |
| 6      | 1         | 0.43%   |
| 5      | 1         | 0.43%   |
| 4      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 61.9%   |
| No        | 88        | 38.1%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 92.14%  |
| No        | 18        | 7.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 83.84%  |
| No        | 37        | 16.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 58.26%  |
| Yes       | 96        | 41.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 66        | 28.7%   |
| Germany      | 19        | 8.26%   |
| Italy        | 16        | 6.96%   |
| UK           | 14        | 6.09%   |
| Brazil       | 12        | 5.22%   |
| Canada       | 9         | 3.91%   |
| Netherlands  | 8         | 3.48%   |
| Romania      | 7         | 3.04%   |
| India        | 7         | 3.04%   |
| Russia       | 6         | 2.61%   |
| Poland       | 6         | 2.61%   |
| Argentina    | 5         | 2.17%   |
| France       | 4         | 1.74%   |
| Finland      | 4         | 1.74%   |
| Sweden       | 3         | 1.3%    |
| Spain        | 3         | 1.3%    |
| Portugal     | 3         | 1.3%    |
| Mexico       | 3         | 1.3%    |
| Japan        | 3         | 1.3%    |
| Philippines  | 2         | 0.87%   |
| Peru         | 2         | 0.87%   |
| Greece       | 2         | 0.87%   |
| Bolivia      | 2         | 0.87%   |
| Australia    | 2         | 0.87%   |
| Ukraine      | 1         | 0.43%   |
| Turkey       | 1         | 0.43%   |
| Switzerland  | 1         | 0.43%   |
| South Africa | 1         | 0.43%   |
| Serbia       | 1         | 0.43%   |
| Panama       | 1         | 0.43%   |
| Norway       | 1         | 0.43%   |
| New Zealand  | 1         | 0.43%   |
| Namibia      | 1         | 0.43%   |
| Malaysia     | 1         | 0.43%   |
| Lithuania    | 1         | 0.43%   |
| Latvia       | 1         | 0.43%   |
| Kazakhstan   | 1         | 0.43%   |
| Ireland      | 1         | 0.43%   |
| Georgia      | 1         | 0.43%   |
| Ecuador      | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Charlotte              | 4         | 1.68%   |
| Bucharest              | 4         | 1.68%   |
| Villingen-Schwenningen | 3         | 1.26%   |
| Turin                  | 3         | 1.26%   |
| Toronto                | 3         | 1.26%   |
| Topeka                 | 2         | 0.84%   |
| Tokyo                  | 2         | 0.84%   |
| Tahlequah              | 2         | 0.84%   |
| Seattle                | 2         | 0.84%   |
| Perth                  | 2         | 0.84%   |
| Osasco                 | 2         | 0.84%   |
| Naples                 | 2         | 0.84%   |
| Moscow                 | 2         | 0.84%   |
| Lima                   | 2         | 0.84%   |
| Hamburg                | 2         | 0.84%   |
| Buenos Aires           | 2         | 0.84%   |
| Brunswick              | 2         | 0.84%   |
| Bengaluru              | 2         | 0.84%   |
| Airdrie                | 2         | 0.84%   |
| Zgierz                 | 1         | 0.42%   |
| York                   | 1         | 0.42%   |
| Yokohama               | 1         | 0.42%   |
| Wysokie Mazowieckie    | 1         | 0.42%   |
| Wroclaw                | 1         | 0.42%   |
| Worthing               | 1         | 0.42%   |
| Windhoek               | 1         | 0.42%   |
| West New York          | 1         | 0.42%   |
| West Chester           | 1         | 0.42%   |
| Weinheim               | 1         | 0.42%   |
| Wassenaar              | 1         | 0.42%   |
| Washington             | 1         | 0.42%   |
| Warsaw                 | 1         | 0.42%   |
| Waalwijk               | 1         | 0.42%   |
| Vitória               | 1         | 0.42%   |
| Villa María           | 1         | 0.42%   |
| Vijayawada             | 1         | 0.42%   |
| Venda do Pinheiro      | 1         | 0.42%   |
| Varna                  | 1         | 0.42%   |
| Van Vleck              | 1         | 0.42%   |
| Uddingston             | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 56        | 77     | 20.59%  |
| Seagate             | 55        | 59     | 20.22%  |
| Samsung Electronics | 27        | 36     | 9.93%   |
| Hitachi             | 26        | 35     | 9.56%   |
| Toshiba             | 20        | 21     | 7.35%   |
| Unknown             | 18        | 23     | 6.62%   |
| Kingston            | 13        | 17     | 4.78%   |
| Maxtor              | 8         | 10     | 2.94%   |
| SanDisk             | 7         | 8      | 2.57%   |
| HGST                | 4         | 5      | 1.47%   |
| Fujitsu             | 4         | 5      | 1.47%   |
| PNY                 | 3         | 4      | 1.1%    |
| Intel               | 3         | 4      | 1.1%    |
| Micron Technology   | 2         | 2      | 0.74%   |
| Integral            | 2         | 2      | 0.74%   |
| Crucial             | 2         | 3      | 0.74%   |
| China               | 2         | 2      | 0.74%   |
| Zheino              | 1         | 1      | 0.37%   |
| WD MediaMax         | 1         | 1      | 0.37%   |
| TCSUNBOW            | 1         | 1      | 0.37%   |
| SK hynix            | 1         | 1      | 0.37%   |
| SABRENT             | 1         | 1      | 0.37%   |
| Phison Electronics  | 1         | 1      | 0.37%   |
| Phison              | 1         | 2      | 0.37%   |
| Patriot             | 1         | 1      | 0.37%   |
| OCZ                 | 1         | 1      | 0.37%   |
| LITEONIT            | 1         | 1      | 0.37%   |
| KingSpec            | 1         | 1      | 0.37%   |
| Intenso             | 1         | 1      | 0.37%   |
| Goodram             | 1         | 1      | 0.37%   |
| GAMER               | 1         | 1      | 0.37%   |
| FATTYDOVE           | 1         | 1      | 0.37%   |
| Drevo               | 1         | 1      | 0.37%   |
| BHT                 | 1         | 2      | 0.37%   |
| ASMT                | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |
| Apacer              | 1         | 3      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 6         | 2.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 1.77%   |
| Seagate ST9500325AS 500GB           | 4         | 1.42%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 1.42%   |
| Unknown MMC Card  16GB              | 3         | 1.06%   |
| Toshiba MQ01ABF050 500GB            | 3         | 1.06%   |
| Seagate ST9320325AS 320GB           | 3         | 1.06%   |
| Seagate ST9250315AS 250GB           | 3         | 1.06%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 1.06%   |
| SanDisk SDSSDA120G 120GB            | 3         | 1.06%   |
| Kingston SA400S37240G 240GB SSD     | 3         | 1.06%   |
| Hitachi HTS545025B9A300 250GB       | 3         | 1.06%   |
| Hitachi HDT721016SLA380 160GB       | 3         | 1.06%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 0.71%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.71%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.71%   |
| Unknown SD/MMC/MS PRO 64GB          | 2         | 0.71%   |
| Unknown MMC Card  64GB              | 2         | 0.71%   |
| Toshiba MK5055GSX 500GB             | 2         | 0.71%   |
| Seagate ST9160314AS 160GB           | 2         | 0.71%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.71%   |
| Seagate ST3500418AS 500GB           | 2         | 0.71%   |
| Seagate ST3250310AS 250GB           | 2         | 0.71%   |
| Seagate ST3160813AS 160GB           | 2         | 0.71%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 0.71%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.71%   |
| Samsung SSD 850 EVO 500GB           | 2         | 0.71%   |
| Samsung HM160HI 160GB               | 2         | 0.71%   |
| Maxtor STM3160215AS 160GB           | 2         | 0.71%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.71%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 0.71%   |
| Hitachi HDS721050CLA362 500GB       | 2         | 0.71%   |
| Hitachi HDP725050GLA360 500GB       | 2         | 0.71%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.71%   |
| Zheino CHN 25SATAA3 120 120GB SSD   | 1         | 0.35%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 59     | 29.57%  |
| WDC                 | 53        | 74     | 28.49%  |
| Hitachi             | 26        | 35     | 13.98%  |
| Toshiba             | 20        | 21     | 10.75%  |
| Samsung Electronics | 13        | 16     | 6.99%   |
| Maxtor              | 8         | 10     | 4.3%    |
| HGST                | 4         | 5      | 2.15%   |
| Fujitsu             | 4         | 5      | 2.15%   |
| Unknown             | 2         | 2      | 1.08%   |
| WD MediaMax         | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 17     | 20.97%  |
| Samsung Electronics | 12        | 18     | 19.35%  |
| SanDisk             | 7         | 8      | 11.29%  |
| WDC                 | 3         | 3      | 4.84%   |
| PNY                 | 3         | 4      | 4.84%   |
| Intel               | 3         | 4      | 4.84%   |
| Integral            | 2         | 2      | 3.23%   |
| Crucial             | 2         | 3      | 3.23%   |
| China               | 2         | 2      | 3.23%   |
| Zheino              | 1         | 1      | 1.61%   |
| TCSUNBOW            | 1         | 1      | 1.61%   |
| Patriot             | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| KingSpec            | 1         | 1      | 1.61%   |
| Goodram             | 1         | 1      | 1.61%   |
| GAMER               | 1         | 1      | 1.61%   |
| FATTYDOVE           | 1         | 1      | 1.61%   |
| Drevo               | 1         | 1      | 1.61%   |
| BHT                 | 1         | 2      | 1.61%   |
| ASMT                | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| Apacer              | 1         | 3      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 167       | 228    | 66.53%  |
| SSD     | 61        | 79     | 24.3%   |
| MMC     | 16        | 21     | 6.37%   |
| NVMe    | 4         | 6      | 1.59%   |
| Unknown | 3         | 3      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 210       | 303    | 88.61%  |
| MMC  | 16        | 21     | 6.75%   |
| SAS  | 7         | 7      | 2.95%   |
| NVMe | 4         | 6      | 1.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 188       | 252    | 80.69%  |
| 0.51-1.0   | 35        | 41     | 15.02%  |
| 1.01-2.0   | 7         | 9      | 3%      |
| 3.01-4.0   | 1         | 1      | 0.43%   |
| 2.01-3.0   | 1         | 3      | 0.43%   |
| 4.01-10.0  | 1         | 1      | 0.43%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 36.44%  |
| 251-500        | 47        | 19.92%  |
| 51-100         | 31        | 13.14%  |
| 21-50          | 26        | 11.02%  |
| 501-1000       | 25        | 10.59%  |
| 1-20           | 10        | 4.24%   |
| 1001-2000      | 6         | 2.54%   |
| 2001-3000      | 2         | 0.85%   |
| Unknown        | 2         | 0.85%   |
| More than 3000 | 1         | 0.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 150       | 61.98%  |
| 21-50     | 46        | 19.01%  |
| 51-100    | 22        | 9.09%   |
| 101-250   | 15        | 6.2%    |
| 501-1000  | 5         | 2.07%   |
| Unknown   | 2         | 0.83%   |
| 251-500   | 1         | 0.41%   |
| 1001-2000 | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB          | 1         | 1      | 16.67%  |
| Seagate ST9500420AS 500GB          | 1         | 1      | 16.67%  |
| Seagate ST9250315AS 250GB          | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 16.67%  |
| Seagate ST31500341AS 1TB           | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 83.33%  |
| WDC     | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 100%    |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 213       | 315    | 91.81%  |
| Works    | 13        | 16     | 5.6%    |
| Malfunc  | 6         | 6      | 2.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 159       | 68.83%  |
| AMD                              | 32        | 13.85%  |
| Nvidia                           | 12        | 5.19%   |
| VIA Technologies                 | 6         | 2.6%    |
| Silicon Integrated Systems [SiS] | 5         | 2.16%   |
| JMicron Technology               | 5         | 2.16%   |
| Samsung Electronics              | 3         | 1.3%    |
| Marvell Technology Group         | 3         | 1.3%    |
| ULi Electronics                  | 1         | 0.43%   |
| Silicon Image                    | 1         | 0.43%   |
| Phison Electronics               | 1         | 0.43%   |
| Micron Technology                | 1         | 0.43%   |
| LSI Logic / Symbios Logic        | 1         | 0.43%   |
| ASMedia Technology               | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 19        | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 5.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 5.54%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 4.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 11        | 3.58%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 11        | 3.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 10        | 3.26%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 10        | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 2.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 1.95%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 6         | 1.95%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 5         | 1.63%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 5         | 1.63%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 5         | 1.63%   |
| Nvidia MCP61 SATA Controller                                                   | 5         | 1.63%   |
| Nvidia MCP61 IDE                                                               | 5         | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.63%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 5         | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.3%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4         | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.3%    |
| Intel 4 Series Chipset PT IDER Controller                                      | 4         | 1.3%    |
| Intel SATA Controller [RAID mode]                                              | 3         | 0.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 3         | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 3         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 3         | 0.98%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3         | 0.98%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 0.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.98%   |
| AMD IXP SB4x0 IDE Controller                                                   | 3         | 0.98%   |
| VIA VT8237/8251 Serial ATA Controller                                          | 2         | 0.65%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 2         | 0.65%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2         | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.65%   |
| JMicron JMB368 IDE controller                                                  | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 137       | 55.24%  |
| IDE  | 94        | 37.9%   |
| RAID | 12        | 4.84%   |
| NVMe | 4         | 1.61%   |
| SAS  | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 188       | 82.1%   |
| AMD          | 40        | 17.47%  |
| CentaurHauls | 1         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 8         | 3.49%   |
| Intel Pentium M processor 1.73GHz           | 5         | 2.18%   |
| Intel Atom CPU N450 @ 1.66GHz               | 5         | 2.18%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4         | 1.75%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.31%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 3         | 1.31%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 3         | 1.31%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 1.31%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 1.31%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.31%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 1.31%   |
| Intel Atom CPU N455 @ 1.66GHz               | 3         | 1.31%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.87%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.87%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.87%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 0.87%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 0.87%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 2         | 0.87%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 0.87%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.87%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.87%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 0.87%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 0.87%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 0.87%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 0.87%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 0.87%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2         | 0.87%   |
| Intel Celeron CPU 925 @ 2.30GHz             | 2         | 0.87%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 0.87%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 0.87%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 2         | 0.87%   |
| Intel Celeron CPU 1017U @ 1.60GHz           | 2         | 0.87%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 0.87%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 0.87%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2         | 0.87%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 0.87%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.44%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1         | 0.44%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 27        | 11.79%  |
| Intel Celeron           | 26        | 11.35%  |
| Intel Core i5           | 19        | 8.3%    |
| Intel Core i7           | 16        | 6.99%   |
| Intel Pentium           | 14        | 6.11%   |
| Intel Core 2 Duo        | 13        | 5.68%   |
| Intel Core i3           | 12        | 5.24%   |
| Intel Pentium Dual-Core | 11        | 4.8%    |
| Intel Genuine           | 11        | 4.8%    |
| Intel Core 2 Quad       | 8         | 3.49%   |
| Intel Core 2            | 7         | 3.06%   |
| AMD Athlon 64 X2        | 7         | 3.06%   |
| Intel Pentium M         | 5         | 2.18%   |
| Intel Pentium Dual      | 5         | 2.18%   |
| Intel Pentium 4         | 5         | 2.18%   |
| Other                   | 4         | 1.75%   |
| Intel Xeon              | 3         | 1.31%   |
| AMD E                   | 3         | 1.31%   |
| AMD A8                  | 3         | 1.31%   |
| Intel Pentium D         | 2         | 0.87%   |
| AMD FX                  | 2         | 0.87%   |
| AMD E2                  | 2         | 0.87%   |
| AMD E1                  | 2         | 0.87%   |
| AMD A6                  | 2         | 0.87%   |
| AMD A4                  | 2         | 0.87%   |
| Intel Core Duo          | 1         | 0.44%   |
| Intel Celeron M         | 1         | 0.44%   |
| Intel Celeron Dual-Core | 1         | 0.44%   |
| CentaurHauls VIA C7     | 1         | 0.44%   |
| AMD Turion 64 X2 Mobile | 1         | 0.44%   |
| AMD Turion 64 Mobile    | 1         | 0.44%   |
| AMD Sempron             | 1         | 0.44%   |
| AMD Ryzen 5             | 1         | 0.44%   |
| AMD Ryzen 3             | 1         | 0.44%   |
| AMD Phenom II X4        | 1         | 0.44%   |
| AMD Phenom II           | 1         | 0.44%   |
| AMD Phenom              | 1         | 0.44%   |
| AMD C-60                | 1         | 0.44%   |
| AMD Athlon II X4        | 1         | 0.44%   |
| AMD Athlon II X2        | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 125       | 54.59%  |
| 1      | 54        | 23.58%  |
| 4      | 45        | 19.65%  |
| 6      | 4         | 1.75%   |
| 3      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 229       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 62.88%  |
| 2      | 85        | 37.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 80.95%  |
| 32-bit         | 28        | 12.12%  |
| Unknown        | 16        | 6.93%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 26        | 11.16%  |
| Unknown    | 20        | 8.58%   |
| 0x306a9    | 18        | 7.73%   |
| 0x206a7    | 17        | 7.3%    |
| 0x6fd      | 12        | 5.15%   |
| 0x106ca    | 11        | 4.72%   |
| 0x106c2    | 11        | 4.72%   |
| 0x10661    | 7         | 3%      |
| 0x806e9    | 6         | 2.58%   |
| 0x406c4    | 6         | 2.58%   |
| 0x30678    | 6         | 2.58%   |
| 0x20655    | 6         | 2.58%   |
| 0x6f6      | 5         | 2.15%   |
| 0x6e8      | 5         | 2.15%   |
| 0x6d8      | 5         | 2.15%   |
| 0xf41      | 4         | 1.72%   |
| 0x6ec      | 4         | 1.72%   |
| 0x05000119 | 4         | 1.72%   |
| 0x010000c8 | 4         | 1.72%   |
| 0x806ec    | 3         | 1.29%   |
| 0x6fb      | 3         | 1.29%   |
| 0x40651    | 3         | 1.29%   |
| 0x10676    | 3         | 1.29%   |
| 0x07030105 | 3         | 1.29%   |
| 0x06006705 | 3         | 1.29%   |
| 0x06001119 | 3         | 1.29%   |
| 0x6f2      | 2         | 0.86%   |
| 0x306d4    | 2         | 0.86%   |
| 0x306c3    | 2         | 0.86%   |
| 0x20652    | 2         | 0.86%   |
| 0x07030106 | 2         | 0.86%   |
| 0xf65      | 1         | 0.43%   |
| 0xf62      | 1         | 0.43%   |
| 0xf47      | 1         | 0.43%   |
| 0xf43      | 1         | 0.43%   |
| 0xf33      | 1         | 0.43%   |
| 0x906ea    | 1         | 0.43%   |
| 0x806c1    | 1         | 0.43%   |
| 0x706a1    | 1         | 0.43%   |
| 0x506c9    | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Penryn        | 31        | 13.54%  |
| Core          | 29        | 12.66%  |
| Bonnell       | 23        | 10.04%  |
| IvyBridge     | 19        | 8.3%    |
| SandyBridge   | 17        | 7.42%   |
| P6            | 14        | 6.11%   |
| Silvermont    | 12        | 5.24%   |
| Westmere      | 10        | 4.37%   |
| KabyLake      | 10        | 4.37%   |
| K8 Hammer     | 10        | 4.37%   |
| NetBurst      | 9         | 3.93%   |
| Haswell       | 7         | 3.06%   |
| K10           | 6         | 2.62%   |
| Puma          | 5         | 2.18%   |
| Piledriver    | 5         | 2.18%   |
| Excavator     | 5         | 2.18%   |
| Bobcat        | 5         | 2.18%   |
| Broadwell     | 3         | 1.31%   |
| Zen+          | 1         | 0.44%   |
| Zen 2         | 1         | 0.44%   |
| Zen           | 1         | 0.44%   |
| TigerLake     | 1         | 0.44%   |
| Nehalem       | 1         | 0.44%   |
| Jaguar        | 1         | 0.44%   |
| Goldmont plus | 1         | 0.44%   |
| Goldmont      | 1         | 0.44%   |
| Unknown       | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 147       | 61.76%  |
| AMD                              | 45        | 18.91%  |
| Nvidia                           | 38        | 15.97%  |
| VIA Technologies                 | 4         | 1.68%   |
| Silicon Integrated Systems [SiS] | 4         | 1.68%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 21        | 7.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 6.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 12        | 4.44%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 10        | 3.7%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 3.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.22%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.85%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 5         | 1.85%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 1.48%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 4         | 1.48%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.11%   |
| Intel HD Graphics 620                                                                    | 3         | 1.11%   |
| Intel HD Graphics 610                                                                    | 3         | 1.11%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.11%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 1.11%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.11%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.11%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.11%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.74%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.74%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.74%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.74%   |
| Nvidia G94 [GeForce 9600 GS]                                                             | 2         | 0.74%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 2         | 0.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.74%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 2         | 0.74%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.74%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 2         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 60.26%  |
| 1 x AMD        | 40        | 17.47%  |
| 1 x Nvidia     | 31        | 13.54%  |
| Intel + Nvidia | 7         | 3.06%   |
| 2 x AMD        | 4         | 1.75%   |
| 1 x VIA        | 4         | 1.75%   |
| 1 x SiS        | 4         | 1.75%   |
| Intel + AMD    | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 205       | 88.74%  |
| Proprietary | 14        | 6.06%   |
| Unknown     | 12        | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 155       | 67.39%  |
| 0.01-0.5   | 45        | 19.57%  |
| 0.51-1.0   | 15        | 6.52%   |
| 1.01-2.0   | 10        | 4.35%   |
| 3.01-4.0   | 3         | 1.3%    |
| 7.01-8.0   | 1         | 0.43%   |
| 8.01-16.0  | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 37        | 16.44%  |
| AU Optronics            | 31        | 13.78%  |
| LG Display              | 18        | 8%      |
| Acer                    | 13        | 5.78%   |
| LG Philips              | 11        | 4.89%   |
| Dell                    | 11        | 4.89%   |
| Chi Mei Optoelectronics | 10        | 4.44%   |
| HannStar                | 8         | 3.56%   |
| Goldstar                | 8         | 3.56%   |
| BOE                     | 7         | 3.11%   |
| Hewlett-Packard         | 6         | 2.67%   |
| Chimei Innolux          | 6         | 2.67%   |
| BenQ                    | 6         | 2.67%   |
| Sony                    | 5         | 2.22%   |
| Lenovo                  | 5         | 2.22%   |
| CPT                     | 4         | 1.78%   |
| AOC                     | 3         | 1.33%   |
| Ancor Communications    | 3         | 1.33%   |
| ViewSonic               | 2         | 0.89%   |
| Sharp                   | 2         | 0.89%   |
| LG Electronics          | 2         | 0.89%   |
| InfoVision              | 2         | 0.89%   |
| Hitachi                 | 2         | 0.89%   |
| Apple                   | 2         | 0.89%   |
| Vizio                   | 1         | 0.44%   |
| VIZ                     | 1         | 0.44%   |
| Vestel Elektronik       | 1         | 0.44%   |
| Toshiba                 | 1         | 0.44%   |
| Seiko/Epson             | 1         | 0.44%   |
| Sceptre Tech            | 1         | 0.44%   |
| Quanta Display          | 1         | 0.44%   |
| Philips                 | 1         | 0.44%   |
| Panasonic               | 1         | 0.44%   |
| Optoma                  | 1         | 0.44%   |
| OEM                     | 1         | 0.44%   |
| MPI                     | 1         | 0.44%   |
| Lite-On                 | 1         | 0.44%   |
| KTC                     | 1         | 0.44%   |
| KDC                     | 1         | 0.44%   |
| Insignia                | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 6         | 2.6%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 1.3%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.3%    |
| BOE LCD Monitor BOE0705 1366x768 309x173mm 13.9-inch                     | 3         | 1.3%    |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch  | 2         | 0.87%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.87%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 0.87%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.87%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.87%   |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                         | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 0.87%   |
| Acer G276HL ACR0300 1920x1080 598x336mm 27.0-inch                        | 2         | 0.87%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.43%   |
| VIZ LCD Monitor D50-D1 1920x1080                                         | 1         | 0.43%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch                 | 1         | 0.43%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 1         | 0.43%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch     | 1         | 0.43%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.43%   |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                             | 1         | 0.43%   |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                      | 1         | 0.43%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.43%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.43%   |
| Sony LCD Monitor TV                                                      | 1         | 0.43%   |
| Sharp LCD SHP1047 1920x1080                                              | 1         | 0.43%   |
| Sharp LCD SHP0FF0 1360x768                                               | 1         | 0.43%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.43%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                   | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 521x293mm 23.5-inch     | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch     | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch     | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch      | 1         | 0.43%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch      | 1         | 0.43%   |
| Samsung Electronics SME1920 SAM06B7 1360x768 410x230mm 18.5-inch         | 1         | 0.43%   |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch        | 1         | 0.43%   |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch        | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 70        | 30.97%  |
| 1920x1080 (FHD)    | 44        | 19.47%  |
| 1280x800 (WXGA)    | 22        | 9.73%   |
| 1280x1024 (SXGA)   | 13        | 5.75%   |
| 1024x600           | 13        | 5.75%   |
| 1600x900 (HD+)     | 10        | 4.42%   |
| 1024x768 (XGA)     | 9         | 3.98%   |
| 2560x1440 (QHD)    | 6         | 2.65%   |
| 1440x900 (WXGA+)   | 6         | 2.65%   |
| 3840x2160 (4K)     | 5         | 2.21%   |
| 1680x1050 (WSXGA+) | 5         | 2.21%   |
| 1360x768           | 5         | 2.21%   |
| 1920x540           | 3         | 1.33%   |
| 2560x1080          | 2         | 0.88%   |
| 1920x1200 (WUXGA)  | 2         | 0.88%   |
| 1024x576           | 2         | 0.88%   |
| Unknown            | 2         | 0.88%   |
| 3840x1080          | 1         | 0.44%   |
| 2624x1200          | 1         | 0.44%   |
| 2048x1152          | 1         | 0.44%   |
| 1600x1200          | 1         | 0.44%   |
| 1400x1050          | 1         | 0.44%   |
| 1280x768           | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 32.3%   |
| 14      | 16        | 7.08%   |
| Unknown | 15        | 6.64%   |
| 13      | 14        | 6.19%   |
| 17      | 13        | 5.75%   |
| 10      | 13        | 5.75%   |
| 19      | 9         | 3.98%   |
| 27      | 8         | 3.54%   |
| 24      | 8         | 3.54%   |
| 11      | 8         | 3.54%   |
| 18      | 7         | 3.1%    |
| 21      | 6         | 2.65%   |
| 84      | 5         | 2.21%   |
| 31      | 5         | 2.21%   |
| 22      | 5         | 2.21%   |
| 23      | 3         | 1.33%   |
| 20      | 3         | 1.33%   |
| 12      | 3         | 1.33%   |
| 8       | 3         | 1.33%   |
| 34      | 2         | 0.88%   |
| 74      | 1         | 0.44%   |
| 41      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 39      | 1         | 0.44%   |
| 32      | 1         | 0.44%   |
| 26      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 44.44%  |
| 201-300     | 31        | 13.78%  |
| 401-500     | 23        | 10.22%  |
| 501-600     | 19        | 8.44%   |
| 351-400     | 17        | 7.56%   |
| Unknown     | 15        | 6.67%   |
| 1501-2000   | 6         | 2.67%   |
| 601-700     | 5         | 2.22%   |
| 701-800     | 3         | 1.33%   |
| 101-200     | 3         | 1.33%   |
| 801-900     | 2         | 0.89%   |
| 901-1000    | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 139       | 65.88%  |
| 16/10   | 33        | 15.64%  |
| 4/3     | 12        | 5.69%   |
| Unknown | 11        | 5.21%   |
| 5/4     | 10        | 4.74%   |
| 6/5     | 3         | 1.42%   |
| 21/9    | 2         | 0.95%   |
| 1.98    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 32%     |
| 81-90          | 24        | 10.67%  |
| 151-200        | 17        | 7.56%   |
| 201-250        | 16        | 7.11%   |
| Unknown        | 15        | 6.67%   |
| 41-50          | 13        | 5.78%   |
| 141-150        | 12        | 5.33%   |
| 351-500        | 9         | 4%      |
| 51-60          | 8         | 3.56%   |
| 301-350        | 7         | 3.11%   |
| More than 1000 | 6         | 2.67%   |
| 121-130        | 6         | 2.67%   |
| 71-80          | 3         | 1.33%   |
| 61-70          | 3         | 1.33%   |
| 1-40           | 3         | 1.33%   |
| 251-300        | 3         | 1.33%   |
| 501-1000       | 3         | 1.33%   |
| 91-100         | 3         | 1.33%   |
| 131-140        | 2         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 89        | 40.64%  |
| 101-120 | 81        | 36.99%  |
| 121-160 | 28        | 12.79%  |
| Unknown | 15        | 6.85%   |
| 1-50    | 4         | 1.83%   |
| 161-240 | 2         | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 196       | 84.48%  |
| 2     | 25        | 10.78%  |
| 0     | 9         | 3.88%   |
| 3     | 2         | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 112       | 29.17%  |
| Intel                             | 72        | 18.75%  |
| Qualcomm Atheros                  | 62        | 16.15%  |
| Broadcom                          | 42        | 10.94%  |
| Marvell Technology Group          | 15        | 3.91%   |
| Broadcom Limited                  | 13        | 3.39%   |
| Nvidia                            | 10        | 2.6%    |
| Ralink Technology                 | 9         | 2.34%   |
| Ralink                            | 6         | 1.56%   |
| VIA Technologies                  | 4         | 1.04%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.78%   |
| Qualcomm Atheros Communications   | 3         | 0.78%   |
| Gemtek                            | 3         | 0.78%   |
| D-Link                            | 3         | 0.78%   |
| ASUSTek Computer                  | 3         | 0.78%   |
| Samsung Electronics               | 2         | 0.52%   |
| JMicron Technology                | 2         | 0.52%   |
| 3Com                              | 2         | 0.52%   |
| Xiaomi                            | 1         | 0.26%   |
| TP-Link                           | 1         | 0.26%   |
| Spreadtrum Communications         | 1         | 0.26%   |
| NetGear                           | 1         | 0.26%   |
| Micro Star International          | 1         | 0.26%   |
| MediaTek                          | 1         | 0.26%   |
| Linksys                           | 1         | 0.26%   |
| LG Electronics                    | 1         | 0.26%   |
| Huawei Technologies               | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| DisplayLink                       | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| BUFFALO                           | 1         | 0.26%   |
| Belkin Components                 | 1         | 0.26%   |
| Attansic Technology               | 1         | 0.26%   |
| ASIX Electronics                  | 1         | 0.26%   |
| AMD                               | 1         | 0.26%   |
| ADMtek                            | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 49        | 11.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 31        | 7.18%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 3.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 12        | 2.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 2.08%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 7         | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.62%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.16%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 1.16%   |
| Nvidia MCP61 Ethernet                                                   | 5         | 1.16%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.93%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.93%   |
| Intel Wireless 3165                                                     | 4         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.93%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 0.93%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 4         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.93%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 3         | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.69%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.69%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.69%   |
| Intel Wireless 7265                                                     | 3         | 0.69%   |
| Intel Wireless 7260                                                     | 3         | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 24.26%  |
| Qualcomm Atheros                | 44        | 21.78%  |
| Realtek Semiconductor           | 36        | 17.82%  |
| Broadcom                        | 30        | 14.85%  |
| Ralink Technology               | 9         | 4.46%   |
| Broadcom Limited                | 7         | 3.47%   |
| Ralink                          | 6         | 2.97%   |
| Qualcomm Atheros Communications | 3         | 1.49%   |
| Gemtek                          | 3         | 1.49%   |
| D-Link                          | 3         | 1.49%   |
| ASUSTek Computer                | 3         | 1.49%   |
| VIA Technologies                | 1         | 0.5%    |
| TP-Link                         | 1         | 0.5%    |
| Samsung Electronics             | 1         | 0.5%    |
| NetGear                         | 1         | 0.5%    |
| Micro Star International        | 1         | 0.5%    |
| Marvell Technology Group        | 1         | 0.5%    |
| Linksys                         | 1         | 0.5%    |
| BUFFALO                         | 1         | 0.5%    |
| Belkin Components               | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 6.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 9         | 4.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 3.45%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.46%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 2.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.97%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.97%   |
| Intel Wireless 3165                                                     | 4         | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.97%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.97%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 1.48%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.48%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 1.48%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.48%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 1.48%   |
| Intel Wireless 7265                                                     | 3         | 1.48%   |
| Intel Wireless 7260                                                     | 3         | 1.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.48%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 1.48%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 3         | 1.48%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.99%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 2         | 0.99%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.99%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.99%   |
| Intel WiFi Link 5100                                                    | 2         | 0.99%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.99%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 97        | 44.09%  |
| Intel                            | 35        | 15.91%  |
| Qualcomm Atheros                 | 23        | 10.45%  |
| Broadcom                         | 15        | 6.82%   |
| Marvell Technology Group         | 14        | 6.36%   |
| Nvidia                           | 10        | 4.55%   |
| Broadcom Limited                 | 7         | 3.18%   |
| VIA Technologies                 | 3         | 1.36%   |
| Silicon Integrated Systems [SiS] | 3         | 1.36%   |
| JMicron Technology               | 2         | 0.91%   |
| 3Com                             | 2         | 0.91%   |
| Xiaomi                           | 1         | 0.45%   |
| Spreadtrum Communications        | 1         | 0.45%   |
| Samsung Electronics              | 1         | 0.45%   |
| MediaTek                         | 1         | 0.45%   |
| LG Electronics                   | 1         | 0.45%   |
| DisplayLink                      | 1         | 0.45%   |
| Attansic Technology              | 1         | 0.45%   |
| ASIX Electronics                 | 1         | 0.45%   |
| ADMtek                           | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 22.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 14.03%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 5.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 7         | 3.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 2.26%   |
| Nvidia MCP61 Ethernet                                             | 5         | 2.26%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 1.81%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3         | 1.36%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 1.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.36%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.36%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 1.36%   |
| Intel 82566DM Gigabit Network Connection                          | 3         | 1.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.9%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.9%    |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.9%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.9%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.9%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.9%    |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 2         | 0.9%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2         | 0.9%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.9%    |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.45%   |
| Spreadtrum Nokia G21                                              | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.45%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.45%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 210       | 51.22%  |
| WiFi     | 192       | 46.83%  |
| Modem    | 8         | 1.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 152       | 63.07%  |
| Ethernet | 89        | 36.93%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 140       | 61.14%  |
| 1     | 81        | 35.37%  |
| 0     | 6         | 2.62%   |
| 3     | 2         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 214       | 92.64%  |
| Yes  | 17        | 7.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 20.62%  |
| Qualcomm Atheros Communications | 13        | 13.4%   |
| Broadcom                        | 11        | 11.34%  |
| Cambridge Silicon Radio         | 10        | 10.31%  |
| Realtek Semiconductor           | 5         | 5.15%   |
| Hewlett-Packard                 | 5         | 5.15%   |
| Toshiba                         | 4         | 4.12%   |
| Lite-On Technology              | 4         | 4.12%   |
| Foxconn International           | 4         | 4.12%   |
| Foxconn / Hon Hai               | 4         | 4.12%   |
| IMC Networks                    | 3         | 3.09%   |
| ASUSTek Computer                | 3         | 3.09%   |
| Ralink                          | 2         | 2.06%   |
| Dell                            | 2         | 2.06%   |
| Apple                           | 2         | 2.06%   |
| Alps Electric                   | 2         | 2.06%   |
| Primax Electronics              | 1         | 1.03%   |
| Kensington                      | 1         | 1.03%   |
| Fujitsu Siemens Computers       | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 10.31%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 10.31%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 5.15%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 5.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 5.15%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 4.12%   |
| Realtek Bluetooth Radio                             | 3         | 3.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 3.09%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.06%   |
| Ralink RT3290 Bluetooth                             | 2         | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.06%   |
| Intel AX201 Bluetooth                               | 2         | 2.06%   |
| Dell DW375 Bluetooth Module                         | 2         | 2.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.06%   |
| ASUS Bluetooth Radio                                | 2         | 2.06%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.03%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.03%   |
| Toshiba Bluetooth Device                            | 1         | 1.03%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.03%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.03%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.03%   |
| Lite-On Bluetooth Device                            | 1         | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.03%   |
| Kensington Bluetooth EDR Dongle                     | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.03%   |
| Intel AX200 Bluetooth                               | 1         | 1.03%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.03%   |
| IMC Networks Bluetooth module                       | 1         | 1.03%   |
| IMC Networks Bluetooth Device                       | 1         | 1.03%   |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 1.03%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.03%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.03%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.03%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 167       | 63.02%  |
| AMD                                             | 43        | 16.23%  |
| Nvidia                                          | 30        | 11.32%  |
| VIA Technologies                                | 6         | 2.26%   |
| C-Media Electronics                             | 5         | 1.89%   |
| Silicon Integrated Systems [SiS]                | 4         | 1.51%   |
| Creative Labs                                   | 4         | 1.51%   |
| ULi Electronics                                 | 1         | 0.38%   |
| Logitech                                        | 1         | 0.38%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.38%   |
| Generalplus Technology                          | 1         | 0.38%   |
| Creative Technology                             | 1         | 0.38%   |
| Corsair                                         | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 42        | 13.95%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 26        | 8.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 6.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 3.65%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 1.99%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 6         | 1.99%   |
| Nvidia MCP61 High Definition Audio                                                                | 5         | 1.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.66%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 1.33%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.33%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 1.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 1.33%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1%      |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 3         | 1%      |
| Nvidia High Definition Audio Controller                                                           | 3         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1%      |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1%      |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1%      |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1%      |
| AMD High Definition Audio Controller                                                              | 3         | 1%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 1%      |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 1%      |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.66%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.66%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.66%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 2         | 0.66%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 14        | 25.93%  |
| Samsung Electronics | 10        | 18.52%  |
| SK hynix            | 7         | 12.96%  |
| Micron Technology   | 4         | 7.41%   |
| Kingston            | 4         | 7.41%   |
| Crucial             | 3         | 5.56%   |
| Corsair             | 2         | 3.7%    |
| Toshiba             | 1         | 1.85%   |
| Smart               | 1         | 1.85%   |
| Ramaxel Technology  | 1         | 1.85%   |
| Nanya Technology    | 1         | 1.85%   |
| Infineon            | 1         | 1.85%   |
| G.Skill             | 1         | 1.85%   |
| Elpida              | 1         | 1.85%   |
| A-DATA Technology   | 1         | 1.85%   |
| 48spaces            | 1         | 1.85%   |
| Unknown             | 1         | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 3.28%   |
| Unknown RAM Module SODIMM DDR                               | 1         | 1.64%   |
| Unknown RAM Module 4GB SODIMM DDR3                          | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM SDRAM                         | 1         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 1         | 1.64%   |
| Unknown RAM Module 2GB DIMM DDR2                            | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DRAM                       | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s              | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s              | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s              | 1         | 1.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3                       | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM SDRAM                         | 1         | 1.64%   |
| Unknown RAM Module 1GB DIMM DDR2                            | 1         | 1.64%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                | 1         | 1.64%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                      | 1         | 1.64%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s                    | 1         | 1.64%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s          | 1         | 1.64%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s      | 1         | 1.64%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s        | 1         | 1.64%   |
| SK hynix RAM Module 512MB DIMM DDR2 533MT/s                 | 1         | 1.64%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                  | 1         | 1.64%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s      | 1         | 1.64%   |
| SK hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s        | 1         | 1.64%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                | 1         | 1.64%   |
| Samsung RAM M471B5674-M0-YK0 4096MB Chip DDR3 1600MT/s      | 1         | 1.64%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s    | 1         | 1.64%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 1         | 1.64%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR 667MT/s        | 1         | 1.64%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s         | 1         | 1.64%   |
| Samsung RAM M378B2873FHS-CH9 1024MB DIMM DDR3 1333MT/s      | 1         | 1.64%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.64%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2GB DIMM DDR3 1333MT/s          | 1         | 1.64%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 33        | 64.71%  |
| DDR2    | 7         | 13.73%  |
| SDRAM   | 3         | 5.88%   |
| DDR     | 3         | 5.88%   |
| DDR4    | 2         | 3.92%   |
| Unknown | 2         | 3.92%   |
| DRAM    | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 34        | 68%     |
| DIMM         | 14        | 28%     |
| Row Of Chips | 1         | 2%      |
| Chip         | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 20        | 35.71%  |
| 2048    | 17        | 30.36%  |
| 1024    | 8         | 14.29%  |
| 8192    | 7         | 12.5%   |
| 16384   | 1         | 1.79%   |
| 512     | 1         | 1.79%   |
| 256     | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 18        | 32.73%  |
| 1333    | 9         | 16.36%  |
| Unknown | 8         | 14.55%  |
| 1334    | 3         | 5.45%   |
| 800     | 3         | 5.45%   |
| 1066    | 2         | 3.64%   |
| 667     | 2         | 3.64%   |
| 41632   | 1         | 1.82%   |
| 3200    | 1         | 1.82%   |
| 2866    | 1         | 1.82%   |
| 2400    | 1         | 1.82%   |
| 1867    | 1         | 1.82%   |
| 1866    | 1         | 1.82%   |
| 1067    | 1         | 1.82%   |
| 533     | 1         | 1.82%   |
| 320     | 1         | 1.82%   |
| 100     | 1         | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 40%     |
| Seiko Epson         | 1         | 20%     |
| Samsung Electronics | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson XP-243 245 247 Series    | 1         | 20%     |
| Samsung ML-216x Series Laser Printer | 1         | 20%     |
| HP OfficeJet 5200 series             | 1         | 20%     |
| Brother HL-L2350DW series            | 1         | 20%     |
| Brother HL-L2340D series             | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 26.98%  |
| Acer                                   | 12        | 9.52%   |
| Suyin                                  | 10        | 7.94%   |
| IMC Networks                           | 10        | 7.94%   |
| Realtek Semiconductor                  | 9         | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.56%   |
| Z-Star Microelectronics                | 6         | 4.76%   |
| Microdia                               | 6         | 4.76%   |
| Sunplus Innovation Technology          | 5         | 3.97%   |
| Ricoh                                  | 5         | 3.97%   |
| Syntek                                 | 3         | 2.38%   |
| Silicon Motion                         | 3         | 2.38%   |
| Importek                               | 3         | 2.38%   |
| Samsung Electronics                    | 2         | 1.59%   |
| Logitech                               | 2         | 1.59%   |
| Cubeternet                             | 2         | 1.59%   |
| Lite-On Technology                     | 1         | 0.79%   |
| GEO Semi                               | 1         | 0.79%   |
| DigiTech                               | 1         | 0.79%   |
| Aveo Technology                        | 1         | 0.79%   |
| Apple                                  | 1         | 0.79%   |
| ALi                                    | 1         | 0.79%   |
| Alcor Micro                            | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 4         | 3.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 4         | 3.17%   |
| Acer EasyCamera                                             | 4         | 3.17%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 2.38%   |
| IMC Networks UVC VGA Webcam                                 | 3         | 2.38%   |
| Chicony USB 2.0 Camera                                      | 3         | 2.38%   |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 2.38%   |
| Acer Lenovo Integrated Webcam                               | 3         | 2.38%   |
| Samsung Galaxy A5 (MTP)                                     | 2         | 1.59%   |
| Ricoh Sony Vaio Integrated Webcam                           | 2         | 1.59%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.59%   |
| Realtek Lenovo EasyCamera                                   | 2         | 1.59%   |
| Realtek Integrated Webcam                                   | 2         | 1.59%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 1.59%   |
| Importek HP Webcam-50                                       | 2         | 1.59%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.59%   |
| IMC Networks Integrated Webcam                              | 2         | 1.59%   |
| Chicony VGA Webcam                                          | 2         | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.59%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.59%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 2         | 1.59%   |
| Acer Integrated Camera                                      | 2         | 1.59%   |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 0.79%   |
| Z-Star Sirius USB2.0 Camera                                 | 1         | 0.79%   |
| Syntek USB Camera Device                                    | 1         | 0.79%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.79%   |
| Syntek Integrated Webcam                                    | 1         | 0.79%   |
| Suyin Webcam-101                                            | 1         | 0.79%   |
| Suyin HP Webcam                                             | 1         | 0.79%   |
| Suyin HP Truevision HD                                      | 1         | 0.79%   |
| Suyin HD Video WebCam                                       | 1         | 0.79%   |
| Suyin Acer OrbiCam                                          | 1         | 0.79%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.79%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.79%   |
| Sunplus SPCA2281 Web Camera                                 | 1         | 0.79%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.79%   |
| Sunplus HP TrueVision HD Camera                             | 1         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.79%   |
| Sunplus Asus Webcam                                         | 1         | 0.79%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 5         | 31.25%  |
| AuthenTec             | 5         | 31.25%  |
| STMicroelectronics    | 3         | 18.75%  |
| Upek                  | 1         | 6.25%   |
| Synaptics             | 1         | 6.25%   |
| LighTuning Technology | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                  | 3         | 18.75%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 6.25%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 6.25%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 6.25%   |
| AuthenTec Fingerprint Sensor                           | 1         | 6.25%   |
| AuthenTec AES2810                                      | 1         | 6.25%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 6.25%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 6.25%   |
| AuthenTec AES1600                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| O2 Micro    | 2         | 33.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 162       | 69.53%  |
| 1     | 58        | 24.89%  |
| 2     | 12        | 5.15%   |
| 4     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 18        | 21.43%  |
| Graphics card            | 16        | 19.05%  |
| Fingerprint reader       | 15        | 17.86%  |
| Communication controller | 6         | 7.14%   |
| Chipcard                 | 6         | 7.14%   |
| Storage                  | 5         | 5.95%   |
| Modem                    | 4         | 4.76%   |
| Bluetooth                | 3         | 3.57%   |
| Sound                    | 2         | 2.38%   |
| Multimedia controller    | 2         | 2.38%   |
| Camera                   | 2         | 2.38%   |
| Unassigned class         | 1         | 1.19%   |
| Storage/raid             | 1         | 1.19%   |
| Storage/ide              | 1         | 1.19%   |
| Net/ethernet             | 1         | 1.19%   |
| Flash memory             | 1         | 1.19%   |

