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

Total: 407

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 14        | 6.8%    |
| 5.15.0-58-generic    | 10        | 4.85%   |
| 6.2.0-36-generic     | 7         | 3.4%    |
| 5.15.0-53-generic    | 7         | 3.4%    |
| 5.15.0-52-generic    | 7         | 3.4%    |
| 5.15.0-43-generic    | 7         | 3.4%    |
| 5.15.0-25-generic    | 7         | 3.4%    |
| 5.15.0-47-generic    | 6         | 2.91%   |
| 5.15.0-46-generic    | 6         | 2.91%   |
| 6.2.0-34-generic     | 5         | 2.43%   |
| 6.2.0-32-generic     | 5         | 2.43%   |
| 5.19.0-46-generic    | 5         | 2.43%   |
| 5.19.0-32-generic    | 5         | 2.43%   |
| 5.15.0-60-generic    | 5         | 2.43%   |
| 5.15.0-48-generic    | 5         | 2.43%   |
| 6.2.0-39-generic     | 4         | 1.94%   |
| 6.2.0-26-generic     | 4         | 1.94%   |
| 5.15.0-40-generic    | 4         | 1.94%   |
| 6.2.0-37-generic     | 3         | 1.46%   |
| 6.2.0-35-generic     | 3         | 1.46%   |
| 6.2.0-33-generic     | 3         | 1.46%   |
| 5.19.0-43-generic    | 3         | 1.46%   |
| 5.19.0-42-generic    | 3         | 1.46%   |
| 5.19.0-38-generic    | 3         | 1.46%   |
| 5.19.0-35-generic    | 3         | 1.46%   |
| 5.15.0-91-generic    | 3         | 1.46%   |
| 5.15.0-83-generic    | 3         | 1.46%   |
| 5.15.0-67-generic    | 3         | 1.46%   |
| 5.15.0-57-generic    | 3         | 1.46%   |
| 5.15.0-41-generic    | 3         | 1.46%   |
| 5.15.0-30-generic    | 3         | 1.46%   |
| 5.15.0-27-generic    | 3         | 1.46%   |
| 5.19.0-50-generic    | 2         | 0.97%   |
| 5.15.0-88-generic    | 2         | 0.97%   |
| 5.15.0-84-generic    | 2         | 0.97%   |
| 5.15.0-79-generic    | 2         | 0.97%   |
| 5.15.0-76-generic    | 2         | 0.97%   |
| 5.15.0-69-generic    | 2         | 0.97%   |
| 5.15.0-52-lowlatency | 2         | 0.97%   |
| 6.5.0-15-generic     | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 111       | 61.33%  |
| 6.2.0   | 33        | 18.23%  |
| 5.19.0  | 25        | 13.81%  |
| 6.5.0   | 4         | 2.21%   |
| 6.2.3   | 1         | 0.55%   |
| 6.1.8   | 1         | 0.55%   |
| 6.0.8   | 1         | 0.55%   |
| 6.0.0   | 1         | 0.55%   |
| 5.18.0  | 1         | 0.55%   |
| 5.17.1  | 1         | 0.55%   |
| 5.17.0  | 1         | 0.55%   |
| 5.14.0  | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 111       | 61.33%  |
| 6.2     | 34        | 18.78%  |
| 5.19    | 25        | 13.81%  |
| 6.5     | 4         | 2.21%   |
| 6.0     | 2         | 1.1%    |
| 5.17    | 2         | 1.1%    |
| 6.1     | 1         | 0.55%   |
| 5.18    | 1         | 0.55%   |
| 5.14    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 171       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| MATE     | 169       | 98.83%  |
| GNOME    | 1         | 0.58%   |
| Cinnamon | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 167       | 97.66%  |
| Wayland | 2         | 1.17%   |
| Tty     | 2         | 1.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 144       | 83.72%  |
| Unknown | 18        | 10.47%  |
| GDM3    | 9         | 5.23%   |
| SDDM    | 1         | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 66        | 38.15%  |
| de_DE | 25        | 14.45%  |
| fr_FR | 22        | 12.72%  |
| it_IT | 12        | 6.94%   |
| ru_RU | 7         | 4.05%   |
| pl_PL | 4         | 2.31%   |
| es_ES | 4         | 2.31%   |
| pt_BR | 3         | 1.73%   |
| en_GB | 3         | 1.73%   |
| en_CA | 3         | 1.73%   |
| en_AU | 3         | 1.73%   |
| C     | 3         | 1.73%   |
| fi_FI | 2         | 1.16%   |
| es_MX | 2         | 1.16%   |
| en_IN | 2         | 1.16%   |
| zh_TW | 1         | 0.58%   |
| zh_CN | 1         | 0.58%   |
| pt_PT | 1         | 0.58%   |
| id_ID | 1         | 0.58%   |
| hu_HU | 1         | 0.58%   |
| es_VE | 1         | 0.58%   |
| es_CL | 1         | 0.58%   |
| es_AR | 1         | 0.58%   |
| en_NZ | 1         | 0.58%   |
| el_GR | 1         | 0.58%   |
| de_CH | 1         | 0.58%   |
| cs_CZ | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 94        | 53.71%  |
| BIOS | 81        | 46.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 142       | 82.08%  |
| Tmpfs   | 16        | 9.25%   |
| Overlay | 7         | 4.05%   |
| Zfs     | 3         | 1.73%   |
| Btrfs   | 2         | 1.16%   |
| Xfs     | 1         | 0.58%   |
| Jfs     | 1         | 0.58%   |
| Ext3    | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 134       | 77.01%  |
| Unknown | 25        | 14.37%  |
| MBR     | 15        | 8.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 151       | 88.3%   |
| Yes       | 20        | 11.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 64.16%  |
| Yes       | 62        | 35.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 35        | 20.47%  |
| Lenovo              | 34        | 19.88%  |
| Dell                | 23        | 13.45%  |
| ASUSTek Computer    | 18        | 10.53%  |
| Acer                | 11        | 6.43%   |
| Sony                | 5         | 2.92%   |
| Apple               | 5         | 2.92%   |
| HUAWEI              | 4         | 2.34%   |
| Google              | 3         | 1.75%   |
| Toshiba             | 2         | 1.17%   |
| Notebook            | 2         | 1.17%   |
| Intel               | 2         | 1.17%   |
| Clevo               | 2         | 1.17%   |
| VIT                 | 1         | 0.58%   |
| TrekStor            | 1         | 0.58%   |
| SLIMBOOK            | 1         | 0.58%   |
| Samsung Electronics | 1         | 0.58%   |
| Positivo            | 1         | 0.58%   |
| Panasonic           | 1         | 0.58%   |
| Packard Bell        | 1         | 0.58%   |
| MSI                 | 1         | 0.58%   |
| MicroByte           | 1         | 0.58%   |
| Medion              | 1         | 0.58%   |
| LincPlus            | 1         | 0.58%   |
| LG Electronics      | 1         | 0.58%   |
| Kiano               | 1         | 0.58%   |
| IPASON              | 1         | 0.58%   |
| Infinix             | 1         | 0.58%   |
| HYPERPC             | 1         | 0.58%   |
| HONOR               | 1         | 0.58%   |
| GPU Company         | 1         | 0.58%   |
| GPD                 | 1         | 0.58%   |
| Gigabyte Technology | 1         | 0.58%   |
| Compaq              | 1         | 0.58%   |
| Chuwi               | 1         | 0.58%   |
| Bluechip Computer   | 1         | 0.58%   |
| BANGHO              | 1         | 0.58%   |
| AZW                 | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell Precision 7520                   | 2         | 1.17%   |
| Dell Latitude 7420                    | 2         | 1.17%   |
| VIT P1400                             | 1         | 0.58%   |
| TrekStor Surfbook A13B                | 1         | 0.58%   |
| Toshiba Satellite P50-B-10Z           | 1         | 0.58%   |
| Toshiba Satellite C50D-A-133          | 1         | 0.58%   |
| Sony VPCEH1E1E                        | 1         | 0.58%   |
| Sony VPCEB2Z1E                        | 1         | 0.58%   |
| Sony VPCEA36FG                        | 1         | 0.58%   |
| Sony VGN-Z21WRN_B                     | 1         | 0.58%   |
| Sony SVF13N2J2ES                      | 1         | 0.58%   |
| SLIMBOOK TITAN                        | 1         | 0.58%   |
| Samsung 905S3G/906S3G/915S3G/9305SG   | 1         | 0.58%   |
| Positivo C4128G-15                    | 1         | 0.58%   |
| Panasonic CF-53SJCZYLM                | 1         | 0.58%   |
| Packard Bell EasyNote ENTG81BA        | 1         | 0.58%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 0.58%   |
| Notebook NJx0MU                       | 1         | 0.58%   |
| MSI GF65 Thin 10SDR                   | 1         | 0.58%   |
| MicroByte ezbook                      | 1         | 0.58%   |
| Medion S6445 MD61281                  | 1         | 0.58%   |
| LincPlus LINNCPLUS P1                 | 1         | 0.58%   |
| LG 17Z990-R.AAS8U1                    | 1         | 0.58%   |
| Lenovo V15 G2 ITL 82KB                | 1         | 0.58%   |
| Lenovo V15 G2 ALC 82KD                | 1         | 0.58%   |
| Lenovo V145-15AST 81MT                | 1         | 0.58%   |
| Lenovo ThinkPad X270 W10DG 20K5S0B700 | 1         | 0.58%   |
| Lenovo ThinkPad X230 2325Y5L          | 1         | 0.58%   |
| Lenovo ThinkPad X200 74595FG          | 1         | 0.58%   |
| Lenovo ThinkPad T580 20LAS0DL00       | 1         | 0.58%   |
| Lenovo ThinkPad T490s 20NYS58200      | 1         | 0.58%   |
| Lenovo ThinkPad T460p 20FW002CPB      | 1         | 0.58%   |
| Lenovo ThinkPad T430 2347G5U          | 1         | 0.58%   |
| Lenovo ThinkPad T420 4238LY7          | 1         | 0.58%   |
| Lenovo ThinkPad T420 4236MBG          | 1         | 0.58%   |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00  | 1         | 0.58%   |
| Lenovo ThinkPad SL500 27463ZG         | 1         | 0.58%   |
| Lenovo ThinkPad SL 2746AHG            | 1         | 0.58%   |
| Lenovo ThinkPad R61 8918DEG           | 1         | 0.58%   |
| Lenovo ThinkPad P53 20QN000FIX        | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 9.94%   |
| Dell Latitude          | 9         | 5.26%   |
| Lenovo IdeaPad         | 8         | 4.68%   |
| HP ProBook             | 6         | 3.51%   |
| HP Pavilion            | 6         | 3.51%   |
| Dell Precision         | 6         | 3.51%   |
| Acer Aspire            | 6         | 3.51%   |
| ASUS VivoBook          | 5         | 2.92%   |
| HP EliteBook           | 4         | 2.34%   |
| HP Laptop              | 3         | 1.75%   |
| Dell Inspiron          | 3         | 1.75%   |
| ASUS ASUS              | 3         | 1.75%   |
| Toshiba Satellite      | 2         | 1.17%   |
| Lenovo V15             | 2         | 1.17%   |
| Lenovo ThinkBook       | 2         | 1.17%   |
| Lenovo Legion          | 2         | 1.17%   |
| HP ZBook               | 2         | 1.17%   |
| HP Stream              | 2         | 1.17%   |
| HP OMEN                | 2         | 1.17%   |
| HP 15                  | 2         | 1.17%   |
| Dell XPS               | 2         | 1.17%   |
| Dell Vostro            | 2         | 1.17%   |
| Acer TravelMate        | 2         | 1.17%   |
| Acer Extensa           | 2         | 1.17%   |
| VIT P1400              | 1         | 0.58%   |
| TrekStor Surfbook      | 1         | 0.58%   |
| Sony VPCEH1E1E         | 1         | 0.58%   |
| Sony VPCEB2Z1E         | 1         | 0.58%   |
| Sony VPCEA36FG         | 1         | 0.58%   |
| Sony VGN-Z21WRN        | 1         | 0.58%   |
| Sony SVF13N2J2ES       | 1         | 0.58%   |
| SLIMBOOK TITAN         | 1         | 0.58%   |
| Samsung 905S3G         | 1         | 0.58%   |
| Positivo C4128G-15     | 1         | 0.58%   |
| Panasonic CF-53SJCZYLM | 1         | 0.58%   |
| Packard Bell EasyNote  | 1         | 0.58%   |
| Notebook NV4XMB        | 1         | 0.58%   |
| Notebook NJx0MU        | 1         | 0.58%   |
| MSI GF65               | 1         | 0.58%   |
| MicroByte ezbook       | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 32        | 18.71%  |
| 2019    | 15        | 8.77%   |
| 2020    | 13        | 7.6%    |
| 2018    | 13        | 7.6%    |
| 2022    | 11        | 6.43%   |
| 2016    | 10        | 5.85%   |
| 2014    | 10        | 5.85%   |
| 2013    | 10        | 5.85%   |
| 2008    | 10        | 5.85%   |
| 2015    | 8         | 4.68%   |
| 2011    | 8         | 4.68%   |
| 2017    | 7         | 4.09%   |
| 2012    | 7         | 4.09%   |
| 2009    | 6         | 3.51%   |
| 2010    | 5         | 2.92%   |
| 2023    | 2         | 1.17%   |
| 2007    | 2         | 1.17%   |
| 2006    | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 171       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 157       | 90.23%  |
| Enabled  | 17        | 9.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 168       | 98.25%  |
| Yes  | 3         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 28.65%  |
| 3.01-4.0    | 41        | 23.98%  |
| 16.01-24.0  | 30        | 17.54%  |
| 8.01-16.0   | 22        | 12.87%  |
| 32.01-64.0  | 14        | 8.19%   |
| 24.01-32.0  | 5         | 2.92%   |
| 1.01-2.0    | 4         | 2.34%   |
| 2.01-3.0    | 3         | 1.75%   |
| 64.01-256.0 | 3         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 65        | 34.76%  |
| 2.01-3.0   | 50        | 26.74%  |
| 3.01-4.0   | 34        | 18.18%  |
| 4.01-8.0   | 22        | 11.76%  |
| 8.01-16.0  | 10        | 5.35%   |
| 0.51-1.0   | 5         | 2.67%   |
| 24.01-32.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 77.19%  |
| 2      | 30        | 17.54%  |
| 3      | 8         | 4.68%   |
| 4      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 65.5%   |
| Yes       | 59        | 34.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 76.02%  |
| No        | 41        | 23.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 98.25%  |
| No        | 3         | 1.75%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 83.82%  |
| No        | 28        | 16.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 26        | 15.2%   |
| France             | 23        | 13.45%  |
| USA                | 22        | 12.87%  |
| Italy              | 14        | 8.19%   |
| Spain              | 7         | 4.09%   |
| Russia             | 7         | 4.09%   |
| Brazil             | 6         | 3.51%   |
| Poland             | 5         | 2.92%   |
| UK                 | 4         | 2.34%   |
| India              | 4         | 2.34%   |
| Turkey             | 3         | 1.75%   |
| Indonesia          | 3         | 1.75%   |
| Finland            | 3         | 1.75%   |
| Thailand           | 2         | 1.17%   |
| Serbia             | 2         | 1.17%   |
| Romania            | 2         | 1.17%   |
| Portugal           | 2         | 1.17%   |
| Mexico             | 2         | 1.17%   |
| Hungary            | 2         | 1.17%   |
| Greece             | 2         | 1.17%   |
| Estonia            | 2         | 1.17%   |
| Chile              | 2         | 1.17%   |
| Belgium            | 2         | 1.17%   |
| Austria            | 2         | 1.17%   |
| Australia          | 2         | 1.17%   |
| Venezuela          | 1         | 0.58%   |
| Ukraine            | 1         | 0.58%   |
| Taiwan             | 1         | 0.58%   |
| Switzerland        | 1         | 0.58%   |
| Slovenia           | 1         | 0.58%   |
| Peru               | 1         | 0.58%   |
| Paraguay           | 1         | 0.58%   |
| New Zealand        | 1         | 0.58%   |
| Netherlands        | 1         | 0.58%   |
| Libya              | 1         | 0.58%   |
| Hong Kong          | 1         | 0.58%   |
| Georgia            | 1         | 0.58%   |
| Dominican Republic | 1         | 0.58%   |
| Czechia            | 1         | 0.58%   |
| Costa Rica         | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 5         | 2.81%   |
| Warsaw            | 4         | 2.25%   |
| Wittingen         | 3         | 1.69%   |
| Moscow            | 3         | 1.69%   |
| Mannheim          | 3         | 1.69%   |
| Vienna            | 2         | 1.12%   |
| Lisbon            | 2         | 1.12%   |
| Hyderabad         | 2         | 1.12%   |
| Hamburg           | 2         | 1.12%   |
| Greenville        | 2         | 1.12%   |
| Frankfurt am Main | 2         | 1.12%   |
| Berlin            | 2         | 1.12%   |
| Belgrade          | 2         | 1.12%   |
| Bangkok           | 2         | 1.12%   |
| Xining            | 1         | 0.56%   |
| Wellin            | 1         | 0.56%   |
| Weiden            | 1         | 0.56%   |
| Voronezh          | 1         | 0.56%   |
| Viroflay          | 1         | 0.56%   |
| Villeurbanne      | 1         | 0.56%   |
| Vaudoy-en-Brie    | 1         | 0.56%   |
| Varna             | 1         | 0.56%   |
| Valenciennes      | 1         | 0.56%   |
| Valence           | 1         | 0.56%   |
| Turku             | 1         | 0.56%   |
| Turin             | 1         | 0.56%   |
| Tulungagung       | 1         | 0.56%   |
| Tula              | 1         | 0.56%   |
| Tripoli           | 1         | 0.56%   |
| Tours             | 1         | 0.56%   |
| Toulouse          | 1         | 0.56%   |
| Tizayuca          | 1         | 0.56%   |
| Thane             | 1         | 0.56%   |
| Tartu             | 1         | 0.56%   |
| Taoyuan District  | 1         | 0.56%   |
| Talcahuano        | 1         | 0.56%   |
| Seville           | 1         | 0.56%   |
| Settimo Torinese  | 1         | 0.56%   |
| Sarzeau           | 1         | 0.56%   |
| Sarospatak        | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 43        | 75     | 20.38%  |
| Unknown               | 18        | 21     | 8.53%   |
| WDC                   | 17        | 18     | 8.06%   |
| Seagate               | 17        | 18     | 8.06%   |
| Toshiba               | 12        | 16     | 5.69%   |
| SK hynix              | 10        | 10     | 4.74%   |
| SanDisk               | 10        | 12     | 4.74%   |
| Kingston              | 10        | 11     | 4.74%   |
| Crucial               | 10        | 12     | 4.74%   |
| Intel                 | 6         | 6      | 2.84%   |
| A-DATA Technology     | 5         | 5      | 2.37%   |
| Hitachi               | 4         | 4      | 1.9%    |
| HGST                  | 4         | 4      | 1.9%    |
| China                 | 4         | 5      | 1.9%    |
| SPCC                  | 3         | 5      | 1.42%   |
| Phison                | 3         | 3      | 1.42%   |
| Micron Technology     | 3         | 3      | 1.42%   |
| KIOXIA                | 3         | 3      | 1.42%   |
| UMIS                  | 2         | 3      | 0.95%   |
| KingSpec              | 2         | 3      | 0.95%   |
| Apple                 | 2         | 2      | 0.95%   |
| WDC WDS2              | 1         | 1      | 0.47%   |
| Verbatim              | 1         | 7      | 0.47%   |
| Silicon Motion        | 1         | 1      | 0.47%   |
| Realtek Semiconductor | 1         | 2      | 0.47%   |
| PNY                   | 1         | 1      | 0.47%   |
| Phison Electronics    | 1         | 1      | 0.47%   |
| Patriot               | 1         | 1      | 0.47%   |
| OCZ                   | 1         | 1      | 0.47%   |
| Netac                 | 1         | 1      | 0.47%   |
| LITEONIT              | 1         | 1      | 0.47%   |
| Lenovo                | 1         | 1      | 0.47%   |
| Kston                 | 1         | 1      | 0.47%   |
| KingFast              | 1         | 1      | 0.47%   |
| JMicron Technology    | 1         | 1      | 0.47%   |
| Intenso               | 1         | 1      | 0.47%   |
| Hjwdz                 | 1         | 1      | 0.47%   |
| Gigabyte Technology   | 1         | 1      | 0.47%   |
| FORESEE               | 1         | 1      | 0.47%   |
| faspeed               | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                             | 3         | 1.36%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 1.36%   |
| Seagate ST500LT012-1DG142 500GB                    | 3         | 1.36%   |
| Samsung MZVLQ512HALU-000H1 512GB                   | 3         | 1.36%   |
| Kingston SA400S37240G 240GB SSD                    | 3         | 1.36%   |
| Unknown SLD64G  64GB                               | 2         | 0.9%    |
| Unknown MMC Card  64GB                             | 2         | 0.9%    |
| Seagate ST9500420AS 500GB                          | 2         | 0.9%    |
| Seagate ST2000LM015-2E8174 2TB                     | 2         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                     | 2         | 0.9%    |
| Seagate Expansion 1TB                              | 2         | 0.9%    |
| Samsung SSD 980 PRO 1TB                            | 2         | 0.9%    |
| Samsung SSD 980 1TB                                | 2         | 0.9%    |
| Samsung SSD 860 EVO 250GB                          | 2         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 0.9%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 2         | 0.9%    |
| Samsung MZVLQ512HBLU-00BH1 512GB                   | 2         | 0.9%    |
| Samsung MZALQ512HBLU-00BL2 512GB                   | 2         | 0.9%    |
| Kingston SA400S37480G 480GB SSD                    | 2         | 0.9%    |
| Crucial CT240BX500SSD1 240GB                       | 2         | 0.9%    |
| Crucial CT1000BX500SSD1 1TB                        | 2         | 0.9%    |
| WDC WDS2 50G2B0B-00YS 250GB SSD                    | 1         | 0.45%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                     | 1         | 0.45%   |
| WDC WD7500BPVX-60JC3T0 752GB                       | 1         | 0.45%   |
| WDC WD5000LPVX-60V0TT0 500GB                       | 1         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 1         | 0.45%   |
| WDC WD5000LPCX-22VHAT0 500GB                       | 1         | 0.45%   |
| WDC WD5000LPCX-21VHAT0 500GB                       | 1         | 0.45%   |
| WDC WD40 EFRX-68N32N0 4TB                          | 1         | 0.45%   |
| WDC WD3200BEVT-22ZCT0 320GB                        | 1         | 0.45%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 0.45%   |
| WDC WD10SPZX-22Z10T0 1TB                           | 1         | 0.45%   |
| WDC WD10SPCX-24HWST1 1TB                           | 1         | 0.45%   |
| WDC WD Blue SA510 M.2 2280 500GB                   | 1         | 0.45%   |
| WDC WD Blue SA510 2.5 500GB                        | 1         | 0.45%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 1         | 0.45%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 1         | 0.45%   |
| WDC PC SN530 NVMe 256GB                            | 1         | 0.45%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB               | 1         | 0.45%   |
| Verbatim Vi550 S3 512GB SSD                        | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 17        | 18     | 38.64%  |
| WDC                | 10        | 11     | 22.73%  |
| Toshiba            | 8         | 11     | 18.18%  |
| Hitachi            | 4         | 4      | 9.09%   |
| HGST               | 4         | 4      | 9.09%   |
| JMicron Technology | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 22        | 25     | 27.5%   |
| Crucial             | 10        | 12     | 12.5%   |
| Kingston            | 9         | 10     | 11.25%  |
| SanDisk             | 5         | 6      | 6.25%   |
| China               | 4         | 5      | 5%      |
| A-DATA Technology   | 4         | 4      | 5%      |
| WDC                 | 3         | 3      | 3.75%   |
| SPCC                | 2         | 4      | 2.5%    |
| KingSpec            | 2         | 3      | 2.5%    |
| Intel               | 2         | 2      | 2.5%    |
| WDC WDS2            | 1         | 1      | 1.25%   |
| Verbatim            | 1         | 7      | 1.25%   |
| Toshiba             | 1         | 2      | 1.25%   |
| SK hynix            | 1         | 1      | 1.25%   |
| PNY                 | 1         | 1      | 1.25%   |
| Phison              | 1         | 1      | 1.25%   |
| Patriot             | 1         | 1      | 1.25%   |
| OCZ                 | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| LITEONIT            | 1         | 1      | 1.25%   |
| Kston               | 1         | 1      | 1.25%   |
| KingFast            | 1         | 1      | 1.25%   |
| Intenso             | 1         | 1      | 1.25%   |
| Corsair             | 1         | 1      | 1.25%   |
| Apple               | 1         | 1      | 1.25%   |
| addlink             | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 72        | 98     | 35.82%  |
| NVMe    | 68        | 101    | 33.83%  |
| HDD     | 42        | 49     | 20.9%   |
| MMC     | 16        | 19     | 7.96%   |
| Unknown | 3         | 3      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 135    | 51.01%  |
| NVMe | 68        | 101    | 34.34%  |
| MMC  | 16        | 19     | 8.08%   |
| SAS  | 13        | 15     | 6.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 93     | 68.42%  |
| 0.51-1.0   | 25        | 35     | 21.93%  |
| 1.01-2.0   | 8         | 15     | 7.02%   |
| 3.01-4.0   | 2         | 2      | 1.75%   |
| 4.01-10.0  | 1         | 2      | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 52        | 29.38%  |
| 251-500        | 47        | 26.55%  |
| 501-1000       | 22        | 12.43%  |
| 51-100         | 15        | 8.47%   |
| 1001-2000      | 13        | 7.34%   |
| 21-50          | 9         | 5.08%   |
| 1-20           | 9         | 5.08%   |
| 2001-3000      | 5         | 2.82%   |
| More than 3000 | 4         | 2.26%   |
| Unknown        | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 52        | 29.21%  |
| 21-50          | 35        | 19.66%  |
| 101-250        | 31        | 17.42%  |
| 51-100         | 23        | 12.92%  |
| 251-500        | 18        | 10.11%  |
| 501-1000       | 8         | 4.49%   |
| 1001-2000      | 5         | 2.81%   |
| 2001-3000      | 3         | 1.69%   |
| More than 3000 | 2         | 1.12%   |
| Unknown        | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 13.33%  |
| WDC WD7500BPVX-60JC3T0 752GB                 | 1         | 2      | 6.67%   |
| WDC WD40 EFRX-68N32N0 4TB                    | 1         | 1      | 6.67%   |
| Toshiba MK3263GSXN 320GB                     | 1         | 1      | 6.67%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 6.67%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 6.67%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 6.67%   |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 6.67%   |
| Netac SSD 256GB                              | 1         | 1      | 6.67%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 6.67%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 6.67%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 26.67%  |
| WDC                 | 2         | 3      | 13.33%  |
| Toshiba             | 1         | 1      | 6.67%   |
| SK hynix            | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |
| OCZ                 | 1         | 1      | 6.67%   |
| Netac               | 1         | 1      | 6.67%   |
| Kingston            | 1         | 1      | 6.67%   |
| Intel               | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 44.44%  |
| WDC     | 2         | 3      | 22.22%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |
| HGST    | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 10     | 60%     |
| SSD  | 4         | 4      | 26.67%  |
| NVMe | 2         | 2      | 13.33%  |

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
| Works    | 101       | 138    | 53.16%  |
| Detected | 74        | 116    | 38.95%  |
| Malfunc  | 15        | 16     | 7.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 110       | 54.19%  |
| Samsung Electronics          | 25        | 12.32%  |
| AMD                          | 21        | 10.34%  |
| SK hynix                     | 9         | 4.43%   |
| Sandisk                      | 9         | 4.43%   |
| Phison Electronics           | 4         | 1.97%   |
| KIOXIA                       | 4         | 1.97%   |
| Toshiba America Info Systems | 3         | 1.48%   |
| Nvidia                       | 3         | 1.48%   |
| Union Memory (Shenzhen)      | 2         | 0.99%   |
| Micron Technology            | 2         | 0.99%   |
| ADATA Technology             | 2         | 0.99%   |
| Silicon Motion               | 1         | 0.49%   |
| Shenzhen Longsys Electronics | 1         | 0.49%   |
| Realtek Semiconductor        | 1         | 0.49%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.49%   |
| Marvell Technology Group     | 1         | 0.49%   |
| Lenovo                       | 1         | 0.49%   |
| Kingston Technology Company  | 1         | 0.49%   |
| Biwin Storage Technology     | 1         | 0.49%   |
| Unknown                      | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 7.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 14        | 6.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 5.14%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 9         | 4.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 7         | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 3.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 2.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 6         | 2.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 2.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 2.34%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 3         | 1.4%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.4%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 1.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.4%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 2         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 2         | 0.93%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 2         | 0.93%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 2         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.93%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 2         | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 112       | 54.37%  |
| NVMe | 68        | 33.01%  |
| RAID | 17        | 8.25%   |
| IDE  | 9         | 4.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 80.12%  |
| AMD    | 34        | 19.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.75%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 3         | 1.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.75%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.75%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 1.17%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 1.17%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.17%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 2         | 1.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.17%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.17%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.17%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.17%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.17%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.17%   |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 2         | 1.17%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.17%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.17%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 1.17%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.58%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.58%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.58%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.58%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.58%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.58%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.58%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 35        | 20.47%  |
| Intel Core i5           | 27        | 15.79%  |
| Other                   | 21        | 12.28%  |
| Intel Celeron           | 19        | 11.11%  |
| Intel Core i3           | 10        | 5.85%   |
| Intel Core 2 Duo        | 10        | 5.85%   |
| Intel Pentium           | 7         | 4.09%   |
| AMD Ryzen 7             | 7         | 4.09%   |
| AMD Ryzen 5             | 6         | 3.51%   |
| Intel Pentium Silver    | 3         | 1.75%   |
| Intel Pentium Dual-Core | 3         | 1.75%   |
| AMD A6                  | 3         | 1.75%   |
| AMD Ryzen 9             | 2         | 1.17%   |
| AMD Ryzen 7 PRO         | 2         | 1.17%   |
| AMD Ryzen 3             | 2         | 1.17%   |
| AMD A4                  | 2         | 1.17%   |
| Intel Xeon              | 1         | 0.58%   |
| Intel Core m5           | 1         | 0.58%   |
| Intel Atom              | 1         | 0.58%   |
| AMD Turion 64 X2 Mobile | 1         | 0.58%   |
| AMD Turion 64 Mobile    | 1         | 0.58%   |
| AMD Sempron             | 1         | 0.58%   |
| AMD Ryzen 5 PRO         | 1         | 0.58%   |
| AMD Quad-Core           | 1         | 0.58%   |
| AMD E1                  | 1         | 0.58%   |
| AMD Athlon X2           | 1         | 0.58%   |
| AMD Athlon II           | 1         | 0.58%   |
| AMD A8                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 79        | 46.2%   |
| 4      | 62        | 36.26%  |
| 8      | 13        | 7.6%    |
| 6      | 11        | 6.43%   |
| 14     | 3         | 1.75%   |
| 1      | 2         | 1.17%   |
| 10     | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 171       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 113       | 66.08%  |
| 1      | 58        | 33.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 171       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 47.75%  |
| 0x806c1    | 8         | 4.49%   |
| 0x806ec    | 6         | 3.37%   |
| 0x40651    | 6         | 3.37%   |
| 0x306a9    | 6         | 3.37%   |
| 0x1067a    | 5         | 2.81%   |
| 0x806d1    | 4         | 2.25%   |
| 0x0a50000c | 4         | 2.25%   |
| 0x906a3    | 3         | 1.69%   |
| 0x706a8    | 3         | 1.69%   |
| 0x506c9    | 3         | 1.69%   |
| 0x406e3    | 3         | 1.69%   |
| 0x406c4    | 3         | 1.69%   |
| 0x30678    | 3         | 1.69%   |
| 0x206a7    | 3         | 1.69%   |
| 0x08108109 | 3         | 1.69%   |
| 0x0700010f | 3         | 1.69%   |
| 0x906c0    | 2         | 1.12%   |
| 0x806e9    | 2         | 1.12%   |
| 0x706e5    | 2         | 1.12%   |
| 0x10676    | 2         | 1.12%   |
| 0x08608103 | 2         | 1.12%   |
| 0x906e9    | 1         | 0.56%   |
| 0x906a4    | 1         | 0.56%   |
| 0x806eb    | 1         | 0.56%   |
| 0x806ea    | 1         | 0.56%   |
| 0x706a1    | 1         | 0.56%   |
| 0x6fd      | 1         | 0.56%   |
| 0x6fb      | 1         | 0.56%   |
| 0x506e3    | 1         | 0.56%   |
| 0x20655    | 1         | 0.56%   |
| 0x0a601203 | 1         | 0.56%   |
| 0x0a50000d | 1         | 0.56%   |
| 0x08608102 | 1         | 0.56%   |
| 0x08101016 | 1         | 0.56%   |
| 0x07030105 | 1         | 0.56%   |
| 0x0600611a | 1         | 0.56%   |
| 0x02000032 | 1         | 0.56%   |
| 0x010000c8 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 12.79%  |
| Silvermont       | 12        | 6.98%   |
| Haswell          | 12        | 6.98%   |
| TigerLake        | 11        | 6.4%    |
| IvyBridge        | 11        | 6.4%    |
| SandyBridge      | 10        | 5.81%   |
| Penryn           | 10        | 5.81%   |
| Skylake          | 9         | 5.23%   |
| IceLake          | 9         | 5.23%   |
| Unknown          | 8         | 4.65%   |
| Goldmont plus    | 7         | 4.07%   |
| Zen 3            | 6         | 3.49%   |
| Zen+             | 4         | 2.33%   |
| Excavator        | 4         | 2.33%   |
| Alderlake Hybrid | 4         | 2.33%   |
| Zen 2            | 3         | 1.74%   |
| Westmere         | 3         | 1.74%   |
| Jaguar           | 3         | 1.74%   |
| Goldmont         | 3         | 1.74%   |
| Core             | 3         | 1.74%   |
| CometLake        | 3         | 1.74%   |
| Zen              | 2         | 1.16%   |
| Tremont          | 2         | 1.16%   |
| Puma             | 2         | 1.16%   |
| Nehalem          | 2         | 1.16%   |
| K8 Hammer        | 2         | 1.16%   |
| K10              | 2         | 1.16%   |
| Broadwell        | 2         | 1.16%   |
| K8 & K10 hybrid  | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 57.89%  |
| Nvidia | 45        | 21.53%  |
| AMD    | 43        | 20.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 4.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.9%    |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 1.9%    |
| Intel HD Graphics 530                                                                    | 4         | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.9%    |
| AMD Lucienne                                                                             | 4         | 1.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.42%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.42%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.42%   |
| Intel HD Graphics 620                                                                    | 3         | 1.42%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.42%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.42%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.95%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.95%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.95%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.95%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.95%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.95%   |
| Intel HD Graphics 500                                                                    | 2         | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.95%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.95%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.95%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.95%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.95%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.95%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 52.05%  |
| 1 x AMD        | 29        | 16.96%  |
| Intel + Nvidia | 25        | 14.62%  |
| 1 x Nvidia     | 14        | 8.19%   |
| Intel + AMD    | 7         | 4.09%   |
| AMD + Nvidia   | 6         | 3.51%   |
| 2 x AMD        | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 137       | 80.12%  |
| Proprietary | 30        | 17.54%  |
| Unknown     | 4         | 2.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 74.42%  |
| 0.01-0.5   | 19        | 11.05%  |
| 1.01-2.0   | 8         | 4.65%   |
| 0.51-1.0   | 8         | 4.65%   |
| 3.01-4.0   | 4         | 2.33%   |
| 5.01-6.0   | 3         | 1.74%   |
| 7.01-8.0   | 1         | 0.58%   |
| 8.01-16.0  | 1         | 0.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 34        | 17.09%  |
| Chimei Innolux          | 28        | 14.07%  |
| LG Display              | 26        | 13.07%  |
| AU Optronics            | 24        | 12.06%  |
| Samsung Electronics     | 21        | 10.55%  |
| Dell                    | 6         | 3.02%   |
| PANDA                   | 5         | 2.51%   |
| Lenovo                  | 5         | 2.51%   |
| Apple                   | 5         | 2.51%   |
| Sharp                   | 4         | 2.01%   |
| Chi Mei Optoelectronics | 4         | 2.01%   |
| BenQ                    | 3         | 1.51%   |
| AOC                     | 3         | 1.51%   |
| Ancor Communications    | 3         | 1.51%   |
| Sony                    | 2         | 1.01%   |
| Philips                 | 2         | 1.01%   |
| Iiyama                  | 2         | 1.01%   |
| Hewlett-Packard         | 2         | 1.01%   |
| Goldstar                | 2         | 1.01%   |
| CSO                     | 2         | 1.01%   |
| ViewSonic               | 1         | 0.5%    |
| Unknown                 | 1         | 0.5%    |
| Toshiba                 | 1         | 0.5%    |
| Sceptre Tech            | 1         | 0.5%    |
| Quanta Display          | 1         | 0.5%    |
| Panasonic               | 1         | 0.5%    |
| LGD                     | 1         | 0.5%    |
| LG Philips              | 1         | 0.5%    |
| IBM                     | 1         | 0.5%    |
| HJC                     | 1         | 0.5%    |
| Hitachi                 | 1         | 0.5%    |
| HannStar                | 1         | 0.5%    |
| Eizo                    | 1         | 0.5%    |
| CS_                     | 1         | 0.5%    |
| ASUSTek Computer        | 1         | 0.5%    |
| Acer                    | 1         | 0.5%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                  | 2         | 1%      |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch   | 2         | 1%      |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 2         | 1%      |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                  | 2         | 1%      |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                  | 2         | 1%      |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                  | 2         | 1%      |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                  | 2         | 1%      |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                   | 2         | 1%      |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                 | 2         | 1%      |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 600x340mm 27.2-inch          | 1         | 0.5%    |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                   | 1         | 0.5%    |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch               | 1         | 0.5%    |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch                | 1         | 0.5%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                | 1         | 0.5%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.5%    |
| Sharp HDMI SHP10E8 1360x768 521x293mm 23.5-inch                        | 1         | 0.5%    |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch         | 1         | 0.5%    |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch    | 1         | 0.5%    |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch     | 1         | 0.5%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 1         | 0.5%    |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch      | 1         | 0.5%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.5%    |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1210x680mm 54.6-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 1         | 0.5%    |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch        | 1         | 0.5%    |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                    | 1         | 0.5%    |
| Philips 239CQH PHLC0A0 1920x1080 509x286mm 23.0-inch                   | 1         | 0.5%    |
| PANDA LCD Monitor NCP004F 1920x1080 309x174mm 14.0-inch                | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 80        | 43.96%  |
| 1366x768 (WXGA)    | 52        | 28.57%  |
| 2560x1440 (QHD)    | 9         | 4.95%   |
| 1280x800 (WXGA)    | 8         | 4.4%    |
| 3840x2160 (4K)     | 7         | 3.85%   |
| 1600x900 (HD+)     | 5         | 2.75%   |
| 1440x900 (WXGA+)   | 5         | 2.75%   |
| 2560x1600          | 4         | 2.2%    |
| 1920x1200 (WUXGA)  | 3         | 1.65%   |
| 3840x2400          | 2         | 1.1%    |
| 2160x1440          | 2         | 1.1%    |
| 1680x1050 (WSXGA+) | 2         | 1.1%    |
| 2880x1800          | 1         | 0.55%   |
| 2880x1620          | 1         | 0.55%   |
| 1360x768           | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 76        | 38.19%  |
| 14      | 25        | 12.56%  |
| 13      | 23        | 11.56%  |
| 17      | 15        | 7.54%   |
| 27      | 14        | 7.04%   |
| 24      | 10        | 5.03%   |
| 12      | 7         | 3.52%   |
| 23      | 6         | 3.02%   |
| 16      | 4         | 2.01%   |
| 11      | 4         | 2.01%   |
| 21      | 3         | 1.51%   |
| 84      | 2         | 1.01%   |
| 54      | 2         | 1.01%   |
| 31      | 2         | 1.01%   |
| 40      | 1         | 0.5%    |
| 25      | 1         | 0.5%    |
| 22      | 1         | 0.5%    |
| 18      | 1         | 0.5%    |
| 10      | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 120       | 61.22%  |
| 501-600     | 28        | 14.29%  |
| 201-300     | 19        | 9.69%   |
| 351-400     | 15        | 7.65%   |
| 401-500     | 5         | 2.55%   |
| 601-700     | 3         | 1.53%   |
| 1501-2000   | 2         | 1.02%   |
| 1001-1500   | 2         | 1.02%   |
| 801-900     | 1         | 0.51%   |
| Unknown     | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 139       | 83.23%  |
| 16/10   | 25        | 14.97%  |
| 3/2     | 2         | 1.2%    |
| Unknown | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 36.87%  |
| 81-90          | 44        | 22.22%  |
| 201-250        | 16        | 8.08%   |
| 301-350        | 14        | 7.07%   |
| 121-130        | 13        | 6.57%   |
| 61-70          | 7         | 3.54%   |
| More than 1000 | 4         | 2.02%   |
| 71-80          | 4         | 2.02%   |
| 51-60          | 4         | 2.02%   |
| 251-300        | 4         | 2.02%   |
| 111-120        | 4         | 2.02%   |
| 91-100         | 3         | 1.52%   |
| 351-500        | 2         | 1.01%   |
| 131-140        | 2         | 1.01%   |
| 41-50          | 1         | 0.51%   |
| 141-150        | 1         | 0.51%   |
| 501-1000       | 1         | 0.51%   |
| Unknown        | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 40.84%  |
| 101-120       | 52        | 27.23%  |
| 51-100        | 36        | 18.85%  |
| 161-240       | 17        | 8.9%    |
| More than 240 | 4         | 2.09%   |
| 1-50          | 3         | 1.57%   |
| Unknown       | 1         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 133       | 77.33%  |
| 2     | 28        | 16.28%  |
| 3     | 6         | 3.49%   |
| 0     | 4         | 2.33%   |
| 4     | 1         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 97        | 37.16%  |
| Intel                             | 94        | 36.02%  |
| Qualcomm Atheros                  | 26        | 9.96%   |
| Broadcom                          | 13        | 4.98%   |
| ASIX Electronics                  | 5         | 1.92%   |
| Ralink                            | 3         | 1.15%   |
| Broadcom Limited                  | 3         | 1.15%   |
| Nvidia                            | 2         | 0.77%   |
| MediaTek                          | 2         | 0.77%   |
| Marvell Technology Group          | 2         | 0.77%   |
| JMicron Technology                | 2         | 0.77%   |
| Ericsson Business Mobile Networks | 2         | 0.77%   |
| DisplayLink                       | 2         | 0.77%   |
| TP-Link                           | 1         | 0.38%   |
| Sierra Wireless                   | 1         | 0.38%   |
| Quectel Wireless Solutions        | 1         | 0.38%   |
| Qualcomm Atheros Communications   | 1         | 0.38%   |
| Microchip Technology              | 1         | 0.38%   |
| Lenovo                            | 1         | 0.38%   |
| Dell                              | 1         | 0.38%   |
| D-Link System                     | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 54        | 16.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 4.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 3.11%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 3.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.48%   |
| Intel Wi-Fi 6 AX201                                                    | 8         | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 2.17%   |
| Intel Wireless 8265 / 8275                                             | 7         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 6         | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.55%   |
| Intel Wireless 7265                                                    | 5         | 1.55%   |
| Intel Wireless 7260                                                    | 5         | 1.55%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.55%   |
| Realtek 802.11ac NIC                                                   | 4         | 1.24%   |
| Intel Wireless 8260                                                    | 4         | 1.24%   |
| Intel WiFi Link 5100                                                   | 4         | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.24%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.93%   |
| Intel Wireless 3165                                                    | 3         | 0.93%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.93%   |
| Intel Wi-Fi 6 AX201 160MHz                                             | 3         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 3         | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 3         | 0.93%   |
| Intel Centrino Wireless-N 2230                                         | 3         | 0.93%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.93%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 52.22%  |
| Realtek Semiconductor           | 40        | 22.22%  |
| Qualcomm Atheros                | 24        | 13.33%  |
| Broadcom                        | 9         | 5%      |
| Ralink                          | 3         | 1.67%   |
| MediaTek                        | 2         | 1.11%   |
| Broadcom Limited                | 2         | 1.11%   |
| TP-Link                         | 1         | 0.56%   |
| Sierra Wireless                 | 1         | 0.56%   |
| Quectel Wireless Solutions      | 1         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.56%   |
| Dell                            | 1         | 0.56%   |
| D-Link System                   | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 5.52%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.42%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.87%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.76%   |
| Intel Wireless 7265                                                     | 5         | 2.76%   |
| Intel Wireless 7260                                                     | 5         | 2.76%   |
| Realtek 802.11ac NIC                                                    | 4         | 2.21%   |
| Intel Wireless 8260                                                     | 4         | 2.21%   |
| Intel WiFi Link 5100                                                    | 4         | 2.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.21%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.66%   |
| Intel Wireless 3165                                                     | 3         | 1.66%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 1.66%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 1.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.66%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.66%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| Intel Wireless 3160                                                     | 2         | 1.1%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.1%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.1%    |
| TP-Link 802.11ac NIC                                                    | 1         | 0.55%   |
| Sierra Wireless EM7455                                                  | 1         | 0.55%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller             | 1         | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 56.2%   |
| Intel                    | 35        | 25.55%  |
| Broadcom                 | 6         | 4.38%   |
| ASIX Electronics         | 5         | 3.65%   |
| Qualcomm Atheros         | 3         | 2.19%   |
| Nvidia                   | 2         | 1.46%   |
| Marvell Technology Group | 2         | 1.46%   |
| JMicron Technology       | 2         | 1.46%   |
| DisplayLink              | 2         | 1.46%   |
| Microchip Technology     | 1         | 0.73%   |
| Lenovo                   | 1         | 0.73%   |
| Broadcom Limited         | 1         | 0.73%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 54        | 38.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 15        | 10.79%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 4.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.32%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 3.6%    |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.16%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 2.16%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 2.16%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.44%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.44%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.44%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.44%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.44%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.44%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.72%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.72%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.72%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.72%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.72%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.72%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.72%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.72%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.72%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.72%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.72%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.72%   |
| Intel 82566MC Gigabit Network Connection                                       | 1         | 0.72%   |
| DisplayLink USB3.0 Dual Video Dock                                             | 1         | 0.72%   |
| DisplayLink Kensington SD3600 Dual Video Dock                                  | 1         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.72%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 56%     |
| Ethernet | 130       | 43.33%  |
| Modem    | 2         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 77.72%  |
| Ethernet | 41        | 22.28%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 121       | 70.76%  |
| 1     | 47        | 27.49%  |
| 0     | 3         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 64.74%  |
| Yes  | 61        | 35.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 51.37%  |
| Realtek Semiconductor           | 23        | 15.75%  |
| Broadcom                        | 13        | 8.9%    |
| Qualcomm Atheros Communications | 8         | 5.48%   |
| IMC Networks                    | 7         | 4.79%   |
| Foxconn / Hon Hai               | 4         | 2.74%   |
| Apple                           | 4         | 2.74%   |
| Ralink                          | 3         | 2.05%   |
| Lite-On Technology              | 3         | 2.05%   |
| Cambridge Silicon Radio         | 3         | 2.05%   |
| Toshiba                         | 1         | 0.68%   |
| Hewlett-Packard                 | 1         | 0.68%   |
| Foxconn International           | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 15.75%  |
| Intel AX201 Bluetooth                                                               | 21        | 14.38%  |
| Realtek Bluetooth Radio                                                             | 19        | 13.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 7.53%   |
| Intel AX200 Bluetooth                                                               | 10        | 6.85%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.74%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.74%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.05%   |
| Intel AX210 Bluetooth                                                               | 3         | 2.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.05%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 2.05%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.37%   |
| Intel Bluetooth Device                                                              | 2         | 1.37%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.37%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.37%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.37%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.68%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.68%   |
| Broadcom Bluetooth 3.0 Dongle                                                       | 1         | 0.68%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.68%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.68%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 134       | 62.33%  |
| AMD                    | 37        | 17.21%  |
| Nvidia                 | 33        | 15.35%  |
| C-Media Electronics    | 2         | 0.93%   |
| Realtek Semiconductor  | 1         | 0.47%   |
| Plantronics            | 1         | 0.47%   |
| Meizu                  | 1         | 0.47%   |
| Lenovo                 | 1         | 0.47%   |
| Kingston Technology    | 1         | 0.47%   |
| GN Netcom              | 1         | 0.47%   |
| Generalplus Technology | 1         | 0.47%   |
| DSEA A/S               | 1         | 0.47%   |
| ASUSTek Computer       | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 7.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 4.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 4.26%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 3.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 3.49%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.33%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.33%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.94%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.94%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.94%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 1.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.55%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.55%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.55%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.16%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.16%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.16%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.16%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.78%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 26.67%  |
| SK hynix            | 36        | 24%     |
| Micron Technology   | 23        | 15.33%  |
| Unknown             | 13        | 8.67%   |
| Kingston            | 10        | 6.67%   |
| Unknown (ABCD)      | 7         | 4.67%   |
| Crucial             | 7         | 4.67%   |
| Ramaxel Technology  | 5         | 3.33%   |
| Nanya Technology    | 3         | 2%      |
| G.Skill             | 2         | 1.33%   |
| Corsair             | 2         | 1.33%   |
| Unknown             | 2         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 6         | 3.68%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 3.07%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 1.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 1.84%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 2         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 2         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.23%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.23%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.23%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s               | 2         | 1.23%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 2         | 1.23%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.23%   |
| Unknown                                                             | 2         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR2                               | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                              | 1         | 0.61%   |
| Unknown RAM Module 1GB DIMM DDR3 1600MT/s                           | 1         | 0.61%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 1         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                        | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 1         | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 1         | 0.61%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 0.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                       | 1         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 1         | 0.61%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s               | 1         | 0.61%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 62        | 46.62%  |
| DDR3    | 40        | 30.08%  |
| LPDDR4  | 12        | 9.02%   |
| DDR2    | 7         | 5.26%   |
| SDRAM   | 5         | 3.76%   |
| LPDDR3  | 3         | 2.26%   |
| DDR5    | 3         | 2.26%   |
| Unknown | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 85.82%  |
| Row Of Chips | 15        | 11.19%  |
| Unknown      | 2         | 1.49%   |
| DIMM         | 1         | 0.75%   |
| Chip         | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 56        | 38.1%   |
| 4096  | 39        | 26.53%  |
| 16384 | 25        | 17.01%  |
| 2048  | 20        | 13.61%  |
| 1024  | 5         | 3.4%    |
| 32768 | 2         | 1.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 38        | 26.57%  |
| 1600    | 28        | 19.58%  |
| 2400    | 17        | 11.89%  |
| 2667    | 15        | 10.49%  |
| 2133    | 7         | 4.9%    |
| 1334    | 5         | 3.5%    |
| Unknown | 5         | 3.5%    |
| 4267    | 3         | 2.1%    |
| 2048    | 3         | 2.1%    |
| 1333    | 3         | 2.1%    |
| 1067    | 3         | 2.1%    |
| 667     | 3         | 2.1%    |
| 4800    | 2         | 1.4%    |
| 4199    | 2         | 1.4%    |
| 1867    | 2         | 1.4%    |
| 1066    | 2         | 1.4%    |
| 5600    | 1         | 0.7%    |
| 4266    | 1         | 0.7%    |
| 2933    | 1         | 0.7%    |
| 975     | 1         | 0.7%    |
| 800     | 1         | 0.7%    |

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
| Chicony Electronics                    | 45        | 28.13%  |
| Realtek Semiconductor                  | 18        | 11.25%  |
| IMC Networks                           | 14        | 8.75%   |
| Microdia                               | 12        | 7.5%    |
| Quanta                                 | 10        | 6.25%   |
| Sunplus Innovation Technology          | 7         | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.38%   |
| Syntek                                 | 6         | 3.75%   |
| Suyin                                  | 5         | 3.13%   |
| Bison Electronics                      | 4         | 2.5%    |
| Acer                                   | 4         | 2.5%    |
| Luxvisions Innotech Limited            | 3         | 1.88%   |
| Lite-On Technology                     | 3         | 1.88%   |
| Apple                                  | 3         | 1.88%   |
| Alcor Micro                            | 3         | 1.88%   |
| Silicon Motion                         | 2         | 1.25%   |
| Ricoh                                  | 2         | 1.25%   |
| Logitech                               | 2         | 1.25%   |
| Lenovo                                 | 2         | 1.25%   |
| USB Camera                             | 1         | 0.63%   |
| SunplusIT                              | 1         | 0.63%   |
| Sonix Technology                       | 1         | 0.63%   |
| Razer USA                              | 1         | 0.63%   |
| Intel                                  | 1         | 0.63%   |
| Generalplus Technology                 | 1         | 0.63%   |
| Denron                                 | 1         | 0.63%   |
| ARC International                      | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 7         | 4.38%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 4.38%   |
| Chicony Integrated Camera                     | 7         | 4.38%   |
| Chicony HP HD Camera                          | 7         | 4.38%   |
| Syntek Integrated Camera                      | 5         | 3.13%   |
| Realtek USB Camera                            | 5         | 3.13%   |
| IMC Networks Integrated Camera                | 4         | 2.5%    |
| Microdia Integrated Webcam                    | 3         | 1.88%   |
| Chicony HP Webcam                             | 3         | 1.88%   |
| Chicony HP Truevision HD camera               | 3         | 1.88%   |
| Chicony HD WebCam                             | 3         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 1.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.25%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.25%   |
| Sunplus Integrated_Webcam_FHD                 | 2         | 1.25%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 1.25%   |
| Quanta ov9734_techfront_camera                | 2         | 1.25%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.25%   |
| Quanta HD User Facing                         | 2         | 1.25%   |
| Microdia Webcam Vitade AF                     | 2         | 1.25%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.25%   |
| Lite-On Integrated Camera                     | 2         | 1.25%   |
| Lenovo CNF7237&CNF7238                        | 2         | 1.25%   |
| Chicony VGA Webcam                            | 2         | 1.25%   |
| Chicony USB2.0 Camera                         | 2         | 1.25%   |
| Chicony USB 2.0 Camera                        | 2         | 1.25%   |
| Chicony HD User Facing                        | 2         | 1.25%   |
| Chicony EasyCamera                            | 2         | 1.25%   |
| Bison Integrated Camera                       | 2         | 1.25%   |
| Apple Built-in iSight                         | 2         | 1.25%   |
| Alcor Micro USB 2.0 Camera                    | 2         | 1.25%   |
| Acer Integrated Camera                        | 2         | 1.25%   |
| USB Camera USB Camera                         | 1         | 0.63%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.63%   |
| Suyin USB 2.0 Camera                          | 1         | 0.63%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.63%   |
| SunplusIT PC Camera                           | 1         | 0.63%   |
| Sunplus MTD Camera                            | 1         | 0.63%   |
| Sunplus HP Truevision HD                      | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 32.14%  |
| Upek                       | 5         | 17.86%  |
| Synaptics                  | 5         | 17.86%  |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| Elan Microelectronics      | 3         | 10.71%  |
| AuthenTec                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 17.86%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 17.86%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 10.71%  |
| Elan ELAN:ARM-M4                                                           | 3         | 10.71%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.57%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.57%   |
| Synaptics UWP WBDI Device                                                  | 1         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.57%   |
| AuthenTec AES1600                                                          | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 12        | 57.14%  |
| Alcor Micro           | 5         | 23.81%  |
| Upek                  | 1         | 4.76%   |
| SCM Microsystems      | 1         | 4.76%   |
| O2 Micro              | 1         | 4.76%   |
| Advanced Card Systems | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 5         | 23.81%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 14.29%  |
| Broadcom 5880                                                                | 3         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.76%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 4.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4.76%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 108       | 62.79%  |
| 1     | 50        | 29.07%  |
| 2     | 12        | 6.98%   |
| 3     | 2         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 28        | 36.36%  |
| Chipcard              | 21        | 27.27%  |
| Graphics card         | 8         | 10.39%  |
| Bluetooth             | 6         | 7.79%   |
| Net/wireless          | 4         | 5.19%   |
| Camera                | 4         | 5.19%   |
| Multimedia controller | 2         | 2.6%    |
| Storage               | 1         | 1.3%    |
| Flash memory          | 1         | 1.3%    |
| Dvb card              | 1         | 1.3%    |
| Card reader           | 1         | 1.3%    |

