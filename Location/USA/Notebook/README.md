Linux in USA - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Linux in USA.

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

Total: 27602

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5558               | [acc47dae75](https://linux-hardware.org/?probe=acc47dae75) | Jan 02, 2024 |
| HP            | Pavilion dm4                | [7b2206d3e1](https://linux-hardware.org/?probe=7b2206d3e1) | Jan 02, 2024 |
| HP            | Pavilion dm4                | [97f8b54561](https://linux-hardware.org/?probe=97f8b54561) | Jan 02, 2024 |
| HP            | Laptop 17-cp0xxx            | [a9e2dd2fb6](https://linux-hardware.org/?probe=a9e2dd2fb6) | Jan 02, 2024 |
| System76      | Serval                      | [a0597a9161](https://linux-hardware.org/?probe=a0597a9161) | Jan 02, 2024 |
| HP            | ProBook 450 G5              | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| System76      | Serval                      | [c4a91b64e5](https://linux-hardware.org/?probe=c4a91b64e5) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [5570fbf22f](https://linux-hardware.org/?probe=5570fbf22f) | Jan 02, 2024 |
| MSI           | GS65 Stealth 9SG            | [6f3ddca46b](https://linux-hardware.org/?probe=6f3ddca46b) | Jan 02, 2024 |
| Gateway       | MT6707                      | [a2a87f6e95](https://linux-hardware.org/?probe=a2a87f6e95) | Jan 02, 2024 |
| Dell          | XPS 13 9380                 | [d290e010eb](https://linux-hardware.org/?probe=d290e010eb) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | [b732d30db5](https://linux-hardware.org/?probe=b732d30db5) | Jan 02, 2024 |
| Valve         | Jupiter                     | [e381b764b0](https://linux-hardware.org/?probe=e381b764b0) | Jan 02, 2024 |
| Dell          | G3 3590                     | [ae7267dd5f](https://linux-hardware.org/?probe=ae7267dd5f) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [197c876252](https://linux-hardware.org/?probe=197c876252) | Jan 02, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fb59929b28](https://linux-hardware.org/?probe=fb59929b28) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | [43bc3cd4bd](https://linux-hardware.org/?probe=43bc3cd4bd) | Jan 02, 2024 |
| Lenovo        | Legion Y545 81Q6            | [954ab5a643](https://linux-hardware.org/?probe=954ab5a643) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | [66f6fa63a2](https://linux-hardware.org/?probe=66f6fa63a2) | Jan 01, 2024 |
| Lenovo        | ThinkPad X260 20F5S0KE00    | [08d2a7a982](https://linux-hardware.org/?probe=08d2a7a982) | Jan 01, 2024 |
| Google        | Gallop                      | [917756724c](https://linux-hardware.org/?probe=917756724c) | Jan 01, 2024 |
| Apple         | MacBookPro11,2              | [4a37a9b35c](https://linux-hardware.org/?probe=4a37a9b35c) | Jan 01, 2024 |
| Dell          | Inspiron 5537               | [d19fc7dff7](https://linux-hardware.org/?probe=d19fc7dff7) | Jan 01, 2024 |
| ASUSTek       | K52Jc                       | [5f0c993270](https://linux-hardware.org/?probe=5f0c993270) | Jan 01, 2024 |
| Valve         | Jupiter                     | [c9de553faa](https://linux-hardware.org/?probe=c9de553faa) | Jan 01, 2024 |
| Dell          | Latitude 5480               | [c1d96bef16](https://linux-hardware.org/?probe=c1d96bef16) | Jan 01, 2024 |
| Gateway       | M-6307                      | [0936f4a650](https://linux-hardware.org/?probe=0936f4a650) | Jan 01, 2024 |
| Lenovo        | ThinkPad Twist 33476LU      | [bb88a71510](https://linux-hardware.org/?probe=bb88a71510) | Jan 01, 2024 |
| Dell          | Inspiron 5379               | [c3c47e54db](https://linux-hardware.org/?probe=c3c47e54db) | Jan 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [488deac73a](https://linux-hardware.org/?probe=488deac73a) | Jan 01, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [2872198e9f](https://linux-hardware.org/?probe=2872198e9f) | Jan 01, 2024 |
| Dell          | Inspiron 5402               | [388a6a9fc1](https://linux-hardware.org/?probe=388a6a9fc1) | Jan 01, 2024 |
| ASUSTek       | G75VW                       | [56e330d7bc](https://linux-hardware.org/?probe=56e330d7bc) | Dec 31, 2023 |
| Dell          | Latitude E6320              | [1833dcdd43](https://linux-hardware.org/?probe=1833dcdd43) | Dec 31, 2023 |
| Dell          | Latitude E6500              | [8d7d1376fd](https://linux-hardware.org/?probe=8d7d1376fd) | Dec 31, 2023 |
| Google        | Peppy                       | [9b8131eea3](https://linux-hardware.org/?probe=9b8131eea3) | Dec 31, 2023 |
| Valve         | Jupiter                     | [5be404c400](https://linux-hardware.org/?probe=5be404c400) | Dec 31, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [fc3a637b52](https://linux-hardware.org/?probe=fc3a637b52) | Dec 31, 2023 |
| Dell          | Latitude 7490               | [455ad2a6f1](https://linux-hardware.org/?probe=455ad2a6f1) | Dec 31, 2023 |
| Acer          | Aspire A515-43              | [68a2707c3f](https://linux-hardware.org/?probe=68a2707c3f) | Dec 31, 2023 |
| Dell          | Inspiron 3521               | [7de98bea51](https://linux-hardware.org/?probe=7de98bea51) | Dec 31, 2023 |
| Valve         | Jupiter                     | [e80d5f8a2b](https://linux-hardware.org/?probe=e80d5f8a2b) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [f160a53f1b](https://linux-hardware.org/?probe=f160a53f1b) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [70bbf55180](https://linux-hardware.org/?probe=70bbf55180) | Dec 31, 2023 |
| Dell          | Latitude E5430 non-vPro     | [e27c2e0ade](https://linux-hardware.org/?probe=e27c2e0ade) | Dec 31, 2023 |
| Lenovo        | Legion Y545 81Q6            | [a91810bda7](https://linux-hardware.org/?probe=a91810bda7) | Dec 31, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [8fb51545f7](https://linux-hardware.org/?probe=8fb51545f7) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | [71c755966f](https://linux-hardware.org/?probe=71c755966f) | Dec 31, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [a62110fad4](https://linux-hardware.org/?probe=a62110fad4) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | [b13ec8c4fe](https://linux-hardware.org/?probe=b13ec8c4fe) | Dec 31, 2023 |
| ASUSTek       | G74Sx                       | [0933c174aa](https://linux-hardware.org/?probe=0933c174aa) | Dec 30, 2023 |
| Google        | Barla                       | [585887bc42](https://linux-hardware.org/?probe=585887bc42) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [98f6888dcd](https://linux-hardware.org/?probe=98f6888dcd) | Dec 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [cb51f62169](https://linux-hardware.org/?probe=cb51f62169) | Dec 30, 2023 |
| System76      | Serval WS                   | [3dd4d45859](https://linux-hardware.org/?probe=3dd4d45859) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p              | [e45829bd8b](https://linux-hardware.org/?probe=e45829bd8b) | Dec 30, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [221c773946](https://linux-hardware.org/?probe=221c773946) | Dec 30, 2023 |
| Lenovo        | B590 20206                  | [d3c6913a54](https://linux-hardware.org/?probe=d3c6913a54) | Dec 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [2a29a4613c](https://linux-hardware.org/?probe=2a29a4613c) | Dec 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [9ee9bc6de8](https://linux-hardware.org/?probe=9ee9bc6de8) | Dec 30, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ebdb840dba](https://linux-hardware.org/?probe=ebdb840dba) | Dec 30, 2023 |
| ASUSTek       | U52F                        | [acf3ac6f23](https://linux-hardware.org/?probe=acf3ac6f23) | Dec 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [24ca756f75](https://linux-hardware.org/?probe=24ca756f75) | Dec 30, 2023 |
| Google        | Reef                        | [362a174638](https://linux-hardware.org/?probe=362a174638) | Dec 30, 2023 |
| Lenovo        | ThinkPad X280 20KF0025US    | [5766ed7c57](https://linux-hardware.org/?probe=5766ed7c57) | Dec 29, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [75516d0dbc](https://linux-hardware.org/?probe=75516d0dbc) | Dec 29, 2023 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [402a1c70b8](https://linux-hardware.org/?probe=402a1c70b8) | Dec 29, 2023 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [13e876e5cf](https://linux-hardware.org/?probe=13e876e5cf) | Dec 29, 2023 |
| Dell          | XPS 15 9560                 | [aabd2af674](https://linux-hardware.org/?probe=aabd2af674) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | [03ad95c394](https://linux-hardware.org/?probe=03ad95c394) | Dec 29, 2023 |
| Unknown       | M17                         | [3d6789f805](https://linux-hardware.org/?probe=3d6789f805) | Dec 29, 2023 |
| Dell          | Latitude 5424 Rugged        | [1339f0b553](https://linux-hardware.org/?probe=1339f0b553) | Dec 29, 2023 |
| Dell          | Latitude 7300               | [926a273123](https://linux-hardware.org/?probe=926a273123) | Dec 29, 2023 |
| Dell          | Latitude 7300               | [ac9c0099fd](https://linux-hardware.org/?probe=ac9c0099fd) | Dec 29, 2023 |
| Dell          | Inspiron 5759               | [9586fa7d24](https://linux-hardware.org/?probe=9586fa7d24) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [13ba865757](https://linux-hardware.org/?probe=13ba865757) | Dec 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [92c8c4f42c](https://linux-hardware.org/?probe=92c8c4f42c) | Dec 28, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [be86cafd2e](https://linux-hardware.org/?probe=be86cafd2e) | Dec 28, 2023 |
| Valve         | Galileo                     | [83bfa965fb](https://linux-hardware.org/?probe=83bfa965fb) | Dec 28, 2023 |
| Dell          | Vostro 15 5510              | [02df63af48](https://linux-hardware.org/?probe=02df63af48) | Dec 28, 2023 |
| ASUSTek       | G73Jh                       | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| Acer          | Nitro AN515-54              | [b310676172](https://linux-hardware.org/?probe=b310676172) | Dec 28, 2023 |
| Acer          | Aspire E5-553G              | [a21fc70e01](https://linux-hardware.org/?probe=a21fc70e01) | Dec 28, 2023 |
| Apple         | MacBookPro8,3               | [e47426bf12](https://linux-hardware.org/?probe=e47426bf12) | Dec 28, 2023 |
| Apple         | MacBookPro9,2               | [b73abb7ffa](https://linux-hardware.org/?probe=b73abb7ffa) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| HP            | ProBook 6470b               | [60858223c4](https://linux-hardware.org/?probe=60858223c4) | Dec 28, 2023 |
| ASUSTek       | G750JX                      | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| GPU Compan... | GWTN141-10                  | [6e74e1b943](https://linux-hardware.org/?probe=6e74e1b943) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a5b16ddafb](https://linux-hardware.org/?probe=a5b16ddafb) | Dec 28, 2023 |
| Valve         | Galileo                     | [ae65838bd7](https://linux-hardware.org/?probe=ae65838bd7) | Dec 28, 2023 |
| Lenovo        | ThinkPad T560 20FH002GUS    | [76926807cc](https://linux-hardware.org/?probe=76926807cc) | Dec 28, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [52a99e896e](https://linux-hardware.org/?probe=52a99e896e) | Dec 28, 2023 |
| Lenovo        | ThinkPad T560 20FH002GUS    | [cf5b823135](https://linux-hardware.org/?probe=cf5b823135) | Dec 28, 2023 |
| MSI           | GF65 Thin 10SDR             | [18a746317d](https://linux-hardware.org/?probe=18a746317d) | Dec 28, 2023 |
| Apple         | MacBookPro5,5               | [609aece6c1](https://linux-hardware.org/?probe=609aece6c1) | Dec 28, 2023 |
| HP            | Laptop 14-dk0xxx            | [754b2e0faf](https://linux-hardware.org/?probe=754b2e0faf) | Dec 27, 2023 |
| HP            | Laptop 14-dk0xxx            | [be356bc929](https://linux-hardware.org/?probe=be356bc929) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a81c208684](https://linux-hardware.org/?probe=a81c208684) | Dec 27, 2023 |
| ASUSTek       | X75A                        | [a7b35ca7c8](https://linux-hardware.org/?probe=a7b35ca7c8) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| Lenovo        | IdeaPad S740-15IRH Touch... | [6584c1853d](https://linux-hardware.org/?probe=6584c1853d) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| LG Electro... | 17Z90N-R.AAC8U1             | [b9fd2cf453](https://linux-hardware.org/?probe=b9fd2cf453) | Dec 27, 2023 |
| Valve         | Jupiter                     | [bee71f6f73](https://linux-hardware.org/?probe=bee71f6f73) | Dec 27, 2023 |
| Dell          | XPS 17 9720                 | [ff40dc8bad](https://linux-hardware.org/?probe=ff40dc8bad) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4290B52       | [f4ec8bd5f1](https://linux-hardware.org/?probe=f4ec8bd5f1) | Dec 27, 2023 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [7979b3518c](https://linux-hardware.org/?probe=7979b3518c) | Dec 27, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [d304e99c16](https://linux-hardware.org/?probe=d304e99c16) | Dec 27, 2023 |
| HP            | ProBook 6570b               | [61f91864e5](https://linux-hardware.org/?probe=61f91864e5) | Dec 27, 2023 |
| Valve         | Jupiter                     | [c2f08b6c04](https://linux-hardware.org/?probe=c2f08b6c04) | Dec 26, 2023 |
| ASUSTek       | K53E                        | [42082143bc](https://linux-hardware.org/?probe=42082143bc) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7a0c2d1a36](https://linux-hardware.org/?probe=7a0c2d1a36) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f2094a7c07](https://linux-hardware.org/?probe=f2094a7c07) | Dec 26, 2023 |
| Dell          | Inspiron 3558               | [d5e9630425](https://linux-hardware.org/?probe=d5e9630425) | Dec 26, 2023 |
| Chuwi         | MiniBook X                  | [f55a24b036](https://linux-hardware.org/?probe=f55a24b036) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3db4d71445](https://linux-hardware.org/?probe=3db4d71445) | Dec 26, 2023 |
| ASUSTek       | UX31A                       | [bb819f78ef](https://linux-hardware.org/?probe=bb819f78ef) | Dec 26, 2023 |
| Dell          | Inspiron 3558               | [3015754a4f](https://linux-hardware.org/?probe=3015754a4f) | Dec 26, 2023 |
| Dell          | XPS 15 9530                 | [5902199f52](https://linux-hardware.org/?probe=5902199f52) | Dec 26, 2023 |
| Lenovo        | ThinkPad E480 20KN003XUS    | [b83c19a718](https://linux-hardware.org/?probe=b83c19a718) | Dec 26, 2023 |
| Dell          | Latitude 5440               | [44e45480d1](https://linux-hardware.org/?probe=44e45480d1) | Dec 26, 2023 |
| Apple         | MacBookPro12,1              | [0714d5920a](https://linux-hardware.org/?probe=0714d5920a) | Dec 26, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [b5b5857360](https://linux-hardware.org/?probe=b5b5857360) | Dec 26, 2023 |
| Dell          | Latitude E6420              | [3a25e340a8](https://linux-hardware.org/?probe=3a25e340a8) | Dec 26, 2023 |
| Dell          | XPS 13 9343                 | [8ba85bdc8c](https://linux-hardware.org/?probe=8ba85bdc8c) | Dec 26, 2023 |
| Unknown       | Unknown                     | [64873f6716](https://linux-hardware.org/?probe=64873f6716) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [ef91ce6df3](https://linux-hardware.org/?probe=ef91ce6df3) | Dec 26, 2023 |
| HP            | Victus by Gaming Laptop ... | [081217d505](https://linux-hardware.org/?probe=081217d505) | Dec 26, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [5f798fd0e0](https://linux-hardware.org/?probe=5f798fd0e0) | Dec 26, 2023 |
| HP            | 15 Notebook PC              | [0b603c74cf](https://linux-hardware.org/?probe=0b603c74cf) | Dec 26, 2023 |
| Dell          | XPS 15 9530                 | [cf1f0e7284](https://linux-hardware.org/?probe=cf1f0e7284) | Dec 26, 2023 |
| HP            | Pavilion dv6                | [5d0a172259](https://linux-hardware.org/?probe=5d0a172259) | Dec 26, 2023 |
| Unknown       | Unknown                     | [ef974b90c4](https://linux-hardware.org/?probe=ef974b90c4) | Dec 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [59e540836e](https://linux-hardware.org/?probe=59e540836e) | Dec 25, 2023 |
| Dell          | Latitude E6520              | [f550eac568](https://linux-hardware.org/?probe=f550eac568) | Dec 25, 2023 |
| Apple         | MacBookAir9,1               | [4997b8894d](https://linux-hardware.org/?probe=4997b8894d) | Dec 25, 2023 |
| HP            | EliteBook 840 G3            | [c395b5cd61](https://linux-hardware.org/?probe=c395b5cd61) | Dec 25, 2023 |
| Valve         | Galileo                     | [99c3c24140](https://linux-hardware.org/?probe=99c3c24140) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [f385a26e94](https://linux-hardware.org/?probe=f385a26e94) | Dec 25, 2023 |
| Lenovo        | G50-45 80E3                 | [884a852341](https://linux-hardware.org/?probe=884a852341) | Dec 25, 2023 |
| HP            | EliteBook 840 G5            | [744adae48d](https://linux-hardware.org/?probe=744adae48d) | Dec 25, 2023 |
| Notebook      | P95_HR                      | [d7283146d3](https://linux-hardware.org/?probe=d7283146d3) | Dec 25, 2023 |
| MSI           | Delta 15 A5EFK              | [af7c011930](https://linux-hardware.org/?probe=af7c011930) | Dec 25, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5HM0... | [79bfce6143](https://linux-hardware.org/?probe=79bfce6143) | Dec 25, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5HM0... | [b30f25ba57](https://linux-hardware.org/?probe=b30f25ba57) | Dec 25, 2023 |
| Apple         | MacBookPro16,2              | [c52e64f2ed](https://linux-hardware.org/?probe=c52e64f2ed) | Dec 25, 2023 |
| Dell          | Inspiron 3531               | [6f8e8606e2](https://linux-hardware.org/?probe=6f8e8606e2) | Dec 25, 2023 |
| Dell          | Latitude E6420              | [ffcec7155a](https://linux-hardware.org/?probe=ffcec7155a) | Dec 25, 2023 |
| HP            | Pavilion dv7                | [72ee76c262](https://linux-hardware.org/?probe=72ee76c262) | Dec 25, 2023 |
| HP            | EliteBook Folio 9470m       | [e1f5de21d1](https://linux-hardware.org/?probe=e1f5de21d1) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [e7d00bdca8](https://linux-hardware.org/?probe=e7d00bdca8) | Dec 25, 2023 |
| HP            | ENVY dv6                    | [7feb95b534](https://linux-hardware.org/?probe=7feb95b534) | Dec 25, 2023 |
| Google        | Madoo                       | [14e757fdb4](https://linux-hardware.org/?probe=14e757fdb4) | Dec 24, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3dcd1787be](https://linux-hardware.org/?probe=3dcd1787be) | Dec 24, 2023 |
| ASUSTek       | X75A                        | [3af5f7aed7](https://linux-hardware.org/?probe=3af5f7aed7) | Dec 24, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [8e4881d45c](https://linux-hardware.org/?probe=8e4881d45c) | Dec 24, 2023 |
| HP            | ProBook 650 G2              | [4d94b390ca](https://linux-hardware.org/?probe=4d94b390ca) | Dec 24, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [65afff0074](https://linux-hardware.org/?probe=65afff0074) | Dec 24, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [496c9bc11f](https://linux-hardware.org/?probe=496c9bc11f) | Dec 24, 2023 |
| HP            | Laptop 14-dk0xxx            | [0762c25f51](https://linux-hardware.org/?probe=0762c25f51) | Dec 24, 2023 |
| Dell          | Latitude 7390               | [6b0dcd03de](https://linux-hardware.org/?probe=6b0dcd03de) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [5206fdfe7e](https://linux-hardware.org/?probe=5206fdfe7e) | Dec 24, 2023 |
| Apple         | MacBookPro9,2               | [976944381c](https://linux-hardware.org/?probe=976944381c) | Dec 24, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [d41bca7300](https://linux-hardware.org/?probe=d41bca7300) | Dec 24, 2023 |
| Lenovo        | ThinkPad E460 20ET0016US    | [96959ec0a3](https://linux-hardware.org/?probe=96959ec0a3) | Dec 24, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [8080c75b27](https://linux-hardware.org/?probe=8080c75b27) | Dec 24, 2023 |
| ASUSTek       | G75VW                       | [63fa97bd36](https://linux-hardware.org/?probe=63fa97bd36) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Apple         | MacBookAir7,1               | [f666ec3927](https://linux-hardware.org/?probe=f666ec3927) | Dec 24, 2023 |
| Dell          | Inspiron 5720               | [bcb6745ac2](https://linux-hardware.org/?probe=bcb6745ac2) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| Toshiba       | Satellite A205              | [c3680bfd29](https://linux-hardware.org/?probe=c3680bfd29) | Dec 24, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [f8abeb2607](https://linux-hardware.org/?probe=f8abeb2607) | Dec 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [29b4b5a349](https://linux-hardware.org/?probe=29b4b5a349) | Dec 24, 2023 |
| HP            | Pavilion g7                 | [bbe3fb1914](https://linux-hardware.org/?probe=bbe3fb1914) | Dec 24, 2023 |
| HP            | Notebook                    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| Dell          | Precision 3560              | [b945ab8339](https://linux-hardware.org/?probe=b945ab8339) | Dec 24, 2023 |
| Valve         | Galileo                     | [aa141b8ea2](https://linux-hardware.org/?probe=aa141b8ea2) | Dec 24, 2023 |
| Apple         | MacBookAir6,2               | [a3af8ee68a](https://linux-hardware.org/?probe=a3af8ee68a) | Dec 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [31291c7bc9](https://linux-hardware.org/?probe=31291c7bc9) | Dec 24, 2023 |
| Lenovo        | ThinkPad T520 424049U       | [c393fb64e3](https://linux-hardware.org/?probe=c393fb64e3) | Dec 24, 2023 |
| Acer          | Aspire A515-43              | [922518c025](https://linux-hardware.org/?probe=922518c025) | Dec 23, 2023 |
| Apple         | MacBookPro9,1               | [a70e7da743](https://linux-hardware.org/?probe=a70e7da743) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [67caa6c117](https://linux-hardware.org/?probe=67caa6c117) | Dec 23, 2023 |
| HP            | ZBook 17 G5                 | [ad6c489ffc](https://linux-hardware.org/?probe=ad6c489ffc) | Dec 23, 2023 |
| Lenovo        | ThinkPad T520 424049U       | [d800424ece](https://linux-hardware.org/?probe=d800424ece) | Dec 23, 2023 |
| ASUSTek       | GL503VM                     | [dfedaea706](https://linux-hardware.org/?probe=dfedaea706) | Dec 23, 2023 |
| ASUSTek       | GL503VM                     | [05b212db99](https://linux-hardware.org/?probe=05b212db99) | Dec 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ef18e09b69](https://linux-hardware.org/?probe=ef18e09b69) | Dec 23, 2023 |
| IBM           | ThinkPad R50e 1842QDU       | [32a349ab97](https://linux-hardware.org/?probe=32a349ab97) | Dec 23, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [c2681f33cc](https://linux-hardware.org/?probe=c2681f33cc) | Dec 23, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5c4d1c7d64](https://linux-hardware.org/?probe=5c4d1c7d64) | Dec 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [95adcc5c56](https://linux-hardware.org/?probe=95adcc5c56) | Dec 23, 2023 |
| Valve         | Jupiter                     | [6fd8f41741](https://linux-hardware.org/?probe=6fd8f41741) | Dec 23, 2023 |
| Dell          | Latitude E6330              | [afca8c73b2](https://linux-hardware.org/?probe=afca8c73b2) | Dec 23, 2023 |
| Dell          | System XPS L322X            | [6b050ff1c8](https://linux-hardware.org/?probe=6b050ff1c8) | Dec 23, 2023 |
| Sony          | VPCF215FX                   | [1a79c8b60f](https://linux-hardware.org/?probe=1a79c8b60f) | Dec 23, 2023 |
| System76      | Serval WS                   | [92d124a8aa](https://linux-hardware.org/?probe=92d124a8aa) | Dec 23, 2023 |
| GPU Compan... | GWTN116-3                   | [89366f9a48](https://linux-hardware.org/?probe=89366f9a48) | Dec 23, 2023 |
| ASUSTek       | X555LAB                     | [6a3b9f5bb2](https://linux-hardware.org/?probe=6a3b9f5bb2) | Dec 23, 2023 |
| HP            | Pavilion dv6                | [c4a6b58303](https://linux-hardware.org/?probe=c4a6b58303) | Dec 23, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [1ace47e8fd](https://linux-hardware.org/?probe=1ace47e8fd) | Dec 23, 2023 |
| ATARI         | VCS 800 Black Walnut        | [34456982d3](https://linux-hardware.org/?probe=34456982d3) | Dec 23, 2023 |
| Dell          | Latitude E6400              | [1a10fd9a2e](https://linux-hardware.org/?probe=1a10fd9a2e) | Dec 23, 2023 |
| System76      | Gazelle                     | [6671df79bd](https://linux-hardware.org/?probe=6671df79bd) | Dec 23, 2023 |
| System76      | Serval WS                   | [a250c12d1d](https://linux-hardware.org/?probe=a250c12d1d) | Dec 23, 2023 |
| Apple         | MacBookPro9,1               | [e3576ca49c](https://linux-hardware.org/?probe=e3576ca49c) | Dec 23, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [6ba8bb7550](https://linux-hardware.org/?probe=6ba8bb7550) | Dec 23, 2023 |
| Google        | Reks                        | [52375a57c5](https://linux-hardware.org/?probe=52375a57c5) | Dec 22, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | [961dddc49e](https://linux-hardware.org/?probe=961dddc49e) | Dec 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [f5f4795192](https://linux-hardware.org/?probe=f5f4795192) | Dec 22, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [937842fe5d](https://linux-hardware.org/?probe=937842fe5d) | Dec 22, 2023 |
| HP            | G62                         | [9f6a13bc50](https://linux-hardware.org/?probe=9f6a13bc50) | Dec 22, 2023 |
| Valve         | Jupiter                     | [482500f7b0](https://linux-hardware.org/?probe=482500f7b0) | Dec 22, 2023 |
| ASUSTek       | X75A                        | [ed3c88f944](https://linux-hardware.org/?probe=ed3c88f944) | Dec 22, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [10c32df82e](https://linux-hardware.org/?probe=10c32df82e) | Dec 22, 2023 |
| Dell          | Latitude 5580               | [e20360557a](https://linux-hardware.org/?probe=e20360557a) | Dec 22, 2023 |
| Valve         | Jupiter                     | [4899962b6a](https://linux-hardware.org/?probe=4899962b6a) | Dec 22, 2023 |
| Dell          | Latitude 5414               | [9b02eedb05](https://linux-hardware.org/?probe=9b02eedb05) | Dec 22, 2023 |
| Toshiba       | Satellite C55D-B            | [d705d8ee57](https://linux-hardware.org/?probe=d705d8ee57) | Dec 22, 2023 |
| Google        | Garg                        | [05bbd9f9f8](https://linux-hardware.org/?probe=05bbd9f9f8) | Dec 22, 2023 |
| Eluktronic... | MECH-17                     | [0a69b2e084](https://linux-hardware.org/?probe=0a69b2e084) | Dec 22, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [684b42a95a](https://linux-hardware.org/?probe=684b42a95a) | Dec 22, 2023 |
| Dell          | Precision 5480              | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| LG Electro... | 17U70Q-P.AAS7U1             | [8846a0ac06](https://linux-hardware.org/?probe=8846a0ac06) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6f60c08653](https://linux-hardware.org/?probe=6f60c08653) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [cf835775a4](https://linux-hardware.org/?probe=cf835775a4) | Dec 21, 2023 |
| Lenovo        | ThinkPad T420 4177QGU       | [7ec167a926](https://linux-hardware.org/?probe=7ec167a926) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [c5c9d669ae](https://linux-hardware.org/?probe=c5c9d669ae) | Dec 21, 2023 |
| Apple         | MacBookPro16,1              | [d67a62b447](https://linux-hardware.org/?probe=d67a62b447) | Dec 21, 2023 |
| ASUSTek       | X75A                        | [6d9c65c8ac](https://linux-hardware.org/?probe=6d9c65c8ac) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [972314af13](https://linux-hardware.org/?probe=972314af13) | Dec 21, 2023 |
| Google        | Reks                        | [9a6f15c5d9](https://linux-hardware.org/?probe=9a6f15c5d9) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK T5010              | [27e7d6f705](https://linux-hardware.org/?probe=27e7d6f705) | Dec 21, 2023 |
| HP            | Pavilion dv7                | [ef719917ef](https://linux-hardware.org/?probe=ef719917ef) | Dec 21, 2023 |
| Lenovo        | ThinkPad T440 20B6005BUS    | [d699475273](https://linux-hardware.org/?probe=d699475273) | Dec 21, 2023 |
| Lenovo        | ThinkPad T440 20B70048US    | [f937778ee0](https://linux-hardware.org/?probe=f937778ee0) | Dec 21, 2023 |
| HP            | Pavilion dv7                | [cd7f768fe8](https://linux-hardware.org/?probe=cd7f768fe8) | Dec 21, 2023 |
| Toshiba       | Satellite L15-B             | [0b1e126b9b](https://linux-hardware.org/?probe=0b1e126b9b) | Dec 21, 2023 |
| Acer          | Aspire M5-581T              | [c99da67d31](https://linux-hardware.org/?probe=c99da67d31) | Dec 21, 2023 |
| Dell          | Latitude E6520              | [9e16e8b2a6](https://linux-hardware.org/?probe=9e16e8b2a6) | Dec 21, 2023 |
| HP            | ProBook 445 G7              | [4153ae7cc6](https://linux-hardware.org/?probe=4153ae7cc6) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [03b86f8fd8](https://linux-hardware.org/?probe=03b86f8fd8) | Dec 21, 2023 |
| System76      | Adder WS                    | [d272c23e51](https://linux-hardware.org/?probe=d272c23e51) | Dec 21, 2023 |
| Acer          | Swift SF314-54              | [edc5223b9b](https://linux-hardware.org/?probe=edc5223b9b) | Dec 21, 2023 |
| Google        | Garg                        | [fb4804bee9](https://linux-hardware.org/?probe=fb4804bee9) | Dec 21, 2023 |
| Google        | Garg                        | [d2558e0746](https://linux-hardware.org/?probe=d2558e0746) | Dec 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [1e223a9ea1](https://linux-hardware.org/?probe=1e223a9ea1) | Dec 21, 2023 |
| MSI           | GF65 Thin 10SDR             | [73408e34a6](https://linux-hardware.org/?probe=73408e34a6) | Dec 21, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | [f5bb1db361](https://linux-hardware.org/?probe=f5bb1db361) | Dec 21, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [57d4ccc05e](https://linux-hardware.org/?probe=57d4ccc05e) | Dec 21, 2023 |
| Lenovo        | ThinkPad T490 20RY0002US    | [95dfdb9327](https://linux-hardware.org/?probe=95dfdb9327) | Dec 21, 2023 |
| Sony          | VGN-NW270F                  | [eee640a54d](https://linux-hardware.org/?probe=eee640a54d) | Dec 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [fb187c2fa4](https://linux-hardware.org/?probe=fb187c2fa4) | Dec 20, 2023 |
| Lenovo        | IdeaPad S340-15APITOUCH ... | [0eb3eaa1c6](https://linux-hardware.org/?probe=0eb3eaa1c6) | Dec 20, 2023 |
| Toshiba       | Satellite C850              | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| Dell          | XPS 15 9510                 | [107d6edb72](https://linux-hardware.org/?probe=107d6edb72) | Dec 20, 2023 |
| Toshiba       | Satellite C55D-B            | [dfd0e27118](https://linux-hardware.org/?probe=dfd0e27118) | Dec 20, 2023 |
| Lenovo        | ThinkPad T440 20B6005BUS    | [bf412b1477](https://linux-hardware.org/?probe=bf412b1477) | Dec 20, 2023 |
| Lenovo        | ThinkPad T440 20B70048US    | [d6a79599da](https://linux-hardware.org/?probe=d6a79599da) | Dec 20, 2023 |
| Google        | Garg                        | [0f05d3580a](https://linux-hardware.org/?probe=0f05d3580a) | Dec 20, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [e3dded7dc3](https://linux-hardware.org/?probe=e3dded7dc3) | Dec 20, 2023 |
| Dell          | Precision 5510              | [033bf69fdf](https://linux-hardware.org/?probe=033bf69fdf) | Dec 20, 2023 |
| Dell          | Precision 5510              | [a40fa883d2](https://linux-hardware.org/?probe=a40fa883d2) | Dec 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [44a01e07bb](https://linux-hardware.org/?probe=44a01e07bb) | Dec 20, 2023 |
| Valve         | Jupiter                     | [ceba2299c2](https://linux-hardware.org/?probe=ceba2299c2) | Dec 20, 2023 |
| System76      | Serval WS                   | [7475c97028](https://linux-hardware.org/?probe=7475c97028) | Dec 20, 2023 |
| Dell          | Inspiron 1750               | [508bf60ff7](https://linux-hardware.org/?probe=508bf60ff7) | Dec 20, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | [e6bc9160c8](https://linux-hardware.org/?probe=e6bc9160c8) | Dec 20, 2023 |
| HP            | Laptop 15-da0xxx            | [a2b93e4d4d](https://linux-hardware.org/?probe=a2b93e4d4d) | Dec 20, 2023 |
| Google        | Cave                        | [ec9d49335f](https://linux-hardware.org/?probe=ec9d49335f) | Dec 20, 2023 |
| ASUSTek       | X550LA                      | [fd673bac37](https://linux-hardware.org/?probe=fd673bac37) | Dec 20, 2023 |
| Dell          | Inspiron 3721               | [2fd8b3f8fc](https://linux-hardware.org/?probe=2fd8b3f8fc) | Dec 20, 2023 |
| Dell          | Latitude 3460               | [c3b4a00583](https://linux-hardware.org/?probe=c3b4a00583) | Dec 19, 2023 |
| Dell          | Latitude 3460               | [3b425238a6](https://linux-hardware.org/?probe=3b425238a6) | Dec 19, 2023 |
| Dell          | Latitude E5270              | [c25a5b1bc7](https://linux-hardware.org/?probe=c25a5b1bc7) | Dec 19, 2023 |
| Valve         | Jupiter                     | [feae313bc0](https://linux-hardware.org/?probe=feae313bc0) | Dec 19, 2023 |
| Google        | Swanky                      | [46b7f27873](https://linux-hardware.org/?probe=46b7f27873) | Dec 19, 2023 |
| System76      | Pangolin                    | [a0cf57c6d1](https://linux-hardware.org/?probe=a0cf57c6d1) | Dec 19, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [a074081eb1](https://linux-hardware.org/?probe=a074081eb1) | Dec 19, 2023 |
| HP            | Dev One Notebook PC         | [b10cd89445](https://linux-hardware.org/?probe=b10cd89445) | Dec 19, 2023 |
| HP            | Laptop 15-dw0xxx            | [4d59263eb3](https://linux-hardware.org/?probe=4d59263eb3) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e37edfc830](https://linux-hardware.org/?probe=e37edfc830) | Dec 19, 2023 |
| Dell          | XPS 13 9310                 | [3a4a73b5f1](https://linux-hardware.org/?probe=3a4a73b5f1) | Dec 19, 2023 |
| Dell          | Inspiron 3542               | [7d3f7e97ce](https://linux-hardware.org/?probe=7d3f7e97ce) | Dec 19, 2023 |
| Dell          | Inspiron 1545               | [fc8665de21](https://linux-hardware.org/?probe=fc8665de21) | Dec 18, 2023 |
| Lenovo        | ThinkPad T450s 20BX001LU... | [b3a6780db5](https://linux-hardware.org/?probe=b3a6780db5) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | Laptop 15-ef2xxx            | [f0d39c9ef3](https://linux-hardware.org/?probe=f0d39c9ef3) | Dec 18, 2023 |
| Acer          | Aspire A715-51G             | [1232ff1050](https://linux-hardware.org/?probe=1232ff1050) | Dec 18, 2023 |
| Dell          | Latitude 7490               | [6fe6e99364](https://linux-hardware.org/?probe=6fe6e99364) | Dec 18, 2023 |
| HP            | Pavilion dv6700             | [dd31f0d1ec](https://linux-hardware.org/?probe=dd31f0d1ec) | Dec 18, 2023 |
| Toshiba       | Satellite C55-A             | [6c0f2ad0c9](https://linux-hardware.org/?probe=6c0f2ad0c9) | Dec 18, 2023 |
| Valve         | Galileo                     | [b79c5fbf78](https://linux-hardware.org/?probe=b79c5fbf78) | Dec 18, 2023 |
| Toshiba       | Satellite C55-A             | [0ae780878c](https://linux-hardware.org/?probe=0ae780878c) | Dec 18, 2023 |
| ASUSTek       | X550LA                      | [759db70e03](https://linux-hardware.org/?probe=759db70e03) | Dec 18, 2023 |
| HP            | 15 Notebook PC              | [1293ea8b65](https://linux-hardware.org/?probe=1293ea8b65) | Dec 18, 2023 |
| Valve         | Jupiter                     | [b5b29d3c59](https://linux-hardware.org/?probe=b5b29d3c59) | Dec 18, 2023 |
| Acer          | Aspire 5349                 | [f81cd33147](https://linux-hardware.org/?probe=f81cd33147) | Dec 18, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [81ea786e13](https://linux-hardware.org/?probe=81ea786e13) | Dec 18, 2023 |
| Dell          | Latitude E6410              | [ad9c836840](https://linux-hardware.org/?probe=ad9c836840) | Dec 18, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [612482d238](https://linux-hardware.org/?probe=612482d238) | Dec 18, 2023 |
| Dell          | XPS 15 7590                 | [7e2afccdd6](https://linux-hardware.org/?probe=7e2afccdd6) | Dec 18, 2023 |
| Acer          | Nitro AN515-55              | [bdecd800b4](https://linux-hardware.org/?probe=bdecd800b4) | Dec 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [7b289201bc](https://linux-hardware.org/?probe=7b289201bc) | Dec 17, 2023 |
| HP            | Dev One Notebook PC         | [3c5fc22ea0](https://linux-hardware.org/?probe=3c5fc22ea0) | Dec 17, 2023 |
| Acer          | Aspire A315-51              | [4169b122de](https://linux-hardware.org/?probe=4169b122de) | Dec 17, 2023 |
| Valve         | Galileo                     | [c02b71450c](https://linux-hardware.org/?probe=c02b71450c) | Dec 17, 2023 |
| Valve         | Jupiter                     | [0cda5b9141](https://linux-hardware.org/?probe=0cda5b9141) | Dec 17, 2023 |
| Valve         | Galileo                     | [355d2e1a38](https://linux-hardware.org/?probe=355d2e1a38) | Dec 17, 2023 |
| HP            | Laptop 17-cp0xxx            | [341ecee745](https://linux-hardware.org/?probe=341ecee745) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [07c7da687a](https://linux-hardware.org/?probe=07c7da687a) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [e6ad27a4dd](https://linux-hardware.org/?probe=e6ad27a4dd) | Dec 17, 2023 |
| HP            | Laptop 15-bw0xx             | [91a9e2e8c4](https://linux-hardware.org/?probe=91a9e2e8c4) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | [efc671c7c2](https://linux-hardware.org/?probe=efc671c7c2) | Dec 17, 2023 |
| MSI           | PE70 6QE                    | [c99e0d38ea](https://linux-hardware.org/?probe=c99e0d38ea) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [b8d81eb2c9](https://linux-hardware.org/?probe=b8d81eb2c9) | Dec 17, 2023 |
| Acer          | Aspire M5-583P              | [34b9748756](https://linux-hardware.org/?probe=34b9748756) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [19d43a41f8](https://linux-hardware.org/?probe=19d43a41f8) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| HP            | Notebook                    | [88e0b592ea](https://linux-hardware.org/?probe=88e0b592ea) | Dec 17, 2023 |
| Valve         | Jupiter                     | [241ed280af](https://linux-hardware.org/?probe=241ed280af) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U727               | [dceda9b2a1](https://linux-hardware.org/?probe=dceda9b2a1) | Dec 17, 2023 |
| HP            | Pavilion dv6                | [dd14fcb656](https://linux-hardware.org/?probe=dd14fcb656) | Dec 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ead7baed80](https://linux-hardware.org/?probe=ead7baed80) | Dec 17, 2023 |
| ASUSTek       | S550CB                      | [20c9c415c9](https://linux-hardware.org/?probe=20c9c415c9) | Dec 17, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [c93d5be9d6](https://linux-hardware.org/?probe=c93d5be9d6) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | [3a08b4d1ea](https://linux-hardware.org/?probe=3a08b4d1ea) | Dec 17, 2023 |
| Dell          | Inspiron 3542               | [6b3cd841db](https://linux-hardware.org/?probe=6b3cd841db) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | [1c0bbe412c](https://linux-hardware.org/?probe=1c0bbe412c) | Dec 17, 2023 |
| Dell          | Latitude E6430              | [13af5c2dc4](https://linux-hardware.org/?probe=13af5c2dc4) | Dec 17, 2023 |
| LG Electro... | 16Z90R-A.ADC8U1             | [5ae89dd818](https://linux-hardware.org/?probe=5ae89dd818) | Dec 16, 2023 |
| Dell          | Latitude 7350               | [ab9a873c1e](https://linux-hardware.org/?probe=ab9a873c1e) | Dec 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [9e217a08be](https://linux-hardware.org/?probe=9e217a08be) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| Lenovo        | B50-80 80LT                 | [ea695bd9c5](https://linux-hardware.org/?probe=ea695bd9c5) | Dec 16, 2023 |
| Lenovo        | B50-80 80LT                 | [40d547e3f5](https://linux-hardware.org/?probe=40d547e3f5) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [c3c947f23f](https://linux-hardware.org/?probe=c3c947f23f) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [db30b82451](https://linux-hardware.org/?probe=db30b82451) | Dec 16, 2023 |
| Lenovo        | IdeaPad S400 20195          | [f4c6ceeca3](https://linux-hardware.org/?probe=f4c6ceeca3) | Dec 16, 2023 |
| Acer          | Aspire A515-56T             | [9579acc8a0](https://linux-hardware.org/?probe=9579acc8a0) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [7b3d7fcb72](https://linux-hardware.org/?probe=7b3d7fcb72) | Dec 16, 2023 |
| System76      | Bonobo WS                   | [22f5ef6fce](https://linux-hardware.org/?probe=22f5ef6fce) | Dec 16, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [251ac554a9](https://linux-hardware.org/?probe=251ac554a9) | Dec 16, 2023 |
| MSI           | GP62MVR 7RFX                | [fcb56f79d6](https://linux-hardware.org/?probe=fcb56f79d6) | Dec 16, 2023 |
| Valve         | Jupiter                     | [dfdfbefee5](https://linux-hardware.org/?probe=dfdfbefee5) | Dec 16, 2023 |
| Dell          | Precision 7510              | [c70e7da2e8](https://linux-hardware.org/?probe=c70e7da2e8) | Dec 16, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [88312d177f](https://linux-hardware.org/?probe=88312d177f) | Dec 16, 2023 |
| HP            | Notebook                    | [5bbbe8e356](https://linux-hardware.org/?probe=5bbbe8e356) | Dec 16, 2023 |
| ASUSTek       | Q524UQ                      | [8466629595](https://linux-hardware.org/?probe=8466629595) | Dec 16, 2023 |
| Dell          | Inspiron 1545               | [3f47a63c82](https://linux-hardware.org/?probe=3f47a63c82) | Dec 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [10f1017f04](https://linux-hardware.org/?probe=10f1017f04) | Dec 16, 2023 |
| Dell          | Inspiron 5447               | [0e868b4cba](https://linux-hardware.org/?probe=0e868b4cba) | Dec 15, 2023 |
| Dell          | Inspiron 5447               | [60320e4007](https://linux-hardware.org/?probe=60320e4007) | Dec 15, 2023 |
| ASUSTek       | X555LAB                     | [199ffa8815](https://linux-hardware.org/?probe=199ffa8815) | Dec 15, 2023 |
| Valve         | Jupiter                     | [ee39964f52](https://linux-hardware.org/?probe=ee39964f52) | Dec 15, 2023 |
| Apple         | MacBookPro5,3               | [f882c29faa](https://linux-hardware.org/?probe=f882c29faa) | Dec 15, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e03062f53d](https://linux-hardware.org/?probe=e03062f53d) | Dec 15, 2023 |
| HP            | Notebook                    | [26c91fe276](https://linux-hardware.org/?probe=26c91fe276) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | [ec4a48125c](https://linux-hardware.org/?probe=ec4a48125c) | Dec 15, 2023 |
| HP            | EliteBook 745 G3            | [d43271b873](https://linux-hardware.org/?probe=d43271b873) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| Dell          | Vostro 7500                 | [65dfb6fec4](https://linux-hardware.org/?probe=65dfb6fec4) | Dec 15, 2023 |
| HP            | Stream Laptop 14-DS0xxx     | [3e26902ac1](https://linux-hardware.org/?probe=3e26902ac1) | Dec 15, 2023 |
| Valve         | Jupiter                     | [4e56fce432](https://linux-hardware.org/?probe=4e56fce432) | Dec 15, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6a2633018c](https://linux-hardware.org/?probe=6a2633018c) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4cb7a5528b](https://linux-hardware.org/?probe=4cb7a5528b) | Dec 15, 2023 |
| Apple         | MacBookPro5,3               | [066c7e2b1a](https://linux-hardware.org/?probe=066c7e2b1a) | Dec 15, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [b342bc9627](https://linux-hardware.org/?probe=b342bc9627) | Dec 14, 2023 |
| Apple         | MacBookPro10,2              | [435c0197d1](https://linux-hardware.org/?probe=435c0197d1) | Dec 14, 2023 |
| Dell          | Latitude E5450              | [b616faa68f](https://linux-hardware.org/?probe=b616faa68f) | Dec 14, 2023 |
| Apple         | MacBookAir9,1               | [6cadf8d04e](https://linux-hardware.org/?probe=6cadf8d04e) | Dec 14, 2023 |
| Lenovo        | ThinkPad T450 20BUS50Q16    | [789b2d6914](https://linux-hardware.org/?probe=789b2d6914) | Dec 14, 2023 |
| Apple         | MacBookAir7,2               | [09a184f2e4](https://linux-hardware.org/?probe=09a184f2e4) | Dec 14, 2023 |
| Dell          | Inspiron 5759               | [9caa48ce75](https://linux-hardware.org/?probe=9caa48ce75) | Dec 14, 2023 |
| Apple         | MacBookPro10,2              | [b95f42f691](https://linux-hardware.org/?probe=b95f42f691) | Dec 14, 2023 |
| HP            | ProBook 650 G1              | [f58535cbfe](https://linux-hardware.org/?probe=f58535cbfe) | Dec 14, 2023 |
| HP            | Laptop 17-by4xxx            | [bb89121e0c](https://linux-hardware.org/?probe=bb89121e0c) | Dec 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6855d17ce1](https://linux-hardware.org/?probe=6855d17ce1) | Dec 14, 2023 |
| Dell          | Precision 5520              | [b3ea29b5a2](https://linux-hardware.org/?probe=b3ea29b5a2) | Dec 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4919d10355](https://linux-hardware.org/?probe=4919d10355) | Dec 14, 2023 |
| Valve         | Galileo                     | [adb5dc0f2d](https://linux-hardware.org/?probe=adb5dc0f2d) | Dec 14, 2023 |
| Dell          | Latitude 5590               | [c52c1d4f2e](https://linux-hardware.org/?probe=c52c1d4f2e) | Dec 14, 2023 |
| Valve         | Jupiter                     | [c2879ac10a](https://linux-hardware.org/?probe=c2879ac10a) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [0ece599b11](https://linux-hardware.org/?probe=0ece599b11) | Dec 14, 2023 |
| HP            | ProBook 4540s               | [24875256cd](https://linux-hardware.org/?probe=24875256cd) | Dec 14, 2023 |
| A-DATA Tec... | XENIA 14                    | [ebbefc4570](https://linux-hardware.org/?probe=ebbefc4570) | Dec 14, 2023 |
| Lenovo        | Flex 2 Pro-15               | [da278da4b6](https://linux-hardware.org/?probe=da278da4b6) | Dec 13, 2023 |
| Valve         | Jupiter                     | [4e38f77c8d](https://linux-hardware.org/?probe=4e38f77c8d) | Dec 13, 2023 |
| ASUSTek       | X75A1                       | [e7d274ca96](https://linux-hardware.org/?probe=e7d274ca96) | Dec 13, 2023 |
| Valve         | Galileo                     | [719db5099f](https://linux-hardware.org/?probe=719db5099f) | Dec 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [05ff735f51](https://linux-hardware.org/?probe=05ff735f51) | Dec 13, 2023 |
| Unknown       | Unknown                     | [4517e8a60b](https://linux-hardware.org/?probe=4517e8a60b) | Dec 13, 2023 |
| Dell          | Latitude 5424 Rugged        | [ce56e420fc](https://linux-hardware.org/?probe=ce56e420fc) | Dec 13, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| Acer          | Aspire 7740                 | [2122676b51](https://linux-hardware.org/?probe=2122676b51) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [6a742a5308](https://linux-hardware.org/?probe=6a742a5308) | Dec 13, 2023 |
| HP            | Pavilion dv6                | [ebc05992b6](https://linux-hardware.org/?probe=ebc05992b6) | Dec 13, 2023 |
| MSI           | GL62M 7RD                   | [fd87c3c373](https://linux-hardware.org/?probe=fd87c3c373) | Dec 12, 2023 |
| HC            | HCAR357-MI                  | [daaf3e0f5f](https://linux-hardware.org/?probe=daaf3e0f5f) | Dec 12, 2023 |
| Lenovo        | ThinkPad E490 20N9S13000    | [d93593921b](https://linux-hardware.org/?probe=d93593921b) | Dec 12, 2023 |
| Acer          | Aspire E1-522               | [e438bd7bc2](https://linux-hardware.org/?probe=e438bd7bc2) | Dec 12, 2023 |
| Acer          | Aspire E1-522               | [0ba0422412](https://linux-hardware.org/?probe=0ba0422412) | Dec 12, 2023 |
| Dell          | G7 7700                     | [9d4e191ab5](https://linux-hardware.org/?probe=9d4e191ab5) | Dec 12, 2023 |
| GPU Compan... | GWTC116-2                   | [10e35dbb2a](https://linux-hardware.org/?probe=10e35dbb2a) | Dec 12, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [84fd94c616](https://linux-hardware.org/?probe=84fd94c616) | Dec 12, 2023 |
| Apple         | MacBookPro11,2              | [cc03da082a](https://linux-hardware.org/?probe=cc03da082a) | Dec 12, 2023 |
| Alienware     | M17x                        | [da64c97fa8](https://linux-hardware.org/?probe=da64c97fa8) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [e617c5041f](https://linux-hardware.org/?probe=e617c5041f) | Dec 12, 2023 |
| Acer          | Aspire E5-576               | [72fc5247a6](https://linux-hardware.org/?probe=72fc5247a6) | Dec 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8d9963d61d](https://linux-hardware.org/?probe=8d9963d61d) | Dec 11, 2023 |
| Valve         | Jupiter                     | [3f0800eb70](https://linux-hardware.org/?probe=3f0800eb70) | Dec 11, 2023 |
| Toshiba       | Satellite A665D             | [b8fc9ba683](https://linux-hardware.org/?probe=b8fc9ba683) | Dec 11, 2023 |
| Dell          | Latitude 7290               | [89a710e338](https://linux-hardware.org/?probe=89a710e338) | Dec 11, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dac56d16cd](https://linux-hardware.org/?probe=dac56d16cd) | Dec 11, 2023 |
| Valve         | Galileo                     | [494f369350](https://linux-hardware.org/?probe=494f369350) | Dec 11, 2023 |
| Dell          | XPS 15 9520                 | [e0f273e27d](https://linux-hardware.org/?probe=e0f273e27d) | Dec 11, 2023 |
| Valve         | Jupiter                     | [449a971a56](https://linux-hardware.org/?probe=449a971a56) | Dec 11, 2023 |
| Dell          | Latitude 5590               | [ebdbfc1740](https://linux-hardware.org/?probe=ebdbfc1740) | Dec 11, 2023 |
| Dell          | Inspiron 5755               | [4b70400e52](https://linux-hardware.org/?probe=4b70400e52) | Dec 11, 2023 |
| ASUSTek       | U52F                        | [5bdf8ec184](https://linux-hardware.org/?probe=5bdf8ec184) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [be5332c927](https://linux-hardware.org/?probe=be5332c927) | Dec 11, 2023 |
| Dell          | Precision M6500             | [5b287ea21f](https://linux-hardware.org/?probe=5b287ea21f) | Dec 11, 2023 |
| Apple         | MacBookPro11,1              | [539d1d09fe](https://linux-hardware.org/?probe=539d1d09fe) | Dec 11, 2023 |
| Lenovo        | ThinkPad T470s 20HF005NU... | [0d9a5839df](https://linux-hardware.org/?probe=0d9a5839df) | Dec 11, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [c2dd869dcf](https://linux-hardware.org/?probe=c2dd869dcf) | Dec 10, 2023 |
| System76      | Lemur Pro                   | [05062ae2dd](https://linux-hardware.org/?probe=05062ae2dd) | Dec 10, 2023 |
| Dell          | XPS 15 9510                 | [b88a7e6159](https://linux-hardware.org/?probe=b88a7e6159) | Dec 10, 2023 |
| Dell          | Precision 3540              | [b4316bc7e3](https://linux-hardware.org/?probe=b4316bc7e3) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [96b05f5be6](https://linux-hardware.org/?probe=96b05f5be6) | Dec 10, 2023 |
| Dell          | Precision 3550              | [0235a02831](https://linux-hardware.org/?probe=0235a02831) | Dec 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e7febd26d4](https://linux-hardware.org/?probe=e7febd26d4) | Dec 10, 2023 |
| Lenovo        | ThinkPad T430s 2356C45      | [a76e3d7e43](https://linux-hardware.org/?probe=a76e3d7e43) | Dec 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9c86c02e7](https://linux-hardware.org/?probe=b9c86c02e7) | Dec 10, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [1709e5c519](https://linux-hardware.org/?probe=1709e5c519) | Dec 10, 2023 |
| HP            | Laptop 15-da0xxx            | [2722000dd3](https://linux-hardware.org/?probe=2722000dd3) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60b75920a4](https://linux-hardware.org/?probe=60b75920a4) | Dec 10, 2023 |
| HP            | Pavilion 17                 | [6822e2b412](https://linux-hardware.org/?probe=6822e2b412) | Dec 10, 2023 |
| Dell          | Precision 5480              | [e2ef5d90ca](https://linux-hardware.org/?probe=e2ef5d90ca) | Dec 10, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [c753b49018](https://linux-hardware.org/?probe=c753b49018) | Dec 10, 2023 |
| Acer          | Nitro AN515-58              | [9939fe96d2](https://linux-hardware.org/?probe=9939fe96d2) | Dec 10, 2023 |
| Acer          | Aspire A515-54              | [d3869522c0](https://linux-hardware.org/?probe=d3869522c0) | Dec 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| HP            | Laptop 15-bw0xx             | [69ebcd04b9](https://linux-hardware.org/?probe=69ebcd04b9) | Dec 10, 2023 |
| Apple         | MacBookPro8,3               | [08a4bea1d7](https://linux-hardware.org/?probe=08a4bea1d7) | Dec 09, 2023 |
| Google        | Gallop                      | [83663e2906](https://linux-hardware.org/?probe=83663e2906) | Dec 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e7b5bdd470](https://linux-hardware.org/?probe=e7b5bdd470) | Dec 09, 2023 |
| HP            | EliteBook 8560w             | [0de5475eb8](https://linux-hardware.org/?probe=0de5475eb8) | Dec 09, 2023 |
| Dell          | Latitude 7490               | [bbbf303467](https://linux-hardware.org/?probe=bbbf303467) | Dec 09, 2023 |
| BOSGAME       | DNB20 series                | [d825ed757b](https://linux-hardware.org/?probe=d825ed757b) | Dec 09, 2023 |
| Dell          | G15 5515                    | [d815dec1af](https://linux-hardware.org/?probe=d815dec1af) | Dec 09, 2023 |
| Unknown       | Unknown                     | [185aa8e9fe](https://linux-hardware.org/?probe=185aa8e9fe) | Dec 09, 2023 |
| Apple         | MacBookPro12,1              | [9d633902a0](https://linux-hardware.org/?probe=9d633902a0) | Dec 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e800d95054](https://linux-hardware.org/?probe=e800d95054) | Dec 09, 2023 |
| Lenovo        | ThinkPad T60 1952AP2        | [803ecc2001](https://linux-hardware.org/?probe=803ecc2001) | Dec 09, 2023 |
| Toshiba       | QOSMIO X770                 | [945c57d421](https://linux-hardware.org/?probe=945c57d421) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [051769648f](https://linux-hardware.org/?probe=051769648f) | Dec 09, 2023 |
| Lenovo        | ThinkPad X220 4290B19       | [1515bfc49e](https://linux-hardware.org/?probe=1515bfc49e) | Dec 09, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [490ad0881a](https://linux-hardware.org/?probe=490ad0881a) | Dec 09, 2023 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [4c18329d9d](https://linux-hardware.org/?probe=4c18329d9d) | Dec 09, 2023 |
| HP            | Laptop 15-da0xxx            | [4106c6dbcf](https://linux-hardware.org/?probe=4106c6dbcf) | Dec 09, 2023 |
| Dell          | Precision 3550              | [a3be7ab761](https://linux-hardware.org/?probe=a3be7ab761) | Dec 09, 2023 |
| Valve         | Jupiter                     | [c40a4f6672](https://linux-hardware.org/?probe=c40a4f6672) | Dec 08, 2023 |
| HP            | Laptop 15-bw0xx             | [b00663cde8](https://linux-hardware.org/?probe=b00663cde8) | Dec 08, 2023 |
| ASUSTek       | TP501UAM                    | [3465474829](https://linux-hardware.org/?probe=3465474829) | Dec 08, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [edabe3eb37](https://linux-hardware.org/?probe=edabe3eb37) | Dec 08, 2023 |
| Toshiba       | Satellite A665D             | [7d646d3dbd](https://linux-hardware.org/?probe=7d646d3dbd) | Dec 08, 2023 |
| Dell          | Latitude E7470              | [81a17083f6](https://linux-hardware.org/?probe=81a17083f6) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [6cd48c055d](https://linux-hardware.org/?probe=6cd48c055d) | Dec 08, 2023 |
| MSI           | Katana GF76 11UD            | [a489e0db56](https://linux-hardware.org/?probe=a489e0db56) | Dec 08, 2023 |
| Panasonic     | CF-31JHG8M1M                | [9e99acdb69](https://linux-hardware.org/?probe=9e99acdb69) | Dec 08, 2023 |
| Dell          | Latitude E5470              | [cea78b64d4](https://linux-hardware.org/?probe=cea78b64d4) | Dec 08, 2023 |
| MSI           | Katana GF76 11UD            | [0f09b2440c](https://linux-hardware.org/?probe=0f09b2440c) | Dec 08, 2023 |
| Valve         | Galileo                     | [0eacb54dca](https://linux-hardware.org/?probe=0eacb54dca) | Dec 08, 2023 |
| Alienware     | 17 R3                       | [b426716979](https://linux-hardware.org/?probe=b426716979) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| Gateway       | NV57H                       | [8e41b1ac70](https://linux-hardware.org/?probe=8e41b1ac70) | Dec 08, 2023 |
| Lenovo        | ThinkPad T60 1952AP2        | [90a7c09cb5](https://linux-hardware.org/?probe=90a7c09cb5) | Dec 08, 2023 |
| Dell          | Precision M4700             | [54abe2ce35](https://linux-hardware.org/?probe=54abe2ce35) | Dec 08, 2023 |
| HP            | Pavilion dv6                | [e6522f1c77](https://linux-hardware.org/?probe=e6522f1c77) | Dec 08, 2023 |
| HP            | 15 Notebook PC              | [35b7f5d288](https://linux-hardware.org/?probe=35b7f5d288) | Dec 08, 2023 |
| Valve         | Jupiter                     | [dfa143c1c0](https://linux-hardware.org/?probe=dfa143c1c0) | Dec 08, 2023 |
| Alienware     | x15 R1                      | [08aa034a6d](https://linux-hardware.org/?probe=08aa034a6d) | Dec 08, 2023 |
| Adreamer      | Mybook PN1308P              | [e2dba2aff0](https://linux-hardware.org/?probe=e2dba2aff0) | Dec 08, 2023 |
| ASUSTek       | G750JX                      | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f76b4716d](https://linux-hardware.org/?probe=7f76b4716d) | Dec 08, 2023 |
| Dell          | G7 7700                     | [aa754020ce](https://linux-hardware.org/?probe=aa754020ce) | Dec 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [529932bcd4](https://linux-hardware.org/?probe=529932bcd4) | Dec 08, 2023 |
| HP            | 15 Notebook PC              | [37a360ec8a](https://linux-hardware.org/?probe=37a360ec8a) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0a3a227554](https://linux-hardware.org/?probe=0a3a227554) | Dec 08, 2023 |
| Valve         | Galileo                     | [f72b98880f](https://linux-hardware.org/?probe=f72b98880f) | Dec 07, 2023 |
| Sony          | VPCEB25FX                   | [f2d99590ca](https://linux-hardware.org/?probe=f2d99590ca) | Dec 07, 2023 |
| Lenovo        | ThinkPad T430 23498Y3       | [5382654b9b](https://linux-hardware.org/?probe=5382654b9b) | Dec 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c37147ae36](https://linux-hardware.org/?probe=c37147ae36) | Dec 07, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Valve         | Jupiter                     | [602605d28d](https://linux-hardware.org/?probe=602605d28d) | Dec 07, 2023 |
| Dell          | Inspiron 13 5310            | [8a4776f925](https://linux-hardware.org/?probe=8a4776f925) | Dec 07, 2023 |
| Chuwi         | CoreBook X                  | [6364cca19b](https://linux-hardware.org/?probe=6364cca19b) | Dec 07, 2023 |
| Alienware     | M17xR3                      | [0522045eab](https://linux-hardware.org/?probe=0522045eab) | Dec 07, 2023 |
| Dell          | Vostro 1520                 | [ac1c78d3a4](https://linux-hardware.org/?probe=ac1c78d3a4) | Dec 07, 2023 |
| Acer          | Aspire A315-51              | [66fc06c54d](https://linux-hardware.org/?probe=66fc06c54d) | Dec 07, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [90ffb00870](https://linux-hardware.org/?probe=90ffb00870) | Dec 07, 2023 |
| Dell          | Precision 7550              | [11f63c8ba3](https://linux-hardware.org/?probe=11f63c8ba3) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [2c7c5b2119](https://linux-hardware.org/?probe=2c7c5b2119) | Dec 06, 2023 |
| HP            | ZBook Studio G3             | [6dc3d18916](https://linux-hardware.org/?probe=6dc3d18916) | Dec 06, 2023 |
| Acer          | Nitro AN515-58              | [a475eb0eb8](https://linux-hardware.org/?probe=a475eb0eb8) | Dec 06, 2023 |
| Dell          | Latitude 7350               | [3fb5b65dba](https://linux-hardware.org/?probe=3fb5b65dba) | Dec 06, 2023 |
| HP            | EliteBook 840 G3            | [c9f70274cf](https://linux-hardware.org/?probe=c9f70274cf) | Dec 06, 2023 |
| Dell          | Latitude E7440              | [6b3c7ea2b5](https://linux-hardware.org/?probe=6b3c7ea2b5) | Dec 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0d809d54ad](https://linux-hardware.org/?probe=0d809d54ad) | Dec 06, 2023 |
| Dell          | G5 5505                     | [74d0a53db4](https://linux-hardware.org/?probe=74d0a53db4) | Dec 06, 2023 |
| HP            | Notebook                    | [8431ed2498](https://linux-hardware.org/?probe=8431ed2498) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [6c558ca3cf](https://linux-hardware.org/?probe=6c558ca3cf) | Dec 06, 2023 |
| Dell          | Latitude 3330               | [843751ec33](https://linux-hardware.org/?probe=843751ec33) | Dec 06, 2023 |
| HP            | EliteBook 850 G3            | [baf21dcbce](https://linux-hardware.org/?probe=baf21dcbce) | Dec 06, 2023 |
| Toshiba       | Satellite L855              | [d737055b41](https://linux-hardware.org/?probe=d737055b41) | Dec 06, 2023 |
| Dell          | Latitude 7490               | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Lenovo        | ThinkPad E460 20ET0014US    | [b1cf294932](https://linux-hardware.org/?probe=b1cf294932) | Dec 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c1a6e3eb9e](https://linux-hardware.org/?probe=c1a6e3eb9e) | Dec 06, 2023 |
| GPU Compan... | GWTC116-2                   | [db1b3d8020](https://linux-hardware.org/?probe=db1b3d8020) | Dec 06, 2023 |
| Apple         | MacBookPro11,2              | [196d6bc9e8](https://linux-hardware.org/?probe=196d6bc9e8) | Dec 05, 2023 |
| Valve         | Jupiter                     | [f7115ec7c0](https://linux-hardware.org/?probe=f7115ec7c0) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | [419da197bb](https://linux-hardware.org/?probe=419da197bb) | Dec 05, 2023 |
| HP            | EliteBook 725 G3            | [21e9914be2](https://linux-hardware.org/?probe=21e9914be2) | Dec 05, 2023 |
| HP            | ProBook 640 G5              | [745d537d97](https://linux-hardware.org/?probe=745d537d97) | Dec 05, 2023 |
| Apple         | MacBookPro11,5              | [749492541f](https://linux-hardware.org/?probe=749492541f) | Dec 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a2c9c3b295](https://linux-hardware.org/?probe=a2c9c3b295) | Dec 05, 2023 |
| Apple         | MacBookPro15,1              | [60aacd19d6](https://linux-hardware.org/?probe=60aacd19d6) | Dec 05, 2023 |
| HP            | Laptop 15-dy2xxx            | [729837dc5c](https://linux-hardware.org/?probe=729837dc5c) | Dec 05, 2023 |
| Dell          | Latitude E6440              | [74db313788](https://linux-hardware.org/?probe=74db313788) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [ac97a3fe1c](https://linux-hardware.org/?probe=ac97a3fe1c) | Dec 05, 2023 |
| Apple         | MacBookAir4,2               | [2b7a417b76](https://linux-hardware.org/?probe=2b7a417b76) | Dec 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS50Q16    | [ad47002b34](https://linux-hardware.org/?probe=ad47002b34) | Dec 04, 2023 |
| Dell          | Inspiron 5584               | [d077f362ea](https://linux-hardware.org/?probe=d077f362ea) | Dec 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2ace6b74e5](https://linux-hardware.org/?probe=2ace6b74e5) | Dec 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1WH0... | [01485bc011](https://linux-hardware.org/?probe=01485bc011) | Dec 04, 2023 |
| HP            | Stream Notebook             | [2f50077231](https://linux-hardware.org/?probe=2f50077231) | Dec 04, 2023 |
| Dynabook      | TECRA A50-J                 | [7aa8d3fb6d](https://linux-hardware.org/?probe=7aa8d3fb6d) | Dec 04, 2023 |
| Panasonic     | CF-52SL3DD1M                | [efdec9a15c](https://linux-hardware.org/?probe=efdec9a15c) | Dec 04, 2023 |
| Acer          | Aspire A317-53              | [2bd5efd212](https://linux-hardware.org/?probe=2bd5efd212) | Dec 04, 2023 |
| Alienware     | 17 R5                       | [e0fdc679e3](https://linux-hardware.org/?probe=e0fdc679e3) | Dec 04, 2023 |
| Alienware     | 17 R5                       | [1e44992982](https://linux-hardware.org/?probe=1e44992982) | Dec 04, 2023 |
| Dell          | XPS 13 9350                 | [aec9f3cb3c](https://linux-hardware.org/?probe=aec9f3cb3c) | Dec 04, 2023 |
| Micro Comp... | Venus series                | [f2c2867f9e](https://linux-hardware.org/?probe=f2c2867f9e) | Dec 04, 2023 |
| Toshiba       | Satellite C855D             | [84e97d4578](https://linux-hardware.org/?probe=84e97d4578) | Dec 04, 2023 |
| Dell          | Latitude 7350               | [74c3983604](https://linux-hardware.org/?probe=74c3983604) | Dec 04, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [caba6d5ee8](https://linux-hardware.org/?probe=caba6d5ee8) | Dec 04, 2023 |
| Lenovo        | ThinkPad T530 2392ASU       | [859f5cb215](https://linux-hardware.org/?probe=859f5cb215) | Dec 04, 2023 |
| HP            | ZBook Studio 15.6 inch G... | [7a78497797](https://linux-hardware.org/?probe=7a78497797) | Dec 03, 2023 |
| Valve         | Jupiter                     | [286c2304f5](https://linux-hardware.org/?probe=286c2304f5) | Dec 03, 2023 |
| Alienware     | M17x                        | [f1c871bbd9](https://linux-hardware.org/?probe=f1c871bbd9) | Dec 03, 2023 |
| Lenovo        | ThinkPad T440s 20AQ005TU... | [3c9d00c839](https://linux-hardware.org/?probe=3c9d00c839) | Dec 03, 2023 |
| Valve         | Jupiter                     | [21c483ddcf](https://linux-hardware.org/?probe=21c483ddcf) | Dec 03, 2023 |
| HP            | ProBook 640 G1              | [287093ae53](https://linux-hardware.org/?probe=287093ae53) | Dec 03, 2023 |
| Dell          | Latitude D630               | [84a1008ee2](https://linux-hardware.org/?probe=84a1008ee2) | Dec 03, 2023 |
| Valve         | Jupiter                     | [36af755784](https://linux-hardware.org/?probe=36af755784) | Dec 03, 2023 |
| HP            | Pavilion 13 x360 PC         | [d481339f2f](https://linux-hardware.org/?probe=d481339f2f) | Dec 03, 2023 |
| HP            | EliteBook 2540p             | [3819853378](https://linux-hardware.org/?probe=3819853378) | Dec 03, 2023 |
| Dell          | Latitude E6530              | [514326bb46](https://linux-hardware.org/?probe=514326bb46) | Dec 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [2f37d84587](https://linux-hardware.org/?probe=2f37d84587) | Dec 03, 2023 |
| HP            | Pavilion 13 x360 PC         | [359c30e001](https://linux-hardware.org/?probe=359c30e001) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [c0681fbe8a](https://linux-hardware.org/?probe=c0681fbe8a) | Dec 03, 2023 |
| ASUSTek       | X705UDR                     | [ea5c2b889d](https://linux-hardware.org/?probe=ea5c2b889d) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [54178ea597](https://linux-hardware.org/?probe=54178ea597) | Dec 03, 2023 |
| HP            | Laptop 15-dw2xxx            | [44390c058f](https://linux-hardware.org/?probe=44390c058f) | Dec 03, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9530a4f63](https://linux-hardware.org/?probe=e9530a4f63) | Dec 03, 2023 |
| HP            | Victus by Gaming Laptop ... | [f150b37e9f](https://linux-hardware.org/?probe=f150b37e9f) | Dec 03, 2023 |
| Dell          | Inspiron 3542               | [793b594721](https://linux-hardware.org/?probe=793b594721) | Dec 03, 2023 |
| HP            | Pavilion dv5                | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| System76      | Lemur Pro                   | [8dcc66a7e6](https://linux-hardware.org/?probe=8dcc66a7e6) | Dec 03, 2023 |
| Toshiba       | Satellite L305              | [a2ac14b9d1](https://linux-hardware.org/?probe=a2ac14b9d1) | Dec 03, 2023 |
| HP            | Pavilion 15                 | [fecd529c90](https://linux-hardware.org/?probe=fecd529c90) | Dec 03, 2023 |
| ASRock        | B550M Steel Legend          | [532cab64b5](https://linux-hardware.org/?probe=532cab64b5) | Dec 03, 2023 |
| Dell          | Inspiron 13-5378            | [0beeed51bc](https://linux-hardware.org/?probe=0beeed51bc) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [e6f0d9a3ae](https://linux-hardware.org/?probe=e6f0d9a3ae) | Dec 03, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | [521b65ac7a](https://linux-hardware.org/?probe=521b65ac7a) | Dec 03, 2023 |
| Dell          | XPS 13 9360                 | [f5b7c2899a](https://linux-hardware.org/?probe=f5b7c2899a) | Dec 03, 2023 |
| Dell          | Inspiron 5515               | [e099b86288](https://linux-hardware.org/?probe=e099b86288) | Dec 02, 2023 |
| HP            | Laptop 15-bs0xx             | [d767fe9238](https://linux-hardware.org/?probe=d767fe9238) | Dec 02, 2023 |
| Alienware     | 18                          | [e2dc3b99fc](https://linux-hardware.org/?probe=e2dc3b99fc) | Dec 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [b517b29f25](https://linux-hardware.org/?probe=b517b29f25) | Dec 02, 2023 |
| Valve         | Galileo                     | [7c11f8f225](https://linux-hardware.org/?probe=7c11f8f225) | Dec 02, 2023 |
| Valve         | Galileo                     | [63234eea22](https://linux-hardware.org/?probe=63234eea22) | Dec 02, 2023 |
| Valve         | Jupiter                     | [c7865c15b0](https://linux-hardware.org/?probe=c7865c15b0) | Dec 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9d3a34c3da](https://linux-hardware.org/?probe=9d3a34c3da) | Dec 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1G63Q    | [0bb363e4fc](https://linux-hardware.org/?probe=0bb363e4fc) | Dec 02, 2023 |
| HP            | 255 G5 Notebook PC          | [dd74ec6df7](https://linux-hardware.org/?probe=dd74ec6df7) | Dec 02, 2023 |
| HP            | 255 G5 Notebook PC          | [e2b2e32290](https://linux-hardware.org/?probe=e2b2e32290) | Dec 02, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [54bfb4d865](https://linux-hardware.org/?probe=54bfb4d865) | Dec 02, 2023 |
| Dell          | Latitude 7400               | [acfa4488ca](https://linux-hardware.org/?probe=acfa4488ca) | Dec 02, 2023 |
| Valve         | Jupiter                     | [dc16a663fa](https://linux-hardware.org/?probe=dc16a663fa) | Dec 02, 2023 |
| Unknown       | Unknown                     | [ecae393240](https://linux-hardware.org/?probe=ecae393240) | Dec 02, 2023 |
| Dell          | Inspiron 15-3565            | [6e0eb386a4](https://linux-hardware.org/?probe=6e0eb386a4) | Dec 02, 2023 |
| Apple         | MacBookPro9,2               | [d72522d400](https://linux-hardware.org/?probe=d72522d400) | Dec 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5568b58564](https://linux-hardware.org/?probe=5568b58564) | Dec 02, 2023 |
| SK hynix      | HyBook                      | [4c0f06eb94](https://linux-hardware.org/?probe=4c0f06eb94) | Dec 02, 2023 |
| HP            | ZBook 15 G2                 | [ba6823f38e](https://linux-hardware.org/?probe=ba6823f38e) | Dec 02, 2023 |
| Framework     | Laptop                      | [92f0d97b05](https://linux-hardware.org/?probe=92f0d97b05) | Dec 02, 2023 |
| Framework     | Laptop                      | [995d231691](https://linux-hardware.org/?probe=995d231691) | Dec 02, 2023 |
| Toshiba       | TECRA R950                  | [8ab7278f60](https://linux-hardware.org/?probe=8ab7278f60) | Dec 01, 2023 |
| Toshiba       | TECRA R950                  | [9634f68cab](https://linux-hardware.org/?probe=9634f68cab) | Dec 01, 2023 |
| HP            | 240 G7                      | [ad50ca6a6e](https://linux-hardware.org/?probe=ad50ca6a6e) | Dec 01, 2023 |
| Apple         | MacBookPro9,2               | [1784c4c5b0](https://linux-hardware.org/?probe=1784c4c5b0) | Dec 01, 2023 |
| Dell          | Inspiron 7720               | [974a2661e2](https://linux-hardware.org/?probe=974a2661e2) | Dec 01, 2023 |
| HP            | EliteBook 6930p             | [0fefa1b40e](https://linux-hardware.org/?probe=0fefa1b40e) | Dec 01, 2023 |
| Dell          | Studio 1737                 | [4e400ded4b](https://linux-hardware.org/?probe=4e400ded4b) | Dec 01, 2023 |
| Dell          | Inspiron 1545               | [7fbbf18938](https://linux-hardware.org/?probe=7fbbf18938) | Dec 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7002CU... | [679acd4c7a](https://linux-hardware.org/?probe=679acd4c7a) | Dec 01, 2023 |
| Lenovo        | 14w Gen 2 82N8              | [bc02b5a084](https://linux-hardware.org/?probe=bc02b5a084) | Dec 01, 2023 |
| HP            | Pavilion 17                 | [6894411a12](https://linux-hardware.org/?probe=6894411a12) | Dec 01, 2023 |
| Acer          | Aspire A317-53              | [3c418227c7](https://linux-hardware.org/?probe=3c418227c7) | Dec 01, 2023 |
| Lenovo        | ThinkPad X60 1706M8U        | [ab0582fe71](https://linux-hardware.org/?probe=ab0582fe71) | Dec 01, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [ea481bfb9d](https://linux-hardware.org/?probe=ea481bfb9d) | Dec 01, 2023 |
| Dell          | Latitude E6520              | [1cb2209cef](https://linux-hardware.org/?probe=1cb2209cef) | Dec 01, 2023 |
| Apple         | MacBookPro8,1               | [ad16e37b50](https://linux-hardware.org/?probe=ad16e37b50) | Dec 01, 2023 |
| Dell          | XPS420                      | [2204a9646d](https://linux-hardware.org/?probe=2204a9646d) | Dec 01, 2023 |
| Dell          | Inspiron 15-7568            | [80d4969c23](https://linux-hardware.org/?probe=80d4969c23) | Dec 01, 2023 |
| Dell          | Latitude E6440              | [4459a634ca](https://linux-hardware.org/?probe=4459a634ca) | Dec 01, 2023 |
| Acer          | Nitro AN515-54              | [3953185e28](https://linux-hardware.org/?probe=3953185e28) | Dec 01, 2023 |
| Toshiba       | Satellite L775              | [da7cc192f7](https://linux-hardware.org/?probe=da7cc192f7) | Dec 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [5c4714ecce](https://linux-hardware.org/?probe=5c4714ecce) | Dec 01, 2023 |
| HP            | 15 Notebook PC              | [b431f0a398](https://linux-hardware.org/?probe=b431f0a398) | Dec 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H1C... | [7590036270](https://linux-hardware.org/?probe=7590036270) | Dec 01, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [5f31cddd2f](https://linux-hardware.org/?probe=5f31cddd2f) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| Valve         | Galileo                     | [3006af1c16](https://linux-hardware.org/?probe=3006af1c16) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Google        | Jinlon                      | [563dc8024c](https://linux-hardware.org/?probe=563dc8024c) | Nov 30, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| Acer          | Nitro AN515-54              | [7c4f4d3207](https://linux-hardware.org/?probe=7c4f4d3207) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [120ad9d1f3](https://linux-hardware.org/?probe=120ad9d1f3) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [863d4d2b8f](https://linux-hardware.org/?probe=863d4d2b8f) | Nov 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S4XW00    | [13a434ff63](https://linux-hardware.org/?probe=13a434ff63) | Nov 30, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | [1b0dd94e69](https://linux-hardware.org/?probe=1b0dd94e69) | Nov 30, 2023 |
| Acer          | Nitro AN515-42              | [4c24f3fddf](https://linux-hardware.org/?probe=4c24f3fddf) | Nov 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3ed69dec15](https://linux-hardware.org/?probe=3ed69dec15) | Nov 30, 2023 |
| HP            | Laptop 15-bs1xx             | [e8f82bc03f](https://linux-hardware.org/?probe=e8f82bc03f) | Nov 29, 2023 |
| Toshiba       | Satellite L455D             | [d08710e3d3](https://linux-hardware.org/?probe=d08710e3d3) | Nov 29, 2023 |
| Lenovo        | ThinkPad L540 20AUS01H00    | [6bdb162853](https://linux-hardware.org/?probe=6bdb162853) | Nov 29, 2023 |
| Google        | Nautilus                    | [1b255e77a3](https://linux-hardware.org/?probe=1b255e77a3) | Nov 29, 2023 |
| ASUSTek       | GL702VM                     | [0f104614aa](https://linux-hardware.org/?probe=0f104614aa) | Nov 29, 2023 |
| HP            | Laptop 17-by3xxx            | [63860f689c](https://linux-hardware.org/?probe=63860f689c) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| Apple         | MacBookPro13,1              | [6074c742c1](https://linux-hardware.org/?probe=6074c742c1) | Nov 29, 2023 |
| Alienware     | 17                          | [1c23fa6051](https://linux-hardware.org/?probe=1c23fa6051) | Nov 29, 2023 |
| HP            | Laptop 15-da0xxx            | [4d9e778bd2](https://linux-hardware.org/?probe=4d9e778bd2) | Nov 29, 2023 |
| Valve         | Jupiter                     | [e92fd78128](https://linux-hardware.org/?probe=e92fd78128) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ef2a2ab2a9](https://linux-hardware.org/?probe=ef2a2ab2a9) | Nov 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [fa60a82ab5](https://linux-hardware.org/?probe=fa60a82ab5) | Nov 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5e08371b05](https://linux-hardware.org/?probe=5e08371b05) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| Valve         | Jupiter                     | [b5216ccd78](https://linux-hardware.org/?probe=b5216ccd78) | Nov 29, 2023 |
| Valve         | Galileo                     | [f8322860f1](https://linux-hardware.org/?probe=f8322860f1) | Nov 29, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [e9f95fd344](https://linux-hardware.org/?probe=e9f95fd344) | Nov 29, 2023 |
| ASUSTek       | K501UW                      | [37ecb34a8a](https://linux-hardware.org/?probe=37ecb34a8a) | Nov 29, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [ce91016387](https://linux-hardware.org/?probe=ce91016387) | Nov 29, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [6af16f3cbb](https://linux-hardware.org/?probe=6af16f3cbb) | Nov 29, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [414132dc07](https://linux-hardware.org/?probe=414132dc07) | Nov 29, 2023 |
| Dell          | Precision 7560              | [035f0d6f41](https://linux-hardware.org/?probe=035f0d6f41) | Nov 29, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [16dda5c039](https://linux-hardware.org/?probe=16dda5c039) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [9b16b68bbe](https://linux-hardware.org/?probe=9b16b68bbe) | Nov 28, 2023 |
| HP            | 15                          | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | [29d00359b8](https://linux-hardware.org/?probe=29d00359b8) | Nov 28, 2023 |
| Acer          | Aspire 5742                 | [88ea78aaf0](https://linux-hardware.org/?probe=88ea78aaf0) | Nov 28, 2023 |
| ASUSTek       | Q550LF                      | [c09615021b](https://linux-hardware.org/?probe=c09615021b) | Nov 28, 2023 |
| HP            | EliteBook 840 G5            | [2efe0e2a59](https://linux-hardware.org/?probe=2efe0e2a59) | Nov 28, 2023 |
| Samsung       | 760XDA                      | [f502815b13](https://linux-hardware.org/?probe=f502815b13) | Nov 28, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [64b58279b2](https://linux-hardware.org/?probe=64b58279b2) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [35775b438a](https://linux-hardware.org/?probe=35775b438a) | Nov 28, 2023 |
| Toshiba       | Satellite L855              | [b1f194a955](https://linux-hardware.org/?probe=b1f194a955) | Nov 28, 2023 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | [8db080dffe](https://linux-hardware.org/?probe=8db080dffe) | Nov 28, 2023 |
| HP            | ZBook 14 G2                 | [124f1ff011](https://linux-hardware.org/?probe=124f1ff011) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [10a019bb7e](https://linux-hardware.org/?probe=10a019bb7e) | Nov 28, 2023 |
| MSI           | Prestige 16Studio A13VF     | [4d8fb7dd05](https://linux-hardware.org/?probe=4d8fb7dd05) | Nov 28, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [8c82a1d8c3](https://linux-hardware.org/?probe=8c82a1d8c3) | Nov 28, 2023 |
| Toshiba       | Satellite L305              | [59abc93874](https://linux-hardware.org/?probe=59abc93874) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [144a7d4106](https://linux-hardware.org/?probe=144a7d4106) | Nov 28, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [160556d559](https://linux-hardware.org/?probe=160556d559) | Nov 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [5358617403](https://linux-hardware.org/?probe=5358617403) | Nov 28, 2023 |
| Google        | Fleex                       | [0f905372c0](https://linux-hardware.org/?probe=0f905372c0) | Nov 28, 2023 |
| HP            | Laptop 15-dy2xxx            | [c56c2fcff2](https://linux-hardware.org/?probe=c56c2fcff2) | Nov 28, 2023 |
| HP            | 15                          | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| GPU Compan... | GWTC116-2                   | [3363b8258e](https://linux-hardware.org/?probe=3363b8258e) | Nov 28, 2023 |
| SGIN          | M15                         | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Valve         | Jupiter                     | [2ceef57eaa](https://linux-hardware.org/?probe=2ceef57eaa) | Nov 28, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0dbf67ab6f](https://linux-hardware.org/?probe=0dbf67ab6f) | Nov 28, 2023 |
| HP            | G60                         | [eb7f66cedc](https://linux-hardware.org/?probe=eb7f66cedc) | Nov 28, 2023 |
| HUAWEI        | MACH-WX9                    | [a09dd535a7](https://linux-hardware.org/?probe=a09dd535a7) | Nov 28, 2023 |
| HP            | ZBook 15 G6                 | [1f87fc5fca](https://linux-hardware.org/?probe=1f87fc5fca) | Nov 28, 2023 |
| Valve         | Jupiter                     | [9544f59716](https://linux-hardware.org/?probe=9544f59716) | Nov 27, 2023 |
| Dell          | XPS 15 9550                 | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S42P00    | [bab4b2e0cf](https://linux-hardware.org/?probe=bab4b2e0cf) | Nov 27, 2023 |
| Dell          | Precision 5520              | [4d773def1d](https://linux-hardware.org/?probe=4d773def1d) | Nov 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d940db14d3](https://linux-hardware.org/?probe=d940db14d3) | Nov 27, 2023 |
| Apple         | MacBookPro10,1              | [3982dc173a](https://linux-hardware.org/?probe=3982dc173a) | Nov 27, 2023 |
| Lenovo        | Flex 2 Pro-15               | [7e7f94ca3b](https://linux-hardware.org/?probe=7e7f94ca3b) | Nov 27, 2023 |
| Dell          | Inspiron 5593               | [fc19161855](https://linux-hardware.org/?probe=fc19161855) | Nov 27, 2023 |
| Dell          | Precision 7670              | [450a8674d6](https://linux-hardware.org/?probe=450a8674d6) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S2YS00    | [635d73bd44](https://linux-hardware.org/?probe=635d73bd44) | Nov 27, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9ba9e50996](https://linux-hardware.org/?probe=9ba9e50996) | Nov 27, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | [a54c387b5f](https://linux-hardware.org/?probe=a54c387b5f) | Nov 27, 2023 |
| Dell          | Inspiron 5585               | [fd11deddc6](https://linux-hardware.org/?probe=fd11deddc6) | Nov 27, 2023 |
| Dell          | Inspiron 5585               | [28ebcf2199](https://linux-hardware.org/?probe=28ebcf2199) | Nov 27, 2023 |
| Acer          | Aspire A515-56              | [419daf1e57](https://linux-hardware.org/?probe=419daf1e57) | Nov 27, 2023 |
| Micro Elec... | MG-VCP17A-3070              | [d252e49a50](https://linux-hardware.org/?probe=d252e49a50) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [4256ad6b53](https://linux-hardware.org/?probe=4256ad6b53) | Nov 27, 2023 |
| Valve         | Jupiter                     | [2a0b1b3a9b](https://linux-hardware.org/?probe=2a0b1b3a9b) | Nov 27, 2023 |
| Dell          | Inspiron 3537               | [d69ca1d353](https://linux-hardware.org/?probe=d69ca1d353) | Nov 27, 2023 |
| Sony          | VPCSB16FH                   | [9e4d687ce4](https://linux-hardware.org/?probe=9e4d687ce4) | Nov 27, 2023 |
| Lenovo        | ThinkPad T520 4242AU2       | [71ffabfcb1](https://linux-hardware.org/?probe=71ffabfcb1) | Nov 27, 2023 |
| ASUSTek       | S301LA                      | [a42a950602](https://linux-hardware.org/?probe=a42a950602) | Nov 27, 2023 |
| Unknown       | Unknown                     | [5cf9f0b3e1](https://linux-hardware.org/?probe=5cf9f0b3e1) | Nov 27, 2023 |
| Acer          | Aspire A515-46              | [c3618a788c](https://linux-hardware.org/?probe=c3618a788c) | Nov 27, 2023 |
| HP            | Laptop 14-dk0xxx            | [9e97507512](https://linux-hardware.org/?probe=9e97507512) | Nov 27, 2023 |
| HP            | Notebook                    | [be0de1221c](https://linux-hardware.org/?probe=be0de1221c) | Nov 26, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [f18c7cb67b](https://linux-hardware.org/?probe=f18c7cb67b) | Nov 26, 2023 |
| Google        | Osiris                      | [104c509853](https://linux-hardware.org/?probe=104c509853) | Nov 26, 2023 |
| Apple         | MacBook10,1                 | [78c3cc842b](https://linux-hardware.org/?probe=78c3cc842b) | Nov 26, 2023 |
| HP            | Laptop 15-bw0xx             | [542c0ce906](https://linux-hardware.org/?probe=542c0ce906) | Nov 26, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [61a33862ad](https://linux-hardware.org/?probe=61a33862ad) | Nov 26, 2023 |
| HP            | EliteBook 820 G3            | [88ed16eec1](https://linux-hardware.org/?probe=88ed16eec1) | Nov 26, 2023 |
| Acer          | Aspire E5-576G              | [cbce88f621](https://linux-hardware.org/?probe=cbce88f621) | Nov 26, 2023 |
| Dell          | Inspiron 5770               | [c35b932f41](https://linux-hardware.org/?probe=c35b932f41) | Nov 26, 2023 |
| Valve         | Jupiter                     | [fe89edacdc](https://linux-hardware.org/?probe=fe89edacdc) | Nov 26, 2023 |
| Valve         | Jupiter                     | [d760d5c451](https://linux-hardware.org/?probe=d760d5c451) | Nov 26, 2023 |
| HP            | Notebook                    | [91ce2608c6](https://linux-hardware.org/?probe=91ce2608c6) | Nov 26, 2023 |
| Dell          | XPS 13 9370                 | [2961332bce](https://linux-hardware.org/?probe=2961332bce) | Nov 26, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [25fd880050](https://linux-hardware.org/?probe=25fd880050) | Nov 26, 2023 |
| Toshiba       | Satellite L855              | [420c85d7b3](https://linux-hardware.org/?probe=420c85d7b3) | Nov 26, 2023 |
| HP            | 2000                        | [a9e55a3aac](https://linux-hardware.org/?probe=a9e55a3aac) | Nov 26, 2023 |
| Acer          | Aspire S3-391               | [ee4eefb0d4](https://linux-hardware.org/?probe=ee4eefb0d4) | Nov 26, 2023 |
| GPU Compan... | GWTN156-2BK                 | [4dee905c74](https://linux-hardware.org/?probe=4dee905c74) | Nov 26, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [3a3a75aa94](https://linux-hardware.org/?probe=3a3a75aa94) | Nov 26, 2023 |
| MSI           | Stealth GS77 12UE           | [92c0eb2e6b](https://linux-hardware.org/?probe=92c0eb2e6b) | Nov 26, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [79c8961819](https://linux-hardware.org/?probe=79c8961819) | Nov 26, 2023 |
| Dell          | Latitude 12 Rugged Table... | [012c390a1c](https://linux-hardware.org/?probe=012c390a1c) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | [484699c792](https://linux-hardware.org/?probe=484699c792) | Nov 26, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [678db1a63a](https://linux-hardware.org/?probe=678db1a63a) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1080... | [37c32a9af7](https://linux-hardware.org/?probe=37c32a9af7) | Nov 25, 2023 |
| Toshiba       | Satellite L55t-A            | [b037dccb20](https://linux-hardware.org/?probe=b037dccb20) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [78063879b6](https://linux-hardware.org/?probe=78063879b6) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [4ded9e9bd5](https://linux-hardware.org/?probe=4ded9e9bd5) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [cf0970cabe](https://linux-hardware.org/?probe=cf0970cabe) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [791f093fc3](https://linux-hardware.org/?probe=791f093fc3) | Nov 25, 2023 |
| HP            | Pavilion TS Sleekbook 15    | [9c76ca1014](https://linux-hardware.org/?probe=9c76ca1014) | Nov 25, 2023 |
| Alienware     | x14                         | [af501023a5](https://linux-hardware.org/?probe=af501023a5) | Nov 25, 2023 |
| Toshiba       | TECRA W50-A                 | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| Dell          | Latitude E5540              | [29c4fc6485](https://linux-hardware.org/?probe=29c4fc6485) | Nov 25, 2023 |
| Acer          | Aspire E5-576G              | [3ce4659fcd](https://linux-hardware.org/?probe=3ce4659fcd) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [9e623760a1](https://linux-hardware.org/?probe=9e623760a1) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [8f6ce26933](https://linux-hardware.org/?probe=8f6ce26933) | Nov 25, 2023 |
| Valve         | Galileo                     | [905889b654](https://linux-hardware.org/?probe=905889b654) | Nov 25, 2023 |
| HP            | Laptop 15-fc0xxx            | [6f3cf47d7d](https://linux-hardware.org/?probe=6f3cf47d7d) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | [7cb8811992](https://linux-hardware.org/?probe=7cb8811992) | Nov 25, 2023 |
| ASUSTek       | Unknown                     | [9d2fdb067c](https://linux-hardware.org/?probe=9d2fdb067c) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [8131bff614](https://linux-hardware.org/?probe=8131bff614) | Nov 25, 2023 |
| HP            | Laptop 15z-ef3xxx           | [278b62313d](https://linux-hardware.org/?probe=278b62313d) | Nov 25, 2023 |
| HP            | EliteBook 865 16 inch G9... | [9620d48b2f](https://linux-hardware.org/?probe=9620d48b2f) | Nov 25, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [344eaa9a2a](https://linux-hardware.org/?probe=344eaa9a2a) | Nov 25, 2023 |
| Lenovo        | G510 20238                  | [75a5b58cb8](https://linux-hardware.org/?probe=75a5b58cb8) | Nov 25, 2023 |
| HP            | EliteBook 840 G5            | [4e7c1f967f](https://linux-hardware.org/?probe=4e7c1f967f) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [a886bd351a](https://linux-hardware.org/?probe=a886bd351a) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [386171f14d](https://linux-hardware.org/?probe=386171f14d) | Nov 24, 2023 |
| Valve         | Galileo                     | [15994404a2](https://linux-hardware.org/?probe=15994404a2) | Nov 24, 2023 |
| HP            | EliteBook 840 G5            | [ac1dfd9609](https://linux-hardware.org/?probe=ac1dfd9609) | Nov 24, 2023 |
| Dell          | Latitude D830               | [472b675869](https://linux-hardware.org/?probe=472b675869) | Nov 24, 2023 |
| Valve         | Jupiter                     | [68d1729e3b](https://linux-hardware.org/?probe=68d1729e3b) | Nov 24, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [8edef55308](https://linux-hardware.org/?probe=8edef55308) | Nov 24, 2023 |
| Dell          | Latitude E5450              | [1a04febc14](https://linux-hardware.org/?probe=1a04febc14) | Nov 24, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | [a67fd8af5c](https://linux-hardware.org/?probe=a67fd8af5c) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [3ea30bf13e](https://linux-hardware.org/?probe=3ea30bf13e) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [8fd3c93367](https://linux-hardware.org/?probe=8fd3c93367) | Nov 24, 2023 |
| Valve         | Jupiter                     | [8ba2f4981d](https://linux-hardware.org/?probe=8ba2f4981d) | Nov 24, 2023 |
| Gateway       | P-6301                      | [d16a00d10d](https://linux-hardware.org/?probe=d16a00d10d) | Nov 24, 2023 |
| Dell          | G3 3500                     | [c53dff54a2](https://linux-hardware.org/?probe=c53dff54a2) | Nov 24, 2023 |
| Gateway       | P-6301                      | [d9c74ac6f8](https://linux-hardware.org/?probe=d9c74ac6f8) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [339e20f716](https://linux-hardware.org/?probe=339e20f716) | Nov 24, 2023 |
| Dell          | Inspiron 1750               | [4d256b493c](https://linux-hardware.org/?probe=4d256b493c) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0LE0... | [3da7eab7e8](https://linux-hardware.org/?probe=3da7eab7e8) | Nov 23, 2023 |
| Valve         | Galileo                     | [0e0c27070c](https://linux-hardware.org/?probe=0e0c27070c) | Nov 23, 2023 |
| HP            | Laptop 17-cp0xxx            | [7f23e0e274](https://linux-hardware.org/?probe=7f23e0e274) | Nov 23, 2023 |
| Dell          | Precision M4700             | [bb717e3193](https://linux-hardware.org/?probe=bb717e3193) | Nov 23, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [b6496b25f7](https://linux-hardware.org/?probe=b6496b25f7) | Nov 23, 2023 |
| Apple         | MacBookAir7,2               | [f7e288a635](https://linux-hardware.org/?probe=f7e288a635) | Nov 23, 2023 |
| ASUSTek       | E403SA                      | [01b3727f1a](https://linux-hardware.org/?probe=01b3727f1a) | Nov 23, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [e897dd5b20](https://linux-hardware.org/?probe=e897dd5b20) | Nov 23, 2023 |
| HP            | Notebook                    | [897e3bf444](https://linux-hardware.org/?probe=897e3bf444) | Nov 23, 2023 |
| Acer          | Aspire E5-576               | [714225261c](https://linux-hardware.org/?probe=714225261c) | Nov 23, 2023 |
| Dell          | Latitude E5450              | [173c3b97bb](https://linux-hardware.org/?probe=173c3b97bb) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450s 20BX001MU... | [80d4678e90](https://linux-hardware.org/?probe=80d4678e90) | Nov 23, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [97b04abe7f](https://linux-hardware.org/?probe=97b04abe7f) | Nov 22, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [20aa8a380c](https://linux-hardware.org/?probe=20aa8a380c) | Nov 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [58252e8597](https://linux-hardware.org/?probe=58252e8597) | Nov 22, 2023 |
| Google        | Edgar                       | [12d8e1b6af](https://linux-hardware.org/?probe=12d8e1b6af) | Nov 22, 2023 |
| Google        | Samus                       | [d87150c47b](https://linux-hardware.org/?probe=d87150c47b) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3f798c7bfd](https://linux-hardware.org/?probe=3f798c7bfd) | Nov 22, 2023 |
| Lenovo        | ThinkPad P52 20MAS21905     | [ada7aab2dd](https://linux-hardware.org/?probe=ada7aab2dd) | Nov 22, 2023 |
| Samsung       | 760XDA                      | [491ebf48ff](https://linux-hardware.org/?probe=491ebf48ff) | Nov 22, 2023 |
| Dell          | XPS 15 9530                 | [2720b6f6d4](https://linux-hardware.org/?probe=2720b6f6d4) | Nov 22, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [228087556b](https://linux-hardware.org/?probe=228087556b) | Nov 22, 2023 |
| Valve         | Jupiter                     | [678fc160d6](https://linux-hardware.org/?probe=678fc160d6) | Nov 22, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [6785d4e239](https://linux-hardware.org/?probe=6785d4e239) | Nov 22, 2023 |
| Dell          | Latitude 3380               | [aac9f14eb9](https://linux-hardware.org/?probe=aac9f14eb9) | Nov 22, 2023 |
| Dell          | Latitude 7440               | [fa13937043](https://linux-hardware.org/?probe=fa13937043) | Nov 22, 2023 |
| Google        | Bluebird                    | [3e2dd5433f](https://linux-hardware.org/?probe=3e2dd5433f) | Nov 22, 2023 |
| Google        | Bluebird                    | [d267ea0312](https://linux-hardware.org/?probe=d267ea0312) | Nov 22, 2023 |
| Acer          | Nitro AN515-54              | [59580145e5](https://linux-hardware.org/?probe=59580145e5) | Nov 22, 2023 |
| Lenovo        | ThinkPad T420 4180KHU       | [cb4a42ed82](https://linux-hardware.org/?probe=cb4a42ed82) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [fbde674650](https://linux-hardware.org/?probe=fbde674650) | Nov 22, 2023 |
| Dell          | Latitude E5450              | [51011f2935](https://linux-hardware.org/?probe=51011f2935) | Nov 21, 2023 |
| HP            | EliteBook 8470p             | [40b88a9c74](https://linux-hardware.org/?probe=40b88a9c74) | Nov 21, 2023 |
| Valve         | Jupiter                     | [3bac0a6d11](https://linux-hardware.org/?probe=3bac0a6d11) | Nov 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Google        | Pujjo                       | [a196388078](https://linux-hardware.org/?probe=a196388078) | Nov 21, 2023 |
| Gigabyte      | AX370-Gaming-CF se1         | [541752a388](https://linux-hardware.org/?probe=541752a388) | Nov 21, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [aa9cb9ab67](https://linux-hardware.org/?probe=aa9cb9ab67) | Nov 21, 2023 |
| Valve         | Jupiter                     | [57479f92a2](https://linux-hardware.org/?probe=57479f92a2) | Nov 21, 2023 |
| Apple         | MacBookPro5,5               | [a87476e787](https://linux-hardware.org/?probe=a87476e787) | Nov 21, 2023 |
| HP            | ZBook 15 G2                 | [7a6763208d](https://linux-hardware.org/?probe=7a6763208d) | Nov 21, 2023 |
| Valve         | Jupiter                     | [e782bdc7ec](https://linux-hardware.org/?probe=e782bdc7ec) | Nov 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | [03d7d46dd0](https://linux-hardware.org/?probe=03d7d46dd0) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| HP            | ZBook Studio G3             | [31da514274](https://linux-hardware.org/?probe=31da514274) | Nov 21, 2023 |
| Apple         | MacBookPro11,1              | [82431655c4](https://linux-hardware.org/?probe=82431655c4) | Nov 21, 2023 |
| Apple         | MacBookPro11,1              | [940aa6936c](https://linux-hardware.org/?probe=940aa6936c) | Nov 21, 2023 |
| Lenovo        | B580 20144                  | [634e12256a](https://linux-hardware.org/?probe=634e12256a) | Nov 21, 2023 |
| Fujitsu       | LIFEBOOK T936               | [524d4c2bdd](https://linux-hardware.org/?probe=524d4c2bdd) | Nov 21, 2023 |
| HP            | Pavilion dv6                | [1407b8e2b3](https://linux-hardware.org/?probe=1407b8e2b3) | Nov 21, 2023 |
| Apple         | MacBookPro15,2              | [eb1dc5dbda](https://linux-hardware.org/?probe=eb1dc5dbda) | Nov 21, 2023 |
| Lenovo        | ThinkPad X280 20KFCTO1WW    | [eb4b335400](https://linux-hardware.org/?probe=eb4b335400) | Nov 21, 2023 |
| Acer          | Aspire A515-43              | [294889610d](https://linux-hardware.org/?probe=294889610d) | Nov 20, 2023 |
| MSI           | Raider GE76 12UE            | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Dell          | Inspiron 3501               | [c207576b9e](https://linux-hardware.org/?probe=c207576b9e) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| Apple         | MacBookPro15,2              | [07e0aacd4c](https://linux-hardware.org/?probe=07e0aacd4c) | Nov 20, 2023 |
| Dell          | Inspiron 3501               | [8ed6bf7673](https://linux-hardware.org/?probe=8ed6bf7673) | Nov 20, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [86845a8402](https://linux-hardware.org/?probe=86845a8402) | Nov 20, 2023 |
| HP            | Laptop 17-ca0xxx            | [f284bf043f](https://linux-hardware.org/?probe=f284bf043f) | Nov 20, 2023 |
| Dell          | Latitude E5500              | [657426e5e9](https://linux-hardware.org/?probe=657426e5e9) | Nov 20, 2023 |
| Unknown       | Unknown                     | [3bbd75201c](https://linux-hardware.org/?probe=3bbd75201c) | Nov 20, 2023 |
| Valve         | Jupiter                     | [4d99a400c5](https://linux-hardware.org/?probe=4d99a400c5) | Nov 20, 2023 |
| HP            | EliteBook 8540p             | [35c40648e5](https://linux-hardware.org/?probe=35c40648e5) | Nov 20, 2023 |
| Apple         | MacBookPro9,2               | [828da99472](https://linux-hardware.org/?probe=828da99472) | Nov 20, 2023 |
| Apple         | MacBookPro10,2              | [a41e49fbb9](https://linux-hardware.org/?probe=a41e49fbb9) | Nov 20, 2023 |
| HP            | Pavilion dv6                | [7c2ae53c17](https://linux-hardware.org/?probe=7c2ae53c17) | Nov 20, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| Apple         | MacBookPro11,1              | [5dfd18dfc1](https://linux-hardware.org/?probe=5dfd18dfc1) | Nov 20, 2023 |
| Apple         | MacBookPro11,1              | [b53cd95828](https://linux-hardware.org/?probe=b53cd95828) | Nov 20, 2023 |
| HP            | ProBook 6570b               | [39ba398a11](https://linux-hardware.org/?probe=39ba398a11) | Nov 20, 2023 |
| Dell          | Latitude 5401               | [b3698296b0](https://linux-hardware.org/?probe=b3698296b0) | Nov 20, 2023 |
| Dell          | Inspiron 5584               | [9e43d7f684](https://linux-hardware.org/?probe=9e43d7f684) | Nov 20, 2023 |
| Google        | Kefka                       | [7522f0b2f5](https://linux-hardware.org/?probe=7522f0b2f5) | Nov 20, 2023 |
| Dell          | Latitude E5520              | [c8e072f47b](https://linux-hardware.org/?probe=c8e072f47b) | Nov 19, 2023 |
| Dell          | Inspiron 3583               | [62a9e9f64e](https://linux-hardware.org/?probe=62a9e9f64e) | Nov 19, 2023 |
| HP            | Notebook                    | [3b356149fd](https://linux-hardware.org/?probe=3b356149fd) | Nov 19, 2023 |
| Lenovo        | IdeaPad Yoga 2 Pro 20266    | [8bf049bac1](https://linux-hardware.org/?probe=8bf049bac1) | Nov 19, 2023 |
| HP            | Pavilion dv6                | [4b2380d3ab](https://linux-hardware.org/?probe=4b2380d3ab) | Nov 19, 2023 |
| Dell          | XPS 15 7590                 | [a40bc78bcf](https://linux-hardware.org/?probe=a40bc78bcf) | Nov 19, 2023 |
| Dell          | Latitude 5580               | [499c9fbac8](https://linux-hardware.org/?probe=499c9fbac8) | Nov 19, 2023 |
| Valve         | Jupiter                     | [b3d483cfb9](https://linux-hardware.org/?probe=b3d483cfb9) | Nov 19, 2023 |
| HP            | Laptop 14-df0xxx            | [aaa013c1b1](https://linux-hardware.org/?probe=aaa013c1b1) | Nov 19, 2023 |
| Toshiba       | QOSMIO X70-A                | [4173fd74a2](https://linux-hardware.org/?probe=4173fd74a2) | Nov 19, 2023 |
| HP            | 15-AF175NR Notebook PC      | [2f6436a60a](https://linux-hardware.org/?probe=2f6436a60a) | Nov 19, 2023 |
| Dell          | Inspiron 3543               | [6246347237](https://linux-hardware.org/?probe=6246347237) | Nov 19, 2023 |
| HP            | 15-AF175NR Notebook PC      | [5515a544e4](https://linux-hardware.org/?probe=5515a544e4) | Nov 19, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [b96e1019c8](https://linux-hardware.org/?probe=b96e1019c8) | Nov 19, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [bcaaff7eea](https://linux-hardware.org/?probe=bcaaff7eea) | Nov 19, 2023 |
| HP            | Pavilion dv6                | [bab0d77625](https://linux-hardware.org/?probe=bab0d77625) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [355e11bb80](https://linux-hardware.org/?probe=355e11bb80) | Nov 19, 2023 |
| MSI           | GE76 Raider 11UE            | [9d0a216d82](https://linux-hardware.org/?probe=9d0a216d82) | Nov 19, 2023 |
| Apple         | MacBookPro10,2              | [414a04328d](https://linux-hardware.org/?probe=414a04328d) | Nov 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ab4faca57e](https://linux-hardware.org/?probe=ab4faca57e) | Nov 19, 2023 |
| HP            | ProBook 640 G1              | [702a886d45](https://linux-hardware.org/?probe=702a886d45) | Nov 19, 2023 |
| Dell          | Precision M6500             | [9bd0aab68e](https://linux-hardware.org/?probe=9bd0aab68e) | Nov 19, 2023 |
| Dell          | Latitude 5400               | [9b2e3ff17c](https://linux-hardware.org/?probe=9b2e3ff17c) | Nov 19, 2023 |
| Apple         | MacBookPro9,2               | [9684410209](https://linux-hardware.org/?probe=9684410209) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [91f7d584f3](https://linux-hardware.org/?probe=91f7d584f3) | Nov 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ef77e621d0](https://linux-hardware.org/?probe=ef77e621d0) | Nov 19, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c7d86840e8](https://linux-hardware.org/?probe=c7d86840e8) | Nov 19, 2023 |
| Unknown       | Unknown                     | [0131d7730a](https://linux-hardware.org/?probe=0131d7730a) | Nov 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [433711d5d8](https://linux-hardware.org/?probe=433711d5d8) | Nov 18, 2023 |
| Alienware     | Area-51m R2                 | [0ed781b812](https://linux-hardware.org/?probe=0ed781b812) | Nov 18, 2023 |
| HP            | Victus by Gaming Laptop ... | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| MSI           | Prestige 14Evo A11M         | [cc8499c524](https://linux-hardware.org/?probe=cc8499c524) | Nov 18, 2023 |
| AMI           | Intel                       | [d590688338](https://linux-hardware.org/?probe=d590688338) | Nov 18, 2023 |
| Dell          | Latitude 3189               | [915f8dc0af](https://linux-hardware.org/?probe=915f8dc0af) | Nov 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | [b8bca4e3cd](https://linux-hardware.org/?probe=b8bca4e3cd) | Nov 18, 2023 |
| Dell          | Latitude 5430               | [a2757959fc](https://linux-hardware.org/?probe=a2757959fc) | Nov 18, 2023 |
| Valve         | Jupiter                     | [2c773bdad4](https://linux-hardware.org/?probe=2c773bdad4) | Nov 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [8d3b6e85bc](https://linux-hardware.org/?probe=8d3b6e85bc) | Nov 18, 2023 |
| HP            | Stream Notebook             | [5d318f7956](https://linux-hardware.org/?probe=5d318f7956) | Nov 18, 2023 |
| Valve         | Jupiter                     | [adbc907a31](https://linux-hardware.org/?probe=adbc907a31) | Nov 18, 2023 |
| Lenovo        | ThinkPad E560 20EWS0M900    | [08bbcc2f7f](https://linux-hardware.org/?probe=08bbcc2f7f) | Nov 18, 2023 |
| HP            | Pavilion g7                 | [2e292ab326](https://linux-hardware.org/?probe=2e292ab326) | Nov 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | [ea53f8ef4f](https://linux-hardware.org/?probe=ea53f8ef4f) | Nov 18, 2023 |
| HP            | Pavilion g7                 | [4c5b84e4bb](https://linux-hardware.org/?probe=4c5b84e4bb) | Nov 18, 2023 |
| Valve         | Jupiter                     | [9d693c070e](https://linux-hardware.org/?probe=9d693c070e) | Nov 18, 2023 |
| Dell          | Inspiron 3543               | [7e856f1c80](https://linux-hardware.org/?probe=7e856f1c80) | Nov 18, 2023 |
| HP            | Laptop 17-ca2xxx            | [04b03f36a6](https://linux-hardware.org/?probe=04b03f36a6) | Nov 18, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0fcb08b949](https://linux-hardware.org/?probe=0fcb08b949) | Nov 18, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [0c33961f58](https://linux-hardware.org/?probe=0c33961f58) | Nov 17, 2023 |
| Dell          | Precision 5680              | [93a3cfb44e](https://linux-hardware.org/?probe=93a3cfb44e) | Nov 17, 2023 |
| HP            | Pavilion dv5                | [0ad6009c48](https://linux-hardware.org/?probe=0ad6009c48) | Nov 17, 2023 |
| HP            | Pavilion dv5                | [f79c95680b](https://linux-hardware.org/?probe=f79c95680b) | Nov 17, 2023 |
| HP            | EliteBook 840 G4            | [7d2d46e750](https://linux-hardware.org/?probe=7d2d46e750) | Nov 17, 2023 |
| Lenovo        | ThinkPad T570 20H9004FUS    | [6b52667081](https://linux-hardware.org/?probe=6b52667081) | Nov 17, 2023 |
| Lenovo        | ThinkPad T570 20H9004FUS    | [d60628038e](https://linux-hardware.org/?probe=d60628038e) | Nov 17, 2023 |
| Google        | Kano                        | [3a0f7846c4](https://linux-hardware.org/?probe=3a0f7846c4) | Nov 17, 2023 |
| Dell          | Latitude 3410               | [edb19e1704](https://linux-hardware.org/?probe=edb19e1704) | Nov 17, 2023 |
| Google        | Kano                        | [0c5e699794](https://linux-hardware.org/?probe=0c5e699794) | Nov 17, 2023 |
| HP            | Pavilion dv6                | [2aaedc3314](https://linux-hardware.org/?probe=2aaedc3314) | Nov 17, 2023 |
| Dell          | Latitude 5430 Rugged        | [a6dbcbf7a9](https://linux-hardware.org/?probe=a6dbcbf7a9) | Nov 17, 2023 |
| Lenovo        | ThinkPad P52s 20LB0026US    | [bdee77c684](https://linux-hardware.org/?probe=bdee77c684) | Nov 17, 2023 |
| Dell          | Latitude E6530              | [f43bd72db4](https://linux-hardware.org/?probe=f43bd72db4) | Nov 16, 2023 |
| Apple         | MacBookPro11,4              | [f21a42a965](https://linux-hardware.org/?probe=f21a42a965) | Nov 16, 2023 |
| Apple         | MacBookAir5,1               | [c431e70be5](https://linux-hardware.org/?probe=c431e70be5) | Nov 16, 2023 |
| Alienware     | m15 R7 AMD                  | [90a140aa10](https://linux-hardware.org/?probe=90a140aa10) | Nov 16, 2023 |
| Valve         | Jupiter                     | [10f96b411d](https://linux-hardware.org/?probe=10f96b411d) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fade86e55e](https://linux-hardware.org/?probe=fade86e55e) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [aca7636589](https://linux-hardware.org/?probe=aca7636589) | Nov 16, 2023 |
| MSI           | GF62 8RC                    | [8e186cf8b9](https://linux-hardware.org/?probe=8e186cf8b9) | Nov 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [7856865861](https://linux-hardware.org/?probe=7856865861) | Nov 16, 2023 |
| Apple         | MacBookPro9,2               | [ac7deed0de](https://linux-hardware.org/?probe=ac7deed0de) | Nov 16, 2023 |
| ASUSTek       | TP501UAM                    | [f4f66e877f](https://linux-hardware.org/?probe=f4f66e877f) | Nov 16, 2023 |
| Valve         | Jupiter                     | [af72567b85](https://linux-hardware.org/?probe=af72567b85) | Nov 16, 2023 |
| HP            | ENVY Laptop 17-cr1xxx       | [806f9b287d](https://linux-hardware.org/?probe=806f9b287d) | Nov 16, 2023 |
| Dell          | XPS 9315                    | [de79c7b970](https://linux-hardware.org/?probe=de79c7b970) | Nov 16, 2023 |
| Toshiba       | Satellite C55-C             | [30653c48a7](https://linux-hardware.org/?probe=30653c48a7) | Nov 15, 2023 |
| HP            | Laptop 14-ck0xxx            | [b082377950](https://linux-hardware.org/?probe=b082377950) | Nov 15, 2023 |
| Notebook      | PA70Hx                      | [14799f850b](https://linux-hardware.org/?probe=14799f850b) | Nov 15, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [ce6a10d6a3](https://linux-hardware.org/?probe=ce6a10d6a3) | Nov 15, 2023 |
| Apple         | MacBookPro11,1              | [3305f0e8ca](https://linux-hardware.org/?probe=3305f0e8ca) | Nov 15, 2023 |
| Valve         | Jupiter                     | [751a8a13dc](https://linux-hardware.org/?probe=751a8a13dc) | Nov 15, 2023 |
| Google        | Markarth                    | [5fb5241c23](https://linux-hardware.org/?probe=5fb5241c23) | Nov 15, 2023 |
| Dell          | XPS 13 9360                 | [b9f38bd221](https://linux-hardware.org/?probe=b9f38bd221) | Nov 15, 2023 |
| Dell          | Latitude 3340               | [2b92bb812f](https://linux-hardware.org/?probe=2b92bb812f) | Nov 15, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [7725a67bda](https://linux-hardware.org/?probe=7725a67bda) | Nov 15, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [d643e4ee02](https://linux-hardware.org/?probe=d643e4ee02) | Nov 15, 2023 |
| HP            | Laptop 14-fq0xxx            | [a5718f2f4d](https://linux-hardware.org/?probe=a5718f2f4d) | Nov 15, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [ccf529e662](https://linux-hardware.org/?probe=ccf529e662) | Nov 15, 2023 |
| HP            | ENVY m7 Notebook            | [9246faa417](https://linux-hardware.org/?probe=9246faa417) | Nov 15, 2023 |
| Eluktronic... | MAX-15                      | [42c14d9b39](https://linux-hardware.org/?probe=42c14d9b39) | Nov 15, 2023 |
| Alienware     | 18                          | [129d60c7cc](https://linux-hardware.org/?probe=129d60c7cc) | Nov 15, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [b89d3678bb](https://linux-hardware.org/?probe=b89d3678bb) | Nov 15, 2023 |
| Chuwi         | HeroBook Pro                | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| LG Electro... | 14Z90RS-K.AAW7U1            | [2921cb3437](https://linux-hardware.org/?probe=2921cb3437) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [018253183e](https://linux-hardware.org/?probe=018253183e) | Nov 14, 2023 |
| Dell          | Latitude 5580               | [3f5fba6417](https://linux-hardware.org/?probe=3f5fba6417) | Nov 14, 2023 |
| HP            | Laptop 15-dy2xxx            | [34d5626656](https://linux-hardware.org/?probe=34d5626656) | Nov 14, 2023 |
| Dell          | Latitude E5500              | [f6a14cca8f](https://linux-hardware.org/?probe=f6a14cca8f) | Nov 14, 2023 |
| Dell          | Inspiron 3543               | [305bd0b03f](https://linux-hardware.org/?probe=305bd0b03f) | Nov 14, 2023 |
| Dell          | G3 3779                     | [af4af2b0b5](https://linux-hardware.org/?probe=af4af2b0b5) | Nov 14, 2023 |
| MSI           | GS66 Stealth 10SF           | [99b8a18021](https://linux-hardware.org/?probe=99b8a18021) | Nov 14, 2023 |
| Dell          | XPS 17 9720                 | [d7e50818b4](https://linux-hardware.org/?probe=d7e50818b4) | Nov 14, 2023 |
| Dell          | G3 3779                     | [e48e3e3d67](https://linux-hardware.org/?probe=e48e3e3d67) | Nov 14, 2023 |
| Gateway       | P-7805u                     | [b613a7801b](https://linux-hardware.org/?probe=b613a7801b) | Nov 14, 2023 |
| HP            | EliteBook 8470p             | [a5def4d720](https://linux-hardware.org/?probe=a5def4d720) | Nov 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [94eceff0ed](https://linux-hardware.org/?probe=94eceff0ed) | Nov 14, 2023 |
| Dell          | Precision 7720              | [1f358e68ee](https://linux-hardware.org/?probe=1f358e68ee) | Nov 13, 2023 |
| Dell          | Precision 7720              | [facdc5c2a4](https://linux-hardware.org/?probe=facdc5c2a4) | Nov 13, 2023 |
| MSI           | GT70                        | [e2c0bb5bfe](https://linux-hardware.org/?probe=e2c0bb5bfe) | Nov 13, 2023 |
| HP            | 2000                        | [70a37e88d6](https://linux-hardware.org/?probe=70a37e88d6) | Nov 13, 2023 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | [ac6e58c0eb](https://linux-hardware.org/?probe=ac6e58c0eb) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [6b6cc6823a](https://linux-hardware.org/?probe=6b6cc6823a) | Nov 13, 2023 |
| Dell          | Latitude E4310              | [85fad762d0](https://linux-hardware.org/?probe=85fad762d0) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK U759               | [5b992613d3](https://linux-hardware.org/?probe=5b992613d3) | Nov 13, 2023 |
| Sony          | VGN-SZ750N                  | [aa0a3e3559](https://linux-hardware.org/?probe=aa0a3e3559) | Nov 13, 2023 |
| HP            | Laptop 15-dy2xxx            | [189c917237](https://linux-hardware.org/?probe=189c917237) | Nov 13, 2023 |
| HP            | ZBook 15 G2                 | [960b3732b0](https://linux-hardware.org/?probe=960b3732b0) | Nov 13, 2023 |
| HP            | Laptop 14-cm0xxx            | [e2b369a154](https://linux-hardware.org/?probe=e2b369a154) | Nov 13, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [f36053c77c](https://linux-hardware.org/?probe=f36053c77c) | Nov 13, 2023 |
| ASUSTek       | K54C                        | [a0369b192d](https://linux-hardware.org/?probe=a0369b192d) | Nov 13, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [226af1608f](https://linux-hardware.org/?probe=226af1608f) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [11995be92f](https://linux-hardware.org/?probe=11995be92f) | Nov 13, 2023 |
| SGIN          | M15                         | [6e69cd90eb](https://linux-hardware.org/?probe=6e69cd90eb) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2802d9278d](https://linux-hardware.org/?probe=2802d9278d) | Nov 13, 2023 |
| System76      | Lemur Pro                   | [35e6e1214c](https://linux-hardware.org/?probe=35e6e1214c) | Nov 12, 2023 |
| Acer          | Swift SF314-512             | [10902dfb11](https://linux-hardware.org/?probe=10902dfb11) | Nov 12, 2023 |
| Apple         | MacBookPro8,3               | [e9232ecc1b](https://linux-hardware.org/?probe=e9232ecc1b) | Nov 12, 2023 |
| Dell          | Precision M3800             | [b84dd534c9](https://linux-hardware.org/?probe=b84dd534c9) | Nov 12, 2023 |
| Dell          | Inspiron 1545               | [b92eb60192](https://linux-hardware.org/?probe=b92eb60192) | Nov 12, 2023 |
| HP            | Pavilion dv6700             | [27e526a564](https://linux-hardware.org/?probe=27e526a564) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9dd24e5aaa](https://linux-hardware.org/?probe=9dd24e5aaa) | Nov 12, 2023 |
| Acer          | Predator PH315-54           | [836439ab9f](https://linux-hardware.org/?probe=836439ab9f) | Nov 12, 2023 |
| AMI           | Intel                       | [edd354c62b](https://linux-hardware.org/?probe=edd354c62b) | Nov 12, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [63c1b9a13e](https://linux-hardware.org/?probe=63c1b9a13e) | Nov 12, 2023 |
| HP            | EliteBook 8470p             | [87ddc0384e](https://linux-hardware.org/?probe=87ddc0384e) | Nov 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/USA/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 2079      | 10.53%  |
| Ubuntu 22.04      | 1122      | 5.68%   |
| Debian 11         | 1105      | 5.6%    |
| Ubuntu 18.04      | 954       | 4.83%   |
| Pop!_OS 22.04     | 596       | 3.02%   |
| Zorin 16          | 432       | 2.19%   |
| Arch Rolling      | 370       | 1.87%   |
| Arch              | 325       | 1.65%   |
| Manjaro           | 313       | 1.59%   |
| Linux Mint 20.3   | 282       | 1.43%   |
| KDE neon 20.04    | 281       | 1.42%   |
| Pop!_OS 21.04     | 279       | 1.41%   |
| Fedora 38         | 262       | 1.33%   |
| Pop!_OS 20.04     | 254       | 1.29%   |
| Pop!_OS 20.10     | 250       | 1.27%   |
| Debian 12         | 242       | 1.23%   |
| Fedora 36         | 225       | 1.14%   |
| OpenMandriva 4.3  | 215       | 1.09%   |
| Linux Mint 21.1   | 215       | 1.09%   |
| ArcoLinux Rolling | 215       | 1.09%   |
| Linux Mint 20.2   | 205       | 1.04%   |
| OpenMandriva 4.2  | 203       | 1.03%   |
| Linux Mint 20.1   | 202       | 1.02%   |
| Zorin 15          | 187       | 0.95%   |
| Ubuntu 20.10      | 184       | 0.93%   |
| Ubuntu 19.10      | 179       | 0.91%   |
| Linux Mint 21.2   | 177       | 0.9%    |
| Linux Mint 19.3   | 175       | 0.89%   |
| Pop!_OS 21.10     | 173       | 0.88%   |
| Fedora 37         | 173       | 0.88%   |
| Xubuntu 20.04     | 169       | 0.86%   |
| Linux Mint 20     | 167       | 0.85%   |
| Ubuntu 21.10      | 162       | 0.82%   |
| Fedora 35         | 159       | 0.81%   |
| Fedora 33         | 149       | 0.75%   |
| Ubuntu 22.10      | 148       | 0.75%   |
| Fedora 32         | 148       | 0.75%   |
| Fedora 34         | 147       | 0.74%   |
| Ubuntu 19.04      | 140       | 0.71%   |
| Ubuntu 21.04      | 138       | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 5134      | 27.51%  |
| Linux Mint    | 1586      | 8.5%    |
| Pop!_OS       | 1485      | 7.96%   |
| Debian        | 1470      | 7.88%   |
| Fedora        | 1352      | 7.24%   |
| OpenMandriva  | 877       | 4.7%    |
| Arch          | 682       | 3.65%   |
| Zorin         | 649       | 3.48%   |
| Manjaro       | 591       | 3.17%   |
| SteamOS       | 479       | 2.57%   |
| KDE neon      | 433       | 2.32%   |
| Kubuntu       | 396       | 2.12%   |
| Xubuntu       | 335       | 1.8%    |
| Kali          | 275       | 1.47%   |
| ArcoLinux     | 233       | 1.25%   |
| openSUSE      | 190       | 1.02%   |
| Endless       | 164       | 0.88%   |
| Elementary    | 156       | 0.84%   |
| Gentoo        | 152       | 0.81%   |
| EndeavourOS   | 151       | 0.81%   |
| Lubuntu       | 129       | 0.69%   |
| Parrot        | 109       | 0.58%   |
| Clear Linux   | 106       | 0.57%   |
| Ubuntu Unity  | 102       | 0.55%   |
| ROSA          | 98        | 0.53%   |
| Ubuntu MATE   | 95        | 0.51%   |
| MX            | 85        | 0.46%   |
| Nobara        | 84        | 0.45%   |
| LMDE          | 82        | 0.44%   |
| Garuda Linux  | 81        | 0.43%   |
| BlackPanther  | 74        | 0.4%    |
| Ubuntu Budgie | 55        | 0.29%   |
| Peppermint    | 51        | 0.27%   |
| RHEL          | 37        | 0.2%    |
| Xero          | 35        | 0.19%   |
| NixOS         | 34        | 0.18%   |
| CentOS        | 33        | 0.18%   |
| Artix         | 31        | 0.17%   |
| Rocky Linux   | 25        | 0.13%   |
| LinuxFX       | 23        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.0-10-amd64          | 402       | 1.86%   |
| 5.10.0-8-amd64           | 303       | 1.4%    |
| 5.4.0-42-generic         | 292       | 1.35%   |
| 5.16.7-desktop-1omv4003  | 206       | 0.95%   |
| 5.13.0-valve36-1-neptune | 192       | 0.89%   |
| 5.10.14-desktop-1omv4002 | 190       | 0.88%   |
| 5.15.0-56-generic        | 189       | 0.87%   |
| 6.2.6-76060206-generic   | 152       | 0.7%    |
| 5.4.0-58-generic         | 152       | 0.7%    |
| 5.11.0-7620-generic      | 147       | 0.68%   |
| 5.15.0-58-generic        | 143       | 0.66%   |
| 6.2.6-desktop-1omv2390   | 128       | 0.59%   |
| 5.4.0-48-generic         | 127       | 0.59%   |
| 5.4.0-29-generic         | 124       | 0.57%   |
| 5.4.0-26-generic         | 116       | 0.54%   |
| 6.1.1-desktop-1omv2290   | 114       | 0.53%   |
| 5.3.0-28-generic         | 114       | 0.53%   |
| 5.15.0-52-generic        | 114       | 0.53%   |
| 5.4.0-52-generic         | 103       | 0.48%   |
| 5.10.0-20-amd64          | 103       | 0.48%   |
| 5.8.0-7630-generic       | 101       | 0.47%   |
| 5.15.0-46-generic        | 100       | 0.46%   |
| 5.11.0-38-generic        | 99        | 0.46%   |
| 5.4.0-91-generic         | 96        | 0.44%   |
| 5.15.0-48-generic        | 95        | 0.44%   |
| 5.11.0-37-generic        | 95        | 0.44%   |
| 5.15.0-41-generic        | 94        | 0.43%   |
| 5.13.0-39-generic        | 92        | 0.42%   |
| 6.1.0-13-amd64           | 91        | 0.42%   |
| 5.3.0-46-generic         | 91        | 0.42%   |
| 5.11.0-27-generic        | 91        | 0.42%   |
| 6.2.0-26-generic         | 88        | 0.41%   |
| 5.4.0-40-generic         | 88        | 0.41%   |
| 6.0.12-76060006-generic  | 87        | 0.4%    |
| 5.13.0-30-generic        | 85        | 0.39%   |
| 5.15.0-43-generic        | 84        | 0.39%   |
| 5.8.0-43-generic         | 81        | 0.37%   |
| 5.4.0-65-generic         | 79        | 0.36%   |
| 5.10.0-16-amd64          | 79        | 0.36%   |
| 5.4.0-7634-generic       | 77        | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 2760      | 13.54%  |
| 5.15.0  | 1784      | 8.75%   |
| 5.10.0  | 1260      | 6.18%   |
| 5.13.0  | 1217      | 5.97%   |
| 5.11.0  | 1036      | 5.08%   |
| 5.8.0   | 920       | 4.51%   |
| 4.15.0  | 737       | 3.62%   |
| 5.19.0  | 674       | 3.31%   |
| 5.3.0   | 656       | 3.22%   |
| 6.2.0   | 545       | 2.67%   |
| 5.0.0   | 392       | 1.92%   |
| 6.1.0   | 361       | 1.77%   |
| 4.18.0  | 301       | 1.48%   |
| 6.2.6   | 292       | 1.43%   |
| 5.16.7  | 209       | 1.03%   |
| 5.10.14 | 193       | 0.95%   |
| 6.1.1   | 138       | 0.68%   |
| 4.19.0  | 136       | 0.67%   |
| 6.5.0   | 123       | 0.6%    |
| 5.14.0  | 121       | 0.59%   |
| 6.0.12  | 109       | 0.53%   |
| 5.17.5  | 98        | 0.48%   |
| 5.18.0  | 82        | 0.4%    |
| 6.0.0   | 79        | 0.39%   |
| 6.4.11  | 76        | 0.37%   |
| 6.1.52  | 72        | 0.35%   |
| 6.6.2   | 71        | 0.35%   |
| 6.5.6   | 68        | 0.33%   |
| 6.4.6   | 66        | 0.32%   |
| 6.1.11  | 59        | 0.29%   |
| 6.5.5   | 57        | 0.28%   |
| 4.18.16 | 57        | 0.28%   |
| 6.3.5   | 54        | 0.27%   |
| 6.2.9   | 49        | 0.24%   |
| 5.18.10 | 49        | 0.24%   |
| 5.16.11 | 49        | 0.24%   |
| 4.4.0   | 47        | 0.23%   |
| 5.15.5  | 46        | 0.23%   |
| 5.9.16  | 45        | 0.22%   |
| 5.15.15 | 44        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 2931      | 14.6%   |
| 5.15    | 2252      | 11.21%  |
| 5.10    | 1690      | 8.42%   |
| 5.13    | 1376      | 6.85%   |
| 5.11    | 1161      | 5.78%   |
| 5.8     | 1114      | 5.55%   |
| 6.2     | 1078      | 5.37%   |
| 6.1     | 907       | 4.52%   |
| 5.19    | 858       | 4.27%   |
| 4.15    | 739       | 3.68%   |
| 5.3     | 727       | 3.62%   |
| 5.16    | 524       | 2.61%   |
| 6.5     | 434       | 2.16%   |
| 6.0     | 426       | 2.12%   |
| 5.0     | 419       | 2.09%   |
| 4.18    | 366       | 1.82%   |
| 5.18    | 358       | 1.78%   |
| 6.4     | 337       | 1.68%   |
| 5.17    | 303       | 1.51%   |
| 5.14    | 293       | 1.46%   |
| 6.3     | 282       | 1.4%    |
| 6.6     | 210       | 1.05%   |
| 5.9     | 208       | 1.04%   |
| 4.19    | 186       | 0.93%   |
| 5.6     | 182       | 0.91%   |
| 5.12    | 152       | 0.76%   |
| 5.7     | 133       | 0.66%   |
| 5.5     | 100       | 0.5%    |
| 4.9     | 79        | 0.39%   |
| 4.4     | 57        | 0.28%   |
| 5.2     | 41        | 0.2%    |
| 5.1     | 24        | 0.12%   |
| 4.16    | 22        | 0.11%   |
| 4.12    | 20        | 0.1%    |
| 3.10    | 15        | 0.07%   |
| 4.1     | 12        | 0.06%   |
| 4.20    | 11        | 0.05%   |
| 4.14    | 11        | 0.05%   |
| 4.13    | 11        | 0.05%   |
| 4.10    | 6         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 17518     | 98.06%  |
| i686    | 318       | 1.78%   |
| aarch64 | 27        | 0.15%   |
| armv7l  | 2         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 8186      | 43.82%  |
| KDE5             | 3272      | 17.52%  |
| Unknown          | 2432      | 13.02%  |
| XFCE             | 1364      | 7.3%    |
| X-Cinnamon       | 1278      | 6.84%   |
| MATE             | 472       | 2.53%   |
| KDE              | 426       | 2.28%   |
| Cinnamon         | 177       | 0.95%   |
| LXQt             | 169       | 0.9%    |
| Pantheon         | 145       | 0.78%   |
| Unity            | 102       | 0.55%   |
| Budgie           | 101       | 0.54%   |
| i3               | 87        | 0.47%   |
| LXDE             | 74        | 0.4%    |
| GNOME Flashback  | 55        | 0.29%   |
| KDE4             | 53        | 0.28%   |
| GNOME Classic    | 30        | 0.16%   |
| Deepin           | 29        | 0.16%   |
| sway             | 24        | 0.13%   |
| awesome          | 23        | 0.12%   |
| Hyprland         | 21        | 0.11%   |
| Enlightenment    | 17        | 0.09%   |
| lightdm-xsession | 16        | 0.09%   |
| DWM              | 14        | 0.07%   |
| Openbox          | 11        | 0.06%   |
| xmonad           | 10        | 0.05%   |
| trinity          | 10        | 0.05%   |
| bspwm            | 10        | 0.05%   |
| ICEWM            | 8         | 0.04%   |
| qtile            | 7         | 0.04%   |
| BunsenLabs       | 7         | 0.04%   |
| LeftWM           | 5         | 0.03%   |
| Xsession         | 4         | 0.02%   |
| fluxbox          | 4         | 0.02%   |
| none+i3          | 3         | 0.02%   |
| gamescope        | 3         | 0.02%   |
| xubuntu          | 2         | 0.01%   |
| none+xmonad      | 2         | 0.01%   |
| KDE6             | 2         | 0.01%   |
| i3-with-shmlog   | 2         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 13200     | 71.65%  |
| Wayland     | 3374      | 18.31%  |
| Unknown     | 1623      | 8.81%   |
| Tty         | 225       | 1.22%   |
| Unspecified | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 10051     | 54.22%  |
| SDDM    | 2287      | 12.34%  |
| GDM3    | 2095      | 11.3%   |
| LightDM | 1771      | 9.55%   |
| GDM     | 1723      | 9.29%   |
| TDM     | 437       | 2.36%   |
| KDM     | 54        | 0.29%   |
| XDM     | 33        | 0.18%   |
| LXDM    | 30        | 0.16%   |
| SLiM    | 25        | 0.13%   |
| GREETD  | 10        | 0.05%   |
| Ly      | 8         | 0.04%   |
| MDM     | 5         | 0.03%   |
| EMPTTY  | 5         | 0.03%   |
| NODM    | 2         | 0.01%   |
| SLIMSKI | 1         | 0.01%   |
| LEMURS  | 1         | 0.01%   |
| LDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 15146     | 83.63%  |
| Unknown    | 2191      | 12.1%   |
| C          | 374       | 2.07%   |
| en_CA      | 105       | 0.58%   |
| en_GB      | 57        | 0.31%   |
| zh_CN      | 37        | 0.2%    |
| POSIX      | 18        | 0.1%    |
| C.UTF8     | 18        | 0.1%    |
| es_US      | 15        | 0.08%   |
| en_AU      | 13        | 0.07%   |
| ru_RU      | 12        | 0.07%   |
| fr_FR      | 12        | 0.07%   |
| en_IN      | 11        | 0.06%   |
| es_ES      | 10        | 0.06%   |
| de_DE      | 9         | 0.05%   |
| pl_PL      | 8         | 0.04%   |
| es_MX      | 7         | 0.04%   |
| it_IT      | 5         | 0.03%   |
| es_VE      | 4         | 0.02%   |
| en-US      | 4         | 0.02%   |
| unm_US     | 3         | 0.02%   |
| pt_BR      | 3         | 0.02%   |
| fr_CA      | 3         | 0.02%   |
| en_IE      | 3         | 0.02%   |
| ru_UA      | 2         | 0.01%   |
| ro_RO      | 2         | 0.01%   |
| ko_KR      | 2         | 0.01%   |
| es_CR      | 2         | 0.01%   |
| es_CO      | 2         | 0.01%   |
| eo_US      | 2         | 0.01%   |
| en_US.UTF8 | 2         | 0.01%   |
| en_PH      | 2         | 0.01%   |
| ca_ES      | 2         | 0.01%   |
| uk_UA      | 1         | 0.01%   |
| tr_TR      | 1         | 0.01%   |
| osa_US     | 1         | 0.01%   |
| ja_JP      | 1         | 0.01%   |
| he_IL      | 1         | 0.01%   |
| fr_CH      | 1         | 0.01%   |
| es_SV      | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 9514      | 51.88%  |
| BIOS | 8824      | 48.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 12572     | 68.38%  |
| Btrfs               | 2387      | 12.98%  |
| Overlay             | 1856      | 10.09%  |
| Tmpfs               | 570       | 3.1%    |
| Unknown             | 448       | 2.44%   |
| Xfs                 | 275       | 1.5%    |
| Zfs                 | 183       | 1%      |
| Ext2                | 37        | 0.2%    |
| Ext3                | 21        | 0.11%   |
| F2fs                | 20        | 0.11%   |
| Reiserfs            | 5         | 0.03%   |
| Jfs                 | 3         | 0.02%   |
| XXXXX               | 2         | 0.01%   |
| Rootfs              | 2         | 0.01%   |
| Aufs                | 2         | 0.01%   |
| XXXXXXX             | 1         | 0.01%   |
| SquasXfs            | 1         | 0.01%   |
| Fuse.fuse-overlayfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 9733      | 53.12%  |
| GPT     | 7189      | 39.24%  |
| MBR     | 1399      | 7.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 16034     | 88.32%  |
| Yes       | 2120      | 11.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 14712     | 81.23%  |
| Yes       | 3399      | 18.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 3786      | 21.2%   |
| Hewlett-Packard                | 3443      | 19.28%  |
| Lenovo                         | 3196      | 17.9%   |
| Apple                          | 1407      | 7.88%   |
| ASUSTek Computer               | 1283      | 7.18%   |
| Acer                           | 797       | 4.46%   |
| Toshiba                        | 612       | 3.43%   |
| Google                         | 510       | 2.86%   |
| Valve                          | 452       | 2.53%   |
| MSI                            | 365       | 2.04%   |
| System76                       | 280       | 1.57%   |
| Alienware                      | 161       | 0.9%    |
| Sony                           | 144       | 0.81%   |
| GPU Company                    | 118       | 0.66%   |
| Unknown                        | 114       | 0.64%   |
| Samsung Electronics            | 105       | 0.59%   |
| Framework                      | 104       | 0.58%   |
| Gateway                        | 98        | 0.55%   |
| Razer                          | 83        | 0.46%   |
| Notebook                       | 75        | 0.42%   |
| Panasonic                      | 71        | 0.4%    |
| Gigabyte Technology            | 55        | 0.31%   |
| Fujitsu                        | 41        | 0.23%   |
| LG Electronics                 | 37        | 0.21%   |
| HUAWEI                         | 33        | 0.18%   |
| Eluktronics                    | 21        | 0.12%   |
| AMI                            | 21        | 0.12%   |
| GPD                            | 18        | 0.1%    |
| Pine Microsystems              | 17        | 0.1%    |
| Chuwi                          | 17        | 0.1%    |
| Purism                         | 16        | 0.09%   |
| AZW                            | 16        | 0.09%   |
| MOTILE                         | 13        | 0.07%   |
| Matsushita Electric Industrial | 12        | 0.07%   |
| Getac                          | 12        | 0.07%   |
| EVOO                           | 12        | 0.07%   |
| IBM                            | 10        | 0.06%   |
| TUXEDO                         | 9         | 0.05%   |
| Timi                           | 9         | 0.05%   |
| Micro Electronics              | 9         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Valve Jupiter         | 435       | 2.44%   |
| Apple MacBook5,2      | 366       | 2.05%   |
| Unknown               | 147       | 0.82%   |
| HP Notebook           | 131       | 0.73%   |
| Apple MacBookAir7,2   | 127       | 0.71%   |
| Apple MacBookAir7,1   | 91        | 0.51%   |
| HP Pavilion dv7       | 86        | 0.48%   |
| Dell Latitude E6420   | 84        | 0.47%   |
| Dell Latitude E6430   | 80        | 0.45%   |
| Google Enguarde       | 79        | 0.44%   |
| HP 2000               | 70        | 0.39%   |
| Framework Laptop      | 68        | 0.38%   |
| HP Pavilion Notebook  | 67        | 0.38%   |
| Apple MacBookPro9,2   | 64        | 0.36%   |
| HP Pavilion dv6       | 61        | 0.34%   |
| HP 15 Notebook PC     | 61        | 0.34%   |
| Apple MacBookPro8,1   | 60        | 0.34%   |
| Apple MacBook2,1      | 60        | 0.34%   |
| Dell Latitude E6410   | 56        | 0.31%   |
| HP Pavilion g7        | 51        | 0.29%   |
| System76 Oryx Pro     | 50        | 0.28%   |
| Dell Latitude E6400   | 49        | 0.27%   |
| HP 15                 | 48        | 0.27%   |
| System76 Gazelle      | 47        | 0.26%   |
| GPU Company GWTC116-2 | 47        | 0.26%   |
| Google Reks           | 47        | 0.26%   |
| Dell XPS 13 9370      | 47        | 0.26%   |
| Dell XPS 15 9500      | 46        | 0.26%   |
| HP Laptop 15-db0xxx   | 45        | 0.25%   |
| Dell XPS 15 9570      | 45        | 0.25%   |
| Dell XPS 15 7590      | 45        | 0.25%   |
| Dell Inspiron 1545    | 44        | 0.25%   |
| Dell XPS 15 9560      | 42        | 0.24%   |
| Dell XPS 13 9300      | 41        | 0.23%   |
| System76 Lemur Pro    | 40        | 0.22%   |
| HP Pavilion g6        | 39        | 0.22%   |
| Dell XPS 13 9360      | 39        | 0.22%   |
| Dell Latitude E7440   | 39        | 0.22%   |
| Dell Inspiron 3521    | 39        | 0.22%   |
| Apple MacBook4,1      | 39        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 2045      | 11.45%  |
| Dell Latitude      | 1329      | 7.44%   |
| Dell Inspiron      | 1103      | 6.18%   |
| HP Pavilion        | 746       | 4.18%   |
| Lenovo IdeaPad     | 659       | 3.69%   |
| HP Laptop          | 642       | 3.6%    |
| Dell XPS           | 618       | 3.46%   |
| Toshiba Satellite  | 558       | 3.12%   |
| Acer Aspire        | 527       | 2.95%   |
| HP EliteBook       | 484       | 2.71%   |
| Valve Jupiter      | 435       | 2.44%   |
| Dell Precision     | 406       | 2.27%   |
| Apple MacBook5     | 381       | 2.13%   |
| HP ProBook         | 283       | 1.58%   |
| Apple MacBookAir7  | 218       | 1.22%   |
| ASUS ROG           | 205       | 1.15%   |
| ASUS VivoBook      | 194       | 1.09%   |
| HP ENVY            | 187       | 1.05%   |
| Lenovo Legion      | 153       | 0.86%   |
| Unknown            | 147       | 0.82%   |
| HP ZBook           | 135       | 0.76%   |
| HP Stream          | 133       | 0.74%   |
| HP Notebook        | 131       | 0.73%   |
| HP 15              | 120       | 0.67%   |
| Apple MacBookPro8  | 110       | 0.62%   |
| Apple MacBookPro11 | 106       | 0.59%   |
| Framework Laptop   | 104       | 0.58%   |
| Acer Nitro         | 98        | 0.55%   |
| HP OMEN            | 94        | 0.53%   |
| HP Compaq          | 88        | 0.49%   |
| Apple MacBookPro9  | 87        | 0.49%   |
| ASUS Zenbook       | 84        | 0.47%   |
| Razer Blade        | 82        | 0.46%   |
| Google Enguarde    | 79        | 0.44%   |
| ASUS ASUS          | 75        | 0.42%   |
| Acer Swift         | 73        | 0.41%   |
| Dell Vostro        | 71        | 0.4%    |
| HP 2000            | 70        | 0.39%   |
| Dell Studio        | 63        | 0.35%   |
| Apple MacBook2     | 60        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 1567      | 8.77%   |
| 2020    | 1538      | 8.61%   |
| 2021    | 1412      | 7.91%   |
| 2018    | 1397      | 7.82%   |
| 2011    | 1304      | 7.3%    |
| 2012    | 1279      | 7.16%   |
| 2022    | 1206      | 6.75%   |
| 2013    | 1100      | 6.16%   |
| 2015    | 971       | 5.44%   |
| 2017    | 963       | 5.39%   |
| 2016    | 919       | 5.15%   |
| 2014    | 909       | 5.09%   |
| 2009    | 794       | 4.45%   |
| 2010    | 729       | 4.08%   |
| 2008    | 703       | 3.94%   |
| 2007    | 457       | 2.56%   |
| 2023    | 392       | 2.2%    |
| 2006    | 98        | 0.55%   |
| 2005    | 46        | 0.26%   |
| Unknown | 41        | 0.23%   |
| 2003    | 16        | 0.09%   |
| 2004    | 15        | 0.08%   |
| 2002    | 2         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 17858     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 16398     | 90.87%  |
| Enabled  | 1648      | 9.13%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 17144     | 95.98%  |
| Yes  | 718       | 4.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 4457      | 24.59%  |
| 3.01-4.0        | 3580      | 19.75%  |
| 8.01-16.0       | 3328      | 18.36%  |
| 16.01-24.0      | 3212      | 17.72%  |
| 32.01-64.0      | 1573      | 8.68%   |
| 1.01-2.0        | 937       | 5.17%   |
| 64.01-256.0     | 417       | 2.3%    |
| 2.01-3.0        | 261       | 1.44%   |
| 24.01-32.0      | 240       | 1.32%   |
| 0.51-1.0        | 103       | 0.57%   |
| 0.01-0.5        | 15        | 0.08%   |
| More than 256.0 | 1         | 0.01%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 7317      | 36.83%  |
| 2.01-3.0   | 4961      | 24.97%  |
| 4.01-8.0   | 2919      | 14.69%  |
| 3.01-4.0   | 2716      | 13.67%  |
| 0.51-1.0   | 1006      | 5.06%   |
| 8.01-16.0  | 687       | 3.46%   |
| 0.01-0.5   | 150       | 0.75%   |
| 16.01-24.0 | 67        | 0.34%   |
| 24.01-32.0 | 28        | 0.14%   |
| 32.01-64.0 | 14        | 0.07%   |
| Unknown    | 3         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 13310     | 72.4%   |
| 2      | 4158      | 22.62%  |
| 3      | 596       | 3.24%   |
| 0      | 195       | 1.06%   |
| 4      | 92        | 0.5%    |
| 5      | 23        | 0.13%   |
| 6      | 6         | 0.03%   |
| 7      | 5         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11394     | 63.45%  |
| Yes       | 6564      | 36.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13584     | 75.6%   |
| No        | 4384      | 24.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 17603     | 98.46%  |
| No        | 276       | 1.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 13771     | 76.2%   |
| No        | 4300      | 23.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| USA     | 17858     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Bangor           | 676       | 3.55%   |
| Los Angeles      | 277       | 1.46%   |
| New York         | 266       | 1.4%    |
| Chicago          | 233       | 1.22%   |
| Seattle          | 232       | 1.22%   |
| Dover-Foxcroft   | 229       | 1.2%    |
| Dallas           | 213       | 1.12%   |
| Portland         | 197       | 1.04%   |
| Houston          | 189       | 0.99%   |
| Denver           | 185       | 0.97%   |
| Atlanta          | 155       | 0.81%   |
| Phoenix          | 144       | 0.76%   |
| Austin           | 125       | 0.66%   |
| Brooklyn         | 121       | 0.64%   |
| Minneapolis      | 112       | 0.59%   |
| San Jose         | 108       | 0.57%   |
| Miami            | 107       | 0.56%   |
| San Antonio      | 106       | 0.56%   |
| Las Vegas        | 106       | 0.56%   |
| San Francisco    | 100       | 0.53%   |
| Washington       | 99        | 0.52%   |
| San Diego        | 94        | 0.49%   |
| Charlotte        | 87        | 0.46%   |
| Kansas City      | 79        | 0.42%   |
| Tucson           | 75        | 0.39%   |
| Philadelphia     | 74        | 0.39%   |
| Columbus         | 74        | 0.39%   |
| Albuquerque      | 70        | 0.37%   |
| Orlando          | 69        | 0.36%   |
| Pittsburgh       | 68        | 0.36%   |
| Rockville        | 67        | 0.35%   |
| Raleigh          | 66        | 0.35%   |
| Jacksonville     | 66        | 0.35%   |
| Salt Lake City   | 65        | 0.34%   |
| Rochester        | 62        | 0.33%   |
| Indianapolis     | 61        | 0.32%   |
| Colorado Springs | 61        | 0.32%   |
| St Louis         | 60        | 0.32%   |
| Queens           | 56        | 0.29%   |
| Saint Paul       | 55        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 3444      | 4911   | 15.42%  |
| Seagate                     | 2123      | 2795   | 9.51%   |
| WDC                         | 2074      | 2622   | 9.29%   |
| Unknown                     | 2006      | 2618   | 8.98%   |
| Toshiba                     | 1761      | 2170   | 7.89%   |
| SanDisk                     | 1517      | 1935   | 6.79%   |
| SK hynix                    | 941       | 1159   | 4.21%   |
| Crucial                     | 660       | 894    | 2.96%   |
| Hitachi                     | 637       | 774    | 2.85%   |
| Intel                       | 624       | 858    | 2.79%   |
| HGST                        | 623       | 823    | 2.79%   |
| Apple                       | 614       | 790    | 2.75%   |
| Kingston                    | 558       | 697    | 2.5%    |
| Micron Technology           | 483       | 564    | 2.16%   |
| Fujitsu                     | 406       | 434    | 1.82%   |
| PNY                         | 265       | 333    | 1.19%   |
| Unknown                     | 213       | 247    | 0.95%   |
| Phison Electronics          | 201       | 237    | 0.9%    |
| Phison                      | 200       | 251    | 0.9%    |
| KIOXIA                      | 196       | 262    | 0.88%   |
| SPCC                        | 187       | 223    | 0.84%   |
| China                       | 179       | 216    | 0.8%    |
| A-DATA Technology           | 178       | 225    | 0.8%    |
| Kingston Technology Company | 142       | 171    | 0.64%   |
| LITEON                      | 139       | 164    | 0.62%   |
| LITEONIT                    | 112       | 142    | 0.5%    |
| Micron/Crucial Technology   | 110       | 152    | 0.49%   |
| SABRENT                     | 105       | 125    | 0.47%   |
| Silicon Motion              | 104       | 132    | 0.47%   |
| Team                        | 80        | 97     | 0.36%   |
| Hewlett-Packard             | 65        | 88     | 0.29%   |
| O2 Micro                    | 63        | 69     | 0.28%   |
| JMicron Technology          | 55        | 62     | 0.25%   |
| Transcend                   | 49        | 58     | 0.22%   |
| ASMT                        | 45        | 67     | 0.2%    |
| OCZ                         | 44        | 49     | 0.2%    |
| Mushkin                     | 44        | 71     | 0.2%    |
| Dogfish                     | 36        | 40     | 0.16%   |
| BHT                         | 36        | 45     | 0.16%   |
| Netac                       | 32        | 39     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 327       | 1.4%    |
| Unknown MMC Card  64GB                              | 310       | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB                      | 254       | 1.08%   |
| Fujitsu MHZ2160BH FFS G1 160GB                      | 242       | 1.03%   |
| Toshiba MQ01ABD100 1TB                              | 226       | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 216       | 0.92%   |
| Unknown                                             | 213       | 0.91%   |
| Unknown MMC Card  128GB                             | 187       | 0.8%    |
| HGST HTS721010A9E630 1TB                            | 182       | 0.78%   |
| Toshiba MQ01ABF050 500GB                            | 157       | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 152       | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 145       | 0.62%   |
| Seagate ST500LT012-1DG142 500GB                     | 141       | 0.6%    |
| Samsung SSD 860 EVO 500GB                           | 139       | 0.59%   |
| Samsung NVMe SSD Drive 512GB                        | 136       | 0.58%   |
| Unknown SD/MMC/MS PRO 512GB                         | 132       | 0.56%   |
| Unknown MMC Card  16GB                              | 128       | 0.55%   |
| Toshiba MQ04ABF100 1TB                              | 124       | 0.53%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 123       | 0.53%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 116       | 0.5%    |
| Apple SSD SM0128G 121GB                             | 116       | 0.5%    |
| Unknown MMC Card  512GB                             | 112       | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 110       | 0.47%   |
| Samsung NVMe SSD Drive 1TB                          | 104       | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 98        | 0.42%   |
| SABRENT Disk 2TB                                    | 96        | 0.41%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 89        | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 88        | 0.38%   |
| Seagate ST9500325AS 500GB                           | 87        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                        | 86        | 0.37%   |
| HGST HTS541010A9E680 1TB                            | 85        | 0.36%   |
| SK hynix NVMe SSD Drive 512GB                       | 84        | 0.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 84        | 0.36%   |
| Samsung SSD 850 EVO 500GB                           | 84        | 0.36%   |
| Unknown MMC Card  256GB                             | 83        | 0.35%   |
| HGST HTS545050A7E680 500GB                          | 83        | 0.35%   |
| Apple SSD AP0128H 121GB                             | 81        | 0.35%   |
| Crucial CT500MX500SSD1 500GB                        | 80        | 0.34%   |
| Samsung NVMe SSD Drive 500GB                        | 78        | 0.33%   |
| Samsung SSD 970 EVO Plus 1TB                        | 75        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 2034      | 2658    | 30.16%  |
| WDC                 | 1327      | 1660    | 19.68%  |
| Toshiba             | 1237      | 1510    | 18.34%  |
| Hitachi             | 637       | 774     | 9.45%   |
| HGST                | 622       | 822     | 9.22%   |
| Fujitsu             | 406       | 434     | 6.02%   |
| Unknown             | 135       | 175     | 2%      |
| SABRENT             | 101       | 120     | 1.5%    |
| Samsung Electronics | 75        | 84      | 1.11%   |
| Apple               | 57        | 77      | 0.85%   |
| SSK                 | 13        | 14      | 0.19%   |
| External            | 12        | 14      | 0.18%   |
| ASMT                | 11        | 22      | 0.16%   |
| USB3.0              | 9         | 12      | 0.13%   |
| TO Exter            | 9         | 10      | 0.13%   |
| IBM/Hitachi         | 9         | 12      | 0.13%   |
| JMicron Technology  | 7         | 11      | 0.1%    |
| Apricorn            | 6         | 8       | 0.09%   |
| HGST HTS            | 5         | 7       | 0.07%   |
| KESU                | 4         | 4       | 0.06%   |
| LaCie               | 3         | 3       | 0.04%   |
| USB                 | 2         | 2       | 0.03%   |
| Pioneer             | 2         | 2       | 0.03%   |
| Maxone              | 2         | 2       | 0.03%   |
| MaxDigital          | 2         | 2       | 0.03%   |
| Inateck             | 2         | 2       | 0.03%   |
| Generic-            | 2         | 3       | 0.03%   |
| StoreJet            | 1         | 1       | 0.01%   |
| RSH-339             | 1         | 1       | 0.01%   |
| RSH-319             | 1         | 1       | 0.01%   |
| Maxtor              | 1         | 1       | 0.01%   |
| Magnetic Data       | 1         | 2       | 0.01%   |
| HGST HDN            | 1         | 1       | 0.01%   |
| Hewlett-Packard     | 1         | 1       | 0.01%   |
| Dell                | 1         | 1       | 0.01%   |
| DAS                 | 1         | 4       | 0.01%   |
| Asm                 | 1         | 1       | 0.01%   |
| ACASIS              | 1         | 1       | 0.01%   |
| AAPL                | 1         | Unknown | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1517      | 2085   | 23.25%  |
| SanDisk             | 717       | 927    | 10.99%  |
| Crucial             | 577       | 793    | 8.84%   |
| Kingston            | 375       | 479    | 5.75%   |
| WDC                 | 365       | 493    | 5.59%   |
| Apple               | 355       | 407    | 5.44%   |
| PNY                 | 257       | 323    | 3.94%   |
| Intel               | 201       | 250    | 3.08%   |
| Micron Technology   | 189       | 223    | 2.9%    |
| SK hynix            | 183       | 221    | 2.8%    |
| China               | 179       | 216    | 2.74%   |
| SPCC                | 161       | 194    | 2.47%   |
| A-DATA Technology   | 152       | 193    | 2.33%   |
| Toshiba             | 150       | 189    | 2.3%    |
| LITEON              | 126       | 151    | 1.93%   |
| LITEONIT            | 112       | 142    | 1.72%   |
| Team                | 67        | 82     | 1.03%   |
| Hewlett-Packard     | 54        | 76     | 0.83%   |
| Transcend           | 46        | 51     | 0.7%    |
| OCZ                 | 43        | 48     | 0.66%   |
| Mushkin             | 40        | 67     | 0.61%   |
| Dogfish             | 36        | 40     | 0.55%   |
| BHT                 | 36        | 45     | 0.55%   |
| ASMT                | 32        | 42     | 0.49%   |
| Patriot             | 29        | 35     | 0.44%   |
| Netac               | 29        | 36     | 0.44%   |
| Seagate             | 24        | 32     | 0.37%   |
| KingSpec            | 23        | 32     | 0.35%   |
| JMicron Technology  | 22        | 25     | 0.34%   |
| Plextor             | 19        | 26     | 0.29%   |
| Lexar               | 19        | 21     | 0.29%   |
| Unknown             | 19        | 24     | 0.29%   |
| BIWIN               | 17        | 19     | 0.26%   |
| Dell                | 16        | 18     | 0.25%   |
| Wibtek              | 15        | 20     | 0.23%   |
| OWC                 | 13        | 17     | 0.2%    |
| KingFast            | 13        | 16     | 0.2%    |
| FORESEE             | 13        | 19     | 0.2%    |
| Corsair             | 12        | 15     | 0.18%   |
| Zheino              | 11        | 11     | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 6421      | 8459   | 30.62%  |
| NVMe    | 6170      | 8876   | 29.42%  |
| SSD     | 6013      | 8412   | 28.67%  |
| MMC     | 2072      | 2675   | 9.88%   |
| Unknown | 296       | 361    | 1.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11257     | 15814  | 54.79%  |
| NVMe | 6158      | 8841   | 29.97%  |
| MMC  | 2072      | 2675   | 10.08%  |
| SAS  | 1059      | 1453   | 5.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8157      | 10758  | 64.67%  |
| 0.51-1.0   | 3683      | 4993   | 29.2%   |
| 1.01-2.0   | 616       | 891    | 4.88%   |
| 4.01-10.0  | 89        | 142    | 0.71%   |
| 3.01-4.0   | 60        | 78     | 0.48%   |
| 10.01-20.0 | 5         | 6      | 0.04%   |
| 2.01-3.0   | 3         | 3      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 4931      | 25.98%  |
| 251-500        | 4410      | 23.23%  |
| 501-1000       | 3139      | 16.54%  |
| 1-20           | 1447      | 7.62%   |
| 1001-2000      | 1219      | 6.42%   |
| 51-100         | 1083      | 5.71%   |
| Unknown        | 1074      | 5.66%   |
| 21-50          | 700       | 3.69%   |
| More than 3000 | 616       | 3.25%   |
| 2001-3000      | 360       | 1.9%    |
| 0              | 1         | 0.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 8045      | 40.72%  |
| 21-50          | 3632      | 18.39%  |
| 101-250        | 2242      | 11.35%  |
| 51-100         | 2220      | 11.24%  |
| 251-500        | 1249      | 6.32%   |
| Unknown        | 1074      | 5.44%   |
| 501-1000       | 725       | 3.67%   |
| 1001-2000      | 329       | 1.67%   |
| More than 3000 | 126       | 0.64%   |
| 2001-3000      | 102       | 0.52%   |
| 0              | 11        | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                | 25        | 29     | 2.54%   |
| Fujitsu MHZ2160BH FFS G1 160GB          | 25        | 25     | 2.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 20        | 20     | 2.03%   |
| Seagate ST500LT012-1DG142 500GB         | 18        | 20     | 1.83%   |
| Toshiba MQ01ABD100 1TB                  | 17        | 19     | 1.73%   |
| Seagate ST500LT012-9WS142 500GB         | 17        | 20     | 1.73%   |
| Seagate ST9500325AS 500GB               | 16        | 16     | 1.63%   |
| HGST HTS725050A7E630 500GB              | 15        | 15     | 1.53%   |
| HGST HTS541010A9E680 1TB                | 15        | 16     | 1.53%   |
| Seagate ST1000LM035-1RK172 1TB          | 14        | 14     | 1.42%   |
| HGST HTS545050A7E680 500GB              | 14        | 14     | 1.42%   |
| Seagate ST320LT007-9ZV142 320GB         | 11        | 13     | 1.12%   |
| Seagate ST1000LX015-1U7172 1TB          | 11        | 12     | 1.12%   |
| Hitachi HTS543216L9SA02 160GB           | 11        | 11     | 1.12%   |
| Toshiba MK1653GSX 160GB                 | 9         | 9      | 0.92%   |
| Seagate ST9750420AS 752GB               | 9         | 12     | 0.92%   |
| Seagate ST9500420AS 500GB               | 9         | 9      | 0.92%   |
| Hitachi HTS547575A9E384 752GB           | 9         | 10     | 0.92%   |
| Toshiba MK1655GSXF 160GB                | 8         | 8      | 0.81%   |
| Hitachi HTS542512K9SA00 120GB           | 8         | 10     | 0.81%   |
| HGST HTS545050A7E380 500GB              | 8         | 8      | 0.81%   |
| Toshiba MQ01ABF050 500GB                | 7         | 7      | 0.71%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB   | 7         | 9      | 0.71%   |
| Seagate ST9320423AS 320GB               | 7         | 7      | 0.71%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 7         | 7      | 0.71%   |
| Hitachi HTS547564A9E384 640GB           | 7         | 8      | 0.71%   |
| Hitachi HTS545050B9A300 500GB           | 7         | 7      | 0.71%   |
| Crucial CT525MX300SSD1 528GB            | 7         | 8      | 0.71%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 6         | 8      | 0.61%   |
| Hitachi HTS723232A7A364 320GB           | 6         | 7      | 0.61%   |
| HGST HTS725032A7E630 320GB              | 6         | 7      | 0.61%   |
| HGST HTS541075A9E680 752GB              | 6         | 6      | 0.61%   |
| Seagate ST9320325AS 320GB               | 5         | 5      | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB         | 5         | 5      | 0.51%   |
| Hitachi HTS543216L9A300 160GB           | 5         | 5      | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 4         | 4      | 0.41%   |
| WDC WD1600BUDT-63DPZY0 160GB            | 4         | 4      | 0.41%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 4      | 0.41%   |
| Toshiba MQ01ACF050 500GB                | 4         | 4      | 0.41%   |
| Toshiba MQ01ABD075 752GB                | 4         | 6      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 205       | 228    | 20.96%  |
| Toshiba               | 121       | 134    | 12.37%  |
| Hitachi               | 105       | 117    | 10.74%  |
| WDC                   | 104       | 113    | 10.63%  |
| HGST                  | 98        | 108    | 10.02%  |
| Samsung Electronics   | 49        | 62     | 5.01%   |
| Fujitsu               | 44        | 44     | 4.5%    |
| SK hynix              | 37        | 42     | 3.78%   |
| Intel                 | 35        | 41     | 3.58%   |
| Crucial               | 35        | 55     | 3.58%   |
| Kingston              | 27        | 30     | 2.76%   |
| SanDisk               | 21        | 24     | 2.15%   |
| Micron Technology     | 12        | 15     | 1.23%   |
| LITEON                | 9         | 10     | 0.92%   |
| Apple                 | 9         | 10     | 0.92%   |
| A-DATA Technology     | 8         | 9      | 0.82%   |
| LITEONIT              | 7         | 8      | 0.72%   |
| SSSTC                 | 4         | 4      | 0.41%   |
| SPCC                  | 4         | 4      | 0.41%   |
| IBM/Hitachi           | 4         | 4      | 0.41%   |
| Unknown               | 4         | 4      | 0.41%   |
| Mushkin               | 3         | 3      | 0.31%   |
| KingSpec              | 3         | 3      | 0.31%   |
| ASMT                  | 3         | 4      | 0.31%   |
| OCZ                   | 2         | 3      | 0.2%    |
| Netac                 | 2         | 3      | 0.2%    |
| HGST HTS              | 2         | 4      | 0.2%    |
| Hewlett-Packard       | 2         | 2      | 0.2%    |
| Wibtek                | 1         | 1      | 0.1%    |
| Union Memory          | 1         | 1      | 0.1%    |
| Transcend             | 1         | 1      | 0.1%    |
| tecmiyo               | 1         | 1      | 0.1%    |
| Team                  | 1         | 1      | 0.1%    |
| SSD                   | 1         | 1      | 0.1%    |
| SABRENT               | 1         | 1      | 0.1%    |
| Realtek Semiconductor | 1         | 2      | 0.1%    |
| OWC                   | 1         | 1      | 0.1%    |
| Neo Forza             | 1         | 1      | 0.1%    |
| Lexar                 | 1         | 1      | 0.1%    |
| KingDian              | 1         | 2      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 205       | 228    | 30.19%  |
| Toshiba             | 109       | 118    | 16.05%  |
| Hitachi             | 105       | 117    | 15.46%  |
| HGST                | 98        | 108    | 14.43%  |
| WDC                 | 96        | 104    | 14.14%  |
| Fujitsu             | 44        | 44     | 6.48%   |
| Samsung Electronics | 9         | 9      | 1.33%   |
| IBM/Hitachi         | 4         | 4      | 0.59%   |
| Apple               | 3         | 4      | 0.44%   |
| HGST HTS            | 2         | 4      | 0.29%   |
| SABRENT             | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |
| Apricorn            | 1         | 1      | 0.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 668       | 744    | 69.22%  |
| SSD  | 239       | 300    | 24.77%  |
| NVMe | 58        | 66     | 6.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-80V0TT0 500GB                | 2         | 2      | 7.69%   |
| HGST HTS541010A9E680 1TB                    | 2         | 2      | 7.69%   |
| Crucial CT500P2SSD8 500GB                   | 2         | 2      | 7.69%   |
| WDC WD5000LPLX-75ZNTT0 500GB                | 1         | 1      | 3.85%   |
| WDC WD2500BEVT-75A23T0 250GB                | 1         | 2      | 3.85%   |
| WDC WD2500BEVT-60ZCT1 250GB                 | 1         | 1      | 3.85%   |
| WDC WD2500BEVT-22A23T0 250GB                | 1         | 1      | 3.85%   |
| Toshiba THNSN5512GPU7 512GB                 | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF032 320GB                    | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 3.85%   |
| Toshiba MK6465GSX 640GB                     | 1         | 1      | 3.85%   |
| Toshiba MK3261GSYN 320GB                    | 1         | 1      | 3.85%   |
| SK hynix PC401 NVMe Solid State Drive 256GB | 1         | 1      | 3.85%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB     | 1         | 1      | 3.85%   |
| Seagate ST9500420AS 500GB                   | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB             | 1         | 1      | 3.85%   |
| SanDisk SSD i100 24GB                       | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD            | 1         | 1      | 3.85%   |
| Intenso JAJP600M1TB                         | 1         | 1      | 3.85%   |
| Intel SSDSCKKF256H6 SATA 256GB              | 1         | 1      | 3.85%   |
| Hitachi HTS721010G9SA00 100GB               | 1         | 1      | 3.85%   |
| Hitachi HTS547575A9E384 752GB               | 1         | 2      | 3.85%   |
| Hitachi HTS547550A9E384 500GB               | 1         | 1      | 3.85%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 6         | 7      | 23.08%  |
| Toshiba  | 5         | 5      | 19.23%  |
| Hitachi  | 3         | 4      | 11.54%  |
| SK hynix | 2         | 2      | 7.69%   |
| Seagate  | 2         | 2      | 7.69%   |
| HGST     | 2         | 2      | 7.69%   |
| Crucial  | 2         | 2      | 7.69%   |
| SanDisk  | 1         | 1      | 3.85%   |
| Kingston | 1         | 1      | 3.85%   |
| Intenso  | 1         | 1      | 3.85%   |
| Intel    | 1         | 1      | 3.85%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 11628     | 18903  | 61.65%  |
| Works    | 6248      | 8740   | 33.13%  |
| Malfunc  | 957       | 1110   | 5.07%   |
| Failed   | 26        | 28     | 0.14%   |
| Fixed    | 1         | 1      | 0.01%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 10805     | 53.56%  |
| Samsung Electronics                     | 2222      | 11.01%  |
| AMD                                     | 2157      | 10.69%  |
| SanDisk                                 | 1092      | 5.41%   |
| SK hynix                                | 738       | 3.66%   |
| Nvidia                                  | 546       | 2.71%   |
| Phison Electronics                      | 424       | 2.1%    |
| Toshiba America Info Systems            | 393       | 1.95%   |
| Kingston Technology Company             | 322       | 1.6%    |
| Micron Technology                       | 296       | 1.47%   |
| Apple                                   | 191       | 0.95%   |
| Micron/Crucial Technology               | 187       | 0.93%   |
| KIOXIA                                  | 187       | 0.93%   |
| Silicon Motion                          | 135       | 0.67%   |
| O2 Micro                                | 63        | 0.31%   |
| Realtek Semiconductor                   | 53        | 0.26%   |
| Marvell Technology Group                | 52        | 0.26%   |
| Solid State Storage Technology          | 50        | 0.25%   |
| Union Memory (Shenzhen)                 | 40        | 0.2%    |
| ADATA Technology                        | 37        | 0.18%   |
| Lite-On Technology                      | 34        | 0.17%   |
| Lenovo                                  | 27        | 0.13%   |
| Seagate Technology                      | 22        | 0.11%   |
| MAXIO Technology (Hangzhou)             | 19        | 0.09%   |
| Biwin Storage Technology                | 14        | 0.07%   |
| Shenzhen Longsys Electronics            | 11        | 0.05%   |
| JMicron Technology                      | 11        | 0.05%   |
| INNOGRIT                                | 10        | 0.05%   |
| ASMedia Technology                      | 9         | 0.04%   |
| Yangtze Memory Technologies             | 7         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 5         | 0.02%   |
| ULi Electronics                         | 3         | 0.01%   |
| VIA Technologies                        | 2         | 0.01%   |
| Solidigm                                | 2         | 0.01%   |
| Shenzhen Unionmemory Information System | 2         | 0.01%   |
| OCZ Technology Group                    | 2         | 0.01%   |
| Transcend                               | 1         | 0.005%  |
| Silicon Image                           | 1         | 0.005%  |
| Broadcom / LSI                          | 1         | 0.005%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1823      | 8.44%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 1322      | 6.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 1101      | 5.1%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 1041      | 4.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 976       | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 933       | 4.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 521       | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 501       | 2.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 478       | 2.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 470       | 2.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 463       | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 456       | 2.11%   |
| Nvidia MCP79 AHCI Controller                                                   | 444       | 2.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 418       | 1.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 343       | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 326       | 1.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 302       | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 298       | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 282       | 1.31%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 275       | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 270       | 1.25%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 259       | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 252       | 1.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 222       | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 212       | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 196       | 0.91%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 187       | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 183       | 0.85%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 177       | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 169       | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 167       | 0.77%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 159       | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 152       | 0.7%    |
| Intel SSD 660P Series                                                          | 151       | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 147       | 0.68%   |
| Phison E12 NVMe Controller                                                     | 142       | 0.66%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 133       | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 129       | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 125       | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 120       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 11346     | 55.16%  |
| NVMe | 6197      | 30.12%  |
| RAID | 1911      | 9.29%   |
| IDE  | 1116      | 5.43%   |
| SAS  | 1         | 0.005%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 14377     | 80.49%  |
| AMD          | 3453      | 19.33%  |
| ARM          | 20        | 0.11%   |
| Unknown      | 8         | 0.04%   |
| Qualcomm     | 2         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 452       | 2.53%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 366       | 2.05%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 257       | 1.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 225       | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 217       | 1.21%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 205       | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 201       | 1.12%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 195       | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 188       | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 185       | 1.03%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 183       | 1.02%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 181       | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 175       | 0.98%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 172       | 0.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 171       | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 168       | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 166       | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 161       | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 158       | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 152       | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 142       | 0.79%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 132       | 0.74%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 130       | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 130       | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 126       | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 119       | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 109       | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 108       | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 100       | 0.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 99        | 0.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 98        | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 98        | 0.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 98        | 0.55%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 96        | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 92        | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 92        | 0.51%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 90        | 0.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 90        | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 89        | 0.5%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 88        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 4292      | 24.02%  |
| Intel Core i5                  | 3865      | 21.63%  |
| Other                          | 1962      | 10.98%  |
| Intel Celeron                  | 1231      | 6.89%   |
| Intel Core 2 Duo               | 1179      | 6.6%    |
| Intel Core i3                  | 1009      | 5.65%   |
| AMD Ryzen 7                    | 517       | 2.89%   |
| AMD Ryzen 5                    | 474       | 2.65%   |
| Intel Pentium                  | 385       | 2.15%   |
| AMD A6                         | 300       | 1.68%   |
| Intel Atom                     | 209       | 1.17%   |
| AMD Ryzen 9                    | 193       | 1.08%   |
| AMD Ryzen 3                    | 188       | 1.05%   |
| AMD A8                         | 175       | 0.98%   |
| Intel Core i9                  | 155       | 0.87%   |
| AMD A10                        | 139       | 0.78%   |
| AMD Ryzen 7 PRO                | 136       | 0.76%   |
| Intel Core 2                   | 114       | 0.64%   |
| Intel Pentium Dual-Core        | 100       | 0.56%   |
| AMD A4                         | 100       | 0.56%   |
| AMD E                          | 95        | 0.53%   |
| Intel Pentium Silver           | 83        | 0.46%   |
| AMD E2                         | 82        | 0.46%   |
| Intel Xeon                     | 79        | 0.44%   |
| Intel Genuine                  | 64        | 0.36%   |
| AMD Turion 64 X2 Mobile        | 55        | 0.31%   |
| AMD Athlon                     | 55        | 0.31%   |
| Intel Pentium Dual             | 51        | 0.29%   |
| Intel Core m3                  | 43        | 0.24%   |
| AMD E1                         | 43        | 0.24%   |
| Intel Pentium M                | 38        | 0.21%   |
| AMD A12                        | 38        | 0.21%   |
| AMD Ryzen 5 PRO                | 35        | 0.2%    |
| AMD Athlon II                  | 28        | 0.16%   |
| AMD Phenom II                  | 25        | 0.14%   |
| AMD FX                         | 21        | 0.12%   |
| Intel Core M                   | 20        | 0.11%   |
| Intel Celeron M                | 20        | 0.11%   |
| AMD Turion X2 Dual-Core Mobile | 18        | 0.1%    |
| Intel Pentium 4                | 17        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 9094      | 50.88%  |
| 4      | 5493      | 30.73%  |
| 6      | 1252      | 7%      |
| 8      | 1144      | 6.4%    |
| 1      | 385       | 2.15%   |
| 14     | 202       | 1.13%   |
| 10     | 127       | 0.71%   |
| 12     | 121       | 0.68%   |
| 24     | 20        | 0.11%   |
| 16     | 19        | 0.11%   |
| 3      | 14        | 0.08%   |
| 5      | 2         | 0.01%   |
| 128    | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 17847     | 99.93%  |
| 2      | 12        | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 13032     | 72.87%  |
| 1      | 4845      | 27.09%  |
| 8      | 4         | 0.02%   |
| 4      | 3         | 0.02%   |
| 16     | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 17461     | 97.53%  |
| Unknown        | 261       | 1.46%   |
| 32-bit         | 169       | 0.94%   |
| 64-bit         | 12        | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 6217      | 33.38%  |
| 0x206a7    | 915       | 4.91%   |
| 0x306a9    | 862       | 4.63%   |
| 0x1067a    | 808       | 4.34%   |
| 0x306d4    | 567       | 3.04%   |
| 0x906ea    | 466       | 2.5%    |
| 0x806ea    | 457       | 2.45%   |
| 0x40651    | 453       | 2.43%   |
| 0x406e3    | 452       | 2.43%   |
| 0x806ec    | 378       | 2.03%   |
| 0x306c3    | 372       | 2%      |
| 0x806c1    | 363       | 1.95%   |
| 0x806e9    | 355       | 1.91%   |
| 0x20655    | 305       | 1.64%   |
| 0x30678    | 303       | 1.63%   |
| 0xa0652    | 268       | 1.44%   |
| 0x406c4    | 255       | 1.37%   |
| 0x906e9    | 198       | 1.06%   |
| 0x506e3    | 187       | 1%      |
| 0x0a50000c | 186       | 1%      |
| 0x706e5    | 177       | 0.95%   |
| 0x08108109 | 173       | 0.93%   |
| 0x706a8    | 161       | 0.86%   |
| 0x6fd      | 154       | 0.83%   |
| 0x806d1    | 150       | 0.81%   |
| 0x08108102 | 149       | 0.8%    |
| 0x10676    | 143       | 0.77%   |
| 0x20652    | 135       | 0.72%   |
| 0x906a3    | 131       | 0.7%    |
| 0x06006705 | 128       | 0.69%   |
| 0x07030105 | 121       | 0.65%   |
| 0x06001119 | 116       | 0.62%   |
| 0x506c9    | 104       | 0.56%   |
| 0x08600106 | 102       | 0.55%   |
| 0x706a1    | 100       | 0.54%   |
| 0x05000119 | 97        | 0.52%   |
| 0x806eb    | 94        | 0.5%    |
| 0x6f6      | 94        | 0.5%    |
| 0x906ed    | 86        | 0.46%   |
| 0x0a404102 | 83        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 3000      | 16.77%  |
| Haswell          | 1277      | 7.14%   |
| SandyBridge      | 1227      | 6.86%   |
| IvyBridge        | 1188      | 6.64%   |
| Penryn           | 1134      | 6.34%   |
| Unknown          | 1061      | 5.93%   |
| Skylake          | 947       | 5.29%   |
| Silvermont       | 817       | 4.57%   |
| Broadwell        | 793       | 4.43%   |
| TigerLake        | 650       | 3.63%   |
| Westmere         | 575       | 3.21%   |
| CometLake        | 496       | 2.77%   |
| Zen+             | 449       | 2.51%   |
| Icelake          | 438       | 2.45%   |
| Core             | 404       | 2.26%   |
| Goldmont plus    | 389       | 2.17%   |
| Excavator        | 371       | 2.07%   |
| Zen 3            | 361       | 2.02%   |
| Alderlake Hybrid | 335       | 1.87%   |
| Zen 2            | 331       | 1.85%   |
| Puma             | 201       | 1.12%   |
| Piledriver       | 174       | 0.97%   |
| Bobcat           | 164       | 0.92%   |
| Goldmont         | 150       | 0.84%   |
| Zen              | 144       | 0.81%   |
| K8 Hammer        | 105       | 0.59%   |
| Jaguar           | 105       | 0.59%   |
| P6               | 104       | 0.58%   |
| K10              | 96        | 0.54%   |
| K10 Llano        | 94        | 0.53%   |
| Bonnell          | 89        | 0.5%    |
| Nehalem          | 86        | 0.48%   |
| K8 & K10 hybrid  | 62        | 0.35%   |
| Tremont          | 25        | 0.14%   |
| Steamroller      | 25        | 0.14%   |
| NetBurst         | 20        | 0.11%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 12777     | 59.25%  |
| Nvidia                           | 4709      | 21.84%  |
| AMD                              | 4071      | 18.88%  |
| ASPEED Technology                | 3         | 0.01%   |
| Silicon Integrated Systems [SiS] | 2         | 0.01%   |
| VIA Technologies                 | 1         | 0.005%  |
| S3 Graphics                      | 1         | 0.005%  |
| ATI Technologies                 | 1         | 0.005%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 1104      | 4.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1104      | 4.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 683       | 3.08%   |
| Intel UHD Graphics 620                                                                   | 647       | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 636       | 2.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 582       | 2.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 552       | 2.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 502       | 2.26%   |
| Intel HD Graphics 5500                                                                   | 493       | 2.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 461       | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 461       | 2.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 460       | 2.07%   |
| Intel HD Graphics 620                                                                    | 452       | 2.04%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 435       | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 423       | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 395       | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 394       | 1.78%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 369       | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 355       | 1.6%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 309       | 1.39%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 306       | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 275       | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 255       | 1.15%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 243       | 1.1%    |
| Intel HD Graphics 630                                                                    | 242       | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 238       | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 236       | 1.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 236       | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 222       | 1%      |
| Intel HD Graphics 6000                                                                   | 219       | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 216       | 0.97%   |
| Intel HD Graphics 530                                                                    | 215       | 0.97%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 178       | 0.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 174       | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 159       | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 155       | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 155       | 0.7%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 155       | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 153       | 0.69%   |
| AMD Rembrandt [Radeon 680M]                                                              | 150       | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 9387      | 52.37%  |
| 1 x AMD                  | 3114      | 17.37%  |
| Intel + Nvidia           | 2854      | 15.92%  |
| 1 x Nvidia               | 1445      | 8.06%   |
| Intel + AMD              | 414       | 2.31%   |
| AMD + Nvidia             | 395       | 2.2%    |
| 2 x AMD                  | 149       | 0.83%   |
| Other                    | 77        | 0.43%   |
| 2 x Intel                | 50        | 0.28%   |
| 2 x Nvidia               | 24        | 0.13%   |
| Intel + 2 x Nvidia       | 8         | 0.04%   |
| 1 x SiS                  | 2         | 0.01%   |
| Nvidia + ASPEED          | 2         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| 1 x S3 Graphics          | 1         | 0.01%   |
| Intel + ASPEED           | 1         | 0.01%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 15400     | 85.04%  |
| Proprietary | 2311      | 12.76%  |
| Unknown     | 398       | 2.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 12481     | 68.19%  |
| 0.01-0.5   | 2318      | 12.67%  |
| 1.01-2.0   | 1258      | 6.87%   |
| 3.01-4.0   | 855       | 4.67%   |
| 0.51-1.0   | 674       | 3.68%   |
| 5.01-6.0   | 312       | 1.7%    |
| 7.01-8.0   | 281       | 1.54%   |
| 2.01-3.0   | 71        | 0.39%   |
| 8.01-16.0  | 52        | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 3616      | 18.05%  |
| LG Display              | 2750      | 13.73%  |
| BOE                     | 2334      | 11.65%  |
| Chimei Innolux          | 2217      | 11.07%  |
| Samsung Electronics     | 1950      | 9.74%   |
| Apple                   | 1373      | 6.86%   |
| Sharp                   | 825       | 4.12%   |
| Dell                    | 571       | 2.85%   |
| Chi Mei Optoelectronics | 419       | 2.09%   |
| Lenovo                  | 334       | 1.67%   |
| Goldstar                | 311       | 1.55%   |
| Valve                   | 302       | 1.51%   |
| Hewlett-Packard         | 294       | 1.47%   |
| PANDA                   | 279       | 1.39%   |
| Acer                    | 229       | 1.14%   |
| InfoVision              | 211       | 1.05%   |
| LG Philips              | 149       | 0.74%   |
| Ancor Communications    | 143       | 0.71%   |
| Vizio                   | 131       | 0.65%   |
| ViewSonic               | 98        | 0.49%   |
| CSO                     | 90        | 0.45%   |
| Sceptre Tech            | 87        | 0.43%   |
| AOC                     | 79        | 0.39%   |
| Sony                    | 78        | 0.39%   |
| ASUSTek Computer        | 70        | 0.35%   |
| Analogix                | 69        | 0.34%   |
| Toshiba                 | 55        | 0.27%   |
| Insignia                | 48        | 0.24%   |
| HannStar                | 47        | 0.23%   |
| BenQ                    | 46        | 0.23%   |
| Panasonic               | 44        | 0.22%   |
| CPT                     | 43        | 0.21%   |
| LGD                     | 34        | 0.17%   |
| TMX                     | 33        | 0.16%   |
| InnoLux Display         | 28        | 0.14%   |
| Philips                 | 25        | 0.12%   |
| Seiko/Epson             | 22        | 0.11%   |
| MSI                     | 20        | 0.1%    |
| JDI                     | 19        | 0.09%   |
| Quanta Display          | 18        | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 284       | 1.4%    |
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                     | 217       | 1.07%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 215       | 1.06%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 171       | 0.84%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 159       | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 100       | 0.49%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 98        | 0.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 95        | 0.47%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 93        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 92        | 0.45%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 80        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 79        | 0.39%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 77        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 74        | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 72        | 0.36%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                     | 71        | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 70        | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 69        | 0.34%   |
| Analogix ANX7530 U ANX7539 800x1280                                      | 69        | 0.34%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 66        | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 62        | 0.31%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 62        | 0.31%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 62        | 0.31%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 58        | 0.29%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 57        | 0.28%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                     | 57        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 54        | 0.27%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 54        | 0.27%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 52        | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 51        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 50        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 50        | 0.25%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 50        | 0.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 49        | 0.24%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 49        | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 48        | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 47        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 46        | 0.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 46        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 45        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6842      | 35.74%  |
| 1366x768 (WXGA)    | 5422      | 28.33%  |
| 1600x900 (HD+)     | 1179      | 6.16%   |
| 1280x800 (WXGA)    | 1152      | 6.02%   |
| 3840x2160 (4K)     | 913       | 4.77%   |
| 1440x900 (WXGA+)   | 524       | 2.74%   |
| 2560x1440 (QHD)    | 441       | 2.3%    |
| 1920x1200 (WUXGA)  | 441       | 2.3%    |
| 800x1280           | 363       | 1.9%    |
| 2560x1600          | 295       | 1.54%   |
| 2880x1800          | 183       | 0.96%   |
| 3840x2400          | 144       | 0.75%   |
| 1680x1050 (WSXGA+) | 128       | 0.67%   |
| 2256x1504          | 112       | 0.59%   |
| 2560x1080          | 98        | 0.51%   |
| 3440x1440          | 97        | 0.51%   |
| 3200x1800 (QHD+)   | 95        | 0.5%    |
| 1024x600           | 80        | 0.42%   |
| 1280x1024 (SXGA)   | 77        | 0.4%    |
| 1360x768           | 57        | 0.3%    |
| 1920x540           | 55        | 0.29%   |
| Unknown            | 52        | 0.27%   |
| 1024x768 (XGA)     | 45        | 0.24%   |
| 3072x1920          | 41        | 0.21%   |
| 3840x1080          | 32        | 0.17%   |
| 1920x1280          | 22        | 0.11%   |
| 3456x2160          | 21        | 0.11%   |
| 2240x1400          | 20        | 0.1%    |
| 3000x2000          | 17        | 0.09%   |
| 3200x2000          | 13        | 0.07%   |
| 2304x1440          | 12        | 0.06%   |
| 2160x1440          | 12        | 0.06%   |
| 3840x1600          | 10        | 0.05%   |
| 1400x1050          | 10        | 0.05%   |
| 3840x1100          | 9         | 0.05%   |
| 1680x945           | 9         | 0.05%   |
| 1600x1200          | 8         | 0.04%   |
| 2560x1700          | 6         | 0.03%   |
| 2400x1600          | 6         | 0.03%   |
| 2288x1287          | 6         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 7300      | 36.51%  |
| 13      | 3241      | 16.21%  |
| 14      | 2229      | 11.15%  |
| 17      | 1829      | 9.15%   |
| 11      | 795       | 3.98%   |
| 27      | 583       | 2.92%   |
| 24      | 445       | 2.23%   |
| 12      | 445       | 2.23%   |
| 23      | 349       | 1.75%   |
| 7       | 302       | 1.51%   |
| Unknown | 293       | 1.47%   |
| 31      | 276       | 1.38%   |
| 21      | 268       | 1.34%   |
| 16      | 264       | 1.32%   |
| 34      | 159       | 0.8%    |
| 18      | 131       | 0.66%   |
| 19      | 103       | 0.52%   |
| 10      | 87        | 0.44%   |
| 32      | 79        | 0.4%    |
| 20      | 73        | 0.37%   |
| 3       | 69        | 0.35%   |
| 84      | 61        | 0.31%   |
| 22      | 60        | 0.3%    |
| 54      | 52        | 0.26%   |
| 40      | 51        | 0.26%   |
| 72      | 49        | 0.25%   |
| 29      | 43        | 0.22%   |
| 26      | 36        | 0.18%   |
| 8       | 29        | 0.15%   |
| 49      | 28        | 0.14%   |
| 74      | 23        | 0.12%   |
| 48      | 20        | 0.1%    |
| 37      | 20        | 0.1%    |
| 25      | 20        | 0.1%    |
| 28      | 19        | 0.1%    |
| 36      | 16        | 0.08%   |
| 42      | 15        | 0.08%   |
| 86      | 12        | 0.06%   |
| 35      | 12        | 0.06%   |
| 39      | 11        | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 10719     | 54.01%  |
| 201-300        | 3313      | 16.69%  |
| 351-400        | 2159      | 10.88%  |
| 501-600        | 1279      | 6.44%   |
| 401-500        | 582       | 2.93%   |
| 601-700        | 406       | 2.05%   |
| 1-100          | 364       | 1.83%   |
| Unknown        | 293       | 1.48%   |
| 701-800        | 255       | 1.28%   |
| 1001-1500      | 161       | 0.81%   |
| 1501-2000      | 147       | 0.74%   |
| 801-900        | 103       | 0.52%   |
| 901-1000       | 33        | 0.17%   |
| 101-200        | 30        | 0.15%   |
| More than 2000 | 3         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 13835     | 76.75%  |
| 16/10   | 2910      | 16.14%  |
| 0.67    | 285       | 1.58%   |
| Unknown | 227       | 1.26%   |
| 3/2     | 222       | 1.23%   |
| 21/9    | 193       | 1.07%   |
| 6/5     | 82        | 0.45%   |
| 4/3     | 74        | 0.41%   |
| 5/4     | 73        | 0.4%    |
| 32/9    | 43        | 0.24%   |
| 0.62    | 30        | 0.17%   |
| 2.65    | 13        | 0.07%   |
| 0.56    | 10        | 0.06%   |
| 3.40    | 9         | 0.05%   |
| 1.96    | 7         | 0.04%   |
| 1.00    | 4         | 0.02%   |
| 2.12    | 2         | 0.01%   |
| 0.63    | 2         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.01    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7240      | 36.29%  |
| 81-90          | 4367      | 21.89%  |
| 121-130        | 1580      | 7.92%   |
| 71-80          | 1053      | 5.28%   |
| 201-250        | 895       | 4.49%   |
| 51-60          | 808       | 4.05%   |
| 301-350        | 614       | 3.08%   |
| 351-500        | 540       | 2.71%   |
| 61-70          | 433       | 2.17%   |
| 1-40           | 394       | 1.98%   |
| 111-120        | 297       | 1.49%   |
| Unknown        | 293       | 1.47%   |
| More than 1000 | 270       | 1.35%   |
| 151-200        | 263       | 1.32%   |
| 131-140        | 234       | 1.17%   |
| 501-1000       | 187       | 0.94%   |
| 251-300        | 176       | 0.88%   |
| 141-150        | 153       | 0.77%   |
| 41-50          | 83        | 0.42%   |
| 91-100         | 69        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 7301      | 37.28%  |
| 101-120       | 6240      | 31.86%  |
| 51-100        | 2689      | 13.73%  |
| 161-240       | 1846      | 9.43%   |
| More than 240 | 933       | 4.76%   |
| Unknown       | 293       | 1.5%    |
| 1-50          | 284       | 1.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 14993     | 81.88%  |
| 2     | 2521      | 13.77%  |
| 0     | 429       | 2.34%   |
| 3     | 338       | 1.85%   |
| 4     | 26        | 0.14%   |
| 5     | 3         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 9728      | 35.23%  |
| Realtek Semiconductor                 | 8340      | 30.21%  |
| Qualcomm Atheros                      | 3135      | 11.35%  |
| Broadcom                              | 2228      | 8.07%   |
| Broadcom Limited                      | 761       | 2.76%   |
| Nvidia                                | 516       | 1.87%   |
| MediaTek                              | 370       | 1.34%   |
| ASIX Electronics                      | 336       | 1.22%   |
| Marvell Technology Group              | 333       | 1.21%   |
| Ralink Technology                     | 176       | 0.64%   |
| Ralink                                | 157       | 0.57%   |
| TP-Link                               | 138       | 0.5%    |
| Samsung Electronics                   | 131       | 0.47%   |
| DisplayLink                           | 130       | 0.47%   |
| Qualcomm                              | 116       | 0.42%   |
| NetGear                               | 102       | 0.37%   |
| Lenovo                                | 87        | 0.32%   |
| Motorola PCS                          | 57        | 0.21%   |
| Dell                                  | 55        | 0.2%    |
| Google                                | 53        | 0.19%   |
| ASUSTek Computer                      | 47        | 0.17%   |
| Edimax Technology                     | 43        | 0.16%   |
| Apple                                 | 43        | 0.16%   |
| Linksys                               | 42        | 0.15%   |
| Sierra Wireless                       | 39        | 0.14%   |
| Qualcomm Atheros Communications       | 38        | 0.14%   |
| Belkin Components                     | 34        | 0.12%   |
| Hewlett-Packard                       | 29        | 0.11%   |
| Cypress Semiconductor                 | 23        | 0.08%   |
| D-Link                                | 19        | 0.07%   |
| T & A Mobile Phones                   | 17        | 0.06%   |
| JMicron Technology                    | 16        | 0.06%   |
| U-Blox                                | 15        | 0.05%   |
| LG Electronics                        | 15        | 0.05%   |
| Microsoft                             | 14        | 0.05%   |
| AMD                                   | 14        | 0.05%   |
| OnePlus Technology (Shenzhen)         | 13        | 0.05%   |
| Arduino SA                            | 13        | 0.05%   |
| Xiaomi                                | 11        | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 10        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 3967      | 11.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 1819      | 5.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 898       | 2.67%   |
| Intel Wireless 7260                                                  | 826       | 2.46%   |
| Intel Wi-Fi 6 AX200                                                  | 776       | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 775       | 2.31%   |
| Intel Wireless 7265                                                  | 747       | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 723       | 2.15%   |
| Intel Wireless 8265 / 8275                                           | 679       | 2.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 509       | 1.52%   |
| Intel Wireless 8260                                                  | 501       | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 498       | 1.48%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 497       | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 495       | 1.47%   |
| Nvidia MCP79 Ethernet                                                | 448       | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 438       | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 426       | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 406       | 1.21%   |
| Intel Wi-Fi 6 AX201                                                  | 400       | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 380       | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 370       | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                | 322       | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 310       | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                        | 295       | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 294       | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 293       | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 293       | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 289       | 0.86%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 278       | 0.83%   |
| Intel Ethernet Connection I217-LM                                    | 259       | 0.77%   |
| Intel Wireless 3165                                                  | 256       | 0.76%   |
| Intel Centrino Ultimate-N 6300                                       | 251       | 0.75%   |
| Intel 82577LM Gigabit Network Connection                             | 250       | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 243       | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 239       | 0.71%   |
| Intel Ethernet Connection I219-LM                                    | 234       | 0.7%    |
| Intel Wireless 3160                                                  | 218       | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 209       | 0.62%   |
| Intel Ethernet Connection I218-LM                                    | 205       | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                | 197       | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 9183      | 49.24%  |
| Realtek Semiconductor                 | 3052      | 16.36%  |
| Qualcomm Atheros                      | 2500      | 13.4%   |
| Broadcom                              | 1950      | 10.46%  |
| Broadcom Limited                      | 617       | 3.31%   |
| MediaTek                              | 348       | 1.87%   |
| Ralink Technology                     | 176       | 0.94%   |
| Ralink                                | 157       | 0.84%   |
| TP-Link                               | 110       | 0.59%   |
| Qualcomm                              | 97        | 0.52%   |
| NetGear                               | 97        | 0.52%   |
| Dell                                  | 53        | 0.28%   |
| Sierra Wireless                       | 39        | 0.21%   |
| ASUSTek Computer                      | 39        | 0.21%   |
| Qualcomm Atheros Communications       | 38        | 0.2%    |
| Linksys                               | 37        | 0.2%    |
| Edimax Technology                     | 36        | 0.19%   |
| Belkin Components                     | 31        | 0.17%   |
| D-Link                                | 16        | 0.09%   |
| Microsoft                             | 13        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 10        | 0.05%   |
| D-Link System                         | 9         | 0.05%   |
| ZyDAS                                 | 4         | 0.02%   |
| TRENDnet                              | 4         | 0.02%   |
| Qualcomm Technologies                 | 4         | 0.02%   |
| Marvell Technology Group              | 4         | 0.02%   |
| Samsung Electronics                   | 3         | 0.02%   |
| Hewlett-Packard                       | 3         | 0.02%   |
| BUFFALO                               | 3         | 0.02%   |
| Tenda                                 | 2         | 0.01%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| U.S. Robotics                         | 1         | 0.01%   |
| Toshiba                               | 1         | 0.01%   |
| Realtek                               | 1         | 0.01%   |
| Quectel Wireless Solutions            | 1         | 0.01%   |
| Panasonic (Matsushita)                | 1         | 0.01%   |
| Micro Star International              | 1         | 0.01%   |
| Hawking Technologies                  | 1         | 0.01%   |
| Fibocom                               | 1         | 0.01%   |
| Elecom                                | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                  | 826       | 4.37%   |
| Intel Wi-Fi 6 AX200                                                  | 776       | 4.11%   |
| Intel Wireless 7265                                                  | 747       | 3.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 723       | 3.83%   |
| Intel Wireless 8265 / 8275                                           | 679       | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 509       | 2.7%    |
| Intel Wireless 8260                                                  | 501       | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 498       | 2.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 497       | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 495       | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 438       | 2.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 426       | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 406       | 2.15%   |
| Intel Wi-Fi 6 AX201                                                  | 400       | 2.12%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 380       | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 370       | 1.96%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 310       | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 294       | 1.56%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 293       | 1.55%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 293       | 1.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 289       | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 278       | 1.47%   |
| Intel Wireless 3165                                                  | 256       | 1.36%   |
| Intel Centrino Ultimate-N 6300                                       | 251       | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 243       | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 239       | 1.27%   |
| Intel Wireless 3160                                                  | 218       | 1.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 209       | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 196       | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 185       | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 185       | 0.98%   |
| Intel Centrino Advanced-N 6200                                       | 170       | 0.9%    |
| Intel Centrino Advanced-N 6235                                       | 168       | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                        | 163       | 0.86%   |
| Intel Wireless-AC 9260                                               | 161       | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 161       | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 155       | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 155       | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 140       | 0.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 131       | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 6815      | 47.92%  |
| Intel                            | 3805      | 26.75%  |
| Qualcomm Atheros                 | 910       | 6.4%    |
| Broadcom                         | 665       | 4.68%   |
| Nvidia                           | 515       | 3.62%   |
| ASIX Electronics                 | 336       | 2.36%   |
| Marvell Technology Group         | 329       | 2.31%   |
| Broadcom Limited                 | 166       | 1.17%   |
| DisplayLink                      | 130       | 0.91%   |
| Lenovo                           | 84        | 0.59%   |
| Samsung Electronics              | 76        | 0.53%   |
| Google                           | 51        | 0.36%   |
| Apple                            | 43        | 0.3%    |
| Motorola PCS                     | 33        | 0.23%   |
| TP-Link                          | 28        | 0.2%    |
| Cypress Semiconductor            | 23        | 0.16%   |
| MediaTek                         | 19        | 0.13%   |
| Qualcomm                         | 18        | 0.13%   |
| Hewlett-Packard                  | 17        | 0.12%   |
| JMicron Technology               | 16        | 0.11%   |
| LG Electronics                   | 14        | 0.1%    |
| Xiaomi                           | 11        | 0.08%   |
| T & A Mobile Phones              | 10        | 0.07%   |
| OnePlus Technology (Shenzhen)    | 10        | 0.07%   |
| ICS Advent                       | 8         | 0.06%   |
| ASUSTek Computer                 | 8         | 0.06%   |
| OPPO Electronics                 | 7         | 0.05%   |
| Edimax Technology                | 7         | 0.05%   |
| Aquantia                         | 7         | 0.05%   |
| Silicon Integrated Systems [SiS] | 5         | 0.04%   |
| Novatel Wireless                 | 5         | 0.04%   |
| NetGear                          | 5         | 0.04%   |
| Linksys                          | 5         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 4         | 0.03%   |
| Attansic Technology              | 4         | 0.03%   |
| Microchip Technology             | 3         | 0.02%   |
| D-Link                           | 3         | 0.02%   |
| Belkin Components                | 3         | 0.02%   |
| ZyXEL Communications             | 2         | 0.01%   |
| National Semiconductor           | 2         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3967      | 27.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1819      | 12.62%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 898       | 6.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 775       | 5.38%   |
| Nvidia MCP79 Ethernet                                             | 448       | 3.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 322       | 2.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 295       | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 259       | 1.8%    |
| Intel 82577LM Gigabit Network Connection                          | 250       | 1.73%   |
| Intel Ethernet Connection I219-LM                                 | 234       | 1.62%   |
| Intel Ethernet Connection I218-LM                                 | 205       | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 197       | 1.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 196       | 1.36%   |
| Intel 82567LM Gigabit Network Connection                          | 174       | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 139       | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 131       | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 128       | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 109       | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 109       | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 102       | 0.71%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 90        | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 90        | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 87        | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 83        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 76        | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 72        | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 71        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 67        | 0.46%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 67        | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                            | 62        | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 62        | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 61        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 59        | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 57        | 0.4%    |
| Intel WiMAX Connection 2400m                                      | 57        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 56        | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 51        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 51        | 0.35%   |
| Intel Ethernet Connection (10) I219-V                             | 50        | 0.35%   |
| Intel 82579V Gigabit Network Connection                           | 50        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 17602     | 56.02%  |
| Ethernet | 13539     | 43.09%  |
| Modem    | 230       | 0.73%   |
| Unknown  | 52        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 15016     | 79.34%  |
| Ethernet | 3902      | 20.62%  |
| Modem    | 6         | 0.03%   |
| Unknown  | 2         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 12100     | 67.56%  |
| 1     | 5338      | 29.81%  |
| 0     | 304       | 1.7%    |
| 3     | 157       | 0.88%   |
| 4     | 7         | 0.04%   |
| 13    | 1         | 0.01%   |
| 10    | 1         | 0.01%   |
| 8     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 13952     | 76.07%  |
| Yes  | 4390      | 23.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 7078      | 50.9%   |
| Realtek Semiconductor           | 1296      | 9.32%   |
| Apple                           | 1285      | 9.24%   |
| Qualcomm Atheros Communications | 1047      | 7.53%   |
| IMC Networks                    | 818       | 5.88%   |
| Broadcom                        | 676       | 4.86%   |
| Foxconn / Hon Hai               | 355       | 2.55%   |
| Lite-On Technology              | 343       | 2.47%   |
| Dell                            | 325       | 2.34%   |
| Cambridge Silicon Radio         | 146       | 1.05%   |
| Hewlett-Packard                 | 140       | 1.01%   |
| Toshiba                         | 97        | 0.7%    |
| Ralink                          | 55        | 0.4%    |
| ASUSTek Computer                | 46        | 0.33%   |
| Alps Electric                   | 41        | 0.29%   |
| MediaTek                        | 31        | 0.22%   |
| Realtek                         | 22        | 0.16%   |
| USI                             | 19        | 0.14%   |
| Ralink Technology               | 14        | 0.1%    |
| Dynex                           | 14        | 0.1%    |
| Taiyo Yuden                     | 13        | 0.09%   |
| Edimax Technology               | 11        | 0.08%   |
| Foxconn International           | 10        | 0.07%   |
| Askey Computer                  | 4         | 0.03%   |
| TP-Link                         | 2         | 0.01%   |
| Primax Electronics              | 2         | 0.01%   |
| Opticis                         | 2         | 0.01%   |
| Marvell Semiconductor           | 2         | 0.01%   |
| Chicony Electronics             | 2         | 0.01%   |
| Unknown                         | 1         | 0.01%   |
| SINO WEALTH                     | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |
| Micro Star International        | 1         | 0.01%   |
| Kensington                      | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Actiontec Electronics           | 1         | 0.01%   |
| Actions                         | 1         | 0.01%   |
| Unknown                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 3039      | 21.81%  |
| Intel Bluetooth Device                              | 1492      | 10.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 855       | 6.14%   |
| Intel AX200 Bluetooth                               | 750       | 5.38%   |
| Realtek Bluetooth Radio                             | 732       | 5.25%   |
| Qualcomm Atheros  Bluetooth Device                  | 657       | 4.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 439       | 3.15%   |
| IMC Networks 802.11ac WLAN Adapter                  | 434       | 3.11%   |
| Apple Bluetooth Host Controller                     | 407       | 2.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 393       | 2.82%   |
| Apple Bluetooth USB Host Controller                 | 360       | 2.58%   |
| Intel AX210 Bluetooth                               | 286       | 2.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 270       | 1.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 160       | 1.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 155       | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 146       | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 135       | 0.97%   |
| IMC Networks Wireless_Device                        | 134       | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 134       | 0.96%   |
| Dell DW375 Bluetooth Module                         | 129       | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 117       | 0.84%   |
| IMC Networks Bluetooth Radio                        | 116       | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 110       | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 109       | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 99        | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 96        | 0.69%   |
| Lite-On Bluetooth Device                            | 96        | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 92        | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 87        | 0.62%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 84        | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                    | 79        | 0.57%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 65        | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 64        | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 60        | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 56        | 0.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 55        | 0.39%   |
| Ralink RT3290 Bluetooth                             | 55        | 0.39%   |
| IMC Networks Bluetooth Device                       | 53        | 0.38%   |
| Lite-On Wireless_Device                             | 51        | 0.37%   |
| Realtek RTL8821A Bluetooth                          | 43        | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 13710     | 62.17%  |
| AMD                                          | 3748      | 17%     |
| Nvidia                                       | 3220      | 14.6%   |
| C-Media Electronics                          | 151       | 0.68%   |
| Realtek Semiconductor                        | 131       | 0.59%   |
| Lenovo                                       | 99        | 0.45%   |
| Logitech                                     | 98        | 0.44%   |
| Apple                                        | 77        | 0.35%   |
| Texas Instruments                            | 71        | 0.32%   |
| JMTek                                        | 66        | 0.3%    |
| GN Netcom                                    | 49        | 0.22%   |
| Plantronics                                  | 44        | 0.2%    |
| Sony                                         | 32        | 0.15%   |
| SteelSeries ApS                              | 31        | 0.14%   |
| Razer USA                                    | 31        | 0.14%   |
| Kingston Technology                          | 28        | 0.13%   |
| Hewlett-Packard                              | 27        | 0.12%   |
| Corsair                                      | 25        | 0.11%   |
| Generalplus Technology                       | 24        | 0.11%   |
| Focusrite-Novation                           | 22        | 0.1%    |
| No brand                                     | 20        | 0.09%   |
| Creative Technology                          | 20        | 0.09%   |
| Blue Microphones                             | 18        | 0.08%   |
| Tenx Technology                              | 16        | 0.07%   |
| ASUSTek Computer                             | 12        | 0.05%   |
| Dell                                         | 9         | 0.04%   |
| Conexant Systems                             | 9         | 0.04%   |
| PreSonus Audio Electronics                   | 8         | 0.04%   |
| BR23                                         | 8         | 0.04%   |
| Audio-Technica                               | 8         | 0.04%   |
| Google                                       | 7         | 0.03%   |
| FiiO Electronics Technology                  | 7         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 6         | 0.03%   |
| Samson Technologies                          | 6         | 0.03%   |
| Microchip Technology                         | 6         | 0.03%   |
| KORG                                         | 6         | 0.03%   |
| GYROCOM C&C                                  | 6         | 0.03%   |
| AKAI                                         | 6         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.02%   |
| XMOS                                         | 5         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 1844      | 6.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 1553      | 5.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1309      | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1105      | 4.15%   |
| Intel Broadwell-U Audio Controller                                                                | 792       | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 779       | 2.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 774       | 2.9%    |
| AMD FCH Azalia Controller                                                                         | 682       | 2.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 659       | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 655       | 2.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 650       | 2.44%   |
| Intel 8 Series HD Audio Controller                                                                | 649       | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 646       | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 630       | 2.36%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 624       | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 586       | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 549       | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 471       | 1.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 461       | 1.73%   |
| Nvidia MCP79 High Definition Audio                                                                | 450       | 1.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 450       | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 398       | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 388       | 1.46%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 359       | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 354       | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 351       | 1.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 349       | 1.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 339       | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 318       | 1.19%   |
| Intel CM238 HD Audio Controller                                                                   | 313       | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 281       | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 281       | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 269       | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 253       | 0.95%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 252       | 0.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 250       | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 242       | 0.91%   |
| AMD High Definition Audio Controller                                                              | 216       | 0.81%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 186       | 0.7%    |
| Nvidia Audio device                                                                               | 185       | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3014      | 28.83%  |
| SK hynix            | 2733      | 26.15%  |
| Micron Technology   | 1351      | 12.92%  |
| Crucial             | 650       | 6.22%   |
| Unknown             | 542       | 5.19%   |
| Kingston            | 514       | 4.92%   |
| Elpida              | 239       | 2.29%   |
| Ramaxel Technology  | 180       | 1.72%   |
| A-DATA Technology   | 167       | 1.6%    |
| G.Skill             | 139       | 1.33%   |
| Unknown (ABCD)      | 132       | 1.26%   |
| Nanya Technology    | 130       | 1.24%   |
| Corsair             | 88        | 0.84%   |
| Unknown             | 79        | 0.76%   |
| Team                | 71        | 0.68%   |
| PNY                 | 49        | 0.47%   |
| Goldkey             | 36        | 0.34%   |
| Avant               | 33        | 0.32%   |
| Neo Forza           | 31        | 0.3%    |
| Patriot             | 29        | 0.28%   |
| Timetec             | 25        | 0.24%   |
| Sesame              | 18        | 0.17%   |
| 4ea5                | 16        | 0.15%   |
| Silicon Power       | 15        | 0.14%   |
| fef5                | 15        | 0.14%   |
| Transcend           | 11        | 0.11%   |
| Qimonda             | 10        | 0.1%    |
| ASint Technology    | 9         | 0.09%   |
| Apacer              | 9         | 0.09%   |
| CSX                 | 8         | 0.08%   |
| GSkill              | 7         | 0.07%   |
| ff                  | 7         | 0.07%   |
| SHARETRONIC         | 6         | 0.06%   |
| Unknown (0x0C26)    | 5         | 0.05%   |
| Gold Key            | 5         | 0.05%   |
| Toshiba             | 4         | 0.04%   |
| Super Talent        | 3         | 0.03%   |
| Innodisk            | 3         | 0.03%   |
| Axiom               | 3         | 0.03%   |
| V-Color             | 2         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 265       | 2.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 134       | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 129       | 1.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 120       | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 117       | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 111       | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 102       | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 97        | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 94        | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 92        | 0.83%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 91        | 0.82%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 90        | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 83        | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 82        | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 82        | 0.74%   |
| Unknown                                                          | 79        | 0.72%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 76        | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 72        | 0.65%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 70        | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 68        | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 68        | 0.62%   |
| Samsung RAM K4E8E324EB-EGCF 2GB LPDDR3 1867MT/s                  | 66        | 0.6%    |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 65        | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 62        | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 62        | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 62        | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 62        | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 61        | 0.55%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 57        | 0.52%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 54        | 0.49%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 54        | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 53        | 0.48%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 53        | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 51        | 0.46%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 49        | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 49        | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 49        | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 48        | 0.43%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 46        | 0.42%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 46        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 3678      | 40.66%  |
| DDR3    | 3032      | 33.52%  |
| DDR2    | 734       | 8.11%   |
| LPDDR4  | 497       | 5.49%   |
| LPDDR3  | 485       | 5.36%   |
| DDR5    | 191       | 2.11%   |
| LPDDR5  | 154       | 1.7%    |
| SDRAM   | 141       | 1.56%   |
| DDR     | 67        | 0.74%   |
| Unknown | 46        | 0.51%   |
| DRAM    | 20        | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 7893      | 87.25%  |
| Row Of Chips    | 807       | 8.92%   |
| Unknown         | 218       | 2.41%   |
| Chip            | 85        | 0.94%   |
| DIMM            | 42        | 0.46%   |
| Proprietary Car | 1         | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 3402      | 34.34%  |
| 4096  | 2700      | 27.25%  |
| 16384 | 1417      | 14.3%   |
| 2048  | 1283      | 12.95%  |
| 1024  | 639       | 6.45%   |
| 32768 | 407       | 4.11%   |
| 512   | 34        | 0.34%   |
| 256   | 19        | 0.19%   |
| 6144  | 2         | 0.02%   |
| 1536  | 2         | 0.02%   |
| 65536 | 1         | 0.01%   |
| 49152 | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 2223      | 23.07%  |
| 2667    | 1694      | 17.58%  |
| 3200    | 1587      | 16.47%  |
| 2400    | 666       | 6.91%   |
| 2133    | 501       | 5.2%    |
| 800     | 427       | 4.43%   |
| 1334    | 364       | 3.78%   |
| 1333    | 297       | 3.08%   |
| 667     | 263       | 2.73%   |
| 1867    | 235       | 2.44%   |
| 4267    | 185       | 1.92%   |
| 4800    | 179       | 1.86%   |
| 1067    | 154       | 1.6%    |
| 6400    | 137       | 1.42%   |
| 3266    | 118       | 1.22%   |
| Unknown | 113       | 1.17%   |
| 4199    | 64        | 0.66%   |
| 2048    | 56        | 0.58%   |
| 975     | 56        | 0.58%   |
| 1066    | 46        | 0.48%   |
| 4266    | 45        | 0.47%   |
| 8400    | 41        | 0.43%   |
| 3733    | 40        | 0.42%   |
| 533     | 40        | 0.42%   |
| 5600    | 17        | 0.18%   |
| 2933    | 15        | 0.16%   |
| 1866    | 12        | 0.12%   |
| 333     | 9         | 0.09%   |
| 266     | 7         | 0.07%   |
| 5500    | 5         | 0.05%   |
| 3000    | 5         | 0.05%   |
| 5200    | 4         | 0.04%   |
| 400     | 4         | 0.04%   |
| 1200    | 3         | 0.03%   |
| 133     | 3         | 0.03%   |
| 7467    | 2         | 0.02%   |
| 1776    | 2         | 0.02%   |
| 1639    | 2         | 0.02%   |
| 933     | 2         | 0.02%   |
| 666     | 2         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 65        | 43.05%  |
| Canon                  | 32        | 21.19%  |
| Brother Industries     | 32        | 21.19%  |
| Samsung Electronics    | 5         | 3.31%   |
| STMicroelectronics     | 3         | 1.99%   |
| Zebra                  | 2         | 1.32%   |
| Xerox                  | 2         | 1.32%   |
| Seiko Epson            | 2         | 1.32%   |
| Prolific Technology    | 2         | 1.32%   |
| Dymo-CoStar            | 2         | 1.32%   |
| TSC Auto ID Technology | 1         | 0.66%   |
| QinHeng Electronics    | 1         | 0.66%   |
| Pantum                 | 1         | 0.66%   |
| Dell                   | 1         | 0.66%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 3050                                          | 11        | 7.05%   |
| Canon PIXMA MG2500 Series                                 | 6         | 3.85%   |
| HP ENVY 4520 series                                       | 3         | 1.92%   |
| HP DeskJet 2600 series                                    | 3         | 1.92%   |
| Canon PIXMA MG3600 Series                                 | 3         | 1.92%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.28%   |
| Seiko Epson WF-3520 Series                                | 2         | 1.28%   |
| Samsung SCX-3400 Series                                   | 2         | 1.28%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.28%   |
| HP LaserJet P1005                                         | 2         | 1.28%   |
| HP LaserJet 1320                                          | 2         | 1.28%   |
| HP ENVY Photo 7800 series                                 | 2         | 1.28%   |
| HP DeskJet 4100 series                                    | 2         | 1.28%   |
| HP Deskjet 3510 series                                    | 2         | 1.28%   |
| HP Deskjet 3050A                                          | 2         | 1.28%   |
| HP DeskJet 2130 series                                    | 2         | 1.28%   |
| HP DeskJet 1110 series                                    | 2         | 1.28%   |
| Canon TR8500 series                                       | 2         | 1.28%   |
| Canon PIXMA MX490 Series                                  | 2         | 1.28%   |
| Brother Printer                                           | 2         | 1.28%   |
| Brother MFC-L2710DW series                                | 2         | 1.28%   |
| Brother MFC-J485DW                                        | 2         | 1.28%   |
| Brother MFC-8690DW                                        | 2         | 1.28%   |
| Brother HL-L2340D series                                  | 2         | 1.28%   |
| Brother HL-L2320D series                                  | 2         | 1.28%   |
| Brother HL-L2305 series                                   | 2         | 1.28%   |
| Brother HL-L2300D series                                  | 2         | 1.28%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1         | 0.64%   |
| Zebra ZP 450 Printer                                      | 1         | 0.64%   |
| Xerox Phaser 6500N                                        | 1         | 0.64%   |
| Xerox Phaser 3610                                         | 1         | 0.64%   |
| TSC Auto ID Printer                                       | 1         | 0.64%   |
| STMicroelectronics USB Printer P                          | 1         | 0.64%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 0.64%   |
| Samsung M283x Series                                      | 1         | 0.64%   |
| Samsung M2020 Series                                      | 1         | 0.64%   |
| QinHeng CH340S                                            | 1         | 0.64%   |
| Pantum P2500W series                                      | 1         | 0.64%   |
| HP PSC 750xi                                              | 1         | 0.64%   |
| HP OfficeJet Reflash                                      | 1         | 0.64%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 10        | 47.62%  |
| Seiko Epson            | 9         | 42.86%  |
| Microtek International | 1         | 4.76%   |
| Hewlett-Packard        | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 2         | 9.52%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 2         | 9.52%   |
| Canon CanoScan LiDE 210                                     | 2         | 9.52%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 4.76%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 4.76%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]     | 1         | 4.76%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 4.76%   |
| Seiko Epson ES-D200 [GT-S50]                                | 1         | 4.76%   |
| Microtek International ScanMaker V6USL                      | 1         | 4.76%   |
| HP OfficeJet 6110                                           | 1         | 4.76%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 4.76%   |
| Canon CanoScan LiDE 70                                      | 1         | 4.76%   |
| Canon CanoScan LiDE 60                                      | 1         | 4.76%   |
| Canon CanoScan LiDE 500F                                    | 1         | 4.76%   |
| Canon CanoScan LiDE 220                                     | 1         | 4.76%   |
| Canon CanoScan LiDE 200                                     | 1         | 4.76%   |
| Canon CanoScan LiDE 110                                     | 1         | 4.76%   |
| Canon CanoScan LiDE 100                                     | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 3198      | 21.68%  |
| Microdia                               | 1617      | 10.96%  |
| Realtek Semiconductor                  | 1311      | 8.89%   |
| IMC Networks                           | 1210      | 8.2%    |
| Sunplus Innovation Technology          | 998       | 6.76%   |
| Bison Electronics                      | 888       | 6.02%   |
| Quanta                                 | 845       | 5.73%   |
| Cheng Uei Precision Industry (Foxlink) | 686       | 4.65%   |
| Apple                                  | 619       | 4.2%    |
| Suyin                                  | 487       | 3.3%    |
| Lite-On Technology                     | 315       | 2.14%   |
| Acer                                   | 315       | 2.14%   |
| Luxvisions Innotech Limited            | 275       | 1.86%   |
| Logitech                               | 271       | 1.84%   |
| Syntek                                 | 234       | 1.59%   |
| Ricoh                                  | 167       | 1.13%   |
| Samsung Electronics                    | 143       | 0.97%   |
| Importek                               | 134       | 0.91%   |
| Alcor Micro                            | 124       | 0.84%   |
| Silicon Motion                         | 96        | 0.65%   |
| Lenovo                                 | 93        | 0.63%   |
| Primax Electronics                     | 64        | 0.43%   |
| Sonix Technology                       | 63        | 0.43%   |
| SunplusIT                              | 50        | 0.34%   |
| OmniVision Technologies                | 48        | 0.33%   |
| Intel                                  | 34        | 0.23%   |
| ALi                                    | 31        | 0.21%   |
| icSpring                               | 30        | 0.2%    |
| Microsoft                              | 25        | 0.17%   |
| LG Electronics                         | 22        | 0.15%   |
| Z-Star Microelectronics                | 21        | 0.14%   |
| ARC International                      | 18        | 0.12%   |
| Shenzhen Kingcome Optoelectronic       | 16        | 0.11%   |
| HRY                                    | 14        | 0.09%   |
| Tobii Technology AB                    | 13        | 0.09%   |
| GEMBIRD                                | 13        | 0.09%   |
| Razer USA                              | 12        | 0.08%   |
| Generalplus Technology                 | 11        | 0.07%   |
| 8SSC20F27114V1SR0BK1X4S                | 10        | 0.07%   |
| Goodong                                | 9         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 753       | 5.07%   |
| Microdia Integrated_Webcam_HD                                  | 706       | 4.75%   |
| Realtek Integrated_Webcam_HD                                   | 533       | 3.59%   |
| IMC Networks Integrated Camera                                 | 383       | 2.58%   |
| Sunplus Integrated_Webcam_HD                                   | 379       | 2.55%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 362       | 2.44%   |
| Bison Integrated Camera                                        | 307       | 2.07%   |
| Chicony HD WebCam                                              | 245       | 1.65%   |
| Microdia Integrated Webcam                                     | 205       | 1.38%   |
| Apple FaceTime HD Camera                                       | 192       | 1.29%   |
| Chicony HP TrueVision HD                                       | 164       | 1.1%    |
| Quanta HP TrueVision HD Camera                                 | 161       | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 157       | 1.06%   |
| Apple Built-in iSight                                          | 145       | 0.98%   |
| Syntek Integrated Camera                                       | 139       | 0.94%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 139       | 0.94%   |
| Realtek USB camera                                             | 139       | 0.94%   |
| Chicony HP TrueVision HD Camera                                | 138       | 0.93%   |
| Lite-On Integrated Camera                                      | 121       | 0.81%   |
| Chicony USB2.0 Camera                                          | 119       | 0.8%    |
| Chicony HP HD Camera                                           | 118       | 0.79%   |
| Quanta HD User Facing                                          | 117       | 0.79%   |
| Acer BisonCam,NB Pro                                           | 117       | 0.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 113       | 0.76%   |
| Bison HD Webcam                                                | 113       | 0.76%   |
| Quanta Chromebook HD Camera                                    | 107       | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 103       | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 103       | 0.69%   |
| Chicony TOSHIBA Web Camera - HD                                | 101       | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 100       | 0.67%   |
| Realtek Integrated Webcam HD                                   | 99        | 0.67%   |
| Suyin HP Truevision HD                                         | 96        | 0.65%   |
| Quanta HP Wide Vision HD Camera                                | 94        | 0.63%   |
| Chicony USB2.0 HD UVC WebCam                                   | 92        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 89        | 0.6%    |
| Chicony HP Webcam                                              | 88        | 0.59%   |
| Chicony HD User Facing                                         | 87        | 0.59%   |
| Chicony Integrated Camera (1280x720@30)                        | 84        | 0.57%   |
| Chicony HP Wide Vision HD Camera                               | 77        | 0.52%   |
| Realtek Integrated Webcam                                      | 76        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 1148      | 39.9%   |
| Synaptics                          | 795       | 27.63%  |
| Shenzhen Goodix Technology         | 311       | 10.81%  |
| Upek                               | 150       | 5.21%   |
| AuthenTec                          | 150       | 5.21%   |
| Elan Microelectronics              | 136       | 4.73%   |
| LighTuning Technology              | 68        | 2.36%   |
| STMicroelectronics                 | 66        | 2.29%   |
| Focal-systems.Corp                 | 26        | 0.9%    |
| Samsung Electronics                | 11        | 0.38%   |
| HOLTEK                             | 6         | 0.21%   |
| Realtek USB2.0 Finger Print Bridge | 5         | 0.17%   |
| DigitalPersona                     | 5         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 291       | 10.11%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 213       | 7.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 202       | 7.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 169       | 5.87%   |
| Shenzhen Goodix FingerPrint                                                | 151       | 5.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 144       | 5.01%   |
| Validity Sensors Fingerprint scanner                                       | 120       | 4.17%   |
| Shenzhen Goodix  FingerPrint Device                                        | 116       | 4.03%   |
| Validity Sensors VFS491                                                    | 89        | 3.09%   |
| Validity Sensors Synaptics WBDI                                            | 89        | 3.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 87        | 3.02%   |
| Elan ELAN:Fingerprint                                                      | 76        | 2.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 75        | 2.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 71        | 2.47%   |
| STMicroelectronics Fingerprint Reader                                      | 64        | 2.22%   |
| AuthenTec AES2810                                                          | 62        | 2.16%   |
| Elan ELAN:ARM-M4                                                           | 56        | 1.95%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 51        | 1.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 49        | 1.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 49        | 1.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 45        | 1.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 44        | 1.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 37        | 1.29%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 37        | 1.29%   |
| Synaptics UWP WBDI Device                                                  | 36        | 1.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 33        | 1.15%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 29        | 1.01%   |
| Synaptics WBDI Device                                                      | 29        | 1.01%   |
| Synaptics TouchPad                                                         | 29        | 1.01%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 28        | 0.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 0.94%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 26        | 0.9%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 24        | 0.83%   |
| AuthenTec Fingerprint Sensor                                               | 23        | 0.8%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 20        | 0.7%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 20        | 0.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 19        | 0.66%   |
| Synaptics UWP WBDI                                                         | 18        | 0.63%   |
| Unknown                                                                    | 18        | 0.63%   |
| AuthenTec AES1600                                                          | 14        | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 914       | 65.76%  |
| Alcor Micro               | 177       | 12.73%  |
| Upek                      | 105       | 7.55%   |
| O2 Micro                  | 96        | 6.91%   |
| Lenovo                    | 41        | 2.95%   |
| SCM Microsystems          | 24        | 1.73%   |
| Gemalto (was Gemplus)     | 9         | 0.65%   |
| Yubico.com                | 6         | 0.43%   |
| Realtek Semiconductor     | 6         | 0.43%   |
| OmniKey                   | 3         | 0.22%   |
| Chicony Electronics       | 2         | 0.14%   |
| Cherry                    | 2         | 0.14%   |
| Purism, SPC               | 1         | 0.07%   |
| NXP Semiconductors        | 1         | 0.07%   |
| MagTek                    | 1         | 0.07%   |
| Aladdin Knowledge Systems | 1         | 0.07%   |
| Advanced Card Systems     | 1         | 0.07%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 419       | 30.08%  |
| Broadcom 5880                                                                | 223       | 16.01%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 173       | 12.42%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 156       | 11.2%   |
| Broadcom 58200                                                               | 107       | 7.68%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 105       | 7.54%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 78        | 5.6%    |
| Lenovo Integrated Smart Card Reader                                          | 41        | 2.94%   |
| O2 Micro Oz776 SmartCard Reader                                              | 18        | 1.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 12        | 0.86%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 11        | 0.79%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 0.43%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 6         | 0.43%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 0.36%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 4         | 0.29%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 3         | 0.22%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.22%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 2         | 0.14%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.14%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.14%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.14%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.07%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.07%   |
| SCM Microsystems SCR3311 Smart Card Reader                                   | 1         | 0.07%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.07%   |
| Purism, SPC Librem Key                                                       | 1         | 0.07%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.07%   |
| OmniKey CardMan 4321                                                         | 1         | 0.07%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.07%   |
| NXP Semiconductors PR533                                                     | 1         | 0.07%   |
| MagTek ZCS160-PCSC                                                           | 1         | 0.07%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.07%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.07%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.07%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 11249     | 61.14%  |
| 1     | 5780      | 31.41%  |
| 2     | 1137      | 6.18%   |
| 3     | 160       | 0.87%   |
| 4     | 36        | 0.2%    |
| 5     | 15        | 0.08%   |
| 6     | 12        | 0.07%   |
| 8     | 5         | 0.03%   |
| 7     | 3         | 0.02%   |
| 9     | 2         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 2833      | 33.28%  |
| Graphics card            | 1549      | 18.2%   |
| Chipcard                 | 1267      | 14.88%  |
| Net/wireless             | 876       | 10.29%  |
| Multimedia controller    | 743       | 8.73%   |
| Camera                   | 236       | 2.77%   |
| Storage                  | 235       | 2.76%   |
| Communication controller | 186       | 2.19%   |
| Bluetooth                | 158       | 1.86%   |
| Sound                    | 112       | 1.32%   |
| Net/ethernet             | 88        | 1.03%   |
| Card reader              | 77        | 0.9%    |
| Modem                    | 53        | 0.62%   |
| Network                  | 52        | 0.61%   |
| Firewire controller      | 11        | 0.13%   |
| Flash memory             | 8         | 0.09%   |
| Storage/nvme             | 6         | 0.07%   |
| Dvb card                 | 6         | 0.07%   |
| Unassigned class         | 3         | 0.04%   |
| Tv card                  | 3         | 0.04%   |
| Storage/ide              | 3         | 0.04%   |
| Wireless                 | 2         | 0.02%   |
| Unclassified device      | 2         | 0.02%   |
| Storage/raid             | 2         | 0.02%   |
| Storage/ata              | 1         | 0.01%   |

