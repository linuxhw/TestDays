Peppermint 10 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Peppermint 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire R3-131T              | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| HP            | 15                          | [a976f1d357](https://linux-hardware.org/?probe=a976f1d357) | Sep 28, 2021 |
| Unknown       | Unknown                     | [b54d6779c8](https://linux-hardware.org/?probe=b54d6779c8) | Sep 19, 2021 |
| Packard Be... | EasyNote TK85               | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| Toshiba       | dynabook Satellite B552/... | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| ASUSTek       | K52F                        | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| Sony          | VGN-S55B_S                  | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| Packard Be... | EasyNote TK85               | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| Sony          | VGN-S55B_S                  | [e531cd57e6](https://linux-hardware.org/?probe=e531cd57e6) | Aug 15, 2021 |
| HP            | EliteBook 820 G1            | [830eaafeac](https://linux-hardware.org/?probe=830eaafeac) | Aug 08, 2021 |
| Samsung       | N150P/N210P/N220P           | [0a9b2f9147](https://linux-hardware.org/?probe=0a9b2f9147) | Aug 08, 2021 |
| Olivetti      | CL133A                      | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [113c8ab052](https://linux-hardware.org/?probe=113c8ab052) | Jul 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [827993d9c3](https://linux-hardware.org/?probe=827993d9c3) | Jul 17, 2021 |
| Olivetti      | CL133A                      | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| Dell          | Precision M4600             | [0242a479d2](https://linux-hardware.org/?probe=0242a479d2) | Jul 13, 2021 |
| Olivetti      | CL133A                      | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| HP            | Compaq Mini 110c-1100       | [9ba35acb61](https://linux-hardware.org/?probe=9ba35acb61) | Jun 24, 2021 |
| HP            | Compaq Mini 110c-1100       | [399e422d5b](https://linux-hardware.org/?probe=399e422d5b) | Jun 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09171395a9](https://linux-hardware.org/?probe=09171395a9) | Jun 22, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdbc4c8c02](https://linux-hardware.org/?probe=cdbc4c8c02) | Jun 22, 2021 |
| Toshiba       | NB500                       | [e5095d1545](https://linux-hardware.org/?probe=e5095d1545) | Jun 21, 2021 |
| Lenovo        | ThinkPad Edge E431 62775... | [6d6430f8ff](https://linux-hardware.org/?probe=6d6430f8ff) | Jun 18, 2021 |
| Acer          | AOA150                      | [7cbadcfcce](https://linux-hardware.org/?probe=7cbadcfcce) | Jun 13, 2021 |
| Toshiba       | NB500                       | [0a57436b83](https://linux-hardware.org/?probe=0a57436b83) | Jun 13, 2021 |
| Toshiba       | NB500                       | [be659779e6](https://linux-hardware.org/?probe=be659779e6) | Jun 13, 2021 |
| HP            | Mini 110-1100               | [dcaac9d2ce](https://linux-hardware.org/?probe=dcaac9d2ce) | Jun 04, 2021 |
| HP            | Mini 110-1100               | [d919b139c6](https://linux-hardware.org/?probe=d919b139c6) | Jun 04, 2021 |
| HP            | Presario C500 (RZ343UA#A... | [d37099a83d](https://linux-hardware.org/?probe=d37099a83d) | May 25, 2021 |
| HP            | Presario C500 (RZ343UA#A... | [4aef9f472c](https://linux-hardware.org/?probe=4aef9f472c) | May 17, 2021 |
| Sony          | VGN-S55B_S                  | [a874601f76](https://linux-hardware.org/?probe=a874601f76) | May 05, 2021 |
| JPSaCouto     | Intel powered classmate ... | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| Acer          | Extensa 5510                | [8e9e536486](https://linux-hardware.org/?probe=8e9e536486) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | [12b76c8bca](https://linux-hardware.org/?probe=12b76c8bca) | Apr 24, 2021 |
| HP            | EliteBook 2530p             | [d54424038e](https://linux-hardware.org/?probe=d54424038e) | Apr 18, 2021 |
| HP            | EliteBook 2530p             | [562d38cca5](https://linux-hardware.org/?probe=562d38cca5) | Apr 18, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | [87befc0401](https://linux-hardware.org/?probe=87befc0401) | Apr 16, 2021 |
| Dell          | Inspiron 1545               | [a23936a0de](https://linux-hardware.org/?probe=a23936a0de) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Li1705                | [56c5cc70d1](https://linux-hardware.org/?probe=56c5cc70d1) | Apr 07, 2021 |
| Fujitsu Si... | AMILO Li1705                | [71e906faa3](https://linux-hardware.org/?probe=71e906faa3) | Apr 07, 2021 |
| Dell          | Latitude 7410               | [a72bb094fd](https://linux-hardware.org/?probe=a72bb094fd) | Mar 26, 2021 |
| Dell          | Vostro 3550                 | [ebd077e7f4](https://linux-hardware.org/?probe=ebd077e7f4) | Mar 16, 2021 |
| HP            | Pavilion g6                 | [6079cacf9b](https://linux-hardware.org/?probe=6079cacf9b) | Mar 14, 2021 |
| Samsung       | R530/R730/R540              | [a9fd173c51](https://linux-hardware.org/?probe=a9fd173c51) | Mar 13, 2021 |
| Dell          | Inspiron 1012               | [4c4bb4bd4a](https://linux-hardware.org/?probe=4c4bb4bd4a) | Mar 04, 2021 |
| Dell          | Inspiron N5050              | [b0cdfde6d1](https://linux-hardware.org/?probe=b0cdfde6d1) | Mar 02, 2021 |
| Dell          | Inspiron N5050              | [492714801f](https://linux-hardware.org/?probe=492714801f) | Mar 02, 2021 |
| ASUSTek       | K50C                        | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| Lenovo        | ThinkPad R60 94566FG        | [f0eb3f1d77](https://linux-hardware.org/?probe=f0eb3f1d77) | Feb 19, 2021 |
| Medion        | Akoya E4214 MD99570         | [3ae1e824ed](https://linux-hardware.org/?probe=3ae1e824ed) | Feb 13, 2021 |
| Toshiba       | Satellite L500              | [003b1f0799](https://linux-hardware.org/?probe=003b1f0799) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | [a642972ffa](https://linux-hardware.org/?probe=a642972ffa) | Feb 12, 2021 |
| Apple         | MacBookAir3,2               | [e4d417012f](https://linux-hardware.org/?probe=e4d417012f) | Feb 08, 2021 |
| ASUSTek       | X541NA                      | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Unknown       | Unknown                     | [cf6b92a979](https://linux-hardware.org/?probe=cf6b92a979) | Feb 07, 2021 |
| Toshiba       | Satellite L300              | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Sony          | VPCZ21V9E                   | [f0e8428fc2](https://linux-hardware.org/?probe=f0e8428fc2) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK T902               | [b0aa1bff61](https://linux-hardware.org/?probe=b0aa1bff61) | Jan 12, 2021 |
| Acer          | AOD255                      | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
| Sony          | VPCZ21V9E                   | [27d806e418](https://linux-hardware.org/?probe=27d806e418) | Jan 02, 2021 |
| Sony          | VPCZ21V9E                   | [a1dc463ae7](https://linux-hardware.org/?probe=a1dc463ae7) | Jan 02, 2021 |
| Lenovo        | ThinkPad T450 20BUS3CF00    | [4dde602ff6](https://linux-hardware.org/?probe=4dde602ff6) | Jan 01, 2021 |
| Acer          | Extensa 5630                | [eed68dd316](https://linux-hardware.org/?probe=eed68dd316) | Dec 30, 2020 |
| Sony          | VPCZ21V9E                   | [b34a53e0e2](https://linux-hardware.org/?probe=b34a53e0e2) | Dec 29, 2020 |
| Acer          | Extensa 5510                | [efd4fce381](https://linux-hardware.org/?probe=efd4fce381) | Dec 29, 2020 |
| Acer          | Aspire 5738                 | [56f8292d5b](https://linux-hardware.org/?probe=56f8292d5b) | Dec 23, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Acer          | Extensa 5220                | [3dfca3a90f](https://linux-hardware.org/?probe=3dfca3a90f) | Dec 12, 2020 |
| Acer          | Extensa 5220                | [9b67134373](https://linux-hardware.org/?probe=9b67134373) | Dec 12, 2020 |
| Dell          | Precision M4700             | [58d2d0e8d4](https://linux-hardware.org/?probe=58d2d0e8d4) | Dec 11, 2020 |
| Dell          | Precision M4700             | [379e1a461c](https://linux-hardware.org/?probe=379e1a461c) | Dec 09, 2020 |
| Dell          | Inspiron N5050              | [ac934f7ac7](https://linux-hardware.org/?probe=ac934f7ac7) | Dec 07, 2020 |
| Dell          | Inspiron N5050              | [8f2d17e846](https://linux-hardware.org/?probe=8f2d17e846) | Dec 07, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | [7499600f8c](https://linux-hardware.org/?probe=7499600f8c) | Dec 02, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | [fed85859bc](https://linux-hardware.org/?probe=fed85859bc) | Dec 02, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| ASUSTek       | 1015PN                      | [c0c9898136](https://linux-hardware.org/?probe=c0c9898136) | Nov 19, 2020 |
| ASUSTek       | 1015PN                      | [f19c7014be](https://linux-hardware.org/?probe=f19c7014be) | Nov 19, 2020 |
| Dell          | Latitude E7440              | [222b0a563a](https://linux-hardware.org/?probe=222b0a563a) | Nov 15, 2020 |
| Sony          | VGN-S55B_S                  | [534a526520](https://linux-hardware.org/?probe=534a526520) | Nov 08, 2020 |
| HP            | Pavilion dv8000 (EZ590UA... | [1e64c078af](https://linux-hardware.org/?probe=1e64c078af) | Nov 04, 2020 |
| Samsung       | N150P/N210P/N220P           | [808224d57c](https://linux-hardware.org/?probe=808224d57c) | Oct 30, 2020 |
| ASUSTek       | X205TA                      | [f7fc9c9932](https://linux-hardware.org/?probe=f7fc9c9932) | Oct 20, 2020 |
| Google        | Gnawty                      | [6bb50a022d](https://linux-hardware.org/?probe=6bb50a022d) | Oct 10, 2020 |
| Toshiba       | QOSMIO F755                 | [defa9c775a](https://linux-hardware.org/?probe=defa9c775a) | Oct 01, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [64da7044cf](https://linux-hardware.org/?probe=64da7044cf) | Sep 26, 2020 |
| Medion        | Akoya E4214 MD99570         | [e45ead8de9](https://linux-hardware.org/?probe=e45ead8de9) | Sep 20, 2020 |
| Samsung       | R610                        | [db61c853a2](https://linux-hardware.org/?probe=db61c853a2) | Sep 17, 2020 |
| ASUSTek       | T101HA                      | [036f4f2304](https://linux-hardware.org/?probe=036f4f2304) | Sep 15, 2020 |
| ASUSTek       | P53E                        | [75d3fa4178](https://linux-hardware.org/?probe=75d3fa4178) | Sep 04, 2020 |
| Lenovo        | IdeaPad Z460 20059          | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| HP            | Stream Laptop 11-y0XX       | [06dd4aecb5](https://linux-hardware.org/?probe=06dd4aecb5) | Sep 01, 2020 |
| Acer          | TravelMate B115-M           | [d3395dca0c](https://linux-hardware.org/?probe=d3395dca0c) | Aug 30, 2020 |
| Itautec       | Infoway                     | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| Toshiba       | Satellite C660              | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Samsung       | N150P                       | [17e2e411da](https://linux-hardware.org/?probe=17e2e411da) | Aug 07, 2020 |
| Toshiba       | Satellite L310              | [bf2bd8711e](https://linux-hardware.org/?probe=bf2bd8711e) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | [304d7ac49d](https://linux-hardware.org/?probe=304d7ac49d) | Aug 02, 2020 |
| HP            | EliteBook 2740p             | [b87f4916b6](https://linux-hardware.org/?probe=b87f4916b6) | Jul 27, 2020 |
| HP            | Compaq Presario CQ40        | [aaf338c454](https://linux-hardware.org/?probe=aaf338c454) | Jul 24, 2020 |
| Dell          | Latitude E6420              | [1db19a0158](https://linux-hardware.org/?probe=1db19a0158) | Jul 24, 2020 |
| Sony          | VGN-S55B_S                  | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| HP            | EliteBook 8570w             | [bd697a03f8](https://linux-hardware.org/?probe=bd697a03f8) | Jul 19, 2020 |
| Itautec       | Infoway                     | [27a7c624d8](https://linux-hardware.org/?probe=27a7c624d8) | Jul 17, 2020 |
| Itautec       | Infoway                     | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
| Positivo      | N1103                       | [3cdb7fc95e](https://linux-hardware.org/?probe=3cdb7fc95e) | Jul 13, 2020 |
| Toshiba       | PORTEGE R500                | [e7c5c010bd](https://linux-hardware.org/?probe=e7c5c010bd) | Jul 12, 2020 |
| Toshiba       | PORTEGE R500                | [fd50b5e2a7](https://linux-hardware.org/?probe=fd50b5e2a7) | Jul 12, 2020 |
| Dell          | Latitude E6420              | [52d11b26d3](https://linux-hardware.org/?probe=52d11b26d3) | Jul 09, 2020 |
| Acer          | Aspire R3-131T              | [dbecc119b2](https://linux-hardware.org/?probe=dbecc119b2) | Jul 08, 2020 |
| Sony          | VGN-S55B_S                  | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| HP            | Notebook                    | [841b43ba94](https://linux-hardware.org/?probe=841b43ba94) | Jun 14, 2020 |
| Lenovo        | B490 37722SP                | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| Toshiba       | Satellite L500              | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Mini 110-1000               | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown       | Unknown                     | [eef6f0a50b](https://linux-hardware.org/?probe=eef6f0a50b) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | [94839129c9](https://linux-hardware.org/?probe=94839129c9) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | [adf1cefbf5](https://linux-hardware.org/?probe=adf1cefbf5) | May 19, 2020 |
| Unknown       | Unknown                     | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Toshiba       | Satellite L500              | [6782b31a2e](https://linux-hardware.org/?probe=6782b31a2e) | May 17, 2020 |
| Clevo         | W55xEU                      | [f1ad04bd23](https://linux-hardware.org/?probe=f1ad04bd23) | May 16, 2020 |
| Toshiba       | Satellite M70               | [c9e02a940d](https://linux-hardware.org/?probe=c9e02a940d) | May 13, 2020 |
| ASUSTek       | Q400A                       | [075d494ee2](https://linux-hardware.org/?probe=075d494ee2) | May 10, 2020 |
| Lenovo        | B575 1450A7U                | [b781397fa7](https://linux-hardware.org/?probe=b781397fa7) | May 05, 2020 |
| Toshiba       | Satellite C660              | [3d10f5b306](https://linux-hardware.org/?probe=3d10f5b306) | May 03, 2020 |
| Toshiba       | Satellite C660              | [0e91d35b8e](https://linux-hardware.org/?probe=0e91d35b8e) | May 03, 2020 |
| Sony          | VGN-FW140E                  | [8aad1d7bfc](https://linux-hardware.org/?probe=8aad1d7bfc) | May 02, 2020 |
| Toshiba       | Satellite C660              | [bc3bd72199](https://linux-hardware.org/?probe=bc3bd72199) | May 01, 2020 |
| Toshiba       | Satellite C660              | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| Toshiba       | Satellite PRO C850          | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5ddee791c7](https://linux-hardware.org/?probe=5ddee791c7) | Apr 20, 2020 |
| ASUSTek       | X45U                        | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Acer          | Aspire ES1-521              | [20e7fea349](https://linux-hardware.org/?probe=20e7fea349) | Apr 08, 2020 |
| Lenovo        | 433328G                     | [3c5b9e3703](https://linux-hardware.org/?probe=3c5b9e3703) | Apr 07, 2020 |
| Acer          | Aspire ES1-521              | [0c74c17c24](https://linux-hardware.org/?probe=0c74c17c24) | Apr 07, 2020 |
| HP            | 2133 (FU346EA)              | [499f685a66](https://linux-hardware.org/?probe=499f685a66) | Mar 31, 2020 |
| HP            | 2133 (FU346EA)              | [2c6f9bf922](https://linux-hardware.org/?probe=2c6f9bf922) | Mar 31, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | [8fae01eff8](https://linux-hardware.org/?probe=8fae01eff8) | Mar 31, 2020 |
| HP            | 255 G2                      | [7cfb9e5a0e](https://linux-hardware.org/?probe=7cfb9e5a0e) | Mar 25, 2020 |
| Clevo         | W55xEU                      | [09d70e49b4](https://linux-hardware.org/?probe=09d70e49b4) | Mar 23, 2020 |
| ASUSTek       | F3E                         | [e01cca6624](https://linux-hardware.org/?probe=e01cca6624) | Mar 18, 2020 |
| ASUSTek       | F3E                         | [51ae68d38f](https://linux-hardware.org/?probe=51ae68d38f) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [5d53434528](https://linux-hardware.org/?probe=5d53434528) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [8491571d31](https://linux-hardware.org/?probe=8491571d31) | Mar 17, 2020 |
| ASUSTek       | F3E                         | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | Pavilion dv6500             | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| Lenovo        | 3000 N500 423374G           | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| eMachines     | E520                        | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| HP            | Pavilion dv4                | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Toshiba       | Satellite C850-F117         | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Apple         | MacBook4,1                  | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| Apple         | MacBook4,1                  | [516c8bcbc2](https://linux-hardware.org/?probe=516c8bcbc2) | Feb 06, 2020 |
| Apple         | MacBook4,1                  | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Apple         | MacBook4,1                  | [17eb93e1dc](https://linux-hardware.org/?probe=17eb93e1dc) | Feb 04, 2020 |
| Toshiba       | NB520                       | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | [20c5cb5e37](https://linux-hardware.org/?probe=20c5cb5e37) | Feb 02, 2020 |
| Toshiba       | NB520                       | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Apple         | MacBook4,1                  | [e341d904c9](https://linux-hardware.org/?probe=e341d904c9) | Feb 01, 2020 |
| Apple         | MacBook4,1                  | [0244fb9c97](https://linux-hardware.org/?probe=0244fb9c97) | Feb 01, 2020 |
| ASUSTek       | S500CA                      | [4f82008cac](https://linux-hardware.org/?probe=4f82008cac) | Jan 29, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Sony          | VPCCW21FX                   | [78ac20109b](https://linux-hardware.org/?probe=78ac20109b) | Jan 21, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [d87b9779d7](https://linux-hardware.org/?probe=d87b9779d7) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c6595736b8](https://linux-hardware.org/?probe=c6595736b8) | Jan 14, 2020 |
| HP            | Laptop 15-db0xxx            | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Toshiba       | Satellite C850-F117         | [5b8f68dbc9](https://linux-hardware.org/?probe=5b8f68dbc9) | Nov 26, 2019 |
| Toshiba       | Satellite C55D-B            | [0d1bbd1e60](https://linux-hardware.org/?probe=0d1bbd1e60) | Nov 25, 2019 |
| Toshiba       | Satellite C55D-B            | [98653dbce0](https://linux-hardware.org/?probe=98653dbce0) | Nov 25, 2019 |
| Lenovo        | G500 20236                  | [c27bae21b0](https://linux-hardware.org/?probe=c27bae21b0) | Nov 16, 2019 |
| Lenovo        | G500 20236                  | [afb3948882](https://linux-hardware.org/?probe=afb3948882) | Nov 15, 2019 |
| Acer          | Aspire F5-573G              | [db302aa54d](https://linux-hardware.org/?probe=db302aa54d) | Nov 14, 2019 |
| HP            | Pavilion 11 x360 PC         | [00c8d1e4e7](https://linux-hardware.org/?probe=00c8d1e4e7) | Nov 11, 2019 |
| HP            | Pavilion 11 x360 PC         | [6b30a9e102](https://linux-hardware.org/?probe=6b30a9e102) | Nov 11, 2019 |
| HP            | Pavilion 11 x360 PC         | [cc352f0876](https://linux-hardware.org/?probe=cc352f0876) | Nov 10, 2019 |
| HP            | Pavilion 11 x360 PC         | [a4bd90bb25](https://linux-hardware.org/?probe=a4bd90bb25) | Nov 09, 2019 |
| HP            | Laptop 15-bs0xx             | [2ac11dfe68](https://linux-hardware.org/?probe=2ac11dfe68) | Nov 02, 2019 |
| ASUSTek       | 1005PXD                     | [d0afcbe081](https://linux-hardware.org/?probe=d0afcbe081) | Oct 26, 2019 |
| ASUSTek       | 1005PXD                     | [1e57ee0116](https://linux-hardware.org/?probe=1e57ee0116) | Oct 26, 2019 |
| HP            | Pavilion Notebook           | [14784cf228](https://linux-hardware.org/?probe=14784cf228) | Oct 19, 2019 |
| HP            | Pavilion Notebook           | [5f57cac098](https://linux-hardware.org/?probe=5f57cac098) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | [6e3970fc39](https://linux-hardware.org/?probe=6e3970fc39) | Sep 17, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | [20f7841be1](https://linux-hardware.org/?probe=20f7841be1) | Sep 17, 2019 |
| HP            | Pavilion Notebook           | [f29f057c97](https://linux-hardware.org/?probe=f29f057c97) | Sep 16, 2019 |
| Unknown       | Unknown                     | [0a9618f99e](https://linux-hardware.org/?probe=0a9618f99e) | Jul 10, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Pavilion dv7                | [24128291a4](https://linux-hardware.org/?probe=24128291a4) | Jun 25, 2019 |
| Unknown       | Unknown                     | [583ec484b5](https://linux-hardware.org/?probe=583ec484b5) | Jun 24, 2019 |
| Unknown       | Unknown                     | [c0eb7dc5f0](https://linux-hardware.org/?probe=c0eb7dc5f0) | Jun 24, 2019 |
| ASUSTek       | Q501LA                      | [ad06395996](https://linux-hardware.org/?probe=ad06395996) | Jun 23, 2019 |
| Toshiba       | Satellite M70               | [c31329a508](https://linux-hardware.org/?probe=c31329a508) | Jun 19, 2019 |
| Toshiba       | Satellite C850-F117         | [de103d8a7d](https://linux-hardware.org/?probe=de103d8a7d) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.0.0-37-generic      | 19        | 14.07%  |
| 5.4.0-42-generic      | 8         | 5.93%   |
| 5.3.0-62-generic      | 7         | 5.19%   |
| 5.3.0-51-generic      | 7         | 5.19%   |
| 4.18.0-18-generic     | 7         | 5.19%   |
| 5.4.0-65-generic      | 6         | 4.44%   |
| 5.4.0-72-generic      | 4         | 2.96%   |
| 5.4.0-58-generic      | 4         | 2.96%   |
| 5.0.0-32-generic      | 4         | 2.96%   |
| 5.4.0-80-generic      | 3         | 2.22%   |
| 5.4.0-77-generic      | 3         | 2.22%   |
| 5.4.0-66-generic      | 3         | 2.22%   |
| 5.4.0-47-generic      | 3         | 2.22%   |
| 5.4.0-45-generic      | 3         | 2.22%   |
| 5.3.0-46-generic      | 3         | 2.22%   |
| 5.3.0-42-generic      | 3         | 2.22%   |
| 5.3.0-28-generic      | 3         | 2.22%   |
| 5.0.0-36-generic      | 3         | 2.22%   |
| 5.4.0-81-generic      | 2         | 1.48%   |
| 5.4.0-74-generic      | 2         | 1.48%   |
| 5.4.0-70-generic      | 2         | 1.48%   |
| 5.4.0-56-generic      | 2         | 1.48%   |
| 5.4.0-54-generic      | 2         | 1.48%   |
| 5.4.0-52-generic      | 2         | 1.48%   |
| 5.4.0-48-generic      | 2         | 1.48%   |
| 5.3.0-59-generic      | 2         | 1.48%   |
| 5.3.0-40-generic      | 2         | 1.48%   |
| 5.0.0-27-generic      | 2         | 1.48%   |
| 4.18.0-21-generic     | 2         | 1.48%   |
| 5.4.95-050495-generic | 1         | 0.74%   |
| 5.4.0-84-generic      | 1         | 0.74%   |
| 5.4.0-73-generic      | 1         | 0.74%   |
| 5.4.0-71-generic      | 1         | 0.74%   |
| 5.4.0-67-generic      | 1         | 0.74%   |
| 5.4.0-64-generic      | 1         | 0.74%   |
| 5.4.0-62-generic      | 1         | 0.74%   |
| 5.4.0-60-generic      | 1         | 0.74%   |
| 5.4.0-59-generic      | 1         | 0.74%   |
| 5.4.0-53-generic      | 1         | 0.74%   |
| 5.4.0-51-generic      | 1         | 0.74%   |
| 5.4.0-49-generic      | 1         | 0.74%   |
| 5.4.0-44-generic      | 1         | 0.74%   |
| 5.3.0-45-generic      | 1         | 0.74%   |
| 5.1.11-050111-generic | 1         | 0.74%   |
| 5.0.0-29-generic      | 1         | 0.74%   |
| 4.18.0-25-generic     | 1         | 0.74%   |
| 4.18.0-24-generic     | 1         | 0.74%   |
| 4.18.0-22-generic     | 1         | 0.74%   |
| 4.18.0-20-generic     | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 60        | 46.51%  |
| 5.3.0   | 27        | 20.93%  |
| 5.0.0   | 27        | 20.93%  |
| 4.18.0  | 13        | 10.08%  |
| 5.4.95  | 1         | 0.78%   |
| 5.1.11  | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 61        | 47.29%  |
| 5.3     | 27        | 20.93%  |
| 5.0     | 27        | 20.93%  |
| 4.18    | 13        | 10.08%  |
| 5.1     | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 84        | 68.29%  |
| i686   | 39        | 31.71%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXDE       | 97        | 77.6%   |
| Unknown    | 20        | 16%     |
| GNOME      | 6         | 4.8%    |
| X-Cinnamon | 1         | 0.8%    |
| Peppermint | 1         | 0.8%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 123       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 115       | 93.5%   |
| TDM     | 6         | 4.88%   |
| SDDM    | 1         | 0.81%   |
| LightDM | 1         | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 38        | 30.4%   |
| Unknown | 14        | 11.2%   |
| en_GB   | 10        | 8%      |
| de_DE   | 7         | 5.6%    |
| pt_BR   | 6         | 4.8%    |
| it_IT   | 6         | 4.8%    |
| nl_NL   | 5         | 4%      |
| pl_PL   | 4         | 3.2%    |
| fr_FR   | 4         | 3.2%    |
| en_CA   | 4         | 3.2%    |
| ru_RU   | 3         | 2.4%    |
| C       | 3         | 2.4%    |
| ja_JP   | 2         | 1.6%    |
| es_MX   | 2         | 1.6%    |
| en_IN   | 2         | 1.6%    |
| tr_TR   | 1         | 0.8%    |
| sv_SE   | 1         | 0.8%    |
| ro_RO   | 1         | 0.8%    |
| pt_PT   | 1         | 0.8%    |
| lv_LV   | 1         | 0.8%    |
| fi_FI   | 1         | 0.8%    |
| es_PE   | 1         | 0.8%    |
| es_PA   | 1         | 0.8%    |
| es_ES   | 1         | 0.8%    |
| es_CR   | 1         | 0.8%    |
| es_BO   | 1         | 0.8%    |
| es_AR   | 1         | 0.8%    |
| en_ZA   | 1         | 0.8%    |
| en_PH   | 1         | 0.8%    |
| en_AU   | 1         | 0.8%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 93        | 75.61%  |
| EFI  | 30        | 24.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 106       | 84.8%   |
| Unknown  | 10        | 8%      |
| Overlay  | 4         | 3.2%    |
| Ext2     | 2         | 1.6%    |
| Reiserfs | 1         | 0.8%    |
| Ext3     | 1         | 0.8%    |
| Btrfs    | 1         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 111       | 89.52%  |
| GPT     | 7         | 5.65%   |
| MBR     | 6         | 4.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 92.8%   |
| Yes       | 9         | 7.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 86.4%   |
| Yes       | 17        | 13.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 21.95%  |
| Toshiba             | 15        | 12.2%   |
| Lenovo              | 15        | 12.2%   |
| ASUSTek Computer    | 14        | 11.38%  |
| Acer                | 11        | 8.94%   |
| Dell                | 10        | 8.13%   |
| Samsung Electronics | 7         | 5.69%   |
| Sony                | 4         | 3.25%   |
| Fujitsu Siemens     | 4         | 3.25%   |
| Apple               | 2         | 1.63%   |
| Unknown             | 2         | 1.63%   |
| Positivo            | 1         | 0.81%   |
| Packard Bell        | 1         | 0.81%   |
| Olivetti            | 1         | 0.81%   |
| Medion              | 1         | 0.81%   |
| JPSaCouto           | 1         | 0.81%   |
| Itautec             | 1         | 0.81%   |
| IBM                 | 1         | 0.81%   |
| Google              | 1         | 0.81%   |
| Gateway             | 1         | 0.81%   |
| Fujitsu             | 1         | 0.81%   |
| eMachines           | 1         | 0.81%   |
| Clevo               | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Toshiba Satellite M70                      | 2         | 1.63%   |
| Toshiba Satellite L500                     | 2         | 1.63%   |
| Samsung N150P/N210P/N220P                  | 2         | 1.63%   |
| Lenovo G500 20236                          | 2         | 1.63%   |
| Dell Inspiron N5050                        | 2         | 1.63%   |
| Acer Extensa 5630                          | 2         | 1.63%   |
| Unknown                                    | 2         | 1.63%   |
| Toshiba Satellite PRO C850                 | 1         | 0.81%   |
| Toshiba Satellite L310                     | 1         | 0.81%   |
| Toshiba Satellite L300                     | 1         | 0.81%   |
| Toshiba Satellite C850-F117                | 1         | 0.81%   |
| Toshiba Satellite C660                     | 1         | 0.81%   |
| Toshiba Satellite C55D-B                   | 1         | 0.81%   |
| Toshiba QOSMIO F755                        | 1         | 0.81%   |
| Toshiba PORTEGE R500                       | 1         | 0.81%   |
| Toshiba NB520                              | 1         | 0.81%   |
| Toshiba NB500                              | 1         | 0.81%   |
| Toshiba dynabook Satellite B552/H          | 1         | 0.81%   |
| Sony VPCZ21V9E                             | 1         | 0.81%   |
| Sony VPCCW21FX                             | 1         | 0.81%   |
| Sony VGN-S55B_S                            | 1         | 0.81%   |
| Sony VGN-FW140E                            | 1         | 0.81%   |
| Samsung R610                               | 1         | 0.81%   |
| Samsung R530/R730/R540                     | 1         | 0.81%   |
| Samsung N150P                              | 1         | 0.81%   |
| Samsung N150/N210/N220                     | 1         | 0.81%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.81%   |
| Positivo N1103                             | 1         | 0.81%   |
| Packard Bell EasyNote TK85                 | 1         | 0.81%   |
| Olivetti CL133A                            | 1         | 0.81%   |
| Medion Akoya E4214 MD99570                 | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS0035US   | 1         | 0.81%   |
| Lenovo ThinkPad T60 1951CJ4                | 1         | 0.81%   |
| Lenovo ThinkPad T450 20BUS3CF00            | 1         | 0.81%   |
| Lenovo ThinkPad R60 94566FG                | 1         | 0.81%   |
| Lenovo ThinkPad Edge E431 62775GU          | 1         | 0.81%   |
| Lenovo ThinkPad E490 20N90019BR            | 1         | 0.81%   |
| Lenovo IdeaPad Z460 20059                  | 1         | 0.81%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 0.81%   |
| Lenovo IdeaPad 1 11ADA05 82GV              | 1         | 0.81%   |
| Lenovo B575 1450A7U                        | 1         | 0.81%   |
| Lenovo B490 37722SP                        | 1         | 0.81%   |
| Lenovo 433328G                             | 1         | 0.81%   |
| Lenovo 3000 N500 423374G                   | 1         | 0.81%   |
| JPSaCouto Intel powered classmate PC       | 1         | 0.81%   |
| Itautec Infoway                            | 1         | 0.81%   |
| IBM ThinkPad T43 2669GY4                   | 1         | 0.81%   |
| HP Stream Laptop 14-ds0xxx                 | 1         | 0.81%   |
| HP Stream Laptop 11-y0XX                   | 1         | 0.81%   |
| HP Presario C500 (RZ343UA#ABA)             | 1         | 0.81%   |
| HP Pavilion Notebook                       | 1         | 0.81%   |
| HP Pavilion g6                             | 1         | 0.81%   |
| HP Pavilion dv8000 (EZ590UA#ABA)           | 1         | 0.81%   |
| HP Pavilion dv7                            | 1         | 0.81%   |
| HP Pavilion dv6500                         | 1         | 0.81%   |
| HP Pavilion dv4                            | 1         | 0.81%   |
| HP Pavilion 11 x360 PC                     | 1         | 0.81%   |
| HP Notebook                                | 1         | 0.81%   |
| HP Mini 110-1100                           | 1         | 0.81%   |
| HP Mini 110-1000                           | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Toshiba Satellite       | 10        | 8.13%   |
| HP Pavilion             | 7         | 5.69%   |
| Lenovo ThinkPad         | 6         | 4.88%   |
| HP EliteBook            | 4         | 3.25%   |
| HP Compaq               | 4         | 3.25%   |
| Dell Inspiron           | 4         | 3.25%   |
| Acer Extensa            | 4         | 3.25%   |
| Acer Aspire             | 4         | 3.25%   |
| Samsung N150P           | 3         | 2.44%   |
| Lenovo IdeaPad          | 3         | 2.44%   |
| Dell Latitude           | 3         | 2.44%   |
| Lenovo G500             | 2         | 1.63%   |
| HP Stream               | 2         | 1.63%   |
| HP Mini                 | 2         | 1.63%   |
| HP Laptop               | 2         | 1.63%   |
| HP 255                  | 2         | 1.63%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.63%   |
| Fujitsu Siemens AMILO   | 2         | 1.63%   |
| Dell Precision          | 2         | 1.63%   |
| Unknown                 | 2         | 1.63%   |
| Toshiba QOSMIO          | 1         | 0.81%   |
| Toshiba PORTEGE         | 1         | 0.81%   |
| Toshiba NB520           | 1         | 0.81%   |
| Toshiba NB500           | 1         | 0.81%   |
| Toshiba dynabook        | 1         | 0.81%   |
| Sony VPCZ21V9E          | 1         | 0.81%   |
| Sony VPCCW21FX          | 1         | 0.81%   |
| Sony VGN-S55B           | 1         | 0.81%   |
| Sony VGN-FW140E         | 1         | 0.81%   |
| Samsung R610            | 1         | 0.81%   |
| Samsung R530            | 1         | 0.81%   |
| Samsung N150            | 1         | 0.81%   |
| Samsung 300E4A          | 1         | 0.81%   |
| Positivo N1103          | 1         | 0.81%   |
| Packard Bell EasyNote   | 1         | 0.81%   |
| Olivetti CL133A         | 1         | 0.81%   |
| Medion Akoya            | 1         | 0.81%   |
| Lenovo B575             | 1         | 0.81%   |
| Lenovo B490             | 1         | 0.81%   |
| Lenovo 433328G          | 1         | 0.81%   |
| Lenovo 3000             | 1         | 0.81%   |
| JPSaCouto Intel         | 1         | 0.81%   |
| Itautec Infoway         | 1         | 0.81%   |
| IBM ThinkPad            | 1         | 0.81%   |
| HP Presario             | 1         | 0.81%   |
| HP Notebook             | 1         | 0.81%   |
| HP 2133                 | 1         | 0.81%   |
| HP 15                   | 1         | 0.81%   |
| Google Gnawty           | 1         | 0.81%   |
| Gateway Blade-K8F       | 1         | 0.81%   |
| Fujitsu LIFEBOOK        | 1         | 0.81%   |
| eMachines E520          | 1         | 0.81%   |
| Dell Vostro             | 1         | 0.81%   |
| Clevo W55xEU            | 1         | 0.81%   |
| ASUS X541NA             | 1         | 0.81%   |
| ASUS X45U               | 1         | 0.81%   |
| ASUS X205TA             | 1         | 0.81%   |
| ASUS VivoBook           | 1         | 0.81%   |
| ASUS T101HA             | 1         | 0.81%   |
| ASUS S500CA             | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 16        | 13.01%  |
| 2008    | 14        | 11.38%  |
| 2010    | 12        | 9.76%   |
| 2013    | 10        | 8.13%   |
| 2012    | 10        | 8.13%   |
| 2011    | 10        | 8.13%   |
| 2019    | 8         | 6.5%    |
| 2007    | 7         | 5.69%   |
| 2017    | 6         | 4.88%   |
| 2018    | 5         | 4.07%   |
| 2016    | 5         | 4.07%   |
| 2015    | 4         | 3.25%   |
| 2014    | 4         | 3.25%   |
| 2006    | 4         | 3.25%   |
| 2020    | 3         | 2.44%   |
| 2021    | 2         | 1.63%   |
| 2005    | 2         | 1.63%   |
| Unknown | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 123       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 117       | 95.12%  |
| Enabled  | 6         | 4.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 122       | 99.19%  |
| Yes  | 1         | 0.81%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 37        | 29.84%  |
| 1.01-2.0   | 36        | 29.03%  |
| 4.01-8.0   | 17        | 13.71%  |
| 0.51-1.0   | 10        | 8.06%   |
| 2.01-3.0   | 9         | 7.26%   |
| 8.01-16.0  | 9         | 7.26%   |
| 16.01-24.0 | 5         | 4.03%   |
| 32.01-64.0 | 1         | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 52        | 38.81%  |
| 0.51-1.0 | 52        | 38.81%  |
| 2.01-3.0 | 19        | 14.18%  |
| 0.01-0.5 | 8         | 5.97%   |
| 4.01-8.0 | 2         | 1.49%   |
| 3.01-4.0 | 1         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 76.38%  |
| 2      | 25        | 19.69%  |
| 3      | 3         | 2.36%   |
| 0      | 2         | 1.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 72        | 58.06%  |
| No        | 52        | 41.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 91.06%  |
| No        | 11        | 8.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 51.61%  |
| No        | 60        | 48.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 31        | 25.2%   |
| Germany      | 12        | 9.76%   |
| UK           | 9         | 7.32%   |
| Netherlands  | 7         | 5.69%   |
| Italy        | 7         | 5.69%   |
| Canada       | 6         | 4.88%   |
| Brazil       | 5         | 4.07%   |
| Russia       | 4         | 3.25%   |
| Poland       | 4         | 3.25%   |
| France       | 4         | 3.25%   |
| Romania      | 3         | 2.44%   |
| Japan        | 3         | 2.44%   |
| Sweden       | 2         | 1.63%   |
| Mexico       | 2         | 1.63%   |
| India        | 2         | 1.63%   |
| Bolivia      | 2         | 1.63%   |
| Turkey       | 1         | 0.81%   |
| Switzerland  | 1         | 0.81%   |
| Spain        | 1         | 0.81%   |
| South Africa | 1         | 0.81%   |
| Serbia       | 1         | 0.81%   |
| Portugal     | 1         | 0.81%   |
| Philippines  | 1         | 0.81%   |
| Peru         | 1         | 0.81%   |
| Panama       | 1         | 0.81%   |
| Norway       | 1         | 0.81%   |
| Namibia      | 1         | 0.81%   |
| Malaysia     | 1         | 0.81%   |
| Latvia       | 1         | 0.81%   |
| Kazakhstan   | 1         | 0.81%   |
| Georgia      | 1         | 0.81%   |
| Finland      | 1         | 0.81%   |
| Costa Rica   | 1         | 0.81%   |
| Belarus      | 1         | 0.81%   |
| Australia    | 1         | 0.81%   |
| Argentina    | 1         | 0.81%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Turin                 | 2         | 1.56%   |
| Toronto               | 2         | 1.56%   |
| Topeka                | 2         | 1.56%   |
| Oldenburg             | 2         | 1.56%   |
| Naples                | 2         | 1.56%   |
| Moscow                | 2         | 1.56%   |
| Bucharest             | 2         | 1.56%   |
| Amsterdam             | 2         | 1.56%   |
| Äänekoski           | 1         | 0.78%   |
| Zvecka                | 1         | 0.78%   |
| Zaandam               | 1         | 0.78%   |
| Yokohama              | 1         | 0.78%   |
| Yacuiba               | 1         | 0.78%   |
| Wysokie Mazowieckie   | 1         | 0.78%   |
| Windhoek              | 1         | 0.78%   |
| West Chester          | 1         | 0.78%   |
| Warsaw                | 1         | 0.78%   |
| Waalwijk              | 1         | 0.78%   |
| Versailles            | 1         | 0.78%   |
| Verona                | 1         | 0.78%   |
| Tucson                | 1         | 0.78%   |
| Tres Rios             | 1         | 0.78%   |
| Telford               | 1         | 0.78%   |
| Tbilisi               | 1         | 0.78%   |
| Tahlequah             | 1         | 0.78%   |
| São Paulo            | 1         | 0.78%   |
| Stockton              | 1         | 0.78%   |
| Southampton           | 1         | 0.78%   |
| Sivas                 | 1         | 0.78%   |
| Shoreham-by-Sea       | 1         | 0.78%   |
| Sherwood Park         | 1         | 0.78%   |
| Seattle               | 1         | 0.78%   |
| Scharendijke          | 1         | 0.78%   |
| Sant Boi de Llobregat | 1         | 0.78%   |
| San Rafael            | 1         | 0.78%   |
| Rugby                 | 1         | 0.78%   |
| Rotterdam             | 1         | 0.78%   |
| Roncade               | 1         | 0.78%   |
| Queens                | 1         | 0.78%   |
| Pruzhany              | 1         | 0.78%   |
| Prince Frederick      | 1         | 0.78%   |
| Poznan                | 1         | 0.78%   |
| Polokwane             | 1         | 0.78%   |
| Plankstadt            | 1         | 0.78%   |
| Piedmont              | 1         | 0.78%   |
| Petrópolis           | 1         | 0.78%   |
| Peseux                | 1         | 0.78%   |
| Perth                 | 1         | 0.78%   |
| Paredes de Coura      | 1         | 0.78%   |
| Panama City           | 1         | 0.78%   |
| Osasco                | 1         | 0.78%   |
| Oroville              | 1         | 0.78%   |
| Nottingham            | 1         | 0.78%   |
| North Bergen          | 1         | 0.78%   |
| Nordingra             | 1         | 0.78%   |
| New Braunfels         | 1         | 0.78%   |
| Münster              | 1         | 0.78%   |
| Mysore                | 1         | 0.78%   |
| Mottingham            | 1         | 0.78%   |
| Montreal              | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 20.9%   |
| WDC                 | 19        | 21     | 14.18%  |
| Unknown             | 15        | 18     | 11.19%  |
| Toshiba             | 14        | 14     | 10.45%  |
| Samsung Electronics | 13        | 17     | 9.7%    |
| Hitachi             | 10        | 12     | 7.46%   |
| Kingston            | 6         | 8      | 4.48%   |
| SanDisk             | 4         | 5      | 2.99%   |
| HGST                | 4         | 5      | 2.99%   |
| PNY                 | 2         | 2      | 1.49%   |
| Integral            | 2         | 2      | 1.49%   |
| Fujitsu             | 2         | 2      | 1.49%   |
| Zheino              | 1         | 1      | 0.75%   |
| TCSUNBOW            | 1         | 1      | 0.75%   |
| SK Hynix            | 1         | 1      | 0.75%   |
| SABRENT             | 1         | 1      | 0.75%   |
| Micron Technology   | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 1      | 0.75%   |
| GOODRAM             | 1         | 1      | 0.75%   |
| FATTYDOVE           | 1         | 1      | 0.75%   |
| DREVO               | 1         | 1      | 0.75%   |
| Crucial             | 1         | 1      | 0.75%   |
| China               | 1         | 1      | 0.75%   |
| BHT                 | 1         | 2      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |
| Apacer              | 1         | 5      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                     | 6         | 4.41%   |
| Seagate ST9500325AS 500GB                  | 4         | 2.94%   |
| Seagate ST9320325AS 320GB                  | 3         | 2.21%   |
| Seagate ST9250315AS 250GB                  | 3         | 2.21%   |
| Seagate ST500LT012-1DG142 500GB            | 3         | 2.21%   |
| Seagate ST500LM012 HN-M500MBB 500GB        | 3         | 2.21%   |
| WDC WD3200BPVT-22ZEST0 320GB               | 2         | 1.47%   |
| WDC WD1200BEVS-22UST0 120GB                | 2         | 1.47%   |
| Unknown SD/MMC/MS PRO 128GB                | 2         | 1.47%   |
| Unknown MMC Card  16GB                     | 2         | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 1.47%   |
| Samsung HM160HI 160GB                      | 2         | 1.47%   |
| Kingston SA400S37240G 240GB SSD            | 2         | 1.47%   |
| HGST HTS725032A7E630 320GB                 | 2         | 1.47%   |
| Zheino CHN 25SATAA3 120 120GB SSD          | 1         | 0.74%   |
| WDC WDS120G2G0A-00JH30 120GB SSD           | 1         | 0.74%   |
| WDC WD5000LPVX-60V0TT0 500GB               | 1         | 0.74%   |
| WDC WD5000LPVX-22V0TT0 500GB               | 1         | 0.74%   |
| WDC WD3200BPVT-08JJ5T0 320GB               | 1         | 0.74%   |
| WDC WD2500BPVT-24ZEST0 250GB               | 1         | 0.74%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 0.74%   |
| WDC WD2500BEVT-35A23T0 250GB               | 1         | 0.74%   |
| WDC WD2500BEVS-00UST0 250GB                | 1         | 0.74%   |
| WDC WD1600BEVT-60ZCT1 160GB                | 1         | 0.74%   |
| WDC WD1600BEVT-22ZCT0 160GB                | 1         | 0.74%   |
| WDC WD1600BEVS-08VAT2 160GB                | 1         | 0.74%   |
| WDC WD1600BEVS-07RST0 160GB                | 1         | 0.74%   |
| WDC WD10SPCX-80HWST0 1TB                   | 1         | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB                   | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB                   | 1         | 0.74%   |
| Unknown SL16G  16GB                        | 1         | 0.74%   |
| Unknown SFSA120GM3AA4TO-I-LB-616-G30 120GB | 1         | 0.74%   |
| Unknown SE128  128GB                       | 1         | 0.74%   |
| Unknown MMC Card  64GB                     | 1         | 0.74%   |
| Unknown MMC Card  2GB                      | 1         | 0.74%   |
| Unknown MMC Card  134GB                    | 1         | 0.74%   |
| Unknown MMC Card  128GB                    | 1         | 0.74%   |
| Toshiba MQ04ABF100 1TB                     | 1         | 0.74%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 0.74%   |
| Toshiba MQ01ABD032 320GB                   | 1         | 0.74%   |
| Toshiba MK8032GSX 80GB                     | 1         | 0.74%   |
| Toshiba MK7559GSXP 752GB                   | 1         | 0.74%   |
| Toshiba MK5055GSXN 500GB                   | 1         | 0.74%   |
| Toshiba MK5055GSX 500GB                    | 1         | 0.74%   |
| Toshiba MK3265GSX 320GB                    | 1         | 0.74%   |
| Toshiba MK2565GSX 250GB                    | 1         | 0.74%   |
| Toshiba MK2035GSS 200GB                    | 1         | 0.74%   |
| Toshiba MK1652GSX 160GB                    | 1         | 0.74%   |
| Toshiba MK1252GSX 120GB                    | 1         | 0.74%   |
| Toshiba MK1237GSX 120GB                    | 1         | 0.74%   |
| Toshiba MK1032GSX 99GB                     | 1         | 0.74%   |
| TCSUNBOW X3 480GB SSD                      | 1         | 0.74%   |
| SK Hynix HBG4e  32GB                       | 1         | 0.74%   |
| Seagate ST98823A 80GB                      | 1         | 0.74%   |
| Seagate ST9500423AS 500GB                  | 1         | 0.74%   |
| Seagate ST9500420AS 500GB                  | 1         | 0.74%   |
| Seagate ST9320310AS 320GB                  | 1         | 0.74%   |
| Seagate ST9160314AS 160GB                  | 1         | 0.74%   |
| Seagate ST9120817AS 120GB                  | 1         | 0.74%   |
| Seagate ST750LM022 HN-M750MBB 752GB        | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 33.73%  |
| WDC                 | 18        | 20     | 21.69%  |
| Toshiba             | 14        | 14     | 16.87%  |
| Hitachi             | 10        | 12     | 12.05%  |
| Samsung Electronics | 5         | 5      | 6.02%   |
| HGST                | 4         | 5      | 4.82%   |
| Unknown             | 2         | 2      | 2.41%   |
| Fujitsu             | 2         | 2      | 2.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 11     | 20%     |
| Kingston            | 6         | 8      | 17.14%  |
| SanDisk             | 4         | 5      | 11.43%  |
| PNY                 | 2         | 2      | 5.71%   |
| Integral            | 2         | 2      | 5.71%   |
| Zheino              | 1         | 1      | 2.86%   |
| WDC                 | 1         | 1      | 2.86%   |
| TCSUNBOW            | 1         | 1      | 2.86%   |
| Micron Technology   | 1         | 1      | 2.86%   |
| LITEONIT            | 1         | 1      | 2.86%   |
| KingSpec            | 1         | 1      | 2.86%   |
| GOODRAM             | 1         | 1      | 2.86%   |
| FATTYDOVE           | 1         | 1      | 2.86%   |
| DREVO               | 1         | 1      | 2.86%   |
| Crucial             | 1         | 1      | 2.86%   |
| China               | 1         | 1      | 2.86%   |
| BHT                 | 1         | 2      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |
| Apacer              | 1         | 5      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 81        | 90     | 61.83%  |
| SSD     | 34        | 47     | 25.95%  |
| MMC     | 13        | 16     | 9.92%   |
| Unknown | 2         | 2      | 1.53%   |
| NVMe    | 1         | 1      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 110       | 135    | 85.94%  |
| MMC  | 13        | 16     | 10.16%  |
| SAS  | 4         | 4      | 3.13%   |
| NVMe | 1         | 1      | 0.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 99        | 121    | 86.84%  |
| 0.51-1.0   | 13        | 14     | 11.4%   |
| 1.01-2.0   | 1         | 1      | 0.88%   |
| 4.01-10.0  | 1         | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 45        | 36%     |
| 251-500    | 28        | 22.4%   |
| 21-50      | 18        | 14.4%   |
| 51-100     | 16        | 12.8%   |
| 501-1000   | 8         | 6.4%    |
| 1-20       | 7         | 5.6%    |
| 1001-2000  | 2         | 1.6%    |
| 2001-3000  | 1         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 86        | 65.15%  |
| 21-50    | 26        | 19.7%   |
| 51-100   | 12        | 9.09%   |
| 101-250  | 5         | 3.79%   |
| 501-1000 | 3         | 2.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB       | 1         | 1      | 33.33%  |
| Seagate ST9250315AS 250GB       | 1         | 1      | 33.33%  |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 112       | 143    | 90.32%  |
| Works    | 9         | 10     | 7.26%   |
| Malfunc  | 3         | 3      | 2.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 89        | 78.07%  |
| AMD                              | 15        | 13.16%  |
| Silicon Integrated Systems [SiS] | 4         | 3.51%   |
| VIA Technologies                 | 2         | 1.75%   |
| Samsung Electronics              | 2         | 1.75%   |
| Nvidia                           | 2         | 1.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 14        | 10.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 14        | 10.29%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 10        | 7.35%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 9         | 6.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 8         | 5.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 8         | 5.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 7         | 5.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 5         | 3.68%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 4         | 2.94%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 4         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 4         | 2.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 4         | 2.94%   |
| Intel 82801FBM (ICH6M) SATA Controller                                       | 4         | 2.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 4         | 2.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 3         | 2.21%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                     | 3         | 2.21%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 2.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 1.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 1.47%   |
| AMD IXP SB4x0 IDE Controller                                                 | 2         | 1.47%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 1         | 0.74%   |
| VIA VT8237A SATA 2-Port Controller                                           | 1         | 0.74%   |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 0.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 0.74%   |
| Samsung Electronics SATA controller                                          | 1         | 0.74%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.74%   |
| Nvidia MCP67 IDE Controller                                                  | 1         | 0.74%   |
| Nvidia MCP67 AHCI Controller                                                 | 1         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                            | 1         | 0.74%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 0.74%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                         | 1         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 1         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 0.74%   |
| AMD FCH SATA Controller [IDE mode]                                           | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 85        | 68%     |
| IDE  | 35        | 28%     |
| RAID | 4         | 3.2%    |
| NVMe | 1         | 0.8%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 105       | 85.37%  |
| AMD          | 17        | 13.82%  |
| CentaurHauls | 1         | 0.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 6         | 4.88%   |
| Intel Atom CPU N450 @ 1.66GHz               | 5         | 4.07%   |
| Intel Pentium M processor 1.73GHz           | 4         | 3.25%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 2.44%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 2.44%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.63%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 2         | 1.63%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 2         | 1.63%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 1.63%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.63%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.63%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.63%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 1.63%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 1.63%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 1.63%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.63%   |
| Intel Atom CPU N455 @ 1.66GHz               | 2         | 1.63%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.63%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.81%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.81%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 0.81%   |
| Intel Pentium Dual CPU T2410 @ 2.00GHz      | 1         | 0.81%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.81%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.81%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 1         | 0.81%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.81%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 1         | 0.81%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.81%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.81%   |
| Intel Core i7-3820QM CPU @ 2.70GHz          | 1         | 0.81%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.81%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 0.81%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.81%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.81%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.81%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 0.81%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.81%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 0.81%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 0.81%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i3-2348M CPU @ 2.30GHz           | 1         | 0.81%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 1         | 0.81%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 0.81%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 1         | 0.81%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 1         | 0.81%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 1         | 0.81%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 0.81%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 0.81%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 1         | 0.81%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 1         | 0.81%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 1         | 0.81%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 18        | 14.63%  |
| Intel Celeron           | 17        | 13.82%  |
| Intel Core i7           | 11        | 8.94%   |
| Intel Core i5           | 11        | 8.94%   |
| Intel Core i3           | 10        | 8.13%   |
| Intel Genuine           | 7         | 5.69%   |
| Intel Core 2 Duo        | 7         | 5.69%   |
| Intel Pentium           | 6         | 4.88%   |
| Intel Pentium Dual-Core | 5         | 4.07%   |
| Intel Pentium M         | 4         | 3.25%   |
| Intel Core 2            | 4         | 3.25%   |
| Intel Pentium Dual      | 3         | 2.44%   |
| AMD A8                  | 3         | 2.44%   |
| AMD E2                  | 2         | 1.63%   |
| Other                   | 1         | 0.81%   |
| Intel Celeron M         | 1         | 0.81%   |
| Intel Celeron Dual-Core | 1         | 0.81%   |
| CentaurHauls VIA C7     | 1         | 0.81%   |
| AMD Turion 64 X2 Mobile | 1         | 0.81%   |
| AMD Turion 64 Mobile    | 1         | 0.81%   |
| AMD Phenom II           | 1         | 0.81%   |
| AMD E1                  | 1         | 0.81%   |
| AMD E                   | 1         | 0.81%   |
| AMD C-60                | 1         | 0.81%   |
| AMD Athlon 64 X2        | 1         | 0.81%   |
| AMD Athlon              | 1         | 0.81%   |
| AMD A6                  | 1         | 0.81%   |
| AMD A4                  | 1         | 0.81%   |
| AMD A10                 | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 60.98%  |
| 1      | 29        | 23.58%  |
| 4      | 19        | 15.45%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 123       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 59.35%  |
| 2      | 50        | 40.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 80.65%  |
| 32-bit         | 16        | 12.9%   |
| Unknown        | 8         | 6.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 12        | 9.6%    |
| 0x1067a    | 12        | 9.6%    |
| 0x206a7    | 11        | 8.8%    |
| 0x106ca    | 9         | 7.2%    |
| 0x6fd      | 8         | 6.4%    |
| Unknown    | 8         | 6.4%    |
| 0x106c2    | 6         | 4.8%    |
| 0x30678    | 5         | 4%      |
| 0x6d8      | 4         | 3.2%    |
| 0x406c4    | 4         | 3.2%    |
| 0x20655    | 4         | 3.2%    |
| 0x10661    | 4         | 3.2%    |
| 0x6f6      | 3         | 2.4%    |
| 0x6e8      | 3         | 2.4%    |
| 0x40651    | 3         | 2.4%    |
| 0x07030105 | 3         | 2.4%    |
| 0x06006705 | 3         | 2.4%    |
| 0x806ec    | 2         | 1.6%    |
| 0x806e9    | 2         | 1.6%    |
| 0x6ec      | 2         | 1.6%    |
| 0x306d4    | 2         | 1.6%    |
| 0x10676    | 2         | 1.6%    |
| 0x706a1    | 1         | 0.8%    |
| 0x6f2      | 1         | 0.8%    |
| 0x506c9    | 1         | 0.8%    |
| 0x30661    | 1         | 0.8%    |
| 0x20652    | 1         | 0.8%    |
| 0x08200103 | 1         | 0.8%    |
| 0x07030106 | 1         | 0.8%    |
| 0x0700010f | 1         | 0.8%    |
| 0x06006118 | 1         | 0.8%    |
| 0x06001119 | 1         | 0.8%    |
| 0x05000119 | 1         | 0.8%    |
| 0x05000029 | 1         | 0.8%    |
| 0x010000c8 | 1         | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Core          | 16        | 13.01%  |
| Bonnell       | 16        | 13.01%  |
| Penryn        | 14        | 11.38%  |
| IvyBridge     | 12        | 9.76%   |
| SandyBridge   | 11        | 8.94%   |
| Silvermont    | 9         | 7.32%   |
| P6            | 9         | 7.32%   |
| Westmere      | 6         | 4.88%   |
| Puma          | 4         | 3.25%   |
| KabyLake      | 4         | 3.25%   |
| Excavator     | 4         | 3.25%   |
| K8 Hammer     | 3         | 2.44%   |
| Haswell       | 3         | 2.44%   |
| Broadwell     | 3         | 2.44%   |
| Bobcat        | 2         | 1.63%   |
| Zen           | 1         | 0.81%   |
| Piledriver    | 1         | 0.81%   |
| K10           | 1         | 0.81%   |
| Jaguar        | 1         | 0.81%   |
| Goldmont plus | 1         | 0.81%   |
| Goldmont      | 1         | 0.81%   |
| Unknown       | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 91        | 71.65%  |
| AMD                              | 17        | 13.39%  |
| Nvidia                           | 13        | 10.24%  |
| Silicon Integrated Systems [SiS] | 4         | 3.15%   |
| VIA Technologies                 | 2         | 1.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 10.07%  |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 14        | 9.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 6.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 6.71%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 8         | 5.37%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 8         | 5.37%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 4.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 3.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 3.36%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 2.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 2.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 2.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.68%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 2.01%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 2.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 2.01%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 2         | 1.34%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 1.34%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 1.34%   |
| Intel HD Graphics 620                                                                    | 2         | 1.34%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.34%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.67%   |
| Nvidia GT218M [ION]                                                                      | 1         | 0.67%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.67%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.67%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.67%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.67%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.67%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.67%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.67%   |
| Intel HD Graphics 500                                                                    | 1         | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.67%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.67%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.67%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.67%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.67%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 0.67%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.67%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.67%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.67%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 1         | 0.67%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.67%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 1         | 0.67%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 0.67%   |
| AMD Picasso                                                                              | 1         | 0.67%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 0.67%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 0.67%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.67%   |
| AMD Kabini [Radeon HD 8280 / R3 Series]                                                  | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 70.73%  |
| 1 x AMD        | 13        | 10.57%  |
| 1 x Nvidia     | 9         | 7.32%   |
| 2 x AMD        | 4         | 3.25%   |
| 1 x SiS        | 4         | 3.25%   |
| Intel + Nvidia | 4         | 3.25%   |
| 1 x VIA        | 2         | 1.63%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 91.87%  |
| Unknown     | 7         | 5.69%   |
| Proprietary | 3         | 2.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 78.23%  |
| 0.01-0.5   | 21        | 16.94%  |
| 1.01-2.0   | 3         | 2.42%   |
| 0.51-1.0   | 3         | 2.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 21.95%  |
| Samsung Electronics     | 23        | 18.7%   |
| LG Display              | 13        | 10.57%  |
| LG Philips              | 8         | 6.5%    |
| Chi Mei Optoelectronics | 8         | 6.5%    |
| Chimei Innolux          | 6         | 4.88%   |
| HannStar                | 5         | 4.07%   |
| Sony                    | 3         | 2.44%   |
| Lenovo                  | 3         | 2.44%   |
| CPT                     | 3         | 2.44%   |
| BOE                     | 3         | 2.44%   |
| InfoVision              | 2         | 1.63%   |
| Dell                    | 2         | 1.63%   |
| Apple                   | 2         | 1.63%   |
| Vizio                   | 1         | 0.81%   |
| ViewSonic               | 1         | 0.81%   |
| Seiko/Epson             | 1         | 0.81%   |
| Quanta Display          | 1         | 0.81%   |
| Optoma                  | 1         | 0.81%   |
| OEM                     | 1         | 0.81%   |
| KDC                     | 1         | 0.81%   |
| HKC                     | 1         | 0.81%   |
| Hitachi                 | 1         | 0.81%   |
| Hewlett-Packard         | 1         | 0.81%   |
| Element                 | 1         | 0.81%   |
| CVT                     | 1         | 0.81%   |
| BenQ                    | 1         | 0.81%   |
| Ancor Communications    | 1         | 0.81%   |
| Acer                    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch               | 4         | 3.17%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 2         | 1.59%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch    | 2         | 1.59%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 2         | 1.59%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch             | 2         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch         | 2         | 1.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch           | 2         | 1.59%   |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                       | 1         | 0.79%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 495x291mm 22.6-inch               | 1         | 0.79%   |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                            | 1         | 0.79%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch    | 1         | 0.79%   |
| Sony Nvidia Defaul SNY05FA 1366x768 290x170mm 13.2-inch                 | 1         | 0.79%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch     | 1         | 0.79%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch     | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC304C 1920x1080 353x198mm 15.9-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC5451 1366x768 340x190mm 15.3-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch    | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch   | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch | 1         | 0.79%   |
| Quanta Display LCD Monitor QDS0033 1024x768 304x228mm 15.0-inch         | 1         | 0.79%   |
| Optoma WXGA OTM0550 1280x1024                                           | 1         | 0.79%   |
| OEM 32W_LCD_TV OEM3700 1920x1080                                        | 1         | 0.79%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch           | 1         | 0.79%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch             | 1         | 0.79%   |
| LG Philips LCD Monitor LPLCB00 1280x800 331x207mm 15.4-inch             | 1         | 0.79%   |
| LG Philips LCD Monitor LPLBB00 1024x768 304x228mm 15.0-inch             | 1         | 0.79%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch             | 1         | 0.79%   |
| LG Philips LCD Monitor LPL2388 1440x900 367x230mm 17.1-inch             | 1         | 0.79%   |
| LG Philips LCD Monitor LPL1E01 1280x800 330x210mm 15.4-inch             | 1         | 0.79%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD0380 1600x900 294x166mm 13.3-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD037E 1920x1080 345x194mm 15.6-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 0.79%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch            | 1         | 0.79%   |
| LG Display LCD Monitor LGD01E8 1366x768 340x190mm 15.3-inch             | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                 | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4040 1024x768 304x228mm 15.0-inch                 | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch                 | 1         | 0.79%   |
| KDC LCD Monitor KDC05F1 1366x768 344x193mm 15.5-inch                    | 1         | 0.79%   |
| InfoVision LCD Monitor IVO048E 1366x768 256x144mm 11.6-inch             | 1         | 0.79%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch            | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 54        | 43.55%  |
| 1280x800 (WXGA)    | 19        | 15.32%  |
| 1920x1080 (FHD)    | 17        | 13.71%  |
| 1024x600           | 9         | 7.26%   |
| 1600x900 (HD+)     | 5         | 4.03%   |
| 1024x768 (XGA)     | 5         | 4.03%   |
| 3840x2160 (4K)     | 2         | 1.61%   |
| 2560x1440 (QHD)    | 2         | 1.61%   |
| 1920x540           | 2         | 1.61%   |
| 1920x1200 (WUXGA)  | 2         | 1.61%   |
| 1440x900 (WXGA+)   | 2         | 1.61%   |
| 1024x576           | 2         | 1.61%   |
| 1680x1050 (WSXGA+) | 1         | 0.81%   |
| 1360x768           | 1         | 0.81%   |
| 1280x1024 (SXGA)   | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58        | 47.15%  |
| 13      | 11        | 8.94%   |
| 14      | 10        | 8.13%   |
| 10      | 10        | 8.13%   |
| 11      | 8         | 6.5%    |
| 24      | 4         | 3.25%   |
| 17      | 4         | 3.25%   |
| 27      | 3         | 2.44%   |
| 12      | 3         | 2.44%   |
| 84      | 2         | 1.63%   |
| 21      | 2         | 1.63%   |
| 18      | 2         | 1.63%   |
| Unknown | 2         | 1.63%   |
| 39      | 1         | 0.81%   |
| 31      | 1         | 0.81%   |
| 22      | 1         | 0.81%   |
| 8       | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 58.54%  |
| 201-300     | 26        | 21.14%  |
| 501-600     | 7         | 5.69%   |
| 351-400     | 6         | 4.88%   |
| 401-500     | 5         | 4.07%   |
| 1501-2000   | 2         | 1.63%   |
| Unknown     | 2         | 1.63%   |
| 801-900     | 1         | 0.81%   |
| 601-700     | 1         | 0.81%   |
| 101-200     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 73.68%  |
| 16/10   | 22        | 19.3%   |
| 4/3     | 6         | 5.26%   |
| 5/4     | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 46.34%  |
| 81-90          | 17        | 13.82%  |
| 41-50          | 10        | 8.13%   |
| 51-60          | 8         | 6.5%    |
| 201-250        | 5         | 4.07%   |
| 71-80          | 3         | 2.44%   |
| 61-70          | 3         | 2.44%   |
| 121-130        | 3         | 2.44%   |
| More than 1000 | 2         | 1.63%   |
| 351-500        | 2         | 1.63%   |
| 301-350        | 2         | 1.63%   |
| 141-150        | 2         | 1.63%   |
| 91-100         | 2         | 1.63%   |
| Unknown        | 2         | 1.63%   |
| 1-40           | 1         | 0.81%   |
| 251-300        | 1         | 0.81%   |
| 151-200        | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |
| 501-1000       | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 59        | 48.76%  |
| 51-100  | 36        | 29.75%  |
| 121-160 | 23        | 19.01%  |
| Unknown | 2         | 1.65%   |
| 161-240 | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 103       | 82.4%   |
| 2     | 16        | 12.8%   |
| 0     | 5         | 4%      |
| 3     | 1         | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 60        | 27.27%  |
| Intel                             | 43        | 19.55%  |
| Qualcomm Atheros                  | 39        | 17.73%  |
| Broadcom                          | 34        | 15.45%  |
| Marvell Technology Group          | 12        | 5.45%   |
| Broadcom Limited                  | 9         | 4.09%   |
| Ralink                            | 4         | 1.82%   |
| Silicon Integrated Systems [SiS]  | 3         | 1.36%   |
| VIA Technologies                  | 1         | 0.45%   |
| Spreadtrum Communications         | 1         | 0.45%   |
| Samsung Electronics               | 1         | 0.45%   |
| Ralink Technology                 | 1         | 0.45%   |
| Nvidia                            | 1         | 0.45%   |
| Micro Star International          | 1         | 0.45%   |
| MediaTek                          | 1         | 0.45%   |
| JMicron Technology                | 1         | 0.45%   |
| Huawei Technologies               | 1         | 0.45%   |
| Ericsson Business Mobile Networks | 1         | 0.45%   |
| Dell                              | 1         | 0.45%   |
| BUFFALO                           | 1         | 0.45%   |
| Attansic Technology               | 1         | 0.45%   |
| ASUSTek Computer                  | 1         | 0.45%   |
| ASIX Electronics                  | 1         | 0.45%   |
| AMD                               | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 25        | 9.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 8.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 2.79%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 2.79%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 6         | 2.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 5         | 1.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.59%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.59%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.2%    |
| Intel Wireless 7265                                                     | 3         | 1.2%    |
| Intel Wireless 7260                                                     | 3         | 1.2%    |
| Intel Wireless 3165                                                     | 3         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.2%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.8%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.8%    |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.8%    |
| Intel WiFi Link 5100                                                    | 2         | 0.8%    |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.8%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.8%    |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.8%    |
| Intel 82573L Gigabit Ethernet Controller                                | 2         | 0.8%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 2         | 0.8%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.8%    |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                     | 2         | 0.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.8%    |
| VIA VT6102/VT6103 [Rhine-II]                                            | 1         | 0.4%    |
| Spreadtrum Unisoc Phone                                                 | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                           | 1         | 0.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.4%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.4%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.4%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.4%    |
| Realtek 802.11ac NIC                                                    | 1         | 0.4%    |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.4%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 41        | 32.03%  |
| Broadcom                 | 29        | 22.66%  |
| Qualcomm Atheros         | 28        | 21.88%  |
| Realtek Semiconductor    | 17        | 13.28%  |
| Broadcom Limited         | 5         | 3.91%   |
| Ralink                   | 4         | 3.13%   |
| Ralink Technology        | 1         | 0.78%   |
| Micro Star International | 1         | 0.78%   |
| BUFFALO                  | 1         | 0.78%   |
| ASUSTek Computer         | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 9         | 6.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 7         | 5.43%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 7         | 5.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 6         | 4.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 3.88%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 5         | 3.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 4         | 3.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 3.1%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 4         | 3.1%    |
| Broadcom BCM4311 802.11b/g WLAN                                               | 4         | 3.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 3         | 2.33%   |
| Intel Wireless 7265                                                           | 3         | 2.33%   |
| Intel Wireless 7260                                                           | 3         | 2.33%   |
| Intel Wireless 3165                                                           | 3         | 2.33%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 2.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 1.55%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2         | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 2         | 1.55%   |
| Realtek RTL8187B Wireless Adapter                                             | 2         | 1.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.55%   |
| Intel WiFi Link 5100                                                          | 2         | 1.55%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 1.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.55%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 1         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 1         | 0.78%   |
| Realtek 802.11ac NIC                                                          | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.78%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)       | 1         | 0.78%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.78%   |
| Micro Star International RT2573                                               | 1         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 0.78%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 0.78%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 0.78%   |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.78%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 1         | 0.78%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 0.78%   |
| Intel Centrino Advanced-N 6200                                                | 1         | 0.78%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                       | 1         | 0.78%   |
| Broadcom Limited BCM43225 802.11b/g/n                                         | 1         | 0.78%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 1         | 0.78%   |
| Broadcom BCM4321 802.11a/b/g/n                                                | 1         | 0.78%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 54        | 46.96%  |
| Intel                            | 13        | 11.3%   |
| Qualcomm Atheros                 | 12        | 10.43%  |
| Marvell Technology Group         | 12        | 10.43%  |
| Broadcom                         | 8         | 6.96%   |
| Broadcom Limited                 | 5         | 4.35%   |
| Silicon Integrated Systems [SiS] | 3         | 2.61%   |
| VIA Technologies                 | 1         | 0.87%   |
| Spreadtrum Communications        | 1         | 0.87%   |
| Samsung Electronics              | 1         | 0.87%   |
| Nvidia                           | 1         | 0.87%   |
| MediaTek                         | 1         | 0.87%   |
| JMicron Technology               | 1         | 0.87%   |
| Attansic Technology              | 1         | 0.87%   |
| ASIX Electronics                 | 1         | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 21.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 18.26%  |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 5.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 4.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 3.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 2.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.74%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.74%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.74%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 1.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.74%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.74%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 2         | 1.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.87%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.87%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.87%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.87%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.87%   |
| MediaTek Infinix X683                                             | 1         | 0.87%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.87%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.87%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.87%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller              | 1         | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.87%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.87%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 1         | 0.87%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.87%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Broadcom Limited NetXtreme BCM5751M Gigabit Ethernet PCI Express  | 1         | 0.87%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.87%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.87%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.87%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 50.83%  |
| Ethernet | 112       | 46.28%  |
| Modem    | 7         | 2.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 110       | 57.59%  |
| Ethernet | 81        | 42.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 82.11%  |
| 1     | 19        | 15.45%  |
| 0     | 2         | 1.63%   |
| 3     | 1         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 96.8%   |
| Yes  | 4         | 3.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 26.15%  |
| Broadcom                        | 7         | 10.77%  |
| Qualcomm Atheros Communications | 5         | 7.69%   |
| Hewlett-Packard                 | 5         | 7.69%   |
| Toshiba                         | 4         | 6.15%   |
| Realtek Semiconductor           | 4         | 6.15%   |
| Lite-On Technology              | 4         | 6.15%   |
| IMC Networks                    | 3         | 4.62%   |
| Foxconn International           | 3         | 4.62%   |
| Cambridge Silicon Radio         | 3         | 4.62%   |
| Ralink                          | 2         | 3.08%   |
| Foxconn / Hon Hai               | 2         | 3.08%   |
| Dell                            | 2         | 3.08%   |
| Apple                           | 2         | 3.08%   |
| Alps Electric                   | 2         | 3.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 11        | 16.92%  |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 7.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 4.62%   |
| Intel Bluetooth wireless interface                  | 3         | 4.62%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 4.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 4.62%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 4.62%   |
| Ralink RT3290 Bluetooth                             | 2         | 3.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 3.08%   |
| Lite-On Bluetooth Device                            | 2         | 3.08%   |
| Dell DW375 Bluetooth Module                         | 2         | 3.08%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.54%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.54%   |
| Toshiba Bluetooth Device                            | 1         | 1.54%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.54%   |
| Realtek Bluetooth Radio                             | 1         | 1.54%   |
| Realtek 802.11n WLAN Adapter                        | 1         | 1.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.54%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.54%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.54%   |
| IMC Networks Bluetooth module                       | 1         | 1.54%   |
| IMC Networks Bluetooth Device                       | 1         | 1.54%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.54%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.54%   |
| Broadcom IBM Integrated Bluetooth IV                | 1         | 1.54%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.54%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.54%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.54%   |
| Apple Bluetooth HCI                                 | 1         | 1.54%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.54%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 97        | 75.19%  |
| AMD                              | 16        | 12.4%   |
| Nvidia                           | 9         | 6.98%   |
| Silicon Integrated Systems [SiS] | 4         | 3.1%    |
| VIA Technologies                 | 2         | 1.55%   |
| Logitech                         | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 16.11%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 11.41%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 9.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 6.04%   |
| AMD FCH Azalia Controller                                                                         | 7         | 4.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 4.03%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 4.03%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 2.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 2.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 2.01%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 2.01%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 2.01%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 2.01%   |
| AMD High Definition Audio Controller                                                              | 3         | 2.01%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 1.34%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.34%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.34%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 1.34%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.34%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.34%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.67%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Logitech Z305                                                                                     | 1         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.67%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.67%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.67%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.67%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.67%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.67%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.67%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 9         | 28.13%  |
| Samsung Electronics | 8         | 25%     |
| SK Hynix            | 4         | 12.5%   |
| Kingston            | 2         | 6.25%   |
| Crucial             | 2         | 6.25%   |
| Toshiba             | 1         | 3.13%   |
| Smart               | 1         | 3.13%   |
| Micron Technology   | 1         | 3.13%   |
| Elpida              | 1         | 3.13%   |
| Corsair             | 1         | 3.13%   |
| A-DATA Technology   | 1         | 3.13%   |
| 48spaces            | 1         | 3.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 5.71%   |
| Unknown RAM Module SODIMM DDR                                             | 1         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DRAM                                     | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                            | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                            | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                            | 1         | 2.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                              | 1         | 2.86%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s                        | 1         | 2.86%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s                         | 1         | 2.86%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR 800MT/s                       | 1         | 2.86%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.86%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.86%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.86%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.86%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s                 | 1         | 2.86%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1600MT/s                 | 1         | 2.86%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s                       | 1         | 2.86%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                  | 1         | 2.86%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s                  | 1         | 2.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s            | 1         | 2.86%   |
| Samsung RAM M4 70T5663QZ3-CE6 2048MB SODIMM DDR2 667MT/s                  | 1         | 2.86%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.86%   |
| Kingston RAM KX830D-ELC 4GB SODIMM DDR3 1333MT/s                          | 1         | 2.86%   |
| Kingston RAM 9905428-196.A00LF 8192MB SODIMM DDR3 1333MT/s                | 1         | 2.86%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2048MB SODIMM DDR3 1334MT/s                  | 1         | 2.86%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s                | 1         | 2.86%   |
| Crucial RAM CT102464BF1339.C16 8GB SODIMM DDR3 1333MT/s                   | 1         | 2.86%   |
| Corsair RAM CMSX8GX3M1A1600C10 8192MB SODIMM DDR3 1600MT/s                | 1         | 2.86%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s                      | 1         | 2.86%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 23        | 74.19%  |
| DDR2  | 3         | 9.68%   |
| DDR   | 2         | 6.45%   |
| SDRAM | 1         | 3.23%   |
| DRAM  | 1         | 3.23%   |
| DDR4  | 1         | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 93.55%  |
| Row Of Chips | 1         | 3.23%   |
| Chip         | 1         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 15        | 45.45%  |
| 2048    | 11        | 33.33%  |
| 8192    | 5         | 15.15%  |
| 1024    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 42.42%  |
| 1333    | 5         | 15.15%  |
| Unknown | 5         | 15.15%  |
| 1334    | 2         | 6.06%   |
| 1066    | 2         | 6.06%   |
| 667     | 2         | 6.06%   |
| 3200    | 1         | 3.03%   |
| 800     | 1         | 3.03%   |
| 100     | 1         | 3.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 29.9%   |
| IMC Networks                           | 9         | 9.28%   |
| Suyin                                  | 7         | 7.22%   |
| Realtek Semiconductor                  | 7         | 7.22%   |
| Acer                                   | 7         | 7.22%   |
| Z-Star Microelectronics                | 6         | 6.19%   |
| Ricoh                                  | 5         | 5.15%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 5.15%   |
| Sunplus Innovation Technology          | 4         | 4.12%   |
| Microdia                               | 4         | 4.12%   |
| Silicon Motion                         | 3         | 3.09%   |
| Importek                               | 3         | 3.09%   |
| Syntek                                 | 2         | 2.06%   |
| Samsung Electronics                    | 1         | 1.03%   |
| Lite-On Technology                     | 1         | 1.03%   |
| DigiTech                               | 1         | 1.03%   |
| Apple                                  | 1         | 1.03%   |
| ALi                                    | 1         | 1.03%   |
| Alcor Micro                            | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 4         | 4.12%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 3.09%   |
| IMC Networks UVC VGA Webcam                                 | 3         | 3.09%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 3         | 3.09%   |
| Ricoh Sony Vaio Integrated Webcam                           | 2         | 2.06%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 2.06%   |
| Realtek HD WebCam                                           | 2         | 2.06%   |
| Importek HP Webcam-50                                       | 2         | 2.06%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 2.06%   |
| IMC Networks Integrated Webcam                              | 2         | 2.06%   |
| Chicony VGA Webcam                                          | 2         | 2.06%   |
| Chicony USB 2.0 Camera                                      | 2         | 2.06%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 2.06%   |
| Chicony Lenovo EasyCamera                                   | 2         | 2.06%   |
| Chicony CNF9055 Toshiba Webcam                              | 2         | 2.06%   |
| Acer Lenovo EasyCamera                                      | 2         | 2.06%   |
| Acer Integrated Camera                                      | 2         | 2.06%   |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 1.03%   |
| Z-Star Sirius USB2.0 Camera                                 | 1         | 1.03%   |
| Syntek USB Camera Device                                    | 1         | 1.03%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.03%   |
| Suyin HP Webcam 101                                         | 1         | 1.03%   |
| Suyin HP Webcam                                             | 1         | 1.03%   |
| Suyin HP Truevision HD                                      | 1         | 1.03%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.03%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 1.03%   |
| Sunplus HP TrueVision HD Camera                             | 1         | 1.03%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.03%   |
| Sunplus ASUS USB2.0 Webcam                                  | 1         | 1.03%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 1.03%   |
| Silicon Motion HP Webcam                                    | 1         | 1.03%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 1.03%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 1.03%   |
| Ricoh Integrated Webcam                                     | 1         | 1.03%   |
| Realtek USB Camera                                          | 1         | 1.03%   |
| Realtek Lenovo EasyCamera                                   | 1         | 1.03%   |
| Realtek Integrated_Webcam_HD                                | 1         | 1.03%   |
| Realtek Integrated Webcam                                   | 1         | 1.03%   |
| Realtek HP Truevision HD integrated webcam                  | 1         | 1.03%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.03%   |
| Microdia Laptop_Integrated_Webcam_0.3M                      | 1         | 1.03%   |
| Microdia Integrated Webcam                                  | 1         | 1.03%   |
| Microdia 1.3 MPixel Integrated Webcam                       | 1         | 1.03%   |
| Lite-On TOSHIBA Web Camera                                  | 1         | 1.03%   |
| Importek Webcam-101                                         | 1         | 1.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 1.03%   |
| IMC Networks TOSHIBA Web Camera - HD                        | 1         | 1.03%   |
| DigiTech USB 2.0 PC Camera                                  | 1         | 1.03%   |
| Chicony VGA 24fps UVC Webcam                                | 1         | 1.03%   |
| Chicony USB2.0 VGA UVC WebCam                               | 1         | 1.03%   |
| Chicony USB2.0 UVC WebCam                                   | 1         | 1.03%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.03%   |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 1.03%   |
| Chicony Integrated Camera                                   | 1         | 1.03%   |
| Chicony HP Wide Vision HD                                   | 1         | 1.03%   |
| Chicony HP Webcam [2 MP Macro]                              | 1         | 1.03%   |
| Chicony HP Webcam                                           | 1         | 1.03%   |
| Chicony HP TrueVision HD Camera                             | 1         | 1.03%   |
| Chicony HP Truevision HD                                    | 1         | 1.03%   |
| Chicony HP HD Webcam                                        | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| O2 Micro    | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 79        | 63.71%  |
| 1     | 35        | 28.23%  |
| 2     | 10        | 8.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 28.3%   |
| Net/wireless             | 9         | 16.98%  |
| Graphics card            | 8         | 15.09%  |
| Storage                  | 5         | 9.43%   |
| Chipcard                 | 5         | 9.43%   |
| Modem                    | 3         | 5.66%   |
| Bluetooth                | 3         | 5.66%   |
| Storage/ide              | 1         | 1.89%   |
| Multimedia controller    | 1         | 1.89%   |
| Flash memory             | 1         | 1.89%   |
| Communication controller | 1         | 1.89%   |
| Camera                   | 1         | 1.89%   |

