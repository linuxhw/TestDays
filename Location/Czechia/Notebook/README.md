Linux in Czechia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

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

Total: 2778

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Pro 7 14AKP10 83KG     | [edc589aee0](https://linux-hardware.org/?probe=edc589aee0) | Jan 03, 2026 |
| Dell          | Inspiron 7348               | [7270e26497](https://linux-hardware.org/?probe=7270e26497) | Jan 02, 2026 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ddc22ba8c0](https://linux-hardware.org/?probe=ddc22ba8c0) | Jan 01, 2026 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [524dd3caf6](https://linux-hardware.org/?probe=524dd3caf6) | Jan 01, 2026 |
| HP            | EliteBook 855 G8 Noteboo... | [d966eaa4db](https://linux-hardware.org/?probe=d966eaa4db) | Jan 01, 2026 |
| ASUSTek       | X556UB                      | [0686ecb473](https://linux-hardware.org/?probe=0686ecb473) | Jan 01, 2026 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | [60d7dc9a67](https://linux-hardware.org/?probe=60d7dc9a67) | Jan 01, 2026 |
| HP            | EliteBook 840 G3            | [4afb089451](https://linux-hardware.org/?probe=4afb089451) | Dec 29, 2025 |
| HP            | Compaq 615                  | [96c7d029d2](https://linux-hardware.org/?probe=96c7d029d2) | Dec 28, 2025 |
| HP            | ProBook 440 G8 Notebook ... | [6abbaf5eca](https://linux-hardware.org/?probe=6abbaf5eca) | Dec 22, 2025 |
| Lenovo        | E51-80 80QB                 | [3fce719dc1](https://linux-hardware.org/?probe=3fce719dc1) | Dec 22, 2025 |
| HP            | OmniBook 7 Laptop 14-fr0... | [a6e44a31e0](https://linux-hardware.org/?probe=a6e44a31e0) | Dec 22, 2025 |
| HP            | EliteBook 845 14 inch G1... | [14ffce0530](https://linux-hardware.org/?probe=14ffce0530) | Dec 21, 2025 |
| Dell          | Inspiron 7348               | [725ff9e4d2](https://linux-hardware.org/?probe=725ff9e4d2) | Dec 19, 2025 |
| Lenovo        | V15 G5 IRL 83GW             | [2a032d96b5](https://linux-hardware.org/?probe=2a032d96b5) | Dec 16, 2025 |
| HP            | Unknown                     | [234707220d](https://linux-hardware.org/?probe=234707220d) | Dec 13, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [15d617b937](https://linux-hardware.org/?probe=15d617b937) | Dec 13, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [84400c7a3a](https://linux-hardware.org/?probe=84400c7a3a) | Dec 13, 2025 |
| HP            | Laptop 15-bw0xx             | [337a308d37](https://linux-hardware.org/?probe=337a308d37) | Dec 12, 2025 |
| Acer          | TravelMate P216-41-TCO      | [3daa6db1d9](https://linux-hardware.org/?probe=3daa6db1d9) | Dec 11, 2025 |
| Acer          | Nitro ANV15-51              | [72a6ee08bd](https://linux-hardware.org/?probe=72a6ee08bd) | Dec 09, 2025 |
| Dell          | XPS 15 9570                 | [8fe7b11dcd](https://linux-hardware.org/?probe=8fe7b11dcd) | Dec 08, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9215095e75](https://linux-hardware.org/?probe=9215095e75) | Dec 08, 2025 |
| HP            | ZBook 15 G5                 | [b00db81fe5](https://linux-hardware.org/?probe=b00db81fe5) | Dec 07, 2025 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [d9a553916d](https://linux-hardware.org/?probe=d9a553916d) | Dec 06, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7dde4b6cec](https://linux-hardware.org/?probe=7dde4b6cec) | Dec 06, 2025 |
| Dell          | Inspiron 7348               | [04a39b1221](https://linux-hardware.org/?probe=04a39b1221) | Dec 05, 2025 |
| Lenovo        | V110-17IKB 80V2             | [354fd365db](https://linux-hardware.org/?probe=354fd365db) | Dec 04, 2025 |
| Dell          | Vostro 3491                 | [767986ee04](https://linux-hardware.org/?probe=767986ee04) | Dec 04, 2025 |
| Lenovo        | Legion 5 16IRX9 83DG        | [6abb72667d](https://linux-hardware.org/?probe=6abb72667d) | Dec 02, 2025 |
| Samsung       | 530U3C/530U4C               | [3d8df2bfed](https://linux-hardware.org/?probe=3d8df2bfed) | Dec 01, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [41463d6994](https://linux-hardware.org/?probe=41463d6994) | Dec 01, 2025 |
| Samsung       | R540/R580/R780/SA41/E452    | [ee211236f6](https://linux-hardware.org/?probe=ee211236f6) | Nov 30, 2025 |
| HP            | ProBook 4740s               | [3926cbde61](https://linux-hardware.org/?probe=3926cbde61) | Nov 29, 2025 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [2f2917e2dd](https://linux-hardware.org/?probe=2f2917e2dd) | Nov 29, 2025 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [5b63ec026f](https://linux-hardware.org/?probe=5b63ec026f) | Nov 29, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a2ebdc757d](https://linux-hardware.org/?probe=a2ebdc757d) | Nov 29, 2025 |
| HP            | 250 G3                      | [0e8e063408](https://linux-hardware.org/?probe=0e8e063408) | Nov 28, 2025 |
| ASUSTek       | X540LJ                      | [589ed32346](https://linux-hardware.org/?probe=589ed32346) | Nov 27, 2025 |
| ASUSTek       | X540LJ                      | [ae6c406062](https://linux-hardware.org/?probe=ae6c406062) | Nov 27, 2025 |
| HP            | EliteBook 855 G8 Noteboo... | [b2d488fa3f](https://linux-hardware.org/?probe=b2d488fa3f) | Nov 27, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [022bbd1727](https://linux-hardware.org/?probe=022bbd1727) | Nov 22, 2025 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [11330f82f3](https://linux-hardware.org/?probe=11330f82f3) | Nov 22, 2025 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7eb961be6](https://linux-hardware.org/?probe=d7eb961be6) | Nov 22, 2025 |
| HP            | ZBook 15                    | [1bfb421800](https://linux-hardware.org/?probe=1bfb421800) | Nov 21, 2025 |
| HP            | 255 G8 Notebook PC          | [4ac2b0c5e5](https://linux-hardware.org/?probe=4ac2b0c5e5) | Nov 19, 2025 |
| HP            | ProBook 4740s               | [1595f789c3](https://linux-hardware.org/?probe=1595f789c3) | Nov 19, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [373bdce267](https://linux-hardware.org/?probe=373bdce267) | Nov 16, 2025 |
| HP            | EliteBook X G1a 14 inch ... | [970f71a294](https://linux-hardware.org/?probe=970f71a294) | Nov 15, 2025 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0ed10d37a1](https://linux-hardware.org/?probe=0ed10d37a1) | Nov 15, 2025 |
| Acer          | Aspire A514-54              | [31cdc29540](https://linux-hardware.org/?probe=31cdc29540) | Nov 15, 2025 |
| ASUSTek       | Zenbook UX425QA_UM425QA     | [405aa6abb6](https://linux-hardware.org/?probe=405aa6abb6) | Nov 14, 2025 |
| Dell          | Inspiron 5379               | [6e5abeb421](https://linux-hardware.org/?probe=6e5abeb421) | Nov 12, 2025 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [dad9db710d](https://linux-hardware.org/?probe=dad9db710d) | Nov 11, 2025 |
| Dell          | Precision 7760              | [95bbbaca85](https://linux-hardware.org/?probe=95bbbaca85) | Nov 11, 2025 |
| Dell          | Inspiron 7537               | [4b203436fa](https://linux-hardware.org/?probe=4b203436fa) | Nov 10, 2025 |
| ASUSTek       | X550MD                      | [195db352d6](https://linux-hardware.org/?probe=195db352d6) | Nov 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d354b8ffbd](https://linux-hardware.org/?probe=d354b8ffbd) | Nov 10, 2025 |
| UMAX          | VisionBook 15WJ Plus        | [0c8a25aed7](https://linux-hardware.org/?probe=0c8a25aed7) | Nov 10, 2025 |
| Samsung       | 950XDB/951XDB/950XDY        | [bde7a4b989](https://linux-hardware.org/?probe=bde7a4b989) | Nov 09, 2025 |
| Lenovo        | V15 G5 IRL 83GW             | [3de3bb8def](https://linux-hardware.org/?probe=3de3bb8def) | Nov 07, 2025 |
| Lenovo        | V15 G5 IRL 83GW             | [63c32cd98f](https://linux-hardware.org/?probe=63c32cd98f) | Nov 07, 2025 |
| Dell          | Pro 14 Plus PB14250         | [4e1e077ab8](https://linux-hardware.org/?probe=4e1e077ab8) | Nov 07, 2025 |
| HP            | 250 G4 Notebook PC          | [50059fa851](https://linux-hardware.org/?probe=50059fa851) | Nov 07, 2025 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [99e9ec1753](https://linux-hardware.org/?probe=99e9ec1753) | Nov 05, 2025 |
| HP            | Compaq 6730b (GB988ET#AB... | [4fb1bf2562](https://linux-hardware.org/?probe=4fb1bf2562) | Nov 03, 2025 |
| Dell          | Latitude 7490               | [090a50d2b3](https://linux-hardware.org/?probe=090a50d2b3) | Nov 01, 2025 |
| HP            | Laptop 15s-eq2xxx           | [4f95cb040a](https://linux-hardware.org/?probe=4f95cb040a) | Nov 01, 2025 |
| Valve         | Galileo                     | [45f4f43de8](https://linux-hardware.org/?probe=45f4f43de8) | Nov 01, 2025 |
| Sony          | VPCEH1M1E                   | [83b707c913](https://linux-hardware.org/?probe=83b707c913) | Oct 31, 2025 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [62da57245d](https://linux-hardware.org/?probe=62da57245d) | Oct 31, 2025 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [dcfe661bc7](https://linux-hardware.org/?probe=dcfe661bc7) | Oct 30, 2025 |
| Acer          | Aspire 4820T                | [7d6ec94850](https://linux-hardware.org/?probe=7d6ec94850) | Oct 28, 2025 |
| Lenovo        | ThinkPad T480 20L6S29D0H    | [e580e83796](https://linux-hardware.org/?probe=e580e83796) | Oct 27, 2025 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [70b0413204](https://linux-hardware.org/?probe=70b0413204) | Oct 27, 2025 |
| ASUSTek       | ROG Strix G16 G614PR_G61... | [37ca4c334d](https://linux-hardware.org/?probe=37ca4c334d) | Oct 24, 2025 |
| Dell          | Latitude E5270              | [9192d3641e](https://linux-hardware.org/?probe=9192d3641e) | Oct 23, 2025 |
| ASUSTek       | N53SV                       | [5e13ee1135](https://linux-hardware.org/?probe=5e13ee1135) | Oct 22, 2025 |
| HP            | EliteBook 855 G8 Noteboo... | [db50da4444](https://linux-hardware.org/?probe=db50da4444) | Oct 21, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MDS... | [1b3b06c36d](https://linux-hardware.org/?probe=1b3b06c36d) | Oct 19, 2025 |
| Acer          | Nitro AN515-55              | [f9d1fda8ed](https://linux-hardware.org/?probe=f9d1fda8ed) | Oct 18, 2025 |
| Lenovo        | ThinkPad T440p 20AWS11D1... | [6e480dedc8](https://linux-hardware.org/?probe=6e480dedc8) | Oct 18, 2025 |
| Lenovo        | IdeaPad Z500 20202          | [66a5eb229c](https://linux-hardware.org/?probe=66a5eb229c) | Oct 16, 2025 |
| Lenovo        | Y520-15IKBN 80WK            | [16addd49b2](https://linux-hardware.org/?probe=16addd49b2) | Oct 14, 2025 |
| Lenovo        | V15 G2 ITL 82KB             | [46c8431557](https://linux-hardware.org/?probe=46c8431557) | Oct 13, 2025 |
| Lenovo        | V15 G2 ITL 82KB             | [c9627056fa](https://linux-hardware.org/?probe=c9627056fa) | Oct 13, 2025 |
| Acer          | JM11-MS                     | [3637495bde](https://linux-hardware.org/?probe=3637495bde) | Oct 12, 2025 |
| Acer          | Aspire 5738                 | [b218fa91ee](https://linux-hardware.org/?probe=b218fa91ee) | Oct 11, 2025 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [6caf7b5045](https://linux-hardware.org/?probe=6caf7b5045) | Oct 11, 2025 |
| Lenovo        | ThinkPad T16 Gen 1 21CJS... | [40cda73174](https://linux-hardware.org/?probe=40cda73174) | Oct 11, 2025 |
| Lenovo        | ThinkPad T16 Gen 1 21CJS... | [a57cfa0fa7](https://linux-hardware.org/?probe=a57cfa0fa7) | Oct 11, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [fb82da8ece](https://linux-hardware.org/?probe=fb82da8ece) | Oct 10, 2025 |
| Lenovo        | G700 20251                  | [b3c7f985d7](https://linux-hardware.org/?probe=b3c7f985d7) | Oct 10, 2025 |
| Lenovo        | G700 20251                  | [8eca1ddf21](https://linux-hardware.org/?probe=8eca1ddf21) | Oct 10, 2025 |
| HP            | EliteBook 745 G4            | [e73a3bd14e](https://linux-hardware.org/?probe=e73a3bd14e) | Oct 09, 2025 |
| Lenovo        | IdeaPad Slim 5 16AKP10 8... | [48256c6580](https://linux-hardware.org/?probe=48256c6580) | Oct 08, 2025 |
| Acer          | Aspire 5750G                | [ce14a26867](https://linux-hardware.org/?probe=ce14a26867) | Oct 05, 2025 |
| Dell          | Latitude E6540              | [0fef688c80](https://linux-hardware.org/?probe=0fef688c80) | Oct 05, 2025 |
| Fujitsu       | LIFEBOOK U7410              | [f4a77dcb45](https://linux-hardware.org/?probe=f4a77dcb45) | Oct 05, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [00c9e3a269](https://linux-hardware.org/?probe=00c9e3a269) | Oct 04, 2025 |
| Acer          | Aspire E1-532               | [bc3740361e](https://linux-hardware.org/?probe=bc3740361e) | Oct 04, 2025 |
| Lenovo        | ThinkPad P14s Gen 6 AMD ... | [58f60824e1](https://linux-hardware.org/?probe=58f60824e1) | Oct 03, 2025 |
| Lenovo        | Yoga Pro 7 14ASP9 83HN      | [b4eb6ca8c2](https://linux-hardware.org/?probe=b4eb6ca8c2) | Oct 03, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | [27f3b5ebfd](https://linux-hardware.org/?probe=27f3b5ebfd) | Oct 02, 2025 |
| Acer          | Nitro ANV15-51              | [30d3c55524](https://linux-hardware.org/?probe=30d3c55524) | Sep 29, 2025 |
| Acer          | Nitro ANV15-51              | [c4f2cb165f](https://linux-hardware.org/?probe=c4f2cb165f) | Sep 28, 2025 |
| Fujitsu       | LIFEBOOK U7410              | [cd2c51f33d](https://linux-hardware.org/?probe=cd2c51f33d) | Sep 27, 2025 |
| Dell          | Latitude 5440               | [d78704503b](https://linux-hardware.org/?probe=d78704503b) | Sep 27, 2025 |
| Dell          | Latitude 5440               | [781bd9afa0](https://linux-hardware.org/?probe=781bd9afa0) | Sep 27, 2025 |
| Dell          | Vostro 5568                 | [b8a13c4feb](https://linux-hardware.org/?probe=b8a13c4feb) | Sep 26, 2025 |
| Acer          | Aspire 5750G                | [ebd8dff71c](https://linux-hardware.org/?probe=ebd8dff71c) | Sep 25, 2025 |
| Acer          | Aspire 5750G                | [f0a39e2811](https://linux-hardware.org/?probe=f0a39e2811) | Sep 25, 2025 |
| HP            | ProBook 6545b (NF047AV)     | [eb8b8e07ec](https://linux-hardware.org/?probe=eb8b8e07ec) | Sep 23, 2025 |
| DATABOX       | BusinessTab A10             | [b9e07e1b8a](https://linux-hardware.org/?probe=b9e07e1b8a) | Sep 22, 2025 |
| Dell          | Inspiron 16 5625            | [160d9abf5d](https://linux-hardware.org/?probe=160d9abf5d) | Sep 22, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [62f5fd7006](https://linux-hardware.org/?probe=62f5fd7006) | Sep 21, 2025 |
| Dell          | Latitude E6430              | [119326d0ee](https://linux-hardware.org/?probe=119326d0ee) | Sep 19, 2025 |
| Dell          | Pro 14 Plus PB14250         | [0c9a5a7368](https://linux-hardware.org/?probe=0c9a5a7368) | Sep 17, 2025 |
| Acer          | Aspire A114-33              | [41f753f291](https://linux-hardware.org/?probe=41f753f291) | Sep 15, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9f9bf80f26](https://linux-hardware.org/?probe=9f9bf80f26) | Sep 13, 2025 |
| ASUSTek       | X411UA                      | [8b2065caa0](https://linux-hardware.org/?probe=8b2065caa0) | Sep 13, 2025 |
| Dell          | Pro 14 Plus PB14250         | [601e9f576e](https://linux-hardware.org/?probe=601e9f576e) | Sep 11, 2025 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [ffabef7150](https://linux-hardware.org/?probe=ffabef7150) | Sep 10, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [3d1e62a3b6](https://linux-hardware.org/?probe=3d1e62a3b6) | Sep 10, 2025 |
| Lenovo        | ThinkPad T16 Gen 1 21CJS... | [f1a9e7c054](https://linux-hardware.org/?probe=f1a9e7c054) | Sep 07, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [6a61411eec](https://linux-hardware.org/?probe=6a61411eec) | Sep 07, 2025 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [3c0ce1d652](https://linux-hardware.org/?probe=3c0ce1d652) | Sep 06, 2025 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [d98131c831](https://linux-hardware.org/?probe=d98131c831) | Sep 05, 2025 |
| HP            | Pavilion g6                 | [cfb7d78c9d](https://linux-hardware.org/?probe=cfb7d78c9d) | Sep 05, 2025 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [479a18d0ee](https://linux-hardware.org/?probe=479a18d0ee) | Sep 05, 2025 |
| Dell          | XPS 15 7590                 | [c370fe3b6f](https://linux-hardware.org/?probe=c370fe3b6f) | Sep 04, 2025 |
| HP            | EliteBook 840 G3            | [f1ce9242c5](https://linux-hardware.org/?probe=f1ce9242c5) | Sep 04, 2025 |
| Dell          | Pro 16 Plus PB16250         | [d5d5a5e7d4](https://linux-hardware.org/?probe=d5d5a5e7d4) | Sep 03, 2025 |
| Lenovo        | ThinkPad T500 224396G       | [48c5aceaac](https://linux-hardware.org/?probe=48c5aceaac) | Sep 03, 2025 |
| Lenovo        | ThinkPad X250 20CLS75800    | [0376d4ca5c](https://linux-hardware.org/?probe=0376d4ca5c) | Sep 03, 2025 |
| HP            | EliteBook 840 G3            | [2b9e8d287e](https://linux-hardware.org/?probe=2b9e8d287e) | Sep 03, 2025 |
| HP            | ZBook 15 G2                 | [63e2212f2b](https://linux-hardware.org/?probe=63e2212f2b) | Sep 01, 2025 |
| HP            | 250 G6 Notebook PC          | [46415137f3](https://linux-hardware.org/?probe=46415137f3) | Aug 31, 2025 |
| HP            | Compaq 615                  | [1c2c12aff7](https://linux-hardware.org/?probe=1c2c12aff7) | Aug 31, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [4d016b7b5a](https://linux-hardware.org/?probe=4d016b7b5a) | Aug 30, 2025 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [296d2fffb5](https://linux-hardware.org/?probe=296d2fffb5) | Aug 29, 2025 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [12ff6b11bf](https://linux-hardware.org/?probe=12ff6b11bf) | Aug 29, 2025 |
| Lenovo        | IdeaPad Pro 5 14AKP10 83... | [38386a529a](https://linux-hardware.org/?probe=38386a529a) | Aug 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [ba7328c86d](https://linux-hardware.org/?probe=ba7328c86d) | Aug 28, 2025 |
| Acer          | Aspire E1-532               | [1939ed9393](https://linux-hardware.org/?probe=1939ed9393) | Aug 26, 2025 |
| Lenovo        | B50-70 20384                | [1abea8916c](https://linux-hardware.org/?probe=1abea8916c) | Aug 26, 2025 |
| Prestigio     | PSB141C03                   | [3c827fcce3](https://linux-hardware.org/?probe=3c827fcce3) | Aug 26, 2025 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [b31cbc77c1](https://linux-hardware.org/?probe=b31cbc77c1) | Aug 26, 2025 |
| ASUSTek       | N61Vg                       | [f080c92b4f](https://linux-hardware.org/?probe=f080c92b4f) | Aug 25, 2025 |
| Lenovo        | ThinkPad T480 20L6SAS100    | [13360a06ce](https://linux-hardware.org/?probe=13360a06ce) | Aug 25, 2025 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [0442d00027](https://linux-hardware.org/?probe=0442d00027) | Aug 24, 2025 |
| Acer          | Swift SF14-71T              | [065806f62e](https://linux-hardware.org/?probe=065806f62e) | Aug 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d9344783c2](https://linux-hardware.org/?probe=d9344783c2) | Aug 20, 2025 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [6fbea8da7b](https://linux-hardware.org/?probe=6fbea8da7b) | Aug 20, 2025 |
| Acer          | Aspire V3-772               | [62e4f6f38b](https://linux-hardware.org/?probe=62e4f6f38b) | Aug 19, 2025 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [8e3e609787](https://linux-hardware.org/?probe=8e3e609787) | Aug 16, 2025 |
| HP            | 15                          | [bf8e6c7da6](https://linux-hardware.org/?probe=bf8e6c7da6) | Aug 15, 2025 |
| Fujitsu       | CELSIUS H770                | [435509fd03](https://linux-hardware.org/?probe=435509fd03) | Aug 15, 2025 |
| Dell          | System Inspiron 7720        | [4abdca85a1](https://linux-hardware.org/?probe=4abdca85a1) | Aug 11, 2025 |
| Dell          | System Inspiron 7720        | [9c0e309abf](https://linux-hardware.org/?probe=9c0e309abf) | Aug 11, 2025 |
| Fujitsu       | CELSIUS H770                | [eb9bb4723c](https://linux-hardware.org/?probe=eb9bb4723c) | Aug 10, 2025 |
| Acer          | Aspire E1-532               | [9673e381f3](https://linux-hardware.org/?probe=9673e381f3) | Aug 09, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | [e37377f73e](https://linux-hardware.org/?probe=e37377f73e) | Aug 07, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [f18a0b09c2](https://linux-hardware.org/?probe=f18a0b09c2) | Aug 07, 2025 |
| Lenovo        | G575 20081                  | [6791e4f4f7](https://linux-hardware.org/?probe=6791e4f4f7) | Aug 06, 2025 |
| Lenovo        | ThinkPad L14 Gen 5 21L6S... | [726969a490](https://linux-hardware.org/?probe=726969a490) | Aug 05, 2025 |
| HP            | Notebook                    | [9da144efc8](https://linux-hardware.org/?probe=9da144efc8) | Aug 03, 2025 |
| HP            | EliteBook 845 14 inch G1... | [5665c16a70](https://linux-hardware.org/?probe=5665c16a70) | Aug 03, 2025 |
| Dell          | Precision 3530              | [db9e4cdbf3](https://linux-hardware.org/?probe=db9e4cdbf3) | Aug 03, 2025 |
| Dell          | Precision 3530              | [6d90551997](https://linux-hardware.org/?probe=6d90551997) | Aug 03, 2025 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [612a693b87](https://linux-hardware.org/?probe=612a693b87) | Aug 02, 2025 |
| Lenovo        | B590 20206                  | [5e5cdb37af](https://linux-hardware.org/?probe=5e5cdb37af) | Jul 31, 2025 |
| Acer          | Nitro AN515-45              | [950a185fe1](https://linux-hardware.org/?probe=950a185fe1) | Jul 31, 2025 |
| Acer          | Nitro AN515-52              | [8e5c36a028](https://linux-hardware.org/?probe=8e5c36a028) | Jul 30, 2025 |
| Dell          | Precision 5530              | [2b3c67d1c1](https://linux-hardware.org/?probe=2b3c67d1c1) | Jul 28, 2025 |
| Acer          | Aspire 5820TG               | [e2e68f6416](https://linux-hardware.org/?probe=e2e68f6416) | Jul 19, 2025 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [7eca490b49](https://linux-hardware.org/?probe=7eca490b49) | Jul 17, 2025 |
| Alienware     | m15 R7                      | [3770bf8c04](https://linux-hardware.org/?probe=3770bf8c04) | Jul 17, 2025 |
| HP            | ProBook 445 G7              | [0a9cd22479](https://linux-hardware.org/?probe=0a9cd22479) | Jul 17, 2025 |
| Toshiba       | Satellite C650              | [d12a8a7d6d](https://linux-hardware.org/?probe=d12a8a7d6d) | Jul 14, 2025 |
| Lenovo        | B50-70 20384                | [0f4359783b](https://linux-hardware.org/?probe=0f4359783b) | Jul 09, 2025 |
| Dell          | XPS 15 9570                 | [1a0d9f5577](https://linux-hardware.org/?probe=1a0d9f5577) | Jul 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [a65cbec217](https://linux-hardware.org/?probe=a65cbec217) | Jul 07, 2025 |
| HP            | EliteBook 840 14 inch G9... | [0ada896f48](https://linux-hardware.org/?probe=0ada896f48) | Jul 07, 2025 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [fddf7462e2](https://linux-hardware.org/?probe=fddf7462e2) | Jul 06, 2025 |
| Acer          | Extensa 5630                | [bad39c8b5a](https://linux-hardware.org/?probe=bad39c8b5a) | Jul 06, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [db007d6732](https://linux-hardware.org/?probe=db007d6732) | Jul 06, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [67a2a1fa10](https://linux-hardware.org/?probe=67a2a1fa10) | Jul 06, 2025 |
| Notebook      | X170SM                      | [1132e96681](https://linux-hardware.org/?probe=1132e96681) | Jul 05, 2025 |
| Dell          | XPS 15 7590                 | [f50b86c248](https://linux-hardware.org/?probe=f50b86c248) | Jul 04, 2025 |
| Lenovo        | ThinkPad X240 20AL007YFR    | [7bcdaee212](https://linux-hardware.org/?probe=7bcdaee212) | Jul 04, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [df3fe6cde6](https://linux-hardware.org/?probe=df3fe6cde6) | Jul 04, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e63e60488d](https://linux-hardware.org/?probe=e63e60488d) | Jul 04, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M2... | [4e306d5d35](https://linux-hardware.org/?probe=4e306d5d35) | Jul 04, 2025 |
| Acer          | Nitro AN515-45              | [941cff9714](https://linux-hardware.org/?probe=941cff9714) | Jul 04, 2025 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [509de1c517](https://linux-hardware.org/?probe=509de1c517) | Jul 03, 2025 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [84f09ecc39](https://linux-hardware.org/?probe=84f09ecc39) | Jul 03, 2025 |
| ASUSTek       | X751MJ                      | [1b29ffc218](https://linux-hardware.org/?probe=1b29ffc218) | Jul 02, 2025 |
| ASUSTek       | X556UB                      | [d850b4b740](https://linux-hardware.org/?probe=d850b4b740) | Jul 01, 2025 |
| HP            | ProBook 650 G4              | [47d9aef20e](https://linux-hardware.org/?probe=47d9aef20e) | Jun 30, 2025 |
| Acer          | Aspire 3100                 | [30818de15d](https://linux-hardware.org/?probe=30818de15d) | Jun 28, 2025 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [611f01c753](https://linux-hardware.org/?probe=611f01c753) | Jun 26, 2025 |
| Unknown       | Unknown                     | [e47aeb6a9a](https://linux-hardware.org/?probe=e47aeb6a9a) | Jun 26, 2025 |
| Toshiba       | Satellite A200              | [cf73c20b01](https://linux-hardware.org/?probe=cf73c20b01) | Jun 23, 2025 |
| Intel         | JV10_CS                     | [fa91e09212](https://linux-hardware.org/?probe=fa91e09212) | Jun 22, 2025 |
| Acer          | Nitro AN515-45              | [607f186ade](https://linux-hardware.org/?probe=607f186ade) | Jun 22, 2025 |
| Lenovo        | G710 20252                  | [3b40c0e702](https://linux-hardware.org/?probe=3b40c0e702) | Jun 20, 2025 |
| Dell          | Latitude E5430 non-vPro     | [23bf78848c](https://linux-hardware.org/?probe=23bf78848c) | Jun 16, 2025 |
| Dell          | Latitude 3340               | [c37406c476](https://linux-hardware.org/?probe=c37406c476) | Jun 16, 2025 |
| Dell          | Latitude 3340               | [88e3a2847d](https://linux-hardware.org/?probe=88e3a2847d) | Jun 16, 2025 |
| Dell          | XPS 13 9305                 | [f545b6c3fc](https://linux-hardware.org/?probe=f545b6c3fc) | Jun 13, 2025 |
| Lenovo        | Yoga Slim 7 14AKP10 83JY    | [6cc189bf8e](https://linux-hardware.org/?probe=6cc189bf8e) | Jun 12, 2025 |
| Dell          | Latitude 5411               | [7a6f19513e](https://linux-hardware.org/?probe=7a6f19513e) | Jun 12, 2025 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a59860c4a8](https://linux-hardware.org/?probe=a59860c4a8) | Jun 11, 2025 |
| UMAX          | N14R                        | [2772dc1e0d](https://linux-hardware.org/?probe=2772dc1e0d) | Jun 11, 2025 |
| Dell          | Latitude 5430               | [9b2bffe7f3](https://linux-hardware.org/?probe=9b2bffe7f3) | Jun 09, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [147154b2c6](https://linux-hardware.org/?probe=147154b2c6) | Jun 08, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a9ae97ef6](https://linux-hardware.org/?probe=9a9ae97ef6) | Jun 07, 2025 |
| Dell          | Latitude 7300               | [fc825913b0](https://linux-hardware.org/?probe=fc825913b0) | Jun 05, 2025 |
| HP            | ZBook Firefly 14 inch G1... | [4b6ff6df30](https://linux-hardware.org/?probe=4b6ff6df30) | Jun 02, 2025 |
| HP            | EliteBook 855 G8 Noteboo... | [8bdcc494f3](https://linux-hardware.org/?probe=8bdcc494f3) | Jun 02, 2025 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [2a2bb8f114](https://linux-hardware.org/?probe=2a2bb8f114) | Jun 01, 2025 |
| HP            | Pavilion Power Laptop 15... | [64df986a60](https://linux-hardware.org/?probe=64df986a60) | Jun 01, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [179b1beb26](https://linux-hardware.org/?probe=179b1beb26) | Jun 01, 2025 |
| HP            | Pavilion Power Laptop 15... | [c9a3a11d18](https://linux-hardware.org/?probe=c9a3a11d18) | Jun 01, 2025 |
| Lenovo        | ThinkPad T490 20N2005SMX    | [f0a067f7c1](https://linux-hardware.org/?probe=f0a067f7c1) | May 31, 2025 |
| HP            | EliteBook 855 G8 Noteboo... | [bc4dd911cd](https://linux-hardware.org/?probe=bc4dd911cd) | May 28, 2025 |
| Lenovo        | Yoga Slim 6 14IRH8 83E0     | [3f8d4fdf12](https://linux-hardware.org/?probe=3f8d4fdf12) | May 25, 2025 |
| Valve         | Jupiter                     | [c99882037c](https://linux-hardware.org/?probe=c99882037c) | May 25, 2025 |
| Dell          | XPS 15 7590                 | [baebd3e0d2](https://linux-hardware.org/?probe=baebd3e0d2) | May 24, 2025 |
| Dell          | XPS 15 7590                 | [83bf6a8863](https://linux-hardware.org/?probe=83bf6a8863) | May 24, 2025 |
| HP            | Unknown                     | [dd7a21dc6a](https://linux-hardware.org/?probe=dd7a21dc6a) | May 24, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [1e84caa6bd](https://linux-hardware.org/?probe=1e84caa6bd) | May 24, 2025 |
| Fujitsu       | LIFEBOOK E751               | [63862a05a4](https://linux-hardware.org/?probe=63862a05a4) | May 23, 2025 |
| ASUSTek       | X551CAP                     | [ac321e5877](https://linux-hardware.org/?probe=ac321e5877) | May 20, 2025 |
| ASUSTek       | X551CAP                     | [23471927af](https://linux-hardware.org/?probe=23471927af) | May 20, 2025 |
| Dell          | Latitude E5550              | [efb6ffe9b2](https://linux-hardware.org/?probe=efb6ffe9b2) | May 17, 2025 |
| Apple         | MacBook5,1                  | [9db620bae0](https://linux-hardware.org/?probe=9db620bae0) | May 14, 2025 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [9c4a36aa2e](https://linux-hardware.org/?probe=9c4a36aa2e) | May 13, 2025 |
| Lenovo        | ThinkPad P1 Gen 4 20Y4S3... | [12bc69c31e](https://linux-hardware.org/?probe=12bc69c31e) | May 13, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [df0cfdaf43](https://linux-hardware.org/?probe=df0cfdaf43) | May 13, 2025 |
| UMAX          | VisionBook 12Wr             | [1a2429a27d](https://linux-hardware.org/?probe=1a2429a27d) | May 12, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | [f8885d856c](https://linux-hardware.org/?probe=f8885d856c) | May 09, 2025 |
| TUXEDO        | Aura 14 Gen3                | [6d0d969030](https://linux-hardware.org/?probe=6d0d969030) | May 07, 2025 |
| Acer          | NC-E1-772G-54204G1TMNSK     | [fba9a12ac8](https://linux-hardware.org/?probe=fba9a12ac8) | May 07, 2025 |
| HP            | EliteBook 855 G8 Noteboo... | [82b8d3a4ae](https://linux-hardware.org/?probe=82b8d3a4ae) | May 06, 2025 |
| Dell          | Vostro 3590                 | [bdb8517258](https://linux-hardware.org/?probe=bdb8517258) | May 04, 2025 |
| Fujitsu       | LIFEBOOK E752               | [103baeded8](https://linux-hardware.org/?probe=103baeded8) | May 04, 2025 |
| Acer          | Nitro AN515-51              | [d927f29277](https://linux-hardware.org/?probe=d927f29277) | May 03, 2025 |
| Acer          | Nitro AN515-51              | [79b467cf9a](https://linux-hardware.org/?probe=79b467cf9a) | May 03, 2025 |
| MSI           | Katana 15 B13VFK            | [d002135e86](https://linux-hardware.org/?probe=d002135e86) | May 03, 2025 |
| Lenovo        | ThinkPad X220 4291BB1       | [792542e8da](https://linux-hardware.org/?probe=792542e8da) | May 03, 2025 |
| UMAX          | N14R                        | [e6cd64315f](https://linux-hardware.org/?probe=e6cd64315f) | May 03, 2025 |
| UMAX          | N14R                        | [ba6b4544ce](https://linux-hardware.org/?probe=ba6b4544ce) | May 03, 2025 |
| Acer          | Nitro AN515-45              | [a42f4d595e](https://linux-hardware.org/?probe=a42f4d595e) | May 02, 2025 |
| Dell          | XPS 15 9570                 | [4e45d939ed](https://linux-hardware.org/?probe=4e45d939ed) | Apr 29, 2025 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [9f3aabe755](https://linux-hardware.org/?probe=9f3aabe755) | Apr 28, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e4549abb85](https://linux-hardware.org/?probe=e4549abb85) | Apr 28, 2025 |
| Dell          | Latitude 7490               | [abe13c1449](https://linux-hardware.org/?probe=abe13c1449) | Apr 27, 2025 |
| Acer          | Aspire E1-531               | [aff2312673](https://linux-hardware.org/?probe=aff2312673) | Apr 27, 2025 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [04bc01fc05](https://linux-hardware.org/?probe=04bc01fc05) | Apr 27, 2025 |
| ASUSTek       | K75VJ                       | [b4d2c35632](https://linux-hardware.org/?probe=b4d2c35632) | Apr 27, 2025 |
| Dell          | Latitude 7490               | [60ce789eb0](https://linux-hardware.org/?probe=60ce789eb0) | Apr 25, 2025 |
| Dell          | Latitude 7490               | [7989edf21c](https://linux-hardware.org/?probe=7989edf21c) | Apr 25, 2025 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [e6c8926bc3](https://linux-hardware.org/?probe=e6c8926bc3) | Apr 23, 2025 |
| Fujitsu       | LIFEBOOK U7311              | [c67ef08569](https://linux-hardware.org/?probe=c67ef08569) | Apr 23, 2025 |
| HP            | EliteBook 640 14 inch G1... | [9524aff992](https://linux-hardware.org/?probe=9524aff992) | Apr 22, 2025 |
| Lenovo        | ThinkPad Edge E540 20C60... | [325a87db4b](https://linux-hardware.org/?probe=325a87db4b) | Apr 21, 2025 |
| Lenovo        | ThinkPad P52 20MAS72W00     | [dffb48cddc](https://linux-hardware.org/?probe=dffb48cddc) | Apr 18, 2025 |
| Lenovo        | ThinkPad Edge E540 20C60... | [22bd8fd9f8](https://linux-hardware.org/?probe=22bd8fd9f8) | Apr 17, 2025 |
| Unknown       | X133                        | [0ba9aa593d](https://linux-hardware.org/?probe=0ba9aa593d) | Apr 16, 2025 |
| Dell          | Vostro 3578                 | [8676cc815b](https://linux-hardware.org/?probe=8676cc815b) | Apr 10, 2025 |
| Unknown       | X133                        | [be33ecd36f](https://linux-hardware.org/?probe=be33ecd36f) | Apr 10, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [8f52c788f5](https://linux-hardware.org/?probe=8f52c788f5) | Apr 08, 2025 |
| Valve         | Jupiter                     | [53ed05af57](https://linux-hardware.org/?probe=53ed05af57) | Apr 06, 2025 |
| Dell          | Inspiron 1545               | [2cb0511c6e](https://linux-hardware.org/?probe=2cb0511c6e) | Apr 05, 2025 |
| win elemen... | MoreFine S500+              | [5f382f9235](https://linux-hardware.org/?probe=5f382f9235) | Apr 03, 2025 |
| win elemen... | MoreFine S500+              | [fa53166013](https://linux-hardware.org/?probe=fa53166013) | Apr 03, 2025 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [051f89d8ed](https://linux-hardware.org/?probe=051f89d8ed) | Apr 02, 2025 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [f3b9521850](https://linux-hardware.org/?probe=f3b9521850) | Mar 31, 2025 |
| Fujitsu       | LIFEBOOK U728               | [bf5f9d0bd7](https://linux-hardware.org/?probe=bf5f9d0bd7) | Mar 29, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [40c823cdc9](https://linux-hardware.org/?probe=40c823cdc9) | Mar 28, 2025 |
| Apple         | MacBookAir7,2               | [16e26753cb](https://linux-hardware.org/?probe=16e26753cb) | Mar 26, 2025 |
| UMAX          | VisionBook N14G Plus        | [8807fc5d1c](https://linux-hardware.org/?probe=8807fc5d1c) | Mar 23, 2025 |
| HP            | ProBook 465 16 inch G11 ... | [ae4179bfde](https://linux-hardware.org/?probe=ae4179bfde) | Mar 22, 2025 |
| Lenovo        | ThinkPad X260 20F5S02U00    | [6a118b80c1](https://linux-hardware.org/?probe=6a118b80c1) | Mar 21, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [5235f42d23](https://linux-hardware.org/?probe=5235f42d23) | Mar 21, 2025 |
| Lenovo        | G710 20252                  | [4487978361](https://linux-hardware.org/?probe=4487978361) | Mar 20, 2025 |
| Acer          | Swift SF14-71T              | [9853afba68](https://linux-hardware.org/?probe=9853afba68) | Mar 20, 2025 |
| ASUSTek       | N73SV                       | [444f77ffd7](https://linux-hardware.org/?probe=444f77ffd7) | Mar 16, 2025 |
| Lenovo        | ThinkPad P53 20QQS0JD01     | [e0acd2ee1e](https://linux-hardware.org/?probe=e0acd2ee1e) | Mar 16, 2025 |
| Lenovo        | ThinkPad T430 2349N3G       | [0367e3341f](https://linux-hardware.org/?probe=0367e3341f) | Mar 15, 2025 |
| Lenovo        | ThinkPad T430 2349N3G       | [9c83c20e70](https://linux-hardware.org/?probe=9c83c20e70) | Mar 15, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | [5a1b0927d4](https://linux-hardware.org/?probe=5a1b0927d4) | Mar 14, 2025 |
| HP            | 255 G8 Notebook PC          | [4909d1d2c6](https://linux-hardware.org/?probe=4909d1d2c6) | Mar 14, 2025 |
| Dell          | XPS 13 9310                 | [db811ce87d](https://linux-hardware.org/?probe=db811ce87d) | Mar 14, 2025 |
| Dell          | XPS 13 9310                 | [b6d7f1b22e](https://linux-hardware.org/?probe=b6d7f1b22e) | Mar 14, 2025 |
| Dell          | Latitude E5570              | [a54b018322](https://linux-hardware.org/?probe=a54b018322) | Mar 12, 2025 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [981392397f](https://linux-hardware.org/?probe=981392397f) | Mar 11, 2025 |
| Google        | Ultima                      | [a8d5b2f931](https://linux-hardware.org/?probe=a8d5b2f931) | Mar 10, 2025 |
| Lenovo        | ThinkPad P53 20QQS0JD01     | [2610793887](https://linux-hardware.org/?probe=2610793887) | Mar 08, 2025 |
| ASUSTek       | UX21E                       | [35cbd54797](https://linux-hardware.org/?probe=35cbd54797) | Mar 08, 2025 |
| ASUSTek       | X705NC                      | [1fe5e3f14d](https://linux-hardware.org/?probe=1fe5e3f14d) | Mar 08, 2025 |
| ASUSTek       | X705NC                      | [c6d2b94043](https://linux-hardware.org/?probe=c6d2b94043) | Mar 08, 2025 |
| Lenovo        | ThinkPad T480s 20L8A09BM... | [722364eee4](https://linux-hardware.org/?probe=722364eee4) | Mar 07, 2025 |
| HP            | EliteBook 840 G8 Noteboo... | [fb564a410b](https://linux-hardware.org/?probe=fb564a410b) | Mar 06, 2025 |
| ASUSTek       | 901                         | [c7fb59cac2](https://linux-hardware.org/?probe=c7fb59cac2) | Mar 06, 2025 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [a30ef94e00](https://linux-hardware.org/?probe=a30ef94e00) | Mar 05, 2025 |
| MSI           | Cyborg 15 A12VE             | [ea0a7f1f33](https://linux-hardware.org/?probe=ea0a7f1f33) | Mar 05, 2025 |
| ASUSTek       | 901                         | [fdafcbf1ec](https://linux-hardware.org/?probe=fdafcbf1ec) | Mar 05, 2025 |
| Dell          | Latitude E5570              | [ce345952d3](https://linux-hardware.org/?probe=ce345952d3) | Mar 04, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [25f651a0de](https://linux-hardware.org/?probe=25f651a0de) | Mar 04, 2025 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [a66b6dccb4](https://linux-hardware.org/?probe=a66b6dccb4) | Mar 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MC0... | [9c960d25c3](https://linux-hardware.org/?probe=9c960d25c3) | Mar 03, 2025 |
| Dell          | Inspiron 5570               | [642911970c](https://linux-hardware.org/?probe=642911970c) | Feb 28, 2025 |
| HP            | 250 G7 Notebook PC          | [38936d84ee](https://linux-hardware.org/?probe=38936d84ee) | Feb 28, 2025 |
| HP            | Pavilion 15                 | [b068474cd6](https://linux-hardware.org/?probe=b068474cd6) | Feb 27, 2025 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [94fd3420c0](https://linux-hardware.org/?probe=94fd3420c0) | Feb 27, 2025 |
| MSI           | Stealth 16 MercedesAMG A... | [ffe04c85c6](https://linux-hardware.org/?probe=ffe04c85c6) | Feb 27, 2025 |
| Acer          | TravelMate P214-54          | [dff8eee6b5](https://linux-hardware.org/?probe=dff8eee6b5) | Feb 25, 2025 |
| Dell          | Vostro 3560                 | [1125137333](https://linux-hardware.org/?probe=1125137333) | Feb 24, 2025 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [1cb9594d09](https://linux-hardware.org/?probe=1cb9594d09) | Feb 24, 2025 |
| Lenovo        | V330-15IKB 81AX             | [c399e48e48](https://linux-hardware.org/?probe=c399e48e48) | Feb 24, 2025 |
| Acer          | TravelMate 5760ZG           | [b850dab2ce](https://linux-hardware.org/?probe=b850dab2ce) | Feb 22, 2025 |
| Acer          | Aspire A317-54              | [3b50ce56ce](https://linux-hardware.org/?probe=3b50ce56ce) | Feb 22, 2025 |
| Dell          | Inspiron 11 - 3148          | [a3214bda64](https://linux-hardware.org/?probe=a3214bda64) | Feb 22, 2025 |
| Acer          | Swift SF314-43              | [a48173572c](https://linux-hardware.org/?probe=a48173572c) | Feb 21, 2025 |
| UMAX          | N14R                        | [ffd9e38b16](https://linux-hardware.org/?probe=ffd9e38b16) | Feb 17, 2025 |
| Lenovo        | ThinkPad T430 2349AK2       | [54c889a28d](https://linux-hardware.org/?probe=54c889a28d) | Feb 17, 2025 |
| Acer          | Nitro AN515-52              | [9ab40585de](https://linux-hardware.org/?probe=9ab40585de) | Feb 16, 2025 |
| Unknown       | Unknown                     | [8c1f6fc439](https://linux-hardware.org/?probe=8c1f6fc439) | Feb 16, 2025 |
| Lenovo        | ThinkPad T520 424049U       | [7bba198ee6](https://linux-hardware.org/?probe=7bba198ee6) | Feb 15, 2025 |
| Dell          | Precision M4800             | [1a5bccccff](https://linux-hardware.org/?probe=1a5bccccff) | Feb 14, 2025 |
| Dell          | Inspiron 5570               | [5e3fdaf9a8](https://linux-hardware.org/?probe=5e3fdaf9a8) | Feb 14, 2025 |
| Lenovo        | ThinkPad P52s 20LB000FMX    | [166c5e711a](https://linux-hardware.org/?probe=166c5e711a) | Feb 14, 2025 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f5b0d5c685](https://linux-hardware.org/?probe=f5b0d5c685) | Feb 13, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | [bf5ad68b7a](https://linux-hardware.org/?probe=bf5ad68b7a) | Feb 11, 2025 |
| Dell          | Vostro 3560                 | [085ff2e1d6](https://linux-hardware.org/?probe=085ff2e1d6) | Feb 10, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c1367a3f19](https://linux-hardware.org/?probe=c1367a3f19) | Feb 09, 2025 |
| Lenovo        | ThinkPad X260 20F5S74Y00    | [26fcf9466e](https://linux-hardware.org/?probe=26fcf9466e) | Feb 07, 2025 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | [de2f1e027f](https://linux-hardware.org/?probe=de2f1e027f) | Feb 07, 2025 |
| Fujitsu       | LIFEBOOK P771               | [65e2360d78](https://linux-hardware.org/?probe=65e2360d78) | Feb 05, 2025 |
| Fujitsu       | LIFEBOOK P771               | [8ef195ef00](https://linux-hardware.org/?probe=8ef195ef00) | Feb 05, 2025 |
| Dell          | Precision 3591              | [e94c66dabb](https://linux-hardware.org/?probe=e94c66dabb) | Feb 04, 2025 |
| ASUSTek       | X555UB                      | [19c7a90a71](https://linux-hardware.org/?probe=19c7a90a71) | Feb 03, 2025 |
| ASUSTek       | X555UB                      | [d808a04d61](https://linux-hardware.org/?probe=d808a04d61) | Feb 03, 2025 |
| HP            | ProBook 470 G3              | [ccb884d90f](https://linux-hardware.org/?probe=ccb884d90f) | Feb 03, 2025 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [d8cd238e34](https://linux-hardware.org/?probe=d8cd238e34) | Feb 03, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b13160d609](https://linux-hardware.org/?probe=b13160d609) | Feb 02, 2025 |
| Apple         | MacBookPro14,1              | [bbc2965aba](https://linux-hardware.org/?probe=bbc2965aba) | Feb 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4b5724ce8b](https://linux-hardware.org/?probe=4b5724ce8b) | Feb 01, 2025 |
| HP            | EliteBook 840 14 inch G9... | [8a0909bbfa](https://linux-hardware.org/?probe=8a0909bbfa) | Feb 01, 2025 |
| Acer          | Aspire A114-33              | [57f901fa0a](https://linux-hardware.org/?probe=57f901fa0a) | Jan 31, 2025 |
| HP            | ProBook 455 15.6 inch G1... | [b88feb7fe5](https://linux-hardware.org/?probe=b88feb7fe5) | Jan 31, 2025 |
| HP            | ProBook 450 15.6 inch G9... | [73225a9c2c](https://linux-hardware.org/?probe=73225a9c2c) | Jan 31, 2025 |
| HP            | ProBook 450 15.6 inch G9... | [8e21371f8b](https://linux-hardware.org/?probe=8e21371f8b) | Jan 31, 2025 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5440d3f272](https://linux-hardware.org/?probe=5440d3f272) | Jan 30, 2025 |
| Acer          | TravelMate P614P-53-TCO     | [5d8b75a234](https://linux-hardware.org/?probe=5d8b75a234) | Jan 29, 2025 |
| ASUSTek       | UL50VT                      | [742036c5e8](https://linux-hardware.org/?probe=742036c5e8) | Jan 28, 2025 |
| ASUSTek       | UL50VT                      | [d713ea72a6](https://linux-hardware.org/?probe=d713ea72a6) | Jan 28, 2025 |
| Lenovo        | ThinkPad W530 244744G       | [a7ebeaee91](https://linux-hardware.org/?probe=a7ebeaee91) | Jan 27, 2025 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ab66ef68ca](https://linux-hardware.org/?probe=ab66ef68ca) | Jan 27, 2025 |
| Dell          | Latitude 5480               | [c9af74f0ae](https://linux-hardware.org/?probe=c9af74f0ae) | Jan 27, 2025 |
| Lenovo        | ThinkPad E480 20KN001NXS    | [f4ead3e92c](https://linux-hardware.org/?probe=f4ead3e92c) | Jan 26, 2025 |
| Lenovo        | ThinkPad X250 20CLS75800    | [8df37ca058](https://linux-hardware.org/?probe=8df37ca058) | Jan 24, 2025 |
| HP            | Presario CQ62               | [23ed2e6a9f](https://linux-hardware.org/?probe=23ed2e6a9f) | Jan 22, 2025 |
| Lenovo        | B51-80 80LM                 | [09c7f7ab60](https://linux-hardware.org/?probe=09c7f7ab60) | Jan 22, 2025 |
| Lenovo        | B51-80 80LM                 | [a84d27f4b3](https://linux-hardware.org/?probe=a84d27f4b3) | Jan 22, 2025 |
| Lenovo        | LOQ 15AHP9 83DX             | [c4001caa51](https://linux-hardware.org/?probe=c4001caa51) | Jan 22, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [c3cb8eaf43](https://linux-hardware.org/?probe=c3cb8eaf43) | Jan 21, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [964ba8e057](https://linux-hardware.org/?probe=964ba8e057) | Jan 19, 2025 |
| HP            | EliteBook 820 G3            | [75db49fa08](https://linux-hardware.org/?probe=75db49fa08) | Jan 19, 2025 |
| HP            | EliteBook 820 G3            | [ac8637b405](https://linux-hardware.org/?probe=ac8637b405) | Jan 19, 2025 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | [0a32b0350f](https://linux-hardware.org/?probe=0a32b0350f) | Jan 18, 2025 |
| Dell          | Latitude 7490               | [66001fc217](https://linux-hardware.org/?probe=66001fc217) | Jan 17, 2025 |
| Panasonic     | CFMX4-1                     | [853afb53ec](https://linux-hardware.org/?probe=853afb53ec) | Jan 16, 2025 |
| HP            | Presario CQ62               | [8429a444bd](https://linux-hardware.org/?probe=8429a444bd) | Jan 16, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ae3ab09f71](https://linux-hardware.org/?probe=ae3ab09f71) | Jan 15, 2025 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [203a7bd128](https://linux-hardware.org/?probe=203a7bd128) | Jan 14, 2025 |
| HP            | ProBook 6465b               | [62bec1c566](https://linux-hardware.org/?probe=62bec1c566) | Jan 14, 2025 |
| Acer          | Aspire 5742G                | [c8a121a146](https://linux-hardware.org/?probe=c8a121a146) | Jan 14, 2025 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [7958e6ca89](https://linux-hardware.org/?probe=7958e6ca89) | Jan 13, 2025 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [f91658cd89](https://linux-hardware.org/?probe=f91658cd89) | Jan 13, 2025 |
| Dell          | Precision M4600             | [307eacfd84](https://linux-hardware.org/?probe=307eacfd84) | Jan 13, 2025 |
| Dell          | Precision M4600             | [ba8d6f15bb](https://linux-hardware.org/?probe=ba8d6f15bb) | Jan 12, 2025 |
| Valve         | Jupiter                     | [5b2fabbee0](https://linux-hardware.org/?probe=5b2fabbee0) | Jan 12, 2025 |
| Apple         | MacBook5,1                  | [a62f53ae2c](https://linux-hardware.org/?probe=a62f53ae2c) | Jan 11, 2025 |
| ASUSTek       | UX410UAK                    | [8e1de7f882](https://linux-hardware.org/?probe=8e1de7f882) | Jan 11, 2025 |
| Fujitsu       | LIFEBOOK E752               | [cdcf4a1ca3](https://linux-hardware.org/?probe=cdcf4a1ca3) | Jan 07, 2025 |
| Valve         | Galileo                     | [dff6a36e92](https://linux-hardware.org/?probe=dff6a36e92) | Jan 06, 2025 |
| HP            | Laptop 15-bw0xx             | [d4de478530](https://linux-hardware.org/?probe=d4de478530) | Jan 06, 2025 |
| MSI           | GE60 0NC\0ND                | [423eca6c8c](https://linux-hardware.org/?probe=423eca6c8c) | Jan 05, 2025 |
| Lenovo        | ThinkPad T60 2007WHH        | [12562aee82](https://linux-hardware.org/?probe=12562aee82) | Jan 04, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a0bbd6cf37](https://linux-hardware.org/?probe=a0bbd6cf37) | Jan 03, 2025 |
| Acer          | Extensa 5630                | [1bb020a4af](https://linux-hardware.org/?probe=1bb020a4af) | Jan 03, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ffdf653988](https://linux-hardware.org/?probe=ffdf653988) | Jan 03, 2025 |
| Fujitsu       | LIFEBOOK E751               | [d6240bc771](https://linux-hardware.org/?probe=d6240bc771) | Jan 02, 2025 |
| Lenovo        | ThinkPad L16 Gen 1 21L70... | [1295119c04](https://linux-hardware.org/?probe=1295119c04) | Jan 01, 2025 |
| HP            | Compaq 610                  | [af961e1650](https://linux-hardware.org/?probe=af961e1650) | Dec 29, 2024 |
| Dell          | Vostro 5620                 | [8d70ffd3a6](https://linux-hardware.org/?probe=8d70ffd3a6) | Dec 28, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | [b378ee4e63](https://linux-hardware.org/?probe=b378ee4e63) | Dec 27, 2024 |
| Dell          | Latitude E5540              | [0f0b366b45](https://linux-hardware.org/?probe=0f0b366b45) | Dec 26, 2024 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [e5724d5492](https://linux-hardware.org/?probe=e5724d5492) | Dec 26, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [38333ea200](https://linux-hardware.org/?probe=38333ea200) | Dec 26, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [3619de98bb](https://linux-hardware.org/?probe=3619de98bb) | Dec 26, 2024 |
| Acer          | Aspire V3-571G              | [1c7d970f58](https://linux-hardware.org/?probe=1c7d970f58) | Dec 26, 2024 |
| Toshiba       | Satellite C55-A             | [019825dc9f](https://linux-hardware.org/?probe=019825dc9f) | Dec 24, 2024 |
| TUXEDO        | Pulse 14 Gen1               | [d1fe4c6194](https://linux-hardware.org/?probe=d1fe4c6194) | Dec 21, 2024 |
| Dell          | System Vostro 3750          | [f765051029](https://linux-hardware.org/?probe=f765051029) | Dec 21, 2024 |
| Acer          | TravelMate B113             | [e4b7bfda97](https://linux-hardware.org/?probe=e4b7bfda97) | Dec 21, 2024 |
| Dell          | Inspiron 11 - 3148          | [d83af261a5](https://linux-hardware.org/?probe=d83af261a5) | Dec 21, 2024 |
| Dell          | XPS 17 9700                 | [a9eb169ad3](https://linux-hardware.org/?probe=a9eb169ad3) | Dec 21, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | [6107bb3e8d](https://linux-hardware.org/?probe=6107bb3e8d) | Dec 20, 2024 |
| Fujitsu       | LIFEBOOK E752               | [6299219a54](https://linux-hardware.org/?probe=6299219a54) | Dec 20, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [e21a2d89c6](https://linux-hardware.org/?probe=e21a2d89c6) | Dec 18, 2024 |
| HP            | 550                         | [c401aa1e31](https://linux-hardware.org/?probe=c401aa1e31) | Dec 17, 2024 |
| HP            | 550                         | [4890cb5e06](https://linux-hardware.org/?probe=4890cb5e06) | Dec 16, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [5a45b1695a](https://linux-hardware.org/?probe=5a45b1695a) | Dec 16, 2024 |
| HP            | 250 G3                      | [33fd855839](https://linux-hardware.org/?probe=33fd855839) | Dec 15, 2024 |
| ASUSTek       | N73SV                       | [633d0b0190](https://linux-hardware.org/?probe=633d0b0190) | Dec 15, 2024 |
| Acer          | Swift SFX14-41G             | [b0a6e23086](https://linux-hardware.org/?probe=b0a6e23086) | Dec 14, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [4457d325cd](https://linux-hardware.org/?probe=4457d325cd) | Dec 13, 2024 |
| Dell          | Precision 3550              | [dd9f0d9ae3](https://linux-hardware.org/?probe=dd9f0d9ae3) | Dec 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MDS... | [67cd429682](https://linux-hardware.org/?probe=67cd429682) | Dec 09, 2024 |
| UMAX          | VisionBook 14WRx            | [03c3fb91c0](https://linux-hardware.org/?probe=03c3fb91c0) | Dec 08, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [6a8446aa46](https://linux-hardware.org/?probe=6a8446aa46) | Dec 08, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [3cef41bf58](https://linux-hardware.org/?probe=3cef41bf58) | Dec 08, 2024 |
| HP            | ProBook 470 G3              | [f6ed449358](https://linux-hardware.org/?probe=f6ed449358) | Dec 08, 2024 |
| Lenovo        | ThinkPad E450 20DC007SMC    | [a6df288487](https://linux-hardware.org/?probe=a6df288487) | Dec 07, 2024 |
| Lenovo        | ThinkPad T410 2537K96       | [ae6d2e915b](https://linux-hardware.org/?probe=ae6d2e915b) | Dec 06, 2024 |
| Lenovo        | ThinkPad X230 23252CG       | [614068917c](https://linux-hardware.org/?probe=614068917c) | Dec 04, 2024 |
| ASUSTek       | K52JK                       | [1e978f8201](https://linux-hardware.org/?probe=1e978f8201) | Dec 03, 2024 |
| Toshiba       | Satellite L500              | [81df2f2b8e](https://linux-hardware.org/?probe=81df2f2b8e) | Nov 29, 2024 |
| Dell          | Latitude E5440              | [0177ef8c95](https://linux-hardware.org/?probe=0177ef8c95) | Nov 29, 2024 |
| ASUSTek       | X705UA                      | [8fb1e3980c](https://linux-hardware.org/?probe=8fb1e3980c) | Nov 27, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [028fe1f620](https://linux-hardware.org/?probe=028fe1f620) | Nov 24, 2024 |
| Notebook      | NV4xPZ                      | [96c89d3fef](https://linux-hardware.org/?probe=96c89d3fef) | Nov 22, 2024 |
| HP            | ZBook Firefly 14 inch G1... | [eae74be3bd](https://linux-hardware.org/?probe=eae74be3bd) | Nov 22, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [4b11bad4e2](https://linux-hardware.org/?probe=4b11bad4e2) | Nov 21, 2024 |
| HP            | ZBook Firefly 16 inch G1... | [515f77bdad](https://linux-hardware.org/?probe=515f77bdad) | Nov 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [81b39da9fd](https://linux-hardware.org/?probe=81b39da9fd) | Nov 19, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cc9386b2dd](https://linux-hardware.org/?probe=cc9386b2dd) | Nov 19, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [06da77f5c0](https://linux-hardware.org/?probe=06da77f5c0) | Nov 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [5f6a56e720](https://linux-hardware.org/?probe=5f6a56e720) | Nov 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [1ff2d7429c](https://linux-hardware.org/?probe=1ff2d7429c) | Nov 15, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [c8bf7ad9df](https://linux-hardware.org/?probe=c8bf7ad9df) | Nov 14, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS9... | [741e754d50](https://linux-hardware.org/?probe=741e754d50) | Nov 14, 2024 |
| Dell          | Latitude 7400               | [44e1fbf742](https://linux-hardware.org/?probe=44e1fbf742) | Nov 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [be79f50c9e](https://linux-hardware.org/?probe=be79f50c9e) | Nov 13, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [e5d1eddfaa](https://linux-hardware.org/?probe=e5d1eddfaa) | Nov 13, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [3a61b52c42](https://linux-hardware.org/?probe=3a61b52c42) | Nov 13, 2024 |
| Dell          | Latitude 7400               | [e0b2bc0e77](https://linux-hardware.org/?probe=e0b2bc0e77) | Nov 12, 2024 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [14d794125a](https://linux-hardware.org/?probe=14d794125a) | Nov 12, 2024 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [9365473cc4](https://linux-hardware.org/?probe=9365473cc4) | Nov 12, 2024 |
| Sony          | VGN-Z51MG_B                 | [704fd4df01](https://linux-hardware.org/?probe=704fd4df01) | Nov 10, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [b5fbe784ce](https://linux-hardware.org/?probe=b5fbe784ce) | Nov 09, 2024 |
| HP            | ProBook 430 G2              | [ea645a6ae1](https://linux-hardware.org/?probe=ea645a6ae1) | Nov 08, 2024 |
| MSI           | P75 Creator 9SE             | [f37da1e270](https://linux-hardware.org/?probe=f37da1e270) | Nov 06, 2024 |
| Acer          | Extensa 7630EZ              | [5c48b2f063](https://linux-hardware.org/?probe=5c48b2f063) | Nov 02, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [67f2f24139](https://linux-hardware.org/?probe=67f2f24139) | Nov 02, 2024 |
| Dell          | Latitude 5410               | [7e4f2bc66a](https://linux-hardware.org/?probe=7e4f2bc66a) | Oct 30, 2024 |
| Dell          | Latitude 5410               | [4fdba8edb7](https://linux-hardware.org/?probe=4fdba8edb7) | Oct 30, 2024 |
| Dell          | Latitude 5410               | [a4cdab59be](https://linux-hardware.org/?probe=a4cdab59be) | Oct 30, 2024 |
| Dell          | Latitude E6510              | [6f5fdc54c6](https://linux-hardware.org/?probe=6f5fdc54c6) | Oct 28, 2024 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [ee9023251f](https://linux-hardware.org/?probe=ee9023251f) | Oct 26, 2024 |
| Dell          | Latitude D820               | [e8052d5ecd](https://linux-hardware.org/?probe=e8052d5ecd) | Oct 26, 2024 |
| Dell          | Latitude D820               | [69777b44d3](https://linux-hardware.org/?probe=69777b44d3) | Oct 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [51f11aa9f2](https://linux-hardware.org/?probe=51f11aa9f2) | Oct 25, 2024 |
| Acer          | Extensa 7630EZ              | [65c6658e55](https://linux-hardware.org/?probe=65c6658e55) | Oct 25, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [730ef7c5f8](https://linux-hardware.org/?probe=730ef7c5f8) | Oct 24, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [82a1bda877](https://linux-hardware.org/?probe=82a1bda877) | Oct 24, 2024 |
| Dell          | Latitude 7370               | [355bbe7ecc](https://linux-hardware.org/?probe=355bbe7ecc) | Oct 24, 2024 |
| HP            | EliteBook 2540p             | [53c668190f](https://linux-hardware.org/?probe=53c668190f) | Oct 23, 2024 |
| Acer          | Swift SF14-71T              | [e190faa132](https://linux-hardware.org/?probe=e190faa132) | Oct 22, 2024 |
| Lenovo        | Z50-75 80EC                 | [6ff4eea4bd](https://linux-hardware.org/?probe=6ff4eea4bd) | Oct 21, 2024 |
| HP            | ENVY Laptop 16-h0xxx        | [d367026292](https://linux-hardware.org/?probe=d367026292) | Oct 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [59e88e8f10](https://linux-hardware.org/?probe=59e88e8f10) | Oct 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [049ff16565](https://linux-hardware.org/?probe=049ff16565) | Oct 19, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5754b92f35](https://linux-hardware.org/?probe=5754b92f35) | Oct 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [eee2e39a57](https://linux-hardware.org/?probe=eee2e39a57) | Oct 19, 2024 |
| Acer          | Aspire E5-573               | [52f3006e15](https://linux-hardware.org/?probe=52f3006e15) | Oct 18, 2024 |
| Dell          | Latitude 5450               | [c5a078d239](https://linux-hardware.org/?probe=c5a078d239) | Oct 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MDS... | [2d00c7ffe3](https://linux-hardware.org/?probe=2d00c7ffe3) | Oct 18, 2024 |
| Valve         | Jupiter                     | [c857c25534](https://linux-hardware.org/?probe=c857c25534) | Oct 18, 2024 |
| Toshiba       | Satellite A200              | [c480e14ad8](https://linux-hardware.org/?probe=c480e14ad8) | Oct 17, 2024 |
| Acer          | Nitro AN515-44              | [505d70884f](https://linux-hardware.org/?probe=505d70884f) | Oct 17, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [bd0906dab7](https://linux-hardware.org/?probe=bd0906dab7) | Oct 17, 2024 |
| Lenovo        | V110-15ISK 80TL             | [6cef126bcc](https://linux-hardware.org/?probe=6cef126bcc) | Oct 12, 2024 |
| HP            | EliteBook 840 G3            | [df0a50bafb](https://linux-hardware.org/?probe=df0a50bafb) | Oct 12, 2024 |
| HP            | 15                          | [812b65f0fe](https://linux-hardware.org/?probe=812b65f0fe) | Oct 11, 2024 |
| Lenovo        | ThinkPad T420 4236NVG       | [a76195d435](https://linux-hardware.org/?probe=a76195d435) | Oct 11, 2024 |
| Timi          | A35S                        | [2e925c5cd6](https://linux-hardware.org/?probe=2e925c5cd6) | Oct 11, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [05af8a3249](https://linux-hardware.org/?probe=05af8a3249) | Oct 10, 2024 |
| Dell          | Latitude 5440               | [71ee76b243](https://linux-hardware.org/?probe=71ee76b243) | Oct 10, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [11bd71149b](https://linux-hardware.org/?probe=11bd71149b) | Oct 10, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b2a2d78933](https://linux-hardware.org/?probe=b2a2d78933) | Oct 10, 2024 |
| Lenovo        | U310                        | [bb887be5e7](https://linux-hardware.org/?probe=bb887be5e7) | Oct 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8428643c32](https://linux-hardware.org/?probe=8428643c32) | Oct 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d58ea9b2a0](https://linux-hardware.org/?probe=d58ea9b2a0) | Oct 07, 2024 |
| HP            | 250 G4                      | [c686ed18ff](https://linux-hardware.org/?probe=c686ed18ff) | Oct 06, 2024 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [c7823c9fd3](https://linux-hardware.org/?probe=c7823c9fd3) | Oct 05, 2024 |
| Dell          | Latitude 5440               | [15ad67d4bf](https://linux-hardware.org/?probe=15ad67d4bf) | Oct 05, 2024 |
| HP            | EliteBook 2540p             | [582f0a4f04](https://linux-hardware.org/?probe=582f0a4f04) | Oct 04, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [4b94f1e513](https://linux-hardware.org/?probe=4b94f1e513) | Oct 03, 2024 |
| ASUSTek       | X75VBP                      | [0c6a739c42](https://linux-hardware.org/?probe=0c6a739c42) | Oct 03, 2024 |
| ASUSTek       | X75VBP                      | [b34a212443](https://linux-hardware.org/?probe=b34a212443) | Oct 03, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [d52e4fc3c0](https://linux-hardware.org/?probe=d52e4fc3c0) | Oct 02, 2024 |
| Lenovo        | ThinkPad T440s 20ARS0HB0... | [820ea26e25](https://linux-hardware.org/?probe=820ea26e25) | Sep 30, 2024 |
| HP            | EliteBook 840 G3            | [4d52b9b4ac](https://linux-hardware.org/?probe=4d52b9b4ac) | Sep 29, 2024 |
| HP            | Pavilion Laptop 14-ec1xx... | [0a0cbfcc0c](https://linux-hardware.org/?probe=0a0cbfcc0c) | Sep 27, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [5daa956157](https://linux-hardware.org/?probe=5daa956157) | Sep 26, 2024 |
| Samsung       | RF511/RF411/RF711           | [da831230cc](https://linux-hardware.org/?probe=da831230cc) | Sep 25, 2024 |
| Dell          | Latitude 5530               | [bfba40b6f7](https://linux-hardware.org/?probe=bfba40b6f7) | Sep 24, 2024 |
| Valve         | Galileo                     | [c863bb9916](https://linux-hardware.org/?probe=c863bb9916) | Sep 24, 2024 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [20e79a1fff](https://linux-hardware.org/?probe=20e79a1fff) | Sep 23, 2024 |
| Apple         | MacBook9,1                  | [99bbe2dde8](https://linux-hardware.org/?probe=99bbe2dde8) | Sep 23, 2024 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [4e3912d4f2](https://linux-hardware.org/?probe=4e3912d4f2) | Sep 22, 2024 |
| HP            | EliteBook 8460p             | [6f4f22f0bc](https://linux-hardware.org/?probe=6f4f22f0bc) | Sep 19, 2024 |
| Dell          | Latitude E6520              | [fb6b6c04d3](https://linux-hardware.org/?probe=fb6b6c04d3) | Sep 19, 2024 |
| Dell          | Latitude E6520              | [b9cef5fd04](https://linux-hardware.org/?probe=b9cef5fd04) | Sep 18, 2024 |
| Dell          | Latitude E6420              | [de841c2a57](https://linux-hardware.org/?probe=de841c2a57) | Sep 18, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [5e08e7f1f0](https://linux-hardware.org/?probe=5e08e7f1f0) | Sep 17, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [048b958f3f](https://linux-hardware.org/?probe=048b958f3f) | Sep 17, 2024 |
| Lenovo        | U310                        | [f09c1c114b](https://linux-hardware.org/?probe=f09c1c114b) | Sep 11, 2024 |
| HP            | EliteBook 840 G6            | [9fe4170603](https://linux-hardware.org/?probe=9fe4170603) | Sep 10, 2024 |
| Apple         | MacBookAir6,2               | [c2a9e07bb5](https://linux-hardware.org/?probe=c2a9e07bb5) | Sep 09, 2024 |
| Fujitsu       | LIFEBOOK U7311              | [2565533bd4](https://linux-hardware.org/?probe=2565533bd4) | Sep 09, 2024 |
| Samsung       | RF511/RF411/RF711           | [ebf317a332](https://linux-hardware.org/?probe=ebf317a332) | Sep 07, 2024 |
| Dell          | Inspiron 3583               | [35acec26c2](https://linux-hardware.org/?probe=35acec26c2) | Sep 07, 2024 |
| Acer          | One S1002                   | [42601193da](https://linux-hardware.org/?probe=42601193da) | Sep 06, 2024 |
| Acer          | One S1002                   | [1730c8b423](https://linux-hardware.org/?probe=1730c8b423) | Sep 06, 2024 |
| Sony          | VPCSB2L1E                   | [40ae94a55a](https://linux-hardware.org/?probe=40ae94a55a) | Sep 06, 2024 |
| Sony          | VPCSB2L1E                   | [3155245cba](https://linux-hardware.org/?probe=3155245cba) | Sep 05, 2024 |
| HP            | ENVY dv7                    | [f06843f3fc](https://linux-hardware.org/?probe=f06843f3fc) | Sep 04, 2024 |
| HP            | Compaq 610                  | [878252e1da](https://linux-hardware.org/?probe=878252e1da) | Sep 02, 2024 |
| HP            | G72                         | [3e3c18c84c](https://linux-hardware.org/?probe=3e3c18c84c) | Sep 01, 2024 |
| HP            | G72                         | [26352c9d5a](https://linux-hardware.org/?probe=26352c9d5a) | Sep 01, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0bb61612c1](https://linux-hardware.org/?probe=0bb61612c1) | Aug 31, 2024 |
| Unknown       | Unknown                     | [ce358de40a](https://linux-hardware.org/?probe=ce358de40a) | Aug 30, 2024 |
| HP            | Laptop 15-rb0xx             | [491800a55e](https://linux-hardware.org/?probe=491800a55e) | Aug 30, 2024 |
| Unknown       | Unknown                     | [fb7e560078](https://linux-hardware.org/?probe=fb7e560078) | Aug 28, 2024 |
| IBM           | ThinkPad T43 2668BU7        | [879c92e2cb](https://linux-hardware.org/?probe=879c92e2cb) | Aug 26, 2024 |
| Acer          | Swift SFX14-41G             | [4977e3c5f8](https://linux-hardware.org/?probe=4977e3c5f8) | Aug 26, 2024 |
| ASUSTek       | UX31E                       | [e909c7ac51](https://linux-hardware.org/?probe=e909c7ac51) | Aug 25, 2024 |
| HP            | ENVY Notebook               | [0374693fee](https://linux-hardware.org/?probe=0374693fee) | Aug 24, 2024 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [d7ddccb5f3](https://linux-hardware.org/?probe=d7ddccb5f3) | Aug 23, 2024 |
| HP            | 255 G8 Notebook PC          | [ac894331d2](https://linux-hardware.org/?probe=ac894331d2) | Aug 22, 2024 |
| HP            | ProBook 455 G8 Notebook ... | [5dd0130b6b](https://linux-hardware.org/?probe=5dd0130b6b) | Aug 21, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [cddf602a76](https://linux-hardware.org/?probe=cddf602a76) | Aug 20, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | [080d34db04](https://linux-hardware.org/?probe=080d34db04) | Aug 19, 2024 |
| Dell          | Inspiron 5537               | [e7e552b46c](https://linux-hardware.org/?probe=e7e552b46c) | Aug 18, 2024 |
| ASUSTek       | ASUS Vivobook S 16 S5606... | [7059aa165a](https://linux-hardware.org/?probe=7059aa165a) | Aug 17, 2024 |
| Dell          | Vostro 3520                 | [8dfe5a0087](https://linux-hardware.org/?probe=8dfe5a0087) | Aug 17, 2024 |
| Notebook      | NV4xPZ                      | [794eceb2ee](https://linux-hardware.org/?probe=794eceb2ee) | Aug 16, 2024 |
| Dell          | Latitude E6420              | [368fe1e67b](https://linux-hardware.org/?probe=368fe1e67b) | Aug 14, 2024 |
| Acer          | Aspire A715-42G             | [59afb561de](https://linux-hardware.org/?probe=59afb561de) | Aug 14, 2024 |
| HP            | EliteBook 840 G4            | [681b90e3e4](https://linux-hardware.org/?probe=681b90e3e4) | Aug 09, 2024 |
| HP            | EliteBook 650 15.6 inch ... | [a832b68002](https://linux-hardware.org/?probe=a832b68002) | Aug 09, 2024 |
| HP            | ProBook 455 G8 Notebook ... | [0e1b307171](https://linux-hardware.org/?probe=0e1b307171) | Aug 08, 2024 |
| Lenovo        | B590 20206                  | [28e0a61e11](https://linux-hardware.org/?probe=28e0a61e11) | Aug 07, 2024 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | [5fd7b86069](https://linux-hardware.org/?probe=5fd7b86069) | Aug 06, 2024 |
| Lenovo        | G500 20236                  | [b2e258b73f](https://linux-hardware.org/?probe=b2e258b73f) | Aug 05, 2024 |
| ASUSTek       | Zenbook UX8402ZE_UX8402Z... | [0f8276d3d6](https://linux-hardware.org/?probe=0f8276d3d6) | Aug 04, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8b221a21ce](https://linux-hardware.org/?probe=8b221a21ce) | Aug 02, 2024 |
| Dell          | Inspiron 7400               | [8e52b6d214](https://linux-hardware.org/?probe=8e52b6d214) | Jul 31, 2024 |
| Apple         | MacBookAir6,2               | [6848bfb011](https://linux-hardware.org/?probe=6848bfb011) | Jul 31, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e2d5da8fc8](https://linux-hardware.org/?probe=e2d5da8fc8) | Jul 28, 2024 |
| Dell          | Latitude E6420              | [c941a3c642](https://linux-hardware.org/?probe=c941a3c642) | Jul 28, 2024 |
| HP            | Pavilion g6                 | [60b2ae433d](https://linux-hardware.org/?probe=60b2ae433d) | Jul 27, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [2e002b034a](https://linux-hardware.org/?probe=2e002b034a) | Jul 26, 2024 |
| Apple         | MacBookAir6,2               | [4f305860f2](https://linux-hardware.org/?probe=4f305860f2) | Jul 25, 2024 |
| ASUSTek       | GL702VMK                    | [47b0561d4f](https://linux-hardware.org/?probe=47b0561d4f) | Jul 25, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [39620c0d06](https://linux-hardware.org/?probe=39620c0d06) | Jul 25, 2024 |
| ASUSTek       | GL702VMK                    | [9e3c872bf0](https://linux-hardware.org/?probe=9e3c872bf0) | Jul 24, 2024 |
| ASUSTek       | X550CA                      | [b166d93b76](https://linux-hardware.org/?probe=b166d93b76) | Jul 24, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21J30... | [bce04e30af](https://linux-hardware.org/?probe=bce04e30af) | Jul 24, 2024 |
| Dell          | Latitude 7440               | [661175db26](https://linux-hardware.org/?probe=661175db26) | Jul 24, 2024 |
| Dell          | XPS 15 9500                 | [6b10bded5b](https://linux-hardware.org/?probe=6b10bded5b) | Jul 23, 2024 |
| ASUSTek       | UX31E                       | [566e36f5b1](https://linux-hardware.org/?probe=566e36f5b1) | Jul 23, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [2a1301a1d4](https://linux-hardware.org/?probe=2a1301a1d4) | Jul 23, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4e3f61c287](https://linux-hardware.org/?probe=4e3f61c287) | Jul 23, 2024 |
| HP            | EliteBook 650 15.6 inch ... | [861a7296b1](https://linux-hardware.org/?probe=861a7296b1) | Jul 23, 2024 |
| HP            | EliteBook 840 G3            | [7d9330f136](https://linux-hardware.org/?probe=7d9330f136) | Jul 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f425651aeb](https://linux-hardware.org/?probe=f425651aeb) | Jul 19, 2024 |
| UMAX          | VisionBook 12WRx            | [4f3f84eb25](https://linux-hardware.org/?probe=4f3f84eb25) | Jul 19, 2024 |
| Dell          | Precision M4600             | [ae485ec60d](https://linux-hardware.org/?probe=ae485ec60d) | Jul 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f307cc5dc](https://linux-hardware.org/?probe=3f307cc5dc) | Jul 16, 2024 |
| Lenovo        | ThinkPad T440 20B7S0W900    | [a98535cd6b](https://linux-hardware.org/?probe=a98535cd6b) | Jul 15, 2024 |
| Lenovo        | E50-80 80J2                 | [d8878401b4](https://linux-hardware.org/?probe=d8878401b4) | Jul 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [aed926371d](https://linux-hardware.org/?probe=aed926371d) | Jul 15, 2024 |
| HP            | Compaq 615                  | [13c2b97b62](https://linux-hardware.org/?probe=13c2b97b62) | Jul 14, 2024 |
| HP            | EliteBook 2170p             | [0e17ae5ff1](https://linux-hardware.org/?probe=0e17ae5ff1) | Jul 13, 2024 |
| Toshiba       | Satellite S70-B10U          | [723a473ae6](https://linux-hardware.org/?probe=723a473ae6) | Jul 12, 2024 |
| Acer          | Aspire 5310                 | [7639bd1fe6](https://linux-hardware.org/?probe=7639bd1fe6) | Jul 11, 2024 |
| Acer          | Aspire 5310                 | [002836bd98](https://linux-hardware.org/?probe=002836bd98) | Jul 11, 2024 |
| Dell          | Latitude E7440              | [4f8117eff3](https://linux-hardware.org/?probe=4f8117eff3) | Jul 10, 2024 |
| HP            | ZBook Power 15.6 inch G1... | [79dcba3221](https://linux-hardware.org/?probe=79dcba3221) | Jul 10, 2024 |
| HP            | Victus by Gaming Laptop ... | [8bc2731133](https://linux-hardware.org/?probe=8bc2731133) | Jul 10, 2024 |
| Dell          | Latitude 7480               | [5958b524e2](https://linux-hardware.org/?probe=5958b524e2) | Jul 08, 2024 |
| Lenovo        | ThinkPad X201 3680DE3       | [a62d6da87a](https://linux-hardware.org/?probe=a62d6da87a) | Jul 07, 2024 |
| ASUSTek       | K53E                        | [d3a0f69d1b](https://linux-hardware.org/?probe=d3a0f69d1b) | Jul 06, 2024 |
| MSI           | MS-168B                     | [5c73f01c7e](https://linux-hardware.org/?probe=5c73f01c7e) | Jul 06, 2024 |
| HP            | Compaq 615                  | [c5ed0bad98](https://linux-hardware.org/?probe=c5ed0bad98) | Jul 03, 2024 |
| Dell          | G5 5590                     | [2e3a79efec](https://linux-hardware.org/?probe=2e3a79efec) | Jul 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [a6e35dde0d](https://linux-hardware.org/?probe=a6e35dde0d) | Jun 29, 2024 |
| Lenovo        | ThinkPad Edge E540 20C60... | [e5eee1d663](https://linux-hardware.org/?probe=e5eee1d663) | Jun 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6024f234f9](https://linux-hardware.org/?probe=6024f234f9) | Jun 28, 2024 |
| Lenovo        | G500 20236                  | [26b7a44021](https://linux-hardware.org/?probe=26b7a44021) | Jun 28, 2024 |
| Dell          | XPS 15 9510                 | [b40878b68f](https://linux-hardware.org/?probe=b40878b68f) | Jun 24, 2024 |
| Samsung       | R530/R730                   | [02dfdcedc8](https://linux-hardware.org/?probe=02dfdcedc8) | Jun 22, 2024 |
| Samsung       | R530/R730                   | [d4f6ab2a15](https://linux-hardware.org/?probe=d4f6ab2a15) | Jun 22, 2024 |
| UMAX          | 13Wr                        | [a791c2a7dc](https://linux-hardware.org/?probe=a791c2a7dc) | Jun 22, 2024 |
| ASUSTek       | G71V                        | [ed6b8bb127](https://linux-hardware.org/?probe=ed6b8bb127) | Jun 21, 2024 |
| ASUSTek       | G71V                        | [5f136475b0](https://linux-hardware.org/?probe=5f136475b0) | Jun 21, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [e179a0e8f7](https://linux-hardware.org/?probe=e179a0e8f7) | Jun 20, 2024 |
| Schenker      | VIA 14 Pro (M24)            | [b85ceb17a8](https://linux-hardware.org/?probe=b85ceb17a8) | Jun 20, 2024 |
| ASUSTek       | GL702VMK                    | [53899b0651](https://linux-hardware.org/?probe=53899b0651) | Jun 18, 2024 |
| HP            | Laptop 15-fd0xxx            | [2a9b456b7b](https://linux-hardware.org/?probe=2a9b456b7b) | Jun 17, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c026a2e07b](https://linux-hardware.org/?probe=c026a2e07b) | Jun 16, 2024 |
| Valve         | Jupiter                     | [1c05546f6c](https://linux-hardware.org/?probe=1c05546f6c) | Jun 16, 2024 |
| HP            | EliteBook 830 G7 Noteboo... | [f960ad3a70](https://linux-hardware.org/?probe=f960ad3a70) | Jun 14, 2024 |
| Acer          | Aspire E5-572G              | [1b882e8719](https://linux-hardware.org/?probe=1b882e8719) | Jun 14, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [bcde5b5704](https://linux-hardware.org/?probe=bcde5b5704) | Jun 14, 2024 |
| Lenovo        | ThinkPad Edge E540 20C60... | [bdb772a648](https://linux-hardware.org/?probe=bdb772a648) | Jun 11, 2024 |
| Dell          | Latitude 5411               | [331d3257cf](https://linux-hardware.org/?probe=331d3257cf) | Jun 10, 2024 |
| Dell          | Inspiron 15 3525            | [20251eaa38](https://linux-hardware.org/?probe=20251eaa38) | Jun 09, 2024 |
| Lenovo        | B5400 80B6QB0               | [05953da264](https://linux-hardware.org/?probe=05953da264) | Jun 09, 2024 |
| Star Labs     | StarBook                    | [494a86a905](https://linux-hardware.org/?probe=494a86a905) | Jun 08, 2024 |
| HP            | Compaq 615                  | [77cb8453bc](https://linux-hardware.org/?probe=77cb8453bc) | Jun 03, 2024 |
| Lenovo        | E31-70 80KX                 | [3f7f65ab96](https://linux-hardware.org/?probe=3f7f65ab96) | Jun 03, 2024 |
| Lenovo        | E31-70 80KX                 | [e968029762](https://linux-hardware.org/?probe=e968029762) | Jun 03, 2024 |
| Acer          | Nitro AN517-41              | [541f9885c5](https://linux-hardware.org/?probe=541f9885c5) | Jun 03, 2024 |
| MSI           | GT628                       | [42403c8496](https://linux-hardware.org/?probe=42403c8496) | Jun 01, 2024 |
| MSI           | GT628                       | [b57f1b2e55](https://linux-hardware.org/?probe=b57f1b2e55) | Jun 01, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5e8bd6884b](https://linux-hardware.org/?probe=5e8bd6884b) | Jun 01, 2024 |
| Fujitsu       | LIFEBOOK U759               | [34f894fbbe](https://linux-hardware.org/?probe=34f894fbbe) | May 29, 2024 |
| Lenovo        | ThinkPad Edge E540 20C60... | [69597ed906](https://linux-hardware.org/?probe=69597ed906) | May 27, 2024 |
| ASUSTek       | 1201N                       | [6466d5ce59](https://linux-hardware.org/?probe=6466d5ce59) | May 27, 2024 |
| MSI           | Creator Z16P B12UGST        | [a37d290e30](https://linux-hardware.org/?probe=a37d290e30) | May 26, 2024 |
| Lenovo        | Y50-70 20378                | [c51c97df3a](https://linux-hardware.org/?probe=c51c97df3a) | May 26, 2024 |
| MSI           | Bravo 17 C7VF               | [0ececdc6c4](https://linux-hardware.org/?probe=0ececdc6c4) | May 25, 2024 |
| Acer          | Aspire one 1-132            | [1408efda14](https://linux-hardware.org/?probe=1408efda14) | May 24, 2024 |
| Lenovo        | ThinkPad X270 20HMS25S00    | [253d2e5692](https://linux-hardware.org/?probe=253d2e5692) | May 23, 2024 |
| ASUSTek       | UL50VT                      | [6754fc4692](https://linux-hardware.org/?probe=6754fc4692) | May 20, 2024 |
| Dell          | Latitude E6400              | [47b3359fb9](https://linux-hardware.org/?probe=47b3359fb9) | May 18, 2024 |
| ASUSTek       | UX31E                       | [0fd2dc51a9](https://linux-hardware.org/?probe=0fd2dc51a9) | May 18, 2024 |
| Lenovo        | G500 20236                  | [4f8fab1cb8](https://linux-hardware.org/?probe=4f8fab1cb8) | May 18, 2024 |
| Lenovo        | G500 20236                  | [df0de8a67c](https://linux-hardware.org/?probe=df0de8a67c) | May 18, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CVA... | [2aef52d6b3](https://linux-hardware.org/?probe=2aef52d6b3) | May 17, 2024 |
| HP            | Compaq 6730b (NN449ES#AK... | [b5c1e233fa](https://linux-hardware.org/?probe=b5c1e233fa) | May 15, 2024 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [10dff4042c](https://linux-hardware.org/?probe=10dff4042c) | May 14, 2024 |
| HP            | EliteBook 840 G3            | [8bd7819691](https://linux-hardware.org/?probe=8bd7819691) | May 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [e7a8669eac](https://linux-hardware.org/?probe=e7a8669eac) | May 13, 2024 |
| Dell          | Latitude E6400              | [f933cd0cfd](https://linux-hardware.org/?probe=f933cd0cfd) | May 13, 2024 |
| Sony          | VPCEH3S1E                   | [5bef66930b](https://linux-hardware.org/?probe=5bef66930b) | May 12, 2024 |
| Apple         | MacBookAir6,2               | [323d54a280](https://linux-hardware.org/?probe=323d54a280) | May 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S29D0W    | [273a642213](https://linux-hardware.org/?probe=273a642213) | May 10, 2024 |
| ASUSTek       | X75VBP                      | [45dd9e0bea](https://linux-hardware.org/?probe=45dd9e0bea) | May 09, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L2502CYA... | [03df260579](https://linux-hardware.org/?probe=03df260579) | May 09, 2024 |
| Sony          | VGN-Z51MG_B                 | [6e5ed9d5f6](https://linux-hardware.org/?probe=6e5ed9d5f6) | May 08, 2024 |
| Hetrix        | Unknown                     | [72a5c6fffe](https://linux-hardware.org/?probe=72a5c6fffe) | May 08, 2024 |
| Lenovo        | ThinkPad Edge E330 3354D... | [4f7e381c6f](https://linux-hardware.org/?probe=4f7e381c6f) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [9122522638](https://linux-hardware.org/?probe=9122522638) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3064d4fb1f](https://linux-hardware.org/?probe=3064d4fb1f) | May 07, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| ASUSTek       | ROG Strix G731GV_G731GV     | [00ceb2ea16](https://linux-hardware.org/?probe=00ceb2ea16) | May 06, 2024 |
| TUXEDO        | Sirius 16 Gen1              | [b093c73dcb](https://linux-hardware.org/?probe=b093c73dcb) | May 04, 2024 |
| Lenovo        | U310                        | [0ce2072c15](https://linux-hardware.org/?probe=0ce2072c15) | May 04, 2024 |
| HP            | EliteBook 8470p             | [2480bab346](https://linux-hardware.org/?probe=2480bab346) | May 02, 2024 |
| HP            | ProBook 4510s               | [a6f89b6485](https://linux-hardware.org/?probe=a6f89b6485) | May 02, 2024 |
| Lenovo        | U310                        | [48cb164f2f](https://linux-hardware.org/?probe=48cb164f2f) | May 01, 2024 |
| Lenovo        | ThinkPad SL510 2847Q7G      | [c2f435ff58](https://linux-hardware.org/?probe=c2f435ff58) | May 01, 2024 |
| ASUSTek       | UX430UNR                    | [5712b06d98](https://linux-hardware.org/?probe=5712b06d98) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | [a032f50d3f](https://linux-hardware.org/?probe=a032f50d3f) | Apr 30, 2024 |
| Lenovo        | ThinkPad X250 20CLS75800    | [7626333cd6](https://linux-hardware.org/?probe=7626333cd6) | Apr 29, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [4060d6bdbe](https://linux-hardware.org/?probe=4060d6bdbe) | Apr 29, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [885d49a692](https://linux-hardware.org/?probe=885d49a692) | Apr 29, 2024 |
| Minix         | Z64 V1.2                    | [7c0143f3e4](https://linux-hardware.org/?probe=7c0143f3e4) | Apr 28, 2024 |
| Lenovo        | ThinkPad T420 4180D81       | [586b69e749](https://linux-hardware.org/?probe=586b69e749) | Apr 23, 2024 |
| Dell          | Precision 7510              | [23916f1909](https://linux-hardware.org/?probe=23916f1909) | Apr 22, 2024 |
| HP            | ProBook 650 G1              | [09883eb0c7](https://linux-hardware.org/?probe=09883eb0c7) | Apr 22, 2024 |
| HP            | Pavilion 15                 | [a0d3bcb2a0](https://linux-hardware.org/?probe=a0d3bcb2a0) | Apr 22, 2024 |
| HP            | Laptop 17-cn0xxx            | [739dd7b39e](https://linux-hardware.org/?probe=739dd7b39e) | Apr 21, 2024 |
| Lenovo        | ThinkPad E590 20NB0018MC    | [6b065854a6](https://linux-hardware.org/?probe=6b065854a6) | Apr 21, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [5b3e452e53](https://linux-hardware.org/?probe=5b3e452e53) | Apr 20, 2024 |
| HP            | Laptop 17-cn0xxx            | [75a61ca2af](https://linux-hardware.org/?probe=75a61ca2af) | Apr 20, 2024 |
| MSI           | Modern 15 B12M              | [b1786f8a58](https://linux-hardware.org/?probe=b1786f8a58) | Apr 17, 2024 |
| Acer          | Swift SFG14-41              | [6fc0fc2e0c](https://linux-hardware.org/?probe=6fc0fc2e0c) | Apr 16, 2024 |
| Acer          | Aspire E1-531               | [7d6a4b8c41](https://linux-hardware.org/?probe=7d6a4b8c41) | Apr 15, 2024 |
| Acer          | Aspire E1-531               | [d38bfe837e](https://linux-hardware.org/?probe=d38bfe837e) | Apr 15, 2024 |
| HP            | OMEN Laptop 15-en1001np ... | [a9e386b4a8](https://linux-hardware.org/?probe=a9e386b4a8) | Apr 15, 2024 |
| Dell          | Latitude E6420              | [713c9b9514](https://linux-hardware.org/?probe=713c9b9514) | Apr 13, 2024 |
| HP            | Pavilion 15                 | [ba8c469ac5](https://linux-hardware.org/?probe=ba8c469ac5) | Apr 13, 2024 |
| HP            | EliteBook 8470p             | [47a86e797f](https://linux-hardware.org/?probe=47a86e797f) | Apr 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S29D0W    | [7d55e2a84d](https://linux-hardware.org/?probe=7d55e2a84d) | Apr 11, 2024 |
| Dell          | Latitude E5430 non-vPro     | [e324b97ac4](https://linux-hardware.org/?probe=e324b97ac4) | Apr 10, 2024 |
| Dell          | Precision 3561              | [6bc6a2a9d9](https://linux-hardware.org/?probe=6bc6a2a9d9) | Apr 09, 2024 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [e54693d43a](https://linux-hardware.org/?probe=e54693d43a) | Apr 08, 2024 |
| Dell          | Latitude E5430 non-vPro     | [f5ade4bf16](https://linux-hardware.org/?probe=f5ade4bf16) | Apr 07, 2024 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [3446428450](https://linux-hardware.org/?probe=3446428450) | Apr 07, 2024 |
| Dell          | Latitude E5430 non-vPro     | [8fa8b6b410](https://linux-hardware.org/?probe=8fa8b6b410) | Apr 06, 2024 |
| Lenovo        | B5400 80B6QB0               | [a4b339c03e](https://linux-hardware.org/?probe=a4b339c03e) | Apr 05, 2024 |
| HP            | EliteBook 840 G4            | [fe41dd5efb](https://linux-hardware.org/?probe=fe41dd5efb) | Apr 05, 2024 |
| Dell          | Latitude 5430               | [2dcc20f886](https://linux-hardware.org/?probe=2dcc20f886) | Apr 05, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [77e3ddbb44](https://linux-hardware.org/?probe=77e3ddbb44) | Apr 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [effac14d53](https://linux-hardware.org/?probe=effac14d53) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [d7142dfd4d](https://linux-hardware.org/?probe=d7142dfd4d) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [971bc94dfd](https://linux-hardware.org/?probe=971bc94dfd) | Mar 31, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [18e0911b3a](https://linux-hardware.org/?probe=18e0911b3a) | Mar 31, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d15637af96](https://linux-hardware.org/?probe=d15637af96) | Mar 25, 2024 |
| Lenovo        | ThinkPad X270 20HMS40900    | [573dd9915e](https://linux-hardware.org/?probe=573dd9915e) | Mar 24, 2024 |
| Panasonic     | CF-NX2LDHTS                 | [0b94846d30](https://linux-hardware.org/?probe=0b94846d30) | Mar 23, 2024 |
| Panasonic     | CF-NX2LDHTS                 | [49f6028a20](https://linux-hardware.org/?probe=49f6028a20) | Mar 23, 2024 |
| ASUSTek       | N56JN                       | [2bc4f9eba7](https://linux-hardware.org/?probe=2bc4f9eba7) | Mar 22, 2024 |
| Acer          | Aspire 5830TG               | [5190665de2](https://linux-hardware.org/?probe=5190665de2) | Mar 22, 2024 |
| Dell          | Latitude E6230              | [78a94f507a](https://linux-hardware.org/?probe=78a94f507a) | Mar 21, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [c4aa0ba90f](https://linux-hardware.org/?probe=c4aa0ba90f) | Mar 21, 2024 |
| Google        | Astronaut                   | [b2e117a773](https://linux-hardware.org/?probe=b2e117a773) | Mar 21, 2024 |
| HP            | Laptop 17-cn0xxx            | [105dbc74d2](https://linux-hardware.org/?probe=105dbc74d2) | Mar 18, 2024 |
| HP            | EliteBook 8470p             | [f28ca01e47](https://linux-hardware.org/?probe=f28ca01e47) | Mar 18, 2024 |
| Dell          | Latitude E6230              | [67bc6aae53](https://linux-hardware.org/?probe=67bc6aae53) | Mar 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [030fe7cb7a](https://linux-hardware.org/?probe=030fe7cb7a) | Mar 17, 2024 |
| Lenovo        | ThinkPad X270 20HMS40900    | [b7babbc9ca](https://linux-hardware.org/?probe=b7babbc9ca) | Mar 17, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [fb730fc344](https://linux-hardware.org/?probe=fb730fc344) | Mar 16, 2024 |
| Dell          | Latitude E6540              | [bbc5613ffc](https://linux-hardware.org/?probe=bbc5613ffc) | Mar 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [5bad97c6ec](https://linux-hardware.org/?probe=5bad97c6ec) | Mar 15, 2024 |
| UMAX          | 13Wr                        | [88c71ba263](https://linux-hardware.org/?probe=88c71ba263) | Mar 14, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [b33165a798](https://linux-hardware.org/?probe=b33165a798) | Mar 13, 2024 |
| HP            | EliteBook 1050 G1           | [a0431bb3bc](https://linux-hardware.org/?probe=a0431bb3bc) | Mar 13, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | [e680816d8a](https://linux-hardware.org/?probe=e680816d8a) | Mar 13, 2024 |
| Lenovo        | B71-80 80RJ                 | [7aa5c86b22](https://linux-hardware.org/?probe=7aa5c86b22) | Mar 12, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [77f28d5d35](https://linux-hardware.org/?probe=77f28d5d35) | Mar 12, 2024 |
| Google        | Cyan                        | [0cc944571a](https://linux-hardware.org/?probe=0cc944571a) | Mar 12, 2024 |
| HP            | Pavilion 15                 | [b2596c60dd](https://linux-hardware.org/?probe=b2596c60dd) | Mar 10, 2024 |
| Acer          | Aspire 5830TG               | [e09799794f](https://linux-hardware.org/?probe=e09799794f) | Mar 10, 2024 |
| ASUSTek       | ROG Strix G814JV_G814JV     | [10e971349c](https://linux-hardware.org/?probe=10e971349c) | Mar 08, 2024 |
| Dell          | Inspiron 15-5578            | [1989ba3a95](https://linux-hardware.org/?probe=1989ba3a95) | Mar 07, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [6f0e97edef](https://linux-hardware.org/?probe=6f0e97edef) | Mar 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [d8a1f42773](https://linux-hardware.org/?probe=d8a1f42773) | Mar 07, 2024 |
| HP            | ZBook Studio 15.6 Inch G... | [ecbd50f245](https://linux-hardware.org/?probe=ecbd50f245) | Mar 07, 2024 |
| Dell          | Latitude 5500               | [8c248216ac](https://linux-hardware.org/?probe=8c248216ac) | Mar 07, 2024 |
| ASUSTek       | N55SF                       | [9579229ce6](https://linux-hardware.org/?probe=9579229ce6) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S37W04    | [1278612ad9](https://linux-hardware.org/?probe=1278612ad9) | Mar 05, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [746fafeef2](https://linux-hardware.org/?probe=746fafeef2) | Mar 05, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H50... | [6b1f0885d9](https://linux-hardware.org/?probe=6b1f0885d9) | Mar 04, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [230157b598](https://linux-hardware.org/?probe=230157b598) | Mar 03, 2024 |
| ASUSTek       | Zenbook UX425QA_UM425QA     | [21975edff4](https://linux-hardware.org/?probe=21975edff4) | Mar 03, 2024 |
| Acer          | Aspire V3-572P              | [bfdf32c8e1](https://linux-hardware.org/?probe=bfdf32c8e1) | Mar 02, 2024 |
| ASUSTek       | K53SV                       | [1043b72dee](https://linux-hardware.org/?probe=1043b72dee) | Feb 29, 2024 |
| Dell          | Latitude 5431               | [03544a6699](https://linux-hardware.org/?probe=03544a6699) | Feb 23, 2024 |
| Valve         | Galileo                     | [f4c12237df](https://linux-hardware.org/?probe=f4c12237df) | Feb 22, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [044616ab5e](https://linux-hardware.org/?probe=044616ab5e) | Feb 21, 2024 |
| HP            | 255 G8 Notebook PC          | [3185694845](https://linux-hardware.org/?probe=3185694845) | Feb 21, 2024 |
| HP            | EliteBook 840 G6            | [eacc26c850](https://linux-hardware.org/?probe=eacc26c850) | Feb 20, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [a6ee663daa](https://linux-hardware.org/?probe=a6ee663daa) | Feb 18, 2024 |
| HP            | Compaq 610                  | [e32de41ce7](https://linux-hardware.org/?probe=e32de41ce7) | Feb 18, 2024 |
| Dell          | Latitude E6540              | [b3d3fd2a6e](https://linux-hardware.org/?probe=b3d3fd2a6e) | Feb 18, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [2399729951](https://linux-hardware.org/?probe=2399729951) | Feb 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [176496db32](https://linux-hardware.org/?probe=176496db32) | Feb 16, 2024 |
| HP            | EliteBook 850 G4            | [d380866ad3](https://linux-hardware.org/?probe=d380866ad3) | Feb 15, 2024 |
| Dell          | Latitude 7490               | [65ce0de8b5](https://linux-hardware.org/?probe=65ce0de8b5) | Feb 15, 2024 |
| HP            | Laptop 17-ca1xxx            | [9c0e3d1a1a](https://linux-hardware.org/?probe=9c0e3d1a1a) | Feb 14, 2024 |
| HP            | EliteBook 8470p             | [e0dbe8fe33](https://linux-hardware.org/?probe=e0dbe8fe33) | Feb 13, 2024 |
| Lenovo        | ThinkPad Edge E535 3260E... | [96f9c6c61c](https://linux-hardware.org/?probe=96f9c6c61c) | Feb 13, 2024 |
| Valve         | Jupiter                     | [71c7cf074b](https://linux-hardware.org/?probe=71c7cf074b) | Feb 12, 2024 |
| Dell          | Latitude D620               | [933222fc00](https://linux-hardware.org/?probe=933222fc00) | Feb 10, 2024 |
| Acer          | Aspire A515-41G             | [11ede91daf](https://linux-hardware.org/?probe=11ede91daf) | Feb 09, 2024 |
| TUXEDO        | InfinityBook S Gen8         | [8dddfa59a5](https://linux-hardware.org/?probe=8dddfa59a5) | Feb 09, 2024 |
| Dell          | Latitude 5411               | [2872c72934](https://linux-hardware.org/?probe=2872c72934) | Feb 06, 2024 |
| Lenovo        | Y50-70 20378                | [67951a8bdd](https://linux-hardware.org/?probe=67951a8bdd) | Feb 03, 2024 |
| Lenovo        | ThinkPad X230 2325SW9       | [e8681e8668](https://linux-hardware.org/?probe=e8681e8668) | Feb 03, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a64852fe4a](https://linux-hardware.org/?probe=a64852fe4a) | Feb 02, 2024 |
| Dell          | Inspiron 7577               | [0155afe6f3](https://linux-hardware.org/?probe=0155afe6f3) | Feb 02, 2024 |
| Dell          | Inspiron 7566               | [e8f24dd8cf](https://linux-hardware.org/?probe=e8f24dd8cf) | Jan 31, 2024 |
| Acer          | Nitro AN515-42              | [9e4c4acd0d](https://linux-hardware.org/?probe=9e4c4acd0d) | Jan 30, 2024 |
| ASUSTek       | UX550VD                     | [3b742650db](https://linux-hardware.org/?probe=3b742650db) | Jan 29, 2024 |
| UMAX          | VisionBook 14Wr Plus        | [148a4486f3](https://linux-hardware.org/?probe=148a4486f3) | Jan 29, 2024 |
| HP            | ZBook Power 15.6 inch G1... | [6304caec55](https://linux-hardware.org/?probe=6304caec55) | Jan 29, 2024 |
| Samsung       | 300V3A                      | [53e3665790](https://linux-hardware.org/?probe=53e3665790) | Jan 27, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4b4af4b9b4](https://linux-hardware.org/?probe=4b4af4b9b4) | Jan 26, 2024 |
| Dell          | XPS 9320                    | [ed6a1f51f5](https://linux-hardware.org/?probe=ed6a1f51f5) | Jan 26, 2024 |
| HP            | 2000                        | [f1e38c4df2](https://linux-hardware.org/?probe=f1e38c4df2) | Jan 25, 2024 |
| HP            | EliteBook 840 G2            | [9ad67b6f8d](https://linux-hardware.org/?probe=9ad67b6f8d) | Jan 23, 2024 |
| HP            | EliteBook 840 G2            | [04f0c2393d](https://linux-hardware.org/?probe=04f0c2393d) | Jan 23, 2024 |
| HP            | Laptop 15-db0xxx            | [79cf6e6101](https://linux-hardware.org/?probe=79cf6e6101) | Jan 22, 2024 |
| Dell          | Latitude 5440               | [4ac53b51b3](https://linux-hardware.org/?probe=4ac53b51b3) | Jan 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5a444c3b35](https://linux-hardware.org/?probe=5a444c3b35) | Jan 22, 2024 |
| Lenovo        | G550 20023                  | [577e991c77](https://linux-hardware.org/?probe=577e991c77) | Jan 21, 2024 |
| Dell          | Latitude E6420              | [b0d535026a](https://linux-hardware.org/?probe=b0d535026a) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| HP            | 530 Notebook PC(GU324AA#... | [785d324acb](https://linux-hardware.org/?probe=785d324acb) | Jan 18, 2024 |
| Dell          | Latitude 5591               | [b91323a39b](https://linux-hardware.org/?probe=b91323a39b) | Jan 17, 2024 |
| Acer          | Swift SFX14-41G             | [e3c95c6c18](https://linux-hardware.org/?probe=e3c95c6c18) | Jan 17, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8e6afbe7c9](https://linux-hardware.org/?probe=8e6afbe7c9) | Jan 16, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [09e866e5e9](https://linux-hardware.org/?probe=09e866e5e9) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | [60e35c48cf](https://linux-hardware.org/?probe=60e35c48cf) | Jan 14, 2024 |
| HP            | EliteBook 735 G5            | [53b86640e5](https://linux-hardware.org/?probe=53b86640e5) | Jan 12, 2024 |
| Apple         | MacBookPro9,2               | [696f5dd9e3](https://linux-hardware.org/?probe=696f5dd9e3) | Jan 12, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [2714705590](https://linux-hardware.org/?probe=2714705590) | Jan 12, 2024 |
| HP            | EliteBook 735 G5            | [c0282ee6a5](https://linux-hardware.org/?probe=c0282ee6a5) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | [0ca9774d55](https://linux-hardware.org/?probe=0ca9774d55) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | [a2ee63de30](https://linux-hardware.org/?probe=a2ee63de30) | Jan 11, 2024 |
| Acer          | Predator PH16-71            | [a2cae97378](https://linux-hardware.org/?probe=a2cae97378) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| Dell          | Latitude 5440               | [61e99860d0](https://linux-hardware.org/?probe=61e99860d0) | Jan 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [10676b8682](https://linux-hardware.org/?probe=10676b8682) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| HP            | Compaq 610                  | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U938               | [b3dbded413](https://linux-hardware.org/?probe=b3dbded413) | Jan 07, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6eaa268ce1](https://linux-hardware.org/?probe=6eaa268ce1) | Jan 07, 2024 |
| HP            | 250 G3                      | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Acer          | Nitro AN515-44              | [4116ba8fb4](https://linux-hardware.org/?probe=4116ba8fb4) | Jan 05, 2024 |
| Acer          | Extensa 5230                | [2c36e88ef4](https://linux-hardware.org/?probe=2c36e88ef4) | Jan 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [5e72d133f1](https://linux-hardware.org/?probe=5e72d133f1) | Jan 02, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | [5983998e46](https://linux-hardware.org/?probe=5983998e46) | Jan 02, 2024 |
| Apple         | MacBookPro9,2               | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| HP            | Compaq 610                  | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Dell          | XPS 13 9380                 | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| HP            | 2000                        | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Dell          | Latitude 5591               | [99b2702a06](https://linux-hardware.org/?probe=99b2702a06) | Dec 27, 2023 |
| Valve         | Jupiter                     | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [f91e53f3e0](https://linux-hardware.org/?probe=f91e53f3e0) | Dec 26, 2023 |
| HP            | 2000                        | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | ProBook 4540s               | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS25R00    | [91820391fd](https://linux-hardware.org/?probe=91820391fd) | Dec 23, 2023 |
| ASUSTek       | X555LA                      | [2f52e3fdc9](https://linux-hardware.org/?probe=2f52e3fdc9) | Dec 22, 2023 |
| HP            | ProBook 4540s               | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Dell          | Latitude 7490               | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| Dell          | Precision M2800             | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| Sony          | VGN-FW455J                  | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Dell          | Latitude 7490               | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| ASUSTek       | X550CA                      | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| HP            | 2000                        | [40929a84a0](https://linux-hardware.org/?probe=40929a84a0) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | [e55319a16a](https://linux-hardware.org/?probe=e55319a16a) | Dec 09, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| Dell          | Latitude 5591               | [1961ebb904](https://linux-hardware.org/?probe=1961ebb904) | Dec 07, 2023 |
| Dell          | Latitude 5591               | [b9f6d020e8](https://linux-hardware.org/?probe=b9f6d020e8) | Dec 07, 2023 |
| Dell          | Precision 3550              | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| Valve         | Jupiter                     | [93bf1ceeec](https://linux-hardware.org/?probe=93bf1ceeec) | Dec 05, 2023 |
| Sony          | VPCS13S9E                   | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Dynabook      | PORTEGE X50-G               | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| Apple         | MacBookPro9,2               | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | [c4a56c14f5](https://linux-hardware.org/?probe=c4a56c14f5) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| UMAX          | VisionBook-N12R             | [e77e8d6999](https://linux-hardware.org/?probe=e77e8d6999) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Dell          | Latitude 5511               | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| HP            | EliteBook 840 G5            | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| Lenovo        | ThinkPad E450 20DC008DMC    | [56fc21d585](https://linux-hardware.org/?probe=56fc21d585) | Nov 23, 2023 |
| ASUSTek       | K54LY                       | [4ebc53e69c](https://linux-hardware.org/?probe=4ebc53e69c) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [748ea9f21b](https://linux-hardware.org/?probe=748ea9f21b) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| UMAX          | VisionBook-N12R             | [89e41854be](https://linux-hardware.org/?probe=89e41854be) | Nov 19, 2023 |
| Lenovo        | ThinkPad X201 3680DE3       | [38290dc3e7](https://linux-hardware.org/?probe=38290dc3e7) | Nov 17, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [ca7747546b](https://linux-hardware.org/?probe=ca7747546b) | Nov 17, 2023 |
| Dell          | Inspiron 7577               | [62e08b2285](https://linux-hardware.org/?probe=62e08b2285) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [2204427cc1](https://linux-hardware.org/?probe=2204427cc1) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [001dd47e7d](https://linux-hardware.org/?probe=001dd47e7d) | Nov 12, 2023 |
| Acer          | Aspire E1-531               | [41e1f90785](https://linux-hardware.org/?probe=41e1f90785) | Nov 11, 2023 |
| Sony          | VPCEB4J0E                   | [c1e2a1a0da](https://linux-hardware.org/?probe=c1e2a1a0da) | Nov 11, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | G505 20240                  | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Dell          | Latitude E7440              | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | [ae8881b2b2](https://linux-hardware.org/?probe=ae8881b2b2) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | [a3d91609e9](https://linux-hardware.org/?probe=a3d91609e9) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| HP            | EliteBook 840 G5            | [a42017f05d](https://linux-hardware.org/?probe=a42017f05d) | Nov 02, 2023 |
| Dell          | Latitude 5480               | [567a2774f8](https://linux-hardware.org/?probe=567a2774f8) | Nov 01, 2023 |
| Dell          | Latitude E5470              | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [15573e8d54](https://linux-hardware.org/?probe=15573e8d54) | Oct 30, 2023 |
| HP            | 250 G3                      | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| ASUSTek       | X550CL                      | [a95ddd6798](https://linux-hardware.org/?probe=a95ddd6798) | Oct 26, 2023 |
| HP            | 250 G3                      | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [819d596b2e](https://linux-hardware.org/?probe=819d596b2e) | Oct 24, 2023 |
| HP            | EliteBook 840 G4            | [a6d732c859](https://linux-hardware.org/?probe=a6d732c859) | Oct 24, 2023 |
| Lenovo        | Unknown                     | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | [8f65236e52](https://linux-hardware.org/?probe=8f65236e52) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | [a523689a60](https://linux-hardware.org/?probe=a523689a60) | Oct 21, 2023 |
| Acer          | Swift SF314-42              | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Acer          | Aspire R3-131T              | [f8d2d274e1](https://linux-hardware.org/?probe=f8d2d274e1) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| Dell          | XPS 13 9310                 | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b2250f3c59](https://linux-hardware.org/?probe=b2250f3c59) | Oct 14, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| UMAX          | N14R                        | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Dell          | Latitude 5431               | [a85fc8f829](https://linux-hardware.org/?probe=a85fc8f829) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| HP            | Pavilion Notebook           | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Sony          | VPCEB4J0E                   | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Precision 7710              | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Dell          | Inspiron 5515               | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| Acer          | Swift SF14-71T              | [10b657bd75](https://linux-hardware.org/?probe=10b657bd75) | Sep 25, 2023 |
| Dell          | Precision 7720              | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [336d5fe8c8](https://linux-hardware.org/?probe=336d5fe8c8) | Sep 25, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [4bb581fb16](https://linux-hardware.org/?probe=4bb581fb16) | Sep 19, 2023 |
| Acer          | Aspire ES1-420              | [db308e1798](https://linux-hardware.org/?probe=db308e1798) | Sep 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Dell          | G3 3500                     | [293bbfe2d6](https://linux-hardware.org/?probe=293bbfe2d6) | Sep 12, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| HP            | 240 G8 Notebook PC          | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| UMAX          | 13Wr                        | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| HP            | Unknown                     | [3809d7ad85](https://linux-hardware.org/?probe=3809d7ad85) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | K53E                        | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| Acer          | Aspire E1-532               | [037143c4fd](https://linux-hardware.org/?probe=037143c4fd) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Google        | Robo                        | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Valve         | Jupiter                     | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| Valve         | Jupiter                     | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 160       | 7.5%    |
| Ubuntu 22.04                 | 110       | 5.15%   |
| Ubuntu 18.04                 | 86        | 4.03%   |
| OpenMandriva 4.2             | 75        | 3.51%   |
| Arch Rolling                 | 63        | 2.95%   |
| OpenMandriva 4.50            | 58        | 2.72%   |
| Ubuntu 24.04                 | 50        | 2.34%   |
| Pop!_OS 22.04                | 44        | 2.06%   |
| OpenMandriva 4.3             | 43        | 2.01%   |
| Debian 12                    | 35        | 1.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 30        | 1.41%   |
| Ubuntu 21.10                 | 29        | 1.36%   |
| Fedora 38                    | 28        | 1.31%   |
| Zorin 17                     | 24        | 1.12%   |
| Zorin 16                     | 23        | 1.08%   |
| Ubuntu 19.10                 | 22        | 1.03%   |
| OpenMandriva 24.12           | 22        | 1.03%   |
| Fedora 34                    | 22        | 1.03%   |
| Zorin 15                     | 21        | 0.98%   |
| Ubuntu 20.10                 | 21        | 0.98%   |
| OpenMandriva 23.01           | 21        | 0.98%   |
| Fedora 39                    | 21        | 0.98%   |
| Linux Mint 21.1              | 20        | 0.94%   |
| Debian 11                    | 20        | 0.94%   |
| Ubuntu 21.04                 | 18        | 0.84%   |
| Linux Mint 20                | 18        | 0.84%   |
| OpenMandriva 23.08           | 17        | 0.8%    |
| Manjaro                      | 17        | 0.8%    |
| Linux Mint 21.2              | 17        | 0.8%    |
| Fedora 40                    | 17        | 0.8%    |
| Arch                         | 17        | 0.8%    |
| Linux Mint 20.2              | 16        | 0.75%   |
| Linux Mint 19.3              | 16        | 0.75%   |
| OpenMandriva 5.0             | 15        | 0.7%    |
| OpenMandriva 23.03           | 15        | 0.7%    |
| Linux Mint 22.1              | 15        | 0.7%    |
| Linux Mint 20.3              | 15        | 0.7%    |
| Fedora 41                    | 15        | 0.7%    |
| ArcoLinux Rolling            | 15        | 0.7%    |
| Linux Mint 20.1              | 14        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 522       | 26.15%  |
| OpenMandriva     | 311       | 15.58%  |
| Fedora           | 199       | 9.97%   |
| Linux Mint       | 159       | 7.97%   |
| Debian           | 82        | 4.11%   |
| Arch             | 80        | 4.01%   |
| Zorin            | 73        | 3.66%   |
| Pop!_OS          | 62        | 3.11%   |
| Kubuntu          | 54        | 2.71%   |
| Manjaro          | 46        | 2.3%    |
| Xubuntu          | 44        | 2.2%    |
| Gentoo           | 44        | 2.2%    |
| openSUSE         | 38        | 1.9%    |
| ROSA             | 22        | 1.1%    |
| KDE neon         | 22        | 1.1%    |
| Kali             | 20        | 1%      |
| Lubuntu          | 17        | 0.85%   |
| SteamOS          | 16        | 0.8%    |
| ArcoLinux        | 16        | 0.8%    |
| NixOS            | 14        | 0.7%    |
| EndeavourOS      | 12        | 0.6%    |
| Elementary       | 12        | 0.6%    |
| Ubuntu MATE      | 8         | 0.4%    |
| RHEL             | 8         | 0.4%    |
| LMDE             | 8         | 0.4%    |
| Endless          | 8         | 0.4%    |
| Parrot           | 7         | 0.35%   |
| Nobara           | 7         | 0.35%   |
| Ubuntu Unity     | 6         | 0.3%    |
| Bazzite          | 6         | 0.3%    |
| Ubuntu Budgie    | 5         | 0.25%   |
| TUXEDO OS        | 5         | 0.25%   |
| MX               | 5         | 0.25%   |
| Garuda Linux     | 5         | 0.25%   |
| Void Linux       | 4         | 0.2%    |
| Rocky Linux      | 4         | 0.2%    |
| BlackPanther     | 4         | 0.2%    |
| Artix            | 4         | 0.2%    |
| Solus            | 3         | 0.15%   |
| org.kde.Platform | 3         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 74        | 3.21%   |
| 5.14.7-desktop-1omv4050  | 55        | 2.39%   |
| 5.16.7-desktop-1omv4003  | 42        | 1.82%   |
| 6.14.2-desktop-3omv2590  | 38        | 1.65%   |
| 5.4.0-42-generic         | 23        | 1%      |
| 6.1.1-desktop-1omv2290   | 20        | 0.87%   |
| 6.12.1-desktop-1omv2490  | 17        | 0.74%   |
| 6.6.2-desktop-1omv2390   | 15        | 0.65%   |
| 5.4.0-52-generic         | 15        | 0.65%   |
| 5.15.0-46-generic        | 15        | 0.65%   |
| 6.4.11-desktop-1omv2390  | 14        | 0.61%   |
| 6.2.6-desktop-1omv2390   | 14        | 0.61%   |
| 5.4.0-26-generic         | 13        | 0.56%   |
| 6.8.0-52-generic         | 12        | 0.52%   |
| 5.4.0-58-generic         | 12        | 0.52%   |
| 5.15.0-56-generic        | 12        | 0.52%   |
| 6.2.0-26-generic         | 11        | 0.48%   |
| 5.3.0-40-generic         | 11        | 0.48%   |
| 5.15.0-58-generic        | 11        | 0.48%   |
| 6.9.3-76060903-generic   | 9         | 0.39%   |
| 6.8.0-51-generic         | 9         | 0.39%   |
| 6.8.0-41-generic         | 9         | 0.39%   |
| 5.4.0-65-generic         | 9         | 0.39%   |
| 5.15.0-48-generic        | 9         | 0.39%   |
| 5.0.0-37-generic         | 9         | 0.39%   |
| 6.8.0-31-generic         | 8         | 0.35%   |
| 6.2.0-39-generic         | 8         | 0.35%   |
| 6.10.0-desktop-1omv2490  | 8         | 0.35%   |
| 5.8.0-59-generic         | 8         | 0.35%   |
| 5.4.0-48-generic         | 8         | 0.35%   |
| 5.4.0-40-generic         | 8         | 0.35%   |
| 5.15.0-78-generic        | 8         | 0.35%   |
| 5.15.0-52-generic        | 8         | 0.35%   |
| 5.13.0-21-generic        | 8         | 0.35%   |
| 6.8.0-63-generic         | 7         | 0.3%    |
| 6.8.0-47-generic         | 7         | 0.3%    |
| 6.8.0-45-generic         | 7         | 0.3%    |
| 6.14.0-33-generic        | 7         | 0.3%    |
| 5.4.0-91-generic         | 7         | 0.3%    |
| 5.19.0-32-generic        | 7         | 0.3%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 200       | 9.16%   |
| 5.15.0  | 136       | 6.23%   |
| 6.8.0   | 101       | 4.62%   |
| 5.10.14 | 74        | 3.39%   |
| 5.3.0   | 68        | 3.11%   |
| 5.13.0  | 67        | 3.07%   |
| 5.11.0  | 63        | 2.88%   |
| 6.5.0   | 62        | 2.84%   |
| 4.15.0  | 60        | 2.75%   |
| 5.8.0   | 58        | 2.66%   |
| 5.14.7  | 56        | 2.56%   |
| 6.1.0   | 45        | 2.06%   |
| 5.0.0   | 44        | 2.01%   |
| 6.2.0   | 43        | 1.97%   |
| 5.16.7  | 43        | 1.97%   |
| 6.14.2  | 41        | 1.88%   |
| 6.14.0  | 39        | 1.79%   |
| 5.19.0  | 39        | 1.79%   |
| 5.10.0  | 29        | 1.33%   |
| 6.11.0  | 28        | 1.28%   |
| 4.18.0  | 26        | 1.19%   |
| 6.1.1   | 23        | 1.05%   |
| 6.2.6   | 20        | 0.92%   |
| 6.12.1  | 19        | 0.87%   |
| 6.6.2   | 17        | 0.78%   |
| 6.4.11  | 14        | 0.64%   |
| 6.5.6   | 12        | 0.55%   |
| 6.9.3   | 10        | 0.46%   |
| 6.10.0  | 9         | 0.41%   |
| 5.14.0  | 8         | 0.37%   |
| 4.19.0  | 8         | 0.37%   |
| 6.7.9   | 7         | 0.32%   |
| 6.17.0  | 7         | 0.32%   |
| 6.16.3  | 7         | 0.32%   |
| 6.12.6  | 7         | 0.32%   |
| 6.12.10 | 7         | 0.32%   |
| 6.11.2  | 7         | 0.32%   |
| 6.8.8   | 6         | 0.27%   |
| 6.7.6   | 6         | 0.27%   |
| 6.2.9   | 6         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 216       | 10%     |
| 5.15    | 169       | 7.82%   |
| 5.10    | 131       | 6.06%   |
| 6.8     | 124       | 5.74%   |
| 6.1     | 100       | 4.63%   |
| 6.14    | 91        | 4.21%   |
| 6.5     | 88        | 4.07%   |
| 6.2     | 85        | 3.93%   |
| 5.11    | 84        | 3.89%   |
| 5.13    | 80        | 3.7%    |
| 5.14    | 78        | 3.61%   |
| 5.3     | 76        | 3.52%   |
| 6.12    | 74        | 3.42%   |
| 5.8     | 74        | 3.42%   |
| 4.15    | 62        | 2.87%   |
| 5.16    | 60        | 2.78%   |
| 6.11    | 55        | 2.55%   |
| 5.19    | 54        | 2.5%    |
| 6.6     | 50        | 2.31%   |
| 5.0     | 47        | 2.17%   |
| 6.4     | 34        | 1.57%   |
| 4.18    | 29        | 1.34%   |
| 6.9     | 27        | 1.25%   |
| 6.10    | 27        | 1.25%   |
| 6.7     | 26        | 1.2%    |
| 6.17    | 23        | 1.06%   |
| 6.0     | 23        | 1.06%   |
| 5.17    | 20        | 0.93%   |
| 6.16    | 16        | 0.74%   |
| 5.9     | 15        | 0.69%   |
| 5.6     | 15        | 0.69%   |
| 5.18    | 15        | 0.69%   |
| 6.13    | 13        | 0.6%    |
| 6.15    | 12        | 0.56%   |
| 4.19    | 12        | 0.56%   |
| 6.3     | 9         | 0.42%   |
| 5.12    | 7         | 0.32%   |
| 4.9     | 7         | 0.32%   |
| 5.7     | 6         | 0.28%   |
| 5.5     | 6         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1896      | 97.53%  |
| i686    | 47        | 2.42%   |
| aarch64 | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 803       | 39.6%   |
| KDE5            | 424       | 20.91%  |
| Unknown         | 175       | 8.63%   |
| XFCE            | 151       | 7.45%   |
| KDE6            | 131       | 6.46%   |
| X-Cinnamon      | 104       | 5.13%   |
| MATE            | 48        | 2.37%   |
| LXQt            | 33        | 1.63%   |
| KDE             | 31        | 1.53%   |
| Cinnamon        | 21        | 1.04%   |
| Hyprland        | 15        | 0.74%   |
| Pantheon        | 12        | 0.59%   |
| LXDE            | 9         | 0.44%   |
| KDE4            | 9         | 0.44%   |
| i3              | 8         | 0.39%   |
| Budgie          | 8         | 0.39%   |
| Unity           | 7         | 0.35%   |
| sway            | 7         | 0.35%   |
| GNOME Flashback | 7         | 0.35%   |
| awesome         | 6         | 0.3%    |
| openbox         | 3         | 0.15%   |
| qtile           | 2         | 0.1%    |
| COSMIC          | 2         | 0.1%    |
| XSession        | 1         | 0.05%   |
| xinitrc         | 1         | 0.05%   |
| xinit-compat    | 1         | 0.05%   |
| sway:wlroots    | 1         | 0.05%   |
| niri            | 1         | 0.05%   |
| icewm           | 1         | 0.05%   |
| GNUstep         | 1         | 0.05%   |
| Enlightenment   | 1         | 0.05%   |
| DWM             | 1         | 0.05%   |
| Deepin          | 1         | 0.05%   |
| custom          | 1         | 0.05%   |
| bspwm           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1306      | 64.98%  |
| Wayland | 576       | 28.66%  |
| Unknown | 97        | 4.83%   |
| Tty     | 31        | 1.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 781       | 38.61%  |
| SDDM           | 525       | 25.95%  |
| GDM3           | 267       | 13.2%   |
| LightDM        | 203       | 10.03%  |
| GDM            | 182       | 9%      |
| TDM            | 39        | 1.93%   |
| SLiM           | 5         | 0.25%   |
| KDM            | 5         | 0.25%   |
| XDM            | 4         | 0.2%    |
| LY-DM          | 3         | 0.15%   |
| LXDM           | 3         | 0.15%   |
| GREETD         | 3         | 0.15%   |
| SLIMSKI        | 1         | 0.05%   |
| Ly             | 1         | 0.05%   |
| COSMIC-GREETER | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| cs_CZ   | 1011      | 50.91%  |
| en_US   | 685       | 34.49%  |
| Unknown | 128       | 6.45%   |
| en_GB   | 47        | 2.37%   |
| C       | 46        | 2.32%   |
| ru_RU   | 23        | 1.16%   |
| sk_SK   | 6         | 0.3%    |
| pl_PL   | 6         | 0.3%    |
| POSIX   | 5         | 0.25%   |
| uk_UA   | 4         | 0.2%    |
| de_DE   | 4         | 0.2%    |
| C.UTF8  | 3         | 0.15%   |
| it_IT   | 2         | 0.1%    |
| fr_FR   | 2         | 0.1%    |
| vi_VN   | 1         | 0.05%   |
| tr_TR   | 1         | 0.05%   |
| ro_RO   | 1         | 0.05%   |
| pt_PT   | 1         | 0.05%   |
| pt_BR   | 1         | 0.05%   |
| hu_HU   | 1         | 0.05%   |
| es_ES   | 1         | 0.05%   |
| en_NG   | 1         | 0.05%   |
| en_DK   | 1         | 0.05%   |
| en_CA   | 1         | 0.05%   |
| en_150  | 1         | 0.05%   |
| el_GR   | 1         | 0.05%   |
| de_CH   | 1         | 0.05%   |
| bg_BG   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1022      | 51.13%  |
| BIOS | 977       | 48.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1215      | 60.72%  |
| Overlay  | 277       | 13.84%  |
| Btrfs    | 274       | 13.69%  |
| Tmpfs    | 125       | 6.25%   |
| Xfs      | 39        | 1.95%   |
| Unknown  | 33        | 1.65%   |
| Zfs      | 14        | 0.7%    |
| Bcachefs | 8         | 0.4%    |
| F2fs     | 5         | 0.25%   |
| Ext3     | 4         | 0.2%    |
| Ext2     | 2         | 0.1%    |
| Aufs     | 2         | 0.1%    |
| Rootfs   | 1         | 0.05%   |
| Reiserfs | 1         | 0.05%   |
| Jfs      | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 928       | 46.54%  |
| Unknown | 785       | 39.37%  |
| MBR     | 281       | 14.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1776      | 89.88%  |
| Yes       | 200       | 10.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1364      | 68.68%  |
| Yes       | 622       | 31.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 537       | 27.62%  |
| Hewlett-Packard                | 350       | 18%     |
| ASUSTek Computer               | 341       | 17.54%  |
| Dell                           | 283       | 14.56%  |
| Acer                           | 176       | 9.05%   |
| UMAX                           | 29        | 1.49%   |
| MSI                            | 28        | 1.44%   |
| Fujitsu                        | 23        | 1.18%   |
| Toshiba                        | 22        | 1.13%   |
| Sony                           | 21        | 1.08%   |
| Valve                          | 16        | 0.82%   |
| Apple                          | 14        | 0.72%   |
| TUXEDO                         | 10        | 0.51%   |
| Unknown                        | 10        | 0.51%   |
| Samsung Electronics            | 8         | 0.41%   |
| Google                         | 8         | 0.41%   |
| HUAWEI                         | 7         | 0.36%   |
| Notebook                       | 6         | 0.31%   |
| Fujitsu Siemens                | 5         | 0.26%   |
| Timi                           | 4         | 0.21%   |
| Packard Bell                   | 4         | 0.21%   |
| Framework                      | 4         | 0.21%   |
| Alienware                      | 3         | 0.15%   |
| Prestigio                      | 2         | 0.1%    |
| Panasonic                      | 2         | 0.1%    |
| Intel                          | 2         | 0.1%    |
| Insyde                         | 2         | 0.1%    |
| IBM                            | 2         | 0.1%    |
| Dynabook                       | 2         | 0.1%    |
| DATABOX                        | 2         | 0.1%    |
| Chuwi                          | 2         | 0.1%    |
| win element                    | 1         | 0.05%   |
| Star Labs                      | 1         | 0.05%   |
| Standard                       | 1         | 0.05%   |
| SmbiosType1_SystemManufacturer | 1         | 0.05%   |
| SLIMBOOK                       | 1         | 0.05%   |
| Schenker                       | 1         | 0.05%   |
| Purism                         | 1         | 0.05%   |
| Minix                          | 1         | 0.05%   |
| Medion                         | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| ASUS UX31E                            | 130       | 6.69%   |
| Unknown                               | 16        | 0.82%   |
| Valve Jupiter                         | 13        | 0.67%   |
| Lenovo IdeaPad S145-15AST 81N3        | 12        | 0.62%   |
| HP EliteBook 840 G3                   | 10        | 0.51%   |
| Dell Latitude E6420                   | 9         | 0.46%   |
| HP ProBook 455 G7                     | 7         | 0.36%   |
| HP EliteBook 840 G6                   | 7         | 0.36%   |
| Dell Latitude E6400                   | 7         | 0.36%   |
| Dell Latitude 7490                    | 7         | 0.36%   |
| HP ProBook 4540s                      | 6         | 0.31%   |
| HP EliteBook 855 G8 Notebook PC       | 6         | 0.31%   |
| HP EliteBook 845 G8 Notebook PC       | 6         | 0.31%   |
| Dell XPS 15 7590                      | 6         | 0.31%   |
| Lenovo ThinkPad E14 20RA001LMC        | 5         | 0.26%   |
| HP ProBook 4530s                      | 5         | 0.26%   |
| HP ProBook 450 G5                     | 5         | 0.26%   |
| HP Pavilion dv7                       | 5         | 0.26%   |
| HP Notebook                           | 5         | 0.26%   |
| HP Laptop 15-bw0xx                    | 5         | 0.26%   |
| HP 250 G6 Notebook PC                 | 5         | 0.26%   |
| Dell XPS 15 9560                      | 5         | 0.26%   |
| Dell Latitude E7440                   | 5         | 0.26%   |
| Dell Latitude 5480                    | 5         | 0.26%   |
| Dell Latitude 5401                    | 5         | 0.26%   |
| Lenovo Z50-75 80EC                    | 4         | 0.21%   |
| Lenovo ThinkPad T14 Gen 1 20UES2WA00  | 4         | 0.21%   |
| Lenovo ThinkPad E14 Gen 6 21M70015CK  | 4         | 0.21%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ      | 4         | 0.21%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL | 4         | 0.21%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 4         | 0.21%   |
| HP Victus by Laptop 16-e0xxx          | 4         | 0.21%   |
| HP ProBook 4510s                      | 4         | 0.21%   |
| HP EliteBook 8470p                    | 4         | 0.21%   |
| HP 250 G3                             | 4         | 0.21%   |
| HP 15                                 | 4         | 0.21%   |
| Dell XPS 15 9570                      | 4         | 0.21%   |
| Dell Precision M6500                  | 4         | 0.21%   |
| Dell Latitude E6430                   | 4         | 0.21%   |
| Dell Latitude E5470                   | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 278       | 14.3%   |
| Dell Latitude     | 143       | 7.36%   |
| ASUS UX31E        | 130       | 6.69%   |
| Lenovo IdeaPad    | 118       | 6.07%   |
| HP EliteBook      | 100       | 5.14%   |
| Acer Aspire       | 98        | 5.04%   |
| HP ProBook        | 78        | 4.01%   |
| Dell XPS          | 39        | 2.01%   |
| Dell Inspiron     | 37        | 1.9%    |
| HP Pavilion       | 35        | 1.8%    |
| Dell Precision    | 29        | 1.49%   |
| ASUS VivoBook     | 28        | 1.44%   |
| HP ZBook          | 27        | 1.39%   |
| ASUS ASUS         | 26        | 1.34%   |
| Lenovo Legion     | 25        | 1.29%   |
| Lenovo Yoga       | 22        | 1.13%   |
| HP Laptop         | 22        | 1.13%   |
| ASUS Zenbook      | 22        | 1.13%   |
| Toshiba Satellite | 21        | 1.08%   |
| HP Compaq         | 21        | 1.08%   |
| Fujitsu LIFEBOOK  | 21        | 1.08%   |
| UMAX VisionBook   | 19        | 0.98%   |
| Acer TravelMate   | 17        | 0.87%   |
| Acer Swift        | 17        | 0.87%   |
| Acer Extensa      | 17        | 0.87%   |
| HP 250            | 16        | 0.82%   |
| Dell Vostro       | 16        | 0.82%   |
| Acer Nitro        | 16        | 0.82%   |
| Unknown           | 16        | 0.82%   |
| ASUS ROG          | 15        | 0.77%   |
| Lenovo ThinkBook  | 14        | 0.72%   |
| Valve Jupiter     | 13        | 0.67%   |
| Lenovo V15        | 6         | 0.31%   |
| HP Victus         | 6         | 0.31%   |
| HP OMEN           | 5         | 0.26%   |
| HP Notebook       | 5         | 0.26%   |
| HP ENVY           | 5         | 0.26%   |
| HP 255            | 5         | 0.26%   |
| Dell System       | 5         | 0.26%   |
| Dell G5           | 5         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 238       | 12.24%  |
| 2021    | 181       | 9.31%   |
| 2020    | 174       | 8.95%   |
| 2019    | 147       | 7.56%   |
| 2018    | 130       | 6.69%   |
| 2012    | 113       | 5.81%   |
| 2017    | 110       | 5.66%   |
| 2013    | 109       | 5.61%   |
| 2022    | 91        | 4.68%   |
| 2015    | 89        | 4.58%   |
| 2014    | 88        | 4.53%   |
| 2016    | 84        | 4.32%   |
| 2008    | 76        | 3.91%   |
| 2023    | 70        | 3.6%    |
| 2010    | 66        | 3.4%    |
| 2024    | 55        | 2.83%   |
| 2009    | 48        | 2.47%   |
| 2007    | 34        | 1.75%   |
| 2006    | 18        | 0.93%   |
| 2025    | 13        | 0.67%   |
| 2005    | 5         | 0.26%   |
| Unknown | 3         | 0.15%   |
| 2004    | 2         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1944      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1746      | 88.63%  |
| Enabled  | 224       | 11.37%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1933      | 99.43%  |
| Yes  | 11        | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 474       | 23.94%  |
| 4.01-8.0    | 421       | 21.26%  |
| 8.01-16.0   | 356       | 17.98%  |
| 16.01-24.0  | 283       | 14.29%  |
| 32.01-64.0  | 217       | 10.96%  |
| 1.01-2.0    | 85        | 4.29%   |
| 24.01-32.0  | 55        | 2.78%   |
| 64.01-256.0 | 39        | 1.97%   |
| 2.01-3.0    | 34        | 1.72%   |
| 0.51-1.0    | 15        | 0.76%   |
| 0.01-0.5    | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 695       | 32.16%  |
| 2.01-3.0   | 478       | 22.12%  |
| 4.01-8.0   | 376       | 17.4%   |
| 3.01-4.0   | 292       | 13.51%  |
| 8.01-16.0  | 146       | 6.76%   |
| 0.51-1.0   | 115       | 5.32%   |
| 16.01-24.0 | 28        | 1.3%    |
| 0.01-0.5   | 23        | 1.06%   |
| 32.01-64.0 | 4         | 0.19%   |
| 24.01-32.0 | 4         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1553      | 78.12%  |
| 2      | 365       | 18.36%  |
| 3      | 44        | 2.21%   |
| 0      | 18        | 0.91%   |
| 4      | 5         | 0.25%   |
| 5      | 2         | 0.1%    |
| 7      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1414      | 72.4%   |
| Yes       | 539       | 27.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1606      | 81.9%   |
| No        | 355       | 18.1%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1885      | 96.82%  |
| No        | 62        | 3.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1513      | 76.69%  |
| No        | 460       | 23.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Czechia | 1944      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Prague               | 819       | 40.23%  |
| Brno                 | 164       | 8.06%   |
| Ostrava              | 55        | 2.7%    |
| Pilsen               | 42        | 2.06%   |
| Brdo                 | 37        | 1.82%   |
| Olomouc              | 33        | 1.62%   |
| Pardubice            | 26        | 1.28%   |
| Liberec              | 21        | 1.03%   |
| Hradec Králové     | 21        | 1.03%   |
| České Budějovice  | 19        | 0.93%   |
| Šlapanice           | 18        | 0.88%   |
| Ústí nad Labem     | 14        | 0.69%   |
| Havířov            | 14        | 0.69%   |
| Chomutov             | 14        | 0.69%   |
| Zlín                | 11        | 0.54%   |
| Most                 | 11        | 0.54%   |
| Znojmo               | 10        | 0.49%   |
| Tábor               | 10        | 0.49%   |
| Kladno               | 10        | 0.49%   |
| Karlovy Vary         | 10        | 0.49%   |
| Opava                | 9         | 0.44%   |
| Jihlava              | 9         | 0.44%   |
| Příbram            | 8         | 0.39%   |
| Mladá Boleslav      | 7         | 0.34%   |
| Frýdek-Místek      | 7         | 0.34%   |
| Stachy               | 6         | 0.29%   |
| Roznov pod Radhostem | 6         | 0.29%   |
| Přerov              | 6         | 0.29%   |
| Krnov                | 6         | 0.29%   |
| Kralupy nad Vltavou  | 6         | 0.29%   |
| Český Těšín     | 6         | 0.29%   |
| Celakovice           | 6         | 0.29%   |
| Vcelna               | 5         | 0.25%   |
| Uhlirske Janovice    | 5         | 0.25%   |
| Uherské Hradiště  | 5         | 0.25%   |
| Třebíč            | 5         | 0.25%   |
| Mariánské Lázně  | 5         | 0.25%   |
| Karvina              | 5         | 0.25%   |
| Jedovnice            | 5         | 0.25%   |
| Havlíčkův Brod    | 5         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 417       | 545    | 17.74%  |
| SanDisk                     | 279       | 312    | 11.87%  |
| Seagate                     | 213       | 286    | 9.06%   |
| WDC                         | 208       | 250    | 8.85%   |
| Toshiba                     | 142       | 174    | 6.04%   |
| Kingston                    | 133       | 154    | 5.66%   |
| SK hynix                    | 121       | 146    | 5.15%   |
| Unknown                     | 109       | 147    | 4.64%   |
| Micron Technology           | 101       | 125    | 4.3%    |
| Intel                       | 81        | 97     | 3.45%   |
| Hitachi                     | 64        | 76     | 2.72%   |
| HGST                        | 50        | 64     | 2.13%   |
| Patriot                     | 42        | 53     | 1.79%   |
| KIOXIA                      | 42        | 61     | 1.79%   |
| A-DATA Technology           | 40        | 44     | 1.7%    |
| Crucial                     | 39        | 49     | 1.66%   |
| Apacer                      | 19        | 24     | 0.81%   |
| Unknown                     | 19        | 22     | 0.81%   |
| Verbatim                    | 16        | 17     | 0.68%   |
| Transcend                   | 12        | 13     | 0.51%   |
| Phison Electronics          | 12        | 16     | 0.51%   |
| LITEONIT                    | 12        | 16     | 0.51%   |
| Kingston Technology Company | 12        | 13     | 0.51%   |
| Apple                       | 12        | 20     | 0.51%   |
| LITEON                      | 9         | 9      | 0.38%   |
| Fujitsu                     | 9         | 10     | 0.38%   |
| China                       | 9         | 10     | 0.38%   |
| Silicon Motion              | 8         | 9      | 0.34%   |
| GOODRAM                     | 7         | 8      | 0.3%    |
| Phison                      | 6         | 13     | 0.26%   |
| Micron/Crucial Technology   | 6         | 7      | 0.26%   |
| Lenovo                      | 6         | 7      | 0.26%   |
| Gigabyte Technology         | 6         | 11     | 0.26%   |
| UMAX                        | 5         | 5      | 0.21%   |
| MAXIO Technology (Hangzhou) | 5         | 5      | 0.21%   |
| JMicron Technology          | 5         | 5      | 0.21%   |
| Team                        | 4         | 4      | 0.17%   |
| SOLIDIGM                    | 4         | 5      | 0.17%   |
| ASMedia                     | 4         | 6      | 0.17%   |
| ADATA Technology            | 4         | 4      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                               | 129       | 5.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 42        | 1.72%   |
| Seagate ST1000LM035-1RK172 1TB                       | 24        | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 21        | 0.86%   |
| Unknown MMC Card  64GB                               | 20        | 0.82%   |
| Unknown MMC Card  32GB                               | 20        | 0.82%   |
| Unknown                                              | 19        | 0.78%   |
| HGST HTS721010A9E630 1TB                             | 18        | 0.74%   |
| Samsung SSD 860 EVO 500GB                            | 17        | 0.69%   |
| Samsung NVMe SSD Drive 512GB                         | 17        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                      | 15        | 0.61%   |
| Toshiba MQ01ABD100 1TB                               | 14        | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 13        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 13        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                         | 13        | 0.53%   |
| Patriot Burst 480GB SSD                              | 12        | 0.49%   |
| Unknown MMC Card  16GB                               | 11        | 0.45%   |
| Seagate ST9500420AS 500GB                            | 11        | 0.45%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 11        | 0.45%   |
| SanDisk NVMe SSD Drive 1TB                           | 11        | 0.45%   |
| Samsung SSD 850 EVO 250GB                            | 11        | 0.45%   |
| Samsung MZVLB1T0HBLR-000L2 1TB                       | 11        | 0.45%   |
| Kingston SA400S37240G 240GB SSD                      | 11        | 0.45%   |
| HGST HTS725050A7E630 500GB                           | 11        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                      | 10        | 0.41%   |
| Seagate ST500LM030-1RK17D 500GB                      | 10        | 0.41%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 10        | 0.41%   |
| Toshiba MQ04ABF100 1TB                               | 9         | 0.37%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                 | 9         | 0.37%   |
| Samsung SSD 860 EVO 250GB                            | 9         | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 9         | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                     | 9         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB                         | 8         | 0.33%   |
| Unknown MMC Card  128GB                              | 8         | 0.33%   |
| Toshiba NVMe SSD Drive 256GB                         | 8         | 0.33%   |
| Toshiba MQ01ABF050 500GB                             | 8         | 0.33%   |
| SK hynix NVMe SSD Drive 512GB                        | 8         | 0.33%   |
| Seagate ST2000LM007-1R8174 2TB                       | 8         | 0.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 8         | 0.33%   |
| Samsung SSD 980 1TB                                  | 8         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 207       | 278    | 38.05%  |
| WDC                 | 119       | 140    | 21.88%  |
| Toshiba             | 82        | 95     | 15.07%  |
| Hitachi             | 64        | 76     | 11.76%  |
| HGST                | 50        | 64     | 9.19%   |
| Fujitsu             | 9         | 10     | 1.65%   |
| Samsung Electronics | 3         | 3      | 0.55%   |
| ASMedia             | 3         | 4      | 0.55%   |
| JMicron Technology  | 2         | 2      | 0.37%   |
| USB3.0              | 1         | 1      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |
| TO Exter            | 1         | 2      | 0.18%   |
| IBM/Hitachi         | 1         | 1      | 0.18%   |
| Apple               | 1         | 3      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 176       | 181    | 22.19%  |
| Samsung Electronics | 157       | 193    | 19.8%   |
| Kingston            | 92        | 105    | 11.6%   |
| WDC                 | 43        | 60     | 5.42%   |
| Patriot             | 38        | 47     | 4.79%   |
| A-DATA Technology   | 36        | 40     | 4.54%   |
| Intel               | 34        | 41     | 4.29%   |
| Crucial             | 32        | 42     | 4.04%   |
| Micron Technology   | 21        | 26     | 2.65%   |
| SK hynix            | 18        | 20     | 2.27%   |
| Apacer              | 18        | 23     | 2.27%   |
| Verbatim            | 16        | 17     | 2.02%   |
| Toshiba             | 14        | 17     | 1.77%   |
| Transcend           | 12        | 13     | 1.51%   |
| LITEONIT            | 12        | 16     | 1.51%   |
| China               | 8         | 9      | 1.01%   |
| LITEON              | 7         | 7      | 0.88%   |
| Apple               | 7         | 9      | 0.88%   |
| GOODRAM             | 6         | 7      | 0.76%   |
| UMAX                | 5         | 5      | 0.63%   |
| Gigabyte Technology | 5         | 9      | 0.63%   |
| Team                | 3         | 3      | 0.38%   |
| WDC WDS             | 2         | 3      | 0.25%   |
| Netac               | 2         | 2      | 0.25%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.25%   |
| KingSpec            | 2         | 4      | 0.25%   |
| Intenso             | 2         | 2      | 0.25%   |
| Hewlett-Packard     | 2         | 2      | 0.25%   |
| ASMT                | 2         | 2      | 0.25%   |
| Unknown             | 2         | 2      | 0.25%   |
| WDC WDS2            | 1         | 1      | 0.13%   |
| Vi550               | 1         | 1      | 0.13%   |
| UMIS                | 1         | 1      | 0.13%   |
| StoreJet            | 1         | 1      | 0.13%   |
| ShanDianZhe         | 1         | 1      | 0.13%   |
| Seagate             | 1         | 1      | 0.13%   |
| SABRENT             | 1         | 1      | 0.13%   |
| OCZ                 | 1         | 4      | 0.13%   |
| Mushkin             | 1         | 1      | 0.13%   |
| MicroFrom           | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 807       | 1114   | 36.25%  |
| SSD     | 748       | 930    | 33.6%   |
| HDD     | 527       | 680    | 23.67%  |
| MMC     | 130       | 170    | 5.84%   |
| Unknown | 14        | 20     | 0.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1153      | 1547   | 53.6%   |
| NVMe | 806       | 1111   | 37.47%  |
| MMC  | 130       | 170    | 6.04%   |
| SAS  | 62        | 86     | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 898       | 1134   | 71.16%  |
| 0.51-1.0   | 309       | 399    | 24.48%  |
| 1.01-2.0   | 47        | 68     | 3.72%   |
| 3.01-4.0   | 6         | 7      | 0.48%   |
| 4.01-10.0  | 2         | 2      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 477       | 23.29%  |
| 251-500        | 471       | 23%     |
| 501-1000       | 322       | 15.72%  |
| 1-20           | 305       | 14.89%  |
| 1001-2000      | 131       | 6.4%    |
| 51-100         | 127       | 6.2%    |
| 21-50          | 75        | 3.66%   |
| Unknown        | 72        | 3.52%   |
| More than 3000 | 42        | 2.05%   |
| 2001-3000      | 26        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 902       | 42.29%  |
| 21-50          | 309       | 14.49%  |
| 101-250        | 275       | 12.89%  |
| 51-100         | 228       | 10.69%  |
| 251-500        | 186       | 8.72%   |
| 501-1000       | 96        | 4.5%    |
| Unknown        | 72        | 3.38%   |
| 1001-2000      | 37        | 1.73%   |
| More than 3000 | 15        | 0.7%    |
| 2001-3000      | 9         | 0.42%   |
| 0              | 4         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                  | 129       | 130    | 53.09%  |
| SK hynix BC711 HFM512GD3JX013N 512GB    | 8         | 11     | 3.29%   |
| HGST HTS725050A7E630 500GB              | 4         | 5      | 1.65%   |
| Seagate ST9500420AS 500GB               | 3         | 4      | 1.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 2      | 0.82%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 0.82%   |
| Toshiba MQ01ABD075 752GB                | 2         | 2      | 0.82%   |
| Toshiba MK1234GSX 120GB                 | 2         | 2      | 0.82%   |
| Seagate ST9250315AS 250GB               | 2         | 4      | 0.82%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 3      | 0.82%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 2      | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 2      | 0.82%   |
| Hitachi HTS541610J9SA00 100GB           | 2         | 2      | 0.82%   |
| HGST HTS721010A9E630 1TB                | 2         | 2      | 0.82%   |
| HGST HTS545050A7E380 500GB              | 2         | 2      | 0.82%   |
| Fujitsu MHZ2250BH G2 250GB              | 2         | 2      | 0.82%   |
| WDC WD7500BPVT-22HXZT3 752GB            | 1         | 1      | 0.41%   |
| WDC WD7500BPKT-75PK4T0 752GB            | 1         | 1      | 0.41%   |
| WDC WD6400BPVT-60HXZT1 640GB            | 1         | 1      | 0.41%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 1      | 0.41%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 1      | 0.41%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 0.41%   |
| WDC WD3200BEVT-60ZCT1 320GB             | 1         | 1      | 0.41%   |
| WDC WD Blue SA510 M.2 2280 500GB SSD    | 1         | 1      | 0.41%   |
| Toshiba MQ04ABF100 1TB                  | 1         | 1      | 0.41%   |
| Toshiba MK8037GSX 80GB                  | 1         | 1      | 0.41%   |
| Toshiba MK7559GSXP 752GB                | 1         | 1      | 0.41%   |
| Toshiba MK6465GSXN 640GB                | 1         | 1      | 0.41%   |
| Toshiba MK5056GSY 500GB                 | 1         | 1      | 0.41%   |
| Toshiba MK3261GSYN 320GB                | 1         | 1      | 0.41%   |
| Toshiba MK2561GSYN 250GB                | 1         | 2      | 0.41%   |
| Toshiba MK2552GSX 250GB                 | 1         | 1      | 0.41%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD | 1         | 1      | 0.41%   |
| SK hynix PC711 HFS512GDE9X073N 512GB    | 1         | 1      | 0.41%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD   | 1         | 1      | 0.41%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 1         | 1      | 0.41%   |
| Seagate ST980811AS 80GB                 | 1         | 1      | 0.41%   |
| Seagate ST9750420AS 752GB               | 1         | 1      | 0.41%   |
| Seagate ST9500420ASG 500GB              | 1         | 1      | 0.41%   |
| Seagate ST9500325AS 500GB               | 1         | 1      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 131       | 132    | 54.13%  |
| Seagate             | 26        | 30     | 10.74%  |
| Hitachi             | 16        | 19     | 6.61%   |
| Toshiba             | 15        | 16     | 6.2%    |
| SK hynix            | 11        | 14     | 4.55%   |
| WDC                 | 10        | 10     | 4.13%   |
| HGST                | 9         | 10     | 3.72%   |
| Samsung Electronics | 7         | 11     | 2.89%   |
| Intel               | 6         | 6      | 2.48%   |
| Fujitsu             | 3         | 4      | 1.24%   |
| A-DATA Technology   | 2         | 3      | 0.83%   |
| Micron Technology   | 1         | 1      | 0.41%   |
| LITEONIT            | 1         | 2      | 0.41%   |
| KIOXIA              | 1         | 2      | 0.41%   |
| Kingston            | 1         | 1      | 0.41%   |
| IBM/Hitachi         | 1         | 1      | 0.41%   |
| Crucial             | 1         | 1      | 0.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor      | Notebooks | Drives | Percent |
|-------------|-----------|--------|---------|
| Seagate     | 26        | 30     | 34.21%  |
| Hitachi     | 16        | 19     | 21.05%  |
| Toshiba     | 14        | 15     | 18.42%  |
| HGST        | 9         | 10     | 11.84%  |
| WDC         | 7         | 7      | 9.21%   |
| Fujitsu     | 3         | 4      | 3.95%   |
| IBM/Hitachi | 1         | 1      | 1.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 152       | 156    | 63.07%  |
| HDD  | 75        | 86     | 31.12%  |
| NVMe | 14        | 21     | 5.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDSC2BW120H6 120GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1007      | 1611   | 49.12%  |
| Works    | 802       | 1038   | 39.12%  |
| Malfunc  | 240       | 263    | 11.71%  |
| Failed   | 1         | 2      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1254      | 54.1%   |
| Samsung Electronics              | 271       | 11.69%  |
| AMD                              | 213       | 9.19%   |
| SanDisk                          | 140       | 6.04%   |
| SK hynix                         | 100       | 4.31%   |
| Micron Technology                | 80        | 3.45%   |
| Kingston Technology Company      | 55        | 2.37%   |
| Toshiba America Info Systems     | 45        | 1.94%   |
| KIOXIA                           | 45        | 1.94%   |
| Phison Electronics               | 22        | 0.95%   |
| Micron/Crucial Technology        | 12        | 0.52%   |
| Silicon Motion                   | 10        | 0.43%   |
| ADATA Technology                 | 9         | 0.39%   |
| Union Memory (Shenzhen)          | 7         | 0.3%    |
| Nvidia                           | 6         | 0.26%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.26%   |
| Lenovo                           | 6         | 0.26%   |
| Solidigm                         | 5         | 0.22%   |
| Lite-On Technology               | 4         | 0.17%   |
| Hosin Global Electronics         | 4         | 0.17%   |
| Solid State Storage Technology   | 3         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.13%   |
| Apple                            | 3         | 0.13%   |
| Seagate Technology               | 2         | 0.09%   |
| Realtek Semiconductor            | 2         | 0.09%   |
| JMicron Technology               | 2         | 0.09%   |
| ASMedia Technology               | 2         | 0.09%   |
| VIA Technologies                 | 1         | 0.04%   |
| TenaFe                           | 1         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| O2 Micro                         | 1         | 0.04%   |
| Marvell Technology Group         | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 218       | 8.86%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 180       | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 121       | 4.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 113       | 4.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 100       | 4.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 84        | 3.41%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 77        | 3.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 70        | 2.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 65        | 2.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 53        | 2.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 52        | 2.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 51        | 2.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 41        | 1.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 40        | 1.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 40        | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 38        | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 36        | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 35        | 1.42%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 33        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 31        | 1.26%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 26        | 1.06%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 26        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 26        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 24        | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 22        | 0.89%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                             | 20        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 19        | 0.77%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 18        | 0.73%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 18        | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 18        | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 17        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 17        | 0.69%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 16        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 16        | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 15        | 0.61%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 15        | 0.61%   |
| Intel SSD 660P Series                                                            | 15        | 0.61%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 15        | 0.61%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 13        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1267      | 54.05%  |
| NVMe | 808       | 34.47%  |
| RAID | 162       | 6.91%   |
| IDE  | 107       | 4.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1532      | 78.81%  |
| AMD     | 411       | 21.14%  |
| Unknown | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 130       | 6.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 1.34%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 1.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 25        | 1.28%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 20        | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.98%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 19        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 0.98%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 18        | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.92%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.92%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 18        | 0.92%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 17        | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 15        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 15        | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 0.77%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 0.77%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 15        | 0.77%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 15        | 0.77%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 14        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.72%   |
| Intel 12th Gen Core i7-12700H                 | 14        | 0.72%   |
| AMD Custom APU 0405                           | 14        | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 13        | 0.67%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 13        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 12        | 0.62%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 0.62%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 11        | 0.57%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 11        | 0.57%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 11        | 0.57%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 10        | 0.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 10        | 0.51%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 10        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 487       | 25.04%  |
| Intel Core i5           | 381       | 19.59%  |
| Other                   | 214       | 11%     |
| Intel Celeron           | 116       | 5.96%   |
| AMD Ryzen 5             | 101       | 5.19%   |
| AMD Ryzen 7             | 99        | 5.09%   |
| Intel Core i3           | 95        | 4.88%   |
| Intel Core 2 Duo        | 94        | 4.83%   |
| Intel Pentium           | 54        | 2.78%   |
| AMD Ryzen 7 PRO         | 43        | 2.21%   |
| Intel Atom              | 31        | 1.59%   |
| AMD A4                  | 21        | 1.08%   |
| Intel Core              | 19        | 0.98%   |
| AMD A6                  | 18        | 0.93%   |
| AMD Ryzen 5 PRO         | 15        | 0.77%   |
| Intel Pentium Dual-Core | 11        | 0.57%   |
| Intel Genuine           | 11        | 0.57%   |
| AMD Ryzen 3             | 11        | 0.57%   |
| AMD Ryzen 9             | 10        | 0.51%   |
| AMD A8                  | 10        | 0.51%   |
| Intel Celeron M         | 9         | 0.46%   |
| Intel Core 2            | 8         | 0.41%   |
| Intel Pentium Silver    | 6         | 0.31%   |
| Intel Core i9           | 6         | 0.31%   |
| AMD E1                  | 6         | 0.31%   |
| Intel Xeon              | 5         | 0.26%   |
| Intel Pentium M         | 5         | 0.26%   |
| Intel Pentium Dual      | 5         | 0.26%   |
| Intel Celeron Dual-Core | 5         | 0.26%   |
| AMD E                   | 5         | 0.26%   |
| AMD Turion II           | 4         | 0.21%   |
| AMD Mobile Sempron      | 4         | 0.21%   |
| AMD FX                  | 4         | 0.21%   |
| Intel Core m5           | 3         | 0.15%   |
| AMD Turion 64 X2 Mobile | 3         | 0.15%   |
| AMD E2                  | 3         | 0.15%   |
| AMD Athlon X2           | 3         | 0.15%   |
| AMD A12                 | 3         | 0.15%   |
| AMD A10                 | 3         | 0.15%   |
| AMD Ryzen 3 PRO         | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 917       | 47.12%  |
| 4       | 527       | 27.08%  |
| 8       | 181       | 9.3%    |
| 6       | 174       | 8.94%   |
| 1       | 41        | 2.11%   |
| 12      | 31        | 1.59%   |
| 10      | 30        | 1.54%   |
| 14      | 29        | 1.49%   |
| 16      | 13        | 0.67%   |
| 24      | 2         | 0.1%    |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1941      | 99.85%  |
| 2      | 3         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1457      | 74.91%  |
| 1       | 487       | 25.04%  |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1905      | 97.79%  |
| 32-bit         | 24        | 1.23%   |
| Unknown        | 17        | 0.87%   |
| 64-bit         | 2         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 892       | 44.27%  |
| 0x206a7    | 190       | 9.43%   |
| 0x306a9    | 54        | 2.68%   |
| 0x806ec    | 43        | 2.13%   |
| 0x806ea    | 43        | 2.13%   |
| 0x1067a    | 41        | 2.03%   |
| 0x406e3    | 40        | 1.99%   |
| 0x806c1    | 35        | 1.74%   |
| 0x0a50000c | 35        | 1.74%   |
| 0x40651    | 33        | 1.64%   |
| 0x08600106 | 31        | 1.54%   |
| 0x906ea    | 30        | 1.49%   |
| 0x306c3    | 30        | 1.49%   |
| 0x806e9    | 27        | 1.34%   |
| 0x306d4    | 25        | 1.24%   |
| 0x6fd      | 21        | 1.04%   |
| 0x30678    | 19        | 0.94%   |
| 0xa0652    | 17        | 0.84%   |
| 0x08608103 | 17        | 0.84%   |
| 0x506e3    | 16        | 0.79%   |
| 0x20655    | 16        | 0.79%   |
| 0x706a1    | 15        | 0.74%   |
| 0x406c3    | 14        | 0.69%   |
| 0x10676    | 14        | 0.69%   |
| 0x906e9    | 13        | 0.65%   |
| 0x08108102 | 13        | 0.65%   |
| 0x706e5    | 12        | 0.6%    |
| 0x06006705 | 12        | 0.6%    |
| 0x906a3    | 11        | 0.55%   |
| 0x406c4    | 11        | 0.55%   |
| 0x0a50000d | 11        | 0.55%   |
| 0x906ed    | 10        | 0.5%    |
| 0x08600104 | 10        | 0.5%    |
| 0x6e8      | 9         | 0.45%   |
| 0x506c9    | 9         | 0.45%   |
| 0x806d1    | 8         | 0.4%    |
| 0x08600103 | 8         | 0.4%    |
| 0x07030105 | 8         | 0.4%    |
| 0x806eb    | 7         | 0.35%   |
| 0x706a8    | 7         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 309       | 15.86%  |
| SandyBridge       | 245       | 12.58%  |
| Unknown           | 149       | 7.65%   |
| Haswell           | 119       | 6.11%   |
| IvyBridge         | 108       | 5.54%   |
| Skylake           | 99        | 5.08%   |
| Zen 3             | 93        | 4.77%   |
| Penryn            | 87        | 4.47%   |
| Zen 2             | 77        | 3.95%   |
| Alderlake Hybrid  | 69        | 3.54%   |
| Silvermont        | 68        | 3.49%   |
| TigerLake         | 66        | 3.39%   |
| Core              | 55        | 2.82%   |
| Broadwell         | 48        | 2.46%   |
| Westmere          | 44        | 2.26%   |
| Goldmont plus     | 42        | 2.16%   |
| Excavator         | 35        | 1.8%    |
| CometLake         | 35        | 1.8%    |
| Icelake           | 28        | 1.44%   |
| Zen+              | 26        | 1.33%   |
| P6                | 15        | 0.77%   |
| Goldmont          | 15        | 0.77%   |
| Bonnell           | 14        | 0.72%   |
| Puma              | 13        | 0.67%   |
| Meteorlake Hybrid | 11        | 0.56%   |
| Bobcat            | 10        | 0.51%   |
| Nehalem           | 9         | 0.46%   |
| K10               | 9         | 0.46%   |
| Piledriver        | 8         | 0.41%   |
| K8 Hammer         | 8         | 0.41%   |
| Zen               | 7         | 0.36%   |
| Steamroller       | 7         | 0.36%   |
| Jaguar            | 6         | 0.31%   |
| Tremont           | 5         | 0.26%   |
| K8 & K10 hybrid   | 4         | 0.21%   |
| Lunarlake Hybrid  | 3         | 0.15%   |
| K10 Llano         | 2         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1407      | 57.41%  |
| AMD                              | 523       | 21.34%  |
| Nvidia                           | 517       | 21.09%  |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| VIA Technologies                 | 1         | 0.04%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 234       | 9.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 102       | 4.03%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 78        | 3.09%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 74        | 2.93%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 63        | 2.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 62        | 2.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 61        | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 59        | 2.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 56        | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 56        | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.98%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 42        | 1.66%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 42        | 1.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 37        | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 36        | 1.42%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 35        | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 32        | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 1.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 31        | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 29        | 1.15%   |
| AMD Lucienne                                                                             | 29        | 1.15%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 28        | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26        | 1.03%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 23        | 0.91%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 23        | 0.91%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 22        | 0.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 22        | 0.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 22        | 0.87%   |
| AMD Barcelo                                                                              | 22        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.83%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 21        | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 20        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 0.75%   |
| AMD Rembrandt [Radeon 680M]                                                              | 17        | 0.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 16        | 0.63%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 15        | 0.59%   |
| AMD Phoenix1                                                                             | 15        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 942       | 48.36%  |
| Intel + Nvidia | 367       | 18.84%  |
| 1 x AMD        | 350       | 17.97%  |
| 1 x Nvidia     | 92        | 4.72%   |
| Intel + AMD    | 82        | 4.21%   |
| AMD + Nvidia   | 59        | 3.03%   |
| 2 x AMD        | 33        | 1.69%   |
| 2 x Intel      | 18        | 0.92%   |
| Other          | 2         | 0.1%    |
| 1 x SiS        | 2         | 0.1%    |
| 1 x VIA        | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1678      | 85.39%  |
| Proprietary | 193       | 9.82%   |
| Unknown     | 94        | 4.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1378      | 69.04%  |
| 0.01-0.5   | 237       | 11.87%  |
| 1.01-2.0   | 176       | 8.82%   |
| 0.51-1.0   | 94        | 4.71%   |
| 3.01-4.0   | 73        | 3.66%   |
| 5.01-6.0   | 22        | 1.1%    |
| 7.01-8.0   | 11        | 0.55%   |
| 2.01-3.0   | 4         | 0.2%    |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 434       | 18.39%  |
| LG Display              | 295       | 12.5%   |
| BOE                     | 256       | 10.85%  |
| Chimei Innolux          | 245       | 10.38%  |
| Samsung Electronics     | 231       | 9.79%   |
| CPT                     | 136       | 5.76%   |
| Dell                    | 100       | 4.24%   |
| Eizo                    | 68        | 2.88%   |
| Lenovo                  | 62        | 2.63%   |
| Sharp                   | 53        | 2.25%   |
| Chi Mei Optoelectronics | 43        | 1.82%   |
| Philips                 | 40        | 1.69%   |
| Hewlett-Packard         | 40        | 1.69%   |
| PANDA                   | 37        | 1.57%   |
| Goldstar                | 33        | 1.4%    |
| BenQ                    | 30        | 1.27%   |
| LG Philips              | 21        | 0.89%   |
| CSO                     | 21        | 0.89%   |
| AOC                     | 21        | 0.89%   |
| InfoVision              | 18        | 0.76%   |
| Acer                    | 18        | 0.76%   |
| Valve                   | 14        | 0.59%   |
| Apple                   | 13        | 0.55%   |
| Ancor Communications    | 12        | 0.51%   |
| Iiyama                  | 11        | 0.47%   |
| Fujitsu Siemens         | 9         | 0.38%   |
| ASUSTek Computer        | 9         | 0.38%   |
| Sony                    | 8         | 0.34%   |
| Quanta Display          | 7         | 0.3%    |
| Panasonic               | 7         | 0.3%    |
| MSI                     | 7         | 0.3%    |
| HannStar                | 6         | 0.25%   |
| Toshiba                 | 5         | 0.21%   |
| NEC Computers           | 5         | 0.21%   |
| CSOT                    | 5         | 0.21%   |
| Mi                      | 3         | 0.13%   |
| JDI                     | 3         | 0.13%   |
| HKC                     | 3         | 0.13%   |
| DENON                   | 3         | 0.13%   |
| Vestel Elektronik       | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 130       | 5.4%    |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 59        | 2.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 19        | 0.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 17        | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 16        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.62%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 11        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.46%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 11        | 0.46%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 10        | 0.42%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 9         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 9         | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 9         | 0.37%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 8         | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 8         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.33%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 7         | 0.29%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 7         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 7         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 7         | 0.29%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 7         | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 7         | 0.29%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 7         | 0.29%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 943       | 42.73%  |
| 1366x768 (WXGA)    | 387       | 17.54%  |
| 1600x900 (HD+)     | 238       | 10.78%  |
| 3840x2160 (4K)     | 143       | 6.48%   |
| 1920x1200 (WUXGA)  | 90        | 4.08%   |
| 2560x1440 (QHD)    | 85        | 3.85%   |
| 1280x800 (WXGA)    | 79        | 3.58%   |
| 2560x1600          | 42        | 1.9%    |
| 1680x1050 (WSXGA+) | 28        | 1.27%   |
| 2880x1800          | 23        | 1.04%   |
| 1440x900 (WXGA+)   | 23        | 1.04%   |
| 800x1280           | 14        | 0.63%   |
| 3440x1440          | 12        | 0.54%   |
| 1280x1024 (SXGA)   | 11        | 0.5%    |
| 3840x2400          | 9         | 0.41%   |
| 1024x600           | 9         | 0.41%   |
| 1024x768 (XGA)     | 6         | 0.27%   |
| Unknown            | 6         | 0.27%   |
| 2256x1504          | 5         | 0.23%   |
| 3456x2160          | 4         | 0.18%   |
| 1360x768           | 4         | 0.18%   |
| 3000x2000          | 3         | 0.14%   |
| 2880x1620          | 3         | 0.14%   |
| 2560x1080          | 3         | 0.14%   |
| 2160x1440          | 3         | 0.14%   |
| 2160x1350          | 3         | 0.14%   |
| 2048x1280          | 3         | 0.14%   |
| 1920x540           | 3         | 0.14%   |
| 3840x1200          | 2         | 0.09%   |
| 3840x1080          | 2         | 0.09%   |
| 3200x2000          | 2         | 0.09%   |
| 3200x1800 (QHD+)   | 2         | 0.09%   |
| 3072x1920          | 2         | 0.09%   |
| 2240x1400          | 2         | 0.09%   |
| 1600x1200          | 2         | 0.09%   |
| 1400x1050          | 2         | 0.09%   |
| 8320x2160          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 3840x1600          | 1         | 0.05%   |
| 2944x1840          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 809       | 34.15%  |
| 13      | 384       | 16.21%  |
| 14      | 286       | 12.07%  |
| 17      | 134       | 5.66%   |
| 24      | 126       | 5.32%   |
| 27      | 105       | 4.43%   |
| 31      | 89        | 3.76%   |
| 16      | 69        | 2.91%   |
| 23      | 60        | 2.53%   |
| 12      | 51        | 2.15%   |
| 11      | 44        | 1.86%   |
| 21      | 36        | 1.52%   |
| Unknown | 19        | 0.8%    |
| 22      | 17        | 0.72%   |
| 7       | 14        | 0.59%   |
| 34      | 13        | 0.55%   |
| 18      | 13        | 0.55%   |
| 19      | 11        | 0.46%   |
| 10      | 11        | 0.46%   |
| 84      | 10        | 0.42%   |
| 20      | 10        | 0.42%   |
| 40      | 6         | 0.25%   |
| 33      | 5         | 0.21%   |
| 29      | 5         | 0.21%   |
| 25      | 5         | 0.21%   |
| 54      | 4         | 0.17%   |
| 32      | 4         | 0.17%   |
| 26      | 4         | 0.17%   |
| 72      | 3         | 0.13%   |
| 43      | 3         | 0.13%   |
| 28      | 3         | 0.13%   |
| 65      | 2         | 0.08%   |
| 49      | 2         | 0.08%   |
| 48      | 2         | 0.08%   |
| 142     | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 38      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1279      | 54.75%  |
| 201-300        | 346       | 14.81%  |
| 501-600        | 265       | 11.34%  |
| 351-400        | 165       | 7.06%   |
| 601-700        | 108       | 4.62%   |
| 401-500        | 76        | 3.25%   |
| 701-800        | 23        | 0.98%   |
| Unknown        | 19        | 0.81%   |
| 1001-1500      | 15        | 0.64%   |
| 1-100          | 14        | 0.6%    |
| 1501-2000      | 13        | 0.56%   |
| 801-900        | 9         | 0.39%   |
| 901-1000       | 2         | 0.09%   |
| More than 2000 | 1         | 0.04%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1610      | 79.94%  |
| 16/10   | 319       | 15.84%  |
| 21/9    | 16        | 0.79%   |
| 3/2     | 15        | 0.74%   |
| Unknown | 13        | 0.65%   |
| 5/4     | 11        | 0.55%   |
| 0.67    | 11        | 0.55%   |
| 4/3     | 10        | 0.5%    |
| 0.62    | 3         | 0.15%   |
| 3.20    | 2         | 0.1%    |
| 32/9    | 1         | 0.05%   |
| 3.73    | 1         | 0.05%   |
| 3.33    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 806       | 34.23%  |
| 81-90          | 441       | 18.73%  |
| 71-80          | 221       | 9.38%   |
| 201-250        | 175       | 7.43%   |
| 351-500        | 117       | 4.97%   |
| 301-350        | 111       | 4.71%   |
| 121-130        | 107       | 4.54%   |
| 111-120        | 65        | 2.76%   |
| 61-70          | 50        | 2.12%   |
| 251-300        | 50        | 2.12%   |
| 51-60          | 44        | 1.87%   |
| 151-200        | 31        | 1.32%   |
| More than 1000 | 24        | 1.02%   |
| 131-140        | 23        | 0.98%   |
| Unknown        | 19        | 0.81%   |
| 141-150        | 16        | 0.68%   |
| 1-40           | 15        | 0.64%   |
| 501-1000       | 15        | 0.64%   |
| 91-100         | 14        | 0.59%   |
| 41-50          | 11        | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1062      | 47.2%   |
| 101-120       | 484       | 21.51%  |
| 51-100        | 395       | 17.56%  |
| 161-240       | 221       | 9.82%   |
| More than 240 | 53        | 2.36%   |
| Unknown       | 19        | 0.84%   |
| 1-50          | 16        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1473      | 73.28%  |
| 2     | 421       | 20.95%  |
| 3     | 61        | 3.03%   |
| 0     | 52        | 2.59%   |
| 4     | 3         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 1034      | 32.88%  |
| Realtek Semiconductor                  | 875       | 27.82%  |
| Qualcomm Atheros                       | 465       | 14.79%  |
| Broadcom                               | 173       | 5.5%    |
| Samsung Electronics                    | 136       | 4.32%   |
| MediaTek                               | 102       | 3.24%   |
| Broadcom Limited                       | 61        | 1.94%   |
| Marvell Technology Group               | 31        | 0.99%   |
| Lenovo                                 | 29        | 0.92%   |
| Shenzhen Goodix Technology             | 24        | 0.76%   |
| ASIX Electronics                       | 24        | 0.76%   |
| Ralink                                 | 21        | 0.67%   |
| Dell                                   | 20        | 0.64%   |
| Qualcomm                               | 19        | 0.6%    |
| DisplayLink                            | 17        | 0.54%   |
| Sierra Wireless                        | 16        | 0.51%   |
| TP-Link                                | 13        | 0.41%   |
| Ralink Technology                      | 12        | 0.38%   |
| Qualcomm Atheros Communications        | 10        | 0.32%   |
| Ericsson Business Mobile Networks      | 8         | 0.25%   |
| Hewlett-Packard                        | 7         | 0.22%   |
| Xiaomi                                 | 6         | 0.19%   |
| Fibocom                                | 6         | 0.19%   |
| Attansic Technology                    | 5         | 0.16%   |
| Qualcomm Technologies                  | 3         | 0.1%    |
| Huawei Technologies                    | 3         | 0.1%    |
| D-Link                                 | 3         | 0.1%    |
| Spreadtrum Communications              | 2         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.06%   |
| Nvidia                                 | 2         | 0.06%   |
| Google                                 | 2         | 0.06%   |
| VIA Technologies                       | 1         | 0.03%   |
| QinHeng Electronics                    | 1         | 0.03%   |
| Prusa                                  | 1         | 0.03%   |
| Motorola PCS                           | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| JMicron Technology                     | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |
| Fujitsu Siemens Computers              | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 538       | 14.19%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 163       | 4.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 133       | 3.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 130       | 3.43%   |
| Intel Wi-Fi 6 AX200                                                    | 107       | 2.82%   |
| Intel Wireless 8265 / 8275                                             | 91        | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 90        | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 73        | 1.93%   |
| Intel Wireless 7260                                                    | 66        | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 56        | 1.48%   |
| Intel Wireless 8260                                                    | 55        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 54        | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 52        | 1.37%   |
| Intel Wi-Fi 6 AX201                                                    | 50        | 1.32%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 49        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 47        | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 47        | 1.24%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 46        | 1.21%   |
| Intel Wireless 7265                                                    | 45        | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                                  | 45        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 39        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 38        | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 36        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 35        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 34        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 33        | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 31        | 0.82%   |
| Intel Wireless 3165                                                    | 31        | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                          | 28        | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 27        | 0.71%   |
| Intel Ethernet Connection I219-LM                                      | 26        | 0.69%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 25        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 25        | 0.66%   |
| Shenzhen Goodix Fingerprint Reader                                     | 24        | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 24        | 0.63%   |
| Intel Ethernet Connection I218-LM                                      | 23        | 0.61%   |
| Intel WiFi Link 5100                                                   | 22        | 0.58%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                               | 22        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                          | 21        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 981       | 49.75%  |
| Qualcomm Atheros                | 401       | 20.33%  |
| Realtek Semiconductor           | 233       | 11.82%  |
| Broadcom                        | 117       | 5.93%   |
| MediaTek                        | 91        | 4.61%   |
| Broadcom Limited                | 32        | 1.62%   |
| Ralink                          | 21        | 1.06%   |
| Qualcomm                        | 18        | 0.91%   |
| Sierra Wireless                 | 16        | 0.81%   |
| Dell                            | 14        | 0.71%   |
| Ralink Technology               | 12        | 0.61%   |
| TP-Link                         | 11        | 0.56%   |
| Qualcomm Atheros Communications | 10        | 0.51%   |
| Fibocom                         | 6         | 0.3%    |
| Qualcomm Technologies           | 3         | 0.15%   |
| Hewlett-Packard                 | 2         | 0.1%    |
| D-Link                          | 2         | 0.1%    |
| Fujitsu Siemens Computers       | 1         | 0.05%   |
| ASUSTek Computer                | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 163       | 8.24%   |
| Intel Wi-Fi 6 AX200                                                  | 107       | 5.41%   |
| Intel Wireless 8265 / 8275                                           | 91        | 4.6%    |
| Intel Wireless 7260                                                  | 66        | 3.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 56        | 2.83%   |
| Intel Wireless 8260                                                  | 55        | 2.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 54        | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 52        | 2.63%   |
| Intel Wi-Fi 6 AX201                                                  | 50        | 2.53%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 49        | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 47        | 2.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 47        | 2.37%   |
| Intel Wireless 7265                                                  | 45        | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 39        | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 38        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 36        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 35        | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 34        | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 33        | 1.67%   |
| Intel Wireless 3165                                                  | 31        | 1.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 30        | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                        | 28        | 1.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 27        | 1.36%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 26        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 25        | 1.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 24        | 1.21%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 23        | 1.16%   |
| Intel WiFi Link 5100                                                 | 22        | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 20        | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 20        | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 19        | 0.96%   |
| Intel Wireless 3160                                                  | 19        | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 19        | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection              | 15        | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 15        | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 14        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 14        | 0.71%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 14        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 14        | 0.71%   |
| Intel Centrino Wireless-N 2230                                       | 13        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 767       | 44.91%  |
| Intel                                  | 452       | 26.46%  |
| Samsung Electronics                    | 136       | 7.96%   |
| Qualcomm Atheros                       | 110       | 6.44%   |
| Broadcom                               | 68        | 3.98%   |
| Marvell Technology Group               | 31        | 1.81%   |
| Lenovo                                 | 29        | 1.7%    |
| Broadcom Limited                       | 29        | 1.7%    |
| ASIX Electronics                       | 24        | 1.41%   |
| DisplayLink                            | 17        | 1%      |
| MediaTek                               | 11        | 0.64%   |
| Xiaomi                                 | 6         | 0.35%   |
| Attansic Technology                    | 5         | 0.29%   |
| Hewlett-Packard                        | 3         | 0.18%   |
| TP-Link                                | 2         | 0.12%   |
| Spreadtrum Communications              | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.12%   |
| Nvidia                                 | 2         | 0.12%   |
| Huawei Technologies                    | 2         | 0.12%   |
| Google                                 | 2         | 0.12%   |
| VIA Technologies                       | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Qualcomm                               | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| JMicron Technology                     | 1         | 0.06%   |
| ICS Advent                             | 1         | 0.06%   |
| Foxconn / Hon Hai                      | 1         | 0.06%   |
| D-Link                                 | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 538       | 30.6%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 133       | 7.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 130       | 7.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 90        | 5.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 73        | 4.15%   |
| Intel Ethernet Connection (4) I219-LM                                  | 45        | 2.56%   |
| Intel Ethernet Connection I219-LM                                      | 26        | 1.48%   |
| Intel Ethernet Connection I218-LM                                      | 23        | 1.31%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 1.25%   |
| Intel 82567LM Gigabit Network Connection                               | 22        | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                          | 21        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                   | 19        | 1.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 18        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                  | 17        | 0.97%   |
| Intel Ethernet Connection (6) I219-V                                   | 16        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 16        | 0.91%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 15        | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                  | 15        | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 14        | 0.8%    |
| Lenovo ThinkPad TBT 3 Dock                                             | 14        | 0.8%    |
| Intel Ethernet Connection (10) I219-LM                                 | 14        | 0.8%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 13        | 0.74%   |
| Intel Ethernet Connection (6) I219-LM                                  | 12        | 0.68%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 12        | 0.68%   |
| Realtek Killer E2600 GbE Controller                                    | 11        | 0.63%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 11        | 0.63%   |
| Intel Ethernet Connection I219-V                                       | 10        | 0.57%   |
| Intel Ethernet Connection (16) I219-LM                                 | 10        | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.46%   |
| Intel Ethernet Connection (18) I219-LM                                 | 8         | 0.46%   |
| Intel Ethernet Connection (16) I219-V                                  | 8         | 0.46%   |
| Intel Ethernet Connection (11) I219-LM                                 | 8         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                | 8         | 0.46%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 8         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1883      | 53.27%  |
| Ethernet | 1599      | 45.23%  |
| Modem    | 51        | 1.44%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1435      | 69.46%  |
| Ethernet | 631       | 30.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1312      | 67.35%  |
| 1     | 578       | 29.67%  |
| 0     | 38        | 1.95%   |
| 3     | 20        | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1629      | 82.36%  |
| Yes  | 349       | 17.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 753       | 49.41%  |
| Realtek Semiconductor           | 152       | 9.97%   |
| IMC Networks                    | 112       | 7.35%   |
| Qualcomm Atheros Communications | 101       | 6.63%   |
| Foxconn / Hon Hai               | 95        | 6.23%   |
| Broadcom                        | 82        | 5.38%   |
| Lite-On Technology              | 58        | 3.81%   |
| Hewlett-Packard                 | 37        | 2.43%   |
| Dell                            | 26        | 1.71%   |
| ASUSTek Computer                | 21        | 1.38%   |
| Ralink                          | 14        | 0.92%   |
| MediaTek                        | 14        | 0.92%   |
| Apple                           | 11        | 0.72%   |
| Cambridge Silicon Radio         | 10        | 0.66%   |
| USI                             | 7         | 0.46%   |
| Foxconn International           | 7         | 0.46%   |
| Alps Electric                   | 6         | 0.39%   |
| Toshiba                         | 5         | 0.33%   |
| Realtek                         | 4         | 0.26%   |
| Ralink Technology               | 3         | 0.2%    |
| Micro Star International        | 2         | 0.13%   |
| Mercucys                        | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 292       | 19.15%  |
| Intel AX201 Bluetooth                               | 129       | 8.46%   |
| Realtek Bluetooth Radio                             | 116       | 7.61%   |
| Intel AX200 Bluetooth                               | 106       | 6.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 87        | 5.7%    |
| Intel Bluetooth Device                              | 72        | 4.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 43        | 2.82%   |
| IMC Networks Bluetooth Radio                        | 32        | 2.1%    |
| IMC Networks Wireless_Device                        | 28        | 1.84%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 27        | 1.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 1.51%   |
| IMC Networks Bluetooth Device                       | 23        | 1.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 1.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 1.25%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 1.25%   |
| Intel AX210 Bluetooth                               | 18        | 1.18%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 17        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.05%   |
| Ralink RT3290 Bluetooth                             | 14        | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.92%   |
| Dell DW375 Bluetooth Module                         | 14        | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                    | 12        | 0.79%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.72%   |
| MediaTek Wireless_Device                            | 11        | 0.72%   |
| Lite-On Wireless_Device                             | 11        | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.59%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 8         | 0.52%   |
| USI Bluetooth Device                                | 7         | 0.46%   |
| Qualcomm Atheros Bluetooth                          | 7         | 0.46%   |
| Lite-On Bluetooth Device                            | 7         | 0.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1500      | 61.53%  |
| AMD                                  | 451       | 18.5%   |
| Nvidia                               | 266       | 10.91%  |
| Lenovo                               | 39        | 1.6%    |
| C-Media Electronics                  | 29        | 1.19%   |
| Realtek Semiconductor                | 28        | 1.15%   |
| GN Netcom                            | 22        | 0.9%    |
| Logitech                             | 12        | 0.49%   |
| Hewlett-Packard                      | 11        | 0.45%   |
| JMTek                                | 9         | 0.37%   |
| Kingston Technology                  | 5         | 0.21%   |
| Creative Technology                  | 5         | 0.21%   |
| Plantronics                          | 4         | 0.16%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.12%   |
| DSEA A/S                             | 3         | 0.12%   |
| BEHRINGER International              | 3         | 0.12%   |
| Yamaha                               | 2         | 0.08%   |
| Texas Instruments                    | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| RODE Microphones                     | 2         | 0.08%   |
| Razer USA                            | 2         | 0.08%   |
| Harman                               | 2         | 0.08%   |
| GYROCOM C&C                          | 2         | 0.08%   |
| Fujitsu                              | 2         | 0.08%   |
| Dell                                 | 2         | 0.08%   |
| ZOOM                                 | 1         | 0.04%   |
| Yealink Network Technology           | 1         | 0.04%   |
| VIA Technologies                     | 1         | 0.04%   |
| Trust                                | 1         | 0.04%   |
| Toshiba                              | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Syntek                               | 1         | 0.04%   |
| Synaptics                            | 1         | 0.04%   |
| SteelSeries ApS                      | 1         | 0.04%   |
| SM950 Microphon                      | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| Samson Technologies                  | 1         | 0.04%   |
| Orbbec 3D Technology International   | 1         | 0.04%   |
| Numark                               | 1         | 0.04%   |
| Medeli Electronics                   | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 288       | 9.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 226       | 7.68%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 195       | 6.63%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 159       | 5.4%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 125       | 4.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 83        | 2.82%   |
| AMD Radeon High Definition Audio Controller                                                       | 73        | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 68        | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 66        | 2.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 62        | 2.11%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 62        | 2.11%   |
| Intel 8 Series HD Audio Controller                                                                | 62        | 2.11%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 57        | 1.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 53        | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 52        | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 51        | 1.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 48        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 48        | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 42        | 1.43%   |
| AMD FCH Azalia Controller                                                                         | 41        | 1.39%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 40        | 1.36%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 38        | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 35        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 34        | 1.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 34        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 33        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 32        | 1.09%   |
| AMD High Definition Audio Controller                                                              | 31        | 1.05%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 29        | 0.99%   |
| Realtek Semiconductor USB Audio                                                                   | 28        | 0.95%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 28        | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 28        | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 27        | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 26        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 25        | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 25        | 0.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 23        | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 23        | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.65%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 18        | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 341       | 24.95%  |
| SK hynix             | 295       | 21.58%  |
| Micron Technology    | 187       | 13.68%  |
| Elpida               | 150       | 10.97%  |
| Kingston             | 147       | 10.75%  |
| Unknown              | 54        | 3.95%   |
| Crucial              | 50        | 3.66%   |
| Ramaxel Technology   | 33        | 2.41%   |
| Unknown (ABCD)       | 20        | 1.46%   |
| Nanya Technology     | 19        | 1.39%   |
| A-DATA Technology    | 18        | 1.32%   |
| Corsair              | 13        | 0.95%   |
| Patriot              | 10        | 0.73%   |
| Unknown              | 6         | 0.44%   |
| Transcend            | 3         | 0.22%   |
| GOODRAM              | 2         | 0.15%   |
| fef5                 | 2         | 0.15%   |
| ASint Technology     | 2         | 0.15%   |
| Unknown (AB)         | 1         | 0.07%   |
| Unifosa              | 1         | 0.07%   |
| SHARETRONIC          | 1         | 0.07%   |
| RZX                  | 1         | 0.07%   |
| Qimonda              | 1         | 0.07%   |
| ProMos/Mosel Vitelic | 1         | 0.07%   |
| OnBoard              | 1         | 0.07%   |
| Nayna                | 1         | 0.07%   |
| Lexar Co Limited     | 1         | 0.07%   |
| Lexar                | 1         | 0.07%   |
| GSkill               | 1         | 0.07%   |
| Golden Empire        | 1         | 0.07%   |
| G.Skill              | 1         | 0.07%   |
| Apacer               | 1         | 0.07%   |
| 48spaces             | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 129       | 9.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 22        | 1.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 20        | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 19        | 1.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 17        | 1.19%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 0.84%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.84%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 11        | 0.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.7%    |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 9         | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 9         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 9         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.56%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 7         | 0.49%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.49%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 7         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.49%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.49%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 7         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.42%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 6         | 0.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.42%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.42%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.42%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 6         | 0.42%   |
| Micron RAM MT62F2G32D4DS-026 WT 8GiB SODIMM LPDDR5 7500MT/s      | 6         | 0.42%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 6         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 520       | 44.14%  |
| DDR3    | 389       | 33.02%  |
| LPDDR4  | 76        | 6.45%   |
| LPDDR5  | 48        | 4.07%   |
| DDR5    | 43        | 3.65%   |
| DDR2    | 40        | 3.4%    |
| SDRAM   | 28        | 2.38%   |
| LPDDR3  | 24        | 2.04%   |
| DDR     | 5         | 0.42%   |
| Unknown | 5         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1046      | 88.72%  |
| Row Of Chips | 113       | 9.58%   |
| Chip         | 11        | 0.93%   |
| Unknown      | 5         | 0.42%   |
| DIMM         | 4         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 437       | 34.57%  |
| 4096  | 259       | 20.49%  |
| 2048  | 236       | 18.67%  |
| 16384 | 234       | 18.51%  |
| 32768 | 61        | 4.83%   |
| 1024  | 30        | 2.37%   |
| 512   | 3         | 0.24%   |
| 12288 | 1         | 0.08%   |
| 6144  | 1         | 0.08%   |
| 3072  | 1         | 0.08%   |
| 256   | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 283       | 22.51%  |
| 1600    | 177       | 14.08%  |
| 2667    | 173       | 13.76%  |
| 1333    | 159       | 12.65%  |
| 2400    | 91        | 7.24%   |
| 2133    | 45        | 3.58%   |
| 1334    | 36        | 2.86%   |
| 5600    | 32        | 2.55%   |
| 4267    | 25        | 1.99%   |
| 6400    | 19        | 1.51%   |
| 3266    | 19        | 1.51%   |
| 667     | 19        | 1.51%   |
| Unknown | 18        | 1.43%   |
| 7500    | 17        | 1.35%   |
| 1067    | 17        | 1.35%   |
| 8400    | 15        | 1.19%   |
| 2048    | 14        | 1.11%   |
| 1867    | 14        | 1.11%   |
| 4800    | 13        | 1.03%   |
| 4266    | 13        | 1.03%   |
| 800     | 11        | 0.88%   |
| 4199    | 10        | 0.8%    |
| 8533    | 7         | 0.56%   |
| 975     | 6         | 0.48%   |
| 533     | 6         | 0.48%   |
| 1066    | 5         | 0.4%    |
| 3733    | 3         | 0.24%   |
| 8600    | 2         | 0.16%   |
| 7467    | 2         | 0.16%   |
| 2933    | 2         | 0.16%   |
| 1639    | 2         | 0.16%   |
| 5500    | 1         | 0.08%   |
| 1400    | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 4         | 44.44%  |
| Xerox               | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| QinHeng Electronics | 1         | 11.11%  |
| Prolific Technology | 1         | 11.11%  |
| Hewlett-Packard     | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Xerox Phaser 3260                | 1         | 11.11%  |
| Samsung M2070 Series             | 1         | 11.11%  |
| QinHeng CH340S                   | 1         | 11.11%  |
| Prolific PL2305 Parallel Port    | 1         | 11.11%  |
| HP LaserJet Professional P 1102w | 1         | 11.11%  |
| Canon MF645C                     | 1         | 11.11%  |
| Canon MB2100 series              | 1         | 11.11%  |
| Canon LBP3010/LBP3018/LBP3050    | 1         | 11.11%  |
| Canon G2020 series               | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| HP ScanJet 4070 PhotoSmart | 1         | 33.33%  |
| Canon CanoScan LiDE 220    | 1         | 33.33%  |
| Canon CanoScan LiDE 110    | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 427       | 26.52%  |
| Realtek Semiconductor                  | 153       | 9.5%    |
| Bison Electronics                      | 152       | 9.44%   |
| IMC Networks                           | 143       | 8.88%   |
| Microdia                               | 136       | 8.45%   |
| Sunplus Innovation Technology          | 98        | 6.09%   |
| Quanta                                 | 76        | 4.72%   |
| Lite-On Technology                     | 58        | 3.6%    |
| Syntek                                 | 57        | 3.54%   |
| Cheng Uei Precision Industry (Foxlink) | 53        | 3.29%   |
| Suyin                                  | 45        | 2.8%    |
| Luxvisions Innotech Limited            | 42        | 2.61%   |
| Apple                                  | 19        | 1.18%   |
| Ricoh                                  | 15        | 0.93%   |
| Alcor Micro                            | 15        | 0.93%   |
| Lenovo                                 | 14        | 0.87%   |
| Sonix Technology                       | 13        | 0.81%   |
| ShineTech                              | 9         | 0.56%   |
| Logitech                               | 9         | 0.56%   |
| Samsung Electronics                    | 8         | 0.5%    |
| Acer                                   | 8         | 0.5%    |
| Primax Electronics                     | 7         | 0.43%   |
| icSpring                               | 7         | 0.43%   |
| Silicon Motion                         | 5         | 0.31%   |
| BillionPixels                          | 3         | 0.19%   |
| Sunplus Technology                     | 2         | 0.12%   |
| Microsoft                              | 2         | 0.12%   |
| KYE Systems (Mouse Systems)            | 2         | 0.12%   |
| Intel                                  | 2         | 0.12%   |
| Genesys Logic                          | 2         | 0.12%   |
| DigiTech                               | 2         | 0.12%   |
| Creative Technology                    | 2         | 0.12%   |
| ALi                                    | 2         | 0.12%   |
| Z-Star Microelectronics                | 1         | 0.06%   |
| vivo                                   | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Shine-optics                           | 1         | 0.06%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.06%   |
| Ruision                                | 1         | 0.06%   |
| Pixart Imaging                         | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 121       | 7.48%   |
| Microdia Integrated_Webcam_HD                     | 63        | 3.89%   |
| IMC Networks Integrated Camera                    | 61        | 3.77%   |
| Realtek Integrated_Webcam_HD                      | 47        | 2.9%    |
| Bison Integrated Camera                           | 43        | 2.66%   |
| Chicony HP HD Camera                              | 42        | 2.6%    |
| Chicony HD WebCam                                 | 38        | 2.35%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 34        | 2.1%    |
| Syntek Integrated Camera                          | 32        | 1.98%   |
| Lite-On HP HD Camera                              | 27        | 1.67%   |
| Bison Lenovo EasyCamera                           | 24        | 1.48%   |
| Sunplus Integrated_Webcam_HD                      | 21        | 1.3%    |
| Quanta HD User Facing                             | 19        | 1.17%   |
| Chicony Integrated Camera (1280x720@30)           | 19        | 1.17%   |
| Quanta HP HD Camera                               | 17        | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 17        | 1.05%   |
| Bison SunplusIT Integrated Camera                 | 17        | 1.05%   |
| Microdia Integrated Webcam                        | 16        | 0.99%   |
| Lite-On Integrated Camera                         | 16        | 0.99%   |
| Bison Lenovo Integrated Webcam                    | 16        | 0.99%   |
| Syntek Lenovo EasyCamera                          | 15        | 0.93%   |
| Sunplus HD WebCam                                 | 15        | 0.93%   |
| Chicony FJ Camera                                 | 15        | 0.93%   |
| Suyin Acer/HP Integrated Webcam [CN0314]          | 14        | 0.87%   |
| Chicony USB2.0 VGA UVC WebCam                     | 14        | 0.87%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 13        | 0.8%    |
| Realtek USB2.0 camera                             | 10        | 0.62%   |
| Realtek USB Camera                                | 10        | 0.62%   |
| Realtek Integrated Webcam HD                      | 10        | 0.62%   |
| Microdia Sonix USB 2.0 Camera                     | 10        | 0.62%   |
| Microdia Integrated_Webcam_FHD                    | 10        | 0.62%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 10        | 0.62%   |
| Luxvisions Innotech Limited Integrated Camera     | 10        | 0.62%   |
| Chicony Lenovo EasyCamera                         | 10        | 0.62%   |
| Bison Integrated RGB Camera                       | 10        | 0.62%   |
| Sonix USB2.0 HD UVC WebCam                        | 9         | 0.56%   |
| Quanta HD Webcam                                  | 9         | 0.56%   |
| Chicony HP HD Webcam                              | 9         | 0.56%   |
| Sunplus Laptop Integrated Webcam HD               | 8         | 0.49%   |
| Sunplus Asus Webcam                               | 8         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 152       | 37.16%  |
| Validity Sensors                   | 136       | 33.25%  |
| Shenzhen Goodix Technology         | 42        | 10.27%  |
| AuthenTec                          | 34        | 8.31%   |
| Upek                               | 18        | 4.4%    |
| Elan Microelectronics              | 13        | 3.18%   |
| LighTuning Technology              | 8         | 1.96%   |
| STMicroelectronics                 | 3         | 0.73%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.49%   |
| Microsoft                          | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 10.02%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 9.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 29        | 7.09%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 26        | 6.36%   |
| Shenzhen Goodix  Fingerprint Device                                        | 22        | 5.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 20        | 4.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 4.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 17        | 4.16%   |
| Synaptics Fingerprint reader [HP G6]                                       | 15        | 3.67%   |
| AuthenTec AES2810                                                          | 15        | 3.67%   |
| Validity Sensors VFS491                                                    | 13        | 3.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 2.93%   |
| Synaptics UWP WBDI Device                                                  | 10        | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 2.44%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 2.2%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.96%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.96%   |
| AuthenTec AES1600                                                          | 8         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.71%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.22%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 0.98%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.98%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.98%   |
| Synaptics  WBDI                                                            | 4         | 0.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 0.73%   |
| Synaptics WBDI                                                             | 3         | 0.73%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.49%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.24%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.24%   |
| Synaptics WBDI Device                                                      | 1         | 0.24%   |
| Synaptics UWP WBDI                                                         | 1         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 112       | 53.59%  |
| Alcor Micro               | 60        | 28.71%  |
| O2 Micro                  | 15        | 7.18%   |
| Lenovo                    | 9         | 4.31%   |
| Upek                      | 7         | 3.35%   |
| SCM Microsystems          | 2         | 0.96%   |
| Yubico.com                | 1         | 0.48%   |
| Purism, SPC               | 1         | 0.48%   |
| Gemalto (was Gemplus)     | 1         | 0.48%   |
| Aladdin Knowledge Systems | 1         | 0.48%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 28.57%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 30        | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 12.86%  |
| Broadcom 5880                                                                | 27        | 12.86%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 7.62%   |
| Broadcom 58200                                                               | 13        | 6.19%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 5.71%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 4.29%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.43%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.95%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.48%   |
| Purism, SPC Librem Key                                                       | 1         | 0.48%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.48%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.48%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1117      | 56.07%  |
| 1     | 656       | 32.93%  |
| 2     | 179       | 8.99%   |
| 3     | 31        | 1.56%   |
| 4     | 5         | 0.25%   |
| 5     | 3         | 0.15%   |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 400       | 36.04%  |
| Graphics card            | 234       | 21.08%  |
| Chipcard                 | 178       | 16.04%  |
| Net/wireless             | 74        | 6.67%   |
| Multimedia controller    | 56        | 5.05%   |
| Camera                   | 33        | 2.97%   |
| Storage                  | 28        | 2.52%   |
| Bluetooth                | 28        | 2.52%   |
| Communication controller | 24        | 2.16%   |
| Card reader              | 22        | 1.98%   |
| Flash memory             | 9         | 0.81%   |
| Net/ethernet             | 7         | 0.63%   |
| Modem                    | 7         | 0.63%   |
| Sound                    | 6         | 0.54%   |
| Network                  | 2         | 0.18%   |
| Storage/ata              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

