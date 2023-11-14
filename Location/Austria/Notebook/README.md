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

Total: 1563

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | ProBook 430 G1              | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [30a0e0602f](https://linux-hardware.org/?probe=30a0e0602f) | Nov 04, 2023 |
| ASUSTek       | K53SD                       | [e26ed8b740](https://linux-hardware.org/?probe=e26ed8b740) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S710               | [b0ee1e5f32](https://linux-hardware.org/?probe=b0ee1e5f32) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S710               | [a8ae4206d4](https://linux-hardware.org/?probe=a8ae4206d4) | Oct 31, 2023 |
| MSI           | Modern 15 A11M              | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| HP            | 250 G7 Notebook PC          | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| Acer          | Aspire E1-572G              | [ebfb310a2d](https://linux-hardware.org/?probe=ebfb310a2d) | Oct 23, 2023 |
| Razer         | Blade 17 (Mid 2021) - RZ... | [c096ac6500](https://linux-hardware.org/?probe=c096ac6500) | Oct 22, 2023 |
| HP            | Pavilion dv7                | [d2beead33c](https://linux-hardware.org/?probe=d2beead33c) | Oct 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [686e5c87a9](https://linux-hardware.org/?probe=686e5c87a9) | Oct 18, 2023 |
| MSI           | Prestige 14H B12UCX         | [17314417bf](https://linux-hardware.org/?probe=17314417bf) | Oct 17, 2023 |
| Unknown       | Unknown                     | [f776cdb186](https://linux-hardware.org/?probe=f776cdb186) | Oct 17, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [67ad226870](https://linux-hardware.org/?probe=67ad226870) | Oct 17, 2023 |
| Lenovo        | ThinkPad E550 20DF00F0GE    | [61c5a7e37a](https://linux-hardware.org/?probe=61c5a7e37a) | Oct 13, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | [5298e96c35](https://linux-hardware.org/?probe=5298e96c35) | Oct 13, 2023 |
| Packard Be... | EasyNote ENTG81BA           | [f25cb1517e](https://linux-hardware.org/?probe=f25cb1517e) | Oct 12, 2023 |
| AMI           | Intel                       | [e60ced0b11](https://linux-hardware.org/?probe=e60ced0b11) | Oct 12, 2023 |
| AMI           | Intel                       | [4b7c1bc00c](https://linux-hardware.org/?probe=4b7c1bc00c) | Oct 12, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [7108bb9955](https://linux-hardware.org/?probe=7108bb9955) | Oct 10, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [7e264895bf](https://linux-hardware.org/?probe=7e264895bf) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [f91905858e](https://linux-hardware.org/?probe=f91905858e) | Oct 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRC... | [a5e4eeba7f](https://linux-hardware.org/?probe=a5e4eeba7f) | Oct 10, 2023 |
| HP            | Notebook                    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| HP            | Notebook                    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | XPS 13 9370                 | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [3a5617ed7c](https://linux-hardware.org/?probe=3a5617ed7c) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [fb307526fa](https://linux-hardware.org/?probe=fb307526fa) | Oct 01, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [411e8279da](https://linux-hardware.org/?probe=411e8279da) | Oct 01, 2023 |
| Acer          | Aspire F5-573G              | [dea46b2302](https://linux-hardware.org/?probe=dea46b2302) | Sep 29, 2023 |
| HP            | EliteBook 850 G1            | [35f0e18f04](https://linux-hardware.org/?probe=35f0e18f04) | Sep 28, 2023 |
| Toshiba       | Satellite L550              | [d93c40647f](https://linux-hardware.org/?probe=d93c40647f) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| Acer          | Aspire A515-56              | [b047457fd1](https://linux-hardware.org/?probe=b047457fd1) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [0b8e5fc8d0](https://linux-hardware.org/?probe=0b8e5fc8d0) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0CN0... | [9c0b702e21](https://linux-hardware.org/?probe=9c0b702e21) | Sep 24, 2023 |
| HP            | 350 G2                      | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| Schenker      | VISION 15 E23 (SVS15E23)    | [d905d3589d](https://linux-hardware.org/?probe=d905d3589d) | Sep 24, 2023 |
| Sony          | VPCEH2J1E                   | [2a09805fe9](https://linux-hardware.org/?probe=2a09805fe9) | Sep 24, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [a616b7f5d0](https://linux-hardware.org/?probe=a616b7f5d0) | Sep 23, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [ddac5bba05](https://linux-hardware.org/?probe=ddac5bba05) | Sep 23, 2023 |
| Dell          | Latitude E7270              | [874b8a2ad5](https://linux-hardware.org/?probe=874b8a2ad5) | Sep 23, 2023 |
| HP            | EliteBook 840 G6            | [10cd0244af](https://linux-hardware.org/?probe=10cd0244af) | Sep 23, 2023 |
| HP            | ProBook 4515s               | [0b755bf978](https://linux-hardware.org/?probe=0b755bf978) | Sep 22, 2023 |
| Acer          | Aspire A114-31              | [968cd24afa](https://linux-hardware.org/?probe=968cd24afa) | Sep 22, 2023 |
| AMI           | Intel                       | [687044ba01](https://linux-hardware.org/?probe=687044ba01) | Sep 21, 2023 |
| Toshiba       | Satellite L550              | [f55adbf4eb](https://linux-hardware.org/?probe=f55adbf4eb) | Sep 20, 2023 |
| Acer          | Aspire E1-572G              | [139fc573bf](https://linux-hardware.org/?probe=139fc573bf) | Sep 19, 2023 |
| Apple         | MacBook3,1                  | [faa5140c74](https://linux-hardware.org/?probe=faa5140c74) | Sep 18, 2023 |
| Acer          | Aspire E1-572G              | [0578825483](https://linux-hardware.org/?probe=0578825483) | Sep 18, 2023 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [b9f92fec9c](https://linux-hardware.org/?probe=b9f92fec9c) | Sep 17, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [0379270fb2](https://linux-hardware.org/?probe=0379270fb2) | Sep 15, 2023 |
| Valve         | Jupiter                     | [5f155701b1](https://linux-hardware.org/?probe=5f155701b1) | Sep 13, 2023 |
| Valve         | Jupiter                     | [3ae7c4440b](https://linux-hardware.org/?probe=3ae7c4440b) | Sep 10, 2023 |
| Valve         | Jupiter                     | [bbbc40365d](https://linux-hardware.org/?probe=bbbc40365d) | Sep 10, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [780a68ac11](https://linux-hardware.org/?probe=780a68ac11) | Sep 09, 2023 |
| HP            | Pavilion dv7                | [a928ff5a33](https://linux-hardware.org/?probe=a928ff5a33) | Sep 09, 2023 |
| HP            | EliteBook 8740w             | [e34200af0f](https://linux-hardware.org/?probe=e34200af0f) | Sep 08, 2023 |
| Inter Sale... | NID-11125DE                 | [2c94bcc096](https://linux-hardware.org/?probe=2c94bcc096) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [4764776393](https://linux-hardware.org/?probe=4764776393) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | [75ad357b16](https://linux-hardware.org/?probe=75ad357b16) | Sep 01, 2023 |
| Sony          | VPCEH2J1E                   | [0d1017e65a](https://linux-hardware.org/?probe=0d1017e65a) | Aug 31, 2023 |
| ASUSTek       | X555LAB                     | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | [05b083817c](https://linux-hardware.org/?probe=05b083817c) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | [f6f76a2e9d](https://linux-hardware.org/?probe=f6f76a2e9d) | Aug 30, 2023 |
| Acer          | Aspire A114-31              | [6bf92318e7](https://linux-hardware.org/?probe=6bf92318e7) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | [0e3563cf3e](https://linux-hardware.org/?probe=0e3563cf3e) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | [1025de1dcf](https://linux-hardware.org/?probe=1025de1dcf) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| Chuwi         | LapBook SE                  | [8c338913ab](https://linux-hardware.org/?probe=8c338913ab) | Aug 19, 2023 |
| Acer          | Predator PH317-52           | [c942508cf0](https://linux-hardware.org/?probe=c942508cf0) | Aug 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| Chuwi         | HeroBook Pro                | [0122fef8fd](https://linux-hardware.org/?probe=0122fef8fd) | Aug 15, 2023 |
| Dell          | Latitude 5290 2-in-1        | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| HP            | 350 G2                      | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| HP            | EliteBook 8740w             | [69a5fc6981](https://linux-hardware.org/?probe=69a5fc6981) | Aug 10, 2023 |
| Toshiba       | Satellite C70D-B            | [ac775a3228](https://linux-hardware.org/?probe=ac775a3228) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | [e3f3b2fcfb](https://linux-hardware.org/?probe=e3f3b2fcfb) | Aug 09, 2023 |
| Dell          | Latitude 5540               | [08c875f58b](https://linux-hardware.org/?probe=08c875f58b) | Aug 08, 2023 |
| Dell          | XPS 13 9310                 | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| HP            | EliteBook 8740w             | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| Dell          | Latitude E6400              | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| HP            | EliteBook 8740w             | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| Dell          | Latitude E6400              | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad T470 20HES2C000    | [6cb5b31808](https://linux-hardware.org/?probe=6cb5b31808) | Jul 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [68d5cb02bf](https://linux-hardware.org/?probe=68d5cb02bf) | Jul 29, 2023 |
| Dell          | Inspiron 5720               | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Valve         | Jupiter                     | [db220d13d6](https://linux-hardware.org/?probe=db220d13d6) | Jul 20, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [01b8ada2a7](https://linux-hardware.org/?probe=01b8ada2a7) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [3ad7db3176](https://linux-hardware.org/?probe=3ad7db3176) | Jul 10, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [919d1fc65b](https://linux-hardware.org/?probe=919d1fc65b) | Jul 09, 2023 |
| ASUSTek       | G60VX                       | [3273a8de27](https://linux-hardware.org/?probe=3273a8de27) | Jul 09, 2023 |
| Acer          | TravelMate P215-53          | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| HP            | ZBook 17 G3                 | [e328019dd8](https://linux-hardware.org/?probe=e328019dd8) | Jul 07, 2023 |
| Medion        | Unknown                     | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [bbce89859f](https://linux-hardware.org/?probe=bbce89859f) | Jul 06, 2023 |
| HP            | ProBook 4740s               | [c920d177db](https://linux-hardware.org/?probe=c920d177db) | Jul 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [5f2c613312](https://linux-hardware.org/?probe=5f2c613312) | Jul 03, 2023 |
| Valve         | Jupiter                     | [cd28af9419](https://linux-hardware.org/?probe=cd28af9419) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | Aspire VN7-593G             | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [eeb516967a](https://linux-hardware.org/?probe=eeb516967a) | Jun 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a2a87af2a4](https://linux-hardware.org/?probe=a2a87af2a4) | Jun 26, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Acer          | Aspire A114-31              | [3cb015a09d](https://linux-hardware.org/?probe=3cb015a09d) | Jun 23, 2023 |
| ASUSTek       | K56CB                       | [e00f1f735d](https://linux-hardware.org/?probe=e00f1f735d) | Jun 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [9fa828d2e4](https://linux-hardware.org/?probe=9fa828d2e4) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Valve         | Jupiter                     | [576a62665a](https://linux-hardware.org/?probe=576a62665a) | Jun 20, 2023 |
| MSI           | Bravo 17 A4DDR              | [bae46c4d0b](https://linux-hardware.org/?probe=bae46c4d0b) | Jun 19, 2023 |
| Apple         | MacBookPro8,2               | [d254709437](https://linux-hardware.org/?probe=d254709437) | Jun 15, 2023 |
| HP            | Notebook                    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Acer          | TravelMate 5742Z            | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [93fe499e47](https://linux-hardware.org/?probe=93fe499e47) | Jun 12, 2023 |
| Lenovo        | ThinkPad W541 20EGS15J0N    | [ba935e9d5c](https://linux-hardware.org/?probe=ba935e9d5c) | Jun 12, 2023 |
| HP            | ProBook 440 G4              | [411faeafd4](https://linux-hardware.org/?probe=411faeafd4) | Jun 11, 2023 |
| HUAWEI        | HVY-WXX9                    | [d6be89e452](https://linux-hardware.org/?probe=d6be89e452) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Acer          | Aspire 7741                 | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| Valve         | Jupiter                     | [7e07a9c15d](https://linux-hardware.org/?probe=7e07a9c15d) | Jun 07, 2023 |
| Dell          | Latitude E7250              | [a80182e728](https://linux-hardware.org/?probe=a80182e728) | Jun 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [5b7617b9c0](https://linux-hardware.org/?probe=5b7617b9c0) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Dell          | Latitude E7450              | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| Apple         | MacBookAir7,2               | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HP            | Compaq Presario CQ60        | [2378902ae8](https://linux-hardware.org/?probe=2378902ae8) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2cacb34a0d](https://linux-hardware.org/?probe=2cacb34a0d) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| Valve         | Jupiter                     | [f2f00bcfcc](https://linux-hardware.org/?probe=f2f00bcfcc) | May 29, 2023 |
| Valve         | Jupiter                     | [242a13f378](https://linux-hardware.org/?probe=242a13f378) | May 27, 2023 |
| HP            | ZBook 17 G6                 | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| Acer          | Aspire V3-772               | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [44bc1d8d62](https://linux-hardware.org/?probe=44bc1d8d62) | May 17, 2023 |
| HP            | ProBook 6570b               | [7d8b9d4be1](https://linux-hardware.org/?probe=7d8b9d4be1) | May 16, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [996d19a70c](https://linux-hardware.org/?probe=996d19a70c) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [3bd39e50a8](https://linux-hardware.org/?probe=3bd39e50a8) | May 15, 2023 |
| Valve         | Jupiter                     | [a130b1b1d0](https://linux-hardware.org/?probe=a130b1b1d0) | May 14, 2023 |
| MSI           | GF65 Thin 10UE              | [7d8bb12818](https://linux-hardware.org/?probe=7d8bb12818) | May 14, 2023 |
| HP            | ProBook 640 G1              | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Sony          | VPCEH2J1E                   | [fb307bc1bb](https://linux-hardware.org/?probe=fb307bc1bb) | May 11, 2023 |
| TUXEDO        | Book XP1511                 | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Dell          | Latitude 5310               | [d72db172f0](https://linux-hardware.org/?probe=d72db172f0) | May 07, 2023 |
| Toshiba       | TECRA A11                   | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Acer          | Aspire 7741                 | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Acer          | Aspire A114-31              | [a7e0c2d3b6](https://linux-hardware.org/?probe=a7e0c2d3b6) | May 05, 2023 |
| Toshiba       | Satellite U300              | [470632e542](https://linux-hardware.org/?probe=470632e542) | May 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [65ddedbd24](https://linux-hardware.org/?probe=65ddedbd24) | May 05, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| Sony          | VPCEH2J1E                   | [c9b6063699](https://linux-hardware.org/?probe=c9b6063699) | May 04, 2023 |
| Fujitsu       | LIFEBOOK E752               | [22f50229d9](https://linux-hardware.org/?probe=22f50229d9) | May 03, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [e3984b7285](https://linux-hardware.org/?probe=e3984b7285) | May 01, 2023 |
| Medion        | E16402                      | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| Dell          | Latitude D630               | [0fecf73eea](https://linux-hardware.org/?probe=0fecf73eea) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [57261fe5ec](https://linux-hardware.org/?probe=57261fe5ec) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Valve         | Jupiter                     | [0d6278dd3a](https://linux-hardware.org/?probe=0d6278dd3a) | Apr 22, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [a7359e872e](https://linux-hardware.org/?probe=a7359e872e) | Apr 22, 2023 |
| Valve         | Jupiter                     | [d315f00cd8](https://linux-hardware.org/?probe=d315f00cd8) | Apr 21, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3219512811](https://linux-hardware.org/?probe=3219512811) | Apr 20, 2023 |
| Medion        | P17605                      | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| Acer          | AS5755                      | [1c163eb17f](https://linux-hardware.org/?probe=1c163eb17f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Acer          | Aspire E5-575               | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| HUAWEI        | RLEF-XX                     | [b425e2afaf](https://linux-hardware.org/?probe=b425e2afaf) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | [19bb54bd98](https://linux-hardware.org/?probe=19bb54bd98) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| Medion        | E7220                       | [ab189f426b](https://linux-hardware.org/?probe=ab189f426b) | Apr 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | [e9fa009df9](https://linux-hardware.org/?probe=e9fa009df9) | Apr 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [0ca203f8b0](https://linux-hardware.org/?probe=0ca203f8b0) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | [8e769590fb](https://linux-hardware.org/?probe=8e769590fb) | Apr 05, 2023 |
| Valve         | Jupiter                     | [a3c3e3267a](https://linux-hardware.org/?probe=a3c3e3267a) | Apr 02, 2023 |
| Valve         | Jupiter                     | [774af9fced](https://linux-hardware.org/?probe=774af9fced) | Apr 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [68dade8d0a](https://linux-hardware.org/?probe=68dade8d0a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| HP            | EliteBook 2530p (KR059AV... | [e7f9bce466](https://linux-hardware.org/?probe=e7f9bce466) | Mar 31, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [225e13e1f0](https://linux-hardware.org/?probe=225e13e1f0) | Mar 30, 2023 |
| HP            | Pavilion 17                 | [46e0a0aed1](https://linux-hardware.org/?probe=46e0a0aed1) | Mar 30, 2023 |
| HP            | Pavilion 17                 | [3da4500905](https://linux-hardware.org/?probe=3da4500905) | Mar 30, 2023 |
| HP            | ProBook 640 G1              | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Samsung       | RC530/RC730                 | [ad2be3eba7](https://linux-hardware.org/?probe=ad2be3eba7) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [64485e9b53](https://linux-hardware.org/?probe=64485e9b53) | Mar 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Hampoo        | Cherry Trail CR             | [b293f3ba3e](https://linux-hardware.org/?probe=b293f3ba3e) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | [f4830d41d6](https://linux-hardware.org/?probe=f4830d41d6) | Mar 21, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [42629ad13b](https://linux-hardware.org/?probe=42629ad13b) | Mar 21, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | [aef19ecbd7](https://linux-hardware.org/?probe=aef19ecbd7) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | [82d9122ebf](https://linux-hardware.org/?probe=82d9122ebf) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Valve         | Jupiter                     | [192fe75be4](https://linux-hardware.org/?probe=192fe75be4) | Mar 19, 2023 |
| Dell          | Vostro 5471                 | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| Hampoo        | Cherry Trail CR             | [fcb7a079cf](https://linux-hardware.org/?probe=fcb7a079cf) | Mar 18, 2023 |
| HP            | EliteBook 1050 G1           | [6dcfa134ac](https://linux-hardware.org/?probe=6dcfa134ac) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Valve         | Jupiter                     | [36eacafa6f](https://linux-hardware.org/?probe=36eacafa6f) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| Hampoo        | Cherry Trail CR             | [c9936da6ba](https://linux-hardware.org/?probe=c9936da6ba) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| HP            | ProBook 450 G6              | [44c6479881](https://linux-hardware.org/?probe=44c6479881) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Clevo         | P370EM                      | [4ac46a0dab](https://linux-hardware.org/?probe=4ac46a0dab) | Mar 07, 2023 |
| HP            | ProBook 450 G6              | [b27b730e8f](https://linux-hardware.org/?probe=b27b730e8f) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Apple         | MacBookAir4,2               | [a9605bf85e](https://linux-hardware.org/?probe=a9605bf85e) | Feb 27, 2023 |
| Dell          | Latitude E7250              | [db6ac786ef](https://linux-hardware.org/?probe=db6ac786ef) | Feb 26, 2023 |
| Valve         | Jupiter                     | [c8006c3bd5](https://linux-hardware.org/?probe=c8006c3bd5) | Feb 26, 2023 |
| Toshiba       | Satellite C70D-B            | [0c69e8ef9b](https://linux-hardware.org/?probe=0c69e8ef9b) | Feb 23, 2023 |
| Toshiba       | Satellite C70D-B            | [bcae8ff254](https://linux-hardware.org/?probe=bcae8ff254) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | [49007433d0](https://linux-hardware.org/?probe=49007433d0) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | [e67cca4a6c](https://linux-hardware.org/?probe=e67cca4a6c) | Feb 23, 2023 |
| Unknown       | Unknown                     | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| Chuwi         | HeroBook Pro                | [f49ba07c1e](https://linux-hardware.org/?probe=f49ba07c1e) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Gigabyte      | GB-BSi7A-6500               | [9c461d33db](https://linux-hardware.org/?probe=9c461d33db) | Feb 16, 2023 |
| Medion        | E7220                       | [dd9de8bf69](https://linux-hardware.org/?probe=dd9de8bf69) | Feb 15, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3S... | [580215c6bb](https://linux-hardware.org/?probe=580215c6bb) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [ca4349a929](https://linux-hardware.org/?probe=ca4349a929) | Feb 15, 2023 |
| Apple         | MacBook5,2                  | [72b8d495ff](https://linux-hardware.org/?probe=72b8d495ff) | Feb 13, 2023 |
| Acer          | Aspire 7740                 | [caeb61e835](https://linux-hardware.org/?probe=caeb61e835) | Feb 12, 2023 |
| Apple         | MacBookPro11,5              | [78e7a0ae85](https://linux-hardware.org/?probe=78e7a0ae85) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| Apple         | MacBookPro5,4               | [b7e924b0cd](https://linux-hardware.org/?probe=b7e924b0cd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T450 20BUS1110E    | [d08c46c46d](https://linux-hardware.org/?probe=d08c46c46d) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| MSI           | GF63 Thin 11UC              | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Apple         | MacBookPro11,5              | [3407774ba7](https://linux-hardware.org/?probe=3407774ba7) | Feb 05, 2023 |
| Dell          | MXG061                      | [40883298a9](https://linux-hardware.org/?probe=40883298a9) | Feb 04, 2023 |
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Acer          | Aspire A515-54G             | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude 5480               | [8b43efc7ea](https://linux-hardware.org/?probe=8b43efc7ea) | Jan 31, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Dell          | XPS 15 7590                 | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| TUXEDO        | Unknown                     | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Toshiba       | Satellite Pro C660          | [f1c0237cc0](https://linux-hardware.org/?probe=f1c0237cc0) | Jan 22, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| MSI           | VR630                       | [943c1d68fa](https://linux-hardware.org/?probe=943c1d68fa) | Jan 19, 2023 |
| ASUSTek       | K53TA                       | [a56a3691e9](https://linux-hardware.org/?probe=a56a3691e9) | Jan 18, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [b68853abf6](https://linux-hardware.org/?probe=b68853abf6) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [80f9124e5a](https://linux-hardware.org/?probe=80f9124e5a) | Jan 14, 2023 |
| TUXEDO        | Unknown                     | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Latitude E5550              | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Medion        | E6222                       | [e3b3da28fa](https://linux-hardware.org/?probe=e3b3da28fa) | Jan 11, 2023 |
| Dell          | Latitude E5550              | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| Dell          | Latitude E7440              | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| Dell          | XPS 13 9380                 | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| MSI           | GS63VR 7RF                  | [95aadb3cc4](https://linux-hardware.org/?probe=95aadb3cc4) | Jan 09, 2023 |
| Sony          | SVE1512H1EB                 | [723e8bfbe6](https://linux-hardware.org/?probe=723e8bfbe6) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | [297380c89a](https://linux-hardware.org/?probe=297380c89a) | Jan 09, 2023 |
| Acer          | Iconia W700                 | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| Google        | Kled                        | [3cb98a4497](https://linux-hardware.org/?probe=3cb98a4497) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Sony          | VPCEH2D0E                   | [78367f11f5](https://linux-hardware.org/?probe=78367f11f5) | Jan 04, 2023 |
| ASUSTek       | K93SM                       | [c0fb78e9a3](https://linux-hardware.org/?probe=c0fb78e9a3) | Jan 03, 2023 |
| Dell          | Latitude 7430               | [ad796336f7](https://linux-hardware.org/?probe=ad796336f7) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Chuwi         | HeroBook Pro                | [cdc31b8338](https://linux-hardware.org/?probe=cdc31b8338) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c28fb2edb2](https://linux-hardware.org/?probe=c28fb2edb2) | Dec 30, 2022 |
| Medion        | X782X/X783X                 | [a8befc040f](https://linux-hardware.org/?probe=a8befc040f) | Dec 26, 2022 |
| Notebook      | P64_HJ,HK1                  | [26a548a6f3](https://linux-hardware.org/?probe=26a548a6f3) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [431eac7d11](https://linux-hardware.org/?probe=431eac7d11) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire A715-72G             | [8e15fef839](https://linux-hardware.org/?probe=8e15fef839) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| Google        | Cyan                        | [fff3502929](https://linux-hardware.org/?probe=fff3502929) | Dec 19, 2022 |
| Acer          | Nitro AN515-42              | [88d7491a00](https://linux-hardware.org/?probe=88d7491a00) | Dec 19, 2022 |
| AXDIA Inte... | myBook PRO14 SE V2          | [14b79d7a8b](https://linux-hardware.org/?probe=14b79d7a8b) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| HP            | EliteBook 850 G2            | [d0d30cd96f](https://linux-hardware.org/?probe=d0d30cd96f) | Dec 14, 2022 |
| Acer          | Swift SF314-59              | [943bcd1d12](https://linux-hardware.org/?probe=943bcd1d12) | Dec 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [b518609312](https://linux-hardware.org/?probe=b518609312) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [f815a2e4a3](https://linux-hardware.org/?probe=f815a2e4a3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| HUAWEI        | RLEF-XX                     | [e0b1d50b7c](https://linux-hardware.org/?probe=e0b1d50b7c) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [50e5b72a10](https://linux-hardware.org/?probe=50e5b72a10) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [b7171256c0](https://linux-hardware.org/?probe=b7171256c0) | Dec 07, 2022 |
| Packard Be... | EasyNote TS11HR             | [cd166beede](https://linux-hardware.org/?probe=cd166beede) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Acer          | Aspire A514-53              | [f0c20f1a0a](https://linux-hardware.org/?probe=f0c20f1a0a) | Dec 04, 2022 |
| ASUSTek       | X580VD                      | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| Apple         | MacBookPro14,1              | [eb13a8db03](https://linux-hardware.org/?probe=eb13a8db03) | Dec 02, 2022 |
| Acer          | Aspire A514-53              | [07ff06f360](https://linux-hardware.org/?probe=07ff06f360) | Dec 02, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| W271ELQ       | Unknown                     | [ae170d1e81](https://linux-hardware.org/?probe=ae170d1e81) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| Dell          | Latitude 3520               | [896180c55d](https://linux-hardware.org/?probe=896180c55d) | Nov 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [6646978243](https://linux-hardware.org/?probe=6646978243) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [ddcb37ea55](https://linux-hardware.org/?probe=ddcb37ea55) | Nov 23, 2022 |
| Dell          | Precision 5560              | [f20218fb35](https://linux-hardware.org/?probe=f20218fb35) | Nov 23, 2022 |
| TUXEDO        | N7x0WU                      | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [dc848e747b](https://linux-hardware.org/?probe=dc848e747b) | Nov 21, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [4ea8f7dbb0](https://linux-hardware.org/?probe=4ea8f7dbb0) | Nov 19, 2022 |
| Valve         | Jupiter                     | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Latitude E6220              | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| HP            | EliteBook 850 G1            | [a83e2b1a92](https://linux-hardware.org/?probe=a83e2b1a92) | Nov 13, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [4406929fb6](https://linux-hardware.org/?probe=4406929fb6) | Nov 11, 2022 |
| Apple         | MacBookPro9,2               | [695b0b0356](https://linux-hardware.org/?probe=695b0b0356) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| ASUSTek       | X55A                        | [6391006e3d](https://linux-hardware.org/?probe=6391006e3d) | Nov 07, 2022 |
| ASUSTek       | X55A                        | [ae4277aa87](https://linux-hardware.org/?probe=ae4277aa87) | Nov 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
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
| Ubuntu 20.04                 | 150       | 13.39%  |
| Ubuntu 18.04                 | 60        | 5.36%   |
| Ubuntu 22.04                 | 58        | 5.18%   |
| Linux Mint 20.2              | 29        | 2.59%   |
| Arch Rolling                 | 29        | 2.59%   |
| Zorin 16                     | 27        | 2.41%   |
| OpenMandriva 4.3             | 24        | 2.14%   |
| Debian 11                    | 24        | 2.14%   |
| Arch                         | 23        | 2.05%   |
| BlackPanther 18.1            | 22        | 1.96%   |
| Fedora 37                    | 19        | 1.7%    |
| Fedora 35                    | 19        | 1.7%    |
| Manjaro                      | 18        | 1.61%   |
| Linux Mint 20.1              | 17        | 1.52%   |
| Ubuntu 21.04                 | 16        | 1.43%   |
| Linux Mint 21.1              | 16        | 1.43%   |
| Fedora 38                    | 16        | 1.43%   |
| Fedora 33                    | 15        | 1.34%   |
| Linux Mint 19.3              | 14        | 1.25%   |
| KDE neon 20.04               | 14        | 1.25%   |
| Ubuntu 19.10                 | 13        | 1.16%   |
| Debian 12                    | 13        | 1.16%   |
| Ubuntu 22.10                 | 12        | 1.07%   |
| Ubuntu 21.10                 | 12        | 1.07%   |
| Fedora 36                    | 12        | 1.07%   |
| Fedora 32                    | 12        | 1.07%   |
| Pop!_OS 22.04                | 11        | 0.98%   |
| OpenMandriva 4.2             | 11        | 0.98%   |
| Linux Mint 20.3              | 11        | 0.98%   |
| Fedora 34                    | 11        | 0.98%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.89%   |
| Linux Mint 21                | 10        | 0.89%   |
| Linux Mint 20                | 10        | 0.89%   |
| EndeavourOS Rolling          | 10        | 0.89%   |
| Zorin 15                     | 9         | 0.8%    |
| Pop!_OS 21.04                | 9         | 0.8%    |
| Linux Mint 21.2              | 9         | 0.8%    |
| Ubuntu 23.04                 | 8         | 0.71%   |
| Ubuntu 20.10                 | 8         | 0.71%   |
| Pop!_OS 20.04                | 8         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 342       | 32.42%  |
| Linux Mint    | 113       | 10.71%  |
| Fedora        | 95        | 9%      |
| OpenMandriva  | 56        | 5.31%   |
| Manjaro       | 53        | 5.02%   |
| Debian        | 50        | 4.74%   |
| Arch          | 49        | 4.64%   |
| Zorin         | 36        | 3.41%   |
| Pop!_OS       | 35        | 3.32%   |
| BlackPanther  | 24        | 2.27%   |
| KDE neon      | 21        | 1.99%   |
| openSUSE      | 18        | 1.71%   |
| Xubuntu       | 15        | 1.42%   |
| Kubuntu       | 14        | 1.33%   |
| Elementary    | 13        | 1.23%   |
| SteamOS       | 12        | 1.14%   |
| ROSA          | 11        | 1.04%   |
| EndeavourOS   | 10        | 0.95%   |
| Endless       | 9         | 0.85%   |
| Kali          | 7         | 0.66%   |
| Ubuntu Budgie | 6         | 0.57%   |
| MX            | 6         | 0.57%   |
| Ubuntu Unity  | 5         | 0.47%   |
| LMDE          | 5         | 0.47%   |
| Gentoo        | 5         | 0.47%   |
| ArcoLinux     | 5         | 0.47%   |
| Ubuntu MATE   | 4         | 0.38%   |
| Clear Linux   | 3         | 0.28%   |
| TUXEDO OS     | 2         | 0.19%   |
| Parrot        | 2         | 0.19%   |
| Nobara        | 2         | 0.19%   |
| NixOS         | 2         | 0.19%   |
| Lubuntu       | 2         | 0.19%   |
| Devuan        | 2         | 0.19%   |
| Deepin        | 2         | 0.19%   |
| CentOS        | 2         | 0.19%   |
| CachyOS       | 2         | 0.19%   |
| Void Linux    | 1         | 0.09%   |
| UbuntuDDE     | 1         | 0.09%   |
| Ubuntu Studio | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 24        | 1.94%   |
| 5.4.0-42-generic         | 16        | 1.29%   |
| 5.15.0-56-generic        | 14        | 1.13%   |
| 5.15.0-43-generic        | 13        | 1.05%   |
| 4.18.16-desktop-1bP      | 13        | 1.05%   |
| 5.4.0-58-generic         | 12        | 0.97%   |
| 5.3.0-46-generic         | 12        | 0.97%   |
| 5.15.0-52-generic        | 11        | 0.89%   |
| 5.10.14-desktop-1omv4002 | 11        | 0.89%   |
| 5.6.14-desktop-2bP       | 10        | 0.81%   |
| 5.4.0-52-generic         | 10        | 0.81%   |
| 5.3.0-26-generic         | 10        | 0.81%   |
| 5.4.0-29-generic         | 9         | 0.73%   |
| 5.4.0-26-generic         | 9         | 0.73%   |
| 5.13.0-39-generic        | 9         | 0.73%   |
| 5.13.0-28-generic        | 9         | 0.73%   |
| 5.13.0-27-generic        | 9         | 0.73%   |
| 5.4.0-91-generic         | 8         | 0.65%   |
| 5.11.0-37-generic        | 8         | 0.65%   |
| 5.4.0-48-generic         | 7         | 0.57%   |
| 5.15.0-58-generic        | 7         | 0.57%   |
| 5.15.0-46-generic        | 7         | 0.57%   |
| 5.13.0-valve36-1-neptune | 7         | 0.57%   |
| 5.11.0-27-generic        | 7         | 0.57%   |
| 5.11.0-25-generic        | 7         | 0.57%   |
| 6.1.1-desktop-1omv2290   | 6         | 0.48%   |
| 5.4.0-74-generic         | 6         | 0.48%   |
| 5.4.0-33-generic         | 6         | 0.48%   |
| 5.3.0-42-generic         | 6         | 0.48%   |
| 5.15.0-50-generic        | 6         | 0.48%   |
| 5.11.0-38-generic        | 6         | 0.48%   |
| 5.10.0-8-amd64           | 6         | 0.48%   |
| 6.2.0-32-generic         | 5         | 0.4%    |
| 5.8.0-43-generic         | 5         | 0.4%    |
| 5.4.0-28-generic         | 5         | 0.4%    |
| 5.19.0-32-generic        | 5         | 0.4%    |
| 5.15.12-200.fc35.x86_64  | 5         | 0.4%    |
| 5.15.0-84-generic        | 5         | 0.4%    |
| 5.15.0-71-generic        | 5         | 0.4%    |
| 5.13.0-40-generic        | 5         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 168       | 14.43%  |
| 5.15.0  | 106       | 9.11%   |
| 5.13.0  | 73        | 6.27%   |
| 5.11.0  | 64        | 5.5%    |
| 5.8.0   | 49        | 4.21%   |
| 5.3.0   | 47        | 4.04%   |
| 4.15.0  | 46        | 3.95%   |
| 5.19.0  | 34        | 2.92%   |
| 5.10.0  | 30        | 2.58%   |
| 5.16.7  | 25        | 2.15%   |
| 5.0.0   | 22        | 1.89%   |
| 6.2.0   | 20        | 1.72%   |
| 6.1.0   | 18        | 1.55%   |
| 4.18.0  | 14        | 1.2%    |
| 4.18.16 | 13        | 1.12%   |
| 5.10.14 | 11        | 0.95%   |
| 4.19.0  | 11        | 0.95%   |
| 5.6.14  | 10        | 0.86%   |
| 6.2.6   | 9         | 0.77%   |
| 6.3.5   | 6         | 0.52%   |
| 6.1.1   | 6         | 0.52%   |
| 5.17.5  | 6         | 0.52%   |
| 6.2.11  | 5         | 0.43%   |
| 6.0.7   | 5         | 0.43%   |
| 5.15.12 | 5         | 0.43%   |
| 6.0.12  | 4         | 0.34%   |
| 5.9.11  | 4         | 0.34%   |
| 5.7.9   | 4         | 0.34%   |
| 5.7.0   | 4         | 0.34%   |
| 5.3.18  | 4         | 0.34%   |
| 5.19.7  | 4         | 0.34%   |
| 5.17.1  | 4         | 0.34%   |
| 5.11.12 | 4         | 0.34%   |
| 4.4.0   | 4         | 0.34%   |
| 6.4.12  | 3         | 0.26%   |
| 6.2.8   | 3         | 0.26%   |
| 6.1.7   | 3         | 0.26%   |
| 6.0.2   | 3         | 0.26%   |
| 6.0.18  | 3         | 0.26%   |
| 5.9.10  | 3         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 182       | 15.85%  |
| 5.15    | 127       | 11.06%  |
| 5.13    | 84        | 7.32%   |
| 5.11    | 75        | 6.53%   |
| 5.8     | 64        | 5.57%   |
| 5.10    | 61        | 5.31%   |
| 5.3     | 55        | 4.79%   |
| 5.19    | 47        | 4.09%   |
| 4.15    | 46        | 4.01%   |
| 6.2     | 44        | 3.83%   |
| 6.1     | 44        | 3.83%   |
| 5.16    | 41        | 3.57%   |
| 6.0     | 29        | 2.53%   |
| 4.18    | 27        | 2.35%   |
| 5.6     | 25        | 2.18%   |
| 5.0     | 23        | 2%      |
| 5.17    | 22        | 1.92%   |
| 5.7     | 18        | 1.57%   |
| 6.4     | 16        | 1.39%   |
| 5.9     | 15        | 1.31%   |
| 5.18    | 13        | 1.13%   |
| 4.19    | 13        | 1.13%   |
| 5.14    | 12        | 1.05%   |
| 6.3     | 11        | 0.96%   |
| 5.12    | 11        | 0.96%   |
| 6.5     | 8         | 0.7%    |
| 4.9     | 7         | 0.61%   |
| 5.5     | 6         | 0.52%   |
| 4.4     | 5         | 0.44%   |
| 4.17    | 4         | 0.35%   |
| 5.2     | 3         | 0.26%   |
| 4.12    | 3         | 0.26%   |
| 5.1     | 2         | 0.17%   |
| 4.13    | 2         | 0.17%   |
| 4.8     | 1         | 0.09%   |
| 4.14    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1014      | 98.73%  |
| i686   | 13        | 1.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 478       | 45.05%  |
| KDE5            | 193       | 18.19%  |
| Unknown         | 93        | 8.77%   |
| XFCE            | 87        | 8.2%    |
| X-Cinnamon      | 87        | 8.2%    |
| MATE            | 26        | 2.45%   |
| KDE             | 17        | 1.6%    |
| Cinnamon        | 15        | 1.41%   |
| Pantheon        | 13        | 1.23%   |
| i3              | 7         | 0.66%   |
| Budgie          | 7         | 0.66%   |
| Unity           | 5         | 0.47%   |
| KDE4            | 5         | 0.47%   |
| LXDE            | 4         | 0.38%   |
| Deepin          | 4         | 0.38%   |
| awesome         | 4         | 0.38%   |
| sway            | 3         | 0.28%   |
| LXQt            | 3         | 0.28%   |
| GNOME Flashback | 3         | 0.28%   |
| qtile           | 1         | 0.09%   |
| openbox         | 1         | 0.09%   |
| Hyprland        | 1         | 0.09%   |
| gamescope       | 1         | 0.09%   |
| fluxbox         | 1         | 0.09%   |
| Enlightenment   | 1         | 0.09%   |
| Bspwm           | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 808       | 76.52%  |
| Wayland | 192       | 18.18%  |
| Unknown | 49        | 4.64%   |
| Tty     | 7         | 0.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 486       | 45.46%  |
| SDDM    | 161       | 15.06%  |
| GDM     | 140       | 13.1%   |
| GDM3    | 133       | 12.44%  |
| LightDM | 117       | 10.94%  |
| TDM     | 25        | 2.34%   |
| KDM     | 5         | 0.47%   |
| SLiM    | 1         | 0.09%   |
| MDM     | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| de_AT   | 369       | 34.88%  |
| en_US   | 321       | 30.34%  |
| de_DE   | 157       | 14.84%  |
| Unknown | 109       | 10.3%   |
| en_GB   | 38        | 3.59%   |
| C       | 14        | 1.32%   |
| es_ES   | 7         | 0.66%   |
| pl_PL   | 6         | 0.57%   |
| en_IE   | 5         | 0.47%   |
| it_IT   | 4         | 0.38%   |
| ru_RU   | 3         | 0.28%   |
| POSIX   | 3         | 0.28%   |
| en_AT   | 3         | 0.28%   |
| de_CH   | 3         | 0.28%   |
| tr_TR   | 2         | 0.19%   |
| en_DE   | 2         | 0.19%   |
| uk_UA   | 1         | 0.09%   |
| sv_SE   | 1         | 0.09%   |
| ro_RO   | 1         | 0.09%   |
| pt_BR   | 1         | 0.09%   |
| nl_NL   | 1         | 0.09%   |
| hr_HR   | 1         | 0.09%   |
| fr_FR   | 1         | 0.09%   |
| en_CA   | 1         | 0.09%   |
| en      | 1         | 0.09%   |
| de_LI   | 1         | 0.09%   |
| C.UTF8  | 1         | 0.09%   |
| bg_BG   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 571       | 54.02%  |
| BIOS | 486       | 45.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 799       | 76.24%  |
| Btrfs   | 101       | 9.64%   |
| Overlay | 84        | 8.02%   |
| Unknown | 30        | 2.86%   |
| Tmpfs   | 13        | 1.24%   |
| Xfs     | 8         | 0.76%   |
| Zfs     | 6         | 0.57%   |
| Ext3    | 2         | 0.19%   |
| Ext2    | 2         | 0.19%   |
| XXXXXXX | 1         | 0.1%    |
| Nfs     | 1         | 0.1%    |
| Aufs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 522       | 49.62%  |
| GPT     | 416       | 39.54%  |
| MBR     | 114       | 10.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 922       | 88.4%   |
| Yes       | 121       | 11.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 787       | 75.6%   |
| Yes       | 254       | 24.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 290       | 28.27%  |
| Hewlett-Packard     | 190       | 18.52%  |
| Dell                | 108       | 10.53%  |
| Acer                | 93        | 9.06%   |
| ASUSTek Computer    | 91        | 8.87%   |
| Apple               | 33        | 3.22%   |
| Medion              | 31        | 3.02%   |
| Toshiba             | 26        | 2.53%   |
| TUXEDO              | 20        | 1.95%   |
| Sony                | 19        | 1.85%   |
| MSI                 | 15        | 1.46%   |
| Valve               | 12        | 1.17%   |
| Fujitsu             | 11        | 1.07%   |
| HUAWEI              | 10        | 0.97%   |
| Samsung Electronics | 8         | 0.78%   |
| Unknown             | 7         | 0.68%   |
| Notebook            | 5         | 0.49%   |
| TrekStor            | 4         | 0.39%   |
| Razer               | 4         | 0.39%   |
| Fujitsu Siemens     | 4         | 0.39%   |
| Clevo               | 4         | 0.39%   |
| Wortmann AG         | 2         | 0.19%   |
| VALE                | 2         | 0.19%   |
| Timi                | 2         | 0.19%   |
| System76            | 2         | 0.19%   |
| Shuttle             | 2         | 0.19%   |
| Schenker            | 2         | 0.19%   |
| Panasonic           | 2         | 0.19%   |
| Packard Bell        | 2         | 0.19%   |
| Hampoo              | 2         | 0.19%   |
| Google              | 2         | 0.19%   |
| Gigabyte Technology | 2         | 0.19%   |
| Chuwi               | 2         | 0.19%   |
| AXDIA International | 2         | 0.19%   |
| W271ELQ             | 1         | 0.1%    |
| TWJ                 | 1         | 0.1%    |
| TENKU               | 1         | 0.1%    |
| Teclast             | 1         | 0.1%    |
| MAXDATA             | 1         | 0.1%    |
| LG Electronics      | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 13        | 1.27%   |
| Valve Jupiter                   | 12        | 1.17%   |
| Apple MacBookPro15,1            | 8         | 0.78%   |
| HP EliteBook 8570p              | 6         | 0.58%   |
| HP EliteBook 840 G3             | 6         | 0.58%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 5         | 0.49%   |
| HP Pavilion dv6                 | 5         | 0.49%   |
| HP EliteBook 840 G6             | 5         | 0.49%   |
| Dell Latitude E6400             | 5         | 0.49%   |
| Toshiba Satellite C70D-B        | 4         | 0.39%   |
| Lenovo Yoga Slim 7 14ARE05 82A2 | 4         | 0.39%   |
| Lenovo IdeaPad 700-15ISK 80RU   | 4         | 0.39%   |
| HP Pavilion dv7                 | 4         | 0.39%   |
| HP Notebook                     | 4         | 0.39%   |
| HP EliteBook 8460p              | 4         | 0.39%   |
| HP EliteBook 6930p              | 4         | 0.39%   |
| Dell XPS 15 9570                | 4         | 0.39%   |
| Dell Latitude E7450             | 4         | 0.39%   |
| Dell Latitude 5520              | 4         | 0.39%   |
| ASUS UX303LAB                   | 4         | 0.39%   |
| Apple MacBookPro8,1             | 4         | 0.39%   |
| TrekStor Notebook Slim S130     | 3         | 0.29%   |
| Medion P15648                   | 3         | 0.29%   |
| Lenovo ThinkPad E470 20H2S00700 | 3         | 0.29%   |
| HP ZBook 17 G5                  | 3         | 0.29%   |
| HP Pavilion g7                  | 3         | 0.29%   |
| HP EliteBook 850 G1             | 3         | 0.29%   |
| HP EliteBook 840 G8 Notebook PC | 3         | 0.29%   |
| HP EliteBook 840 G1             | 3         | 0.29%   |
| HP EliteBook 2560p              | 3         | 0.29%   |
| Dell XPS 17 9700                | 3         | 0.29%   |
| Dell XPS 13 9343                | 3         | 0.29%   |
| Dell XPS 13 9305                | 3         | 0.29%   |
| Dell Latitude E7440             | 3         | 0.29%   |
| Dell Latitude E5550             | 3         | 0.29%   |
| Dell Inspiron 1720              | 3         | 0.29%   |
| Apple MacBookPro9,2             | 3         | 0.29%   |
| Acer TravelMate P253            | 3         | 0.29%   |
| Acer Swift SF314-42             | 3         | 0.29%   |
| Acer Swift SF114-34             | 3         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 202       | 19.69%  |
| HP EliteBook        | 69        | 6.73%   |
| Acer Aspire         | 59        | 5.75%   |
| Dell Latitude       | 52        | 5.07%   |
| Lenovo IdeaPad      | 35        | 3.41%   |
| HP ProBook          | 33        | 3.22%   |
| HP Pavilion         | 28        | 2.73%   |
| Dell XPS            | 28        | 2.73%   |
| Toshiba Satellite   | 23        | 2.24%   |
| Dell Inspiron       | 14        | 1.36%   |
| Unknown             | 13        | 1.27%   |
| Valve Jupiter       | 12        | 1.17%   |
| Lenovo Yoga         | 12        | 1.17%   |
| HP ZBook            | 12        | 1.17%   |
| ASUS VivoBook       | 12        | 1.17%   |
| Fujitsu LIFEBOOK    | 11        | 1.07%   |
| Acer TravelMate     | 11        | 1.07%   |
| Lenovo ThinkBook    | 10        | 0.97%   |
| HP Laptop           | 10        | 0.97%   |
| Dell Precision      | 9         | 0.88%   |
| Acer Swift          | 9         | 0.88%   |
| Apple MacBookPro15  | 8         | 0.78%   |
| ASUS ZenBook        | 7         | 0.68%   |
| ASUS ROG            | 7         | 0.68%   |
| HP Compaq           | 6         | 0.58%   |
| HP 250              | 6         | 0.58%   |
| Acer Nitro          | 6         | 0.58%   |
| Lenovo Legion       | 5         | 0.49%   |
| HP OMEN             | 5         | 0.49%   |
| Apple MacBookPro8   | 5         | 0.49%   |
| Razer Blade         | 4         | 0.39%   |
| HP Notebook         | 4         | 0.39%   |
| HP 255              | 4         | 0.39%   |
| ASUS UX303LAB       | 4         | 0.39%   |
| TUXEDO InfinityBook | 3         | 0.29%   |
| TrekStor Notebook   | 3         | 0.29%   |
| MSI Modern          | 3         | 0.29%   |
| Medion P15648       | 3         | 0.29%   |
| Apple MacBookPro9   | 3         | 0.29%   |
| Apple MacBookPro5   | 3         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 128       | 12.48%  |
| 2012 | 92        | 8.97%   |
| 2021 | 83        | 8.09%   |
| 2011 | 78        | 7.6%    |
| 2019 | 76        | 7.41%   |
| 2018 | 75        | 7.31%   |
| 2017 | 68        | 6.63%   |
| 2014 | 64        | 6.24%   |
| 2016 | 63        | 6.14%   |
| 2015 | 61        | 5.95%   |
| 2013 | 58        | 5.65%   |
| 2008 | 41        | 4%      |
| 2022 | 38        | 3.7%    |
| 2010 | 35        | 3.41%   |
| 2009 | 31        | 3.02%   |
| 2007 | 18        | 1.75%   |
| 2023 | 10        | 0.97%   |
| 2006 | 6         | 0.58%   |
| 2005 | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1026      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 912       | 87.52%  |
| Enabled  | 130       | 12.48%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1021      | 99.51%  |
| Yes  | 5         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 267       | 25.72%  |
| 16.01-24.0  | 204       | 19.65%  |
| 8.01-16.0   | 204       | 19.65%  |
| 3.01-4.0    | 182       | 17.53%  |
| 32.01-64.0  | 92        | 8.86%   |
| 1.01-2.0    | 38        | 3.66%   |
| 24.01-32.0  | 20        | 1.93%   |
| 64.01-256.0 | 13        | 1.25%   |
| 2.01-3.0    | 11        | 1.06%   |
| 0.51-1.0    | 7         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 401       | 34.9%   |
| 2.01-3.0   | 299       | 26.02%  |
| 4.01-8.0   | 169       | 14.71%  |
| 3.01-4.0   | 141       | 12.27%  |
| 0.51-1.0   | 66        | 5.74%   |
| 8.01-16.0  | 51        | 4.44%   |
| 16.01-24.0 | 11        | 0.96%   |
| 24.01-32.0 | 5         | 0.44%   |
| 0.01-0.5   | 5         | 0.44%   |
| 32.01-64.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 778       | 74.31%  |
| 2      | 219       | 20.92%  |
| 3      | 37        | 3.53%   |
| 0      | 7         | 0.67%   |
| 5      | 3         | 0.29%   |
| 4      | 3         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 682       | 66.28%  |
| Yes       | 347       | 33.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 846       | 82.22%  |
| No        | 183       | 17.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1015      | 98.93%  |
| No        | 11        | 1.07%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 804       | 77.91%  |
| No        | 228       | 22.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Austria | 1026      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Vienna                    | 630       | 58.23%  |
| Graz                      | 59        | 5.45%   |
| Salzburg                  | 26        | 2.4%    |
| Innsbruck                 | 26        | 2.4%    |
| Linz                      | 22        | 2.03%   |
| Bad Hall                  | 18        | 1.66%   |
| Klagenfurt                | 14        | 1.29%   |
| Wels                      | 8         | 0.74%   |
| Leonding                  | 8         | 0.74%   |
| Baden bei Wien            | 7         | 0.65%   |
| Wiener Neustadt           | 6         | 0.55%   |
| Villach                   | 6         | 0.55%   |
| Sankt Pölten             | 6         | 0.55%   |
| Perg                      | 6         | 0.55%   |
| Wörgl                    | 5         | 0.46%   |
| Korneuburg                | 5         | 0.46%   |
| Dornbirn                  | 5         | 0.46%   |
| Umhausen                  | 4         | 0.37%   |
| Traun                     | 4         | 0.37%   |
| Feldkirch                 | 4         | 0.37%   |
| Bregenz                   | 4         | 0.37%   |
| Traunkirchen              | 3         | 0.28%   |
| Knittelfeld               | 3         | 0.28%   |
| Hard                      | 3         | 0.28%   |
| Gaenserndorf              | 3         | 0.28%   |
| Woerdern                  | 2         | 0.18%   |
| Traiskirchen              | 2         | 0.18%   |
| Steyr                     | 2         | 0.18%   |
| Spielberg bei Knittelfeld | 2         | 0.18%   |
| Sommerein                 | 2         | 0.18%   |
| Schleinbach               | 2         | 0.18%   |
| Oberneukirchen            | 2         | 0.18%   |
| Neusiedl am See           | 2         | 0.18%   |
| Mauthausen                | 2         | 0.18%   |
| Mautern                   | 2         | 0.18%   |
| Mattersburg               | 2         | 0.18%   |
| Lustenau                  | 2         | 0.18%   |
| Lech                      | 2         | 0.18%   |
| Kalsdorf bei Graz         | 2         | 0.18%   |
| Hartberg                  | 2         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 306       | 424    | 24.08%  |
| SanDisk                        | 125       | 167    | 9.83%   |
| Seagate                        | 110       | 146    | 8.65%   |
| Toshiba                        | 101       | 126    | 7.95%   |
| WDC                            | 92        | 126    | 7.24%   |
| Unknown                        | 71        | 94     | 5.59%   |
| SK hynix                       | 59        | 74     | 4.64%   |
| Kingston                       | 48        | 63     | 3.78%   |
| Crucial                        | 44        | 60     | 3.46%   |
| Intel                          | 37        | 39     | 2.91%   |
| Micron Technology              | 30        | 38     | 2.36%   |
| Hitachi                        | 30        | 33     | 2.36%   |
| HGST                           | 28        | 35     | 2.2%    |
| Intenso                        | 24        | 30     | 1.89%   |
| Transcend                      | 15        | 17     | 1.18%   |
| Apple                          | 15        | 26     | 1.18%   |
| KIOXIA                         | 14        | 20     | 1.1%    |
| China                          | 9         | 9      | 0.71%   |
| LITEONIT                       | 7         | 10     | 0.55%   |
| Phison                         | 6         | 6      | 0.47%   |
| LITEON                         | 5         | 6      | 0.39%   |
| A-DATA Technology              | 5         | 8      | 0.39%   |
| Unknown                        | 5         | 9      | 0.39%   |
| Micron/Crucial Technology      | 4         | 4      | 0.31%   |
| Lenovo                         | 4         | 5      | 0.31%   |
| ASMT                           | 4         | 6      | 0.31%   |
| Union Memory (Shenzhen)        | 3         | 4      | 0.24%   |
| SABRENT                        | 3         | 3      | 0.24%   |
| Phison Electronics             | 3         | 4      | 0.24%   |
| OCZ                            | 3         | 4      | 0.24%   |
| MAXIO Technology (Hangzhou)    | 3         | 3      | 0.24%   |
| Kingston Technology Company    | 3         | 3      | 0.24%   |
| JMicron Technology             | 3         | 3      | 0.24%   |
| INNOVATION IT                  | 3         | 4      | 0.24%   |
| UMIS                           | 2         | 2      | 0.16%   |
| SPCC                           | 2         | 2      | 0.16%   |
| Solid State Storage Technology | 2         | 2      | 0.16%   |
| Silicon Motion                 | 2         | 3      | 0.16%   |
| Leven                          | 2         | 2      | 0.16%   |
| KingDian                       | 2         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB                      | 23        | 1.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 15        | 1.12%   |
| Toshiba MQ01ABD100 1TB                            | 13        | 0.97%   |
| Samsung SSD 860 EVO 500GB                         | 13        | 0.97%   |
| Samsung SSD 850 EVO 250GB                         | 13        | 0.97%   |
| Unknown MMC Card  64GB                            | 12        | 0.9%    |
| SanDisk NVMe SSD Drive 512GB                      | 12        | 0.9%    |
| Samsung NVMe SSD Drive 1TB                        | 12        | 0.9%    |
| Unknown MMC Card  32GB                            | 10        | 0.75%   |
| Toshiba MQ04ABF100 1TB                            | 10        | 0.75%   |
| Seagate ST500LT012-1DG142 500GB                   | 9         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 9         | 0.67%   |
| Samsung NVMe SSD Drive 1024GB                     | 9         | 0.67%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB              | 8         | 0.6%    |
| Transcend TS240GMTS420S 240GB SSD                 | 8         | 0.6%    |
| SK hynix NVMe SSD Drive 512GB                     | 8         | 0.6%    |
| SK hynix HFS256G39TND-N210A 256GB SSD             | 8         | 0.6%    |
| SanDisk SSD PLUS 240GB                            | 8         | 0.6%    |
| Samsung SSD 850 PRO 256GB                         | 8         | 0.6%    |
| Toshiba MQ01ABF050 500GB                          | 7         | 0.52%   |
| Seagate ST9500325AS 500GB                         | 7         | 0.52%   |
| Samsung NVMe SSD Drive 500GB                      | 7         | 0.52%   |
| Apple SSD AP0512M 500GB                           | 7         | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                      | 6         | 0.45%   |
| Samsung SSD 850 EVO 500GB                         | 6         | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                  | 6         | 0.45%   |
| Kingston NVMe SSD Drive 512GB                     | 6         | 0.45%   |
| HGST HTS721010A9E630 1TB                          | 6         | 0.45%   |
| HGST HTS541010A9E680 1TB                          | 6         | 0.45%   |
| Crucial CT500MX500SSD1 500GB                      | 6         | 0.45%   |
| Crucial CT240BX500SSD1 240GB                      | 6         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 5         | 0.37%   |
| Unknown MMC Card  128GB                           | 5         | 0.37%   |
| Toshiba NVMe SSD Drive 512GB                      | 5         | 0.37%   |
| Toshiba NVMe SSD Drive 256GB                      | 5         | 0.37%   |
| Toshiba KXG6AZNV1T02 1TB                          | 5         | 0.37%   |
| Seagate ST2000LM015-2E8174 2TB                    | 5         | 0.37%   |
| Seagate Expansion 1TB                             | 5         | 0.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB | 5         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 108       | 144    | 36.24%  |
| Toshiba             | 64        | 85     | 21.48%  |
| WDC                 | 56        | 75     | 18.79%  |
| Hitachi             | 30        | 33     | 10.07%  |
| HGST                | 28        | 35     | 9.4%    |
| Samsung Electronics | 6         | 7      | 2.01%   |
| Fujitsu             | 2         | 2      | 0.67%   |
| Unknown             | 1         | 2      | 0.34%   |
| IB-1122             | 1         | 1      | 0.34%   |
| IB                  | 1         | 2      | 0.34%   |
| Apple               | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 135       | 175    | 29.09%  |
| SanDisk             | 85        | 116    | 18.32%  |
| Crucial             | 41        | 57     | 8.84%   |
| Kingston            | 32        | 42     | 6.9%    |
| Intenso             | 22        | 28     | 4.74%   |
| SK hynix            | 18        | 22     | 3.88%   |
| Intel               | 16        | 16     | 3.45%   |
| Transcend           | 15        | 17     | 3.23%   |
| Micron Technology   | 11        | 15     | 2.37%   |
| Toshiba             | 9         | 11     | 1.94%   |
| China               | 9         | 9      | 1.94%   |
| WDC                 | 7         | 8      | 1.51%   |
| LITEONIT            | 7         | 10     | 1.51%   |
| Apple               | 6         | 6      | 1.29%   |
| LITEON              | 5         | 6      | 1.08%   |
| A-DATA Technology   | 5         | 8      | 1.08%   |
| SABRENT             | 3         | 3      | 0.65%   |
| OCZ                 | 3         | 4      | 0.65%   |
| INNOVATION IT       | 3         | 4      | 0.65%   |
| SPCC                | 2         | 2      | 0.43%   |
| Phison              | 2         | 2      | 0.43%   |
| Leven               | 2         | 2      | 0.43%   |
| KingDian            | 2         | 2      | 0.43%   |
| GOODRAM             | 2         | 2      | 0.43%   |
| Corsair             | 2         | 2      | 0.43%   |
| ASMT                | 2         | 2      | 0.43%   |
| WDC WDS             | 1         | 1      | 0.22%   |
| Verbatim            | 1         | 1      | 0.22%   |
| Vaseky              | 1         | 1      | 0.22%   |
| Unknown             | 1         | 2      | 0.22%   |
| Teclast             | 1         | 1      | 0.22%   |
| TCSUNBOW            | 1         | 1      | 0.22%   |
| Seagate             | 1         | 1      | 0.22%   |
| Patriot             | 1         | 1      | 0.22%   |
| Netac               | 1         | 4      | 0.22%   |
| Mushkin             | 1         | 1      | 0.22%   |
| Inateck             | 1         | 1      | 0.22%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |
| Gigabyte Technology | 1         | 1      | 0.22%   |
| FORESEE             | 1         | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 430       | 593    | 35.22%  |
| NVMe    | 415       | 567    | 33.99%  |
| HDD     | 287       | 387    | 23.51%  |
| MMC     | 74        | 102    | 6.06%   |
| Unknown | 15        | 16     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 639       | 933    | 54.29%  |
| NVMe | 413       | 562    | 35.09%  |
| MMC  | 74        | 102    | 6.29%   |
| SAS  | 51        | 68     | 4.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 491       | 689    | 68.67%  |
| 0.51-1.0   | 196       | 252    | 27.41%  |
| 1.01-2.0   | 19        | 28     | 2.66%   |
| 3.01-4.0   | 3         | 3      | 0.42%   |
| 2.01-3.0   | 3         | 5      | 0.42%   |
| 4.01-10.0  | 3         | 3      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 316       | 29.18%  |
| 251-500        | 262       | 24.19%  |
| 501-1000       | 157       | 14.5%   |
| 1-20           | 80        | 7.39%   |
| 51-100         | 66        | 6.09%   |
| 1001-2000      | 60        | 5.54%   |
| Unknown        | 53        | 4.89%   |
| 21-50          | 44        | 4.06%   |
| More than 3000 | 26        | 2.4%    |
| 2001-3000      | 19        | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 423       | 37.43%  |
| 21-50          | 211       | 18.67%  |
| 101-250        | 154       | 13.63%  |
| 51-100         | 119       | 10.53%  |
| 251-500        | 76        | 6.73%   |
| 501-1000       | 58        | 5.13%   |
| Unknown        | 53        | 4.69%   |
| 1001-2000      | 23        | 2.04%   |
| More than 3000 | 7         | 0.62%   |
| 2001-3000      | 6         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB               | 4         | 4      | 6.56%   |
| Toshiba MQ01ABF050 500GB                         | 3         | 4      | 4.92%   |
| Seagate ST9160412AS 160GB                        | 2         | 2      | 3.28%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 4      | 3.28%   |
| HGST HTS721010A9E630 1TB                         | 2         | 3      | 3.28%   |
| WDC WD5000LPLX-00ZNTT0 500GB                     | 1         | 1      | 1.64%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 1.64%   |
| Toshiba MQ02ABF050H 500GB                        | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100M 1TB                          | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.64%   |
| Toshiba MK7559GSXP 752GB                         | 1         | 1      | 1.64%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 1.64%   |
| Toshiba MK3276GSX 320GB                          | 1         | 1      | 1.64%   |
| Toshiba MK2035GSS 200GB                          | 1         | 1      | 1.64%   |
| Toshiba MK1233GSG 120GB                          | 1         | 1      | 1.64%   |
| Seagate ST9750420AS 752GB                        | 1         | 1      | 1.64%   |
| Seagate ST95005620AS 500GB                       | 1         | 1      | 1.64%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.64%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.64%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 2      | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 1.64%   |
| Seagate ST1000LM014-1EJ164-SSHD 1TB              | 1         | 9      | 1.64%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 1.64%   |
| SanDisk SDSSDH3 1T00 1TB                         | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 870 EVO 500GB            | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 870 EVO 1TB              | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 850 EVO 1TB              | 1         | 1      | 1.64%   |
| Samsung Electronics SSD 840 Series 120GB         | 1         | 1      | 1.64%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB SSD | 1         | 1      | 1.64%   |
| Samsung Electronics MMCRE28G8MXP-0VBH1 128GB SSD | 1         | 1      | 1.64%   |
| Samsung Electronics HN-M101MBB 1TB               | 1         | 1      | 1.64%   |
| Samsung Electronics HM500JI 500GB                | 1         | 1      | 1.64%   |
| LITEONIT LCS-128L9S-11 2.5 7mm 128GB SSD         | 1         | 1      | 1.64%   |
| LITEONIT CMT-64L3M 64GB SSD                      | 1         | 2      | 1.64%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 1      | 1.64%   |
| Kingston SMSM150S324G 24GB SSD                   | 1         | 1      | 1.64%   |
| Intel SSDSCKJF180A5L 180GB                       | 1         | 1      | 1.64%   |
| Intel SSDSC2BF240A5L 240GB                       | 1         | 1      | 1.64%   |
| Intel SSDSC2BF180A5L 180GB                       | 1         | 1      | 1.64%   |
| Intel SSDPEKNW512G8H 512GB                       | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 26     | 23.73%  |
| Toshiba             | 11        | 12     | 18.64%  |
| Samsung Electronics | 7         | 8      | 11.86%  |
| Hitachi             | 5         | 6      | 8.47%   |
| HGST                | 5         | 6      | 8.47%   |
| Intel               | 4         | 4      | 6.78%   |
| WDC                 | 2         | 2      | 3.39%   |
| SanDisk             | 2         | 2      | 3.39%   |
| LITEONIT            | 2         | 3      | 3.39%   |
| LITEON              | 1         | 1      | 1.69%   |
| Kingston            | 1         | 1      | 1.69%   |
| GOODRAM             | 1         | 1      | 1.69%   |
| Fujitsu             | 1         | 1      | 1.69%   |
| Crucial             | 1         | 1      | 1.69%   |
| Corsair             | 1         | 1      | 1.69%   |
| A-DATA Technology   | 1         | 3      | 1.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 26     | 35%     |
| Toshiba             | 11        | 12     | 27.5%   |
| Hitachi             | 5         | 6      | 12.5%   |
| HGST                | 5         | 6      | 12.5%   |
| WDC                 | 2         | 2      | 5%      |
| Samsung Electronics | 2         | 2      | 5%      |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 55     | 67.24%  |
| SSD  | 18        | 22     | 31.03%  |
| NVMe | 1         | 1      | 1.72%   |

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
| Detected | 625       | 996    | 56.56%  |
| Works    | 422       | 591    | 38.19%  |
| Malfunc  | 58        | 78     | 5.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 664       | 55.8%   |
| Samsung Electronics                     | 178       | 14.96%  |
| AMD                                     | 105       | 8.82%   |
| SanDisk                                 | 65        | 5.46%   |
| SK hynix                                | 41        | 3.45%   |
| Toshiba America Info Systems            | 32        | 2.69%   |
| Micron Technology                       | 20        | 1.68%   |
| Kingston Technology Company             | 18        | 1.51%   |
| KIOXIA                                  | 13        | 1.09%   |
| Nvidia                                  | 10        | 0.84%   |
| Apple                                   | 8         | 0.67%   |
| Phison Electronics                      | 7         | 0.59%   |
| Union Memory (Shenzhen)                 | 6         | 0.5%    |
| Micron/Crucial Technology               | 6         | 0.5%    |
| Lenovo                                  | 4         | 0.34%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.25%   |
| Solid State Storage Technology          | 2         | 0.17%   |
| Silicon Motion                          | 2         | 0.17%   |
| VIA Technologies                        | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.08%   |
| Shenzhen Unionmemory Information System | 1         | 0.08%   |
| Seagate Technology                      | 1         | 0.08%   |
| Realtek Semiconductor                   | 1         | 0.08%   |
| ADATA Technology                        | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 93        | 7.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 87        | 6.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 81        | 6.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 80        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 77        | 6.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 50        | 3.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 39        | 3.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 39        | 3.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 34        | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 33        | 2.59%   |
| Intel Volume Management Device NVMe RAID Controller                              | 30        | 2.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 24        | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 1.81%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 22        | 1.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 21        | 1.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 21        | 1.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 20        | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 19        | 1.49%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 17        | 1.34%   |
| Intel Tiger Lake-LP SATA Controller                                              | 16        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 1.18%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 12        | 0.94%   |
| Intel SSD 660P Series                                                            | 12        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 0.86%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 10        | 0.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 10        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 10        | 0.79%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 9         | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.71%   |
| SK hynix BC511 NVMe SSD                                                          | 8         | 0.63%   |
| Apple ANS2 NVMe Controller                                                       | 8         | 0.63%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 7         | 0.55%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 7         | 0.55%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 7         | 0.55%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 7         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 684       | 55.07%  |
| NVMe | 414       | 33.33%  |
| RAID | 82        | 6.6%    |
| IDE  | 62        | 4.99%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 828       | 80.7%   |
| AMD    | 198       | 19.3%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 23        | 2.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 1.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.56%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 1.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 1.46%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 14        | 1.36%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 1.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 14        | 1.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 1.17%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 1.17%   |
| AMD Custom APU 0405                           | 12        | 1.17%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 11        | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 1.07%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.07%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 0.88%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 9         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 9         | 0.88%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 8         | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.78%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 0.78%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 8         | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 7         | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.68%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 7         | 0.68%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 7         | 0.68%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 6         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 6         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 265       | 25.8%   |
| Intel Core i5           | 260       | 25.32%  |
| Other                   | 90        | 8.76%   |
| Intel Core 2 Duo        | 55        | 5.36%   |
| AMD Ryzen 7             | 49        | 4.77%   |
| Intel Core i3           | 45        | 4.38%   |
| AMD Ryzen 5             | 41        | 3.99%   |
| Intel Celeron           | 36        | 3.51%   |
| Intel Pentium           | 28        | 2.73%   |
| AMD Ryzen 7 PRO         | 22        | 2.14%   |
| Intel Atom              | 20        | 1.95%   |
| Intel Pentium Dual-Core | 9         | 0.88%   |
| Intel Core i9           | 9         | 0.88%   |
| AMD A6                  | 9         | 0.88%   |
| AMD A4                  | 9         | 0.88%   |
| AMD Ryzen 9             | 8         | 0.78%   |
| AMD A8                  | 8         | 0.78%   |
| Intel Core 2            | 6         | 0.58%   |
| AMD Ryzen 5 PRO         | 6         | 0.58%   |
| Intel Pentium Silver    | 5         | 0.49%   |
| AMD E2                  | 5         | 0.49%   |
| Intel Genuine           | 4         | 0.39%   |
| AMD E1                  | 4         | 0.39%   |
| AMD Ryzen 3             | 3         | 0.29%   |
| AMD E                   | 3         | 0.29%   |
| AMD Athlon II           | 3         | 0.29%   |
| AMD Athlon              | 3         | 0.29%   |
| Intel Xeon              | 2         | 0.19%   |
| Intel Pentium Dual      | 2         | 0.19%   |
| Intel Core m5           | 2         | 0.19%   |
| AMD Turion 64 X2 Mobile | 2         | 0.19%   |
| AMD A10                 | 2         | 0.19%   |
| Intel Pentium Gold      | 1         | 0.1%    |
| Intel Core m7           | 1         | 0.1%    |
| Intel Core M            | 1         | 0.1%    |
| Intel Core 2 Solo       | 1         | 0.1%    |
| Intel Celeron M         | 1         | 0.1%    |
| AMD Sempron             | 1         | 0.1%    |
| AMD PRO A8              | 1         | 0.1%    |
| AMD Phenom II           | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 470       | 45.76%  |
| 4       | 355       | 34.57%  |
| 8       | 90        | 8.76%   |
| 6       | 78        | 7.59%   |
| 1       | 14        | 1.36%   |
| 12      | 8         | 0.78%   |
| 10      | 5         | 0.49%   |
| 14      | 4         | 0.39%   |
| 16      | 1         | 0.1%    |
| 5       | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1026      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 785       | 76.36%  |
| 1       | 242       | 23.54%  |
| Unknown | 1         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1007      | 98.05%  |
| Unknown        | 13        | 1.27%   |
| 32-bit         | 7         | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 256       | 24.04%  |
| 0x206a7    | 74        | 6.95%   |
| 0x306a9    | 62        | 5.82%   |
| 0x806ec    | 48        | 4.51%   |
| 0x806ea    | 36        | 3.38%   |
| 0x406e3    | 36        | 3.38%   |
| 0x806c1    | 34        | 3.19%   |
| 0x306d4    | 34        | 3.19%   |
| 0x1067a    | 33        | 3.1%    |
| 0x906ea    | 30        | 2.82%   |
| 0x40651    | 28        | 2.63%   |
| 0x806e9    | 21        | 1.97%   |
| 0x306c3    | 21        | 1.97%   |
| 0x08600106 | 21        | 1.97%   |
| 0x0a50000c | 16        | 1.5%    |
| 0x506e3    | 15        | 1.41%   |
| 0x20655    | 14        | 1.31%   |
| 0xa0652    | 12        | 1.13%   |
| 0x906e9    | 12        | 1.13%   |
| 0x10676    | 12        | 1.13%   |
| 0x08600103 | 12        | 1.13%   |
| 0x08108102 | 12        | 1.13%   |
| 0x706e5    | 11        | 1.03%   |
| 0x08608103 | 11        | 1.03%   |
| 0x07030105 | 11        | 1.03%   |
| 0x506c9    | 10        | 0.94%   |
| 0x806eb    | 9         | 0.85%   |
| 0x406c3    | 9         | 0.85%   |
| 0x906a3    | 8         | 0.75%   |
| 0x30678    | 8         | 0.75%   |
| 0x406c4    | 7         | 0.66%   |
| 0x20652    | 7         | 0.66%   |
| 0x08600104 | 7         | 0.66%   |
| 0x906ed    | 6         | 0.56%   |
| 0x706a8    | 6         | 0.56%   |
| 0x06006705 | 6         | 0.56%   |
| 0x05000119 | 6         | 0.56%   |
| 0x806d1    | 5         | 0.47%   |
| 0x6fd      | 5         | 0.47%   |
| 0x6fb      | 5         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 208       | 20.25%  |
| SandyBridge      | 88        | 8.57%   |
| IvyBridge        | 80        | 7.79%   |
| Haswell          | 70        | 6.82%   |
| Skylake          | 60        | 5.84%   |
| Penryn           | 55        | 5.36%   |
| Zen 2            | 53        | 5.16%   |
| TigerLake        | 49        | 4.77%   |
| Broadwell        | 42        | 4.09%   |
| Unknown          | 39        | 3.8%    |
| Silvermont       | 30        | 2.92%   |
| Zen 3            | 29        | 2.82%   |
| Westmere         | 27        | 2.63%   |
| Icelake          | 21        | 2.04%   |
| Zen+             | 20        | 1.95%   |
| Core             | 20        | 1.95%   |
| Alderlake Hybrid | 16        | 1.56%   |
| Puma             | 14        | 1.36%   |
| CometLake        | 14        | 1.36%   |
| Goldmont plus    | 12        | 1.17%   |
| Goldmont         | 11        | 1.07%   |
| Excavator        | 11        | 1.07%   |
| Zen              | 9         | 0.88%   |
| Bobcat           | 9         | 0.88%   |
| Bonnell          | 8         | 0.78%   |
| Nehalem          | 5         | 0.49%   |
| K10              | 5         | 0.49%   |
| Jaguar           | 5         | 0.49%   |
| K8 Hammer        | 4         | 0.39%   |
| Piledriver       | 3         | 0.29%   |
| P6               | 3         | 0.29%   |
| K10 Llano        | 3         | 0.29%   |
| Tremont          | 2         | 0.19%   |
| K8 & K10 hybrid  | 2         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 720       | 56.25%  |
| Nvidia                           | 280       | 21.88%  |
| AMD                              | 279       | 21.8%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 74        | 5.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 72        | 5.48%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 52        | 3.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 44        | 3.35%   |
| Intel UHD Graphics 620                                                                   | 43        | 3.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 40        | 3.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 40        | 3.05%   |
| Intel HD Graphics 5500                                                                   | 36        | 2.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 2.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 2.36%   |
| Intel HD Graphics 620                                                                    | 31        | 2.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 2.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 20        | 1.52%   |
| Intel HD Graphics 530                                                                    | 15        | 1.14%   |
| Nvidia GP108M [GeForce MX250]                                                            | 14        | 1.07%   |
| AMD Lucienne                                                                             | 14        | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 0.99%   |
| Intel HD Graphics 630                                                                    | 12        | 0.91%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 12        | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.76%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 10        | 0.76%   |
| Nvidia GM108M [GeForce 840M]                                                             | 9         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 0.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 0.69%   |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.69%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 9         | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 0.69%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 8         | 0.61%   |
| Intel HD Graphics 500                                                                    | 8         | 0.61%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 0.61%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 482       | 46.84%  |
| 1 x AMD        | 200       | 19.44%  |
| Intel + Nvidia | 194       | 18.85%  |
| 1 x Nvidia     | 71        | 6.9%    |
| Intel + AMD    | 44        | 4.28%   |
| 2 x AMD        | 19        | 1.85%   |
| AMD + Nvidia   | 16        | 1.55%   |
| 2 x Intel      | 2         | 0.19%   |
| 1 x SiS        | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 889       | 85.81%  |
| Proprietary | 126       | 12.16%  |
| Unknown     | 21        | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 649       | 61.52%  |
| 0.01-0.5   | 129       | 12.23%  |
| 1.01-2.0   | 118       | 11.18%  |
| 0.51-1.0   | 70        | 6.64%   |
| 3.01-4.0   | 62        | 5.88%   |
| 7.01-8.0   | 12        | 1.14%   |
| 5.01-6.0   | 12        | 1.14%   |
| 2.01-3.0   | 2         | 0.19%   |
| 8.01-16.0  | 1         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 245       | 20.57%  |
| LG Display              | 172       | 14.44%  |
| Chimei Innolux          | 132       | 11.08%  |
| Samsung Electronics     | 126       | 10.58%  |
| BOE                     | 125       | 10.5%   |
| Lenovo                  | 38        | 3.19%   |
| Dell                    | 36        | 3.02%   |
| Sharp                   | 35        | 2.94%   |
| Apple                   | 35        | 2.94%   |
| Hewlett-Packard         | 22        | 1.85%   |
| Goldstar                | 22        | 1.85%   |
| Chi Mei Optoelectronics | 20        | 1.68%   |
| Acer                    | 14        | 1.18%   |
| InfoVision              | 13        | 1.09%   |
| AOC                     | 13        | 1.09%   |
| PANDA                   | 11        | 0.92%   |
| Valve                   | 10        | 0.84%   |
| LG Philips              | 9         | 0.76%   |
| Philips                 | 8         | 0.67%   |
| Iiyama                  | 8         | 0.67%   |
| CSO                     | 8         | 0.67%   |
| BenQ                    | 8         | 0.67%   |
| Ancor Communications    | 7         | 0.59%   |
| HannStar                | 5         | 0.42%   |
| Eizo                    | 5         | 0.42%   |
| CPT                     | 5         | 0.42%   |
| Sony                    | 4         | 0.34%   |
| Panasonic               | 4         | 0.34%   |
| Gericom                 | 4         | 0.34%   |
| Toshiba                 | 3         | 0.25%   |
| TMX                     | 3         | 0.25%   |
| LGD                     | 3         | 0.25%   |
| Analogix                | 3         | 0.25%   |
| ViewSonic               | 2         | 0.17%   |
| Unknown                 | 2         | 0.17%   |
| Medion Akoya            | 2         | 0.17%   |
| Fujitsu Siemens         | 2         | 0.17%   |
| CMN                     | 2         | 0.17%   |
| CHD                     | 2         | 0.17%   |
| ASUSTek Computer        | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 10        | 0.82%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 9         | 0.74%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 9         | 0.74%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 9         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 9         | 0.74%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 8         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 8         | 0.66%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                | 8         | 0.66%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 7         | 0.58%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch       | 7         | 0.58%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 7         | 0.58%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch              | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch     | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 6         | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 5         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch     | 5         | 0.41%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                | 5         | 0.41%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                | 5         | 0.41%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch       | 5         | 0.41%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 5         | 0.41%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 5         | 0.41%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch    | 4         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 4         | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 4         | 0.33%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch         | 4         | 0.33%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch          | 4         | 0.33%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch          | 4         | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 4         | 0.33%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch              | 4         | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch      | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch      | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1362 1366x768 293x164mm 13.2-inch      | 4         | 0.33%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 4         | 0.33%   |
| BOE LCD Monitor BOE065D 1920x1080 344x194mm 15.5-inch                | 4         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 519       | 46.3%   |
| 1366x768 (WXGA)    | 202       | 18.02%  |
| 1600x900 (HD+)     | 87        | 7.76%   |
| 3840x2160 (4K)     | 55        | 4.91%   |
| 2560x1440 (QHD)    | 47        | 4.19%   |
| 1280x800 (WXGA)    | 46        | 4.1%    |
| 1920x1200 (WUXGA)  | 27        | 2.41%   |
| 1440x900 (WXGA+)   | 26        | 2.32%   |
| 2880x1800          | 13        | 1.16%   |
| 1680x1050 (WSXGA+) | 13        | 1.16%   |
| 800x1280           | 11        | 0.98%   |
| 3440x1440          | 11        | 0.98%   |
| 3840x2400          | 8         | 0.71%   |
| 2560x1600          | 8         | 0.71%   |
| 1280x1024 (SXGA)   | 6         | 0.54%   |
| 1024x600           | 6         | 0.54%   |
| 2560x1080          | 5         | 0.45%   |
| Unknown            | 5         | 0.45%   |
| 3840x1080          | 4         | 0.36%   |
| 3200x1800 (QHD+)   | 4         | 0.36%   |
| 2288x1287          | 3         | 0.27%   |
| 2160x1440          | 3         | 0.27%   |
| 1920x540           | 3         | 0.27%   |
| 3456x2160          | 2         | 0.18%   |
| 1600x1200          | 2         | 0.18%   |
| 3000x2000          | 1         | 0.09%   |
| 2256x1504          | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1360x768           | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 400       | 33.59%  |
| 14      | 157       | 13.18%  |
| 13      | 155       | 13.01%  |
| 17      | 124       | 10.41%  |
| 27      | 59        | 4.95%   |
| 12      | 43        | 3.61%   |
| 24      | 41        | 3.44%   |
| 23      | 29        | 2.43%   |
| 21      | 22        | 1.85%   |
| 11      | 18        | 1.51%   |
| Unknown | 18        | 1.51%   |
| 16      | 17        | 1.43%   |
| 34      | 16        | 1.34%   |
| 31      | 11        | 0.92%   |
| 10      | 9         | 0.76%   |
| 7       | 9         | 0.76%   |
| 22      | 8         | 0.67%   |
| 54      | 7         | 0.59%   |
| 25      | 7         | 0.59%   |
| 19      | 7         | 0.59%   |
| 18      | 7         | 0.59%   |
| 84      | 4         | 0.34%   |
| 20      | 3         | 0.25%   |
| 3       | 3         | 0.25%   |
| 142     | 2         | 0.17%   |
| 40      | 2         | 0.17%   |
| 39      | 2         | 0.17%   |
| 32      | 2         | 0.17%   |
| 28      | 2         | 0.17%   |
| 85      | 1         | 0.08%   |
| 72      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 628       | 53.27%  |
| 201-300        | 153       | 12.98%  |
| 351-400        | 146       | 12.38%  |
| 501-600        | 115       | 9.75%   |
| 401-500        | 40        | 3.39%   |
| 601-700        | 27        | 2.29%   |
| 701-800        | 18        | 1.53%   |
| Unknown        | 18        | 1.53%   |
| 1001-1500      | 11        | 0.93%   |
| 1-100          | 11        | 0.93%   |
| 1501-2000      | 6         | 0.51%   |
| 801-900        | 4         | 0.34%   |
| More than 2000 | 2         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 844       | 80.38%  |
| 16/10   | 144       | 13.71%  |
| 21/9    | 17        | 1.62%   |
| Unknown | 14        | 1.33%   |
| 0.67    | 9         | 0.86%   |
| 3/2     | 7         | 0.67%   |
| 5/4     | 6         | 0.57%   |
| 6/5     | 4         | 0.38%   |
| 32/9    | 2         | 0.19%   |
| 1.00    | 2         | 0.19%   |
| 4/3     | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 403       | 34.07%  |
| 81-90          | 246       | 20.79%  |
| 121-130        | 108       | 9.13%   |
| 201-250        | 69        | 5.83%   |
| 71-80          | 65        | 5.49%   |
| 301-350        | 59        | 4.99%   |
| 61-70          | 43        | 3.63%   |
| 351-500        | 30        | 2.54%   |
| 251-300        | 25        | 2.11%   |
| 151-200        | 20        | 1.69%   |
| 131-140        | 19        | 1.61%   |
| More than 1000 | 18        | 1.52%   |
| 51-60          | 18        | 1.52%   |
| Unknown        | 18        | 1.52%   |
| 1-40           | 11        | 0.93%   |
| 41-50          | 9         | 0.76%   |
| 111-120        | 9         | 0.76%   |
| 141-150        | 6         | 0.51%   |
| 501-1000       | 5         | 0.42%   |
| 91-100         | 2         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 506       | 43.32%  |
| 101-120       | 287       | 24.57%  |
| 51-100        | 193       | 16.52%  |
| 161-240       | 109       | 9.33%   |
| More than 240 | 44        | 3.77%   |
| Unknown       | 18        | 1.54%   |
| 1-50          | 11        | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 819       | 77.56%  |
| 2     | 174       | 16.48%  |
| 3     | 30        | 2.84%   |
| 0     | 28        | 2.65%   |
| 4     | 5         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 629       | 37.91%  |
| Realtek Semiconductor             | 482       | 29.05%  |
| Qualcomm Atheros                  | 188       | 11.33%  |
| Broadcom                          | 96        | 5.79%   |
| MediaTek                          | 20        | 1.21%   |
| Sierra Wireless                   | 18        | 1.08%   |
| Broadcom Limited                  | 18        | 1.08%   |
| Ralink                            | 16        | 0.96%   |
| Ericsson Business Mobile Networks | 16        | 0.96%   |
| Dell                              | 16        | 0.96%   |
| Marvell Technology Group          | 15        | 0.9%    |
| Lenovo                            | 13        | 0.78%   |
| Hewlett-Packard                   | 10        | 0.6%    |
| ASIX Electronics                  | 10        | 0.6%    |
| Huawei Technologies               | 9         | 0.54%   |
| Fibocom                           | 9         | 0.54%   |
| DisplayLink                       | 9         | 0.54%   |
| Nvidia                            | 7         | 0.42%   |
| TP-Link                           | 6         | 0.36%   |
| Samsung Electronics               | 6         | 0.36%   |
| Qualcomm                          | 6         | 0.36%   |
| NetGear                           | 6         | 0.36%   |
| Edimax Technology                 | 6         | 0.36%   |
| Google                            | 5         | 0.3%    |
| ZyXEL Communications              | 4         | 0.24%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.24%   |
| JMicron Technology                | 4         | 0.24%   |
| Ralink Technology                 | 3         | 0.18%   |
| ASUSTek Computer                  | 3         | 0.18%   |
| Xiaomi                            | 2         | 0.12%   |
| Qualcomm Atheros Communications   | 2         | 0.12%   |
| Motorola PCS                      | 2         | 0.12%   |
| Linksys                           | 2         | 0.12%   |
| D-Link System                     | 2         | 0.12%   |
| Apple                             | 2         | 0.12%   |
| ZyDAS                             | 1         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| Sitecom Europe                    | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.06%   |
| Research In Motion                | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 312       | 15.23%  |
| Intel Wi-Fi 6 AX200                                               | 79        | 3.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 2.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 2.73%   |
| Intel Wireless 8265 / 8275                                        | 54        | 2.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 2.39%   |
| Intel Wireless 7265                                               | 39        | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 38        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 37        | 1.81%   |
| Intel Wireless 8260                                               | 35        | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 1.46%   |
| Intel Wireless 7260                                               | 28        | 1.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 27        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 24        | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 22        | 1.07%   |
| Intel Centrino Ultimate-N 6300                                    | 21        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 1.03%   |
| Intel Wireless 3165                                               | 20        | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 19        | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 0.93%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 17        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 0.78%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 0.73%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 0.73%   |
| Intel WiFi Link 5100                                              | 14        | 0.68%   |
| Intel Wireless-AC 9260                                            | 13        | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 13        | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 12        | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 0.54%   |
| Intel Wireless 3160                                               | 11        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 603       | 54.72%  |
| Qualcomm Atheros                  | 155       | 14.07%  |
| Realtek Semiconductor             | 140       | 12.7%   |
| Broadcom                          | 76        | 6.9%    |
| MediaTek                          | 19        | 1.72%   |
| Sierra Wireless                   | 18        | 1.63%   |
| Ralink                            | 16        | 1.45%   |
| Dell                              | 12        | 1.09%   |
| Fibocom                           | 9         | 0.82%   |
| Broadcom Limited                  | 9         | 0.82%   |
| TP-Link                           | 6         | 0.54%   |
| Edimax Technology                 | 6         | 0.54%   |
| Qualcomm                          | 5         | 0.45%   |
| NetGear                           | 5         | 0.45%   |
| ZyXEL Communications              | 4         | 0.36%   |
| Ericsson Business Mobile Networks | 4         | 0.36%   |
| Ralink Technology                 | 3         | 0.27%   |
| ASUSTek Computer                  | 3         | 0.27%   |
| Qualcomm Atheros Communications   | 2         | 0.18%   |
| D-Link System                     | 2         | 0.18%   |
| ZyDAS                             | 1         | 0.09%   |
| Sitecom Europe                    | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| Hewlett-Packard                   | 1         | 0.09%   |
| D-Link                            | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 79        | 7.16%   |
| Intel Wireless 8265 / 8275                                              | 54        | 4.9%    |
| Intel Wireless 7265                                                     | 39        | 3.54%   |
| Intel Wi-Fi 6 AX201                                                     | 38        | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 37        | 3.35%   |
| Intel Wireless 8260                                                     | 35        | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 30        | 2.72%   |
| Intel Wireless 7260                                                     | 28        | 2.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 27        | 2.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 2.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 1.99%   |
| Intel Centrino Ultimate-N 6300                                          | 21        | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 21        | 1.9%    |
| Intel Wireless 3165                                                     | 20        | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 15        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                           | 15        | 1.36%   |
| Intel WiFi Link 5100                                                    | 14        | 1.27%   |
| Intel Wireless-AC 9260                                                  | 13        | 1.18%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 1.18%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 11        | 1%      |
| Intel Wireless 3160                                                     | 11        | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 11        | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 11        | 1%      |
| Sierra Wireless EM7455                                                  | 10        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 10        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 10        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 9         | 0.82%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 9         | 0.82%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 423       | 47%     |
| Intel                         | 282       | 31.33%  |
| Qualcomm Atheros              | 57        | 6.33%   |
| Broadcom                      | 36        | 4%      |
| Marvell Technology Group      | 15        | 1.67%   |
| Lenovo                        | 13        | 1.44%   |
| ASIX Electronics              | 10        | 1.11%   |
| DisplayLink                   | 9         | 1%      |
| Broadcom Limited              | 9         | 1%      |
| Nvidia                        | 7         | 0.78%   |
| Samsung Electronics           | 6         | 0.67%   |
| Google                        | 5         | 0.56%   |
| OnePlus Technology (Shenzhen) | 4         | 0.44%   |
| JMicron Technology            | 4         | 0.44%   |
| Huawei Technologies           | 4         | 0.44%   |
| Xiaomi                        | 2         | 0.22%   |
| Motorola PCS                  | 2         | 0.22%   |
| Hewlett-Packard               | 2         | 0.22%   |
| Apple                         | 2         | 0.22%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.11%   |
| Research In Motion            | 1         | 0.11%   |
| Qualcomm                      | 1         | 0.11%   |
| NetGear                       | 1         | 0.11%   |
| MediaTek                      | 1         | 0.11%   |
| Linksys                       | 1         | 0.11%   |
| Cypress Semiconductor         | 1         | 0.11%   |
| Attansic Technology           | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 312       | 34.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 58        | 6.37%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 6.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 49        | 5.38%   |
| Intel Ethernet Connection I219-LM                                 | 19        | 2.09%   |
| Intel Ethernet Connection (6) I219-V                              | 18        | 1.98%   |
| Intel 82577LM Gigabit Network Connection                          | 17        | 1.87%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 1.76%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 1.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 15        | 1.65%   |
| Intel Ethernet Connection (4) I219-V                              | 15        | 1.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.1%    |
| Intel Ethernet Connection I219-V                                  | 8         | 0.88%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 8         | 0.88%   |
| Lenovo USB-C Dock Ethernet                                        | 7         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 6         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.66%   |
| Intel Ethernet Connection (13) I219-LM                            | 6         | 0.66%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 6         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.44%   |
| OnePlus (Shenzhen) OnePlus                                        | 4         | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.44%   |
| DisplayLink Dell Universal Dock D6000                             | 4         | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 0.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 4         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1015      | 53.62%  |
| Ethernet | 845       | 44.64%  |
| Modem    | 31        | 1.64%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 842       | 77.6%   |
| Ethernet | 243       | 22.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 759       | 73.98%  |
| 1     | 236       | 23%     |
| 3     | 17        | 1.66%   |
| 0     | 14        | 1.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 889       | 85.15%  |
| Yes  | 155       | 14.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 444       | 54.41%  |
| Realtek Semiconductor           | 81        | 9.93%   |
| Qualcomm Atheros Communications | 51        | 6.25%   |
| Broadcom                        | 49        | 6%      |
| IMC Networks                    | 36        | 4.41%   |
| Lite-On Technology              | 32        | 3.92%   |
| Foxconn / Hon Hai               | 26        | 3.19%   |
| Apple                           | 24        | 2.94%   |
| Hewlett-Packard                 | 15        | 1.84%   |
| Dell                            | 14        | 1.72%   |
| Cambridge Silicon Radio         | 10        | 1.23%   |
| Toshiba                         | 9         | 1.1%    |
| Ralink                          | 5         | 0.61%   |
| Foxconn International           | 5         | 0.61%   |
| MediaTek                        | 3         | 0.37%   |
| USI                             | 2         | 0.25%   |
| Realtek                         | 2         | 0.25%   |
| ASUSTek Computer                | 2         | 0.25%   |
| Alps Electric                   | 2         | 0.25%   |
| i.Tech Dynamic Limited          | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Belkin Components               | 1         | 0.12%   |
| Askey Computer                  | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 176       | 21.57%  |
| Intel AX201 Bluetooth                               | 82        | 10.05%  |
| Intel AX200 Bluetooth                               | 76        | 9.31%   |
| Realtek Bluetooth Radio                             | 58        | 7.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 43        | 5.27%   |
| Intel Bluetooth Device                              | 23        | 2.82%   |
| IMC Networks Bluetooth Radio                        | 18        | 2.21%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 2.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.84%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 1.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.47%   |
| Foxconn / Hon Hai Bluetooth Device                  | 12        | 1.47%   |
| Apple Bluetooth Host Controller                     | 11        | 1.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 1.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 1.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 1.1%    |
| Intel AX210 Bluetooth                               | 8         | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.86%   |
| IMC Networks Bluetooth Device                       | 7         | 0.86%   |
| Apple Bluetooth USB Host Controller                 | 7         | 0.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.74%   |
| Lite-On Bluetooth Device                            | 6         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.74%   |
| IMC Networks Wireless_Device                        | 6         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.74%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.74%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.61%   |
| Lite-On Wireless_Device                             | 5         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 4         | 0.49%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.49%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 0.49%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.49%   |
| Apple Bluetooth HCI                                 | 4         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 803       | 61.91%  |
| AMD                              | 232       | 17.89%  |
| Nvidia                           | 135       | 10.41%  |
| Lenovo                           | 14        | 1.08%   |
| C-Media Electronics              | 14        | 1.08%   |
| Logitech                         | 11        | 0.85%   |
| GN Netcom                        | 11        | 0.85%   |
| Realtek Semiconductor            | 8         | 0.62%   |
| Hewlett-Packard                  | 8         | 0.62%   |
| Apple                            | 8         | 0.62%   |
| Texas Instruments                | 6         | 0.46%   |
| Plantronics                      | 4         | 0.31%   |
| Creative Technology              | 4         | 0.31%   |
| SteelSeries ApS                  | 3         | 0.23%   |
| Sony                             | 3         | 0.23%   |
| Sennheiser Communications        | 3         | 0.23%   |
| Focusrite-Novation               | 3         | 0.23%   |
| Yamaha                           | 2         | 0.15%   |
| RODE Microphones                 | 2         | 0.15%   |
| Kingston Technology              | 2         | 0.15%   |
| ZOOM                             | 1         | 0.08%   |
| XMOS                             | 1         | 0.08%   |
| Valve Software                   | 1         | 0.08%   |
| Tenx Technology                  | 1         | 0.08%   |
| Silicon Motion                   | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Samsung Electronics              | 1         | 0.08%   |
| Roland                           | 1         | 0.08%   |
| No brand                         | 1         | 0.08%   |
| Microsoft                        | 1         | 0.08%   |
| Mackie Designs                   | 1         | 0.08%   |
| M-Audio                          | 1         | 0.08%   |
| JMTek                            | 1         | 0.08%   |
| GYROCOM C&C                      | 1         | 0.08%   |
| Generalplus Technology           | 1         | 0.08%   |
| FiiO Electronics Technology      | 1         | 0.08%   |
| DSEA A/S                         | 1         | 0.08%   |
| Bose                             | 1         | 0.08%   |
| Blue Microphones                 | 1         | 0.08%   |
| BEHRINGER International          | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 126       | 8.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 122       | 7.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 90        | 5.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 82        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 78        | 4.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 49        | 3.12%   |
| Intel Broadwell-U Audio Controller                                                                | 42        | 2.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 41        | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 41        | 2.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 2.61%   |
| Intel 8 Series HD Audio Controller                                                                | 41        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 39        | 2.48%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 2.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 32        | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 31        | 1.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 30        | 1.91%   |
| AMD FCH Azalia Controller                                                                         | 29        | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                                          | 23        | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 17        | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.08%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 17        | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 11        | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 0.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 11        | 0.7%    |
| Realtek Semiconductor USB Audio                                                                   | 8         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 0.51%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 208       | 30.54%  |
| SK hynix              | 164       | 24.08%  |
| Micron Technology     | 98        | 14.39%  |
| Kingston              | 51        | 7.49%   |
| Unknown               | 43        | 6.31%   |
| Crucial               | 36        | 5.29%   |
| Ramaxel Technology    | 17        | 2.5%    |
| Elpida                | 13        | 1.91%   |
| Corsair               | 12        | 1.76%   |
| Unknown (ABCD)        | 8         | 1.17%   |
| Nanya Technology      | 6         | 0.88%   |
| G.Skill               | 6         | 0.88%   |
| A-DATA Technology     | 5         | 0.73%   |
| Transcend             | 2         | 0.29%   |
| Silicon Power         | 2         | 0.29%   |
| GOODRAM               | 2         | 0.29%   |
| Vaseky                | 1         | 0.15%   |
| Smart                 | 1         | 0.15%   |
| Kingmax Semiconductor | 1         | 0.15%   |
| CSX                   | 1         | 0.15%   |
| ChangXin Memory       | 1         | 0.15%   |
| Avant                 | 1         | 0.15%   |
| ASint Technology      | 1         | 0.15%   |
| Unknown               | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 19        | 2.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.25%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 9         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 1.11%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.11%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 7         | 0.97%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.97%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.97%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.97%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 7         | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.84%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.84%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.84%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.7%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.7%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 5         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.7%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.7%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.56%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.56%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 4         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.56%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2667MT/s            | 4         | 0.56%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 4         | 0.56%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.56%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.56%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 4         | 0.56%   |
| Corsair RAM CMSX8GX3M1A1600C10 8GB SODIMM DDR3 1600MT/s          | 4         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 283       | 49.48%  |
| DDR3    | 183       | 31.99%  |
| LPDDR4  | 32        | 5.59%   |
| DDR2    | 30        | 5.24%   |
| LPDDR3  | 17        | 2.97%   |
| SDRAM   | 12        | 2.1%    |
| LPDDR5  | 9         | 1.57%   |
| DDR5    | 5         | 0.87%   |
| Unknown | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 505       | 87.37%  |
| Row Of Chips | 63        | 10.9%   |
| Chip         | 8         | 1.38%   |
| DIMM         | 2         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 275       | 43.93%  |
| 4096  | 137       | 21.88%  |
| 16384 | 111       | 17.73%  |
| 2048  | 68        | 10.86%  |
| 32768 | 21        | 3.35%   |
| 1024  | 14        | 2.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 133       | 21.63%  |
| 1600    | 126       | 20.49%  |
| 2667    | 125       | 20.33%  |
| 2400    | 42        | 6.83%   |
| 2133    | 30        | 4.88%   |
| 1334    | 24        | 3.9%    |
| 1333    | 24        | 3.9%    |
| 667     | 17        | 2.76%   |
| 4267    | 12        | 1.95%   |
| 800     | 9         | 1.46%   |
| 6400    | 8         | 1.3%    |
| Unknown | 8         | 1.3%    |
| 4800    | 7         | 1.14%   |
| 4199    | 7         | 1.14%   |
| 1067    | 7         | 1.14%   |
| 1867    | 6         | 0.98%   |
| 3266    | 5         | 0.81%   |
| 2048    | 5         | 0.81%   |
| 8400    | 4         | 0.65%   |
| 4266    | 4         | 0.65%   |
| 5600    | 2         | 0.33%   |
| 3733    | 2         | 0.33%   |
| 975     | 2         | 0.33%   |
| 533     | 2         | 0.33%   |
| 333     | 2         | 0.33%   |
| 7400    | 1         | 0.16%   |
| 1066    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 54.55%  |
| Samsung Electronics | 2         | 18.18%  |
| Canon               | 2         | 18.18%  |
| Seiko Epson         | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-235 Series  | 1         | 9.09%   |
| Samsung SCX-4300 Series    | 1         | 9.09%   |
| Samsung C48x Series        | 1         | 9.09%   |
| HP LaserJet P1102          | 1         | 9.09%   |
| HP LaserJet 1200           | 1         | 9.09%   |
| HP LaserJet 1022           | 1         | 9.09%   |
| HP ENVY Pro 6400 series    | 1         | 9.09%   |
| HP Deskjet 3520 series     | 1         | 9.09%   |
| HP DeskJet 2600 series     | 1         | 9.09%   |
| Canon PIXMA iX6850 Printer | 1         | 9.09%   |
| Canon MG2100 series        | 1         | 9.09%   |

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
| Chicony Electronics                    | 266       | 29.62%  |
| IMC Networks                           | 97        | 10.8%   |
| Bison Electronics                      | 76        | 8.46%   |
| Microdia                               | 55        | 6.12%   |
| Sunplus Innovation Technology          | 47        | 5.23%   |
| Realtek Semiconductor                  | 47        | 5.23%   |
| Quanta                                 | 45        | 5.01%   |
| Lite-On Technology                     | 32        | 3.56%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 3.45%   |
| Suyin                                  | 30        | 3.34%   |
| Apple                                  | 22        | 2.45%   |
| Syntek                                 | 21        | 2.34%   |
| Acer                                   | 19        | 2.12%   |
| Luxvisions Innotech Limited            | 16        | 1.78%   |
| Alcor Micro                            | 13        | 1.45%   |
| Logitech                               | 11        | 1.22%   |
| Lenovo                                 | 9         | 1%      |
| Ricoh                                  | 7         | 0.78%   |
| Primax Electronics                     | 6         | 0.67%   |
| Samsung Electronics                    | 5         | 0.56%   |
| Z-Star Microelectronics                | 4         | 0.45%   |
| OmniVision Technologies                | 4         | 0.45%   |
| icSpring                               | 4         | 0.45%   |
| Silicon Motion                         | 3         | 0.33%   |
| Microsoft                              | 3         | 0.33%   |
| DigiTech                               | 3         | 0.33%   |
| SunplusIT                              | 2         | 0.22%   |
| Sony                                   | 2         | 0.22%   |
| SHENZHEN AONI ELECTRONIC               | 2         | 0.22%   |
| Generalplus Technology                 | 2         | 0.22%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.22%   |
| Valve Software                         | 1         | 0.11%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Sonix Technology                       | 1         | 0.11%   |
| ShineTech                              | 1         | 0.11%   |
| Nebraska Furniture Mart                | 1         | 0.11%   |
| KYE Systems (Mouse Systems)            | 1         | 0.11%   |
| Jieli Technology                       | 1         | 0.11%   |
| Goertek Electronics                    | 1         | 0.11%   |
| Genesys Logic                          | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 67        | 7.44%   |
| IMC Networks Integrated Camera           | 47        | 5.22%   |
| Microdia Integrated_Webcam_HD            | 27        | 3%      |
| Bison Integrated Camera                  | 24        | 2.67%   |
| Chicony HD WebCam                        | 22        | 2.44%   |
| Chicony HP HD Camera                     | 18        | 2%      |
| Quanta HD User Facing                    | 15        | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam        | 14        | 1.56%   |
| Sunplus Integrated_Webcam_HD             | 13        | 1.44%   |
| Lite-On Integrated Camera                | 13        | 1.44%   |
| Realtek Integrated_Webcam_HD             | 12        | 1.33%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 12        | 1.33%   |
| Quanta HP HD Camera                      | 11        | 1.22%   |
| Chicony TOSHIBA Web Camera - HD          | 11        | 1.22%   |
| Syntek Integrated Camera                 | 10        | 1.11%   |
| Lite-On HP HD Camera                     | 10        | 1.11%   |
| Chicony HP HD Webcam                     | 10        | 1.11%   |
| Sunplus HD WebCam                        | 9         | 1%      |
| Realtek USB2.0 HD UVC WebCam             | 9         | 1%      |
| Chicony VGA Webcam                       | 9         | 1%      |
| Chicony USB2.0 HD UVC WebCam             | 9         | 1%      |
| Bison HD Webcam                          | 9         | 1%      |
| Bison Lenovo EasyCamera                  | 8         | 0.89%   |
| Apple FaceTime HD Camera                 | 8         | 0.89%   |
| Acer Integrated Camera                   | 8         | 0.89%   |
| Realtek HD WebCam                        | 7         | 0.78%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 0.78%   |
| Chicony Integrated HP HD Webcam          | 7         | 0.78%   |
| Chicony Integrated Camera (1280x720@30)  | 7         | 0.78%   |
| Chicony HP Truevision HD camera          | 7         | 0.78%   |
| Chicony HD User Facing                   | 7         | 0.78%   |
| Bison SunplusIT Integrated Camera        | 7         | 0.78%   |
| Syntek Lenovo EasyCamera                 | 6         | 0.67%   |
| Luxvisions Innotech Limited HP HD Camera | 6         | 0.67%   |
| Lenovo Integrated Webcam [R5U877]        | 6         | 0.67%   |
| Chicony USB2.0 Camera                    | 6         | 0.67%   |
| Chicony FJ Camera                        | 6         | 0.67%   |
| Bison Integrated RGB Camera              | 6         | 0.67%   |
| Suyin Asus Integrated Webcam             | 5         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 106       | 37.72%  |
| Synaptics                  | 100       | 35.59%  |
| Shenzhen Goodix Technology | 27        | 9.61%   |
| Upek                       | 17        | 6.05%   |
| AuthenTec                  | 16        | 5.69%   |
| Elan Microelectronics      | 7         | 2.49%   |
| LighTuning Technology      | 6         | 2.14%   |
| STMicroelectronics         | 1         | 0.36%   |
| Focal-systems.Corp         | 1         | 0.36%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 49        | 17.38%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 31        | 10.99%  |
| Shenzhen Goodix  Fingerprint Device                                        | 19        | 6.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 6.03%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 4.61%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.55%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 3.19%   |
| Validity Sensors VFS491                                                    | 9         | 3.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.48%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 2.48%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.48%   |
| AuthenTec AES2810                                                          | 7         | 2.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.77%   |
| Synaptics WBDI                                                             | 5         | 1.77%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.77%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.77%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.42%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.42%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.06%   |
| Synaptics WBDI Device                                                      | 3         | 1.06%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 1.06%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.06%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.06%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.71%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.71%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.35%   |
| Synaptics UWP WBDI                                                         | 1         | 0.35%   |
| Synaptics TouchPad                                                         | 1         | 0.35%   |
| Synaptics  WBDI                                                            | 1         | 0.35%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.35%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 74        | 51.75%  |
| Broadcom              | 41        | 28.67%  |
| Lenovo                | 11        | 7.69%   |
| Upek                  | 9         | 6.29%   |
| O2 Micro              | 5         | 3.5%    |
| SCM Microsystems      | 1         | 0.7%    |
| Realtek Semiconductor | 1         | 0.7%    |
| Advanced Card Systems | 1         | 0.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 74        | 51.75%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.89%  |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 6.29%   |
| Broadcom 58200                                                               | 7         | 4.9%    |
| Broadcom 5880                                                                | 6         | 4.2%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 2.8%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.7%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.7%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.7%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 567       | 53.34%  |
| 1     | 370       | 34.81%  |
| 2     | 92        | 8.65%   |
| 3     | 22        | 2.07%   |
| 4     | 6         | 0.56%   |
| 8     | 2         | 0.19%   |
| 6     | 2         | 0.19%   |
| 5     | 2         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 276       | 42.59%  |
| Chipcard                 | 112       | 17.28%  |
| Graphics card            | 86        | 13.27%  |
| Net/wireless             | 63        | 9.72%   |
| Multimedia controller    | 25        | 3.86%   |
| Bluetooth                | 18        | 2.78%   |
| Sound                    | 15        | 2.31%   |
| Camera                   | 14        | 2.16%   |
| Communication controller | 10        | 1.54%   |
| Card reader              | 8         | 1.23%   |
| Storage                  | 6         | 0.93%   |
| Net/ethernet             | 4         | 0.62%   |
| Modem                    | 4         | 0.62%   |
| Unassigned class         | 3         | 0.46%   |
| Flash memory             | 2         | 0.31%   |
| Network                  | 1         | 0.15%   |
| Firewire controller      | 1         | 0.15%   |

