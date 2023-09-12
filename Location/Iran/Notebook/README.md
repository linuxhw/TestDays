Linux in Iran - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

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

Total: 652

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [24a7c8a496](https://linux-hardware.org/?probe=24a7c8a496) | Sep 04, 2023 |
| Lenovo        | G50-70 20351                | [00a308aa4a](https://linux-hardware.org/?probe=00a308aa4a) | Sep 01, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| Apple         | MacBookPro5,5               | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | [243b20df85](https://linux-hardware.org/?probe=243b20df85) | Aug 28, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | [8cbbb0c64a](https://linux-hardware.org/?probe=8cbbb0c64a) | Aug 28, 2023 |
| HP            | OMEN by Laptop              | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| HP            | EliteBook 850 G1            | [4f74cc24e0](https://linux-hardware.org/?probe=4f74cc24e0) | Aug 26, 2023 |
| ASUSTek       | X450LD                      | [b9187b37b7](https://linux-hardware.org/?probe=b9187b37b7) | Aug 24, 2023 |
| ASUSTek       | X540UP                      | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| HP            | EliteBook 8540w             | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dbee57dbed](https://linux-hardware.org/?probe=dbee57dbed) | Aug 17, 2023 |
| HP            | EliteBook 8540w             | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| HP            | EliteBook 8540w             | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Dell          | Latitude E6400              | [f28a234c30](https://linux-hardware.org/?probe=f28a234c30) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [cb8ad3e0fc](https://linux-hardware.org/?probe=cb8ad3e0fc) | Aug 10, 2023 |
| Sony          | VGN-FW373D                  | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| Dell          | Latitude E6400              | [9f3cef93ed](https://linux-hardware.org/?probe=9f3cef93ed) | Aug 03, 2023 |
| HP            | ZBook 17 G3                 | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d9db031e65](https://linux-hardware.org/?probe=d9db031e65) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [7ed6a80c20](https://linux-hardware.org/?probe=7ed6a80c20) | Aug 01, 2023 |
| HP            | EliteBook 8540w             | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| HP            | EliteBook 8540w             | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [779f922cbb](https://linux-hardware.org/?probe=779f922cbb) | Jul 12, 2023 |
| HP            | EliteBook 8540w             | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| HP            | EliteBook 8540w             | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [df0ca94515](https://linux-hardware.org/?probe=df0ca94515) | Jun 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| HP            | EliteBook 8540w             | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| HP            | EliteBook 8540w             | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Toshiba       | PORTEGE X30-D               | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [1c33fe3f61](https://linux-hardware.org/?probe=1c33fe3f61) | Jun 12, 2023 |
| Dell          | Latitude E5470              | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| Toshiba       | PORTEGE X30-D               | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| ASUSTek       | X540UP                      | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| Sony          | VPCEA45FG                   | [873ca04445](https://linux-hardware.org/?probe=873ca04445) | May 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [c2125f60d2](https://linux-hardware.org/?probe=c2125f60d2) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| Toshiba       | Satellite C640              | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5086f7f4a2](https://linux-hardware.org/?probe=5086f7f4a2) | May 01, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [e37aab534f](https://linux-hardware.org/?probe=e37aab534f) | Apr 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Sony          | VGN-SZ640N                  | [659b01c666](https://linux-hardware.org/?probe=659b01c666) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Toshiba       | Satellite A100              | [f95e411124](https://linux-hardware.org/?probe=f95e411124) | Apr 20, 2023 |
| HP            | ZBook 15                    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| HP            | ZBook 15                    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| ASUSTek       | K55VD                       | [110fdee9b2](https://linux-hardware.org/?probe=110fdee9b2) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420 4178A4G       | [206861226d](https://linux-hardware.org/?probe=206861226d) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9e7e969310](https://linux-hardware.org/?probe=9e7e969310) | Apr 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0a028a43f8](https://linux-hardware.org/?probe=0a028a43f8) | Apr 01, 2023 |
| ASUSTek       | X555BP                      | [c7f621e335](https://linux-hardware.org/?probe=c7f621e335) | Apr 01, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| ASUSTek       | K54HR                       | [ac6cf948d5](https://linux-hardware.org/?probe=ac6cf948d5) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e4a88fa14e](https://linux-hardware.org/?probe=e4a88fa14e) | Mar 27, 2023 |
| Acer          | Aspire 4736Z                | [30e77255e4](https://linux-hardware.org/?probe=30e77255e4) | Mar 20, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [95ae633abb](https://linux-hardware.org/?probe=95ae633abb) | Mar 19, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [54025a10f5](https://linux-hardware.org/?probe=54025a10f5) | Mar 19, 2023 |
| ASUSTek       | X550LC                      | [5f73fa5db7](https://linux-hardware.org/?probe=5f73fa5db7) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [51ec4d252f](https://linux-hardware.org/?probe=51ec4d252f) | Mar 17, 2023 |
| Toshiba       | PORTEGE X30-D               | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5e4e9bde6f](https://linux-hardware.org/?probe=5e4e9bde6f) | Mar 03, 2023 |
| HP            | EliteBook 8470p             | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | [c6d06c27c7](https://linux-hardware.org/?probe=c6d06c27c7) | Feb 19, 2023 |
| Lenovo        | Z50-70 20354                | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f6276d350a](https://linux-hardware.org/?probe=f6276d350a) | Feb 08, 2023 |
| MSI           | S12T 3M/S12 3M              | [787543930a](https://linux-hardware.org/?probe=787543930a) | Feb 07, 2023 |
| Acer          | Aspire VN7-592G             | [a313fa3b83](https://linux-hardware.org/?probe=a313fa3b83) | Feb 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [2b2401b0f0](https://linux-hardware.org/?probe=2b2401b0f0) | Jan 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| ASUSTek       | X550VX                      | [b325ae9a48](https://linux-hardware.org/?probe=b325ae9a48) | Jan 11, 2023 |
| HP            | EliteBook 8570p             | [268f34635a](https://linux-hardware.org/?probe=268f34635a) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| HP            | EliteBook 8470p             | [d70aca4ad6](https://linux-hardware.org/?probe=d70aca4ad6) | Dec 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a6d43b6afd](https://linux-hardware.org/?probe=a6d43b6afd) | Dec 22, 2022 |
| Acer          | Predator PH315-55           | [01ba4c7b4a](https://linux-hardware.org/?probe=01ba4c7b4a) | Dec 16, 2022 |
| Acer          | Predator PH315-55           | [e2297c201d](https://linux-hardware.org/?probe=e2297c201d) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| HP            | Pavilion g6                 | [1120db45a3](https://linux-hardware.org/?probe=1120db45a3) | Dec 13, 2022 |
| Acer          | Aspire E1-572G              | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| Acer          | Aspire A315-56              | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| ASUSTek       | 1015CX                      | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [451d2e210d](https://linux-hardware.org/?probe=451d2e210d) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [51809e1ff3](https://linux-hardware.org/?probe=51809e1ff3) | Nov 11, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | G50-70 20351                | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| HP            | G62                         | [a7b5ac8e19](https://linux-hardware.org/?probe=a7b5ac8e19) | Oct 20, 2022 |
| MSI           | Modern 15 A5M               | [6459e3fedb](https://linux-hardware.org/?probe=6459e3fedb) | Oct 16, 2022 |
| MSI           | Modern 15 A5M               | [5192a80499](https://linux-hardware.org/?probe=5192a80499) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | G62                         | [dbe9a778bb](https://linux-hardware.org/?probe=dbe9a778bb) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| HP            | EliteBook Revolve 810 G3    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| ASUSTek       | UX490UA                     | [e953c29d50](https://linux-hardware.org/?probe=e953c29d50) | Sep 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0737d49df2](https://linux-hardware.org/?probe=0737d49df2) | Sep 15, 2022 |
| ASUSTek       | K56CB                       | [8718c2bb09](https://linux-hardware.org/?probe=8718c2bb09) | Sep 12, 2022 |
| Acer          | Aspire V3-571G              | [33c08b8aef](https://linux-hardware.org/?probe=33c08b8aef) | Sep 09, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [c803fe67f3](https://linux-hardware.org/?probe=c803fe67f3) | Sep 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c98348c9a3](https://linux-hardware.org/?probe=c98348c9a3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [68b6da5fe1](https://linux-hardware.org/?probe=68b6da5fe1) | Sep 04, 2022 |
| Lenovo        | G50-80 80E5                 | [ec5bb450ff](https://linux-hardware.org/?probe=ec5bb450ff) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASUSTek       | E202SA                      | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| ASUSTek       | N61Jv                       | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fa12e95e32](https://linux-hardware.org/?probe=fa12e95e32) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a36a32eb0e](https://linux-hardware.org/?probe=a36a32eb0e) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [759c9dee6b](https://linux-hardware.org/?probe=759c9dee6b) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [114ada270e](https://linux-hardware.org/?probe=114ada270e) | Aug 08, 2022 |
| ASUSTek       | 1015CX                      | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Timi          | RedmiBook 14                | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Dell          | Latitude E7470              | [0851479f6b](https://linux-hardware.org/?probe=0851479f6b) | Aug 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [9996781aa7](https://linux-hardware.org/?probe=9996781aa7) | Jul 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb442470d4](https://linux-hardware.org/?probe=fb442470d4) | Jul 24, 2022 |
| ASUSTek       | X555LD                      | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | G62                         | [bcb07d1cc9](https://linux-hardware.org/?probe=bcb07d1cc9) | Jul 16, 2022 |
| HP            | G62                         | [020a13b927](https://linux-hardware.org/?probe=020a13b927) | Jul 16, 2022 |
| Acer          | Nitro AN515-55              | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| ASUSTek       | N43JQ                       | [d73f714472](https://linux-hardware.org/?probe=d73f714472) | Jul 01, 2022 |
| ASUSTek       | X542UN                      | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| HP            | EliteBook 8440p             | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2893254eb3](https://linux-hardware.org/?probe=2893254eb3) | Jun 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e64a2a0eeb](https://linux-hardware.org/?probe=e64a2a0eeb) | Jun 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b0e13d9a94](https://linux-hardware.org/?probe=b0e13d9a94) | Jun 05, 2022 |
| ASUSTek       | X550JX                      | [05094a5491](https://linux-hardware.org/?probe=05094a5491) | Jun 05, 2022 |
| Lenovo        | ThinkPad E420 1141E9G       | [48b5588cbd](https://linux-hardware.org/?probe=48b5588cbd) | Jun 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [27dffb7089](https://linux-hardware.org/?probe=27dffb7089) | May 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Toshiba       | Satellite Pro T130          | [2771a53784](https://linux-hardware.org/?probe=2771a53784) | May 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [247fc8ed78](https://linux-hardware.org/?probe=247fc8ed78) | May 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8a9646dc78](https://linux-hardware.org/?probe=8a9646dc78) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| ASUSTek       | X580VD                      | [1d71c877c7](https://linux-hardware.org/?probe=1d71c877c7) | May 13, 2022 |
| Lenovo        | ThinkPad X230 23253QU       | [fde2b81a1c](https://linux-hardware.org/?probe=fde2b81a1c) | May 11, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [020929c7b4](https://linux-hardware.org/?probe=020929c7b4) | Apr 17, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Acer          | Aspire VX5-591G             | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | X550CC                      | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| MSI           | Katana GF66 11UE            | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000RAD     | [6f4db41ef5](https://linux-hardware.org/?probe=6f4db41ef5) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Dell          | Latitude E7240              | [242cae44a5](https://linux-hardware.org/?probe=242cae44a5) | Apr 04, 2022 |
| HP            | Pavilion Notebook           | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Packard Be... | EasyNote TK85               | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| Apple         | MacBookPro7,1               | [6e0eef7b54](https://linux-hardware.org/?probe=6e0eef7b54) | Mar 25, 2022 |
| ASUSTek       | N550JK                      | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| ASUSTek       | N501VW                      | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Dell          | Latitude E7470              | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Dell          | Latitude E7470              | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Dell          | Latitude E6530              | [2c3bfeff1d](https://linux-hardware.org/?probe=2c3bfeff1d) | Mar 13, 2022 |
| Unknown       | Unknown                     | [472d23c4f4](https://linux-hardware.org/?probe=472d23c4f4) | Mar 13, 2022 |
| ASUSTek       | X550VX                      | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| HP            | Pavilion dv6                | [dad6067f40](https://linux-hardware.org/?probe=dad6067f40) | Mar 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [29926fb03b](https://linux-hardware.org/?probe=29926fb03b) | Mar 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [071f146979](https://linux-hardware.org/?probe=071f146979) | Feb 24, 2022 |
| Dell          | Inspiron 5520               | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [93ca64d766](https://linux-hardware.org/?probe=93ca64d766) | Jan 28, 2022 |
| ASUSTek       | UX303UB                     | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| Alienware     | 17 R3                       | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| ASUSTek       | N55SF                       | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| Dell          | Inspiron 7577               | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| ASUSTek       | X450LC                      | [8228658808](https://linux-hardware.org/?probe=8228658808) | Jan 09, 2022 |
| ASUSTek       | 1001PX                      | [ba7acc9c68](https://linux-hardware.org/?probe=ba7acc9c68) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| Lenovo        | G50-80 80E5                 | [71a50bcb50](https://linux-hardware.org/?probe=71a50bcb50) | Dec 30, 2021 |
| Lenovo        | G50-80 80E5                 | [d8d81e5c50](https://linux-hardware.org/?probe=d8d81e5c50) | Dec 30, 2021 |
| Lenovo        | G580 20150                  | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| Acer          | Aspire E1-572G              | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| ASUSTek       | UX430UNR                    | [8e802c50ad](https://linux-hardware.org/?probe=8e802c50ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [7b6f9acbf8](https://linux-hardware.org/?probe=7b6f9acbf8) | Dec 15, 2021 |
| HP            | ZBook 15 G3                 | [2c739999fa](https://linux-hardware.org/?probe=2c739999fa) | Dec 10, 2021 |
| ASUSTek       | X580VD                      | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | [68820e21d2](https://linux-hardware.org/?probe=68820e21d2) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | [c7e180ab84](https://linux-hardware.org/?probe=c7e180ab84) | Dec 08, 2021 |
| Dell          | Latitude E7470              | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| ASUSTek       | GL702VMK                    | [ff58d2a76e](https://linux-hardware.org/?probe=ff58d2a76e) | Nov 21, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [f119e55cf9](https://linux-hardware.org/?probe=f119e55cf9) | Nov 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Dell          | Latitude E7240              | [366228fab6](https://linux-hardware.org/?probe=366228fab6) | Nov 05, 2021 |
| HP            | ProBook 640 G2              | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| Sony          | VPCSA25GX                   | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [6ab1ce41db](https://linux-hardware.org/?probe=6ab1ce41db) | Oct 25, 2021 |
| Dell          | Inspiron N5010              | [6547cded19](https://linux-hardware.org/?probe=6547cded19) | Oct 22, 2021 |
| Dell          | Inspiron N5010              | [30c1b322ad](https://linux-hardware.org/?probe=30c1b322ad) | Oct 22, 2021 |
| ASUSTek       | U56E                        | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | Laptop 15-ef2xxx            | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| Acer          | Aspire A715-75G             | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| ASUSTek       | K55VD                       | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| HP            | EliteBook 840 G2            | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| HP            | ProBook 440 G2              | [cc83275513](https://linux-hardware.org/?probe=cc83275513) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325655d6c5](https://linux-hardware.org/?probe=325655d6c5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [3c4378f506](https://linux-hardware.org/?probe=3c4378f506) | Sep 25, 2021 |
| HP            | EliteBook 745 G2            | [2b74c7b1ff](https://linux-hardware.org/?probe=2b74c7b1ff) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [07d1890920](https://linux-hardware.org/?probe=07d1890920) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| ASUSTek       | X540UV                      | [b0a231831a](https://linux-hardware.org/?probe=b0a231831a) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | [d47d63a84f](https://linux-hardware.org/?probe=d47d63a84f) | Sep 07, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [453f65a5e7](https://linux-hardware.org/?probe=453f65a5e7) | Sep 07, 2021 |
| Acer          | Aspire A715-71G             | [b915ae27b7](https://linux-hardware.org/?probe=b915ae27b7) | Sep 06, 2021 |
| Acer          | Aspire F5-573G              | [62fc103f71](https://linux-hardware.org/?probe=62fc103f71) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| MSI           | Prestige 14 A10RB           | [2aaa6d05d2](https://linux-hardware.org/?probe=2aaa6d05d2) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [9f01a4629a](https://linux-hardware.org/?probe=9f01a4629a) | Aug 28, 2021 |
| ASUSTek       | X550EA                      | [19a7dfc92a](https://linux-hardware.org/?probe=19a7dfc92a) | Aug 22, 2021 |
| ASUSTek       | K55VD                       | [bfe60273f6](https://linux-hardware.org/?probe=bfe60273f6) | Aug 09, 2021 |
| HP            | ZBook 15                    | [1a67896055](https://linux-hardware.org/?probe=1a67896055) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [fe27de6bbc](https://linux-hardware.org/?probe=fe27de6bbc) | Aug 07, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | [407501f166](https://linux-hardware.org/?probe=407501f166) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Acer          | Aspire 5749Z                | [a5c472e082](https://linux-hardware.org/?probe=a5c472e082) | Aug 01, 2021 |
| Acer          | Aspire 5749Z                | [538eb1efa0](https://linux-hardware.org/?probe=538eb1efa0) | Aug 01, 2021 |
| ASUSTek       | N53SV                       | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Acer          | Aspire E5-475G              | [063facd29a](https://linux-hardware.org/?probe=063facd29a) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [afb9cb6674](https://linux-hardware.org/?probe=afb9cb6674) | Jul 27, 2021 |
| Lenovo        | Z50-75 80EC                 | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | Inspiron N4030              | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | ProBook 4540s               | [719b37c9ac](https://linux-hardware.org/?probe=719b37c9ac) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [0ae43f5015](https://linux-hardware.org/?probe=0ae43f5015) | Jul 20, 2021 |
| ASUSTek       | K55VD                       | [b26638f586](https://linux-hardware.org/?probe=b26638f586) | Jul 17, 2021 |
| ASUSTek       | K55VD                       | [8a28a4f7f5](https://linux-hardware.org/?probe=8a28a4f7f5) | Jul 17, 2021 |
| HP            | ProBook 450 G0              | [08f5207ee6](https://linux-hardware.org/?probe=08f5207ee6) | Jul 17, 2021 |
| ASUSTek       | X550LD                      | [b3bb7e1295](https://linux-hardware.org/?probe=b3bb7e1295) | Jul 17, 2021 |
| HP            | Notebook                    | [3fc4cb2f55](https://linux-hardware.org/?probe=3fc4cb2f55) | Jul 09, 2021 |
| Lenovo        | ThinkPad E560 20EV0005AD    | [fab11e73ee](https://linux-hardware.org/?probe=fab11e73ee) | Jun 29, 2021 |
| Acer          | Aspire 4736Z                | [6a5d92699d](https://linux-hardware.org/?probe=6a5d92699d) | Jun 23, 2021 |
| Dell          | Latitude D420               | [5f0d609bef](https://linux-hardware.org/?probe=5f0d609bef) | Jun 21, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [4af988fc2f](https://linux-hardware.org/?probe=4af988fc2f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [1fd8a9e8c8](https://linux-hardware.org/?probe=1fd8a9e8c8) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| ASUSTek       | N53SV                       | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Acer          | Aspire R3-131T              | [35b68a0b4a](https://linux-hardware.org/?probe=35b68a0b4a) | Jun 06, 2021 |
| HP            | ProBook 4520s               | [b0a9a196db](https://linux-hardware.org/?probe=b0a9a196db) | Jun 03, 2021 |
| ASUSTek       | N56VM                       | [b3206cba40](https://linux-hardware.org/?probe=b3206cba40) | Jun 03, 2021 |
| Sony          | VGN-CS38GD_B                | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [74d1da4b68](https://linux-hardware.org/?probe=74d1da4b68) | May 28, 2021 |
| ASUSTek       | X550MJ                      | [208fc3f30f](https://linux-hardware.org/?probe=208fc3f30f) | May 25, 2021 |
| Acer          | Aspire R3-131T              | [28d19f1a59](https://linux-hardware.org/?probe=28d19f1a59) | May 25, 2021 |
| Acer          | Aspire R3-131T              | [512cc44d82](https://linux-hardware.org/?probe=512cc44d82) | May 21, 2021 |
| ASUSTek       | K53SM                       | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| ASUSTek       | T100TA                      | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| ASUSTek       | N56VM                       | [1417eccc8b](https://linux-hardware.org/?probe=1417eccc8b) | May 15, 2021 |
| HP            | EliteBook 725 G2            | [5dddeca3e8](https://linux-hardware.org/?probe=5dddeca3e8) | May 09, 2021 |
| Acer          | Aspire V3-574G              | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Dell          | XPS 15 9500                 | [2d12301b1c](https://linux-hardware.org/?probe=2d12301b1c) | May 05, 2021 |
| HP            | Laptop 15-bs0xx             | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | Laptop 15-bs0xx             | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [940758b420](https://linux-hardware.org/?probe=940758b420) | Apr 27, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | [ced3a1165d](https://linux-hardware.org/?probe=ced3a1165d) | Apr 24, 2021 |
| ASUSTek       | X555LF                      | [eb9637ae4a](https://linux-hardware.org/?probe=eb9637ae4a) | Apr 19, 2021 |
| Lenovo        | ThinkPad E590 20NB0057AD    | [d06cfc6dee](https://linux-hardware.org/?probe=d06cfc6dee) | Apr 18, 2021 |
| Acer          | AOD260                      | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Lenovo        | ThinkPad T470p 20J6S08M0... | [84619b1b45](https://linux-hardware.org/?probe=84619b1b45) | Apr 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [1dcb2a173e](https://linux-hardware.org/?probe=1dcb2a173e) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [28d13bbb26](https://linux-hardware.org/?probe=28d13bbb26) | Apr 14, 2021 |
| Acer          | Aspire E1-571G              | [7713767fa6](https://linux-hardware.org/?probe=7713767fa6) | Apr 10, 2021 |
| HP            | EliteBook 840 G2            | [9c00d55213](https://linux-hardware.org/?probe=9c00d55213) | Apr 10, 2021 |
| HP            | Laptop 15-bs0xx             | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| MSI           | CR610M                      | [e2e00880a3](https://linux-hardware.org/?probe=e2e00880a3) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire 4741                 | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| Acer          | Aspire E1-571G              | [c5e7e65164](https://linux-hardware.org/?probe=c5e7e65164) | Apr 01, 2021 |
| HP            | EliteBook 745 G4            | [a5888bbded](https://linux-hardware.org/?probe=a5888bbded) | Apr 01, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [9a4a054203](https://linux-hardware.org/?probe=9a4a054203) | Apr 01, 2021 |
| Acer          | Aspire E5-573G              | [bacb9e5030](https://linux-hardware.org/?probe=bacb9e5030) | Mar 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [344eec241a](https://linux-hardware.org/?probe=344eec241a) | Mar 21, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | [ca815648fc](https://linux-hardware.org/?probe=ca815648fc) | Mar 17, 2021 |
| Sony          | VGN-CS38GD_B                | [d5d788f2f3](https://linux-hardware.org/?probe=d5d788f2f3) | Mar 15, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | [75ba14ee94](https://linux-hardware.org/?probe=75ba14ee94) | Mar 14, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | [be98339598](https://linux-hardware.org/?probe=be98339598) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | [b7e39a92a0](https://linux-hardware.org/?probe=b7e39a92a0) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | [7ca6ad9361](https://linux-hardware.org/?probe=7ca6ad9361) | Mar 06, 2021 |
| ASUSTek       | K42JK                       | [bae11d222f](https://linux-hardware.org/?probe=bae11d222f) | Mar 04, 2021 |
| ASUSTek       | K42JK                       | [3ae670828a](https://linux-hardware.org/?probe=3ae670828a) | Mar 03, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | [fd21e67a3c](https://linux-hardware.org/?probe=fd21e67a3c) | Feb 28, 2021 |
| HP            | Pavilion g6                 | [2ce61d58bf](https://linux-hardware.org/?probe=2ce61d58bf) | Feb 26, 2021 |
| HP            | ProBook 4540s               | [dda65f86ac](https://linux-hardware.org/?probe=dda65f86ac) | Feb 24, 2021 |
| HP            | ProBook 4540s               | [e3ff93ab0a](https://linux-hardware.org/?probe=e3ff93ab0a) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [ab787a4172](https://linux-hardware.org/?probe=ab787a4172) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [7ba0b6a17d](https://linux-hardware.org/?probe=7ba0b6a17d) | Feb 21, 2021 |
| Lenovo        | G580 20150                  | [d45ed4ad08](https://linux-hardware.org/?probe=d45ed4ad08) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | [520780b02d](https://linux-hardware.org/?probe=520780b02d) | Feb 18, 2021 |
| MSI           | Modern 14 A10M              | [62c9e819cd](https://linux-hardware.org/?probe=62c9e819cd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [8070e672a7](https://linux-hardware.org/?probe=8070e672a7) | Feb 15, 2021 |
| Lenovo        | Flex 2-15 20405             | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | [a0eb5fc713](https://linux-hardware.org/?probe=a0eb5fc713) | Jan 20, 2021 |
| Dell          | Vostro 5470                 | [2fa2f12de6](https://linux-hardware.org/?probe=2fa2f12de6) | Jan 19, 2021 |
| Sony          | VPCZ126GG                   | [537d05799c](https://linux-hardware.org/?probe=537d05799c) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | [66598d3f69](https://linux-hardware.org/?probe=66598d3f69) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [703dd398d1](https://linux-hardware.org/?probe=703dd398d1) | Jan 14, 2021 |
| ASUSTek       | X542UN                      | [44633c4ff2](https://linux-hardware.org/?probe=44633c4ff2) | Jan 13, 2021 |
| Sony          | SVF15N12SGB                 | [3ff592b868](https://linux-hardware.org/?probe=3ff592b868) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| Dell          | Vostro 1015                 | [7243a2df4f](https://linux-hardware.org/?probe=7243a2df4f) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Acer          | Aspire 5755G                | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| HP            | ProBook 4540s               | [86bd405fac](https://linux-hardware.org/?probe=86bd405fac) | Dec 27, 2020 |
| HP            | ProBook 4540s               | [7a93e1b05a](https://linux-hardware.org/?probe=7a93e1b05a) | Dec 27, 2020 |
| Dell          | Vostro 1015                 | [9be1d69693](https://linux-hardware.org/?probe=9be1d69693) | Dec 26, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [f7f32358db](https://linux-hardware.org/?probe=f7f32358db) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| MSI           | GE60 2PC                    | [46af0a2d84](https://linux-hardware.org/?probe=46af0a2d84) | Dec 22, 2020 |
| MSI           | GE60 2PC                    | [c659f6a910](https://linux-hardware.org/?probe=c659f6a910) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T10... | [d5a85767cd](https://linux-hardware.org/?probe=d5a85767cd) | Dec 18, 2020 |
| Dell          | Inspiron N5110              | [a6bf272580](https://linux-hardware.org/?probe=a6bf272580) | Dec 18, 2020 |
| HP            | ProBook 450 G4              | [fe5ef27982](https://linux-hardware.org/?probe=fe5ef27982) | Dec 17, 2020 |
| Acer          | Aspire A715-74G             | [03f5d24d56](https://linux-hardware.org/?probe=03f5d24d56) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | [886054e929](https://linux-hardware.org/?probe=886054e929) | Dec 15, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [67aa2554c3](https://linux-hardware.org/?probe=67aa2554c3) | Dec 10, 2020 |
| MSI           | CX62 6QL                    | [90a60a1e78](https://linux-hardware.org/?probe=90a60a1e78) | Dec 06, 2020 |
| MSI           | CX62 6QL                    | [9b4aaf5856](https://linux-hardware.org/?probe=9b4aaf5856) | Dec 06, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [47835d66f6](https://linux-hardware.org/?probe=47835d66f6) | Dec 01, 2020 |
| Sony          | VPCEH11FX                   | [d3ff8db043](https://linux-hardware.org/?probe=d3ff8db043) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e0bc13a31](https://linux-hardware.org/?probe=8e0bc13a31) | Nov 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | [c099ac62d5](https://linux-hardware.org/?probe=c099ac62d5) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [7787345258](https://linux-hardware.org/?probe=7787345258) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3bc3e0823a](https://linux-hardware.org/?probe=3bc3e0823a) | Nov 09, 2020 |
| HP            | ProBook 4540s               | [4864704e84](https://linux-hardware.org/?probe=4864704e84) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [adbb505553](https://linux-hardware.org/?probe=adbb505553) | Nov 08, 2020 |
| ASUSTek       | X550IU                      | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| Lenovo        | E5                          | [3b7111b4a2](https://linux-hardware.org/?probe=3b7111b4a2) | Nov 07, 2020 |
| Lenovo        | E5                          | [cb3bf5a3df](https://linux-hardware.org/?probe=cb3bf5a3df) | Nov 07, 2020 |
| ASUSTek       | X550VXK                     | [5f95436c09](https://linux-hardware.org/?probe=5f95436c09) | Nov 06, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [42ef7e253c](https://linux-hardware.org/?probe=42ef7e253c) | Nov 01, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cba527dd9f](https://linux-hardware.org/?probe=cba527dd9f) | Nov 01, 2020 |
| Acer          | Aspire 5741G                | [75bacf18a7](https://linux-hardware.org/?probe=75bacf18a7) | Oct 31, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [11db584122](https://linux-hardware.org/?probe=11db584122) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [7525ff1dde](https://linux-hardware.org/?probe=7525ff1dde) | Oct 23, 2020 |
| ASUSTek       | N552VW                      | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| Lenovo        | B50-80 80EW                 | [c6bf9e5376](https://linux-hardware.org/?probe=c6bf9e5376) | Oct 17, 2020 |
| ASUSTek       | X505BA                      | [6f5c254a9f](https://linux-hardware.org/?probe=6f5c254a9f) | Oct 15, 2020 |
| Sony          | VPCSB36FG                   | [2763c330eb](https://linux-hardware.org/?probe=2763c330eb) | Oct 09, 2020 |
| ASUSTek       | UX430UA                     | [d6586b9bb8](https://linux-hardware.org/?probe=d6586b9bb8) | Oct 05, 2020 |
| Sony          | VPCEB1SFX                   | [01b67b1979](https://linux-hardware.org/?probe=01b67b1979) | Sep 27, 2020 |
| Sony          | VPCEB1SFX                   | [616d06a0b0](https://linux-hardware.org/?probe=616d06a0b0) | Sep 26, 2020 |
| HP            | EliteBook 725 G2            | [6f184c4bc8](https://linux-hardware.org/?probe=6f184c4bc8) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| HP            | EliteBook 725 G2            | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| Sony          | VPCSB36FG                   | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| ASUSTek       | K52F                        | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | [61bc69e87c](https://linux-hardware.org/?probe=61bc69e87c) | Sep 04, 2020 |
| Dell          | Latitude E6530              | [c026f89bd8](https://linux-hardware.org/?probe=c026f89bd8) | Aug 31, 2020 |
| MSI           | Prestige 14 A10RB           | [b7fff5e5cc](https://linux-hardware.org/?probe=b7fff5e5cc) | Aug 28, 2020 |
| HP            | EliteBook 8570w             | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [af595ebfde](https://linux-hardware.org/?probe=af595ebfde) | Aug 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c03d58914c](https://linux-hardware.org/?probe=c03d58914c) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [55c0c83149](https://linux-hardware.org/?probe=55c0c83149) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e97f7b8582](https://linux-hardware.org/?probe=e97f7b8582) | Aug 02, 2020 |
| MSI           | GF63 Thin 9RC               | [f7eff6d78e](https://linux-hardware.org/?probe=f7eff6d78e) | Jul 28, 2020 |
| MSI           | GF63 Thin 9RC               | [7b12eabb3e](https://linux-hardware.org/?probe=7b12eabb3e) | Jul 28, 2020 |
| Lenovo        | ThinkPad E490 20N8000JUE    | [66d2ca1186](https://linux-hardware.org/?probe=66d2ca1186) | Jul 22, 2020 |
| ASUSTek       | N53Jq                       | [4d04d4ee3a](https://linux-hardware.org/?probe=4d04d4ee3a) | Jul 19, 2020 |
| Acer          | Aspire V3-571G              | [d7789565b7](https://linux-hardware.org/?probe=d7789565b7) | Jul 18, 2020 |
| ASUSTek       | N56JN                       | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [e9a3474bde](https://linux-hardware.org/?probe=e9a3474bde) | Jul 09, 2020 |
| Acer          | TravelMate 5742Z            | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| ASUSTek       | N56JN                       | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Dell          | Inspiron N5110              | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Lenovo        | G580 20157                  | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [842fbba95c](https://linux-hardware.org/?probe=842fbba95c) | May 22, 2020 |
| Lenovo        | G580 20157                  | [c9967bfff4](https://linux-hardware.org/?probe=c9967bfff4) | May 22, 2020 |
| Fujitsu       | LIFEBOOK NH570              | [58dbbb5f10](https://linux-hardware.org/?probe=58dbbb5f10) | May 22, 2020 |
| Acer          | Aspire V5-572G              | [d919340bf8](https://linux-hardware.org/?probe=d919340bf8) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91908a3d7e](https://linux-hardware.org/?probe=91908a3d7e) | May 15, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3448fe759e](https://linux-hardware.org/?probe=3448fe759e) | May 13, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [d27ef604e7](https://linux-hardware.org/?probe=d27ef604e7) | May 10, 2020 |
| HP            | EliteBook 8470p             | [cc84ca4df1](https://linux-hardware.org/?probe=cc84ca4df1) | May 08, 2020 |
| HP            | EliteBook 8470p             | [150b4cbfba](https://linux-hardware.org/?probe=150b4cbfba) | May 08, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [efe32a1257](https://linux-hardware.org/?probe=efe32a1257) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | [3cac051446](https://linux-hardware.org/?probe=3cac051446) | May 07, 2020 |
| HP            | EliteBook 8470p             | [543fb035d1](https://linux-hardware.org/?probe=543fb035d1) | May 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7d8b34f96f](https://linux-hardware.org/?probe=7d8b34f96f) | May 03, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96005fbb6f](https://linux-hardware.org/?probe=96005fbb6f) | Apr 28, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [3405972303](https://linux-hardware.org/?probe=3405972303) | Apr 27, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [2950c5ee7f](https://linux-hardware.org/?probe=2950c5ee7f) | Apr 27, 2020 |
| HP            | EliteBook 8470p             | [f82980ac2c](https://linux-hardware.org/?probe=f82980ac2c) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| HP            | EliteBook 8470p             | [abfe333fb8](https://linux-hardware.org/?probe=abfe333fb8) | Apr 25, 2020 |
| HP            | EliteBook 8470p             | [9e8575f75a](https://linux-hardware.org/?probe=9e8575f75a) | Apr 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5ec8b8b3b7](https://linux-hardware.org/?probe=5ec8b8b3b7) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |
| Lenovo        | G505 20240                  | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| ASUSTek       | X550IU                      | [943b36ee80](https://linux-hardware.org/?probe=943b36ee80) | Apr 10, 2020 |
| Sony          | VPCEH11FX                   | [e0ef96682b](https://linux-hardware.org/?probe=e0ef96682b) | Apr 09, 2020 |
| ASUSTek       | G750JH                      | [45a70fa311](https://linux-hardware.org/?probe=45a70fa311) | Apr 08, 2020 |
| ASUSTek       | G750JH                      | [3314aa590e](https://linux-hardware.org/?probe=3314aa590e) | Apr 08, 2020 |
| Dell          | Latitude D630               | [98199f8421](https://linux-hardware.org/?probe=98199f8421) | Apr 07, 2020 |
| Lenovo        | Z50-70 20354                | [839c8344be](https://linux-hardware.org/?probe=839c8344be) | Apr 07, 2020 |
| ASUSTek       | 1015CX                      | [c98f5bcee3](https://linux-hardware.org/?probe=c98f5bcee3) | Apr 05, 2020 |
| ASUSTek       | 1015CX                      | [216b680d21](https://linux-hardware.org/?probe=216b680d21) | Apr 05, 2020 |
| Dell          | Latitude 7350               | [3ecdea8fcc](https://linux-hardware.org/?probe=3ecdea8fcc) | Apr 03, 2020 |
| Toshiba       | PORTEGE R930                | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| Dell          | Inspiron 1545               | [ffeee579db](https://linux-hardware.org/?probe=ffeee579db) | Mar 28, 2020 |
| Dell          | Inspiron 3443               | [0a21a54858](https://linux-hardware.org/?probe=0a21a54858) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [aa94d9ab9b](https://linux-hardware.org/?probe=aa94d9ab9b) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | [96f26b673c](https://linux-hardware.org/?probe=96f26b673c) | Mar 28, 2020 |
| Dell          | Vostro 3578                 | [21b92f29e5](https://linux-hardware.org/?probe=21b92f29e5) | Mar 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e7effd8e19](https://linux-hardware.org/?probe=e7effd8e19) | Mar 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [aa7093b56c](https://linux-hardware.org/?probe=aa7093b56c) | Mar 23, 2020 |
| Dell          | Inspiron 5570               | [a79912cfdf](https://linux-hardware.org/?probe=a79912cfdf) | Mar 22, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | [409951a0dd](https://linux-hardware.org/?probe=409951a0dd) | Mar 20, 2020 |
| Dell          | Studio 1558                 | [06b0f26f6a](https://linux-hardware.org/?probe=06b0f26f6a) | Mar 12, 2020 |
| Dell          | Studio 1558                 | [57fddb1856](https://linux-hardware.org/?probe=57fddb1856) | Mar 12, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b224a48803](https://linux-hardware.org/?probe=b224a48803) | Mar 04, 2020 |
| ASUSTek       | N82JQ                       | [b1b698b060](https://linux-hardware.org/?probe=b1b698b060) | Mar 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [910ec05246](https://linux-hardware.org/?probe=910ec05246) | Feb 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [ddb0fad848](https://linux-hardware.org/?probe=ddb0fad848) | Feb 29, 2020 |
| Dell          | Vostro 1015                 | [091443df09](https://linux-hardware.org/?probe=091443df09) | Feb 20, 2020 |
| Toshiba       | Satellite L655              | [c04cf86240](https://linux-hardware.org/?probe=c04cf86240) | Feb 15, 2020 |
| Toshiba       | Satellite L655              | [00e7d3f0b6](https://linux-hardware.org/?probe=00e7d3f0b6) | Feb 15, 2020 |
| Lenovo        | V580c 20160                 | [7e02c8c738](https://linux-hardware.org/?probe=7e02c8c738) | Feb 11, 2020 |
| Sony          | VPCSB19GG                   | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | [dccdce5101](https://linux-hardware.org/?probe=dccdce5101) | Jan 23, 2020 |
| Dell          | Vostro 1510                 | [51fbe1ce5b](https://linux-hardware.org/?probe=51fbe1ce5b) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | [664116ebbf](https://linux-hardware.org/?probe=664116ebbf) | Jan 22, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f77d00b6ce](https://linux-hardware.org/?probe=f77d00b6ce) | Jan 10, 2020 |
| Dell          | Precision M4800             | [cc63357309](https://linux-hardware.org/?probe=cc63357309) | Jan 09, 2020 |
| Lenovo        | ThinkPad X131e 33711T4      | [f06e98b417](https://linux-hardware.org/?probe=f06e98b417) | Jan 08, 2020 |
| HP            | ProBook 4540s               | [9ef64f7487](https://linux-hardware.org/?probe=9ef64f7487) | Jan 03, 2020 |
| Lenovo        | G510 20238                  | [63fd9a500f](https://linux-hardware.org/?probe=63fd9a500f) | Dec 27, 2019 |
| Lenovo        | G510 20238                  | [8543221f24](https://linux-hardware.org/?probe=8543221f24) | Dec 27, 2019 |
| HP            | EliteBook 2740p             | [82cb2d5e90](https://linux-hardware.org/?probe=82cb2d5e90) | Dec 26, 2019 |
| Dell          | Inspiron N5040              | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| ASUSTek       | X542UN                      | [4b7f71d936](https://linux-hardware.org/?probe=4b7f71d936) | Dec 14, 2019 |
| Lenovo        | G50-70 20351                | [f30b5e8075](https://linux-hardware.org/?probe=f30b5e8075) | Dec 09, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [15babe41d0](https://linux-hardware.org/?probe=15babe41d0) | Nov 26, 2019 |
| ASUSTek       | B9440UA                     | [ed7fb8cbb9](https://linux-hardware.org/?probe=ed7fb8cbb9) | Nov 15, 2019 |
| ASUSTek       | B9440UA                     | [5e184acc59](https://linux-hardware.org/?probe=5e184acc59) | Nov 15, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [f13de25d56](https://linux-hardware.org/?probe=f13de25d56) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dda0a53712](https://linux-hardware.org/?probe=dda0a53712) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b86e3d7141](https://linux-hardware.org/?probe=b86e3d7141) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | Pavilion 15                 | [57540edaa7](https://linux-hardware.org/?probe=57540edaa7) | Nov 12, 2019 |
| ASUSTek       | B9440UA                     | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| Dell          | Vostro 1520                 | [247d9e9c2f](https://linux-hardware.org/?probe=247d9e9c2f) | Nov 01, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [797965c573](https://linux-hardware.org/?probe=797965c573) | Oct 30, 2019 |
| Dell          | Vostro 1015                 | [400532e714](https://linux-hardware.org/?probe=400532e714) | Oct 24, 2019 |
| Dell          | Vostro 1015                 | [df8815e747](https://linux-hardware.org/?probe=df8815e747) | Oct 24, 2019 |
| ASUSTek       | N501VW                      | [4d2a1a9add](https://linux-hardware.org/?probe=4d2a1a9add) | Oct 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d1394d6252](https://linux-hardware.org/?probe=d1394d6252) | Oct 11, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c8223df556](https://linux-hardware.org/?probe=c8223df556) | Oct 03, 2019 |
| Dell          | Inspiron N4050              | [153db5ae1b](https://linux-hardware.org/?probe=153db5ae1b) | Oct 01, 2019 |
| Lenovo        | G50-45 80E3                 | [a814f0be14](https://linux-hardware.org/?probe=a814f0be14) | Sep 26, 2019 |
| Lenovo        | G50-45 80E3                 | [4c39be72b3](https://linux-hardware.org/?probe=4c39be72b3) | Sep 26, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [fbbabc5836](https://linux-hardware.org/?probe=fbbabc5836) | Sep 23, 2019 |
| Lenovo        | G50-70 20351                | [0143228659](https://linux-hardware.org/?probe=0143228659) | Sep 20, 2019 |
| Lenovo        | G50-70 20351                | [6e13970f68](https://linux-hardware.org/?probe=6e13970f68) | Sep 18, 2019 |
| ASUSTek       | X556UQK                     | [cd4ce4d624](https://linux-hardware.org/?probe=cd4ce4d624) | Sep 12, 2019 |
| HP            | Pavilion 15                 | [c56817e0e4](https://linux-hardware.org/?probe=c56817e0e4) | Sep 10, 2019 |
| HP            | Pavilion g6                 | [81b3b2667e](https://linux-hardware.org/?probe=81b3b2667e) | Sep 03, 2019 |
| Acer          | Aspire V3-571G              | [a4f33fd40a](https://linux-hardware.org/?probe=a4f33fd40a) | Sep 03, 2019 |
| HP            | ProBook 4540s               | [1349a15c0f](https://linux-hardware.org/?probe=1349a15c0f) | Sep 01, 2019 |
| Lenovo        | ThinkPad E470 20H1002DAD    | [75804928d2](https://linux-hardware.org/?probe=75804928d2) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [579809b8b0](https://linux-hardware.org/?probe=579809b8b0) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [81e015523a](https://linux-hardware.org/?probe=81e015523a) | Aug 30, 2019 |
| HP            | EliteBook 2540p             | [72437e888c](https://linux-hardware.org/?probe=72437e888c) | Aug 29, 2019 |
| ASUSTek       | X102BA                      | [8365a8b9d6](https://linux-hardware.org/?probe=8365a8b9d6) | Aug 27, 2019 |
| ASUSTek       | X102BA                      | [43b9931c92](https://linux-hardware.org/?probe=43b9931c92) | Aug 26, 2019 |
| MSI           | MS-1454                     | [b03f58cc28](https://linux-hardware.org/?probe=b03f58cc28) | Aug 23, 2019 |
| MSI           | MS-1454                     | [94bfc26599](https://linux-hardware.org/?probe=94bfc26599) | Aug 23, 2019 |
| ASUSTek       | X540UPR                     | [2f40c492db](https://linux-hardware.org/?probe=2f40c492db) | Aug 12, 2019 |
| Lenovo        | ThinkPad X201 3249CTO       | [24c83ab728](https://linux-hardware.org/?probe=24c83ab728) | Aug 09, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | [2507713bd4](https://linux-hardware.org/?probe=2507713bd4) | Aug 06, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | [0ad209e005](https://linux-hardware.org/?probe=0ad209e005) | Aug 06, 2019 |
| ASUSTek       | X555LJ                      | [541fb4f240](https://linux-hardware.org/?probe=541fb4f240) | Aug 06, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [2ab556fd2e](https://linux-hardware.org/?probe=2ab556fd2e) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [3ff8ae9e18](https://linux-hardware.org/?probe=3ff8ae9e18) | Aug 01, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [9518b70a0d](https://linux-hardware.org/?probe=9518b70a0d) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [9c80796306](https://linux-hardware.org/?probe=9c80796306) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | [66cc9aa111](https://linux-hardware.org/?probe=66cc9aa111) | Jul 31, 2019 |
| HP            | Pavilion dv6                | [38f37f78c5](https://linux-hardware.org/?probe=38f37f78c5) | Jul 29, 2019 |
| ASUSTek       | FX503VD                     | [c53df5f083](https://linux-hardware.org/?probe=c53df5f083) | Jul 27, 2019 |
| ASUSTek       | FX503VD                     | [051b4df60a](https://linux-hardware.org/?probe=051b4df60a) | Jul 27, 2019 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [b6b40de397](https://linux-hardware.org/?probe=b6b40de397) | Jul 26, 2019 |
| ASUSTek       | GL553VD                     | [1a816e6ebb](https://linux-hardware.org/?probe=1a816e6ebb) | Jul 23, 2019 |
| Acer          | Aspire V3-571G              | [6478022b75](https://linux-hardware.org/?probe=6478022b75) | Jul 21, 2019 |
| Acer          | Aspire V3-571G              | [22e01f3d1f](https://linux-hardware.org/?probe=22e01f3d1f) | Jul 21, 2019 |
| ASUSTek       | X542UN                      | [0120b3a78b](https://linux-hardware.org/?probe=0120b3a78b) | Jul 19, 2019 |
| HP            | ProBook 450 G1              | [ce6df77b4c](https://linux-hardware.org/?probe=ce6df77b4c) | Jul 18, 2019 |
| HP            | ProBook 450 G1              | [997a4ec1c4](https://linux-hardware.org/?probe=997a4ec1c4) | Jul 18, 2019 |
| ASUSTek       | X411UNV                     | [ca77267e34](https://linux-hardware.org/?probe=ca77267e34) | Jul 17, 2019 |
| HP            | EliteBook Revolve 810 G3    | [46408abbb6](https://linux-hardware.org/?probe=46408abbb6) | Jul 12, 2019 |
| Lenovo        | AILZx                       | [3673023593](https://linux-hardware.org/?probe=3673023593) | Jun 27, 2019 |
| Lenovo        | AILZx                       | [e4c012a605](https://linux-hardware.org/?probe=e4c012a605) | Jun 27, 2019 |
| ASUSTek       | UX550VD                     | [b4ed65654c](https://linux-hardware.org/?probe=b4ed65654c) | Jun 26, 2019 |
| ASUSTek       | UX550VD                     | [dfc972293d](https://linux-hardware.org/?probe=dfc972293d) | Jun 25, 2019 |
| Dell          | Latitude E6500              | [5d172397d7](https://linux-hardware.org/?probe=5d172397d7) | Jun 10, 2019 |
| ASUSTek       | X556URK                     | [1ac09da8a9](https://linux-hardware.org/?probe=1ac09da8a9) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | [586a6a9f8a](https://linux-hardware.org/?probe=586a6a9f8a) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | [3633557547](https://linux-hardware.org/?probe=3633557547) | Jun 06, 2019 |
| Acer          | Aspire V3-571G              | [116b742db8](https://linux-hardware.org/?probe=116b742db8) | Jun 05, 2019 |
| Dell          | Latitude E6410              | [91ff183bf0](https://linux-hardware.org/?probe=91ff183bf0) | Jun 02, 2019 |
| Dell          | Latitude E6410              | [3029853366](https://linux-hardware.org/?probe=3029853366) | Jun 02, 2019 |
| ASUSTek       | 1005PX                      | [33f338599d](https://linux-hardware.org/?probe=33f338599d) | May 29, 2019 |
| ASUSTek       | X541NA                      | [b8a49028c8](https://linux-hardware.org/?probe=b8a49028c8) | May 27, 2019 |
| ASUSTek       | N550JV                      | [1f0902bced](https://linux-hardware.org/?probe=1f0902bced) | May 17, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [89b4ae088c](https://linux-hardware.org/?probe=89b4ae088c) | May 16, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [4626315623](https://linux-hardware.org/?probe=4626315623) | May 14, 2019 |
| Dell          | Vostro 1500                 | [7008fbfa25](https://linux-hardware.org/?probe=7008fbfa25) | May 13, 2019 |
| HP            | EliteBook 8460w             | [2e2a41395d](https://linux-hardware.org/?probe=2e2a41395d) | May 07, 2019 |
| HP            | EliteBook Revolve 810 G3    | [e50b27ba1a](https://linux-hardware.org/?probe=e50b27ba1a) | Apr 27, 2019 |
| ASUSTek       | N501VW                      | [976a879300](https://linux-hardware.org/?probe=976a879300) | Apr 27, 2019 |
| Acer          | Aspire 5738                 | [9b6046b160](https://linux-hardware.org/?probe=9b6046b160) | Apr 22, 2019 |
| Fujitsu       | LIFEBOOK AH530/HD6          | [7c65853191](https://linux-hardware.org/?probe=7c65853191) | Apr 21, 2019 |
| Dell          | Inspiron 5567               | [cc9157e4bd](https://linux-hardware.org/?probe=cc9157e4bd) | Apr 14, 2019 |
| Lenovo        | V330-15IKB 81AX             | [1218f381aa](https://linux-hardware.org/?probe=1218f381aa) | Apr 11, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [b9f44fe73b](https://linux-hardware.org/?probe=b9f44fe73b) | Apr 11, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ea6eec5a29](https://linux-hardware.org/?probe=ea6eec5a29) | Apr 03, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f7854f2bb7](https://linux-hardware.org/?probe=f7854f2bb7) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | [2dd89e3983](https://linux-hardware.org/?probe=2dd89e3983) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | [9e505ea7e9](https://linux-hardware.org/?probe=9e505ea7e9) | Apr 03, 2019 |
| HP            | EliteBook 8470p             | [2d5727bd09](https://linux-hardware.org/?probe=2d5727bd09) | Apr 02, 2019 |
| HP            | EliteBook 8570p             | [fd1396f058](https://linux-hardware.org/?probe=fd1396f058) | Mar 29, 2019 |
| Lenovo        | V330-15IKB 81AX             | [ec89277577](https://linux-hardware.org/?probe=ec89277577) | Mar 09, 2019 |
| Acer          | Aspire A715-71G             | [b01e1626a7](https://linux-hardware.org/?probe=b01e1626a7) | Oct 31, 2018 |
| ASUSTek       | GL553VE                     | [3cdb244ea4](https://linux-hardware.org/?probe=3cdb244ea4) | Mar 31, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Iran/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 71        | 15.96%  |
| Ubuntu 18.04        | 55        | 12.36%  |
| Ubuntu 22.04        | 33        | 7.42%   |
| Arch Rolling        | 14        | 3.15%   |
| Fedora 33           | 13        | 2.92%   |
| Arch                | 13        | 2.92%   |
| Ubuntu 19.04        | 10        | 2.25%   |
| Fedora 34           | 8         | 1.8%    |
| Ubuntu 21.10        | 7         | 1.57%   |
| Ubuntu 20.10        | 7         | 1.57%   |
| KDE neon 20.04      | 7         | 1.57%   |
| Ubuntu 19.10        | 6         | 1.35%   |
| Manjaro             | 6         | 1.35%   |
| Fedora 37           | 6         | 1.35%   |
| Debian 11           | 6         | 1.35%   |
| Xubuntu 18.04       | 5         | 1.12%   |
| Ubuntu 21.04        | 5         | 1.12%   |
| OpenMandriva 4.2    | 5         | 1.12%   |
| Fedora 35           | 5         | 1.12%   |
| ArcoLinux Rolling   | 5         | 1.12%   |
| Ubuntu 18.10        | 4         | 0.9%    |
| Xubuntu 22.04       | 3         | 0.67%   |
| Xubuntu 20.04       | 3         | 0.67%   |
| Ubuntu Budgie 20.04 | 3         | 0.67%   |
| Ubuntu 22.10        | 3         | 0.67%   |
| Pop!_OS 22.04       | 3         | 0.67%   |
| OpenMandriva 4.3    | 3         | 0.67%   |
| Linux Mint 20.2     | 3         | 0.67%   |
| Linux Mint 19.3     | 3         | 0.67%   |
| Kubuntu 20.04       | 3         | 0.67%   |
| Kali 2021.2         | 3         | 0.67%   |
| Fedora 38           | 3         | 0.67%   |
| Fedora 36           | 3         | 0.67%   |
| Fedora 31           | 3         | 0.67%   |
| Debian              | 3         | 0.67%   |
| Zorin 16            | 2         | 0.45%   |
| Zorin 15            | 2         | 0.45%   |
| Ubuntu Unity 20.04  | 2         | 0.45%   |
| Ubuntu 23.04        | 2         | 0.45%   |
| Ubuntu 17.10        | 2         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 200       | 46.62%  |
| Fedora        | 41        | 9.56%   |
| Arch          | 25        | 5.83%   |
| Manjaro       | 19        | 4.43%   |
| Endless       | 14        | 3.26%   |
| OpenMandriva  | 12        | 2.8%    |
| Linux Mint    | 12        | 2.8%    |
| Debian        | 12        | 2.8%    |
| Xubuntu       | 11        | 2.56%   |
| KDE neon      | 11        | 2.56%   |
| Kali          | 11        | 2.56%   |
| Kubuntu       | 9         | 2.1%    |
| Pop!_OS       | 8         | 1.86%   |
| ArcoLinux     | 5         | 1.17%   |
| Zorin         | 4         | 0.93%   |
| ROSA          | 4         | 0.93%   |
| Ubuntu Unity  | 3         | 0.7%    |
| Ubuntu Budgie | 3         | 0.7%    |
| openSUSE      | 3         | 0.7%    |
| Gentoo        | 3         | 0.7%    |
| Lubuntu       | 2         | 0.47%   |
| Elementary    | 2         | 0.47%   |
| CentOS        | 2         | 0.47%   |
| Ubuntu MATE   | 1         | 0.23%   |
| Solus         | 1         | 0.23%   |
| Slackware     | 1         | 0.23%   |
| Sabayon       | 1         | 0.23%   |
| PureOS        | 1         | 0.23%   |
| Parch         | 1         | 0.23%   |
| NixOS         | 1         | 0.23%   |
| MX            | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| GNOME OS      | 1         | 0.23%   |
| Deepin        | 1         | 0.23%   |
| Clear Linux   | 1         | 0.23%   |
| Artix         | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 12        | 2.54%   |
| 5.3.0-46-generic         | 7         | 1.48%   |
| 5.4.0-26-generic         | 6         | 1.27%   |
| 5.8.0-63-generic         | 5         | 1.06%   |
| 5.4.0-52-generic         | 5         | 1.06%   |
| 5.15.0-56-generic        | 5         | 1.06%   |
| 5.15.0-47-generic        | 5         | 1.06%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.06%   |
| 5.0.0-13-generic         | 5         | 1.06%   |
| 5.8.0-48-generic         | 4         | 0.85%   |
| 5.4.0-58-generic         | 4         | 0.85%   |
| 5.3.0-40-generic         | 4         | 0.85%   |
| 5.11.0-41-generic        | 4         | 0.85%   |
| 5.11.0-27-generic        | 4         | 0.85%   |
| 5.0.0-23-generic         | 4         | 0.85%   |
| 4.18.0-25-generic        | 4         | 0.85%   |
| 4.18.0-15-generic        | 4         | 0.85%   |
| 5.8.0-59-generic         | 3         | 0.64%   |
| 5.4.0-40-generic         | 3         | 0.64%   |
| 5.3.0-51-generic         | 3         | 0.64%   |
| 5.19.0-35-generic        | 3         | 0.64%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.64%   |
| 5.15.0-58-generic        | 3         | 0.64%   |
| 5.15.0-46-generic        | 3         | 0.64%   |
| 5.15.0-33-generic        | 3         | 0.64%   |
| 5.13.0-22-generic        | 3         | 0.64%   |
| 5.0.0-37-generic         | 3         | 0.64%   |
| 5.0.0-25-generic         | 3         | 0.64%   |
| 4.18.0-16-generic        | 3         | 0.64%   |
| 4.15.0-15-generic        | 3         | 0.64%   |
| 6.4.0-3-amd64            | 2         | 0.42%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.42%   |
| 5.9.16-1-MANJARO         | 2         | 0.42%   |
| 5.8.18-1-MANJARO         | 2         | 0.42%   |
| 5.8.0-50-generic         | 2         | 0.42%   |
| 5.8.0-43-generic         | 2         | 0.42%   |
| 5.8.0-14-generic         | 2         | 0.42%   |
| 5.6.0-7-generic          | 2         | 0.42%   |
| 5.4.0-91-generic         | 2         | 0.42%   |
| 5.4.0-73-generic         | 2         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 71        | 15.57%  |
| 5.15.0  | 35        | 7.68%   |
| 5.0.0   | 26        | 5.7%    |
| 5.3.0   | 24        | 5.26%   |
| 5.8.0   | 23        | 5.04%   |
| 5.11.0  | 23        | 5.04%   |
| 4.15.0  | 23        | 5.04%   |
| 4.18.0  | 19        | 4.17%   |
| 5.13.0  | 18        | 3.95%   |
| 5.19.0  | 15        | 3.29%   |
| 5.10.0  | 12        | 2.63%   |
| 5.10.14 | 5         | 1.1%    |
| 5.16.7  | 4         | 0.88%   |
| 5.11.11 | 4         | 0.88%   |
| 4.13.0  | 4         | 0.88%   |
| 6.0.9   | 3         | 0.66%   |
| 5.9.16  | 3         | 0.66%   |
| 5.8.18  | 3         | 0.66%   |
| 5.6.0   | 3         | 0.66%   |
| 5.16.15 | 3         | 0.66%   |
| 5.14.16 | 3         | 0.66%   |
| 5.13.19 | 3         | 0.66%   |
| 6.4.2   | 2         | 0.44%   |
| 6.4.0   | 2         | 0.44%   |
| 6.2.6   | 2         | 0.44%   |
| 6.2.11  | 2         | 0.44%   |
| 6.2.0   | 2         | 0.44%   |
| 6.1.0   | 2         | 0.44%   |
| 5.7.0   | 2         | 0.44%   |
| 5.16.0  | 2         | 0.44%   |
| 5.15.4  | 2         | 0.44%   |
| 5.13.7  | 2         | 0.44%   |
| 5.13.13 | 2         | 0.44%   |
| 5.12.8  | 2         | 0.44%   |
| 6.4.7   | 1         | 0.22%   |
| 6.4.6   | 1         | 0.22%   |
| 6.4.3   | 1         | 0.22%   |
| 6.4.11  | 1         | 0.22%   |
| 6.3.8   | 1         | 0.22%   |
| 6.3.6   | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 76        | 16.85%  |
| 5.15    | 44        | 9.76%   |
| 5.8     | 31        | 6.87%   |
| 5.11    | 31        | 6.87%   |
| 5.0     | 28        | 6.21%   |
| 5.13    | 26        | 5.76%   |
| 5.10    | 26        | 5.76%   |
| 5.3     | 25        | 5.54%   |
| 4.15    | 23        | 5.1%    |
| 4.18    | 19        | 4.21%   |
| 5.19    | 17        | 3.77%   |
| 5.16    | 13        | 2.88%   |
| 5.14    | 10        | 2.22%   |
| 6.1     | 9         | 2%      |
| 6.4     | 8         | 1.77%   |
| 6.2     | 8         | 1.77%   |
| 6.3     | 7         | 1.55%   |
| 6.0     | 6         | 1.33%   |
| 5.6     | 6         | 1.33%   |
| 5.12    | 6         | 1.33%   |
| 5.9     | 5         | 1.11%   |
| 5.18    | 5         | 1.11%   |
| 4.13    | 4         | 0.89%   |
| 5.7     | 3         | 0.67%   |
| 4.19    | 3         | 0.67%   |
| 5.5     | 2         | 0.44%   |
| 5.17    | 2         | 0.44%   |
| 4.9     | 2         | 0.44%   |
| 5.2     | 1         | 0.22%   |
| 4.5     | 1         | 0.22%   |
| 4.20    | 1         | 0.22%   |
| 4.14    | 1         | 0.22%   |
| 4.12    | 1         | 0.22%   |
| 3.10    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 416       | 98.35%  |
| i686   | 7         | 1.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 232       | 53.58%  |
| Unknown         | 73        | 16.86%  |
| KDE5            | 41        | 9.47%   |
| XFCE            | 32        | 7.39%   |
| KDE             | 16        | 3.7%    |
| X-Cinnamon      | 9         | 2.08%   |
| i3              | 6         | 1.39%   |
| MATE            | 5         | 1.15%   |
| Unity           | 3         | 0.69%   |
| LXQt            | 3         | 0.69%   |
| Budgie          | 3         | 0.69%   |
| Pantheon        | 2         | 0.46%   |
| KDE4            | 2         | 0.46%   |
| Trinity         | 1         | 0.23%   |
| sway            | 1         | 0.23%   |
| GNOME Flashback | 1         | 0.23%   |
| enlightenment   | 1         | 0.23%   |
| Cinnamon        | 1         | 0.23%   |
| bspwm           | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 302       | 69.59%  |
| Wayland | 76        | 17.51%  |
| Unknown | 52        | 11.98%  |
| Tty     | 4         | 0.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 224       | 51.14%  |
| GDM     | 72        | 16.44%  |
| GDM3    | 54        | 12.33%  |
| SDDM    | 43        | 9.82%   |
| LightDM | 29        | 6.62%   |
| TDM     | 10        | 2.28%   |
| XDM     | 2         | 0.46%   |
| Ly      | 2         | 0.46%   |
| KDM     | 2         | 0.46%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 327       | 76.22%  |
| Unknown | 69        | 16.08%  |
| en_GB   | 11        | 2.56%   |
| fa_IR   | 7         | 1.63%   |
| C       | 6         | 1.4%    |
| en_CA   | 3         | 0.7%    |
| en_AG   | 2         | 0.47%   |
| POSIX   | 1         | 0.23%   |
| ja_JP   | 1         | 0.23%   |
| de_DE   | 1         | 0.23%   |
| az_IR   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 225       | 51.84%  |
| EFI  | 209       | 48.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 344       | 80.19%  |
| Btrfs   | 36        | 8.39%   |
| Overlay | 19        | 4.43%   |
| Unknown | 14        | 3.26%   |
| Zfs     | 6         | 1.4%    |
| Xfs     | 5         | 1.17%   |
| Tmpfs   | 3         | 0.7%    |
| Ext3    | 1         | 0.23%   |
| Ext2    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 243       | 56.91%  |
| GPT     | 148       | 34.66%  |
| MBR     | 36        | 8.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 360       | 83.92%  |
| Yes       | 69        | 16.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 224       | 52.46%  |
| Yes       | 203       | 47.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ASUSTek Computer | 126       | 29.79%  |
| Lenovo           | 113       | 26.71%  |
| Hewlett-Packard  | 61        | 14.42%  |
| Dell             | 38        | 8.98%   |
| Acer             | 38        | 8.98%   |
| MSI              | 14        | 3.31%   |
| Sony             | 13        | 3.07%   |
| Toshiba          | 7         | 1.65%   |
| Fujitsu          | 3         | 0.71%   |
| Apple            | 3         | 0.71%   |
| Timi             | 1         | 0.24%   |
| Razer            | 1         | 0.24%   |
| Packard Bell     | 1         | 0.24%   |
| LG Electronics   | 1         | 0.24%   |
| HIGRADED         | 1         | 0.24%   |
| Alienware        | 1         | 0.24%   |
| Unknown          | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-15IKB 81DE         | 6         | 1.42%   |
| HP ProBook 4540s                      | 6         | 1.42%   |
| Acer Aspire V3-571G                   | 6         | 1.42%   |
| Lenovo IdeaPad Z510 20287             | 5         | 1.18%   |
| Lenovo G50-70 20351                   | 4         | 0.95%   |
| HP Pavilion g6                        | 4         | 0.95%   |
| HP EliteBook 8470p                    | 4         | 0.95%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR  | 4         | 0.95%   |
| Lenovo Z50-70 20354                   | 3         | 0.71%   |
| Lenovo IdeaPad 5 15ITL05 82FG         | 3         | 0.71%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.71%   |
| HP EliteBook 840 G2                   | 3         | 0.71%   |
| ASUS X580VD                           | 3         | 0.71%   |
| ASUS K55VD                            | 3         | 0.71%   |
| Toshiba PORTEGE X30-D                 | 2         | 0.47%   |
| MSI Prestige 14 A10RB                 | 2         | 0.47%   |
| Lenovo ThinkPad X250 20CM002XUS       | 2         | 0.47%   |
| Lenovo ThinkPad E15 20RD0086UE        | 2         | 0.47%   |
| Lenovo Legion 5 15IMH05H 81Y6         | 2         | 0.47%   |
| Lenovo Legion 5 15ARH05H 82B1         | 2         | 0.47%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW    | 2         | 0.47%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 2         | 0.47%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 2         | 0.47%   |
| Lenovo IdeaPad 520-15IKB 81BF         | 2         | 0.47%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 2         | 0.47%   |
| Lenovo IdeaPad 330-15IGM 81D1         | 2         | 0.47%   |
| Lenovo G50-80 80E5                    | 2         | 0.47%   |
| Lenovo Flex 2-15 20405                | 2         | 0.47%   |
| Lenovo B570e HuronRiver Platform      | 2         | 0.47%   |
| HP ZBook 15                           | 2         | 0.47%   |
| HP ProBook 450 G4                     | 2         | 0.47%   |
| HP Pavilion dv6                       | 2         | 0.47%   |
| HP Laptop 15-bs0xx                    | 2         | 0.47%   |
| HP EliteBook Revolve 810 G3           | 2         | 0.47%   |
| HP EliteBook 8570p                    | 2         | 0.47%   |
| Dell Vostro 1510                      | 2         | 0.47%   |
| Dell Vostro 1015                      | 2         | 0.47%   |
| Dell Latitude E7470                   | 2         | 0.47%   |
| Dell Latitude E6530                   | 2         | 0.47%   |
| Dell Inspiron N5110                   | 2         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 45        | 10.64%  |
| ASUS VivoBook     | 33        | 7.8%    |
| Acer Aspire       | 32        | 7.57%   |
| Lenovo ThinkPad   | 31        | 7.33%   |
| HP EliteBook      | 24        | 5.67%   |
| HP ProBook        | 14        | 3.31%   |
| Dell Inspiron     | 14        | 3.31%   |
| Dell Latitude     | 13        | 3.07%   |
| HP Pavilion       | 10        | 2.36%   |
| Lenovo Legion     | 8         | 1.89%   |
| Dell Vostro       | 8         | 1.89%   |
| ASUS ASUS         | 8         | 1.89%   |
| Toshiba Satellite | 4         | 0.95%   |
| Lenovo G50-70     | 4         | 0.95%   |
| HP ZBook          | 4         | 0.95%   |
| ASUS ROG          | 4         | 0.95%   |
| Toshiba PORTEGE   | 3         | 0.71%   |
| MSI Modern        | 3         | 0.71%   |
| Lenovo Z50-70     | 3         | 0.71%   |
| Fujitsu LIFEBOOK  | 3         | 0.71%   |
| ASUS X580VD       | 3         | 0.71%   |
| ASUS K55VD        | 3         | 0.71%   |
| Acer TravelMate   | 3         | 0.71%   |
| MSI Prestige      | 2         | 0.47%   |
| MSI GE60          | 2         | 0.47%   |
| Lenovo ThinkBook  | 2         | 0.47%   |
| Lenovo G580       | 2         | 0.47%   |
| Lenovo G50-80     | 2         | 0.47%   |
| Lenovo Flex       | 2         | 0.47%   |
| Lenovo B570e      | 2         | 0.47%   |
| HP OMEN           | 2         | 0.47%   |
| HP Laptop         | 2         | 0.47%   |
| ASUS ZenBook      | 2         | 0.47%   |
| ASUS X550VX       | 2         | 0.47%   |
| ASUS X550IU       | 2         | 0.47%   |
| ASUS X542UN       | 2         | 0.47%   |
| ASUS N53SV        | 2         | 0.47%   |
| ASUS N501VW       | 2         | 0.47%   |
| Timi RedmiBook    | 1         | 0.24%   |
| Sony VPCZ126GG    | 1         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 43        | 10.17%  |
| 2017 | 40        | 9.46%   |
| 2012 | 38        | 8.98%   |
| 2019 | 37        | 8.75%   |
| 2010 | 35        | 8.27%   |
| 2011 | 31        | 7.33%   |
| 2015 | 30        | 7.09%   |
| 2020 | 29        | 6.86%   |
| 2018 | 28        | 6.62%   |
| 2016 | 27        | 6.38%   |
| 2014 | 25        | 5.91%   |
| 2021 | 23        | 5.44%   |
| 2009 | 12        | 2.84%   |
| 2022 | 10        | 2.36%   |
| 2008 | 10        | 2.36%   |
| 2006 | 3         | 0.71%   |
| 2007 | 2         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 423       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 395       | 92.94%  |
| Enabled  | 30        | 7.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 423       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 147       | 34.59%  |
| 8.01-16.0  | 90        | 21.18%  |
| 3.01-4.0   | 82        | 19.29%  |
| 16.01-24.0 | 68        | 16%     |
| 32.01-64.0 | 15        | 3.53%   |
| 1.01-2.0   | 11        | 2.59%   |
| 2.01-3.0   | 6         | 1.41%   |
| 24.01-32.0 | 3         | 0.71%   |
| 0.51-1.0   | 3         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 145       | 31.87%  |
| 2.01-3.0   | 131       | 28.79%  |
| 3.01-4.0   | 84        | 18.46%  |
| 4.01-8.0   | 60        | 13.19%  |
| 0.51-1.0   | 23        | 5.05%   |
| 8.01-16.0  | 9         | 1.98%   |
| 0.01-0.5   | 2         | 0.44%   |
| 16.01-24.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 295       | 68.76%  |
| 2      | 124       | 28.9%   |
| 3      | 8         | 1.86%   |
| 0      | 2         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 231       | 54.35%  |
| Yes       | 194       | 45.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 359       | 84.67%  |
| No        | 65        | 15.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 419       | 99.05%  |
| No        | 4         | 0.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 347       | 81.46%  |
| No        | 79        | 18.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Iran    | 423       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 250       | 56.43%  |
| TehrДЃn                      | 34        | 7.67%   |
| Mashhad                        | 20        | 4.51%   |
| Isfahan                        | 14        | 3.16%   |
| Khorramshahr                   | 7         | 1.58%   |
| Tajrish                        | 6         | 1.35%   |
| Tabriz                         | 6         | 1.35%   |
| Karaj                          | 6         | 1.35%   |
| Rasht                          | 5         | 1.13%   |
| Qom                            | 5         | 1.13%   |
| Babol                          | 5         | 1.13%   |
| TajrД«sh                     | 3         | 0.68%   |
| Shiraz                         | 3         | 0.68%   |
| Sanandij                       | 3         | 0.68%   |
| Kerman                         | 3         | 0.68%   |
| Gorgan                         | 3         | 0.68%   |
| Ahvaz                          | 3         | 0.68%   |
| Zanjan                         | 2         | 0.45%   |
| Yazd                           | 2         | 0.45%   |
| Shahre Jadide Andisheh         | 2         | 0.45%   |
| Shahr-e Qods                   | 2         | 0.45%   |
| Shahr-e Kord                   | 2         | 0.45%   |
| Qazvin                         | 2         | 0.45%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.23%   |
| Varamin                        | 1         | 0.23%   |
| Şowmeeh Sarā                 | 1         | 0.23%   |
| ShДЃhД«n Shahr             | 1         | 0.23%   |
| Shirvan                        | 1         | 0.23%   |
| ShahrД«ДЃr                 | 1         | 0.23%   |
| Shahedshahr                    | 1         | 0.23%   |
| Shādegān                     | 1         | 0.23%   |
| SemÄ«rom                     | 1         | 0.23%   |
| Sari                           | 1         | 0.23%   |
| SalmДЃs                      | 1         | 0.23%   |
| Sakdeh Alvand                  | 1         | 0.23%   |
| Rūdsar                        | 1         | 0.23%   |
| Robat Karim                    | 1         | 0.23%   |
| Rey                            | 1         | 0.23%   |
| RÅ«dÄn                    | 1         | 0.23%   |
| RafsanjДЃn                   | 1         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 99        | 120    | 18.27%  |
| WDC                          | 91        | 104    | 16.79%  |
| Toshiba                      | 81        | 94     | 14.94%  |
| Samsung Electronics          | 71        | 77     | 13.1%   |
| Micron Technology            | 21        | 23     | 3.87%   |
| HGST                         | 21        | 25     | 3.87%   |
| SanDisk                      | 19        | 23     | 3.51%   |
| A-DATA Technology            | 18        | 23     | 3.32%   |
| Intel                        | 15        | 15     | 2.77%   |
| Unknown                      | 11        | 12     | 2.03%   |
| SK hynix                     | 10        | 11     | 1.85%   |
| Kingston                     | 8         | 11     | 1.48%   |
| Hitachi                      | 8         | 8      | 1.48%   |
| Lexar                        | 7         | 8      | 1.29%   |
| PNY                          | 6         | 7      | 1.11%   |
| Kingmax                      | 4         | 4      | 0.74%   |
| Plextor                      | 3         | 3      | 0.55%   |
| Gigabyte Technology          | 3         | 4      | 0.55%   |
| Apacer                       | 3         | 3      | 0.55%   |
| ValueTech                    | 2         | 3      | 0.37%   |
| Union Memory                 | 2         | 2      | 0.37%   |
| Silicon Motion               | 2         | 2      | 0.37%   |
| LITEONIT                     | 2         | 3      | 0.37%   |
| LITEON                       | 2         | 3      | 0.37%   |
| Biostar                      | 2         | 3      | 0.37%   |
| Apple                        | 2         | 3      | 0.37%   |
| XPG                          | 1         | 1      | 0.18%   |
| VC-500                       | 1         | 1      | 0.18%   |
| USB3.0                       | 1         | 1      | 0.18%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.18%   |
| UMIS                         | 1         | 1      | 0.18%   |
| TwinMOS                      | 1         | 1      | 0.18%   |
| Transcend                    | 1         | 1      | 0.18%   |
| Teleplan                     | 1         | 3      | 0.18%   |
| Team                         | 1         | 1      | 0.18%   |
| SSSTC                        | 1         | 1      | 0.18%   |
| SPCC                         | 1         | 1      | 0.18%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.18%   |
| Phison                       | 1         | 1      | 0.18%   |
| OCZ                          | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 38        | 6.95%   |
| Toshiba MQ01ABD100 1TB                               | 20        | 3.66%   |
| Toshiba MQ04ABF100 1TB                               | 18        | 3.29%   |
| Seagate ST9500325AS 500GB                            | 11        | 2.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 11        | 2.01%   |
| WDC WD10SPZX-08Z10 1TB                               | 10        | 1.83%   |
| WDC WD10SPZX-24Z10 1TB                               | 8         | 1.46%   |
| Samsung SSD 860 EVO 500GB                            | 8         | 1.46%   |
| Samsung SSD 860 EVO 250GB                            | 8         | 1.46%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 7         | 1.28%   |
| Toshiba MQ01ABF050 500GB                             | 7         | 1.28%   |
| Micron 2210_MTFDHBA512QFD 512GB                      | 6         | 1.1%    |
| HGST HTS721010A9E630 1TB                             | 5         | 0.91%   |
| A-DATA SU650 120GB SSD                               | 5         | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 4         | 0.73%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 4         | 0.73%   |
| Unknown MMC Card  32GB                               | 4         | 0.73%   |
| Toshiba MQ01ABD075 752GB                             | 4         | 0.73%   |
| Toshiba MQ01ABD050V 500GB                            | 4         | 0.73%   |
| Seagate ST9500420AS 500GB                            | 4         | 0.73%   |
| Seagate ST2000LM007-1R8174 2TB                       | 4         | 0.73%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                   | 4         | 0.73%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                  | 4         | 0.73%   |
| Intel NVMe SSD Drive 512GB                           | 4         | 0.73%   |
| HGST HTS541010B7E610 1TB                             | 4         | 0.73%   |
| HGST HTS541010A9E680 1TB                             | 4         | 0.73%   |
| WDC WD10SPZX-80Z10T2 1TB                             | 3         | 0.55%   |
| Toshiba MQ01ABD050 500GB                             | 3         | 0.55%   |
| SK hynix HFM001TD3JX013N 1TB                         | 3         | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                      | 3         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB                       | 3         | 0.55%   |
| Samsung SSD 870 EVO 500GB                            | 3         | 0.55%   |
| Samsung SSD 850 EVO 250GB                            | 3         | 0.55%   |
| Samsung NVMe SSD Drive 1024GB                        | 3         | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 3         | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 3         | 0.55%   |
| PNY CS900 480GB SSD                                  | 3         | 0.55%   |
| Lexar 128GB SSD                                      | 3         | 0.55%   |
| HGST HTS541075A9E680 752GB                           | 3         | 0.55%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 120    | 35.23%  |
| WDC                 | 74        | 81     | 26.33%  |
| Toshiba             | 73        | 82     | 25.98%  |
| HGST                | 21        | 25     | 7.47%   |
| Hitachi             | 8         | 8      | 2.85%   |
| USB3.0              | 1         | 1      | 0.36%   |
| Unknown             | 1         | 1      | 0.36%   |
| Teleplan            | 1         | 3      | 0.36%   |
| Samsung Electronics | 1         | 1      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| Apple               | 1         | 2      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 47     | 26.09%  |
| A-DATA Technology   | 18        | 23     | 11.18%  |
| WDC                 | 16        | 19     | 9.94%   |
| SanDisk             | 13        | 16     | 8.07%   |
| Micron Technology   | 10        | 10     | 6.21%   |
| Lexar               | 6         | 7      | 3.73%   |
| Toshiba             | 5         | 9      | 3.11%   |
| SK hynix            | 5         | 5      | 3.11%   |
| PNY                 | 5         | 5      | 3.11%   |
| Kingston            | 5         | 7      | 3.11%   |
| Plextor             | 3         | 3      | 1.86%   |
| Intel               | 3         | 3      | 1.86%   |
| Gigabyte Technology | 3         | 4      | 1.86%   |
| Apacer              | 3         | 3      | 1.86%   |
| ValueTech           | 2         | 3      | 1.24%   |
| LITEONIT            | 2         | 3      | 1.24%   |
| LITEON              | 2         | 3      | 1.24%   |
| Kingmax             | 2         | 2      | 1.24%   |
| Biostar             | 2         | 3      | 1.24%   |
| TwinMOS             | 1         | 1      | 0.62%   |
| Transcend           | 1         | 1      | 0.62%   |
| Team                | 1         | 1      | 0.62%   |
| SSSTC               | 1         | 1      | 0.62%   |
| SPCC                | 1         | 1      | 0.62%   |
| OCZ                 | 1         | 1      | 0.62%   |
| Netac               | 1         | 1      | 0.62%   |
| MSI                 | 1         | 1      | 0.62%   |
| KODAK               | 1         | 1      | 0.62%   |
| GeIL                | 1         | 1      | 0.62%   |
| Crucial             | 1         | 1      | 0.62%   |
| China               | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 278       | 325    | 52.06%  |
| SSD     | 157       | 189    | 29.4%   |
| NVMe    | 86        | 97     | 16.1%   |
| MMC     | 8         | 9      | 1.5%    |
| Unknown | 5         | 6      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 368       | 512    | 78.63%  |
| NVMe | 86        | 97     | 18.38%  |
| MMC  | 8         | 9      | 1.71%   |
| SAS  | 6         | 8      | 1.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 226       | 285    | 54.2%   |
| 0.51-1.0   | 181       | 218    | 43.41%  |
| 1.01-2.0   | 10        | 11     | 2.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 125       | 28.41%  |
| 251-500        | 88        | 20%     |
| 501-1000       | 79        | 17.95%  |
| 51-100         | 38        | 8.64%   |
| 1001-2000      | 36        | 8.18%   |
| 21-50          | 30        | 6.82%   |
| 1-20           | 29        | 6.59%   |
| Unknown        | 10        | 2.27%   |
| 2001-3000      | 3         | 0.68%   |
| More than 3000 | 2         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 165       | 36.5%   |
| 21-50          | 84        | 18.58%  |
| 51-100         | 59        | 13.05%  |
| 101-250        | 54        | 11.95%  |
| 501-1000       | 38        | 8.41%   |
| 251-500        | 36        | 7.96%   |
| Unknown        | 10        | 2.21%   |
| 1001-2000      | 3         | 0.66%   |
| 2001-3000      | 2         | 0.44%   |
| More than 3000 | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 5         | 6      | 12.2%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 3      | 7.32%   |
| Seagate ST9500325AS 500GB                      | 3         | 3      | 7.32%   |
| Toshiba MQ01ABD075 752GB                       | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD050 500GB                       | 2         | 2      | 4.88%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 4.88%   |
| HGST HTS541075A9E680 752GB                     | 2         | 2      | 4.88%   |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 2.44%   |
| WDC WD5000LPVX-80V0TT0 500GB                   | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 1      | 2.44%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 2.44%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 2.44%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 2.44%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXN 320GB                       | 1         | 1      | 2.44%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 2.44%   |
| SSSTC CVB-8D128-HP 128GB                       | 1         | 1      | 2.44%   |
| SK hynix SC308 SATA 256GB SSD                  | 1         | 1      | 2.44%   |
| Seagate ST9250315AS 250GB                      | 1         | 2      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 2.44%   |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 2.44%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 2.44%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS541080G9SA00 80GB                   | 1         | 1      | 2.44%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 13        | 15     | 31.71%  |
| Toshiba           | 11        | 11     | 26.83%  |
| WDC               | 6         | 6      | 14.63%  |
| Hitachi           | 4         | 4      | 9.76%   |
| HGST              | 4         | 4      | 9.76%   |
| SSSTC             | 1         | 1      | 2.44%   |
| SK hynix          | 1         | 1      | 2.44%   |
| Micron Technology | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 13        | 15     | 35.14%  |
| Toshiba | 11        | 11     | 29.73%  |
| WDC     | 5         | 5      | 13.51%  |
| Hitachi | 4         | 4      | 10.81%  |
| HGST    | 4         | 4      | 10.81%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 39     | 89.74%  |
| SSD  | 4         | 4      | 10.26%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 266       | 387    | 59.91%  |
| Works    | 139       | 195    | 31.31%  |
| Malfunc  | 38        | 43     | 8.56%   |
| Failed   | 1         | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 359       | 75.26%  |
| AMD                          | 37        | 7.76%   |
| Samsung Electronics          | 29        | 6.08%   |
| Micron Technology            | 11        | 2.31%   |
| SanDisk                      | 10        | 2.1%    |
| Union Memory (Shenzhen)      | 5         | 1.05%   |
| SK hynix                     | 5         | 1.05%   |
| Phison Electronics           | 4         | 0.84%   |
| Silicon Motion               | 3         | 0.63%   |
| Kingston Technology Company  | 3         | 0.63%   |
| Toshiba America Info Systems | 2         | 0.42%   |
| Shenzhen Longsys Electronics | 2         | 0.42%   |
| Nvidia                       | 2         | 0.42%   |
| Realtek Semiconductor        | 1         | 0.21%   |
| Micron/Crucial Technology    | 1         | 0.21%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.21%   |
| KIOXIA                       | 1         | 0.21%   |
| ADATA Technology             | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 51        | 10.06%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 39        | 7.69%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 37        | 7.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 31        | 6.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 24        | 4.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 22        | 4.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 22        | 4.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 22        | 4.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 4.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 21        | 4.14%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 3.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 2.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 2.37%   |
| Samsung NVMe SSD Controller 980                                                | 10        | 1.97%   |
| Intel SSD 660P Series                                                          | 9         | 1.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 9         | 1.78%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 8         | 1.58%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 1.58%   |
| Intel Comet Lake SATA AHCI Controller                                          | 8         | 1.58%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 4         | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.59%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.59%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 0.59%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 3         | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.59%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                          | 2         | 0.39%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 2         | 0.39%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.39%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                              | 2         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 343       | 69.72%  |
| NVMe | 86        | 17.48%  |
| RAID | 45        | 9.15%   |
| IDE  | 18        | 3.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 378       | 89.36%  |
| AMD    | 45        | 10.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 21        | 4.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 14        | 3.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 12        | 2.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 10        | 2.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 2.36%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 9         | 2.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 2.13%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 2.13%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 9         | 2.13%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 2.13%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz      | 8         | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 7         | 1.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 7         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 1.42%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 5         | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 5         | 1.18%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 5         | 1.18%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz      | 5         | 1.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 1.18%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 5         | 1.18%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 5         | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.95%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 0.95%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 4         | 0.95%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 4         | 0.95%   |
| Intel Core i5 CPU M 480 @ 2.67GHz       | 4         | 0.95%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 4         | 0.95%   |
| Intel 12th Gen Core i7-12700H           | 4         | 0.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 4         | 0.95%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 3         | 0.71%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 3         | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 0.71%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz       | 3         | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.71%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 3         | 0.71%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 3         | 0.71%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 3         | 0.71%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 3         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 157       | 37.12%  |
| Intel Core i5           | 121       | 28.61%  |
| Other                   | 28        | 6.62%   |
| Intel Core i3           | 21        | 4.96%   |
| Intel Core 2 Duo        | 18        | 4.26%   |
| AMD Ryzen 7             | 14        | 3.31%   |
| Intel Pentium           | 12        | 2.84%   |
| Intel Celeron           | 8         | 1.89%   |
| AMD Ryzen 5             | 7         | 1.65%   |
| Intel Atom              | 5         | 1.18%   |
| AMD FX                  | 4         | 0.95%   |
| Intel Pentium Dual-Core | 3         | 0.71%   |
| Intel Genuine           | 3         | 0.71%   |
| AMD Ryzen 3             | 3         | 0.71%   |
| AMD E1                  | 3         | 0.71%   |
| AMD A4                  | 3         | 0.71%   |
| AMD A10                 | 3         | 0.71%   |
| Intel Pentium Silver    | 2         | 0.47%   |
| AMD A6                  | 2         | 0.47%   |
| Intel Core M            | 1         | 0.24%   |
| Intel Core Duo          | 1         | 0.24%   |
| AMD Ryzen 9             | 1         | 0.24%   |
| AMD PRO A8              | 1         | 0.24%   |
| AMD PRO A10             | 1         | 0.24%   |
| AMD E2                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 231       | 54.61%  |
| 4      | 143       | 33.81%  |
| 6      | 20        | 4.73%   |
| 8      | 19        | 4.49%   |
| 14     | 5         | 1.18%   |
| 1      | 3         | 0.71%   |
| 10     | 2         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 423       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 362       | 85.58%  |
| 1      | 61        | 14.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 411       | 96.93%  |
| Unknown        | 9         | 2.12%   |
| 32-bit         | 4         | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 21.79%  |
| 0x306a9    | 35        | 8.03%   |
| 0x806ea    | 25        | 5.73%   |
| 0x206a7    | 24        | 5.5%    |
| 0x306d4    | 23        | 5.28%   |
| 0x20655    | 22        | 5.05%   |
| 0x306c3    | 17        | 3.9%    |
| 0x806e9    | 16        | 3.67%   |
| 0x806ec    | 14        | 3.21%   |
| 0x40651    | 13        | 2.98%   |
| 0x906e9    | 11        | 2.52%   |
| 0x1067a    | 11        | 2.52%   |
| 0x906ea    | 10        | 2.29%   |
| 0x806c1    | 10        | 2.29%   |
| 0x406e3    | 9         | 2.06%   |
| 0x506e3    | 8         | 1.83%   |
| 0xa0652    | 6         | 1.38%   |
| 0x906a3    | 6         | 1.38%   |
| 0x20652    | 6         | 1.38%   |
| 0x706e5    | 5         | 1.15%   |
| 0x106e5    | 5         | 1.15%   |
| 0x706a1    | 4         | 0.92%   |
| 0x10676    | 4         | 0.92%   |
| 0x0700010f | 4         | 0.92%   |
| 0x806d1    | 3         | 0.69%   |
| 0x6fd      | 3         | 0.69%   |
| 0x106ca    | 3         | 0.69%   |
| 0x0a50000c | 3         | 0.69%   |
| 0x08608103 | 3         | 0.69%   |
| 0x08108109 | 3         | 0.69%   |
| 0x0600611a | 3         | 0.69%   |
| 0x6e8      | 2         | 0.46%   |
| 0x30678    | 2         | 0.46%   |
| 0x0a50000d | 2         | 0.46%   |
| 0x08600104 | 2         | 0.46%   |
| 0x08108102 | 2         | 0.46%   |
| 0x07030105 | 2         | 0.46%   |
| 0x06006705 | 2         | 0.46%   |
| 0x06003109 | 2         | 0.46%   |
| 0x06003106 | 2         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 97        | 22.93%  |
| Haswell          | 47        | 11.11%  |
| IvyBridge        | 44        | 10.4%   |
| Westmere         | 30        | 7.09%   |
| SandyBridge      | 26        | 6.15%   |
| Skylake          | 24        | 5.67%   |
| Broadwell        | 23        | 5.44%   |
| Penryn           | 17        | 4.02%   |
| TigerLake        | 14        | 3.31%   |
| CometLake        | 9         | 2.13%   |
| Zen 3            | 8         | 1.89%   |
| IceLake          | 8         | 1.89%   |
| Excavator        | 8         | 1.89%   |
| Alderlake Hybrid | 8         | 1.89%   |
| Goldmont plus    | 7         | 1.65%   |
| Unknown          | 7         | 1.65%   |
| Zen+             | 6         | 1.42%   |
| Zen 2            | 5         | 1.18%   |
| Nehalem          | 5         | 1.18%   |
| Core             | 5         | 1.18%   |
| Steamroller      | 4         | 0.95%   |
| Silvermont       | 4         | 0.95%   |
| Jaguar           | 4         | 0.95%   |
| Bonnell          | 4         | 0.95%   |
| P6               | 3         | 0.71%   |
| Puma             | 2         | 0.47%   |
| Goldmont         | 2         | 0.47%   |
| K10 Llano        | 1         | 0.24%   |
| Bobcat           | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 337       | 49.78%  |
| Nvidia           | 222       | 32.79%  |
| AMD              | 117       | 17.28%  |
| ATI Technologies | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 40        | 5.79%   |
| Intel UHD Graphics 620                                                                | 29        | 4.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 24        | 3.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 23        | 3.33%   |
| Intel HD Graphics 620                                                                 | 22        | 3.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 22        | 3.18%   |
| Intel HD Graphics 5500                                                                | 21        | 3.04%   |
| Intel Core Processor Integrated Graphics Controller                                   | 18        | 2.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 2.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 14        | 2.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 13        | 1.88%   |
| Intel HD Graphics 630                                                                 | 13        | 1.88%   |
| Nvidia GP108M [GeForce MX150]                                                         | 12        | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 12        | 1.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 1.59%   |
| Intel HD Graphics 530                                                                 | 11        | 1.59%   |
| Nvidia GP107M [GeForce MX350]                                                         | 10        | 1.45%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 10        | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 10        | 1.45%   |
| Nvidia GM108M [GeForce MX110]                                                         | 9         | 1.3%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 9         | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 1.3%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 9         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 8         | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 8         | 1.16%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 7         | 1.01%   |
| Nvidia GM108M [GeForce 840M]                                                          | 7         | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 1.01%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 7         | 1.01%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 6         | 0.87%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 6         | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 0.87%   |
| AMD Lucienne                                                                          | 6         | 0.87%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 6         | 0.87%   |
| Nvidia TU117M [GeForce MX450]                                                         | 5         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 5         | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 0.72%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 5         | 0.72%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 5         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 185       | 43.74%  |
| 1 x Intel      | 94        | 22.22%  |
| Intel + AMD    | 55        | 13%     |
| 1 x AMD        | 41        | 9.69%   |
| 1 x Nvidia     | 25        | 5.91%   |
| AMD + Nvidia   | 12        | 2.84%   |
| 2 x AMD        | 10        | 2.36%   |
| 2 x Intel      | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 324       | 75.7%   |
| Proprietary | 95        | 22.2%   |
| Unknown     | 9         | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 196       | 45.48%  |
| 1.01-2.0   | 91        | 21.11%  |
| 3.01-4.0   | 56        | 12.99%  |
| 0.51-1.0   | 47        | 10.9%   |
| 0.01-0.5   | 31        | 7.19%   |
| 5.01-6.0   | 6         | 1.39%   |
| 7.01-8.0   | 3         | 0.7%    |
| 2.01-3.0   | 1         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 83        | 18.95%  |
| LG Display              | 80        | 18.26%  |
| BOE                     | 74        | 16.89%  |
| Chimei Innolux          | 66        | 15.07%  |
| Samsung Electronics     | 49        | 11.19%  |
| Goldstar                | 19        | 4.34%   |
| Chi Mei Optoelectronics | 11        | 2.51%   |
| PANDA                   | 10        | 2.28%   |
| HannStar                | 5         | 1.14%   |
| BenQ                    | 5         | 1.14%   |
| Apple                   | 4         | 0.91%   |
| LG Philips              | 3         | 0.68%   |
| Lenovo                  | 3         | 0.68%   |
| Sony                    | 2         | 0.46%   |
| Sharp                   | 2         | 0.46%   |
| InnoLux Display         | 2         | 0.46%   |
| InfoVision              | 2         | 0.46%   |
| CHD                     | 2         | 0.46%   |
| ASUSTek Computer        | 2         | 0.46%   |
| TMX                     | 1         | 0.23%   |
| Seiko/Epson             | 1         | 0.23%   |
| RTK                     | 1         | 0.23%   |
| Quanta Display          | 1         | 0.23%   |
| PAR                     | 1         | 0.23%   |
| Nvidia                  | 1         | 0.23%   |
| LGD                     | 1         | 0.23%   |
| KDC                     | 1         | 0.23%   |
| Hewlett-Packard         | 1         | 0.23%   |
| cPATH                   | 1         | 0.23%   |
| CHI                     | 1         | 0.23%   |
| AUS                     | 1         | 0.23%   |
| AOC                     | 1         | 0.23%   |
| Ancor Communications    | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 2.73%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 8         | 1.82%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 1.59%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 1.59%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 5         | 1.14%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 1.14%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 1.14%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.91%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.91%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.91%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.68%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 3         | 0.68%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.68%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.68%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch          | 3         | 0.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.68%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 3         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.46%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.46%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.46%   |
| LG Display LCD Monitor LGD0577 1920x1080 294x165mm 13.3-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 190       | 44.39%  |
| 1366x768 (WXGA)    | 163       | 38.08%  |
| 3840x2160 (4K)     | 16        | 3.74%   |
| 1600x900 (HD+)     | 15        | 3.5%    |
| 1280x800 (WXGA)    | 14        | 3.27%   |
| 1440x900 (WXGA+)   | 10        | 2.34%   |
| 1024x600           | 4         | 0.93%   |
| Unknown            | 3         | 0.7%    |
| 2560x1440 (QHD)    | 2         | 0.47%   |
| 1680x1050 (WSXGA+) | 2         | 0.47%   |
| 5760x2160          | 1         | 0.23%   |
| 3840x2400          | 1         | 0.23%   |
| 3840x1080          | 1         | 0.23%   |
| 2944x1080          | 1         | 0.23%   |
| 2880x1620          | 1         | 0.23%   |
| 2560x1600          | 1         | 0.23%   |
| 1920x1200 (WUXGA)  | 1         | 0.23%   |
| 1680x945           | 1         | 0.23%   |
| 1280x1024 (SXGA)   | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 273       | 62.76%  |
| 14      | 46        | 10.57%  |
| 13      | 37        | 8.51%   |
| 21      | 14        | 3.22%   |
| 12      | 11        | 2.53%   |
| 17      | 7         | 1.61%   |
| 20      | 6         | 1.38%   |
| 11      | 6         | 1.38%   |
| 10      | 5         | 1.15%   |
| Unknown | 5         | 1.15%   |
| 24      | 4         | 0.92%   |
| 23      | 4         | 0.92%   |
| 18      | 4         | 0.92%   |
| 16      | 4         | 0.92%   |
| 27      | 3         | 0.69%   |
| 19      | 2         | 0.46%   |
| 84      | 1         | 0.23%   |
| 46      | 1         | 0.23%   |
| 32      | 1         | 0.23%   |
| 22      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 345       | 79.31%  |
| 201-300     | 31        | 7.13%   |
| 401-500     | 27        | 6.21%   |
| 351-400     | 13        | 2.99%   |
| 501-600     | 10        | 2.3%    |
| Unknown     | 5         | 1.15%   |
| 701-800     | 1         | 0.23%   |
| 601-700     | 1         | 0.23%   |
| 1501-2000   | 1         | 0.23%   |
| 1001-1500   | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 370       | 91.81%  |
| 16/10   | 26        | 6.45%   |
| Unknown | 5         | 1.24%   |
| 4/3     | 1         | 0.25%   |
| 3/2     | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 274       | 62.99%  |
| 81-90          | 74        | 17.01%  |
| 201-250        | 23        | 5.29%   |
| 61-70          | 11        | 2.53%   |
| 151-200        | 9         | 2.07%   |
| 71-80          | 7         | 1.61%   |
| 51-60          | 6         | 1.38%   |
| 121-130        | 6         | 1.38%   |
| 41-50          | 5         | 1.15%   |
| Unknown        | 5         | 1.15%   |
| 301-350        | 3         | 0.69%   |
| 141-150        | 3         | 0.69%   |
| 91-100         | 3         | 0.69%   |
| 131-140        | 2         | 0.46%   |
| More than 1000 | 1         | 0.23%   |
| 351-500        | 1         | 0.23%   |
| 111-120        | 1         | 0.23%   |
| 501-1000       | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 196       | 46.01%  |
| 101-120       | 153       | 35.92%  |
| 51-100        | 52        | 12.21%  |
| More than 240 | 11        | 2.58%   |
| 161-240       | 8         | 1.88%   |
| Unknown       | 5         | 1.17%   |
| 1-50          | 1         | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 373       | 87.15%  |
| 2     | 44        | 10.28%  |
| 0     | 10        | 2.34%   |
| 3     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 250       | 35.71%  |
| Intel                    | 197       | 28.14%  |
| Qualcomm Atheros         | 105       | 15%     |
| Broadcom                 | 47        | 6.71%   |
| Ralink                   | 15        | 2.14%   |
| Broadcom Limited         | 15        | 2.14%   |
| MediaTek                 | 11        | 1.57%   |
| Xiaomi                   | 10        | 1.43%   |
| Samsung Electronics      | 10        | 1.43%   |
| Marvell Technology Group | 7         | 1%      |
| Huawei Technologies      | 4         | 0.57%   |
| Hewlett-Packard          | 4         | 0.57%   |
| TP-Link                  | 3         | 0.43%   |
| JMicron Technology       | 3         | 0.43%   |
| HTC (High Tech Computer) | 3         | 0.43%   |
| D-Link                   | 3         | 0.43%   |
| Qualcomm                 | 2         | 0.29%   |
| ASIX Electronics         | 2         | 0.29%   |
| Sierra Wireless          | 1         | 0.14%   |
| Ralink Technology        | 1         | 0.14%   |
| Nvidia                   | 1         | 0.14%   |
| LG Electronics           | 1         | 0.14%   |
| Lenovo                   | 1         | 0.14%   |
| ICS Advent               | 1         | 0.14%   |
| BUFFALO                  | 1         | 0.14%   |
| Attansic Technology      | 1         | 0.14%   |
| ASUSTek Computer         | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 186       | 22.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 36        | 4.39%   |
| Intel Wireless 7265                                               | 23        | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 2.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 2.2%    |
| Intel Wireless 7260                                               | 16        | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 15        | 1.83%   |
| Intel Wireless 8265 / 8275                                        | 15        | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 13        | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 12        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 1.1%    |
| Intel Wireless 8260                                               | 9         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 8         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.73%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 0.73%   |
| Intel Centrino Ultimate-N 6300                                    | 6         | 0.73%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 194       | 45.12%  |
| Qualcomm Atheros      | 90        | 20.93%  |
| Realtek Semiconductor | 66        | 15.35%  |
| Broadcom              | 32        | 7.44%   |
| Ralink                | 15        | 3.49%   |
| Broadcom Limited      | 12        | 2.79%   |
| MediaTek              | 10        | 2.33%   |
| Hewlett-Packard       | 3         | 0.7%    |
| TP-Link               | 2         | 0.47%   |
| D-Link                | 2         | 0.47%   |
| Xiaomi                | 1         | 0.23%   |
| Sierra Wireless       | 1         | 0.23%   |
| Ralink Technology     | 1         | 0.23%   |
| BUFFALO               | 1         | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 23        | 5.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 5.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 4.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 4.16%   |
| Intel Wireless 7260                                            | 16        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 3.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 15        | 3.46%   |
| Intel Wireless 8265 / 8275                                     | 15        | 3.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 3%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12        | 2.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 2.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 2.54%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 2.31%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 2.31%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 2.08%   |
| Intel Wireless 8260                                            | 9         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8         | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.62%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 1.39%   |
| Intel Centrino Ultimate-N 6300                                 | 6         | 1.39%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.39%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 1.15%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.92%   |
| Intel Wireless 3165                                            | 4         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 0.69%   |
| Intel Wireless 3160                                            | 3         | 0.69%   |
| Intel WiFi Link 5100                                           | 3         | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 226       | 58.85%  |
| Intel                    | 51        | 13.28%  |
| Qualcomm Atheros         | 32        | 8.33%   |
| Broadcom                 | 23        | 5.99%   |
| Samsung Electronics      | 10        | 2.6%    |
| Xiaomi                   | 9         | 2.34%   |
| Marvell Technology Group | 7         | 1.82%   |
| Huawei Technologies      | 4         | 1.04%   |
| JMicron Technology       | 3         | 0.78%   |
| HTC (High Tech Computer) | 3         | 0.78%   |
| Broadcom Limited         | 3         | 0.78%   |
| Qualcomm                 | 2         | 0.52%   |
| ASIX Electronics         | 2         | 0.52%   |
| TP-Link                  | 1         | 0.26%   |
| Nvidia                   | 1         | 0.26%   |
| MediaTek                 | 1         | 0.26%   |
| LG Electronics           | 1         | 0.26%   |
| Lenovo                   | 1         | 0.26%   |
| ICS Advent               | 1         | 0.26%   |
| Hewlett-Packard          | 1         | 0.26%   |
| D-Link                   | 1         | 0.26%   |
| Attansic Technology      | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 186       | 48.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 36        | 9.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 3.89%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 8         | 2.07%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 8         | 2.07%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 1.55%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 1.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 1.3%    |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.3%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 4         | 1.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 4         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.04%   |
| Huawei MLA-L11                                                                 | 4         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.78%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.78%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.78%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.78%   |
| Intel Ethernet Connection (16) I219-LM                                         | 3         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 2         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.52%   |
| Qualcomm Android                                                               | 2         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.52%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.52%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.52%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.52%   |
| HTC (High Tech Computer) HTC                                                   | 2         | 0.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 419       | 53.99%  |
| Ethernet | 356       | 45.88%  |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 358       | 85.85%  |
| Ethernet | 58        | 13.91%  |
| Unknown  | 1         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 342       | 80.85%  |
| 1     | 80        | 18.91%  |
| 0     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 394       | 92.27%  |
| Yes  | 33        | 7.73%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 39.71%  |
| IMC Networks                    | 51        | 14.57%  |
| Realtek Semiconductor           | 36        | 10.29%  |
| Qualcomm Atheros Communications | 27        | 7.71%   |
| Broadcom                        | 19        | 5.43%   |
| Lite-On Technology              | 15        | 4.29%   |
| Foxconn / Hon Hai               | 15        | 4.29%   |
| Ralink                          | 9         | 2.57%   |
| Dell                            | 9         | 2.57%   |
| ASUSTek Computer                | 8         | 2.29%   |
| Foxconn International           | 5         | 1.43%   |
| Ralink Technology               | 3         | 0.86%   |
| Apple                           | 3         | 0.86%   |
| Realtek                         | 2         | 0.57%   |
| Hewlett-Packard                 | 2         | 0.57%   |
| Cambridge Silicon Radio         | 2         | 0.57%   |
| Askey Computer                  | 2         | 0.57%   |
| Micro Star International        | 1         | 0.29%   |
| MediaTek                        | 1         | 0.29%   |
| Alps Electric                   | 1         | 0.29%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 71        | 20.29%  |
| Realtek Bluetooth Radio                                                             | 28        | 8%      |
| Intel AX201 Bluetooth                                                               | 25        | 7.14%   |
| IMC Networks Bluetooth Radio                                                        | 23        | 6.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 6%      |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 4%      |
| IMC Networks Bluetooth Device                                                       | 10        | 2.86%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 2.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 2%      |
| IMC Networks Wireless_Device                                                        | 7         | 2%      |
| ASUS BT-270 Bluetooth Adapter                                                       | 7         | 2%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 1.71%   |
| Intel AX200 Bluetooth                                                               | 6         | 1.71%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 1.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.43%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.43%   |
| Intel Bluetooth Device                                                              | 5         | 1.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 1.43%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 5         | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.14%   |
| Broadcom BCM20702A0                                                                 | 4         | 1.14%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 0.86%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.86%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.86%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.86%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.86%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.86%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.57%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.57%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.57%   |
| IMC Networks Bluetooth                                                              | 2         | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.57%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.57%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.57%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.57%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 375       | 71.98%  |
| Nvidia                 | 73        | 14.01%  |
| AMD                    | 65        | 12.48%  |
| ASUSTek Computer       | 4         | 0.77%   |
| Yamaha                 | 1         | 0.19%   |
| Generalplus Technology | 1         | 0.19%   |
| Focusrite-Novation     | 1         | 0.19%   |
| CMX Systems            | 1         | 0.19%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 63        | 10.02%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 44        | 7%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35        | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 26        | 4.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 3.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 3.97%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22        | 3.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 3.5%    |
| Intel Haswell-ULT HD Audio Controller                                      | 22        | 3.5%    |
| Intel 8 Series HD Audio Controller                                         | 22        | 3.5%    |
| Intel CM238 HD Audio Controller                                            | 15        | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 2.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 14        | 2.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 2.07%   |
| Nvidia GF108 High Definition Audio Controller                              | 12        | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.91%   |
| AMD FCH Azalia Controller                                                  | 12        | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 11        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 8         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.95%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 6         | 0.95%   |
| Nvidia GT216 HDMI Audio Controller                                         | 5         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.79%   |
| Nvidia Audio device                                                        | 5         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.64%   |
| ASUSTek Computer C-Media Audio                                             | 4         | 0.64%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 4         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 91        | 32.85%  |
| SK hynix            | 59        | 21.3%   |
| Micron Technology   | 40        | 14.44%  |
| Crucial             | 19        | 6.86%   |
| Kingston            | 17        | 6.14%   |
| Unknown             | 14        | 5.05%   |
| Ramaxel Technology  | 13        | 4.69%   |
| Elpida              | 11        | 3.97%   |
| A-DATA Technology   | 7         | 2.53%   |
| Transcend           | 1         | 0.36%   |
| Neo Forza           | 1         | 0.36%   |
| Nanya Technology    | 1         | 0.36%   |
| Kingmax             | 1         | 0.36%   |
| ASint Technology    | 1         | 0.36%   |
| Apacer              | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 8         | 2.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 7         | 2.38%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 2.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 2.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 2.04%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s        | 6         | 2.04%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 1.7%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 5         | 1.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 1.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 1.7%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 5         | 1.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 4         | 1.36%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 1.36%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 4         | 1.36%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 4         | 1.36%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 4         | 1.36%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 3         | 1.02%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 1.02%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 1.02%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 1.02%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 3         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.68%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.68%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s     | 2         | 0.68%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s     | 2         | 0.68%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.68%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 104       | 47.49%  |
| DDR3    | 89        | 40.64%  |
| DDR2    | 9         | 4.11%   |
| DDR5    | 6         | 2.74%   |
| SDRAM   | 5         | 2.28%   |
| LPDDR4  | 3         | 1.37%   |
| LPDDR3  | 2         | 0.91%   |
| Unknown | 1         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 205       | 94.91%  |
| Row Of Chips | 9         | 4.17%   |
| Chip         | 2         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 95        | 37.55%  |
| 4096  | 93        | 36.76%  |
| 16384 | 29        | 11.46%  |
| 2048  | 27        | 10.67%  |
| 1024  | 8         | 3.16%   |
| 32768 | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 65        | 26.64%  |
| 2667    | 50        | 20.49%  |
| 3200    | 31        | 12.7%   |
| 1334    | 22        | 9.02%   |
| 2400    | 15        | 6.15%   |
| 2133    | 13        | 5.33%   |
| 3266    | 8         | 3.28%   |
| 667     | 7         | 2.87%   |
| 4800    | 6         | 2.46%   |
| 1333    | 6         | 2.46%   |
| Unknown | 6         | 2.46%   |
| 4199    | 5         | 2.05%   |
| 8400    | 3         | 1.23%   |
| 1067    | 3         | 1.23%   |
| 4266    | 1         | 0.41%   |
| 1867    | 1         | 0.41%   |
| 800     | 1         | 0.41%   |
| 533     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP LaserJet P1102      | 1         | 50%     |
| HP DeskJet 2130 series | 1         | 50%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 50%     |
| Canon CanoScan 4400F    | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 90        | 22.9%   |
| IMC Networks                           | 87        | 22.14%  |
| Realtek Semiconductor                  | 30        | 7.63%   |
| Bison Electronics                      | 27        | 6.87%   |
| Microdia                               | 24        | 6.11%   |
| Syntek                                 | 18        | 4.58%   |
| Sunplus Innovation Technology          | 17        | 4.33%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 4.07%   |
| Acer                                   | 11        | 2.8%    |
| Lite-On Technology                     | 10        | 2.54%   |
| Suyin                                  | 9         | 2.29%   |
| Sonix Technology                       | 9         | 2.29%   |
| Quanta                                 | 9         | 2.29%   |
| Ricoh                                  | 7         | 1.78%   |
| Apple                                  | 7         | 1.78%   |
| Samsung Electronics                    | 3         | 0.76%   |
| Lenovo                                 | 3         | 0.76%   |
| ALi                                    | 3         | 0.76%   |
| Alcor Micro                            | 3         | 0.76%   |
| Pixart Imaging                         | 2         | 0.51%   |
| Importek                               | 2         | 0.51%   |
| Silicon Motion                         | 1         | 0.25%   |
| Primax Electronics                     | 1         | 0.25%   |
| OmniVision Technologies                | 1         | 0.25%   |
| Luxvisions Innotech Limited            | 1         | 0.25%   |
| LG Electronics                         | 1         | 0.25%   |
| Goertek Electronics                    | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 33        | 8.4%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 17        | 4.33%   |
| IMC Networks Integrated Camera                      | 16        | 4.07%   |
| Chicony Integrated Camera                           | 14        | 3.56%   |
| Chicony USB2.0 HD UVC WebCam                        | 9         | 2.29%   |
| IMC Networks Lenovo EasyCamera                      | 8         | 2.04%   |
| Chicony EasyCamera                                  | 8         | 2.04%   |
| Bison Lenovo EasyCamera                             | 8         | 2.04%   |
| Sonix USB2.0 HD UVC WebCam                          | 7         | 1.78%   |
| Chicony HD WebCam                                   | 7         | 1.78%   |
| Syntek Integrated Camera                            | 6         | 1.53%   |
| Syntek EasyCamera                                   | 6         | 1.53%   |
| Sunplus HD WebCam                                   | 6         | 1.53%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 1.53%   |
| Realtek USB Camera                                  | 6         | 1.53%   |
| Lite-On Integrated Camera                           | 6         | 1.53%   |
| Syntek Lenovo EasyCamera                            | 5         | 1.27%   |
| Sunplus Asus Webcam                                 | 5         | 1.27%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 1.27%   |
| Chicony HP HD Webcam [Fixed]                        | 5         | 1.27%   |
| Chicony HP HD Webcam                                | 5         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 5         | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 5         | 1.27%   |
| Acer Lenovo EasyCamera                              | 5         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 1.02%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.02%   |
| Chicony Integrated HP HD Webcam                     | 4         | 1.02%   |
| Chicony HP HD Camera                                | 4         | 1.02%   |
| Bison Integrated Camera                             | 4         | 1.02%   |
| Bison EasyCamera                                    | 4         | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 0.76%   |
| Realtek Integrated_Webcam_HD                        | 3         | 0.76%   |
| Microdia Sonix Integrated Webcam                    | 3         | 0.76%   |
| Microdia Integrated Webcam                          | 3         | 0.76%   |
| Lite-On HP HD Camera                                | 3         | 0.76%   |
| IMC Networks VGA UVC WebCam                         | 3         | 0.76%   |
| IMC Networks Integrated Webcam                      | 3         | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 0.76%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 0.76%   |
| Chicony HP Truevision HD                            | 3         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 38        | 40.43%  |
| Shenzhen Goodix Technology         | 15        | 15.96%  |
| Upek                               | 12        | 12.77%  |
| Elan Microelectronics              | 11        | 11.7%   |
| Synaptics                          | 9         | 9.57%   |
| AuthenTec                          | 4         | 4.26%   |
| LighTuning Technology              | 3         | 3.19%   |
| STMicroelectronics                 | 1         | 1.06%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 16        | 17.02%  |
| Validity Sensors VFS491                                         | 11        | 11.7%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 11        | 11.7%   |
| Shenzhen Goodix  FingerPrint Device                             | 11        | 11.7%   |
| Elan ELAN:Fingerprint                                           | 9         | 9.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 5.32%   |
| Synaptics  WBDI                                                 | 3         | 3.19%   |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 3.19%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 2.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 2         | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 2.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 2         | 2.13%   |
| Elan WBF Fingerprint Sensor                                     | 2         | 2.13%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 2         | 2.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.06%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.06%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.06%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.06%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.06%   |
| Synaptics UWP WBDI                                              | 1         | 1.06%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 1.06%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 1.06%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.06%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.06%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.06%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.06%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 7         | 43.75%  |
| Alcor Micro           | 4         | 25%     |
| Upek                  | 2         | 12.5%   |
| O2 Micro              | 2         | 12.5%   |
| Gemalto (was Gemplus) | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 18.75%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 12.5%   |
| Broadcom 5880                                                                | 2         | 12.5%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 253       | 58.43%  |
| 1     | 135       | 31.18%  |
| 2     | 37        | 8.55%   |
| 3     | 5         | 1.15%   |
| 7     | 1         | 0.23%   |
| 5     | 1         | 0.23%   |
| 4     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 94        | 41.05%  |
| Graphics card            | 65        | 28.38%  |
| Bluetooth                | 16        | 6.99%   |
| Chipcard                 | 14        | 6.11%   |
| Net/wireless             | 13        | 5.68%   |
| Communication controller | 7         | 3.06%   |
| Camera                   | 7         | 3.06%   |
| Storage                  | 4         | 1.75%   |
| Sound                    | 2         | 0.87%   |
| Multimedia controller    | 2         | 0.87%   |
| Card reader              | 2         | 0.87%   |
| Wireless                 | 1         | 0.44%   |
| Network                  | 1         | 0.44%   |
| Net/ethernet             | 1         | 0.44%   |

