Gentoo - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Gentoo.

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

Total: 1550

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G5              | [4536e47198](https://linux-hardware.org/?probe=4536e47198) | May 07, 2024 |
| Dell          | Precision 7720              | [5423da6e5c](https://linux-hardware.org/?probe=5423da6e5c) | May 07, 2024 |
| METAPHYUNI    | MetawillBook03              | [d5af716feb](https://linux-hardware.org/?probe=d5af716feb) | May 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [67fbb6a446](https://linux-hardware.org/?probe=67fbb6a446) | May 03, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [f6152a7042](https://linux-hardware.org/?probe=f6152a7042) | May 03, 2024 |
| HP            | ProBook 4510s               | [a6f89b6485](https://linux-hardware.org/?probe=a6f89b6485) | May 02, 2024 |
| Dell          | XPS 13 9310                 | [50ea9a7b8e](https://linux-hardware.org/?probe=50ea9a7b8e) | May 01, 2024 |
| Dell          | XPS 13 9310                 | [39ab9869d2](https://linux-hardware.org/?probe=39ab9869d2) | May 01, 2024 |
| HP            | EliteBook 845 14 inch G1... | [8fa3424cce](https://linux-hardware.org/?probe=8fa3424cce) | Apr 30, 2024 |
| HP            | EliteBook 845 14 inch G1... | [62914f0506](https://linux-hardware.org/?probe=62914f0506) | Apr 30, 2024 |
| Maibenben     | MaiBook M                   | [48837878a2](https://linux-hardware.org/?probe=48837878a2) | Apr 29, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [703d565003](https://linux-hardware.org/?probe=703d565003) | Apr 26, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [c207bea569](https://linux-hardware.org/?probe=c207bea569) | Apr 25, 2024 |
| ASUSTek       | X550ZA                      | [89422ba7fc](https://linux-hardware.org/?probe=89422ba7fc) | Apr 23, 2024 |
| Lenovo        | G50-30 80G0                 | [6b8474e96b](https://linux-hardware.org/?probe=6b8474e96b) | Apr 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4c782693bf](https://linux-hardware.org/?probe=4c782693bf) | Apr 20, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [2bb3d4f699](https://linux-hardware.org/?probe=2bb3d4f699) | Apr 19, 2024 |
| Lenovo        | ThinkPad P16 Gen 2 21FA0... | [445b981f65](https://linux-hardware.org/?probe=445b981f65) | Apr 18, 2024 |
| Lenovo        | ZHAOYANG E43                | [1192eac8f1](https://linux-hardware.org/?probe=1192eac8f1) | Apr 17, 2024 |
| Chuwi         | GemiBook XPro               | [9ebacb4cf9](https://linux-hardware.org/?probe=9ebacb4cf9) | Apr 17, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [e3d7887dbb](https://linux-hardware.org/?probe=e3d7887dbb) | Apr 16, 2024 |
| Lenovo        | ThinkPad T480 20L6SAYX00    | [f53da67ab4](https://linux-hardware.org/?probe=f53da67ab4) | Apr 15, 2024 |
| Lenovo        | ThinkPad T480 20L6SAYX00    | [fc73e6bb02](https://linux-hardware.org/?probe=fc73e6bb02) | Apr 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [c28ddacfd6](https://linux-hardware.org/?probe=c28ddacfd6) | Apr 13, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [2eea232a7e](https://linux-hardware.org/?probe=2eea232a7e) | Apr 13, 2024 |
| Dell          | Latitude 5440               | [1fb5966e12](https://linux-hardware.org/?probe=1fb5966e12) | Apr 12, 2024 |
| Dell          | G15 5510                    | [e8cfa16a81](https://linux-hardware.org/?probe=e8cfa16a81) | Apr 12, 2024 |
| Dell          | G15 5510                    | [9ed69c889f](https://linux-hardware.org/?probe=9ed69c889f) | Apr 12, 2024 |
| IBM           | ThinkPad T41 23737JU        | [3e03052246](https://linux-hardware.org/?probe=3e03052246) | Apr 12, 2024 |
| Dell          | G3 3590                     | [6b282a982e](https://linux-hardware.org/?probe=6b282a982e) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [44ed4afea3](https://linux-hardware.org/?probe=44ed4afea3) | Apr 09, 2024 |
| Dell          | Precision 5530              | [84d24da656](https://linux-hardware.org/?probe=84d24da656) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [0ca999c16b](https://linux-hardware.org/?probe=0ca999c16b) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [40e7da85c2](https://linux-hardware.org/?probe=40e7da85c2) | Apr 06, 2024 |
| Framework     | Laptop (13th Gen Intel C... | [0d1189e3fb](https://linux-hardware.org/?probe=0d1189e3fb) | Apr 04, 2024 |
| Dell          | Precision 5480              | [665a2dee23](https://linux-hardware.org/?probe=665a2dee23) | Apr 04, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [9d19446a7f](https://linux-hardware.org/?probe=9d19446a7f) | Apr 01, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [df89cb1a75](https://linux-hardware.org/?probe=df89cb1a75) | Mar 31, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [82ac8c0b36](https://linux-hardware.org/?probe=82ac8c0b36) | Mar 31, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [0b20dc1c09](https://linux-hardware.org/?probe=0b20dc1c09) | Mar 30, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | [b0c74f7b30](https://linux-hardware.org/?probe=b0c74f7b30) | Mar 30, 2024 |
| Lenovo        | ThinkPad T470 20HES18R20    | [0c5f481d17](https://linux-hardware.org/?probe=0c5f481d17) | Mar 27, 2024 |
| Dell          | Inspiron N5010              | [14031f3746](https://linux-hardware.org/?probe=14031f3746) | Mar 17, 2024 |
| Dell          | G5 5590                     | [c914da4cc5](https://linux-hardware.org/?probe=c914da4cc5) | Mar 17, 2024 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [63eb058c79](https://linux-hardware.org/?probe=63eb058c79) | Mar 17, 2024 |
| HP            | ProBook 430 G7              | [05be2ac277](https://linux-hardware.org/?probe=05be2ac277) | Mar 17, 2024 |
| Dell          | Latitude E6540              | [bbc5613ffc](https://linux-hardware.org/?probe=bbc5613ffc) | Mar 15, 2024 |
| HP            | Pavilion Notebook           | [b2e7f143bc](https://linux-hardware.org/?probe=b2e7f143bc) | Mar 13, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B5402CVA... | [093a0c28e4](https://linux-hardware.org/?probe=093a0c28e4) | Mar 11, 2024 |
| Lenovo        | ThinkPad T480 20L50013US    | [8b29b924ae](https://linux-hardware.org/?probe=8b29b924ae) | Mar 10, 2024 |
| Dell          | Latitude 7490               | [af0f098b77](https://linux-hardware.org/?probe=af0f098b77) | Mar 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [b4686bb020](https://linux-hardware.org/?probe=b4686bb020) | Mar 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [4d7fa7ac88](https://linux-hardware.org/?probe=4d7fa7ac88) | Mar 10, 2024 |
| HP            | Laptop 15-fc0xxx            | [63f6678f1c](https://linux-hardware.org/?probe=63f6678f1c) | Mar 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2ce71ad477](https://linux-hardware.org/?probe=2ce71ad477) | Mar 04, 2024 |
| Acer          | Swift SF314-41              | [9143ec0c20](https://linux-hardware.org/?probe=9143ec0c20) | Mar 04, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [279f64b529](https://linux-hardware.org/?probe=279f64b529) | Mar 04, 2024 |
| Acer          | Aspire V3-572P              | [bfdf32c8e1](https://linux-hardware.org/?probe=bfdf32c8e1) | Mar 02, 2024 |
| Timi          | RedmiBook Pro 15S           | [402f19be59](https://linux-hardware.org/?probe=402f19be59) | Mar 02, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [9d279afdd2](https://linux-hardware.org/?probe=9d279afdd2) | Feb 29, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [4e7241b44f](https://linux-hardware.org/?probe=4e7241b44f) | Feb 29, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | [1b28fd0c04](https://linux-hardware.org/?probe=1b28fd0c04) | Feb 28, 2024 |
| Anbernic      | Win600                      | [309a79c0c5](https://linux-hardware.org/?probe=309a79c0c5) | Feb 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c6cff98a84](https://linux-hardware.org/?probe=c6cff98a84) | Feb 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [448ad7f7cf](https://linux-hardware.org/?probe=448ad7f7cf) | Feb 24, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | [6f6430db27](https://linux-hardware.org/?probe=6f6430db27) | Feb 20, 2024 |
| Lenovo        | G50-30 80G0                 | [05d7ddd936](https://linux-hardware.org/?probe=05d7ddd936) | Feb 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d3554f701e](https://linux-hardware.org/?probe=d3554f701e) | Feb 19, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [a6ee663daa](https://linux-hardware.org/?probe=a6ee663daa) | Feb 18, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [5b768d1518](https://linux-hardware.org/?probe=5b768d1518) | Feb 18, 2024 |
| Dell          | Latitude E6540              | [b3d3fd2a6e](https://linux-hardware.org/?probe=b3d3fd2a6e) | Feb 18, 2024 |
| HP            | Laptop 17-ca1xxx            | [9c0e3d1a1a](https://linux-hardware.org/?probe=9c0e3d1a1a) | Feb 14, 2024 |
| TUXEDO        | Book BA1510                 | [5e0d56776d](https://linux-hardware.org/?probe=5e0d56776d) | Feb 14, 2024 |
| Lenovo        | ThinkPad T480s 20L8002VM... | [8e506a8c7e](https://linux-hardware.org/?probe=8e506a8c7e) | Feb 09, 2024 |
| Notebook      | NS5x_NS7xPU                 | [d528da165f](https://linux-hardware.org/?probe=d528da165f) | Feb 07, 2024 |
| HP            | Pavilion Notebook           | [075e2f410b](https://linux-hardware.org/?probe=075e2f410b) | Feb 05, 2024 |
| HP            | Pavilion Notebook           | [f6f5d83216](https://linux-hardware.org/?probe=f6f5d83216) | Feb 04, 2024 |
| Razer         | Blade 14 - RZ09-0482        | [49f14f0aae](https://linux-hardware.org/?probe=49f14f0aae) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [afbbc9ebf0](https://linux-hardware.org/?probe=afbbc9ebf0) | Jan 31, 2024 |
| Star Labs     | StarBook                    | [a324d865a6](https://linux-hardware.org/?probe=a324d865a6) | Jan 24, 2024 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [07799fb2f9](https://linux-hardware.org/?probe=07799fb2f9) | Jan 19, 2024 |
| HP            | ZBook Studio 16 inch G9 ... | [e736cc5c9a](https://linux-hardware.org/?probe=e736cc5c9a) | Jan 18, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [18a0aeeddf](https://linux-hardware.org/?probe=18a0aeeddf) | Jan 18, 2024 |
| HP            | Laptop 15t-dy100            | [68c23a7bd3](https://linux-hardware.org/?probe=68c23a7bd3) | Jan 17, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [4af392aac3](https://linux-hardware.org/?probe=4af392aac3) | Jan 14, 2024 |
| HP            | EliteBook 830 G6            | [dc433d32e3](https://linux-hardware.org/?probe=dc433d32e3) | Jan 13, 2024 |
| MSI           | Pulse 15 B13VFK             | [75dde9eefd](https://linux-hardware.org/?probe=75dde9eefd) | Jan 12, 2024 |
| HP            | Laptop 15 da0018nk          | [11c54a0e5b](https://linux-hardware.org/?probe=11c54a0e5b) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d3f6265673](https://linux-hardware.org/?probe=d3f6265673) | Jan 10, 2024 |
| DEXP          | Aquilon C14                 | [d38932d74f](https://linux-hardware.org/?probe=d38932d74f) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | [36dc56b0ed](https://linux-hardware.org/?probe=36dc56b0ed) | Jan 09, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [ac39f0a923](https://linux-hardware.org/?probe=ac39f0a923) | Jan 08, 2024 |
| Star Labs     | StarLite                    | [751432d737](https://linux-hardware.org/?probe=751432d737) | Jan 07, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [33b192a7d0](https://linux-hardware.org/?probe=33b192a7d0) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | [513f1c7737](https://linux-hardware.org/?probe=513f1c7737) | Jan 06, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1ecec883dd](https://linux-hardware.org/?probe=1ecec883dd) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [98da18a6c0](https://linux-hardware.org/?probe=98da18a6c0) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2602d65d52](https://linux-hardware.org/?probe=2602d65d52) | Jan 06, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [94b30c5116](https://linux-hardware.org/?probe=94b30c5116) | Jan 06, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8d63c2ea2b](https://linux-hardware.org/?probe=8d63c2ea2b) | Jan 06, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [90b8ceb64c](https://linux-hardware.org/?probe=90b8ceb64c) | Jan 05, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [42bd246eae](https://linux-hardware.org/?probe=42bd246eae) | Jan 05, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [f7ad5f683a](https://linux-hardware.org/?probe=f7ad5f683a) | Jan 04, 2024 |
| Star Labs     | StarLite                    | [9f0fae17e5](https://linux-hardware.org/?probe=9f0fae17e5) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [ab04c74157](https://linux-hardware.org/?probe=ab04c74157) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| Acer          | Aspire A517-52G             | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [6826d7c88d](https://linux-hardware.org/?probe=6826d7c88d) | Jan 01, 2024 |
| Dell          | Latitude D630               | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| MSI           | Stealth 16Studio A13VF      | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| Dell          | Precision 5560              | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| ASUSTek       | G750JX                      | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| MSI           | Delta 15 A5EFK              | [af7c011930](https://linux-hardware.org/?probe=af7c011930) | Dec 25, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [2394204218](https://linux-hardware.org/?probe=2394204218) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | [c1abfa26d5](https://linux-hardware.org/?probe=c1abfa26d5) | Dec 24, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6b0368fd61](https://linux-hardware.org/?probe=6b0368fd61) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [87b9f04878](https://linux-hardware.org/?probe=87b9f04878) | Dec 23, 2023 |
| Dell          | Precision 5480              | [7cc190b5c0](https://linux-hardware.org/?probe=7cc190b5c0) | Dec 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b14bdf4602](https://linux-hardware.org/?probe=b14bdf4602) | Dec 20, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [8e419e7090](https://linux-hardware.org/?probe=8e419e7090) | Dec 16, 2023 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [042bbde845](https://linux-hardware.org/?probe=042bbde845) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [4c6cd4453d](https://linux-hardware.org/?probe=4c6cd4453d) | Dec 10, 2023 |
| Dell          | XPS 9320                    | [60c734eb9c](https://linux-hardware.org/?probe=60c734eb9c) | Dec 08, 2023 |
| BANGHO        | MAX L4                      | [d1306fe54f](https://linux-hardware.org/?probe=d1306fe54f) | Dec 03, 2023 |
| BANGHO        | MAX L4                      | [a0f107fc92](https://linux-hardware.org/?probe=a0f107fc92) | Dec 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [426263e458](https://linux-hardware.org/?probe=426263e458) | Dec 03, 2023 |
| Lenovo        | ThinkPad T410 2518C3U       | [d95358436c](https://linux-hardware.org/?probe=d95358436c) | Nov 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [d4c90a615f](https://linux-hardware.org/?probe=d4c90a615f) | Nov 29, 2023 |
| Unknown       | Unknown                     | [b6ebeab524](https://linux-hardware.org/?probe=b6ebeab524) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [2b2bb98701](https://linux-hardware.org/?probe=2b2bb98701) | Nov 29, 2023 |
| Dell          | Latitude E6540              | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Unknown       | Unknown                     | [d7d0f11ab2](https://linux-hardware.org/?probe=d7d0f11ab2) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [f5949df300](https://linux-hardware.org/?probe=f5949df300) | Nov 28, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [ee929504ae](https://linux-hardware.org/?probe=ee929504ae) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [9d3e14a9ba](https://linux-hardware.org/?probe=9d3e14a9ba) | Nov 27, 2023 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [83d5ded7d9](https://linux-hardware.org/?probe=83d5ded7d9) | Nov 27, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| Dell          | Latitude D630               | [51af6a8f00](https://linux-hardware.org/?probe=51af6a8f00) | Nov 26, 2023 |
| HP            | EliteBook 840 G5            | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [360ad65af8](https://linux-hardware.org/?probe=360ad65af8) | Nov 21, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3a8da808e0](https://linux-hardware.org/?probe=3a8da808e0) | Nov 20, 2023 |
| HP            | Victus by Gaming Laptop ... | [d46bf1bcb4](https://linux-hardware.org/?probe=d46bf1bcb4) | Nov 18, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CMC... | [e25caef1f8](https://linux-hardware.org/?probe=e25caef1f8) | Nov 18, 2023 |
| HP            | Pavilion Notebook           | [85f5d912da](https://linux-hardware.org/?probe=85f5d912da) | Nov 18, 2023 |
| Dell          | Latitude D630               | [54e404f085](https://linux-hardware.org/?probe=54e404f085) | Nov 18, 2023 |
| Dell          | Precision 5480              | [ee10103325](https://linux-hardware.org/?probe=ee10103325) | Nov 18, 2023 |
| Notebook      | NS5x_NS7xPU                 | [c26f7106c6](https://linux-hardware.org/?probe=c26f7106c6) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Dell          | G5 5505                     | [be553804bd](https://linux-hardware.org/?probe=be553804bd) | Nov 13, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [f1e3e6eb2c](https://linux-hardware.org/?probe=f1e3e6eb2c) | Nov 13, 2023 |
| Dell          | G5 5505                     | [574ccd4e6f](https://linux-hardware.org/?probe=574ccd4e6f) | Nov 13, 2023 |
| Lenovo        | G50-30 80G0                 | [51cd292a70](https://linux-hardware.org/?probe=51cd292a70) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [8415697290](https://linux-hardware.org/?probe=8415697290) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | [16d356b88c](https://linux-hardware.org/?probe=16d356b88c) | Nov 12, 2023 |
| Lenovo        | ThinkPad T420 4236QE0       | [bce581924a](https://linux-hardware.org/?probe=bce581924a) | Nov 12, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [6996973cde](https://linux-hardware.org/?probe=6996973cde) | Nov 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4aae90aee9](https://linux-hardware.org/?probe=4aae90aee9) | Nov 11, 2023 |
| Dell          | Latitude D630               | [8af88f25f0](https://linux-hardware.org/?probe=8af88f25f0) | Nov 10, 2023 |
| Notebook      | NS5x_NS7xPU                 | [4b53c4e9da](https://linux-hardware.org/?probe=4b53c4e9da) | Nov 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [aa17167e95](https://linux-hardware.org/?probe=aa17167e95) | Nov 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [379584ba47](https://linux-hardware.org/?probe=379584ba47) | Nov 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [c0f28da2b7](https://linux-hardware.org/?probe=c0f28da2b7) | Nov 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [24cd0b58d3](https://linux-hardware.org/?probe=24cd0b58d3) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [503b6e943c](https://linux-hardware.org/?probe=503b6e943c) | Nov 06, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| Dell          | XPS 15 7590                 | [63e30986f6](https://linux-hardware.org/?probe=63e30986f6) | Nov 05, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Dell          | XPS 15 9530                 | [148857cc51](https://linux-hardware.org/?probe=148857cc51) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [b553bb2a36](https://linux-hardware.org/?probe=b553bb2a36) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [0a990e1165](https://linux-hardware.org/?probe=0a990e1165) | Oct 31, 2023 |
| Dell          | Latitude 7320               | [efc40122bf](https://linux-hardware.org/?probe=efc40122bf) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [de3f77c938](https://linux-hardware.org/?probe=de3f77c938) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| Acer          | Swift SFX14-41G             | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [5c169fe4ed](https://linux-hardware.org/?probe=5c169fe4ed) | Oct 27, 2023 |
| ASUSTek       | Zenbook UX7602VI_UX7602V... | [1c1d7bd2b1](https://linux-hardware.org/?probe=1c1d7bd2b1) | Oct 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [47e99a1356](https://linux-hardware.org/?probe=47e99a1356) | Oct 26, 2023 |
| HP            | EliteBook 845 14 inch G1... | [ba2a49fbef](https://linux-hardware.org/?probe=ba2a49fbef) | Oct 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f4a0aca53d](https://linux-hardware.org/?probe=f4a0aca53d) | Oct 24, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [f2b15bc2f1](https://linux-hardware.org/?probe=f2b15bc2f1) | Oct 23, 2023 |
| Lenovo        | G50-30 80G0                 | [2a00efe761](https://linux-hardware.org/?probe=2a00efe761) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [3368da4a2b](https://linux-hardware.org/?probe=3368da4a2b) | Oct 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [e794aa4113](https://linux-hardware.org/?probe=e794aa4113) | Oct 18, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8be373f42f](https://linux-hardware.org/?probe=8be373f42f) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [98ebe6766d](https://linux-hardware.org/?probe=98ebe6766d) | Oct 14, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [4f5f1c9eea](https://linux-hardware.org/?probe=4f5f1c9eea) | Oct 11, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [af06968ae1](https://linux-hardware.org/?probe=af06968ae1) | Oct 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da869ee2ba](https://linux-hardware.org/?probe=da869ee2ba) | Oct 04, 2023 |
| HP            | EliteBook 830 G6            | [e684c274a6](https://linux-hardware.org/?probe=e684c274a6) | Oct 03, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [40f87e9874](https://linux-hardware.org/?probe=40f87e9874) | Oct 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| HP            | EliteBook 830 G6            | [154150aa88](https://linux-hardware.org/?probe=154150aa88) | Sep 30, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [2a507c567b](https://linux-hardware.org/?probe=2a507c567b) | Sep 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [f1623258a8](https://linux-hardware.org/?probe=f1623258a8) | Sep 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8a581a8a85](https://linux-hardware.org/?probe=8a581a8a85) | Sep 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [7732f1eb9b](https://linux-hardware.org/?probe=7732f1eb9b) | Sep 22, 2023 |
| HP            | ProBook 450 G5              | [e1b56bb588](https://linux-hardware.org/?probe=e1b56bb588) | Sep 19, 2023 |
| HP            | EliteBook 830 G6            | [8dcd49002d](https://linux-hardware.org/?probe=8dcd49002d) | Sep 18, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [4b1c4ae225](https://linux-hardware.org/?probe=4b1c4ae225) | Sep 18, 2023 |
| Timi          | RedmiBook Pro 15S           | [3306655fb2](https://linux-hardware.org/?probe=3306655fb2) | Sep 17, 2023 |
| Timi          | RedmiBook Pro 15S           | [75a8af42cd](https://linux-hardware.org/?probe=75a8af42cd) | Sep 17, 2023 |
| Acer          | Aspire A515-45              | [7cd5acacf7](https://linux-hardware.org/?probe=7cd5acacf7) | Sep 16, 2023 |
| HP            | EliteBook 8540w             | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| HP            | ProBook 450 G5              | [077f5b81b8](https://linux-hardware.org/?probe=077f5b81b8) | Sep 14, 2023 |
| Apple         | MacBookPro11,2              | [e38a2e668b](https://linux-hardware.org/?probe=e38a2e668b) | Sep 12, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [de7acf45a6](https://linux-hardware.org/?probe=de7acf45a6) | Sep 12, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [5ac44fe5ec](https://linux-hardware.org/?probe=5ac44fe5ec) | Sep 11, 2023 |
| Apple         | MacBookPro11,2              | [830ca674bb](https://linux-hardware.org/?probe=830ca674bb) | Sep 10, 2023 |
| Dell          | Precision M4800             | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [a6bbf0ac50](https://linux-hardware.org/?probe=a6bbf0ac50) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| System76      | Pangolin                    | [43dbf49440](https://linux-hardware.org/?probe=43dbf49440) | Sep 06, 2023 |
| System76      | Pangolin                    | [461b8d48ba](https://linux-hardware.org/?probe=461b8d48ba) | Sep 05, 2023 |
| Gigabyte      | AORUS 17 XE4                | [7987abcc44](https://linux-hardware.org/?probe=7987abcc44) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | [f3cbaf1a86](https://linux-hardware.org/?probe=f3cbaf1a86) | Sep 04, 2023 |
| Dell          | Inspiron 16 5625            | [b0e01251ca](https://linux-hardware.org/?probe=b0e01251ca) | Sep 04, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| HP            | ProBook 430 G5              | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [5032531f3e](https://linux-hardware.org/?probe=5032531f3e) | Sep 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [cb84df3a99](https://linux-hardware.org/?probe=cb84df3a99) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [b4eb252e8f](https://linux-hardware.org/?probe=b4eb252e8f) | Aug 31, 2023 |
| Dell          | Inspiron 15 3511            | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Dell          | Latitude E6510              | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| Dell          | Latitude E6510              | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Dell          | G5 5505                     | [a96b02c261](https://linux-hardware.org/?probe=a96b02c261) | Aug 28, 2023 |
| Dell          | G5 5505                     | [01201d16aa](https://linux-hardware.org/?probe=01201d16aa) | Aug 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [19433fe76f](https://linux-hardware.org/?probe=19433fe76f) | Aug 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [475563b8b4](https://linux-hardware.org/?probe=475563b8b4) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| HP            | EliteBook 8540w             | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| MSI           | Modern 14 C12M              | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| Timi          | RedmiBook Pro 15S           | [3223b9a4bb](https://linux-hardware.org/?probe=3223b9a4bb) | Aug 19, 2023 |
| HP            | Laptop 14-df0xxx            | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Apple         | MacBookPro11,1              | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| HP            | EliteBook 8540w             | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| Dell          | Latitude E7450              | [057d88b470](https://linux-hardware.org/?probe=057d88b470) | Aug 13, 2023 |
| HP            | EliteBook 8540w             | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Apple         | MacBookPro10,1              | [ed97e2ea3e](https://linux-hardware.org/?probe=ed97e2ea3e) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [41b594c2c7](https://linux-hardware.org/?probe=41b594c2c7) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [ae42e537d2](https://linux-hardware.org/?probe=ae42e537d2) | Aug 05, 2023 |
| HP            | Laptop 15-ra0xx             | [51f2c38666](https://linux-hardware.org/?probe=51f2c38666) | Aug 05, 2023 |
| Lenovo        | Yoga 2 13 20344             | [767b492aa4](https://linux-hardware.org/?probe=767b492aa4) | Aug 03, 2023 |
| Lenovo        | Yoga 2 13 20344             | [47ca08e0d1](https://linux-hardware.org/?probe=47ca08e0d1) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| Alienware     | x17 R1                      | [bcdf52a63e](https://linux-hardware.org/?probe=bcdf52a63e) | Aug 01, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [451cbfaee5](https://linux-hardware.org/?probe=451cbfaee5) | Jul 29, 2023 |
| Apple         | MacBookPro12,1              | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| HP            | EliteBook 8540w             | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [3cb74490f6](https://linux-hardware.org/?probe=3cb74490f6) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [c73107bcac](https://linux-hardware.org/?probe=c73107bcac) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [1aeabb238f](https://linux-hardware.org/?probe=1aeabb238f) | Jul 25, 2023 |
| Dell          | XPS 15 9520                 | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |
| A-DATA Tec... | XENIA 15                    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| HP            | ProBook 450 G5              | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| HP            | ProBook 440 G7              | [48cf81576d](https://linux-hardware.org/?probe=48cf81576d) | Jul 17, 2023 |
| HP            | EliteBook 8540w             | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [a5cdc8bb58](https://linux-hardware.org/?probe=a5cdc8bb58) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| Lenovo        | ThinkPad T430 2344BZU       | [2a37881afa](https://linux-hardware.org/?probe=2a37881afa) | Jul 11, 2023 |
| Apple         | MacBookPro11,1              | [7256e6a7b2](https://linux-hardware.org/?probe=7256e6a7b2) | Jul 11, 2023 |
| Dell          | XPS 15 7590                 | [ca41a9886a](https://linux-hardware.org/?probe=ca41a9886a) | Jul 09, 2023 |
| HP            | EliteBook 8540w             | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| Fujitsu       | LIFEBOOK U758               | [eaa8bbf9da](https://linux-hardware.org/?probe=eaa8bbf9da) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Jumper        | EZbook                      | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [68daff498d](https://linux-hardware.org/?probe=68daff498d) | Jul 02, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [f587b9a46c](https://linux-hardware.org/?probe=f587b9a46c) | Jul 02, 2023 |
| HP            | EliteBook 8540w             | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | [bf36f89d32](https://linux-hardware.org/?probe=bf36f89d32) | Jul 01, 2023 |
| Dell          | Inspiron 16 5625            | [cbbe256fa2](https://linux-hardware.org/?probe=cbbe256fa2) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [2d16f5be74](https://linux-hardware.org/?probe=2d16f5be74) | Jun 29, 2023 |
| HP            | EliteBook 8540w             | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [178ed56625](https://linux-hardware.org/?probe=178ed56625) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [12153cd235](https://linux-hardware.org/?probe=12153cd235) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4d509da42f](https://linux-hardware.org/?probe=4d509da42f) | Jun 18, 2023 |
| HP            | ENVY m6                     | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| Dell          | Precision 5530              | [29ec4c7e1d](https://linux-hardware.org/?probe=29ec4c7e1d) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| Dell          | Precision 5530              | [cff5125fb6](https://linux-hardware.org/?probe=cff5125fb6) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ec46ef5f36](https://linux-hardware.org/?probe=ec46ef5f36) | Jun 15, 2023 |
| HP            | EliteBook 8540w             | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| Google        | Nightfury                   | [02badb166b](https://linux-hardware.org/?probe=02badb166b) | Jun 14, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [fc0318992c](https://linux-hardware.org/?probe=fc0318992c) | Jun 12, 2023 |
| Lenovo        | Yoga 2 13 20344             | [eab5787d6a](https://linux-hardware.org/?probe=eab5787d6a) | Jun 11, 2023 |
| ASUSTek       | ROG G703GI_G7BI             | [272de7ad6b](https://linux-hardware.org/?probe=272de7ad6b) | Jun 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Acer          | Swift SF314-511             | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| Dell          | Precision 5530              | [8b4e10b85a](https://linux-hardware.org/?probe=8b4e10b85a) | Jun 05, 2023 |
| Apple         | MacBookPro11,1              | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| Dell          | Precision 5530              | [151584f5aa](https://linux-hardware.org/?probe=151584f5aa) | Jun 02, 2023 |
| MSI           | GE76 Raider 11UH            | [64a17da7a3](https://linux-hardware.org/?probe=64a17da7a3) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [f4889c41be](https://linux-hardware.org/?probe=f4889c41be) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| HP            | Pavilion Notebook           | [08eec5e6ca](https://linux-hardware.org/?probe=08eec5e6ca) | May 26, 2023 |
| Acer          | Aspire A515-45G             | [99bcbfbb2a](https://linux-hardware.org/?probe=99bcbfbb2a) | May 25, 2023 |
| HP            | EliteBook 8570w             | [35a7542634](https://linux-hardware.org/?probe=35a7542634) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Fujitsu       | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [4b3b94a776](https://linux-hardware.org/?probe=4b3b94a776) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [870c85a9ac](https://linux-hardware.org/?probe=870c85a9ac) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [847d86e573](https://linux-hardware.org/?probe=847d86e573) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Unknown       | Unknown                     | [82281ca3d5](https://linux-hardware.org/?probe=82281ca3d5) | May 06, 2023 |
| HUAWEI        | CREM-WXX9                   | [8ebf347e24](https://linux-hardware.org/?probe=8ebf347e24) | May 03, 2023 |
| Acer          | Swift SF314-41              | [520066013b](https://linux-hardware.org/?probe=520066013b) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [6f015f949c](https://linux-hardware.org/?probe=6f015f949c) | May 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | [eeb1550b82](https://linux-hardware.org/?probe=eeb1550b82) | Apr 29, 2023 |
| HP            | G62                         | [e5ae199298](https://linux-hardware.org/?probe=e5ae199298) | Apr 28, 2023 |
| ASUSTek       | N550JX                      | [790f73f0bd](https://linux-hardware.org/?probe=790f73f0bd) | Apr 28, 2023 |
| Dell          | Inspiron N5010              | [78b4f0cd2f](https://linux-hardware.org/?probe=78b4f0cd2f) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a16e963c10](https://linux-hardware.org/?probe=a16e963c10) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8bc0a29b23](https://linux-hardware.org/?probe=8bc0a29b23) | Apr 26, 2023 |
| HP            | EliteBook 840 G3            | [1413437b1f](https://linux-hardware.org/?probe=1413437b1f) | Apr 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [fe2d361db9](https://linux-hardware.org/?probe=fe2d361db9) | Apr 25, 2023 |
| Dell          | Precision 7770              | [e9208415d5](https://linux-hardware.org/?probe=e9208415d5) | Apr 24, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [3d88744f22](https://linux-hardware.org/?probe=3d88744f22) | Apr 20, 2023 |
| Dell          | Latitude 7420               | [480290fd34](https://linux-hardware.org/?probe=480290fd34) | Apr 19, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [21c928caeb](https://linux-hardware.org/?probe=21c928caeb) | Apr 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [1c99075a1d](https://linux-hardware.org/?probe=1c99075a1d) | Apr 16, 2023 |
| Toshiba       | Satellite L850              | [2fd09b6ba5](https://linux-hardware.org/?probe=2fd09b6ba5) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| HP            | OMEN by Laptop              | [8a1ef40351](https://linux-hardware.org/?probe=8a1ef40351) | Apr 15, 2023 |
| Dell          | Inspiron 5415               | [83ec457b1d](https://linux-hardware.org/?probe=83ec457b1d) | Apr 14, 2023 |
| Dell          | Inspiron 5415               | [ccf77bf033](https://linux-hardware.org/?probe=ccf77bf033) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [2ecd45a19e](https://linux-hardware.org/?probe=2ecd45a19e) | Apr 13, 2023 |
| Acer          | Aspire one                  | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Dell          | Precision 7770              | [5091c10fa2](https://linux-hardware.org/?probe=5091c10fa2) | Apr 11, 2023 |
| HUAWEI        | KPL-W0X                     | [2cf04d07fb](https://linux-hardware.org/?probe=2cf04d07fb) | Apr 09, 2023 |
| HP            | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [3125aa5d21](https://linux-hardware.org/?probe=3125aa5d21) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | [c1f70c64ad](https://linux-hardware.org/?probe=c1f70c64ad) | Apr 01, 2023 |
| Dell          | XPS 15 9570                 | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Dell          | XPS 13 9305                 | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| HP            | EliteBook 745 G6            | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| Dell          | Latitude 7480               | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP            | EliteBook 745 G6            | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | EliteBook 8570p             | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| HP            | ZBook 17 G3                 | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Unknown       | Unknown                     | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs     | StarBook                    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Precision 7770              | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell          | Precision 7770              | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell          | Precision 7770              | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| Dell          | Precision 7770              | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| Dell          | Precision 7770              | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| IBM           | ThinkPad T41 23737JU        | [5495bd2109](https://linux-hardware.org/?probe=5495bd2109) | Mar 03, 2023 |
| Apple         | MacBookPro9,1               | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| MSI           | GS66 Stealth 10UE           | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| HP            | Laptop 17-ca1xxx            | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| MSI           | GS66 Stealth 10UE           | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Valve         | Jupiter                     | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| MSI           | GS66 Stealth 10UE           | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | Victus by Gaming Laptop ... | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Alienware     | 17                          | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| Dell          | Precision 7770              | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Valve         | Jupiter                     | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| Unknown       | Unknown                     | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| MSI           | GS66 Stealth 10UE           | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Timi          | RedmiBook Pro 15S           | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | [aedfc67444](https://linux-hardware.org/?probe=aedfc67444) | Feb 12, 2023 |
| Unknown       | Unknown                     | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| Apple         | MacBookPro10,2              | [85b07c179c](https://linux-hardware.org/?probe=85b07c179c) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | [238c7a2c08](https://linux-hardware.org/?probe=238c7a2c08) | Feb 09, 2023 |
| Dell          | Precision 7770              | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Valve         | Jupiter                     | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| Valve         | Jupiter                     | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [37d0cc301b](https://linux-hardware.org/?probe=37d0cc301b) | Feb 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [a08ee9b387](https://linux-hardware.org/?probe=a08ee9b387) | Feb 03, 2023 |
| Dell          | Precision 7770              | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| MSI           | GP60 2PE                    | [a1bb8934a0](https://linux-hardware.org/?probe=a1bb8934a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Sony          | PCG-GRT230(UC)              | [0a7c76da78](https://linux-hardware.org/?probe=0a7c76da78) | Jan 30, 2023 |
| Google        | Helios                      | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [f71299a9c6](https://linux-hardware.org/?probe=f71299a9c6) | Jan 27, 2023 |
| Dell          | XPS 9320                    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Dell          | Latitude 5530               | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 7770              | [47044d362f](https://linux-hardware.org/?probe=47044d362f) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| HP            | Victus by Gaming Laptop ... | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Dell          | XPS 9320                    | [ebe686793d](https://linux-hardware.org/?probe=ebe686793d) | Jan 21, 2023 |
| Dell          | XPS 9320                    | [706152a268](https://linux-hardware.org/?probe=706152a268) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | [d37b338c87](https://linux-hardware.org/?probe=d37b338c87) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | [413cd3b7cf](https://linux-hardware.org/?probe=413cd3b7cf) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [753a61e1de](https://linux-hardware.org/?probe=753a61e1de) | Jan 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | [b14d57e1a3](https://linux-hardware.org/?probe=b14d57e1a3) | Jan 19, 2023 |
| Dell          | Precision 7720              | [9a00916b91](https://linux-hardware.org/?probe=9a00916b91) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Schenker      | XMG PRO (E22)               | [475e812e56](https://linux-hardware.org/?probe=475e812e56) | Jan 19, 2023 |
| Dell          | Latitude 5410               | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| Dell          | Precision 7720              | [f8e1c53257](https://linux-hardware.org/?probe=f8e1c53257) | Jan 16, 2023 |
| MSI           | Bravo 15 B5DD               | [8e35281ea5](https://linux-hardware.org/?probe=8e35281ea5) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [4fe502c977](https://linux-hardware.org/?probe=4fe502c977) | Jan 10, 2023 |
| Google        | Sasuke                      | [aa3a09aaef](https://linux-hardware.org/?probe=aa3a09aaef) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | [0dbae6cda4](https://linux-hardware.org/?probe=0dbae6cda4) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | [bca9343f96](https://linux-hardware.org/?probe=bca9343f96) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Acer          | TravelMate B115-M           | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| Dell          | Precision 7720              | [59813a7461](https://linux-hardware.org/?probe=59813a7461) | Jan 03, 2023 |
| Lenovo        | ThinkPad W540 20BG0033RT    | [5cfa12cec1](https://linux-hardware.org/?probe=5cfa12cec1) | Dec 31, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [4b130212a2](https://linux-hardware.org/?probe=4b130212a2) | Dec 30, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0c7ced8708](https://linux-hardware.org/?probe=0c7ced8708) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| Dell          | Precision 7720              | [56db0ab146](https://linux-hardware.org/?probe=56db0ab146) | Dec 28, 2022 |
| Dell          | Precision 7720              | [e94a7bb989](https://linux-hardware.org/?probe=e94a7bb989) | Dec 28, 2022 |
| Dell          | G3 3500                     | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| System76      | Darter Pro                  | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| Dell          | G5 5505                     | [87f62bee87](https://linux-hardware.org/?probe=87f62bee87) | Dec 26, 2022 |
| Star Labs     | StarLite                    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Dell          | Vostro 5490                 | [f694fa24c8](https://linux-hardware.org/?probe=f694fa24c8) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [25cbb2c39a](https://linux-hardware.org/?probe=25cbb2c39a) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| HP            | 250 G7 Notebook PC          | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b9aed745da](https://linux-hardware.org/?probe=b9aed745da) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c7cea6dd19](https://linux-hardware.org/?probe=c7cea6dd19) | Dec 20, 2022 |
| Dell          | Inspiron 15 3511            | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | [3dc497faf1](https://linux-hardware.org/?probe=3dc497faf1) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| Acer          | Predator PH315-51           | [34676168fa](https://linux-hardware.org/?probe=34676168fa) | Dec 14, 2022 |
| Acer          | Predator PH315-51           | [0f9b4ae170](https://linux-hardware.org/?probe=0f9b4ae170) | Dec 14, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [7541ce9ac6](https://linux-hardware.org/?probe=7541ce9ac6) | Dec 11, 2022 |
| Star Labs     | StarLite                    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| HP            | ProBook 6570b               | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Star Labs     | StarLite                    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| Google        | Eve                         | [d78558c833](https://linux-hardware.org/?probe=d78558c833) | Dec 08, 2022 |
| Google        | Eve                         | [92d1d03fed](https://linux-hardware.org/?probe=92d1d03fed) | Dec 08, 2022 |
| Toshiba       | Satellite L50-B             | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9fec7bdfdc](https://linux-hardware.org/?probe=9fec7bdfdc) | Dec 04, 2022 |
| HP            | G62                         | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| Dell          | Inspiron 3501               | [f9379c4ffb](https://linux-hardware.org/?probe=f9379c4ffb) | Dec 01, 2022 |
| Unknown       | Unknown                     | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [d77cb5ebb0](https://linux-hardware.org/?probe=d77cb5ebb0) | Nov 30, 2022 |
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Acer          | Swift SF314-57              | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| Dell          | Inspiron N5010              | [8a94d169c5](https://linux-hardware.org/?probe=8a94d169c5) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | [fbe52d681e](https://linux-hardware.org/?probe=fbe52d681e) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Unknown       | Unknown                     | [f3222cf843](https://linux-hardware.org/?probe=f3222cf843) | Nov 16, 2022 |
| Unknown       | Unknown                     | [9217d900c4](https://linux-hardware.org/?probe=9217d900c4) | Nov 16, 2022 |
| Lenovo        | G50-30 80G0                 | [b870eb1d72](https://linux-hardware.org/?probe=b870eb1d72) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [cbd0b88f5f](https://linux-hardware.org/?probe=cbd0b88f5f) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | [0e9a1a51a5](https://linux-hardware.org/?probe=0e9a1a51a5) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9db585ddc5](https://linux-hardware.org/?probe=9db585ddc5) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| Dell          | Precision 5540              | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Acer          | Nitro AN515-58              | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| Dell          | G3 3500                     | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d238949b9f](https://linux-hardware.org/?probe=d238949b9f) | Nov 06, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| Acer          | Nitro AN515-43              | [8ca3bfde82](https://linux-hardware.org/?probe=8ca3bfde82) | Nov 02, 2022 |
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | G3 3500                     | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Dell          | Vostro 5490                 | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7800fc7b5b](https://linux-hardware.org/?probe=7800fc7b5b) | Oct 29, 2022 |
| Acer          | AOD257                      | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Dell          | Vostro 5490                 | [ac6587adbb](https://linux-hardware.org/?probe=ac6587adbb) | Oct 27, 2022 |
| Acer          | AOD257                      | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [a44f774778](https://linux-hardware.org/?probe=a44f774778) | Oct 27, 2022 |
| Dell          | Precision 5570              | [d74abc314b](https://linux-hardware.org/?probe=d74abc314b) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [9115752bd4](https://linux-hardware.org/?probe=9115752bd4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| Gigabyte      | G5 KD                       | [c0f91f7282](https://linux-hardware.org/?probe=c0f91f7282) | Oct 20, 2022 |
| Gigabyte      | G5 KD                       | [35db9f3cd8](https://linux-hardware.org/?probe=35db9f3cd8) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [4644a299f3](https://linux-hardware.org/?probe=4644a299f3) | Oct 18, 2022 |
| Dell          | Precision 7760              | [44b60a4fcf](https://linux-hardware.org/?probe=44b60a4fcf) | Oct 18, 2022 |
| Sony          | PCG-GRT230(UC)              | [b33a31225b](https://linux-hardware.org/?probe=b33a31225b) | Oct 18, 2022 |
| HP            | Laptop 14-dk1xxx            | [caf126d0af](https://linux-hardware.org/?probe=caf126d0af) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [41d3e4e97d](https://linux-hardware.org/?probe=41d3e4e97d) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | G3 3500                     | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | [f60fd55235](https://linux-hardware.org/?probe=f60fd55235) | Oct 16, 2022 |
| Dell          | G3 3500                     | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| HP            | EliteBook 830 G6            | [0dc42d7e5e](https://linux-hardware.org/?probe=0dc42d7e5e) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| IBM           | ThinkPad T42 2373K1U        | [934a3226e9](https://linux-hardware.org/?probe=934a3226e9) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Intel Clie... | LAPBC710                    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [99d95e9424](https://linux-hardware.org/?probe=99d95e9424) | Oct 09, 2022 |
| Valve         | Jupiter                     | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| Intel Clie... | LAPBC710                    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| HP            | Laptop 15-ra0xx             | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| Alienware     | x14                         | [ad37874de1](https://linux-hardware.org/?probe=ad37874de1) | Oct 05, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [ae4533cfd6](https://linux-hardware.org/?probe=ae4533cfd6) | Oct 03, 2022 |
| MSI           | GE66 Raider 11UE            | [0eb2e22fc1](https://linux-hardware.org/?probe=0eb2e22fc1) | Oct 03, 2022 |
| Sony          | PCG-GRT230(UC)              | [cab24d4c04](https://linux-hardware.org/?probe=cab24d4c04) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| Sony          | PCG-GRT230(UC)              | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| System76      | Gazelle Professional        | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| Dell          | G7 7588                     | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Timi          | TM1604                      | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Dell          | Latitude D410               | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| win elemen... | MoreFine S500+              | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Timi          | A35                         | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| Dell          | G3 3500                     | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Purism        | Librem 15 v4                | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| Timi          | A35                         | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Samsung       | 700G7C                      | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | [fa1566785a](https://linux-hardware.org/?probe=fa1566785a) | Aug 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Razer         | Blade 15 Studio Edition ... | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | GS63VR 6RF                  | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| HP            | EliteBook 2560p             | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Toshiba       | Satellite A200              | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| Timi          | RedmiBook 13                | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Dell          | Precision 7550              | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| AVITA         | NS14A6                      | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| Dell          | G3 3500                     | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | G3 3500                     | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| Dell          | XPS 17 9710                 | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Dell          | Inspiron 15 5510            | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | 1005HA                      | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| HP            | Laptop 14-dk1xxx            | [6f78dba14b](https://linux-hardware.org/?probe=6f78dba14b) | May 23, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Acer          | Aspire E5-571G              | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| HP            | ProBook 430 G7              | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Dell          | Vostro 5568                 | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| HP            | ZBook 15 G3                 | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| HP            | Laptop 15s-eq0xxx           | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| HP            | Pavilion Notebook           | [0f04e6b439](https://linux-hardware.org/?probe=0f04e6b439) | May 09, 2022 |
| HP            | 255 G8 Notebook PC          | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Dell          | Inspiron 1525               | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| Lenovo        | Yoga 2 13 20344             | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Acer          | Aspire E5-571G              | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| Dell          | Precision 3520              | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| Lenovo        | Yoga 2 13 20344             | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| HP            | ZBook 15 G3                 | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| Dell          | G3 3500                     | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Acer          | Aspire VX5-591G             | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | G5 5505                     | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| HP            | ProBook 6570b               | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | Precision 7560              | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| System76      | Gazelle                     | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| System76      | Gazelle                     | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| MSI           | GE66 Raider 11UE            | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| Timi          | A35                         | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [4b3bd32143](https://linux-hardware.org/?probe=4b3bd32143) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| Apple         | MacBookPro11,3              | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| MSI           | MS-7A34                     | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| Framework     | Laptop                      | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Framework     | Laptop                      | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Dell          | XPS 17 9710                 | [302433b9e3](https://linux-hardware.org/?probe=302433b9e3) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Timi          | RedmiBook Pro 15S           | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| Dell          | XPS 17 9710                 | [018fa00447](https://linux-hardware.org/?probe=018fa00447) | Feb 17, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | XPS 13 9310                 | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| Dell          | Inspiron 5515               | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| Samsung       | RC530/RC730                 | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [2f36ebcc7e](https://linux-hardware.org/?probe=2f36ebcc7e) | Jan 30, 2022 |
| MSI           | GS63VR 6RF                  | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| Dell          | Precision 7520              | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Dell          | XPS 15 9570                 | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [7e7edbe447](https://linux-hardware.org/?probe=7e7edbe447) | Jan 23, 2022 |
| HUAWEI        | HVY-WXX9                    | [3c430f09c4](https://linux-hardware.org/?probe=3c430f09c4) | Jan 23, 2022 |
| MSI           | GE73 Raider RGB 8RF         | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| Dell          | XPS 17 9710                 | [597fae9cb6](https://linux-hardware.org/?probe=597fae9cb6) | Jan 19, 2022 |
| Timi          | Mi Laptop Pro 15            | [65ce2eb070](https://linux-hardware.org/?probe=65ce2eb070) | Jan 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Apple         | MacBookPro6,2               | [93dfa22733](https://linux-hardware.org/?probe=93dfa22733) | Jan 17, 2022 |
| Dell          | Precision 3561              | [f5417a1852](https://linux-hardware.org/?probe=f5417a1852) | Jan 16, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2aa146518a](https://linux-hardware.org/?probe=2aa146518a) | Jan 16, 2022 |
| Apple         | MacBookPro6,2               | [e69fb99ebf](https://linux-hardware.org/?probe=e69fb99ebf) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [cdb65d6460](https://linux-hardware.org/?probe=cdb65d6460) | Jan 13, 2022 |
| Acer          | Swift SF314-59              | [175b161d3f](https://linux-hardware.org/?probe=175b161d3f) | Jan 11, 2022 |
| Samsung       | 700T1C                      | [349d306d37](https://linux-hardware.org/?probe=349d306d37) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [6b764029b7](https://linux-hardware.org/?probe=6b764029b7) | Jan 11, 2022 |
| Dell          | Inspiron 5402               | [60f264617e](https://linux-hardware.org/?probe=60f264617e) | Jan 11, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [5f92f3376e](https://linux-hardware.org/?probe=5f92f3376e) | Jan 11, 2022 |
| Acer          | Nitro AN515-54              | [d46da820e0](https://linux-hardware.org/?probe=d46da820e0) | Jan 10, 2022 |
| HUAWEI        | HVY-WXX9                    | [f6376ab7d5](https://linux-hardware.org/?probe=f6376ab7d5) | Jan 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [639c7cbb68](https://linux-hardware.org/?probe=639c7cbb68) | Jan 06, 2022 |
| Acer          | Aspire E5-571G              | [75edf90312](https://linux-hardware.org/?probe=75edf90312) | Jan 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [08b04c15d3](https://linux-hardware.org/?probe=08b04c15d3) | Jan 03, 2022 |
| Dell          | Precision 7560              | [158ff657e7](https://linux-hardware.org/?probe=158ff657e7) | Jan 02, 2022 |
| Timi          | RedmiBook 13                | [528d0d32b4](https://linux-hardware.org/?probe=528d0d32b4) | Jan 01, 2022 |
| Timi          | A35                         | [253959bb70](https://linux-hardware.org/?probe=253959bb70) | Dec 30, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| Dell          | XPS 17 9710                 | [ac139db0b3](https://linux-hardware.org/?probe=ac139db0b3) | Dec 27, 2021 |
| MSI           | Delta 15 A5EFK              | [e874b85848](https://linux-hardware.org/?probe=e874b85848) | Dec 26, 2021 |
| Lenovo        | ThinkPad T480s 20L7001MR... | [199482a1fe](https://linux-hardware.org/?probe=199482a1fe) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [913bb7bf0b](https://linux-hardware.org/?probe=913bb7bf0b) | Dec 25, 2021 |
| Timi          | A35                         | [66e9c6919d](https://linux-hardware.org/?probe=66e9c6919d) | Dec 24, 2021 |
| Apple         | MacBook10,1                 | [4b98d2c8ba](https://linux-hardware.org/?probe=4b98d2c8ba) | Dec 24, 2021 |
| Dell          | Inspiron 15 5510            | [060d274be1](https://linux-hardware.org/?probe=060d274be1) | Dec 24, 2021 |
| Dell          | XPS 15 9570                 | [1695a19b52](https://linux-hardware.org/?probe=1695a19b52) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2144a3a32c](https://linux-hardware.org/?probe=2144a3a32c) | Dec 23, 2021 |
| Dell          | Inspiron 15 5510            | [e4d91f5636](https://linux-hardware.org/?probe=e4d91f5636) | Dec 21, 2021 |
| Framework     | Laptop                      | [33bb6590a6](https://linux-hardware.org/?probe=33bb6590a6) | Dec 21, 2021 |
| Dell          | Inspiron 15 5510            | [2018752b06](https://linux-hardware.org/?probe=2018752b06) | Dec 21, 2021 |
| Acer          | Aspire E5-571G              | [201e93fd24](https://linux-hardware.org/?probe=201e93fd24) | Dec 20, 2021 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b03f7a8ab8](https://linux-hardware.org/?probe=b03f7a8ab8) | Dec 20, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [fbd0755545](https://linux-hardware.org/?probe=fbd0755545) | Dec 19, 2021 |
| Dell          | Latitude 5420               | [f8313f07c4](https://linux-hardware.org/?probe=f8313f07c4) | Dec 18, 2021 |
| Samsung       | 700T1C                      | [f63266db56](https://linux-hardware.org/?probe=f63266db56) | Dec 18, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [ce3508ebb4](https://linux-hardware.org/?probe=ce3508ebb4) | Dec 17, 2021 |
| HP            | EliteBook 830 G5            | [bf884733a1](https://linux-hardware.org/?probe=bf884733a1) | Dec 16, 2021 |
| HP            | EliteBook 830 G5            | [61d4bff2bd](https://linux-hardware.org/?probe=61d4bff2bd) | Dec 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [d94711b81b](https://linux-hardware.org/?probe=d94711b81b) | Dec 13, 2021 |
| Dell          | XPS 17 9710                 | [ade9c0e3ec](https://linux-hardware.org/?probe=ade9c0e3ec) | Dec 13, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee63a84605](https://linux-hardware.org/?probe=ee63a84605) | Dec 11, 2021 |
| Dell          | XPS 17 9710                 | [fd6cff7345](https://linux-hardware.org/?probe=fd6cff7345) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Acer          | Aspire E5-571G              | [53fb790458](https://linux-hardware.org/?probe=53fb790458) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [208868fbae](https://linux-hardware.org/?probe=208868fbae) | Dec 07, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | RC530/RC730                 | [6105853b97](https://linux-hardware.org/?probe=6105853b97) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| HP            | Laptop 15s-eq0xxx           | [86f5c0bc34](https://linux-hardware.org/?probe=86f5c0bc34) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | [e06c73ada9](https://linux-hardware.org/?probe=e06c73ada9) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [ad15be0510](https://linux-hardware.org/?probe=ad15be0510) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Timi          | A35                         | [d1461858c8](https://linux-hardware.org/?probe=d1461858c8) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8876123555](https://linux-hardware.org/?probe=8876123555) | Nov 26, 2021 |
| Timi          | A35                         | [ce66e74002](https://linux-hardware.org/?probe=ce66e74002) | Nov 25, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | [1bb2b21d60](https://linux-hardware.org/?probe=1bb2b21d60) | Nov 24, 2021 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [58684dd498](https://linux-hardware.org/?probe=58684dd498) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| SIEMENS       | SIMATIC Field PG M6         | [a0e1ef3935](https://linux-hardware.org/?probe=a0e1ef3935) | Nov 22, 2021 |
| HP            | Compaq 6730b (KE717AV)      | [71527b8152](https://linux-hardware.org/?probe=71527b8152) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [674bb00d63](https://linux-hardware.org/?probe=674bb00d63) | Nov 21, 2021 |
| Samsung       | N150P/N210P/N220P           | [47908fe107](https://linux-hardware.org/?probe=47908fe107) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| HP            | ProBook 430 G5              | [634b7c7102](https://linux-hardware.org/?probe=634b7c7102) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [05879919b0](https://linux-hardware.org/?probe=05879919b0) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5f0f191f13](https://linux-hardware.org/?probe=5f0f191f13) | Nov 16, 2021 |
| MOTILE        | M142                        | [d56931cbc6](https://linux-hardware.org/?probe=d56931cbc6) | Nov 15, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5c55a759db](https://linux-hardware.org/?probe=5c55a759db) | Nov 13, 2021 |
| HP            | EliteBook 745 G6            | [a4bc523c79](https://linux-hardware.org/?probe=a4bc523c79) | Nov 12, 2021 |
| HP            | EliteBook 745 G6            | [faa7680568](https://linux-hardware.org/?probe=faa7680568) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE000BGE    | [871e0a8d36](https://linux-hardware.org/?probe=871e0a8d36) | Nov 11, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [49148de6c4](https://linux-hardware.org/?probe=49148de6c4) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [531b838f59](https://linux-hardware.org/?probe=531b838f59) | Nov 09, 2021 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [8ea29d23df](https://linux-hardware.org/?probe=8ea29d23df) | Nov 09, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [97e66fa893](https://linux-hardware.org/?probe=97e66fa893) | Nov 09, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [efd3dadc76](https://linux-hardware.org/?probe=efd3dadc76) | Nov 08, 2021 |
| Dell          | Latitude E7440              | [96a92b3d98](https://linux-hardware.org/?probe=96a92b3d98) | Nov 04, 2021 |
| Samsung       | RC530/RC730                 | [a4d9d06231](https://linux-hardware.org/?probe=a4d9d06231) | Nov 02, 2021 |
| Dell          | Latitude 7490               | [ea64667f2c](https://linux-hardware.org/?probe=ea64667f2c) | Nov 01, 2021 |
| Dell          | Latitude 5520               | [49a6b5ef90](https://linux-hardware.org/?probe=49a6b5ef90) | Nov 01, 2021 |
| Purism        | librem_15v4                 | [f3e5eba0c2](https://linux-hardware.org/?probe=f3e5eba0c2) | Oct 31, 2021 |
| Purism        | librem_15v4                 | [c74129a618](https://linux-hardware.org/?probe=c74129a618) | Oct 31, 2021 |
| HP            | ProBook 455 G7              | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| ASUSTek       | X556URK                     | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| Dell          | Latitude E6530              | [fd1375d5f1](https://linux-hardware.org/?probe=fd1375d5f1) | Oct 28, 2021 |
| Dell          | Latitude E6530              | [f37394899f](https://linux-hardware.org/?probe=f37394899f) | Oct 28, 2021 |
| HP            | Pavilion Notebook           | [4b691f2884](https://linux-hardware.org/?probe=4b691f2884) | Oct 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [6105164e23](https://linux-hardware.org/?probe=6105164e23) | Oct 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8a34d739fd](https://linux-hardware.org/?probe=8a34d739fd) | Oct 25, 2021 |
| Timi          | RedmiBook 13 R              | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d2b877508b](https://linux-hardware.org/?probe=d2b877508b) | Oct 13, 2021 |
| Acer          | Aspire A515-55              | [437c8fb96b](https://linux-hardware.org/?probe=437c8fb96b) | Oct 12, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [10d09b7d77](https://linux-hardware.org/?probe=10d09b7d77) | Oct 12, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [d7a870e424](https://linux-hardware.org/?probe=d7a870e424) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [03350be971](https://linux-hardware.org/?probe=03350be971) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| Acer          | TravelMate P648-M           | [6e6d3fe55c](https://linux-hardware.org/?probe=6e6d3fe55c) | Oct 10, 2021 |
| IBM           | ThinkPad T43 2668Z3S        | [67510cc1aa](https://linux-hardware.org/?probe=67510cc1aa) | Oct 10, 2021 |
| Timi          | RedmiBook 13 R              | [e6c38e5b79](https://linux-hardware.org/?probe=e6c38e5b79) | Oct 10, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [a8ea4ccbef](https://linux-hardware.org/?probe=a8ea4ccbef) | Oct 06, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [666f9cb875](https://linux-hardware.org/?probe=666f9cb875) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3ad4e11bac](https://linux-hardware.org/?probe=3ad4e11bac) | Oct 06, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [18a2385458](https://linux-hardware.org/?probe=18a2385458) | Oct 06, 2021 |
| Samsung       | RC530/RC730                 | [931664ed89](https://linux-hardware.org/?probe=931664ed89) | Oct 04, 2021 |
| Timi          | Mi Laptop Pro 15            | [e2057e68dd](https://linux-hardware.org/?probe=e2057e68dd) | Oct 03, 2021 |
| ASUSTek       | Unknown                     | [9b357ee9bb](https://linux-hardware.org/?probe=9b357ee9bb) | Oct 01, 2021 |
| Dell          | Inspiron 5415               | [a265f8ea5c](https://linux-hardware.org/?probe=a265f8ea5c) | Oct 01, 2021 |
| Lenovo        | Legion 5P 15IMH05 82AW      | [fbade9e61e](https://linux-hardware.org/?probe=fbade9e61e) | Oct 01, 2021 |
| ASUSTek       | X555LJ                      | [dea4201e98](https://linux-hardware.org/?probe=dea4201e98) | Oct 01, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [27707fb954](https://linux-hardware.org/?probe=27707fb954) | Oct 01, 2021 |
| HP            | 255 G6 Notebook PC          | [9823c616ed](https://linux-hardware.org/?probe=9823c616ed) | Sep 30, 2021 |
| HP            | ProBook 430 G5              | [6ee2943500](https://linux-hardware.org/?probe=6ee2943500) | Sep 30, 2021 |
| Dell          | Inspiron 5577               | [f5ec85dd12](https://linux-hardware.org/?probe=f5ec85dd12) | Sep 29, 2021 |
| Dell          | Inspiron 5577               | [80e36f9785](https://linux-hardware.org/?probe=80e36f9785) | Sep 29, 2021 |
| Timi          | Mi Laptop Pro 15            | [de13c8f3fa](https://linux-hardware.org/?probe=de13c8f3fa) | Sep 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS1LN00    | [71d301cc84](https://linux-hardware.org/?probe=71d301cc84) | Sep 26, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [116e97036b](https://linux-hardware.org/?probe=116e97036b) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8b939aae88](https://linux-hardware.org/?probe=8b939aae88) | Sep 25, 2021 |
| ASUSTek       | GX501VIK                    | [b36bf17cc2](https://linux-hardware.org/?probe=b36bf17cc2) | Sep 24, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [f40c18c3b8](https://linux-hardware.org/?probe=f40c18c3b8) | Sep 23, 2021 |
| Samsung       | RC530/RC730                 | [4aa6a34c0c](https://linux-hardware.org/?probe=4aa6a34c0c) | Sep 23, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Lenovo        | B51-80 80LM                 | [320ab41cbb](https://linux-hardware.org/?probe=320ab41cbb) | Sep 17, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [4c18c08616](https://linux-hardware.org/?probe=4c18c08616) | Sep 15, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | [d406b31a3a](https://linux-hardware.org/?probe=d406b31a3a) | Sep 15, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [3d0115d011](https://linux-hardware.org/?probe=3d0115d011) | Sep 15, 2021 |
| Notebook      | P65xHP                      | [12a7ec2b86](https://linux-hardware.org/?probe=12a7ec2b86) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b1c5ad62b3](https://linux-hardware.org/?probe=b1c5ad62b3) | Sep 13, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 244       | 25.28%  |
| Gentoo 2.6     | 200       | 20.73%  |
| Gentoo 2.8     | 156       | 16.17%  |
| Gentoo 2.14    | 144       | 14.92%  |
| Gentoo 2.13    | 102       | 10.57%  |
| Gentoo 2.9     | 76        | 7.88%   |
| Gentoo 2.15    | 13        | 1.35%   |
| Gentoo         | 7         | 0.73%   |
| Gentoo 2.4.1   | 5         | 0.52%   |
| Gentoo 2.3     | 4         | 0.41%   |
| Gentoo 2.2     | 4         | 0.41%   |
| Gentoo 23      | 3         | 0.31%   |
| Gentoo Pelikan | 1         | 0.1%    |
| Gentoo 22      | 1         | 0.1%    |
| Gentoo 2022    | 1         | 0.1%    |
| Gentoo 20.04   | 1         | 0.1%    |
| Gentoo 2.1     | 1         | 0.1%    |
| Gentoo 1       | 1         | 0.1%    |
| Gentoo 0.5     | 1         | 0.1%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Gentoo | 828       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.27-gentoo           | 16        | 1.45%   |
| 5.10.61-gentoo           | 13        | 1.18%   |
| 5.4.38-gentoo            | 11        | 1%      |
| 5.15.80-gentoo-x86_64    | 10        | 0.91%   |
| 5.10.76-gentoo-r1        | 10        | 0.91%   |
| 5.4.80-gentoo-r1         | 9         | 0.82%   |
| 5.4.48-gentoo            | 9         | 0.82%   |
| 5.15.32-gentoo-r1        | 9         | 0.82%   |
| 6.1.57-gentoo-x86_64     | 7         | 0.64%   |
| 6.1.19-gentoo-x86_64     | 7         | 0.64%   |
| 5.15.80-gentoo           | 7         | 0.64%   |
| 5.4.97-gentoo            | 6         | 0.54%   |
| 5.15.75-gentoo-x86_64    | 6         | 0.54%   |
| 5.15.72-gentoo           | 6         | 0.54%   |
| 5.15.59-gentoo-x86_64    | 6         | 0.54%   |
| 5.10.76-gentoo-r1-x86_64 | 6         | 0.54%   |
| 5.10.52-gentoo           | 6         | 0.54%   |
| 5.10.27-gentoo-x86_64    | 6         | 0.54%   |
| 6.1.67-gentoo-dist       | 5         | 0.45%   |
| 6.1.57-gentoo            | 5         | 0.45%   |
| 6.1.46-gentoo            | 5         | 0.45%   |
| 6.1.41-gentoo-dist       | 5         | 0.45%   |
| 6.1.31-gentoo-dist       | 5         | 0.45%   |
| 6.1.19-gentoo            | 5         | 0.45%   |
| 6.1.12-gentoo-dist       | 5         | 0.45%   |
| 5.4.60-gentoo            | 5         | 0.45%   |
| 5.4.28-gentoo            | 5         | 0.45%   |
| 5.15.75-gentoo           | 5         | 0.45%   |
| 5.15.72-gentoo-x86_64    | 5         | 0.45%   |
| 5.15.52-gentoo           | 5         | 0.45%   |
| 5.15.32-gentoo-r1-x86_64 | 5         | 0.45%   |
| 5.10.61-gentoo-x86_64    | 5         | 0.45%   |
| 6.6.21-gentoo            | 4         | 0.36%   |
| 6.6.13-gentoo            | 4         | 0.36%   |
| 6.1.57-gentoo-dist       | 4         | 0.36%   |
| 5.8.0-gentoo-r1          | 4         | 0.36%   |
| 5.4.97-gentoo-x86_64     | 4         | 0.36%   |
| 5.4.48-gentoo-x86_64     | 4         | 0.36%   |
| 5.19.0-gentoo-x86_64     | 4         | 0.36%   |
| 5.15.88-gentoo-x86_64    | 4         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.27 | 25        | 2.28%   |
| 5.10.76 | 21        | 1.91%   |
| 5.4.48  | 20        | 1.82%   |
| 6.1.57  | 19        | 1.73%   |
| 5.10.61 | 19        | 1.73%   |
| 5.15.80 | 17        | 1.55%   |
| 5.15.32 | 17        | 1.55%   |
| 6.1.19  | 16        | 1.46%   |
| 5.4.38  | 16        | 1.46%   |
| 6.6.21  | 13        | 1.19%   |
| 6.6.13  | 13        | 1.19%   |
| 5.15.75 | 13        | 1.19%   |
| 5.15.72 | 13        | 1.19%   |
| 5.15.59 | 13        | 1.19%   |
| 6.1.31  | 12        | 1.09%   |
| 6.1.12  | 12        | 1.09%   |
| 5.4.97  | 12        | 1.09%   |
| 6.1.46  | 11        | 1%      |
| 5.4.80  | 11        | 1%      |
| 5.4.28  | 11        | 1%      |
| 5.15.52 | 11        | 1%      |
| 5.10.52 | 11        | 1%      |
| 6.1.67  | 10        | 0.91%   |
| 6.1.41  | 9         | 0.82%   |
| 6.1.38  | 9         | 0.82%   |
| 5.15.11 | 9         | 0.82%   |
| 6.0.0   | 8         | 0.73%   |
| 5.15.88 | 8         | 0.73%   |
| 5.15.41 | 8         | 0.73%   |
| 4.19.97 | 8         | 0.73%   |
| 5.4.72  | 7         | 0.64%   |
| 5.4.60  | 7         | 0.64%   |
| 5.19.0  | 7         | 0.64%   |
| 5.16.0  | 7         | 0.64%   |
| 5.15.69 | 7         | 0.64%   |
| 6.6.8   | 6         | 0.55%   |
| 6.6.0   | 6         | 0.55%   |
| 6.1.7   | 6         | 0.55%   |
| 6.1.53  | 6         | 0.55%   |
| 5.4.66  | 6         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 169       | 16.68%  |
| 6.1     | 134       | 13.23%  |
| 5.10    | 110       | 10.86%  |
| 5.4     | 102       | 10.07%  |
| 6.6     | 54        | 5.33%   |
| 4.19    | 33        | 3.26%   |
| 6.2     | 25        | 2.47%   |
| 6.0     | 25        | 2.47%   |
| 5.17    | 25        | 2.47%   |
| 5.16    | 25        | 2.47%   |
| 5.9     | 23        | 2.27%   |
| 5.6     | 22        | 2.17%   |
| 5.14    | 22        | 2.17%   |
| 6.5     | 21        | 2.07%   |
| 5.18    | 20        | 1.97%   |
| 5.8     | 19        | 1.88%   |
| 5.11    | 19        | 1.88%   |
| 5.12    | 17        | 1.68%   |
| 6.4     | 16        | 1.58%   |
| 5.7     | 16        | 1.58%   |
| 5.19    | 16        | 1.58%   |
| 6.8     | 14        | 1.38%   |
| 5.13    | 13        | 1.28%   |
| 6.7     | 12        | 1.18%   |
| 6.3     | 11        | 1.09%   |
| 4.14    | 8         | 0.79%   |
| 5.5     | 7         | 0.69%   |
| 5.3     | 5         | 0.49%   |
| 5.1     | 5         | 0.49%   |
| 4.4     | 5         | 0.49%   |
| 5.2     | 3         | 0.3%    |
| 4.9     | 3         | 0.3%    |
| 4.18    | 3         | 0.3%    |
| 5.0     | 2         | 0.2%    |
| 4.6     | 2         | 0.2%    |
| 4.12    | 2         | 0.2%    |
| 6.9     | 1         | 0.1%    |
| 4.5     | 1         | 0.1%    |
| 4.20    | 1         | 0.1%    |
| 4.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 803       | 96.98%  |
| i686   | 22        | 2.66%   |
| ppc    | 3         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 340       | 38.16%  |
| KDE5           | 200       | 22.45%  |
| GNOME          | 114       | 12.79%  |
| XFCE           | 74        | 8.31%   |
| MATE           | 26        | 2.92%   |
| KDE            | 26        | 2.92%   |
| DWM            | 22        | 2.47%   |
| LXQt           | 13        | 1.46%   |
| sway           | 11        | 1.23%   |
| Hyprland       | 11        | 1.23%   |
| LXDE           | 6         | 0.67%   |
| Xsession       | 5         | 0.56%   |
| i3             | 5         | 0.56%   |
| X-Cinnamon     | 4         | 0.45%   |
| bspwm          | 4         | 0.45%   |
| awesome        | 4         | 0.45%   |
| Trinity        | 3         | 0.34%   |
| openbox        | 3         | 0.34%   |
| Enlightenment  | 3         | 0.34%   |
| Cinnamon       | 3         | 0.34%   |
| KDE6           | 2         | 0.22%   |
| GNOME Classic  | 2         | 0.22%   |
| fluxbox        | 2         | 0.22%   |
| xmonad         | 1         | 0.11%   |
| ratpoison      | 1         | 0.11%   |
| qt5ct          | 1         | 0.11%   |
| LeftWM         | 1         | 0.11%   |
| ICEWM          | 1         | 0.11%   |
| i3-with-shmlog | 1         | 0.11%   |
| fvwm           | 1         | 0.11%   |
| dwl            | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 474       | 52.84%  |
| Wayland | 164       | 18.28%  |
| Unknown | 131       | 14.6%   |
| Tty     | 128       | 14.27%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 382       | 43.96%  |
| SDDM    | 249       | 28.65%  |
| LightDM | 101       | 11.62%  |
| GDM     | 82        | 9.44%   |
| SLiM    | 17        | 1.96%   |
| XDM     | 16        | 1.84%   |
| LXDM    | 7         | 0.81%   |
| GREETD  | 7         | 0.81%   |
| TDM     | 5         | 0.58%   |
| Ly      | 1         | 0.12%   |
| KDM     | 1         | 0.12%   |
| GDM3    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 333       | 38.01%  |
| Unknown    | 133       | 15.18%  |
| C.UTF8     | 83        | 9.47%   |
| en_GB      | 49        | 5.59%   |
| de_DE      | 41        | 4.68%   |
| ru_RU      | 38        | 4.34%   |
| fr_FR      | 24        | 2.74%   |
| C          | 24        | 2.74%   |
| cs_CZ      | 16        | 1.83%   |
| it_IT      | 14        | 1.6%    |
| en_AU      | 13        | 1.48%   |
| zh_CN      | 9         | 1.03%   |
| pl_PL      | 8         | 0.91%   |
| en_CA      | 8         | 0.91%   |
| es_ES      | 7         | 0.8%    |
| POSIX      | 6         | 0.68%   |
| pt_BR      | 5         | 0.57%   |
| es_AR      | 5         | 0.57%   |
| el_GR      | 5         | 0.57%   |
| de_CH      | 4         | 0.46%   |
| uk_UA      | 3         | 0.34%   |
| nl_NL      | 3         | 0.34%   |
| nl_BE      | 3         | 0.34%   |
| ja_JP      | 3         | 0.34%   |
| fr_CA      | 3         | 0.34%   |
| es_CL      | 3         | 0.34%   |
| en_IE      | 3         | 0.34%   |
| mi_NZ      | 2         | 0.23%   |
| es_MX      | 2         | 0.23%   |
| en_ZA      | 2         | 0.23%   |
| en_US.UTF8 | 2         | 0.23%   |
| en_MX      | 2         | 0.23%   |
| ca_ES      | 2         | 0.23%   |
| zh_TW      | 1         | 0.11%   |
| tr_TR.UTF8 | 1         | 0.11%   |
| tr_TR      | 1         | 0.11%   |
| sv_SE      | 1         | 0.11%   |
| ru_UA      | 1         | 0.11%   |
| ro_RO      | 1         | 0.11%   |
| lt_LT      | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 667       | 78.93%  |
| BIOS | 178       | 21.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 484       | 57.41%  |
| Btrfs    | 218       | 25.86%  |
| Xfs      | 48        | 5.69%   |
| F2fs     | 24        | 2.85%   |
| Unknown  | 23        | 2.73%   |
| Zfs      | 20        | 2.37%   |
| XXXXXXX  | 13        | 1.54%   |
| Reiserfs | 3         | 0.36%   |
| Bcachefs | 3         | 0.36%   |
| Overlay  | 2         | 0.24%   |
| Jfs      | 2         | 0.24%   |
| Ext3     | 2         | 0.24%   |
| Ext2     | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 718       | 85.68%  |
| MBR     | 79        | 9.43%   |
| Unknown | 41        | 4.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 657       | 76.48%  |
| Yes       | 202       | 23.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 589       | 69.29%  |
| Yes       | 261       | 30.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 230       | 27.78%  |
| Dell                | 140       | 16.91%  |
| Hewlett-Packard     | 122       | 14.73%  |
| ASUSTek Computer    | 93        | 11.23%  |
| Acer                | 47        | 5.68%   |
| MSI                 | 27        | 3.26%   |
| Apple               | 22        | 2.66%   |
| Timi                | 12        | 1.45%   |
| HUAWEI              | 12        | 1.45%   |
| Framework           | 10        | 1.21%   |
| Toshiba             | 9         | 1.09%   |
| TUXEDO              | 8         | 0.97%   |
| Samsung Electronics | 8         | 0.97%   |
| Unknown             | 8         | 0.97%   |
| Razer               | 6         | 0.72%   |
| Notebook            | 5         | 0.6%    |
| IBM                 | 5         | 0.6%    |
| Google              | 5         | 0.6%    |
| System76            | 4         | 0.48%   |
| Fujitsu             | 4         | 0.48%   |
| Star Labs           | 3         | 0.36%   |
| Sony                | 3         | 0.36%   |
| Chuwi               | 3         | 0.36%   |
| Alienware           | 3         | 0.36%   |
| win element         | 2         | 0.24%   |
| Valve               | 2         | 0.24%   |
| Schenker            | 2         | 0.24%   |
| Purism              | 2         | 0.24%   |
| Positivo            | 2         | 0.24%   |
| Medion              | 2         | 0.24%   |
| Jumper              | 2         | 0.24%   |
| Gigabyte Technology | 2         | 0.24%   |
| BANGHO              | 2         | 0.24%   |
| XMG                 | 1         | 0.12%   |
| Wortmann AG         | 1         | 0.12%   |
| TULPAR              | 1         | 0.12%   |
| SIEMENS             | 1         | 0.12%   |
| Seco                | 1         | 0.12%   |
| realme              | 1         | 0.12%   |
| PC Specialist       | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 15        | 1.81%   |
| Dell XPS 15 9570                           | 6         | 0.72%   |
| ASUS ROG Strix G513QY_G513QY               | 6         | 0.72%   |
| HP Pavilion Notebook                       | 5         | 0.6%    |
| HP OMEN by Laptop                          | 5         | 0.6%    |
| Dell XPS 13 9310                           | 5         | 0.6%    |
| HP Pavilion Gaming Laptop 15-ec1xxx        | 4         | 0.48%   |
| HP Laptop 14-dk1xxx                        | 4         | 0.48%   |
| Framework Laptop 13 (AMD Ryzen 7040Series) | 4         | 0.48%   |
| Framework Laptop (13th Gen Intel Core)     | 4         | 0.48%   |
| Dell XPS 17 9710                           | 4         | 0.48%   |
| Dell XPS 15 7590                           | 4         | 0.48%   |
| ASUS ROG Zephyrus G14 GA401II_GA401II      | 4         | 0.48%   |
| Timi RedmiBook Pro 15S                     | 3         | 0.36%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013GE       | 3         | 0.36%   |
| Lenovo Legion Y530-15ICH 81FV              | 3         | 0.36%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 3         | 0.36%   |
| HP Victus by Laptop 16-e0xxx               | 3         | 0.36%   |
| HP EliteBook 845 14 inch G10 Notebook PC   | 3         | 0.36%   |
| Dell XPS 9320                              | 3         | 0.36%   |
| Dell XPS 13 9370                           | 3         | 0.36%   |
| Dell XPS 13 9360                           | 3         | 0.36%   |
| Dell Precision 5480                        | 3         | 0.36%   |
| Dell Latitude E7440                        | 3         | 0.36%   |
| Dell Latitude 7390                         | 3         | 0.36%   |
| Dell G5 5505                               | 3         | 0.36%   |
| win element MoreFine S500+                 | 2         | 0.24%   |
| Valve Jupiter                              | 2         | 0.24%   |
| Toshiba Satellite C850D-118                | 2         | 0.24%   |
| Toshiba NB100                              | 2         | 0.24%   |
| Timi RedmiBook 13 R                        | 2         | 0.24%   |
| Star Labs StarBook                         | 2         | 0.24%   |
| Sony PCG-GRT230(UC)                        | 2         | 0.24%   |
| Notebook NS5x_NS7xPU                       | 2         | 0.24%   |
| MSI GS65 Stealth Thin 8RF                  | 2         | 0.24%   |
| MSI GS63VR 6RF                             | 2         | 0.24%   |
| MSI Delta 15 A5EFK                         | 2         | 0.24%   |
| Lenovo Yoga 2 13 20344                     | 2         | 0.24%   |
| Lenovo ThinkPad X13 Gen 3 21CM0024US       | 2         | 0.24%   |
| Lenovo ThinkPad T480 20L5CTO1WW            | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 147       | 17.75%  |
| Dell Latitude        | 47        | 5.68%   |
| Dell XPS             | 39        | 4.71%   |
| HP EliteBook         | 29        | 3.5%    |
| Lenovo IdeaPad       | 27        | 3.26%   |
| Acer Aspire          | 26        | 3.14%   |
| Lenovo Legion        | 25        | 3.02%   |
| HP Pavilion          | 23        | 2.78%   |
| HP Laptop            | 22        | 2.66%   |
| ASUS ROG             | 21        | 2.54%   |
| Dell Precision       | 20        | 2.42%   |
| Dell Inspiron        | 19        | 2.29%   |
| ASUS VivoBook        | 17        | 2.05%   |
| Unknown              | 15        | 1.81%   |
| HP ProBook           | 12        | 1.45%   |
| HP OMEN              | 12        | 1.45%   |
| Framework Laptop     | 10        | 1.21%   |
| ASUS ZenBook         | 10        | 1.21%   |
| Lenovo Yoga          | 9         | 1.09%   |
| Acer Swift           | 9         | 1.09%   |
| Toshiba Satellite    | 7         | 0.85%   |
| Timi RedmiBook       | 7         | 0.85%   |
| HP ZBook             | 7         | 0.85%   |
| ASUS ASUS            | 7         | 0.85%   |
| Acer Nitro           | 7         | 0.85%   |
| Razer Blade          | 6         | 0.72%   |
| Lenovo ThinkBook     | 5         | 0.6%    |
| HP Victus            | 5         | 0.6%    |
| Dell G5              | 5         | 0.6%    |
| Apple MacBookPro8    | 5         | 0.6%    |
| Apple MacBookPro11   | 5         | 0.6%    |
| IBM ThinkPad         | 4         | 0.48%   |
| Dell G3              | 4         | 0.48%   |
| ASUS TUF             | 4         | 0.48%   |
| TUXEDO Book          | 3         | 0.36%   |
| Timi Mi              | 3         | 0.36%   |
| HP 255               | 3         | 0.36%   |
| Fujitsu LIFEBOOK     | 3         | 0.36%   |
| Dell Vostro          | 3         | 0.36%   |
| win element MoreFine | 2         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 124       | 14.98%  |
| 2019    | 118       | 14.25%  |
| 2021    | 113       | 13.65%  |
| 2018    | 83        | 10.02%  |
| 2022    | 60        | 7.25%   |
| 2017    | 45        | 5.43%   |
| 2014    | 42        | 5.07%   |
| 2023    | 37        | 4.47%   |
| 2012    | 35        | 4.23%   |
| 2016    | 27        | 3.26%   |
| 2015    | 27        | 3.26%   |
| 2011    | 26        | 3.14%   |
| 2013    | 23        | 2.78%   |
| 2008    | 19        | 2.29%   |
| 2010    | 18        | 2.17%   |
| 2006    | 7         | 0.85%   |
| 2009    | 6         | 0.72%   |
| Unknown | 5         | 0.6%    |
| 2007    | 4         | 0.48%   |
| 2005    | 3         | 0.36%   |
| 2004    | 3         | 0.36%   |
| 2003    | 2         | 0.24%   |
| 2024    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 828       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 813       | 97.48%  |
| Enabled  | 21        | 2.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 816       | 98.55%  |
| Yes  | 12        | 1.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 194       | 22.77%  |
| 8.01-16.0   | 191       | 22.42%  |
| 4.01-8.0    | 152       | 17.84%  |
| 32.01-64.0  | 148       | 17.37%  |
| 3.01-4.0    | 51        | 5.99%   |
| 64.01-256.0 | 40        | 4.69%   |
| 24.01-32.0  | 34        | 3.99%   |
| 1.01-2.0    | 17        | 2%      |
| 2.01-3.0    | 14        | 1.64%   |
| 0.51-1.0    | 8         | 0.94%   |
| 0.01-0.5    | 3         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 240       | 24.22%  |
| 2.01-3.0   | 172       | 17.36%  |
| 4.01-8.0   | 161       | 16.25%  |
| 3.01-4.0   | 120       | 12.11%  |
| 0.51-1.0   | 105       | 10.6%   |
| 0.01-0.5   | 100       | 10.09%  |
| 8.01-16.0  | 78        | 7.87%   |
| 16.01-24.0 | 12        | 1.21%   |
| 32.01-64.0 | 2         | 0.2%    |
| 24.01-32.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 594       | 69.47%  |
| 2      | 224       | 26.2%   |
| 3      | 28        | 3.27%   |
| 0      | 6         | 0.7%    |
| 4      | 3         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 710       | 85.13%  |
| Yes       | 124       | 14.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 647       | 77.21%  |
| No        | 191       | 22.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 817       | 98.67%  |
| No        | 11        | 1.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 726       | 86.84%  |
| No        | 110       | 13.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 163       | 19.29%  |
| Germany      | 100       | 11.83%  |
| Russia       | 76        | 8.99%   |
| France       | 43        | 5.09%   |
| China        | 39        | 4.62%   |
| UK           | 34        | 4.02%   |
| Canada       | 34        | 4.02%   |
| Czechia      | 28        | 3.31%   |
| Poland       | 27        | 3.2%    |
| Italy        | 24        | 2.84%   |
| Spain        | 22        | 2.6%    |
| Netherlands  | 22        | 2.6%    |
| Australia    | 17        | 2.01%   |
| Ukraine      | 13        | 1.54%   |
| Sweden       | 13        | 1.54%   |
| Turkey       | 12        | 1.42%   |
| Switzerland  | 11        | 1.3%    |
| Greece       | 10        | 1.18%   |
| Brazil       | 10        | 1.18%   |
| Belgium      | 9         | 1.07%   |
| Mexico       | 8         | 0.95%   |
| India        | 8         | 0.95%   |
| Finland      | 8         | 0.95%   |
| Japan        | 7         | 0.83%   |
| Hong Kong    | 7         | 0.83%   |
| Romania      | 6         | 0.71%   |
| Norway       | 6         | 0.71%   |
| Austria      | 6         | 0.71%   |
| Slovakia     | 5         | 0.59%   |
| Portugal     | 5         | 0.59%   |
| Indonesia    | 5         | 0.59%   |
| Belarus      | 5         | 0.59%   |
| Argentina    | 5         | 0.59%   |
| South Africa | 4         | 0.47%   |
| New Zealand  | 4         | 0.47%   |
| Lithuania    | 4         | 0.47%   |
| Hungary      | 4         | 0.47%   |
| Taiwan       | 3         | 0.36%   |
| Iran         | 3         | 0.36%   |
| Chile        | 3         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 29        | 3.09%   |
| Moscow            | 27        | 2.88%   |
| St Petersburg     | 12        | 1.28%   |
| Sydney            | 10        | 1.07%   |
| Athens            | 10        | 1.07%   |
| Amsterdam         | 10        | 1.07%   |
| Milan             | 9         | 0.96%   |
| Prague            | 8         | 0.85%   |
| Paris             | 8         | 0.85%   |
| Warsaw            | 7         | 0.75%   |
| Vancouver         | 7         | 0.75%   |
| New York          | 7         | 0.75%   |
| Munich            | 7         | 0.75%   |
| Kyiv              | 7         | 0.75%   |
| Guangzhou         | 7         | 0.75%   |
| Šlapanice        | 6         | 0.64%   |
| Madrid            | 6         | 0.64%   |
| Istanbul          | 6         | 0.64%   |
| Beijing           | 6         | 0.64%   |
| Weatherford       | 5         | 0.53%   |
| Minsk             | 5         | 0.53%   |
| Los Angeles       | 5         | 0.53%   |
| Cieszyn           | 5         | 0.53%   |
| Central           | 5         | 0.53%   |
| Toulouse          | 4         | 0.43%   |
| Stockholm         | 4         | 0.43%   |
| Shenzhen          | 4         | 0.43%   |
| Pittsburgh        | 4         | 0.43%   |
| Melbourne         | 4         | 0.43%   |
| London            | 4         | 0.43%   |
| Helsinki          | 4         | 0.43%   |
| Frankfurt am Main | 4         | 0.43%   |
| Wuelfrath         | 3         | 0.32%   |
| Vilnius           | 3         | 0.32%   |
| Vienna            | 3         | 0.32%   |
| Tehran            | 3         | 0.32%   |
| Taganrog          | 3         | 0.32%   |
| Sun Prairie       | 3         | 0.32%   |
| Seattle           | 3         | 0.32%   |
| San Jose          | 3         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 259       | 427    | 24.18%  |
| WDC                            | 112       | 156    | 10.46%  |
| SanDisk                        | 78        | 112    | 7.28%   |
| SK hynix                       | 73        | 94     | 6.82%   |
| Intel                          | 65        | 110    | 6.07%   |
| Seagate                        | 62        | 92     | 5.79%   |
| Toshiba                        | 53        | 61     | 4.95%   |
| Micron Technology              | 42        | 55     | 3.92%   |
| Unknown                        | 41        | 54     | 3.83%   |
| Kingston                       | 41        | 58     | 3.83%   |
| HGST                           | 31        | 36     | 2.89%   |
| KIOXIA                         | 24        | 32     | 2.24%   |
| Crucial                        | 20        | 24     | 1.87%   |
| Hitachi                        | 13        | 13     | 1.21%   |
| Phison Electronics             | 12        | 13     | 1.12%   |
| Apple                          | 11        | 13     | 1.03%   |
| A-DATA Technology              | 10        | 16     | 0.93%   |
| Kingston Technology Company    | 9         | 11     | 0.84%   |
| China                          | 7         | 18     | 0.65%   |
| Fujitsu                        | 6         | 8      | 0.56%   |
| OCZ                            | 5         | 9      | 0.47%   |
| Phison                         | 4         | 4      | 0.37%   |
| Micron/Crucial Technology      | 4         | 6      | 0.37%   |
| LITEON                         | 4         | 9      | 0.37%   |
| Transcend                      | 3         | 6      | 0.28%   |
| Solid State Storage Technology | 3         | 3      | 0.28%   |
| Netac                          | 3         | 3      | 0.28%   |
| LITEONIT                       | 3         | 4      | 0.28%   |
| Lenovo                         | 3         | 5      | 0.28%   |
| IBM/Hitachi                    | 3         | 4      | 0.28%   |
| Yangtze Memory Technologies    | 2         | 2      | 0.19%   |
| XPG                            | 2         | 3      | 0.19%   |
| Union Memory                   | 2         | 5      | 0.19%   |
| Solid State Storage            | 2         | 2      | 0.19%   |
| Plextor                        | 2         | 2      | 0.19%   |
| MyDigitalSSD                   | 2         | 2      | 0.19%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.19%   |
| Lexar                          | 2         | 2      | 0.19%   |
| KIOXIA-EXCERIA                 | 2         | 5      | 0.19%   |
| Intenso                        | 2         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 40        | 3.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 28        | 2.44%   |
| HGST HTS721010A9E630 1TB                           | 20        | 1.74%   |
| Samsung SSD 980 1TB                                | 11        | 0.96%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 10        | 0.87%   |
| Intel SSDPEKNW010T8 1TB                            | 10        | 0.87%   |
| Intel SSDPEKNU512GZ 512GB                          | 10        | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB                     | 9         | 0.78%   |
| Samsung SSD 860 EVO 500GB                          | 8         | 0.7%    |
| Samsung SSD 850 EVO 250GB                          | 8         | 0.7%    |
| Samsung MZVLB512HBJQ-000L2 512GB                   | 8         | 0.7%    |
| Intel SSD 660P Series 1024GB                       | 8         | 0.7%    |
| Unknown MMC Card  128GB                            | 7         | 0.61%   |
| Toshiba MQ04ABF100 1TB                             | 7         | 0.61%   |
| Seagate ST1000LM049-2GH172 1TB                     | 7         | 0.61%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 7         | 0.61%   |
| Unknown MMC Card  32GB                             | 6         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 6         | 0.52%   |
| Sandisk WD Black SN850 512GB                       | 6         | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                     | 6         | 0.52%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 6         | 0.52%   |
| KIOXIA KBG40ZNV512G 512GB                          | 6         | 0.52%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                   | 5         | 0.44%   |
| Unknown MMC Card  16GB                             | 5         | 0.44%   |
| SK hynix PC711 NVMe 1TB                            | 5         | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 5         | 0.44%   |
| Samsung SSD 980 PRO 2TB                            | 5         | 0.44%   |
| Samsung SSD 860 EVO 1TB                            | 5         | 0.44%   |
| Samsung NVMe SSD Drive 512GB                       | 5         | 0.44%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.44%   |
| Kingston SA400S37240G 240GB SSD                    | 5         | 0.44%   |
| HGST HTS541010A9E680 1TB                           | 5         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 4         | 0.35%   |
| WDC WDS100T2B0C-00PXH0 1TB                         | 4         | 0.35%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB               | 4         | 0.35%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                 | 4         | 0.35%   |
| Unknown MMC Card  64GB                             | 4         | 0.35%   |
| Toshiba MQ01ABF050 500GB                           | 4         | 0.35%   |
| Toshiba MQ01ABD100 1TB                             | 4         | 0.35%   |
| Toshiba KXG50ZNV512G NVMe 512GB                    | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 59        | 89     | 31.89%  |
| WDC                 | 42        | 49     | 22.7%   |
| HGST                | 31        | 36     | 16.76%  |
| Toshiba             | 26        | 30     | 14.05%  |
| Hitachi             | 13        | 13     | 7.03%   |
| Fujitsu             | 6         | 8      | 3.24%   |
| IBM/Hitachi         | 3         | 4      | 1.62%   |
| Teleplan            | 1         | 4      | 0.54%   |
| Samsung Electronics | 1         | 2      | 0.54%   |
| HGST HTS            | 1         | 1      | 0.54%   |
| ASMT                | 1         | 2      | 0.54%   |
| Apple               | 1         | 1      | 0.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 85        | 127    | 28.24%  |
| SanDisk             | 31        | 44     | 10.3%   |
| Kingston            | 25        | 36     | 8.31%   |
| WDC                 | 19        | 35     | 6.31%   |
| Crucial             | 17        | 21     | 5.65%   |
| Intel               | 14        | 15     | 4.65%   |
| SK hynix            | 13        | 14     | 4.32%   |
| Micron Technology   | 9         | 14     | 2.99%   |
| A-DATA Technology   | 9         | 15     | 2.99%   |
| Apple               | 8         | 9      | 2.66%   |
| Toshiba             | 7         | 8      | 2.33%   |
| China               | 7         | 18     | 2.33%   |
| OCZ                 | 5         | 9      | 1.66%   |
| Netac               | 3         | 3      | 1%      |
| LITEONIT            | 3         | 4      | 1%      |
| Transcend           | 2         | 5      | 0.66%   |
| Seagate             | 2         | 2      | 0.66%   |
| Plextor             | 2         | 2      | 0.66%   |
| MyDigitalSSD        | 2         | 2      | 0.66%   |
| Lexar               | 2         | 2      | 0.66%   |
| Intenso             | 2         | 3      | 0.66%   |
| GOODRAM             | 2         | 2      | 0.66%   |
| Dogfish             | 2         | 2      | 0.66%   |
| Unknown             | 2         | 3      | 0.66%   |
| Zheino              | 1         | 1      | 0.33%   |
| XrayDisk            | 1         | 1      | 0.33%   |
| Verbatim            | 1         | 1      | 0.33%   |
| StoreJet            | 1         | 1      | 0.33%   |
| Star                | 1         | 2      | 0.33%   |
| SPCC                | 1         | 1      | 0.33%   |
| Smartbuy            | 1         | 1      | 0.33%   |
| ShanDianZhe         | 1         | 2      | 0.33%   |
| SCCTS-603-256G      | 1         | 1      | 0.33%   |
| RevuAhn             | 1         | 1      | 0.33%   |
| PNY                 | 1         | 2      | 0.33%   |
| Phison              | 1         | 1      | 0.33%   |
| Mushkin             | 1         | 1      | 0.33%   |
| LITEON              | 1         | 4      | 0.33%   |
| Lite-On             | 1         | 1      | 0.33%   |
| Linux               | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 508       | 818    | 50.8%   |
| SSD     | 272       | 432    | 27.2%   |
| HDD     | 178       | 239    | 17.8%   |
| MMC     | 39        | 50     | 3.9%    |
| Unknown | 3         | 5      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 508       | 813    | 52.92%  |
| SATA | 389       | 650    | 40.52%  |
| MMC  | 39        | 50     | 4.06%   |
| SAS  | 24        | 31     | 2.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 268       | 413    | 59.42%  |
| 0.51-1.0   | 156       | 215    | 34.59%  |
| 1.01-2.0   | 24        | 40     | 5.32%   |
| 3.01-4.0   | 2         | 2      | 0.44%   |
| 4.01-10.0  | 1         | 1      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 222       | 24.78%  |
| 101-250        | 197       | 21.99%  |
| 501-1000       | 171       | 19.08%  |
| 1001-2000      | 99        | 11.05%  |
| 1-20           | 48        | 5.36%   |
| 51-100         | 48        | 5.36%   |
| Unknown        | 47        | 5.25%   |
| More than 3000 | 27        | 3.01%   |
| 21-50          | 20        | 2.23%   |
| 2001-3000      | 17        | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 225       | 23.51%  |
| 21-50          | 174       | 18.18%  |
| 101-250        | 154       | 16.09%  |
| 251-500        | 128       | 13.38%  |
| 51-100         | 110       | 11.49%  |
| 501-1000       | 78        | 8.15%   |
| Unknown        | 47        | 4.91%   |
| 1001-2000      | 26        | 2.72%   |
| 2001-3000      | 8         | 0.84%   |
| More than 3000 | 7         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Notebooks | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                                       | 6         | 7      | 7.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                             | 3         | 10     | 3.61%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD                        | 3         | 3      | 3.61%   |
| WDC WD10JPVX-75JC3T0 1TB                                       | 2         | 2      | 2.41%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                           | 2         | 3      | 2.41%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                          | 2         | 2      | 2.41%   |
| Seagate ST2000LX001-1RG174 2TB                                 | 2         | 2      | 2.41%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                            | 2         | 2      | 2.41%   |
| Samsung Electronics SSD 850 EVO 1TB                            | 2         | 2      | 2.41%   |
| HGST HTS725050A7E630 500GB                                     | 2         | 3      | 2.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                               | 1         | 1      | 1.2%    |
| WDC WDS120G2G0B-00EPW0 120GB SSD                               | 1         | 1      | 1.2%    |
| WDC WD1600BEVS-22RST0 160GB                                    | 1         | 1      | 1.2%    |
| WDC WD10SPZX-24Z10T0 1TB                                       | 1         | 1      | 1.2%    |
| WDC WD10EZEX-08M2NA0 1TB                                       | 1         | 2      | 1.2%    |
| WDC WD Green 2.5 240GB                                         | 1         | 1      | 1.2%    |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD                       | 1         | 1      | 1.2%    |
| Toshiba MQ02ABD100H 1TB                                        | 1         | 1      | 1.2%    |
| Toshiba MQ01ABF050 500GB                                       | 1         | 1      | 1.2%    |
| Toshiba MK6008GAH 64GB                                         | 1         | 2      | 1.2%    |
| Toshiba MK5056GSY 500GB                                        | 1         | 1      | 1.2%    |
| Toshiba MK4026GAX 40GB                                         | 1         | 1      | 1.2%    |
| Toshiba MK1629GSG 160GB                                        | 1         | 1      | 1.2%    |
| SK hynix SH920 mSATA 256GB SSD                                 | 1         | 1      | 1.2%    |
| SK hynix SC210 mSATA 128GB SSD                                 | 1         | 1      | 1.2%    |
| SK hynix BC501 NVMe Solid State Drive 512GB                    | 1         | 3      | 1.2%    |
| Seagate ST9750420AS 752GB                                      | 1         | 1      | 1.2%    |
| Seagate ST9100824AS 100GB                                      | 1         | 1      | 1.2%    |
| Seagate ST320LT007-9ZV142 320GB                                | 1         | 1      | 1.2%    |
| Seagate ST1000LM049-2GH172 1TB                                 | 1         | 1      | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB                                 | 1         | 2      | 1.2%    |
| Seagate ST1000LM014-1EJ164 1TB                                 | 1         | 1      | 1.2%    |
| SanDisk SSD PLUS 480GB                                         | 1         | 1      | 1.2%    |
| SanDisk SD9SN8W 128GB SSD                                      | 1         | 1      | 1.2%    |
| SanDisk SD7SB2Q512G1001 512GB SSD                              | 1         | 1      | 1.2%    |
| Samsung Electronics SSD SM841 mSATA 512GB                      | 1         | 1      | 1.2%    |
| Samsung Electronics SSD 870 EVO 2TB                            | 1         | 1      | 1.2%    |
| Samsung Electronics PM9A1 NVMe 2048GB                          | 1         | 1      | 1.2%    |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1      | 1.2%    |
| Samsung Electronics HM160HC 160GB                              | 1         | 1      | 1.2%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 11        | 19     | 13.41%  |
| HGST                        | 11        | 13     | 13.41%  |
| WDC                         | 8         | 9      | 9.76%   |
| Toshiba                     | 7         | 8      | 8.54%   |
| SK hynix                    | 7         | 10     | 8.54%   |
| Samsung Electronics         | 7         | 7      | 8.54%   |
| Intel                       | 6         | 6      | 7.32%   |
| Hitachi                     | 5         | 5      | 6.1%    |
| SanDisk                     | 4         | 5      | 4.88%   |
| Kingston                    | 3         | 3      | 3.66%   |
| Fujitsu                     | 3         | 3      | 3.66%   |
| IBM/Hitachi                 | 2         | 2      | 2.44%   |
| A-DATA Technology           | 2         | 2      | 2.44%   |
| Realtek Semiconductor       | 1         | 2      | 1.22%   |
| OCZ                         | 1         | 1      | 1.22%   |
| LITEON                      | 1         | 4      | 1.22%   |
| Kingston Technology Company | 1         | 1      | 1.22%   |
| HGST HTS                    | 1         | 1      | 1.22%   |
| Crucial                     | 1         | 1      | 1.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 19     | 24.44%  |
| HGST                | 11        | 13     | 24.44%  |
| Toshiba             | 6         | 7      | 13.33%  |
| WDC                 | 5         | 6      | 11.11%  |
| Hitachi             | 5         | 5      | 11.11%  |
| Fujitsu             | 3         | 3      | 6.67%   |
| IBM/Hitachi         | 2         | 2      | 4.44%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| HGST HTS            | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 57     | 54.88%  |
| SSD  | 28        | 32     | 34.15%  |
| NVMe | 9         | 13     | 10.98%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB | 1         | 1      | 33.33%  |
| Samsung Electronics SSD 980 1TB  | 1         | 1      | 33.33%  |
| Hitachi HTS721010G9SA00 100GB    | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 714       | 1283   | 78.81%  |
| Detected | 109       | 156    | 12.03%  |
| Malfunc  | 80        | 102    | 8.83%   |
| Failed   | 3         | 3      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 458       | 42.45%  |
| Samsung Electronics              | 196       | 18.16%  |
| AMD                              | 105       | 9.73%   |
| SanDisk                          | 93        | 8.62%   |
| SK hynix                         | 60        | 5.56%   |
| Micron Technology                | 33        | 3.06%   |
| Kingston Technology Company      | 26        | 2.41%   |
| KIOXIA                           | 24        | 2.22%   |
| Toshiba America Info Systems     | 23        | 2.13%   |
| Phison Electronics               | 15        | 1.39%   |
| Micron/Crucial Technology        | 6         | 0.56%   |
| Solid State Storage Technology   | 5         | 0.46%   |
| ADATA Technology                 | 4         | 0.37%   |
| Yangtze Memory Technologies      | 3         | 0.28%   |
| Union Memory (Shenzhen)          | 3         | 0.28%   |
| Lite-On Technology               | 3         | 0.28%   |
| INNOGRIT                         | 3         | 0.28%   |
| Silicon Motion                   | 2         | 0.19%   |
| Silicon Integrated Systems [SiS] | 2         | 0.19%   |
| Seagate Technology               | 2         | 0.19%   |
| Nvidia                           | 2         | 0.19%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.19%   |
| Lenovo                           | 2         | 0.19%   |
| JMicron Technology               | 2         | 0.19%   |
| Apple                            | 2         | 0.19%   |
| Transcend                        | 1         | 0.09%   |
| Shenzhen Longsys Electronics     | 1         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 101       | 8.92%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 97        | 8.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 51        | 4.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 44        | 3.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 42        | 3.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 40        | 3.53%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 34        | 3%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 30        | 2.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 29        | 2.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 29        | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 27        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 24        | 2.12%   |
| Intel SSD 660P Series                                                          | 23        | 2.03%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 20        | 1.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 1.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 17        | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.41%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 15        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 1.06%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 12        | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 12        | 1.06%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 11        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 10        | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 10        | 0.88%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 9         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 9         | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 8         | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 8         | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 8         | 0.71%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 7         | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.62%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 6         | 0.53%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 6         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 514       | 48.08%  |
| SATA | 440       | 41.16%  |
| RAID | 78        | 7.3%    |
| IDE  | 37        | 3.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 601       | 72.58%  |
| AMD          | 224       | 27.05%  |
| PowerBook5,6 | 1         | 0.12%   |
| PowerBook5,4 | 1         | 0.12%   |
| PowerBook3,4 | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 2.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 22        | 2.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 2.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 2.17%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 1.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 1.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 14        | 1.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.69%   |
| Intel 12th Gen Core i7-12700H                 | 12        | 1.45%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 12        | 1.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 1.33%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 11        | 1.33%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 1.33%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 1.08%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 8         | 0.96%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 8         | 0.96%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 0.96%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 7         | 0.84%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.84%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 7         | 0.84%   |
| Intel 12th Gen Core i7-1260P                  | 7         | 0.84%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 7         | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 0.84%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.72%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 6         | 0.72%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 0.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 0.72%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics    | 6         | 0.72%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 6         | 0.72%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 0.72%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 239       | 28.86%  |
| Intel Core i5           | 146       | 17.63%  |
| Other                   | 114       | 13.77%  |
| AMD Ryzen 7             | 94        | 11.35%  |
| AMD Ryzen 5             | 44        | 5.31%   |
| AMD Ryzen 7 PRO         | 32        | 3.86%   |
| AMD Ryzen 9             | 17        | 2.05%   |
| Intel Core 2 Duo        | 16        | 1.93%   |
| Intel Celeron           | 16        | 1.93%   |
| Intel Core i3           | 15        | 1.81%   |
| Intel Atom              | 12        | 1.45%   |
| Intel Core i9           | 10        | 1.21%   |
| Intel Pentium M         | 9         | 1.09%   |
| Intel Pentium           | 9         | 1.09%   |
| AMD Ryzen 3             | 8         | 0.97%   |
| Intel Xeon              | 6         | 0.72%   |
| AMD Ryzen 5 PRO         | 6         | 0.72%   |
| AMD A6                  | 6         | 0.72%   |
| Intel Pentium Silver    | 3         | 0.36%   |
| Intel Core m3           | 3         | 0.36%   |
| AMD A8                  | 3         | 0.36%   |
| Intel Pentium 4         | 2         | 0.24%   |
| Intel Genuine           | 2         | 0.24%   |
| Intel Core Duo          | 2         | 0.24%   |
| AMD E1                  | 2         | 0.24%   |
| AMD Athlon II           | 2         | 0.24%   |
| AMD Athlon              | 2         | 0.24%   |
| Intel Core 2            | 1         | 0.12%   |
| Intel Celeron M         | 1         | 0.12%   |
| AMD Turion II Dual-Core | 1         | 0.12%   |
| AMD E                   | 1         | 0.12%   |
| AMD Athlon Neo X2       | 1         | 0.12%   |
| AMD Athlon 64           | 1         | 0.12%   |
| AMD A12                 | 1         | 0.12%   |
| AMD A10                 | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 307       | 37.03%  |
| 2       | 191       | 23.04%  |
| 8       | 155       | 18.7%   |
| 6       | 102       | 12.3%   |
| 14      | 26        | 3.14%   |
| 1       | 25        | 3.02%   |
| 12      | 12        | 1.45%   |
| 10      | 4         | 0.48%   |
| 16      | 3         | 0.36%   |
| Unknown | 2         | 0.24%   |
| 24      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 826       | 99.76%  |
| Unknown | 2         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 714       | 85.82%  |
| 1       | 115       | 13.82%  |
| Unknown | 2         | 0.24%   |
| 4       | 1         | 0.12%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 801       | 96.74%  |
| 32-bit         | 24        | 2.9%    |
| Unknown        | 3         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 180       | 20.69%  |
| 0x906ea    | 51        | 5.86%   |
| 0x0a50000c | 42        | 4.83%   |
| 0x806ec    | 40        | 4.6%    |
| 0x806ea    | 35        | 4.02%   |
| 0x806c1    | 33        | 3.79%   |
| 0x206a7    | 27        | 3.1%    |
| 0x08600106 | 27        | 3.1%    |
| 0x306a9    | 24        | 2.76%   |
| 0x506e3    | 22        | 2.53%   |
| 0x806e9    | 21        | 2.41%   |
| 0xa0652    | 20        | 2.3%    |
| 0x806d1    | 19        | 2.18%   |
| 0x906e9    | 18        | 2.07%   |
| 0x40651    | 18        | 2.07%   |
| 0x08108109 | 18        | 2.07%   |
| 0x906a3    | 17        | 1.95%   |
| 0x406e3    | 16        | 1.84%   |
| 0x306c3    | 14        | 1.61%   |
| 0x08600103 | 14        | 1.61%   |
| 0x306d4    | 13        | 1.49%   |
| 0x906ed    | 11        | 1.26%   |
| 0x0a404102 | 11        | 1.26%   |
| 0x08608103 | 11        | 1.26%   |
| 0x08108102 | 11        | 1.26%   |
| 0xb06a2    | 10        | 1.15%   |
| 0x0a50000d | 10        | 1.15%   |
| 0x08600104 | 10        | 1.15%   |
| 0x30678    | 9         | 1.03%   |
| 0x806eb    | 7         | 0.8%    |
| 0x706e5    | 7         | 0.8%    |
| 0x0a704103 | 6         | 0.69%   |
| 0x6d8      | 5         | 0.57%   |
| 0x20655    | 4         | 0.46%   |
| 0x1067a    | 4         | 0.46%   |
| 0x706a8    | 3         | 0.34%   |
| 0x706a1    | 3         | 0.34%   |
| 0x6fb      | 3         | 0.34%   |
| 0x406c4    | 3         | 0.34%   |
| 0x20652    | 3         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 222       | 26.71%  |
| Zen 2            | 61        | 7.34%   |
| Unknown          | 59        | 7.1%    |
| Zen 3            | 58        | 6.98%   |
| Alderlake Hybrid | 44        | 5.29%   |
| Skylake          | 42        | 5.05%   |
| Haswell          | 42        | 5.05%   |
| TigerLake        | 41        | 4.93%   |
| Zen+             | 34        | 4.09%   |
| SandyBridge      | 32        | 3.85%   |
| Icelake          | 29        | 3.49%   |
| IvyBridge        | 28        | 3.37%   |
| CometLake        | 24        | 2.89%   |
| Broadwell        | 16        | 1.93%   |
| Silvermont       | 14        | 1.68%   |
| P6               | 14        | 1.68%   |
| Westmere         | 10        | 1.2%    |
| Penryn           | 9         | 1.08%   |
| Core             | 8         | 0.96%   |
| Bonnell          | 8         | 0.96%   |
| Goldmont plus    | 7         | 0.84%   |
| Zen              | 6         | 0.72%   |
| Steamroller      | 3         | 0.36%   |
| Excavator        | 3         | 0.36%   |
| Bobcat           | 3         | 0.36%   |
| Puma             | 2         | 0.24%   |
| NetBurst         | 2         | 0.24%   |
| K8 Hammer        | 2         | 0.24%   |
| K10 Llano        | 2         | 0.24%   |
| K10              | 2         | 0.24%   |
| Tremont          | 1         | 0.12%   |
| Jaguar           | 1         | 0.12%   |
| Gracemont        | 1         | 0.12%   |
| Goldmont         | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 543       | 49.27%  |
| Nvidia | 310       | 28.13%  |
| AMD    | 249       | 22.6%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 62        | 5.44%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 57        | 5%      |
| Intel UHD Graphics 620                                                        | 50        | 4.39%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 46        | 4.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 39        | 3.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 35        | 3.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 32        | 2.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 27        | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 27        | 2.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 24        | 2.11%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 23        | 2.02%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 23        | 2.02%   |
| Intel HD Graphics 530                                                         | 21        | 1.84%   |
| Intel HD Graphics 620                                                         | 20        | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 20        | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 19        | 1.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 18        | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 17        | 1.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 17        | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 16        | 1.4%    |
| AMD Rembrandt [Radeon 680M]                                                   | 16        | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 15        | 1.32%   |
| AMD Lucienne                                                                  | 15        | 1.32%   |
| Intel HD Graphics 630                                                         | 13        | 1.14%   |
| Intel HD Graphics 5500                                                        | 13        | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 12        | 1.05%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                        | 12        | 1.05%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 11        | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                 | 10        | 0.88%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 10        | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 10        | 0.88%   |
| AMD Phoenix1                                                                  | 9         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 8         | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                              | 8         | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 8         | 0.7%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 8         | 0.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 8         | 0.7%    |
| AMD Barcelo                                                                   | 8         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 7         | 0.61%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 7         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 294       | 34.96%  |
| Intel + Nvidia | 219       | 26.04%  |
| 1 x AMD        | 175       | 20.81%  |
| 1 x Nvidia     | 63        | 7.49%   |
| AMD + Nvidia   | 34        | 4.04%   |
| 2 x AMD        | 23        | 2.73%   |
| Intel + AMD    | 19        | 2.26%   |
| 2 x Intel      | 13        | 1.55%   |
| 2 x Nvidia     | 1         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 648       | 75.7%   |
| Proprietary | 175       | 20.44%  |
| Unknown     | 33        | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 493       | 57.26%  |
| 0.01-0.5   | 124       | 14.4%   |
| 1.01-2.0   | 87        | 10.1%   |
| 3.01-4.0   | 58        | 6.74%   |
| 0.51-1.0   | 38        | 4.41%   |
| 7.01-8.0   | 22        | 2.56%   |
| 5.01-6.0   | 22        | 2.56%   |
| 8.01-16.0  | 13        | 1.51%   |
| 2.01-3.0   | 4         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 180       | 18.29%  |
| BOE                     | 143       | 14.53%  |
| LG Display              | 118       | 11.99%  |
| Chimei Innolux          | 116       | 11.79%  |
| Samsung Electronics     | 74        | 7.52%   |
| Sharp                   | 59        | 6%      |
| Dell                    | 46        | 4.67%   |
| Apple                   | 25        | 2.54%   |
| Lenovo                  | 20        | 2.03%   |
| Goldstar                | 20        | 2.03%   |
| PANDA                   | 16        | 1.63%   |
| Chi Mei Optoelectronics | 16        | 1.63%   |
| CSO                     | 14        | 1.42%   |
| Hewlett-Packard         | 12        | 1.22%   |
| AOC                     | 10        | 1.02%   |
| BenQ                    | 9         | 0.91%   |
| Philips                 | 8         | 0.81%   |
| InfoVision              | 7         | 0.71%   |
| Acer                    | 7         | 0.71%   |
| Iiyama                  | 6         | 0.61%   |
| ASUSTek Computer        | 6         | 0.61%   |
| ViewSonic               | 5         | 0.51%   |
| TMX                     | 5         | 0.51%   |
| Ancor Communications    | 5         | 0.51%   |
| Eizo                    | 4         | 0.41%   |
| Sony                    | 3         | 0.3%    |
| MSI                     | 3         | 0.3%    |
| Mi                      | 3         | 0.3%    |
| HannStar                | 3         | 0.3%    |
| Toshiba                 | 2         | 0.2%    |
| RTK                     | 2         | 0.2%    |
| LGD                     | 2         | 0.2%    |
| LG Philips              | 2         | 0.2%    |
| HKC                     | 2         | 0.2%    |
| Gigabyte Technology     | 2         | 0.2%    |
| Fujitsu Siemens         | 2         | 0.2%    |
| CTO                     | 2         | 0.2%    |
| CMN                     | 2         | 0.2%    |
| BOE Technology Group    | 2         | 0.2%    |
| Unknown                 | 2         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.9%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 8         | 0.8%    |
| BOE LCD Monitor BOE0BCA 2256x1504 285x190mm 13.5-inch                    | 7         | 0.7%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 7         | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 0.6%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 5         | 0.5%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.5%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 5         | 0.5%    |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                    | 4         | 0.4%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 4         | 0.4%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 4         | 0.4%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 4         | 0.4%    |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                    | 4         | 0.4%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 4         | 0.4%    |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 4         | 0.4%    |
| AU Optronics LCD Monitor AUO2336 2560x1440 309x174mm 14.0-inch           | 4         | 0.4%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 3         | 0.3%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 3         | 0.3%    |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 3         | 0.3%    |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.3%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 3         | 0.3%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.3%    |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch             | 3         | 0.3%    |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.3%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 3         | 0.3%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.3%    |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                        | 3         | 0.3%    |
| Dell U2414H DELA0A3 1920x1080 527x296mm 23.8-inch                        | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 3         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.3%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 3         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 480       | 52.81%  |
| 1366x768 (WXGA)    | 87        | 9.57%   |
| 3840x2160 (4K)     | 59        | 6.49%   |
| 2560x1440 (QHD)    | 49        | 5.39%   |
| 1920x1200 (WUXGA)  | 30        | 3.3%    |
| 2560x1600          | 29        | 3.19%   |
| 1600x900 (HD+)     | 23        | 2.53%   |
| 3840x2400          | 19        | 2.09%   |
| 1280x800 (WXGA)    | 14        | 1.54%   |
| 3440x1440          | 12        | 1.32%   |
| 1680x1050 (WSXGA+) | 12        | 1.32%   |
| 1440x900 (WXGA+)   | 11        | 1.21%   |
| 2880x1800          | 10        | 1.1%    |
| 2256x1504          | 10        | 1.1%    |
| 1024x600           | 8         | 0.88%   |
| 1280x1024 (SXGA)   | 6         | 0.66%   |
| 3200x2000          | 5         | 0.55%   |
| 2160x1440          | 5         | 0.55%   |
| 3456x2160          | 3         | 0.33%   |
| 3200x1800 (QHD+)   | 3         | 0.33%   |
| 1280x854           | 3         | 0.33%   |
| 800x1280           | 2         | 0.22%   |
| 3840x1080          | 2         | 0.22%   |
| 2880x1620          | 2         | 0.22%   |
| 2560x1080          | 2         | 0.22%   |
| 2240x1400          | 2         | 0.22%   |
| 2048x1152          | 2         | 0.22%   |
| 1600x1200          | 2         | 0.22%   |
| Unknown            | 2         | 0.22%   |
| 5040x1080          | 1         | 0.11%   |
| 3840x1600          | 1         | 0.11%   |
| 3840x1200          | 1         | 0.11%   |
| 3840x1100          | 1         | 0.11%   |
| 3072x1920          | 1         | 0.11%   |
| 2520x1680          | 1         | 0.11%   |
| 2400x1600          | 1         | 0.11%   |
| 2304x1440          | 1         | 0.11%   |
| 2288x1287          | 1         | 0.11%   |
| 1920x540           | 1         | 0.11%   |
| 1920x1280          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 342       | 34.9%   |
| 13      | 144       | 14.69%  |
| 14      | 130       | 13.27%  |
| 17      | 68        | 6.94%   |
| 27      | 43        | 4.39%   |
| 24      | 39        | 3.98%   |
| 16      | 31        | 3.16%   |
| 23      | 29        | 2.96%   |
| 12      | 29        | 2.96%   |
| 21      | 24        | 2.45%   |
| 34      | 14        | 1.43%   |
| Unknown | 12        | 1.22%   |
| 11      | 11        | 1.12%   |
| 31      | 10        | 1.02%   |
| 22      | 6         | 0.61%   |
| 19      | 6         | 0.61%   |
| 10      | 6         | 0.61%   |
| 25      | 4         | 0.41%   |
| 18      | 4         | 0.41%   |
| 8       | 3         | 0.31%   |
| 58      | 2         | 0.2%    |
| 40      | 2         | 0.2%    |
| 37      | 2         | 0.2%    |
| 20      | 2         | 0.2%    |
| 142     | 1         | 0.1%    |
| 84      | 1         | 0.1%    |
| 75      | 1         | 0.1%    |
| 74      | 1         | 0.1%    |
| 72      | 1         | 0.1%    |
| 65      | 1         | 0.1%    |
| 57      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 43      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 28      | 1         | 0.1%    |
| 26      | 1         | 0.1%    |
| 7       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 553       | 57.13%  |
| 201-300        | 129       | 13.33%  |
| 501-600        | 105       | 10.85%  |
| 351-400        | 77        | 7.95%   |
| 401-500        | 39        | 4.03%   |
| 701-800        | 16        | 1.65%   |
| 601-700        | 16        | 1.65%   |
| Unknown        | 12        | 1.24%   |
| 1001-1500      | 7         | 0.72%   |
| 801-900        | 4         | 0.41%   |
| 1501-2000      | 4         | 0.41%   |
| 101-200        | 3         | 0.31%   |
| 1-100          | 2         | 0.21%   |
| More than 2000 | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 654       | 76.05%  |
| 16/10   | 136       | 15.81%  |
| 3/2     | 25        | 2.91%   |
| 21/9    | 16        | 1.86%   |
| Unknown | 10        | 1.16%   |
| 5/4     | 5         | 0.58%   |
| 4/3     | 5         | 0.58%   |
| 32/9    | 2         | 0.23%   |
| 6/5     | 1         | 0.12%   |
| 3.40    | 1         | 0.12%   |
| 3.20    | 1         | 0.12%   |
| 1.00    | 1         | 0.12%   |
| 0.67    | 1         | 0.12%   |
| 0.62    | 1         | 0.12%   |
| 0.56    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 341       | 34.8%   |
| 81-90          | 209       | 21.33%  |
| 201-250        | 72        | 7.35%   |
| 71-80          | 65        | 6.63%   |
| 121-130        | 60        | 6.12%   |
| 301-350        | 44        | 4.49%   |
| 111-120        | 30        | 3.06%   |
| 61-70          | 27        | 2.76%   |
| 351-500        | 25        | 2.55%   |
| 251-300        | 21        | 2.14%   |
| 151-200        | 15        | 1.53%   |
| 51-60          | 12        | 1.22%   |
| Unknown        | 12        | 1.22%   |
| More than 1000 | 11        | 1.12%   |
| 131-140        | 7         | 0.71%   |
| 501-1000       | 7         | 0.71%   |
| 41-50          | 6         | 0.61%   |
| 141-150        | 6         | 0.61%   |
| 1-40           | 5         | 0.51%   |
| 91-100         | 5         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 456       | 47.65%  |
| 101-120       | 147       | 15.36%  |
| 161-240       | 135       | 14.11%  |
| 51-100        | 127       | 13.27%  |
| More than 240 | 71        | 7.42%   |
| Unknown       | 12        | 1.25%   |
| 1-50          | 9         | 0.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 661       | 75.98%  |
| 2     | 150       | 17.24%  |
| 0     | 32        | 3.68%   |
| 3     | 27        | 3.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 541       | 41.71%  |
| Realtek Semiconductor                 | 410       | 31.61%  |
| Qualcomm Atheros                      | 101       | 7.79%   |
| Broadcom                              | 48        | 3.7%    |
| MediaTek                              | 43        | 3.32%   |
| ASIX Electronics                      | 17        | 1.31%   |
| Qualcomm                              | 16        | 1.23%   |
| Lenovo                                | 14        | 1.08%   |
| Marvell Technology Group              | 10        | 0.77%   |
| Dell                                  | 9         | 0.69%   |
| Broadcom Limited                      | 9         | 0.69%   |
| Xiaomi                                | 8         | 0.62%   |
| Sierra Wireless                       | 7         | 0.54%   |
| Samsung Electronics                   | 6         | 0.46%   |
| TP-Link                               | 5         | 0.39%   |
| FIBOCOM                               | 5         | 0.39%   |
| Ericsson Business Mobile Networks     | 5         | 0.39%   |
| Apple                                 | 5         | 0.39%   |
| Ralink Technology                     | 4         | 0.31%   |
| Qualcomm Atheros Communications       | 3         | 0.23%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.15%   |
| Silicon Integrated Systems [SiS]      | 2         | 0.15%   |
| Ralink                                | 2         | 0.15%   |
| ICS Advent                            | 2         | 0.15%   |
| Google                                | 2         | 0.15%   |
| D-Link System                         | 2         | 0.15%   |
| Texas Instruments                     | 1         | 0.08%   |
| Shenzhen Goodix Technology            | 1         | 0.08%   |
| Prusa                                 | 1         | 0.08%   |
| Nvidia                                | 1         | 0.08%   |
| NetGear                               | 1         | 0.08%   |
| Microsoft                             | 1         | 0.08%   |
| JMicron Technology                    | 1         | 0.08%   |
| Huawei Technologies                   | 1         | 0.08%   |
| Gemtek                                | 1         | 0.08%   |
| Emulex                                | 1         | 0.08%   |
| Edimax Technology                     | 1         | 0.08%   |
| D-Link                                | 1         | 0.08%   |
| Cisco Aironet Wireless Communications | 1         | 0.08%   |
| BUFFALO                               | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 279       | 17.55%  |
| Intel Wi-Fi 6 AX200                                                    | 86        | 5.41%   |
| Intel Wireless 8265 / 8275                                             | 60        | 3.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 52        | 3.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 37        | 2.33%   |
| Intel Wi-Fi 6 AX201                                                    | 31        | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 28        | 1.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 26        | 1.64%   |
| Intel Wireless 7265                                                    | 25        | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 24        | 1.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 1.51%   |
| Intel Ethernet Connection (4) I219-LM                                  | 24        | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 24        | 1.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 24        | 1.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 21        | 1.32%   |
| Intel Wireless 8260                                                    | 21        | 1.32%   |
| Intel Wireless 7260                                                    | 21        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 21        | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 21        | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 19        | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 15        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 14        | 0.88%   |
| Intel Wireless 3165                                                    | 14        | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 13        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 0.82%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 12        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 0.75%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 11        | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 10        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                                  | 10        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 9         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 8         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 8         | 0.5%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 8         | 0.5%    |
| Intel Centrino Advanced-N 6235                                         | 8         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 528       | 61.47%  |
| Realtek Semiconductor                 | 111       | 12.92%  |
| Qualcomm Atheros                      | 77        | 8.96%   |
| MediaTek                              | 41        | 4.77%   |
| Broadcom                              | 40        | 4.66%   |
| Qualcomm                              | 16        | 1.86%   |
| Sierra Wireless                       | 7         | 0.81%   |
| Dell                                  | 7         | 0.81%   |
| FIBOCOM                               | 5         | 0.58%   |
| Broadcom Limited                      | 5         | 0.58%   |
| Ralink Technology                     | 4         | 0.47%   |
| TP-Link                               | 3         | 0.35%   |
| Qualcomm Atheros Communications       | 3         | 0.35%   |
| Ralink                                | 2         | 0.23%   |
| D-Link System                         | 2         | 0.23%   |
| NetGear                               | 1         | 0.12%   |
| Microsoft                             | 1         | 0.12%   |
| Edimax Technology                     | 1         | 0.12%   |
| D-Link                                | 1         | 0.12%   |
| Cisco Aironet Wireless Communications | 1         | 0.12%   |
| BUFFALO                               | 1         | 0.12%   |
| AVM                                   | 1         | 0.12%   |
| ASUSTek Computer                      | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 86        | 9.98%   |
| Intel Wireless 8265 / 8275                                              | 60        | 6.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 37        | 4.29%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 3.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 28        | 3.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 26        | 3.02%   |
| Intel Wireless 7265                                                     | 25        | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 24        | 2.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 24        | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 2.44%   |
| Intel Wireless 8260                                                     | 21        | 2.44%   |
| Intel Wireless 7260                                                     | 21        | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 21        | 2.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 19        | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 1.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 14        | 1.62%   |
| Intel Wireless 3165                                                     | 14        | 1.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 13        | 1.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 13        | 1.51%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 12        | 1.39%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 11        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 8         | 0.93%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 8         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 7         | 0.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.58%   |
| Intel Wireless 3160                                                     | 5         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 370       | 53.7%   |
| Intel                            | 186       | 27%     |
| Qualcomm Atheros                 | 35        | 5.08%   |
| Broadcom                         | 18        | 2.61%   |
| ASIX Electronics                 | 17        | 2.47%   |
| Lenovo                           | 14        | 2.03%   |
| Marvell Technology Group         | 10        | 1.45%   |
| Xiaomi                           | 8         | 1.16%   |
| Samsung Electronics              | 5         | 0.73%   |
| Apple                            | 5         | 0.73%   |
| Broadcom Limited                 | 4         | 0.58%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.29%   |
| TP-Link                          | 2         | 0.29%   |
| Silicon Integrated Systems [SiS] | 2         | 0.29%   |
| ICS Advent                       | 2         | 0.29%   |
| Google                           | 2         | 0.29%   |
| Nvidia                           | 1         | 0.15%   |
| MediaTek                         | 1         | 0.15%   |
| JMicron Technology               | 1         | 0.15%   |
| Huawei Technologies              | 1         | 0.15%   |
| Gemtek                           | 1         | 0.15%   |
| Emulex                           | 1         | 0.15%   |
| Aquantia                         | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 279       | 39.69%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 52        | 7.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 3.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 24        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 21        | 2.99%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 1.71%   |
| Intel Ethernet Connection (6) I219-V                                   | 11        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 1.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 10        | 1.42%   |
| Intel Ethernet Connection (2) I219-LM                                  | 10        | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 1%      |
| Intel Ethernet Connection I219-LM                                      | 7         | 1%      |
| Intel Ethernet Connection I218-LM                                      | 7         | 1%      |
| Intel Ethernet Connection I217-LM                                      | 7         | 1%      |
| Intel Ethernet Connection (7) I219-LM                                  | 7         | 1%      |
| Intel Ethernet Connection (5) I219-LM                                  | 7         | 1%      |
| Intel 82577LM Gigabit Network Connection                               | 7         | 1%      |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.85%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 5         | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 5         | 0.71%   |
| Lenovo USB-C Dock Ethernet                                             | 5         | 0.71%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 5         | 0.71%   |
| Intel I210 Gigabit Network Connection                                  | 5         | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 4         | 0.57%   |
| Intel Ethernet Connection I219-V                                       | 4         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.57%   |
| Intel Ethernet Connection (6) I219-LM                                  | 4         | 0.57%   |
| Intel Ethernet Connection (14) I219-LM                                 | 4         | 0.57%   |
| Intel Ethernet Connection (10) I219-LM                                 | 4         | 0.57%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 0.43%   |
| Intel Ethernet Connection (14) I219-V                                  | 3         | 0.43%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.43%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                     | 3         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 817       | 54.87%  |
| Ethernet | 647       | 43.45%  |
| Modem    | 24        | 1.61%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 651       | 71.7%   |
| Ethernet | 257       | 28.3%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 550       | 66.19%  |
| 1     | 256       | 30.81%  |
| 3     | 19        | 2.29%   |
| 0     | 5         | 0.6%    |
| 4     | 1         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 694       | 81.26%  |
| Yes  | 160       | 18.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 452       | 62%     |
| Realtek Semiconductor           | 69        | 9.47%   |
| IMC Networks                    | 32        | 4.39%   |
| Foxconn / Hon Hai               | 29        | 3.98%   |
| Lite-On Technology              | 25        | 3.43%   |
| Qualcomm Atheros Communications | 22        | 3.02%   |
| Apple                           | 22        | 3.02%   |
| Broadcom                        | 18        | 2.47%   |
| USI                             | 9         | 1.23%   |
| Dell                            | 9         | 1.23%   |
| Realtek                         | 8         | 1.1%    |
| Cambridge Silicon Radio         | 7         | 0.96%   |
| MediaTek                        | 6         | 0.82%   |
| Hewlett-Packard                 | 5         | 0.69%   |
| Toshiba                         | 4         | 0.55%   |
| Foxconn International           | 3         | 0.41%   |
| ASUSTek Computer                | 3         | 0.41%   |
| Ralink Technology               | 1         | 0.14%   |
| Opticis                         | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |
| Askey Computer                  | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |
| Actiontec Electronics           | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 82        | 11.23%  |
| Intel AX200 Bluetooth                               | 81        | 11.1%   |
| Intel Bluetooth Device                              | 72        | 9.86%   |
| Intel Bluetooth wireless interface                  | 69        | 9.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 69        | 9.45%   |
| Realtek Bluetooth Radio                             | 37        | 5.07%   |
| Intel AX211 Bluetooth                               | 30        | 4.11%   |
| Intel AX210 Bluetooth                               | 27        | 3.7%    |
| Apple Bluetooth Host Controller                     | 17        | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 1.78%   |
| IMC Networks Wireless_Device                        | 13        | 1.78%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 1.37%   |
| USI Bluetooth Device                                | 9         | 1.23%   |
| Realtek 802.11ac WLAN Adapter                       | 9         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 1.23%   |
| Realtek Bluetooth Radio                             | 8         | 1.1%    |
| Lite-On Bluetooth Device                            | 8         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.96%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 0.96%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.82%   |
| MediaTek Wireless_Device                            | 6         | 0.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.68%   |
| IMC Networks Bluetooth Device                       | 5         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.55%   |
| Lite-On Wireless_Device                             | 4         | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 0.55%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.55%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.41%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 592       | 52.2%   |
| AMD                                  | 229       | 20.19%  |
| Nvidia                               | 198       | 17.46%  |
| Lenovo                               | 18        | 1.59%   |
| Realtek Semiconductor                | 11        | 0.97%   |
| C-Media Electronics                  | 9         | 0.79%   |
| Plantronics                          | 5         | 0.44%   |
| Logitech                             | 5         | 0.44%   |
| Razer USA                            | 4         | 0.35%   |
| No brand                             | 4         | 0.35%   |
| Kingston Technology                  | 4         | 0.35%   |
| Hewlett-Packard                      | 4         | 0.35%   |
| Creative Technology                  | 4         | 0.35%   |
| SteelSeries ApS                      | 3         | 0.26%   |
| Dell                                 | 3         | 0.26%   |
| Blue Microphones                     | 3         | 0.26%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.18%   |
| JMTek                                | 2         | 0.18%   |
| JBL                                  | 2         | 0.18%   |
| GYROCOM C&C                          | 2         | 0.18%   |
| GN Netcom                            | 2         | 0.18%   |
| Generalplus Technology               | 2         | 0.18%   |
| DSEA A/S                             | 2         | 0.18%   |
| AudioQuest                           | 2         | 0.18%   |
| ASUSTek Computer                     | 2         | 0.18%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.09%   |
| Texas Instruments                    | 1         | 0.09%   |
| Tdlasunnic                           | 1         | 0.09%   |
| Synaptics                            | 1         | 0.09%   |
| Sennheiser Communications            | 1         | 0.09%   |
| Samson Technologies                  | 1         | 0.09%   |
| RODE Microphones                     | 1         | 0.09%   |
| LG Electronics                       | 1         | 0.09%   |
| iCreate Technologies                 | 1         | 0.09%   |
| FiiO Electronics Technology          | 1         | 0.09%   |
| EGO SYStems                          | 1         | 0.09%   |
| Corsair                              | 1         | 0.09%   |
| Behringer.......                     | 1         | 0.09%   |
| AVer Information                     | 1         | 0.09%   |
| Audio-Technica                       | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 198       | 14.17%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 113       | 8.09%   |
| Intel Sunrise Point-LP HD Audio                                            | 94        | 6.73%   |
| Intel Cannon Lake PCH cAVS                                                 | 72        | 5.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 41        | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 36        | 2.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 33        | 2.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 30        | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 28        | 2%      |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 28        | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 27        | 1.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 25        | 1.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 25        | 1.79%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 1.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 23        | 1.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 22        | 1.57%   |
| Intel CM238 HD Audio Controller                                            | 22        | 1.57%   |
| Nvidia Audio device                                                        | 20        | 1.43%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 1.43%   |
| Intel 8 Series HD Audio Controller                                         | 20        | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                              | 18        | 1.29%   |
| Nvidia GA106 High Definition Audio Controller                              | 18        | 1.29%   |
| Nvidia GA104 High Definition Audio Controller                              | 17        | 1.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 1.15%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 16        | 1.15%   |
| Intel Broadwell-U Audio Controller                                         | 16        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 1.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 14        | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 12        | 0.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12        | 0.86%   |
| Realtek Semiconductor USB Audio                                            | 11        | 0.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 11        | 0.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 0.72%   |
| AMD FCH Azalia Controller                                                  | 10        | 0.72%   |
| Nvidia TU104 HD Audio Controller                                           | 9         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 9         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 9         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 297       | 31.63%  |
| SK hynix                     | 201       | 21.41%  |
| Micron Technology            | 133       | 14.16%  |
| Kingston                     | 73        | 7.77%   |
| Crucial                      | 58        | 6.18%   |
| Unknown                      | 47        | 5.01%   |
| Ramaxel Technology           | 15        | 1.6%    |
| Corsair                      | 15        | 1.6%    |
| A-DATA Technology            | 15        | 1.6%    |
| Elpida                       | 12        | 1.28%   |
| Unknown                      | 11        | 1.17%   |
| G.Skill                      | 9         | 0.96%   |
| Team                         | 8         | 0.85%   |
| Transcend                    | 6         | 0.64%   |
| Nanya Technology             | 6         | 0.64%   |
| Patriot                      | 5         | 0.53%   |
| Unknown (ABCD)               | 4         | 0.43%   |
| GOODRAM                      | 4         | 0.43%   |
| Timetec                      | 3         | 0.32%   |
| AMD                          | 3         | 0.32%   |
| Avant                        | 2         | 0.21%   |
| Apacer                       | 2         | 0.21%   |
| Unknown (0x5D00000000000000) | 1         | 0.11%   |
| Teikon                       | 1         | 0.11%   |
| Saikano                      | 1         | 0.11%   |
| Magnum Tech                  | 1         | 0.11%   |
| KLEVV                        | 1         | 0.11%   |
| Kimtigo                      | 1         | 0.11%   |
| GSkill                       | 1         | 0.11%   |
| Goldkey                      | 1         | 0.11%   |
| CSX                          | 1         | 0.11%   |
| 48spaces                     | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s    | 15        | 1.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 12        | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 12        | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 12        | 1.22%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s    | 12        | 1.22%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 12        | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 11        | 1.12%   |
| Unknown                                                     | 11        | 1.12%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 10        | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 9         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 9         | 0.92%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.81%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.81%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 8         | 0.81%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 8         | 0.81%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 8         | 0.81%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.71%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 7         | 0.71%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 7         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 6         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 6         | 0.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 6         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.61%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s          | 6         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 6         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.51%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.51%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 5         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 5         | 0.51%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s  | 5         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 5         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 5         | 0.51%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.51%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 5         | 0.51%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 5         | 0.51%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.51%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s  | 5         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 480       | 60.08%  |
| DDR3    | 159       | 19.9%   |
| LPDDR4  | 38        | 4.76%   |
| DDR5    | 35        | 4.38%   |
| LPDDR5  | 24        | 3%      |
| LPDDR3  | 23        | 2.88%   |
| DDR2    | 19        | 2.38%   |
| DDR     | 12        | 1.5%    |
| SDRAM   | 6         | 0.75%   |
| Unknown | 2         | 0.25%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 709       | 88.4%   |
| Row Of Chips | 82        | 10.22%  |
| Chip         | 5         | 0.62%   |
| DIMM         | 3         | 0.37%   |
| Unknown      | 3         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 367       | 42.14%  |
| 16384 | 204       | 23.42%  |
| 4096  | 154       | 17.68%  |
| 32768 | 60        | 6.89%   |
| 2048  | 56        | 6.43%   |
| 1024  | 21        | 2.41%   |
| 512   | 4         | 0.46%   |
| 256   | 4         | 0.46%   |
| 49152 | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 225       | 26.25%  |
| 2667    | 200       | 23.34%  |
| 1600    | 111       | 12.95%  |
| 2400    | 55        | 6.42%   |
| 2133    | 41        | 4.78%   |
| 4800    | 26        | 3.03%   |
| 1333    | 24        | 2.8%    |
| 6400    | 21        | 2.45%   |
| 4267    | 19        | 2.22%   |
| 1334    | 17        | 1.98%   |
| Unknown | 16        | 1.87%   |
| 667     | 15        | 1.75%   |
| 5600    | 12        | 1.4%    |
| 3266    | 12        | 1.4%    |
| 8400    | 10        | 1.17%   |
| 1867    | 10        | 1.17%   |
| 1067    | 7         | 0.82%   |
| 4266    | 5         | 0.58%   |
| 800     | 5         | 0.58%   |
| 3733    | 4         | 0.47%   |
| 2933    | 4         | 0.47%   |
| 533     | 4         | 0.47%   |
| 3000    | 2         | 0.23%   |
| 400     | 2         | 0.23%   |
| 133     | 2         | 0.23%   |
| 8600    | 1         | 0.12%   |
| 7500    | 1         | 0.12%   |
| 5500    | 1         | 0.12%   |
| 4199    | 1         | 0.12%   |
| 3600    | 1         | 0.12%   |
| 3467    | 1         | 0.12%   |
| 2048    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 40%     |
| Seiko Epson         | 2         | 20%     |
| Xiaomi              | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| Konica Minolta      | 1         | 10%     |
| Canon               | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xiaomi MiMouse 2                     | 1         | 10%     |
| Seiko Epson WF-2510 Series           | 1         | 10%     |
| Seiko Epson AL-M310DN                | 1         | 10%     |
| Samsung CLP-325 Color Laser Printer  | 1         | 10%     |
| Konica Minolta magicolor 1680MF scan | 1         | 10%     |
| HP LaserJet P2055 series             | 1         | 10%     |
| HP Deskjet D1500 series              | 1         | 10%     |
| HP DeskJet 5440                      | 1         | 10%     |
| HP DeskJet 3630 series               | 1         | 10%     |
| Canon LiDE 300                       | 1         | 10%     |

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
| Chicony Electronics                    | 184       | 25.52%  |
| IMC Networks                           | 101       | 14.01%  |
| Microdia                               | 69        | 9.57%   |
| Realtek Semiconductor                  | 54        | 7.49%   |
| Bison Electronics                      | 43        | 5.96%   |
| Sunplus Innovation Technology          | 38        | 5.27%   |
| Quanta                                 | 38        | 5.27%   |
| Lite-On Technology                     | 25        | 3.47%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 3.47%   |
| Luxvisions Innotech Limited            | 23        | 3.19%   |
| Syntek                                 | 16        | 2.22%   |
| Acer                                   | 16        | 2.22%   |
| Logitech                               | 15        | 2.08%   |
| Apple                                  | 15        | 2.08%   |
| Sonix Technology                       | 6         | 0.83%   |
| Samsung Electronics                    | 5         | 0.69%   |
| Suyin                                  | 4         | 0.55%   |
| DigiTech                               | 4         | 0.55%   |
| Z-Star Microelectronics                | 3         | 0.42%   |
| Silicon Motion                         | 3         | 0.42%   |
| Microsoft                              | 3         | 0.42%   |
| Ricoh                                  | 2         | 0.28%   |
| LG Electronics                         | 2         | 0.28%   |
| Lenovo                                 | 2         | 0.28%   |
| kingcome                               | 2         | 0.28%   |
| Genesys Logic                          | 2         | 0.28%   |
| Alcor Micro                            | 2         | 0.28%   |
| USB3.0 HD Audio Capture                | 1         | 0.14%   |
| Tripath Technology                     | 1         | 0.14%   |
| SunplusIT                              | 1         | 0.14%   |
| Sunplus Technology                     | 1         | 0.14%   |
| ShineTech                              | 1         | 0.14%   |
| Razer USA                              | 1         | 0.14%   |
| Omnivision                             | 1         | 0.14%   |
| MacroSilicon                           | 1         | 0.14%   |
| Intel                                  | 1         | 0.14%   |
| icSpring                               | 1         | 0.14%   |
| Holitech                               | 1         | 0.14%   |
| Hewlett-Packard                        | 1         | 0.14%   |
| Google                                 | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 65        | 8.9%    |
| Microdia Integrated_Webcam_HD                        | 44        | 6.03%   |
| IMC Networks Integrated Camera                       | 39        | 5.34%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 28        | 3.84%   |
| Realtek Integrated_Webcam_HD                         | 23        | 3.15%   |
| Chicony HD WebCam                                    | 18        | 2.47%   |
| Bison Integrated Camera                              | 18        | 2.47%   |
| Sunplus Integrated_Webcam_HD                         | 13        | 1.78%   |
| Chicony HP HD Camera                                 | 12        | 1.64%   |
| Syntek Integrated Camera                             | 11        | 1.51%   |
| Quanta HD User Facing                                | 9         | 1.23%   |
| Lite-On Integrated Camera                            | 9         | 1.23%   |
| Chicony USB2.0 Camera                                | 9         | 1.23%   |
| Chicony Integrated IR Camera                         | 7         | 0.96%   |
| Chicony Integrated Camera (1280x720@30)              | 7         | 0.96%   |
| Chicony HD User Facing                               | 7         | 0.96%   |
| Acer Integrated Camera                               | 7         | 0.96%   |
| Sunplus HD WebCam                                    | 6         | 0.82%   |
| Realtek Laptop Camera                                | 6         | 0.82%   |
| Logitech HD Pro Webcam C920                          | 6         | 0.82%   |
| Lite-On HP HD Camera                                 | 6         | 0.82%   |
| Chicony Lenovo EasyCamera                            | 6         | 0.82%   |
| Bison SunplusIT Integrated Camera                    | 6         | 0.82%   |
| Bison HD Webcam                                      | 6         | 0.82%   |
| Apple FaceTime HD Camera                             | 6         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)              | 5         | 0.68%   |
| Quanta HP Wide Vision HD Camera                      | 5         | 0.68%   |
| Quanta HP TrueVision HD Camera                       | 5         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 5         | 0.68%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 5         | 0.68%   |
| Luxvisions Innotech Limited HP HD Camera             | 5         | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 5         | 0.68%   |
| Chicony ThinkPad T490 Webcam                         | 5         | 0.68%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.55%   |
| Quanta HD Webcam                                     | 4         | 0.55%   |
| Microdia USB 2.0 Camera                              | 4         | 0.55%   |
| Microdia Integrated_Webcam_FHD                       | 4         | 0.55%   |
| Microdia Integrated Webcam                           | 4         | 0.55%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 4         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 76        | 46.63%  |
| Validity Sensors                   | 39        | 23.93%  |
| Shenzhen Goodix Technology         | 24        | 14.72%  |
| Elan Microelectronics              | 9         | 5.52%   |
| STMicroelectronics                 | 4         | 2.45%   |
| LighTuning Technology              | 4         | 2.45%   |
| AuthenTec                          | 4         | 2.45%   |
| Upek                               | 2         | 1.23%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.61%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 19.63%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 17        | 10.43%  |
| Validity Sensors Synaptics WBDI                                            | 12        | 7.36%   |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 7.36%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 5.52%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.68%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.68%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 3.68%   |
| Synaptics UWP WBDI Device                                                  | 5         | 3.07%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 3.07%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.45%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.45%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.84%   |
| Synaptics WBDI                                                             | 3         | 1.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.84%   |
| Validity Sensors VFS491                                                    | 2         | 1.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 1.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.23%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.23%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.23%   |
| Unknown                                                                    | 2         | 1.23%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.61%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.61%   |
| Synaptics WBDI Device                                                      | 1         | 0.61%   |
| Synaptics TouchPad                                                         | 1         | 0.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.61%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.61%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 45        | 41.67%  |
| Alcor Micro               | 45        | 41.67%  |
| Upek                      | 5         | 4.63%   |
| O2 Micro                  | 5         | 4.63%   |
| Yubico.com                | 1         | 0.93%   |
| Purism, SPC               | 1         | 0.93%   |
| OmniKey                   | 1         | 0.93%   |
| Microchip Technology      | 1         | 0.93%   |
| Lenovo                    | 1         | 0.93%   |
| Gemalto (was Gemplus)     | 1         | 0.93%   |
| Clay Logic                | 1         | 0.93%   |
| Aladdin Knowledge Systems | 1         | 0.93%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 45        | 41.67%  |
| Broadcom 58200                                                               | 18        | 16.67%  |
| Broadcom 5880                                                                | 13        | 12.04%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.48%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 5.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 3.7%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.93%   |
| Purism, SPC Librem Key                                                       | 1         | 0.93%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.93%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.93%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.93%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 0.93%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.93%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.93%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.93%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.93%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 327       | 34.68%  |
| 1     | 256       | 27.15%  |
| 2     | 147       | 15.59%  |
| 3     | 98        | 10.39%  |
| 4     | 59        | 6.26%   |
| 5     | 37        | 3.92%   |
| 6     | 16        | 1.7%    |
| 7     | 2         | 0.21%   |
| 8     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 189       | 15.05%  |
| Camera                   | 174       | 13.85%  |
| Bluetooth                | 166       | 13.22%  |
| Fingerprint reader       | 161       | 12.82%  |
| Graphics card            | 150       | 11.94%  |
| Chipcard                 | 93        | 7.4%    |
| Multimedia controller    | 78        | 6.21%   |
| Net/wireless             | 72        | 5.73%   |
| Card reader              | 71        | 5.65%   |
| Sound                    | 23        | 1.83%   |
| Net/ethernet             | 16        | 1.27%   |
| Modem                    | 16        | 1.27%   |
| Network                  | 15        | 1.19%   |
| Storage/ata              | 8         | 0.64%   |
| Firewire controller      | 6         | 0.48%   |
| Storage                  | 5         | 0.4%    |
| Storage/ide              | 4         | 0.32%   |
| Tv card                  | 2         | 0.16%   |
| Storage/raid             | 2         | 0.16%   |
| Storage/nvme             | 2         | 0.16%   |
| Dvb card                 | 2         | 0.16%   |
| Wireless                 | 1         | 0.08%   |

