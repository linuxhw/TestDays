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

Total: 291

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 13 9343                 | [aca11b8b22](https://linux-hardware.org/?probe=aca11b8b22) | Dec 04, 2023 |
| Dell          | Vostro 3500                 | [bd6506d274](https://linux-hardware.org/?probe=bd6506d274) | Nov 30, 2023 |
| Acer          | Aspire E5-576G              | [cbce88f621](https://linux-hardware.org/?probe=cbce88f621) | Nov 26, 2023 |
| Acer          | Aspire E5-576G              | [3ce4659fcd](https://linux-hardware.org/?probe=3ce4659fcd) | Nov 25, 2023 |
| Toshiba       | Satellite C50-A-1DV         | [190ce47896](https://linux-hardware.org/?probe=190ce47896) | Oct 03, 2023 |
| Toshiba       | Satellite C50-A-1DV         | [791e483369](https://linux-hardware.org/?probe=791e483369) | Oct 03, 2023 |
| Dell          | Inspiron 5559               | [c25a72c95a](https://linux-hardware.org/?probe=c25a72c95a) | Sep 27, 2023 |
| SiS           | M672 Board SI94B-20+SI96... | [4b309ad43c](https://linux-hardware.org/?probe=4b309ad43c) | Sep 02, 2023 |
| Packard Be... | EasyNote MZ36               | [d628db6497](https://linux-hardware.org/?probe=d628db6497) | Aug 21, 2023 |
| Dell          | Inspiron 15-3552            | [91d473eb35](https://linux-hardware.org/?probe=91d473eb35) | Aug 17, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [aa12dbe8bf](https://linux-hardware.org/?probe=aa12dbe8bf) | Jul 28, 2023 |
| Dell          | Latitude E6330              | [32dbf41885](https://linux-hardware.org/?probe=32dbf41885) | Jul 24, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [2294cf035b](https://linux-hardware.org/?probe=2294cf035b) | Jul 16, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [b26a172e92](https://linux-hardware.org/?probe=b26a172e92) | Jul 16, 2023 |
| Dell          | Latitude E6400              | [a5af3e134e](https://linux-hardware.org/?probe=a5af3e134e) | Jun 30, 2023 |
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
| Peppermint 10   | 148       | 75.51%  |
| Peppermint 9    | 16        | 8.16%   |
| Peppermint      | 13        | 6.63%   |
| Peppermint 11.4 | 4         | 2.04%   |
| Peppermint 11.3 | 4         | 2.04%   |
| Peppermint 11.1 | 4         | 2.04%   |
| Peppermint 11.5 | 2         | 1.02%   |
| Peppermint 11.2 | 2         | 1.02%   |
| Peppermint 8    | 1         | 0.51%   |
| Peppermint 12   | 1         | 0.51%   |
| Peppermint 11.7 | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Peppermint | 196       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.0.0-37-generic  | 24        | 11.11%  |
| 5.4.0-42-generic  | 7         | 3.24%   |
| 5.3.0-62-generic  | 7         | 3.24%   |
| 5.3.0-51-generic  | 7         | 3.24%   |
| 4.18.0-18-generic | 7         | 3.24%   |
| 5.4.0-65-generic  | 6         | 2.78%   |
| 4.15.0-43-generic | 6         | 2.78%   |
| 5.10.0-14-amd64   | 5         | 2.31%   |
| 6.1.0-10-amd64    | 4         | 1.85%   |
| 5.4.0-91-generic  | 4         | 1.85%   |
| 5.4.0-72-generic  | 4         | 1.85%   |
| 5.4.0-58-generic  | 4         | 1.85%   |
| 5.10.0-19-amd64   | 4         | 1.85%   |
| 5.0.0-32-generic  | 4         | 1.85%   |
| 5.4.0-90-generic  | 3         | 1.39%   |
| 5.4.0-87-generic  | 3         | 1.39%   |
| 5.4.0-80-generic  | 3         | 1.39%   |
| 5.4.0-77-generic  | 3         | 1.39%   |
| 5.4.0-66-generic  | 3         | 1.39%   |
| 5.4.0-47-generic  | 3         | 1.39%   |
| 5.4.0-45-generic  | 3         | 1.39%   |
| 5.3.0-46-generic  | 3         | 1.39%   |
| 5.3.0-42-generic  | 3         | 1.39%   |
| 5.3.0-28-generic  | 3         | 1.39%   |
| 5.10.0-16-amd64   | 3         | 1.39%   |
| 5.0.0-36-generic  | 3         | 1.39%   |
| 4.15.0-48-generic | 3         | 1.39%   |
| 4.15.0-47-generic | 3         | 1.39%   |
| 6.1.0-11-amd64    | 2         | 0.93%   |
| 5.4.0-97-generic  | 2         | 0.93%   |
| 5.4.0-84-generic  | 2         | 0.93%   |
| 5.4.0-81-generic  | 2         | 0.93%   |
| 5.4.0-74-generic  | 2         | 0.93%   |
| 5.4.0-70-generic  | 2         | 0.93%   |
| 5.4.0-67-generic  | 2         | 0.93%   |
| 5.4.0-56-generic  | 2         | 0.93%   |
| 5.4.0-54-generic  | 2         | 0.93%   |
| 5.4.0-52-generic  | 2         | 0.93%   |
| 5.4.0-48-generic  | 2         | 0.93%   |
| 5.3.0-59-generic  | 2         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 82        | 40.2%   |
| 5.0.0   | 32        | 15.69%  |
| 5.3.0   | 27        | 13.24%  |
| 5.10.0  | 21        | 10.29%  |
| 4.15.0  | 15        | 7.35%   |
| 4.18.0  | 13        | 6.37%   |
| 6.1.0   | 9         | 4.41%   |
| 5.4.95  | 1         | 0.49%   |
| 5.3.6   | 1         | 0.49%   |
| 5.18.0  | 1         | 0.49%   |
| 5.1.11  | 1         | 0.49%   |
| 4.8.0   | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 83        | 40.69%  |
| 5.0     | 32        | 15.69%  |
| 5.3     | 28        | 13.73%  |
| 5.10    | 21        | 10.29%  |
| 4.15    | 15        | 7.35%   |
| 4.18    | 13        | 6.37%   |
| 6.1     | 9         | 4.41%   |
| 5.18    | 1         | 0.49%   |
| 5.1     | 1         | 0.49%   |
| 4.8     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 132       | 67.35%  |
| i686   | 64        | 32.65%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| LXDE       | 127       | 63.5%   |
| Unknown    | 33        | 16.5%   |
| XFCE       | 30        | 15%     |
| GNOME      | 7         | 3.5%    |
| X-Cinnamon | 1         | 0.5%    |
| Peppermint | 1         | 0.5%    |
| Cinnamon   | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 196       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 152       | 77.16%  |
| LightDM | 37        | 18.78%  |
| TDM     | 7         | 3.55%   |
| SDDM    | 1         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 66        | 33.17%  |
| Unknown | 27        | 13.57%  |
| en_GB   | 14        | 7.04%   |
| de_DE   | 12        | 6.03%   |
| pt_BR   | 10        | 5.03%   |
| it_IT   | 9         | 4.52%   |
| pl_PL   | 7         | 3.52%   |
| nl_NL   | 5         | 2.51%   |
| C       | 5         | 2.51%   |
| fr_FR   | 4         | 2.01%   |
| es_AR   | 4         | 2.01%   |
| en_CA   | 4         | 2.01%   |
| ru_RU   | 3         | 1.51%   |
| es_MX   | 3         | 1.51%   |
| ro_RO   | 2         | 1.01%   |
| ja_JP   | 2         | 1.01%   |
| fi_FI   | 2         | 1.01%   |
| en_NZ   | 2         | 1.01%   |
| en_IN   | 2         | 1.01%   |
| en_AU   | 2         | 1.01%   |
| tr_TR   | 1         | 0.5%    |
| sv_SE   | 1         | 0.5%    |
| pt_PT   | 1         | 0.5%    |
| nl_BE   | 1         | 0.5%    |
| lv_LV   | 1         | 0.5%    |
| es_PE   | 1         | 0.5%    |
| es_PA   | 1         | 0.5%    |
| es_ES   | 1         | 0.5%    |
| es_CR   | 1         | 0.5%    |
| es_BO   | 1         | 0.5%    |
| en_ZA   | 1         | 0.5%    |
| en_PH   | 1         | 0.5%    |
| el_GR   | 1         | 0.5%    |
| cs_CZ   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 148       | 75.51%  |
| EFI  | 48        | 24.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 163       | 82.32%  |
| Unknown  | 16        | 8.08%   |
| Overlay  | 9         | 4.55%   |
| Ext3     | 3         | 1.52%   |
| Ext2     | 2         | 1.01%   |
| Tmpfs    | 1         | 0.51%   |
| Reiserfs | 1         | 0.51%   |
| F2fs     | 1         | 0.51%   |
| Btrfs    | 1         | 0.51%   |
| Aufs     | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 158       | 80.2%   |
| GPT     | 20        | 10.15%  |
| MBR     | 19        | 9.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 94.95%  |
| Yes       | 10        | 5.05%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 175       | 87.94%  |
| Yes       | 24        | 12.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 38        | 19.39%  |
| Dell                | 27        | 13.78%  |
| Lenovo              | 26        | 13.27%  |
| ASUSTek Computer    | 18        | 9.18%   |
| Toshiba             | 17        | 8.67%   |
| Acer                | 17        | 8.67%   |
| Samsung Electronics | 8         | 4.08%   |
| Sony                | 6         | 3.06%   |
| Google              | 5         | 2.55%   |
| Fujitsu Siemens     | 5         | 2.55%   |
| Positivo            | 3         | 1.53%   |
| Packard Bell        | 3         | 1.53%   |
| eMachines           | 3         | 1.53%   |
| Medion              | 2         | 1.02%   |
| IBM                 | 2         | 1.02%   |
| Gateway             | 2         | 1.02%   |
| Clevo               | 2         | 1.02%   |
| Apple               | 2         | 1.02%   |
| Unknown             | 2         | 1.02%   |
| WinBook             | 1         | 0.51%   |
| SiS                 | 1         | 0.51%   |
| Olivetti            | 1         | 0.51%   |
| LincPlus            | 1         | 0.51%   |
| JPSaCouto           | 1         | 0.51%   |
| Itautec             | 1         | 0.51%   |
| GPU Company         | 1         | 0.51%   |
| Fujitsu             | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo G500 20236                           | 3         | 1.53%   |
| Toshiba Satellite M70                       | 2         | 1.02%   |
| Toshiba Satellite L500                      | 2         | 1.02%   |
| Samsung N150P/N210P/N220P                   | 2         | 1.02%   |
| Positivo Mobile                             | 2         | 1.02%   |
| Google Banon                                | 2         | 1.02%   |
| Fujitsu Siemens ESPRIMO Mobile V5535        | 2         | 1.02%   |
| Dell Latitude D630                          | 2         | 1.02%   |
| Dell Inspiron N5050                         | 2         | 1.02%   |
| Dell Inspiron 1545                          | 2         | 1.02%   |
| Acer Extensa 5630                           | 2         | 1.02%   |
| Unknown                                     | 2         | 1.02%   |
| WinBook GL Series                           | 1         | 0.51%   |
| Toshiba Satellite Pro C850                  | 1         | 0.51%   |
| Toshiba Satellite L750D                     | 1         | 0.51%   |
| Toshiba Satellite L310                      | 1         | 0.51%   |
| Toshiba Satellite L300                      | 1         | 0.51%   |
| Toshiba Satellite C850-F117                 | 1         | 0.51%   |
| Toshiba Satellite C660                      | 1         | 0.51%   |
| Toshiba Satellite C55D-B                    | 1         | 0.51%   |
| Toshiba Satellite C50-A-1DV                 | 1         | 0.51%   |
| Toshiba QOSMIO F755                         | 1         | 0.51%   |
| Toshiba PORTEGE R500                        | 1         | 0.51%   |
| Toshiba NB520                               | 1         | 0.51%   |
| Toshiba NB500                               | 1         | 0.51%   |
| Toshiba dynabook Satellite B552/H           | 1         | 0.51%   |
| Sony VPCZ21V9E                              | 1         | 0.51%   |
| Sony VPCEA36FM                              | 1         | 0.51%   |
| Sony VPCCW21FX                              | 1         | 0.51%   |
| Sony VGN-S55B_S                             | 1         | 0.51%   |
| Sony VGN-FW140E                             | 1         | 0.51%   |
| Sony VGN-CR21S_P                            | 1         | 0.51%   |
| SiS M672+968                                | 1         | 0.51%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.51%   |
| Samsung R610                                | 1         | 0.51%   |
| Samsung R530/R730/R540                      | 1         | 0.51%   |
| Samsung N150P                               | 1         | 0.51%   |
| Samsung N150/N210/N220                      | 1         | 0.51%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA  | 1         | 0.51%   |
| Positivo N1103                              | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Dell Inspiron           | 14        | 7.14%   |
| Toshiba Satellite       | 12        | 6.12%   |
| Lenovo ThinkPad         | 12        | 6.12%   |
| HP Pavilion             | 9         | 4.59%   |
| Dell Latitude           | 9         | 4.59%   |
| HP Compaq               | 8         | 4.08%   |
| Acer Aspire             | 8         | 4.08%   |
| HP EliteBook            | 6         | 3.06%   |
| Lenovo IdeaPad          | 4         | 2.04%   |
| HP Laptop               | 4         | 2.04%   |
| Acer Extensa            | 4         | 2.04%   |
| Samsung N150P           | 3         | 1.53%   |
| Packard Bell EasyNote   | 3         | 1.53%   |
| Lenovo G500             | 3         | 1.53%   |
| Fujitsu Siemens AMILO   | 3         | 1.53%   |
| Positivo Mobile         | 2         | 1.02%   |
| IBM ThinkPad            | 2         | 1.02%   |
| HP Stream               | 2         | 1.02%   |
| HP Mini                 | 2         | 1.02%   |
| HP 255                  | 2         | 1.02%   |
| Google Banon            | 2         | 1.02%   |
| Fujitsu Siemens ESPRIMO | 2         | 1.02%   |
| Dell Vostro             | 2         | 1.02%   |
| Dell Precision          | 2         | 1.02%   |
| Unknown                 | 2         | 1.02%   |
| WinBook GL              | 1         | 0.51%   |
| Toshiba QOSMIO          | 1         | 0.51%   |
| Toshiba PORTEGE         | 1         | 0.51%   |
| Toshiba NB520           | 1         | 0.51%   |
| Toshiba NB500           | 1         | 0.51%   |
| Toshiba dynabook        | 1         | 0.51%   |
| Sony VPCZ21V9E          | 1         | 0.51%   |
| Sony VPCEA36FM          | 1         | 0.51%   |
| Sony VPCCW21FX          | 1         | 0.51%   |
| Sony VGN-S55B           | 1         | 0.51%   |
| Sony VGN-FW140E         | 1         | 0.51%   |
| Sony VGN-CR21S          | 1         | 0.51%   |
| SiS M672+968            | 1         | 0.51%   |
| Samsung RV411           | 1         | 0.51%   |
| Samsung R610            | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2008    | 30        | 15.31%  |
| 2011    | 20        | 10.2%   |
| 2010    | 19        | 9.69%   |
| 2012    | 18        | 9.18%   |
| 2009    | 17        | 8.67%   |
| 2007    | 17        | 8.67%   |
| 2006    | 14        | 7.14%   |
| 2013    | 13        | 6.63%   |
| 2018    | 7         | 3.57%   |
| 2015    | 7         | 3.57%   |
| 2016    | 6         | 3.06%   |
| 2014    | 6         | 3.06%   |
| 2017    | 5         | 2.55%   |
| 2005    | 5         | 2.55%   |
| 2020    | 3         | 1.53%   |
| 2019    | 3         | 1.53%   |
| 2023    | 2         | 1.02%   |
| 2022    | 2         | 1.02%   |
| 2021    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 196       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 188       | 95.92%  |
| Enabled  | 8         | 4.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 190       | 96.94%  |
| Yes  | 6         | 3.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 58        | 29.29%  |
| 1.01-2.0   | 53        | 26.77%  |
| 4.01-8.0   | 34        | 17.17%  |
| 0.51-1.0   | 18        | 9.09%   |
| 2.01-3.0   | 15        | 7.58%   |
| 8.01-16.0  | 12        | 6.06%   |
| 16.01-24.0 | 6         | 3.03%   |
| 32.01-64.0 | 1         | 0.51%   |
| 0.01-0.5   | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 78        | 36.45%  |
| 0.51-1.0 | 76        | 35.51%  |
| 2.01-3.0 | 31        | 14.49%  |
| 0.01-0.5 | 18        | 8.41%   |
| 3.01-4.0 | 7         | 3.27%   |
| 4.01-8.0 | 4         | 1.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 155       | 77.5%   |
| 2      | 36        | 18%     |
| 3      | 5         | 2.5%    |
| 0      | 4         | 2%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 58.38%  |
| No        | 82        | 41.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 89.29%  |
| No        | 21        | 10.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 98.47%  |
| No        | 3         | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 51.27%  |
| No        | 96        | 48.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 51        | 26.02%  |
| Germany      | 18        | 9.18%   |
| UK           | 13        | 6.63%   |
| Italy        | 11        | 5.61%   |
| Brazil       | 10        | 5.1%    |
| Netherlands  | 9         | 4.59%   |
| Canada       | 9         | 4.59%   |
| Poland       | 7         | 3.57%   |
| France       | 6         | 3.06%   |
| Argentina    | 6         | 3.06%   |
| Sweden       | 4         | 2.04%   |
| Russia       | 4         | 2.04%   |
| Romania      | 4         | 2.04%   |
| Spain        | 3         | 1.53%   |
| Mexico       | 3         | 1.53%   |
| Japan        | 3         | 1.53%   |
| Portugal     | 2         | 1.02%   |
| Philippines  | 2         | 1.02%   |
| New Zealand  | 2         | 1.02%   |
| India        | 2         | 1.02%   |
| Greece       | 2         | 1.02%   |
| Finland      | 2         | 1.02%   |
| Bolivia      | 2         | 1.02%   |
| Turkey       | 1         | 0.51%   |
| Switzerland  | 1         | 0.51%   |
| South Africa | 1         | 0.51%   |
| Serbia       | 1         | 0.51%   |
| Puerto Rico  | 1         | 0.51%   |
| Peru         | 1         | 0.51%   |
| Panama       | 1         | 0.51%   |
| Norway       | 1         | 0.51%   |
| Namibia      | 1         | 0.51%   |
| Malaysia     | 1         | 0.51%   |
| Lithuania    | 1         | 0.51%   |
| Latvia       | 1         | 0.51%   |
| Kazakhstan   | 1         | 0.51%   |
| Ireland      | 1         | 0.51%   |
| Georgia      | 1         | 0.51%   |
| Czechia      | 1         | 0.51%   |
| Costa Rica   | 1         | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Toronto             | 4         | 1.96%   |
| Warsaw              | 2         | 0.98%   |
| Turin               | 2         | 0.98%   |
| Topeka              | 2         | 0.98%   |
| Tokyo               | 2         | 0.98%   |
| Osasco              | 2         | 0.98%   |
| Naples              | 2         | 0.98%   |
| Moscow              | 2         | 0.98%   |
| Fayetteville        | 2         | 0.98%   |
| Bucharest           | 2         | 0.98%   |
| Zgierz              | 1         | 0.49%   |
| York                | 1         | 0.49%   |
| Yokohama            | 1         | 0.49%   |
| Wysokie Mazowieckie | 1         | 0.49%   |
| Worthing            | 1         | 0.49%   |
| Windhoek            | 1         | 0.49%   |
| West New York       | 1         | 0.49%   |
| West Chester        | 1         | 0.49%   |
| Weissenfels         | 1         | 0.49%   |
| Weinheim            | 1         | 0.49%   |
| Waalwijk            | 1         | 0.49%   |
| Volos               | 1         | 0.49%   |
| Vista               | 1         | 0.49%   |
| Villa María        | 1         | 0.49%   |
| Vijayawada          | 1         | 0.49%   |
| Venda do Pinheiro   | 1         | 0.49%   |
| Varna               | 1         | 0.49%   |
| Umeå               | 1         | 0.49%   |
| Uddingston          | 1         | 0.49%   |
| Tucson              | 1         | 0.49%   |
| Trofarello          | 1         | 0.49%   |
| Trento              | 1         | 0.49%   |
| Telford             | 1         | 0.49%   |
| Tauranga            | 1         | 0.49%   |
| Tampere             | 1         | 0.49%   |
| Tahlequah           | 1         | 0.49%   |
| Taguatinga          | 1         | 0.49%   |
| Sunchales           | 1         | 0.49%   |
| Stockton            | 1         | 0.49%   |
| Staffanstorp        | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 43        | 45     | 20.28%  |
| WDC                   | 36        | 41     | 16.98%  |
| Unknown               | 22        | 27     | 10.38%  |
| Toshiba               | 20        | 21     | 9.43%   |
| Samsung Electronics   | 20        | 30     | 9.43%   |
| Hitachi               | 15        | 18     | 7.08%   |
| Kingston              | 9         | 11     | 4.25%   |
| HGST                  | 6         | 7      | 2.83%   |
| SanDisk               | 5         | 6      | 2.36%   |
| Fujitsu               | 5         | 6      | 2.36%   |
| China                 | 3         | 3      | 1.42%   |
| PNY                   | 2         | 2      | 0.94%   |
| Micron Technology     | 2         | 2      | 0.94%   |
| Intenso               | 2         | 2      | 0.94%   |
| Integral              | 2         | 2      | 0.94%   |
| GOODRAM               | 2         | 2      | 0.94%   |
| Zheino                | 1         | 1      | 0.47%   |
| TrekStor              | 1         | 1      | 0.47%   |
| TCSUNBOW              | 1         | 1      | 0.47%   |
| SK hynix              | 1         | 1      | 0.47%   |
| SABRENT               | 1         | 1      | 0.47%   |
| Realtek Semiconductor | 1         | 1      | 0.47%   |
| Patriot               | 1         | 1      | 0.47%   |
| LITEONIT              | 1         | 1      | 0.47%   |
| KingSpec              | 1         | 1      | 0.47%   |
| Intel                 | 1         | 2      | 0.47%   |
| HS-SSD-C100           | 1         | 1      | 0.47%   |
| FATTYDOVE             | 1         | 1      | 0.47%   |
| Drevo                 | 1         | 1      | 0.47%   |
| Crucial               | 1         | 1      | 0.47%   |
| BHT                   | 1         | 2      | 0.47%   |
| Apple                 | 1         | 1      | 0.47%   |
| Apacer                | 1         | 3      | 0.47%   |
| Unknown               | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 6         | 2.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 2.31%   |
| Seagate ST9500325AS 500GB           | 4         | 1.85%   |
| Seagate ST9250315AS 250GB           | 4         | 1.85%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 1.85%   |
| Seagate ST9320325AS 320GB           | 3         | 1.39%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 1.39%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.93%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 0.93%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.93%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.93%   |
| Unknown SD/MMC/MS PRO 128GB         | 2         | 0.93%   |
| Unknown MMC Card  64GB              | 2         | 0.93%   |
| Unknown MMC Card  2GB               | 2         | 0.93%   |
| Unknown MMC Card  16GB              | 2         | 0.93%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.93%   |
| Toshiba MK5055GSX 500GB             | 2         | 0.93%   |
| Seagate ST9120822AS 120GB           | 2         | 0.93%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 0.93%   |
| Samsung SSD 850 EVO 250GB           | 2         | 0.93%   |
| Samsung HM160HI 160GB               | 2         | 0.93%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.93%   |
| Hitachi HTS545025B9A300 250GB       | 2         | 0.93%   |
| HGST HTS725050A7E630 500GB          | 2         | 0.93%   |
| HGST HTS725032A7E630 320GB          | 2         | 0.93%   |
| Zheino CHN 25SATAA3 120 120GB SSD   | 1         | 0.46%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 1         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.46%   |
| WDC WD800BEVS-60LAT0 80GB           | 1         | 0.46%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.46%   |
| WDC WD5000LPCX-00VHAT0 500GB        | 1         | 0.46%   |
| WDC WD5000BPVT-00HXZT3 500GB        | 1         | 0.46%   |
| WDC WD5000BEVT-55A0RT0 500GB        | 1         | 0.46%   |
| WDC WD3200BPVT-08JJ5T0 320GB        | 1         | 0.46%   |
| WDC WD3200BEVT-75ZCT2 320GB         | 1         | 0.46%   |
| WDC WD3200BEVT-00A0RT0 320GB        | 1         | 0.46%   |
| WDC WD2500BPVT-24ZEST0 250GB        | 1         | 0.46%   |
| WDC WD2500BEVT-80A23T0 250GB        | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 44     | 31.82%  |
| WDC                 | 34        | 39     | 25.76%  |
| Toshiba             | 19        | 20     | 14.39%  |
| Hitachi             | 15        | 18     | 11.36%  |
| Samsung Electronics | 9         | 9      | 6.82%   |
| HGST                | 6         | 7      | 4.55%   |
| Fujitsu             | 5         | 6      | 3.79%   |
| Unknown             | 2         | 2      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 19     | 19.61%  |
| Kingston            | 9         | 11     | 17.65%  |
| SanDisk             | 4         | 5      | 7.84%   |
| China               | 3         | 3      | 5.88%   |
| WDC                 | 2         | 2      | 3.92%   |
| PNY                 | 2         | 2      | 3.92%   |
| Intenso             | 2         | 2      | 3.92%   |
| Integral            | 2         | 2      | 3.92%   |
| GOODRAM             | 2         | 2      | 3.92%   |
| Zheino              | 1         | 1      | 1.96%   |
| TrekStor            | 1         | 1      | 1.96%   |
| Toshiba             | 1         | 1      | 1.96%   |
| TCSUNBOW            | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| LITEONIT            | 1         | 1      | 1.96%   |
| KingSpec            | 1         | 1      | 1.96%   |
| Intel               | 1         | 2      | 1.96%   |
| FATTYDOVE           | 1         | 1      | 1.96%   |
| Drevo               | 1         | 1      | 1.96%   |
| Crucial             | 1         | 1      | 1.96%   |
| BHT                 | 1         | 2      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |
| Apacer              | 1         | 3      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 130       | 145    | 61.9%   |
| SSD     | 50        | 67     | 23.81%  |
| MMC     | 22        | 27     | 10.48%  |
| NVMe    | 4         | 4      | 1.9%    |
| Unknown | 4         | 4      | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 172       | 210    | 84.31%  |
| MMC  | 22        | 27     | 10.78%  |
| SAS  | 6         | 6      | 2.94%   |
| NVMe | 4         | 4      | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 155       | 188    | 87.08%  |
| 0.51-1.0   | 23        | 24     | 12.92%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 70        | 35.18%  |
| 251-500        | 40        | 20.1%   |
| 51-100         | 31        | 15.58%  |
| 21-50          | 21        | 10.55%  |
| 1-20           | 18        | 9.05%   |
| 501-1000       | 13        | 6.53%   |
| 1001-2000      | 2         | 1.01%   |
| Unknown        | 2         | 1.01%   |
| More than 3000 | 1         | 0.5%    |
| 2001-3000      | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 139       | 67.48%  |
| 21-50     | 38        | 18.45%  |
| 51-100    | 16        | 7.77%   |
| 101-250   | 7         | 3.4%    |
| 501-1000  | 3         | 1.46%   |
| Unknown   | 2         | 0.97%   |
| 1001-2000 | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 10%     |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 10%     |
| Seagate ST9500420AS 500GB           | 1         | 1      | 10%     |
| Seagate ST9250315AS 250GB           | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB           | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 10%     |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 10%     |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 10%     |
| Hitachi HTS545016B9SA00 160GB       | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 60%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 60%     |
| WDC     | 1         | 1      | 10%     |
| Toshiba | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 100%    |

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
| Detected | 163       | 213    | 83.59%  |
| Works    | 22        | 24     | 11.28%  |
| Malfunc  | 10        | 10     | 5.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 146       | 79.78%  |
| AMD                              | 21        | 11.48%  |
| Silicon Integrated Systems [SiS] | 5         | 2.73%   |
| VIA Technologies                 | 3         | 1.64%   |
| Samsung Electronics              | 3         | 1.64%   |
| Nvidia                           | 3         | 1.64%   |
| Realtek Semiconductor            | 1         | 0.55%   |
| Micron Technology                | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 22        | 9.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 20        | 9.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 13        | 5.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                    | 13        | 5.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 12        | 5.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]               | 11        | 4.95%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 11        | 4.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 9         | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 9         | 4.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 3.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 6         | 2.7%    |
| Intel 82801FBM (ICH6M) SATA Controller                                       | 6         | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 6         | 2.7%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                  | 5         | 2.25%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 5         | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 5         | 2.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                 | 4         | 1.8%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                     | 4         | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 4         | 1.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 1.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 3         | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]         | 3         | 1.35%   |
| AMD IXP SB4x0 IDE Controller                                                 | 3         | 1.35%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                  | 2         | 0.9%    |
| VIA VT8237A SATA 2-Port Controller                                           | 2         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 0.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 0.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 2         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 2         | 0.9%    |
| AMD SB600 Non-Raid-5 SATA                                                    | 2         | 0.9%    |
| AMD SB600 IDE                                                                | 2         | 0.9%    |
| VIA VT8237/8251 Serial ATA Controller                                        | 1         | 0.45%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                   | 1         | 0.45%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.45%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.45%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                 | 1         | 0.45%   |
| Nvidia MCP78S [GeForce 8200] IDE                                             | 1         | 0.45%   |
| Nvidia MCP67 IDE Controller                                                  | 1         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 127       | 62.87%  |
| IDE  | 64        | 31.68%  |
| RAID | 7         | 3.47%   |
| NVMe | 4         | 1.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 172       | 87.76%  |
| AMD          | 23        | 11.73%  |
| CentaurHauls | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 9         | 4.59%   |
| Intel Pentium M processor 1.73GHz           | 6         | 3.06%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 3.06%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 3.06%   |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 2.04%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 1.53%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 3         | 1.53%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 3         | 1.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 1.53%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 3         | 1.53%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 1.53%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 1.02%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 1.02%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 1.02%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 1.02%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 1.02%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 1.02%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.02%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 1.02%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 1.02%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.02%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 1.02%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 1.02%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.02%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 2         | 1.02%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 2         | 1.02%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 1.02%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 2         | 1.02%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.02%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 1.02%   |
| Intel Celeron CPU 925 @ 2.30GHz             | 2         | 1.02%   |
| Intel Celeron CPU 900 @ 2.20GHz             | 2         | 1.02%   |
| Intel Celeron CPU 530 @ 1.73GHz             | 2         | 1.02%   |
| Intel Atom CPU N550 @ 1.50GHz               | 2         | 1.02%   |
| AMD E-450 APU with Radeon HD Graphics       | 2         | 1.02%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 2         | 1.02%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.51%   |
| Intel Pentium M processor 1.60GHz           | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 27        | 13.78%  |
| Intel Atom              | 25        | 12.76%  |
| Intel Core i5           | 20        | 10.2%   |
| Intel Core i7           | 17        | 8.67%   |
| Intel Core 2 Duo        | 16        | 8.16%   |
| Intel Core i3           | 14        | 7.14%   |
| Intel Genuine           | 12        | 6.12%   |
| Intel Pentium           | 9         | 4.59%   |
| Intel Pentium Dual-Core | 8         | 4.08%   |
| Intel Core 2            | 8         | 4.08%   |
| Intel Pentium M         | 7         | 3.57%   |
| Intel Pentium Dual      | 4         | 2.04%   |
| AMD E                   | 3         | 1.53%   |
| AMD A8                  | 3         | 1.53%   |
| Other                   | 2         | 1.02%   |
| AMD Turion 64 X2 Mobile | 2         | 1.02%   |
| AMD E2                  | 2         | 1.02%   |
| AMD E1                  | 2         | 1.02%   |
| AMD Athlon              | 2         | 1.02%   |
| Intel Pentium Silver    | 1         | 0.51%   |
| Intel Core Duo          | 1         | 0.51%   |
| Intel Celeron M         | 1         | 0.51%   |
| Intel Celeron Dual-Core | 1         | 0.51%   |
| CentaurHauls VIA C7     | 1         | 0.51%   |
| AMD Turion 64 Mobile    | 1         | 0.51%   |
| AMD Sempron             | 1         | 0.51%   |
| AMD Phenom II           | 1         | 0.51%   |
| AMD C-60                | 1         | 0.51%   |
| AMD Athlon 64 X2        | 1         | 0.51%   |
| AMD A6                  | 1         | 0.51%   |
| AMD A4                  | 1         | 0.51%   |
| AMD A10                 | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 62.24%  |
| 1      | 45        | 22.96%  |
| 4      | 29        | 14.8%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 196       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 60.71%  |
| 2      | 77        | 39.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 157       | 79.7%   |
| 32-bit         | 28        | 14.21%  |
| Unknown        | 12        | 6.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 19        | 9.5%    |
| Unknown    | 19        | 9.5%    |
| 0x1067a    | 18        | 9%      |
| 0x206a7    | 14        | 7%      |
| 0x6fd      | 13        | 6.5%    |
| 0x106ca    | 12        | 6%      |
| 0x106c2    | 10        | 5%      |
| 0x6d8      | 7         | 3.5%    |
| 0x406c4    | 7         | 3.5%    |
| 0x6e8      | 6         | 3%      |
| 0x30678    | 6         | 3%      |
| 0x20655    | 5         | 2.5%    |
| 0x10661    | 5         | 2.5%    |
| 0x6f6      | 4         | 2%      |
| 0x6ec      | 4         | 2%      |
| 0x05000119 | 4         | 2%      |
| 0x806ec    | 3         | 1.5%    |
| 0x806ea    | 3         | 1.5%    |
| 0x806e9    | 3         | 1.5%    |
| 0x6f2      | 3         | 1.5%    |
| 0x40651    | 3         | 1.5%    |
| 0x10676    | 3         | 1.5%    |
| 0x07030105 | 3         | 1.5%    |
| 0x06006705 | 3         | 1.5%    |
| 0x706a8    | 2         | 1%      |
| 0x706a1    | 2         | 1%      |
| 0x306d4    | 2         | 1%      |
| 0x806c1    | 1         | 0.5%    |
| 0x6fb      | 1         | 0.5%    |
| 0x506c9    | 1         | 0.5%    |
| 0x406e3    | 1         | 0.5%    |
| 0x406c3    | 1         | 0.5%    |
| 0x30673    | 1         | 0.5%    |
| 0x30661    | 1         | 0.5%    |
| 0x20652    | 1         | 0.5%    |
| 0x106e5    | 1         | 0.5%    |
| 0x08200103 | 1         | 0.5%    |
| 0x07030106 | 1         | 0.5%    |
| 0x0700010f | 1         | 0.5%    |
| 0x06006118 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Core            | 28        | 14.29%  |
| Bonnell         | 23        | 11.73%  |
| Penryn          | 22        | 11.22%  |
| IvyBridge       | 20        | 10.2%   |
| P6              | 17        | 8.67%   |
| Silvermont      | 15        | 7.65%   |
| SandyBridge     | 14        | 7.14%   |
| KabyLake        | 10        | 5.1%    |
| Westmere        | 9         | 4.59%   |
| K8 Hammer       | 5         | 2.55%   |
| Bobcat          | 5         | 2.55%   |
| Puma            | 4         | 2.04%   |
| Goldmont plus   | 4         | 2.04%   |
| Excavator       | 4         | 2.04%   |
| Haswell         | 3         | 1.53%   |
| Broadwell       | 3         | 1.53%   |
| Zen             | 1         | 0.51%   |
| TigerLake       | 1         | 0.51%   |
| Skylake         | 1         | 0.51%   |
| Piledriver      | 1         | 0.51%   |
| Nehalem         | 1         | 0.51%   |
| K8 & K10 hybrid | 1         | 0.51%   |
| K10             | 1         | 0.51%   |
| Jaguar          | 1         | 0.51%   |
| Goldmont        | 1         | 0.51%   |
| Unknown         | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 148       | 72.2%   |
| AMD                              | 27        | 13.17%  |
| Nvidia                           | 22        | 10.73%  |
| Silicon Integrated Systems [SiS] | 5         | 2.44%   |
| VIA Technologies                 | 3         | 1.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 24        | 9.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 8.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 7.38%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 14        | 5.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 5.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 4.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 4.51%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 11        | 4.51%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 10        | 4.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 3.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.46%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 5         | 2.05%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 2.05%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.64%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 3         | 1.23%   |
| Intel HD Graphics 620                                                                    | 3         | 1.23%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.23%   |
| Nvidia GT218M [GeForce 310M]                                                             | 2         | 0.82%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.82%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.82%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.82%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 2         | 0.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.82%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.82%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 0.82%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.82%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.41%   |
| Nvidia GT218M [ION]                                                                      | 1         | 0.41%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.41%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.41%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.41%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.41%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 1         | 0.41%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.41%   |
| Nvidia GF119M [GeForce GT 520MX]                                                         | 1         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 70.41%  |
| 1 x AMD        | 22        | 11.22%  |
| 1 x Nvidia     | 14        | 7.14%   |
| Intel + Nvidia | 8         | 4.08%   |
| 1 x SiS        | 5         | 2.55%   |
| 2 x AMD        | 4         | 2.04%   |
| 1 x VIA        | 3         | 1.53%   |
| Other          | 1         | 0.51%   |
| Intel + AMD    | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 180       | 91.37%  |
| Unknown     | 13        | 6.6%    |
| Proprietary | 4         | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 146       | 73.74%  |
| 0.01-0.5   | 39        | 19.7%   |
| 0.51-1.0   | 8         | 4.04%   |
| 1.01-2.0   | 3         | 1.52%   |
| 3.01-4.0   | 2         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 22.16%  |
| Samsung Electronics     | 30        | 15.46%  |
| LG Display              | 24        | 12.37%  |
| LG Philips              | 14        | 7.22%   |
| Chi Mei Optoelectronics | 10        | 5.15%   |
| Chimei Innolux          | 9         | 4.64%   |
| HannStar                | 8         | 4.12%   |
| BOE                     | 8         | 4.12%   |
| Lenovo                  | 6         | 3.09%   |
| InfoVision              | 4         | 2.06%   |
| CPT                     | 4         | 2.06%   |
| Sony                    | 3         | 1.55%   |
| Dell                    | 3         | 1.55%   |
| ViewSonic               | 2         | 1.03%   |
| PANDA                   | 2         | 1.03%   |
| Hitachi                 | 2         | 1.03%   |
| Hewlett-Packard         | 2         | 1.03%   |
| BenQ                    | 2         | 1.03%   |
| Apple                   | 2         | 1.03%   |
| Vizio                   | 1         | 0.52%   |
| Toshiba                 | 1         | 0.52%   |
| Seiko/Epson             | 1         | 0.52%   |
| Quanta Display          | 1         | 0.52%   |
| Philips                 | 1         | 0.52%   |
| Optoma                  | 1         | 0.52%   |
| OEM                     | 1         | 0.52%   |
| LPL                     | 1         | 0.52%   |
| KDC                     | 1         | 0.52%   |
| HKC                     | 1         | 0.52%   |
| Element                 | 1         | 0.52%   |
| Daewoo                  | 1         | 0.52%   |
| CVT                     | 1         | 0.52%   |
| AOC                     | 1         | 0.52%   |
| Ancor Communications    | 1         | 0.52%   |
| Acer                    | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 3.05%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 1.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 330x210mm 15.4-inch     | 2         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 1.02%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.02%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 2         | 1.02%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 1.02%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 1.02%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 1.02%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.02%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 1.02%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 2         | 1.02%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 1.02%   |
| Vizio M190VA VIZ0067 1360x768 410x230mm 18.5-inch                        | 1         | 0.51%   |
| ViewSonic VG710s VSCA218 1280x1024 338x270mm 17.0-inch                   | 1         | 0.51%   |
| ViewSonic VA2226w-11 VSC2051 1680x1050 495x291mm 22.6-inch               | 1         | 0.51%   |
| Toshiba LCD Monitor LCD58EF 1280x800 261x163mm 12.1-inch                 | 1         | 0.51%   |
| Sony TV SNY9500 720x480 560x420mm 27.6-inch                              | 1         | 0.51%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                  | 1         | 0.51%   |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                            | 1         | 0.51%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM0019 1024x768 304x228mm 15.0-inch      | 1         | 0.51%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch      | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4745 1280x800 331x207mm 15.4-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC364E 1024x600 223x125mm 10.1-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch     | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 81        | 41.54%  |
| 1280x800 (WXGA)    | 33        | 16.92%  |
| 1920x1080 (FHD)    | 31        | 15.9%   |
| 1024x600           | 14        | 7.18%   |
| 1600x900 (HD+)     | 7         | 3.59%   |
| 1024x768 (XGA)     | 6         | 3.08%   |
| 1440x900 (WXGA+)   | 4         | 2.05%   |
| 3840x2160 (4K)     | 3         | 1.54%   |
| 1920x1200 (WUXGA)  | 3         | 1.54%   |
| 2560x1440 (QHD)    | 2         | 1.03%   |
| 1920x540           | 2         | 1.03%   |
| 1280x1024 (SXGA)   | 2         | 1.03%   |
| 1024x576           | 2         | 1.03%   |
| 1680x1050 (WSXGA+) | 1         | 0.51%   |
| 1400x1050          | 1         | 0.51%   |
| 1360x768           | 1         | 0.51%   |
| 1280x960           | 1         | 0.51%   |
| 1280x768           | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 93        | 47.94%  |
| 14      | 19        | 9.79%   |
| 13      | 16        | 8.25%   |
| 10      | 14        | 7.22%   |
| 11      | 10        | 5.15%   |
| 17      | 9         | 4.64%   |
| 24      | 6         | 3.09%   |
| 12      | 5         | 2.58%   |
| 84      | 3         | 1.55%   |
| 27      | 3         | 1.55%   |
| 21      | 3         | 1.55%   |
| Unknown | 3         | 1.55%   |
| 31      | 2         | 1.03%   |
| 8       | 2         | 1.03%   |
| 52      | 1         | 0.52%   |
| 39      | 1         | 0.52%   |
| 23      | 1         | 0.52%   |
| 22      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| 18      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 60.1%   |
| 201-300     | 39        | 20.21%  |
| 501-600     | 10        | 5.18%   |
| 351-400     | 10        | 5.18%   |
| 401-500     | 6         | 3.11%   |
| 1501-2000   | 3         | 1.55%   |
| Unknown     | 3         | 1.55%   |
| 601-700     | 2         | 1.04%   |
| 101-200     | 2         | 1.04%   |
| 801-900     | 1         | 0.52%   |
| 1001-1500   | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 131       | 72.38%  |
| 16/10   | 37        | 20.44%  |
| 4/3     | 8         | 4.42%   |
| 5/4     | 3         | 1.66%   |
| Unknown | 2         | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 47.42%  |
| 81-90          | 26        | 13.4%   |
| 41-50          | 14        | 7.22%   |
| 51-60          | 10        | 5.15%   |
| 71-80          | 7         | 3.61%   |
| 201-250        | 7         | 3.61%   |
| 121-130        | 6         | 3.09%   |
| 61-70          | 5         | 2.58%   |
| More than 1000 | 4         | 2.06%   |
| 351-500        | 3         | 1.55%   |
| 151-200        | 3         | 1.55%   |
| 141-150        | 3         | 1.55%   |
| 91-100         | 3         | 1.55%   |
| Unknown        | 3         | 1.55%   |
| 1-40           | 2         | 1.03%   |
| 301-350        | 2         | 1.03%   |
| 251-300        | 2         | 1.03%   |
| 131-140        | 1         | 0.52%   |
| 501-1000       | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 92        | 48.42%  |
| 51-100  | 54        | 28.42%  |
| 121-160 | 36        | 18.95%  |
| 161-240 | 3         | 1.58%   |
| Unknown | 3         | 1.58%   |
| 1-50    | 2         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 165       | 82.91%  |
| 2     | 24        | 12.06%  |
| 0     | 9         | 4.52%   |
| 3     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 90        | 25.86%  |
| Intel                             | 76        | 21.84%  |
| Qualcomm Atheros                  | 61        | 17.53%  |
| Broadcom                          | 51        | 14.66%  |
| Marvell Technology Group          | 17        | 4.89%   |
| Broadcom Limited                  | 12        | 3.45%   |
| Ralink                            | 5         | 1.44%   |
| Silicon Integrated Systems [SiS]  | 4         | 1.15%   |
| VIA Technologies                  | 2         | 0.57%   |
| TP-Link                           | 2         | 0.57%   |
| Samsung Electronics               | 2         | 0.57%   |
| Ralink Technology                 | 2         | 0.57%   |
| Nvidia                            | 2         | 0.57%   |
| JMicron Technology                | 2         | 0.57%   |
| Huawei Technologies               | 2         | 0.57%   |
| ASIX Electronics                  | 2         | 0.57%   |
| Spreadtrum Communications         | 1         | 0.29%   |
| NetGear                           | 1         | 0.29%   |
| Motorola PCS                      | 1         | 0.29%   |
| Micro Star International          | 1         | 0.29%   |
| MediaTek                          | 1         | 0.29%   |
| Linksys                           | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| Compal Electronics                | 1         | 0.29%   |
| BUFFALO                           | 1         | 0.29%   |
| Belkin Components                 | 1         | 0.29%   |
| Attansic Technology               | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |
| Apple                             | 1         | 0.29%   |
| AMD                               | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 35        | 8.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 30        | 7.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 3.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 3.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 2.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 2.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 9         | 2.24%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 2%      |
| Intel Wireless 7265                                                     | 6         | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.5%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 1.25%   |
| Intel Wireless 7260                                                     | 5         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.25%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 1.25%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 4         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1%      |
| Intel Wireless 3165                                                     | 4         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1%      |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1%      |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.75%   |
| Intel 82573L Gigabit Ethernet Controller                                | 3         | 0.75%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.75%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 3         | 0.75%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 3         | 0.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.75%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 2         | 0.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 71        | 34.8%   |
| Qualcomm Atheros         | 47        | 23.04%  |
| Broadcom                 | 37        | 18.14%  |
| Realtek Semiconductor    | 26        | 12.75%  |
| Broadcom Limited         | 8         | 3.92%   |
| Ralink                   | 5         | 2.45%   |
| TP-Link                  | 2         | 0.98%   |
| Ralink Technology        | 2         | 0.98%   |
| NetGear                  | 1         | 0.49%   |
| Micro Star International | 1         | 0.49%   |
| Dell                     | 1         | 0.49%   |
| BUFFALO                  | 1         | 0.49%   |
| Belkin Components        | 1         | 0.49%   |
| ASUSTek Computer         | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 7.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 7.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 4.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 4.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.9%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 3.9%    |
| Intel Wireless 7265                                                     | 6         | 2.93%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 2.93%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.93%   |
| Intel Wireless 7260                                                     | 5         | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 2.44%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 2.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.95%   |
| Intel Wireless 3165                                                     | 4         | 1.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.95%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 3         | 1.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.46%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.46%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.46%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.98%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.98%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.98%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.98%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.98%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.98%   |
| Intel WiFi Link 5100                                                    | 2         | 0.98%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.98%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.98%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 79        | 42.93%  |
| Intel                            | 23        | 12.5%   |
| Qualcomm Atheros                 | 21        | 11.41%  |
| Broadcom                         | 19        | 10.33%  |
| Marvell Technology Group         | 17        | 9.24%   |
| Broadcom Limited                 | 5         | 2.72%   |
| Silicon Integrated Systems [SiS] | 4         | 2.17%   |
| VIA Technologies                 | 2         | 1.09%   |
| Nvidia                           | 2         | 1.09%   |
| JMicron Technology               | 2         | 1.09%   |
| ASIX Electronics                 | 2         | 1.09%   |
| Spreadtrum Communications        | 1         | 0.54%   |
| Samsung Electronics              | 1         | 0.54%   |
| Motorola PCS                     | 1         | 0.54%   |
| MediaTek                         | 1         | 0.54%   |
| Linksys                          | 1         | 0.54%   |
| DisplayLink                      | 1         | 0.54%   |
| Attansic Technology              | 1         | 0.54%   |
| Apple                            | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 35        | 18.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 30        | 16.22%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 4.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 9         | 4.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 3.24%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 2.7%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 4         | 2.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 2.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.62%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 1.62%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.62%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 1.62%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 3         | 1.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 1.08%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 1.08%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 1.08%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 1.08%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller                           | 2         | 1.08%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 1.08%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.08%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 2         | 1.08%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 2         | 1.08%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 1.08%   |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                            | 2         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.08%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.54%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.54%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.54%   |
| Motorola PCS moto g62 5G                                                       | 1         | 0.54%   |
| MediaTek P8                                                                    | 1         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 193       | 51.06%  |
| Ethernet | 175       | 46.3%   |
| Modem    | 9         | 2.38%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 155       | 72.09%  |
| Ethernet | 58        | 26.98%  |
| Modem    | 1         | 0.47%   |
| Unknown  | 1         | 0.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 157       | 80.1%   |
| 1     | 35        | 17.86%  |
| 0     | 3         | 1.53%   |
| 3     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 88.38%  |
| Yes  | 23        | 11.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 28.43%  |
| Broadcom                        | 12        | 11.76%  |
| Qualcomm Atheros Communications | 10        | 9.8%    |
| Hewlett-Packard                 | 7         | 6.86%   |
| Realtek Semiconductor           | 6         | 5.88%   |
| Toshiba                         | 5         | 4.9%    |
| Lite-On Technology              | 5         | 4.9%    |
| Foxconn / Hon Hai               | 5         | 4.9%    |
| Dell                            | 5         | 4.9%    |
| Foxconn International           | 4         | 3.92%   |
| IMC Networks                    | 3         | 2.94%   |
| Cambridge Silicon Radio         | 3         | 2.94%   |
| Ralink                          | 2         | 1.96%   |
| Apple                           | 2         | 1.96%   |
| Alps Electric                   | 2         | 1.96%   |
| Fujitsu Siemens Computers       | 1         | 0.98%   |
| ASUSTek Computer                | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 18        | 17.65%  |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 6.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 3.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 3.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 3.92%   |
| Realtek Bluetooth Radio                             | 3         | 2.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 2.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.94%   |
| Broadcom BCM2070 Bluetooth Device                   | 3         | 2.94%   |
| Toshiba Bluetooth Device                            | 2         | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.96%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 1.96%   |
| Intel AX201 Bluetooth                               | 2         | 1.96%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.96%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 1.96%   |
| Broadcom BCM20702A0                                 | 2         | 1.96%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.98%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.98%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.98%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.98%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.98%   |
| Lite-On Bluetooth Device                            | 1         | 0.98%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.98%   |
| Intel AX200 Bluetooth                               | 1         | 0.98%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.98%   |
| IMC Networks Bluetooth module                       | 1         | 0.98%   |
| IMC Networks Bluetooth Device                       | 1         | 0.98%   |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 0.98%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.98%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 0.98%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.98%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.98%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 161       | 75.59%  |
| AMD                              | 23        | 10.8%   |
| Nvidia                           | 15        | 7.04%   |
| Silicon Integrated Systems [SiS] | 5         | 2.35%   |
| VIA Technologies                 | 3         | 1.41%   |
| Logitech                         | 2         | 0.94%   |
| JMTek                            | 1         | 0.47%   |
| Hewlett-Packard                  | 1         | 0.47%   |
| Elite Silicon                    | 1         | 0.47%   |
| C-Media Electronics              | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 39        | 16.6%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 24        | 10.21%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 9.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 4.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 4.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 4.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 3.4%    |
| AMD FCH Azalia Controller                                                                         | 8         | 3.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.55%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 2.55%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.55%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 2.13%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 5         | 2.13%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.7%    |
| AMD Wrestler HDMI Audio                                                                           | 4         | 1.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.7%    |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 3         | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.28%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.28%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.28%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.28%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.85%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 2         | 0.85%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.43%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.43%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Logitech Z305                                                                                     | 1         | 0.43%   |
| Logitech Headset H390                                                                             | 1         | 0.43%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Unknown             | 17        | 25%     |
| Samsung Electronics | 15        | 22.06%  |
| SK hynix            | 11        | 16.18%  |
| Kingston            | 5         | 7.35%   |
| Micron Technology   | 4         | 5.88%   |
| Ramaxel Technology  | 2         | 2.94%   |
| Crucial             | 2         | 2.94%   |
| Corsair             | 2         | 2.94%   |
| Unknown (ABCD)      | 1         | 1.47%   |
| Toshiba             | 1         | 1.47%   |
| Smart               | 1         | 1.47%   |
| PNY                 | 1         | 1.47%   |
| Nanya Technology    | 1         | 1.47%   |
| Infineon            | 1         | 1.47%   |
| Elpida              | 1         | 1.47%   |
| A-DATA Technology   | 1         | 1.47%   |
| 48spaces            | 1         | 1.47%   |
| Unknown             | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 4.17%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.78%   |
| Micron RAM MT52L256M32D1PF107 2GB LPDDR3 1600MT/s                | 2         | 2.78%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 1.39%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 1.39%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.39%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.39%   |
| Unknown RAM Module 2GB DIMM DRAM                                 | 1         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 1         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 1         | 1.39%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 1.39%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.39%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                     | 1         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.39%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 1.39%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.39%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 1.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.39%   |
| SK hynix RAM Module 512MB DIMM DDR2 533MT/s                      | 1         | 1.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.39%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.39%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5674-M0-YK0 4GB Chip DDR3 1600MT/s              | 1         | 1.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 35        | 55.56%  |
| DDR2   | 9         | 14.29%  |
| DDR4   | 5         | 7.94%   |
| DRAM   | 4         | 6.35%   |
| SDRAM  | 3         | 4.76%   |
| LPDDR3 | 3         | 4.76%   |
| DDR    | 3         | 4.76%   |
| LPDDR4 | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 88.89%  |
| Unknown      | 3         | 4.76%   |
| DIMM         | 2         | 3.17%   |
| Row Of Chips | 1         | 1.59%   |
| Chip         | 1         | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 25        | 36.76%  |
| 2048    | 23        | 33.82%  |
| 8192    | 10        | 14.71%  |
| 1024    | 5         | 7.35%   |
| 512     | 3         | 4.41%   |
| 256     | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 24        | 35.29%  |
| Unknown | 12        | 17.65%  |
| 1333    | 6         | 8.82%   |
| 2400    | 4         | 5.88%   |
| 667     | 4         | 5.88%   |
| 1334    | 3         | 4.41%   |
| 3200    | 2         | 2.94%   |
| 1066    | 2         | 2.94%   |
| 800     | 2         | 2.94%   |
| 533     | 2         | 2.94%   |
| 3266    | 1         | 1.47%   |
| 2667    | 1         | 1.47%   |
| 2048    | 1         | 1.47%   |
| 1867    | 1         | 1.47%   |
| 1067    | 1         | 1.47%   |
| 975     | 1         | 1.47%   |
| 100     | 1         | 1.47%   |

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
| Chicony Electronics                    | 40        | 27.03%  |
| Suyin                                  | 12        | 8.11%   |
| Realtek Semiconductor                  | 12        | 8.11%   |
| Microdia                               | 12        | 8.11%   |
| IMC Networks                           | 11        | 7.43%   |
| Bison Electronics                      | 9         | 6.08%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 5.41%   |
| Ricoh                                  | 7         | 4.73%   |
| Z-Star Microelectronics                | 6         | 4.05%   |
| Sunplus Innovation Technology          | 5         | 3.38%   |
| Acer                                   | 5         | 3.38%   |
| Silicon Motion                         | 4         | 2.7%    |
| Syntek                                 | 3         | 2.03%   |
| Importek                               | 3         | 2.03%   |
| ALi                                    | 3         | 2.03%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Quanta                                 | 1         | 0.68%   |
| OmniVision Technologies                | 1         | 0.68%   |
| Lite-On Technology                     | 1         | 0.68%   |
| Lenovo                                 | 1         | 0.68%   |
| DigiTech                               | 1         | 0.68%   |
| Apple                                  | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                           | 4         | 2.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 4         | 2.7%    |
| Chicony TOSHIBA Web Camera - HD                         | 4         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 2.7%    |
| Bison Lenovo Integrated Webcam                          | 4         | 2.7%    |
| Microdia Sonix USB 2.0 Camera                           | 3         | 2.03%   |
| IMC Networks UVC VGA Webcam                             | 3         | 2.03%   |
| Chicony USB 2.0 Camera                                  | 3         | 2.03%   |
| Chicony CNF9055 Toshiba Webcam                          | 3         | 2.03%   |
| Bison Integrated Camera                                 | 3         | 2.03%   |
| Silicon Motion WebCam SC-0311139N                       | 2         | 1.35%   |
| Ricoh Sony Vaio Integrated Webcam                       | 2         | 1.35%   |
| Ricoh Laptop_Integrated_Webcam_FHD                      | 2         | 1.35%   |
| Realtek USB Camera                                      | 2         | 1.35%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.35%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.35%   |
| Realtek Integrated Webcam                               | 2         | 1.35%   |
| Realtek HD WebCam                                       | 2         | 1.35%   |
| Microdia Integrated Webcam                              | 2         | 1.35%   |
| Importek HP Webcam-50                                   | 2         | 1.35%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 2         | 1.35%   |
| IMC Networks Integrated Webcam                          | 2         | 1.35%   |
| Chicony VGA Webcam                                      | 2         | 1.35%   |
| Chicony Lenovo EasyCamera                               | 2         | 1.35%   |
| Chicony HP HD Camera                                    | 2         | 1.35%   |
| Chicony HD WebCam                                       | 2         | 1.35%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 2         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.35%   |
| Acer BisonCam, NB Pro                                   | 2         | 1.35%   |
| Z-Star Vega USB 2.0 Camera                              | 1         | 0.68%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.68%   |
| Syntek USB Camera Device                                | 1         | 0.68%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.68%   |
| Syntek Integrated Webcam                                | 1         | 0.68%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.68%   |
| Suyin HP Webcam 101                                     | 1         | 0.68%   |
| Suyin HP Webcam                                         | 1         | 0.68%   |
| Suyin HP Truevision HD                                  | 1         | 0.68%   |
| Suyin HD Video WebCam                                   | 1         | 0.68%   |
| Suyin Acer OrbiCam                                      | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 31.58%  |
| AuthenTec             | 5         | 26.32%  |
| STMicroelectronics    | 4         | 21.05%  |
| Upek                  | 2         | 10.53%  |
| Synaptics             | 1         | 5.26%   |
| LighTuning Technology | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                                      | 4         | 21.05%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 10.53%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 5.26%   |
| AuthenTec AES2810                                                          | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 5.26%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 5.26%   |
| AuthenTec AES1600                                                          | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| O2 Micro    | 4         | 36.36%  |
| Broadcom    | 4         | 36.36%  |
| Upek        | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 27.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 9.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 119       | 60.1%   |
| 1     | 59        | 29.8%   |
| 2     | 18        | 9.09%   |
| 4     | 1         | 0.51%   |
| 3     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 33        | 33.33%  |
| Fingerprint reader       | 18        | 18.18%  |
| Net/wireless             | 12        | 12.12%  |
| Chipcard                 | 11        | 11.11%  |
| Storage                  | 6         | 6.06%   |
| Modem                    | 5         | 5.05%   |
| Communication controller | 3         | 3.03%   |
| Bluetooth                | 3         | 3.03%   |
| Flash memory             | 2         | 2.02%   |
| Camera                   | 2         | 2.02%   |
| Storage/raid             | 1         | 1.01%   |
| Storage/ide              | 1         | 1.01%   |
| Sound                    | 1         | 1.01%   |
| Multimedia controller    | 1         | 1.01%   |

