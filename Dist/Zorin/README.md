Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 6459

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | Notebook    | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [92f6e450b8](https://linux-hardware.org/?probe=92f6e450b8) | Jan 31, 2023 |
| Dell          | Latitude E6540              | Notebook    | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9bb7eb28ed](https://linux-hardware.org/?probe=9bb7eb28ed) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | Notebook    | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| MSI           | H81M-P33                    | Desktop     | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | Desktop     | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [56622f5d6c](https://linux-hardware.org/?probe=56622f5d6c) | Jan 29, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | Notebook    | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| HP            | 843F                        | Desktop     | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cf4086f3e4](https://linux-hardware.org/?probe=cf4086f3e4) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| HP            | 2B47                        | Desktop     | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | Desktop     | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| HP            | Notebook                    | Notebook    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | Notebook    | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| HP            | 625                         | Notebook    | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | Notebook    | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| HP            | 2ADE                        | Desktop     | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Acer          | RS880M05                    | Desktop     | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f72fec3364](https://linux-hardware.org/?probe=f72fec3364) | Jan 23, 2023 |
| Dell          | Latitude E7470              | Notebook    | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| ASRock        | H61M                        | Desktop     | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| Dell          | Precision M6800             | Notebook    | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | Notebook    | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [25013b14a9](https://linux-hardware.org/?probe=25013b14a9) | Jan 22, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1c3214e8c5](https://linux-hardware.org/?probe=1c3214e8c5) | Jan 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [b47caaf20b](https://linux-hardware.org/?probe=b47caaf20b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | Notebook    | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| HP            | 625                         | Notebook    | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | Notebook    | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | Notebook    | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| HP            | 843F                        | Desktop     | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | A6U                         | Notebook    | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | 843F                        | Desktop     | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| HP            | ProBook 4740s               | Notebook    | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | Desktop     | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | Notebook    | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | Notebook    | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| HP            | 3397                        | Desktop     | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d87fb3cf65](https://linux-hardware.org/?probe=d87fb3cf65) | Jan 17, 2023 |
| Fujitsu       | LIFEBOOK T726               | Convertible | [ab8e5c3c70](https://linux-hardware.org/?probe=ab8e5c3c70) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | Notebook    | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | Notebook    | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| HP            | Pavilion 17                 | Notebook    | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | Desktop     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f4232dc72a](https://linux-hardware.org/?probe=f4232dc72a) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | Desktop     | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | Notebook    | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Tactus        | GeoPad 110                  | Tablet      | [810d937888](https://linux-hardware.org/?probe=810d937888) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [e5ab68f182](https://linux-hardware.org/?probe=e5ab68f182) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | Desktop     | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | Notebook    | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| HP            | 18E7                        | Desktop     | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | Notebook    | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845fca1774](https://linux-hardware.org/?probe=845fca1774) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | Notebook    | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | Desktop     | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | Notebook    | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | Desktop     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | Notebook    | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [3d1b3bf218](https://linux-hardware.org/?probe=3d1b3bf218) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| GPU Compan... | GWTC116-2                   | Convertible | [a1c1965381](https://linux-hardware.org/?probe=a1c1965381) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| Wortmann      | TERRA_MOBILE_1062           | Tablet      | [d363c969bc](https://linux-hardware.org/?probe=d363c969bc) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [fd9ae626c7](https://linux-hardware.org/?probe=fd9ae626c7) | Jan 10, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [8c41599fdd](https://linux-hardware.org/?probe=8c41599fdd) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HP            | 843B                        | Desktop     | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d482768ec9](https://linux-hardware.org/?probe=d482768ec9) | Jan 09, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| Dell          | Latitude E6510              | Notebook    | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| HP            | 2129                        | Desktop     | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MSI           | CR62 6M                     | Notebook    | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Sony          | VAIO                        | All in one  | [1f521568e1](https://linux-hardware.org/?probe=1f521568e1) | Jan 07, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| Standard      | X50-V2                      | Desktop     | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | Desktop     | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | Notebook    | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | Notebook    | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | Notebook    | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | Notebook    | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | Desktop     | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f31ae01428](https://linux-hardware.org/?probe=f31ae01428) | Jan 02, 2023 |
| HP            | 8350                        | Desktop     | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | Desktop     | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | Notebook    | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| HP            | 2AF7                        | Desktop     | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [2fe0a7fe8b](https://linux-hardware.org/?probe=2fe0a7fe8b) | Dec 27, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | 2AF7                        | Desktop     | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1c2f8d9457](https://linux-hardware.org/?probe=1c2f8d9457) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [9bcea5d857](https://linux-hardware.org/?probe=9bcea5d857) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| Intel         | H61                         | Desktop     | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| HP            | 2AF7                        | Desktop     | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| HP            | 2AF7                        | Desktop     | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | Desktop     | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | Desktop     | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | Desktop     | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Sony          | VJZ13A                      | Notebook    | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| MSI           | MS-1035                     | Notebook    | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| HP            | 8715                        | Mini pc     | [a6f7705fd4](https://linux-hardware.org/?probe=a6f7705fd4) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d12b0d42fc](https://linux-hardware.org/?probe=d12b0d42fc) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | Notebook    | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | Notebook    | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | Notebook    | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [53ae51748b](https://linux-hardware.org/?probe=53ae51748b) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [396db83818](https://linux-hardware.org/?probe=396db83818) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [1a8c883ac5](https://linux-hardware.org/?probe=1a8c883ac5) | Dec 16, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ced1979abf](https://linux-hardware.org/?probe=ced1979abf) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | Notebook    | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| HP            | 8750                        | Desktop     | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | Notebook    | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | Notebook    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [e32ae95f08](https://linux-hardware.org/?probe=e32ae95f08) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | Desktop     | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [1e8031daad](https://linux-hardware.org/?probe=1e8031daad) | Dec 13, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [c8c56f3e93](https://linux-hardware.org/?probe=c8c56f3e93) | Dec 13, 2022 |
| HP            | 1905                        | Desktop     | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7cae9d407c](https://linux-hardware.org/?probe=7cae9d407c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | Notebook    | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| HP            | 82FE 11                     | Desktop     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | Desktop     | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | Desktop     | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | Desktop     | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| Biostar       | TPower X58                  | Desktop     | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [71b49e89e9](https://linux-hardware.org/?probe=71b49e89e9) | Dec 02, 2022 |
| AZW           | U59                         | Desktop     | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | Desktop     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| HP            | 8433 11                     | Desktop     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [ab421fd2d4](https://linux-hardware.org/?probe=ab421fd2d4) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [4f517e816d](https://linux-hardware.org/?probe=4f517e816d) | Dec 01, 2022 |
| Dell          | Latitude E5520              | Notebook    | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | Notebook    | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Gateway       | SX2851                      | Desktop     | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Dell          | System XPS L502X            | Notebook    | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | Desktop     | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5e51349002](https://linux-hardware.org/?probe=5e51349002) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f70a6fa6ae](https://linux-hardware.org/?probe=f70a6fa6ae) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | Notebook    | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | Desktop     | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [e49d5c5f9d](https://linux-hardware.org/?probe=e49d5c5f9d) | Nov 24, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | Notebook    | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | Desktop     | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | Notebook    | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| HP            | Notebook                    | Notebook    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | Notebook    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | 15                          | Notebook    | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | Desktop     | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [7a2c8b647d](https://linux-hardware.org/?probe=7a2c8b647d) | Nov 22, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | Notebook    | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| HP            | 8184 X4                     | Desktop     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| HP            | 822A                        | Desktop     | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Acer          | Veriton N4640G              | Desktop     | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [87f2179621](https://linux-hardware.org/?probe=87f2179621) | Nov 20, 2022 |
| Framework     | Laptop                      | Notebook    | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | Desktop     | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [c92c0834ef](https://linux-hardware.org/?probe=c92c0834ef) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| MSI           | 2AE0                        | Desktop     | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | Desktop     | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| Gateway       | NV59C                       | Notebook    | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | Notebook    | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| HP            | 0AA4h                       | Desktop     | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | Desktop     | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Microtech     | ebookLite                   | Notebook    | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | Notebook    | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4ce82dba3d](https://linux-hardware.org/?probe=4ce82dba3d) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| HP            | 1850                        | Desktop     | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | Notebook    | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | Desktop     | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | Desktop     | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Microtech     | ebookLite                   | Notebook    | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | Notebook    | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Unknown       | 775i65G                     | Desktop     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Biostar       | TPower X58                  | Desktop     | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | Notebook    | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | Notebook    | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | Notebook    | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fb2770f137](https://linux-hardware.org/?probe=fb2770f137) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | Notebook    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | Notebook    | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | Notebook    | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| ASUSTek       | F5V                         | Notebook    | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Acer          | H81H3-M4                    | Desktop     | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| HP            | 1790                        | Desktop     | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| HP            | 1790                        | Desktop     | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | Notebook    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | Desktop     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | Desktop     | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| HP            | 1790                        | Desktop     | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| HP            | 2000                        | Notebook    | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | Notebook    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | Notebook    | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| MSI           | B560M PRO                   | Desktop     | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| Dell          | Latitude E6530              | Notebook    | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | Notebook    | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| Gateway       | SX2851                      | Desktop     | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| HP            | 829B                        | All in one  | [1f8f75d1c0](https://linux-hardware.org/?probe=1f8f75d1c0) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [54f6493d11](https://linux-hardware.org/?probe=54f6493d11) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | Notebook    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | Notebook    | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| MSI           | GE62 7RE                    | Notebook    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | Notebook    | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | Notebook    | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | Notebook    | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| Dell          | Vostro V13                  | Notebook    | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | Notebook    | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [f31749db41](https://linux-hardware.org/?probe=f31749db41) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [8ae5de2c7d](https://linux-hardware.org/?probe=8ae5de2c7d) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| HP            | G62                         | Notebook    | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | Studio 1458                 | Notebook    | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| HP            | Notebook                    | Notebook    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | Notebook    | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | Desktop     | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Dell          | 0XGMD0 A00                  | All in one  | [e38169d409](https://linux-hardware.org/?probe=e38169d409) | Oct 16, 2022 |
| Intel         | H55                         | Desktop     | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| HP            | 18E7                        | Desktop     | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | Desktop     | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| HP            | 2AF3                        | Desktop     | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e8dd0752ac](https://linux-hardware.org/?probe=e8dd0752ac) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| HP            | 304Ah                       | Desktop     | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Standard      | X50-V2                      | Desktop     | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | Notebook    | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | Notebook    | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | Desktop     | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | Desktop     | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| Dell          | Inspiron 1200               | Notebook    | [45c46e1b91](https://linux-hardware.org/?probe=45c46e1b91) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| HP            | 822A                        | Desktop     | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | Desktop     | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | Desktop     | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | Desktop     | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [5c00e1dddc](https://linux-hardware.org/?probe=5c00e1dddc) | Oct 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [29c7a43356](https://linux-hardware.org/?probe=29c7a43356) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| Dell          | Latitude E6500              | Notebook    | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| HP            | 2B60 MVB                    | Desktop     | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | Notebook    | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | Notebook    | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | Notebook    | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | 3397                        | Desktop     | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | Notebook    | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [1a331f2583](https://linux-hardware.org/?probe=1a331f2583) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | Notebook    | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | 8055                        | Desktop     | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Dell          | Inspiron 1200               | Notebook    | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| HP            | 843C                        | Desktop     | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | Notebook    | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [62d808a3e5](https://linux-hardware.org/?probe=62d808a3e5) | Sep 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3052bded51](https://linux-hardware.org/?probe=3052bded51) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | Desktop     | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Gateway       | FMCP7AM                     | Desktop     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | Notebook    | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 2521      | 58.41%  |
| Zorin 15 | 1599      | 37.05%  |
| Zorin 12 | 196       | 4.54%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 4302      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 190       | 3.91%   |
| 5.11.0-38-generic | 177       | 3.64%   |
| 5.11.0-27-generic | 154       | 3.17%   |
| 5.15.0-46-generic | 152       | 3.13%   |
| 5.15.0-52-generic | 143       | 2.94%   |
| 5.13.0-30-generic | 124       | 2.55%   |
| 5.11.0-40-generic | 124       | 2.55%   |
| 5.13.0-39-generic | 120       | 2.47%   |
| 5.3.0-40-generic  | 110       | 2.26%   |
| 5.11.0-41-generic | 107       | 2.2%    |
| 5.11.0-37-generic | 107       | 2.2%    |
| 5.11.0-43-generic | 101       | 2.08%   |
| 5.4.0-42-generic  | 99        | 2.04%   |
| 5.15.0-58-generic | 96        | 1.98%   |
| 5.15.0-48-generic | 95        | 1.96%   |
| 5.11.0-34-generic | 94        | 1.94%   |
| 5.13.0-40-generic | 89        | 1.83%   |
| 5.0.0-37-generic  | 79        | 1.63%   |
| 5.15.0-53-generic | 78        | 1.61%   |
| 5.13.0-44-generic | 76        | 1.56%   |
| 5.15.0-41-generic | 75        | 1.54%   |
| 5.13.0-35-generic | 74        | 1.52%   |
| 5.3.0-46-generic  | 73        | 1.5%    |
| 5.13.0-28-generic | 71        | 1.46%   |
| 5.3.0-51-generic  | 65        | 1.34%   |
| 5.4.0-47-generic  | 60        | 1.24%   |
| 5.13.0-52-generic | 59        | 1.21%   |
| 5.13.0-27-generic | 59        | 1.21%   |
| 5.3.0-53-generic  | 54        | 1.11%   |
| 5.13.0-41-generic | 54        | 1.11%   |
| 5.4.0-58-generic  | 53        | 1.09%   |
| 5.3.0-42-generic  | 52        | 1.07%   |
| 5.4.0-48-generic  | 48        | 0.99%   |
| 5.4.0-65-generic  | 46        | 0.95%   |
| 5.4.0-45-generic  | 46        | 0.95%   |
| 5.4.0-72-generic  | 45        | 0.93%   |
| 5.4.0-80-generic  | 41        | 0.84%   |
| 5.13.0-51-generic | 41        | 0.84%   |
| 5.15.0-43-generic | 40        | 0.82%   |
| 5.11.0-36-generic | 39        | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 945       | 21.01%  |
| 5.4.0   | 923       | 20.52%  |
| 5.15.0  | 851       | 18.92%  |
| 5.13.0  | 762       | 16.94%  |
| 5.3.0   | 487       | 10.83%  |
| 4.15.0  | 189       | 4.2%    |
| 5.0.0   | 153       | 3.4%    |
| 4.18.0  | 75        | 1.67%   |
| 5.8.0   | 53        | 1.18%   |
| 5.14.0  | 8         | 0.18%   |
| 4.4.0   | 6         | 0.13%   |
| 5.7.1   | 3         | 0.07%   |
| 5.7.0   | 2         | 0.04%   |
| 5.6.0   | 2         | 0.04%   |
| 5.19.12 | 2         | 0.04%   |
| 5.17.5  | 2         | 0.04%   |
| 5.17.1  | 2         | 0.04%   |
| 5.16.0  | 2         | 0.04%   |
| 5.10.0  | 2         | 0.04%   |
| 4.13.0  | 2         | 0.04%   |
| 6.1.7   | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.9.12  | 1         | 0.02%   |
| 5.9.0   | 1         | 0.02%   |
| 5.8.5   | 1         | 0.02%   |
| 5.7.17  | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.4.1   | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.14 | 1         | 0.02%   |
| 5.19.1  | 1         | 0.02%   |
| 5.19.0  | 1         | 0.02%   |
| 5.18.6  | 1         | 0.02%   |
| 5.18.15 | 1         | 0.02%   |
| 5.17.9  | 1         | 0.02%   |
| 5.16.5  | 1         | 0.02%   |
| 5.16.14 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 945       | 21.01%  |
| 5.4     | 925       | 20.56%  |
| 5.15    | 854       | 18.99%  |
| 5.13    | 763       | 16.96%  |
| 5.3     | 487       | 10.83%  |
| 4.15    | 189       | 4.2%    |
| 5.0     | 153       | 3.4%    |
| 4.18    | 75        | 1.67%   |
| 5.8     | 54        | 1.2%    |
| 5.19    | 8         | 0.18%   |
| 5.14    | 8         | 0.18%   |
| 5.7     | 6         | 0.13%   |
| 4.4     | 6         | 0.13%   |
| 5.17    | 5         | 0.11%   |
| 5.16    | 5         | 0.11%   |
| 5.10    | 4         | 0.09%   |
| 6.0     | 2         | 0.04%   |
| 5.9     | 2         | 0.04%   |
| 5.6     | 2         | 0.04%   |
| 5.18    | 2         | 0.04%   |
| 4.13    | 2         | 0.04%   |
| 6.1     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3932      | 91.34%  |
| i686   | 373       | 8.66%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3133      | 71.91%  |
| XFCE       | 904       | 20.75%  |
| Unknown    | 296       | 6.79%   |
| X-Cinnamon | 8         | 0.18%   |
| KDE        | 4         | 0.09%   |
| Unity      | 3         | 0.07%   |
| KDE5       | 2         | 0.05%   |
| Cinnamon   | 2         | 0.05%   |
| Budgie     | 2         | 0.05%   |
| MATE       | 1         | 0.02%   |
| LXDE       | 1         | 0.02%   |
| i3         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 4093      | 94.35%  |
| Unknown | 182       | 4.2%    |
| Wayland | 62        | 1.43%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3563      | 81.51%  |
| GDM3    | 317       | 7.25%   |
| GDM     | 277       | 6.34%   |
| LightDM | 199       | 4.55%   |
| TDM     | 11        | 0.25%   |
| SDDM    | 3         | 0.07%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1566      | 36.12%  |
| de_DE   | 333       | 7.68%   |
| pt_BR   | 285       | 6.57%   |
| en_GB   | 263       | 6.07%   |
| Unknown | 230       | 5.3%    |
| it_IT   | 146       | 3.37%   |
| en_CA   | 123       | 2.84%   |
| fr_FR   | 121       | 2.79%   |
| en_IN   | 116       | 2.68%   |
| es_ES   | 111       | 2.56%   |
| pl_PL   | 97        | 2.24%   |
| en_AU   | 81        | 1.87%   |
| nl_NL   | 67        | 1.55%   |
| es_MX   | 61        | 1.41%   |
| ru_RU   | 59        | 1.36%   |
| es_AR   | 48        | 1.11%   |
| pt_PT   | 46        | 1.06%   |
| en_ZA   | 40        | 0.92%   |
| cs_CZ   | 40        | 0.92%   |
| C       | 29        | 0.67%   |
| tr_TR   | 27        | 0.62%   |
| hu_HU   | 27        | 0.62%   |
| es_CL   | 27        | 0.62%   |
| sv_SE   | 26        | 0.6%    |
| en_NZ   | 23        | 0.53%   |
| fr_CA   | 21        | 0.48%   |
| es_CO   | 20        | 0.46%   |
| ja_JP   | 19        | 0.44%   |
| de_AT   | 19        | 0.44%   |
| nl_BE   | 17        | 0.39%   |
| el_GR   | 15        | 0.35%   |
| fr_BE   | 13        | 0.3%    |
| da_DK   | 13        | 0.3%    |
| es_PE   | 12        | 0.28%   |
| en_PH   | 12        | 0.28%   |
| nb_NO   | 11        | 0.25%   |
| de_CH   | 11        | 0.25%   |
| ru_UA   | 9         | 0.21%   |
| fi_FI   | 9         | 0.21%   |
| bg_BG   | 9         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2400      | 55.16%  |
| EFI  | 1951      | 44.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 4061      | 94.09%  |
| Overlay  | 94        | 2.18%   |
| Zfs      | 51        | 1.18%   |
| Btrfs    | 35        | 0.81%   |
| Ext2     | 32        | 0.74%   |
| Unknown  | 27        | 0.63%   |
| Ext3     | 9         | 0.21%   |
| Xfs      | 6         | 0.14%   |
| Reiserfs | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3901      | 90.05%  |
| GPT     | 324       | 7.48%   |
| MBR     | 107       | 2.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4065      | 93.9%   |
| Yes       | 264       | 6.1%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3503      | 80.79%  |
| Yes       | 833       | 19.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 757       | 17.6%   |
| ASUSTek Computer    | 617       | 14.34%  |
| Dell                | 569       | 13.23%  |
| Lenovo              | 483       | 11.23%  |
| Acer                | 238       | 5.53%   |
| Gigabyte Technology | 235       | 5.46%   |
| MSI                 | 174       | 4.04%   |
| Toshiba             | 144       | 3.35%   |
| ASRock              | 124       | 2.88%   |
| Apple               | 118       | 2.74%   |
| Intel               | 67        | 1.56%   |
| Samsung Electronics | 58        | 1.35%   |
| Unknown             | 50        | 1.16%   |
| Sony                | 47        | 1.09%   |
| Fujitsu             | 38        | 0.88%   |
| Packard Bell        | 29        | 0.67%   |
| Pegatron            | 27        | 0.63%   |
| Positivo            | 23        | 0.53%   |
| Foxconn             | 22        | 0.51%   |
| Biostar             | 22        | 0.51%   |
| Microsoft           | 19        | 0.44%   |
| Medion              | 19        | 0.44%   |
| Google              | 19        | 0.44%   |
| HUAWEI              | 18        | 0.42%   |
| Fujitsu Siemens     | 18        | 0.42%   |
| ECS                 | 18        | 0.42%   |
| Alienware           | 16        | 0.37%   |
| Gateway             | 13        | 0.3%    |
| AMI                 | 13        | 0.3%    |
| Notebook            | 11        | 0.26%   |
| Panasonic           | 9         | 0.21%   |
| eMachines           | 9         | 0.21%   |
| Chuwi               | 8         | 0.19%   |
| NEC Computers       | 7         | 0.16%   |
| Shuttle             | 6         | 0.14%   |
| Semp Toshiba        | 6         | 0.14%   |
| Quanta              | 6         | 0.14%   |
| Multilaser          | 6         | 0.14%   |
| Insyde              | 6         | 0.14%   |
| IBM                 | 6         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 79        | 1.84%   |
| ASUS All Series            | 33        | 0.77%   |
| HP Notebook                | 26        | 0.6%    |
| HP Pavilion Notebook       | 16        | 0.37%   |
| HP Pavilion dv6            | 13        | 0.3%    |
| HP 15                      | 12        | 0.28%   |
| Dell OptiPlex 7010         | 11        | 0.26%   |
| Toshiba Satellite C660     | 10        | 0.23%   |
| HP Pavilion dv7            | 10        | 0.23%   |
| Dell OptiPlex 790          | 10        | 0.23%   |
| Dell OptiPlex 780          | 10        | 0.23%   |
| HP Pavilion 15             | 9         | 0.21%   |
| Dell Inspiron 1545         | 9         | 0.21%   |
| HP Pavilion g6             | 8         | 0.19%   |
| HP Laptop 15-bw0xx         | 8         | 0.19%   |
| Gigabyte A320M-S2H         | 8         | 0.19%   |
| Dell OptiPlex 380          | 8         | 0.19%   |
| Dell Latitude E6540        | 8         | 0.19%   |
| Dell Latitude D630         | 8         | 0.19%   |
| Dell Inspiron 15-3567      | 8         | 0.19%   |
| Apple MacBookPro8,1        | 8         | 0.19%   |
| Apple iMac12,2             | 8         | 0.19%   |
| MSI MS-7C02                | 7         | 0.16%   |
| Gigabyte 970A-DS3P         | 7         | 0.16%   |
| Dell OptiPlex 990          | 7         | 0.16%   |
| Dell OptiPlex 755          | 7         | 0.16%   |
| Dell Latitude E6410        | 7         | 0.16%   |
| Dell Latitude E6400        | 7         | 0.16%   |
| Dell Inspiron 3521         | 7         | 0.16%   |
| Dell Inspiron 1525         | 7         | 0.16%   |
| ASUS M5A78L-M/USB3         | 7         | 0.16%   |
| MSI MS-7817                | 6         | 0.14%   |
| Lenovo MIIX 320-10ICR 80XF | 6         | 0.14%   |
| HP ProDesk 600 G1 SFF      | 6         | 0.14%   |
| HP ProBook 640 G1          | 6         | 0.14%   |
| HP Pavilion g7             | 6         | 0.14%   |
| HP Pavilion dv6700         | 6         | 0.14%   |
| HP Pavilion 17             | 6         | 0.14%   |
| HP EliteBook 840 G1        | 6         | 0.14%   |
| Gigabyte B450 AORUS M      | 6         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 176       | 4.09%   |
| HP Pavilion           | 167       | 3.88%   |
| Acer Aspire           | 158       | 3.67%   |
| Lenovo ThinkPad       | 148       | 3.44%   |
| Dell Latitude         | 143       | 3.32%   |
| Lenovo IdeaPad        | 124       | 2.88%   |
| Toshiba Satellite     | 122       | 2.84%   |
| Dell OptiPlex         | 99        | 2.3%    |
| HP Compaq             | 97        | 2.25%   |
| Unknown               | 79        | 1.84%   |
| HP EliteBook          | 75        | 1.74%   |
| HP ProBook            | 64        | 1.49%   |
| HP Laptop             | 50        | 1.16%   |
| Lenovo ThinkCentre    | 46        | 1.07%   |
| ASUS ROG              | 43        | 1%      |
| ASUS PRIME            | 40        | 0.93%   |
| Dell Vostro           | 38        | 0.88%   |
| ASUS VivoBook         | 34        | 0.79%   |
| ASUS All              | 33        | 0.77%   |
| HP ENVY               | 32        | 0.74%   |
| Dell Precision        | 31        | 0.72%   |
| ASUS TUF              | 31        | 0.72%   |
| Dell XPS              | 30        | 0.7%    |
| Lenovo Yoga           | 26        | 0.6%    |
| HP Notebook           | 26        | 0.6%    |
| Packard Bell EasyNote | 24        | 0.56%   |
| Microsoft Surface     | 19        | 0.44%   |
| HP Stream             | 17        | 0.4%    |
| Fujitsu ESPRIMO       | 16        | 0.37%   |
| Dell Studio           | 16        | 0.37%   |
| HP Presario           | 14        | 0.33%   |
| HP EliteDesk          | 14        | 0.33%   |
| HP 15                 | 14        | 0.33%   |
| ASUS ZenBook          | 14        | 0.33%   |
| HP 255                | 13        | 0.3%    |
| Apple iMac12          | 13        | 0.3%    |
| HP ProDesk            | 12        | 0.28%   |
| HP OMEN               | 12        | 0.28%   |
| Gigabyte B450         | 12        | 0.28%   |
| Fujitsu LIFEBOOK      | 12        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 390       | 9.07%   |
| 2012    | 357       | 8.3%    |
| 2013    | 343       | 7.97%   |
| 2010    | 322       | 7.48%   |
| 2018    | 306       | 7.11%   |
| 2008    | 278       | 6.46%   |
| 2014    | 271       | 6.3%    |
| 2019    | 256       | 5.95%   |
| 2009    | 242       | 5.63%   |
| 2017    | 236       | 5.49%   |
| 2021    | 227       | 5.28%   |
| 2020    | 223       | 5.18%   |
| 2007    | 212       | 4.93%   |
| 2016    | 206       | 4.79%   |
| 2015    | 205       | 4.77%   |
| 2006    | 95        | 2.21%   |
| 2005    | 60        | 1.39%   |
| 2022    | 45        | 1.05%   |
| 2004    | 11        | 0.26%   |
| 2003    | 8         | 0.19%   |
| Unknown | 8         | 0.19%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2490      | 57.88%  |
| Desktop     | 1523      | 35.4%   |
| Convertible | 87        | 2.02%   |
| All in one  | 84        | 1.95%   |
| Tablet      | 56        | 1.3%    |
| Mini pc     | 53        | 1.23%   |
| Server      | 9         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3918      | 90.55%  |
| Enabled  | 409       | 9.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4279      | 99.47%  |
| Yes  | 23        | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1122      | 25.83%  |
| 4.01-8.0    | 999       | 23%     |
| 8.01-16.0   | 674       | 15.52%  |
| 16.01-24.0  | 567       | 13.06%  |
| 1.01-2.0    | 427       | 9.83%   |
| 32.01-64.0  | 236       | 5.43%   |
| 2.01-3.0    | 147       | 3.38%   |
| 0.51-1.0    | 89        | 2.05%   |
| 64.01-256.0 | 52        | 1.2%    |
| 24.01-32.0  | 30        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1994      | 43.08%  |
| 2.01-3.0   | 1252      | 27.05%  |
| 3.01-4.0   | 501       | 10.82%  |
| 4.01-8.0   | 390       | 8.43%   |
| 0.51-1.0   | 375       | 8.1%    |
| 8.01-16.0  | 63        | 1.36%   |
| 0.01-0.5   | 41        | 0.89%   |
| 16.01-24.0 | 8         | 0.17%   |
| 24.01-32.0 | 4         | 0.09%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2894      | 65.94%  |
| 2       | 1028      | 23.42%  |
| 3       | 245       | 5.58%   |
| 4       | 98        | 2.23%   |
| 5       | 49        | 1.12%   |
| 6       | 28        | 0.64%   |
| 0       | 22        | 0.5%    |
| 7       | 11        | 0.25%   |
| 8       | 9         | 0.21%   |
| 51      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2192      | 50.71%  |
| No        | 2131      | 49.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3750      | 87.01%  |
| No        | 560       | 12.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3412      | 79%     |
| No        | 907       | 21%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2250      | 51.83%  |
| No        | 2091      | 48.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 991       | 22.95%  |
| Germany      | 386       | 8.94%   |
| Brazil       | 322       | 7.46%   |
| UK           | 263       | 6.09%   |
| Canada       | 166       | 3.84%   |
| Italy        | 163       | 3.77%   |
| Spain        | 127       | 2.94%   |
| India        | 124       | 2.87%   |
| France       | 122       | 2.82%   |
| Netherlands  | 115       | 2.66%   |
| Poland       | 98        | 2.27%   |
| Australia    | 91        | 2.11%   |
| Mexico       | 82        | 1.9%    |
| Argentina    | 60        | 1.39%   |
| Portugal     | 55        | 1.27%   |
| Russia       | 53        | 1.23%   |
| Sweden       | 48        | 1.11%   |
| South Africa | 48        | 1.11%   |
| Czechia      | 47        | 1.09%   |
| Belgium      | 47        | 1.09%   |
| Romania      | 41        | 0.95%   |
| Greece       | 40        | 0.93%   |
| Indonesia    | 39        | 0.9%    |
| Austria      | 36        | 0.83%   |
| Switzerland  | 34        | 0.79%   |
| Hungary      | 34        | 0.79%   |
| Turkey       | 33        | 0.76%   |
| Chile        | 33        | 0.76%   |
| Norway       | 30        | 0.69%   |
| Colombia     | 30        | 0.69%   |
| New Zealand  | 29        | 0.67%   |
| Japan        | 29        | 0.67%   |
| Serbia       | 27        | 0.63%   |
| Denmark      | 27        | 0.63%   |
| Egypt        | 23        | 0.53%   |
| Bulgaria     | 21        | 0.49%   |
| Ukraine      | 19        | 0.44%   |
| Philippines  | 18        | 0.42%   |
| Finland      | 16        | 0.37%   |
| Slovakia     | 15        | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 36        | 0.8%    |
| Sao Paulo      | 35        | 0.78%   |
| Athens         | 29        | 0.65%   |
| Sydney         | 26        | 0.58%   |
| Munich         | 26        | 0.58%   |
| Rio de Janeiro | 23        | 0.51%   |
| Vienna         | 22        | 0.49%   |
| Madrid         | 22        | 0.49%   |
| Milan          | 21        | 0.47%   |
| Rome           | 19        | 0.42%   |
| Montreal       | 18        | 0.4%    |
| Toronto        | 17        | 0.38%   |
| New York       | 17        | 0.38%   |
| Dallas         | 17        | 0.38%   |
| Auckland       | 17        | 0.38%   |
| Perth          | 16        | 0.36%   |
| Johannesburg   | 16        | 0.36%   |
| Belgrade       | 16        | 0.36%   |
| Cairo          | 15        | 0.33%   |
| Buenos Aires   | 15        | 0.33%   |
| Bengaluru      | 15        | 0.33%   |
| Warsaw         | 14        | 0.31%   |
| Mexico City    | 14        | 0.31%   |
| London         | 14        | 0.31%   |
| Istanbul       | 14        | 0.31%   |
| Hamburg        | 14        | 0.31%   |
| Bogotá        | 14        | 0.31%   |
| Paris          | 13        | 0.29%   |
| Moscow         | 13        | 0.29%   |
| Jakarta        | 13        | 0.29%   |
| Denver         | 13        | 0.29%   |
| Bucharest      | 13        | 0.29%   |
| Brisbane       | 13        | 0.29%   |
| Zurich         | 12        | 0.27%   |
| Seattle        | 12        | 0.27%   |
| Prague         | 12        | 0.27%   |
| Stockholm      | 11        | 0.25%   |
| Portland       | 11        | 0.25%   |
| Phoenix        | 11        | 0.25%   |
| Nairobi        | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 978       | 1335   | 16.87%  |
| WDC                       | 869       | 1141   | 14.99%  |
| Samsung Electronics       | 703       | 998    | 12.12%  |
| Toshiba                   | 467       | 585    | 8.05%   |
| Unknown                   | 330       | 468    | 5.69%   |
| Kingston                  | 302       | 385    | 5.21%   |
| SanDisk                   | 298       | 349    | 5.14%   |
| Hitachi                   | 283       | 346    | 4.88%   |
| Crucial                   | 189       | 227    | 3.26%   |
| Intel                     | 109       | 144    | 1.88%   |
| HGST                      | 105       | 128    | 1.81%   |
| SK hynix                  | 80        | 97     | 1.38%   |
| A-DATA Technology         | 69        | 78     | 1.19%   |
| China                     | 58        | 66     | 1%      |
| Micron Technology         | 56        | 65     | 0.97%   |
| Apple                     | 47        | 50     | 0.81%   |
| Phison                    | 46        | 58     | 0.79%   |
| Maxtor                    | 42        | 59     | 0.72%   |
| PNY                       | 41        | 52     | 0.71%   |
| Fujitsu                   | 41        | 43     | 0.71%   |
| Intenso                   | 39        | 43     | 0.67%   |
| Silicon Motion            | 32        | 40     | 0.55%   |
| SPCC                      | 29        | 33     | 0.5%    |
| Patriot                   | 28        | 39     | 0.48%   |
| OCZ                       | 26        | 30     | 0.45%   |
| JMicron Technology        | 22        | 28     | 0.38%   |
| Transcend                 | 21        | 42     | 0.36%   |
| LITEON                    | 21        | 26     | 0.36%   |
| KIOXIA                    | 21        | 22     | 0.36%   |
| Netac                     | 20        | 22     | 0.34%   |
| Micron/Crucial Technology | 17        | 18     | 0.29%   |
| GOODRAM                   | 17        | 18     | 0.29%   |
| SABRENT                   | 16        | 17     | 0.28%   |
| LITEONIT                  | 16        | 18     | 0.28%   |
| Hewlett-Packard           | 15        | 19     | 0.26%   |
| Unknown                   | 15        | 17     | 0.26%   |
| Team                      | 14        | 17     | 0.24%   |
| Lexar                     | 13        | 13     | 0.22%   |
| KingSpec                  | 11        | 13     | 0.19%   |
| Gigabyte Technology       | 11        | 19     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 114       | 1.81%   |
| Unknown MMC Card  64GB                 | 88        | 1.4%    |
| Kingston SA400S37240G 240GB SSD        | 75        | 1.19%   |
| Seagate ST500DM002-1BD142 500GB        | 52        | 0.82%   |
| Toshiba MQ01ABF050 500GB               | 48        | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB         | 48        | 0.76%   |
| Kingston SA400S37480G 480GB SSD        | 45        | 0.71%   |
| Crucial CT240BX500SSD1 240GB           | 42        | 0.67%   |
| Samsung SSD 860 EVO 500GB              | 41        | 0.65%   |
| Kingston SA400S37120G 120GB SSD        | 40        | 0.63%   |
| Toshiba MQ01ABD100 1TB                 | 39        | 0.62%   |
| Unknown MMC Card  128GB                | 37        | 0.59%   |
| Seagate ST500LT012-1DG142 500GB        | 37        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 36        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB         | 36        | 0.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 34        | 0.54%   |
| Samsung NVMe SSD Drive 512GB           | 33        | 0.52%   |
| Toshiba MQ04ABF100 1TB                 | 32        | 0.51%   |
| Samsung SSD 850 EVO 500GB              | 31        | 0.49%   |
| Unknown SD/MMC/MS PRO 2GB              | 30        | 0.48%   |
| Samsung NVMe SSD Drive 500GB           | 30        | 0.48%   |
| Samsung SSD 850 EVO 250GB              | 29        | 0.46%   |
| Samsung NVMe SSD Drive 1TB             | 29        | 0.46%   |
| Kingston SV300S37A120G 120GB SSD       | 29        | 0.46%   |
| Seagate ST9500325AS 500GB              | 28        | 0.44%   |
| Seagate ST3500418AS 500GB              | 28        | 0.44%   |
| Crucial CT500MX500SSD1 500GB           | 27        | 0.43%   |
| Seagate Expansion 240GB                | 25        | 0.4%    |
| Toshiba DT01ACA100 1TB                 | 24        | 0.38%   |
| Unknown MMC Card  16GB                 | 23        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB               | 22        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 22        | 0.35%   |
| SanDisk NVMe SSD Drive 256GB           | 22        | 0.35%   |
| Samsung SSD 860 EVO 250GB              | 22        | 0.35%   |
| Samsung SSD 840 EVO 250GB              | 21        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB         | 20        | 0.32%   |
| Intel NVMe SSD Drive 512GB             | 20        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB         | 19        | 0.3%    |
| SanDisk NVMe SSD Drive 512GB           | 19        | 0.3%    |
| Hitachi HTS545032B9A300 320GB          | 19        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 967       | 1307   | 33.88%  |
| WDC                 | 786       | 1017   | 27.54%  |
| Toshiba             | 394       | 499    | 13.81%  |
| Hitachi             | 283       | 346    | 9.92%   |
| Samsung Electronics | 141       | 179    | 4.94%   |
| HGST                | 105       | 128    | 3.68%   |
| Fujitsu             | 41        | 43     | 1.44%   |
| Maxtor              | 40        | 57     | 1.4%    |
| Unknown             | 30        | 39     | 1.05%   |
| Apple               | 24        | 26     | 0.84%   |
| SABRENT             | 16        | 17     | 0.56%   |
| ASMT                | 7         | 7      | 0.25%   |
| USB3.0              | 4         | 5      | 0.14%   |
| IBM/Hitachi         | 4         | 5      | 0.14%   |
| Hewlett-Packard     | 3         | 6      | 0.11%   |
| JMicron Technology  | 2         | 2      | 0.07%   |
| Intenso             | 2         | 2      | 0.07%   |
| Quantum             | 1         | 1      | 0.04%   |
| Pioneer             | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 2      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 363       | 502    | 19.78%  |
| Kingston            | 262       | 327    | 14.28%  |
| SanDisk             | 188       | 223    | 10.25%  |
| Crucial             | 184       | 220    | 10.03%  |
| WDC                 | 80        | 98     | 4.36%   |
| A-DATA Technology   | 64        | 73     | 3.49%   |
| China               | 55        | 63     | 3%      |
| Intel               | 53        | 63     | 2.89%   |
| PNY                 | 41        | 52     | 2.23%   |
| Toshiba             | 39        | 45     | 2.13%   |
| Micron Technology   | 31        | 36     | 1.69%   |
| SK hynix            | 30        | 34     | 1.63%   |
| SPCC                | 27        | 31     | 1.47%   |
| Patriot             | 27        | 38     | 1.47%   |
| Intenso             | 26        | 29     | 1.42%   |
| OCZ                 | 24        | 28     | 1.31%   |
| Transcend           | 21        | 42     | 1.14%   |
| LITEON              | 21        | 26     | 1.14%   |
| Netac               | 20        | 21     | 1.09%   |
| Apple               | 19        | 19     | 1.04%   |
| LITEONIT            | 16        | 18     | 0.87%   |
| GOODRAM             | 16        | 17     | 0.87%   |
| Team                | 14        | 17     | 0.76%   |
| JMicron Technology  | 13        | 18     | 0.71%   |
| Lexar               | 12        | 12     | 0.65%   |
| Hewlett-Packard     | 11        | 12     | 0.6%    |
| KingSpec            | 10        | 12     | 0.54%   |
| Leven               | 9         | 10     | 0.49%   |
| Gigabyte Technology | 9         | 16     | 0.49%   |
| Apacer              | 9         | 10     | 0.49%   |
| Corsair             | 8         | 10     | 0.44%   |
| Plextor             | 7         | 8      | 0.38%   |
| Unknown             | 7         | 9      | 0.38%   |
| OWC                 | 6         | 7      | 0.33%   |
| Verbatim            | 4         | 4      | 0.22%   |
| TCSUNBOW            | 4         | 4      | 0.22%   |
| Super Talent        | 4         | 5      | 0.22%   |
| Seagate             | 4         | 6      | 0.22%   |
| Mushkin             | 4         | 4      | 0.22%   |
| FORESEE             | 4         | 4      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2495      | 3691   | 47.18%  |
| SSD     | 1655      | 2280   | 31.3%   |
| NVMe    | 718       | 956    | 13.58%  |
| MMC     | 306       | 423    | 5.79%   |
| Unknown | 114       | 144    | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3623      | 5804   | 74.5%   |
| NVMe | 717       | 954    | 14.74%  |
| MMC  | 306       | 423    | 6.29%   |
| SAS  | 217       | 313    | 4.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2848      | 3972   | 67.15%  |
| 0.51-1.0   | 1023      | 1395   | 24.12%  |
| 1.01-2.0   | 209       | 301    | 4.93%   |
| 3.01-4.0   | 70        | 150    | 1.65%   |
| 4.01-10.0  | 55        | 77     | 1.3%    |
| 2.01-3.0   | 32        | 60     | 0.75%   |
| 10.01-20.0 | 4         | 16     | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1447      | 32.57%  |
| 251-500        | 1095      | 24.65%  |
| 501-1000       | 583       | 13.12%  |
| 51-100         | 462       | 10.4%   |
| 21-50          | 269       | 6.05%   |
| 1001-2000      | 212       | 4.77%   |
| 1-20           | 135       | 3.04%   |
| More than 3000 | 129       | 2.9%    |
| 2001-3000      | 71        | 1.6%    |
| Unknown        | 40        | 0.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2221      | 48.23%  |
| 21-50          | 1030      | 22.37%  |
| 51-100         | 476       | 10.34%  |
| 101-250        | 379       | 8.23%   |
| 251-500        | 207       | 4.5%    |
| 501-1000       | 114       | 2.48%   |
| 1001-2000      | 63        | 1.37%   |
| More than 3000 | 58        | 1.26%   |
| Unknown        | 40        | 0.87%   |
| 2001-3000      | 17        | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 3         | 3      | 3.66%   |
| Toshiba MQ02ABD100H 1TB              | 2         | 2      | 2.44%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 2.44%   |
| Seagate ST9500420AS 500GB            | 2         | 2      | 2.44%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 2      | 2.44%   |
| Kingston SUV400S37240G 240GB SSD     | 2         | 2      | 2.44%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 1.22%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 1      | 1.22%   |
| WDC WD5000BEVT-24A0RT0 500GB         | 1         | 1      | 1.22%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 1.22%   |
| WDC WD3200BPVT-55ZEST0 320GB         | 1         | 1      | 1.22%   |
| WDC WD3200AAKS-22B3A0 320GB          | 1         | 1      | 1.22%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 1.22%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 1      | 1.22%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 1      | 1.22%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 1.22%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 1      | 1.22%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 2      | 1.22%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 1      | 1.22%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 1         | 1      | 1.22%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.22%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.22%   |
| Toshiba MK8046GSX 80GB               | 1         | 1      | 1.22%   |
| Toshiba MK5061GSY 500GB              | 1         | 1      | 1.22%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 1.22%   |
| Toshiba MK2046GSX 200GB              | 1         | 1      | 1.22%   |
| Toshiba MG03ACA200 2TB               | 1         | 1      | 1.22%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.22%   |
| Silicon Motion Inland NVMe SSD 256GB | 1         | 1      | 1.22%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 1.22%   |
| Seagate ST9320310AS 320GB            | 1         | 1      | 1.22%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.22%   |
| Seagate ST9200420ASG 200GB           | 1         | 1      | 1.22%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 1.22%   |
| Seagate ST9120822AS 120GB            | 1         | 1      | 1.22%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1      | 1.22%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.22%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 1      | 1.22%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1      | 1.22%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 1      | 1.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 30     | 35.8%   |
| WDC                 | 13        | 14     | 16.05%  |
| Toshiba             | 12        | 12     | 14.81%  |
| Kingston            | 5         | 5      | 6.17%   |
| HGST                | 5         | 5      | 6.17%   |
| Hitachi             | 4         | 4      | 4.94%   |
| Samsung Electronics | 3         | 3      | 3.7%    |
| A-DATA Technology   | 2         | 2      | 2.47%   |
| SK hynix            | 1         | 1      | 1.23%   |
| Silicon Motion      | 1         | 1      | 1.23%   |
| OCZ                 | 1         | 1      | 1.23%   |
| Micron Technology   | 1         | 1      | 1.23%   |
| LITEONIT            | 1         | 1      | 1.23%   |
| LITEON              | 1         | 1      | 1.23%   |
| Intel               | 1         | 1      | 1.23%   |
| Hewlett-Packard     | 1         | 1      | 1.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 30     | 46.03%  |
| WDC                 | 13        | 14     | 20.63%  |
| Toshiba             | 11        | 11     | 17.46%  |
| HGST                | 5         | 5      | 7.94%   |
| Hitachi             | 4         | 4      | 6.35%   |
| Samsung Electronics | 1         | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 65     | 77.22%  |
| SSD  | 15        | 15     | 18.99%  |
| NVMe | 3         | 3      | 3.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3974      | 6880   | 90.86%  |
| Works    | 320       | 529    | 7.32%   |
| Malfunc  | 78        | 83     | 1.78%   |
| Failed   | 2         | 2      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2988      | 61.22%  |
| AMD                              | 790       | 16.19%  |
| Samsung Electronics              | 254       | 5.2%    |
| Nvidia                           | 129       | 2.64%   |
| SanDisk                          | 113       | 2.32%   |
| ASMedia Technology               | 57        | 1.17%   |
| Phison Electronics               | 56        | 1.15%   |
| JMicron Technology               | 56        | 1.15%   |
| Kingston Technology Company      | 49        | 1%      |
| SK hynix                         | 46        | 0.94%   |
| Marvell Technology Group         | 40        | 0.82%   |
| VIA Technologies                 | 35        | 0.72%   |
| Toshiba America Info Systems     | 35        | 0.72%   |
| Silicon Motion                   | 34        | 0.7%    |
| Silicon Integrated Systems [SiS] | 34        | 0.7%    |
| Micron Technology                | 26        | 0.53%   |
| KIOXIA                           | 23        | 0.47%   |
| Micron/Crucial Technology        | 22        | 0.45%   |
| ADATA Technology                 | 15        | 0.31%   |
| Silicon Image                    | 14        | 0.29%   |
| Realtek Semiconductor            | 10        | 0.2%    |
| Broadcom / LSI                   | 7         | 0.14%   |
| Union Memory (Shenzhen)          | 6         | 0.12%   |
| Lite-On Technology               | 6         | 0.12%   |
| Seagate Technology               | 4         | 0.08%   |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| Apple                            | 4         | 0.08%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| OCZ Technology Group             | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Promise Technology               | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 491       | 8.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 213       | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 191       | 3.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 189       | 3.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 177       | 3%      |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 158       | 2.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 151       | 2.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 141       | 2.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 139       | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 121       | 2.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 115       | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 113       | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 112       | 1.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 110       | 1.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 106       | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 97        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 91        | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 87        | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 76        | 1.29%   |
| Intel SATA Controller [RAID mode]                                                       | 72        | 1.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 71        | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 63        | 1.07%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 61        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 60        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 57        | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 54        | 0.91%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 51        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 51        | 0.86%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 51        | 0.86%   |
| Samsung NVMe SSD Controller 980                                                         | 46        | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 44        | 0.75%   |
| Nvidia MCP61 SATA Controller                                                            | 42        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 41        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 40        | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 39        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 39        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 38        | 0.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 36        | 0.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34        | 0.58%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 33        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3059      | 59.61%  |
| IDE  | 1007      | 19.62%  |
| NVMe | 720       | 14.03%  |
| RAID | 332       | 6.47%   |
| SAS  | 8         | 0.16%   |
| SCSI | 6         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3361      | 78.13%  |
| AMD          | 940       | 21.85%  |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 62        | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 36        | 0.84%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 35        | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.51%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 22        | 0.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 22        | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 20        | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 20        | 0.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 0.44%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 19        | 0.44%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 19        | 0.44%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 19        | 0.44%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 19        | 0.44%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.42%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.42%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 17        | 0.39%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.37%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 16        | 0.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.37%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 16        | 0.37%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 16        | 0.37%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 16        | 0.37%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 16        | 0.37%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 16        | 0.37%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 16        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 852       | 19.77%  |
| Intel Core i7           | 546       | 12.67%  |
| Intel Core i3           | 396       | 9.19%   |
| Intel Core 2 Duo        | 311       | 7.22%   |
| Intel Celeron           | 279       | 6.47%   |
| Intel Atom              | 191       | 4.43%   |
| AMD Ryzen 5             | 152       | 3.53%   |
| Intel Pentium           | 136       | 3.16%   |
| Other                   | 131       | 3.04%   |
| AMD Ryzen 7             | 104       | 2.41%   |
| Intel Xeon              | 80        | 1.86%   |
| Intel Pentium Dual-Core | 79        | 1.83%   |
| AMD FX                  | 69        | 1.6%    |
| Intel Pentium Dual      | 68        | 1.58%   |
| AMD A6                  | 64        | 1.49%   |
| Intel Core 2 Quad       | 58        | 1.35%   |
| AMD A4                  | 49        | 1.14%   |
| Intel Genuine           | 45        | 1.04%   |
| AMD Ryzen 3             | 43        | 1%      |
| Intel Core 2            | 42        | 0.97%   |
| AMD Athlon 64 X2        | 39        | 0.91%   |
| AMD A8                  | 39        | 0.91%   |
| Intel Pentium 4         | 38        | 0.88%   |
| AMD A10                 | 37        | 0.86%   |
| AMD Ryzen 9             | 35        | 0.81%   |
| AMD Athlon II X2        | 29        | 0.67%   |
| Intel Celeron M         | 24        | 0.56%   |
| AMD E1                  | 24        | 0.56%   |
| Intel Pentium M         | 23        | 0.53%   |
| AMD Phenom II X4        | 22        | 0.51%   |
| AMD E                   | 20        | 0.46%   |
| AMD Athlon              | 20        | 0.46%   |
| AMD Sempron             | 17        | 0.39%   |
| AMD Turion 64 X2 Mobile | 15        | 0.35%   |
| Intel Core i9           | 14        | 0.32%   |
| Intel Pentium Silver    | 12        | 0.28%   |
| AMD Athlon II X4        | 12        | 0.28%   |
| Intel Pentium Gold      | 9         | 0.21%   |
| Intel Pentium D         | 9         | 0.21%   |
| Intel Core M            | 9         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2245      | 52.09%  |
| 4      | 1324      | 30.72%  |
| 1      | 262       | 6.08%   |
| 6      | 225       | 5.22%   |
| 8      | 165       | 3.83%   |
| 3      | 33        | 0.77%   |
| 12     | 25        | 0.58%   |
| 16     | 13        | 0.3%    |
| 10     | 12        | 0.28%   |
| 14     | 3         | 0.07%   |
| 20     | 2         | 0.05%   |
| 40     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4284      | 99.58%  |
| 2      | 18        | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2286      | 53.13%  |
| 1      | 2017      | 46.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4158      | 96.63%  |
| 32-bit         | 142       | 3.3%    |
| Unknown        | 3         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 398       | 9.1%    |
| 0x206a7    | 362       | 8.28%   |
| 0x306a9    | 289       | 6.61%   |
| 0x1067a    | 273       | 6.24%   |
| 0x306c3    | 223       | 5.1%    |
| 0x6fd      | 128       | 2.93%   |
| 0x40651    | 123       | 2.81%   |
| 0x20655    | 112       | 2.56%   |
| 0x406e3    | 89        | 2.04%   |
| 0x806e9    | 87        | 1.99%   |
| 0x406c4    | 84        | 1.92%   |
| 0x30678    | 84        | 1.92%   |
| 0x306d4    | 83        | 1.9%    |
| 0x806ea    | 71        | 1.62%   |
| 0x506e3    | 67        | 1.53%   |
| 0x806c1    | 66        | 1.51%   |
| 0x10676    | 63        | 1.44%   |
| 0x906ea    | 62        | 1.42%   |
| 0x906e9    | 56        | 1.28%   |
| 0x806ec    | 56        | 1.28%   |
| 0x6fb      | 54        | 1.24%   |
| 0x010000c8 | 50        | 1.14%   |
| 0x06000852 | 49        | 1.12%   |
| 0x06001119 | 47        | 1.08%   |
| 0x20652    | 46        | 1.05%   |
| 0x08701021 | 42        | 0.96%   |
| 0x506c9    | 41        | 0.94%   |
| 0x406c3    | 40        | 0.91%   |
| 0x08108109 | 37        | 0.85%   |
| 0x706a8    | 36        | 0.82%   |
| 0x106ca    | 36        | 0.82%   |
| 0x06006705 | 35        | 0.8%    |
| 0x6f6      | 34        | 0.78%   |
| 0x0700010f | 32        | 0.73%   |
| 0x706e5    | 30        | 0.69%   |
| 0x6e8      | 30        | 0.69%   |
| 0x6d8      | 29        | 0.66%   |
| 0x07030105 | 27        | 0.62%   |
| 0x0800820d | 26        | 0.59%   |
| 0x05000119 | 26        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 415       | 9.64%   |
| SandyBridge      | 385       | 8.94%   |
| Haswell          | 378       | 8.78%   |
| Penryn           | 357       | 8.29%   |
| IvyBridge        | 308       | 7.15%   |
| Core             | 275       | 6.39%   |
| Silvermont       | 243       | 5.64%   |
| Westmere         | 177       | 4.11%   |
| Skylake          | 167       | 3.88%   |
| K10              | 113       | 2.62%   |
| Piledriver       | 103       | 2.39%   |
| Zen+             | 101       | 2.35%   |
| Zen 2            | 99        | 2.3%    |
| K8 Hammer        | 96        | 2.23%   |
| Broadwell        | 88        | 2.04%   |
| P6               | 82        | 1.9%    |
| TigerLake        | 76        | 1.77%   |
| Bonnell          | 73        | 1.7%    |
| Zen 3            | 70        | 1.63%   |
| Excavator        | 69        | 1.6%    |
| Zen              | 61        | 1.42%   |
| Goldmont plus    | 60        | 1.39%   |
| CometLake        | 57        | 1.32%   |
| NetBurst         | 55        | 1.28%   |
| Icelake          | 52        | 1.21%   |
| Goldmont         | 44        | 1.02%   |
| Puma             | 43        | 1%      |
| Nehalem          | 43        | 1%      |
| Bobcat           | 40        | 0.93%   |
| Jaguar           | 39        | 0.91%   |
| Unknown          | 37        | 0.86%   |
| K10 Llano        | 26        | 0.6%    |
| Steamroller      | 19        | 0.44%   |
| Bulldozer        | 17        | 0.39%   |
| K8 & K10 hybrid  | 15        | 0.35%   |
| Alderlake Hybrid | 13        | 0.3%    |
| Tremont          | 6         | 0.14%   |
| K6               | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2543      | 52.36%  |
| Nvidia                           | 1143      | 23.53%  |
| AMD                              | 1118      | 23.02%  |
| Silicon Integrated Systems [SiS] | 27        | 0.56%   |
| VIA Technologies                 | 17        | 0.35%   |
| Matrox Electronics Systems       | 5         | 0.1%    |
| ASPEED Technology                | 2         | 0.04%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 297       | 5.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 187       | 3.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 135       | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 126       | 2.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 120       | 2.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 120       | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 107       | 2.1%    |
| Intel HD Graphics 620                                                                    | 85        | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 77        | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 74        | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 74        | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 74        | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 71        | 1.4%    |
| Intel UHD Graphics 620                                                                   | 66        | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 63        | 1.24%   |
| Intel HD Graphics 5500                                                                   | 60        | 1.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 59        | 1.16%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 54        | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 53        | 1.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 52        | 1.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 52        | 1.02%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 49        | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 48        | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 45        | 0.88%   |
| Intel HD Graphics 630                                                                    | 43        | 0.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 0.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 40        | 0.79%   |
| Intel HD Graphics 530                                                                    | 39        | 0.77%   |
| AMD Renoir                                                                               | 39        | 0.77%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.73%   |
| Intel HD Graphics 500                                                                    | 36        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 35        | 0.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 0.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 27        | 0.53%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27        | 0.53%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 27        | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 26        | 0.51%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26        | 0.51%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 26        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2040      | 47.26%  |
| 1 x AMD                  | 898       | 20.8%   |
| 1 x Nvidia               | 763       | 17.67%  |
| Intel + Nvidia           | 332       | 7.69%   |
| Intel + AMD              | 118       | 2.73%   |
| 2 x AMD                  | 66        | 1.53%   |
| AMD + Nvidia             | 34        | 0.79%   |
| 1 x SiS                  | 27        | 0.63%   |
| 1 x VIA                  | 17        | 0.39%   |
| 2 x Nvidia               | 7         | 0.16%   |
| Other                    | 5         | 0.12%   |
| 1 x Matrox               | 5         | 0.12%   |
| 2 x Intel                | 1         | 0.02%   |
| 1 x Trident Microsystems | 1         | 0.02%   |
| Nvidia + Silicon Motion  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| 1 x ASPEED               | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3502      | 80.84%  |
| Proprietary | 621       | 14.34%  |
| Unknown     | 209       | 4.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2461      | 56.19%  |
| 0.01-0.5   | 684       | 15.62%  |
| 1.01-2.0   | 456       | 10.41%  |
| 0.51-1.0   | 382       | 8.72%   |
| 3.01-4.0   | 184       | 4.2%    |
| 7.01-8.0   | 106       | 2.42%   |
| 5.01-6.0   | 51        | 1.16%   |
| 8.01-16.0  | 29        | 0.66%   |
| 2.01-3.0   | 22        | 0.5%    |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 603       | 14.13%  |
| AU Optronics            | 516       | 12.09%  |
| LG Display              | 386       | 9.04%   |
| Chimei Innolux          | 339       | 7.94%   |
| BOE                     | 295       | 6.91%   |
| Dell                    | 210       | 4.92%   |
| Goldstar                | 191       | 4.48%   |
| Hewlett-Packard         | 159       | 3.73%   |
| Acer                    | 120       | 2.81%   |
| Chi Mei Optoelectronics | 107       | 2.51%   |
| Apple                   | 102       | 2.39%   |
| AOC                     | 88        | 2.06%   |
| Philips                 | 85        | 1.99%   |
| Ancor Communications    | 75        | 1.76%   |
| LG Philips              | 67        | 1.57%   |
| BenQ                    | 66        | 1.55%   |
| Lenovo                  | 63        | 1.48%   |
| Sharp                   | 46        | 1.08%   |
| LG Electronics          | 40        | 0.94%   |
| InfoVision              | 39        | 0.91%   |
| ViewSonic               | 37        | 0.87%   |
| Unknown                 | 35        | 0.82%   |
| Sony                    | 32        | 0.75%   |
| PANDA                   | 26        | 0.61%   |
| Vizio                   | 25        | 0.59%   |
| Toshiba                 | 25        | 0.59%   |
| HannStar                | 25        | 0.59%   |
| Iiyama                  | 23        | 0.54%   |
| ASUSTek Computer        | 20        | 0.47%   |
| CPT                     | 18        | 0.42%   |
| Unknown                 | 18        | 0.42%   |
| Eizo                    | 16        | 0.37%   |
| Sceptre Tech            | 14        | 0.33%   |
| NEC Computers           | 13        | 0.3%    |
| Panasonic               | 12        | 0.28%   |
| Fujitsu Siemens         | 12        | 0.28%   |
| Quanta Display          | 11        | 0.26%   |
| LGD                     | 10        | 0.23%   |
| HPN                     | 10        | 0.23%   |
| Gateway                 | 10        | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 31        | 0.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 20        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.41%   |
| Unknown                                                                  | 18        | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.27%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 11        | 0.25%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 11        | 0.25%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 10        | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.23%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.23%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 9         | 0.21%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.21%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.21%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 8         | 0.18%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 8         | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.18%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 8         | 0.18%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1377      | 32.93%  |
| 1366x768 (WXGA)    | 1152      | 27.55%  |
| 1600x900 (HD+)     | 243       | 5.81%   |
| 1280x800 (WXGA)    | 205       | 4.9%    |
| 3840x2160 (4K)     | 177       | 4.23%   |
| 1280x1024 (SXGA)   | 139       | 3.32%   |
| 1440x900 (WXGA+)   | 138       | 3.3%    |
| 1680x1050 (WSXGA+) | 122       | 2.92%   |
| 2560x1440 (QHD)    | 91        | 2.18%   |
| Unknown            | 71        | 1.7%    |
| 1920x1200 (WUXGA)  | 69        | 1.65%   |
| 1360x768           | 62        | 1.48%   |
| 1024x600           | 46        | 1.1%    |
| 3840x1080          | 26        | 0.62%   |
| 1024x768 (XGA)     | 24        | 0.57%   |
| 3440x1440          | 23        | 0.55%   |
| 2560x1600          | 23        | 0.55%   |
| 2560x1080          | 19        | 0.45%   |
| 1920x540           | 19        | 0.45%   |
| 2736x1824          | 12        | 0.29%   |
| 2256x1504          | 8         | 0.19%   |
| 2160x1440          | 8         | 0.19%   |
| 1600x1200          | 8         | 0.19%   |
| 5760x1080          | 7         | 0.17%   |
| 3200x1800 (QHD+)   | 7         | 0.17%   |
| 1280x768           | 7         | 0.17%   |
| 3840x2400          | 5         | 0.12%   |
| 3600x1080          | 5         | 0.12%   |
| 2880x1800          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 5760x2160          | 4         | 0.1%    |
| 4480x1440          | 4         | 0.1%    |
| 3840x1600          | 4         | 0.1%    |
| 1680x945           | 4         | 0.1%    |
| 2048x1152          | 3         | 0.07%   |
| 1920x1280          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 1024x576           | 3         | 0.07%   |
| 6400x1440          | 2         | 0.05%   |
| 5440x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1189      | 28.07%  |
| Unknown | 363       | 8.57%   |
| 13      | 346       | 8.17%   |
| 14      | 298       | 7.03%   |
| 17      | 291       | 6.87%   |
| 27      | 190       | 4.49%   |
| 24      | 183       | 4.32%   |
| 21      | 183       | 4.32%   |
| 23      | 181       | 4.27%   |
| 19      | 126       | 2.97%   |
| 18      | 111       | 2.62%   |
| 11      | 99        | 2.34%   |
| 20      | 93        | 2.2%    |
| 12      | 80        | 1.89%   |
| 31      | 77        | 1.82%   |
| 22      | 75        | 1.77%   |
| 10      | 58        | 1.37%   |
| 34      | 37        | 0.87%   |
| 40      | 29        | 0.68%   |
| 84      | 24        | 0.57%   |
| 72      | 23        | 0.54%   |
| 54      | 21        | 0.5%    |
| 32      | 17        | 0.4%    |
| 16      | 17        | 0.4%    |
| 26      | 16        | 0.38%   |
| 25      | 10        | 0.24%   |
| 52      | 9         | 0.21%   |
| 65      | 7         | 0.17%   |
| 49      | 6         | 0.14%   |
| 42      | 6         | 0.14%   |
| 74      | 5         | 0.12%   |
| 37      | 5         | 0.12%   |
| 36      | 5         | 0.12%   |
| 33      | 5         | 0.12%   |
| 29      | 5         | 0.12%   |
| 8       | 4         | 0.09%   |
| 64      | 3         | 0.07%   |
| 55      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 47      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1697      | 40.61%  |
| 501-600     | 523       | 12.51%  |
| 401-500     | 520       | 12.44%  |
| 201-300     | 399       | 9.55%   |
| Unknown     | 363       | 8.69%   |
| 351-400     | 335       | 8.02%   |
| 601-700     | 102       | 2.44%   |
| 1001-1500   | 65        | 1.56%   |
| 701-800     | 64        | 1.53%   |
| 1501-2000   | 55        | 1.32%   |
| 801-900     | 39        | 0.93%   |
| 901-1000    | 13        | 0.31%   |
| 101-200     | 4         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2812      | 71.32%  |
| 16/10   | 545       | 13.82%  |
| Unknown | 321       | 8.14%   |
| 5/4     | 124       | 3.14%   |
| 4/3     | 41        | 1.04%   |
| 21/9    | 41        | 1.04%   |
| 3/2     | 40        | 1.01%   |
| 32/9    | 11        | 0.28%   |
| 6/5     | 5         | 0.13%   |
| 3.73    | 2         | 0.05%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1186      | 28.19%  |
| 81-90          | 519       | 12.34%  |
| 201-250        | 485       | 11.53%  |
| Unknown        | 363       | 8.63%   |
| 151-200        | 299       | 7.11%   |
| 301-350        | 194       | 4.61%   |
| 121-130        | 165       | 3.92%   |
| 141-150        | 158       | 3.76%   |
| 351-500        | 145       | 3.45%   |
| 71-80          | 123       | 2.92%   |
| More than 1000 | 108       | 2.57%   |
| 51-60          | 101       | 2.4%    |
| 251-300        | 79        | 1.88%   |
| 61-70          | 71        | 1.69%   |
| 501-1000       | 65        | 1.55%   |
| 131-140        | 60        | 1.43%   |
| 41-50          | 56        | 1.33%   |
| 111-120        | 13        | 0.31%   |
| 91-100         | 13        | 0.31%   |
| 1-40           | 4         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1361      | 33.18%  |
| 51-100        | 1302      | 31.74%  |
| 121-160       | 776       | 18.92%  |
| Unknown       | 363       | 8.85%   |
| 161-240       | 143       | 3.49%   |
| 1-50          | 109       | 2.66%   |
| More than 240 | 48        | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3655      | 83.62%  |
| 2     | 458       | 10.48%  |
| 0     | 212       | 4.85%   |
| 3     | 42        | 0.96%   |
| 4     | 3         | 0.07%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2293      | 34%     |
| Intel                             | 1673      | 24.8%   |
| Qualcomm Atheros                  | 911       | 13.51%  |
| Broadcom                          | 552       | 8.18%   |
| Broadcom Limited                  | 174       | 2.58%   |
| Marvell Technology Group          | 126       | 1.87%   |
| Ralink Technology                 | 115       | 1.7%    |
| Nvidia                            | 112       | 1.66%   |
| Ralink                            | 90        | 1.33%   |
| TP-Link                           | 78        | 1.16%   |
| Samsung Electronics               | 43        | 0.64%   |
| MediaTek                          | 43        | 0.64%   |
| Silicon Integrated Systems [SiS]  | 31        | 0.46%   |
| VIA Technologies                  | 29        | 0.43%   |
| ASIX Electronics                  | 28        | 0.42%   |
| Xiaomi                            | 27        | 0.4%    |
| NetGear                           | 27        | 0.4%    |
| JMicron Technology                | 24        | 0.36%   |
| D-Link                            | 24        | 0.36%   |
| Qualcomm Atheros Communications   | 22        | 0.33%   |
| D-Link System                     | 22        | 0.33%   |
| Huawei Technologies               | 21        | 0.31%   |
| Edimax Technology                 | 18        | 0.27%   |
| DisplayLink                       | 18        | 0.27%   |
| Dell                              | 18        | 0.27%   |
| ASUSTek Computer                  | 16        | 0.24%   |
| Sierra Wireless                   | 13        | 0.19%   |
| Hewlett-Packard                   | 13        | 0.19%   |
| Microsoft                         | 12        | 0.18%   |
| OPPO Electronics                  | 10        | 0.15%   |
| Motorola PCS                      | 10        | 0.15%   |
| Qualcomm                          | 9         | 0.13%   |
| Ericsson Business Mobile Networks | 9         | 0.13%   |
| Belkin Components                 | 9         | 0.13%   |
| Linksys                           | 8         | 0.12%   |
| AMD                               | 8         | 0.12%   |
| Aquantia                          | 7         | 0.1%    |
| Attansic Technology               | 6         | 0.09%   |
| T & A Mobile Phones               | 5         | 0.07%   |
| Sitecom Europe                    | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1371      | 17.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 437       | 5.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 186       | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 144       | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 130       | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 121       | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 111       | 1.41%   |
| Intel Wireless 7260                                                     | 100       | 1.27%   |
| Intel Wi-Fi 6 AX200                                                     | 96        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 84        | 1.07%   |
| Intel Wireless 7265                                                     | 77        | 0.98%   |
| Intel Wireless 8265 / 8275                                              | 76        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 76        | 0.97%   |
| Intel Ethernet Connection I217-LM                                       | 73        | 0.93%   |
| Intel Wireless 3165                                                     | 65        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 64        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 63        | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 63        | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 0.78%   |
| Intel I211 Gigabit Network Connection                                   | 58        | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 57        | 0.73%   |
| Ralink MT7601U Wireless Adapter                                         | 55        | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 54        | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                       | 54        | 0.69%   |
| Intel Wireless 8260                                                     | 54        | 0.69%   |
| Intel Wi-Fi 6 AX201                                                     | 51        | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 48        | 0.61%   |
| Realtek 802.11ac NIC                                                    | 47        | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 47        | 0.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 45        | 0.57%   |
| Intel WiFi Link 5100                                                    | 43        | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 41        | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 40        | 0.51%   |
| Nvidia MCP61 Ethernet                                                   | 40        | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 35        | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 34        | 0.43%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 34        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1227      | 33.28%  |
| Qualcomm Atheros                      | 728       | 19.75%  |
| Realtek Semiconductor                 | 697       | 18.9%   |
| Broadcom                              | 383       | 10.39%  |
| Ralink Technology                     | 115       | 3.12%   |
| Broadcom Limited                      | 112       | 3.04%   |
| Ralink                                | 90        | 2.44%   |
| TP-Link                               | 69        | 1.87%   |
| MediaTek                              | 32        | 0.87%   |
| NetGear                               | 26        | 0.71%   |
| D-Link                                | 24        | 0.65%   |
| Qualcomm Atheros Communications       | 22        | 0.6%    |
| Edimax Technology                     | 18        | 0.49%   |
| D-Link System                         | 18        | 0.49%   |
| Marvell Technology Group              | 17        | 0.46%   |
| ASUSTek Computer                      | 14        | 0.38%   |
| Sierra Wireless                       | 13        | 0.35%   |
| Microsoft                             | 10        | 0.27%   |
| Dell                                  | 9         | 0.24%   |
| Belkin Components                     | 9         | 0.24%   |
| Linksys                               | 8         | 0.22%   |
| Sitecom Europe                        | 4         | 0.11%   |
| Micro Star International              | 4         | 0.11%   |
| Gemtek                                | 4         | 0.11%   |
| ZyDAS                                 | 3         | 0.08%   |
| Hewlett-Packard                       | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Xiaomi                                | 2         | 0.05%   |
| TRENDnet                              | 2         | 0.05%   |
| Senao                                 | 2         | 0.05%   |
| IMC Networks                          | 2         | 0.05%   |
| Fibocom                               | 2         | 0.05%   |
| AVM                                   | 2         | 0.05%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 144       | 3.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 130       | 3.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 121       | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 111       | 2.98%   |
| Intel Wireless 7260                                                     | 100       | 2.69%   |
| Intel Wi-Fi 6 AX200                                                     | 96        | 2.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 84        | 2.26%   |
| Intel Wireless 7265                                                     | 77        | 2.07%   |
| Intel Wireless 8265 / 8275                                              | 76        | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 76        | 2.04%   |
| Intel Wireless 3165                                                     | 65        | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 64        | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 63        | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 1.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 1.64%   |
| Ralink MT7601U Wireless Adapter                                         | 55        | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 54        | 1.45%   |
| Intel Wireless 8260                                                     | 54        | 1.45%   |
| Intel Wi-Fi 6 AX201                                                     | 51        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 48        | 1.29%   |
| Realtek 802.11ac NIC                                                    | 47        | 1.26%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 47        | 1.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 45        | 1.21%   |
| Intel WiFi Link 5100                                                    | 43        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 40        | 1.07%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 37        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 35        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 34        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 34        | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.89%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 33        | 0.89%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 32        | 0.86%   |
| Intel Wireless 3160                                                     | 31        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 30        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 28        | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 27        | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 26        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 25        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2002      | 50.52%  |
| Intel                                  | 862       | 21.75%  |
| Qualcomm Atheros                       | 265       | 6.69%   |
| Broadcom                               | 237       | 5.98%   |
| Nvidia                                 | 112       | 2.83%   |
| Marvell Technology Group               | 109       | 2.75%   |
| Broadcom Limited                       | 68        | 1.72%   |
| Samsung Electronics                    | 42        | 1.06%   |
| VIA Technologies                       | 29        | 0.73%   |
| Silicon Integrated Systems [SiS]       | 29        | 0.73%   |
| ASIX Electronics                       | 28        | 0.71%   |
| Xiaomi                                 | 25        | 0.63%   |
| JMicron Technology                     | 24        | 0.61%   |
| DisplayLink                            | 18        | 0.45%   |
| Huawei Technologies                    | 17        | 0.43%   |
| MediaTek                               | 11        | 0.28%   |
| OPPO Electronics                       | 10        | 0.25%   |
| TP-Link                                | 9         | 0.23%   |
| Qualcomm                               | 8         | 0.2%    |
| Motorola PCS                           | 7         | 0.18%   |
| Aquantia                               | 7         | 0.18%   |
| Attansic Technology                    | 6         | 0.15%   |
| Google                                 | 4         | 0.1%    |
| D-Link System                          | 4         | 0.1%    |
| Hewlett-Packard                        | 3         | 0.08%   |
| Davicom Semiconductor                  | 3         | 0.08%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| ASUSTek Computer                       | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Sun Microsystems                       | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Research In Motion                     | 1         | 0.03%   |
| Novatel Wireless                       | 1         | 0.03%   |
| NetGear                                | 1         | 0.03%   |
| Motorola BCS                           | 1         | 0.03%   |
| Microsoft                              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1371      | 34.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 437       | 10.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 186       | 4.63%   |
| Intel Ethernet Connection I217-LM                                 | 73        | 1.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 63        | 1.57%   |
| Intel I211 Gigabit Network Connection                             | 58        | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 57        | 1.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 54        | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 41        | 1.02%   |
| Nvidia MCP61 Ethernet                                             | 40        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 34        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 30        | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.7%    |
| Intel 82567LM Gigabit Network Connection                          | 28        | 0.7%    |
| Intel Ethernet Controller I225-V                                  | 27        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 25        | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 24        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 24        | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 23        | 0.57%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 23        | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23        | 0.57%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 22        | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 21        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21        | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 20        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20        | 0.5%    |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 18        | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 18        | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 18        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3746      | 51.56%  |
| WiFi     | 3411      | 46.95%  |
| Modem    | 95        | 1.31%   |
| Unknown  | 13        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2677      | 60.06%  |
| Ethernet | 1776      | 39.85%  |
| Modem    | 2         | 0.04%   |
| Unknown  | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2485      | 57.58%  |
| 1     | 1624      | 37.63%  |
| 0     | 136       | 3.15%   |
| 3     | 64        | 1.48%   |
| 5     | 4         | 0.09%   |
| 4     | 2         | 0.05%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3412      | 78.26%  |
| Yes  | 948       | 21.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 812       | 35.66%  |
| Realtek Semiconductor           | 263       | 11.55%  |
| Qualcomm Atheros Communications | 243       | 10.67%  |
| Broadcom                        | 166       | 7.29%   |
| Cambridge Silicon Radio         | 130       | 5.71%   |
| Apple                           | 113       | 4.96%   |
| IMC Networks                    | 99        | 4.35%   |
| Lite-On Technology              | 70        | 3.07%   |
| Dell                            | 62        | 2.72%   |
| Foxconn / Hon Hai               | 59        | 2.59%   |
| Hewlett-Packard                 | 55        | 2.42%   |
| Toshiba                         | 35        | 1.54%   |
| ASUSTek Computer                | 35        | 1.54%   |
| Ralink                          | 21        | 0.92%   |
| Marvell Semiconductor           | 14        | 0.61%   |
| Alps Electric                   | 13        | 0.57%   |
| Realtek                         | 12        | 0.53%   |
| MediaTek                        | 10        | 0.44%   |
| Foxconn International           | 10        | 0.44%   |
| Dynex                           | 8         | 0.35%   |
| Integrated System Solution      | 7         | 0.31%   |
| Askey Computer                  | 6         | 0.26%   |
| TP-Link                         | 5         | 0.22%   |
| Taiyo Yuden                     | 4         | 0.18%   |
| Ralink Technology               | 4         | 0.18%   |
| Micro Star International        | 4         | 0.18%   |
| Belkin Components               | 4         | 0.18%   |
| Chicony Electronics             | 3         | 0.13%   |
| Qcom                            | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 383       | 16.81%  |
| Realtek Bluetooth Radio                             | 168       | 7.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 130       | 5.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 104       | 4.56%   |
| Intel Bluetooth Device                              | 98        | 4.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 96        | 4.21%   |
| Intel AX200 Bluetooth                               | 84        | 3.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 71        | 3.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 46        | 2.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 1.8%    |
| IMC Networks Bluetooth Device                       | 39        | 1.71%   |
| Apple Bluetooth Host Controller                     | 39        | 1.71%   |
| Lite-On Bluetooth Device                            | 38        | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 1.45%   |
| Intel AX210 Bluetooth                               | 32        | 1.4%    |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 1.36%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 31        | 1.36%   |
| Apple Bluetooth USB Host Controller                 | 29        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 28        | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 27        | 1.18%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 27        | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.1%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 24        | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 23        | 1.01%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.83%   |
| Apple Bluetooth HCI                                 | 18        | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.75%   |
| Dell DW375 Bluetooth Module                         | 17        | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 17        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 14        | 0.61%   |
| Marvell Bluetooth and Wireless LAN Composite        | 13        | 0.57%   |
| Realtek Bluetooth Radio                             | 12        | 0.53%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.53%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.53%   |
| Toshiba Bluetooth Device                            | 11        | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3129      | 56.78%  |
| AMD                                  | 1112      | 20.18%  |
| Nvidia                               | 849       | 15.41%  |
| C-Media Electronics                  | 72        | 1.31%   |
| Silicon Integrated Systems [SiS]     | 34        | 0.62%   |
| VIA Technologies                     | 31        | 0.56%   |
| Creative Labs                        | 30        | 0.54%   |
| Logitech                             | 23        | 0.42%   |
| Texas Instruments                    | 17        | 0.31%   |
| JMTek                                | 16        | 0.29%   |
| Kingston Technology                  | 12        | 0.22%   |
| GN Netcom                            | 12        | 0.22%   |
| Generalplus Technology               | 12        | 0.22%   |
| Realtek Semiconductor                | 11        | 0.2%    |
| Razer USA                            | 9         | 0.16%   |
| Creative Technology                  | 9         | 0.16%   |
| Tenx Technology                      | 8         | 0.15%   |
| Plantronics                          | 8         | 0.15%   |
| ASUSTek Computer                     | 8         | 0.15%   |
| SteelSeries ApS                      | 6         | 0.11%   |
| KTMicro                              | 5         | 0.09%   |
| Corsair                              | 4         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| Samsung Electronics                  | 3         | 0.05%   |
| Lenovo                               | 3         | 0.05%   |
| Focusrite-Novation                   | 3         | 0.05%   |
| DSEA A/S                             | 3         | 0.05%   |
| Astro Gaming                         | 3         | 0.05%   |
| Yamaha                               | 2         | 0.04%   |
| Turtle Beach                         | 2         | 0.04%   |
| SAVITECH                             | 2         | 0.04%   |
| RODE Microphones                     | 2         | 0.04%   |
| Numark                               | 2         | 0.04%   |
| Micronas                             | 2         | 0.04%   |
| Micro Star International             | 2         | 0.04%   |
| Klipsch Audio                        | 2         | 0.04%   |
| Jieli Technology                     | 2         | 0.04%   |
| Hewlett-Packard                      | 2         | 0.04%   |
| Ensoniq                              | 2         | 0.04%   |
| DigiTech                             | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 357       | 5.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 319       | 4.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 274       | 4.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 266       | 4.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 213       | 3.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 210       | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 209       | 3.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 198       | 3.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 191       | 2.94%   |
| AMD FCH Azalia Controller                                                                         | 189       | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 154       | 2.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 130       | 2%      |
| Intel 8 Series HD Audio Controller                                                                | 129       | 1.98%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 125       | 1.92%   |
| AMD Kabini HDMI/DP Audio                                                                          | 96        | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 95        | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 93        | 1.43%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 92        | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 86        | 1.32%   |
| Intel Broadwell-U Audio Controller                                                                | 84        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 84        | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 81        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 77        | 1.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 76        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 75        | 1.15%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 74        | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 67        | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 60        | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 57        | 0.88%   |
| Nvidia High Definition Audio Controller                                                           | 54        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 54        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 52        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 52        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 50        | 0.77%   |
| AMD High Definition Audio Controller                                                              | 49        | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 45        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 44        | 0.68%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 43        | 0.66%   |
| Nvidia MCP61 High Definition Audio                                                                | 41        | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 39        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 198       | 22.15%  |
| SK hynix               | 171       | 19.13%  |
| Unknown                | 120       | 13.42%  |
| Micron Technology      | 84        | 9.4%    |
| Kingston               | 77        | 8.61%   |
| Crucial                | 38        | 4.25%   |
| Corsair                | 27        | 3.02%   |
| G.Skill                | 22        | 2.46%   |
| Unknown (ABCD)         | 20        | 2.24%   |
| Nanya Technology       | 17        | 1.9%    |
| Elpida                 | 17        | 1.9%    |
| Ramaxel Technology     | 16        | 1.79%   |
| A-DATA Technology      | 16        | 1.79%   |
| Team                   | 7         | 0.78%   |
| Qimonda                | 6         | 0.67%   |
| Patriot                | 6         | 0.67%   |
| Smart                  | 5         | 0.56%   |
| Unknown                | 4         | 0.45%   |
| Avant                  | 3         | 0.34%   |
| Transcend              | 2         | 0.22%   |
| Timetec                | 2         | 0.22%   |
| Teikon                 | 2         | 0.22%   |
| SHARETRONIC            | 2         | 0.22%   |
| High Bridge            | 2         | 0.22%   |
| ff                     | 2         | 0.22%   |
| CSX                    | 2         | 0.22%   |
| 4ea5                   | 2         | 0.22%   |
| Wilk                   | 1         | 0.11%   |
| Walton Chaintech       | 1         | 0.11%   |
| Unknown (08B5)         | 1         | 0.11%   |
| Unknown (000080B30080) | 1         | 0.11%   |
| Unifosa                | 1         | 0.11%   |
| Toshiba                | 1         | 0.11%   |
| Strontium              | 1         | 0.11%   |
| Smart Brazil           | 1         | 0.11%   |
| Ramos Technology       | 1         | 0.11%   |
| PUSKILL                | 1         | 0.11%   |
| PNY                    | 1         | 0.11%   |
| Netlist                | 1         | 0.11%   |
| Nayna                  | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 1.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.25%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.94%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 8         | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.84%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.73%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 6         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.63%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.63%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.63%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.63%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 5         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.52%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.42%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 4         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.42%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.42%   |
| Unknown                                                          | 4         | 0.42%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.31%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 3         | 0.31%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 0.31%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.31%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                  | 3         | 0.31%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 297       | 38.67%  |
| DDR4    | 252       | 32.81%  |
| DDR2    | 79        | 10.29%  |
| LPDDR4  | 40        | 5.21%   |
| SDRAM   | 35        | 4.56%   |
| Unknown | 27        | 3.52%   |
| LPDDR3  | 22        | 2.86%   |
| DDR     | 9         | 1.17%   |
| DRAM    | 6         | 0.78%   |
| LPDDR5  | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 477       | 63.1%   |
| DIMM         | 215       | 28.44%  |
| Row Of Chips | 56        | 7.41%   |
| Chip         | 4         | 0.53%   |
| Unknown      | 3         | 0.4%    |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 273       | 31.78%  |
| 8192  | 264       | 30.73%  |
| 2048  | 172       | 20.02%  |
| 1024  | 68        | 7.92%   |
| 16384 | 57        | 6.64%   |
| 512   | 12        | 1.4%    |
| 32768 | 11        | 1.28%   |
| 256   | 2         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 190       | 22.78%  |
| 2667    | 89        | 10.67%  |
| 3200    | 80        | 9.59%   |
| 1333    | 62        | 7.43%   |
| 2400    | 54        | 6.47%   |
| 667     | 41        | 4.92%   |
| Unknown | 38        | 4.56%   |
| 1334    | 36        | 4.32%   |
| 2133    | 34        | 4.08%   |
| 800     | 25        | 3%      |
| 1066    | 21        | 2.52%   |
| 3600    | 15        | 1.8%    |
| 3266    | 13        | 1.56%   |
| 1867    | 13        | 1.56%   |
| 4267    | 12        | 1.44%   |
| 533     | 11        | 1.32%   |
| 4199    | 9         | 1.08%   |
| 975     | 9         | 1.08%   |
| 2048    | 8         | 0.96%   |
| 3000    | 6         | 0.72%   |
| 1866    | 6         | 0.72%   |
| 400     | 6         | 0.72%   |
| 1067    | 5         | 0.6%    |
| 2666    | 4         | 0.48%   |
| 1800    | 4         | 0.48%   |
| 333     | 4         | 0.48%   |
| 8400    | 3         | 0.36%   |
| 3866    | 3         | 0.36%   |
| 3466    | 3         | 0.36%   |
| 2933    | 3         | 0.36%   |
| 2800    | 3         | 0.36%   |
| 4266    | 2         | 0.24%   |
| 3800    | 2         | 0.24%   |
| 3733    | 2         | 0.24%   |
| 3666    | 2         | 0.24%   |
| 3400    | 2         | 0.24%   |
| 3333    | 2         | 0.24%   |
| 1639    | 2         | 0.24%   |
| 49926   | 1         | 0.12%   |
| 6400    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 36        | 32.14%  |
| Canon                 | 25        | 22.32%  |
| Brother Industries    | 17        | 15.18%  |
| Seiko Epson           | 13        | 11.61%  |
| Samsung Electronics   | 13        | 11.61%  |
| STMicroelectronics    | 2         | 1.79%   |
| Zebra                 | 1         | 0.89%   |
| Toshiba TEC           | 1         | 0.89%   |
| Ricoh                 | 1         | 0.89%   |
| QinHeng Electronics   | 1         | 0.89%   |
| Pantum                | 1         | 0.89%   |
| Lexmark International | 1         | 0.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 3.57%   |
| Seiko Epson L3110 Series                                  | 3         | 2.68%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.68%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.79%   |
| Samsung SCX-3400 Series                                   | 2         | 1.79%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.79%   |
| Samsung CLX-3300 Series                                   | 2         | 1.79%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.79%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.79%   |
| HP ENVY 5000 series                                       | 2         | 1.79%   |
| HP ENVY 4520 series                                       | 2         | 1.79%   |
| HP DeskJet 2700 series                                    | 2         | 1.79%   |
| HP DeskJet 2130 series                                    | 2         | 1.79%   |
| HP DeskJet 1110 series                                    | 2         | 1.79%   |
| Canon PIXMA MX340                                         | 2         | 1.79%   |
| Canon MF4010 series                                       | 2         | 1.79%   |
| Brother HL-2130 series                                    | 2         | 1.79%   |
| Zebra ZP 450 Printer                                      | 1         | 0.89%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.89%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.89%   |
| Seiko Epson XP-200 Series                                 | 1         | 0.89%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.89%   |
| Seiko Epson Printer                                       | 1         | 0.89%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.89%   |
| Seiko Epson L365 Series                                   | 1         | 0.89%   |
| Seiko Epson L355 Series                                   | 1         | 0.89%   |
| Seiko Epson L220 Series                                   | 1         | 0.89%   |
| Seiko Epson L120 Series                                   | 1         | 0.89%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.89%   |
| Samsung SCX-483x 5x3x Series                              | 1         | 0.89%   |
| Samsung SCX-4200 series                                   | 1         | 0.89%   |
| Samsung ML-2950 Series                                    | 1         | 0.89%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 0.89%   |
| Samsung M2070 Series                                      | 1         | 0.89%   |
| Samsung M2020 Series                                      | 1         | 0.89%   |
| Samsung C460 Series                                       | 1         | 0.89%   |
| Ricoh SP C250SF                                           | 1         | 0.89%   |
| QinHeng CH340S                                            | 1         | 0.89%   |
| Pantum P2500W series                                      | 1         | 0.89%   |
| Lexmark International 2400 series                         | 1         | 0.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 73.33%  |
| Seiko Epson     | 2         | 13.33%  |
| Hewlett-Packard | 2         | 13.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 13.33%  |
| Canon CanoScan LIDE 25                      | 2         | 13.33%  |
| Canon CanoScan LiDE 100                     | 2         | 13.33%  |
| HP ScanJet 2400c                            | 1         | 6.67%   |
| HP PSC 1200                                 | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 6.67%   |
| Canon CanoScan LiDE 90                      | 1         | 6.67%   |
| Canon CanoScan LiDE 60                      | 1         | 6.67%   |
| Canon CanoScan LiDE 200                     | 1         | 6.67%   |
| Canon CanoScan LiDE 110                     | 1         | 6.67%   |
| Canon CanoScan D660U                        | 1         | 6.67%   |
| Canon CanoScan 8800F                        | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 551       | 22.99%  |
| Microdia                               | 223       | 9.3%    |
| Realtek Semiconductor                  | 180       | 7.51%   |
| IMC Networks                           | 170       | 7.09%   |
| Acer                                   | 150       | 6.26%   |
| Sunplus Innovation Technology          | 124       | 5.17%   |
| Suyin                                  | 115       | 4.8%    |
| Apple                                  | 111       | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 106       | 4.42%   |
| Quanta                                 | 82        | 3.42%   |
| Logitech                               | 73        | 3.05%   |
| Syntek                                 | 55        | 2.29%   |
| Silicon Motion                         | 48        | 2%      |
| Lite-On Technology                     | 43        | 1.79%   |
| Alcor Micro                            | 40        | 1.67%   |
| Ricoh                                  | 32        | 1.34%   |
| Samsung Electronics                    | 26        | 1.08%   |
| Microsoft                              | 21        | 0.88%   |
| Luxvisions Innotech Limited            | 17        | 0.71%   |
| Importek                               | 17        | 0.71%   |
| ALi                                    | 16        | 0.67%   |
| Z-Star Microelectronics                | 14        | 0.58%   |
| Primax Electronics                     | 14        | 0.58%   |
| Generalplus Technology                 | 12        | 0.5%    |
| icSpring                               | 11        | 0.46%   |
| GEMBIRD                                | 11        | 0.46%   |
| OmniVision Technologies                | 9         | 0.38%   |
| Lenovo                                 | 9         | 0.38%   |
| ARC International                      | 9         | 0.38%   |
| Sonix Technology                       | 8         | 0.33%   |
| Genesys Logic                          | 7         | 0.29%   |
| Unknown                                | 6         | 0.25%   |
| SunplusIT                              | 5         | 0.21%   |
| Sunplus Technology                     | 5         | 0.21%   |
| Cubeternet                             | 5         | 0.21%   |
| Pixart Imaging                         | 4         | 0.17%   |
| Jieli Technology                       | 4         | 0.17%   |
| Huawei Technologies                    | 4         | 0.17%   |
| Razer USA                              | 3         | 0.13%   |
| LG Electronics                         | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 63        | 2.62%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 39        | 1.62%   |
| Acer Lenovo EasyCamera                                  | 39        | 1.62%   |
| Realtek Integrated_Webcam_HD                            | 38        | 1.58%   |
| Microdia Integrated_Webcam_HD                           | 37        | 1.54%   |
| Microdia Integrated Webcam                              | 35        | 1.45%   |
| Apple FaceTime HD Camera (Built-in)                     | 35        | 1.45%   |
| Chicony HP Truevision HD                                | 32        | 1.33%   |
| Chicony HD WebCam                                       | 31        | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE                               | 31        | 1.29%   |
| Acer Integrated Camera                                  | 31        | 1.29%   |
| Samsung Galaxy A5 (MTP)                                 | 26        | 1.08%   |
| Chicony USB 2.0 Camera                                  | 26        | 1.08%   |
| Syntek Integrated Camera                                | 25        | 1.04%   |
| Realtek USB Camera                                      | 24        | 1%      |
| Chicony HP Truevision HD camera                         | 23        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 22        | 0.91%   |
| IMC Networks Integrated Camera                          | 22        | 0.91%   |
| Apple Built-in iSight                                   | 22        | 0.91%   |
| Sunplus Integrated_Webcam_HD                            | 20        | 0.83%   |
| Chicony EasyCamera                                      | 20        | 0.83%   |
| Logitech Webcam C270                                    | 19        | 0.79%   |
| Chicony Lenovo EasyCamera                               | 18        | 0.75%   |
| Chicony HP HD Webcam                                    | 18        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.75%   |
| Sunplus HD WebCam                                       | 17        | 0.71%   |
| Chicony VGA WebCam                                      | 17        | 0.71%   |
| Suyin HP Truevision HD                                  | 16        | 0.66%   |
| Realtek Integrated Webcam                               | 16        | 0.66%   |
| Microdia USB 2.0 Camera                                 | 16        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                           | 16        | 0.66%   |
| Chicony TOSHIBA Web Camera - HD                         | 16        | 0.66%   |
| Alcor Micro USB Camera                                  | 16        | 0.66%   |
| Microdia Sonix USB 2.0 Camera                           | 15        | 0.62%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.62%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 14        | 0.58%   |
| Quanta HP Webcam                                        | 14        | 0.58%   |
| Quanta HP TrueVision HD Camera                          | 14        | 0.58%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 14        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 170       | 44.39%  |
| AuthenTec                  | 55        | 14.36%  |
| Synaptics                  | 39        | 10.18%  |
| Shenzhen Goodix Technology | 37        | 9.66%   |
| Upek                       | 31        | 8.09%   |
| Elan Microelectronics      | 19        | 4.96%   |
| STMicroelectronics         | 18        | 4.7%    |
| LighTuning Technology      | 10        | 2.61%   |
| Samsung Electronics        | 2         | 0.52%   |
| HOLTEK                     | 1         | 0.26%   |
| Focal-systems.Corp         | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 37        | 9.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 7.83%   |
| Shenzhen Goodix  FingerPrint Device                                        | 21        | 5.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 20        | 5.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.7%    |
| STMicroelectronics Fingerprint Reader                                      | 18        | 4.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 17        | 4.44%   |
| AuthenTec AES2810                                                          | 17        | 4.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 16        | 4.18%   |
| Validity Sensors VFS491                                                    | 15        | 3.92%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 3.92%   |
| Unknown                                                                    | 14        | 3.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.39%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.61%   |
| Synaptics  WBDI                                                            | 9         | 2.35%   |
| Elan ELAN:ARM-M4                                                           | 9         | 2.35%   |
| AuthenTec AES1600                                                          | 9         | 2.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.09%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.83%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.57%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.31%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.31%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.04%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.04%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.04%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.78%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.52%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.52%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.52%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.52%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 77        | 48.43%  |
| Alcor Micro                       | 26        | 16.35%  |
| O2 Micro                          | 24        | 15.09%  |
| Lenovo                            | 9         | 5.66%   |
| Upek                              | 7         | 4.4%    |
| Realtek Semiconductor             | 4         | 2.52%   |
| SCM Microsystems                  | 3         | 1.89%   |
| Yubico.com                        | 2         | 1.26%   |
| Advanced Card Systems             | 2         | 1.26%   |
| VASCO Data Security International | 1         | 0.63%   |
| Reiner SCT Kartensysteme          | 1         | 0.63%   |
| OmniKey                           | 1         | 0.63%   |
| Kobil Systems                     | 1         | 0.63%   |
| Fujitsu Siemens Computers         | 1         | 0.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 23.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 15.72%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 13.21%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 11.95%  |
| Broadcom 5880                                                                | 15        | 9.43%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 5.66%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.4%    |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 3.14%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.52%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.26%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.26%   |
| Broadcom 58200                                                               | 2         | 1.26%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.63%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.63%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.63%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.63%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.63%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.63%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.63%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.63%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3060      | 70.04%  |
| 1     | 1061      | 24.28%  |
| 2     | 225       | 5.15%   |
| 3     | 19        | 0.43%   |
| 4     | 3         | 0.07%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 396       | 25.9%   |
| Fingerprint reader       | 376       | 24.59%  |
| Net/wireless             | 262       | 17.14%  |
| Chipcard                 | 148       | 9.68%   |
| Multimedia controller    | 114       | 7.46%   |
| Modem                    | 41        | 2.68%   |
| Storage                  | 39        | 2.55%   |
| Communication controller | 38        | 2.49%   |
| Bluetooth                | 28        | 1.83%   |
| Sound                    | 17        | 1.11%   |
| Camera                   | 15        | 0.98%   |
| Unassigned class         | 13        | 0.85%   |
| Flash memory             | 11        | 0.72%   |
| Net/ethernet             | 7         | 0.46%   |
| Card reader              | 6         | 0.39%   |
| Network                  | 4         | 0.26%   |
| Dvb card                 | 4         | 0.26%   |
| Storage/nvme             | 3         | 0.2%    |
| Storage/ide              | 3         | 0.2%    |
| Storage/raid             | 2         | 0.13%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |

