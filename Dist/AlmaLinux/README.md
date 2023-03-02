AlmaLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for AlmaLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/AlmaLinux/Desktop/README.md) and [notebooks](/Dist/AlmaLinux/Notebook/README.md).

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

Total: 111

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | H12SSL-i                    | Server      | [3b0e50edda](https://linux-hardware.org/?probe=3b0e50edda) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6ccb40f64d](https://linux-hardware.org/?probe=6ccb40f64d) | Feb 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [126100b078](https://linux-hardware.org/?probe=126100b078) | Feb 25, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [fb42cba088](https://linux-hardware.org/?probe=fb42cba088) | Feb 25, 2023 |
| Google        | Kefka                       | Notebook    | [8142fbc91a](https://linux-hardware.org/?probe=8142fbc91a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6ecc72101c](https://linux-hardware.org/?probe=6ecc72101c) | Feb 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [59ec61666a](https://linux-hardware.org/?probe=59ec61666a) | Feb 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cf977da464](https://linux-hardware.org/?probe=cf977da464) | Feb 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [2a2dfe19fc](https://linux-hardware.org/?probe=2a2dfe19fc) | Feb 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0001e56a68](https://linux-hardware.org/?probe=0001e56a68) | Feb 17, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c913edda07](https://linux-hardware.org/?probe=c913edda07) | Feb 17, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [016e12b43e](https://linux-hardware.org/?probe=016e12b43e) | Feb 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [3e048e046a](https://linux-hardware.org/?probe=3e048e046a) | Feb 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [4599836936](https://linux-hardware.org/?probe=4599836936) | Feb 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [9a81107301](https://linux-hardware.org/?probe=9a81107301) | Feb 11, 2023 |
| HP            | 8455                        | Desktop     | [ffc8587d29](https://linux-hardware.org/?probe=ffc8587d29) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [84ba50b16d](https://linux-hardware.org/?probe=84ba50b16d) | Feb 08, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0593b2bac6](https://linux-hardware.org/?probe=0593b2bac6) | Feb 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ee7dbe4f81](https://linux-hardware.org/?probe=ee7dbe4f81) | Feb 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a019143fe9](https://linux-hardware.org/?probe=a019143fe9) | Feb 07, 2023 |
| AZW           | SER                         | Mini pc     | [dd0c654d95](https://linux-hardware.org/?probe=dd0c654d95) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [a0f53917f9](https://linux-hardware.org/?probe=a0f53917f9) | Feb 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [768696d7b8](https://linux-hardware.org/?probe=768696d7b8) | Feb 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [04a26e636e](https://linux-hardware.org/?probe=04a26e636e) | Feb 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6bb0e68672](https://linux-hardware.org/?probe=6bb0e68672) | Feb 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [5b505d5d7a](https://linux-hardware.org/?probe=5b505d5d7a) | Feb 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f6ad918c7e](https://linux-hardware.org/?probe=f6ad918c7e) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [21ce876854](https://linux-hardware.org/?probe=21ce876854) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [cca8d74416](https://linux-hardware.org/?probe=cca8d74416) | Feb 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [602482d070](https://linux-hardware.org/?probe=602482d070) | Feb 01, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f0884ec1aa](https://linux-hardware.org/?probe=f0884ec1aa) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [89430aeb82](https://linux-hardware.org/?probe=89430aeb82) | Jan 31, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [af3cf25119](https://linux-hardware.org/?probe=af3cf25119) | Jan 31, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6d079ed3ca](https://linux-hardware.org/?probe=6d079ed3ca) | Jan 30, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d81d33bda5](https://linux-hardware.org/?probe=d81d33bda5) | Jan 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [ec76a40223](https://linux-hardware.org/?probe=ec76a40223) | Jan 30, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e4289105c5](https://linux-hardware.org/?probe=e4289105c5) | Jan 30, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ee36c9d395](https://linux-hardware.org/?probe=ee36c9d395) | Jan 30, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [725c2a80f8](https://linux-hardware.org/?probe=725c2a80f8) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [091b3e37fb](https://linux-hardware.org/?probe=091b3e37fb) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [49654976af](https://linux-hardware.org/?probe=49654976af) | Jan 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [6b99585bc0](https://linux-hardware.org/?probe=6b99585bc0) | Jan 29, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [d41a70cbf5](https://linux-hardware.org/?probe=d41a70cbf5) | Jan 28, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [9fbcd4b714](https://linux-hardware.org/?probe=9fbcd4b714) | Jan 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [af868046e3](https://linux-hardware.org/?probe=af868046e3) | Jan 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [b9f3d19faa](https://linux-hardware.org/?probe=b9f3d19faa) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [df1811bf5d](https://linux-hardware.org/?probe=df1811bf5d) | Jan 26, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [7c026252d0](https://linux-hardware.org/?probe=7c026252d0) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [bd3f6fa130](https://linux-hardware.org/?probe=bd3f6fa130) | Jan 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [477f1a3aad](https://linux-hardware.org/?probe=477f1a3aad) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [71a9255bc8](https://linux-hardware.org/?probe=71a9255bc8) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [e327d1dea4](https://linux-hardware.org/?probe=e327d1dea4) | Jan 24, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [f62d0d9183](https://linux-hardware.org/?probe=f62d0d9183) | Jan 24, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [ed6204876e](https://linux-hardware.org/?probe=ed6204876e) | Jan 22, 2023 |
| HP            | Falco                       | Notebook    | [a52a8f8f4e](https://linux-hardware.org/?probe=a52a8f8f4e) | Jan 14, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dab9cdc1be](https://linux-hardware.org/?probe=dab9cdc1be) | Jan 11, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [2b4b7560b7](https://linux-hardware.org/?probe=2b4b7560b7) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [56758aeb6f](https://linux-hardware.org/?probe=56758aeb6f) | Jan 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ec3b130618](https://linux-hardware.org/?probe=ec3b130618) | Jan 07, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [891e0757ed](https://linux-hardware.org/?probe=891e0757ed) | Dec 31, 2022 |
| MSI           | A88X-G45 GAMING             | Desktop     | [bdb45edaad](https://linux-hardware.org/?probe=bdb45edaad) | Dec 31, 2022 |
| HP            | Falco                       | Notebook    | [61ce7c6739](https://linux-hardware.org/?probe=61ce7c6739) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [4571b799f0](https://linux-hardware.org/?probe=4571b799f0) | Dec 20, 2022 |
| Optimized ... | KVM                         | Desktop     | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [95d47d14cb](https://linux-hardware.org/?probe=95d47d14cb) | Dec 09, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3706f368de](https://linux-hardware.org/?probe=3706f368de) | Nov 24, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| ASUSTek       | Q170M2                      | Desktop     | [c62954095d](https://linux-hardware.org/?probe=c62954095d) | Nov 11, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [ef43d1f352](https://linux-hardware.org/?probe=ef43d1f352) | Nov 03, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| Acer          | TMP453-MG                   | Notebook    | [4d36d13ea9](https://linux-hardware.org/?probe=4d36d13ea9) | Oct 01, 2022 |
| Lenovo        | 1052 NOK                    | Desktop     | [28cd1416fe](https://linux-hardware.org/?probe=28cd1416fe) | Sep 22, 2022 |
| Acer          | TravelMate 5735Z            | Notebook    | [b920fce554](https://linux-hardware.org/?probe=b920fce554) | Sep 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7e56cce9c8](https://linux-hardware.org/?probe=7e56cce9c8) | Sep 17, 2022 |
| HP            | Falco                       | Notebook    | [5fa86b77d6](https://linux-hardware.org/?probe=5fa86b77d6) | Sep 17, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [c01403937e](https://linux-hardware.org/?probe=c01403937e) | Sep 08, 2022 |
| HP            | ENVY dv6                    | Notebook    | [e7bc07047b](https://linux-hardware.org/?probe=e7bc07047b) | Aug 24, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [82b34535ae](https://linux-hardware.org/?probe=82b34535ae) | Jul 06, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0dc125da55](https://linux-hardware.org/?probe=0dc125da55) | Jul 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d6adb170de](https://linux-hardware.org/?probe=d6adb170de) | Jun 25, 2022 |
| Google        | Kohaku                      | Notebook    | [f43841c5e0](https://linux-hardware.org/?probe=f43841c5e0) | Jun 08, 2022 |
| Google        | Kohaku                      | Notebook    | [740a608274](https://linux-hardware.org/?probe=740a608274) | Jun 08, 2022 |
| Lenovo        | ThinkPad T440s 20ARS32P0... | Notebook    | [100b65a86d](https://linux-hardware.org/?probe=100b65a86d) | Jun 04, 2022 |
| Dell          | 060K5C A06                  | Server      | [c8be539d80](https://linux-hardware.org/?probe=c8be539d80) | May 14, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [2fecc1fd76](https://linux-hardware.org/?probe=2fecc1fd76) | Apr 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5ac68bc542](https://linux-hardware.org/?probe=5ac68bc542) | Mar 16, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [a517886d4d](https://linux-hardware.org/?probe=a517886d4d) | Feb 10, 2022 |
| Dell          | 0R4CNN A02                  | Server      | [c701d3a15f](https://linux-hardware.org/?probe=c701d3a15f) | Feb 07, 2022 |
| Intel         | powered classmate PC        | Notebook    | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | Notebook    | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c28c41bdd4](https://linux-hardware.org/?probe=c28c41bdd4) | Nov 05, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [53ac57fbea](https://linux-hardware.org/?probe=53ac57fbea) | Oct 26, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [2c9cec7881](https://linux-hardware.org/?probe=2c9cec7881) | Oct 01, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [1a59499d3a](https://linux-hardware.org/?probe=1a59499d3a) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [95a2b3a95d](https://linux-hardware.org/?probe=95a2b3a95d) | Aug 27, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [972f935578](https://linux-hardware.org/?probe=972f935578) | Aug 23, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [37e72494a5](https://linux-hardware.org/?probe=37e72494a5) | Jul 29, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [cdf0f4017c](https://linux-hardware.org/?probe=cdf0f4017c) | Jul 16, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [9044b57593](https://linux-hardware.org/?probe=9044b57593) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [21a6135eda](https://linux-hardware.org/?probe=21a6135eda) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e5a30a171e](https://linux-hardware.org/?probe=e5a30a171e) | Jun 08, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [043878564d](https://linux-hardware.org/?probe=043878564d) | Jun 08, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [84fa76eb2f](https://linux-hardware.org/?probe=84fa76eb2f) | Apr 20, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [d49edb76fa](https://linux-hardware.org/?probe=d49edb76fa) | Apr 15, 2021 |
| Dell          | Inspiron 3185               | Notebook    | [15b8da5bc1](https://linux-hardware.org/?probe=15b8da5bc1) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [f0791eb42d](https://linux-hardware.org/?probe=f0791eb42d) | Mar 30, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b7fd559b13](https://linux-hardware.org/?probe=b7fd559b13) | Mar 24, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8810309035](https://linux-hardware.org/?probe=8810309035) | Mar 24, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| AlmaLinux 9.1 | 13        | 23.21%  |
| AlmaLinux 8.6 | 10        | 17.86%  |
| AlmaLinux 9.0 | 9         | 16.07%  |
| AlmaLinux 8.4 | 9         | 16.07%  |
| AlmaLinux 8.7 | 8         | 14.29%  |
| AlmaLinux 8.3 | 4         | 7.14%   |
| AlmaLinux 8.5 | 3         | 5.36%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 54        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64   | 8         | 14.55%  |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 10.91%  |
| 5.14.0-162.12.1.el9_1.x86_64  | 5         | 9.09%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 5.45%   |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 5.45%   |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 5.45%   |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 3.64%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 3.64%   |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 3.64%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 3.64%   |
| 4.18.0-305.el8.x86_64         | 2         | 3.64%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 3.64%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 3.64%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 1.82%   |
| 5.15.45-v8.1.el8              | 1         | 1.82%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 1.82%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 1.82%   |
| 5.10.60-v8.1.el8              | 1         | 1.82%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 1         | 1.82%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 1.82%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 1.82%   |
| 4.18.0-348.el8.x86_64         | 1         | 1.82%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 1.82%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 1         | 1.82%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 1         | 1.82%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 1         | 1.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 29        | 53.7%   |
| 5.14.0  | 22        | 40.74%  |
| 5.4.175 | 1         | 1.85%   |
| 5.15.45 | 1         | 1.85%   |
| 5.10.60 | 1         | 1.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 29        | 53.7%   |
| 5.14    | 22        | 40.74%  |
| 5.4     | 1         | 1.85%   |
| 5.15    | 1         | 1.85%   |
| 5.10    | 1         | 1.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 51        | 94.44%  |
| aarch64 | 3         | 5.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 33        | 61.11%  |
| Unknown       | 13        | 24.07%  |
| KDE5          | 3         | 5.56%   |
| XFCE          | 2         | 3.7%    |
| MATE          | 2         | 3.7%    |
| GNOME Classic | 1         | 1.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 26        | 48.15%  |
| X11     | 20        | 37.04%  |
| Unknown | 5         | 9.26%   |
| Tty     | 3         | 5.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 36        | 66.67%  |
| GDM     | 14        | 25.93%  |
| SDDM    | 2         | 3.7%    |
| LightDM | 2         | 3.7%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 27        | 48.21%  |
| en_GB   | 7         | 12.5%   |
| de_DE   | 7         | 12.5%   |
| en_CA   | 3         | 5.36%   |
| fr_FR   | 2         | 3.57%   |
| C       | 2         | 3.57%   |
| Unknown | 2         | 3.57%   |
| uk_UA   | 1         | 1.79%   |
| ru_UA   | 1         | 1.79%   |
| ru_RU   | 1         | 1.79%   |
| es_VE   | 1         | 1.79%   |
| es_ES   | 1         | 1.79%   |
| da_DK   | 1         | 1.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 34        | 61.82%  |
| BIOS | 21        | 38.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 42        | 77.78%  |
| Ext4 | 12        | 22.22%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 28        | 51.85%  |
| Unknown | 20        | 37.04%  |
| MBR     | 6         | 11.11%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 81.48%  |
| Yes       | 10        | 18.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 81.48%  |
| Yes       | 10        | 18.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 13        | 24.07%  |
| Hewlett-Packard         | 11        | 20.37%  |
| Dell                    | 5         | 9.26%   |
| Gigabyte Technology     | 4         | 7.41%   |
| ASUSTek Computer        | 4         | 7.41%   |
| Supermicro              | 2         | 3.7%    |
| Raspberry Pi Foundation | 2         | 3.7%    |
| Intel                   | 2         | 3.7%    |
| Google                  | 2         | 3.7%    |
| ASRock                  | 2         | 3.7%    |
| Acer                    | 2         | 3.7%    |
| Toshiba                 | 1         | 1.85%   |
| Optimized Hosting       | 1         | 1.85%   |
| MSI                     | 1         | 1.85%   |
| AZW                     | 1         | 1.85%   |
| ASRockRack              | 1         | 1.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 3.7%    |
| Toshiba Satellite L50-C              | 1         | 1.85%   |
| Supermicro Super Server              | 1         | 1.85%   |
| Supermicro motherboard-H12 Series    | 1         | 1.85%   |
| Optimized Hosting KVM                | 1         | 1.85%   |
| MSI MS-7900                          | 1         | 1.85%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.85%   |
| Lenovo V14-ARE 82DQ                  | 1         | 1.85%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 1.85%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 1.85%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 1.85%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 1.85%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 1.85%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 1         | 1.85%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 1.85%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 1.85%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.85%   |
| Lenovo H520S 10093                   | 1         | 1.85%   |
| Lenovo B50-30 20382                  | 1         | 1.85%   |
| Intel powered classmate PC           | 1         | 1.85%   |
| Intel NUC8i5BEH                      | 1         | 1.85%   |
| HP Z620 Workstation                  | 1         | 1.85%   |
| HP Z600 Workstation                  | 1         | 1.85%   |
| HP Z2 Tower G4 Workstation           | 1         | 1.85%   |
| HP ProLiant DL360p Gen8              | 1         | 1.85%   |
| HP Laptop 17-cp0xxx                  | 1         | 1.85%   |
| HP Laptop 15-ef1xxx                  | 1         | 1.85%   |
| HP Falco                             | 1         | 1.85%   |
| HP ENVY dv6                          | 1         | 1.85%   |
| HP EliteBook 8570w                   | 1         | 1.85%   |
| HP EliteBook 850 G8 Notebook PC      | 1         | 1.85%   |
| HP EliteBook 8470p                   | 1         | 1.85%   |
| Google Kohaku                        | 1         | 1.85%   |
| Google Kefka                         | 1         | 1.85%   |
| Gigabyte Z690 GAMING X DDR4          | 1         | 1.85%   |
| Gigabyte Z590 AORUS PRO AX           | 1         | 1.85%   |
| Gigabyte MP32-AR1-00                 | 1         | 1.85%   |
| Gigabyte H81M-D2V                    | 1         | 1.85%   |
| Dell XPS 13 9365                     | 1         | 1.85%   |
| Dell Precision 7920 Tower            | 1         | 1.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo IdeaPad             | 3         | 5.56%   |
| HP EliteBook               | 3         | 5.56%   |
| RPi Raspberry              | 2         | 3.7%    |
| Lenovo ThinkPad            | 2         | 3.7%    |
| Lenovo Legion              | 2         | 3.7%    |
| HP Laptop                  | 2         | 3.7%    |
| Toshiba Satellite          | 1         | 1.85%   |
| Supermicro Super           | 1         | 1.85%   |
| Supermicro motherboard-H12 | 1         | 1.85%   |
| Optimized Hosting KVM      | 1         | 1.85%   |
| MSI MS-7900                | 1         | 1.85%   |
| Lenovo Yoga                | 1         | 1.85%   |
| Lenovo V14-ARE             | 1         | 1.85%   |
| Lenovo ThinkStation        | 1         | 1.85%   |
| Lenovo IdeaPadFlex         | 1         | 1.85%   |
| Lenovo H520S               | 1         | 1.85%   |
| Lenovo B50-30              | 1         | 1.85%   |
| Intel powered              | 1         | 1.85%   |
| Intel NUC8i5BEH            | 1         | 1.85%   |
| HP Z620                    | 1         | 1.85%   |
| HP Z600                    | 1         | 1.85%   |
| HP Z2                      | 1         | 1.85%   |
| HP ProLiant                | 1         | 1.85%   |
| HP Falco                   | 1         | 1.85%   |
| HP ENVY                    | 1         | 1.85%   |
| Google Kohaku              | 1         | 1.85%   |
| Google Kefka               | 1         | 1.85%   |
| Gigabyte Z690              | 1         | 1.85%   |
| Gigabyte Z590              | 1         | 1.85%   |
| Gigabyte MP32-AR1-00       | 1         | 1.85%   |
| Gigabyte H81M-D2V          | 1         | 1.85%   |
| Dell XPS                   | 1         | 1.85%   |
| Dell Precision             | 1         | 1.85%   |
| Dell PowerEdge             | 1         | 1.85%   |
| Dell Latitude              | 1         | 1.85%   |
| Dell Inspiron              | 1         | 1.85%   |
| AZW SER                    | 1         | 1.85%   |
| ASUS TUF                   | 1         | 1.85%   |
| ASUS Q170M2                | 1         | 1.85%   |
| ASUS M5A78L-M              | 1         | 1.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 10        | 18.52%  |
| 2012    | 8         | 14.81%  |
| 2022    | 6         | 11.11%  |
| 2019    | 5         | 9.26%   |
| 2021    | 4         | 7.41%   |
| 2018    | 4         | 7.41%   |
| 2014    | 4         | 7.41%   |
| 2011    | 3         | 5.56%   |
| 2015    | 2         | 3.7%    |
| 2013    | 2         | 3.7%    |
| 2010    | 2         | 3.7%    |
| Unknown | 2         | 3.7%    |
| 2016    | 1         | 1.85%   |
| 2009    | 1         | 1.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 26        | 48.15%  |
| Desktop        | 16        | 29.63%  |
| Server         | 6         | 11.11%  |
| System on chip | 2         | 3.7%    |
| Convertible    | 2         | 3.7%    |
| Mini pc        | 2         | 3.7%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 47        | 87.04%  |
| Enabled  | 7         | 12.96%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 51        | 94.44%  |
| Yes  | 3         | 5.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 15        | 27.78%  |
| 8.01-16.0       | 11        | 20.37%  |
| 64.01-256.0     | 7         | 12.96%  |
| 16.01-24.0      | 6         | 11.11%  |
| 3.01-4.0        | 5         | 9.26%   |
| More than 256.0 | 3         | 5.56%   |
| 32.01-64.0      | 2         | 3.7%    |
| 1.01-2.0        | 2         | 3.7%    |
| 0.51-1.0        | 2         | 3.7%    |
| 24.01-32.0      | 1         | 1.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 15        | 26.32%  |
| 1.01-2.0    | 12        | 21.05%  |
| 3.01-4.0    | 10        | 17.54%  |
| 4.01-8.0    | 6         | 10.53%  |
| 8.01-16.0   | 3         | 5.26%   |
| 0.51-1.0    | 3         | 5.26%   |
| 32.01-64.0  | 2         | 3.51%   |
| 16.01-24.0  | 2         | 3.51%   |
| 0.01-0.5    | 2         | 3.51%   |
| 24.01-32.0  | 1         | 1.75%   |
| 64.01-256.0 | 1         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 25        | 45.45%  |
| 2      | 18        | 32.73%  |
| 4      | 4         | 7.27%   |
| 3      | 4         | 7.27%   |
| 11     | 1         | 1.82%   |
| 6      | 1         | 1.82%   |
| 5      | 1         | 1.82%   |
| 0      | 1         | 1.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 40        | 74.07%  |
| Yes       | 14        | 25.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 43        | 79.63%  |
| No        | 11        | 20.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 62.96%  |
| No        | 20        | 37.04%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 32        | 59.26%  |
| No        | 22        | 40.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 15        | 27.78%  |
| Germany      | 8         | 14.81%  |
| UK           | 4         | 7.41%   |
| France       | 4         | 7.41%   |
| Canada       | 4         | 7.41%   |
| Ukraine      | 2         | 3.7%    |
| Spain        | 2         | 3.7%    |
| Russia       | 2         | 3.7%    |
| Netherlands  | 2         | 3.7%    |
| Venezuela    | 1         | 1.85%   |
| Switzerland  | 1         | 1.85%   |
| Sweden       | 1         | 1.85%   |
| South Africa | 1         | 1.85%   |
| Puerto Rico  | 1         | 1.85%   |
| Pakistan     | 1         | 1.85%   |
| Kazakhstan   | 1         | 1.85%   |
| India        | 1         | 1.85%   |
| Greenland    | 1         | 1.85%   |
| Finland      | 1         | 1.85%   |
| Bulgaria     | 1         | 1.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Hamburg       | 3         | 5.45%   |
| Queens        | 2         | 3.64%   |
| Dallas        | 2         | 3.64%   |
| Zaporizhzhia  | 1         | 1.82%   |
| Winterswijk   | 1         | 1.82%   |
| Uppsala       | 1         | 1.82%   |
| Tuusula       | 1         | 1.82%   |
| Tampa         | 1         | 1.82%   |
| Strasbourg    | 1         | 1.82%   |
| Stadtilm      | 1         | 1.82%   |
| St. Paul      | 1         | 1.82%   |
| Sofia         | 1         | 1.82%   |
| Shimanovsk    | 1         | 1.82%   |
| San Diego     | 1         | 1.82%   |
| Rothwell      | 1         | 1.82%   |
| Regina        | 1         | 1.82%   |
| Parla         | 1         | 1.82%   |
| Paris         | 1         | 1.82%   |
| Moscow        | 1         | 1.82%   |
| Mangalore     | 1         | 1.82%   |
| Los Angeles   | 1         | 1.82%   |
| London        | 1         | 1.82%   |
| Liverpool     | 1         | 1.82%   |
| Lille         | 1         | 1.82%   |
| Lawrence      | 1         | 1.82%   |
| Land O' Lakes | 1         | 1.82%   |
| Lahore        | 1         | 1.82%   |
| Kyiv          | 1         | 1.82%   |
| Kitimat       | 1         | 1.82%   |
| Kennewick     | 1         | 1.82%   |
| Johannesburg  | 1         | 1.82%   |
| Ilulissat     | 1         | 1.82%   |
| Guglingen     | 1         | 1.82%   |
| Guanare       | 1         | 1.82%   |
| Groningen     | 1         | 1.82%   |
| Frankenthal   | 1         | 1.82%   |
| Essen         | 1         | 1.82%   |
| East Orange   | 1         | 1.82%   |
| Deeside       | 1         | 1.82%   |
| Columbia      | 1         | 1.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 11        | 13     | 13.92%  |
| Seagate                     | 10        | 18     | 12.66%  |
| Samsung Electronics         | 9         | 13     | 11.39%  |
| Kingston                    | 5         | 6      | 6.33%   |
| Unknown                     | 4         | 6      | 5.06%   |
| SK hynix                    | 4         | 4      | 5.06%   |
| Kingston Technology Company | 3         | 7      | 3.8%    |
| Toshiba                     | 2         | 2      | 2.53%   |
| Netac                       | 2         | 2      | 2.53%   |
| Micron Technology           | 2         | 2      | 2.53%   |
| LITEONIT                    | 2         | 4      | 2.53%   |
| Intel                       | 2         | 2      | 2.53%   |
| Hewlett-Packard             | 2         | 9      | 2.53%   |
| Dell                        | 2         | 3      | 2.53%   |
| Crucial                     | 2         | 4      | 2.53%   |
| Union Memory                | 1         | 1      | 1.27%   |
| Transcend                   | 1         | 1      | 1.27%   |
| Team                        | 1         | 1      | 1.27%   |
| SSSTC                       | 1         | 1      | 1.27%   |
| Silicon Motion              | 1         | 4      | 1.27%   |
| Sandisk                     | 1         | 1      | 1.27%   |
| QEMU                        | 1         | 1      | 1.27%   |
| Plextor                     | 1         | 1      | 1.27%   |
| LITEON                      | 1         | 1      | 1.27%   |
| KIOXIA                      | 1         | 1      | 1.27%   |
| Hitachi                     | 1         | 1      | 1.27%   |
| HGST                        | 1         | 1      | 1.27%   |
| EMTEC                       | 1         | 2      | 1.27%   |
| DELLBOSS                    | 1         | 1      | 1.27%   |
| China                       | 1         | 1      | 1.27%   |
| ASMT                        | 1         | 2      | 1.27%   |
| A-DATA Technology           | 1         | 1      | 1.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                            | 2         | 2.27%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 2.27%   |
| Kingston Company KC2000 NVMe SSD 1TB              | 2         | 2.27%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 2.27%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 1.14%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 1.14%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 1.14%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1         | 1.14%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 1.14%   |
| WDC WD10EZEX-75M2NA0 1TB                          | 1         | 1.14%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 1.14%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1.14%   |
| Unknown SD64G  64GB                               | 1         | 1.14%   |
| Unknown SD/MMC/MS PRO 16GB                        | 1         | 1.14%   |
| Unknown MMC Card  16GB                            | 1         | 1.14%   |
| Unknown EC2QT  64GB                               | 1         | 1.14%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB           | 1         | 1.14%   |
| Transcend TS256GMTE220S 256GB                     | 1         | 1.14%   |
| Toshiba MK6475GSX 640GB                           | 1         | 1.14%   |
| Toshiba DT01ACA100 1TB                            | 1         | 1.14%   |
| Team T253X1480G 480GB SSD                         | 1         | 1.14%   |
| SSSTC CL1-3D256 256GB                             | 1         | 1.14%   |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1         | 1.14%   |
| SK hynix PC300 NVMe Solid State Drive 256GB       | 1         | 1.14%   |
| SK hynix NVMe SSD Drive 256GB                     | 1         | 1.14%   |
| SK hynix BC511 NVMe 256GB                         | 1         | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1         | 1.14%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB       | 1         | 1.14%   |
| Seagate ST4000NC001-1FS168 4TB                    | 1         | 1.14%   |
| Seagate ST4000DM000-1F2168 4TB                    | 1         | 1.14%   |
| Seagate ST31000528AS 1TB                          | 1         | 1.14%   |
| Seagate ST3000DM001-1CH166 3TB                    | 1         | 1.14%   |
| Seagate ST250LM004 HN-M250MBB 250GB               | 1         | 1.14%   |
| Seagate ST2000NM012A-2MP130 2TB                   | 1         | 1.14%   |
| Seagate ST2000LM015-2E8174 2TB                    | 1         | 1.14%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 1         | 1.14%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1         | 1.14%   |
| Seagate ST2000DL003-9VT166 2TB                    | 1         | 1.14%   |
| Seagate ST1000NM0033-9ZM173 1TB                   | 1         | 1.14%   |
| Seagate ST1000DM003-9YN162 1TB                    | 1         | 1.14%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 10        | 18     | 37.04%  |
| WDC             | 8         | 8      | 29.63%  |
| Toshiba         | 2         | 2      | 7.41%   |
| Unknown         | 1         | 2      | 3.7%    |
| QEMU            | 1         | 1      | 3.7%    |
| Hitachi         | 1         | 1      | 3.7%    |
| HGST            | 1         | 1      | 3.7%    |
| Hewlett-Packard | 1         | 8      | 3.7%    |
| DELLBOSS        | 1         | 1      | 3.7%    |
| ASMT            | 1         | 2      | 3.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 20%     |
| Samsung Electronics | 3         | 3      | 12%     |
| Netac               | 2         | 2      | 8%      |
| LITEONIT            | 2         | 4      | 8%      |
| Intel               | 2         | 2      | 8%      |
| WDC                 | 1         | 3      | 4%      |
| Team                | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Plextor             | 1         | 1      | 4%      |
| Micron Technology   | 1         | 1      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| Hewlett-Packard     | 1         | 1      | 4%      |
| Dell                | 1         | 2      | 4%      |
| Crucial             | 1         | 2      | 4%      |
| China               | 1         | 1      | 4%      |
| A-DATA Technology   | 1         | 1      | 4%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 25        | 44     | 32.47%  |
| NVMe    | 24        | 36     | 31.17%  |
| SSD     | 24        | 31     | 31.17%  |
| MMC     | 3         | 4      | 3.9%    |
| Unknown | 1         | 2      | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 39        | 69     | 55.71%  |
| NVMe | 24        | 36     | 34.29%  |
| SAS  | 4         | 8      | 5.71%   |
| MMC  | 3         | 4      | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 26        | 32     | 49.06%  |
| 0.51-1.0   | 15        | 18     | 28.3%   |
| 1.01-2.0   | 5         | 10     | 9.43%   |
| 3.01-4.0   | 3         | 3      | 5.66%   |
| 2.01-3.0   | 2         | 3      | 3.77%   |
| 4.01-10.0  | 2         | 9      | 3.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 28.57%  |
| 251-500        | 9         | 16.07%  |
| 501-1000       | 7         | 12.5%   |
| More than 3000 | 6         | 10.71%  |
| 51-100         | 5         | 8.93%   |
| Unknown        | 4         | 7.14%   |
| 1-20           | 3         | 5.36%   |
| 21-50          | 2         | 3.57%   |
| 2001-3000      | 2         | 3.57%   |
| 1001-2000      | 2         | 3.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 23        | 39.66%  |
| 21-50          | 11        | 18.97%  |
| 101-250        | 7         | 12.07%  |
| 51-100         | 6         | 10.34%  |
| Unknown        | 4         | 6.9%    |
| 251-500        | 3         | 5.17%   |
| More than 3000 | 2         | 3.45%   |
| 2001-3000      | 1         | 1.72%   |
| 501-1000       | 1         | 1.72%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD20EARS-00J2GB0 2TB         | 1         | 1      | 33.33%  |
| SK hynix SH920 2.5 7MM 256GB SSD | 1         | 1      | 33.33%  |
| LITEONIT LSS-16L6G-HP 16GB SSD   | 1         | 3      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 33.33%  |
| SK hynix | 1         | 1      | 33.33%  |
| LITEONIT | 1         | 3      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 4      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Works    | 30        | 65     | 49.18%  |
| Detected | 28        | 47     | 45.9%   |
| Malfunc  | 3         | 5      | 4.92%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 32        | 43.84%  |
| AMD                            | 14        | 19.18%  |
| Samsung Electronics            | 7         | 9.59%   |
| Kingston Technology Company    | 4         | 5.48%   |
| Union Memory (Shenzhen)        | 2         | 2.74%   |
| SK hynix                       | 2         | 2.74%   |
| Silicon Motion                 | 2         | 2.74%   |
| SanDisk                        | 2         | 2.74%   |
| Toshiba America Info Systems   | 1         | 1.37%   |
| Solid State Storage Technology | 1         | 1.37%   |
| Red Hat                        | 1         | 1.37%   |
| Micron/Crucial Technology      | 1         | 1.37%   |
| Micron Technology              | 1         | 1.37%   |
| Marvell Technology Group       | 1         | 1.37%   |
| Hewlett-Packard                | 1         | 1.37%   |
| Broadcom / LSI                 | 1         | 1.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 11        | 13.75%  |
| Samsung NVMe SSD Controller 980                                               | 3         | 3.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 3.75%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 3.75%   |
| AMD 400 Series Chipset SATA Controller                                        | 3         | 3.75%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 2.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 2         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 2         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 2         | 2.5%    |
| Kingston Company KC2000 NVMe SSD                                              | 2         | 2.5%    |
| Intel SATA Controller [RAID mode]                                             | 2         | 2.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.5%    |
| Intel C600/X79 series chipset SATA RAID Controller                            | 2         | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.5%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 2.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.5%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 1.25%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 1.25%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 1.25%   |
| SK hynix BC511                                                                | 1         | 1.25%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.25%   |
| SanDisk Non-Volatile memory controller                                        | 1         | 1.25%   |
| Red Hat Virtio SCSI                                                           | 1         | 1.25%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 1.25%   |
| Micron Non-Volatile memory controller                                         | 1         | 1.25%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 1.25%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.25%   |
| Kingston Company A2000 NVMe SSD                                               | 1         | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 1.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.25%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                      | 1         | 1.25%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.25%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.25%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 1         | 1.25%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1         | 1.25%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 1         | 1.25%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1         | 1.25%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                      | 1         | 1.25%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 37        | 48.68%  |
| NVMe | 24        | 31.58%  |
| RAID | 8         | 10.53%  |
| IDE  | 5         | 6.58%   |
| SAS  | 1         | 1.32%   |
| SCSI | 1         | 1.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 35        | 64.81%  |
| AMD    | 16        | 29.63%  |
| ARM    | 3         | 5.56%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 5.56%   |
| ARM Processor                                 | 3         | 5.56%   |
| AMD EPYC 7282 16-Core Processor               | 2         | 3.7%    |
| Intel Xeon W-1350 @ 3.30GHz                   | 1         | 1.85%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz           | 1         | 1.85%   |
| Intel Xeon E-2144G CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Xeon CPU X5550 @ 2.67GHz                | 1         | 1.85%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz           | 1         | 1.85%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz            | 1         | 1.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 1.85%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 1.85%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 1.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i7-3840QM CPU @ 2.80GHz            | 1         | 1.85%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.85%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz              | 1         | 1.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.85%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.85%   |
| Intel Core i5-10400F CPU @ 2.90GHz            | 1         | 1.85%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1.85%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 1.85%   |
| Intel Core i3-2130 CPU @ 3.40GHz              | 1         | 1.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 1         | 1.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 1         | 1.85%   |
| Intel Celeron 2955U @ 1.40GHz                 | 1         | 1.85%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 1         | 1.85%   |
| Intel 12th Gen Core i7-12700KF                | 1         | 1.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 1.85%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz        | 1         | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1         | 1.85%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 1         | 1.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.85%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 1         | 1.85%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 1         | 1.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 1         | 1.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 18.52%  |
| Other                   | 8         | 14.81%  |
| Intel Xeon              | 5         | 9.26%   |
| Intel Core i7           | 5         | 9.26%   |
| Intel Core i3           | 5         | 9.26%   |
| AMD EPYC                | 4         | 7.41%   |
| AMD Ryzen 5             | 3         | 5.56%   |
| Intel Celeron           | 2         | 3.7%    |
| AMD Ryzen 9             | 2         | 3.7%    |
| AMD Ryzen 7             | 2         | 3.7%    |
| Intel Xeon Gold         | 1         | 1.85%   |
| Intel Pentium Dual-Core | 1         | 1.85%   |
| Intel Pentium           | 1         | 1.85%   |
| Intel Atom              | 1         | 1.85%   |
| AMD Ryzen 3             | 1         | 1.85%   |
| AMD FX                  | 1         | 1.85%   |
| AMD A6                  | 1         | 1.85%   |
| AMD A10                 | 1         | 1.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 17        | 31.48%  |
| 2       | 17        | 31.48%  |
| 6       | 6         | 11.11%  |
| 16      | 4         | 7.41%   |
| 12      | 3         | 5.56%   |
| Unknown | 2         | 3.7%    |
| 80      | 1         | 1.85%   |
| 48      | 1         | 1.85%   |
| 24      | 1         | 1.85%   |
| 8       | 1         | 1.85%   |
| 1       | 1         | 1.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 48        | 88.89%  |
| 2       | 3         | 5.56%   |
| Unknown | 2         | 3.7%    |
| 4       | 1         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 43        | 79.63%  |
| 1       | 9         | 16.67%  |
| Unknown | 2         | 3.7%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 51        | 94.44%  |
| Unknown        | 3         | 5.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 10        | 18.18%  |
| 0x806ec    | 4         | 7.27%   |
| 0x306a9    | 4         | 7.27%   |
| 0x40651    | 3         | 5.45%   |
| 0xa0671    | 2         | 3.64%   |
| 0x906ea    | 2         | 3.64%   |
| 0x806c1    | 2         | 3.64%   |
| 0x08701021 | 2         | 3.64%   |
| 0xa0655    | 1         | 1.82%   |
| 0xa0652    | 1         | 1.82%   |
| 0x906e9    | 1         | 1.82%   |
| 0x90672    | 1         | 1.82%   |
| 0x806e9    | 1         | 1.82%   |
| 0x50657    | 1         | 1.82%   |
| 0x406e3    | 1         | 1.82%   |
| 0x406c4    | 1         | 1.82%   |
| 0x306e4    | 1         | 1.82%   |
| 0x306c3    | 1         | 1.82%   |
| 0x30678    | 1         | 1.82%   |
| 0x206a7    | 1         | 1.82%   |
| 0x20655    | 1         | 1.82%   |
| 0x106ca    | 1         | 1.82%   |
| 0x106a5    | 1         | 1.82%   |
| 0x1067a    | 1         | 1.82%   |
| 0x08608103 | 1         | 1.82%   |
| 0x08600106 | 1         | 1.82%   |
| 0x08301055 | 1         | 1.82%   |
| 0x08108109 | 1         | 1.82%   |
| 0x08108102 | 1         | 1.82%   |
| 0x0810100b | 1         | 1.82%   |
| 0x06006705 | 1         | 1.82%   |
| 0x06006704 | 1         | 1.82%   |
| 0x06003106 | 1         | 1.82%   |
| 0x06000852 | 1         | 1.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 9         | 16.67%  |
| Zen 2            | 8         | 14.81%  |
| IvyBridge        | 5         | 9.26%   |
| Haswell          | 4         | 7.41%   |
| Unknown          | 4         | 7.41%   |
| Zen+             | 2         | 3.7%    |
| TigerLake        | 2         | 3.7%    |
| Skylake          | 2         | 3.7%    |
| Silvermont       | 2         | 3.7%    |
| SandyBridge      | 2         | 3.7%    |
| Icelake          | 2         | 3.7%    |
| Excavator        | 2         | 3.7%    |
| CometLake        | 2         | 3.7%    |
| Zen              | 1         | 1.85%   |
| Westmere         | 1         | 1.85%   |
| Steamroller      | 1         | 1.85%   |
| Piledriver       | 1         | 1.85%   |
| Penryn           | 1         | 1.85%   |
| Nehalem          | 1         | 1.85%   |
| Bonnell          | 1         | 1.85%   |
| Alderlake Hybrid | 1         | 1.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 25        | 45.45%  |
| AMD                        | 12        | 21.82%  |
| Nvidia                     | 11        | 20%     |
| ASPEED Technology          | 4         | 7.27%   |
| Matrox Electronics Systems | 2         | 3.64%   |
| Red Hat                    | 1         | 1.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 7.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 5.45%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 2         | 3.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.64%   |
| Red Hat QXL paravirtual graphic card                                                     | 1         | 1.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.82%   |
| Nvidia GP107GL [Quadro P620]                                                             | 1         | 1.82%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 1.82%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 1.82%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 1.82%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.82%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.82%   |
| Nvidia GA102GL [RTX A6000]                                                               | 1         | 1.82%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.82%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.82%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                               | 1         | 1.82%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.82%   |
| Intel HD Graphics 615                                                                    | 1         | 1.82%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.82%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 1.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.82%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 1.82%   |
| AMD RS780L [Radeon 3000]                                                                 | 1         | 1.82%   |
| AMD Renoir                                                                               | 1         | 1.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 1.82%   |
| AMD Lucienne                                                                             | 1         | 1.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 40.74%  |
| 1 x AMD        | 12        | 22.22%  |
| 1 x Nvidia     | 8         | 14.81%  |
| 1 x ASPEED     | 4         | 7.41%   |
| Intel + Nvidia | 3         | 5.56%   |
| Other          | 2         | 3.7%    |
| 1 x Matrox     | 2         | 3.7%    |
| 1 x Red Hat    | 1         | 1.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 41        | 75.93%  |
| Unknown     | 9         | 16.67%  |
| Proprietary | 4         | 7.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 66.67%  |
| 0.01-0.5   | 6         | 11.11%  |
| 1.01-2.0   | 5         | 9.26%   |
| 7.01-8.0   | 3         | 5.56%   |
| 32.01-64.0 | 1         | 1.85%   |
| 5.01-6.0   | 1         | 1.85%   |
| 3.01-4.0   | 1         | 1.85%   |
| 0.51-1.0   | 1         | 1.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 7         | 15.91%  |
| Samsung Electronics     | 6         | 13.64%  |
| LG Display              | 6         | 13.64%  |
| Chimei Innolux          | 3         | 6.82%   |
| Sharp                   | 2         | 4.55%   |
| InfoVision              | 2         | 4.55%   |
| Goldstar                | 2         | 4.55%   |
| Dell                    | 2         | 4.55%   |
| BOE                     | 2         | 4.55%   |
| BenQ                    | 2         | 4.55%   |
| ViewSonic               | 1         | 2.27%   |
| TopView                 | 1         | 2.27%   |
| STD                     | 1         | 2.27%   |
| Seiki                   | 1         | 2.27%   |
| Philips                 | 1         | 2.27%   |
| PANDA                   | 1         | 2.27%   |
| Medion                  | 1         | 2.27%   |
| Lenovo                  | 1         | 2.27%   |
| Chi Mei Optoelectronics | 1         | 2.27%   |
| AOC                     | 1         | 2.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 2         | 4.44%   |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch               | 1         | 2.22%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                      | 1         | 2.22%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                        | 1         | 2.22%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch                  | 1         | 2.22%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 2.22%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 2.22%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch     | 1         | 2.22%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch        | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 2.22%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 2.22%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 2.22%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                        | 1         | 2.22%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 2.22%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                    | 1         | 2.22%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 2.22%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.22%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 2.22%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 2.22%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 2.22%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 2.22%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 1         | 2.22%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                    | 1         | 2.22%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                         | 1         | 2.22%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 1         | 2.22%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 2.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 2.22%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 2.22%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 1         | 2.22%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 2.22%   |
| AU Optronics LCD Monitor AUOF992 1920x1080 382x215mm 17.3-inch           | 1         | 2.22%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 1         | 2.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 25        | 55.56%  |
| 1366x768 (WXGA)   | 9         | 20%     |
| 1280x1024 (SXGA)  | 3         | 6.67%   |
| 3840x2160 (4K)    | 2         | 4.44%   |
| 3200x1800 (QHD+)  | 1         | 2.22%   |
| 2560x1440 (QHD)   | 1         | 2.22%   |
| 2560x1080         | 1         | 2.22%   |
| 1920x1200 (WUXGA) | 1         | 2.22%   |
| 1600x900 (HD+)    | 1         | 2.22%   |
| 1400x1050         | 1         | 2.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 12        | 26.67%  |
| 14     | 7         | 15.56%  |
| 31     | 4         | 8.89%   |
| 24     | 4         | 8.89%   |
| 13     | 4         | 8.89%   |
| 21     | 3         | 6.67%   |
| 27     | 2         | 4.44%   |
| 19     | 2         | 4.44%   |
| 17     | 2         | 4.44%   |
| 11     | 2         | 4.44%   |
| 34     | 1         | 2.22%   |
| 20     | 1         | 2.22%   |
| 18     | 1         | 2.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 20        | 44.44%  |
| 501-600     | 6         | 13.33%  |
| 351-400     | 5         | 11.11%  |
| 201-300     | 5         | 11.11%  |
| 601-700     | 4         | 8.89%   |
| 401-500     | 4         | 8.89%   |
| 701-800     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 36        | 85.71%  |
| 5/4   | 2         | 4.76%   |
| 6/5   | 1         | 2.38%   |
| 4/3   | 1         | 2.38%   |
| 21/9  | 1         | 2.38%   |
| 16/10 | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 12        | 26.67%  |
| 81-90          | 8         | 17.78%  |
| 151-200        | 7         | 15.56%  |
| 351-500        | 5         | 11.11%  |
| 71-80          | 3         | 6.67%   |
| 201-250        | 3         | 6.67%   |
| 51-60          | 2         | 4.44%   |
| 301-350        | 2         | 4.44%   |
| 121-130        | 2         | 4.44%   |
| 251-300        | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 16        | 37.21%  |
| 51-100        | 13        | 30.23%  |
| 101-120       | 9         | 20.93%  |
| More than 240 | 3         | 6.98%   |
| 1-50          | 1         | 2.33%   |
| 161-240       | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 33        | 61.11%  |
| 0     | 13        | 24.07%  |
| 2     | 8         | 14.81%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 26        | 34.67%  |
| Realtek Semiconductor | 17        | 22.67%  |
| Qualcomm Atheros      | 9         | 12%     |
| Broadcom              | 7         | 9.33%   |
| Broadcom Limited      | 3         | 4%      |
| TP-Link               | 2         | 2.67%   |
| Standard Microsystems | 2         | 2.67%   |
| Mellanox Technologies | 2         | 2.67%   |
| Insyde Software       | 2         | 2.67%   |
| Sierra Wireless       | 1         | 1.33%   |
| Samsung Electronics   | 1         | 1.33%   |
| Ralink Technology     | 1         | 1.33%   |
| Ralink                | 1         | 1.33%   |
| MediaTek              | 1         | 1.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 13        | 13.83%  |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 3.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.19%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 3.19%   |
| Standard Microsystems Ethernet controller                         | 2         | 2.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.13%   |
| Intel Wireless 7260                                               | 2         | 2.13%   |
| Intel Wireless 3165                                               | 2         | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.13%   |
| Intel I350 Gigabit Network Connection                             | 2         | 2.13%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.13%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 2.13%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2         | 2.13%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.06%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.06%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.06%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.06%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.06%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.06%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.06%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                           | 1         | 1.06%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 1.06%   |
| MediaTek Armor 8 Pro                                              | 1         | 1.06%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.06%   |
| Intel Wireless 8260                                               | 1         | 1.06%   |
| Intel Wireless 7265                                               | 1         | 1.06%   |
| Intel Wi-Fi 6 AX200                                               | 1         | 1.06%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 16        | 44.44%  |
| Qualcomm Atheros      | 8         | 22.22%  |
| Realtek Semiconductor | 5         | 13.89%  |
| Broadcom              | 2         | 5.56%   |
| TP-Link               | 1         | 2.78%   |
| Sierra Wireless       | 1         | 2.78%   |
| Ralink Technology     | 1         | 2.78%   |
| Ralink                | 1         | 2.78%   |
| Broadcom Limited      | 1         | 2.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 8.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 5.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 5.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 5.56%   |
| Intel Wireless 7260                                        | 2         | 5.56%   |
| Intel Wireless 3165                                        | 2         | 5.56%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 5.56%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1         | 2.78%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.78%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.78%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 2.78%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.78%   |
| Intel Wireless 8260                                        | 1         | 2.78%   |
| Intel Wireless 7265                                        | 1         | 2.78%   |
| Intel Wi-Fi 6 AX200                                        | 1         | 2.78%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.78%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.78%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.78%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 2.78%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 2.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 16        | 32%     |
| Intel                 | 16        | 32%     |
| Broadcom              | 5         | 10%     |
| Standard Microsystems | 2         | 4%      |
| Qualcomm Atheros      | 2         | 4%      |
| Mellanox Technologies | 2         | 4%      |
| Insyde Software       | 2         | 4%      |
| Broadcom Limited      | 2         | 4%      |
| TP-Link               | 1         | 2%      |
| Samsung Electronics   | 1         | 2%      |
| MediaTek              | 1         | 2%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 13        | 22.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 5.17%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 5.17%   |
| Standard Microsystems Ethernet controller                             | 2         | 3.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 3.45%   |
| Intel I350 Gigabit Network Connection                                 | 2         | 3.45%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 3.45%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 3.45%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 3.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 1.72%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1         | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1         | 1.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.72%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 1.72%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.72%   |
| MediaTek Armor 8 Pro                                                  | 1         | 1.72%   |
| Intel Ethernet Controller X550                                        | 1         | 1.72%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.72%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.72%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.72%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 1.72%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.72%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 1.72%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1         | 1.72%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.72%   |
| Intel 82574L Gigabit Network Connection                               | 1         | 1.72%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 1.72%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 1.72%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                | 1         | 1.72%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 1.72%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 43        | 55.84%  |
| WiFi     | 34        | 44.16%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 53.85%  |
| WiFi     | 24        | 46.15%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 28        | 51.85%  |
| 1     | 18        | 33.33%  |
| 0     | 3         | 5.56%   |
| 5     | 2         | 3.7%    |
| 4     | 2         | 3.7%    |
| 6     | 1         | 1.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 43        | 78.18%  |
| Yes  | 12        | 21.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 15        | 46.88%  |
| Qualcomm Atheros Communications | 6         | 18.75%  |
| Realtek Semiconductor           | 4         | 12.5%   |
| Broadcom                        | 3         | 9.38%   |
| Cambridge Silicon Radio         | 2         | 6.25%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |
| ASUSTek Computer                | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 21.88%  |
| Intel AX201 Bluetooth                               | 6         | 18.75%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 12.5%   |
| Realtek Bluetooth Radio                             | 3         | 9.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 6.25%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 3.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 3.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 3.13%   |
| Intel AX200 Bluetooth                               | 1         | 3.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 3.13%   |
| Broadcom HP Portable SoftSailing                    | 1         | 3.13%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 3.13%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 3.13%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 32        | 52.46%  |
| AMD                  | 14        | 22.95%  |
| Nvidia               | 10        | 16.39%  |
| C-Media Electronics  | 2         | 3.28%   |
| Giga-Byte Technology | 1         | 1.64%   |
| Conrad Electronic SE | 1         | 1.64%   |
| Apple                | 1         | 1.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 5         | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 4%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 4%      |
| Intel 8 Series HD Audio Controller                                                                | 3         | 4%      |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 4%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.67%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.67%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.67%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 2.67%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.33%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.33%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.33%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.33%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.33%   |
| Intel Lewisburg MROM 0                                                                            | 1         | 1.33%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.33%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.33%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.33%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.33%   |
| Giga-Byte Technology USB Audio                                                                    | 1         | 1.33%   |
| Conrad Electronic SE MIDI Cable UA0037                                                            | 1         | 1.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 9         | 24.32%  |
| Kingston            | 8         | 21.62%  |
| Micron Technology   | 6         | 16.22%  |
| SK hynix            | 4         | 10.81%  |
| Crucial             | 4         | 10.81%  |
| Unknown             | 2         | 5.41%   |
| Timetec             | 1         | 2.7%    |
| QEMU                | 1         | 2.7%    |
| Hewlett-Packard     | 1         | 2.7%    |
| Elpida              | 1         | 2.7%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 2         | 4.76%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                      | 1         | 2.38%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.38%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 2.38%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.38%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 1         | 2.38%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s                     | 1         | 2.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 2.38%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s       | 1         | 2.38%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.38%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 2.38%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                              | 1         | 2.38%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                                | 1         | 2.38%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s                  | 1         | 2.38%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s                      | 1         | 2.38%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s                      | 1         | 2.38%   |
| QEMU RAM Module 8GB DIMM RAM                                              | 1         | 2.38%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s                       | 1         | 2.38%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.38%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.38%   |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s                      | 1         | 2.38%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.38%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                      | 1         | 2.38%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                     | 1         | 2.38%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s                    | 1         | 2.38%   |
| Kingston RAM 9965742-029.B00G 32GB DIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Kingston RAM 9965640-033.C00G 32GB DIMM DDR4 2667MT/s                     | 1         | 2.38%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 2.38%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 2.38%   |
| HP RAM 712384-081 32GB DIMM DDR3 1866MT/s                                 | 1         | 2.38%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.38%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.38%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.38%   |
| Crucial RAM CT8G4SFS824A.C8FDD1 8192MB SODIMM DDR4 2400MT/s               | 1         | 2.38%   |
| Crucial RAM CT8G4DFRA32A.C4FE 8192MB DIMM DDR4 3200MT/s                   | 1         | 2.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 21        | 63.64%  |
| DDR3    | 7         | 21.21%  |
| LPDDR3  | 2         | 6.06%   |
| RAM     | 1         | 3.03%   |
| DDR2    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 16        | 48.48%  |
| SODIMM       | 14        | 42.42%  |
| Row Of Chips | 3         | 9.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 38.24%  |
| 4096  | 7         | 20.59%  |
| 32768 | 5         | 14.71%  |
| 16384 | 5         | 14.71%  |
| 65536 | 2         | 5.88%   |
| 2048  | 2         | 5.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 13        | 36.11%  |
| 2667    | 6         | 16.67%  |
| 1600    | 6         | 16.67%  |
| 2133    | 2         | 5.56%   |
| 1866    | 2         | 5.56%   |
| 1333    | 2         | 5.56%   |
| 3600    | 1         | 2.78%   |
| 3466    | 1         | 2.78%   |
| 2400    | 1         | 2.78%   |
| 667     | 1         | 2.78%   |
| Unknown | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 26.67%  |
| IMC Networks                           | 5         | 16.67%  |
| Acer                                   | 4         | 13.33%  |
| Suyin                                  | 2         | 6.67%   |
| Realtek Semiconductor                  | 2         | 6.67%   |
| Microdia                               | 2         | 6.67%   |
| Logitech                               | 2         | 6.67%   |
| Syntek                                 | 1         | 3.33%   |
| Luxvisions Innotech Limited            | 1         | 3.33%   |
| DLEQNA19IFK6G2                         | 1         | 3.33%   |
| Creative Technology                    | 1         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 4         | 12.5%   |
| Chicony Integrated HP HD Webcam                                 | 2         | 6.25%   |
| Chicony HP Truevision HD                                        | 2         | 6.25%   |
| Acer Integrated Camera                                          | 2         | 6.25%   |
| Syntek Integrated Camera                                        | 1         | 3.13%   |
| Suyin HD WebCam                                                 | 1         | 3.13%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 3.13%   |
| Realtek Integrated Webcam HD                                    | 1         | 3.13%   |
| Realtek EasyCamera                                              | 1         | 3.13%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 3.13%   |
| Microdia CameraA                                                | 1         | 3.13%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 3.13%   |
| Logitech Webcam C120                                            | 1         | 3.13%   |
| Logitech Webcam B500                                            | 1         | 3.13%   |
| Logitech QuickCam Vision Pro                                    | 1         | 3.13%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 3.13%   |
| DLEQNA19IFK6G2 HP TrueVision HD Camera                          | 1         | 3.13%   |
| Creative Live! Cam Chat HD [VF0700]                             | 1         | 3.13%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 3.13%   |
| Chicony Lenovo EasyCamera                                       | 1         | 3.13%   |
| Chicony EasyCamera                                              | 1         | 3.13%   |
| Chicony 8M Camera                                               | 1         | 3.13%   |
| Chicony 720p HD Camera                                          | 1         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 3.13%   |
| Acer USB Camera                                                 | 1         | 3.13%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.13%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 75%     |
| Synaptics             | 1         | 12.5%   |
| Elan Microelectronics | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 2         | 25%     |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 12.5%   |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 12.5%   |
| Validity Sensors Fingerprint scanner              | 1         | 12.5%   |
| Elan ELAN:ARM-M4                                  | 1         | 12.5%   |
| Unknown                                           | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| OmniKey     | 1         | 33.33%  |
| Broadcom    | 1         | 33.33%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| OmniKey CardMan 3021 / 3121                    | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 33        | 61.11%  |
| 1     | 17        | 31.48%  |
| 2     | 2         | 3.7%    |
| 7     | 1         | 1.85%   |
| 5     | 1         | 1.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 8         | 27.59%  |
| Graphics card         | 6         | 20.69%  |
| Net/wireless          | 3         | 10.34%  |
| Sound                 | 2         | 6.9%    |
| Net/ethernet          | 2         | 6.9%    |
| Multimedia controller | 2         | 6.9%    |
| Unassigned class      | 1         | 3.45%   |
| Storage/ide           | 1         | 3.45%   |
| Firewire controller   | 1         | 3.45%   |
| Chipcard              | 1         | 3.45%   |
| Camera                | 1         | 3.45%   |
| Bluetooth             | 1         | 3.45%   |

