Linux in Brazil - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 11159

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Acer          | Aspire E5-574G              | [8ca78da386](https://linux-hardware.org/?probe=8ca78da386) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| Valve         | Jupiter                     | [c1e32f24ee](https://linux-hardware.org/?probe=c1e32f24ee) | Jun 10, 2023 |
| Acer          | Nitro AN515-44              | [b3531502a8](https://linux-hardware.org/?probe=b3531502a8) | Jun 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [0b0c11a052](https://linux-hardware.org/?probe=0b0c11a052) | Jun 09, 2023 |
| Dell          | Vostro 3460                 | [e8ed8e8b1e](https://linux-hardware.org/?probe=e8ed8e8b1e) | Jun 09, 2023 |
| Dell          | Vostro 1310                 | [05fc6f167c](https://linux-hardware.org/?probe=05fc6f167c) | Jun 09, 2023 |
| Digibras      | NH4CU03                     | [c66d30943e](https://linux-hardware.org/?probe=c66d30943e) | Jun 09, 2023 |
| Dell          | Latitude E7240              | [1d8eb4fce4](https://linux-hardware.org/?probe=1d8eb4fce4) | Jun 09, 2023 |
| Dell          | Latitude E7240              | [da22551dca](https://linux-hardware.org/?probe=da22551dca) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [6b42200bee](https://linux-hardware.org/?probe=6b42200bee) | Jun 09, 2023 |
| Acer          | TravelMate P449-G2-M        | [0fa009ad04](https://linux-hardware.org/?probe=0fa009ad04) | Jun 08, 2023 |
| Dell          | G15 5520                    | [2410d016d6](https://linux-hardware.org/?probe=2410d016d6) | Jun 08, 2023 |
| Dell          | G15 5520                    | [8d48df5869](https://linux-hardware.org/?probe=8d48df5869) | Jun 07, 2023 |
| Dell          | Inspiron 15 5510            | [98d7cb7ea7](https://linux-hardware.org/?probe=98d7cb7ea7) | Jun 07, 2023 |
| Toshiba       | Satellite C855-233          | [fb90f9aa02](https://linux-hardware.org/?probe=fb90f9aa02) | Jun 07, 2023 |
| Dell          | Inspiron 5548               | [e67581e121](https://linux-hardware.org/?probe=e67581e121) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Google        | Chell                       | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| Acer          | Predator PH315-52           | [f7178495c7](https://linux-hardware.org/?probe=f7178495c7) | Jun 07, 2023 |
| Positivo      | Mobile                      | [12d5c3248c](https://linux-hardware.org/?probe=12d5c3248c) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [2f138401f6](https://linux-hardware.org/?probe=2f138401f6) | Jun 06, 2023 |
| HP            | Laptop 14s-dq1xxx           | [8f99826bf1](https://linux-hardware.org/?probe=8f99826bf1) | Jun 06, 2023 |
| Notebook      | NJx0MU                      | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| Apple         | MacBookAir7,2               | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| Compaq        | CQ-27                       | [ae3d9bce8c](https://linux-hardware.org/?probe=ae3d9bce8c) | Jun 05, 2023 |
| Acer          | Nitro AN515-52              | [e9d79e576b](https://linux-hardware.org/?probe=e9d79e576b) | Jun 05, 2023 |
| ASUSTek       | VX7SX                       | [ddf3010e73](https://linux-hardware.org/?probe=ddf3010e73) | Jun 05, 2023 |
| Samsung       | 950XEE                      | [cc47fd0df0](https://linux-hardware.org/?probe=cc47fd0df0) | Jun 05, 2023 |
| Notebook      | NJx0MU                      | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Acer          | Aspire A315-42G             | [eb67866c74](https://linux-hardware.org/?probe=eb67866c74) | Jun 05, 2023 |
| Dell          | Latitude 3410               | [820e62c9d3](https://linux-hardware.org/?probe=820e62c9d3) | Jun 04, 2023 |
| Dell          | Latitude 3410               | [12515d41c8](https://linux-hardware.org/?probe=12515d41c8) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Dell          | Inspiron 5437               | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Compaq        | 420                         | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Samsung       | 670Z5E                      | [647589cbbd](https://linux-hardware.org/?probe=647589cbbd) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [3c92b81349](https://linux-hardware.org/?probe=3c92b81349) | Jun 02, 2023 |
| Dell          | Inspiron N4030              | [1aca93ba38](https://linux-hardware.org/?probe=1aca93ba38) | Jun 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [664282cc84](https://linux-hardware.org/?probe=664282cc84) | Jun 02, 2023 |
| Dell          | G15 5520                    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| Acer          | Nitro AN515-51              | [2dc3c08466](https://linux-hardware.org/?probe=2dc3c08466) | Jun 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [55c7d4b615](https://linux-hardware.org/?probe=55c7d4b615) | Jun 02, 2023 |
| HP            | 420                         | [0e369b273b](https://linux-hardware.org/?probe=0e369b273b) | Jun 02, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [ea337d3d2a](https://linux-hardware.org/?probe=ea337d3d2a) | Jun 02, 2023 |
| Lenovo        | G400s VILG1                 | [fee541ee18](https://linux-hardware.org/?probe=fee541ee18) | Jun 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [33e440f44f](https://linux-hardware.org/?probe=33e440f44f) | Jun 01, 2023 |
| HP            | Pavilion dv6600             | [5e2867ee61](https://linux-hardware.org/?probe=5e2867ee61) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | [17621fb846](https://linux-hardware.org/?probe=17621fb846) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Samsung       | 300E5K/300E5Q               | [00d2d07850](https://linux-hardware.org/?probe=00d2d07850) | May 31, 2023 |
| Unknown       | Unknown                     | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| HP            | Pavilion dv4                | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Apple         | MacBookPro7,1               | [4fc174a983](https://linux-hardware.org/?probe=4fc174a983) | May 31, 2023 |
| Toshiba       | IS 1413G                    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | TravelMate P449-G2-M        | [41177ef027](https://linux-hardware.org/?probe=41177ef027) | May 31, 2023 |
| Notebook      | NJx0MU                      | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b457302ec](https://linux-hardware.org/?probe=1b457302ec) | May 31, 2023 |
| Acer          | Nitro AN515-51              | [d3ee3757e0](https://linux-hardware.org/?probe=d3ee3757e0) | May 30, 2023 |
| Notebook      | P15SM-A/SM1-A               | [e71d8e3bc0](https://linux-hardware.org/?probe=e71d8e3bc0) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Unknown       | Unknown                     | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| Samsung       | RV419/RV420                 | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| Notebook      | NJx0MU                      | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Dell          | Inspiron 1525               | [29d2e377ad](https://linux-hardware.org/?probe=29d2e377ad) | May 29, 2023 |
| Acer          | Aspire A515-57              | [e9f91331b2](https://linux-hardware.org/?probe=e9f91331b2) | May 29, 2023 |
| Avell High... | A70 MOB                     | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | Inspiron 1525               | [7adfc9796d](https://linux-hardware.org/?probe=7adfc9796d) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [981a09e39a](https://linux-hardware.org/?probe=981a09e39a) | May 29, 2023 |
| Sony          | VPCSA25GB                   | [e36e944a92](https://linux-hardware.org/?probe=e36e944a92) | May 29, 2023 |
| Dell          | Inspiron 5447               | [270e3cd993](https://linux-hardware.org/?probe=270e3cd993) | May 29, 2023 |
| HP            | Pavilion g4                 | [12bef484db](https://linux-hardware.org/?probe=12bef484db) | May 29, 2023 |
| Notebook      | NJx0MU                      | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [14e5763b6f](https://linux-hardware.org/?probe=14e5763b6f) | May 29, 2023 |
| Apple         | MacBookAir5,1               | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| Dell          | Inspiron 1525               | [99540846c4](https://linux-hardware.org/?probe=99540846c4) | May 28, 2023 |
| Dell          | Inspiron 1525               | [99c9a792f5](https://linux-hardware.org/?probe=99c9a792f5) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [95793a85de](https://linux-hardware.org/?probe=95793a85de) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [7c9addaf1c](https://linux-hardware.org/?probe=7c9addaf1c) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [1b4eb11af8](https://linux-hardware.org/?probe=1b4eb11af8) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [77e5b682ff](https://linux-hardware.org/?probe=77e5b682ff) | May 28, 2023 |
| Unknown       | Unknown                     | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Positivo      | N1250                       | [f014b93eba](https://linux-hardware.org/?probe=f014b93eba) | May 28, 2023 |
| Dell          | Inspiron 5421               | [c559e851a2](https://linux-hardware.org/?probe=c559e851a2) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| Dell          | Vostro 5402                 | [41a9c1dcf2](https://linux-hardware.org/?probe=41a9c1dcf2) | May 28, 2023 |
| Acer          | Aspire A515-45              | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Latitude 7490               | [fbad4c1a53](https://linux-hardware.org/?probe=fbad4c1a53) | May 27, 2023 |
| Dell          | Latitude 7490               | [00c44ed00c](https://linux-hardware.org/?probe=00c44ed00c) | May 27, 2023 |
| Positivo      | C14CR21TV                   | [f3907d940d](https://linux-hardware.org/?probe=f3907d940d) | May 27, 2023 |
| HP            | 1000                        | [f3b014fa71](https://linux-hardware.org/?probe=f3b014fa71) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [82cad47c63](https://linux-hardware.org/?probe=82cad47c63) | May 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [09cc59aa19](https://linux-hardware.org/?probe=09cc59aa19) | May 27, 2023 |
| HP            | Pavilion dm4                | [708daa02e2](https://linux-hardware.org/?probe=708daa02e2) | May 26, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [8b93a6ab33](https://linux-hardware.org/?probe=8b93a6ab33) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Itautec       | Infoway                     | [03be6afc10](https://linux-hardware.org/?probe=03be6afc10) | May 26, 2023 |
| Dell          | Inspiron 15-3567            | [0f79b43742](https://linux-hardware.org/?probe=0f79b43742) | May 26, 2023 |
| Samsung       | 550XDA                      | [6cc9f3cbe4](https://linux-hardware.org/?probe=6cc9f3cbe4) | May 26, 2023 |
| Acer          | Predator PT316-51s          | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| HP            | ProBook 645 G1              | [347779f3bf](https://linux-hardware.org/?probe=347779f3bf) | May 26, 2023 |
| A14CR         | Unknown                     | [a504061244](https://linux-hardware.org/?probe=a504061244) | May 25, 2023 |
| Clevo         | P150HMx                     | [d6c90a2c0c](https://linux-hardware.org/?probe=d6c90a2c0c) | May 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ffdb62c45](https://linux-hardware.org/?probe=0ffdb62c45) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [3304e68c39](https://linux-hardware.org/?probe=3304e68c39) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [c885a13922](https://linux-hardware.org/?probe=c885a13922) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [897b688aba](https://linux-hardware.org/?probe=897b688aba) | May 25, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | [dc91cb92af](https://linux-hardware.org/?probe=dc91cb92af) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86666c3371](https://linux-hardware.org/?probe=86666c3371) | May 24, 2023 |
| Avell High... | A72 HYB                     | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| Dell          | XPS 13 9300                 | [255811069a](https://linux-hardware.org/?probe=255811069a) | May 23, 2023 |
| Dell          | Inspiron 3583               | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| Dell          | Vostro 5402                 | [e6834866ba](https://linux-hardware.org/?probe=e6834866ba) | May 23, 2023 |
| Dell          | Inspiron 1525               | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| Chuwi         | HeroBook Air                | [724db856f3](https://linux-hardware.org/?probe=724db856f3) | May 23, 2023 |
| Notebook      | NJx0MU                      | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Dell          | Inspiron 1525               | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84717aefdf](https://linux-hardware.org/?probe=84717aefdf) | May 22, 2023 |
| Acer          | Swift SF514-56T             | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Inspiron 3443               | [35923f74b5](https://linux-hardware.org/?probe=35923f74b5) | May 22, 2023 |
| Dell          | Inspiron 7520               | [eeca18ff12](https://linux-hardware.org/?probe=eeca18ff12) | May 22, 2023 |
| Samsung       | 300E5M/300E5L               | [ebd65238d8](https://linux-hardware.org/?probe=ebd65238d8) | May 22, 2023 |
| Notebook      | NJx0MU                      | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| Philco        | 14H                         | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Dell          | XPS 13 9310                 | [19be933f8a](https://linux-hardware.org/?probe=19be933f8a) | May 21, 2023 |
| Toshiba       | IS 1413G                    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| Acer          | Nitro AN517-54              | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| Acer          | Nitro AN515-54              | [4f27fb9c64](https://linux-hardware.org/?probe=4f27fb9c64) | May 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| Acer          | Aspire A315-42G             | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3442               | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Avell High... | A40 LIV                     | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| Dell          | Vostro 15 3515              | [6b5bc55aeb](https://linux-hardware.org/?probe=6b5bc55aeb) | May 18, 2023 |
| Dell          | Vostro 15 3515              | [e26f4ecf2f](https://linux-hardware.org/?probe=e26f4ecf2f) | May 18, 2023 |
| Lenovo        | ThinkPad T400 2767E53       | [5cd6c87b7e](https://linux-hardware.org/?probe=5cd6c87b7e) | May 18, 2023 |
| Dell          | Vostro 15 3510              | [e5e7213107](https://linux-hardware.org/?probe=e5e7213107) | May 18, 2023 |
| Lenovo        | ThinkPad T490s 20NXS01Y0... | [277ed003ce](https://linux-hardware.org/?probe=277ed003ce) | May 18, 2023 |
| Dell          | Inspiron 3583               | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| Clevo         | P150HMx                     | [17e11751ef](https://linux-hardware.org/?probe=17e11751ef) | May 18, 2023 |
| Clevo         | P150HMx                     | [f749300168](https://linux-hardware.org/?probe=f749300168) | May 18, 2023 |
| Lenovo        | IdeaPad Z470                | [158feeb98d](https://linux-hardware.org/?probe=158feeb98d) | May 18, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [681fd36c12](https://linux-hardware.org/?probe=681fd36c12) | May 18, 2023 |
| Dell          | Inspiron 15 3511            | [255961cb74](https://linux-hardware.org/?probe=255961cb74) | May 18, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a167afa608](https://linux-hardware.org/?probe=a167afa608) | May 17, 2023 |
| Acer          | Nitro AN517-54              | [9372615767](https://linux-hardware.org/?probe=9372615767) | May 17, 2023 |
| Dell          | Latitude E7240              | [1990186432](https://linux-hardware.org/?probe=1990186432) | May 17, 2023 |
| Dell          | Inspiron 15-7568            | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Dell          | Latitude 5420               | [ddd072b69c](https://linux-hardware.org/?probe=ddd072b69c) | May 16, 2023 |
| Acer          | Aspire 5050                 | [44f9abca04](https://linux-hardware.org/?probe=44f9abca04) | May 16, 2023 |
| Dell          | Latitude 7420               | [4e1680877b](https://linux-hardware.org/?probe=4e1680877b) | May 16, 2023 |
| Samsung       | 550XDA                      | [75bc1cdfb3](https://linux-hardware.org/?probe=75bc1cdfb3) | May 16, 2023 |
| Acer          | Aspire E5-571               | [6094f7a191](https://linux-hardware.org/?probe=6094f7a191) | May 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [055aae99b8](https://linux-hardware.org/?probe=055aae99b8) | May 16, 2023 |
| Toshiba       | IS 1413G                    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| PHILCO ELE... | PNB15.6AP34H1W10            | [4c4c7467ec](https://linux-hardware.org/?probe=4c4c7467ec) | May 16, 2023 |
| Positivo      | Q4128C-S                    | [05c0522fe3](https://linux-hardware.org/?probe=05c0522fe3) | May 16, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [fe4f47ccc9](https://linux-hardware.org/?probe=fe4f47ccc9) | May 15, 2023 |
| Dell          | Inspiron 3542               | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| Dell          | G3 3590                     | [75a6a8a107](https://linux-hardware.org/?probe=75a6a8a107) | May 15, 2023 |
| Acer          | Aspire A515-45              | [2375fac142](https://linux-hardware.org/?probe=2375fac142) | May 15, 2023 |
| Dell          | G3 3590                     | [b19462038d](https://linux-hardware.org/?probe=b19462038d) | May 15, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [f199f11aa5](https://linux-hardware.org/?probe=f199f11aa5) | May 15, 2023 |
| Acer          | AO532h                      | [6cfe2a58cc](https://linux-hardware.org/?probe=6cfe2a58cc) | May 15, 2023 |
| Dell          | Inspiron N5010              | [98f448ed70](https://linux-hardware.org/?probe=98f448ed70) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5dadcb24d0](https://linux-hardware.org/?probe=5dadcb24d0) | May 15, 2023 |
| Valve         | Jupiter                     | [dca8b16469](https://linux-hardware.org/?probe=dca8b16469) | May 15, 2023 |
| ASUSTek       | K45VM                       | [eaef457c8a](https://linux-hardware.org/?probe=eaef457c8a) | May 15, 2023 |
| Dell          | G15 5510                    | [5624d414be](https://linux-hardware.org/?probe=5624d414be) | May 15, 2023 |
| Notebook      | NJx0MU                      | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| Dell          | Inspiron 3583               | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| Lenovo        | ThinkPad T420 4236PJ2       | [22a9e8213e](https://linux-hardware.org/?probe=22a9e8213e) | May 14, 2023 |
| Intel         | W7650                       | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Notebook      | NJx0MU                      | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Dell          | Vostro 5471                 | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Toshiba       | IS 1413G                    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| Dell          | System Inspiron N4120       | [c7f1c9e542](https://linux-hardware.org/?probe=c7f1c9e542) | May 14, 2023 |
| Acer          | Aspire A315-23              | [64237b5d6e](https://linux-hardware.org/?probe=64237b5d6e) | May 14, 2023 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [9eb38c956d](https://linux-hardware.org/?probe=9eb38c956d) | May 14, 2023 |
| HP            | Compaq Presario CQ40        | [22d379cd2f](https://linux-hardware.org/?probe=22d379cd2f) | May 13, 2023 |
| Samsung       | 550XDA                      | [5f562807be](https://linux-hardware.org/?probe=5f562807be) | May 13, 2023 |
| Notebook      | NJx0MU                      | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Dell          | Inspiron 7580               | [01d9730a88](https://linux-hardware.org/?probe=01d9730a88) | May 12, 2023 |
| Toshiba       | STI NA 1401                 | [c9aa3a7539](https://linux-hardware.org/?probe=c9aa3a7539) | May 12, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [ee8fe21e76](https://linux-hardware.org/?probe=ee8fe21e76) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| Positivo      | J14GL11                     | [bfdf0df9b8](https://linux-hardware.org/?probe=bfdf0df9b8) | May 12, 2023 |
| Multilaser    | PC150                       | [0a59946a8f](https://linux-hardware.org/?probe=0a59946a8f) | May 12, 2023 |
| Positivo      | J14GL11                     | [9594837399](https://linux-hardware.org/?probe=9594837399) | May 11, 2023 |
| Itautec       | Infoway w7440               | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Alienware     | m15 R6                      | [bfa28cc7bd](https://linux-hardware.org/?probe=bfa28cc7bd) | May 11, 2023 |
| Alienware     | m15 R7                      | [d481f5a70d](https://linux-hardware.org/?probe=d481f5a70d) | May 10, 2023 |
| Dell          | Inspiron 5590               | [117a2b318d](https://linux-hardware.org/?probe=117a2b318d) | May 10, 2023 |
| Dell          | Inspiron 5590               | [9c53d54cae](https://linux-hardware.org/?probe=9c53d54cae) | May 10, 2023 |
| HP            | ENVY 15                     | [ba0636efe5](https://linux-hardware.org/?probe=ba0636efe5) | May 10, 2023 |
| Dell          | Inspiron 5566               | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Dell          | Inspiron 15 5510            | [174505e46f](https://linux-hardware.org/?probe=174505e46f) | May 10, 2023 |
| Notebook      | NJx0MU                      | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| Alienware     | m15 R7                      | [cfd5f51d93](https://linux-hardware.org/?probe=cfd5f51d93) | May 09, 2023 |
| Acer          | Aspire A515-45              | [922a0d7b9e](https://linux-hardware.org/?probe=922a0d7b9e) | May 09, 2023 |
| Acer          | Aspire A515-45              | [4df8233d54](https://linux-hardware.org/?probe=4df8233d54) | May 09, 2023 |
| Avell High... | A40 LIV                     | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Acer          | Aspire A514-54              | [dafa2886a3](https://linux-hardware.org/?probe=dafa2886a3) | May 09, 2023 |
| Dell          | Inspiron 3442               | [e858474ff0](https://linux-hardware.org/?probe=e858474ff0) | May 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [205b8a8ca7](https://linux-hardware.org/?probe=205b8a8ca7) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Samsung       | 550XBE/350XBE               | [479ad5c021](https://linux-hardware.org/?probe=479ad5c021) | May 08, 2023 |
| Avell High... | A65 MOB                     | [d6c6781535](https://linux-hardware.org/?probe=d6c6781535) | May 08, 2023 |
| Avell High... | 1513                        | [6e383641d6](https://linux-hardware.org/?probe=6e383641d6) | May 08, 2023 |
| Notebook      | NJx0MU                      | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| Samsung       | 530XBB                      | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | Latitude 7490               | [c871c848b9](https://linux-hardware.org/?probe=c871c848b9) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Toshiba       | IS 1413G                    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Biostar       | A320MH                      | [5b240feaed](https://linux-hardware.org/?probe=5b240feaed) | May 07, 2023 |
| Itautec       | Infoway a7420               | [52788f2c92](https://linux-hardware.org/?probe=52788f2c92) | May 07, 2023 |
| HP            | Pavilion dm4                | [8f79a54339](https://linux-hardware.org/?probe=8f79a54339) | May 07, 2023 |
| Dell          | Vostro 14-3468              | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| Dell          | Inspiron 15-3567            | [9a510bb01b](https://linux-hardware.org/?probe=9a510bb01b) | May 06, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [696525cf17](https://linux-hardware.org/?probe=696525cf17) | May 06, 2023 |
| ASUSTek       | X441BA                      | [326309c1f1](https://linux-hardware.org/?probe=326309c1f1) | May 06, 2023 |
| ASUSTek       | X441BA                      | [dee3bc2cdb](https://linux-hardware.org/?probe=dee3bc2cdb) | May 06, 2023 |
| Acer          | Nitro AN517-54              | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [384cc356fc](https://linux-hardware.org/?probe=384cc356fc) | May 06, 2023 |
| Avell High... | A70 HYB                     | [0d871806d1](https://linux-hardware.org/?probe=0d871806d1) | May 05, 2023 |
| Avell High... | A70 HYB                     | [9519eef96f](https://linux-hardware.org/?probe=9519eef96f) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f2c390eb7e](https://linux-hardware.org/?probe=f2c390eb7e) | May 05, 2023 |
| ASUSTek       | K45VM                       | [09e73cade8](https://linux-hardware.org/?probe=09e73cade8) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7046c6c99](https://linux-hardware.org/?probe=f7046c6c99) | May 05, 2023 |
| Positivo      | N4350                       | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| Dell          | Inspiron 7520               | [2ae295d2a0](https://linux-hardware.org/?probe=2ae295d2a0) | May 05, 2023 |
| Acer          | Aspire E1-421               | [45bca26278](https://linux-hardware.org/?probe=45bca26278) | May 05, 2023 |
| Dell          | Inspiron 5490               | [a6c9c8b3b5](https://linux-hardware.org/?probe=a6c9c8b3b5) | May 05, 2023 |
| Avell High... | A40 LIV                     | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| Dell          | Inspiron 5402               | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Avell High... | C62 LIV                     | [b53a07f1a3](https://linux-hardware.org/?probe=b53a07f1a3) | May 04, 2023 |
| Acer          | Aspire A515-52G             | [4f2fbcc26f](https://linux-hardware.org/?probe=4f2fbcc26f) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | Latitude 3470               | [532cd0124e](https://linux-hardware.org/?probe=532cd0124e) | May 04, 2023 |
| Lenovo        | B490 37722XP                | [62808a2dee](https://linux-hardware.org/?probe=62808a2dee) | May 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [42c07a1fe0](https://linux-hardware.org/?probe=42c07a1fe0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [bbe569dff7](https://linux-hardware.org/?probe=bbe569dff7) | May 03, 2023 |
| ASUSTek       | X751LJ                      | [708ac49447](https://linux-hardware.org/?probe=708ac49447) | May 03, 2023 |
| ASUSTek       | X751LJ                      | [66e45eac2c](https://linux-hardware.org/?probe=66e45eac2c) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Acer          | Nitro AN517-54              | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| Toshiba       | IS 1413G                    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Adreamer      | PN1308P                     | [8ae75bc5a0](https://linux-hardware.org/?probe=8ae75bc5a0) | May 02, 2023 |
| Dell          | Inspiron 3501               | [6e70e21e58](https://linux-hardware.org/?probe=6e70e21e58) | May 02, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [143b75f514](https://linux-hardware.org/?probe=143b75f514) | May 02, 2023 |
| Samsung       | 550XDA                      | [4bea46787f](https://linux-hardware.org/?probe=4bea46787f) | May 02, 2023 |
| Notebook      | NJx0MU                      | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a5ac1bf5b4](https://linux-hardware.org/?probe=a5ac1bf5b4) | May 01, 2023 |
| Notebook      | NJx0MU                      | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| Dell          | Inspiron 5458               | [c38d3e6513](https://linux-hardware.org/?probe=c38d3e6513) | May 01, 2023 |
| Dell          | Inspiron 7460               | [696014fc68](https://linux-hardware.org/?probe=696014fc68) | May 01, 2023 |
| Notebook      | NJx0MU                      | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Acer          | Nitro AN517-54              | [593a6b247f](https://linux-hardware.org/?probe=593a6b247f) | May 01, 2023 |
| Notebook      | NJx0MU                      | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Unknown       | Unknown                     | [8978b9aa5f](https://linux-hardware.org/?probe=8978b9aa5f) | May 01, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [a7d6d782b2](https://linux-hardware.org/?probe=a7d6d782b2) | May 01, 2023 |
| Notebook      | NJx0MU                      | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| Unknown       | Unknown                     | [070854df6b](https://linux-hardware.org/?probe=070854df6b) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bd460bdc62](https://linux-hardware.org/?probe=bd460bdc62) | Apr 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [edfcd7daa6](https://linux-hardware.org/?probe=edfcd7daa6) | Apr 30, 2023 |
| Positivo      | Q464C                       | [8e41593bd3](https://linux-hardware.org/?probe=8e41593bd3) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Acer          | Nitro AN515-45              | [9b28e69254](https://linux-hardware.org/?probe=9b28e69254) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| HP            | Pavilion dm4                | [3473d4b312](https://linux-hardware.org/?probe=3473d4b312) | Apr 29, 2023 |
| Apple         | MacBookPro9,2               | [1e75efbfab](https://linux-hardware.org/?probe=1e75efbfab) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| ASUSTek       | Z550SA                      | [7c6c0c9599](https://linux-hardware.org/?probe=7c6c0c9599) | Apr 28, 2023 |
| Acer          | Aspire E5-571               | [1d36dafa86](https://linux-hardware.org/?probe=1d36dafa86) | Apr 28, 2023 |
| HP            | Presario CQ43               | [c14c79b3cf](https://linux-hardware.org/?probe=c14c79b3cf) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [6926565982](https://linux-hardware.org/?probe=6926565982) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [6a56164bfd](https://linux-hardware.org/?probe=6a56164bfd) | Apr 27, 2023 |
| Acer          | Aspire A315-54              | [8137aa9008](https://linux-hardware.org/?probe=8137aa9008) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Notebook      | NJx0MU                      | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [393c7b06d5](https://linux-hardware.org/?probe=393c7b06d5) | Apr 26, 2023 |
| Dell          | Inspiron 7580               | [d9fe7034bd](https://linux-hardware.org/?probe=d9fe7034bd) | Apr 26, 2023 |
| Dell          | G15 5510                    | [9dcb76f7c1](https://linux-hardware.org/?probe=9dcb76f7c1) | Apr 26, 2023 |
| Dell          | G15 5510                    | [4030b4f936](https://linux-hardware.org/?probe=4030b4f936) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | [7cbf188375](https://linux-hardware.org/?probe=7cbf188375) | Apr 26, 2023 |
| Apple         | MacBookAir7,2               | [b94d783285](https://linux-hardware.org/?probe=b94d783285) | Apr 26, 2023 |
| Notebook      | NJx0MU                      | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| Acer          | Nitro AN517-54              | [9fe0f33003](https://linux-hardware.org/?probe=9fe0f33003) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| HP            | Pavilion g4                 | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| Dell          | G15 5515                    | [a0dd3f2003](https://linux-hardware.org/?probe=a0dd3f2003) | Apr 25, 2023 |
| Avell High... | A70 HYB BS                  | [c7b5f9ef04](https://linux-hardware.org/?probe=c7b5f9ef04) | Apr 25, 2023 |
| Acer          | Nitro AN515-51              | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Dell          | Vostro 3550                 | [653c3c4650](https://linux-hardware.org/?probe=653c3c4650) | Apr 25, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [afcce1c52c](https://linux-hardware.org/?probe=afcce1c52c) | Apr 25, 2023 |
| Dell          | G3 3500                     | [46996524d0](https://linux-hardware.org/?probe=46996524d0) | Apr 25, 2023 |
| Purism        | Librem 14                   | [8462dbaccb](https://linux-hardware.org/?probe=8462dbaccb) | Apr 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [1b26b3f89b](https://linux-hardware.org/?probe=1b26b3f89b) | Apr 24, 2023 |
| Notebook      | N85_N87HCHNHZ               | [ecb3270b4a](https://linux-hardware.org/?probe=ecb3270b4a) | Apr 24, 2023 |
| Dell          | Vostro 15 3515              | [13c75fa32e](https://linux-hardware.org/?probe=13c75fa32e) | Apr 24, 2023 |
| Apple         | MacBookPro8,1               | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Gateway       | NV55C                       | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Dell          | Inspiron 11-3168            | [5ac6392b05](https://linux-hardware.org/?probe=5ac6392b05) | Apr 24, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e562ba35c6](https://linux-hardware.org/?probe=e562ba35c6) | Apr 23, 2023 |
| Dell          | G15 5520                    | [d2cc8527a5](https://linux-hardware.org/?probe=d2cc8527a5) | Apr 23, 2023 |
| HP            | G42                         | [1d5b2eefc3](https://linux-hardware.org/?probe=1d5b2eefc3) | Apr 23, 2023 |
| ASUSTek       | X45C                        | [759ed58d76](https://linux-hardware.org/?probe=759ed58d76) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9a92345b08](https://linux-hardware.org/?probe=9a92345b08) | Apr 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0e798db6a8](https://linux-hardware.org/?probe=0e798db6a8) | Apr 23, 2023 |
| Dell          | G15 5520                    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [8bb0353706](https://linux-hardware.org/?probe=8bb0353706) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [b699c8ed48](https://linux-hardware.org/?probe=b699c8ed48) | Apr 22, 2023 |
| LG Electro... | A530-T.BE76P1               | [f5c282ca6c](https://linux-hardware.org/?probe=f5c282ca6c) | Apr 22, 2023 |
| Dell          | G15 5520                    | [07751c950a](https://linux-hardware.org/?probe=07751c950a) | Apr 22, 2023 |
| Acer          | Nitro AN515-54              | [452177f9a5](https://linux-hardware.org/?probe=452177f9a5) | Apr 21, 2023 |
| Digibras      | NH4CU53                     | [d6571e3d78](https://linux-hardware.org/?probe=d6571e3d78) | Apr 21, 2023 |
| Multilaser    | PC13X                       | [d1144e31a1](https://linux-hardware.org/?probe=d1144e31a1) | Apr 21, 2023 |
| Positivo      | N6440                       | [b0a1fe417d](https://linux-hardware.org/?probe=b0a1fe417d) | Apr 21, 2023 |
| Dell          | Inspiron 3501               | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Dell          | XPS 13 9310                 | [55685c168f](https://linux-hardware.org/?probe=55685c168f) | Apr 20, 2023 |
| Samsung       | 550P5C/550P7C               | [3648dd39f8](https://linux-hardware.org/?probe=3648dd39f8) | Apr 20, 2023 |
| Dell          | Inspiron 7460               | [bbfe51bf3c](https://linux-hardware.org/?probe=bbfe51bf3c) | Apr 19, 2023 |
| Acer          | AO722                       | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| Dell          | Vostro 3480                 | [f2f48756e6](https://linux-hardware.org/?probe=f2f48756e6) | Apr 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [90c4ba9f6e](https://linux-hardware.org/?probe=90c4ba9f6e) | Apr 17, 2023 |
| HP            | 240 G4 Notebook PC          | [6410232c86](https://linux-hardware.org/?probe=6410232c86) | Apr 17, 2023 |
| Dell          | Latitude E5430 non-vPro     | [961e1f1908](https://linux-hardware.org/?probe=961e1f1908) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Dell          | Inspiron 5566               | [5e9ebca163](https://linux-hardware.org/?probe=5e9ebca163) | Apr 17, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [acd0161868](https://linux-hardware.org/?probe=acd0161868) | Apr 17, 2023 |
| Multilaser    | PC13X                       | [3b755838a2](https://linux-hardware.org/?probe=3b755838a2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| HP            | 240 G2                      | [ca6ae60a2b](https://linux-hardware.org/?probe=ca6ae60a2b) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Valve         | Jupiter                     | [6c83afd9b3](https://linux-hardware.org/?probe=6c83afd9b3) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Aspire A515-45              | [5ce7874f2e](https://linux-hardware.org/?probe=5ce7874f2e) | Apr 16, 2023 |
| Itautec       | Infoway                     | [c046d6e093](https://linux-hardware.org/?probe=c046d6e093) | Apr 16, 2023 |
| Positivo      | C14CR01                     | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f7cf140a28](https://linux-hardware.org/?probe=f7cf140a28) | Apr 16, 2023 |
| Acer          | Nitro AN515-54              | [73c46e2901](https://linux-hardware.org/?probe=73c46e2901) | Apr 15, 2023 |
| Dell          | Inspiron 5566               | [3decfdc1f6](https://linux-hardware.org/?probe=3decfdc1f6) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| Dell          | Inspiron 7460               | [ae861b54cd](https://linux-hardware.org/?probe=ae861b54cd) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a34f2e065b](https://linux-hardware.org/?probe=a34f2e065b) | Apr 14, 2023 |
| Avell High... | B.ON                        | [0ac252a73b](https://linux-hardware.org/?probe=0ac252a73b) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| Samsung       | 670Z5E                      | [96bcf536e6](https://linux-hardware.org/?probe=96bcf536e6) | Apr 14, 2023 |
| Samsung       | 670Z5E                      | [dff09c0918](https://linux-hardware.org/?probe=dff09c0918) | Apr 14, 2023 |
| Acer          | Nitro AN515-54              | [07a2ba2393](https://linux-hardware.org/?probe=07a2ba2393) | Apr 13, 2023 |
| Dell          | Inspiron 5515               | [e7306b2521](https://linux-hardware.org/?probe=e7306b2521) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | [c200475e1f](https://linux-hardware.org/?probe=c200475e1f) | Apr 13, 2023 |
| Acer          | Aspire A515-54G             | [eedb55e1ba](https://linux-hardware.org/?probe=eedb55e1ba) | Apr 13, 2023 |
| Dell          | Inspiron 15-3567            | [ae928fe177](https://linux-hardware.org/?probe=ae928fe177) | Apr 13, 2023 |
| Toshiba       | IS 1413G                    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Positivo      | H14SU08                     | [8e8d14728f](https://linux-hardware.org/?probe=8e8d14728f) | Apr 13, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c53ec6a9c0](https://linux-hardware.org/?probe=c53ec6a9c0) | Apr 13, 2023 |
| Positivo      | Q4128C-S                    | [a46ba9bff2](https://linux-hardware.org/?probe=a46ba9bff2) | Apr 12, 2023 |
| Positivo      | Q4128C-S                    | [3b5a11f774](https://linux-hardware.org/?probe=3b5a11f774) | Apr 12, 2023 |
| Intel         | powered classmate PC        | [79b262de52](https://linux-hardware.org/?probe=79b262de52) | Apr 12, 2023 |
| Acer          | Nitro AN515-44              | [12ca37afd3](https://linux-hardware.org/?probe=12ca37afd3) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Dell          | G3 3579                     | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Samsung       | 550XCJ/550XCR               | [c074d665d9](https://linux-hardware.org/?probe=c074d665d9) | Apr 11, 2023 |
| Samsung       | 550XCJ/550XCR               | [845a04c326](https://linux-hardware.org/?probe=845a04c326) | Apr 11, 2023 |
| Intel         | W7650                       | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| HP            | Unknown                     | [abc7d95b62](https://linux-hardware.org/?probe=abc7d95b62) | Apr 11, 2023 |
| Acer          | Aspire E5-471               | [6e44530b23](https://linux-hardware.org/?probe=6e44530b23) | Apr 11, 2023 |
| HP            | 250 G8 Notebook PC          | [a60609df80](https://linux-hardware.org/?probe=a60609df80) | Apr 11, 2023 |
| Acer          | Aspire A515-57              | [f577606375](https://linux-hardware.org/?probe=f577606375) | Apr 11, 2023 |
| Acer          | Aspire E5-471               | [dbcbf972e5](https://linux-hardware.org/?probe=dbcbf972e5) | Apr 11, 2023 |
| Dell          | Inspiron N5110              | [4506c94bfd](https://linux-hardware.org/?probe=4506c94bfd) | Apr 11, 2023 |
| Avell High... | A52 HYB                     | [0795bca947](https://linux-hardware.org/?probe=0795bca947) | Apr 11, 2023 |
| Samsung       | 550XDA                      | [e1d5d2f193](https://linux-hardware.org/?probe=e1d5d2f193) | Apr 11, 2023 |
| Acer          | Aspire E5-511               | [f66d23c175](https://linux-hardware.org/?probe=f66d23c175) | Apr 10, 2023 |
| Dell          | Inspiron 3583               | [502c993dfd](https://linux-hardware.org/?probe=502c993dfd) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | [2bb9767ca7](https://linux-hardware.org/?probe=2bb9767ca7) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | [681be67c93](https://linux-hardware.org/?probe=681be67c93) | Apr 09, 2023 |
| Acer          | Aspire 5538                 | [3128c45dbc](https://linux-hardware.org/?probe=3128c45dbc) | Apr 09, 2023 |
| Samsung       | RV419                       | [88985a3d0d](https://linux-hardware.org/?probe=88985a3d0d) | Apr 09, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | [779e8396d6](https://linux-hardware.org/?probe=779e8396d6) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Toshiba       | IS 1413G                    | [be9d1636a7](https://linux-hardware.org/?probe=be9d1636a7) | Apr 09, 2023 |
| Dell          | Inspiron N5110              | [6514811aaf](https://linux-hardware.org/?probe=6514811aaf) | Apr 09, 2023 |
| Avell High... | A52 HYB                     | [7da3b9f780](https://linux-hardware.org/?probe=7da3b9f780) | Apr 09, 2023 |
| Acer          | Aspire A515-57              | [e04fc7e8e8](https://linux-hardware.org/?probe=e04fc7e8e8) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | ProBook 6470b               | [9926dac4aa](https://linux-hardware.org/?probe=9926dac4aa) | Apr 08, 2023 |
| Acer          | Aspire A515-51G             | [34d03fbbcd](https://linux-hardware.org/?probe=34d03fbbcd) | Apr 08, 2023 |
| Sony          | VJF155F11X-B0811B           | [89f9cc86a7](https://linux-hardware.org/?probe=89f9cc86a7) | Apr 08, 2023 |
| MSI           | Katana GF76 11UD            | [6f9a54256f](https://linux-hardware.org/?probe=6f9a54256f) | Apr 07, 2023 |
| Acer          | Aspire 5517                 | [bbedb2d88e](https://linux-hardware.org/?probe=bbedb2d88e) | Apr 07, 2023 |
| HP            | EliteBook 2530p             | [66ec38445f](https://linux-hardware.org/?probe=66ec38445f) | Apr 07, 2023 |
| Acer          | Aspire A515-52              | [3d9e5a4546](https://linux-hardware.org/?probe=3d9e5a4546) | Apr 07, 2023 |
| Positivo      | H14BT58                     | [135bb6e61a](https://linux-hardware.org/?probe=135bb6e61a) | Apr 06, 2023 |
| Dell          | Inspiron 3584               | [50f052ef1c](https://linux-hardware.org/?probe=50f052ef1c) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cd6431fbf5](https://linux-hardware.org/?probe=cd6431fbf5) | Apr 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBC... | [f4dd5b1a73](https://linux-hardware.org/?probe=f4dd5b1a73) | Apr 05, 2023 |
| Multilaser    | PC13X                       | [85579abbc9](https://linux-hardware.org/?probe=85579abbc9) | Apr 05, 2023 |
| Evolute       | B14HM21                     | [be41163512](https://linux-hardware.org/?probe=be41163512) | Apr 05, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [473898ff0e](https://linux-hardware.org/?probe=473898ff0e) | Apr 04, 2023 |
| Acer          | Aspire 4349                 | [43ae04b9c3](https://linux-hardware.org/?probe=43ae04b9c3) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| Samsung       | 767XCL                      | [b5a44d9194](https://linux-hardware.org/?probe=b5a44d9194) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8a7681ab18](https://linux-hardware.org/?probe=8a7681ab18) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Timi          | RedmiBook Pro 14S           | [e3eb0fe882](https://linux-hardware.org/?probe=e3eb0fe882) | Apr 02, 2023 |
| Samsung       | 550P5C/550P7C               | [8e6191f4bb](https://linux-hardware.org/?probe=8e6191f4bb) | Apr 02, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [e42bc1dd05](https://linux-hardware.org/?probe=e42bc1dd05) | Apr 02, 2023 |
| ASUSTek       | X451CA                      | [81002767d0](https://linux-hardware.org/?probe=81002767d0) | Apr 02, 2023 |
| Multilaser    | PC150                       | [0bcb0ca7ba](https://linux-hardware.org/?probe=0bcb0ca7ba) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Alienware     | m15 R7                      | [68b2947cdb](https://linux-hardware.org/?probe=68b2947cdb) | Apr 02, 2023 |
| Dell          | Latitude E5400              | [4b69d7d67c](https://linux-hardware.org/?probe=4b69d7d67c) | Apr 02, 2023 |
| Dell          | Inspiron 5458               | [38b9db2538](https://linux-hardware.org/?probe=38b9db2538) | Apr 01, 2023 |
| Samsung       | 767XCL                      | [a3167908c0](https://linux-hardware.org/?probe=a3167908c0) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | [207edc0a25](https://linux-hardware.org/?probe=207edc0a25) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Itautec       | Infoway w7535               | [48a539f108](https://linux-hardware.org/?probe=48a539f108) | Apr 01, 2023 |
| Valve         | Jupiter                     | [816e9cb6f6](https://linux-hardware.org/?probe=816e9cb6f6) | Apr 01, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [93ef0bb287](https://linux-hardware.org/?probe=93ef0bb287) | Apr 01, 2023 |
| Samsung       | 270E5G/270E5U               | [67b91e463a](https://linux-hardware.org/?probe=67b91e463a) | Mar 31, 2023 |
| Acer          | Aspire A315-54K             | [d325177071](https://linux-hardware.org/?probe=d325177071) | Mar 31, 2023 |
| Positivo      | S14CT01                     | [a47919fcc4](https://linux-hardware.org/?probe=a47919fcc4) | Mar 31, 2023 |
| Quanta        | QL3 TBD                     | [21673aecac](https://linux-hardware.org/?probe=21673aecac) | Mar 31, 2023 |
| Dell          | Vostro V131                 | [53538c2ae9](https://linux-hardware.org/?probe=53538c2ae9) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7597a96654](https://linux-hardware.org/?probe=7597a96654) | Mar 31, 2023 |
| Dell          | Inspiron 5567               | [fe5578a96e](https://linux-hardware.org/?probe=fe5578a96e) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Acer          | Prespa M                    | [a6541a27d9](https://linux-hardware.org/?probe=a6541a27d9) | Mar 30, 2023 |
| Dell          | Vostro 5402                 | [27b9c84cbe](https://linux-hardware.org/?probe=27b9c84cbe) | Mar 30, 2023 |
| Dell          | Inspiron 3421               | [5418efd855](https://linux-hardware.org/?probe=5418efd855) | Mar 30, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | [722c1e9d68](https://linux-hardware.org/?probe=722c1e9d68) | Mar 30, 2023 |
| Dell          | Latitude 3490               | [16d4f0954b](https://linux-hardware.org/?probe=16d4f0954b) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Dell          | Vostro 3480                 | [83cb13ffb4](https://linux-hardware.org/?probe=83cb13ffb4) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Apple         | MacBookAir9,1               | [1fe20bdfcb](https://linux-hardware.org/?probe=1fe20bdfcb) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Dell          | Inspiron 5566               | [7b53b4da78](https://linux-hardware.org/?probe=7b53b4da78) | Mar 29, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| ASUSTek       | X751LJ                      | [cf5d71e2b3](https://linux-hardware.org/?probe=cf5d71e2b3) | Mar 29, 2023 |
| Samsung       | 370E4K                      | [68e9294ac9](https://linux-hardware.org/?probe=68e9294ac9) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| Samsung       | 670Z5E                      | [2bf528dfb1](https://linux-hardware.org/?probe=2bf528dfb1) | Mar 29, 2023 |
| Samsung       | 300E5M/300E5L               | [9d48f53259](https://linux-hardware.org/?probe=9d48f53259) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Dell          | Inspiron 7520               | [8258074853](https://linux-hardware.org/?probe=8258074853) | Mar 28, 2023 |
| HP            | Compaq Presario CQ40        | [7f2e65257c](https://linux-hardware.org/?probe=7f2e65257c) | Mar 28, 2023 |
| HP            | Compaq Presario CQ40        | [9ee954843e](https://linux-hardware.org/?probe=9ee954843e) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Dell          | Vostro 14-5480              | [b1ef6303a6](https://linux-hardware.org/?probe=b1ef6303a6) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Dell          | G3 3579                     | [55b5db4326](https://linux-hardware.org/?probe=55b5db4326) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Notebook      | NJx0MU                      | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| Dell          | Inspiron 5448               | [b800b24cbd](https://linux-hardware.org/?probe=b800b24cbd) | Mar 27, 2023 |
| Dell          | G15 5515                    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| Acer          | Aspire A515-41G             | [33bccb2234](https://linux-hardware.org/?probe=33bccb2234) | Mar 27, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Positivo      | Smash2                      | [b61791c478](https://linux-hardware.org/?probe=b61791c478) | Mar 26, 2023 |
| MSI           | CR620                       | [2fce81cc28](https://linux-hardware.org/?probe=2fce81cc28) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [5c3f0186de](https://linux-hardware.org/?probe=5c3f0186de) | Mar 26, 2023 |
| Dell          | G3 3590                     | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| Sony          | SVF14215CXB                 | [624af23eb4](https://linux-hardware.org/?probe=624af23eb4) | Mar 26, 2023 |
| Acer          | Nitro AN515-54              | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| Samsung       | 550XDA                      | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2df4a612b4](https://linux-hardware.org/?probe=2df4a612b4) | Mar 25, 2023 |
| Acer          | Aspire 4740                 | [c4e47e53dc](https://linux-hardware.org/?probe=c4e47e53dc) | Mar 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27ff485a92](https://linux-hardware.org/?probe=27ff485a92) | Mar 25, 2023 |
| Acer          | Aspire ES1-411              | [1a4caa9a83](https://linux-hardware.org/?probe=1a4caa9a83) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a9ffd21a7f](https://linux-hardware.org/?probe=a9ffd21a7f) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [9e55d83acd](https://linux-hardware.org/?probe=9e55d83acd) | Mar 23, 2023 |
| Samsung       | 530XBB                      | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Avell High... | B.ON                        | [0fe36e1e74](https://linux-hardware.org/?probe=0fe36e1e74) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| Lenovo        | ThinkPad L450 20DSA25V01    | [68b1ae2c5d](https://linux-hardware.org/?probe=68b1ae2c5d) | Mar 23, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [64c4a47e0e](https://linux-hardware.org/?probe=64c4a47e0e) | Mar 23, 2023 |
| Acer          | Nitro AN515-44              | [fca39bd9eb](https://linux-hardware.org/?probe=fca39bd9eb) | Mar 22, 2023 |
| Samsung       | 550XDA                      | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| Acer          | Nitro AN515-44              | [e07e3320b1](https://linux-hardware.org/?probe=e07e3320b1) | Mar 22, 2023 |
| Acer          | Nitro AN517-54              | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| HP            | Pavilion dv4                | [20adc36857](https://linux-hardware.org/?probe=20adc36857) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1165b3734c](https://linux-hardware.org/?probe=1165b3734c) | Mar 21, 2023 |
| Avell High... | A62 LIV                     | [14dab05208](https://linux-hardware.org/?probe=14dab05208) | Mar 21, 2023 |
| Toshiba       | Satellite A305              | [ed7bc92488](https://linux-hardware.org/?probe=ed7bc92488) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b6b5eb415f](https://linux-hardware.org/?probe=b6b5eb415f) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Dell          | Inspiron 7520               | [330f307e06](https://linux-hardware.org/?probe=330f307e06) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ProBook 440 G3              | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Dell          | G15 5511                    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Avell High... | B.ON                        | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1292539ef0](https://linux-hardware.org/?probe=1292539ef0) | Mar 19, 2023 |
| Samsung       | 550XDA                      | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Dell          | Inspiron 7520               | [f587cfd0f1](https://linux-hardware.org/?probe=f587cfd0f1) | Mar 19, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [964d71f3f2](https://linux-hardware.org/?probe=964d71f3f2) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Avell High... | C62 MOB                     | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| Clevo         | W340EU                      | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Clevo         | W340EU                      | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [8c8a87616c](https://linux-hardware.org/?probe=8c8a87616c) | Mar 18, 2023 |
| Notebook      | NJx0MU                      | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| Positivo      | C14CU51                     | [02fe8f2e3b](https://linux-hardware.org/?probe=02fe8f2e3b) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| ASUSTek       | K84C                        | [1c6b73b907](https://linux-hardware.org/?probe=1c6b73b907) | Mar 18, 2023 |
| Samsung       | 550XDA                      | [210e5d9e14](https://linux-hardware.org/?probe=210e5d9e14) | Mar 17, 2023 |
| Acer          | Aspire V7-482PG             | [9ba6bdc643](https://linux-hardware.org/?probe=9ba6bdc643) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [353d82cd61](https://linux-hardware.org/?probe=353d82cd61) | Mar 17, 2023 |
| Positivo      | N1250                       | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| Acer          | Nitro AN515-44              | [dd12b2101e](https://linux-hardware.org/?probe=dd12b2101e) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| Dell          | Inspiron 7520               | [1cedff3f90](https://linux-hardware.org/?probe=1cedff3f90) | Mar 17, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Dell          | XPS 13 9310                 | [0d1834afd1](https://linux-hardware.org/?probe=0d1834afd1) | Mar 16, 2023 |
| Avell High... | STORM TWO                   | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| Acer          | Aspire A315-34              | [63676e7012](https://linux-hardware.org/?probe=63676e7012) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f4374c5a2b](https://linux-hardware.org/?probe=f4374c5a2b) | Mar 15, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3028035868](https://linux-hardware.org/?probe=3028035868) | Mar 15, 2023 |
| Acer          | Aspire A515-51              | [6e1d22df26](https://linux-hardware.org/?probe=6e1d22df26) | Mar 15, 2023 |
| Acer          | Aspire E1-421               | [bb1dca9ea3](https://linux-hardware.org/?probe=bb1dca9ea3) | Mar 14, 2023 |
| Positivo      | Q464B                       | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Acer          | Aspire A315-34              | [bbb4128793](https://linux-hardware.org/?probe=bbb4128793) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| Google        | Celes                       | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [7ffbc62c94](https://linux-hardware.org/?probe=7ffbc62c94) | Mar 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [4c6424525e](https://linux-hardware.org/?probe=4c6424525e) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| HP            | ProBook 6460b               | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| HP            | Pavilion dm1                | [9ed7d80abb](https://linux-hardware.org/?probe=9ed7d80abb) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [bd0af3660b](https://linux-hardware.org/?probe=bd0af3660b) | Mar 12, 2023 |
| Samsung       | 550XDA                      | [c42ead0ecf](https://linux-hardware.org/?probe=c42ead0ecf) | Mar 12, 2023 |
| Positivo      | Q464B                       | [513b08857c](https://linux-hardware.org/?probe=513b08857c) | Mar 11, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| Acer          | Aspire A515-51G             | [757a62eff0](https://linux-hardware.org/?probe=757a62eff0) | Mar 11, 2023 |
| Dell          | System XPS L502X            | [b3f35673e6](https://linux-hardware.org/?probe=b3f35673e6) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Positivo      | C14CU51                     | [0cc5053d97](https://linux-hardware.org/?probe=0cc5053d97) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [15dd4409fc](https://linux-hardware.org/?probe=15dd4409fc) | Mar 11, 2023 |
| Dell          | Inspiron 5420               | [9e6843fe2e](https://linux-hardware.org/?probe=9e6843fe2e) | Mar 10, 2023 |
| Dell          | Latitude E6420              | [514c8548aa](https://linux-hardware.org/?probe=514c8548aa) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [0d8d93d401](https://linux-hardware.org/?probe=0d8d93d401) | Mar 10, 2023 |
| Dell          | Inspiron 5420               | [77d13c9c12](https://linux-hardware.org/?probe=77d13c9c12) | Mar 10, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [b8dffd9bd3](https://linux-hardware.org/?probe=b8dffd9bd3) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | [d524e6c586](https://linux-hardware.org/?probe=d524e6c586) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6ae7081970](https://linux-hardware.org/?probe=6ae7081970) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | [2d75f5ea8b](https://linux-hardware.org/?probe=2d75f5ea8b) | Mar 10, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [12d1ccac8d](https://linux-hardware.org/?probe=12d1ccac8d) | Mar 09, 2023 |
| Dell          | Vostro 1310                 | [a5677d37dc](https://linux-hardware.org/?probe=a5677d37dc) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7429f9be3](https://linux-hardware.org/?probe=e7429f9be3) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Itautec       | Infoway w7440               | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| Samsung       | 550XDA                      | [65093a6cf5](https://linux-hardware.org/?probe=65093a6cf5) | Mar 08, 2023 |
| Dell          | Inspiron 3442               | [8900b65d0b](https://linux-hardware.org/?probe=8900b65d0b) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Sony          | VPCEA23FB                   | [d6618b65cf](https://linux-hardware.org/?probe=d6618b65cf) | Mar 08, 2023 |
| Dell          | Vostro 3550                 | [30d171ddbc](https://linux-hardware.org/?probe=30d171ddbc) | Mar 08, 2023 |
| Dell          | XPS 13 9380                 | [1edca5142c](https://linux-hardware.org/?probe=1edca5142c) | Mar 07, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | [285589b568](https://linux-hardware.org/?probe=285589b568) | Mar 07, 2023 |
| Lenovo        | ThinkPad T430 234424P       | [f9d41f9054](https://linux-hardware.org/?probe=f9d41f9054) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Dell          | Vostro 3550                 | [cb9468fb01](https://linux-hardware.org/?probe=cb9468fb01) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| LG Electro... | A530-U.BE54P1               | [c0260c82db](https://linux-hardware.org/?probe=c0260c82db) | Mar 07, 2023 |
| Samsung       | 550XDA                      | [f73f29bd0b](https://linux-hardware.org/?probe=f73f29bd0b) | Mar 06, 2023 |
| Digibras      | NH4CU03                     | [ff8a1d6dc3](https://linux-hardware.org/?probe=ff8a1d6dc3) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7fb36218d9](https://linux-hardware.org/?probe=7fb36218d9) | Mar 06, 2023 |
| Dell          | G15 5520                    | [0322e7d38c](https://linux-hardware.org/?probe=0322e7d38c) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2e4f2069e8](https://linux-hardware.org/?probe=2e4f2069e8) | Mar 06, 2023 |
| Digibras      | NH4CU03                     | [9bfa331a22](https://linux-hardware.org/?probe=9bfa331a22) | Mar 06, 2023 |
| Intel         | Crestline & ICH8M Chipse... | [c9e67a9174](https://linux-hardware.org/?probe=c9e67a9174) | Mar 06, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [a6c7741454](https://linux-hardware.org/?probe=a6c7741454) | Mar 06, 2023 |
| Acer          | Aspire A515-54              | [a544ef69d8](https://linux-hardware.org/?probe=a544ef69d8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| Acer          | Aspire A515-54              | [6c190c594b](https://linux-hardware.org/?probe=6c190c594b) | Mar 05, 2023 |
| Dell          | Vostro 3550                 | [973f97d171](https://linux-hardware.org/?probe=973f97d171) | Mar 05, 2023 |
| Avell High... | A70 MOB                     | [79d3147035](https://linux-hardware.org/?probe=79d3147035) | Mar 05, 2023 |
| Lenovo        | G50-80 80R0                 | [6d4a93e1d8](https://linux-hardware.org/?probe=6d4a93e1d8) | Mar 05, 2023 |
| Avell High... | A70 MOB                     | [38bf7fda89](https://linux-hardware.org/?probe=38bf7fda89) | Mar 05, 2023 |
| Lenovo        | G50-80 80R0                 | [5e640d57d8](https://linux-hardware.org/?probe=5e640d57d8) | Mar 05, 2023 |
| Dell          | Inspiron 5557               | [7950f8f750](https://linux-hardware.org/?probe=7950f8f750) | Mar 05, 2023 |
| Google        | Lillipup                    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| Dell          | Inspiron 5566               | [a067a3c4a6](https://linux-hardware.org/?probe=a067a3c4a6) | Mar 04, 2023 |
| Valve         | Jupiter                     | [05dc2f9352](https://linux-hardware.org/?probe=05dc2f9352) | Mar 04, 2023 |
| Notebook      | NJx0MU                      | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Nitro AN515-54              | [463de722cd](https://linux-hardware.org/?probe=463de722cd) | Mar 04, 2023 |
| Dell          | G15 5520                    | [1e3dcc41d3](https://linux-hardware.org/?probe=1e3dcc41d3) | Mar 04, 2023 |
| Lenovo        | ThinkPad T430 234424P       | [54a25c6e4b](https://linux-hardware.org/?probe=54a25c6e4b) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [b7d678deee](https://linux-hardware.org/?probe=b7d678deee) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [d7b1fc0c9d](https://linux-hardware.org/?probe=d7b1fc0c9d) | Mar 04, 2023 |
| Acer          | Nitro AN515-45              | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| Acer          | Aspire A315-53              | [d16e7dcded](https://linux-hardware.org/?probe=d16e7dcded) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Acer          | Aspire 5750                 | [d1e6cecff5](https://linux-hardware.org/?probe=d1e6cecff5) | Mar 03, 2023 |
| Dell          | Inspiron N5010              | [5043ee2124](https://linux-hardware.org/?probe=5043ee2124) | Mar 03, 2023 |
| Dell          | Inspiron N5010              | [1139097eb7](https://linux-hardware.org/?probe=1139097eb7) | Mar 03, 2023 |
| HP            | Compaq Presario CQ42        | [f8cfeeb2d9](https://linux-hardware.org/?probe=f8cfeeb2d9) | Mar 03, 2023 |
| Intel         | W7650                       | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Dell          | Latitude 3490               | [e23ef8765b](https://linux-hardware.org/?probe=e23ef8765b) | Mar 02, 2023 |
| HP            | Pavilion dv7                | [534da84bd1](https://linux-hardware.org/?probe=534da84bd1) | Mar 02, 2023 |
| Dell          | Vostro 3550                 | [1427d9ce74](https://linux-hardware.org/?probe=1427d9ce74) | Mar 02, 2023 |
| HP            | Pavilion dv7                | [4a0bc37c58](https://linux-hardware.org/?probe=4a0bc37c58) | Mar 02, 2023 |
| Dell          | Vostro 3550                 | [eebbe0447e](https://linux-hardware.org/?probe=eebbe0447e) | Mar 02, 2023 |
| Dell          | Inspiron 3442               | [3a56892391](https://linux-hardware.org/?probe=3a56892391) | Mar 02, 2023 |
| Sony          | VPCEH10EB                   | [9c8bb09559](https://linux-hardware.org/?probe=9c8bb09559) | Mar 01, 2023 |
| Positivo      | S14CT01                     | [312e70e158](https://linux-hardware.org/?probe=312e70e158) | Mar 01, 2023 |
| HP            | Compaq Presario CQ42        | [5118aed3c9](https://linux-hardware.org/?probe=5118aed3c9) | Mar 01, 2023 |
| Notebook      | NJx0MU                      | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Dell          | Vostro 3500                 | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| Toshiba       | IS 1413G                    | [05ad6c694b](https://linux-hardware.org/?probe=05ad6c694b) | Mar 01, 2023 |
| Philco        | 10D                         | [dd709d35db](https://linux-hardware.org/?probe=dd709d35db) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Dell          | G15 5510                    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| Dell          | G15 5510                    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [d66bcd2bc8](https://linux-hardware.org/?probe=d66bcd2bc8) | Feb 27, 2023 |
| Dell          | Inspiron 1525               | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | [04c721038a](https://linux-hardware.org/?probe=04c721038a) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| HP            | 430                         | [f90c967f06](https://linux-hardware.org/?probe=f90c967f06) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [86fac430ca](https://linux-hardware.org/?probe=86fac430ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| Dell          | Inspiron 3584               | [47eff629e0](https://linux-hardware.org/?probe=47eff629e0) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Intel         | HuronRiver Platform         | [2168c2bb5c](https://linux-hardware.org/?probe=2168c2bb5c) | Feb 26, 2023 |
| Dell          | G15 5520                    | [d68c28ea8d](https://linux-hardware.org/?probe=d68c28ea8d) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [75e601b927](https://linux-hardware.org/?probe=75e601b927) | Feb 26, 2023 |
| Dell          | Inspiron 3576               | [5911354b82](https://linux-hardware.org/?probe=5911354b82) | Feb 26, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Acer          | Acadia V1.45                | [faee032e6c](https://linux-hardware.org/?probe=faee032e6c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [af95b24466](https://linux-hardware.org/?probe=af95b24466) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| Samsung       | 550XBE/350XBE               | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5c3d39f884](https://linux-hardware.org/?probe=5c3d39f884) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | Z450LA                      | [304be04748](https://linux-hardware.org/?probe=304be04748) | Feb 25, 2023 |
| Samsung       | RV415/RV515                 | [23c0509d46](https://linux-hardware.org/?probe=23c0509d46) | Feb 25, 2023 |
| Sony          | VPCCW13FB                   | [1772a3987b](https://linux-hardware.org/?probe=1772a3987b) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [d3354bd88c](https://linux-hardware.org/?probe=d3354bd88c) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6dd01c6a20](https://linux-hardware.org/?probe=6dd01c6a20) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1b5b668cea](https://linux-hardware.org/?probe=1b5b668cea) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c0af9c8bdb](https://linux-hardware.org/?probe=c0af9c8bdb) | Feb 24, 2023 |
| Positivo      | N1103                       | [b89c4551aa](https://linux-hardware.org/?probe=b89c4551aa) | Feb 24, 2023 |
| Positivo      | Q464C-O                     | [cda1faecb1](https://linux-hardware.org/?probe=cda1faecb1) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Avell High... | A70 MOB                     | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| Dell          | Inspiron N5010              | [5b4def0870](https://linux-hardware.org/?probe=5b4def0870) | Feb 23, 2023 |
| Dell          | Latitude 3420               | [86fd73d1e3](https://linux-hardware.org/?probe=86fd73d1e3) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| Acer          | Nitro AN515-52              | [05f7c375b7](https://linux-hardware.org/?probe=05f7c375b7) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe9944c457](https://linux-hardware.org/?probe=fe9944c457) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Positivo      | Q464C                       | [1b08f16a08](https://linux-hardware.org/?probe=1b08f16a08) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | [5b173518b5](https://linux-hardware.org/?probe=5b173518b5) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | [107bd5b235](https://linux-hardware.org/?probe=107bd5b235) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c99d1595ec](https://linux-hardware.org/?probe=c99d1595ec) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Positivo      | S14SL01                     | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Dell          | Inspiron 3583               | [ad766a4190](https://linux-hardware.org/?probe=ad766a4190) | Feb 22, 2023 |
| Positivo      | Q232A                       | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Positivo      | S14CT01                     | [af73fc0481](https://linux-hardware.org/?probe=af73fc0481) | Feb 22, 2023 |
| Samsung       | 767XCL                      | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Inspiron 5547               | [ff88bcbafc](https://linux-hardware.org/?probe=ff88bcbafc) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [818012d7ef](https://linux-hardware.org/?probe=818012d7ef) | Feb 21, 2023 |
| Unknown       | Unknown                     | [08eab2bac4](https://linux-hardware.org/?probe=08eab2bac4) | Feb 21, 2023 |
| Avell High... | 1513                        | [0b46cb6de1](https://linux-hardware.org/?probe=0b46cb6de1) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [caccb434d2](https://linux-hardware.org/?probe=caccb434d2) | Feb 21, 2023 |
| Compaq        | 430                         | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| HP            | 1000                        | [91faf9460d](https://linux-hardware.org/?probe=91faf9460d) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | G40-80 80JE                 | [e7e12370af](https://linux-hardware.org/?probe=e7e12370af) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Unknown       | Unknown                     | [cccf0ea7f3](https://linux-hardware.org/?probe=cccf0ea7f3) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Acer          | Predator PH315-52           | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| HP            | Compaq Presario CQ42        | [001f2f1a86](https://linux-hardware.org/?probe=001f2f1a86) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | [ca537a9b24](https://linux-hardware.org/?probe=ca537a9b24) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | [d5dbc5770a](https://linux-hardware.org/?probe=d5dbc5770a) | Feb 19, 2023 |
| Notebook      | NJx0MU                      | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Acer          | Aspire A515-41G             | [e06b3509f1](https://linux-hardware.org/?probe=e06b3509f1) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Avell High... | B.ON                        | [d7f2dafd5e](https://linux-hardware.org/?probe=d7f2dafd5e) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [beff031939](https://linux-hardware.org/?probe=beff031939) | Feb 18, 2023 |
| Acer          | Aspire A515-51              | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| Samsung       | 270E5G/270E5U               | [daf6a78f6f](https://linux-hardware.org/?probe=daf6a78f6f) | Feb 17, 2023 |
| Samsung       | 550XDA                      | [d7f1482689](https://linux-hardware.org/?probe=d7f1482689) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Dell          | Inspiron 3583               | [9200702bb7](https://linux-hardware.org/?probe=9200702bb7) | Feb 16, 2023 |
| Dell          | Inspiron 13-5378            | [cf5749e5be](https://linux-hardware.org/?probe=cf5749e5be) | Feb 16, 2023 |
| Positivo      | S14BW01                     | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Positivo      | CHT14B                      | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | [7d55f655bb](https://linux-hardware.org/?probe=7d55f655bb) | Feb 15, 2023 |
| Acer          | Nitro AN515-54              | [4e0f0e0310](https://linux-hardware.org/?probe=4e0f0e0310) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e42ed53dcf](https://linux-hardware.org/?probe=e42ed53dcf) | Feb 15, 2023 |
| Lenovo        | G470 20078                  | [8385999199](https://linux-hardware.org/?probe=8385999199) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| HP            | EliteBook 8460p             | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Acer          | Predator G3-572             | [410a9aae8c](https://linux-hardware.org/?probe=410a9aae8c) | Feb 14, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03f90da8d3](https://linux-hardware.org/?probe=03f90da8d3) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Dell          | Inspiron 5402               | [805931ad5f](https://linux-hardware.org/?probe=805931ad5f) | Feb 14, 2023 |
| Positivo      | CHT14B                      | [859e8a3c17](https://linux-hardware.org/?probe=859e8a3c17) | Feb 13, 2023 |
| Positivo      | CHT14B                      | [2d5b910ed3](https://linux-hardware.org/?probe=2d5b910ed3) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Samsung       | 550XDA                      | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| Toshiba       | IS 1413G                    | [75f2859a68](https://linux-hardware.org/?probe=75f2859a68) | Feb 12, 2023 |
| Toshiba       | IS 1413G                    | [ec0e0c6dc2](https://linux-hardware.org/?probe=ec0e0c6dc2) | Feb 12, 2023 |
| Samsung       | 767XCL                      | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Toshiba       | IS 1413G                    | [e32070b494](https://linux-hardware.org/?probe=e32070b494) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| Unknown       | Unknown                     | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Dell          | Inspiron 5590               | [594e3be773](https://linux-hardware.org/?probe=594e3be773) | Feb 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [1a1760b638](https://linux-hardware.org/?probe=1a1760b638) | Feb 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [2dca851444](https://linux-hardware.org/?probe=2dca851444) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Acer          | Aspire A515-45              | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| Intel         | HuronRiver Platform         | [e3ad5a0e88](https://linux-hardware.org/?probe=e3ad5a0e88) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| Dell          | Inspiron 5402               | [52125d1623](https://linux-hardware.org/?probe=52125d1623) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| HP            | ProBook 440 G5              | [0f111bd12b](https://linux-hardware.org/?probe=0f111bd12b) | Feb 09, 2023 |
| Dell          | Inspiron 7460               | [2c17efbcd7](https://linux-hardware.org/?probe=2c17efbcd7) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Toshiba       | IS 1413G                    | [c5c9fb9b41](https://linux-hardware.org/?probe=c5c9fb9b41) | Feb 09, 2023 |
| Acer          | Aspire A315-53G             | [e2a551b06b](https://linux-hardware.org/?probe=e2a551b06b) | Feb 09, 2023 |
| Acer          | Predator PH315-55           | [452c65c04b](https://linux-hardware.org/?probe=452c65c04b) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | [5e1eb34232](https://linux-hardware.org/?probe=5e1eb34232) | Feb 09, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [43968e7a27](https://linux-hardware.org/?probe=43968e7a27) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [74f2ac0aeb](https://linux-hardware.org/?probe=74f2ac0aeb) | Feb 08, 2023 |
| Dell          | G15 5515                    | [3b0208199f](https://linux-hardware.org/?probe=3b0208199f) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Apple         | MacBookAir7,2               | [0a94d67455](https://linux-hardware.org/?probe=0a94d67455) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a2378e95f6](https://linux-hardware.org/?probe=a2378e95f6) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| Acer          | TravelMate P256-M           | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| Dell          | Inspiron 7580               | [986d240b5d](https://linux-hardware.org/?probe=986d240b5d) | Feb 06, 2023 |
| Quanta        | TWS                         | [275ccf1b58](https://linux-hardware.org/?probe=275ccf1b58) | Feb 05, 2023 |
| Dell          | G15 5510                    | [41bbdf84c2](https://linux-hardware.org/?probe=41bbdf84c2) | Feb 05, 2023 |
| Acer          | Aspire E1-572               | [02d439f664](https://linux-hardware.org/?probe=02d439f664) | Feb 05, 2023 |
| Lenovo        | G400s VILG1                 | [426348e103](https://linux-hardware.org/?probe=426348e103) | Feb 05, 2023 |
| Dell          | G15 5515                    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| Evolute       | SFX-65                      | [7b37b32f92](https://linux-hardware.org/?probe=7b37b32f92) | Feb 04, 2023 |
| Dell          | Inspiron 15-3567            | [7659183894](https://linux-hardware.org/?probe=7659183894) | Feb 04, 2023 |
| HP            | Compaq Presario CQ40        | [de29ca3277](https://linux-hardware.org/?probe=de29ca3277) | Feb 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Notebook      | NJx0MU                      | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| ASUSTek       | K45VM                       | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Dell          | Precision M4600             | [a0d6749416](https://linux-hardware.org/?probe=a0d6749416) | Feb 04, 2023 |
| Acer          | Aspire E1-572               | [6f3ba6b805](https://linux-hardware.org/?probe=6f3ba6b805) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| Acer          | Aspire E1-572               | [f99e3aa76d](https://linux-hardware.org/?probe=f99e3aa76d) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [b82450078c](https://linux-hardware.org/?probe=b82450078c) | Feb 03, 2023 |
| Dell          | Vostro 3550                 | [17a4a2e5fd](https://linux-hardware.org/?probe=17a4a2e5fd) | Feb 02, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [92d639c0f4](https://linux-hardware.org/?probe=92d639c0f4) | Feb 02, 2023 |
| Dell          | Latitude 7480               | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Positivo      | Mobile                      | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [721bc8fb78](https://linux-hardware.org/?probe=721bc8fb78) | Feb 02, 2023 |
| Insyde        | Braswell                    | [928b461a5b](https://linux-hardware.org/?probe=928b461a5b) | Feb 02, 2023 |
| Lenovo        | G40-80 80JE                 | [9a5e6fd61e](https://linux-hardware.org/?probe=9a5e6fd61e) | Feb 02, 2023 |
| Philco        | 14I                         | [8f9833285e](https://linux-hardware.org/?probe=8f9833285e) | Feb 01, 2023 |
| Acer          | Aspire E1-572               | [c4e6e989f5](https://linux-hardware.org/?probe=c4e6e989f5) | Feb 01, 2023 |
| Dell          | Inspiron 5566               | [b2dd8d93c7](https://linux-hardware.org/?probe=b2dd8d93c7) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | [fa4104f438](https://linux-hardware.org/?probe=fa4104f438) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | [ec80fcb8a5](https://linux-hardware.org/?probe=ec80fcb8a5) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Acer          | Nitro AN515-54              | [9aee0a798c](https://linux-hardware.org/?probe=9aee0a798c) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Dell          | Inspiron 15-3567            | [2f6f4bc8c7](https://linux-hardware.org/?probe=2f6f4bc8c7) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Samsung       | RV415/RV515                 | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | [bb5d758714](https://linux-hardware.org/?probe=bb5d758714) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | [e5dc585024](https://linux-hardware.org/?probe=e5dc585024) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire A515-41G             | [88db10e257](https://linux-hardware.org/?probe=88db10e257) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Avell High... | B.ON                        | [721fbbdeb2](https://linux-hardware.org/?probe=721fbbdeb2) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [1c62beb905](https://linux-hardware.org/?probe=1c62beb905) | Jan 29, 2023 |
| Samsung       | RV415/RV515                 | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [51245400df](https://linux-hardware.org/?probe=51245400df) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| Positivo      | Q464C-O                     | [e61f2d0622](https://linux-hardware.org/?probe=e61f2d0622) | Jan 29, 2023 |
| Acer          | Aspire 5733                 | [da753d74a1](https://linux-hardware.org/?probe=da753d74a1) | Jan 29, 2023 |
| Dell          | G15 5520                    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f1f5def619](https://linux-hardware.org/?probe=f1f5def619) | Jan 28, 2023 |
| Samsung       | RV415/RV515                 | [fd9d67e4b8](https://linux-hardware.org/?probe=fd9d67e4b8) | Jan 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [c74ea31148](https://linux-hardware.org/?probe=c74ea31148) | Jan 27, 2023 |
| HP            | Compaq 6530b                | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [5a32be51f4](https://linux-hardware.org/?probe=5a32be51f4) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Philco        | 14E                         | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [93be3d62c4](https://linux-hardware.org/?probe=93be3d62c4) | Jan 27, 2023 |
| Compaq        | 430                         | [069fa715b9](https://linux-hardware.org/?probe=069fa715b9) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [b4d0bbaf56](https://linux-hardware.org/?probe=b4d0bbaf56) | Jan 27, 2023 |
| Dell          | Inspiron 5468               | [d155136857](https://linux-hardware.org/?probe=d155136857) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [05dac90dec](https://linux-hardware.org/?probe=05dac90dec) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [0697311f5f](https://linux-hardware.org/?probe=0697311f5f) | Jan 27, 2023 |
| Dell          | G3 3500                     | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| Dell          | Vostro 3458                 | [3beffe6710](https://linux-hardware.org/?probe=3beffe6710) | Jan 26, 2023 |
| ASUSTek       | Z550SA                      | [f5ac147c1e](https://linux-hardware.org/?probe=f5ac147c1e) | Jan 26, 2023 |
| Multilaser    | PC150                       | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| Dell          | Latitude 5490               | [b392e71ce5](https://linux-hardware.org/?probe=b392e71ce5) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| HP            | G60                         | [8fe616c588](https://linux-hardware.org/?probe=8fe616c588) | Jan 25, 2023 |
| HP            | Folio 13                    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| Digibras      | NH4CU03                     | [7de7df58a3](https://linux-hardware.org/?probe=7de7df58a3) | Jan 24, 2023 |
| Digibras      | NH4CU03                     | [fce5f618d8](https://linux-hardware.org/?probe=fce5f618d8) | Jan 24, 2023 |
| Dell          | Inspiron 3421               | [02491de92f](https://linux-hardware.org/?probe=02491de92f) | Jan 24, 2023 |
| Compaq        | 420                         | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| Acer          | Aspire A515-51              | [418e5a2787](https://linux-hardware.org/?probe=418e5a2787) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Insyde        | Braswell                    | [6abab0adc1](https://linux-hardware.org/?probe=6abab0adc1) | Jan 24, 2023 |
| Positivo      | N1240                       | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| ASUSTek       | K46CB                       | [62aa75f57a](https://linux-hardware.org/?probe=62aa75f57a) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [4a97e29245](https://linux-hardware.org/?probe=4a97e29245) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [54ebd7c5f8](https://linux-hardware.org/?probe=54ebd7c5f8) | Jan 23, 2023 |
| Dell          | Latitude 3420               | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| Notebook      | NJx0MU                      | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Alienware     | m15 R7                      | [e57302bf60](https://linux-hardware.org/?probe=e57302bf60) | Jan 23, 2023 |
| HP            | 540                         | [a4a7b26f42](https://linux-hardware.org/?probe=a4a7b26f42) | Jan 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7d4406c9bc](https://linux-hardware.org/?probe=7d4406c9bc) | Jan 22, 2023 |
| HP            | Pavilion dv4                | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| Dell          | G3 3500                     | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [697fbcd8d1](https://linux-hardware.org/?probe=697fbcd8d1) | Jan 22, 2023 |
| Dell          | G3 3500                     | [e81b4d5e46](https://linux-hardware.org/?probe=e81b4d5e46) | Jan 22, 2023 |
| Dell          | Inspiron N4050              | [6ddc2793d7](https://linux-hardware.org/?probe=6ddc2793d7) | Jan 21, 2023 |
| Dell          | Inspiron N4050              | [ae4c9eaa9c](https://linux-hardware.org/?probe=ae4c9eaa9c) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ed9d60d9b7](https://linux-hardware.org/?probe=ed9d60d9b7) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| Philco        | OEM                         | [a39f50ccfd](https://linux-hardware.org/?probe=a39f50ccfd) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [fa251ca13c](https://linux-hardware.org/?probe=fa251ca13c) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [965d1fa09f](https://linux-hardware.org/?probe=965d1fa09f) | Jan 20, 2023 |
| Acer          | Aspire E5-571               | [a37e873516](https://linux-hardware.org/?probe=a37e873516) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [138a9b3b0c](https://linux-hardware.org/?probe=138a9b3b0c) | Jan 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6364be5249](https://linux-hardware.org/?probe=6364be5249) | Jan 20, 2023 |
| Dell          | Inspiron N4050              | [46e35da681](https://linux-hardware.org/?probe=46e35da681) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| Dell          | Vostro 3400                 | [c158cd6095](https://linux-hardware.org/?probe=c158cd6095) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Notebook      | NJx0MU                      | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| Dell          | Inspiron 15-3567            | [33a3aac223](https://linux-hardware.org/?probe=33a3aac223) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [cc9e6f8862](https://linux-hardware.org/?probe=cc9e6f8862) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| Sony          | VPCCA15FX                   | [41138327da](https://linux-hardware.org/?probe=41138327da) | Jan 19, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 918       | 11.53%  |
| Ubuntu 18.04       | 598       | 7.51%   |
| Ubuntu 22.04       | 292       | 3.67%   |
| Pop!_OS 20.04      | 193       | 2.42%   |
| Linux Mint 20      | 189       | 2.37%   |
| Linux Mint 19.3    | 165       | 2.07%   |
| OpenMandriva 4.2   | 157       | 1.97%   |
| OpenMandriva 4.3   | 150       | 1.88%   |
| Linux Mint 20.3    | 140       | 1.76%   |
| Pop!_OS 22.04      | 134       | 1.68%   |
| Manjaro            | 125       | 1.57%   |
| Linux Mint 19.1    | 122       | 1.53%   |
| Linux Mint 20.1    | 119       | 1.5%    |
| Ubuntu 19.04       | 117       | 1.47%   |
| Arch               | 114       | 1.43%   |
| KDE neon 20.04     | 113       | 1.42%   |
| Linux Mint 20.2    | 112       | 1.41%   |
| Zorin 16           | 111       | 1.39%   |
| Debian 11          | 107       | 1.34%   |
| Ubuntu 19.10       | 106       | 1.33%   |
| Zorin 15           | 91        | 1.14%   |
| Arch Rolling       | 84        | 1.06%   |
| Debian 10          | 83        | 1.04%   |
| Fedora 35          | 80        | 1.01%   |
| Fedora 34          | 73        | 0.92%   |
| Pop!_OS 21.10      | 71        | 0.89%   |
| Fedora 37          | 70        | 0.88%   |
| Fedora 32          | 69        | 0.87%   |
| Endless 3.7.8      | 69        | 0.87%   |
| Xubuntu 20.04      | 68        | 0.85%   |
| OpenMandriva 23.01 | 68        | 0.85%   |
| Fedora 36          | 68        | 0.85%   |
| Pop!_OS 21.04      | 67        | 0.84%   |
| Linux Mint 21.1    | 67        | 0.84%   |
| Endless 3.9.5      | 67        | 0.84%   |
| Kubuntu 20.04      | 62        | 0.78%   |
| Pop!_OS 20.10      | 60        | 0.75%   |
| Fedora 33          | 60        | 0.75%   |
| Ubuntu 20.10       | 57        | 0.72%   |
| Linux Mint 21      | 56        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2221      | 29.28%  |
| Linux Mint    | 999       | 13.17%  |
| Endless       | 868       | 11.44%  |
| Pop!_OS       | 506       | 6.67%   |
| Fedora        | 484       | 6.38%   |
| OpenMandriva  | 429       | 5.66%   |
| Debian        | 243       | 3.2%    |
| Manjaro       | 225       | 2.97%   |
| Zorin         | 206       | 2.72%   |
| Arch          | 188       | 2.48%   |
| KDE neon      | 148       | 1.95%   |
| Xubuntu       | 125       | 1.65%   |
| Kubuntu       | 124       | 1.63%   |
| Lubuntu       | 72        | 0.95%   |
| openSUSE      | 68        | 0.9%    |
| Elementary    | 65        | 0.86%   |
| Ubuntu MATE   | 63        | 0.83%   |
| ROSA          | 54        | 0.71%   |
| Ubuntu Unity  | 52        | 0.69%   |
| Kali          | 45        | 0.59%   |
| LMDE          | 38        | 0.5%    |
| Deepin        | 31        | 0.41%   |
| Ubuntu Budgie | 28        | 0.37%   |
| ArcoLinux     | 28        | 0.37%   |
| Clear Linux   | 26        | 0.34%   |
| LinuxFX       | 21        | 0.28%   |
| BigLinux      | 20        | 0.26%   |
| EndeavourOS   | 17        | 0.22%   |
| BlackPanther  | 11        | 0.15%   |
| Reborn OS     | 10        | 0.13%   |
| Parrot        | 10        | 0.13%   |
| CentOS        | 10        | 0.13%   |
| SteamOS       | 9         | 0.12%   |
| Garuda Linux  | 9         | 0.12%   |
| UbuntuDDE     | 8         | 0.11%   |
| Peppermint    | 8         | 0.11%   |
| Nobara        | 8         | 0.11%   |
| MX            | 8         | 0.11%   |
| Gentoo        | 8         | 0.11%   |
| Solus         | 6         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 471       | 5.51%   |
| 5.8.0-14-generic         | 289       | 3.38%   |
| 5.10.14-desktop-1omv4002 | 151       | 1.77%   |
| 5.16.7-desktop-1omv4003  | 144       | 1.68%   |
| 5.4.0-19-generic         | 114       | 1.33%   |
| 5.3.0-28-generic         | 108       | 1.26%   |
| 5.11.0-35-generic        | 95        | 1.11%   |
| 5.4.0-7634-generic       | 74        | 0.87%   |
| 5.4.0-48-generic         | 72        | 0.84%   |
| 5.4.0-40-generic         | 70        | 0.82%   |
| 4.15.0-46-generic        | 70        | 0.82%   |
| 5.15.0-56-generic        | 69        | 0.81%   |
| 6.1.1-desktop-1omv2290   | 66        | 0.77%   |
| 5.4.0-26-generic         | 63        | 0.74%   |
| 5.4.0-58-generic         | 61        | 0.71%   |
| 5.4.0-52-generic         | 57        | 0.67%   |
| 5.4.0-47-generic         | 54        | 0.63%   |
| 5.3.0-19-generic         | 50        | 0.58%   |
| 5.3.0-23-generic         | 47        | 0.55%   |
| 5.3.0-46-generic         | 46        | 0.54%   |
| 5.0.0-32-generic         | 46        | 0.54%   |
| 5.4.0-29-generic         | 44        | 0.51%   |
| 4.18.0-15-generic        | 44        | 0.51%   |
| 5.3.0-40-generic         | 43        | 0.5%    |
| 5.4.0-65-generic         | 42        | 0.49%   |
| 5.4.0-39-generic         | 41        | 0.48%   |
| 5.15.0-52-generic        | 41        | 0.48%   |
| 5.15.0-46-generic        | 41        | 0.48%   |
| 5.0.0-37-generic         | 41        | 0.48%   |
| 5.4.0-80-generic         | 40        | 0.47%   |
| 5.4.0-70-generic         | 39        | 0.46%   |
| 5.0.0-25-generic         | 39        | 0.46%   |
| 5.15.0-58-generic        | 38        | 0.44%   |
| 5.13.0-30-generic        | 38        | 0.44%   |
| 5.11.0-7620-generic      | 38        | 0.44%   |
| 4.18.0-16-generic        | 38        | 0.44%   |
| 5.4.0-91-generic         | 37        | 0.43%   |
| 5.4.0-37-generic         | 37        | 0.43%   |
| 4.15.0-20-generic        | 37        | 0.43%   |
| 6.2.6-desktop-1omv2390   | 36        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 1842      | 22.71%  |
| 5.8.0   | 623       | 7.68%   |
| 5.3.0   | 535       | 6.6%    |
| 4.15.0  | 516       | 6.36%   |
| 5.15.0  | 507       | 6.25%   |
| 5.11.0  | 440       | 5.42%   |
| 5.0.0   | 320       | 3.95%   |
| 5.13.0  | 274       | 3.38%   |
| 4.18.0  | 232       | 2.86%   |
| 5.19.0  | 163       | 2.01%   |
| 5.10.14 | 153       | 1.89%   |
| 5.16.7  | 144       | 1.78%   |
| 5.10.0  | 144       | 1.78%   |
| 4.19.0  | 101       | 1.25%   |
| 6.1.1   | 73        | 0.9%    |
| 6.2.6   | 57        | 0.7%    |
| 5.17.5  | 35        | 0.43%   |
| 6.0.12  | 30        | 0.37%   |
| 5.16.11 | 29        | 0.36%   |
| 5.14.0  | 28        | 0.35%   |
| 4.4.0   | 27        | 0.33%   |
| 5.7.9   | 26        | 0.32%   |
| 6.2.0   | 23        | 0.28%   |
| 4.9.0   | 22        | 0.27%   |
| 5.15.15 | 20        | 0.25%   |
| 6.1.0   | 19        | 0.23%   |
| 5.15.5  | 19        | 0.23%   |
| 6.2.15  | 17        | 0.21%   |
| 6.0.0   | 17        | 0.21%   |
| 5.9.16  | 17        | 0.21%   |
| 5.7.0   | 17        | 0.21%   |
| 5.6.19  | 16        | 0.2%    |
| 5.16.19 | 16        | 0.2%    |
| 5.11.12 | 16        | 0.2%    |
| 5.3.18  | 15        | 0.18%   |
| 5.18.10 | 15        | 0.18%   |
| 5.16.15 | 15        | 0.18%   |
| 5.17.0  | 14        | 0.17%   |
| 6.2.11  | 13        | 0.16%   |
| 5.9.11  | 13        | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1915      | 23.89%  |
| 5.8     | 692       | 8.63%   |
| 5.15    | 676       | 8.43%   |
| 5.3     | 579       | 7.22%   |
| 4.15    | 516       | 6.44%   |
| 5.11    | 507       | 6.33%   |
| 5.10    | 402       | 5.02%   |
| 5.0     | 345       | 4.3%    |
| 5.13    | 328       | 4.09%   |
| 5.16    | 270       | 3.37%   |
| 4.18    | 248       | 3.09%   |
| 5.19    | 209       | 2.61%   |
| 6.2     | 169       | 2.11%   |
| 6.1     | 166       | 2.07%   |
| 4.19    | 118       | 1.47%   |
| 6.0     | 110       | 1.37%   |
| 5.7     | 101       | 1.26%   |
| 5.17    | 98        | 1.22%   |
| 5.14    | 88        | 1.1%    |
| 5.18    | 78        | 0.97%   |
| 5.6     | 68        | 0.85%   |
| 5.9     | 66        | 0.82%   |
| 5.12    | 61        | 0.76%   |
| 4.9     | 46        | 0.57%   |
| 5.5     | 32        | 0.4%    |
| 4.4     | 30        | 0.37%   |
| 5.1     | 28        | 0.35%   |
| 6.3     | 21        | 0.26%   |
| 5.2     | 15        | 0.19%   |
| 4.13    | 7         | 0.09%   |
| 4.20    | 5         | 0.06%   |
| 4.14    | 4         | 0.05%   |
| 4.10    | 4         | 0.05%   |
| 4.1     | 4         | 0.05%   |
| 3.10    | 3         | 0.04%   |
| 4.17    | 2         | 0.02%   |
| 6       | 1         | 0.01%   |
| 4.8     | 1         | 0.01%   |
| 4.12    | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 7069      | 97.58%  |
| i686   | 173       | 2.39%   |
| armv7l | 2         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3771      | 49.87%  |
| Unknown         | 985       | 13.03%  |
| KDE5            | 863       | 11.41%  |
| X-Cinnamon      | 599       | 7.92%   |
| XFCE            | 477       | 6.31%   |
| MATE            | 195       | 2.58%   |
| KDE             | 160       | 2.12%   |
| Cinnamon        | 133       | 1.76%   |
| LXQt            | 75        | 0.99%   |
| Pantheon        | 58        | 0.77%   |
| Unity           | 54        | 0.71%   |
| Deepin          | 41        | 0.54%   |
| Budgie          | 37        | 0.49%   |
| LXDE            | 33        | 0.44%   |
| KDE4            | 25        | 0.33%   |
| i3              | 20        | 0.26%   |
| GNOME Classic   | 10        | 0.13%   |
| sway            | 5         | 0.07%   |
| awesome         | 5         | 0.07%   |
| Hyprland        | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| Enlightenment   | 2         | 0.03%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Openbox         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| icewm           | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| bspwm           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6037      | 81.11%  |
| Wayland | 872       | 11.72%  |
| Unknown | 504       | 6.77%   |
| Tty     | 30        | 0.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4768      | 63.32%  |
| GDM     | 782       | 10.39%  |
| SDDM    | 751       | 9.97%   |
| GDM3    | 509       | 6.76%   |
| LightDM | 390       | 5.18%   |
| TDM     | 292       | 3.88%   |
| KDM     | 26        | 0.35%   |
| XDM     | 6         | 0.08%   |
| SLiM    | 3         | 0.04%   |
| MDM     | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| LXDM    | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang      | Notebooks | Percent |
|-----------|-----------|---------|
| pt_BR     | 4950      | 66.88%  |
| en_US     | 1318      | 17.81%  |
| Unknown   | 916       | 12.38%  |
| C         | 105       | 1.42%   |
| en_GB     | 37        | 0.5%    |
| pt_PT     | 30        | 0.41%   |
| es_ES     | 13        | 0.18%   |
| en_CA     | 6         | 0.08%   |
| fr_FR     | 5         | 0.07%   |
| POSIX     | 3         | 0.04%   |
| de_DE     | 3         | 0.04%   |
| ja_JP     | 2         | 0.03%   |
| it_IT     | 2         | 0.03%   |
| ru_RU     | 1         | 0.01%   |
| pt_BRutf8 | 1         | 0.01%   |
| es_MX     | 1         | 0.01%   |
| es_CL     | 1         | 0.01%   |
| es_AR     | 1         | 0.01%   |
| en_DK     | 1         | 0.01%   |
| en-US     | 1         | 0.01%   |
| em_US     | 1         | 0.01%   |
| de_CH     | 1         | 0.01%   |
| C.UTF8    | 1         | 0.01%   |
| ar_EG     | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3736      | 50.32%  |
| BIOS | 3689      | 49.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5824      | 78.44%  |
| Btrfs   | 562       | 7.57%   |
| Overlay | 503       | 6.77%   |
| Unknown | 388       | 5.23%   |
| Xfs     | 51        | 0.69%   |
| Tmpfs   | 40        | 0.54%   |
| Zfs     | 26        | 0.35%   |
| Ext2    | 11        | 0.15%   |
| Ext3    | 10        | 0.13%   |
| F2fs    | 8         | 0.11%   |
| Aufs    | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4974      | 66.83%  |
| GPT     | 1797      | 24.14%  |
| MBR     | 672       | 9.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6639      | 90.67%  |
| Yes       | 683       | 9.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5739      | 78.05%  |
| Yes       | 1614      | 21.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 1667      | 23.02%  |
| Acer                   | 1411      | 19.48%  |
| Lenovo                 | 909       | 12.55%  |
| Samsung Electronics    | 606       | 8.37%   |
| Hewlett-Packard        | 490       | 6.77%   |
| Positivo               | 478       | 6.6%    |
| ASUSTek Computer       | 411       | 5.67%   |
| Sony                   | 154       | 2.13%   |
| LG Electronics         | 93        | 1.28%   |
| Apple                  | 90        | 1.24%   |
| Avell High Performance | 86        | 1.19%   |
| Digibras               | 70        | 0.97%   |
| Itautec                | 69        | 0.95%   |
| Unknown                | 65        | 0.9%    |
| Semp Toshiba           | 64        | 0.88%   |
| Intel                  | 51        | 0.7%    |
| Multilaser             | 42        | 0.58%   |
| Philco                 | 41        | 0.57%   |
| Compaq                 | 40        | 0.55%   |
| Positivo Bahia - VAIO  | 37        | 0.51%   |
| Toshiba                | 35        | 0.48%   |
| OEM                    | 31        | 0.43%   |
| Notebook               | 27        | 0.37%   |
| Clevo                  | 24        | 0.33%   |
| Gateway                | 21        | 0.29%   |
| Compal                 | 19        | 0.26%   |
| Google                 | 18        | 0.25%   |
| MSI                    | 17        | 0.23%   |
| Alienware              | 15        | 0.21%   |
| Quanta                 | 12        | 0.17%   |
| Timi                   | 10        | 0.14%   |
| Standard               | 10        | 0.14%   |
| eMachines              | 10        | 0.14%   |
| Daten Tecnologia       | 8         | 0.11%   |
| Chuwi                  | 8         | 0.11%   |
| Valve                  | 7         | 0.1%    |
| CCE                    | 7         | 0.1%    |
| Login Informatica      | 6         | 0.08%   |
| LNV                    | 5         | 0.07%   |
| TPVAOC                 | 4         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Nitro AN515-54                         | 138       | 1.91%   |
| Positivo Mobile                             | 120       | 1.66%   |
| Unknown                                     | 109       | 1.5%    |
| Acer Nitro AN515-44                         | 84        | 1.16%   |
| Acer Aspire A315-53                         | 68        | 0.94%   |
| Samsung 340XAA/350XAA/550XAA                | 67        | 0.93%   |
| Dell Inspiron 5566                          | 66        | 0.91%   |
| Lenovo IdeaPad S145-15API 81V7              | 61        | 0.84%   |
| Dell Inspiron 3583                          | 59        | 0.81%   |
| Dell Inspiron 15-3567                       | 57        | 0.79%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 56        | 0.77%   |
| Acer Aspire A315-34                         | 54        | 0.75%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 53        | 0.73%   |
| Acer Nitro AN517-51                         | 51        | 0.7%    |
| Acer Aspire A515-51                         | 50        | 0.69%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 49        | 0.68%   |
| Acer Nitro AN515-43                         | 45        | 0.62%   |
| Samsung 300E5M/300E5L                       | 43        | 0.59%   |
| HP G42                                      | 41        | 0.57%   |
| Dell Inspiron 3442                          | 41        | 0.57%   |
| Samsung 550XDA                              | 40        | 0.55%   |
| Positivo S14CT01                            | 40        | 0.55%   |
| Dell Inspiron N4050                         | 38        | 0.52%   |
| Dell Inspiron 3421                          | 38        | 0.52%   |
| Acer Nitro AN515-52                         | 37        | 0.51%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 35        | 0.48%   |
| Digibras NH4CU03                            | 34        | 0.47%   |
| Dell Inspiron 7520                          | 34        | 0.47%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 33        | 0.46%   |
| HP Pavilion g4                              | 33        | 0.46%   |
| Dell Inspiron 5458                          | 32        | 0.44%   |
| Dell Inspiron 1545                          | 32        | 0.44%   |
| Acer Aspire E5-571                          | 32        | 0.44%   |
| Acer Aspire E1-571                          | 32        | 0.44%   |
| Dell Inspiron 1525                          | 30        | 0.41%   |
| Itautec Infoway                             | 29        | 0.4%    |
| Dell Inspiron 5437                          | 29        | 0.4%    |
| Dell G3 3590                                | 29        | 0.4%    |
| Samsung 550XBE/350XBE                       | 28        | 0.39%   |
| Dell Inspiron 5423                          | 28        | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 1076      | 14.86%  |
| Acer Aspire       | 915       | 12.63%  |
| Lenovo IdeaPad    | 501       | 6.92%   |
| Acer Nitro        | 399       | 5.51%   |
| Dell Vostro       | 228       | 3.15%   |
| Lenovo ThinkPad   | 204       | 2.82%   |
| HP Pavilion       | 194       | 2.68%   |
| Dell Latitude     | 179       | 2.47%   |
| ASUS VivoBook     | 125       | 1.73%   |
| Positivo Mobile   | 120       | 1.66%   |
| Unknown           | 109       | 1.5%    |
| Itautec Infoway   | 69        | 0.95%   |
| Samsung 340XAA    | 67        | 0.93%   |
| Dell G3           | 56        | 0.77%   |
| HP ProBook        | 49        | 0.68%   |
| Samsung RV411     | 46        | 0.64%   |
| Samsung 300E5M    | 43        | 0.59%   |
| HP G42            | 41        | 0.57%   |
| Samsung 550XDA    | 40        | 0.55%   |
| Positivo S14CT01  | 40        | 0.55%   |
| Dell System       | 38        | 0.52%   |
| Acer Predator     | 36        | 0.5%    |
| HP EliteBook      | 35        | 0.48%   |
| Digibras NH4CU03  | 34        | 0.47%   |
| Semp Toshiba IS   | 32        | 0.44%   |
| Toshiba Satellite | 29        | 0.4%    |
| HP Compaq         | 29        | 0.4%    |
| Samsung 550XBE    | 28        | 0.39%   |
| Digibras NH4CU53  | 27        | 0.37%   |
| Compaq Presario   | 27        | 0.37%   |
| Samsung 370E4K    | 26        | 0.36%   |
| Dell G15          | 26        | 0.36%   |
| Samsung 270E5J    | 25        | 0.35%   |
| Lenovo G400s      | 25        | 0.35%   |
| Dell XPS          | 25        | 0.35%   |
| Samsung RV415     | 24        | 0.33%   |
| Positivo Q232A    | 24        | 0.33%   |
| Positivo H14BT58  | 24        | 0.33%   |
| Samsung 300E5EV   | 23        | 0.32%   |
| Positivo CHT14B   | 23        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 950       | 13.12%  |
| 2012    | 740       | 10.22%  |
| 2011    | 661       | 9.13%   |
| 2018    | 586       | 8.09%   |
| 2013    | 560       | 7.73%   |
| 2017    | 543       | 7.5%    |
| 2016    | 529       | 7.3%    |
| 2010    | 439       | 6.06%   |
| 2020    | 425       | 5.87%   |
| 2014    | 390       | 5.38%   |
| 2021    | 366       | 5.05%   |
| 2015    | 329       | 4.54%   |
| 2008    | 264       | 3.64%   |
| 2009    | 226       | 3.12%   |
| 2007    | 91        | 1.26%   |
| 2022    | 66        | 0.91%   |
| 2006    | 36        | 0.5%    |
| Unknown | 27        | 0.37%   |
| 2005    | 9         | 0.12%   |
| 2004    | 4         | 0.06%   |
| 2023    | 2         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7243      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6202      | 84.81%  |
| Enabled  | 1111      | 15.19%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7221      | 99.7%   |
| Yes  | 22        | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2415      | 32.84%  |
| 3.01-4.0    | 2015      | 27.4%   |
| 8.01-16.0   | 1027      | 13.97%  |
| 16.01-24.0  | 947       | 12.88%  |
| 1.01-2.0    | 535       | 7.27%   |
| 2.01-3.0    | 181       | 2.46%   |
| 32.01-64.0  | 136       | 1.85%   |
| 24.01-32.0  | 37        | 0.5%    |
| 0.51-1.0    | 33        | 0.45%   |
| 64.01-256.0 | 27        | 0.37%   |
| 0.01-0.5    | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2925      | 36.58%  |
| 2.01-3.0   | 2237      | 27.97%  |
| 3.01-4.0   | 1072      | 13.41%  |
| 4.01-8.0   | 986       | 12.33%  |
| 0.51-1.0   | 534       | 6.68%   |
| 8.01-16.0  | 188       | 2.35%   |
| 0.01-0.5   | 40        | 0.5%    |
| 16.01-24.0 | 10        | 0.13%   |
| 32.01-64.0 | 3         | 0.04%   |
| Unknown    | 2         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5163      | 70%     |
| 2      | 1993      | 27.02%  |
| 3      | 152       | 2.06%   |
| 0      | 54        | 0.73%   |
| 4      | 14        | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4515      | 62.04%  |
| Yes       | 2762      | 37.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6403      | 88.2%   |
| No        | 857       | 11.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7018      | 96.64%  |
| No        | 244       | 3.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5209      | 71.17%  |
| No        | 2110      | 28.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 7243      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 894       | 11.74%  |
| Rio de Janeiro        | 403       | 5.29%   |
| Brasília             | 239       | 3.14%   |
| Curitiba              | 221       | 2.9%    |
| Belo Horizonte        | 211       | 2.77%   |
| Fortaleza             | 181       | 2.38%   |
| Porto Alegre          | 158       | 2.08%   |
| Salvador              | 119       | 1.56%   |
| Campinas              | 112       | 1.47%   |
| Recife                | 102       | 1.34%   |
| Goiânia              | 90        | 1.18%   |
| Florianópolis        | 84        | 1.1%    |
| Santo André          | 82        | 1.08%   |
| Natal                 | 79        | 1.04%   |
| Sao Luís             | 62        | 0.81%   |
| Sao José dos Campos  | 62        | 0.81%   |
| Manaus                | 62        | 0.81%   |
| Osasco                | 61        | 0.8%    |
| Campo Grande          | 60        | 0.79%   |
| Joao Pessoa           | 56        | 0.74%   |
| Niterói              | 54        | 0.71%   |
| Teresina              | 52        | 0.68%   |
| Belém                | 51        | 0.67%   |
| Maringá              | 50        | 0.66%   |
| Guarulhos             | 50        | 0.66%   |
| Uberlândia           | 47        | 0.62%   |
| Sorocaba              | 47        | 0.62%   |
| Aracaju               | 45        | 0.59%   |
| Joinville             | 44        | 0.58%   |
| Londrina              | 43        | 0.56%   |
| Ribeirao Preto        | 42        | 0.55%   |
| Maceió               | 41        | 0.54%   |
| Sao Jose              | 36        | 0.47%   |
| Cuiabá               | 36        | 0.47%   |
| Juiz de Fora          | 35        | 0.46%   |
| Canoas                | 33        | 0.43%   |
| Sao Carlos            | 32        | 0.42%   |
| Vitória              | 31        | 0.41%   |
| Sao Bernardo do Campo | 31        | 0.41%   |
| Americana             | 30        | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 1988      | 2425   | 22.05%  |
| Seagate                        | 1357      | 1622   | 15.05%  |
| Kingston                       | 853       | 1025   | 9.46%   |
| Samsung Electronics            | 636       | 823    | 7.05%   |
| Toshiba                        | 619       | 717    | 6.87%   |
| Sandisk                        | 520       | 685    | 5.77%   |
| Unknown                        | 408       | 545    | 4.53%   |
| A-DATA Technology              | 369       | 473    | 4.09%   |
| Intel                          | 268       | 326    | 2.97%   |
| Hitachi                        | 196       | 239    | 2.17%   |
| China                          | 170       | 208    | 1.89%   |
| ADATA Technology               | 170       | 198    | 1.89%   |
| Crucial                        | 164       | 220    | 1.82%   |
| SK hynix                       | 118       | 151    | 1.31%   |
| LITEON                         | 107       | 127    | 1.19%   |
| HGST                           | 104       | 124    | 1.15%   |
| Silicon Motion                 | 71        | 84     | 0.79%   |
| KingSpec                       | 60        | 68     | 0.67%   |
| SSSTC                          | 45        | 46     | 0.5%    |
| Fujitsu                        | 42        | 49     | 0.47%   |
| JMicron Technology             | 40        | 46     | 0.44%   |
| Apple                          | 37        | 47     | 0.41%   |
| Lexar                          | 36        | 46     | 0.4%    |
| Solid State Storage Technology | 34        | 45     | 0.38%   |
| Phison                         | 34        | 37     | 0.38%   |
| Netac                          | 33        | 37     | 0.37%   |
| KIOXIA                         | 33        | 39     | 0.37%   |
| Solid State Storage            | 31        | 36     | 0.34%   |
| Corsair                        | 26        | 26     | 0.29%   |
| Micron Technology              | 25        | 26     | 0.28%   |
| Realtek Semiconductor          | 24        | 31     | 0.27%   |
| PNY                            | 22        | 32     | 0.24%   |
| Unknown                        | 20        | 24     | 0.22%   |
| Hewlett-Packard                | 19        | 22     | 0.21%   |
| Smart                          | 18        | 20     | 0.2%    |
| Patriot                        | 18        | 21     | 0.2%    |
| XPG                            | 16        | 20     | 0.18%   |
| XrayDisk                       | 15        | 18     | 0.17%   |
| Gigabyte Technology            | 15        | 20     | 0.17%   |
| KingDian                       | 14        | 20     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 475       | 5.13%   |
| Kingston SA400S37240G 240GB SSD     | 297       | 3.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 260       | 2.81%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 224       | 2.42%   |
| Kingston SA400S37480G 480GB SSD     | 164       | 1.77%   |
| Toshiba MQ01ABD100 1TB              | 137       | 1.48%   |
| Kingston SA400S37120G 120GB SSD     | 136       | 1.47%   |
| WDC WD10SPZX-24Z10 1TB              | 127       | 1.37%   |
| Unknown MMC Card  32GB              | 123       | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 100       | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB            | 99        | 1.07%   |
| Intel NVMe SSD Drive 512GB          | 98        | 1.06%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 89        | 0.96%   |
| WDC WD10SPZX-75Z10T2 1TB            | 80        | 0.86%   |
| Samsung HM321HI 320GB               | 78        | 0.84%   |
| Seagate ST9500325AS 500GB           | 76        | 0.82%   |
| Toshiba MQ04ABF100 1TB              | 75        | 0.81%   |
| SanDisk NVMe SSD Drive 512GB        | 72        | 0.78%   |
| Intel SSDPEKKW256G7 256GB           | 70        | 0.76%   |
| SanDisk SSD PLUS 240GB              | 68        | 0.73%   |
| ADATA NVMe SSD Drive 256GB          | 68        | 0.73%   |
| WDC WD10JPVX-75JC3T0 1TB            | 62        | 0.67%   |
| Kingston SV300S37A120G 120GB SSD    | 62        | 0.67%   |
| Seagate Expansion 1TB               | 60        | 0.65%   |
| SanDisk SSD PLUS 120GB              | 58        | 0.63%   |
| Toshiba MQ01ABF050 500GB            | 56        | 0.6%    |
| Seagate ST2000LM007-1R8174 2TB      | 55        | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 54        | 0.58%   |
| Seagate ST500LT012-9WS142 500GB     | 53        | 0.57%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 53        | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 49        | 0.53%   |
| WDC WD10JPCX-24UE4T0 1TB            | 48        | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 48        | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 46        | 0.5%    |
| A-DATA IM2P33F3A NVMe 256GB         | 45        | 0.49%   |
| WDC WD10SPZX-75Z10T1 1TB            | 42        | 0.45%   |
| Toshiba MQ01ABD050 500GB            | 41        | 0.44%   |
| Seagate ST1000LM014-1EJ164 1TB      | 40        | 0.43%   |
| Intel NVMe SSD Drive 256GB          | 40        | 0.43%   |
| Seagate ST1000LM048-2E7172 1TB      | 38        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1774      | 2090   | 40.48%  |
| Seagate             | 1347      | 1608   | 30.74%  |
| Toshiba             | 584       | 676    | 13.33%  |
| Samsung Electronics | 284       | 328    | 6.48%   |
| Hitachi             | 196       | 239    | 4.47%   |
| HGST                | 104       | 124    | 2.37%   |
| Fujitsu             | 41        | 47     | 0.94%   |
| Unknown             | 22        | 27     | 0.5%    |
| Apple               | 13        | 16     | 0.3%    |
| SAGE                | 6         | 10     | 0.14%   |
| JMicron Technology  | 3         | 3      | 0.07%   |
| USB3.0              | 1         | 1      | 0.02%   |
| Phison              | 1         | 1      | 0.02%   |
| Maxtor 6            | 1         | 1      | 0.02%   |
| Maxtor              | 1         | 1      | 0.02%   |
| Intenso             | 1         | 1      | 0.02%   |
| IBM/Hitachi         | 1         | 2      | 0.02%   |
| External            | 1         | 1      | 0.02%   |
| CLOVER              | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 816       | 973    | 30.01%  |
| SanDisk             | 334       | 461    | 12.28%  |
| Samsung Electronics | 226       | 312    | 8.31%   |
| WDC                 | 205       | 252    | 7.54%   |
| A-DATA Technology   | 191       | 234    | 7.02%   |
| China               | 170       | 208    | 6.25%   |
| Crucial             | 155       | 208    | 5.7%    |
| LITEON              | 98        | 118    | 3.6%    |
| KingSpec            | 57        | 65     | 2.1%    |
| Lexar               | 35        | 45     | 1.29%   |
| JMicron Technology  | 31        | 37     | 1.14%   |
| Netac               | 28        | 30     | 1.03%   |
| PNY                 | 22        | 32     | 0.81%   |
| Intel               | 22        | 26     | 0.81%   |
| Apple               | 22        | 28     | 0.81%   |
| Corsair             | 21        | 21     | 0.77%   |
| Smart               | 18        | 20     | 0.66%   |
| Patriot             | 17        | 20     | 0.63%   |
| SK hynix            | 16        | 19     | 0.59%   |
| Hewlett-Packard     | 15        | 17     | 0.55%   |
| Unknown             | 13        | 14     | 0.48%   |
| LITEONIT            | 13        | 20     | 0.48%   |
| KingDian            | 13        | 19     | 0.48%   |
| Gigabyte Technology | 13        | 18     | 0.48%   |
| XrayDisk            | 10        | 11     | 0.37%   |
| Toshiba             | 10        | 11     | 0.37%   |
| Unknown             | 10        | 11     | 0.37%   |
| Seagate             | 9         | 10     | 0.33%   |
| Micron Technology   | 8         | 9      | 0.29%   |
| Win Memory          | 7         | 8      | 0.26%   |
| BHT                 | 7         | 7      | 0.26%   |
| walram              | 6         | 6      | 0.22%   |
| HUSKY               | 5         | 6      | 0.18%   |
| BIWIN               | 5         | 5      | 0.18%   |
| Transcend           | 4         | 4      | 0.15%   |
| S3+                 | 4         | 4      | 0.15%   |
| Maxtor              | 4         | 4      | 0.15%   |
| Advantech           | 4         | 5      | 0.15%   |
| Vaseky              | 3         | 4      | 0.11%   |
| RZX                 | 3         | 4      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4305      | 5177   | 49.4%   |
| SSD     | 2527      | 3381   | 29%     |
| NVMe    | 1477      | 1931   | 16.95%  |
| MMC     | 334       | 470    | 3.83%   |
| Unknown | 71        | 91     | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6026      | 8404   | 75.09%  |
| NVMe | 1477      | 1931   | 18.4%   |
| MMC  | 334       | 470    | 4.16%   |
| SAS  | 188       | 245    | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4280      | 5652   | 64.34%  |
| 0.51-1.0   | 2243      | 2751   | 33.72%  |
| 1.01-2.0   | 120       | 145    | 1.8%    |
| 3.01-4.0   | 6         | 7      | 0.09%   |
| 4.01-10.0  | 2         | 2      | 0.03%   |
| 0          | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2266      | 29.69%  |
| 251-500        | 1939      | 25.41%  |
| 501-1000       | 1367      | 17.91%  |
| 1-20           | 559       | 7.33%   |
| 51-100         | 457       | 5.99%   |
| 1001-2000      | 419       | 5.49%   |
| 21-50          | 374       | 4.9%    |
| Unknown        | 115       | 1.51%   |
| 2001-3000      | 74        | 0.97%   |
| More than 3000 | 61        | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2989      | 37.77%  |
| 21-50          | 1879      | 23.74%  |
| 51-100         | 1040      | 13.14%  |
| 101-250        | 1033      | 13.05%  |
| 251-500        | 506       | 6.39%   |
| 501-1000       | 245       | 3.1%    |
| Unknown        | 115       | 1.45%   |
| 1001-2000      | 87        | 1.1%    |
| 2001-3000      | 10        | 0.13%   |
| More than 3000 | 9         | 0.11%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 39     | 7.17%   |
| Seagate ST9500325AS 500GB           | 21        | 23     | 4.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 19        | 21     | 3.89%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 13     | 2.66%   |
| Toshiba MQ01ABD100 1TB              | 12        | 12     | 2.46%   |
| Seagate ST500LT012-9WS142 500GB     | 9         | 11     | 1.84%   |
| Seagate ST9320325AS 320GB           | 8         | 8      | 1.64%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 1.43%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 7      | 1.23%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 6         | 6      | 1.23%   |
| Toshiba MQ02ABD100H 1TB             | 6         | 9      | 1.23%   |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 1.23%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 7      | 1.23%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 6      | 1.23%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 5         | 6      | 1.02%   |
| WDC WD10JPCX-24UE4T0 1TB            | 5         | 5      | 1.02%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 6      | 1.02%   |
| Seagate ST320LT007-9ZV142 320GB     | 5         | 5      | 1.02%   |
| Seagate ST1000LM048-2E7172 1TB      | 5         | 6      | 1.02%   |
| Seagate ST1000LM014-1EJ164 1TB      | 5         | 5      | 1.02%   |
| Samsung Electronics HM321HI 320GB   | 5         | 5      | 1.02%   |
| Samsung Electronics HM160HI 160GB   | 5         | 5      | 1.02%   |
| Hitachi HTS547550A9E384 500GB       | 5         | 5      | 1.02%   |
| Seagate ST9500423AS 500GB           | 4         | 4      | 0.82%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 4         | 4      | 0.82%   |
| SanDisk SSD PLUS 480GB              | 4         | 4      | 0.82%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 4      | 0.82%   |
| HGST HCC545050A7E380 500GB          | 4         | 4      | 0.82%   |
| China SSD 120GB                     | 4         | 4      | 0.82%   |
| WDC WD7500BPKT-75PK4T0 752GB        | 3         | 3      | 0.61%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 3         | 3      | 0.61%   |
| WDC WD3200BPVT-00JJ5T0 320GB        | 3         | 5      | 0.61%   |
| WDC WD10SPZX-24Z10T0 1TB            | 3         | 4      | 0.61%   |
| WDC WD10SPZX-24Z10 1TB              | 3         | 3      | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 3      | 0.61%   |
| Toshiba MQ01ACF050 500GB            | 3         | 3      | 0.61%   |
| Toshiba MQ01ABD032 320GB            | 3         | 3      | 0.61%   |
| Toshiba MK5061GSYN 500GB            | 3         | 4      | 0.61%   |
| Toshiba MK3259GSXP 320GB            | 3         | 3      | 0.61%   |
| Seagate ST9320423AS 320GB           | 3         | 3      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 168       | 185    | 34.71%  |
| WDC                 | 89        | 99     | 18.39%  |
| Toshiba             | 71        | 79     | 14.67%  |
| Hitachi             | 30        | 33     | 6.2%    |
| Samsung Electronics | 28        | 39     | 5.79%   |
| Kingston            | 23        | 27     | 4.75%   |
| SanDisk             | 14        | 14     | 2.89%   |
| China               | 10        | 11     | 2.07%   |
| HGST                | 9         | 9      | 1.86%   |
| A-DATA Technology   | 8         | 9      | 1.65%   |
| Fujitsu             | 4         | 5      | 0.83%   |
| PNY                 | 3         | 5      | 0.62%   |
| LITEON              | 3         | 3      | 0.62%   |
| Intel               | 3         | 3      | 0.62%   |
| WALRAM              | 2         | 2      | 0.41%   |
| KingSpec            | 2         | 2      | 0.41%   |
| Crucial             | 2         | 2      | 0.41%   |
| Apple               | 2         | 2      | 0.41%   |
| XrayDisk            | 1         | 1      | 0.21%   |
| XPG                 | 1         | 1      | 0.21%   |
| SSSTC               | 1         | 1      | 0.21%   |
| SK hynix            | 1         | 1      | 0.21%   |
| Silicon Motion      | 1         | 1      | 0.21%   |
| ShiJi               | 1         | 2      | 0.21%   |
| OCZ                 | 1         | 1      | 0.21%   |
| Netac               | 1         | 1      | 0.21%   |
| Micron Technology   | 1         | 1      | 0.21%   |
| LITEONIT            | 1         | 2      | 0.21%   |
| Kross Elegance      | 1         | 1      | 0.21%   |
| JMicron Technology  | 1         | 1      | 0.21%   |
| ADATA Technology    | 1         | 1      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 168       | 185    | 43.19%  |
| WDC                 | 83        | 93     | 21.34%  |
| Toshiba             | 70        | 78     | 17.99%  |
| Hitachi             | 30        | 33     | 7.71%   |
| Samsung Electronics | 24        | 35     | 6.17%   |
| HGST                | 9         | 9      | 2.31%   |
| Fujitsu             | 4         | 5      | 1.03%   |
| Apple               | 1         | 1      | 0.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 388       | 439    | 80.33%  |
| SSD  | 81        | 89     | 16.77%  |
| NVMe | 14        | 16     | 2.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 18.18%  |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 9.09%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 9.09%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 9.09%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 9.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 9.09%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 9.09%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 9.09%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 9.09%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 36.36%  |
| WDC                 | 2         | 2      | 18.18%  |
| Toshiba             | 2         | 2      | 18.18%  |
| Seagate             | 2         | 2      | 18.18%  |
| Maxtor              | 1         | 1      | 9.09%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 5267      | 7931   | 69.42%  |
| Works    | 1835      | 2563   | 24.19%  |
| Malfunc  | 473       | 544    | 6.23%   |
| Failed   | 11        | 11     | 0.14%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6002      | 73.71%  |
| AMD                              | 682       | 8.38%   |
| ADATA Technology                 | 360       | 4.42%   |
| SanDisk                          | 222       | 2.73%   |
| Samsung Electronics              | 148       | 1.82%   |
| Solid State Storage Technology   | 122       | 1.5%    |
| SK hynix                         | 97        | 1.19%   |
| Silicon Integrated Systems [SiS] | 94        | 1.15%   |
| Silicon Motion                   | 79        | 0.97%   |
| Kingston Technology Company      | 49        | 0.6%    |
| Phison Electronics               | 44        | 0.54%   |
| Realtek Semiconductor            | 36        | 0.44%   |
| Nvidia                           | 36        | 0.44%   |
| KIOXIA                           | 31        | 0.38%   |
| VIA Technologies                 | 24        | 0.29%   |
| Toshiba America Info Systems     | 24        | 0.29%   |
| Micron/Crucial Technology        | 21        | 0.26%   |
| Lite-On Technology               | 18        | 0.22%   |
| Micron Technology                | 17        | 0.21%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.1%    |
| Union Memory (Shenzhen)          | 7         | 0.09%   |
| Marvell Technology Group         | 6         | 0.07%   |
| Netac Technology                 | 4         | 0.05%   |
| Shenzhen Longsys Electronics     | 3         | 0.04%   |
| Apple                            | 3         | 0.04%   |
| TenaFe                           | 1         | 0.01%   |
| Seagate Technology               | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |
| Lenovo                           | 1         | 0.01%   |
| INNOGRIT                         | 1         | 0.01%   |
| Beijing Starblaze Technology     | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 988       | 11.03%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 814       | 9.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 635       | 7.09%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 500       | 5.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 466       | 5.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 384       | 4.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 319       | 3.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 302       | 3.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 242       | 2.7%    |
| Intel PROSet/Wireless WiFi Software extension                                    | 205       | 2.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 202       | 2.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 152       | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 142       | 1.58%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                      | 140       | 1.56%   |
| ADATA Non-Volatile memory controller                                             | 138       | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                              | 137       | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 133       | 1.48%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 132       | 1.47%   |
| Intel Comet Lake SATA AHCI Controller                                            | 127       | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 126       | 1.41%   |
| Solid State Storage Non-Volatile memory controller                               | 122       | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 121       | 1.35%   |
| Intel Volume Management Device NVMe RAID Controller                              | 117       | 1.31%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 108       | 1.21%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 93        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 91        | 1.02%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 78        | 0.87%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 77        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 77        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 74        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 74        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 68        | 0.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 64        | 0.71%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 58        | 0.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 58        | 0.65%   |
| ADATA A Non-Volatile memory controller                                           | 57        | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 53        | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 51        | 0.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 48        | 0.54%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 46        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5857      | 67.9%   |
| NVMe | 1482      | 17.18%  |
| RAID | 720       | 8.35%   |
| IDE  | 567       | 6.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 6502      | 89.77%  |
| AMD    | 739       | 10.2%   |
| ARM    | 2         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 260       | 3.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 164       | 2.26%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 149       | 2.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 134       | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 131       | 1.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 130       | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 128       | 1.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 121       | 1.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 121       | 1.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 109       | 1.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 107       | 1.48%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 95        | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 95        | 1.31%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 91        | 1.26%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 90        | 1.24%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 90        | 1.24%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 90        | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 90        | 1.24%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 88        | 1.21%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 84        | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 81        | 1.12%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 80        | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 78        | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 75        | 1.03%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 74        | 1.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 74        | 1.02%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 69        | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 68        | 0.94%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 67        | 0.92%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 66        | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 65        | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 64        | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 63        | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 61        | 0.84%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 61        | 0.84%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 60        | 0.83%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 58        | 0.8%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 56        | 0.77%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 56        | 0.77%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 56        | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2109      | 29.11%  |
| Intel Core i7                  | 1456      | 20.09%  |
| Intel Core i3                  | 1135      | 15.66%  |
| Intel Celeron                  | 545       | 7.52%   |
| Other                          | 297       | 4.1%    |
| Intel Core 2 Duo               | 270       | 3.73%   |
| Intel Atom                     | 261       | 3.6%    |
| AMD Ryzen 5                    | 190       | 2.62%   |
| AMD Ryzen 7                    | 174       | 2.4%    |
| Intel Pentium Dual-Core        | 140       | 1.93%   |
| Intel Pentium                  | 137       | 1.89%   |
| Intel Pentium Dual             | 73        | 1.01%   |
| AMD E                          | 49        | 0.68%   |
| AMD C-60                       | 37        | 0.51%   |
| AMD E1                         | 33        | 0.46%   |
| AMD A4                         | 28        | 0.39%   |
| AMD A6                         | 27        | 0.37%   |
| Intel Genuine                  | 26        | 0.36%   |
| AMD C-70                       | 23        | 0.32%   |
| AMD A10                        | 22        | 0.3%    |
| Intel Core 2                   | 21        | 0.29%   |
| Intel Celeron Dual-Core        | 17        | 0.23%   |
| AMD C-50                       | 17        | 0.23%   |
| AMD A12                        | 14        | 0.19%   |
| AMD Ryzen 3                    | 12        | 0.17%   |
| AMD Mobile Sempron             | 12        | 0.17%   |
| Intel Celeron M                | 11        | 0.15%   |
| AMD Ryzen 9                    | 9         | 0.12%   |
| AMD Athlon II                  | 9         | 0.12%   |
| AMD Turion 64 Mobile           | 7         | 0.1%    |
| AMD Turion X2 Dual-Core Mobile | 6         | 0.08%   |
| AMD Turion II                  | 5         | 0.07%   |
| AMD Turion 64 X2 Mobile        | 5         | 0.07%   |
| AMD Phenom II                  | 5         | 0.07%   |
| AMD Athlon 64 X2               | 5         | 0.07%   |
| Intel Pentium M                | 4         | 0.06%   |
| Intel Pentium Gold             | 4         | 0.06%   |
| AMD Ryzen 7 PRO                | 4         | 0.06%   |
| AMD A8                         | 4         | 0.06%   |
| AMD V120                       | 3         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 4567      | 63.04%  |
| 4       | 2042      | 28.18%  |
| 6       | 296       | 4.09%   |
| 8       | 154       | 2.13%   |
| 1       | 150       | 2.07%   |
| 14      | 14        | 0.19%   |
| 12      | 11        | 0.15%   |
| 10      | 4         | 0.06%   |
| Unknown | 3         | 0.04%   |
| 5       | 2         | 0.03%   |
| 3       | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7243      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5473      | 75.49%  |
| 1       | 1773      | 24.46%  |
| Unknown | 3         | 0.04%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6926      | 95.12%  |
| Unknown        | 295       | 4.05%   |
| 32-bit         | 45        | 0.62%   |
| 64-bit         | 15        | 0.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1535      | 20.41%  |
| 0x306a9    | 602       | 8.01%   |
| 0x206a7    | 593       | 7.89%   |
| 0x806e9    | 394       | 5.24%   |
| 0x40651    | 341       | 4.53%   |
| 0x806ec    | 316       | 4.2%    |
| 0x906ea    | 296       | 3.94%   |
| 0x20655    | 296       | 3.94%   |
| 0x306d4    | 281       | 3.74%   |
| 0x406e3    | 270       | 3.59%   |
| 0x1067a    | 261       | 3.47%   |
| 0x806ea    | 248       | 3.3%    |
| 0x806c1    | 179       | 2.38%   |
| 0x406c4    | 161       | 2.14%   |
| 0x6fd      | 147       | 1.95%   |
| 0x08108109 | 87        | 1.16%   |
| 0x05000119 | 87        | 1.16%   |
| 0x08600103 | 84        | 1.12%   |
| 0x906e9    | 83        | 1.1%    |
| 0x30678    | 83        | 1.1%    |
| 0x706e5    | 74        | 0.98%   |
| 0x08108102 | 62        | 0.82%   |
| 0x706a1    | 61        | 0.81%   |
| 0x906ed    | 58        | 0.77%   |
| 0x306c3    | 57        | 0.76%   |
| 0x706a8    | 54        | 0.72%   |
| 0x406c3    | 54        | 0.72%   |
| 0xa0652    | 51        | 0.68%   |
| 0x806eb    | 50        | 0.66%   |
| 0x20652    | 49        | 0.65%   |
| 0x106ca    | 47        | 0.63%   |
| 0x30661    | 33        | 0.44%   |
| 0x10676    | 33        | 0.44%   |
| 0x05000029 | 28        | 0.37%   |
| 0x03000027 | 28        | 0.37%   |
| 0x506c9    | 27        | 0.36%   |
| 0x08608103 | 26        | 0.35%   |
| 0x506e3    | 24        | 0.32%   |
| 0x10661    | 24        | 0.32%   |
| 0x0810100b | 21        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1764      | 24.34%  |
| IvyBridge        | 733       | 10.12%  |
| SandyBridge      | 706       | 9.74%   |
| Haswell          | 475       | 6.56%   |
| Westmere         | 413       | 5.7%    |
| Silvermont       | 360       | 4.97%   |
| Skylake          | 353       | 4.87%   |
| Penryn           | 348       | 4.8%    |
| Broadwell        | 330       | 4.55%   |
| TigerLake        | 231       | 3.19%   |
| Core             | 230       | 3.17%   |
| Zen+             | 187       | 2.58%   |
| Bobcat           | 148       | 2.04%   |
| Goldmont plus    | 133       | 1.84%   |
| IceLake          | 115       | 1.59%   |
| Bonnell          | 99        | 1.37%   |
| Unknown          | 96        | 1.32%   |
| Zen 2            | 93        | 1.28%   |
| CometLake        | 89        | 1.23%   |
| K8 Hammer        | 43        | 0.59%   |
| Excavator        | 42        | 0.58%   |
| Goldmont         | 33        | 0.46%   |
| K10 Llano        | 32        | 0.44%   |
| Zen              | 29        | 0.4%    |
| K10              | 28        | 0.39%   |
| Alderlake Hybrid | 26        | 0.36%   |
| Zen 3            | 25        | 0.35%   |
| P6               | 24        | 0.33%   |
| Jaguar           | 21        | 0.29%   |
| Nehalem          | 12        | 0.17%   |
| K8 & K10 hybrid  | 11        | 0.15%   |
| Piledriver       | 10        | 0.14%   |
| Puma             | 4         | 0.06%   |
| Steamroller      | 2         | 0.03%   |
| NetBurst         | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6238      | 66.47%  |
| Nvidia                           | 1885      | 20.09%  |
| AMD                              | 1144      | 12.19%  |
| Silicon Integrated Systems [SiS] | 94        | 1%      |
| VIA Technologies                 | 24        | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 724       | 7.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 692       | 7.18%   |
| Intel HD Graphics 620                                                                    | 505       | 5.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 400       | 4.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 388       | 4.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 379       | 3.93%   |
| Intel HD Graphics 5500                                                                   | 310       | 3.22%   |
| Intel UHD Graphics 620                                                                   | 288       | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 288       | 2.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 281       | 2.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 272       | 2.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 258       | 2.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 256       | 2.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 193       | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 186       | 1.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 167       | 1.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 146       | 1.52%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 137       | 1.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 137       | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 133       | 1.38%   |
| Intel HD Graphics 630                                                                    | 103       | 1.07%   |
| Nvidia TU117M                                                                            | 102       | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 102       | 1.06%   |
| Nvidia GP108M [GeForce MX150]                                                            | 96        | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 95        | 0.99%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 91        | 0.94%   |
| AMD Renoir                                                                               | 91        | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 89        | 0.92%   |
| Nvidia GM108M [GeForce MX110]                                                            | 89        | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 84        | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 84        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 74        | 0.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 70        | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 64        | 0.66%   |
| Nvidia GP108M [GeForce MX250]                                                            | 55        | 0.57%   |
| AMD Lucienne                                                                             | 54        | 0.56%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 51        | 0.53%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 48        | 0.5%    |
| Nvidia GP108M [GeForce MX230]                                                            | 44        | 0.46%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 44        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 4243      | 58.47%  |
| Intel + Nvidia | 1605      | 22.12%  |
| 1 x AMD        | 533       | 7.34%   |
| Intel + AMD    | 387       | 5.33%   |
| AMD + Nvidia   | 149       | 2.05%   |
| 1 x Nvidia     | 130       | 1.79%   |
| 1 x SiS        | 94        | 1.3%    |
| 2 x AMD        | 74        | 1.02%   |
| 1 x VIA        | 24        | 0.33%   |
| 2 x Intel      | 14        | 0.19%   |
| Other          | 4         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 5928      | 81.02%  |
| Proprietary | 1181      | 16.14%  |
| Unknown     | 208       | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5166      | 69.85%  |
| 1.01-2.0   | 1042      | 14.09%  |
| 0.01-0.5   | 533       | 7.21%   |
| 3.01-4.0   | 382       | 5.16%   |
| 0.51-1.0   | 176       | 2.38%   |
| 5.01-6.0   | 67        | 0.91%   |
| 2.01-3.0   | 16        | 0.22%   |
| 7.01-8.0   | 12        | 0.16%   |
| 8.01-16.0  | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 1554      | 18.84%  |
| AU Optronics            | 1507      | 18.27%  |
| Chimei Innolux          | 1206      | 14.62%  |
| LG Display              | 1133      | 13.73%  |
| Samsung Electronics     | 842       | 10.21%  |
| Goldstar                | 436       | 5.29%   |
| AOC                     | 172       | 2.09%   |
| Dell                    | 166       | 2.01%   |
| Chi Mei Optoelectronics | 159       | 1.93%   |
| InfoVision              | 122       | 1.48%   |
| PANDA                   | 117       | 1.42%   |
| Philips                 | 95        | 1.15%   |
| Apple                   | 88        | 1.07%   |
| Lenovo                  | 59        | 0.72%   |
| Acer                    | 56        | 0.68%   |
| CPT                     | 49        | 0.59%   |
| HannStar                | 47        | 0.57%   |
| LG Philips              | 38        | 0.46%   |
| Sony                    | 33        | 0.4%    |
| SLD                     | 32        | 0.39%   |
| InnoLux Display         | 30        | 0.36%   |
| Hewlett-Packard         | 30        | 0.36%   |
| Sharp                   | 23        | 0.28%   |
| MTD                     | 19        | 0.23%   |
| KDC                     | 14        | 0.17%   |
| Panasonic               | 13        | 0.16%   |
| BenQ                    | 11        | 0.13%   |
| Toshiba                 | 10        | 0.12%   |
| STA                     | 10        | 0.12%   |
| ASUSTek Computer        | 10        | 0.12%   |
| Unknown                 | 9         | 0.11%   |
| SKY                     | 9         | 0.11%   |
| GDH                     | 9         | 0.11%   |
| Unknown (XXX)           | 7         | 0.08%   |
| NCS                     | 7         | 0.08%   |
| Valve                   | 6         | 0.07%   |
| RTK                     | 6         | 0.07%   |
| MStar                   | 6         | 0.07%   |
| ITE                     | 6         | 0.07%   |
| HB@                     | 6         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 119       | 1.43%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 119       | 1.43%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 114       | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 109       | 1.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 103       | 1.24%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 102       | 1.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 101       | 1.22%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 98        | 1.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 82        | 0.99%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 75        | 0.9%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 73        | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 73        | 0.88%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 70        | 0.84%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 68        | 0.82%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 64        | 0.77%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.75%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 60        | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 58        | 0.7%    |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 58        | 0.7%    |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 57        | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 55        | 0.66%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 54        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 53        | 0.64%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 52        | 0.63%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 48        | 0.58%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.57%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 47        | 0.57%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 46        | 0.55%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 46        | 0.55%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 45        | 0.54%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 45        | 0.54%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 42        | 0.51%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 42        | 0.51%   |
| AU Optronics LCD Monitor AUO193C 1366x768 310x170mm 13.9-inch        | 40        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 39        | 0.47%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 38        | 0.46%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 38        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch      | 37        | 0.45%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                 | 36        | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4335      | 55.08%  |
| 1920x1080 (FHD)    | 2281      | 28.98%  |
| 1280x800 (WXGA)    | 307       | 3.9%    |
| 1600x900 (HD+)     | 171       | 2.17%   |
| 2560x1080          | 161       | 2.05%   |
| 3840x2160 (4K)     | 110       | 1.4%    |
| 1440x900 (WXGA+)   | 93        | 1.18%   |
| 1360x768           | 76        | 0.97%   |
| 2560x1440 (QHD)    | 59        | 0.75%   |
| 1920x1200 (WUXGA)  | 49        | 0.62%   |
| 1024x600           | 42        | 0.53%   |
| 1280x1024 (SXGA)   | 31        | 0.39%   |
| 1680x1050 (WSXGA+) | 29        | 0.37%   |
| 1024x768 (XGA)     | 21        | 0.27%   |
| 1920x540           | 17        | 0.22%   |
| 2560x1600          | 14        | 0.18%   |
| 1280x720 (HD)      | 10        | 0.13%   |
| 2288x1287          | 8         | 0.1%    |
| Unknown            | 8         | 0.1%    |
| 800x1280           | 6         | 0.08%   |
| 3840x2400          | 6         | 0.08%   |
| 2880x1800          | 4         | 0.05%   |
| 3840x1080          | 3         | 0.04%   |
| 3440x1440          | 3         | 0.04%   |
| 3200x1800 (QHD+)   | 3         | 0.04%   |
| 1280x960           | 3         | 0.04%   |
| 2160x1440          | 2         | 0.03%   |
| 1024x576           | 2         | 0.03%   |
| 4240x1080          | 1         | 0.01%   |
| 3926x1080          | 1         | 0.01%   |
| 3600x1080          | 1         | 0.01%   |
| 3286x1080          | 1         | 0.01%   |
| 3200x2000          | 1         | 0.01%   |
| 2880x900           | 1         | 0.01%   |
| 2646x800           | 1         | 0.01%   |
| 2640x800           | 1         | 0.01%   |
| 2400x1600          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |
| 2256x1504          | 1         | 0.01%   |
| 2160x1350          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3536      | 42.94%  |
| 14      | 1557      | 18.91%  |
| 13      | 1320      | 16.03%  |
| 21      | 244       | 2.96%   |
| 23      | 211       | 2.56%   |
| 17      | 186       | 2.26%   |
| 18      | 172       | 2.09%   |
| 34      | 146       | 1.77%   |
| 24      | 122       | 1.48%   |
| 11      | 114       | 1.38%   |
| 27      | 98        | 1.19%   |
| 12      | 56        | 0.68%   |
| 31      | 52        | 0.63%   |
| 20      | 50        | 0.61%   |
| Unknown | 50        | 0.61%   |
| 19      | 48        | 0.58%   |
| 10      | 46        | 0.56%   |
| 40      | 31        | 0.38%   |
| 28      | 25        | 0.3%    |
| 72      | 19        | 0.23%   |
| 32      | 18        | 0.22%   |
| 84      | 17        | 0.21%   |
| 54      | 17        | 0.21%   |
| 52      | 17        | 0.21%   |
| 22      | 17        | 0.21%   |
| 16      | 16        | 0.19%   |
| 47      | 7         | 0.09%   |
| 46      | 7         | 0.09%   |
| 37      | 7         | 0.09%   |
| 7       | 6         | 0.07%   |
| 26      | 5         | 0.06%   |
| 58      | 3         | 0.04%   |
| 48      | 3         | 0.04%   |
| 65      | 2         | 0.02%   |
| 142     | 1         | 0.01%   |
| 60      | 1         | 0.01%   |
| 57      | 1         | 0.01%   |
| 55      | 1         | 0.01%   |
| 49      | 1         | 0.01%   |
| 43      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6091      | 74.55%  |
| 401-500        | 523       | 6.4%    |
| 501-600        | 416       | 5.09%   |
| 201-300        | 411       | 5.03%   |
| 351-400        | 286       | 3.5%    |
| 701-800        | 164       | 2.01%   |
| 601-700        | 84        | 1.03%   |
| 1001-1500      | 60        | 0.73%   |
| Unknown        | 50        | 0.61%   |
| 801-900        | 39        | 0.48%   |
| 1501-2000      | 36        | 0.44%   |
| 1-100          | 6         | 0.07%   |
| 901-1000       | 3         | 0.04%   |
| More than 2000 | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6421      | 88.9%   |
| 16/10   | 519       | 7.19%   |
| 21/9    | 165       | 2.28%   |
| 4/3     | 40        | 0.55%   |
| 5/4     | 31        | 0.43%   |
| Unknown | 24        | 0.33%   |
| 3/2     | 13        | 0.18%   |
| 0.67    | 6         | 0.08%   |
| 32/9    | 3         | 0.04%   |
| 1.00    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3517      | 42.76%  |
| 81-90          | 2727      | 33.16%  |
| 201-250        | 516       | 6.27%   |
| 351-500        | 222       | 2.7%    |
| 141-150        | 179       | 2.18%   |
| 151-200        | 170       | 2.07%   |
| 71-80          | 146       | 1.78%   |
| 121-130        | 133       | 1.62%   |
| 51-60          | 114       | 1.39%   |
| 301-350        | 100       | 1.22%   |
| More than 1000 | 81        | 0.98%   |
| 501-1000       | 58        | 0.71%   |
| Unknown        | 50        | 0.61%   |
| 41-50          | 46        | 0.56%   |
| 61-70          | 43        | 0.52%   |
| 251-300        | 40        | 0.49%   |
| 91-100         | 34        | 0.41%   |
| 131-140        | 30        | 0.36%   |
| 111-120        | 13        | 0.16%   |
| 1-40           | 6         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 4479      | 55.73%  |
| 121-160       | 2013      | 25.05%  |
| 51-100        | 1226      | 15.25%  |
| 161-240       | 130       | 1.62%   |
| 1-50          | 116       | 1.44%   |
| Unknown       | 50        | 0.62%   |
| More than 240 | 23        | 0.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5842      | 78.65%  |
| 2     | 1324      | 17.82%  |
| 0     | 197       | 2.65%   |
| 3     | 63        | 0.85%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5283      | 41.65%  |
| Qualcomm Atheros                  | 3162      | 24.93%  |
| Intel                             | 2310      | 18.21%  |
| Broadcom                          | 691       | 5.45%   |
| JMicron Technology                | 201       | 1.58%   |
| Marvell Technology Group          | 184       | 1.45%   |
| Broadcom Limited                  | 149       | 1.17%   |
| Ralink                            | 130       | 1.02%   |
| Silicon Integrated Systems [SiS]  | 94        | 0.74%   |
| Ralink Technology                 | 84        | 0.66%   |
| TP-Link                           | 60        | 0.47%   |
| Samsung Electronics               | 52        | 0.41%   |
| Motorola PCS                      | 31        | 0.24%   |
| ASIX Electronics                  | 30        | 0.24%   |
| Nvidia                            | 25        | 0.2%    |
| VIA Technologies                  | 24        | 0.19%   |
| Qualcomm Atheros Communications   | 24        | 0.19%   |
| Xiaomi                            | 23        | 0.18%   |
| MediaTek                          | 22        | 0.17%   |
| D-Link                            | 17        | 0.13%   |
| ICS Advent                        | 10        | 0.08%   |
| D-Link System                     | 10        | 0.08%   |
| DisplayLink                       | 8         | 0.06%   |
| LG Electronics                    | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| Dell                              | 5         | 0.04%   |
| Huawei Technologies               | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Qualcomm                          | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| AMD                               | 3         | 0.02%   |
| OPPO Electronics                  | 2         | 0.02%   |
| NetGear                           | 2         | 0.02%   |
| Microsoft                         | 2         | 0.02%   |
| Micro Star International          | 2         | 0.02%   |
| ASUSTek Computer                  | 2         | 0.02%   |
| Arduino SA                        | 2         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.01%   |
| Spreadtrum Communications         | 1         | 0.01%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3063      | 22.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1422      | 10.23%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 846       | 6.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 761       | 5.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 577       | 4.15%   |
| Intel Wi-Fi 6 AX200                                               | 319       | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 305       | 2.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 293       | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 291       | 2.09%   |
| Intel Wi-Fi 6 AX201                                               | 218       | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 217       | 1.56%   |
| Intel Wireless 7265                                               | 169       | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 160       | 1.15%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 149       | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 132       | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 121       | 0.87%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 110       | 0.79%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 102       | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 98        | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 98        | 0.71%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 91        | 0.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 89        | 0.64%   |
| Intel Wireless 7260                                               | 87        | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 84        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 81        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 80        | 0.58%   |
| Intel Wireless 3165                                               | 80        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 79        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 77        | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 74        | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 72        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 69        | 0.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 68        | 0.49%   |
| Intel Centrino Advanced-N 6235                                    | 67        | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 64        | 0.46%   |
| Intel Wireless 3160                                               | 63        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 62        | 0.45%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 61        | 0.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 59        | 0.42%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 58        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 2974      | 40.89%  |
| Intel                                 | 2254      | 30.99%  |
| Realtek Semiconductor                 | 1104      | 15.18%  |
| Broadcom                              | 497       | 6.83%   |
| Ralink                                | 130       | 1.79%   |
| Broadcom Limited                      | 94        | 1.29%   |
| Ralink Technology                     | 84        | 1.15%   |
| TP-Link                               | 45        | 0.62%   |
| Qualcomm Atheros Communications       | 24        | 0.33%   |
| MediaTek                              | 20        | 0.27%   |
| D-Link                                | 17        | 0.23%   |
| D-Link System                         | 10        | 0.14%   |
| Dell                                  | 4         | 0.05%   |
| Edimax Technology                     | 3         | 0.04%   |
| NetGear                               | 2         | 0.03%   |
| Microsoft                             | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Sierra Wireless                       | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Linksys                               | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 846       | 11.57%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 761       | 10.41%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 577       | 7.89%   |
| Intel Wi-Fi 6 AX200                                                     | 319       | 4.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 305       | 4.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 293       | 4.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 291       | 3.98%   |
| Intel Wi-Fi 6 AX201                                                     | 218       | 2.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 217       | 2.97%   |
| Intel Wireless 7265                                                     | 169       | 2.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 160       | 2.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 132       | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 121       | 1.66%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 102       | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 98        | 1.34%   |
| Intel Wireless 7260                                                     | 87        | 1.19%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 84        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 81        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 80        | 1.09%   |
| Intel Wireless 3165                                                     | 80        | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 74        | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 69        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 67        | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 64        | 0.88%   |
| Intel Wireless 3160                                                     | 63        | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 61        | 0.83%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 59        | 0.81%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 58        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 57        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 57        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 51        | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 51        | 0.7%    |
| Intel Wireless 8265 / 8275                                              | 51        | 0.7%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 51        | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 48        | 0.66%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 48        | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 47        | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 45        | 0.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 42        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4724      | 72.68%  |
| Qualcomm Atheros                 | 415       | 6.38%   |
| Intel                            | 336       | 5.17%   |
| Broadcom                         | 267       | 4.11%   |
| JMicron Technology               | 201       | 3.09%   |
| Marvell Technology Group         | 184       | 2.83%   |
| Silicon Integrated Systems [SiS] | 94        | 1.45%   |
| Broadcom Limited                 | 61        | 0.94%   |
| Samsung Electronics              | 35        | 0.54%   |
| ASIX Electronics                 | 30        | 0.46%   |
| VIA Technologies                 | 24        | 0.37%   |
| Nvidia                           | 24        | 0.37%   |
| Motorola PCS                     | 24        | 0.37%   |
| Xiaomi                           | 23        | 0.35%   |
| TP-Link                          | 15        | 0.23%   |
| ICS Advent                       | 10        | 0.15%   |
| DisplayLink                      | 8         | 0.12%   |
| Lenovo                           | 5         | 0.08%   |
| Attansic Technology              | 4         | 0.06%   |
| Qualcomm                         | 3         | 0.05%   |
| LG Electronics                   | 3         | 0.05%   |
| OPPO Electronics                 | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| Spreadtrum Communications        | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.02%   |
| MediaTek                         | 1         | 0.02%   |
| Huawei Technologies              | 1         | 0.02%   |
| Apple                            | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3063      | 46.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1422      | 21.76%  |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 149       | 2.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 110       | 1.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 98        | 1.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 91        | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 89        | 1.36%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 79        | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 77        | 1.18%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 72        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 62        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 56        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 54        | 0.83%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 52        | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 43        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                              | 38        | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 38        | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 36        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 35        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 33        | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                                          | 32        | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 30        | 0.46%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 30        | 0.46%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 27        | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 25        | 0.38%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 24        | 0.37%   |
| Motorola PCS moto g(40) fusion                                                 | 24        | 0.37%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 23        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 22        | 0.34%   |
| Intel Ethernet Connection I219-LM                                              | 22        | 0.34%   |
| Intel 82577LM Gigabit Network Connection                                       | 22        | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 21        | 0.32%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 21        | 0.32%   |
| Intel Ethernet Connection I218-LM                                              | 20        | 0.31%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 18        | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 18        | 0.28%   |
| Intel Ethernet Connection (13) I219-LM                                         | 18        | 0.28%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 17        | 0.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 17        | 0.26%   |
| Intel Ethernet Connection I217-LM                                              | 16        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7016      | 52.12%  |
| Ethernet | 6393      | 47.49%  |
| Modem    | 42        | 0.31%   |
| Unknown  | 11        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6053      | 79.55%  |
| Ethernet | 1554      | 20.42%  |
| Modem    | 1         | 0.01%   |
| Unknown  | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 6020      | 82.92%  |
| 1     | 983       | 13.54%  |
| 0     | 246       | 3.39%   |
| 3     | 11        | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5650      | 75.88%  |
| Yes  | 1796      | 24.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1916      | 36.55%  |
| Qualcomm Atheros Communications | 1508      | 28.77%  |
| Lite-On Technology              | 662       | 12.63%  |
| Broadcom                        | 206       | 3.93%   |
| Realtek Semiconductor           | 183       | 3.49%   |
| IMC Networks                    | 137       | 2.61%   |
| Foxconn / Hon Hai               | 121       | 2.31%   |
| Cambridge Silicon Radio         | 97        | 1.85%   |
| Apple                           | 87        | 1.66%   |
| Dell                            | 79        | 1.51%   |
| Hewlett-Packard                 | 57        | 1.09%   |
| Ralink                          | 47        | 0.9%    |
| Smart Modular Technologies      | 42        | 0.8%    |
| Qcom                            | 26        | 0.5%    |
| Ralink Technology               | 17        | 0.32%   |
| Foxconn International           | 13        | 0.25%   |
| Alps Electric                   | 13        | 0.25%   |
| Askey Computer                  | 10        | 0.19%   |
| Toshiba                         | 5         | 0.1%    |
| Opticis                         | 5         | 0.1%    |
| Micro Star International        | 4         | 0.08%   |
| ASUSTek Computer                | 4         | 0.08%   |
| Syntek                          | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 866       | 16.52%  |
| Intel Bluetooth wireless interface                                                  | 614       | 11.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 525       | 10.02%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 373       | 7.12%   |
| Intel AX200 Bluetooth                                                               | 315       | 6.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 241       | 4.6%    |
| Intel AX201 Bluetooth                                                               | 217       | 4.14%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 136       | 2.59%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 130       | 2.48%   |
| Realtek Bluetooth Radio                                                             | 123       | 2.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 121       | 2.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 97        | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 95        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 93        | 1.77%   |
| Lite-On Bluetooth Device                                                            | 88        | 1.68%   |
| IMC Networks Bluetooth Radio                                                        | 69        | 1.32%   |
| Intel Bluetooth Device                                                              | 68        | 1.3%    |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 63        | 1.2%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 1.13%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 59        | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 56        | 1.07%   |
| Ralink RT3290 Bluetooth                                                             | 47        | 0.9%    |
| Smart Modular Bluetooth Device                                                      | 42        | 0.8%    |
| Apple Bluetooth Host Controller                                                     | 41        | 0.78%   |
| Dell Wireless 365 Bluetooth                                                         | 34        | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 32        | 0.61%   |
| IMC Networks Bluetooth Device                                                       | 30        | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 30        | 0.57%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 28        | 0.53%   |
| Apple Bluetooth USB Host Controller                                                 | 27        | 0.52%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.46%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 22        | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 21        | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 20        | 0.38%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 18        | 0.34%   |
| Lite-On Wireless_Device                                                             | 17        | 0.32%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 0.32%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 16        | 0.31%   |
| Realtek RTL8723A Bluetooth                                                          | 15        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6205      | 74.12%  |
| Nvidia                                          | 918       | 10.97%  |
| AMD                                             | 772       | 9.22%   |
| Silicon Integrated Systems [SiS]                | 94        | 1.12%   |
| C-Media Electronics                             | 72        | 0.86%   |
| Logitech                                        | 48        | 0.57%   |
| Generalplus Technology                          | 46        | 0.55%   |
| VIA Technologies                                | 24        | 0.29%   |
| Kingston Technology                             | 23        | 0.27%   |
| JMTek                                           | 19        | 0.23%   |
| Texas Instruments                               | 12        | 0.14%   |
| Corsair                                         | 11        | 0.13%   |
| Realtek Semiconductor                           | 10        | 0.12%   |
| Plantronics                                     | 10        | 0.12%   |
| Microsoft                                       | 10        | 0.12%   |
| GN Netcom                                       | 9         | 0.11%   |
| Sony                                            | 6         | 0.07%   |
| Samsung Electronics                             | 6         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.07%   |
| Samson Technologies                             | 4         | 0.05%   |
| Razer USA                                       | 4         | 0.05%   |
| JBL                                             | 4         | 0.05%   |
| BR23                                            | 4         | 0.05%   |
| SteelSeries ApS                                 | 3         | 0.04%   |
| Meizu                                           | 3         | 0.04%   |
| Lenovo                                          | 3         | 0.04%   |
| Goldvish                                        | 3         | 0.04%   |
| Focusrite-Novation                              | 3         | 0.04%   |
| Dell                                            | 3         | 0.04%   |
| BEHRINGER International                         | 3         | 0.04%   |
| Turtle Beach                                    | 2         | 0.02%   |
| Tdlasunnic                                      | 2         | 0.02%   |
| M-Audio                                         | 2         | 0.02%   |
| EDFIER                                          | 2         | 0.02%   |
| BY EDIFIER                                      | 2         | 0.02%   |
| Astro Gaming                                    | 2         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech)    | 1         | 0.01%   |
| Winbond Electronics                             | 1         | 0.01%   |
| Trust                                           | 1         | 0.01%   |
| Tenx Technology                                 | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1128      | 11.55%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 942       | 9.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 497       | 5.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 424       | 4.34%   |
| Intel 8 Series HD Audio Controller                                                                | 402       | 4.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 398       | 4.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 396       | 4.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 387       | 3.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 342       | 3.5%    |
| Intel Broadwell-U Audio Controller                                                                | 329       | 3.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 327       | 3.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 292       | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 276       | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 230       | 2.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 211       | 2.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 187       | 1.92%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 157       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 153       | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 150       | 1.54%   |
| AMD Wrestler HDMI Audio                                                                           | 140       | 1.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 133       | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 125       | 1.28%   |
| AMD FCH Azalia Controller                                                                         | 118       | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 106       | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 104       | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 95        | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 93        | 0.95%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 91        | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 86        | 0.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 77        | 0.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 74        | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 69        | 0.71%   |
| Intel Comet Lake PCH cAVS                                                                         | 69        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 56        | 0.57%   |
| Generalplus Technology USB Audio Device                                                           | 46        | 0.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 42        | 0.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 42        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 40        | 0.41%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 38        | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 547       | 18.86%  |
| Samsung Electronics | 398       | 13.72%  |
| Unknown             | 276       | 9.51%   |
| SK hynix            | 273       | 9.41%   |
| Kingston            | 264       | 9.1%    |
| A-DATA Technology   | 235       | 8.1%    |
| Teikon              | 152       | 5.24%   |
| Micron Technology   | 124       | 4.27%   |
| Smart Brazil        | 110       | 3.79%   |
| Crucial             | 77        | 2.65%   |
| Corsair             | 64        | 2.21%   |
| High Bridge         | 61        | 2.1%    |
| Elpida              | 44        | 1.52%   |
| Unknown (ABCD)      | 31        | 1.07%   |
| Unknown             | 25        | 0.86%   |
| Multilaser          | 24        | 0.83%   |
| Apacer              | 18        | 0.62%   |
| Nanya Technology    | 17        | 0.59%   |
| Kllisre             | 14        | 0.48%   |
| Patriot             | 13        | 0.45%   |
| Ramaxel Technology  | 12        | 0.41%   |
| HT Micron           | 11        | 0.38%   |
| PUSKILL             | 8         | 0.28%   |
| Smart Modular       | 7         | 0.24%   |
| Avant               | 6         | 0.21%   |
| Unknown (0x0B5E)    | 5         | 0.17%   |
| Atermiter           | 5         | 0.17%   |
| Team                | 4         | 0.14%   |
| RZX                 | 4         | 0.14%   |
| Carry               | 4         | 0.14%   |
| Walton Chaintech    | 3         | 0.1%    |
| Super Talent        | 3         | 0.1%    |
| Qimonda             | 3         | 0.1%    |
| Kreton              | 3         | 0.1%    |
| Kingmax             | 3         | 0.1%    |
| HBS                 | 3         | 0.1%    |
| G.Skill             | 3         | 0.1%    |
| Unknown (8A02)      | 2         | 0.07%   |
| Unknown (898F)      | 2         | 0.07%   |
| Unknown (0xAD0A)    | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 78        | 2.47%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 50        | 1.59%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 49        | 1.55%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 45        | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 45        | 1.43%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 43        | 1.36%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 39        | 1.24%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 38        | 1.21%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 33        | 1.05%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 31        | 0.98%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 31        | 0.98%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 25        | 0.79%   |
| Unknown                                                          | 25        | 0.79%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.76%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 23        | 0.73%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 23        | 0.73%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 23        | 0.73%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 22        | 0.7%    |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 21        | 0.67%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 21        | 0.67%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 20        | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.63%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 19        | 0.6%    |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 18        | 0.57%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 18        | 0.57%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 18        | 0.57%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 17        | 0.54%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 16        | 0.51%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 16        | 0.51%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 16        | 0.51%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 15        | 0.48%   |
| A-DATA RAM AM1P26KC4U1-BACS 4GB SODIMM DDR4 2667MT/s             | 15        | 0.48%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 15        | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 14        | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.44%   |
| Micron RAM 53E1G32D4NQ-046 2GB Row Of Chips LPDDR4 4267MT/s      | 14        | 0.44%   |
| A-DATA RAM 4JQA-0622AC 4GB SODIMM DDR4 3200MT/s                  | 14        | 0.44%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 13        | 0.41%   |
| Teikon RAM TMA851S6AFR6N-UHHC 4GB SODIMM DDR4 2400MT/s           | 13        | 0.41%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s           | 13        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1091      | 45.44%  |
| DDR4    | 941       | 39.19%  |
| DDR2    | 148       | 6.16%   |
| LPDDR4  | 68        | 2.83%   |
| SDRAM   | 64        | 2.67%   |
| LPDDR3  | 30        | 1.25%   |
| DRAM    | 18        | 0.75%   |
| DDR5    | 16        | 0.67%   |
| DDR     | 12        | 0.5%    |
| Unknown | 7         | 0.29%   |
| LPDDR5  | 5         | 0.21%   |
| RAM     | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2276      | 94.99%  |
| Row Of Chips | 95        | 3.96%   |
| Unknown      | 14        | 0.58%   |
| DIMM         | 9         | 0.38%   |
| Chip         | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 1089      | 39.7%   |
| 8192  | 733       | 26.72%  |
| 2048  | 545       | 19.87%  |
| 16384 | 256       | 9.33%   |
| 1024  | 87        | 3.17%   |
| 32768 | 28        | 1.02%   |
| 512   | 5         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 691       | 25.53%  |
| 2667    | 508       | 18.77%  |
| 2400    | 308       | 11.38%  |
| 1334    | 229       | 8.46%   |
| 3200    | 199       | 7.35%   |
| 1333    | 190       | 7.02%   |
| Unknown | 91        | 3.36%   |
| 2133    | 88        | 3.25%   |
| 800     | 60        | 2.22%   |
| 667     | 57        | 2.11%   |
| 1066    | 46        | 1.7%    |
| 1067    | 40        | 1.48%   |
| 4199    | 39        | 1.44%   |
| 4267    | 25        | 0.92%   |
| 975     | 22        | 0.81%   |
| 533     | 22        | 0.81%   |
| 2048    | 20        | 0.74%   |
| 4800    | 16        | 0.59%   |
| 1867    | 11        | 0.41%   |
| 3266    | 10        | 0.37%   |
| 8400    | 6         | 0.22%   |
| 6400    | 5         | 0.18%   |
| 3733    | 5         | 0.18%   |
| 1200    | 4         | 0.15%   |
| 2933    | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 3466    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 1866    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1400    | 1         | 0.04%   |
| 666     | 1         | 0.04%   |
| 2       | 1         | 0.04%   |
| 1       | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 38.6%   |
| Seiko Epson         | 21        | 36.84%  |
| Samsung Electronics | 5         | 8.77%   |
| Canon               | 5         | 8.77%   |
| Brother Industries  | 2         | 3.51%   |
| Xerox               | 1         | 1.75%   |
| MIIIW               | 1         | 1.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                    | 7         | 12.28%  |
| HP LaserJet 1020                              | 3         | 5.26%   |
| HP DeskJet 2700 series                        | 3         | 5.26%   |
| Seiko Epson L6160 Series                      | 2         | 3.51%   |
| Seiko Epson L396 Series                       | 2         | 3.51%   |
| Seiko Epson L355 Series                       | 2         | 3.51%   |
| Samsung M2020 Series                          | 2         | 3.51%   |
| HP LaserJet Professional P1102w               | 2         | 3.51%   |
| HP Ink Tank Wireless 410 series               | 2         | 3.51%   |
| HP Deskjet 3050 J610 series                   | 2         | 3.51%   |
| HP Deskjet 2540 series                        | 2         | 3.51%   |
| Canon G3000 series                            | 2         | 3.51%   |
| Xerox Phaser 3040                             | 1         | 1.75%   |
| Seiko Epson XP-230 Series                     | 1         | 1.75%   |
| Seiko Epson Thermal Receipt Printer [TM-T20]  | 1         | 1.75%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.75%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]  | 1         | 1.75%   |
| Seiko Epson L805 Series                       | 1         | 1.75%   |
| Seiko Epson L380 Series                       | 1         | 1.75%   |
| Seiko Epson L220 Series                       | 1         | 1.75%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.75%   |
| Samsung SCX-4623 Series                       | 1         | 1.75%   |
| Samsung SCX-4200 series                       | 1         | 1.75%   |
| Samsung M332x 382x 402x Series                | 1         | 1.75%   |
| MIIIW MW Keyboard Air Mini                    | 1         | 1.75%   |
| HP LaserJet 1018                              | 1         | 1.75%   |
| HP DeskJet F4200 series                       | 1         | 1.75%   |
| HP DeskJet F4100 Printer series               | 1         | 1.75%   |
| HP DeskJet D1360                              | 1         | 1.75%   |
| HP DeskJet 3630 series                        | 1         | 1.75%   |
| HP DeskJet 2300 series                        | 1         | 1.75%   |
| HP DeskJet 2130 series                        | 1         | 1.75%   |
| HP Deskjet 1510                               | 1         | 1.75%   |
| Canon G4010 series                            | 1         | 1.75%   |
| Canon G4000 series                            | 1         | 1.75%   |
| Canon G3010 series                            | 1         | 1.75%   |
| Brother HL-5250DN Printer                     | 1         | 1.75%   |
| Brother DCP-7040                              | 1         | 1.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 60%     |
| Hewlett-Packard | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HP ScanJet 2400c                   | 1         | 20%     |
| HP Scanjet 200                     | 1         | 20%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30      | 1         | 20%     |
| Canon CanoScan LiDE 110            | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1405      | 21.14%  |
| Microdia                               | 808       | 12.16%  |
| Realtek Semiconductor                  | 671       | 10.09%  |
| Quanta                                 | 617       | 9.28%   |
| Silicon Motion                         | 539       | 8.11%   |
| Sunplus Innovation Technology          | 505       | 7.6%    |
| IMC Networks                           | 308       | 4.63%   |
| Bison Electronics                      | 290       | 4.36%   |
| Suyin                                  | 281       | 4.23%   |
| Syntek                                 | 215       | 3.23%   |
| Acer                                   | 162       | 2.44%   |
| Alcor Micro                            | 127       | 1.91%   |
| Apple                                  | 89        | 1.34%   |
| Cheng Uei Precision Industry (Foxlink) | 84        | 1.26%   |
| Logitech                               | 58        | 0.87%   |
| Samsung Electronics                    | 56        | 0.84%   |
| Ricoh                                  | 50        | 0.75%   |
| ALi                                    | 42        | 0.63%   |
| Sonix Technology                       | 35        | 0.53%   |
| Lite-On Technology                     | 24        | 0.36%   |
| Importek                               | 24        | 0.36%   |
| OmniVision Technologies                | 23        | 0.35%   |
| Z-Star Microelectronics                | 20        | 0.3%    |
| icSpring                               | 19        | 0.29%   |
| Unknown                                | 18        | 0.27%   |
| Y Media                                | 13        | 0.2%    |
| Lenovo                                 | 12        | 0.18%   |
| Generalplus Technology                 | 12        | 0.18%   |
| SunplusIT                              | 11        | 0.17%   |
| LG Electronics                         | 10        | 0.15%   |
| Intel                                  | 9         | 0.14%   |
| Pixart Imaging                         | 8         | 0.12%   |
| Primax Electronics                     | 7         | 0.11%   |
| Microsoft                              | 7         | 0.11%   |
| Shenzhen Kingcome Optoelectronic       | 6         | 0.09%   |
| Jieli Technology                       | 6         | 0.09%   |
| Image Processor                        | 6         | 0.09%   |
| Camera                                 | 6         | 0.09%   |
| Sunplus Technology                     | 5         | 0.08%   |
| Luxvisions Innotech Limited            | 5         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 307       | 4.61%   |
| Realtek Integrated_Webcam_HD              | 295       | 4.43%   |
| Quanta HD User Facing                     | 267       | 4.01%   |
| Chicony HD WebCam                         | 257       | 3.86%   |
| Chicony HD User Facing                    | 214       | 3.22%   |
| Sunplus Integrated_Webcam_HD              | 202       | 3.04%   |
| Silicon Motion Web Camera                 | 201       | 3.02%   |
| Quanta VGA WebCam                         | 194       | 2.92%   |
| Chicony Integrated Camera                 | 153       | 2.3%    |
| Chicony VGA WebCam                        | 140       | 2.1%    |
| Syntek Integrated Camera                  | 120       | 1.8%    |
| Realtek Integrated Webcam                 | 108       | 1.62%   |
| Sunplus HD WebCam                         | 105       | 1.58%   |
| Chicony USB 2.0 Camera                    | 90        | 1.35%   |
| Quanta HD Webcam                          | 87        | 1.31%   |
| Alcor Micro USB 2.0 Camera                | 78        | 1.17%   |
| Microdia Laptop_Integrated_Webcam_HD      | 77        | 1.16%   |
| Bison EasyCamera                          | 57        | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)   | 56        | 0.84%   |
| Realtek USB Camera                        | 56        | 0.84%   |
| Microdia Dell Laptop Integrated Webcam HD | 56        | 0.84%   |
| Silicon Motion WebCam SC-10HDD12636N      | 53        | 0.8%    |
| IMC Networks Integrated Camera            | 53        | 0.8%    |
| Microdia Integrated Webcam HD             | 49        | 0.74%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 48        | 0.72%   |
| Suyin Integrated_Webcam_HD                | 45        | 0.68%   |
| Bison VGA WebCam                          | 45        | 0.68%   |
| Acer BisonCam, NB Pro                     | 43        | 0.65%   |
| Silicon Motion WebCam SCB-1100N           | 41        | 0.62%   |
| Silicon Motion WebCam SC-13HDL11939N      | 41        | 0.62%   |
| Syntek EasyCamera                         | 40        | 0.6%    |
| Silicon Motion WebCam SC-0311139N         | 39        | 0.59%   |
| Realtek HD WebCam                         | 39        | 0.59%   |
| IMC Networks USB2.0 HD UVC WebCam         | 39        | 0.59%   |
| Chicony EasyCamera                        | 38        | 0.57%   |
| Bison Lenovo EasyCamera                   | 37        | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                | 35        | 0.53%   |
| Microdia Integrated Webcam                | 35        | 0.53%   |
| Silicon Motion WebCam SCB-0385N           | 33        | 0.5%    |
| Realtek EasyCamera                        | 33        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 286       | 49.31%  |
| AuthenTec                  | 60        | 10.34%  |
| Synaptics                  | 59        | 10.17%  |
| Upek                       | 57        | 9.83%   |
| Shenzhen Goodix Technology | 51        | 8.79%   |
| LighTuning Technology      | 32        | 5.52%   |
| Samsung Electronics        | 17        | 2.93%   |
| Elan Microelectronics      | 9         | 1.55%   |
| STMicroelectronics         | 4         | 0.69%   |
| Focal-systems.Corp         | 2         | 0.34%   |
| Next Biometrics            | 1         | 0.17%   |
| DigitalPersona             | 1         | 0.17%   |
| Dell                       | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 109       | 18.79%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 48        | 8.28%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 28        | 4.83%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 27        | 4.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 4.66%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 26        | 4.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 4.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 3.97%   |
| Validity Sensors Fingerprint scanner                                       | 22        | 3.79%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 19        | 3.28%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 19        | 3.28%   |
| Shenzhen Goodix  FingerPrint Device                                        | 17        | 2.93%   |
| Samsung Fingerprint Device                                                 | 17        | 2.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 2.41%   |
| AuthenTec AES2810                                                          | 14        | 2.41%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.41%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 13        | 2.24%   |
| Validity Sensors VFS491                                                    | 11        | 1.9%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.9%    |
| AuthenTec Fingerprint Sensor                                               | 11        | 1.9%    |
| Elan ELAN:Fingerprint                                                      | 9         | 1.55%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.38%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.38%   |
| Upek TCS5B Fingerprint sensor                                              | 8         | 1.38%   |
| Synaptics  WBDI                                                            | 7         | 1.21%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.21%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.21%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.03%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.86%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.34%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.34%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.34%   |
| AuthenTec AES1600                                                          | 2         | 0.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.17%   |
| Upek TouchStrip Fingerprint Sensor                                         | 1         | 0.17%   |
| Synaptics WBDI                                                             | 1         | 0.17%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 83        | 53.9%   |
| Alcor Micro               | 24        | 15.58%  |
| Lenovo                    | 13        | 8.44%   |
| Upek                      | 10        | 6.49%   |
| Giesecke & Devrient       | 8         | 5.19%   |
| Watchdata                 | 5         | 3.25%   |
| Aladdin Knowledge Systems | 5         | 3.25%   |
| O2 Micro                  | 3         | 1.95%   |
| SCM Microsystems          | 1         | 0.65%   |
| Gemalto (was Gemplus)     | 1         | 0.65%   |
| Advanced Card Systems     | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 15.58%  |
| Broadcom 58200                                                               | 23        | 14.94%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 13.64%  |
| Broadcom 5880                                                                | 21        | 13.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 11.69%  |
| Lenovo Integrated Smart Card Reader                                          | 13        | 8.44%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 6.49%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.9%    |
| Watchdata USB Key                                                            | 5         | 3.25%   |
| Aladdin Knowledge Systems Token JC                                           | 5         | 3.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.3%    |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 1.3%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.65%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.65%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5591      | 75.87%  |
| 1     | 1548      | 21.01%  |
| 2     | 191       | 2.59%   |
| 3     | 21        | 0.28%   |
| 4     | 9         | 0.12%   |
| 7     | 4         | 0.05%   |
| 5     | 3         | 0.04%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 587       | 29.16%  |
| Fingerprint reader       | 578       | 28.71%  |
| Multimedia controller    | 217       | 10.78%  |
| Net/wireless             | 167       | 8.3%    |
| Chipcard                 | 135       | 6.71%   |
| Bluetooth                | 82        | 4.07%   |
| Camera                   | 62        | 3.08%   |
| Storage                  | 42        | 2.09%   |
| Communication controller | 42        | 2.09%   |
| Sound                    | 32        | 1.59%   |
| Net/ethernet             | 23        | 1.14%   |
| Flash memory             | 21        | 1.04%   |
| Card reader              | 8         | 0.4%    |
| Modem                    | 7         | 0.35%   |
| Firewire controller      | 4         | 0.2%    |
| Network                  | 3         | 0.15%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |

