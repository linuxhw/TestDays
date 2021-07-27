Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
  - [ Dual Boot with Linux/BSD ](#dual-boot-with-linux-bsd)
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

* [ Printers & scanners ](#printers-scanners)
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
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 68        | 40%     |
| 5.10.0-7-amd64             | 53        | 31.18%  |
| 5.10.0-6-amd64             | 23        | 13.53%  |
| 5.12.0-19.3-liquorix-amd64 | 2         | 1.18%   |
| 4.19.0-14-amd64            | 2         | 1.18%   |
| 5.13.5-xanmod1             | 1         | 0.59%   |
| 5.13.4-e5520               | 1         | 0.59%   |
| 5.12.10                    | 1         | 0.59%   |
| 5.12.1                     | 1         | 0.59%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.59%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.59%   |
| 5.11.9+                    | 1         | 0.59%   |
| 5.11.22-1-pve              | 1         | 0.59%   |
| 5.11.15-051115-generic     | 1         | 0.59%   |
| 5.11.14                    | 1         | 0.59%   |
| 5.11.0-rc6                 | 1         | 0.59%   |
| 5.10.40-ismynik            | 1         | 0.59%   |
| 5.10.0-io7-amd64           | 1         | 0.59%   |
| 5.10.0-8-686-pae           | 1         | 0.59%   |
| 5.10.0-8-686               | 1         | 0.59%   |
| 5.10.0-6-rt-amd64          | 1         | 0.59%   |
| 5.10.0-6-686               | 1         | 0.59%   |
| 5.10.0-5-amd64             | 1         | 0.59%   |
| 5.10.0-4-amd64             | 1         | 0.59%   |
| 4.19.181-z580322           | 1         | 0.59%   |
| 4.19.0-16-amd64            | 1         | 0.59%   |
| 4.19.0-16-686-pae          | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 145       | 88.96%  |
| 4.19.0   | 4         | 2.45%   |
| 5.12.0   | 3         | 1.84%   |
| 5.13.5   | 1         | 0.61%   |
| 5.13.4   | 1         | 0.61%   |
| 5.12.10  | 1         | 0.61%   |
| 5.12.1   | 1         | 0.61%   |
| 5.11.9   | 1         | 0.61%   |
| 5.11.22  | 1         | 0.61%   |
| 5.11.15  | 1         | 0.61%   |
| 5.11.14  | 1         | 0.61%   |
| 5.11.0   | 1         | 0.61%   |
| 5.10.40  | 1         | 0.61%   |
| 4.19.181 | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 146       | 89.57%  |
| 5.12    | 5         | 3.07%   |
| 5.11    | 5         | 3.07%   |
| 4.19    | 5         | 3.07%   |
| 5.13    | 2         | 1.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 159       | 97.55%  |
| i686   | 4         | 2.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 58        | 35.15%  |
| KDE5             | 37        | 22.42%  |
| XFCE             | 18        | 10.91%  |
| MATE             | 10        | 6.06%   |
| Unknown          | 7         | 4.24%   |
| i3               | 6         | 3.64%   |
| LXQt             | 5         | 3.03%   |
| LXDE             | 4         | 2.42%   |
| KDE              | 4         | 2.42%   |
| X-Cinnamon       | 3         | 1.82%   |
| lightdm-xsession | 3         | 1.82%   |
| Cinnamon         | 3         | 1.82%   |
| openbox          | 2         | 1.21%   |
| GNOME Flashback  | 2         | 1.21%   |
| sway             | 1         | 0.61%   |
| default          | 1         | 0.61%   |
| awesome          | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 103       | 62.42%  |
| Wayland | 49        | 29.7%   |
| Tty     | 10        | 6.06%   |
| Unknown | 3         | 1.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 57        | 34.76%  |
| TDM     | 41        | 25%     |
| SDDM    | 40        | 24.39%  |
| Unknown | 23        | 14.02%  |
| LightDM | 2         | 1.22%   |
| XDM     | 1         | 0.61%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 67        | 41.1%   |
| en_GB   | 12        | 7.36%   |
| ru_RU   | 10        | 6.13%   |
| fr_FR   | 10        | 6.13%   |
| de_DE   | 10        | 6.13%   |
| en_IN   | 7         | 4.29%   |
| es_ES   | 6         | 3.68%   |
| pt_BR   | 5         | 3.07%   |
| pl_PL   | 4         | 2.45%   |
| it_IT   | 4         | 2.45%   |
| tr_TR   | 3         | 1.84%   |
| pt_PT   | 2         | 1.23%   |
| en_SG   | 2         | 1.23%   |
| en_AU   | 2         | 1.23%   |
| de_CH   | 2         | 1.23%   |
| uk_UA   | 1         | 0.61%   |
| ru_UA   | 1         | 0.61%   |
| ro_RO   | 1         | 0.61%   |
| nl_BE   | 1         | 0.61%   |
| ja_JP   | 1         | 0.61%   |
| hu_HU   | 1         | 0.61%   |
| hr_HR   | 1         | 0.61%   |
| fi_FI   | 1         | 0.61%   |
| es_MX   | 1         | 0.61%   |
| es_EC   | 1         | 0.61%   |
| es_CO   | 1         | 0.61%   |
| en_HK   | 1         | 0.61%   |
| en_CA   | 1         | 0.61%   |
| cs_CZ   | 1         | 0.61%   |
| ca_ES   | 1         | 0.61%   |
| C       | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 111       | 67.68%  |
| BIOS | 53        | 32.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 142       | 87.12%  |
| Btrfs   | 11        | 6.75%   |
| Overlay | 6         | 3.68%   |
| Xfs     | 2         | 1.23%   |
| Zfs     | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 114       | 69.51%  |
| MBR     | 35        | 21.34%  |
| Unknown | 15        | 9.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 87.8%   |
| Yes       | 20        | 12.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 69.94%  |
| Yes       | 49        | 30.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 55        | 33.74%  |
| Hewlett-Packard     | 28        | 17.18%  |
| Dell                | 28        | 17.18%  |
| ASUSTek Computer    | 17        | 10.43%  |
| Acer                | 10        | 6.13%   |
| MSI                 | 4         | 2.45%   |
| Toshiba             | 3         | 1.84%   |
| HUAWEI              | 3         | 1.84%   |
| Apple               | 3         | 1.84%   |
| Gigabyte Technology | 2         | 1.23%   |
| Fujitsu             | 2         | 1.23%   |
| UNOWHY              | 1         | 0.61%   |
| Samsung Electronics | 1         | 0.61%   |
| Quanta              | 1         | 0.61%   |
| Pegatron            | 1         | 0.61%   |
| PC Specialist       | 1         | 0.61%   |
| Panasonic           | 1         | 0.61%   |
| Monster             | 1         | 0.61%   |
| Itautec             | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo G50-80 80E5                          | 2         | 1.23%   |
| HUAWEI NBLK-WAX9X                           | 2         | 1.23%   |
| Dell XPS 13 9310                            | 2         | 1.23%   |
| Dell Latitude 7480                          | 2         | 1.23%   |
| Dell Inspiron 3793                          | 2         | 1.23%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA     | 2         | 1.23%   |
| UNOWHY Y13G002S4EI                          | 1         | 0.61%   |
| Toshiba Satellite U800W                     | 1         | 0.61%   |
| Toshiba Satellite S55-A                     | 1         | 0.61%   |
| Toshiba Satellite C45-A                     | 1         | 0.61%   |
| Samsung 370E4K                              | 1         | 0.61%   |
| Quanta TWC                                  | 1         | 0.61%   |
| Pegatron A15                                | 1         | 0.61%   |
| PC Specialist NV4XMB,ME,MZ                  | 1         | 0.61%   |
| Panasonic CF-AX2LDCZMF                      | 1         | 0.61%   |
| MSI U90/U100                                | 1         | 0.61%   |
| MSI Modern 15 A11M                          | 1         | 0.61%   |
| MSI GF65 Thin 10UE                          | 1         | 0.61%   |
| MSI CX700                                   | 1         | 0.61%   |
| Monster ABRA A5 V15.2                       | 1         | 0.61%   |
| Lenovo Yoga 300-11IBR 80M1                  | 1         | 0.61%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00       | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S46R00             | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S0JF00             | 1         | 0.61%   |
| Lenovo ThinkPad X230 2325AZ8                | 1         | 0.61%   |
| Lenovo ThinkPad X201 3626ES3                | 1         | 0.61%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT    | 1         | 0.61%   |
| Lenovo ThinkPad T530 24296HG                | 1         | 0.61%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 0.61%   |
| Lenovo ThinkPad T495 20NJCTO1WW             | 1         | 0.61%   |
| Lenovo ThinkPad T490 20N2CTO1WW             | 1         | 0.61%   |
| Lenovo ThinkPad T480s 20L8S7HF00            | 1         | 0.61%   |
| Lenovo ThinkPad T480 20L5S1S000             | 1         | 0.61%   |
| Lenovo ThinkPad T480 20L50063EU             | 1         | 0.61%   |
| Lenovo ThinkPad T470 W10DG 20JNS42314       | 1         | 0.61%   |
| Lenovo ThinkPad T460 20FMS03600             | 1         | 0.61%   |
| Lenovo ThinkPad T450s 20BX004QGE            | 1         | 0.61%   |
| Lenovo ThinkPad T440p 20AWS4PN00            | 1         | 0.61%   |
| Lenovo ThinkPad T430s 2356A89               | 1         | 0.61%   |
| Lenovo ThinkPad T430s 23533KJ               | 1         | 0.61%   |
| Lenovo ThinkPad T430 2349V4B                | 1         | 0.61%   |
| Lenovo ThinkPad T430 2349GCG                | 1         | 0.61%   |
| Lenovo ThinkPad T430 2349BW1                | 1         | 0.61%   |
| Lenovo ThinkPad T430 2347FF9                | 1         | 0.61%   |
| Lenovo ThinkPad T420 4236WNU                | 1         | 0.61%   |
| Lenovo ThinkPad T420 4236WC3                | 1         | 0.61%   |
| Lenovo ThinkPad T420 4236EV9                | 1         | 0.61%   |
| Lenovo ThinkPad T410 2522WUZ                | 1         | 0.61%   |
| Lenovo ThinkPad T14s Gen 1 20UH001AGE       | 1         | 0.61%   |
| Lenovo ThinkPad T14 Gen 2i 20W0CTO1WW       | 1         | 0.61%   |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW        | 1         | 0.61%   |
| Lenovo ThinkPad P14s Gen 1 20Y1002AFR       | 1         | 0.61%   |
| Lenovo ThinkPad Edge E540 20C600KCJP        | 1         | 0.61%   |
| Lenovo ThinkPad E595 20NF0005IX             | 1         | 0.61%   |
| Lenovo ThinkPad E480 20KN001NGE             | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 3 20YHS00900        | 1         | 0.61%   |
| Lenovo ThinkPad E15 Gen 2 20TD003MRT        | 1         | 0.61%   |
| Lenovo ThinkPad E14 20RB000UBR              | 1         | 0.61%   |
| Lenovo ThinkPad E14 20RAS13M00              | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 41        | 25.15%  |
| Lenovo IdeaPad         | 11        | 6.75%   |
| Dell Inspiron          | 10        | 6.13%   |
| Acer Aspire            | 9         | 5.52%   |
| Dell XPS               | 8         | 4.91%   |
| HP EliteBook           | 7         | 4.29%   |
| HP ProBook             | 6         | 3.68%   |
| Dell Latitude          | 6         | 3.68%   |
| ASUS VivoBook          | 5         | 3.07%   |
| HP Laptop              | 4         | 2.45%   |
| ASUS ZenBook           | 4         | 2.45%   |
| Toshiba Satellite      | 3         | 1.84%   |
| HP Compaq              | 3         | 1.84%   |
| Lenovo G50-80          | 2         | 1.23%   |
| HUAWEI NBLK-WAX9X      | 2         | 1.23%   |
| HP ZBook               | 2         | 1.23%   |
| HP 250                 | 2         | 1.23%   |
| Gigabyte AERO          | 2         | 1.23%   |
| Fujitsu LIFEBOOK       | 2         | 1.23%   |
| Dell Precision         | 2         | 1.23%   |
| UNOWHY Y13G002S4EI     | 1         | 0.61%   |
| Samsung 370E4K         | 1         | 0.61%   |
| Quanta TWC             | 1         | 0.61%   |
| Pegatron A15           | 1         | 0.61%   |
| PC Specialist NV4XMB   | 1         | 0.61%   |
| Panasonic CF-AX2LDCZMF | 1         | 0.61%   |
| MSI U90                | 1         | 0.61%   |
| MSI Modern             | 1         | 0.61%   |
| MSI GF65               | 1         | 0.61%   |
| MSI CX700              | 1         | 0.61%   |
| Monster ABRA           | 1         | 0.61%   |
| Lenovo Yoga            | 1         | 0.61%   |
| Itautec Infoway        | 1         | 0.61%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.61%   |
| HP Stream              | 1         | 0.61%   |
| HP Split               | 1         | 0.61%   |
| HP OMEN                | 1         | 0.61%   |
| HP 2000                | 1         | 0.61%   |
| Dell Vostro            | 1         | 0.61%   |
| Dell Studio            | 1         | 0.61%   |
| ASUS X550LD            | 1         | 0.61%   |
| ASUS X541NC            | 1         | 0.61%   |
| ASUS TUF               | 1         | 0.61%   |
| ASUS ROG               | 1         | 0.61%   |
| ASUS M3N               | 1         | 0.61%   |
| ASUS 701SD             | 1         | 0.61%   |
| ASUS 701               | 1         | 0.61%   |
| ASUS 1215B             | 1         | 0.61%   |
| Apple MacBookPro9      | 1         | 0.61%   |
| Apple MacBookPro8      | 1         | 0.61%   |
| Apple MacBookPro11     | 1         | 0.61%   |
| Acer Nitro             | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 37        | 22.7%   |
| 2021 | 33        | 20.25%  |
| 2019 | 28        | 17.18%  |
| 2018 | 12        | 7.36%   |
| 2012 | 10        | 6.13%   |
| 2013 | 9         | 5.52%   |
| 2016 | 7         | 4.29%   |
| 2011 | 6         | 3.68%   |
| 2017 | 5         | 3.07%   |
| 2014 | 4         | 2.45%   |
| 2008 | 4         | 2.45%   |
| 2015 | 3         | 1.84%   |
| 2009 | 3         | 1.84%   |
| 2007 | 1         | 0.61%   |
| 2004 | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 163       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 137       | 83.03%  |
| Enabled  | 28        | 16.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 163       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 46        | 28.22%  |
| 16.01-24.0  | 42        | 25.77%  |
| 8.01-16.0   | 29        | 17.79%  |
| 3.01-4.0    | 20        | 12.27%  |
| 32.01-64.0  | 10        | 6.13%   |
| 1.01-2.0    | 6         | 3.68%   |
| 2.01-3.0    | 3         | 1.84%   |
| 64.01-256.0 | 3         | 1.84%   |
| 24.01-32.0  | 2         | 1.23%   |
| 0.01-0.5    | 2         | 1.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 45        | 26.79%  |
| 1.01-2.0   | 38        | 22.62%  |
| 4.01-8.0   | 27        | 16.07%  |
| 3.01-4.0   | 24        | 14.29%  |
| 8.01-16.0  | 14        | 8.33%   |
| 0.51-1.0   | 13        | 7.74%   |
| 0.01-0.5   | 6         | 3.57%   |
| 32.01-64.0 | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 107       | 65.64%  |
| 2      | 49        | 30.06%  |
| 3      | 3         | 1.84%   |
| 4      | 2         | 1.23%   |
| 0      | 2         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 125       | 76.69%  |
| Yes       | 38        | 23.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 77.91%  |
| No        | 36        | 22.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 98.16%  |
| No        | 3         | 1.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 80.37%  |
| No        | 32        | 19.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 17        | 10.43%  |
| USA         | 16        | 9.82%   |
| France      | 15        | 9.2%    |
| Russia      | 14        | 8.59%   |
| Spain       | 7         | 4.29%   |
| Poland      | 7         | 4.29%   |
| India       | 7         | 4.29%   |
| Brazil      | 7         | 4.29%   |
| Ukraine     | 6         | 3.68%   |
| UK          | 5         | 3.07%   |
| Netherlands | 5         | 3.07%   |
| Thailand    | 4         | 2.45%   |
| Switzerland | 4         | 2.45%   |
| Greece      | 4         | 2.45%   |
| Turkey      | 3         | 1.84%   |
| Portugal    | 3         | 1.84%   |
| Kazakhstan  | 3         | 1.84%   |
| Italy       | 3         | 1.84%   |
| Canada      | 3         | 1.84%   |
| Belarus     | 3         | 1.84%   |
| Mexico      | 2         | 1.23%   |
| Ecuador     | 2         | 1.23%   |
| Czechia     | 2         | 1.23%   |
| Croatia     | 2         | 1.23%   |
| Australia   | 2         | 1.23%   |
| Slovenia    | 1         | 0.61%   |
| Romania     | 1         | 0.61%   |
| Philippines | 1         | 0.61%   |
| Mongolia    | 1         | 0.61%   |
| Malaysia    | 1         | 0.61%   |
| Japan       | 1         | 0.61%   |
| Indonesia   | 1         | 0.61%   |
| Hungary     | 1         | 0.61%   |
| Finland     | 1         | 0.61%   |
| Denmark     | 1         | 0.61%   |
| Colombia    | 1         | 0.61%   |
| China       | 1         | 0.61%   |
| Bulgaria    | 1         | 0.61%   |
| Belgium     | 1         | 0.61%   |
| Bangladesh  | 1         | 0.61%   |
| Austria     | 1         | 0.61%   |
| Argentina   | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Paris                | 7         | 4.27%   |
| St Petersburg        | 6         | 3.66%   |
| Bengaluru            | 4         | 2.44%   |
| Bangkok              | 4         | 2.44%   |
| Rio de Janeiro       | 2         | 1.22%   |
| Mesa                 | 2         | 1.22%   |
| Kyiv                 | 2         | 1.22%   |
| Gorinchem            | 2         | 1.22%   |
| Gloucester           | 2         | 1.22%   |
| Fryazino             | 2         | 1.22%   |
| Berlin               | 2         | 1.22%   |
| Athens               | 2         | 1.22%   |
| Ankara               | 2         | 1.22%   |
| Zurich               | 1         | 0.61%   |
| Zaragoza             | 1         | 0.61%   |
| Zagreb               | 1         | 0.61%   |
| Waterloo             | 1         | 0.61%   |
| Warsaw               | 1         | 0.61%   |
| Waregem              | 1         | 0.61%   |
| VitÃ³ria             | 1         | 0.61%   |
| Vienna               | 1         | 0.61%   |
| Valladolid           | 1         | 0.61%   |
| Utrecht              | 1         | 0.61%   |
| Tyumen               | 1         | 0.61%   |
| Turin                | 1         | 0.61%   |
| Toul                 | 1         | 0.61%   |
| Toronto              | 1         | 0.61%   |
| Thonex               | 1         | 0.61%   |
| The Hague            | 1         | 0.61%   |
| The Colony           | 1         | 0.61%   |
| Tarn??w              | 1         | 0.61%   |
| Sydney               | 1         | 0.61%   |
| Sunnyvale            | 1         | 0.61%   |
| Stepnogorsk          | 1         | 0.61%   |
| Srednyaya Akhtuba    | 1         | 0.61%   |
| Sofia                | 1         | 0.61%   |
| Shizuoka             | 1         | 0.61%   |
| Schleswig            | 1         | 0.61%   |
| Saynshand            | 1         | 0.61%   |
| Sarand               | 1         | 0.61%   |
| San Justo            | 1         | 0.61%   |
| Sagunto              | 1         | 0.61%   |
| Runding              | 1         | 0.61%   |
| Rottenburg           | 1         | 0.61%   |
| Rio Vista            | 1         | 0.61%   |
| Reliquias            | 1         | 0.61%   |
| Regen                | 1         | 0.61%   |
| Ratiskovice          | 1         | 0.61%   |
| Pune                 | 1         | 0.61%   |
| Pula                 | 1         | 0.61%   |
| Pokrovsk             | 1         | 0.61%   |
| Piracicaba           | 1         | 0.61%   |
| Perm                 | 1         | 0.61%   |
| P?™?­bram            | 1         | 0.61%   |
| Paderno Franciacorta | 1         | 0.61%   |
| Oleksandrivka        | 1         | 0.61%   |
| Odessa               | 1         | 0.61%   |
| Nur-Sultan           | 1         | 0.61%   |
| Novo Hamburgo        | 1         | 0.61%   |
| Nova Porteirinha     | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 45     | 18.57%  |
| WDC                 | 26        | 32     | 12.38%  |
| Seagate             | 21        | 23     | 10%     |
| Toshiba             | 18        | 18     | 8.57%   |
| Unknown             | 12        | 14     | 5.71%   |
| Kingston            | 12        | 14     | 5.71%   |
| Crucial             | 10        | 10     | 4.76%   |
| SK Hynix            | 8         | 8      | 3.81%   |
| Intel               | 8         | 8      | 3.81%   |
| A-DATA Technology   | 6         | 8      | 2.86%   |
| SanDisk             | 4         | 4      | 1.9%    |
| Micron Technology   | 4         | 4      | 1.9%    |
| Transcend           | 3         | 3      | 1.43%   |
| LITEONIT            | 3         | 3      | 1.43%   |
| Hitachi             | 3         | 3      | 1.43%   |
| HGST                | 3         | 3      | 1.43%   |
| China               | 3         | 3      | 1.43%   |
| Union Memory        | 2         | 2      | 0.95%   |
| Patriot             | 2         | 2      | 0.95%   |
| LITEON              | 2         | 2      | 0.95%   |
| Lenovo              | 2         | 2      | 0.95%   |
| KIOXIA              | 2         | 2      | 0.95%   |
| JMicron             | 2         | 2      | 0.95%   |
| Intenso             | 2         | 2      | 0.95%   |
| Apple               | 2         | 2      | 0.95%   |
| ZTC                 | 1         | 1      | 0.48%   |
| XPG                 | 1         | 1      | 0.48%   |
| SILICONMOTION       | 1         | 1      | 0.48%   |
| Silicon Motion      | 1         | 2      | 0.48%   |
| Phison              | 1         | 4      | 0.48%   |
| Maxtor              | 1         | 2      | 0.48%   |
| LDLC                | 1         | 1      | 0.48%   |
| Fujitsu             | 1         | 1      | 0.48%   |
| ASUS-PHISON         | 1         | 1      | 0.48%   |
| Apacer              | 1         | 1      | 0.48%   |
| AMD                 | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 970 EVO Plus 1TB            | 4         | 1.81%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 1.36%   |
| Unknown DA4064  64GB                    | 3         | 1.36%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 1.36%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.36%   |
| Samsung SSD 850 EVO 500GB               | 3         | 1.36%   |
| Samsung SSD 850 EVO 250GB               | 3         | 1.36%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 1.36%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.36%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.9%    |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 2         | 0.9%    |
| Samsung SSD 970 EVO Plus 500GB          | 2         | 0.9%    |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.9%    |
| Samsung SSD 860 EVO 500GB               | 2         | 0.9%    |
| Samsung SSD 860 EVO 1TB                 | 2         | 0.9%    |
| Samsung SSD 850 EVO M.2 250GB           | 2         | 0.9%    |
| Samsung MZALQ256HAJD-000L1 256GB        | 2         | 0.9%    |
| Kingston OM8PCP3512F-AI1 512GB          | 2         | 0.9%    |
| HGST HTS721010A9E630 1TB                | 2         | 0.9%    |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.9%    |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.9%    |
| ZTC SM201-512G SSD                      | 1         | 0.45%   |
| XPG NVMe SSD Drive 1024GB               | 1         | 0.45%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.45%   |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.45%   |
| WDC WD5000BPVT-00HXZT3 500GB            | 1         | 0.45%   |
| WDC WD50 00LPCX-24VHA 500GB             | 1         | 0.45%   |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 0.45%   |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 0.45%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.45%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.45%   |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.45%   |
| WDC WD10JPVT-75A1YT0 1TB                | 1         | 0.45%   |
| WDC WD10JPVT-00A1YT0 1TB                | 1         | 0.45%   |
| WDC WD-WD3200BVVT-62A26Y080 320GB       | 1         | 0.45%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 1         | 0.45%   |
| WDC PC SN730 SDBPNTY-256G-1027 256GB    | 1         | 0.45%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 1         | 0.45%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 1         | 0.45%   |
| WDC PC SN530 SDBPNPZ-1T00-1006 1TB      | 1         | 0.45%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 1         | 0.45%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB    | 1         | 0.45%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB    | 1         | 0.45%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB    | 1         | 0.45%   |
| Unknown SU01G  1GB                      | 1         | 0.45%   |
| Unknown SL16G  16GB                     | 1         | 0.45%   |
| Unknown SL128  128GB                    | 1         | 0.45%   |
| Unknown SDW32G  32GB                    | 1         | 0.45%   |
| Unknown SD64G  64GB                     | 1         | 0.45%   |
| Unknown SD/MMC/MS PRO 32GB              | 1         | 0.45%   |
| Unknown SC32G  32GB                     | 1         | 0.45%   |
| Unknown SB64G  64GB                     | 1         | 0.45%   |
| Unknown LX32G  32GB                     | 1         | 0.45%   |
| Unknown BGND3R  32GB                    | 1         | 0.45%   |
| Unknown APPSD  272GB                    | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 19     | 34.69%  |
| WDC                 | 14        | 15     | 28.57%  |
| Toshiba             | 9         | 9      | 18.37%  |
| Hitachi             | 3         | 3      | 6.12%   |
| HGST                | 3         | 3      | 6.12%   |
| SILICONMOTION       | 1         | 1      | 2.04%   |
| Samsung Electronics | 1         | 1      | 2.04%   |
| Fujitsu             | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 25     | 26.32%  |
| Kingston            | 7         | 9      | 9.21%   |
| Crucial             | 7         | 7      | 9.21%   |
| Intel               | 5         | 5      | 6.58%   |
| WDC                 | 3         | 5      | 3.95%   |
| Transcend           | 3         | 3      | 3.95%   |
| SanDisk             | 3         | 3      | 3.95%   |
| LITEONIT            | 3         | 3      | 3.95%   |
| China               | 3         | 3      | 3.95%   |
| Seagate             | 2         | 2      | 2.63%   |
| Patriot             | 2         | 2      | 2.63%   |
| Intenso             | 2         | 2      | 2.63%   |
| Apple               | 2         | 2      | 2.63%   |
| A-DATA Technology   | 2         | 2      | 2.63%   |
| ZTC                 | 1         | 1      | 1.32%   |
| Union Memory        | 1         | 1      | 1.32%   |
| Toshiba             | 1         | 1      | 1.32%   |
| SK Hynix            | 1         | 1      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| Maxtor              | 1         | 2      | 1.32%   |
| LITEON              | 1         | 1      | 1.32%   |
| LDLC                | 1         | 1      | 1.32%   |
| JMicron             | 1         | 1      | 1.32%   |
| ASUS-PHISON         | 1         | 1      | 1.32%   |
| Apacer              | 1         | 1      | 1.32%   |
| AMD                 | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 70        | 86     | 35%     |
| NVMe    | 66        | 80     | 33%     |
| HDD     | 49        | 52     | 24.5%   |
| MMC     | 11        | 13     | 5.5%    |
| Unknown | 4         | 4      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 130    | 53.76%  |
| NVMe | 66        | 80     | 35.48%  |
| MMC  | 11        | 13     | 5.91%   |
| SAS  | 9         | 12     | 4.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 72        | 91     | 61.54%  |
| 0.51-1.0   | 38        | 40     | 32.48%  |
| 1.01-2.0   | 5         | 5      | 4.27%   |
| 3.01-4.0   | 1         | 1      | 0.85%   |
| 2.01-3.0   | 1         | 1      | 0.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 42        | 25.45%  |
| 101-250        | 39        | 23.64%  |
| 501-1000       | 23        | 13.94%  |
| 1001-2000      | 21        | 12.73%  |
| 51-100         | 13        | 7.88%   |
| 1-20           | 11        | 6.67%   |
| 21-50          | 9         | 5.45%   |
| More than 3000 | 4         | 2.42%   |
| Unknown        | 2         | 1.21%   |
| 2001-3000      | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 46        | 27.38%  |
| 21-50     | 31        | 18.45%  |
| 101-250   | 26        | 15.48%  |
| 51-100    | 23        | 13.69%  |
| 251-500   | 18        | 10.71%  |
| 501-1000  | 14        | 8.33%   |
| 1001-2000 | 5         | 2.98%   |
| 0         | 2         | 1.19%   |
| Unknown   | 2         | 1.19%   |
| 2001-3000 | 1         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD10JPVT-75A1YT0 1TB                     | 1         | 1      | 5.88%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 5.88%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 5.88%   |
| Seagate ST9160310AS 160GB                    | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 5.88%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 5.88%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 5.88%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 5.88%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 5.88%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 5.88%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 5.88%   |
| A-DATA Technology SU630 480GB SSD            | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 29.41%  |
| Toshiba             | 3         | 3      | 17.65%  |
| Intel               | 2         | 2      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| WDC                 | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 2      | 5.88%   |
| LITEONIT            | 1         | 1      | 5.88%   |
| HGST                | 1         | 1      | 5.88%   |
| A-DATA Technology   | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| Toshiba | 3         | 3      | 25%     |
| Hitachi | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 70.59%  |
| SSD  | 5         | 6      | 29.41%  |

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
| Works    | 129       | 169    | 72.88%  |
| Detected | 31        | 48     | 17.51%  |
| Malfunc  | 17        | 18     | 9.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 109       | 57.98%  |
| Samsung Electronics          | 20        | 10.64%  |
| Sandisk                      | 11        | 5.85%   |
| AMD                          | 10        | 5.32%   |
| Toshiba America Info Systems | 7         | 3.72%   |
| SK Hynix                     | 7         | 3.72%   |
| Kingston Technology Company  | 5         | 2.66%   |
| ADATA Technology             | 4         | 2.13%   |
| Micron/Crucial Technology    | 3         | 1.6%    |
| Micron Technology            | 3         | 1.6%    |
| KIOXIA                       | 3         | 1.6%    |
| Lenovo                       | 2         | 1.06%   |
| Union Memory (Shenzhen)      | 1         | 0.53%   |
| Silicon Motion               | 1         | 0.53%   |
| Phison Electronics           | 1         | 0.53%   |
| Lite-On Technology           | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 10.2%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 7.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 6.63%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 4.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 3.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 5         | 2.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 2.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 2.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 2.04%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.53%   |
| Samsung NVMe Controller                                                          | 3         | 1.53%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 1.53%   |
| Micron Non-Volatile memory controller                                            | 3         | 1.53%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 1.53%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.53%   |
| SK Hynix NVMe SSD Controller                                                     | 2         | 1.02%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.02%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.02%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 1.02%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 1.02%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.02%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.02%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.02%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 1.02%   |
| ADATA Non-Volatile memory controller                                             | 2         | 1.02%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.51%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.51%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.51%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.51%   |
| SK Hynix BC511                                                                   | 1         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.51%   |
| Samsung Electronics SATA controller                                              | 1         | 0.51%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.51%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.51%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.51%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.51%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.51%   |
| Intel SSD 660P Series                                                            | 1         | 0.51%   |
| Intel SSD 600P Series                                                            | 1         | 0.51%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.51%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.51%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 1         | 0.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 98        | 51.58%  |
| NVMe | 66        | 34.74%  |
| RAID | 19        | 10%     |
| IDE  | 7         | 3.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 141       | 86.5%   |
| AMD    | 22        | 13.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz               | 7         | 4.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 7         | 4.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 6         | 3.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 5         | 3.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 5         | 3.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 5         | 3.07%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 3.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 4         | 2.45%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 2.45%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 2.45%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 4         | 2.45%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 3         | 1.84%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 3         | 1.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 3         | 1.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 1.84%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 1.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.23%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 2         | 1.23%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 2         | 1.23%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 2         | 1.23%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.23%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 2         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.23%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 1.23%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 2         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 1.23%   |
| Intel Celeron M processor 900MHz                | 2         | 1.23%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 1.23%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.23%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                | 1         | 0.61%   |
| Intel Pentium M processor 1600MHz               | 1         | 0.61%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 0.61%   |
| Intel Pentium 3556U @ 1.70GHz                   | 1         | 0.61%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 1         | 0.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz               | 1         | 0.61%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 1         | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 0.61%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 1         | 0.61%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz              | 1         | 0.61%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz              | 1         | 0.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 0.61%   |
| Intel Core i7-3632QM CPU @ 2.20GHz              | 1         | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 1         | 0.61%   |
| Intel Core i7-3610QM CPU @ 2.30GHz              | 1         | 0.61%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.61%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 1         | 0.61%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 0.61%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 1         | 0.61%   |
| Intel Core i7-10850H CPU @ 2.70GHz              | 1         | 0.61%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 1         | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 1         | 0.61%   |
| Intel Core i5-4200Y CPU @ 1.40GHz               | 1         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 1         | 0.61%   |
| Intel Core i5-3427U CPU @ 1.80GHz               | 1         | 0.61%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 51        | 31.29%  |
| Intel Core i7    | 46        | 28.22%  |
| Other            | 14        | 8.59%   |
| Intel Core i3    | 8         | 4.91%   |
| Intel Celeron    | 8         | 4.91%   |
| AMD Ryzen 5      | 8         | 4.91%   |
| AMD Ryzen 7 PRO  | 6         | 3.68%   |
| Intel Pentium    | 5         | 3.07%   |
| Intel Core 2 Duo | 4         | 2.45%   |
| Intel Celeron M  | 2         | 1.23%   |
| AMD Ryzen 7      | 2         | 1.23%   |
| AMD Ryzen 3      | 2         | 1.23%   |
| Intel Xeon       | 1         | 0.61%   |
| Intel Pentium M  | 1         | 0.61%   |
| Intel Core 2     | 1         | 0.61%   |
| Intel Atom       | 1         | 0.61%   |
| AMD Ryzen 9      | 1         | 0.61%   |
| AMD C-30         | 1         | 0.61%   |
| AMD A12          | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 44.79%  |
| 4      | 67        | 41.1%   |
| 6      | 9         | 5.52%   |
| 8      | 8         | 4.91%   |
| 1      | 6         | 3.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 163       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 137       | 84.05%  |
| 1      | 26        | 15.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 159       | 97.55%  |
| 32-bit         | 4         | 2.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 18.18%  |
| 0x306a9    | 18        | 10.91%  |
| 0x806c1    | 11        | 6.67%   |
| 0x206a7    | 11        | 6.67%   |
| 0x306d4    | 8         | 4.85%   |
| 0x806ec    | 7         | 4.24%   |
| 0x806ea    | 7         | 4.24%   |
| 0x706e5    | 6         | 3.64%   |
| 0x406e3    | 6         | 3.64%   |
| 0x08108109 | 6         | 3.64%   |
| 0x906ea    | 5         | 3.03%   |
| 0x806e9    | 5         | 3.03%   |
| 0x08600106 | 5         | 3.03%   |
| 0xa0652    | 4         | 2.42%   |
| 0x806eb    | 4         | 2.42%   |
| 0x506c9    | 4         | 2.42%   |
| 0x40651    | 3         | 1.82%   |
| 0x706a8    | 2         | 1.21%   |
| 0x6d8      | 2         | 1.21%   |
| 0x306c3    | 2         | 1.21%   |
| 0x20655    | 2         | 1.21%   |
| 0x1067a    | 2         | 1.21%   |
| 0x906e9    | 1         | 0.61%   |
| 0x6f6      | 1         | 0.61%   |
| 0x695      | 1         | 0.61%   |
| 0x406c4    | 1         | 0.61%   |
| 0x406c3    | 1         | 0.61%   |
| 0x40661    | 1         | 0.61%   |
| 0x106c2    | 1         | 0.61%   |
| 0x10661    | 1         | 0.61%   |
| 0x0a50000b | 1         | 0.61%   |
| 0x08608103 | 1         | 0.61%   |
| 0x08108102 | 1         | 0.61%   |
| 0x0810100b | 1         | 0.61%   |
| 0x06006705 | 1         | 0.61%   |
| 0x0600611a | 1         | 0.61%   |
| 0x05000029 | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 37        | 22.7%   |
| IvyBridge     | 21        | 12.88%  |
| TigerLake     | 13        | 7.98%   |
| SandyBridge   | 11        | 6.75%   |
| Skylake       | 10        | 6.13%   |
| Zen+          | 9         | 5.52%   |
| Haswell       | 9         | 5.52%   |
| Broadwell     | 8         | 4.91%   |
| Zen 2         | 7         | 4.29%   |
| IceLake       | 6         | 3.68%   |
| CometLake     | 5         | 3.07%   |
| Goldmont      | 4         | 2.45%   |
| Westmere      | 3         | 1.84%   |
| Penryn        | 3         | 1.84%   |
| P6            | 3         | 1.84%   |
| Core          | 3         | 1.84%   |
| Silvermont    | 2         | 1.23%   |
| Goldmont plus | 2         | 1.23%   |
| Excavator     | 2         | 1.23%   |
| Zen 3         | 1         | 0.61%   |
| Zen           | 1         | 0.61%   |
| Bonnell       | 1         | 0.61%   |
| Bobcat        | 1         | 0.61%   |
| Unknown       | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 67.16%  |
| Nvidia | 34        | 16.67%  |
| AMD    | 33        | 16.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 9.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 5.71%   |
| Intel UHD Graphics 620                                                                   | 11        | 5.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 5.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.29%   |
| AMD Picasso                                                                              | 9         | 4.29%   |
| Intel HD Graphics 5500                                                                   | 8         | 3.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.33%   |
| AMD Renoir                                                                               | 7         | 3.33%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.86%   |
| Intel HD Graphics 620                                                                    | 5         | 2.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 2.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.38%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.43%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 1.43%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 1.43%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.95%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.95%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.95%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.95%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.95%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.48%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.48%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia GP104GLM [Quadro P3200 Mobile]                                                    | 1         | 0.48%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.48%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.48%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.48%   |
| Nvidia GK107M [GeForce GT 640M LE]                                                       | 1         | 0.48%   |
| Nvidia GK107M [GeForce 810M]                                                             | 1         | 0.48%   |
| Nvidia GF119M [Quadro NVS 4200M]                                                         | 1         | 0.48%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 0.48%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.48%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 0.48%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.48%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 1         | 0.48%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.48%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 1         | 0.48%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.48%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 58.79%  |
| Intel + Nvidia | 33        | 20%     |
| 1 x AMD        | 23        | 13.94%  |
| Intel + AMD    | 7         | 4.24%   |
| 2 x AMD        | 2         | 1.21%   |
| Other          | 1         | 0.61%   |
| 1 x Nvidia     | 1         | 0.61%   |
| AMD + Nvidia   | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Notebooks | Percent |
|---------|-----------|---------|
| Free    | 162       | 98.78%  |
| Unknown | 2         | 1.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 79.52%  |
| 0.51-1.0   | 11        | 6.63%   |
| 0.01-0.5   | 11        | 6.63%   |
| 1.01-2.0   | 9         | 5.42%   |
| 3.01-4.0   | 2         | 1.2%    |
| 5.01-6.0   | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 44        | 23.53%  |
| Chimei Innolux       | 32        | 17.11%  |
| BOE                  | 27        | 14.44%  |
| LG Display           | 26        | 13.9%   |
| Samsung Electronics  | 13        | 6.95%   |
| Sharp                | 8         | 4.28%   |
| Dell                 | 7         | 3.74%   |
| Lenovo               | 4         | 2.14%   |
| Hewlett-Packard      | 3         | 1.6%    |
| BenQ                 | 3         | 1.6%    |
| Apple                | 3         | 1.6%    |
| Ancor Communications | 3         | 1.6%    |
| Philips              | 2         | 1.07%   |
| CPT                  | 2         | 1.07%   |
| ___                  | 1         | 0.53%   |
| Unknown              | 1         | 0.53%   |
| PANDA                | 1         | 0.53%   |
| NCS                  | 1         | 0.53%   |
| JXG                  | 1         | 0.53%   |
| JRY                  | 1         | 0.53%   |
| HannStar             | 1         | 0.53%   |
| Goldstar             | 1         | 0.53%   |
| CSO                  | 1         | 0.53%   |
| AOC                  | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 2.12%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 1.59%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 1.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 1.59%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 1.59%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 1.06%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 1.06%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 1.06%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch          | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 1.06%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.53%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.53%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.53%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.53%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                | 1         | 0.53%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 1         | 0.53%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 1         | 0.53%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch    | 1         | 0.53%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch      | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 340x190mm 15.3-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch | 1         | 0.53%   |
| Samsung Electronics LC32G7xT SAM705A 2560x1440 698x393mm 31.5-inch     | 1         | 0.53%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch    | 1         | 0.53%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.53%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                     | 1         | 0.53%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                | 1         | 0.53%   |
| NCS LCD Monitor NCS2275 1920x1080 256x192mm 12.6-inch                  | 1         | 0.53%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD7001 1366x768 344x194mm 15.5-inch            | 1         | 0.53%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD0543 2560x1440 310x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD04F9 1920x1080 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD04A7 1920x1080 340x190mm 15.3-inch           | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 46.41%  |
| 1366x768 (WXGA)    | 46        | 25.41%  |
| 1600x900 (HD+)     | 13        | 7.18%   |
| 3840x2160 (4K)     | 7         | 3.87%   |
| 1920x1200 (WUXGA)  | 6         | 3.31%   |
| 2560x1440 (QHD)    | 5         | 2.76%   |
| 1280x800 (WXGA)    | 5         | 2.76%   |
| 1440x900 (WXGA+)   | 3         | 1.66%   |
| 1280x1024 (SXGA)   | 3         | 1.66%   |
| 1680x1050 (WSXGA+) | 2         | 1.1%    |
| 3840x2400          | 1         | 0.55%   |
| 3440x1440          | 1         | 0.55%   |
| 2880x1800          | 1         | 0.55%   |
| 2560x1600          | 1         | 0.55%   |
| 1792x768           | 1         | 0.55%   |
| 1024x768 (XGA)     | 1         | 0.55%   |
| 1024x600           | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 58        | 30.85%  |
| 13     | 44        | 23.4%   |
| 14     | 28        | 14.89%  |
| 17     | 10        | 5.32%   |
| 12     | 10        | 5.32%   |
| 24     | 8         | 4.26%   |
| 21     | 6         | 3.19%   |
| 11     | 6         | 3.19%   |
| 23     | 5         | 2.66%   |
| 19     | 3         | 1.6%    |
| 72     | 1         | 0.53%   |
| 47     | 1         | 0.53%   |
| 40     | 1         | 0.53%   |
| 34     | 1         | 0.53%   |
| 33     | 1         | 0.53%   |
| 31     | 1         | 0.53%   |
| 27     | 1         | 0.53%   |
| 25     | 1         | 0.53%   |
| 18     | 1         | 0.53%   |
| 10     | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 114       | 60.96%  |
| 201-300     | 34        | 18.18%  |
| 501-600     | 13        | 6.95%   |
| 401-500     | 10        | 5.35%   |
| 351-400     | 9         | 4.81%   |
| 701-800     | 2         | 1.07%   |
| 601-700     | 2         | 1.07%   |
| 801-900     | 1         | 0.53%   |
| 1501-2000   | 1         | 0.53%   |
| 1001-1500   | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 144       | 84.71%  |
| 16/10 | 16        | 9.41%   |
| 5/4   | 3         | 1.76%   |
| 3/2   | 3         | 1.76%   |
| 4/3   | 2         | 1.18%   |
| 21/9  | 2         | 1.18%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 30.85%  |
| 81-90          | 56        | 29.79%  |
| 71-80          | 17        | 9.04%   |
| 201-250        | 14        | 7.45%   |
| 61-70          | 9         | 4.79%   |
| 121-130        | 8         | 4.26%   |
| 51-60          | 6         | 3.19%   |
| 151-200        | 5         | 2.66%   |
| 251-300        | 4         | 2.13%   |
| 351-500        | 3         | 1.6%    |
| 141-150        | 3         | 1.6%    |
| 501-1000       | 2         | 1.06%   |
| More than 1000 | 1         | 0.53%   |
| 41-50          | 1         | 0.53%   |
| 301-350        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 97        | 52.72%  |
| 101-120       | 42        | 22.83%  |
| 51-100        | 25        | 13.59%  |
| 161-240       | 13        | 7.07%   |
| More than 240 | 5         | 2.72%   |
| 1-50          | 2         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 133       | 81.1%   |
| 2     | 27        | 16.46%  |
| 3     | 2         | 1.22%   |
| 0     | 2         | 1.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 106       | 43.62%  |
| Realtek Semiconductor             | 75        | 30.86%  |
| Qualcomm Atheros                  | 32        | 13.17%  |
| Broadcom                          | 7         | 2.88%   |
| Marvell Technology Group          | 3         | 1.23%   |
| Broadcom Limited                  | 3         | 1.23%   |
| Ralink                            | 2         | 0.82%   |
| Ericsson Business Mobile Networks | 2         | 0.82%   |
| Dell                              | 2         | 0.82%   |
| Cypress Semiconductor             | 2         | 0.82%   |
| Xiaomi                            | 1         | 0.41%   |
| Qualcomm                          | 1         | 0.41%   |
| Microchip Technology              | 1         | 0.41%   |
| Huawei Technologies               | 1         | 0.41%   |
| Hewlett-Packard                   | 1         | 0.41%   |
| Fibocom                           | 1         | 0.41%   |
| Edimax Technology                 | 1         | 0.41%   |
| DisplayLink                       | 1         | 0.41%   |
| Attansic Technology               | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 46        | 14.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16        | 5.21%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 4.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 3.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 3.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.93%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.61%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.28%   |
| Intel Wireless 8260                                                     | 7         | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.63%   |
| Intel Wireless 7265                                                     | 5         | 1.63%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.3%    |
| Intel Wireless 7260                                                     | 4         | 1.3%    |
| Intel Wireless 3160                                                     | 4         | 1.3%    |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.98%   |
| Intel Wireless 3165                                                     | 3         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.98%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.65%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.65%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.65%   |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.65%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.65%   |
| Cypress K38231_03                                                       | 2         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.33%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.33%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 1         | 0.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.33%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.33%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 1         | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                              | 1         | 0.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 104       | 63.03%  |
| Qualcomm Atheros      | 27        | 16.36%  |
| Realtek Semiconductor | 22        | 13.33%  |
| Broadcom              | 5         | 3.03%   |
| Ralink                | 2         | 1.21%   |
| Broadcom Limited      | 2         | 1.21%   |
| Qualcomm              | 1         | 0.61%   |
| Fibocom               | 1         | 0.61%   |
| Edimax Technology     | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 7.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 6.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 5.42%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.82%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.22%   |
| Intel Wireless 8260                                                     | 7         | 4.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.01%   |
| Intel Wireless 7265                                                     | 5         | 3.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 2.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.41%   |
| Intel Wireless 7260                                                     | 4         | 2.41%   |
| Intel Wireless 3160                                                     | 4         | 2.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 2.41%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 2.41%   |
| Intel Centrino Ultimate-N 6300                                          | 4         | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.81%   |
| Intel Wireless 3165                                                     | 3         | 1.81%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.2%    |
| Intel Wireless-AC 9260                                                  | 2         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.6%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.6%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 1         | 0.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.6%    |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.6%    |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]             | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.6%    |
| Intel Wireless Gigabit 17265                                            | 1         | 0.6%    |
| Intel WiFi Link 5100                                                    | 1         | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.6%    |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                         | 1         | 0.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.6%    |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.6%    |
| Intel Centrino Wireless-N 130                                           | 1         | 0.6%    |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.6%    |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.6%    |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 0.6%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.6%    |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.6%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.6%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 1         | 0.6%    |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 63        | 47.01%  |
| Intel                    | 45        | 33.58%  |
| Qualcomm Atheros         | 9         | 6.72%   |
| Broadcom                 | 5         | 3.73%   |
| Marvell Technology Group | 3         | 2.24%   |
| Cypress Semiconductor    | 2         | 1.49%   |
| Broadcom Limited         | 2         | 1.49%   |
| Xiaomi                   | 1         | 0.75%   |
| Microchip Technology     | 1         | 0.75%   |
| Huawei Technologies      | 1         | 0.75%   |
| DisplayLink              | 1         | 0.75%   |
| Attansic Technology      | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 34.07%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 11.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 8.15%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.96%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.48%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.48%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.48%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.48%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.48%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.48%   |
| Cypress K38231_03                                                 | 2         | 1.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.74%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.74%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.74%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.74%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.74%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.74%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.74%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.74%   |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 0.74%   |
| Huawei E353/E3131                                                 | 1         | 0.74%   |
| DisplayLink LAPDOCK                                               | 1         | 0.74%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.74%   |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 0.74%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.74%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 54.61%  |
| Ethernet | 127       | 43.34%  |
| Modem    | 6         | 2.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 153       | 63.75%  |
| Ethernet | 86        | 35.83%  |
| Modem    | 1         | 0.42%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 69.94%  |
| 1     | 44        | 26.99%  |
| 3     | 5         | 3.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 125       | 76.22%  |
| Yes  | 39        | 23.78%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 56.82%  |
| Realtek Semiconductor           | 13        | 9.85%   |
| Qualcomm Atheros Communications | 10        | 7.58%   |
| Broadcom                        | 8         | 6.06%   |
| Lite-On Technology              | 6         | 4.55%   |
| Realtek                         | 3         | 2.27%   |
| IMC Networks                    | 3         | 2.27%   |
| Foxconn / Hon Hai               | 3         | 2.27%   |
| Apple                           | 3         | 2.27%   |
| Toshiba                         | 2         | 1.52%   |
| Dell                            | 2         | 1.52%   |
| Cambridge Silicon Radio         | 2         | 1.52%   |
| Ralink                          | 1         | 0.76%   |
| Hewlett-Packard                 | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 28        | 21.21%  |
| Intel Bluetooth Device                              | 16        | 12.12%  |
| Intel AX200 Bluetooth                               | 13        | 9.85%   |
| Realtek Bluetooth Radio                             | 10        | 7.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 7.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 5.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 3.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 3.03%   |
| Realtek Bluetooth Radio                             | 3         | 2.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.27%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 2.27%   |
| Toshiba Bluetooth Device                            | 2         | 1.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.52%   |
| Lite-On Bluetooth Device                            | 2         | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.52%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.52%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.52%   |
| Apple Bluetooth Host Controller                     | 2         | 1.52%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.76%   |
| Realtek CSR BS8510                                  | 1         | 0.76%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.76%   |
| IMC Networks Bluetooth Device                       | 1         | 0.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.76%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.76%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.76%   |
| Dell BCM20702A0                                     | 1         | 0.76%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.76%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 141       | 71.57%  |
| AMD                    | 25        | 12.69%  |
| Nvidia                 | 17        | 8.63%   |
| Generalplus Technology | 3         | 1.52%   |
| C-Media Electronics    | 3         | 1.52%   |
| Texas Instruments      | 2         | 1.02%   |
| Logitech               | 2         | 1.02%   |
| Razer USA              | 1         | 0.51%   |
| Plantronics            | 1         | 0.51%   |
| GN Netcom              | 1         | 0.51%   |
| Creative Technology    | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 11.02%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 9.75%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 19        | 8.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 5.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 4.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 3.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 3.39%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 3.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 2.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 2.12%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.12%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.27%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.27%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.85%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.85%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.85%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.42%   |
| Plantronics DA40                                                                                  | 1         | 0.42%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.42%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Nvidia Audio device                                                                               | 1         | 0.42%   |
| Logitech USB Headset                                                                              | 1         | 0.42%   |
| Logitech Headset H340                                                                             | 1         | 0.42%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.42%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.42%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 1         | 0.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.42%   |
| GN Netcom Jabra Link 380                                                                          | 1         | 0.42%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1         | 0.42%   |
| C-Media Electronics CM102-A+/102S+ Audio Controller                                               | 1         | 0.42%   |
| C-Media Electronics Blue Snowball                                                                 | 1         | 0.42%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.42%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.42%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.42%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.42%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.42%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 48        | 26.23%  |
| Samsung Electronics | 44        | 24.04%  |
| Micron Technology   | 20        | 10.93%  |
| Kingston            | 14        | 7.65%   |
| Crucial             | 13        | 7.1%    |
| Unknown             | 12        | 6.56%   |
| A-DATA Technology   | 9         | 4.92%   |
| Ramaxel Technology  | 5         | 2.73%   |
| Corsair             | 4         | 2.19%   |
| Elpida              | 3         | 1.64%   |
| Team                | 2         | 1.09%   |
| Nanya Technology    | 2         | 1.09%   |
| Unknown (ABCD)      | 1         | 0.55%   |
| Unifosa             | 1         | 0.55%   |
| SMART Brazil        | 1         | 0.55%   |
| Smart               | 1         | 0.55%   |
| PNY                 | 1         | 0.55%   |
| Kllisre             | 1         | 0.55%   |
| GOODRAM             | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 2.08%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.56%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 1.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.56%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 1.56%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 1.04%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 1.04%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 1.04%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.04%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.04%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.04%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.04%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.04%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.04%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 1.04%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.04%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.04%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.04%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.04%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 2         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.04%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.04%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.04%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                           | 1         | 0.52%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                           | 1         | 0.52%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                           | 1         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.52%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.52%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.52%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s             | 1         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s   | 1         | 0.52%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 0.52%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.52%   |
| Team RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.52%   |
| Smart RAM SH5641G8FJ8NWRNSQR 8GB SODIMM DDR3 1600MT/s            | 1         | 0.52%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.52%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1333MT/s                     | 1         | 0.52%   |
| SK Hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.52%   |
| SK Hynix RAM Module 2GB Row Of Chips DDR3 1600MT/s               | 1         | 0.52%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.52%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.52%   |
| SK Hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.52%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.52%   |
| SK Hynix RAM HMT112S6TFR8C-H9 1GB SODIMM DDR3 1333MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.52%   |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 76        | 50.67%  |
| DDR3   | 52        | 34.67%  |
| DDR2   | 8         | 5.33%   |
| LPDDR4 | 6         | 4%      |
| LPDDR3 | 6         | 4%      |
| SDRAM  | 2         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 134       | 89.93%  |
| Row Of Chips | 15        | 10.07%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 59        | 35.76%  |
| 8192  | 56        | 33.94%  |
| 16384 | 21        | 12.73%  |
| 2048  | 14        | 8.48%   |
| 1024  | 7         | 4.24%   |
| 32768 | 6         | 3.64%   |
| 512   | 2         | 1.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 40        | 24.39%  |
| 1600    | 40        | 24.39%  |
| 3200    | 22        | 13.41%  |
| 2400    | 16        | 9.76%   |
| 2133    | 13        | 7.93%   |
| 1333    | 10        | 6.1%    |
| 1334    | 9         | 5.49%   |
| 4267    | 3         | 1.83%   |
| 667     | 2         | 1.22%   |
| 533     | 2         | 1.22%   |
| 400     | 2         | 1.22%   |
| Unknown | 2         | 1.22%   |
| 4266    | 1         | 0.61%   |
| 4199    | 1         | 0.61%   |
| 975     | 1         | 0.61%   |

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
| Chicony Electronics                    | 30        | 21.13%  |
| IMC Networks                           | 28        | 19.72%  |
| Acer                                   | 17        | 11.97%  |
| Microdia                               | 12        | 8.45%   |
| Realtek Semiconductor                  | 11        | 7.75%   |
| Lite-On Technology                     | 9         | 6.34%   |
| Sunplus Innovation Technology          | 7         | 4.93%   |
| Quanta                                 | 7         | 4.93%   |
| Suyin                                  | 4         | 2.82%   |
| Logitech                               | 3         | 2.11%   |
| Apple                                  | 3         | 2.11%   |
| Syntek                                 | 2         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.41%   |
| Pixart Imaging                         | 1         | 0.7%    |
| Lenovo                                 | 1         | 0.7%    |
| eMPIA Technology                       | 1         | 0.7%    |
| DJKCVA19IE3NE8                         | 1         | 0.7%    |
| ALi                                    | 1         | 0.7%    |
| Alcor Micro                            | 1         | 0.7%    |
| A4Tech                                 | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera           | 10        | 7.04%   |
| Chicony integrated camera                | 9         | 6.34%   |
| Microdia Integrated_Webcam_HD            | 7         | 4.93%   |
| IMC Networks USB2.0 HD UVC WebCam        | 7         | 4.93%   |
| Realtek Integrated_Webcam_HD             | 6         | 4.23%   |
| Acer Integrated Camera                   | 6         | 4.23%   |
| Chicony HP HD Camera                     | 5         | 3.52%   |
| Acer SunplusIT Integrated Camera         | 5         | 3.52%   |
| Lite-On Integrated Camera                | 4         | 2.82%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 3         | 2.11%   |
| Chicony HD WebCam                        | 3         | 2.11%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.41%   |
| Quanta HD Webcam                         | 2         | 1.41%   |
| Microdia Integrated Webcam HD            | 2         | 1.41%   |
| Logitech C505 HD Webcam                  | 2         | 1.41%   |
| Lite-On HP HD Camera                     | 2         | 1.41%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 2         | 1.41%   |
| IMC Networks ov9734_azurewave_camera     | 2         | 1.41%   |
| IMC Networks Lenovo EasyCamera           | 2         | 1.41%   |
| Chicony Lenovo EasyCamera                | 2         | 1.41%   |
| Chicony HP HD Webcam                     | 2         | 1.41%   |
| Apple FaceTime HD Camera                 | 2         | 1.41%   |
| Acer EasyCamera                          | 2         | 1.41%   |
| Syntek USB 2.0 UVC PC Camera             | 1         | 0.7%    |
| Syntek Lenovo EasyCamera                 | 1         | 0.7%    |
| Suyin Laptop_Integrated_Webcam_HD        | 1         | 0.7%    |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 0.7%    |
| Suyin HP TrueVision Full HD              | 1         | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_HD      | 1         | 0.7%    |
| Sunplus Laptop_Integrated_Webcam_FHD     | 1         | 0.7%    |
| Sunplus Laptop Integrated Webcam FHD     | 1         | 0.7%    |
| Sunplus Dell E5570 integrated webcam     | 1         | 0.7%    |
| Sunplus 1.3M HD WebCam                   | 1         | 0.7%    |
| Realtek Lenovo EasyCamera                | 1         | 0.7%    |
| Realtek Integrated Webcam                | 1         | 0.7%    |
| Realtek HD WebCam                        | 1         | 0.7%    |
| Realtek EasyCamera                       | 1         | 0.7%    |
| Realtek Acer 640 x 480 laptop camera     | 1         | 0.7%    |
| Quanta VGA WebCam                        | 1         | 0.7%    |
| Quanta ov9734_techfront_camera           | 1         | 0.7%    |
| Quanta HP Webcam                         | 1         | 0.7%    |
| Quanta HP TrueVision HD Camera           | 1         | 0.7%    |
| Quanta HP HD Camera                      | 1         | 0.7%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_E4HD   | 1         | 0.7%    |
| Microdia Laptop_Integrated_Webcam_2M     | 1         | 0.7%    |
| Microdia 1.3 MPixel Integrated Webcam    | 1         | 0.7%    |
| Logitech Webcam C930e                    | 1         | 0.7%    |
| Lite-On TOSHIBA Web Camera - HD          | 1         | 0.7%    |
| Lite-On HP Webcam                        | 1         | 0.7%    |
| Lite-On HP HD Webcam                     | 1         | 0.7%    |
| Lenovo Integrated Webcam                 | 1         | 0.7%    |
| IMC Networks TOSHIBA Web Camera - HD     | 1         | 0.7%    |
| IMC Networks HP TrueVision HD Camera     | 1         | 0.7%    |
| eMPIA EeePC 701 integrated Webcam        | 1         | 0.7%    |
| DJKCVA19IE3NE8 HP TrueVision HD Camera   | 1         | 0.7%    |
| Chicony USB2.0 HD UVC WebCam             | 1         | 0.7%    |
| Chicony USB2.0 Camera                    | 1         | 0.7%    |
| Chicony ThinkPad T490 Webcam             | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 38.24%  |
| Shenzhen Goodix Technology | 9         | 26.47%  |
| Validity Sensors           | 6         | 17.65%  |
| Elan Microelectronics      | 3         | 8.82%   |
| Upek                       | 2         | 5.88%   |
| AuthenTec                  | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 17.65%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 14.71%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 11.76%  |
| Shenzhen Goodix FingerPrint                                                | 4         | 11.76%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 8.82%   |
| Elan ELAN:Fingerprint                                                      | 3         | 8.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 5.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.94%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 33.33%  |
| Broadcom    | 6         | 28.57%  |
| Lenovo      | 4         | 19.05%  |
| Upek        | 3         | 14.29%  |
| O2 Micro    | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 33.33%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 19.05%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 14.29%  |
| Broadcom 5880                                                                | 2         | 9.52%   |
| Broadcom 58200                                                               | 2         | 9.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 107       | 64.46%  |
| 1     | 38        | 22.89%  |
| 2     | 19        | 11.45%  |
| 4     | 1         | 0.6%    |
| 3     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 42.5%   |
| Chipcard                 | 17        | 21.25%  |
| Graphics card            | 12        | 15%     |
| Net/wireless             | 4         | 5%      |
| Multimedia controller    | 4         | 5%      |
| Communication controller | 3         | 3.75%   |
| Storage                  | 2         | 2.5%    |
| Modem                    | 1         | 1.25%   |
| Firewire controller      | 1         | 1.25%   |
| Card reader              | 1         | 1.25%   |
| Bluetooth                | 1         | 1.25%   |

