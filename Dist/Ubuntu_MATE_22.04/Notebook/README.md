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

Total: 365

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-56-generic     | 14        | 7.57%   |
| 5.15.0-58-generic     | 10        | 5.41%   |
| 5.15.0-53-generic     | 7         | 3.78%   |
| 5.15.0-52-generic     | 7         | 3.78%   |
| 5.15.0-43-generic     | 7         | 3.78%   |
| 5.15.0-25-generic     | 7         | 3.78%   |
| 5.15.0-47-generic     | 6         | 3.24%   |
| 5.15.0-46-generic     | 6         | 3.24%   |
| 6.2.0-34-generic      | 5         | 2.7%    |
| 6.2.0-32-generic      | 5         | 2.7%    |
| 5.19.0-46-generic     | 5         | 2.7%    |
| 5.19.0-32-generic     | 5         | 2.7%    |
| 5.15.0-60-generic     | 5         | 2.7%    |
| 5.15.0-48-generic     | 5         | 2.7%    |
| 6.2.0-36-generic      | 4         | 2.16%   |
| 5.15.0-40-generic     | 4         | 2.16%   |
| 6.2.0-35-generic      | 3         | 1.62%   |
| 6.2.0-33-generic      | 3         | 1.62%   |
| 6.2.0-26-generic      | 3         | 1.62%   |
| 5.19.0-43-generic     | 3         | 1.62%   |
| 5.19.0-42-generic     | 3         | 1.62%   |
| 5.19.0-38-generic     | 3         | 1.62%   |
| 5.19.0-35-generic     | 3         | 1.62%   |
| 5.15.0-83-generic     | 3         | 1.62%   |
| 5.15.0-67-generic     | 3         | 1.62%   |
| 5.15.0-57-generic     | 3         | 1.62%   |
| 5.15.0-41-generic     | 3         | 1.62%   |
| 5.15.0-30-generic     | 3         | 1.62%   |
| 5.15.0-27-generic     | 3         | 1.62%   |
| 5.19.0-50-generic     | 2         | 1.08%   |
| 5.15.0-79-generic     | 2         | 1.08%   |
| 5.15.0-76-generic     | 2         | 1.08%   |
| 5.15.0-69-generic     | 2         | 1.08%   |
| 5.15.0-52-lowlatency  | 2         | 1.08%   |
| 6.2.3-x64v1-xanmod1   | 1         | 0.54%   |
| 6.2.0-1016-lowlatency | 1         | 0.54%   |
| 6.2.0-1013-lowlatency | 1         | 0.54%   |
| 6.2.0-1011-lowlatency | 1         | 0.54%   |
| 6.2.0-1009-nvidia     | 1         | 0.54%   |
| 6.2.0-1009-lowlatency | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 108       | 65.85%  |
| 5.19.0  | 25        | 15.24%  |
| 6.2.0   | 23        | 14.02%  |
| 6.2.3   | 1         | 0.61%   |
| 6.1.8   | 1         | 0.61%   |
| 6.0.8   | 1         | 0.61%   |
| 6.0.0   | 1         | 0.61%   |
| 5.18.0  | 1         | 0.61%   |
| 5.17.1  | 1         | 0.61%   |
| 5.17.0  | 1         | 0.61%   |
| 5.14.0  | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 108       | 65.85%  |
| 5.19    | 25        | 15.24%  |
| 6.2     | 24        | 14.63%  |
| 6.0     | 2         | 1.22%   |
| 5.17    | 2         | 1.22%   |
| 6.1     | 1         | 0.61%   |
| 5.18    | 1         | 0.61%   |
| 5.14    | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 156       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MATE  | 155       | 99.36%  |
| GNOME | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 153       | 98.08%  |
| Wayland | 2         | 1.28%   |
| Tty     | 1         | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 132       | 84.08%  |
| Unknown | 15        | 9.55%   |
| GDM3    | 9         | 5.73%   |
| SDDM    | 1         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 58        | 36.71%  |
| de_DE | 23        | 14.56%  |
| fr_FR | 22        | 13.92%  |
| it_IT | 11        | 6.96%   |
| ru_RU | 7         | 4.43%   |
| pl_PL | 4         | 2.53%   |
| pt_BR | 3         | 1.9%    |
| es_ES | 3         | 1.9%    |
| en_GB | 3         | 1.9%    |
| en_CA | 3         | 1.9%    |
| en_AU | 3         | 1.9%    |
| C     | 3         | 1.9%    |
| fi_FI | 2         | 1.27%   |
| es_MX | 2         | 1.27%   |
| zh_TW | 1         | 0.63%   |
| zh_CN | 1         | 0.63%   |
| pt_PT | 1         | 0.63%   |
| id_ID | 1         | 0.63%   |
| hu_HU | 1         | 0.63%   |
| es_VE | 1         | 0.63%   |
| es_CL | 1         | 0.63%   |
| en_NZ | 1         | 0.63%   |
| el_GR | 1         | 0.63%   |
| de_CH | 1         | 0.63%   |
| cs_CZ | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 85        | 53.13%  |
| BIOS | 75        | 46.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 131       | 82.91%  |
| Tmpfs   | 13        | 8.23%   |
| Overlay | 7         | 4.43%   |
| Zfs     | 3         | 1.9%    |
| Btrfs   | 2         | 1.27%   |
| Xfs     | 1         | 0.63%   |
| Jfs     | 1         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 123       | 77.36%  |
| Unknown | 22        | 13.84%  |
| MBR     | 14        | 8.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 88.46%  |
| Yes       | 18        | 11.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 63.92%  |
| Yes       | 57        | 36.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 21.15%  |
| Lenovo              | 31        | 19.87%  |
| Dell                | 20        | 12.82%  |
| ASUSTek Computer    | 17        | 10.9%   |
| Acer                | 11        | 7.05%   |
| Sony                | 5         | 3.21%   |
| HUAWEI              | 4         | 2.56%   |
| Apple               | 4         | 2.56%   |
| Google              | 3         | 1.92%   |
| Toshiba             | 2         | 1.28%   |
| Notebook            | 2         | 1.28%   |
| Intel               | 2         | 1.28%   |
| VIT                 | 1         | 0.64%   |
| TrekStor            | 1         | 0.64%   |
| SLIMBOOK            | 1         | 0.64%   |
| Samsung Electronics | 1         | 0.64%   |
| Positivo            | 1         | 0.64%   |
| Panasonic           | 1         | 0.64%   |
| Packard Bell        | 1         | 0.64%   |
| MicroByte           | 1         | 0.64%   |
| LincPlus            | 1         | 0.64%   |
| LG Electronics      | 1         | 0.64%   |
| Kiano               | 1         | 0.64%   |
| IPASON              | 1         | 0.64%   |
| Infinix             | 1         | 0.64%   |
| HYPERPC             | 1         | 0.64%   |
| HONOR               | 1         | 0.64%   |
| GPD                 | 1         | 0.64%   |
| Gigabyte Technology | 1         | 0.64%   |
| Compaq              | 1         | 0.64%   |
| Clevo               | 1         | 0.64%   |
| Chuwi               | 1         | 0.64%   |
| Bluechip Computer   | 1         | 0.64%   |
| AZW                 | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Dell Precision 7520                  | 2         | 1.28%   |
| Dell Latitude 7420                   | 2         | 1.28%   |
| VIT P1400                            | 1         | 0.64%   |
| TrekStor Surfbook A13B               | 1         | 0.64%   |
| Toshiba Satellite P50-B-10Z          | 1         | 0.64%   |
| Toshiba Satellite C50D-A-133         | 1         | 0.64%   |
| Sony VPCEH1E1E                       | 1         | 0.64%   |
| Sony VPCEB2Z1E                       | 1         | 0.64%   |
| Sony VPCEA36FG                       | 1         | 0.64%   |
| Sony VGN-Z21WRN_B                    | 1         | 0.64%   |
| Sony SVF13N2J2ES                     | 1         | 0.64%   |
| SLIMBOOK TITAN                       | 1         | 0.64%   |
| Samsung 905S3G/906S3G/915S3G/9305SG  | 1         | 0.64%   |
| Positivo C4128G-15                   | 1         | 0.64%   |
| Panasonic CF-53SJCZYLM               | 1         | 0.64%   |
| Packard Bell EasyNote ENTG81BA       | 1         | 0.64%   |
| Notebook NV4XMB,ME,MZ                | 1         | 0.64%   |
| Notebook NJx0MU                      | 1         | 0.64%   |
| MicroByte ezbook                     | 1         | 0.64%   |
| LincPlus LINNCPLUS P1                | 1         | 0.64%   |
| LG 17Z990-R.AAS8U1                   | 1         | 0.64%   |
| Lenovo V15 G2 ITL 82KB               | 1         | 0.64%   |
| Lenovo V15 G2 ALC 82KD               | 1         | 0.64%   |
| Lenovo V145-15AST 81MT               | 1         | 0.64%   |
| Lenovo ThinkPad X230 2325Y5L         | 1         | 0.64%   |
| Lenovo ThinkPad X200 74595FG         | 1         | 0.64%   |
| Lenovo ThinkPad T580 20LAS0DL00      | 1         | 0.64%   |
| Lenovo ThinkPad T490s 20NYS58200     | 1         | 0.64%   |
| Lenovo ThinkPad T460p 20FW002CPB     | 1         | 0.64%   |
| Lenovo ThinkPad T430 2347G5U         | 1         | 0.64%   |
| Lenovo ThinkPad T420 4238LY7         | 1         | 0.64%   |
| Lenovo ThinkPad T420 4236MBG         | 1         | 0.64%   |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00 | 1         | 0.64%   |
| Lenovo ThinkPad SL500 27463ZG        | 1         | 0.64%   |
| Lenovo ThinkPad SL 2746AHG           | 1         | 0.64%   |
| Lenovo ThinkPad R61 8918DEG          | 1         | 0.64%   |
| Lenovo ThinkPad P53 20QN000FIX       | 1         | 0.64%   |
| Lenovo ThinkPad L14 Gen 3 21C6S1HW00 | 1         | 0.64%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500 | 1         | 0.64%   |
| Lenovo ThinkPad A275 20KCS09T1G      | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 10.26%  |
| Dell Latitude          | 9         | 5.77%   |
| Lenovo IdeaPad         | 8         | 5.13%   |
| HP Pavilion            | 6         | 3.85%   |
| Acer Aspire            | 6         | 3.85%   |
| Dell Precision         | 5         | 3.21%   |
| HP ProBook             | 4         | 2.56%   |
| HP EliteBook           | 4         | 2.56%   |
| ASUS VivoBook          | 4         | 2.56%   |
| HP Laptop              | 3         | 1.92%   |
| Dell Inspiron          | 3         | 1.92%   |
| ASUS ASUS              | 3         | 1.92%   |
| Toshiba Satellite      | 2         | 1.28%   |
| Lenovo V15             | 2         | 1.28%   |
| Lenovo ThinkBook       | 2         | 1.28%   |
| HP ZBook               | 2         | 1.28%   |
| HP Stream              | 2         | 1.28%   |
| HP OMEN                | 2         | 1.28%   |
| HP 15                  | 2         | 1.28%   |
| Acer TravelMate        | 2         | 1.28%   |
| Acer Extensa           | 2         | 1.28%   |
| VIT P1400              | 1         | 0.64%   |
| TrekStor Surfbook      | 1         | 0.64%   |
| Sony VPCEH1E1E         | 1         | 0.64%   |
| Sony VPCEB2Z1E         | 1         | 0.64%   |
| Sony VPCEA36FG         | 1         | 0.64%   |
| Sony VGN-Z21WRN        | 1         | 0.64%   |
| Sony SVF13N2J2ES       | 1         | 0.64%   |
| SLIMBOOK TITAN         | 1         | 0.64%   |
| Samsung 905S3G         | 1         | 0.64%   |
| Positivo C4128G-15     | 1         | 0.64%   |
| Panasonic CF-53SJCZYLM | 1         | 0.64%   |
| Packard Bell EasyNote  | 1         | 0.64%   |
| Notebook NV4XMB        | 1         | 0.64%   |
| Notebook NJx0MU        | 1         | 0.64%   |
| MicroByte ezbook       | 1         | 0.64%   |
| LincPlus LINNCPLUS     | 1         | 0.64%   |
| LG 17Z990-R.AAS8U1     | 1         | 0.64%   |
| Lenovo V145-15AST      | 1         | 0.64%   |
| Lenovo Legion          | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 29        | 18.59%  |
| 2019    | 14        | 8.97%   |
| 2020    | 12        | 7.69%   |
| 2018    | 12        | 7.69%   |
| 2022    | 10        | 6.41%   |
| 2014    | 9         | 5.77%   |
| 2013    | 9         | 5.77%   |
| 2008    | 9         | 5.77%   |
| 2016    | 8         | 5.13%   |
| 2015    | 8         | 5.13%   |
| 2012    | 8         | 5.13%   |
| 2011    | 8         | 5.13%   |
| 2010    | 5         | 3.21%   |
| 2009    | 5         | 3.21%   |
| 2017    | 4         | 2.56%   |
| 2023    | 2         | 1.28%   |
| 2007    | 2         | 1.28%   |
| 2006    | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 156       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 143       | 89.94%  |
| Enabled  | 16        | 10.06%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 153       | 98.08%  |
| Yes  | 3         | 1.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 44        | 28.21%  |
| 3.01-4.0    | 38        | 24.36%  |
| 16.01-24.0  | 25        | 16.03%  |
| 8.01-16.0   | 22        | 14.1%   |
| 32.01-64.0  | 13        | 8.33%   |
| 24.01-32.0  | 4         | 2.56%   |
| 1.01-2.0    | 4         | 2.56%   |
| 2.01-3.0    | 3         | 1.92%   |
| 64.01-256.0 | 3         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 59        | 34.71%  |
| 2.01-3.0   | 45        | 26.47%  |
| 3.01-4.0   | 29        | 17.06%  |
| 4.01-8.0   | 21        | 12.35%  |
| 8.01-16.0  | 10        | 5.88%   |
| 0.51-1.0   | 5         | 2.94%   |
| 24.01-32.0 | 1         | 0.59%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 75.64%  |
| 2      | 29        | 18.59%  |
| 3      | 8         | 5.13%   |
| 4      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 100       | 64.1%   |
| Yes       | 56        | 35.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 76.28%  |
| No        | 37        | 23.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 98.72%  |
| No        | 2         | 1.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 84.18%  |
| No        | 25        | 15.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 24        | 15.38%  |
| France             | 23        | 14.74%  |
| USA                | 17        | 10.9%   |
| Italy              | 13        | 8.33%   |
| Russia             | 7         | 4.49%   |
| Spain              | 6         | 3.85%   |
| Brazil             | 6         | 3.85%   |
| Poland             | 5         | 3.21%   |
| UK                 | 4         | 2.56%   |
| Turkey             | 3         | 1.92%   |
| Finland            | 3         | 1.92%   |
| Thailand           | 2         | 1.28%   |
| Serbia             | 2         | 1.28%   |
| Romania            | 2         | 1.28%   |
| Portugal           | 2         | 1.28%   |
| Mexico             | 2         | 1.28%   |
| Indonesia          | 2         | 1.28%   |
| India              | 2         | 1.28%   |
| Hungary            | 2         | 1.28%   |
| Greece             | 2         | 1.28%   |
| Estonia            | 2         | 1.28%   |
| Chile              | 2         | 1.28%   |
| Belgium            | 2         | 1.28%   |
| Australia          | 2         | 1.28%   |
| Venezuela          | 1         | 0.64%   |
| Ukraine            | 1         | 0.64%   |
| Taiwan             | 1         | 0.64%   |
| Switzerland        | 1         | 0.64%   |
| Slovenia           | 1         | 0.64%   |
| Peru               | 1         | 0.64%   |
| Paraguay           | 1         | 0.64%   |
| New Zealand        | 1         | 0.64%   |
| Netherlands        | 1         | 0.64%   |
| Libya              | 1         | 0.64%   |
| Hong Kong          | 1         | 0.64%   |
| Georgia            | 1         | 0.64%   |
| Dominican Republic | 1         | 0.64%   |
| Czechia            | 1         | 0.64%   |
| Colombia           | 1         | 0.64%   |
| China              | 1         | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 5         | 3.11%   |
| Warsaw            | 4         | 2.48%   |
| Wittingen         | 3         | 1.86%   |
| Moscow            | 3         | 1.86%   |
| Mannheim          | 3         | 1.86%   |
| Lisbon            | 2         | 1.24%   |
| Hamburg           | 2         | 1.24%   |
| Frankfurt am Main | 2         | 1.24%   |
| Berlin            | 2         | 1.24%   |
| Belgrade          | 2         | 1.24%   |
| Bangkok           | 2         | 1.24%   |
| Xining            | 1         | 0.62%   |
| Wellin            | 1         | 0.62%   |
| Weiden            | 1         | 0.62%   |
| Voronezh          | 1         | 0.62%   |
| Viroflay          | 1         | 0.62%   |
| Villeurbanne      | 1         | 0.62%   |
| Vienna            | 1         | 0.62%   |
| Vaudoy-en-Brie    | 1         | 0.62%   |
| Varna             | 1         | 0.62%   |
| Valenciennes      | 1         | 0.62%   |
| Valence           | 1         | 0.62%   |
| Turku             | 1         | 0.62%   |
| Turin             | 1         | 0.62%   |
| Tulungagung       | 1         | 0.62%   |
| Tula              | 1         | 0.62%   |
| Tripoli           | 1         | 0.62%   |
| Tours             | 1         | 0.62%   |
| Toulouse          | 1         | 0.62%   |
| Tizayuca          | 1         | 0.62%   |
| Thane             | 1         | 0.62%   |
| Tartu             | 1         | 0.62%   |
| Taoyuan District  | 1         | 0.62%   |
| Talcahuano        | 1         | 0.62%   |
| Seville           | 1         | 0.62%   |
| Settimo Torinese  | 1         | 0.62%   |
| Sarzeau           | 1         | 0.62%   |
| Sarospatak        | 1         | 0.62%   |
| Sao Paulo         | 1         | 0.62%   |
| San Fernando      | 1         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 39        | 65     | 20%     |
| Unknown               | 17        | 20     | 8.72%   |
| Seagate               | 17        | 18     | 8.72%   |
| WDC                   | 15        | 15     | 7.69%   |
| Toshiba               | 12        | 16     | 6.15%   |
| SanDisk               | 10        | 12     | 5.13%   |
| Crucial               | 10        | 12     | 5.13%   |
| Kingston              | 9         | 10     | 4.62%   |
| SK hynix              | 8         | 8      | 4.1%    |
| Intel                 | 6         | 6      | 3.08%   |
| Hitachi               | 4         | 4      | 2.05%   |
| China                 | 4         | 5      | 2.05%   |
| A-DATA Technology     | 4         | 4      | 2.05%   |
| Micron Technology     | 3         | 3      | 1.54%   |
| KIOXIA                | 3         | 3      | 1.54%   |
| HGST                  | 3         | 3      | 1.54%   |
| UMIS                  | 2         | 3      | 1.03%   |
| SPCC                  | 2         | 4      | 1.03%   |
| Phison                | 2         | 2      | 1.03%   |
| KingSpec              | 2         | 3      | 1.03%   |
| WDC WDS2              | 1         | 1      | 0.51%   |
| Verbatim              | 1         | 6      | 0.51%   |
| Silicon Motion        | 1         | 1      | 0.51%   |
| Realtek Semiconductor | 1         | 2      | 0.51%   |
| PNY                   | 1         | 1      | 0.51%   |
| Phison Electronics    | 1         | 1      | 0.51%   |
| Patriot               | 1         | 1      | 0.51%   |
| OCZ                   | 1         | 1      | 0.51%   |
| Netac                 | 1         | 1      | 0.51%   |
| LITEONIT              | 1         | 1      | 0.51%   |
| Lenovo                | 1         | 1      | 0.51%   |
| Kston                 | 1         | 1      | 0.51%   |
| JMicron Technology    | 1         | 1      | 0.51%   |
| Intenso               | 1         | 1      | 0.51%   |
| Hjwdz                 | 1         | 1      | 0.51%   |
| Gigabyte Technology   | 1         | 1      | 0.51%   |
| FORESEE               | 1         | 1      | 0.51%   |
| faspeed               | 1         | 1      | 0.51%   |
| Corsair               | 1         | 1      | 0.51%   |
| BIWIN                 | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                            | 3         | 1.47%   |
| Toshiba MQ01ABF050 500GB                          | 3         | 1.47%   |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 1.47%   |
| Kingston SA400S37240G 240GB SSD                   | 3         | 1.47%   |
| Unknown SLD64G  64GB                              | 2         | 0.98%   |
| Unknown MMC Card  64GB                            | 2         | 0.98%   |
| Seagate ST9500420AS 500GB                         | 2         | 0.98%   |
| Seagate ST2000LM015-2E8174 2TB                    | 2         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB                    | 2         | 0.98%   |
| Seagate Expansion 1TB                             | 2         | 0.98%   |
| Samsung SSD 980 PRO 1TB                           | 2         | 0.98%   |
| Samsung SSD 860 EVO 250GB                         | 2         | 0.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.98%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                  | 2         | 0.98%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 2         | 0.98%   |
| Samsung MZALQ512HBLU-00BL2 512GB                  | 2         | 0.98%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 0.98%   |
| Crucial CT240BX500SSD1 240GB                      | 2         | 0.98%   |
| Crucial CT1000BX500SSD1 1TB                       | 2         | 0.98%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD                   | 1         | 0.49%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 0.49%   |
| WDC WD7500BPVX-60JC3T0 752GB                      | 1         | 0.49%   |
| WDC WD5000LPVX-60V0TT0 500GB                      | 1         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 1         | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 0.49%   |
| WDC WD40 EFRX-68N32N0 4TB                         | 1         | 0.49%   |
| WDC WD3200BEVT-22ZCT0 320GB                       | 1         | 0.49%   |
| WDC WD10SPZX-24Z10 1TB                            | 1         | 0.49%   |
| WDC WD10SPZX-22Z10T0 1TB                          | 1         | 0.49%   |
| WDC WD10SPCX-24HWST1 1TB                          | 1         | 0.49%   |
| WDC WD Blue SA510 M.2 2280 500GB SSD              | 1         | 0.49%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB              | 1         | 0.49%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                | 1         | 0.49%   |
| WDC PC SN530 NVMe 256GB                           | 1         | 0.49%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB              | 1         | 0.49%   |
| Verbatim Vi550 S3 128GB                           | 1         | 0.49%   |
| Unknown xD/SD/M.S.                                | 1         | 0.49%   |
| Unknown SLD32G  32GB                              | 1         | 0.49%   |
| Unknown SD32G  32GB                               | 1         | 0.49%   |
| Unknown SD256  256GB                              | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 17        | 18     | 41.46%  |
| WDC     | 9         | 9      | 21.95%  |
| Toshiba | 8         | 11     | 19.51%  |
| Hitachi | 4         | 4      | 9.76%   |
| HGST    | 3         | 3      | 7.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 22     | 27.4%   |
| Crucial             | 10        | 12     | 13.7%   |
| Kingston            | 8         | 9      | 10.96%  |
| SanDisk             | 5         | 6      | 6.85%   |
| China               | 4         | 5      | 5.48%   |
| A-DATA Technology   | 4         | 4      | 5.48%   |
| WDC                 | 2         | 2      | 2.74%   |
| KingSpec            | 2         | 3      | 2.74%   |
| Intel               | 2         | 2      | 2.74%   |
| WDC WDS2            | 1         | 1      | 1.37%   |
| Verbatim            | 1         | 6      | 1.37%   |
| Toshiba             | 1         | 2      | 1.37%   |
| SPCC                | 1         | 3      | 1.37%   |
| SK hynix            | 1         | 1      | 1.37%   |
| PNY                 | 1         | 1      | 1.37%   |
| Patriot             | 1         | 1      | 1.37%   |
| OCZ                 | 1         | 1      | 1.37%   |
| Netac               | 1         | 1      | 1.37%   |
| Micron Technology   | 1         | 1      | 1.37%   |
| LITEONIT            | 1         | 1      | 1.37%   |
| Kston               | 1         | 1      | 1.37%   |
| Intenso             | 1         | 1      | 1.37%   |
| Corsair             | 1         | 1      | 1.37%   |
| Apple               | 1         | 1      | 1.37%   |
| addlink             | 1         | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 65        | 89     | 35.33%  |
| NVMe    | 62        | 90     | 33.7%   |
| HDD     | 39        | 45     | 21.2%   |
| MMC     | 15        | 18     | 8.15%   |
| Unknown | 3         | 3      | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 124    | 51.65%  |
| NVMe | 61        | 89     | 33.52%  |
| MMC  | 15        | 18     | 8.24%   |
| SAS  | 12        | 14     | 6.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 92     | 69.44%  |
| 0.51-1.0   | 23        | 25     | 21.3%   |
| 1.01-2.0   | 6         | 12     | 5.56%   |
| 3.01-4.0   | 3         | 4      | 2.78%   |
| 4.01-10.0  | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 29.19%  |
| 251-500        | 44        | 27.33%  |
| 501-1000       | 18        | 11.18%  |
| 51-100         | 13        | 8.07%   |
| 1001-2000      | 12        | 7.45%   |
| 1-20           | 9         | 5.59%   |
| 21-50          | 8         | 4.97%   |
| 2001-3000      | 5         | 3.11%   |
| More than 3000 | 4         | 2.48%   |
| Unknown        | 1         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 47        | 29.01%  |
| 21-50          | 34        | 20.99%  |
| 101-250        | 27        | 16.67%  |
| 51-100         | 21        | 12.96%  |
| 251-500        | 14        | 8.64%   |
| 501-1000       | 8         | 4.94%   |
| 1001-2000      | 5         | 3.09%   |
| 2001-3000      | 3         | 1.85%   |
| More than 3000 | 2         | 1.23%   |
| Unknown        | 1         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 14.29%  |
| WDC WD7500BPVX-60JC3T0 752GB                 | 1         | 1      | 7.14%   |
| WDC WD40 EFRX-68N32N0 4TB                    | 1         | 1      | 7.14%   |
| Toshiba MK3263GSXN 320GB                     | 1         | 1      | 7.14%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 7.14%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 7.14%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 7.14%   |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 7.14%   |
| Netac SSD 256GB                              | 1         | 1      | 7.14%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 7.14%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 7.14%   |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 28.57%  |
| WDC                 | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| SK hynix            | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| OCZ                 | 1         | 1      | 7.14%   |
| Netac               | 1         | 1      | 7.14%   |
| Kingston            | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 50%     |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 57.14%  |
| SSD  | 4         | 4      | 28.57%  |
| NVMe | 2         | 2      | 14.29%  |

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
| Works    | 93        | 125    | 53.45%  |
| Detected | 67        | 106    | 38.51%  |
| Malfunc  | 14        | 14     | 8.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 53.01%  |
| Samsung Electronics          | 21        | 11.48%  |
| AMD                          | 21        | 11.48%  |
| SanDisk                      | 9         | 4.92%   |
| SK hynix                     | 7         | 3.83%   |
| Phison Electronics           | 4         | 2.19%   |
| KIOXIA                       | 4         | 2.19%   |
| Toshiba America Info Systems | 3         | 1.64%   |
| Nvidia                       | 3         | 1.64%   |
| Union Memory (Shenzhen)      | 2         | 1.09%   |
| Micron Technology            | 2         | 1.09%   |
| Silicon Motion               | 1         | 0.55%   |
| Shenzhen Longsys Electronics | 1         | 0.55%   |
| Realtek Semiconductor        | 1         | 0.55%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.55%   |
| Marvell Technology Group     | 1         | 0.55%   |
| Lenovo                       | 1         | 0.55%   |
| Kingston Technology Company  | 1         | 0.55%   |
| Biwin Storage Technology     | 1         | 0.55%   |
| ADATA Technology             | 1         | 0.55%   |
| Unknown                      | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 8.76%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 12        | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 5.67%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 4.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 3.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 7         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 7         | 3.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 6         | 3.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 2.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 2.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 2.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 2.06%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 3         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.55%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 1.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.55%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 2         | 1.03%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 1.03%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 2         | 1.03%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 2         | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.03%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                                  | 1         | 0.52%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                        | 1         | 0.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.52%   |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 100       | 53.76%  |
| NVMe | 61        | 32.8%   |
| RAID | 16        | 8.6%    |
| IDE  | 9         | 4.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 122       | 78.21%  |
| AMD    | 34        | 21.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 3.21%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.92%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 3         | 1.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.92%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 1.28%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 1.28%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 1.28%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 2         | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.28%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.28%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.28%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.28%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.28%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.28%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.28%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.28%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.28%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 2         | 1.28%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.28%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.28%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.28%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.28%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.28%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.28%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 1.28%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.64%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.64%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.64%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.64%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.64%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz              | 1         | 0.64%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.64%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.64%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz            | 1         | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.64%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 29        | 18.59%  |
| Intel Core i5           | 24        | 15.38%  |
| Other                   | 19        | 12.18%  |
| Intel Celeron           | 16        | 10.26%  |
| Intel Core i3           | 10        | 6.41%   |
| Intel Core 2 Duo        | 10        | 6.41%   |
| AMD Ryzen 7             | 7         | 4.49%   |
| Intel Pentium           | 6         | 3.85%   |
| AMD Ryzen 5             | 6         | 3.85%   |
| Intel Pentium Silver    | 3         | 1.92%   |
| Intel Pentium Dual-Core | 3         | 1.92%   |
| AMD A6                  | 3         | 1.92%   |
| AMD Ryzen 9             | 2         | 1.28%   |
| AMD Ryzen 7 PRO         | 2         | 1.28%   |
| AMD Ryzen 3             | 2         | 1.28%   |
| AMD A4                  | 2         | 1.28%   |
| Intel Xeon              | 1         | 0.64%   |
| Intel Core m5           | 1         | 0.64%   |
| Intel Atom              | 1         | 0.64%   |
| AMD Turion 64 X2 Mobile | 1         | 0.64%   |
| AMD Turion 64 Mobile    | 1         | 0.64%   |
| AMD Sempron             | 1         | 0.64%   |
| AMD Ryzen 5 PRO         | 1         | 0.64%   |
| AMD Quad-Core           | 1         | 0.64%   |
| AMD E1                  | 1         | 0.64%   |
| AMD Athlon X2           | 1         | 0.64%   |
| AMD Athlon II           | 1         | 0.64%   |
| AMD A8                  | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 46.15%  |
| 4      | 57        | 36.54%  |
| 8      | 12        | 7.69%   |
| 6      | 10        | 6.41%   |
| 14     | 2         | 1.28%   |
| 1      | 2         | 1.28%   |
| 10     | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 156       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 101       | 64.74%  |
| 1      | 55        | 35.26%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 156       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 43.83%  |
| 0x806c1    | 8         | 4.94%   |
| 0x40651    | 6         | 3.7%    |
| 0x306a9    | 6         | 3.7%    |
| 0x806ec    | 5         | 3.09%   |
| 0x1067a    | 5         | 3.09%   |
| 0x806d1    | 4         | 2.47%   |
| 0x0a50000c | 4         | 2.47%   |
| 0x706a8    | 3         | 1.85%   |
| 0x506c9    | 3         | 1.85%   |
| 0x406e3    | 3         | 1.85%   |
| 0x406c4    | 3         | 1.85%   |
| 0x30678    | 3         | 1.85%   |
| 0x206a7    | 3         | 1.85%   |
| 0x08108109 | 3         | 1.85%   |
| 0x0700010f | 3         | 1.85%   |
| 0x906c0    | 2         | 1.23%   |
| 0x906a3    | 2         | 1.23%   |
| 0x806e9    | 2         | 1.23%   |
| 0x706e5    | 2         | 1.23%   |
| 0x10676    | 2         | 1.23%   |
| 0x08608103 | 2         | 1.23%   |
| 0x906e9    | 1         | 0.62%   |
| 0x906a4    | 1         | 0.62%   |
| 0x806eb    | 1         | 0.62%   |
| 0x806ea    | 1         | 0.62%   |
| 0x706a1    | 1         | 0.62%   |
| 0x6fd      | 1         | 0.62%   |
| 0x6fb      | 1         | 0.62%   |
| 0x506e3    | 1         | 0.62%   |
| 0x20655    | 1         | 0.62%   |
| 0x0a601203 | 1         | 0.62%   |
| 0x0a50000d | 1         | 0.62%   |
| 0x08608102 | 1         | 0.62%   |
| 0x08101016 | 1         | 0.62%   |
| 0x07030105 | 1         | 0.62%   |
| 0x0600611a | 1         | 0.62%   |
| 0x02000032 | 1         | 0.62%   |
| 0x010000c8 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 11.46%  |
| TigerLake        | 11        | 7.01%   |
| Silvermont       | 11        | 7.01%   |
| IvyBridge        | 11        | 7.01%   |
| SandyBridge      | 10        | 6.37%   |
| Penryn           | 10        | 6.37%   |
| Haswell          | 10        | 6.37%   |
| Icelake          | 8         | 5.1%    |
| Unknown          | 8         | 5.1%    |
| Skylake          | 7         | 4.46%   |
| Zen 3            | 6         | 3.82%   |
| Goldmont plus    | 6         | 3.82%   |
| Zen+             | 4         | 2.55%   |
| Excavator        | 4         | 2.55%   |
| Zen 2            | 3         | 1.91%   |
| Westmere         | 3         | 1.91%   |
| Jaguar           | 3         | 1.91%   |
| Goldmont         | 3         | 1.91%   |
| Core             | 3         | 1.91%   |
| Alderlake Hybrid | 3         | 1.91%   |
| Zen              | 2         | 1.27%   |
| Puma             | 2         | 1.27%   |
| K8 Hammer        | 2         | 1.27%   |
| K10              | 2         | 1.27%   |
| CometLake        | 2         | 1.27%   |
| Broadwell        | 2         | 1.27%   |
| Tremont          | 1         | 0.64%   |
| Nehalem          | 1         | 0.64%   |
| K8 & K10 hybrid  | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 108       | 56.84%  |
| AMD    | 42        | 22.11%  |
| Nvidia | 40        | 21.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 5.21%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 5.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 3.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 3.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 2.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.6%    |
| Intel HD Graphics 530                                                                    | 4         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.08%   |
| AMD Lucienne                                                                             | 4         | 2.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 2.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.56%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.56%   |
| Intel JasperLake [UHD Graphics]                                                          | 3         | 1.56%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.56%   |
| Intel HD Graphics 620                                                                    | 3         | 1.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.56%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.56%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 1.04%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 1.04%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.04%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.04%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.04%   |
| Intel HD Graphics 500                                                                    | 2         | 1.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.04%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.04%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 1.04%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.04%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.04%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.52%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 80        | 51.28%  |
| 1 x AMD        | 28        | 17.95%  |
| Intel + Nvidia | 21        | 13.46%  |
| 1 x Nvidia     | 13        | 8.33%   |
| Intel + AMD    | 7         | 4.49%   |
| AMD + Nvidia   | 6         | 3.85%   |
| 2 x AMD        | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 126       | 80.77%  |
| Proprietary | 26        | 16.67%  |
| Unknown     | 4         | 2.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 73.25%  |
| 0.01-0.5   | 19        | 12.1%   |
| 0.51-1.0   | 8         | 5.1%    |
| 1.01-2.0   | 7         | 4.46%   |
| 3.01-4.0   | 4         | 2.55%   |
| 5.01-6.0   | 3         | 1.91%   |
| 7.01-8.0   | 1         | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 33        | 18.03%  |
| Chimei Innolux          | 27        | 14.75%  |
| LG Display              | 23        | 12.57%  |
| Samsung Electronics     | 20        | 10.93%  |
| AU Optronics            | 20        | 10.93%  |
| Dell                    | 6         | 3.28%   |
| PANDA                   | 4         | 2.19%   |
| Lenovo                  | 4         | 2.19%   |
| Chi Mei Optoelectronics | 4         | 2.19%   |
| Apple                   | 4         | 2.19%   |
| Sharp                   | 3         | 1.64%   |
| BenQ                    | 3         | 1.64%   |
| AOC                     | 3         | 1.64%   |
| Ancor Communications    | 3         | 1.64%   |
| Sony                    | 2         | 1.09%   |
| Philips                 | 2         | 1.09%   |
| Iiyama                  | 2         | 1.09%   |
| Hewlett-Packard         | 2         | 1.09%   |
| Goldstar                | 2         | 1.09%   |
| ViewSonic               | 1         | 0.55%   |
| Unknown                 | 1         | 0.55%   |
| Toshiba                 | 1         | 0.55%   |
| Sceptre Tech            | 1         | 0.55%   |
| Quanta Display          | 1         | 0.55%   |
| Panasonic               | 1         | 0.55%   |
| LGD                     | 1         | 0.55%   |
| LG Philips              | 1         | 0.55%   |
| IBM                     | 1         | 0.55%   |
| HJC                     | 1         | 0.55%   |
| Hitachi                 | 1         | 0.55%   |
| HannStar                | 1         | 0.55%   |
| Eizo                    | 1         | 0.55%   |
| CS_                     | 1         | 0.55%   |
| CSO                     | 1         | 0.55%   |
| Acer                    | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch  | 2         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 2         | 1.08%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                 | 2         | 1.08%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.08%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 1.08%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 600x340mm 27.2-inch         | 1         | 0.54%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.54%   |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 0.54%   |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch               | 1         | 0.54%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.54%   |
| Sharp HDMI SHP10E8 1360x768 521x293mm 23.5-inch                       | 1         | 0.54%   |
| Sceptre Tech Sceptre E24 SPT099D 1920x1080 521x293mm 23.5-inch        | 1         | 0.54%   |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 0.54%   |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1         | 0.54%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.54%   |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch     | 1         | 0.54%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.54%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 530x300mm 24.0-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 950x540mm 43.0-inch | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 580x320mm 26.1-inch  | 1         | 0.54%   |
| Samsung Electronics 173HT02-T01 SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 0.54%   |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch       | 1         | 0.54%   |
| Philips 247EL PHLC084 1920x1080 520x290mm 23.4-inch                   | 1         | 0.54%   |
| Philips 239CQH PHLC0A0 1920x1080 509x286mm 23.0-inch                  | 1         | 0.54%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.54%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.54%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.54%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 43.11%  |
| 1366x768 (WXGA)    | 48        | 28.74%  |
| 2560x1440 (QHD)    | 9         | 5.39%   |
| 1280x800 (WXGA)    | 8         | 4.79%   |
| 3840x2160 (4K)     | 7         | 4.19%   |
| 1600x900 (HD+)     | 5         | 2.99%   |
| 1440x900 (WXGA+)   | 5         | 2.99%   |
| 2560x1600          | 3         | 1.8%    |
| 3840x2400          | 2         | 1.2%    |
| 2160x1440          | 2         | 1.2%    |
| 1920x1200 (WUXGA)  | 2         | 1.2%    |
| 1680x1050 (WSXGA+) | 2         | 1.2%    |
| 2880x1620          | 1         | 0.6%    |
| 1360x768           | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 39.34%  |
| 14      | 23        | 12.57%  |
| 13      | 20        | 10.93%  |
| 17      | 15        | 8.2%    |
| 27      | 13        | 7.1%    |
| 24      | 9         | 4.92%   |
| 23      | 6         | 3.28%   |
| 12      | 6         | 3.28%   |
| 21      | 3         | 1.64%   |
| 11      | 3         | 1.64%   |
| 84      | 2         | 1.09%   |
| 54      | 2         | 1.09%   |
| 31      | 2         | 1.09%   |
| 16      | 2         | 1.09%   |
| 40      | 1         | 0.55%   |
| 25      | 1         | 0.55%   |
| 22      | 1         | 0.55%   |
| 18      | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 110       | 60.77%  |
| 501-600     | 27        | 14.92%  |
| 351-400     | 15        | 8.29%   |
| 201-300     | 15        | 8.29%   |
| 401-500     | 5         | 2.76%   |
| 601-700     | 3         | 1.66%   |
| 1501-2000   | 2         | 1.1%    |
| 1001-1500   | 2         | 1.1%    |
| 801-900     | 1         | 0.55%   |
| Unknown     | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 127       | 83.55%  |
| 16/10   | 22        | 14.47%  |
| 3/2     | 2         | 1.32%   |
| Unknown | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 37.91%  |
| 81-90          | 39        | 21.43%  |
| 201-250        | 15        | 8.24%   |
| 301-350        | 13        | 7.14%   |
| 121-130        | 13        | 7.14%   |
| 61-70          | 6         | 3.3%    |
| More than 1000 | 4         | 2.2%    |
| 71-80          | 4         | 2.2%    |
| 251-300        | 4         | 2.2%    |
| 51-60          | 3         | 1.65%   |
| 91-100         | 3         | 1.65%   |
| 351-500        | 2         | 1.1%    |
| 131-140        | 2         | 1.1%    |
| 111-120        | 2         | 1.1%    |
| 141-150        | 1         | 0.55%   |
| 501-1000       | 1         | 0.55%   |
| Unknown        | 1         | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 39.2%   |
| 101-120       | 50        | 28.41%  |
| 51-100        | 35        | 19.89%  |
| 161-240       | 15        | 8.52%   |
| More than 240 | 3         | 1.7%    |
| 1-50          | 3         | 1.7%    |
| Unknown       | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 120       | 76.43%  |
| 2     | 28        | 17.83%  |
| 3     | 5         | 3.18%   |
| 0     | 3         | 1.91%   |
| 4     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 87        | 36.71%  |
| Intel                             | 86        | 36.29%  |
| Qualcomm Atheros                  | 25        | 10.55%  |
| Broadcom                          | 12        | 5.06%   |
| Ralink                            | 3         | 1.27%   |
| Broadcom Limited                  | 3         | 1.27%   |
| ASIX Electronics                  | 3         | 1.27%   |
| Nvidia                            | 2         | 0.84%   |
| MediaTek                          | 2         | 0.84%   |
| Marvell Technology Group          | 2         | 0.84%   |
| Ericsson Business Mobile Networks | 2         | 0.84%   |
| DisplayLink                       | 2         | 0.84%   |
| TP-Link                           | 1         | 0.42%   |
| Quectel Wireless Solutions        | 1         | 0.42%   |
| Qualcomm Atheros Communications   | 1         | 0.42%   |
| Microchip Technology              | 1         | 0.42%   |
| Lenovo                            | 1         | 0.42%   |
| JMicron Technology                | 1         | 0.42%   |
| Dell                              | 1         | 0.42%   |
| D-Link System                     | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 48        | 16.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14        | 4.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 10        | 3.4%    |
| Intel Wi-Fi 6 AX200                                                            | 10        | 3.4%    |
| Intel Wi-Fi 6 AX201                                                            | 8         | 2.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 7         | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 7         | 2.38%   |
| Intel Wireless 8265 / 8275                                                     | 7         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 5         | 1.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 5         | 1.7%    |
| Intel Wireless 7265                                                            | 5         | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 5         | 1.7%    |
| Realtek 802.11ac NIC                                                           | 4         | 1.36%   |
| Intel Wireless 7260                                                            | 4         | 1.36%   |
| Intel WiFi Link 5100                                                           | 4         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 4         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.02%   |
| Intel Wireless 3165                                                            | 3         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 1.02%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 3         | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 3         | 1.02%   |
| Intel Centrino Wireless-N 2230                                                 | 3         | 1.02%   |
| Intel Centrino Advanced-N 6235                                                 | 3         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 3         | 1.02%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.02%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 2         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2         | 0.68%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.68%   |
| Intel Wireless 8260                                                            | 2         | 0.68%   |
| Intel Wireless 3160                                                            | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 52.12%  |
| Realtek Semiconductor           | 36        | 21.82%  |
| Qualcomm Atheros                | 23        | 13.94%  |
| Broadcom                        | 8         | 4.85%   |
| Ralink                          | 3         | 1.82%   |
| MediaTek                        | 2         | 1.21%   |
| Broadcom Limited                | 2         | 1.21%   |
| TP-Link                         | 1         | 0.61%   |
| Quectel Wireless Solutions      | 1         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.61%   |
| Dell                            | 1         | 0.61%   |
| D-Link System                   | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 6.02%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 6.02%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 4.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 4.22%   |
| Intel Wireless 8265 / 8275                                              | 7         | 4.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 3.01%   |
| Intel Wireless 7265                                                     | 5         | 3.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.01%   |
| Realtek 802.11ac NIC                                                    | 4         | 2.41%   |
| Intel Wireless 7260                                                     | 4         | 2.41%   |
| Intel WiFi Link 5100                                                    | 4         | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.81%   |
| Intel Wireless 3165                                                     | 3         | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.81%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 3         | 1.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.81%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.81%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.2%    |
| Intel Wireless 8260                                                     | 2         | 1.2%    |
| Intel Wireless 3160                                                     | 2         | 1.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.2%    |
| TP-Link 802.11ac NIC                                                    | 1         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.6%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.6%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 55.65%  |
| Intel                    | 33        | 26.61%  |
| Broadcom                 | 6         | 4.84%   |
| Qualcomm Atheros         | 3         | 2.42%   |
| ASIX Electronics         | 3         | 2.42%   |
| Nvidia                   | 2         | 1.61%   |
| Marvell Technology Group | 2         | 1.61%   |
| DisplayLink              | 2         | 1.61%   |
| Microchip Technology     | 1         | 0.81%   |
| Lenovo                   | 1         | 0.81%   |
| JMicron Technology       | 1         | 0.81%   |
| Broadcom Limited         | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 48        | 38.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14        | 11.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 4.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 3.97%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.38%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 2.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 2.38%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 2.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.59%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.59%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.59%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.59%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.59%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.59%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.79%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.79%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.79%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.79%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.79%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.79%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.79%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.79%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.79%   |
| Intel 82566MC Gigabit Network Connection                                       | 1         | 0.79%   |
| DisplayLink USB3.0 Dual Video Dock                                             | 1         | 0.79%   |
| DisplayLink Kensington SD3600 Dual Video Dock                                  | 1         | 0.79%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.79%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.79%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 56%     |
| Ethernet | 119       | 43.27%  |
| Modem    | 2         | 0.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 78.44%  |
| Ethernet | 36        | 21.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 112       | 71.79%  |
| 1     | 42        | 26.92%  |
| 0     | 2         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 65.61%  |
| Yes  | 54        | 34.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 50%     |
| Realtek Semiconductor           | 21        | 15.67%  |
| Broadcom                        | 13        | 9.7%    |
| Qualcomm Atheros Communications | 7         | 5.22%   |
| IMC Networks                    | 6         | 4.48%   |
| Foxconn / Hon Hai               | 4         | 2.99%   |
| Apple                           | 4         | 2.99%   |
| Ralink                          | 3         | 2.24%   |
| Lite-On Technology              | 3         | 2.24%   |
| Cambridge Silicon Radio         | 3         | 2.24%   |
| Toshiba                         | 1         | 0.75%   |
| Hewlett-Packard                 | 1         | 0.75%   |
| Foxconn International           | 1         | 0.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 14.93%  |
| Intel AX201 Bluetooth                                                               | 19        | 14.18%  |
| Realtek Bluetooth Radio                                                             | 18        | 13.43%  |
| Intel AX200 Bluetooth                                                               | 10        | 7.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 6.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 3.73%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.24%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.24%   |
| Intel AX210 Bluetooth                                                               | 3         | 2.24%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.24%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 2.24%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.49%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.49%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.49%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.49%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.49%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.49%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.49%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.49%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.75%   |
| Intel Bluetooth Device                                                              | 1         | 0.75%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.75%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.75%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.75%   |
| Broadcom Bluetooth 3.0 USB Dongle                                                   | 1         | 0.75%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.75%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.75%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 119       | 60.71%  |
| AMD                    | 36        | 18.37%  |
| Nvidia                 | 30        | 15.31%  |
| C-Media Electronics    | 2         | 1.02%   |
| Realtek Semiconductor  | 1         | 0.51%   |
| Plantronics            | 1         | 0.51%   |
| Meizu                  | 1         | 0.51%   |
| Lenovo                 | 1         | 0.51%   |
| Kingston Technology    | 1         | 0.51%   |
| GN Netcom              | 1         | 0.51%   |
| Generalplus Technology | 1         | 0.51%   |
| DSEA A/S               | 1         | 0.51%   |
| ASUSTek Computer       | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 8.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 4.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 4.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 3.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.8%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 3.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 3.38%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 2.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.53%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 2.11%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 2.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.11%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.11%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.27%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.27%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.27%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.84%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.84%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.84%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.84%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.84%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 39        | 28.06%  |
| SK hynix            | 32        | 23.02%  |
| Micron Technology   | 21        | 15.11%  |
| Unknown             | 13        | 9.35%   |
| Kingston            | 10        | 7.19%   |
| Unknown (ABCD)      | 6         | 4.32%   |
| Crucial             | 6         | 4.32%   |
| Ramaxel Technology  | 4         | 2.88%   |
| Nanya Technology    | 3         | 2.16%   |
| G.Skill             | 2         | 1.44%   |
| Corsair             | 2         | 1.44%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 3.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.97%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.32%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.32%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                           | 1         | 0.66%   |
| Unknown RAM Module 1GB DIMM DDR3 1600MT/s                        | 1         | 0.66%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 1         | 0.66%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s            | 1         | 0.66%   |
| SK hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1333MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 56        | 45.53%  |
| DDR3    | 39        | 31.71%  |
| LPDDR4  | 11        | 8.94%   |
| DDR2    | 7         | 5.69%   |
| SDRAM   | 5         | 4.07%   |
| LPDDR3  | 2         | 1.63%   |
| DDR5    | 2         | 1.63%   |
| Unknown | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 84.68%  |
| Row Of Chips | 15        | 12.1%   |
| Unknown      | 2         | 1.61%   |
| DIMM         | 1         | 0.81%   |
| Chip         | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 51        | 37.5%   |
| 4096  | 36        | 26.47%  |
| 16384 | 22        | 16.18%  |
| 2048  | 20        | 14.71%  |
| 1024  | 5         | 3.68%   |
| 32768 | 2         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 35        | 26.32%  |
| 1600    | 27        | 20.3%   |
| 2400    | 15        | 11.28%  |
| 2667    | 14        | 10.53%  |
| 2133    | 5         | 3.76%   |
| 1334    | 5         | 3.76%   |
| Unknown | 5         | 3.76%   |
| 4267    | 3         | 2.26%   |
| 2048    | 3         | 2.26%   |
| 1333    | 3         | 2.26%   |
| 1067    | 3         | 2.26%   |
| 667     | 3         | 2.26%   |
| 4199    | 2         | 1.5%    |
| 1867    | 2         | 1.5%    |
| 1066    | 2         | 1.5%    |
| 5600    | 1         | 0.75%   |
| 4800    | 1         | 0.75%   |
| 4266    | 1         | 0.75%   |
| 2933    | 1         | 0.75%   |
| 975     | 1         | 0.75%   |
| 800     | 1         | 0.75%   |

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
| Chicony Electronics                    | 39        | 26.35%  |
| Realtek Semiconductor                  | 18        | 12.16%  |
| IMC Networks                           | 13        | 8.78%   |
| Quanta                                 | 10        | 6.76%   |
| Microdia                               | 9         | 6.08%   |
| Sunplus Innovation Technology          | 7         | 4.73%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.73%   |
| Syntek                                 | 6         | 4.05%   |
| Suyin                                  | 5         | 3.38%   |
| Bison Electronics                      | 5         | 3.38%   |
| Luxvisions Innotech Limited            | 3         | 2.03%   |
| Lite-On Technology                     | 3         | 2.03%   |
| Apple                                  | 3         | 2.03%   |
| Alcor Micro                            | 3         | 2.03%   |
| Acer                                   | 3         | 2.03%   |
| Silicon Motion                         | 2         | 1.35%   |
| Ricoh                                  | 2         | 1.35%   |
| Lenovo                                 | 2         | 1.35%   |
| SunplusIT                              | 1         | 0.68%   |
| Sonix Technology                       | 1         | 0.68%   |
| Razer USA                              | 1         | 0.68%   |
| Logitech                               | 1         | 0.68%   |
| Intel                                  | 1         | 0.68%   |
| Generalplus Technology                 | 1         | 0.68%   |
| Denron                                 | 1         | 0.68%   |
| ARC International                      | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 6         | 4.05%   |
| IMC Networks USB2.0 HD UVC WebCam             | 6         | 4.05%   |
| Chicony HP HD Camera                          | 6         | 4.05%   |
| Syntek Integrated Camera                      | 5         | 3.38%   |
| Chicony Integrated Camera                     | 5         | 3.38%   |
| IMC Networks Integrated Camera                | 4         | 2.7%    |
| Realtek USB Camera                            | 3         | 2.03%   |
| Chicony HP Webcam                             | 3         | 2.03%   |
| Chicony HP Truevision HD camera               | 3         | 2.03%   |
| Chicony HD WebCam                             | 3         | 2.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.03%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.35%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.35%   |
| Sunplus Integrated_Webcam_FHD                 | 2         | 1.35%   |
| Realtek USB2.0 camera                         | 2         | 1.35%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 1.35%   |
| Quanta ov9734_techfront_camera                | 2         | 1.35%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.35%   |
| Quanta HD User Facing                         | 2         | 1.35%   |
| Microdia Webcam Vitade AF                     | 2         | 1.35%   |
| Microdia Integrated Webcam                    | 2         | 1.35%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.35%   |
| Lite-On Integrated Camera                     | 2         | 1.35%   |
| Lenovo CNF7237&CNF7238                        | 2         | 1.35%   |
| Chicony VGA Webcam                            | 2         | 1.35%   |
| Chicony USB2.0 Camera                         | 2         | 1.35%   |
| Chicony HD User Facing                        | 2         | 1.35%   |
| Chicony EasyCamera                            | 2         | 1.35%   |
| Bison Integrated Camera                       | 2         | 1.35%   |
| Apple Built-in iSight                         | 2         | 1.35%   |
| Alcor Micro USB 2.0 Camera                    | 2         | 1.35%   |
| Acer Integrated Camera                        | 2         | 1.35%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.68%   |
| Suyin USB 2.0 Camera                          | 1         | 0.68%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.68%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.68%   |
| SunplusIT PC Camera                           | 1         | 0.68%   |
| Sunplus HP Truevision HD                      | 1         | 0.68%   |
| Sunplus FHD Capture                           | 1         | 0.68%   |
| Sunplus Camera                                | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 26.92%  |
| Upek                       | 5         | 19.23%  |
| Synaptics                  | 5         | 19.23%  |
| Shenzhen Goodix Technology | 5         | 19.23%  |
| Elan Microelectronics      | 3         | 11.54%  |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 19.23%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 19.23%  |
| Elan ELAN:ARM-M4                                                           | 3         | 11.54%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.85%   |
| Synaptics UWP WBDI Device                                                  | 1         | 3.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.85%   |
| AuthenTec AES1600                                                          | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 11        | 55%     |
| Alcor Micro           | 5         | 25%     |
| Upek                  | 1         | 5%      |
| SCM Microsystems      | 1         | 5%      |
| O2 Micro              | 1         | 5%      |
| Advanced Card Systems | 1         | 5%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 5         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15%     |
| Broadcom 5880                                                                | 3         | 15%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5%      |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5%      |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 98        | 62.42%  |
| 1     | 44        | 28.03%  |
| 2     | 12        | 7.64%   |
| 3     | 3         | 1.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 26        | 35.62%  |
| Chipcard              | 20        | 27.4%   |
| Graphics card         | 8         | 10.96%  |
| Bluetooth             | 6         | 8.22%   |
| Net/wireless          | 4         | 5.48%   |
| Camera                | 4         | 5.48%   |
| Storage               | 1         | 1.37%   |
| Multimedia controller | 1         | 1.37%   |
| Flash memory          | 1         | 1.37%   |
| Dvb card              | 1         | 1.37%   |
| Card reader           | 1         | 1.37%   |

