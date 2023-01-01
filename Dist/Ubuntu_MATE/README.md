Ubuntu MATE - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE/Notebook/README.md).

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

Total: 1819

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | Notebook    | [43923d1e98](https://linux-hardware.org/?probe=43923d1e98) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [8540c1c554](https://linux-hardware.org/?probe=8540c1c554) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [b4c615f28c](https://linux-hardware.org/?probe=b4c615f28c) | Dec 30, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a323cc954e](https://linux-hardware.org/?probe=a323cc954e) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [531e60d101](https://linux-hardware.org/?probe=531e60d101) | Dec 30, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [c286883155](https://linux-hardware.org/?probe=c286883155) | Dec 29, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4dab06b05f](https://linux-hardware.org/?probe=4dab06b05f) | Dec 29, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [4a26556b6b](https://linux-hardware.org/?probe=4a26556b6b) | Dec 29, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7ac222385a](https://linux-hardware.org/?probe=7ac222385a) | Dec 28, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [faf2c0e5d7](https://linux-hardware.org/?probe=faf2c0e5d7) | Dec 28, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [870deddfbe](https://linux-hardware.org/?probe=870deddfbe) | Dec 27, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4283e3bb1e](https://linux-hardware.org/?probe=4283e3bb1e) | Dec 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [db1c25cde3](https://linux-hardware.org/?probe=db1c25cde3) | Dec 27, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [0a5cad12c2](https://linux-hardware.org/?probe=0a5cad12c2) | Dec 26, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [037841f71c](https://linux-hardware.org/?probe=037841f71c) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f113c7d475](https://linux-hardware.org/?probe=f113c7d475) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [cc49bb2ef6](https://linux-hardware.org/?probe=cc49bb2ef6) | Dec 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [838eb1f6fa](https://linux-hardware.org/?probe=838eb1f6fa) | Dec 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2995a5ea20](https://linux-hardware.org/?probe=2995a5ea20) | Dec 24, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| Toshiba       | Satellite C50D-C            | Notebook    | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [a4447312cc](https://linux-hardware.org/?probe=a4447312cc) | Dec 23, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [cc88046606](https://linux-hardware.org/?probe=cc88046606) | Dec 22, 2022 |
| HP            | Compaq Presario CQ61        | Notebook    | [a85b255853](https://linux-hardware.org/?probe=a85b255853) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | Desktop     | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [c1d47a051f](https://linux-hardware.org/?probe=c1d47a051f) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0410be2105](https://linux-hardware.org/?probe=0410be2105) | Dec 22, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d1dc69cc49](https://linux-hardware.org/?probe=d1dc69cc49) | Dec 22, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [2ad8b45619](https://linux-hardware.org/?probe=2ad8b45619) | Dec 21, 2022 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0e53e0be48](https://linux-hardware.org/?probe=0e53e0be48) | Dec 21, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ae1cc3b6c0](https://linux-hardware.org/?probe=ae1cc3b6c0) | Dec 21, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2f3edb2954](https://linux-hardware.org/?probe=2f3edb2954) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5542739f1e](https://linux-hardware.org/?probe=5542739f1e) | Dec 20, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [0d03f7978b](https://linux-hardware.org/?probe=0d03f7978b) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | Notebook    | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [21a91196b1](https://linux-hardware.org/?probe=21a91196b1) | Dec 19, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [af260af715](https://linux-hardware.org/?probe=af260af715) | Dec 19, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [ac787dc7dc](https://linux-hardware.org/?probe=ac787dc7dc) | Dec 17, 2022 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [34ac0b3211](https://linux-hardware.org/?probe=34ac0b3211) | Dec 17, 2022 |
| Lenovo        | ThinkPad T430 2347G5U       | Notebook    | [e47e7c18c9](https://linux-hardware.org/?probe=e47e7c18c9) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e3ac894e13](https://linux-hardware.org/?probe=e3ac894e13) | Dec 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [987d96714a](https://linux-hardware.org/?probe=987d96714a) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [ac15fdcc8b](https://linux-hardware.org/?probe=ac15fdcc8b) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7f2f68d436](https://linux-hardware.org/?probe=7f2f68d436) | Dec 16, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [a69be3386b](https://linux-hardware.org/?probe=a69be3386b) | Dec 16, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [8caca0975b](https://linux-hardware.org/?probe=8caca0975b) | Dec 15, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2c5167b360](https://linux-hardware.org/?probe=2c5167b360) | Dec 14, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [ca7464eb3f](https://linux-hardware.org/?probe=ca7464eb3f) | Dec 14, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Biostar       | A320MH                      | Desktop     | [31cc96d1d3](https://linux-hardware.org/?probe=31cc96d1d3) | Dec 11, 2022 |
| MSI           | H81M-E34                    | Desktop     | [a9cc317647](https://linux-hardware.org/?probe=a9cc317647) | Dec 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b7a944c773](https://linux-hardware.org/?probe=b7a944c773) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [118d4ebca0](https://linux-hardware.org/?probe=118d4ebca0) | Dec 11, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c57f5be505](https://linux-hardware.org/?probe=c57f5be505) | Dec 10, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [7a6c67f095](https://linux-hardware.org/?probe=7a6c67f095) | Dec 09, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [345eb47090](https://linux-hardware.org/?probe=345eb47090) | Dec 09, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [1d97601be2](https://linux-hardware.org/?probe=1d97601be2) | Dec 08, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4943e0aa12](https://linux-hardware.org/?probe=4943e0aa12) | Dec 08, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bb704e1b90](https://linux-hardware.org/?probe=bb704e1b90) | Dec 08, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [be0753651f](https://linux-hardware.org/?probe=be0753651f) | Dec 07, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [3caa213ecf](https://linux-hardware.org/?probe=3caa213ecf) | Dec 04, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [c41ea027f7](https://linux-hardware.org/?probe=c41ea027f7) | Dec 04, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| Intel         | H61                         | Desktop     | [4050e46b94](https://linux-hardware.org/?probe=4050e46b94) | Dec 03, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bd06d3a448](https://linux-hardware.org/?probe=bd06d3a448) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e61b6313fa](https://linux-hardware.org/?probe=e61b6313fa) | Dec 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [9964cb6fe2](https://linux-hardware.org/?probe=9964cb6fe2) | Nov 30, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [c9e94d483e](https://linux-hardware.org/?probe=c9e94d483e) | Nov 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [d53007b0b3](https://linux-hardware.org/?probe=d53007b0b3) | Nov 30, 2022 |
| Acer          | TravelMate P614-51T-G2      | Notebook    | [37e14fc1c1](https://linux-hardware.org/?probe=37e14fc1c1) | Nov 30, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Getac         | S410                        | Notebook    | [3df44aa3af](https://linux-hardware.org/?probe=3df44aa3af) | Nov 26, 2022 |
| HP            | 3397                        | Desktop     | [0605f9214a](https://linux-hardware.org/?probe=0605f9214a) | Nov 25, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [05d0bf9d8d](https://linux-hardware.org/?probe=05d0bf9d8d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9e22e08aa1](https://linux-hardware.org/?probe=9e22e08aa1) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [cf30d2df93](https://linux-hardware.org/?probe=cf30d2df93) | Nov 24, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [bc690a128e](https://linux-hardware.org/?probe=bc690a128e) | Nov 23, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ef9a6b217c](https://linux-hardware.org/?probe=ef9a6b217c) | Nov 22, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [ea7c3c0cc4](https://linux-hardware.org/?probe=ea7c3c0cc4) | Nov 22, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [29b92290e8](https://linux-hardware.org/?probe=29b92290e8) | Nov 22, 2022 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [f01dec11e4](https://linux-hardware.org/?probe=f01dec11e4) | Nov 21, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [39a6819014](https://linux-hardware.org/?probe=39a6819014) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [d4b8ffffe1](https://linux-hardware.org/?probe=d4b8ffffe1) | Nov 19, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [39ecfb673f](https://linux-hardware.org/?probe=39ecfb673f) | Nov 19, 2022 |
| NEC Comput... | PC-VK27MCZDM                | Notebook    | [fce4afe996](https://linux-hardware.org/?probe=fce4afe996) | Nov 19, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [a09398bb26](https://linux-hardware.org/?probe=a09398bb26) | Nov 18, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f2e60e58dc](https://linux-hardware.org/?probe=f2e60e58dc) | Nov 17, 2022 |
| Chuwi         | X312B                       | Notebook    | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [fe43edb930](https://linux-hardware.org/?probe=fe43edb930) | Nov 16, 2022 |
| Chuwi         | X312B                       | Notebook    | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| MSI           | Z97I GAMING AC              | Desktop     | [b0a5c0251f](https://linux-hardware.org/?probe=b0a5c0251f) | Nov 15, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Dell          | Latitude D630               | Notebook    | [3a15603bd6](https://linux-hardware.org/?probe=3a15603bd6) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [3e964fdd59](https://linux-hardware.org/?probe=3e964fdd59) | Nov 12, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2dc75b76f4](https://linux-hardware.org/?probe=2dc75b76f4) | Nov 12, 2022 |
| Sony          | VGN-CR120E                  | Notebook    | [99def76c59](https://linux-hardware.org/?probe=99def76c59) | Nov 12, 2022 |
| Intel         | H61                         | Desktop     | [7d93f12ac4](https://linux-hardware.org/?probe=7d93f12ac4) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [01a339fb27](https://linux-hardware.org/?probe=01a339fb27) | Nov 11, 2022 |
| Microsoft     | Surface 2                   | Tablet      | [0cab1d9501](https://linux-hardware.org/?probe=0cab1d9501) | Nov 10, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6e773a6bf0](https://linux-hardware.org/?probe=6e773a6bf0) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [5264f28363](https://linux-hardware.org/?probe=5264f28363) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7818a033c6](https://linux-hardware.org/?probe=7818a033c6) | Nov 06, 2022 |
| Dell          | Studio 1558                 | Notebook    | [8b5cb100a8](https://linux-hardware.org/?probe=8b5cb100a8) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5ad3928a6d](https://linux-hardware.org/?probe=5ad3928a6d) | Nov 05, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [e56aa65a39](https://linux-hardware.org/?probe=e56aa65a39) | Nov 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [65c0f5965b](https://linux-hardware.org/?probe=65c0f5965b) | Nov 04, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [4b580ecb2b](https://linux-hardware.org/?probe=4b580ecb2b) | Nov 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c47ee488a5](https://linux-hardware.org/?probe=c47ee488a5) | Nov 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [34c050ed44](https://linux-hardware.org/?probe=34c050ed44) | Nov 03, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [ada830a489](https://linux-hardware.org/?probe=ada830a489) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5c0b61dfb6](https://linux-hardware.org/?probe=5c0b61dfb6) | Nov 03, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d17e8e8e36](https://linux-hardware.org/?probe=d17e8e8e36) | Nov 03, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [342c7609c9](https://linux-hardware.org/?probe=342c7609c9) | Nov 02, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [5b45883fef](https://linux-hardware.org/?probe=5b45883fef) | Nov 02, 2022 |
| MSI           | B75A-IE35                   | Desktop     | [57b74e4ca2](https://linux-hardware.org/?probe=57b74e4ca2) | Nov 01, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [6b2b490208](https://linux-hardware.org/?probe=6b2b490208) | Nov 01, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [e4af6d51f3](https://linux-hardware.org/?probe=e4af6d51f3) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b626eed02](https://linux-hardware.org/?probe=1b626eed02) | Oct 31, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [600587e66a](https://linux-hardware.org/?probe=600587e66a) | Oct 31, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [1b03bb8445](https://linux-hardware.org/?probe=1b03bb8445) | Oct 30, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [f27aa95917](https://linux-hardware.org/?probe=f27aa95917) | Oct 29, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [e1709bf653](https://linux-hardware.org/?probe=e1709bf653) | Oct 28, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [05cffb09e0](https://linux-hardware.org/?probe=05cffb09e0) | Oct 28, 2022 |
| Samsung       | 760XBE                      | Notebook    | [436b83d360](https://linux-hardware.org/?probe=436b83d360) | Oct 27, 2022 |
| Samsung       | 760XBE                      | Notebook    | [6787286004](https://linux-hardware.org/?probe=6787286004) | Oct 27, 2022 |
| Dell          | Precision 7760              | Notebook    | [b8fce270db](https://linux-hardware.org/?probe=b8fce270db) | Oct 27, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [2474ff9baf](https://linux-hardware.org/?probe=2474ff9baf) | Oct 27, 2022 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c1ba737ccc](https://linux-hardware.org/?probe=c1ba737ccc) | Oct 25, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [4785b7f6f6](https://linux-hardware.org/?probe=4785b7f6f6) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [91bf754e64](https://linux-hardware.org/?probe=91bf754e64) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [7640c7a49f](https://linux-hardware.org/?probe=7640c7a49f) | Oct 20, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [7d12ed56e5](https://linux-hardware.org/?probe=7d12ed56e5) | Oct 19, 2022 |
| HP            | ENVY Sleekbook 6            | Notebook    | [a197375e26](https://linux-hardware.org/?probe=a197375e26) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e45f7ecd7](https://linux-hardware.org/?probe=6e45f7ecd7) | Oct 15, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [d1a5c91196](https://linux-hardware.org/?probe=d1a5c91196) | Oct 14, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [b69b373cc1](https://linux-hardware.org/?probe=b69b373cc1) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [175ebd8462](https://linux-hardware.org/?probe=175ebd8462) | Oct 14, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1ba5f65f98](https://linux-hardware.org/?probe=1ba5f65f98) | Oct 10, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [41dd35ae5f](https://linux-hardware.org/?probe=41dd35ae5f) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Dell          | 0DPRF9 A00                  | All in one  | [3d0b820b58](https://linux-hardware.org/?probe=3d0b820b58) | Oct 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [1a165faedb](https://linux-hardware.org/?probe=1a165faedb) | Oct 08, 2022 |
| HP            | ENVY x360                   | Convertible | [b299af0bca](https://linux-hardware.org/?probe=b299af0bca) | Oct 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2643af430d](https://linux-hardware.org/?probe=2643af430d) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [85eb59fc6d](https://linux-hardware.org/?probe=85eb59fc6d) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [0bea9d8673](https://linux-hardware.org/?probe=0bea9d8673) | Oct 05, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | Notebook    | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [d9acb6ec9c](https://linux-hardware.org/?probe=d9acb6ec9c) | Oct 03, 2022 |
| Sony          | VGN-SZ3XP_C                 | Notebook    | [6e9671dd1a](https://linux-hardware.org/?probe=6e9671dd1a) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [ccf9b69093](https://linux-hardware.org/?probe=ccf9b69093) | Oct 02, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [7b89b5d0cf](https://linux-hardware.org/?probe=7b89b5d0cf) | Oct 02, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [ac14cbda52](https://linux-hardware.org/?probe=ac14cbda52) | Oct 02, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [92e65a376a](https://linux-hardware.org/?probe=92e65a376a) | Oct 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [cb5d0d1945](https://linux-hardware.org/?probe=cb5d0d1945) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [3af0c5cc5f](https://linux-hardware.org/?probe=3af0c5cc5f) | Oct 01, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [db15c7b708](https://linux-hardware.org/?probe=db15c7b708) | Oct 01, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [608c715bab](https://linux-hardware.org/?probe=608c715bab) | Sep 26, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [682eb02d48](https://linux-hardware.org/?probe=682eb02d48) | Sep 22, 2022 |
| Dell          | Precision 7760              | Notebook    | [f6600a1244](https://linux-hardware.org/?probe=f6600a1244) | Sep 22, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [8b1c5eb5bf](https://linux-hardware.org/?probe=8b1c5eb5bf) | Sep 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [108817dc0f](https://linux-hardware.org/?probe=108817dc0f) | Sep 21, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [1573d65d2d](https://linux-hardware.org/?probe=1573d65d2d) | Sep 18, 2022 |
| MSI           | 870-G45                     | Desktop     | [74af87b0c5](https://linux-hardware.org/?probe=74af87b0c5) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [25c30e4e54](https://linux-hardware.org/?probe=25c30e4e54) | Sep 14, 2022 |
| ASUSTek       | M2A74-AM                    | Desktop     | [24e6ffe552](https://linux-hardware.org/?probe=24e6ffe552) | Sep 14, 2022 |
| Dell          | Precision 7520              | Notebook    | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [8774a8312b](https://linux-hardware.org/?probe=8774a8312b) | Sep 13, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [1961d1c468](https://linux-hardware.org/?probe=1961d1c468) | Sep 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a86e9d966b](https://linux-hardware.org/?probe=a86e9d966b) | Sep 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [64b8914cb2](https://linux-hardware.org/?probe=64b8914cb2) | Sep 12, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | Notebook    | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| ASUSTek       | P5GZ-MX                     | Desktop     | [883739db23](https://linux-hardware.org/?probe=883739db23) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| Dell          | Precision 7760              | Notebook    | [e920197599](https://linux-hardware.org/?probe=e920197599) | Sep 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [194bb33f3d](https://linux-hardware.org/?probe=194bb33f3d) | Sep 04, 2022 |
| HP            | 2ADC                        | Desktop     | [d9e5d2b511](https://linux-hardware.org/?probe=d9e5d2b511) | Sep 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0749c352d0](https://linux-hardware.org/?probe=0749c352d0) | Sep 03, 2022 |
| HP            | 18E4                        | Desktop     | [c58c0043cb](https://linux-hardware.org/?probe=c58c0043cb) | Sep 03, 2022 |
| HP            | 3397                        | Desktop     | [5cd2349a9c](https://linux-hardware.org/?probe=5cd2349a9c) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Dell          | Latitude 5285               | Tablet      | [4e75bec854](https://linux-hardware.org/?probe=4e75bec854) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [573d359faf](https://linux-hardware.org/?probe=573d359faf) | Aug 31, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [1109650747](https://linux-hardware.org/?probe=1109650747) | Aug 31, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [2be9b66ba1](https://linux-hardware.org/?probe=2be9b66ba1) | Aug 30, 2022 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2d66cac294](https://linux-hardware.org/?probe=2d66cac294) | Aug 28, 2022 |
| HP            | Pavilion dv5                | Notebook    | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [516427e0e9](https://linux-hardware.org/?probe=516427e0e9) | Aug 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| Notebook      | NJx0MU                      | Notebook    | [7a86bdf14e](https://linux-hardware.org/?probe=7a86bdf14e) | Aug 22, 2022 |
| AZW           | GK55                        | Desktop     | [0ae52e1fdf](https://linux-hardware.org/?probe=0ae52e1fdf) | Aug 21, 2022 |
| Dell          | Latitude 7420               | Notebook    | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [76028e78e9](https://linux-hardware.org/?probe=76028e78e9) | Aug 19, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4efd818377](https://linux-hardware.org/?probe=4efd818377) | Aug 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [e8b519c4de](https://linux-hardware.org/?probe=e8b519c4de) | Aug 18, 2022 |
| ASUSTek       | UX32A                       | Notebook    | [99bb55bc78](https://linux-hardware.org/?probe=99bb55bc78) | Aug 17, 2022 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [a5ed221478](https://linux-hardware.org/?probe=a5ed221478) | Aug 17, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [4d7aa09763](https://linux-hardware.org/?probe=4d7aa09763) | Aug 16, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [7e8d33a07f](https://linux-hardware.org/?probe=7e8d33a07f) | Aug 16, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [1b78691cac](https://linux-hardware.org/?probe=1b78691cac) | Aug 14, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [b41823f392](https://linux-hardware.org/?probe=b41823f392) | Aug 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [644fbe551a](https://linux-hardware.org/?probe=644fbe551a) | Aug 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [61d0b104e9](https://linux-hardware.org/?probe=61d0b104e9) | Aug 13, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [46aa83aeb4](https://linux-hardware.org/?probe=46aa83aeb4) | Aug 07, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [9655bf78d0](https://linux-hardware.org/?probe=9655bf78d0) | Aug 05, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [3d426cb1de](https://linux-hardware.org/?probe=3d426cb1de) | Aug 04, 2022 |
| Google        | Swanky                      | Notebook    | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [40099f2516](https://linux-hardware.org/?probe=40099f2516) | Aug 03, 2022 |
| HP            | 8433 11                     | Desktop     | [cd790281b5](https://linux-hardware.org/?probe=cd790281b5) | Aug 02, 2022 |
| Google        | Swanky                      | Notebook    | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b44bebcab6](https://linux-hardware.org/?probe=b44bebcab6) | Aug 01, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cdca6713e9](https://linux-hardware.org/?probe=cdca6713e9) | Jul 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1444843fcd](https://linux-hardware.org/?probe=1444843fcd) | Jul 31, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [3aa2ff8224](https://linux-hardware.org/?probe=3aa2ff8224) | Jul 29, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [4f2ba69c49](https://linux-hardware.org/?probe=4f2ba69c49) | Jul 27, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [19572ca302](https://linux-hardware.org/?probe=19572ca302) | Jul 27, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | Notebook    | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5795e098d2](https://linux-hardware.org/?probe=5795e098d2) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| MSI           | 2AE0                        | Desktop     | [5c0034d313](https://linux-hardware.org/?probe=5c0034d313) | Jul 22, 2022 |
| MSI           | 2AE0                        | Desktop     | [df441346da](https://linux-hardware.org/?probe=df441346da) | Jul 22, 2022 |
| Dell          | Latitude E4200              | Notebook    | [6cc0415a8a](https://linux-hardware.org/?probe=6cc0415a8a) | Jul 21, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| BESSTAR Te... | CB9                         | Mini pc     | [faa42224f0](https://linux-hardware.org/?probe=faa42224f0) | Jul 18, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [3e74ebae5a](https://linux-hardware.org/?probe=3e74ebae5a) | Jul 14, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [589a41e629](https://linux-hardware.org/?probe=589a41e629) | Jul 14, 2022 |
| Sony          | VPCEB1S1E                   | Notebook    | [d35015a369](https://linux-hardware.org/?probe=d35015a369) | Jul 12, 2022 |
| Dell          | Latitude XT                 | Notebook    | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | Notebook    | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0cdcc2c0e0](https://linux-hardware.org/?probe=0cdcc2c0e0) | Jul 10, 2022 |
| MicroByte     | ezbook                      | Notebook    | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [5f1b339a57](https://linux-hardware.org/?probe=5f1b339a57) | Jul 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [cce90ecbf2](https://linux-hardware.org/?probe=cce90ecbf2) | Jul 04, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e0c6593aee](https://linux-hardware.org/?probe=e0c6593aee) | Jul 04, 2022 |
| Dell          | 0M6C7G A00                  | Desktop     | [5eee0db64f](https://linux-hardware.org/?probe=5eee0db64f) | Jul 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| HP            | 2B0D A01                    | All in one  | [43b3fd0fd4](https://linux-hardware.org/?probe=43b3fd0fd4) | Jul 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [87eecce08e](https://linux-hardware.org/?probe=87eecce08e) | Jun 30, 2022 |
| MicroByte     | ezbook                      | Notebook    | [91b1fc169b](https://linux-hardware.org/?probe=91b1fc169b) | Jun 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [6e16eed17c](https://linux-hardware.org/?probe=6e16eed17c) | Jun 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| ASUSTek       | S550CM                      | Notebook    | [c7262ada04](https://linux-hardware.org/?probe=c7262ada04) | Jun 25, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a8c98b76b4](https://linux-hardware.org/?probe=a8c98b76b4) | Jun 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [10de805cb0](https://linux-hardware.org/?probe=10de805cb0) | Jun 24, 2022 |
| MSI           | H81M-E33                    | Desktop     | [0685f37e2c](https://linux-hardware.org/?probe=0685f37e2c) | Jun 22, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0112d58d4e](https://linux-hardware.org/?probe=0112d58d4e) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e048d9df09](https://linux-hardware.org/?probe=e048d9df09) | Jun 17, 2022 |
| Google        | Kled                        | Notebook    | [5f47e6d3e3](https://linux-hardware.org/?probe=5f47e6d3e3) | Jun 16, 2022 |
| Google        | Kled                        | Notebook    | [6a566134c4](https://linux-hardware.org/?probe=6a566134c4) | Jun 16, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [f7abc9fae0](https://linux-hardware.org/?probe=f7abc9fae0) | Jun 14, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efc9e12c05](https://linux-hardware.org/?probe=efc9e12c05) | Jun 12, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [3de31234b3](https://linux-hardware.org/?probe=3de31234b3) | Jun 12, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [33d201cb1d](https://linux-hardware.org/?probe=33d201cb1d) | Jun 10, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [9bfdb902ce](https://linux-hardware.org/?probe=9bfdb902ce) | Jun 08, 2022 |
| HP            | 3397                        | Desktop     | [55bcbdbc1f](https://linux-hardware.org/?probe=55bcbdbc1f) | Jun 07, 2022 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [5407d4a1f6](https://linux-hardware.org/?probe=5407d4a1f6) | Jun 07, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [074fd90c6a](https://linux-hardware.org/?probe=074fd90c6a) | Jun 06, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [d9e8d3957e](https://linux-hardware.org/?probe=d9e8d3957e) | Jun 06, 2022 |
| TrekStor      | Surfbook A13B               | Notebook    | [a42b3de31a](https://linux-hardware.org/?probe=a42b3de31a) | Jun 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3b4483236d](https://linux-hardware.org/?probe=3b4483236d) | Jun 05, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [20544feb00](https://linux-hardware.org/?probe=20544feb00) | Jun 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
| Dell          | Precision M6500             | Notebook    | [1b68d2ca74](https://linux-hardware.org/?probe=1b68d2ca74) | Jun 01, 2022 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | Notebook    | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8e0addf4d3](https://linux-hardware.org/?probe=8e0addf4d3) | May 24, 2022 |
| INP           | i1000BTS                    | Desktop     | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [74e6dbe9af](https://linux-hardware.org/?probe=74e6dbe9af) | May 23, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a53d746d08](https://linux-hardware.org/?probe=a53d746d08) | May 23, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Dell          | Latitude E6410              | Notebook    | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [9044b2e4e2](https://linux-hardware.org/?probe=9044b2e4e2) | May 18, 2022 |
| Medion        | Akoya E6415                 | Notebook    | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [e6c4aaa3d8](https://linux-hardware.org/?probe=e6c4aaa3d8) | May 12, 2022 |
| ASUSTek       | ProArt Z490-CREATOR 10G     | Desktop     | [4d68e6fd8d](https://linux-hardware.org/?probe=4d68e6fd8d) | May 12, 2022 |
| HP            | 3031h                       | Desktop     | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| Unknown       | HX90                        | Desktop     | [3a7e2628b0](https://linux-hardware.org/?probe=3a7e2628b0) | May 09, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e99cdba363](https://linux-hardware.org/?probe=e99cdba363) | May 07, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HYPERPC       | PLAY                        | Notebook    | [408e86d04f](https://linux-hardware.org/?probe=408e86d04f) | May 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [246c63d834](https://linux-hardware.org/?probe=246c63d834) | May 06, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [ebaaf4a69b](https://linux-hardware.org/?probe=ebaaf4a69b) | May 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | 8433 11                     | Desktop     | [a5b829538b](https://linux-hardware.org/?probe=a5b829538b) | Apr 29, 2022 |
| TYAN Compu... | S7012                       | Server      | [018f293210](https://linux-hardware.org/?probe=018f293210) | Apr 28, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4dd8fa1d2f](https://linux-hardware.org/?probe=4dd8fa1d2f) | Apr 27, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [fc283a78af](https://linux-hardware.org/?probe=fc283a78af) | Apr 26, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [bbb54a4f60](https://linux-hardware.org/?probe=bbb54a4f60) | Apr 26, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [35b3b3ae30](https://linux-hardware.org/?probe=35b3b3ae30) | Apr 26, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [b2b220b65d](https://linux-hardware.org/?probe=b2b220b65d) | Apr 25, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [d3d995a41b](https://linux-hardware.org/?probe=d3d995a41b) | Apr 24, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [faf447a067](https://linux-hardware.org/?probe=faf447a067) | Apr 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [83ffe21604](https://linux-hardware.org/?probe=83ffe21604) | Apr 18, 2022 |
| Dell          | 0X9M3X A05                  | Desktop     | [f049c88dfe](https://linux-hardware.org/?probe=f049c88dfe) | Apr 18, 2022 |
| Clevo         | W54xEU                      | Notebook    | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [81dced5e0a](https://linux-hardware.org/?probe=81dced5e0a) | Apr 16, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [19055b80bc](https://linux-hardware.org/?probe=19055b80bc) | Apr 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | Notebook    | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Unknown       | Unknown                     | Desktop     | [d7811dbd43](https://linux-hardware.org/?probe=d7811dbd43) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [52d05bca1d](https://linux-hardware.org/?probe=52d05bca1d) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [7a9f6e1de7](https://linux-hardware.org/?probe=7a9f6e1de7) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| Samsung       | R505                        | Notebook    | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | Notebook    | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [c640615939](https://linux-hardware.org/?probe=c640615939) | Apr 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a54c91912a](https://linux-hardware.org/?probe=a54c91912a) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [5e31d89c28](https://linux-hardware.org/?probe=5e31d89c28) | Apr 09, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3c17fb0db4](https://linux-hardware.org/?probe=3c17fb0db4) | Apr 07, 2022 |
| Gigabyte      | H470M DS3H                  | Desktop     | [bbfc43c637](https://linux-hardware.org/?probe=bbfc43c637) | Apr 05, 2022 |
| IPASON        | MaxBook P1                  | Notebook    | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [5f45322780](https://linux-hardware.org/?probe=5f45322780) | Apr 04, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [42cf748563](https://linux-hardware.org/?probe=42cf748563) | Apr 03, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [8340e366fc](https://linux-hardware.org/?probe=8340e366fc) | Mar 28, 2022 |
| Toshiba       | Satellite L755D             | Notebook    | [d99ccc2771](https://linux-hardware.org/?probe=d99ccc2771) | Mar 28, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [3a8a0e2c0c](https://linux-hardware.org/?probe=3a8a0e2c0c) | Mar 26, 2022 |
| Dell          | 05KX61 A00                  | Server      | [77d570f7ae](https://linux-hardware.org/?probe=77d570f7ae) | Mar 25, 2022 |
| Dell          | Studio 1558                 | Notebook    | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | Notebook    | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| HP            | 802E                        | Desktop     | [b15f756d65](https://linux-hardware.org/?probe=b15f756d65) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | 3397                        | Desktop     | [fe1ae429b1](https://linux-hardware.org/?probe=fe1ae429b1) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| HP            | Pavilion dv7                | Notebook    | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [220c4f69b0](https://linux-hardware.org/?probe=220c4f69b0) | Mar 15, 2022 |
| ASUSTek       | A55BM-E                     | Desktop     | [7bbbcc53c1](https://linux-hardware.org/?probe=7bbbcc53c1) | Mar 14, 2022 |
| Dell          | OptiPlex 980                | Desktop     | [14cf2b23f7](https://linux-hardware.org/?probe=14cf2b23f7) | Mar 14, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [d59f0b152c](https://linux-hardware.org/?probe=d59f0b152c) | Mar 10, 2022 |
| Toshiba       | Satellite P755              | Notebook    | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| Packard Be... | EasyNote MH35               | Notebook    | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [6382c70064](https://linux-hardware.org/?probe=6382c70064) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [8e3573295d](https://linux-hardware.org/?probe=8e3573295d) | Mar 07, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [d57f5c8ce3](https://linux-hardware.org/?probe=d57f5c8ce3) | Mar 07, 2022 |
| Medion        | MS-7797                     | Desktop     | [88982d8ccb](https://linux-hardware.org/?probe=88982d8ccb) | Mar 05, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [f23d0b2728](https://linux-hardware.org/?probe=f23d0b2728) | Mar 05, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [b18f6804d6](https://linux-hardware.org/?probe=b18f6804d6) | Mar 02, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [43c3e7c4a0](https://linux-hardware.org/?probe=43c3e7c4a0) | Mar 02, 2022 |
| Lenovo        | U310                        | Notebook    | [856a65502e](https://linux-hardware.org/?probe=856a65502e) | Feb 28, 2022 |
| ASUSTek       | UX305FA                     | Notebook    | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Intel         | H55                         | Desktop     | [2f52a73f85](https://linux-hardware.org/?probe=2f52a73f85) | Feb 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [beeb081772](https://linux-hardware.org/?probe=beeb081772) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Pegatron      | Narra6                      | Desktop     | [ad9a06f14d](https://linux-hardware.org/?probe=ad9a06f14d) | Feb 25, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | Notebook    | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [0747de6777](https://linux-hardware.org/?probe=0747de6777) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| ECS           | A785GM-AD3                  | Desktop     | [b6459dbb39](https://linux-hardware.org/?probe=b6459dbb39) | Feb 12, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [e58751112a](https://linux-hardware.org/?probe=e58751112a) | Feb 11, 2022 |
| Notebook      | NK50S5_SZ                   | Notebook    | [c5a3485d32](https://linux-hardware.org/?probe=c5a3485d32) | Feb 11, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [6f66651cd1](https://linux-hardware.org/?probe=6f66651cd1) | Feb 10, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [7c3fa0c43b](https://linux-hardware.org/?probe=7c3fa0c43b) | Feb 08, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3d6c666b77](https://linux-hardware.org/?probe=3d6c666b77) | Feb 08, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [6bb9884c12](https://linux-hardware.org/?probe=6bb9884c12) | Feb 08, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [74ebb0645d](https://linux-hardware.org/?probe=74ebb0645d) | Feb 06, 2022 |
| HP            | Notebook                    | Notebook    | [69071da574](https://linux-hardware.org/?probe=69071da574) | Feb 06, 2022 |
| Acer          | Aspire 7735                 | Notebook    | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [451c540217](https://linux-hardware.org/?probe=451c540217) | Feb 05, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | Desktop     | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| HP            | 8434 11                     | Desktop     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [fab2b2828e](https://linux-hardware.org/?probe=fab2b2828e) | Jan 26, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [8062682731](https://linux-hardware.org/?probe=8062682731) | Jan 25, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [47e447f5da](https://linux-hardware.org/?probe=47e447f5da) | Jan 25, 2022 |
| Sony          | VPCF13Z1R                   | Notebook    | [7aff0d5c29](https://linux-hardware.org/?probe=7aff0d5c29) | Jan 25, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [cad36b0eba](https://linux-hardware.org/?probe=cad36b0eba) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [868c5fe3a4](https://linux-hardware.org/?probe=868c5fe3a4) | Jan 24, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [a4b48a8427](https://linux-hardware.org/?probe=a4b48a8427) | Jan 23, 2022 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | Desktop     | [622bf721f3](https://linux-hardware.org/?probe=622bf721f3) | Jan 23, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [55067d6afe](https://linux-hardware.org/?probe=55067d6afe) | Jan 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [37730388fd](https://linux-hardware.org/?probe=37730388fd) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | Desktop     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | Desktop     | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | 8455                        | Desktop     | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [512b021ab8](https://linux-hardware.org/?probe=512b021ab8) | Jan 19, 2022 |
| Lenovo        | V155-15API 81V5             | Notebook    | [09e824f68b](https://linux-hardware.org/?probe=09e824f68b) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | Desktop     | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | Desktop     | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | Desktop     | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | Desktop     | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| HP            | 18E7                        | Desktop     | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | Desktop     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | Desktop     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | Desktop     | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | Desktop     | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [556d0fb884](https://linux-hardware.org/?probe=556d0fb884) | Jan 18, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3d19d1297](https://linux-hardware.org/?probe=c3d19d1297) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | Desktop     | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | Desktop     | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6438d5a5af](https://linux-hardware.org/?probe=6438d5a5af) | Jan 15, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [89d70da207](https://linux-hardware.org/?probe=89d70da207) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ae80854830](https://linux-hardware.org/?probe=ae80854830) | Jan 15, 2022 |
| ZOTAC         | NM10                        | Desktop     | [d758728651](https://linux-hardware.org/?probe=d758728651) | Jan 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d2fa7ede7](https://linux-hardware.org/?probe=9d2fa7ede7) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2fbac2ebd5](https://linux-hardware.org/?probe=2fbac2ebd5) | Jan 12, 2022 |
| HPE           | ML10Gen9                    | Server      | [03f2d30df2](https://linux-hardware.org/?probe=03f2d30df2) | Jan 11, 2022 |
| Dell          | Latitude E5400              | Notebook    | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| HP            | 3397                        | Desktop     | [38a4d731fe](https://linux-hardware.org/?probe=38a4d731fe) | Jan 08, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [858d718984](https://linux-hardware.org/?probe=858d718984) | Jan 07, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [faef08af10](https://linux-hardware.org/?probe=faef08af10) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [55ac013e1e](https://linux-hardware.org/?probe=55ac013e1e) | Jan 06, 2022 |
| Dell          | 032W55 A03                  | Desktop     | [f3838abaaf](https://linux-hardware.org/?probe=f3838abaaf) | Jan 04, 2022 |
| HP            | ProLiant DL120 G7           | Server      | [70c39995ec](https://linux-hardware.org/?probe=70c39995ec) | Jan 03, 2022 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [9eb9340d47](https://linux-hardware.org/?probe=9eb9340d47) | Jan 02, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| ASRock        | 870iCafe R2.0               | Desktop     | [f67cc91b2e](https://linux-hardware.org/?probe=f67cc91b2e) | Dec 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5a25a3ab14](https://linux-hardware.org/?probe=5a25a3ab14) | Dec 31, 2021 |
| Gigabyte      | MZ71-CE0-00 01000100        | Server      | [6d2ee30f72](https://linux-hardware.org/?probe=6d2ee30f72) | Dec 31, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e637f730e7](https://linux-hardware.org/?probe=e637f730e7) | Dec 31, 2021 |
| MSI           | H81M-P33                    | Desktop     | [4c225dc457](https://linux-hardware.org/?probe=4c225dc457) | Dec 30, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Gigabyte      | H67MA-UD2H-B3               | Desktop     | [e32af6a3de](https://linux-hardware.org/?probe=e32af6a3de) | Dec 26, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [62abb9d0ef](https://linux-hardware.org/?probe=62abb9d0ef) | Dec 25, 2021 |
| Lenovo        | U310                        | Notebook    | [fa57a69141](https://linux-hardware.org/?probe=fa57a69141) | Dec 24, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [1fbef2b76c](https://linux-hardware.org/?probe=1fbef2b76c) | Dec 23, 2021 |
| HP            | Pavilion dv4                | Notebook    | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Lenovo        | G580 2189                   | Notebook    | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [8f53f4e97c](https://linux-hardware.org/?probe=8f53f4e97c) | Dec 19, 2021 |
| AZW           | GK mini                     | Mini pc     | [bb4770d627](https://linux-hardware.org/?probe=bb4770d627) | Dec 17, 2021 |
| HP            | ENVY Notebook               | Notebook    | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | Notebook    | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [3bd9548bab](https://linux-hardware.org/?probe=3bd9548bab) | Dec 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| ASUSTek       | X751BP                      | Notebook    | [e1acc83725](https://linux-hardware.org/?probe=e1acc83725) | Dec 06, 2021 |
| MSI           | H61M-S20                    | Desktop     | [7e1fdb578c](https://linux-hardware.org/?probe=7e1fdb578c) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [50acb69e6e](https://linux-hardware.org/?probe=50acb69e6e) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | Notebook    | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d0d26ec246](https://linux-hardware.org/?probe=d0d26ec246) | Dec 01, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6b7ec76b64](https://linux-hardware.org/?probe=6b7ec76b64) | Nov 28, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [9b13286f92](https://linux-hardware.org/?probe=9b13286f92) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [3d2583b1f1](https://linux-hardware.org/?probe=3d2583b1f1) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| Dell          | 0T656F A01                  | Desktop     | [06f4633f1b](https://linux-hardware.org/?probe=06f4633f1b) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [bb170a308c](https://linux-hardware.org/?probe=bb170a308c) | Nov 24, 2021 |
| HPE           | ML10Gen9                    | Server      | [141f8709dd](https://linux-hardware.org/?probe=141f8709dd) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4368bd67ac](https://linux-hardware.org/?probe=4368bd67ac) | Nov 23, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [686454975b](https://linux-hardware.org/?probe=686454975b) | Nov 23, 2021 |
| Dell          | Precision 5560              | Notebook    | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| ASUSTek       | AT3IONT-I                   | Desktop     | [b8f5329824](https://linux-hardware.org/?probe=b8f5329824) | Nov 22, 2021 |
| Dell          | 0M017G A00                  | Desktop     | [da444f9b8f](https://linux-hardware.org/?probe=da444f9b8f) | Nov 22, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [a13103a9ad](https://linux-hardware.org/?probe=a13103a9ad) | Nov 20, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [36ac197007](https://linux-hardware.org/?probe=36ac197007) | Nov 17, 2021 |
| Dell          | 0G261D A00                  | Desktop     | [1bb376a60b](https://linux-hardware.org/?probe=1bb376a60b) | Nov 17, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [8a6de2970d](https://linux-hardware.org/?probe=8a6de2970d) | Nov 15, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [2cdd151d75](https://linux-hardware.org/?probe=2cdd151d75) | Nov 14, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Notebook    | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| Dell          | Latitude E6410              | Notebook    | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| AMI           | Unknown                     | Notebook    | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | Notebook    | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [61bfe5dfa7](https://linux-hardware.org/?probe=61bfe5dfa7) | Nov 11, 2021 |
| Fujitsu       | D3633-S1 S26361-D3633-S1    | Desktop     | [1971073b86](https://linux-hardware.org/?probe=1971073b86) | Nov 10, 2021 |
| HP            | ZBook 15                    | Notebook    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [dd8a96b615](https://linux-hardware.org/?probe=dd8a96b615) | Nov 09, 2021 |
| ASUSTek       | M4A78-E                     | Desktop     | [89aff3881c](https://linux-hardware.org/?probe=89aff3881c) | Nov 09, 2021 |
| ASUSTek       | A55BM-E                     | Desktop     | [fd25737c58](https://linux-hardware.org/?probe=fd25737c58) | Nov 09, 2021 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [c0b1971c18](https://linux-hardware.org/?probe=c0b1971c18) | Nov 09, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| Rockchip      | Unknown                     | Soc         | [de559ac6d9](https://linux-hardware.org/?probe=de559ac6d9) | Nov 08, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [914d585adc](https://linux-hardware.org/?probe=914d585adc) | Nov 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| AZW           | SEi                         | Notebook    | [6d9a86e769](https://linux-hardware.org/?probe=6d9a86e769) | Nov 02, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [05e3caa05c](https://linux-hardware.org/?probe=05e3caa05c) | Nov 02, 2021 |
| MSI           | GE76 Raider 11UG            | Notebook    | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [60ffb9d428](https://linux-hardware.org/?probe=60ffb9d428) | Oct 31, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [7eaeae034c](https://linux-hardware.org/?probe=7eaeae034c) | Oct 29, 2021 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [6e1fbe4dde](https://linux-hardware.org/?probe=6e1fbe4dde) | Oct 27, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | Notebook    | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [4946a6a02c](https://linux-hardware.org/?probe=4946a6a02c) | Oct 26, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [0ad429cea5](https://linux-hardware.org/?probe=0ad429cea5) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| HP            | G70                         | Notebook    | [68fb8430c2](https://linux-hardware.org/?probe=68fb8430c2) | Oct 24, 2021 |
| HP            | G70                         | Notebook    | [3e2c50a321](https://linux-hardware.org/?probe=3e2c50a321) | Oct 24, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [4ba408d68c](https://linux-hardware.org/?probe=4ba408d68c) | Oct 23, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [e82ee9096e](https://linux-hardware.org/?probe=e82ee9096e) | Oct 23, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [3e15c8708a](https://linux-hardware.org/?probe=3e15c8708a) | Oct 23, 2021 |
| Rockchip      | Unknown                     | Soc         | [e7c44d5f41](https://linux-hardware.org/?probe=e7c44d5f41) | Oct 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [09e3d5da46](https://linux-hardware.org/?probe=09e3d5da46) | Oct 21, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [27b0a66ceb](https://linux-hardware.org/?probe=27b0a66ceb) | Oct 20, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | Notebook    | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [34a5253469](https://linux-hardware.org/?probe=34a5253469) | Oct 16, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [b4660289b3](https://linux-hardware.org/?probe=b4660289b3) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | Notebook    | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| Dell          | Latitude E6440              | Notebook    | [383edb4c99](https://linux-hardware.org/?probe=383edb4c99) | Oct 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6c0867e544](https://linux-hardware.org/?probe=6c0867e544) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [a8e5248d3d](https://linux-hardware.org/?probe=a8e5248d3d) | Oct 13, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | Notebook    | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [fe1c549ed6](https://linux-hardware.org/?probe=fe1c549ed6) | Oct 05, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [f0ff9a911e](https://linux-hardware.org/?probe=f0ff9a911e) | Oct 03, 2021 |
| Dell          | Latitude E6440              | Notebook    | [a8884539e7](https://linux-hardware.org/?probe=a8884539e7) | Oct 02, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b535b99341](https://linux-hardware.org/?probe=b535b99341) | Sep 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [f04c751d60](https://linux-hardware.org/?probe=f04c751d60) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5f6c245dc5](https://linux-hardware.org/?probe=5f6c245dc5) | Sep 28, 2021 |
| MSI           | H61M-P23                    | Desktop     | [3a07878154](https://linux-hardware.org/?probe=3a07878154) | Sep 28, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [5422d3bf1d](https://linux-hardware.org/?probe=5422d3bf1d) | Sep 27, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [060da3d3ab](https://linux-hardware.org/?probe=060da3d3ab) | Sep 26, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ed937ed1cd](https://linux-hardware.org/?probe=ed937ed1cd) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Entroware     | Aether                      | Notebook    | [c65a69857f](https://linux-hardware.org/?probe=c65a69857f) | Sep 22, 2021 |
| HP            | 8265                        | Desktop     | [f840aed42d](https://linux-hardware.org/?probe=f840aed42d) | Sep 21, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a5211dc1bb](https://linux-hardware.org/?probe=a5211dc1bb) | Sep 21, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [13298e0f6b](https://linux-hardware.org/?probe=13298e0f6b) | Sep 19, 2021 |
| HP            | 3397                        | Desktop     | [13d358c48e](https://linux-hardware.org/?probe=13d358c48e) | Sep 18, 2021 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [3c40bbda61](https://linux-hardware.org/?probe=3c40bbda61) | Sep 18, 2021 |
| HP            | 1497                        | Desktop     | [311efc294a](https://linux-hardware.org/?probe=311efc294a) | Sep 16, 2021 |
| ASRock        | H110M-STX                   | Desktop     | [6bb90d3b07](https://linux-hardware.org/?probe=6bb90d3b07) | Sep 16, 2021 |
| Medion        | MS-7797                     | Desktop     | [f2f5579dc5](https://linux-hardware.org/?probe=f2f5579dc5) | Sep 15, 2021 |
| Medion        | MS-7797                     | Desktop     | [6ca6bee736](https://linux-hardware.org/?probe=6ca6bee736) | Sep 15, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [6e8ca97f4b](https://linux-hardware.org/?probe=6e8ca97f4b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [e0b0d2d509](https://linux-hardware.org/?probe=e0b0d2d509) | Sep 13, 2021 |
| Teclast       | F15S                        | Notebook    | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | Notebook    | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Lenovo        | ThinkPad T420 42361P0       | Notebook    | [24f3d09047](https://linux-hardware.org/?probe=24f3d09047) | Sep 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | Notebook    | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | Notebook    | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | Notebook    | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [5f2f500f7a](https://linux-hardware.org/?probe=5f2f500f7a) | Sep 10, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| Intel         | DH67CL AAG10212-204         | Desktop     | [e9d68ab5e4](https://linux-hardware.org/?probe=e9d68ab5e4) | Sep 09, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [14109edfc9](https://linux-hardware.org/?probe=14109edfc9) | Sep 07, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [cb82d03efe](https://linux-hardware.org/?probe=cb82d03efe) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Acer          | Spin SP111-33               | Convertible | [2a5ddf7be8](https://linux-hardware.org/?probe=2a5ddf7be8) | Sep 05, 2021 |
| HP            | 3396                        | Desktop     | [147c8ed96c](https://linux-hardware.org/?probe=147c8ed96c) | Sep 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [54c321b6bd](https://linux-hardware.org/?probe=54c321b6bd) | Sep 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | Notebook    | [812cc9220c](https://linux-hardware.org/?probe=812cc9220c) | Sep 01, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [c594736488](https://linux-hardware.org/?probe=c594736488) | Aug 30, 2021 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [16250b0c12](https://linux-hardware.org/?probe=16250b0c12) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [41e440c2e5](https://linux-hardware.org/?probe=41e440c2e5) | Aug 29, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e086d2eb61](https://linux-hardware.org/?probe=e086d2eb61) | Aug 29, 2021 |
| MSI           | 2A9C                        | Desktop     | [57601d98f3](https://linux-hardware.org/?probe=57601d98f3) | Aug 28, 2021 |
| Notebook      | NK50S5_SZ                   | Notebook    | [6cba599e57](https://linux-hardware.org/?probe=6cba599e57) | Aug 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [c375ab72c5](https://linux-hardware.org/?probe=c375ab72c5) | Aug 25, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [d3e14ad15a](https://linux-hardware.org/?probe=d3e14ad15a) | Aug 25, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [413934fef3](https://linux-hardware.org/?probe=413934fef3) | Aug 23, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [b28b036f78](https://linux-hardware.org/?probe=b28b036f78) | Aug 22, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a1189f529](https://linux-hardware.org/?probe=1a1189f529) | Aug 21, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [19cfd7b8f5](https://linux-hardware.org/?probe=19cfd7b8f5) | Aug 21, 2021 |
| Packard Be... | EasyNote SL65               | Notebook    | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| GPD           | MicroPC                     | Notebook    | [7fa0c4e3c4](https://linux-hardware.org/?probe=7fa0c4e3c4) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | Notebook    | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [635d8e55e7](https://linux-hardware.org/?probe=635d8e55e7) | Aug 17, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| Acer          | Extensa 5630                | Notebook    | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| ASRock        | M3A785GMH/128M              | Desktop     | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| HP            | Notebook                    | Notebook    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| MSI           | X79A-GD45                   | Desktop     | [c5b78e1a01](https://linux-hardware.org/?probe=c5b78e1a01) | Aug 13, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [cfe37f86a3](https://linux-hardware.org/?probe=cfe37f86a3) | Aug 12, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6776a424d5](https://linux-hardware.org/?probe=6776a424d5) | Aug 11, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [bbfbd42562](https://linux-hardware.org/?probe=bbfbd42562) | Aug 07, 2021 |
| ASUSTek       | X556UAK                     | Notebook    | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | Notebook    | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Notebook      | N24_25GU                    | Notebook    | [2e67e53ad7](https://linux-hardware.org/?probe=2e67e53ad7) | Aug 05, 2021 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [c861e28d21](https://linux-hardware.org/?probe=c861e28d21) | Aug 05, 2021 |
| ASRock        | Q1900M                      | Desktop     | [700f4a0ca1](https://linux-hardware.org/?probe=700f4a0ca1) | Aug 02, 2021 |
| Dell          | 08NPPY A00                  | Desktop     | [e706b18dd8](https://linux-hardware.org/?probe=e706b18dd8) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | Notebook    | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Dell          | Vostro 1520                 | Notebook    | [af01145277](https://linux-hardware.org/?probe=af01145277) | Jul 28, 2021 |
| Clevo         | M720R                       | Notebook    | [a52f0f2d7c](https://linux-hardware.org/?probe=a52f0f2d7c) | Jul 27, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| HP            | Laptop 15z-ef1xxx           | Notebook    | [d72c30940e](https://linux-hardware.org/?probe=d72c30940e) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e8e43c77ca](https://linux-hardware.org/?probe=e8e43c77ca) | Jul 23, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [6dcb19e468](https://linux-hardware.org/?probe=6dcb19e468) | Jul 23, 2021 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [db7104ee10](https://linux-hardware.org/?probe=db7104ee10) | Jul 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [647fe69592](https://linux-hardware.org/?probe=647fe69592) | Jul 22, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| System76      | Galago Pro                  | Notebook    | [c74e5f1cf9](https://linux-hardware.org/?probe=c74e5f1cf9) | Jul 17, 2021 |
| MSI           | H61M-E33                    | Desktop     | [0d1a9284a9](https://linux-hardware.org/?probe=0d1a9284a9) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Dell          | Studio 1558                 | Notebook    | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [6001052e23](https://linux-hardware.org/?probe=6001052e23) | Jul 15, 2021 |
| Toshiba       | Satellite C850-BMK          | Notebook    | [d92515e12e](https://linux-hardware.org/?probe=d92515e12e) | Jul 14, 2021 |
| HP            | Pavilion 17                 | Notebook    | [628e42055f](https://linux-hardware.org/?probe=628e42055f) | Jul 12, 2021 |
| Lenovo        | Tilapia CRB                 | Desktop     | [da1f0d65ec](https://linux-hardware.org/?probe=da1f0d65ec) | Jul 12, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d49086311b](https://linux-hardware.org/?probe=d49086311b) | Jul 12, 2021 |
| Fujitsu       | LIFEBOOK E5511              | Notebook    | [4c13b21a8c](https://linux-hardware.org/?probe=4c13b21a8c) | Jul 10, 2021 |
| Unknown       | TB-4000                     | Desktop     | [fb3e1984b0](https://linux-hardware.org/?probe=fb3e1984b0) | Jul 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [ae14beb6fd](https://linux-hardware.org/?probe=ae14beb6fd) | Jul 09, 2021 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [7adcf7dc7c](https://linux-hardware.org/?probe=7adcf7dc7c) | Jul 09, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [ebd157141b](https://linux-hardware.org/?probe=ebd157141b) | Jul 08, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [4b2c3ea073](https://linux-hardware.org/?probe=4b2c3ea073) | Jul 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cce6c3a767](https://linux-hardware.org/?probe=cce6c3a767) | Jul 06, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b6c1f36f1f](https://linux-hardware.org/?probe=b6c1f36f1f) | Jul 04, 2021 |
| ASUSTek       | Z170-AR                     | Desktop     | [37343856a5](https://linux-hardware.org/?probe=37343856a5) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | Notebook    | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | 05GD68 A00                  | Desktop     | [9bb3c8dbe9](https://linux-hardware.org/?probe=9bb3c8dbe9) | Jul 02, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [820725cbbd](https://linux-hardware.org/?probe=820725cbbd) | Jun 30, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [dcf91492a2](https://linux-hardware.org/?probe=dcf91492a2) | Jun 29, 2021 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [55bdc0f976](https://linux-hardware.org/?probe=55bdc0f976) | Jun 28, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [d90a6deaeb](https://linux-hardware.org/?probe=d90a6deaeb) | Jun 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0e6ca5f944](https://linux-hardware.org/?probe=0e6ca5f944) | Jun 27, 2021 |
| HP            | Pavilion g6                 | Notebook    | [3cfb1f50dc](https://linux-hardware.org/?probe=3cfb1f50dc) | Jun 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [772a91651b](https://linux-hardware.org/?probe=772a91651b) | Jun 26, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [4b13ffc6ce](https://linux-hardware.org/?probe=4b13ffc6ce) | Jun 26, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [4fdc27b018](https://linux-hardware.org/?probe=4fdc27b018) | Jun 25, 2021 |
| HP            | Pavilion dv7                | Notebook    | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [7fba4b1b78](https://linux-hardware.org/?probe=7fba4b1b78) | Jun 23, 2021 |
| Acer          | V7-710                      | Notebook    | [fe9a84f137](https://linux-hardware.org/?probe=fe9a84f137) | Jun 23, 2021 |
| Dell          | Latitude E6400              | Notebook    | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| HP            | 1495                        | Desktop     | [03ab704550](https://linux-hardware.org/?probe=03ab704550) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [c71b41c7a8](https://linux-hardware.org/?probe=c71b41c7a8) | Jun 20, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [f39e5005bd](https://linux-hardware.org/?probe=f39e5005bd) | Jun 20, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [7bf43ae0d0](https://linux-hardware.org/?probe=7bf43ae0d0) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [9a4e288f49](https://linux-hardware.org/?probe=9a4e288f49) | Jun 19, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d41809b4c9](https://linux-hardware.org/?probe=d41809b4c9) | Jun 19, 2021 |
| Hardkernel    | ODROID-C4                   | Soc         | [b10313d89f](https://linux-hardware.org/?probe=b10313d89f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [32538ae4b8](https://linux-hardware.org/?probe=32538ae4b8) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [882855d037](https://linux-hardware.org/?probe=882855d037) | Jun 17, 2021 |
| eMachines     | EL1352                      | Desktop     | [f175ae71f2](https://linux-hardware.org/?probe=f175ae71f2) | Jun 16, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8bb06ce851](https://linux-hardware.org/?probe=8bb06ce851) | Jun 16, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [0616fdb086](https://linux-hardware.org/?probe=0616fdb086) | Jun 14, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3d47d96665](https://linux-hardware.org/?probe=3d47d96665) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9bea47caa](https://linux-hardware.org/?probe=c9bea47caa) | Jun 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c9c757474a](https://linux-hardware.org/?probe=c9c757474a) | Jun 12, 2021 |
| Dell          | Latitude D520               | Notebook    | [5f08e309ae](https://linux-hardware.org/?probe=5f08e309ae) | Jun 11, 2021 |
| Dell          | Latitude E6510              | Notebook    | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Acer          | Aspire 7730G                | Notebook    | [4d314b5039](https://linux-hardware.org/?probe=4d314b5039) | Jun 10, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [17af721bae](https://linux-hardware.org/?probe=17af721bae) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23dc47130c](https://linux-hardware.org/?probe=23dc47130c) | Jun 10, 2021 |
| Gigabyte      | Z97-HD3                     | Desktop     | [1ab4ff25ab](https://linux-hardware.org/?probe=1ab4ff25ab) | Jun 10, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b234c99d47](https://linux-hardware.org/?probe=b234c99d47) | Jun 08, 2021 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [95708a9a82](https://linux-hardware.org/?probe=95708a9a82) | Jun 07, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [865f37b773](https://linux-hardware.org/?probe=865f37b773) | Jun 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b5aa561890](https://linux-hardware.org/?probe=b5aa561890) | Jun 05, 2021 |
| ASUSTek       | K73SJ                       | Notebook    | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [af16143ad8](https://linux-hardware.org/?probe=af16143ad8) | Jun 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [d732611ebb](https://linux-hardware.org/?probe=d732611ebb) | Jun 02, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [3f2f789273](https://linux-hardware.org/?probe=3f2f789273) | Jun 01, 2021 |
| HP            | Pavilion g6                 | Notebook    | [0245da9040](https://linux-hardware.org/?probe=0245da9040) | May 31, 2021 |
| Lenovo        | 3102 NOK                    | Desktop     | [3d1a8cffc3](https://linux-hardware.org/?probe=3d1a8cffc3) | May 31, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [913ea68973](https://linux-hardware.org/?probe=913ea68973) | May 31, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23a20d91ef](https://linux-hardware.org/?probe=23a20d91ef) | May 31, 2021 |
| Dell          | 0PC5F7 A02                  | Desktop     | [86611a5efe](https://linux-hardware.org/?probe=86611a5efe) | May 31, 2021 |
| Inventec      | Z CLASS A02                 | Desktop     | [7fc4815cbd](https://linux-hardware.org/?probe=7fc4815cbd) | May 29, 2021 |
| ASUSTek       | GL12CX                      | Desktop     | [d95dd524bc](https://linux-hardware.org/?probe=d95dd524bc) | May 28, 2021 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [cf31dd498a](https://linux-hardware.org/?probe=cf31dd498a) | May 26, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [8e44c9edaf](https://linux-hardware.org/?probe=8e44c9edaf) | May 26, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [3a2f765228](https://linux-hardware.org/?probe=3a2f765228) | May 26, 2021 |
| HP            | Pavilion                    | Notebook    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| HP            | 635                         | Notebook    | [acff9705ee](https://linux-hardware.org/?probe=acff9705ee) | May 26, 2021 |
| Dell          | G7 7500                     | Notebook    | [65cb46fe46](https://linux-hardware.org/?probe=65cb46fe46) | May 25, 2021 |
| HP            | 635                         | Notebook    | [b96dfdc2fa](https://linux-hardware.org/?probe=b96dfdc2fa) | May 24, 2021 |
| Dell          | Precision M4800             | Notebook    | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a9539e0359](https://linux-hardware.org/?probe=a9539e0359) | May 24, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [74e472db93](https://linux-hardware.org/?probe=74e472db93) | May 23, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | Notebook    | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | Notebook    | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [d328ce9f69](https://linux-hardware.org/?probe=d328ce9f69) | May 18, 2021 |
| Dell          | 02YYK5 A01                  | Desktop     | [6b9dbebe2f](https://linux-hardware.org/?probe=6b9dbebe2f) | May 18, 2021 |
| Acer          | C-AXC-605                   | Desktop     | [7f9d35f468](https://linux-hardware.org/?probe=7f9d35f468) | May 18, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [c56840df98](https://linux-hardware.org/?probe=c56840df98) | May 17, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f1592b156b](https://linux-hardware.org/?probe=f1592b156b) | May 16, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [dec38c20c6](https://linux-hardware.org/?probe=dec38c20c6) | May 15, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | Notebook    | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | Notebook    | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [ea47dfa580](https://linux-hardware.org/?probe=ea47dfa580) | May 13, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bbefe7273f](https://linux-hardware.org/?probe=bbefe7273f) | May 13, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [e39d859a43](https://linux-hardware.org/?probe=e39d859a43) | May 12, 2021 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [6b07e6e09b](https://linux-hardware.org/?probe=6b07e6e09b) | May 12, 2021 |
| Notebook      | P17SM-A                     | Notebook    | [2a8297469f](https://linux-hardware.org/?probe=2a8297469f) | May 11, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [33a95ff348](https://linux-hardware.org/?probe=33a95ff348) | May 10, 2021 |
| Dell          | Precision M4500             | Notebook    | [407d9c0748](https://linux-hardware.org/?probe=407d9c0748) | May 10, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40a8a145e6](https://linux-hardware.org/?probe=40a8a145e6) | May 10, 2021 |
| Dell          | G7 7588                     | Notebook    | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | Notebook    | [d0fb43caf0](https://linux-hardware.org/?probe=d0fb43caf0) | May 08, 2021 |
| HP            | Pavilion 17                 | Notebook    | [32ea31fd5f](https://linux-hardware.org/?probe=32ea31fd5f) | May 07, 2021 |
| Cube          | i18-L                       | Notebook    | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [9db6c930c1](https://linux-hardware.org/?probe=9db6c930c1) | May 06, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| HP            | Pavilion                    | Notebook    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [1eea89f8bb](https://linux-hardware.org/?probe=1eea89f8bb) | May 03, 2021 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9ff1a95290](https://linux-hardware.org/?probe=9ff1a95290) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| HP            | Pavilion 17                 | Notebook    | [7bb6b560e5](https://linux-hardware.org/?probe=7bb6b560e5) | Apr 29, 2021 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [e91c8823fa](https://linux-hardware.org/?probe=e91c8823fa) | Apr 28, 2021 |
| Intel         | S5520HC E26045-407          | Server      | [61dfd26e01](https://linux-hardware.org/?probe=61dfd26e01) | Apr 24, 2021 |
| GPD           | MicroPC                     | Notebook    | [1169a84e36](https://linux-hardware.org/?probe=1169a84e36) | Apr 24, 2021 |
| Intel         | S5520HC E26045-407          | Server      | [28bf977c65](https://linux-hardware.org/?probe=28bf977c65) | Apr 24, 2021 |
| ONE-NETBOO... | A1                          | Notebook    | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Pegatron      | Benicia                     | Desktop     | [517b7af416](https://linux-hardware.org/?probe=517b7af416) | Apr 22, 2021 |
| HP            | Pavilion 17                 | Notebook    | [b5353a5537](https://linux-hardware.org/?probe=b5353a5537) | Apr 22, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| HP            | Pavilion 17                 | Notebook    | [eb45979ba4](https://linux-hardware.org/?probe=eb45979ba4) | Apr 19, 2021 |
| Dell          | Vostro 1014                 | Notebook    | [84a1787483](https://linux-hardware.org/?probe=84a1787483) | Apr 18, 2021 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [289a9d70d9](https://linux-hardware.org/?probe=289a9d70d9) | Apr 17, 2021 |
| Fujitsu Si... | D2840-A1 S26361-D2840-A1    | Desktop     | [d5310b7f74](https://linux-hardware.org/?probe=d5310b7f74) | Apr 15, 2021 |
| Packard Be... | EasyNote SB87               | Notebook    | [342ca9babb](https://linux-hardware.org/?probe=342ca9babb) | Apr 15, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [21501b34c2](https://linux-hardware.org/?probe=21501b34c2) | Apr 15, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | Notebook    | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [37502c4abe](https://linux-hardware.org/?probe=37502c4abe) | Apr 12, 2021 |
| Unknown       | NF-MCP61                    | Desktop     | [265d75e8f5](https://linux-hardware.org/?probe=265d75e8f5) | Apr 12, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [416997431c](https://linux-hardware.org/?probe=416997431c) | Apr 11, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9fc394df40](https://linux-hardware.org/?probe=9fc394df40) | Apr 10, 2021 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [a0e1e8da67](https://linux-hardware.org/?probe=a0e1e8da67) | Apr 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [33f5b55ba6](https://linux-hardware.org/?probe=33f5b55ba6) | Apr 09, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c2aed97877](https://linux-hardware.org/?probe=c2aed97877) | Apr 08, 2021 |
| HP            | 15                          | Notebook    | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [946c22503a](https://linux-hardware.org/?probe=946c22503a) | Apr 07, 2021 |
| HP            | ProBook 4530s               | Notebook    | [91397a0024](https://linux-hardware.org/?probe=91397a0024) | Apr 07, 2021 |
| HP            | ProBook 4530s               | Notebook    | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1d9693a3dc](https://linux-hardware.org/?probe=1d9693a3dc) | Apr 05, 2021 |
| Gigabyte      | B450M H                     | Desktop     | [d1a51a8680](https://linux-hardware.org/?probe=d1a51a8680) | Apr 04, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [16218d28da](https://linux-hardware.org/?probe=16218d28da) | Apr 04, 2021 |
| Dell          | Precision 5550              | Notebook    | [fb83e2c0e0](https://linux-hardware.org/?probe=fb83e2c0e0) | Apr 04, 2021 |
| Dell          | Precision 5550              | Notebook    | [bf3982f88a](https://linux-hardware.org/?probe=bf3982f88a) | Apr 04, 2021 |
| Dell          | Latitude E6410              | Notebook    | [297aaeb4ac](https://linux-hardware.org/?probe=297aaeb4ac) | Apr 03, 2021 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [4a94a9d35a](https://linux-hardware.org/?probe=4a94a9d35a) | Apr 02, 2021 |
| Gigabyte      | P31-S3G                     | Desktop     | [8600b9ee23](https://linux-hardware.org/?probe=8600b9ee23) | Apr 02, 2021 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [9afaeda84f](https://linux-hardware.org/?probe=9afaeda84f) | Apr 01, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [db1ca65bed](https://linux-hardware.org/?probe=db1ca65bed) | Apr 01, 2021 |
| Unknown       | Unknown                     | All in one  | [a8185511a2](https://linux-hardware.org/?probe=a8185511a2) | Apr 01, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| Pegatron      | Benicia                     | Desktop     | [4e2a1c50d1](https://linux-hardware.org/?probe=4e2a1c50d1) | Apr 01, 2021 |
| HP            | 1632                        | Desktop     | [c6df0e432e](https://linux-hardware.org/?probe=c6df0e432e) | Mar 31, 2021 |
| HP            | 3397                        | Desktop     | [e5812883ce](https://linux-hardware.org/?probe=e5812883ce) | Mar 31, 2021 |
| Dell          | Latitude E7250              | Notebook    | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1509fc7671](https://linux-hardware.org/?probe=1509fc7671) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | Notebook    | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| HP            | 1632                        | Desktop     | [50fc7fcff6](https://linux-hardware.org/?probe=50fc7fcff6) | Mar 30, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [2140003dfe](https://linux-hardware.org/?probe=2140003dfe) | Mar 28, 2021 |
| Dell          | Latitude E7250              | Notebook    | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| Digibras      | NH4CU53                     | Notebook    | [da93e6d427](https://linux-hardware.org/?probe=da93e6d427) | Mar 27, 2021 |
| Metabox       | X170SM                      | Notebook    | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | Notebook    | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [419277b830](https://linux-hardware.org/?probe=419277b830) | Mar 26, 2021 |
| Acer          | Aspire 4740                 | Notebook    | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Supermicro    | X10SRM-TFA                  | Server      | [3fc4f3458f](https://linux-hardware.org/?probe=3fc4f3458f) | Mar 24, 2021 |
| Samsung       | 760XBE                      | Notebook    | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e9b0291347](https://linux-hardware.org/?probe=e9b0291347) | Mar 21, 2021 |
| Dell          | Latitude E6540              | Notebook    | [fe1f341842](https://linux-hardware.org/?probe=fe1f341842) | Mar 21, 2021 |
| Samsung       | 760XBE                      | Notebook    | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ba76425a1a](https://linux-hardware.org/?probe=ba76425a1a) | Mar 20, 2021 |
| HP            | 1497                        | Desktop     | [d35a7eef80](https://linux-hardware.org/?probe=d35a7eef80) | Mar 19, 2021 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [e4faf817fd](https://linux-hardware.org/?probe=e4faf817fd) | Mar 19, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9210657e45](https://linux-hardware.org/?probe=9210657e45) | Mar 17, 2021 |
| ASRock        | 960GM-S3 FX                 | Desktop     | [5784a74c50](https://linux-hardware.org/?probe=5784a74c50) | Mar 17, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [2b8f8e4cec](https://linux-hardware.org/?probe=2b8f8e4cec) | Mar 14, 2021 |
| Sony          | VPCEB1S1E                   | Notebook    | [528d0ef3a5](https://linux-hardware.org/?probe=528d0ef3a5) | Mar 12, 2021 |
| HP            | Pavilion 17                 | Notebook    | [c74bd609b2](https://linux-hardware.org/?probe=c74bd609b2) | Mar 10, 2021 |
| H61M          | 5123660003                  | Desktop     | [4aec213a10](https://linux-hardware.org/?probe=4aec213a10) | Mar 09, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2af8335e88](https://linux-hardware.org/?probe=2af8335e88) | Mar 09, 2021 |
| H61M          | 5123660003                  | Desktop     | [7a6ac13ee4](https://linux-hardware.org/?probe=7a6ac13ee4) | Mar 09, 2021 |
| MSI           | B85M-P33                    | Desktop     | [e7d2bb8e63](https://linux-hardware.org/?probe=e7d2bb8e63) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [957f68f2b7](https://linux-hardware.org/?probe=957f68f2b7) | Mar 08, 2021 |
| ASRock        | EP2C602-4L/D16              | Desktop     | [839bc4873c](https://linux-hardware.org/?probe=839bc4873c) | Mar 08, 2021 |
| Sony          | VGN-FZ4000E                 | Notebook    | [fabf3e783d](https://linux-hardware.org/?probe=fabf3e783d) | Mar 07, 2021 |
| MSI           | G41M-S01                    | Desktop     | [e375637dd3](https://linux-hardware.org/?probe=e375637dd3) | Mar 07, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [b5cf5849a1](https://linux-hardware.org/?probe=b5cf5849a1) | Mar 06, 2021 |
| Acer          | Aspire GX-785               | Desktop     | [f9bff3e5ad](https://linux-hardware.org/?probe=f9bff3e5ad) | Mar 06, 2021 |
| ASUSTek       | Z450LA                      | Notebook    | [7bd4f23045](https://linux-hardware.org/?probe=7bd4f23045) | Mar 05, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| HP            | 2B2C                        | Desktop     | [20c11c9bbc](https://linux-hardware.org/?probe=20c11c9bbc) | Mar 04, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [2ab61e6080](https://linux-hardware.org/?probe=2ab61e6080) | Mar 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [efdf3f9098](https://linux-hardware.org/?probe=efdf3f9098) | Mar 02, 2021 |
| Toshiba       | Satellite L350D             | Notebook    | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [7c1ac98fc7](https://linux-hardware.org/?probe=7c1ac98fc7) | Mar 02, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [f418cb6b18](https://linux-hardware.org/?probe=f418cb6b18) | Mar 01, 2021 |
| Lenovo        | ThinkCentre M90 5485WFL     | Desktop     | [47fadb4fa4](https://linux-hardware.org/?probe=47fadb4fa4) | Feb 27, 2021 |
| HP            | Pavilion g7                 | Notebook    | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [eb757aee01](https://linux-hardware.org/?probe=eb757aee01) | Feb 26, 2021 |
| Lenovo        | ThinkPad W530 24491E8       | Notebook    | [fcf9d9a8d2](https://linux-hardware.org/?probe=fcf9d9a8d2) | Feb 25, 2021 |
| Entroware     | Aether                      | Notebook    | [9e308b1fda](https://linux-hardware.org/?probe=9e308b1fda) | Feb 24, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [53ada57eb3](https://linux-hardware.org/?probe=53ada57eb3) | Feb 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Intel         | DG31PR AAD97573-306         | Desktop     | [e6e8f6870c](https://linux-hardware.org/?probe=e6e8f6870c) | Feb 22, 2021 |
| HP            | HDX 16                      | Notebook    | [214dc69b28](https://linux-hardware.org/?probe=214dc69b28) | Feb 22, 2021 |
| Unknown       | XH61X000.100                | Desktop     | [029de8905d](https://linux-hardware.org/?probe=029de8905d) | Feb 17, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [64fa49b9d3](https://linux-hardware.org/?probe=64fa49b9d3) | Feb 17, 2021 |
| HP            | Pavilion 17                 | Notebook    | [46033bbdfd](https://linux-hardware.org/?probe=46033bbdfd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| JINGSHA       | Unknown                     | Desktop     | [01ab676e78](https://linux-hardware.org/?probe=01ab676e78) | Feb 15, 2021 |
| Dell          | 08WKV3 A00                  | Desktop     | [5f126b3966](https://linux-hardware.org/?probe=5f126b3966) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | Notebook    | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| HP            | Unknown                     | Notebook    | [46be5bd9f4](https://linux-hardware.org/?probe=46be5bd9f4) | Feb 12, 2021 |
| Dell          | 03NVJ6 A00                  | Desktop     | [87f43dfecd](https://linux-hardware.org/?probe=87f43dfecd) | Feb 12, 2021 |
| Dell          | Latitude E6500              | Notebook    | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Latitude E6500              | Notebook    | [200b4ad049](https://linux-hardware.org/?probe=200b4ad049) | Feb 11, 2021 |
| Dell          | Studio 1747                 | Notebook    | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [bd107eb4ae](https://linux-hardware.org/?probe=bd107eb4ae) | Feb 10, 2021 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [fa48450d71](https://linux-hardware.org/?probe=fa48450d71) | Feb 09, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | Notebook    | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [bbff698cb8](https://linux-hardware.org/?probe=bbff698cb8) | Feb 09, 2021 |
| Lenovo        | U310                        | Notebook    | [8e7c82ea87](https://linux-hardware.org/?probe=8e7c82ea87) | Feb 08, 2021 |
| HP            | Unknown                     | Notebook    | [34a482168b](https://linux-hardware.org/?probe=34a482168b) | Feb 08, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [394af8312b](https://linux-hardware.org/?probe=394af8312b) | Feb 07, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [0e61287ad7](https://linux-hardware.org/?probe=0e61287ad7) | Feb 07, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ad3df90a2e](https://linux-hardware.org/?probe=ad3df90a2e) | Feb 06, 2021 |
| Dell          | Latitude E7250              | Notebook    | [2679c5b467](https://linux-hardware.org/?probe=2679c5b467) | Feb 05, 2021 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [b99d5ec5ca](https://linux-hardware.org/?probe=b99d5ec5ca) | Feb 04, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2d0dd3b08e](https://linux-hardware.org/?probe=2d0dd3b08e) | Feb 04, 2021 |
| Gateway       | DX4885                      | Desktop     | [48628b0b95](https://linux-hardware.org/?probe=48628b0b95) | Feb 03, 2021 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [e39393dcdb](https://linux-hardware.org/?probe=e39393dcdb) | Feb 02, 2021 |
| Sony          | VGN-FE41M                   | Notebook    | [c51a776cc5](https://linux-hardware.org/?probe=c51a776cc5) | Feb 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu MATE 20.04 | 612       | 48.61%  |
| Ubuntu MATE 18.04 | 259       | 20.57%  |
| Ubuntu MATE 22.04 | 145       | 11.52%  |
| Ubuntu MATE 20.10 | 53        | 4.21%   |
| Ubuntu MATE 19.10 | 48        | 3.81%   |
| Ubuntu MATE 21.10 | 45        | 3.57%   |
| Ubuntu MATE 21.04 | 42        | 3.34%   |
| Ubuntu MATE 22.10 | 21        | 1.67%   |
| Ubuntu MATE 16.04 | 20        | 1.59%   |
| Ubuntu MATE       | 6         | 0.48%   |
| Ubuntu MATE 19.04 | 2         | 0.16%   |
| Ubuntu MATE 18.10 | 2         | 0.16%   |
| Ubuntu MATE 17.04 | 2         | 0.16%   |
| Ubuntu MATE 16.10 | 1         | 0.08%   |
| Ubuntu MATE 15.04 | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Ubuntu MATE | 1215      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 56        | 4.03%   |
| 5.4.0-48-generic   | 44        | 3.16%   |
| 5.4.0-52-generic   | 35        | 2.52%   |
| 5.4.0-47-generic   | 31        | 2.23%   |
| 5.4.0-65-generic   | 23        | 1.65%   |
| 5.15.0-56-generic  | 23        | 1.65%   |
| 5.4.0-58-generic   | 19        | 1.37%   |
| 5.4.0-40-generic   | 18        | 1.29%   |
| 5.15.0-47-generic  | 18        | 1.29%   |
| 4.15.0-163-generic | 17        | 1.22%   |
| 5.4.0-45-generic   | 16        | 1.15%   |
| 5.3.0-46-generic   | 16        | 1.15%   |
| 5.3.0-40-generic   | 16        | 1.15%   |
| 5.8.0-48-generic   | 15        | 1.08%   |
| 5.15.0-48-generic  | 15        | 1.08%   |
| 5.15.0-46-generic  | 14        | 1.01%   |
| 5.4.0-94-generic   | 13        | 0.93%   |
| 5.3.0-42-generic   | 13        | 0.93%   |
| 5.11.0-40-generic  | 13        | 0.93%   |
| 5.8.0-50-generic   | 12        | 0.86%   |
| 5.4.0-81-generic   | 12        | 0.86%   |
| 5.4.0-56-generic   | 12        | 0.86%   |
| 5.15.0-52-generic  | 12        | 0.86%   |
| 5.4.0-26-generic   | 11        | 0.79%   |
| 5.15.0-43-generic  | 11        | 0.79%   |
| 5.15.0-40-generic  | 11        | 0.79%   |
| 5.4.0-89-generic   | 10        | 0.72%   |
| 5.4.0-74-generic   | 10        | 0.72%   |
| 5.4.0-66-generic   | 10        | 0.72%   |
| 5.4.0-31-generic   | 10        | 0.72%   |
| 5.4.0-29-generic   | 10        | 0.72%   |
| 5.3.0-51-generic   | 10        | 0.72%   |
| 5.3.0-28-generic   | 10        | 0.72%   |
| 5.13.0-39-generic  | 10        | 0.72%   |
| 5.13.0-30-generic  | 10        | 0.72%   |
| 5.8.0-59-generic   | 9         | 0.65%   |
| 5.4.0-80-generic   | 9         | 0.65%   |
| 5.4.0-70-generic   | 9         | 0.65%   |
| 5.4.0-54-generic   | 9         | 0.65%   |
| 5.3.0-45-generic   | 9         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 505       | 39.55%  |
| 5.15.0  | 156       | 12.22%  |
| 5.3.0   | 118       | 9.24%   |
| 5.8.0   | 105       | 8.22%   |
| 4.15.0  | 98        | 7.67%   |
| 5.11.0  | 96        | 7.52%   |
| 5.13.0  | 87        | 6.81%   |
| 5.19.0  | 19        | 1.49%   |
| 5.0.0   | 15        | 1.17%   |
| 5.14.0  | 8         | 0.63%   |
| 4.4.0   | 8         | 0.63%   |
| 5.10.27 | 4         | 0.31%   |
| 4.9.277 | 4         | 0.31%   |
| 4.18.0  | 4         | 0.31%   |
| 5.18.0  | 3         | 0.23%   |
| 5.17.0  | 3         | 0.23%   |
| 4.10.0  | 3         | 0.23%   |
| 5.4.2   | 2         | 0.16%   |
| 5.10.5  | 2         | 0.16%   |
| 5.10.0  | 2         | 0.16%   |
| 4.4.154 | 2         | 0.16%   |
| 6.0.8   | 1         | 0.08%   |
| 5.9.3   | 1         | 0.08%   |
| 5.9.1   | 1         | 0.08%   |
| 5.9.0   | 1         | 0.08%   |
| 5.8.17  | 1         | 0.08%   |
| 5.8.16  | 1         | 0.08%   |
| 5.7.6   | 1         | 0.08%   |
| 5.7.0   | 1         | 0.08%   |
| 5.6.7   | 1         | 0.08%   |
| 5.6.5   | 1         | 0.08%   |
| 5.5.5   | 1         | 0.08%   |
| 5.5.11  | 1         | 0.08%   |
| 5.4.167 | 1         | 0.08%   |
| 5.17.1  | 1         | 0.08%   |
| 5.16.0  | 1         | 0.08%   |
| 5.15.6  | 1         | 0.08%   |
| 5.15.34 | 1         | 0.08%   |
| 5.15.29 | 1         | 0.08%   |
| 5.15.27 | 1         | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 508       | 39.81%  |
| 5.15    | 161       | 12.62%  |
| 5.3     | 118       | 9.25%   |
| 5.8     | 107       | 8.39%   |
| 4.15    | 98        | 7.68%   |
| 5.11    | 96        | 7.52%   |
| 5.13    | 87        | 6.82%   |
| 5.19    | 19        | 1.49%   |
| 5.0     | 15        | 1.18%   |
| 4.4     | 11        | 0.86%   |
| 5.14    | 8         | 0.63%   |
| 5.10    | 8         | 0.63%   |
| 4.9     | 5         | 0.39%   |
| 5.17    | 4         | 0.31%   |
| 4.18    | 4         | 0.31%   |
| 5.9     | 3         | 0.24%   |
| 5.18    | 3         | 0.24%   |
| 4.14    | 3         | 0.24%   |
| 4.10    | 3         | 0.24%   |
| 5.7     | 2         | 0.16%   |
| 5.6     | 2         | 0.16%   |
| 5.5     | 2         | 0.16%   |
| 5.12    | 2         | 0.16%   |
| 6.0     | 1         | 0.08%   |
| 5.16    | 1         | 0.08%   |
| 4.8     | 1         | 0.08%   |
| 4.13    | 1         | 0.08%   |
| 3.19    | 1         | 0.08%   |
| 3.16    | 1         | 0.08%   |
| 3.14    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1091      | 89.79%  |
| i686    | 71        | 5.84%   |
| aarch64 | 43        | 3.54%   |
| armv7l  | 9         | 0.74%   |
| ppc     | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 1188      | 97.78%  |
| Cinnamon   | 7         | 0.58%   |
| X-Cinnamon | 5         | 0.41%   |
| KDE5       | 5         | 0.41%   |
| GNOME      | 4         | 0.33%   |
| Trinity    | 2         | 0.16%   |
| Budgie     | 2         | 0.16%   |
| XFCE       | 1         | 0.08%   |
| i3         | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1181      | 97.04%  |
| Tty     | 22        | 1.81%   |
| Wayland | 14        | 1.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 448       | 35.56%  |
| LightDM | 433       | 34.37%  |
| TDM     | 309       | 24.52%  |
| GDM     | 36        | 2.86%   |
| GDM3    | 27        | 2.14%   |
| SDDM    | 4         | 0.32%   |
| SLiM    | 3         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 406       | 33.14%  |
| pt_BR   | 113       | 9.22%   |
| de_DE   | 103       | 8.41%   |
| fr_FR   | 99        | 8.08%   |
| en_GB   | 63        | 5.14%   |
| it_IT   | 52        | 4.24%   |
| es_ES   | 38        | 3.1%    |
| ru_RU   | 36        | 2.94%   |
| Unknown | 35        | 2.86%   |
| el_GR   | 34        | 2.78%   |
| en_CA   | 27        | 2.2%    |
| C       | 27        | 2.2%    |
| en_AU   | 22        | 1.8%    |
| es_AR   | 15        | 1.22%   |
| pl_PL   | 14        | 1.14%   |
| hu_HU   | 11        | 0.9%    |
| nl_NL   | 9         | 0.73%   |
| en_IN   | 9         | 0.73%   |
| de_CH   | 8         | 0.65%   |
| fi_FI   | 7         | 0.57%   |
| es_PE   | 7         | 0.57%   |
| ru_UA   | 6         | 0.49%   |
| cs_CZ   | 6         | 0.49%   |
| sv_SE   | 5         | 0.41%   |
| es_VE   | 4         | 0.33%   |
| es_CL   | 4         | 0.33%   |
| en_PH   | 4         | 0.33%   |
| en_IL   | 4         | 0.33%   |
| de_AT   | 4         | 0.33%   |
| nl_BE   | 3         | 0.24%   |
| hr_HR   | 3         | 0.24%   |
| fr_CA   | 3         | 0.24%   |
| es_MX   | 3         | 0.24%   |
| ca_ES   | 3         | 0.24%   |
| zh_TW   | 2         | 0.16%   |
| zh_CN   | 2         | 0.16%   |
| pt_PT   | 2         | 0.16%   |
| ja_JP   | 2         | 0.16%   |
| fr_BE   | 2         | 0.16%   |
| es_GT   | 2         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 697       | 56.3%   |
| EFI  | 541       | 43.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1113      | 91.15%  |
| Overlay | 48        | 3.93%   |
| Zfs     | 17        | 1.39%   |
| Btrfs   | 17        | 1.39%   |
| Unknown | 9         | 0.74%   |
| Xfs     | 8         | 0.66%   |
| Ext3    | 3         | 0.25%   |
| Jfs     | 2         | 0.16%   |
| Aufs    | 2         | 0.16%   |
| ExX4    | 1         | 0.08%   |
| Ext2    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 549       | 44.31%  |
| GPT     | 443       | 35.75%  |
| MBR     | 247       | 19.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1055      | 85.77%  |
| Yes       | 175       | 14.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 822       | 66.67%  |
| Yes       | 411       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 201       | 16.54%  |
| ASUSTek Computer        | 187       | 15.39%  |
| Dell                    | 168       | 13.83%  |
| Lenovo                  | 144       | 11.85%  |
| Gigabyte Technology     | 66        | 5.43%   |
| MSI                     | 62        | 5.1%    |
| Acer                    | 50        | 4.12%   |
| Raspberry Pi Foundation | 37        | 3.05%   |
| ASRock                  | 34        | 2.8%    |
| Intel                   | 32        | 2.63%   |
| Toshiba                 | 25        | 2.06%   |
| Unknown                 | 15        | 1.23%   |
| Samsung Electronics     | 13        | 1.07%   |
| Apple                   | 13        | 1.07%   |
| Sony                    | 12        | 0.99%   |
| Fujitsu                 | 11        | 0.91%   |
| Medion                  | 9         | 0.74%   |
| Hardkernel              | 9         | 0.74%   |
| Notebook                | 7         | 0.58%   |
| Supermicro              | 6         | 0.49%   |
| Pegatron                | 5         | 0.41%   |
| Packard Bell            | 5         | 0.41%   |
| Positivo                | 4         | 0.33%   |
| Fujitsu Siemens         | 4         | 0.33%   |
| ECS                     | 4         | 0.33%   |
| Biostar                 | 4         | 0.33%   |
| TUXEDO                  | 3         | 0.25%   |
| TrekStor                | 3         | 0.25%   |
| Quanta                  | 3         | 0.25%   |
| LG Electronics          | 3         | 0.25%   |
| eMachines               | 3         | 0.25%   |
| Clevo                   | 3         | 0.25%   |
| Chuwi                   | 3         | 0.25%   |
| AZW                     | 3         | 0.25%   |
| Wortmann AG             | 2         | 0.16%   |
| TYAN Computer           | 2         | 0.16%   |
| System76                | 2         | 0.16%   |
| Semp Toshiba            | 2         | 0.16%   |
| Rockchip                | 2         | 0.16%   |
| NEC Computers           | 2         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 25        | 2.06%   |
| RPi Raspberry Pi 4 Model B Rev 1.4  | 11        | 0.91%   |
| HP Compaq Elite 8300 SFF            | 10        | 0.82%   |
| ASUS All Series                     | 10        | 0.82%   |
| RPi Raspberry Pi 4 Model B Rev 1.2  | 8         | 0.66%   |
| HP ProDesk 600 G1 SFF               | 8         | 0.66%   |
| HP Compaq 6005 Pro SFF PC           | 8         | 0.66%   |
| RPi Raspberry Pi 4 Model B Rev 1.1  | 7         | 0.58%   |
| RPi Raspberry Pi                    | 7         | 0.58%   |
| HP Pavilion g6                      | 6         | 0.49%   |
| Dell Latitude E6410                 | 6         | 0.49%   |
| HP Pavilion dv7                     | 5         | 0.41%   |
| Hardkernel ODROID-N2Plus            | 5         | 0.41%   |
| Dell OptiPlex 3010                  | 5         | 0.41%   |
| Dell Latitude E6420                 | 5         | 0.41%   |
| MSI MS-7817                         | 4         | 0.33%   |
| Lenovo IdeaPad 3 15IIL05 81WE       | 4         | 0.33%   |
| HP Notebook                         | 4         | 0.33%   |
| HP Compaq 6200 Pro SFF PC           | 4         | 0.33%   |
| Dell OptiPlex GX520                 | 4         | 0.33%   |
| Dell OptiPlex 755                   | 4         | 0.33%   |
| Dell OptiPlex 390                   | 4         | 0.33%   |
| Dell OptiPlex 360                   | 4         | 0.33%   |
| ASUS M5A97 R2.0                     | 4         | 0.33%   |
| ASRock B450M Pro4                   | 4         | 0.33%   |
| TrekStor Surfbook A13B              | 3         | 0.25%   |
| RPi Raspberry Pi 3 Model B Rev 1.2  | 3         | 0.25%   |
| HP Compaq 8000 Elite SFF PC         | 3         | 0.25%   |
| Gigabyte B450M DS3H                 | 3         | 0.25%   |
| Dell Precision M4800                | 3         | 0.25%   |
| Dell OptiPlex GX620                 | 3         | 0.25%   |
| Dell OptiPlex 330                   | 3         | 0.25%   |
| Dell Latitude E6500                 | 3         | 0.25%   |
| ASUS M5A78L-M/USB3                  | 3         | 0.25%   |
| Toshiba Satellite C660              | 2         | 0.16%   |
| Toshiba Satellite A200              | 2         | 0.16%   |
| Supermicro H8DG6/H8DGi              | 2         | 0.16%   |
| Sony VGN-CR120E                     | 2         | 0.16%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 2         | 0.16%   |
| MSI MS-7C94                         | 2         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 65        | 5.35%   |
| Dell OptiPlex            | 49        | 4.03%   |
| HP Compaq                | 42        | 3.46%   |
| Dell Latitude            | 41        | 3.37%   |
| RPi Raspberry            | 37        | 3.05%   |
| HP Pavilion              | 35        | 2.88%   |
| Acer Aspire              | 35        | 2.88%   |
| Lenovo IdeaPad           | 29        | 2.39%   |
| Dell Precision           | 25        | 2.06%   |
| Unknown                  | 25        | 2.06%   |
| HP EliteBook             | 24        | 1.98%   |
| Toshiba Satellite        | 23        | 1.89%   |
| Dell Inspiron            | 21        | 1.73%   |
| ASUS PRIME               | 19        | 1.56%   |
| Lenovo ThinkCentre       | 16        | 1.32%   |
| HP ProBook               | 13        | 1.07%   |
| ASUS ROG                 | 13        | 1.07%   |
| HP ProDesk               | 10        | 0.82%   |
| Dell XPS                 | 10        | 0.82%   |
| ASUS All                 | 10        | 0.82%   |
| Fujitsu LIFEBOOK         | 9         | 0.74%   |
| Dell Vostro              | 9         | 0.74%   |
| HP ZBook                 | 7         | 0.58%   |
| HP Laptop                | 7         | 0.58%   |
| ASUS VivoBook            | 7         | 0.58%   |
| ASUS TUF                 | 7         | 0.58%   |
| Lenovo ThinkBook         | 6         | 0.49%   |
| HP 250                   | 6         | 0.49%   |
| ASUS M5A97               | 6         | 0.49%   |
| ASUS M5A78L-M            | 6         | 0.49%   |
| HP ENVY                  | 5         | 0.41%   |
| Hardkernel ODROID-N2Plus | 5         | 0.41%   |
| Acer TravelMate          | 5         | 0.41%   |
| Packard Bell EasyNote    | 4         | 0.33%   |
| MSI MS-7817              | 4         | 0.33%   |
| Lenovo IdeaPadFlex       | 4         | 0.33%   |
| HP Stream                | 4         | 0.33%   |
| HP ProLiant              | 4         | 0.33%   |
| HP Notebook              | 4         | 0.33%   |
| HP EliteDesk             | 4         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 120       | 9.88%   |
| 2012    | 110       | 9.05%   |
| 2020    | 104       | 8.56%   |
| 2018    | 100       | 8.23%   |
| 2013    | 93        | 7.65%   |
| 2019    | 76        | 6.26%   |
| 2010    | 72        | 5.93%   |
| 2014    | 71        | 5.84%   |
| 2009    | 65        | 5.35%   |
| 2008    | 65        | 5.35%   |
| 2021    | 61        | 5.02%   |
| 2017    | 58        | 4.77%   |
| 2015    | 57        | 4.69%   |
| 2016    | 48        | 3.95%   |
| 2007    | 37        | 3.05%   |
| Unknown | 35        | 2.88%   |
| 2006    | 22        | 1.81%   |
| 2005    | 12        | 0.99%   |
| 2022    | 7         | 0.58%   |
| 2004    | 1         | 0.08%   |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 604       | 49.71%  |
| Desktop        | 487       | 40.08%  |
| System on chip | 50        | 4.12%   |
| Mini pc        | 22        | 1.81%   |
| Convertible    | 16        | 1.32%   |
| Server         | 15        | 1.23%   |
| All in one     | 12        | 0.99%   |
| Tablet         | 9         | 0.74%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1143      | 93.61%  |
| Enabled  | 78        | 6.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1212      | 99.75%  |
| Yes  | 3         | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 326       | 26.57%  |
| 4.01-8.0        | 248       | 20.21%  |
| 8.01-16.0       | 192       | 15.65%  |
| 16.01-24.0      | 179       | 14.59%  |
| 32.01-64.0      | 96        | 7.82%   |
| 1.01-2.0        | 70        | 5.7%    |
| 64.01-256.0     | 48        | 3.91%   |
| 2.01-3.0        | 30        | 2.44%   |
| 0.51-1.0        | 19        | 1.55%   |
| 24.01-32.0      | 17        | 1.39%   |
| More than 256.0 | 1         | 0.08%   |
| 0.01-0.5        | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 460       | 35.25%  |
| 2.01-3.0   | 284       | 21.76%  |
| 0.51-1.0   | 190       | 14.56%  |
| 4.01-8.0   | 153       | 11.72%  |
| 3.01-4.0   | 142       | 10.88%  |
| 8.01-16.0  | 39        | 2.99%   |
| 0.01-0.5   | 21        | 1.61%   |
| 24.01-32.0 | 7         | 0.54%   |
| 16.01-24.0 | 5         | 0.38%   |
| 32.01-64.0 | 4         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 758       | 60.93%  |
| 2      | 306       | 24.6%   |
| 3      | 91        | 7.32%   |
| 4      | 41        | 3.3%    |
| 5      | 15        | 1.21%   |
| 6      | 10        | 0.8%    |
| 0      | 8         | 0.64%   |
| 7      | 6         | 0.48%   |
| 10     | 3         | 0.24%   |
| 11     | 2         | 0.16%   |
| 8      | 2         | 0.16%   |
| 12     | 1         | 0.08%   |
| 9      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 634       | 51.8%   |
| Yes       | 590       | 48.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1060      | 87.17%  |
| No        | 156       | 12.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 833       | 68.06%  |
| No        | 391       | 31.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 614       | 50.16%  |
| Yes       | 610       | 49.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 168       | 13.75%  |
| Germany     | 132       | 10.8%   |
| Brazil      | 132       | 10.8%   |
| France      | 108       | 8.84%   |
| Italy       | 66        | 5.4%    |
| UK          | 62        | 5.07%   |
| Russia      | 60        | 4.91%   |
| Spain       | 54        | 4.42%   |
| Greece      | 41        | 3.36%   |
| Canada      | 29        | 2.37%   |
| Australia   | 23        | 1.88%   |
| Netherlands | 20        | 1.64%   |
| Argentina   | 20        | 1.64%   |
| Switzerland | 17        | 1.39%   |
| Hungary     | 17        | 1.39%   |
| Ukraine     | 15        | 1.23%   |
| Poland      | 15        | 1.23%   |
| India       | 13        | 1.06%   |
| Finland     | 13        | 1.06%   |
| Belgium     | 13        | 1.06%   |
| Austria     | 12        | 0.98%   |
| Turkey      | 11        | 0.9%    |
| Czechia     | 11        | 0.9%    |
| Sweden      | 9         | 0.74%   |
| Romania     | 9         | 0.74%   |
| Norway      | 9         | 0.74%   |
| Mexico      | 8         | 0.65%   |
| Portugal    | 7         | 0.57%   |
| Peru        | 7         | 0.57%   |
| Chile       | 7         | 0.57%   |
| Indonesia   | 6         | 0.49%   |
| Croatia     | 6         | 0.49%   |
| Venezuela   | 5         | 0.41%   |
| Thailand    | 5         | 0.41%   |
| Taiwan      | 5         | 0.41%   |
| Denmark     | 5         | 0.41%   |
| Philippines | 4         | 0.33%   |
| Japan       | 4         | 0.33%   |
| Israel      | 4         | 0.33%   |
| Estonia     | 4         | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 75        | 5.85%   |
| Paris          | 23        | 1.79%   |
| Moscow         | 20        | 1.56%   |
| Thessaloniki   | 19        | 1.48%   |
| Berlin         | 17        | 1.33%   |
| Athens         | 17        | 1.33%   |
| St Petersburg  | 9         | 0.7%    |
| Rome           | 9         | 0.7%    |
| Budapest       | 8         | 0.62%   |
| Melbourne      | 7         | 0.55%   |
| Zurich         | 6         | 0.47%   |
| Manchester     | 6         | 0.47%   |
| Madrid         | 6         | 0.47%   |
| Kyiv           | 6         | 0.47%   |
| Hamburg        | 6         | 0.47%   |
| Amsterdam      | 6         | 0.47%   |
| Vienna         | 5         | 0.39%   |
| Rio de Janeiro | 5         | 0.39%   |
| Munich         | 5         | 0.39%   |
| Los Angeles    | 5         | 0.39%   |
| Helsinki       | 5         | 0.39%   |
| Barcelona      | 5         | 0.39%   |
| Southampton    | 4         | 0.31%   |
| Perth          | 4         | 0.31%   |
| Milan          | 4         | 0.31%   |
| Mannheim       | 4         | 0.31%   |
| Genoa          | 4         | 0.31%   |
| Essen          | 4         | 0.31%   |
| Ely            | 4         | 0.31%   |
| Cleveland      | 4         | 0.31%   |
| Bucharest      | 4         | 0.31%   |
| Brisbane       | 4         | 0.31%   |
| Bengaluru      | 4         | 0.31%   |
| Zagreb         | 3         | 0.23%   |
| Windsor        | 3         | 0.23%   |
| Vancouver      | 3         | 0.23%   |
| Toronto        | 3         | 0.23%   |
| Sydney         | 3         | 0.23%   |
| Stuttgart      | 3         | 0.23%   |
| Sneek          | 3         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 291       | 450    | 16.84%  |
| WDC                       | 281       | 415    | 16.26%  |
| Samsung Electronics       | 251       | 367    | 14.53%  |
| Toshiba                   | 114       | 155    | 6.6%    |
| Unknown                   | 109       | 143    | 6.31%   |
| Kingston                  | 99        | 119    | 5.73%   |
| SanDisk                   | 77        | 92     | 4.46%   |
| Hitachi                   | 71        | 84     | 4.11%   |
| Crucial                   | 63        | 87     | 3.65%   |
| Intel                     | 36        | 46     | 2.08%   |
| SK hynix                  | 34        | 43     | 1.97%   |
| A-DATA Technology         | 24        | 25     | 1.39%   |
| HGST                      | 18        | 24     | 1.04%   |
| China                     | 18        | 22     | 1.04%   |
| Fujitsu                   | 15        | 16     | 0.87%   |
| Phison                    | 14        | 15     | 0.81%   |
| Micron Technology         | 12        | 13     | 0.69%   |
| PNY                       | 11        | 12     | 0.64%   |
| KIOXIA                    | 10        | 11     | 0.58%   |
| Patriot                   | 8         | 10     | 0.46%   |
| Intenso                   | 8         | 11     | 0.46%   |
| SPCC                      | 7         | 12     | 0.41%   |
| Silicon Motion            | 7         | 8      | 0.41%   |
| Maxtor                    | 7         | 12     | 0.41%   |
| JMicron Technology        | 7         | 10     | 0.41%   |
| LITEON                    | 6         | 7      | 0.35%   |
| Transcend                 | 5         | 8      | 0.29%   |
| LITEONIT                  | 5         | 6      | 0.29%   |
| Apacer                    | 5         | 6      | 0.29%   |
| Netac                     | 4         | 4      | 0.23%   |
| Micron/Crucial Technology | 4         | 8      | 0.23%   |
| KingSpec                  | 4         | 5      | 0.23%   |
| Corsair                   | 4         | 5      | 0.23%   |
| SABRENT                   | 3         | 3      | 0.17%   |
| Plextor                   | 3         | 3      | 0.17%   |
| OCZ                       | 3         | 3      | 0.17%   |
| LaCie                     | 3         | 3      | 0.17%   |
| Hewlett-Packard           | 3         | 3      | 0.17%   |
| Unknown                   | 3         | 3      | 0.17%   |
| Verbatim                  | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 27        | 1.42%   |
| Seagate ST500DM002-1BD142 500GB     | 24        | 1.26%   |
| Unknown MMC Card  64GB              | 21        | 1.1%    |
| Kingston SA400S37120G 120GB SSD     | 20        | 1.05%   |
| Samsung SSD 860 EVO 500GB           | 15        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB            | 14        | 0.73%   |
| Kingston SA400S37240G 240GB SSD     | 14        | 0.73%   |
| Toshiba MQ01ABF050 500GB            | 12        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 0.63%   |
| Seagate ST2000DM008-2FR102 2TB      | 11        | 0.58%   |
| Seagate ST2000DM001-1ER164 2TB      | 11        | 0.58%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 0.58%   |
| Toshiba DT01ACA050 500GB            | 10        | 0.52%   |
| Seagate ST3500418AS 500GB           | 10        | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB      | 10        | 0.52%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 9         | 0.47%   |
| Unknown MMC Card  16GB              | 9         | 0.47%   |
| Unknown MMC Card  128GB             | 9         | 0.47%   |
| Toshiba DT01ACA100 1TB              | 9         | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB      | 9         | 0.47%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 0.47%   |
| WDC WD5000AAKX-003CA0 500GB         | 7         | 0.37%   |
| Toshiba MQ01ABD100 1TB              | 7         | 0.37%   |
| Toshiba DT01ACA200 2TB              | 7         | 0.37%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 0.37%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB      | 7         | 0.37%   |
| Seagate ST320LT007-9ZV142 320GB     | 7         | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 0.37%   |
| SanDisk SSD PLUS 480GB              | 7         | 0.37%   |
| SanDisk SDSSDA240G 240GB            | 7         | 0.37%   |
| Samsung SSD 850 EVO 250GB           | 7         | 0.37%   |
| Samsung NVMe SSD Drive 500GB        | 7         | 0.37%   |
| Crucial CT500MX500SSD1 500GB        | 7         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 6         | 0.31%   |
| WDC WD5000AAKX-083CA1 500GB         | 6         | 0.31%   |
| WDC WD10EZEX-00BN5A0 1TB            | 6         | 0.31%   |
| Toshiba MQ04ABF100 1TB              | 6         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 290       | 446    | 36.62%  |
| WDC                 | 235       | 345    | 29.67%  |
| Toshiba             | 95        | 131    | 11.99%  |
| Hitachi             | 71        | 84     | 8.96%   |
| Samsung Electronics | 41        | 52     | 5.18%   |
| HGST                | 18        | 24     | 2.27%   |
| Fujitsu             | 15        | 16     | 1.89%   |
| Unknown             | 7         | 10     | 0.88%   |
| Maxtor              | 6         | 10     | 0.76%   |
| IBM/Hitachi         | 2         | 2      | 0.25%   |
| ASMT109x            | 2         | 3      | 0.25%   |
| USB3.0              | 1         | 1      | 0.13%   |
| SAGE                | 1         | 1      | 0.13%   |
| LaCie               | 1         | 1      | 0.13%   |
| KESU                | 1         | 3      | 0.13%   |
| JMicron Technology  | 1         | 1      | 0.13%   |
| Inateck             | 1         | 1      | 0.13%   |
| Hewlett-Packard     | 1         | 1      | 0.13%   |
| DAS                 | 1         | 6      | 0.13%   |
| ASMT                | 1         | 2      | 0.13%   |
| Apricorn            | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 132       | 183    | 23.53%  |
| Kingston            | 85        | 99     | 15.15%  |
| SanDisk             | 62        | 74     | 11.05%  |
| Crucial             | 60        | 84     | 10.7%   |
| WDC                 | 33        | 44     | 5.88%   |
| Intel               | 21        | 29     | 3.74%   |
| A-DATA Technology   | 21        | 22     | 3.74%   |
| China               | 17        | 21     | 3.03%   |
| PNY                 | 11        | 12     | 1.96%   |
| Toshiba             | 8         | 10     | 1.43%   |
| SK hynix            | 7         | 9      | 1.25%   |
| Intenso             | 7         | 10     | 1.25%   |
| SPCC                | 6         | 10     | 1.07%   |
| Patriot             | 6         | 8      | 1.07%   |
| Transcend           | 5         | 8      | 0.89%   |
| LITEONIT            | 5         | 6      | 0.89%   |
| LITEON              | 5         | 6      | 0.89%   |
| Apacer              | 5         | 6      | 0.89%   |
| Micron Technology   | 4         | 5      | 0.71%   |
| KingSpec            | 4         | 5      | 0.71%   |
| Plextor             | 3         | 3      | 0.53%   |
| OCZ                 | 3         | 3      | 0.53%   |
| Netac               | 3         | 3      | 0.53%   |
| JMicron Technology  | 3         | 4      | 0.53%   |
| Verbatim            | 2         | 2      | 0.36%   |
| Vaseky              | 2         | 2      | 0.36%   |
| Team                | 2         | 2      | 0.36%   |
| Seagate             | 2         | 2      | 0.36%   |
| FORESEE             | 2         | 2      | 0.36%   |
| BAITITON            | 2         | 2      | 0.36%   |
| Argon               | 2         | 3      | 0.36%   |
| AMD                 | 2         | 2      | 0.36%   |
| WDC WDS2            | 1         | 1      | 0.18%   |
| Unknown             | 1         | 2      | 0.18%   |
| TO Exter            | 1         | 1      | 0.18%   |
| Super Talent        | 1         | 1      | 0.18%   |
| SMI                 | 1         | 1      | 0.18%   |
| Smart               | 1         | 1      | 0.18%   |
| RZX                 | 1         | 1      | 0.18%   |
| NGFF                | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 677       | 1141   | 43.54%  |
| SSD     | 494       | 713    | 31.77%  |
| NVMe    | 258       | 347    | 16.59%  |
| MMC     | 99        | 131    | 6.37%   |
| Unknown | 27        | 31     | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 973       | 1787   | 69.55%  |
| NVMe | 256       | 344    | 18.3%   |
| MMC  | 99        | 131    | 7.08%   |
| SAS  | 71        | 101    | 5.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 762       | 1095   | 61.06%  |
| 0.51-1.0   | 300       | 446    | 24.04%  |
| 1.01-2.0   | 104       | 167    | 8.33%   |
| 3.01-4.0   | 39        | 55     | 3.13%   |
| 4.01-10.0  | 26        | 54     | 2.08%   |
| 2.01-3.0   | 15        | 28     | 1.2%    |
| 10.01-20.0 | 2         | 9      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 320       | 25.38%  |
| 251-500        | 311       | 24.66%  |
| 501-1000       | 182       | 14.43%  |
| 1001-2000      | 106       | 8.41%   |
| 51-100         | 88        | 6.98%   |
| More than 3000 | 72        | 5.71%   |
| 21-50          | 58        | 4.6%    |
| 1-20           | 55        | 4.36%   |
| 2001-3000      | 41        | 3.25%   |
| Unknown        | 28        | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 433       | 33.44%  |
| 21-50          | 198       | 15.29%  |
| 101-250        | 181       | 13.98%  |
| 51-100         | 157       | 12.12%  |
| 251-500        | 115       | 8.88%   |
| 501-1000       | 78        | 6.02%   |
| 1001-2000      | 51        | 3.94%   |
| More than 3000 | 29        | 2.24%   |
| Unknown        | 28        | 2.16%   |
| 2001-3000      | 25        | 1.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 9         | 9      | 5.84%   |
| Seagate ST320LT007-9ZV142 320GB   | 5         | 5      | 3.25%   |
| WDC WD5000AAKX-083CA1 500GB       | 4         | 4      | 2.6%    |
| Seagate ST3500418AS 500GB         | 4         | 4      | 2.6%    |
| WDC WD5000AAKX-003CA0 500GB       | 2         | 2      | 1.3%    |
| WDC WD3200BEVT-60ZCT1 320GB       | 2         | 2      | 1.3%    |
| WDC WD2500AAKX-753CA1 250GB       | 2         | 2      | 1.3%    |
| WDC WD10EADS-00L5B1 1TB           | 2         | 4      | 1.3%    |
| Unknown MM0500EANCR 500GB         | 2         | 5      | 1.3%    |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 1.3%    |
| Seagate ST9500420AS 500GB         | 2         | 2      | 1.3%    |
| Seagate ST9320325AS 320GB         | 2         | 2      | 1.3%    |
| Seagate ST500LT012-9WS142 500GB   | 2         | 2      | 1.3%    |
| Seagate ST2000DM001-9YN164 2TB    | 2         | 3      | 1.3%    |
| Seagate ST1000LM049-2GH172 1TB    | 2         | 2      | 1.3%    |
| Seagate ST1000DM003-1CH162 1TB    | 2         | 2      | 1.3%    |
| Samsung Electronics HD502HJ 500GB | 2         | 2      | 1.3%    |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 1.3%    |
| Hitachi HTS545050B9A300 500GB     | 2         | 2      | 1.3%    |
| Hitachi HTS542516K9SA00 160GB     | 2         | 2      | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 1         | 1      | 0.65%   |
| WDC WD7500BPVX-22JC3T0 752GB      | 1         | 1      | 0.65%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 0.65%   |
| WDC WD7500BPVT-22A1YT0 752GB      | 1         | 1      | 0.65%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 0.65%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 0.65%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 0.65%   |
| WDC WD5000AAKS-00V1A0 500GB       | 1         | 1      | 0.65%   |
| WDC WD5000AADS-00S9B0 500GB       | 1         | 1      | 0.65%   |
| WDC WD40EFAX-68JH4N0 4TB          | 1         | 2      | 0.65%   |
| WDC WD3200BEKT-60V5T1 320GB       | 1         | 1      | 0.65%   |
| WDC WD3200AAJS-40VWA1 320GB       | 1         | 1      | 0.65%   |
| WDC WD30EFRX-68EUZN0 3TB          | 1         | 1      | 0.65%   |
| WDC WD2500YS-01SHB1 256GB         | 1         | 1      | 0.65%   |
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 0.65%   |
| WDC WD2500AAKX-75U6AA0 250GB      | 1         | 1      | 0.65%   |
| WDC WD2500AAJS-75M0A0 249GB       | 1         | 1      | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 1         | 1      | 0.65%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 2      | 0.65%   |
| WDC WD15EARS-00Z5B1 1TB           | 1         | 1      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 53     | 33.11%  |
| WDC                 | 37        | 45     | 24.5%   |
| Samsung Electronics | 13        | 17     | 8.61%   |
| Hitachi             | 11        | 11     | 7.28%   |
| Toshiba             | 8         | 8      | 5.3%    |
| Intel               | 5         | 6      | 3.31%   |
| Unknown             | 2         | 5      | 1.32%   |
| SanDisk             | 2         | 2      | 1.32%   |
| Maxtor              | 2         | 2      | 1.32%   |
| Kingston            | 2         | 2      | 1.32%   |
| Fujitsu             | 2         | 2      | 1.32%   |
| Crucial             | 2         | 2      | 1.32%   |
| China               | 2         | 2      | 1.32%   |
| A-DATA Technology   | 2         | 3      | 1.32%   |
| Vaseky              | 1         | 1      | 0.66%   |
| SK hynix            | 1         | 4      | 0.66%   |
| OCZ                 | 1         | 1      | 0.66%   |
| NGFF                | 1         | 1      | 0.66%   |
| Netac               | 1         | 1      | 0.66%   |
| IBM/Hitachi         | 1         | 1      | 0.66%   |
| HGST                | 1         | 2      | 0.66%   |
| Eluktro             | 1         | 1      | 0.66%   |
| DAS                 | 1         | 3      | 0.66%   |
| ASMT                | 1         | 2      | 0.66%   |
| Apricorn            | 1         | 1      | 0.66%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 53     | 40.65%  |
| WDC                 | 36        | 44     | 29.27%  |
| Hitachi             | 11        | 11     | 8.94%   |
| Toshiba             | 8         | 8      | 6.5%    |
| Samsung Electronics | 7         | 8      | 5.69%   |
| Unknown             | 2         | 5      | 1.63%   |
| Maxtor              | 2         | 2      | 1.63%   |
| Fujitsu             | 2         | 2      | 1.63%   |
| IBM/Hitachi         | 1         | 1      | 0.81%   |
| HGST                | 1         | 2      | 0.81%   |
| DAS                 | 1         | 3      | 0.81%   |
| ASMT                | 1         | 2      | 0.81%   |
| Apricorn            | 1         | 1      | 0.81%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 117       | 142    | 80.69%  |
| SSD  | 22        | 23     | 15.17%  |
| NVMe | 6         | 13     | 4.14%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 621       | 1227   | 46.73%  |
| Works    | 567       | 958    | 42.66%  |
| Malfunc  | 141       | 178    | 10.61%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 818       | 58.64%  |
| AMD                              | 217       | 15.56%  |
| Samsung Electronics              | 91        | 6.52%   |
| SanDisk                          | 35        | 2.51%   |
| Nvidia                           | 25        | 1.79%   |
| SK hynix                         | 24        | 1.72%   |
| ASMedia Technology               | 23        | 1.65%   |
| Phison Electronics               | 22        | 1.58%   |
| Marvell Technology Group         | 19        | 1.36%   |
| Kingston Technology Company      | 18        | 1.29%   |
| Toshiba America Info Systems     | 15        | 1.08%   |
| Silicon Motion                   | 13        | 0.93%   |
| JMicron Technology               | 10        | 0.72%   |
| Silicon Integrated Systems [SiS] | 8         | 0.57%   |
| Micron Technology                | 8         | 0.57%   |
| KIOXIA                           | 8         | 0.57%   |
| Micron/Crucial Technology        | 7         | 0.5%    |
| VIA Technologies                 | 6         | 0.43%   |
| ADATA Technology                 | 6         | 0.43%   |
| LSI Logic / Symbios Logic        | 4         | 0.29%   |
| Union Memory (Shenzhen)          | 3         | 0.22%   |
| Solid State Storage Technology   | 3         | 0.22%   |
| Realtek Semiconductor            | 2         | 0.14%   |
| Hewlett-Packard                  | 2         | 0.14%   |
| Silicon Image                    | 1         | 0.07%   |
| Lite-On Technology               | 1         | 0.07%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| Integrated Technology Express    | 1         | 0.07%   |
| Broadcom / LSI                   | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |
| 3ware                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 117       | 7.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 67        | 4.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 61        | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 47        | 2.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 45        | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 44        | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 43        | 2.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41        | 2.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 39        | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 37        | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 36        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 31        | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 26        | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 25        | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 25        | 1.5%    |
| Samsung NVMe SSD Controller 980                                                         | 23        | 1.38%   |
| AMD 400 Series Chipset SATA Controller                                                  | 23        | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 22        | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 22        | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 20        | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 18        | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 18        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 18        | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 17        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 16        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 16        | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16        | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15        | 0.9%    |
| Nvidia MCP61 SATA Controller                                                            | 15        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 15        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 15        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 15        | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 14        | 0.84%   |
| Intel SATA Controller [RAID mode]                                                       | 14        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 13        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 13        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 13        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 854       | 59.47%  |
| NVMe | 254       | 17.69%  |
| IDE  | 241       | 16.78%  |
| RAID | 79        | 5.5%    |
| SAS  | 6         | 0.42%   |
| SCSI | 2         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 905       | 74.49%  |
| AMD          | 256       | 21.07%  |
| ARM          | 52        | 4.28%   |
| PowerBook5,6 | 1         | 0.08%   |
| CentaurHauls | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 43        | 3.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 10        | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 0.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.66%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.58%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 0.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 7         | 0.58%   |
| AMD Phenom II X4 B97 Processor                | 7         | 0.58%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.49%   |
| Intel Pentium 4 CPU 3.00GHz                   | 6         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.49%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 0.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.49%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 6         | 0.49%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 6         | 0.49%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 6         | 0.49%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6         | 0.49%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.49%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 6         | 0.49%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 6         | 0.49%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.41%   |
| Intel Pentium D CPU 2.80GHz                   | 5         | 0.41%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 5         | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 0.41%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 5         | 0.41%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 5         | 0.41%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 5         | 0.41%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.41%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 5         | 0.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 237       | 19.51%  |
| Intel Core i7                  | 187       | 15.39%  |
| Intel Core i3                  | 97        | 7.98%   |
| Other                          | 95        | 7.82%   |
| Intel Celeron                  | 66        | 5.43%   |
| Intel Core 2 Duo               | 62        | 5.1%    |
| Intel Pentium                  | 45        | 3.7%    |
| AMD Ryzen 5                    | 44        | 3.62%   |
| Intel Xeon                     | 32        | 2.63%   |
| Intel Atom                     | 29        | 2.39%   |
| AMD Ryzen 7                    | 27        | 2.22%   |
| AMD FX                         | 21        | 1.73%   |
| Intel Pentium Dual-Core        | 20        | 1.65%   |
| Intel Core 2 Quad              | 18        | 1.48%   |
| AMD Athlon II X2               | 18        | 1.48%   |
| AMD Ryzen 3                    | 14        | 1.15%   |
| AMD Phenom II X4               | 13        | 1.07%   |
| AMD Ryzen 9                    | 11        | 0.91%   |
| Intel Pentium 4                | 10        | 0.82%   |
| Intel Genuine                  | 10        | 0.82%   |
| AMD A6                         | 10        | 0.82%   |
| AMD A4                         | 9         | 0.74%   |
| Intel Core i9                  | 8         | 0.66%   |
| Intel Core 2                   | 8         | 0.66%   |
| AMD A8                         | 8         | 0.66%   |
| AMD Athlon                     | 7         | 0.58%   |
| Intel Pentium Dual             | 6         | 0.49%   |
| Intel Pentium D                | 6         | 0.49%   |
| ARM BCM                        | 6         | 0.49%   |
| Intel Pentium Silver           | 5         | 0.41%   |
| AMD E                          | 5         | 0.41%   |
| AMD Athlon II X4               | 5         | 0.41%   |
| AMD Athlon 64 X2               | 5         | 0.41%   |
| AMD Turion 64 X2 Mobile        | 4         | 0.33%   |
| AMD Ryzen 7 PRO                | 4         | 0.33%   |
| AMD E1                         | 4         | 0.33%   |
| AMD A10                        | 4         | 0.33%   |
| Intel Core m3                  | 3         | 0.25%   |
| Intel Core Duo                 | 3         | 0.25%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 528       | 43.35%  |
| 4       | 469       | 38.51%  |
| 6       | 81        | 6.65%   |
| 8       | 53        | 4.35%   |
| 1       | 43        | 3.53%   |
| 16      | 12        | 0.99%   |
| 12      | 10        | 0.82%   |
| 3       | 9         | 0.74%   |
| 10      | 6         | 0.49%   |
| 24      | 3         | 0.25%   |
| 32      | 2         | 0.16%   |
| Unknown | 2         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1189      | 97.78%  |
| 2       | 24        | 1.97%   |
| 4       | 2         | 0.16%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 661       | 54.27%  |
| 1       | 555       | 45.57%  |
| Unknown | 2         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1152      | 94.74%  |
| Unknown        | 36        | 2.96%   |
| 32-bit         | 25        | 2.06%   |
| 64-bit         | 3         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 270       | 21.55%  |
| 0x306a9    | 89        | 7.1%    |
| 0x206a7    | 81        | 6.46%   |
| 0x306c3    | 70        | 5.59%   |
| 0x1067a    | 53        | 4.23%   |
| 0x906e9    | 23        | 1.84%   |
| 0x806ec    | 23        | 1.84%   |
| 0x6fd      | 23        | 1.84%   |
| 0x010000c8 | 23        | 1.84%   |
| 0x806c1    | 22        | 1.76%   |
| 0x506e3    | 22        | 1.76%   |
| 0x906ea    | 20        | 1.6%    |
| 0x20655    | 20        | 1.6%    |
| 0x806ea    | 19        | 1.52%   |
| 0x40651    | 19        | 1.52%   |
| 0x306d4    | 18        | 1.44%   |
| 0x30678    | 18        | 1.44%   |
| 0x806e9    | 17        | 1.36%   |
| 0x406c4    | 15        | 1.2%    |
| 0x10676    | 15        | 1.2%    |
| 0x706e5    | 13        | 1.04%   |
| 0x08108109 | 12        | 0.96%   |
| 0x06000852 | 12        | 0.96%   |
| 0x406e3    | 11        | 0.88%   |
| 0x706a1    | 10        | 0.8%    |
| 0x6fb      | 10        | 0.8%    |
| 0x106e5    | 10        | 0.8%    |
| 0x08701021 | 10        | 0.8%    |
| 0x06001119 | 10        | 0.8%    |
| 0x20652    | 9         | 0.72%   |
| 0x08600106 | 9         | 0.72%   |
| 0xa0671    | 8         | 0.64%   |
| 0x906ed    | 8         | 0.64%   |
| 0x106ca    | 8         | 0.64%   |
| 0xf41      | 7         | 0.56%   |
| 0x806d1    | 7         | 0.56%   |
| 0x0a50000c | 7         | 0.56%   |
| 0x08108102 | 7         | 0.56%   |
| 0x08101016 | 7         | 0.56%   |
| 0x07030105 | 7         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 144       | 11.83%  |
| Haswell          | 110       | 9.04%   |
| SandyBridge      | 104       | 8.55%   |
| IvyBridge        | 102       | 8.38%   |
| Penryn           | 80        | 6.57%   |
| Unknown          | 66        | 5.42%   |
| K10              | 49        | 4.03%   |
| Core             | 49        | 4.03%   |
| Silvermont       | 43        | 3.53%   |
| Skylake          | 42        | 3.45%   |
| Zen 2            | 39        | 3.2%    |
| Westmere         | 37        | 3.04%   |
| Piledriver       | 30        | 2.47%   |
| Zen+             | 29        | 2.38%   |
| Icelake          | 28        | 2.3%    |
| Zen              | 24        | 1.97%   |
| TigerLake        | 24        | 1.97%   |
| Broadwell        | 23        | 1.89%   |
| Goldmont plus    | 20        | 1.64%   |
| NetBurst         | 18        | 1.48%   |
| Nehalem          | 18        | 1.48%   |
| K8 Hammer        | 18        | 1.48%   |
| CometLake        | 18        | 1.48%   |
| Bonnell          | 17        | 1.4%    |
| Zen 3            | 16        | 1.31%   |
| P6               | 13        | 1.07%   |
| Excavator        | 13        | 1.07%   |
| Bobcat           | 9         | 0.74%   |
| Puma             | 8         | 0.66%   |
| Goldmont         | 7         | 0.58%   |
| Bulldozer        | 5         | 0.41%   |
| K8 & K10 hybrid  | 4         | 0.33%   |
| Jaguar           | 4         | 0.33%   |
| Steamroller      | 2         | 0.16%   |
| K10 Llano        | 2         | 0.16%   |
| Alderlake Hybrid | 2         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 693       | 51.68%  |
| Nvidia                           | 327       | 24.38%  |
| AMD                              | 301       | 22.45%  |
| Silicon Integrated Systems [SiS] | 6         | 0.45%   |
| Matrox Electronics Systems       | 6         | 0.45%   |
| ASPEED Technology                | 5         | 0.37%   |
| VIA Technologies                 | 3         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 69        | 4.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 59        | 4.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 2.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 24        | 1.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 1.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 1.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 1.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22        | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.52%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.45%   |
| Intel UHD Graphics 620                                                                   | 19        | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 1.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.23%   |
| AMD Renoir                                                                               | 17        | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 1.16%   |
| Intel HD Graphics 630                                                                    | 15        | 1.09%   |
| Nvidia GT218 [GeForce 210]                                                               | 14        | 1.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.01%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 0.94%   |
| Intel HD Graphics 530                                                                    | 13        | 0.94%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.87%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 12        | 0.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 0.87%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 11        | 0.8%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 0.8%    |
| AMD RS880 [Radeon HD 4200]                                                               | 11        | 0.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 0.72%   |
| Intel HD Graphics 620                                                                    | 10        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.72%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 9         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 538       | 44.17%  |
| 1 x AMD                  | 240       | 19.7%   |
| 1 x Nvidia               | 199       | 16.34%  |
| Intel + Nvidia           | 110       | 9.03%   |
| Other                    | 53        | 4.35%   |
| Intel + AMD              | 31        | 2.55%   |
| 2 x AMD                  | 13        | 1.07%   |
| AMD + Nvidia             | 11        | 0.9%    |
| 1 x SiS                  | 6         | 0.49%   |
| 1 x VIA                  | 3         | 0.25%   |
| Nvidia + Matrox          | 3         | 0.25%   |
| 1 x Matrox               | 3         | 0.25%   |
| 2 x Nvidia               | 2         | 0.16%   |
| 1 x ASPEED               | 2         | 0.16%   |
| AMD + ASPEED             | 2         | 0.16%   |
| Nvidia + ASPEED          | 1         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 930       | 75.92%  |
| Proprietary | 202       | 16.49%  |
| Unknown     | 93        | 7.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 695       | 56.18%  |
| 1.01-2.0   | 162       | 13.1%   |
| 0.01-0.5   | 154       | 12.45%  |
| 0.51-1.0   | 102       | 8.25%   |
| 3.01-4.0   | 70        | 5.66%   |
| 7.01-8.0   | 29        | 2.34%   |
| 5.01-6.0   | 13        | 1.05%   |
| 2.01-3.0   | 7         | 0.57%   |
| 16.01-24.0 | 2         | 0.16%   |
| 8.01-16.0  | 2         | 0.16%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 194       | 15.2%   |
| AU Optronics            | 128       | 10.03%  |
| Dell                    | 120       | 9.4%    |
| LG Display              | 104       | 8.15%   |
| Chimei Innolux          | 87        | 6.82%   |
| Goldstar                | 75        | 5.88%   |
| BOE                     | 73        | 5.72%   |
| Hewlett-Packard         | 56        | 4.39%   |
| Acer                    | 47        | 3.68%   |
| Philips                 | 37        | 2.9%    |
| BenQ                    | 27        | 2.12%   |
| AOC                     | 26        | 2.04%   |
| Ancor Communications    | 25        | 1.96%   |
| Chi Mei Optoelectronics | 22        | 1.72%   |
| ViewSonic               | 16        | 1.25%   |
| Sharp                   | 15        | 1.18%   |
| Lenovo                  | 14        | 1.1%    |
| Unknown                 | 13        | 1.02%   |
| PANDA                   | 13        | 1.02%   |
| Apple                   | 13        | 1.02%   |
| Iiyama                  | 11        | 0.86%   |
| Sony                    | 9         | 0.71%   |
| LG Electronics          | 9         | 0.71%   |
| LG Philips              | 8         | 0.63%   |
| ASUSTek Computer        | 8         | 0.63%   |
| NEC Computers           | 7         | 0.55%   |
| HannStar                | 7         | 0.55%   |
| Eizo                    | 7         | 0.55%   |
| Vizio                   | 6         | 0.47%   |
| InfoVision              | 5         | 0.39%   |
| Fujitsu Siemens         | 5         | 0.39%   |
| Toshiba                 | 4         | 0.31%   |
| Packard Bell            | 4         | 0.31%   |
| Medion                  | 4         | 0.31%   |
| Gateway                 | 4         | 0.31%   |
| Belinea                 | 4         | 0.31%   |
| RTK                     | 3         | 0.24%   |
| Insignia                | 3         | 0.24%   |
| InnoLux Display         | 3         | 0.24%   |
| Hitachi                 | 3         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                        | 31        | 2.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.45%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 0.38%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                        | 5         | 0.38%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch            | 4         | 0.3%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.3%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.3%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 4         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.3%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.3%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 4         | 0.3%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 3         | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.23%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 3         | 0.23%   |
| Hewlett-Packard L1740 HWP2648 1280x1024 338x270mm 17.0-inch              | 3         | 0.23%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 3         | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 3         | 0.23%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 3         | 0.23%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 3         | 0.23%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                    | 3         | 0.23%   |
| Dell E1916H DELF064 1366x768 410x230mm 18.5-inch                         | 3         | 0.23%   |
| Dell 1708FP DEL4024 1280x1024 338x270mm 17.0-inch                        | 3         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch         | 3         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 3         | 0.23%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.23%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.23%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 3         | 0.23%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 3         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 463       | 37.86%  |
| 1366x768 (WXGA)    | 235       | 19.22%  |
| 1280x1024 (SXGA)   | 111       | 9.08%   |
| 1600x900 (HD+)     | 58        | 4.74%   |
| 3840x2160 (4K)     | 56        | 4.58%   |
| 1680x1050 (WSXGA+) | 42        | 3.43%   |
| 1440x900 (WXGA+)   | 39        | 3.19%   |
| 2560x1440 (QHD)    | 36        | 2.94%   |
| 1920x1200 (WUXGA)  | 32        | 2.62%   |
| 1280x800 (WXGA)    | 32        | 2.62%   |
| 1360x768           | 23        | 1.88%   |
| Unknown            | 16        | 1.31%   |
| 1024x600           | 11        | 0.9%    |
| 1600x1200          | 9         | 0.74%   |
| 3440x1440          | 8         | 0.65%   |
| 3840x1080          | 7         | 0.57%   |
| 2560x1600          | 6         | 0.49%   |
| 2560x1080          | 4         | 0.33%   |
| 1024x768 (XGA)     | 4         | 0.33%   |
| 2160x1440          | 3         | 0.25%   |
| 1280x720 (HD)      | 3         | 0.25%   |
| 3200x1800 (QHD+)   | 2         | 0.16%   |
| 2880x1800          | 2         | 0.16%   |
| 1920x540           | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 6400x1080          | 1         | 0.08%   |
| 5840x1440          | 1         | 0.08%   |
| 5760x2160          | 1         | 0.08%   |
| 5040x1050          | 1         | 0.08%   |
| 4240x1440          | 1         | 0.08%   |
| 3840x2400          | 1         | 0.08%   |
| 3840x1200          | 1         | 0.08%   |
| 3200x1080          | 1         | 0.08%   |
| 3000x1920          | 1         | 0.08%   |
| 2880x900           | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2640x1024          | 1         | 0.08%   |
| 1680x945           | 1         | 0.08%   |
| 1280x854           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 275       | 21.7%   |
| 17      | 141       | 11.13%  |
| 14      | 90        | 7.1%    |
| 13      | 86        | 6.79%   |
| 24      | 82        | 6.47%   |
| 23      | 77        | 6.08%   |
| 21      | 77        | 6.08%   |
| Unknown | 73        | 5.76%   |
| 27      | 67        | 5.29%   |
| 19      | 50        | 3.95%   |
| 18      | 38        | 3%      |
| 31      | 30        | 2.37%   |
| 22      | 28        | 2.21%   |
| 12      | 21        | 1.66%   |
| 20      | 20        | 1.58%   |
| 11      | 17        | 1.34%   |
| 10      | 15        | 1.18%   |
| 34      | 11        | 0.87%   |
| 84      | 8         | 0.63%   |
| 72      | 8         | 0.63%   |
| 40      | 7         | 0.55%   |
| 46      | 5         | 0.39%   |
| 32      | 5         | 0.39%   |
| 54      | 4         | 0.32%   |
| 33      | 4         | 0.32%   |
| 16      | 4         | 0.32%   |
| 52      | 3         | 0.24%   |
| 42      | 3         | 0.24%   |
| 25      | 3         | 0.24%   |
| 36      | 2         | 0.16%   |
| 74      | 1         | 0.08%   |
| 65      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 57      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 48      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 41      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 29      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 472       | 37.76%  |
| 501-600     | 209       | 16.72%  |
| 401-500     | 180       | 14.4%   |
| 351-400     | 111       | 8.88%   |
| 201-300     | 95        | 7.6%    |
| Unknown     | 73        | 5.84%   |
| 601-700     | 40        | 3.2%    |
| 701-800     | 22        | 1.76%   |
| 1001-1500   | 18        | 1.44%   |
| 1501-2000   | 17        | 1.36%   |
| 801-900     | 8         | 0.64%   |
| 901-1000    | 4         | 0.32%   |
| 101-200     | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 811       | 69.32%  |
| 16/10   | 149       | 12.74%  |
| 5/4     | 99        | 8.46%   |
| Unknown | 62        | 5.3%    |
| 4/3     | 17        | 1.45%   |
| 3/2     | 14        | 1.2%    |
| 21/9    | 11        | 0.94%   |
| 6/5     | 4         | 0.34%   |
| 32/9    | 1         | 0.09%   |
| 1.96    | 1         | 0.09%   |
| 0.62    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 269       | 21.43%  |
| 201-250        | 203       | 16.18%  |
| 81-90          | 137       | 10.92%  |
| 141-150        | 107       | 8.53%   |
| 151-200        | 92        | 7.33%   |
| Unknown        | 73        | 5.82%   |
| 301-350        | 67        | 5.34%   |
| 121-130        | 53        | 4.22%   |
| 351-500        | 51        | 4.06%   |
| 251-300        | 38        | 3.03%   |
| 71-80          | 36        | 2.87%   |
| More than 1000 | 28        | 2.23%   |
| 61-70          | 21        | 1.67%   |
| 501-1000       | 21        | 1.67%   |
| 51-60          | 17        | 1.35%   |
| 41-50          | 15        | 1.2%    |
| 131-140        | 14        | 1.12%   |
| 111-120        | 6         | 0.48%   |
| 91-100         | 6         | 0.48%   |
| 1-40           | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 483       | 39.49%  |
| 101-120       | 309       | 25.27%  |
| 121-160       | 258       | 21.1%   |
| Unknown       | 73        | 5.97%   |
| 161-240       | 47        | 3.84%   |
| 1-50          | 38        | 3.11%   |
| More than 240 | 15        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 977       | 79.82%  |
| 2     | 169       | 13.81%  |
| 0     | 59        | 4.82%   |
| 3     | 18        | 1.47%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 615       | 35.22%  |
| Intel                             | 542       | 31.04%  |
| Qualcomm Atheros                  | 190       | 10.88%  |
| Broadcom                          | 113       | 6.47%   |
| Broadcom Limited                  | 36        | 2.06%   |
| Marvell Technology Group          | 24        | 1.37%   |
| Ralink                            | 23        | 1.32%   |
| Ralink Technology                 | 22        | 1.26%   |
| Nvidia                            | 21        | 1.2%    |
| TP-Link                           | 20        | 1.15%   |
| Qualcomm Atheros Communications   | 10        | 0.57%   |
| ASIX Electronics                  | 9         | 0.52%   |
| Microchip Technology              | 8         | 0.46%   |
| Silicon Integrated Systems [SiS]  | 7         | 0.4%    |
| Sierra Wireless                   | 7         | 0.4%    |
| MediaTek                          | 6         | 0.34%   |
| D-Link                            | 6         | 0.34%   |
| Attansic Technology               | 6         | 0.34%   |
| ASUSTek Computer                  | 6         | 0.34%   |
| Aquantia                          | 6         | 0.34%   |
| Xiaomi                            | 5         | 0.29%   |
| NetGear                           | 5         | 0.29%   |
| Ericsson Business Mobile Networks | 5         | 0.29%   |
| VIA Technologies                  | 4         | 0.23%   |
| Huawei Technologies               | 4         | 0.23%   |
| Edimax Technology                 | 4         | 0.23%   |
| Samsung Electronics               | 3         | 0.17%   |
| Hewlett-Packard                   | 3         | 0.17%   |
| D-Link System                     | 3         | 0.17%   |
| QLogic                            | 2         | 0.11%   |
| Microsoft                         | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| JMicron Technology                | 2         | 0.11%   |
| Dell                              | 2         | 0.11%   |
| Belkin Components                 | 2         | 0.11%   |
| ZyDAS                             | 1         | 0.06%   |
| U.S. Robotics                     | 1         | 0.06%   |
| U-Blox                            | 1         | 0.06%   |
| Tenda                             | 1         | 0.06%   |
| Sitecom Europe                    | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 412       | 20.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 90        | 4.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 65        | 3.16%   |
| Intel Wi-Fi 6 AX200                                               | 33        | 1.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 1.56%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 28        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 1.36%   |
| Intel Wireless 7265                                               | 27        | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 1.22%   |
| Intel Wireless 7260                                               | 25        | 1.22%   |
| Intel Wireless 8265 / 8275                                        | 24        | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 1.12%   |
| Intel Wireless 3165                                               | 22        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 21        | 1.02%   |
| Intel Wi-Fi 6 AX201                                               | 20        | 0.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 15        | 0.73%   |
| Intel Ethernet Controller I225-V                                  | 15        | 0.73%   |
| Nvidia MCP61 Ethernet                                             | 14        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 13        | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.58%   |
| Intel Wireless 8260                                               | 12        | 0.58%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.54%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.54%   |
| Intel Centrino Advanced-N 6235                                    | 11        | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 10        | 0.49%   |
| Realtek 802.11ac NIC                                              | 10        | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 374       | 42.26%  |
| Realtek Semiconductor           | 157       | 17.74%  |
| Qualcomm Atheros                | 150       | 16.95%  |
| Broadcom                        | 55        | 6.21%   |
| Ralink                          | 23        | 2.6%    |
| Broadcom Limited                | 23        | 2.6%    |
| Ralink Technology               | 22        | 2.49%   |
| TP-Link                         | 20        | 2.26%   |
| Qualcomm Atheros Communications | 10        | 1.13%   |
| Sierra Wireless                 | 7         | 0.79%   |
| ASUSTek Computer                | 6         | 0.68%   |
| NetGear                         | 5         | 0.56%   |
| MediaTek                        | 5         | 0.56%   |
| Edimax Technology               | 4         | 0.45%   |
| D-Link                          | 4         | 0.45%   |
| Microsoft                       | 2         | 0.23%   |
| Linksys                         | 2         | 0.23%   |
| Dell                            | 2         | 0.23%   |
| Belkin Components               | 2         | 0.23%   |
| ZyDAS                           | 1         | 0.11%   |
| Xiaomi                          | 1         | 0.11%   |
| U.S. Robotics                   | 1         | 0.11%   |
| Tenda                           | 1         | 0.11%   |
| Sitecom Europe                  | 1         | 0.11%   |
| Quectel Wireless Solutions      | 1         | 0.11%   |
| Qualcomm                        | 1         | 0.11%   |
| IMC Networks                    | 1         | 0.11%   |
| Hewlett-Packard                 | 1         | 0.11%   |
| Gemtek                          | 1         | 0.11%   |
| Fibocom                         | 1         | 0.11%   |
| AVM                             | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 33        | 3.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 32        | 3.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 28        | 3.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 3.15%   |
| Intel Wireless 7265                                                     | 27        | 3.04%   |
| Intel Wireless 7260                                                     | 25        | 2.81%   |
| Intel Wireless 8265 / 8275                                              | 24        | 2.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 2.59%   |
| Intel Wireless 3165                                                     | 22        | 2.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 2.36%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 14        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.46%   |
| Intel Wireless 8260                                                     | 12        | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.24%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 1.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 10        | 1.12%   |
| Realtek 802.11ac NIC                                                    | 10        | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.01%   |
| Intel Wireless 3160                                                     | 9         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                         | 8         | 0.9%    |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 8         | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 8         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 8         | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 547       | 49.37%  |
| Intel                            | 313       | 28.25%  |
| Broadcom                         | 64        | 5.78%   |
| Qualcomm Atheros                 | 61        | 5.51%   |
| Marvell Technology Group         | 24        | 2.17%   |
| Nvidia                           | 21        | 1.9%    |
| Broadcom Limited                 | 14        | 1.26%   |
| ASIX Electronics                 | 9         | 0.81%   |
| Microchip Technology             | 8         | 0.72%   |
| Silicon Integrated Systems [SiS] | 6         | 0.54%   |
| Attansic Technology              | 6         | 0.54%   |
| Aquantia                         | 6         | 0.54%   |
| Xiaomi                           | 4         | 0.36%   |
| VIA Technologies                 | 4         | 0.36%   |
| Samsung Electronics              | 3         | 0.27%   |
| Huawei Technologies              | 3         | 0.27%   |
| D-Link System                    | 3         | 0.27%   |
| QLogic                           | 2         | 0.18%   |
| JMicron Technology               | 2         | 0.18%   |
| D-Link                           | 2         | 0.18%   |
| Netchip Technology               | 1         | 0.09%   |
| Mellanox Technologies            | 1         | 0.09%   |
| MediaTek                         | 1         | 0.09%   |
| Lenovo                           | 1         | 0.09%   |
| DisplayLink                      | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 412       | 36.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 90        | 7.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 65        | 5.69%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 2.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 1.49%   |
| Intel I211 Gigabit Network Connection                             | 15        | 1.31%   |
| Intel Ethernet Controller I225-V                                  | 15        | 1.31%   |
| Nvidia MCP61 Ethernet                                             | 14        | 1.22%   |
| Intel Ethernet Connection (2) I219-V                              | 14        | 1.22%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.05%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 1.05%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 0.79%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.79%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 7         | 0.61%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.61%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express           | 7         | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.52%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.52%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 6         | 0.52%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 6         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.44%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 5         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1057      | 55.37%  |
| WiFi     | 832       | 43.58%  |
| Modem    | 18        | 0.94%   |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 647       | 52.69%  |
| Ethernet | 581       | 47.31%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 620       | 50.74%  |
| 1     | 506       | 41.41%  |
| 0     | 64        | 5.24%   |
| 3     | 21        | 1.72%   |
| 4     | 7         | 0.57%   |
| 6     | 2         | 0.16%   |
| 14    | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1054      | 85.9%   |
| Yes     | 172       | 14.02%  |
| Unknown | 1         | 0.08%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 285       | 45.75%  |
| Realtek Semiconductor           | 59        | 9.47%   |
| Broadcom                        | 53        | 8.51%   |
| Qualcomm Atheros Communications | 46        | 7.38%   |
| Cambridge Silicon Radio         | 44        | 7.06%   |
| IMC Networks                    | 24        | 3.85%   |
| Dell                            | 20        | 3.21%   |
| Lite-On Technology              | 17        | 2.73%   |
| Foxconn / Hon Hai               | 14        | 2.25%   |
| Apple                           | 14        | 2.25%   |
| Hewlett-Packard                 | 10        | 1.61%   |
| ASUSTek Computer                | 9         | 1.44%   |
| Ralink                          | 7         | 1.12%   |
| Toshiba                         | 5         | 0.8%    |
| Ralink Technology               | 2         | 0.32%   |
| Integrated System Solution      | 2         | 0.32%   |
| Foxconn International           | 2         | 0.32%   |
| Belkin Components               | 2         | 0.32%   |
| Alps Electric                   | 2         | 0.32%   |
| Unknown                         | 1         | 0.16%   |
| TRENDnet                        | 1         | 0.16%   |
| Qcom                            | 1         | 0.16%   |
| MediaTek                        | 1         | 0.16%   |
| Conwise Technology              | 1         | 0.16%   |
| Chicony Electronics             | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 115       | 18.46%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 50        | 8.03%   |
| Intel AX201 Bluetooth                               | 48        | 7.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 44        | 7.06%   |
| Realtek Bluetooth Radio                             | 37        | 5.94%   |
| Intel AX200 Bluetooth                               | 32        | 5.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 2.73%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 14        | 2.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 2.09%   |
| IMC Networks Bluetooth Device                       | 12        | 1.93%   |
| Dell DW375 Bluetooth Module                         | 12        | 1.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 1.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 1.44%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 1.44%   |
| Ralink RT3290 Bluetooth                             | 7         | 1.12%   |
| IMC Networks Bluetooth Radio                        | 7         | 1.12%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 1.12%   |
| Lite-On Bluetooth Device                            | 6         | 0.96%   |
| Intel AX210 Bluetooth                               | 6         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.96%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 6         | 0.96%   |
| Apple Bluetooth HCI                                 | 6         | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.8%    |
| Broadcom HP Portable SoftSailing                    | 5         | 0.8%    |
| Realtek RTL8723B Bluetooth                          | 4         | 0.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.64%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.64%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.48%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter    | 3         | 0.48%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.48%   |
| Broadcom BCM2045 Bluetooth                          | 3         | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.48%   |
| ASUS Bluetooth Device                               | 3         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 863       | 54.72%  |
| AMD                                            | 300       | 19.02%  |
| Nvidia                                         | 263       | 16.68%  |
| C-Media Electronics                            | 29        | 1.84%   |
| Logitech                                       | 9         | 0.57%   |
| Creative Labs                                  | 9         | 0.57%   |
| Silicon Integrated Systems [SiS]               | 8         | 0.51%   |
| Realtek Semiconductor                          | 7         | 0.44%   |
| JMTek                                          | 7         | 0.44%   |
| GN Netcom                                      | 6         | 0.38%   |
| Generalplus Technology                         | 6         | 0.38%   |
| Corsair                                        | 5         | 0.32%   |
| ASUSTek Computer                               | 5         | 0.32%   |
| VIA Technologies                               | 4         | 0.25%   |
| Kingston Technology                            | 4         | 0.25%   |
| Razer USA                                      | 3         | 0.19%   |
| Plantronics                                    | 3         | 0.19%   |
| Hewlett-Packard                                | 3         | 0.19%   |
| Creative Technology                            | 3         | 0.19%   |
| Tenx Technology                                | 2         | 0.13%   |
| Sony                                           | 2         | 0.13%   |
| Meizu                                          | 2         | 0.13%   |
| Lenovo                                         | 2         | 0.13%   |
| Focusrite-Novation                             | 2         | 0.13%   |
| Dell                                           | 2         | 0.13%   |
| D&M Holdings (Denon/Marantz)                   | 2         | 0.13%   |
| Conexant Systems                               | 2         | 0.13%   |
| Cambridge Silicon Radio                        | 2         | 0.13%   |
| BR25                                           | 2         | 0.13%   |
| BEHRINGER International                        | 2         | 0.13%   |
| Alesis                                         | 2         | 0.13%   |
| XMOS                                           | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting           | 1         | 0.06%   |
| Texas Instruments                              | 1         | 0.06%   |
| SmartAction                                    | 1         | 0.06%   |
| Siemens Information and Communication Products | 1         | 0.06%   |
| ONN                                            | 1         | 0.06%   |
| No brand                                       | 1         | 0.06%   |
| Micro Star International                       | 1         | 0.06%   |
| Medeli Electronics                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 100       | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 97        | 5.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 76        | 4.1%    |
| AMD Family 17h/19h HD Audio Controller                                     | 72        | 3.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 71        | 3.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 65        | 3.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 61        | 3.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 52        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 45        | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 37        | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 34        | 1.83%   |
| AMD FCH Azalia Controller                                                  | 30        | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 27        | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 27        | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 26        | 1.4%    |
| AMD Starship/Matisse HD Audio Controller                                   | 26        | 1.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 24        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 23        | 1.24%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 22        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                              | 22        | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 22        | 1.19%   |
| Nvidia High Definition Audio Controller                                    | 20        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 19        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 18        | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 18        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 17        | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 17        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 16        | 0.86%   |
| Nvidia MCP61 High Definition Audio                                         | 15        | 0.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 14        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 14        | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 14        | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 14        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 164       | 19.09%  |
| SK hynix                                         | 136       | 15.83%  |
| Kingston                                         | 121       | 14.09%  |
| Unknown                                          | 108       | 12.57%  |
| Micron Technology                                | 71        | 8.27%   |
| Crucial                                          | 56        | 6.52%   |
| Corsair                                          | 43        | 5.01%   |
| G.Skill                                          | 27        | 3.14%   |
| Ramaxel Technology                               | 19        | 2.21%   |
| Nanya Technology                                 | 18        | 2.1%    |
| Elpida                                           | 14        | 1.63%   |
| Unknown (ABCD)                                   | 12        | 1.4%    |
| Smart                                            | 11        | 1.28%   |
| A-DATA Technology                                | 9         | 1.05%   |
| Team                                             | 6         | 0.7%    |
| Teikon                                           | 5         | 0.58%   |
| Patriot                                          | 5         | 0.58%   |
| Unknown                                          | 4         | 0.47%   |
| Qimonda                                          | 3         | 0.35%   |
| HBS                                              | 3         | 0.35%   |
| Transcend                                        | 2         | 0.23%   |
| Silicon Power                                    | 2         | 0.23%   |
| Netlist                                          | 2         | 0.23%   |
| Goodram                                          | 2         | 0.23%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.12%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.12%   |
| Unknown (0x0C26)                                 | 1         | 0.12%   |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.12%   |
| Unifosa                                          | 1         | 0.12%   |
| Toshiba                                          | 1         | 0.12%   |
| Timetec                                          | 1         | 0.12%   |
| Neo Forza                                        | 1         | 0.12%   |
| Kreton                                           | 1         | 0.12%   |
| Goldenmars                                       | 1         | 0.12%   |
| Golden Empire                                    | 1         | 0.12%   |
| GeIL                                             | 1         | 0.12%   |
| Eluktro                                          | 1         | 0.12%   |
| Atermiter                                        | 1         | 0.12%   |
| ASint Technology                                 | 1         | 0.12%   |
| Apacer                                           | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.65%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.65%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.54%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.54%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 5         | 0.54%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.54%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                    | 5         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 4         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.43%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.43%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s                     | 4         | 0.43%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 4         | 0.43%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 4         | 0.43%   |
| Unknown                                                          | 4         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.33%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 0.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 3         | 0.33%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 3         | 0.33%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s            | 3         | 0.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.33%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 307       | 41.32%  |
| DDR4    | 269       | 36.2%   |
| DDR2    | 57        | 7.67%   |
| SDRAM   | 29        | 3.9%    |
| LPDDR4  | 23        | 3.1%    |
| Unknown | 23        | 3.1%    |
| DDR     | 15        | 2.02%   |
| LPDDR3  | 14        | 1.88%   |
| DRAM    | 3         | 0.4%    |
| DDR5    | 2         | 0.27%   |
| LPDDR5  | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 401       | 54.12%  |
| DIMM         | 297       | 40.08%  |
| Row Of Chips | 39        | 5.26%   |
| Chip         | 4         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 255       | 31.72%  |
| 8192  | 245       | 30.47%  |
| 2048  | 135       | 16.79%  |
| 16384 | 102       | 12.69%  |
| 1024  | 31        | 3.86%   |
| 32768 | 28        | 3.48%   |
| 512   | 5         | 0.62%   |
| 1536  | 1         | 0.12%   |
| 256   | 1         | 0.12%   |
| 32    | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 189       | 23.86%  |
| 3200    | 94        | 11.87%  |
| 2667    | 84        | 10.61%  |
| 1333    | 78        | 9.85%   |
| 2400    | 62        | 7.83%   |
| 1334    | 31        | 3.91%   |
| 2133    | 29        | 3.66%   |
| 667     | 29        | 3.66%   |
| 800     | 28        | 3.54%   |
| Unknown | 24        | 3.03%   |
| 1066    | 14        | 1.77%   |
| 3266    | 11        | 1.39%   |
| 1067    | 10        | 1.26%   |
| 533     | 10        | 1.26%   |
| 3600    | 8         | 1.01%   |
| 1867    | 8         | 1.01%   |
| 4199    | 7         | 0.88%   |
| 3400    | 6         | 0.76%   |
| 2048    | 6         | 0.76%   |
| 4267    | 5         | 0.63%   |
| 2933    | 5         | 0.63%   |
| 3000    | 4         | 0.51%   |
| 2666    | 4         | 0.51%   |
| 49926   | 3         | 0.38%   |
| 3800    | 3         | 0.38%   |
| 3466    | 3         | 0.38%   |
| 2800    | 3         | 0.38%   |
| 975     | 3         | 0.38%   |
| 400     | 3         | 0.38%   |
| 266     | 3         | 0.38%   |
| 8400    | 2         | 0.25%   |
| 3866    | 2         | 0.25%   |
| 3733    | 2         | 0.25%   |
| 3100    | 2         | 0.25%   |
| 1866    | 2         | 0.25%   |
| 1648    | 2         | 0.25%   |
| 6400    | 1         | 0.13%   |
| 6000    | 1         | 0.13%   |
| 4800    | 1         | 0.13%   |
| 4000    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 15        | 29.41%  |
| Brother Industries     | 8         | 15.69%  |
| Samsung Electronics    | 7         | 13.73%  |
| Seiko Epson            | 5         | 9.8%    |
| Canon                  | 5         | 9.8%    |
| Dymo-CoStar            | 4         | 7.84%   |
| QinHeng Electronics    | 2         | 3.92%   |
| Prolific Technology    | 1         | 1.96%   |
| Panasonic (Matsushita) | 1         | 1.96%   |
| Lexmark International  | 1         | 1.96%   |
| Graphtec America       | 1         | 1.96%   |
| BIXOLON                | 1         | 1.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Brother Printer                            | 3         | 5.77%   |
| Seiko Epson Printer                        | 2         | 3.85%   |
| Samsung SCX-4200 series                    | 2         | 3.85%   |
| Samsung M2020 Series                       | 2         | 3.85%   |
| QinHeng CH340S                             | 2         | 3.85%   |
| HP LaserJet Professional P 1102w           | 2         | 3.85%   |
| HP Deskjet F4500 series                    | 2         | 3.85%   |
| Dymo-CoStar LabelWriter 450                | 2         | 3.85%   |
| Seiko Epson XP-4100 Series                 | 1         | 1.92%   |
| Seiko Epson WF-2010 Series                 | 1         | 1.92%   |
| Seiko Epson L312 Series                    | 1         | 1.92%   |
| Samsung M2070 Series                       | 1         | 1.92%   |
| Samsung CLX-8380 Series                    | 1         | 1.92%   |
| Samsung CLX-4190 Series                    | 1         | 1.92%   |
| Prolific PL2305 Parallel Port              | 1         | 1.92%   |
| Panasonic (Matsushita) KX-MB2130RU         | 1         | 1.92%   |
| Lexmark International InkJet Color Printer | 1         | 1.92%   |
| HP Officejet 4500 G510a-f                  | 1         | 1.92%   |
| HP LaserJet Professional P1102w            | 1         | 1.92%   |
| HP LaserJet 1022                           | 1         | 1.92%   |
| HP LaserJet 1020                           | 1         | 1.92%   |
| HP DeskJet F300 series                     | 1         | 1.92%   |
| HP DeskJet 845c                            | 1         | 1.92%   |
| HP Deskjet 3050 J610 series                | 1         | 1.92%   |
| HP DeskJet 2700 series                     | 1         | 1.92%   |
| HP DeskJet 2620 All-in-One Printer         | 1         | 1.92%   |
| HP DeskJet 2130 series                     | 1         | 1.92%   |
| HP color LaserJet 4650                     | 1         | 1.92%   |
| Graphtec America Graphtec Printer          | 1         | 1.92%   |
| Dymo-CoStar LabelWriter 310                | 1         | 1.92%   |
| Dymo-CoStar DYMO LabelWriter 320           | 1         | 1.92%   |
| Canon PIXMA MG2500 Series                  | 1         | 1.92%   |
| Canon Pixma iP4500 Printer                 | 1         | 1.92%   |
| Canon LiDE 400                             | 1         | 1.92%   |
| Canon LBP7010C/7018C                       | 1         | 1.92%   |
| Canon LaserShot LBP-1120 Printer           | 1         | 1.92%   |
| Brother MFC-L2710DN series                 | 1         | 1.92%   |
| Brother HL-3170CDW series                  | 1         | 1.92%   |
| Brother HL-3140CW series                   | 1         | 1.92%   |
| Brother HL-1440 Laser Printer              | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 6         | 46.15%  |
| Seiko Epson                 | 4         | 30.77%  |
| Hewlett-Packard             | 2         | 15.38%  |
| Acer Peripherals (now BenQ) | 1         | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                              | 2         | 15.38%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]     | 1         | 7.69%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]    | 1         | 7.69%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo] | 1         | 7.69%   |
| Seiko Epson ES-D400 [GT-S80]                         | 1         | 7.69%   |
| HP ScanJet G4010                                     | 1         | 7.69%   |
| HP ScanJet 4370                                      | 1         | 7.69%   |
| Canon CanoScan N1240U/LiDE 30                        | 1         | 7.69%   |
| Canon CanoScan LIDE 25                               | 1         | 7.69%   |
| Canon CanoScan LiDE 210                              | 1         | 7.69%   |
| Canon CanoScan LiDE 120                              | 1         | 7.69%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U          | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 164       | 25.47%  |
| Acer                                   | 54        | 8.39%   |
| Microdia                               | 51        | 7.92%   |
| Logitech                               | 43        | 6.68%   |
| IMC Networks                           | 43        | 6.68%   |
| Realtek Semiconductor                  | 37        | 5.75%   |
| Sunplus Innovation Technology          | 31        | 4.81%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.5%    |
| Quanta                                 | 23        | 3.57%   |
| Suyin                                  | 18        | 2.8%    |
| Syntek                                 | 17        | 2.64%   |
| Ricoh                                  | 16        | 2.48%   |
| Apple                                  | 14        | 2.17%   |
| Silicon Motion                         | 11        | 1.71%   |
| Lite-On Technology                     | 11        | 1.71%   |
| Alcor Micro                            | 7         | 1.09%   |
| Samsung Electronics                    | 6         | 0.93%   |
| Z-Star Microelectronics                | 5         | 0.78%   |
| Luxvisions Innotech Limited            | 5         | 0.78%   |
| Importek                               | 5         | 0.78%   |
| Microsoft                              | 4         | 0.62%   |
| Lenovo                                 | 4         | 0.62%   |
| ARC International                      | 4         | 0.62%   |
| Primax Electronics                     | 3         | 0.47%   |
| KYE Systems (Mouse Systems)            | 3         | 0.47%   |
| Generalplus Technology                 | 3         | 0.47%   |
| Creative Technology                    | 3         | 0.47%   |
| ALi                                    | 3         | 0.47%   |
| Unknown                                | 2         | 0.31%   |
| Sunplus Technology                     | 2         | 0.31%   |
| Ruision                                | 2         | 0.31%   |
| DJJHFA1BIF5595                         | 2         | 0.31%   |
| DigiTech                               | 2         | 0.31%   |
| Cubeternet                             | 2         | 0.31%   |
| Aveo Technology                        | 2         | 0.31%   |
| Y Media                                | 1         | 0.16%   |
| U0AS01A-0                              | 1         | 0.16%   |
| Razer USA                              | 1         | 0.16%   |
| Novatel Wireless                       | 1         | 0.16%   |
| Nokia Mobile Phones                    | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony integrated camera                               | 27        | 4.17%   |
| Acer Integrated Camera                                  | 17        | 2.62%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 14        | 2.16%   |
| Microdia Integrated_Webcam_HD                           | 12        | 1.85%   |
| Chicony HD Webcam                                       | 12        | 1.85%   |
| Realtek Integrated_Webcam_HD                            | 11        | 1.7%    |
| Sunplus Integrated_Webcam_HD                            | 10        | 1.54%   |
| Syntek Integrated Camera                                | 9         | 1.39%   |
| Logitech Webcam C270                                    | 9         | 1.39%   |
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 1.39%   |
| Chicony USB2.0 Camera                                   | 9         | 1.39%   |
| IMC Networks Integrated Camera                          | 8         | 1.23%   |
| Realtek USB Camera                                      | 7         | 1.08%   |
| Microdia USB 2.0 Camera                                 | 7         | 1.08%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 7         | 1.08%   |
| Logitech HD Pro Webcam C920                             | 7         | 1.08%   |
| Chicony USB 2.0 Camera                                  | 7         | 1.08%   |
| Chicony HP HD Camera                                    | 7         | 1.08%   |
| Apple iPhone5/5C/5S/6                                   | 7         | 1.08%   |
| Acer BisonCam, NB Pro                                   | 7         | 1.08%   |
| Samsung Galaxy A5 (MTP)                                 | 6         | 0.93%   |
| Ricoh HD Webcam                                         | 6         | 0.93%   |
| Quanta HD User Facing                                   | 6         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 6         | 0.93%   |
| Acer Lenovo Integrated Webcam                           | 6         | 0.93%   |
| Microdia Webcam Vitade AF                               | 5         | 0.77%   |
| Microdia Integrated Webcam                              | 5         | 0.77%   |
| Chicony HP Webcam                                       | 5         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 5         | 0.77%   |
| Acer Lenovo EasyCamera                                  | 5         | 0.77%   |
| Suyin HP TrueVision HD Integrated Webcam                | 4         | 0.62%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 4         | 0.62%   |
| Quanta HP HD Camera                                     | 4         | 0.62%   |
| Chicony VGA Webcam                                      | 4         | 0.62%   |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 0.62%   |
| Chicony HP Truevision HD                                | 4         | 0.62%   |
| Chicony FJ Camera                                       | 4         | 0.62%   |
| ARC International Camera                                | 4         | 0.62%   |
| Apple Built-in iSight                                   | 4         | 0.62%   |
| Alcor Micro USB 2.0 Camera                              | 4         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 49        | 42.61%  |
| Synaptics                  | 25        | 21.74%  |
| Shenzhen Goodix Technology | 14        | 12.17%  |
| Upek                       | 7         | 6.09%   |
| Elan Microelectronics      | 7         | 6.09%   |
| AuthenTec                  | 6         | 5.22%   |
| STMicroelectronics         | 3         | 2.61%   |
| LighTuning Technology      | 2         | 1.74%   |
| Samsung Electronics        | 1         | 0.87%   |
| Focal-systems.Corp         | 1         | 0.87%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 6.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 6.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 6.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 6.09%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 6.09%   |
| Unknown                                                                    | 7         | 6.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.22%   |
| Validity Sensors VFS491                                                    | 5         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.35%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 3.48%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.48%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.61%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.61%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 2.61%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.61%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.61%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.74%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.74%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.74%   |
| Synaptics  WBDI                                                            | 2         | 1.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.74%   |
| AuthenTec AES1600                                                          | 2         | 1.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.87%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.87%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.87%   |
| Synaptics WBDI Device                                                      | 1         | 0.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.87%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.87%   |
| Samsung Fingerprint Device                                                 | 1         | 0.87%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.87%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.87%   |
| AuthenTec AES2810                                                          | 1         | 0.87%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 35        | 47.95%  |
| Alcor Micro           | 17        | 23.29%  |
| Upek                  | 4         | 5.48%   |
| O2 Micro              | 4         | 5.48%   |
| Lenovo                | 3         | 4.11%   |
| Advanced Card Systems | 3         | 4.11%   |
| SCM Microsystems      | 2         | 2.74%   |
| Gemalto (was Gemplus) | 2         | 2.74%   |
| Realtek Semiconductor | 1         | 1.37%   |
| Kobil Systems         | 1         | 1.37%   |
| Chicony Electronics   | 1         | 1.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 17        | 23.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 19.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 16.44%  |
| Broadcom 58200                                                               | 6         | 8.22%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.48%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.48%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.11%   |
| Broadcom 5880                                                                | 3         | 4.11%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 2.74%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 2.74%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.37%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.37%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.37%   |
| Kobil Systems Smart Token                                                    | 1         | 1.37%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.37%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 910       | 73.86%  |
| 1     | 259       | 21.02%  |
| 2     | 51        | 4.14%   |
| 3     | 8         | 0.65%   |
| 8     | 2         | 0.16%   |
| 5     | 1         | 0.08%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 115       | 29.34%  |
| Graphics card            | 85        | 21.68%  |
| Chipcard                 | 67        | 17.09%  |
| Net/wireless             | 32        | 8.16%   |
| Camera                   | 14        | 3.57%   |
| Communication controller | 13        | 3.32%   |
| Bluetooth                | 12        | 3.06%   |
| Storage                  | 11        | 2.81%   |
| Multimedia controller    | 10        | 2.55%   |
| Modem                    | 6         | 1.53%   |
| Unassigned class         | 5         | 1.28%   |
| Sound                    | 5         | 1.28%   |
| Network                  | 5         | 1.28%   |
| Flash memory             | 4         | 1.02%   |
| Card reader              | 3         | 0.77%   |
| Net/ethernet             | 2         | 0.51%   |
| Tv card                  | 1         | 0.26%   |
| Storage/ata              | 1         | 0.26%   |
| Firewire controller      | 1         | 0.26%   |

