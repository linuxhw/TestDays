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

Total: 140

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | H12SSL-i                    | Server      | [61297d4bc4](https://linux-hardware.org/?probe=61297d4bc4) | Apr 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [acb0f81194](https://linux-hardware.org/?probe=acb0f81194) | Apr 01, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [3c3474d69b](https://linux-hardware.org/?probe=3c3474d69b) | Mar 28, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [21f6af6f50](https://linux-hardware.org/?probe=21f6af6f50) | Mar 28, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [586decd061](https://linux-hardware.org/?probe=586decd061) | Mar 27, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d96c0cfcd9](https://linux-hardware.org/?probe=d96c0cfcd9) | Mar 27, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [56d537b480](https://linux-hardware.org/?probe=56d537b480) | Mar 26, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [da489de02c](https://linux-hardware.org/?probe=da489de02c) | Mar 26, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1584039ca8](https://linux-hardware.org/?probe=1584039ca8) | Mar 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a8e6ba1268](https://linux-hardware.org/?probe=a8e6ba1268) | Mar 24, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0fc5cf1944](https://linux-hardware.org/?probe=0fc5cf1944) | Mar 19, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [d21d79ee06](https://linux-hardware.org/?probe=d21d79ee06) | Mar 19, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [97af59e728](https://linux-hardware.org/?probe=97af59e728) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [173e6ad8bf](https://linux-hardware.org/?probe=173e6ad8bf) | Mar 18, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [17e455c4df](https://linux-hardware.org/?probe=17e455c4df) | Mar 18, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [43b58e51b4](https://linux-hardware.org/?probe=43b58e51b4) | Mar 12, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [7d42741fac](https://linux-hardware.org/?probe=7d42741fac) | Mar 12, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [6b87ac7144](https://linux-hardware.org/?probe=6b87ac7144) | Mar 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [c5419b8b27](https://linux-hardware.org/?probe=c5419b8b27) | Mar 11, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [f98fe964b2](https://linux-hardware.org/?probe=f98fe964b2) | Mar 07, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [70b5b39ce8](https://linux-hardware.org/?probe=70b5b39ce8) | Mar 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [da9d93a7ea](https://linux-hardware.org/?probe=da9d93a7ea) | Mar 06, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [77ca3b430b](https://linux-hardware.org/?probe=77ca3b430b) | Mar 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [81c9f3a796](https://linux-hardware.org/?probe=81c9f3a796) | Mar 04, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [a750fc7c24](https://linux-hardware.org/?probe=a750fc7c24) | Mar 04, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [ff1f611cc9](https://linux-hardware.org/?probe=ff1f611cc9) | Mar 03, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [0a8ce98d46](https://linux-hardware.org/?probe=0a8ce98d46) | Mar 03, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [975790ee68](https://linux-hardware.org/?probe=975790ee68) | Mar 01, 2023 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [92300b45fe](https://linux-hardware.org/?probe=92300b45fe) | Mar 01, 2023 |
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
| AlmaLinux 9.1 | 16        | 27.12%  |
| AlmaLinux 8.6 | 10        | 16.95%  |
| AlmaLinux 9.0 | 9         | 15.25%  |
| AlmaLinux 8.4 | 9         | 15.25%  |
| AlmaLinux 8.7 | 8         | 13.56%  |
| AlmaLinux 8.3 | 4         | 6.78%   |
| AlmaLinux 8.5 | 3         | 5.08%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| AlmaLinux | 57        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.x86_64   | 8         | 13.33%  |
| 4.18.0-425.3.1.el8.x86_64     | 6         | 10%     |
| 5.14.0-162.12.1.el9_1.x86_64  | 5         | 8.33%   |
| 5.14.0-70.22.1.el9_0.x86_64   | 3         | 5%      |
| 5.14.0-162.18.1.el9_1.x86_64  | 3         | 5%      |
| 4.18.0-372.26.1.el8_6.x86_64  | 3         | 5%      |
| 4.18.0-240.15.1.el8_3.x86_64  | 3         | 5%      |
| 5.14.0-70.30.1.el9_0.x86_64   | 2         | 3.33%   |
| 5.14.0-70.13.1.el9_0.x86_64   | 2         | 3.33%   |
| 4.18.0-425.13.1.el8_7.x86_64  | 2         | 3.33%   |
| 4.18.0-372.9.1.el8.x86_64     | 2         | 3.33%   |
| 4.18.0-348.12.2.el8_5.x86_64  | 2         | 3.33%   |
| 4.18.0-305.el8.x86_64         | 2         | 3.33%   |
| 4.18.0-305.7.1.el8_4.x86_64   | 2         | 3.33%   |
| 4.18.0-305.12.1.el8_4.x86_64  | 2         | 3.33%   |
| 5.4.175-1.el8.elrepo.x86_64   | 1         | 1.67%   |
| 5.15.45-v8.1.el8              | 1         | 1.67%   |
| 5.14.0-70.26.1.el9_0.x86_64   | 1         | 1.67%   |
| 5.14.0-70.17.1.el9_0.x86_64   | 1         | 1.67%   |
| 5.10.60-v8.1.el8              | 1         | 1.67%   |
| 4.18.0-425.10.1.el8_7.x86_64  | 1         | 1.67%   |
| 4.18.0-372.19.1.el8_6.x86_64  | 1         | 1.67%   |
| 4.18.0-372.16.1.el8_6.aarch64 | 1         | 1.67%   |
| 4.18.0-348.el8.x86_64         | 1         | 1.67%   |
| 4.18.0-348.2.1.el8_5.x86_64   | 1         | 1.67%   |
| 4.18.0-305.3.1.el8_4.x86_64   | 1         | 1.67%   |
| 4.18.0-305.10.2.el8_4.x86_64  | 1         | 1.67%   |
| 4.18.0-240.22.1.el8_3.x86_64  | 1         | 1.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 29        | 50.88%  |
| 5.14.0  | 25        | 43.86%  |
| 5.4.175 | 1         | 1.75%   |
| 5.15.45 | 1         | 1.75%   |
| 5.10.60 | 1         | 1.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 29        | 50.88%  |
| 5.14    | 25        | 43.86%  |
| 5.4     | 1         | 1.75%   |
| 5.15    | 1         | 1.75%   |
| 5.10    | 1         | 1.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 54        | 94.74%  |
| aarch64 | 3         | 5.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 34        | 59.65%  |
| Unknown         | 14        | 24.56%  |
| KDE5            | 3         | 5.26%   |
| XFCE            | 2         | 3.51%   |
| MATE            | 2         | 3.51%   |
| GNOME Flashback | 1         | 1.75%   |
| GNOME Classic   | 1         | 1.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 28        | 49.12%  |
| X11     | 20        | 35.09%  |
| Unknown | 6         | 10.53%  |
| Tty     | 3         | 5.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 66.67%  |
| GDM     | 15        | 26.32%  |
| SDDM    | 2         | 3.51%   |
| LightDM | 2         | 3.51%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 29        | 49.15%  |
| en_GB   | 7         | 11.86%  |
| de_DE   | 7         | 11.86%  |
| en_CA   | 3         | 5.08%   |
| Unknown | 3         | 5.08%   |
| fr_FR   | 2         | 3.39%   |
| C       | 2         | 3.39%   |
| uk_UA   | 1         | 1.69%   |
| ru_UA   | 1         | 1.69%   |
| ru_RU   | 1         | 1.69%   |
| es_VE   | 1         | 1.69%   |
| es_ES   | 1         | 1.69%   |
| da_DK   | 1         | 1.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 36        | 62.07%  |
| BIOS | 22        | 37.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 45        | 78.95%  |
| Ext4 | 12        | 21.05%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 29        | 50.88%  |
| Unknown | 21        | 36.84%  |
| MBR     | 7         | 12.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 46        | 80.7%   |
| Yes       | 11        | 19.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 47        | 82.46%  |
| Yes       | 10        | 17.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 14        | 24.56%  |
| Hewlett-Packard         | 11        | 19.3%   |
| Dell                    | 5         | 8.77%   |
| Gigabyte Technology     | 4         | 7.02%   |
| ASUSTek Computer        | 4         | 7.02%   |
| Supermicro              | 3         | 5.26%   |
| Raspberry Pi Foundation | 2         | 3.51%   |
| Intel                   | 2         | 3.51%   |
| Google                  | 2         | 3.51%   |
| ASRock                  | 2         | 3.51%   |
| Acer                    | 2         | 3.51%   |
| TUXEDO                  | 1         | 1.75%   |
| Toshiba                 | 1         | 1.75%   |
| Optimized Hosting       | 1         | 1.75%   |
| MSI                     | 1         | 1.75%   |
| AZW                     | 1         | 1.75%   |
| ASRockRack              | 1         | 1.75%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| RPi Raspberry Pi                     | 2         | 3.51%   |
| TUXEDO Aura 15 Gen1                  | 1         | 1.75%   |
| Toshiba Satellite L50-C              | 1         | 1.75%   |
| Supermicro Super Server              | 1         | 1.75%   |
| Supermicro PIO-617R-TLN4F+-ST031     | 1         | 1.75%   |
| Supermicro motherboard-H12 Series    | 1         | 1.75%   |
| Optimized Hosting KVM                | 1         | 1.75%   |
| MSI MS-7900                          | 1         | 1.75%   |
| Lenovo Yoga 2 13 20344               | 1         | 1.75%   |
| Lenovo V14-ARE 82DQ                  | 1         | 1.75%   |
| Lenovo ThinkStation P350 30E6S20S00  | 1         | 1.75%   |
| Lenovo ThinkPad T440s 20ARS32P00     | 1         | 1.75%   |
| Lenovo ThinkPad T14 Gen 1 20S1S39Q00 | 1         | 1.75%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3003XUS | 1         | 1.75%   |
| Lenovo Legion Y530-15ICH 81FV        | 1         | 1.75%   |
| Lenovo Legion 5 15IMH05H 81Y6        | 1         | 1.75%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS    | 1         | 1.75%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS  | 1         | 1.75%   |
| Lenovo IdeaPad S145-15IWL 81MV       | 1         | 1.75%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.75%   |
| Lenovo H520S 10093                   | 1         | 1.75%   |
| Lenovo B50-30 20382                  | 1         | 1.75%   |
| Intel powered classmate PC           | 1         | 1.75%   |
| Intel NUC8i5BEH                      | 1         | 1.75%   |
| HP Z620 Workstation                  | 1         | 1.75%   |
| HP Z600 Workstation                  | 1         | 1.75%   |
| HP Z2 Tower G4 Workstation           | 1         | 1.75%   |
| HP ProLiant DL360p Gen8              | 1         | 1.75%   |
| HP Laptop 17-cp0xxx                  | 1         | 1.75%   |
| HP Laptop 15-ef1xxx                  | 1         | 1.75%   |
| HP Falco                             | 1         | 1.75%   |
| HP ENVY dv6                          | 1         | 1.75%   |
| HP EliteBook 8570w                   | 1         | 1.75%   |
| HP EliteBook 850 G8 Notebook PC      | 1         | 1.75%   |
| HP EliteBook 8470p                   | 1         | 1.75%   |
| Google Kohaku                        | 1         | 1.75%   |
| Google Kefka                         | 1         | 1.75%   |
| Gigabyte Z690 GAMING X DDR4          | 1         | 1.75%   |
| Gigabyte Z590 AORUS PRO AX           | 1         | 1.75%   |
| Gigabyte MP32-AR1-00                 | 1         | 1.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Lenovo ThinkPad                  | 3         | 5.26%   |
| Lenovo IdeaPad                   | 3         | 5.26%   |
| HP EliteBook                     | 3         | 5.26%   |
| RPi Raspberry                    | 2         | 3.51%   |
| Lenovo Legion                    | 2         | 3.51%   |
| HP Laptop                        | 2         | 3.51%   |
| TUXEDO Aura                      | 1         | 1.75%   |
| Toshiba Satellite                | 1         | 1.75%   |
| Supermicro Super                 | 1         | 1.75%   |
| Supermicro PIO-617R-TLN4F+-ST031 | 1         | 1.75%   |
| Supermicro motherboard-H12       | 1         | 1.75%   |
| Optimized Hosting KVM            | 1         | 1.75%   |
| MSI MS-7900                      | 1         | 1.75%   |
| Lenovo Yoga                      | 1         | 1.75%   |
| Lenovo V14-ARE                   | 1         | 1.75%   |
| Lenovo ThinkStation              | 1         | 1.75%   |
| Lenovo IdeaPadFlex               | 1         | 1.75%   |
| Lenovo H520S                     | 1         | 1.75%   |
| Lenovo B50-30                    | 1         | 1.75%   |
| Intel powered                    | 1         | 1.75%   |
| Intel NUC8i5BEH                  | 1         | 1.75%   |
| HP Z620                          | 1         | 1.75%   |
| HP Z600                          | 1         | 1.75%   |
| HP Z2                            | 1         | 1.75%   |
| HP ProLiant                      | 1         | 1.75%   |
| HP Falco                         | 1         | 1.75%   |
| HP ENVY                          | 1         | 1.75%   |
| Google Kohaku                    | 1         | 1.75%   |
| Google Kefka                     | 1         | 1.75%   |
| Gigabyte Z690                    | 1         | 1.75%   |
| Gigabyte Z590                    | 1         | 1.75%   |
| Gigabyte MP32-AR1-00             | 1         | 1.75%   |
| Gigabyte H81M-D2V                | 1         | 1.75%   |
| Dell XPS                         | 1         | 1.75%   |
| Dell Precision                   | 1         | 1.75%   |
| Dell PowerEdge                   | 1         | 1.75%   |
| Dell Latitude                    | 1         | 1.75%   |
| Dell Inspiron                    | 1         | 1.75%   |
| AZW SER                          | 1         | 1.75%   |
| ASUS TUF                         | 1         | 1.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 11        | 19.3%   |
| 2012    | 8         | 14.04%  |
| 2022    | 6         | 10.53%  |
| 2019    | 6         | 10.53%  |
| 2021    | 5         | 8.77%   |
| 2018    | 4         | 7.02%   |
| 2014    | 4         | 7.02%   |
| 2011    | 3         | 5.26%   |
| 2015    | 2         | 3.51%   |
| 2013    | 2         | 3.51%   |
| 2010    | 2         | 3.51%   |
| Unknown | 2         | 3.51%   |
| 2016    | 1         | 1.75%   |
| 2009    | 1         | 1.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 28        | 49.12%  |
| Desktop        | 17        | 29.82%  |
| Server         | 6         | 10.53%  |
| System on chip | 2         | 3.51%   |
| Convertible    | 2         | 3.51%   |
| Mini pc        | 2         | 3.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 50        | 87.72%  |
| Enabled  | 7         | 12.28%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 94.74%  |
| Yes  | 3         | 5.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 15        | 25.86%  |
| 8.01-16.0       | 12        | 20.69%  |
| 64.01-256.0     | 9         | 15.52%  |
| 16.01-24.0      | 6         | 10.34%  |
| 3.01-4.0        | 5         | 8.62%   |
| More than 256.0 | 4         | 6.9%    |
| 32.01-64.0      | 2         | 3.45%   |
| 1.01-2.0        | 2         | 3.45%   |
| 0.51-1.0        | 2         | 3.45%   |
| 24.01-32.0      | 1         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 16        | 26.67%  |
| 1.01-2.0    | 12        | 20%     |
| 3.01-4.0    | 10        | 16.67%  |
| 4.01-8.0    | 8         | 13.33%  |
| 8.01-16.0   | 3         | 5%      |
| 0.51-1.0    | 3         | 5%      |
| 32.01-64.0  | 2         | 3.33%   |
| 16.01-24.0  | 2         | 3.33%   |
| 0.01-0.5    | 2         | 3.33%   |
| 24.01-32.0  | 1         | 1.67%   |
| 64.01-256.0 | 1         | 1.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 27        | 46.55%  |
| 2      | 18        | 31.03%  |
| 3      | 5         | 8.62%   |
| 4      | 4         | 6.9%    |
| 11     | 1         | 1.72%   |
| 6      | 1         | 1.72%   |
| 5      | 1         | 1.72%   |
| 0      | 1         | 1.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 44        | 77.19%  |
| Yes       | 13        | 22.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 45        | 78.95%  |
| No        | 12        | 21.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 36        | 63.16%  |
| No        | 21        | 36.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 34        | 59.65%  |
| No        | 23        | 40.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 17        | 29.82%  |
| Germany      | 8         | 14.04%  |
| UK           | 4         | 7.02%   |
| France       | 4         | 7.02%   |
| Canada       | 4         | 7.02%   |
| Russia       | 3         | 5.26%   |
| Ukraine      | 2         | 3.51%   |
| Spain        | 2         | 3.51%   |
| Netherlands  | 2         | 3.51%   |
| Venezuela    | 1         | 1.75%   |
| Switzerland  | 1         | 1.75%   |
| Sweden       | 1         | 1.75%   |
| South Africa | 1         | 1.75%   |
| Puerto Rico  | 1         | 1.75%   |
| Pakistan     | 1         | 1.75%   |
| Kazakhstan   | 1         | 1.75%   |
| India        | 1         | 1.75%   |
| Greenland    | 1         | 1.75%   |
| Finland      | 1         | 1.75%   |
| Bulgaria     | 1         | 1.75%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Hamburg          | 3         | 5.17%   |
| Queens           | 2         | 3.45%   |
| Dallas           | 2         | 3.45%   |
| Zaporizhzhia     | 1         | 1.72%   |
| Winterswijk      | 1         | 1.72%   |
| Uppsala          | 1         | 1.72%   |
| Tuusula          | 1         | 1.72%   |
| Tampa            | 1         | 1.72%   |
| Strasbourg       | 1         | 1.72%   |
| Stadtilm         | 1         | 1.72%   |
| St. Paul         | 1         | 1.72%   |
| Sofia            | 1         | 1.72%   |
| Shimanovsk       | 1         | 1.72%   |
| San Diego        | 1         | 1.72%   |
| Rothwell         | 1         | 1.72%   |
| Regina           | 1         | 1.72%   |
| Redlands         | 1         | 1.72%   |
| Parla            | 1         | 1.72%   |
| Paris            | 1         | 1.72%   |
| Nizhniy Novgorod | 1         | 1.72%   |
| Moscow           | 1         | 1.72%   |
| Mangalore        | 1         | 1.72%   |
| Los Angeles      | 1         | 1.72%   |
| London           | 1         | 1.72%   |
| Liverpool        | 1         | 1.72%   |
| Lille            | 1         | 1.72%   |
| Lawrence         | 1         | 1.72%   |
| Land O' Lakes    | 1         | 1.72%   |
| Lahore           | 1         | 1.72%   |
| Kyiv             | 1         | 1.72%   |
| Kitimat          | 1         | 1.72%   |
| Kennewick        | 1         | 1.72%   |
| Johannesburg     | 1         | 1.72%   |
| Ilulissat        | 1         | 1.72%   |
| Guglingen        | 1         | 1.72%   |
| Guanare          | 1         | 1.72%   |
| Groningen        | 1         | 1.72%   |
| Frankenthal      | 1         | 1.72%   |
| Essen            | 1         | 1.72%   |
| East Orange      | 1         | 1.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 11        | 13     | 13.25%  |
| Seagate                     | 10        | 18     | 12.05%  |
| Samsung Electronics         | 10        | 14     | 12.05%  |
| Kingston                    | 5         | 6      | 6.02%   |
| Unknown                     | 4         | 6      | 4.82%   |
| SK hynix                    | 4         | 4      | 4.82%   |
| Kingston Technology Company | 4         | 12     | 4.82%   |
| Toshiba                     | 3         | 4      | 3.61%   |
| Intel                       | 3         | 3      | 3.61%   |
| Netac                       | 2         | 2      | 2.41%   |
| Micron Technology           | 2         | 2      | 2.41%   |
| LITEONIT                    | 2         | 4      | 2.41%   |
| Hewlett-Packard             | 2         | 9      | 2.41%   |
| Dell                        | 2         | 3      | 2.41%   |
| Crucial                     | 2         | 4      | 2.41%   |
| Union Memory                | 1         | 1      | 1.2%    |
| Transcend                   | 1         | 1      | 1.2%    |
| Team                        | 1         | 1      | 1.2%    |
| SSSTC                       | 1         | 1      | 1.2%    |
| Silicon Motion              | 1         | 8      | 1.2%    |
| Sandisk                     | 1         | 1      | 1.2%    |
| QEMU                        | 1         | 1      | 1.2%    |
| Plextor                     | 1         | 1      | 1.2%    |
| LITEON                      | 1         | 1      | 1.2%    |
| KIOXIA                      | 1         | 1      | 1.2%    |
| Hitachi                     | 1         | 1      | 1.2%    |
| HGST                        | 1         | 1      | 1.2%    |
| EMTEC                       | 1         | 2      | 1.2%    |
| DELLBOSS                    | 1         | 1      | 1.2%    |
| China                       | 1         | 1      | 1.2%    |
| ASMT                        | 1         | 2      | 1.2%    |
| A-DATA Technology           | 1         | 1      | 1.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| WDC WD10SPZX-24Z10 1TB                            | 2         | 2.17%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 2.17%   |
| Samsung MZVL22T0HBLB-00BL7 2TB                    | 2         | 2.17%   |
| Kingston Company KC2000 NVMe SSD 1TB              | 2         | 2.17%   |
| Kingston Company A2000 NVMe SSD 500GB             | 2         | 2.17%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 2.17%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 1.09%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 1.09%   |
| WDC WD5000LPCX-21VHAT0 500GB                      | 1         | 1.09%   |
| WDC WD20EARS-00J2GB0 2TB                          | 1         | 1.09%   |
| WDC WD10SPZX-60Z10T1 1TB                          | 1         | 1.09%   |
| WDC WD10EZEX-75M2NA0 1TB                          | 1         | 1.09%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB              | 1         | 1.09%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB              | 1         | 1.09%   |
| Unknown SD64G  64GB                               | 1         | 1.09%   |
| Unknown SD/MMC/MS PRO 64GB                        | 1         | 1.09%   |
| Unknown MMC Card  16GB                            | 1         | 1.09%   |
| Unknown EC2QT  64GB                               | 1         | 1.09%   |
| Union Memory UMIS RPITJ512VME2OWD 512GB           | 1         | 1.09%   |
| Transcend TS256GMTE220S 256GB                     | 1         | 1.09%   |
| Toshiba MK6475GSX 640GB                           | 1         | 1.09%   |
| Toshiba MG06ACA800E 8TB                           | 1         | 1.09%   |
| Toshiba DT01ACA100 1TB                            | 1         | 1.09%   |
| Team T253X1480G 480GB SSD                         | 1         | 1.09%   |
| SSSTC CL1-3D256 256GB                             | 1         | 1.09%   |
| SK hynix SH920 2.5 7MM 256GB SSD                  | 1         | 1.09%   |
| SK hynix PC300 NVMe Solid State Drive 256GB       | 1         | 1.09%   |
| SK hynix NVMe SSD Drive 256GB                     | 1         | 1.09%   |
| SK hynix BC511 NVMe 256GB                         | 1         | 1.09%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1         | 1.09%   |
| Seagate ST4000NM000A 00MX141 00MX141LEN 4TB       | 1         | 1.09%   |
| Seagate ST4000NC001-1FS168 4TB                    | 1         | 1.09%   |
| Seagate ST4000DM000-1F2168 4TB                    | 1         | 1.09%   |
| Seagate ST31000528AS 1TB                          | 1         | 1.09%   |
| Seagate ST3000DM001-1CH166 3TB                    | 1         | 1.09%   |
| Seagate ST250LM004 HN-M250MBB 250GB               | 1         | 1.09%   |
| Seagate ST2000NM012A-2MP130 2TB                   | 1         | 1.09%   |
| Seagate ST2000LM015-2E8174 2TB                    | 1         | 1.09%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 1         | 1.09%   |
| Seagate ST2000DM001-1ER164 2TB                    | 1         | 1.09%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 10        | 18     | 35.71%  |
| WDC             | 8         | 8      | 28.57%  |
| Toshiba         | 3         | 4      | 10.71%  |
| Unknown         | 1         | 2      | 3.57%   |
| QEMU            | 1         | 1      | 3.57%   |
| Hitachi         | 1         | 1      | 3.57%   |
| HGST            | 1         | 1      | 3.57%   |
| Hewlett-Packard | 1         | 8      | 3.57%   |
| DELLBOSS        | 1         | 1      | 3.57%   |
| ASMT            | 1         | 2      | 3.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 5         | 5      | 19.23%  |
| Samsung Electronics | 3         | 3      | 11.54%  |
| Intel               | 3         | 3      | 11.54%  |
| Netac               | 2         | 2      | 7.69%   |
| LITEONIT            | 2         | 4      | 7.69%   |
| WDC                 | 1         | 3      | 3.85%   |
| Team                | 1         | 1      | 3.85%   |
| SK hynix            | 1         | 1      | 3.85%   |
| Plextor             | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| LITEON              | 1         | 1      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |
| Dell                | 1         | 2      | 3.85%   |
| Crucial             | 1         | 2      | 3.85%   |
| China               | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 26        | 46     | 32.1%   |
| HDD     | 26        | 46     | 32.1%   |
| SSD     | 25        | 32     | 30.86%  |
| MMC     | 3         | 4      | 3.7%    |
| Unknown | 1         | 2      | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 40        | 72     | 54.79%  |
| NVMe | 26        | 46     | 35.62%  |
| SAS  | 4         | 8      | 5.48%   |
| MMC  | 3         | 4      | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 33     | 50%     |
| 0.51-1.0   | 15        | 19     | 27.78%  |
| 1.01-2.0   | 5         | 11     | 9.26%   |
| 3.01-4.0   | 3         | 3      | 5.56%   |
| 4.01-10.0  | 3         | 11     | 5.56%   |
| 2.01-3.0   | 1         | 1      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 16        | 27.12%  |
| 251-500        | 10        | 16.95%  |
| 501-1000       | 7         | 11.86%  |
| More than 3000 | 6         | 10.17%  |
| 51-100         | 5         | 8.47%   |
| Unknown        | 5         | 8.47%   |
| 1001-2000      | 3         | 5.08%   |
| 1-20           | 3         | 5.08%   |
| 21-50          | 2         | 3.39%   |
| 2001-3000      | 2         | 3.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 38.71%  |
| 21-50          | 11        | 17.74%  |
| 101-250        | 8         | 12.9%   |
| 51-100         | 7         | 11.29%  |
| Unknown        | 5         | 8.06%   |
| 251-500        | 3         | 4.84%   |
| More than 3000 | 2         | 3.23%   |
| 2001-3000      | 1         | 1.61%   |
| 501-1000       | 1         | 1.61%   |

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
| Works    | 32        | 77     | 50%     |
| Detected | 29        | 48     | 45.31%  |
| Malfunc  | 3         | 5      | 4.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 33        | 42.86%  |
| AMD                            | 14        | 18.18%  |
| Samsung Electronics            | 8         | 10.39%  |
| Kingston Technology Company    | 5         | 6.49%   |
| Union Memory (Shenzhen)        | 2         | 2.6%    |
| SK hynix                       | 2         | 2.6%    |
| Silicon Motion                 | 2         | 2.6%    |
| SanDisk                        | 2         | 2.6%    |
| Toshiba America Info Systems   | 1         | 1.3%    |
| Solid State Storage Technology | 1         | 1.3%    |
| Red Hat                        | 1         | 1.3%    |
| Micron/Crucial Technology      | 1         | 1.3%    |
| Micron Technology              | 1         | 1.3%    |
| Marvell Technology Group       | 1         | 1.3%    |
| LSI Logic / Symbios Logic      | 1         | 1.3%    |
| Hewlett-Packard                | 1         | 1.3%    |
| Broadcom / LSI                 | 1         | 1.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 11        | 12.94%  |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                | 3         | 3.53%   |
| Samsung NVMe SSD Controller 980                                               | 3         | 3.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 3         | 3.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 3         | 3.53%   |
| AMD 400 Series Chipset SATA Controller                                        | 3         | 3.53%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 2.35%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                 | 2         | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 2         | 2.35%   |
| Kingston Company KC2000 NVMe SSD                                              | 2         | 2.35%   |
| Kingston Company A2000 NVMe SSD                                               | 2         | 2.35%   |
| Intel SATA Controller [RAID mode]                                             | 2         | 2.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 2.35%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                           | 2         | 2.35%   |
| Intel C600/X79 series chipset SATA RAID Controller                            | 2         | 2.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 2         | 2.35%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                          | 2         | 2.35%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 2         | 2.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                          | 1         | 1.18%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 1.18%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                   | 1         | 1.18%   |
| SK hynix BC511                                                                | 1         | 1.18%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 1         | 1.18%   |
| SanDisk NVMe Controller                                                       | 1         | 1.18%   |
| Red Hat Virtio SCSI                                                           | 1         | 1.18%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                          | 1         | 1.18%   |
| Micron NVMe Controller                                                        | 1         | 1.18%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller         | 1         | 1.18%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                       | 1         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                       | 1         | 1.18%   |
| Intel Volume Management Device NVMe RAID Controller                           | 1         | 1.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 1         | 1.18%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 1.18%   |
| Intel NVMe Datacenter SSD [3DNAND, Beta Rock Controller]                      | 1         | 1.18%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 1         | 1.18%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                 | 1         | 1.18%   |
| Intel C620 Series Chipset Family IDE Redirection                              | 1         | 1.18%   |
| Intel C600/X79 series chipset IDE-r Controller                                | 1         | 1.18%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 38        | 46.91%  |
| NVMe | 26        | 32.1%   |
| RAID | 9         | 11.11%  |
| IDE  | 5         | 6.17%   |
| SAS  | 2         | 2.47%   |
| SCSI | 1         | 1.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 37        | 64.91%  |
| AMD    | 17        | 29.82%  |
| ARM    | 3         | 5.26%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 5.17%   |
| ARM Processor                               | 3         | 5.17%   |
| AMD EPYC 7282 16-Core Processor             | 2         | 3.45%   |
| Intel Xeon W-1350 @ 3.30GHz                 | 1         | 1.72%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 1.72%   |
| Intel Xeon Gold 5220R CPU @ 2.20GHz         | 1         | 1.72%   |
| Intel Xeon E-2144G CPU @ 3.60GHz            | 1         | 1.72%   |
| Intel Xeon CPU X5550 @ 2.67GHz              | 1         | 1.72%   |
| Intel Xeon CPU E5-2667 v2 @ 3.30GHz         | 1         | 1.72%   |
| Intel Xeon CPU E5-2630 0 @ 2.30GHz          | 1         | 1.72%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 1.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 1.72%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 1.72%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 1.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 1.72%   |
| Intel Core i7-3840QM CPU @ 2.80GHz          | 1         | 1.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.72%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.72%   |
| Intel Core i5-8259U CPU @ 2.30GHz           | 1         | 1.72%   |
| Intel Core i5-7Y54 CPU @ 1.20GHz            | 1         | 1.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 1.72%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.72%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 1         | 1.72%   |
| Intel Core i3-8145U CPU @ 2.10GHz           | 1         | 1.72%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 1         | 1.72%   |
| Intel Core i3-4010U CPU @ 1.70GHz           | 1         | 1.72%   |
| Intel Core i3-2130 CPU @ 3.40GHz            | 1         | 1.72%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 1         | 1.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 1         | 1.72%   |
| Intel Celeron 2955U @ 1.40GHz               | 1         | 1.72%   |
| Intel Atom CPU N455 @ 1.66GHz               | 1         | 1.72%   |
| Intel 12th Gen Core i7-12700KF              | 1         | 1.72%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 1         | 1.72%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 1         | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 1         | 1.72%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1         | 1.72%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.72%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 1         | 1.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 10        | 17.54%  |
| Other                   | 8         | 14.04%  |
| Intel Xeon              | 7         | 12.28%  |
| Intel Core i7           | 5         | 8.77%   |
| Intel Core i3           | 5         | 8.77%   |
| AMD EPYC                | 4         | 7.02%   |
| AMD Ryzen 7             | 3         | 5.26%   |
| AMD Ryzen 5             | 3         | 5.26%   |
| Intel Celeron           | 2         | 3.51%   |
| AMD Ryzen 9             | 2         | 3.51%   |
| Intel Xeon Gold         | 1         | 1.75%   |
| Intel Pentium Dual-Core | 1         | 1.75%   |
| Intel Pentium           | 1         | 1.75%   |
| Intel Atom              | 1         | 1.75%   |
| AMD Ryzen 3             | 1         | 1.75%   |
| AMD FX                  | 1         | 1.75%   |
| AMD A6                  | 1         | 1.75%   |
| AMD A10                 | 1         | 1.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 17        | 29.31%  |
| 2       | 17        | 29.31%  |
| 6       | 7         | 12.07%  |
| 16      | 4         | 6.9%    |
| 12      | 4         | 6.9%    |
| 8       | 2         | 3.45%   |
| Unknown | 2         | 3.45%   |
| 80      | 1         | 1.72%   |
| 48      | 1         | 1.72%   |
| 32      | 1         | 1.72%   |
| 24      | 1         | 1.72%   |
| 1       | 1         | 1.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 50        | 87.72%  |
| 2       | 4         | 7.02%   |
| Unknown | 2         | 3.51%   |
| 4       | 1         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 45        | 78.95%  |
| 1       | 10        | 17.54%  |
| Unknown | 2         | 3.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 54        | 94.74%  |
| Unknown        | 3         | 5.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 11        | 18.64%  |
| 0x806ec    | 4         | 6.78%   |
| 0x306a9    | 4         | 6.78%   |
| 0x40651    | 3         | 5.08%   |
| 0xa0671    | 2         | 3.39%   |
| 0x906ea    | 2         | 3.39%   |
| 0x806c1    | 2         | 3.39%   |
| 0x306e4    | 2         | 3.39%   |
| 0x08701021 | 2         | 3.39%   |
| 0x08600106 | 2         | 3.39%   |
| 0xa0655    | 1         | 1.69%   |
| 0xa0652    | 1         | 1.69%   |
| 0x906e9    | 1         | 1.69%   |
| 0x90672    | 1         | 1.69%   |
| 0x806e9    | 1         | 1.69%   |
| 0x806d1    | 1         | 1.69%   |
| 0x50657    | 1         | 1.69%   |
| 0x406e3    | 1         | 1.69%   |
| 0x406c4    | 1         | 1.69%   |
| 0x306c3    | 1         | 1.69%   |
| 0x30678    | 1         | 1.69%   |
| 0x206a7    | 1         | 1.69%   |
| 0x20655    | 1         | 1.69%   |
| 0x106ca    | 1         | 1.69%   |
| 0x106a5    | 1         | 1.69%   |
| 0x1067a    | 1         | 1.69%   |
| 0x08608103 | 1         | 1.69%   |
| 0x08301055 | 1         | 1.69%   |
| 0x08108109 | 1         | 1.69%   |
| 0x08108102 | 1         | 1.69%   |
| 0x0810100b | 1         | 1.69%   |
| 0x06006705 | 1         | 1.69%   |
| 0x06006704 | 1         | 1.69%   |
| 0x06003106 | 1         | 1.69%   |
| 0x06000852 | 1         | 1.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 2            | 9         | 15.79%  |
| KabyLake         | 9         | 15.79%  |
| IvyBridge        | 6         | 10.53%  |
| Haswell          | 4         | 7.02%   |
| Unknown          | 4         | 7.02%   |
| Icelake          | 3         | 5.26%   |
| Zen+             | 2         | 3.51%   |
| TigerLake        | 2         | 3.51%   |
| Skylake          | 2         | 3.51%   |
| Silvermont       | 2         | 3.51%   |
| SandyBridge      | 2         | 3.51%   |
| Excavator        | 2         | 3.51%   |
| CometLake        | 2         | 3.51%   |
| Zen              | 1         | 1.75%   |
| Westmere         | 1         | 1.75%   |
| Steamroller      | 1         | 1.75%   |
| Piledriver       | 1         | 1.75%   |
| Penryn           | 1         | 1.75%   |
| Nehalem          | 1         | 1.75%   |
| Bonnell          | 1         | 1.75%   |
| Alderlake Hybrid | 1         | 1.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 26        | 44.07%  |
| AMD                        | 13        | 22.03%  |
| Nvidia                     | 12        | 20.34%  |
| ASPEED Technology          | 4         | 6.78%   |
| Matrox Electronics Systems | 3         | 5.08%   |
| Red Hat                    | 1         | 1.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 6.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 5.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 5.08%   |
| Nvidia GA106 [Geforce RTX 3050]                                                          | 2         | 3.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 3.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 3.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 3.39%   |
| AMD Renoir                                                                               | 2         | 3.39%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 3.39%   |
| Red Hat QXL paravirtual graphic card                                                     | 1         | 1.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1.69%   |
| Nvidia GP107GL [Quadro P620]                                                             | 1         | 1.69%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 1         | 1.69%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 1.69%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 1         | 1.69%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 1         | 1.69%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1.69%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 1         | 1.69%   |
| Nvidia GA102GL [RTX A6000]                                                               | 1         | 1.69%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1         | 1.69%   |
| Matrox Electronics Systems MGA G200EH                                                    | 1         | 1.69%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 1         | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 1         | 1.69%   |
| Intel Tiger Lake-H GT1 [UHD Graphics]                                                    | 1         | 1.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 1.69%   |
| Intel RocketLake-S GT1 [UHD Graphics P750]                                               | 1         | 1.69%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 1         | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 1.69%   |
| Intel HD Graphics 615                                                                    | 1         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.69%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.69%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 1         | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 1         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 1.69%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.69%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 1.69%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 1         | 1.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 22        | 38.6%   |
| 1 x AMD        | 13        | 22.81%  |
| 1 x Nvidia     | 8         | 14.04%  |
| Intel + Nvidia | 4         | 7.02%   |
| 1 x ASPEED     | 4         | 7.02%   |
| 1 x Matrox     | 3         | 5.26%   |
| Other          | 2         | 3.51%   |
| 1 x Red Hat    | 1         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 43        | 75.44%  |
| Unknown     | 10        | 17.54%  |
| Proprietary | 4         | 7.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 64.91%  |
| 0.01-0.5   | 7         | 12.28%  |
| 1.01-2.0   | 5         | 8.77%   |
| 7.01-8.0   | 3         | 5.26%   |
| 3.01-4.0   | 2         | 3.51%   |
| 32.01-64.0 | 1         | 1.75%   |
| 5.01-6.0   | 1         | 1.75%   |
| 0.51-1.0   | 1         | 1.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 7         | 15.22%  |
| Samsung Electronics     | 6         | 13.04%  |
| LG Display              | 6         | 13.04%  |
| Chimei Innolux          | 4         | 8.7%    |
| BOE                     | 3         | 6.52%   |
| Sharp                   | 2         | 4.35%   |
| InfoVision              | 2         | 4.35%   |
| Goldstar                | 2         | 4.35%   |
| Dell                    | 2         | 4.35%   |
| BenQ                    | 2         | 4.35%   |
| ViewSonic               | 1         | 2.17%   |
| TopView                 | 1         | 2.17%   |
| STD                     | 1         | 2.17%   |
| Seiki                   | 1         | 2.17%   |
| Philips                 | 1         | 2.17%   |
| PANDA                   | 1         | 2.17%   |
| Medion                  | 1         | 2.17%   |
| Lenovo                  | 1         | 2.17%   |
| Chi Mei Optoelectronics | 1         | 2.17%   |
| AOC                     | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 2         | 4.26%   |
| ViewSonic VX2233wm-1 VSC1D22 1920x1080 477x268mm 21.5-inch               | 1         | 2.13%   |
| TopView HD TV TOPC37E 1920x1080 700x390mm 31.5-inch                      | 1         | 2.13%   |
| STD HDMI TV STD00C7 1360x768 698x392mm 31.5-inch                         | 1         | 2.13%   |
| Sharp LCD Monitor SHP146B 3200x1800 294x165mm 13.3-inch                  | 1         | 2.13%   |
| Sharp LC-32LB480U SHP3263 1920x1080 698x392mm 31.5-inch                  | 1         | 2.13%   |
| Seiki SC32HT04 SEK1366 1366x768 700x390mm 31.5-inch                      | 1         | 2.13%   |
| Samsung Electronics SyncMaster SAM021B 1400x1050 408x300mm 19.9-inch     | 1         | 2.13%   |
| Samsung Electronics S27H65x SAM0E1D 1920x1080 598x336mm 27.0-inch        | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch    | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 2.13%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch       | 1         | 2.13%   |
| Philips 19B PHL0879 1280x1024 376x301mm 19.0-inch                        | 1         | 2.13%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 1         | 2.13%   |
| Medion MD7212AS MED4971 1280x1024 359x287mm 18.1-inch                    | 1         | 2.13%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD042D 1920x1080 294x165mm 13.3-inch             | 1         | 2.13%   |
| LG Display LCD Monitor LGD034A 1366x768 345x194mm 15.6-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 2.13%   |
| LG Display LCD Monitor LGD02A5 1366x768 345x194mm 15.6-inch              | 1         | 2.13%   |
| Lenovo L24q-10 LEN65CF 2560x1440 527x296mm 23.8-inch                     | 1         | 2.13%   |
| InfoVision LCD Monitor IVO3D41 1920x1080 344x194mm 15.5-inch             | 1         | 2.13%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 1         | 2.13%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 1         | 2.13%   |
| Goldstar 22EA53 GSM59A6 1920x1080 477x268mm 21.5-inch                    | 1         | 2.13%   |
| Dell U2410 DELF015 1920x1200 518x324mm 24.1-inch                         | 1         | 2.13%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1510 1920x1080 344x193mm 15.5-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch         | 1         | 2.13%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 1         | 2.13%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 1         | 2.13%   |
| BOE LCD Monitor BOE09BA 2560x1600 345x215mm 16.0-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 1         | 2.13%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                    | 1         | 2.13%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 1         | 2.13%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                        | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 26        | 55.32%  |
| 1366x768 (WXGA)   | 9         | 19.15%  |
| 1280x1024 (SXGA)  | 3         | 6.38%   |
| 3840x2160 (4K)    | 2         | 4.26%   |
| 3200x1800 (QHD+)  | 1         | 2.13%   |
| 2560x1600         | 1         | 2.13%   |
| 2560x1440 (QHD)   | 1         | 2.13%   |
| 2560x1080         | 1         | 2.13%   |
| 1920x1200 (WUXGA) | 1         | 2.13%   |
| 1600x900 (HD+)    | 1         | 2.13%   |
| 1400x1050         | 1         | 2.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 13        | 27.66%  |
| 14     | 7         | 14.89%  |
| 31     | 4         | 8.51%   |
| 24     | 4         | 8.51%   |
| 13     | 4         | 8.51%   |
| 21     | 3         | 6.38%   |
| 27     | 2         | 4.26%   |
| 19     | 2         | 4.26%   |
| 17     | 2         | 4.26%   |
| 11     | 2         | 4.26%   |
| 34     | 1         | 2.13%   |
| 20     | 1         | 2.13%   |
| 18     | 1         | 2.13%   |
| 16     | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 22        | 46.81%  |
| 501-600     | 6         | 12.77%  |
| 351-400     | 5         | 10.64%  |
| 201-300     | 5         | 10.64%  |
| 601-700     | 4         | 8.51%   |
| 401-500     | 4         | 8.51%   |
| 701-800     | 1         | 2.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 37        | 84.09%  |
| 5/4   | 2         | 4.55%   |
| 16/10 | 2         | 4.55%   |
| 6/5   | 1         | 2.27%   |
| 4/3   | 1         | 2.27%   |
| 21/9  | 1         | 2.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 13        | 27.66%  |
| 81-90          | 8         | 17.02%  |
| 151-200        | 7         | 14.89%  |
| 351-500        | 5         | 10.64%  |
| 71-80          | 3         | 6.38%   |
| 201-250        | 3         | 6.38%   |
| 51-60          | 2         | 4.26%   |
| 301-350        | 2         | 4.26%   |
| 121-130        | 2         | 4.26%   |
| 251-300        | 1         | 2.13%   |
| 111-120        | 1         | 2.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 17        | 37.78%  |
| 51-100        | 13        | 28.89%  |
| 101-120       | 9         | 20%     |
| More than 240 | 3         | 6.67%   |
| 161-240       | 2         | 4.44%   |
| 1-50          | 1         | 2.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 35        | 61.4%   |
| 0     | 14        | 24.56%  |
| 2     | 8         | 14.04%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 29        | 36.71%  |
| Realtek Semiconductor | 18        | 22.78%  |
| Qualcomm Atheros      | 9         | 11.39%  |
| Broadcom              | 7         | 8.86%   |
| Broadcom Limited      | 3         | 3.8%    |
| TP-Link               | 2         | 2.53%   |
| Standard Microsystems | 2         | 2.53%   |
| Mellanox Technologies | 2         | 2.53%   |
| Insyde Software       | 2         | 2.53%   |
| Sierra Wireless       | 1         | 1.27%   |
| Samsung Electronics   | 1         | 1.27%   |
| Ralink Technology     | 1         | 1.27%   |
| Ralink                | 1         | 1.27%   |
| MediaTek              | 1         | 1.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 14        | 14.29%  |
| Intel I350 Gigabit Network Connection                             | 3         | 3.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.06%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 3         | 3.06%   |
| Standard Microsystems Ethernet controller                         | 2         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 2.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 2.04%   |
| Intel Wireless 7260                                               | 2         | 2.04%   |
| Intel Wireless 3165                                               | 2         | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 2.04%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 2.04%   |
| Intel I210 Gigabit Network Connection                             | 2         | 2.04%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 2.04%   |
| Insyde Software RNDIS/Ethernet Gadget                             | 2         | 2.04%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 1.02%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 1.02%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 1.02%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 1.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.02%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 1.02%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                         | 1         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.02%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 1.02%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                           | 1         | 1.02%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 1.02%   |
| MediaTek KINGKONG_MINI                                            | 1         | 1.02%   |
| Intel Wireless 8265 / 8275                                        | 1         | 1.02%   |
| Intel Wireless 8260                                               | 1         | 1.02%   |
| Intel Wireless 7265                                               | 1         | 1.02%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 18        | 47.37%  |
| Qualcomm Atheros      | 8         | 21.05%  |
| Realtek Semiconductor | 5         | 13.16%  |
| Broadcom              | 2         | 5.26%   |
| TP-Link               | 1         | 2.63%   |
| Sierra Wireless       | 1         | 2.63%   |
| Ralink Technology     | 1         | 2.63%   |
| Ralink                | 1         | 2.63%   |
| Broadcom Limited      | 1         | 2.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH-LP CNVi WiFi                          | 3         | 7.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 2         | 5.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2         | 5.26%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter           | 2         | 5.26%   |
| Intel Wireless 7260                                        | 2         | 5.26%   |
| Intel Wireless 3165                                        | 2         | 5.26%   |
| Intel Wi-Fi 6 AX201                                        | 2         | 5.26%   |
| Intel Wi-Fi 6 AX200                                        | 2         | 5.26%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 1         | 2.63%   |
| Sierra Wireless EM7345 4G LTE                              | 1         | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 1         | 2.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 1         | 2.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                | 1         | 2.63%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 2.63%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 1         | 2.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 1         | 2.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 1         | 2.63%   |
| Intel Wireless 8265 / 8275                                 | 1         | 2.63%   |
| Intel Wireless 8260                                        | 1         | 2.63%   |
| Intel Wireless 7265                                        | 1         | 2.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 1         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                             | 1         | 2.63%   |
| Intel Centrino Wireless-N 2230                             | 1         | 2.63%   |
| Intel Centrino Ultimate-N 6300                             | 1         | 2.63%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                    | 1         | 2.63%   |
| Broadcom BCM43225 802.11b/g/n                              | 1         | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 1         | 2.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 17        | 32.69%  |
| Intel                 | 17        | 32.69%  |
| Broadcom              | 5         | 9.62%   |
| Standard Microsystems | 2         | 3.85%   |
| Qualcomm Atheros      | 2         | 3.85%   |
| Mellanox Technologies | 2         | 3.85%   |
| Insyde Software       | 2         | 3.85%   |
| Broadcom Limited      | 2         | 3.85%   |
| TP-Link               | 1         | 1.92%   |
| Samsung Electronics   | 1         | 1.92%   |
| MediaTek              | 1         | 1.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 14        | 23.33%  |
| Intel I350 Gigabit Network Connection                                 | 3         | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3         | 5%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                      | 3         | 5%      |
| Standard Microsystems Ethernet controller                             | 2         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2         | 3.33%   |
| Intel I210 Gigabit Network Connection                                 | 2         | 3.33%   |
| Intel Ethernet Connection (10) I219-V                                 | 2         | 3.33%   |
| Insyde Software RNDIS/Ethernet Gadget                                 | 2         | 3.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]       | 1         | 1.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)           | 1         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                     | 1         | 1.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1         | 1.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1         | 1.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller             | 1         | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                         | 1         | 1.67%   |
| Mellanox MT28800 Family [ConnectX-5 Ex]                               | 1         | 1.67%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                 | 1         | 1.67%   |
| MediaTek KINGKONG_MINI                                                | 1         | 1.67%   |
| Intel Ethernet Controller X550                                        | 1         | 1.67%   |
| Intel Ethernet Controller I225-V                                      | 1         | 1.67%   |
| Intel Ethernet Connection I219-LM                                     | 1         | 1.67%   |
| Intel Ethernet Connection I218-LM                                     | 1         | 1.67%   |
| Intel Ethernet Connection (7) I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (6) I219-V                                  | 1         | 1.67%   |
| Intel Ethernet Connection (3) I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                                 | 1         | 1.67%   |
| Intel Ethernet Connection (14) I219-LM                                | 1         | 1.67%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                              | 1         | 1.67%   |
| Intel 82574L Gigabit Network Connection                               | 1         | 1.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                     | 1         | 1.67%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                      | 1         | 1.67%   |
| Broadcom Limited NetXtreme II BCM5709 Gigabit Ethernet                | 1         | 1.67%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe               | 1         | 1.67%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1         | 1.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 45        | 55.56%  |
| WiFi     | 36        | 44.44%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 28        | 51.85%  |
| WiFi     | 26        | 48.15%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 29        | 50.88%  |
| 1     | 19        | 33.33%  |
| 4     | 3         | 5.26%   |
| 0     | 3         | 5.26%   |
| 5     | 2         | 3.51%   |
| 6     | 1         | 1.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 46        | 79.31%  |
| Yes  | 12        | 20.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 17        | 50%     |
| Qualcomm Atheros Communications | 6         | 17.65%  |
| Realtek Semiconductor           | 4         | 11.76%  |
| Broadcom                        | 3         | 8.82%   |
| Cambridge Silicon Radio         | 2         | 5.88%   |
| Foxconn / Hon Hai               | 1         | 2.94%   |
| ASUSTek Computer                | 1         | 2.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 7         | 20.59%  |
| Intel AX201 Bluetooth                               | 6         | 17.65%  |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 11.76%  |
| Realtek Bluetooth Radio                             | 3         | 8.82%   |
| Intel AX200 Bluetooth                               | 2         | 5.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 5.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 2.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 2.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 2.94%   |
| Intel AX210 Bluetooth                               | 1         | 2.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 2.94%   |
| Broadcom HP Portable SoftSailing                    | 1         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 2.94%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 2.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 2.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 33        | 51.56%  |
| AMD                  | 15        | 23.44%  |
| Nvidia               | 11        | 17.19%  |
| C-Media Electronics  | 2         | 3.13%   |
| Giga-Byte Technology | 1         | 1.56%   |
| Conrad Electronic SE | 1         | 1.56%   |
| Apple                | 1         | 1.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 7.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 5.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 3.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 3.8%    |
| Intel 8 Series HD Audio Controller                                                                | 3         | 3.8%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 3.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 3.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 3.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 2.53%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 2.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 2.53%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 2.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 2.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 2.53%   |
| AMD High Definition Audio Controller                                                              | 2         | 2.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 2.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 1.27%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 1.27%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 1.27%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 1         | 1.27%   |
| Nvidia Audio device                                                                               | 1         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 1.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1         | 1.27%   |
| Intel Lewisburg MROM 0                                                                            | 1         | 1.27%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 1.27%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 1         | 1.27%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 1         | 1.27%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 1.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 1.27%   |
| Giga-Byte Technology USB Audio                                                                    | 1         | 1.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 10        | 25.64%  |
| Kingston            | 8         | 20.51%  |
| Micron Technology   | 7         | 17.95%  |
| SK hynix            | 4         | 10.26%  |
| Crucial             | 4         | 10.26%  |
| Unknown             | 2         | 5.13%   |
| Timetec             | 1         | 2.56%   |
| QEMU                | 1         | 2.56%   |
| Hewlett-Packard     | 1         | 2.56%   |
| Elpida              | 1         | 2.56%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 2         | 4.55%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                      | 1         | 2.27%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.27%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                             | 1         | 2.27%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 2.27%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                 | 1         | 2.27%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s                     | 1         | 2.27%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s              | 1         | 2.27%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s          | 1         | 2.27%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                               | 1         | 2.27%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s                       | 1         | 2.27%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                              | 1         | 2.27%   |
| Samsung RAM Module 16GB DIMM DDR4 2667MT/s                                | 1         | 2.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s                    | 1         | 2.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| Samsung RAM M393A4G43AB3-CWE 32GB DIMM DDR4 3200MT/s                      | 1         | 2.27%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s                      | 1         | 2.27%   |
| QEMU RAM Module 8GB DIMM RAM                                              | 1         | 2.27%   |
| Micron RAM 9ASF2G72AZ-3G2B1 16GB DIMM DDR4 3200MT/s                       | 1         | 2.27%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.27%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 1         | 2.27%   |
| Micron RAM 36KSF2G72PZ-1G6E1 16GB DIMM DDR3 1600MT/s                      | 1         | 2.27%   |
| Micron RAM 36ASF8G72PZ-3G2E1 64GB DIMM DDR4 3200MT/s                      | 1         | 2.27%   |
| Kingston RAM LV32D4S2S8HD-8 8192MB SODIMM DDR4 3200MT/s                   | 1         | 2.27%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s                      | 1         | 2.27%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                     | 1         | 2.27%   |
| Kingston RAM ACR256X64D3U1333C9 2GB DIMM DDR3 1333MT/s                    | 1         | 2.27%   |
| Kingston RAM 9965742-029.B00G 32GB DIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| Kingston RAM 9965640-033.C00G 32GB DIMM DDR4 2667MT/s                     | 1         | 2.27%   |
| Kingston RAM 787878787878787878787878787878787878 2GB SODIMM DDR2 667MT/s | 1         | 2.27%   |
| Kingston RAM 272727272727272727272727272727272727 2GB SODIMM DDR2 667MT/s | 1         | 2.27%   |
| HP RAM 712384-081 32GB DIMM DDR3 1866MT/s                                 | 1         | 2.27%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 1         | 2.27%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s                    | 1         | 2.27%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s                    | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 22        | 62.86%  |
| DDR3    | 8         | 22.86%  |
| LPDDR3  | 2         | 5.71%   |
| RAM     | 1         | 2.86%   |
| DDR2    | 1         | 2.86%   |
| Unknown | 1         | 2.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 17        | 48.57%  |
| SODIMM       | 15        | 42.86%  |
| Row Of Chips | 3         | 8.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 13        | 36.11%  |
| 4096  | 7         | 19.44%  |
| 32768 | 6         | 16.67%  |
| 16384 | 6         | 16.67%  |
| 65536 | 2         | 5.56%   |
| 2048  | 2         | 5.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 14        | 36.84%  |
| 1600    | 7         | 18.42%  |
| 2667    | 6         | 15.79%  |
| 2133    | 2         | 5.26%   |
| 1866    | 2         | 5.26%   |
| 1333    | 2         | 5.26%   |
| 3600    | 1         | 2.63%   |
| 3466    | 1         | 2.63%   |
| 2400    | 1         | 2.63%   |
| 667     | 1         | 2.63%   |
| Unknown | 1         | 2.63%   |

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
| Chicony Electronics                    | 9         | 29.03%  |
| IMC Networks                           | 5         | 16.13%  |
| Acer                                   | 4         | 12.9%   |
| Suyin                                  | 2         | 6.45%   |
| Realtek Semiconductor                  | 2         | 6.45%   |
| Microdia                               | 2         | 6.45%   |
| Luxvisions Innotech Limited            | 2         | 6.45%   |
| Logitech                               | 2         | 6.45%   |
| Syntek                                 | 1         | 3.23%   |
| Creative Technology                    | 1         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 3.23%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                  | 4         | 12.12%  |
| Chicony Integrated HP HD Webcam                                 | 2         | 6.06%   |
| Chicony HP Truevision HD                                        | 2         | 6.06%   |
| Acer Integrated Camera                                          | 2         | 6.06%   |
| Syntek Integrated Camera                                        | 1         | 3.03%   |
| Suyin HD WebCam                                                 | 1         | 3.03%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 1         | 3.03%   |
| Realtek Integrated Webcam HD                                    | 1         | 3.03%   |
| Realtek EasyCamera                                              | 1         | 3.03%   |
| Microdia USB 2.0 Camera                                         | 1         | 3.03%   |
| Microdia Integrated_Webcam_HD                                   | 1         | 3.03%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 1         | 3.03%   |
| Luxvisions Innotech Limited HP HD Camera                        | 1         | 3.03%   |
| Logitech Webcam C120                                            | 1         | 3.03%   |
| Logitech Webcam B500                                            | 1         | 3.03%   |
| Logitech QuickCam Vision Pro                                    | 1         | 3.03%   |
| IMC Networks USB2.0 HD IR UVC WebCam                            | 1         | 3.03%   |
| Creative Live! Cam Chat HD [VF0700]                             | 1         | 3.03%   |
| Chicony TOSHIBA Web Camera - HD                                 | 1         | 3.03%   |
| Chicony Lenovo EasyCamera                                       | 1         | 3.03%   |
| Chicony Integrated RGB Camera                                   | 1         | 3.03%   |
| Chicony EasyCamera                                              | 1         | 3.03%   |
| Chicony 8M Camera                                               | 1         | 3.03%   |
| Chicony 720p HD Camera                                          | 1         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) HP True Vision HD Camera | 1         | 3.03%   |
| Acer USB Camera                                                 | 1         | 3.03%   |
| Acer Lenovo EasyCamera                                          | 1         | 3.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 66.67%  |
| Synaptics             | 2         | 22.22%  |
| Elan Microelectronics | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS491                           | 2         | 22.22%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor | 1         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 11.11%  |
| Validity Sensors Fingerprint scanner              | 1         | 11.11%  |
| Synaptics WBDI                                    | 1         | 11.11%  |
| Synaptics UWP WBDI Device                         | 1         | 11.11%  |
| Elan ELAN:ARM-M4                                  | 1         | 11.11%  |

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
| 0     | 33        | 57.89%  |
| 1     | 19        | 33.33%  |
| 2     | 2         | 3.51%   |
| 7     | 1         | 1.75%   |
| 5     | 1         | 1.75%   |
| 3     | 1         | 1.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 26.47%  |
| Graphics card            | 7         | 20.59%  |
| Net/wireless             | 3         | 8.82%   |
| Multimedia controller    | 3         | 8.82%   |
| Sound                    | 2         | 5.88%   |
| Net/ethernet             | 2         | 5.88%   |
| Unassigned class         | 1         | 2.94%   |
| Storage/raid             | 1         | 2.94%   |
| Storage/ide              | 1         | 2.94%   |
| Firewire controller      | 1         | 2.94%   |
| Communication controller | 1         | 2.94%   |
| Chipcard                 | 1         | 2.94%   |
| Camera                   | 1         | 2.94%   |
| Bluetooth                | 1         | 2.94%   |

