Peppermint 10 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Peppermint 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Peppermint_10/Desktop/README.md) and [notebooks](/Dist/Peppermint_10/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=peppermint-10

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
| Sony          | VGN-S55B_S                  | Notebook    | [e531cd57e6](https://linux-hardware.org/?probe=e531cd57e6) | Aug 15, 2021 |
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
| Sony          | VGN-S55B_S                  | Notebook    | [a874601f76](https://linux-hardware.org/?probe=a874601f76) | May 05, 2021 |
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
| Dell          | Board                       | Desktop     | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | Board                       | Desktop     | [6c93eb4440](https://linux-hardware.org/?probe=6c93eb4440) | Mar 07, 2021 |
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
| Dell          | Board                       | Desktop     | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Board                       | Desktop     | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
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
| Sony          | VPCZ21V9E                   | Notebook    | [27d806e418](https://linux-hardware.org/?probe=27d806e418) | Jan 02, 2021 |
| Sony          | VPCZ21V9E                   | Notebook    | [a1dc463ae7](https://linux-hardware.org/?probe=a1dc463ae7) | Jan 02, 2021 |
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
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [fed85859bc](https://linux-hardware.org/?probe=fed85859bc) | Dec 02, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
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
| Sony          | VGN-S55B_S                  | Notebook    | [534a526520](https://linux-hardware.org/?probe=534a526520) | Nov 08, 2020 |
| HP            | Pavilion dv8000 (EZ590UA... | Notebook    | [1e64c078af](https://linux-hardware.org/?probe=1e64c078af) | Nov 04, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [c02b06f51f](https://linux-hardware.org/?probe=c02b06f51f) | Oct 31, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [831a02648f](https://linux-hardware.org/?probe=831a02648f) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [808224d57c](https://linux-hardware.org/?probe=808224d57c) | Oct 30, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [f7fc9c9932](https://linux-hardware.org/?probe=f7fc9c9932) | Oct 20, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [c2bab5c22b](https://linux-hardware.org/?probe=c2bab5c22b) | Oct 15, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [c7104649d5](https://linux-hardware.org/?probe=c7104649d5) | Oct 15, 2020 |
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
| Itautec       | Infoway                     | Notebook    | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| HP            | 8265                        | Desktop     | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| MSI           | MS-7211                     | Desktop     | [98822d361e](https://linux-hardware.org/?probe=98822d361e) | Aug 17, 2020 |
| MSI           | MS-7211                     | Desktop     | [a07f95af54](https://linux-hardware.org/?probe=a07f95af54) | Aug 17, 2020 |
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
| Itautec       | Infoway                     | Notebook    | [27a7c624d8](https://linux-hardware.org/?probe=27a7c624d8) | Jul 17, 2020 |
| Itautec       | Infoway                     | Notebook    | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
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
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [5fa350f8ac](https://linux-hardware.org/?probe=5fa350f8ac) | May 31, 2020 |
| Lenovo        | B490 37722SP                | Notebook    | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| MSI           | MS-7267                     | Desktop     | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Mini 110-1000               | Notebook    | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | Notebook    | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [eef6f0a50b](https://linux-hardware.org/?probe=eef6f0a50b) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [94839129c9](https://linux-hardware.org/?probe=94839129c9) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [adf1cefbf5](https://linux-hardware.org/?probe=adf1cefbf5) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [6782b31a2e](https://linux-hardware.org/?probe=6782b31a2e) | May 17, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Clevo         | W55xEU                      | Notebook    | [f1ad04bd23](https://linux-hardware.org/?probe=f1ad04bd23) | May 16, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [82a7d47cf6](https://linux-hardware.org/?probe=82a7d47cf6) | May 15, 2020 |
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
| Toshiba       | Satellite C660              | Notebook    | [bc3bd72199](https://linux-hardware.org/?probe=bc3bd72199) | May 01, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [c948d7fd76](https://linux-hardware.org/?probe=c948d7fd76) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [595c810650](https://linux-hardware.org/?probe=595c810650) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [f1fc9b4580](https://linux-hardware.org/?probe=f1fc9b4580) | Apr 29, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [131e2c31a9](https://linux-hardware.org/?probe=131e2c31a9) | Apr 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [f9944d9361](https://linux-hardware.org/?probe=f9944d9361) | Apr 25, 2020 |
| Toshiba       | Satellite PRO C850          | Notebook    | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
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
| ASUSTek       | F3E                         | Notebook    | [51ae68d38f](https://linux-hardware.org/?probe=51ae68d38f) | Mar 17, 2020 |
| ASUSTek       | F3E                         | Notebook    | [5d53434528](https://linux-hardware.org/?probe=5d53434528) | Mar 17, 2020 |
| ASUSTek       | F3E                         | Notebook    | [8491571d31](https://linux-hardware.org/?probe=8491571d31) | Mar 17, 2020 |
| ASUSTek       | F3E                         | Notebook    | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | 0AA8h                       | Desktop     | [881008d596](https://linux-hardware.org/?probe=881008d596) | Mar 11, 2020 |
| Acer          | MCP73PV NVIDIA MCP73        | Desktop     | [97b8e03710](https://linux-hardware.org/?probe=97b8e03710) | Mar 04, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [8b516d50ef](https://linux-hardware.org/?probe=8b516d50ef) | Mar 03, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [c67fe8542c](https://linux-hardware.org/?probe=c67fe8542c) | Mar 01, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| ECS           | Alhena5                     | Desktop     | [89c17f438e](https://linux-hardware.org/?probe=89c17f438e) | Feb 28, 2020 |
| eMachines     | E520                        | Notebook    | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [e5dda37f22](https://linux-hardware.org/?probe=e5dda37f22) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| Toshiba       | Satellite C850-F117         | Notebook    | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [516c8bcbc2](https://linux-hardware.org/?probe=516c8bcbc2) | Feb 06, 2020 |
| HP            | 0AA8h                       | Desktop     | [c5721d223f](https://linux-hardware.org/?probe=c5721d223f) | Feb 05, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [17eb93e1dc](https://linux-hardware.org/?probe=17eb93e1dc) | Feb 04, 2020 |
| Toshiba       | NB520                       | Notebook    | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | Notebook    | [20c5cb5e37](https://linux-hardware.org/?probe=20c5cb5e37) | Feb 02, 2020 |
| Toshiba       | NB520                       | Notebook    | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [e341d904c9](https://linux-hardware.org/?probe=e341d904c9) | Feb 01, 2020 |
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
| Gigabyte      | F2A55M-HD2                  | Desktop     | [ee80ea4e41](https://linux-hardware.org/?probe=ee80ea4e41) | Nov 24, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                     | Desktop     | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [c27bae21b0](https://linux-hardware.org/?probe=c27bae21b0) | Nov 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [afb3948882](https://linux-hardware.org/?probe=afb3948882) | Nov 15, 2019 |
| Acer          | Aspire F5-573G              | Notebook    | [db302aa54d](https://linux-hardware.org/?probe=db302aa54d) | Nov 14, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [00c8d1e4e7](https://linux-hardware.org/?probe=00c8d1e4e7) | Nov 11, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [6b30a9e102](https://linux-hardware.org/?probe=6b30a9e102) | Nov 11, 2019 |
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
| HP            | Pavilion Notebook           | Notebook    | [5f57cac098](https://linux-hardware.org/?probe=5f57cac098) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Gigabyte      | H61M-S1                     | Desktop     | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                     | Desktop     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                     | Desktop     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | Desktop     | [e0f3e1d46f](https://linux-hardware.org/?probe=e0f3e1d46f) | Sep 22, 2019 |
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
| Toshiba       | Satellite C850-F117         | Notebook    | [de103d8a7d](https://linux-hardware.org/?probe=de103d8a7d) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | Notebook    | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | Notebook    | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.0.0-37-generic      | 33        | 15%     |
| 5.4.0-42-generic      | 11        | 5%      |
| 4.18.0-18-generic     | 11        | 5%      |
| 5.3.0-51-generic      | 10        | 4.55%   |
| 5.3.0-62-generic      | 9         | 4.09%   |
| 5.4.0-65-generic      | 7         | 3.18%   |
| 5.3.0-46-generic      | 7         | 3.18%   |
| 5.0.0-36-generic      | 7         | 3.18%   |
| 5.0.0-32-generic      | 7         | 3.18%   |
| 5.4.0-66-generic      | 6         | 2.73%   |
| 5.4.0-58-generic      | 6         | 2.73%   |
| 5.3.0-40-generic      | 5         | 2.27%   |
| 5.3.0-28-generic      | 5         | 2.27%   |
| 5.4.0-80-generic      | 4         | 1.82%   |
| 5.4.0-72-generic      | 4         | 1.82%   |
| 5.4.0-54-generic      | 4         | 1.82%   |
| 5.4.0-52-generic      | 4         | 1.82%   |
| 5.4.0-48-generic      | 4         | 1.82%   |
| 5.4.0-45-generic      | 4         | 1.82%   |
| 5.3.0-59-generic      | 4         | 1.82%   |
| 4.18.0-25-generic     | 4         | 1.82%   |
| 5.4.0-81-generic      | 3         | 1.36%   |
| 5.4.0-77-generic      | 3         | 1.36%   |
| 5.4.0-70-generic      | 3         | 1.36%   |
| 5.4.0-67-generic      | 3         | 1.36%   |
| 5.4.0-56-generic      | 3         | 1.36%   |
| 5.4.0-47-generic      | 3         | 1.36%   |
| 5.3.0-47-generic      | 3         | 1.36%   |
| 5.3.0-42-generic      | 3         | 1.36%   |
| 5.0.0-29-generic      | 3         | 1.36%   |
| 5.4.0-74-generic      | 2         | 0.91%   |
| 5.4.0-62-generic      | 2         | 0.91%   |
| 5.4.0-60-generic      | 2         | 0.91%   |
| 5.4.0-51-generic      | 2         | 0.91%   |
| 5.4.0-49-generic      | 2         | 0.91%   |
| 5.3.0-45-generic      | 2         | 0.91%   |
| 5.0.0-27-generic      | 2         | 0.91%   |
| 5.0.0-25-generic      | 2         | 0.91%   |
| 4.18.0-24-generic     | 2         | 0.91%   |
| 4.18.0-21-generic     | 2         | 0.91%   |
| 5.7.1-050701-generic  | 1         | 0.45%   |
| 5.6.7-050607-generic  | 1         | 0.45%   |
| 5.4.95-050495-generic | 1         | 0.45%   |
| 5.4.0-84-generic      | 1         | 0.45%   |
| 5.4.0-73-generic      | 1         | 0.45%   |
| 5.4.0-71-generic      | 1         | 0.45%   |
| 5.4.0-64-generic      | 1         | 0.45%   |
| 5.4.0-59-generic      | 1         | 0.45%   |
| 5.4.0-53-generic      | 1         | 0.45%   |
| 5.4.0-44-generic      | 1         | 0.45%   |
| 5.3.9-050309-generic  | 1         | 0.45%   |
| 5.3.6-050306-generic  | 1         | 0.45%   |
| 5.3.0-53-generic      | 1         | 0.45%   |
| 5.1.11-050111-generic | 1         | 0.45%   |
| 5.0.0-23-generic      | 1         | 0.45%   |
| 4.18.0-22-generic     | 1         | 0.45%   |
| 4.18.0-20-generic     | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 84        | 40.38%  |
| 5.0.0   | 51        | 24.52%  |
| 5.3.0   | 47        | 22.6%   |
| 4.18.0  | 20        | 9.62%   |
| 5.7.1   | 1         | 0.48%   |
| 5.6.7   | 1         | 0.48%   |
| 5.4.95  | 1         | 0.48%   |
| 5.3.9   | 1         | 0.48%   |
| 5.3.6   | 1         | 0.48%   |
| 5.1.11  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 85        | 40.87%  |
| 5.0     | 51        | 24.52%  |
| 5.3     | 49        | 23.56%  |
| 4.18    | 20        | 9.62%   |
| 5.7     | 1         | 0.48%   |
| 5.6     | 1         | 0.48%   |
| 5.1     | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 138       | 69.7%   |
| i686   | 60        | 30.3%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXDE       | 157       | 78.11%  |
| Unknown    | 33        | 16.42%  |
| GNOME      | 9         | 4.48%   |
| X-Cinnamon | 1         | 0.5%    |
| Peppermint | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 197       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 186       | 93.47%  |
| TDM     | 10        | 5.03%   |
| LightDM | 2         | 1.01%   |
| SDDM    | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 63        | 31.19%  |
| Unknown | 26        | 12.87%  |
| en_GB   | 14        | 6.93%   |
| it_IT   | 12        | 5.94%   |
| pt_BR   | 11        | 5.45%   |
| de_DE   | 11        | 5.45%   |
| ru_RU   | 5         | 2.48%   |
| pl_PL   | 5         | 2.48%   |
| nl_NL   | 5         | 2.48%   |
| fr_FR   | 5         | 2.48%   |
| en_IN   | 5         | 2.48%   |
| en_CA   | 5         | 2.48%   |
| C       | 5         | 2.48%   |
| fi_FI   | 3         | 1.49%   |
| ro_RO   | 2         | 0.99%   |
| ja_JP   | 2         | 0.99%   |
| es_PE   | 2         | 0.99%   |
| es_MX   | 2         | 0.99%   |
| es_ES   | 2         | 0.99%   |
| es_AR   | 2         | 0.99%   |
| en_PH   | 2         | 0.99%   |
| en_AU   | 2         | 0.99%   |
| tr_TR   | 1         | 0.5%    |
| sv_SE   | 1         | 0.5%    |
| pt_PT   | 1         | 0.5%    |
| lv_LV   | 1         | 0.5%    |
| es_PA   | 1         | 0.5%    |
| es_EC   | 1         | 0.5%    |
| es_CR   | 1         | 0.5%    |
| es_BO   | 1         | 0.5%    |
| en_ZA   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| en_IE   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 155       | 78.28%  |
| EFI  | 43        | 21.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 167       | 82.67%  |
| Unknown  | 19        | 9.41%   |
| Overlay  | 6         | 2.97%   |
| Btrfs    | 4         | 1.98%   |
| Ext2     | 3         | 1.49%   |
| Xfs      | 1         | 0.5%    |
| Reiserfs | 1         | 0.5%    |
| Ext3     | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 182       | 91.92%  |
| GPT     | 9         | 4.55%   |
| MBR     | 7         | 3.54%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 91.5%   |
| Yes       | 17        | 8.5%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 85.43%  |
| Yes       | 29        | 14.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 36        | 18.27%  |
| ASUSTek Computer    | 29        | 14.72%  |
| Dell                | 21        | 10.66%  |
| Lenovo              | 20        | 10.15%  |
| Toshiba             | 15        | 7.61%   |
| Acer                | 13        | 6.6%    |
| Gigabyte Technology | 11        | 5.58%   |
| Samsung Electronics | 7         | 3.55%   |
| Fujitsu Siemens     | 6         | 3.05%   |
| Sony                | 4         | 2.03%   |
| Intel               | 4         | 2.03%   |
| eMachines           | 3         | 1.52%   |
| Unknown             | 3         | 1.52%   |
| Pegatron            | 2         | 1.02%   |
| MSI                 | 2         | 1.02%   |
| Gateway             | 2         | 1.02%   |
| Fujitsu             | 2         | 1.02%   |
| ASRock              | 2         | 1.02%   |
| Apple               | 2         | 1.02%   |
| Positivo            | 1         | 0.51%   |
| Packard Bell        | 1         | 0.51%   |
| Olivetti            | 1         | 0.51%   |
| Nvidia              | 1         | 0.51%   |
| Medion              | 1         | 0.51%   |
| JPSaCouto           | 1         | 0.51%   |
| Itautec             | 1         | 0.51%   |
| IBM                 | 1         | 0.51%   |
| Google              | 1         | 0.51%   |
| Foxconn             | 1         | 0.51%   |
| ECS                 | 1         | 0.51%   |
| Clevo               | 1         | 0.51%   |
| Biostar             | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo IdeaPad 2in1 14 81CW                | 3         | 1.52%   |
| Unknown                                    | 3         | 1.52%   |
| Toshiba Satellite M70                      | 2         | 1.02%   |
| Toshiba Satellite L500                     | 2         | 1.02%   |
| Samsung N150P/N210P/N220P                  | 2         | 1.02%   |
| Lenovo G500 20236                          | 2         | 1.02%   |
| HP Compaq dc7900 Convertible Minitower     | 2         | 1.02%   |
| Fujitsu Siemens D1931                      | 2         | 1.02%   |
| Dell Inspiron N5050                        | 2         | 1.02%   |
| Acer Extensa 5630                          | 2         | 1.02%   |
| Toshiba Satellite PRO C850                 | 1         | 0.51%   |
| Toshiba Satellite L310                     | 1         | 0.51%   |
| Toshiba Satellite L300                     | 1         | 0.51%   |
| Toshiba Satellite C850-F117                | 1         | 0.51%   |
| Toshiba Satellite C660                     | 1         | 0.51%   |
| Toshiba Satellite C55D-B                   | 1         | 0.51%   |
| Toshiba QOSMIO F755                        | 1         | 0.51%   |
| Toshiba PORTEGE R500                       | 1         | 0.51%   |
| Toshiba NB520                              | 1         | 0.51%   |
| Toshiba NB500                              | 1         | 0.51%   |
| Toshiba dynabook Satellite B552/H          | 1         | 0.51%   |
| Sony VPCZ21V9E                             | 1         | 0.51%   |
| Sony VPCCW21FX                             | 1         | 0.51%   |
| Sony VGN-S55B_S                            | 1         | 0.51%   |
| Sony VGN-FW140E                            | 1         | 0.51%   |
| Samsung R610                               | 1         | 0.51%   |
| Samsung R530/R730/R540                     | 1         | 0.51%   |
| Samsung N150P                              | 1         | 0.51%   |
| Samsung N150/N210/N220                     | 1         | 0.51%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.51%   |
| Positivo N1103                             | 1         | 0.51%   |
| Pegatron FR502AA-ABZ m9355.it              | 1         | 0.51%   |
| Pegatron CQ1506LA                          | 1         | 0.51%   |
| Packard Bell EasyNote TK85                 | 1         | 0.51%   |
| Olivetti CL133A                            | 1         | 0.51%   |
| Nvidia MCP7A                               | 1         | 0.51%   |
| MSI MS-7267                                | 1         | 0.51%   |
| MSI MS-7211                                | 1         | 0.51%   |
| Medion Akoya E4214 MD99570                 | 1         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS0035US   | 1         | 0.51%   |
| Lenovo ThinkPad T60 1951CJ4                | 1         | 0.51%   |
| Lenovo ThinkPad T450 20BUS3CF00            | 1         | 0.51%   |
| Lenovo ThinkPad R60 94566FG                | 1         | 0.51%   |
| Lenovo ThinkPad Edge E431 62775GU          | 1         | 0.51%   |
| Lenovo ThinkPad E490 20N90019BR            | 1         | 0.51%   |
| Lenovo MIIX 310-10ICR 80SG                 | 1         | 0.51%   |
| Lenovo IdeaPad Z460 20059                  | 1         | 0.51%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 0.51%   |
| Lenovo IdeaPad 1 11ADA05 82GV              | 1         | 0.51%   |
| Lenovo IdeaCentre Q190 10115               | 1         | 0.51%   |
| Lenovo B575 1450A7U                        | 1         | 0.51%   |
| Lenovo B490 37722SP                        | 1         | 0.51%   |
| Lenovo 433328G                             | 1         | 0.51%   |
| Lenovo 3000 N500 423374G                   | 1         | 0.51%   |
| JPSaCouto Intel powered classmate PC       | 1         | 0.51%   |
| Itautec Infoway                            | 1         | 0.51%   |
| Intel Energy Systems                       | 1         | 0.51%   |
| Intel DP55WG AAE57269-408                  | 1         | 0.51%   |
| Intel D945GCLF2 AAE46416-106               | 1         | 0.51%   |
| Intel 945GCT-M                             | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Toshiba Satellite       | 10        | 5.08%   |
| HP Compaq               | 10        | 5.08%   |
| HP Pavilion             | 7         | 3.55%   |
| Dell Inspiron           | 7         | 3.55%   |
| Lenovo ThinkPad         | 6         | 3.05%   |
| Lenovo IdeaPad          | 6         | 3.05%   |
| Acer Aspire             | 6         | 3.05%   |
| Dell OptiPlex           | 5         | 2.54%   |
| HP EliteBook            | 4         | 2.03%   |
| Acer Extensa            | 4         | 2.03%   |
| Samsung N150P           | 3         | 1.52%   |
| Dell Precision          | 3         | 1.52%   |
| Dell Latitude           | 3         | 1.52%   |
| Unknown                 | 3         | 1.52%   |
| Lenovo G500             | 2         | 1.02%   |
| HP Stream               | 2         | 1.02%   |
| HP Mini                 | 2         | 1.02%   |
| HP Laptop               | 2         | 1.02%   |
| HP 255                  | 2         | 1.02%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.02%   |
| Fujitsu Siemens D1931   | 2         | 1.02%   |
| Fujitsu Siemens AMILO   | 2         | 1.02%   |
| Toshiba QOSMIO          | 1         | 0.51%   |
| Toshiba PORTEGE         | 1         | 0.51%   |
| Toshiba NB520           | 1         | 0.51%   |
| Toshiba NB500           | 1         | 0.51%   |
| Toshiba dynabook        | 1         | 0.51%   |
| Sony VPCZ21V9E          | 1         | 0.51%   |
| Sony VPCCW21FX          | 1         | 0.51%   |
| Sony VGN-S55B           | 1         | 0.51%   |
| Sony VGN-FW140E         | 1         | 0.51%   |
| Samsung R610            | 1         | 0.51%   |
| Samsung R530            | 1         | 0.51%   |
| Samsung N150            | 1         | 0.51%   |
| Samsung 300E4A          | 1         | 0.51%   |
| Positivo N1103          | 1         | 0.51%   |
| Pegatron FR502AA-ABZ    | 1         | 0.51%   |
| Pegatron CQ1506LA       | 1         | 0.51%   |
| Packard Bell EasyNote   | 1         | 0.51%   |
| Olivetti CL133A         | 1         | 0.51%   |
| Nvidia MCP7A            | 1         | 0.51%   |
| MSI MS-7267             | 1         | 0.51%   |
| MSI MS-7211             | 1         | 0.51%   |
| Medion Akoya            | 1         | 0.51%   |
| Lenovo MIIX             | 1         | 0.51%   |
| Lenovo IdeaCentre       | 1         | 0.51%   |
| Lenovo B575             | 1         | 0.51%   |
| Lenovo B490             | 1         | 0.51%   |
| Lenovo 433328G          | 1         | 0.51%   |
| Lenovo 3000             | 1         | 0.51%   |
| JPSaCouto Intel         | 1         | 0.51%   |
| Itautec Infoway         | 1         | 0.51%   |
| Intel Energy            | 1         | 0.51%   |
| Intel DP55WG            | 1         | 0.51%   |
| Intel D945GCLF2         | 1         | 0.51%   |
| Intel 945GCT-M          | 1         | 0.51%   |
| IBM ThinkPad            | 1         | 0.51%   |
| HP ProDesk              | 1         | 0.51%   |
| HP Presario             | 1         | 0.51%   |
| HP Notebook             | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2009    | 22        | 11.17%  |
| 2008    | 21        | 10.66%  |
| 2013    | 19        | 9.64%   |
| 2007    | 18        | 9.14%   |
| 2019    | 17        | 8.63%   |
| 2010    | 17        | 8.63%   |
| 2011    | 16        | 8.12%   |
| 2012    | 14        | 7.11%   |
| 2016    | 8         | 4.06%   |
| 2018    | 7         | 3.55%   |
| 2005    | 7         | 3.55%   |
| 2017    | 6         | 3.05%   |
| 2015    | 6         | 3.05%   |
| 2006    | 6         | 3.05%   |
| 2014    | 5         | 2.54%   |
| 2020    | 4         | 2.03%   |
| 2021    | 2         | 1.02%   |
| 2004    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 123       | 62.44%  |
| Desktop     | 70        | 35.53%  |
| Convertible | 3         | 1.52%   |
| Tablet      | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 190       | 96.45%  |
| Enabled  | 7         | 3.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 196       | 99.49%  |
| Yes  | 1         | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 65        | 32.5%   |
| 1.01-2.0   | 54        | 27%     |
| 4.01-8.0   | 23        | 11.5%   |
| 8.01-16.0  | 17        | 8.5%    |
| 2.01-3.0   | 14        | 7%      |
| 0.51-1.0   | 12        | 6%      |
| 16.01-24.0 | 10        | 5%      |
| 32.01-64.0 | 4         | 2%      |
| 24.01-32.0 | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.51-1.0  | 87        | 40.47%  |
| 1.01-2.0  | 84        | 39.07%  |
| 2.01-3.0  | 24        | 11.16%  |
| 0.01-0.5  | 12        | 5.58%   |
| 4.01-8.0  | 4         | 1.86%   |
| 3.01-4.0  | 3         | 1.4%    |
| 8.01-16.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 70.94%  |
| 2      | 43        | 21.18%  |
| 3      | 10        | 4.93%   |
| 0      | 2         | 0.99%   |
| 7      | 1         | 0.49%   |
| 6      | 1         | 0.49%   |
| 5      | 1         | 0.49%   |
| 4      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 60.8%   |
| No        | 78        | 39.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 91.88%  |
| No        | 16        | 8.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 83.25%  |
| No        | 33        | 16.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 59.6%   |
| Yes       | 80        | 40.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 58        | 29.29%  |
| Germany      | 17        | 8.59%   |
| UK           | 13        | 6.57%   |
| Italy        | 13        | 6.57%   |
| Brazil       | 10        | 5.05%   |
| Netherlands  | 8         | 4.04%   |
| Canada       | 8         | 4.04%   |
| Russia       | 6         | 3.03%   |
| Romania      | 6         | 3.03%   |
| Poland       | 5         | 2.53%   |
| India        | 5         | 2.53%   |
| France       | 4         | 2.02%   |
| Finland      | 4         | 2.02%   |
| Japan        | 3         | 1.52%   |
| Argentina    | 3         | 1.52%   |
| Sweden       | 2         | 1.01%   |
| Spain        | 2         | 1.01%   |
| Portugal     | 2         | 1.01%   |
| Philippines  | 2         | 1.01%   |
| Peru         | 2         | 1.01%   |
| Mexico       | 2         | 1.01%   |
| Bolivia      | 2         | 1.01%   |
| Australia    | 2         | 1.01%   |
| Turkey       | 1         | 0.51%   |
| Switzerland  | 1         | 0.51%   |
| South Africa | 1         | 0.51%   |
| Serbia       | 1         | 0.51%   |
| Panama       | 1         | 0.51%   |
| Norway       | 1         | 0.51%   |
| New Zealand  | 1         | 0.51%   |
| Namibia      | 1         | 0.51%   |
| Malaysia     | 1         | 0.51%   |
| Latvia       | 1         | 0.51%   |
| Kazakhstan   | 1         | 0.51%   |
| Ireland      | 1         | 0.51%   |
| Greece       | 1         | 0.51%   |
| Georgia      | 1         | 0.51%   |
| Ecuador      | 1         | 0.51%   |
| Costa Rica   | 1         | 0.51%   |
| Belgium      | 1         | 0.51%   |
| Belarus      | 1         | 0.51%   |
| Algeria      | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Bucharest              | 4         | 1.94%   |
| Villingen-Schwenningen | 3         | 1.46%   |
| Turin                  | 3         | 1.46%   |
| Toronto                | 2         | 0.97%   |
| Topeka                 | 2         | 0.97%   |
| Tahlequah              | 2         | 0.97%   |
| Perth                  | 2         | 0.97%   |
| Oldenburg              | 2         | 0.97%   |
| Naples                 | 2         | 0.97%   |
| Moscow                 | 2         | 0.97%   |
| Manchester             | 2         | 0.97%   |
| Lima                   | 2         | 0.97%   |
| Hamburg                | 2         | 0.97%   |
| Calgary                | 2         | 0.97%   |
| Brunswick              | 2         | 0.97%   |
| Amsterdam              | 2         | 0.97%   |
| Środa Śląska        | 1         | 0.49%   |
| Äänekoski            | 1         | 0.49%   |
| Zvecka                 | 1         | 0.49%   |
| Zaandam                | 1         | 0.49%   |
| Yokohama               | 1         | 0.49%   |
| Yacuiba                | 1         | 0.49%   |
| Wysokie Mazowieckie    | 1         | 0.49%   |
| Winfield               | 1         | 0.49%   |
| Windhoek               | 1         | 0.49%   |
| West Chester           | 1         | 0.49%   |
| Welwyn Garden City     | 1         | 0.49%   |
| Wassenaar              | 1         | 0.49%   |
| Washington             | 1         | 0.49%   |
| Warsaw                 | 1         | 0.49%   |
| Waalwijk               | 1         | 0.49%   |
| Versailles             | 1         | 0.49%   |
| Verona                 | 1         | 0.49%   |
| Van Vleck              | 1         | 0.49%   |
| Tucson                 | 1         | 0.49%   |
| Tsarskoye Selo         | 1         | 0.49%   |
| Tres Rios              | 1         | 0.49%   |
| Thatcher               | 1         | 0.49%   |
| Telford                | 1         | 0.49%   |
| Tbilisi                | 1         | 0.49%   |
| Taranto                | 1         | 0.49%   |
| Talala                 | 1         | 0.49%   |
| São Paulo             | 1         | 0.49%   |
| Stockton               | 1         | 0.49%   |
| Spokane                | 1         | 0.49%   |
| Southampton            | 1         | 0.49%   |
| South Jordan           | 1         | 0.49%   |
| Somma Vesuviana        | 1         | 0.49%   |
| Sivas                  | 1         | 0.49%   |
| Shoreham-by-Sea        | 1         | 0.49%   |
| Sherwood Park          | 1         | 0.49%   |
| Seville                | 1         | 0.49%   |
| Seattle                | 1         | 0.49%   |
| Scharendijke           | 1         | 0.49%   |
| Saratov                | 1         | 0.49%   |
| Santa Barbara          | 1         | 0.49%   |
| Sant Boi de Llobregat  | 1         | 0.49%   |
| San Rafael             | 1         | 0.49%   |
| Saint-Jerome           | 1         | 0.49%   |
| Rugby                  | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 67     | 19.75%  |
| Seagate             | 47        | 51     | 19.75%  |
| Samsung Electronics | 26        | 35     | 10.92%  |
| Hitachi             | 24        | 33     | 10.08%  |
| Toshiba             | 19        | 19     | 7.98%   |
| Unknown             | 16        | 19     | 6.72%   |
| Kingston            | 11        | 15     | 4.62%   |
| SanDisk             | 7         | 8      | 2.94%   |
| MAXTOR              | 6         | 9      | 2.52%   |
| HGST                | 4         | 5      | 1.68%   |
| PNY                 | 3         | 4      | 1.26%   |
| Fujitsu             | 3         | 3      | 1.26%   |
| Intel               | 2         | 2      | 0.84%   |
| Integral            | 2         | 2      | 0.84%   |
| Crucial             | 2         | 3      | 0.84%   |
| Zheino              | 1         | 1      | 0.42%   |
| WD MediaMax         | 1         | 1      | 0.42%   |
| TCSUNBOW            | 1         | 1      | 0.42%   |
| SK Hynix            | 1         | 1      | 0.42%   |
| SABRENT             | 1         | 1      | 0.42%   |
| OCZ                 | 1         | 1      | 0.42%   |
| Micron Technology   | 1         | 1      | 0.42%   |
| LITEONIT            | 1         | 1      | 0.42%   |
| KingSpec            | 1         | 1      | 0.42%   |
| Intenso             | 1         | 1      | 0.42%   |
| GOODRAM             | 1         | 1      | 0.42%   |
| GAMER               | 1         | 1      | 0.42%   |
| FATTYDOVE           | 1         | 1      | 0.42%   |
| DREVO               | 1         | 1      | 0.42%   |
| China               | 1         | 1      | 0.42%   |
| BHT                 | 1         | 2      | 0.42%   |
| ASMT                | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |
| Apacer              | 1         | 5      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 6         | 2.42%   |
| Seagate ST9500325AS 500GB           | 4         | 1.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.61%   |
| Kingston SA400S37120G 120GB SSD     | 4         | 1.61%   |
| Toshiba MQ01ABF050 500GB            | 3         | 1.21%   |
| Seagate ST9320325AS 320GB           | 3         | 1.21%   |
| Seagate ST9250315AS 250GB           | 3         | 1.21%   |
| Seagate ST500LT012-1DG142 500GB     | 3         | 1.21%   |
| SanDisk SDSSDA120G 120GB            | 3         | 1.21%   |
| Hitachi HDT721016SLA380 160GB       | 3         | 1.21%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.81%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.81%   |
| Unknown SD/MMC/MS PRO 128GB         | 2         | 0.81%   |
| Unknown MMC Card  64GB              | 2         | 0.81%   |
| Unknown MMC Card  16GB              | 2         | 0.81%   |
| Seagate ST9160314AS 160GB           | 2         | 0.81%   |
| Seagate ST3500418AS 500GB           | 2         | 0.81%   |
| Seagate ST3250310AS 250GB           | 2         | 0.81%   |
| Seagate ST3160813AS 160GB           | 2         | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.81%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 0.81%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.81%   |
| Samsung SSD 850 EVO 500GB           | 2         | 0.81%   |
| Samsung HM160HI 160GB               | 2         | 0.81%   |
| MAXTOR STM3160215AS 160GB           | 2         | 0.81%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.81%   |
| Hitachi HTS723232A7A364 320GB       | 2         | 0.81%   |
| Hitachi HTS545025B9A300 250GB       | 2         | 0.81%   |
| Hitachi HDS721050CLA362 500GB       | 2         | 0.81%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.81%   |
| Zheino CHN 25SATAA3 120 120GB SSD   | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.4%    |
| WDC WD800JD-75MSA1 80GB             | 1         | 0.4%    |
| WDC WD800JD-60LSA5 80GB             | 1         | 0.4%    |
| WDC WD800JD-00MSA1 80GB             | 1         | 0.4%    |
| WDC WD6400AAKS-65A7B2 640GB         | 1         | 0.4%    |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.4%    |
| WDC WD5000LPVT-24G33T1 500GB        | 1         | 0.4%    |
| WDC WD5000AAKX-753CA1 500GB         | 1         | 0.4%    |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 0.4%    |
| WDC WD5000AAKS-00A7B2 500GB         | 1         | 0.4%    |
| WDC WD4000AAJS-00YFA0 400GB         | 1         | 0.4%    |
| WDC WD3200JS-22PDB0 320GB           | 1         | 0.4%    |
| WDC WD3200BPVT-08JJ5T0 320GB        | 1         | 0.4%    |
| WDC WD3200AVVS-63L2B0 320GB         | 1         | 0.4%    |
| WDC WD3200AVJB-63WKA0 320GB         | 1         | 0.4%    |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 0.4%    |
| WDC WD2500BPVT-24ZEST0 250GB        | 1         | 0.4%    |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 0.4%    |
| WDC WD2500BEVT-35A23T0 250GB        | 1         | 0.4%    |
| WDC WD2500BEVT-22A23T0 250GB        | 1         | 0.4%    |
| WDC WD2500BEVS-00UST0 250GB         | 1         | 0.4%    |
| WDC WD2500AVJB-63WKA0 250GB         | 1         | 0.4%    |
| WDC WD2500AAJS-75M0A0 250GB         | 1         | 0.4%    |
| WDC WD2500AAJS-00VTA0 250GB         | 1         | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB            | 1         | 0.4%    |
| WDC WD20EURS-63S48Y0 2TB            | 1         | 0.4%    |
| WDC WD2000JS-60NCB1 200GB           | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 51     | 28.83%  |
| WDC                 | 45        | 65     | 27.61%  |
| Hitachi             | 24        | 33     | 14.72%  |
| Toshiba             | 19        | 19     | 11.66%  |
| Samsung Electronics | 12        | 15     | 7.36%   |
| MAXTOR              | 6         | 9      | 3.68%   |
| HGST                | 4         | 5      | 2.45%   |
| Fujitsu             | 3         | 3      | 1.84%   |
| Unknown             | 2         | 2      | 1.23%   |
| WD MediaMax         | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 18     | 21.82%  |
| Kingston            | 11        | 15     | 20%     |
| SanDisk             | 7         | 8      | 12.73%  |
| PNY                 | 3         | 4      | 5.45%   |
| WDC                 | 2         | 2      | 3.64%   |
| Intel               | 2         | 2      | 3.64%   |
| Integral            | 2         | 2      | 3.64%   |
| Crucial             | 2         | 3      | 3.64%   |
| Zheino              | 1         | 1      | 1.82%   |
| TCSUNBOW            | 1         | 1      | 1.82%   |
| OCZ                 | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| LITEONIT            | 1         | 1      | 1.82%   |
| KingSpec            | 1         | 1      | 1.82%   |
| GOODRAM             | 1         | 1      | 1.82%   |
| FATTYDOVE           | 1         | 1      | 1.82%   |
| DREVO               | 1         | 1      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| BHT                 | 1         | 2      | 1.82%   |
| ASMT                | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |
| Apacer              | 1         | 5      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 144       | 203    | 66.06%  |
| SSD     | 54        | 73     | 24.77%  |
| MMC     | 14        | 17     | 6.42%   |
| Unknown | 4         | 4      | 1.83%   |
| NVMe    | 2         | 2      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 182       | 274    | 89.22%  |
| MMC  | 14        | 17     | 6.86%   |
| SAS  | 6         | 6      | 2.94%   |
| NVMe | 2         | 2      | 0.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 164       | 229    | 80.79%  |
| 0.51-1.0   | 31        | 37     | 15.27%  |
| 1.01-2.0   | 6         | 8      | 2.96%   |
| 4.01-10.0  | 2         | 2      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 76        | 37.44%  |
| 251-500        | 38        | 18.72%  |
| 51-100         | 25        | 12.32%  |
| 21-50          | 24        | 11.82%  |
| 501-1000       | 22        | 10.84%  |
| 1-20           | 7         | 3.45%   |
| 1001-2000      | 6         | 2.96%   |
| 2001-3000      | 2         | 0.99%   |
| Unknown        | 2         | 0.99%   |
| More than 3000 | 1         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 129       | 61.72%  |
| 21-50     | 40        | 19.14%  |
| 51-100    | 18        | 8.61%   |
| 101-250   | 13        | 6.22%   |
| 501-1000  | 5         | 2.39%   |
| Unknown   | 2         | 0.96%   |
| 251-500   | 1         | 0.48%   |
| 1001-2000 | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD1001FALS-00J7B0 1TB       | 1         | 1      | 20%     |
| Seagate ST9500420AS 500GB       | 1         | 1      | 20%     |
| Seagate ST9250315AS 250GB       | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 20%     |
| Seagate ST31500341AS 1TB        | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 80%     |
| WDC     | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 80%     |
| WDC     | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 100%    |

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
| Detected | 183       | 279    | 91.5%   |
| Works    | 12        | 15     | 6%      |
| Malfunc  | 5         | 5      | 2.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 68.34%  |
| AMD                              | 28        | 14.07%  |
| Nvidia                           | 10        | 5.03%   |
| VIA Technologies                 | 5         | 2.51%   |
| Silicon Integrated Systems [SiS] | 5         | 2.51%   |
| JMicron Technology               | 5         | 2.51%   |
| Samsung Electronics              | 3         | 1.51%   |
| Marvell Technology Group         | 3         | 1.51%   |
| ULi Electronics                  | 1         | 0.5%    |
| Silicon Image                    | 1         | 0.5%    |
| LSI Logic / Symbios Logic        | 1         | 0.5%    |
| ASMedia Technology               | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 16        | 6.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 5.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 5.28%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 5.28%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 3.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 10        | 3.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 8         | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 2.64%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 5         | 1.89%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 5         | 1.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 5         | 1.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 5         | 1.89%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 5         | 1.89%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 4         | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.51%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4         | 1.51%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 4         | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.51%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 4         | 1.51%   |
| Nvidia MCP61 SATA Controller                                                   | 3         | 1.13%   |
| Nvidia MCP61 IDE                                                               | 3         | 1.13%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.13%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 3         | 1.13%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 3         | 1.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 3         | 1.13%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3         | 1.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 3         | 1.13%   |
| AMD IXP SB4x0 IDE Controller                                                   | 3         | 1.13%   |
| VIA VT8237/8251 Serial ATA Controller                                          | 2         | 0.75%   |
| Nvidia MCP51 Serial ATA Controller                                             | 2         | 0.75%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.75%   |
| JMicron JMB368 IDE controller                                                  | 2         | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.75%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 2         | 0.75%   |
| Intel 82801FB/FW (ICH6/ICH6W) SATA Controller                                  | 2         | 0.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 0.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 0.75%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 0.75%   |
| AMD FCH SATA Controller [IDE mode]                                             | 2         | 0.75%   |
| VIA VT8237A SATA 2-Port Controller                                             | 1         | 0.38%   |
| VIA VIA VT6420 SATA RAID Controller                                            | 1         | 0.38%   |
| ULi ULi 5287 SATA                                                              | 1         | 0.38%   |
| ULi M5229 IDE                                                                  | 1         | 0.38%   |
| Silicon Image SiI 3114 [SATALink/SATARaid] Serial ATA Controller               | 1         | 0.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1         | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.38%   |
| Samsung Electronics SATA controller                                            | 1         | 0.38%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 1         | 0.38%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.38%   |
| Nvidia MCP73 SATA RAID Controller                                              | 1         | 0.38%   |
| Nvidia MCP73 IDE Controller                                                    | 1         | 0.38%   |
| Nvidia MCP67 IDE Controller                                                    | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 56.13%  |
| IDE  | 79        | 37.26%  |
| RAID | 11        | 5.19%   |
| NVMe | 2         | 0.94%   |
| SAS  | 1         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 162       | 82.23%  |
| AMD          | 34        | 17.26%  |
| CentaurHauls | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 3.05%   |
| Intel Atom CPU N450 @ 1.66GHz               | 5         | 2.54%   |
| Intel Pentium M processor 1.73GHz           | 4         | 2.03%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4         | 2.03%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.52%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 3         | 1.52%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 1.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 1.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.52%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 1.02%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.02%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 2         | 1.02%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 2         | 1.02%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 1.02%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.02%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.02%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.02%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 1.02%   |
| Intel Core 2 CPU 6600 @ 2.40GHz             | 2         | 1.02%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 1.02%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 1.02%   |
| Intel Celeron CPU 430 @ 1.80GHz             | 2         | 1.02%   |
| Intel Celeron CPU 1017U @ 1.60GHz           | 2         | 1.02%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 2         | 1.02%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.02%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 1.02%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 2         | 1.02%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.02%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.51%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1         | 0.51%   |
| Intel Xeon CPU E31270 @ 3.40GHz             | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.51%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.51%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 0.51%   |
| Intel Pentium Dual CPU T2410 @ 2.00GHz      | 1         | 0.51%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.51%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.51%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.51%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.51%   |
| Intel Pentium CPU G6960 @ 2.93GHz           | 1         | 0.51%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1         | 0.51%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 1         | 0.51%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.51%   |
| Intel Pentium 4 CPU 3.40GHz                 | 1         | 0.51%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.51%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.51%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.51%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 1         | 0.51%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.51%   |
| Intel Core i7-5930K CPU @ 3.50GHz           | 1         | 0.51%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.51%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 0.51%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.51%   |
| Intel Core i7-3820QM CPU @ 2.70GHz          | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 23        | 11.68%  |
| Intel Atom              | 22        | 11.17%  |
| Intel Core i5           | 16        | 8.12%   |
| Intel Core i7           | 14        | 7.11%   |
| Intel Pentium           | 12        | 6.09%   |
| Intel Core i3           | 12        | 6.09%   |
| Intel Core 2 Duo        | 12        | 6.09%   |
| Intel Pentium Dual-Core | 9         | 4.57%   |
| Intel Core 2 Quad       | 8         | 4.06%   |
| Intel Genuine           | 7         | 3.55%   |
| Intel Core 2            | 7         | 3.55%   |
| AMD Athlon 64 X2        | 6         | 3.05%   |
| Intel Pentium Dual      | 5         | 2.54%   |
| Intel Pentium 4         | 5         | 2.54%   |
| Intel Pentium M         | 4         | 2.03%   |
| Other                   | 3         | 1.52%   |
| Intel Xeon              | 3         | 1.52%   |
| AMD A8                  | 3         | 1.52%   |
| AMD FX                  | 2         | 1.02%   |
| AMD E2                  | 2         | 1.02%   |
| AMD E1                  | 2         | 1.02%   |
| AMD A6                  | 2         | 1.02%   |
| AMD A4                  | 2         | 1.02%   |
| Intel Pentium D         | 1         | 0.51%   |
| Intel Celeron M         | 1         | 0.51%   |
| Intel Celeron Dual-Core | 1         | 0.51%   |
| CentaurHauls VIA C7     | 1         | 0.51%   |
| AMD Turion 64 X2 Mobile | 1         | 0.51%   |
| AMD Turion 64 Mobile    | 1         | 0.51%   |
| AMD Sempron             | 1         | 0.51%   |
| AMD Ryzen 3             | 1         | 0.51%   |
| AMD Phenom II X4        | 1         | 0.51%   |
| AMD Phenom II           | 1         | 0.51%   |
| AMD E                   | 1         | 0.51%   |
| AMD C-60                | 1         | 0.51%   |
| AMD Athlon II X2        | 1         | 0.51%   |
| AMD Athlon 64           | 1         | 0.51%   |
| AMD Athlon              | 1         | 0.51%   |
| AMD A10                 | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 110       | 55.84%  |
| 1      | 44        | 22.34%  |
| 4      | 39        | 19.8%   |
| 6      | 3         | 1.52%   |
| 3      | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 197       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 62.44%  |
| 2      | 74        | 37.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 164       | 82.41%  |
| 32-bit         | 19        | 9.55%   |
| Unknown        | 16        | 8.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x1067a    | 23        | 11.56%  |
| Unknown    | 17        | 8.54%   |
| 0x306a9    | 15        | 7.54%   |
| 0x206a7    | 14        | 7.04%   |
| 0x6fd      | 11        | 5.53%   |
| 0x106ca    | 10        | 5.03%   |
| 0x106c2    | 8         | 4.02%   |
| 0x10661    | 7         | 3.52%   |
| 0x30678    | 6         | 3.02%   |
| 0x20655    | 6         | 3.02%   |
| 0x806e9    | 5         | 2.51%   |
| 0x6f6      | 5         | 2.51%   |
| 0x406c4    | 5         | 2.51%   |
| 0x6d8      | 4         | 2.01%   |
| 0xf41      | 3         | 1.51%   |
| 0x6fb      | 3         | 1.51%   |
| 0x6e8      | 3         | 1.51%   |
| 0x40651    | 3         | 1.51%   |
| 0x10676    | 3         | 1.51%   |
| 0x07030105 | 3         | 1.51%   |
| 0x06006705 | 3         | 1.51%   |
| 0x06001119 | 3         | 1.51%   |
| 0x010000c8 | 3         | 1.51%   |
| 0x806ec    | 2         | 1.01%   |
| 0x6f2      | 2         | 1.01%   |
| 0x6ec      | 2         | 1.01%   |
| 0x306d4    | 2         | 1.01%   |
| 0x306c3    | 2         | 1.01%   |
| 0x20652    | 2         | 1.01%   |
| 0x07030106 | 2         | 1.01%   |
| 0x05000119 | 2         | 1.01%   |
| 0xf65      | 1         | 0.5%    |
| 0xf62      | 1         | 0.5%    |
| 0xf43      | 1         | 0.5%    |
| 0xf33      | 1         | 0.5%    |
| 0x906ea    | 1         | 0.5%    |
| 0x706a1    | 1         | 0.5%    |
| 0x506c9    | 1         | 0.5%    |
| 0x306f2    | 1         | 0.5%    |
| 0x30661    | 1         | 0.5%    |
| 0x206c2    | 1         | 0.5%    |
| 0x106a5    | 1         | 0.5%    |
| 0x10677    | 1         | 0.5%    |
| 0x08200103 | 1         | 0.5%    |
| 0x08108109 | 1         | 0.5%    |
| 0x0700010f | 1         | 0.5%    |
| 0x0600611a | 1         | 0.5%    |
| 0x06006118 | 1         | 0.5%    |
| 0x06000852 | 1         | 0.5%    |
| 0x06000822 | 1         | 0.5%    |
| 0x05000029 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Core          | 28        | 14.21%  |
| Penryn        | 27        | 13.71%  |
| Bonnell       | 19        | 9.64%   |
| IvyBridge     | 16        | 8.12%   |
| SandyBridge   | 14        | 7.11%   |
| Silvermont    | 11        | 5.58%   |
| Westmere      | 10        | 5.08%   |
| P6            | 9         | 4.57%   |
| K8 Hammer     | 9         | 4.57%   |
| KabyLake      | 8         | 4.06%   |
| NetBurst      | 7         | 3.55%   |
| Haswell       | 7         | 3.55%   |
| Puma          | 5         | 2.54%   |
| Piledriver    | 5         | 2.54%   |
| Excavator     | 5         | 2.54%   |
| K10           | 4         | 2.03%   |
| Broadwell     | 3         | 1.52%   |
| Bobcat        | 3         | 1.52%   |
| Zen+          | 1         | 0.51%   |
| Zen           | 1         | 0.51%   |
| Nehalem       | 1         | 0.51%   |
| Jaguar        | 1         | 0.51%   |
| Goldmont plus | 1         | 0.51%   |
| Goldmont      | 1         | 0.51%   |
| Unknown       | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 124       | 60.78%  |
| AMD                              | 39        | 19.12%  |
| Nvidia                           | 34        | 16.67%  |
| Silicon Integrated Systems [SiS] | 4         | 1.96%   |
| VIA Technologies                 | 3         | 1.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 6.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 6.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.41%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 9         | 3.96%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 3.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.08%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 2.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.64%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 2.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.2%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 1.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.76%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4         | 1.76%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.32%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.32%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 1.32%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.32%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.32%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 1.32%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.32%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.88%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.88%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.88%   |
| Nvidia G94 [GeForce 9600 GS]                                                             | 2         | 0.88%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 2         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.88%   |
| Intel HD Graphics 620                                                                    | 2         | 0.88%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 2         | 0.88%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 2         | 0.88%   |
| AMD Picasso                                                                              | 2         | 0.88%   |
| Nvidia NV43 [GeForce 6600 LE]                                                            | 1         | 0.44%   |
| Nvidia NV18 [GeForce4 MX 440 AGP 8x]                                                     | 1         | 0.44%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.44%   |
| Nvidia GT218M [ION]                                                                      | 1         | 0.44%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.44%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 1         | 0.44%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 1         | 0.44%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.44%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.44%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.44%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 1         | 0.44%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.44%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.44%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 1         | 0.44%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                                        | 1         | 0.44%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.44%   |
| Nvidia GF108 [GeForce GT 420]                                                            | 1         | 0.44%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.44%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 1         | 0.44%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 1         | 0.44%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.44%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 1         | 0.44%   |
| Nvidia C61 [GeForce 6100 nForce 405]                                                     | 1         | 0.44%   |
| Nvidia C51 [GeForce 6150 LE]                                                             | 1         | 0.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 117       | 59.39%  |
| 1 x AMD        | 35        | 17.77%  |
| 1 x Nvidia     | 28        | 14.21%  |
| Intel + Nvidia | 6         | 3.05%   |
| 2 x AMD        | 4         | 2.03%   |
| 1 x SiS        | 4         | 2.03%   |
| 1 x VIA        | 3         | 1.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 175       | 88.38%  |
| Proprietary | 14        | 7.07%   |
| Unknown     | 9         | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 67.17%  |
| 0.01-0.5   | 40        | 20.2%   |
| 0.51-1.0   | 11        | 5.56%   |
| 1.01-2.0   | 10        | 5.05%   |
| 3.01-4.0   | 2         | 1.01%   |
| 7.01-8.0   | 1         | 0.51%   |
| 8.01-16.0  | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 33        | 16.92%  |
| AU Optronics            | 27        | 13.85%  |
| LG Display              | 13        | 6.67%   |
| Acer                    | 12        | 6.15%   |
| Dell                    | 11        | 5.64%   |
| LG Philips              | 8         | 4.1%    |
| Goldstar                | 8         | 4.1%    |
| Chi Mei Optoelectronics | 8         | 4.1%    |
| Hewlett-Packard         | 6         | 3.08%   |
| Chimei Innolux          | 6         | 3.08%   |
| BOE                     | 6         | 3.08%   |
| Sony                    | 5         | 2.56%   |
| HannStar                | 5         | 2.56%   |
| BenQ                    | 5         | 2.56%   |
| Lenovo                  | 4         | 2.05%   |
| CPT                     | 4         | 2.05%   |
| AOC                     | 3         | 1.54%   |
| ViewSonic               | 2         | 1.03%   |
| LG Electronics          | 2         | 1.03%   |
| InfoVision              | 2         | 1.03%   |
| Apple                   | 2         | 1.03%   |
| Ancor Communications    | 2         | 1.03%   |
| Vizio                   | 1         | 0.51%   |
| VIZ                     | 1         | 0.51%   |
| Vestel Elektronik       | 1         | 0.51%   |
| Toshiba                 | 1         | 0.51%   |
| Sharp                   | 1         | 0.51%   |
| Seiko/Epson             | 1         | 0.51%   |
| Sceptre Tech            | 1         | 0.51%   |
| Quanta Display          | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| Optoma                  | 1         | 0.51%   |
| OEM                     | 1         | 0.51%   |
| MPI                     | 1         | 0.51%   |
| KTC                     | 1         | 0.51%   |
| KDC                     | 1         | 0.51%   |
| Insignia                | 1         | 0.51%   |
| HKC                     | 1         | 0.51%   |
| Hitachi                 | 1         | 0.51%   |
| FUS                     | 1         | 0.51%   |
| Fujitsu Siemens         | 1         | 0.51%   |
| Element                 | 1         | 0.51%   |
| CVT                     | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch               | 4         | 1.99%   |
| BOE LCD Monitor BOE0705 1366x768 309x173mm 13.9-inch                    | 3         | 1.49%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 2         | 1%      |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch    | 2         | 1%      |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch | 2         | 1%      |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 1%      |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch             | 2         | 1%      |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                       | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch         | 2         | 1%      |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                        | 2         | 1%      |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 2         | 1%      |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                       | 2         | 1%      |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                       | 1         | 0.5%    |
| VIZ LCD Monitor D50-D1 1920x1080                                        | 1         | 0.5%    |
| ViewSonic VG2230wm-EU VSCA21E 1680x1050 474x296mm 22.0-inch             | 1         | 0.5%    |
| ViewSonic VA2226w-3 VSC2051 1680x1050 495x291mm 22.6-inch               | 1         | 0.5%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.5%    |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                        | 1         | 0.5%    |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                            | 1         | 0.5%    |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                     | 1         | 0.5%    |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch    | 1         | 0.5%    |
| Sony Nvidia Defaul SNY05FA 1366x768 290x170mm 13.2-inch                 | 1         | 0.5%    |
| Sony LCD Monitor TV                                                     | 1         | 0.5%    |
| Sharp LCD SHP0FF0 1360x768                                              | 1         | 0.5%    |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.5%    |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                  | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM05C8 1920x1080 521x293mm 23.5-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM018F 1280x1024 338x270mm 17.0-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch     | 1         | 0.5%    |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch     | 1         | 0.5%    |
| Samsung Electronics SME1920 SAM06B7 1366x768 410x230mm 18.5-inch        | 1         | 0.5%    |
| Samsung Electronics S22B370 SAM0898 1920x1080 477x268mm 21.5-inch       | 1         | 0.5%    |
| Samsung Electronics S22B300 SAM08AB 1920x1080 477x268mm 21.5-inch       | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SyncMaster 2624x1200                    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SMB1930NW 1440x900                      | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC304C 1920x1080 353x198mm 15.9-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC5451 1366x768 340x190mm 15.3-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                       | 1         | 0.5%    |
| Quanta Display LCD Monitor QDS0033 1024x768 304x228mm 15.0-inch         | 1         | 0.5%    |
| Panasonic TH-42PD25U MEIA023 1920x540 920x518mm 41.6-inch               | 1         | 0.5%    |
| Optoma WXGA OTM0550 1280x1024                                           | 1         | 0.5%    |
| OEM 32W_LCD_TV OEM3700 1920x1080                                        | 1         | 0.5%    |
| MPI MPI7002 MPI7002 1920x1080 180x130mm 8.7-inch                        | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 60        | 30.61%  |
| 1920x1080 (FHD)    | 37        | 18.88%  |
| 1280x800 (WXGA)    | 19        | 9.69%   |
| 1280x1024 (SXGA)   | 13        | 6.63%   |
| 1600x900 (HD+)     | 9         | 4.59%   |
| 1024x600           | 9         | 4.59%   |
| 1024x768 (XGA)     | 8         | 4.08%   |
| 1440x900 (WXGA+)   | 6         | 3.06%   |
| 2560x1440 (QHD)    | 5         | 2.55%   |
| 1680x1050 (WSXGA+) | 5         | 2.55%   |
| 1360x768           | 5         | 2.55%   |
| 3840x2160 (4K)     | 4         | 2.04%   |
| 1920x540           | 3         | 1.53%   |
| 2560x1080          | 2         | 1.02%   |
| 1920x1200 (WUXGA)  | 2         | 1.02%   |
| 1024x576           | 2         | 1.02%   |
| Unknown            | 2         | 1.02%   |
| 3840x1080          | 1         | 0.51%   |
| 2624x1200          | 1         | 0.51%   |
| 2048x1152          | 1         | 0.51%   |
| 1600x1200          | 1         | 0.51%   |
| 1280x720 (HD)      | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 32.14%  |
| 13      | 14        | 7.14%   |
| Unknown | 14        | 7.14%   |
| 17      | 11        | 5.61%   |
| 14      | 11        | 5.61%   |
| 10      | 10        | 5.1%    |
| 19      | 9         | 4.59%   |
| 11      | 8         | 4.08%   |
| 27      | 7         | 3.57%   |
| 24      | 6         | 3.06%   |
| 21      | 6         | 3.06%   |
| 18      | 6         | 3.06%   |
| 22      | 5         | 2.55%   |
| 84      | 4         | 2.04%   |
| 31      | 4         | 2.04%   |
| 23      | 3         | 1.53%   |
| 20      | 3         | 1.53%   |
| 12      | 3         | 1.53%   |
| 34      | 2         | 1.02%   |
| 8       | 2         | 1.02%   |
| 74      | 1         | 0.51%   |
| 41      | 1         | 0.51%   |
| 39      | 1         | 0.51%   |
| 32      | 1         | 0.51%   |
| 26      | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 44.1%   |
| 201-300     | 27        | 13.85%  |
| 401-500     | 22        | 11.28%  |
| 501-600     | 16        | 8.21%   |
| 351-400     | 14        | 7.18%   |
| Unknown     | 14        | 7.18%   |
| 1501-2000   | 5         | 2.56%   |
| 601-700     | 4         | 2.05%   |
| 701-800     | 3         | 1.54%   |
| 101-200     | 2         | 1.03%   |
| 801-900     | 1         | 0.51%   |
| 901-1000    | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 116       | 63.39%  |
| 16/10   | 30        | 16.39%  |
| 5/4     | 12        | 6.56%   |
| Unknown | 11        | 6.01%   |
| 4/3     | 10        | 5.46%   |
| 21/9    | 2         | 1.09%   |
| 6/5     | 1         | 0.55%   |
| 1.98    | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 31.79%  |
| 81-90          | 20        | 10.26%  |
| 151-200        | 17        | 8.72%   |
| 201-250        | 14        | 7.18%   |
| Unknown        | 14        | 7.18%   |
| 141-150        | 11        | 5.64%   |
| 41-50          | 10        | 5.13%   |
| 51-60          | 8         | 4.1%    |
| 351-500        | 8         | 4.1%    |
| 301-350        | 6         | 3.08%   |
| More than 1000 | 5         | 2.56%   |
| 71-80          | 3         | 1.54%   |
| 61-70          | 3         | 1.54%   |
| 251-300        | 3         | 1.54%   |
| 121-130        | 3         | 1.54%   |
| 1-40           | 2         | 1.03%   |
| 131-140        | 2         | 1.03%   |
| 501-1000       | 2         | 1.03%   |
| 91-100         | 2         | 1.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 79        | 41.58%  |
| 101-120 | 69        | 36.32%  |
| 121-160 | 23        | 12.11%  |
| Unknown | 14        | 7.37%   |
| 1-50    | 3         | 1.58%   |
| 161-240 | 2         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 167       | 83.92%  |
| 2     | 23        | 11.56%  |
| 0     | 7         | 3.52%   |
| 3     | 2         | 1.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 95        | 28.53%  |
| Intel                             | 63        | 18.92%  |
| Qualcomm Atheros                  | 51        | 15.32%  |
| Broadcom                          | 40        | 12.01%  |
| Marvell Technology Group          | 14        | 4.2%    |
| Broadcom Limited                  | 11        | 3.3%    |
| Ralink Technology                 | 8         | 2.4%    |
| Nvidia                            | 8         | 2.4%    |
| Ralink                            | 6         | 1.8%    |
| VIA Technologies                  | 3         | 0.9%    |
| Silicon Integrated Systems [SiS]  | 3         | 0.9%    |
| Qualcomm Atheros Communications   | 3         | 0.9%    |
| ASUSTek Computer                  | 3         | 0.9%    |
| Samsung Electronics               | 2         | 0.6%    |
| Gemtek                            | 2         | 0.6%    |
| 3Com                              | 2         | 0.6%    |
| TP-Link                           | 1         | 0.3%    |
| Spreadtrum Communications         | 1         | 0.3%    |
| NetGear                           | 1         | 0.3%    |
| Micro Star International          | 1         | 0.3%    |
| MediaTek                          | 1         | 0.3%    |
| Linksys                           | 1         | 0.3%    |
| LG Electronics                    | 1         | 0.3%    |
| JMicron Technology                | 1         | 0.3%    |
| Huawei Technologies               | 1         | 0.3%    |
| Ericsson Business Mobile Networks | 1         | 0.3%    |
| DisplayLink                       | 1         | 0.3%    |
| Dell                              | 1         | 0.3%    |
| D-Link                            | 1         | 0.3%    |
| BUFFALO                           | 1         | 0.3%    |
| Belkin Components                 | 1         | 0.3%    |
| Attansic Technology               | 1         | 0.3%    |
| ASIX Electronics                  | 1         | 0.3%    |
| AMD                               | 1         | 0.3%    |
| ADMtek                            | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 45        | 12.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 6.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.89%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.35%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.08%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 4         | 1.08%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.08%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.08%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.81%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.81%   |
| Ralink RT5370 Wireless Adapter                                          | 3         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.81%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.81%   |
| Intel Wireless 7265                                                     | 3         | 0.81%   |
| Intel Wireless 7260                                                     | 3         | 0.81%   |
| Intel Wireless 3165                                                     | 3         | 0.81%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.81%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 0.81%   |
| Intel 82579V Gigabit Network Connection                                 | 3         | 0.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.81%   |
| Intel 82566DM Gigabit Network Connection                                | 3         | 0.81%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.54%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.54%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.54%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.54%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 2         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.54%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.54%   |
| Intel WiFi Link 5100                                                    | 2         | 0.54%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.54%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.54%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.54%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.54%   |
| Intel 82573L Gigabit Ethernet Controller                                | 2         | 0.54%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 2         | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.54%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 24.14%  |
| Qualcomm Atheros                | 37        | 21.26%  |
| Realtek Semiconductor           | 29        | 16.67%  |
| Broadcom                        | 29        | 16.67%  |
| Ralink Technology               | 8         | 4.6%    |
| Ralink                          | 6         | 3.45%   |
| Broadcom Limited                | 5         | 2.87%   |
| Qualcomm Atheros Communications | 3         | 1.72%   |
| ASUSTek Computer                | 3         | 1.72%   |
| Gemtek                          | 2         | 1.15%   |
| VIA Technologies                | 1         | 0.57%   |
| TP-Link                         | 1         | 0.57%   |
| Samsung Electronics             | 1         | 0.57%   |
| NetGear                         | 1         | 0.57%   |
| Micro Star International        | 1         | 0.57%   |
| Marvell Technology Group        | 1         | 0.57%   |
| Linksys                         | 1         | 0.57%   |
| D-Link                          | 1         | 0.57%   |
| BUFFALO                         | 1         | 0.57%   |
| Belkin Components               | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 9         | 5.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 7         | 4%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 7         | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 6         | 3.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 6         | 3.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 2.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 2.86%   |
| Ralink MT7601U Wireless Adapter                                               | 4         | 2.29%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 4         | 2.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 2.29%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 4         | 2.29%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 4         | 2.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 3         | 1.71%   |
| Realtek 802.11ac NIC                                                          | 3         | 1.71%   |
| Ralink RT5370 Wireless Adapter                                                | 3         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 3         | 1.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 3         | 1.71%   |
| Intel Wireless 7265                                                           | 3         | 1.71%   |
| Intel Wireless 7260                                                           | 3         | 1.71%   |
| Intel Wireless 3165                                                           | 3         | 1.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 1.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2         | 1.14%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 2         | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.14%   |
| Realtek RTL8187B Wireless Adapter                                             | 2         | 1.14%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 2         | 1.14%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                     | 2         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.14%   |
| Qualcomm Atheros AR9271 802.11n                                               | 2         | 1.14%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 2         | 1.14%   |
| Intel WiFi Link 5100                                                          | 2         | 1.14%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 1.14%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 1.14%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.14%   |
| Gemtek WUBR-177G [Ralink RT2571W]                                             | 2         | 1.14%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.14%   |
| VIA VIA VNT-6656 [WiFi 802.11b/g USB Dongle]                                  | 1         | 0.57%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                   | 1         | 0.57%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                              | 1         | 0.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.57%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.57%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 1         | 0.57%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.57%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.57%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.57%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.57%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 1         | 0.57%   |
| Ralink RT2561/RT61 rev B 802.11g                                              | 1         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.57%   |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.57%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)       | 1         | 0.57%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.57%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                           | 1         | 0.57%   |
| Micro Star International RT2573                                               | 1         | 0.57%   |
| Marvell Group 88w8335 [Libertas] 802.11b/g Wireless                           | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 82        | 43.85%  |
| Intel                            | 32        | 17.11%  |
| Qualcomm Atheros                 | 15        | 8.02%   |
| Broadcom                         | 14        | 7.49%   |
| Marvell Technology Group         | 13        | 6.95%   |
| Nvidia                           | 8         | 4.28%   |
| Broadcom Limited                 | 7         | 3.74%   |
| Silicon Integrated Systems [SiS] | 3         | 1.6%    |
| VIA Technologies                 | 2         | 1.07%   |
| 3Com                             | 2         | 1.07%   |
| Spreadtrum Communications        | 1         | 0.53%   |
| Samsung Electronics              | 1         | 0.53%   |
| MediaTek                         | 1         | 0.53%   |
| LG Electronics                   | 1         | 0.53%   |
| JMicron Technology               | 1         | 0.53%   |
| DisplayLink                      | 1         | 0.53%   |
| Attansic Technology              | 1         | 0.53%   |
| ASIX Electronics                 | 1         | 0.53%   |
| ADMtek                           | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 23.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 13.3%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 4.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 3.19%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 2.66%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 2.13%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.6%    |
| Nvidia MCP61 Ethernet                                             | 3         | 1.6%    |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.6%    |
| Intel 82566DM Gigabit Network Connection                          | 3         | 1.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.06%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.06%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.06%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 1.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.06%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.06%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.06%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 2         | 1.06%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 2         | 1.06%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 1.06%   |
| 3Com 3c905B 100BaseTX [Cyclone]                                   | 2         | 1.06%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.53%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.53%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.53%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.53%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 0.53%   |
| MediaTek Infinix X683                                             | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.53%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller              | 1         | 0.53%   |
| LG G2 Android Phone [tethering mode]                              | 1         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.53%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.53%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.53%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.53%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.53%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.53%   |
| Intel 82567LM-2 Gigabit Network Connection                        | 1         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 1         | 0.53%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 180       | 51.28%  |
| WiFi     | 164       | 46.72%  |
| Modem    | 7         | 1.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 51.06%  |
| Ethernet | 139       | 48.94%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 118       | 59.9%   |
| 1     | 71        | 36.04%  |
| 0     | 6         | 3.05%   |
| 3     | 2         | 1.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 192       | 96.48%  |
| Yes  | 7         | 3.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 18        | 22.22%  |
| Qualcomm Atheros Communications | 10        | 12.35%  |
| Broadcom                        | 10        | 12.35%  |
| Cambridge Silicon Radio         | 7         | 8.64%   |
| Hewlett-Packard                 | 5         | 6.17%   |
| Toshiba                         | 4         | 4.94%   |
| Realtek Semiconductor           | 4         | 4.94%   |
| Lite-On Technology              | 4         | 4.94%   |
| IMC Networks                    | 3         | 3.7%    |
| Foxconn International           | 3         | 3.7%    |
| Ralink                          | 2         | 2.47%   |
| Foxconn / Hon Hai               | 2         | 2.47%   |
| Dell                            | 2         | 2.47%   |
| Apple                           | 2         | 2.47%   |
| Alps Electric                   | 2         | 2.47%   |
| Primax Electronics              | 1         | 1.23%   |
| Kensington                      | 1         | 1.23%   |
| ASUSTek Computer                | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 11        | 13.58%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 8.64%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 6.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 6.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 3.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 3.7%    |
| Intel Bluetooth wireless interface                  | 3         | 3.7%    |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 3.7%    |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 3.7%    |
| Ralink RT3290 Bluetooth                             | 2         | 2.47%   |
| Lite-On Bluetooth Device                            | 2         | 2.47%   |
| Dell DW375 Bluetooth Module                         | 2         | 2.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.47%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.23%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.23%   |
| Toshiba Bluetooth Device                            | 1         | 1.23%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.23%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.23%   |
| Realtek Bluetooth Radio                             | 1         | 1.23%   |
| Realtek 802.11n WLAN Adapter                        | 1         | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.23%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1         | 1.23%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.23%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.23%   |
| Kensington Bluetooth EDR Dongle                     | 1         | 1.23%   |
| Intel AX200 Bluetooth                               | 1         | 1.23%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.23%   |
| IMC Networks Bluetooth module                       | 1         | 1.23%   |
| IMC Networks Bluetooth Device                       | 1         | 1.23%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.23%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.23%   |
| Broadcom IBM Integrated Bluetooth IV                | 1         | 1.23%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.23%   |
| Broadcom Bluetooth Controller                       | 1         | 1.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.23%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.23%   |
| ASUS Bluetooth Radio                                | 1         | 1.23%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.23%   |
| Apple Bluetooth HCI                                 | 1         | 1.23%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.23%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 143       | 62.45%  |
| AMD                                             | 37        | 16.16%  |
| Nvidia                                          | 26        | 11.35%  |
| VIA Technologies                                | 5         | 2.18%   |
| C-Media Electronics                             | 5         | 2.18%   |
| Silicon Integrated Systems [SiS]                | 4         | 1.75%   |
| Creative Labs                                   | 4         | 1.75%   |
| ULi Electronics                                 | 1         | 0.44%   |
| Logitech                                        | 1         | 0.44%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.44%   |
| Creative Technology                             | 1         | 0.44%   |
| Corsair                                         | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 33        | 12.64%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 8.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 6.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.98%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 3.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 3.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.68%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 1.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.92%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 1.53%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 1.53%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1.15%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.15%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.15%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.15%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.15%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.15%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.15%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2         | 0.77%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 2         | 0.77%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 2         | 0.77%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 2         | 0.77%   |
| C-Media Electronics CM108 Audio Controller                                                        | 2         | 0.77%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.77%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.77%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.77%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 0.77%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.77%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 2         | 0.77%   |
| ULi Electronics HD Audio Controller                                                               | 1         | 0.38%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia MCP73 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.38%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia CK804 AC'97 Audio Controller                                                               | 1         | 0.38%   |
| Logitech Z305                                                                                     | 1         | 0.38%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter                          | 1         | 0.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 12        | 26.67%  |
| Samsung Electronics | 10        | 22.22%  |
| SK Hynix            | 5         | 11.11%  |
| Micron Technology   | 4         | 8.89%   |
| Kingston            | 3         | 6.67%   |
| Crucial             | 3         | 6.67%   |
| Toshiba             | 1         | 2.22%   |
| Smart               | 1         | 2.22%   |
| Nanya Technology    | 1         | 2.22%   |
| G.Skill             | 1         | 2.22%   |
| Elpida              | 1         | 2.22%   |
| Corsair             | 1         | 2.22%   |
| A-DATA Technology   | 1         | 2.22%   |
| 48spaces            | 1         | 2.22%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 3.92%   |
| Unknown RAM Module SODIMM DDR                                             | 1         | 1.96%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 1.96%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 1.96%   |
| Unknown RAM Module 2GB DIMM DDR2                                          | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DRAM                                     | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                            | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                            | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                            | 1         | 1.96%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 1.96%   |
| Unknown RAM Module 1GB DIMM DDR2                                          | 1         | 1.96%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                              | 1         | 1.96%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                    | 1         | 1.96%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s                                  | 1         | 1.96%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s                        | 1         | 1.96%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s                         | 1         | 1.96%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR 800MT/s                       | 1         | 1.96%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.96%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.96%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.96%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.96%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s                 | 1         | 1.96%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.96%   |
| SK Hynix RAM HMT125U6TFR8C-H9 2GB DIMM DDR3 1333MT/s                      | 1         | 1.96%   |
| Samsung RAM Module 2048MB DIMM DDR3 1333MT/s                              | 1         | 1.96%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s                       | 1         | 1.96%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                  | 1         | 1.96%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.96%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s                  | 1         | 1.96%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s                       | 1         | 1.96%   |
| Samsung RAM M378B2873FHS-CH9 1GB DIMM DDR3 1333MT/s                       | 1         | 1.96%   |
| Nanya RAM NT2GC64B8HC0NF-CG 2048MB DIMM DDR3 1333MT/s                     | 1         | 1.96%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s                               | 1         | 1.96%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                       | 1         | 1.96%   |
| Micron RAM 8HTF12864AY-800J1 1GB DIMM DDR2 800MT/s                        | 1         | 1.96%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.96%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s                          | 1         | 1.96%   |
| Kingston RAM 9905734-019.A00G 16384MB DIMM DDR4 2400MT/s                  | 1         | 1.96%   |
| Kingston RAM 9905713-017.A00G 4096MB DIMM DDR4 2400MT/s                   | 1         | 1.96%   |
| Kingston RAM 9905428-196.A00LF 8192MB SODIMM DDR3 1333MT/s                | 1         | 1.96%   |
| G.Skill RAM F3-1866C10-8GAB 8GB DIMM DDR3 1866MT/s                        | 1         | 1.96%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2048MB SODIMM DDR3 1334MT/s                  | 1         | 1.96%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.96%   |
| Crucial RAM CT102464BF1339.C16 8GB SODIMM DDR3 1333MT/s                   | 1         | 1.96%   |
| Crucial RAM BLS8G3D18ADS3 8192MB DIMM DDR3 1866MT/s                       | 1         | 1.96%   |
| Corsair RAM CMSX8GX3M1A1600C10 8192MB SODIMM DDR3 1600MT/s                | 1         | 1.96%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.96%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 29        | 67.44%  |
| DDR2    | 5         | 11.63%  |
| SDRAM   | 2         | 4.65%   |
| DDR4    | 2         | 4.65%   |
| DDR     | 2         | 4.65%   |
| Unknown | 2         | 4.65%   |
| DRAM    | 1         | 2.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 69.05%  |
| DIMM         | 11        | 26.19%  |
| Row Of Chips | 1         | 2.38%   |
| Chip         | 1         | 2.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 17        | 36.17%  |
| 2048    | 15        | 31.91%  |
| 8192    | 7         | 14.89%  |
| 1024    | 6         | 12.77%  |
| 16384   | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 16        | 35.56%  |
| 1333    | 8         | 17.78%  |
| Unknown | 6         | 13.33%  |
| 800     | 3         | 6.67%   |
| 1334    | 2         | 4.44%   |
| 1066    | 2         | 4.44%   |
| 667     | 2         | 4.44%   |
| 41632   | 1         | 2.22%   |
| 3200    | 1         | 2.22%   |
| 2400    | 1         | 2.22%   |
| 1867    | 1         | 2.22%   |
| 1866    | 1         | 2.22%   |
| 100     | 1         | 2.22%   |

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
| Seiko Epson XP-240 Series            | 1         | 20%     |
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
| Chicony Electronics                    | 29        | 27.36%  |
| Acer                                   | 10        | 9.43%   |
| IMC Networks                           | 9         | 8.49%   |
| Suyin                                  | 7         | 6.6%    |
| Realtek Semiconductor                  | 7         | 6.6%    |
| Z-Star Microelectronics                | 6         | 5.66%   |
| Sunplus Innovation Technology          | 5         | 4.72%   |
| Ricoh                                  | 5         | 4.72%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.72%   |
| Microdia                               | 4         | 3.77%   |
| Silicon Motion                         | 3         | 2.83%   |
| Importek                               | 3         | 2.83%   |
| Syntek                                 | 2         | 1.89%   |
| Samsung Electronics                    | 2         | 1.89%   |
| Cubeternet                             | 2         | 1.89%   |
| Logitech                               | 1         | 0.94%   |
| Lite-On Technology                     | 1         | 0.94%   |
| DigiTech                               | 1         | 0.94%   |
| Aveo Technology                        | 1         | 0.94%   |
| Apple                                  | 1         | 0.94%   |
| ALi                                    | 1         | 0.94%   |
| Alcor Micro                            | 1         | 0.94%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                                       | 4         | 3.77%   |
| Acer EasyCamera                                                     | 4         | 3.77%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                            | 3         | 2.83%   |
| IMC Networks UVC VGA Webcam                                         | 3         | 2.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD             | 3         | 2.83%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 2         | 1.89%   |
| Ricoh Sony Vaio Integrated Webcam                                   | 2         | 1.89%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                  | 2         | 1.89%   |
| Realtek HD WebCam                                                   | 2         | 1.89%   |
| Importek HP Webcam-50                                               | 2         | 1.89%   |
| IMC Networks USB2.0 UVC HD Webcam                                   | 2         | 1.89%   |
| IMC Networks Integrated Webcam                                      | 2         | 1.89%   |
| Chicony VGA Webcam                                                  | 2         | 1.89%   |
| Chicony USB 2.0 Camera                                              | 2         | 1.89%   |
| Chicony TOSHIBA Web Camera - HD                                     | 2         | 1.89%   |
| Chicony Lenovo EasyCamera                                           | 2         | 1.89%   |
| Chicony CNF9055 Toshiba Webcam                                      | 2         | 1.89%   |
| Acer Lenovo EasyCamera                                              | 2         | 1.89%   |
| Acer Integrated Camera                                              | 2         | 1.89%   |
| Z-Star Vega USB 2.0 Camera                                          | 1         | 0.94%   |
| Z-Star Sirius USB2.0 Camera                                         | 1         | 0.94%   |
| Syntek USB Camera Device                                            | 1         | 0.94%   |
| Syntek Lenovo EasyCamera                                            | 1         | 0.94%   |
| Suyin HP Webcam 101                                                 | 1         | 0.94%   |
| Suyin HP Webcam                                                     | 1         | 0.94%   |
| Suyin HP Truevision HD                                              | 1         | 0.94%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)         | 1         | 0.94%   |
| Sunplus SPCA2281 Web Camera                                         | 1         | 0.94%   |
| Sunplus Laptop Integrated Webcam HD                                 | 1         | 0.94%   |
| Sunplus HP TrueVision HD Camera                                     | 1         | 0.94%   |
| Sunplus HP HD Webcam [Fixed]                                        | 1         | 0.94%   |
| Sunplus ASUS USB2.0 Webcam                                          | 1         | 0.94%   |
| Silicon Motion WebCam SC-0311139N                                   | 1         | 0.94%   |
| Silicon Motion HP Webcam                                            | 1         | 0.94%   |
| Silicon Motion 300k Pixel Camera                                    | 1         | 0.94%   |
| Ricoh Integrated Webcam                                             | 1         | 0.94%   |
| Realtek USB Camera                                                  | 1         | 0.94%   |
| Realtek Lenovo EasyCamera                                           | 1         | 0.94%   |
| Realtek Integrated_Webcam_HD                                        | 1         | 0.94%   |
| Realtek Integrated Webcam                                           | 1         | 0.94%   |
| Realtek HP Truevision HD integrated webcam                          | 1         | 0.94%   |
| Microdia Sonix USB 2.0 Camera                                       | 1         | 0.94%   |
| Microdia Laptop_Integrated_Webcam_0.3M                              | 1         | 0.94%   |
| Microdia Integrated Webcam                                          | 1         | 0.94%   |
| Microdia 1.3 MPixel Integrated Webcam                               | 1         | 0.94%   |
| Logitech Webcam C270                                                | 1         | 0.94%   |
| Lite-On TOSHIBA Web Camera                                          | 1         | 0.94%   |
| Importek Webcam-101                                                 | 1         | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                                  | 1         | 0.94%   |
| IMC Networks TOSHIBA Web Camera - HD                                | 1         | 0.94%   |
| DigiTech USB 2.0 PC Camera                                          | 1         | 0.94%   |
| Cubeternet USB2.0 Camera                                            | 1         | 0.94%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1         | 0.94%   |
| Chicony VGA 24fps UVC Webcam                                        | 1         | 0.94%   |
| Chicony USB2.0 VGA UVC WebCam                                       | 1         | 0.94%   |
| Chicony USB2.0 UVC WebCam                                           | 1         | 0.94%   |
| Chicony USB2.0 HD UVC WebCam                                        | 1         | 0.94%   |
| Chicony Integrated Camera (1280x720@30)                             | 1         | 0.94%   |
| Chicony Integrated Camera                                           | 1         | 0.94%   |
| Chicony HP Wide Vision HD                                           | 1         | 0.94%   |

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
| Broadcom    | 3         | 60%     |
| O2 Micro    | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 138       | 69.35%  |
| 1     | 49        | 24.62%  |
| 2     | 12        | 6.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 15        | 21.43%  |
| Fingerprint reader       | 15        | 21.43%  |
| Graphics card            | 10        | 14.29%  |
| Storage                  | 5         | 7.14%   |
| Communication controller | 5         | 7.14%   |
| Chipcard                 | 5         | 7.14%   |
| Modem                    | 3         | 4.29%   |
| Bluetooth                | 3         | 4.29%   |
| Multimedia controller    | 2         | 2.86%   |
| Camera                   | 2         | 2.86%   |
| Unassigned class         | 1         | 1.43%   |
| Storage/ide              | 1         | 1.43%   |
| Sound                    | 1         | 1.43%   |
| Net/ethernet             | 1         | 1.43%   |
| Flash memory             | 1         | 1.43%   |

