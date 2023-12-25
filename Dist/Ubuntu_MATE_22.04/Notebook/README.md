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

Total: 392

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-56-generic    | 14        | 7%      |
| 5.15.0-58-generic    | 10        | 5%      |
| 6.2.0-36-generic     | 7         | 3.5%    |
| 5.15.0-53-generic    | 7         | 3.5%    |
| 5.15.0-52-generic    | 7         | 3.5%    |
| 5.15.0-43-generic    | 7         | 3.5%    |
| 5.15.0-25-generic    | 7         | 3.5%    |
| 5.15.0-47-generic    | 6         | 3%      |
| 5.15.0-46-generic    | 6         | 3%      |
| 6.2.0-34-generic     | 5         | 2.5%    |
| 6.2.0-32-generic     | 5         | 2.5%    |
| 5.19.0-46-generic    | 5         | 2.5%    |
| 5.19.0-32-generic    | 5         | 2.5%    |
| 5.15.0-60-generic    | 5         | 2.5%    |
| 5.15.0-48-generic    | 5         | 2.5%    |
| 6.2.0-26-generic     | 4         | 2%      |
| 5.15.0-40-generic    | 4         | 2%      |
| 6.2.0-39-generic     | 3         | 1.5%    |
| 6.2.0-37-generic     | 3         | 1.5%    |
| 6.2.0-35-generic     | 3         | 1.5%    |
| 6.2.0-33-generic     | 3         | 1.5%    |
| 5.19.0-43-generic    | 3         | 1.5%    |
| 5.19.0-42-generic    | 3         | 1.5%    |
| 5.19.0-38-generic    | 3         | 1.5%    |
| 5.19.0-35-generic    | 3         | 1.5%    |
| 5.15.0-83-generic    | 3         | 1.5%    |
| 5.15.0-67-generic    | 3         | 1.5%    |
| 5.15.0-57-generic    | 3         | 1.5%    |
| 5.15.0-41-generic    | 3         | 1.5%    |
| 5.15.0-30-generic    | 3         | 1.5%    |
| 5.15.0-27-generic    | 3         | 1.5%    |
| 5.19.0-50-generic    | 2         | 1%      |
| 5.15.0-91-generic    | 2         | 1%      |
| 5.15.0-88-generic    | 2         | 1%      |
| 5.15.0-84-generic    | 2         | 1%      |
| 5.15.0-79-generic    | 2         | 1%      |
| 5.15.0-76-generic    | 2         | 1%      |
| 5.15.0-69-generic    | 2         | 1%      |
| 5.15.0-52-lowlatency | 2         | 1%      |
| 6.2.3-x64v1-xanmod1  | 1         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 110       | 62.86%  |
| 6.2.0   | 32        | 18.29%  |
| 5.19.0  | 25        | 14.29%  |
| 6.2.3   | 1         | 0.57%   |
| 6.1.8   | 1         | 0.57%   |
| 6.0.8   | 1         | 0.57%   |
| 6.0.0   | 1         | 0.57%   |
| 5.18.0  | 1         | 0.57%   |
| 5.17.1  | 1         | 0.57%   |
| 5.17.0  | 1         | 0.57%   |
| 5.14.0  | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 110       | 62.86%  |
| 6.2     | 33        | 18.86%  |
| 5.19    | 25        | 14.29%  |
| 6.0     | 2         | 1.14%   |
| 5.17    | 2         | 1.14%   |
| 6.1     | 1         | 0.57%   |
| 5.18    | 1         | 0.57%   |
| 5.14    | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 167       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MATE  | 166       | 99.4%   |
| GNOME | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 164       | 98.2%   |
| Wayland | 2         | 1.2%    |
| Tty     | 1         | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 140       | 83.33%  |
| Unknown | 18        | 10.71%  |
| GDM3    | 9         | 5.36%   |
| SDDM    | 1         | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 64        | 37.87%  |
| de_DE | 23        | 13.61%  |
| fr_FR | 22        | 13.02%  |
| it_IT | 12        | 7.1%    |
| ru_RU | 7         | 4.14%   |
| pl_PL | 4         | 2.37%   |
| es_ES | 4         | 2.37%   |
| pt_BR | 3         | 1.78%   |
| en_GB | 3         | 1.78%   |
| en_CA | 3         | 1.78%   |
| en_AU | 3         | 1.78%   |
| C     | 3         | 1.78%   |
| fi_FI | 2         | 1.18%   |
| es_MX | 2         | 1.18%   |
| en_IN | 2         | 1.18%   |
| zh_TW | 1         | 0.59%   |
| zh_CN | 1         | 0.59%   |
| pt_PT | 1         | 0.59%   |
| id_ID | 1         | 0.59%   |
| hu_HU | 1         | 0.59%   |
| es_VE | 1         | 0.59%   |
| es_CL | 1         | 0.59%   |
| es_AR | 1         | 0.59%   |
| en_NZ | 1         | 0.59%   |
| el_GR | 1         | 0.59%   |
| de_CH | 1         | 0.59%   |
| cs_CZ | 1         | 0.59%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 91        | 53.22%  |
| BIOS | 80        | 46.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 138       | 81.66%  |
| Tmpfs   | 16        | 9.47%   |
| Overlay | 7         | 4.14%   |
| Zfs     | 3         | 1.78%   |
| Btrfs   | 2         | 1.18%   |
| Xfs     | 1         | 0.59%   |
| Jfs     | 1         | 0.59%   |
| Ext3    | 1         | 0.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 131       | 77.06%  |
| Unknown | 25        | 14.71%  |
| MBR     | 14        | 8.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 148       | 88.62%  |
| Yes       | 19        | 11.38%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 64.5%   |
| Yes       | 60        | 35.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 35        | 20.96%  |
| Lenovo              | 33        | 19.76%  |
| Dell                | 22        | 13.17%  |
| ASUSTek Computer    | 18        | 10.78%  |
| Acer                | 11        | 6.59%   |
| Sony                | 5         | 2.99%   |
| HUAWEI              | 4         | 2.4%    |
| Apple               | 4         | 2.4%    |
| Google              | 3         | 1.8%    |
| Toshiba             | 2         | 1.2%    |
| Notebook            | 2         | 1.2%    |
| Intel               | 2         | 1.2%    |
| Clevo               | 2         | 1.2%    |
| VIT                 | 1         | 0.6%    |
| TrekStor            | 1         | 0.6%    |
| SLIMBOOK            | 1         | 0.6%    |
| Samsung Electronics | 1         | 0.6%    |
| Positivo            | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| Packard Bell        | 1         | 0.6%    |
| MSI                 | 1         | 0.6%    |
| MicroByte           | 1         | 0.6%    |
| LincPlus            | 1         | 0.6%    |
| LG Electronics      | 1         | 0.6%    |
| Kiano               | 1         | 0.6%    |
| IPASON              | 1         | 0.6%    |
| Infinix             | 1         | 0.6%    |
| HYPERPC             | 1         | 0.6%    |
| HONOR               | 1         | 0.6%    |
| GPU Company         | 1         | 0.6%    |
| GPD                 | 1         | 0.6%    |
| Gigabyte Technology | 1         | 0.6%    |
| Compaq              | 1         | 0.6%    |
| Chuwi               | 1         | 0.6%    |
| Bluechip Computer   | 1         | 0.6%    |
| BANGHO              | 1         | 0.6%    |
| AZW                 | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Precision 7520                  | 2         | 1.2%    |
| Dell Latitude 7420                   | 2         | 1.2%    |
| VIT P1400                            | 1         | 0.6%    |
| TrekStor Surfbook A13B               | 1         | 0.6%    |
| Toshiba Satellite P50-B-10Z          | 1         | 0.6%    |
| Toshiba Satellite C50D-A-133         | 1         | 0.6%    |
| Sony VPCEH1E1E                       | 1         | 0.6%    |
| Sony VPCEB2Z1E                       | 1         | 0.6%    |
| Sony VPCEA36FG                       | 1         | 0.6%    |
| Sony VGN-Z21WRN_B                    | 1         | 0.6%    |
| Sony SVF13N2J2ES                     | 1         | 0.6%    |
| SLIMBOOK TITAN                       | 1         | 0.6%    |
| Samsung 905S3G/906S3G/915S3G/9305SG  | 1         | 0.6%    |
| Positivo C4128G-15                   | 1         | 0.6%    |
| Panasonic CF-53SJCZYLM               | 1         | 0.6%    |
| Packard Bell EasyNote ENTG81BA       | 1         | 0.6%    |
| Notebook NV4XMB,ME,MZ                | 1         | 0.6%    |
| Notebook NJx0MU                      | 1         | 0.6%    |
| MSI GF65 Thin 10SDR                  | 1         | 0.6%    |
| MicroByte ezbook                     | 1         | 0.6%    |
| LincPlus LINNCPLUS P1                | 1         | 0.6%    |
| LG 17Z990-R.AAS8U1                   | 1         | 0.6%    |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.6%    |
| Lenovo V15 G2 ALC 82KD               | 1         | 0.6%    |
| Lenovo V145-15AST 81MT               | 1         | 0.6%    |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.6%    |
| Lenovo ThinkPad X200 74595FG         | 1         | 0.6%    |
| Lenovo ThinkPad T580 20LAS0DL00      | 1         | 0.6%    |
| Lenovo ThinkPad T490s 20NYS58200     | 1         | 0.6%    |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.6%    |
| Lenovo ThinkPad T430 2347G5U         | 1         | 0.6%    |
| Lenovo ThinkPad T420 4238LY7         | 1         | 0.6%    |
| Lenovo ThinkPad T420 4236MBG         | 1         | 0.6%    |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00 | 1         | 0.6%    |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.6%    |
| Lenovo ThinkPad SL 2746AHG           | 1         | 0.6%    |
| Lenovo ThinkPad R61 8918DEG          | 1         | 0.6%    |
| Lenovo ThinkPad P53 20QN000FIX       | 1         | 0.6%    |
| Lenovo ThinkPad L14 Gen 3 21C6S1HW00 | 1         | 0.6%    |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 9.58%   |
| Dell Latitude          | 9         | 5.39%   |
| Lenovo IdeaPad         | 8         | 4.79%   |
| HP ProBook             | 6         | 3.59%   |
| HP Pavilion            | 6         | 3.59%   |
| Dell Precision         | 6         | 3.59%   |
| Acer Aspire            | 6         | 3.59%   |
| ASUS VivoBook          | 5         | 2.99%   |
| HP EliteBook           | 4         | 2.4%    |
| HP Laptop              | 3         | 1.8%    |
| Dell Inspiron          | 3         | 1.8%    |
| ASUS ASUS              | 3         | 1.8%    |
| Toshiba Satellite      | 2         | 1.2%    |
| Lenovo V15             | 2         | 1.2%    |
| Lenovo ThinkBook       | 2         | 1.2%    |
| Lenovo Legion          | 2         | 1.2%    |
| HP ZBook               | 2         | 1.2%    |
| HP Stream              | 2         | 1.2%    |
| HP OMEN                | 2         | 1.2%    |
| HP 15                  | 2         | 1.2%    |
| Dell XPS               | 2         | 1.2%    |
| Acer TravelMate        | 2         | 1.2%    |
| Acer Extensa           | 2         | 1.2%    |
| VIT P1400              | 1         | 0.6%    |
| TrekStor Surfbook      | 1         | 0.6%    |
| Sony VPCEH1E1E         | 1         | 0.6%    |
| Sony VPCEB2Z1E         | 1         | 0.6%    |
| Sony VPCEA36FG         | 1         | 0.6%    |
| Sony VGN-Z21WRN        | 1         | 0.6%    |
| Sony SVF13N2J2ES       | 1         | 0.6%    |
| SLIMBOOK TITAN         | 1         | 0.6%    |
| Samsung 905S3G         | 1         | 0.6%    |
| Positivo C4128G-15     | 1         | 0.6%    |
| Panasonic CF-53SJCZYLM | 1         | 0.6%    |
| Packard Bell EasyNote  | 1         | 0.6%    |
| Notebook NV4XMB        | 1         | 0.6%    |
| Notebook NJx0MU        | 1         | 0.6%    |
| MSI GF65               | 1         | 0.6%    |
| MicroByte ezbook       | 1         | 0.6%    |
| LincPlus LINNCPLUS     | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 32        | 19.16%  |
| 2019    | 15        | 8.98%   |
| 2020    | 13        | 7.78%   |
| 2018    | 12        | 7.19%   |
| 2022    | 10        | 5.99%   |
| 2016    | 10        | 5.99%   |
| 2014    | 10        | 5.99%   |
| 2013    | 10        | 5.99%   |
| 2008    | 9         | 5.39%   |
| 2015    | 8         | 4.79%   |
| 2012    | 8         | 4.79%   |
| 2011    | 8         | 4.79%   |
| 2009    | 6         | 3.59%   |
| 2017    | 5         | 2.99%   |
| 2010    | 5         | 2.99%   |
| 2023    | 2         | 1.2%    |
| 2007    | 2         | 1.2%    |
| 2006    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 167       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 154       | 90.59%  |
| Enabled  | 16        | 9.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 98.2%   |
| Yes  | 3         | 1.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 46        | 27.54%  |
| 3.01-4.0    | 41        | 24.55%  |
| 16.01-24.0  | 30        | 17.96%  |
| 8.01-16.0   | 22        | 13.17%  |
| 32.01-64.0  | 14        | 8.38%   |
| 24.01-32.0  | 4         | 2.4%    |
| 1.01-2.0    | 4         | 2.4%    |
| 2.01-3.0    | 3         | 1.8%    |
| 64.01-256.0 | 3         | 1.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 63        | 34.62%  |
| 2.01-3.0   | 49        | 26.92%  |
| 3.01-4.0   | 33        | 18.13%  |
| 4.01-8.0   | 21        | 11.54%  |
| 8.01-16.0  | 10        | 5.49%   |
| 0.51-1.0   | 5         | 2.75%   |
| 24.01-32.0 | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 76.65%  |
| 2      | 30        | 17.96%  |
| 3      | 8         | 4.79%   |
| 4      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 65.27%  |
| Yes       | 58        | 34.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 127       | 76.05%  |
| No        | 40        | 23.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 98.2%   |
| No        | 3         | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 84.02%  |
| No        | 27        | 15.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 25        | 14.97%  |
| France             | 23        | 13.77%  |
| USA                | 20        | 11.98%  |
| Italy              | 14        | 8.38%   |
| Spain              | 7         | 4.19%   |
| Russia             | 7         | 4.19%   |
| Brazil             | 6         | 3.59%   |
| Poland             | 5         | 2.99%   |
| UK                 | 4         | 2.4%    |
| India              | 4         | 2.4%    |
| Turkey             | 3         | 1.8%    |
| Indonesia          | 3         | 1.8%    |
| Finland            | 3         | 1.8%    |
| Thailand           | 2         | 1.2%    |
| Serbia             | 2         | 1.2%    |
| Romania            | 2         | 1.2%    |
| Portugal           | 2         | 1.2%    |
| Mexico             | 2         | 1.2%    |
| Hungary            | 2         | 1.2%    |
| Greece             | 2         | 1.2%    |
| Estonia            | 2         | 1.2%    |
| Chile              | 2         | 1.2%    |
| Belgium            | 2         | 1.2%    |
| Australia          | 2         | 1.2%    |
| Venezuela          | 1         | 0.6%    |
| Ukraine            | 1         | 0.6%    |
| Taiwan             | 1         | 0.6%    |
| Switzerland        | 1         | 0.6%    |
| Slovenia           | 1         | 0.6%    |
| Peru               | 1         | 0.6%    |
| Paraguay           | 1         | 0.6%    |
| New Zealand        | 1         | 0.6%    |
| Netherlands        | 1         | 0.6%    |
| Libya              | 1         | 0.6%    |
| Hong Kong          | 1         | 0.6%    |
| Georgia            | 1         | 0.6%    |
| Dominican Republic | 1         | 0.6%    |
| Czechia            | 1         | 0.6%    |
| Costa Rica         | 1         | 0.6%    |
| Colombia           | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 5         | 2.89%   |
| Warsaw            | 4         | 2.31%   |
| Wittingen         | 3         | 1.73%   |
| Moscow            | 3         | 1.73%   |
| Mannheim          | 3         | 1.73%   |
| Lisbon            | 2         | 1.16%   |
| Hyderabad         | 2         | 1.16%   |
| Hamburg           | 2         | 1.16%   |
| Greenville        | 2         | 1.16%   |
| Frankfurt am Main | 2         | 1.16%   |
| Berlin            | 2         | 1.16%   |
| Belgrade          | 2         | 1.16%   |
| Bangkok           | 2         | 1.16%   |
| Xining            | 1         | 0.58%   |
| Wellin            | 1         | 0.58%   |
| Weiden            | 1         | 0.58%   |
| Voronezh          | 1         | 0.58%   |
| Viroflay          | 1         | 0.58%   |
| Villeurbanne      | 1         | 0.58%   |
| Vienna            | 1         | 0.58%   |
| Vaudoy-en-Brie    | 1         | 0.58%   |
| Varna             | 1         | 0.58%   |
| Valenciennes      | 1         | 0.58%   |
| Valence           | 1         | 0.58%   |
| Turku             | 1         | 0.58%   |
| Turin             | 1         | 0.58%   |
| Tulungagung       | 1         | 0.58%   |
| Tula              | 1         | 0.58%   |
| Tripoli           | 1         | 0.58%   |
| Tours             | 1         | 0.58%   |
| Toulouse          | 1         | 0.58%   |
| Tizayuca          | 1         | 0.58%   |
| Thane             | 1         | 0.58%   |
| Tartu             | 1         | 0.58%   |
| Taoyuan District  | 1         | 0.58%   |
| Talcahuano        | 1         | 0.58%   |
| Seville           | 1         | 0.58%   |
| Settimo Torinese  | 1         | 0.58%   |
| Sarzeau           | 1         | 0.58%   |
| Sarospatak        | 1         | 0.58%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 42        | 71     | 20.29%  |
| Unknown               | 18        | 21     | 8.7%    |
| WDC                   | 17        | 18     | 8.21%   |
| Seagate               | 17        | 18     | 8.21%   |
| Toshiba               | 12        | 16     | 5.8%    |
| SanDisk               | 10        | 12     | 4.83%   |
| Kingston              | 10        | 11     | 4.83%   |
| Crucial               | 10        | 12     | 4.83%   |
| SK hynix              | 9         | 9      | 4.35%   |
| Intel                 | 6         | 6      | 2.9%    |
| A-DATA Technology     | 5         | 5      | 2.42%   |
| Hitachi               | 4         | 4      | 1.93%   |
| HGST                  | 4         | 4      | 1.93%   |
| China                 | 4         | 5      | 1.93%   |
| SPCC                  | 3         | 5      | 1.45%   |
| Micron Technology     | 3         | 3      | 1.45%   |
| KIOXIA                | 3         | 3      | 1.45%   |
| UMIS                  | 2         | 3      | 0.97%   |
| Phison                | 2         | 2      | 0.97%   |
| KingSpec              | 2         | 3      | 0.97%   |
| WDC WDS2              | 1         | 1      | 0.48%   |
| Verbatim              | 1         | 7      | 0.48%   |
| Silicon Motion        | 1         | 1      | 0.48%   |
| Realtek Semiconductor | 1         | 2      | 0.48%   |
| PNY                   | 1         | 1      | 0.48%   |
| Phison Electronics    | 1         | 1      | 0.48%   |
| Patriot               | 1         | 1      | 0.48%   |
| OCZ                   | 1         | 1      | 0.48%   |
| Netac                 | 1         | 1      | 0.48%   |
| LITEONIT              | 1         | 1      | 0.48%   |
| Lenovo                | 1         | 1      | 0.48%   |
| Kston                 | 1         | 1      | 0.48%   |
| KingFast              | 1         | 1      | 0.48%   |
| JMicron Technology    | 1         | 1      | 0.48%   |
| Intenso               | 1         | 1      | 0.48%   |
| Hjwdz                 | 1         | 1      | 0.48%   |
| Gigabyte Technology   | 1         | 1      | 0.48%   |
| FORESEE               | 1         | 1      | 0.48%   |
| faspeed               | 1         | 1      | 0.48%   |
| Corsair               | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 3         | 1.38%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 1.38%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.38%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 3         | 1.38%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.38%   |
| Unknown SLD64G  64GB                                | 2         | 0.92%   |
| Unknown MMC Card  64GB                              | 2         | 0.92%   |
| Seagate ST9500420AS 500GB                           | 2         | 0.92%   |
| Seagate ST2000LM015-2E8174 2TB                      | 2         | 0.92%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.92%   |
| Seagate Expansion 1TB                               | 2         | 0.92%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.92%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 2         | 0.92%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 0.92%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 2         | 0.92%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.92%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.92%   |
| Crucial CT1000BX500SSD1 1TB                         | 2         | 0.92%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD                     | 1         | 0.46%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.46%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 0.46%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.46%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 0.46%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 0.46%   |
| WDC WD40 EFRX-68N32N0 4TB                           | 1         | 0.46%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 0.46%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 0.46%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 0.46%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.46%   |
| WDC WD Blue SA510 M.2 2280 500GB                    | 1         | 0.46%   |
| WDC WD Blue SA510 2.5 500GB                         | 1         | 0.46%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 1         | 0.46%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 0.46%   |
| WDC PC SN530 NVMe 256GB                             | 1         | 0.46%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB                | 1         | 0.46%   |
| Verbatim Vi550 S3 512GB                             | 1         | 0.46%   |
| Unknown xD/SD/M.S.                                  | 1         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 18     | 39.53%  |
| WDC     | 10        | 11     | 23.26%  |
| Toshiba | 8         | 11     | 18.6%   |
| Hitachi | 4         | 4      | 9.3%    |
| HGST    | 4         | 4      | 9.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 26.58%  |
| Crucial             | 10        | 12     | 12.66%  |
| Kingston            | 9         | 10     | 11.39%  |
| SanDisk             | 5         | 6      | 6.33%   |
| China               | 4         | 5      | 5.06%   |
| A-DATA Technology   | 4         | 4      | 5.06%   |
| WDC                 | 3         | 3      | 3.8%    |
| SPCC                | 2         | 4      | 2.53%   |
| KingSpec            | 2         | 3      | 2.53%   |
| Intel               | 2         | 2      | 2.53%   |
| WDC WDS2            | 1         | 1      | 1.27%   |
| Verbatim            | 1         | 7      | 1.27%   |
| Toshiba             | 1         | 2      | 1.27%   |
| SK hynix            | 1         | 1      | 1.27%   |
| PNY                 | 1         | 1      | 1.27%   |
| Patriot             | 1         | 1      | 1.27%   |
| OCZ                 | 1         | 1      | 1.27%   |
| Netac               | 1         | 1      | 1.27%   |
| Micron Technology   | 1         | 1      | 1.27%   |
| LITEONIT            | 1         | 1      | 1.27%   |
| Kston               | 1         | 1      | 1.27%   |
| KingFast            | 1         | 1      | 1.27%   |
| JMicron Technology  | 1         | 1      | 1.27%   |
| Intenso             | 1         | 1      | 1.27%   |
| Corsair             | 1         | 1      | 1.27%   |
| Apple               | 1         | 1      | 1.27%   |
| addlink             | 1         | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 70        | 97     | 35.9%   |
| NVMe    | 65        | 96     | 33.33%  |
| HDD     | 41        | 48     | 21.03%  |
| MMC     | 16        | 19     | 8.21%   |
| Unknown | 3         | 3      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 100       | 134    | 51.55%  |
| NVMe | 65        | 95     | 33.51%  |
| MMC  | 16        | 19     | 8.25%   |
| SAS  | 13        | 15     | 6.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 78        | 93     | 68.42%  |
| 0.51-1.0   | 24        | 33     | 21.05%  |
| 1.01-2.0   | 7         | 13     | 6.14%   |
| 3.01-4.0   | 3         | 4      | 2.63%   |
| 4.01-10.0  | 2         | 2      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 29.65%  |
| 251-500        | 45        | 26.16%  |
| 501-1000       | 21        | 12.21%  |
| 51-100         | 14        | 8.14%   |
| 1001-2000      | 13        | 7.56%   |
| 21-50          | 9         | 5.23%   |
| 1-20           | 9         | 5.23%   |
| 2001-3000      | 5         | 2.91%   |
| More than 3000 | 4         | 2.33%   |
| Unknown        | 1         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 50        | 28.74%  |
| 21-50          | 35        | 20.11%  |
| 101-250        | 31        | 17.82%  |
| 51-100         | 23        | 13.22%  |
| 251-500        | 16        | 9.2%    |
| 501-1000       | 8         | 4.6%    |
| 1001-2000      | 5         | 2.87%   |
| 2001-3000      | 3         | 1.72%   |
| More than 3000 | 2         | 1.15%   |
| Unknown        | 1         | 0.57%   |

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
| Works    | 97        | 131    | 52.15%  |
| Detected | 74        | 116    | 39.78%  |
| Malfunc  | 15        | 16     | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 108       | 54.55%  |
| Samsung Electronics          | 23        | 11.62%  |
| AMD                          | 21        | 10.61%  |
| SanDisk                      | 9         | 4.55%   |
| SK hynix                     | 8         | 4.04%   |
| Phison Electronics           | 4         | 2.02%   |
| KIOXIA                       | 4         | 2.02%   |
| Toshiba America Info Systems | 3         | 1.52%   |
| Nvidia                       | 3         | 1.52%   |
| Union Memory (Shenzhen)      | 2         | 1.01%   |
| Micron Technology            | 2         | 1.01%   |
| ADATA Technology             | 2         | 1.01%   |
| Silicon Motion               | 1         | 0.51%   |
| Shenzhen Longsys Electronics | 1         | 0.51%   |
| Realtek Semiconductor        | 1         | 0.51%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.51%   |
| Marvell Technology Group     | 1         | 0.51%   |
| Lenovo                       | 1         | 0.51%   |
| Kingston Technology Company  | 1         | 0.51%   |
| Biwin Storage Technology     | 1         | 0.51%   |
| Unknown                      | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 8.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 13        | 6.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 5.26%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 3.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.83%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 7         | 3.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 6         | 2.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 6         | 2.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 2.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 2.39%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 1.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.44%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.44%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 1.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.44%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 2         | 0.96%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 2         | 0.96%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 2         | 0.96%   |
| Intel Tiger Lake SATA AHCI Controller                                                  | 2         | 0.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 2         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.96%   |
| Intel Jasper Lake SATA AHCI Controller                                                 | 2         | 0.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 111       | 55.22%  |
| NVMe | 65        | 32.34%  |
| RAID | 16        | 7.96%   |
| IDE  | 9         | 4.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 79.64%  |
| AMD    | 34        | 20.36%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.8%    |
| Intel Core i7-3517U CPU @ 1.90GHz             | 3         | 1.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 1.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.8%    |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 1.2%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 1.2%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.2%    |
| Intel Pentium CPU B940 @ 2.00GHz              | 2         | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.2%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.2%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.2%    |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.2%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.2%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.2%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.2%    |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.2%    |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.2%    |
| Intel 11th Gen Core i9-11980HK @ 2.60GHz      | 2         | 1.2%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.2%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.2%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.2%    |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 1.2%    |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.6%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.6%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.6%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.6%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.6%    |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.6%    |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.6%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 35        | 20.96%  |
| Intel Core i5           | 24        | 14.37%  |
| Other                   | 20        | 11.98%  |
| Intel Celeron           | 19        | 11.38%  |
| Intel Core i3           | 10        | 5.99%   |
| Intel Core 2 Duo        | 10        | 5.99%   |
| Intel Pentium           | 7         | 4.19%   |
| AMD Ryzen 7             | 7         | 4.19%   |
| AMD Ryzen 5             | 6         | 3.59%   |
| Intel Pentium Silver    | 3         | 1.8%    |
| Intel Pentium Dual-Core | 3         | 1.8%    |
| AMD A6                  | 3         | 1.8%    |
| AMD Ryzen 9             | 2         | 1.2%    |
| AMD Ryzen 7 PRO         | 2         | 1.2%    |
| AMD Ryzen 3             | 2         | 1.2%    |
| AMD A4                  | 2         | 1.2%    |
| Intel Xeon              | 1         | 0.6%    |
| Intel Core m5           | 1         | 0.6%    |
| Intel Atom              | 1         | 0.6%    |
| AMD Turion 64 X2 Mobile | 1         | 0.6%    |
| AMD Turion 64 Mobile    | 1         | 0.6%    |
| AMD Sempron             | 1         | 0.6%    |
| AMD Ryzen 5 PRO         | 1         | 0.6%    |
| AMD Quad-Core           | 1         | 0.6%    |
| AMD E1                  | 1         | 0.6%    |
| AMD Athlon X2           | 1         | 0.6%    |
| AMD Athlon II           | 1         | 0.6%    |
| AMD A8                  | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 77        | 46.11%  |
| 4      | 61        | 36.53%  |
| 8      | 13        | 7.78%   |
| 6      | 11        | 6.59%   |
| 14     | 2         | 1.2%    |
| 1      | 2         | 1.2%    |
| 10     | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 167       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 109       | 65.27%  |
| 1      | 58        | 34.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 167       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 46.82%  |
| 0x806c1    | 8         | 4.62%   |
| 0x806ec    | 6         | 3.47%   |
| 0x40651    | 6         | 3.47%   |
| 0x306a9    | 6         | 3.47%   |
| 0x1067a    | 5         | 2.89%   |
| 0x806d1    | 4         | 2.31%   |
| 0x0a50000c | 4         | 2.31%   |
| 0x706a8    | 3         | 1.73%   |
| 0x506c9    | 3         | 1.73%   |
| 0x406e3    | 3         | 1.73%   |
| 0x406c4    | 3         | 1.73%   |
| 0x30678    | 3         | 1.73%   |
| 0x206a7    | 3         | 1.73%   |
| 0x08108109 | 3         | 1.73%   |
| 0x0700010f | 3         | 1.73%   |
| 0x906c0    | 2         | 1.16%   |
| 0x906a3    | 2         | 1.16%   |
| 0x806e9    | 2         | 1.16%   |
| 0x706e5    | 2         | 1.16%   |
| 0x10676    | 2         | 1.16%   |
| 0x08608103 | 2         | 1.16%   |
| 0x906e9    | 1         | 0.58%   |
| 0x906a4    | 1         | 0.58%   |
| 0x806eb    | 1         | 0.58%   |
| 0x806ea    | 1         | 0.58%   |
| 0x706a1    | 1         | 0.58%   |
| 0x6fd      | 1         | 0.58%   |
| 0x6fb      | 1         | 0.58%   |
| 0x506e3    | 1         | 0.58%   |
| 0x20655    | 1         | 0.58%   |
| 0x0a601203 | 1         | 0.58%   |
| 0x0a50000d | 1         | 0.58%   |
| 0x08608102 | 1         | 0.58%   |
| 0x08101016 | 1         | 0.58%   |
| 0x07030105 | 1         | 0.58%   |
| 0x0600611a | 1         | 0.58%   |
| 0x02000032 | 1         | 0.58%   |
| 0x010000c8 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 11.9%   |
| Silvermont       | 12        | 7.14%   |
| Haswell          | 12        | 7.14%   |
| TigerLake        | 11        | 6.55%   |
| IvyBridge        | 11        | 6.55%   |
| SandyBridge      | 10        | 5.95%   |
| Penryn           | 10        | 5.95%   |
| IceLake          | 9         | 5.36%   |
| Skylake          | 8         | 4.76%   |
| Unknown          | 8         | 4.76%   |
| Goldmont plus    | 7         | 4.17%   |
| Zen 3            | 6         | 3.57%   |
| Zen+             | 4         | 2.38%   |
| Excavator        | 4         | 2.38%   |
| Zen 2            | 3         | 1.79%   |
| Westmere         | 3         | 1.79%   |
| Jaguar           | 3         | 1.79%   |
| Goldmont         | 3         | 1.79%   |
| Core             | 3         | 1.79%   |
| CometLake        | 3         | 1.79%   |
| Alderlake Hybrid | 3         | 1.79%   |
| Zen              | 2         | 1.19%   |
| Tremont          | 2         | 1.19%   |
| Puma             | 2         | 1.19%   |
| Nehalem          | 2         | 1.19%   |
| K8 Hammer        | 2         | 1.19%   |
| K10              | 2         | 1.19%   |
| Broadwell        | 2         | 1.19%   |
| K8 & K10 hybrid  | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 57.35%  |
| Nvidia | 44        | 21.57%  |
| AMD    | 43        | 21.08%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 4.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.37%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 3.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.91%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 2.43%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 1.94%   |
| Intel HD Graphics 530                                                                    | 4         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.94%   |
| AMD Lucienne                                                                             | 4         | 1.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.46%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.46%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.46%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.46%   |
| Intel HD Graphics 620                                                                    | 3         | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.46%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.46%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.46%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.97%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 0.97%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.97%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.97%   |
| Intel UHD Graphics 620                                                                   | 2         | 0.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.97%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.97%   |
| Intel HD Graphics 500                                                                    | 2         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.97%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.97%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.97%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.97%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 0.97%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 51.5%   |
| 1 x AMD        | 29        | 17.37%  |
| Intel + Nvidia | 24        | 14.37%  |
| 1 x Nvidia     | 14        | 8.38%   |
| Intel + AMD    | 7         | 4.19%   |
| AMD + Nvidia   | 6         | 3.59%   |
| 2 x AMD        | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 134       | 80.24%  |
| Proprietary | 29        | 17.37%  |
| Unknown     | 4         | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 73.81%  |
| 0.01-0.5   | 19        | 11.31%  |
| 1.01-2.0   | 8         | 4.76%   |
| 0.51-1.0   | 8         | 4.76%   |
| 3.01-4.0   | 4         | 2.38%   |
| 5.01-6.0   | 3         | 1.79%   |
| 7.01-8.0   | 1         | 0.6%    |
| 8.01-16.0  | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 34        | 17.44%  |
| Chimei Innolux          | 28        | 14.36%  |
| LG Display              | 24        | 12.31%  |
| AU Optronics            | 23        | 11.79%  |
| Samsung Electronics     | 21        | 10.77%  |
| Dell                    | 6         | 3.08%   |
| PANDA                   | 5         | 2.56%   |
| Lenovo                  | 5         | 2.56%   |
| Sharp                   | 4         | 2.05%   |
| Chi Mei Optoelectronics | 4         | 2.05%   |
| Apple                   | 4         | 2.05%   |
| BenQ                    | 3         | 1.54%   |
| AOC                     | 3         | 1.54%   |
| Ancor Communications    | 3         | 1.54%   |
| Sony                    | 2         | 1.03%   |
| Philips                 | 2         | 1.03%   |
| Iiyama                  | 2         | 1.03%   |
| Hewlett-Packard         | 2         | 1.03%   |
| Goldstar                | 2         | 1.03%   |
| CSO                     | 2         | 1.03%   |
| ViewSonic               | 1         | 0.51%   |
| Unknown                 | 1         | 0.51%   |
| Toshiba                 | 1         | 0.51%   |
| Sceptre Tech            | 1         | 0.51%   |
| Quanta Display          | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| LGD                     | 1         | 0.51%   |
| LG Philips              | 1         | 0.51%   |
| IBM                     | 1         | 0.51%   |
| HJC                     | 1         | 0.51%   |
| Hitachi                 | 1         | 0.51%   |
| HannStar                | 1         | 0.51%   |
| Eizo                    | 1         | 0.51%   |
| CS_                     | 1         | 0.51%   |
| ASUSTek Computer        | 1         | 0.51%   |
| Acer                    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch                 | 2         | 1.02%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch    | 2         | 1.02%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 2         | 1.02%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                   | 2         | 1.02%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 2         | 1.02%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                   | 2         | 1.02%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 1.02%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                  | 2         | 1.02%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 600x340mm 27.2-inch           | 1         | 0.51%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                    | 1         | 0.51%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch                | 1         | 0.51%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch                 | 1         | 0.51%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                 | 1         | 0.51%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                 | 1         | 0.51%   |
| Sharp HDMI SHP10E8 1360x768 521x293mm 23.5-inch                         | 1         | 0.51%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                  | 1         | 0.51%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch     | 1         | 0.51%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch      | 1         | 0.51%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.51%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch       | 1         | 0.51%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 1         | 0.51%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5044 1920x1080 382x215mm 17.3-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch   | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch    | 1         | 0.51%   |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch         | 1         | 0.51%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 1         | 0.51%   |
| Philips 239CQH PHLC0A0 1920x1080 509x286mm 23.0-inch                    | 1         | 0.51%   |
| PANDA LCD Monitor NCP004F 1920x1080 309x174mm 14.0-inch                 | 1         | 0.51%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                 | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 78        | 43.82%  |
| 1366x768 (WXGA)    | 52        | 29.21%  |
| 2560x1440 (QHD)    | 9         | 5.06%   |
| 1280x800 (WXGA)    | 8         | 4.49%   |
| 3840x2160 (4K)     | 7         | 3.93%   |
| 1600x900 (HD+)     | 5         | 2.81%   |
| 1440x900 (WXGA+)   | 5         | 2.81%   |
| 2560x1600          | 4         | 2.25%   |
| 3840x2400          | 2         | 1.12%   |
| 2160x1440          | 2         | 1.12%   |
| 1920x1200 (WUXGA)  | 2         | 1.12%   |
| 1680x1050 (WSXGA+) | 2         | 1.12%   |
| 2880x1620          | 1         | 0.56%   |
| 1360x768           | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 75        | 38.46%  |
| 14      | 25        | 12.82%  |
| 13      | 22        | 11.28%  |
| 17      | 15        | 7.69%   |
| 27      | 14        | 7.18%   |
| 24      | 10        | 5.13%   |
| 23      | 6         | 3.08%   |
| 12      | 6         | 3.08%   |
| 11      | 4         | 2.05%   |
| 21      | 3         | 1.54%   |
| 16      | 3         | 1.54%   |
| 84      | 2         | 1.03%   |
| 54      | 2         | 1.03%   |
| 31      | 2         | 1.03%   |
| 40      | 1         | 0.51%   |
| 25      | 1         | 0.51%   |
| 22      | 1         | 0.51%   |
| 18      | 1         | 0.51%   |
| 10      | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 118       | 61.46%  |
| 501-600     | 28        | 14.58%  |
| 201-300     | 17        | 8.85%   |
| 351-400     | 15        | 7.81%   |
| 401-500     | 5         | 2.6%    |
| 601-700     | 3         | 1.56%   |
| 1501-2000   | 2         | 1.04%   |
| 1001-1500   | 2         | 1.04%   |
| 801-900     | 1         | 0.52%   |
| Unknown     | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 137       | 84.05%  |
| 16/10   | 23        | 14.11%  |
| 3/2     | 2         | 1.23%   |
| Unknown | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 37.11%  |
| 81-90          | 43        | 22.16%  |
| 201-250        | 16        | 8.25%   |
| 301-350        | 14        | 7.22%   |
| 121-130        | 13        | 6.7%    |
| 61-70          | 6         | 3.09%   |
| More than 1000 | 4         | 2.06%   |
| 71-80          | 4         | 2.06%   |
| 51-60          | 4         | 2.06%   |
| 251-300        | 4         | 2.06%   |
| 111-120        | 3         | 1.55%   |
| 91-100         | 3         | 1.55%   |
| 351-500        | 2         | 1.03%   |
| 131-140        | 2         | 1.03%   |
| 41-50          | 1         | 0.52%   |
| 141-150        | 1         | 0.52%   |
| 501-1000       | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 76        | 40.64%  |
| 101-120       | 52        | 27.81%  |
| 51-100        | 36        | 19.25%  |
| 161-240       | 16        | 8.56%   |
| More than 240 | 3         | 1.6%    |
| 1-50          | 3         | 1.6%    |
| Unknown       | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 129       | 76.79%  |
| 2     | 28        | 16.67%  |
| 3     | 6         | 3.57%   |
| 0     | 4         | 2.38%   |
| 4     | 1         | 0.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 95        | 37.4%   |
| Intel                             | 91        | 35.83%  |
| Qualcomm Atheros                  | 26        | 10.24%  |
| Broadcom                          | 12        | 4.72%   |
| ASIX Electronics                  | 5         | 1.97%   |
| Ralink                            | 3         | 1.18%   |
| Broadcom Limited                  | 3         | 1.18%   |
| Nvidia                            | 2         | 0.79%   |
| MediaTek                          | 2         | 0.79%   |
| Marvell Technology Group          | 2         | 0.79%   |
| JMicron Technology                | 2         | 0.79%   |
| Ericsson Business Mobile Networks | 2         | 0.79%   |
| DisplayLink                       | 2         | 0.79%   |
| TP-Link                           | 1         | 0.39%   |
| Quectel Wireless Solutions        | 1         | 0.39%   |
| Qualcomm Atheros Communications   | 1         | 0.39%   |
| Microchip Technology              | 1         | 0.39%   |
| Lenovo                            | 1         | 0.39%   |
| Dell                              | 1         | 0.39%   |
| D-Link System                     | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 53        | 16.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 4.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.18%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.55%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.23%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 1.59%   |
| Intel Wireless 7265                                                     | 5         | 1.59%   |
| Intel Wireless 7260                                                     | 5         | 1.59%   |
| ASIX AX88179 Gigabit Ethernet                                           | 5         | 1.59%   |
| Intel WiFi Link 5100                                                    | 4         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.96%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.96%   |
| Intel Wireless 8260                                                     | 3         | 0.96%   |
| Intel Wireless 3165                                                     | 3         | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.96%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.96%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.96%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                       | 3         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 91        | 52%     |
| Realtek Semiconductor           | 40        | 22.86%  |
| Qualcomm Atheros                | 24        | 13.71%  |
| Broadcom                        | 8         | 4.57%   |
| Ralink                          | 3         | 1.71%   |
| MediaTek                        | 2         | 1.14%   |
| Broadcom Limited                | 2         | 1.14%   |
| TP-Link                         | 1         | 0.57%   |
| Quectel Wireless Solutions      | 1         | 0.57%   |
| Qualcomm Atheros Communications | 1         | 0.57%   |
| Dell                            | 1         | 0.57%   |
| D-Link System                   | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 5.68%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 5.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 4.55%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.98%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 3.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.84%   |
| Intel Wireless 7265                                                     | 5         | 2.84%   |
| Intel Wireless 7260                                                     | 5         | 2.84%   |
| Intel WiFi Link 5100                                                    | 4         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.7%    |
| Realtek 802.11ac NIC                                                    | 3         | 1.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.7%    |
| Intel Wireless 8260                                                     | 3         | 1.7%    |
| Intel Wireless 3165                                                     | 3         | 1.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.7%    |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 1.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.7%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.7%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.7%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| Intel Wireless 3160                                                     | 2         | 1.14%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.14%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.14%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.57%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.57%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 75        | 55.97%  |
| Intel                    | 34        | 25.37%  |
| Broadcom                 | 6         | 4.48%   |
| ASIX Electronics         | 5         | 3.73%   |
| Qualcomm Atheros         | 3         | 2.24%   |
| Nvidia                   | 2         | 1.49%   |
| Marvell Technology Group | 2         | 1.49%   |
| JMicron Technology       | 2         | 1.49%   |
| DisplayLink              | 2         | 1.49%   |
| Microchip Technology     | 1         | 0.75%   |
| Lenovo                   | 1         | 0.75%   |
| Broadcom Limited         | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 53        | 38.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 15        | 11.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.68%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 5         | 3.68%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.21%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 2.21%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 2.21%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.47%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.47%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.47%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.47%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.47%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.74%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.74%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.74%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.74%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.74%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.74%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.74%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.74%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.74%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.74%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.74%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.74%   |
| Intel 82566MC Gigabit Network Connection                                       | 1         | 0.74%   |
| DisplayLink USB 3.0 Dual Video Dock                                            | 1         | 0.74%   |
| DisplayLink Kensington SD3600 Dual Video Dock                                  | 1         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.74%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.74%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.74%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 164       | 55.97%  |
| Ethernet | 127       | 43.34%  |
| Modem    | 2         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 78.21%  |
| Ethernet | 39        | 21.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 119       | 71.26%  |
| 1     | 45        | 26.95%  |
| 0     | 3         | 1.8%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 110       | 65.09%  |
| Yes  | 59        | 34.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 50.35%  |
| Realtek Semiconductor           | 23        | 16.08%  |
| Broadcom                        | 13        | 9.09%   |
| Qualcomm Atheros Communications | 8         | 5.59%   |
| IMC Networks                    | 7         | 4.9%    |
| Foxconn / Hon Hai               | 4         | 2.8%    |
| Apple                           | 4         | 2.8%    |
| Ralink                          | 3         | 2.1%    |
| Lite-On Technology              | 3         | 2.1%    |
| Cambridge Silicon Radio         | 3         | 2.1%    |
| Toshiba                         | 1         | 0.7%    |
| Hewlett-Packard                 | 1         | 0.7%    |
| Foxconn International           | 1         | 0.7%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 15.38%  |
| Intel AX201 Bluetooth                                                               | 21        | 14.69%  |
| Realtek Bluetooth Radio                                                             | 15        | 10.49%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 6.99%   |
| Intel AX200 Bluetooth                                                               | 10        | 6.99%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.5%    |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 2.8%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.8%    |
| IMC Networks Bluetooth Radio                                                        | 4         | 2.8%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.1%    |
| Intel AX210 Bluetooth                                                               | 3         | 2.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.1%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 2.1%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.4%    |
| IMC Networks Bluetooth Device                                                       | 2         | 1.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.4%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.4%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.4%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.4%    |
| Apple Bluetooth Host Controller                                                     | 2         | 1.4%    |
| Toshiba Bluetooth Device                                                            | 1         | 0.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.7%    |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.7%    |
| IMC Networks Wireless_Device                                                        | 1         | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.7%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.7%    |
| Foxconn / Hon Hai Bluetooth Adapter                                                 | 1         | 0.7%    |
| Broadcom Bluetooth 3.0 Dongle                                                       | 1         | 0.7%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.7%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.7%    |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 130       | 61.61%  |
| AMD                    | 37        | 17.54%  |
| Nvidia                 | 33        | 15.64%  |
| C-Media Electronics    | 2         | 0.95%   |
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
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 7.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 4.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 4.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 3.94%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 9         | 3.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 3.54%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.36%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 2.36%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.36%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.97%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.97%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 1.57%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.57%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.18%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.18%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.18%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.18%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.79%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.79%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 27.59%  |
| SK hynix            | 34        | 23.45%  |
| Micron Technology   | 22        | 15.17%  |
| Unknown             | 13        | 8.97%   |
| Kingston            | 10        | 6.9%    |
| Unknown (ABCD)      | 7         | 4.83%   |
| Crucial             | 7         | 4.83%   |
| Ramaxel Technology  | 4         | 2.76%   |
| Nanya Technology    | 3         | 2.07%   |
| G.Skill             | 2         | 1.38%   |
| Corsair             | 2         | 1.38%   |
| Unknown             | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 6         | 3.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 5         | 3.16%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 3         | 1.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 3         | 1.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 3         | 1.9%    |
| Unknown RAM Module 4GB SODIMM DDR3                                | 2         | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR3                                | 2         | 1.27%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                        | 2         | 1.27%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 2         | 1.27%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 2         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 2         | 1.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 2         | 1.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 2         | 1.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 2         | 1.27%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 2         | 1.27%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s    | 2         | 1.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 2         | 1.27%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                       | 1         | 0.63%   |
| Unknown RAM Module 4096MB SODIMM DDR2                             | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                       | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2                                | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                            | 1         | 0.63%   |
| Unknown RAM Module 1GB DIMM DDR3 1600MT/s                         | 1         | 0.63%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 1         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.63%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.63%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 0.63%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                     | 1         | 0.63%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s             | 1         | 0.63%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s             | 1         | 0.63%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 1         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 46.51%  |
| DDR3    | 40        | 31.01%  |
| LPDDR4  | 12        | 9.3%    |
| DDR2    | 7         | 5.43%   |
| SDRAM   | 5         | 3.88%   |
| LPDDR3  | 2         | 1.55%   |
| DDR5    | 2         | 1.55%   |
| Unknown | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 111       | 85.38%  |
| Row Of Chips | 15        | 11.54%  |
| Unknown      | 2         | 1.54%   |
| DIMM         | 1         | 0.77%   |
| Chip         | 1         | 0.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 53        | 37.32%  |
| 4096  | 38        | 26.76%  |
| 16384 | 24        | 16.9%   |
| 2048  | 20        | 14.08%  |
| 1024  | 5         | 3.52%   |
| 32768 | 2         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 38        | 27.34%  |
| 1600    | 28        | 20.14%  |
| 2400    | 16        | 11.51%  |
| 2667    | 14        | 10.07%  |
| 2133    | 6         | 4.32%   |
| 1334    | 5         | 3.6%    |
| Unknown | 5         | 3.6%    |
| 4267    | 3         | 2.16%   |
| 2048    | 3         | 2.16%   |
| 1333    | 3         | 2.16%   |
| 1067    | 3         | 2.16%   |
| 667     | 3         | 2.16%   |
| 4199    | 2         | 1.44%   |
| 1867    | 2         | 1.44%   |
| 1066    | 2         | 1.44%   |
| 5600    | 1         | 0.72%   |
| 4800    | 1         | 0.72%   |
| 4266    | 1         | 0.72%   |
| 2933    | 1         | 0.72%   |
| 975     | 1         | 0.72%   |
| 800     | 1         | 0.72%   |

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
| Chicony Electronics                    | 43        | 27.39%  |
| Realtek Semiconductor                  | 18        | 11.46%  |
| IMC Networks                           | 14        | 8.92%   |
| Microdia                               | 11        | 7.01%   |
| Quanta                                 | 10        | 6.37%   |
| Sunplus Innovation Technology          | 7         | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.46%   |
| Syntek                                 | 6         | 3.82%   |
| Suyin                                  | 5         | 3.18%   |
| Bison Electronics                      | 4         | 2.55%   |
| Acer                                   | 4         | 2.55%   |
| Luxvisions Innotech Limited            | 3         | 1.91%   |
| Lite-On Technology                     | 3         | 1.91%   |
| Apple                                  | 3         | 1.91%   |
| Alcor Micro                            | 3         | 1.91%   |
| Silicon Motion                         | 2         | 1.27%   |
| Ricoh                                  | 2         | 1.27%   |
| Logitech                               | 2         | 1.27%   |
| Lenovo                                 | 2         | 1.27%   |
| SunplusIT                              | 1         | 0.64%   |
| Sonix Technology                       | 1         | 0.64%   |
| Razer USA                              | 1         | 0.64%   |
| Intel                                  | 1         | 0.64%   |
| icSpring                               | 1         | 0.64%   |
| Generalplus Technology                 | 1         | 0.64%   |
| Denron                                 | 1         | 0.64%   |
| ARC International                      | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 4.46%   |
| Chicony HP HD Camera                          | 7         | 4.46%   |
| Realtek Integrated_Webcam_HD                  | 6         | 3.82%   |
| Chicony Integrated Camera                     | 6         | 3.82%   |
| Syntek Integrated Camera                      | 5         | 3.18%   |
| Realtek USB Camera                            | 5         | 3.18%   |
| IMC Networks Integrated Camera                | 4         | 2.55%   |
| Microdia Integrated Webcam                    | 3         | 1.91%   |
| Chicony HP Webcam                             | 3         | 1.91%   |
| Chicony HP Truevision HD camera               | 3         | 1.91%   |
| Chicony HD WebCam                             | 3         | 1.91%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 1.91%   |
| Bison Integrated Camera                       | 3         | 1.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.27%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.27%   |
| Sunplus Integrated_Webcam_FHD                 | 2         | 1.27%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 1.27%   |
| Quanta ov9734_techfront_camera                | 2         | 1.27%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.27%   |
| Quanta HD User Facing                         | 2         | 1.27%   |
| Microdia Webcam Vitade AF                     | 2         | 1.27%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.27%   |
| Lite-On Integrated Camera                     | 2         | 1.27%   |
| Lenovo CNF7237&CNF7238                        | 2         | 1.27%   |
| Chicony VGA Webcam                            | 2         | 1.27%   |
| Chicony USB2.0 Camera                         | 2         | 1.27%   |
| Chicony USB 2.0 Camera                        | 2         | 1.27%   |
| Chicony HD User Facing                        | 2         | 1.27%   |
| Chicony EasyCamera                            | 2         | 1.27%   |
| Apple Built-in iSight                         | 2         | 1.27%   |
| Alcor Micro USB 2.0 Camera                    | 2         | 1.27%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.64%   |
| Suyin USB 2.0 Camera                          | 1         | 0.64%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.64%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.64%   |
| SunplusIT PC Camera                           | 1         | 0.64%   |
| Sunplus USB Camera                            | 1         | 0.64%   |
| Sunplus HP Truevision HD                      | 1         | 0.64%   |
| Sunplus FHD Capture                           | 1         | 0.64%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 29.63%  |
| Upek                       | 5         | 18.52%  |
| Synaptics                  | 5         | 18.52%  |
| Shenzhen Goodix Technology | 5         | 18.52%  |
| Elan Microelectronics      | 3         | 11.11%  |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 18.52%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 18.52%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 11.11%  |
| Elan ELAN:ARM-M4                                                           | 3         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.7%    |
| Synaptics UWP WBDI Device                                                  | 1         | 3.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.7%    |
| AuthenTec AES1600                                                          | 1         | 3.7%    |

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
| 0     | 105       | 62.5%   |
| 1     | 47        | 27.98%  |
| 2     | 13        | 7.74%   |
| 3     | 2         | 1.19%   |
| 4     | 1         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 27        | 34.62%  |
| Chipcard              | 21        | 26.92%  |
| Graphics card         | 11        | 14.1%   |
| Bluetooth             | 6         | 7.69%   |
| Net/wireless          | 4         | 5.13%   |
| Camera                | 4         | 5.13%   |
| Storage               | 1         | 1.28%   |
| Multimedia controller | 1         | 1.28%   |
| Flash memory          | 1         | 1.28%   |
| Dvb card              | 1         | 1.28%   |
| Card reader           | 1         | 1.28%   |

