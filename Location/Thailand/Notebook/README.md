Linux in Thailand - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Thailand.

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

Total: 226

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek   | K40IN                       | [ab6a95da52](https://linux-hardware.org/?probe=ab6a95da52) | Apr 28, 2022 |
| HP        | Pro Tablet 608 G1           | [a8b97ee7cf](https://linux-hardware.org/?probe=a8b97ee7cf) | Apr 25, 2022 |
| Acer      | Aspire A515-45              | [377315649e](https://linux-hardware.org/?probe=377315649e) | Apr 22, 2022 |
| ASUSTek   | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| ASUSTek   | G550JK                      | [6d291b9c9c](https://linux-hardware.org/?probe=6d291b9c9c) | Apr 21, 2022 |
| ASUSTek   | FX503VD                     | [218e8b7d2a](https://linux-hardware.org/?probe=218e8b7d2a) | Apr 20, 2022 |
| Lenovo    | ThinkPad X220 4286A78       | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| Acer      | Aspire E5-471G              | [a7179e1ba3](https://linux-hardware.org/?probe=a7179e1ba3) | Apr 16, 2022 |
| Framework | Laptop                      | [bd5ea938e7](https://linux-hardware.org/?probe=bd5ea938e7) | Apr 07, 2022 |
| Dell      | Latitude 3120               | [c0df9a1ac0](https://linux-hardware.org/?probe=c0df9a1ac0) | Apr 06, 2022 |
| Lenovo    | ThinkBook 15 G3 ACL 21A4    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| Lenovo    | IdeaPad S530-13IWL 81J7     | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Dell      | Latitude 3120               | [69b7d6b1a3](https://linux-hardware.org/?probe=69b7d6b1a3) | Mar 26, 2022 |
| Dell      | Latitude 3120               | [78ae48c482](https://linux-hardware.org/?probe=78ae48c482) | Mar 26, 2022 |
| Acer      | Aspire E5-571               | [c2f6faf193](https://linux-hardware.org/?probe=c2f6faf193) | Mar 06, 2022 |
| HUAWEI    | HLYL-WXX9                   | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| Acer      | AOA150                      | [aeb35f9f12](https://linux-hardware.org/?probe=aeb35f9f12) | Feb 13, 2022 |
| Acer      | AOA150                      | [7d493dd5d5](https://linux-hardware.org/?probe=7d493dd5d5) | Feb 13, 2022 |
| ASUSTek   | Vivobook_ASUSLaptop M350... | [5d3d7c5340](https://linux-hardware.org/?probe=5d3d7c5340) | Feb 12, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X513... | [1488d5e773](https://linux-hardware.org/?probe=1488d5e773) | Feb 09, 2022 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [dfc4821588](https://linux-hardware.org/?probe=dfc4821588) | Feb 08, 2022 |
| Dell      | Vostro 5471                 | [c90234250e](https://linux-hardware.org/?probe=c90234250e) | Jan 31, 2022 |
| Lenovo    | ThinkPad P50 20EQS2AB00     | [bdc680b5f1](https://linux-hardware.org/?probe=bdc680b5f1) | Jan 19, 2022 |
| Lenovo    | ThinkPad X13 Gen 1 20UFS... | [31f48cd25e](https://linux-hardware.org/?probe=31f48cd25e) | Jan 19, 2022 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [cfdad00b0a](https://linux-hardware.org/?probe=cfdad00b0a) | Jan 18, 2022 |
| ASUSTek   | G550JK                      | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| Lenovo    | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo    | ThinkBook 15 G3 ACL 21A4    | [2e71480673](https://linux-hardware.org/?probe=2e71480673) | Dec 24, 2021 |
| Lenovo    | ThinkPad L530 24792T1       | [3e12618615](https://linux-hardware.org/?probe=3e12618615) | Nov 29, 2021 |
| Toshiba   | Satellite L840              | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| ASUSTek   | TUF Gaming FX505DT_FX505... | [0d0596e9ea](https://linux-hardware.org/?probe=0d0596e9ea) | Nov 25, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [039121e888](https://linux-hardware.org/?probe=039121e888) | Nov 23, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [1cd234b66d](https://linux-hardware.org/?probe=1cd234b66d) | Nov 22, 2021 |
| Notebook  | NV4XMB,ME,MZ                | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [fbf00ef864](https://linux-hardware.org/?probe=fbf00ef864) | Nov 15, 2021 |
| Dell      | Vostro 5471                 | [4083699145](https://linux-hardware.org/?probe=4083699145) | Nov 14, 2021 |
| MSI       | Prestige 15 A10SC           | [b362dd3f20](https://linux-hardware.org/?probe=b362dd3f20) | Nov 13, 2021 |
| Dell      | Inspiron N5010              | [d1b6520785](https://linux-hardware.org/?probe=d1b6520785) | Nov 13, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [808a55a867](https://linux-hardware.org/?probe=808a55a867) | Nov 01, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [bee34d8394](https://linux-hardware.org/?probe=bee34d8394) | Oct 29, 2021 |
| HP        | EliteBook 6930p (FL488AW... | [af8e63842a](https://linux-hardware.org/?probe=af8e63842a) | Oct 28, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [4cee09021a](https://linux-hardware.org/?probe=4cee09021a) | Oct 28, 2021 |
| Acer      | Aspire ES1-131              | [de7bee5c36](https://linux-hardware.org/?probe=de7bee5c36) | Oct 20, 2021 |
| HP        | Pavilion Gaming Laptop 1... | [1193264475](https://linux-hardware.org/?probe=1193264475) | Oct 10, 2021 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Apple     | MacBookPro5,5               | [514642d183](https://linux-hardware.org/?probe=514642d183) | Sep 30, 2021 |
| ASUSTek   | ZenBook UX333FN_UX333FN     | [e4fb99f5b8](https://linux-hardware.org/?probe=e4fb99f5b8) | Sep 30, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [8141d6fa89](https://linux-hardware.org/?probe=8141d6fa89) | Sep 22, 2021 |
| ASUSTek   | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| Dell      | Latitude D630               | [3af0cdbc54](https://linux-hardware.org/?probe=3af0cdbc54) | Sep 09, 2021 |
| Acer      | Aspire V3-575G              | [28e06e0c2b](https://linux-hardware.org/?probe=28e06e0c2b) | Aug 28, 2021 |
| Lenovo    | ThinkBook 14-IML 20RV       | [8e060f6c6c](https://linux-hardware.org/?probe=8e060f6c6c) | Aug 23, 2021 |
| Acer      | Aspire E5-471G              | [7f7c5133ad](https://linux-hardware.org/?probe=7f7c5133ad) | Aug 18, 2021 |
| Fujitsu   | LIFEBOOK A357               | [68af6cccad](https://linux-hardware.org/?probe=68af6cccad) | Aug 05, 2021 |
| Acer      | Aspire E5-475G              | [65ad8ece4a](https://linux-hardware.org/?probe=65ad8ece4a) | Jul 30, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [10b4953c7e](https://linux-hardware.org/?probe=10b4953c7e) | Jul 26, 2021 |
| Lenovo    | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| ASUSTek   | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek   | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [9d13b7e8df](https://linux-hardware.org/?probe=9d13b7e8df) | Jul 21, 2021 |
| Acer      | Aspire E5-471G              | [2f1c2df79d](https://linux-hardware.org/?probe=2f1c2df79d) | Jul 21, 2021 |
| Acer      | Aspire E5-471G              | [bde4a22e40](https://linux-hardware.org/?probe=bde4a22e40) | Jul 19, 2021 |
| Acer      | Nitro AN515-55              | [5c7365be9d](https://linux-hardware.org/?probe=5c7365be9d) | Jul 16, 2021 |
| Dell      | Vostro 3578                 | [f5bfb0ada6](https://linux-hardware.org/?probe=f5bfb0ada6) | Jul 09, 2021 |
| Dell      | Vostro 3578                 | [e69ebc683f](https://linux-hardware.org/?probe=e69ebc683f) | Jul 09, 2021 |
| Acer      | Aspire ES1-111M             | [40450f88e3](https://linux-hardware.org/?probe=40450f88e3) | Jul 07, 2021 |
| Acer      | Aspire ES1-111M             | [7eb7b4a001](https://linux-hardware.org/?probe=7eb7b4a001) | Jul 07, 2021 |
| MSI       | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Fujitsu   | LIFEBOOK BH531              | [688d9f583e](https://linux-hardware.org/?probe=688d9f583e) | Jun 16, 2021 |
| HP        | Stream Notebook             | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| Fujitsu   | LIFEBOOK BH531              | [93d4456b05](https://linux-hardware.org/?probe=93d4456b05) | May 29, 2021 |
| ASUSTek   | X450LN                      | [9157df68c1](https://linux-hardware.org/?probe=9157df68c1) | May 27, 2021 |
| Lenovo    | B50-80 80LT                 | [ef615e10ea](https://linux-hardware.org/?probe=ef615e10ea) | May 27, 2021 |
| ASUSTek   | X450LN                      | [aa8e32e484](https://linux-hardware.org/?probe=aa8e32e484) | May 25, 2021 |
| Toshiba   | Satellite L645              | [a3c061e392](https://linux-hardware.org/?probe=a3c061e392) | May 17, 2021 |
| MSI       | GF63 Thin 9SCSR             | [0d99884dcd](https://linux-hardware.org/?probe=0d99884dcd) | May 17, 2021 |
| Dell      | Inspiron 7501               | [e8e3c50f4b](https://linux-hardware.org/?probe=e8e3c50f4b) | May 16, 2021 |
| Acer      | Aspire E5-475G              | [bb2586293c](https://linux-hardware.org/?probe=bb2586293c) | May 09, 2021 |
| Dell      | Latitude 3410               | [b29d7ddfe8](https://linux-hardware.org/?probe=b29d7ddfe8) | May 09, 2021 |
| Dell      | Latitude E6430              | [1a7d88c72a](https://linux-hardware.org/?probe=1a7d88c72a) | May 04, 2021 |
| Dell      | Latitude E6430              | [dd83942c96](https://linux-hardware.org/?probe=dd83942c96) | May 04, 2021 |
| Dell      | Latitude E6430              | [7b00c56952](https://linux-hardware.org/?probe=7b00c56952) | May 02, 2021 |
| Lenovo    | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo    | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Acer      | Aspire ES1-111M             | [aa9bfbf347](https://linux-hardware.org/?probe=aa9bfbf347) | Apr 29, 2021 |
| Acer      | Aspire ES1-111M             | [298d859193](https://linux-hardware.org/?probe=298d859193) | Apr 27, 2021 |
| Dell      | Latitude 3410               | [b6748a9a7e](https://linux-hardware.org/?probe=b6748a9a7e) | Apr 25, 2021 |
| Fujitsu   | LIFEBOOK BH531              | [2fa4c2d1ef](https://linux-hardware.org/?probe=2fa4c2d1ef) | Apr 18, 2021 |
| Dell      | G7 7590                     | [be5780df0a](https://linux-hardware.org/?probe=be5780df0a) | Mar 09, 2021 |
| Samsung   | R780/R778                   | [0c57a7241e](https://linux-hardware.org/?probe=0c57a7241e) | Feb 26, 2021 |
| ASUSTek   | E200HA                      | [1faf0b360f](https://linux-hardware.org/?probe=1faf0b360f) | Feb 19, 2021 |
| ASUSTek   | K45VM                       | [26690f314d](https://linux-hardware.org/?probe=26690f314d) | Feb 15, 2021 |
| ASUSTek   | X555LD                      | [1b2994e7f3](https://linux-hardware.org/?probe=1b2994e7f3) | Feb 15, 2021 |
| HUAWEI    | BOHK-WAX9X                  | [40bcb4aaf2](https://linux-hardware.org/?probe=40bcb4aaf2) | Feb 15, 2021 |
| Apple     | MacBookAir3,2               | [0392f08b03](https://linux-hardware.org/?probe=0392f08b03) | Feb 15, 2021 |
| Acer      | Aspire E5-471G              | [401fa9d58e](https://linux-hardware.org/?probe=401fa9d58e) | Feb 13, 2021 |
| HP        | 1000                        | [16b305a6f5](https://linux-hardware.org/?probe=16b305a6f5) | Feb 13, 2021 |
| HUAWEI    | KLVL-WXX9                   | [20b10721e2](https://linux-hardware.org/?probe=20b10721e2) | Feb 09, 2021 |
| Acer      | Aspire E5-475G              | [360e7155d7](https://linux-hardware.org/?probe=360e7155d7) | Feb 06, 2021 |
| Sony      | SVF14N25CXB                 | [1db1e6aec9](https://linux-hardware.org/?probe=1db1e6aec9) | Jan 28, 2021 |
| ASUSTek   | TUF Gaming FA506IV_FA506... | [731a44edca](https://linux-hardware.org/?probe=731a44edca) | Jan 16, 2021 |
| Lenovo    | IdeaPad Y450                | [1285c5deb9](https://linux-hardware.org/?probe=1285c5deb9) | Jan 11, 2021 |
| Lenovo    | G460 20041                  | [f224060be4](https://linux-hardware.org/?probe=f224060be4) | Jan 07, 2021 |
| ASUSTek   | TUF Gaming FA506II_FA506... | [e28d350fac](https://linux-hardware.org/?probe=e28d350fac) | Dec 24, 2020 |
| ASUSTek   | X450CC                      | [750f666a09](https://linux-hardware.org/?probe=750f666a09) | Dec 23, 2020 |
| Lenovo    | ThinkPad E15 20RES51Y00     | [66b1afc07c](https://linux-hardware.org/?probe=66b1afc07c) | Dec 15, 2020 |
| Dell      | Inspiron 5468               | [abc26c7422](https://linux-hardware.org/?probe=abc26c7422) | Dec 09, 2020 |
| MSI       | PE70 6QE                    | [cb5f05e67d](https://linux-hardware.org/?probe=cb5f05e67d) | Dec 02, 2020 |
| Acer      | Aspire E5-475G              | [53a62697ed](https://linux-hardware.org/?probe=53a62697ed) | Dec 01, 2020 |
| Acer      | Aspire E5-475G              | [719a24bc0f](https://linux-hardware.org/?probe=719a24bc0f) | Nov 30, 2020 |
| MSI       | PE70 6QE                    | [90b21f8369](https://linux-hardware.org/?probe=90b21f8369) | Nov 23, 2020 |
| MSI       | PE70 6QE                    | [7f0423b813](https://linux-hardware.org/?probe=7f0423b813) | Nov 23, 2020 |
| Acer      | Aspire VN7-793G             | [79f11201bc](https://linux-hardware.org/?probe=79f11201bc) | Nov 22, 2020 |
| Dell      | G5 5590                     | [007ad64378](https://linux-hardware.org/?probe=007ad64378) | Nov 20, 2020 |
| MSI       | GE75 Raider 10SGS           | [025deb9bbe](https://linux-hardware.org/?probe=025deb9bbe) | Nov 19, 2020 |
| Dell      | G5 5590                     | [e82ed4c1d0](https://linux-hardware.org/?probe=e82ed4c1d0) | Nov 19, 2020 |
| MSI       | PE70 6QE                    | [725682e6fb](https://linux-hardware.org/?probe=725682e6fb) | Nov 16, 2020 |
| HP        | Laptop 14-bs0xx             | [f90473f671](https://linux-hardware.org/?probe=f90473f671) | Nov 16, 2020 |
| HP        | Laptop 14-bs0xx             | [bf8d99074a](https://linux-hardware.org/?probe=bf8d99074a) | Nov 15, 2020 |
| Lenovo    | IdeaPad 100S-14IBR 80R9     | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Lenovo    | IdeaPad 100S-14IBR 80R9     | [d568aab65e](https://linux-hardware.org/?probe=d568aab65e) | Nov 09, 2020 |
| MSI       | PE70 6QE                    | [0782656308](https://linux-hardware.org/?probe=0782656308) | Nov 06, 2020 |
| MSI       | PE70 6QE                    | [1178f79928](https://linux-hardware.org/?probe=1178f79928) | Nov 03, 2020 |
| Hampoo    | Unknown                     | [b713cd21d1](https://linux-hardware.org/?probe=b713cd21d1) | Oct 24, 2020 |
| Hampoo    | Unknown                     | [03640b9aac](https://linux-hardware.org/?probe=03640b9aac) | Oct 24, 2020 |
| MSI       | PE70 6QE                    | [8c3ccf4956](https://linux-hardware.org/?probe=8c3ccf4956) | Oct 19, 2020 |
| MSI       | PE70 6QE                    | [055f7713d3](https://linux-hardware.org/?probe=055f7713d3) | Oct 19, 2020 |
| Dell      | Precision 7740              | [814a0ec705](https://linux-hardware.org/?probe=814a0ec705) | Oct 15, 2020 |
| MSI       | PE70 6QE                    | [446aaab92d](https://linux-hardware.org/?probe=446aaab92d) | Oct 14, 2020 |
| MSI       | PE70 6QE                    | [1691661a18](https://linux-hardware.org/?probe=1691661a18) | Oct 12, 2020 |
| ASUSTek   | VivoBook_ASUSLaptop X412... | [e0d54e69ff](https://linux-hardware.org/?probe=e0d54e69ff) | Oct 11, 2020 |
| HP        | Pavilion dv7                | [058179daf5](https://linux-hardware.org/?probe=058179daf5) | Sep 24, 2020 |
| HP        | Pavilion dv6                | [acce68d947](https://linux-hardware.org/?probe=acce68d947) | Sep 09, 2020 |
| Dell      | Inspiron 5447               | [9fc26445da](https://linux-hardware.org/?probe=9fc26445da) | Sep 03, 2020 |
| Dell      | Inspiron 5447               | [fd56e29478](https://linux-hardware.org/?probe=fd56e29478) | Sep 03, 2020 |
| Lenovo    | IdeaPad 300-14ISK 80Q6      | [e55f750fc2](https://linux-hardware.org/?probe=e55f750fc2) | Sep 02, 2020 |
| Lenovo    | IdeaPad 300-14ISK 80Q6      | [cc7e35217e](https://linux-hardware.org/?probe=cc7e35217e) | Sep 02, 2020 |
| Acer      | Aspire VN7-792G             | [706847f6cd](https://linux-hardware.org/?probe=706847f6cd) | Aug 30, 2020 |
| Lenovo    | IdeaPad 100S-14IBR 80R9     | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| ASUSTek   | X411UN                      | [212932d80d](https://linux-hardware.org/?probe=212932d80d) | Jul 27, 2020 |
| Lenovo    | IdeaPad 100S-14IBR 80R9     | [c9eb825434](https://linux-hardware.org/?probe=c9eb825434) | Jul 24, 2020 |
| Lenovo    | IdeaPad 100S-14IBR 80R9     | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Acer      | Swift SF314-57G             | [c74653b694](https://linux-hardware.org/?probe=c74653b694) | Jul 15, 2020 |
| Lenovo    | IdeaPad 330-15ARR 81D2      | [f545576ae9](https://linux-hardware.org/?probe=f545576ae9) | Jul 14, 2020 |
| Acer      | Aspire VN7-792G             | [405d399549](https://linux-hardware.org/?probe=405d399549) | Jul 10, 2020 |
| ASUSTek   | VivoBook_ASUSLaptop X570... | [4175ac62a0](https://linux-hardware.org/?probe=4175ac62a0) | Jul 10, 2020 |
| Acer      | Aspire VN7-792G             | [ab45ac9f0d](https://linux-hardware.org/?probe=ab45ac9f0d) | Jul 07, 2020 |
| Acer      | Aspire A315-42              | [7c061a0688](https://linux-hardware.org/?probe=7c061a0688) | Jul 06, 2020 |
| Acer      | Aspire VN7-792G             | [1457f6e3b5](https://linux-hardware.org/?probe=1457f6e3b5) | Jul 04, 2020 |
| Fujitsu   | LIFEBOOK BH531              | [2484e68205](https://linux-hardware.org/?probe=2484e68205) | Jul 03, 2020 |
| ASUSTek   | VivoBook_ASUS Laptop E40... | [adc28756a8](https://linux-hardware.org/?probe=adc28756a8) | Jun 29, 2020 |
| ASUSTek   | VivoBook_ASUS Laptop E40... | [6e947dfc9d](https://linux-hardware.org/?probe=6e947dfc9d) | Jun 27, 2020 |
| ASUSTek   | K42JB                       | [5f87f39c75](https://linux-hardware.org/?probe=5f87f39c75) | Jun 27, 2020 |
| MSI       | MS-14Y1                     | [c585b33393](https://linux-hardware.org/?probe=c585b33393) | Jun 25, 2020 |
| HP        | Pavilion Notebook           | [8d0c93ef24](https://linux-hardware.org/?probe=8d0c93ef24) | Jun 17, 2020 |
| MSI       | MS-14Y1                     | [657c6d539f](https://linux-hardware.org/?probe=657c6d539f) | Jun 03, 2020 |
| Sony      | SVF14N25CXB                 | [2fdd1fc4d3](https://linux-hardware.org/?probe=2fdd1fc4d3) | Jun 02, 2020 |
| ASUSTek   | K53SV                       | [0bb72c8f71](https://linux-hardware.org/?probe=0bb72c8f71) | Jun 01, 2020 |
| ASUSTek   | ROG Zephyrus G14 GA401IV... | [645ef14cb4](https://linux-hardware.org/?probe=645ef14cb4) | May 21, 2020 |
| Lenovo    | IdeaPad S540-14API 81NH     | [4827cdc9b5](https://linux-hardware.org/?probe=4827cdc9b5) | May 21, 2020 |
| Lenovo    | ThinkPad T540p 20BFS0WB0... | [338493712f](https://linux-hardware.org/?probe=338493712f) | May 19, 2020 |
| Lenovo    | ThinkPad T540p 20BFS0WB0... | [17f5a0932c](https://linux-hardware.org/?probe=17f5a0932c) | May 19, 2020 |
| Samsung   | RV418/RV518/RV718           | [ff8f525d6b](https://linux-hardware.org/?probe=ff8f525d6b) | May 18, 2020 |
| Lenovo    | G480 20156                  | [6cb3a28f6a](https://linux-hardware.org/?probe=6cb3a28f6a) | May 18, 2020 |
| Lenovo    | G480 20156                  | [7487bf67c4](https://linux-hardware.org/?probe=7487bf67c4) | May 18, 2020 |
| Acer      | Nitro AN515-42              | [5c659d6268](https://linux-hardware.org/?probe=5c659d6268) | May 07, 2020 |
| Lenovo    | ThinkPad E490 20N9S26G00    | [a26e5790ce](https://linux-hardware.org/?probe=a26e5790ce) | May 06, 2020 |
| ASUSTek   | TUF Gaming FX505DY_FX505... | [f286a38265](https://linux-hardware.org/?probe=f286a38265) | Apr 30, 2020 |
| Lenovo    | Y50-70 20378                | [bbd3e36751](https://linux-hardware.org/?probe=bbd3e36751) | Apr 16, 2020 |
| Lenovo    | Y50-70 20378                | [8bca0c818d](https://linux-hardware.org/?probe=8bca0c818d) | Apr 16, 2020 |
| Lenovo    | ThinkPad T420 4180JH1       | [4d0e9109bb](https://linux-hardware.org/?probe=4d0e9109bb) | Mar 21, 2020 |
| Samsung   | NC208/NC108                 | [d577b178a1](https://linux-hardware.org/?probe=d577b178a1) | Mar 06, 2020 |
| Samsung   | NC208/NC108                 | [cc28243d3d](https://linux-hardware.org/?probe=cc28243d3d) | Mar 06, 2020 |
| Lenovo    | ThinkPad X1 Carbon 6th 2... | [626f7fb341](https://linux-hardware.org/?probe=626f7fb341) | Feb 29, 2020 |
| Acer      | Predator PH315-51           | [b3edf8c190](https://linux-hardware.org/?probe=b3edf8c190) | Feb 23, 2020 |
| Samsung   | NC208/NC108                 | [8d16cc2992](https://linux-hardware.org/?probe=8d16cc2992) | Feb 23, 2020 |
| Samsung   | NC208/NC108                 | [ffbfac004c](https://linux-hardware.org/?probe=ffbfac004c) | Feb 23, 2020 |
| Dell      | Precision 5510              | [0e30ff12b4](https://linux-hardware.org/?probe=0e30ff12b4) | Feb 18, 2020 |
| ASUSTek   | TUF Gaming FX505DY_FX505... | [ac7b752d68](https://linux-hardware.org/?probe=ac7b752d68) | Feb 13, 2020 |
| HP        | Compaq 15                   | [e8597ab3e4](https://linux-hardware.org/?probe=e8597ab3e4) | Feb 06, 2020 |
| MSI       | X460/X460DX                 | [faf3829102](https://linux-hardware.org/?probe=faf3829102) | Feb 04, 2020 |
| Lenovo    | IdeaPad S540-14IML 81NF     | [670b5a0247](https://linux-hardware.org/?probe=670b5a0247) | Dec 27, 2019 |
| Lenovo    | IdeaPad S540-14IML 81NF     | [fc21e1c322](https://linux-hardware.org/?probe=fc21e1c322) | Dec 18, 2019 |
| Lenovo    | ThinkPad P50 20EQS5XE00     | [65dc93e325](https://linux-hardware.org/?probe=65dc93e325) | Dec 18, 2019 |
| HP        | Laptop 14-ck0xxx            | [ff52ea1b93](https://linux-hardware.org/?probe=ff52ea1b93) | Dec 03, 2019 |
| Fujitsu   | LIFEBOOK BH531              | [c00057fc87](https://linux-hardware.org/?probe=c00057fc87) | Dec 01, 2019 |
| Clevo     | M540SR                      | [97181c941c](https://linux-hardware.org/?probe=97181c941c) | Nov 23, 2019 |
| Fujitsu   | LIFEBOOK BH531              | [39e52c6efd](https://linux-hardware.org/?probe=39e52c6efd) | Nov 23, 2019 |
| Fujitsu   | LIFEBOOK BH531              | [2b67125cb0](https://linux-hardware.org/?probe=2b67125cb0) | Nov 22, 2019 |
| Fujitsu   | LIFEBOOK BH531              | [0223eca896](https://linux-hardware.org/?probe=0223eca896) | Nov 22, 2019 |
| Lenovo    | G710 20252                  | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| Lenovo    | G710 20252                  | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| Lenovo    | ThinkPad 11e 5th Gen 20L... | [b65742b189](https://linux-hardware.org/?probe=b65742b189) | Oct 26, 2019 |
| Lenovo    | ThinkPad 11e 5th Gen 20L... | [6ccf378246](https://linux-hardware.org/?probe=6ccf378246) | Oct 26, 2019 |
| Lenovo    | ThinkPad 11e 5th Gen 20L... | [29d4434f82](https://linux-hardware.org/?probe=29d4434f82) | Oct 26, 2019 |
| HP        | Laptop 14-cm0xxx            | [6a706da421](https://linux-hardware.org/?probe=6a706da421) | Oct 23, 2019 |
| Acer      | Swift SF113-31              | [a37935b2e0](https://linux-hardware.org/?probe=a37935b2e0) | Sep 27, 2019 |
| Lenovo    | ThinkPad T540p 20BFS0WB0... | [ccf2eacdd1](https://linux-hardware.org/?probe=ccf2eacdd1) | Sep 14, 2019 |
| Acer      | Aspire E5-552G              | [5c4bd87bc9](https://linux-hardware.org/?probe=5c4bd87bc9) | Sep 04, 2019 |
| Dell      | Vostro 3458                 | [a62197181c](https://linux-hardware.org/?probe=a62197181c) | Sep 04, 2019 |
| Lenovo    | G460 20041                  | [7b5945bfc2](https://linux-hardware.org/?probe=7b5945bfc2) | Aug 31, 2019 |
| HP        | Laptop 15-db0xxx            | [2d5f51cdd8](https://linux-hardware.org/?probe=2d5f51cdd8) | Aug 23, 2019 |
| HP        | Pavilion Gaming Laptop 1... | [fe49019be0](https://linux-hardware.org/?probe=fe49019be0) | Aug 16, 2019 |
| HP        | Pavilion Gaming Laptop 1... | [7551b403e2](https://linux-hardware.org/?probe=7551b403e2) | Aug 16, 2019 |
| HP        | Pavilion Gaming Laptop 1... | [ef69a20f15](https://linux-hardware.org/?probe=ef69a20f15) | Aug 07, 2019 |
| HP        | ENVY Laptop ah0xxx          | [defe18c4c3](https://linux-hardware.org/?probe=defe18c4c3) | Jul 09, 2019 |
| HP        | Pavilion Gaming Laptop 1... | [05bb755a5a](https://linux-hardware.org/?probe=05bb755a5a) | Jun 26, 2019 |
| Dell      | Latitude E6430              | [c8334c6a31](https://linux-hardware.org/?probe=c8334c6a31) | Jun 22, 2019 |
| HP        | Pavilion Gaming Laptop 1... | [26db49d8f2](https://linux-hardware.org/?probe=26db49d8f2) | Jun 19, 2019 |
| Lenovo    | G460 20041                  | [62697bf35b](https://linux-hardware.org/?probe=62697bf35b) | Jun 16, 2019 |
| Acer      | Aspire A315-21              | [6d4aebc3ef](https://linux-hardware.org/?probe=6d4aebc3ef) | May 22, 2019 |
| Acer      | Aspire A315-21              | [f878e784e2](https://linux-hardware.org/?probe=f878e784e2) | May 04, 2019 |
| ASUSTek   | X556UQK                     | [d906d6357c](https://linux-hardware.org/?probe=d906d6357c) | May 02, 2019 |
| ASUSTek   | X556UQK                     | [69302db595](https://linux-hardware.org/?probe=69302db595) | May 02, 2019 |
| ASUSTek   | X556UQK                     | [63a8e04d9e](https://linux-hardware.org/?probe=63a8e04d9e) | May 02, 2019 |
| ASUSTek   | X556UQK                     | [7d55bd0096](https://linux-hardware.org/?probe=7d55bd0096) | May 02, 2019 |
| ASUSTek   | X556UQK                     | [6648050a69](https://linux-hardware.org/?probe=6648050a69) | May 01, 2019 |
| Dell      | Inspiron 14-3467            | [9b390a3c82](https://linux-hardware.org/?probe=9b390a3c82) | Apr 11, 2019 |
| Dell      | Inspiron 14-3467            | [7f1e85018c](https://linux-hardware.org/?probe=7f1e85018c) | Apr 11, 2019 |
| Acer      | Aspire 4750                 | [94d50c8e16](https://linux-hardware.org/?probe=94d50c8e16) | Mar 26, 2019 |
| Apple     | MacBookAir3,2               | [ee6b3b0da4](https://linux-hardware.org/?probe=ee6b3b0da4) | Jan 29, 2019 |
| HP        | Compaq nx6325 (EQ422AV)     | [410fe4b520](https://linux-hardware.org/?probe=410fe4b520) | Dec 21, 2018 |
| HP        | Compaq nx6325 (EQ422AV)     | [1697d0f3f4](https://linux-hardware.org/?probe=1697d0f3f4) | Dec 21, 2018 |
| Acer      | Aspire 4741                 | [0875804f8d](https://linux-hardware.org/?probe=0875804f8d) | Nov 22, 2018 |
| Acer      | Aspire 4741                 | [d2f2af2cb2](https://linux-hardware.org/?probe=d2f2af2cb2) | Nov 13, 2018 |
| Lenovo    | G40-45 80E1                 | [ebf69568bf](https://linux-hardware.org/?probe=ebf69568bf) | Oct 29, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 23        | 15.13%  |
| OpenMandriva 4.2   | 9         | 5.92%   |
| Ubuntu 18.04       | 8         | 5.26%   |
| KDE neon 20.04     | 7         | 4.61%   |
| Debian 11          | 5         | 3.29%   |
| Debian 10          | 5         | 3.29%   |
| Ubuntu 19.10       | 4         | 2.63%   |
| Ubuntu 19.04       | 4         | 2.63%   |
| Ubuntu 16.04       | 4         | 2.63%   |
| Linux Mint 20.2    | 4         | 2.63%   |
| Zorin 15           | 3         | 1.97%   |
| Ubuntu 18.10       | 3         | 1.97%   |
| Linux Mint 19.2    | 3         | 1.97%   |
| Kubuntu 20.04      | 3         | 1.97%   |
| Arch Rolling       | 3         | 1.97%   |
| Arch               | 3         | 1.97%   |
| Zorin 16           | 2         | 1.32%   |
| Xubuntu 20.04      | 2         | 1.32%   |
| Ubuntu MATE 20.10  | 2         | 1.32%   |
| Ubuntu MATE 20.04  | 2         | 1.32%   |
| Ubuntu 22.04       | 2         | 1.32%   |
| Ubuntu 21.10       | 2         | 1.32%   |
| Pop!_OS 21.04      | 2         | 1.32%   |
| Pop!_OS 20.04      | 2         | 1.32%   |
| MX 19              | 2         | 1.32%   |
| Linux Mint 20.3    | 2         | 1.32%   |
| Fedora 33          | 2         | 1.32%   |
| Endless 3.7.7      | 2         | 1.32%   |
| Debian Testing     | 2         | 1.32%   |
| Xubuntu 18.04      | 1         | 0.66%   |
| Ubuntu 20.10       | 1         | 0.66%   |
| ROSA R11           | 1         | 0.66%   |
| Pop!_OS 22.04      | 1         | 0.66%   |
| Pop!_OS 20.10      | 1         | 0.66%   |
| openSUSE Leap-15.3 | 1         | 0.66%   |
| openSUSE 20201221  | 1         | 0.66%   |
| OpenMandriva 4.3   | 1         | 0.66%   |
| MX 18              | 1         | 0.66%   |
| Lubuntu 20.10      | 1         | 0.66%   |
| Linux Mint 20.1    | 1         | 0.66%   |
| Linux Mint 20      | 1         | 0.66%   |
| Linux Mint 19.3    | 1         | 0.66%   |
| Linux Mint 19.1    | 1         | 0.66%   |
| Linux Mint 19      | 1         | 0.66%   |
| Kubuntu 22.04      | 1         | 0.66%   |
| Kali 2020.3        | 1         | 0.66%   |
| Kali 2020.2        | 1         | 0.66%   |
| Fedora 35          | 1         | 0.66%   |
| Fedora 34          | 1         | 0.66%   |
| Fedora 32          | 1         | 0.66%   |
| Fedora 31          | 1         | 0.66%   |
| Endless 3.7.8      | 1         | 0.66%   |
| Endless 3.6.3      | 1         | 0.66%   |
| Endless 3.5.9      | 1         | 0.66%   |
| Endless 3.5.8      | 1         | 0.66%   |
| EndeavourOS        | 1         | 0.66%   |
| Elementary 6       | 1         | 0.66%   |
| Clear Linux 34820  | 1         | 0.66%   |
| Clear Linux 34550  | 1         | 0.66%   |
| Clear Linux 34200  | 1         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 48        | 32.88%  |
| Linux Mint   | 13        | 8.9%    |
| Debian       | 12        | 8.22%   |
| OpenMandriva | 10        | 6.85%   |
| KDE neon     | 7         | 4.79%   |
| Pop!_OS      | 6         | 4.11%   |
| Fedora       | 6         | 4.11%   |
| Endless      | 6         | 4.11%   |
| Arch         | 6         | 4.11%   |
| Zorin        | 5         | 3.42%   |
| Ubuntu MATE  | 4         | 2.74%   |
| Kubuntu      | 4         | 2.74%   |
| Xubuntu      | 3         | 2.05%   |
| MX           | 3         | 2.05%   |
| Clear Linux  | 3         | 2.05%   |
| openSUSE     | 2         | 1.37%   |
| Kali         | 2         | 1.37%   |
| ROSA         | 1         | 0.68%   |
| Lubuntu      | 1         | 0.68%   |
| EndeavourOS  | 1         | 0.68%   |
| Elementary   | 1         | 0.68%   |
| BlackPanther | 1         | 0.68%   |
| ArcoLinux    | 1         | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 9         | 5.52%   |
| 5.8.0-50-generic                | 3         | 1.84%   |
| 5.4.0-42-generic                | 3         | 1.84%   |
| 5.3.0-28-generic                | 3         | 1.84%   |
| 5.11.0-40-generic               | 3         | 1.84%   |
| 5.0.0-27-generic                | 3         | 1.84%   |
| 4.18.0-15-generic               | 3         | 1.84%   |
| 5.8.14-arch1-1                  | 2         | 1.23%   |
| 5.8.0-59-generic                | 2         | 1.23%   |
| 5.8.0-29-generic                | 2         | 1.23%   |
| 5.4.0-81-generic                | 2         | 1.23%   |
| 5.4.0-73-generic                | 2         | 1.23%   |
| 5.4.0-58-generic                | 2         | 1.23%   |
| 5.4.0-40-generic                | 2         | 1.23%   |
| 5.4.0-39-generic                | 2         | 1.23%   |
| 5.4.0-31-generic                | 2         | 1.23%   |
| 5.3.0-20-generic                | 2         | 1.23%   |
| 5.13.0-39-generic               | 2         | 1.23%   |
| 5.12.0-19.3-liquorix-amd64      | 2         | 1.23%   |
| 5.11.0-43-generic               | 2         | 1.23%   |
| 5.11.0-34-generic               | 2         | 1.23%   |
| 5.0.0-32-generic                | 2         | 1.23%   |
| 5.0.0-25-generic                | 2         | 1.23%   |
| 4.19.0-6-amd64                  | 2         | 1.23%   |
| 4.19.0-16-amd64                 | 2         | 1.23%   |
| 4.15.0-70-generic               | 2         | 1.23%   |
| 4.15.0-51-generic               | 2         | 1.23%   |
| 4.15.0-48-generic               | 2         | 1.23%   |
| 5.9.3-1-clear                   | 1         | 0.61%   |
| 5.9.14-1-default                | 1         | 0.61%   |
| 5.9.12-1004.native              | 1         | 0.61%   |
| 5.9.11-1-clear                  | 1         | 0.61%   |
| 5.8.4-200.fc32.x86_64           | 1         | 0.61%   |
| 5.8.0-kali3-amd64               | 1         | 0.61%   |
| 5.8.0-7642-generic              | 1         | 0.61%   |
| 5.8.0-63-generic                | 1         | 0.61%   |
| 5.8.0-44-generic                | 1         | 0.61%   |
| 5.8.0-36-generic                | 1         | 0.61%   |
| 5.8.0-33-generic                | 1         | 0.61%   |
| 5.7.7-arch1-1                   | 1         | 0.61%   |
| 5.6.15-957.native               | 1         | 0.61%   |
| 5.6.14-desktop-2bP              | 1         | 0.61%   |
| 5.6.0-kali1-amd64               | 1         | 0.61%   |
| 5.5.5-200.fc31.x86_64           | 1         | 0.61%   |
| 5.5.4-909.native                | 1         | 0.61%   |
| 5.4.21-1-lts                    | 1         | 0.61%   |
| 5.4.15-nrj-desktop-1rosa-x86_64 | 1         | 0.61%   |
| 5.4.0-89-generic                | 1         | 0.61%   |
| 5.4.0-7634-generic              | 1         | 0.61%   |
| 5.4.0-7626-generic              | 1         | 0.61%   |
| 5.4.0-74-generic                | 1         | 0.61%   |
| 5.4.0-72-generic                | 1         | 0.61%   |
| 5.4.0-59-generic                | 1         | 0.61%   |
| 5.4.0-54-generic                | 1         | 0.61%   |
| 5.4.0-53-generic                | 1         | 0.61%   |
| 5.4.0-52-generic                | 1         | 0.61%   |
| 5.4.0-48-generic                | 1         | 0.61%   |
| 5.4.0-47-generic                | 1         | 0.61%   |
| 5.4.0-45-generic                | 1         | 0.61%   |
| 5.4.0-37-generic                | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 32        | 20%     |
| 5.8.0   | 13        | 8.13%   |
| 4.15.0  | 13        | 8.13%   |
| 5.11.0  | 11        | 6.88%   |
| 5.3.0   | 10        | 6.25%   |
| 5.10.14 | 9         | 5.63%   |
| 5.0.0   | 8         | 5%      |
| 4.19.0  | 7         | 4.38%   |
| 4.18.0  | 7         | 4.38%   |
| 5.13.0  | 6         | 3.75%   |
| 5.10.0  | 3         | 1.88%   |
| 5.8.14  | 2         | 1.25%   |
| 5.16.1  | 2         | 1.25%   |
| 5.16.0  | 2         | 1.25%   |
| 5.15.0  | 2         | 1.25%   |
| 5.12.0  | 2         | 1.25%   |
| 5.9.3   | 1         | 0.63%   |
| 5.9.14  | 1         | 0.63%   |
| 5.9.12  | 1         | 0.63%   |
| 5.9.11  | 1         | 0.63%   |
| 5.8.4   | 1         | 0.63%   |
| 5.7.7   | 1         | 0.63%   |
| 5.6.15  | 1         | 0.63%   |
| 5.6.14  | 1         | 0.63%   |
| 5.6.0   | 1         | 0.63%   |
| 5.5.5   | 1         | 0.63%   |
| 5.5.4   | 1         | 0.63%   |
| 5.4.21  | 1         | 0.63%   |
| 5.4.15  | 1         | 0.63%   |
| 5.3.18  | 1         | 0.63%   |
| 5.17.0  | 1         | 0.63%   |
| 5.16.9  | 1         | 0.63%   |
| 5.16.7  | 1         | 0.63%   |
| 5.16.5  | 1         | 0.63%   |
| 5.16.19 | 1         | 0.63%   |
| 5.16.18 | 1         | 0.63%   |
| 5.15.34 | 1         | 0.63%   |
| 5.15.3  | 1         | 0.63%   |
| 5.14.15 | 1         | 0.63%   |
| 5.14.14 | 1         | 0.63%   |
| 5.13.6  | 1         | 0.63%   |
| 5.13.4  | 1         | 0.63%   |
| 5.12.14 | 1         | 0.63%   |
| 5.12.13 | 1         | 0.63%   |
| 5.10.32 | 1         | 0.63%   |
| 5.10.19 | 1         | 0.63%   |
| 4.18.16 | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 21.66%  |
| 5.8     | 16        | 10.19%  |
| 5.10    | 14        | 8.92%   |
| 4.15    | 13        | 8.28%   |
| 5.3     | 11        | 7.01%   |
| 5.11    | 11        | 7.01%   |
| 5.16    | 8         | 5.1%    |
| 5.13    | 8         | 5.1%    |
| 5.0     | 8         | 5.1%    |
| 4.18    | 8         | 5.1%    |
| 4.19    | 7         | 4.46%   |
| 5.15    | 4         | 2.55%   |
| 5.12    | 4         | 2.55%   |
| 5.9     | 3         | 1.91%   |
| 5.6     | 3         | 1.91%   |
| 5.5     | 2         | 1.27%   |
| 5.7     | 1         | 0.64%   |
| 5.17    | 1         | 0.64%   |
| 5.14    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 140       | 97.9%   |
| i686   | 3         | 2.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 62        | 41.89%  |
| Unknown    | 24        | 16.22%  |
| KDE5       | 23        | 15.54%  |
| X-Cinnamon | 12        | 8.11%   |
| XFCE       | 9         | 6.08%   |
| KDE        | 7         | 4.73%   |
| MATE       | 4         | 2.7%    |
| Budgie     | 2         | 1.35%   |
| Unity      | 1         | 0.68%   |
| Pantheon   | 1         | 0.68%   |
| LXQt       | 1         | 0.68%   |
| Deepin     | 1         | 0.68%   |
| awesome    | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 117       | 80.14%  |
| Wayland | 16        | 10.96%  |
| Unknown | 13        | 8.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 82        | 56.16%  |
| SDDM    | 22        | 15.07%  |
| GDM     | 20        | 13.7%   |
| LightDM | 9         | 6.16%   |
| GDM3    | 7         | 4.79%   |
| TDM     | 6         | 4.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 94        | 64.38%  |
| Unknown | 26        | 17.81%  |
| en_GB   | 7         | 4.79%   |
| th_TH   | 5         | 3.42%   |
| en_SG   | 4         | 2.74%   |
| ru_RU   | 3         | 2.05%   |
| fr_FR   | 2         | 1.37%   |
| de_DE   | 2         | 1.37%   |
| C       | 2         | 1.37%   |
| es_MX   | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 89        | 62.24%  |
| BIOS | 54        | 37.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 123       | 84.83%  |
| Overlay | 11        | 7.59%   |
| Btrfs   | 5         | 3.45%   |
| Unknown | 5         | 3.45%   |
| Zfs     | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 85        | 59.03%  |
| GPT     | 51        | 35.42%  |
| MBR     | 8         | 5.56%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 90.21%  |
| Yes       | 14        | 9.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 65.07%  |
| Yes       | 51        | 34.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 22.38%  |
| ASUSTek Computer    | 29        | 20.28%  |
| Acer                | 22        | 15.38%  |
| Dell                | 18        | 12.59%  |
| Hewlett-Packard     | 16        | 11.19%  |
| MSI                 | 7         | 4.9%    |
| Samsung Electronics | 4         | 2.8%    |
| HUAWEI              | 3         | 2.1%    |
| Apple               | 3         | 2.1%    |
| Toshiba             | 2         | 1.4%    |
| Fujitsu             | 2         | 1.4%    |
| Sony                | 1         | 0.7%    |
| Notebook            | 1         | 0.7%    |
| Hampoo              | 1         | 0.7%    |
| Framework           | 1         | 0.7%    |
| Clevo               | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Samsung NC208/NC108                        | 2         | 1.4%    |
| Lenovo ThinkPad 11e 5th Gen 20LQS00000     | 2         | 1.4%    |
| Lenovo G460 20041                          | 2         | 1.4%    |
| Dell Latitude E6430                        | 2         | 1.4%    |
| Dell Latitude 3120                         | 2         | 1.4%    |
| ASUS X556UQK                               | 2         | 1.4%    |
| ASUS X450LN                                | 2         | 1.4%    |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA    | 2         | 1.4%    |
| Apple MacBookAir3,2                        | 2         | 1.4%    |
| Acer Aspire E5-471G                        | 2         | 1.4%    |
| Acer Aspire A315-21                        | 2         | 1.4%    |
| Toshiba Satellite L840                     | 1         | 0.7%    |
| Toshiba Satellite L645                     | 1         | 0.7%    |
| Sony SVF14N25CXB                           | 1         | 0.7%    |
| Samsung RV418/RV518/RV718                  | 1         | 0.7%    |
| Samsung R780/R778                          | 1         | 0.7%    |
| Notebook NV4XMB,ME,MZ                      | 1         | 0.7%    |
| MSI X460/X460DX                            | 1         | 0.7%    |
| MSI Prestige 15 A10SC                      | 1         | 0.7%    |
| MSI PE70 6QE                               | 1         | 0.7%    |
| MSI MS-14Y1                                | 1         | 0.7%    |
| MSI GF65 Thin 10UE                         | 1         | 0.7%    |
| MSI GF63 Thin 9SCSR                        | 1         | 0.7%    |
| MSI GE75 Raider 10SGS                      | 1         | 0.7%    |
| Lenovo Y50-70 20378                        | 1         | 0.7%    |
| Lenovo ThinkPad X220 4286A78               | 1         | 0.7%    |
| Lenovo ThinkPad X201 Tablet 3093BL3        | 1         | 0.7%    |
| Lenovo ThinkPad X131e 33722VU              | 1         | 0.7%    |
| Lenovo ThinkPad X13 Gen 1 20UFS04J00       | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH | 1         | 0.7%    |
| Lenovo ThinkPad X1 Carbon 6th 20KGS0A400   | 1         | 0.7%    |
| Lenovo ThinkPad T540p 20BFS0WB00           | 1         | 0.7%    |
| Lenovo ThinkPad T480s 20L8S7HF00           | 1         | 0.7%    |
| Lenovo ThinkPad T420 4180JH1               | 1         | 0.7%    |
| Lenovo ThinkPad P50 20EQS5XE00             | 1         | 0.7%    |
| Lenovo ThinkPad P50 20EQS2AB00             | 1         | 0.7%    |
| Lenovo ThinkPad L530 24792T1               | 1         | 0.7%    |
| Lenovo ThinkPad E490 20N9S26G00            | 1         | 0.7%    |
| Lenovo ThinkPad E15 20RES51Y00             | 1         | 0.7%    |
| Lenovo ThinkBook 15 G3 ACL 21A4            | 1         | 0.7%    |
| Lenovo ThinkBook 14-IML 20RV               | 1         | 0.7%    |
| Lenovo IdeaPad Y450                        | 1         | 0.7%    |
| Lenovo IdeaPad S540-14IML 81NF             | 1         | 0.7%    |
| Lenovo IdeaPad S540-14API 81NH             | 1         | 0.7%    |
| Lenovo IdeaPad S530-13IWL 81J7             | 1         | 0.7%    |
| Lenovo IdeaPad 330-15ARR 81D2              | 1         | 0.7%    |
| Lenovo IdeaPad 300-14ISK 80Q6              | 1         | 0.7%    |
| Lenovo IdeaPad 100S-14IBR 80R9             | 1         | 0.7%    |
| Lenovo G710 20252                          | 1         | 0.7%    |
| Lenovo G480 20156                          | 1         | 0.7%    |
| Lenovo G40-45 80E1                         | 1         | 0.7%    |
| Lenovo B50-80 80LT                         | 1         | 0.7%    |
| HUAWEI KLVL-WXX9                           | 1         | 0.7%    |
| HUAWEI HLYL-WXX9                           | 1         | 0.7%    |
| HUAWEI BOHK-WAX9X                          | 1         | 0.7%    |
| HP Stream Notebook                         | 1         | 0.7%    |
| HP Pro Tablet 608 G1                       | 1         | 0.7%    |
| HP Pavilion Notebook                       | 1         | 0.7%    |
| HP Pavilion Gaming Laptop 15-dk1xxx        | 1         | 0.7%    |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 16        | 11.19%  |
| Acer Aspire       | 16        | 11.19%  |
| Lenovo IdeaPad    | 7         | 4.9%    |
| ASUS VivoBook     | 7         | 4.9%    |
| Dell Latitude     | 6         | 4.2%    |
| HP Pavilion       | 5         | 3.5%    |
| Dell Inspiron     | 5         | 3.5%    |
| HP Laptop         | 4         | 2.8%    |
| ASUS TUF          | 4         | 2.8%    |
| Dell Vostro       | 3         | 2.1%    |
| Toshiba Satellite | 2         | 1.4%    |
| Samsung NC208     | 2         | 1.4%    |
| Lenovo ThinkBook  | 2         | 1.4%    |
| Lenovo G460       | 2         | 1.4%    |
| HP Compaq         | 2         | 1.4%    |
| Fujitsu LIFEBOOK  | 2         | 1.4%    |
| Dell Precision    | 2         | 1.4%    |
| ASUS ZenBook      | 2         | 1.4%    |
| ASUS X556UQK      | 2         | 1.4%    |
| ASUS X450LN       | 2         | 1.4%    |
| Apple MacBookAir3 | 2         | 1.4%    |
| Acer Swift        | 2         | 1.4%    |
| Acer Nitro        | 2         | 1.4%    |
| Sony SVF14N25CXB  | 1         | 0.7%    |
| Samsung RV418     | 1         | 0.7%    |
| Samsung R780      | 1         | 0.7%    |
| Notebook NV4XMB   | 1         | 0.7%    |
| MSI X460          | 1         | 0.7%    |
| MSI Prestige      | 1         | 0.7%    |
| MSI PE70          | 1         | 0.7%    |
| MSI MS-14Y1       | 1         | 0.7%    |
| MSI GF65          | 1         | 0.7%    |
| MSI GF63          | 1         | 0.7%    |
| MSI GE75          | 1         | 0.7%    |
| Lenovo Y50-70     | 1         | 0.7%    |
| Lenovo G710       | 1         | 0.7%    |
| Lenovo G480       | 1         | 0.7%    |
| Lenovo G40-45     | 1         | 0.7%    |
| Lenovo B50-80     | 1         | 0.7%    |
| HUAWEI KLVL-WXX9  | 1         | 0.7%    |
| HUAWEI HLYL-WXX9  | 1         | 0.7%    |
| HUAWEI BOHK-WAX9X | 1         | 0.7%    |
| HP Stream         | 1         | 0.7%    |
| HP Pro            | 1         | 0.7%    |
| HP ENVY           | 1         | 0.7%    |
| HP EliteBook      | 1         | 0.7%    |
| HP 1000           | 1         | 0.7%    |
| Framework Laptop  | 1         | 0.7%    |
| Dell G7           | 1         | 0.7%    |
| Dell G5           | 1         | 0.7%    |
| Clevo M540SR      | 1         | 0.7%    |
| ASUS X555LD       | 1         | 0.7%    |
| ASUS X450CC       | 1         | 0.7%    |
| ASUS X411UN       | 1         | 0.7%    |
| ASUS ROG          | 1         | 0.7%    |
| ASUS K53SV        | 1         | 0.7%    |
| ASUS K45VM        | 1         | 0.7%    |
| ASUS K42JB        | 1         | 0.7%    |
| ASUS K40IN        | 1         | 0.7%    |
| ASUS G550JK       | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 18        | 12.59%  |
| 2020 | 17        | 11.89%  |
| 2019 | 15        | 10.49%  |
| 2015 | 12        | 8.39%   |
| 2014 | 12        | 8.39%   |
| 2011 | 12        | 8.39%   |
| 2021 | 10        | 6.99%   |
| 2017 | 9         | 6.29%   |
| 2016 | 9         | 6.29%   |
| 2010 | 9         | 6.29%   |
| 2012 | 8         | 5.59%   |
| 2013 | 3         | 2.1%    |
| 2009 | 3         | 2.1%    |
| 2008 | 3         | 2.1%    |
| 2007 | 2         | 1.4%    |
| 2006 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 143       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 121       | 84.03%  |
| Enabled  | 23        | 15.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 37        | 25.69%  |
| 4.01-8.0    | 34        | 23.61%  |
| 8.01-16.0   | 26        | 18.06%  |
| 16.01-24.0  | 24        | 16.67%  |
| 32.01-64.0  | 11        | 7.64%   |
| 1.01-2.0    | 7         | 4.86%   |
| 24.01-32.0  | 2         | 1.39%   |
| 2.01-3.0    | 1         | 0.69%   |
| 64.01-256.0 | 1         | 0.69%   |
| 0.51-1.0    | 1         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 61        | 40.13%  |
| 2.01-3.0  | 40        | 26.32%  |
| 4.01-8.0  | 23        | 15.13%  |
| 3.01-4.0  | 16        | 10.53%  |
| 8.01-16.0 | 6         | 3.95%   |
| 0.51-1.0  | 5         | 3.29%   |
| 0.01-0.5  | 1         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 66.89%  |
| 2      | 39        | 26.35%  |
| 3      | 7         | 4.73%   |
| 0      | 3         | 2.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 70.63%  |
| Yes       | 42        | 29.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 79.02%  |
| No        | 30        | 20.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 98.6%   |
| No        | 2         | 1.4%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 80.56%  |
| No        | 28        | 19.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Thailand | 143       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Bangkok              | 66        | 42.86%  |
| Chiang Mai           | 15        | 9.74%   |
| Nonthaburi           | 7         | 4.55%   |
| Surat Thani          | 5         | 3.25%   |
| Pattaya              | 4         | 2.6%    |
| Nakhon Pathom        | 4         | 2.6%    |
| Chiang Rai           | 4         | 2.6%    |
| Rayong               | 3         | 1.95%   |
| Phuket               | 3         | 1.95%   |
| Si Sa Ket            | 2         | 1.3%    |
| Nakhon Ratchasima    | 2         | 1.3%    |
| Khlong Luang         | 2         | 1.3%    |
| Chon Buri            | 2         | 1.3%    |
| Ban San Sai          | 2         | 1.3%    |
| Ban Laeng            | 2         | 1.3%    |
| Watthana             | 1         | 0.65%   |
| Uthumphon Phisai     | 1         | 0.65%   |
| Uthai                | 1         | 0.65%   |
| Si Racha             | 1         | 0.65%   |
| Seka                 | 1         | 0.65%   |
| Satun                | 1         | 0.65%   |
| Sanam Chai Khet      | 1         | 0.65%   |
| Samut Sakhon         | 1         | 0.65%   |
| Samut Prakan         | 1         | 0.65%   |
| Sam Khok             | 1         | 0.65%   |
| Sai Mai              | 1         | 0.65%   |
| Ratchathewi          | 1         | 0.65%   |
| Rat Burana           | 1         | 0.65%   |
| Prang Ku             | 1         | 0.65%   |
| Phitsanulok          | 1         | 0.65%   |
| Phetchaburi          | 1         | 0.65%   |
| Phen                 | 1         | 0.65%   |
| Phayao               | 1         | 0.65%   |
| Phayakkhaphum Phisai | 1         | 0.65%   |
| Pak Thong Chai       | 1         | 0.65%   |
| Pak Kret             | 1         | 0.65%   |
| Nong Bua Lamphu      | 1         | 0.65%   |
| Mae Sai              | 1         | 0.65%   |
| Lampang              | 1         | 0.65%   |
| Lam Luk Ka           | 1         | 0.65%   |
| Khon Kaen            | 1         | 0.65%   |
| Kathu                | 1         | 0.65%   |
| Hua Hin              | 1         | 0.65%   |
| Bang Bon             | 1         | 0.65%   |
| Ban Phan Don         | 1         | 0.65%   |
| Ban Ko Bon           | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 44     | 19.78%  |
| Seagate             | 28        | 38     | 15.38%  |
| Samsung Electronics | 25        | 32     | 13.74%  |
| Toshiba             | 15        | 17     | 8.24%   |
| Unknown             | 12        | 15     | 6.59%   |
| Kingston            | 10        | 11     | 5.49%   |
| Intel               | 8         | 8      | 4.4%    |
| Sandisk             | 7         | 9      | 3.85%   |
| SK Hynix            | 6         | 12     | 3.3%    |
| Hitachi             | 5         | 5      | 2.75%   |
| HGST                | 4         | 5      | 2.2%    |
| Micron Technology   | 3         | 3      | 1.65%   |
| Transcend           | 2         | 3      | 1.1%    |
| SPCC                | 2         | 2      | 1.1%    |
| Silicon Motion      | 2         | 3      | 1.1%    |
| KIOXIA              | 2         | 2      | 1.1%    |
| Crucial             | 2         | 2      | 1.1%    |
| Apple               | 2         | 2      | 1.1%    |
| XPG                 | 1         | 1      | 0.55%   |
| PLEXTOR             | 1         | 1      | 0.55%   |
| Pioneer             | 1         | 1      | 0.55%   |
| LITEON              | 1         | 2      | 0.55%   |
| Lite-On             | 1         | 2      | 0.55%   |
| HS-SSD-C100         | 1         | 1      | 0.55%   |
| GAMER               | 1         | 1      | 0.55%   |
| Fujitsu             | 1         | 2      | 0.55%   |
| China               | 1         | 1      | 0.55%   |
| Apacer              | 1         | 1      | 0.55%   |
| A-DATA Technology   | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                | 5         | 2.69%   |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 2.69%   |
| Unknown MMC Card  64GB                | 4         | 2.15%   |
| Unknown MMC Card  32GB                | 4         | 2.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 2.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 1.61%   |
| WDC WD10JPVX-22JC3T0 1TB              | 3         | 1.61%   |
| Toshiba MQ04ABF100 1TB                | 3         | 1.61%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 1.61%   |
| Seagate ST1000LM049-2GH172 1TB        | 3         | 1.61%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 2         | 1.08%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 2         | 1.08%   |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 2         | 1.08%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 2         | 1.08%   |
| WDC WD10SPZX-21Z10T0 1TB              | 2         | 1.08%   |
| WDC PC SN730 SDBPNTY-1T00-1032 1TB    | 2         | 1.08%   |
| Unknown DA4064  64GB                  | 2         | 1.08%   |
| Toshiba KBG30ZMT128G 128GB            | 2         | 1.08%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.08%   |
| SK Hynix HFM512GD3JX013N 512GB        | 2         | 1.08%   |
| Sandisk NVMe SSD Drive 512GB          | 2         | 1.08%   |
| Samsung SSD 970 EVO Plus 500GB        | 2         | 1.08%   |
| KIOXIA KBG40ZNS128G NVMe 128GB        | 2         | 1.08%   |
| Kingston SA400S37240G 240GB SSD       | 2         | 1.08%   |
| Kingston NVMe SSD Drive 512GB         | 2         | 1.08%   |
| Intel NVMe SSD Drive 512GB            | 2         | 1.08%   |
| Intel NVMe SSD Drive 1024GB           | 2         | 1.08%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 1.08%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.08%   |
| Apple SSD TS256C 256GB                | 2         | 1.08%   |
| XPG NVMe SSD Drive 2TB                | 1         | 0.54%   |
| WDC WDS500G1B0A-00H9H0 500GB SSD      | 1         | 0.54%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 0.54%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1         | 0.54%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 0.54%   |
| WDC WD5000LPVX-80V0TT0 500GB          | 1         | 0.54%   |
| WDC WD5000LPLX-08ZNTT0 500GB          | 1         | 0.54%   |
| WDC WD5000LPCX-75VHAT0 500GB          | 1         | 0.54%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 0.54%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 0.54%   |
| WDC WD3200BEVT-75A23T0 320GB          | 1         | 0.54%   |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB              | 1         | 0.54%   |
| WDC WD10JPVX-00JC3T0 1TB              | 1         | 0.54%   |
| WDC WD10JPLX-00MBPT0 1TB              | 1         | 0.54%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 0.54%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB  | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB  | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB    | 1         | 0.54%   |
| Unknown SL128  128GB                  | 1         | 0.54%   |
| Unknown SD64G  64GB                   | 1         | 0.54%   |
| Unknown SD/MMC/MS PRO 128GB           | 1         | 0.54%   |
| Unknown BGND3R  32GB                  | 1         | 0.54%   |
| Transcend TS256GMTS830S 256GB SSD     | 1         | 0.54%   |
| Transcend TS1TMTE220S 1TB             | 1         | 0.54%   |
| Toshiba MQ01ABF032 320GB              | 1         | 0.54%   |
| Toshiba MK6475GSX 640GB               | 1         | 0.54%   |
| Toshiba MK6034GSX 64GB                | 1         | 0.54%   |
| Toshiba MK1637GSX 160GB               | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 38     | 38.89%  |
| WDC                 | 19        | 20     | 26.39%  |
| Toshiba             | 12        | 14     | 16.67%  |
| Hitachi             | 5         | 5      | 6.94%   |
| HGST                | 4         | 5      | 5.56%   |
| Samsung Electronics | 2         | 3      | 2.78%   |
| Unknown             | 1         | 1      | 1.39%   |
| Fujitsu             | 1         | 2      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 18     | 23.53%  |
| Samsung Electronics | 12        | 17     | 23.53%  |
| Kingston            | 6         | 6      | 11.76%  |
| SanDisk             | 3         | 5      | 5.88%   |
| SPCC                | 2         | 2      | 3.92%   |
| SK Hynix            | 2         | 2      | 3.92%   |
| Micron Technology   | 2         | 2      | 3.92%   |
| Intel               | 2         | 2      | 3.92%   |
| Crucial             | 2         | 2      | 3.92%   |
| Apple               | 2         | 2      | 3.92%   |
| Transcend           | 1         | 2      | 1.96%   |
| PLEXTOR             | 1         | 1      | 1.96%   |
| Pioneer             | 1         | 1      | 1.96%   |
| LITEON              | 1         | 2      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| Apacer              | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 70        | 88     | 39.33%  |
| SSD     | 49        | 66     | 27.53%  |
| NVMe    | 46        | 57     | 25.84%  |
| MMC     | 11        | 14     | 6.18%   |
| Unknown | 2         | 2      | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 152    | 62.96%  |
| NVMe | 46        | 57     | 28.4%   |
| MMC  | 11        | 14     | 6.79%   |
| SAS  | 3         | 4      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 94     | 57.89%  |
| 0.51-1.0   | 47        | 59     | 41.23%  |
| 1.01-2.0   | 1         | 1      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 37        | 24.83%  |
| 101-250    | 37        | 24.83%  |
| 501-1000   | 26        | 17.45%  |
| 51-100     | 13        | 8.72%   |
| 21-50      | 12        | 8.05%   |
| 1001-2000  | 12        | 8.05%   |
| 1-20       | 9         | 6.04%   |
| Unknown    | 2         | 1.34%   |
| 2001-3000  | 1         | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 66        | 42.58%  |
| 21-50     | 28        | 18.06%  |
| 101-250   | 21        | 13.55%  |
| 251-500   | 15        | 9.68%   |
| 51-100    | 14        | 9.03%   |
| 501-1000  | 7         | 4.52%   |
| 1001-2000 | 2         | 1.29%   |
| Unknown   | 2         | 1.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST1000LM049-2GH172 1TB    | 2         | 2      | 20%     |
| Seagate ST1000LM035-1RK172 1TB    | 2         | 2      | 20%     |
| Toshiba MQ01ABD100 1TB            | 1         | 1      | 10%     |
| Seagate ST500LM000-SSHD-8GB       | 1         | 1      | 10%     |
| SanDisk SDSSDX240GG25 240GB       | 1         | 1      | 10%     |
| Samsung Electronics HM160HI 160GB | 1         | 2      | 10%     |
| Intel SSDSC2KF256H6 SATA 256GB    | 1         | 1      | 10%     |
| HGST HTS721010A9E630 1TB          | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 50%     |
| Toshiba             | 1         | 1      | 10%     |
| SanDisk             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 2      | 10%     |
| Intel               | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 62.5%   |
| Toshiba             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 2      | 12.5%   |
| HGST                | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 80%     |
| SSD  | 2         | 2      | 20%     |

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
| Detected | 89        | 149    | 60.54%  |
| Works    | 48        | 67     | 32.65%  |
| Malfunc  | 10        | 11     | 6.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 95        | 57.23%  |
| AMD                          | 21        | 12.65%  |
| Samsung Electronics          | 15        | 9.04%   |
| Sandisk                      | 10        | 6.02%   |
| SK Hynix                     | 4         | 2.41%   |
| Nvidia                       | 4         | 2.41%   |
| Kingston Technology Company  | 4         | 2.41%   |
| Toshiba America Info Systems | 3         | 1.81%   |
| Silicon Motion               | 3         | 1.81%   |
| KIOXIA                       | 2         | 1.2%    |
| ADATA Technology             | 2         | 1.2%    |
| VIA Technologies             | 1         | 0.6%    |
| Micron Technology            | 1         | 0.6%    |
| Lite-On Technology           | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 20        | 11.36%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 12        | 6.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 11        | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 5.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 7         | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 3.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 3.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 6         | 3.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 5         | 2.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 2.27%   |
| Intel SSD 660P Series                                                                  | 4         | 2.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 4         | 2.27%   |
| SK Hynix Gold P31 SSD                                                                  | 3         | 1.7%    |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 3         | 1.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 3         | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 3         | 1.7%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.7%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.7%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                          | 2         | 1.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 1.14%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 2         | 1.14%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 1.14%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 1.14%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 2         | 1.14%   |
| Intel SSD 600P Series                                                                  | 2         | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 2         | 1.14%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 2         | 1.14%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 1.14%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.57%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.57%   |
| SK Hynix Non-Volatile memory controller                                                | 1         | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.57%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.57%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.57%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.57%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 1         | 0.57%   |
| Micron Non-Volatile memory controller                                                  | 1         | 0.57%   |
| Lite-On Non-Volatile memory controller                                                 | 1         | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 1         | 0.57%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.57%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.57%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.57%   |
| AMD IXP SB4x0 Serial ATA Controller                                                    | 1         | 0.57%   |
| AMD IXP SB4x0 IDE Controller                                                           | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 106       | 62.72%  |
| NVMe | 49        | 28.99%  |
| RAID | 7         | 4.14%   |
| IDE  | 7         | 4.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 80.42%  |
| AMD    | 28        | 19.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 2.8%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 2.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.1%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.1%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 2.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.1%    |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 3         | 2.1%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 1.4%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 1.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.4%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 1.4%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.4%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.4%    |
| Intel Core i5 CPU M 450 @ 2.40GHz             | 2         | 1.4%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.4%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.4%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.4%    |
| Intel Core 2 Duo CPU L9600 @ 2.13GHz          | 2         | 1.4%    |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 1.4%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.4%    |
| Intel Atom CPU N570 @ 1.66GHz                 | 2         | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.4%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.4%    |
| AMD A4-9120 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.4%    |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.7%    |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.7%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.7%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.7%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.7%    |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 1         | 0.7%    |
| Intel Core i9-10980HK CPU @ 2.40GHz           | 1         | 0.7%    |
| Intel Core i7-9850H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.7%    |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.7%    |
| Intel Core i7-3540M CPU @ 3.00GHz             | 1         | 0.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.7%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 1         | 0.7%    |
| Intel Core i7 CPU L 640 @ 2.13GHz             | 1         | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.7%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.7%    |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 34        | 23.78%  |
| Intel Core i5           | 31        | 21.68%  |
| Intel Core i3           | 13        | 9.09%   |
| AMD Ryzen 5             | 10        | 6.99%   |
| Intel Core 2 Duo        | 9         | 6.29%   |
| Intel Pentium           | 6         | 4.2%    |
| Intel Celeron           | 6         | 4.2%    |
| Other                   | 5         | 3.5%    |
| Intel Atom              | 5         | 3.5%    |
| AMD Ryzen 7             | 5         | 3.5%    |
| AMD Ryzen 3             | 3         | 2.1%    |
| Intel Pentium Silver    | 2         | 1.4%    |
| AMD Ryzen 9             | 2         | 1.4%    |
| AMD A4                  | 2         | 1.4%    |
| Intel Xeon              | 1         | 0.7%    |
| Intel Pentium Dual      | 1         | 0.7%    |
| Intel Core m3           | 1         | 0.7%    |
| Intel Core i9           | 1         | 0.7%    |
| AMD Turion 64 X2 Mobile | 1         | 0.7%    |
| AMD Ryzen 7 PRO         | 1         | 0.7%    |
| AMD E2                  | 1         | 0.7%    |
| AMD E1                  | 1         | 0.7%    |
| AMD A8                  | 1         | 0.7%    |
| AMD A10                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 69        | 48.25%  |
| 4      | 54        | 37.76%  |
| 6      | 11        | 7.69%   |
| 8      | 8         | 5.59%   |
| 1      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 143       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 111       | 77.08%  |
| 1      | 33        | 22.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 96.5%   |
| Unknown        | 4         | 2.8%    |
| 32-bit         | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 18.24%  |
| 0x206a7    | 10        | 6.76%   |
| 0x806ec    | 6         | 4.05%   |
| 0x806e9    | 6         | 4.05%   |
| 0x40651    | 6         | 4.05%   |
| 0x306a9    | 6         | 4.05%   |
| 0x1067a    | 5         | 3.38%   |
| 0x906ea    | 4         | 2.7%    |
| 0x806ea    | 4         | 2.7%    |
| 0x806c1    | 4         | 2.7%    |
| 0x406e3    | 4         | 2.7%    |
| 0x20655    | 4         | 2.7%    |
| 0x20652    | 4         | 2.7%    |
| 0x08108102 | 4         | 2.7%    |
| 0xa0652    | 3         | 2.03%   |
| 0x706a1    | 3         | 2.03%   |
| 0x506e3    | 3         | 2.03%   |
| 0x406c4    | 3         | 2.03%   |
| 0x406c3    | 3         | 2.03%   |
| 0x306c3    | 3         | 2.03%   |
| 0x08600104 | 3         | 2.03%   |
| 0x0810100b | 3         | 2.03%   |
| 0x906e9    | 2         | 1.35%   |
| 0x906c0    | 2         | 1.35%   |
| 0x706a8    | 2         | 1.35%   |
| 0x6fd      | 2         | 1.35%   |
| 0x106ca    | 2         | 1.35%   |
| 0x0a50000c | 2         | 1.35%   |
| 0x08101007 | 2         | 1.35%   |
| 0x06006704 | 2         | 1.35%   |
| 0xa0660    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x506c9    | 1         | 0.68%   |
| 0x306d4    | 1         | 0.68%   |
| 0x106c2    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x08608103 | 1         | 0.68%   |
| 0x08608102 | 1         | 0.68%   |
| 0x08600106 | 1         | 0.68%   |
| 0x08600102 | 1         | 0.68%   |
| 0x08108109 | 1         | 0.68%   |
| 0x0700010f | 1         | 0.68%   |
| 0x0600610b | 1         | 0.68%   |
| 0x05000119 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 18.88%  |
| Haswell       | 13        | 9.09%   |
| Skylake       | 10        | 6.99%   |
| SandyBridge   | 10        | 6.99%   |
| Westmere      | 8         | 5.59%   |
| Penryn        | 8         | 5.59%   |
| Silvermont    | 7         | 4.9%    |
| Zen+          | 6         | 4.2%    |
| Zen 2         | 6         | 4.2%    |
| IvyBridge     | 6         | 4.2%    |
| CometLake     | 6         | 4.2%    |
| Zen           | 5         | 3.5%    |
| TigerLake     | 5         | 3.5%    |
| Goldmont plus | 5         | 3.5%    |
| Excavator     | 3         | 2.1%    |
| Bonnell       | 3         | 2.1%    |
| Zen 3         | 2         | 1.4%    |
| Tremont       | 2         | 1.4%    |
| Core          | 2         | 1.4%    |
| Unknown       | 2         | 1.4%    |
| Puma          | 1         | 0.7%    |
| K8 Hammer     | 1         | 0.7%    |
| Jaguar        | 1         | 0.7%    |
| IceLake       | 1         | 0.7%    |
| Goldmont      | 1         | 0.7%    |
| Broadwell     | 1         | 0.7%    |
| Bobcat        | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 99        | 48.06%  |
| Nvidia           | 65        | 31.55%  |
| AMD              | 40        | 19.42%  |
| VIA Technologies | 1         | 0.49%   |
| ATI Technologies | 1         | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.17%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.78%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.78%   |
| AMD Renoir                                                                               | 6         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 2.31%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 2.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.31%   |
| Intel HD Graphics 620                                                                    | 5         | 2.31%   |
| Intel HD Graphics 530                                                                    | 5         | 2.31%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 2.31%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 2.31%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 2.31%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.85%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.39%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.39%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.39%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.39%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 3         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 2         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.93%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.93%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.93%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.93%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.93%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.93%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.93%   |
| Intel HD Graphics 630                                                                    | 2         | 0.93%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.93%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.93%   |
| AMD Lucienne                                                                             | 2         | 0.93%   |
| AMD Cezanne                                                                              | 2         | 0.93%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.93%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 1         | 0.46%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.46%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.46%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 0.46%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.46%   |
| Nvidia GT216M [GeForce GT 240M]                                                          | 1         | 0.46%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.46%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.46%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.46%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.46%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.46%   |
| Nvidia GK208M [GeForce GT 730M]                                                          | 1         | 0.46%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.46%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.46%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 47        | 32.87%  |
| 1 x Intel          | 42        | 29.37%  |
| 1 x AMD            | 21        | 14.69%  |
| 1 x Nvidia         | 10        | 6.99%   |
| Intel + AMD        | 8         | 5.59%   |
| 2 x AMD            | 6         | 4.2%    |
| AMD + Nvidia       | 6         | 4.2%    |
| Intel + 2 x Nvidia | 2         | 1.4%    |
| 1 x VIA            | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 115       | 78.77%  |
| Proprietary | 29        | 19.86%  |
| Unknown     | 2         | 1.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 45.27%  |
| 1.01-2.0   | 27        | 18.24%  |
| 0.01-0.5   | 21        | 14.19%  |
| 3.01-4.0   | 19        | 12.84%  |
| 0.51-1.0   | 11        | 7.43%   |
| 5.01-6.0   | 3         | 2.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 23.64%  |
| Chimei Innolux          | 25        | 15.15%  |
| LG Display              | 20        | 12.12%  |
| Samsung Electronics     | 19        | 11.52%  |
| BOE                     | 18        | 10.91%  |
| PANDA                   | 7         | 4.24%   |
| Goldstar                | 6         | 3.64%   |
| Dell                    | 6         | 3.64%   |
| Sharp                   | 3         | 1.82%   |
| Lenovo                  | 3         | 1.82%   |
| Chi Mei Optoelectronics | 3         | 1.82%   |
| Apple                   | 3         | 1.82%   |
| Acer                    | 2         | 1.21%   |
| TCL                     | 1         | 0.61%   |
| Quanta Display          | 1         | 0.61%   |
| Panasonic               | 1         | 0.61%   |
| NEC Computers           | 1         | 0.61%   |
| LPL                     | 1         | 0.61%   |
| Lenovo Group Limited    | 1         | 0.61%   |
| InfoVision              | 1         | 0.61%   |
| Hewlett-Packard         | 1         | 0.61%   |
| CSO                     | 1         | 0.61%   |
| CPT                     | 1         | 0.61%   |
| BenQ                    | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 1.21%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 1.21%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 1.21%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 1.21%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 1.21%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 2         | 1.21%   |
| BOE LCD Monitor BOE09C3 1366x768 256x144mm 11.6-inch                  | 2         | 1.21%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                  | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO363C 1366x768 309x173mm 13.9-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO353D 1920x1080 309x174mm 14.0-inch        | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.21%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 1.21%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 1.21%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.61%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP14A1 3840x2160 344x194mm 15.5-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.61%   |
| Samsung Electronics SyncMaster SAM0366 1280x1024 338x270mm 17.0-inch  | 1         | 0.61%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.61%   |
| Samsung Electronics S20D300 SAM0B3A 1600x900 432x240mm 19.5-inch      | 1         | 0.61%   |
| Samsung Electronics S19C170 SAM0B01 1366x768 410x230mm 18.5-inch      | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5042 1440x900 303x190mm 14.1-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1         | 0.61%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch    | 1         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.61%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch       | 1         | 0.61%   |
| PANDA LM133LF5L01 NCP0020 1920x1080 294x165mm 13.3-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP0058 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| PANDA LC133LF4L02 NCP0017 1920x1080 294x165mm 13.3-inch               | 1         | 0.61%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                    | 1         | 0.61%   |
| NEC Computers LCD73VXM NEC6735 1280x1024 338x270mm 17.0-inch          | 1         | 0.61%   |
| LPL LCD Monitor 1440x900                                              | 1         | 0.61%   |
| LG Display LP156WH2-TLQ1 LGD021B 1366x768 344x194mm 15.5-inch         | 1         | 0.61%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD061E 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0597 1920x1080 294x165mm 13.3-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0527 1366x768 309x174mm 14.0-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 63        | 40.13%  |
| 1366x768 (WXGA)   | 61        | 38.85%  |
| 3840x2160 (4K)    | 8         | 5.1%    |
| 1600x900 (HD+)    | 5         | 3.18%   |
| 1440x900 (WXGA+)  | 5         | 3.18%   |
| 2560x1440 (QHD)   | 3         | 1.91%   |
| 1280x800 (WXGA)   | 3         | 1.91%   |
| 1280x1024 (SXGA)  | 2         | 1.27%   |
| 2256x1504         | 1         | 0.64%   |
| 2160x1440         | 1         | 0.64%   |
| 1920x515          | 1         | 0.64%   |
| 1920x1200 (WUXGA) | 1         | 0.64%   |
| 1360x768          | 1         | 0.64%   |
| 1024x768 (XGA)    | 1         | 0.64%   |
| 1024x600          | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 51        | 30.91%  |
| 14      | 33        | 20%     |
| 13      | 27        | 16.36%  |
| 11      | 11        | 6.67%   |
| 17      | 10        | 6.06%   |
| 27      | 4         | 2.42%   |
| 24      | 4         | 2.42%   |
| 23      | 4         | 2.42%   |
| 18      | 3         | 1.82%   |
| Unknown | 3         | 1.82%   |
| 31      | 2         | 1.21%   |
| 21      | 2         | 1.21%   |
| 19      | 2         | 1.21%   |
| 12      | 2         | 1.21%   |
| 10      | 2         | 1.21%   |
| 84      | 1         | 0.61%   |
| 54      | 1         | 0.61%   |
| 40      | 1         | 0.61%   |
| 16      | 1         | 0.61%   |
| 8       | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 60.74%  |
| 201-300     | 27        | 16.56%  |
| 501-600     | 12        | 7.36%   |
| 351-400     | 9         | 5.52%   |
| 401-500     | 7         | 4.29%   |
| Unknown     | 3         | 1.84%   |
| 601-700     | 2         | 1.23%   |
| 801-900     | 1         | 0.61%   |
| 1501-2000   | 1         | 0.61%   |
| 101-200     | 1         | 0.61%   |
| 1001-1500   | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 125       | 87.41%  |
| 16/10   | 9         | 6.29%   |
| 3/2     | 3         | 2.1%    |
| 5/4     | 2         | 1.4%    |
| Unknown | 2         | 1.4%    |
| 4/3     | 1         | 0.7%    |
| 3.73    | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 52        | 31.52%  |
| 101-110        | 51        | 30.91%  |
| 51-60          | 11        | 6.67%   |
| 201-250        | 10        | 6.06%   |
| 71-80          | 8         | 4.85%   |
| 121-130        | 7         | 4.24%   |
| 141-150        | 5         | 3.03%   |
| 301-350        | 4         | 2.42%   |
| Unknown        | 3         | 1.82%   |
| More than 1000 | 2         | 1.21%   |
| 61-70          | 2         | 1.21%   |
| 351-500        | 2         | 1.21%   |
| 41-50          | 2         | 1.21%   |
| 151-200        | 2         | 1.21%   |
| 1-40           | 1         | 0.61%   |
| 131-140        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |
| 91-100         | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 42.59%  |
| 101-120       | 50        | 30.86%  |
| 51-100        | 25        | 15.43%  |
| 161-240       | 13        | 8.02%   |
| Unknown       | 3         | 1.85%   |
| More than 240 | 2         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 115       | 79.86%  |
| 2     | 26        | 18.06%  |
| 0     | 2         | 1.39%   |
| 3     | 1         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 91        | 37.14%  |
| Intel                             | 69        | 28.16%  |
| Qualcomm Atheros                  | 42        | 17.14%  |
| Broadcom                          | 18        | 7.35%   |
| MEDIATEK                          | 3         | 1.22%   |
| ASIX Electronics                  | 3         | 1.22%   |
| Ralink Technology                 | 2         | 0.82%   |
| Ralink                            | 2         | 0.82%   |
| Ericsson Business Mobile Networks | 2         | 0.82%   |
| Broadcom Limited                  | 2         | 0.82%   |
| VIA Technologies                  | 1         | 0.41%   |
| TP-Link                           | 1         | 0.41%   |
| Samsung Electronics               | 1         | 0.41%   |
| Nvidia                            | 1         | 0.41%   |
| Marvell Technology Group          | 1         | 0.41%   |
| Lenovo                            | 1         | 0.41%   |
| JMicron Technology                | 1         | 0.41%   |
| Huawei Technologies               | 1         | 0.41%   |
| D-Link System                     | 1         | 0.41%   |
| D-Link                            | 1         | 0.41%   |
| ASUSTek Computer                  | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 68        | 25.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 3.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 10        | 3.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 8         | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 7         | 2.58%   |
| Intel Wi-Fi 6 AX200                                                            | 7         | 2.58%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 6         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 5         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 5         | 1.85%   |
| Intel Wireless 7265                                                            | 5         | 1.85%   |
| Intel Wireless 3160                                                            | 5         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 5         | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 5         | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 1.48%   |
| Intel Wireless-AC 9260                                                         | 4         | 1.48%   |
| Intel Wireless 8265 / 8275                                                     | 4         | 1.48%   |
| Intel Wireless 8260                                                            | 4         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 4         | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4         | 1.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 1.48%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 4         | 1.48%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 3         | 1.11%   |
| Intel Wireless 3165                                                            | 3         | 1.11%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 3         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.74%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.74%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 2         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.74%   |
| Intel Centrino Ultimate-N 6300                                                 | 2         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 0.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 2         | 0.74%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 2         | 0.74%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.37%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                     | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.37%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                             | 1         | 0.37%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.37%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.37%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.37%   |
| Ralink RT5572 Wireless Adapter                                                 | 1         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.37%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                    | 1         | 0.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.37%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.37%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.37%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 68        | 44.74%  |
| Qualcomm Atheros      | 36        | 23.68%  |
| Realtek Semiconductor | 19        | 12.5%   |
| Broadcom              | 16        | 10.53%  |
| MEDIATEK              | 3         | 1.97%   |
| Ralink Technology     | 2         | 1.32%   |
| Ralink                | 2         | 1.32%   |
| Broadcom Limited      | 2         | 1.32%   |
| TP-Link               | 1         | 0.66%   |
| D-Link System         | 1         | 0.66%   |
| D-Link                | 1         | 0.66%   |
| ASUSTek Computer      | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 6.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.61%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 4.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 3.29%   |
| Intel Wireless 7265                                                     | 5         | 3.29%   |
| Intel Wireless 3160                                                     | 5         | 3.29%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 3.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.63%   |
| Intel Wireless-AC 9260                                                  | 4         | 2.63%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.63%   |
| Intel Wireless 8260                                                     | 4         | 2.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.63%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.97%   |
| Intel Wireless 3165                                                     | 3         | 1.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.32%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.32%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.32%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.66%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 0.66%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.66%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.66%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.66%   |
| Ralink RT5392 PCIe Wireless Network Adapter                             | 1         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.66%   |
| Intel Wireless 7260                                                     | 1         | 0.66%   |
| Intel WiFi Link 5100                                                    | 1         | 0.66%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.66%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.66%   |
| D-Link System DWA-110 Wireless G Adapter(rev.A1) [Ralink RT2571W]       | 1         | 0.66%   |
| D-Link DWA-171                                                          | 1         | 0.66%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                                 | 1         | 0.66%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 1         | 0.66%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.66%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.66%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 1         | 0.66%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]               | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 81        | 69.83%  |
| Intel                    | 12        | 10.34%  |
| Qualcomm Atheros         | 8         | 6.9%    |
| Broadcom                 | 5         | 4.31%   |
| ASIX Electronics         | 3         | 2.59%   |
| VIA Technologies         | 1         | 0.86%   |
| Samsung Electronics      | 1         | 0.86%   |
| Nvidia                   | 1         | 0.86%   |
| Marvell Technology Group | 1         | 0.86%   |
| Lenovo                   | 1         | 0.86%   |
| JMicron Technology       | 1         | 0.86%   |
| Huawei Technologies      | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 68        | 58.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 8.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 3.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.85%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.85%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.85%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.85%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.85%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.85%   |
| Huawei E353/E3131                                                              | 1         | 0.85%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                                    | 1         | 0.85%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.85%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.85%   |
| ASIX AX88772B Fast Ethernet Controller                                         | 1         | 0.85%   |
| ASIX AX88772A Fast Ethernet                                                    | 1         | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 55.08%  |
| Ethernet | 113       | 44.14%  |
| Modem    | 2         | 0.78%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 66.15%  |
| Ethernet | 65        | 33.33%  |
| Modem    | 1         | 0.51%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 106       | 74.13%  |
| 1     | 37        | 25.87%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 86.11%  |
| Yes  | 20        | 13.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 44.07%  |
| Lite-On Technology              | 13        | 11.02%  |
| IMC Networks                    | 13        | 11.02%  |
| Qualcomm Atheros Communications | 8         | 6.78%   |
| Broadcom                        | 6         | 5.08%   |
| Realtek Semiconductor           | 5         | 4.24%   |
| Foxconn / Hon Hai               | 4         | 3.39%   |
| Dell                            | 3         | 2.54%   |
| Apple                           | 3         | 2.54%   |
| Toshiba                         | 2         | 1.69%   |
| Realtek                         | 2         | 1.69%   |
| Hewlett-Packard                 | 2         | 1.69%   |
| Ralink                          | 1         | 0.85%   |
| Foxconn International           | 1         | 0.85%   |
| Cambridge Silicon Radio         | 1         | 0.85%   |
| ASUSTek Computer                | 1         | 0.85%   |
| Askey Computer                  | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 17.8%   |
| Intel AX201 Bluetooth                               | 11        | 9.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 6.78%   |
| Intel AX200 Bluetooth                               | 6         | 5.08%   |
| IMC Networks Bluetooth Device                       | 6         | 5.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 3.39%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.54%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 2.54%   |
| Lite-On Bluetooth Device                            | 3         | 2.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 2.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 2.54%   |
| Realtek Bluetooth Radio                             | 2         | 1.69%   |
| Realtek Bluetooth Radio                             | 2         | 1.69%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.69%   |
| Lite-On Bluetooth Radio                             | 2         | 1.69%   |
| Intel AX210 Bluetooth                               | 2         | 1.69%   |
| IMC Networks Wireless_Device                        | 2         | 1.69%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.69%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.85%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.85%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.85%   |
| Lite-On Wireless_Device                             | 1         | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.85%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.85%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.85%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.85%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.85%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.85%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.85%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.85%   |
| Broadcom Bluetooth 2.1 Device                       | 1         | 0.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.85%   |
| Broadcom BCM20702A0                                 | 1         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.85%   |
| Broadcom BCM2046 Bluetooth Device                   | 1         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.85%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.85%   |
| Askey Bluetooth Device                              | 1         | 0.85%   |
| Apple Bluetooth Host Controller                     | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 108       | 58.7%   |
| AMD                 | 34        | 18.48%  |
| Nvidia              | 33        | 17.93%  |
| Samson Technologies | 2         | 1.09%   |
| JMTek               | 2         | 1.09%   |
| VIA Technologies    | 1         | 0.54%   |
| Samsung Electronics | 1         | 0.54%   |
| Razer USA           | 1         | 0.54%   |
| Lenovo              | 1         | 0.54%   |
| Dell                | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 9.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 7.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 4.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 4.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.02%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.02%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 2.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 1.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.79%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.34%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.34%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.34%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.34%   |
| Samson Technologies GoMic compact condenser mic                                                   | 2         | 0.89%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.89%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.89%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.89%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.89%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.89%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.89%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.45%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 0.45%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.45%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.45%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Nvidia Audio device                                                                               | 1         | 0.45%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.45%   |
| JMTek USB PnP Audio Device(EEPROM)                                                                | 1         | 0.45%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.45%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.45%   |
| Dell AC511 USB SoundBar                                                                           | 1         | 0.45%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.45%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 30.59%  |
| SK Hynix            | 18        | 21.18%  |
| Kingston            | 13        | 15.29%  |
| Micron Technology   | 9         | 10.59%  |
| Unknown             | 4         | 4.71%   |
| Elpida              | 3         | 3.53%   |
| Crucial             | 3         | 3.53%   |
| Transcend           | 2         | 2.35%   |
| Unknown (08B5)      | 1         | 1.18%   |
| Ramaxel Technology  | 1         | 1.18%   |
| Nanya Technology    | 1         | 1.18%   |
| Lexar               | 1         | 1.18%   |
| G.Skill             | 1         | 1.18%   |
| ASint Technology    | 1         | 1.18%   |
| A-DATA Technology   | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s       | 3         | 3.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 3         | 3.37%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 2         | 2.25%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 2.25%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 2         | 2.25%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 2         | 2.25%   |
| SK Hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 2         | 2.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 2.25%   |
| Micron RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 2         | 2.25%   |
| Crucial RAM CT16G4SFD824A.C16FBR 16GB SODIMM DDR4 2400MT/s     | 2         | 2.25%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                 | 1         | 1.12%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.12%   |
| Unknown (08B5) RAM IM308GU16N16 8192MB SODIMM DDR3 1333MT/s    | 1         | 1.12%   |
| Transcend RAM JM2666HSB-8G 8GB SODIMM DDR4 2667MT/s            | 1         | 1.12%   |
| Transcend RAM JM1600KSN-4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.12%   |
| SK Hynix RAM Module 4096MB Row Of Chips LPDDR4 3733MT/s        | 1         | 1.12%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.12%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.12%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.12%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.12%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.12%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.12%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s         | 1         | 1.12%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s     | 1         | 1.12%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                    | 1         | 1.12%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.12%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s          | 1         | 1.12%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s       | 1         | 1.12%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.12%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.12%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.12%   |
| Samsung RAM M471B1G73DH0-CH9 8192MB SODIMM DDR3 1333MT/s       | 1         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s    | 1         | 1.12%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 1         | 1.12%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.12%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.12%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s          | 1         | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 1.12%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s    | 1         | 1.12%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 1         | 1.12%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s     | 1         | 1.12%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s           | 1         | 1.12%   |
| Nanya RAM M2S4G64CB8HG5N-CG 4GB SODIMM DDR3 1334MT/s           | 1         | 1.12%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.12%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s          | 1         | 1.12%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.12%   |
| Micron RAM 4ATS1G64HZ-2G3A1 8GB SODIMM DDR4 2400MT/s           | 1         | 1.12%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s          | 1         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 1         | 1.12%   |
| Lexar RAM LD4AS008G-3200ST 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.12%   |
| Kingston RAM KHX3200C20S4/16GX 16GB SODIMM DDR4 3200MT/s       | 1         | 1.12%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s        | 1         | 1.12%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s           | 1         | 1.12%   |
| Kingston RAM ACR24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s          | 1         | 1.12%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 37        | 52.11%  |
| DDR3   | 24        | 33.8%   |
| LPDDR4 | 6         | 8.45%   |
| LPDDR3 | 3         | 4.23%   |
| SDRAM  | 1         | 1.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 85.71%  |
| Row Of Chips | 10        | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 31        | 41.33%  |
| 8192  | 25        | 33.33%  |
| 16384 | 10        | 13.33%  |
| 2048  | 9         | 12%     |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 18        | 23.08%  |
| 2667  | 16        | 20.51%  |
| 3200  | 12        | 15.38%  |
| 2400  | 9         | 11.54%  |
| 2133  | 4         | 5.13%   |
| 1334  | 4         | 5.13%   |
| 1333  | 4         | 5.13%   |
| 4267  | 3         | 3.85%   |
| 3266  | 3         | 3.85%   |
| 1067  | 3         | 3.85%   |
| 4199  | 1         | 1.28%   |
| 3733  | 1         | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 50%     |
| Samsung Electronics | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson ME-100 Series | 1         | 50%     |
| Samsung SCX-4300 Series   | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 36        | 27.27%  |
| IMC Networks                           | 21        | 15.91%  |
| Acer                                   | 19        | 14.39%  |
| Realtek Semiconductor                  | 13        | 9.85%   |
| Microdia                               | 9         | 6.82%   |
| Quanta                                 | 8         | 6.06%   |
| Suyin                                  | 3         | 2.27%   |
| Silicon Motion                         | 3         | 2.27%   |
| Logitech                               | 3         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.27%   |
| Apple                                  | 3         | 2.27%   |
| Sunplus Innovation Technology          | 2         | 1.52%   |
| Lite-On Technology                     | 2         | 1.52%   |
| Z-Star Microelectronics                | 1         | 0.76%   |
| Sonix Technology                       | 1         | 0.76%   |
| Samsung Electronics                    | 1         | 0.76%   |
| Microsoft                              | 1         | 0.76%   |
| Lenovo                                 | 1         | 0.76%   |
| Aveo Technology                        | 1         | 0.76%   |
| Alcor Micro                            | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                           | 9         | 6.82%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 7         | 5.3%    |
| Chicony Integrated Camera                                   | 5         | 3.79%   |
| Realtek Integrated_Webcam_HD                                | 4         | 3.03%   |
| Microdia Integrated_Webcam_HD                               | 4         | 3.03%   |
| Chicony HP TrueVision HD Camera                             | 4         | 3.03%   |
| Acer Lenovo EasyCamera                                      | 4         | 3.03%   |
| Acer Integrated Camera                                      | 4         | 3.03%   |
| Silicon Motion WebCam SCB-0385N                             | 3         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 2.27%   |
| IMC Networks Integrated Camera                              | 3         | 2.27%   |
| Chicony Lenovo EasyCamera                                   | 3         | 2.27%   |
| Acer SunplusIT Integrated Camera                            | 3         | 2.27%   |
| Acer Lenovo Integrated Webcam                               | 3         | 2.27%   |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.52%   |
| Quanta VGA WebCam                                           | 2         | 1.52%   |
| Quanta HD Webcam                                            | 2         | 1.52%   |
| Microdia Integrated Webcam                                  | 2         | 1.52%   |
| IMC Networks VGA UVC WebCam                                 | 2         | 1.52%   |
| IMC Networks HD Camera                                      | 2         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                               | 2         | 1.52%   |
| Apple FaceTime Camera                                       | 2         | 1.52%   |
| Acer HD Webcam                                              | 2         | 1.52%   |
| Z-Star WebCam SCB-1900N                                     | 1         | 0.76%   |
| Suyin UVC HD Webcam                                         | 1         | 0.76%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.76%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.76%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.76%   |
| Sonix USB2.0 HD UVC WebCam                                  | 1         | 0.76%   |
| Samsung Galaxy A5 (MTP)                                     | 1         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                               | 1         | 0.76%   |
| Realtek USB Camera                                          | 1         | 0.76%   |
| Realtek Integrated Webcam                                   | 1         | 0.76%   |
| Realtek HP Truevision HD                                    | 1         | 0.76%   |
| Realtek HD Webcam - Realtek                                 | 1         | 0.76%   |
| Realtek HD WebCam                                           | 1         | 0.76%   |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 0.76%   |
| Quanta USB2.0 HD UVC WebCam                                 | 1         | 0.76%   |
| Quanta ov9734_techfront_camera                              | 1         | 0.76%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 0.76%   |
| Quanta HD User Facing                                       | 1         | 0.76%   |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks         | 1         | 0.76%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.76%   |
| Microdia Dell Integrated HD Webcam                          | 1         | 0.76%   |
| Microdia 1.3 MPixel Integrated Webcam                       | 1         | 0.76%   |
| Logitech HP Webcam                                          | 1         | 0.76%   |
| Logitech HD Pro Webcam C920                                 | 1         | 0.76%   |
| Logitech C920 PRO HD Webcam                                 | 1         | 0.76%   |
| Lite-On Integrated Camera                                   | 1         | 0.76%   |
| Lite-On HP Wide Vision HD Camera                            | 1         | 0.76%   |
| Lenovo Integrated Webcam                                    | 1         | 0.76%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 1         | 0.76%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 0.76%   |
| IMC Networks Lenovo EasyCamera                              | 1         | 0.76%   |
| IMC Networks EasyCamera                                     | 1         | 0.76%   |
| Chicony VGA WebCam                                          | 1         | 0.76%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 0.76%   |
| Chicony USB2.0 Camera                                       | 1         | 0.76%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 8         | 32%     |
| Synaptics                  | 6         | 24%     |
| Validity Sensors           | 4         | 16%     |
| Upek                       | 2         | 8%      |
| LighTuning Technology      | 2         | 8%      |
| AuthenTec                  | 2         | 8%      |
| Elan Microelectronics      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 5         | 20%     |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 12%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 8%      |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 8%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8%      |
| Unknown                                                | 2         | 8%      |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4%      |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4%      |
| Elan ELAN:Fingerprint                                  | 1         | 4%      |
| AuthenTec AES2810                                      | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 50%     |
| Broadcom    | 2         | 33.33%  |
| O2 Micro    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 91        | 61.49%  |
| 1     | 45        | 30.41%  |
| 2     | 12        | 8.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 37.31%  |
| Graphics card         | 13        | 19.4%   |
| Net/wireless          | 9         | 13.43%  |
| Multimedia controller | 8         | 11.94%  |
| Chipcard              | 6         | 8.96%   |
| Bluetooth             | 2         | 2.99%   |
| Storage/ide           | 1         | 1.49%   |
| Flash memory          | 1         | 1.49%   |
| Card reader           | 1         | 1.49%   |
| Camera                | 1         | 1.49%   |

