Linux in Austria - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

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

Total: 1166

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | [565ad502cc](https://linux-hardware.org/?probe=565ad502cc) | Nov 02, 2022 |
| HP            | ZBook 15 G2                 | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| ASUSTek       | K54L                        | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| Adlinktech    | SB-MLC                      | [203d95e012](https://linux-hardware.org/?probe=203d95e012) | Oct 31, 2022 |
| Dell          | Latitude E6400              | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Lenovo        | ThinkPad T510 4384WKU       | [86fee6e260](https://linux-hardware.org/?probe=86fee6e260) | Oct 30, 2022 |
| Dell          | Studio 1737                 | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | EliteBook 820 G4            | [c41402e832](https://linux-hardware.org/?probe=c41402e832) | Oct 29, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [c079764998](https://linux-hardware.org/?probe=c079764998) | Oct 28, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [5ef9b4213f](https://linux-hardware.org/?probe=5ef9b4213f) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| ASUSTek       | UX303LAB                    | [5748274da1](https://linux-hardware.org/?probe=5748274da1) | Oct 27, 2022 |
| Dell          | Precision 7530              | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| ASUSTek       | UX303LAB                    | [622aa11277](https://linux-hardware.org/?probe=622aa11277) | Oct 26, 2022 |
| Lenovo        | ThinkPad P1 20MD000NGE      | [561f09ba0f](https://linux-hardware.org/?probe=561f09ba0f) | Oct 25, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Valve         | Jupiter                     | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [99da3e6f09](https://linux-hardware.org/?probe=99da3e6f09) | Oct 22, 2022 |
| Dell          | XPS 13 9343                 | [1ce3fc664e](https://linux-hardware.org/?probe=1ce3fc664e) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Dell          | Latitude 5520               | [fc014585a8](https://linux-hardware.org/?probe=fc014585a8) | Oct 19, 2022 |
| Dell          | Latitude 5520               | [3589f77c74](https://linux-hardware.org/?probe=3589f77c74) | Oct 19, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20US... | [ec42bc932e](https://linux-hardware.org/?probe=ec42bc932e) | Oct 18, 2022 |
| Dell          | Precision 5510              | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| Dell          | Latitude 3520               | [f556b42181](https://linux-hardware.org/?probe=f556b42181) | Oct 16, 2022 |
| ASUSTek       | X580VD                      | [59ecc7da84](https://linux-hardware.org/?probe=59ecc7da84) | Oct 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [766f4b2d1f](https://linux-hardware.org/?probe=766f4b2d1f) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [bf46cd0c9e](https://linux-hardware.org/?probe=bf46cd0c9e) | Oct 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [bc23ce28e0](https://linux-hardware.org/?probe=bc23ce28e0) | Oct 14, 2022 |
| Dell          | Inspiron 3505               | [04147466b3](https://linux-hardware.org/?probe=04147466b3) | Oct 13, 2022 |
| Dell          | Latitude E6440              | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| Dell          | Latitude E6540              | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [e860301211](https://linux-hardware.org/?probe=e860301211) | Oct 09, 2022 |
| Valve         | Jupiter                     | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| MSI           | Modern 14 B11M              | [e0391b5084](https://linux-hardware.org/?probe=e0391b5084) | Oct 05, 2022 |
| HP            | ProBook 450 G3              | [16b58b369a](https://linux-hardware.org/?probe=16b58b369a) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| HP            | EliteBook 850 G1            | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e829c9c0c6](https://linux-hardware.org/?probe=e829c9c0c6) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [3c0a494baa](https://linux-hardware.org/?probe=3c0a494baa) | Sep 26, 2022 |
| Dell          | Latitude E6400              | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| AMI           | Intel                       | [56de8f8b8a](https://linux-hardware.org/?probe=56de8f8b8a) | Sep 25, 2022 |
| AMI           | Intel                       | [330585dcd8](https://linux-hardware.org/?probe=330585dcd8) | Sep 25, 2022 |
| Acer          | Aspire E5-771G              | [39dc43058e](https://linux-hardware.org/?probe=39dc43058e) | Sep 23, 2022 |
| HP            | Compaq 15                   | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Dell          | Latitude E6510              | [fa644f90c4](https://linux-hardware.org/?probe=fa644f90c4) | Sep 22, 2022 |
| HP            | Pavilion 17                 | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| HP            | EliteBook 840 G3            | [233ba928b8](https://linux-hardware.org/?probe=233ba928b8) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Dell          | XPS 13 9380                 | [0c6c042af0](https://linux-hardware.org/?probe=0c6c042af0) | Sep 20, 2022 |
| Samsung       | R530/R730                   | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| HP            | ProBook 470 G4              | [c11b354c39](https://linux-hardware.org/?probe=c11b354c39) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| Valve         | Jupiter                     | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| HP            | ProBook 450 G0              | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Acer          | Aspire S3                   | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| HP            | EliteBook 8460p             | [12abaecf7e](https://linux-hardware.org/?probe=12abaecf7e) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| TrekStor      | Notebook Slim S130          | [abd3c1ccf8](https://linux-hardware.org/?probe=abd3c1ccf8) | Sep 05, 2022 |
| Lenovo        | ThinkPad T500 2241WH7       | [1e14648d27](https://linux-hardware.org/?probe=1e14648d27) | Sep 04, 2022 |
| BESSTAR Te... | X400                        | [8eb69c0ad6](https://linux-hardware.org/?probe=8eb69c0ad6) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [6109fc3fa8](https://linux-hardware.org/?probe=6109fc3fa8) | Sep 02, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [9f98c80601](https://linux-hardware.org/?probe=9f98c80601) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Panasonic     | CF-191HACHFG                | [c1f0177dcb](https://linux-hardware.org/?probe=c1f0177dcb) | Sep 01, 2022 |
| BESSTAR Te... | X400                        | [ab70086ae7](https://linux-hardware.org/?probe=ab70086ae7) | Aug 27, 2022 |
| Fujitsu       | LIFEBOOK E752               | [adf76251c5](https://linux-hardware.org/?probe=adf76251c5) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | [7c7a83f951](https://linux-hardware.org/?probe=7c7a83f951) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| HP            | 250 G7 Notebook PC          | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| TrekStor      | Notebook Slim S130          | [2b5689655d](https://linux-hardware.org/?probe=2b5689655d) | Aug 16, 2022 |
| TrekStor      | Notebook Slim S130          | [baf685c170](https://linux-hardware.org/?probe=baf685c170) | Aug 16, 2022 |
| VALE          | Notebook Classic C170       | [e1563aa775](https://linux-hardware.org/?probe=e1563aa775) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | [ce03a2383e](https://linux-hardware.org/?probe=ce03a2383e) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | [cb10c34587](https://linux-hardware.org/?probe=cb10c34587) | Aug 15, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [4a52da1c38](https://linux-hardware.org/?probe=4a52da1c38) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | [f71b1992c9](https://linux-hardware.org/?probe=f71b1992c9) | Aug 13, 2022 |
| BESSTAR Te... | X400                        | [e8424e153d](https://linux-hardware.org/?probe=e8424e153d) | Aug 12, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [0f33fa05f5](https://linux-hardware.org/?probe=0f33fa05f5) | Aug 10, 2022 |
| AMI           | Intel                       | [8d8db9dc8b](https://linux-hardware.org/?probe=8d8db9dc8b) | Aug 09, 2022 |
| AMI           | Intel                       | [0958b0a578](https://linux-hardware.org/?probe=0958b0a578) | Aug 09, 2022 |
| ASUSTek       | N56VZ                       | [3ee621b609](https://linux-hardware.org/?probe=3ee621b609) | Aug 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Dell          | Latitude E5550              | [c1d9204443](https://linux-hardware.org/?probe=c1d9204443) | Aug 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [91998a6bfe](https://linux-hardware.org/?probe=91998a6bfe) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [8f934de8ef](https://linux-hardware.org/?probe=8f934de8ef) | Aug 03, 2022 |
| Dell          | Latitude E6430              | [82abc4b330](https://linux-hardware.org/?probe=82abc4b330) | Aug 03, 2022 |
| Sony          | VGN-FW51ZF_H                | [f42e9458c7](https://linux-hardware.org/?probe=f42e9458c7) | Jul 31, 2022 |
| Toshiba       | Satellite L70-B             | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Acer          | Aspire 3810T                | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| ASUSTek       | X556UQK                     | [3e6c333747](https://linux-hardware.org/?probe=3e6c333747) | Jul 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [f611683c8a](https://linux-hardware.org/?probe=f611683c8a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [bad36e8ab5](https://linux-hardware.org/?probe=bad36e8ab5) | Jul 19, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | [b8220c7bb8](https://linux-hardware.org/?probe=b8220c7bb8) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| ASUSTek       | UX31E                       | [b3059e0094](https://linux-hardware.org/?probe=b3059e0094) | Jul 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | [01fae3a07c](https://linux-hardware.org/?probe=01fae3a07c) | Jul 15, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6606cb7d46](https://linux-hardware.org/?probe=6606cb7d46) | Jul 06, 2022 |
| Sony          | VPCEH2J1E                   | [e51b908744](https://linux-hardware.org/?probe=e51b908744) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| AXDIA Inte... | WINPAD 12                   | [c263197569](https://linux-hardware.org/?probe=c263197569) | Jul 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Clevo         | Modified by dsanke          | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | [e18983e0d8](https://linux-hardware.org/?probe=e18983e0d8) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | [d59ef2842d](https://linux-hardware.org/?probe=d59ef2842d) | Jun 21, 2022 |
| Razer         | Blade 15 Advanced Model ... | [de5d975c12](https://linux-hardware.org/?probe=de5d975c12) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [bfc7b65dee](https://linux-hardware.org/?probe=bfc7b65dee) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eb60cda77f](https://linux-hardware.org/?probe=eb60cda77f) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Acer          | Aspire A515-44G             | [f07dc47259](https://linux-hardware.org/?probe=f07dc47259) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6db07f5434](https://linux-hardware.org/?probe=6db07f5434) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| Valve         | Jupiter                     | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| HP            | ProBook 450 G6              | [898eff4fae](https://linux-hardware.org/?probe=898eff4fae) | Jun 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [5ad950659b](https://linux-hardware.org/?probe=5ad950659b) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [24da0cf09c](https://linux-hardware.org/?probe=24da0cf09c) | Jun 06, 2022 |
| Acer          | Swift SFX14-41G             | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Dell          | Latitude 5520               | [03622600a8](https://linux-hardware.org/?probe=03622600a8) | May 30, 2022 |
| Dell          | Latitude E6410              | [72345f9352](https://linux-hardware.org/?probe=72345f9352) | May 28, 2022 |
| HP            | ProBook 470 G4              | [6049c10c3c](https://linux-hardware.org/?probe=6049c10c3c) | May 28, 2022 |
| System76      | Lemur Pro                   | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| Valve         | Jupiter                     | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| Dell          | Latitude E6410              | [39be06dd23](https://linux-hardware.org/?probe=39be06dd23) | May 19, 2022 |
| Acer          | Extensa 2509                | [46df59d8b3](https://linux-hardware.org/?probe=46df59d8b3) | May 19, 2022 |
| Acer          | Aspire A515-51G             | [9a945a6cf5](https://linux-hardware.org/?probe=9a945a6cf5) | May 17, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [b28d047360](https://linux-hardware.org/?probe=b28d047360) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [36ccfac84d](https://linux-hardware.org/?probe=36ccfac84d) | May 14, 2022 |
| Valve         | Jupiter                     | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [d3d6871bf7](https://linux-hardware.org/?probe=d3d6871bf7) | May 12, 2022 |
| Dell          | Latitude 5520               | [927a4b0ed0](https://linux-hardware.org/?probe=927a4b0ed0) | May 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [17dda821a0](https://linux-hardware.org/?probe=17dda821a0) | May 11, 2022 |
| Apple         | MacBook1,1                  | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Dell          | XPS 13 9310                 | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Dell          | Latitude E6430              | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| HP            | ZBook 17 G5                 | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | [0bc5a5fb9f](https://linux-hardware.org/?probe=0bc5a5fb9f) | May 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Sony          | VPCEH2J1E                   | [86f6b8c750](https://linux-hardware.org/?probe=86f6b8c750) | Apr 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Fujitsu       | LIFEBOOK E751               | [ace84bb1e5](https://linux-hardware.org/?probe=ace84bb1e5) | Apr 25, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [a8038d3972](https://linux-hardware.org/?probe=a8038d3972) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [bbc4928d39](https://linux-hardware.org/?probe=bbc4928d39) | Apr 19, 2022 |
| Apple         | MacBookPro9,2               | [812afb255a](https://linux-hardware.org/?probe=812afb255a) | Apr 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [b228a9bf01](https://linux-hardware.org/?probe=b228a9bf01) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c68c62f98c](https://linux-hardware.org/?probe=c68c62f98c) | Apr 14, 2022 |
| Medion        | X6816                       | [41350ad402](https://linux-hardware.org/?probe=41350ad402) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [ac82d62350](https://linux-hardware.org/?probe=ac82d62350) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [60a1fc5c39](https://linux-hardware.org/?probe=60a1fc5c39) | Apr 12, 2022 |
| TUXEDO        | P65xHP                      | [a29da5ce79](https://linux-hardware.org/?probe=a29da5ce79) | Apr 11, 2022 |
| Acer          | Aspire A114-31              | [8779ba2891](https://linux-hardware.org/?probe=8779ba2891) | Apr 09, 2022 |
| Acer          | Aspire A114-31              | [298acab48c](https://linux-hardware.org/?probe=298acab48c) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [0b5e11625d](https://linux-hardware.org/?probe=0b5e11625d) | Apr 08, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fed3e90b10](https://linux-hardware.org/?probe=fed3e90b10) | Apr 08, 2022 |
| HP            | Pavilion dv6                | [b69de03677](https://linux-hardware.org/?probe=b69de03677) | Apr 06, 2022 |
| HP            | Pavilion dv6                | [9e8312e9c1](https://linux-hardware.org/?probe=9e8312e9c1) | Apr 06, 2022 |
| Dell          | XPS 13 9305                 | [0e254bc578](https://linux-hardware.org/?probe=0e254bc578) | Apr 05, 2022 |
| Medion        | E7216                       | [58f12f9e91](https://linux-hardware.org/?probe=58f12f9e91) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [edf4c472c3](https://linux-hardware.org/?probe=edf4c472c3) | Apr 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [35e0c67fed](https://linux-hardware.org/?probe=35e0c67fed) | Apr 03, 2022 |
| Acer          | TravelMate 7730             | [c0c1bedcec](https://linux-hardware.org/?probe=c0c1bedcec) | Apr 03, 2022 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [869407eb01](https://linux-hardware.org/?probe=869407eb01) | Apr 03, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [26082e6921](https://linux-hardware.org/?probe=26082e6921) | Apr 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [0f191252cb](https://linux-hardware.org/?probe=0f191252cb) | Apr 02, 2022 |
| MSI           | Bravo 17 A4DDR              | [590d188f5d](https://linux-hardware.org/?probe=590d188f5d) | Apr 01, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Acer          | TravelMate 7730             | [6cabffccbe](https://linux-hardware.org/?probe=6cabffccbe) | Mar 30, 2022 |
| TUXEDO        | N7x0WU                      | [cf4f31fe3c](https://linux-hardware.org/?probe=cf4f31fe3c) | Mar 30, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Sony          | VPCEH2J1E                   | [23d5b99aca](https://linux-hardware.org/?probe=23d5b99aca) | Mar 27, 2022 |
| Acer          | Nitro AN515-45              | [c6fa89e81f](https://linux-hardware.org/?probe=c6fa89e81f) | Mar 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [76b97dcfe7](https://linux-hardware.org/?probe=76b97dcfe7) | Mar 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [ec3089df82](https://linux-hardware.org/?probe=ec3089df82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| HP            | Pavilion dv7                | [64d5f14244](https://linux-hardware.org/?probe=64d5f14244) | Mar 22, 2022 |
| HP            | Pavilion dv7                | [e2bfdae482](https://linux-hardware.org/?probe=e2bfdae482) | Mar 22, 2022 |
| MSI           | Modern 14 B10MW             | [e8bbca6adf](https://linux-hardware.org/?probe=e8bbca6adf) | Mar 21, 2022 |
| Fujitsu Si... | AMILO Pro Edition V3545     | [be2c23f4a5](https://linux-hardware.org/?probe=be2c23f4a5) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Medion        | E14410                      | [800f98d1ef](https://linux-hardware.org/?probe=800f98d1ef) | Mar 21, 2022 |
| Sony          | VPCEH2J1E                   | [ae54fc4033](https://linux-hardware.org/?probe=ae54fc4033) | Mar 19, 2022 |
| ASUSTek       | X201EP                      | [864fc80ac3](https://linux-hardware.org/?probe=864fc80ac3) | Mar 17, 2022 |
| MSI           | Alpha 15 B5EEK              | [f4c72eaa35](https://linux-hardware.org/?probe=f4c72eaa35) | Mar 15, 2022 |
| MSI           | Alpha 15 B5EEK              | [8859888f0c](https://linux-hardware.org/?probe=8859888f0c) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [1aa06e7b53](https://linux-hardware.org/?probe=1aa06e7b53) | Mar 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e2eacd6969](https://linux-hardware.org/?probe=e2eacd6969) | Mar 12, 2022 |
| Lenovo        | ThinkPad E15 20RES12P00     | [200b3a0b69](https://linux-hardware.org/?probe=200b3a0b69) | Mar 12, 2022 |
| ASUSTek       | UX303LAB                    | [f3d0e8fbea](https://linux-hardware.org/?probe=f3d0e8fbea) | Mar 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [adf7b6c95e](https://linux-hardware.org/?probe=adf7b6c95e) | Mar 10, 2022 |
| ASUSTek       | UX305FA                     | [f1641a436c](https://linux-hardware.org/?probe=f1641a436c) | Mar 09, 2022 |
| Dell          | Vostro 5471                 | [6e46455791](https://linux-hardware.org/?probe=6e46455791) | Mar 09, 2022 |
| Sony          | VPCEH2J1E                   | [713f08757a](https://linux-hardware.org/?probe=713f08757a) | Mar 09, 2022 |
| HP            | EliteBook 850 G1            | [b2aeea55e5](https://linux-hardware.org/?probe=b2aeea55e5) | Mar 07, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | Pavilion g6                 | [e9b1f4c1ec](https://linux-hardware.org/?probe=e9b1f4c1ec) | Mar 03, 2022 |
| HP            | Pavilion g6                 | [f378d8a1df](https://linux-hardware.org/?probe=f378d8a1df) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| Toshiba       | Satellite L775-166          | [f0ad0a4da5](https://linux-hardware.org/?probe=f0ad0a4da5) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [16281a52e8](https://linux-hardware.org/?probe=16281a52e8) | Feb 26, 2022 |
| Toshiba       | Satellite P500              | [980cb1d4af](https://linux-hardware.org/?probe=980cb1d4af) | Feb 25, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [6bf461797c](https://linux-hardware.org/?probe=6bf461797c) | Feb 25, 2022 |
| HP            | ZBook 15 G3                 | [7b9e3082bf](https://linux-hardware.org/?probe=7b9e3082bf) | Feb 25, 2022 |
| HP            | EliteBook 820 G1            | [916b00f114](https://linux-hardware.org/?probe=916b00f114) | Feb 24, 2022 |
| Lenovo        | IdeaPad S206 2638           | [84772cc34d](https://linux-hardware.org/?probe=84772cc34d) | Feb 23, 2022 |
| HP            | EliteBook 6930p             | [82000c3346](https://linux-hardware.org/?probe=82000c3346) | Feb 22, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Acer          | Aspire A517-51              | [997108b078](https://linux-hardware.org/?probe=997108b078) | Feb 19, 2022 |
| Acer          | Aspire E1-572G              | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| HP            | EliteBook 840 G1            | [3047069a4f](https://linux-hardware.org/?probe=3047069a4f) | Feb 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [934591472d](https://linux-hardware.org/?probe=934591472d) | Feb 16, 2022 |
| Dell          | XPS 15 9550                 | [701eeea0ed](https://linux-hardware.org/?probe=701eeea0ed) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [32022a8232](https://linux-hardware.org/?probe=32022a8232) | Feb 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [372c231b58](https://linux-hardware.org/?probe=372c231b58) | Feb 14, 2022 |
| Acer          | Swift SF114-34              | [31d020671e](https://linux-hardware.org/?probe=31d020671e) | Feb 13, 2022 |
| Lenovo        | ThinkPad X230T 34382AG      | [bec561800f](https://linux-hardware.org/?probe=bec561800f) | Feb 13, 2022 |
| HP            | ProBook 4730s               | [2a3ff15659](https://linux-hardware.org/?probe=2a3ff15659) | Feb 12, 2022 |
| HP            | Compaq 15                   | [78b2f3bfa6](https://linux-hardware.org/?probe=78b2f3bfa6) | Feb 11, 2022 |
| Acer          | Aspire A315-54              | [d4e5b617c7](https://linux-hardware.org/?probe=d4e5b617c7) | Feb 10, 2022 |
| Fujitsu       | LIFEBOOK E559               | [66696218c1](https://linux-hardware.org/?probe=66696218c1) | Feb 09, 2022 |
| Fujitsu       | LIFEBOOK S751               | [42d5c28f38](https://linux-hardware.org/?probe=42d5c28f38) | Feb 09, 2022 |
| Medion        | P6402 MD60800               | [a749ba246d](https://linux-hardware.org/?probe=a749ba246d) | Feb 08, 2022 |
| HP            | ProBook 450 G2              | [57c513ecbc](https://linux-hardware.org/?probe=57c513ecbc) | Feb 08, 2022 |
| Acer          | Predator G9-792             | [8404f2e6d1](https://linux-hardware.org/?probe=8404f2e6d1) | Feb 08, 2022 |
| HP            | EliteBook 840 G3            | [82d892f3e5](https://linux-hardware.org/?probe=82d892f3e5) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Acer          | TravelMate 5720             | [9db7cd9351](https://linux-hardware.org/?probe=9db7cd9351) | Feb 06, 2022 |
| Chuwi         | HeroBook Pro                | [9f5da53181](https://linux-hardware.org/?probe=9f5da53181) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Acer          | Swift SF314-54              | [d11fb8c7b6](https://linux-hardware.org/?probe=d11fb8c7b6) | Feb 04, 2022 |
| Acer          | Aspire A114-31              | [caa9365785](https://linux-hardware.org/?probe=caa9365785) | Feb 04, 2022 |
| Sony          | VPCEH2J1E                   | [f5ed0cbaa4](https://linux-hardware.org/?probe=f5ed0cbaa4) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [5a1723f28e](https://linux-hardware.org/?probe=5a1723f28e) | Feb 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [7db46606ab](https://linux-hardware.org/?probe=7db46606ab) | Feb 04, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [376503f06d](https://linux-hardware.org/?probe=376503f06d) | Feb 03, 2022 |
| HP            | ProBook 4310s               | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | ThinkPad X280 20KF001GGE    | [f076061f22](https://linux-hardware.org/?probe=f076061f22) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| Acer          | Aspire E1-571G              | [440bc30637](https://linux-hardware.org/?probe=440bc30637) | Jan 31, 2022 |
| Acer          | Aspire E1-571G              | [dd2d541140](https://linux-hardware.org/?probe=dd2d541140) | Jan 31, 2022 |
| Dell          | XPS M1530                   | [4b402569cc](https://linux-hardware.org/?probe=4b402569cc) | Jan 29, 2022 |
| Acer          | Predator G9-792             | [863bce4abe](https://linux-hardware.org/?probe=863bce4abe) | Jan 28, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5edb2eb3](https://linux-hardware.org/?probe=4d5edb2eb3) | Jan 25, 2022 |
| Lenovo        | ThinkPad T495 20NJS0KB00    | [e92c44b58a](https://linux-hardware.org/?probe=e92c44b58a) | Jan 24, 2022 |
| Dell          | Inspiron 1720               | [0b6d89660a](https://linux-hardware.org/?probe=0b6d89660a) | Jan 24, 2022 |
| Lenovo        | Yoga 500-15IBD 80N6         | [46a5cef815](https://linux-hardware.org/?probe=46a5cef815) | Jan 23, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | [e9f3d5c785](https://linux-hardware.org/?probe=e9f3d5c785) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [e19ee364b0](https://linux-hardware.org/?probe=e19ee364b0) | Jan 21, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [a0399b1c6b](https://linux-hardware.org/?probe=a0399b1c6b) | Jan 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0410ba28b0](https://linux-hardware.org/?probe=0410ba28b0) | Jan 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [24c10d9f2d](https://linux-hardware.org/?probe=24c10d9f2d) | Jan 20, 2022 |
| Acer          | Nitro AN515-44              | [f45a7eb0bb](https://linux-hardware.org/?probe=f45a7eb0bb) | Jan 20, 2022 |
| Acer          | Swift SF114-34              | [7ea8fc4686](https://linux-hardware.org/?probe=7ea8fc4686) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [5ba89b6e26](https://linux-hardware.org/?probe=5ba89b6e26) | Jan 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fca800793f](https://linux-hardware.org/?probe=fca800793f) | Jan 18, 2022 |
| Lenovo        | ThinkPad T560 20FJS2PN00    | [11340212f2](https://linux-hardware.org/?probe=11340212f2) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| Dell          | XPS 15 9570                 | [b8d4a9ee87](https://linux-hardware.org/?probe=b8d4a9ee87) | Jan 17, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [dd69f44bab](https://linux-hardware.org/?probe=dd69f44bab) | Jan 15, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| Medion        | CRAWLER E10                 | [d658e7cd88](https://linux-hardware.org/?probe=d658e7cd88) | Jan 13, 2022 |
| HP            | EliteBook 1030 G1           | [73839f5dd5](https://linux-hardware.org/?probe=73839f5dd5) | Jan 09, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f212038b15](https://linux-hardware.org/?probe=f212038b15) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| HP            | Laptop 15-db1xxx            | [28db094e56](https://linux-hardware.org/?probe=28db094e56) | Jan 08, 2022 |
| Lenovo        | IdeaPad 3 17ARE05 81W5      | [2dbdfe4883](https://linux-hardware.org/?probe=2dbdfe4883) | Jan 08, 2022 |
| Dell          | Vostro 5370                 | [0d027d4b84](https://linux-hardware.org/?probe=0d027d4b84) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| HP            | Laptop 17-ak0xx             | [fee6068743](https://linux-hardware.org/?probe=fee6068743) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| HP            | EliteBook 8540p             | [a321b2cfd9](https://linux-hardware.org/?probe=a321b2cfd9) | Jan 03, 2022 |
| HP            | EliteBook 8540p             | [6130b11204](https://linux-hardware.org/?probe=6130b11204) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| TUXEDO        | P65_67HSHP                  | [4d448637c0](https://linux-hardware.org/?probe=4d448637c0) | Jan 02, 2022 |
| ASUSTek       | N50Vn                       | [8fadb8c7af](https://linux-hardware.org/?probe=8fadb8c7af) | Jan 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS05V0... | [7c496e685d](https://linux-hardware.org/?probe=7c496e685d) | Dec 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [5095c47f07](https://linux-hardware.org/?probe=5095c47f07) | Dec 29, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [1724d0d357](https://linux-hardware.org/?probe=1724d0d357) | Dec 26, 2021 |
| HP            | ProBook 470 G1              | [0e99096fe2](https://linux-hardware.org/?probe=0e99096fe2) | Dec 26, 2021 |
| Dell          | Inspiron 3505               | [fe87929ac5](https://linux-hardware.org/?probe=fe87929ac5) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [cb2ae92d82](https://linux-hardware.org/?probe=cb2ae92d82) | Dec 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [492fc37142](https://linux-hardware.org/?probe=492fc37142) | Dec 22, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [d7f3d69923](https://linux-hardware.org/?probe=d7f3d69923) | Dec 21, 2021 |
| HP            | EliteBook 8460p             | [59ec7afd71](https://linux-hardware.org/?probe=59ec7afd71) | Dec 20, 2021 |
| ASUSTek       | GL702ZC                     | [ff27d21705](https://linux-hardware.org/?probe=ff27d21705) | Dec 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [a8713c0bd9](https://linux-hardware.org/?probe=a8713c0bd9) | Dec 18, 2021 |
| MSI           | Modern 14 B10MW             | [1771ceeb4e](https://linux-hardware.org/?probe=1771ceeb4e) | Dec 14, 2021 |
| Dell          | XPS 17 9700                 | [eef9ef9d60](https://linux-hardware.org/?probe=eef9ef9d60) | Dec 12, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [c33bc12a7a](https://linux-hardware.org/?probe=c33bc12a7a) | Dec 11, 2021 |
| Dell          | XPS 17 9700                 | [d5ec843ea7](https://linux-hardware.org/?probe=d5ec843ea7) | Dec 11, 2021 |
| Toshiba       | Satellite L500              | [aaab078915](https://linux-hardware.org/?probe=aaab078915) | Dec 11, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [ec9930ae99](https://linux-hardware.org/?probe=ec9930ae99) | Dec 11, 2021 |
| HP            | ZBook Firefly 15 inch G8... | [f2bfaaf185](https://linux-hardware.org/?probe=f2bfaaf185) | Dec 11, 2021 |
| Dell          | XPS M1530                   | [ad4bfb0cbd](https://linux-hardware.org/?probe=ad4bfb0cbd) | Dec 08, 2021 |
| HP            | Pavilion dv6                | [9dd21ffaf4](https://linux-hardware.org/?probe=9dd21ffaf4) | Dec 08, 2021 |
| Medion        | P7624                       | [05d0f23734](https://linux-hardware.org/?probe=05d0f23734) | Dec 08, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [600faccbe5](https://linux-hardware.org/?probe=600faccbe5) | Dec 07, 2021 |
| ASUSTek       | T100HAN                     | [9ad6409a34](https://linux-hardware.org/?probe=9ad6409a34) | Dec 06, 2021 |
| Dell          | Vostro 5471                 | [0d989a4f1f](https://linux-hardware.org/?probe=0d989a4f1f) | Dec 05, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42844LG       | [cd254ead05](https://linux-hardware.org/?probe=cd254ead05) | Dec 04, 2021 |
| HP            | ProBook 470 G1              | [4359617795](https://linux-hardware.org/?probe=4359617795) | Dec 03, 2021 |
| Lenovo        | ThinkPad Edge E330 33549... | [d8c1e34c94](https://linux-hardware.org/?probe=d8c1e34c94) | Dec 02, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6204315459](https://linux-hardware.org/?probe=6204315459) | Dec 02, 2021 |
| HP            | Pavilion dv6                | [640e1f0491](https://linux-hardware.org/?probe=640e1f0491) | Dec 01, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [d77b252a78](https://linux-hardware.org/?probe=d77b252a78) | Dec 01, 2021 |
| Acer          | Swift SF314-42              | [c77012b538](https://linux-hardware.org/?probe=c77012b538) | Nov 30, 2021 |
| HP            | 625                         | [75b1dd3ee1](https://linux-hardware.org/?probe=75b1dd3ee1) | Nov 29, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Medion        | P15648                      | [1328e63002](https://linux-hardware.org/?probe=1328e63002) | Nov 25, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5632c40eac](https://linux-hardware.org/?probe=5632c40eac) | Nov 24, 2021 |
| HP            | Pavilion g7                 | [c8b8a8bed7](https://linux-hardware.org/?probe=c8b8a8bed7) | Nov 24, 2021 |
| HP            | Pavilion g7                 | [fab49120f0](https://linux-hardware.org/?probe=fab49120f0) | Nov 23, 2021 |
| HP            | ProBook 455 G8 Notebook ... | [56cd58b089](https://linux-hardware.org/?probe=56cd58b089) | Nov 23, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| HP            | ENVY 15                     | [f4752615c9](https://linux-hardware.org/?probe=f4752615c9) | Nov 19, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | [73b9b15b14](https://linux-hardware.org/?probe=73b9b15b14) | Nov 19, 2021 |
| Lenovo        | ThinkPad P50 20EQS15P00     | [4c9b03387c](https://linux-hardware.org/?probe=4c9b03387c) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [915853adf6](https://linux-hardware.org/?probe=915853adf6) | Nov 18, 2021 |
| HP            | Laptop 15-db1xxx            | [cd32f937e9](https://linux-hardware.org/?probe=cd32f937e9) | Nov 17, 2021 |
| Acer          | Aspire 7750G                | [79eb5a8344](https://linux-hardware.org/?probe=79eb5a8344) | Nov 16, 2021 |
| Dell          | Vostro 5471                 | [348b6bc909](https://linux-hardware.org/?probe=348b6bc909) | Nov 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [1976dd6a72](https://linux-hardware.org/?probe=1976dd6a72) | Nov 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [039fb54354](https://linux-hardware.org/?probe=039fb54354) | Nov 12, 2021 |
| HP            | Laptop 15-db1xxx            | [c34d10b1c8](https://linux-hardware.org/?probe=c34d10b1c8) | Nov 12, 2021 |
| Sony          | VPCEH2J1E                   | [02a4a3ea01](https://linux-hardware.org/?probe=02a4a3ea01) | Nov 06, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f0d8cb68f0](https://linux-hardware.org/?probe=f0d8cb68f0) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [f4273d4dc1](https://linux-hardware.org/?probe=f4273d4dc1) | Nov 06, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [86f7bd9873](https://linux-hardware.org/?probe=86f7bd9873) | Nov 06, 2021 |
| Lenovo        | G500s 20245                 | [e16940fe24](https://linux-hardware.org/?probe=e16940fe24) | Nov 05, 2021 |
| Medion        | E6220                       | [45d5f5ec30](https://linux-hardware.org/?probe=45d5f5ec30) | Nov 04, 2021 |
| ASUSTek       | X580VD                      | [2970522382](https://linux-hardware.org/?probe=2970522382) | Nov 01, 2021 |
| Panasonic     | FZG1-3                      | [8a52b831d7](https://linux-hardware.org/?probe=8a52b831d7) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ba228b1ed7](https://linux-hardware.org/?probe=ba228b1ed7) | Oct 31, 2021 |
| Medion        | Akoya S4220 MD99660         | [fd406382b2](https://linux-hardware.org/?probe=fd406382b2) | Oct 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0c865ddf24](https://linux-hardware.org/?probe=0c865ddf24) | Oct 30, 2021 |
| Dell          | Latitude 5490               | [4efdbaeea5](https://linux-hardware.org/?probe=4efdbaeea5) | Oct 30, 2021 |
| Acer          | Aspire A317-33              | [ad0f3b8799](https://linux-hardware.org/?probe=ad0f3b8799) | Oct 24, 2021 |
| Acer          | TravelMate P253             | [d74c10f41f](https://linux-hardware.org/?probe=d74c10f41f) | Oct 24, 2021 |
| Medion        | E7216                       | [f4c7def4b7](https://linux-hardware.org/?probe=f4c7def4b7) | Oct 24, 2021 |
| Medion        | P7624                       | [efc2ccc6a2](https://linux-hardware.org/?probe=efc2ccc6a2) | Oct 24, 2021 |
| HP            | ProBook 430 G5              | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| Lenovo        | ThinkPad T440s 20AQS0090... | [415cc7fe56](https://linux-hardware.org/?probe=415cc7fe56) | Oct 18, 2021 |
| HP            | Pavilion dv6                | [0392f507d0](https://linux-hardware.org/?probe=0392f507d0) | Oct 18, 2021 |
| HP            | Laptop 14s-fq1xxx           | [61d5829888](https://linux-hardware.org/?probe=61d5829888) | Oct 14, 2021 |
| HP            | Laptop 14s-fq1xxx           | [c42ff576c7](https://linux-hardware.org/?probe=c42ff576c7) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| Medion        | P15648                      | [5ea319450e](https://linux-hardware.org/?probe=5ea319450e) | Oct 13, 2021 |
| HP            | Laptop 14s-fq1xxx           | [1e047e7a9a](https://linux-hardware.org/?probe=1e047e7a9a) | Oct 12, 2021 |
| ASUSTek       | N61Jv                       | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [037a558c7d](https://linux-hardware.org/?probe=037a558c7d) | Oct 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [1984f59bbe](https://linux-hardware.org/?probe=1984f59bbe) | Oct 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [a631c78255](https://linux-hardware.org/?probe=a631c78255) | Oct 09, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [b6715f92f7](https://linux-hardware.org/?probe=b6715f92f7) | Oct 08, 2021 |
| Dell          | Latitude E5550              | [a4f8896675](https://linux-hardware.org/?probe=a4f8896675) | Oct 07, 2021 |
| Medion        | E6415 MD99904               | [4b24e7fb1a](https://linux-hardware.org/?probe=4b24e7fb1a) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| ASUSTek       | X556UQK                     | [363c1a3642](https://linux-hardware.org/?probe=363c1a3642) | Oct 03, 2021 |
| Apple         | MacBookPro12,1              | [2a4757a98f](https://linux-hardware.org/?probe=2a4757a98f) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [a7e79f067e](https://linux-hardware.org/?probe=a7e79f067e) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [0b2f645654](https://linux-hardware.org/?probe=0b2f645654) | Sep 30, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [c63b30f0df](https://linux-hardware.org/?probe=c63b30f0df) | Sep 29, 2021 |
| Lenovo        | Z50-70 20354                | [0aef47a401](https://linux-hardware.org/?probe=0aef47a401) | Sep 29, 2021 |
| TUXEDO        | Book BA1510                 | [e408c8fb46](https://linux-hardware.org/?probe=e408c8fb46) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | [ae6c812e4c](https://linux-hardware.org/?probe=ae6c812e4c) | Sep 28, 2021 |
| Acer          | Aspire ES1-332              | [6bbaec4cfc](https://linux-hardware.org/?probe=6bbaec4cfc) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [4850590ac5](https://linux-hardware.org/?probe=4850590ac5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e7f361c688](https://linux-hardware.org/?probe=e7f361c688) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [17bef7f4cf](https://linux-hardware.org/?probe=17bef7f4cf) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Dell          | Latitude E7450              | [f600127ab1](https://linux-hardware.org/?probe=f600127ab1) | Sep 24, 2021 |
| Lenovo        | B575e 368523G               | [f795bbcedc](https://linux-hardware.org/?probe=f795bbcedc) | Sep 22, 2021 |
| HP            | Compaq nc6400 (EH522AV)     | [8e613adf36](https://linux-hardware.org/?probe=8e613adf36) | Sep 22, 2021 |
| Apple         | MacBookPro15,1              | [3a3ccf8143](https://linux-hardware.org/?probe=3a3ccf8143) | Sep 21, 2021 |
| TUXEDO        | N130BU                      | [12a72404ea](https://linux-hardware.org/?probe=12a72404ea) | Sep 18, 2021 |
| Dell          | XPS 13 9305                 | [369e99699a](https://linux-hardware.org/?probe=369e99699a) | Sep 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [318f8d1653](https://linux-hardware.org/?probe=318f8d1653) | Sep 18, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| TUXEDO        | Book BA1510                 | [2397ee987d](https://linux-hardware.org/?probe=2397ee987d) | Sep 15, 2021 |
| Apple         | MacBookPro15,1              | [73bab0d19c](https://linux-hardware.org/?probe=73bab0d19c) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| Lenovo        | ThinkPad E580 20KS0039GE    | [d85ddde9ba](https://linux-hardware.org/?probe=d85ddde9ba) | Sep 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [216f21f8d5](https://linux-hardware.org/?probe=216f21f8d5) | Sep 13, 2021 |
| Dell          | Precision 5540              | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| ASUSTek       | G750JX                      | [185445c775](https://linux-hardware.org/?probe=185445c775) | Sep 12, 2021 |
| Dell          | Latitude E4300              | [4c52be511c](https://linux-hardware.org/?probe=4c52be511c) | Sep 11, 2021 |
| TUXEDO        | N130BU                      | [e81e4cc415](https://linux-hardware.org/?probe=e81e4cc415) | Sep 08, 2021 |
| Medion        | P6618                       | [3fabc658b8](https://linux-hardware.org/?probe=3fabc658b8) | Sep 07, 2021 |
| Unknown       | T3 MRD                      | [e4aff60504](https://linux-hardware.org/?probe=e4aff60504) | Sep 05, 2021 |
| Lenovo        | ThinkPad X130e 06222EU      | [a5822f49a3](https://linux-hardware.org/?probe=a5822f49a3) | Sep 05, 2021 |
| Lenovo        | ThinkPad X270 20HN0016GE    | [cecb5eb453](https://linux-hardware.org/?probe=cecb5eb453) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | [686ecdcfdb](https://linux-hardware.org/?probe=686ecdcfdb) | Sep 04, 2021 |
| Acer          | Aspire A517-52G             | [2d3edcffdd](https://linux-hardware.org/?probe=2d3edcffdd) | Sep 04, 2021 |
| Acer          | Nitro AN517-41              | [5e1633d787](https://linux-hardware.org/?probe=5e1633d787) | Sep 04, 2021 |
| Acer          | Nitro AN517-41              | [37968ff92c](https://linux-hardware.org/?probe=37968ff92c) | Sep 04, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [8c8a4d9cdf](https://linux-hardware.org/?probe=8c8a4d9cdf) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [bb2bba4301](https://linux-hardware.org/?probe=bb2bba4301) | Aug 31, 2021 |
| Apple         | MacBookPro8,1               | [cf9595f120](https://linux-hardware.org/?probe=cf9595f120) | Aug 31, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [2db9a5db96](https://linux-hardware.org/?probe=2db9a5db96) | Aug 29, 2021 |
| ASUSTek       | X556UQK                     | [e0132c63a3](https://linux-hardware.org/?probe=e0132c63a3) | Aug 29, 2021 |
| Medion        | P6618                       | [39c6d2480b](https://linux-hardware.org/?probe=39c6d2480b) | Aug 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [39ae07c4d8](https://linux-hardware.org/?probe=39ae07c4d8) | Aug 27, 2021 |
| Apple         | MacBookPro8,1               | [c7926f6e27](https://linux-hardware.org/?probe=c7926f6e27) | Aug 27, 2021 |
| HP            | 655                         | [31397c6fa8](https://linux-hardware.org/?probe=31397c6fa8) | Aug 27, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | UX305CA                     | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| Apple         | MacBookPro15,1              | [c797030409](https://linux-hardware.org/?probe=c797030409) | Aug 17, 2021 |
| MSI           | GE63VR 7RF                  | [d7bffa1592](https://linux-hardware.org/?probe=d7bffa1592) | Aug 15, 2021 |
| Acer          | Aspire 7750G                | [33750f4d18](https://linux-hardware.org/?probe=33750f4d18) | Aug 14, 2021 |
| Acer          | Aspire 7750G                | [0a59ad8e86](https://linux-hardware.org/?probe=0a59ad8e86) | Aug 14, 2021 |
| MSI           | GE63VR 7RF                  | [15a5918df5](https://linux-hardware.org/?probe=15a5918df5) | Aug 12, 2021 |
| Dell          | Precision 7550              | [4fc8f5c8e5](https://linux-hardware.org/?probe=4fc8f5c8e5) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Apple         | MacBookAir7,2               | [54ca114d0c](https://linux-hardware.org/?probe=54ca114d0c) | Aug 10, 2021 |
| Acer          | AO531h                      | [f677e6e910](https://linux-hardware.org/?probe=f677e6e910) | Aug 09, 2021 |
| Acer          | AO531h                      | [42bc030846](https://linux-hardware.org/?probe=42bc030846) | Aug 09, 2021 |
| Acer          | AO531h                      | [3475d2f343](https://linux-hardware.org/?probe=3475d2f343) | Aug 09, 2021 |
| Acer          | Aspire E1-531               | [b26c826616](https://linux-hardware.org/?probe=b26c826616) | Aug 08, 2021 |
| Acer          | Aspire E1-531               | [e3f2ac2973](https://linux-hardware.org/?probe=e3f2ac2973) | Aug 08, 2021 |
| Apple         | MacBookAir6,1               | [5bf397d9fa](https://linux-hardware.org/?probe=5bf397d9fa) | Aug 08, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [dff1b9d6eb](https://linux-hardware.org/?probe=dff1b9d6eb) | Aug 07, 2021 |
| Acer          | Aspire ES1-511              | [d8963041b5](https://linux-hardware.org/?probe=d8963041b5) | Aug 06, 2021 |
| Dell          | Latitude E4300              | [2e5aebdfe9](https://linux-hardware.org/?probe=2e5aebdfe9) | Aug 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [b83cac3113](https://linux-hardware.org/?probe=b83cac3113) | Aug 03, 2021 |
| Teclast       | F15S                        | [68bbf00d14](https://linux-hardware.org/?probe=68bbf00d14) | Jul 31, 2021 |
| HP            | ProBook 4740s               | [ac069e99cf](https://linux-hardware.org/?probe=ac069e99cf) | Jul 30, 2021 |
| HP            | ProBook 4740s               | [a5251f5930](https://linux-hardware.org/?probe=a5251f5930) | Jul 30, 2021 |
| TENKU         | SB14                        | [b59b680689](https://linux-hardware.org/?probe=b59b680689) | Jul 30, 2021 |
| Lenovo        | ThinkPad P51 20HJS0D107     | [7100544202](https://linux-hardware.org/?probe=7100544202) | Jul 29, 2021 |
| Razer         | Blade 14 - RZ09-0370        | [3927a38ae3](https://linux-hardware.org/?probe=3927a38ae3) | Jul 28, 2021 |
| Dell          | XPS M1530                   | [30b7f582ce](https://linux-hardware.org/?probe=30b7f582ce) | Jul 27, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [d1e3a988b1](https://linux-hardware.org/?probe=d1e3a988b1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | [5ca74a5c0a](https://linux-hardware.org/?probe=5ca74a5c0a) | Jul 22, 2021 |
| Dell          | Latitude E6320              | [f4460165a4](https://linux-hardware.org/?probe=f4460165a4) | Jul 22, 2021 |
| Timi          | A35S                        | [203b3229da](https://linux-hardware.org/?probe=203b3229da) | Jul 20, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Dell          | Latitude E7470              | [d4985046b7](https://linux-hardware.org/?probe=d4985046b7) | Jul 15, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [36f192a564](https://linux-hardware.org/?probe=36f192a564) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | [5292f36e16](https://linux-hardware.org/?probe=5292f36e16) | Jul 15, 2021 |
| HP            | ZBook 17 G5                 | [3367527048](https://linux-hardware.org/?probe=3367527048) | Jul 15, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [5676714ec9](https://linux-hardware.org/?probe=5676714ec9) | Jul 14, 2021 |
| HP            | EliteBook 1030 G1           | [6c60248fbc](https://linux-hardware.org/?probe=6c60248fbc) | Jul 11, 2021 |
| ASUSTek       | K95VB                       | [ee4aa23d71](https://linux-hardware.org/?probe=ee4aa23d71) | Jul 11, 2021 |
| HP            | EliteBook 8570p             | [f4d41192b1](https://linux-hardware.org/?probe=f4d41192b1) | Jul 10, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b411603809](https://linux-hardware.org/?probe=b411603809) | Jul 10, 2021 |
| Lenovo        | ThinkPad T470s 20HGS45C0... | [afc9280a07](https://linux-hardware.org/?probe=afc9280a07) | Jul 09, 2021 |
| Dell          | Precision 5530              | [a2698d4e69](https://linux-hardware.org/?probe=a2698d4e69) | Jul 07, 2021 |
| Sony          | VPCEH2J1E                   | [dcad426e53](https://linux-hardware.org/?probe=dcad426e53) | Jul 06, 2021 |
| Sony          | VPCEH2J1E                   | [d9c094da9f](https://linux-hardware.org/?probe=d9c094da9f) | Jul 05, 2021 |
| HP            | ProBook 430 G2              | [82608fa1f4](https://linux-hardware.org/?probe=82608fa1f4) | Jul 04, 2021 |
| HP            | ProBook 430 G2              | [73af72bee1](https://linux-hardware.org/?probe=73af72bee1) | Jul 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [048d10c013](https://linux-hardware.org/?probe=048d10c013) | Jul 04, 2021 |
| Acer          | Aspire V5-573G              | [eef9527dd8](https://linux-hardware.org/?probe=eef9527dd8) | Jul 04, 2021 |
| Toshiba       | QOSMIO X70-B                | [dcec6c2c5f](https://linux-hardware.org/?probe=dcec6c2c5f) | Jul 02, 2021 |
| Acer          | Aspire V5-573G              | [243f7cf95e](https://linux-hardware.org/?probe=243f7cf95e) | Jul 01, 2021 |
| Acer          | Aspire E5-575G              | [698f108789](https://linux-hardware.org/?probe=698f108789) | Jun 29, 2021 |
| Acer          | Aspire V5-573G              | [5b40b1a1a3](https://linux-hardware.org/?probe=5b40b1a1a3) | Jun 27, 2021 |
| Sony          | VGN-CR42S_W                 | [26b02ccda4](https://linux-hardware.org/?probe=26b02ccda4) | Jun 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [71134cd640](https://linux-hardware.org/?probe=71134cd640) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [7c679b05c3](https://linux-hardware.org/?probe=7c679b05c3) | Jun 25, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [2bf10c3d80](https://linux-hardware.org/?probe=2bf10c3d80) | Jun 19, 2021 |
| HP            | EliteBook 8570p             | [f872ec3b49](https://linux-hardware.org/?probe=f872ec3b49) | Jun 18, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [9f796182e7](https://linux-hardware.org/?probe=9f796182e7) | Jun 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE R7 8... | [b2c24061a6](https://linux-hardware.org/?probe=b2c24061a6) | Jun 13, 2021 |
| Sony          | VGN-NW21MF_P                | [60fc563598](https://linux-hardware.org/?probe=60fc563598) | Jun 12, 2021 |
| Dell          | Precision 5540              | [b21ffd09ff](https://linux-hardware.org/?probe=b21ffd09ff) | Jun 11, 2021 |
| Medion        | P6669 MD60147               | [3ed80daa7b](https://linux-hardware.org/?probe=3ed80daa7b) | Jun 10, 2021 |
| Dell          | Latitude E6400              | [6e177b21bc](https://linux-hardware.org/?probe=6e177b21bc) | Jun 08, 2021 |
| Dell          | Latitude E7450              | [2a06a286c3](https://linux-hardware.org/?probe=2a06a286c3) | Jun 07, 2021 |
| Dell          | Latitude E6540              | [92f0506c6a](https://linux-hardware.org/?probe=92f0506c6a) | Jun 07, 2021 |
| HP            | Unknown                     | [c3e3f15a63](https://linux-hardware.org/?probe=c3e3f15a63) | Jun 05, 2021 |
| LG Electro... | 16Z90P-G.AA76G              | [7a64de799d](https://linux-hardware.org/?probe=7a64de799d) | Jun 03, 2021 |
| Dell          | Latitude E6520              | [4a0a20fd2b](https://linux-hardware.org/?probe=4a0a20fd2b) | Jun 03, 2021 |
| Dell          | Latitude E5550              | [4a4f7af190](https://linux-hardware.org/?probe=4a4f7af190) | Jun 03, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [6c7ee340df](https://linux-hardware.org/?probe=6c7ee340df) | Jun 03, 2021 |
| Acer          | Aspire S7-191               | [0b0c0919e0](https://linux-hardware.org/?probe=0b0c0919e0) | Jun 02, 2021 |
| Apple         | MacBookPro9,2               | [08232b5b75](https://linux-hardware.org/?probe=08232b5b75) | Jun 02, 2021 |
| HP            | EliteBook 2540p             | [d62314d0c2](https://linux-hardware.org/?probe=d62314d0c2) | Jun 01, 2021 |
| Acer          | Aspire E5-575G              | [d8f16e67c0](https://linux-hardware.org/?probe=d8f16e67c0) | Jun 01, 2021 |
| HP            | EliteBook 2560p             | [e96260cfb9](https://linux-hardware.org/?probe=e96260cfb9) | May 31, 2021 |
| TUXEDO        | InfinityBook_S_14_v5        | [36d147c67f](https://linux-hardware.org/?probe=36d147c67f) | May 31, 2021 |
| Acer          | Aspire ES1-511              | [a7aea0a2dd](https://linux-hardware.org/?probe=a7aea0a2dd) | May 30, 2021 |
| Acer          | Aspire ES1-511              | [ac5911f3a7](https://linux-hardware.org/?probe=ac5911f3a7) | May 30, 2021 |
| Medion        | Erazer X7841 MD99556        | [3e6f8e05b4](https://linux-hardware.org/?probe=3e6f8e05b4) | May 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [2ffefbd96c](https://linux-hardware.org/?probe=2ffefbd96c) | May 25, 2021 |
| HP            | EliteBook 1030 G1           | [34cf12674c](https://linux-hardware.org/?probe=34cf12674c) | May 24, 2021 |
| Acer          | Swift SF114-34              | [7747754c25](https://linux-hardware.org/?probe=7747754c25) | May 23, 2021 |
| Acer          | Swift SF114-34              | [b8c61540de](https://linux-hardware.org/?probe=b8c61540de) | May 23, 2021 |
| Toshiba       | Satellite C50D-B            | [7ae2644ef1](https://linux-hardware.org/?probe=7ae2644ef1) | May 20, 2021 |
| Toshiba       | Satellite C50D-B            | [599106595e](https://linux-hardware.org/?probe=599106595e) | May 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [12ffaaefb1](https://linux-hardware.org/?probe=12ffaaefb1) | May 18, 2021 |
| Dell          | XPS 13 7390                 | [e69f835f2b](https://linux-hardware.org/?probe=e69f835f2b) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| HP            | EliteBook 8570p             | [2c31a6309e](https://linux-hardware.org/?probe=2c31a6309e) | May 12, 2021 |
| HP            | EliteBook 8570p             | [6d330f71d0](https://linux-hardware.org/?probe=6d330f71d0) | May 12, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [28f6f5a90b](https://linux-hardware.org/?probe=28f6f5a90b) | May 12, 2021 |
| ASUSTek       | K50IJ                       | [9932cbdd1a](https://linux-hardware.org/?probe=9932cbdd1a) | May 12, 2021 |
| Sony          | VPCEH2D0E                   | [3c201a9337](https://linux-hardware.org/?probe=3c201a9337) | May 11, 2021 |
| Dell          | Venue 11 Pro 7130 MS        | [478ca880ab](https://linux-hardware.org/?probe=478ca880ab) | May 10, 2021 |
| ASUSTek       | K52F                        | [0ff0faf2a5](https://linux-hardware.org/?probe=0ff0faf2a5) | May 07, 2021 |
| Acer          | Swift SF314-42              | [ecb10aec9a](https://linux-hardware.org/?probe=ecb10aec9a) | May 03, 2021 |
| HP            | Pavilion x2 Detachable      | [71120b9356](https://linux-hardware.org/?probe=71120b9356) | May 03, 2021 |
| Lenovo        | G570 4334                   | [e7e1be6de9](https://linux-hardware.org/?probe=e7e1be6de9) | May 01, 2021 |
| Lenovo        | G570 4334                   | [c9ba5be735](https://linux-hardware.org/?probe=c9ba5be735) | May 01, 2021 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cc35722c1f](https://linux-hardware.org/?probe=cc35722c1f) | May 01, 2021 |
| Lenovo        | G505 20240                  | [3b93e825de](https://linux-hardware.org/?probe=3b93e825de) | Apr 29, 2021 |
| Dell          | Latitude E6540              | [b704f13c9d](https://linux-hardware.org/?probe=b704f13c9d) | Apr 29, 2021 |
| Lenovo        | G505 20240                  | [af3eb72485](https://linux-hardware.org/?probe=af3eb72485) | Apr 28, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [190564ec8e](https://linux-hardware.org/?probe=190564ec8e) | Apr 28, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4e842c54ad](https://linux-hardware.org/?probe=4e842c54ad) | Apr 23, 2021 |
| Lenovo        | ThinkPad T430 23511Z0       | [7bea11a2e4](https://linux-hardware.org/?probe=7bea11a2e4) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [7074c51162](https://linux-hardware.org/?probe=7074c51162) | Apr 21, 2021 |
| Toshiba       | Satellite A200              | [3f0ebd44ad](https://linux-hardware.org/?probe=3f0ebd44ad) | Apr 19, 2021 |
| Lenovo        | ThinkPad T430s 2356GW2      | [1a6dcc75f5](https://linux-hardware.org/?probe=1a6dcc75f5) | Apr 19, 2021 |
| Lenovo        | ThinkPad E495 20NEA001GE    | [d7fed90840](https://linux-hardware.org/?probe=d7fed90840) | Apr 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [0fafab787e](https://linux-hardware.org/?probe=0fafab787e) | Apr 19, 2021 |
| Shuttle       | DS67U                       | [f1dff13da7](https://linux-hardware.org/?probe=f1dff13da7) | Apr 18, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [b753c3d9a0](https://linux-hardware.org/?probe=b753c3d9a0) | Apr 16, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [dd3ff8b26e](https://linux-hardware.org/?probe=dd3ff8b26e) | Apr 16, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [763d56e304](https://linux-hardware.org/?probe=763d56e304) | Apr 15, 2021 |
| HP            | EliteBook Folio 9470m       | [9801f1066c](https://linux-hardware.org/?probe=9801f1066c) | Apr 14, 2021 |
| HP            | EliteBook Folio 9470m       | [267c47f371](https://linux-hardware.org/?probe=267c47f371) | Apr 14, 2021 |
| Jumper        | EZpad6                      | [4cd7cb7569](https://linux-hardware.org/?probe=4cd7cb7569) | Apr 13, 2021 |
| Jumper        | EZpad6                      | [5c8abe710b](https://linux-hardware.org/?probe=5c8abe710b) | Apr 13, 2021 |
| Lenovo        | IdeaPad U510 4941           | [96b93bc0f4](https://linux-hardware.org/?probe=96b93bc0f4) | Apr 12, 2021 |
| HP            | Laptop 15-bs1xx             | [44520abad1](https://linux-hardware.org/?probe=44520abad1) | Apr 11, 2021 |
| Acer          | Nitro AN515-44              | [19f0a0eeed](https://linux-hardware.org/?probe=19f0a0eeed) | Apr 10, 2021 |
| Medion        | E7426 MD62150               | [e5a42ec693](https://linux-hardware.org/?probe=e5a42ec693) | Apr 10, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [54d7d9c149](https://linux-hardware.org/?probe=54d7d9c149) | Apr 10, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [3db45eec95](https://linux-hardware.org/?probe=3db45eec95) | Apr 10, 2021 |
| Notebook      | N8xEJEK                     | [4794a1ad98](https://linux-hardware.org/?probe=4794a1ad98) | Apr 09, 2021 |
| Acer          | Nitro AN515-44              | [c9dcfde4e1](https://linux-hardware.org/?probe=c9dcfde4e1) | Apr 09, 2021 |
| Dell          | Latitude 7280               | [1c4da429ac](https://linux-hardware.org/?probe=1c4da429ac) | Apr 09, 2021 |
| HP            | EliteBook 8760w             | [9067d9bf55](https://linux-hardware.org/?probe=9067d9bf55) | Apr 08, 2021 |
| HP            | EliteBook 8760w             | [59247a25b1](https://linux-hardware.org/?probe=59247a25b1) | Apr 07, 2021 |
| Dell          | Precision M6700             | [8a5e6b4598](https://linux-hardware.org/?probe=8a5e6b4598) | Apr 06, 2021 |
| HP            | EliteBook Folio 9480m       | [c878c10e7b](https://linux-hardware.org/?probe=c878c10e7b) | Apr 03, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Medion        | P7402 MD60850               | [0e482f31af](https://linux-hardware.org/?probe=0e482f31af) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [430aae4994](https://linux-hardware.org/?probe=430aae4994) | Mar 27, 2021 |
| ASUSTek       | GL702ZC                     | [b79e897508](https://linux-hardware.org/?probe=b79e897508) | Mar 27, 2021 |
| Lenovo        | Yoga S940-14IIL 81Q8        | [53acf73fdc](https://linux-hardware.org/?probe=53acf73fdc) | Mar 25, 2021 |
| Schenker      | VIA 15 Pro                  | [2773f5141e](https://linux-hardware.org/?probe=2773f5141e) | Mar 24, 2021 |
| ASUSTek       | ZenBook UX392FA_UX392FA     | [bc779456b0](https://linux-hardware.org/?probe=bc779456b0) | Mar 20, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [e143b5b907](https://linux-hardware.org/?probe=e143b5b907) | Mar 17, 2021 |
| Dell          | Latitude E6540              | [1d979a7265](https://linux-hardware.org/?probe=1d979a7265) | Mar 17, 2021 |
| Medion        | Akoya E4214 MD99570         | [45e8b2ad25](https://linux-hardware.org/?probe=45e8b2ad25) | Mar 17, 2021 |
| ASUSTek       | X541NA                      | [c18feddb7b](https://linux-hardware.org/?probe=c18feddb7b) | Mar 15, 2021 |
| Acer          | Aspire 5733Z                | [beb1b7f09e](https://linux-hardware.org/?probe=beb1b7f09e) | Mar 15, 2021 |
| Sony          | VGN-CR42S_W                 | [b45fd47859](https://linux-hardware.org/?probe=b45fd47859) | Mar 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8C... | [199c5a397a](https://linux-hardware.org/?probe=199c5a397a) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HGS45C0... | [8739fea3ef](https://linux-hardware.org/?probe=8739fea3ef) | Mar 14, 2021 |
| Lenovo        | ThinkPad T470s 20HGS45C0... | [b6d9e2c549](https://linux-hardware.org/?probe=b6d9e2c549) | Mar 14, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [ae0a17e8ab](https://linux-hardware.org/?probe=ae0a17e8ab) | Mar 13, 2021 |
| Lenovo        | Yoga S940-14IIL 81Q8        | [4816527f0e](https://linux-hardware.org/?probe=4816527f0e) | Mar 12, 2021 |
| Dell          | Latitude E5470              | [064cf2bccd](https://linux-hardware.org/?probe=064cf2bccd) | Mar 11, 2021 |
| HP            | EliteBook 1030 G1           | [3b865be010](https://linux-hardware.org/?probe=3b865be010) | Mar 09, 2021 |
| Medion        | P6618                       | [70a3be7f75](https://linux-hardware.org/?probe=70a3be7f75) | Mar 06, 2021 |
| Lenovo        | G500 20236                  | [d3f859d949](https://linux-hardware.org/?probe=d3f859d949) | Mar 06, 2021 |
| HP            | EliteBook 840 G1            | [078c01d2d4](https://linux-hardware.org/?probe=078c01d2d4) | Mar 04, 2021 |
| HP            | EliteBook 840 G1            | [4209d1408d](https://linux-hardware.org/?probe=4209d1408d) | Mar 04, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [3621039fbb](https://linux-hardware.org/?probe=3621039fbb) | Mar 04, 2021 |
| Acer          | Aspire 2930 V1.04           | [8ec4fa1849](https://linux-hardware.org/?probe=8ec4fa1849) | Feb 26, 2021 |
| Acer          | Aspire 2930 V1.04           | [4730e616bb](https://linux-hardware.org/?probe=4730e616bb) | Feb 26, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [4b4b633bd6](https://linux-hardware.org/?probe=4b4b633bd6) | Feb 22, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [4376a22c0a](https://linux-hardware.org/?probe=4376a22c0a) | Feb 22, 2021 |
| Apple         | MacBookPro15,1              | [566cc27d41](https://linux-hardware.org/?probe=566cc27d41) | Feb 22, 2021 |
| Apple         | MacBookPro15,1              | [18cb9d83ae](https://linux-hardware.org/?probe=18cb9d83ae) | Feb 22, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| HP            | Compaq 6820s                | [26295aee0f](https://linux-hardware.org/?probe=26295aee0f) | Feb 18, 2021 |
| HP            | Compaq 6820s                | [b8c238fd7a](https://linux-hardware.org/?probe=b8c238fd7a) | Feb 18, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [42cd2866c5](https://linux-hardware.org/?probe=42cd2866c5) | Feb 17, 2021 |
| Toshiba       | Satellite C50D-B            | [4114652578](https://linux-hardware.org/?probe=4114652578) | Feb 16, 2021 |
| Toshiba       | Satellite C50D-B            | [63a04a0d52](https://linux-hardware.org/?probe=63a04a0d52) | Feb 16, 2021 |
| HP            | ProBook 450 G3              | [8b14f78b72](https://linux-hardware.org/?probe=8b14f78b72) | Feb 16, 2021 |
| Toshiba       | Satellite L70-B             | [6ac7d50ce6](https://linux-hardware.org/?probe=6ac7d50ce6) | Feb 15, 2021 |
| Acer          | Chapala                     | [317beca6a3](https://linux-hardware.org/?probe=317beca6a3) | Feb 14, 2021 |
| Acer          | Chapala                     | [42de79c5ac](https://linux-hardware.org/?probe=42de79c5ac) | Feb 14, 2021 |
| Medion        | E7426 MD62150               | [12c4a589c1](https://linux-hardware.org/?probe=12c4a589c1) | Feb 14, 2021 |
| ASUSTek       | F5N                         | [40ca2e2a26](https://linux-hardware.org/?probe=40ca2e2a26) | Feb 14, 2021 |
| Toshiba       | Satellite P300              | [a00049839a](https://linux-hardware.org/?probe=a00049839a) | Feb 13, 2021 |
| Toshiba       | Satellite C855D-12N         | [4c6329a7a2](https://linux-hardware.org/?probe=4c6329a7a2) | Feb 13, 2021 |
| Toshiba       | Satellite C855D-12N         | [8ec19f60ae](https://linux-hardware.org/?probe=8ec19f60ae) | Feb 13, 2021 |
| Lenovo        | V15-ADA 82C7                | [b736631193](https://linux-hardware.org/?probe=b736631193) | Feb 11, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43d2f5786d](https://linux-hardware.org/?probe=43d2f5786d) | Feb 08, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [38992d7b6b](https://linux-hardware.org/?probe=38992d7b6b) | Feb 08, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [fc50e7350b](https://linux-hardware.org/?probe=fc50e7350b) | Feb 07, 2021 |
| Lenovo        | ThinkPad W510 4389W1B       | [ec27151293](https://linux-hardware.org/?probe=ec27151293) | Feb 06, 2021 |
| Acer          | TravelMate P253             | [678af5f2af](https://linux-hardware.org/?probe=678af5f2af) | Feb 06, 2021 |
| HP            | Pavilion x2 Detachable      | [8d05902c8c](https://linux-hardware.org/?probe=8d05902c8c) | Feb 06, 2021 |
| Lenovo        | ThinkPad W530 2447H21       | [9a62d43629](https://linux-hardware.org/?probe=9a62d43629) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [109924ff6a](https://linux-hardware.org/?probe=109924ff6a) | Feb 02, 2021 |
| Lenovo        | ThinkPad T460s 20FAS1TH0... | [2d4882b3f4](https://linux-hardware.org/?probe=2d4882b3f4) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460s 20FAS1TH0... | [bd4071fabf](https://linux-hardware.org/?probe=bd4071fabf) | Feb 01, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [529126337c](https://linux-hardware.org/?probe=529126337c) | Jan 31, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| Dell          | Latitude 5490               | [7747e6a7ea](https://linux-hardware.org/?probe=7747e6a7ea) | Jan 28, 2021 |
| Lenovo        | ThinkPad T410 25376R9       | [2ca383227c](https://linux-hardware.org/?probe=2ca383227c) | Jan 27, 2021 |
| HP            | EliteBook Folio 1040 G3     | [78ae5415c8](https://linux-hardware.org/?probe=78ae5415c8) | Jan 22, 2021 |
| Dell          | XPS 13 9300                 | [c014c04288](https://linux-hardware.org/?probe=c014c04288) | Jan 21, 2021 |
| HP            | Pavilion dv6                | [ab2744120a](https://linux-hardware.org/?probe=ab2744120a) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [8ac8b21edc](https://linux-hardware.org/?probe=8ac8b21edc) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [1fd8dfebee](https://linux-hardware.org/?probe=1fd8dfebee) | Jan 20, 2021 |
| HP            | Pavilion dv6                | [facfb18441](https://linux-hardware.org/?probe=facfb18441) | Jan 20, 2021 |
| Lenovo        | Flex 2-14D 20376            | [a93ecc2faa](https://linux-hardware.org/?probe=a93ecc2faa) | Jan 19, 2021 |
| Apple         | MacBookPro9,2               | [25244fe913](https://linux-hardware.org/?probe=25244fe913) | Jan 19, 2021 |
| Toshiba       | Satellite Pro C660          | [ba0d7bcaf8](https://linux-hardware.org/?probe=ba0d7bcaf8) | Jan 19, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | Pavilion dv6                | [650296bdfb](https://linux-hardware.org/?probe=650296bdfb) | Jan 16, 2021 |
| Dell          | XPS L322X                   | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [6a0bdefe43](https://linux-hardware.org/?probe=6a0bdefe43) | Jan 13, 2021 |
| HP            | ProBook 650 G5              | [d81e73dec0](https://linux-hardware.org/?probe=d81e73dec0) | Jan 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a716890bba](https://linux-hardware.org/?probe=a716890bba) | Jan 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [cc4b76d3f9](https://linux-hardware.org/?probe=cc4b76d3f9) | Jan 12, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [d292578866](https://linux-hardware.org/?probe=d292578866) | Jan 11, 2021 |
| Dell          | XPS 13 9310                 | [ac8d0ac299](https://linux-hardware.org/?probe=ac8d0ac299) | Jan 11, 2021 |
| TUXEDO        | P65_67HSHP                  | [ac1abdaf6f](https://linux-hardware.org/?probe=ac1abdaf6f) | Jan 10, 2021 |
| ASUSTek       | K53SC                       | [5bdf46531d](https://linux-hardware.org/?probe=5bdf46531d) | Jan 09, 2021 |
| ASUSTek       | K53SC                       | [14e9aa89c7](https://linux-hardware.org/?probe=14e9aa89c7) | Jan 09, 2021 |
| HP            | EliteBook 840 G3            | [37610922c3](https://linux-hardware.org/?probe=37610922c3) | Jan 06, 2021 |
| Lenovo        | ThinkPad X250 20CLS78300    | [fd874fe822](https://linux-hardware.org/?probe=fd874fe822) | Jan 06, 2021 |
| Sony          | VPCEH2J1E                   | [6ef61078ae](https://linux-hardware.org/?probe=6ef61078ae) | Jan 05, 2021 |
| Sony          | VPCEH2J1E                   | [a063086db9](https://linux-hardware.org/?probe=a063086db9) | Jan 05, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [892e0a235f](https://linux-hardware.org/?probe=892e0a235f) | Jan 05, 2021 |
| HP            | EliteBook 840 G3            | [e6886a3a33](https://linux-hardware.org/?probe=e6886a3a33) | Jan 04, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0f2ae77a6d](https://linux-hardware.org/?probe=0f2ae77a6d) | Jan 04, 2021 |
| Medion        | Erazer X7841 MD99556        | [13c1c5ae54](https://linux-hardware.org/?probe=13c1c5ae54) | Jan 04, 2021 |
| Unknown       | Unknown                     | [e702e7abac](https://linux-hardware.org/?probe=e702e7abac) | Jan 04, 2021 |
| HP            | Pavilion dv6                | [6f5046b1ce](https://linux-hardware.org/?probe=6f5046b1ce) | Jan 04, 2021 |
| HP            | EliteBook 8570p             | [387e3e274b](https://linux-hardware.org/?probe=387e3e274b) | Jan 03, 2021 |
| HP            | EliteBook 850 G1            | [60b89588c9](https://linux-hardware.org/?probe=60b89588c9) | Jan 03, 2021 |
| HP            | EliteBook 850 G1            | [eafc5693d2](https://linux-hardware.org/?probe=eafc5693d2) | Jan 03, 2021 |
| ASUSTek       | N501VW                      | [76cb94dddc](https://linux-hardware.org/?probe=76cb94dddc) | Dec 31, 2020 |
| HP            | Presario CQ57               | [351ae067b6](https://linux-hardware.org/?probe=351ae067b6) | Dec 31, 2020 |
| Lenovo        | Flex 2-14D 20376            | [c834f7e438](https://linux-hardware.org/?probe=c834f7e438) | Dec 31, 2020 |
| HP            | Presario CQ57               | [94b74045cc](https://linux-hardware.org/?probe=94b74045cc) | Dec 30, 2020 |
| Acer          | TravelMate 5735Z            | [caca9a9ee2](https://linux-hardware.org/?probe=caca9a9ee2) | Dec 30, 2020 |
| HP            | ZBook 17 G5                 | [f314302d88](https://linux-hardware.org/?probe=f314302d88) | Dec 30, 2020 |
| Wortmann      | Mobile 1745                 | [72f9ad676b](https://linux-hardware.org/?probe=72f9ad676b) | Dec 30, 2020 |
| Wortmann      | Mobile 1745                 | [17db63ebf8](https://linux-hardware.org/?probe=17db63ebf8) | Dec 30, 2020 |
| Dell          | Latitude E6320              | [c4cccf3f47](https://linux-hardware.org/?probe=c4cccf3f47) | Dec 30, 2020 |
| HP            | EliteBook 745 G3            | [ec6c4665e1](https://linux-hardware.org/?probe=ec6c4665e1) | Dec 29, 2020 |
| HP            | EliteBook 745 G3            | [50225c105a](https://linux-hardware.org/?probe=50225c105a) | Dec 29, 2020 |
| TUXEDO        | Pulse 15 Gen1               | [84c045204c](https://linux-hardware.org/?probe=84c045204c) | Dec 28, 2020 |
| Dell          | Inspiron 5570               | [a8dfd61976](https://linux-hardware.org/?probe=a8dfd61976) | Dec 28, 2020 |
| Wortmann      | Mobile 1745                 | [579e27e69b](https://linux-hardware.org/?probe=579e27e69b) | Dec 27, 2020 |
| Dell          | Latitude E7440              | [0f52253e24](https://linux-hardware.org/?probe=0f52253e24) | Dec 25, 2020 |
| Dell          | Inspiron 5570               | [d3732710f8](https://linux-hardware.org/?probe=d3732710f8) | Dec 25, 2020 |
| HP            | Notebook                    | [4264579980](https://linux-hardware.org/?probe=4264579980) | Dec 25, 2020 |
| HP            | Notebook                    | [23299a3071](https://linux-hardware.org/?probe=23299a3071) | Dec 25, 2020 |
| HP            | EliteBook 8570p             | [a85684b0e3](https://linux-hardware.org/?probe=a85684b0e3) | Dec 23, 2020 |
| HP            | EliteBook 8570p             | [625c0af78f](https://linux-hardware.org/?probe=625c0af78f) | Dec 23, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8b65be60d7](https://linux-hardware.org/?probe=8b65be60d7) | Dec 22, 2020 |
| Fujitsu       | LIFEBOOK E756               | [9072367bc6](https://linux-hardware.org/?probe=9072367bc6) | Dec 22, 2020 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [c1f5cdeba9](https://linux-hardware.org/?probe=c1f5cdeba9) | Dec 22, 2020 |
| Apple         | MacBook4,1                  | [0ff1a21e49](https://linux-hardware.org/?probe=0ff1a21e49) | Dec 21, 2020 |
| Dell          | XPS 15 9570                 | [169f75ba5c](https://linux-hardware.org/?probe=169f75ba5c) | Dec 21, 2020 |
| Lenovo        | ThinkPad P70 20ER000EGE     | [6413990c99](https://linux-hardware.org/?probe=6413990c99) | Dec 16, 2020 |
| HP            | EliteBook 840 G3            | [708eaf5602](https://linux-hardware.org/?probe=708eaf5602) | Dec 14, 2020 |
| Dell          | XPS 15 9570                 | [7d337ec9b3](https://linux-hardware.org/?probe=7d337ec9b3) | Dec 13, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [2494a33ba4](https://linux-hardware.org/?probe=2494a33ba4) | Dec 13, 2020 |
| Apple         | MacBookPro15,1              | [6b39cb0ac1](https://linux-hardware.org/?probe=6b39cb0ac1) | Dec 11, 2020 |
| Apple         | MacBookPro15,1              | [4a2bda5c7e](https://linux-hardware.org/?probe=4a2bda5c7e) | Dec 11, 2020 |
| Medion        | Akoya S4220 MD99660         | [b07a7e906e](https://linux-hardware.org/?probe=b07a7e906e) | Dec 07, 2020 |
| Acer          | TravelMate P253             | [a9e4db8396](https://linux-hardware.org/?probe=a9e4db8396) | Dec 06, 2020 |
| Unknown       | Unknown                     | [b6af52b707](https://linux-hardware.org/?probe=b6af52b707) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [d8fff30988](https://linux-hardware.org/?probe=d8fff30988) | Dec 04, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [548218334c](https://linux-hardware.org/?probe=548218334c) | Dec 03, 2020 |
| Acer          | Aspire 5733Z                | [cee0103079](https://linux-hardware.org/?probe=cee0103079) | Dec 02, 2020 |
| Unknown       | Unknown                     | [4102aed9b6](https://linux-hardware.org/?probe=4102aed9b6) | Dec 02, 2020 |
| Dell          | Precision 5530              | [7067683c8a](https://linux-hardware.org/?probe=7067683c8a) | Dec 01, 2020 |
| Clevo         | W150ER                      | [43d4833cd9](https://linux-hardware.org/?probe=43d4833cd9) | Dec 01, 2020 |
| Sony          | SVE1513S1EW                 | [cabda1d2bb](https://linux-hardware.org/?probe=cabda1d2bb) | Nov 30, 2020 |
| Lenovo        | Z710 20250                  | [700c65c16f](https://linux-hardware.org/?probe=700c65c16f) | Nov 29, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [e3c0f67fb8](https://linux-hardware.org/?probe=e3c0f67fb8) | Nov 29, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [14558cdb25](https://linux-hardware.org/?probe=14558cdb25) | Nov 29, 2020 |
| Lenovo        | ThinkPad T420 4236B87       | [c4208169ee](https://linux-hardware.org/?probe=c4208169ee) | Nov 29, 2020 |
| ASUSTek       | X541UAK                     | [b527cf9243](https://linux-hardware.org/?probe=b527cf9243) | Nov 29, 2020 |
| Apple         | MacBookPro15,1              | [9cedfc4727](https://linux-hardware.org/?probe=9cedfc4727) | Nov 25, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [87d6a75f6f](https://linux-hardware.org/?probe=87d6a75f6f) | Nov 23, 2020 |
| MSI           | CX700                       | [78401c7758](https://linux-hardware.org/?probe=78401c7758) | Nov 22, 2020 |
| ASUSTek       | X200CA                      | [73a317dd32](https://linux-hardware.org/?probe=73a317dd32) | Nov 21, 2020 |
| ASUSTek       | X200CA                      | [2a86994bf7](https://linux-hardware.org/?probe=2a86994bf7) | Nov 21, 2020 |
| ASUSTek       | P553UA                      | [08a45ba314](https://linux-hardware.org/?probe=08a45ba314) | Nov 16, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [43f7b0ed5e](https://linux-hardware.org/?probe=43f7b0ed5e) | Nov 16, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4fccf7c912](https://linux-hardware.org/?probe=4fccf7c912) | Nov 15, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [00d5983461](https://linux-hardware.org/?probe=00d5983461) | Nov 15, 2020 |
| Apple         | MacBookPro15,1              | [1ebfd7c5b6](https://linux-hardware.org/?probe=1ebfd7c5b6) | Nov 14, 2020 |
| Apple         | MacBookPro15,1              | [8bc8600e93](https://linux-hardware.org/?probe=8bc8600e93) | Nov 14, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU0S    | [f70cdb0ad4](https://linux-hardware.org/?probe=f70cdb0ad4) | Nov 12, 2020 |
| Alienware     | 18                          | [57676ac43d](https://linux-hardware.org/?probe=57676ac43d) | Nov 10, 2020 |
| TUXEDO        | P65_67HSHP                  | [66d5b793fb](https://linux-hardware.org/?probe=66d5b793fb) | Nov 08, 2020 |
| HP            | 250 G3                      | [8b5f98ec2a](https://linux-hardware.org/?probe=8b5f98ec2a) | Nov 07, 2020 |
| Medion        | Akoya S4220 MD99660         | [7f1c16bcda](https://linux-hardware.org/?probe=7f1c16bcda) | Nov 06, 2020 |
| Lenovo        | E51-80 80QB                 | [ca5466d80a](https://linux-hardware.org/?probe=ca5466d80a) | Nov 05, 2020 |
| HP            | ProBook 455 G7              | [98b7cd43d4](https://linux-hardware.org/?probe=98b7cd43d4) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [aa9c0e0e54](https://linux-hardware.org/?probe=aa9c0e0e54) | Nov 04, 2020 |
| Dell          | Latitude E6530              | [37fe920988](https://linux-hardware.org/?probe=37fe920988) | Oct 31, 2020 |
| Medion        | Akoya S4220 MD99660         | [bb717a9e21](https://linux-hardware.org/?probe=bb717a9e21) | Oct 31, 2020 |
| Gigabyte      | M1M3XBP-00                  | [b6c122e3a8](https://linux-hardware.org/?probe=b6c122e3a8) | Oct 30, 2020 |
| Dell          | Inspiron N5110              | [cf33d9bfbd](https://linux-hardware.org/?probe=cf33d9bfbd) | Oct 30, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [560dfacda1](https://linux-hardware.org/?probe=560dfacda1) | Oct 30, 2020 |
| Acer          | Aspire VN7-571G             | [cb343ac230](https://linux-hardware.org/?probe=cb343ac230) | Oct 29, 2020 |
| HP            | Notebook                    | [e9cffa5296](https://linux-hardware.org/?probe=e9cffa5296) | Oct 27, 2020 |
| Sony          | VPCEH2J1E                   | [63d6cbf81b](https://linux-hardware.org/?probe=63d6cbf81b) | Oct 26, 2020 |
| Apple         | MacBookPro5,1               | [9a77d8bcee](https://linux-hardware.org/?probe=9a77d8bcee) | Oct 25, 2020 |
| HP            | ProBook 455 G7              | [2567e8cd8d](https://linux-hardware.org/?probe=2567e8cd8d) | Oct 22, 2020 |
| ASUSTek       | K70IC                       | [bd81130974](https://linux-hardware.org/?probe=bd81130974) | Oct 21, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0795bcf48b](https://linux-hardware.org/?probe=0795bcf48b) | Oct 20, 2020 |
| Dell          | XPS M1530                   | [fe7376d804](https://linux-hardware.org/?probe=fe7376d804) | Oct 20, 2020 |
| HP            | ZBook 15u G6                | [d7fdb50013](https://linux-hardware.org/?probe=d7fdb50013) | Oct 20, 2020 |
| Sony          | VPCEH2J1E                   | [1eaddc7d21](https://linux-hardware.org/?probe=1eaddc7d21) | Oct 19, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [425f8279f4](https://linux-hardware.org/?probe=425f8279f4) | Oct 18, 2020 |
| HP            | Pavilion dv6000 (RM474EA... | [45c9c4c500](https://linux-hardware.org/?probe=45c9c4c500) | Oct 16, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [6c91e0804a](https://linux-hardware.org/?probe=6c91e0804a) | Oct 16, 2020 |
| Lenovo        | ThinkPad P51 20HJS0Q900     | [afbd1d03a4](https://linux-hardware.org/?probe=afbd1d03a4) | Oct 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [8f7686c8ae](https://linux-hardware.org/?probe=8f7686c8ae) | Oct 15, 2020 |
| HP            | 250 G3                      | [66a0f6f80d](https://linux-hardware.org/?probe=66a0f6f80d) | Oct 15, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [89d37bfc4f](https://linux-hardware.org/?probe=89d37bfc4f) | Oct 15, 2020 |
| HP            | EliteBook 8460p             | [081e9ba453](https://linux-hardware.org/?probe=081e9ba453) | Oct 13, 2020 |
| HP            | ProBook 445 G7              | [d915bbd395](https://linux-hardware.org/?probe=d915bbd395) | Oct 12, 2020 |
| Lenovo        | ThinkPad T480 20L50063GE    | [8e233f307a](https://linux-hardware.org/?probe=8e233f307a) | Oct 12, 2020 |
| HP            | EliteBook 8460p             | [efecdb4bd2](https://linux-hardware.org/?probe=efecdb4bd2) | Oct 11, 2020 |
| HP            | 250 G3                      | [4bd94aaef2](https://linux-hardware.org/?probe=4bd94aaef2) | Oct 07, 2020 |
| Apple         | MacBookPro15,1              | [d1bf2547ae](https://linux-hardware.org/?probe=d1bf2547ae) | Oct 07, 2020 |
| Apple         | MacBookPro15,1              | [9782f126d8](https://linux-hardware.org/?probe=9782f126d8) | Oct 07, 2020 |
| HP            | 250 G3                      | [c4e7564fc7](https://linux-hardware.org/?probe=c4e7564fc7) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| System76      | Lemur Pro                   | [5f01c32134](https://linux-hardware.org/?probe=5f01c32134) | Oct 05, 2020 |
| Dell          | Latitude 5411               | [84fa41043c](https://linux-hardware.org/?probe=84fa41043c) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ec7ec04666](https://linux-hardware.org/?probe=ec7ec04666) | Oct 01, 2020 |
| Acer          | TravelMate B117-M           | [0d658847c1](https://linux-hardware.org/?probe=0d658847c1) | Sep 30, 2020 |
| Dell          | Latitude 3330               | [e9df98027f](https://linux-hardware.org/?probe=e9df98027f) | Sep 29, 2020 |
| System76      | Lemur Pro                   | [a364cc95e8](https://linux-hardware.org/?probe=a364cc95e8) | Sep 26, 2020 |
| HP            | Notebook                    | [07eb4784fa](https://linux-hardware.org/?probe=07eb4784fa) | Sep 20, 2020 |
| ASUSTek       | G750JZA                     | [0f045b46bd](https://linux-hardware.org/?probe=0f045b46bd) | Sep 20, 2020 |
| Medion        | P15648                      | [c135c2beeb](https://linux-hardware.org/?probe=c135c2beeb) | Sep 20, 2020 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [fe11f72b06](https://linux-hardware.org/?probe=fe11f72b06) | Sep 19, 2020 |
| HP            | 255 G7 Notebook PC          | [eee18a3d6f](https://linux-hardware.org/?probe=eee18a3d6f) | Sep 15, 2020 |
| HP            | EliteBook Folio G1          | [406bd04dda](https://linux-hardware.org/?probe=406bd04dda) | Sep 13, 2020 |
| HP            | EliteBook Folio G1          | [cfaad6c829](https://linux-hardware.org/?probe=cfaad6c829) | Sep 13, 2020 |
| Lenovo        | ThinkPad T460s 20FAS54D0... | [1906a25c9b](https://linux-hardware.org/?probe=1906a25c9b) | Sep 13, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [451f9dcbaa](https://linux-hardware.org/?probe=451f9dcbaa) | Sep 13, 2020 |
| Lenovo        | V145-15AST 81MT             | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Lenovo        | ThinkPad T490 20N20048GE    | [3d81acb7a7](https://linux-hardware.org/?probe=3d81acb7a7) | Sep 08, 2020 |
| Apple         | MacBookPro15,1              | [14f7792e0d](https://linux-hardware.org/?probe=14f7792e0d) | Sep 07, 2020 |
| Lenovo        | Flex 2-14D 20376            | [42f622f899](https://linux-hardware.org/?probe=42f622f899) | Sep 06, 2020 |
| Lenovo        | Flex 2-14D 20376            | [976ebfa4ea](https://linux-hardware.org/?probe=976ebfa4ea) | Sep 06, 2020 |
| Apple         | MacBookPro9,2               | [97a1b28c1a](https://linux-hardware.org/?probe=97a1b28c1a) | Sep 06, 2020 |
| HP            | ZBook 15 G2                 | [4517259103](https://linux-hardware.org/?probe=4517259103) | Sep 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [ee329db2e4](https://linux-hardware.org/?probe=ee329db2e4) | Sep 05, 2020 |
| Apple         | MacBookPro8,1               | [1a243ff587](https://linux-hardware.org/?probe=1a243ff587) | Sep 04, 2020 |
| Lenovo        | ThinkPad L470 20J4000NIX    | [a9bf3bb043](https://linux-hardware.org/?probe=a9bf3bb043) | Sep 04, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2de7a19bf0](https://linux-hardware.org/?probe=2de7a19bf0) | Sep 02, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9c0614c658](https://linux-hardware.org/?probe=9c0614c658) | Sep 02, 2020 |
| Medion        | E6415 MD99904               | [736d4513c4](https://linux-hardware.org/?probe=736d4513c4) | Sep 01, 2020 |
| Sony          | VPCSB4M9E                   | [7dcc858a48](https://linux-hardware.org/?probe=7dcc858a48) | Aug 31, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [540e8eb564](https://linux-hardware.org/?probe=540e8eb564) | Aug 31, 2020 |
| HP            | ProBook 445 G7              | [b8baf427ab](https://linux-hardware.org/?probe=b8baf427ab) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f462ed28f8](https://linux-hardware.org/?probe=f462ed28f8) | Aug 27, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8f4232f9f1](https://linux-hardware.org/?probe=8f4232f9f1) | Aug 27, 2020 |
| Apple         | MacBookPro15,1              | [7453da059c](https://linux-hardware.org/?probe=7453da059c) | Aug 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b2afc4638f](https://linux-hardware.org/?probe=b2afc4638f) | Aug 24, 2020 |
| Dell          | XPS 13 9343                 | [65cff6afdc](https://linux-hardware.org/?probe=65cff6afdc) | Aug 24, 2020 |
| Apple         | MacBookPro15,1              | [be21c397d9](https://linux-hardware.org/?probe=be21c397d9) | Aug 23, 2020 |
| Apple         | MacBookPro3,1               | [dfbcd5465f](https://linux-hardware.org/?probe=dfbcd5465f) | Aug 22, 2020 |
| HP            | Pavilion g7                 | [2af3b3e46e](https://linux-hardware.org/?probe=2af3b3e46e) | Aug 21, 2020 |
| Apple         | MacBookPro15,1              | [9bfbed1a2a](https://linux-hardware.org/?probe=9bfbed1a2a) | Aug 21, 2020 |
| Apple         | MacBookPro8,1               | [de109678e9](https://linux-hardware.org/?probe=de109678e9) | Aug 19, 2020 |
| Sony          | VPCSB4M9E                   | [023b8f969c](https://linux-hardware.org/?probe=023b8f969c) | Aug 17, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [fd1b79a95a](https://linux-hardware.org/?probe=fd1b79a95a) | Aug 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [b88b8f8632](https://linux-hardware.org/?probe=b88b8f8632) | Aug 13, 2020 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [d4b87a0017](https://linux-hardware.org/?probe=d4b87a0017) | Aug 13, 2020 |
| HP            | EliteBook 840 G6            | [48e5c468eb](https://linux-hardware.org/?probe=48e5c468eb) | Aug 11, 2020 |
| TUXEDO        | Book BA1510                 | [cb33d0e196](https://linux-hardware.org/?probe=cb33d0e196) | Aug 11, 2020 |
| ASUSTek       | X555LAB                     | [53f9b8a1a8](https://linux-hardware.org/?probe=53f9b8a1a8) | Aug 10, 2020 |
| Apple         | MacBookPro15,1              | [f9412036c4](https://linux-hardware.org/?probe=f9412036c4) | Aug 10, 2020 |
| HP            | 255 G3                      | [4d659eb265](https://linux-hardware.org/?probe=4d659eb265) | Aug 10, 2020 |
| Dell          | Inspiron 1012               | [f6bcf43f2d](https://linux-hardware.org/?probe=f6bcf43f2d) | Aug 10, 2020 |
| Acer          | TravelMate P256-MG          | [b87afa646c](https://linux-hardware.org/?probe=b87afa646c) | Aug 08, 2020 |
| Apple         | MacBookPro15,1              | [5cef1b9672](https://linux-hardware.org/?probe=5cef1b9672) | Aug 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3b0831d8cd](https://linux-hardware.org/?probe=3b0831d8cd) | Aug 07, 2020 |
| Lenovo        | ThinkPad W541 20EF000UGE    | [5069a399ae](https://linux-hardware.org/?probe=5069a399ae) | Aug 04, 2020 |
| Apple         | MacBookPro10,1              | [9c24d40f13](https://linux-hardware.org/?probe=9c24d40f13) | Aug 03, 2020 |
| Apple         | MacBookPro15,1              | [6cdc75b450](https://linux-hardware.org/?probe=6cdc75b450) | Jul 30, 2020 |
| Apple         | MacBookPro15,1              | [eeba18a905](https://linux-hardware.org/?probe=eeba18a905) | Jul 30, 2020 |
| Lenovo        | ThinkPad L470 20J4003WGE    | [48cd289259](https://linux-hardware.org/?probe=48cd289259) | Jul 29, 2020 |
| MSI           | P65 Creator 9SE             | [cba3c22a57](https://linux-hardware.org/?probe=cba3c22a57) | Jul 28, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c53ab8278b](https://linux-hardware.org/?probe=c53ab8278b) | Jul 27, 2020 |
| HP            | ProBook 440 G4              | [d5dd831e60](https://linux-hardware.org/?probe=d5dd831e60) | Jul 25, 2020 |
| Lenovo        | V110-15AST 80TD             | [f7ebec8b02](https://linux-hardware.org/?probe=f7ebec8b02) | Jul 25, 2020 |
| Apple         | MacBookPro15,1              | [7f8b2568b4](https://linux-hardware.org/?probe=7f8b2568b4) | Jul 18, 2020 |
| Sony          | VPCEJ2L1E                   | [2497ad55e0](https://linux-hardware.org/?probe=2497ad55e0) | Jul 17, 2020 |
| Dell          | Latitude E7450              | [81d0042be7](https://linux-hardware.org/?probe=81d0042be7) | Jul 17, 2020 |
| Apple         | MacBookPro15,1              | [f128e49c63](https://linux-hardware.org/?probe=f128e49c63) | Jul 16, 2020 |
| Apple         | MacBookPro15,1              | [8cdd0c7080](https://linux-hardware.org/?probe=8cdd0c7080) | Jul 16, 2020 |
| ASUSTek       | ZenBook UX392FA_UX392FA     | [56c9214691](https://linux-hardware.org/?probe=56c9214691) | Jul 14, 2020 |
| Lenovo        | V15-IIL 82C5                | [0b79ef9ef1](https://linux-hardware.org/?probe=0b79ef9ef1) | Jul 12, 2020 |
| HP            | 530 Notebook PC(GH634AA#... | [271e393696](https://linux-hardware.org/?probe=271e393696) | Jul 12, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [1cb4a44270](https://linux-hardware.org/?probe=1cb4a44270) | Jul 11, 2020 |
| HP            | ProBook 440 G4              | [6a65b389b0](https://linux-hardware.org/?probe=6a65b389b0) | Jul 10, 2020 |
| HP            | EliteBook 840 G2            | [c560a5a1db](https://linux-hardware.org/?probe=c560a5a1db) | Jul 10, 2020 |
| HP            | Pavilion Notebook           | [72710ffdc6](https://linux-hardware.org/?probe=72710ffdc6) | Jul 10, 2020 |
| HP            | EliteBook 840 G6            | [2aa344c383](https://linux-hardware.org/?probe=2aa344c383) | Jul 09, 2020 |
| Toshiba       | Satellite Pro A30t-C        | [02a72184b0](https://linux-hardware.org/?probe=02a72184b0) | Jul 09, 2020 |
| Notebook      | W65_W67RN,RC1,RCY           | [57db8f98a9](https://linux-hardware.org/?probe=57db8f98a9) | Jul 07, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a253e286bf](https://linux-hardware.org/?probe=a253e286bf) | Jul 06, 2020 |
| HP            | Notebook                    | [c71e280237](https://linux-hardware.org/?probe=c71e280237) | Jul 06, 2020 |
| Sony          | VPCW22M1E                   | [d2527d279c](https://linux-hardware.org/?probe=d2527d279c) | Jul 06, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| HP            | ProBook 430 G5              | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| HP            | ProBook 440 G4              | [0957532611](https://linux-hardware.org/?probe=0957532611) | Jul 01, 2020 |
| Apple         | MacBookPro15,1              | [e4d129c0d2](https://linux-hardware.org/?probe=e4d129c0d2) | Jul 01, 2020 |
| Apple         | MacBookPro15,1              | [e686fdbfb1](https://linux-hardware.org/?probe=e686fdbfb1) | Jul 01, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c2c3727c6a](https://linux-hardware.org/?probe=c2c3727c6a) | Jun 30, 2020 |
| ASUSTek       | X540LA                      | [df995fd6b3](https://linux-hardware.org/?probe=df995fd6b3) | Jun 27, 2020 |
| HP            | ProBook 440 G4              | [c60568237f](https://linux-hardware.org/?probe=c60568237f) | Jun 27, 2020 |
| Sony          | VGN-AW41MF_H                | [222b0cb3b0](https://linux-hardware.org/?probe=222b0cb3b0) | Jun 27, 2020 |
| HP            | Pavilion Notebook           | [f4b2e3494d](https://linux-hardware.org/?probe=f4b2e3494d) | Jun 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [73c01bef24](https://linux-hardware.org/?probe=73c01bef24) | Jun 23, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | [1ee633aa8c](https://linux-hardware.org/?probe=1ee633aa8c) | Jun 22, 2020 |
| HP            | 250 G7 Notebook PC          | [3fa7c66cb7](https://linux-hardware.org/?probe=3fa7c66cb7) | Jun 19, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a6d2c4f2e2](https://linux-hardware.org/?probe=a6d2c4f2e2) | Jun 17, 2020 |
| Acer          | Aspire E5-774G              | [f76380f497](https://linux-hardware.org/?probe=f76380f497) | Jun 17, 2020 |
| ASUSTek       | X55U                        | [139c699a3b](https://linux-hardware.org/?probe=139c699a3b) | Jun 17, 2020 |
| ASUSTek       | X55U                        | [acecf7cf92](https://linux-hardware.org/?probe=acecf7cf92) | Jun 17, 2020 |
| HP            | Notebook                    | [acd1e9f946](https://linux-hardware.org/?probe=acd1e9f946) | Jun 16, 2020 |
| Toshiba       | Satellite U920T             | [3bcf98d2cf](https://linux-hardware.org/?probe=3bcf98d2cf) | Jun 15, 2020 |
| TUXEDO        | Unknown                     | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| HP            | 250 G3                      | [f6cf1f21df](https://linux-hardware.org/?probe=f6cf1f21df) | Jun 12, 2020 |
| ASUSTek       | X550CC                      | [19c1cd0275](https://linux-hardware.org/?probe=19c1cd0275) | Jun 11, 2020 |
| Apple         | MacBookPro15,1              | [953fe94792](https://linux-hardware.org/?probe=953fe94792) | Jun 06, 2020 |
| HP            | EliteBook 2560p             | [a04fddd992](https://linux-hardware.org/?probe=a04fddd992) | Jun 05, 2020 |
| Acer          | Swift SF314-42              | [5fbd0c2b78](https://linux-hardware.org/?probe=5fbd0c2b78) | Jun 05, 2020 |
| Acer          | Swift SF314-42              | [7270fcf010](https://linux-hardware.org/?probe=7270fcf010) | Jun 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [bbf7b189e8](https://linux-hardware.org/?probe=bbf7b189e8) | Jun 04, 2020 |
| Lenovo        | ThinkPad T590 20N40009GE    | [c757daf95b](https://linux-hardware.org/?probe=c757daf95b) | Jun 04, 2020 |
| Lenovo        | ThinkPad T590 20N40009GE    | [55592316df](https://linux-hardware.org/?probe=55592316df) | Jun 04, 2020 |
| Medion        | E6234                       | [156d0fad52](https://linux-hardware.org/?probe=156d0fad52) | Jun 04, 2020 |
| HP            | EliteBook 2560p             | [63e8663282](https://linux-hardware.org/?probe=63e8663282) | Jun 03, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [6341aa627a](https://linux-hardware.org/?probe=6341aa627a) | Jun 01, 2020 |
| Acer          | Aspire E5-774G              | [3ace5aa3a2](https://linux-hardware.org/?probe=3ace5aa3a2) | May 31, 2020 |
| Apple         | MacBookPro15,1              | [91f82cb3f9](https://linux-hardware.org/?probe=91f82cb3f9) | May 31, 2020 |
| Apple         | MacBookPro15,1              | [8f3ca25a03](https://linux-hardware.org/?probe=8f3ca25a03) | May 31, 2020 |
| Apple         | MacBookPro15,1              | [4b8f308a9a](https://linux-hardware.org/?probe=4b8f308a9a) | May 30, 2020 |
| Lenovo        | ThinkPad T470s 20JTS0K80... | [c8512a9720](https://linux-hardware.org/?probe=c8512a9720) | May 30, 2020 |
| Lenovo        | ThinkPad T470s 20JTS0K80... | [3c1a33f98c](https://linux-hardware.org/?probe=3c1a33f98c) | May 30, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [6c69546de7](https://linux-hardware.org/?probe=6c69546de7) | May 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4aff0b33d1](https://linux-hardware.org/?probe=4aff0b33d1) | May 29, 2020 |
| Apple         | MacBookPro15,1              | [c856b73498](https://linux-hardware.org/?probe=c856b73498) | May 28, 2020 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7f2c6aaee](https://linux-hardware.org/?probe=e7f2c6aaee) | May 25, 2020 |
| ASUSTek       | K52F                        | [ce6b7f3bfb](https://linux-hardware.org/?probe=ce6b7f3bfb) | May 23, 2020 |
| HP            | ZBook 17 G5                 | [93f2b3d9a8](https://linux-hardware.org/?probe=93f2b3d9a8) | May 22, 2020 |
| HP            | 250 G7 Notebook PC          | [9db7fe5c54](https://linux-hardware.org/?probe=9db7fe5c54) | May 19, 2020 |
| HP            | 250 G7 Notebook PC          | [3f7cabee9f](https://linux-hardware.org/?probe=3f7cabee9f) | May 16, 2020 |
| Acer          | Aspire 5551G                | [013faec925](https://linux-hardware.org/?probe=013faec925) | May 16, 2020 |
| Lenovo        | IdeaPad Z360                | [fd6f7cb118](https://linux-hardware.org/?probe=fd6f7cb118) | May 15, 2020 |
| Sony          | VPCSB4M9E                   | [ee9d1561e1](https://linux-hardware.org/?probe=ee9d1561e1) | May 15, 2020 |
| Sony          | VPCSB4M9E                   | [3e4e276564](https://linux-hardware.org/?probe=3e4e276564) | May 15, 2020 |
| HP            | EliteBook 8460p             | [68f49e181f](https://linux-hardware.org/?probe=68f49e181f) | May 14, 2020 |
| HP            | Compaq 15                   | [8362ccc50e](https://linux-hardware.org/?probe=8362ccc50e) | May 14, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [b60c49bd7d](https://linux-hardware.org/?probe=b60c49bd7d) | May 13, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [2a491de495](https://linux-hardware.org/?probe=2a491de495) | May 13, 2020 |
| HP            | ProBook 450 G2              | [4851e2f3ff](https://linux-hardware.org/?probe=4851e2f3ff) | May 11, 2020 |
| Dell          | XPS 15 7590                 | [3526843e9f](https://linux-hardware.org/?probe=3526843e9f) | May 10, 2020 |
| HP            | EliteBook 2560p             | [d738b6165b](https://linux-hardware.org/?probe=d738b6165b) | May 09, 2020 |
| Lenovo        | Z710 20250                  | [40527a10da](https://linux-hardware.org/?probe=40527a10da) | May 09, 2020 |
| Lenovo        | IdeaPad Z360                | [68d24fa190](https://linux-hardware.org/?probe=68d24fa190) | May 07, 2020 |
| Lenovo        | ThinkPad X201 Tablet 309... | [49c9895e09](https://linux-hardware.org/?probe=49c9895e09) | May 07, 2020 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e3bbc139a1](https://linux-hardware.org/?probe=e3bbc139a1) | May 06, 2020 |
| HP            | Pavilion dv6                | [a797799780](https://linux-hardware.org/?probe=a797799780) | May 06, 2020 |
| Lenovo        | ThinkPad T400 6475V8J       | [891f806dbf](https://linux-hardware.org/?probe=891f806dbf) | May 05, 2020 |
| Lenovo        | U310                        | [173c832aac](https://linux-hardware.org/?probe=173c832aac) | May 05, 2020 |
| Lenovo        | Z710 20250                  | [90f5ccee90](https://linux-hardware.org/?probe=90f5ccee90) | May 04, 2020 |
| HP            | EliteBook 830 G5            | [1c5b9e257f](https://linux-hardware.org/?probe=1c5b9e257f) | May 04, 2020 |
| HP            | EliteBook 2530p             | [11361df5c1](https://linux-hardware.org/?probe=11361df5c1) | May 04, 2020 |
| Timi          | TM1701                      | [dce301507a](https://linux-hardware.org/?probe=dce301507a) | May 03, 2020 |
| Dell          | XPS 13 9343                 | [0c0460401a](https://linux-hardware.org/?probe=0c0460401a) | May 02, 2020 |
| Lenovo        | V155-15API 81V5             | [07ecad57e1](https://linux-hardware.org/?probe=07ecad57e1) | May 02, 2020 |
| Acer          | Predator PH317-52           | [d5d4771606](https://linux-hardware.org/?probe=d5d4771606) | May 02, 2020 |
| Timi          | TM1701                      | [2c0cd9b7cf](https://linux-hardware.org/?probe=2c0cd9b7cf) | May 02, 2020 |
| Lenovo        | ThinkPad E470 20H2S00700    | [5509ae8eb8](https://linux-hardware.org/?probe=5509ae8eb8) | Apr 30, 2020 |
| HP            | ZBook 17 G5                 | [222fb4f26b](https://linux-hardware.org/?probe=222fb4f26b) | Apr 29, 2020 |
| HP            | EliteBook 6930p             | [72e7230b26](https://linux-hardware.org/?probe=72e7230b26) | Apr 28, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| Lenovo        | V155-15API 81V5             | [eaa6cfe3a1](https://linux-hardware.org/?probe=eaa6cfe3a1) | Apr 27, 2020 |
| HP            | 250 G3                      | [77a826318e](https://linux-hardware.org/?probe=77a826318e) | Apr 27, 2020 |
| HP            | EliteBook 840 G5            | [25a57d9328](https://linux-hardware.org/?probe=25a57d9328) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| ASUSTek       | K52F                        | [4592f833fa](https://linux-hardware.org/?probe=4592f833fa) | Apr 26, 2020 |
| HP            | ProBook 470 G5              | [14762c7fc9](https://linux-hardware.org/?probe=14762c7fc9) | Apr 26, 2020 |
| Lenovo        | ThinkPad T400 6475V8J       | [ac93664dd5](https://linux-hardware.org/?probe=ac93664dd5) | Apr 25, 2020 |
| HP            | EliteBook 8560p             | [7fe6ce5446](https://linux-hardware.org/?probe=7fe6ce5446) | Apr 24, 2020 |
| Dell          | XPS 15 9570                 | [d2d9a88841](https://linux-hardware.org/?probe=d2d9a88841) | Apr 23, 2020 |
| HP            | 250 G3                      | [e58e824d1e](https://linux-hardware.org/?probe=e58e824d1e) | Apr 23, 2020 |
| HP            | Presario CQ62               | [89ec142930](https://linux-hardware.org/?probe=89ec142930) | Apr 22, 2020 |
| Dell          | Inspiron 1720               | [5bbab2bc27](https://linux-hardware.org/?probe=5bbab2bc27) | Apr 21, 2020 |
| HP            | Pavilion dv6                | [c87812f0b6](https://linux-hardware.org/?probe=c87812f0b6) | Apr 19, 2020 |
| Lenovo        | ThinkPad X230 2325E58       | [115a7cb6e8](https://linux-hardware.org/?probe=115a7cb6e8) | Apr 19, 2020 |
| Lenovo        | ThinkPad E580 20KS001RGE    | [15a9d81427](https://linux-hardware.org/?probe=15a9d81427) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [75a149c376](https://linux-hardware.org/?probe=75a149c376) | Apr 18, 2020 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [0f324eff93](https://linux-hardware.org/?probe=0f324eff93) | Apr 15, 2020 |
| HP            | ZBook 17 G5                 | [19a267ec38](https://linux-hardware.org/?probe=19a267ec38) | Apr 15, 2020 |
| Dell          | Inspiron 1370               | [c7ec016f28](https://linux-hardware.org/?probe=c7ec016f28) | Apr 13, 2020 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [dab9ed3a88](https://linux-hardware.org/?probe=dab9ed3a88) | Apr 12, 2020 |
| Samsung       | 900X3C/900X4C/900X4D        | [c3727b56fe](https://linux-hardware.org/?probe=c3727b56fe) | Apr 11, 2020 |
| Dell          | Latitude 5591               | [0a0cc321d5](https://linux-hardware.org/?probe=0a0cc321d5) | Apr 10, 2020 |
| Fujitsu Si... | LIFEBOOK S7210              | [83ef7b016e](https://linux-hardware.org/?probe=83ef7b016e) | Apr 08, 2020 |
| Acer          | Aspire 7720Z                | [53bced64ee](https://linux-hardware.org/?probe=53bced64ee) | Apr 08, 2020 |
| Samsung       | 275E4E/275E5E               | [42334085a3](https://linux-hardware.org/?probe=42334085a3) | Apr 07, 2020 |
| Sony          | VPCEJ2Z1E                   | [8644050307](https://linux-hardware.org/?probe=8644050307) | Apr 07, 2020 |
| Sony          | VPCEJ2Z1E                   | [d2f25d33cd](https://linux-hardware.org/?probe=d2f25d33cd) | Apr 07, 2020 |
| TWJ           | Unknown                     | [46d5d76af1](https://linux-hardware.org/?probe=46d5d76af1) | Apr 05, 2020 |
| TWJ           | Unknown                     | [ff50430fcf](https://linux-hardware.org/?probe=ff50430fcf) | Apr 05, 2020 |
| Acer          | Aspire A315-41              | [ec505d4ab7](https://linux-hardware.org/?probe=ec505d4ab7) | Apr 02, 2020 |
| HP            | EliteBook 8540p             | [8a7018aba0](https://linux-hardware.org/?probe=8a7018aba0) | Apr 01, 2020 |
| Dell          | Inspiron MM061              | [81c8f6a88f](https://linux-hardware.org/?probe=81c8f6a88f) | Mar 31, 2020 |
| Dell          | Inspiron MM061              | [ec58223171](https://linux-hardware.org/?probe=ec58223171) | Mar 31, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [cea75ac44a](https://linux-hardware.org/?probe=cea75ac44a) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [59c568e03a](https://linux-hardware.org/?probe=59c568e03a) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [592d008d70](https://linux-hardware.org/?probe=592d008d70) | Mar 30, 2020 |
| MAXDATA       | obook3-2                    | [1fcc44c107](https://linux-hardware.org/?probe=1fcc44c107) | Mar 29, 2020 |
| MAXDATA       | obook3-2                    | [96f3fa6a9a](https://linux-hardware.org/?probe=96f3fa6a9a) | Mar 29, 2020 |
| HP            | Laptop 15-bw0xx             | [711444c9be](https://linux-hardware.org/?probe=711444c9be) | Mar 28, 2020 |
| Lenovo        | ThinkPad T480 20L50063GE    | [02a6eb697c](https://linux-hardware.org/?probe=02a6eb697c) | Mar 25, 2020 |
| HP            | ProBook 470 G5              | [e9c424a2bc](https://linux-hardware.org/?probe=e9c424a2bc) | Mar 22, 2020 |
| Sony          | VGN-FE21M                   | [b117ba3f2f](https://linux-hardware.org/?probe=b117ba3f2f) | Mar 22, 2020 |
| Acer          | Aspire A315-53              | [41cb001222](https://linux-hardware.org/?probe=41cb001222) | Mar 22, 2020 |
| ASUSTek       | X75A1                       | [6b38c604cc](https://linux-hardware.org/?probe=6b38c604cc) | Mar 21, 2020 |
| Dell          | Latitude 5401               | [224f10a741](https://linux-hardware.org/?probe=224f10a741) | Mar 21, 2020 |
| ASUSTek       | R11CX                       | [680a4502f2](https://linux-hardware.org/?probe=680a4502f2) | Mar 19, 2020 |
| ASUSTek       | R11CX                       | [36a803af0b](https://linux-hardware.org/?probe=36a803af0b) | Mar 19, 2020 |
| Lenovo        | B50-70 80EU                 | [32162d2fcb](https://linux-hardware.org/?probe=32162d2fcb) | Mar 19, 2020 |
| HP            | OMEN by Laptop 17-cb0xxx    | [a42a77029d](https://linux-hardware.org/?probe=a42a77029d) | Mar 18, 2020 |
| Toshiba       | Satellite C50D-B            | [7ff86aad0f](https://linux-hardware.org/?probe=7ff86aad0f) | Mar 12, 2020 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [7089e13229](https://linux-hardware.org/?probe=7089e13229) | Mar 11, 2020 |
| ASUSTek       | X55VD                       | [bde6829542](https://linux-hardware.org/?probe=bde6829542) | Mar 10, 2020 |
| Lenovo        | ThinkPad T490s 20NX000AG... | [0ea72326af](https://linux-hardware.org/?probe=0ea72326af) | Mar 01, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 140       | 16.57%  |
| Ubuntu 18.04                 | 60        | 7.1%    |
| Linux Mint 20.2              | 28        | 3.31%   |
| Ubuntu 22.04                 | 27        | 3.2%    |
| OpenMandriva 4.3             | 23        | 2.72%   |
| Arch                         | 23        | 2.72%   |
| BlackPanther 18.1            | 19        | 2.25%   |
| Zorin 16                     | 18        | 2.13%   |
| Fedora 35                    | 18        | 2.13%   |
| Linux Mint 20.1              | 17        | 2.01%   |
| Arch Rolling                 | 17        | 2.01%   |
| Ubuntu 21.04                 | 16        | 1.89%   |
| Debian 11                    | 16        | 1.89%   |
| Fedora 33                    | 15        | 1.78%   |
| Manjaro                      | 14        | 1.66%   |
| Linux Mint 19.3              | 14        | 1.66%   |
| KDE neon 20.04               | 14        | 1.66%   |
| Ubuntu 19.10                 | 13        | 1.54%   |
| Ubuntu 21.10                 | 12        | 1.42%   |
| Fedora 32                    | 12        | 1.42%   |
| OpenMandriva 4.2             | 11        | 1.3%    |
| Fedora 36                    | 11        | 1.3%    |
| Fedora 34                    | 10        | 1.18%   |
| Pop!_OS 21.04                | 9         | 1.07%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 1.07%   |
| Zorin 15                     | 8         | 0.95%   |
| Ubuntu 20.10                 | 8         | 0.95%   |
| Pop!_OS 20.04                | 8         | 0.95%   |
| Linux Mint 20.3              | 8         | 0.95%   |
| Linux Mint 20                | 8         | 0.95%   |
| Ubuntu 19.04                 | 7         | 0.83%   |
| Xubuntu 20.04                | 6         | 0.71%   |
| Pop!_OS 20.10                | 6         | 0.71%   |
| OpenMandriva 4.50            | 6         | 0.71%   |
| Ubuntu 16.04                 | 5         | 0.59%   |
| ROSA R10                     | 5         | 0.59%   |
| Linux Mint 21                | 5         | 0.59%   |
| Pop!_OS 22.04                | 4         | 0.47%   |
| MX 19                        | 4         | 0.47%   |
| Manjaro 20.0.3               | 4         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 285       | 35.67%  |
| Linux Mint    | 79        | 9.89%   |
| Fedora        | 66        | 8.26%   |
| Manjaro       | 45        | 5.63%   |
| OpenMandriva  | 40        | 5.01%   |
| Arch          | 37        | 4.63%   |
| Pop!_OS       | 28        | 3.5%    |
| Debian        | 28        | 3.5%    |
| Zorin         | 26        | 3.25%   |
| BlackPanther  | 19        | 2.38%   |
| KDE neon      | 18        | 2.25%   |
| openSUSE      | 16        | 2%      |
| Xubuntu       | 11        | 1.38%   |
| ROSA          | 11        | 1.38%   |
| Kubuntu       | 10        | 1.25%   |
| Endless       | 9         | 1.13%   |
| Elementary    | 9         | 1.13%   |
| MX            | 6         | 0.75%   |
| Ubuntu Budgie | 5         | 0.63%   |
| Gentoo        | 5         | 0.63%   |
| Ubuntu Unity  | 4         | 0.5%    |
| SteamOS       | 4         | 0.5%    |
| LMDE          | 4         | 0.5%    |
| Kali          | 4         | 0.5%    |
| Ubuntu MATE   | 3         | 0.38%   |
| EndeavourOS   | 3         | 0.38%   |
| ArcoLinux     | 3         | 0.38%   |
| Lubuntu       | 2         | 0.25%   |
| Clear Linux   | 2         | 0.25%   |
| CentOS        | 2         | 0.25%   |
| CachyOS       | 2         | 0.25%   |
| UbuntuDDE     | 1         | 0.13%   |
| Ubuntu Studio | 1         | 0.13%   |
| Solus         | 1         | 0.13%   |
| Sn3rpOs       | 1         | 0.13%   |
| Parrot        | 1         | 0.13%   |
| Nobara        | 1         | 0.13%   |
| NixOS         | 1         | 0.13%   |
| Garuda Linux  | 1         | 0.13%   |
| Funtoo        | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 23        | 2.48%   |
| 5.4.0-42-generic         | 16        | 1.72%   |
| 4.18.16-desktop-1bP      | 13        | 1.4%    |
| 5.4.0-58-generic         | 12        | 1.29%   |
| 5.3.0-46-generic         | 12        | 1.29%   |
| 5.10.14-desktop-1omv4002 | 11        | 1.18%   |
| 5.4.0-52-generic         | 10        | 1.08%   |
| 5.3.0-26-generic         | 10        | 1.08%   |
| 5.4.0-29-generic         | 9         | 0.97%   |
| 5.4.0-26-generic         | 9         | 0.97%   |
| 5.13.0-39-generic        | 9         | 0.97%   |
| 5.13.0-28-generic        | 9         | 0.97%   |
| 5.13.0-27-generic        | 9         | 0.97%   |
| 5.4.0-91-generic         | 8         | 0.86%   |
| 5.15.0-43-generic        | 8         | 0.86%   |
| 5.11.0-37-generic        | 8         | 0.86%   |
| 5.6.14-desktop-2bP       | 7         | 0.75%   |
| 5.4.0-48-generic         | 7         | 0.75%   |
| 5.15.0-52-generic        | 7         | 0.75%   |
| 5.15.0-46-generic        | 7         | 0.75%   |
| 5.11.0-27-generic        | 7         | 0.75%   |
| 5.11.0-25-generic        | 7         | 0.75%   |
| 5.4.0-74-generic         | 6         | 0.65%   |
| 5.4.0-33-generic         | 6         | 0.65%   |
| 5.3.0-42-generic         | 6         | 0.65%   |
| 5.15.0-50-generic        | 6         | 0.65%   |
| 5.10.0-8-amd64           | 6         | 0.65%   |
| 5.8.0-43-generic         | 5         | 0.54%   |
| 5.4.0-28-generic         | 5         | 0.54%   |
| 5.15.12-200.fc35.x86_64  | 5         | 0.54%   |
| 5.13.0-40-generic        | 5         | 0.54%   |
| 5.11.0-43-generic        | 5         | 0.54%   |
| 5.11.0-40-generic        | 5         | 0.54%   |
| 5.11.0-38-generic        | 5         | 0.54%   |
| 5.11.0-34-generic        | 5         | 0.54%   |
| 5.0.0-32-generic         | 5         | 0.54%   |
| 5.0.0-25-generic         | 5         | 0.54%   |
| 5.8.0-7630-generic       | 4         | 0.43%   |
| 5.8.0-53-generic         | 4         | 0.43%   |
| 5.8.0-50-generic         | 4         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 158       | 18.02%  |
| 5.13.0  | 66        | 7.53%   |
| 5.11.0  | 63        | 7.18%   |
| 5.8.0   | 49        | 5.59%   |
| 5.3.0   | 47        | 5.36%   |
| 4.15.0  | 45        | 5.13%   |
| 5.15.0  | 44        | 5.02%   |
| 5.16.7  | 24        | 2.74%   |
| 5.10.0  | 22        | 2.51%   |
| 5.0.0   | 22        | 2.51%   |
| 4.18.0  | 14        | 1.6%    |
| 4.18.16 | 13        | 1.48%   |
| 5.10.14 | 11        | 1.25%   |
| 4.19.0  | 11        | 1.25%   |
| 5.6.14  | 7         | 0.8%    |
| 5.17.5  | 6         | 0.68%   |
| 5.19.0  | 5         | 0.57%   |
| 5.15.12 | 5         | 0.57%   |
| 5.9.11  | 4         | 0.46%   |
| 5.7.9   | 4         | 0.46%   |
| 5.7.0   | 4         | 0.46%   |
| 5.3.18  | 4         | 0.46%   |
| 5.19.7  | 4         | 0.46%   |
| 5.17.1  | 4         | 0.46%   |
| 4.4.0   | 4         | 0.46%   |
| 6.0.2   | 3         | 0.34%   |
| 5.9.10  | 3         | 0.34%   |
| 5.8.14  | 3         | 0.34%   |
| 5.6.19  | 3         | 0.34%   |
| 5.18.0  | 3         | 0.34%   |
| 5.17.4  | 3         | 0.34%   |
| 5.17.15 | 3         | 0.34%   |
| 5.16.18 | 3         | 0.34%   |
| 5.13.19 | 3         | 0.34%   |
| 5.12.4  | 3         | 0.34%   |
| 5.11.12 | 3         | 0.34%   |
| 5.10.2  | 3         | 0.34%   |
| 4.12.14 | 3         | 0.34%   |
| 5.9.16  | 2         | 0.23%   |
| 5.8.6   | 2         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 172       | 19.86%  |
| 5.13    | 77        | 8.89%   |
| 5.11    | 73        | 8.43%   |
| 5.8     | 64        | 7.39%   |
| 5.15    | 61        | 7.04%   |
| 5.3     | 55        | 6.35%   |
| 5.10    | 52        | 6%      |
| 4.15    | 45        | 5.2%    |
| 5.16    | 38        | 4.39%   |
| 4.18    | 27        | 3.12%   |
| 5.0     | 23        | 2.66%   |
| 5.6     | 22        | 2.54%   |
| 5.17    | 22        | 2.54%   |
| 5.7     | 18        | 2.08%   |
| 5.19    | 18        | 2.08%   |
| 5.9     | 15        | 1.73%   |
| 4.19    | 13        | 1.5%    |
| 5.18    | 12        | 1.39%   |
| 5.12    | 11        | 1.27%   |
| 5.14    | 8         | 0.92%   |
| 4.9     | 7         | 0.81%   |
| 5.5     | 6         | 0.69%   |
| 6.0     | 5         | 0.58%   |
| 4.4     | 5         | 0.58%   |
| 4.17    | 4         | 0.46%   |
| 5.2     | 3         | 0.35%   |
| 4.12    | 3         | 0.35%   |
| 5.1     | 2         | 0.23%   |
| 4.13    | 2         | 0.23%   |
| 4.8     | 1         | 0.12%   |
| 4.14    | 1         | 0.12%   |
| 4.10    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 769       | 98.46%  |
| i686   | 12        | 1.54%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 374       | 46.4%   |
| KDE5            | 132       | 16.38%  |
| Unknown         | 85        | 10.55%  |
| XFCE            | 59        | 7.32%   |
| X-Cinnamon      | 58        | 7.2%    |
| MATE            | 19        | 2.36%   |
| KDE             | 17        | 2.11%   |
| Cinnamon        | 14        | 1.74%   |
| Pantheon        | 9         | 1.12%   |
| Budgie          | 6         | 0.74%   |
| KDE4            | 5         | 0.62%   |
| i3              | 5         | 0.62%   |
| Unity           | 4         | 0.5%    |
| LXDE            | 4         | 0.5%    |
| LXQt            | 3         | 0.37%   |
| GNOME Flashback | 3         | 0.37%   |
| Deepin          | 3         | 0.37%   |
| awesome         | 3         | 0.37%   |
| sway            | 1         | 0.12%   |
| qtile           | 1         | 0.12%   |
| Bspwm           | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 636       | 79.1%   |
| Wayland | 117       | 14.55%  |
| Unknown | 46        | 5.72%   |
| Tty     | 5         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 397       | 48.83%  |
| SDDM    | 119       | 14.64%  |
| GDM     | 112       | 13.78%  |
| GDM3    | 81        | 9.96%   |
| LightDM | 72        | 8.86%   |
| TDM     | 25        | 3.08%   |
| KDM     | 5         | 0.62%   |
| SLiM    | 1         | 0.12%   |
| MDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| de_AT   | 271       | 33.79%  |
| en_US   | 239       | 29.8%   |
| de_DE   | 114       | 14.21%  |
| Unknown | 103       | 12.84%  |
| en_GB   | 29        | 3.62%   |
| C       | 9         | 1.12%   |
| pl_PL   | 5         | 0.62%   |
| es_ES   | 5         | 0.62%   |
| POSIX   | 3         | 0.37%   |
| it_IT   | 3         | 0.37%   |
| en_AT   | 3         | 0.37%   |
| de_CH   | 3         | 0.37%   |
| tr_TR   | 2         | 0.25%   |
| en_IE   | 2         | 0.25%   |
| en_DE   | 2         | 0.25%   |
| uk_UA   | 1         | 0.12%   |
| ru_RU   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| pt_BR   | 1         | 0.12%   |
| hr_HR   | 1         | 0.12%   |
| en      | 1         | 0.12%   |
| de_LI   | 1         | 0.12%   |
| C.UTF8  | 1         | 0.12%   |
| bg_BG   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 434       | 54.05%  |
| BIOS | 369       | 45.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 620       | 78.58%  |
| Overlay | 66        | 8.37%   |
| Btrfs   | 58        | 7.35%   |
| Unknown | 30        | 3.8%    |
| Xfs     | 6         | 0.76%   |
| Zfs     | 2         | 0.25%   |
| Ext3    | 2         | 0.25%   |
| XXXXXXX | 1         | 0.13%   |
| Tmpfs   | 1         | 0.13%   |
| Nfs     | 1         | 0.13%   |
| Ext2    | 1         | 0.13%   |
| Aufs    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 441       | 55.33%  |
| GPT     | 270       | 33.88%  |
| MBR     | 86        | 10.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 696       | 87.99%  |
| Yes       | 95        | 12.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 593       | 74.87%  |
| Yes       | 199       | 25.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 215       | 27.56%  |
| Hewlett-Packard     | 152       | 19.49%  |
| Dell                | 88        | 11.28%  |
| ASUSTek Computer    | 73        | 9.36%   |
| Acer                | 71        | 9.1%    |
| Medion              | 24        | 3.08%   |
| Apple               | 23        | 2.95%   |
| Toshiba             | 20        | 2.56%   |
| Sony                | 16        | 2.05%   |
| TUXEDO              | 15        | 1.92%   |
| Fujitsu             | 9         | 1.15%   |
| MSI                 | 8         | 1.03%   |
| Samsung Electronics | 6         | 0.77%   |
| HUAWEI              | 6         | 0.77%   |
| Unknown             | 5         | 0.64%   |
| Valve               | 4         | 0.51%   |
| TrekStor            | 4         | 0.51%   |
| Fujitsu Siemens     | 4         | 0.51%   |
| Razer               | 3         | 0.38%   |
| Notebook            | 3         | 0.38%   |
| Clevo               | 3         | 0.38%   |
| Wortmann AG         | 2         | 0.26%   |
| VALE                | 2         | 0.26%   |
| Timi                | 2         | 0.26%   |
| System76            | 2         | 0.26%   |
| Shuttle             | 2         | 0.26%   |
| Panasonic           | 2         | 0.26%   |
| TWJ                 | 1         | 0.13%   |
| TENKU               | 1         | 0.13%   |
| Teclast             | 1         | 0.13%   |
| Schenker            | 1         | 0.13%   |
| MAXDATA             | 1         | 0.13%   |
| LG Electronics      | 1         | 0.13%   |
| Jumper              | 1         | 0.13%   |
| GPD                 | 1         | 0.13%   |
| Gigabyte Technology | 1         | 0.13%   |
| eMachines           | 1         | 0.13%   |
| Chuwi               | 1         | 0.13%   |
| BESSTAR Tech        | 1         | 0.13%   |
| AXDIA International | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Apple MacBookPro15,1            | 8         | 1.03%   |
| Unknown                         | 8         | 1.03%   |
| HP EliteBook 840 G3             | 6         | 0.77%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 5         | 0.64%   |
| HP Pavilion dv6                 | 5         | 0.64%   |
| HP EliteBook 8570p              | 5         | 0.64%   |
| Valve Jupiter                   | 4         | 0.51%   |
| HP EliteBook 8460p              | 4         | 0.51%   |
| HP EliteBook 840 G6             | 4         | 0.51%   |
| Dell XPS 15 9570                | 4         | 0.51%   |
| Dell Latitude 5520              | 4         | 0.51%   |
| ASUS UX303LAB                   | 4         | 0.51%   |
| TrekStor Notebook Slim S130     | 3         | 0.38%   |
| Toshiba Satellite C70D-B        | 3         | 0.38%   |
| Medion P15648                   | 3         | 0.38%   |
| Lenovo Yoga Slim 7 14ARE05 82A2 | 3         | 0.38%   |
| Lenovo ThinkPad E470 20H2S00700 | 3         | 0.38%   |
| HP ZBook 17 G5                  | 3         | 0.38%   |
| HP Pavilion g7                  | 3         | 0.38%   |
| HP Notebook                     | 3         | 0.38%   |
| HP EliteBook 840 G1             | 3         | 0.38%   |
| HP EliteBook 6930p              | 3         | 0.38%   |
| HP EliteBook 2560p              | 3         | 0.38%   |
| Dell XPS 17 9700                | 3         | 0.38%   |
| Dell XPS 13 9343                | 3         | 0.38%   |
| Dell XPS 13 9305                | 3         | 0.38%   |
| Dell Latitude E7450             | 3         | 0.38%   |
| Dell Latitude E7440             | 3         | 0.38%   |
| Dell Latitude E6400             | 3         | 0.38%   |
| Dell Latitude E5550             | 3         | 0.38%   |
| Dell Inspiron 1720              | 3         | 0.38%   |
| Apple MacBookPro8,1             | 3         | 0.38%   |
| Acer TravelMate P253            | 3         | 0.38%   |
| Acer Swift SF314-42             | 3         | 0.38%   |
| Acer Swift SF114-34             | 3         | 0.38%   |
| Acer Aspire 7750G               | 3         | 0.38%   |
| TUXEDO Pulse 15 Gen1            | 2         | 0.26%   |
| Toshiba Satellite L70-B         | 2         | 0.26%   |
| Toshiba Satellite C50D-B        | 2         | 0.26%   |
| System76 Lemur Pro              | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 148       | 18.97%  |
| HP EliteBook        | 57        | 7.31%   |
| Acer Aspire         | 44        | 5.64%   |
| Dell Latitude       | 39        | 5%      |
| Lenovo IdeaPad      | 25        | 3.21%   |
| HP ProBook          | 25        | 3.21%   |
| Dell XPS            | 24        | 3.08%   |
| HP Pavilion         | 22        | 2.82%   |
| Toshiba Satellite   | 18        | 2.31%   |
| Dell Inspiron       | 13        | 1.67%   |
| HP ZBook            | 10        | 1.28%   |
| Lenovo Yoga         | 9         | 1.15%   |
| HP Laptop           | 9         | 1.15%   |
| Fujitsu LIFEBOOK    | 9         | 1.15%   |
| ASUS VivoBook       | 9         | 1.15%   |
| Acer TravelMate     | 9         | 1.15%   |
| Lenovo ThinkBook    | 8         | 1.03%   |
| Dell Precision      | 8         | 1.03%   |
| Apple MacBookPro15  | 8         | 1.03%   |
| Acer Swift          | 8         | 1.03%   |
| Unknown             | 8         | 1.03%   |
| HP Compaq           | 5         | 0.64%   |
| HP 250              | 5         | 0.64%   |
| ASUS ZenBook        | 5         | 0.64%   |
| Acer Nitro          | 5         | 0.64%   |
| Valve Jupiter       | 4         | 0.51%   |
| ASUS UX303LAB       | 4         | 0.51%   |
| ASUS ROG            | 4         | 0.51%   |
| TrekStor Notebook   | 3         | 0.38%   |
| Razer Blade         | 3         | 0.38%   |
| Medion P15648       | 3         | 0.38%   |
| Lenovo Legion       | 3         | 0.38%   |
| HP OMEN             | 3         | 0.38%   |
| HP Notebook         | 3         | 0.38%   |
| HP 255              | 3         | 0.38%   |
| Apple MacBookPro8   | 3         | 0.38%   |
| VALE Notebook       | 2         | 0.26%   |
| TUXEDO Pulse        | 2         | 0.26%   |
| TUXEDO InfinityBook | 2         | 0.26%   |
| System76 Lemur      | 2         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 103       | 13.21%  |
| 2012 | 72        | 9.23%   |
| 2011 | 64        | 8.21%   |
| 2019 | 63        | 8.08%   |
| 2018 | 59        | 7.56%   |
| 2021 | 57        | 7.31%   |
| 2017 | 57        | 7.31%   |
| 2015 | 54        | 6.92%   |
| 2016 | 48        | 6.15%   |
| 2014 | 46        | 5.9%    |
| 2013 | 43        | 5.51%   |
| 2008 | 32        | 4.1%    |
| 2010 | 27        | 3.46%   |
| 2009 | 23        | 2.95%   |
| 2007 | 16        | 2.05%   |
| 2022 | 11        | 1.41%   |
| 2006 | 5         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 780       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 692       | 87.48%  |
| Enabled  | 99        | 12.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 778       | 99.74%  |
| Yes  | 2         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 200       | 25.38%  |
| 8.01-16.0   | 158       | 20.05%  |
| 16.01-24.0  | 156       | 19.8%   |
| 3.01-4.0    | 139       | 17.64%  |
| 32.01-64.0  | 69        | 8.76%   |
| 1.01-2.0    | 33        | 4.19%   |
| 24.01-32.0  | 13        | 1.65%   |
| 2.01-3.0    | 9         | 1.14%   |
| 0.51-1.0    | 7         | 0.89%   |
| 64.01-256.0 | 4         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 327       | 37.85%  |
| 2.01-3.0   | 214       | 24.77%  |
| 4.01-8.0   | 119       | 13.77%  |
| 3.01-4.0   | 101       | 11.69%  |
| 0.51-1.0   | 56        | 6.48%   |
| 8.01-16.0  | 33        | 3.82%   |
| 16.01-24.0 | 7         | 0.81%   |
| 0.01-0.5   | 4         | 0.46%   |
| 24.01-32.0 | 2         | 0.23%   |
| 32.01-64.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 598       | 75.31%  |
| 2      | 162       | 20.4%   |
| 3      | 25        | 3.15%   |
| 0      | 6         | 0.76%   |
| 4      | 2         | 0.25%   |
| 5      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 512       | 65.22%  |
| Yes       | 273       | 34.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 653       | 83.5%   |
| No        | 129       | 16.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 772       | 98.97%  |
| No        | 8         | 1.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 598       | 76.28%  |
| No        | 186       | 23.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 780       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 476       | 58.48%  |
| Graz                      | 46        | 5.65%   |
| Salzburg                  | 19        | 2.33%   |
| Linz                      | 18        | 2.21%   |
| Bad Hall                  | 18        | 2.21%   |
| Innsbruck                 | 15        | 1.84%   |
| Klagenfurt                | 9         | 1.11%   |
| Perg                      | 6         | 0.74%   |
| Leonding                  | 6         | 0.74%   |
| Wörgl                    | 5         | 0.61%   |
| Wiener Neustadt           | 5         | 0.61%   |
| Wels                      | 5         | 0.61%   |
| Villach                   | 5         | 0.61%   |
| Sankt Pölten             | 5         | 0.61%   |
| Korneuburg                | 5         | 0.61%   |
| Baden bei Wien            | 5         | 0.61%   |
| Umhausen                  | 4         | 0.49%   |
| Dornbirn                  | 4         | 0.49%   |
| Bregenz                   | 4         | 0.49%   |
| Traun                     | 3         | 0.37%   |
| Hard                      | 3         | 0.37%   |
| Gaenserndorf              | 3         | 0.37%   |
| Woerdern                  | 2         | 0.25%   |
| Traunkirchen              | 2         | 0.25%   |
| Traiskirchen              | 2         | 0.25%   |
| Spielberg bei Knittelfeld | 2         | 0.25%   |
| Neusiedl am See           | 2         | 0.25%   |
| Mauthausen                | 2         | 0.25%   |
| Mautern                   | 2         | 0.25%   |
| Lech                      | 2         | 0.25%   |
| Hartberg                  | 2         | 0.25%   |
| Hallwang                  | 2         | 0.25%   |
| Gross-Enzersdorf          | 2         | 0.25%   |
| Fraham                    | 2         | 0.25%   |
| Feldkirch                 | 2         | 0.25%   |
| Eisenstadt                | 2         | 0.25%   |
| Deutsch Griffen           | 2         | 0.25%   |
| Zell am See               | 1         | 0.12%   |
| Wolfern                   | 1         | 0.12%   |
| Wildon                    | 1         | 0.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 224       | 310    | 23.6%   |
| SanDisk                        | 93        | 128    | 9.8%    |
| Seagate                        | 86        | 111    | 9.06%   |
| WDC                            | 79        | 104    | 8.32%   |
| Toshiba                        | 79        | 97     | 8.32%   |
| Unknown                        | 48        | 62     | 5.06%   |
| SK hynix                       | 42        | 53     | 4.43%   |
| Kingston                       | 40        | 50     | 4.21%   |
| Crucial                        | 29        | 39     | 3.06%   |
| Intel                          | 28        | 30     | 2.95%   |
| Hitachi                        | 25        | 27     | 2.63%   |
| HGST                           | 25        | 30     | 2.63%   |
| Micron Technology              | 21        | 27     | 2.21%   |
| Intenso                        | 13        | 15     | 1.37%   |
| Apple                          | 13        | 24     | 1.37%   |
| Transcend                      | 12        | 14     | 1.26%   |
| KIOXIA                         | 10        | 13     | 1.05%   |
| LITEONIT                       | 6         | 8      | 0.63%   |
| LITEON                         | 5         | 6      | 0.53%   |
| China                          | 5         | 5      | 0.53%   |
| A-DATA Technology              | 5         | 8      | 0.53%   |
| Phison                         | 4         | 4      | 0.42%   |
| ASMT                           | 4         | 6      | 0.42%   |
| SABRENT                        | 3         | 3      | 0.32%   |
| OCZ                            | 3         | 4      | 0.32%   |
| Lenovo                         | 3         | 4      | 0.32%   |
| INNOVATION IT                  | 3         | 3      | 0.32%   |
| Unknown                        | 3         | 4      | 0.32%   |
| UMIS                           | 2         | 2      | 0.21%   |
| Solid State Storage Technology | 2         | 2      | 0.21%   |
| Micron/Crucial Technology      | 2         | 2      | 0.21%   |
| Leven                          | 2         | 2      | 0.21%   |
| ICY BOX                        | 2         | 2      | 0.21%   |
| Hewlett-Packard                | 2         | 1      | 0.21%   |
| GOODRAM                        | 2         | 2      | 0.21%   |
| Fujitsu                        | 2         | 2      | 0.21%   |
| Corsair                        | 2         | 2      | 0.21%   |
| Verbatim                       | 1         | 1      | 0.11%   |
| Vaseky                         | 1         | 1      | 0.11%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB          | 23        | 2.31%   |
| SanDisk NVMe SSD Drive 512GB          | 12        | 1.2%    |
| Samsung NVMe SSD Drive 1TB            | 12        | 1.2%    |
| Toshiba MQ01ABD100 1TB                | 11        | 1.1%    |
| Samsung SSD 850 EVO 250GB             | 11        | 1.1%    |
| Samsung SSD 860 EVO 500GB             | 9         | 0.9%    |
| Samsung NVMe SSD Drive 1024GB         | 9         | 0.9%    |
| SK hynix NVMe SSD Drive 512GB         | 8         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 8         | 0.8%    |
| Transcend TS240GMTS420S 240GB SSD     | 7         | 0.7%    |
| Toshiba MQ04ABF100 1TB                | 7         | 0.7%    |
| Seagate ST9500325AS 500GB             | 7         | 0.7%    |
| Seagate ST500LT012-1DG142 500GB       | 7         | 0.7%    |
| Samsung NVMe SSD Drive 500GB          | 7         | 0.7%    |
| Apple SSD AP0512M 500GB               | 7         | 0.7%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 6         | 0.6%    |
| SanDisk SSD PLUS 240GB                | 6         | 0.6%    |
| Samsung SSD 850 PRO 256GB             | 6         | 0.6%    |
| Kingston SV300S37A120G 120GB SSD      | 6         | 0.6%    |
| Kingston NVMe SSD Drive 512GB         | 6         | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB          | 5         | 0.5%    |
| Toshiba NVMe SSD Drive 512GB          | 5         | 0.5%    |
| Toshiba NVMe SSD Drive 256GB          | 5         | 0.5%    |
| Toshiba MQ01ABF050 500GB              | 5         | 0.5%    |
| SK hynix HFS256G39TND-N210A 256GB SSD | 5         | 0.5%    |
| Seagate ST2000LM015-2E8174 2TB        | 5         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 0.5%    |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 5         | 0.5%    |
| Samsung SSD 970 EVO Plus 1TB          | 5         | 0.5%    |
| Samsung SSD 850 EVO 500GB             | 5         | 0.5%    |
| Samsung MZVLB1T0HBLR-000L7 1TB        | 5         | 0.5%    |
| Kingston SA400S37480G 480GB SSD       | 5         | 0.5%    |
| Intel NVMe SSD Drive 512GB            | 5         | 0.5%    |
| HGST HTS721010A9E630 1TB              | 5         | 0.5%    |
| HGST HTS541010A9E680 1TB              | 5         | 0.5%    |
| Unknown MMC Card  64GB                | 4         | 0.4%    |
| Unknown MMC Card  32GB                | 4         | 0.4%    |
| SK hynix NVMe SSD Drive 1024GB        | 4         | 0.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 4         | 0.4%    |
| SanDisk NVMe SSD Drive 256GB          | 4         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 84        | 109    | 34.71%  |
| WDC                 | 48        | 62     | 19.83%  |
| Toshiba             | 48        | 63     | 19.83%  |
| Hitachi             | 25        | 27     | 10.33%  |
| HGST                | 25        | 30     | 10.33%  |
| Samsung Electronics | 5         | 6      | 2.07%   |
| SABRENT             | 3         | 3      | 1.24%   |
| Fujitsu             | 2         | 2      | 0.83%   |
| Inateck             | 1         | 1      | 0.41%   |
| Apple               | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 105       | 132    | 29.75%  |
| SanDisk             | 66        | 93     | 18.7%   |
| Kingston            | 28        | 33     | 7.93%   |
| Crucial             | 28        | 38     | 7.93%   |
| Transcend           | 12        | 14     | 3.4%    |
| SK hynix            | 12        | 15     | 3.4%    |
| Intenso             | 12        | 14     | 3.4%    |
| Micron Technology   | 11        | 14     | 3.12%   |
| Intel               | 10        | 10     | 2.83%   |
| Toshiba             | 8         | 10     | 2.27%   |
| WDC                 | 6         | 7      | 1.7%    |
| LITEONIT            | 6         | 8      | 1.7%    |
| LITEON              | 5         | 6      | 1.42%   |
| China               | 5         | 5      | 1.42%   |
| A-DATA Technology   | 5         | 8      | 1.42%   |
| Apple               | 4         | 4      | 1.13%   |
| OCZ                 | 3         | 4      | 0.85%   |
| INNOVATION IT       | 3         | 3      | 0.85%   |
| Phison              | 2         | 2      | 0.57%   |
| Leven               | 2         | 2      | 0.57%   |
| GOODRAM             | 2         | 2      | 0.57%   |
| Corsair             | 2         | 2      | 0.57%   |
| ASMT                | 2         | 2      | 0.57%   |
| Verbatim            | 1         | 1      | 0.28%   |
| Vaseky              | 1         | 1      | 0.28%   |
| Unknown             | 1         | 2      | 0.28%   |
| Teclast             | 1         | 1      | 0.28%   |
| TCSUNBOW            | 1         | 1      | 0.28%   |
| SPCC                | 1         | 1      | 0.28%   |
| Seagate             | 1         | 1      | 0.28%   |
| Netac               | 1         | 1      | 0.28%   |
| Mushkin             | 1         | 1      | 0.28%   |
| KingDian            | 1         | 1      | 0.28%   |
| Hewlett-Packard     | 1         | 1      | 0.28%   |
| Emtec               | 1         | 1      | 0.28%   |
| BIWIN               | 1         | 1      | 0.28%   |
| Apacer              | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 331       | 443    | 36.1%   |
| NVMe    | 296       | 401    | 32.28%  |
| HDD     | 231       | 304    | 25.19%  |
| MMC     | 48        | 66     | 5.23%   |
| Unknown | 11        | 12     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 500       | 717    | 56.95%  |
| NVMe | 295       | 400    | 33.6%   |
| MMC  | 48        | 66     | 5.47%   |
| SAS  | 35        | 43     | 3.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 393       | 541    | 70.94%  |
| 0.51-1.0   | 139       | 177    | 25.09%  |
| 1.01-2.0   | 16        | 23     | 2.89%   |
| 4.01-10.0  | 3         | 3      | 0.54%   |
| 3.01-4.0   | 2         | 2      | 0.36%   |
| 2.01-3.0   | 1         | 1      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 250       | 30.71%  |
| 251-500        | 198       | 24.32%  |
| 501-1000       | 110       | 13.51%  |
| 1-20           | 58        | 7.13%   |
| 51-100         | 51        | 6.27%   |
| 1001-2000      | 42        | 5.16%   |
| Unknown        | 42        | 5.16%   |
| 21-50          | 35        | 4.3%    |
| More than 3000 | 17        | 2.09%   |
| 2001-3000      | 11        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 334       | 39.57%  |
| 21-50          | 155       | 18.36%  |
| 101-250        | 125       | 14.81%  |
| 51-100         | 86        | 10.19%  |
| 251-500        | 46        | 5.45%   |
| Unknown        | 42        | 4.98%   |
| 501-1000       | 36        | 4.27%   |
| 1001-2000      | 14        | 1.66%   |
| More than 3000 | 3         | 0.36%   |
| 2001-3000      | 3         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB               | 4         | 4      | 8.89%   |
| Toshiba MQ01ABF050 500GB                         | 2         | 3      | 4.44%   |
| HGST HTS721010A9E630 1TB                         | 2         | 3      | 4.44%   |
| WDC WD5000LPLX-00ZNTT0 500GB                     | 1         | 1      | 2.22%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 2.22%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 2.22%   |
| Toshiba MQ01ABD100M 1TB                          | 1         | 1      | 2.22%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.22%   |
| Toshiba MK7559GSXP 752GB                         | 1         | 1      | 2.22%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 2.22%   |
| Toshiba MK3276GSX 320GB                          | 1         | 1      | 2.22%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 2.22%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 2.22%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 2      | 2.22%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 2.22%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB              | 1         | 8      | 2.22%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 2.22%   |
| Samsung Electronics SSD 840 Series 120GB         | 1         | 1      | 2.22%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB SSD | 1         | 1      | 2.22%   |
| Samsung Electronics MMCRE28G8MXP-0VBH1 128GB SSD | 1         | 1      | 2.22%   |
| Samsung Electronics HN-M101MBB 1TB               | 1         | 1      | 2.22%   |
| Samsung Electronics HM500JI 500GB                | 1         | 1      | 2.22%   |
| LITEONIT LCS-128L9S-11 2.5 7mm 128GB SSD         | 1         | 1      | 2.22%   |
| LITEONIT CMT-64L3M 64GB SSD                      | 1         | 2      | 2.22%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 1      | 2.22%   |
| Intel SSDSC2BF240A5L 240GB                       | 1         | 1      | 2.22%   |
| Intel SSDPEKNW512G8H 512GB                       | 1         | 1      | 2.22%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 2      | 2.22%   |
| Hitachi HTS725032A9A364 320GB                    | 1         | 1      | 2.22%   |
| Hitachi HTS547575A9E384 752GB                    | 1         | 1      | 2.22%   |
| Hitachi HTS543232A7A384 320GB                    | 1         | 1      | 2.22%   |
| Hitachi HTS543216A7A384 160GB                    | 1         | 1      | 2.22%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.22%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.22%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 2.22%   |
| GOODRAM C40 120GB SSD                            | 1         | 1      | 2.22%   |
| Fujitsu MHY2200BH 200GB                          | 1         | 1      | 2.22%   |
| Crucial CT512M550SSD3 512GB                      | 1         | 1      | 2.22%   |
| Corsair Neutron GTX SSD 120GB                    | 1         | 1      | 2.22%   |
| A-DATA Technology SSD DP900 128GB-DL3            | 1         | 3      | 2.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 9      | 18.6%   |
| Seagate             | 8         | 17     | 18.6%   |
| Samsung Electronics | 5         | 6      | 11.63%  |
| Hitachi             | 5         | 6      | 11.63%  |
| HGST                | 5         | 6      | 11.63%  |
| WDC                 | 2         | 2      | 4.65%   |
| LITEONIT            | 2         | 3      | 4.65%   |
| Intel               | 2         | 2      | 4.65%   |
| LITEON              | 1         | 1      | 2.33%   |
| GOODRAM             | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| Crucial             | 1         | 1      | 2.33%   |
| Corsair             | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 3      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 8         | 9      | 25.81%  |
| Seagate             | 8         | 17     | 25.81%  |
| Hitachi             | 5         | 6      | 16.13%  |
| HGST                | 5         | 6      | 16.13%  |
| WDC                 | 2         | 2      | 6.45%   |
| Samsung Electronics | 2         | 2      | 6.45%   |
| Fujitsu             | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 43     | 71.43%  |
| SSD  | 11        | 15     | 26.19%  |
| NVMe | 1         | 1      | 2.38%   |

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
| Detected | 494       | 758    | 59.09%  |
| Works    | 300       | 409    | 35.89%  |
| Malfunc  | 42        | 59     | 5.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 522       | 57.81%  |
| Samsung Electronics            | 123       | 13.62%  |
| AMD                            | 87        | 9.63%   |
| SanDisk                        | 50        | 5.54%   |
| SK hynix                       | 31        | 3.43%   |
| Toshiba America Info Systems   | 26        | 2.88%   |
| Kingston Technology Company    | 13        | 1.44%   |
| Micron Technology              | 10        | 1.11%   |
| KIOXIA                         | 10        | 1.11%   |
| Apple                          | 8         | 0.89%   |
| Nvidia                         | 6         | 0.66%   |
| Union Memory (Shenzhen)        | 5         | 0.55%   |
| Micron/Crucial Technology      | 3         | 0.33%   |
| Lenovo                         | 3         | 0.33%   |
| Solid State Storage Technology | 2         | 0.22%   |
| Phison Electronics             | 2         | 0.22%   |
| VIA Technologies               | 1         | 0.11%   |
| Seagate Technology             | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 77        | 7.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 70        | 7.22%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 69        | 7.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 62        | 6.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 58        | 5.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 41        | 4.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 32        | 3.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 28        | 2.89%   |
| Samsung NVMe SSD Controller 980                                                  | 25        | 2.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 25        | 2.58%   |
| Intel Volume Management Device NVMe RAID Controller                              | 20        | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 18        | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 18        | 1.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 17        | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 1.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 16        | 1.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 15        | 1.55%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 13        | 1.34%   |
| SK hynix Non-Volatile memory controller                                          | 13        | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 1.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 11        | 1.14%   |
| Intel SSD 660P Series                                                            | 11        | 1.14%   |
| Micron Non-Volatile memory controller                                            | 10        | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 1.03%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 9         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 0.83%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 8         | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 0.83%   |
| Apple ANS2 NVMe Controller                                                       | 8         | 0.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 7         | 0.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 0.72%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.62%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 0.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 535       | 56.43%  |
| NVMe | 296       | 31.22%  |
| RAID | 64        | 6.75%   |
| IDE  | 53        | 5.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 634       | 81.28%  |
| AMD    | 146       | 18.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 2.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 2.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.54%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 11        | 1.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 1.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.28%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 1.15%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 1.15%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.03%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 8         | 1.03%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.9%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 7         | 0.9%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.9%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.9%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.9%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.77%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.77%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 6         | 0.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.64%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 5         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 5         | 0.64%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 217       | 27.82%  |
| Intel Core i5           | 198       | 25.38%  |
| Intel Core 2 Duo        | 44        | 5.64%   |
| Other                   | 43        | 5.51%   |
| AMD Ryzen 7             | 39        | 5%      |
| Intel Core i3           | 31        | 3.97%   |
| AMD Ryzen 5             | 31        | 3.97%   |
| Intel Celeron           | 28        | 3.59%   |
| Intel Pentium           | 23        | 2.95%   |
| Intel Atom              | 17        | 2.18%   |
| AMD Ryzen 7 PRO         | 17        | 2.18%   |
| Intel Pentium Dual-Core | 9         | 1.15%   |
| AMD A4                  | 9         | 1.15%   |
| Intel Core i9           | 6         | 0.77%   |
| AMD Ryzen 9             | 6         | 0.77%   |
| Intel Core 2            | 5         | 0.64%   |
| AMD E2                  | 5         | 0.64%   |
| AMD A6                  | 5         | 0.64%   |
| Intel Pentium Silver    | 4         | 0.51%   |
| Intel Genuine           | 4         | 0.51%   |
| AMD Ryzen 5 PRO         | 4         | 0.51%   |
| AMD E1                  | 4         | 0.51%   |
| AMD A8                  | 4         | 0.51%   |
| AMD E                   | 3         | 0.38%   |
| AMD Athlon II           | 3         | 0.38%   |
| Intel Xeon              | 2         | 0.26%   |
| Intel Pentium Dual      | 2         | 0.26%   |
| Intel Core m5           | 2         | 0.26%   |
| AMD Turion 64 X2 Mobile | 2         | 0.26%   |
| AMD Ryzen 3             | 2         | 0.26%   |
| AMD Athlon              | 2         | 0.26%   |
| AMD A10                 | 2         | 0.26%   |
| Intel Core m7           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |
| Intel Core 2 Solo       | 1         | 0.13%   |
| Intel Celeron M         | 1         | 0.13%   |
| AMD PRO A8              | 1         | 0.13%   |
| AMD Phenom II           | 1         | 0.13%   |
| AMD C-50                | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 373       | 47.82%  |
| 4       | 271       | 34.74%  |
| 8       | 63        | 8.08%   |
| 6       | 57        | 7.31%   |
| 1       | 11        | 1.41%   |
| 12      | 3         | 0.38%   |
| 14      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 780       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 591       | 75.58%  |
| 1       | 190       | 24.3%   |
| Unknown | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 762       | 97.57%  |
| Unknown        | 13        | 1.66%   |
| 32-bit         | 6         | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 17.25%  |
| 0x206a7    | 60        | 7.44%   |
| 0x306a9    | 52        | 6.45%   |
| 0x806ec    | 38        | 4.71%   |
| 0x806ea    | 32        | 3.97%   |
| 0x406e3    | 29        | 3.6%    |
| 0x306d4    | 28        | 3.47%   |
| 0x1067a    | 28        | 3.47%   |
| 0x906ea    | 26        | 3.23%   |
| 0x806c1    | 26        | 3.23%   |
| 0x40651    | 26        | 3.23%   |
| 0x806e9    | 21        | 2.61%   |
| 0x306c3    | 17        | 2.11%   |
| 0x08600106 | 17        | 2.11%   |
| 0x506e3    | 14        | 1.74%   |
| 0x0a50000c | 12        | 1.49%   |
| 0x08108102 | 12        | 1.49%   |
| 0x906e9    | 11        | 1.36%   |
| 0x706e5    | 11        | 1.36%   |
| 0x10676    | 11        | 1.36%   |
| 0x08600103 | 11        | 1.36%   |
| 0x506c9    | 10        | 1.24%   |
| 0x20655    | 10        | 1.24%   |
| 0xa0652    | 9         | 1.12%   |
| 0x406c3    | 9         | 1.12%   |
| 0x806eb    | 8         | 0.99%   |
| 0x30678    | 8         | 0.99%   |
| 0x08608103 | 8         | 0.99%   |
| 0x08600104 | 7         | 0.87%   |
| 0x20652    | 6         | 0.74%   |
| 0x07030105 | 6         | 0.74%   |
| 0x05000119 | 6         | 0.74%   |
| 0x6fd      | 5         | 0.62%   |
| 0x406c4    | 5         | 0.62%   |
| 0x106ca    | 5         | 0.62%   |
| 0x06006705 | 5         | 0.62%   |
| 0x906ed    | 4         | 0.5%    |
| 0x906c0    | 4         | 0.5%    |
| 0x906a3    | 4         | 0.5%    |
| 0x706a8    | 4         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 167       | 21.41%  |
| SandyBridge      | 66        | 8.46%   |
| IvyBridge        | 65        | 8.33%   |
| Haswell          | 55        | 7.05%   |
| Skylake          | 47        | 6.03%   |
| Penryn           | 47        | 6.03%   |
| Zen 2            | 46        | 5.9%    |
| TigerLake        | 32        | 4.1%    |
| Broadwell        | 31        | 3.97%   |
| Silvermont       | 24        | 3.08%   |
| Zen+             | 19        | 2.44%   |
| Zen 3            | 19        | 2.44%   |
| Westmere         | 19        | 2.44%   |
| Core             | 16        | 2.05%   |
| Unknown          | 16        | 2.05%   |
| Icelake          | 15        | 1.92%   |
| Goldmont         | 10        | 1.28%   |
| CometLake        | 10        | 1.28%   |
| Excavator        | 9         | 1.15%   |
| Bobcat           | 9         | 1.15%   |
| Puma             | 8         | 1.03%   |
| Goldmont plus    | 8         | 1.03%   |
| Bonnell          | 8         | 1.03%   |
| Zen              | 6         | 0.77%   |
| Jaguar           | 5         | 0.64%   |
| K10              | 4         | 0.51%   |
| Alderlake Hybrid | 4         | 0.51%   |
| P6               | 3         | 0.38%   |
| Nehalem          | 3         | 0.38%   |
| K8 Hammer        | 3         | 0.38%   |
| Tremont          | 2         | 0.26%   |
| Piledriver       | 2         | 0.26%   |
| K10 Llano        | 2         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 542       | 55.7%   |
| AMD    | 217       | 22.3%   |
| Nvidia | 214       | 21.99%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 62        | 6.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 5.01%   |
| AMD Renoir                                                                               | 45        | 4.51%   |
| Intel UHD Graphics 620                                                                   | 36        | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 33        | 3.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 30        | 3.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 3.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 27        | 2.71%   |
| Intel HD Graphics 620                                                                    | 27        | 2.71%   |
| Intel HD Graphics 5500                                                                   | 26        | 2.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 2.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 1.8%    |
| AMD Cezanne                                                                              | 17        | 1.7%    |
| Intel Core Processor Integrated Graphics Controller                                      | 16        | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.5%    |
| Intel HD Graphics 530                                                                    | 12        | 1.2%    |
| Nvidia GP108M [GeForce MX250]                                                            | 11        | 1.1%    |
| AMD Lucienne                                                                             | 10        | 1%      |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.9%    |
| Intel HD Graphics 630                                                                    | 9         | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.9%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 9         | 0.9%    |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.7%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.7%    |
| Nvidia G84M [GeForce 8600M GT]                                                           | 7         | 0.7%    |
| Intel HD Graphics 500                                                                    | 7         | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.6%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.5%    |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.5%    |
| Nvidia GP107M [GeForce MX350]                                                            | 5         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 365       | 46.68%  |
| 1 x AMD        | 151       | 19.31%  |
| Intel + Nvidia | 141       | 18.03%  |
| 1 x Nvidia     | 59        | 7.54%   |
| Intel + AMD    | 37        | 4.73%   |
| AMD + Nvidia   | 15        | 1.92%   |
| 2 x AMD        | 14        | 1.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 681       | 86.31%  |
| Proprietary | 96        | 12.17%  |
| Unknown     | 12        | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 462       | 57.75%  |
| 1.01-2.0   | 106       | 13.25%  |
| 0.01-0.5   | 104       | 13%     |
| 0.51-1.0   | 55        | 6.88%   |
| 3.01-4.0   | 52        | 6.5%    |
| 7.01-8.0   | 10        | 1.25%   |
| 5.01-6.0   | 8         | 1%      |
| 2.01-3.0   | 2         | 0.25%   |
| 8.01-16.0  | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 184       | 20.38%  |
| LG Display              | 136       | 15.06%  |
| Chimei Innolux          | 101       | 11.18%  |
| Samsung Electronics     | 98        | 10.85%  |
| BOE                     | 91        | 10.08%  |
| Sharp                   | 30        | 3.32%   |
| Lenovo                  | 28        | 3.1%    |
| Dell                    | 25        | 2.77%   |
| Apple                   | 24        | 2.66%   |
| Hewlett-Packard         | 17        | 1.88%   |
| Goldstar                | 17        | 1.88%   |
| Chi Mei Optoelectronics | 15        | 1.66%   |
| InfoVision              | 10        | 1.11%   |
| Acer                    | 10        | 1.11%   |
| PANDA                   | 9         | 1%      |
| AOC                     | 9         | 1%      |
| LG Philips              | 7         | 0.78%   |
| Iiyama                  | 7         | 0.78%   |
| Philips                 | 6         | 0.66%   |
| CSO                     | 6         | 0.66%   |
| BenQ                    | 6         | 0.66%   |
| Eizo                    | 5         | 0.55%   |
| CPT                     | 5         | 0.55%   |
| Ancor Communications    | 5         | 0.55%   |
| HannStar                | 4         | 0.44%   |
| Gericom                 | 4         | 0.44%   |
| Toshiba                 | 3         | 0.33%   |
| Panasonic               | 3         | 0.33%   |
| LGD                     | 3         | 0.33%   |
| TMX                     | 2         | 0.22%   |
| Sony                    | 2         | 0.22%   |
| Fujitsu Siemens         | 2         | 0.22%   |
| CMN                     | 2         | 0.22%   |
| ASUSTek Computer        | 2         | 0.22%   |
| ANX                     | 2         | 0.22%   |
| Analogix                | 2         | 0.22%   |
| WYT                     | 1         | 0.11%   |
| Vestel Elektronik       | 1         | 0.11%   |
| Unknown                 | 1         | 0.11%   |
| TM@                     | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.87%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                 | 8         | 0.87%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.76%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.76%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 6         | 0.65%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 6         | 0.65%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.65%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 6         | 0.65%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 5         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.54%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 5         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.54%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                 | 5         | 0.54%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 4         | 0.43%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1362 1366x768 293x164mm 13.2-inch       | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch      | 4         | 0.43%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch        | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO1136 2560x1440 309x174mm 14.0-inch        | 4         | 0.43%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 4         | 0.43%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.33%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch               | 3         | 0.33%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3143 1366x768 256x144mm 11.6-inch  | 3         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 3         | 0.33%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 3         | 0.33%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 396       | 46.86%  |
| 1366x768 (WXGA)    | 158       | 18.7%   |
| 1600x900 (HD+)     | 67        | 7.93%   |
| 3840x2160 (4K)     | 38        | 4.5%    |
| 2560x1440 (QHD)    | 36        | 4.26%   |
| 1280x800 (WXGA)    | 36        | 4.26%   |
| 1440x900 (WXGA+)   | 21        | 2.49%   |
| 1920x1200 (WUXGA)  | 15        | 1.78%   |
| 1680x1050 (WSXGA+) | 11        | 1.3%    |
| 2880x1800          | 9         | 1.07%   |
| 3440x1440          | 7         | 0.83%   |
| 3840x2400          | 6         | 0.71%   |
| 1280x1024 (SXGA)   | 6         | 0.71%   |
| 1024x600           | 6         | 0.71%   |
| 2560x1600          | 5         | 0.59%   |
| 800x1280           | 4         | 0.47%   |
| 3200x1800 (QHD+)   | 4         | 0.47%   |
| 3840x1080          | 3         | 0.36%   |
| 2560x1080          | 3         | 0.36%   |
| 1920x540           | 3         | 0.36%   |
| Unknown            | 3         | 0.36%   |
| 1600x1200          | 2         | 0.24%   |
| 3456x2160          | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 2160x1440          | 1         | 0.12%   |
| 1680x945           | 1         | 0.12%   |
| 1360x768           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 316       | 35.03%  |
| 13      | 125       | 13.86%  |
| 14      | 117       | 12.97%  |
| 17      | 93        | 10.31%  |
| 27      | 48        | 5.32%   |
| 12      | 30        | 3.33%   |
| 24      | 29        | 3.22%   |
| 23      | 23        | 2.55%   |
| Unknown | 19        | 2.11%   |
| 21      | 15        | 1.66%   |
| 11      | 12        | 1.33%   |
| 34      | 10        | 1.11%   |
| 10      | 9         | 1%      |
| 31      | 7         | 0.78%   |
| 16      | 7         | 0.78%   |
| 25      | 6         | 0.67%   |
| 22      | 6         | 0.67%   |
| 19      | 6         | 0.67%   |
| 18      | 6         | 0.67%   |
| 54      | 4         | 0.44%   |
| 84      | 2         | 0.22%   |
| 32      | 2         | 0.22%   |
| 142     | 1         | 0.11%   |
| 65      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 49      | 1         | 0.11%   |
| 47      | 1         | 0.11%   |
| 40      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 28      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 20      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 489       | 54.7%   |
| 201-300        | 116       | 12.98%  |
| 351-400        | 107       | 11.97%  |
| 501-600        | 89        | 9.96%   |
| 401-500        | 29        | 3.24%   |
| 601-700        | 20        | 2.24%   |
| Unknown        | 19        | 2.13%   |
| 701-800        | 12        | 1.34%   |
| 1001-1500      | 8         | 0.89%   |
| 801-900        | 2         | 0.22%   |
| 1501-2000      | 2         | 0.22%   |
| More than 2000 | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 646       | 81.67%  |
| 16/10   | 105       | 13.27%  |
| Unknown | 12        | 1.52%   |
| 21/9    | 10        | 1.26%   |
| 5/4     | 5         | 0.63%   |
| 3/2     | 4         | 0.51%   |
| 0.62    | 4         | 0.51%   |
| 32/9    | 2         | 0.25%   |
| 6/5     | 1         | 0.13%   |
| 4/3     | 1         | 0.13%   |
| 1.00    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 316       | 35.19%  |
| 81-90          | 186       | 20.71%  |
| 121-130        | 82        | 9.13%   |
| 71-80          | 55        | 6.12%   |
| 201-250        | 50        | 5.57%   |
| 301-350        | 48        | 5.35%   |
| 61-70          | 30        | 3.34%   |
| 251-300        | 21        | 2.34%   |
| 351-500        | 20        | 2.23%   |
| Unknown        | 19        | 2.12%   |
| 151-200        | 14        | 1.56%   |
| 51-60          | 12        | 1.34%   |
| 131-140        | 12        | 1.34%   |
| More than 1000 | 9         | 1%      |
| 41-50          | 9         | 1%      |
| 141-150        | 5         | 0.56%   |
| 111-120        | 4         | 0.45%   |
| 501-1000       | 4         | 0.45%   |
| 91-100         | 2         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 393       | 44.46%  |
| 101-120       | 219       | 24.77%  |
| 51-100        | 150       | 16.97%  |
| 161-240       | 69        | 7.81%   |
| More than 240 | 27        | 3.05%   |
| Unknown       | 19        | 2.15%   |
| 1-50          | 7         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 636       | 78.91%  |
| 2     | 126       | 15.63%  |
| 3     | 20        | 2.48%   |
| 0     | 19        | 2.36%   |
| 4     | 5         | 0.62%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 480       | 38%     |
| Realtek Semiconductor             | 363       | 28.74%  |
| Qualcomm Atheros                  | 146       | 11.56%  |
| Broadcom                          | 67        | 5.3%    |
| Ericsson Business Mobile Networks | 15        | 1.19%   |
| Ralink                            | 14        | 1.11%   |
| Marvell Technology Group          | 14        | 1.11%   |
| Broadcom Limited                  | 14        | 1.11%   |
| Sierra Wireless                   | 13        | 1.03%   |
| Dell                              | 13        | 1.03%   |
| MediaTek                          | 11        | 0.87%   |
| Hewlett-Packard                   | 10        | 0.79%   |
| Lenovo                            | 9         | 0.71%   |
| DisplayLink                       | 9         | 0.71%   |
| Huawei Technologies               | 8         | 0.63%   |
| FIBOCOM                           | 7         | 0.55%   |
| Samsung Electronics               | 5         | 0.4%    |
| NetGear                           | 5         | 0.4%    |
| Edimax Technology                 | 5         | 0.4%    |
| ASIX Electronics                  | 5         | 0.4%    |
| TP-Link                           | 4         | 0.32%   |
| Qualcomm                          | 4         | 0.32%   |
| OnePlus                           | 4         | 0.32%   |
| Nvidia                            | 4         | 0.32%   |
| JMicron Technology                | 4         | 0.32%   |
| ZyXEL Communications              | 3         | 0.24%   |
| Ralink Technology                 | 3         | 0.24%   |
| Google                            | 3         | 0.24%   |
| ASUSTek Computer                  | 3         | 0.24%   |
| Xiaomi                            | 2         | 0.16%   |
| Qualcomm Atheros Communications   | 2         | 0.16%   |
| Linksys                           | 2         | 0.16%   |
| D-Link System                     | 2         | 0.16%   |
| Apple                             | 2         | 0.16%   |
| Sitecom Europe                    | 1         | 0.08%   |
| Research In Motion                | 1         | 0.08%   |
| Motorola PCS                      | 1         | 0.08%   |
| MicroPython                       | 1         | 0.08%   |
| Manta                             | 1         | 0.08%   |
| Cypress Semiconductor             | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 236       | 15.03%  |
| Intel Wi-Fi 6 AX200                                               | 65        | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 48        | 3.06%   |
| Intel Wireless 8265 / 8275                                        | 45        | 2.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 2.1%    |
| Intel Wireless 7265                                               | 32        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 29        | 1.85%   |
| Intel Wireless 8260                                               | 28        | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 1.59%   |
| Intel Wi-Fi 6 AX201                                               | 22        | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.34%   |
| Intel Wireless 7260                                               | 21        | 1.34%   |
| Intel Centrino Ultimate-N 6300                                    | 20        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 17        | 1.08%   |
| Intel Wireless 3165                                               | 16        | 1.02%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 0.89%   |
| Intel WiFi Link 5100                                              | 14        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.89%   |
| Intel Ethernet Connection I218-LM                                 | 13        | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.76%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 0.7%    |
| Intel Wireless-AC 9260                                            | 11        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 11        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 0.7%    |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 10        | 0.64%   |
| Intel Wireless 3160                                               | 9         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 467       | 55.93%  |
| Qualcomm Atheros                | 122       | 14.61%  |
| Realtek Semiconductor           | 98        | 11.74%  |
| Broadcom                        | 54        | 6.47%   |
| Ralink                          | 14        | 1.68%   |
| Sierra Wireless                 | 13        | 1.56%   |
| MediaTek                        | 11        | 1.32%   |
| Dell                            | 9         | 1.08%   |
| Broadcom Limited                | 8         | 0.96%   |
| FIBOCOM                         | 7         | 0.84%   |
| Edimax Technology               | 5         | 0.6%    |
| TP-Link                         | 4         | 0.48%   |
| NetGear                         | 4         | 0.48%   |
| ZyXEL Communications            | 3         | 0.36%   |
| Ralink Technology               | 3         | 0.36%   |
| Qualcomm                        | 3         | 0.36%   |
| ASUSTek Computer                | 3         | 0.36%   |
| Qualcomm Atheros Communications | 2         | 0.24%   |
| D-Link System                   | 2         | 0.24%   |
| Sitecom Europe                  | 1         | 0.12%   |
| Linksys                         | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 65        | 7.78%   |
| Intel Wireless 8265 / 8275                                              | 45        | 5.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 33        | 3.95%   |
| Intel Wireless 7265                                                     | 32        | 3.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 3.47%   |
| Intel Wireless 8260                                                     | 28        | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 2.99%   |
| Intel Wi-Fi 6 AX201                                                     | 22        | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.51%   |
| Intel Wireless 7260                                                     | 21        | 2.51%   |
| Intel Centrino Ultimate-N 6300                                          | 20        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 18        | 2.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 17        | 2.03%   |
| Intel Wireless 3165                                                     | 16        | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.67%   |
| Intel WiFi Link 5100                                                    | 14        | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 1.32%   |
| Intel Wireless-AC 9260                                                  | 11        | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 11        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 1.2%    |
| Intel Wireless 3160                                                     | 9         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 8         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.96%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.96%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 8         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.84%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 6         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 324       | 46.75%  |
| Intel                    | 219       | 31.6%   |
| Qualcomm Atheros         | 46        | 6.64%   |
| Broadcom                 | 25        | 3.61%   |
| Marvell Technology Group | 14        | 2.02%   |
| Lenovo                   | 9         | 1.3%    |
| DisplayLink              | 9         | 1.3%    |
| Broadcom Limited         | 6         | 0.87%   |
| Samsung Electronics      | 5         | 0.72%   |
| ASIX Electronics         | 5         | 0.72%   |
| OnePlus                  | 4         | 0.58%   |
| Nvidia                   | 4         | 0.58%   |
| JMicron Technology       | 4         | 0.58%   |
| Huawei Technologies      | 3         | 0.43%   |
| Google                   | 3         | 0.43%   |
| Xiaomi                   | 2         | 0.29%   |
| Hewlett-Packard          | 2         | 0.29%   |
| Apple                    | 2         | 0.29%   |
| Research In Motion       | 1         | 0.14%   |
| Qualcomm                 | 1         | 0.14%   |
| NetGear                  | 1         | 0.14%   |
| Motorola PCS             | 1         | 0.14%   |
| Linksys                  | 1         | 0.14%   |
| Cypress Semiconductor    | 1         | 0.14%   |
| Attansic Technology      | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 236       | 33.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 51        | 7.29%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 48        | 6.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 33        | 4.71%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 2.29%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 2%      |
| Intel Ethernet Connection (4) I219-V                              | 14        | 2%      |
| Intel Ethernet Connection I218-LM                                 | 13        | 1.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.71%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.71%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 1.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 1.43%   |
| Intel Ethernet Connection (7) I219-LM                             | 9         | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.86%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.71%   |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.71%   |
| Intel Ethernet Connection (13) I219-LM                            | 5         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.57%   |
| OnePlus OnePlus                                                   | 4         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.57%   |
| DisplayLink Dell Universal Dock D6000                             | 4         | 0.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 4         | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.43%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 772       | 52.99%  |
| Ethernet | 652       | 44.75%  |
| Modem    | 32        | 2.2%    |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 643       | 78.03%  |
| Ethernet | 181       | 21.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 585       | 75%     |
| 1     | 171       | 21.92%  |
| 3     | 15        | 1.92%   |
| 0     | 9         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 695       | 87.75%  |
| Yes  | 97        | 12.25%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 330       | 54.46%  |
| Realtek Semiconductor           | 57        | 9.41%   |
| Qualcomm Atheros Communications | 47        | 7.76%   |
| Broadcom                        | 36        | 5.94%   |
| IMC Networks                    | 24        | 3.96%   |
| Lite-On Technology              | 23        | 3.8%    |
| Foxconn / Hon Hai               | 16        | 2.64%   |
| Apple                           | 15        | 2.48%   |
| Hewlett-Packard                 | 13        | 2.15%   |
| Dell                            | 11        | 1.82%   |
| Cambridge Silicon Radio         | 9         | 1.49%   |
| Toshiba                         | 7         | 1.16%   |
| Ralink                          | 4         | 0.66%   |
| Foxconn International           | 4         | 0.66%   |
| Realtek                         | 2         | 0.33%   |
| MediaTek                        | 2         | 0.33%   |
| Alps Electric                   | 2         | 0.33%   |
| i.Tech Dynamic Limited          | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |
| Belkin Components               | 1         | 0.17%   |
| ASUSTek Computer                | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 139       | 22.94%  |
| Intel AX200 Bluetooth                               | 62        | 10.23%  |
| Intel AX201 Bluetooth                               | 49        | 8.09%   |
| Realtek Bluetooth Radio                             | 42        | 6.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 34        | 5.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 2.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 2.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 1.65%   |
| IMC Networks Bluetooth Radio                        | 10        | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 1.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 1.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 1.49%   |
| Apple Bluetooth Host Controller                     | 8         | 1.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.16%   |
| IMC Networks Bluetooth Device                       | 7         | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.99%   |
| Intel AX210 Bluetooth                               | 5         | 0.83%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.83%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.66%   |
| Lite-On Wireless_Device                             | 4         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.66%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.66%   |
| Toshiba Bluetooth Device                            | 3         | 0.5%    |
| IMC Networks Wireless_Device                        | 3         | 0.5%    |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 0.5%    |
| Broadcom BCM20702A0 Bluetooth                       | 3         | 0.5%    |
| Broadcom BCM2045 Bluetooth                          | 3         | 0.5%    |
| Apple Bluetooth HCI                                 | 3         | 0.5%    |
| Toshiba BCM43142A0                                  | 2         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 614       | 62.91%  |
| AMD                         | 176       | 18.03%  |
| Nvidia                      | 98        | 10.04%  |
| C-Media Electronics         | 9         | 0.92%   |
| Lenovo                      | 8         | 0.82%   |
| Apple                       | 8         | 0.82%   |
| GN Netcom                   | 7         | 0.72%   |
| Texas Instruments           | 6         | 0.61%   |
| Hewlett-Packard             | 6         | 0.61%   |
| Logitech                    | 5         | 0.51%   |
| Sennheiser Communications   | 4         | 0.41%   |
| Realtek Semiconductor       | 4         | 0.41%   |
| Plantronics                 | 4         | 0.41%   |
| Yamaha                      | 2         | 0.2%    |
| SteelSeries ApS             | 2         | 0.2%    |
| Sony                        | 2         | 0.2%    |
| Focusrite-Novation          | 2         | 0.2%    |
| Creative Technology         | 2         | 0.2%    |
| ZOOM                        | 1         | 0.1%    |
| XMOS                        | 1         | 0.1%    |
| Tenx Technology             | 1         | 0.1%    |
| Samsung Electronics         | 1         | 0.1%    |
| Roland                      | 1         | 0.1%    |
| RODE Microphones            | 1         | 0.1%    |
| No brand                    | 1         | 0.1%    |
| Microsoft                   | 1         | 0.1%    |
| Mackie Designs              | 1         | 0.1%    |
| M-Audio                     | 1         | 0.1%    |
| Kingston Technology         | 1         | 0.1%    |
| GYROCOM C&C                 | 1         | 0.1%    |
| Generalplus Technology      | 1         | 0.1%    |
| FiiO Electronics Technology | 1         | 0.1%    |
| Blue Microphones            | 1         | 0.1%    |
| BEHRINGER International     | 1         | 0.1%    |
| AudioQuest                  | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 100       | 8.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 99        | 8.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 72        | 6.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 62        | 5.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 59        | 4.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 35        | 2.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 2.87%   |
| Intel 8 Series HD Audio Controller                                                                | 34        | 2.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 32        | 2.7%    |
| Intel Broadwell-U Audio Controller                                                                | 31        | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 30        | 2.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 2.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 23        | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 1.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 22        | 1.85%   |
| AMD FCH Azalia Controller                                                                         | 21        | 1.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 1.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 16        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 12        | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 10        | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 0.67%   |
| Apple Audio Device                                                                                | 8         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 0.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7         | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 7         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 158       | 31.41%  |
| SK hynix              | 120       | 23.86%  |
| Micron Technology     | 73        | 14.51%  |
| Kingston              | 39        | 7.75%   |
| Unknown               | 32        | 6.36%   |
| Crucial               | 27        | 5.37%   |
| Ramaxel Technology    | 10        | 1.99%   |
| Corsair               | 10        | 1.99%   |
| Elpida                | 9         | 1.79%   |
| Unknown (ABCD)        | 6         | 1.19%   |
| G.Skill               | 3         | 0.6%    |
| A-DATA Technology     | 3         | 0.6%    |
| Silicon Power         | 2         | 0.4%    |
| Nanya Technology      | 2         | 0.4%    |
| GOODRAM               | 2         | 0.4%    |
| Vaseky                | 1         | 0.2%    |
| Transcend             | 1         | 0.2%    |
| Smart                 | 1         | 0.2%    |
| Kingmax Semiconductor | 1         | 0.2%    |
| CSX                   | 1         | 0.2%    |
| Avant                 | 1         | 0.2%    |
| Unknown               | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 2.61%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 9         | 1.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 1.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.12%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.12%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 6         | 1.12%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.93%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.93%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.75%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.75%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.75%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.75%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 4         | 0.75%   |
| Samsung RAM M4 70T5663EH3-CF7 2048MB SODIMM DDR2 975MT/s         | 4         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 3         | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 3         | 0.56%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 3         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.56%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                  | 3         | 0.56%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 211       | 49.88%  |
| DDR3    | 140       | 33.1%   |
| LPDDR4  | 25        | 5.91%   |
| DDR2    | 20        | 4.73%   |
| SDRAM   | 12        | 2.84%   |
| LPDDR3  | 12        | 2.84%   |
| LPDDR5  | 2         | 0.47%   |
| Unknown | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 376       | 88.68%  |
| Row Of Chips | 42        | 9.91%   |
| Chip         | 5         | 1.18%   |
| DIMM         | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 187       | 40.74%  |
| 4096  | 119       | 25.93%  |
| 16384 | 85        | 18.52%  |
| 2048  | 49        | 10.68%  |
| 1024  | 11        | 2.4%    |
| 32768 | 8         | 1.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 96        | 21.19%  |
| 2667    | 94        | 20.75%  |
| 3200    | 86        | 18.98%  |
| 2400    | 39        | 8.61%   |
| 2133    | 24        | 5.3%    |
| 1333    | 23        | 5.08%   |
| 1334    | 17        | 3.75%   |
| 667     | 10        | 2.21%   |
| 4267    | 9         | 1.99%   |
| 4199    | 7         | 1.55%   |
| Unknown | 7         | 1.55%   |
| 3266    | 5         | 1.1%    |
| 2048    | 5         | 1.1%    |
| 1867    | 5         | 1.1%    |
| 1067    | 5         | 1.1%    |
| 4266    | 4         | 0.88%   |
| 800     | 4         | 0.88%   |
| 8400    | 3         | 0.66%   |
| 4800    | 3         | 0.66%   |
| 6400    | 2         | 0.44%   |
| 533     | 2         | 0.44%   |
| 3733    | 1         | 0.22%   |
| 975     | 1         | 0.22%   |
| 333     | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 55.56%  |
| Samsung Electronics | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung SCX-4300 Series                               | 1         | 11.11%  |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 11.11%  |
| HP LaserJet 1200                                      | 1         | 11.11%  |
| HP LaserJet 1022                                      | 1         | 11.11%  |
| HP ENVY Pro 6400 series                               | 1         | 11.11%  |
| HP Deskjet 3520 series                                | 1         | 11.11%  |
| HP DeskJet 2620 All-in-One Printer                    | 1         | 11.11%  |
| Canon PIXMA iX6850 Printer                            | 1         | 11.11%  |
| Canon MG2100 series                                   | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan                | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 208       | 30.41%  |
| IMC Networks                           | 73        | 10.67%  |
| Acer                                   | 72        | 10.53%  |
| Microdia                               | 48        | 7.02%   |
| Sunplus Innovation Technology          | 38        | 5.56%   |
| Realtek Semiconductor                  | 36        | 5.26%   |
| Quanta                                 | 33        | 4.82%   |
| Suyin                                  | 26        | 3.8%    |
| Lite-On Technology                     | 25        | 3.65%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 3.51%   |
| Apple                                  | 16        | 2.34%   |
| Syntek                                 | 14        | 2.05%   |
| Alcor Micro                            | 8         | 1.17%   |
| Luxvisions Innotech Limited            | 7         | 1.02%   |
| Ricoh                                  | 6         | 0.88%   |
| Logitech                               | 6         | 0.88%   |
| Lenovo                                 | 6         | 0.88%   |
| Samsung Electronics                    | 5         | 0.73%   |
| Primax Electronics                     | 5         | 0.73%   |
| OmniVision Technologies                | 4         | 0.58%   |
| Silicon Motion                         | 3         | 0.44%   |
| Z-Star Microelectronics                | 2         | 0.29%   |
| Sony                                   | 2         | 0.29%   |
| Microsoft                              | 2         | 0.29%   |
| icSpring                               | 2         | 0.29%   |
| DigiTech                               | 2         | 0.29%   |
| SunplusIT                              | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.15%   |
| Nebraska Furniture Mart                | 1         | 0.15%   |
| Jieli Technology                       | 1         | 0.15%   |
| Goertek Electronics                    | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| GEMBIRD                                | 1         | 0.15%   |
| Alpha Imaging Technology               | 1         | 0.15%   |
| 8SSC21D67422V1SR25503GH                | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 51        | 7.43%   |
| IMC Networks Integrated Camera           | 36        | 5.25%   |
| Microdia Integrated_Webcam_HD            | 25        | 3.64%   |
| Acer Integrated Camera                   | 25        | 3.64%   |
| Chicony HD WebCam                        | 17        | 2.48%   |
| Chicony HP HD Camera                     | 16        | 2.33%   |
| Sunplus Integrated_Webcam_HD             | 11        | 1.6%    |
| Quanta HD User Facing                    | 11        | 1.6%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 10        | 1.46%   |
| Chicony TOSHIBA Web Camera - HD          | 10        | 1.46%   |
| Realtek USB2.0 HD UVC WebCam             | 9         | 1.31%   |
| Realtek Integrated_Webcam_HD             | 9         | 1.31%   |
| Lite-On HP HD Camera                     | 9         | 1.31%   |
| IMC Networks USB2.0 HD UVC WebCam        | 9         | 1.31%   |
| Quanta HP HD Camera                      | 8         | 1.17%   |
| Lite-On Integrated Camera                | 8         | 1.17%   |
| Chicony VGA WebCam                       | 8         | 1.17%   |
| Chicony USB2.0 HD UVC WebCam             | 8         | 1.17%   |
| Chicony HP HD Webcam                     | 8         | 1.17%   |
| Chicony Integrated HP HD Webcam          | 7         | 1.02%   |
| Chicony HP Truevision HD camera          | 7         | 1.02%   |
| Acer Lenovo EasyCamera                   | 7         | 1.02%   |
| Syntek Integrated Camera                 | 6         | 0.87%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 6         | 0.87%   |
| Acer SunplusIT Integrated Camera         | 6         | 0.87%   |
| Acer BisonCam, NB Pro                    | 6         | 0.87%   |
| Suyin Asus Integrated Webcam             | 5         | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode)  | 5         | 0.73%   |
| Realtek HD WebCam                        | 5         | 0.73%   |
| Lenovo Integrated Webcam [R5U877]        | 5         | 0.73%   |
| Chicony USB 2.0 Camera                   | 5         | 0.73%   |
| Chicony Integrated Camera (1280x720@30)  | 5         | 0.73%   |
| Chicony HD User Facing                   | 5         | 0.73%   |
| Chicony FJ Camera                        | 5         | 0.73%   |
| Apple FaceTime HD Camera                 | 5         | 0.73%   |
| Acer Lenovo Integrated Webcam            | 5         | 0.73%   |
| Syntek Lenovo EasyCamera                 | 4         | 0.58%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 4         | 0.58%   |
| Sunplus Laptop Integrated WebCam HD      | 4         | 0.58%   |
| Sunplus HD WebCam                        | 4         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 87        | 39.73%  |
| Synaptics                  | 73        | 33.33%  |
| Shenzhen Goodix Technology | 23        | 10.5%   |
| Upek                       | 13        | 5.94%   |
| AuthenTec                  | 13        | 5.94%   |
| LighTuning Technology      | 6         | 2.74%   |
| Elan Microelectronics      | 2         | 0.91%   |
| STMicroelectronics         | 1         | 0.46%   |
| Focal-systems.Corp         | 1         | 0.46%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 37        | 16.82%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 11.82%  |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 7.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 5.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 4.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 4.09%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 4.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 4.09%   |
| Unknown                                                                    | 7         | 3.18%   |
| Validity Sensors VFS491                                                    | 6         | 2.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.73%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.73%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 2.27%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.27%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.27%   |
| AuthenTec AES2810                                                          | 5         | 2.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.82%   |
| Synaptics WBDI Device                                                      | 3         | 1.36%   |
| LighTuning EgisTec_ES603                                                   | 3         | 1.36%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.91%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.91%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 0.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.91%   |
| Elan ELAN:Fingerprint                                                      | 2         | 0.91%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.45%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.45%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.45%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.45%   |
| AuthenTec AES1600                                                          | 1         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 51        | 49.04%  |
| Broadcom              | 31        | 29.81%  |
| Upek                  | 8         | 7.69%   |
| Lenovo                | 8         | 7.69%   |
| O2 Micro              | 3         | 2.88%   |
| SCM Microsystems      | 1         | 0.96%   |
| Realtek Semiconductor | 1         | 0.96%   |
| Advanced Card Systems | 1         | 0.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 49.04%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 11.54%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 9.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 7.69%   |
| Broadcom 58200                                                               | 5         | 4.81%   |
| Broadcom 5880                                                                | 4         | 3.85%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.88%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.96%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 431       | 53.34%  |
| 1     | 289       | 35.77%  |
| 2     | 60        | 7.43%   |
| 3     | 20        | 2.48%   |
| 4     | 4         | 0.5%    |
| 8     | 2         | 0.25%   |
| 6     | 1         | 0.12%   |
| 5     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 214       | 43.94%  |
| Chipcard                 | 80        | 16.43%  |
| Graphics card            | 61        | 12.53%  |
| Net/wireless             | 47        | 9.65%   |
| Multimedia controller    | 19        | 3.9%    |
| Bluetooth                | 13        | 2.67%   |
| Sound                    | 12        | 2.46%   |
| Camera                   | 10        | 2.05%   |
| Communication controller | 8         | 1.64%   |
| Card reader              | 5         | 1.03%   |
| Storage                  | 4         | 0.82%   |
| Net/ethernet             | 4         | 0.82%   |
| Unassigned class         | 3         | 0.62%   |
| Modem                    | 3         | 0.62%   |
| Flash memory             | 2         | 0.41%   |
| Network                  | 1         | 0.21%   |
| Firewire controller      | 1         | 0.21%   |

