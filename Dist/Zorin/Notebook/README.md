Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 3703

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | Latitude E6540              | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Dell          | Latitude E7470              | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Google        | Kip                         | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Latitude E6510              | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HP            | Pavilion dv6                | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Dell          | Latitude E6540              | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | Latitude 7490               | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Lenovo        | G500 20236                  | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| MSI           | MS-1035                     | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| GPD           | G1619-04                    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Jumper        | EZbook                      | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Toshiba       | Satellite P500              | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| Toshiba       | Satellite L500              | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Dell          | Latitude 7490               | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| Dell          | Latitude 7490               | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| HP            | Notebook                    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Framework     | Laptop                      | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Gateway       | NV59C                       | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| ASUSTek       | F5V                         | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 240 G8                      | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Quanta        | TW8/SW8/DW8                 | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| Dell          | Latitude E6500              | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| MSI           | GE62 7RE                    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Chuwi         | HeroBook Air                | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | Studio 1558                 | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| HP            | Notebook                    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Dell          | Inspiron 1200               | [45c46e1b91](https://linux-hardware.org/?probe=45c46e1b91) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [29c7a43356](https://linux-hardware.org/?probe=29c7a43356) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Dell          | Latitude E6500              | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Dell          | Inspiron 1200               | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Dell          | Latitude E6520              | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Alienware     | 18                          | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Dell          | G15 5515                    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Dell          | Latitude D610               | [47e0f0fa27](https://linux-hardware.org/?probe=47e0f0fa27) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkPad 11e 20DAS09U00     | [81bd748796](https://linux-hardware.org/?probe=81bd748796) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| Ematic        | EWT118                      | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| Dell          | Latitude D610               | [df13ed7396](https://linux-hardware.org/?probe=df13ed7396) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| HP            | EliteBook 820 G2            | [199f191441](https://linux-hardware.org/?probe=199f191441) | Sep 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| Dell          | Latitude E7240              | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| AZW           | Z83-V                       | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| Toshiba       | Satellite P200              | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| HP            | 15                          | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| HP            | Pavilion g7                 | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| Positivo      | C14CR01                     | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| Intel         | powered classmate PC        | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Dell          | Inspiron 15-3552            | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| HP            | ProBook 6470b               | [2cbe458c94](https://linux-hardware.org/?probe=2cbe458c94) | Aug 30, 2022 |
| Apple         | MacBookAir7,2               | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| Dell          | Latitude E5440              | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| Dell          | Latitude E7240              | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Alienware     | 15 R3                       | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| HP            | Pavilion dv9700             | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| HP            | EliteBook 6930p             | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [b3e408ce95](https://linux-hardware.org/?probe=b3e408ce95) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [1fe351cfab](https://linux-hardware.org/?probe=1fe351cfab) | Aug 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| Unknown       | Unknown                     | [ddeddb54bf](https://linux-hardware.org/?probe=ddeddb54bf) | Aug 12, 2022 |
| Unknown       | Unknown                     | [b19949df5a](https://linux-hardware.org/?probe=b19949df5a) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| HP            | Pavilion 15                 | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Google        | Kasumi                      | [0d1ce61572](https://linux-hardware.org/?probe=0d1ce61572) | Aug 11, 2022 |
| Google        | Kasumi                      | [47ebd6bcac](https://linux-hardware.org/?probe=47ebd6bcac) | Aug 11, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | [4e54f20c67](https://linux-hardware.org/?probe=4e54f20c67) | Aug 10, 2022 |
| Samsung       | 600B4B/600B5B               | [889eb9531f](https://linux-hardware.org/?probe=889eb9531f) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| HP            | Pro x2 612 G1 Tablet        | [a40ad10b4c](https://linux-hardware.org/?probe=a40ad10b4c) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| HP            | Stream Notebook PC 13       | [9071c341a9](https://linux-hardware.org/?probe=9071c341a9) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| Toshiba       | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [69430d4693](https://linux-hardware.org/?probe=69430d4693) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| ASUSTek       | X550JK                      | [a90c14a429](https://linux-hardware.org/?probe=a90c14a429) | Aug 07, 2022 |
| AMI           | Unknown                     | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| MSI           | CR620                       | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Ematic        | EWT118                      | [a5362d970a](https://linux-hardware.org/?probe=a5362d970a) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Medion        | E7419 MD60990               | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| Acer          | Peppy                       | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| Toshiba       | Satellite P200              | [87bf7fcb48](https://linux-hardware.org/?probe=87bf7fcb48) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| HP            | Notebook                    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| Toshiba       | Satellite P205              | [8ed745a2dc](https://linux-hardware.org/?probe=8ed745a2dc) | Aug 03, 2022 |
| Dell          | G15 5510                    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | ThinkPad T420 4236VTQ       | [1ea6046182](https://linux-hardware.org/?probe=1ea6046182) | Aug 02, 2022 |
| HP            | Pro x2 612 G1 Tablet        | [b4bee86632](https://linux-hardware.org/?probe=b4bee86632) | Aug 02, 2022 |
| HP            | Laptop 14-dq4xxx            | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| HP            | Compaq 6730s                | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| HP            | 550                         | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Dell          | Latitude E7450              | [894a489a03](https://linux-hardware.org/?probe=894a489a03) | Jul 30, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Dell          | Latitude E7450              | [4a277d4cee](https://linux-hardware.org/?probe=4a277d4cee) | Jul 27, 2022 |
| Sony          | VGN-Z31XN_B                 | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ff4dba6b3e](https://linux-hardware.org/?probe=ff4dba6b3e) | Jul 24, 2022 |
| HP            | Unknown                     | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Dell          | Inspiron 1525               | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| HP            | ProBook 4540s               | [a2d1e2fd68](https://linux-hardware.org/?probe=a2d1e2fd68) | Jul 22, 2022 |
| HP            | Compaq 420                  | [913795a620](https://linux-hardware.org/?probe=913795a620) | Jul 21, 2022 |
| ASUSTek       | X550CL                      | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Inspiron 5520               | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Dell          | Inspiron 3541               | [cb0f9c95d2](https://linux-hardware.org/?probe=cb0f9c95d2) | Jul 20, 2022 |
| Toshiba       | Satellite L655              | [e332607406](https://linux-hardware.org/?probe=e332607406) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Google        | Butterfly                   | [ed6aa75ba5](https://linux-hardware.org/?probe=ed6aa75ba5) | Jul 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| Apple         | MacBookPro12,1              | [4a5f294565](https://linux-hardware.org/?probe=4a5f294565) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| Dell          | MXG061                      | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Acer          | NC-A315-41G-R88F            | [8ffe1077fd](https://linux-hardware.org/?probe=8ffe1077fd) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| HP            | ENVY 17                     | [bc1e8b41a5](https://linux-hardware.org/?probe=bc1e8b41a5) | Jul 17, 2022 |
| ASUSTek       | X751MA                      | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| Toshiba       | TECRA S11                   | [26ed071525](https://linux-hardware.org/?probe=26ed071525) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| AMI           | Unknown                     | [2d15648f33](https://linux-hardware.org/?probe=2d15648f33) | Jul 14, 2022 |
| Alienware     | x15 R1                      | [95ee5b34a7](https://linux-hardware.org/?probe=95ee5b34a7) | Jul 14, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HP            | Unknown                     | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | ProBook 455 G1              | [a0dd163643](https://linux-hardware.org/?probe=a0dd163643) | Jul 14, 2022 |
| HP            | Laptop 15-dw3xxx            | [09e66aef7e](https://linux-hardware.org/?probe=09e66aef7e) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| Star Labs     | StarBook                    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | Laptop 15-dw3xxx            | [e974774285](https://linux-hardware.org/?probe=e974774285) | Jul 12, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| HP            | ProBook 640 G1              | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| MSI           | Creator 15 A10SET           | [d90f2aec1b](https://linux-hardware.org/?probe=d90f2aec1b) | Jul 10, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8a02619147](https://linux-hardware.org/?probe=8a02619147) | Jul 10, 2022 |
| eMachines     | E720 V1.06                  | [ec23637bd5](https://linux-hardware.org/?probe=ec23637bd5) | Jul 09, 2022 |
| Packard Be... | EasyNote TE69KB             | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| HP            | Pavilion 15                 | [1fbb699502](https://linux-hardware.org/?probe=1fbb699502) | Jul 09, 2022 |
| Dell          | Latitude 5400               | [46ce7cf7fe](https://linux-hardware.org/?probe=46ce7cf7fe) | Jul 09, 2022 |
| HP            | Pavilion 15                 | [c74f3711f3](https://linux-hardware.org/?probe=c74f3711f3) | Jul 09, 2022 |
| Fujitsu Si... | AMILO L Series              | [410cd1aeec](https://linux-hardware.org/?probe=410cd1aeec) | Jul 08, 2022 |
| Sony          | VGN-Z31XN_B                 | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T400 2768GB4       | [498bb4a509](https://linux-hardware.org/?probe=498bb4a509) | Jul 08, 2022 |
| Acer          | Aspire 5755G                | [37aff6bb24](https://linux-hardware.org/?probe=37aff6bb24) | Jul 08, 2022 |
| HP            | EliteBook 745 G6            | [159ebeaa5e](https://linux-hardware.org/?probe=159ebeaa5e) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [f11f4826ba](https://linux-hardware.org/?probe=f11f4826ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [50e02d8554](https://linux-hardware.org/?probe=50e02d8554) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| ASUSTek       | K70IC                       | [baa2ddeb5a](https://linux-hardware.org/?probe=baa2ddeb5a) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| HP            | Mini 110-3100               | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Samsung       | 550XDA                      | [74bcded10f](https://linux-hardware.org/?probe=74bcded10f) | Jul 06, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| Acer          | Aspire 5755G                | [0dcb64ed5f](https://linux-hardware.org/?probe=0dcb64ed5f) | Jul 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [167fe0c2d1](https://linux-hardware.org/?probe=167fe0c2d1) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [59923a9781](https://linux-hardware.org/?probe=59923a9781) | Jul 06, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [17607e5f03](https://linux-hardware.org/?probe=17607e5f03) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [b8e2b7b6bd](https://linux-hardware.org/?probe=b8e2b7b6bd) | Jul 05, 2022 |
| Lenovo        | S21e-20 80M4                | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| HP            | ProBook 6475b               | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| Packard Be... | H17HV                       | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| Deffad        | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Dell          | Inspiron 5520               | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX392FN_UX392FN     | [b4699ba106](https://linux-hardware.org/?probe=b4699ba106) | Jun 30, 2022 |
| MSI           | CR620                       | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Dell          | XPS 15 9570                 | [8cf2281f01](https://linux-hardware.org/?probe=8cf2281f01) | Jun 27, 2022 |
| Acer          | Aspire A515-55G             | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Google        | Candy                       | [8888e44843](https://linux-hardware.org/?probe=8888e44843) | Jun 25, 2022 |
| Acer          | Aspire A315-42              | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| HP            | Laptop 15-db0xxx            | [26cd390b15](https://linux-hardware.org/?probe=26cd390b15) | Jun 24, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8f8ce01734](https://linux-hardware.org/?probe=8f8ce01734) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Dell          | XPS 13 9360                 | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Acer          | Swift SF314-54              | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [3bd256be91](https://linux-hardware.org/?probe=3bd256be91) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430s 23539MU      | [cb159502de](https://linux-hardware.org/?probe=cb159502de) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Toshiba       | Satellite C870-1C2          | [421b2e1975](https://linux-hardware.org/?probe=421b2e1975) | Jun 20, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| HP            | EliteBook 840 G1            | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| Global Dis... | W11651                      | [a28b308f7f](https://linux-hardware.org/?probe=a28b308f7f) | Jun 19, 2022 |
| Dell          | Inspiron N5010              | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a20ee1d5b6](https://linux-hardware.org/?probe=a20ee1d5b6) | Jun 17, 2022 |
| Dell          | Latitude E6540              | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Dell          | Precision M4700             | [3d10ec3c17](https://linux-hardware.org/?probe=3d10ec3c17) | Jun 15, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dell          | XPS 12 9Q23                 | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| GPU Compan... | GWTC116-2                   | [e849fd55ad](https://linux-hardware.org/?probe=e849fd55ad) | Jun 14, 2022 |
| Positivo      | Q464C                       | [1cb4cb4da1](https://linux-hardware.org/?probe=1cb4cb4da1) | Jun 13, 2022 |
| Positivo      | Q464C                       | [a772cd7eae](https://linux-hardware.org/?probe=a772cd7eae) | Jun 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [9baa7ce30e](https://linux-hardware.org/?probe=9baa7ce30e) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| HP            | Pavilion 17                 | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Positivo      | C4500D                      | [70dc4735fa](https://linux-hardware.org/?probe=70dc4735fa) | Jun 11, 2022 |
| Acer          | Aspire 5736Z                | [dcaa9a66f4](https://linux-hardware.org/?probe=dcaa9a66f4) | Jun 10, 2022 |
| Lenovo        | G50-70 20351                | [828f110a40](https://linux-hardware.org/?probe=828f110a40) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Samsung       | 600B4B/600B5B               | [431ccbf84a](https://linux-hardware.org/?probe=431ccbf84a) | Jun 08, 2022 |
| Toshiba       | Satellite A200              | [9719a84d3e](https://linux-hardware.org/?probe=9719a84d3e) | Jun 08, 2022 |
| Dell          | Inspiron 11-3168            | [9651975542](https://linux-hardware.org/?probe=9651975542) | Jun 07, 2022 |
| Dell          | Inspiron 11-3168            | [b43b02cdeb](https://linux-hardware.org/?probe=b43b02cdeb) | Jun 07, 2022 |
| HP            | Laptop 14-dq0xxx            | [39cfb21bae](https://linux-hardware.org/?probe=39cfb21bae) | Jun 07, 2022 |
| Lenovo        | ThinkPad T540p 20BF0038G... | [e7d830048d](https://linux-hardware.org/?probe=e7d830048d) | Jun 06, 2022 |
| Dell          | Inspiron 3521               | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [94d4930070](https://linux-hardware.org/?probe=94d4930070) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [96ed2caf25](https://linux-hardware.org/?probe=96ed2caf25) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4af3ead1a7](https://linux-hardware.org/?probe=4af3ead1a7) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [0ebbfb5b74](https://linux-hardware.org/?probe=0ebbfb5b74) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| HP            | Pavilion dv6                | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Dell          | Inspiron 15-5578            | [d88547de78](https://linux-hardware.org/?probe=d88547de78) | Jun 04, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Ematic        | EWT935DK                    | [13c5b6c48c](https://linux-hardware.org/?probe=13c5b6c48c) | Jun 03, 2022 |
| Medion        | WIM2180                     | [0548ef61b7](https://linux-hardware.org/?probe=0548ef61b7) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Medion        | WIM2180                     | [b645a2fa42](https://linux-hardware.org/?probe=b645a2fa42) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [71e59838a5](https://linux-hardware.org/?probe=71e59838a5) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [702f836250](https://linux-hardware.org/?probe=702f836250) | Jun 02, 2022 |
| Dell          | XPS 15 9510                 | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| Dell          | Inspiron 15-5578            | [7c1c1fa1ce](https://linux-hardware.org/?probe=7c1c1fa1ce) | Jun 01, 2022 |
| Apple         | MacBook2,1                  | [12cfa4cdb2](https://linux-hardware.org/?probe=12cfa4cdb2) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| HP            | EliteBook 8460p             | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| ASUSTek       | X450LD                      | [b77a4297da](https://linux-hardware.org/?probe=b77a4297da) | May 31, 2022 |
| Dell          | Inspiron 3541               | [20b5815ca3](https://linux-hardware.org/?probe=20b5815ca3) | May 31, 2022 |
| Dell          | Latitude E6510              | [4fe104ba1c](https://linux-hardware.org/?probe=4fe104ba1c) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [dbf473f0a0](https://linux-hardware.org/?probe=dbf473f0a0) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [574439c3c6](https://linux-hardware.org/?probe=574439c3c6) | May 30, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| HP            | Laptop 14-dq0xxx            | [fac9e55ae9](https://linux-hardware.org/?probe=fac9e55ae9) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Dell          | Latitude 3410               | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| HP            | Laptop 14-dq0xxx            | [7d47123b6c](https://linux-hardware.org/?probe=7d47123b6c) | May 28, 2022 |
| Dell          | Latitude D630               | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| Dell          | Inspiron 5423               | [bd9cd24b2d](https://linux-hardware.org/?probe=bd9cd24b2d) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ba19793a38](https://linux-hardware.org/?probe=ba19793a38) | May 26, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [7a7ef6ced7](https://linux-hardware.org/?probe=7a7ef6ced7) | May 26, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| HP            | ZBook 15 G2                 | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [a439693491](https://linux-hardware.org/?probe=a439693491) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [cca71eec7f](https://linux-hardware.org/?probe=cca71eec7f) | May 24, 2022 |
| Dell          | Venue 8 Pro 5830            | [c07937f5ea](https://linux-hardware.org/?probe=c07937f5ea) | May 24, 2022 |
| ASUSTek       | X201EP                      | [783e306676](https://linux-hardware.org/?probe=783e306676) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| Toshiba       | Satellite L75D-A            | [0a4b6bedbf](https://linux-hardware.org/?probe=0a4b6bedbf) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| Positivo      | CHT14B                      | [435bbd3b75](https://linux-hardware.org/?probe=435bbd3b75) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [8e5e8ea1ba](https://linux-hardware.org/?probe=8e5e8ea1ba) | May 20, 2022 |
| Medion        | Akoya S6214T                | [b0a0df98e0](https://linux-hardware.org/?probe=b0a0df98e0) | May 20, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Acer          | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| HP            | Pavilion g4                 | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Gateway       | NV55C                       | [16404d222a](https://linux-hardware.org/?probe=16404d222a) | May 18, 2022 |
| Gateway       | NV55C                       | [82fcde80bb](https://linux-hardware.org/?probe=82fcde80bb) | May 18, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [eb1da20105](https://linux-hardware.org/?probe=eb1da20105) | May 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 1395      | 55.82%  |
| Zorin 15 | 990       | 39.62%  |
| Zorin 12 | 114       | 4.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 2490      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 102       | 3.64%   |
| 5.11.0-38-generic | 98        | 3.5%    |
| 5.11.0-27-generic | 92        | 3.28%   |
| 5.15.0-46-generic | 88        | 3.14%   |
| 5.15.0-52-generic | 87        | 3.1%    |
| 5.13.0-30-generic | 73        | 2.61%   |
| 5.3.0-40-generic  | 67        | 2.39%   |
| 5.11.0-37-generic | 67        | 2.39%   |
| 5.11.0-40-generic | 65        | 2.32%   |
| 5.11.0-41-generic | 62        | 2.21%   |
| 5.4.0-42-generic  | 61        | 2.18%   |
| 5.15.0-58-generic | 61        | 2.18%   |
| 5.13.0-39-generic | 60        | 2.14%   |
| 5.11.0-34-generic | 57        | 2.03%   |
| 5.11.0-43-generic | 56        | 2%      |
| 5.3.0-46-generic  | 53        | 1.89%   |
| 5.15.0-48-generic | 51        | 1.82%   |
| 5.13.0-44-generic | 48        | 1.71%   |
| 5.3.0-51-generic  | 47        | 1.68%   |
| 5.0.0-37-generic  | 47        | 1.68%   |
| 5.13.0-40-generic | 45        | 1.61%   |
| 5.15.0-53-generic | 41        | 1.46%   |
| 5.13.0-35-generic | 40        | 1.43%   |
| 5.4.0-47-generic  | 38        | 1.36%   |
| 5.3.0-53-generic  | 37        | 1.32%   |
| 5.3.0-42-generic  | 36        | 1.28%   |
| 5.13.0-28-generic | 36        | 1.28%   |
| 5.4.0-45-generic  | 34        | 1.21%   |
| 5.15.0-41-generic | 33        | 1.18%   |
| 5.4.0-58-generic  | 31        | 1.11%   |
| 5.4.0-48-generic  | 31        | 1.11%   |
| 5.13.0-52-generic | 31        | 1.11%   |
| 5.4.0-65-generic  | 28        | 1%      |
| 5.13.0-27-generic | 28        | 1%      |
| 5.4.0-80-generic  | 26        | 0.93%   |
| 5.11.0-46-generic | 26        | 0.93%   |
| 5.13.0-41-generic | 25        | 0.89%   |
| 5.4.0-72-generic  | 23        | 0.82%   |
| 5.4.0-52-generic  | 23        | 0.82%   |
| 5.11.0-36-generic | 22        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 568       | 21.85%  |
| 5.11.0  | 545       | 20.96%  |
| 5.15.0  | 470       | 18.08%  |
| 5.13.0  | 404       | 15.54%  |
| 5.3.0   | 312       | 12%     |
| 4.15.0  | 110       | 4.23%   |
| 5.0.0   | 89        | 3.42%   |
| 4.18.0  | 44        | 1.69%   |
| 5.8.0   | 22        | 0.85%   |
| 5.14.0  | 6         | 0.23%   |
| 4.4.0   | 4         | 0.15%   |
| 5.6.0   | 2         | 0.08%   |
| 5.16.0  | 2         | 0.08%   |
| 5.10.0  | 2         | 0.08%   |
| 6.0.0   | 1         | 0.04%   |
| 5.9.12  | 1         | 0.04%   |
| 5.9.0   | 1         | 0.04%   |
| 5.7.1   | 1         | 0.04%   |
| 5.4.180 | 1         | 0.04%   |
| 5.4.1   | 1         | 0.04%   |
| 5.19.9  | 1         | 0.04%   |
| 5.19.14 | 1         | 0.04%   |
| 5.19.12 | 1         | 0.04%   |
| 5.19.1  | 1         | 0.04%   |
| 5.19.0  | 1         | 0.04%   |
| 5.18.6  | 1         | 0.04%   |
| 5.18.15 | 1         | 0.04%   |
| 5.16.12 | 1         | 0.04%   |
| 5.15.49 | 1         | 0.04%   |
| 5.15.24 | 1         | 0.04%   |
| 5.13.18 | 1         | 0.04%   |
| 5.10.35 | 1         | 0.04%   |
| 5.10.16 | 1         | 0.04%   |
| 4.13.0  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 570       | 21.92%  |
| 5.11    | 545       | 20.96%  |
| 5.15    | 472       | 18.15%  |
| 5.13    | 405       | 15.58%  |
| 5.3     | 312       | 12%     |
| 4.15    | 110       | 4.23%   |
| 5.0     | 89        | 3.42%   |
| 4.18    | 44        | 1.69%   |
| 5.8     | 22        | 0.85%   |
| 5.14    | 6         | 0.23%   |
| 5.19    | 5         | 0.19%   |
| 5.10    | 4         | 0.15%   |
| 4.4     | 4         | 0.15%   |
| 5.16    | 3         | 0.12%   |
| 5.9     | 2         | 0.08%   |
| 5.6     | 2         | 0.08%   |
| 5.18    | 2         | 0.08%   |
| 6.0     | 1         | 0.04%   |
| 5.7     | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2224      | 89.21%  |
| i686   | 269       | 10.79%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 1736      | 68.94%  |
| XFCE       | 597       | 23.71%  |
| Unknown    | 168       | 6.67%   |
| X-Cinnamon | 7         | 0.28%   |
| KDE        | 3         | 0.12%   |
| Unity      | 2         | 0.08%   |
| LXDE       | 1         | 0.04%   |
| KDE5       | 1         | 0.04%   |
| i3         | 1         | 0.04%   |
| Cinnamon   | 1         | 0.04%   |
| Budgie     | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2362      | 94.07%  |
| Unknown | 106       | 4.22%   |
| Wayland | 43        | 1.71%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2019      | 79.96%  |
| GDM3    | 182       | 7.21%   |
| GDM     | 176       | 6.97%   |
| LightDM | 139       | 5.5%    |
| TDM     | 6         | 0.24%   |
| SDDM    | 2         | 0.08%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 868       | 34.57%  |
| de_DE   | 182       | 7.25%   |
| pt_BR   | 164       | 6.53%   |
| en_GB   | 145       | 5.77%   |
| Unknown | 126       | 5.02%   |
| it_IT   | 95        | 3.78%   |
| en_IN   | 79        | 3.15%   |
| fr_FR   | 76        | 3.03%   |
| en_CA   | 75        | 2.99%   |
| es_ES   | 73        | 2.91%   |
| pl_PL   | 60        | 2.39%   |
| en_AU   | 42        | 1.67%   |
| pt_PT   | 37        | 1.47%   |
| es_MX   | 36        | 1.43%   |
| nl_NL   | 32        | 1.27%   |
| ru_RU   | 31        | 1.23%   |
| cs_CZ   | 28        | 1.12%   |
| es_AR   | 25        | 1%      |
| en_ZA   | 25        | 1%      |
| tr_TR   | 20        | 0.8%    |
| C       | 20        | 0.8%    |
| es_CL   | 18        | 0.72%   |
| sv_SE   | 17        | 0.68%   |
| en_NZ   | 16        | 0.64%   |
| de_AT   | 16        | 0.64%   |
| ja_JP   | 13        | 0.52%   |
| hu_HU   | 12        | 0.48%   |
| fr_BE   | 12        | 0.48%   |
| fr_CA   | 11        | 0.44%   |
| nl_BE   | 10        | 0.4%    |
| el_GR   | 10        | 0.4%    |
| es_CO   | 9         | 0.36%   |
| da_DK   | 8         | 0.32%   |
| ru_UA   | 7         | 0.28%   |
| es_PE   | 7         | 0.28%   |
| en_PH   | 7         | 0.28%   |
| de_CH   | 7         | 0.28%   |
| ro_RO   | 6         | 0.24%   |
| hr_HR   | 5         | 0.2%    |
| fi_FI   | 5         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1354      | 53.79%  |
| EFI  | 1163      | 46.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2353      | 94.16%  |
| Overlay | 55        | 2.2%    |
| Zfs     | 26        | 1.04%   |
| Btrfs   | 22        | 0.88%   |
| Ext2    | 20        | 0.8%    |
| Unknown | 17        | 0.68%   |
| Xfs     | 3         | 0.12%   |
| Ext3    | 3         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2235      | 89.04%  |
| GPT     | 210       | 8.37%   |
| MBR     | 65        | 2.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2373      | 94.73%  |
| Yes       | 132       | 5.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2081      | 83.11%  |
| Yes       | 423       | 16.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 575       | 23.09%  |
| Dell                | 382       | 15.34%  |
| Lenovo              | 370       | 14.86%  |
| ASUSTek Computer    | 252       | 10.12%  |
| Acer                | 200       | 8.03%   |
| Toshiba             | 144       | 5.78%   |
| Apple               | 57        | 2.29%   |
| Samsung Electronics | 52        | 2.09%   |
| Sony                | 46        | 1.85%   |
| MSI                 | 41        | 1.65%   |
| Packard Bell        | 26        | 1.04%   |
| Unknown             | 26        | 1.04%   |
| HUAWEI              | 17        | 0.68%   |
| Google              | 17        | 0.68%   |
| Fujitsu Siemens     | 17        | 0.68%   |
| Fujitsu             | 17        | 0.68%   |
| Positivo            | 16        | 0.64%   |
| Medion              | 12        | 0.48%   |
| Notebook            | 11        | 0.44%   |
| Alienware           | 10        | 0.4%    |
| Panasonic           | 9         | 0.36%   |
| Gateway             | 8         | 0.32%   |
| Chuwi               | 8         | 0.32%   |
| AMI                 | 7         | 0.28%   |
| Insyde              | 6         | 0.24%   |
| eMachines           | 6         | 0.24%   |
| NEC Computers       | 5         | 0.2%    |
| Multilaser          | 5         | 0.2%    |
| LG Electronics      | 5         | 0.2%    |
| Itautec             | 5         | 0.2%    |
| GPU Company         | 5         | 0.2%    |
| Ematic              | 5         | 0.2%    |
| Semp Toshiba        | 4         | 0.16%   |
| Razer               | 4         | 0.16%   |
| Quanta              | 4         | 0.16%   |
| Jumper              | 4         | 0.16%   |
| Digibras            | 4         | 0.16%   |
| Clevo               | 4         | 0.16%   |
| TUXEDO              | 3         | 0.12%   |
| TrekStor            | 3         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 51        | 2.05%   |
| HP Notebook             | 26        | 1.04%   |
| HP Pavilion Notebook    | 16        | 0.64%   |
| HP Pavilion dv6         | 13        | 0.52%   |
| HP 15                   | 12        | 0.48%   |
| Toshiba Satellite C660  | 10        | 0.4%    |
| HP Pavilion dv7         | 10        | 0.4%    |
| HP Pavilion 15          | 9         | 0.36%   |
| Dell Inspiron 1545      | 9         | 0.36%   |
| HP Pavilion g6          | 8         | 0.32%   |
| HP Laptop 15-bw0xx      | 8         | 0.32%   |
| Dell Latitude E6540     | 8         | 0.32%   |
| Dell Latitude D630      | 8         | 0.32%   |
| Dell Inspiron 15-3567   | 8         | 0.32%   |
| Apple MacBookPro8,1     | 8         | 0.32%   |
| Dell Latitude E6410     | 7         | 0.28%   |
| Dell Latitude E6400     | 7         | 0.28%   |
| Dell Inspiron 3521      | 7         | 0.28%   |
| Dell Inspiron 1525      | 7         | 0.28%   |
| HP ProBook 640 G1       | 6         | 0.24%   |
| HP Pavilion g7          | 6         | 0.24%   |
| HP Pavilion dv6700      | 6         | 0.24%   |
| HP Pavilion 17          | 6         | 0.24%   |
| HP EliteBook 840 G1     | 6         | 0.24%   |
| Dell Inspiron 7520      | 6         | 0.24%   |
| Toshiba Satellite A100  | 5         | 0.2%    |
| HP ProBook 4540s        | 5         | 0.2%    |
| HP Pavilion dv5         | 5         | 0.2%    |
| HP Laptop 15-db0xxx     | 5         | 0.2%    |
| HP EliteBook 8460p      | 5         | 0.2%    |
| HP Compaq Presario CQ60 | 5         | 0.2%    |
| HP 14                   | 5         | 0.2%    |
| Dell Latitude E6430     | 5         | 0.2%    |
| Dell Latitude E6420     | 5         | 0.2%    |
| Dell Latitude E5500     | 5         | 0.2%    |
| Dell Latitude E5440     | 5         | 0.2%    |
| Dell Inspiron N5010     | 5         | 0.2%    |
| Dell Inspiron 3542      | 5         | 0.2%    |
| Apple MacBookPro11,1    | 5         | 0.2%    |
| Toshiba Satellite L500  | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 149       | 5.98%   |
| HP Pavilion           | 148       | 5.94%   |
| Lenovo ThinkPad       | 145       | 5.82%   |
| Acer Aspire           | 142       | 5.7%    |
| Dell Latitude         | 140       | 5.62%   |
| Toshiba Satellite     | 122       | 4.9%    |
| Lenovo IdeaPad        | 120       | 4.82%   |
| HP EliteBook          | 70        | 2.81%   |
| HP ProBook            | 64        | 2.57%   |
| Unknown               | 51        | 2.05%   |
| HP Laptop             | 50        | 2.01%   |
| HP Compaq             | 46        | 1.85%   |
| ASUS VivoBook         | 33        | 1.33%   |
| Dell Vostro           | 27        | 1.08%   |
| HP Notebook           | 26        | 1.04%   |
| Packard Bell EasyNote | 24        | 0.96%   |
| HP ENVY               | 20        | 0.8%    |
| Dell XPS              | 19        | 0.76%   |
| HP Stream             | 17        | 0.68%   |
| HP Presario           | 14        | 0.56%   |
| HP 15                 | 14        | 0.56%   |
| Dell Precision        | 14        | 0.56%   |
| ASUS ZenBook          | 14        | 0.56%   |
| HP 255                | 13        | 0.52%   |
| Dell Studio           | 12        | 0.48%   |
| HP OMEN               | 11        | 0.44%   |
| Fujitsu LIFEBOOK      | 11        | 0.44%   |
| ASUS ROG              | 11        | 0.44%   |
| Apple MacBookPro8     | 11        | 0.44%   |
| Lenovo Yoga           | 9         | 0.36%   |
| HP ZBook              | 9         | 0.36%   |
| Fujitsu Siemens AMILO | 9         | 0.36%   |
| Dell System           | 9         | 0.36%   |
| Toshiba PORTEGE       | 8         | 0.32%   |
| HP Mini               | 8         | 0.32%   |
| ASUS ASUS             | 8         | 0.32%   |
| Acer Swift            | 8         | 0.32%   |
| ASUS TUF              | 7         | 0.28%   |
| Apple MacBookPro11    | 7         | 0.28%   |
| Acer TravelMate       | 7         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 238       | 9.56%   |
| 2012    | 212       | 8.51%   |
| 2013    | 208       | 8.35%   |
| 2010    | 191       | 7.67%   |
| 2008    | 174       | 6.99%   |
| 2014    | 155       | 6.22%   |
| 2018    | 151       | 6.06%   |
| 2019    | 150       | 6.02%   |
| 2017    | 134       | 5.38%   |
| 2015    | 133       | 5.34%   |
| 2007    | 133       | 5.34%   |
| 2009    | 128       | 5.14%   |
| 2016    | 125       | 5.02%   |
| 2021    | 124       | 4.98%   |
| 2020    | 117       | 4.7%    |
| 2006    | 51        | 2.05%   |
| 2005    | 34        | 1.37%   |
| 2022    | 25        | 1%      |
| Unknown | 4         | 0.16%   |
| 2003    | 2         | 0.08%   |
| 2004    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2490      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2218      | 88.54%  |
| Enabled  | 287       | 11.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2469      | 99.16%  |
| Yes  | 21        | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 756       | 30.18%  |
| 4.01-8.0    | 691       | 27.58%  |
| 8.01-16.0   | 309       | 12.34%  |
| 1.01-2.0    | 294       | 11.74%  |
| 16.01-24.0  | 208       | 8.3%    |
| 2.01-3.0    | 100       | 3.99%   |
| 32.01-64.0  | 66        | 2.63%   |
| 0.51-1.0    | 65        | 2.59%   |
| 64.01-256.0 | 9         | 0.36%   |
| 24.01-32.0  | 7         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1180      | 44.15%  |
| 2.01-3.0   | 718       | 26.86%  |
| 3.01-4.0   | 285       | 10.66%  |
| 0.51-1.0   | 251       | 9.39%   |
| 4.01-8.0   | 185       | 6.92%   |
| 8.01-16.0  | 26        | 0.97%   |
| 0.01-0.5   | 25        | 0.94%   |
| 24.01-32.0 | 2         | 0.07%   |
| 16.01-24.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1931      | 76.41%  |
| 2      | 521       | 20.62%  |
| 3      | 53        | 2.1%    |
| 0      | 10        | 0.4%    |
| 4      | 8         | 0.32%   |
| 5      | 2         | 0.08%   |
| 8      | 1         | 0.04%   |
| 6      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1273      | 50.92%  |
| No        | 1227      | 49.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2080      | 83.33%  |
| No        | 416       | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2411      | 96.75%  |
| No        | 81        | 3.25%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1598      | 63.61%  |
| No        | 914       | 36.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 515       | 20.6%   |
| Germany      | 215       | 8.6%    |
| Brazil       | 188       | 7.52%   |
| UK           | 144       | 5.76%   |
| Italy        | 102       | 4.08%   |
| Canada       | 97        | 3.88%   |
| India        | 85        | 3.4%    |
| Spain        | 81        | 3.24%   |
| France       | 75        | 3%      |
| Poland       | 60        | 2.4%    |
| Mexico       | 56        | 2.24%   |
| Netherlands  | 55        | 2.2%    |
| Australia    | 48        | 1.92%   |
| Portugal     | 42        | 1.68%   |
| Belgium      | 33        | 1.32%   |
| Sweden       | 32        | 1.28%   |
| Russia       | 32        | 1.28%   |
| Czechia      | 32        | 1.28%   |
| South Africa | 31        | 1.24%   |
| Argentina    | 31        | 1.24%   |
| Austria      | 29        | 1.16%   |
| Romania      | 26        | 1.04%   |
| Turkey       | 25        | 1%      |
| Indonesia    | 25        | 1%      |
| Greece       | 22        | 0.88%   |
| Switzerland  | 20        | 0.8%    |
| New Zealand  | 19        | 0.76%   |
| Japan        | 18        | 0.72%   |
| Chile        | 18        | 0.72%   |
| Serbia       | 15        | 0.6%    |
| Norway       | 15        | 0.6%    |
| Hungary      | 15        | 0.6%    |
| Colombia     | 15        | 0.6%    |
| Egypt        | 14        | 0.56%   |
| Bulgaria     | 13        | 0.52%   |
| Ukraine      | 12        | 0.48%   |
| Philippines  | 10        | 0.4%    |
| Kenya        | 10        | 0.4%    |
| Denmark      | 10        | 0.4%    |
| Israel       | 9         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 20        | 0.77%   |
| Sydney         | 19        | 0.73%   |
| Berlin         | 17        | 0.65%   |
| Vienna         | 16        | 0.62%   |
| Madrid         | 15        | 0.58%   |
| Munich         | 13        | 0.5%    |
| Athens         | 13        | 0.5%    |
| Rome           | 12        | 0.46%   |
| Montreal       | 12        | 0.46%   |
| Milan          | 12        | 0.46%   |
| Johannesburg   | 12        | 0.46%   |
| Auckland       | 12        | 0.46%   |
| Rio de Janeiro | 11        | 0.42%   |
| New York       | 11        | 0.42%   |
| Istanbul       | 11        | 0.42%   |
| Hamburg        | 11        | 0.42%   |
| Cairo          | 11        | 0.42%   |
| Mexico City    | 10        | 0.38%   |
| Jakarta        | 10        | 0.38%   |
| Toronto        | 9         | 0.35%   |
| Stockholm      | 9         | 0.35%   |
| Seattle        | 9         | 0.35%   |
| Prague         | 9         | 0.35%   |
| Paris          | 9         | 0.35%   |
| Nairobi        | 9         | 0.35%   |
| Moscow         | 9         | 0.35%   |
| Dallas         | 9         | 0.35%   |
| Warsaw         | 8         | 0.31%   |
| Krakow         | 8         | 0.31%   |
| Glasgow        | 8         | 0.31%   |
| Bengaluru      | 8         | 0.31%   |
| Belgrade       | 8         | 0.31%   |
| Tel Aviv       | 7         | 0.27%   |
| Perth          | 7         | 0.27%   |
| Buenos Aires   | 7         | 0.27%   |
| Bucharest      | 7         | 0.27%   |
| Barcelona      | 7         | 0.27%   |
| Amsterdam      | 7         | 0.27%   |
| Zurich         | 6         | 0.23%   |
| Stuttgart      | 6         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 400       | 483    | 13.84%  |
| WDC                       | 365       | 435    | 12.63%  |
| Toshiba                   | 318       | 360    | 11%     |
| Samsung Electronics       | 318       | 430    | 11%     |
| Unknown                   | 238       | 328    | 8.23%   |
| SanDisk                   | 158       | 182    | 5.47%   |
| Hitachi                   | 155       | 178    | 5.36%   |
| Kingston                  | 130       | 153    | 4.5%    |
| Crucial                   | 101       | 121    | 3.49%   |
| HGST                      | 86        | 101    | 2.97%   |
| Intel                     | 67        | 85     | 2.32%   |
| SK hynix                  | 55        | 66     | 1.9%    |
| Micron Technology         | 41        | 48     | 1.42%   |
| Fujitsu                   | 40        | 42     | 1.38%   |
| A-DATA Technology         | 36        | 38     | 1.25%   |
| China                     | 27        | 31     | 0.93%   |
| Intenso                   | 21        | 22     | 0.73%   |
| Apple                     | 20        | 21     | 0.69%   |
| PNY                       | 19        | 22     | 0.66%   |
| KIOXIA                    | 17        | 18     | 0.59%   |
| SPCC                      | 15        | 17     | 0.52%   |
| LITEON                    | 15        | 19     | 0.52%   |
| LITEONIT                  | 14        | 16     | 0.48%   |
| Transcend                 | 13        | 18     | 0.45%   |
| Netac                     | 13        | 13     | 0.45%   |
| Phison                    | 12        | 14     | 0.42%   |
| Patriot                   | 11        | 13     | 0.38%   |
| Team                      | 10        | 11     | 0.35%   |
| JMicron Technology        | 10        | 11     | 0.35%   |
| Unknown                   | 10        | 12     | 0.35%   |
| GOODRAM                   | 9         | 10     | 0.31%   |
| SABRENT                   | 8         | 9      | 0.28%   |
| OCZ                       | 8         | 9      | 0.28%   |
| ASMT                      | 6         | 6      | 0.21%   |
| Lite-On                   | 5         | 7      | 0.17%   |
| Hewlett-Packard           | 5         | 5      | 0.17%   |
| Silicon Motion            | 4         | 4      | 0.14%   |
| Plextor                   | 4         | 4      | 0.14%   |
| Micron/Crucial Technology | 4         | 4      | 0.14%   |
| Lexar                     | 4         | 4      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 91        | 3.03%   |
| Unknown MMC Card  64GB                 | 59        | 1.96%   |
| Toshiba MQ01ABF050 500GB               | 45        | 1.5%    |
| Seagate ST1000LM035-1RK172 1TB         | 42        | 1.4%    |
| Toshiba MQ01ABD100 1TB                 | 33        | 1.1%    |
| Seagate ST500LT012-1DG142 500GB        | 32        | 1.06%   |
| Kingston SA400S37240G 240GB SSD        | 30        | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 29        | 0.96%   |
| Toshiba MQ04ABF100 1TB                 | 28        | 0.93%   |
| Unknown MMC Card  128GB                | 25        | 0.83%   |
| Samsung NVMe SSD Drive 512GB           | 24        | 0.8%    |
| Seagate ST9500325AS 500GB              | 23        | 0.76%   |
| Unknown MMC Card  16GB                 | 22        | 0.73%   |
| Kingston SA400S37480G 480GB SSD        | 22        | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 20        | 0.67%   |
| SanDisk NVMe SSD Drive 256GB           | 20        | 0.67%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 19        | 0.63%   |
| Crucial CT240BX500SSD1 240GB           | 19        | 0.63%   |
| Kingston SA400S37120G 120GB SSD        | 18        | 0.6%    |
| Intel NVMe SSD Drive 512GB             | 17        | 0.57%   |
| HGST HTS725050A7E630 500GB             | 17        | 0.57%   |
| Seagate Expansion 240GB                | 16        | 0.53%   |
| Hitachi HTS545032B9A300 320GB          | 16        | 0.53%   |
| HGST HTS721010A9E630 1TB               | 16        | 0.53%   |
| HGST HTS541010A9E680 1TB               | 16        | 0.53%   |
| Crucial CT500MX500SSD1 500GB           | 16        | 0.53%   |
| Samsung SSD 850 EVO 500GB              | 15        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB           | 14        | 0.47%   |
| Samsung SSD 860 EVO 500GB              | 13        | 0.43%   |
| Samsung SSD 860 EVO 250GB              | 12        | 0.4%    |
| HGST HTS545050A7E680 500GB             | 12        | 0.4%    |
| Unknown SD/MMC/MS PRO 2GB              | 11        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD       | 11        | 0.37%   |
| Seagate ST9320325AS 320GB              | 10        | 0.33%   |
| Seagate ST500LT012-9WS142 500GB        | 10        | 0.33%   |
| Seagate ST500LM021-1KJ152 500GB        | 10        | 0.33%   |
| Hitachi HTS545050A7E380 500GB          | 10        | 0.33%   |
| Hitachi HTS543232A7A384 320GB          | 10        | 0.33%   |
| HGST HTS545050A7E380 500GB             | 10        | 0.33%   |
| Unknown                                | 10        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 397       | 476    | 29.56%  |
| WDC                 | 316       | 368    | 23.53%  |
| Toshiba             | 272       | 304    | 20.25%  |
| Hitachi             | 155       | 178    | 11.54%  |
| HGST                | 86        | 101    | 6.4%    |
| Fujitsu             | 40        | 42     | 2.98%   |
| Samsung Electronics | 39        | 44     | 2.9%    |
| Unknown             | 11        | 16     | 0.82%   |
| SABRENT             | 8         | 9      | 0.6%    |
| ASMT                | 6         | 6      | 0.45%   |
| IBM/Hitachi         | 4         | 5      | 0.3%    |
| Apple               | 3         | 3      | 0.22%   |
| JMicron Technology  | 2         | 2      | 0.15%   |
| USB3.0              | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 182       | 244    | 19.83%  |
| Kingston            | 112       | 134    | 12.2%   |
| Crucial             | 99        | 117    | 10.78%  |
| SanDisk             | 94        | 110    | 10.24%  |
| WDC                 | 40        | 51     | 4.36%   |
| A-DATA Technology   | 32        | 34     | 3.49%   |
| Intel               | 31        | 36     | 3.38%   |
| Toshiba             | 29        | 33     | 3.16%   |
| China               | 26        | 30     | 2.83%   |
| SK hynix            | 22        | 26     | 2.4%    |
| Micron Technology   | 20        | 23     | 2.18%   |
| PNY                 | 19        | 22     | 2.07%   |
| LITEON              | 15        | 19     | 1.63%   |
| Apple               | 15        | 15     | 1.63%   |
| SPCC                | 14        | 16     | 1.53%   |
| LITEONIT            | 14        | 16     | 1.53%   |
| Intenso             | 14        | 14     | 1.53%   |
| Transcend           | 13        | 18     | 1.42%   |
| Netac               | 13        | 13     | 1.42%   |
| Patriot             | 11        | 13     | 1.2%    |
| Team                | 10        | 11     | 1.09%   |
| GOODRAM             | 9         | 10     | 0.98%   |
| OCZ                 | 8         | 9      | 0.87%   |
| JMicron Technology  | 6         | 7      | 0.65%   |
| Plextor             | 4         | 4      | 0.44%   |
| Hewlett-Packard     | 4         | 4      | 0.44%   |
| Unknown             | 4         | 6      | 0.44%   |
| Lexar               | 3         | 3      | 0.33%   |
| BHT                 | 3         | 4      | 0.33%   |
| Verbatim            | 2         | 2      | 0.22%   |
| Vaseky              | 2         | 3      | 0.22%   |
| TO Exter            | 2         | 3      | 0.22%   |
| TCSUNBOW            | 2         | 2      | 0.22%   |
| Mushkin             | 2         | 2      | 0.22%   |
| Leven               | 2         | 2      | 0.22%   |
| KingSpec            | 2         | 2      | 0.22%   |
| KingDian            | 2         | 2      | 0.22%   |
| HS-SSD-E100         | 2         | 2      | 0.22%   |
| ZOTAC               | 1         | 1      | 0.11%   |
| Zheino              | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1309      | 1558   | 46.63%  |
| SSD     | 874       | 1098   | 31.14%  |
| NVMe    | 346       | 451    | 12.33%  |
| MMC     | 238       | 325    | 8.48%   |
| Unknown | 40        | 45     | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2047      | 2579   | 75.4%   |
| NVMe | 346       | 451    | 12.74%  |
| MMC  | 238       | 325    | 8.77%   |
| SAS  | 84        | 122    | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1624      | 1991   | 75.19%  |
| 0.51-1.0   | 483       | 592    | 22.36%  |
| 1.01-2.0   | 35        | 48     | 1.62%   |
| 3.01-4.0   | 10        | 14     | 0.46%   |
| 4.01-10.0  | 8         | 11     | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 887       | 34.7%   |
| 251-500        | 668       | 26.13%  |
| 501-1000       | 311       | 12.17%  |
| 51-100         | 291       | 11.38%  |
| 21-50          | 178       | 6.96%   |
| 1001-2000      | 79        | 3.09%   |
| 1-20           | 79        | 3.09%   |
| Unknown        | 24        | 0.94%   |
| More than 3000 | 23        | 0.9%    |
| 2001-3000      | 16        | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1369      | 51.82%  |
| 21-50          | 608       | 23.01%  |
| 51-100         | 254       | 9.61%   |
| 101-250        | 219       | 8.29%   |
| 251-500        | 104       | 3.94%   |
| 501-1000       | 40        | 1.51%   |
| Unknown        | 24        | 0.91%   |
| 1001-2000      | 11        | 0.42%   |
| More than 3000 | 10        | 0.38%   |
| 2001-3000      | 3         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 3         | 3      | 6%      |
| Toshiba MQ02ABD100H 1TB                             | 2         | 2      | 4%      |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 4%      |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 4%      |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1      | 2%      |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2%      |
| WDC WD5000BEVT-24A0RT0 500GB                        | 1         | 1      | 2%      |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 2%      |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 1      | 2%      |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 2%      |
| WDC WD10JPVT-55A1YT0 1TB                            | 1         | 1      | 2%      |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 2%      |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2%      |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2%      |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 2%      |
| Toshiba MK2046GSX 200GB                             | 1         | 1      | 2%      |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2%      |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2%      |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2%      |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 2%      |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2%      |
| Seagate ST9200420ASG 200GB                          | 1         | 1      | 2%      |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 2%      |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 2%      |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2%      |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 2%      |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2%      |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD    | 1         | 1      | 2%      |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD       | 1         | 1      | 2%      |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2%      |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD               | 1         | 1      | 2%      |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 2%      |
| Kingston SA400S37120G 120GB SSD                     | 1         | 1      | 2%      |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 2%      |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2%      |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 2%      |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2%      |
| Hitachi HTS542516K9SA00 160GB                       | 1         | 1      | 2%      |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 32%     |
| Toshiba             | 9         | 9      | 18%     |
| WDC                 | 7         | 7      | 14%     |
| HGST                | 5         | 5      | 10%     |
| Hitachi             | 4         | 4      | 8%      |
| Kingston            | 3         | 3      | 6%      |
| Samsung Electronics | 2         | 2      | 4%      |
| SK hynix            | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| LITEONIT            | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 40%     |
| Toshiba | 8         | 8      | 20%     |
| WDC     | 7         | 7      | 17.5%   |
| HGST    | 5         | 5      | 12.5%   |
| Hitachi | 4         | 4      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 40     | 80%     |
| SSD  | 9         | 9      | 18%     |
| NVMe | 1         | 1      | 2%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2283      | 3196   | 90.42%  |
| Works    | 191       | 229    | 7.56%   |
| Malfunc  | 49        | 50     | 1.94%   |
| Failed   | 2         | 2      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1842      | 70.47%  |
| AMD                              | 332       | 12.7%   |
| Samsung Electronics              | 118       | 4.51%   |
| SanDisk                          | 66        | 2.52%   |
| Nvidia                           | 42        | 1.61%   |
| SK hynix                         | 31        | 1.19%   |
| Silicon Integrated Systems [SiS] | 28        | 1.07%   |
| Micron Technology                | 22        | 0.84%   |
| Kingston Technology Company      | 20        | 0.77%   |
| Toshiba America Info Systems     | 19        | 0.73%   |
| KIOXIA                           | 17        | 0.65%   |
| Phison Electronics               | 13        | 0.5%    |
| VIA Technologies                 | 11        | 0.42%   |
| Micron/Crucial Technology        | 7         | 0.27%   |
| ADATA Technology                 | 6         | 0.23%   |
| Silicon Motion                   | 5         | 0.19%   |
| Marvell Technology Group         | 5         | 0.19%   |
| Lite-On Technology               | 5         | 0.19%   |
| JMicron Technology               | 5         | 0.19%   |
| Union Memory (Shenzhen)          | 4         | 0.15%   |
| ASMedia Technology               | 4         | 0.15%   |
| Realtek Semiconductor            | 3         | 0.11%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| Silicon Image                    | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Solid State Storage Technology   | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 250       | 8.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 204       | 6.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 172       | 5.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 166       | 5.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 142       | 4.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 138       | 4.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 109       | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 101       | 3.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 91        | 3.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 90        | 3.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 65        | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 63        | 2.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 53        | 1.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 51        | 1.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 47        | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 47        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 46        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 39        | 1.32%   |
| Intel Volume Management Device NVMe RAID Controller                              | 36        | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 36        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 35        | 1.19%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 34        | 1.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 34        | 1.15%   |
| Samsung NVMe SSD Controller 980                                                  | 31        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 28        | 0.95%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 27        | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 27        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 27        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 25        | 0.85%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 22        | 0.75%   |
| Micron Non-Volatile memory controller                                            | 22        | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 18        | 0.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 18        | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 17        | 0.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 17        | 0.58%   |
| Intel Tiger Lake-LP SATA Controller                                              | 17        | 0.58%   |
| Intel Comet Lake SATA AHCI Controller                                            | 17        | 0.58%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 16        | 0.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 16        | 0.54%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1829      | 65.84%  |
| IDE  | 412       | 14.83%  |
| NVMe | 349       | 12.56%  |
| RAID | 188       | 6.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2086      | 83.78%  |
| AMD          | 403       | 16.18%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 33        | 1.32%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 31        | 1.24%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 29        | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 25        | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.96%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 22        | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 20        | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 20        | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 19        | 0.76%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.72%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 18        | 0.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.72%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 0.72%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.68%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 17        | 0.68%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 17        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 16        | 0.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.64%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 16        | 0.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 16        | 0.64%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 16        | 0.64%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 16        | 0.64%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.6%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 15        | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 15        | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 14        | 0.56%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 14        | 0.56%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 14        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 512       | 20.55%  |
| Intel Core i7           | 372       | 14.93%  |
| Intel Core i3           | 258       | 10.35%  |
| Intel Core 2 Duo        | 218       | 8.75%   |
| Intel Celeron           | 207       | 8.31%   |
| Intel Atom              | 144       | 5.78%   |
| Intel Pentium           | 87        | 3.49%   |
| Other                   | 80        | 3.21%   |
| AMD Ryzen 5             | 56        | 2.25%   |
| AMD A6                  | 47        | 1.89%   |
| Intel Genuine           | 41        | 1.65%   |
| AMD Ryzen 7             | 38        | 1.52%   |
| Intel Pentium Dual-Core | 35        | 1.4%    |
| AMD A4                  | 34        | 1.36%   |
| Intel Pentium Dual      | 29        | 1.16%   |
| Intel Pentium M         | 23        | 0.92%   |
| Intel Core 2            | 23        | 0.92%   |
| Intel Celeron M         | 23        | 0.92%   |
| AMD A10                 | 23        | 0.92%   |
| AMD E1                  | 21        | 0.84%   |
| AMD Ryzen 3             | 19        | 0.76%   |
| AMD A8                  | 19        | 0.76%   |
| AMD E                   | 17        | 0.68%   |
| AMD Turion 64 X2 Mobile | 15        | 0.6%    |
| AMD Turion 64 Mobile    | 9         | 0.36%   |
| Intel Core M            | 8         | 0.32%   |
| Intel Celeron Dual-Core | 8         | 0.32%   |
| AMD Athlon II           | 8         | 0.32%   |
| Intel Pentium Silver    | 7         | 0.28%   |
| Intel Core Duo          | 7         | 0.28%   |
| AMD E2                  | 7         | 0.28%   |
| AMD Athlon 64 X2        | 7         | 0.28%   |
| AMD Ryzen 9             | 6         | 0.24%   |
| AMD Mobile Sempron      | 6         | 0.24%   |
| AMD C-50                | 6         | 0.24%   |
| AMD Athlon X2           | 6         | 0.24%   |
| AMD Athlon              | 6         | 0.24%   |
| AMD Sempron             | 5         | 0.2%    |
| AMD C-60                | 5         | 0.2%    |
| Intel Pentium 4         | 4         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1608      | 64.53%  |
| 4      | 585       | 23.48%  |
| 1      | 171       | 6.86%   |
| 6      | 68        | 2.73%   |
| 8      | 52        | 2.09%   |
| 14     | 3         | 0.12%   |
| 10     | 2         | 0.08%   |
| 3      | 2         | 0.08%   |
| 16     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2490      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1442      | 57.91%  |
| 1      | 1048      | 42.09%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2376      | 95.38%  |
| 32-bit         | 113       | 4.54%   |
| Unknown        | 2         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 230       | 9.11%   |
| Unknown    | 219       | 8.67%   |
| 0x306a9    | 181       | 7.17%   |
| 0x1067a    | 138       | 5.47%   |
| 0x40651    | 114       | 4.51%   |
| 0x20655    | 94        | 3.72%   |
| 0x6fd      | 80        | 3.17%   |
| 0x406e3    | 76        | 3.01%   |
| 0x306d4    | 76        | 3.01%   |
| 0x306c3    | 73        | 2.89%   |
| 0x30678    | 71        | 2.81%   |
| 0x806ea    | 58        | 2.3%    |
| 0x806e9    | 58        | 2.3%    |
| 0x406c4    | 50        | 1.98%   |
| 0x10676    | 44        | 1.74%   |
| 0x806c1    | 43        | 1.7%    |
| 0x806ec    | 40        | 1.58%   |
| 0x906ea    | 36        | 1.43%   |
| 0x20652    | 35        | 1.39%   |
| 0x406c3    | 34        | 1.35%   |
| 0x106ca    | 33        | 1.31%   |
| 0x506c9    | 32        | 1.27%   |
| 0x06006705 | 30        | 1.19%   |
| 0x6e8      | 29        | 1.15%   |
| 0x706e5    | 28        | 1.11%   |
| 0x706a8    | 28        | 1.11%   |
| 0x6d8      | 28        | 1.11%   |
| 0x906e9    | 27        | 1.07%   |
| 0x106c2    | 24        | 0.95%   |
| 0x08108109 | 24        | 0.95%   |
| 0x08108102 | 23        | 0.91%   |
| 0x05000119 | 23        | 0.91%   |
| 0x07030105 | 22        | 0.87%   |
| 0x0700010f | 22        | 0.87%   |
| 0x06001119 | 21        | 0.83%   |
| 0x6fb      | 20        | 0.79%   |
| 0x6f6      | 20        | 0.79%   |
| 0x10661    | 17        | 0.67%   |
| 0xa0652    | 16        | 0.63%   |
| 0x706a1    | 16        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 259       | 10.4%   |
| SandyBridge      | 236       | 9.48%   |
| Haswell          | 201       | 8.07%   |
| Penryn           | 193       | 7.75%   |
| IvyBridge        | 189       | 7.59%   |
| Silvermont       | 179       | 7.19%   |
| Core             | 163       | 6.55%   |
| Westmere         | 136       | 5.46%   |
| Skylake          | 93        | 3.73%   |
| P6               | 79        | 3.17%   |
| Broadwell        | 76        | 3.05%   |
| Bonnell          | 67        | 2.69%   |
| Excavator        | 56        | 2.25%   |
| TigerLake        | 52        | 2.09%   |
| Zen+             | 50        | 2.01%   |
| Goldmont plus    | 45        | 1.81%   |
| K8 Hammer        | 42        | 1.69%   |
| IceLake          | 39        | 1.57%   |
| Bobcat           | 35        | 1.41%   |
| Goldmont         | 34        | 1.37%   |
| Puma             | 33        | 1.33%   |
| Zen 2            | 29        | 1.16%   |
| Jaguar           | 28        | 1.12%   |
| Piledriver       | 24        | 0.96%   |
| CometLake        | 21        | 0.84%   |
| Unknown          | 21        | 0.84%   |
| Zen 3            | 20        | 0.8%    |
| K10              | 18        | 0.72%   |
| K10 Llano        | 17        | 0.68%   |
| K8 & K10 hybrid  | 15        | 0.6%    |
| Zen              | 13        | 0.52%   |
| Nehalem          | 10        | 0.4%    |
| Steamroller      | 5         | 0.2%    |
| Tremont          | 4         | 0.16%   |
| NetBurst         | 4         | 0.16%   |
| Alderlake Hybrid | 4         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1808      | 61.75%  |
| AMD                              | 571       | 19.5%   |
| Nvidia                           | 514       | 17.55%  |
| Silicon Integrated Systems [SiS] | 25        | 0.85%   |
| VIA Technologies                 | 10        | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 211       | 6.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 178       | 5.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 119       | 3.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 118       | 3.79%   |
| Intel Core Processor Integrated Graphics Controller                                      | 102       | 3.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 90        | 2.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 89        | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 2.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 2.31%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 72        | 2.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 71        | 2.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 70        | 2.25%   |
| Intel HD Graphics 620                                                                    | 70        | 2.25%   |
| Intel HD Graphics 5500                                                                   | 57        | 1.83%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 48        | 1.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 45        | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 1.28%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 40        | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 1.25%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 1.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 1%      |
| AMD Renoir                                                                               | 29        | 0.93%   |
| Intel HD Graphics 500                                                                    | 28        | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 26        | 0.83%   |
| Intel HD Graphics 630                                                                    | 25        | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 25        | 0.8%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 24        | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 23        | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 22        | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 21        | 0.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 21        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 19        | 0.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.55%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 16        | 0.51%   |
| AMD Lucienne                                                                             | 16        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1394      | 55.89%  |
| 1 x AMD        | 403       | 16.16%  |
| Intel + Nvidia | 306       | 12.27%  |
| 1 x Nvidia     | 178       | 7.14%   |
| Intel + AMD    | 104       | 4.17%   |
| 2 x AMD        | 38        | 1.52%   |
| AMD + Nvidia   | 27        | 1.08%   |
| 1 x SiS        | 25        | 1%      |
| 1 x VIA        | 10        | 0.4%    |
| Other          | 5         | 0.2%    |
| 2 x Nvidia     | 4         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2164      | 86.53%  |
| Proprietary | 252       | 10.08%  |
| Unknown     | 85        | 3.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1615      | 63.99%  |
| 0.01-0.5   | 406       | 16.09%  |
| 1.01-2.0   | 224       | 8.87%   |
| 0.51-1.0   | 159       | 6.3%    |
| 3.01-4.0   | 75        | 2.97%   |
| 5.01-6.0   | 18        | 0.71%   |
| 7.01-8.0   | 15        | 0.59%   |
| 2.01-3.0   | 11        | 0.44%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 494       | 19.54%  |
| LG Display              | 368       | 14.56%  |
| Samsung Electronics     | 357       | 14.12%  |
| Chimei Innolux          | 323       | 12.78%  |
| BOE                     | 273       | 10.8%   |
| Chi Mei Optoelectronics | 107       | 4.23%   |
| LG Philips              | 67        | 2.65%   |
| Apple                   | 59        | 2.33%   |
| Lenovo                  | 43        | 1.7%    |
| Dell                    | 40        | 1.58%   |
| Goldstar                | 37        | 1.46%   |
| Sharp                   | 36        | 1.42%   |
| InfoVision              | 27        | 1.07%   |
| PANDA                   | 25        | 0.99%   |
| CPT                     | 18        | 0.71%   |
| Toshiba                 | 17        | 0.67%   |
| Hewlett-Packard         | 17        | 0.67%   |
| HannStar                | 17        | 0.67%   |
| Sony                    | 13        | 0.51%   |
| Acer                    | 12        | 0.47%   |
| Quanta Display          | 11        | 0.44%   |
| LGD                     | 10        | 0.4%    |
| Philips                 | 9         | 0.36%   |
| InnoLux Display         | 9         | 0.36%   |
| AOC                     | 9         | 0.36%   |
| Vizio                   | 8         | 0.32%   |
| Seiko/Epson             | 8         | 0.32%   |
| BenQ                    | 8         | 0.32%   |
| Panasonic               | 7         | 0.28%   |
| Eizo                    | 6         | 0.24%   |
| Iiyama                  | 5         | 0.2%    |
| Ancor Communications    | 5         | 0.2%    |
| Unknown                 | 4         | 0.16%   |
| KDC                     | 4         | 0.16%   |
| IBM                     | 4         | 0.16%   |
| ASUSTek Computer        | 4         | 0.16%   |
| ViewSonic               | 3         | 0.12%   |
| SAC                     | 3         | 0.12%   |
| Nvidia                  | 3         | 0.12%   |
| BOE Technology Group    | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 31        | 1.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 20        | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.71%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.67%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.51%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.47%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.47%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 11        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.43%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.43%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 11        | 0.43%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 10        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.39%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 10        | 0.39%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 10        | 0.39%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 9         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.35%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 8         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.31%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 8         | 0.31%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 8         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.31%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 8         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch    | 7         | 0.27%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 7         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 220x120mm 9.9-inch  | 7         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 7         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1055      | 42.73%  |
| 1920x1080 (FHD)    | 652       | 26.41%  |
| 1280x800 (WXGA)    | 205       | 8.3%    |
| 1600x900 (HD+)     | 167       | 6.76%   |
| 1440x900 (WXGA+)   | 71        | 2.88%   |
| 3840x2160 (4K)     | 50        | 2.03%   |
| 1024x600           | 46        | 1.86%   |
| 1680x1050 (WSXGA+) | 30        | 1.22%   |
| 1920x1200 (WUXGA)  | 28        | 1.13%   |
| 2560x1600          | 19        | 0.77%   |
| 2560x1440 (QHD)    | 19        | 0.77%   |
| 1360x768           | 14        | 0.57%   |
| 1280x1024 (SXGA)   | 14        | 0.57%   |
| 1024x768 (XGA)     | 10        | 0.41%   |
| Unknown            | 9         | 0.36%   |
| 2160x1440          | 7         | 0.28%   |
| 1280x768           | 7         | 0.28%   |
| 3200x1800 (QHD+)   | 6         | 0.24%   |
| 2560x1080          | 6         | 0.24%   |
| 2256x1504          | 6         | 0.24%   |
| 2880x1800          | 5         | 0.2%    |
| 3840x2400          | 4         | 0.16%   |
| 1920x540           | 4         | 0.16%   |
| 1680x945           | 4         | 0.16%   |
| 3840x1080          | 3         | 0.12%   |
| 3440x1440          | 3         | 0.12%   |
| 1400x1050          | 3         | 0.12%   |
| 1024x576           | 3         | 0.12%   |
| 5760x1080          | 2         | 0.08%   |
| 3600x1080          | 2         | 0.08%   |
| 2288x1287          | 2         | 0.08%   |
| 1920x515           | 2         | 0.08%   |
| 5760x2160          | 1         | 0.04%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1136      | 44.99%  |
| 13      | 314       | 12.44%  |
| 14      | 277       | 10.97%  |
| 17      | 224       | 8.87%   |
| 11      | 91        | 3.6%    |
| 12      | 67        | 2.65%   |
| Unknown | 62        | 2.46%   |
| 10      | 56        | 2.22%   |
| 24      | 40        | 1.58%   |
| 27      | 38        | 1.5%    |
| 23      | 30        | 1.19%   |
| 21      | 27        | 1.07%   |
| 18      | 25        | 0.99%   |
| 16      | 15        | 0.59%   |
| 31      | 14        | 0.55%   |
| 34      | 12        | 0.48%   |
| 20      | 12        | 0.48%   |
| 22      | 11        | 0.44%   |
| 19      | 11        | 0.44%   |
| 72      | 8         | 0.32%   |
| 40      | 8         | 0.32%   |
| 84      | 5         | 0.2%    |
| 54      | 5         | 0.2%    |
| 32      | 4         | 0.16%   |
| 8       | 4         | 0.16%   |
| 74      | 3         | 0.12%   |
| 49      | 3         | 0.12%   |
| 25      | 3         | 0.12%   |
| 58      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 37      | 2         | 0.08%   |
| 29      | 2         | 0.08%   |
| 26      | 2         | 0.08%   |
| 65      | 1         | 0.04%   |
| 64      | 1         | 0.04%   |
| 59      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 44      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1554      | 61.81%  |
| 201-300     | 353       | 14.04%  |
| 351-400     | 268       | 10.66%  |
| 501-600     | 103       | 4.1%    |
| 401-500     | 85        | 3.38%   |
| Unknown     | 62        | 2.47%   |
| 601-700     | 21        | 0.84%   |
| 1001-1500   | 18        | 0.72%   |
| 701-800     | 17        | 0.68%   |
| 1501-2000   | 16        | 0.64%   |
| 801-900     | 10        | 0.4%    |
| 101-200     | 4         | 0.16%   |
| 901-1000    | 3         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1881      | 80.35%  |
| 16/10   | 349       | 14.91%  |
| Unknown | 48        | 2.05%   |
| 4/3     | 18        | 0.77%   |
| 3/2     | 17        | 0.73%   |
| 5/4     | 12        | 0.51%   |
| 21/9    | 11        | 0.47%   |
| 32/9    | 2         | 0.09%   |
| 3.73    | 2         | 0.09%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1137      | 45.12%  |
| 81-90          | 487       | 19.33%  |
| 121-130        | 161       | 6.39%   |
| 71-80          | 96        | 3.81%   |
| 51-60          | 91        | 3.61%   |
| 201-250        | 88        | 3.49%   |
| 61-70          | 66        | 2.62%   |
| Unknown        | 62        | 2.46%   |
| 41-50          | 56        | 2.22%   |
| 131-140        | 53        | 2.1%    |
| 301-350        | 39        | 1.55%   |
| 151-200        | 35        | 1.39%   |
| 141-150        | 33        | 1.31%   |
| 351-500        | 32        | 1.27%   |
| More than 1000 | 31        | 1.23%   |
| 501-1000       | 17        | 0.67%   |
| 251-300        | 12        | 0.48%   |
| 91-100         | 11        | 0.44%   |
| 111-120        | 9         | 0.36%   |
| 1-40           | 4         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1115      | 45.03%  |
| 121-160       | 697       | 28.15%  |
| 51-100        | 442       | 17.85%  |
| 161-240       | 93        | 3.76%   |
| Unknown       | 62        | 2.5%    |
| 1-50          | 34        | 1.37%   |
| More than 240 | 33        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2159      | 85.34%  |
| 2     | 260       | 10.28%  |
| 0     | 90        | 3.56%   |
| 3     | 19        | 0.75%   |
| 5     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1271      | 31.14%  |
| Intel                             | 1015      | 24.87%  |
| Qualcomm Atheros                  | 715       | 17.52%  |
| Broadcom                          | 411       | 10.07%  |
| Broadcom Limited                  | 133       | 3.26%   |
| Marvell Technology Group          | 78        | 1.91%   |
| Ralink                            | 51        | 1.25%   |
| Nvidia                            | 37        | 0.91%   |
| TP-Link                           | 29        | 0.71%   |
| Silicon Integrated Systems [SiS]  | 26        | 0.64%   |
| Ralink Technology                 | 24        | 0.59%   |
| ASIX Electronics                  | 22        | 0.54%   |
| Samsung Electronics               | 21        | 0.51%   |
| JMicron Technology                | 21        | 0.51%   |
| MediaTek                          | 18        | 0.44%   |
| Dell                              | 18        | 0.44%   |
| Xiaomi                            | 15        | 0.37%   |
| Hewlett-Packard                   | 13        | 0.32%   |
| Sierra Wireless                   | 12        | 0.29%   |
| DisplayLink                       | 11        | 0.27%   |
| Huawei Technologies               | 10        | 0.25%   |
| VIA Technologies                  | 9         | 0.22%   |
| Qualcomm Atheros Communications   | 9         | 0.22%   |
| Ericsson Business Mobile Networks | 9         | 0.22%   |
| Edimax Technology                 | 8         | 0.2%    |
| ASUSTek Computer                  | 8         | 0.2%    |
| AMD                               | 8         | 0.2%    |
| OPPO Electronics                  | 7         | 0.17%   |
| NetGear                           | 7         | 0.17%   |
| Attansic Technology               | 6         | 0.15%   |
| Qualcomm                          | 5         | 0.12%   |
| Motorola PCS                      | 5         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.1%    |
| D-Link System                     | 4         | 0.1%    |
| T & A Mobile Phones               | 3         | 0.07%   |
| Linksys                           | 3         | 0.07%   |
| D-Link                            | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyDAS                             | 2         | 0.05%   |
| Micro Star International          | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 627       | 12.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 368       | 7.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 134       | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 120       | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 103       | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 101       | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 93        | 1.92%   |
| Intel Wireless 7260                                                     | 92        | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 63        | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 1.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 57        | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 1.13%   |
| Intel Wireless 8265 / 8275                                              | 52        | 1.07%   |
| Intel Wireless 7265                                                     | 49        | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 47        | 0.97%   |
| Intel Wireless 3165                                                     | 46        | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 45        | 0.93%   |
| Intel WiFi Link 5100                                                    | 43        | 0.89%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 0.87%   |
| Intel Wireless 8260                                                     | 41        | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 36        | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 36        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.7%    |
| Intel Wi-Fi 6 AX201                                                     | 32        | 0.66%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 32        | 0.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 32        | 0.66%   |
| Intel Ethernet Connection I217-LM                                       | 31        | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 30        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                          | 30        | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 29        | 0.6%    |
| Intel Wireless 3160                                                     | 29        | 0.6%    |
| Intel Ethernet Connection I218-LM                                       | 29        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                | 28        | 0.58%   |
| Intel 82567LM Gigabit Network Connection                                | 28        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 27        | 0.56%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 939       | 36.27%  |
| Qualcomm Atheros                | 606       | 23.41%  |
| Realtek Semiconductor           | 441       | 17.03%  |
| Broadcom                        | 316       | 12.21%  |
| Broadcom Limited                | 92        | 3.55%   |
| Ralink                          | 51        | 1.97%   |
| Ralink Technology               | 24        | 0.93%   |
| TP-Link                         | 23        | 0.89%   |
| MediaTek                        | 15        | 0.58%   |
| Sierra Wireless                 | 12        | 0.46%   |
| Qualcomm Atheros Communications | 9         | 0.35%   |
| Dell                            | 9         | 0.35%   |
| Edimax Technology               | 8         | 0.31%   |
| NetGear                         | 7         | 0.27%   |
| ASUSTek Computer                | 7         | 0.27%   |
| D-Link System                   | 4         | 0.15%   |
| Linksys                         | 3         | 0.12%   |
| Hewlett-Packard                 | 3         | 0.12%   |
| D-Link                          | 3         | 0.12%   |
| Belkin Components               | 3         | 0.12%   |
| ZyDAS                           | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| ZyXEL Communications            | 1         | 0.04%   |
| Xiaomi                          | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Lite-On Technology              | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| Fibocom                         | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 134       | 5.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 120       | 4.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 103       | 3.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 93        | 3.56%   |
| Intel Wireless 7260                                                     | 92        | 3.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 2.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 2.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 63        | 2.41%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 2.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 57        | 2.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 2.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 2.1%    |
| Intel Wireless 8265 / 8275                                              | 52        | 1.99%   |
| Intel Wireless 7265                                                     | 49        | 1.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 47        | 1.8%    |
| Intel Wireless 3165                                                     | 46        | 1.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 45        | 1.72%   |
| Intel WiFi Link 5100                                                    | 43        | 1.64%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 1.61%   |
| Intel Wireless 8260                                                     | 41        | 1.57%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 1.3%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 1.3%    |
| Intel Wi-Fi 6 AX201                                                     | 32        | 1.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 32        | 1.22%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 32        | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 30        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 30        | 1.15%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 29        | 1.11%   |
| Intel Wireless 3160                                                     | 29        | 1.11%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 0.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 24        | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 24        | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 23        | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 22        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 21        | 0.8%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 21        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 21        | 0.8%    |
| Intel Centrino Advanced-N 6200                                          | 21        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1085      | 50.49%  |
| Intel                                  | 393       | 18.29%  |
| Qualcomm Atheros                       | 188       | 8.75%   |
| Broadcom                               | 144       | 6.7%    |
| Marvell Technology Group               | 78        | 3.63%   |
| Broadcom Limited                       | 46        | 2.14%   |
| Nvidia                                 | 37        | 1.72%   |
| Silicon Integrated Systems [SiS]       | 24        | 1.12%   |
| ASIX Electronics                       | 22        | 1.02%   |
| Samsung Electronics                    | 21        | 0.98%   |
| JMicron Technology                     | 21        | 0.98%   |
| Xiaomi                                 | 14        | 0.65%   |
| DisplayLink                            | 11        | 0.51%   |
| VIA Technologies                       | 9         | 0.42%   |
| OPPO Electronics                       | 7         | 0.33%   |
| Huawei Technologies                    | 7         | 0.33%   |
| TP-Link                                | 6         | 0.28%   |
| Attansic Technology                    | 6         | 0.28%   |
| Motorola PCS                           | 5         | 0.23%   |
| Qualcomm                               | 4         | 0.19%   |
| MediaTek                               | 3         | 0.14%   |
| Hewlett-Packard                        | 3         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Davicom Semiconductor                  | 2         | 0.09%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Novatel Wireless                       | 1         | 0.05%   |
| Motorola BCS                           | 1         | 0.05%   |
| Lenovo                                 | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| HMD Global                             | 1         | 0.05%   |
| GoPro                                  | 1         | 0.05%   |
| ASUSTek Computer                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 627       | 29.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 368       | 17.06%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101       | 4.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 36        | 1.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 36        | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 1.34%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 28        | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 27        | 1.25%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 1.11%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 1.07%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 22        | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.02%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.97%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.97%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 17        | 0.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 16        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.74%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 15        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14        | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.6%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 13        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 13        | 0.6%    |
| Nvidia MCP79 Ethernet                                             | 12        | 0.56%   |
| Nvidia MCP67 Ethernet                                             | 12        | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.56%   |
| Intel PRO/100 VE Network Connection                               | 12        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.51%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 11        | 0.51%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 11        | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2409      | 52.77%  |
| Ethernet | 2076      | 45.48%  |
| Modem    | 75        | 1.64%   |
| Unknown  | 5         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2015      | 77.86%  |
| Ethernet | 572       | 22.1%   |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1924      | 77.21%  |
| 1     | 458       | 18.38%  |
| 0     | 100       | 4.01%   |
| 3     | 10        | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1991      | 78.98%  |
| Yes  | 530       | 21.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 560       | 34.7%   |
| Qualcomm Atheros Communications | 212       | 13.14%  |
| Realtek Semiconductor           | 186       | 11.52%  |
| Broadcom                        | 132       | 8.18%   |
| IMC Networks                    | 76        | 4.71%   |
| Lite-On Technology              | 64        | 3.97%   |
| Dell                            | 60        | 3.72%   |
| Foxconn / Hon Hai               | 55        | 3.41%   |
| Hewlett-Packard                 | 54        | 3.35%   |
| Apple                           | 53        | 3.28%   |
| Toshiba                         | 35        | 2.17%   |
| Cambridge Silicon Radio         | 28        | 1.73%   |
| Ralink                          | 21        | 1.3%    |
| ASUSTek Computer                | 15        | 0.93%   |
| Alps Electric                   | 13        | 0.81%   |
| Realtek                         | 11        | 0.68%   |
| Foxconn International           | 10        | 0.62%   |
| Askey Computer                  | 6         | 0.37%   |
| Taiyo Yuden                     | 4         | 0.25%   |
| Ralink Technology               | 4         | 0.25%   |
| Dynex                           | 3         | 0.19%   |
| Chicony Electronics             | 3         | 0.19%   |
| Qcom                            | 2         | 0.12%   |
| MediaTek                        | 2         | 0.12%   |
| Integrated System Solution      | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 295       | 18.25%  |
| Realtek Bluetooth Radio                             | 115       | 7.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 93        | 5.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 69        | 4.27%   |
| Intel Bluetooth Device                              | 65        | 4.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 55        | 3.4%    |
| Intel AX200 Bluetooth                               | 42        | 2.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 2.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 2.17%   |
| Lite-On Bluetooth Device                            | 32        | 1.98%   |
| Apple Bluetooth Host Controller                     | 31        | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 1.86%   |
| IMC Networks Bluetooth Device                       | 30        | 1.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 30        | 1.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 1.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.55%   |
| Ralink RT3290 Bluetooth                             | 21        | 1.3%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 21        | 1.3%    |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 1.18%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 19        | 1.18%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.11%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.05%   |
| Dell DW375 Bluetooth Module                         | 17        | 1.05%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 17        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.87%   |
| Intel AX210 Bluetooth                               | 13        | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.74%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.74%   |
| Toshiba Bluetooth Device                            | 11        | 0.68%   |
| Realtek Bluetooth Radio                             | 11        | 0.68%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 10        | 0.62%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.62%   |
| IMC Networks Wireless_Device                        | 9         | 0.56%   |
| Dell Wireless 370 Bluetooth Mini-card               | 9         | 0.56%   |
| Broadcom BCM20702A0                                 | 9         | 0.56%   |
| Apple Bluetooth HCI                                 | 9         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1957      | 69.94%  |
| AMD                                  | 450       | 16.08%  |
| Nvidia                               | 282       | 10.08%  |
| Silicon Integrated Systems [SiS]     | 28        | 1%      |
| VIA Technologies                     | 10        | 0.36%   |
| C-Media Electronics                  | 9         | 0.32%   |
| Tenx Technology                      | 6         | 0.21%   |
| Generalplus Technology               | 5         | 0.18%   |
| Realtek Semiconductor                | 4         | 0.14%   |
| Logitech                             | 4         | 0.14%   |
| Creative Technology                  | 4         | 0.14%   |
| Texas Instruments                    | 3         | 0.11%   |
| SteelSeries ApS                      | 3         | 0.11%   |
| JMTek                                | 3         | 0.11%   |
| GN Netcom                            | 3         | 0.11%   |
| Yamaha                               | 2         | 0.07%   |
| Lenovo                               | 2         | 0.07%   |
| KTMicro                              | 2         | 0.07%   |
| Focusrite-Novation                   | 2         | 0.07%   |
| ZOOM                                 | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Syntek                               | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| SAVITECH                             | 1         | 0.04%   |
| Roland                               | 1         | 0.04%   |
| Razer USA                            | 1         | 0.04%   |
| PreSonus Audio Electronics           | 1         | 0.04%   |
| Plantronics                          | 1         | 0.04%   |
| OPPO Electronics                     | 1         | 0.04%   |
| Hewlett-Packard                      | 1         | 0.04%   |
| DSEA A/S                             | 1         | 0.04%   |
| Dell                                 | 1         | 0.04%   |
| Corsair                              | 1         | 0.04%   |
| Conexant Systems                     | 1         | 0.04%   |
| CMX Systems                          | 1         | 0.04%   |
| ASUSTek Computer                     | 1         | 0.04%   |
| AKAI Professional M.I.               | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 232       | 6.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 211       | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 192       | 5.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 166       | 4.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 146       | 4.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 134       | 3.95%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 128       | 3.78%   |
| Intel 8 Series HD Audio Controller                                                                | 120       | 3.54%   |
| AMD FCH Azalia Controller                                                                         | 117       | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 116       | 3.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 115       | 3.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 81        | 2.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 76        | 2.24%   |
| Intel Broadwell-U Audio Controller                                                                | 76        | 2.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 72        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 69        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 63        | 1.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 61        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 56        | 1.65%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 55        | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 54        | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 52        | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 45        | 1.33%   |
| AMD High Definition Audio Controller                                                              | 45        | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 44        | 1.3%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 42        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 39        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 34        | 1%      |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 34        | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 29        | 0.86%   |
| AMD Wrestler HDMI Audio                                                                           | 29        | 0.86%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 24        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 24        | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 24        | 0.71%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 22        | 0.65%   |
| Nvidia High Definition Audio Controller                                                           | 21        | 0.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 18        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 148       | 25.43%  |
| SK hynix               | 139       | 23.88%  |
| Micron Technology      | 64        | 11%     |
| Unknown                | 57        | 9.79%   |
| Kingston               | 43        | 7.39%   |
| Unknown (ABCD)         | 18        | 3.09%   |
| Nanya Technology       | 15        | 2.58%   |
| Crucial                | 14        | 2.41%   |
| A-DATA Technology      | 13        | 2.23%   |
| Ramaxel Technology     | 11        | 1.89%   |
| Elpida                 | 11        | 1.89%   |
| Smart                  | 5         | 0.86%   |
| Qimonda                | 4         | 0.69%   |
| Transcend              | 2         | 0.34%   |
| Timetec                | 2         | 0.34%   |
| Teikon                 | 2         | 0.34%   |
| Team                   | 2         | 0.34%   |
| SHARETRONIC            | 2         | 0.34%   |
| Patriot                | 2         | 0.34%   |
| High Bridge            | 2         | 0.34%   |
| ff                     | 2         | 0.34%   |
| Corsair                | 2         | 0.34%   |
| 4ea5                   | 2         | 0.34%   |
| Walton Chaintech       | 1         | 0.17%   |
| Unknown (08B5)         | 1         | 0.17%   |
| Unknown (000080B30080) | 1         | 0.17%   |
| Toshiba                | 1         | 0.17%   |
| Strontium              | 1         | 0.17%   |
| Smart Brazil           | 1         | 0.17%   |
| PUSKILL                | 1         | 0.17%   |
| Netlist                | 1         | 0.17%   |
| Nayna                  | 1         | 0.17%   |
| Kllisre                | 1         | 0.17%   |
| Kingmax                | 1         | 0.17%   |
| HBS                    | 1         | 0.17%   |
| GSkill                 | 1         | 0.17%   |
| G.Skill                | 1         | 0.17%   |
| Essencore              | 1         | 0.17%   |
| CSX                    | 1         | 0.17%   |
| COS Memory             | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 16        | 2.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.45%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 8         | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.13%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 6         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.96%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.96%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.96%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.8%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.8%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.64%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.64%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.64%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.64%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 0.48%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.48%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 3         | 0.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.48%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 197       | 40.45%  |
| DDR4    | 151       | 31.01%  |
| DDR2    | 59        | 12.11%  |
| LPDDR4  | 31        | 6.37%   |
| SDRAM   | 19        | 3.9%    |
| LPDDR3  | 14        | 2.87%   |
| DRAM    | 6         | 1.23%   |
| DDR     | 5         | 1.03%   |
| Unknown | 4         | 0.82%   |
| LPDDR5  | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 427       | 88.59%  |
| Row Of Chips | 38        | 7.88%   |
| DIMM         | 10        | 2.07%   |
| Chip         | 4         | 0.83%   |
| Unknown      | 3         | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 182       | 33.03%  |
| 8192  | 163       | 29.58%  |
| 2048  | 118       | 21.42%  |
| 1024  | 42        | 7.62%   |
| 16384 | 29        | 5.26%   |
| 512   | 11        | 2%      |
| 32768 | 4         | 0.73%   |
| 256   | 2         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 134       | 25.09%  |
| 2667    | 75        | 14.04%  |
| 3200    | 51        | 9.55%   |
| 2400    | 43        | 8.05%   |
| 1334    | 35        | 6.55%   |
| 667     | 34        | 6.37%   |
| Unknown | 24        | 4.49%   |
| 1333    | 23        | 4.31%   |
| 2133    | 21        | 3.93%   |
| 1066    | 14        | 2.62%   |
| 800     | 10        | 1.87%   |
| 533     | 10        | 1.87%   |
| 4199    | 9         | 1.69%   |
| 975     | 9         | 1.69%   |
| 4267    | 8         | 1.5%    |
| 3266    | 8         | 1.5%    |
| 2048    | 6         | 1.12%   |
| 1067    | 5         | 0.94%   |
| 8400    | 3         | 0.56%   |
| 1867    | 3         | 0.56%   |
| 400     | 3         | 0.56%   |
| 6400    | 1         | 0.19%   |
| 4800    | 1         | 0.19%   |
| 4266    | 1         | 0.19%   |
| 3733    | 1         | 0.19%   |
| 2933    | 1         | 0.19%   |
| 1639    | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 42.31%  |
| Canon                 | 5         | 19.23%  |
| Seiko Epson           | 3         | 11.54%  |
| Samsung Electronics   | 2         | 7.69%   |
| Brother Industries    | 2         | 7.69%   |
| Zebra                 | 1         | 3.85%   |
| STMicroelectronics    | 1         | 3.85%   |
| Lexmark International | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 7.69%   |
| HP DeskJet 1110 series                                    | 2         | 7.69%   |
| Zebra ZP 450 Printer                                      | 1         | 3.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.85%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.85%   |
| Seiko Epson Printer                                       | 1         | 3.85%   |
| Seiko Epson L3110 Series                                  | 1         | 3.85%   |
| Samsung M2020 Series                                      | 1         | 3.85%   |
| Samsung CLX-3300 Series                                   | 1         | 3.85%   |
| Lexmark International 2400 series                         | 1         | 3.85%   |
| HP Laserjet P1505                                         | 1         | 3.85%   |
| HP LaserJet 1200                                          | 1         | 3.85%   |
| HP LaserJet 1020                                          | 1         | 3.85%   |
| HP LaserJet 1000                                          | 1         | 3.85%   |
| HP DeskJet 2700 series                                    | 1         | 3.85%   |
| HP DeskJet 2300 series                                    | 1         | 3.85%   |
| HP Deskjet 1510                                           | 1         | 3.85%   |
| Canon TS3100 series                                       | 1         | 3.85%   |
| Canon PIXMA MX340                                         | 1         | 3.85%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.85%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.85%   |
| Canon MG2100 series                                       | 1         | 3.85%   |
| Brother MFC-L2730DW series                                | 1         | 3.85%   |
| Brother DCP-T300                                          | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 40%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 200                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 514       | 25.66%  |
| Microdia                               | 192       | 9.59%   |
| Realtek Semiconductor                  | 164       | 8.19%   |
| IMC Networks                           | 160       | 7.99%   |
| Acer                                   | 136       | 6.79%   |
| Sunplus Innovation Technology          | 112       | 5.59%   |
| Suyin                                  | 110       | 5.49%   |
| Cheng Uei Precision Industry (Foxlink) | 93        | 4.64%   |
| Quanta                                 | 78        | 3.89%   |
| Apple                                  | 52        | 2.6%    |
| Syntek                                 | 50        | 2.5%    |
| Silicon Motion                         | 47        | 2.35%   |
| Lite-On Technology                     | 37        | 1.85%   |
| Alcor Micro                            | 35        | 1.75%   |
| Ricoh                                  | 32        | 1.6%    |
| Luxvisions Innotech Limited            | 17        | 0.85%   |
| Importek                               | 17        | 0.85%   |
| ALi                                    | 16        | 0.8%    |
| Primax Electronics                     | 14        | 0.7%    |
| Samsung Electronics                    | 13        | 0.65%   |
| icSpring                               | 11        | 0.55%   |
| Z-Star Microelectronics                | 10        | 0.5%    |
| OmniVision Technologies                | 9         | 0.45%   |
| GEMBIRD                                | 9         | 0.45%   |
| Logitech                               | 8         | 0.4%    |
| Lenovo                                 | 8         | 0.4%    |
| Sonix Technology                       | 6         | 0.3%    |
| SunplusIT                              | 5         | 0.25%   |
| Genesys Logic                          | 5         | 0.25%   |
| Sunplus Technology                     | 4         | 0.2%    |
| Generalplus Technology                 | 3         | 0.15%   |
| ARC International                      | 3         | 0.15%   |
| Microsoft                              | 2         | 0.1%    |
| LG Electronics                         | 2         | 0.1%    |
| Intel                                  | 2         | 0.1%    |
| Huawei Technologies                    | 2         | 0.1%    |
| Camera                                 | 2         | 0.1%    |
| YGTek                                  | 1         | 0.05%   |
| Y Media                                | 1         | 0.05%   |
| Xiaomi                                 | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 60        | 2.99%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 38        | 1.89%   |
| Acer Lenovo EasyCamera                                  | 38        | 1.89%   |
| Microdia Integrated_Webcam_HD                           | 35        | 1.74%   |
| Microdia Integrated Webcam                              | 35        | 1.74%   |
| Realtek Integrated_Webcam_HD                            | 31        | 1.54%   |
| Chicony HP Truevision HD                                | 31        | 1.54%   |
| Chicony HD WebCam                                       | 28        | 1.4%    |
| Realtek USB Camera                                      | 24        | 1.2%    |
| Acer Integrated Camera                                  | 24        | 1.2%    |
| Chicony USB 2.0 Camera                                  | 23        | 1.15%   |
| Syntek Integrated Camera                                | 22        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 22        | 1.1%    |
| Chicony HP Truevision HD camera                         | 22        | 1.1%    |
| Sunplus Integrated_Webcam_HD                            | 19        | 0.95%   |
| Chicony Lenovo EasyCamera                               | 18        | 0.9%    |
| Chicony HP HD Webcam                                    | 18        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.9%    |
| Sunplus HD WebCam                                       | 17        | 0.85%   |
| IMC Networks Integrated Camera                          | 17        | 0.85%   |
| Chicony EasyCamera                                      | 17        | 0.85%   |
| Apple iPhone 5/5C/5S/6/SE                               | 17        | 0.85%   |
| Suyin HP Truevision HD                                  | 16        | 0.8%    |
| Realtek Integrated Webcam                               | 16        | 0.8%    |
| Chicony VGA WebCam                                      | 16        | 0.8%    |
| Chicony TOSHIBA Web Camera - HD                         | 16        | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                           | 15        | 0.75%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 14        | 0.7%    |
| Quanta HP Webcam                                        | 14        | 0.7%    |
| Microdia Sonix USB 2.0 Camera                           | 14        | 0.7%    |
| Chicony HP Webcam                                       | 14        | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.7%    |
| Apple FaceTime HD Camera                                | 14        | 0.7%    |
| ALi Gateway Webcam                                      | 14        | 0.7%    |
| Samsung Galaxy A5 (MTP)                                 | 13        | 0.65%   |
| Quanta HP TrueVision HD Camera                          | 13        | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 13        | 0.65%   |
| Chicony USB2.0 HD UVC WebCam                            | 13        | 0.65%   |
| Alcor Micro USB Camera                                  | 13        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 163       | 47.8%   |
| AuthenTec                  | 55        | 16.13%  |
| Upek                       | 31        | 9.09%   |
| Shenzhen Goodix Technology | 29        | 8.5%    |
| Synaptics                  | 21        | 6.16%   |
| STMicroelectronics         | 18        | 5.28%   |
| Elan Microelectronics      | 15        | 4.4%    |
| LighTuning Technology      | 7         | 2.05%   |
| Samsung Electronics        | 1         | 0.29%   |
| Focal-systems.Corp         | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 10.85%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 8.8%    |
| Shenzhen Goodix  FingerPrint Device                                        | 21        | 6.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 5.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 5.28%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 5.28%   |
| AuthenTec AES2810                                                          | 17        | 4.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 16        | 4.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 16        | 4.69%   |
| Validity Sensors VFS491                                                    | 15        | 4.4%    |
| Validity Sensors Fingerprint scanner                                       | 15        | 4.4%    |
| AuthenTec AES1600                                                          | 9         | 2.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.35%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.35%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.76%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.76%   |
| Unknown                                                                    | 6         | 1.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.47%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.47%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.47%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.17%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 1.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.17%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.17%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.59%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.59%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.59%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.29%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.29%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.29%   |
| Synaptics  WBDI                                                            | 1         | 0.29%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 76        | 52.05%  |
| O2 Micro                          | 23        | 15.75%  |
| Alcor Micro                       | 23        | 15.75%  |
| Lenovo                            | 9         | 6.16%   |
| Upek                              | 7         | 4.79%   |
| Yubico.com                        | 2         | 1.37%   |
| SCM Microsystems                  | 2         | 1.37%   |
| Realtek Semiconductor             | 2         | 1.37%   |
| VASCO Data Security International | 1         | 0.68%   |
| OmniKey                           | 1         | 0.68%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 25.34%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 15.07%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 14.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 12.33%  |
| Broadcom 5880                                                                | 15        | 10.27%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 6.16%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 3.42%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.37%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.37%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.37%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.37%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.68%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.68%   |
| Broadcom 58200                                                               | 1         | 0.68%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.68%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1635      | 64.7%   |
| 1     | 697       | 27.58%  |
| 2     | 177       | 7%      |
| 3     | 15        | 0.59%   |
| 4     | 2         | 0.08%   |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 334       | 31.3%   |
| Graphics card            | 238       | 22.31%  |
| Chipcard                 | 137       | 12.84%  |
| Net/wireless             | 128       | 12%     |
| Multimedia controller    | 64        | 6%      |
| Storage                  | 38        | 3.56%   |
| Modem                    | 34        | 3.19%   |
| Bluetooth                | 28        | 2.62%   |
| Sound                    | 14        | 1.31%   |
| Camera                   | 12        | 1.12%   |
| Flash memory             | 11        | 1.03%   |
| Communication controller | 9         | 0.84%   |
| Net/ethernet             | 6         | 0.56%   |
| Card reader              | 5         | 0.47%   |
| Network                  | 3         | 0.28%   |
| Storage/nvme             | 2         | 0.19%   |
| Unclassified device      | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Storage/ata              | 1         | 0.09%   |
| Dvb card                 | 1         | 0.09%   |

