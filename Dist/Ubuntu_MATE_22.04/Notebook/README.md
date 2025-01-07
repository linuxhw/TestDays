Ubuntu MATE 22.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 507

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad U510 4941           | [78a774dc27](https://linux-hardware.org/?probe=78a774dc27) | Jan 01, 2025 |
| HP            | Pavilion dv4                | [e09129add9](https://linux-hardware.org/?probe=e09129add9) | Dec 30, 2024 |
| Lenovo        | ThinkPad T430 23498F0       | [4b2306ff9f](https://linux-hardware.org/?probe=4b2306ff9f) | Dec 19, 2024 |
| Notebook      | NJx0MU                      | [20e57b7eca](https://linux-hardware.org/?probe=20e57b7eca) | Nov 24, 2024 |
| Notebook      | NJx0MU                      | [76c5e79d46](https://linux-hardware.org/?probe=76c5e79d46) | Nov 23, 2024 |
| Acer          | Aspire 5050                 | [eac5cc26a2](https://linux-hardware.org/?probe=eac5cc26a2) | Nov 10, 2024 |
| HP            | Notebook                    | [00a772808d](https://linux-hardware.org/?probe=00a772808d) | Oct 23, 2024 |
| Dell          | XPS 13 9310                 | [b8119f542b](https://linux-hardware.org/?probe=b8119f542b) | Oct 18, 2024 |
| Dell          | XPS 13 9310                 | [92736b8de6](https://linux-hardware.org/?probe=92736b8de6) | Oct 18, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0bdda39e37](https://linux-hardware.org/?probe=0bdda39e37) | Oct 16, 2024 |
| Notebook      | NJx0MU                      | [78a5ceba6e](https://linux-hardware.org/?probe=78a5ceba6e) | Oct 12, 2024 |
| Lenovo        | ThinkPad T440p 20AWS4N90... | [367e64b3ed](https://linux-hardware.org/?probe=367e64b3ed) | Oct 12, 2024 |
| Notebook      | NJx0MU                      | [4a7041c67c](https://linux-hardware.org/?probe=4a7041c67c) | Oct 11, 2024 |
| Lenovo        | B51-80 80LM                 | [aa39bd173c](https://linux-hardware.org/?probe=aa39bd173c) | Oct 09, 2024 |
| Dell          | XPS L322X                   | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| ASUSTek       | X550LN                      | [61239b6939](https://linux-hardware.org/?probe=61239b6939) | Oct 03, 2024 |
| ASUSTek       | X550LN                      | [aa1afeaff4](https://linux-hardware.org/?probe=aa1afeaff4) | Oct 03, 2024 |
| Dell          | Latitude E7440              | [e214523782](https://linux-hardware.org/?probe=e214523782) | Oct 01, 2024 |
| ASUSTek       | UX305FA                     | [cab58b19a5](https://linux-hardware.org/?probe=cab58b19a5) | Sep 27, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | [4422a8ed1b](https://linux-hardware.org/?probe=4422a8ed1b) | Sep 26, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [baed1e9059](https://linux-hardware.org/?probe=baed1e9059) | Sep 17, 2024 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [9146d15a3b](https://linux-hardware.org/?probe=9146d15a3b) | Sep 16, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [0ecccff1eb](https://linux-hardware.org/?probe=0ecccff1eb) | Sep 16, 2024 |
| HP            | ProBook 4710s               | [e6ca3a8cfc](https://linux-hardware.org/?probe=e6ca3a8cfc) | Sep 13, 2024 |
| Lenovo        | ThinkPad P53 20QQS2Q500     | [f59c986142](https://linux-hardware.org/?probe=f59c986142) | Sep 08, 2024 |
| Lenovo        | ThinkPad P53 20QQS2Q500     | [036064fb7d](https://linux-hardware.org/?probe=036064fb7d) | Sep 08, 2024 |
| Notebook      | NJx0MU                      | [759b1d1403](https://linux-hardware.org/?probe=759b1d1403) | Sep 07, 2024 |
| Notebook      | NJx0MU                      | [7582b12cfa](https://linux-hardware.org/?probe=7582b12cfa) | Sep 07, 2024 |
| ASUSTek       | X550LN                      | [ce640045ef](https://linux-hardware.org/?probe=ce640045ef) | Sep 03, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [4c3b6cd503](https://linux-hardware.org/?probe=4c3b6cd503) | Aug 30, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [8c4be8ba0d](https://linux-hardware.org/?probe=8c4be8ba0d) | Aug 27, 2024 |
| Dell          | Latitude 3420               | [f13d050d62](https://linux-hardware.org/?probe=f13d050d62) | Aug 21, 2024 |
| Notebook      | NJx0MU                      | [4fd40665fe](https://linux-hardware.org/?probe=4fd40665fe) | Aug 15, 2024 |
| Notebook      | NJx0MU                      | [752565b32e](https://linux-hardware.org/?probe=752565b32e) | Aug 15, 2024 |
| Notebook      | NJx0MU                      | [72a76100c0](https://linux-hardware.org/?probe=72a76100c0) | Aug 14, 2024 |
| HP            | EliteBook 8570p             | [18231f879f](https://linux-hardware.org/?probe=18231f879f) | Jul 31, 2024 |
| Dell          | XPS L322X                   | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Lenovo        | ThinkPad L512 2597W1R       | [30c12bace2](https://linux-hardware.org/?probe=30c12bace2) | Jul 30, 2024 |
| Dell          | Precision M4800             | [50f7d3e735](https://linux-hardware.org/?probe=50f7d3e735) | Jul 28, 2024 |
| HP            | EliteBook 820 G1            | [fd49810070](https://linux-hardware.org/?probe=fd49810070) | Jul 14, 2024 |
| Medion        | P8610                       | [a39e7058a3](https://linux-hardware.org/?probe=a39e7058a3) | Jul 09, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| Notebook      | NJx0MU                      | [a9ffcc9574](https://linux-hardware.org/?probe=a9ffcc9574) | Jul 07, 2024 |
| Notebook      | NJx0MU                      | [d332637cfe](https://linux-hardware.org/?probe=d332637cfe) | Jul 07, 2024 |
| HP            | Pavilion dv4                | [4d8fa0dcd3](https://linux-hardware.org/?probe=4d8fa0dcd3) | Jun 23, 2024 |
| Dell          | XPS L322X                   | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [a448de0f44](https://linux-hardware.org/?probe=a448de0f44) | Jun 15, 2024 |
| Dell          | XPS 15 9560                 | [35684afb98](https://linux-hardware.org/?probe=35684afb98) | May 28, 2024 |
| HP            | 355 G2                      | [3a458e83e5](https://linux-hardware.org/?probe=3a458e83e5) | May 26, 2024 |
| HP            | 355 G2                      | [8b28adff93](https://linux-hardware.org/?probe=8b28adff93) | May 26, 2024 |
| Acer          | Aspire A515-54              | [fbfb9ee390](https://linux-hardware.org/?probe=fbfb9ee390) | May 24, 2024 |
| Acer          | Aspire 5742G                | [9bc61751b1](https://linux-hardware.org/?probe=9bc61751b1) | May 24, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | [5618803794](https://linux-hardware.org/?probe=5618803794) | May 21, 2024 |
| Compumax C... | ONIX-CEL-0001               | [36eb3289fa](https://linux-hardware.org/?probe=36eb3289fa) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | [a667660a0c](https://linux-hardware.org/?probe=a667660a0c) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | [146a53575b](https://linux-hardware.org/?probe=146a53575b) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1d905f7200](https://linux-hardware.org/?probe=1d905f7200) | May 15, 2024 |
| Notebook      | NJx0MU                      | [2d829398cc](https://linux-hardware.org/?probe=2d829398cc) | May 11, 2024 |
| Notebook      | NJx0MU                      | [ee086eec1f](https://linux-hardware.org/?probe=ee086eec1f) | May 09, 2024 |
| Intel         | STCK1A32WFC H67490-302      | [51c75f3848](https://linux-hardware.org/?probe=51c75f3848) | May 08, 2024 |
| ASUSTek       | X550LN                      | [b139a58ea9](https://linux-hardware.org/?probe=b139a58ea9) | May 07, 2024 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [1680c3ad15](https://linux-hardware.org/?probe=1680c3ad15) | Apr 27, 2024 |
| Lenovo        | G70-70 80HW                 | [73f307b60b](https://linux-hardware.org/?probe=73f307b60b) | Apr 20, 2024 |
| AMI           | Unknown                     | [8330483e6e](https://linux-hardware.org/?probe=8330483e6e) | Apr 20, 2024 |
| Lenovo        | ThinkPad L470 20J4002FMX    | [d7337f7684](https://linux-hardware.org/?probe=d7337f7684) | Apr 17, 2024 |
| Dell          | Latitude 5410               | [700b37dcf0](https://linux-hardware.org/?probe=700b37dcf0) | Apr 16, 2024 |
| HP            | Pavilion 13 x2 PC           | [684e30a2e3](https://linux-hardware.org/?probe=684e30a2e3) | Apr 13, 2024 |
| HP            | Pavilion 13 x2 PC           | [60d693276a](https://linux-hardware.org/?probe=60d693276a) | Apr 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [b6a43ddde6](https://linux-hardware.org/?probe=b6a43ddde6) | Apr 11, 2024 |
| HP            | EliteBook 2760p             | [37781c3e84](https://linux-hardware.org/?probe=37781c3e84) | Apr 07, 2024 |
| Notebook      | NJx0MU                      | [e8546100eb](https://linux-hardware.org/?probe=e8546100eb) | Apr 07, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a130a64c11](https://linux-hardware.org/?probe=a130a64c11) | Apr 07, 2024 |
| AMI           | Unknown                     | [e52668ee27](https://linux-hardware.org/?probe=e52668ee27) | Apr 05, 2024 |
| Notebook      | NJx0MU                      | [4f2bc03aca](https://linux-hardware.org/?probe=4f2bc03aca) | Apr 04, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | [3709076728](https://linux-hardware.org/?probe=3709076728) | Mar 30, 2024 |
| Toshiba       | Satellite C70D-A            | [8489c1e38c](https://linux-hardware.org/?probe=8489c1e38c) | Mar 28, 2024 |
| Dell          | Latitude 3410               | [3aee33bb58](https://linux-hardware.org/?probe=3aee33bb58) | Mar 27, 2024 |
| Monster       | ABRA A5 V17.4               | [153af2c8d9](https://linux-hardware.org/?probe=153af2c8d9) | Mar 23, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Toshiba       | PORTEGE R500                | [33c598fc6e](https://linux-hardware.org/?probe=33c598fc6e) | Mar 21, 2024 |
| HP            | EliteBook 820 G3            | [5d5d06eab9](https://linux-hardware.org/?probe=5d5d06eab9) | Mar 20, 2024 |
| Lenovo        | Z710 20250                  | [60c82a772a](https://linux-hardware.org/?probe=60c82a772a) | Mar 17, 2024 |
| Sony          | SVE1712T1EB                 | [a01a793d3b](https://linux-hardware.org/?probe=a01a793d3b) | Mar 12, 2024 |
| Sony          | SVE1712T1EB                 | [2bc7cadf31](https://linux-hardware.org/?probe=2bc7cadf31) | Mar 12, 2024 |
| Dell          | Latitude 3410               | [5ea9fa7a7c](https://linux-hardware.org/?probe=5ea9fa7a7c) | Mar 07, 2024 |
| Dell          | Inspiron 1520               | [6cffe59389](https://linux-hardware.org/?probe=6cffe59389) | Mar 02, 2024 |
| HP            | Notebook                    | [9b7a8a0478](https://linux-hardware.org/?probe=9b7a8a0478) | Feb 29, 2024 |
| Dell          | Precision 5550              | [59677e206f](https://linux-hardware.org/?probe=59677e206f) | Feb 27, 2024 |
| Positivo B... | VJFE59F11X-B0411H           | [f193f8bd36](https://linux-hardware.org/?probe=f193f8bd36) | Feb 23, 2024 |
| Notebook      | NJx0MU                      | [645bf6be84](https://linux-hardware.org/?probe=645bf6be84) | Feb 20, 2024 |
| Dell          | Latitude 5590               | [e25be34559](https://linux-hardware.org/?probe=e25be34559) | Feb 19, 2024 |
| Notebook      | NJx0MU                      | [3c40fa1a9f](https://linux-hardware.org/?probe=3c40fa1a9f) | Feb 19, 2024 |
| Acer          | Extensa 215-22              | [a7faa9b520](https://linux-hardware.org/?probe=a7faa9b520) | Feb 14, 2024 |
| Dell          | Inspiron 1520               | [953b2c870f](https://linux-hardware.org/?probe=953b2c870f) | Feb 11, 2024 |
| Toshiba       | Satellite C55-B             | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
| Dell          | Precision 7520              | [3ba06d2c0d](https://linux-hardware.org/?probe=3ba06d2c0d) | Feb 08, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [1d5c5c6bdc](https://linux-hardware.org/?probe=1d5c5c6bdc) | Feb 07, 2024 |
| Notebook      | NJx0MU                      | [dbe298a22e](https://linux-hardware.org/?probe=dbe298a22e) | Feb 03, 2024 |
| Notebook      | NJx0MU                      | [6259b53b1c](https://linux-hardware.org/?probe=6259b53b1c) | Feb 02, 2024 |
| Notebook      | NJx0MU                      | [7def8ee544](https://linux-hardware.org/?probe=7def8ee544) | Feb 01, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c62ec1a167](https://linux-hardware.org/?probe=c62ec1a167) | Jan 31, 2024 |
| Notebook      | NJx0MU                      | [6f8f587ec5](https://linux-hardware.org/?probe=6f8f587ec5) | Jan 30, 2024 |
| Apple         | MacBookPro14,1              | [bdf8f178f4](https://linux-hardware.org/?probe=bdf8f178f4) | Jan 18, 2024 |
| Dell          | Latitude E5550              | [0755281d4f](https://linux-hardware.org/?probe=0755281d4f) | Jan 16, 2024 |
| Dell          | Vostro 7620                 | [433547fc16](https://linux-hardware.org/?probe=433547fc16) | Jan 11, 2024 |
| Notebook      | NJx0MU                      | [c038b7f7e4](https://linux-hardware.org/?probe=c038b7f7e4) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | [cdb97873fa](https://linux-hardware.org/?probe=cdb97873fa) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | [f9d4fa4d55](https://linux-hardware.org/?probe=f9d4fa4d55) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | [c7f2d68d77](https://linux-hardware.org/?probe=c7f2d68d77) | Dec 30, 2023 |
| HP            | ProBook 440 G7              | [10d9fd3230](https://linux-hardware.org/?probe=10d9fd3230) | Dec 30, 2023 |
| Medion        | S6445 MD61281               | [b7db1404b6](https://linux-hardware.org/?probe=b7db1404b6) | Dec 26, 2023 |
| Notebook      | NJx0MU                      | [87cef435db](https://linux-hardware.org/?probe=87cef435db) | Dec 24, 2023 |
| Clevo         | W760/M770CU                 | [c64bdf2349](https://linux-hardware.org/?probe=c64bdf2349) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | [b57fdd9854](https://linux-hardware.org/?probe=b57fdd9854) | Dec 24, 2023 |
| GPU Compan... | GWTN116-3                   | [89366f9a48](https://linux-hardware.org/?probe=89366f9a48) | Dec 23, 2023 |
| GPD           | G1621-02                    | [eaf78f9da1](https://linux-hardware.org/?probe=eaf78f9da1) | Dec 22, 2023 |
| MSI           | GF65 Thin 10SDR             | [73408e34a6](https://linux-hardware.org/?probe=73408e34a6) | Dec 21, 2023 |
| HP            | 350 G1                      | [c219133bce](https://linux-hardware.org/?probe=c219133bce) | Dec 20, 2023 |
| Clevo         | W760/M770CU                 | [fdde778b3c](https://linux-hardware.org/?probe=fdde778b3c) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Notebook      | NJx0MU                      | [1446130ae9](https://linux-hardware.org/?probe=1446130ae9) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | [80281cb193](https://linux-hardware.org/?probe=80281cb193) | Dec 17, 2023 |
| HP            | ProBook 650 G1              | [f58535cbfe](https://linux-hardware.org/?probe=f58535cbfe) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| ASUSTek       | X550LN                      | [5f4856fdab](https://linux-hardware.org/?probe=5f4856fdab) | Dec 01, 2023 |
| HP            | ProBook 440 G7              | [bb8295e3fa](https://linux-hardware.org/?probe=bb8295e3fa) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | [0d3ea0a6dc](https://linux-hardware.org/?probe=0d3ea0a6dc) | Nov 30, 2023 |
| HP            | ProBook 440 G2              | [608d264af2](https://linux-hardware.org/?probe=608d264af2) | Nov 27, 2023 |
| HP            | ProBook 440 G2              | [2ecc0c852a](https://linux-hardware.org/?probe=2ecc0c852a) | Nov 27, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [5c0820855b](https://linux-hardware.org/?probe=5c0820855b) | Nov 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a4cda5b12d](https://linux-hardware.org/?probe=a4cda5b12d) | Nov 22, 2023 |
| Notebook      | NJx0MU                      | [96d6ec7f1f](https://linux-hardware.org/?probe=96d6ec7f1f) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | [c0a0353d6f](https://linux-hardware.org/?probe=c0a0353d6f) | Nov 20, 2023 |
| HP            | ProBook 440 G2              | [6a9af286f8](https://linux-hardware.org/?probe=6a9af286f8) | Nov 19, 2023 |
| BANGHO        | 1025                        | [d1d51fc17a](https://linux-hardware.org/?probe=d1d51fc17a) | Nov 15, 2023 |
| Dell          | Precision M4800             | [9a63057a12](https://linux-hardware.org/?probe=9a63057a12) | Nov 13, 2023 |
| BANGHO        | 1025                        | [97b39ed05d](https://linux-hardware.org/?probe=97b39ed05d) | Nov 13, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | [a206fa30d7](https://linux-hardware.org/?probe=a206fa30d7) | Nov 11, 2023 |
| Notebook      | NJx0MU                      | [70cdbefd00](https://linux-hardware.org/?probe=70cdbefd00) | Nov 07, 2023 |
| Notebook      | NJx0MU                      | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [254a87d641](https://linux-hardware.org/?probe=254a87d641) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| Lenovo        | ThinkPad P53 20QN000FIX     | [40de43c266](https://linux-hardware.org/?probe=40de43c266) | Nov 02, 2023 |
| Panasonic     | CF-53SJCZYLM                | [94941374a2](https://linux-hardware.org/?probe=94941374a2) | Oct 30, 2023 |
| VIT           | P1400                       | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| HP            | ProBook 650 G1              | [698c3abcba](https://linux-hardware.org/?probe=698c3abcba) | Oct 27, 2023 |
| Dell          | Latitude 7430               | [e9cfada6a4](https://linux-hardware.org/?probe=e9cfada6a4) | Oct 26, 2023 |
| Acer          | Aspire 5050                 | [2129ab3e24](https://linux-hardware.org/?probe=2129ab3e24) | Oct 26, 2023 |
| Gigabyte      | G5 KC                       | [32743a624c](https://linux-hardware.org/?probe=32743a624c) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | [23d64978d9](https://linux-hardware.org/?probe=23d64978d9) | Oct 24, 2023 |
| Positivo      | C4128G-15                   | [8d9aa2f206](https://linux-hardware.org/?probe=8d9aa2f206) | Oct 23, 2023 |
| Notebook      | NJx0MU                      | [961c369ea4](https://linux-hardware.org/?probe=961c369ea4) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | [f19c18154b](https://linux-hardware.org/?probe=f19c18154b) | Oct 21, 2023 |
| Acer          | Aspire E3-112M              | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [bc4cc061a2](https://linux-hardware.org/?probe=bc4cc061a2) | Oct 18, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| Packard Be... | EasyNote ENTG81BA           | [f25cb1517e](https://linux-hardware.org/?probe=f25cb1517e) | Oct 12, 2023 |
| Clevo         | W240HU/W250HUQ              | [deb84129fb](https://linux-hardware.org/?probe=deb84129fb) | Oct 10, 2023 |
| ASUSTek       | K50ID                       | [2763bfac4e](https://linux-hardware.org/?probe=2763bfac4e) | Oct 07, 2023 |
| Lenovo        | ThinkPad A275 20KCS09T1G    | [1e797cb20f](https://linux-hardware.org/?probe=1e797cb20f) | Oct 07, 2023 |
| Infinix       | INBOOK X2                   | [5d39adb330](https://linux-hardware.org/?probe=5d39adb330) | Oct 05, 2023 |
| Google        | Galtic                      | [cae091837b](https://linux-hardware.org/?probe=cae091837b) | Oct 03, 2023 |
| GPD           | G1621-02                    | [10ca9df59f](https://linux-hardware.org/?probe=10ca9df59f) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [f510af1acf](https://linux-hardware.org/?probe=f510af1acf) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [8db3bb5b34](https://linux-hardware.org/?probe=8db3bb5b34) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| ASUSTek       | X550LN                      | [390c16a341](https://linux-hardware.org/?probe=390c16a341) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | [89d81885ff](https://linux-hardware.org/?probe=89d81885ff) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | [84bba5e5a7](https://linux-hardware.org/?probe=84bba5e5a7) | Sep 24, 2023 |
| Dell          | Latitude E5470              | [f6e9a7233c](https://linux-hardware.org/?probe=f6e9a7233c) | Sep 23, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d00cc6b535](https://linux-hardware.org/?probe=d00cc6b535) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [89cce2b6cb](https://linux-hardware.org/?probe=89cce2b6cb) | Sep 21, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | [c5cda29091](https://linux-hardware.org/?probe=c5cda29091) | Sep 21, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [43e04cf99c](https://linux-hardware.org/?probe=43e04cf99c) | Sep 20, 2023 |
| Acer          | Aspire ES1-531              | [50023a1d3a](https://linux-hardware.org/?probe=50023a1d3a) | Sep 18, 2023 |
| ASUSTek       | N73SM                       | [d4ce8f336d](https://linux-hardware.org/?probe=d4ce8f336d) | Sep 17, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | [22a0210f8f](https://linux-hardware.org/?probe=22a0210f8f) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | [4c56913d07](https://linux-hardware.org/?probe=4c56913d07) | Sep 13, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [55b8608662](https://linux-hardware.org/?probe=55b8608662) | Sep 08, 2023 |
| Notebook      | NJx0MU                      | [4e54155977](https://linux-hardware.org/?probe=4e54155977) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| Notebook      | NJx0MU                      | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| Bluechip C... | TRAVELline TL14W4           | [7959987246](https://linux-hardware.org/?probe=7959987246) | Aug 28, 2023 |
| Kiano         | Elegance 14.2               | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Lenovo        | V145-15AST 81MT             | [36e12540f3](https://linux-hardware.org/?probe=36e12540f3) | Aug 23, 2023 |
| ASUSTek       | X550LN                      | [810d33b380](https://linux-hardware.org/?probe=810d33b380) | Aug 16, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [06316c3471](https://linux-hardware.org/?probe=06316c3471) | Aug 13, 2023 |
| Notebook      | NJx0MU                      | [b97fcb7117](https://linux-hardware.org/?probe=b97fcb7117) | Aug 12, 2023 |
| Dell          | Latitude E7250              | [7418a0dc06](https://linux-hardware.org/?probe=7418a0dc06) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | [6f230d02c1](https://linux-hardware.org/?probe=6f230d02c1) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | [ea4ae0e0f3](https://linux-hardware.org/?probe=ea4ae0e0f3) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | [2db90ee24e](https://linux-hardware.org/?probe=2db90ee24e) | Aug 11, 2023 |
| Lenovo        | ThinkPad T420 4236MBG       | [aaaa17358f](https://linux-hardware.org/?probe=aaaa17358f) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | [8b6b5ff142](https://linux-hardware.org/?probe=8b6b5ff142) | Aug 04, 2023 |
| Acer          | Extensa 5630                | [8b3c2a89a1](https://linux-hardware.org/?probe=8b3c2a89a1) | Aug 04, 2023 |
| Acer          | Extensa 5630                | [ba6669a5e7](https://linux-hardware.org/?probe=ba6669a5e7) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | [bd88b4e8fa](https://linux-hardware.org/?probe=bd88b4e8fa) | Aug 04, 2023 |
| Dell          | Precision 7520              | [b5addbb003](https://linux-hardware.org/?probe=b5addbb003) | Aug 01, 2023 |
| Notebook      | NJx0MU                      | [f720b1a032](https://linux-hardware.org/?probe=f720b1a032) | Jul 26, 2023 |
| Dell          | Studio 1537                 | [803a98f7e6](https://linux-hardware.org/?probe=803a98f7e6) | Jul 25, 2023 |
| Notebook      | NJx0MU                      | [c675a3feab](https://linux-hardware.org/?probe=c675a3feab) | Jul 25, 2023 |
| Dell          | Precision 7520              | [66922483cf](https://linux-hardware.org/?probe=66922483cf) | Jul 24, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a448a20876](https://linux-hardware.org/?probe=a448a20876) | Jul 17, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d5079cefe1](https://linux-hardware.org/?probe=d5079cefe1) | Jul 13, 2023 |
| Notebook      | NJx0MU                      | [cc7487e50f](https://linux-hardware.org/?probe=cc7487e50f) | Jul 09, 2023 |
| Notebook      | NJx0MU                      | [502c216e98](https://linux-hardware.org/?probe=502c216e98) | Jul 08, 2023 |
| Dell          | Latitude 7420               | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| Dell          | Latitude 7420               | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| AZW           | Z85                         | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| HP            | 350 G1                      | [d965c2785d](https://linux-hardware.org/?probe=d965c2785d) | Jul 04, 2023 |
| HP            | 350 G1                      | [bb742c9ffb](https://linux-hardware.org/?probe=bb742c9ffb) | Jul 04, 2023 |
| Notebook      | NJx0MU                      | [700348835b](https://linux-hardware.org/?probe=700348835b) | Jul 04, 2023 |
| Notebook      | NJx0MU                      | [63a0b07325](https://linux-hardware.org/?probe=63a0b07325) | Jul 02, 2023 |
| Notebook      | NJx0MU                      | [6896f4aafb](https://linux-hardware.org/?probe=6896f4aafb) | Jul 01, 2023 |
| Notebook      | NJx0MU                      | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| HP            | Pavilion 17                 | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| Notebook      | NJx0MU                      | [235e541e2d](https://linux-hardware.org/?probe=235e541e2d) | Jun 28, 2023 |
| Acer          | Extensa 2519                | [1a8a4ee11e](https://linux-hardware.org/?probe=1a8a4ee11e) | Jun 27, 2023 |
| Notebook      | NJx0MU                      | [47a0ae93f4](https://linux-hardware.org/?probe=47a0ae93f4) | Jun 25, 2023 |
| Lenovo        | V145-15AST 81MT             | [1fe939429c](https://linux-hardware.org/?probe=1fe939429c) | Jun 24, 2023 |
| ASUSTek       | K53SD                       | [ac006b8cb7](https://linux-hardware.org/?probe=ac006b8cb7) | Jun 18, 2023 |
| HP            | 625 (WT144EA#ABD)           | [352eaf6ce7](https://linux-hardware.org/?probe=352eaf6ce7) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | [673ab1f0a9](https://linux-hardware.org/?probe=673ab1f0a9) | Jun 11, 2023 |
| Notebook      | NJx0MU                      | [c610b3b9fe](https://linux-hardware.org/?probe=c610b3b9fe) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| Notebook      | NJx0MU                      | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Dell          | Latitude E5540              | [d2bde0e098](https://linux-hardware.org/?probe=d2bde0e098) | Jun 04, 2023 |
| Dell          | Latitude E5540              | [f9483c219e](https://linux-hardware.org/?probe=f9483c219e) | Jun 04, 2023 |
| Notebook      | NJx0MU                      | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Notebook      | NJx0MU                      | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Notebook      | NJx0MU                      | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| Sony          | SVF13N2J2ES                 | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Notebook      | NJx0MU                      | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Notebook      | NJx0MU                      | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| HP            | Pavilion dv6                | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Dell          | Latitude E7270              | [c3b39e55f4](https://linux-hardware.org/?probe=c3b39e55f4) | May 17, 2023 |
| Notebook      | NJx0MU                      | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| Notebook      | NJx0MU                      | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Notebook      | NJx0MU                      | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Notebook      | NJx0MU                      | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| Notebook      | NJx0MU                      | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| Dell          | Vostro 14-3468              | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| Notebook      | NJx0MU                      | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Notebook      | NJx0MU                      | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| Notebook      | NJx0MU                      | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Notebook      | NJx0MU                      | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Notebook      | NJx0MU                      | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| Notebook      | NJx0MU                      | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | [554f32b909](https://linux-hardware.org/?probe=554f32b909) | Apr 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| Google        | Chell                       | [64cecf4575](https://linux-hardware.org/?probe=64cecf4575) | Apr 12, 2023 |
| Notebook      | NJx0MU                      | [2bb9767ca7](https://linux-hardware.org/?probe=2bb9767ca7) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | [681be67c93](https://linux-hardware.org/?probe=681be67c93) | Apr 09, 2023 |
| HUAWEI        | NDZ-WXX9                    | [707d59612f](https://linux-hardware.org/?probe=707d59612f) | Apr 05, 2023 |
| HUAWEI        | NDZ-WXX9                    | [058290755b](https://linux-hardware.org/?probe=058290755b) | Apr 05, 2023 |
| Notebook      | NJx0MU                      | [207edc0a25](https://linux-hardware.org/?probe=207edc0a25) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| Notebook      | NJx0MU                      | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| ASUSTek       | X550LN                      | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| Notebook      | NJx0MU                      | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| ASUSTek       | X550LN                      | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| ASUSTek       | K93SV                       | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| Notebook      | NJx0MU                      | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| HP            | Laptop 15s-eq0xxx           | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| HP            | Presario CQ61               | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Notebook      | NJx0MU                      | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| Sony          | VGN-Z21WRN_B                | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Notebook      | NJx0MU                      | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| HP            | Laptop 15s-fq5xxx           | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | [e2cc024607](https://linux-hardware.org/?probe=e2cc024607) | Feb 18, 2023 |
| Sony          | VPCEB2Z1E                   | [5c172121ab](https://linux-hardware.org/?probe=5c172121ab) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Notebook      | NJx0MU                      | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| ASUSTek       | X541UAK                     | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Acer          | Aspire ES1-523              | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Sony          | VPCEH1E1E                   | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | NJx0MU                      | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Notebook      | NJx0MU                      | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Google        | Relm                        | [44fb1d9db1](https://linux-hardware.org/?probe=44fb1d9db1) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| Dell          | Latitude 5410               | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| Notebook      | NJx0MU                      | [e76a4c32dc](https://linux-hardware.org/?probe=e76a4c32dc) | Jan 17, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6S... | [b4629bd83f](https://linux-hardware.org/?probe=b4629bd83f) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | [cdd815de42](https://linux-hardware.org/?probe=cdd815de42) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [ff52c2505f](https://linux-hardware.org/?probe=ff52c2505f) | Jan 13, 2023 |
| HP            | 15                          | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| Notebook      | NJx0MU                      | [03505c402c](https://linux-hardware.org/?probe=03505c402c) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | [7ee7875a97](https://linux-hardware.org/?probe=7ee7875a97) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Notebook      | NJx0MU                      | [efd4eaee02](https://linux-hardware.org/?probe=efd4eaee02) | Jan 07, 2023 |
| Dell          | Inspiron 5520               | [9b4925d88d](https://linux-hardware.org/?probe=9b4925d88d) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | [8b7d2f1a46](https://linux-hardware.org/?probe=8b7d2f1a46) | Jan 07, 2023 |
| Notebook      | NJx0MU                      | [05c69304bb](https://linux-hardware.org/?probe=05c69304bb) | Jan 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [2cb5d2f306](https://linux-hardware.org/?probe=2cb5d2f306) | Jan 05, 2023 |
| Notebook      | NJx0MU                      | [fc365670d0](https://linux-hardware.org/?probe=fc365670d0) | Jan 05, 2023 |
| Dell          | Precision 7520              | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| Acer          | Aspire 5530                 | [8c12909b0a](https://linux-hardware.org/?probe=8c12909b0a) | Jan 04, 2023 |
| Lenovo        | G500 20236                  | [501b47c258](https://linux-hardware.org/?probe=501b47c258) | Jan 02, 2023 |
| Notebook      | NJx0MU                      | [0eb54f1078](https://linux-hardware.org/?probe=0eb54f1078) | Jan 01, 2023 |
| Notebook      | NJx0MU                      | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| HP            | Compaq Presario CQ61        | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | X550LN                      | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | 14                          | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | ProBook 450 G6              | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Notebook      | NJx0MU                      | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Notebook      | NJx0MU                      | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Dell          | Latitude D630               | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Precision 7760              | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| HP            | ENVY Sleekbook 6            | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| Chuwi         | GemiBook Pro                | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| Dell          | Precision 7760              | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| Acer          | Aspire 5050                 | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Precision 7760              | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | Notebook                    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| LincPlus      | LINNCPLUS P1                | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| HP            | EliteBook 745 G5            | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| HP            | 15 Notebook PC              | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HONOR         | BOHK-WAX9X                  | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| Dell          | Latitude E4200              | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Compaq        | Presario CQ-23              | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| MicroByte     | ezbook                      | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| Google        | Kled                        | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| Intel         | Kabylake Platform           | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| Dell          | Precision M6500             | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Apple         | MacBook5,1                  | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| Apple         | MacBookPro6,2               | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Apple         | MacBookPro9,1               | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 14        | 4.95%   |
| 5.15.0-58-generic | 10        | 3.53%   |
| 6.8.0-40-generic  | 7         | 2.47%   |
| 6.5.0-35-generic  | 7         | 2.47%   |
| 6.2.0-36-generic  | 7         | 2.47%   |
| 5.15.0-53-generic | 7         | 2.47%   |
| 5.15.0-52-generic | 7         | 2.47%   |
| 5.15.0-43-generic | 7         | 2.47%   |
| 5.15.0-25-generic | 7         | 2.47%   |
| 6.5.0-26-generic  | 6         | 2.12%   |
| 6.2.0-26-generic  | 6         | 2.12%   |
| 5.15.0-47-generic | 6         | 2.12%   |
| 5.15.0-46-generic | 6         | 2.12%   |
| 6.5.0-21-generic  | 5         | 1.77%   |
| 6.2.0-34-generic  | 5         | 1.77%   |
| 6.2.0-32-generic  | 5         | 1.77%   |
| 5.19.0-46-generic | 5         | 1.77%   |
| 5.19.0-32-generic | 5         | 1.77%   |
| 5.15.0-60-generic | 5         | 1.77%   |
| 5.15.0-48-generic | 5         | 1.77%   |
| 6.8.0-45-generic  | 4         | 1.41%   |
| 6.5.0-41-generic  | 4         | 1.41%   |
| 6.5.0-28-generic  | 4         | 1.41%   |
| 6.2.0-39-generic  | 4         | 1.41%   |
| 5.15.0-91-generic | 4         | 1.41%   |
| 5.15.0-40-generic | 4         | 1.41%   |
| 6.5.0-17-generic  | 3         | 1.06%   |
| 6.2.0-37-generic  | 3         | 1.06%   |
| 6.2.0-35-generic  | 3         | 1.06%   |
| 6.2.0-33-generic  | 3         | 1.06%   |
| 5.19.0-43-generic | 3         | 1.06%   |
| 5.19.0-42-generic | 3         | 1.06%   |
| 5.19.0-38-generic | 3         | 1.06%   |
| 5.19.0-35-generic | 3         | 1.06%   |
| 5.15.0-83-generic | 3         | 1.06%   |
| 5.15.0-67-generic | 3         | 1.06%   |
| 5.15.0-57-generic | 3         | 1.06%   |
| 5.15.0-41-generic | 3         | 1.06%   |
| 5.15.0-30-generic | 3         | 1.06%   |
| 5.15.0-27-generic | 3         | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 129       | 51.81%  |
| 6.5.0   | 37        | 14.86%  |
| 6.2.0   | 35        | 14.06%  |
| 5.19.0  | 25        | 10.04%  |
| 6.8.0   | 13        | 5.22%   |
| 6.6.6   | 1         | 0.4%    |
| 6.4.3   | 1         | 0.4%    |
| 6.2.3   | 1         | 0.4%    |
| 6.1.8   | 1         | 0.4%    |
| 6.0.8   | 1         | 0.4%    |
| 6.0.0   | 1         | 0.4%    |
| 5.18.0  | 1         | 0.4%    |
| 5.17.1  | 1         | 0.4%    |
| 5.17.0  | 1         | 0.4%    |
| 5.14.0  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 129       | 51.81%  |
| 6.5     | 37        | 14.86%  |
| 6.2     | 36        | 14.46%  |
| 5.19    | 25        | 10.04%  |
| 6.8     | 13        | 5.22%   |
| 6.0     | 2         | 0.8%    |
| 5.17    | 2         | 0.8%    |
| 6.6     | 1         | 0.4%    |
| 6.4     | 1         | 0.4%    |
| 6.1     | 1         | 0.4%    |
| 5.18    | 1         | 0.4%    |
| 5.14    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 233       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 230       | 98.71%  |
| X-Cinnamon | 1         | 0.43%   |
| GNOME      | 1         | 0.43%   |
| Cinnamon   | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 228       | 97.85%  |
| Tty     | 3         | 1.29%   |
| Wayland | 2         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 195       | 82.98%  |
| Unknown | 24        | 10.21%  |
| GDM3    | 15        | 6.38%   |
| SDDM    | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 81        | 34.47%  |
| de_DE | 40        | 17.02%  |
| fr_FR | 28        | 11.91%  |
| it_IT | 14        | 5.96%   |
| ru_RU | 11        | 4.68%   |
| pt_BR | 6         | 2.55%   |
| es_ES | 6         | 2.55%   |
| pl_PL | 5         | 2.13%   |
| en_GB | 4         | 1.7%    |
| en_CA | 4         | 1.7%    |
| es_MX | 3         | 1.28%   |
| en_AU | 3         | 1.28%   |
| C     | 3         | 1.28%   |
| zh_TW | 2         | 0.85%   |
| hu_HU | 2         | 0.85%   |
| fi_FI | 2         | 0.85%   |
| en_IN | 2         | 0.85%   |
| zh_CN | 1         | 0.43%   |
| tr_TR | 1         | 0.43%   |
| pt_PT | 1         | 0.43%   |
| nl_NL | 1         | 0.43%   |
| nl_BE | 1         | 0.43%   |
| ja_JP | 1         | 0.43%   |
| id_ID | 1         | 0.43%   |
| fr_CH | 1         | 0.43%   |
| eu_ES | 1         | 0.43%   |
| et_EE | 1         | 0.43%   |
| es_VE | 1         | 0.43%   |
| es_PY | 1         | 0.43%   |
| es_CO | 1         | 0.43%   |
| es_CL | 1         | 0.43%   |
| es_AR | 1         | 0.43%   |
| en_NZ | 1         | 0.43%   |
| el_GR | 1         | 0.43%   |
| de_CH | 1         | 0.43%   |
| cs_CZ | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 131       | 55.04%  |
| BIOS | 107       | 44.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 190       | 80.51%  |
| Tmpfs   | 29        | 12.29%  |
| Overlay | 8         | 3.39%   |
| Zfs     | 4         | 1.69%   |
| Btrfs   | 2         | 0.85%   |
| Xfs     | 1         | 0.42%   |
| Jfs     | 1         | 0.42%   |
| Ext3    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 179       | 75.85%  |
| Unknown | 31        | 13.14%  |
| MBR     | 26        | 11.02%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 208       | 89.27%  |
| Yes       | 25        | 10.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 158       | 67.23%  |
| Yes       | 77        | 32.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 52        | 22.32%  |
| Hewlett-Packard       | 51        | 21.89%  |
| Dell                  | 33        | 14.16%  |
| ASUSTek Computer      | 22        | 9.44%   |
| Acer                  | 14        | 6.01%   |
| Sony                  | 6         | 2.58%   |
| Toshiba               | 5         | 2.15%   |
| Apple                 | 5         | 2.15%   |
| HUAWEI                | 4         | 1.72%   |
| Intel                 | 3         | 1.29%   |
| Google                | 3         | 1.29%   |
| Notebook              | 2         | 0.86%   |
| Medion                | 2         | 0.86%   |
| Clevo                 | 2         | 0.86%   |
| AMI                   | 2         | 0.86%   |
| VIT                   | 1         | 0.43%   |
| TrekStor              | 1         | 0.43%   |
| SLIMBOOK              | 1         | 0.43%   |
| Samsung Electronics   | 1         | 0.43%   |
| Positivo Bahia - VAIO | 1         | 0.43%   |
| Positivo              | 1         | 0.43%   |
| Panasonic             | 1         | 0.43%   |
| Packard Bell          | 1         | 0.43%   |
| MSI                   | 1         | 0.43%   |
| Monster               | 1         | 0.43%   |
| MicroByte             | 1         | 0.43%   |
| LincPlus              | 1         | 0.43%   |
| LG Electronics        | 1         | 0.43%   |
| Kiano                 | 1         | 0.43%   |
| IPASON                | 1         | 0.43%   |
| Infinix               | 1         | 0.43%   |
| HYPERPC               | 1         | 0.43%   |
| HONOR                 | 1         | 0.43%   |
| GPU Company           | 1         | 0.43%   |
| GPD                   | 1         | 0.43%   |
| Gigabyte Technology   | 1         | 0.43%   |
| Compumax Computer     | 1         | 0.43%   |
| Compaq                | 1         | 0.43%   |
| Chuwi                 | 1         | 0.43%   |
| Bluechip Computer     | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP ProBook 640 G8 Notebook PC           | 3         | 1.29%   |
| HP Notebook                             | 3         | 1.29%   |
| HP Pavilion dv4                         | 2         | 0.86%   |
| Dell Precision M4800                    | 2         | 0.86%   |
| Dell Precision 7520                     | 2         | 0.86%   |
| Dell Latitude 7420                      | 2         | 0.86%   |
| Dell Latitude 5410                      | 2         | 0.86%   |
| Unknown                                 | 2         | 0.86%   |
| VIT P1400                               | 1         | 0.43%   |
| TrekStor Surfbook A13B                  | 1         | 0.43%   |
| Toshiba Satellite P50-B-10Z             | 1         | 0.43%   |
| Toshiba Satellite C70D-A                | 1         | 0.43%   |
| Toshiba Satellite C55-B                 | 1         | 0.43%   |
| Toshiba Satellite C50D-A-133            | 1         | 0.43%   |
| Toshiba PORTEGE R500                    | 1         | 0.43%   |
| Sony VPCEH1E1E                          | 1         | 0.43%   |
| Sony VPCEB2Z1E                          | 1         | 0.43%   |
| Sony VPCEA36FG                          | 1         | 0.43%   |
| Sony VGN-Z21WRN_B                       | 1         | 0.43%   |
| Sony SVF13N2J2ES                        | 1         | 0.43%   |
| Sony SVE1712T1EB                        | 1         | 0.43%   |
| SLIMBOOK TITAN                          | 1         | 0.43%   |
| Samsung 905S3G/906S3G/915S3G/9305SG     | 1         | 0.43%   |
| Positivo C4128G-15                      | 1         | 0.43%   |
| Positivo Bahia - VAIO VJFE59F11X-B0411H | 1         | 0.43%   |
| Panasonic CF-53SJCZYLM                  | 1         | 0.43%   |
| Packard Bell EasyNote ENTG81BA          | 1         | 0.43%   |
| Notebook NV4XMB,ME,MZ                   | 1         | 0.43%   |
| Notebook NJx0MU                         | 1         | 0.43%   |
| MSI GF65 Thin 10SDR                     | 1         | 0.43%   |
| Monster ABRA A5 V17.4                   | 1         | 0.43%   |
| MicroByte ezbook                        | 1         | 0.43%   |
| Medion S6445 MD61281                    | 1         | 0.43%   |
| Medion P8610                            | 1         | 0.43%   |
| LincPlus LINNCPLUS P1                   | 1         | 0.43%   |
| LG 17Z990-R.AAS8U1                      | 1         | 0.43%   |
| Lenovo Z710 20250                       | 1         | 0.43%   |
| Lenovo V15 G2 ITL 82KB                  | 1         | 0.43%   |
| Lenovo V15 G2 ALC 82KD                  | 1         | 0.43%   |
| Lenovo V145-15AST 81MT                  | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 27        | 11.59%  |
| Dell Latitude                           | 14        | 6.01%   |
| Lenovo IdeaPad                          | 12        | 5.15%   |
| HP Pavilion                             | 10        | 4.29%   |
| HP ProBook                              | 9         | 3.86%   |
| HP EliteBook                            | 9         | 3.86%   |
| Dell Precision                          | 8         | 3.43%   |
| Acer Aspire                             | 8         | 3.43%   |
| ASUS VivoBook                           | 7         | 3%      |
| Toshiba Satellite                       | 4         | 1.72%   |
| Dell XPS                                | 4         | 1.72%   |
| Dell Inspiron                           | 4         | 1.72%   |
| HP OMEN                                 | 3         | 1.29%   |
| HP Notebook                             | 3         | 1.29%   |
| HP Laptop                               | 3         | 1.29%   |
| ASUS ASUS                               | 3         | 1.29%   |
| Acer Extensa                            | 3         | 1.29%   |
| Lenovo V15                              | 2         | 0.86%   |
| Lenovo ThinkBook                        | 2         | 0.86%   |
| Lenovo Legion                           | 2         | 0.86%   |
| HP ZBook                                | 2         | 0.86%   |
| HP Stream                               | 2         | 0.86%   |
| HP 15                                   | 2         | 0.86%   |
| Dell Vostro                             | 2         | 0.86%   |
| Acer TravelMate                         | 2         | 0.86%   |
| Unknown                                 | 2         | 0.86%   |
| VIT P1400                               | 1         | 0.43%   |
| TrekStor Surfbook                       | 1         | 0.43%   |
| Toshiba PORTEGE                         | 1         | 0.43%   |
| Sony VPCEH1E1E                          | 1         | 0.43%   |
| Sony VPCEB2Z1E                          | 1         | 0.43%   |
| Sony VPCEA36FG                          | 1         | 0.43%   |
| Sony VGN-Z21WRN                         | 1         | 0.43%   |
| Sony SVF13N2J2ES                        | 1         | 0.43%   |
| Sony SVE1712T1EB                        | 1         | 0.43%   |
| SLIMBOOK TITAN                          | 1         | 0.43%   |
| Samsung 905S3G                          | 1         | 0.43%   |
| Positivo C4128G-15                      | 1         | 0.43%   |
| Positivo Bahia - VAIO VJFE59F11X-B0411H | 1         | 0.43%   |
| Panasonic CF-53SJCZYLM                  | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 39        | 16.74%  |
| 2020    | 22        | 9.44%   |
| 2019    | 20        | 8.58%   |
| 2013    | 19        | 8.15%   |
| 2018    | 15        | 6.44%   |
| 2016    | 13        | 5.58%   |
| 2015    | 13        | 5.58%   |
| 2014    | 13        | 5.58%   |
| 2008    | 13        | 5.58%   |
| 2022    | 12        | 5.15%   |
| 2012    | 11        | 4.72%   |
| 2017    | 10        | 4.29%   |
| 2011    | 9         | 3.86%   |
| 2010    | 7         | 3%      |
| 2009    | 7         | 3%      |
| 2007    | 4         | 1.72%   |
| 2023    | 3         | 1.29%   |
| 2024    | 1         | 0.43%   |
| 2006    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 233       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 213       | 90.25%  |
| Enabled  | 23        | 9.75%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 230       | 98.71%  |
| Yes  | 3         | 1.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 73        | 31.2%   |
| 3.01-4.0    | 51        | 21.79%  |
| 16.01-24.0  | 40        | 17.09%  |
| 8.01-16.0   | 33        | 14.1%   |
| 32.01-64.0  | 19        | 8.12%   |
| 24.01-32.0  | 6         | 2.56%   |
| 1.01-2.0    | 6         | 2.56%   |
| 2.01-3.0    | 3         | 1.28%   |
| 64.01-256.0 | 3         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 81        | 32.14%  |
| 2.01-3.0   | 78        | 30.95%  |
| 3.01-4.0   | 44        | 17.46%  |
| 4.01-8.0   | 33        | 13.1%   |
| 8.01-16.0  | 9         | 3.57%   |
| 0.51-1.0   | 5         | 1.98%   |
| 24.01-32.0 | 1         | 0.4%    |
| 16.01-24.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 183       | 78.21%  |
| 2      | 40        | 17.09%  |
| 3      | 10        | 4.27%   |
| 4      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 157       | 67.38%  |
| Yes       | 76        | 32.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 77.68%  |
| No        | 52        | 22.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 227       | 97.42%  |
| No        | 6         | 2.58%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 82.7%   |
| No        | 41        | 17.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 42        | 18.03%  |
| France      | 29        | 12.45%  |
| USA         | 24        | 10.3%   |
| Italy       | 18        | 7.73%   |
| Russia      | 11        | 4.72%   |
| Spain       | 10        | 4.29%   |
| Brazil      | 10        | 4.29%   |
| Poland      | 6         | 2.58%   |
| Turkey      | 5         | 2.15%   |
| Estonia     | 5         | 2.15%   |
| UK          | 4         | 1.72%   |
| Mexico      | 4         | 1.72%   |
| India       | 4         | 1.72%   |
| Finland     | 4         | 1.72%   |
| Switzerland | 3         | 1.29%   |
| Indonesia   | 3         | 1.29%   |
| Hungary     | 3         | 1.29%   |
| Chile       | 3         | 1.29%   |
| Canada      | 3         | 1.29%   |
| Belgium     | 3         | 1.29%   |
| Thailand    | 2         | 0.86%   |
| Serbia      | 2         | 0.86%   |
| Romania     | 2         | 0.86%   |
| Portugal    | 2         | 0.86%   |
| Paraguay    | 2         | 0.86%   |
| Netherlands | 2         | 0.86%   |
| Hong Kong   | 2         | 0.86%   |
| Greece      | 2         | 0.86%   |
| Colombia    | 2         | 0.86%   |
| Austria     | 2         | 0.86%   |
| Australia   | 2         | 0.86%   |
| Venezuela   | 1         | 0.43%   |
| Ukraine     | 1         | 0.43%   |
| Taiwan      | 1         | 0.43%   |
| Slovenia    | 1         | 0.43%   |
| Peru        | 1         | 0.43%   |
| New Zealand | 1         | 0.43%   |
| Libya       | 1         | 0.43%   |
| Japan       | 1         | 0.43%   |
| Israel      | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 7         | 2.89%   |
| Moscow            | 7         | 2.89%   |
| Warsaw            | 5         | 2.07%   |
| Wittingen         | 4         | 1.65%   |
| Mannheim          | 3         | 1.24%   |
| Hamburg           | 3         | 1.24%   |
| Frankfurt am Main | 3         | 1.24%   |
| Berlin            | 3         | 1.24%   |
| Vienna            | 2         | 0.83%   |
| Tallinn           | 2         | 0.83%   |
| Tabasalu          | 2         | 0.83%   |
| Rome              | 2         | 0.83%   |
| Madrid            | 2         | 0.83%   |
| Lisbon            | 2         | 0.83%   |
| Hyderabad         | 2         | 0.83%   |
| Greenville        | 2         | 0.83%   |
| Düsseldorf       | 2         | 0.83%   |
| Dortmund          | 2         | 0.83%   |
| Belgrade          | 2         | 0.83%   |
| Bangkok           | 2         | 0.83%   |
| Bad Doberan       | 2         | 0.83%   |
| Asunción         | 2         | 0.83%   |
| Zalla             | 1         | 0.41%   |
| Xining            | 1         | 0.41%   |
| Wuppertal         | 1         | 0.41%   |
| Werder            | 1         | 0.41%   |
| Wellin            | 1         | 0.41%   |
| Weiden            | 1         | 0.41%   |
| Voronezh          | 1         | 0.41%   |
| Viroflay          | 1         | 0.41%   |
| Villeurbanne      | 1         | 0.41%   |
| Veracruz          | 1         | 0.41%   |
| Venice            | 1         | 0.41%   |
| Vaudoy-en-Brie    | 1         | 0.41%   |
| Varna             | 1         | 0.41%   |
| Valledupar        | 1         | 0.41%   |
| Valenciennes      | 1         | 0.41%   |
| Valence           | 1         | 0.41%   |
| Turku             | 1         | 0.41%   |
| Turin             | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 55        | 100    | 19.23%  |
| Seagate                     | 28        | 30     | 9.79%   |
| Unknown                     | 23        | 26     | 8.04%   |
| WDC                         | 21        | 22     | 7.34%   |
| Toshiba                     | 17        | 21     | 5.94%   |
| Crucial                     | 17        | 19     | 5.94%   |
| SanDisk                     | 16        | 18     | 5.59%   |
| SK hynix                    | 12        | 13     | 4.2%    |
| Kingston                    | 12        | 13     | 4.2%    |
| Intel                       | 7         | 7      | 2.45%   |
| A-DATA Technology           | 7         | 7      | 2.45%   |
| Hitachi                     | 6         | 6      | 2.1%    |
| HGST                        | 6         | 6      | 2.1%    |
| SPCC                        | 5         | 7      | 1.75%   |
| China                       | 5         | 6      | 1.75%   |
| KIOXIA                      | 4         | 4      | 1.4%    |
| Phison                      | 3         | 3      | 1.05%   |
| Micron Technology           | 3         | 3      | 1.05%   |
| Intenso                     | 3         | 3      | 1.05%   |
| UMIS                        | 2         | 3      | 0.7%    |
| Patriot                     | 2         | 2      | 0.7%    |
| LITEONIT                    | 2         | 2      | 0.7%    |
| KingSpec                    | 2         | 4      | 0.7%    |
| Apple                       | 2         | 2      | 0.7%    |
| ADATA Technology            | 2         | 2      | 0.7%    |
| WDC WDS2                    | 1         | 1      | 0.35%   |
| Verbatim                    | 1         | 10     | 0.35%   |
| Smartbuy                    | 1         | 1      | 0.35%   |
| Silicon Motion              | 1         | 1      | 0.35%   |
| SABRENT                     | 1         | 1      | 0.35%   |
| Realtek Semiconductor       | 1         | 2      | 0.35%   |
| R580                        | 1         | 1      | 0.35%   |
| PNY                         | 1         | 1      | 0.35%   |
| Phison Electronics          | 1         | 1      | 0.35%   |
| OCZ                         | 1         | 1      | 0.35%   |
| Netac                       | 1         | 1      | 0.35%   |
| LITEON                      | 1         | 1      | 0.35%   |
| Lenovo                      | 1         | 1      | 0.35%   |
| Kston                       | 1         | 1      | 0.35%   |
| Kingston Technology Company | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 4         | 1.34%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                     | 4         | 1.34%   |
| Unknown NVMe SSD Drive 512GB                         | 3         | 1%      |
| Unknown MMC Card  64GB                               | 3         | 1%      |
| Unknown MMC Card  32GB                               | 3         | 1%      |
| Toshiba MQ01ABF050 500GB                             | 3         | 1%      |
| Seagate ST500LT012-1DG142 500GB                      | 3         | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 3         | 1%      |
| Samsung MZVLQ512HALU-000H1 512GB                     | 3         | 1%      |
| Kingston SA400S37240G 240GB SSD                      | 3         | 1%      |
| Crucial CT1000MX500SSD1 1TB                          | 3         | 1%      |
| WDC WD5000LPVX-60V0TT0 500GB                         | 2         | 0.67%   |
| Unknown SLD64G  64GB                                 | 2         | 0.67%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 2         | 0.67%   |
| Toshiba MQ01ABD075 752GB                             | 2         | 0.67%   |
| SK hynix PC611 NVMe 1TB                              | 2         | 0.67%   |
| Seagate ST9500420AS 500GB                            | 2         | 0.67%   |
| Seagate ST2000LM015-2E8174 2TB                       | 2         | 0.67%   |
| Seagate ST1000LM014-1EJ164 1TB                       | 2         | 0.67%   |
| Seagate Expansion 1TB                                | 2         | 0.67%   |
| Sandisk PC SN520 NVMe SSD 256GB                      | 2         | 0.67%   |
| Samsung SSD 980 PRO 1TB                              | 2         | 0.67%   |
| Samsung SSD 980 1TB                                  | 2         | 0.67%   |
| Samsung SSD 970 EVO Plus 2TB                         | 2         | 0.67%   |
| Samsung SSD 860 EVO 250GB                            | 2         | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 2         | 0.67%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 2         | 0.67%   |
| Kingston SA400S37480G 480GB SSD                      | 2         | 0.67%   |
| HGST HTS725050A7E630 500GB                           | 2         | 0.67%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 0.67%   |
| Crucial CT240BX500SSD1 240GB                         | 2         | 0.67%   |
| Crucial CT1000BX500SSD1 1TB                          | 2         | 0.67%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD                      | 1         | 0.33%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                       | 1         | 0.33%   |
| WDC WD7500BPVX-60JC3T0 752GB                         | 1         | 0.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 1         | 0.33%   |
| WDC WD5000LPCX-22VHAT0 500GB                         | 1         | 0.33%   |
| WDC WD5000LPCX-21VHAT0 500GB                         | 1         | 0.33%   |
| WDC WD40 EFRX-68N32N0 4TB                            | 1         | 0.33%   |
| WDC WD3200BEVT-22ZCT0 320GB                          | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 27        | 29     | 42.19%  |
| WDC                | 13        | 14     | 20.31%  |
| Toshiba            | 10        | 13     | 15.63%  |
| Hitachi            | 6         | 6      | 9.38%   |
| HGST               | 6         | 6      | 9.38%   |
| SABRENT            | 1         | 1      | 1.56%   |
| JMicron Technology | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 34     | 26.42%  |
| Crucial             | 14        | 16     | 13.21%  |
| Kingston            | 11        | 12     | 10.38%  |
| SanDisk             | 9         | 10     | 8.49%   |
| China               | 5         | 6      | 4.72%   |
| A-DATA Technology   | 5         | 5      | 4.72%   |
| SPCC                | 4         | 6      | 3.77%   |
| WDC                 | 3         | 3      | 2.83%   |
| Intenso             | 3         | 3      | 2.83%   |
| Toshiba             | 2         | 3      | 1.89%   |
| LITEONIT            | 2         | 2      | 1.89%   |
| KingSpec            | 2         | 4      | 1.89%   |
| Intel               | 2         | 2      | 1.89%   |
| WDC WDS2            | 1         | 1      | 0.94%   |
| Verbatim            | 1         | 10     | 0.94%   |
| Smartbuy            | 1         | 1      | 0.94%   |
| SK hynix            | 1         | 1      | 0.94%   |
| PNY                 | 1         | 1      | 0.94%   |
| Phison              | 1         | 1      | 0.94%   |
| Patriot             | 1         | 1      | 0.94%   |
| OCZ                 | 1         | 1      | 0.94%   |
| Netac               | 1         | 1      | 0.94%   |
| Micron Technology   | 1         | 1      | 0.94%   |
| LITEON              | 1         | 1      | 0.94%   |
| Kston               | 1         | 1      | 0.94%   |
| KingFast            | 1         | 1      | 0.94%   |
| Corsair             | 1         | 1      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |
| addlink             | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 96        | 131    | 35.16%  |
| NVMe    | 92        | 135    | 33.7%   |
| HDD     | 60        | 70     | 21.98%  |
| MMC     | 20        | 23     | 7.33%   |
| Unknown | 5         | 5      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 187    | 52.04%  |
| NVMe | 92        | 135    | 34.2%   |
| MMC  | 20        | 23     | 7.43%   |
| SAS  | 17        | 19     | 6.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 98        | 119    | 61.25%  |
| 0.51-1.0   | 43        | 55     | 26.88%  |
| 1.01-2.0   | 10        | 17     | 6.25%   |
| 3.01-4.0   | 6         | 7      | 3.75%   |
| 4.01-10.0  | 2         | 2      | 1.25%   |
| 10.01-20.0 | 1         | 1      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 30.71%  |
| 251-500        | 59        | 24.48%  |
| 501-1000       | 36        | 14.94%  |
| 51-100         | 20        | 8.3%    |
| 1001-2000      | 15        | 6.22%   |
| 1-20           | 11        | 4.56%   |
| 21-50          | 10        | 4.15%   |
| More than 3000 | 8         | 3.32%   |
| 2001-3000      | 6         | 2.49%   |
| Unknown        | 2         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 69        | 28.51%  |
| 21-50          | 48        | 19.83%  |
| 101-250        | 41        | 16.94%  |
| 51-100         | 34        | 14.05%  |
| 251-500        | 20        | 8.26%   |
| 501-1000       | 14        | 5.79%   |
| 2001-3000      | 5         | 2.07%   |
| 1001-2000      | 5         | 2.07%   |
| More than 3000 | 4         | 1.65%   |
| Unknown        | 2         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 10%     |
| WDC WD7500BPVX-60JC3T0 752GB                 | 1         | 2      | 5%      |
| WDC WD40 EFRX-68N32N0 4TB                    | 1         | 1      | 5%      |
| Toshiba MQ01ABD075 752GB                     | 1         | 1      | 5%      |
| Toshiba MK3263GSXN 320GB                     | 1         | 1      | 5%      |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 5%      |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 5%      |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 5%      |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 5%      |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 5%      |
| Netac SSD 256GB                              | 1         | 1      | 5%      |
| LITEON CV8-CE256-HP 256GB SSD                | 1         | 1      | 5%      |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 5%      |
| Intenso SSD 1TB                              | 1         | 1      | 5%      |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 5%      |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 5%      |
| Hitachi HTS723225L9A360 250GB                | 1         | 1      | 5%      |
| Hitachi HTS543232L9A300 320GB                | 1         | 1      | 5%      |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 20%     |
| Hitachi             | 3         | 3      | 15%     |
| WDC                 | 2         | 3      | 10%     |
| Toshiba             | 2         | 2      | 10%     |
| SK hynix            | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| OCZ                 | 1         | 1      | 5%      |
| Netac               | 1         | 1      | 5%      |
| LITEON              | 1         | 1      | 5%      |
| Kingston            | 1         | 1      | 5%      |
| Intenso             | 1         | 1      | 5%      |
| Intel               | 1         | 1      | 5%      |
| HGST                | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 33.33%  |
| Hitachi | 3         | 3      | 25%     |
| WDC     | 2         | 3      | 16.67%  |
| Toshiba | 2         | 2      | 16.67%  |
| HGST    | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 60%     |
| SSD  | 6         | 6      | 30%     |
| NVMe | 2         | 2      | 10%     |

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
| Works    | 137       | 189    | 53.1%   |
| Detected | 101       | 154    | 39.15%  |
| Malfunc  | 20        | 21     | 7.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 154       | 55.8%   |
| Samsung Electronics          | 32        | 11.59%  |
| AMD                          | 26        | 9.42%   |
| SK hynix                     | 11        | 3.99%   |
| SanDisk                      | 11        | 3.99%   |
| Toshiba America Info Systems | 5         | 1.81%   |
| KIOXIA                       | 5         | 1.81%   |
| Phison Electronics           | 4         | 1.45%   |
| Nvidia                       | 4         | 1.45%   |
| ADATA Technology             | 4         | 1.45%   |
| Micron Technology            | 3         | 1.09%   |
| Union Memory (Shenzhen)      | 2         | 0.72%   |
| Solidigm                     | 2         | 0.72%   |
| Micron/Crucial Technology    | 2         | 0.72%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.72%   |
| Kingston Technology Company  | 2         | 0.72%   |
| Silicon Motion               | 1         | 0.36%   |
| Shenzhen Longsys Electronics | 1         | 0.36%   |
| Realtek Semiconductor        | 1         | 0.36%   |
| Marvell Technology Group     | 1         | 0.36%   |
| Lenovo                       | 1         | 0.36%   |
| Biwin Storage Technology     | 1         | 0.36%   |
| Unknown                      | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 7.61%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 17        | 5.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 5.19%   |
| Intel Volume Management Device NVMe RAID Controller                              | 12        | 4.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 3.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 3.81%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 3.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 3.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 2.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 2.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 2.42%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.38%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.04%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 1.04%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.04%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 3         | 1.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 3         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 1.04%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.04%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.69%   |
| Solidigm P41 Plus NVMe SSD (DRAM-less) [Echo Harbor]                             | 2         | 0.69%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 2         | 0.69%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.69%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.69%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 2         | 0.69%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 2         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 152       | 54.48%  |
| NVMe | 92        | 32.97%  |
| RAID | 24        | 8.6%    |
| IDE  | 11        | 3.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 191       | 81.97%  |
| AMD    | 42        | 18.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.72%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 3         | 1.29%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.29%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.29%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.29%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 1.29%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.29%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 1.29%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 3         | 1.29%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.29%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.29%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 3         | 1.29%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.86%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.86%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.86%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 2         | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.86%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.86%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.86%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.86%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.86%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.86%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.86%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.86%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.86%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 2         | 0.86%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 2         | 0.86%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.86%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 49        | 21.03%  |
| Intel Core i5           | 42        | 18.03%  |
| Other                   | 28        | 12.02%  |
| Intel Celeron           | 22        | 9.44%   |
| Intel Core i3           | 16        | 6.87%   |
| Intel Core 2 Duo        | 15        | 6.44%   |
| AMD Ryzen 7             | 9         | 3.86%   |
| AMD Ryzen 5             | 9         | 3.86%   |
| Intel Pentium           | 7         | 3%      |
| AMD A6                  | 5         | 2.15%   |
| Intel Atom              | 4         | 1.72%   |
| Intel Pentium Silver    | 3         | 1.29%   |
| Intel Pentium Dual-Core | 3         | 1.29%   |
| AMD Ryzen 9             | 2         | 0.86%   |
| AMD Ryzen 7 PRO         | 2         | 0.86%   |
| AMD Ryzen 3             | 2         | 0.86%   |
| AMD A8                  | 2         | 0.86%   |
| AMD A4                  | 2         | 0.86%   |
| Intel Xeon              | 1         | 0.43%   |
| Intel Core m5           | 1         | 0.43%   |
| Intel Core M            | 1         | 0.43%   |
| AMD Turion 64 X2 Mobile | 1         | 0.43%   |
| AMD Turion 64 Mobile    | 1         | 0.43%   |
| AMD Sempron             | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD Quad-Core           | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD Athlon X2           | 1         | 0.43%   |
| AMD Athlon II           | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 112       | 48.07%  |
| 4      | 82        | 35.19%  |
| 8      | 18        | 7.73%   |
| 6      | 15        | 6.44%   |
| 14     | 3         | 1.29%   |
| 1      | 2         | 0.86%   |
| 10     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 233       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 160       | 68.67%  |
| 1      | 73        | 31.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 233       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 54.17%  |
| 0x806c1    | 11        | 4.58%   |
| 0x806ec    | 7         | 2.92%   |
| 0x40651    | 7         | 2.92%   |
| 0x306a9    | 6         | 2.5%    |
| 0x406e3    | 5         | 2.08%   |
| 0x1067a    | 5         | 2.08%   |
| 0x0700010f | 5         | 2.08%   |
| 0x806d1    | 4         | 1.67%   |
| 0x406c4    | 4         | 1.67%   |
| 0x30678    | 4         | 1.67%   |
| 0x0a50000c | 4         | 1.67%   |
| 0x08108109 | 4         | 1.67%   |
| 0x906a3    | 3         | 1.25%   |
| 0x706a8    | 3         | 1.25%   |
| 0x506c9    | 3         | 1.25%   |
| 0x206a7    | 3         | 1.25%   |
| 0x906c0    | 2         | 0.83%   |
| 0x806ea    | 2         | 0.83%   |
| 0x806e9    | 2         | 0.83%   |
| 0x706e5    | 2         | 0.83%   |
| 0x6fd      | 2         | 0.83%   |
| 0x20655    | 2         | 0.83%   |
| 0x10676    | 2         | 0.83%   |
| 0x08608103 | 2         | 0.83%   |
| 0x906e9    | 1         | 0.42%   |
| 0x906a4    | 1         | 0.42%   |
| 0x806eb    | 1         | 0.42%   |
| 0x706a1    | 1         | 0.42%   |
| 0x6fb      | 1         | 0.42%   |
| 0x506e3    | 1         | 0.42%   |
| 0x0a601203 | 1         | 0.42%   |
| 0x0a50000d | 1         | 0.42%   |
| 0x08608104 | 1         | 0.42%   |
| 0x08608102 | 1         | 0.42%   |
| 0x08101016 | 1         | 0.42%   |
| 0x07030105 | 1         | 0.42%   |
| 0x07030104 | 1         | 0.42%   |
| 0x0600611a | 1         | 0.42%   |
| 0x02000032 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 12.82%  |
| Haswell          | 19        | 8.12%   |
| TigerLake        | 16        | 6.84%   |
| Silvermont       | 16        | 6.84%   |
| IvyBridge        | 16        | 6.84%   |
| Skylake          | 13        | 5.56%   |
| Penryn           | 13        | 5.56%   |
| SandyBridge      | 12        | 5.13%   |
| Icelake          | 11        | 4.7%    |
| Goldmont plus    | 9         | 3.85%   |
| Unknown          | 9         | 3.85%   |
| Zen 3            | 7         | 2.99%   |
| Zen+             | 6         | 2.56%   |
| Broadwell        | 6         | 2.56%   |
| Westmere         | 5         | 2.14%   |
| Jaguar           | 5         | 2.14%   |
| Core             | 5         | 2.14%   |
| CometLake        | 5         | 2.14%   |
| Alderlake Hybrid | 5         | 2.14%   |
| Zen 2            | 4         | 1.71%   |
| Excavator        | 4         | 1.71%   |
| Puma             | 3         | 1.28%   |
| Goldmont         | 3         | 1.28%   |
| Zen              | 2         | 0.85%   |
| Tremont          | 2         | 0.85%   |
| Nehalem          | 2         | 0.85%   |
| K8 Hammer        | 2         | 0.85%   |
| K10              | 2         | 0.85%   |
| K8 & K10 hybrid  | 1         | 0.43%   |
| Gracemont        | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 170       | 59.86%  |
| Nvidia | 58        | 20.42%  |
| AMD    | 56        | 19.72%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 4.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 4.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 3.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 3.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 3.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 2.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.72%   |
| AMD Lucienne                                                                             | 5         | 1.72%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 4         | 1.38%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.38%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 1.38%   |
| Intel HD Graphics 620                                                                    | 4         | 1.38%   |
| Intel HD Graphics 530                                                                    | 4         | 1.38%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 4         | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.03%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.03%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.03%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.03%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.03%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.69%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.69%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.69%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 126       | 54.08%  |
| 1 x AMD        | 38        | 16.31%  |
| Intel + Nvidia | 35        | 15.02%  |
| 1 x Nvidia     | 15        | 6.44%   |
| Intel + AMD    | 9         | 3.86%   |
| AMD + Nvidia   | 7         | 3%      |
| 2 x AMD        | 2         | 0.86%   |
| 2 x Nvidia     | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 191       | 81.28%  |
| Proprietary | 37        | 15.74%  |
| Unknown     | 7         | 2.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 176       | 74.89%  |
| 0.01-0.5   | 26        | 11.06%  |
| 1.01-2.0   | 11        | 4.68%   |
| 0.51-1.0   | 10        | 4.26%   |
| 3.01-4.0   | 6         | 2.55%   |
| 5.01-6.0   | 4         | 1.7%    |
| 7.01-8.0   | 1         | 0.43%   |
| 8.01-16.0  | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 45        | 16.79%  |
| LG Display              | 40        | 14.93%  |
| Chimei Innolux          | 37        | 13.81%  |
| AU Optronics            | 34        | 12.69%  |
| Samsung Electronics     | 27        | 10.07%  |
| Dell                    | 8         | 2.99%   |
| Sharp                   | 6         | 2.24%   |
| PANDA                   | 6         | 2.24%   |
| Lenovo                  | 6         | 2.24%   |
| Apple                   | 5         | 1.87%   |
| Hewlett-Packard         | 4         | 1.49%   |
| Goldstar                | 4         | 1.49%   |
| Chi Mei Optoelectronics | 4         | 1.49%   |
| Sony                    | 3         | 1.12%   |
| CSO                     | 3         | 1.12%   |
| BenQ                    | 3         | 1.12%   |
| AOC                     | 3         | 1.12%   |
| Ancor Communications    | 3         | 1.12%   |
| Philips                 | 2         | 0.75%   |
| LG Philips              | 2         | 0.75%   |
| Iiyama                  | 2         | 0.75%   |
| CS_                     | 2         | 0.75%   |
| ViewSonic               | 1         | 0.37%   |
| Unknown                 | 1         | 0.37%   |
| Toshiba                 | 1         | 0.37%   |
| Sceptre Tech            | 1         | 0.37%   |
| Quanta Display          | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| LGD                     | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| HJC                     | 1         | 0.37%   |
| Hitachi                 | 1         | 0.37%   |
| HannStar                | 1         | 0.37%   |
| GBE                     | 1         | 0.37%   |
| Envision                | 1         | 0.37%   |
| Eizo                    | 1         | 0.37%   |
| CSW                     | 1         | 0.37%   |
| CPT                     | 1         | 0.37%   |
| ASUSTek Computer        | 1         | 0.37%   |
| Aosiman                 | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0724 1920x1080 309x174mm 14.0-inch         | 3         | 1.11%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch | 2         | 0.74%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch         | 2         | 0.74%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 2         | 0.74%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch              | 2         | 0.74%   |
| CS_ LCD Monitor CS_5211 1920x1080 519x324mm 24.1-inch                | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch     | 2         | 0.74%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                | 2         | 0.74%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch        | 2         | 0.74%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch               | 2         | 0.74%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 600x340mm 27.2-inch        | 1         | 0.37%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                 | 1         | 0.37%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch             | 1         | 0.37%   |
| Sony TV SNYA102 1920x1080 708x398mm 32.0-inch                        | 1         | 0.37%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch              | 1         | 0.37%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch              | 1         | 0.37%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 0.37%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 1         | 0.37%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.37%   |
| Sharp HDMI SHP10E8 1360x768 521x293mm 23.5-inch                      | 1         | 0.37%   |
| Sceptre Tech E248W-1920 SPT099D 1920x1080 443x249mm 20.0-inch        | 1         | 0.37%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch  | 1         | 0.37%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch   | 1         | 0.37%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 1         | 0.37%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch    | 1         | 0.37%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 1         | 0.37%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1         | 0.37%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch  | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 110       | 44.18%  |
| 1366x768 (WXGA)    | 72        | 28.92%  |
| 1280x800 (WXGA)    | 11        | 4.42%   |
| 1600x900 (HD+)     | 10        | 4.02%   |
| 2560x1440 (QHD)    | 9         | 3.61%   |
| 3840x2160 (4K)     | 8         | 3.21%   |
| 2560x1600          | 5         | 2.01%   |
| 1440x900 (WXGA+)   | 5         | 2.01%   |
| 3840x2400          | 4         | 1.61%   |
| 1920x1200 (WUXGA)  | 4         | 1.61%   |
| 2160x1440          | 2         | 0.8%    |
| 1680x1050 (WSXGA+) | 2         | 0.8%    |
| 3200x1800 (QHD+)   | 1         | 0.4%    |
| 2880x1800          | 1         | 0.4%    |
| 2880x1620          | 1         | 0.4%    |
| 2560x1080          | 1         | 0.4%    |
| 1680x945           | 1         | 0.4%    |
| 1360x768           | 1         | 0.4%    |
| 1280x960           | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 99        | 36.94%  |
| 14      | 36        | 13.43%  |
| 13      | 33        | 12.31%  |
| 17      | 21        | 7.84%   |
| 27      | 15        | 5.6%    |
| 24      | 15        | 5.6%    |
| 12      | 10        | 3.73%   |
| 23      | 5         | 1.87%   |
| 21      | 5         | 1.87%   |
| 11      | 5         | 1.87%   |
| 31      | 4         | 1.49%   |
| 16      | 4         | 1.49%   |
| 84      | 2         | 0.75%   |
| 54      | 2         | 0.75%   |
| 40      | 2         | 0.75%   |
| 18      | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 42      | 1         | 0.37%   |
| 34      | 1         | 0.37%   |
| 32      | 1         | 0.37%   |
| 25      | 1         | 0.37%   |
| 22      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 161       | 60.75%  |
| 501-600     | 33        | 12.45%  |
| 201-300     | 27        | 10.19%  |
| 351-400     | 20        | 7.55%   |
| 401-500     | 8         | 3.02%   |
| 601-700     | 5         | 1.89%   |
| 801-900     | 2         | 0.75%   |
| 701-800     | 2         | 0.75%   |
| 1501-2000   | 2         | 0.75%   |
| 1001-1500   | 2         | 0.75%   |
| Unknown     | 2         | 0.75%   |
| 901-1000    | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 190       | 82.97%  |
| 16/10   | 34        | 14.85%  |
| 3/2     | 2         | 0.87%   |
| 5/4     | 1         | 0.44%   |
| 21/9    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 96        | 35.96%  |
| 81-90          | 61        | 22.85%  |
| 201-250        | 18        | 6.74%   |
| 121-130        | 17        | 6.37%   |
| 301-350        | 15        | 5.62%   |
| 61-70          | 10        | 3.75%   |
| 71-80          | 8         | 3%      |
| 251-300        | 8         | 3%      |
| 351-500        | 6         | 2.25%   |
| 51-60          | 5         | 1.87%   |
| More than 1000 | 4         | 1.5%    |
| 111-120        | 4         | 1.5%    |
| 141-150        | 3         | 1.12%   |
| 131-140        | 3         | 1.12%   |
| 501-1000       | 3         | 1.12%   |
| 91-100         | 3         | 1.12%   |
| Unknown        | 2         | 0.75%   |
| 41-50          | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 40.15%  |
| 101-120       | 76        | 29.34%  |
| 51-100        | 50        | 19.31%  |
| 161-240       | 19        | 7.34%   |
| More than 240 | 5         | 1.93%   |
| 1-50          | 3         | 1.16%   |
| Unknown       | 2         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 184       | 78.63%  |
| 2     | 38        | 16.24%  |
| 3     | 7         | 2.99%   |
| 0     | 4         | 1.71%   |
| 4     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 131       | 37.01%  |
| Realtek Semiconductor             | 120       | 33.9%   |
| Qualcomm Atheros                  | 37        | 10.45%  |
| Broadcom                          | 21        | 5.93%   |
| ASIX Electronics                  | 7         | 1.98%   |
| Ralink                            | 4         | 1.13%   |
| MediaTek                          | 4         | 1.13%   |
| TP-Link                           | 3         | 0.85%   |
| Nvidia                            | 3         | 0.85%   |
| Marvell Technology Group          | 3         | 0.85%   |
| Ericsson Business Mobile Networks | 3         | 0.85%   |
| Broadcom Limited                  | 3         | 0.85%   |
| JMicron Technology                | 2         | 0.56%   |
| Hewlett-Packard                   | 2         | 0.56%   |
| DisplayLink                       | 2         | 0.56%   |
| Sierra Wireless                   | 1         | 0.28%   |
| Samsung Electronics               | 1         | 0.28%   |
| Ralink Technology                 | 1         | 0.28%   |
| Quectel Wireless Solutions        | 1         | 0.28%   |
| Qualcomm Atheros Communications   | 1         | 0.28%   |
| Microchip Technology              | 1         | 0.28%   |
| Lenovo                            | 1         | 0.28%   |
| Dell                              | 1         | 0.28%   |
| D-Link System                     | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 67        | 15.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 19        | 4.27%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 2.92%   |
| Intel Wi-Fi 6 AX200                                                    | 11        | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 9         | 2.02%   |
| Intel Wireless 8265 / 8275                                             | 9         | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.8%    |
| Intel Wireless 7260                                                    | 8         | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 1.57%   |
| Intel Wireless 8260                                                    | 7         | 1.57%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.35%   |
| Intel Wireless 7265                                                    | 6         | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.35%   |
| Realtek 802.11ac NIC                                                   | 5         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.9%    |
| Intel Wireless 3165                                                    | 4         | 0.9%    |
| Intel WiFi Link 5100                                                   | 4         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 0.9%    |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.9%    |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.9%    |
| Intel Centrino Wireless-N 2230                                         | 4         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.67%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 3         | 0.67%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 3         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 0.67%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 130       | 53.5%   |
| Realtek Semiconductor           | 47        | 19.34%  |
| Qualcomm Atheros                | 34        | 13.99%  |
| Broadcom                        | 16        | 6.58%   |
| Ralink                          | 4         | 1.65%   |
| TP-Link                         | 3         | 1.23%   |
| MediaTek                        | 2         | 0.82%   |
| Broadcom Limited                | 2         | 0.82%   |
| Sierra Wireless                 | 1         | 0.41%   |
| Ralink Technology               | 1         | 0.41%   |
| Qualcomm Atheros Communications | 1         | 0.41%   |
| Dell                            | 1         | 0.41%   |
| D-Link System                   | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 13        | 5.33%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 4.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 4.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 10        | 4.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.69%   |
| Intel Wireless 8265 / 8275                                              | 9         | 3.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.28%   |
| Intel Wireless 7260                                                     | 8         | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.87%   |
| Intel Wireless 8260                                                     | 7         | 2.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.46%   |
| Intel Wireless 7265                                                     | 6         | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.46%   |
| Realtek 802.11ac NIC                                                    | 5         | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.64%   |
| Intel Wireless 3165                                                     | 4         | 1.64%   |
| Intel WiFi Link 5100                                                    | 4         | 1.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.64%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 1.64%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.23%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 1.23%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 1.23%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.23%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.82%   |
| Intel Wireless 3160                                                     | 2         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 97        | 50.79%  |
| Intel                    | 56        | 29.32%  |
| Broadcom                 | 8         | 4.19%   |
| ASIX Electronics         | 7         | 3.66%   |
| Qualcomm Atheros         | 6         | 3.14%   |
| Nvidia                   | 3         | 1.57%   |
| Marvell Technology Group | 3         | 1.57%   |
| MediaTek                 | 2         | 1.05%   |
| JMicron Technology       | 2         | 1.05%   |
| DisplayLink              | 2         | 1.05%   |
| Samsung Electronics      | 1         | 0.52%   |
| Microchip Technology     | 1         | 0.52%   |
| Lenovo                   | 1         | 0.52%   |
| Hewlett-Packard          | 1         | 0.52%   |
| Broadcom Limited         | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 67        | 34.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 9.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 4.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 4.08%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 3.57%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 2.04%   |
| Intel Ethernet Connection (13) I219-V                                          | 4         | 2.04%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.53%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.53%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.53%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.53%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 1.53%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.02%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.02%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.02%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.02%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.51%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller                    | 1         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.51%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.51%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.51%   |
| MediaTek Infinix SMART 5                                                       | 1         | 0.51%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.51%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.51%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 227       | 54.96%  |
| Ethernet | 181       | 43.83%  |
| Modem    | 5         | 1.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 193       | 77.51%  |
| Ethernet | 56        | 22.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 166       | 71.24%  |
| 1     | 62        | 26.61%  |
| 0     | 5         | 2.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 65.68%  |
| Yes  | 81        | 34.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 106       | 53.81%  |
| Realtek Semiconductor           | 27        | 13.71%  |
| Broadcom                        | 18        | 9.14%   |
| Qualcomm Atheros Communications | 13        | 6.6%    |
| IMC Networks                    | 8         | 4.06%   |
| Ralink                          | 4         | 2.03%   |
| Foxconn / Hon Hai               | 4         | 2.03%   |
| Apple                           | 4         | 2.03%   |
| Toshiba                         | 3         | 1.52%   |
| Lite-On Technology              | 3         | 1.52%   |
| Hewlett-Packard                 | 3         | 1.52%   |
| Cambridge Silicon Radio         | 3         | 1.52%   |
| Foxconn International           | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 34        | 17.26%  |
| Intel AX201 Bluetooth                                                               | 34        | 17.26%  |
| Realtek Bluetooth Radio                                                             | 20        | 10.15%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 7.11%   |
| Intel AX200 Bluetooth                                                               | 11        | 5.58%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 3.05%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.05%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 2.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.03%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.03%   |
| Realtek 802.11ac WLAN Adapter                                                       | 3         | 1.52%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.52%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.52%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 1.52%   |
| Toshiba Bluetooth Device                                                            | 2         | 1.02%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.02%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.02%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.02%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.02%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.02%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.02%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.02%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.51%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.51%   |
| Intel AX211 Bluetooth                                                               | 1         | 0.51%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.51%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 184       | 64.79%  |
| AMD                       | 48        | 16.9%   |
| Nvidia                    | 41        | 14.44%  |
| C-Media Electronics       | 2         | 0.7%    |
| Sennheiser Communications | 1         | 0.35%   |
| Realtek Semiconductor     | 1         | 0.35%   |
| Plantronics               | 1         | 0.35%   |
| Meizu                     | 1         | 0.35%   |
| Lenovo                    | 1         | 0.35%   |
| Kingston Technology       | 1         | 0.35%   |
| GN Netcom                 | 1         | 0.35%   |
| Generalplus Technology    | 1         | 0.35%   |
| ASUSTek Computer          | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 25        | 7.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 4.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.76%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.76%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 3.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.18%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 2.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 2.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 2.6%    |
| AMD FCH Azalia Controller                                                                         | 8         | 2.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.02%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 2.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.02%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.73%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 1.73%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.45%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.45%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 1.16%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.16%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.87%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 28.99%  |
| SK hynix            | 45        | 21.74%  |
| Micron Technology   | 29        | 14.01%  |
| Unknown             | 17        | 8.21%   |
| Kingston            | 17        | 8.21%   |
| Crucial             | 11        | 5.31%   |
| Unknown (ABCD)      | 8         | 3.86%   |
| Ramaxel Technology  | 7         | 3.38%   |
| Nanya Technology    | 3         | 1.45%   |
| Corsair             | 3         | 1.45%   |
| Unknown             | 3         | 1.45%   |
| G.Skill             | 2         | 0.97%   |
| Elpida              | 1         | 0.48%   |
| A-DATA Technology   | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 7         | 3.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 3.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.25%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.35%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.35%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 3         | 1.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.35%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 1.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.35%   |
| Unknown                                                          | 3         | 1.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.9%    |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.9%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.9%    |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.9%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.9%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.9%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.9%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.9%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.9%    |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s            | 2         | 0.9%    |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.9%    |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.9%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.9%    |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.9%    |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                        | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.45%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                           | 1         | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.45%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.45%   |
| Unknown RAM Module 1GB DIMM DDR3 1600MT/s                        | 1         | 0.45%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 83        | 45.6%   |
| DDR3    | 56        | 30.77%  |
| LPDDR4  | 15        | 8.24%   |
| DDR2    | 10        | 5.49%   |
| SDRAM   | 7         | 3.85%   |
| LPDDR3  | 4         | 2.2%    |
| DDR5    | 4         | 2.2%    |
| LPDDR5  | 1         | 0.55%   |
| DDR     | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 86.41%  |
| Row Of Chips | 17        | 9.24%   |
| DIMM         | 3         | 1.63%   |
| Unknown      | 3         | 1.63%   |
| Chip         | 2         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 74        | 36.45%  |
| 4096  | 54        | 26.6%   |
| 16384 | 38        | 18.72%  |
| 2048  | 27        | 13.3%   |
| 1024  | 6         | 2.96%   |
| 32768 | 3         | 1.48%   |
| 12288 | 1         | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 49        | 25%     |
| 1600    | 41        | 20.92%  |
| 2667    | 23        | 11.73%  |
| 2400    | 22        | 11.22%  |
| 2133    | 9         | 4.59%   |
| Unknown | 6         | 3.06%   |
| 1334    | 5         | 2.55%   |
| 667     | 5         | 2.55%   |
| 4267    | 4         | 2.04%   |
| 2048    | 4         | 2.04%   |
| 1333    | 4         | 2.04%   |
| 1067    | 4         | 2.04%   |
| 4800    | 3         | 1.53%   |
| 4199    | 3         | 1.53%   |
| 1066    | 3         | 1.53%   |
| 800     | 3         | 1.53%   |
| 1867    | 2         | 1.02%   |
| 6400    | 1         | 0.51%   |
| 5600    | 1         | 0.51%   |
| 4266    | 1         | 0.51%   |
| 3266    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 975     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M2070 Series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 27.7%   |
| Realtek Semiconductor                  | 23        | 10.8%   |
| IMC Networks                           | 18        | 8.45%   |
| Microdia                               | 16        | 7.51%   |
| Bison Electronics                      | 14        | 6.57%   |
| Quanta                                 | 11        | 5.16%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.69%   |
| Syntek                                 | 9         | 4.23%   |
| Suyin                                  | 8         | 3.76%   |
| Sunplus Innovation Technology          | 8         | 3.76%   |
| Lite-On Technology                     | 5         | 2.35%   |
| Luxvisions Innotech Limited            | 3         | 1.41%   |
| Lenovo                                 | 3         | 1.41%   |
| Apple                                  | 3         | 1.41%   |
| Alcor Micro                            | 3         | 1.41%   |
| Silicon Motion                         | 2         | 0.94%   |
| Ricoh                                  | 2         | 0.94%   |
| Logitech                               | 2         | 0.94%   |
| Acer                                   | 2         | 0.94%   |
| Y Media                                | 1         | 0.47%   |
| SunplusIT                              | 1         | 0.47%   |
| Sonix Technology                       | 1         | 0.47%   |
| Razer USA                              | 1         | 0.47%   |
| OYT                                    | 1         | 0.47%   |
| OmniVision Technologies                | 1         | 0.47%   |
| Intel                                  | 1         | 0.47%   |
| icSpring                               | 1         | 0.47%   |
| Generalplus Technology                 | 1         | 0.47%   |
| eMPIA Technology                       | 1         | 0.47%   |
| Denron                                 | 1         | 0.47%   |
| ARC International                      | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HP HD Camera                                    | 10        | 4.69%   |
| Chicony Integrated Camera                               | 9         | 4.23%   |
| Realtek Integrated_Webcam_HD                            | 8         | 3.76%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 3.76%   |
| Syntek Integrated Camera                                | 7         | 3.29%   |
| IMC Networks Integrated Camera                          | 6         | 2.82%   |
| Bison Integrated Camera                                 | 5         | 2.35%   |
| Microdia Integrated_Webcam_HD                           | 4         | 1.88%   |
| Microdia Integrated Webcam                              | 4         | 1.88%   |
| Lite-On Integrated Camera                               | 4         | 1.88%   |
| Realtek USB Camera                                      | 3         | 1.41%   |
| Chicony TOSHIBA Web Camera - HD                         | 3         | 1.41%   |
| Chicony HP Wide Vision HD Camera                        | 3         | 1.41%   |
| Chicony HP Webcam                                       | 3         | 1.41%   |
| Chicony HP Truevision HD camera                         | 3         | 1.41%   |
| Chicony HD User Facing                                  | 3         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.94%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.94%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 0.94%   |
| Realtek USB2.0 camera                                   | 2         | 0.94%   |
| Realtek Acer 640 x 480 laptop camera                    | 2         | 0.94%   |
| Quanta ov9734_techfront_camera                          | 2         | 0.94%   |
| Quanta HP TrueVision HD Camera                          | 2         | 0.94%   |
| Quanta HD User Facing                                   | 2         | 0.94%   |
| Microdia Webcam Vitade AF                               | 2         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.94%   |
| Lenovo CNF7237&CNF7238                                  | 2         | 0.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 0.94%   |
| Chicony VGA Webcam                                      | 2         | 0.94%   |
| Chicony USB 2.0 Camera                                  | 2         | 0.94%   |
| Chicony Integrated IR Camera                            | 2         | 0.94%   |
| Chicony HP Truevision HD                                | 2         | 0.94%   |
| Chicony HP HD Webcam [Fixed]                            | 2         | 0.94%   |
| Chicony EasyCamera                                      | 2         | 0.94%   |
| Chicony Chicony USB2.0 Camera                           | 2         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 2         | 0.94%   |
| Bison Lenovo Integrated Webcam                          | 2         | 0.94%   |
| Apple Built-in iSight                                   | 2         | 0.94%   |
| Alcor Micro USB 2.0 Camera                              | 2         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 34.21%  |
| Shenzhen Goodix Technology | 7         | 18.42%  |
| Upek                       | 6         | 15.79%  |
| Synaptics                  | 6         | 15.79%  |
| Elan Microelectronics      | 4         | 10.53%  |
| AuthenTec                  | 2         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 13.16%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 13.16%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 10.53%  |
| Elan ELAN:ARM-M4                                                           | 4         | 10.53%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 5.26%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 5.26%   |
| AuthenTec AES1600                                                          | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.63%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 2.63%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.63%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 2.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.63%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 16        | 53.33%  |
| Alcor Micro           | 10        | 33.33%  |
| Upek                  | 1         | 3.33%   |
| SCM Microsystems      | 1         | 3.33%   |
| O2 Micro              | 1         | 3.33%   |
| Advanced Card Systems | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 33.33%  |
| Broadcom 58200                                                               | 6         | 20%     |
| Broadcom 5880                                                                | 4         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.33%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 3.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.33%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 147       | 62.82%  |
| 1     | 66        | 28.21%  |
| 2     | 18        | 7.69%   |
| 3     | 2         | 0.85%   |
| 4     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 38        | 35.19%  |
| Chipcard              | 28        | 25.93%  |
| Graphics card         | 15        | 13.89%  |
| Net/wireless          | 7         | 6.48%   |
| Bluetooth             | 7         | 6.48%   |
| Camera                | 5         | 4.63%   |
| Multimedia controller | 2         | 1.85%   |
| Card reader           | 2         | 1.85%   |
| Storage               | 1         | 0.93%   |
| Network               | 1         | 0.93%   |
| Flash memory          | 1         | 0.93%   |
| Dvb card              | 1         | 0.93%   |

