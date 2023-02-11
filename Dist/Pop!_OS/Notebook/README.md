Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 6545

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | Latitude E7240              | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| System76      | Lemur Pro                   | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| Dell          | Latitude E7240              | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| HP            | ProBook 6550b               | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [f201c986f0](https://linux-hardware.org/?probe=f201c986f0) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| HP            | Notebook                    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [641654df50](https://linux-hardware.org/?probe=641654df50) | Jan 19, 2023 |
| Dell          | Latitude E7240              | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| Razer         | Blade                       | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Framework     | Laptop                      | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| Acer          | Aspire 5625G                | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| Apple         | MacBook8,1                  | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Dell          | Latitude E7240              | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| Dell          | Latitude E7240              | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| System76      | Bonobo WS                   | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | [1178b43f82](https://linux-hardware.org/?probe=1178b43f82) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Dell          | Latitude E7240              | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| System76      | Lemur Pro                   | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [de111c3be5](https://linux-hardware.org/?probe=de111c3be5) | Dec 24, 2022 |
| HP            | EliteBook 865 16 inch G9... | [857cb922f9](https://linux-hardware.org/?probe=857cb922f9) | Dec 24, 2022 |
| Dell          | Latitude E7470              | [8e6bdc1809](https://linux-hardware.org/?probe=8e6bdc1809) | Dec 24, 2022 |
| System76      | Pangolin                    | [2ee273cbcf](https://linux-hardware.org/?probe=2ee273cbcf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| Timi          | TM1703                      | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Dell          | Latitude E7240              | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Inspiron 7572               | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| System76      | Gazelle                     | [da46fb926a](https://linux-hardware.org/?probe=da46fb926a) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| GPU Compan... | GWNR71517                   | [e680612eb4](https://linux-hardware.org/?probe=e680612eb4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | XPS 15 9510                 | [1641d91910](https://linux-hardware.org/?probe=1641d91910) | Dec 17, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| System76      | Gazelle                     | [b5ef8cec53](https://linux-hardware.org/?probe=b5ef8cec53) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Apple         | MacBookPro10,1              | [a22dd35e04](https://linux-hardware.org/?probe=a22dd35e04) | Dec 14, 2022 |
| Apple         | MacBookPro11,3              | [d0c2bf600a](https://linux-hardware.org/?probe=d0c2bf600a) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | [e5d69d9f81](https://linux-hardware.org/?probe=e5d69d9f81) | Dec 13, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| System76      | Gazelle                     | [8498636db6](https://linux-hardware.org/?probe=8498636db6) | Dec 12, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d438f3f50a](https://linux-hardware.org/?probe=d438f3f50a) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire A515-44G             | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| System76      | Gazelle                     | [8b0297b19e](https://linux-hardware.org/?probe=8b0297b19e) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [ef20df1d4f](https://linux-hardware.org/?probe=ef20df1d4f) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| Dell          | G15 5515                    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | Inspiron 1750               | [e369c14198](https://linux-hardware.org/?probe=e369c14198) | Dec 07, 2022 |
| Lenovo        | IdeaPad Y560                | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | G5 5505                     | [f19a76c344](https://linux-hardware.org/?probe=f19a76c344) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| System76      | Gazelle                     | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Nitro AN515-54              | [33f26cca4f](https://linux-hardware.org/?probe=33f26cca4f) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Dell          | Latitude E7240              | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Google        | Cyan                        | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| Dell          | Latitude E7240              | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Alienware     | 17                          | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| Dell          | Inspiron 7720               | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Precision 7670              | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Dell          | G15 5515                    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Lemur Pro                   | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| MSI           | MS-1688                     | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Dell          | Latitude E7240              | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| System76      | Galago Pro                  | [8728b448e9](https://linux-hardware.org/?probe=8728b448e9) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [0622b6fa8f](https://linux-hardware.org/?probe=0622b6fa8f) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [bec7082d7a](https://linux-hardware.org/?probe=bec7082d7a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [fa19e49b0a](https://linux-hardware.org/?probe=fa19e49b0a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [d63435720c](https://linux-hardware.org/?probe=d63435720c) | Nov 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| Dell          | XPS 13 9310                 | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Apple         | MacBookPro3,1               | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| MSI           | Prestige 15 A12UC           | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| HP            | ZBook 15                    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Dell          | G15 5511                    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Dell          | Latitude E7240              | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Dell          | XPS 15 9570                 | [d76c41ef1b](https://linux-hardware.org/?probe=d76c41ef1b) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| Apple         | MacBookAir6,2               | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| System76      | Gazelle                     | [77686d0854](https://linux-hardware.org/?probe=77686d0854) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [c70d6b90b6](https://linux-hardware.org/?probe=c70d6b90b6) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| System76      | Oryx Pro                    | [7de5d55c99](https://linux-hardware.org/?probe=7de5d55c99) | Oct 22, 2022 |
| Intel         | Montevina CRB               | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [504036a2f6](https://linux-hardware.org/?probe=504036a2f6) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| System76      | Lemur Pro                   | [df61411c9d](https://linux-hardware.org/?probe=df61411c9d) | Oct 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [ed64a103f1](https://linux-hardware.org/?probe=ed64a103f1) | Oct 18, 2022 |
| HP            | Laptop 15-dy0xxx            | [2d1482e433](https://linux-hardware.org/?probe=2d1482e433) | Oct 18, 2022 |
| System76      | Lemur Pro                   | [53226822f5](https://linux-hardware.org/?probe=53226822f5) | Oct 18, 2022 |
| MSI           | GF63 Thin 11UD              | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| Lenovo        | Legion Y740-17IRH 81UG      | [67aec6ad33](https://linux-hardware.org/?probe=67aec6ad33) | Oct 17, 2022 |
| MSI           | GP72VR 7RF                  | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| HP            | G62                         | [839b09744e](https://linux-hardware.org/?probe=839b09744e) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [502f19e8b3](https://linux-hardware.org/?probe=502f19e8b3) | Oct 16, 2022 |
| HP            | Pavilion g6                 | [2729d4b101](https://linux-hardware.org/?probe=2729d4b101) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Google        | Kefka                       | [4775b995dd](https://linux-hardware.org/?probe=4775b995dd) | Oct 13, 2022 |
| System76      | Lemur Pro                   | [ec569ddc8f](https://linux-hardware.org/?probe=ec569ddc8f) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [3c11d61a58](https://linux-hardware.org/?probe=3c11d61a58) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [236e24530f](https://linux-hardware.org/?probe=236e24530f) | Oct 12, 2022 |
| Dell          | Precision M6700             | [4c867e9075](https://linux-hardware.org/?probe=4c867e9075) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| Razer         | Blade                       | [c7386df23f](https://linux-hardware.org/?probe=c7386df23f) | Oct 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| HP            | Pavilion 15                 | [8b93ec27f4](https://linux-hardware.org/?probe=8b93ec27f4) | Oct 12, 2022 |
| GPU Compan... | GWTN141-10                  | [1feb5d7501](https://linux-hardware.org/?probe=1feb5d7501) | Oct 12, 2022 |
| Alienware     | 15 R3                       | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [f4a46537c2](https://linux-hardware.org/?probe=f4a46537c2) | Oct 10, 2022 |
| Acer          | Predator PH317-52           | [379aad9180](https://linux-hardware.org/?probe=379aad9180) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| HP            | Laptop 15-bw0xx             | [7231761ea1](https://linux-hardware.org/?probe=7231761ea1) | Oct 09, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Dell          | G7 7500                     | [e50429ccfa](https://linux-hardware.org/?probe=e50429ccfa) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Sony          | VPCEH3LFX                   | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| Alienware     | 17 R4                       | [cac06d6050](https://linux-hardware.org/?probe=cac06d6050) | Oct 07, 2022 |
| Positivo      | Mobile                      | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| MSI           | GP66 Leopard 10UG           | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Acer          | Aspire 5520                 | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Lenovo        | IdeaPad Y560                | [15e2c8994f](https://linux-hardware.org/?probe=15e2c8994f) | Oct 06, 2022 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [fa7e7d106e](https://linux-hardware.org/?probe=fa7e7d106e) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Valve         | Jupiter                     | [2fda8270f0](https://linux-hardware.org/?probe=2fda8270f0) | Oct 05, 2022 |
| Acer          | Aspire A315-21              | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Lenovo        | Z51-70 80K6                 | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| System76      | Lemur Pro                   | [8842585a92](https://linux-hardware.org/?probe=8842585a92) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Dell          | Latitude E6420              | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| Google        | Banon                       | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [2637a452d0](https://linux-hardware.org/?probe=2637a452d0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Dell          | XPS L421X                   | [aedcc42b0a](https://linux-hardware.org/?probe=aedcc42b0a) | Oct 02, 2022 |
| Apple         | MacBookPro5,2               | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| Alienware     | 15 R3                       | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| ASUSTek       | GL502VM                     | [1d1616405d](https://linux-hardware.org/?probe=1d1616405d) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| Apple         | MacBook7,1                  | [49595ef8f4](https://linux-hardware.org/?probe=49595ef8f4) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Micro Elec... | Element                     | [9cee0f76c1](https://linux-hardware.org/?probe=9cee0f76c1) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| System76      | Darter Pro                  | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [bde2b36c88](https://linux-hardware.org/?probe=bde2b36c88) | Oct 01, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Dell          | Latitude 5400               | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [81653ba834](https://linux-hardware.org/?probe=81653ba834) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [d31b97630d](https://linux-hardware.org/?probe=d31b97630d) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | [5ce350f38b](https://linux-hardware.org/?probe=5ce350f38b) | Sep 28, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a3c4032d28](https://linux-hardware.org/?probe=a3c4032d28) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [99b6a53bd2](https://linux-hardware.org/?probe=99b6a53bd2) | Sep 27, 2022 |
| ASUSTek       | GL702VSK                    | [3b69ddb263](https://linux-hardware.org/?probe=3b69ddb263) | Sep 27, 2022 |
| MSI           | GS73 Stealth 8RF            | [37d9172163](https://linux-hardware.org/?probe=37d9172163) | Sep 26, 2022 |
| Acer          | Nitro AN515-45              | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| ASUSTek       | GL702VSK                    | [e91056ceab](https://linux-hardware.org/?probe=e91056ceab) | Sep 26, 2022 |
| Dell          | Inspiron N5110              | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| ASUSTek       | K52N                        | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [e9de38d8eb](https://linux-hardware.org/?probe=e9de38d8eb) | Sep 25, 2022 |
| System76      | Oryx Pro                    | [3cf39a6993](https://linux-hardware.org/?probe=3cf39a6993) | Sep 24, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| HP            | Laptop 15s-eq1xxx           | [2bc6e102ef](https://linux-hardware.org/?probe=2bc6e102ef) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| Apple         | MacBookPro9,2               | [86b6d46191](https://linux-hardware.org/?probe=86b6d46191) | Sep 24, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| System76      | Darter Pro                  | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| System76      | Darter Pro                  | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Dell          | Inspiron 5520               | [032bbec1e3](https://linux-hardware.org/?probe=032bbec1e3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Dell          | Latitude 3490               | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Dell          | Latitude 7490               | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Dell          | Vostro 3500                 | [7fa417e9a6](https://linux-hardware.org/?probe=7fa417e9a6) | Sep 21, 2022 |
| Apple         | MacBookAir6,2               | [7fc6799a48](https://linux-hardware.org/?probe=7fc6799a48) | Sep 21, 2022 |
| Dell          | Inspiron 5577               | [c6f4124e49](https://linux-hardware.org/?probe=c6f4124e49) | Sep 21, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| Itronix       | GD8200                      | [d9f515b935](https://linux-hardware.org/?probe=d9f515b935) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| GPU Compan... | GWTN141-10                  | [6d43012457](https://linux-hardware.org/?probe=6d43012457) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [47b0aed151](https://linux-hardware.org/?probe=47b0aed151) | Sep 19, 2022 |
| Framework     | Laptop                      | [8dbbe54af9](https://linux-hardware.org/?probe=8dbbe54af9) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [37b4da9922](https://linux-hardware.org/?probe=37b4da9922) | Sep 18, 2022 |
| Gateway       | NV55C                       | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Latitude E7470              | [ceed7544ab](https://linux-hardware.org/?probe=ceed7544ab) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| MSI           | Sword 15 A11UD              | [e749154c3d](https://linux-hardware.org/?probe=e749154c3d) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [5a1085f939](https://linux-hardware.org/?probe=5a1085f939) | Sep 18, 2022 |
| ASUSTek       | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| MSI           | Prestige 15 A12UC           | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| OriginPC      | NT17-PRO                    | [962138caa9](https://linux-hardware.org/?probe=962138caa9) | Sep 17, 2022 |
| System76      | Darter Pro                  | [5d1e0ddc1a](https://linux-hardware.org/?probe=5d1e0ddc1a) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| ASUSTek       | E402NA                      | [9d97fe89bb](https://linux-hardware.org/?probe=9d97fe89bb) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| HP            | Laptop 15s-fq1xxx           | [dc870b4e8a](https://linux-hardware.org/?probe=dc870b4e8a) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude 3420               | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| Dell          | XPS 13 9360                 | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| ASUSTek       | X555LN                      | [64b85307ec](https://linux-hardware.org/?probe=64b85307ec) | Sep 14, 2022 |
| ASUSTek       | X405UA                      | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [81b9b18da4](https://linux-hardware.org/?probe=81b9b18da4) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Dell          | Studio 1555                 | [0d0f3de3b4](https://linux-hardware.org/?probe=0d0f3de3b4) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [1889334e1f](https://linux-hardware.org/?probe=1889334e1f) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [f9add8f93d](https://linux-hardware.org/?probe=f9add8f93d) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | Dev One Notebook PC         | [bb72f0c2f4](https://linux-hardware.org/?probe=bb72f0c2f4) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5811e17863](https://linux-hardware.org/?probe=5811e17863) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4d3543d03f](https://linux-hardware.org/?probe=4d3543d03f) | Sep 09, 2022 |
| Dell          | Precision 3551              | [78f7c77b35](https://linux-hardware.org/?probe=78f7c77b35) | Sep 09, 2022 |
| System76      | Galago Pro                  | [8d52d900f2](https://linux-hardware.org/?probe=8d52d900f2) | Sep 09, 2022 |
| Dell          | Inspiron 5457               | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| AZW           | SEi                         | [d3531738fa](https://linux-hardware.org/?probe=d3531738fa) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [6108c677a2](https://linux-hardware.org/?probe=6108c677a2) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [0f8da1f0c8](https://linux-hardware.org/?probe=0f8da1f0c8) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| HP            | 245 G6                      | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| Acer          | Aspire S3                   | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [cb787086fa](https://linux-hardware.org/?probe=cb787086fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Dell          | XPS 15 9500                 | [ea5f9662d7](https://linux-hardware.org/?probe=ea5f9662d7) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| Apple         | MacBookPro11,3              | [c40b757ca3](https://linux-hardware.org/?probe=c40b757ca3) | Sep 04, 2022 |
| MSI           | GP72 7RDX                   | [5d4efc6589](https://linux-hardware.org/?probe=5d4efc6589) | Sep 04, 2022 |
| Apple         | MacBookPro5,5               | [70de682c06](https://linux-hardware.org/?probe=70de682c06) | Sep 03, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30D0... | [b75636bf8b](https://linux-hardware.org/?probe=b75636bf8b) | Sep 03, 2022 |
| Dell          | Inspiron 13-7378            | [0ab8b4e169](https://linux-hardware.org/?probe=0ab8b4e169) | Sep 03, 2022 |
| Dell          | XPS 15 9520                 | [39e1d43301](https://linux-hardware.org/?probe=39e1d43301) | Sep 03, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [db5a53a31c](https://linux-hardware.org/?probe=db5a53a31c) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | [cfb4e75518](https://linux-hardware.org/?probe=cfb4e75518) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| ASUSTek       | X550CL                      | [6e45ea1408](https://linux-hardware.org/?probe=6e45ea1408) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Dell          | Latitude E5570              | [20350411cf](https://linux-hardware.org/?probe=20350411cf) | Sep 03, 2022 |
| HUAWEI        | KPL-W0X                     | [2e3f16bc80](https://linux-hardware.org/?probe=2e3f16bc80) | Sep 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [9b42566191](https://linux-hardware.org/?probe=9b42566191) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| Dell          | Precision 5530              | [0151d15e28](https://linux-hardware.org/?probe=0151d15e28) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| Samsung       | 270E5G/270E5U               | [7ef3570396](https://linux-hardware.org/?probe=7ef3570396) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Dell          | G3 3590                     | [cbe6c26276](https://linux-hardware.org/?probe=cbe6c26276) | Sep 01, 2022 |
| ASUSTek       | N552VW                      | [99d4a9be86](https://linux-hardware.org/?probe=99d4a9be86) | Sep 01, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [55073b08dc](https://linux-hardware.org/?probe=55073b08dc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| Apple         | MacBookAir9,1               | [51c4002c97](https://linux-hardware.org/?probe=51c4002c97) | Sep 01, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d96b24b7f3](https://linux-hardware.org/?probe=d96b24b7f3) | Sep 01, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [838e09c9cf](https://linux-hardware.org/?probe=838e09c9cf) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | [d6e9455a63](https://linux-hardware.org/?probe=d6e9455a63) | Aug 31, 2022 |
| Dell          | Inspiron 13-7378            | [42666a5460](https://linux-hardware.org/?probe=42666a5460) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [6eeadaf886](https://linux-hardware.org/?probe=6eeadaf886) | Aug 31, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [56e8f54a3e](https://linux-hardware.org/?probe=56e8f54a3e) | Aug 31, 2022 |
| Acer          | Aspire E1-571               | [4db54180a8](https://linux-hardware.org/?probe=4db54180a8) | Aug 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6d04d534fa](https://linux-hardware.org/?probe=6d04d534fa) | Aug 31, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [988032b933](https://linux-hardware.org/?probe=988032b933) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Dell          | Inspiron 3493               | [dc23941a16](https://linux-hardware.org/?probe=dc23941a16) | Aug 31, 2022 |
| ASUSTek       | G75VX                       | [e249508d61](https://linux-hardware.org/?probe=e249508d61) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| Toshiba       | Satellite C845              | [58d3152512](https://linux-hardware.org/?probe=58d3152512) | Aug 29, 2022 |
| ASUSTek       | N550JV                      | [059ab7e21e](https://linux-hardware.org/?probe=059ab7e21e) | Aug 29, 2022 |
| HP            | EliteBook 8570w             | [907d5f36e6](https://linux-hardware.org/?probe=907d5f36e6) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [aa5f4a0207](https://linux-hardware.org/?probe=aa5f4a0207) | Aug 29, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [065da8ca1e](https://linux-hardware.org/?probe=065da8ca1e) | Aug 29, 2022 |
| Apple         | MacBook5,2                  | [780e5cbb44](https://linux-hardware.org/?probe=780e5cbb44) | Aug 28, 2022 |
| Dell          | XPS 13 9305                 | [d8bd3d6fc6](https://linux-hardware.org/?probe=d8bd3d6fc6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [c4be3fe1b6](https://linux-hardware.org/?probe=c4be3fe1b6) | Aug 28, 2022 |
| Lenovo        | ThinkPad W520 4270CTO       | [568802fb43](https://linux-hardware.org/?probe=568802fb43) | Aug 28, 2022 |
| HP            | ENVY dv7                    | [cbd3824347](https://linux-hardware.org/?probe=cbd3824347) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2e085a419b](https://linux-hardware.org/?probe=2e085a419b) | Aug 27, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c47cd7c7ed](https://linux-hardware.org/?probe=c47cd7c7ed) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1746f3874c](https://linux-hardware.org/?probe=1746f3874c) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c75cbf917](https://linux-hardware.org/?probe=1c75cbf917) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| Dell          | XPS 9315                    | [6ab1d7417d](https://linux-hardware.org/?probe=6ab1d7417d) | Aug 27, 2022 |
| Apple         | MacBook4,1                  | [fdb7c715b3](https://linux-hardware.org/?probe=fdb7c715b3) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [a45848f10f](https://linux-hardware.org/?probe=a45848f10f) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | [88467a99ae](https://linux-hardware.org/?probe=88467a99ae) | Aug 26, 2022 |
| Dell          | Precision M4600             | [de9a03d9be](https://linux-hardware.org/?probe=de9a03d9be) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [8aa6fdef16](https://linux-hardware.org/?probe=8aa6fdef16) | Aug 26, 2022 |
| Panasonic     | FZ55-1                      | [0ec106ca31](https://linux-hardware.org/?probe=0ec106ca31) | Aug 26, 2022 |
| Dell          | Precision M4600             | [83c727c6db](https://linux-hardware.org/?probe=83c727c6db) | Aug 26, 2022 |
| Dell          | Latitude E6400              | [714643ef93](https://linux-hardware.org/?probe=714643ef93) | Aug 25, 2022 |
| ASUSTek       | X540LJ                      | [edac754e93](https://linux-hardware.org/?probe=edac754e93) | Aug 25, 2022 |
| Acer          | Swift SFX14-41G             | [8d1cad5e52](https://linux-hardware.org/?probe=8d1cad5e52) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [945109f9f8](https://linux-hardware.org/?probe=945109f9f8) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HONOR         | NBR-WAX9                    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| HUAWEI        | KPL-W0X                     | [b502ab922f](https://linux-hardware.org/?probe=b502ab922f) | Aug 25, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [b008775e13](https://linux-hardware.org/?probe=b008775e13) | Aug 24, 2022 |
| HP            | Dev One Notebook PC         | [4263165650](https://linux-hardware.org/?probe=4263165650) | Aug 24, 2022 |
| MSI           | Prestige 15 A10SC           | [35ffc8d54b](https://linux-hardware.org/?probe=35ffc8d54b) | Aug 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | [6cb194ca87](https://linux-hardware.org/?probe=6cb194ca87) | Aug 23, 2022 |
| Acer          | Aspire V3-772G              | [92b070c9be](https://linux-hardware.org/?probe=92b070c9be) | Aug 23, 2022 |
| Positivo      | W942SV_SV1                  | [24ad2b387d](https://linux-hardware.org/?probe=24ad2b387d) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| MSI           | PS63 Modern 8RC             | [33a1092c01](https://linux-hardware.org/?probe=33a1092c01) | Aug 22, 2022 |
| Dell          | XPS 15 9520                 | [33ff4e4962](https://linux-hardware.org/?probe=33ff4e4962) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [52a1f16ef3](https://linux-hardware.org/?probe=52a1f16ef3) | Aug 22, 2022 |
| Apple         | MacBookPro6,1               | [ae19610f33](https://linux-hardware.org/?probe=ae19610f33) | Aug 21, 2022 |
| Acer          | Swift SFX14-41G             | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| System76      | Oryx Pro                    | [7c763e43c6](https://linux-hardware.org/?probe=7c763e43c6) | Aug 21, 2022 |
| Dell          | Inspiron 5547               | [f67221bd42](https://linux-hardware.org/?probe=f67221bd42) | Aug 21, 2022 |
| Acer          | Aspire 5740                 | [19158f2e35](https://linux-hardware.org/?probe=19158f2e35) | Aug 21, 2022 |
| HP            | ENVY TS m6 Sleekbook        | [314250b1d7](https://linux-hardware.org/?probe=314250b1d7) | Aug 21, 2022 |
| MSI           | Katana GF76 11UD            | [256a057752](https://linux-hardware.org/?probe=256a057752) | Aug 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Vostro 15 3515              | [3f12b83029](https://linux-hardware.org/?probe=3f12b83029) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | GL703VD                     | [54f9d46a7d](https://linux-hardware.org/?probe=54f9d46a7d) | Aug 19, 2022 |
| Gateway       | NV55C                       | [377412b832](https://linux-hardware.org/?probe=377412b832) | Aug 18, 2022 |
| System76      | Oryx Pro                    | [1583fbab76](https://linux-hardware.org/?probe=1583fbab76) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| Acer          | Aspire A515-43              | [bec0e1fbd6](https://linux-hardware.org/?probe=bec0e1fbd6) | Aug 16, 2022 |
| Apple         | MacBookPro13,3              | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | UX310UQ                     | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [332459de48](https://linux-hardware.org/?probe=332459de48) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [b2c1b403b8](https://linux-hardware.org/?probe=b2c1b403b8) | Aug 14, 2022 |
| Acer          | Aspire 4752                 | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| MSI           | GF63 Thin 11UD              | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| Dell          | Latitude E7470              | [1c49732e63](https://linux-hardware.org/?probe=1c49732e63) | Aug 14, 2022 |
| Apple         | MacBookAir3,2               | [0756ed833b](https://linux-hardware.org/?probe=0756ed833b) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| ASUSTek       | G74Sx                       | [309312e25d](https://linux-hardware.org/?probe=309312e25d) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [da7cc3fcb6](https://linux-hardware.org/?probe=da7cc3fcb6) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| Dell          | Inspiron N5110              | [74624820da](https://linux-hardware.org/?probe=74624820da) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5e0a6f08b1](https://linux-hardware.org/?probe=5e0a6f08b1) | Aug 12, 2022 |
| Dell          | Inspiron 13-7378            | [097cd944e0](https://linux-hardware.org/?probe=097cd944e0) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [31a967ba05](https://linux-hardware.org/?probe=31a967ba05) | Aug 12, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ff6370169f](https://linux-hardware.org/?probe=ff6370169f) | Aug 11, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 1148      | 24.17%  |
| Pop!_OS 22.04 | 1140      | 24.01%  |
| Pop!_OS 21.04 | 959       | 20.19%  |
| Pop!_OS 20.10 | 856       | 18.02%  |
| Pop!_OS 21.10 | 599       | 12.61%  |
| Pop!_OS 19.10 | 30        | 0.63%   |
| Pop!_OS 18.04 | 7         | 0.15%   |
| Pop!_OS 19.04 | 6         | 0.13%   |
| Pop!_OS 18.10 | 4         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 4508      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 442       | 8.76%   |
| 5.8.0-7630-generic       | 381       | 7.55%   |
| 5.4.0-7634-generic       | 346       | 6.86%   |
| 5.19.0-76051900-generic  | 269       | 5.33%   |
| 5.13.0-7614-generic      | 262       | 5.19%   |
| 5.4.0-7642-generic       | 256       | 5.07%   |
| 5.17.5-76051705-generic  | 247       | 4.9%    |
| 5.8.0-7642-generic       | 242       | 4.8%    |
| 5.11.0-7614-generic      | 227       | 4.5%    |
| 5.13.0-7620-generic      | 218       | 4.32%   |
| 6.0.6-76060006-generic   | 159       | 3.15%   |
| 5.15.15-76051515-generic | 154       | 3.05%   |
| 6.0.12-76060006-generic  | 148       | 2.93%   |
| 5.16.11-76051611-generic | 138       | 2.74%   |
| 5.11.0-7612-generic      | 127       | 2.52%   |
| 5.15.5-76051505-generic  | 123       | 2.44%   |
| 5.18.10-76051810-generic | 118       | 2.34%   |
| 5.8.0-7625-generic       | 105       | 2.08%   |
| 5.17.15-76051715-generic | 105       | 2.08%   |
| 5.11.0-7633-generic      | 99        | 1.96%   |
| 5.15.8-76051508-generic  | 98        | 1.94%   |
| 5.16.19-76051619-generic | 95        | 1.88%   |
| 5.16.15-76051615-generic | 91        | 1.8%    |
| 5.4.0-7626-generic       | 84        | 1.67%   |
| 5.15.11-76051511-generic | 62        | 1.23%   |
| 6.0.2-76060002-generic   | 59        | 1.17%   |
| 5.15.23-76051523-generic | 56        | 1.11%   |
| 5.4.0-7625-generic       | 44        | 0.87%   |
| 5.4.0-7629-generic       | 35        | 0.69%   |
| 6.0.3-76060003-generic   | 23        | 0.46%   |
| 5.19.16-76051916-generic | 21        | 0.42%   |
| 5.3.0-7625-generic       | 10        | 0.2%    |
| 5.3.0-7648-generic       | 6         | 0.12%   |
| 5.11.0-051100-generic    | 6         | 0.12%   |
| 5.3.0-7642-generic       | 4         | 0.08%   |
| 5.3.0-7629-generic       | 4         | 0.08%   |
| 5.3.0-20-generic         | 4         | 0.08%   |
| 5.7.1-050701-generic     | 3         | 0.06%   |
| 4.18.0-16-generic        | 3         | 0.06%   |
| 5.9.12-xanmod1           | 2         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 873       | 17.66%  |
| 5.4.0   | 744       | 15.05%  |
| 5.8.0   | 698       | 14.12%  |
| 5.13.0  | 467       | 9.45%   |
| 5.19.0  | 271       | 5.48%   |
| 5.17.5  | 250       | 5.06%   |
| 6.0.6   | 159       | 3.22%   |
| 5.15.15 | 154       | 3.12%   |
| 6.0.12  | 148       | 2.99%   |
| 5.16.11 | 138       | 2.79%   |
| 5.15.5  | 123       | 2.49%   |
| 5.18.10 | 118       | 2.39%   |
| 5.17.15 | 105       | 2.12%   |
| 5.15.8  | 98        | 1.98%   |
| 5.16.19 | 95        | 1.92%   |
| 5.16.15 | 91        | 1.84%   |
| 5.15.11 | 62        | 1.25%   |
| 6.0.2   | 60        | 1.21%   |
| 5.15.23 | 56        | 1.13%   |
| 5.3.0   | 32        | 0.65%   |
| 6.0.3   | 23        | 0.47%   |
| 5.19.16 | 21        | 0.42%   |
| 5.0.0   | 6         | 0.12%   |
| 4.18.0  | 6         | 0.12%   |
| 5.7.0   | 4         | 0.08%   |
| 5.8.6   | 3         | 0.06%   |
| 5.8.11  | 3         | 0.06%   |
| 5.7.1   | 3         | 0.06%   |
| 5.15.0  | 3         | 0.06%   |
| 5.14.0  | 3         | 0.06%   |
| 5.12.14 | 3         | 0.06%   |
| 5.10.0  | 3         | 0.06%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |
| 5.9.12  | 2         | 0.04%   |
| 5.8.9   | 2         | 0.04%   |
| 5.8.1   | 2         | 0.04%   |
| 5.7.15  | 2         | 0.04%   |
| 5.6.7   | 2         | 0.04%   |
| 5.6.16  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 879       | 17.94%  |
| 5.4     | 745       | 15.21%  |
| 5.8     | 712       | 14.53%  |
| 5.15    | 492       | 10.04%  |
| 5.13    | 478       | 9.76%   |
| 6.0     | 381       | 7.78%   |
| 5.17    | 354       | 7.23%   |
| 5.16    | 322       | 6.57%   |
| 5.19    | 294       | 6%      |
| 5.18    | 122       | 2.49%   |
| 5.3     | 32        | 0.65%   |
| 5.10    | 18        | 0.37%   |
| 5.12    | 13        | 0.27%   |
| 5.7     | 11        | 0.22%   |
| 5.14    | 11        | 0.22%   |
| 5.9     | 9         | 0.18%   |
| 5.6     | 7         | 0.14%   |
| 4.18    | 7         | 0.14%   |
| 5.0     | 6         | 0.12%   |
| 6.1     | 3         | 0.06%   |
| 4.15    | 2         | 0.04%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4508      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4366      | 96.32%  |
| KDE5            | 39        | 0.86%   |
| Unknown         | 36        | 0.79%   |
| KDE             | 25        | 0.55%   |
| X-Cinnamon      | 16        | 0.35%   |
| GNOME Flashback | 10        | 0.22%   |
| XFCE            | 9         | 0.2%    |
| MATE            | 8         | 0.18%   |
| LXQt            | 8         | 0.18%   |
| Cinnamon        | 6         | 0.13%   |
| Unity           | 4         | 0.09%   |
| Budgie          | 4         | 0.09%   |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4363      | 96.31%  |
| Wayland | 146       | 3.22%   |
| Unknown | 14        | 0.31%   |
| Tty     | 7         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3450      | 75.69%  |
| GDM     | 772       | 16.94%  |
| GDM3    | 323       | 7.09%   |
| SDDM    | 7         | 0.15%   |
| TDM     | 5         | 0.11%   |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2600      | 57.32%  |
| pt_BR   | 341       | 7.52%   |
| en_GB   | 330       | 7.28%   |
| de_DE   | 188       | 4.14%   |
| C       | 111       | 2.45%   |
| it_IT   | 96        | 2.12%   |
| en_AU   | 95        | 2.09%   |
| es_ES   | 93        | 2.05%   |
| fr_FR   | 91        | 2.01%   |
| en_CA   | 83        | 1.83%   |
| ru_RU   | 62        | 1.37%   |
| Unknown | 48        | 1.06%   |
| pl_PL   | 39        | 0.86%   |
| pt_PT   | 38        | 0.84%   |
| sv_SE   | 30        | 0.66%   |
| en_IN   | 28        | 0.62%   |
| nl_NL   | 20        | 0.44%   |
| nb_NO   | 17        | 0.37%   |
| es_MX   | 17        | 0.37%   |
| en_ZA   | 17        | 0.37%   |
| fi_FI   | 15        | 0.33%   |
| tr_TR   | 12        | 0.26%   |
| fr_CA   | 11        | 0.24%   |
| es_AR   | 11        | 0.24%   |
| en_NZ   | 11        | 0.24%   |
| en_IE   | 10        | 0.22%   |
| hr_HR   | 8         | 0.18%   |
| en_DK   | 8         | 0.18%   |
| hu_HU   | 7         | 0.15%   |
| da_DK   | 7         | 0.15%   |
| cs_CZ   | 7         | 0.15%   |
| ro_RO   | 6         | 0.13%   |
| es_CL   | 6         | 0.13%   |
| de_CH   | 6         | 0.13%   |
| sk_SK   | 5         | 0.11%   |
| zh_CN   | 4         | 0.09%   |
| nl_BE   | 4         | 0.09%   |
| es_CO   | 4         | 0.09%   |
| en_IL   | 4         | 0.09%   |
| zh_TW   | 3         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3179      | 69.43%  |
| EFI  | 1400      | 30.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4322      | 95.58%  |
| Btrfs   | 110       | 2.43%   |
| Overlay | 65        | 1.44%   |
| Xfs     | 17        | 0.38%   |
| Unknown | 7         | 0.15%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3422      | 75.21%  |
| GPT     | 1026      | 22.55%  |
| MBR     | 102       | 2.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4410      | 97.54%  |
| Yes       | 111       | 2.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4113      | 90.81%  |
| Yes       | 416       | 9.19%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 867       | 19.23%  |
| Dell                   | 801       | 17.77%  |
| Hewlett-Packard        | 612       | 13.58%  |
| ASUSTek Computer       | 526       | 11.67%  |
| Acer                   | 360       | 7.99%   |
| Apple                  | 251       | 5.57%   |
| System76               | 169       | 3.75%   |
| MSI                    | 152       | 3.37%   |
| Toshiba                | 91        | 2.02%   |
| Samsung Electronics    | 82        | 1.82%   |
| HUAWEI                 | 54        | 1.2%    |
| Sony                   | 47        | 1.04%   |
| Notebook               | 42        | 0.93%   |
| Google                 | 34        | 0.75%   |
| Alienware              | 34        | 0.75%   |
| Fujitsu                | 27        | 0.6%    |
| Positivo               | 24        | 0.53%   |
| Razer                  | 21        | 0.47%   |
| Timi                   | 17        | 0.38%   |
| PC Specialist          | 16        | 0.35%   |
| Gigabyte Technology    | 16        | 0.35%   |
| LG Electronics         | 13        | 0.29%   |
| Framework              | 12        | 0.27%   |
| TUXEDO                 | 11        | 0.24%   |
| Medion                 | 11        | 0.24%   |
| GPU Company            | 11        | 0.24%   |
| Unknown                | 11        | 0.24%   |
| Avell High Performance | 10        | 0.22%   |
| Packard Bell           | 9         | 0.2%    |
| Eluktronics            | 7         | 0.16%   |
| Teclast                | 6         | 0.13%   |
| Panasonic              | 6         | 0.13%   |
| Intel                  | 6         | 0.13%   |
| Gateway                | 6         | 0.13%   |
| Clevo                  | 6         | 0.13%   |
| Chuwi                  | 5         | 0.11%   |
| SLIMBOOK               | 4         | 0.09%   |
| Schenker               | 4         | 0.09%   |
| Quanta                 | 4         | 0.09%   |
| MOTILE                 | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 42        | 0.93%   |
| System76 Lemur Pro                        | 37        | 0.82%   |
| Dell XPS 15 7590                          | 29        | 0.64%   |
| Apple MacBookPro9,2                       | 23        | 0.51%   |
| Unknown                                   | 23        | 0.51%   |
| System76 Gazelle                          | 22        | 0.49%   |
| System76 Galago Pro                       | 20        | 0.44%   |
| Dell XPS 15 9500                          | 20        | 0.44%   |
| HP Pavilion Notebook                      | 19        | 0.42%   |
| HP Notebook                               | 18        | 0.4%    |
| Apple MacBookPro12,1                      | 17        | 0.38%   |
| System76 Darter Pro                       | 16        | 0.35%   |
| Apple MacBookPro8,1                       | 16        | 0.35%   |
| HP Pavilion dv6                           | 15        | 0.33%   |
| HP Pavilion 15                            | 15        | 0.33%   |
| Dell XPS 15 9560                          | 14        | 0.31%   |
| Apple MacBookAir7,2                       | 14        | 0.31%   |
| Apple MacBookAir6,2                       | 14        | 0.31%   |
| Lenovo IdeaPad S145-15API 81V7            | 13        | 0.29%   |
| Dell Latitude E6420                       | 13        | 0.29%   |
| Apple MacBookPro7,1                       | 13        | 0.29%   |
| Dell XPS 15 9570                          | 12        | 0.27%   |
| Dell XPS 17 9700                          | 11        | 0.24%   |
| Dell XPS 13 9380                          | 11        | 0.24%   |
| Dell Latitude E7240                       | 11        | 0.24%   |
| Apple MacBookPro5,5                       | 11        | 0.24%   |
| Acer Aspire E5-575G                       | 11        | 0.24%   |
| HP Pavilion g6                            | 10        | 0.22%   |
| Framework Laptop                          | 10        | 0.22%   |
| Dell Inspiron N5110                       | 10        | 0.22%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 10        | 0.22%   |
| Samsung 340XAA/350XAA/550XAA              | 9         | 0.2%    |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 9         | 0.2%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY      | 9         | 0.2%    |
| Lenovo IdeaPad 330-15IKB 81FE             | 9         | 0.2%    |
| HP Pavilion Laptop 15-cw1xxx              | 9         | 0.2%    |
| Dell XPS 13 9310                          | 9         | 0.2%    |
| Dell Latitude E7470                       | 9         | 0.2%    |
| Dell Inspiron 3542                        | 9         | 0.2%    |
| Dell Inspiron 3521                        | 9         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 426       | 9.45%   |
| Dell Inspiron      | 263       | 5.83%   |
| Acer Aspire        | 248       | 5.5%    |
| Lenovo IdeaPad     | 238       | 5.28%   |
| Dell Latitude      | 191       | 4.24%   |
| Dell XPS           | 174       | 3.86%   |
| HP Pavilion        | 152       | 3.37%   |
| HP EliteBook       | 93        | 2.06%   |
| HP Laptop          | 88        | 1.95%   |
| ASUS VivoBook      | 80        | 1.77%   |
| Toshiba Satellite  | 79        | 1.75%   |
| ASUS ROG           | 75        | 1.66%   |
| HP ProBook         | 72        | 1.6%    |
| Lenovo Legion      | 65        | 1.44%   |
| Dell Precision     | 54        | 1.2%    |
| Dell Vostro        | 46        | 1.02%   |
| System76 Oryx      | 42        | 0.93%   |
| ASUS ASUS          | 42        | 0.93%   |
| Acer Nitro         | 42        | 0.93%   |
| System76 Lemur     | 40        | 0.89%   |
| HP ENVY            | 32        | 0.71%   |
| Acer Swift         | 32        | 0.71%   |
| ASUS TUF           | 30        | 0.67%   |
| Apple MacBookPro9  | 30        | 0.67%   |
| Apple MacBookPro11 | 29        | 0.64%   |
| HP OMEN            | 27        | 0.6%    |
| ASUS ZenBook       | 27        | 0.6%    |
| System76 Gazelle   | 24        | 0.53%   |
| Apple MacBookPro8  | 24        | 0.53%   |
| System76 Galago    | 23        | 0.51%   |
| Apple MacBookPro5  | 23        | 0.51%   |
| Unknown            | 23        | 0.51%   |
| Lenovo ThinkBook   | 22        | 0.49%   |
| Razer Blade        | 21        | 0.47%   |
| HP ZBook           | 21        | 0.47%   |
| Fujitsu LIFEBOOK   | 20        | 0.44%   |
| HP Notebook        | 18        | 0.4%    |
| Lenovo Yoga        | 17        | 0.38%   |
| Apple MacBookPro12 | 17        | 0.38%   |
| System76 Darter    | 16        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 591       | 13.11%  |
| 2020    | 547       | 12.13%  |
| 2021    | 450       | 9.98%   |
| 2018    | 429       | 9.52%   |
| 2012    | 335       | 7.43%   |
| 2013    | 290       | 6.43%   |
| 2017    | 283       | 6.28%   |
| 2011    | 272       | 6.03%   |
| 2015    | 269       | 5.97%   |
| 2016    | 249       | 5.52%   |
| 2014    | 222       | 4.92%   |
| 2010    | 186       | 4.13%   |
| 2022    | 117       | 2.6%    |
| 2009    | 113       | 2.51%   |
| 2008    | 106       | 2.35%   |
| 2007    | 36        | 0.8%    |
| 2006    | 9         | 0.2%    |
| Unknown | 2         | 0.04%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4508      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4505      | 99.93%  |
| Enabled  | 3         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4370      | 96.94%  |
| Yes  | 138       | 3.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1343      | 29.55%  |
| 16.01-24.0  | 1018      | 22.4%   |
| 8.01-16.0   | 838       | 18.44%  |
| 3.01-4.0    | 692       | 15.23%  |
| 32.01-64.0  | 411       | 9.04%   |
| 64.01-256.0 | 89        | 1.96%   |
| 1.01-2.0    | 66        | 1.45%   |
| 24.01-32.0  | 56        | 1.23%   |
| 2.01-3.0    | 32        | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1598      | 32.63%  |
| 1.01-2.0   | 1286      | 26.26%  |
| 3.01-4.0   | 902       | 18.42%  |
| 4.01-8.0   | 864       | 17.64%  |
| 8.01-16.0  | 206       | 4.21%   |
| 16.01-24.0 | 23        | 0.47%   |
| 0.51-1.0   | 10        | 0.2%    |
| 24.01-32.0 | 7         | 0.14%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3185      | 69.48%  |
| 2      | 1200      | 26.18%  |
| 3      | 148       | 3.23%   |
| 0      | 23        | 0.5%    |
| 4      | 19        | 0.41%   |
| 5      | 7         | 0.15%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3214      | 71.07%  |
| Yes       | 1308      | 28.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3605      | 79.6%   |
| No        | 924       | 20.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4458      | 98.83%  |
| No        | 53        | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3809      | 83.75%  |
| No        | 739       | 16.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1188      | 26.22%  |
| Brazil       | 474       | 10.46%  |
| Germany      | 269       | 5.94%   |
| UK           | 204       | 4.5%    |
| India        | 199       | 4.39%   |
| Canada       | 163       | 3.6%    |
| Italy        | 148       | 3.27%   |
| France       | 135       | 2.98%   |
| Australia    | 104       | 2.3%    |
| Netherlands  | 94        | 2.07%   |
| Russia       | 83        | 1.83%   |
| Sweden       | 77        | 1.7%    |
| Spain        | 73        | 1.61%   |
| Poland       | 66        | 1.46%   |
| Mexico       | 66        | 1.46%   |
| Portugal     | 63        | 1.39%   |
| Romania      | 54        | 1.19%   |
| Norway       | 47        | 1.04%   |
| Switzerland  | 46        | 1.02%   |
| South Africa | 43        | 0.95%   |
| Turkey       | 40        | 0.88%   |
| Greece       | 37        | 0.82%   |
| Finland      | 36        | 0.79%   |
| Philippines  | 35        | 0.77%   |
| Indonesia    | 35        | 0.77%   |
| Belgium      | 35        | 0.77%   |
| Argentina    | 35        | 0.77%   |
| Denmark      | 31        | 0.68%   |
| Austria      | 31        | 0.68%   |
| New Zealand  | 29        | 0.64%   |
| Chile        | 24        | 0.53%   |
| Croatia      | 22        | 0.49%   |
| Ireland      | 20        | 0.44%   |
| Hungary      | 20        | 0.44%   |
| Colombia     | 20        | 0.44%   |
| Bulgaria     | 20        | 0.44%   |
| Malaysia     | 19        | 0.42%   |
| Czechia      | 19        | 0.42%   |
| Vietnam      | 18        | 0.4%    |
| Japan        | 18        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 51        | 1.08%   |
| Bengaluru      | 30        | 0.64%   |
| Milan          | 29        | 0.61%   |
| Brisbane       | 27        | 0.57%   |
| Sydney         | 26        | 0.55%   |
| Rio de Janeiro | 24        | 0.51%   |
| London         | 23        | 0.49%   |
| Dallas         | 23        | 0.49%   |
| Paris          | 22        | 0.47%   |
| Vienna         | 21        | 0.44%   |
| Melbourne      | 21        | 0.44%   |
| Bucharest      | 21        | 0.44%   |
| Moscow         | 20        | 0.42%   |
| Berlin         | 20        | 0.42%   |
| Athens         | 20        | 0.42%   |
| Rome           | 19        | 0.4%    |
| New York       | 18        | 0.38%   |
| Istanbul       | 18        | 0.38%   |
| Helsinki       | 18        | 0.38%   |
| Amsterdam      | 18        | 0.38%   |
| Zagreb         | 17        | 0.36%   |
| Warsaw         | 17        | 0.36%   |
| Madrid         | 17        | 0.36%   |
| St Petersburg  | 15        | 0.32%   |
| Mexico City    | 15        | 0.32%   |
| Los Angeles    | 15        | 0.32%   |
| Johannesburg   | 15        | 0.32%   |
| Chicago        | 15        | 0.32%   |
| Zurich         | 14        | 0.3%    |
| Toronto        | 14        | 0.3%    |
| Stockholm      | 14        | 0.3%    |
| Sofia          | 14        | 0.3%    |
| Fortaleza      | 14        | 0.3%    |
| Brooklyn       | 14        | 0.3%    |
| Auckland       | 14        | 0.3%    |
| Singapore      | 13        | 0.28%   |
| Pune           | 13        | 0.28%   |
| Oslo           | 13        | 0.28%   |
| Hyderabad      | 13        | 0.28%   |
| Edmonton       | 13        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1051      | 1408   | 18.13%  |
| WDC                            | 623       | 711    | 10.75%  |
| Seagate                        | 582       | 685    | 10.04%  |
| Sandisk                        | 417       | 543    | 7.19%   |
| Toshiba                        | 378       | 444    | 6.52%   |
| Kingston                       | 310       | 368    | 5.35%   |
| SK hynix                       | 274       | 354    | 4.73%   |
| Unknown                        | 272       | 332    | 4.69%   |
| Crucial                        | 207       | 239    | 3.57%   |
| Intel                          | 188       | 234    | 3.24%   |
| HGST                           | 171       | 196    | 2.95%   |
| Micron Technology              | 152       | 167    | 2.62%   |
| Apple                          | 120       | 127    | 2.07%   |
| Hitachi                        | 93        | 102    | 1.6%    |
| A-DATA Technology              | 88        | 106    | 1.52%   |
| Phison                         | 73        | 90     | 1.26%   |
| PNY                            | 44        | 52     | 0.76%   |
| China                          | 43        | 48     | 0.74%   |
| LITEON                         | 41        | 47     | 0.71%   |
| KIOXIA                         | 40        | 47     | 0.69%   |
| Silicon Motion                 | 38        | 46     | 0.66%   |
| Micron/Crucial Technology      | 34        | 45     | 0.59%   |
| Transcend                      | 30        | 35     | 0.52%   |
| LITEONIT                       | 28        | 36     | 0.48%   |
| ADATA Technology               | 21        | 30     | 0.36%   |
| Fujitsu                        | 18        | 19     | 0.31%   |
| Team                           | 17        | 21     | 0.29%   |
| SPCC                           | 17        | 18     | 0.29%   |
| JMicron Technology             | 16        | 22     | 0.28%   |
| Union Memory (Shenzhen)        | 15        | 18     | 0.26%   |
| KingSpec                       | 15        | 17     | 0.26%   |
| Solid State Storage Technology | 12        | 15     | 0.21%   |
| Patriot                        | 12        | 13     | 0.21%   |
| OCZ                            | 12        | 12     | 0.21%   |
| Netac                          | 12        | 13     | 0.21%   |
| Hewlett-Packard                | 12        | 14     | 0.21%   |
| Corsair                        | 12        | 14     | 0.21%   |
| Phison Electronics             | 11        | 13     | 0.19%   |
| Lexar                          | 10        | 10     | 0.17%   |
| Intenso                        | 10        | 10     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 99        | 1.63%   |
| Kingston SA400S37240G 240GB SSD        | 83        | 1.36%   |
| Samsung NVMe SSD Drive 512GB           | 80        | 1.32%   |
| HGST HTS721010A9E630 1TB               | 73        | 1.2%    |
| Unknown MMC Card  64GB                 | 66        | 1.09%   |
| Samsung NVMe SSD Drive 1TB             | 64        | 1.05%   |
| SK hynix NVMe SSD Drive 512GB          | 59        | 0.97%   |
| Toshiba MQ01ABD100 1TB                 | 58        | 0.95%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 57        | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 53        | 0.87%   |
| SanDisk NVMe SSD Drive 512GB           | 52        | 0.86%   |
| Samsung NVMe SSD Drive 500GB           | 52        | 0.86%   |
| Unknown MMC Card  32GB                 | 47        | 0.77%   |
| Intel NVMe SSD Drive 512GB             | 47        | 0.77%   |
| Toshiba MQ04ABF100 1TB                 | 43        | 0.71%   |
| Samsung NVMe SSD Drive 1024GB          | 40        | 0.66%   |
| WDC WD10SPZX-24Z10 1TB                 | 39        | 0.64%   |
| Seagate ST9500325AS 500GB              | 36        | 0.59%   |
| SanDisk NVMe SSD Drive 1TB             | 36        | 0.59%   |
| Seagate ST1000LM049-2GH172 1TB         | 35        | 0.58%   |
| SanDisk NVMe SSD Drive 256GB           | 35        | 0.58%   |
| Samsung SSD 860 EVO 500GB              | 33        | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB               | 32        | 0.53%   |
| SK hynix NVMe SSD Drive 1024GB         | 31        | 0.51%   |
| Samsung SSD 850 EVO 250GB              | 31        | 0.51%   |
| Kingston SA400S37480G 480GB SSD        | 31        | 0.51%   |
| Crucial CT500MX500SSD1 500GB           | 30        | 0.49%   |
| SK hynix NVMe SSD Drive 256GB          | 29        | 0.48%   |
| SanDisk NVMe SSD Drive 500GB           | 29        | 0.48%   |
| Unknown MMC Card  128GB                | 28        | 0.46%   |
| Toshiba NVMe SSD Drive 512GB           | 28        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB        | 28        | 0.46%   |
| Crucial CT240BX500SSD1 240GB           | 28        | 0.46%   |
| Kingston SA400S37120G 120GB SSD        | 27        | 0.44%   |
| HGST HTS541010A9E680 1TB               | 27        | 0.44%   |
| Samsung SSD 860 EVO 1TB                | 26        | 0.43%   |
| Samsung NVMe SSD Drive 2TB             | 26        | 0.43%   |
| Micron NVMe SSD Drive 512GB            | 26        | 0.43%   |
| Seagate Expansion 240GB                | 25        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB           | 24        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 558       | 645    | 36.14%  |
| WDC                 | 383       | 420    | 24.81%  |
| Toshiba             | 232       | 261    | 15.03%  |
| HGST                | 171       | 196    | 11.08%  |
| Hitachi             | 93        | 102    | 6.02%   |
| Samsung Electronics | 29        | 30     | 1.88%   |
| Unknown             | 24        | 26     | 1.55%   |
| Fujitsu             | 18        | 19     | 1.17%   |
| Apple               | 15        | 15     | 0.97%   |
| SABRENT             | 5         | 6      | 0.32%   |
| ASMT                | 5         | 6      | 0.32%   |
| Intenso             | 3         | 3      | 0.19%   |
| JMicron Technology  | 2         | 5      | 0.13%   |
| USB3.0              | 1         | 1      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 431       | 563    | 21.71%  |
| Kingston            | 240       | 271    | 12.09%  |
| SanDisk             | 205       | 249    | 10.33%  |
| Crucial             | 192       | 224    | 9.67%   |
| WDC                 | 129       | 157    | 6.5%    |
| Apple               | 89        | 93     | 4.48%   |
| A-DATA Technology   | 58        | 69     | 2.92%   |
| Micron Technology   | 50        | 53     | 2.52%   |
| SK hynix            | 49        | 58     | 2.47%   |
| Toshiba             | 48        | 58     | 2.42%   |
| PNY                 | 43        | 51     | 2.17%   |
| China               | 42        | 47     | 2.12%   |
| Intel               | 40        | 43     | 2.02%   |
| LITEON              | 39        | 45     | 1.96%   |
| Transcend           | 29        | 34     | 1.46%   |
| LITEONIT            | 28        | 36     | 1.41%   |
| SPCC                | 15        | 16     | 0.76%   |
| Seagate             | 14        | 15     | 0.71%   |
| KingSpec            | 14        | 16     | 0.71%   |
| Patriot             | 12        | 13     | 0.6%    |
| OCZ                 | 12        | 12     | 0.6%    |
| Team                | 11        | 15     | 0.55%   |
| Netac               | 10        | 11     | 0.5%    |
| Lexar               | 9         | 9      | 0.45%   |
| JMicron Technology  | 9         | 10     | 0.45%   |
| Hewlett-Packard     | 9         | 11     | 0.45%   |
| Corsair             | 9         | 10     | 0.45%   |
| KingDian            | 7         | 8      | 0.35%   |
| Intenso             | 6         | 6      | 0.3%    |
| Dogfish             | 6         | 8      | 0.3%    |
| BHT                 | 6         | 6      | 0.3%    |
| Apacer              | 6         | 10     | 0.3%    |
| TO Exter            | 5         | 5      | 0.25%   |
| Plextor             | 5         | 7      | 0.25%   |
| GOODRAM             | 5         | 6      | 0.25%   |
| Mushkin             | 4         | 4      | 0.2%    |
| Maxtor              | 4         | 4      | 0.2%    |
| Gigabyte Technology | 4         | 6      | 0.2%    |
| FORESEE             | 4         | 5      | 0.2%    |
| Unknown             | 3         | 3      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1855      | 2581   | 33.78%  |
| SSD     | 1848      | 2354   | 33.66%  |
| HDD     | 1495      | 1743   | 27.23%  |
| MMC     | 221       | 267    | 4.02%   |
| Unknown | 72        | 94     | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2921      | 3940   | 56.24%  |
| NVMe | 1852      | 2575   | 35.66%  |
| MMC  | 221       | 267    | 4.25%   |
| SAS  | 200       | 257    | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2114      | 2712   | 64.27%  |
| 0.51-1.0   | 1059      | 1236   | 32.2%   |
| 1.01-2.0   | 97        | 124    | 2.95%   |
| 4.01-10.0  | 10        | 15     | 0.3%    |
| 3.01-4.0   | 6         | 6      | 0.18%   |
| 10.01-20.0 | 2         | 3      | 0.06%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1577      | 33.94%  |
| 251-500        | 1314      | 28.28%  |
| 501-1000       | 846       | 18.21%  |
| 1001-2000      | 313       | 6.74%   |
| 51-100         | 237       | 5.1%    |
| 21-50          | 115       | 2.47%   |
| 1-20           | 106       | 2.28%   |
| 2001-3000      | 63        | 1.36%   |
| More than 3000 | 48        | 1.03%   |
| Unknown        | 28        | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1951      | 40.04%  |
| 21-50          | 1055      | 21.65%  |
| 101-250        | 636       | 13.05%  |
| 51-100         | 623       | 12.78%  |
| 251-500        | 322       | 6.61%   |
| 501-1000       | 172       | 3.53%   |
| 1001-2000      | 59        | 1.21%   |
| Unknown        | 28        | 0.57%   |
| More than 3000 | 15        | 0.31%   |
| 2001-3000      | 12        | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 5         | 8      | 4.63%   |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 3.7%    |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.78%   |
| Seagate ST1000LX015-1U7172 1TB           | 3         | 3      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.78%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.78%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.78%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.85%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.85%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.85%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.85%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.85%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.93%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.93%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.93%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.93%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.93%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.93%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.93%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.93%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.93%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.93%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.93%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.93%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.93%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 0.93%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.93%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.93%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 0.93%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.93%   |
| Toshiba MK5059GSXP 500GB                 | 1         | 1      | 0.93%   |
| Toshiba MK2035GSS 200GB                  | 1         | 1      | 0.93%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 0.93%   |
| Team TM8FP4004T 4TB                      | 1         | 1      | 0.93%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 26     | 23.15%  |
| WDC                 | 16        | 16     | 14.81%  |
| HGST                | 12        | 15     | 11.11%  |
| Toshiba             | 10        | 11     | 9.26%   |
| SK hynix            | 6         | 8      | 5.56%   |
| Samsung Electronics | 6         | 6      | 5.56%   |
| Hitachi             | 6         | 8      | 5.56%   |
| Crucial             | 5         | 5      | 4.63%   |
| A-DATA Technology   | 5         | 5      | 4.63%   |
| Micron Technology   | 4         | 4      | 3.7%    |
| Kingston            | 4         | 4      | 3.7%    |
| Intel               | 3         | 3      | 2.78%   |
| SanDisk             | 2         | 2      | 1.85%   |
| Team                | 1         | 1      | 0.93%   |
| Lexar               | 1         | 1      | 0.93%   |
| Leven               | 1         | 1      | 0.93%   |
| China               | 1         | 1      | 0.93%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 26     | 38.46%  |
| WDC     | 14        | 14     | 21.54%  |
| HGST    | 12        | 15     | 18.46%  |
| Toshiba | 8         | 8      | 12.31%  |
| Hitachi | 6         | 8      | 9.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 71     | 60.19%  |
| SSD  | 28        | 31     | 25.93%  |
| NVMe | 15        | 15     | 13.89%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3490      | 5424   | 74.02%  |
| Works    | 1116      | 1497   | 23.67%  |
| Malfunc  | 108       | 117    | 2.29%   |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3052      | 54.07%  |
| Samsung Electronics              | 683       | 12.1%   |
| AMD                              | 573       | 10.15%  |
| SanDisk                          | 317       | 5.62%   |
| SK hynix                         | 224       | 3.97%   |
| Toshiba America Info Systems     | 106       | 1.88%   |
| Micron Technology                | 102       | 1.81%   |
| Phison Electronics               | 86        | 1.52%   |
| Kingston Technology Company      | 74        | 1.31%   |
| Nvidia                           | 72        | 1.28%   |
| ADATA Technology                 | 52        | 0.92%   |
| Silicon Motion                   | 45        | 0.8%    |
| Micron/Crucial Technology        | 45        | 0.8%    |
| KIOXIA                           | 43        | 0.76%   |
| Solid State Storage Technology   | 31        | 0.55%   |
| Union Memory (Shenzhen)          | 30        | 0.53%   |
| Realtek Semiconductor            | 17        | 0.3%    |
| Marvell Technology Group         | 17        | 0.3%    |
| Apple                            | 16        | 0.28%   |
| Seagate Technology               | 11        | 0.19%   |
| Silicon Integrated Systems [SiS] | 8         | 0.14%   |
| Shenzhen Longsys Electronics     | 8         | 0.14%   |
| Lite-On Technology               | 7         | 0.12%   |
| Lenovo                           | 6         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| JMicron Technology               | 4         | 0.07%   |
| ASMedia Technology               | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 543       | 9.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 377       | 6.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 367       | 6.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 321       | 5.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 292       | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 248       | 4.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 230       | 3.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 188       | 3.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 147       | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 131       | 2.22%   |
| Intel Volume Management Device NVMe RAID Controller                            | 123       | 2.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 109       | 1.84%   |
| Samsung NVMe SSD Controller 980                                                | 105       | 1.78%   |
| Micron Non-Volatile memory controller                                          | 102       | 1.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 97        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 93        | 1.57%   |
| Intel SSD 660P Series                                                          | 87        | 1.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 86        | 1.45%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 84        | 1.42%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 83        | 1.4%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 81        | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 77        | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 72        | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 67        | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 1.08%   |
| SanDisk Non-Volatile memory controller                                         | 60        | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 50        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 48        | 0.81%   |
| Phison E12 NVMe Controller                                                     | 48        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 48        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 48        | 0.81%   |
| SK hynix Non-Volatile memory controller                                        | 46        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 42        | 0.71%   |
| Nvidia MCP79 AHCI Controller                                                   | 41        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 41        | 0.69%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 40        | 0.68%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 39        | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 38        | 0.64%   |
| Samsung Electronics SATA controller                                            | 38        | 0.64%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 33        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3224      | 56.91%  |
| NVMe | 1850      | 32.66%  |
| RAID | 437       | 7.71%   |
| IDE  | 154       | 2.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3673      | 81.48%  |
| AMD    | 835       | 18.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 115       | 2.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 92        | 2.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 89        | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 83        | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 80        | 1.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 70        | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 67        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 64        | 1.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 63        | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 63        | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 63        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 60        | 1.33%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 55        | 1.22%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 55        | 1.22%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 1.13%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 50        | 1.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 44        | 0.98%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 39        | 0.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 39        | 0.86%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 38        | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 37        | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 37        | 0.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 36        | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 34        | 0.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 34        | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 33        | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 32        | 0.71%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 31        | 0.69%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 31        | 0.69%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 30        | 0.67%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 29        | 0.64%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 29        | 0.64%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 29        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 28        | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 28        | 0.62%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 27        | 0.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1348      | 29.9%   |
| Intel Core i5           | 1158      | 25.69%  |
| Other                   | 351       | 7.79%   |
| Intel Core i3           | 283       | 6.28%   |
| AMD Ryzen 5             | 233       | 5.17%   |
| AMD Ryzen 7             | 228       | 5.06%   |
| Intel Core 2 Duo        | 166       | 3.68%   |
| Intel Celeron           | 145       | 3.22%   |
| AMD Ryzen 3             | 55        | 1.22%   |
| Intel Pentium           | 54        | 1.2%    |
| AMD Ryzen 9             | 52        | 1.15%   |
| Intel Core i9           | 48        | 1.06%   |
| AMD A6                  | 48        | 1.06%   |
| AMD A8                  | 32        | 0.71%   |
| Intel Pentium Dual-Core | 31        | 0.69%   |
| AMD A10                 | 29        | 0.64%   |
| AMD Ryzen 7 PRO         | 26        | 0.58%   |
| AMD A4                  | 24        | 0.53%   |
| Intel Atom              | 19        | 0.42%   |
| Intel Core 2            | 16        | 0.35%   |
| Intel Xeon              | 13        | 0.29%   |
| Intel Pentium Dual      | 13        | 0.29%   |
| Intel Genuine           | 13        | 0.29%   |
| Intel Core m3           | 12        | 0.27%   |
| AMD E1                  | 11        | 0.24%   |
| AMD Athlon              | 10        | 0.22%   |
| AMD Ryzen 5 PRO         | 9         | 0.2%    |
| AMD E                   | 8         | 0.18%   |
| AMD E2                  | 7         | 0.16%   |
| AMD Turion 64 X2 Mobile | 6         | 0.13%   |
| AMD FX                  | 6         | 0.13%   |
| AMD A12                 | 6         | 0.13%   |
| Intel Core M            | 5         | 0.11%   |
| Intel Pentium Silver    | 4         | 0.09%   |
| Intel Celeron Dual-Core | 4         | 0.09%   |
| AMD C-60                | 4         | 0.09%   |
| Intel Core m5           | 3         | 0.07%   |
| AMD Phenom II           | 3         | 0.07%   |
| AMD Athlon X2           | 3         | 0.07%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1961      | 43.5%   |
| 4      | 1592      | 35.31%  |
| 6      | 460       | 10.2%   |
| 8      | 402       | 8.92%   |
| 14     | 33        | 0.73%   |
| 1      | 23        | 0.51%   |
| 12     | 19        | 0.42%   |
| 10     | 13        | 0.29%   |
| 16     | 2         | 0.04%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4508      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3768      | 83.55%  |
| 1      | 742       | 16.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4501      | 99.84%  |
| Unknown        | 7         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2879      | 62.29%  |
| 0x906ea    | 149       | 3.22%   |
| 0x806ea    | 104       | 2.25%   |
| 0x806ec    | 98        | 2.12%   |
| 0x306a9    | 98        | 2.12%   |
| 0x206a7    | 90        | 1.95%   |
| 0x806c1    | 88        | 1.9%    |
| 0x406e3    | 84        | 1.82%   |
| 0x40651    | 78        | 1.69%   |
| 0xa0652    | 73        | 1.58%   |
| 0x806e9    | 58        | 1.25%   |
| 0x306c3    | 56        | 1.21%   |
| 0x906e9    | 53        | 1.15%   |
| 0x0a50000c | 44        | 0.95%   |
| 0x08108102 | 44        | 0.95%   |
| 0x306d4    | 37        | 0.8%    |
| 0x806d1    | 36        | 0.78%   |
| 0x806eb    | 34        | 0.74%   |
| 0x506e3    | 34        | 0.74%   |
| 0x1067a    | 33        | 0.71%   |
| 0x08600106 | 32        | 0.69%   |
| 0x906ed    | 27        | 0.58%   |
| 0x08108109 | 27        | 0.58%   |
| 0x08600104 | 23        | 0.5%    |
| 0x906a3    | 22        | 0.48%   |
| 0x20655    | 22        | 0.48%   |
| 0x706e5    | 20        | 0.43%   |
| 0x08608103 | 17        | 0.37%   |
| 0x08600103 | 17        | 0.37%   |
| 0x06006705 | 17        | 0.37%   |
| 0x0810100b | 15        | 0.32%   |
| 0x706a1    | 13        | 0.28%   |
| 0x40661    | 11        | 0.24%   |
| 0x10676    | 11        | 0.24%   |
| 0x07030105 | 10        | 0.22%   |
| 0xa0660    | 9         | 0.19%   |
| 0x0a404101 | 8         | 0.17%   |
| 0x08600102 | 8         | 0.17%   |
| 0x06001119 | 8         | 0.17%   |
| 0x406c4    | 7         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1075      | 23.83%  |
| Haswell          | 404       | 8.96%   |
| SandyBridge      | 324       | 7.18%   |
| IvyBridge        | 322       | 7.14%   |
| Skylake          | 264       | 5.85%   |
| TigerLake        | 204       | 4.52%   |
| Zen+             | 185       | 4.1%    |
| CometLake        | 180       | 3.99%   |
| Penryn           | 179       | 3.97%   |
| Zen 2            | 174       | 3.86%   |
| Unknown          | 161       | 3.57%   |
| Broadwell        | 157       | 3.48%   |
| Westmere         | 139       | 3.08%   |
| Zen 3            | 130       | 2.88%   |
| Icelake          | 87        | 1.93%   |
| Silvermont       | 74        | 1.64%   |
| Core             | 71        | 1.57%   |
| Excavator        | 63        | 1.4%    |
| Zen              | 47        | 1.04%   |
| Goldmont plus    | 47        | 1.04%   |
| Puma             | 39        | 0.86%   |
| Piledriver       | 34        | 0.75%   |
| Alderlake Hybrid | 25        | 0.55%   |
| Bobcat           | 21        | 0.47%   |
| Goldmont         | 20        | 0.44%   |
| Nehalem          | 16        | 0.35%   |
| Jaguar           | 13        | 0.29%   |
| Steamroller      | 12        | 0.27%   |
| K10 Llano        | 12        | 0.27%   |
| K8 Hammer        | 11        | 0.24%   |
| K10              | 9         | 0.2%    |
| K8 & K10 hybrid  | 7         | 0.16%   |
| Bonnell          | 4         | 0.09%   |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3329      | 55.21%  |
| Nvidia                           | 1637      | 27.15%  |
| AMD                              | 1057      | 17.53%  |
| Silicon Integrated Systems [SiS] | 6         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 307       | 4.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 296       | 4.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 296       | 4.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 226       | 3.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 192       | 3.11%   |
| Intel UHD Graphics 620                                                                   | 188       | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 185       | 3%      |
| AMD Renoir                                                                               | 165       | 2.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 163       | 2.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 151       | 2.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 141       | 2.28%   |
| Intel HD Graphics 620                                                                    | 132       | 2.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 131       | 2.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 117       | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 116       | 1.88%   |
| Intel HD Graphics 630                                                                    | 113       | 1.83%   |
| Intel HD Graphics 5500                                                                   | 111       | 1.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 110       | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 105       | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 80        | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 76        | 1.23%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 72        | 1.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 68        | 1.1%    |
| Intel HD Graphics 530                                                                    | 66        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 62        | 1%      |
| AMD Lucienne                                                                             | 58        | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 55        | 0.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 55        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 52        | 0.84%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 51        | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                            | 49        | 0.79%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 49        | 0.79%   |
| Nvidia TU117M                                                                            | 48        | 0.78%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 48        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 45        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 43        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 43        | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 36        | 0.58%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 35        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2034      | 44.81%  |
| Intel + Nvidia     | 1131      | 24.92%  |
| 1 x AMD            | 607       | 13.37%  |
| 1 x Nvidia         | 299       | 6.59%   |
| AMD + Nvidia       | 186       | 4.1%    |
| Intel + AMD        | 174       | 3.83%   |
| 2 x AMD            | 91        | 2%      |
| 2 x Nvidia         | 9         | 0.2%    |
| 1 x SiS            | 6         | 0.13%   |
| 1 x S3 Graphics    | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3118      | 68.54%  |
| Proprietary | 1306      | 28.71%  |
| Unknown     | 125       | 2.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3372      | 73.46%  |
| 1.01-2.0   | 325       | 7.08%   |
| 3.01-4.0   | 306       | 6.67%   |
| 5.01-6.0   | 180       | 3.92%   |
| 0.01-0.5   | 176       | 3.83%   |
| 7.01-8.0   | 101       | 2.2%    |
| 0.51-1.0   | 89        | 1.94%   |
| 2.01-3.0   | 29        | 0.63%   |
| 8.01-16.0  | 12        | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 950       | 18.06%  |
| Chimei Innolux          | 756       | 14.37%  |
| LG Display              | 747       | 14.2%   |
| BOE                     | 666       | 12.66%  |
| Samsung Electronics     | 485       | 9.22%   |
| Apple                   | 211       | 4.01%   |
| Sharp                   | 193       | 3.67%   |
| Goldstar                | 162       | 3.08%   |
| Dell                    | 153       | 2.91%   |
| PANDA                   | 134       | 2.55%   |
| Chi Mei Optoelectronics | 82        | 1.56%   |
| Lenovo                  | 69        | 1.31%   |
| AOC                     | 55        | 1.05%   |
| Acer                    | 55        | 1.05%   |
| Hewlett-Packard         | 52        | 0.99%   |
| Philips                 | 43        | 0.82%   |
| BenQ                    | 43        | 0.82%   |
| InfoVision              | 40        | 0.76%   |
| Ancor Communications    | 33        | 0.63%   |
| ASUSTek Computer        | 28        | 0.53%   |
| CSO                     | 26        | 0.49%   |
| ViewSonic               | 19        | 0.36%   |
| TMX                     | 14        | 0.27%   |
| Sony                    | 14        | 0.27%   |
| LG Philips              | 14        | 0.27%   |
| Panasonic               | 12        | 0.23%   |
| Vizio                   | 11        | 0.21%   |
| InnoLux Display         | 10        | 0.19%   |
| Toshiba                 | 8         | 0.15%   |
| Sceptre Tech            | 8         | 0.15%   |
| Iiyama                  | 8         | 0.15%   |
| JDI                     | 7         | 0.13%   |
| MSI                     | 6         | 0.11%   |
| Vestel Elektronik       | 5         | 0.1%    |
| LGD                     | 5         | 0.1%    |
| Insignia                | 4         | 0.08%   |
| Hitachi                 | 4         | 0.08%   |
| HannStar                | 4         | 0.08%   |
| Eizo                    | 4         | 0.08%   |
| CPT                     | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 55        | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 50        | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 43        | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 43        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 39        | 0.73%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 38        | 0.71%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 33        | 0.62%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 33        | 0.62%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 25        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 25        | 0.47%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 24        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 24        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 24        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 24        | 0.45%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 24        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 23        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 22        | 0.41%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 20        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 20        | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 20        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 19        | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 19        | 0.36%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 18        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 18        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 18        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 17        | 0.32%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 16        | 0.3%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 15        | 0.28%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 15        | 0.28%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 15        | 0.28%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 15        | 0.28%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 14        | 0.26%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 14        | 0.26%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x193mm 15.5-inch        | 14        | 0.26%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch        | 14        | 0.26%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                | 14        | 0.26%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 14        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2319      | 47.1%   |
| 1366x768 (WXGA)    | 1264      | 25.67%  |
| 3840x2160 (4K)     | 249       | 5.06%   |
| 1600x900 (HD+)     | 210       | 4.26%   |
| 2560x1440 (QHD)    | 158       | 3.21%   |
| 1280x800 (WXGA)    | 117       | 2.38%   |
| 1920x1200 (WUXGA)  | 97        | 1.97%   |
| 1440x900 (WXGA+)   | 91        | 1.85%   |
| 2560x1600          | 68        | 1.38%   |
| 2880x1800          | 52        | 1.06%   |
| 2560x1080          | 43        | 0.87%   |
| 3840x2400          | 31        | 0.63%   |
| 3440x1440          | 30        | 0.61%   |
| 1680x1050 (WSXGA+) | 28        | 0.57%   |
| 2160x1440          | 18        | 0.37%   |
| 3200x1800 (QHD+)   | 17        | 0.35%   |
| 1360x768           | 17        | 0.35%   |
| 2256x1504          | 14        | 0.28%   |
| 1920x540           | 13        | 0.26%   |
| 1280x1024 (SXGA)   | 12        | 0.24%   |
| 3000x2000          | 10        | 0.2%    |
| 3840x1080          | 9         | 0.18%   |
| 3456x2160          | 6         | 0.12%   |
| 3200x2000          | 6         | 0.12%   |
| Unknown            | 6         | 0.12%   |
| 3840x1100          | 3         | 0.06%   |
| 3072x1920          | 3         | 0.06%   |
| 2560x1700          | 3         | 0.06%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 2304x1440          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x768 (XGA)     | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |
| 7680x2160          | 1         | 0.02%   |
| 5120x1080          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2234      | 42.49%  |
| 13      | 806       | 15.33%  |
| 14      | 579       | 11.01%  |
| 17      | 388       | 7.38%   |
| 27      | 175       | 3.33%   |
| 24      | 151       | 2.87%   |
| 23      | 139       | 2.64%   |
| 12      | 112       | 2.13%   |
| 21      | 96        | 1.83%   |
| 31      | 81        | 1.54%   |
| 16      | 64        | 1.22%   |
| 34      | 63        | 1.2%    |
| 11      | 63        | 1.2%    |
| 18      | 46        | 0.87%   |
| Unknown | 42        | 0.8%    |
| 19      | 30        | 0.57%   |
| 32      | 19        | 0.36%   |
| 84      | 18        | 0.34%   |
| 20      | 17        | 0.32%   |
| 72      | 15        | 0.29%   |
| 40      | 15        | 0.29%   |
| 22      | 13        | 0.25%   |
| 48      | 10        | 0.19%   |
| 54      | 9         | 0.17%   |
| 25      | 8         | 0.15%   |
| 26      | 6         | 0.11%   |
| 52      | 5         | 0.1%    |
| 35      | 5         | 0.1%    |
| 28      | 5         | 0.1%    |
| 10      | 5         | 0.1%    |
| 65      | 4         | 0.08%   |
| 49      | 4         | 0.08%   |
| 46      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 29      | 4         | 0.08%   |
| 47      | 3         | 0.06%   |
| 37      | 3         | 0.06%   |
| 99      | 1         | 0.02%   |
| 69      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3212      | 61.54%  |
| 201-300        | 570       | 10.92%  |
| 351-400        | 470       | 9.01%   |
| 501-600        | 424       | 8.12%   |
| 401-500        | 194       | 3.72%   |
| 601-700        | 114       | 2.18%   |
| 701-800        | 86        | 1.65%   |
| 1001-1500      | 42        | 0.8%    |
| Unknown        | 42        | 0.8%    |
| 1501-2000      | 34        | 0.65%   |
| 801-900        | 25        | 0.48%   |
| 901-1000       | 3         | 0.06%   |
| More than 2000 | 1         | 0.02%   |
| 101-200        | 1         | 0.02%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3864      | 84.77%  |
| 16/10   | 498       | 10.93%  |
| 21/9    | 75        | 1.65%   |
| 3/2     | 54        | 1.18%   |
| Unknown | 23        | 0.5%    |
| 5/4     | 15        | 0.33%   |
| 32/9    | 10        | 0.22%   |
| 4/3     | 8         | 0.18%   |
| 3.40    | 3         | 0.07%   |
| 3.73    | 2         | 0.04%   |
| 0.62    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2246      | 42.8%   |
| 81-90          | 1118      | 21.3%   |
| 121-130        | 362       | 6.9%    |
| 201-250        | 332       | 6.33%   |
| 71-80          | 265       | 5.05%   |
| 301-350        | 179       | 3.41%   |
| 351-500        | 171       | 3.26%   |
| 61-70          | 105       | 2%      |
| 151-200        | 69        | 1.31%   |
| 51-60          | 66        | 1.26%   |
| More than 1000 | 62        | 1.18%   |
| 251-300        | 56        | 1.07%   |
| 141-150        | 49        | 0.93%   |
| 111-120        | 47        | 0.9%    |
| Unknown        | 42        | 0.8%    |
| 501-1000       | 41        | 0.78%   |
| 131-140        | 23        | 0.44%   |
| 91-100         | 8         | 0.15%   |
| 41-50          | 5         | 0.1%    |
| 1-40           | 2         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2256      | 43.93%  |
| 101-120       | 1439      | 28.02%  |
| 51-100        | 722       | 14.06%  |
| 161-240       | 388       | 7.55%   |
| More than 240 | 222       | 4.32%   |
| 1-50          | 67        | 1.3%    |
| Unknown       | 42        | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3563      | 77.27%  |
| 2     | 794       | 17.22%  |
| 0     | 157       | 3.4%    |
| 3     | 91        | 1.97%   |
| 4     | 6         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2467      | 33.75%  |
| Intel                             | 2421      | 33.12%  |
| Qualcomm Atheros                  | 1031      | 14.1%   |
| Broadcom                          | 499       | 6.83%   |
| Broadcom Limited                  | 143       | 1.96%   |
| MediaTek                          | 104       | 1.42%   |
| Marvell Technology Group          | 63        | 0.86%   |
| Nvidia                            | 51        | 0.7%    |
| Ralink                            | 49        | 0.67%   |
| TP-Link                           | 48        | 0.66%   |
| ASIX Electronics                  | 46        | 0.63%   |
| Ralink Technology                 | 38        | 0.52%   |
| Samsung Electronics               | 34        | 0.47%   |
| DisplayLink                       | 28        | 0.38%   |
| Dell                              | 23        | 0.31%   |
| Lenovo                            | 22        | 0.3%    |
| Ericsson Business Mobile Networks | 20        | 0.27%   |
| Sierra Wireless                   | 19        | 0.26%   |
| Qualcomm                          | 17        | 0.23%   |
| Xiaomi                            | 16        | 0.22%   |
| JMicron Technology                | 16        | 0.22%   |
| Google                            | 13        | 0.18%   |
| Hewlett-Packard                   | 12        | 0.16%   |
| NetGear                           | 11        | 0.15%   |
| ASUSTek Computer                  | 11        | 0.15%   |
| Huawei Technologies               | 10        | 0.14%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.12%   |
| D-Link                            | 9         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.11%   |
| Motorola PCS                      | 8         | 0.11%   |
| Apple                             | 6         | 0.08%   |
| OPPO Electronics                  | 5         | 0.07%   |
| Microsoft                         | 4         | 0.05%   |
| Linksys                           | 4         | 0.05%   |
| Qualcomm Atheros Communications   | 3         | 0.04%   |
| Fibocom                           | 3         | 0.04%   |
| Edimax Technology                 | 3         | 0.04%   |
| U-Blox                            | 2         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1599      | 18.62%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 402       | 4.68%   |
| Intel Wi-Fi 6 AX200                                               | 312       | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 228       | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 188       | 2.19%   |
| Intel Wireless 8265 / 8275                                        | 174       | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 161       | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 152       | 1.77%   |
| Intel Wi-Fi 6 AX201                                               | 152       | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 151       | 1.76%   |
| Intel Wireless 7260                                               | 150       | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 139       | 1.62%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 136       | 1.58%   |
| Intel Wireless 7265                                               | 135       | 1.57%   |
| Intel Wireless 8260                                               | 116       | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 109       | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 107       | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 105       | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 100       | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 96        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 83        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 77        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                     | 77        | 0.9%    |
| Intel Wireless 3165                                               | 70        | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 58        | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 57        | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 55        | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 55        | 0.64%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 54        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 0.62%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 53        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 0.61%   |
| Intel Wireless 3160                                               | 51        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 50        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 50        | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 49        | 0.57%   |
| Intel Wireless-AC 9260                                            | 48        | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 45        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2334      | 49.75%  |
| Qualcomm Atheros                      | 860       | 18.33%  |
| Realtek Semiconductor                 | 618       | 13.17%  |
| Broadcom                              | 425       | 9.06%   |
| Broadcom Limited                      | 113       | 2.41%   |
| MediaTek                              | 100       | 2.13%   |
| Ralink                                | 49        | 1.04%   |
| TP-Link                               | 41        | 0.87%   |
| Ralink Technology                     | 38        | 0.81%   |
| Dell                                  | 20        | 0.43%   |
| Sierra Wireless                       | 19        | 0.41%   |
| Qualcomm                              | 14        | 0.3%    |
| NetGear                               | 10        | 0.21%   |
| D-Link                                | 9         | 0.19%   |
| ASUSTek Computer                      | 9         | 0.19%   |
| Hewlett-Packard                       | 4         | 0.09%   |
| Qualcomm Atheros Communications       | 3         | 0.06%   |
| Microsoft                             | 3         | 0.06%   |
| Fibocom                               | 3         | 0.06%   |
| Edimax Technology                     | 3         | 0.06%   |
| Ericsson Business Mobile Networks     | 2         | 0.04%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Linksys                               | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 312       | 6.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 228       | 4.83%   |
| Intel Wireless 8265 / 8275                                     | 174       | 3.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 161       | 3.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 152       | 3.22%   |
| Intel Wi-Fi 6 AX201                                            | 152       | 3.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 151       | 3.2%    |
| Intel Wireless 7260                                            | 150       | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 139       | 2.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 136       | 2.88%   |
| Intel Wireless 7265                                            | 135       | 2.86%   |
| Intel Wireless 8260                                            | 116       | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 109       | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 107       | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 105       | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 100       | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 96        | 2.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 83        | 1.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 77        | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                  | 77        | 1.63%   |
| Intel Wireless 3165                                            | 70        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 58        | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 57        | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 55        | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 55        | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 53        | 1.12%   |
| Intel Wireless 3160                                            | 51        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 50        | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 49        | 1.04%   |
| Intel Wireless-AC 9260                                         | 48        | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 45        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                 | 45        | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 44        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 42        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 40        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 40        | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 40        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 34        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 33        | 0.7%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 31        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2242      | 59.49%  |
| Intel                            | 691       | 18.33%  |
| Qualcomm Atheros                 | 271       | 7.19%   |
| Broadcom                         | 167       | 4.43%   |
| Marvell Technology Group         | 63        | 1.67%   |
| Nvidia                           | 51        | 1.35%   |
| ASIX Electronics                 | 46        | 1.22%   |
| Broadcom Limited                 | 34        | 0.9%    |
| Samsung Electronics              | 33        | 0.88%   |
| DisplayLink                      | 28        | 0.74%   |
| Lenovo                           | 22        | 0.58%   |
| Xiaomi                           | 16        | 0.42%   |
| JMicron Technology               | 16        | 0.42%   |
| Google                           | 13        | 0.34%   |
| Silicon Integrated Systems [SiS] | 8         | 0.21%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.21%   |
| TP-Link                          | 7         | 0.19%   |
| Huawei Technologies              | 7         | 0.19%   |
| Motorola PCS                     | 6         | 0.16%   |
| OPPO Electronics                 | 5         | 0.13%   |
| Apple                            | 5         | 0.13%   |
| Qualcomm                         | 3         | 0.08%   |
| MediaTek                         | 3         | 0.08%   |
| Linksys                          | 3         | 0.08%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| LSI                              | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| Research In Motion               | 1         | 0.03%   |
| NTmore                           | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Cypress Semiconductor            | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1599      | 41.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 402       | 10.53%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 188       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 4.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 54        | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 53        | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 50        | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 42        | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 39        | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                     | 38        | 1%      |
| Nvidia MCP79 Ethernet                                             | 37        | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.89%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 33        | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 30        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 30        | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 26        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 20        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 19        | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 18        | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 18        | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 18        | 0.47%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 17        | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 16        | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 15        | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4460      | 55.03%  |
| Ethernet | 3596      | 44.37%  |
| Modem    | 36        | 0.44%   |
| Unknown  | 13        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3802      | 79.03%  |
| Ethernet | 1009      | 20.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3288      | 72.89%  |
| 1     | 1162      | 25.76%  |
| 3     | 31        | 0.69%   |
| 0     | 30        | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3628      | 79.51%  |
| Yes  | 935       | 20.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1960      | 51.11%  |
| Qualcomm Atheros Communications | 379       | 9.88%   |
| Realtek Semiconductor           | 315       | 8.21%   |
| Apple                           | 231       | 6.02%   |
| IMC Networks                    | 206       | 5.37%   |
| Lite-On Technology              | 183       | 4.77%   |
| Broadcom                        | 182       | 4.75%   |
| Foxconn / Hon Hai               | 107       | 2.79%   |
| Dell                            | 60        | 1.56%   |
| Cambridge Silicon Radio         | 38        | 0.99%   |
| Toshiba                         | 28        | 0.73%   |
| Realtek                         | 27        | 0.7%    |
| Ralink                          | 27        | 0.7%    |
| Hewlett-Packard                 | 27        | 0.7%    |
| ASUSTek Computer                | 14        | 0.37%   |
| Foxconn International           | 11        | 0.29%   |
| Ralink Technology               | 7         | 0.18%   |
| Alps Electric                   | 7         | 0.18%   |
| Askey Computer                  | 4         | 0.1%    |
| USI                             | 3         | 0.08%   |
| Unknown                         | 3         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Qcom                            | 3         | 0.08%   |
| Opticis                         | 3         | 0.08%   |
| SIN                             | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| MediaTek                        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| Actions                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 680       | 17.72%  |
| Intel Bluetooth Device                              | 424       | 11.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 329       | 8.57%   |
| Intel AX200 Bluetooth                               | 307       | 8%      |
| Qualcomm Atheros  Bluetooth Device                  | 211       | 5.5%    |
| Realtek Bluetooth Radio                             | 185       | 4.82%   |
| Apple Bluetooth Host Controller                     | 129       | 3.36%   |
| Lite-On Bluetooth Device                            | 112       | 2.92%   |
| Realtek  Bluetooth 4.2 Adapter                      | 90        | 2.35%   |
| Apple Bluetooth USB Host Controller                 | 73        | 1.9%    |
| IMC Networks Bluetooth Radio                        | 66        | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 62        | 1.62%   |
| IMC Networks Wireless_Device                        | 53        | 1.38%   |
| Intel AX210 Bluetooth                               | 49        | 1.28%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 47        | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 46        | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 44        | 1.15%   |
| IMC Networks Bluetooth Device                       | 42        | 1.09%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 38        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 38        | 0.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38        | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 34        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 0.86%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.73%   |
| Realtek Bluetooth Radio                             | 27        | 0.7%    |
| Ralink RT3290 Bluetooth                             | 27        | 0.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.63%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.5%    |
| Apple Bluetooth HCI                                 | 18        | 0.47%   |
| Lite-On Wireless_Device                             | 17        | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 15        | 0.39%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.39%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.36%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 14        | 0.36%   |
| Realtek RTL8821A Bluetooth                          | 13        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3585      | 60.9%   |
| Nvidia                               | 1022      | 17.36%  |
| AMD                                  | 909       | 15.44%  |
| C-Media Electronics                  | 46        | 0.78%   |
| Realtek Semiconductor                | 37        | 0.63%   |
| Logitech                             | 36        | 0.61%   |
| Lenovo                               | 20        | 0.34%   |
| JMTek                                | 19        | 0.32%   |
| GN Netcom                            | 19        | 0.32%   |
| Kingston Technology                  | 14        | 0.24%   |
| Texas Instruments                    | 13        | 0.22%   |
| Apple                                | 12        | 0.2%    |
| Razer USA                            | 10        | 0.17%   |
| Hewlett-Packard                      | 10        | 0.17%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.14%   |
| Generalplus Technology               | 8         | 0.14%   |
| Corsair                              | 8         | 0.14%   |
| SteelSeries ApS                      | 7         | 0.12%   |
| Sony                                 | 7         | 0.12%   |
| Plantronics                          | 7         | 0.12%   |
| Focusrite-Novation                   | 5         | 0.08%   |
| Sennheiser Communications            | 4         | 0.07%   |
| Creative Technology                  | 4         | 0.07%   |
| ASUSTek Computer                     | 4         | 0.07%   |
| Tenx Technology                      | 3         | 0.05%   |
| Samson Technologies                  | 3         | 0.05%   |
| No brand                             | 3         | 0.05%   |
| FiiO Electronics Technology          | 3         | 0.05%   |
| Yamaha                               | 2         | 0.03%   |
| XMOS                                 | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.03%   |
| TerraTec Electronic                  | 2         | 0.03%   |
| Pioneer DJ                           | 2         | 0.03%   |
| GYROCOM C&C                          | 2         | 0.03%   |
| DSEA A/S                             | 2         | 0.03%   |
| CMX Systems                          | 2         | 0.03%   |
| Blue Microphones                     | 2         | 0.03%   |
| AudioQuest                           | 2         | 0.03%   |
| Astro Gaming                         | 2         | 0.03%   |
| Vestax                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 593       | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 519       | 7.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 367       | 5.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 332       | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 277       | 3.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 271       | 3.81%   |
| Intel 8 Series HD Audio Controller                                         | 227       | 3.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 225       | 3.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 204       | 2.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 204       | 2.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 180       | 2.53%   |
| Intel Comet Lake PCH cAVS                                                  | 166       | 2.33%   |
| Intel Broadwell-U Audio Controller                                         | 157       | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 155       | 2.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 150       | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 148       | 2.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 145       | 2.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 131       | 1.84%   |
| Nvidia TU106 High Definition Audio Controller                              | 127       | 1.78%   |
| Intel CM238 HD Audio Controller                                            | 126       | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 125       | 1.76%   |
| AMD FCH Azalia Controller                                                  | 120       | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 111       | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 89        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 84        | 1.18%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 75        | 1.05%   |
| Nvidia GA106 High Definition Audio Controller                              | 72        | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                   | 71        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 64        | 0.9%    |
| Nvidia GA104 High Definition Audio Controller                              | 63        | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 63        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 57        | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 57        | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 54        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 50        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 47        | 0.66%   |
| AMD High Definition Audio Controller                                       | 44        | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 43        | 0.6%    |
| Nvidia MCP79 High Definition Audio                                         | 41        | 0.58%   |
| Nvidia Audio device                                                        | 41        | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 428       | 29.27%  |
| SK hynix            | 325       | 22.23%  |
| Micron Technology   | 197       | 13.47%  |
| Kingston            | 123       | 8.41%   |
| Crucial             | 79        | 5.4%    |
| Unknown             | 52        | 3.56%   |
| A-DATA Technology   | 33        | 2.26%   |
| Smart               | 26        | 1.78%   |
| Ramaxel Technology  | 23        | 1.57%   |
| Corsair             | 21        | 1.44%   |
| Goldkey             | 20        | 1.37%   |
| Elpida              | 18        | 1.23%   |
| Neo Forza           | 17        | 1.16%   |
| G.Skill             | 13        | 0.89%   |
| Smart Brazil        | 10        | 0.68%   |
| Unknown             | 10        | 0.68%   |
| Unknown (ABCD)      | 9         | 0.62%   |
| Team                | 7         | 0.48%   |
| Teikon              | 6         | 0.41%   |
| Nanya Technology    | 6         | 0.41%   |
| Apacer              | 5         | 0.34%   |
| PNY                 | 3         | 0.21%   |
| Patriot             | 3         | 0.21%   |
| High Bridge         | 3         | 0.21%   |
| Avant               | 3         | 0.21%   |
| Timetec             | 2         | 0.14%   |
| GSkill              | 2         | 0.14%   |
| GOODRAM             | 2         | 0.14%   |
| Gold Key            | 2         | 0.14%   |
| ChangXin Memory     | 2         | 0.14%   |
| Unknown (8A02)      | 1         | 0.07%   |
| Unknown (898F)      | 1         | 0.07%   |
| Transcend           | 1         | 0.07%   |
| Silicon Power       | 1         | 0.07%   |
| RZX                 | 1         | 0.07%   |
| PUSKILL             | 1         | 0.07%   |
| Multilaser          | 1         | 0.07%   |
| Magnum Tech         | 1         | 0.07%   |
| Lenovo              | 1         | 0.07%   |
| Hewlett-Packard     | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 36        | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 27        | 1.76%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 1.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 1.17%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 1.11%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 17        | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.98%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.98%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.78%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.72%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 10        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.65%   |
| Unknown                                                          | 10        | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.59%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.59%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.59%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.59%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.52%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.52%   |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 8         | 0.52%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 8         | 0.52%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.52%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 7         | 0.46%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 813       | 66.75%  |
| DDR3    | 236       | 19.38%  |
| LPDDR4  | 64        | 5.25%   |
| LPDDR3  | 57        | 4.68%   |
| DDR5    | 18        | 1.48%   |
| LPDDR5  | 12        | 0.99%   |
| DDR2    | 10        | 0.82%   |
| SDRAM   | 4         | 0.33%   |
| Unknown | 4         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1066      | 85.9%   |
| Row Of Chips | 160       | 12.89%  |
| Chip         | 11        | 0.89%   |
| DIMM         | 3         | 0.24%   |
| Unknown      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 608       | 45.61%  |
| 4096  | 325       | 24.38%  |
| 16384 | 258       | 19.35%  |
| 2048  | 69        | 5.18%   |
| 32768 | 64        | 4.8%    |
| 1024  | 9         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 393       | 29.55%  |
| 3200    | 308       | 23.16%  |
| 1600    | 189       | 14.21%  |
| 2400    | 128       | 9.62%   |
| 2133    | 83        | 6.24%   |
| 4267    | 31        | 2.33%   |
| 1334    | 28        | 2.11%   |
| 3266    | 24        | 1.8%    |
| 1333    | 21        | 1.58%   |
| 4800    | 18        | 1.35%   |
| 8400    | 17        | 1.28%   |
| 1867    | 15        | 1.13%   |
| 6400    | 12        | 0.9%    |
| 4266    | 11        | 0.83%   |
| 1067    | 10        | 0.75%   |
| 800     | 9         | 0.68%   |
| 3733    | 7         | 0.53%   |
| 1866    | 5         | 0.38%   |
| 2933    | 4         | 0.3%    |
| 667     | 4         | 0.3%    |
| Unknown | 3         | 0.23%   |
| 4199    | 2         | 0.15%   |
| 2048    | 2         | 0.15%   |
| 3466    | 1         | 0.08%   |
| 3400    | 1         | 0.08%   |
| 3333    | 1         | 0.08%   |
| 3000    | 1         | 0.08%   |
| 1200    | 1         | 0.08%   |
| 1066    | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 29.17%  |
| Seiko Epson         | 5         | 20.83%  |
| Canon               | 4         | 16.67%  |
| Brother Industries  | 4         | 16.67%  |
| Xerox               | 1         | 4.17%   |
| Samsung Electronics | 1         | 4.17%   |
| MIIIW               | 1         | 4.17%   |
| ICS Advent          | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox B215                      | 1         | 4.17%   |
| Seiko Epson WF-3520 Series      | 1         | 4.17%   |
| Seiko Epson L3110 Series        | 1         | 4.17%   |
| Seiko Epson L132 Series         | 1         | 4.17%   |
| Seiko Epson ET-3750 Series      | 1         | 4.17%   |
| Seiko Epson ET-2700 Series      | 1         | 4.17%   |
| Samsung M2020 Series            | 1         | 4.17%   |
| MIIIW MW Keyboard Air Mini      | 1         | 4.17%   |
| ICS Advent Parallel Adapter     | 1         | 4.17%   |
| HP Ink Tank Wireless 410 series | 1         | 4.17%   |
| HP ENVY Photo 7800 series       | 1         | 4.17%   |
| HP ENVY 4520 series             | 1         | 4.17%   |
| HP Deskjet 3050 J610 series     | 1         | 4.17%   |
| HP Deskjet 2540 series          | 1         | 4.17%   |
| HP Deskjet 2050 J510            | 1         | 4.17%   |
| HP Color LaserJet CP2025dn      | 1         | 4.17%   |
| Canon PIXMA MX920 Series        | 1         | 4.17%   |
| Canon GX7000 series             | 1         | 4.17%   |
| Canon G4010 series              | 1         | 4.17%   |
| Canon E400 series               | 1         | 4.17%   |
| Brother HL-L2370DW series       | 1         | 4.17%   |
| Brother HL-L2320D series        | 1         | 4.17%   |
| Brother HL-3170CDW series       | 1         | 4.17%   |
| Brother HL-2270DW Laser Printer | 1         | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 972       | 24.21%  |
| IMC Networks                           | 434       | 10.81%  |
| Acer                                   | 409       | 10.19%  |
| Microdia                               | 402       | 10.01%  |
| Realtek Semiconductor                  | 337       | 8.39%   |
| Sunplus Innovation Technology          | 224       | 5.58%   |
| Quanta                                 | 198       | 4.93%   |
| Apple                                  | 175       | 4.36%   |
| Cheng Uei Precision Industry (Foxlink) | 145       | 3.61%   |
| Suyin                                  | 120       | 2.99%   |
| Syntek                                 | 99        | 2.47%   |
| Lite-On Technology                     | 78        | 1.94%   |
| Silicon Motion                         | 59        | 1.47%   |
| Luxvisions Innotech Limited            | 56        | 1.39%   |
| Logitech                               | 53        | 1.32%   |
| Ricoh                                  | 37        | 0.92%   |
| Alcor Micro                            | 28        | 0.7%    |
| Samsung Electronics                    | 22        | 0.55%   |
| Sonix Technology                       | 17        | 0.42%   |
| SunplusIT                              | 12        | 0.3%    |
| ALi                                    | 12        | 0.3%    |
| Primax Electronics                     | 10        | 0.25%   |
| DigiTech                               | 10        | 0.25%   |
| Microsoft                              | 9         | 0.22%   |
| Importek                               | 9         | 0.22%   |
| Z-Star Microelectronics                | 8         | 0.2%    |
| Lenovo                                 | 8         | 0.2%    |
| Intel                                  | 7         | 0.17%   |
| Unknown                                | 5         | 0.12%   |
| OmniVision Technologies                | 5         | 0.12%   |
| Generalplus Technology                 | 5         | 0.12%   |
| MacroSilicon                           | 4         | 0.1%    |
| Foxconn / Hon Hai                      | 4         | 0.1%    |
| Razer USA                              | 3         | 0.07%   |
| icSpring                               | 3         | 0.07%   |
| AVerMedia Technologies                 | 3         | 0.07%   |
| Tobii Technology AB                    | 2         | 0.05%   |
| Sunplus Technology                     | 2         | 0.05%   |
| Mustek Systems                         | 2         | 0.05%   |
| LG Electronics                         | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 216       | 5.35%   |
| Chicony Integrated Camera                           | 179       | 4.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 141       | 3.49%   |
| Chicony HD WebCam                                   | 137       | 3.4%    |
| Realtek Integrated_Webcam_HD                        | 133       | 3.3%    |
| IMC Networks Integrated Camera                      | 120       | 2.97%   |
| Chicony USB2.0 Camera                               | 96        | 2.38%   |
| Acer BisonCam,NB Pro                                | 90        | 2.23%   |
| Acer Integrated Camera                              | 77        | 1.91%   |
| Sunplus Integrated_Webcam_HD                        | 65        | 1.61%   |
| Syntek Integrated Camera                            | 60        | 1.49%   |
| Apple Built-in iSight                               | 59        | 1.46%   |
| Apple FaceTime HD Camera                            | 55        | 1.36%   |
| Acer HD Webcam                                      | 52        | 1.29%   |
| Quanta HD User Facing                               | 48        | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 45        | 1.12%   |
| Acer BisonCam, NB Pro                               | 40        | 0.99%   |
| Apple iPhone 5/5C/5S/6/SE                           | 38        | 0.94%   |
| Chicony USB 2.0 Camera                              | 33        | 0.82%   |
| Quanta HD Webcam                                    | 32        | 0.79%   |
| Microdia Integrated Webcam                          | 32        | 0.79%   |
| Sunplus HD WebCam                                   | 31        | 0.77%   |
| Lite-On Integrated Camera                           | 31        | 0.77%   |
| Chicony Integrated Camera (1280x720@30)             | 31        | 0.77%   |
| Chicony HD User Facing                              | 29        | 0.72%   |
| Sunplus ASUS Webcam                                 | 28        | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                | 28        | 0.69%   |
| Chicony USB2.0 HD UVC WebCam                        | 27        | 0.67%   |
| Acer SunplusIT Integrated Camera                    | 27        | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                       | 26        | 0.64%   |
| Acer Lenovo EasyCamera                              | 26        | 0.64%   |
| Chicony HP HD Camera                                | 25        | 0.62%   |
| Realtek USB Camera                                  | 24        | 0.59%   |
| Realtek Integrated Webcam                           | 22        | 0.55%   |
| Quanta VGA WebCam                                   | 22        | 0.55%   |
| Chicony HP TrueVision HD Camera                     | 22        | 0.55%   |
| Quanta HP TrueVision HD Camera                      | 21        | 0.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 21        | 0.52%   |
| Chicony HP Wide Vision HD Camera                    | 21        | 0.52%   |
| Chicony HP TrueVision HD                            | 21        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 237       | 30.35%  |
| Validity Sensors                   | 235       | 30.09%  |
| Shenzhen Goodix Technology         | 144       | 18.44%  |
| Upek                               | 44        | 5.63%   |
| Elan Microelectronics              | 42        | 5.38%   |
| LighTuning Technology              | 36        | 4.61%   |
| AuthenTec                          | 26        | 3.33%   |
| STMicroelectronics                 | 7         | 0.9%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.38%   |
| Focal-systems.Corp                 | 3         | 0.38%   |
| HOLTEK                             | 2         | 0.26%   |
| Samsung Electronics                | 1         | 0.13%   |
| DigitalPersona                     | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 73        | 9.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 72        | 9.22%   |
| Shenzhen Goodix  Fingerprint Device                                        | 67        | 8.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 6.91%   |
| Shenzhen Goodix FingerPrint                                                | 46        | 5.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 43        | 5.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 40        | 5.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 32        | 4.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 31        | 3.97%   |
| Elan ELAN:Fingerprint                                                      | 31        | 3.97%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 2.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.3%    |
| Validity Sensors VFS491                                                    | 18        | 2.3%    |
| Synaptics WBDI Device                                                      | 18        | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.18%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.79%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 1.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.28%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.15%   |
| Synaptics  WBDI                                                            | 8         | 1.02%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.02%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.02%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 0.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 0.9%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.9%    |
| AuthenTec AES2810                                                          | 7         | 0.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.64%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.51%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.51%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.38%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.38%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.38%   |
| AuthenTec AES1600                                                          | 3         | 0.38%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 139       | 46.96%  |
| Alcor Micro               | 81        | 27.36%  |
| Upek                      | 28        | 9.46%   |
| O2 Micro                  | 23        | 7.77%   |
| Lenovo                    | 17        | 5.74%   |
| Aladdin Knowledge Systems | 2         | 0.68%   |
| SCM Microsystems          | 1         | 0.34%   |
| OmniKey                   | 1         | 0.34%   |
| Giesecke & Devrient       | 1         | 0.34%   |
| Gemalto (was Gemplus)     | 1         | 0.34%   |
| Clay Logic                | 1         | 0.34%   |
| Advanced Card Systems     | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 27.36%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 14.86%  |
| Broadcom 5880                                                                | 38        | 12.84%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 37        | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 9.46%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 6.42%   |
| Broadcom 58200                                                               | 18        | 6.08%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.74%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.68%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.34%   |
| OmniKey CardMan 4321                                                         | 1         | 0.34%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.34%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.34%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.34%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2865      | 62.51%  |
| 1     | 1351      | 29.48%  |
| 2     | 314       | 6.85%   |
| 3     | 47        | 1.03%   |
| 4     | 5         | 0.11%   |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 761       | 36.69%  |
| Chipcard                 | 288       | 13.89%  |
| Multimedia controller    | 287       | 13.84%  |
| Net/wireless             | 245       | 11.81%  |
| Graphics card            | 239       | 11.52%  |
| Bluetooth                | 63        | 3.04%   |
| Camera                   | 42        | 2.03%   |
| Storage                  | 37        | 1.78%   |
| Net/ethernet             | 27        | 1.3%    |
| Sound                    | 22        | 1.06%   |
| Card reader              | 16        | 0.77%   |
| Communication controller | 15        | 0.72%   |
| Network                  | 10        | 0.48%   |
| Modem                    | 9         | 0.43%   |
| Storage/ide              | 5         | 0.24%   |
| Storage/nvme             | 2         | 0.1%    |
| Flash memory             | 2         | 0.1%    |
| Firewire controller      | 2         | 0.1%    |
| Unclassified device      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

