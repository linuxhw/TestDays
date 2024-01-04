Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 10547

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | N13xWU                      | [b88a27e565](https://linux-hardware.org/?probe=b88a27e565) | Jan 02, 2024 |
| Google        | Caroline                    | [8b3ec77c48](https://linux-hardware.org/?probe=8b3ec77c48) | Jan 02, 2024 |
| HP            | ProBook 430 G2              | [c56ad1ad48](https://linux-hardware.org/?probe=c56ad1ad48) | Jan 02, 2024 |
| Dell          | G3 3590                     | [ae7267dd5f](https://linux-hardware.org/?probe=ae7267dd5f) | Jan 02, 2024 |
| HP            | Pavilion dv3                | [351a45926e](https://linux-hardware.org/?probe=351a45926e) | Jan 02, 2024 |
| Acer          | Nitro AN515-58              | [b822b77797](https://linux-hardware.org/?probe=b822b77797) | Jan 02, 2024 |
| Sony          | VGN-AR51SU                  | [ad09db7b69](https://linux-hardware.org/?probe=ad09db7b69) | Jan 01, 2024 |
| Sony          | VGN-AR51SU                  | [01e1a67d40](https://linux-hardware.org/?probe=01e1a67d40) | Jan 01, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [a679e6f722](https://linux-hardware.org/?probe=a679e6f722) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| Google        | Caroline                    | [95fb0e423e](https://linux-hardware.org/?probe=95fb0e423e) | Jan 01, 2024 |
| Lenovo        | Legion Y7000P2020H 82AX     | [59d5eb147b](https://linux-hardware.org/?probe=59d5eb147b) | Jan 01, 2024 |
| Packard Be... | EasyNote LJ65               | [52bbda495f](https://linux-hardware.org/?probe=52bbda495f) | Jan 01, 2024 |
| Notebook      | N13xWU                      | [d877ecb7be](https://linux-hardware.org/?probe=d877ecb7be) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | [34dd6e3ec3](https://linux-hardware.org/?probe=34dd6e3ec3) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | [4b00ffd071](https://linux-hardware.org/?probe=4b00ffd071) | Jan 01, 2024 |
| Dell          | Inspiron 3593               | [a2424d3523](https://linux-hardware.org/?probe=a2424d3523) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| HP            | ProBook 640 G1              | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| ASUSTek       | UX550VE                     | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| Google        | Caroline                    | [94a1dd78ec](https://linux-hardware.org/?probe=94a1dd78ec) | Dec 31, 2023 |
| HP            | Laptop 17-ca1xxx            | [b569c39f5a](https://linux-hardware.org/?probe=b569c39f5a) | Dec 31, 2023 |
| Google        | Caroline                    | [0d1ce09fbd](https://linux-hardware.org/?probe=0d1ce09fbd) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | [5dde4deb12](https://linux-hardware.org/?probe=5dde4deb12) | Dec 31, 2023 |
| HP            | Pavilion 17                 | [77a7431f73](https://linux-hardware.org/?probe=77a7431f73) | Dec 31, 2023 |
| Google        | Peppy                       | [9b8131eea3](https://linux-hardware.org/?probe=9b8131eea3) | Dec 31, 2023 |
| Unknown       | Unknown                     | [764c59c56e](https://linux-hardware.org/?probe=764c59c56e) | Dec 31, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [9f9b454f97](https://linux-hardware.org/?probe=9f9b454f97) | Dec 31, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [7b1fe348e4](https://linux-hardware.org/?probe=7b1fe348e4) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [934f756965](https://linux-hardware.org/?probe=934f756965) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [76869cc8d4](https://linux-hardware.org/?probe=76869cc8d4) | Dec 31, 2023 |
| HP            | Laptop 14s-ef1xxx           | [961d2db618](https://linux-hardware.org/?probe=961d2db618) | Dec 30, 2023 |
| Apple         | MacBookPro11,5              | [4987fb1cb9](https://linux-hardware.org/?probe=4987fb1cb9) | Dec 30, 2023 |
| HP            | ProBook 440 G6              | [14623af544](https://linux-hardware.org/?probe=14623af544) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | [811e5b34cd](https://linux-hardware.org/?probe=811e5b34cd) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| Dell          | Latitude E5420              | [0bc1fb2eaf](https://linux-hardware.org/?probe=0bc1fb2eaf) | Dec 30, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [221c773946](https://linux-hardware.org/?probe=221c773946) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | [2e99d46be8](https://linux-hardware.org/?probe=2e99d46be8) | Dec 30, 2023 |
| Alurin        | ALU-BAR-I511-000-140        | [04ce6d9f2e](https://linux-hardware.org/?probe=04ce6d9f2e) | Dec 30, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [6410cef098](https://linux-hardware.org/?probe=6410cef098) | Dec 30, 2023 |
| Acer          | Aspire F5-573G              | [4744ad0a98](https://linux-hardware.org/?probe=4744ad0a98) | Dec 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [01c6121d4c](https://linux-hardware.org/?probe=01c6121d4c) | Dec 29, 2023 |
| Dell          | Inspiron 3593               | [dc67ac3e38](https://linux-hardware.org/?probe=dc67ac3e38) | Dec 29, 2023 |
| Apple         | MacBookPro14,3              | [83399f5e60](https://linux-hardware.org/?probe=83399f5e60) | Dec 29, 2023 |
| Acer          | Aspire A715-76G             | [e25984fb5e](https://linux-hardware.org/?probe=e25984fb5e) | Dec 29, 2023 |
| Dell          | XPS 13 9380                 | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [f3af16ad5d](https://linux-hardware.org/?probe=f3af16ad5d) | Dec 29, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4ba914628d](https://linux-hardware.org/?probe=4ba914628d) | Dec 29, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a353b43ac0](https://linux-hardware.org/?probe=a353b43ac0) | Dec 29, 2023 |
| Timi          | A34R                        | [d72018ec19](https://linux-hardware.org/?probe=d72018ec19) | Dec 29, 2023 |
| Dell          | Latitude 5424 Rugged        | [1339f0b553](https://linux-hardware.org/?probe=1339f0b553) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a99e4eda2](https://linux-hardware.org/?probe=6a99e4eda2) | Dec 29, 2023 |
| MSI           | MS-168B                     | [cd9dc4eadd](https://linux-hardware.org/?probe=cd9dc4eadd) | Dec 29, 2023 |
| Dell          | Latitude 7300               | [926a273123](https://linux-hardware.org/?probe=926a273123) | Dec 29, 2023 |
| Acer          | Aspire 4736Z                | [ea8dffb40f](https://linux-hardware.org/?probe=ea8dffb40f) | Dec 29, 2023 |
| Dell          | Latitude 7300               | [ac9c0099fd](https://linux-hardware.org/?probe=ac9c0099fd) | Dec 29, 2023 |
| HP            | ZBook 14 G2                 | [0d092c7ece](https://linux-hardware.org/?probe=0d092c7ece) | Dec 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [13ba865757](https://linux-hardware.org/?probe=13ba865757) | Dec 29, 2023 |
| Lenovo        | Unknown                     | [71b939033d](https://linux-hardware.org/?probe=71b939033d) | Dec 28, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [be86cafd2e](https://linux-hardware.org/?probe=be86cafd2e) | Dec 28, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [c2d6079fe7](https://linux-hardware.org/?probe=c2d6079fe7) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [e456132635](https://linux-hardware.org/?probe=e456132635) | Dec 28, 2023 |
| HUAWEI        | CREFG-XX                    | [91cc2daf14](https://linux-hardware.org/?probe=91cc2daf14) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [4e1a45dee6](https://linux-hardware.org/?probe=4e1a45dee6) | Dec 28, 2023 |
| Lenovo        | G500 20236                  | [62aa46f354](https://linux-hardware.org/?probe=62aa46f354) | Dec 28, 2023 |
| HP            | EliteBook 840 G4            | [412a23e374](https://linux-hardware.org/?probe=412a23e374) | Dec 28, 2023 |
| Lenovo        | ThinkPad T420 4180ED3       | [0c9cecfac4](https://linux-hardware.org/?probe=0c9cecfac4) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [d6477c7999](https://linux-hardware.org/?probe=d6477c7999) | Dec 28, 2023 |
| Acer          | Aspire E5-553G              | [a21fc70e01](https://linux-hardware.org/?probe=a21fc70e01) | Dec 28, 2023 |
| HP            | ZBook 15                    | [92d7e45b22](https://linux-hardware.org/?probe=92d7e45b22) | Dec 28, 2023 |
| HP            | EliteBook 840 G3            | [ce26af0483](https://linux-hardware.org/?probe=ce26af0483) | Dec 28, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [6abb72e809](https://linux-hardware.org/?probe=6abb72e809) | Dec 28, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8250429628](https://linux-hardware.org/?probe=8250429628) | Dec 28, 2023 |
| Dell          | Inspiron 3593               | [27f6eb03d0](https://linux-hardware.org/?probe=27f6eb03d0) | Dec 28, 2023 |
| win elemen... | MoreFine S500+              | [6880205d9e](https://linux-hardware.org/?probe=6880205d9e) | Dec 28, 2023 |
| Acer          | Nitro AN515-51              | [f61d16f126](https://linux-hardware.org/?probe=f61d16f126) | Dec 28, 2023 |
| Valve         | Galileo                     | [ae65838bd7](https://linux-hardware.org/?probe=ae65838bd7) | Dec 28, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [52a99e896e](https://linux-hardware.org/?probe=52a99e896e) | Dec 28, 2023 |
| Acer          | Aspire E5-573G              | [323f661113](https://linux-hardware.org/?probe=323f661113) | Dec 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [6be155ee0d](https://linux-hardware.org/?probe=6be155ee0d) | Dec 27, 2023 |
| MSI           | Pulse GL66 12UEK            | [4600a758fa](https://linux-hardware.org/?probe=4600a758fa) | Dec 27, 2023 |
| Dell          | G3 3500                     | [87c0216250](https://linux-hardware.org/?probe=87c0216250) | Dec 27, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [c16f162169](https://linux-hardware.org/?probe=c16f162169) | Dec 27, 2023 |
| Dell          | Latitude 3520               | [b5802159c7](https://linux-hardware.org/?probe=b5802159c7) | Dec 27, 2023 |
| Dell          | Inspiron 5570               | [84242f4904](https://linux-hardware.org/?probe=84242f4904) | Dec 27, 2023 |
| Acer          | Nitro AN517-41              | [ab7e890030](https://linux-hardware.org/?probe=ab7e890030) | Dec 27, 2023 |
| Unknown       | Unknown                     | [0f40cd177e](https://linux-hardware.org/?probe=0f40cd177e) | Dec 27, 2023 |
| Unknown       | Unknown                     | [5965d25e5a](https://linux-hardware.org/?probe=5965d25e5a) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Dell          | Inspiron 3583               | [de1dd08f64](https://linux-hardware.org/?probe=de1dd08f64) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [8af95757fe](https://linux-hardware.org/?probe=8af95757fe) | Dec 27, 2023 |
| Lenovo        | ThinkPad E480 20KN0065MX    | [14018f1aec](https://linux-hardware.org/?probe=14018f1aec) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S24N3J    | [b6b0c2c889](https://linux-hardware.org/?probe=b6b0c2c889) | Dec 27, 2023 |
| HUAWEI        | NbDE-WXX9                   | [5f124e4838](https://linux-hardware.org/?probe=5f124e4838) | Dec 27, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [a8871fb21b](https://linux-hardware.org/?probe=a8871fb21b) | Dec 27, 2023 |
| MSI           | GS40 6QE Phantom            | [2946f9add8](https://linux-hardware.org/?probe=2946f9add8) | Dec 26, 2023 |
| Medion        | P6613                       | [1f30069d6d](https://linux-hardware.org/?probe=1f30069d6d) | Dec 26, 2023 |
| TUXEDO        | N24_25JU                    | [3c7a5feb48](https://linux-hardware.org/?probe=3c7a5feb48) | Dec 26, 2023 |
| Apple         | MacBookAir6,2               | [67979f3133](https://linux-hardware.org/?probe=67979f3133) | Dec 26, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [e514863c67](https://linux-hardware.org/?probe=e514863c67) | Dec 26, 2023 |
| Dell          | XPS 13 9370                 | [17304074a6](https://linux-hardware.org/?probe=17304074a6) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8fae3225fd](https://linux-hardware.org/?probe=8fae3225fd) | Dec 26, 2023 |
| Dell          | Latitude 5440               | [44e45480d1](https://linux-hardware.org/?probe=44e45480d1) | Dec 26, 2023 |
| Medion        | E6228                       | [827fcc5d4b](https://linux-hardware.org/?probe=827fcc5d4b) | Dec 26, 2023 |
| Unknown       | Unknown                     | [d382bd5980](https://linux-hardware.org/?probe=d382bd5980) | Dec 26, 2023 |
| Acer          | Nitro AN515-54              | [67492721ec](https://linux-hardware.org/?probe=67492721ec) | Dec 26, 2023 |
| Unknown       | Unknown                     | [c701a5ce22](https://linux-hardware.org/?probe=c701a5ce22) | Dec 26, 2023 |
| Unknown       | Unknown                     | [ef974b90c4](https://linux-hardware.org/?probe=ef974b90c4) | Dec 25, 2023 |
| Dell          | Latitude 7490               | [3c17f0bdce](https://linux-hardware.org/?probe=3c17f0bdce) | Dec 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [59e540836e](https://linux-hardware.org/?probe=59e540836e) | Dec 25, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [fb78f052e1](https://linux-hardware.org/?probe=fb78f052e1) | Dec 25, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [771d35e2bc](https://linux-hardware.org/?probe=771d35e2bc) | Dec 25, 2023 |
| Google        | Aleena                      | [a5a888a877](https://linux-hardware.org/?probe=a5a888a877) | Dec 25, 2023 |
| Lenovo        | G50-45 80E3                 | [884a852341](https://linux-hardware.org/?probe=884a852341) | Dec 25, 2023 |
| MSI           | PS63 Modern 8M              | [3097ac02eb](https://linux-hardware.org/?probe=3097ac02eb) | Dec 25, 2023 |
| HP            | Laptop 17-bs1xx             | [736cd905c8](https://linux-hardware.org/?probe=736cd905c8) | Dec 25, 2023 |
| TUXEDO        | N24_25JU                    | [26beeaeefa](https://linux-hardware.org/?probe=26beeaeefa) | Dec 25, 2023 |
| HUAWEI        | BoDE-WXX9                   | [a8acfd11f6](https://linux-hardware.org/?probe=a8acfd11f6) | Dec 25, 2023 |
| MSI           | EX610                       | [95fe9d0294](https://linux-hardware.org/?probe=95fe9d0294) | Dec 25, 2023 |
| HP            | EliteBook Folio 9470m       | [e1f5de21d1](https://linux-hardware.org/?probe=e1f5de21d1) | Dec 25, 2023 |
| Acer          | Aspire 5749                 | [e70e0eae25](https://linux-hardware.org/?probe=e70e0eae25) | Dec 24, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [e6d150acea](https://linux-hardware.org/?probe=e6d150acea) | Dec 24, 2023 |
| Lenovo        | ThinkPad W530 2436CT0       | [7f8be52856](https://linux-hardware.org/?probe=7f8be52856) | Dec 24, 2023 |
| Acer          | Aspire A315-35              | [a3c4869087](https://linux-hardware.org/?probe=a3c4869087) | Dec 24, 2023 |
| Panasonic     | FZG1-4                      | [f6c98a5b67](https://linux-hardware.org/?probe=f6c98a5b67) | Dec 24, 2023 |
| Apple         | MacBookAir7,1               | [f666ec3927](https://linux-hardware.org/?probe=f666ec3927) | Dec 24, 2023 |
| Dell          | Latitude 7490               | [69205c648f](https://linux-hardware.org/?probe=69205c648f) | Dec 24, 2023 |
| Acer          | Nitro AN515-44              | [cc87c11e7b](https://linux-hardware.org/?probe=cc87c11e7b) | Dec 24, 2023 |
| Notebook      | NL5xNU                      | [1cb09f63f9](https://linux-hardware.org/?probe=1cb09f63f9) | Dec 24, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [f8abeb2607](https://linux-hardware.org/?probe=f8abeb2607) | Dec 24, 2023 |
| Google        | Magolor                     | [f5d079bc79](https://linux-hardware.org/?probe=f5d079bc79) | Dec 24, 2023 |
| Dell          | Latitude 12 Rugged Table... | [7690d56522](https://linux-hardware.org/?probe=7690d56522) | Dec 24, 2023 |
| Unknown       | Unknown                     | [ef80f96d40](https://linux-hardware.org/?probe=ef80f96d40) | Dec 23, 2023 |
| Sony          | VPCEA1S1E                   | [af850dd5f3](https://linux-hardware.org/?probe=af850dd5f3) | Dec 23, 2023 |
| TUXEDO        | N24_25JU                    | [8a1a153723](https://linux-hardware.org/?probe=8a1a153723) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | [d153c701cc](https://linux-hardware.org/?probe=d153c701cc) | Dec 23, 2023 |
| Lenovo        | ThinkPad T410 2537E82       | [398233e395](https://linux-hardware.org/?probe=398233e395) | Dec 23, 2023 |
| Acer          | TravelMate 5730             | [69571c0b91](https://linux-hardware.org/?probe=69571c0b91) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d3dabca767](https://linux-hardware.org/?probe=d3dabca767) | Dec 23, 2023 |
| Dell          | Latitude E6330              | [afca8c73b2](https://linux-hardware.org/?probe=afca8c73b2) | Dec 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [26673c372e](https://linux-hardware.org/?probe=26673c372e) | Dec 23, 2023 |
| Dell          | Inspiron 3501               | [2fcf77279a](https://linux-hardware.org/?probe=2fcf77279a) | Dec 23, 2023 |
| Toshiba       | Satellite L750              | [8f2f7cd8c9](https://linux-hardware.org/?probe=8f2f7cd8c9) | Dec 23, 2023 |
| HP            | Laptop 17-bs1xx             | [984a979a7b](https://linux-hardware.org/?probe=984a979a7b) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [19e33f2ead](https://linux-hardware.org/?probe=19e33f2ead) | Dec 23, 2023 |
| Dell          | Latitude E6400              | [1a10fd9a2e](https://linux-hardware.org/?probe=1a10fd9a2e) | Dec 23, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [6ba8bb7550](https://linux-hardware.org/?probe=6ba8bb7550) | Dec 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [0f2cad4391](https://linux-hardware.org/?probe=0f2cad4391) | Dec 22, 2023 |
| Acer          | Aspire VX5-591G             | [2268342e9f](https://linux-hardware.org/?probe=2268342e9f) | Dec 22, 2023 |
| Apple         | MacBookPro13,1              | [89ef1fa23c](https://linux-hardware.org/?probe=89ef1fa23c) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | [c81a75e686](https://linux-hardware.org/?probe=c81a75e686) | Dec 22, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [937842fe5d](https://linux-hardware.org/?probe=937842fe5d) | Dec 22, 2023 |
| HP            | EliteBook 8460p             | [6ff6445717](https://linux-hardware.org/?probe=6ff6445717) | Dec 22, 2023 |
| ASUSTek       | X555LD                      | [30e988edc9](https://linux-hardware.org/?probe=30e988edc9) | Dec 22, 2023 |
| Allview       | Allbook I/1                 | [960dfde4cd](https://linux-hardware.org/?probe=960dfde4cd) | Dec 22, 2023 |
| Dell          | Latitude 5414               | [9b02eedb05](https://linux-hardware.org/?probe=9b02eedb05) | Dec 22, 2023 |
| Dell          | Vostro 15 3510              | [d2c7d30632](https://linux-hardware.org/?probe=d2c7d30632) | Dec 22, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [60690b9d12](https://linux-hardware.org/?probe=60690b9d12) | Dec 22, 2023 |
| Toshiba       | Satellite C55D-B            | [d705d8ee57](https://linux-hardware.org/?probe=d705d8ee57) | Dec 22, 2023 |
| Acer          | Nitro AN515-44              | [5f1c04a086](https://linux-hardware.org/?probe=5f1c04a086) | Dec 22, 2023 |
| Entroware     | Hybris                      | [870d0c5323](https://linux-hardware.org/?probe=870d0c5323) | Dec 22, 2023 |
| Dell          | Latitude 5501               | [0b6206153c](https://linux-hardware.org/?probe=0b6206153c) | Dec 22, 2023 |
| Acer          | Aspire 5742G                | [1f9d486306](https://linux-hardware.org/?probe=1f9d486306) | Dec 22, 2023 |
| Dell          | Latitude E6440              | [904540fc01](https://linux-hardware.org/?probe=904540fc01) | Dec 21, 2023 |
| Dell          | Inspiron 3541               | [67f350fefc](https://linux-hardware.org/?probe=67f350fefc) | Dec 21, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [907851c66b](https://linux-hardware.org/?probe=907851c66b) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [c5c9d669ae](https://linux-hardware.org/?probe=c5c9d669ae) | Dec 21, 2023 |
| Dell          | Precision 3581              | [aa0186ade6](https://linux-hardware.org/?probe=aa0186ade6) | Dec 21, 2023 |
| HP            | ProBook 445 14 inch G10 ... | [0e95b32d0b](https://linux-hardware.org/?probe=0e95b32d0b) | Dec 21, 2023 |
| Dell          | Inspiron 15 3535            | [466204d787](https://linux-hardware.org/?probe=466204d787) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK U749               | [75a3ef28b0](https://linux-hardware.org/?probe=75a3ef28b0) | Dec 21, 2023 |
| HUAWEI        | BOD-WXX9                    | [f95bb7d27c](https://linux-hardware.org/?probe=f95bb7d27c) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [27e7d6f705](https://linux-hardware.org/?probe=27e7d6f705) | Dec 21, 2023 |
| Dell          | Latitude 7490               | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| realme        | RMNBXXXX                    | [d8e473e1e4](https://linux-hardware.org/?probe=d8e473e1e4) | Dec 21, 2023 |
| HP            | Pavilion dv7                | [ef719917ef](https://linux-hardware.org/?probe=ef719917ef) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | [ebaf3f3e71](https://linux-hardware.org/?probe=ebaf3f3e71) | Dec 21, 2023 |
| HP            | Notebook                    | [9010ced489](https://linux-hardware.org/?probe=9010ced489) | Dec 21, 2023 |
| Dell          | Inspiron 5448               | [edf818740d](https://linux-hardware.org/?probe=edf818740d) | Dec 21, 2023 |
| HP            | Pavilion dv7                | [cd7f768fe8](https://linux-hardware.org/?probe=cd7f768fe8) | Dec 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [e36c36774e](https://linux-hardware.org/?probe=e36c36774e) | Dec 21, 2023 |
| Dell          | Latitude E6520              | [9e16e8b2a6](https://linux-hardware.org/?probe=9e16e8b2a6) | Dec 21, 2023 |
| Dell          | Inspiron 7572               | [cd9385a64b](https://linux-hardware.org/?probe=cd9385a64b) | Dec 21, 2023 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [4bd3fc58a8](https://linux-hardware.org/?probe=4bd3fc58a8) | Dec 21, 2023 |
| Panasonic     | CF-19RDRCHH7                | [0e67081368](https://linux-hardware.org/?probe=0e67081368) | Dec 21, 2023 |
| Dell          | Latitude 5590               | [4f307c792f](https://linux-hardware.org/?probe=4f307c792f) | Dec 20, 2023 |
| Apple         | MacBookPro9,2               | [da159da872](https://linux-hardware.org/?probe=da159da872) | Dec 20, 2023 |
| Dell          | Latitude 7480               | [f080cc67aa](https://linux-hardware.org/?probe=f080cc67aa) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [393c13e870](https://linux-hardware.org/?probe=393c13e870) | Dec 20, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [09af8afa56](https://linux-hardware.org/?probe=09af8afa56) | Dec 20, 2023 |
| Toshiba       | Satellite C55D-B            | [dfd0e27118](https://linux-hardware.org/?probe=dfd0e27118) | Dec 20, 2023 |
| Lenovo        | ThinkPad T410 2537HN2       | [c268085f95](https://linux-hardware.org/?probe=c268085f95) | Dec 20, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [06984b497c](https://linux-hardware.org/?probe=06984b497c) | Dec 20, 2023 |
| Dell          | Precision 5510              | [033bf69fdf](https://linux-hardware.org/?probe=033bf69fdf) | Dec 20, 2023 |
| Dell          | Precision 5510              | [a40fa883d2](https://linux-hardware.org/?probe=a40fa883d2) | Dec 20, 2023 |
| STONE COMP... | NOTCHA-286                  | [c931f0f65a](https://linux-hardware.org/?probe=c931f0f65a) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [71bc732b86](https://linux-hardware.org/?probe=71bc732b86) | Dec 20, 2023 |
| Dell          | G7 7700                     | [506de63cb5](https://linux-hardware.org/?probe=506de63cb5) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [5d14b45611](https://linux-hardware.org/?probe=5d14b45611) | Dec 20, 2023 |
| Lenovo        | ThinkPad T520 42404AU       | [2b29070879](https://linux-hardware.org/?probe=2b29070879) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [71d03541a9](https://linux-hardware.org/?probe=71d03541a9) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6f7295809b](https://linux-hardware.org/?probe=6f7295809b) | Dec 20, 2023 |
| Daten Tecn... | DT02-M4                     | [8f754589f6](https://linux-hardware.org/?probe=8f754589f6) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [dbbab5f96b](https://linux-hardware.org/?probe=dbbab5f96b) | Dec 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [775e2dfe26](https://linux-hardware.org/?probe=775e2dfe26) | Dec 19, 2023 |
| Google        | Swanky                      | [46b7f27873](https://linux-hardware.org/?probe=46b7f27873) | Dec 19, 2023 |
| Mediacom      | GTZS                        | [f326507469](https://linux-hardware.org/?probe=f326507469) | Dec 19, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [3cc3621576](https://linux-hardware.org/?probe=3cc3621576) | Dec 19, 2023 |
| HUAWEI        | CREFG-XX                    | [b97589a2bc](https://linux-hardware.org/?probe=b97589a2bc) | Dec 19, 2023 |
| HUAWEI        | CREFG-XX                    | [5dd323e917](https://linux-hardware.org/?probe=5dd323e917) | Dec 19, 2023 |
| HP            | EliteBook 840 14 inch G1... | [2222f1a1fb](https://linux-hardware.org/?probe=2222f1a1fb) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1b5268d64f](https://linux-hardware.org/?probe=1b5268d64f) | Dec 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1290fe8e5a](https://linux-hardware.org/?probe=1290fe8e5a) | Dec 19, 2023 |
| Dell          | Latitude E6510              | [e9aceddae8](https://linux-hardware.org/?probe=e9aceddae8) | Dec 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a4efec2a2c](https://linux-hardware.org/?probe=a4efec2a2c) | Dec 19, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | [f09218ee8f](https://linux-hardware.org/?probe=f09218ee8f) | Dec 19, 2023 |
| Unknown       | Unknown                     | [6f1ca9e563](https://linux-hardware.org/?probe=6f1ca9e563) | Dec 19, 2023 |
| Dell          | Precision M2800             | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| Unknown       | Unknown                     | [13072c9ecc](https://linux-hardware.org/?probe=13072c9ecc) | Dec 19, 2023 |
| Acer          | Aspire E5-573               | [91c6527140](https://linux-hardware.org/?probe=91c6527140) | Dec 19, 2023 |
| Dell          | XPS 13 9380                 | [1038e25caf](https://linux-hardware.org/?probe=1038e25caf) | Dec 19, 2023 |
| Dell          | XPS 13 9310                 | [3a4a73b5f1](https://linux-hardware.org/?probe=3a4a73b5f1) | Dec 19, 2023 |
| Acer          | Aspire E5-571               | [55a802f43c](https://linux-hardware.org/?probe=55a802f43c) | Dec 18, 2023 |
| Dell          | Latitude 3420               | [5fdda723cd](https://linux-hardware.org/?probe=5fdda723cd) | Dec 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [923f390d62](https://linux-hardware.org/?probe=923f390d62) | Dec 18, 2023 |
| Acer          | Aspire A715-51G             | [1232ff1050](https://linux-hardware.org/?probe=1232ff1050) | Dec 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8a224cfad3](https://linux-hardware.org/?probe=8a224cfad3) | Dec 18, 2023 |
| HP            | Pavilion Notebook           | [0376612ef7](https://linux-hardware.org/?probe=0376612ef7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [45a0b94112](https://linux-hardware.org/?probe=45a0b94112) | Dec 18, 2023 |
| Dell          | Latitude 7440               | [644c46aba6](https://linux-hardware.org/?probe=644c46aba6) | Dec 18, 2023 |
| realme        | RMNBXXXX                    | [100bef421f](https://linux-hardware.org/?probe=100bef421f) | Dec 18, 2023 |
| Dell          | XPS 15 9500                 | [941f6d849a](https://linux-hardware.org/?probe=941f6d849a) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [fcc1139818](https://linux-hardware.org/?probe=fcc1139818) | Dec 18, 2023 |
| Acer          | Aspire 5349                 | [f81cd33147](https://linux-hardware.org/?probe=f81cd33147) | Dec 18, 2023 |
| Wortmann      | TERRA_MOBILE_1542           | [054ed4fad9](https://linux-hardware.org/?probe=054ed4fad9) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | [0c3974dad9](https://linux-hardware.org/?probe=0c3974dad9) | Dec 18, 2023 |
| HP            | 255 G6 Notebook PC          | [f4412027d4](https://linux-hardware.org/?probe=f4412027d4) | Dec 18, 2023 |
| ASUSTek       | X550LD                      | [d1dcdfda30](https://linux-hardware.org/?probe=d1dcdfda30) | Dec 17, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [4802066fc1](https://linux-hardware.org/?probe=4802066fc1) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | [ab734913e8](https://linux-hardware.org/?probe=ab734913e8) | Dec 17, 2023 |
| Acer          | Aspire S7-391               | [1d66b3f887](https://linux-hardware.org/?probe=1d66b3f887) | Dec 17, 2023 |
| Acer          | Swift SF315-41              | [300b426183](https://linux-hardware.org/?probe=300b426183) | Dec 17, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | [17b157ef44](https://linux-hardware.org/?probe=17b157ef44) | Dec 17, 2023 |
| Sony          | SVD1321L2EW                 | [b753425d70](https://linux-hardware.org/?probe=b753425d70) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [78a88bfe8c](https://linux-hardware.org/?probe=78a88bfe8c) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [8833b0a058](https://linux-hardware.org/?probe=8833b0a058) | Dec 17, 2023 |
| HP            | Laptop 17-cp0xxx            | [341ecee745](https://linux-hardware.org/?probe=341ecee745) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [987ab63f96](https://linux-hardware.org/?probe=987ab63f96) | Dec 17, 2023 |
| Acer          | Aspire V3-772               | [d3e1291358](https://linux-hardware.org/?probe=d3e1291358) | Dec 17, 2023 |
| Lenovo        | ThinkPad A475 20KMS08300    | [b652245cca](https://linux-hardware.org/?probe=b652245cca) | Dec 17, 2023 |
| HP            | Laptop 15-bw0xx             | [91a9e2e8c4](https://linux-hardware.org/?probe=91a9e2e8c4) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | [efc671c7c2](https://linux-hardware.org/?probe=efc671c7c2) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | [c99e0d38ea](https://linux-hardware.org/?probe=c99e0d38ea) | Dec 17, 2023 |
| HP            | 2000                        | [3570eb7cd0](https://linux-hardware.org/?probe=3570eb7cd0) | Dec 17, 2023 |
| HP            | EliteBook 8460p             | [e85c54f3fd](https://linux-hardware.org/?probe=e85c54f3fd) | Dec 17, 2023 |
| Dell          | Inspiron N4030              | [a77869199a](https://linux-hardware.org/?probe=a77869199a) | Dec 17, 2023 |
| Lenovo        | ThinkPad W530 24491D1       | [bab70d44b1](https://linux-hardware.org/?probe=bab70d44b1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [1c0bbe412c](https://linux-hardware.org/?probe=1c0bbe412c) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | [492e654dfb](https://linux-hardware.org/?probe=492e654dfb) | Dec 17, 2023 |
| LG Electro... | 16Z90R-A.ADC8U1             | [5ae89dd818](https://linux-hardware.org/?probe=5ae89dd818) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| HP            | 250 G8 Notebook PC          | [6e6dfdc457](https://linux-hardware.org/?probe=6e6dfdc457) | Dec 16, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [2167a2f148](https://linux-hardware.org/?probe=2167a2f148) | Dec 16, 2023 |
| Acer          | Aspire 6930G                | [3e93a62792](https://linux-hardware.org/?probe=3e93a62792) | Dec 16, 2023 |
| Lenovo        | ThinkPad T420 4238AW2       | [01fae631cf](https://linux-hardware.org/?probe=01fae631cf) | Dec 16, 2023 |
| Allview       | Allbook H                   | [2da4fcb35c](https://linux-hardware.org/?probe=2da4fcb35c) | Dec 16, 2023 |
| HUAWEI        | BoDE-WXX9                   | [e9f2e211bd](https://linux-hardware.org/?probe=e9f2e211bd) | Dec 16, 2023 |
| ASUSTek       | X555LD                      | [109311067f](https://linux-hardware.org/?probe=109311067f) | Dec 16, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | [2598a81fd9](https://linux-hardware.org/?probe=2598a81fd9) | Dec 16, 2023 |
| Lenovo        | IdeaPad S400 20195          | [f4c6ceeca3](https://linux-hardware.org/?probe=f4c6ceeca3) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7b3d7fcb72](https://linux-hardware.org/?probe=7b3d7fcb72) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [251ac554a9](https://linux-hardware.org/?probe=251ac554a9) | Dec 16, 2023 |
| Dell          | Precision 5540              | [ff22e47089](https://linux-hardware.org/?probe=ff22e47089) | Dec 16, 2023 |
| HP            | Notebook                    | [5bbbe8e356](https://linux-hardware.org/?probe=5bbbe8e356) | Dec 16, 2023 |
| ROMBICA       | myBook Discovery            | [c7b69fb478](https://linux-hardware.org/?probe=c7b69fb478) | Dec 16, 2023 |
| Dell          | Inspiron 1545               | [3f47a63c82](https://linux-hardware.org/?probe=3f47a63c82) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [933e5b48f2](https://linux-hardware.org/?probe=933e5b48f2) | Dec 16, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [9df7fd000e](https://linux-hardware.org/?probe=9df7fd000e) | Dec 16, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [12c5d1d331](https://linux-hardware.org/?probe=12c5d1d331) | Dec 16, 2023 |
| Medion        | E6417 MD99252               | [26e9c2ba0c](https://linux-hardware.org/?probe=26e9c2ba0c) | Dec 15, 2023 |
| MSI           | Katana GF66 11SC            | [1eb5b02078](https://linux-hardware.org/?probe=1eb5b02078) | Dec 15, 2023 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [2d3b97c04a](https://linux-hardware.org/?probe=2d3b97c04a) | Dec 15, 2023 |
| ASUSTek       | X555LAB                     | [199ffa8815](https://linux-hardware.org/?probe=199ffa8815) | Dec 15, 2023 |
| Dell          | Latitude 7490               | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5223e586fd](https://linux-hardware.org/?probe=5223e586fd) | Dec 15, 2023 |
| Lenovo        | B590 62742QG                | [edb1cd89f6](https://linux-hardware.org/?probe=edb1cd89f6) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| HP            | Pavilion g6                 | [7863fae702](https://linux-hardware.org/?probe=7863fae702) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [618978da16](https://linux-hardware.org/?probe=618978da16) | Dec 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| HP            | Laptop 17-bs1xx             | [ef29718fd5](https://linux-hardware.org/?probe=ef29718fd5) | Dec 15, 2023 |
| Dell          | Vostro 15 3510              | [051090b9e0](https://linux-hardware.org/?probe=051090b9e0) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d8db62d461](https://linux-hardware.org/?probe=d8db62d461) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [a0eaa74105](https://linux-hardware.org/?probe=a0eaa74105) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [db4a7dea97](https://linux-hardware.org/?probe=db4a7dea97) | Dec 15, 2023 |
| HP            | Pavilion 15                 | [166f55ae0b](https://linux-hardware.org/?probe=166f55ae0b) | Dec 15, 2023 |
| Acer          | Nitro AN515-57              | [7e43febcae](https://linux-hardware.org/?probe=7e43febcae) | Dec 15, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [e4542af709](https://linux-hardware.org/?probe=e4542af709) | Dec 15, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [46fbc450b5](https://linux-hardware.org/?probe=46fbc450b5) | Dec 14, 2023 |
| Dell          | Latitude E5450              | [b616faa68f](https://linux-hardware.org/?probe=b616faa68f) | Dec 14, 2023 |
| ASUSTek       | X555LD                      | [9609ed5138](https://linux-hardware.org/?probe=9609ed5138) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | [b537ee14db](https://linux-hardware.org/?probe=b537ee14db) | Dec 14, 2023 |
| Fujitsu       | LIFEBOOK E736               | [7f788f5265](https://linux-hardware.org/?probe=7f788f5265) | Dec 14, 2023 |
| Dell          | XPS 15 9520                 | [ac8fb0b18d](https://linux-hardware.org/?probe=ac8fb0b18d) | Dec 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [adbfbb8174](https://linux-hardware.org/?probe=adbfbb8174) | Dec 13, 2023 |
| Acer          | Nitro AN515-51              | [1522c84fb7](https://linux-hardware.org/?probe=1522c84fb7) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | [9c3e8b880d](https://linux-hardware.org/?probe=9c3e8b880d) | Dec 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e70de29c90](https://linux-hardware.org/?probe=e70de29c90) | Dec 13, 2023 |
| Lenovo        | V110-15IAP 80TG             | [de6e3bf0eb](https://linux-hardware.org/?probe=de6e3bf0eb) | Dec 13, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | [bf54dfd215](https://linux-hardware.org/?probe=bf54dfd215) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | [9d192a95d8](https://linux-hardware.org/?probe=9d192a95d8) | Dec 13, 2023 |
| Fujitsu       | LIFEBOOK S762               | [19e6b5a871](https://linux-hardware.org/?probe=19e6b5a871) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [4a5e5bbe29](https://linux-hardware.org/?probe=4a5e5bbe29) | Dec 13, 2023 |
| Acer          | Swift SF314-43              | [6e8b956266](https://linux-hardware.org/?probe=6e8b956266) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | [cdcd6ddfc6](https://linux-hardware.org/?probe=cdcd6ddfc6) | Dec 13, 2023 |
| Apple         | MacBookAir6,2               | [963ff854d9](https://linux-hardware.org/?probe=963ff854d9) | Dec 13, 2023 |
| Dell          | Vostro 3400                 | [01915c7894](https://linux-hardware.org/?probe=01915c7894) | Dec 13, 2023 |
| Dell          | Vostro 3400                 | [a8d24008e2](https://linux-hardware.org/?probe=a8d24008e2) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [05ff735f51](https://linux-hardware.org/?probe=05ff735f51) | Dec 13, 2023 |
| Unknown       | Unknown                     | [4517e8a60b](https://linux-hardware.org/?probe=4517e8a60b) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [9c38707d13](https://linux-hardware.org/?probe=9c38707d13) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [f837c928be](https://linux-hardware.org/?probe=f837c928be) | Dec 13, 2023 |
| Dell          | G3 3590                     | [e764bfc760](https://linux-hardware.org/?probe=e764bfc760) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | [e6f39159ad](https://linux-hardware.org/?probe=e6f39159ad) | Dec 13, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [2b589c71b3](https://linux-hardware.org/?probe=2b589c71b3) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK T902               | [da78a4dd31](https://linux-hardware.org/?probe=da78a4dd31) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7be431fb](https://linux-hardware.org/?probe=af7be431fb) | Dec 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a128efcd01](https://linux-hardware.org/?probe=a128efcd01) | Dec 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4293932b86](https://linux-hardware.org/?probe=4293932b86) | Dec 12, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | [695a85cd79](https://linux-hardware.org/?probe=695a85cd79) | Dec 12, 2023 |
| Fujitsu       | LIFEBOOK T902               | [dff662b36c](https://linux-hardware.org/?probe=dff662b36c) | Dec 12, 2023 |
| Lenovo        | ThinkPad E490 20N9S13000    | [d93593921b](https://linux-hardware.org/?probe=d93593921b) | Dec 12, 2023 |
| HP            | Laptop 15-fc0xxx            | [0ad101e0f2](https://linux-hardware.org/?probe=0ad101e0f2) | Dec 12, 2023 |
| Acer          | Aspire E1-522               | [e438bd7bc2](https://linux-hardware.org/?probe=e438bd7bc2) | Dec 12, 2023 |
| Acer          | Aspire E1-571               | [4576cb723a](https://linux-hardware.org/?probe=4576cb723a) | Dec 12, 2023 |
| Acer          | Aspire E1-522               | [0ba0422412](https://linux-hardware.org/?probe=0ba0422412) | Dec 12, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [41ff1cd0ca](https://linux-hardware.org/?probe=41ff1cd0ca) | Dec 12, 2023 |
| ASUSTek       | X550LD                      | [1e1b5e9985](https://linux-hardware.org/?probe=1e1b5e9985) | Dec 12, 2023 |
| Sony          | VPCEH25EN                   | [284401858f](https://linux-hardware.org/?probe=284401858f) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [84fd94c616](https://linux-hardware.org/?probe=84fd94c616) | Dec 12, 2023 |
| Sony          | VPCCW1S1E                   | [361d9573dd](https://linux-hardware.org/?probe=361d9573dd) | Dec 12, 2023 |
| HP            | Pavilion 15                 | [235d10da72](https://linux-hardware.org/?probe=235d10da72) | Dec 12, 2023 |
| HP            | Pavilion 15                 | [fd466b16c8](https://linux-hardware.org/?probe=fd466b16c8) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d27df22c9a](https://linux-hardware.org/?probe=d27df22c9a) | Dec 11, 2023 |
| MSI           | GX60 1AC/GX60 3AE/GX60 3... | [262637b1e2](https://linux-hardware.org/?probe=262637b1e2) | Dec 11, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [ccd16e5c8d](https://linux-hardware.org/?probe=ccd16e5c8d) | Dec 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S1FW00    | [9ea0dccce0](https://linux-hardware.org/?probe=9ea0dccce0) | Dec 11, 2023 |
| Dell          | Inspiron 3442               | [deced1a058](https://linux-hardware.org/?probe=deced1a058) | Dec 11, 2023 |
| Dell          | Inspiron 3521               | [e96af5da4d](https://linux-hardware.org/?probe=e96af5da4d) | Dec 11, 2023 |
| ASUSTek       | X202E                       | [3d45a17e7f](https://linux-hardware.org/?probe=3d45a17e7f) | Dec 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [f8b53d98cc](https://linux-hardware.org/?probe=f8b53d98cc) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [c2dd869dcf](https://linux-hardware.org/?probe=c2dd869dcf) | Dec 10, 2023 |
| Acer          | Aspire 7520                 | [70405c9fa1](https://linux-hardware.org/?probe=70405c9fa1) | Dec 10, 2023 |
| Unknown       | Unknown                     | [e70fd6bdb5](https://linux-hardware.org/?probe=e70fd6bdb5) | Dec 10, 2023 |
| Samsung       | RF511/RF411/RF711           | [59846b1d85](https://linux-hardware.org/?probe=59846b1d85) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [96b05f5be6](https://linux-hardware.org/?probe=96b05f5be6) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | [48fffc72b6](https://linux-hardware.org/?probe=48fffc72b6) | Dec 10, 2023 |
| Sony          | VGN-AR51M                   | [d1c67ac651](https://linux-hardware.org/?probe=d1c67ac651) | Dec 10, 2023 |
| Acer          | Aspire 6930G                | [eea9d9e525](https://linux-hardware.org/?probe=eea9d9e525) | Dec 10, 2023 |
| HP            | EliteBook 8460p             | [1e96233f59](https://linux-hardware.org/?probe=1e96233f59) | Dec 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9c86c02e7](https://linux-hardware.org/?probe=b9c86c02e7) | Dec 10, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [37214745c0](https://linux-hardware.org/?probe=37214745c0) | Dec 10, 2023 |
| Valve         | Jupiter                     | [4c72e88035](https://linux-hardware.org/?probe=4c72e88035) | Dec 10, 2023 |
| Valve         | Jupiter                     | [9f822d68bb](https://linux-hardware.org/?probe=9f822d68bb) | Dec 10, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [c753b49018](https://linux-hardware.org/?probe=c753b49018) | Dec 10, 2023 |
| HP            | 240 G8 Notebook PC          | [e5f4045026](https://linux-hardware.org/?probe=e5f4045026) | Dec 10, 2023 |
| Irbis         | NB290                       | [dcea177b24](https://linux-hardware.org/?probe=dcea177b24) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [63b05d421b](https://linux-hardware.org/?probe=63b05d421b) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecb7258d5](https://linux-hardware.org/?probe=1ecb7258d5) | Dec 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2bc305a065](https://linux-hardware.org/?probe=2bc305a065) | Dec 09, 2023 |
| HP            | EliteBook 8560w             | [0de5475eb8](https://linux-hardware.org/?probe=0de5475eb8) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f0bcb0009e](https://linux-hardware.org/?probe=f0bcb0009e) | Dec 09, 2023 |
| HP            | ProBook 640 G2              | [0989548d19](https://linux-hardware.org/?probe=0989548d19) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| HUAWEI        | HN-WX9X                     | [d9d22e25cb](https://linux-hardware.org/?probe=d9d22e25cb) | Dec 09, 2023 |
| Medion        | P8614                       | [a7689ec115](https://linux-hardware.org/?probe=a7689ec115) | Dec 09, 2023 |
| HP            | EliteBook 840 G3            | [ae0afe3e73](https://linux-hardware.org/?probe=ae0afe3e73) | Dec 09, 2023 |
| ASUSTek       | K55DR                       | [a869089d9a](https://linux-hardware.org/?probe=a869089d9a) | Dec 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e800d95054](https://linux-hardware.org/?probe=e800d95054) | Dec 09, 2023 |
| Toshiba       | QOSMIO X770                 | [945c57d421](https://linux-hardware.org/?probe=945c57d421) | Dec 09, 2023 |
| Unknown       | Unknown                     | [130b4fa28a](https://linux-hardware.org/?probe=130b4fa28a) | Dec 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [acb9e267c5](https://linux-hardware.org/?probe=acb9e267c5) | Dec 09, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [490ad0881a](https://linux-hardware.org/?probe=490ad0881a) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | [48dc91498c](https://linux-hardware.org/?probe=48dc91498c) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| Dell          | Latitude 7400               | [71ba2c1398](https://linux-hardware.org/?probe=71ba2c1398) | Dec 08, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H3C... | [2c3c1f7ad2](https://linux-hardware.org/?probe=2c3c1f7ad2) | Dec 08, 2023 |
| HP            | Laptop 15-bw0xx             | [b00663cde8](https://linux-hardware.org/?probe=b00663cde8) | Dec 08, 2023 |
| HP            | Pavilion dv6                | [3ffa0f12b7](https://linux-hardware.org/?probe=3ffa0f12b7) | Dec 08, 2023 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a7dccd5888](https://linux-hardware.org/?probe=a7dccd5888) | Dec 08, 2023 |
| Acer          | Aspire E1-531               | [7082f03269](https://linux-hardware.org/?probe=7082f03269) | Dec 08, 2023 |
| Sony          | SVE1713Q1EB                 | [482c83143b](https://linux-hardware.org/?probe=482c83143b) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [6cd48c055d](https://linux-hardware.org/?probe=6cd48c055d) | Dec 08, 2023 |
| Dell          | Inspiron 15 3520            | [6452783d8a](https://linux-hardware.org/?probe=6452783d8a) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [2d85c45e57](https://linux-hardware.org/?probe=2d85c45e57) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [01177d538f](https://linux-hardware.org/?probe=01177d538f) | Dec 08, 2023 |
| Acer          | Aspire E5-573               | [c23042b293](https://linux-hardware.org/?probe=c23042b293) | Dec 08, 2023 |
| Timi          | RedmiBook 13 R              | [6b3b67cc8b](https://linux-hardware.org/?probe=6b3b67cc8b) | Dec 08, 2023 |
| HP            | Compaq 6720s                | [63200c945b](https://linux-hardware.org/?probe=63200c945b) | Dec 08, 2023 |
| HUAWEI        | BoDE-WXX9                   | [44e608daff](https://linux-hardware.org/?probe=44e608daff) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [afc78e9ba2](https://linux-hardware.org/?probe=afc78e9ba2) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a6b0055398](https://linux-hardware.org/?probe=a6b0055398) | Dec 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [529932bcd4](https://linux-hardware.org/?probe=529932bcd4) | Dec 08, 2023 |
| HP            | 15 Notebook PC              | [37a360ec8a](https://linux-hardware.org/?probe=37a360ec8a) | Dec 08, 2023 |
| HP            | EliteBook 840 G6            | [6e7af6d32b](https://linux-hardware.org/?probe=6e7af6d32b) | Dec 07, 2023 |
| ASUSTek       | X555BP                      | [b7680df948](https://linux-hardware.org/?probe=b7680df948) | Dec 07, 2023 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | [f7511ff0d0](https://linux-hardware.org/?probe=f7511ff0d0) | Dec 07, 2023 |
| Dell          | Latitude E5540              | [208d70d734](https://linux-hardware.org/?probe=208d70d734) | Dec 07, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [f85ac7ef66](https://linux-hardware.org/?probe=f85ac7ef66) | Dec 07, 2023 |
| Lenovo        | ThinkPad T540p 20BFS2600... | [b6ec0a5c30](https://linux-hardware.org/?probe=b6ec0a5c30) | Dec 07, 2023 |
| Medion        | Unknown                     | [58a27e1f8f](https://linux-hardware.org/?probe=58a27e1f8f) | Dec 07, 2023 |
| Dell          | Inspiron 13 5310            | [8a4776f925](https://linux-hardware.org/?probe=8a4776f925) | Dec 07, 2023 |
| HP            | ProBook 450 G2              | [0e087e0b94](https://linux-hardware.org/?probe=0e087e0b94) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cf8f25ba97](https://linux-hardware.org/?probe=cf8f25ba97) | Dec 07, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e9ddadffad](https://linux-hardware.org/?probe=e9ddadffad) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [673016ba0f](https://linux-hardware.org/?probe=673016ba0f) | Dec 07, 2023 |
| MSI           | CX62 7QL                    | [33cd9ad75d](https://linux-hardware.org/?probe=33cd9ad75d) | Dec 07, 2023 |
| Positivo      | Q4128C-S                    | [018aab637c](https://linux-hardware.org/?probe=018aab637c) | Dec 07, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [90ffb00870](https://linux-hardware.org/?probe=90ffb00870) | Dec 07, 2023 |
| HP            | Laptop 17-by3xxx            | [d124640ef5](https://linux-hardware.org/?probe=d124640ef5) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [2c7c5b2119](https://linux-hardware.org/?probe=2c7c5b2119) | Dec 06, 2023 |
| HP            | Pavilion 17                 | [93ecaf88d6](https://linux-hardware.org/?probe=93ecaf88d6) | Dec 06, 2023 |
| Dell          | Latitude E5440              | [56987fc258](https://linux-hardware.org/?probe=56987fc258) | Dec 06, 2023 |
| Dell          | Latitude E5440              | [6cdafbd9d1](https://linux-hardware.org/?probe=6cdafbd9d1) | Dec 06, 2023 |
| ASUSTek       | GL702VSK                    | [d8547acd71](https://linux-hardware.org/?probe=d8547acd71) | Dec 06, 2023 |
| Apple         | MacBookPro6,2               | [ee4cab6d84](https://linux-hardware.org/?probe=ee4cab6d84) | Dec 06, 2023 |
| ASUSTek       | UX510UWK                    | [30a7e501ad](https://linux-hardware.org/?probe=30a7e501ad) | Dec 06, 2023 |
| HP            | EliteBook 8460p             | [747cf33a22](https://linux-hardware.org/?probe=747cf33a22) | Dec 06, 2023 |
| Dell          | Vostro 3580                 | [896cdac0e2](https://linux-hardware.org/?probe=896cdac0e2) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [52ee43b1e5](https://linux-hardware.org/?probe=52ee43b1e5) | Dec 06, 2023 |
| Acer          | Aspire A315-23              | [7d11b1aed9](https://linux-hardware.org/?probe=7d11b1aed9) | Dec 06, 2023 |
| Acer          | Aspire A517-51G             | [68f538dbc9](https://linux-hardware.org/?probe=68f538dbc9) | Dec 06, 2023 |
| HP            | Notebook                    | [8431ed2498](https://linux-hardware.org/?probe=8431ed2498) | Dec 06, 2023 |
| ASUSTek       | UX305CA                     | [6bac81f943](https://linux-hardware.org/?probe=6bac81f943) | Dec 06, 2023 |
| Lenovo        | ThinkPad E460 20ET0014US    | [b1cf294932](https://linux-hardware.org/?probe=b1cf294932) | Dec 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c1a6e3eb9e](https://linux-hardware.org/?probe=c1a6e3eb9e) | Dec 06, 2023 |
| Dell          | Inspiron 7472               | [ef77efb220](https://linux-hardware.org/?probe=ef77efb220) | Dec 06, 2023 |
| HP            | ProBook 450 G7              | [b70e2e4765](https://linux-hardware.org/?probe=b70e2e4765) | Dec 05, 2023 |
| Toshiba       | Satellite S75-B             | [dbec4c564e](https://linux-hardware.org/?probe=dbec4c564e) | Dec 05, 2023 |
| Apple         | MacBookPro11,2              | [196d6bc9e8](https://linux-hardware.org/?probe=196d6bc9e8) | Dec 05, 2023 |
| Apple         | MacBookPro6,2               | [a47e6e3616](https://linux-hardware.org/?probe=a47e6e3616) | Dec 05, 2023 |
| Google        | Robo                        | [52fb2b7262](https://linux-hardware.org/?probe=52fb2b7262) | Dec 05, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [8d46bb6a3c](https://linux-hardware.org/?probe=8d46bb6a3c) | Dec 05, 2023 |
| Google        | Robo                        | [f18235e8ca](https://linux-hardware.org/?probe=f18235e8ca) | Dec 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0JC0... | [11fdf05513](https://linux-hardware.org/?probe=11fdf05513) | Dec 05, 2023 |
| Google        | Relm                        | [577c8dbfe0](https://linux-hardware.org/?probe=577c8dbfe0) | Dec 05, 2023 |
| Apple         | MacBookPro9,2               | [f665409b48](https://linux-hardware.org/?probe=f665409b48) | Dec 05, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [8fbe891429](https://linux-hardware.org/?probe=8fbe891429) | Dec 05, 2023 |
| SDZ           | X133                        | [6e7c008a6a](https://linux-hardware.org/?probe=6e7c008a6a) | Dec 05, 2023 |
| Acer          | Aspire A315-510P            | [3937003fd0](https://linux-hardware.org/?probe=3937003fd0) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [3306bdcb6c](https://linux-hardware.org/?probe=3306bdcb6c) | Dec 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c64bc46e3a](https://linux-hardware.org/?probe=c64bc46e3a) | Dec 05, 2023 |
| HP            | 550                         | [a3dc2d4062](https://linux-hardware.org/?probe=a3dc2d4062) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [becdc5222d](https://linux-hardware.org/?probe=becdc5222d) | Dec 05, 2023 |
| Dell          | Latitude E6440              | [74db313788](https://linux-hardware.org/?probe=74db313788) | Dec 05, 2023 |
| ASUSTek       | GL702VSK                    | [20e6076fd3](https://linux-hardware.org/?probe=20e6076fd3) | Dec 05, 2023 |
| ASUSTek       | K55DR                       | [a13beb506c](https://linux-hardware.org/?probe=a13beb506c) | Dec 05, 2023 |
| Fujitsu       | LIFEBOOK A357               | [8725242a43](https://linux-hardware.org/?probe=8725242a43) | Dec 04, 2023 |
| Acer          | Aspire A515-55              | [0c467a2af3](https://linux-hardware.org/?probe=0c467a2af3) | Dec 04, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [dfc33bff7a](https://linux-hardware.org/?probe=dfc33bff7a) | Dec 04, 2023 |
| Lenovo        | G50-45 80E3                 | [9cbacbf139](https://linux-hardware.org/?probe=9cbacbf139) | Dec 04, 2023 |
| HP            | Laptop 17t-cn200            | [26c356c486](https://linux-hardware.org/?probe=26c356c486) | Dec 04, 2023 |
| Acer          | Nitro AN517-41              | [a1b25ec823](https://linux-hardware.org/?probe=a1b25ec823) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [fd95385327](https://linux-hardware.org/?probe=fd95385327) | Dec 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c2d2b59a76](https://linux-hardware.org/?probe=c2d2b59a76) | Dec 04, 2023 |
| Dell          | Inspiron 3558               | [29d253c1cd](https://linux-hardware.org/?probe=29d253c1cd) | Dec 04, 2023 |
| Lenovo        | E41-25 81FS                 | [d088539ba0](https://linux-hardware.org/?probe=d088539ba0) | Dec 04, 2023 |
| HP            | EliteBook 840 G6            | [dc816e1423](https://linux-hardware.org/?probe=dc816e1423) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [80d59e5b16](https://linux-hardware.org/?probe=80d59e5b16) | Dec 03, 2023 |
| Acer          | Aspire 5750G                | [8bca63eb54](https://linux-hardware.org/?probe=8bca63eb54) | Dec 03, 2023 |
| ASUSTek       | K50IJ                       | [c093780dc5](https://linux-hardware.org/?probe=c093780dc5) | Dec 03, 2023 |
| Dell          | Vostro 3550                 | [0926acf98a](https://linux-hardware.org/?probe=0926acf98a) | Dec 03, 2023 |
| Acer          | Aspire E5-573               | [c265401f64](https://linux-hardware.org/?probe=c265401f64) | Dec 03, 2023 |
| Dell          | Precision 5680              | [6982d86e8c](https://linux-hardware.org/?probe=6982d86e8c) | Dec 03, 2023 |
| ASUSTek       | GL703VM                     | [616bfbe220](https://linux-hardware.org/?probe=616bfbe220) | Dec 03, 2023 |
| Acer          | Nitro AN515-57              | [1f8c488e82](https://linux-hardware.org/?probe=1f8c488e82) | Dec 03, 2023 |
| HP            | Pavilion 13 x360 PC         | [d481339f2f](https://linux-hardware.org/?probe=d481339f2f) | Dec 03, 2023 |
| HP            | EliteBook 840 G2            | [0ae6e0f882](https://linux-hardware.org/?probe=0ae6e0f882) | Dec 03, 2023 |
| Acer          | Aspire 5750G                | [f04a8e4722](https://linux-hardware.org/?probe=f04a8e4722) | Dec 03, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8d214d7977](https://linux-hardware.org/?probe=8d214d7977) | Dec 03, 2023 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | [9cedc35586](https://linux-hardware.org/?probe=9cedc35586) | Dec 03, 2023 |
| Acer          | Swift SF515-51T             | [3cd6a2e9dc](https://linux-hardware.org/?probe=3cd6a2e9dc) | Dec 03, 2023 |
| Acer          | Swift SF515-51T             | [a0306c58e5](https://linux-hardware.org/?probe=a0306c58e5) | Dec 03, 2023 |
| HP            | Pavilion 13 x360 PC         | [359c30e001](https://linux-hardware.org/?probe=359c30e001) | Dec 03, 2023 |
| MSI           | PS63 Modern 8RC             | [76f07c96fd](https://linux-hardware.org/?probe=76f07c96fd) | Dec 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [2d7c4215b0](https://linux-hardware.org/?probe=2d7c4215b0) | Dec 03, 2023 |
| Lenovo        | ThinkPad T440p 20AWA02M0... | [c977bbe2c4](https://linux-hardware.org/?probe=c977bbe2c4) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | [318a41e343](https://linux-hardware.org/?probe=318a41e343) | Dec 03, 2023 |
| HP            | Pavilion 15                 | [fecd529c90](https://linux-hardware.org/?probe=fecd529c90) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | [f5b7c2899a](https://linux-hardware.org/?probe=f5b7c2899a) | Dec 03, 2023 |
| UNOWHY        | Y13G002S4EI                 | [4587cd55f9](https://linux-hardware.org/?probe=4587cd55f9) | Dec 03, 2023 |
| Acer          | Nitro AN515-58              | [e2d48a6b41](https://linux-hardware.org/?probe=e2d48a6b41) | Dec 03, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | [7922226a1c](https://linux-hardware.org/?probe=7922226a1c) | Dec 02, 2023 |
| Lenovo        | ThinkPad T420 4180PBG       | [cb2b5c10a7](https://linux-hardware.org/?probe=cb2b5c10a7) | Dec 02, 2023 |
| Apple         | MacBookPro13,1              | [165571d0a3](https://linux-hardware.org/?probe=165571d0a3) | Dec 02, 2023 |
| Dell          | Latitude E6430              | [fedc3b8a8d](https://linux-hardware.org/?probe=fedc3b8a8d) | Dec 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | [b7acc6efe8](https://linux-hardware.org/?probe=b7acc6efe8) | Dec 02, 2023 |
| ASUSTek       | K53E                        | [4b184d1d81](https://linux-hardware.org/?probe=4b184d1d81) | Dec 02, 2023 |
| MSI           | GE72 6QD                    | [2e250b81a4](https://linux-hardware.org/?probe=2e250b81a4) | Dec 02, 2023 |
| MSI           | GE72 6QF                    | [2cce4d92fe](https://linux-hardware.org/?probe=2cce4d92fe) | Dec 02, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [3b3d0cb740](https://linux-hardware.org/?probe=3b3d0cb740) | Dec 02, 2023 |
| HUAWEI        | HLYL-WXX9                   | [514428be56](https://linux-hardware.org/?probe=514428be56) | Dec 02, 2023 |
| Dell          | Latitude E6430              | [980a0b89b5](https://linux-hardware.org/?probe=980a0b89b5) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [a1a93224e4](https://linux-hardware.org/?probe=a1a93224e4) | Dec 02, 2023 |
| SK hynix      | HyBook                      | [4c0f06eb94](https://linux-hardware.org/?probe=4c0f06eb94) | Dec 02, 2023 |
| Sony          | VPCEB1S1E                   | [d240ac5f41](https://linux-hardware.org/?probe=d240ac5f41) | Dec 02, 2023 |
| Dell          | G15 5510                    | [bdfca2648a](https://linux-hardware.org/?probe=bdfca2648a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | [186eb0ce63](https://linux-hardware.org/?probe=186eb0ce63) | Dec 02, 2023 |
| HP            | EliteBook 8560p             | [6f6f496558](https://linux-hardware.org/?probe=6f6f496558) | Dec 01, 2023 |
| Acer          | Predator PH317-52           | [013bd43bc7](https://linux-hardware.org/?probe=013bd43bc7) | Dec 01, 2023 |
| Dell          | Studio 1737                 | [4e400ded4b](https://linux-hardware.org/?probe=4e400ded4b) | Dec 01, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | [1645df2234](https://linux-hardware.org/?probe=1645df2234) | Dec 01, 2023 |
| Lenovo        | ThinkPad W550s 20E2CTO1W... | [570da1b5b2](https://linux-hardware.org/?probe=570da1b5b2) | Dec 01, 2023 |
| Toshiba       | Satellite C870-1F3          | [adb628ff38](https://linux-hardware.org/?probe=adb628ff38) | Dec 01, 2023 |
| Toshiba       | Satellite C870-1F3          | [93907ea0f4](https://linux-hardware.org/?probe=93907ea0f4) | Dec 01, 2023 |
| Dell          | Latitude 5520               | [5b61695af2](https://linux-hardware.org/?probe=5b61695af2) | Dec 01, 2023 |
| Acer          | Predator PH317-52           | [abb14dcedb](https://linux-hardware.org/?probe=abb14dcedb) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | [22af506155](https://linux-hardware.org/?probe=22af506155) | Dec 01, 2023 |
| Acer          | Aspire V3-571               | [90e07856e4](https://linux-hardware.org/?probe=90e07856e4) | Dec 01, 2023 |
| Lenovo        | ThinkPad X60 1706M8U        | [ab0582fe71](https://linux-hardware.org/?probe=ab0582fe71) | Dec 01, 2023 |
| Dell          | Latitude E6520              | [1cb2209cef](https://linux-hardware.org/?probe=1cb2209cef) | Dec 01, 2023 |
| Dell          | XPS420                      | [2204a9646d](https://linux-hardware.org/?probe=2204a9646d) | Dec 01, 2023 |
| Dell          | Inspiron 15-7568            | [80d4969c23](https://linux-hardware.org/?probe=80d4969c23) | Dec 01, 2023 |
| HP            | Pavilion 15                 | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| Lenovo        | ThinkPad T490s 20NYS02A0... | [a23499d148](https://linux-hardware.org/?probe=a23499d148) | Nov 30, 2023 |
| Acer          | Aspire V5-573               | [8a76c8baac](https://linux-hardware.org/?probe=8a76c8baac) | Nov 30, 2023 |
| Lenovo        | G50-70 20351                | [7b700be3e2](https://linux-hardware.org/?probe=7b700be3e2) | Nov 30, 2023 |
| HP            | 15                          | [df51360bdd](https://linux-hardware.org/?probe=df51360bdd) | Nov 30, 2023 |
| Clevo         | C4100/C5100                 | [8e2637b70f](https://linux-hardware.org/?probe=8e2637b70f) | Nov 30, 2023 |
| Clevo         | C4100/C5100                 | [ea98614215](https://linux-hardware.org/?probe=ea98614215) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [120ad9d1f3](https://linux-hardware.org/?probe=120ad9d1f3) | Nov 30, 2023 |
| Dell          | Inspiron 3521               | [3e97ecc95d](https://linux-hardware.org/?probe=3e97ecc95d) | Nov 30, 2023 |
| Kelyx Arge... | Kelyx KL3450                | [0d6ca3bd1a](https://linux-hardware.org/?probe=0d6ca3bd1a) | Nov 30, 2023 |
| Acer          | Predator PH315-52           | [bb1fc18586](https://linux-hardware.org/?probe=bb1fc18586) | Nov 30, 2023 |
| HP            | Pavilion g6                 | [f36afef418](https://linux-hardware.org/?probe=f36afef418) | Nov 30, 2023 |
| Apple         | MacBookPro5,4               | [bc9394652a](https://linux-hardware.org/?probe=bc9394652a) | Nov 30, 2023 |
| MSI           | Prestige 16Studio A13VF     | [dc93bfeb80](https://linux-hardware.org/?probe=dc93bfeb80) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d92b5d4caf](https://linux-hardware.org/?probe=d92b5d4caf) | Nov 30, 2023 |
| Lenovo        | B50-50 80S2                 | [51d5653319](https://linux-hardware.org/?probe=51d5653319) | Nov 30, 2023 |
| Acer          | Nitro AN515-42              | [4c24f3fddf](https://linux-hardware.org/?probe=4c24f3fddf) | Nov 30, 2023 |
| Irbis         | NB290                       | [75805d6558](https://linux-hardware.org/?probe=75805d6558) | Nov 29, 2023 |
| Google        | Nautilus                    | [1b255e77a3](https://linux-hardware.org/?probe=1b255e77a3) | Nov 29, 2023 |
| PC Special... | Recoil 16                   | [3dd3569b17](https://linux-hardware.org/?probe=3dd3569b17) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | [cd5316e290](https://linux-hardware.org/?probe=cd5316e290) | Nov 29, 2023 |
| Notebook      | P9XXEN_EF_ED                | [29e5da6013](https://linux-hardware.org/?probe=29e5da6013) | Nov 29, 2023 |
| Apple         | MacBookPro13,1              | [6074c742c1](https://linux-hardware.org/?probe=6074c742c1) | Nov 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2d1452d207](https://linux-hardware.org/?probe=2d1452d207) | Nov 29, 2023 |
| ASUSTek       | N71Jq                       | [f13e32bb82](https://linux-hardware.org/?probe=f13e32bb82) | Nov 29, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0524ad397b](https://linux-hardware.org/?probe=0524ad397b) | Nov 29, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2ad6007c7f](https://linux-hardware.org/?probe=2ad6007c7f) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK E5512              | [9df65d1a3d](https://linux-hardware.org/?probe=9df65d1a3d) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| HP            | Laptop 15-da0xxx            | [4d9e778bd2](https://linux-hardware.org/?probe=4d9e778bd2) | Nov 29, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [6b83c6bd43](https://linux-hardware.org/?probe=6b83c6bd43) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | [d9e4a9a2cd](https://linux-hardware.org/?probe=d9e4a9a2cd) | Nov 29, 2023 |
| HP            | Laptop 15-bw0xx             | [e3e8042ebf](https://linux-hardware.org/?probe=e3e8042ebf) | Nov 29, 2023 |
| ASUSTek       | X441NA                      | [6965a13f84](https://linux-hardware.org/?probe=6965a13f84) | Nov 29, 2023 |
| ASUSTek       | K501UW                      | [bb2313602b](https://linux-hardware.org/?probe=bb2313602b) | Nov 29, 2023 |
| ASUSTek       | X555LD                      | [363701a47c](https://linux-hardware.org/?probe=363701a47c) | Nov 29, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [77e37462eb](https://linux-hardware.org/?probe=77e37462eb) | Nov 29, 2023 |
| HP            | EliteBook 640 14 inch G9... | [a9f36d870b](https://linux-hardware.org/?probe=a9f36d870b) | Nov 28, 2023 |
| MSI           | GF63 Thin 11UD              | [bde4e92728](https://linux-hardware.org/?probe=bde4e92728) | Nov 28, 2023 |
| ASUSTek       | X200CA                      | [d0ea54e4fa](https://linux-hardware.org/?probe=d0ea54e4fa) | Nov 28, 2023 |
| HP            | EliteBook 860 16 inch G1... | [ebf45c9457](https://linux-hardware.org/?probe=ebf45c9457) | Nov 28, 2023 |
| HP            | EliteBook 840 14 inch G9... | [bbfe8e99fc](https://linux-hardware.org/?probe=bbfe8e99fc) | Nov 28, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [4fbfde63e3](https://linux-hardware.org/?probe=4fbfde63e3) | Nov 28, 2023 |
| Toshiba       | Satellite L855              | [b1f194a955](https://linux-hardware.org/?probe=b1f194a955) | Nov 28, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [ff997b6ca3](https://linux-hardware.org/?probe=ff997b6ca3) | Nov 28, 2023 |
| Sony          | VPCF13M1E                   | [4a6e054f68](https://linux-hardware.org/?probe=4a6e054f68) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [144a7d4106](https://linux-hardware.org/?probe=144a7d4106) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [49fad3d40c](https://linux-hardware.org/?probe=49fad3d40c) | Nov 28, 2023 |
| HP            | G60                         | [eb7f66cedc](https://linux-hardware.org/?probe=eb7f66cedc) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9f9e92a1f6](https://linux-hardware.org/?probe=9f9e92a1f6) | Nov 28, 2023 |
| Dell          | Latitude 7440               | [aa4dce8576](https://linux-hardware.org/?probe=aa4dce8576) | Nov 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | [f5f1058473](https://linux-hardware.org/?probe=f5f1058473) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4243PH3       | [63ba3b10d4](https://linux-hardware.org/?probe=63ba3b10d4) | Nov 27, 2023 |
| Dell          | Precision 5520              | [4d773def1d](https://linux-hardware.org/?probe=4d773def1d) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [8739388aac](https://linux-hardware.org/?probe=8739388aac) | Nov 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [b760a588ee](https://linux-hardware.org/?probe=b760a588ee) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9ba9e50996](https://linux-hardware.org/?probe=9ba9e50996) | Nov 27, 2023 |
| ASUSTek       | K56CB                       | [fc0cf53ff2](https://linux-hardware.org/?probe=fc0cf53ff2) | Nov 27, 2023 |
| HP            | ZBook 15 G3                 | [03586846aa](https://linux-hardware.org/?probe=03586846aa) | Nov 27, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [aadba04a83](https://linux-hardware.org/?probe=aadba04a83) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DU14    | [37cb36a6fa](https://linux-hardware.org/?probe=37cb36a6fa) | Nov 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ade10d9872](https://linux-hardware.org/?probe=ade10d9872) | Nov 27, 2023 |
| HUAWEI        | CREF-XX                     | [096f432812](https://linux-hardware.org/?probe=096f432812) | Nov 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06bf1b0f79](https://linux-hardware.org/?probe=06bf1b0f79) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [956dbda516](https://linux-hardware.org/?probe=956dbda516) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | [92f23bf41c](https://linux-hardware.org/?probe=92f23bf41c) | Nov 26, 2023 |
| SHENZHEN Y... | XBOOK-3                     | [beeefc2461](https://linux-hardware.org/?probe=beeefc2461) | Nov 26, 2023 |
| Dell          | Latitude 5590               | [cd823db120](https://linux-hardware.org/?probe=cd823db120) | Nov 26, 2023 |
| HP            | Notebook                    | [d13874e201](https://linux-hardware.org/?probe=d13874e201) | Nov 26, 2023 |
| HP            | Notebook                    | [6d348c3a7a](https://linux-hardware.org/?probe=6d348c3a7a) | Nov 26, 2023 |
| MSI           | Modern 15 A10M              | [105e84e282](https://linux-hardware.org/?probe=105e84e282) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [351dde4845](https://linux-hardware.org/?probe=351dde4845) | Nov 26, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [8378baf644](https://linux-hardware.org/?probe=8378baf644) | Nov 26, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [2ca445207e](https://linux-hardware.org/?probe=2ca445207e) | Nov 26, 2023 |
| Lenovo        | ThinkPad R400 7440DQ6       | [3720b52e84](https://linux-hardware.org/?probe=3720b52e84) | Nov 26, 2023 |
| HP            | Laptop 15-db0xxx            | [22dbbee029](https://linux-hardware.org/?probe=22dbbee029) | Nov 26, 2023 |
| HP            | Notebook                    | [671f5f59ac](https://linux-hardware.org/?probe=671f5f59ac) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [7ea3637c4f](https://linux-hardware.org/?probe=7ea3637c4f) | Nov 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [7b30223421](https://linux-hardware.org/?probe=7b30223421) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | [ed18c0bb54](https://linux-hardware.org/?probe=ed18c0bb54) | Nov 26, 2023 |
| HP            | ProBook 450 G7              | [6e903b92f6](https://linux-hardware.org/?probe=6e903b92f6) | Nov 26, 2023 |
| HP            | Pavilion dv6                | [e09777761c](https://linux-hardware.org/?probe=e09777761c) | Nov 26, 2023 |
| Toshiba       | Satellite L300D             | [5910ef90fd](https://linux-hardware.org/?probe=5910ef90fd) | Nov 26, 2023 |
| ASUSTek       | K53SD                       | [e7c6d5b018](https://linux-hardware.org/?probe=e7c6d5b018) | Nov 26, 2023 |
| Panasonic     | CF-53JALZY1M                | [e90faa0f97](https://linux-hardware.org/?probe=e90faa0f97) | Nov 26, 2023 |
| Samsung       | R520/R522/R620              | [36cde2f22a](https://linux-hardware.org/?probe=36cde2f22a) | Nov 25, 2023 |
| Dell          | XPS 15 9570                 | [99daa92571](https://linux-hardware.org/?probe=99daa92571) | Nov 25, 2023 |
| Dell          | Latitude 7490               | [a9d03c8349](https://linux-hardware.org/?probe=a9d03c8349) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | [ea362b85cf](https://linux-hardware.org/?probe=ea362b85cf) | Nov 25, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [8973295484](https://linux-hardware.org/?probe=8973295484) | Nov 25, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [7359fe59a4](https://linux-hardware.org/?probe=7359fe59a4) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [23914b5dc2](https://linux-hardware.org/?probe=23914b5dc2) | Nov 25, 2023 |
| Unknown       | Unknown                     | [a719bb0ba3](https://linux-hardware.org/?probe=a719bb0ba3) | Nov 25, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [344eaa9a2a](https://linux-hardware.org/?probe=344eaa9a2a) | Nov 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [d32adc8fff](https://linux-hardware.org/?probe=d32adc8fff) | Nov 24, 2023 |
| ASUSTek       | K501UW                      | [4f1442fcc4](https://linux-hardware.org/?probe=4f1442fcc4) | Nov 24, 2023 |
| Dell          | Latitude D830               | [472b675869](https://linux-hardware.org/?probe=472b675869) | Nov 24, 2023 |
| Acer          | Aspire A315-58              | [1bf1e47f81](https://linux-hardware.org/?probe=1bf1e47f81) | Nov 24, 2023 |
| Apple         | MacBookAir6,2               | [013087de59](https://linux-hardware.org/?probe=013087de59) | Nov 24, 2023 |
| Dell          | Latitude 7400               | [86a9de8212](https://linux-hardware.org/?probe=86a9de8212) | Nov 24, 2023 |
| Dell          | XPS 13 9305                 | [6a47a3a5de](https://linux-hardware.org/?probe=6a47a3a5de) | Nov 24, 2023 |
| Unknown       | Unknown                     | [b96d7a11ef](https://linux-hardware.org/?probe=b96d7a11ef) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5a01c502bd](https://linux-hardware.org/?probe=5a01c502bd) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [d262dd65d4](https://linux-hardware.org/?probe=d262dd65d4) | Nov 24, 2023 |
| Timi          | Mi NoteBook Pro             | [90499ad4f0](https://linux-hardware.org/?probe=90499ad4f0) | Nov 24, 2023 |
| Acer          | Aspire A315-59              | [37984277e9](https://linux-hardware.org/?probe=37984277e9) | Nov 24, 2023 |
| Packard Be... | EasyNote ENLG71BM           | [25ae01fde2](https://linux-hardware.org/?probe=25ae01fde2) | Nov 24, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aa4097f060](https://linux-hardware.org/?probe=aa4097f060) | Nov 24, 2023 |
| Apple         | MacBookPro14,2              | [e210f3a972](https://linux-hardware.org/?probe=e210f3a972) | Nov 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f17333cca3](https://linux-hardware.org/?probe=f17333cca3) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | [d733fc5f50](https://linux-hardware.org/?probe=d733fc5f50) | Nov 24, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | [17fd894479](https://linux-hardware.org/?probe=17fd894479) | Nov 24, 2023 |
| HP            | Presario CQ61               | [5c7a775c76](https://linux-hardware.org/?probe=5c7a775c76) | Nov 24, 2023 |
| Samsung       | 960XFH                      | [2ad3d93589](https://linux-hardware.org/?probe=2ad3d93589) | Nov 24, 2023 |
| Dell          | Latitude E5550              | [96a4d03e8c](https://linux-hardware.org/?probe=96a4d03e8c) | Nov 23, 2023 |
| Linx          | LINX1010L                   | [07d470eaac](https://linux-hardware.org/?probe=07d470eaac) | Nov 23, 2023 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [db22f8c316](https://linux-hardware.org/?probe=db22f8c316) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0LE0... | [3da7eab7e8](https://linux-hardware.org/?probe=3da7eab7e8) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [ca5e9fbf52](https://linux-hardware.org/?probe=ca5e9fbf52) | Nov 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [94fc35a5f9](https://linux-hardware.org/?probe=94fc35a5f9) | Nov 23, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [49ec5aa905](https://linux-hardware.org/?probe=49ec5aa905) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [ab672024d6](https://linux-hardware.org/?probe=ab672024d6) | Nov 23, 2023 |
| HP            | ProBook 430 G5              | [1c9b64b051](https://linux-hardware.org/?probe=1c9b64b051) | Nov 23, 2023 |
| HP            | Pavilion Notebook           | [7d55f31a65](https://linux-hardware.org/?probe=7d55f31a65) | Nov 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b450d3fe43](https://linux-hardware.org/?probe=b450d3fe43) | Nov 23, 2023 |
| HP            | Laptop 17-cp0xxx            | [7f23e0e274](https://linux-hardware.org/?probe=7f23e0e274) | Nov 23, 2023 |
| Dell          | Latitude 7440               | [c05ecee673](https://linux-hardware.org/?probe=c05ecee673) | Nov 23, 2023 |
| Acer          | Aspire Lite AL15-52         | [a86c46d6fa](https://linux-hardware.org/?probe=a86c46d6fa) | Nov 23, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e897dd5b20](https://linux-hardware.org/?probe=e897dd5b20) | Nov 23, 2023 |
| HP            | Notebook                    | [897e3bf444](https://linux-hardware.org/?probe=897e3bf444) | Nov 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [8d944b2cf7](https://linux-hardware.org/?probe=8d944b2cf7) | Nov 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [58252e8597](https://linux-hardware.org/?probe=58252e8597) | Nov 22, 2023 |
| Toshiba       | Satellite Pro L500          | [712435b9a5](https://linux-hardware.org/?probe=712435b9a5) | Nov 22, 2023 |
| Google        | Samus                       | [d87150c47b](https://linux-hardware.org/?probe=d87150c47b) | Nov 22, 2023 |
| Lenovo        | ThinkPad E560 20EV0000ZA    | [dad936ca8a](https://linux-hardware.org/?probe=dad936ca8a) | Nov 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ac1c1063ba](https://linux-hardware.org/?probe=ac1c1063ba) | Nov 22, 2023 |
| Lenovo        | ThinkPad E560 20EV0000ZA    | [6cb322f4cb](https://linux-hardware.org/?probe=6cb322f4cb) | Nov 22, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3f798c7bfd](https://linux-hardware.org/?probe=3f798c7bfd) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [5ebe8bc062](https://linux-hardware.org/?probe=5ebe8bc062) | Nov 22, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [bd428a8490](https://linux-hardware.org/?probe=bd428a8490) | Nov 22, 2023 |
| Samsung       | 760XDA                      | [491ebf48ff](https://linux-hardware.org/?probe=491ebf48ff) | Nov 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [e80db886ed](https://linux-hardware.org/?probe=e80db886ed) | Nov 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8789c24bc2](https://linux-hardware.org/?probe=8789c24bc2) | Nov 22, 2023 |
| Acer          | TravelMate 5760             | [bcec28eaaa](https://linux-hardware.org/?probe=bcec28eaaa) | Nov 22, 2023 |
| Toshiba       | Satellite C670D-11Z         | [354cabf09c](https://linux-hardware.org/?probe=354cabf09c) | Nov 22, 2023 |
| Apple         | MacBook3,1                  | [ceffa3f19e](https://linux-hardware.org/?probe=ceffa3f19e) | Nov 22, 2023 |
| Apple         | MacBook3,1                  | [fa85f5740d](https://linux-hardware.org/?probe=fa85f5740d) | Nov 22, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [1862966cbe](https://linux-hardware.org/?probe=1862966cbe) | Nov 22, 2023 |
| TECNO         | MEGABOOK T1                 | [af9ab5c122](https://linux-hardware.org/?probe=af9ab5c122) | Nov 22, 2023 |
| Dell          | Latitude E6540              | [6fe2a2a1dd](https://linux-hardware.org/?probe=6fe2a2a1dd) | Nov 22, 2023 |
| Acer          | Aspire 7750G                | [eb37f9f9b4](https://linux-hardware.org/?probe=eb37f9f9b4) | Nov 22, 2023 |
| Dell          | Latitude 3580               | [c5c5d11d39](https://linux-hardware.org/?probe=c5c5d11d39) | Nov 22, 2023 |
| MSI           | Prestige 15 A11SCX          | [e443925a9c](https://linux-hardware.org/?probe=e443925a9c) | Nov 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS02A0... | [90e2dbaa74](https://linux-hardware.org/?probe=90e2dbaa74) | Nov 21, 2023 |
| Dell          | Latitude E5450              | [51011f2935](https://linux-hardware.org/?probe=51011f2935) | Nov 21, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [56319a6e9d](https://linux-hardware.org/?probe=56319a6e9d) | Nov 21, 2023 |
| HP            | Pavilion 15                 | [9ac4b59c55](https://linux-hardware.org/?probe=9ac4b59c55) | Nov 21, 2023 |
| Acer          | Aspire E1-731               | [abb995bc38](https://linux-hardware.org/?probe=abb995bc38) | Nov 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [88fba30cec](https://linux-hardware.org/?probe=88fba30cec) | Nov 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d91c731a96](https://linux-hardware.org/?probe=d91c731a96) | Nov 21, 2023 |
| Dell          | Latitude E6430              | [7fb0b53d1c](https://linux-hardware.org/?probe=7fb0b53d1c) | Nov 21, 2023 |
| Acer          | Aspire A315-41              | [e880b6a41f](https://linux-hardware.org/?probe=e880b6a41f) | Nov 21, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [8d5fa67be3](https://linux-hardware.org/?probe=8d5fa67be3) | Nov 21, 2023 |
| HP            | ProBook 6560b               | [84d3b269c8](https://linux-hardware.org/?probe=84d3b269c8) | Nov 21, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2964062ee1](https://linux-hardware.org/?probe=2964062ee1) | Nov 21, 2023 |
| HP            | Laptop 15-da0xxx            | [a322cc26b1](https://linux-hardware.org/?probe=a322cc26b1) | Nov 21, 2023 |
| MSI           | Pulse GL76 12UEK            | [def3f12e81](https://linux-hardware.org/?probe=def3f12e81) | Nov 21, 2023 |
| Allview       | Allbook H                   | [8c23eb07ac](https://linux-hardware.org/?probe=8c23eb07ac) | Nov 21, 2023 |
| HP            | EliteBook 840 G3            | [3adc2d4951](https://linux-hardware.org/?probe=3adc2d4951) | Nov 21, 2023 |
| HP            | Pavilion 15                 | [a38bb99384](https://linux-hardware.org/?probe=a38bb99384) | Nov 21, 2023 |
| Samsung       | 550XDA                      | [4c1328b562](https://linux-hardware.org/?probe=4c1328b562) | Nov 21, 2023 |
| Apple         | MacBookPro7,1               | [e0f2e8180d](https://linux-hardware.org/?probe=e0f2e8180d) | Nov 21, 2023 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | [43d2b6b8b6](https://linux-hardware.org/?probe=43d2b6b8b6) | Nov 21, 2023 |
| Acer          | Aspire A515-43              | [294889610d](https://linux-hardware.org/?probe=294889610d) | Nov 20, 2023 |
| Dell          | Inspiron 3501               | [c207576b9e](https://linux-hardware.org/?probe=c207576b9e) | Nov 20, 2023 |
| MSI           | Bravo 15 A4DDR              | [d678fe79f8](https://linux-hardware.org/?probe=d678fe79f8) | Nov 20, 2023 |
| Dell          | Inspiron 3501               | [8ed6bf7673](https://linux-hardware.org/?probe=8ed6bf7673) | Nov 20, 2023 |
| Dell          | Inspiron N5110              | [78992043bf](https://linux-hardware.org/?probe=78992043bf) | Nov 20, 2023 |
| Lenovo        | ThinkPad X230 2320JPU       | [10e0d2e090](https://linux-hardware.org/?probe=10e0d2e090) | Nov 20, 2023 |
| HP            | Laptop 15-bs0xx             | [3982d2c377](https://linux-hardware.org/?probe=3982d2c377) | Nov 20, 2023 |
| Lenovo        | Legion R7000P ARH7 82RE     | [0ae39d9390](https://linux-hardware.org/?probe=0ae39d9390) | Nov 20, 2023 |
| HP            | ProBook 650 G5              | [ea9539a6d2](https://linux-hardware.org/?probe=ea9539a6d2) | Nov 20, 2023 |
| Dell          | Latitude 5440               | [107b422b2c](https://linux-hardware.org/?probe=107b422b2c) | Nov 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C4S... | [e5d9227cf4](https://linux-hardware.org/?probe=e5d9227cf4) | Nov 20, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7183e48f52](https://linux-hardware.org/?probe=7183e48f52) | Nov 20, 2023 |
| Dell          | G15 5530                    | [0d608c0d48](https://linux-hardware.org/?probe=0d608c0d48) | Nov 20, 2023 |
| ASUSTek       | X555LN                      | [e2f9466842](https://linux-hardware.org/?probe=e2f9466842) | Nov 19, 2023 |
| HP            | Notebook                    | [3b356149fd](https://linux-hardware.org/?probe=3b356149fd) | Nov 19, 2023 |
| Sony          | SVP1321S1EBI                | [589b7a8e3f](https://linux-hardware.org/?probe=589b7a8e3f) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0af175a9d7](https://linux-hardware.org/?probe=0af175a9d7) | Nov 19, 2023 |
| ASUSTek       | GL553VD                     | [eff083cd7e](https://linux-hardware.org/?probe=eff083cd7e) | Nov 19, 2023 |
| HP            | Pavilion dm4                | [6fb416e928](https://linux-hardware.org/?probe=6fb416e928) | Nov 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5edc51a963](https://linux-hardware.org/?probe=5edc51a963) | Nov 19, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e89473830f](https://linux-hardware.org/?probe=e89473830f) | Nov 19, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [bcaaff7eea](https://linux-hardware.org/?probe=bcaaff7eea) | Nov 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0B70... | [808b3a2a5d](https://linux-hardware.org/?probe=808b3a2a5d) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [ed0b97c0a4](https://linux-hardware.org/?probe=ed0b97c0a4) | Nov 19, 2023 |
| HP            | ProBook 6550b               | [b0ed7bd41d](https://linux-hardware.org/?probe=b0ed7bd41d) | Nov 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | [21433a0601](https://linux-hardware.org/?probe=21433a0601) | Nov 19, 2023 |
| HP            | ProBook 640 G1              | [702a886d45](https://linux-hardware.org/?probe=702a886d45) | Nov 19, 2023 |
| Apple         | MacBookPro11,4              | [07fadadf4b](https://linux-hardware.org/?probe=07fadadf4b) | Nov 19, 2023 |
| HP            | ZBook Firefly 16 inch G1... | [e27aa36a0d](https://linux-hardware.org/?probe=e27aa36a0d) | Nov 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [2f1ba470f6](https://linux-hardware.org/?probe=2f1ba470f6) | Nov 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [f5414a4ffe](https://linux-hardware.org/?probe=f5414a4ffe) | Nov 18, 2023 |
| Toshiba       | Satellite C660D             | [fed171dba3](https://linux-hardware.org/?probe=fed171dba3) | Nov 18, 2023 |
| Toshiba       | Satellite P50t-B-10T        | [1515cbaa91](https://linux-hardware.org/?probe=1515cbaa91) | Nov 18, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [f3170951f8](https://linux-hardware.org/?probe=f3170951f8) | Nov 18, 2023 |
| ASUSTek       | K501UXM                     | [727b1debe1](https://linux-hardware.org/?probe=727b1debe1) | Nov 18, 2023 |
| HP            | Compaq 6910p                | [7501434931](https://linux-hardware.org/?probe=7501434931) | Nov 18, 2023 |
| ASUSTek       | X550JX                      | [d8e10147d2](https://linux-hardware.org/?probe=d8e10147d2) | Nov 18, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2be4a499cb](https://linux-hardware.org/?probe=2be4a499cb) | Nov 18, 2023 |
| HP            | ProBook 650 G1              | [d61fe67d3f](https://linux-hardware.org/?probe=d61fe67d3f) | Nov 18, 2023 |
| Dell          | Latitude 5430               | [a2757959fc](https://linux-hardware.org/?probe=a2757959fc) | Nov 18, 2023 |
| ASUSTek       | S300CA                      | [0d1a79b878](https://linux-hardware.org/?probe=0d1a79b878) | Nov 18, 2023 |
| HP            | ProBook 440 G7              | [dbbf51e4c5](https://linux-hardware.org/?probe=dbbf51e4c5) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [669208a0f6](https://linux-hardware.org/?probe=669208a0f6) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [a8095f2a1a](https://linux-hardware.org/?probe=a8095f2a1a) | Nov 18, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [08bbcc2f7f](https://linux-hardware.org/?probe=08bbcc2f7f) | Nov 18, 2023 |
| Acer          | Nitro AN515-56              | [dc208dca03](https://linux-hardware.org/?probe=dc208dca03) | Nov 18, 2023 |
| Sony          | SVE1713Q1EB                 | [d561fc3b0e](https://linux-hardware.org/?probe=d561fc3b0e) | Nov 17, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [6e4144386d](https://linux-hardware.org/?probe=6e4144386d) | Nov 17, 2023 |
| Dell          | Vostro 15 5510              | [21505599dd](https://linux-hardware.org/?probe=21505599dd) | Nov 17, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [66a57a819b](https://linux-hardware.org/?probe=66a57a819b) | Nov 17, 2023 |
| HP            | ProBook 650 G1              | [8cba43dfd6](https://linux-hardware.org/?probe=8cba43dfd6) | Nov 17, 2023 |
| Dell          | Inspiron 15 3515            | [c526bb7fac](https://linux-hardware.org/?probe=c526bb7fac) | Nov 17, 2023 |
| Dell          | Latitude 5420               | [cc85910964](https://linux-hardware.org/?probe=cc85910964) | Nov 17, 2023 |
| Dell          | Inspiron 15 3515            | [ea21fd1e60](https://linux-hardware.org/?probe=ea21fd1e60) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | [44d575bc98](https://linux-hardware.org/?probe=44d575bc98) | Nov 17, 2023 |
| Lenovo        | ThinkPad X220 4290KV8       | [cb34220afb](https://linux-hardware.org/?probe=cb34220afb) | Nov 17, 2023 |
| HP            | Pavilion dv5                | [0ad6009c48](https://linux-hardware.org/?probe=0ad6009c48) | Nov 17, 2023 |
| HP            | Pavilion dv5                | [f79c95680b](https://linux-hardware.org/?probe=f79c95680b) | Nov 17, 2023 |
| Dell          | XPS 9320                    | [04760461ba](https://linux-hardware.org/?probe=04760461ba) | Nov 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [56ae69a7dc](https://linux-hardware.org/?probe=56ae69a7dc) | Nov 17, 2023 |
| Apple         | MacBookPro5,2               | [6ab9a3a012](https://linux-hardware.org/?probe=6ab9a3a012) | Nov 17, 2023 |
| ASUSTek       | X201E                       | [f9b0c13ec1](https://linux-hardware.org/?probe=f9b0c13ec1) | Nov 17, 2023 |
| MSI           | Pulse GL66 12UEK            | [9421ac824c](https://linux-hardware.org/?probe=9421ac824c) | Nov 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | [168e6686a8](https://linux-hardware.org/?probe=168e6686a8) | Nov 17, 2023 |
| HP            | Pavilion dv6                | [2aaedc3314](https://linux-hardware.org/?probe=2aaedc3314) | Nov 17, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [ca7747546b](https://linux-hardware.org/?probe=ca7747546b) | Nov 17, 2023 |
| Apple         | MacBookAir3,2               | [17cf4dd653](https://linux-hardware.org/?probe=17cf4dd653) | Nov 17, 2023 |
| Lenovo        | ThinkPad T460 20FMS36800    | [5954abe148](https://linux-hardware.org/?probe=5954abe148) | Nov 17, 2023 |
| Medion        | P8614                       | [fbbdd9bd21](https://linux-hardware.org/?probe=fbbdd9bd21) | Nov 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [a76432f7df](https://linux-hardware.org/?probe=a76432f7df) | Nov 16, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [3e6ad056d6](https://linux-hardware.org/?probe=3e6ad056d6) | Nov 16, 2023 |
| Dell          | XPS 15 9510                 | [8414c926f0](https://linux-hardware.org/?probe=8414c926f0) | Nov 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | [fd50b727cb](https://linux-hardware.org/?probe=fd50b727cb) | Nov 16, 2023 |
| HUAWEI        | MDF-XX                      | [d4cdc093f4](https://linux-hardware.org/?probe=d4cdc093f4) | Nov 16, 2023 |
| Acer          | Extensa 5220                | [313dfe3829](https://linux-hardware.org/?probe=313dfe3829) | Nov 16, 2023 |
| HP            | ProBook 650 G5              | [5736b02f06](https://linux-hardware.org/?probe=5736b02f06) | Nov 16, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [a9704992fa](https://linux-hardware.org/?probe=a9704992fa) | Nov 16, 2023 |
| Apple         | MacBook5,1                  | [1987d370db](https://linux-hardware.org/?probe=1987d370db) | Nov 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3281df4dcd](https://linux-hardware.org/?probe=3281df4dcd) | Nov 15, 2023 |
| Toshiba       | Satellite C55-C             | [30653c48a7](https://linux-hardware.org/?probe=30653c48a7) | Nov 15, 2023 |
| Dell          | Latitude 5440               | [1f337ab4b1](https://linux-hardware.org/?probe=1f337ab4b1) | Nov 15, 2023 |
| Lenovo        | ThinkPad E480 20KN003WLM    | [f5b7705de3](https://linux-hardware.org/?probe=f5b7705de3) | Nov 15, 2023 |
| Acer          | Extensa 5220                | [6b5e8902be](https://linux-hardware.org/?probe=6b5e8902be) | Nov 15, 2023 |
| HP            | Notebook                    | [73567de74e](https://linux-hardware.org/?probe=73567de74e) | Nov 15, 2023 |
| Apple         | MacBookPro11,1              | [3305f0e8ca](https://linux-hardware.org/?probe=3305f0e8ca) | Nov 15, 2023 |
| Dell          | Latitude E6540              | [6ee01afb58](https://linux-hardware.org/?probe=6ee01afb58) | Nov 15, 2023 |
| Notebook      | P9XXEN_EF_ED                | [9119b16d75](https://linux-hardware.org/?probe=9119b16d75) | Nov 15, 2023 |
| Notebook      | P9XXEN_EF_ED                | [ac5c2d0218](https://linux-hardware.org/?probe=ac5c2d0218) | Nov 15, 2023 |
| Acer          | TMP215-52-32DT              | [582fca0005](https://linux-hardware.org/?probe=582fca0005) | Nov 15, 2023 |
| ASUSTek       | UL80VT                      | [35735f2cbf](https://linux-hardware.org/?probe=35735f2cbf) | Nov 15, 2023 |
| Acer          | TMP215-52-32DT              | [1aec98605f](https://linux-hardware.org/?probe=1aec98605f) | Nov 15, 2023 |
| ASUSTek       | UL80VT                      | [e4eaf39f61](https://linux-hardware.org/?probe=e4eaf39f61) | Nov 15, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [a4bbeade58](https://linux-hardware.org/?probe=a4bbeade58) | Nov 15, 2023 |
| Dell          | Latitude 7310               | [8370505908](https://linux-hardware.org/?probe=8370505908) | Nov 15, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6ea69f0699](https://linux-hardware.org/?probe=6ea69f0699) | Nov 15, 2023 |
| Sony          | VGN-NS130AE                 | [7a70acb426](https://linux-hardware.org/?probe=7a70acb426) | Nov 15, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [9b2d42ff24](https://linux-hardware.org/?probe=9b2d42ff24) | Nov 15, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [f5413c3dd5](https://linux-hardware.org/?probe=f5413c3dd5) | Nov 15, 2023 |
| Jumper        | EZbook                      | [5623f4ec87](https://linux-hardware.org/?probe=5623f4ec87) | Nov 15, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [b89d3678bb](https://linux-hardware.org/?probe=b89d3678bb) | Nov 15, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [f4de613bd5](https://linux-hardware.org/?probe=f4de613bd5) | Nov 15, 2023 |
| ASUSTek       | K52Jr                       | [142c6a9c61](https://linux-hardware.org/?probe=142c6a9c61) | Nov 15, 2023 |
| Medion        | P8614                       | [42700378f9](https://linux-hardware.org/?probe=42700378f9) | Nov 15, 2023 |
| Dell          | Inspiron 3583               | [d014ceb833](https://linux-hardware.org/?probe=d014ceb833) | Nov 14, 2023 |
| Medion        | E6417 MD99252               | [4703096a9d](https://linux-hardware.org/?probe=4703096a9d) | Nov 14, 2023 |
| Dell          | Latitude E5540              | [75c5f17cf5](https://linux-hardware.org/?probe=75c5f17cf5) | Nov 14, 2023 |
| HP            | ProBook 440 G5              | [84acc862ff](https://linux-hardware.org/?probe=84acc862ff) | Nov 14, 2023 |
| HP            | ProBook 440 G5              | [c533e77f38](https://linux-hardware.org/?probe=c533e77f38) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [95a4f9ff42](https://linux-hardware.org/?probe=95a4f9ff42) | Nov 14, 2023 |
| HP            | Laptop 15-bs0xx             | [1606b9e027](https://linux-hardware.org/?probe=1606b9e027) | Nov 14, 2023 |
| MSI           | GF63 Thin 11SC              | [5fbfbad938](https://linux-hardware.org/?probe=5fbfbad938) | Nov 14, 2023 |
| MSI           | GF63 Thin 11SC              | [a6f59c7877](https://linux-hardware.org/?probe=a6f59c7877) | Nov 14, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4c653190f6](https://linux-hardware.org/?probe=4c653190f6) | Nov 14, 2023 |
| HP            | Laptop 15-da0xxx            | [e71274f9db](https://linux-hardware.org/?probe=e71274f9db) | Nov 14, 2023 |
| HP            | Compaq 15                   | [85c63bfd1e](https://linux-hardware.org/?probe=85c63bfd1e) | Nov 14, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7ae6ce2914](https://linux-hardware.org/?probe=7ae6ce2914) | Nov 14, 2023 |
| Sony          | SVF13N1L2ES                 | [e0b7ae1d8a](https://linux-hardware.org/?probe=e0b7ae1d8a) | Nov 14, 2023 |
| HP            | EliteBook 845 14 inch G9... | [33256c25e9](https://linux-hardware.org/?probe=33256c25e9) | Nov 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | [e0930f95d8](https://linux-hardware.org/?probe=e0930f95d8) | Nov 14, 2023 |
| Gateway       | P-7805u                     | [b613a7801b](https://linux-hardware.org/?probe=b613a7801b) | Nov 14, 2023 |
| Acer          | Nitro AN515-56              | [3ad9fc243a](https://linux-hardware.org/?probe=3ad9fc243a) | Nov 14, 2023 |
| Acer          | AOD255                      | [64aee07a6b](https://linux-hardware.org/?probe=64aee07a6b) | Nov 14, 2023 |
| Acer          | AOD255                      | [140fc27d54](https://linux-hardware.org/?probe=140fc27d54) | Nov 14, 2023 |
| Lenovo        | G40-70 20369                | [c103e79147](https://linux-hardware.org/?probe=c103e79147) | Nov 14, 2023 |
| Sony          | SVF13N1L2ES                 | [1fe409a47f](https://linux-hardware.org/?probe=1fe409a47f) | Nov 14, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [65712a4bc0](https://linux-hardware.org/?probe=65712a4bc0) | Nov 14, 2023 |
| HP            | EliteBook 840 14 inch G1... | [f4d839670e](https://linux-hardware.org/?probe=f4d839670e) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d95de7fccb](https://linux-hardware.org/?probe=d95de7fccb) | Nov 13, 2023 |
| HP            | EliteBook 2570p             | [133a963c15](https://linux-hardware.org/?probe=133a963c15) | Nov 13, 2023 |
| Acer          | Swift SF314-512             | [a1b5f65a73](https://linux-hardware.org/?probe=a1b5f65a73) | Nov 13, 2023 |
| Dell          | Vostro 3480                 | [4eae719332](https://linux-hardware.org/?probe=4eae719332) | Nov 13, 2023 |
| HP            | ENVY 15                     | [b8ee2c11e1](https://linux-hardware.org/?probe=b8ee2c11e1) | Nov 13, 2023 |
| ASUSTek       | K52Jr                       | [7e34d5b70b](https://linux-hardware.org/?probe=7e34d5b70b) | Nov 13, 2023 |
| Acer          | Aspire 4350                 | [32da8a19ac](https://linux-hardware.org/?probe=32da8a19ac) | Nov 13, 2023 |
| MSI           | Modern 14 C5M               | [94c27199a0](https://linux-hardware.org/?probe=94c27199a0) | Nov 13, 2023 |
| MSI           | Modern 14 C5M               | [808a76b01b](https://linux-hardware.org/?probe=808a76b01b) | Nov 13, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [2204427cc1](https://linux-hardware.org/?probe=2204427cc1) | Nov 13, 2023 |
| HP            | Pavilion m6                 | [60a4921f94](https://linux-hardware.org/?probe=60a4921f94) | Nov 13, 2023 |
| Dell          | Latitude E4310              | [85fad762d0](https://linux-hardware.org/?probe=85fad762d0) | Nov 13, 2023 |
| Dell          | Inspiron 14 5430            | [32082de399](https://linux-hardware.org/?probe=32082de399) | Nov 13, 2023 |
| Dell          | XPS 15 9520                 | [a8e7103aa2](https://linux-hardware.org/?probe=a8e7103aa2) | Nov 13, 2023 |
| Acer          | TravelMate 5730             | [accf863283](https://linux-hardware.org/?probe=accf863283) | Nov 13, 2023 |
| HONOR         | NBR-WAX9                    | [c648b2a80e](https://linux-hardware.org/?probe=c648b2a80e) | Nov 13, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [226af1608f](https://linux-hardware.org/?probe=226af1608f) | Nov 13, 2023 |
| Dell          | Latitude 5580               | [4343277d0b](https://linux-hardware.org/?probe=4343277d0b) | Nov 12, 2023 |
| HP            | Laptop 15-db0xxx            | [44aa818077](https://linux-hardware.org/?probe=44aa818077) | Nov 12, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [cd033cf790](https://linux-hardware.org/?probe=cd033cf790) | Nov 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [81dca17f20](https://linux-hardware.org/?probe=81dca17f20) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [e7f5173a86](https://linux-hardware.org/?probe=e7f5173a86) | Nov 12, 2023 |
| Toshiba       | Satellite C55t-A            | [22d791cf19](https://linux-hardware.org/?probe=22d791cf19) | Nov 12, 2023 |
| ASUSTek       | X556UR                      | [c4b344c176](https://linux-hardware.org/?probe=c4b344c176) | Nov 12, 2023 |
| HP            | Laptop 14-dq0xxx            | [f2123bd01c](https://linux-hardware.org/?probe=f2123bd01c) | Nov 12, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [1542535fcc](https://linux-hardware.org/?probe=1542535fcc) | Nov 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | [1bc14c9509](https://linux-hardware.org/?probe=1bc14c9509) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8b2e3f1f31](https://linux-hardware.org/?probe=8b2e3f1f31) | Nov 12, 2023 |
| Dell          | Inspiron 1545               | [b92eb60192](https://linux-hardware.org/?probe=b92eb60192) | Nov 12, 2023 |
| HP            | 255 G7 Notebook PC          | [5e137ad583](https://linux-hardware.org/?probe=5e137ad583) | Nov 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [001dd47e7d](https://linux-hardware.org/?probe=001dd47e7d) | Nov 12, 2023 |
| Acer          | Aspire 5750                 | [60981bc50d](https://linux-hardware.org/?probe=60981bc50d) | Nov 11, 2023 |
| Toshiba       | Satellite C650D             | [a49e05d0b8](https://linux-hardware.org/?probe=a49e05d0b8) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [5168262bbe](https://linux-hardware.org/?probe=5168262bbe) | Nov 11, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [f5f9243038](https://linux-hardware.org/?probe=f5f9243038) | Nov 11, 2023 |
| Acer          | Predator PT515-52           | [4f5c31bd64](https://linux-hardware.org/?probe=4f5c31bd64) | Nov 11, 2023 |
| Acer          | Predator PT515-52           | [ac3ab44d32](https://linux-hardware.org/?probe=ac3ab44d32) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E780               | [86e17547d2](https://linux-hardware.org/?probe=86e17547d2) | Nov 11, 2023 |
| Allview       | Allbook I/1                 | [2da284e5a6](https://linux-hardware.org/?probe=2da284e5a6) | Nov 11, 2023 |
| MSI           | Alpha 17 C7VG               | [99fa1e8cbd](https://linux-hardware.org/?probe=99fa1e8cbd) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4a32a91914](https://linux-hardware.org/?probe=4a32a91914) | Nov 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5fdbcfb950](https://linux-hardware.org/?probe=5fdbcfb950) | Nov 11, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [3f794fd46d](https://linux-hardware.org/?probe=3f794fd46d) | Nov 11, 2023 |
| Lenovo        | G50-30 80G0                 | [36d24b7c8b](https://linux-hardware.org/?probe=36d24b7c8b) | Nov 11, 2023 |
| ASUSTek       | X580VD                      | [81b80194be](https://linux-hardware.org/?probe=81b80194be) | Nov 10, 2023 |
| ASUSTek       | X580VD                      | [5dcc6790c2](https://linux-hardware.org/?probe=5dcc6790c2) | Nov 10, 2023 |
| Allview       | Allbook I/1                 | [4ea9038785](https://linux-hardware.org/?probe=4ea9038785) | Nov 10, 2023 |
| Sony          | VPCEB1S1E                   | [b0d4e06348](https://linux-hardware.org/?probe=b0d4e06348) | Nov 10, 2023 |
| Dynabook      | PORTEGE X30L-G              | [64326392ac](https://linux-hardware.org/?probe=64326392ac) | Nov 10, 2023 |
| Samsung       | R425D/R525D                 | [566985b28a](https://linux-hardware.org/?probe=566985b28a) | Nov 10, 2023 |
| HP            | Laptop 14-bs0xx             | [a6085bc08f](https://linux-hardware.org/?probe=a6085bc08f) | Nov 10, 2023 |
| Acer          | Nitro AN17-41               | [63911d68d6](https://linux-hardware.org/?probe=63911d68d6) | Nov 10, 2023 |
| HP            | Laptop 14-bs0xx             | [e8cbd8b1b9](https://linux-hardware.org/?probe=e8cbd8b1b9) | Nov 10, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [dc40a2bbb1](https://linux-hardware.org/?probe=dc40a2bbb1) | Nov 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ad64dd8d76](https://linux-hardware.org/?probe=ad64dd8d76) | Nov 10, 2023 |
| HP            | Pavilion Notebook           | [164a2ae911](https://linux-hardware.org/?probe=164a2ae911) | Nov 10, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [1cda9633ce](https://linux-hardware.org/?probe=1cda9633ce) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [139e9d8e09](https://linux-hardware.org/?probe=139e9d8e09) | Nov 10, 2023 |
| ASUSTek       | N53SN                       | [0f6145e565](https://linux-hardware.org/?probe=0f6145e565) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [7ffe26a7bc](https://linux-hardware.org/?probe=7ffe26a7bc) | Nov 10, 2023 |
| Dell          | XPS 13 9370                 | [dadc0b1102](https://linux-hardware.org/?probe=dadc0b1102) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [1284e15df1](https://linux-hardware.org/?probe=1284e15df1) | Nov 10, 2023 |
| Pegatron      | Deepcam                     | [5bf6bdb719](https://linux-hardware.org/?probe=5bf6bdb719) | Nov 09, 2023 |
| ASUSTek       | N56VZ                       | [44d4fd8a09](https://linux-hardware.org/?probe=44d4fd8a09) | Nov 09, 2023 |
| HP            | Laptop 15-da2xxx            | [d38ccb16c4](https://linux-hardware.org/?probe=d38ccb16c4) | Nov 09, 2023 |
| HP            | Laptop 15-da2xxx            | [f6d111d4d4](https://linux-hardware.org/?probe=f6d111d4d4) | Nov 09, 2023 |
| HP            | ProBook 6460b               | [1f7edfc832](https://linux-hardware.org/?probe=1f7edfc832) | Nov 09, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HS_... | [b845aeef55](https://linux-hardware.org/?probe=b845aeef55) | Nov 09, 2023 |
| HP            | Pavilion Notebook           | [b0e940c986](https://linux-hardware.org/?probe=b0e940c986) | Nov 09, 2023 |
| Fujitsu Si... | LIFEBOOK S7220              | [52f980a58c](https://linux-hardware.org/?probe=52f980a58c) | Nov 09, 2023 |
| LG Electro... | 15Z90RT-G.AD75B             | [2ec6124055](https://linux-hardware.org/?probe=2ec6124055) | Nov 09, 2023 |
| HP            | Pavilion Notebook           | [6f78578b19](https://linux-hardware.org/?probe=6f78578b19) | Nov 09, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5cf379008d](https://linux-hardware.org/?probe=5cf379008d) | Nov 08, 2023 |
| HP            | ProBook 4530s               | [5a82c400aa](https://linux-hardware.org/?probe=5a82c400aa) | Nov 08, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [5792e73603](https://linux-hardware.org/?probe=5792e73603) | Nov 08, 2023 |
| HP            | Notebook                    | [28b2b3c585](https://linux-hardware.org/?probe=28b2b3c585) | Nov 08, 2023 |
| HP            | Notebook                    | [8881671430](https://linux-hardware.org/?probe=8881671430) | Nov 08, 2023 |
| MSI           | Modern 14 C12MO             | [61aae729b5](https://linux-hardware.org/?probe=61aae729b5) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JLC... | [d44b69e61b](https://linux-hardware.org/?probe=d44b69e61b) | Nov 08, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | [4b9f31e3e0](https://linux-hardware.org/?probe=4b9f31e3e0) | Nov 08, 2023 |
| Dell          | Latitude 5430               | [e7df6855a7](https://linux-hardware.org/?probe=e7df6855a7) | Nov 08, 2023 |
| Medion        | P6613                       | [549455ad75](https://linux-hardware.org/?probe=549455ad75) | Nov 08, 2023 |
| Medion        | P6613                       | [ad65262643](https://linux-hardware.org/?probe=ad65262643) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | [25fd8cabab](https://linux-hardware.org/?probe=25fd8cabab) | Nov 08, 2023 |
| Toshiba       | Satellite A300              | [3845af142b](https://linux-hardware.org/?probe=3845af142b) | Nov 08, 2023 |
| Dell          | Latitude 5490               | [ac938f1435](https://linux-hardware.org/?probe=ac938f1435) | Nov 08, 2023 |
| Dell          | Latitude E7440              | [31b059f91b](https://linux-hardware.org/?probe=31b059f91b) | Nov 08, 2023 |
| Acer          | Aspire F5-573G              | [00b9675b99](https://linux-hardware.org/?probe=00b9675b99) | Nov 08, 2023 |
| Unknown       | Unknown                     | [526930f6aa](https://linux-hardware.org/?probe=526930f6aa) | Nov 08, 2023 |
| Google        | Barla                       | [5abf75595d](https://linux-hardware.org/?probe=5abf75595d) | Nov 08, 2023 |
| Google        | Barla                       | [bb1f6ed257](https://linux-hardware.org/?probe=bb1f6ed257) | Nov 08, 2023 |
| Acer          | Nitro AN515-46              | [69541ca76a](https://linux-hardware.org/?probe=69541ca76a) | Nov 07, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [216e0bed29](https://linux-hardware.org/?probe=216e0bed29) | Nov 07, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [e65bfd3de3](https://linux-hardware.org/?probe=e65bfd3de3) | Nov 07, 2023 |
| ASUSTek       | K501UW                      | [54d6d39995](https://linux-hardware.org/?probe=54d6d39995) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | [c88fd34c8f](https://linux-hardware.org/?probe=c88fd34c8f) | Nov 07, 2023 |
| ASUSTek       | N71Jq                       | [680e4d8cc9](https://linux-hardware.org/?probe=680e4d8cc9) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [be7a52191a](https://linux-hardware.org/?probe=be7a52191a) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [6ec54b38a2](https://linux-hardware.org/?probe=6ec54b38a2) | Nov 07, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [220d14894a](https://linux-hardware.org/?probe=220d14894a) | Nov 07, 2023 |
| Dell          | Latitude E4310              | [57d2a2984f](https://linux-hardware.org/?probe=57d2a2984f) | Nov 07, 2023 |
| HUAWEI        | BOHB-WAX9                   | [9964a0a9f1](https://linux-hardware.org/?probe=9964a0a9f1) | Nov 07, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XJ... | [5756bdb835](https://linux-hardware.org/?probe=5756bdb835) | Nov 07, 2023 |
| Dell          | Latitude 5540               | [9ff5e6f1e6](https://linux-hardware.org/?probe=9ff5e6f1e6) | Nov 07, 2023 |
| Lenovo        | ThinkPad X240 20AMS7X300    | [e87e6bdcfc](https://linux-hardware.org/?probe=e87e6bdcfc) | Nov 07, 2023 |
| Lenovo        | ThinkPad X230 23259T0       | [bc52f6064a](https://linux-hardware.org/?probe=bc52f6064a) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [18a292fb51](https://linux-hardware.org/?probe=18a292fb51) | Nov 07, 2023 |
| HP            | Laptop 17-bs0xx             | [2887cb4781](https://linux-hardware.org/?probe=2887cb4781) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [996538af0c](https://linux-hardware.org/?probe=996538af0c) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | [8ee0ec30d3](https://linux-hardware.org/?probe=8ee0ec30d3) | Nov 06, 2023 |
| MSI           | Alpha 17 C7VG               | [6ac34aa88a](https://linux-hardware.org/?probe=6ac34aa88a) | Nov 06, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d33b9781b7](https://linux-hardware.org/?probe=d33b9781b7) | Nov 06, 2023 |
| Lenovo        | ThinkPad T420 4236NHG       | [6db239877b](https://linux-hardware.org/?probe=6db239877b) | Nov 06, 2023 |
| Inferit       | E-Note                      | [ab14e435d4](https://linux-hardware.org/?probe=ab14e435d4) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [3cd8e36ab1](https://linux-hardware.org/?probe=3cd8e36ab1) | Nov 06, 2023 |
| Dell          | Latitude 5590               | [0290e5fd1a](https://linux-hardware.org/?probe=0290e5fd1a) | Nov 06, 2023 |
| HP            | EliteBook 840 G5            | [279ac4ed92](https://linux-hardware.org/?probe=279ac4ed92) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [10f2785958](https://linux-hardware.org/?probe=10f2785958) | Nov 06, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0HB0... | [95376bfed1](https://linux-hardware.org/?probe=95376bfed1) | Nov 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2430... | [658d6f150e](https://linux-hardware.org/?probe=658d6f150e) | Nov 05, 2023 |
| Dell          | Latitude 5590               | [913308d97b](https://linux-hardware.org/?probe=913308d97b) | Nov 05, 2023 |
| Toshiba       | PORTEGE Z10t-A              | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | [27923cd021](https://linux-hardware.org/?probe=27923cd021) | Nov 05, 2023 |
| ASUSTek       | K401UB                      | [3bc894aa34](https://linux-hardware.org/?probe=3bc894aa34) | Nov 05, 2023 |
| Dell          | Latitude E6400              | [c5f0762ae5](https://linux-hardware.org/?probe=c5f0762ae5) | Nov 05, 2023 |
| HP            | ProBook 4740s               | [2efc1092dd](https://linux-hardware.org/?probe=2efc1092dd) | Nov 05, 2023 |
| HP            | ProBook 4740s               | [0351f35099](https://linux-hardware.org/?probe=0351f35099) | Nov 05, 2023 |
| Acer          | Aspire ES1-311              | [d06185f74c](https://linux-hardware.org/?probe=d06185f74c) | Nov 05, 2023 |
| HP            | 250 G5 Notebook PC          | [7b281cb925](https://linux-hardware.org/?probe=7b281cb925) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ae9fcece31](https://linux-hardware.org/?probe=ae9fcece31) | Nov 05, 2023 |
| ASUSTek       | K55VJ                       | [47851a05e9](https://linux-hardware.org/?probe=47851a05e9) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [fd9594de89](https://linux-hardware.org/?probe=fd9594de89) | Nov 05, 2023 |
| Google        | Pyro                        | [2fd8f11a53](https://linux-hardware.org/?probe=2fd8f11a53) | Nov 05, 2023 |
| ASUSTek       | X756UVK                     | [3ba2cc1e0c](https://linux-hardware.org/?probe=3ba2cc1e0c) | Nov 05, 2023 |
| Apple         | MacBookAir7,1               | [23e52fc4f5](https://linux-hardware.org/?probe=23e52fc4f5) | Nov 05, 2023 |
| Lenovo        | ThinkPad E580 20KS003QUS    | [6bccd355f7](https://linux-hardware.org/?probe=6bccd355f7) | Nov 05, 2023 |
| Medion        | E6417 MD99252               | [8660ae1c16](https://linux-hardware.org/?probe=8660ae1c16) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [a5a8cf5c09](https://linux-hardware.org/?probe=a5a8cf5c09) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [74099b3a6e](https://linux-hardware.org/?probe=74099b3a6e) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [bdad71bf99](https://linux-hardware.org/?probe=bdad71bf99) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [7a8597dd50](https://linux-hardware.org/?probe=7a8597dd50) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | [124c666940](https://linux-hardware.org/?probe=124c666940) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | [9eeeda059e](https://linux-hardware.org/?probe=9eeeda059e) | Nov 05, 2023 |
| Acer          | Aspire A517-51G             | [11f85eb258](https://linux-hardware.org/?probe=11f85eb258) | Nov 04, 2023 |
| Acer          | Aspire 7750G                | [ddf88ff37c](https://linux-hardware.org/?probe=ddf88ff37c) | Nov 04, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [dc13d6012b](https://linux-hardware.org/?probe=dc13d6012b) | Nov 04, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [5b7dc65a39](https://linux-hardware.org/?probe=5b7dc65a39) | Nov 04, 2023 |
| Acer          | TravelMate B118-M           | [051346666e](https://linux-hardware.org/?probe=051346666e) | Nov 04, 2023 |
| Acer          | TravelMate P215-54          | [5688b7940d](https://linux-hardware.org/?probe=5688b7940d) | Nov 04, 2023 |
| Lenovo        | ThinkPad T550 20CJS07P01    | [52157a4ee8](https://linux-hardware.org/?probe=52157a4ee8) | Nov 04, 2023 |
| Acer          | TravelMate P215-54          | [f051dc617c](https://linux-hardware.org/?probe=f051dc617c) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [aba7da7a37](https://linux-hardware.org/?probe=aba7da7a37) | Nov 04, 2023 |
| HP            | 15                          | [5d5fb36764](https://linux-hardware.org/?probe=5d5fb36764) | Nov 04, 2023 |
| Dell          | Latitude E6420              | [6bd73f2b0e](https://linux-hardware.org/?probe=6bd73f2b0e) | Nov 04, 2023 |
| HP            | EliteBook 840 G6            | [d4b22ac16a](https://linux-hardware.org/?probe=d4b22ac16a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [1d51aba71e](https://linux-hardware.org/?probe=1d51aba71e) | Nov 04, 2023 |
| HP            | ZBook Studio G3             | [eb90a23afa](https://linux-hardware.org/?probe=eb90a23afa) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | [585906fa27](https://linux-hardware.org/?probe=585906fa27) | Nov 04, 2023 |
| American M... | A6                          | [4ff43d7d31](https://linux-hardware.org/?probe=4ff43d7d31) | Nov 04, 2023 |
| Acer          | Aspire A314-23P             | [1e3cdf0bf2](https://linux-hardware.org/?probe=1e3cdf0bf2) | Nov 04, 2023 |
| Dell          | XPS 15 7590                 | [8685e384af](https://linux-hardware.org/?probe=8685e384af) | Nov 04, 2023 |
| Dell          | Inspiron N4010              | [f8aed4abab](https://linux-hardware.org/?probe=f8aed4abab) | Nov 03, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [de4c3bfe46](https://linux-hardware.org/?probe=de4c3bfe46) | Nov 03, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0960... | [10407542ab](https://linux-hardware.org/?probe=10407542ab) | Nov 03, 2023 |
| Lenovo        | B560 433028U                | [37a6693c3d](https://linux-hardware.org/?probe=37a6693c3d) | Nov 03, 2023 |
| HUAWEI        | MRGFG-XX                    | [5117a849b3](https://linux-hardware.org/?probe=5117a849b3) | Nov 03, 2023 |
| HUAWEI        | HLYL-WXX9                   | [993a2b9f3e](https://linux-hardware.org/?probe=993a2b9f3e) | Nov 03, 2023 |
| Medion        | ERAZER X7855 MD60892        | [b34c69b29d](https://linux-hardware.org/?probe=b34c69b29d) | Nov 03, 2023 |
| Dell          | Latitude E5570              | [a4617a2ea3](https://linux-hardware.org/?probe=a4617a2ea3) | Nov 03, 2023 |
| Dell          | Precision 5750              | [00e8468779](https://linux-hardware.org/?probe=00e8468779) | Nov 03, 2023 |
| Dell          | Latitude E5570              | [82d66aaaf1](https://linux-hardware.org/?probe=82d66aaaf1) | Nov 03, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [fca8401d97](https://linux-hardware.org/?probe=fca8401d97) | Nov 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | [5ff77430fa](https://linux-hardware.org/?probe=5ff77430fa) | Nov 03, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 423       | 5.07%   |
| 6.2.0-26-generic  | 389       | 4.67%   |
| 5.15.0-52-generic | 375       | 4.5%    |
| 5.15.0-58-generic | 346       | 4.15%   |
| 5.19.0-32-generic | 318       | 3.81%   |
| 5.15.0-43-generic | 297       | 3.56%   |
| 5.15.0-48-generic | 292       | 3.5%    |
| 5.19.0-35-generic | 279       | 3.35%   |
| 5.15.0-47-generic | 254       | 3.05%   |
| 5.19.0-41-generic | 239       | 2.87%   |
| 6.2.0-37-generic  | 238       | 2.85%   |
| 5.15.0-46-generic | 235       | 2.82%   |
| 6.2.0-36-generic  | 228       | 2.73%   |
| 5.19.0-46-generic | 228       | 2.73%   |
| 5.15.0-53-generic | 212       | 2.54%   |
| 6.2.0-34-generic  | 208       | 2.49%   |
| 5.19.0-38-generic | 199       | 2.39%   |
| 5.15.0-25-generic | 193       | 2.31%   |
| 6.2.0-33-generic  | 183       | 2.19%   |
| 5.15.0-27-generic | 175       | 2.1%    |
| 6.2.0-32-generic  | 169       | 2.03%   |
| 6.2.0-39-generic  | 167       | 2%      |
| 5.15.0-41-generic | 167       | 2%      |
| 5.19.0-43-generic | 158       | 1.89%   |
| 5.15.0-40-generic | 157       | 1.88%   |
| 6.2.0-35-generic  | 147       | 1.76%   |
| 5.15.0-50-generic | 145       | 1.74%   |
| 5.15.0-60-generic | 128       | 1.54%   |
| 5.19.0-45-generic | 115       | 1.38%   |
| 5.15.0-33-generic | 108       | 1.3%    |
| 5.15.0-57-generic | 103       | 1.24%   |
| 5.19.0-50-generic | 93        | 1.12%   |
| 5.19.0-40-generic | 90        | 1.08%   |
| 5.15.0-30-generic | 87        | 1.04%   |
| 5.19.0-42-generic | 75        | 0.9%    |
| 5.15.0-39-generic | 74        | 0.89%   |
| 6.2.0-31-generic  | 72        | 0.86%   |
| 5.15.0-37-generic | 57        | 0.68%   |
| 5.15.0-35-generic | 46        | 0.55%   |
| 5.15.0-71-generic | 29        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 3984      | 50.7%   |
| 6.2.0   | 1731      | 22.03%  |
| 5.19.0  | 1718      | 21.86%  |
| 5.17.0  | 64        | 0.81%   |
| 6.1.0   | 36        | 0.46%   |
| 5.14.0  | 34        | 0.43%   |
| 6.5.0   | 26        | 0.33%   |
| 6.0.0   | 21        | 0.27%   |
| 5.13.0  | 15        | 0.19%   |
| 5.18.0  | 9         | 0.11%   |
| 6.4.0   | 8         | 0.1%    |
| 6.2.11  | 8         | 0.1%    |
| 6.3.1   | 7         | 0.09%   |
| 5.19.5  | 7         | 0.09%   |
| 5.17.1  | 7         | 0.09%   |
| 6.2.2   | 6         | 0.08%   |
| 6.0.9   | 6         | 0.08%   |
| 6.2.8   | 5         | 0.06%   |
| 5.17.5  | 5         | 0.06%   |
| 6.6.0   | 4         | 0.05%   |
| 6.4.11  | 4         | 0.05%   |
| 6.4.10  | 4         | 0.05%   |
| 6.2.10  | 4         | 0.05%   |
| 6.0.6   | 4         | 0.05%   |
| 5.4.0   | 4         | 0.05%   |
| 5.13.19 | 4         | 0.05%   |
| 6.5.1   | 3         | 0.04%   |
| 6.4.6   | 3         | 0.04%   |
| 6.3.3   | 3         | 0.04%   |
| 6.2.9   | 3         | 0.04%   |
| 6.2.6   | 3         | 0.04%   |
| 6.2.1   | 3         | 0.04%   |
| 6.1.12  | 3         | 0.04%   |
| 5.18.8  | 3         | 0.04%   |
| 5.17.9  | 3         | 0.04%   |
| 5.17.8  | 3         | 0.04%   |
| 5.17.2  | 3         | 0.04%   |
| 5.16.0  | 3         | 0.04%   |
| 6.5.8   | 2         | 0.03%   |
| 6.5.7   | 2         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 3999      | 50.93%  |
| 6.2     | 1768      | 22.52%  |
| 5.19    | 1733      | 22.07%  |
| 5.17    | 92        | 1.17%   |
| 6.1     | 49        | 0.62%   |
| 6.0     | 39        | 0.5%    |
| 6.5     | 38        | 0.48%   |
| 5.14    | 34        | 0.43%   |
| 5.18    | 25        | 0.32%   |
| 6.4     | 23        | 0.29%   |
| 5.13    | 19        | 0.24%   |
| 6.3     | 14        | 0.18%   |
| 6.6     | 5         | 0.06%   |
| 5.16    | 5         | 0.06%   |
| 5.4     | 4         | 0.05%   |
| 5.11    | 2         | 0.03%   |
| 6       | 1         | 0.01%   |
| 5.8     | 1         | 0.01%   |
| 5.10    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7507      | 99.99%  |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 7234      | 96.15%  |
| Unknown           | 148       | 1.97%   |
| X-Cinnamon        | 54        | 0.72%   |
| GNOME Flashback   | 36        | 0.48%   |
| i3                | 15        | 0.2%    |
| GNOME Classic     | 7         | 0.09%   |
| Enlightenment     | 6         | 0.08%   |
| sway              | 5         | 0.07%   |
| Cinnamon          | 5         | 0.07%   |
| awesome           | 4         | 0.05%   |
| DWM               | 2         | 0.03%   |
| Yaru:ubuntu:GNOME | 1         | 0.01%   |
| xsession          | 1         | 0.01%   |
| ratflow           | 1         | 0.01%   |
| Pantheon          | 1         | 0.01%   |
| openbox           | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| GNUstep           | 1         | 0.01%   |
| fluxbox           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 5227      | 68.4%   |
| X11     | 2217      | 29.01%  |
| Unknown | 148       | 1.94%   |
| Tty     | 50        | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 6967      | 92.4%   |
| Unknown | 412       | 5.46%   |
| LightDM | 101       | 1.34%   |
| GDM     | 29        | 0.38%   |
| SDDM    | 25        | 0.33%   |
| SLiM    | 5         | 0.07%   |
| XDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3472      | 46.08%  |
| de_DE   | 576       | 7.64%   |
| fr_FR   | 470       | 6.24%   |
| en_GB   | 353       | 4.68%   |
| pt_BR   | 298       | 3.95%   |
| en_IN   | 269       | 3.57%   |
| it_IT   | 250       | 3.32%   |
| ru_RU   | 225       | 2.99%   |
| es_ES   | 200       | 2.65%   |
| en_CA   | 155       | 2.06%   |
| pl_PL   | 107       | 1.42%   |
| en_AU   | 87        | 1.15%   |
| nl_NL   | 73        | 0.97%   |
| zh_CN   | 64        | 0.85%   |
| Unknown | 63        | 0.84%   |
| es_MX   | 57        | 0.76%   |
| hu_HU   | 52        | 0.69%   |
| C       | 45        | 0.6%    |
| en_ZA   | 43        | 0.57%   |
| es_AR   | 41        | 0.54%   |
| cs_CZ   | 40        | 0.53%   |
| pt_PT   | 38        | 0.5%    |
| tr_TR   | 36        | 0.48%   |
| sv_SE   | 33        | 0.44%   |
| es_CO   | 29        | 0.38%   |
| de_AT   | 27        | 0.36%   |
| en_PH   | 26        | 0.35%   |
| de_CH   | 21        | 0.28%   |
| fi_FI   | 20        | 0.27%   |
| en_IL   | 19        | 0.25%   |
| da_DK   | 19        | 0.25%   |
| fr_BE   | 18        | 0.24%   |
| en_NZ   | 18        | 0.24%   |
| ja_JP   | 17        | 0.23%   |
| es_CL   | 17        | 0.23%   |
| nb_NO   | 16        | 0.21%   |
| ko_KR   | 14        | 0.19%   |
| ro_RO   | 13        | 0.17%   |
| en_IE   | 13        | 0.17%   |
| el_GR   | 13        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 4100      | 53.88%  |
| EFI  | 3509      | 46.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 5774      | 75.11%  |
| Tmpfs   | 1486      | 19.33%  |
| Overlay | 191       | 2.48%   |
| Zfs     | 154       | 2%      |
| Btrfs   | 54        | 0.7%    |
| Xfs     | 11        | 0.14%   |
| Ext3    | 8         | 0.1%    |
| Ext2    | 8         | 0.1%    |
| XXX4    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 5737      | 75.34%  |
| Unknown | 1317      | 17.29%  |
| MBR     | 561       | 7.37%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6963      | 92.12%  |
| Yes       | 596       | 7.88%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4844      | 64.06%  |
| Yes       | 2718      | 35.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1522      | 20.27%  |
| Hewlett-Packard        | 1364      | 18.17%  |
| Dell                   | 1285      | 17.12%  |
| ASUSTek Computer       | 823       | 10.96%  |
| Acer                   | 595       | 7.92%   |
| Apple                  | 228       | 3.04%   |
| MSI                    | 204       | 2.72%   |
| HUAWEI                 | 190       | 2.53%   |
| Toshiba                | 157       | 2.09%   |
| Samsung Electronics    | 114       | 1.52%   |
| Sony                   | 74        | 0.99%   |
| Notebook               | 64        | 0.85%   |
| Google                 | 59        | 0.79%   |
| Unknown                | 58        | 0.77%   |
| Fujitsu                | 53        | 0.71%   |
| Timi                   | 48        | 0.64%   |
| Medion                 | 39        | 0.52%   |
| Alienware              | 38        | 0.51%   |
| Positivo               | 26        | 0.35%   |
| Packard Bell           | 25        | 0.33%   |
| Chuwi                  | 25        | 0.33%   |
| LG Electronics         | 24        | 0.32%   |
| TUXEDO                 | 22        | 0.29%   |
| Framework              | 18        | 0.24%   |
| HONOR                  | 17        | 0.23%   |
| System76               | 16        | 0.21%   |
| Panasonic              | 16        | 0.21%   |
| Gigabyte Technology    | 16        | 0.21%   |
| Gateway                | 16        | 0.21%   |
| Avell High Performance | 14        | 0.19%   |
| Razer                  | 13        | 0.17%   |
| Teclast                | 12        | 0.16%   |
| GPU Company            | 11        | 0.15%   |
| Schenker               | 10        | 0.13%   |
| Dynabook               | 8         | 0.11%   |
| AZW                    | 8         | 0.11%   |
| AMI                    | 8         | 0.11%   |
| UNOWHY                 | 7         | 0.09%   |
| PC Specialist          | 7         | 0.09%   |
| Monster                | 7         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 79        | 1.05%   |
| HP Notebook                     | 44        | 0.59%   |
| HP Pavilion Notebook            | 23        | 0.31%   |
| HP Pavilion 15                  | 22        | 0.29%   |
| Dell Latitude 5420              | 21        | 0.28%   |
| HUAWEI BOM-WXX9                 | 20        | 0.27%   |
| HP Pavilion dv6                 | 20        | 0.27%   |
| HP Pavilion g6                  | 19        | 0.25%   |
| HP 15                           | 19        | 0.25%   |
| Dell XPS 15 9520                | 19        | 0.25%   |
| HUAWEI NBLB-WAX9N               | 18        | 0.24%   |
| HUAWEI BOD-WXX9                 | 18        | 0.24%   |
| HP EliteBook 840 G3             | 18        | 0.24%   |
| HUAWEI HVY-WXX9                 | 17        | 0.23%   |
| HP Pavilion dv7                 | 17        | 0.23%   |
| HP EliteBook 840 G8 Notebook PC | 17        | 0.23%   |
| HP EliteBook 840 G5             | 17        | 0.23%   |
| Dell XPS 15 9500                | 17        | 0.23%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 16        | 0.21%   |
| Dell XPS 15 7590                | 16        | 0.21%   |
| HUAWEI BOHB-WAX9                | 15        | 0.2%    |
| Dell XPS 13 9370                | 15        | 0.2%    |
| Dell Latitude E6420             | 15        | 0.2%    |
| Acer Aspire E5-571              | 15        | 0.2%    |
| HP EliteBook 8470p              | 14        | 0.19%   |
| Dell XPS 15 9570                | 14        | 0.19%   |
| Apple MacBookPro9,2             | 14        | 0.19%   |
| HUAWEI NBLK-WAX9X               | 13        | 0.17%   |
| HP Laptop 15-db0xxx             | 13        | 0.17%   |
| Dell XPS 9320                   | 13        | 0.17%   |
| Dell XPS 13 9380                | 13        | 0.17%   |
| Dell Vostro 3500                | 13        | 0.17%   |
| Apple MacBookPro8,1             | 13        | 0.17%   |
| HP Pavilion g7                  | 12        | 0.16%   |
| HP EliteBook 8460p              | 12        | 0.16%   |
| Apple MacBookPro8,2             | 12        | 0.16%   |
| Lenovo ThinkBook 15 G3 ACL 21A4 | 11        | 0.15%   |
| HP ProBook 650 G1               | 11        | 0.15%   |
| HP ProBook 450 G8 Notebook PC   | 11        | 0.15%   |
| HP Pavilion 17                  | 11        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 751       | 10%     |
| Dell Latitude         | 465       | 6.19%   |
| Acer Aspire           | 400       | 5.33%   |
| Lenovo IdeaPad        | 374       | 4.98%   |
| Dell Inspiron         | 323       | 4.3%    |
| HP Pavilion           | 278       | 3.7%    |
| HP EliteBook          | 266       | 3.54%   |
| ASUS VivoBook         | 238       | 3.17%   |
| HP ProBook            | 201       | 2.68%   |
| Dell XPS              | 195       | 2.6%    |
| HP Laptop             | 190       | 2.53%   |
| Toshiba Satellite     | 126       | 1.68%   |
| Dell Precision        | 126       | 1.68%   |
| Dell Vostro           | 97        | 1.29%   |
| Lenovo ThinkBook      | 85        | 1.13%   |
| Lenovo Legion         | 84        | 1.12%   |
| ASUS Zenbook          | 84        | 1.12%   |
| ASUS ROG              | 80        | 1.07%   |
| Unknown               | 79        | 1.05%   |
| HP ZBook              | 73        | 0.97%   |
| ASUS ASUS             | 64        | 0.85%   |
| Acer Swift            | 61        | 0.81%   |
| Acer Nitro            | 58        | 0.77%   |
| HP ENVY               | 52        | 0.69%   |
| HP Notebook           | 45        | 0.6%    |
| Fujitsu LIFEBOOK      | 45        | 0.6%    |
| HP OMEN               | 34        | 0.45%   |
| Dell G15              | 32        | 0.43%   |
| Lenovo Yoga           | 31        | 0.41%   |
| HP 255                | 31        | 0.41%   |
| HP 250                | 30        | 0.4%    |
| Apple MacBookPro11    | 27        | 0.36%   |
| HP Compaq             | 26        | 0.35%   |
| Apple MacBookPro8     | 26        | 0.35%   |
| HP 15                 | 25        | 0.33%   |
| Acer TravelMate       | 24        | 0.32%   |
| MSI Modern            | 23        | 0.31%   |
| Packard Bell EasyNote | 22        | 0.29%   |
| MSI Katana            | 22        | 0.29%   |
| ASUS TUF              | 21        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 1126      | 15%     |
| 2020    | 851       | 11.33%  |
| 2022    | 686       | 9.14%   |
| 2019    | 631       | 8.4%    |
| 2018    | 538       | 7.17%   |
| 2013    | 474       | 6.31%   |
| 2012    | 447       | 5.95%   |
| 2017    | 431       | 5.74%   |
| 2011    | 420       | 5.59%   |
| 2014    | 364       | 4.85%   |
| 2016    | 335       | 4.46%   |
| 2015    | 332       | 4.42%   |
| 2010    | 282       | 3.76%   |
| 2023    | 221       | 2.94%   |
| 2008    | 149       | 1.98%   |
| 2009    | 136       | 1.81%   |
| 2007    | 61        | 0.81%   |
| 2006    | 17        | 0.23%   |
| Unknown | 7         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7508      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6479      | 85.69%  |
| Enabled  | 1082      | 14.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7435      | 99.03%  |
| Yes  | 73        | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2273      | 30.12%  |
| 16.01-24.0  | 1618      | 21.44%  |
| 8.01-16.0   | 1287      | 17.06%  |
| 3.01-4.0    | 1209      | 16.02%  |
| 32.01-64.0  | 700       | 9.28%   |
| 64.01-256.0 | 130       | 1.72%   |
| 1.01-2.0    | 130       | 1.72%   |
| 24.01-32.0  | 128       | 1.7%    |
| 2.01-3.0    | 68        | 0.9%    |
| 0.51-1.0    | 3         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 2505      | 31.53%  |
| 1.01-2.0   | 2088      | 26.28%  |
| 4.01-8.0   | 1471      | 18.51%  |
| 3.01-4.0   | 1348      | 16.96%  |
| 8.01-16.0  | 409       | 5.15%   |
| 0.51-1.0   | 53        | 0.67%   |
| 16.01-24.0 | 46        | 0.58%   |
| 24.01-32.0 | 15        | 0.19%   |
| 32.01-64.0 | 6         | 0.08%   |
| 0.01-0.5   | 5         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5832      | 76.96%  |
| 2      | 1541      | 20.34%  |
| 3      | 132       | 1.74%   |
| 0      | 49        | 0.65%   |
| 4      | 19        | 0.25%   |
| 5      | 3         | 0.04%   |
| 7      | 2         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5460      | 72.53%  |
| Yes       | 2068      | 27.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5655      | 75.1%   |
| No        | 1875      | 24.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7396      | 98.47%  |
| No        | 115       | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6278      | 83.04%  |
| No        | 1282      | 16.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1122      | 14.88%  |
| Germany      | 767       | 10.17%  |
| France       | 568       | 7.53%   |
| Brazil       | 414       | 5.49%   |
| Italy        | 372       | 4.93%   |
| Russia       | 317       | 4.2%    |
| India        | 303       | 4.02%   |
| UK           | 284       | 3.77%   |
| Spain        | 257       | 3.41%   |
| Poland       | 206       | 2.73%   |
| Canada       | 185       | 2.45%   |
| Netherlands  | 180       | 2.39%   |
| Mexico       | 115       | 1.52%   |
| Turkey       | 108       | 1.43%   |
| Sweden       | 91        | 1.21%   |
| Hungary      | 88        | 1.17%   |
| Australia    | 85        | 1.13%   |
| Argentina    | 82        | 1.09%   |
| Czechia      | 78        | 1.03%   |
| Portugal     | 77        | 1.02%   |
| China        | 76        | 1.01%   |
| Belgium      | 75        | 0.99%   |
| Switzerland  | 73        | 0.97%   |
| Romania      | 71        | 0.94%   |
| Austria      | 65        | 0.86%   |
| Indonesia    | 58        | 0.77%   |
| Greece       | 54        | 0.72%   |
| Colombia     | 54        | 0.72%   |
| Finland      | 47        | 0.62%   |
| South Africa | 45        | 0.6%    |
| Denmark      | 42        | 0.56%   |
| Bulgaria     | 42        | 0.56%   |
| Egypt        | 41        | 0.54%   |
| Norway       | 40        | 0.53%   |
| Iran         | 39        | 0.52%   |
| Chile        | 37        | 0.49%   |
| Pakistan     | 35        | 0.46%   |
| Japan        | 34        | 0.45%   |
| Vietnam      | 33        | 0.44%   |
| Philippines  | 32        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 94        | 1.2%    |
| Moscow            | 87        | 1.11%   |
| Berlin            | 82        | 1.05%   |
| Milan             | 64        | 0.82%   |
| St Petersburg     | 54        | 0.69%   |
| Warsaw            | 53        | 0.68%   |
| Rome              | 53        | 0.68%   |
| Madrid            | 51        | 0.65%   |
| Sao Paulo         | 49        | 0.63%   |
| Budapest          | 46        | 0.59%   |
| Barcelona         | 41        | 0.52%   |
| Vienna            | 39        | 0.5%    |
| Istanbul          | 39        | 0.5%    |
| Bengaluru         | 37        | 0.47%   |
| Munich            | 34        | 0.43%   |
| Prague            | 31        | 0.4%    |
| Rio de Janeiro    | 30        | 0.38%   |
| Amsterdam         | 30        | 0.38%   |
| Toronto           | 28        | 0.36%   |
| London            | 28        | 0.36%   |
| Helsinki          | 28        | 0.36%   |
| Hamburg           | 28        | 0.36%   |
| Athens            | 27        | 0.34%   |
| Sydney            | 26        | 0.33%   |
| Nairobi           | 26        | 0.33%   |
| Chennai           | 26        | 0.33%   |
| Tehran            | 25        | 0.32%   |
| Melbourne         | 25        | 0.32%   |
| Los Angeles       | 25        | 0.32%   |
| Frankfurt am Main | 25        | 0.32%   |
| Sofia             | 24        | 0.31%   |
| New York          | 24        | 0.31%   |
| Mexico City       | 24        | 0.31%   |
| Delhi             | 24        | 0.31%   |
| Bogotá           | 23        | 0.29%   |
| Denver            | 22        | 0.28%   |
| Stockholm         | 21        | 0.27%   |
| Dublin            | 21        | 0.27%   |
| Curitiba          | 21        | 0.27%   |
| Belgrade          | 21        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1541      | 1856   | 17.16%  |
| WDC                         | 862       | 1007   | 9.6%    |
| Seagate                     | 710       | 835    | 7.91%   |
| Sandisk                     | 584       | 702    | 6.5%    |
| Toshiba                     | 559       | 626    | 6.22%   |
| SK hynix                    | 510       | 564    | 5.68%   |
| Kingston                    | 461       | 514    | 5.13%   |
| Unknown                     | 424       | 519    | 4.72%   |
| Micron Technology           | 391       | 427    | 4.35%   |
| Intel                       | 360       | 446    | 4.01%   |
| Crucial                     | 275       | 320    | 3.06%   |
| KIOXIA                      | 209       | 234    | 2.33%   |
| HGST                        | 189       | 213    | 2.1%    |
| Hitachi                     | 180       | 220    | 2%      |
| Apple                       | 138       | 169    | 1.54%   |
| A-DATA Technology           | 126       | 141    | 1.4%    |
| Phison                      | 82        | 93     | 0.91%   |
| Unknown                     | 73        | 76     | 0.81%   |
| China                       | 72        | 84     | 0.8%    |
| Silicon Motion              | 62        | 72     | 0.69%   |
| LITEON                      | 62        | 67     | 0.69%   |
| Kingston Technology Company | 54        | 64     | 0.6%    |
| SPCC                        | 44        | 51     | 0.49%   |
| Netac                       | 44        | 53     | 0.49%   |
| Phison Electronics          | 42        | 44     | 0.47%   |
| Intenso                     | 39        | 51     | 0.43%   |
| PNY                         | 38        | 43     | 0.42%   |
| Micron/Crucial Technology   | 34        | 36     | 0.38%   |
| SSSTC                       | 30        | 32     | 0.33%   |
| ADATA Technology            | 29        | 34     | 0.32%   |
| Transcend                   | 27        | 32     | 0.3%    |
| Fujitsu                     | 25        | 28     | 0.28%   |
| LITEONIT                    | 22        | 30     | 0.24%   |
| GOODRAM                     | 22        | 24     | 0.24%   |
| UMIS                        | 21        | 23     | 0.23%   |
| JMicron Technology          | 21        | 24     | 0.23%   |
| Gigabyte Technology         | 21        | 22     | 0.23%   |
| Team                        | 20        | 21     | 0.22%   |
| Patriot                     | 18        | 20     | 0.2%    |
| Lexar                       | 17        | 18     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 113       | 1.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 100       | 1.08%   |
| Toshiba MQ04ABF100 1TB                              | 80        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 80        | 0.86%   |
| Unknown MMC Card  32GB                              | 77        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 77        | 0.83%   |
| Unknown MMC Card  64GB                              | 74        | 0.8%    |
| Unknown                                             | 73        | 0.79%   |
| Toshiba MQ01ABD100 1TB                              | 72        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 68        | 0.73%   |
| Intel SSDPEKNU512GZ 512GB                           | 61        | 0.66%   |
| Seagate ST500LT012-1DG142 500GB                     | 54        | 0.58%   |
| Toshiba MQ01ABF050 500GB                            | 49        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 48        | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 47        | 0.51%   |
| Seagate ST9500325AS 500GB                           | 45        | 0.49%   |
| Kingston SA400S37480G 480GB SSD                     | 45        | 0.49%   |
| HGST HTS721010A9E630 1TB                            | 45        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                        | 44        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                        | 44        | 0.48%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 43        | 0.46%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 42        | 0.45%   |
| Unknown MMC Card  128GB                             | 40        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 38        | 0.41%   |
| HGST HTS545050A7E680 500GB                          | 37        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 37        | 0.4%    |
| Samsung MZALQ512HALU-000L2 512GB                    | 36        | 0.39%   |
| Phison 311CD0512GB                                  | 36        | 0.39%   |
| Intel SSD 660P Series 1TB                           | 36        | 0.39%   |
| HGST HTS541010A9E680 1TB                            | 36        | 0.39%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 35        | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 34        | 0.37%   |
| Intel SSDPEKNW512G8 512GB                           | 32        | 0.35%   |
| KIOXIA KBG40ZNV512G 512GB                           | 31        | 0.33%   |
| Kingston SA400S37120G 120GB SSD                     | 31        | 0.33%   |
| Unknown SD/MMC/MS PRO 512GB                         | 30        | 0.32%   |
| Samsung SSD 980 1TB                                 | 30        | 0.32%   |
| Samsung SSD 850 EVO 500GB                           | 30        | 0.32%   |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 29        | 0.31%   |
| Crucial CT1000MX500SSD1 1TB                         | 29        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 683       | 801    | 33.01%  |
| WDC                 | 496       | 579    | 23.97%  |
| Toshiba             | 368       | 404    | 17.79%  |
| HGST                | 189       | 213    | 9.13%   |
| Hitachi             | 179       | 219    | 8.65%   |
| Samsung Electronics | 38        | 45     | 1.84%   |
| Unknown             | 33        | 38     | 1.59%   |
| Fujitsu             | 25        | 28     | 1.21%   |
| SABRENT             | 12        | 12     | 0.58%   |
| Apple               | 9         | 10     | 0.43%   |
| USB3.0              | 5         | 5      | 0.24%   |
| External            | 5         | 13     | 0.24%   |
| Intenso             | 4         | 4      | 0.19%   |
| USB                 | 3         | 3      | 0.14%   |
| TO Exter            | 3         | 3      | 0.14%   |
| StoreJet            | 3         | 3      | 0.14%   |
| SSK                 | 3         | 3      | 0.14%   |
| ASMT                | 3         | 3      | 0.14%   |
| SAGE                | 2         | 2      | 0.1%    |
| MARSHAL             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| JMicron Technology  | 1         | 1      | 0.05%   |
| Initio              | 1         | 1      | 0.05%   |
| HGST HTS            | 1         | 2      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 525       | 622    | 20.4%   |
| Kingston            | 311       | 353    | 12.08%  |
| SanDisk             | 250       | 314    | 9.71%   |
| Crucial             | 237       | 277    | 9.21%   |
| WDC                 | 135       | 162    | 5.24%   |
| SK hynix            | 84        | 99     | 3.26%   |
| Micron Technology   | 76        | 84     | 2.95%   |
| China               | 69        | 77     | 2.68%   |
| Intel               | 65        | 72     | 2.53%   |
| A-DATA Technology   | 65        | 68     | 2.53%   |
| Apple               | 62        | 68     | 2.41%   |
| LITEON              | 58        | 63     | 2.25%   |
| Toshiba             | 48        | 52     | 1.86%   |
| SPCC                | 41        | 48     | 1.59%   |
| Netac               | 41        | 48     | 1.59%   |
| PNY                 | 35        | 39     | 1.36%   |
| Unknown             | 25        | 25     | 0.97%   |
| Transcend           | 24        | 29     | 0.93%   |
| LITEONIT            | 22        | 30     | 0.85%   |
| Intenso             | 22        | 28     | 0.85%   |
| GOODRAM             | 19        | 21     | 0.74%   |
| Team                | 18        | 18     | 0.7%    |
| Patriot             | 18        | 20     | 0.7%    |
| Lexar               | 14        | 15     | 0.54%   |
| Gigabyte Technology | 14        | 14     | 0.54%   |
| KingSpec            | 13        | 13     | 0.51%   |
| JMicron Technology  | 12        | 13     | 0.47%   |
| Teclast             | 11        | 12     | 0.43%   |
| Hewlett-Packard     | 10        | 18     | 0.39%   |
| BHT                 | 9         | 12     | 0.35%   |
| Apacer              | 9         | 9      | 0.35%   |
| OCZ                 | 8         | 8      | 0.31%   |
| Emtec               | 8         | 10     | 0.31%   |
| Seagate             | 7         | 9      | 0.27%   |
| BIWIN               | 7         | 7      | 0.27%   |
| Corsair             | 6         | 6      | 0.23%   |
| Verbatim            | 5         | 5      | 0.19%   |
| SSSTC               | 5         | 6      | 0.19%   |
| Plextor             | 5         | 5      | 0.19%   |
| Phison              | 5         | 8      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 3638      | 4391   | 42.18%  |
| SSD     | 2425      | 2985   | 28.12%  |
| HDD     | 2007      | 2395   | 23.27%  |
| MMC     | 418       | 515    | 4.85%   |
| Unknown | 136       | 169    | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3987      | 5184   | 47.87%  |
| NVMe | 3633      | 4380   | 43.62%  |
| MMC  | 418       | 515    | 5.02%   |
| SAS  | 291       | 376    | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2802      | 3478   | 63.55%  |
| 0.51-1.0   | 1404      | 1653   | 31.84%  |
| 1.01-2.0   | 168       | 200    | 3.81%   |
| 4.01-10.0  | 19        | 27     | 0.43%   |
| 3.01-4.0   | 12        | 13     | 0.27%   |
| 2.01-3.0   | 2         | 7      | 0.05%   |
| 10.01-20.0 | 2         | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 2389      | 31.1%   |
| 251-500        | 2312      | 30.1%   |
| 501-1000       | 1274      | 16.59%  |
| 51-100         | 465       | 6.05%   |
| 1-20           | 375       | 4.88%   |
| 1001-2000      | 343       | 4.47%   |
| 21-50          | 274       | 3.57%   |
| More than 3000 | 87        | 1.13%   |
| 2001-3000      | 85        | 1.11%   |
| Unknown        | 77        | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2751      | 34.73%  |
| 21-50          | 1822      | 23.01%  |
| 51-100         | 1169      | 14.76%  |
| 101-250        | 1136      | 14.34%  |
| 251-500        | 564       | 7.12%   |
| 501-1000       | 268       | 3.38%   |
| 1001-2000      | 88        | 1.11%   |
| Unknown        | 77        | 0.97%   |
| More than 3000 | 26        | 0.33%   |
| 2001-3000      | 19        | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 10     | 3.13%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 7      | 2.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 8      | 2.19%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 6      | 1.88%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 6         | 6      | 1.88%   |
| Seagate ST9500325AS 500GB                           | 6         | 6      | 1.88%   |
| Seagate ST500LT012-9WS142 500GB                     | 6         | 6      | 1.88%   |
| HGST HTS541010A9E680 1TB                            | 6         | 6      | 1.88%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 5      | 1.57%   |
| HGST HTS545050A7E680 500GB                          | 5         | 5      | 1.57%   |
| Seagate ST1000LX015-1U7172 1TB                      | 4         | 4      | 1.25%   |
| Seagate ST1000LM014-SSHD-8GB                        | 4         | 4      | 1.25%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 4         | 5      | 1.25%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 1.25%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 3         | 3      | 0.94%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 3         | 3      | 0.94%   |
| Toshiba MQ01ABF050 500GB                            | 3         | 3      | 0.94%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 3         | 3      | 0.94%   |
| Seagate ST9320325AS 320GB                           | 3         | 3      | 0.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 4      | 0.94%   |
| Hitachi HTS547550A9E384 500GB                       | 3         | 3      | 0.94%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 0.94%   |
| Hitachi HTS543232A7A384 320GB                       | 3         | 3      | 0.94%   |
| HGST HTS721010A9E630 1TB                            | 3         | 3      | 0.94%   |
| HGST HTS541075A9E680 752GB                          | 3         | 3      | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 2      | 0.63%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 2         | 2      | 0.63%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 2         | 2      | 0.63%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 2      | 0.63%   |
| SK hynix HFS512G39TND-N210A 512GB SSD               | 2         | 2      | 0.63%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 2      | 0.63%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 2         | 2      | 0.63%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB             | 2         | 2      | 0.63%   |
| Seagate ST9500420AS 500GB                           | 2         | 2      | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 2      | 0.63%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 0.63%   |
| SanDisk SSD PLUS 240GB                              | 2         | 4      | 0.63%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                 | 2         | 2      | 0.63%   |
| Samsung Electronics SSD 870 EVO 500GB               | 2         | 2      | 0.63%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 72     | 21.07%  |
| WDC                 | 48        | 53     | 15.09%  |
| Toshiba             | 33        | 34     | 10.38%  |
| SK hynix            | 31        | 31     | 9.75%   |
| HGST                | 25        | 25     | 7.86%   |
| Hitachi             | 23        | 24     | 7.23%   |
| Samsung Electronics | 13        | 13     | 4.09%   |
| SanDisk             | 12        | 15     | 3.77%   |
| Intel               | 12        | 12     | 3.77%   |
| Micron Technology   | 10        | 10     | 3.14%   |
| Kingston            | 6         | 7      | 1.89%   |
| Crucial             | 6         | 7      | 1.89%   |
| LITEON              | 5         | 5      | 1.57%   |
| A-DATA Technology   | 5         | 6      | 1.57%   |
| Fujitsu             | 2         | 2      | 0.63%   |
| China               | 2         | 2      | 0.63%   |
| Apple               | 2         | 2      | 0.63%   |
| WALRAM              | 1         | 1      | 0.31%   |
| VISIPRO             | 1         | 1      | 0.31%   |
| Transcend           | 1         | 1      | 0.31%   |
| tecmiyo             | 1         | 1      | 0.31%   |
| SSSTC               | 1         | 1      | 0.31%   |
| ShiJi               | 1         | 1      | 0.31%   |
| RX7                 | 1         | 1      | 0.31%   |
| Phison              | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| LITEONIT            | 1         | 1      | 0.31%   |
| KingSpec            | 1         | 1      | 0.31%   |
| Intenso             | 1         | 1      | 0.31%   |
| Hypertec            | 1         | 1      | 0.31%   |
| HS-SSD-E100         | 1         | 1      | 0.31%   |
| HS-SSD-C160         | 1         | 1      | 0.31%   |
| Corsair             | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 72     | 35.26%  |
| WDC                 | 37        | 40     | 19.47%  |
| Toshiba             | 31        | 32     | 16.32%  |
| HGST                | 25        | 25     | 13.16%  |
| Hitachi             | 23        | 24     | 12.11%  |
| Samsung Electronics | 4         | 4      | 2.11%   |
| Fujitsu             | 2         | 2      | 1.05%   |
| Apple               | 1         | 1      | 0.53%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 189       | 200    | 59.81%  |
| SSD  | 94        | 102    | 29.75%  |
| NVMe | 33        | 34     | 10.44%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                                    | 1         | 1      | 14.29%  |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                               | 1         | 1      | 14.29%  |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 250GB | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 14.29%  |
| Crucial M4-CT256M4SSD3 256GB                                    | 1         | 1      | 14.29%  |
| A-DATA Technology SX8200PNP 256GB                               | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| HGST                | 1         | 1      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |
| A-DATA Technology   | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4374      | 6242   | 55.91%  |
| Works    | 3129      | 3869   | 40%     |
| Malfunc  | 312       | 336    | 3.99%   |
| Failed   | 7         | 7      | 0.09%   |
| Fixed    | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4881      | 52.61%  |
| Samsung Electronics                     | 1041      | 11.22%  |
| AMD                                     | 785       | 8.46%   |
| SanDisk                                 | 554       | 5.97%   |
| SK hynix                                | 414       | 4.46%   |
| Micron Technology                       | 315       | 3.4%    |
| Kingston Technology Company             | 202       | 2.18%   |
| KIOXIA                                  | 196       | 2.11%   |
| Toshiba America Info Systems            | 162       | 1.75%   |
| Phison Electronics                      | 134       | 1.44%   |
| Silicon Motion                          | 85        | 0.92%   |
| ADATA Technology                        | 83        | 0.89%   |
| Micron/Crucial Technology               | 74        | 0.8%    |
| Apple                                   | 63        | 0.68%   |
| Solid State Storage Technology          | 53        | 0.57%   |
| Nvidia                                  | 48        | 0.52%   |
| Union Memory (Shenzhen)                 | 39        | 0.42%   |
| Shenzhen Longsys Electronics            | 22        | 0.24%   |
| Marvell Technology Group                | 21        | 0.23%   |
| Yangtze Memory Technologies             | 16        | 0.17%   |
| Realtek Semiconductor                   | 15        | 0.16%   |
| MAXIO Technology (Hangzhou)             | 14        | 0.15%   |
| Lite-On Technology                      | 9         | 0.1%    |
| Lenovo                                  | 8         | 0.09%   |
| Solidigm                                | 7         | 0.08%   |
| Seagate Technology                      | 6         | 0.06%   |
| Shenzhen Unionmemory Information System | 4         | 0.04%   |
| Biwin Storage Technology                | 4         | 0.04%   |
| ASMedia Technology                      | 4         | 0.04%   |
| Unknown                                 | 4         | 0.04%   |
| Transcend                               | 3         | 0.03%   |
| Netac Technology                        | 3         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| INNOGRIT                                | 2         | 0.02%   |
| Zhaoxin                                 | 1         | 0.01%   |
| Ramaxel Technology(Shenzhen) Limited    | 1         | 0.01%   |
| JMicron Technology                      | 1         | 0.01%   |
| Jiangsu Huacun Elec.                    | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 698       | 7.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 575       | 5.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 526       | 5.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 445       | 4.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 428       | 4.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 343       | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 317       | 3.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 311       | 3.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 250       | 2.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 219       | 2.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 201       | 2.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 194       | 1.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 192       | 1.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 181       | 1.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 174       | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 165       | 1.68%   |
| Intel Comet Lake SATA AHCI Controller                                          | 155       | 1.58%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 145       | 1.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 134       | 1.37%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 132       | 1.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 126       | 1.28%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 121       | 1.23%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 118       | 1.2%    |
| Intel SSD 660P Series                                                          | 95        | 0.97%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 93        | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 91        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 89        | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 88        | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 85        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 83        | 0.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 82        | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 79        | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 74        | 0.75%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 71        | 0.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 70        | 0.71%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 70        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 67        | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 66        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 65        | 0.66%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 63        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4680      | 49.07%  |
| NVMe | 3627      | 38.03%  |
| RAID | 1004      | 10.53%  |
| IDE  | 226       | 2.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6103      | 81.29%  |
| AMD          | 1402      | 18.67%  |
| CentaurHauls | 2         | 0.03%   |
| Phytium      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 201       | 2.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 187       | 2.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 119       | 1.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 107       | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 106       | 1.41%   |
| Intel 12th Gen Core i7-12700H                 | 101       | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 97        | 1.29%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 94        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 85        | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 84        | 1.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 83        | 1.11%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 82        | 1.09%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 82        | 1.09%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 81        | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 78        | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 77        | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 76        | 1.01%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 76        | 1.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 72        | 0.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 71        | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 67        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 64        | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 61        | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 60        | 0.8%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 55        | 0.73%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 54        | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 53        | 0.71%   |
| Intel 12th Gen Core i7-1260P                  | 53        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 50        | 0.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 48        | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 48        | 0.64%   |
| Intel 12th Gen Core i7-1255U                  | 48        | 0.64%   |
| Intel 12th Gen Core i5-1235U                  | 47        | 0.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 45        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 43        | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 43        | 0.57%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 41        | 0.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 40        | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 40        | 0.53%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 40        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1726      | 22.99%  |
| Intel Core i7           | 1540      | 20.51%  |
| Other                   | 1357      | 18.07%  |
| Intel Core i3           | 531       | 7.07%   |
| Intel Celeron           | 423       | 5.63%   |
| AMD Ryzen 5             | 403       | 5.37%   |
| AMD Ryzen 7             | 382       | 5.09%   |
| Intel Core 2 Duo        | 188       | 2.5%    |
| Intel Pentium           | 145       | 1.93%   |
| AMD Ryzen 9             | 71        | 0.95%   |
| AMD A6                  | 66        | 0.88%   |
| Intel Atom              | 62        | 0.83%   |
| AMD Ryzen 3             | 62        | 0.83%   |
| AMD Ryzen 7 PRO         | 51        | 0.68%   |
| AMD A8                  | 49        | 0.65%   |
| AMD A4                  | 43        | 0.57%   |
| AMD A10                 | 40        | 0.53%   |
| Intel Pentium Dual-Core | 32        | 0.43%   |
| AMD E2                  | 28        | 0.37%   |
| Intel Core i9           | 27        | 0.36%   |
| AMD Ryzen 5 PRO         | 21        | 0.28%   |
| AMD E1                  | 20        | 0.27%   |
| Intel Pentium Silver    | 19        | 0.25%   |
| AMD E                   | 19        | 0.25%   |
| Intel Pentium Dual      | 18        | 0.24%   |
| AMD Athlon              | 18        | 0.24%   |
| Intel Xeon              | 14        | 0.19%   |
| Intel Core 2            | 12        | 0.16%   |
| Intel Core m3           | 11        | 0.15%   |
| AMD Turion 64 X2 Mobile | 11        | 0.15%   |
| Intel Genuine           | 9         | 0.12%   |
| Intel Core M            | 9         | 0.12%   |
| AMD Athlon II           | 9         | 0.12%   |
| Intel Celeron Dual-Core | 7         | 0.09%   |
| AMD A12                 | 7         | 0.09%   |
| AMD Phenom II           | 6         | 0.08%   |
| AMD FX                  | 6         | 0.08%   |
| AMD Sempron             | 5         | 0.07%   |
| AMD Athlon X2           | 5         | 0.07%   |
| AMD Athlon II Dual-Core | 5         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3137      | 41.78%  |
| 4      | 2537      | 33.79%  |
| 8      | 655       | 8.72%   |
| 6      | 597       | 7.95%   |
| 14     | 204       | 2.72%   |
| 10     | 152       | 2.02%   |
| 12     | 142       | 1.89%   |
| 1      | 47        | 0.63%   |
| 16     | 20        | 0.27%   |
| 24     | 10        | 0.13%   |
| 5      | 4         | 0.05%   |
| 3      | 4         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7508      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 6028      | 80.23%  |
| 1      | 1485      | 19.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7507      | 99.99%  |
| Unknown        | 1         | 0.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4543      | 59.16%  |
| 0x806c1    | 323       | 4.21%   |
| 0x806ec    | 218       | 2.84%   |
| 0x906a3    | 162       | 2.11%   |
| 0x0a50000c | 150       | 1.95%   |
| 0x806ea    | 148       | 1.93%   |
| 0x306a9    | 136       | 1.77%   |
| 0x08608103 | 112       | 1.46%   |
| 0x206a7    | 107       | 1.39%   |
| 0x906ea    | 95        | 1.24%   |
| 0x406e3    | 90        | 1.17%   |
| 0x40651    | 88        | 1.15%   |
| 0x306d4    | 84        | 1.09%   |
| 0xa0652    | 83        | 1.08%   |
| 0x806d1    | 83        | 1.08%   |
| 0x806e9    | 77        | 1%      |
| 0x706e5    | 71        | 0.92%   |
| 0x08108109 | 68        | 0.89%   |
| 0x08600106 | 67        | 0.87%   |
| 0x306c3    | 62        | 0.81%   |
| 0x706a8    | 59        | 0.77%   |
| 0x906a4    | 55        | 0.72%   |
| 0x0a50000d | 51        | 0.66%   |
| 0x20655    | 41        | 0.53%   |
| 0x906e9    | 33        | 0.43%   |
| 0x806eb    | 30        | 0.39%   |
| 0x0a404102 | 30        | 0.39%   |
| 0x506e3    | 29        | 0.38%   |
| 0x1067a    | 28        | 0.36%   |
| 0x08600104 | 28        | 0.36%   |
| 0x08108102 | 27        | 0.35%   |
| 0x30678    | 26        | 0.34%   |
| 0x06006705 | 25        | 0.33%   |
| 0x906ed    | 23        | 0.3%    |
| 0x506c9    | 23        | 0.3%    |
| 0x706a1    | 21        | 0.27%   |
| 0x806c2    | 18        | 0.23%   |
| 0x08608102 | 16        | 0.21%   |
| 0xb06a2    | 15        | 0.2%    |
| 0x20652    | 15        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1398      | 18.58%  |
| TigerLake        | 621       | 8.25%   |
| Unknown          | 565       | 7.51%   |
| Haswell          | 516       | 6.86%   |
| IvyBridge        | 457       | 6.07%   |
| SandyBridge      | 436       | 5.79%   |
| Skylake          | 390       | 5.18%   |
| Alderlake Hybrid | 374       | 4.97%   |
| Zen 3            | 308       | 4.09%   |
| Icelake          | 274       | 3.64%   |
| Broadwell        | 235       | 3.12%   |
| Westmere         | 228       | 3.03%   |
| Silvermont       | 190       | 2.52%   |
| Zen+             | 186       | 2.47%   |
| Penryn           | 185       | 2.46%   |
| Goldmont plus    | 184       | 2.45%   |
| Zen 2            | 176       | 2.34%   |
| CometLake        | 172       | 2.29%   |
| Excavator        | 117       | 1.55%   |
| Core             | 92        | 1.22%   |
| Goldmont         | 74        | 0.98%   |
| Puma             | 59        | 0.78%   |
| Piledriver       | 42        | 0.56%   |
| Zen              | 41        | 0.54%   |
| Bobcat           | 38        | 0.5%    |
| K10              | 32        | 0.43%   |
| Jaguar           | 28        | 0.37%   |
| Nehalem          | 22        | 0.29%   |
| K8 Hammer        | 21        | 0.28%   |
| K10 Llano        | 18        | 0.24%   |
| K8 & K10 hybrid  | 16        | 0.21%   |
| Steamroller      | 14        | 0.19%   |
| Tremont          | 11        | 0.15%   |
| Bonnell          | 4         | 0.05%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5700      | 58.98%  |
| Nvidia                           | 2173      | 22.48%  |
| AMD                              | 1789      | 18.51%  |
| Zhaoxin                          | 2         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 555       | 5.66%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 422       | 4.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 395       | 4.03%   |
| Intel UHD Graphics 620                                                                   | 324       | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 287       | 2.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 264       | 2.69%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 263       | 2.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 254       | 2.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 216       | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 213       | 2.17%   |
| Intel HD Graphics 620                                                                    | 212       | 2.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 210       | 2.14%   |
| AMD Lucienne                                                                             | 197       | 2.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 194       | 1.98%   |
| Intel HD Graphics 5500                                                                   | 193       | 1.97%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 190       | 1.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 168       | 1.71%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 166       | 1.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 153       | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 152       | 1.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 146       | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 142       | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 140       | 1.43%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 116       | 1.18%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 108       | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 97        | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 94        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 93        | 0.95%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 85        | 0.87%   |
| AMD Barcelo                                                                              | 82        | 0.84%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 81        | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 79        | 0.81%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 75        | 0.76%   |
| Intel HD Graphics 530                                                                    | 71        | 0.72%   |
| Intel HD Graphics 630                                                                    | 70        | 0.71%   |
| Intel HD Graphics 500                                                                    | 67        | 0.68%   |
| AMD Rembrandt [Radeon 680M]                                                              | 66        | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 64        | 0.65%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 63        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 61        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3756      | 50%     |
| Intel + Nvidia | 1650      | 21.96%  |
| 1 x AMD        | 1201      | 15.99%  |
| 1 x Nvidia     | 295       | 3.93%   |
| Intel + AMD    | 271       | 3.61%   |
| AMD + Nvidia   | 224       | 2.98%   |
| 2 x AMD        | 92        | 1.22%   |
| Other          | 15        | 0.2%    |
| 2 x Nvidia     | 4         | 0.05%   |
| 1 x Zhaoxin    | 2         | 0.03%   |
| 2 x Intel      | 1         | 0.01%   |
| 1 x SiS        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6230      | 82.39%  |
| Proprietary | 1189      | 15.72%  |
| Unknown     | 143       | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6206      | 81.97%  |
| 0.01-0.5   | 479       | 6.33%   |
| 1.01-2.0   | 386       | 5.1%    |
| 0.51-1.0   | 208       | 2.75%   |
| 3.01-4.0   | 188       | 2.48%   |
| 5.01-6.0   | 56        | 0.74%   |
| 7.01-8.0   | 31        | 0.41%   |
| 2.01-3.0   | 11        | 0.15%   |
| 8.01-16.0  | 6         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1609      | 18.16%  |
| BOE                     | 1464      | 16.53%  |
| Chimei Innolux          | 1225      | 13.83%  |
| LG Display              | 1092      | 12.33%  |
| Samsung Electronics     | 852       | 9.62%   |
| Dell                    | 285       | 3.22%   |
| Sharp                   | 257       | 2.9%    |
| Apple                   | 225       | 2.54%   |
| Goldstar                | 203       | 2.29%   |
| PANDA                   | 163       | 1.84%   |
| Chi Mei Optoelectronics | 141       | 1.59%   |
| Lenovo                  | 138       | 1.56%   |
| Hewlett-Packard         | 119       | 1.34%   |
| Acer                    | 87        | 0.98%   |
| InfoVision              | 83        | 0.94%   |
| AOC                     | 77        | 0.87%   |
| CSO                     | 76        | 0.86%   |
| Philips                 | 69        | 0.78%   |
| BenQ                    | 59        | 0.67%   |
| Iiyama                  | 57        | 0.64%   |
| Ancor Communications    | 52        | 0.59%   |
| ASUSTek Computer        | 43        | 0.49%   |
| Sony                    | 38        | 0.43%   |
| ViewSonic               | 33        | 0.37%   |
| LG Philips              | 31        | 0.35%   |
| TMX                     | 28        | 0.32%   |
| Mi                      | 19        | 0.21%   |
| CPT                     | 19        | 0.21%   |
| Panasonic               | 17        | 0.19%   |
| Toshiba                 | 14        | 0.16%   |
| MSI                     | 14        | 0.16%   |
| Sceptre Tech            | 11        | 0.12%   |
| KDC                     | 10        | 0.11%   |
| HKC                     | 10        | 0.11%   |
| HannStar                | 9         | 0.1%    |
| Fujitsu Siemens         | 9         | 0.1%    |
| Vizio                   | 8         | 0.09%   |
| Vestel Elektronik       | 8         | 0.09%   |
| SLD                     | 8         | 0.09%   |
| Eizo                    | 8         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 71        | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 58        | 0.65%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 57        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 56        | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 55        | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 45        | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 44        | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 42        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 38        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 38        | 0.42%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 35        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 34        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 34        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 33        | 0.37%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 31        | 0.35%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 31        | 0.35%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 29        | 0.32%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 29        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 28        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 28        | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 26        | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 26        | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 25        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 24        | 0.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 22        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 22        | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 22        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 22        | 0.25%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 22        | 0.25%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 21        | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 21        | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 20        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 20        | 0.22%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 20        | 0.22%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 20        | 0.22%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 20        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 19        | 0.21%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 19        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3855      | 46.67%  |
| 1366x768 (WXGA)    | 1991      | 24.1%   |
| 1600x900 (HD+)     | 408       | 4.94%   |
| 3840x2160 (4K)     | 350       | 4.24%   |
| 2560x1440 (QHD)    | 285       | 3.45%   |
| 1920x1200 (WUXGA)  | 262       | 3.17%   |
| 1280x800 (WXGA)    | 177       | 2.14%   |
| 2560x1600          | 169       | 2.05%   |
| 2880x1800          | 115       | 1.39%   |
| 1440x900 (WXGA+)   | 88        | 1.07%   |
| 3840x2400          | 64        | 0.77%   |
| 2560x1080          | 63        | 0.76%   |
| 1680x1050 (WSXGA+) | 63        | 0.76%   |
| 3440x1440          | 57        | 0.69%   |
| 2160x1440          | 45        | 0.54%   |
| 1280x1024 (SXGA)   | 29        | 0.35%   |
| 3200x1800 (QHD+)   | 20        | 0.24%   |
| 2256x1504          | 20        | 0.24%   |
| 1360x768           | 18        | 0.22%   |
| 3200x2000          | 14        | 0.17%   |
| 2520x1680          | 13        | 0.16%   |
| 1920x540           | 13        | 0.16%   |
| 3840x1080          | 12        | 0.15%   |
| 3072x1920          | 12        | 0.15%   |
| 2880x1620          | 12        | 0.15%   |
| 3000x2000          | 11        | 0.13%   |
| 3456x2160          | 10        | 0.12%   |
| 1920x1280          | 9         | 0.11%   |
| 1680x945           | 7         | 0.08%   |
| Unknown            | 7         | 0.08%   |
| 2240x1400          | 6         | 0.07%   |
| 3840x1600          | 5         | 0.06%   |
| 2304x1440          | 5         | 0.06%   |
| 1280x720 (HD)      | 5         | 0.06%   |
| 1024x768 (XGA)     | 4         | 0.05%   |
| 1024x600           | 4         | 0.05%   |
| 3840x1100          | 3         | 0.04%   |
| 800x1280           | 2         | 0.02%   |
| 3300x2200          | 2         | 0.02%   |
| 3120x2080          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3547      | 40.04%  |
| 13      | 1251      | 14.12%  |
| 14      | 1130      | 12.76%  |
| 17      | 631       | 7.12%   |
| 27      | 346       | 3.91%   |
| 24      | 325       | 3.67%   |
| 23      | 234       | 2.64%   |
| 16      | 231       | 2.61%   |
| 21      | 194       | 2.19%   |
| 12      | 151       | 1.7%    |
| 11      | 140       | 1.58%   |
| 34      | 107       | 1.21%   |
| 31      | 89        | 1%      |
| 18      | 60        | 0.68%   |
| Unknown | 56        | 0.63%   |
| 22      | 38        | 0.43%   |
| 19      | 33        | 0.37%   |
| 40      | 31        | 0.35%   |
| 20      | 30        | 0.34%   |
| 84      | 24        | 0.27%   |
| 54      | 24        | 0.27%   |
| 10      | 22        | 0.25%   |
| 72      | 20        | 0.23%   |
| 32      | 18        | 0.2%    |
| 28      | 17        | 0.19%   |
| 26      | 13        | 0.15%   |
| 25      | 11        | 0.12%   |
| 48      | 8         | 0.09%   |
| 43      | 7         | 0.08%   |
| 37      | 7         | 0.08%   |
| 86      | 6         | 0.07%   |
| 65      | 6         | 0.07%   |
| 49      | 6         | 0.07%   |
| 29      | 6         | 0.07%   |
| 46      | 5         | 0.06%   |
| 52      | 4         | 0.05%   |
| 38      | 4         | 0.05%   |
| 74      | 3         | 0.03%   |
| 42      | 3         | 0.03%   |
| 35      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 5421      | 61.7%   |
| 201-300     | 931       | 10.6%   |
| 501-600     | 828       | 9.42%   |
| 351-400     | 752       | 8.56%   |
| 401-500     | 340       | 3.87%   |
| 601-700     | 155       | 1.76%   |
| 701-800     | 126       | 1.43%   |
| 1001-1500   | 66        | 0.75%   |
| Unknown     | 56        | 0.64%   |
| 1501-2000   | 48        | 0.55%   |
| 801-900     | 46        | 0.52%   |
| 901-1000    | 11        | 0.13%   |
| 101-200     | 4         | 0.05%   |
| 1-100       | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6368      | 82.55%  |
| 16/10   | 995       | 12.9%   |
| 21/9    | 128       | 1.66%   |
| 3/2     | 120       | 1.56%   |
| Unknown | 29        | 0.38%   |
| 5/4     | 26        | 0.34%   |
| 32/9    | 14        | 0.18%   |
| 4/3     | 12        | 0.16%   |
| 0.56    | 6         | 0.08%   |
| 0.62    | 4         | 0.05%   |
| 6/5     | 3         | 0.04%   |
| 3.40    | 3         | 0.04%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.12    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3544      | 40.12%  |
| 81-90          | 1920      | 21.73%  |
| 201-250        | 635       | 7.19%   |
| 121-130        | 561       | 6.35%   |
| 71-80          | 449       | 5.08%   |
| 301-350        | 359       | 4.06%   |
| 351-500        | 229       | 2.59%   |
| 111-120        | 209       | 2.37%   |
| 51-60          | 143       | 1.62%   |
| 61-70          | 142       | 1.61%   |
| 151-200        | 112       | 1.27%   |
| 251-300        | 107       | 1.21%   |
| More than 1000 | 93        | 1.05%   |
| 501-1000       | 72        | 0.82%   |
| 141-150        | 70        | 0.79%   |
| 131-140        | 64        | 0.72%   |
| Unknown        | 56        | 0.63%   |
| 91-100         | 41        | 0.46%   |
| 41-50          | 23        | 0.26%   |
| 1-40           | 5         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 3753      | 43.38%  |
| 101-120       | 2317      | 26.78%  |
| 51-100        | 1282      | 14.82%  |
| 161-240       | 842       | 9.73%   |
| More than 240 | 319       | 3.69%   |
| 1-50          | 83        | 0.96%   |
| Unknown       | 56        | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5853      | 76.77%  |
| 2     | 1378      | 18.07%  |
| 0     | 191       | 2.51%   |
| 3     | 185       | 2.43%   |
| 4     | 14        | 0.18%   |
| 5     | 2         | 0.03%   |
| 6     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4162      | 35.71%  |
| Realtek Semiconductor             | 3973      | 34.09%  |
| Qualcomm Atheros                  | 1343      | 11.52%  |
| Broadcom                          | 640       | 5.49%   |
| MediaTek                          | 349       | 2.99%   |
| Broadcom Limited                  | 150       | 1.29%   |
| ASIX Electronics                  | 110       | 0.94%   |
| Ralink                            | 80        | 0.69%   |
| TP-Link                           | 77        | 0.66%   |
| Marvell Technology Group          | 76        | 0.65%   |
| DisplayLink                       | 62        | 0.53%   |
| Samsung Electronics               | 50        | 0.43%   |
| Dell                              | 46        | 0.39%   |
| Sierra Wireless                   | 42        | 0.36%   |
| Qualcomm                          | 41        | 0.35%   |
| Xiaomi                            | 37        | 0.32%   |
| Lenovo                            | 37        | 0.32%   |
| Nvidia                            | 35        | 0.3%    |
| Ralink Technology                 | 32        | 0.27%   |
| Ericsson Business Mobile Networks | 29        | 0.25%   |
| Hewlett-Packard                   | 25        | 0.21%   |
| NetGear                           | 22        | 0.19%   |
| Huawei Technologies               | 20        | 0.17%   |
| JMicron Technology                | 18        | 0.15%   |
| Apple                             | 18        | 0.15%   |
| OPPO Electronics                  | 16        | 0.14%   |
| Google                            | 16        | 0.14%   |
| ICS Advent                        | 14        | 0.12%   |
| Qualcomm Atheros Communications   | 13        | 0.11%   |
| Motorola PCS                      | 10        | 0.09%   |
| D-Link                            | 10        | 0.09%   |
| Fibocom                           | 9         | 0.08%   |
| Edimax Technology                 | 7         | 0.06%   |
| Arduino SA                        | 6         | 0.05%   |
| U-Blox                            | 5         | 0.04%   |
| D-Link System                     | 5         | 0.04%   |
| Toshiba                           | 4         | 0.03%   |
| Microchip Technology              | 4         | 0.03%   |
| Dresden Elektronik                | 4         | 0.03%   |
| Qualcomm Technologies             | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2256      | 16.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 551       | 3.95%   |
| Intel Wi-Fi 6 AX201                                               | 477       | 3.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 407       | 2.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 353       | 2.53%   |
| Intel Wireless 8265 / 8275                                        | 324       | 2.32%   |
| Intel Wi-Fi 6 AX200                                               | 303       | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 258       | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 253       | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 245       | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 244       | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 222       | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 214       | 1.54%   |
| Intel Wireless 7265                                               | 206       | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 206       | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 189       | 1.36%   |
| Intel Wireless 7260                                               | 187       | 1.34%   |
| Intel Wireless 8260                                               | 184       | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 183       | 1.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 150       | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 148       | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 147       | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 138       | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 127       | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 117       | 0.84%   |
| Intel Wireless 3165                                               | 114       | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 112       | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 109       | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 105       | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 101       | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 93        | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 92        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 92        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 90        | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 87        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 77        | 0.55%   |
| Intel Ethernet Connection I218-LM                                 | 73        | 0.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71        | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 71        | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 71        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 3985      | 51.49%  |
| Realtek Semiconductor             | 1252      | 16.18%  |
| Qualcomm Atheros                  | 1153      | 14.9%   |
| Broadcom                          | 518       | 6.69%   |
| MediaTek                          | 338       | 4.37%   |
| Broadcom Limited                  | 105       | 1.36%   |
| Ralink                            | 80        | 1.03%   |
| TP-Link                           | 64        | 0.83%   |
| Sierra Wireless                   | 42        | 0.54%   |
| Dell                              | 39        | 0.5%    |
| Qualcomm                          | 33        | 0.43%   |
| Ralink Technology                 | 32        | 0.41%   |
| NetGear                           | 21        | 0.27%   |
| Qualcomm Atheros Communications   | 13        | 0.17%   |
| Hewlett-Packard                   | 9         | 0.12%   |
| Fibocom                           | 9         | 0.12%   |
| Ericsson Business Mobile Networks | 9         | 0.12%   |
| D-Link                            | 9         | 0.12%   |
| D-Link System                     | 5         | 0.06%   |
| Edimax Technology                 | 3         | 0.04%   |
| TRENDnet                          | 2         | 0.03%   |
| Qualcomm Technologies             | 2         | 0.03%   |
| Linksys                           | 2         | 0.03%   |
| Belkin Components                 | 2         | 0.03%   |
| ASUSTek Computer                  | 2         | 0.03%   |
| U.S. Robotics                     | 1         | 0.01%   |
| Quectel Wireless Solutions        | 1         | 0.01%   |
| Microsoft                         | 1         | 0.01%   |
| Mercucys                          | 1         | 0.01%   |
| Marvell Technology Group          | 1         | 0.01%   |
| IMC Networks                      | 1         | 0.01%   |
| I-O Data Device                   | 1         | 0.01%   |
| Guillemot                         | 1         | 0.01%   |
| Fujitsu Siemens Computers         | 1         | 0.01%   |
| AboCom Systems                    | 1         | 0.01%   |
| Unknown                           | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 477       | 6.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 353       | 4.53%   |
| Intel Wireless 8265 / 8275                                     | 324       | 4.16%   |
| Intel Wi-Fi 6 AX200                                            | 303       | 3.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 258       | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 253       | 3.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 245       | 3.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 244       | 3.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 214       | 2.75%   |
| Intel Wireless 7265                                            | 206       | 2.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 206       | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 189       | 2.43%   |
| Intel Wireless 7260                                            | 187       | 2.4%    |
| Intel Wireless 8260                                            | 184       | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 183       | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 150       | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 148       | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 138       | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 127       | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 117       | 1.5%    |
| Intel Wireless 3165                                            | 114       | 1.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 112       | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 109       | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 93        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 92        | 1.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 92        | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                  | 90        | 1.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 87        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 77        | 0.99%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 71        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 71        | 0.91%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 68        | 0.87%   |
| Intel Wireless 3160                                            | 65        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 63        | 0.81%   |
| Intel Wireless-AC 9260                                         | 62        | 0.8%    |
| Intel Centrino Wireless-N 2230                                 | 56        | 0.72%   |
| Intel Centrino Advanced-N 6235                                 | 54        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 53        | 0.68%   |
| Intel Centrino Ultimate-N 6300                                 | 53        | 0.68%   |
| Intel Centrino Advanced-N 6200                                 | 53        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3379      | 56.88%  |
| Intel                                  | 1410      | 23.73%  |
| Qualcomm Atheros                       | 326       | 5.49%   |
| Broadcom                               | 220       | 3.7%    |
| ASIX Electronics                       | 110       | 1.85%   |
| Marvell Technology Group               | 75        | 1.26%   |
| DisplayLink                            | 62        | 1.04%   |
| Broadcom Limited                       | 48        | 0.81%   |
| Samsung Electronics                    | 39        | 0.66%   |
| Xiaomi                                 | 37        | 0.62%   |
| Lenovo                                 | 37        | 0.62%   |
| Nvidia                                 | 35        | 0.59%   |
| JMicron Technology                     | 18        | 0.3%    |
| Apple                                  | 18        | 0.3%    |
| OPPO Electronics                       | 16        | 0.27%   |
| Google                                 | 16        | 0.27%   |
| ICS Advent                             | 14        | 0.24%   |
| TP-Link                                | 13        | 0.22%   |
| MediaTek                               | 12        | 0.2%    |
| Huawei Technologies                    | 11        | 0.19%   |
| Qualcomm                               | 8         | 0.13%   |
| Motorola PCS                           | 7         | 0.12%   |
| Hewlett-Packard                        | 4         | 0.07%   |
| Edimax Technology                      | 4         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.05%   |
| Microchip Technology                   | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Netchip Technology                     | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| Davicom Semiconductor                  | 1         | 0.02%   |
| D-Link                                 | 1         | 0.02%   |
| Cypress Semiconductor                  | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2256      | 37.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 551       | 9.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 407       | 6.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 222       | 3.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 147       | 2.44%   |
| Intel Ethernet Connection I219-LM                                 | 105       | 1.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 101       | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 73        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 71        | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 71        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 69        | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 1.03%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 61        | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 60        | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 55        | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 49        | 0.81%   |
| Intel Ethernet Connection (16) I219-V                             | 47        | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                            | 40        | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                             | 40        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 40        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 39        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 38        | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 38        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 37        | 0.61%   |
| Intel Ethernet Connection (13) I219-V                             | 37        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 35        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 33        | 0.55%   |
| Intel Ethernet Connection (13) I219-LM                            | 33        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 32        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 31        | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 31        | 0.51%   |
| Intel Ethernet Connection (16) I219-LM                            | 30        | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 27        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 27        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 27        | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 27        | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 26        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 26        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 25        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7398      | 56.29%  |
| Ethernet | 5635      | 42.88%  |
| Modem    | 89        | 0.68%   |
| Unknown  | 20        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6282      | 78.94%  |
| Ethernet | 1676      | 21.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 4975      | 66.24%  |
| 1     | 2361      | 31.43%  |
| 0     | 124       | 1.65%   |
| 3     | 51        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5255      | 69.05%  |
| Yes  | 2355      | 30.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3377      | 53.47%  |
| Realtek Semiconductor           | 706       | 11.18%  |
| Qualcomm Atheros Communications | 477       | 7.55%   |
| IMC Networks                    | 348       | 5.51%   |
| Foxconn / Hon Hai               | 264       | 4.18%   |
| Lite-On Technology              | 260       | 4.12%   |
| Broadcom                        | 230       | 3.64%   |
| Apple                           | 164       | 2.6%    |
| Dell                            | 83        | 1.31%   |
| Realtek                         | 81        | 1.28%   |
| Hewlett-Packard                 | 62        | 0.98%   |
| Cambridge Silicon Radio         | 55        | 0.87%   |
| Ralink                          | 46        | 0.73%   |
| Toshiba                         | 39        | 0.62%   |
| MediaTek                        | 23        | 0.36%   |
| ASUSTek Computer                | 18        | 0.28%   |
| Alps Electric                   | 17        | 0.27%   |
| Foxconn International           | 12        | 0.19%   |
| USI                             | 11        | 0.17%   |
| Ralink Technology               | 11        | 0.17%   |
| Opticis                         | 7         | 0.11%   |
| Askey Computer                  | 6         | 0.09%   |
| Integrated System Solution      | 3         | 0.05%   |
| TP-Link                         | 2         | 0.03%   |
| Taiyo Yuden                     | 2         | 0.03%   |
| Micro Star International        | 2         | 0.03%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Mobile Action Technology        | 1         | 0.02%   |
| Marvell Semiconductor           | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 1237      | 19.57%  |
| Intel Bluetooth wireless interface                  | 1060      | 16.77%  |
| Realtek Bluetooth Radio                             | 516       | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 472       | 7.47%   |
| Intel AX200 Bluetooth                               | 298       | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 248       | 3.92%   |
| IMC Networks Wireless_Device                        | 150       | 2.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 126       | 1.99%   |
| Apple Bluetooth Host Controller                     | 101       | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 100       | 1.58%   |
| IMC Networks Bluetooth Radio                        | 99        | 1.57%   |
| Intel AX210 Bluetooth                               | 87        | 1.38%   |
| Foxconn / Hon Hai Bluetooth Device                  | 82        | 1.3%    |
| Realtek Bluetooth Radio                             | 81        | 1.28%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 74        | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 70        | 1.11%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 58        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 56        | 0.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 55        | 0.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 55        | 0.87%   |
| Lite-On Bluetooth Device                            | 54        | 0.85%   |
| Lite-On Wireless_Device                             | 50        | 0.79%   |
| IMC Networks Bluetooth Device                       | 49        | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 48        | 0.76%   |
| Apple Bluetooth USB Host Controller                 | 48        | 0.76%   |
| Ralink RT3290 Bluetooth                             | 46        | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 45        | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 42        | 0.66%   |
| Broadcom BCM2045B (BDC-2.1)                         | 34        | 0.54%   |
| Dell DW375 Bluetooth Module                         | 32        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 31        | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 29        | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 29        | 0.46%   |
| Broadcom HP Portable SoftSailing                    | 28        | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.43%   |
| Realtek RTL8723B Bluetooth                          | 25        | 0.4%    |
| MediaTek Wireless_Device                            | 23        | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 21        | 0.33%   |
| Broadcom BCM43142A0 Bluetooth Device                | 21        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5995      | 63.91%  |
| AMD                                          | 1564      | 16.67%  |
| Nvidia                                       | 1171      | 12.48%  |
| Logitech                                     | 54        | 0.58%   |
| Realtek Semiconductor                        | 53        | 0.57%   |
| C-Media Electronics                          | 50        | 0.53%   |
| Hewlett-Packard                              | 48        | 0.51%   |
| Lenovo                                       | 47        | 0.5%    |
| GN Netcom                                    | 47        | 0.5%    |
| Apple                                        | 45        | 0.48%   |
| Plantronics                                  | 33        | 0.35%   |
| JMTek                                        | 22        | 0.23%   |
| Generalplus Technology                       | 20        | 0.21%   |
| Texas Instruments                            | 16        | 0.17%   |
| Razer USA                                    | 16        | 0.17%   |
| Kingston Technology                          | 15        | 0.16%   |
| DSEA A/S                                     | 15        | 0.16%   |
| Corsair                                      | 15        | 0.16%   |
| Creative Technology                          | 10        | 0.11%   |
| ASUSTek Computer                             | 9         | 0.1%    |
| SteelSeries ApS                              | 8         | 0.09%   |
| DCMT Technology                              | 7         | 0.07%   |
| Sony                                         | 6         | 0.06%   |
| Focusrite-Novation                           | 6         | 0.06%   |
| BR23                                         | 6         | 0.06%   |
| BEHRINGER International                      | 5         | 0.05%   |
| RODE Microphones                             | 4         | 0.04%   |
| Google                                       | 4         | 0.04%   |
| Conexant Systems                             | 4         | 0.04%   |
| Turtle Beach                                 | 3         | 0.03%   |
| Sennheiser Communications                    | 3         | 0.03%   |
| Samsung Electronics                          | 3         | 0.03%   |
| OPPO Electronics                             | 3         | 0.03%   |
| Microsoft                                    | 3         | 0.03%   |
| Mark of the Unicorn                          | 3         | 0.03%   |
| JBL                                          | 3         | 0.03%   |
| FIFINE Microphones                           | 3         | 0.03%   |
| Dell                                         | 3         | 0.03%   |
| CMX Systems                                  | 3         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 953       | 8.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 873       | 7.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 621       | 5.5%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 592       | 5.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 529       | 4.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 428       | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 363       | 3.21%   |
| Intel 8 Series HD Audio Controller                                         | 293       | 2.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 292       | 2.59%   |
| Intel Comet Lake PCH-LP cAVS                                               | 266       | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 249       | 2.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 239       | 2.12%   |
| Intel Broadwell-U Audio Controller                                         | 235       | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 230       | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 227       | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 226       | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 208       | 1.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 184       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 180       | 1.59%   |
| AMD FCH Azalia Controller                                                  | 176       | 1.56%   |
| Nvidia Audio device                                                        | 168       | 1.49%   |
| Intel Comet Lake PCH cAVS                                                  | 163       | 1.44%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 160       | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 154       | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 153       | 1.35%   |
| Nvidia GA106 High Definition Audio Controller                              | 138       | 1.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 126       | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                   | 119       | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 113       | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 102       | 0.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 92        | 0.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 88        | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 85        | 0.75%   |
| AMD High Definition Audio Controller                                       | 85        | 0.75%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 83        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 82        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                              | 79        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 79        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                            | 77        | 0.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 76        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1547      | 30.88%  |
| SK hynix            | 1168      | 23.31%  |
| Micron Technology   | 730       | 14.57%  |
| Kingston            | 360       | 7.19%   |
| Crucial             | 246       | 4.91%   |
| Unknown             | 161       | 3.21%   |
| A-DATA Technology   | 119       | 2.38%   |
| Unknown (ABCD)      | 95        | 1.9%    |
| Ramaxel Technology  | 91        | 1.82%   |
| Unknown             | 57        | 1.14%   |
| Nanya Technology    | 53        | 1.06%   |
| Elpida              | 49        | 0.98%   |
| Corsair             | 47        | 0.94%   |
| Smart               | 32        | 0.64%   |
| G.Skill             | 31        | 0.62%   |
| Team                | 23        | 0.46%   |
| ChangXin Memory     | 15        | 0.3%    |
| Patriot             | 14        | 0.28%   |
| GOODRAM             | 12        | 0.24%   |
| Transcend           | 10        | 0.2%    |
| Smart Brazil        | 10        | 0.2%    |
| Teikon              | 6         | 0.12%   |
| PNY                 | 6         | 0.12%   |
| Goldkey             | 6         | 0.12%   |
| Apacer              | 6         | 0.12%   |
| Neo Forza           | 5         | 0.1%    |
| Wilk                | 4         | 0.08%   |
| SHARETRONIC         | 4         | 0.08%   |
| ff                  | 4         | 0.08%   |
| fef5                | 4         | 0.08%   |
| Avant               | 4         | 0.08%   |
| ASint Technology    | 4         | 0.08%   |
| 4ea5                | 4         | 0.08%   |
| Toshiba             | 3         | 0.06%   |
| Timetec             | 3         | 0.06%   |
| Silicon Power       | 3         | 0.06%   |
| Hikvision           | 3         | 0.06%   |
| AMD                 | 3         | 0.06%   |
| 8CFD000080AD        | 3         | 0.06%   |
| Unknown (8AD6)      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 104       | 1.98%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 88        | 1.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 74        | 1.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 73        | 1.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 57        | 1.09%   |
| Unknown                                                          | 57        | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 50        | 0.95%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 50        | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 49        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 0.89%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 46        | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 41        | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 41        | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 38        | 0.72%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 38        | 0.72%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 37        | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 33        | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 33        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 32        | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 32        | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 30        | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 28        | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 27        | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 27        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 27        | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 26        | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 26        | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 25        | 0.48%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 25        | 0.48%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 24        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 24        | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2374      | 55.85%  |
| DDR3    | 938       | 22.07%  |
| LPDDR4  | 364       | 8.56%   |
| DDR5    | 186       | 4.38%   |
| LPDDR3  | 155       | 3.65%   |
| LPDDR5  | 124       | 2.92%   |
| DDR2    | 58        | 1.36%   |
| SDRAM   | 30        | 0.71%   |
| Unknown | 17        | 0.4%    |
| DDR     | 4         | 0.09%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 3556      | 82.47%  |
| Row Of Chips    | 678       | 15.72%  |
| Unknown         | 34        | 0.79%   |
| Chip            | 23        | 0.53%   |
| DIMM            | 18        | 0.42%   |
| Proprietary Car | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Notebooks | Percent |
|--------|-----------|---------|
| 8192   | 2044      | 44.26%  |
| 4096   | 1122      | 24.3%   |
| 16384  | 906       | 19.62%  |
| 2048   | 292       | 6.32%   |
| 32768  | 180       | 3.9%    |
| 1024   | 64        | 1.39%   |
| 6144   | 4         | 0.09%   |
| 65536  | 2         | 0.04%   |
| 12288  | 2         | 0.04%   |
| 131072 | 1         | 0.02%   |
| 1536   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 1363      | 30.13%  |
| 2667    | 867       | 19.16%  |
| 1600    | 701       | 15.5%   |
| 2400    | 323       | 7.14%   |
| 2133    | 220       | 4.86%   |
| 4800    | 170       | 3.76%   |
| 1334    | 143       | 3.16%   |
| 4267    | 142       | 3.14%   |
| 6400    | 120       | 2.65%   |
| 1333    | 84        | 1.86%   |
| 3266    | 49        | 1.08%   |
| 1867    | 44        | 0.97%   |
| 4266    | 42        | 0.93%   |
| Unknown | 35        | 0.77%   |
| 667     | 34        | 0.75%   |
| 1067    | 31        | 0.69%   |
| 3733    | 28        | 0.62%   |
| 4199    | 23        | 0.51%   |
| 5600    | 19        | 0.42%   |
| 8400    | 14        | 0.31%   |
| 1066    | 14        | 0.31%   |
| 800     | 14        | 0.31%   |
| 2933    | 7         | 0.15%   |
| 2048    | 6         | 0.13%   |
| 1866    | 4         | 0.09%   |
| 533     | 4         | 0.09%   |
| 5500    | 3         | 0.07%   |
| 975     | 3         | 0.07%   |
| 333     | 3         | 0.07%   |
| 7467    | 2         | 0.04%   |
| 8600    | 1         | 0.02%   |
| 7500    | 1         | 0.02%   |
| 5200    | 1         | 0.02%   |
| 3000    | 1         | 0.02%   |
| 2800    | 1         | 0.02%   |
| 2666    | 1         | 0.02%   |
| 1800    | 1         | 0.02%   |
| 1777    | 1         | 0.02%   |
| 1639    | 1         | 0.02%   |
| 1330    | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 26        | 33.77%  |
| Canon               | 15        | 19.48%  |
| Brother Industries  | 14        | 18.18%  |
| Seiko Epson         | 8         | 10.39%  |
| Samsung Electronics | 5         | 6.49%   |
| STMicroelectronics  | 2         | 2.6%    |
| Xiaomi              | 1         | 1.3%    |
| Xerox               | 1         | 1.3%    |
| QinHeng Electronics | 1         | 1.3%    |
| Kyocera             | 1         | 1.3%    |
| Dymo-CoStar         | 1         | 1.3%    |
| Dell                | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2300 series                                    | 4         | 5.13%   |
| HP DeskJet 2700 series                                    | 3         | 3.85%   |
| HP LaserJet 1020                                          | 2         | 2.56%   |
| Brother DCP-1510                                          | 2         | 2.56%   |
| Xiaomi MiMouse 2                                          | 1         | 1.28%   |
| Xerox Phaser 3260                                         | 1         | 1.28%   |
| STMicroelectronics USB Printer P                          | 1         | 1.28%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.28%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.28%   |
| Seiko Epson USB2.0 Printer                                | 1         | 1.28%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 1.28%   |
| Seiko Epson L360 Series                                   | 1         | 1.28%   |
| Seiko Epson L3110 Series                                  | 1         | 1.28%   |
| Seiko Epson FX-2190IIN                                    | 1         | 1.28%   |
| Seiko Epson ET-2600 Series                                | 1         | 1.28%   |
| Seiko Epson Epson Stylus Photo 1500                       | 1         | 1.28%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.28%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.28%   |
| Samsung M2020 Series                                      | 1         | 1.28%   |
| Samsung CLX-3180 Series                                   | 1         | 1.28%   |
| Samsung C43x Series                                       | 1         | 1.28%   |
| QinHeng CH340S                                            | 1         | 1.28%   |
| Kyocera FS-1116MFP                                        | 1         | 1.28%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.28%   |
| HP Officejet 4630 series                                  | 1         | 1.28%   |
| HP Officejet 4500 G510n-z                                 | 1         | 1.28%   |
| HP LaserJet P1102                                         | 1         | 1.28%   |
| HP LaserJet M14-M17                                       | 1         | 1.28%   |
| HP LaserJet 4250                                          | 1         | 1.28%   |
| HP LaserJet 400 M401a                                     | 1         | 1.28%   |
| HP LaserJet 1300                                          | 1         | 1.28%   |
| HP LaserJet 1150                                          | 1         | 1.28%   |
| HP LaserJet 1018                                          | 1         | 1.28%   |
| HP Laser 107a                                             | 1         | 1.28%   |
| HP ENVY 6000 series                                       | 1         | 1.28%   |
| HP DeskJet 3700 series                                    | 1         | 1.28%   |
| HP DeskJet 2600 series                                    | 1         | 1.28%   |
| HP Deskjet 2540 series                                    | 1         | 1.28%   |
| HP Deskjet 2050 J510                                      | 1         | 1.28%   |
| HP Color LaserJet CP1215                                  | 1         | 1.28%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 4         | 36.36%  |
| Seiko Epson                 | 2         | 18.18%  |
| Hewlett-Packard             | 2         | 18.18%  |
| Mustek Systems              | 1         | 9.09%   |
| KYE Systems (Mouse Systems) | 1         | 9.09%   |
| AGFA-Gevaert NV             | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Seiko Epson ES-D200 [GT-S50]                      | 1         | 9.09%   |
| Mustek Systems BearPaw 2448 CU Pro                | 1         | 9.09%   |
| KYE Systems (Mouse Systems) ColorPage-SF600       | 1         | 9.09%   |
| HP ScanJet 7400c                                  | 1         | 9.09%   |
| HP OfficeJet 6110                                 | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 110                           | 1         | 9.09%   |
| Canon CanoScan LiDE 100                           | 1         | 9.09%   |
| Canon CanoScan 4200F                              | 1         | 9.09%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1457      | 21.06%  |
| IMC Networks                           | 789       | 11.41%  |
| Microdia                               | 686       | 9.92%   |
| Realtek Semiconductor                  | 552       | 7.98%   |
| Quanta                                 | 470       | 6.79%   |
| Sunplus Innovation Technology          | 432       | 6.25%   |
| Bison Electronics                      | 425       | 6.14%   |
| Cheng Uei Precision Industry (Foxlink) | 287       | 4.15%   |
| Luxvisions Innotech Limited            | 199       | 2.88%   |
| Suyin                                  | 183       | 2.65%   |
| Syntek                                 | 182       | 2.63%   |
| Apple                                  | 160       | 2.31%   |
| Lite-On Technology                     | 159       | 2.3%    |
| Acer                                   | 103       | 1.49%   |
| Logitech                               | 102       | 1.47%   |
| Sonix Technology                       | 78        | 1.13%   |
| Silicon Motion                         | 77        | 1.11%   |
| Alcor Micro                            | 69        | 1%      |
| Samsung Electronics                    | 53        | 0.77%   |
| Ricoh                                  | 51        | 0.74%   |
| SunplusIT                              | 44        | 0.64%   |
| icSpring                               | 30        | 0.43%   |
| Importek                               | 28        | 0.4%    |
| Lenovo                                 | 24        | 0.35%   |
| Primax Electronics                     | 23        | 0.33%   |
| ALi                                    | 22        | 0.32%   |
| Z-Star Microelectronics                | 18        | 0.26%   |
| Y Media                                | 17        | 0.25%   |
| ShineTech                              | 12        | 0.17%   |
| Sunplus Technology                     | 11        | 0.16%   |
| Microsoft                              | 10        | 0.14%   |
| Intel                                  | 9         | 0.13%   |
| DigiTech                               | 9         | 0.13%   |
| OmniVision Technologies                | 7         | 0.1%    |
| 8SSC20F27114V1SR0BK1X4S                | 7         | 0.1%    |
| 8SSC21D67422V1SR28902JL                | 6         | 0.09%   |
| Unknown                                | 6         | 0.09%   |
| USB Camera CS                          | 5         | 0.07%   |
| Shine-optics                           | 5         | 0.07%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 380       | 5.47%   |
| Chicony Integrated Camera                           | 327       | 4.71%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 244       | 3.51%   |
| IMC Networks Integrated Camera                      | 207       | 2.98%   |
| Realtek Integrated_Webcam_HD                        | 205       | 2.95%   |
| Sunplus Integrated_Webcam_HD                        | 152       | 2.19%   |
| Bison Integrated Camera                             | 138       | 1.99%   |
| Chicony HD WebCam                                   | 129       | 1.86%   |
| Syntek Integrated Camera                            | 121       | 1.74%   |
| Chicony HP HD Camera                                | 87        | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 80        | 1.15%   |
| Quanta HD User Facing                               | 74        | 1.06%   |
| Realtek USB camera                                  | 73        | 1.05%   |
| Quanta HP HD Camera                                 | 70        | 1.01%   |
| Bison HD Webcam                                     | 65        | 0.94%   |
| IMC Networks HD Camera                              | 63        | 0.91%   |
| Sunplus HD WebCam                                   | 56        | 0.81%   |
| Chicony HP TrueVision HD Camera                     | 56        | 0.81%   |
| Quanta HP TrueVision HD Camera                      | 55        | 0.79%   |
| Lite-On Integrated Camera                           | 55        | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)             | 53        | 0.76%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 50        | 0.72%   |
| Chicony USB2.0 Camera                               | 50        | 0.72%   |
| Chicony TOSHIBA Web Camera - HD                     | 49        | 0.71%   |
| Chicony HD User Facing                              | 49        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE                           | 49        | 0.71%   |
| Quanta ACER HD User Facing                          | 48        | 0.69%   |
| Sonix USB2.0 HD UVC WebCam                          | 47        | 0.68%   |
| Luxvisions Innotech Limited Integrated Camera       | 46        | 0.66%   |
| Luxvisions Innotech Limited HP HD Camera            | 46        | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                        | 46        | 0.66%   |
| Microdia Integrated Webcam                          | 43        | 0.62%   |
| Chicony HP TrueVision HD                            | 43        | 0.62%   |
| Acer BisonCam,NB Pro                                | 42        | 0.6%    |
| Chicony HP Wide Vision HD Camera                    | 40        | 0.58%   |
| Suyin HP Truevision HD                              | 39        | 0.56%   |
| Bison SunplusIT Integrated Camera                   | 39        | 0.56%   |
| Bison Lenovo EasyCamera                             | 39        | 0.56%   |
| Apple FaceTime HD Camera                            | 39        | 0.56%   |
| Quanta HP Wide Vision HD Camera                     | 38        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 453       | 30.65%  |
| Synaptics                          | 396       | 26.79%  |
| Shenzhen Goodix Technology         | 322       | 21.79%  |
| Elan Microelectronics              | 116       | 7.85%   |
| Upek                               | 50        | 3.38%   |
| AuthenTec                          | 46        | 3.11%   |
| LighTuning Technology              | 35        | 2.37%   |
| Realtek USB2.0 Finger Print Bridge | 26        | 1.76%   |
| STMicroelectronics                 | 10        | 0.68%   |
| Samsung Electronics                | 8         | 0.54%   |
| Focal-systems.Corp                 | 7         | 0.47%   |
| HOLTEK                             | 5         | 0.34%   |
| GDMicroelectronics                 | 3         | 0.2%    |
| DigitalPersona                     | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 240       | 16.23%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 120       | 8.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 107       | 7.23%   |
| Elan ELAN:ARM-M4                                                           | 68        | 4.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 56        | 3.79%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 52        | 3.52%   |
| Elan ELAN:Fingerprint                                                      | 48        | 3.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 45        | 3.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 42        | 2.84%   |
| Shenzhen Goodix FingerPrint                                                | 42        | 2.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 40        | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 38        | 2.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 2.5%    |
| Validity Sensors Synaptics WBDI                                            | 36        | 2.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 31        | 2.1%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 30        | 2.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 30        | 2.03%   |
| Validity Sensors VFS491                                                    | 28        | 1.89%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 26        | 1.76%   |
| Validity Sensors Fingerprint scanner                                       | 25        | 1.69%   |
| Synaptics UWP WBDI Device                                                  | 24        | 1.62%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 24        | 1.62%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 23        | 1.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 22        | 1.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 21        | 1.42%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 1.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 20        | 1.35%   |
| AuthenTec Fingerprint Sensor                                               | 18        | 1.22%   |
| Synaptics WBDI                                                             | 16        | 1.08%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 12        | 0.81%   |
| Unknown                                                                    | 11        | 0.74%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 0.61%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.61%   |
| Synaptics UWP WBDI                                                         | 8         | 0.54%   |
| AuthenTec AES2810                                                          | 8         | 0.54%   |
| Synaptics  WBDI                                                            | 7         | 0.47%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 0.47%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.41%   |
| Synaptics TouchPad                                                         | 6         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 342       | 56.81%  |
| Alcor Micro               | 162       | 26.91%  |
| O2 Micro                  | 27        | 4.49%   |
| Upek                      | 22        | 3.65%   |
| Lenovo                    | 13        | 2.16%   |
| Gemalto (was Gemplus)     | 10        | 1.66%   |
| SCM Microsystems          | 5         | 0.83%   |
| Giesecke & Devrient       | 3         | 0.5%    |
| Aladdin Knowledge Systems | 3         | 0.5%    |
| Watchdata                 | 2         | 0.33%   |
| OmniKey                   | 2         | 0.33%   |
| Chicony Electronics       | 2         | 0.33%   |
| Cherry                    | 2         | 0.33%   |
| Reiner SCT Kartensysteme  | 1         | 0.17%   |
| Realtek Semiconductor     | 1         | 0.17%   |
| NXP Semiconductors        | 1         | 0.17%   |
| Fujitsu Siemens Computers | 1         | 0.17%   |
| C3PO                      | 1         | 0.17%   |
| Aktiv                     | 1         | 0.17%   |
| Advanced Card Systems     | 1         | 0.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 162       | 26.91%  |
| Broadcom 58200                                                               | 114       | 18.94%  |
| Broadcom BCM5880 Secure Applications Processor                               | 97        | 16.11%  |
| Broadcom 5880                                                                | 87        | 14.45%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 44        | 7.31%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 4.15%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 3.65%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 2.16%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 1.16%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 0.66%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.5%    |
| Watchdata USB Key                                                            | 2         | 0.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 0.33%   |
| Giesecke & Devrient StarSign CUT                                             | 2         | 0.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.33%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.17%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.17%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.17%   |
| OmniKey CardMan 4321                                                         | 1         | 0.17%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.17%   |
| NXP Semiconductors PR533                                                     | 1         | 0.17%   |
| Giesecke & Devrient StarSign CUT S                                           | 1         | 0.17%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.17%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.17%   |
| C3PO LTC31v2                                                                 | 1         | 0.17%   |
| Aktiv Rutoken lite                                                           | 1         | 0.17%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4377      | 57.48%  |
| 1     | 2580      | 33.88%  |
| 2     | 573       | 7.52%   |
| 3     | 65        | 0.85%   |
| 5     | 5         | 0.07%   |
| 4     | 5         | 0.07%   |
| 9     | 3         | 0.04%   |
| 8     | 2         | 0.03%   |
| 7     | 2         | 0.03%   |
| 6     | 2         | 0.03%   |
| 10    | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1444      | 36.6%   |
| Graphics card            | 883       | 22.38%  |
| Chipcard                 | 566       | 14.35%  |
| Net/wireless             | 320       | 8.11%   |
| Camera                   | 261       | 6.62%   |
| Multimedia controller    | 145       | 3.68%   |
| Bluetooth                | 94        | 2.38%   |
| Sound                    | 63        | 1.6%    |
| Storage                  | 60        | 1.52%   |
| Card reader              | 39        | 0.99%   |
| Communication controller | 26        | 0.66%   |
| Net/ethernet             | 23        | 0.58%   |
| Network                  | 16        | 0.41%   |
| Flash memory             | 3         | 0.08%   |
| Modem                    | 2         | 0.05%   |

