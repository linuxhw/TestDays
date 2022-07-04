Peppermint - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Peppermint.

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

Total: 248

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5567               | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| HP            | Laptop 17-by4xxx            | [4b63d98b33](https://linux-hardware.org/?probe=4b63d98b33) | May 16, 2022 |
| Lenovo        | G500 20236                  | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Dell          | Inspiron 3421               | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | G575 4383                   | [2f6fdef961](https://linux-hardware.org/?probe=2f6fdef961) | Apr 27, 2022 |
| Dell          | Inspiron MM061              | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| HP            | EliteBook 830 G5            | [271af2d869](https://linux-hardware.org/?probe=271af2d869) | Mar 30, 2022 |
| Packard Be... | EasyNote_MX45               | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| Dell          | Inspiron 1525               | [b8783a8415](https://linux-hardware.org/?probe=b8783a8415) | Mar 12, 2022 |
| Dell          | Inspiron 1525               | [b0d58c6895](https://linux-hardware.org/?probe=b0d58c6895) | Mar 12, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [bedf7835b0](https://linux-hardware.org/?probe=bedf7835b0) | Feb 08, 2022 |
| Dell          | Latitude D630               | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Dell          | Latitude D630               | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Medion        | WIM2160                     | [5e529f33bc](https://linux-hardware.org/?probe=5e529f33bc) | Jan 15, 2022 |
| Medion        | WIM2160                     | [758e2a7717](https://linux-hardware.org/?probe=758e2a7717) | Jan 15, 2022 |
| ASUSTek       | 1000HE                      | [3cdc62c355](https://linux-hardware.org/?probe=3cdc62c355) | Jan 05, 2022 |
| Acer          | AOA110                      | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASUSTek       | 1000H                       | [7b25815657](https://linux-hardware.org/?probe=7b25815657) | Dec 29, 2021 |
| Lenovo        | G575 4383                   | [ef4143d3b6](https://linux-hardware.org/?probe=ef4143d3b6) | Dec 22, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| Toshiba       | Satellite L300              | [1a2930b22b](https://linux-hardware.org/?probe=1a2930b22b) | Dec 02, 2021 |
| Acer          | Aspire 4810T                | [2f0aa07be8](https://linux-hardware.org/?probe=2f0aa07be8) | Nov 26, 2021 |
| Positivo      | Mobile                      | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Positivo      | Mobile                      | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| Dell          | Inspiron 1750               | [58d4a2dd00](https://linux-hardware.org/?probe=58d4a2dd00) | Nov 10, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | [15f9885d1f](https://linux-hardware.org/?probe=15f9885d1f) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| Toshiba       | Satellite L750D             | [e24684255d](https://linux-hardware.org/?probe=e24684255d) | Oct 26, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| Dell          | Inspiron 1018               | [7f51bdb2d1](https://linux-hardware.org/?probe=7f51bdb2d1) | Oct 08, 2021 |
| HP            | 2000                        | [00f01e8929](https://linux-hardware.org/?probe=00f01e8929) | Oct 08, 2021 |
| Dell          | Inspiron 1750               | [be79dd5979](https://linux-hardware.org/?probe=be79dd5979) | Oct 06, 2021 |
| Acer          | Aspire R3-131T              | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| HP            | 15                          | [a976f1d357](https://linux-hardware.org/?probe=a976f1d357) | Sep 28, 2021 |
| Unknown       | Unknown                     | [b54d6779c8](https://linux-hardware.org/?probe=b54d6779c8) | Sep 19, 2021 |
| Packard Be... | EasyNote TK85               | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| Toshiba       | dynabook Satellite B552/... | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| ASUSTek       | K52F                        | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| Sony          | VGN-S55B_S                  | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| Packard Be... | EasyNote TK85               | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
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
| LincPlus      | P1                          | [4b49a81a7c](https://linux-hardware.org/?probe=4b49a81a7c) | May 30, 2021 |
| HP            | Presario C500 (RZ343UA#A... | [d37099a83d](https://linux-hardware.org/?probe=d37099a83d) | May 25, 2021 |
| HP            | Presario C500 (RZ343UA#A... | [4aef9f472c](https://linux-hardware.org/?probe=4aef9f472c) | May 17, 2021 |
| LincPlus      | P1                          | [bac5471f0f](https://linux-hardware.org/?probe=bac5471f0f) | May 15, 2021 |
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
| Acer          | Aspire 7730G                | [6fadc9e655](https://linux-hardware.org/?probe=6fadc9e655) | Jan 31, 2021 |
| Toshiba       | Satellite L300              | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Sony          | VPCZ21V9E                   | [f0e8428fc2](https://linux-hardware.org/?probe=f0e8428fc2) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK T902               | [b0aa1bff61](https://linux-hardware.org/?probe=b0aa1bff61) | Jan 12, 2021 |
| Acer          | AOD255                      | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
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
| Fujitsu Si... | ESPRIMO Mobile V5535        | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| ASUSTek       | 1015PN                      | [c0c9898136](https://linux-hardware.org/?probe=c0c9898136) | Nov 19, 2020 |
| ASUSTek       | 1015PN                      | [f19c7014be](https://linux-hardware.org/?probe=f19c7014be) | Nov 19, 2020 |
| Dell          | Latitude E7440              | [222b0a563a](https://linux-hardware.org/?probe=222b0a563a) | Nov 15, 2020 |
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
| Itautec       | W7655                       | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| Toshiba       | Satellite C660              | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Samsung       | N150P                       | [17e2e411da](https://linux-hardware.org/?probe=17e2e411da) | Aug 07, 2020 |
| Toshiba       | Satellite L310              | [bf2bd8711e](https://linux-hardware.org/?probe=bf2bd8711e) | Aug 03, 2020 |
| Samsung       | N150/N210/N220              | [304d7ac49d](https://linux-hardware.org/?probe=304d7ac49d) | Aug 02, 2020 |
| HP            | EliteBook 2740p             | [b87f4916b6](https://linux-hardware.org/?probe=b87f4916b6) | Jul 27, 2020 |
| HP            | Compaq Presario CQ40        | [aaf338c454](https://linux-hardware.org/?probe=aaf338c454) | Jul 24, 2020 |
| Dell          | Latitude E6420              | [1db19a0158](https://linux-hardware.org/?probe=1db19a0158) | Jul 24, 2020 |
| Sony          | VGN-S55B_S                  | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| HP            | EliteBook 8570w             | [bd697a03f8](https://linux-hardware.org/?probe=bd697a03f8) | Jul 19, 2020 |
| Itautec       | W7655                       | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
| Positivo      | N1103                       | [3cdb7fc95e](https://linux-hardware.org/?probe=3cdb7fc95e) | Jul 13, 2020 |
| Toshiba       | PORTEGE R500                | [e7c5c010bd](https://linux-hardware.org/?probe=e7c5c010bd) | Jul 12, 2020 |
| Toshiba       | PORTEGE R500                | [fd50b5e2a7](https://linux-hardware.org/?probe=fd50b5e2a7) | Jul 12, 2020 |
| Dell          | Latitude E6420              | [52d11b26d3](https://linux-hardware.org/?probe=52d11b26d3) | Jul 09, 2020 |
| Acer          | Aspire R3-131T              | [dbecc119b2](https://linux-hardware.org/?probe=dbecc119b2) | Jul 08, 2020 |
| Sony          | VGN-S55B_S                  | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| HP            | Notebook                    | [841b43ba94](https://linux-hardware.org/?probe=841b43ba94) | Jun 14, 2020 |
| Lenovo        | B490 37722SP                | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| Toshiba       | Satellite L500              | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| HP            | Compaq Presario C700        | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Mini 110-1000               | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
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
| Toshiba       | Satellite C660              | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| Toshiba       | Satellite Pro C850          | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
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
| ASUSTek       | F3E                         | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | Pavilion dv6500             | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| Lenovo        | 3000 N500 423374G           | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| eMachines     | E520 V1.06                  | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| HP            | Pavilion dv4                | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Acer          | Aspire 7730G                | [f00cf2c184](https://linux-hardware.org/?probe=f00cf2c184) | Feb 13, 2020 |
| Toshiba       | Satellite C850-F117         | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Sony          | VGN-CR21S_P                 | [2ceca1462f](https://linux-hardware.org/?probe=2ceca1462f) | Feb 08, 2020 |
| Apple         | MacBook4,1                  | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| Apple         | MacBook4,1                  | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Toshiba       | NB520                       | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
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
| HP            | Pavilion 11 x360 PC         | [cc352f0876](https://linux-hardware.org/?probe=cc352f0876) | Nov 10, 2019 |
| HP            | Pavilion 11 x360 PC         | [a4bd90bb25](https://linux-hardware.org/?probe=a4bd90bb25) | Nov 09, 2019 |
| HP            | Laptop 15-bs0xx             | [2ac11dfe68](https://linux-hardware.org/?probe=2ac11dfe68) | Nov 02, 2019 |
| ASUSTek       | 1005PXD                     | [d0afcbe081](https://linux-hardware.org/?probe=d0afcbe081) | Oct 26, 2019 |
| ASUSTek       | 1005PXD                     | [1e57ee0116](https://linux-hardware.org/?probe=1e57ee0116) | Oct 26, 2019 |
| HP            | Pavilion Notebook           | [14784cf228](https://linux-hardware.org/?probe=14784cf228) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | [6e3970fc39](https://linux-hardware.org/?probe=6e3970fc39) | Sep 17, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | [20f7841be1](https://linux-hardware.org/?probe=20f7841be1) | Sep 17, 2019 |
| HP            | Pavilion Notebook           | [f29f057c97](https://linux-hardware.org/?probe=f29f057c97) | Sep 16, 2019 |
| Dell          | Inspiron 1501               | [a638607db3](https://linux-hardware.org/?probe=a638607db3) | Sep 11, 2019 |
| Unknown       | Unknown                     | [0a9618f99e](https://linux-hardware.org/?probe=0a9618f99e) | Jul 10, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Pavilion dv7                | [24128291a4](https://linux-hardware.org/?probe=24128291a4) | Jun 25, 2019 |
| Unknown       | Unknown                     | [583ec484b5](https://linux-hardware.org/?probe=583ec484b5) | Jun 24, 2019 |
| Unknown       | Unknown                     | [c0eb7dc5f0](https://linux-hardware.org/?probe=c0eb7dc5f0) | Jun 24, 2019 |
| ASUSTek       | Q501LA                      | [ad06395996](https://linux-hardware.org/?probe=ad06395996) | Jun 23, 2019 |
| Toshiba       | Satellite M70               | [c31329a508](https://linux-hardware.org/?probe=c31329a508) | Jun 19, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | [cca643879f](https://linux-hardware.org/?probe=cca643879f) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |
| Gateway       | MX6940M                     | [668db92873](https://linux-hardware.org/?probe=668db92873) | May 09, 2019 |
| Dell          | Latitude D630               | [6ad005d6b7](https://linux-hardware.org/?probe=6ad005d6b7) | May 02, 2019 |
| WinBook       | GL Series                   | [89dac45ef6](https://linux-hardware.org/?probe=89dac45ef6) | Apr 28, 2019 |
| Dell          | Latitude D630               | [d8bf959191](https://linux-hardware.org/?probe=d8bf959191) | Apr 16, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | [c662baa8f5](https://linux-hardware.org/?probe=c662baa8f5) | Apr 10, 2019 |
| eMachines     | E620                        | [de3cfd34b1](https://linux-hardware.org/?probe=de3cfd34b1) | Apr 05, 2019 |
| Dell          | Latitude D430               | [269e1c2948](https://linux-hardware.org/?probe=269e1c2948) | Apr 04, 2019 |
| Dell          | Latitude D430               | [d1c49bd4e8](https://linux-hardware.org/?probe=d1c49bd4e8) | Apr 04, 2019 |
| Positivo      | UW3                         | [dda25a3dc9](https://linux-hardware.org/?probe=dda25a3dc9) | Apr 03, 2019 |
| Positivo      | UW3                         | [aebfedfabb](https://linux-hardware.org/?probe=aebfedfabb) | Apr 03, 2019 |
| HP            | Pavilion dv1000 (PS600EA... | [6802b34fdd](https://linux-hardware.org/?probe=6802b34fdd) | Mar 31, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Acer          | Aspire 7730G                | [09bd4355b9](https://linux-hardware.org/?probe=09bd4355b9) | Jan 30, 2019 |
| Clevo         | M660SR VT6363A              | [647fd58075](https://linux-hardware.org/?probe=647fd58075) | Jan 15, 2019 |
| Clevo         | M660SR VT6363A              | [ad84ff197d](https://linux-hardware.org/?probe=ad84ff197d) | Jan 15, 2019 |
| Lenovo        | ThinkPad W510 4391B49       | [227847df62](https://linux-hardware.org/?probe=227847df62) | Feb 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Peppermint 10   | 144       | 87.8%   |
| Peppermint 9    | 16        | 9.76%   |
| Peppermint 11.2 | 2         | 1.22%   |
| Peppermint 8    | 1         | 0.61%   |
| Peppermint      | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Peppermint | 164       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.0.0-37-generic      | 24        | 13.11%  |
| 5.4.0-42-generic      | 7         | 3.83%   |
| 5.3.0-62-generic      | 7         | 3.83%   |
| 5.3.0-51-generic      | 7         | 3.83%   |
| 4.18.0-18-generic     | 7         | 3.83%   |
| 5.4.0-65-generic      | 6         | 3.28%   |
| 4.15.0-43-generic     | 6         | 3.28%   |
| 5.4.0-91-generic      | 4         | 2.19%   |
| 5.4.0-72-generic      | 4         | 2.19%   |
| 5.4.0-58-generic      | 4         | 2.19%   |
| 5.0.0-32-generic      | 4         | 2.19%   |
| 5.4.0-90-generic      | 3         | 1.64%   |
| 5.4.0-87-generic      | 3         | 1.64%   |
| 5.4.0-80-generic      | 3         | 1.64%   |
| 5.4.0-77-generic      | 3         | 1.64%   |
| 5.4.0-66-generic      | 3         | 1.64%   |
| 5.4.0-47-generic      | 3         | 1.64%   |
| 5.4.0-45-generic      | 3         | 1.64%   |
| 5.3.0-46-generic      | 3         | 1.64%   |
| 5.3.0-42-generic      | 3         | 1.64%   |
| 5.3.0-28-generic      | 3         | 1.64%   |
| 5.0.0-36-generic      | 3         | 1.64%   |
| 4.15.0-48-generic     | 3         | 1.64%   |
| 4.15.0-47-generic     | 3         | 1.64%   |
| 5.4.0-97-generic      | 2         | 1.09%   |
| 5.4.0-84-generic      | 2         | 1.09%   |
| 5.4.0-81-generic      | 2         | 1.09%   |
| 5.4.0-74-generic      | 2         | 1.09%   |
| 5.4.0-70-generic      | 2         | 1.09%   |
| 5.4.0-67-generic      | 2         | 1.09%   |
| 5.4.0-56-generic      | 2         | 1.09%   |
| 5.4.0-54-generic      | 2         | 1.09%   |
| 5.4.0-52-generic      | 2         | 1.09%   |
| 5.4.0-48-generic      | 2         | 1.09%   |
| 5.3.0-59-generic      | 2         | 1.09%   |
| 5.3.0-40-generic      | 2         | 1.09%   |
| 5.10.0-11-amd64       | 2         | 1.09%   |
| 5.0.0-27-generic      | 2         | 1.09%   |
| 4.18.0-21-generic     | 2         | 1.09%   |
| 4.15.0-76-generic     | 2         | 1.09%   |
| 5.4.95-050495-generic | 1         | 0.55%   |
| 5.4.0-94-generic      | 1         | 0.55%   |
| 5.4.0-92-generic      | 1         | 0.55%   |
| 5.4.0-73-generic      | 1         | 0.55%   |
| 5.4.0-71-generic      | 1         | 0.55%   |
| 5.4.0-64-generic      | 1         | 0.55%   |
| 5.4.0-62-generic      | 1         | 0.55%   |
| 5.4.0-60-generic      | 1         | 0.55%   |
| 5.4.0-59-generic      | 1         | 0.55%   |
| 5.4.0-53-generic      | 1         | 0.55%   |
| 5.4.0-51-generic      | 1         | 0.55%   |
| 5.4.0-49-generic      | 1         | 0.55%   |
| 5.4.0-44-generic      | 1         | 0.55%   |
| 5.4.0-120-generic     | 1         | 0.55%   |
| 5.4.0-109-generic     | 1         | 0.55%   |
| 5.4.0-107-generic     | 1         | 0.55%   |
| 5.4.0-104-generic     | 1         | 0.55%   |
| 5.3.6-050306-generic  | 1         | 0.55%   |
| 5.3.0-45-generic      | 1         | 0.55%   |
| 5.10.0-12-amd64       | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 77        | 45.03%  |
| 5.0.0   | 32        | 18.71%  |
| 5.3.0   | 27        | 15.79%  |
| 4.15.0  | 15        | 8.77%   |
| 4.18.0  | 13        | 7.6%    |
| 5.10.0  | 3         | 1.75%   |
| 5.4.95  | 1         | 0.58%   |
| 5.3.6   | 1         | 0.58%   |
| 5.1.11  | 1         | 0.58%   |
| 4.8.0   | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 78        | 45.61%  |
| 5.0     | 32        | 18.71%  |
| 5.3     | 28        | 16.37%  |
| 4.15    | 15        | 8.77%   |
| 4.18    | 13        | 7.6%    |
| 5.10    | 3         | 1.75%   |
| 5.1     | 1         | 0.58%   |
| 4.8     | 1         | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 104       | 63.41%  |
| i686   | 60        | 36.59%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXDE       | 122       | 73.05%  |
| Unknown    | 33        | 19.76%  |
| GNOME      | 7         | 4.19%   |
| XFCE       | 3         | 1.8%    |
| X-Cinnamon | 1         | 0.6%    |
| Peppermint | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 164       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 146       | 88.48%  |
| LightDM | 11        | 6.67%   |
| TDM     | 7         | 4.24%   |
| SDDM    | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 30.54%  |
| Unknown | 27        | 16.17%  |
| en_GB   | 11        | 6.59%   |
| de_DE   | 10        | 5.99%   |
| pt_BR   | 8         | 4.79%   |
| it_IT   | 7         | 4.19%   |
| pl_PL   | 6         | 3.59%   |
| nl_NL   | 5         | 2.99%   |
| C       | 5         | 2.99%   |
| fr_FR   | 4         | 2.4%    |
| en_CA   | 4         | 2.4%    |
| ru_RU   | 3         | 1.8%    |
| es_AR   | 3         | 1.8%    |
| ro_RO   | 2         | 1.2%    |
| ja_JP   | 2         | 1.2%    |
| es_MX   | 2         | 1.2%    |
| en_IN   | 2         | 1.2%    |
| tr_TR   | 1         | 0.6%    |
| sv_SE   | 1         | 0.6%    |
| pt_PT   | 1         | 0.6%    |
| lv_LV   | 1         | 0.6%    |
| fi_FI   | 1         | 0.6%    |
| es_PE   | 1         | 0.6%    |
| es_PA   | 1         | 0.6%    |
| es_ES   | 1         | 0.6%    |
| es_CR   | 1         | 0.6%    |
| es_BO   | 1         | 0.6%    |
| en_ZA   | 1         | 0.6%    |
| en_PH   | 1         | 0.6%    |
| en_AU   | 1         | 0.6%    |
| el_GR   | 1         | 0.6%    |
| cs_CZ   | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 129       | 78.66%  |
| EFI  | 35        | 21.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 137       | 82.53%  |
| Unknown  | 16        | 9.64%   |
| Overlay  | 6         | 3.61%   |
| Ext3     | 2         | 1.2%    |
| Ext2     | 2         | 1.2%    |
| Reiserfs | 1         | 0.6%    |
| Btrfs    | 1         | 0.6%    |
| Aufs     | 1         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 150       | 90.91%  |
| GPT     | 8         | 4.85%   |
| MBR     | 7         | 4.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 157       | 94.58%  |
| Yes       | 9         | 5.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 88.02%  |
| Yes       | 20        | 11.98%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 34        | 20.73%  |
| Dell                | 20        | 12.2%   |
| Lenovo              | 19        | 11.59%  |
| ASUSTek Computer    | 17        | 10.37%  |
| Toshiba             | 16        | 9.76%   |
| Acer                | 14        | 8.54%   |
| Samsung Electronics | 7         | 4.27%   |
| Sony                | 5         | 3.05%   |
| Fujitsu Siemens     | 5         | 3.05%   |
| Positivo            | 3         | 1.83%   |
| eMachines           | 3         | 1.83%   |
| Packard Bell        | 2         | 1.22%   |
| Medion              | 2         | 1.22%   |
| IBM                 | 2         | 1.22%   |
| Gateway             | 2         | 1.22%   |
| Clevo               | 2         | 1.22%   |
| Apple               | 2         | 1.22%   |
| Unknown             | 2         | 1.22%   |
| WinBook             | 1         | 0.61%   |
| Olivetti            | 1         | 0.61%   |
| LincPlus            | 1         | 0.61%   |
| JPSaCouto           | 1         | 0.61%   |
| Itautec             | 1         | 0.61%   |
| Google              | 1         | 0.61%   |
| Fujitsu             | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo G500 20236                          | 3         | 1.83%   |
| Toshiba Satellite M70                      | 2         | 1.22%   |
| Toshiba Satellite L500                     | 2         | 1.22%   |
| Samsung N150P/N210P/N220P                  | 2         | 1.22%   |
| Positivo Mobile                            | 2         | 1.22%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 1.22%   |
| Dell Latitude D630                         | 2         | 1.22%   |
| Dell Inspiron N5050                        | 2         | 1.22%   |
| Acer Extensa 5630                          | 2         | 1.22%   |
| Unknown                                    | 2         | 1.22%   |
| WinBook GL Series                          | 1         | 0.61%   |
| Toshiba Satellite Pro C850                 | 1         | 0.61%   |
| Toshiba Satellite L750D                    | 1         | 0.61%   |
| Toshiba Satellite L310                     | 1         | 0.61%   |
| Toshiba Satellite L300                     | 1         | 0.61%   |
| Toshiba Satellite C850-F117                | 1         | 0.61%   |
| Toshiba Satellite C660                     | 1         | 0.61%   |
| Toshiba Satellite C55D-B                   | 1         | 0.61%   |
| Toshiba QOSMIO F755                        | 1         | 0.61%   |
| Toshiba PORTEGE R500                       | 1         | 0.61%   |
| Toshiba NB520                              | 1         | 0.61%   |
| Toshiba NB500                              | 1         | 0.61%   |
| Toshiba dynabook Satellite B552/H          | 1         | 0.61%   |
| Sony VPCZ21V9E                             | 1         | 0.61%   |
| Sony VPCCW21FX                             | 1         | 0.61%   |
| Sony VGN-S55B_S                            | 1         | 0.61%   |
| Sony VGN-FW140E                            | 1         | 0.61%   |
| Sony VGN-CR21S_P                           | 1         | 0.61%   |
| Samsung R610                               | 1         | 0.61%   |
| Samsung R530/R730/R540                     | 1         | 0.61%   |
| Samsung N150P                              | 1         | 0.61%   |
| Samsung N150/N210/N220                     | 1         | 0.61%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.61%   |
| Positivo N1103                             | 1         | 0.61%   |
| Packard Bell EasyNote_MX45                 | 1         | 0.61%   |
| Packard Bell EasyNote TK85                 | 1         | 0.61%   |
| Olivetti CL133A                            | 1         | 0.61%   |
| Medion WIM2160                             | 1         | 0.61%   |
| Medion Akoya E4214 MD99570                 | 1         | 0.61%   |
| LincPlus P1                                | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BS0035US   | 1         | 0.61%   |
| Lenovo ThinkPad W510 4391B49               | 1         | 0.61%   |
| Lenovo ThinkPad T60 1951CJ4                | 1         | 0.61%   |
| Lenovo ThinkPad T450 20BUS3CF00            | 1         | 0.61%   |
| Lenovo ThinkPad R60 94566FG                | 1         | 0.61%   |
| Lenovo ThinkPad Edge E431 62775GU          | 1         | 0.61%   |
| Lenovo ThinkPad E490 20N90019BR            | 1         | 0.61%   |
| Lenovo IdeaPad Z460 20059                  | 1         | 0.61%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 1         | 0.61%   |
| Lenovo IdeaPad 1 11ADA05 82GV              | 1         | 0.61%   |
| Lenovo G575 4383                           | 1         | 0.61%   |
| Lenovo B575 1450A7U                        | 1         | 0.61%   |
| Lenovo B570e HuronRiver Platform           | 1         | 0.61%   |
| Lenovo B490 37722SP                        | 1         | 0.61%   |
| Lenovo 433328G                             | 1         | 0.61%   |
| Lenovo 3000 N500 423374G                   | 1         | 0.61%   |
| JPSaCouto Intel powered classmate PC       | 1         | 0.61%   |
| Itautec Infoway                            | 1         | 0.61%   |
| IBM ThinkPad X41 Tablet 1869CNG            | 1         | 0.61%   |
| IBM ThinkPad T43 2669GY4                   | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Toshiba Satellite       | 11        | 6.71%   |
| Dell Inspiron           | 11        | 6.71%   |
| HP Pavilion             | 9         | 5.49%   |
| Lenovo ThinkPad         | 7         | 4.27%   |
| HP Compaq               | 6         | 3.66%   |
| Dell Latitude           | 6         | 3.66%   |
| Acer Aspire             | 6         | 3.66%   |
| HP EliteBook            | 5         | 3.05%   |
| Acer Extensa            | 4         | 2.44%   |
| Samsung N150P           | 3         | 1.83%   |
| Lenovo IdeaPad          | 3         | 1.83%   |
| Lenovo G500             | 3         | 1.83%   |
| HP Laptop               | 3         | 1.83%   |
| Fujitsu Siemens AMILO   | 3         | 1.83%   |
| Positivo Mobile         | 2         | 1.22%   |
| Packard Bell EasyNote   | 2         | 1.22%   |
| IBM ThinkPad            | 2         | 1.22%   |
| HP Stream               | 2         | 1.22%   |
| HP Mini                 | 2         | 1.22%   |
| HP 255                  | 2         | 1.22%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.22%   |
| Dell Precision          | 2         | 1.22%   |
| Unknown                 | 2         | 1.22%   |
| WinBook GL              | 1         | 0.61%   |
| Toshiba QOSMIO          | 1         | 0.61%   |
| Toshiba PORTEGE         | 1         | 0.61%   |
| Toshiba NB520           | 1         | 0.61%   |
| Toshiba NB500           | 1         | 0.61%   |
| Toshiba dynabook        | 1         | 0.61%   |
| Sony VPCZ21V9E          | 1         | 0.61%   |
| Sony VPCCW21FX          | 1         | 0.61%   |
| Sony VGN-S55B           | 1         | 0.61%   |
| Sony VGN-FW140E         | 1         | 0.61%   |
| Sony VGN-CR21S          | 1         | 0.61%   |
| Samsung R610            | 1         | 0.61%   |
| Samsung R530            | 1         | 0.61%   |
| Samsung N150            | 1         | 0.61%   |
| Samsung 300E4A          | 1         | 0.61%   |
| Positivo N1103          | 1         | 0.61%   |
| Olivetti CL133A         | 1         | 0.61%   |
| Medion WIM2160          | 1         | 0.61%   |
| Medion Akoya            | 1         | 0.61%   |
| LincPlus P1             | 1         | 0.61%   |
| Lenovo G575             | 1         | 0.61%   |
| Lenovo B575             | 1         | 0.61%   |
| Lenovo B570e            | 1         | 0.61%   |
| Lenovo B490             | 1         | 0.61%   |
| Lenovo 433328G          | 1         | 0.61%   |
| Lenovo 3000             | 1         | 0.61%   |
| JPSaCouto Intel         | 1         | 0.61%   |
| Itautec Infoway         | 1         | 0.61%   |
| HP Presario             | 1         | 0.61%   |
| HP Notebook             | 1         | 0.61%   |
| HP 2133                 | 1         | 0.61%   |
| HP 2000                 | 1         | 0.61%   |
| HP 15                   | 1         | 0.61%   |
| Google Gnawty           | 1         | 0.61%   |
| Gateway MX6940M         | 1         | 0.61%   |
| Gateway Blade-K8F       | 1         | 0.61%   |
| Fujitsu LIFEBOOK        | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2008    | 25        | 15.24%  |
| 2011    | 19        | 11.59%  |
| 2009    | 17        | 10.37%  |
| 2010    | 16        | 9.76%   |
| 2007    | 16        | 9.76%   |
| 2006    | 12        | 7.32%   |
| 2012    | 11        | 6.71%   |
| 2013    | 10        | 6.1%    |
| 2016    | 6         | 3.66%   |
| 2015    | 6         | 3.66%   |
| 2014    | 6         | 3.66%   |
| 2018    | 5         | 3.05%   |
| 2005    | 5         | 3.05%   |
| 2020    | 3         | 1.83%   |
| 2019    | 3         | 1.83%   |
| 2017    | 3         | 1.83%   |
| Unknown | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 164       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 156       | 95.12%  |
| Enabled  | 8         | 4.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 163       | 99.39%  |
| Yes  | 1         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 47        | 28.31%  |
| 1.01-2.0   | 46        | 27.71%  |
| 4.01-8.0   | 24        | 14.46%  |
| 0.51-1.0   | 17        | 10.24%  |
| 2.01-3.0   | 14        | 8.43%   |
| 8.01-16.0  | 11        | 6.63%   |
| 16.01-24.0 | 5         | 3.01%   |
| 32.01-64.0 | 1         | 0.6%    |
| 0.01-0.5   | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 67        | 37.02%  |
| 1.01-2.0 | 64        | 35.36%  |
| 2.01-3.0 | 26        | 14.36%  |
| 0.01-0.5 | 18        | 9.94%   |
| 3.01-4.0 | 4         | 2.21%   |
| 4.01-8.0 | 2         | 1.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 130       | 77.38%  |
| 2      | 31        | 18.45%  |
| 3      | 4         | 2.38%   |
| 0      | 3         | 1.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 59.39%  |
| No        | 67        | 40.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 92.07%  |
| No        | 13        | 7.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 98.78%  |
| No        | 2         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 52.12%  |
| Yes       | 79        | 47.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 41        | 25%     |
| Germany      | 16        | 9.76%   |
| UK           | 10        | 6.1%    |
| Netherlands  | 9         | 5.49%   |
| Italy        | 8         | 4.88%   |
| Canada       | 8         | 4.88%   |
| Brazil       | 8         | 4.88%   |
| Poland       | 6         | 3.66%   |
| France       | 5         | 3.05%   |
| Russia       | 4         | 2.44%   |
| Romania      | 4         | 2.44%   |
| Sweden       | 3         | 1.83%   |
| Spain        | 3         | 1.83%   |
| Mexico       | 3         | 1.83%   |
| Japan        | 3         | 1.83%   |
| Argentina    | 3         | 1.83%   |
| Portugal     | 2         | 1.22%   |
| India        | 2         | 1.22%   |
| Greece       | 2         | 1.22%   |
| Bolivia      | 2         | 1.22%   |
| Turkey       | 1         | 0.61%   |
| Switzerland  | 1         | 0.61%   |
| South Africa | 1         | 0.61%   |
| Serbia       | 1         | 0.61%   |
| Puerto Rico  | 1         | 0.61%   |
| Philippines  | 1         | 0.61%   |
| Peru         | 1         | 0.61%   |
| Panama       | 1         | 0.61%   |
| Norway       | 1         | 0.61%   |
| Namibia      | 1         | 0.61%   |
| Malaysia     | 1         | 0.61%   |
| Lithuania    | 1         | 0.61%   |
| Latvia       | 1         | 0.61%   |
| Kazakhstan   | 1         | 0.61%   |
| Ireland      | 1         | 0.61%   |
| Georgia      | 1         | 0.61%   |
| Finland      | 1         | 0.61%   |
| Czechia      | 1         | 0.61%   |
| Costa Rica   | 1         | 0.61%   |
| Bulgaria     | 1         | 0.61%   |
| Belarus      | 1         | 0.61%   |
| Australia    | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Toronto                 | 4         | 2.34%   |
| Warsaw                  | 2         | 1.17%   |
| Turin                   | 2         | 1.17%   |
| Topeka                  | 2         | 1.17%   |
| Tokyo                   | 2         | 1.17%   |
| Osasco                  | 2         | 1.17%   |
| Naples                  | 2         | 1.17%   |
| Moscow                  | 2         | 1.17%   |
| Bucharest               | 2         | 1.17%   |
| Zgierz                  | 1         | 0.58%   |
| York                    | 1         | 0.58%   |
| Yokohama                | 1         | 0.58%   |
| Wysokie Mazowieckie     | 1         | 0.58%   |
| Worthing                | 1         | 0.58%   |
| Windhoek                | 1         | 0.58%   |
| West New York           | 1         | 0.58%   |
| West Chester            | 1         | 0.58%   |
| Weinheim                | 1         | 0.58%   |
| Waalwijk                | 1         | 0.58%   |
| Volos                   | 1         | 0.58%   |
| Villa María            | 1         | 0.58%   |
| Vijayawada              | 1         | 0.58%   |
| Venda do Pinheiro       | 1         | 0.58%   |
| Varna                   | 1         | 0.58%   |
| Umeå                   | 1         | 0.58%   |
| Trento                  | 1         | 0.58%   |
| Telford                 | 1         | 0.58%   |
| Tampere                 | 1         | 0.58%   |
| Tahlequah               | 1         | 0.58%   |
| Stockton                | 1         | 0.58%   |
| Staffanstorp            | 1         | 0.58%   |
| Southampton             | 1         | 0.58%   |
| Sicklerville            | 1         | 0.58%   |
| Sherwood Park           | 1         | 0.58%   |
| Seattle                 | 1         | 0.58%   |
| Scarborough             | 1         | 0.58%   |
| Sao Paulo               | 1         | 0.58%   |
| Santa Cruz              | 1         | 0.58%   |
| Sant Pere de Vilamajor  | 1         | 0.58%   |
| Sant Feliu de Llobregat | 1         | 0.58%   |
| San Vito al Tagliamento | 1         | 0.58%   |
| San Rafael              | 1         | 0.58%   |
| Saint-Germain-en-Laye   | 1         | 0.58%   |
| Ronago                  | 1         | 0.58%   |
| Riga                    | 1         | 0.58%   |
| Queens                  | 1         | 0.58%   |
| Prince Frederick        | 1         | 0.58%   |
| Prague                  | 1         | 0.58%   |
| Poznan                  | 1         | 0.58%   |
| Pouso Alegre            | 1         | 0.58%   |
| Potosí                 | 1         | 0.58%   |
| Potigny                 | 1         | 0.58%   |
| Portets                 | 1         | 0.58%   |
| Ponte de Lima           | 1         | 0.58%   |
| Polokwane               | 1         | 0.58%   |
| Pisgah                  | 1         | 0.58%   |
| Piedmont                | 1         | 0.58%   |
| Petrópolis             | 1         | 0.58%   |
| Perth                   | 1         | 0.58%   |
| Panama City             | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 42     | 22.6%   |
| WDC                 | 28        | 33     | 15.82%  |
| Unknown             | 18        | 21     | 10.17%  |
| Samsung Electronics | 18        | 28     | 10.17%  |
| Toshiba             | 16        | 17     | 9.04%   |
| Hitachi             | 14        | 17     | 7.91%   |
| Kingston            | 8         | 10     | 4.52%   |
| Fujitsu             | 5         | 6      | 2.82%   |
| SanDisk             | 4         | 5      | 2.26%   |
| HGST                | 4         | 5      | 2.26%   |
| PNY                 | 2         | 2      | 1.13%   |
| Integral            | 2         | 2      | 1.13%   |
| Zheino              | 1         | 1      | 0.56%   |
| TrekStor            | 1         | 1      | 0.56%   |
| TCSUNBOW            | 1         | 1      | 0.56%   |
| SK hynix            | 1         | 1      | 0.56%   |
| SABRENT             | 1         | 1      | 0.56%   |
| Patriot             | 1         | 1      | 0.56%   |
| Micron Technology   | 1         | 1      | 0.56%   |
| LITEONIT            | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| Intel               | 1         | 1      | 0.56%   |
| Goodram             | 1         | 1      | 0.56%   |
| FATTYDOVE           | 1         | 1      | 0.56%   |
| Drevo               | 1         | 1      | 0.56%   |
| Crucial             | 1         | 1      | 0.56%   |
| China               | 1         | 1      | 0.56%   |
| BHT                 | 1         | 2      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |
| Apacer              | 1         | 3      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                     | 6         | 3.31%   |
| Seagate ST9500325AS 500GB                  | 4         | 2.21%   |
| Seagate ST9250315AS 250GB                  | 4         | 2.21%   |
| Seagate ST500LM012 HN-M500MBB 500GB        | 4         | 2.21%   |
| Seagate ST9320325AS 320GB                  | 3         | 1.66%   |
| Seagate ST500LT012-1DG142 500GB            | 3         | 1.66%   |
| WDC WD3200BPVT-24JJ5T0 320GB               | 2         | 1.1%    |
| WDC WD3200BPVT-22ZEST0 320GB               | 2         | 1.1%    |
| WDC WD1200BEVS-22UST0 120GB                | 2         | 1.1%    |
| Unknown SD/MMC/MS PRO 128GB                | 2         | 1.1%    |
| Unknown MMC Card  64GB                     | 2         | 1.1%    |
| Unknown MMC Card  2GB                      | 2         | 1.1%    |
| Unknown MMC Card  16GB                     | 2         | 1.1%    |
| Toshiba MK5055GSX 500GB                    | 2         | 1.1%    |
| Seagate ST750LM022 HN-M750MBB 752GB        | 2         | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB             | 2         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 1.1%    |
| Samsung HM160HI 160GB                      | 2         | 1.1%    |
| Kingston SA400S37240G 240GB SSD            | 2         | 1.1%    |
| Kingston SA400S37120G 120GB SSD            | 2         | 1.1%    |
| Hitachi HTS545025B9A300 250GB              | 2         | 1.1%    |
| HGST HTS725032A7E630 320GB                 | 2         | 1.1%    |
| Zheino CHN 25SATAA3 120 120GB SSD          | 1         | 0.55%   |
| WDC WDS120G2G0A-00JH30 120GB SSD           | 1         | 0.55%   |
| WDC WD800BEVS-60LAT0 80GB                  | 1         | 0.55%   |
| WDC WD5000LPVX-60V0TT0 500GB               | 1         | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB               | 1         | 0.55%   |
| WDC WD5000BPVT-00HXZT3 500GB               | 1         | 0.55%   |
| WDC WD3200BPVT-08JJ5T0 320GB               | 1         | 0.55%   |
| WDC WD3200BEVT-75ZCT2 320GB                | 1         | 0.55%   |
| WDC WD2500BPVT-24ZEST0 250GB               | 1         | 0.55%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 0.55%   |
| WDC WD2500BEVT-35A23T0 250GB               | 1         | 0.55%   |
| WDC WD2500BEVS-00UST0 250GB                | 1         | 0.55%   |
| WDC WD2500BEKT-66F3T2 250GB                | 1         | 0.55%   |
| WDC WD1600BEVT-60ZCT1 160GB                | 1         | 0.55%   |
| WDC WD1600BEVT-22ZCT0 160GB                | 1         | 0.55%   |
| WDC WD1600BEVT-00A23T0 160GB               | 1         | 0.55%   |
| WDC WD1600BEVS-22RST0 160GB                | 1         | 0.55%   |
| WDC WD1600BEVS-08VAT2 160GB                | 1         | 0.55%   |
| WDC WD1600BEVS-07RST0 160GB                | 1         | 0.55%   |
| WDC WD1600BEKT-75A25T0 160GB               | 1         | 0.55%   |
| WDC WD10SPCX-80HWST0 1TB                   | 1         | 0.55%   |
| WDC WD10JPVX-75JC3T0 1TB                   | 1         | 0.55%   |
| WDC WD10JPVX-60JC3T0 1TB                   | 1         | 0.55%   |
| Unknown SL16G  16GB                        | 1         | 0.55%   |
| Unknown SFSA120GM3AA4TO-I-LB-616-G30 120GB | 1         | 0.55%   |
| Unknown SE128  128GB                       | 1         | 0.55%   |
| Unknown MMC Card  970MB                    | 1         | 0.55%   |
| Unknown MMC Card  134GB                    | 1         | 0.55%   |
| Unknown MMC Card  128GB                    | 1         | 0.55%   |
| TrekStor TREKSTORSSD64GB                   | 1         | 0.55%   |
| Toshiba MQ04ABF100 1TB                     | 1         | 0.55%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 0.55%   |
| Toshiba MQ01ABD032 320GB                   | 1         | 0.55%   |
| Toshiba MK8032GSX 80GB                     | 1         | 0.55%   |
| Toshiba MK7559GSXP 752GB                   | 1         | 0.55%   |
| Toshiba MK6008GAH 64GB                     | 1         | 0.55%   |
| Toshiba MK5055GSXN 500GB                   | 1         | 0.55%   |
| Toshiba MK3265GSX 320GB                    | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 41     | 33.91%  |
| WDC                 | 27        | 32     | 23.48%  |
| Toshiba             | 16        | 17     | 13.91%  |
| Hitachi             | 14        | 17     | 12.17%  |
| Samsung Electronics | 8         | 8      | 6.96%   |
| Fujitsu             | 5         | 6      | 4.35%   |
| HGST                | 4         | 5      | 3.48%   |
| Unknown             | 2         | 2      | 1.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 18     | 21.43%  |
| Kingston            | 8         | 10     | 19.05%  |
| SanDisk             | 4         | 5      | 9.52%   |
| PNY                 | 2         | 2      | 4.76%   |
| Integral            | 2         | 2      | 4.76%   |
| Zheino              | 1         | 1      | 2.38%   |
| WDC                 | 1         | 1      | 2.38%   |
| TrekStor            | 1         | 1      | 2.38%   |
| TCSUNBOW            | 1         | 1      | 2.38%   |
| Patriot             | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| KingSpec            | 1         | 1      | 2.38%   |
| Intel               | 1         | 1      | 2.38%   |
| Goodram             | 1         | 1      | 2.38%   |
| FATTYDOVE           | 1         | 1      | 2.38%   |
| Drevo               | 1         | 1      | 2.38%   |
| Crucial             | 1         | 1      | 2.38%   |
| China               | 1         | 1      | 2.38%   |
| BHT                 | 1         | 2      | 2.38%   |
| Apple               | 1         | 1      | 2.38%   |
| Apacer              | 1         | 3      | 2.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 113       | 128    | 64.57%  |
| SSD     | 41        | 57     | 23.43%  |
| MMC     | 16        | 19     | 9.14%   |
| Unknown | 3         | 3      | 1.71%   |
| NVMe    | 2         | 2      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 147       | 182    | 85.96%  |
| MMC  | 16        | 19     | 9.36%   |
| SAS  | 6         | 6      | 3.51%   |
| NVMe | 2         | 2      | 1.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 133       | 164    | 86.93%  |
| 0.51-1.0   | 18        | 19     | 11.76%  |
| 1.01-2.0   | 2         | 2      | 1.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 58        | 34.73%  |
| 251-500        | 36        | 21.56%  |
| 51-100         | 28        | 16.77%  |
| 21-50          | 20        | 11.98%  |
| 501-1000       | 11        | 6.59%   |
| 1-20           | 9         | 5.39%   |
| 1001-2000      | 2         | 1.2%    |
| More than 3000 | 1         | 0.6%    |
| 2001-3000      | 1         | 0.6%    |
| Unknown        | 1         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 115       | 66.09%  |
| 21-50     | 33        | 18.97%  |
| 51-100    | 14        | 8.05%   |
| 101-250   | 7         | 4.02%   |
| 501-1000  | 3         | 1.72%   |
| 1001-2000 | 1         | 0.57%   |
| Unknown   | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB          | 1         | 1      | 25%     |
| Seagate ST9250315AS 250GB          | 1         | 1      | 25%     |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 25%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 100%    |

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
| Detected | 148       | 192    | 90.24%  |
| Works    | 12        | 13     | 7.32%   |
| Malfunc  | 4         | 4      | 2.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 124       | 80%     |
| AMD                              | 19        | 12.26%  |
| Silicon Integrated Systems [SiS] | 4         | 2.58%   |
| VIA Technologies                 | 3         | 1.94%   |
| Samsung Electronics              | 3         | 1.94%   |
| Nvidia                           | 2         | 1.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 18        | 9.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 17        | 9.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 12        | 6.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 12        | 6.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 11        | 5.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 11        | 5.85%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 10        | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 9         | 4.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 8         | 4.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 6         | 3.19%   |
| Intel 82801FBM (ICH6M) SATA Controller                                       | 6         | 3.19%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 4         | 2.13%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 4         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 4         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                     | 4         | 2.13%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 4         | 2.13%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 4         | 2.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 3         | 1.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 3         | 1.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 1.6%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 2         | 1.06%   |
| VIA VT8237A SATA 2-Port Controller                                           | 2         | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 1.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.06%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 2         | 1.06%   |
| AMD SB600 IDE                                                                | 2         | 1.06%   |
| AMD IXP SB4x0 IDE Controller                                                 | 2         | 1.06%   |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 0.53%   |
| Samsung Electronics SATA controller                                          | 1         | 0.53%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.53%   |
| Nvidia MCP67 IDE Controller                                                  | 1         | 0.53%   |
| Nvidia MCP67 AHCI Controller                                                 | 1         | 0.53%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                            | 1         | 0.53%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                             | 1         | 0.53%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                         | 1         | 0.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 0.53%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                       | 1         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 1         | 0.53%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 1         | 0.53%   |
| AMD FCH SATA Controller [IDE mode]                                           | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 110       | 63.22%  |
| IDE  | 57        | 32.76%  |
| RAID | 5         | 2.87%   |
| NVMe | 2         | 1.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 142       | 86.59%  |
| AMD          | 21        | 12.8%   |
| CentaurHauls | 1         | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 8         | 4.88%   |
| Intel Pentium M processor 1.73GHz           | 6         | 3.66%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 3.66%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 2.44%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.83%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 3         | 1.83%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 3         | 1.83%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 1.83%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.83%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 1.22%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.22%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 1.22%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 1.22%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 1.22%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.22%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.22%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.22%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.22%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.22%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 2         | 1.22%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 2         | 1.22%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 1.22%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 2         | 1.22%   |
| Intel Celeron CPU 925 @ 2.30GHz             | 2         | 1.22%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 1.22%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 1.22%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.22%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 1.22%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.22%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.61%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 1         | 0.61%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 0.61%   |
| Intel Pentium Dual CPU T2410 @ 2.00GHz      | 1         | 0.61%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 0.61%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 1         | 0.61%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.61%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.61%   |
| Intel Genuine CPU T2300 @ 1.66GHz           | 1         | 0.61%   |
| Intel Genuine CPU T1350 @ 1.86GHz           | 1         | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.61%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 0.61%   |
| Intel Core i7-3820QM CPU @ 2.70GHz          | 1         | 0.61%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.61%   |
| Intel Core i7-2720QM CPU @ 2.20GHz          | 1         | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.61%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.61%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 1         | 0.61%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.61%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 1         | 0.61%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 1         | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.61%   |
| Intel Core i5-3340M CPU @ 2.70GHz           | 1         | 0.61%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Atom              | 24        | 14.63%  |
| Intel Celeron           | 21        | 12.8%   |
| Intel Core i7           | 14        | 8.54%   |
| Intel Core i5           | 13        | 7.93%   |
| Intel Core 2 Duo        | 13        | 7.93%   |
| Intel Genuine           | 11        | 6.71%   |
| Intel Core i3           | 10        | 6.1%    |
| Intel Pentium           | 8         | 4.88%   |
| Intel Pentium M         | 7         | 4.27%   |
| Intel Core 2            | 7         | 4.27%   |
| Intel Pentium Dual-Core | 6         | 3.66%   |
| Intel Pentium Dual      | 4         | 2.44%   |
| AMD E                   | 3         | 1.83%   |
| AMD A8                  | 3         | 1.83%   |
| Other                   | 2         | 1.22%   |
| AMD Turion 64 X2 Mobile | 2         | 1.22%   |
| AMD E2                  | 2         | 1.22%   |
| AMD Athlon              | 2         | 1.22%   |
| Intel Core Duo          | 1         | 0.61%   |
| Intel Celeron M         | 1         | 0.61%   |
| Intel Celeron Dual-Core | 1         | 0.61%   |
| CentaurHauls VIA C7     | 1         | 0.61%   |
| AMD Turion 64 Mobile    | 1         | 0.61%   |
| AMD Phenom II           | 1         | 0.61%   |
| AMD E1                  | 1         | 0.61%   |
| AMD C-60                | 1         | 0.61%   |
| AMD Athlon 64 X2        | 1         | 0.61%   |
| AMD A6                  | 1         | 0.61%   |
| AMD A4                  | 1         | 0.61%   |
| AMD A10                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 99        | 60.37%  |
| 1      | 42        | 25.61%  |
| 4      | 23        | 14.02%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 164       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 102       | 62.2%   |
| 2      | 62        | 37.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 127       | 76.97%  |
| 32-bit         | 26        | 15.76%  |
| Unknown        | 12        | 7.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 16        | 9.52%   |
| 0x306a9    | 14        | 8.33%   |
| 0x206a7    | 14        | 8.33%   |
| Unknown    | 14        | 8.33%   |
| 0x6fd      | 12        | 7.14%   |
| 0x106ca    | 12        | 7.14%   |
| 0x106c2    | 9         | 5.36%   |
| 0x6d8      | 7         | 4.17%   |
| 0x6e8      | 5         | 2.98%   |
| 0x30678    | 5         | 2.98%   |
| 0x10661    | 5         | 2.98%   |
| 0x6f6      | 4         | 2.38%   |
| 0x6ec      | 4         | 2.38%   |
| 0x406c4    | 4         | 2.38%   |
| 0x20655    | 4         | 2.38%   |
| 0x806e9    | 3         | 1.79%   |
| 0x40651    | 3         | 1.79%   |
| 0x07030105 | 3         | 1.79%   |
| 0x06006705 | 3         | 1.79%   |
| 0x05000119 | 3         | 1.79%   |
| 0x806ec    | 2         | 1.19%   |
| 0x6f2      | 2         | 1.19%   |
| 0x306d4    | 2         | 1.19%   |
| 0x10676    | 2         | 1.19%   |
| 0x806ea    | 1         | 0.6%    |
| 0x806c1    | 1         | 0.6%    |
| 0x706a8    | 1         | 0.6%    |
| 0x706a1    | 1         | 0.6%    |
| 0x6fb      | 1         | 0.6%    |
| 0x506c9    | 1         | 0.6%    |
| 0x30661    | 1         | 0.6%    |
| 0x20652    | 1         | 0.6%    |
| 0x106e5    | 1         | 0.6%    |
| 0x08200103 | 1         | 0.6%    |
| 0x07030106 | 1         | 0.6%    |
| 0x0700010f | 1         | 0.6%    |
| 0x06006118 | 1         | 0.6%    |
| 0x06001119 | 1         | 0.6%    |
| 0x05000029 | 1         | 0.6%    |
| 0x010000c8 | 1         | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Core          | 26        | 15.85%  |
| Bonnell       | 22        | 13.41%  |
| Penryn        | 18        | 10.98%  |
| P6            | 16        | 9.76%   |
| SandyBridge   | 14        | 8.54%   |
| IvyBridge     | 14        | 8.54%   |
| Silvermont    | 9         | 5.49%   |
| Westmere      | 6         | 3.66%   |
| KabyLake      | 6         | 3.66%   |
| K8 Hammer     | 5         | 3.05%   |
| Puma          | 4         | 2.44%   |
| Excavator     | 4         | 2.44%   |
| Bobcat        | 4         | 2.44%   |
| Haswell       | 3         | 1.83%   |
| Broadwell     | 3         | 1.83%   |
| Goldmont plus | 2         | 1.22%   |
| Zen           | 1         | 0.61%   |
| TigerLake     | 1         | 0.61%   |
| Piledriver    | 1         | 0.61%   |
| Nehalem       | 1         | 0.61%   |
| K10           | 1         | 0.61%   |
| Jaguar        | 1         | 0.61%   |
| Goldmont      | 1         | 0.61%   |
| Unknown       | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 122       | 71.76%  |
| AMD                              | 25        | 14.71%  |
| Nvidia                           | 16        | 9.41%   |
| Silicon Integrated Systems [SiS] | 4         | 2.35%   |
| VIA Technologies                 | 3         | 1.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 22        | 10.68%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 8.25%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 13        | 6.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 6.31%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 5.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 11        | 5.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 4.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 4.85%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 4.37%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 2.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.43%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.94%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.46%   |
| Intel HD Graphics 620                                                                    | 3         | 1.46%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.46%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.46%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.97%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.97%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.97%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.97%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.97%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 0.97%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.97%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.49%   |
| Nvidia GT218M [ION]                                                                      | 1         | 0.49%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.49%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.49%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.49%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.49%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.49%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 1         | 0.49%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.49%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 1         | 0.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 0.49%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.49%   |
| Intel HD Graphics 500                                                                    | 1         | 0.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.49%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1         | 0.49%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 1         | 0.49%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 1         | 0.49%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 1         | 0.49%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 1         | 0.49%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.49%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 1         | 0.49%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 0.49%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 1         | 0.49%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 1         | 0.49%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 0.49%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 1         | 0.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 0.49%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 1         | 0.49%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 1         | 0.49%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 115       | 70.12%  |
| 1 x AMD        | 20        | 12.2%   |
| 1 x Nvidia     | 11        | 6.71%   |
| Intel + Nvidia | 5         | 3.05%   |
| 2 x AMD        | 4         | 2.44%   |
| 1 x SiS        | 4         | 2.44%   |
| 1 x VIA        | 3         | 1.83%   |
| Other          | 1         | 0.61%   |
| Intel + AMD    | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 150       | 90.91%  |
| Unknown     | 11        | 6.67%   |
| Proprietary | 4         | 2.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 119       | 71.69%  |
| 0.01-0.5   | 36        | 21.69%  |
| 0.51-1.0   | 6         | 3.61%   |
| 1.01-2.0   | 3         | 1.81%   |
| 3.01-4.0   | 2         | 1.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 36        | 22.36%  |
| Samsung Electronics     | 27        | 16.77%  |
| LG Display              | 18        | 11.18%  |
| LG Philips              | 13        | 8.07%   |
| Chi Mei Optoelectronics | 10        | 6.21%   |
| HannStar                | 8         | 4.97%   |
| Chimei Innolux          | 6         | 3.73%   |
| Lenovo                  | 4         | 2.48%   |
| CPT                     | 4         | 2.48%   |
| BOE                     | 4         | 2.48%   |
| Sony                    | 3         | 1.86%   |
| InfoVision              | 3         | 1.86%   |
| Dell                    | 3         | 1.86%   |
| Hitachi                 | 2         | 1.24%   |
| Hewlett-Packard         | 2         | 1.24%   |
| BenQ                    | 2         | 1.24%   |
| Apple                   | 2         | 1.24%   |
| Vizio                   | 1         | 0.62%   |
| ViewSonic               | 1         | 0.62%   |
| Seiko/Epson             | 1         | 0.62%   |
| Quanta Display          | 1         | 0.62%   |
| PANDA                   | 1         | 0.62%   |
| Optoma                  | 1         | 0.62%   |
| OEM                     | 1         | 0.62%   |
| LPL                     | 1         | 0.62%   |
| KDC                     | 1         | 0.62%   |
| HKC                     | 1         | 0.62%   |
| Element                 | 1         | 0.62%   |
| CVT                     | 1         | 0.62%   |
| Ancor Communications    | 1         | 0.62%   |
| Acer                    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 3.66%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 1.83%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 2         | 1.22%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 1.22%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 2         | 1.22%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 1.22%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.22%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 1.22%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 1.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 1.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 2         | 1.22%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 1.22%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                        | 1         | 0.61%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 1         | 0.61%   |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                             | 1         | 0.61%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.61%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 0.61%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch      | 1         | 0.61%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC5451 1366x768 344x194mm 15.5-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.61%   |
| Quanta Display LCD Monitor QDS0033 1024x768 304x228mm 15.0-inch          | 1         | 0.61%   |
| PANDA LC133LF1L02 NCP0019 1920x1080 294x165mm 13.3-inch                  | 1         | 0.61%   |
| Optoma WXGA OTM0550 1280x1024                                            | 1         | 0.61%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                          | 1         | 0.61%   |
| LPL LCD Monitor 1440x900                                                 | 1         | 0.61%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 1         | 0.61%   |
| LG Philips LCD Monitor LPLE600 1280x800 331x207mm 15.4-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPLCB00 1280x800 331x207mm 15.4-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPLBB00 1024x768 304x228mm 15.0-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPLB900 1280x800 330x210mm 15.4-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPLA500 1280x800 304x190mm 14.1-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPL2388 1440x900 367x230mm 17.1-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPL0C01 1280x800 304x190mm 14.1-inch              | 1         | 0.61%   |
| LG Philips LCD Monitor LPL0129 1280x800 304x190mm 14.1-inch              | 1         | 0.61%   |
| LG Display LP140WH2-TLA1 LGD0201 1366x768 310x174mm 14.0-inch            | 1         | 0.61%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch             | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 63        | 38.89%  |
| 1280x800 (WXGA)    | 29        | 17.9%   |
| 1920x1080 (FHD)    | 24        | 14.81%  |
| 1024x600           | 14        | 8.64%   |
| 1600x900 (HD+)     | 6         | 3.7%    |
| 1024x768 (XGA)     | 6         | 3.7%    |
| 3840x2160 (4K)     | 3         | 1.85%   |
| 1920x1200 (WUXGA)  | 3         | 1.85%   |
| 1440x900 (WXGA+)   | 3         | 1.85%   |
| 2560x1440 (QHD)    | 2         | 1.23%   |
| 1920x540           | 2         | 1.23%   |
| 1024x576           | 2         | 1.23%   |
| 1680x1050 (WSXGA+) | 1         | 0.62%   |
| 1360x768           | 1         | 0.62%   |
| 1280x960           | 1         | 0.62%   |
| 1280x768           | 1         | 0.62%   |
| 1280x1024 (SXGA)   | 1         | 0.62%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 77        | 47.83%  |
| 14      | 15        | 9.32%   |
| 10      | 14        | 8.7%    |
| 13      | 13        | 8.07%   |
| 11      | 8         | 4.97%   |
| 17      | 7         | 4.35%   |
| 24      | 4         | 2.48%   |
| 84      | 3         | 1.86%   |
| 27      | 3         | 1.86%   |
| 21      | 3         | 1.86%   |
| 12      | 3         | 1.86%   |
| Unknown | 3         | 1.86%   |
| 18      | 2         | 1.24%   |
| 8       | 2         | 1.24%   |
| 39      | 1         | 0.62%   |
| 31      | 1         | 0.62%   |
| 23      | 1         | 0.62%   |
| 22      | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 95        | 59.38%  |
| 201-300     | 32        | 20%     |
| 351-400     | 9         | 5.63%   |
| 501-600     | 8         | 5%      |
| 401-500     | 6         | 3.75%   |
| 1501-2000   | 3         | 1.88%   |
| Unknown     | 3         | 1.88%   |
| 101-200     | 2         | 1.25%   |
| 801-900     | 1         | 0.63%   |
| 601-700     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 108       | 71.52%  |
| 16/10   | 32        | 21.19%  |
| 4/3     | 7         | 4.64%   |
| 5/4     | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 76        | 47.2%   |
| 81-90          | 22        | 13.66%  |
| 41-50          | 14        | 8.7%    |
| 51-60          | 8         | 4.97%   |
| 201-250        | 6         | 3.73%   |
| 71-80          | 5         | 3.11%   |
| 121-130        | 5         | 3.11%   |
| More than 1000 | 3         | 1.86%   |
| 61-70          | 3         | 1.86%   |
| 141-150        | 3         | 1.86%   |
| Unknown        | 3         | 1.86%   |
| 351-500        | 2         | 1.24%   |
| 1-40           | 2         | 1.24%   |
| 301-350        | 2         | 1.24%   |
| 151-200        | 2         | 1.24%   |
| 91-100         | 2         | 1.24%   |
| 251-300        | 1         | 0.62%   |
| 131-140        | 1         | 0.62%   |
| 501-1000       | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 75        | 47.77%  |
| 51-100  | 49        | 31.21%  |
| 121-160 | 27        | 17.2%   |
| 161-240 | 3         | 1.91%   |
| Unknown | 3         | 1.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 140       | 84.34%  |
| 2     | 18        | 10.84%  |
| 0     | 7         | 4.22%   |
| 3     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 79        | 27.15%  |
| Intel                             | 59        | 20.27%  |
| Qualcomm Atheros                  | 52        | 17.87%  |
| Broadcom                          | 44        | 15.12%  |
| Marvell Technology Group          | 15        | 5.15%   |
| Broadcom Limited                  | 11        | 3.78%   |
| Ralink                            | 4         | 1.37%   |
| Silicon Integrated Systems [SiS]  | 3         | 1.03%   |
| VIA Technologies                  | 2         | 0.69%   |
| Samsung Electronics               | 2         | 0.69%   |
| Ralink Technology                 | 2         | 0.69%   |
| JMicron Technology                | 2         | 0.69%   |
| TP-Link                           | 1         | 0.34%   |
| Spreadtrum Communications         | 1         | 0.34%   |
| Nvidia                            | 1         | 0.34%   |
| NetGear                           | 1         | 0.34%   |
| Micro Star International          | 1         | 0.34%   |
| MediaTek                          | 1         | 0.34%   |
| Huawei Technologies               | 1         | 0.34%   |
| Ericsson Business Mobile Networks | 1         | 0.34%   |
| DisplayLink                       | 1         | 0.34%   |
| Dell                              | 1         | 0.34%   |
| BUFFALO                           | 1         | 0.34%   |
| Belkin Components                 | 1         | 0.34%   |
| Attansic Technology               | 1         | 0.34%   |
| ASUSTek Computer                  | 1         | 0.34%   |
| ASIX Electronics                  | 1         | 0.34%   |
| AMD                               | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 8.58%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 28        | 8.28%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 4.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 2.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 8         | 2.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 8         | 2.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 2.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 1.48%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 1.48%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.18%   |
| Intel Wireless 7260                                                     | 4         | 1.18%   |
| Intel Wireless 3165                                                     | 4         | 1.18%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.18%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 1.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3         | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.89%   |
| Intel Wireless 7265                                                     | 3         | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.89%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.89%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.89%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 3         | 0.89%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.59%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.59%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.59%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 2         | 0.59%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                    | 2         | 0.59%   |
| Intel WiFi Link 5100                                                    | 2         | 0.59%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.59%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.59%   |
| Intel 82573L Gigabit Ethernet Controller                                | 2         | 0.59%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                | 2         | 0.59%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 2         | 0.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.59%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                     | 2         | 0.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 57        | 33.33%  |
| Qualcomm Atheros         | 38        | 22.22%  |
| Broadcom                 | 32        | 18.71%  |
| Realtek Semiconductor    | 25        | 14.62%  |
| Broadcom Limited         | 7         | 4.09%   |
| Ralink                   | 4         | 2.34%   |
| Ralink Technology        | 2         | 1.17%   |
| TP-Link                  | 1         | 0.58%   |
| NetGear                  | 1         | 0.58%   |
| Micro Star International | 1         | 0.58%   |
| BUFFALO                  | 1         | 0.58%   |
| Belkin Components        | 1         | 0.58%   |
| ASUSTek Computer         | 1         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 15        | 8.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 14        | 8.14%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 8         | 4.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 7         | 4.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 7         | 4.07%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 6         | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 5         | 2.91%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 5         | 2.91%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 5         | 2.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 4         | 2.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 2.33%   |
| Intel Wireless 7260                                                           | 4         | 2.33%   |
| Intel Wireless 3165                                                           | 4         | 2.33%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 4         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 2.33%   |
| Intel Wireless 7265                                                           | 3         | 1.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 1.74%   |
| Intel Centrino Ultimate-N 6300                                                | 3         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.16%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 2         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 2         | 1.16%   |
| Realtek RTL8187B Wireless Adapter                                             | 2         | 1.16%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 2         | 1.16%   |
| Realtek 802.11ac NIC                                                          | 2         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 2         | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 2         | 1.16%   |
| Intel WiFi Link 5100                                                          | 2         | 1.16%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 2         | 1.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 2         | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 1.16%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                  | 1         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 1         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                         | 1         | 0.58%   |
| Realtek RTL8187 Wireless Adapter                                              | 1         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 1         | 0.58%   |
| Ralink MT7601U Wireless Adapter                                               | 1         | 0.58%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.58%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 1         | 0.58%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)       | 1         | 0.58%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.58%   |
| NetGear A6150                                                                 | 1         | 0.58%   |
| Micro Star International RT2573                                               | 1         | 0.58%   |
| Intel Wireless 8265 / 8275                                                    | 1         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 1         | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 1         | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 1         | 0.58%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 0.58%   |
| Intel Centrino Wireless-N 130                                                 | 1         | 0.58%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 1         | 0.58%   |
| Intel Centrino Advanced-N 6235                                                | 1         | 0.58%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                 | 1         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 69        | 44.23%  |
| Qualcomm Atheros                 | 20        | 12.82%  |
| Intel                            | 16        | 10.26%  |
| Broadcom                         | 16        | 10.26%  |
| Marvell Technology Group         | 15        | 9.62%   |
| Broadcom Limited                 | 5         | 3.21%   |
| Silicon Integrated Systems [SiS] | 3         | 1.92%   |
| VIA Technologies                 | 2         | 1.28%   |
| Samsung Electronics              | 2         | 1.28%   |
| JMicron Technology               | 2         | 1.28%   |
| Spreadtrum Communications        | 1         | 0.64%   |
| Nvidia                           | 1         | 0.64%   |
| MediaTek                         | 1         | 0.64%   |
| DisplayLink                      | 1         | 0.64%   |
| Attansic Technology              | 1         | 0.64%   |
| ASIX Electronics                 | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 18.47%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 28        | 17.83%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 5.1%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 5.1%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 3.18%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 1.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 1.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1.91%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.91%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.27%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.27%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.27%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.27%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller              | 2         | 1.27%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.27%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 1.27%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 1.27%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 1.27%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 1.27%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet               | 2         | 1.27%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.64%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.64%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.64%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.64%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.64%   |
| MediaTek TECNO SPARK 6 Go                                         | 1         | 0.64%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.64%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.64%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.64%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1         | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.64%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.64%   |
| DisplayLink Targus USB3 DV4K DOCK w PD60W                         | 1         | 0.64%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 0.64%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.64%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.64%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.64%   |
| Broadcom Limited NetXtreme BCM5751M Gigabit Ethernet PCI Express  | 1         | 0.64%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.64%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.64%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 50.31%  |
| Ethernet | 151       | 46.89%  |
| Modem    | 9         | 2.8%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 73.33%  |
| Ethernet | 48        | 26.67%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 135       | 82.32%  |
| 1     | 26        | 15.85%  |
| 0     | 2         | 1.22%   |
| 3     | 1         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 154       | 92.77%  |
| Yes  | 12        | 7.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 20        | 25%     |
| Qualcomm Atheros Communications | 8         | 10%     |
| Broadcom                        | 8         | 10%     |
| Realtek Semiconductor           | 6         | 7.5%    |
| Hewlett-Packard                 | 6         | 7.5%    |
| Toshiba                         | 4         | 5%      |
| Lite-On Technology              | 4         | 5%      |
| Foxconn International           | 4         | 5%      |
| Foxconn / Hon Hai               | 4         | 5%      |
| IMC Networks                    | 3         | 3.75%   |
| Cambridge Silicon Radio         | 3         | 3.75%   |
| Ralink                          | 2         | 2.5%    |
| Dell                            | 2         | 2.5%    |
| Apple                           | 2         | 2.5%    |
| Alps Electric                   | 2         | 2.5%    |
| Fujitsu Siemens Computers       | 1         | 1.25%   |
| ASUSTek Computer                | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 15%     |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 7.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 5%      |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 5%      |
| Realtek Bluetooth Radio                             | 3         | 3.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 3.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.75%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 3.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.5%    |
| Ralink RT3290 Bluetooth                             | 2         | 2.5%    |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.5%    |
| Dell DW375 Bluetooth Module                         | 2         | 2.5%    |
| Toshiba RT Bluetooth Radio                          | 1         | 1.25%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.25%   |
| Toshiba Bluetooth Device                            | 1         | 1.25%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.25%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.25%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.25%   |
| Lite-On Bluetooth Device                            | 1         | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.25%   |
| Intel Bluetooth Device                              | 1         | 1.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 1         | 1.25%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.25%   |
| IMC Networks Bluetooth module                       | 1         | 1.25%   |
| IMC Networks Bluetooth Device                       | 1         | 1.25%   |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 1.25%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.25%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.25%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.25%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.25%   |
| Broadcom IBM Integrated Bluetooth IV                | 1         | 1.25%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.25%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.25%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.25%   |
| ASUS Broadcom Bluetooth 2.1                         | 1         | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.25%   |
| Apple Bluetooth HCI                                 | 1         | 1.25%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.25%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 133       | 75.57%  |
| AMD                              | 21        | 11.93%  |
| Nvidia                           | 11        | 6.25%   |
| Silicon Integrated Systems [SiS] | 4         | 2.27%   |
| VIA Technologies                 | 3         | 1.7%    |
| Logitech                         | 2         | 1.14%   |
| Elite Silicon                    | 1         | 0.57%   |
| C-Media Electronics              | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 37        | 18.78%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 10.66%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 8.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 5.58%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 5.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 3.55%   |
| AMD FCH Azalia Controller                                                                         | 7         | 3.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 3.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 3.05%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 2.54%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 2.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 4         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 2.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 2.03%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.52%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.52%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.52%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.52%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.52%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.02%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Logitech Z305                                                                                     | 1         | 0.51%   |
| Logitech Headset H390                                                                             | 1         | 0.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.51%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.51%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.51%   |
| Elite Silicon USB Audio Device                                                                    | 1         | 0.51%   |
| C-Media Electronics CM106 Like Sound Device                                                       | 1         | 0.51%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.51%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.51%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 1         | 0.51%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.51%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 1         | 0.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 12        | 27.91%  |
| Samsung Electronics | 10        | 23.26%  |
| SK hynix            | 6         | 13.95%  |
| Kingston            | 3         | 6.98%   |
| Crucial             | 2         | 4.65%   |
| Corsair             | 2         | 4.65%   |
| Toshiba             | 1         | 2.33%   |
| Smart               | 1         | 2.33%   |
| Ramaxel Technology  | 1         | 2.33%   |
| Micron Technology   | 1         | 2.33%   |
| Infineon            | 1         | 2.33%   |
| Elpida              | 1         | 2.33%   |
| A-DATA Technology   | 1         | 2.33%   |
| 48spaces            | 1         | 2.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 4.26%   |
| Unknown RAM Module SODIMM DDR                                             | 1         | 2.13%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 1         | 2.13%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 2.13%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM DRAM                                     | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                            | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                            | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                            | 1         | 2.13%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                     | 1         | 2.13%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                       | 1         | 2.13%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 1         | 2.13%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                              | 1         | 2.13%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s                     | 1         | 2.13%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s                      | 1         | 2.13%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                      | 1         | 2.13%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                              | 1         | 2.13%   |
| SK hynix RAM Module 512MB DIMM DDR2 533MT/s                               | 1         | 2.13%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 2.13%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 2.13%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                    | 1         | 2.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 1         | 2.13%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s                       | 1         | 2.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 1         | 2.13%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s               | 1         | 2.13%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s                     | 1         | 2.13%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                      | 1         | 2.13%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 1         | 2.13%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.13%   |
| Kingston RAM KX830D-ELC 4096MB SODIMM DDR3 1333MT/s                       | 1         | 2.13%   |
| Kingston RAM ASU1333S9-4G-ECEWG 4GB SODIMM DDR3 1333MT/s                  | 1         | 2.13%   |
| Kingston RAM 9905428-196.A00LF 8192MB SODIMM DDR3 1333MT/s                | 1         | 2.13%   |
| Infineon RAM Module 256MB DIMM DDR2 533MT/s                               | 1         | 2.13%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s                     | 1         | 2.13%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s                | 1         | 2.13%   |
| Crucial RAM CT102464BF1339.C16 8GB SODIMM DDR3 1333MT/s                   | 1         | 2.13%   |
| Corsair RAM CMSX8GX3M1A1600C10 8192MB SODIMM DDR3 1600MT/s                | 1         | 2.13%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s                    | 1         | 2.13%   |
| Corsair RAM CM3X4GSD1066 4GB SODIMM 1067MT/s                              | 1         | 2.13%   |
| A-DATA RAM AM1U16BC4P2-B19H 4096MB SODIMM DDR3 1600MT/s                   | 1         | 2.13%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 1         | 2.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 27        | 65.85%  |
| DDR2  | 5         | 12.2%   |
| SDRAM | 3         | 7.32%   |
| DDR   | 3         | 7.32%   |
| DDR4  | 2         | 4.88%   |
| DRAM  | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 92.68%  |
| Row Of Chips | 1         | 2.44%   |
| DIMM         | 1         | 2.44%   |
| Chip         | 1         | 2.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 18        | 40.91%  |
| 2048    | 13        | 29.55%  |
| 8192    | 6         | 13.64%  |
| 1024    | 3         | 6.82%   |
| 512     | 2         | 4.55%   |
| 256     | 1         | 2.27%   |
| Unknown | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 16        | 36.36%  |
| Unknown | 8         | 18.18%  |
| 1333    | 6         | 13.64%  |
| 1334    | 3         | 6.82%   |
| 1066    | 2         | 4.55%   |
| 667     | 2         | 4.55%   |
| 3200    | 1         | 2.27%   |
| 2400    | 1         | 2.27%   |
| 2048    | 1         | 2.27%   |
| 1067    | 1         | 2.27%   |
| 800     | 1         | 2.27%   |
| 533     | 1         | 2.27%   |
| 100     | 1         | 2.27%   |

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
| Chicony Electronics                    | 34        | 27.64%  |
| Suyin                                  | 11        | 8.94%   |
| Realtek Semiconductor                  | 10        | 8.13%   |
| IMC Networks                           | 10        | 8.13%   |
| Acer                                   | 10        | 8.13%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.69%   |
| Z-Star Microelectronics                | 6         | 4.88%   |
| Ricoh                                  | 6         | 4.88%   |
| Microdia                               | 6         | 4.88%   |
| Sunplus Innovation Technology          | 4         | 3.25%   |
| Syntek                                 | 3         | 2.44%   |
| Silicon Motion                         | 3         | 2.44%   |
| Importek                               | 3         | 2.44%   |
| ALi                                    | 3         | 2.44%   |
| Samsung Electronics                    | 1         | 0.81%   |
| OmniVision Technologies                | 1         | 0.81%   |
| Lite-On Technology                     | 1         | 0.81%   |
| Lenovo                                 | 1         | 0.81%   |
| DigiTech                               | 1         | 0.81%   |
| Apple                                  | 1         | 0.81%   |
| Alcor Micro                            | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                               | 4         | 3.25%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 4         | 3.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 4         | 3.25%   |
| IMC Networks UVC VGA Webcam                                 | 3         | 2.44%   |
| Chicony USB 2.0 Camera                                      | 3         | 2.44%   |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 2.44%   |
| Acer Lenovo Integrated Webcam                               | 3         | 2.44%   |
| Ricoh Sony Vaio Integrated Webcam                           | 2         | 1.63%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.63%   |
| Realtek Lenovo EasyCamera                                   | 2         | 1.63%   |
| Realtek Integrated Webcam                                   | 2         | 1.63%   |
| Microdia Sonix USB 2.0 Camera                               | 2         | 1.63%   |
| Importek HP Webcam-50                                       | 2         | 1.63%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 2         | 1.63%   |
| IMC Networks Integrated Webcam                              | 2         | 1.63%   |
| Chicony VGA Webcam                                          | 2         | 1.63%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.63%   |
| Chicony Lenovo EasyCamera                                   | 2         | 1.63%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 2         | 1.63%   |
| Acer Integrated Camera                                      | 2         | 1.63%   |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 0.81%   |
| Z-Star Sirius USB2.0 Camera                                 | 1         | 0.81%   |
| Syntek USB Camera Device                                    | 1         | 0.81%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.81%   |
| Syntek Integrated Webcam                                    | 1         | 0.81%   |
| Suyin HP Webcam 101                                         | 1         | 0.81%   |
| Suyin HP Webcam                                             | 1         | 0.81%   |
| Suyin HP Truevision HD                                      | 1         | 0.81%   |
| Suyin HD Video WebCam                                       | 1         | 0.81%   |
| Suyin Acer OrbiCam                                          | 1         | 0.81%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.81%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.81%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.81%   |
| Sunplus HP TrueVision HD Camera                             | 1         | 0.81%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.81%   |
| Sunplus Asus Webcam                                         | 1         | 0.81%   |
| Silicon Motion WebCam SC-0311139N                           | 1         | 0.81%   |
| Silicon Motion HP Webcam                                    | 1         | 0.81%   |
| Silicon Motion 300k Pixel Camera                            | 1         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.81%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 0.81%   |
| Ricoh Integrated Webcam                                     | 1         | 0.81%   |
| Realtek USB2.0 camera                                       | 1         | 0.81%   |
| Realtek USB Camera                                          | 1         | 0.81%   |
| Realtek Integrated_Webcam_HD                                | 1         | 0.81%   |
| Realtek HP Truevision HD integrated webcam                  | 1         | 0.81%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.81%   |
| Realtek HD WebCam                                           | 1         | 0.81%   |
| OmniVision OV2640 Webcam                                    | 1         | 0.81%   |
| Microdia Laptop_Integrated_Webcam_0.3M                      | 1         | 0.81%   |
| Microdia Integrated_Webcam_1.3M                             | 1         | 0.81%   |
| Microdia Integrated Webcam                                  | 1         | 0.81%   |
| Microdia 1.3 MPixel Integrated Webcam                       | 1         | 0.81%   |
| Lite-On TOSHIBA Web Camera                                  | 1         | 0.81%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 0.81%   |
| Importek Webcam-101                                         | 1         | 0.81%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 1         | 0.81%   |
| IMC Networks USB2.0 UVC 2M WebCam                           | 1         | 0.81%   |
| IMC Networks TOSHIBA Web Camera - HD                        | 1         | 0.81%   |
| DigiTech USB 2.0 PC Camera                                  | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 33.33%  |
| AuthenTec             | 5         | 27.78%  |
| STMicroelectronics    | 4         | 22.22%  |
| Upek                  | 1         | 5.56%   |
| Synaptics             | 1         | 5.56%   |
| LighTuning Technology | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                                      | 4         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 5.56%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 5.56%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 5.56%   |
| AuthenTec AES2810                                                          | 1         | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 5.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 5.56%   |
| AuthenTec AES1600                                                          | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 4         | 50%     |
| Broadcom    | 3         | 37.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 107       | 64.46%  |
| 1     | 46        | 27.71%  |
| 2     | 12        | 7.23%   |
| 4     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 23.29%  |
| Net/wireless             | 12        | 16.44%  |
| Graphics card            | 12        | 16.44%  |
| Chipcard                 | 8         | 10.96%  |
| Storage                  | 6         | 8.22%   |
| Modem                    | 5         | 6.85%   |
| Bluetooth                | 3         | 4.11%   |
| Flash memory             | 2         | 2.74%   |
| Communication controller | 2         | 2.74%   |
| Camera                   | 2         | 2.74%   |
| Storage/raid             | 1         | 1.37%   |
| Storage/ide              | 1         | 1.37%   |
| Sound                    | 1         | 1.37%   |
| Multimedia controller    | 1         | 1.37%   |

