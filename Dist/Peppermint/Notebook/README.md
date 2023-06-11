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

Total: 276

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | E1-510                      | [709c32e016](https://linux-hardware.org/?probe=709c32e016) | May 21, 2023 |
| Acer          | E1-510                      | [c18f4ac56b](https://linux-hardware.org/?probe=c18f4ac56b) | May 21, 2023 |
| Google        | Banon                       | [c693655850](https://linux-hardware.org/?probe=c693655850) | Apr 04, 2023 |
| Google        | Kefka                       | [4817109a3d](https://linux-hardware.org/?probe=4817109a3d) | Mar 12, 2023 |
| ASUSTek       | X510UAR                     | [7996de313e](https://linux-hardware.org/?probe=7996de313e) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [3f4e15d14a](https://linux-hardware.org/?probe=3f4e15d14a) | Jan 25, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | [d2ee3f78a9](https://linux-hardware.org/?probe=d2ee3f78a9) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | [9c9801b860](https://linux-hardware.org/?probe=9c9801b860) | Jan 06, 2023 |
| Acer          | AOA110                      | [560aa745c1](https://linux-hardware.org/?probe=560aa745c1) | Dec 14, 2022 |
| Lenovo        | 40684WG                     | [27e2eeccbf](https://linux-hardware.org/?probe=27e2eeccbf) | Nov 25, 2022 |
| Samsung       | SR70S/SR71S                 | [2e1f6c73da](https://linux-hardware.org/?probe=2e1f6c73da) | Nov 22, 2022 |
| HP            | Laptop 15-bs2xx             | [7c94d16c1c](https://linux-hardware.org/?probe=7c94d16c1c) | Oct 31, 2022 |
| Lenovo        | ThinkPad X230 232465G       | [4cfe90552b](https://linux-hardware.org/?probe=4cfe90552b) | Oct 24, 2022 |
| Google        | Swanky                      | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Lenovo        | ThinkPad T60 1952CTO        | [f84f14587b](https://linux-hardware.org/?probe=f84f14587b) | Oct 17, 2022 |
| HP            | Compaq Presario CQ60        | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| Google        | Banon                       | [a54fd2e29b](https://linux-hardware.org/?probe=a54fd2e29b) | Sep 04, 2022 |
| Acer          | Aspire M5-581TG             | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| HP            | Compaq 2510p                | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Dell          | Latitude E6430              | [c6f235793c](https://linux-hardware.org/?probe=c6f235793c) | Jul 25, 2022 |
| Dell          | Inspiron 1545               | [893377b9f7](https://linux-hardware.org/?probe=893377b9f7) | Jul 23, 2022 |
| GPU Compan... | GWTC116-2                   | [e67924ef34](https://linux-hardware.org/?probe=e67924ef34) | Jul 19, 2022 |
| GPU Compan... | GWTC116-2                   | [33266494dc](https://linux-hardware.org/?probe=33266494dc) | Jul 19, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [7177bb644a](https://linux-hardware.org/?probe=7177bb644a) | Jul 15, 2022 |
| Acer          | Aspire R3-131T              | [36851c847b](https://linux-hardware.org/?probe=36851c847b) | Jul 08, 2022 |
| Sony          | VPCEA36FM                   | [3e993cbd4b](https://linux-hardware.org/?probe=3e993cbd4b) | Jul 06, 2022 |
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
| Peppermint 10   | 147       | 79.46%  |
| Peppermint 9    | 16        | 8.65%   |
| Peppermint 11.4 | 4         | 2.16%   |
| Peppermint 11.3 | 4         | 2.16%   |
| Peppermint 11.1 | 4         | 2.16%   |
| Peppermint      | 4         | 2.16%   |
| Peppermint 11.5 | 2         | 1.08%   |
| Peppermint 11.2 | 2         | 1.08%   |
| Peppermint 8    | 1         | 0.54%   |
| Peppermint 11.7 | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Peppermint | 185       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.0.0-37-generic  | 24        | 11.71%  |
| 5.4.0-42-generic  | 7         | 3.41%   |
| 5.3.0-62-generic  | 7         | 3.41%   |
| 5.3.0-51-generic  | 7         | 3.41%   |
| 4.18.0-18-generic | 7         | 3.41%   |
| 5.4.0-65-generic  | 6         | 2.93%   |
| 4.15.0-43-generic | 6         | 2.93%   |
| 5.10.0-14-amd64   | 5         | 2.44%   |
| 5.4.0-91-generic  | 4         | 1.95%   |
| 5.4.0-72-generic  | 4         | 1.95%   |
| 5.4.0-58-generic  | 4         | 1.95%   |
| 5.10.0-19-amd64   | 4         | 1.95%   |
| 5.0.0-32-generic  | 4         | 1.95%   |
| 5.4.0-90-generic  | 3         | 1.46%   |
| 5.4.0-87-generic  | 3         | 1.46%   |
| 5.4.0-80-generic  | 3         | 1.46%   |
| 5.4.0-77-generic  | 3         | 1.46%   |
| 5.4.0-66-generic  | 3         | 1.46%   |
| 5.4.0-47-generic  | 3         | 1.46%   |
| 5.4.0-45-generic  | 3         | 1.46%   |
| 5.3.0-46-generic  | 3         | 1.46%   |
| 5.3.0-42-generic  | 3         | 1.46%   |
| 5.3.0-28-generic  | 3         | 1.46%   |
| 5.10.0-16-amd64   | 3         | 1.46%   |
| 5.0.0-36-generic  | 3         | 1.46%   |
| 4.15.0-48-generic | 3         | 1.46%   |
| 4.15.0-47-generic | 3         | 1.46%   |
| 5.4.0-97-generic  | 2         | 0.98%   |
| 5.4.0-84-generic  | 2         | 0.98%   |
| 5.4.0-81-generic  | 2         | 0.98%   |
| 5.4.0-74-generic  | 2         | 0.98%   |
| 5.4.0-70-generic  | 2         | 0.98%   |
| 5.4.0-67-generic  | 2         | 0.98%   |
| 5.4.0-56-generic  | 2         | 0.98%   |
| 5.4.0-54-generic  | 2         | 0.98%   |
| 5.4.0-52-generic  | 2         | 0.98%   |
| 5.4.0-48-generic  | 2         | 0.98%   |
| 5.3.0-59-generic  | 2         | 0.98%   |
| 5.3.0-40-generic  | 2         | 0.98%   |
| 5.10.0-20-amd64   | 2         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 81        | 41.97%  |
| 5.0.0   | 32        | 16.58%  |
| 5.3.0   | 27        | 13.99%  |
| 5.10.0  | 20        | 10.36%  |
| 4.15.0  | 15        | 7.77%   |
| 4.18.0  | 13        | 6.74%   |
| 5.4.95  | 1         | 0.52%   |
| 5.3.6   | 1         | 0.52%   |
| 5.18.0  | 1         | 0.52%   |
| 5.1.11  | 1         | 0.52%   |
| 4.8.0   | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 82        | 42.49%  |
| 5.0     | 32        | 16.58%  |
| 5.3     | 28        | 14.51%  |
| 5.10    | 20        | 10.36%  |
| 4.15    | 15        | 7.77%   |
| 4.18    | 13        | 6.74%   |
| 5.18    | 1         | 0.52%   |
| 5.1     | 1         | 0.52%   |
| 4.8     | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 122       | 65.95%  |
| i686   | 63        | 34.05%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXDE       | 126       | 66.67%  |
| Unknown    | 33        | 17.46%  |
| XFCE       | 20        | 10.58%  |
| GNOME      | 7         | 3.7%    |
| X-Cinnamon | 1         | 0.53%   |
| Peppermint | 1         | 0.53%   |
| Cinnamon   | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 185       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 149       | 80.11%  |
| LightDM | 29        | 15.59%  |
| TDM     | 7         | 3.76%   |
| SDDM    | 1         | 0.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 60        | 31.91%  |
| Unknown | 27        | 14.36%  |
| en_GB   | 13        | 6.91%   |
| de_DE   | 12        | 6.38%   |
| it_IT   | 9         | 4.79%   |
| pt_BR   | 8         | 4.26%   |
| pl_PL   | 7         | 3.72%   |
| nl_NL   | 5         | 2.66%   |
| C       | 5         | 2.66%   |
| fr_FR   | 4         | 2.13%   |
| en_CA   | 4         | 2.13%   |
| ru_RU   | 3         | 1.6%    |
| es_AR   | 3         | 1.6%    |
| ro_RO   | 2         | 1.06%   |
| ja_JP   | 2         | 1.06%   |
| fi_FI   | 2         | 1.06%   |
| es_MX   | 2         | 1.06%   |
| en_NZ   | 2         | 1.06%   |
| en_IN   | 2         | 1.06%   |
| en_AU   | 2         | 1.06%   |
| tr_TR   | 1         | 0.53%   |
| sv_SE   | 1         | 0.53%   |
| pt_PT   | 1         | 0.53%   |
| nl_BE   | 1         | 0.53%   |
| lv_LV   | 1         | 0.53%   |
| es_PE   | 1         | 0.53%   |
| es_PA   | 1         | 0.53%   |
| es_ES   | 1         | 0.53%   |
| es_CR   | 1         | 0.53%   |
| es_BO   | 1         | 0.53%   |
| en_ZA   | 1         | 0.53%   |
| en_PH   | 1         | 0.53%   |
| el_GR   | 1         | 0.53%   |
| cs_CZ   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 141       | 76.22%  |
| EFI  | 44        | 23.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 155       | 82.89%  |
| Unknown  | 16        | 8.56%   |
| Overlay  | 8         | 4.28%   |
| Ext3     | 3         | 1.6%    |
| Ext2     | 2         | 1.07%   |
| Reiserfs | 1         | 0.53%   |
| Btrfs    | 1         | 0.53%   |
| Aufs     | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 155       | 83.33%  |
| GPT     | 17        | 9.14%   |
| MBR     | 14        | 7.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 177       | 94.65%  |
| Yes       | 10        | 5.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 88.3%   |
| Yes       | 22        | 11.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 38        | 20.54%  |
| Lenovo              | 24        | 12.97%  |
| Dell                | 22        | 11.89%  |
| ASUSTek Computer    | 18        | 9.73%   |
| Toshiba             | 16        | 8.65%   |
| Acer                | 16        | 8.65%   |
| Samsung Electronics | 8         | 4.32%   |
| Sony                | 6         | 3.24%   |
| Google              | 5         | 2.7%    |
| Fujitsu Siemens     | 5         | 2.7%    |
| Positivo            | 3         | 1.62%   |
| eMachines           | 3         | 1.62%   |
| Packard Bell        | 2         | 1.08%   |
| Medion              | 2         | 1.08%   |
| IBM                 | 2         | 1.08%   |
| Gateway             | 2         | 1.08%   |
| Clevo               | 2         | 1.08%   |
| Apple               | 2         | 1.08%   |
| Unknown             | 2         | 1.08%   |
| WinBook             | 1         | 0.54%   |
| Olivetti            | 1         | 0.54%   |
| LincPlus            | 1         | 0.54%   |
| JPSaCouto           | 1         | 0.54%   |
| Itautec             | 1         | 0.54%   |
| GPU Company         | 1         | 0.54%   |
| Fujitsu             | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo G500 20236                           | 3         | 1.62%   |
| Toshiba Satellite M70                       | 2         | 1.08%   |
| Toshiba Satellite L500                      | 2         | 1.08%   |
| Samsung N150P/N210P/N220P                   | 2         | 1.08%   |
| Positivo Mobile                             | 2         | 1.08%   |
| Google Banon                                | 2         | 1.08%   |
| Fujitsu Siemens ESPRIMO Mobile V5535        | 2         | 1.08%   |
| Dell Latitude D630                          | 2         | 1.08%   |
| Dell Inspiron N5050                         | 2         | 1.08%   |
| Dell Inspiron 1545                          | 2         | 1.08%   |
| Acer Extensa 5630                           | 2         | 1.08%   |
| Unknown                                     | 2         | 1.08%   |
| WinBook GL Series                           | 1         | 0.54%   |
| Toshiba Satellite Pro C850                  | 1         | 0.54%   |
| Toshiba Satellite L750D                     | 1         | 0.54%   |
| Toshiba Satellite L310                      | 1         | 0.54%   |
| Toshiba Satellite L300                      | 1         | 0.54%   |
| Toshiba Satellite C850-F117                 | 1         | 0.54%   |
| Toshiba Satellite C660                      | 1         | 0.54%   |
| Toshiba Satellite C55D-B                    | 1         | 0.54%   |
| Toshiba QOSMIO F755                         | 1         | 0.54%   |
| Toshiba PORTEGE R500                        | 1         | 0.54%   |
| Toshiba NB520                               | 1         | 0.54%   |
| Toshiba NB500                               | 1         | 0.54%   |
| Toshiba dynabook Satellite B552/H           | 1         | 0.54%   |
| Sony VPCZ21V9E                              | 1         | 0.54%   |
| Sony VPCEA36FM                              | 1         | 0.54%   |
| Sony VPCCW21FX                              | 1         | 0.54%   |
| Sony VGN-S55B_S                             | 1         | 0.54%   |
| Sony VGN-FW140E                             | 1         | 0.54%   |
| Sony VGN-CR21S_P                            | 1         | 0.54%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.54%   |
| Samsung R610                                | 1         | 0.54%   |
| Samsung R530/R730/R540                      | 1         | 0.54%   |
| Samsung N150P                               | 1         | 0.54%   |
| Samsung N150/N210/N220                      | 1         | 0.54%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA  | 1         | 0.54%   |
| Positivo N1103                              | 1         | 0.54%   |
| Packard Bell EasyNote_MX45                  | 1         | 0.54%   |
| Packard Bell EasyNote TK85                  | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Dell Inspiron           | 12        | 6.49%   |
| Toshiba Satellite       | 11        | 5.95%   |
| Lenovo ThinkPad         | 11        | 5.95%   |
| HP Pavilion             | 9         | 4.86%   |
| HP Compaq               | 8         | 4.32%   |
| Dell Latitude           | 7         | 3.78%   |
| Acer Aspire             | 7         | 3.78%   |
| HP EliteBook            | 6         | 3.24%   |
| HP Laptop               | 4         | 2.16%   |
| Acer Extensa            | 4         | 2.16%   |
| Samsung N150P           | 3         | 1.62%   |
| Lenovo IdeaPad          | 3         | 1.62%   |
| Lenovo G500             | 3         | 1.62%   |
| Fujitsu Siemens AMILO   | 3         | 1.62%   |
| Positivo Mobile         | 2         | 1.08%   |
| Packard Bell EasyNote   | 2         | 1.08%   |
| IBM ThinkPad            | 2         | 1.08%   |
| HP Stream               | 2         | 1.08%   |
| HP Mini                 | 2         | 1.08%   |
| HP 255                  | 2         | 1.08%   |
| Google Banon            | 2         | 1.08%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.08%   |
| Dell Precision          | 2         | 1.08%   |
| Unknown                 | 2         | 1.08%   |
| WinBook GL              | 1         | 0.54%   |
| Toshiba QOSMIO          | 1         | 0.54%   |
| Toshiba PORTEGE         | 1         | 0.54%   |
| Toshiba NB520           | 1         | 0.54%   |
| Toshiba NB500           | 1         | 0.54%   |
| Toshiba dynabook        | 1         | 0.54%   |
| Sony VPCZ21V9E          | 1         | 0.54%   |
| Sony VPCEA36FM          | 1         | 0.54%   |
| Sony VPCCW21FX          | 1         | 0.54%   |
| Sony VGN-S55B           | 1         | 0.54%   |
| Sony VGN-FW140E         | 1         | 0.54%   |
| Sony VGN-CR21S          | 1         | 0.54%   |
| Samsung RV411           | 1         | 0.54%   |
| Samsung R610            | 1         | 0.54%   |
| Samsung R530            | 1         | 0.54%   |
| Samsung N150            | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2008    | 29        | 15.68%  |
| 2011    | 20        | 10.81%  |
| 2010    | 17        | 9.19%   |
| 2009    | 17        | 9.19%   |
| 2007    | 16        | 8.65%   |
| 2012    | 15        | 8.11%   |
| 2006    | 14        | 7.57%   |
| 2013    | 12        | 6.49%   |
| 2018    | 6         | 3.24%   |
| 2016    | 6         | 3.24%   |
| 2015    | 6         | 3.24%   |
| 2014    | 5         | 2.7%    |
| 2005    | 5         | 2.7%    |
| 2020    | 4         | 2.16%   |
| 2017    | 4         | 2.16%   |
| 2019    | 3         | 1.62%   |
| 2023    | 2         | 1.08%   |
| 2022    | 2         | 1.08%   |
| 2021    | 1         | 0.54%   |
| Unknown | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 185       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 177       | 95.68%  |
| Enabled  | 8         | 4.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 179       | 96.76%  |
| Yes  | 6         | 3.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 55        | 29.41%  |
| 1.01-2.0   | 51        | 27.27%  |
| 4.01-8.0   | 29        | 15.51%  |
| 0.51-1.0   | 18        | 9.63%   |
| 2.01-3.0   | 15        | 8.02%   |
| 8.01-16.0  | 12        | 6.42%   |
| 16.01-24.0 | 5         | 2.67%   |
| 32.01-64.0 | 1         | 0.53%   |
| 0.01-0.5   | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.51-1.0 | 75        | 36.95%  |
| 1.01-2.0 | 72        | 35.47%  |
| 2.01-3.0 | 30        | 14.78%  |
| 0.01-0.5 | 18        | 8.87%   |
| 3.01-4.0 | 5         | 2.46%   |
| 4.01-8.0 | 3         | 1.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 77.25%  |
| 2      | 36        | 19.05%  |
| 3      | 4         | 2.12%   |
| 0      | 3         | 1.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 56.99%  |
| No        | 80        | 43.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 89.73%  |
| No        | 19        | 10.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 98.38%  |
| No        | 3         | 1.62%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 50%     |
| No        | 93        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 47        | 25.41%  |
| Germany      | 18        | 9.73%   |
| UK           | 12        | 6.49%   |
| Italy        | 11        | 5.95%   |
| Netherlands  | 9         | 4.86%   |
| Canada       | 9         | 4.86%   |
| Brazil       | 8         | 4.32%   |
| Poland       | 7         | 3.78%   |
| France       | 6         | 3.24%   |
| Sweden       | 4         | 2.16%   |
| Russia       | 4         | 2.16%   |
| Romania      | 4         | 2.16%   |
| Spain        | 3         | 1.62%   |
| Mexico       | 3         | 1.62%   |
| Japan        | 3         | 1.62%   |
| Argentina    | 3         | 1.62%   |
| Portugal     | 2         | 1.08%   |
| New Zealand  | 2         | 1.08%   |
| India        | 2         | 1.08%   |
| Greece       | 2         | 1.08%   |
| Finland      | 2         | 1.08%   |
| Bolivia      | 2         | 1.08%   |
| Turkey       | 1         | 0.54%   |
| Switzerland  | 1         | 0.54%   |
| South Africa | 1         | 0.54%   |
| Serbia       | 1         | 0.54%   |
| Puerto Rico  | 1         | 0.54%   |
| Philippines  | 1         | 0.54%   |
| Peru         | 1         | 0.54%   |
| Panama       | 1         | 0.54%   |
| Norway       | 1         | 0.54%   |
| Namibia      | 1         | 0.54%   |
| Malaysia     | 1         | 0.54%   |
| Lithuania    | 1         | 0.54%   |
| Latvia       | 1         | 0.54%   |
| Kazakhstan   | 1         | 0.54%   |
| Ireland      | 1         | 0.54%   |
| Georgia      | 1         | 0.54%   |
| Czechia      | 1         | 0.54%   |
| Costa Rica   | 1         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Toronto                | 4         | 2.07%   |
| Warsaw                 | 2         | 1.04%   |
| Turin                  | 2         | 1.04%   |
| Topeka                 | 2         | 1.04%   |
| Tokyo                  | 2         | 1.04%   |
| Osasco                 | 2         | 1.04%   |
| Naples                 | 2         | 1.04%   |
| Moscow                 | 2         | 1.04%   |
| Fayetteville           | 2         | 1.04%   |
| Bucharest              | 2         | 1.04%   |
| Zgierz                 | 1         | 0.52%   |
| York                   | 1         | 0.52%   |
| Yokohama               | 1         | 0.52%   |
| Wysokie Mazowieckie    | 1         | 0.52%   |
| Worthing               | 1         | 0.52%   |
| Windhoek               | 1         | 0.52%   |
| West New York          | 1         | 0.52%   |
| West Chester           | 1         | 0.52%   |
| Weissenfels            | 1         | 0.52%   |
| Weinheim               | 1         | 0.52%   |
| Waalwijk               | 1         | 0.52%   |
| Volos                  | 1         | 0.52%   |
| Villa María           | 1         | 0.52%   |
| Vijayawada             | 1         | 0.52%   |
| Venda do Pinheiro      | 1         | 0.52%   |
| Varna                  | 1         | 0.52%   |
| Umeå                  | 1         | 0.52%   |
| Uddingston             | 1         | 0.52%   |
| Tucson                 | 1         | 0.52%   |
| Trofarello             | 1         | 0.52%   |
| Trento                 | 1         | 0.52%   |
| Telford                | 1         | 0.52%   |
| Tauranga               | 1         | 0.52%   |
| Tampere                | 1         | 0.52%   |
| Tahlequah              | 1         | 0.52%   |
| Stockton               | 1         | 0.52%   |
| Staffanstorp           | 1         | 0.52%   |
| Southampton            | 1         | 0.52%   |
| Siemianowice Śląskie | 1         | 0.52%   |
| Sicklerville           | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 43     | 20.5%   |
| WDC                 | 34        | 39     | 17%     |
| Unknown             | 22        | 27     | 11%     |
| Toshiba             | 19        | 20     | 9.5%    |
| Samsung Electronics | 19        | 29     | 9.5%    |
| Hitachi             | 15        | 18     | 7.5%    |
| Kingston            | 8         | 10     | 4%      |
| SanDisk             | 5         | 6      | 2.5%    |
| HGST                | 5         | 6      | 2.5%    |
| Fujitsu             | 5         | 6      | 2.5%    |
| PNY                 | 2         | 2      | 1%      |
| Micron Technology   | 2         | 2      | 1%      |
| Intenso             | 2         | 2      | 1%      |
| Integral            | 2         | 2      | 1%      |
| GOODRAM             | 2         | 2      | 1%      |
| China               | 2         | 2      | 1%      |
| Zheino              | 1         | 1      | 0.5%    |
| TrekStor            | 1         | 1      | 0.5%    |
| TCSUNBOW            | 1         | 1      | 0.5%    |
| SK hynix            | 1         | 1      | 0.5%    |
| SABRENT             | 1         | 1      | 0.5%    |
| Patriot             | 1         | 1      | 0.5%    |
| LITEONIT            | 1         | 1      | 0.5%    |
| KingSpec            | 1         | 1      | 0.5%    |
| Intel               | 1         | 2      | 0.5%    |
| FATTYDOVE           | 1         | 1      | 0.5%    |
| Drevo               | 1         | 1      | 0.5%    |
| Crucial             | 1         | 1      | 0.5%    |
| BHT                 | 1         | 2      | 0.5%    |
| Apple               | 1         | 1      | 0.5%    |
| Apacer              | 1         | 3      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 6         | 2.94%   |
| Seagate ST9500325AS 500GB           | 4         | 1.96%   |
| Seagate ST9250315AS 250GB           | 4         | 1.96%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 1.96%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 1.96%   |
| Seagate ST9320325AS 320GB           | 3         | 1.47%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.98%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 0.98%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.98%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.98%   |
| Unknown SD/MMC/MS PRO 64GB          | 2         | 0.98%   |
| Unknown MMC Card  64GB              | 2         | 0.98%   |
| Unknown MMC Card  2GB               | 2         | 0.98%   |
| Unknown MMC Card  16GB              | 2         | 0.98%   |
| Toshiba MK5055GSX 500GB             | 2         | 0.98%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.98%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.98%   |
| Samsung HM160HI 160GB               | 2         | 0.98%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.98%   |
| Kingston SA400S37120G 120GB SSD     | 2         | 0.98%   |
| Hitachi HTS545025B9A300 250GB       | 2         | 0.98%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.98%   |
| Zheino CHN 25SATAA3 120 120GB SSD   | 1         | 0.49%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 1         | 0.49%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.49%   |
| WDC WD800BEVS-60LAT0 80GB           | 1         | 0.49%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.49%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.49%   |
| WDC WD5000BPVT-00HXZT3 500GB        | 1         | 0.49%   |
| WDC WD5000BEVT-55A0RT0 500GB        | 1         | 0.49%   |
| WDC WD3200BPVT-08JJ5T0 320GB        | 1         | 0.49%   |
| WDC WD3200BEVT-75ZCT2 320GB         | 1         | 0.49%   |
| WDC WD2500BPVT-24ZEST0 250GB        | 1         | 0.49%   |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 0.49%   |
| WDC WD2500BEVT-35A23T0 250GB        | 1         | 0.49%   |
| WDC WD2500BEVS-00UST0 250GB         | 1         | 0.49%   |
| WDC WD2500BEKT-66F3T2 250GB         | 1         | 0.49%   |
| WDC WD1600BEVT-60ZCT1 160GB         | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 42     | 32%     |
| WDC                 | 32        | 37     | 25.6%   |
| Toshiba             | 18        | 19     | 14.4%   |
| Hitachi             | 15        | 18     | 12%     |
| Samsung Electronics | 8         | 8      | 6.4%    |
| HGST                | 5         | 6      | 4%      |
| Fujitsu             | 5         | 6      | 4%      |
| Unknown             | 2         | 2      | 1.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 19     | 20.41%  |
| Kingston            | 8         | 10     | 16.33%  |
| SanDisk             | 4         | 5      | 8.16%   |
| WDC                 | 2         | 2      | 4.08%   |
| PNY                 | 2         | 2      | 4.08%   |
| Intenso             | 2         | 2      | 4.08%   |
| Integral            | 2         | 2      | 4.08%   |
| GOODRAM             | 2         | 2      | 4.08%   |
| China               | 2         | 2      | 4.08%   |
| Zheino              | 1         | 1      | 2.04%   |
| TrekStor            | 1         | 1      | 2.04%   |
| Toshiba             | 1         | 1      | 2.04%   |
| TCSUNBOW            | 1         | 1      | 2.04%   |
| Patriot             | 1         | 1      | 2.04%   |
| Micron Technology   | 1         | 1      | 2.04%   |
| LITEONIT            | 1         | 1      | 2.04%   |
| KingSpec            | 1         | 1      | 2.04%   |
| Intel               | 1         | 2      | 2.04%   |
| FATTYDOVE           | 1         | 1      | 2.04%   |
| Drevo               | 1         | 1      | 2.04%   |
| Crucial             | 1         | 1      | 2.04%   |
| BHT                 | 1         | 2      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |
| Apacer              | 1         | 3      | 2.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 123       | 138    | 62.12%  |
| SSD     | 48        | 65     | 24.24%  |
| MMC     | 21        | 26     | 10.61%  |
| NVMe    | 3         | 3      | 1.52%   |
| Unknown | 3         | 3      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 200    | 84.38%  |
| MMC  | 21        | 26     | 10.94%  |
| SAS  | 6         | 6      | 3.13%   |
| NVMe | 3         | 3      | 1.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 148       | 181    | 87.57%  |
| 0.51-1.0   | 20        | 21     | 11.83%  |
| 1.01-2.0   | 1         | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 35.64%  |
| 251-500        | 39        | 20.74%  |
| 51-100         | 30        | 15.96%  |
| 21-50          | 20        | 10.64%  |
| 1-20           | 15        | 7.98%   |
| 501-1000       | 11        | 5.85%   |
| 1001-2000      | 2         | 1.06%   |
| Unknown        | 2         | 1.06%   |
| More than 3000 | 1         | 0.53%   |
| 2001-3000      | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 130       | 66.67%  |
| 21-50     | 36        | 18.46%  |
| 51-100    | 16        | 8.21%   |
| 101-250   | 7         | 3.59%   |
| 501-1000  | 3         | 1.54%   |
| Unknown   | 2         | 1.03%   |
| 1001-2000 | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 16.67%  |
| Seagate ST9500420AS 500GB          | 1         | 1      | 16.67%  |
| Seagate ST9250315AS 250GB          | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| Hitachi HTS545016B9SA00 160GB      | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 66.67%  |
| WDC     | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 159       | 207    | 85.95%  |
| Works    | 20        | 22     | 10.81%  |
| Malfunc  | 6         | 6      | 3.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 138       | 80.23%  |
| AMD                              | 20        | 11.63%  |
| Silicon Integrated Systems [SiS] | 4         | 2.33%   |
| VIA Technologies                 | 3         | 1.74%   |
| Samsung Electronics              | 3         | 1.74%   |
| Nvidia                           | 3         | 1.74%   |
| Micron Technology                | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 20        | 9.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 20        | 9.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 13        | 6.25%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 13        | 6.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 12        | 5.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 11        | 5.29%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 11        | 5.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 9         | 4.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 9         | 4.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 6         | 2.88%   |
| Intel 82801FBM (ICH6M) SATA Controller                                       | 6         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 6         | 2.88%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 4         | 1.92%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 4         | 1.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 4         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 4         | 1.92%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                     | 4         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 4         | 1.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 1.44%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 3         | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 3         | 1.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 1.44%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 2         | 0.96%   |
| VIA VT8237A SATA 2-Port Controller                                           | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 0.96%   |
| AMD SB600 Non-Raid-5 SATA                                                    | 2         | 0.96%   |
| AMD SB600 IDE                                                                | 2         | 0.96%   |
| AMD IXP SB4x0 IDE Controller                                                 | 2         | 0.96%   |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 0.48%   |
| Samsung Electronics SATA controller                                          | 1         | 0.48%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.48%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                 | 1         | 0.48%   |
| Nvidia MCP78S [GeForce 8200] IDE                                             | 1         | 0.48%   |
| Nvidia MCP67 IDE Controller                                                  | 1         | 0.48%   |
| Nvidia MCP67 AHCI Controller                                                 | 1         | 0.48%   |
| Micron NVMe Storage Controller                                               | 1         | 0.48%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 122       | 63.87%  |
| IDE  | 61        | 31.94%  |
| RAID | 5         | 2.62%   |
| NVMe | 3         | 1.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 161       | 87.03%  |
| AMD          | 23        | 12.43%  |
| CentaurHauls | 1         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 9         | 4.86%   |
| Intel Pentium M processor 1.73GHz           | 6         | 3.24%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 3.24%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 3.24%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 2.16%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.62%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 3         | 1.62%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 3         | 1.62%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 1.62%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 1.08%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.08%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 1.08%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 1.08%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 1.08%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.08%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.08%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.08%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.08%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.08%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.08%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.08%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 2         | 1.08%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 2         | 1.08%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 1.08%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 1.08%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 2         | 1.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.08%   |
| Intel Celeron CPU 925 @ 2.30GHz             | 2         | 1.08%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 1.08%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 1.08%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.08%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 1.08%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.08%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.54%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 26        | 14.05%  |
| Intel Atom              | 25        | 13.51%  |
| Intel Core i7           | 17        | 9.19%   |
| Intel Core i5           | 15        | 8.11%   |
| Intel Core 2 Duo        | 15        | 8.11%   |
| Intel Genuine           | 12        | 6.49%   |
| Intel Core i3           | 12        | 6.49%   |
| Intel Pentium           | 9         | 4.86%   |
| Intel Pentium M         | 7         | 3.78%   |
| Intel Pentium Dual-Core | 7         | 3.78%   |
| Intel Core 2            | 7         | 3.78%   |
| Intel Pentium Dual      | 4         | 2.16%   |
| AMD E                   | 3         | 1.62%   |
| AMD A8                  | 3         | 1.62%   |
| Other                   | 2         | 1.08%   |
| AMD Turion 64 X2 Mobile | 2         | 1.08%   |
| AMD E2                  | 2         | 1.08%   |
| AMD E1                  | 2         | 1.08%   |
| AMD Athlon              | 2         | 1.08%   |
| Intel Pentium Silver    | 1         | 0.54%   |
| Intel Core Duo          | 1         | 0.54%   |
| Intel Celeron M         | 1         | 0.54%   |
| Intel Celeron Dual-Core | 1         | 0.54%   |
| CentaurHauls VIA C7     | 1         | 0.54%   |
| AMD Turion 64 Mobile    | 1         | 0.54%   |
| AMD Sempron             | 1         | 0.54%   |
| AMD Phenom II           | 1         | 0.54%   |
| AMD C-60                | 1         | 0.54%   |
| AMD Athlon 64 X2        | 1         | 0.54%   |
| AMD A6                  | 1         | 0.54%   |
| AMD A4                  | 1         | 0.54%   |
| AMD A10                 | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 112       | 60.54%  |
| 1      | 45        | 24.32%  |
| 4      | 28        | 15.14%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 185       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 62.16%  |
| 2      | 70        | 37.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 146       | 78.49%  |
| 32-bit         | 28        | 15.05%  |
| Unknown        | 12        | 6.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x1067a    | 17        | 8.99%   |
| 0x306a9    | 16        | 8.47%   |
| Unknown    | 16        | 8.47%   |
| 0x206a7    | 14        | 7.41%   |
| 0x6fd      | 13        | 6.88%   |
| 0x106ca    | 12        | 6.35%   |
| 0x106c2    | 10        | 5.29%   |
| 0x6d8      | 7         | 3.7%    |
| 0x406c4    | 7         | 3.7%    |
| 0x6e8      | 6         | 3.17%   |
| 0x30678    | 6         | 3.17%   |
| 0x20655    | 5         | 2.65%   |
| 0x10661    | 5         | 2.65%   |
| 0x6f6      | 4         | 2.12%   |
| 0x6ec      | 4         | 2.12%   |
| 0x05000119 | 4         | 2.12%   |
| 0x806ec    | 3         | 1.59%   |
| 0x806e9    | 3         | 1.59%   |
| 0x40651    | 3         | 1.59%   |
| 0x10676    | 3         | 1.59%   |
| 0x07030105 | 3         | 1.59%   |
| 0x06006705 | 3         | 1.59%   |
| 0x806ea    | 2         | 1.06%   |
| 0x706a8    | 2         | 1.06%   |
| 0x706a1    | 2         | 1.06%   |
| 0x6f2      | 2         | 1.06%   |
| 0x306d4    | 2         | 1.06%   |
| 0x806c1    | 1         | 0.53%   |
| 0x6fb      | 1         | 0.53%   |
| 0x506c9    | 1         | 0.53%   |
| 0x30673    | 1         | 0.53%   |
| 0x30661    | 1         | 0.53%   |
| 0x20652    | 1         | 0.53%   |
| 0x106e5    | 1         | 0.53%   |
| 0x08200103 | 1         | 0.53%   |
| 0x07030106 | 1         | 0.53%   |
| 0x0700010f | 1         | 0.53%   |
| 0x06006118 | 1         | 0.53%   |
| 0x06001119 | 1         | 0.53%   |
| 0x05000029 | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Core            | 27        | 14.59%  |
| Bonnell         | 23        | 12.43%  |
| Penryn          | 20        | 10.81%  |
| P6              | 17        | 9.19%   |
| IvyBridge       | 17        | 9.19%   |
| Silvermont      | 14        | 7.57%   |
| SandyBridge     | 14        | 7.57%   |
| Westmere        | 8         | 4.32%   |
| KabyLake        | 8         | 4.32%   |
| K8 Hammer       | 5         | 2.7%    |
| Bobcat          | 5         | 2.7%    |
| Puma            | 4         | 2.16%   |
| Goldmont plus   | 4         | 2.16%   |
| Excavator       | 4         | 2.16%   |
| Haswell         | 3         | 1.62%   |
| Broadwell       | 3         | 1.62%   |
| Zen             | 1         | 0.54%   |
| TigerLake       | 1         | 0.54%   |
| Piledriver      | 1         | 0.54%   |
| Nehalem         | 1         | 0.54%   |
| K8 & K10 hybrid | 1         | 0.54%   |
| K10             | 1         | 0.54%   |
| Jaguar          | 1         | 0.54%   |
| Goldmont        | 1         | 0.54%   |
| Unknown         | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 140       | 72.54%  |
| AMD                              | 26        | 13.47%  |
| Nvidia                           | 20        | 10.36%  |
| Silicon Integrated Systems [SiS] | 4         | 2.07%   |
| VIA Technologies                 | 3         | 1.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 24        | 10.34%  |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 8.19%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 6.47%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 14        | 6.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 5.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 4.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 4.74%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 11        | 4.74%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 10        | 4.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.02%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.59%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 2.16%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 1.72%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.29%   |
| Intel HD Graphics 620                                                                    | 3         | 1.29%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.29%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.86%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.86%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.86%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.86%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.86%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.86%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 0.86%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.86%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.43%   |
| Nvidia GT218M [ION]                                                                      | 1         | 0.43%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.43%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.43%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.43%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 1         | 0.43%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.43%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.43%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 131       | 70.81%  |
| 1 x AMD        | 21        | 11.35%  |
| 1 x Nvidia     | 13        | 7.03%   |
| Intel + Nvidia | 7         | 3.78%   |
| 2 x AMD        | 4         | 2.16%   |
| 1 x SiS        | 4         | 2.16%   |
| 1 x VIA        | 3         | 1.62%   |
| Other          | 1         | 0.54%   |
| Intel + AMD    | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 170       | 91.4%   |
| Unknown     | 12        | 6.45%   |
| Proprietary | 4         | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 136       | 72.73%  |
| 0.01-0.5   | 38        | 20.32%  |
| 0.51-1.0   | 8         | 4.28%   |
| 1.01-2.0   | 3         | 1.6%    |
| 3.01-4.0   | 2         | 1.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 42        | 23.08%  |
| Samsung Electronics     | 29        | 15.93%  |
| LG Display              | 21        | 11.54%  |
| LG Philips              | 13        | 7.14%   |
| Chi Mei Optoelectronics | 10        | 5.49%   |
| HannStar                | 8         | 4.4%    |
| Chimei Innolux          | 8         | 4.4%    |
| Lenovo                  | 6         | 3.3%    |
| BOE                     | 5         | 2.75%   |
| InfoVision              | 4         | 2.2%    |
| CPT                     | 4         | 2.2%    |
| Sony                    | 3         | 1.65%   |
| Dell                    | 3         | 1.65%   |
| ViewSonic               | 2         | 1.1%    |
| Hitachi                 | 2         | 1.1%    |
| Hewlett-Packard         | 2         | 1.1%    |
| BenQ                    | 2         | 1.1%    |
| Apple                   | 2         | 1.1%    |
| Vizio                   | 1         | 0.55%   |
| Toshiba                 | 1         | 0.55%   |
| Seiko/Epson             | 1         | 0.55%   |
| Quanta Display          | 1         | 0.55%   |
| Philips                 | 1         | 0.55%   |
| PANDA                   | 1         | 0.55%   |
| Optoma                  | 1         | 0.55%   |
| OEM                     | 1         | 0.55%   |
| LPL                     | 1         | 0.55%   |
| KDC                     | 1         | 0.55%   |
| HKC                     | 1         | 0.55%   |
| Element                 | 1         | 0.55%   |
| CVT                     | 1         | 0.55%   |
| AOC                     | 1         | 0.55%   |
| Ancor Communications    | 1         | 0.55%   |
| Acer                    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 6         | 3.24%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 1.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.62%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 330x210mm 15.4-inch     | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 2         | 1.08%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 1.08%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.08%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 1.08%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 1.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 1.08%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.54%   |
| ViewSonic VG710s VSCA218 1280x1024 338x270mm 17.0-inch                   | 1         | 0.54%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 1         | 0.54%   |
| Toshiba LCD Monitor LCD58EF 1280x800 261x163mm 12.1-inch                 | 1         | 0.54%   |
| Sony TV SNY9500 1920x540 560x420mm 27.6-inch                             | 1         | 0.54%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch     | 1         | 0.54%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 1         | 0.54%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch      | 1         | 0.54%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch     | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 75        | 40.76%  |
| 1280x800 (WXGA)    | 31        | 16.85%  |
| 1920x1080 (FHD)    | 29        | 15.76%  |
| 1024x600           | 14        | 7.61%   |
| 1600x900 (HD+)     | 7         | 3.8%    |
| 1024x768 (XGA)     | 6         | 3.26%   |
| 3840x2160 (4K)     | 3         | 1.63%   |
| 1920x1200 (WUXGA)  | 3         | 1.63%   |
| 1440x900 (WXGA+)   | 3         | 1.63%   |
| 2560x1440 (QHD)    | 2         | 1.09%   |
| 1920x540           | 2         | 1.09%   |
| 1280x1024 (SXGA)   | 2         | 1.09%   |
| 1024x576           | 2         | 1.09%   |
| 1680x1050 (WSXGA+) | 1         | 0.54%   |
| 1400x1050          | 1         | 0.54%   |
| 1360x768           | 1         | 0.54%   |
| 1280x960           | 1         | 0.54%   |
| 1280x768           | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 87        | 47.8%   |
| 14      | 17        | 9.34%   |
| 13      | 14        | 7.69%   |
| 10      | 14        | 7.69%   |
| 11      | 10        | 5.49%   |
| 17      | 9         | 4.95%   |
| 24      | 6         | 3.3%    |
| 12      | 5         | 2.75%   |
| 84      | 3         | 1.65%   |
| 27      | 3         | 1.65%   |
| 21      | 3         | 1.65%   |
| Unknown | 3         | 1.65%   |
| 8       | 2         | 1.1%    |
| 52      | 1         | 0.55%   |
| 39      | 1         | 0.55%   |
| 31      | 1         | 0.55%   |
| 23      | 1         | 0.55%   |
| 22      | 1         | 0.55%   |
| 18      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 59.12%  |
| 201-300     | 38        | 20.99%  |
| 501-600     | 10        | 5.52%   |
| 351-400     | 10        | 5.52%   |
| 401-500     | 5         | 2.76%   |
| 1501-2000   | 3         | 1.66%   |
| Unknown     | 3         | 1.66%   |
| 101-200     | 2         | 1.1%    |
| 801-900     | 1         | 0.55%   |
| 601-700     | 1         | 0.55%   |
| 1001-1500   | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 123       | 72.35%  |
| 16/10   | 34        | 20%     |
| 4/3     | 8         | 4.71%   |
| 5/4     | 3         | 1.76%   |
| Unknown | 2         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 47.25%  |
| 81-90          | 23        | 12.64%  |
| 41-50          | 14        | 7.69%   |
| 51-60          | 10        | 5.49%   |
| 201-250        | 7         | 3.85%   |
| 71-80          | 6         | 3.3%    |
| 121-130        | 6         | 3.3%    |
| 61-70          | 5         | 2.75%   |
| More than 1000 | 4         | 2.2%    |
| 141-150        | 3         | 1.65%   |
| 91-100         | 3         | 1.65%   |
| Unknown        | 3         | 1.65%   |
| 351-500        | 2         | 1.1%    |
| 1-40           | 2         | 1.1%    |
| 301-350        | 2         | 1.1%    |
| 251-300        | 2         | 1.1%    |
| 151-200        | 2         | 1.1%    |
| 131-140        | 1         | 0.55%   |
| 501-1000       | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 85        | 47.75%  |
| 51-100  | 52        | 29.21%  |
| 121-160 | 34        | 19.1%   |
| 161-240 | 3         | 1.69%   |
| Unknown | 3         | 1.69%   |
| 1-50    | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 158       | 84.04%  |
| 2     | 21        | 11.17%  |
| 0     | 8         | 4.26%   |
| 3     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 85        | 25.76%  |
| Intel                             | 72        | 21.82%  |
| Qualcomm Atheros                  | 57        | 17.27%  |
| Broadcom                          | 49        | 14.85%  |
| Marvell Technology Group          | 17        | 5.15%   |
| Broadcom Limited                  | 12        | 3.64%   |
| Ralink                            | 4         | 1.21%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.91%   |
| VIA Technologies                  | 2         | 0.61%   |
| TP-Link                           | 2         | 0.61%   |
| Samsung Electronics               | 2         | 0.61%   |
| Ralink Technology                 | 2         | 0.61%   |
| Nvidia                            | 2         | 0.61%   |
| JMicron Technology                | 2         | 0.61%   |
| Huawei Technologies               | 2         | 0.61%   |
| ASIX Electronics                  | 2         | 0.61%   |
| Spreadtrum Communications         | 1         | 0.3%    |
| NetGear                           | 1         | 0.3%    |
| Micro Star International          | 1         | 0.3%    |
| MediaTek                          | 1         | 0.3%    |
| Linksys                           | 1         | 0.3%    |
| Ericsson Business Mobile Networks | 1         | 0.3%    |
| DisplayLink                       | 1         | 0.3%    |
| Dell                              | 1         | 0.3%    |
| Compal Electronics                | 1         | 0.3%    |
| BUFFALO                           | 1         | 0.3%    |
| Belkin Components                 | 1         | 0.3%    |
| Attansic Technology               | 1         | 0.3%    |
| ASUSTek Computer                  | 1         | 0.3%    |
| Apple                             | 1         | 0.3%    |
| AMD                               | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 32        | 8.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 7.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 3.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 3.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 9         | 2.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.37%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 2.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 8         | 2.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.58%   |
| Intel Wireless 7265                                                     | 6         | 1.58%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 1.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 1.32%   |
| Intel Wireless 7260                                                     | 5         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.32%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.05%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.05%   |
| Intel Wireless 3165                                                     | 4         | 1.05%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.05%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.05%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 1.05%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 3         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.79%   |
| Intel 82573L Gigabit Ethernet Controller                                | 3         | 0.79%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.79%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 3         | 0.79%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 3         | 0.79%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.53%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 67        | 34.9%   |
| Qualcomm Atheros         | 43        | 22.4%   |
| Broadcom                 | 35        | 18.23%  |
| Realtek Semiconductor    | 26        | 13.54%  |
| Broadcom Limited         | 8         | 4.17%   |
| Ralink                   | 4         | 2.08%   |
| TP-Link                  | 2         | 1.04%   |
| Ralink Technology        | 2         | 1.04%   |
| NetGear                  | 1         | 0.52%   |
| Micro Star International | 1         | 0.52%   |
| BUFFALO                  | 1         | 0.52%   |
| Belkin Components        | 1         | 0.52%   |
| ASUSTek Computer         | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 7.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 7.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 4.66%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 4.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.11%   |
| Intel Wireless 7265                                                     | 6         | 3.11%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 3.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 3.11%   |
| Intel Wireless 7260                                                     | 5         | 2.59%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 2.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 2.07%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 2.07%   |
| Intel Wireless 3165                                                     | 4         | 2.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.07%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.55%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.04%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1.04%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 1.04%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 1.04%   |
| Realtek 802.11ac NIC                                                    | 2         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.04%   |
| Intel Wireless 8265 / 8275                                              | 2         | 1.04%   |
| Intel WiFi Link 5100                                                    | 2         | 1.04%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 1.04%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.04%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.04%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 74        | 42.53%  |
| Intel                            | 21        | 12.07%  |
| Qualcomm Atheros                 | 20        | 11.49%  |
| Broadcom                         | 19        | 10.92%  |
| Marvell Technology Group         | 17        | 9.77%   |
| Broadcom Limited                 | 5         | 2.87%   |
| Silicon Integrated Systems [SiS] | 3         | 1.72%   |
| VIA Technologies                 | 2         | 1.15%   |
| Nvidia                           | 2         | 1.15%   |
| JMicron Technology               | 2         | 1.15%   |
| ASIX Electronics                 | 2         | 1.15%   |
| Spreadtrum Communications        | 1         | 0.57%   |
| Samsung Electronics              | 1         | 0.57%   |
| MediaTek                         | 1         | 0.57%   |
| Linksys                          | 1         | 0.57%   |
| DisplayLink                      | 1         | 0.57%   |
| Attansic Technology              | 1         | 0.57%   |
| Apple                            | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 32        | 18.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 16.57%  |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 9         | 5.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 8         | 4.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.29%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.71%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 1.71%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.71%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 1.71%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 3         | 1.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 1.14%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 1.14%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.14%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 2         | 1.14%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.14%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 2         | 1.14%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 2         | 1.14%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 1.14%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                            | 2         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.14%   |
| Spreadtrum Spreadtrum Phone                                                    | 1         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.57%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.57%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.57%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.57%   |
| MediaTek CPH2211                                                               | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.57%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 50.7%   |
| Ethernet | 166       | 46.24%  |
| Modem    | 10        | 2.79%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 72.28%  |
| Ethernet | 54        | 26.73%  |
| Modem    | 1         | 0.5%    |
| Unknown  | 1         | 0.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 148       | 80%     |
| 1     | 33        | 17.84%  |
| 0     | 3         | 1.62%   |
| 3     | 1         | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 170       | 90.91%  |
| Yes  | 17        | 9.09%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 28.72%  |
| Broadcom                        | 11        | 11.7%   |
| Qualcomm Atheros Communications | 8         | 8.51%   |
| Hewlett-Packard                 | 7         | 7.45%   |
| Realtek Semiconductor           | 6         | 6.38%   |
| Lite-On Technology              | 5         | 5.32%   |
| Foxconn / Hon Hai               | 5         | 5.32%   |
| Toshiba                         | 4         | 4.26%   |
| Foxconn International           | 4         | 4.26%   |
| IMC Networks                    | 3         | 3.19%   |
| Dell                            | 3         | 3.19%   |
| Cambridge Silicon Radio         | 3         | 3.19%   |
| Ralink                          | 2         | 2.13%   |
| Apple                           | 2         | 2.13%   |
| Alps Electric                   | 2         | 2.13%   |
| Fujitsu Siemens Computers       | 1         | 1.06%   |
| ASUSTek Computer                | 1         | 1.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 18.09%  |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 7.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 4.26%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 4.26%   |
| Realtek Bluetooth Radio                             | 3         | 3.19%   |
| Intel Bluetooth Device                              | 3         | 3.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 3.19%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 3.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.13%   |
| Ralink RT3290 Bluetooth                             | 2         | 2.13%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.13%   |
| Intel AX201 Bluetooth                               | 2         | 2.13%   |
| Dell DW375 Bluetooth Module                         | 2         | 2.13%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.06%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 1.06%   |
| Toshiba Bluetooth Device                            | 1         | 1.06%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 1.06%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.06%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.06%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.06%   |
| Lite-On Bluetooth Device                            | 1         | 1.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.06%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 1.06%   |
| IMC Networks Bluetooth module                       | 1         | 1.06%   |
| IMC Networks Bluetooth Device                       | 1         | 1.06%   |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 1.06%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.06%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 1.06%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.06%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 1.06%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.06%   |
| Broadcom IBM Integrated Bluetooth IV                | 1         | 1.06%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.06%   |
| Broadcom BCM20702A0                                 | 1         | 1.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 76%     |
| AMD                              | 22        | 11%     |
| Nvidia                           | 14        | 7%      |
| Silicon Integrated Systems [SiS] | 4         | 2%      |
| VIA Technologies                 | 3         | 1.5%    |
| Logitech                         | 2         | 1%      |
| JMTek                            | 1         | 0.5%    |
| Elite Silicon                    | 1         | 0.5%    |
| C-Media Electronics              | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 39        | 17.57%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 23        | 10.36%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 9.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 4.05%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.7%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 5         | 2.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 2.25%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 1.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.8%    |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.8%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1.35%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.35%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.35%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.35%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.35%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.9%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.45%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.45%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.45%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Logitech Z305                                                                                     | 1         | 0.45%   |
| Logitech Headset H390                                                                             | 1         | 0.45%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.45%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 15        | 25.42%  |
| Samsung Electronics | 13        | 22.03%  |
| SK hynix            | 8         | 13.56%  |
| Micron Technology   | 4         | 6.78%   |
| Kingston            | 4         | 6.78%   |
| Crucial             | 2         | 3.39%   |
| Corsair             | 2         | 3.39%   |
| Unknown (ABCD)      | 1         | 1.69%   |
| Toshiba             | 1         | 1.69%   |
| Smart               | 1         | 1.69%   |
| Ramaxel Technology  | 1         | 1.69%   |
| PNY                 | 1         | 1.69%   |
| Nanya Technology    | 1         | 1.69%   |
| Infineon            | 1         | 1.69%   |
| Elpida              | 1         | 1.69%   |
| A-DATA Technology   | 1         | 1.69%   |
| 48spaces            | 1         | 1.69%   |
| Unknown             | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 3.17%   |
| Micron RAM MT52L256M32D1PF107 2GB LPDDR3 1600MT/s                | 2         | 3.17%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 1.59%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 1.59%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.59%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 1         | 1.59%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 1.59%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.59%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.59%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                     | 1         | 1.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.59%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.59%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.59%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 1.59%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.59%   |
| SK hynix RAM Module 512MB DIMM DDR2 533MT/s                      | 1         | 1.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.59%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s              | 1         | 1.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.59%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s            | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 31        | 55.36%  |
| DDR2   | 9         | 16.07%  |
| DDR4   | 4         | 7.14%   |
| SDRAM  | 3         | 5.36%   |
| LPDDR3 | 3         | 5.36%   |
| DDR    | 3         | 5.36%   |
| DRAM   | 2         | 3.57%   |
| LPDDR4 | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 50        | 89.29%  |
| Unknown      | 3         | 5.36%   |
| Row Of Chips | 1         | 1.79%   |
| DIMM         | 1         | 1.79%   |
| Chip         | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 21        | 35%     |
| 2048    | 20        | 33.33%  |
| 8192    | 9         | 15%     |
| 1024    | 5         | 8.33%   |
| 512     | 3         | 5%      |
| 256     | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 21        | 35%     |
| Unknown | 10        | 16.67%  |
| 1333    | 6         | 10%     |
| 667     | 4         | 6.67%   |
| 2400    | 3         | 5%      |
| 1334    | 3         | 5%      |
| 1066    | 2         | 3.33%   |
| 800     | 2         | 3.33%   |
| 533     | 2         | 3.33%   |
| 3200    | 1         | 1.67%   |
| 2667    | 1         | 1.67%   |
| 2048    | 1         | 1.67%   |
| 1867    | 1         | 1.67%   |
| 1067    | 1         | 1.67%   |
| 975     | 1         | 1.67%   |
| 100     | 1         | 1.67%   |

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
| Chicony Electronics                    | 39        | 28.06%  |
| Suyin                                  | 12        | 8.63%   |
| Realtek Semiconductor                  | 12        | 8.63%   |
| IMC Networks                           | 11        | 7.91%   |
| Acer                                   | 9         | 6.47%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.76%   |
| Microdia                               | 7         | 5.04%   |
| Z-Star Microelectronics                | 6         | 4.32%   |
| Ricoh                                  | 6         | 4.32%   |
| Sunplus Innovation Technology          | 5         | 3.6%    |
| Silicon Motion                         | 4         | 2.88%   |
| Bison Electronics                      | 4         | 2.88%   |
| Syntek                                 | 3         | 2.16%   |
| Importek                               | 3         | 2.16%   |
| ALi                                    | 3         | 2.16%   |
| Samsung Electronics                    | 1         | 0.72%   |
| OmniVision Technologies                | 1         | 0.72%   |
| Lite-On Technology                     | 1         | 0.72%   |
| Lenovo                                 | 1         | 0.72%   |
| DigiTech                               | 1         | 0.72%   |
| Apple                                  | 1         | 0.72%   |
| Alcor Micro                            | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                           | 4         | 2.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 4         | 2.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 2.88%   |
| IMC Networks UVC VGA Webcam                             | 3         | 2.16%   |
| Chicony USB 2.0 Camera                                  | 3         | 2.16%   |
| Chicony TOSHIBA Web Camera - HD                         | 3         | 2.16%   |
| Chicony CNF9055 Toshiba Webcam                          | 3         | 2.16%   |
| Acer Lenovo EasyCamera                                  | 3         | 2.16%   |
| Silicon Motion WebCam SC-0311139N                       | 2         | 1.44%   |
| Ricoh Sony Vaio Integrated Webcam                       | 2         | 1.44%   |
| Ricoh Laptop_Integrated_Webcam_FHD                      | 2         | 1.44%   |
| Realtek USB Camera                                      | 2         | 1.44%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.44%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.44%   |
| Realtek Integrated Webcam                               | 2         | 1.44%   |
| Realtek HD WebCam                                       | 2         | 1.44%   |
| Microdia Sonix USB 2.0 Camera                           | 2         | 1.44%   |
| Importek HP Webcam-50                                   | 2         | 1.44%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 2         | 1.44%   |
| IMC Networks Integrated Webcam                          | 2         | 1.44%   |
| Chicony VGA Webcam                                      | 2         | 1.44%   |
| Chicony Lenovo EasyCamera                               | 2         | 1.44%   |
| Chicony HP HD Camera                                    | 2         | 1.44%   |
| Chicony HD WebCam                                       | 2         | 1.44%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 2         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.44%   |
| Bison Integrated Camera                                 | 2         | 1.44%   |
| Acer BisonCam, NB Pro                                   | 2         | 1.44%   |
| Z-Star Vega USB 2.0 Camera                              | 1         | 0.72%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.72%   |
| Syntek USB Camera Device                                | 1         | 0.72%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.72%   |
| Syntek Integrated Webcam                                | 1         | 0.72%   |
| Suyin Webcam-101                                        | 1         | 0.72%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.72%   |
| Suyin HP Webcam                                         | 1         | 0.72%   |
| Suyin HP Truevision HD                                  | 1         | 0.72%   |
| Suyin HD Video WebCam                                   | 1         | 0.72%   |
| Suyin Acer OrbiCam                                      | 1         | 0.72%   |
| Suyin Acer CrystalEye Webcam                            | 1         | 0.72%   |

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
| O2 Micro    | 4         | 40%     |
| Broadcom    | 3         | 30%     |
| Upek        | 1         | 10%     |
| Lenovo      | 1         | 10%     |
| Alcor Micro | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 30%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 20%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 62.57%  |
| 1     | 55        | 29.41%  |
| 2     | 13        | 6.95%   |
| 4     | 1         | 0.53%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 23        | 26.44%  |
| Fingerprint reader       | 17        | 19.54%  |
| Net/wireless             | 12        | 13.79%  |
| Chipcard                 | 10        | 11.49%  |
| Storage                  | 6         | 6.9%    |
| Modem                    | 5         | 5.75%   |
| Communication controller | 3         | 3.45%   |
| Bluetooth                | 3         | 3.45%   |
| Flash memory             | 2         | 2.3%    |
| Camera                   | 2         | 2.3%    |
| Storage/raid             | 1         | 1.15%   |
| Storage/ide              | 1         | 1.15%   |
| Sound                    | 1         | 1.15%   |
| Multimedia controller    | 1         | 1.15%   |

