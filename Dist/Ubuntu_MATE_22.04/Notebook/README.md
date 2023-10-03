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

Total: 340

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.15.0-56-generic     | 14        | 8.43%   |
| 5.15.0-58-generic     | 10        | 6.02%   |
| 5.15.0-53-generic     | 7         | 4.22%   |
| 5.15.0-52-generic     | 7         | 4.22%   |
| 5.15.0-43-generic     | 7         | 4.22%   |
| 5.15.0-25-generic     | 7         | 4.22%   |
| 5.15.0-47-generic     | 6         | 3.61%   |
| 5.15.0-46-generic     | 6         | 3.61%   |
| 5.19.0-46-generic     | 5         | 3.01%   |
| 5.19.0-32-generic     | 5         | 3.01%   |
| 5.15.0-60-generic     | 5         | 3.01%   |
| 5.15.0-48-generic     | 5         | 3.01%   |
| 5.15.0-40-generic     | 4         | 2.41%   |
| 6.2.0-32-generic      | 3         | 1.81%   |
| 6.2.0-26-generic      | 3         | 1.81%   |
| 5.19.0-43-generic     | 3         | 1.81%   |
| 5.19.0-42-generic     | 3         | 1.81%   |
| 5.19.0-38-generic     | 3         | 1.81%   |
| 5.19.0-35-generic     | 3         | 1.81%   |
| 5.15.0-83-generic     | 3         | 1.81%   |
| 5.15.0-67-generic     | 3         | 1.81%   |
| 5.15.0-57-generic     | 3         | 1.81%   |
| 5.15.0-41-generic     | 3         | 1.81%   |
| 5.15.0-30-generic     | 3         | 1.81%   |
| 5.15.0-27-generic     | 3         | 1.81%   |
| 6.2.0-33-generic      | 2         | 1.2%    |
| 5.19.0-50-generic     | 2         | 1.2%    |
| 5.15.0-79-generic     | 2         | 1.2%    |
| 5.15.0-76-generic     | 2         | 1.2%    |
| 5.15.0-69-generic     | 2         | 1.2%    |
| 5.15.0-52-lowlatency  | 2         | 1.2%    |
| 6.2.3-x64v1-xanmod1   | 1         | 0.6%    |
| 6.2.0-1013-lowlatency | 1         | 0.6%    |
| 6.2.0-1011-lowlatency | 1         | 0.6%    |
| 6.2.0-1009-nvidia     | 1         | 0.6%    |
| 6.2.0-1009-lowlatency | 1         | 0.6%    |
| 6.1.8-x64v1-xanmod1   | 1         | 0.6%    |
| 6.0.8-x64v1-xanmod1   | 1         | 0.6%    |
| 6.0.0-060000-generic  | 1         | 0.6%    |
| 5.19.0-41-generic     | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 105       | 71.43%  |
| 5.19.0  | 25        | 17.01%  |
| 6.2.0   | 9         | 6.12%   |
| 6.2.3   | 1         | 0.68%   |
| 6.1.8   | 1         | 0.68%   |
| 6.0.8   | 1         | 0.68%   |
| 6.0.0   | 1         | 0.68%   |
| 5.18.0  | 1         | 0.68%   |
| 5.17.1  | 1         | 0.68%   |
| 5.17.0  | 1         | 0.68%   |
| 5.14.0  | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 105       | 71.43%  |
| 5.19    | 25        | 17.01%  |
| 6.2     | 10        | 6.8%    |
| 6.0     | 2         | 1.36%   |
| 5.17    | 2         | 1.36%   |
| 6.1     | 1         | 0.68%   |
| 5.18    | 1         | 0.68%   |
| 5.14    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 141       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| MATE  | 140       | 99.29%  |
| GNOME | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 138       | 97.87%  |
| Wayland | 2         | 1.42%   |
| Tty     | 1         | 0.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 120       | 84.51%  |
| Unknown | 12        | 8.45%   |
| GDM3    | 9         | 6.34%   |
| SDDM    | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 52        | 36.36%  |
| fr_FR | 21        | 14.69%  |
| de_DE | 20        | 13.99%  |
| it_IT | 9         | 6.29%   |
| ru_RU | 7         | 4.9%    |
| pl_PL | 4         | 2.8%    |
| es_ES | 3         | 2.1%    |
| en_GB | 3         | 2.1%    |
| en_CA | 3         | 2.1%    |
| en_AU | 3         | 2.1%    |
| C     | 3         | 2.1%    |
| pt_BR | 2         | 1.4%    |
| fi_FI | 2         | 1.4%    |
| es_MX | 2         | 1.4%    |
| zh_TW | 1         | 0.7%    |
| zh_CN | 1         | 0.7%    |
| pt_PT | 1         | 0.7%    |
| hu_HU | 1         | 0.7%    |
| es_CL | 1         | 0.7%    |
| en_NZ | 1         | 0.7%    |
| el_GR | 1         | 0.7%    |
| de_CH | 1         | 0.7%    |
| cs_CZ | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 53.1%   |
| BIOS | 68        | 46.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 117       | 82.39%  |
| Tmpfs   | 11        | 7.75%   |
| Overlay | 7         | 4.93%   |
| Zfs     | 3         | 2.11%   |
| Btrfs   | 2         | 1.41%   |
| Xfs     | 1         | 0.7%    |
| Jfs     | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 112       | 78.32%  |
| Unknown | 19        | 13.29%  |
| MBR     | 12        | 8.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 126       | 89.36%  |
| Yes       | 15        | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 64.34%  |
| Yes       | 51        | 35.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 32        | 22.7%   |
| Lenovo              | 28        | 19.86%  |
| Dell                | 20        | 14.18%  |
| ASUSTek Computer    | 15        | 10.64%  |
| Acer                | 10        | 7.09%   |
| Sony                | 5         | 3.55%   |
| HUAWEI              | 4         | 2.84%   |
| Apple               | 4         | 2.84%   |
| Google              | 3         | 2.13%   |
| Toshiba             | 2         | 1.42%   |
| Notebook            | 2         | 1.42%   |
| Intel               | 2         | 1.42%   |
| TrekStor            | 1         | 0.71%   |
| SLIMBOOK            | 1         | 0.71%   |
| Samsung Electronics | 1         | 0.71%   |
| MicroByte           | 1         | 0.71%   |
| LincPlus            | 1         | 0.71%   |
| LG Electronics      | 1         | 0.71%   |
| Kiano               | 1         | 0.71%   |
| IPASON              | 1         | 0.71%   |
| HYPERPC             | 1         | 0.71%   |
| HONOR               | 1         | 0.71%   |
| Compaq              | 1         | 0.71%   |
| Chuwi               | 1         | 0.71%   |
| Bluechip Computer   | 1         | 0.71%   |
| AZW                 | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell Precision 7520                   | 2         | 1.42%   |
| Dell Latitude 7420                    | 2         | 1.42%   |
| TrekStor Surfbook A13B                | 1         | 0.71%   |
| Toshiba Satellite P50-B-10Z           | 1         | 0.71%   |
| Toshiba Satellite C50D-A-133          | 1         | 0.71%   |
| Sony VPCEH1E1E                        | 1         | 0.71%   |
| Sony VPCEB2Z1E                        | 1         | 0.71%   |
| Sony VPCEA36FG                        | 1         | 0.71%   |
| Sony VGN-Z21WRN_B                     | 1         | 0.71%   |
| Sony SVF13N2J2ES                      | 1         | 0.71%   |
| SLIMBOOK TITAN                        | 1         | 0.71%   |
| Samsung 905S3G/906S3G/915S3G/9305SG   | 1         | 0.71%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 0.71%   |
| Notebook NJx0MU                       | 1         | 0.71%   |
| MicroByte ezbook                      | 1         | 0.71%   |
| LincPlus LINNCPLUS P1                 | 1         | 0.71%   |
| LG 17Z990-R.AAS8U1                    | 1         | 0.71%   |
| Lenovo V15 G2 ITL 82KB                | 1         | 0.71%   |
| Lenovo V15 G2 ALC 82KD                | 1         | 0.71%   |
| Lenovo V145-15AST 81MT                | 1         | 0.71%   |
| Lenovo ThinkPad X230 2325Y5L          | 1         | 0.71%   |
| Lenovo ThinkPad X200 74595FG          | 1         | 0.71%   |
| Lenovo ThinkPad T580 20LAS0DL00       | 1         | 0.71%   |
| Lenovo ThinkPad T490s 20NYS58200      | 1         | 0.71%   |
| Lenovo ThinkPad T460p 20FW002CPB      | 1         | 0.71%   |
| Lenovo ThinkPad T430 2347G5U          | 1         | 0.71%   |
| Lenovo ThinkPad T420 4238LY7          | 1         | 0.71%   |
| Lenovo ThinkPad T420 4236MBG          | 1         | 0.71%   |
| Lenovo ThinkPad T15 Gen 1 20S6S1HN00  | 1         | 0.71%   |
| Lenovo ThinkPad SL500 27463ZG         | 1         | 0.71%   |
| Lenovo ThinkPad SL 2746AHG            | 1         | 0.71%   |
| Lenovo ThinkPad R61 8918DEG           | 1         | 0.71%   |
| Lenovo ThinkPad L14 Gen 3 21C6S1HW00  | 1         | 0.71%   |
| Lenovo ThinkPad E15 Gen 2 20TDS0T500  | 1         | 0.71%   |
| Lenovo ThinkBook 16p Gen 2 20YM       | 1         | 0.71%   |
| Lenovo ThinkBook 14 G2 ITL 20VD       | 1         | 0.71%   |
| Lenovo Legion Pro 5 16ARX8 82WM       | 1         | 0.71%   |
| Lenovo IdeaPad S145-14IIL 81W6        | 1         | 0.71%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 1         | 0.71%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9   | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 14        | 9.93%   |
| Dell Latitude      | 9         | 6.38%   |
| Lenovo IdeaPad     | 7         | 4.96%   |
| HP Pavilion        | 6         | 4.26%   |
| Dell Precision     | 5         | 3.55%   |
| Acer Aspire        | 5         | 3.55%   |
| HP EliteBook       | 4         | 2.84%   |
| HP ProBook         | 3         | 2.13%   |
| HP Laptop          | 3         | 2.13%   |
| Dell Inspiron      | 3         | 2.13%   |
| ASUS VivoBook      | 3         | 2.13%   |
| ASUS ASUS          | 3         | 2.13%   |
| Toshiba Satellite  | 2         | 1.42%   |
| Lenovo V15         | 2         | 1.42%   |
| Lenovo ThinkBook   | 2         | 1.42%   |
| HP ZBook           | 2         | 1.42%   |
| HP Stream          | 2         | 1.42%   |
| HP OMEN            | 2         | 1.42%   |
| HP 15              | 2         | 1.42%   |
| Acer TravelMate    | 2         | 1.42%   |
| Acer Extensa       | 2         | 1.42%   |
| TrekStor Surfbook  | 1         | 0.71%   |
| Sony VPCEH1E1E     | 1         | 0.71%   |
| Sony VPCEB2Z1E     | 1         | 0.71%   |
| Sony VPCEA36FG     | 1         | 0.71%   |
| Sony VGN-Z21WRN    | 1         | 0.71%   |
| Sony SVF13N2J2ES   | 1         | 0.71%   |
| SLIMBOOK TITAN     | 1         | 0.71%   |
| Samsung 905S3G     | 1         | 0.71%   |
| Notebook NV4XMB    | 1         | 0.71%   |
| Notebook NJx0MU    | 1         | 0.71%   |
| MicroByte ezbook   | 1         | 0.71%   |
| LincPlus LINNCPLUS | 1         | 0.71%   |
| LG 17Z990-R.AAS8U1 | 1         | 0.71%   |
| Lenovo V145-15AST  | 1         | 0.71%   |
| Lenovo Legion      | 1         | 0.71%   |
| Lenovo G500        | 1         | 0.71%   |
| Kiano Elegance     | 1         | 0.71%   |
| IPASON MaxBook     | 1         | 0.71%   |
| Intel Kabylake     | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 26        | 18.44%  |
| 2020 | 12        | 8.51%   |
| 2019 | 12        | 8.51%   |
| 2018 | 11        | 7.8%    |
| 2022 | 10        | 7.09%   |
| 2008 | 9         | 6.38%   |
| 2014 | 8         | 5.67%   |
| 2012 | 8         | 5.67%   |
| 2016 | 7         | 4.96%   |
| 2013 | 7         | 4.96%   |
| 2011 | 7         | 4.96%   |
| 2015 | 6         | 4.26%   |
| 2010 | 5         | 3.55%   |
| 2017 | 4         | 2.84%   |
| 2009 | 4         | 2.84%   |
| 2023 | 2         | 1.42%   |
| 2007 | 2         | 1.42%   |
| 2006 | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 141       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 129       | 89.58%  |
| Enabled  | 15        | 10.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 138       | 97.87%  |
| Yes  | 3         | 2.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 28.37%  |
| 3.01-4.0    | 34        | 24.11%  |
| 8.01-16.0   | 22        | 15.6%   |
| 16.01-24.0  | 21        | 14.89%  |
| 32.01-64.0  | 12        | 8.51%   |
| 24.01-32.0  | 4         | 2.84%   |
| 2.01-3.0    | 3         | 2.13%   |
| 64.01-256.0 | 3         | 2.13%   |
| 1.01-2.0    | 2         | 1.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 53        | 34.42%  |
| 2.01-3.0   | 39        | 25.32%  |
| 3.01-4.0   | 25        | 16.23%  |
| 4.01-8.0   | 21        | 13.64%  |
| 8.01-16.0  | 10        | 6.49%   |
| 0.51-1.0   | 5         | 3.25%   |
| 24.01-32.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 75.18%  |
| 2      | 28        | 19.86%  |
| 3      | 7         | 4.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 64.54%  |
| Yes       | 50        | 35.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 75.89%  |
| No        | 34        | 24.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 98.58%  |
| No        | 2         | 1.42%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 85.92%  |
| No        | 20        | 14.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 22        | 15.6%   |
| France             | 21        | 14.89%  |
| USA                | 15        | 10.64%  |
| Italy              | 11        | 7.8%    |
| Russia             | 7         | 4.96%   |
| Spain              | 6         | 4.26%   |
| Poland             | 5         | 3.55%   |
| Brazil             | 5         | 3.55%   |
| UK                 | 4         | 2.84%   |
| Turkey             | 3         | 2.13%   |
| Finland            | 3         | 2.13%   |
| Serbia             | 2         | 1.42%   |
| Mexico             | 2         | 1.42%   |
| India              | 2         | 1.42%   |
| Hungary            | 2         | 1.42%   |
| Greece             | 2         | 1.42%   |
| Estonia            | 2         | 1.42%   |
| Chile              | 2         | 1.42%   |
| Belgium            | 2         | 1.42%   |
| Australia          | 2         | 1.42%   |
| Ukraine            | 1         | 0.71%   |
| Thailand           | 1         | 0.71%   |
| Taiwan             | 1         | 0.71%   |
| Switzerland        | 1         | 0.71%   |
| Slovenia           | 1         | 0.71%   |
| Romania            | 1         | 0.71%   |
| Portugal           | 1         | 0.71%   |
| Peru               | 1         | 0.71%   |
| Paraguay           | 1         | 0.71%   |
| New Zealand        | 1         | 0.71%   |
| Netherlands        | 1         | 0.71%   |
| Libya              | 1         | 0.71%   |
| Indonesia          | 1         | 0.71%   |
| Hong Kong          | 1         | 0.71%   |
| Georgia            | 1         | 0.71%   |
| Dominican Republic | 1         | 0.71%   |
| Czechia            | 1         | 0.71%   |
| Colombia           | 1         | 0.71%   |
| China              | 1         | 0.71%   |
| Canada             | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Warsaw            | 4         | 2.76%   |
| Paris             | 4         | 2.76%   |
| Moscow            | 3         | 2.07%   |
| Mannheim          | 3         | 2.07%   |
| Wittingen         | 2         | 1.38%   |
| Frankfurt am Main | 2         | 1.38%   |
| Berlin            | 2         | 1.38%   |
| Belgrade          | 2         | 1.38%   |
| Xining            | 1         | 0.69%   |
| Wellin            | 1         | 0.69%   |
| Weiden            | 1         | 0.69%   |
| Voronezh          | 1         | 0.69%   |
| Viroflay          | 1         | 0.69%   |
| Villeurbanne      | 1         | 0.69%   |
| Vaudoy-en-Brie    | 1         | 0.69%   |
| Varna             | 1         | 0.69%   |
| Valenciennes      | 1         | 0.69%   |
| Valence           | 1         | 0.69%   |
| Turku             | 1         | 0.69%   |
| Turin             | 1         | 0.69%   |
| Tulungagung       | 1         | 0.69%   |
| Tula              | 1         | 0.69%   |
| Tripoli           | 1         | 0.69%   |
| Tours             | 1         | 0.69%   |
| Toulouse          | 1         | 0.69%   |
| Tizayuca          | 1         | 0.69%   |
| Thane             | 1         | 0.69%   |
| Tartu             | 1         | 0.69%   |
| Taoyuan District  | 1         | 0.69%   |
| Talcahuano        | 1         | 0.69%   |
| Seville           | 1         | 0.69%   |
| Settimo Torinese  | 1         | 0.69%   |
| Sarzeau           | 1         | 0.69%   |
| Sarospatak        | 1         | 0.69%   |
| Sao Paulo         | 1         | 0.69%   |
| San Fernando      | 1         | 0.69%   |
| Saint-Nicolas     | 1         | 0.69%   |
| Saint-Apollinaire | 1         | 0.69%   |
| Rotorua           | 1         | 0.69%   |
| Rostov-on-Don     | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 35        | 57     | 20%     |
| Unknown               | 15        | 18     | 8.57%   |
| Seagate               | 13        | 14     | 7.43%   |
| WDC                   | 12        | 12     | 6.86%   |
| Toshiba               | 12        | 16     | 6.86%   |
| SanDisk               | 10        | 12     | 5.71%   |
| Crucial               | 10        | 12     | 5.71%   |
| SK hynix              | 8         | 8      | 4.57%   |
| Kingston              | 8         | 9      | 4.57%   |
| Intel                 | 4         | 4      | 2.29%   |
| Hitachi               | 4         | 4      | 2.29%   |
| China                 | 4         | 5      | 2.29%   |
| A-DATA Technology     | 4         | 4      | 2.29%   |
| Micron Technology     | 3         | 3      | 1.71%   |
| KIOXIA                | 3         | 3      | 1.71%   |
| HGST                  | 3         | 3      | 1.71%   |
| UMIS                  | 2         | 3      | 1.14%   |
| SPCC                  | 2         | 4      | 1.14%   |
| Phison                | 2         | 2      | 1.14%   |
| KingSpec              | 2         | 2      | 1.14%   |
| WDC WDS2              | 1         | 1      | 0.57%   |
| Verbatim              | 1         | 6      | 0.57%   |
| Silicon Motion        | 1         | 1      | 0.57%   |
| Realtek Semiconductor | 1         | 2      | 0.57%   |
| Patriot               | 1         | 1      | 0.57%   |
| OCZ                   | 1         | 1      | 0.57%   |
| Netac                 | 1         | 1      | 0.57%   |
| LITEONIT              | 1         | 1      | 0.57%   |
| Lenovo                | 1         | 1      | 0.57%   |
| Kston                 | 1         | 1      | 0.57%   |
| JMicron Technology    | 1         | 1      | 0.57%   |
| Intenso               | 1         | 1      | 0.57%   |
| Hjwdz                 | 1         | 1      | 0.57%   |
| Gigabyte Technology   | 1         | 1      | 0.57%   |
| faspeed               | 1         | 1      | 0.57%   |
| Corsair               | 1         | 1      | 0.57%   |
| Apple                 | 1         | 1      | 0.57%   |
| addlink               | 1         | 1      | 0.57%   |
| ADATA Technology      | 1         | 1      | 0.57%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 3         | 1.64%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 1.64%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.64%   |
| Unknown SLD64G  64GB                                | 2         | 1.09%   |
| Unknown MMC Card  64GB                              | 2         | 1.09%   |
| Seagate ST9500420AS 500GB                           | 2         | 1.09%   |
| Seagate ST2000LM015-2E8174 2TB                      | 2         | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 1.09%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 1.09%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 1.09%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 2         | 1.09%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 1.09%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 1.09%   |
| Crucial CT1000BX500SSD1 1TB                         | 2         | 1.09%   |
| WDC WDS2 50G2B0B-00YS 250GB SSD                     | 1         | 0.55%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.55%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 0.55%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 0.55%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 0.55%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 0.55%   |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 0.55%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 0.55%   |
| WDC WD Blue SA510 M.2 2280 500GB SSD                | 1         | 0.55%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 1         | 0.55%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 0.55%   |
| WDC PC SN530 NVMe 256GB                             | 1         | 0.55%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB                | 1         | 0.55%   |
| Verbatim Vi550 S3 512GB                             | 1         | 0.55%   |
| Unknown xD/SD/M.S.                                  | 1         | 0.55%   |
| Unknown SLD32G  32GB                                | 1         | 0.55%   |
| Unknown SD256  256GB                                | 1         | 0.55%   |
| Unknown SC64G  64GB                                 | 1         | 0.55%   |
| Unknown NVMe SSD Drive 512GB                        | 1         | 0.55%   |
| Unknown MMC Card  7GB                               | 1         | 0.55%   |
| Unknown MMC Card  16GB                              | 1         | 0.55%   |
| Unknown CJTD4R  64GB                                | 1         | 0.55%   |
| Unknown Biwin  64GB                                 | 1         | 0.55%   |
| Unknown BGND3R  32GB                                | 1         | 0.55%   |
| Unknown 00000  4GB                                  | 1         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 14     | 38.24%  |
| Toshiba | 8         | 11     | 23.53%  |
| WDC     | 6         | 6      | 17.65%  |
| Hitachi | 4         | 4      | 11.76%  |
| HGST    | 3         | 3      | 8.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 19     | 25%     |
| Crucial             | 10        | 12     | 14.71%  |
| Kingston            | 7         | 8      | 10.29%  |
| SanDisk             | 5         | 6      | 7.35%   |
| China               | 4         | 5      | 5.88%   |
| A-DATA Technology   | 4         | 4      | 5.88%   |
| WDC                 | 2         | 2      | 2.94%   |
| KingSpec            | 2         | 2      | 2.94%   |
| WDC WDS2            | 1         | 1      | 1.47%   |
| Verbatim            | 1         | 6      | 1.47%   |
| Toshiba             | 1         | 2      | 1.47%   |
| SPCC                | 1         | 3      | 1.47%   |
| SK hynix            | 1         | 1      | 1.47%   |
| Patriot             | 1         | 1      | 1.47%   |
| OCZ                 | 1         | 1      | 1.47%   |
| Netac               | 1         | 1      | 1.47%   |
| Micron Technology   | 1         | 1      | 1.47%   |
| LITEONIT            | 1         | 1      | 1.47%   |
| Kston               | 1         | 1      | 1.47%   |
| JMicron Technology  | 1         | 1      | 1.47%   |
| Intenso             | 1         | 1      | 1.47%   |
| Intel               | 1         | 1      | 1.47%   |
| Corsair             | 1         | 1      | 1.47%   |
| Apple               | 1         | 1      | 1.47%   |
| addlink             | 1         | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 59        | 83     | 35.98%  |
| NVMe    | 56        | 80     | 34.15%  |
| HDD     | 33        | 38     | 20.12%  |
| MMC     | 13        | 16     | 7.93%   |
| Unknown | 3         | 3      | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 84        | 112    | 51.53%  |
| NVMe | 56        | 80     | 34.36%  |
| MMC  | 13        | 16     | 7.98%   |
| SAS  | 10        | 12     | 6.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 65        | 77     | 68.42%  |
| 0.51-1.0   | 23        | 29     | 24.21%  |
| 1.01-2.0   | 5         | 12     | 5.26%   |
| 3.01-4.0   | 1         | 2      | 1.05%   |
| 4.01-10.0  | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 31.03%  |
| 251-500        | 36        | 24.83%  |
| 501-1000       | 17        | 11.72%  |
| 51-100         | 11        | 7.59%   |
| 1001-2000      | 10        | 6.9%    |
| 1-20           | 9         | 6.21%   |
| 21-50          | 8         | 5.52%   |
| 2001-3000      | 5         | 3.45%   |
| More than 3000 | 3         | 2.07%   |
| Unknown        | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 44        | 30.34%  |
| 21-50          | 30        | 20.69%  |
| 101-250        | 25        | 17.24%  |
| 51-100         | 16        | 11.03%  |
| 251-500        | 12        | 8.28%   |
| 501-1000       | 8         | 5.52%   |
| 1001-2000      | 5         | 3.45%   |
| 2001-3000      | 3         | 2.07%   |
| More than 3000 | 1         | 0.69%   |
| Unknown        | 1         | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-60JC3T0 752GB                 | 1         | 1      | 8.33%   |
| Toshiba MK3263GSXN 320GB                     | 1         | 1      | 8.33%   |
| SK hynix BC711 HFM512GD3JX013N 512GB         | 1         | 1      | 8.33%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 8.33%   |
| Samsung Electronics MZVLQ512HBLU-00BH1 512GB | 1         | 1      | 8.33%   |
| OCZ VERTEX3 240GB SSD                        | 1         | 1      | 8.33%   |
| Netac SSD 256GB                              | 1         | 1      | 8.33%   |
| Kingston SA400S37240G 240GB SSD              | 1         | 1      | 8.33%   |
| Intel SSDSC2KW512G8 512GB                    | 1         | 1      | 8.33%   |
| Hitachi HTS725032A9A364 320GB                | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 25%     |
| WDC                 | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| SK hynix            | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| OCZ                 | 1         | 1      | 8.33%   |
| Netac               | 1         | 1      | 8.33%   |
| Kingston            | 1         | 1      | 8.33%   |
| Intel               | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 1         | 1      | 16.67%  |
| Toshiba | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 6      | 50%     |
| SSD  | 4         | 4      | 33.33%  |
| NVMe | 2         | 2      | 16.67%  |

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
| Works    | 83        | 111    | 53.21%  |
| Detected | 61        | 97     | 39.1%   |
| Malfunc  | 12        | 12     | 7.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 87        | 52.73%  |
| Samsung Electronics          | 19        | 11.52%  |
| AMD                          | 19        | 11.52%  |
| SanDisk                      | 9         | 5.45%   |
| SK hynix                     | 7         | 4.24%   |
| KIOXIA                       | 4         | 2.42%   |
| Toshiba America Info Systems | 3         | 1.82%   |
| Phison Electronics           | 3         | 1.82%   |
| Union Memory (Shenzhen)      | 2         | 1.21%   |
| Nvidia                       | 2         | 1.21%   |
| Micron Technology            | 2         | 1.21%   |
| Silicon Motion               | 1         | 0.61%   |
| Realtek Semiconductor        | 1         | 0.61%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.61%   |
| Marvell Technology Group     | 1         | 0.61%   |
| Lenovo                       | 1         | 0.61%   |
| Kingston Technology Company  | 1         | 0.61%   |
| ADATA Technology             | 1         | 0.61%   |
| Unknown                      | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 15        | 8.57%   |
| Samsung NVMe SSD Controller 980                                                        | 11        | 6.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 9         | 5.14%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 4.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 4%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 7         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 3.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 5         | 2.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 5         | 2.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 5         | 2.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 4         | 2.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.71%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 2         | 1.14%   |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 1.14%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 2         | 1.14%   |
| Intel SSD 670p Series [Keystone Harbor]                                                | 2         | 1.14%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 1.14%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.14%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 1.14%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.14%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                                  | 1         | 0.57%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                                  | 1         | 0.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.57%   |
| Toshiba America Info Systems Toshiba America Info SATA controller                      | 1         | 0.57%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.57%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                     | 1         | 0.57%   |
| SK hynix PC611 NVMe Solid State Drive                                                  | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 87        | 51.79%  |
| NVMe | 56        | 33.33%  |
| RAID | 16        | 9.52%   |
| IDE  | 9         | 5.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 109       | 77.3%   |
| AMD    | 32        | 22.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 5         | 3.55%   |
| Intel Core i7-3517U CPU @ 1.90GHz            | 3         | 2.13%   |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 3         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 3         | 2.13%   |
| Intel Pentium CPU N3540 @ 2.16GHz            | 2         | 1.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 2         | 1.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 2         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 2         | 1.42%   |
| Intel Core i5-2540M CPU @ 2.60GHz            | 2         | 1.42%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 2         | 1.42%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 1.42%   |
| Intel Core i3-10110U CPU @ 2.10GHz           | 2         | 1.42%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz           | 2         | 1.42%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz         | 2         | 1.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz            | 2         | 1.42%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.42%   |
| Intel Celeron CPU N2830 @ 2.16GHz            | 2         | 1.42%   |
| Intel 12th Gen Core i7-12700H                | 2         | 1.42%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz      | 2         | 1.42%   |
| AMD Ryzen 9 5900HX with Radeon Graphics      | 2         | 1.42%   |
| AMD Ryzen 7 5800H with Radeon Graphics       | 2         | 1.42%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 2         | 1.42%   |
| AMD Ryzen 5 4600H with Radeon Graphics       | 2         | 1.42%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 2         | 1.42%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz         | 1         | 0.71%   |
| Intel Pentium Silver N6000 @ 1.10GHz         | 1         | 0.71%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz     | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz  | 1         | 0.71%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz  | 1         | 0.71%   |
| Intel Pentium CPU N4200 @ 1.10GHz            | 1         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.71%   |
| Intel Pentium CPU B940 @ 2.00GHz             | 1         | 0.71%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz             | 1         | 0.71%   |
| Intel Core i7-8850H CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-8665U CPU @ 1.90GHz            | 1         | 0.71%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz           | 1         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 25        | 17.73%  |
| Intel Core i5           | 22        | 15.6%   |
| Other                   | 18        | 12.77%  |
| Intel Celeron           | 12        | 8.51%   |
| Intel Core i3           | 10        | 7.09%   |
| Intel Core 2 Duo        | 10        | 7.09%   |
| AMD Ryzen 7             | 7         | 4.96%   |
| Intel Pentium           | 5         | 3.55%   |
| AMD Ryzen 5             | 5         | 3.55%   |
| AMD A6                  | 3         | 2.13%   |
| Intel Pentium Silver    | 2         | 1.42%   |
| Intel Pentium Dual-Core | 2         | 1.42%   |
| AMD Ryzen 9             | 2         | 1.42%   |
| AMD Ryzen 7 PRO         | 2         | 1.42%   |
| AMD Ryzen 3             | 2         | 1.42%   |
| AMD A4                  | 2         | 1.42%   |
| Intel Xeon              | 1         | 0.71%   |
| Intel Core m5           | 1         | 0.71%   |
| Intel Atom              | 1         | 0.71%   |
| AMD Turion 64 X2 Mobile | 1         | 0.71%   |
| AMD Turion 64 Mobile    | 1         | 0.71%   |
| AMD Sempron             | 1         | 0.71%   |
| AMD Ryzen 5 PRO         | 1         | 0.71%   |
| AMD Quad-Core           | 1         | 0.71%   |
| AMD E1                  | 1         | 0.71%   |
| AMD Athlon X2           | 1         | 0.71%   |
| AMD Athlon II           | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 64        | 45.39%  |
| 4      | 52        | 36.88%  |
| 8      | 12        | 8.51%   |
| 6      | 8         | 5.67%   |
| 14     | 2         | 1.42%   |
| 1      | 2         | 1.42%   |
| 10     | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 141       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 93        | 65.96%  |
| 1      | 48        | 34.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 40.82%  |
| 0x806c1    | 8         | 5.44%   |
| 0x40651    | 6         | 4.08%   |
| 0x306a9    | 6         | 4.08%   |
| 0x806ec    | 5         | 3.4%    |
| 0x806d1    | 4         | 2.72%   |
| 0x1067a    | 4         | 2.72%   |
| 0x0a50000c | 4         | 2.72%   |
| 0x706a8    | 3         | 2.04%   |
| 0x506c9    | 3         | 2.04%   |
| 0x406e3    | 3         | 2.04%   |
| 0x406c4    | 3         | 2.04%   |
| 0x30678    | 3         | 2.04%   |
| 0x206a7    | 3         | 2.04%   |
| 0x0700010f | 3         | 2.04%   |
| 0x906a3    | 2         | 1.36%   |
| 0x806e9    | 2         | 1.36%   |
| 0x706e5    | 2         | 1.36%   |
| 0x10676    | 2         | 1.36%   |
| 0x08608103 | 2         | 1.36%   |
| 0x08108109 | 2         | 1.36%   |
| 0x906e9    | 1         | 0.68%   |
| 0x906c0    | 1         | 0.68%   |
| 0x906a4    | 1         | 0.68%   |
| 0x806eb    | 1         | 0.68%   |
| 0x806ea    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x6fd      | 1         | 0.68%   |
| 0x6fb      | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x20655    | 1         | 0.68%   |
| 0x0a601203 | 1         | 0.68%   |
| 0x0a50000d | 1         | 0.68%   |
| 0x08608102 | 1         | 0.68%   |
| 0x08101016 | 1         | 0.68%   |
| 0x07030105 | 1         | 0.68%   |
| 0x02000032 | 1         | 0.68%   |
| 0x010000c8 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 11.97%  |
| TigerLake        | 11        | 7.75%   |
| IvyBridge        | 10        | 7.04%   |
| Silvermont       | 9         | 6.34%   |
| Penryn           | 9         | 6.34%   |
| Haswell          | 9         | 6.34%   |
| SandyBridge      | 8         | 5.63%   |
| Unknown          | 8         | 5.63%   |
| IceLake          | 7         | 4.93%   |
| Zen 3            | 6         | 4.23%   |
| Skylake          | 6         | 4.23%   |
| Goldmont plus    | 5         | 3.52%   |
| Zen+             | 3         | 2.11%   |
| Zen 2            | 3         | 2.11%   |
| Westmere         | 3         | 2.11%   |
| Jaguar           | 3         | 2.11%   |
| Goldmont         | 3         | 2.11%   |
| Excavator        | 3         | 2.11%   |
| Core             | 3         | 2.11%   |
| Alderlake Hybrid | 3         | 2.11%   |
| Zen              | 2         | 1.41%   |
| Puma             | 2         | 1.41%   |
| K8 Hammer        | 2         | 1.41%   |
| K10              | 2         | 1.41%   |
| Broadwell        | 2         | 1.41%   |
| Nehalem          | 1         | 0.7%    |
| K8 & K10 hybrid  | 1         | 0.7%    |
| CometLake        | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 97        | 56.07%  |
| AMD    | 40        | 23.12%  |
| Nvidia | 36        | 20.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 5.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 5.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 4%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 4%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 2.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 2.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 2.29%   |
| AMD Lucienne                                                                             | 4         | 2.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 2.29%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.71%   |
| Intel HD Graphics 620                                                                    | 3         | 1.71%   |
| Intel HD Graphics 530                                                                    | 3         | 1.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.71%   |
| AMD Renoir                                                                               | 3         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.14%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 2         | 1.14%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.14%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.14%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 1.14%   |
| Intel HD Graphics 5500                                                                   | 2         | 1.14%   |
| Intel HD Graphics 500                                                                    | 2         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.14%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.14%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 1.14%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.14%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 2         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.57%   |
| Nvidia TU117M                                                                            | 1         | 0.57%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.57%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.57%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 50.35%  |
| 1 x AMD        | 26        | 18.44%  |
| Intel + Nvidia | 19        | 13.48%  |
| 1 x Nvidia     | 11        | 7.8%    |
| Intel + AMD    | 7         | 4.96%   |
| AMD + Nvidia   | 6         | 4.26%   |
| 2 x AMD        | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 80.14%  |
| Proprietary | 24        | 17.02%  |
| Unknown     | 4         | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 73.94%  |
| 0.01-0.5   | 18        | 12.68%  |
| 0.51-1.0   | 7         | 4.93%   |
| 1.01-2.0   | 6         | 4.23%   |
| 5.01-6.0   | 3         | 2.11%   |
| 3.01-4.0   | 2         | 1.41%   |
| 7.01-8.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 29        | 17.47%  |
| Chimei Innolux          | 24        | 14.46%  |
| LG Display              | 22        | 13.25%  |
| Samsung Electronics     | 18        | 10.84%  |
| AU Optronics            | 18        | 10.84%  |
| Dell                    | 6         | 3.61%   |
| Chi Mei Optoelectronics | 4         | 2.41%   |
| Apple                   | 4         | 2.41%   |
| Sharp                   | 3         | 1.81%   |
| PANDA                   | 3         | 1.81%   |
| Lenovo                  | 3         | 1.81%   |
| AOC                     | 3         | 1.81%   |
| Ancor Communications    | 3         | 1.81%   |
| Sony                    | 2         | 1.2%    |
| Iiyama                  | 2         | 1.2%    |
| Hewlett-Packard         | 2         | 1.2%    |
| Goldstar                | 2         | 1.2%    |
| BenQ                    | 2         | 1.2%    |
| ViewSonic               | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |
| Toshiba                 | 1         | 0.6%    |
| Sceptre Tech            | 1         | 0.6%    |
| Quanta Display          | 1         | 0.6%    |
| Philips                 | 1         | 0.6%    |
| Panasonic               | 1         | 0.6%    |
| LGD                     | 1         | 0.6%    |
| LG Philips              | 1         | 0.6%    |
| IBM                     | 1         | 0.6%    |
| Hitachi                 | 1         | 0.6%    |
| HannStar                | 1         | 0.6%    |
| Eizo                    | 1         | 0.6%    |
| CS_                     | 1         | 0.6%    |
| CSO                     | 1         | 0.6%    |
| Acer                    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 2         | 1.19%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 2         | 1.19%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 1.19%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 2         | 1.19%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.19%   |
| BOE LCD Monitor BOE0713 1920x1080 344x193mm 15.5-inch                 | 2         | 1.19%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 2         | 1.19%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 1.19%   |
| ViewSonic VP2765 SERIES VSC9F28 1920x1080 598x336mm 27.0-inch         | 1         | 0.6%    |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.6%    |
| Toshiba LCD Monitor LCD2109 1280x800 261x163mm 12.1-inch              | 1         | 0.6%    |
| Sharp LQ156M1JW26 SHP1532 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.6%    |
| Sharp HDMI SHP10E8 1360x768 521x293mm 23.5-inch                       | 1         | 0.6%    |
| Sceptre Tech E24 SPT099D 1920x1080 530x300mm 24.0-inch                | 1         | 0.6%    |
| Samsung Electronics SMT27A300 SAM087A 1920x1080 598x336mm 27.0-inch   | 1         | 0.6%    |
| Samsung Electronics SMB2220N SAM06A2 1920x1080 477x268mm 21.5-inch    | 1         | 0.6%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.6%    |
| Samsung Electronics S24C750 SAM0A5D 1920x1080 531x299mm 24.0-inch     | 1         | 0.6%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 1         | 0.6%    |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3157 1280x800 303x190mm 14.1-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4A51 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC415A 3840x2400 302x189mm 14.0-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM094E 1920x1080 700x390mm 31.5-inch | 1         | 0.6%    |
| Samsung Electronics 173HT02-T01 SEC5044 1920x1080 382x215mm 17.3-inch | 1         | 0.6%    |
| Quanta Display LCD Monitor QDS0027 1280x800 331x207mm 15.4-inch       | 1         | 0.6%    |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                   | 1         | 0.6%    |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.6%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.6%    |
| LGD LCD Monitor 1366x768                                              | 1         | 0.6%    |
| LG Philips LCD Monitor LPLA106 1440x900 367x230mm 17.1-inch           | 1         | 0.6%    |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch           | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 43.14%  |
| 1366x768 (WXGA)    | 41        | 26.8%   |
| 2560x1440 (QHD)    | 9         | 5.88%   |
| 1280x800 (WXGA)    | 8         | 5.23%   |
| 3840x2160 (4K)     | 6         | 3.92%   |
| 1600x900 (HD+)     | 5         | 3.27%   |
| 1440x900 (WXGA+)   | 5         | 3.27%   |
| 2560x1600          | 3         | 1.96%   |
| 3840x2400          | 2         | 1.31%   |
| 2160x1440          | 2         | 1.31%   |
| 1920x1200 (WUXGA)  | 2         | 1.31%   |
| 1680x1050 (WSXGA+) | 2         | 1.31%   |
| 2880x1620          | 1         | 0.65%   |
| 1360x768           | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 64        | 38.55%  |
| 14      | 22        | 13.25%  |
| 13      | 18        | 10.84%  |
| 17      | 14        | 8.43%   |
| 27      | 13        | 7.83%   |
| 24      | 8         | 4.82%   |
| 23      | 5         | 3.01%   |
| 12      | 5         | 3.01%   |
| 21      | 3         | 1.81%   |
| 11      | 3         | 1.81%   |
| 54      | 2         | 1.2%    |
| 16      | 2         | 1.2%    |
| 84      | 1         | 0.6%    |
| 40      | 1         | 0.6%    |
| 31      | 1         | 0.6%    |
| 25      | 1         | 0.6%    |
| 22      | 1         | 0.6%    |
| 18      | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 60.37%  |
| 501-600     | 25        | 15.24%  |
| 351-400     | 14        | 8.54%   |
| 201-300     | 14        | 8.54%   |
| 401-500     | 5         | 3.05%   |
| 601-700     | 2         | 1.22%   |
| 1001-1500   | 2         | 1.22%   |
| 801-900     | 1         | 0.61%   |
| 1501-2000   | 1         | 0.61%   |
| Unknown     | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 114       | 82.01%  |
| 16/10   | 22        | 15.83%  |
| 3/2     | 2         | 1.44%   |
| Unknown | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 37.58%  |
| 81-90          | 36        | 21.82%  |
| 301-350        | 13        | 7.88%   |
| 201-250        | 13        | 7.88%   |
| 121-130        | 12        | 7.27%   |
| 61-70          | 5         | 3.03%   |
| 71-80          | 4         | 2.42%   |
| 251-300        | 4         | 2.42%   |
| More than 1000 | 3         | 1.82%   |
| 51-60          | 3         | 1.82%   |
| 131-140        | 2         | 1.21%   |
| 111-120        | 2         | 1.21%   |
| 91-100         | 2         | 1.21%   |
| 351-500        | 1         | 0.61%   |
| 141-150        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |
| Unknown        | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 62        | 38.99%  |
| 101-120       | 45        | 28.3%   |
| 51-100        | 31        | 19.5%   |
| 161-240       | 15        | 9.43%   |
| More than 240 | 3         | 1.89%   |
| 1-50          | 2         | 1.26%   |
| Unknown       | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 109       | 76.76%  |
| 2     | 24        | 16.9%   |
| 3     | 5         | 3.52%   |
| 0     | 3         | 2.11%   |
| 4     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 36.92%  |
| Realtek Semiconductor             | 77        | 35.98%  |
| Qualcomm Atheros                  | 20        | 9.35%   |
| Broadcom                          | 12        | 5.61%   |
| Ralink                            | 3         | 1.4%    |
| Broadcom Limited                  | 3         | 1.4%    |
| ASIX Electronics                  | 3         | 1.4%    |
| Nvidia                            | 2         | 0.93%   |
| MediaTek                          | 2         | 0.93%   |
| Marvell Technology Group          | 2         | 0.93%   |
| Ericsson Business Mobile Networks | 2         | 0.93%   |
| DisplayLink                       | 2         | 0.93%   |
| TP-Link                           | 1         | 0.47%   |
| Quectel Wireless Solutions        | 1         | 0.47%   |
| Qualcomm Atheros Communications   | 1         | 0.47%   |
| Microchip Technology              | 1         | 0.47%   |
| Lenovo                            | 1         | 0.47%   |
| Dell                              | 1         | 0.47%   |
| D-Link System                     | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 15.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14        | 5.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 10        | 3.75%   |
| Intel Wi-Fi 6 AX201                                                            | 8         | 3%      |
| Intel Wi-Fi 6 AX200                                                            | 8         | 3%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 6         | 2.25%   |
| Intel Wireless 8265 / 8275                                                     | 6         | 2.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.87%   |
| Intel Wireless 7265                                                            | 5         | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 5         | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 1.87%   |
| Realtek 802.11ac NIC                                                           | 4         | 1.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 4         | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 1.5%    |
| Intel Wireless 7260                                                            | 4         | 1.5%    |
| Intel WiFi Link 5100                                                           | 4         | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 4         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.12%   |
| Intel Wireless 3165                                                            | 3         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                        | 3         | 1.12%   |
| Intel Centrino Wireless-N 2230                                                 | 3         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 3         | 1.12%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.12%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2         | 0.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.75%   |
| Intel Wireless 8260                                                            | 2         | 0.75%   |
| Intel Wireless 3160                                                            | 2         | 0.75%   |
| Intel Wi-Fi 6 AX201 160MHz                                                     | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.75%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.75%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 52.67%  |
| Realtek Semiconductor           | 33        | 22%     |
| Qualcomm Atheros                | 18        | 12%     |
| Broadcom                        | 8         | 5.33%   |
| Ralink                          | 3         | 2%      |
| MediaTek                        | 2         | 1.33%   |
| Broadcom Limited                | 2         | 1.33%   |
| TP-Link                         | 1         | 0.67%   |
| Quectel Wireless Solutions      | 1         | 0.67%   |
| Qualcomm Atheros Communications | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| D-Link System                   | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 6.62%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 5.3%    |
| Intel Wi-Fi 6 AX200                                                     | 8         | 5.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.97%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.31%   |
| Intel Wireless 7265                                                     | 5         | 3.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 3.31%   |
| Realtek 802.11ac NIC                                                    | 4         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.65%   |
| Intel Wireless 7260                                                     | 4         | 2.65%   |
| Intel WiFi Link 5100                                                    | 4         | 2.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.99%   |
| Intel Wireless 3165                                                     | 3         | 1.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.99%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.32%   |
| Intel Wireless 8260                                                     | 2         | 1.32%   |
| Intel Wireless 3160                                                     | 2         | 1.32%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.32%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.32%   |
| TP-Link 802.11ac NIC                                                    | 1         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.66%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.66%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.66%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.66%   |
| Realtek Realtek WLAN controller                                         | 1         | 0.66%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.66%   |
| Quectel Wireless Solutions EM12G-ACER                                   | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 54.46%  |
| Intel                    | 30        | 26.79%  |
| Broadcom                 | 6         | 5.36%   |
| Qualcomm Atheros         | 3         | 2.68%   |
| ASIX Electronics         | 3         | 2.68%   |
| Nvidia                   | 2         | 1.79%   |
| Marvell Technology Group | 2         | 1.79%   |
| DisplayLink              | 2         | 1.79%   |
| Microchip Technology     | 1         | 0.89%   |
| Lenovo                   | 1         | 0.89%   |
| Broadcom Limited         | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 35.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 14        | 12.28%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 4.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 4.39%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 2.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 2.63%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 2.63%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.75%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.75%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.75%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 1.75%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.75%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.75%   |
| Intel Ethernet Connection (13) I219-V                                          | 2         | 1.75%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.88%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.88%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.88%   |
| Microchip LAN7500 Ethernet 10/100/1000 Adapter                                 | 1         | 0.88%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.88%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.88%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                                         | 1         | 0.88%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.88%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.88%   |
| Intel 82566MC Gigabit Network Connection                                       | 1         | 0.88%   |
| DisplayLink USB3.0 dock                                                        | 1         | 0.88%   |
| DisplayLink Kensington SD3600 Dual Video Dock                                  | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.88%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.88%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.88%   |
| Broadcom Limited NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 139       | 56.05%  |
| Ethernet | 107       | 43.15%  |
| Modem    | 2         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 121       | 80.13%  |
| Ethernet | 30        | 19.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 100       | 70.92%  |
| 1     | 39        | 27.66%  |
| 0     | 2         | 1.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 65.25%  |
| Yes  | 49        | 34.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 49.59%  |
| Realtek Semiconductor           | 18        | 14.63%  |
| Broadcom                        | 13        | 10.57%  |
| Qualcomm Atheros Communications | 6         | 4.88%   |
| IMC Networks                    | 6         | 4.88%   |
| Apple                           | 4         | 3.25%   |
| Ralink                          | 3         | 2.44%   |
| Lite-On Technology              | 3         | 2.44%   |
| Foxconn / Hon Hai               | 3         | 2.44%   |
| Cambridge Silicon Radio         | 3         | 2.44%   |
| Toshiba                         | 1         | 0.81%   |
| Hewlett-Packard                 | 1         | 0.81%   |
| Foxconn International           | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 15.45%  |
| Intel AX201 Bluetooth                                                               | 18        | 14.63%  |
| Realtek Bluetooth Radio                                                             | 16        | 13.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 6.5%    |
| Intel AX200 Bluetooth                                                               | 8         | 6.5%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 3.25%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.44%   |
| Intel AX210 Bluetooth                                                               | 3         | 2.44%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.44%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.44%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.63%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.63%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.63%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.63%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 1.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.63%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.63%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.63%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.81%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.81%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.81%   |
| Broadcom Bluetooth 3.0 Dongle                                                       | 1         | 0.81%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.81%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 107       | 60.11%  |
| AMD                    | 34        | 19.1%   |
| Nvidia                 | 27        | 15.17%  |
| C-Media Electronics    | 2         | 1.12%   |
| Realtek Semiconductor  | 1         | 0.56%   |
| Plantronics            | 1         | 0.56%   |
| Meizu                  | 1         | 0.56%   |
| Lenovo                 | 1         | 0.56%   |
| GN Netcom              | 1         | 0.56%   |
| Generalplus Technology | 1         | 0.56%   |
| DSEA A/S               | 1         | 0.56%   |
| ASUSTek Computer       | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 8.84%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 5.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 4.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 4.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 3.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 3.72%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 3.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 2.33%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 2.33%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.33%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.33%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.4%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.4%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.4%    |
| AMD High Definition Audio Controller                                                              | 3         | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.4%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.93%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.93%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.93%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 27.42%  |
| SK hynix            | 29        | 23.39%  |
| Micron Technology   | 19        | 15.32%  |
| Unknown             | 12        | 9.68%   |
| Kingston            | 10        | 8.06%   |
| Unknown (ABCD)      | 6         | 4.84%   |
| Crucial             | 5         | 4.03%   |
| Ramaxel Technology  | 3         | 2.42%   |
| Nanya Technology    | 3         | 2.42%   |
| G.Skill             | 2         | 1.61%   |
| Corsair             | 1         | 0.81%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 3.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.92%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 2.19%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.19%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.19%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 1.46%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 1.46%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 1.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 1.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.46%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.46%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.46%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 1.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.73%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.73%   |
| Unknown RAM Module 2GB SODIMM 1067MT/s                           | 1         | 0.73%   |
| Unknown RAM Module 1GB DIMM DDR3 1600MT/s                        | 1         | 0.73%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 1         | 0.73%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2400MT/s                    | 1         | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.73%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 800MT/s            | 1         | 0.73%   |
| SK hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1333MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6BFR8C-G7 4GB SODIMM DDR3 1067MT/s           | 1         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 50        | 45.05%  |
| DDR3    | 36        | 32.43%  |
| LPDDR4  | 9         | 8.11%   |
| DDR2    | 7         | 6.31%   |
| SDRAM   | 4         | 3.6%    |
| LPDDR3  | 2         | 1.8%    |
| DDR5    | 2         | 1.8%    |
| Unknown | 1         | 0.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 85.71%  |
| Row Of Chips | 12        | 10.71%  |
| Unknown      | 2         | 1.79%   |
| DIMM         | 1         | 0.89%   |
| Chip         | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 45        | 36.59%  |
| 4096  | 34        | 27.64%  |
| 16384 | 20        | 16.26%  |
| 2048  | 17        | 13.82%  |
| 1024  | 5         | 4.07%   |
| 32768 | 2         | 1.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 32        | 26.89%  |
| 1600    | 25        | 21.01%  |
| 2400    | 14        | 11.76%  |
| 2667    | 11        | 9.24%   |
| 1334    | 5         | 4.2%    |
| Unknown | 5         | 4.2%    |
| 2133    | 4         | 3.36%   |
| 2048    | 3         | 2.52%   |
| 1067    | 3         | 2.52%   |
| 667     | 3         | 2.52%   |
| 4267    | 2         | 1.68%   |
| 1867    | 2         | 1.68%   |
| 1333    | 2         | 1.68%   |
| 1066    | 2         | 1.68%   |
| 5600    | 1         | 0.84%   |
| 4800    | 1         | 0.84%   |
| 4199    | 1         | 0.84%   |
| 2933    | 1         | 0.84%   |
| 975     | 1         | 0.84%   |
| 800     | 1         | 0.84%   |

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
| Chicony Electronics                    | 36        | 26.67%  |
| Realtek Semiconductor                  | 18        | 13.33%  |
| IMC Networks                           | 12        | 8.89%   |
| Quanta                                 | 10        | 7.41%   |
| Microdia                               | 8         | 5.93%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.19%   |
| Syntek                                 | 6         | 4.44%   |
| Suyin                                  | 5         | 3.7%    |
| Sunplus Innovation Technology          | 5         | 3.7%    |
| Acer                                   | 4         | 2.96%   |
| Luxvisions Innotech Limited            | 3         | 2.22%   |
| Apple                                  | 3         | 2.22%   |
| Silicon Motion                         | 2         | 1.48%   |
| Ricoh                                  | 2         | 1.48%   |
| Lite-On Technology                     | 2         | 1.48%   |
| Lenovo                                 | 2         | 1.48%   |
| Bison Electronics                      | 2         | 1.48%   |
| Alcor Micro                            | 2         | 1.48%   |
| SunplusIT                              | 1         | 0.74%   |
| Sonix Technology                       | 1         | 0.74%   |
| Razer USA                              | 1         | 0.74%   |
| Logitech                               | 1         | 0.74%   |
| Denron                                 | 1         | 0.74%   |
| ARC International                      | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                  | 6         | 4.44%   |
| Chicony HP HD Camera                          | 6         | 4.44%   |
| Syntek Integrated Camera                      | 5         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 3.7%    |
| Chicony Integrated Camera                     | 5         | 3.7%    |
| IMC Networks Integrated Camera                | 4         | 2.96%   |
| Realtek USB Camera                            | 3         | 2.22%   |
| Chicony HP Webcam                             | 3         | 2.22%   |
| Chicony HP Truevision HD camera               | 3         | 2.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.22%   |
| Acer Integrated Camera                        | 3         | 2.22%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 2         | 1.48%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.48%   |
| Sunplus Integrated_Webcam_FHD                 | 2         | 1.48%   |
| Realtek USB2.0 camera                         | 2         | 1.48%   |
| Realtek Acer 640 x 480 laptop camera          | 2         | 1.48%   |
| Quanta ov9734_techfront_camera                | 2         | 1.48%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.48%   |
| Quanta HD User Facing                         | 2         | 1.48%   |
| Microdia Webcam Vitade AF                     | 2         | 1.48%   |
| Microdia Integrated Webcam                    | 2         | 1.48%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.48%   |
| Lenovo CNF7237&CNF7238                        | 2         | 1.48%   |
| Chicony USB2.0 Camera                         | 2         | 1.48%   |
| Chicony Integrated IR Camera                  | 2         | 1.48%   |
| Chicony HD User Facing                        | 2         | 1.48%   |
| Chicony EasyCamera                            | 2         | 1.48%   |
| Apple Built-in iSight                         | 2         | 1.48%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.74%   |
| Suyin USB 2.0 Camera                          | 1         | 0.74%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.74%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.74%   |
| SunplusIT PC Camera                           | 1         | 0.74%   |
| Sunplus HP Truevision HD                      | 1         | 0.74%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 0.74%   |
| Silicon Motion WebCam SC-10HDD13335N          | 1         | 0.74%   |
| Silicon Motion HP Webcam-101                  | 1         | 0.74%   |
| Ricoh Sony Vaio Integrated Webcam             | 1         | 0.74%   |
| Ricoh Dell Laptop Integrated Webcam           | 1         | 0.74%   |
| Realtek Streamplify CAM                       | 1         | 0.74%   |

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
| Broadcom              | 11        | 57.89%  |
| Alcor Micro           | 4         | 21.05%  |
| Upek                  | 1         | 5.26%   |
| SCM Microsystems      | 1         | 5.26%   |
| O2 Micro              | 1         | 5.26%   |
| Advanced Card Systems | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 5         | 26.32%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 21.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15.79%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.26%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 83        | 58.45%  |
| 1     | 42        | 29.58%  |
| 2     | 14        | 9.86%   |
| 3     | 2         | 1.41%   |
| 4     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 26        | 34.67%  |
| Chipcard              | 19        | 25.33%  |
| Graphics card         | 11        | 14.67%  |
| Bluetooth             | 6         | 8%      |
| Net/wireless          | 4         | 5.33%   |
| Camera                | 4         | 5.33%   |
| Storage               | 1         | 1.33%   |
| Multimedia controller | 1         | 1.33%   |
| Flash memory          | 1         | 1.33%   |
| Dvb card              | 1         | 1.33%   |
| Card reader           | 1         | 1.33%   |

