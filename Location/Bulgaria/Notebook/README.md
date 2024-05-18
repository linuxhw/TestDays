Linux in Bulgaria - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

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

Total: 1184

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G6            | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| Lenovo        | IdeaPad S12 20021,2959      | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| Lenovo        | ThinkPad X230 2325BK0       | [0c39b2e745](https://linux-hardware.org/?probe=0c39b2e745) | May 05, 2024 |
| Dell          | Inspiron 11-3162            | [ccf99ca586](https://linux-hardware.org/?probe=ccf99ca586) | May 05, 2024 |
| Lenovo        | ThinkPad X270 20HMS34L00    | [dcc424b27d](https://linux-hardware.org/?probe=dcc424b27d) | May 04, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [c03d3e0508](https://linux-hardware.org/?probe=c03d3e0508) | May 03, 2024 |
| Toshiba       | Satellite P200              | [f9f88ee996](https://linux-hardware.org/?probe=f9f88ee996) | May 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [01432a3384](https://linux-hardware.org/?probe=01432a3384) | Apr 23, 2024 |
| Allview       | Allbook J                   | [77d90c2a69](https://linux-hardware.org/?probe=77d90c2a69) | Apr 23, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [e0c405894c](https://linux-hardware.org/?probe=e0c405894c) | Apr 21, 2024 |
| Toshiba       | Satellite C850-124          | [b580358635](https://linux-hardware.org/?probe=b580358635) | Apr 20, 2024 |
| Unknown       | Unknown                     | [7ee99946ca](https://linux-hardware.org/?probe=7ee99946ca) | Apr 19, 2024 |
| Acer          | Aspire 7738                 | [dc56784ca7](https://linux-hardware.org/?probe=dc56784ca7) | Apr 19, 2024 |
| HP            | ProBook 640 G1              | [a5d4162d2f](https://linux-hardware.org/?probe=a5d4162d2f) | Apr 19, 2024 |
| Allview       | Allbook J                   | [a106195c34](https://linux-hardware.org/?probe=a106195c34) | Apr 18, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [2d02eae5ec](https://linux-hardware.org/?probe=2d02eae5ec) | Apr 13, 2024 |
| Lenovo        | ThinkPad T440 20B7A0MN04    | [2244374672](https://linux-hardware.org/?probe=2244374672) | Apr 13, 2024 |
| HP            | Pavilion dv8                | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e5830d8754](https://linux-hardware.org/?probe=e5830d8754) | Apr 07, 2024 |
| Acer          | Predator PH315-53           | [4c8bbd0426](https://linux-hardware.org/?probe=4c8bbd0426) | Apr 07, 2024 |
| Lenovo        | Unknown                     | [18961ee7a8](https://linux-hardware.org/?probe=18961ee7a8) | Apr 07, 2024 |
| Lenovo        | Unknown                     | [d74a81067e](https://linux-hardware.org/?probe=d74a81067e) | Apr 07, 2024 |
| Acer          | Aspire V5-572G              | [ca5e1f767e](https://linux-hardware.org/?probe=ca5e1f767e) | Apr 04, 2024 |
| ASUSTek       | X55VD                       | [bc22ba01de](https://linux-hardware.org/?probe=bc22ba01de) | Apr 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [708291ee28](https://linux-hardware.org/?probe=708291ee28) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [449d0ad45b](https://linux-hardware.org/?probe=449d0ad45b) | Mar 31, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [431002bc2d](https://linux-hardware.org/?probe=431002bc2d) | Mar 30, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [3d2abf7e0d](https://linux-hardware.org/?probe=3d2abf7e0d) | Mar 30, 2024 |
| Dell          | Latitude 5580               | [db427c180d](https://linux-hardware.org/?probe=db427c180d) | Mar 28, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [deae5b6cdf](https://linux-hardware.org/?probe=deae5b6cdf) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | [602d79d663](https://linux-hardware.org/?probe=602d79d663) | Mar 27, 2024 |
| HP            | Compaq CQ58                 | [bfe7fd8a2e](https://linux-hardware.org/?probe=bfe7fd8a2e) | Mar 26, 2024 |
| HP            | Compaq CQ58                 | [806d659258](https://linux-hardware.org/?probe=806d659258) | Mar 26, 2024 |
| HP            | EliteBook 2540p             | [99983f8fbf](https://linux-hardware.org/?probe=99983f8fbf) | Mar 25, 2024 |
| Dell          | Precision M4700             | [212d29f26d](https://linux-hardware.org/?probe=212d29f26d) | Mar 21, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [f8fa83eaf5](https://linux-hardware.org/?probe=f8fa83eaf5) | Mar 20, 2024 |
| Acer          | Predator PT516-52s          | [86614957f2](https://linux-hardware.org/?probe=86614957f2) | Mar 17, 2024 |
| Lenovo        | ThinkPad X230 2325CL7       | [9bde6bc531](https://linux-hardware.org/?probe=9bde6bc531) | Mar 17, 2024 |
| ASUSTek       | X55VD                       | [a959f1dfec](https://linux-hardware.org/?probe=a959f1dfec) | Mar 17, 2024 |
| Lenovo        | G50-30 80G0                 | [3ec06d0273](https://linux-hardware.org/?probe=3ec06d0273) | Mar 16, 2024 |
| ASUSTek       | X541NA                      | [75bc4f3af5](https://linux-hardware.org/?probe=75bc4f3af5) | Mar 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [fbc1335ccc](https://linux-hardware.org/?probe=fbc1335ccc) | Mar 12, 2024 |
| Acer          | Aspire A315-59              | [edf84e43ee](https://linux-hardware.org/?probe=edf84e43ee) | Mar 11, 2024 |
| HP            | 255 G8 Notebook PC          | [ca3f8b06ab](https://linux-hardware.org/?probe=ca3f8b06ab) | Mar 10, 2024 |
| Allview       | Allbook J                   | [58b6452c8f](https://linux-hardware.org/?probe=58b6452c8f) | Mar 08, 2024 |
| Dell          | XPS 15 9560                 | [898154cbf9](https://linux-hardware.org/?probe=898154cbf9) | Mar 05, 2024 |
| HP            | ZBook Studio G5             | [208ce1e5fd](https://linux-hardware.org/?probe=208ce1e5fd) | Mar 04, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b957a4b5d8](https://linux-hardware.org/?probe=b957a4b5d8) | Mar 03, 2024 |
| Allview       | Allbook J                   | [dd1b4469c1](https://linux-hardware.org/?probe=dd1b4469c1) | Mar 01, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | [935b64ed30](https://linux-hardware.org/?probe=935b64ed30) | Feb 29, 2024 |
| MSI           | Thin GF63 12UDX             | [648c7d0aa4](https://linux-hardware.org/?probe=648c7d0aa4) | Feb 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [27c2f0156e](https://linux-hardware.org/?probe=27c2f0156e) | Feb 25, 2024 |
| MSI           | Modern 14 B11MO             | [6f5a4e6e1e](https://linux-hardware.org/?probe=6f5a4e6e1e) | Feb 23, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [e2780e976f](https://linux-hardware.org/?probe=e2780e976f) | Feb 18, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [95978292b2](https://linux-hardware.org/?probe=95978292b2) | Feb 18, 2024 |
| Dell          | Latitude E5470              | [4f6f03415f](https://linux-hardware.org/?probe=4f6f03415f) | Feb 12, 2024 |
| Acer          | Predator PT516-52s          | [d271f4b0ca](https://linux-hardware.org/?probe=d271f4b0ca) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | [a3255728e7](https://linux-hardware.org/?probe=a3255728e7) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | [aa78cf8909](https://linux-hardware.org/?probe=aa78cf8909) | Feb 12, 2024 |
| Dell          | Vostro 3580                 | [1d2758029b](https://linux-hardware.org/?probe=1d2758029b) | Feb 08, 2024 |
| Dell          | Vostro 3580                 | [0b028612c5](https://linux-hardware.org/?probe=0b028612c5) | Feb 08, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | [d01b52dd20](https://linux-hardware.org/?probe=d01b52dd20) | Feb 05, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | [1e6645fdc9](https://linux-hardware.org/?probe=1e6645fdc9) | Feb 05, 2024 |
| Acer          | Swift SF314-43              | [e87efb031b](https://linux-hardware.org/?probe=e87efb031b) | Feb 02, 2024 |
| HP            | Pavilion Notebook           | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| HP            | 255 G8 Notebook PC          | [62254b1636](https://linux-hardware.org/?probe=62254b1636) | Jan 31, 2024 |
| Acer          | Aspire A315-41              | [a78d79030e](https://linux-hardware.org/?probe=a78d79030e) | Jan 30, 2024 |
| Dell          | Studio 1747                 | [b43d9b4a13](https://linux-hardware.org/?probe=b43d9b4a13) | Jan 29, 2024 |
| Dell          | Studio 1747                 | [9fe0b059bc](https://linux-hardware.org/?probe=9fe0b059bc) | Jan 29, 2024 |
| HP            | Victus by Gaming Laptop ... | [49e891b67d](https://linux-hardware.org/?probe=49e891b67d) | Jan 28, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [be74f076bd](https://linux-hardware.org/?probe=be74f076bd) | Jan 23, 2024 |
| Dell          | Latitude 7280               | [21e6e4a581](https://linux-hardware.org/?probe=21e6e4a581) | Jan 22, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [36cb9057d7](https://linux-hardware.org/?probe=36cb9057d7) | Jan 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [f6204361d0](https://linux-hardware.org/?probe=f6204361d0) | Jan 19, 2024 |
| Apple         | MacBookAir6,2               | [12539bda5e](https://linux-hardware.org/?probe=12539bda5e) | Jan 19, 2024 |
| HP            | 255 G8 Notebook PC          | [667df4a998](https://linux-hardware.org/?probe=667df4a998) | Jan 17, 2024 |
| HP            | 255 G3                      | [7f8af802a0](https://linux-hardware.org/?probe=7f8af802a0) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [82f1c7e4f3](https://linux-hardware.org/?probe=82f1c7e4f3) | Jan 14, 2024 |
| HP            | EliteBook 745 G5            | [64314a5149](https://linux-hardware.org/?probe=64314a5149) | Jan 13, 2024 |
| Dell          | Latitude 5431               | [45d7b96fb3](https://linux-hardware.org/?probe=45d7b96fb3) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Dell          | Latitude E7470              | [2d36d1a363](https://linux-hardware.org/?probe=2d36d1a363) | Jan 11, 2024 |
| MSI           | Katana GF66 12UG            | [d4affacb08](https://linux-hardware.org/?probe=d4affacb08) | Jan 08, 2024 |
| Dell          | Latitude 7280               | [9557a37753](https://linux-hardware.org/?probe=9557a37753) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [26ec173956](https://linux-hardware.org/?probe=26ec173956) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [514f7e46c3](https://linux-hardware.org/?probe=514f7e46c3) | Jan 04, 2024 |
| Dell          | Latitude D630               | [e48315d3aa](https://linux-hardware.org/?probe=e48315d3aa) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [88f364d196](https://linux-hardware.org/?probe=88f364d196) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | [15ae58d88c](https://linux-hardware.org/?probe=15ae58d88c) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | [c9312cc676](https://linux-hardware.org/?probe=c9312cc676) | Jan 03, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Sony          | VGN-CS21Z_Q                 | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Dell          | Precision 5560              | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| Lenovo        | G570 20079                  | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| Lenovo        | G50-30 80G0                 | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| Lenovo        | G580 20150                  | [c6c8d22a8e](https://linux-hardware.org/?probe=c6c8d22a8e) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [c71041fa59](https://linux-hardware.org/?probe=c71041fa59) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| Dell          | Vostro 3400                 | [0841e29863](https://linux-hardware.org/?probe=0841e29863) | Dec 10, 2023 |
| HP            | EliteBook 830 G5            | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| Lenovo        | 3000 G410                   | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| MSI           | Modern 14 B4MW              | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [80e09b727b](https://linux-hardware.org/?probe=80e09b727b) | Nov 30, 2023 |
| HP            | EliteBook 8530p             | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DV0Y    | [c68289cf4c](https://linux-hardware.org/?probe=c68289cf4c) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Lenovo        | Unknown                     | [2ab4754aa8](https://linux-hardware.org/?probe=2ab4754aa8) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| Acer          | Aspire 5750G                | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Lenovo        | ThinkPad X270 20HMS76D02    | [7da50d5ad3](https://linux-hardware.org/?probe=7da50d5ad3) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Apple         | MacBookPro6,2               | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [4a2561319d](https://linux-hardware.org/?probe=4a2561319d) | Nov 08, 2023 |
| Lenovo        | ThinkPad X230 23252EG       | [143a351fe0](https://linux-hardware.org/?probe=143a351fe0) | Nov 08, 2023 |
| Valve         | Jupiter                     | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Y500 20193          | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c06d2e60fc](https://linux-hardware.org/?probe=c06d2e60fc) | Nov 01, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [09b312b58c](https://linux-hardware.org/?probe=09b312b58c) | Oct 30, 2023 |
| Acer          | Aspire 5810T                | [9b65c56faa](https://linux-hardware.org/?probe=9b65c56faa) | Oct 29, 2023 |
| Sony          | SVE1712V1EB                 | [3b8803286b](https://linux-hardware.org/?probe=3b8803286b) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | [63963cbe04](https://linux-hardware.org/?probe=63963cbe04) | Oct 25, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [9c136d661d](https://linux-hardware.org/?probe=9c136d661d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| Dell          | Latitude E5410              | [b1559718de](https://linux-hardware.org/?probe=b1559718de) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| ASUSTek       | K73SV                       | [63341aa786](https://linux-hardware.org/?probe=63341aa786) | Oct 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ec7aee0455](https://linux-hardware.org/?probe=ec7aee0455) | Oct 10, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e06a9dcd7d](https://linux-hardware.org/?probe=e06a9dcd7d) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| HP            | 635                         | [ef474a26d0](https://linux-hardware.org/?probe=ef474a26d0) | Oct 07, 2023 |
| Dell          | Vostro 15 3510              | [233fe08ffd](https://linux-hardware.org/?probe=233fe08ffd) | Oct 07, 2023 |
| ONDA          | V80 PLUS                    | [8651e33f83](https://linux-hardware.org/?probe=8651e33f83) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5584c834bc](https://linux-hardware.org/?probe=5584c834bc) | Oct 04, 2023 |
| HP            | 15                          | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| HP            | 15                          | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Dell          | Precision 5510              | [34ddd03339](https://linux-hardware.org/?probe=34ddd03339) | Sep 25, 2023 |
| Toshiba       | Satellite A300              | [03aa0d1366](https://linux-hardware.org/?probe=03aa0d1366) | Sep 25, 2023 |
| Acer          | Nitro AN515-58              | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Acer          | Extensa 5635ZG              | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Timi          | A30                         | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [744362d446](https://linux-hardware.org/?probe=744362d446) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [82d4f51421](https://linux-hardware.org/?probe=82d4f51421) | Sep 12, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ae29792d70](https://linux-hardware.org/?probe=ae29792d70) | Sep 11, 2023 |
| Dell          | Latitude 5431               | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| Dell          | Latitude 5431               | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| MSI           | Bravo 15 C7VF               | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [245964564e](https://linux-hardware.org/?probe=245964564e) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| ASUSTek       | K55VD                       | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6dc701c67d](https://linux-hardware.org/?probe=6dc701c67d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| Dell          | Precision M4600             | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| Dell          | Studio 1747                 | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| MSI           | GL65 9SE                    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Acer          | Aspire 5755G                | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| Lenovo        | ThinkPad X395 20NL000HGE    | [3dacfd8a02](https://linux-hardware.org/?probe=3dacfd8a02) | Aug 16, 2023 |
| Dell          | Latitude E4300              | [7c153c96f5](https://linux-hardware.org/?probe=7c153c96f5) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Dell          | Latitude E4300              | [ec4bac7b02](https://linux-hardware.org/?probe=ec4bac7b02) | Aug 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| Dell          | Precision M4600             | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Dell          | Inspiron 15 3520            | [7723e84488](https://linux-hardware.org/?probe=7723e84488) | Aug 09, 2023 |
| Dell          | Latitude E4300              | [9ae3d19a62](https://linux-hardware.org/?probe=9ae3d19a62) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | Vostro 1700                 | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| Dell          | Precision 7750              | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| HP            | ProBook 4530s               | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| TUXEDO        | Gemini Gen2                 | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | 635                         | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| HP            | ProBook 6570b               | [0a74371e23](https://linux-hardware.org/?probe=0a74371e23) | Jul 18, 2023 |
| Dell          | Inspiron 3551               | [543382ea16](https://linux-hardware.org/?probe=543382ea16) | Jul 16, 2023 |
| Dell          | Inspiron 3551               | [74050e892f](https://linux-hardware.org/?probe=74050e892f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire A515-52G             | [639eb4733c](https://linux-hardware.org/?probe=639eb4733c) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Dell          | G15 5511                    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| HP            | Notebook                    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| Acer          | Aspire VN7-591G             | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Dell          | Latitude 3180               | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [3c0316ef92](https://linux-hardware.org/?probe=3c0316ef92) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Lenovo        | Unknown                     | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| Dell          | Vostro 3500                 | [3d694e1b9a](https://linux-hardware.org/?probe=3d694e1b9a) | Jun 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Dell          | Precision 7710              | [f1b57ded18](https://linux-hardware.org/?probe=f1b57ded18) | Jun 08, 2023 |
| Dell          | Latitude 3350               | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| Cube          | i16-L                       | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| HP            | Laptop 15-dw3xxx            | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Dell          | Inspiron 7577               | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Lenovo        | Unknown                     | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Dell          | Inspiron 1501               | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Dell          | Inspiron N5110              | [4280ce2bd4](https://linux-hardware.org/?probe=4280ce2bd4) | May 15, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Beelink       | BT3 PRO                     | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| MSI           | Modern 15 A5M               | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| Acer          | Aspire A515-51G             | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Dell          | Vostro 3500                 | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| Dell          | Latitude E4300              | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Dell          | Latitude E4300              | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| HP            | ProBook 4540s               | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [3b0ab63643](https://linux-hardware.org/?probe=3b0ab63643) | Apr 17, 2023 |
| Valve         | Jupiter                     | [f05e3341d3](https://linux-hardware.org/?probe=f05e3341d3) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Acer          | Aspire A515-57              | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Gigabyte      | G5 KF                       | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Dell          | Vostro 5620                 | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| HP            | Notebook                    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [90b9eaf3fe](https://linux-hardware.org/?probe=90b9eaf3fe) | Apr 02, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| Acer          | Aspire A515-51G             | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [88caf7c0d1](https://linux-hardware.org/?probe=88caf7c0d1) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Toshiba       | Satellite C850-140          | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| HP            | Pavilion g6                 | [abd4bb0963](https://linux-hardware.org/?probe=abd4bb0963) | Mar 21, 2023 |
| HP            | Pavilion g6                 | [4dcebf6a41](https://linux-hardware.org/?probe=4dcebf6a41) | Mar 21, 2023 |
| HP            | ProBook 6475b               | [1b7a5f385c](https://linux-hardware.org/?probe=1b7a5f385c) | Mar 18, 2023 |
| HP            | ProBook 6475b               | [0fd12da29b](https://linux-hardware.org/?probe=0fd12da29b) | Mar 18, 2023 |
| HP            | ProBook 6475b               | [701aca7f61](https://linux-hardware.org/?probe=701aca7f61) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | 255 G6 Notebook PC          | [47df31e0fb](https://linux-hardware.org/?probe=47df31e0fb) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [c14956dd2d](https://linux-hardware.org/?probe=c14956dd2d) | Mar 12, 2023 |
| Acer          | Aspire 5333                 | [214db069e4](https://linux-hardware.org/?probe=214db069e4) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [65c2aab8aa](https://linux-hardware.org/?probe=65c2aab8aa) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | [e03e243c84](https://linux-hardware.org/?probe=e03e243c84) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Dell          | Latitude E4300              | [3c777f1c07](https://linux-hardware.org/?probe=3c777f1c07) | Mar 10, 2023 |
| HP            | ProBook 6475b               | [be06cdc105](https://linux-hardware.org/?probe=be06cdc105) | Mar 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| ASUSTek       | X580VD                      | [f4b107fbf3](https://linux-hardware.org/?probe=f4b107fbf3) | Mar 02, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | [c068117b39](https://linux-hardware.org/?probe=c068117b39) | Mar 01, 2023 |
| Valve         | Jupiter                     | [df09052bac](https://linux-hardware.org/?probe=df09052bac) | Mar 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| HP            | Notebook                    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [4f7bbbdd28](https://linux-hardware.org/?probe=4f7bbbdd28) | Feb 24, 2023 |
| Google        | Astronaut                   | [71e8582f54](https://linux-hardware.org/?probe=71e8582f54) | Feb 22, 2023 |
| Google        | Astronaut                   | [4949e50dad](https://linux-hardware.org/?probe=4949e50dad) | Feb 22, 2023 |
| HP            | Notebook                    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Valve         | Jupiter                     | [74b6676de3](https://linux-hardware.org/?probe=74b6676de3) | Feb 19, 2023 |
| HP            | Notebook                    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| HP            | Notebook                    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| HP            | ProBook 6460b               | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Valve         | Jupiter                     | [1df562d2d8](https://linux-hardware.org/?probe=1df562d2d8) | Feb 13, 2023 |
| Dell          | Precision M4700             | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Dell          | Latitude E7470              | [9b58106fd6](https://linux-hardware.org/?probe=9b58106fd6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| Dell          | Precision M4700             | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| Dell          | Precision 5540              | [de6a1c523e](https://linux-hardware.org/?probe=de6a1c523e) | Jan 28, 2023 |
| HP            | ProBook 455 G1              | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| HP            | Pavilion g6                 | [c34bc63cb0](https://linux-hardware.org/?probe=c34bc63cb0) | Jan 24, 2023 |
| HP            | Pavilion g6                 | [a9a199e6f7](https://linux-hardware.org/?probe=a9a199e6f7) | Jan 24, 2023 |
| Dell          | Vostro 5620                 | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Acer          | Aspire A315-59              | [ca332b4905](https://linux-hardware.org/?probe=ca332b4905) | Jan 13, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| Google        | Kled                        | [6380ae012e](https://linux-hardware.org/?probe=6380ae012e) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| Dell          | Precision M6400             | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [be5212ebcc](https://linux-hardware.org/?probe=be5212ebcc) | Jan 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [c51bc128e2](https://linux-hardware.org/?probe=c51bc128e2) | Dec 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Valve         | Jupiter                     | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Dell          | Latitude E5410              | [969f85bfc3](https://linux-hardware.org/?probe=969f85bfc3) | Dec 21, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Valve         | Jupiter                     | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| Acer          | AO756                       | [ebc4d7cfcb](https://linux-hardware.org/?probe=ebc4d7cfcb) | Dec 16, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| Dell          | Vostro 5620                 | [6987aeacd5](https://linux-hardware.org/?probe=6987aeacd5) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Dell          | Precision 5510              | [f464385b16](https://linux-hardware.org/?probe=f464385b16) | Dec 13, 2022 |
| Dell          | Precision 5510              | [f4188b30c9](https://linux-hardware.org/?probe=f4188b30c9) | Dec 13, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| HP            | Compaq Presario CQ71        | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Acer          | Aspire ES1-731G             | [589cce31c8](https://linux-hardware.org/?probe=589cce31c8) | Dec 09, 2022 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [ff0997b72a](https://linux-hardware.org/?probe=ff0997b72a) | Dec 09, 2022 |
| HP            | ProBook 450 G0              | [01e7f95a23](https://linux-hardware.org/?probe=01e7f95a23) | Dec 07, 2022 |
| HP            | ProBook 450 G0              | [c3b6c86431](https://linux-hardware.org/?probe=c3b6c86431) | Dec 07, 2022 |
| Dell          | Vostro 5620                 | [50acc3b3b8](https://linux-hardware.org/?probe=50acc3b3b8) | Dec 04, 2022 |
| ASUSTek       | X541NA                      | [9da9a87b5b](https://linux-hardware.org/?probe=9da9a87b5b) | Dec 03, 2022 |
| Acer          | Aspire ES1-731G             | [06918f4cc5](https://linux-hardware.org/?probe=06918f4cc5) | Dec 03, 2022 |
| Dell          | Inspiron N7010              | [3e9458fd24](https://linux-hardware.org/?probe=3e9458fd24) | Dec 02, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| Acer          | AO756                       | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Dell          | Latitude 5420               | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| HP            | EliteBook 2730p             | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| HP            | ProBook 450 G6              | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Acer          | Aspire 5830T                | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Lenovo        | Y50-70 20378                | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| Acer          | Nitro AN515-45              | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| HP            | ProBook 640 G1              | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Apple         | MacBookPro16,4              | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| Lenovo        | Unknown                     | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Toshiba       | PORTEGE Z930                | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| HP            | ProBook 450 G3              | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| HP            | ProBook 450 G0              | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| HP            | Compaq 6730s                | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Dell          | XPS 15 9570                 | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Acer          | Aspire E5-571               | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| ASUSTek       | X540LJ                      | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Toshiba       | Satellite C650              | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Dell          | Precision M6800             | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| MSI           | Modern 15 A4M               | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| HP            | ProBook 455 G7              | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Dell          | Precision M4600             | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Dell          | Inspiron 7559               | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| Lenovo        | IdeaPad Y580                | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| HP            | EliteBook 850 G5            | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASUSTek       | N551VW                      | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Dell          | Latitude E6330              | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| HP            | 250 G6 Notebook PC          | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| Toshiba       | Satellite A200              | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| HP            | Notebook                    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| Acer          | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| HP            | ProBook 4540s               | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| Dell          | Latitude E6430              | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| HP            | EliteBook 8460p             | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| HP            | Pavilion dv7                | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Acer          | Aspire A515-52G             | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| Acer          | Extensa 5630                | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| HP            | EliteBook 850 G5            | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| MSI           | Modern 14 B4MW              | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| AMI           | Cherry Trail CR             | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | ProBook 6450b               | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Lenovo        | V15-ADA 82C7                | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| Acer          | Aspire V3-571G              | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| Acer          | Predator G9-792             | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Dell          | Latitude 5410               | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Acer          | Extensa 5630                | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Dell          | Studio 1747                 | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| ASUSTek       | GL553VE                     | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| Dell          | Studio 1535                 | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| HP            | EliteBook 8460p             | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Lenovo        | ThinkPad T61 765912G        | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| HP            | EliteBook 850 G5            | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| HP            | Notebook                    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| Lenovo        | ThinkPad X230 232425U       | [69e5ab7b60](https://linux-hardware.org/?probe=69e5ab7b60) | Apr 24, 2021 |
| Dell          | Vostro 3580                 | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Dell          | Vostro 3558                 | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| Acer          | Nitro AN515-43              | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| Dell          | Latitude E6330              | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| Dell          | Inspiron MM061              | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| Dell          | Inspiron 3584               | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| ASUSTek       | G752VL                      | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Toshiba       | TECRA A11                   | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| Dell          | Vostro 3580                 | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| Dell          | Vostro 3580                 | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| Apple         | MacBook4,1                  | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| HP            | Laptop 15-da0xxx            | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| MSI           | GP60 2PE                    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| HP            | EliteBook 850 G5            | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Packard Be... | EasyNote TK87               | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Dell          | Latitude E6410              | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| Toshiba       | Satellite C50-A-19T         | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Apple         | MacBook4,1                  | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Dell          | Latitude E5430 non-vPro     | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Apple         | MacBook4,1                  | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| HP            | EliteBook 8560p             | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| Dell          | Latitude 5591               | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| Dell          | Inspiron N5110              | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| ASUSTek       | G551JM                      | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| HP            | ProBook 6470b               | [18f5fab938](https://linux-hardware.org/?probe=18f5fab938) | Oct 31, 2020 |
| Dell          | Vostro 3580                 | [a0e40c6f16](https://linux-hardware.org/?probe=a0e40c6f16) | Oct 29, 2020 |
| ASUSTek       | X541NA                      | [a4497b52bb](https://linux-hardware.org/?probe=a4497b52bb) | Oct 28, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | [4643cfe86d](https://linux-hardware.org/?probe=4643cfe86d) | Oct 27, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | [da5ad20c60](https://linux-hardware.org/?probe=da5ad20c60) | Oct 27, 2020 |
| Dell          | Latitude 5480               | [4191db79b7](https://linux-hardware.org/?probe=4191db79b7) | Oct 25, 2020 |
| Toshiba       | Satellite S70-B             | [a6521e505a](https://linux-hardware.org/?probe=a6521e505a) | Oct 25, 2020 |
| Lenovo        | G50-80 80E5                 | [89f32e3856](https://linux-hardware.org/?probe=89f32e3856) | Oct 23, 2020 |
| ASUSTek       | N551VW                      | [76852e9990](https://linux-hardware.org/?probe=76852e9990) | Oct 22, 2020 |
| Lenovo        | G570 20079                  | [74b57e7887](https://linux-hardware.org/?probe=74b57e7887) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a1a02fe851](https://linux-hardware.org/?probe=a1a02fe851) | Oct 18, 2020 |
| Dell          | Latitude E5430 non-vPro     | [dd68c7b3f6](https://linux-hardware.org/?probe=dd68c7b3f6) | Oct 18, 2020 |
| Toshiba       | Satellite P300              | [fdc8cb1b11](https://linux-hardware.org/?probe=fdc8cb1b11) | Oct 16, 2020 |
| Lenovo        | Yoga 2 11 20428             | [f5c8360ae3](https://linux-hardware.org/?probe=f5c8360ae3) | Oct 15, 2020 |
| Lenovo        | G50-80 80E5                 | [3f72e0309a](https://linux-hardware.org/?probe=3f72e0309a) | Oct 15, 2020 |
| Lenovo        | G570 20079                  | [ba66ad5205](https://linux-hardware.org/?probe=ba66ad5205) | Oct 12, 2020 |
| Lenovo        | G570 20079                  | [5e14548b50](https://linux-hardware.org/?probe=5e14548b50) | Oct 12, 2020 |
| HP            | EliteBook 8560p             | [bbae413f9c](https://linux-hardware.org/?probe=bbae413f9c) | Oct 10, 2020 |
| ASUSTek       | K53U                        | [59444922e7](https://linux-hardware.org/?probe=59444922e7) | Oct 10, 2020 |
| ASUSTek       | K53U                        | [5c5b3815f7](https://linux-hardware.org/?probe=5c5b3815f7) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [25fb29514f](https://linux-hardware.org/?probe=25fb29514f) | Oct 10, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Acer          | Aspire V3-571G              | [86c3c25832](https://linux-hardware.org/?probe=86c3c25832) | Oct 05, 2020 |
| HP            | 250 G3                      | [ab75ccc4f8](https://linux-hardware.org/?probe=ab75ccc4f8) | Oct 02, 2020 |
| Dell          | Inspiron 3583               | [419cd76be1](https://linux-hardware.org/?probe=419cd76be1) | Oct 01, 2020 |
| Acer          | Aspire 5738                 | [18199ffdaf](https://linux-hardware.org/?probe=18199ffdaf) | Sep 30, 2020 |
| Dell          | G7 7588                     | [0d38edaf0c](https://linux-hardware.org/?probe=0d38edaf0c) | Sep 28, 2020 |
| Toshiba       | Satellite P300              | [33020554c0](https://linux-hardware.org/?probe=33020554c0) | Sep 27, 2020 |
| HP            | EliteBook 8470p             | [e330dd752b](https://linux-hardware.org/?probe=e330dd752b) | Sep 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Nitro AN515-44              | [18afb6b15d](https://linux-hardware.org/?probe=18afb6b15d) | Sep 22, 2020 |
| Acer          | Nitro AN515-44              | [c078093e0f](https://linux-hardware.org/?probe=c078093e0f) | Sep 22, 2020 |
| HP            | Compaq tc4400 (RH489ES#A... | [c0305edfae](https://linux-hardware.org/?probe=c0305edfae) | Sep 20, 2020 |
| ASUSTek       | K50C                        | [d4e11f2289](https://linux-hardware.org/?probe=d4e11f2289) | Sep 18, 2020 |
| Acer          | Extensa 5630                | [9040e8e334](https://linux-hardware.org/?probe=9040e8e334) | Sep 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [a66f1b519a](https://linux-hardware.org/?probe=a66f1b519a) | Sep 10, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| Lenovo        | ThinkPad X250 20CLS2YH00    | [cee4231640](https://linux-hardware.org/?probe=cee4231640) | Aug 29, 2020 |
| Fujitsu       | LIFEBOOK E752               | [9820c3c8bd](https://linux-hardware.org/?probe=9820c3c8bd) | Aug 28, 2020 |
| Dell          | Precision M4800             | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| Dell          | Precision M4800             | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| HP            | 250 G3                      | [ff5c3ce273](https://linux-hardware.org/?probe=ff5c3ce273) | Aug 19, 2020 |
| HP            | EliteBook 8560w             | [bf7ae9d5bf](https://linux-hardware.org/?probe=bf7ae9d5bf) | Aug 19, 2020 |
| HP            | 250 G3                      | [01f2866b5c](https://linux-hardware.org/?probe=01f2866b5c) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [1619b6bb6c](https://linux-hardware.org/?probe=1619b6bb6c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [18c07b157f](https://linux-hardware.org/?probe=18c07b157f) | Jul 29, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [8051286600](https://linux-hardware.org/?probe=8051286600) | Jul 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06120056c3](https://linux-hardware.org/?probe=06120056c3) | Jul 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8d593715c](https://linux-hardware.org/?probe=e8d593715c) | Jul 25, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [42fc06b0e4](https://linux-hardware.org/?probe=42fc06b0e4) | Jul 23, 2020 |
| Packard Be... | DOTS E2                     | [223cceb869](https://linux-hardware.org/?probe=223cceb869) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | [699033745c](https://linux-hardware.org/?probe=699033745c) | Jul 19, 2020 |
| Acer          | E5-575G                     | [9fb1e1bee4](https://linux-hardware.org/?probe=9fb1e1bee4) | Jul 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee5e7f9151](https://linux-hardware.org/?probe=ee5e7f9151) | Jul 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [968247c419](https://linux-hardware.org/?probe=968247c419) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c1fb882fc5](https://linux-hardware.org/?probe=c1fb882fc5) | Jul 17, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ac0d845ddb](https://linux-hardware.org/?probe=ac0d845ddb) | Jul 13, 2020 |
| ASUSTek       | X510UQR                     | [54f20878cf](https://linux-hardware.org/?probe=54f20878cf) | Jul 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| Fujitsu Si... | AMILO L Series              | [33762202ef](https://linux-hardware.org/?probe=33762202ef) | Jul 01, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [9b54e3f16c](https://linux-hardware.org/?probe=9b54e3f16c) | Jun 30, 2020 |
| Dell          | Latitude E6410              | [79c1af2581](https://linux-hardware.org/?probe=79c1af2581) | Jun 29, 2020 |
| Acer          | Swift SF314-57G             | [9bd6123d76](https://linux-hardware.org/?probe=9bd6123d76) | Jun 25, 2020 |
| Toshiba       | Satellite C55-A-1HL         | [c6d6bb3ba1](https://linux-hardware.org/?probe=c6d6bb3ba1) | Jun 18, 2020 |
| Toshiba       | Satellite C55-A-1HL         | [d16857f500](https://linux-hardware.org/?probe=d16857f500) | Jun 17, 2020 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [7a3bd1d810](https://linux-hardware.org/?probe=7a3bd1d810) | Jun 10, 2020 |
| Acer          | Nitro AN515-43              | [65f523b6f2](https://linux-hardware.org/?probe=65f523b6f2) | Jun 06, 2020 |
| Acer          | Nitro AN515-43              | [c8ddcb0ec8](https://linux-hardware.org/?probe=c8ddcb0ec8) | Jun 06, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d23bc12452](https://linux-hardware.org/?probe=d23bc12452) | Jun 04, 2020 |
| HP            | 250 G3                      | [99be1919b2](https://linux-hardware.org/?probe=99be1919b2) | Jun 01, 2020 |
| Toshiba       | Satellite P300              | [8eb9fa72de](https://linux-hardware.org/?probe=8eb9fa72de) | May 31, 2020 |
| Lenovo        | G505 20240                  | [6860a03dd0](https://linux-hardware.org/?probe=6860a03dd0) | May 31, 2020 |
| HP            | 250 G3                      | [a4e1d1f904](https://linux-hardware.org/?probe=a4e1d1f904) | May 29, 2020 |
| Lenovo        | ThinkPad T495 20NJ0010BM    | [6974ca5761](https://linux-hardware.org/?probe=6974ca5761) | May 29, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [edcc0b8c05](https://linux-hardware.org/?probe=edcc0b8c05) | May 29, 2020 |
| ASUSTek       | X540LJ                      | [67a3981fe5](https://linux-hardware.org/?probe=67a3981fe5) | May 27, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| ASUSTek       | X705UNR                     | [015957a390](https://linux-hardware.org/?probe=015957a390) | May 22, 2020 |
| HP            | ProBook 6460b               | [babf988605](https://linux-hardware.org/?probe=babf988605) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | EliteBook 840 G1            | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33722345b4](https://linux-hardware.org/?probe=33722345b4) | May 13, 2020 |
| HP            | 255 G2                      | [ad9ef87735](https://linux-hardware.org/?probe=ad9ef87735) | May 13, 2020 |
| Acer          | Aspire 5742G                | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| HP            | ProBook 450 G0              | [88fc8f3bc8](https://linux-hardware.org/?probe=88fc8f3bc8) | May 13, 2020 |
| Acer          | Aspire 5742G                | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [715f4fa65b](https://linux-hardware.org/?probe=715f4fa65b) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [96cd96c818](https://linux-hardware.org/?probe=96cd96c818) | May 12, 2020 |
| HP            | ProBook 4710s               | [b2680d0881](https://linux-hardware.org/?probe=b2680d0881) | May 11, 2020 |
| HP            | EliteBook 840 G1            | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Acer          | Nitro AN515-43              | [6da190e95d](https://linux-hardware.org/?probe=6da190e95d) | May 10, 2020 |
| HP            | 255 G2                      | [ee5dcad518](https://linux-hardware.org/?probe=ee5dcad518) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Dell          | Latitude 7490               | [94b949eb90](https://linux-hardware.org/?probe=94b949eb90) | May 08, 2020 |
| Acer          | E5-575G                     | [4de3c815fd](https://linux-hardware.org/?probe=4de3c815fd) | May 08, 2020 |
| HP            | EliteBook 820 G2            | [3b379abf6a](https://linux-hardware.org/?probe=3b379abf6a) | May 07, 2020 |
| HP            | EliteBook 840 G1            | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| HP            | 255 G2                      | [162f37494e](https://linux-hardware.org/?probe=162f37494e) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ea793cbae5](https://linux-hardware.org/?probe=ea793cbae5) | May 06, 2020 |
| Dell          | Latitude E4300              | [8b26d2727c](https://linux-hardware.org/?probe=8b26d2727c) | May 06, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [cbcdbbc816](https://linux-hardware.org/?probe=cbcdbbc816) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [72e18e38ce](https://linux-hardware.org/?probe=72e18e38ce) | May 04, 2020 |
| HP            | Pavilion Notebook           | [35d925dbae](https://linux-hardware.org/?probe=35d925dbae) | May 04, 2020 |
| Dell          | Inspiron 7577               | [02c7c61130](https://linux-hardware.org/?probe=02c7c61130) | May 03, 2020 |
| Dell          | Inspiron 7577               | [d987f6c242](https://linux-hardware.org/?probe=d987f6c242) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [c3b3575e58](https://linux-hardware.org/?probe=c3b3575e58) | May 02, 2020 |
| ASUSTek       | G771JW                      | [77202c9853](https://linux-hardware.org/?probe=77202c9853) | May 02, 2020 |
| HP            | ProBook 450 G0              | [f74dab71c3](https://linux-hardware.org/?probe=f74dab71c3) | May 01, 2020 |
| HP            | ProBook 450 G0              | [7ac5247653](https://linux-hardware.org/?probe=7ac5247653) | May 01, 2020 |
| Acer          | Aspire 3830G                | [1af95987d0](https://linux-hardware.org/?probe=1af95987d0) | Apr 26, 2020 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | [2dde18f51f](https://linux-hardware.org/?probe=2dde18f51f) | Apr 24, 2020 |
| ASUSTek       | N551VW                      | [2d93805421](https://linux-hardware.org/?probe=2d93805421) | Apr 23, 2020 |
| ASUSTek       | N551VW                      | [155a39180a](https://linux-hardware.org/?probe=155a39180a) | Apr 23, 2020 |
| HP            | 250 G7 Notebook PC          | [28fa6e8b6e](https://linux-hardware.org/?probe=28fa6e8b6e) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [73f401be06](https://linux-hardware.org/?probe=73f401be06) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [562403e85f](https://linux-hardware.org/?probe=562403e85f) | Apr 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [ee479d0e5d](https://linux-hardware.org/?probe=ee479d0e5d) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [a78b041d0c](https://linux-hardware.org/?probe=a78b041d0c) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [fbfdc3b5e3](https://linux-hardware.org/?probe=fbfdc3b5e3) | Apr 20, 2020 |
| Sony          | VPCEB4L1E                   | [f1a3807b60](https://linux-hardware.org/?probe=f1a3807b60) | Apr 20, 2020 |
| Compal        | HEL80I                      | [41fd098e10](https://linux-hardware.org/?probe=41fd098e10) | Apr 20, 2020 |
| HP            | 250 G7 Notebook PC          | [6b8e555d43](https://linux-hardware.org/?probe=6b8e555d43) | Apr 18, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [f3b92c302c](https://linux-hardware.org/?probe=f3b92c302c) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | [d1e3e7d629](https://linux-hardware.org/?probe=d1e3e7d629) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | [a9b4abdd56](https://linux-hardware.org/?probe=a9b4abdd56) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | [43f93a43d6](https://linux-hardware.org/?probe=43f93a43d6) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | [20b4b0a6ad](https://linux-hardware.org/?probe=20b4b0a6ad) | Apr 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5fc32fd27b](https://linux-hardware.org/?probe=5fc32fd27b) | Apr 12, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Inspiron 3521               | [53b2f1863a](https://linux-hardware.org/?probe=53b2f1863a) | Apr 07, 2020 |
| Acer          | Nitro AN515-43              | [6b0efa548b](https://linux-hardware.org/?probe=6b0efa548b) | Apr 04, 2020 |
| HP            | ProBook 4540s               | [e3c52f3d96](https://linux-hardware.org/?probe=e3c52f3d96) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 74        | 8.93%   |
| Ubuntu 22.04                 | 52        | 6.27%   |
| Ubuntu 18.04                 | 49        | 5.91%   |
| Pop!_OS 22.04                | 16        | 1.93%   |
| Manjaro                      | 16        | 1.93%   |
| OpenMandriva 4.3             | 15        | 1.81%   |
| Fedora 38                    | 15        | 1.81%   |
| Fedora 39                    | 14        | 1.69%   |
| Debian 11                    | 14        | 1.69%   |
| OpenMandriva 4.2             | 13        | 1.57%   |
| Linux Mint 20.3              | 13        | 1.57%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 1.45%   |
| KDE neon 20.04               | 12        | 1.45%   |
| Arch Rolling                 | 12        | 1.45%   |
| Linux Mint 21.1              | 11        | 1.33%   |
| Linux Mint 20.1              | 11        | 1.33%   |
| Zorin 16                     | 10        | 1.21%   |
| ROSA R11                     | 10        | 1.21%   |
| Linux Mint 20.2              | 10        | 1.21%   |
| Linux Mint 19.3              | 10        | 1.21%   |
| Kubuntu 20.04                | 10        | 1.21%   |
| Ubuntu 22.10                 | 9         | 1.09%   |
| Ubuntu 19.04                 | 9         | 1.09%   |
| ArcoLinux Rolling            | 9         | 1.09%   |
| Arch                         | 9         | 1.09%   |
| Xubuntu 20.04                | 8         | 0.97%   |
| Ubuntu 23.10                 | 8         | 0.97%   |
| ROSA R10                     | 8         | 0.97%   |
| Linux Mint 21.2              | 8         | 0.97%   |
| Linux Mint 20                | 8         | 0.97%   |
| Fedora 33                    | 8         | 0.97%   |
| Ubuntu 19.10                 | 7         | 0.84%   |
| OpenMandriva 23.08           | 7         | 0.84%   |
| Zorin 15                     | 6         | 0.72%   |
| Xubuntu 18.04                | 6         | 0.72%   |
| Ubuntu 23.04                 | 6         | 0.72%   |
| ROSA R9                      | 6         | 0.72%   |
| LMDE 4                       | 6         | 0.72%   |
| Fedora 37                    | 6         | 0.72%   |
| Debian 12                    | 6         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 214       | 28.84%  |
| Linux Mint    | 71        | 9.57%   |
| Fedora        | 58        | 7.82%   |
| OpenMandriva  | 46        | 6.2%    |
| ROSA          | 32        | 4.31%   |
| Manjaro       | 31        | 4.18%   |
| Pop!_OS       | 28        | 3.77%   |
| Endless       | 24        | 3.23%   |
| Debian        | 24        | 3.23%   |
| Arch          | 20        | 2.7%    |
| Kubuntu       | 19        | 2.56%   |
| KDE neon      | 19        | 2.56%   |
| Kali          | 19        | 2.56%   |
| Zorin         | 18        | 2.43%   |
| Xubuntu       | 16        | 2.16%   |
| openSUSE      | 15        | 2.02%   |
| ArcoLinux     | 11        | 1.48%   |
| Clear Linux   | 9         | 1.21%   |
| Ubuntu Unity  | 6         | 0.81%   |
| LMDE          | 6         | 0.81%   |
| SteamOS       | 4         | 0.54%   |
| EndeavourOS   | 4         | 0.54%   |
| Lubuntu       | 3         | 0.4%    |
| Gentoo        | 3         | 0.4%    |
| Elementary    | 3         | 0.4%    |
| CentOS        | 3         | 0.4%    |
| Artix         | 3         | 0.4%    |
| Void Linux    | 2         | 0.27%   |
| Ubuntu Budgie | 2         | 0.27%   |
| Parrot        | 2         | 0.27%   |
| MX            | 2         | 0.27%   |
| Mageia        | 2         | 0.27%   |
| Garuda Linux  | 2         | 0.27%   |
| Deepin        | 2         | 0.27%   |
| BunsenLabs    | 2         | 0.27%   |
| Ubuntu Studio | 1         | 0.13%   |
| Ubuntu MATE   | 1         | 0.13%   |
| TUXEDO OS     | 1         | 0.13%   |
| Sparky        | 1         | 0.13%   |
| Rocky Linux   | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 14        | 1.54%   |
| 5.10.14-desktop-1omv4002        | 13        | 1.43%   |
| 5.15.0-56-generic               | 12        | 1.32%   |
| 5.4.0-42-generic                | 10        | 1.1%    |
| 5.4.0-58-generic                | 8         | 0.88%   |
| 5.3.0-28-generic                | 7         | 0.77%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 7         | 0.77%   |
| 6.2.0-26-generic                | 6         | 0.66%   |
| 5.8.0-14-generic                | 6         | 0.66%   |
| 6.4.11-desktop-1omv2390         | 5         | 0.55%   |
| 5.4.0-91-generic                | 5         | 0.55%   |
| 5.4.0-48-generic                | 5         | 0.55%   |
| 5.4.0-29-generic                | 5         | 0.55%   |
| 5.4.0-26-generic                | 5         | 0.55%   |
| 4.15.0-20-generic               | 5         | 0.55%   |
| 6.2.6-desktop-1omv2390          | 4         | 0.44%   |
| 6.2.0-39-generic                | 4         | 0.44%   |
| 5.9.16-1-MANJARO                | 4         | 0.44%   |
| 5.4.0-90-generic                | 4         | 0.44%   |
| 5.4.0-77-generic                | 4         | 0.44%   |
| 5.4.0-73-generic                | 4         | 0.44%   |
| 5.4.0-65-generic                | 4         | 0.44%   |
| 5.4.0-47-generic                | 4         | 0.44%   |
| 5.4.0-40-generic                | 4         | 0.44%   |
| 5.4.0-19-generic                | 4         | 0.44%   |
| 5.3.0-53-generic                | 4         | 0.44%   |
| 5.19.0-35-generic               | 4         | 0.44%   |
| 5.15.0-52-generic               | 4         | 0.44%   |
| 5.15.0-47-generic               | 4         | 0.44%   |
| 5.13.0-28-generic               | 4         | 0.44%   |
| 5.13.0-27-generic               | 4         | 0.44%   |
| 5.11.0-37-generic               | 4         | 0.44%   |
| 5.0.0-37-generic                | 4         | 0.44%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 4         | 0.44%   |
| 4.19.0-8-amd64                  | 4         | 0.44%   |
| 6.5.0-27-generic                | 3         | 0.33%   |
| 6.5.0-26-generic                | 3         | 0.33%   |
| 6.5.0-25-generic                | 3         | 0.33%   |
| 6.5.0-14-generic                | 3         | 0.33%   |
| 6.4.8-desktop-2omv2390          | 3         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 112       | 12.99%  |
| 5.15.0  | 68        | 7.89%   |
| 4.15.0  | 46        | 5.34%   |
| 6.2.0   | 31        | 3.6%    |
| 5.3.0   | 31        | 3.6%    |
| 5.8.0   | 30        | 3.48%   |
| 5.13.0  | 29        | 3.36%   |
| 5.19.0  | 25        | 2.9%    |
| 5.11.0  | 25        | 2.9%    |
| 5.0.0   | 23        | 2.67%   |
| 6.5.0   | 22        | 2.55%   |
| 5.10.0  | 19        | 2.2%    |
| 4.18.0  | 16        | 1.86%   |
| 5.16.7  | 14        | 1.62%   |
| 5.10.14 | 14        | 1.62%   |
| 6.1.0   | 11        | 1.28%   |
| 4.19.0  | 9         | 1.04%   |
| 6.2.6   | 7         | 0.81%   |
| 5.9.16  | 7         | 0.81%   |
| 4.9.20  | 6         | 0.7%    |
| 6.8.0   | 5         | 0.58%   |
| 6.6.10  | 5         | 0.58%   |
| 6.4.11  | 5         | 0.58%   |
| 6.1.1   | 5         | 0.58%   |
| 5.17.5  | 5         | 0.58%   |
| 6.0.12  | 4         | 0.46%   |
| 6.0.0   | 4         | 0.46%   |
| 5.6.8   | 4         | 0.46%   |
| 5.18.0  | 4         | 0.46%   |
| 5.14.0  | 4         | 0.46%   |
| 4.4.0   | 4         | 0.46%   |
| 6.7.7   | 3         | 0.35%   |
| 6.7.4   | 3         | 0.35%   |
| 6.7.0   | 3         | 0.35%   |
| 6.6.9   | 3         | 0.35%   |
| 6.6.8   | 3         | 0.35%   |
| 6.6.6   | 3         | 0.35%   |
| 6.5.6   | 3         | 0.35%   |
| 6.5.5   | 3         | 0.35%   |
| 6.4.8   | 3         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 120       | 14.25%  |
| 5.15    | 87        | 10.33%  |
| 6.2     | 48        | 5.7%    |
| 5.10    | 46        | 5.46%   |
| 4.15    | 46        | 5.46%   |
| 6.5     | 37        | 4.39%   |
| 5.8     | 35        | 4.16%   |
| 5.3     | 35        | 4.16%   |
| 5.13    | 33        | 3.92%   |
| 5.11    | 31        | 3.68%   |
| 5.19    | 29        | 3.44%   |
| 6.1     | 28        | 3.33%   |
| 5.0     | 26        | 3.09%   |
| 6.6     | 25        | 2.97%   |
| 5.16    | 25        | 2.97%   |
| 6.4     | 18        | 2.14%   |
| 4.18    | 17        | 2.02%   |
| 4.9     | 15        | 1.78%   |
| 6.0     | 14        | 1.66%   |
| 4.19    | 14        | 1.66%   |
| 6.7     | 13        | 1.54%   |
| 5.9     | 12        | 1.43%   |
| 5.6     | 11        | 1.31%   |
| 5.17    | 11        | 1.31%   |
| 6.8     | 9         | 1.07%   |
| 6.3     | 9         | 1.07%   |
| 5.14    | 9         | 1.07%   |
| 5.18    | 8         | 0.95%   |
| 5.12    | 8         | 0.95%   |
| 5.7     | 6         | 0.71%   |
| 5.5     | 6         | 0.71%   |
| 4.4     | 4         | 0.48%   |
| 5.1     | 2         | 0.24%   |
| 5.2     | 1         | 0.12%   |
| 4.13    | 1         | 0.12%   |
| 4.1     | 1         | 0.12%   |
| 3.13    | 1         | 0.12%   |
| 3.10    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 687       | 96.49%  |
| i686   | 25        | 3.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 303       | 39.71%  |
| KDE5             | 140       | 18.35%  |
| Unknown          | 77        | 10.09%  |
| XFCE             | 74        | 9.7%    |
| X-Cinnamon       | 57        | 7.47%   |
| KDE4             | 18        | 2.36%   |
| KDE              | 18        | 2.36%   |
| Cinnamon         | 16        | 2.1%    |
| MATE             | 15        | 1.97%   |
| LXQt             | 8         | 1.05%   |
| Unity            | 6         | 0.79%   |
| i3               | 5         | 0.66%   |
| Deepin           | 4         | 0.52%   |
| Pantheon         | 3         | 0.39%   |
| GNOME Flashback  | 3         | 0.39%   |
| GNOME Classic    | 3         | 0.39%   |
| Budgie           | 3         | 0.39%   |
| LXDE             | 2         | 0.26%   |
| lightdm-xsession | 2         | 0.26%   |
| xmonad           | 1         | 0.13%   |
| sway             | 1         | 0.13%   |
| openbox          | 1         | 0.13%   |
| KDE6             | 1         | 0.13%   |
| icewm            | 1         | 0.13%   |
| bspwm            | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 551       | 73.96%  |
| Wayland | 143       | 19.19%  |
| Unknown | 46        | 6.17%   |
| Tty     | 5         | 0.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 346       | 45.95%  |
| SDDM    | 117       | 15.54%  |
| GDM3    | 94        | 12.48%  |
| LightDM | 90        | 11.95%  |
| GDM     | 68        | 9.03%   |
| TDM     | 18        | 2.39%   |
| KDM     | 17        | 2.26%   |
| XDM     | 2         | 0.27%   |
| MDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 473       | 64.18%  |
| bg_BG   | 125       | 16.96%  |
| Unknown | 85        | 11.53%  |
| en_GB   | 18        | 2.44%   |
| C       | 13        | 1.76%   |
| ru_RU   | 8         | 1.09%   |
| POSIX   | 2         | 0.27%   |
| en_DK   | 2         | 0.27%   |
| de_DE   | 2         | 0.27%   |
| uk_UA   | 1         | 0.14%   |
| tr_TR   | 1         | 0.14%   |
| sv_SE   | 1         | 0.14%   |
| it_IT   | 1         | 0.14%   |
| fr_FR   | 1         | 0.14%   |
| es_ES   | 1         | 0.14%   |
| en_NZ   | 1         | 0.14%   |
| en_AG   | 1         | 0.14%   |
| C.UTF8  | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 381       | 51.98%  |
| EFI  | 352       | 48.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 532       | 72.68%  |
| Btrfs   | 68        | 9.29%   |
| Overlay | 44        | 6.01%   |
| Tmpfs   | 34        | 4.64%   |
| Unknown | 32        | 4.37%   |
| Xfs     | 14        | 1.91%   |
| Zfs     | 3         | 0.41%   |
| Ext2    | 3         | 0.41%   |
| Ext3    | 2         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 366       | 49.59%  |
| GPT     | 277       | 37.53%  |
| MBR     | 95        | 12.87%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 635       | 88.19%  |
| Yes       | 85        | 11.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 514       | 70.9%   |
| Yes       | 211       | 29.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 206       | 29.01%  |
| Hewlett-Packard     | 128       | 18.03%  |
| Dell                | 111       | 15.63%  |
| ASUSTek Computer    | 86        | 12.11%  |
| Acer                | 72        | 10.14%  |
| Toshiba             | 34        | 4.79%   |
| MSI                 | 16        | 2.25%   |
| Apple               | 8         | 1.13%   |
| Fujitsu             | 5         | 0.7%    |
| Valve               | 4         | 0.56%   |
| Sony                | 4         | 0.56%   |
| Fujitsu Siemens     | 4         | 0.56%   |
| TUXEDO              | 3         | 0.42%   |
| Samsung Electronics | 3         | 0.42%   |
| HUAWEI              | 3         | 0.42%   |
| Packard Bell        | 2         | 0.28%   |
| Medion              | 2         | 0.28%   |
| Google              | 2         | 0.28%   |
| Gigabyte Technology | 2         | 0.28%   |
| AMI                 | 2         | 0.28%   |
| Timi                | 1         | 0.14%   |
| System76            | 1         | 0.14%   |
| Razer               | 1         | 0.14%   |
| Pegatron            | 1         | 0.14%   |
| ONDA                | 1         | 0.14%   |
| Notebook            | 1         | 0.14%   |
| LG Electronics      | 1         | 0.14%   |
| IBM                 | 1         | 0.14%   |
| Cube                | 1         | 0.14%   |
| Compal              | 1         | 0.14%   |
| Beelink             | 1         | 0.14%   |
| Allview             | 1         | 0.14%   |
| Unknown             | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo G500 20236                          | 5         | 0.7%    |
| Dell Inspiron N5110                        | 5         | 0.7%    |
| ASUS X541NA                                | 5         | 0.7%    |
| Unknown                                    | 5         | 0.7%    |
| Valve Jupiter                              | 4         | 0.56%   |
| HP ProBook 4540s                           | 4         | 0.56%   |
| HP ProBook 450 G8 Notebook PC              | 4         | 0.56%   |
| Lenovo Y520-15IKBN 80WK                    | 3         | 0.42%   |
| HP ProBook 450 G0                          | 3         | 0.42%   |
| HP Pavilion 15                             | 3         | 0.42%   |
| HP Notebook                                | 3         | 0.42%   |
| HP 255 G8 Notebook PC                      | 3         | 0.42%   |
| Dell Precision M4600                       | 3         | 0.42%   |
| Dell Latitude E6410                        | 3         | 0.42%   |
| Dell Latitude E4300                        | 3         | 0.42%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA   | 3         | 0.42%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.42%   |
| ASUS N551VW                                | 3         | 0.42%   |
| Acer Aspire 5738                           | 3         | 0.42%   |
| Toshiba Satellite L300                     | 2         | 0.28%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.28%   |
| Toshiba Satellite A300                     | 2         | 0.28%   |
| Toshiba Satellite A200                     | 2         | 0.28%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.28%   |
| MSI Modern 15 A5M                          | 2         | 0.28%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.28%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.28%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.28%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.28%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.28%   |
| Lenovo ThinkPad T14 Gen 1 20S0000NBM       | 2         | 0.28%   |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.28%   |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.28%   |
| Lenovo ThinkPad E15 Gen 4 21E6006WBM       | 2         | 0.28%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.28%   |
| Lenovo ThinkBook 13s-IML 20RR              | 2         | 0.28%   |
| Lenovo Legion Y740-17IRHg 81UJ             | 2         | 0.28%   |
| Lenovo Legion Y530-15ICH 81FV              | 2         | 0.28%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.28%   |
| Lenovo IdeaPad Y510P 20217                 | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 100       | 14.08%  |
| Acer Aspire           | 51        | 7.18%   |
| Lenovo IdeaPad        | 44        | 6.2%    |
| Dell Latitude         | 41        | 5.77%   |
| HP ProBook            | 34        | 4.79%   |
| Dell Inspiron         | 31        | 4.37%   |
| Toshiba Satellite     | 28        | 3.94%   |
| HP EliteBook          | 26        | 3.66%   |
| ASUS VivoBook         | 24        | 3.38%   |
| HP Pavilion           | 23        | 3.24%   |
| Lenovo Legion         | 14        | 1.97%   |
| Dell Vostro           | 13        | 1.83%   |
| Dell Precision        | 12        | 1.69%   |
| HP Compaq             | 10        | 1.41%   |
| Lenovo Yoga           | 7         | 0.99%   |
| HP 255                | 7         | 0.99%   |
| ASUS ROG              | 7         | 0.99%   |
| MSI Modern            | 6         | 0.85%   |
| Lenovo ThinkBook      | 6         | 0.85%   |
| HP Laptop             | 6         | 0.85%   |
| Acer Nitro            | 6         | 0.85%   |
| Lenovo G500           | 5         | 0.7%    |
| Dell XPS              | 5         | 0.7%    |
| ASUS X541NA           | 5         | 0.7%    |
| ASUS ASUS             | 5         | 0.7%    |
| Unknown               | 5         | 0.7%    |
| Valve Jupiter         | 4         | 0.56%   |
| Lenovo V15            | 4         | 0.56%   |
| HP ZBook              | 4         | 0.56%   |
| HP 250                | 4         | 0.56%   |
| ASUS ZenBook          | 4         | 0.56%   |
| Acer Predator         | 4         | 0.56%   |
| MSI GF63              | 3         | 0.42%   |
| Lenovo Y520-15IKBN    | 3         | 0.42%   |
| HP Notebook           | 3         | 0.42%   |
| Fujitsu Siemens AMILO | 3         | 0.42%   |
| Fujitsu LIFEBOOK      | 3         | 0.42%   |
| Dell Studio           | 3         | 0.42%   |
| ASUS TUF              | 3         | 0.42%   |
| ASUS N551VW           | 3         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 68        | 9.58%   |
| 2017 | 56        | 7.89%   |
| 2012 | 56        | 7.89%   |
| 2011 | 55        | 7.75%   |
| 2019 | 54        | 7.61%   |
| 2021 | 49        | 6.9%    |
| 2013 | 49        | 6.9%    |
| 2018 | 46        | 6.48%   |
| 2022 | 42        | 5.92%   |
| 2014 | 39        | 5.49%   |
| 2008 | 39        | 5.49%   |
| 2015 | 38        | 5.35%   |
| 2010 | 35        | 4.93%   |
| 2009 | 24        | 3.38%   |
| 2016 | 22        | 3.1%    |
| 2023 | 16        | 2.25%   |
| 2007 | 14        | 1.97%   |
| 2006 | 6         | 0.85%   |
| 2004 | 2         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 710       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 665       | 93.01%  |
| Enabled  | 50        | 6.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 706       | 99.44%  |
| Yes  | 4         | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 209       | 28.75%  |
| 8.01-16.0   | 150       | 20.63%  |
| 3.01-4.0    | 147       | 20.22%  |
| 16.01-24.0  | 101       | 13.89%  |
| 32.01-64.0  | 55        | 7.57%   |
| 1.01-2.0    | 20        | 2.75%   |
| 24.01-32.0  | 17        | 2.34%   |
| 2.01-3.0    | 16        | 2.2%    |
| 64.01-256.0 | 9         | 1.24%   |
| 0.51-1.0    | 3         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 246       | 30%     |
| 2.01-3.0   | 231       | 28.17%  |
| 4.01-8.0   | 125       | 15.24%  |
| 3.01-4.0   | 120       | 14.63%  |
| 0.51-1.0   | 48        | 5.85%   |
| 8.01-16.0  | 38        | 4.63%   |
| 16.01-24.0 | 6         | 0.73%   |
| 0.01-0.5   | 4         | 0.49%   |
| 32.01-64.0 | 1         | 0.12%   |
| Unknown    | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 538       | 73.8%   |
| 2      | 167       | 22.91%  |
| 3      | 17        | 2.33%   |
| 0      | 6         | 0.82%   |
| 4      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 457       | 63.83%  |
| Yes       | 259       | 36.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 607       | 85.01%  |
| No        | 107       | 14.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 704       | 99.15%  |
| No        | 6         | 0.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 563       | 78.09%  |
| No        | 158       | 21.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Bulgaria | 710       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sofia               | 391       | 51.65%  |
| Varna               | 62        | 8.19%   |
| Plovdiv             | 49        | 6.47%   |
| Burgas              | 38        | 5.02%   |
| Stara Zagora        | 12        | 1.59%   |
| Pernik              | 10        | 1.32%   |
| Pleven              | 9         | 1.19%   |
| Yambol              | 8         | 1.06%   |
| Veliko Tarnovo      | 8         | 1.06%   |
| Rousse              | 8         | 1.06%   |
| Montana             | 7         | 0.92%   |
| Svilengrad          | 6         | 0.79%   |
| Haskovo             | 6         | 0.79%   |
| Gabrovo             | 6         | 0.79%   |
| Dobrich             | 6         | 0.79%   |
| Shumen              | 5         | 0.66%   |
| Pazardzhik          | 5         | 0.66%   |
| Kazanlak            | 5         | 0.66%   |
| Blagoevgrad         | 5         | 0.66%   |
| Gorna Oryahovitsa   | 4         | 0.53%   |
| Asenovgrad          | 4         | 0.53%   |
| Vidin               | 3         | 0.4%    |
| Razgrad             | 3         | 0.4%    |
| Nesebar             | 3         | 0.4%    |
| Kyustendil          | 3         | 0.4%    |
| Vratsa              | 2         | 0.26%   |
| Troyan Municipality | 2         | 0.26%   |
| Svoge               | 2         | 0.26%   |
| Smolyan             | 2         | 0.26%   |
| Sliven              | 2         | 0.26%   |
| Sistov              | 2         | 0.26%   |
| Silistra            | 2         | 0.26%   |
| Sevlievo            | 2         | 0.26%   |
| Karlovo             | 2         | 0.26%   |
| Kardzhali           | 2         | 0.26%   |
| Botevgrad           | 2         | 0.26%   |
| Zlatia              | 1         | 0.13%   |
| Vresovo             | 1         | 0.13%   |
| Voluyak             | 1         | 0.13%   |
| Velingrad           | 1         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 142       | 210    | 16.17%  |
| Seagate                     | 95        | 125    | 10.82%  |
| WDC                         | 89        | 121    | 10.14%  |
| Toshiba                     | 79        | 105    | 9%      |
| SanDisk                     | 47        | 61     | 5.35%   |
| Kingston                    | 45        | 65     | 5.13%   |
| Unknown                     | 42        | 52     | 4.78%   |
| SK hynix                    | 37        | 48     | 4.21%   |
| Intel                       | 33        | 47     | 3.76%   |
| HGST                        | 33        | 48     | 3.76%   |
| Hitachi                     | 31        | 33     | 3.53%   |
| Micron Technology           | 29        | 35     | 3.3%    |
| A-DATA Technology           | 24        | 33     | 2.73%   |
| Transcend                   | 12        | 12     | 1.37%   |
| KIOXIA                      | 12        | 13     | 1.37%   |
| Crucial                     | 12        | 16     | 1.37%   |
| Fujitsu                     | 10        | 13     | 1.14%   |
| SPCC                        | 9         | 12     | 1.03%   |
| KingSpec                    | 8         | 9      | 0.91%   |
| China                       | 7         | 9      | 0.8%    |
| PNY                         | 6         | 7      | 0.68%   |
| Phison Electronics          | 6         | 8      | 0.68%   |
| Kingston Technology Company | 6         | 6      | 0.68%   |
| Team                        | 5         | 5      | 0.57%   |
| LITEON                      | 5         | 8      | 0.57%   |
| Apple                       | 5         | 7      | 0.57%   |
| LITEONIT                    | 4         | 4      | 0.46%   |
| Silicon Motion              | 3         | 3      | 0.34%   |
| Patriot                     | 3         | 3      | 0.34%   |
| Lexar                       | 3         | 3      | 0.34%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.23%   |
| TO Exter                    | 2         | 2      | 0.23%   |
| Teclast                     | 2         | 2      | 0.23%   |
| Realtek                     | 2         | 2      | 0.23%   |
| Lenovo                      | 2         | 2      | 0.23%   |
| Intenso                     | 2         | 2      | 0.23%   |
| GOODRAM                     | 2         | 2      | 0.23%   |
| AMD                         | 2         | 3      | 0.23%   |
| Wibtek                      | 1         | 2      | 0.11%   |
| VT                          | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 19        | 2.07%   |
| Toshiba MQ01ABF050 500GB                           | 14        | 1.53%   |
| Toshiba MQ01ABD100 1TB                             | 14        | 1.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 14        | 1.53%   |
| HGST HTS721010A9E630 1TB                           | 13        | 1.42%   |
| Samsung NVMe SSD Drive 512GB                       | 11        | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 11        | 1.2%    |
| Kingston SA400S37240G 240GB SSD                    | 10        | 1.09%   |
| Unknown MMC Card  32GB                             | 9         | 0.98%   |
| Samsung SSD 860 EVO 250GB                          | 9         | 0.98%   |
| Unknown MMC Card  64GB                             | 8         | 0.87%   |
| Samsung SSD 860 EVO 500GB                          | 8         | 0.87%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 7         | 0.76%   |
| SanDisk NVMe SSD Drive 512GB                       | 7         | 0.76%   |
| Kingston SA400S37120G 120GB SSD                    | 7         | 0.76%   |
| HGST HTS541010A9E680 1TB                           | 7         | 0.76%   |
| Samsung SSD 850 EVO 250GB                          | 6         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 6         | 0.66%   |
| Toshiba NVMe SSD Drive 256GB                       | 5         | 0.55%   |
| Toshiba MQ04ABF100 1TB                             | 5         | 0.55%   |
| Seagate ST9500325AS 500GB                          | 5         | 0.55%   |
| Seagate ST500LT012-1DG142 500GB                    | 5         | 0.55%   |
| SanDisk NVMe SSD Drive 256GB                       | 5         | 0.55%   |
| Samsung NVMe SSD Drive 1024GB                      | 5         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 4         | 0.44%   |
| Toshiba MQ01ABD075 752GB                           | 4         | 0.44%   |
| SPCC Solid State Disk 512GB                        | 4         | 0.44%   |
| SK hynix NVMe SSD Drive 256GB                      | 4         | 0.44%   |
| Seagate ST9750420AS 752GB                          | 4         | 0.44%   |
| Seagate ST1000LM048-2E7172 1TB                     | 4         | 0.44%   |
| Samsung SSD 870 EVO 500GB                          | 4         | 0.44%   |
| Phison PS5013 E13 NVMe Controller 512GB            | 4         | 0.44%   |
| Kingston NVMe SSD Drive 512GB                      | 4         | 0.44%   |
| Intel NVMe SSD Drive 512GB                         | 4         | 0.44%   |
| Hitachi HTS547575A9E384 752GB                      | 4         | 0.44%   |
| HGST HTS545050A7E680 500GB                         | 4         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 3         | 0.33%   |
| WDC WD5000LPVX-75V0TT0 500GB                       | 3         | 0.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                       | 3         | 0.33%   |
| Unknown SD/MMC/MS PRO 128GB                        | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 123    | 30.49%  |
| WDC                 | 70        | 91     | 22.95%  |
| Toshiba             | 58        | 74     | 19.02%  |
| HGST                | 33        | 48     | 10.82%  |
| Hitachi             | 31        | 33     | 10.16%  |
| Fujitsu             | 10        | 13     | 3.28%   |
| Unknown             | 3         | 4      | 0.98%   |
| Samsung Electronics | 3         | 4      | 0.98%   |
| TO Exter            | 2         | 2      | 0.66%   |
| JMicron Technology  | 1         | 1      | 0.33%   |
| IBM/Hitachi         | 1         | 2      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 74     | 23.17%  |
| Kingston            | 28        | 33     | 10.81%  |
| SanDisk             | 23        | 28     | 8.88%   |
| A-DATA Technology   | 19        | 28     | 7.34%   |
| WDC                 | 13        | 20     | 5.02%   |
| Transcend           | 10        | 10     | 3.86%   |
| Crucial             | 10        | 13     | 3.86%   |
| SPCC                | 8         | 11     | 3.09%   |
| KingSpec            | 8         | 9      | 3.09%   |
| Intel               | 8         | 11     | 3.09%   |
| Micron Technology   | 7         | 8      | 2.7%    |
| China               | 7         | 9      | 2.7%    |
| PNY                 | 6         | 7      | 2.32%   |
| Toshiba             | 5         | 6      | 1.93%   |
| Team                | 5         | 5      | 1.93%   |
| LITEON              | 5         | 8      | 1.93%   |
| LITEONIT            | 4         | 4      | 1.54%   |
| Apple               | 4         | 6      | 1.54%   |
| SK hynix            | 3         | 3      | 1.16%   |
| Patriot             | 3         | 3      | 1.16%   |
| Lexar               | 3         | 3      | 1.16%   |
| Teclast             | 2         | 2      | 0.77%   |
| Intenso             | 2         | 2      | 0.77%   |
| GOODRAM             | 2         | 2      | 0.77%   |
| AMD                 | 2         | 3      | 0.77%   |
| Wibtek              | 1         | 2      | 0.39%   |
| VT                  | 1         | 1      | 0.39%   |
| Verbatim            | 1         | 1      | 0.39%   |
| Unknown             | 1         | 1      | 0.39%   |
| Seagate             | 1         | 1      | 0.39%   |
| Netac               | 1         | 4      | 0.39%   |
| Indilinx            | 1         | 1      | 0.39%   |
| FORESEE             | 1         | 2      | 0.39%   |
| EDGE                | 1         | 1      | 0.39%   |
| ASMT                | 1         | 1      | 0.39%   |
| ADATA SU            | 1         | 1      | 0.39%   |
| Unknown             | 1         | 1      | 0.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 295       | 395    | 34.99%  |
| NVMe    | 262       | 396    | 31.08%  |
| SSD     | 246       | 325    | 29.18%  |
| MMC     | 36        | 45     | 4.27%   |
| Unknown | 4         | 3      | 0.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 472       | 696    | 59.3%   |
| NVMe | 261       | 394    | 32.79%  |
| MMC  | 36        | 45     | 4.52%   |
| SAS  | 27        | 29     | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 353       | 471    | 66.23%  |
| 0.51-1.0   | 170       | 238    | 31.89%  |
| 1.01-2.0   | 7         | 8      | 1.31%   |
| 3.01-4.0   | 1         | 1      | 0.19%   |
| 10.01-20.0 | 1         | 1      | 0.19%   |
| 4.01-10.0  | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 200       | 26.6%   |
| 101-250        | 197       | 26.2%   |
| 501-1000       | 127       | 16.89%  |
| 1001-2000      | 55        | 7.31%   |
| 1-20           | 54        | 7.18%   |
| 51-100         | 49        | 6.52%   |
| 21-50          | 37        | 4.92%   |
| Unknown        | 15        | 1.99%   |
| More than 3000 | 11        | 1.46%   |
| 2001-3000      | 7         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 292       | 35.92%  |
| 21-50          | 152       | 18.7%   |
| 101-250        | 118       | 14.51%  |
| 51-100         | 102       | 12.55%  |
| 251-500        | 70        | 8.61%   |
| 501-1000       | 45        | 5.54%   |
| Unknown        | 15        | 1.85%   |
| 1001-2000      | 12        | 1.48%   |
| 2001-3000      | 4         | 0.49%   |
| More than 3000 | 3         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                          | Notebooks | Drives | Percent |
|----------------------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                                      | 3         | 3      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                             | 3         | 3      | 6.25%   |
| Toshiba MQ01ABF050 500GB                                       | 2         | 2      | 4.17%   |
| Intel SSDSC2CW120A3 120GB                                      | 2         | 2      | 4.17%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                                 | 1         | 1      | 2.08%   |
| WDC WD5000LPVX-55V0TT0 500GB                                   | 1         | 1      | 2.08%   |
| WDC WD5000BEVT-75A0RT0 500GB                                   | 1         | 1      | 2.08%   |
| WDC WD3200BEVT-80A0RT0 320GB                                   | 1         | 1      | 2.08%   |
| WDC WD1600BEVT-80A23T0 160GB                                   | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD100 1TB                                         | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD050 500GB                                       | 1         | 1      | 2.08%   |
| Toshiba MK2552GSX 250GB                                        | 1         | 3      | 2.08%   |
| Toshiba MK2035GSS 200GB                                        | 1         | 1      | 2.08%   |
| Toshiba MK1637GSX 160GB                                        | 1         | 1      | 2.08%   |
| SPCC M.2 PCIe SSD 256GB                                        | 1         | 1      | 2.08%   |
| SK hynix HFS256G32TNH-73A0A 256GB SSD                          | 1         | 1      | 2.08%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                           | 1         | 1      | 2.08%   |
| Seagate ST9500420AS 500GB                                      | 1         | 2      | 2.08%   |
| Seagate ST94019A 40GB                                          | 1         | 1      | 2.08%   |
| Seagate ST500LT012-9WS142 500GB                                | 1         | 1      | 2.08%   |
| Seagate ST500LT012-1DG142 500GB                                | 1         | 1      | 2.08%   |
| Seagate ST500LM021-1KJ152 500GB                                | 1         | 1      | 2.08%   |
| Seagate ST500LM000-1EJ162 500GB                                | 1         | 1      | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                                 | 1         | 1      | 2.08%   |
| Seagate ST1000LM014-1EJ164 1TB                                 | 1         | 1      | 2.08%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1         | 1      | 2.08%   |
| KingSpec P3-256 256GB SSD                                      | 1         | 1      | 2.08%   |
| KingSpec P3-128 128GB SSD                                      | 1         | 1      | 2.08%   |
| Hitachi HTS723216L9A360 160GB                                  | 1         | 1      | 2.08%   |
| Hitachi HTS547550A9E384 500GB                                  | 1         | 1      | 2.08%   |
| Hitachi HTS545050A7E380 500GB                                  | 1         | 1      | 2.08%   |
| Hitachi HTS543225L9SA00 250GB                                  | 1         | 2      | 2.08%   |
| Hitachi HTS543225L9A300 250GB                                  | 1         | 1      | 2.08%   |
| Hitachi HTS543216L9SA00 160GB                                  | 1         | 1      | 2.08%   |
| Hitachi HTS542525K9SA00 250GB                                  | 1         | 1      | 2.08%   |
| Hitachi HTS541616J9SA00 160GB                                  | 1         | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB                                       | 1         | 1      | 2.08%   |
| Fujitsu MJA2160BH G2 160GB                                     | 1         | 2      | 2.08%   |
| China SSD 120GB                                                | 1         | 1      | 2.08%   |
| A-DATA Technology SX300 64GB SSD                               | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 15     | 29.17%  |
| Hitachi             | 8         | 9      | 16.67%  |
| Toshiba             | 7         | 9      | 14.58%  |
| WDC                 | 5         | 5      | 10.42%  |
| A-DATA Technology   | 3         | 3      | 6.25%   |
| SK hynix            | 2         | 2      | 4.17%   |
| KingSpec            | 2         | 2      | 4.17%   |
| Intel               | 2         | 2      | 4.17%   |
| SPCC                | 1         | 1      | 2.08%   |
| Samsung Electronics | 1         | 1      | 2.08%   |
| HGST                | 1         | 1      | 2.08%   |
| Fujitsu             | 1         | 2      | 2.08%   |
| China               | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 15     | 40%     |
| Hitachi | 8         | 9      | 22.86%  |
| Toshiba | 7         | 9      | 20%     |
| WDC     | 4         | 4      | 11.43%  |
| HGST    | 1         | 1      | 2.86%   |
| Fujitsu | 1         | 2      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 40     | 72.34%  |
| SSD  | 10        | 10     | 21.28%  |
| NVMe | 3         | 3      | 6.38%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 50%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 428       | 699    | 56.91%  |
| Works    | 276       | 410    | 36.7%   |
| Malfunc  | 46        | 53     | 6.12%   |
| Failed   | 2         | 2      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 510       | 60.43%  |
| Samsung Electronics              | 88        | 10.43%  |
| AMD                              | 69        | 8.18%   |
| SK hynix                         | 34        | 4.03%   |
| SanDisk                          | 33        | 3.91%   |
| Kingston Technology Company      | 23        | 2.73%   |
| Micron Technology                | 22        | 2.61%   |
| KIOXIA                           | 15        | 1.78%   |
| Toshiba America Info Systems     | 14        | 1.66%   |
| Phison Electronics               | 7         | 0.83%   |
| Realtek Semiconductor            | 6         | 0.71%   |
| Silicon Motion                   | 4         | 0.47%   |
| Micron/Crucial Technology        | 3         | 0.36%   |
| Union Memory (Shenzhen)          | 2         | 0.24%   |
| Transcend                        | 2         | 0.24%   |
| Marvell Technology Group         | 2         | 0.24%   |
| Lenovo                           | 2         | 0.24%   |
| ADATA Technology                 | 2         | 0.24%   |
| VIA Technologies                 | 1         | 0.12%   |
| Solid State Storage Technology   | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| O2 Micro                         | 1         | 0.12%   |
| Nvidia                           | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 68        | 7.47%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 57        | 6.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 42        | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 41        | 4.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 38        | 4.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 36        | 3.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 33        | 3.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 27        | 2.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 26        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 25        | 2.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 21        | 2.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 2.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 2.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 18        | 1.98%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 16        | 1.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 1.54%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 13        | 1.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 1.43%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 12        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 1.21%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 10        | 1.1%    |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 9         | 0.99%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 9         | 0.99%   |
| Intel SSD 660P Series                                                            | 9         | 0.99%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 9         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 0.99%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 8         | 0.88%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 8         | 0.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 7         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 6         | 0.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 6         | 0.66%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 5         | 0.55%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 5         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 489       | 56.08%  |
| NVMe | 265       | 30.39%  |
| RAID | 61        | 7%      |
| IDE  | 57        | 6.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 581       | 81.83%  |
| AMD          | 128       | 18.03%  |
| CentaurHauls | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 13        | 1.83%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 12        | 1.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 11        | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 10        | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 9         | 1.27%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 9         | 1.27%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 8         | 1.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 8         | 1.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 8         | 1.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 7         | 0.99%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 7         | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 7         | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 7         | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 7         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 7         | 0.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 7         | 0.99%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 7         | 0.99%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 6         | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 6         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 0.85%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 6         | 0.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.85%   |
| Intel 12th Gen Core i5-1235U             | 6         | 0.85%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 6         | 0.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 6         | 0.85%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 6         | 0.85%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.7%    |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz        | 5         | 0.7%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 5         | 0.7%    |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 5         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz        | 5         | 0.7%    |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 5         | 0.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz        | 5         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz        | 5         | 0.7%    |
| Intel Core i3-2310M CPU @ 2.10GHz        | 5         | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 5         | 0.7%    |
| AMD Ryzen 7 6800H with Radeon Graphics   | 5         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics   | 5         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 165       | 23.24%  |
| Intel Core i5           | 147       | 20.7%   |
| Other                   | 64        | 9.01%   |
| Intel Core i3           | 51        | 7.18%   |
| AMD Ryzen 7             | 42        | 5.92%   |
| Intel Core 2 Duo        | 41        | 5.77%   |
| Intel Celeron           | 34        | 4.79%   |
| Intel Pentium           | 32        | 4.51%   |
| AMD Ryzen 5             | 27        | 3.8%    |
| AMD Ryzen 3             | 13        | 1.83%   |
| Intel Atom              | 11        | 1.55%   |
| AMD Ryzen 7 PRO         | 9         | 1.27%   |
| Intel Pentium Dual-Core | 7         | 0.99%   |
| Intel Pentium Silver    | 6         | 0.85%   |
| Intel Pentium Dual      | 6         | 0.85%   |
| AMD Ryzen 5 PRO         | 6         | 0.85%   |
| Intel Core 2            | 5         | 0.7%    |
| AMD A6                  | 5         | 0.7%    |
| Intel Genuine           | 3         | 0.42%   |
| AMD E1                  | 3         | 0.42%   |
| AMD E                   | 3         | 0.42%   |
| Intel Pentium M         | 2         | 0.28%   |
| Intel Core i9           | 2         | 0.28%   |
| Intel Celeron Dual-Core | 2         | 0.28%   |
| AMD Turion 64 X2 Mobile | 2         | 0.28%   |
| AMD Ryzen 9             | 2         | 0.28%   |
| AMD A10                 | 2         | 0.28%   |
| Intel Xeon              | 1         | 0.14%   |
| Intel Mobile Pentium 4  | 1         | 0.14%   |
| Intel Core m3           | 1         | 0.14%   |
| Intel Core M            | 1         | 0.14%   |
| Intel Core Duo          | 1         | 0.14%   |
| Intel Core 2 Solo       | 1         | 0.14%   |
| Intel Core              | 1         | 0.14%   |
| Intel Celeron M         | 1         | 0.14%   |
| CentaurHauls VIA Nano   | 1         | 0.14%   |
| AMD Turion 64 Mobile    | 1         | 0.14%   |
| AMD Sempron             | 1         | 0.14%   |
| AMD Phenom II           | 1         | 0.14%   |
| AMD FX                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 337       | 47.4%   |
| 4       | 219       | 30.8%   |
| 6       | 57        | 8.02%   |
| 8       | 56        | 7.88%   |
| 1       | 17        | 2.39%   |
| 10      | 12        | 1.69%   |
| 14      | 6         | 0.84%   |
| 12      | 4         | 0.56%   |
| 24      | 1         | 0.14%   |
| 3       | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 710       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 524       | 73.7%   |
| 1       | 185       | 26.02%  |
| 4       | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 686       | 96.08%  |
| Unknown        | 17        | 2.38%   |
| 32-bit         | 11        | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 240       | 31.83%  |
| 0x306a9    | 48        | 6.37%   |
| 0x206a7    | 44        | 5.84%   |
| 0x1067a    | 25        | 3.32%   |
| 0x806ec    | 23        | 3.05%   |
| 0x306d4    | 23        | 3.05%   |
| 0x306c3    | 20        | 2.65%   |
| 0x406e3    | 17        | 2.25%   |
| 0x40651    | 17        | 2.25%   |
| 0x20655    | 17        | 2.25%   |
| 0x906ea    | 16        | 2.12%   |
| 0x806c1    | 16        | 2.12%   |
| 0x806ea    | 14        | 1.86%   |
| 0x6fd      | 13        | 1.72%   |
| 0x906e9    | 12        | 1.59%   |
| 0x0a50000c | 11        | 1.46%   |
| 0x706a1    | 10        | 1.33%   |
| 0x506e3    | 10        | 1.33%   |
| 0x506c9    | 10        | 1.33%   |
| 0x10676    | 10        | 1.33%   |
| 0x08608103 | 10        | 1.33%   |
| 0x806e9    | 8         | 1.06%   |
| 0x08108109 | 8         | 1.06%   |
| 0xa0652    | 7         | 0.93%   |
| 0x0a50000d | 7         | 0.93%   |
| 0x08108102 | 7         | 0.93%   |
| 0x806eb    | 6         | 0.8%    |
| 0x406c3    | 6         | 0.8%    |
| 0x08600106 | 6         | 0.8%    |
| 0x906a4    | 5         | 0.66%   |
| 0x706e5    | 5         | 0.66%   |
| 0x0a404102 | 5         | 0.66%   |
| 0x08600104 | 5         | 0.66%   |
| 0x906a3    | 4         | 0.53%   |
| 0x6f6      | 4         | 0.53%   |
| 0x106c2    | 4         | 0.53%   |
| 0x906ed    | 3         | 0.4%    |
| 0x806d1    | 3         | 0.4%    |
| 0x106e5    | 3         | 0.4%    |
| 0x0a704103 | 3         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 111       | 15.61%  |
| IvyBridge        | 71        | 9.99%   |
| SandyBridge      | 55        | 7.74%   |
| Haswell          | 50        | 7.03%   |
| Unknown          | 48        | 6.75%   |
| Penryn           | 40        | 5.63%   |
| Skylake          | 35        | 4.92%   |
| TigerLake        | 29        | 4.08%   |
| Broadwell        | 28        | 3.94%   |
| Zen 3            | 25        | 3.52%   |
| Westmere         | 25        | 3.52%   |
| Core             | 25        | 3.52%   |
| Zen 2            | 21        | 2.95%   |
| Alderlake Hybrid | 19        | 2.67%   |
| Zen+             | 18        | 2.53%   |
| Silvermont       | 18        | 2.53%   |
| Goldmont plus    | 14        | 1.97%   |
| Goldmont         | 14        | 1.97%   |
| CometLake        | 11        | 1.55%   |
| IceLake          | 9         | 1.27%   |
| Excavator        | 6         | 0.84%   |
| Bonnell          | 6         | 0.84%   |
| P6               | 5         | 0.7%    |
| Bobcat           | 5         | 0.7%    |
| Nehalem          | 4         | 0.56%   |
| Zen              | 3         | 0.42%   |
| K8 Hammer        | 3         | 0.42%   |
| Jaguar           | 3         | 0.42%   |
| Piledriver       | 2         | 0.28%   |
| K10              | 2         | 0.28%   |
| Tremont          | 1         | 0.14%   |
| Steamroller      | 1         | 0.14%   |
| Puma             | 1         | 0.14%   |
| NetBurst         | 1         | 0.14%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| K10 Llano        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 522       | 55.12%  |
| Nvidia                           | 231       | 24.39%  |
| AMD                              | 192       | 20.27%  |
| VIA Technologies                 | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 6.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 48        | 4.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 2.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 2.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 2.67%   |
| Intel HD Graphics 5500                                                                   | 25        | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 2.16%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 21        | 2.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.85%   |
| Intel HD Graphics 630                                                                    | 17        | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 1.75%   |
| Intel UHD Graphics 620                                                                   | 15        | 1.54%   |
| AMD Lucienne                                                                             | 15        | 1.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.54%   |
| Intel HD Graphics 620                                                                    | 14        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.13%   |
| Intel HD Graphics 530                                                                    | 11        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.13%   |
| AMD Rembrandt [Radeon 680M]                                                              | 11        | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.03%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 1.03%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.92%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 9         | 0.92%   |
| AMD Barcelo                                                                              | 9         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.82%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 8         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 7         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 308       | 43.02%  |
| Intel + Nvidia | 179       | 25%     |
| 1 x AMD        | 124       | 17.32%  |
| Intel + AMD    | 35        | 4.89%   |
| 1 x Nvidia     | 32        | 4.47%   |
| AMD + Nvidia   | 23        | 3.21%   |
| 2 x AMD        | 10        | 1.4%    |
| 2 x Intel      | 2         | 0.28%   |
| Other          | 1         | 0.14%   |
| 1 x VIA        | 1         | 0.14%   |
| 1 x SiS        | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 589       | 81.13%  |
| Proprietary | 109       | 15.01%  |
| Unknown     | 28        | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 447       | 60.65%  |
| 1.01-2.0   | 101       | 13.7%   |
| 0.01-0.5   | 81        | 10.99%  |
| 3.01-4.0   | 44        | 5.97%   |
| 0.51-1.0   | 42        | 5.7%    |
| 5.01-6.0   | 15        | 2.04%   |
| 7.01-8.0   | 3         | 0.41%   |
| 2.01-3.0   | 2         | 0.27%   |
| 8.01-16.0  | 2         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 179       | 22.52%  |
| AU Optronics            | 126       | 15.85%  |
| BOE                     | 94        | 11.82%  |
| Chimei Innolux          | 91        | 11.45%  |
| Samsung Electronics     | 68        | 8.55%   |
| Dell                    | 33        | 4.15%   |
| Lenovo                  | 24        | 3.02%   |
| Chi Mei Optoelectronics | 23        | 2.89%   |
| Philips                 | 15        | 1.89%   |
| PANDA                   | 15        | 1.89%   |
| LG Philips              | 12        | 1.51%   |
| Goldstar                | 12        | 1.51%   |
| Hewlett-Packard         | 11        | 1.38%   |
| Sharp                   | 10        | 1.26%   |
| Apple                   | 8         | 1.01%   |
| CSO                     | 7         | 0.88%   |
| BenQ                    | 7         | 0.88%   |
| Acer                    | 6         | 0.75%   |
| AOC                     | 5         | 0.63%   |
| CPT                     | 4         | 0.5%    |
| Ancor Communications    | 4         | 0.5%    |
| Vestel Elektronik       | 3         | 0.38%   |
| Valve                   | 3         | 0.38%   |
| Toshiba                 | 3         | 0.38%   |
| Sony                    | 3         | 0.38%   |
| InfoVision              | 3         | 0.38%   |
| InnoLux Display         | 2         | 0.25%   |
| Iiyama                  | 2         | 0.25%   |
| HannStar                | 2         | 0.25%   |
| BOE Technology Group    | 2         | 0.25%   |
| ASUSTek Computer        | 2         | 0.25%   |
| ViewSonic               | 1         | 0.13%   |
| TMX                     | 1         | 0.13%   |
| Seiko/Epson             | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| NEC Computers           | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| MPI                     | 1         | 0.13%   |
| LGD                     | 1         | 0.13%   |
| KDC                     | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 1.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 1.25%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 1%      |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.87%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.87%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.75%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 0.75%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 5         | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.62%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.5%    |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 4         | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 4         | 0.5%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.5%    |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.5%    |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 3         | 0.37%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 3         | 0.37%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.37%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 3         | 0.37%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.37%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.37%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.37%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 0.37%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 3         | 0.37%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 3         | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 342       | 46.15%  |
| 1366x768 (WXGA)    | 195       | 26.32%  |
| 1280x800 (WXGA)    | 36        | 4.86%   |
| 1600x900 (HD+)     | 35        | 4.72%   |
| 3840x2160 (4K)     | 22        | 2.97%   |
| 1920x1200 (WUXGA)  | 20        | 2.7%    |
| 2560x1440 (QHD)    | 15        | 2.02%   |
| 2560x1600          | 13        | 1.75%   |
| 1680x1050 (WSXGA+) | 12        | 1.62%   |
| 1440x900 (WXGA+)   | 8         | 1.08%   |
| 1280x1024 (SXGA)   | 7         | 0.94%   |
| 1024x600           | 5         | 0.67%   |
| 800x1280           | 4         | 0.54%   |
| 2880x1800          | 4         | 0.54%   |
| 2560x1080          | 4         | 0.54%   |
| 3840x2400          | 3         | 0.4%    |
| 3440x1440          | 2         | 0.27%   |
| 800x480            | 1         | 0.13%   |
| 3840x1080          | 1         | 0.13%   |
| 3456x2160          | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3072x1920          | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 2160x1440          | 1         | 0.13%   |
| 2048x1152          | 1         | 0.13%   |
| 1600x1200          | 1         | 0.13%   |
| 1280x960           | 1         | 0.13%   |
| 1280x720 (HD)      | 1         | 0.13%   |
| 1024x768 (XGA)     | 1         | 0.13%   |
| Unknown            | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 387       | 48.8%   |
| 14      | 77        | 9.71%   |
| 13      | 69        | 8.7%    |
| 17      | 51        | 6.43%   |
| 24      | 36        | 4.54%   |
| 12      | 30        | 3.78%   |
| 16      | 22        | 2.77%   |
| 23      | 21        | 2.65%   |
| 27      | 17        | 2.14%   |
| 21      | 17        | 2.14%   |
| 11      | 8         | 1.01%   |
| 34      | 6         | 0.76%   |
| 18      | 6         | 0.76%   |
| 10      | 6         | 0.76%   |
| 22      | 5         | 0.63%   |
| 84      | 4         | 0.5%    |
| 54      | 4         | 0.5%    |
| 19      | 4         | 0.5%    |
| Unknown | 4         | 0.5%    |
| 20      | 3         | 0.38%   |
| 7       | 3         | 0.38%   |
| 72      | 2         | 0.25%   |
| 40      | 2         | 0.25%   |
| 32      | 2         | 0.25%   |
| 28      | 2         | 0.25%   |
| 65      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |
| 31      | 1         | 0.13%   |
| 25      | 1         | 0.13%   |
| 3       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 514       | 65.06%  |
| 201-300     | 78        | 9.87%   |
| 501-600     | 70        | 8.86%   |
| 351-400     | 63        | 7.97%   |
| 401-500     | 30        | 3.8%    |
| 701-800     | 9         | 1.14%   |
| 1501-2000   | 6         | 0.76%   |
| 601-700     | 5         | 0.63%   |
| 1001-1500   | 5         | 0.63%   |
| 1-100       | 4         | 0.51%   |
| Unknown     | 4         | 0.51%   |
| 801-900     | 2         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 575       | 81.56%  |
| 16/10   | 101       | 14.33%  |
| 5/4     | 8         | 1.13%   |
| 21/9    | 6         | 0.85%   |
| 3/2     | 4         | 0.57%   |
| Unknown | 4         | 0.57%   |
| 0.67    | 3         | 0.43%   |
| 4/3     | 2         | 0.28%   |
| 6/5     | 1         | 0.14%   |
| 1.00    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 385       | 48.8%   |
| 81-90          | 118       | 14.96%  |
| 201-250        | 57        | 7.22%   |
| 121-130        | 43        | 5.45%   |
| 61-70          | 30        | 3.8%    |
| 71-80          | 26        | 3.3%    |
| 111-120        | 21        | 2.66%   |
| 301-350        | 17        | 2.15%   |
| 151-200        | 15        | 1.9%    |
| 251-300        | 14        | 1.77%   |
| 351-500        | 12        | 1.52%   |
| More than 1000 | 10        | 1.27%   |
| 51-60          | 8         | 1.01%   |
| 141-150        | 8         | 1.01%   |
| 131-140        | 7         | 0.89%   |
| 41-50          | 6         | 0.76%   |
| 1-40           | 4         | 0.51%   |
| Unknown        | 4         | 0.51%   |
| 501-1000       | 2         | 0.25%   |
| 91-100         | 2         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 346       | 44.53%  |
| 101-120       | 213       | 27.41%  |
| 51-100        | 140       | 18.02%  |
| 161-240       | 46        | 5.92%   |
| More than 240 | 22        | 2.83%   |
| 1-50          | 6         | 0.77%   |
| Unknown       | 4         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 584       | 79.46%  |
| 2     | 110       | 14.97%  |
| 0     | 27        | 3.67%   |
| 3     | 14        | 1.9%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 384       | 32.49%  |
| Realtek Semiconductor             | 377       | 31.9%   |
| Qualcomm Atheros                  | 149       | 12.61%  |
| Broadcom                          | 68        | 5.75%   |
| MediaTek                          | 36        | 3.05%   |
| Broadcom Limited                  | 24        | 2.03%   |
| Ralink                            | 23        | 1.95%   |
| TP-Link                           | 19        | 1.61%   |
| Ericsson Business Mobile Networks | 15        | 1.27%   |
| Sierra Wireless                   | 12        | 1.02%   |
| Marvell Technology Group          | 12        | 1.02%   |
| Dell                              | 6         | 0.51%   |
| Ralink Technology                 | 5         | 0.42%   |
| Lenovo                            | 5         | 0.42%   |
| Hewlett-Packard                   | 5         | 0.42%   |
| Qualcomm Atheros Communications   | 4         | 0.34%   |
| Motorola PCS                      | 4         | 0.34%   |
| Huawei Technologies               | 3         | 0.25%   |
| DisplayLink                       | 3         | 0.25%   |
| ASIX Electronics                  | 3         | 0.25%   |
| AMD                               | 3         | 0.25%   |
| Xiaomi                            | 2         | 0.17%   |
| Toshiba                           | 2         | 0.17%   |
| Samsung Electronics               | 2         | 0.17%   |
| Qualcomm                          | 2         | 0.17%   |
| Google                            | 2         | 0.17%   |
| Davicom Semiconductor             | 2         | 0.17%   |
| D-Link                            | 2         | 0.17%   |
| Quectel Wireless Solutions        | 1         | 0.08%   |
| Nvidia                            | 1         | 0.08%   |
| NetGear                           | 1         | 0.08%   |
| Micro Star International          | 1         | 0.08%   |
| JMicron Technology                | 1         | 0.08%   |
| ICS Advent                        | 1         | 0.08%   |
| Attansic Technology               | 1         | 0.08%   |
| Apple                             | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 236       | 16.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 66        | 4.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 33        | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 31        | 2.17%   |
| Intel Wireless 8265 / 8275                                             | 30        | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 27        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 25        | 1.75%   |
| Intel Wi-Fi 6 AX201                                                    | 24        | 1.68%   |
| Intel Wireless 7260                                                    | 23        | 1.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 1.54%   |
| Intel Wireless 7265                                                    | 22        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 21        | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 19        | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 19        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                    | 18        | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 17        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 15        | 1.05%   |
| Intel Wireless 3160                                                    | 15        | 1.05%   |
| Intel Wireless 8260                                                    | 14        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                          | 14        | 0.98%   |
| Intel WiFi Link 5100                                                   | 13        | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 12        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 12        | 0.84%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 11        | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 11        | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 11        | 0.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                | 11        | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 11        | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 10        | 0.7%    |
| Intel Centrino Ultimate-N 6300                                         | 10        | 0.7%    |
| Intel 82577LM Gigabit Network Connection                               | 10        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 10        | 0.7%    |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.63%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 365       | 48.41%  |
| Qualcomm Atheros                | 124       | 16.45%  |
| Realtek Semiconductor           | 103       | 13.66%  |
| Broadcom                        | 51        | 6.76%   |
| MediaTek                        | 36        | 4.77%   |
| Ralink                          | 23        | 3.05%   |
| TP-Link                         | 14        | 1.86%   |
| Sierra Wireless                 | 12        | 1.59%   |
| Broadcom Limited                | 8         | 1.06%   |
| Ralink Technology               | 5         | 0.66%   |
| Qualcomm Atheros Communications | 4         | 0.53%   |
| Dell                            | 3         | 0.4%    |
| Qualcomm                        | 2         | 0.27%   |
| Quectel Wireless Solutions      | 1         | 0.13%   |
| NetGear                         | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 31        | 4.09%   |
| Intel Wireless 8265 / 8275                                     | 30        | 3.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 27        | 3.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 3.3%    |
| Intel Wi-Fi 6 AX201                                            | 24        | 3.17%   |
| Intel Wireless 7260                                            | 23        | 3.03%   |
| Intel Wireless 7265                                            | 22        | 2.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21        | 2.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 2.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 19        | 2.51%   |
| Intel Wi-Fi 6 AX200                                            | 18        | 2.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 2.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 1.98%   |
| Intel Wireless 3160                                            | 15        | 1.98%   |
| Intel Wireless 8260                                            | 14        | 1.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.85%   |
| Intel WiFi Link 5100                                           | 13        | 1.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 12        | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 1.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 1.45%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 1.45%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 11        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 10        | 1.32%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 1.19%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 8         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 1.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 8         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 7         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 0.92%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 6         | 0.79%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                  | 6         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 333       | 52.77%  |
| Intel                    | 166       | 26.31%  |
| Qualcomm Atheros         | 43        | 6.81%   |
| Broadcom                 | 25        | 3.96%   |
| Broadcom Limited         | 16        | 2.54%   |
| Marvell Technology Group | 12        | 1.9%    |
| TP-Link                  | 5         | 0.79%   |
| Lenovo                   | 4         | 0.63%   |
| Motorola PCS             | 3         | 0.48%   |
| DisplayLink              | 3         | 0.48%   |
| ASIX Electronics         | 3         | 0.48%   |
| Xiaomi                   | 2         | 0.32%   |
| Samsung Electronics      | 2         | 0.32%   |
| Huawei Technologies      | 2         | 0.32%   |
| Google                   | 2         | 0.32%   |
| Davicom Semiconductor    | 2         | 0.32%   |
| D-Link                   | 2         | 0.32%   |
| Nvidia                   | 1         | 0.16%   |
| MediaTek                 | 1         | 0.16%   |
| JMicron Technology       | 1         | 0.16%   |
| ICS Advent               | 1         | 0.16%   |
| Attansic Technology      | 1         | 0.16%   |
| Apple                    | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 236       | 37.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 66        | 10.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 39        | 6.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 3.45%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 1.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 1.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 1.73%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 1.57%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 1.41%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.26%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.1%    |
| Intel Ethernet Connection (6) I219-V                                   | 7         | 1.1%    |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.94%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.94%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 6         | 0.94%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 5         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.78%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.78%   |
| Intel Ethernet Connection (16) I219-V                                  | 5         | 0.78%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 5         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 5         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 4         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.47%   |
| Motorola PCS moto g(7) power                                           | 3         | 0.47%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 3         | 0.47%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 3         | 0.47%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                  | 3         | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 3         | 0.47%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 3         | 0.47%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 3         | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 704       | 52.42%  |
| Ethernet | 607       | 45.2%   |
| Modem    | 31        | 2.31%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 595       | 77.57%  |
| Ethernet | 172       | 22.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 566       | 79.61%  |
| 1     | 133       | 18.71%  |
| 3     | 7         | 0.98%   |
| 0     | 5         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 691       | 95.31%  |
| Yes  | 34        | 4.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 247       | 43.11%  |
| Realtek Semiconductor           | 52        | 9.08%   |
| Qualcomm Atheros Communications | 45        | 7.85%   |
| IMC Networks                    | 39        | 6.81%   |
| Broadcom                        | 37        | 6.46%   |
| Foxconn / Hon Hai               | 30        | 5.24%   |
| Lite-On Technology              | 28        | 4.89%   |
| Toshiba                         | 17        | 2.97%   |
| Hewlett-Packard                 | 16        | 2.79%   |
| Dell                            | 15        | 2.62%   |
| Ralink                          | 12        | 2.09%   |
| Cambridge Silicon Radio         | 8         | 1.4%    |
| Apple                           | 7         | 1.22%   |
| Foxconn International           | 6         | 1.05%   |
| MediaTek                        | 4         | 0.7%    |
| TP-Link                         | 2         | 0.35%   |
| Realtek                         | 2         | 0.35%   |
| Ralink Technology               | 2         | 0.35%   |
| ASUSTek Computer                | 2         | 0.35%   |
| USI                             | 1         | 0.17%   |
| Belkin Components               | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 60        | 10.47%  |
| Intel AX201 Bluetooth                               | 55        | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 7.33%   |
| Intel Bluetooth Device                              | 41        | 7.16%   |
| Realtek Bluetooth Radio                             | 34        | 5.93%   |
| Qualcomm Atheros  Bluetooth Device                  | 26        | 4.54%   |
| Intel AX200 Bluetooth                               | 17        | 2.97%   |
| IMC Networks Bluetooth Radio                        | 17        | 2.97%   |
| IMC Networks Wireless_Device                        | 13        | 2.27%   |
| Ralink RT3290 Bluetooth                             | 12        | 2.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 1.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1.57%   |
| Lite-On Bluetooth Device                            | 9         | 1.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 1.57%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 1.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.4%    |
| IMC Networks Bluetooth Device                       | 8         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.4%    |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.4%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 1.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 1.4%    |
| Toshiba Integrated Bluetooth HCI                    | 7         | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.22%   |
| Intel AX211 Bluetooth                               | 7         | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.22%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.05%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 1.05%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 0.7%    |
| Toshiba RT Bluetooth Radio                          | 3         | 0.52%   |
| Toshiba Bluetooth Device                            | 3         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.52%   |
| MediaTek Wireless_Device                            | 3         | 0.52%   |
| Lite-On Wireless_Device                             | 3         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 571       | 64.59%  |
| AMD                              | 152       | 17.19%  |
| Nvidia                           | 114       | 12.9%   |
| Lenovo                           | 7         | 0.79%   |
| Razer USA                        | 5         | 0.57%   |
| C-Media Electronics              | 5         | 0.57%   |
| GN Netcom                        | 4         | 0.45%   |
| Realtek Semiconductor            | 3         | 0.34%   |
| Logitech                         | 3         | 0.34%   |
| JMTek                            | 3         | 0.34%   |
| Creative Technology              | 3         | 0.34%   |
| Plantronics                      | 2         | 0.23%   |
| ZOOM                             | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| Sony                             | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| No brand                         | 1         | 0.11%   |
| Native Instruments               | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| GYROCOM C&C                      | 1         | 0.11%   |
| Generalplus Technology           | 1         | 0.11%   |
| ASUSTek Computer                 | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |
| A4Tech                           | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 98        | 9.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 78        | 7.28%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 54        | 5.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 52        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 48        | 4.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 45        | 4.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 29        | 2.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 29        | 2.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 28        | 2.61%   |
| Intel Broadwell-U Audio Controller                                                                | 28        | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 27        | 2.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.15%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 21        | 1.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 1.87%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 18        | 1.68%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 1.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 1.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 1.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.12%   |
| Nvidia Audio device                                                                               | 12        | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.12%   |
| Intel Comet Lake PCH cAVS                                                                         | 11        | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 10        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 0.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 0.84%   |
| AMD FCH Azalia Controller                                                                         | 9         | 0.84%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 128       | 26.56%  |
| SK hynix                                | 103       | 21.37%  |
| Micron Technology                       | 61        | 12.66%  |
| Kingston                                | 56        | 11.62%  |
| Unknown                                 | 27        | 5.6%    |
| Ramaxel Technology                      | 20        | 4.15%   |
| A-DATA Technology                       | 20        | 4.15%   |
| Transcend                               | 11        | 2.28%   |
| Nanya Technology                        | 10        | 2.07%   |
| Elpida                                  | 9         | 1.87%   |
| Corsair                                 | 8         | 1.66%   |
| Apacer                                  | 7         | 1.45%   |
| Team                                    | 5         | 1.04%   |
| Crucial                                 | 4         | 0.83%   |
| Silicon Power Computer & Communications | 2         | 0.41%   |
| ASint Technology                        | 2         | 0.41%   |
| Unknown (ABCD)                          | 1         | 0.21%   |
| Unifosa                                 | 1         | 0.21%   |
| Silicon Power                           | 1         | 0.21%   |
| Qimonda                                 | 1         | 0.21%   |
| Neo Forza                               | 1         | 0.21%   |
| GOODRAM                                 | 1         | 0.21%   |
| fef5                                    | 1         | 0.21%   |
| A Force                                 | 1         | 0.21%   |
| Unknown                                 | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 10        | 1.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 8         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s    | 7         | 1.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s       | 6         | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 6         | 1.17%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 0.98%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 5         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 5         | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s        | 5         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 5         | 0.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 0.78%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 4         | 0.78%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 4         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.78%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 4         | 0.78%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s     | 4         | 0.78%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 4         | 0.78%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                  | 4         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 3         | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 3         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 3         | 0.59%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s      | 3         | 0.59%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 3         | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 0.59%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 3         | 0.59%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 3         | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s    | 3         | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 3         | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 3         | 0.59%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 3         | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s    | 3         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 3         | 0.59%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 3         | 0.59%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s        | 3         | 0.59%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s        | 3         | 0.59%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 3         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 3         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 172       | 44.91%  |
| DDR3    | 145       | 37.86%  |
| DDR2    | 13        | 3.39%   |
| DDR5    | 12        | 3.13%   |
| SDRAM   | 10        | 2.61%   |
| LPDDR4  | 8         | 2.09%   |
| LPDDR5  | 6         | 1.57%   |
| Unknown | 5         | 1.31%   |
| LPDDR3  | 4         | 1.04%   |
| DRAM    | 4         | 1.04%   |
| DDR     | 4         | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 353       | 93.39%  |
| Row Of Chips | 17        | 4.5%    |
| Chip         | 4         | 1.06%   |
| DIMM         | 3         | 0.79%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 154       | 36.84%  |
| 4096    | 118       | 28.23%  |
| 16384   | 65        | 15.55%  |
| 2048    | 44        | 10.53%  |
| 32768   | 20        | 4.78%   |
| 1024    | 15        | 3.59%   |
| 512     | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 97        | 23.21%  |
| 3200    | 92        | 22.01%  |
| 2667    | 70        | 16.75%  |
| 1334    | 31        | 7.42%   |
| 2400    | 21        | 5.02%   |
| 1333    | 18        | 4.31%   |
| 667     | 12        | 2.87%   |
| Unknown | 12        | 2.87%   |
| 2133    | 8         | 1.91%   |
| 4800    | 7         | 1.67%   |
| 3266    | 6         | 1.44%   |
| 1067    | 6         | 1.44%   |
| 6400    | 5         | 1.2%    |
| 5600    | 5         | 1.2%    |
| 4199    | 5         | 1.2%    |
| 1066    | 5         | 1.2%    |
| 2048    | 4         | 0.96%   |
| 1867    | 3         | 0.72%   |
| 800     | 3         | 0.72%   |
| 4266    | 2         | 0.48%   |
| 975     | 2         | 0.48%   |
| 7500    | 1         | 0.24%   |
| 4267    | 1         | 0.24%   |
| 2933    | 1         | 0.24%   |
| 1866    | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 2         | 25%     |
| Samsung Electronics | 2         | 25%     |
| Canon               | 2         | 25%     |
| STMicroelectronics  | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 12.5%   |
| Seiko Epson ET-2820 Series                                | 1         | 12.5%   |
| Seiko Epson ET-2710 Series                                | 1         | 12.5%   |
| Samsung M332x 382x 402x Series                            | 1         | 12.5%   |
| Samsung M267x 287x Series                                 | 1         | 12.5%   |
| Canon PIXMA MP240                                         | 1         | 12.5%   |
| Canon MF3200 series                                       | 1         | 12.5%   |
| Brother DCP-7055 scanner/printer                          | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 159       | 25.32%  |
| IMC Networks                           | 76        | 12.1%   |
| Microdia                               | 51        | 8.12%   |
| Realtek Semiconductor                  | 48        | 7.64%   |
| Quanta                                 | 46        | 7.32%   |
| Bison Electronics                      | 46        | 7.32%   |
| Sunplus Innovation Technology          | 39        | 6.21%   |
| Syntek                                 | 19        | 3.03%   |
| Acer                                   | 18        | 2.87%   |
| Suyin                                  | 17        | 2.71%   |
| Lite-On Technology                     | 17        | 2.71%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 2.55%   |
| Luxvisions Innotech Limited            | 15        | 2.39%   |
| Logitech                               | 11        | 1.75%   |
| Alcor Micro                            | 8         | 1.27%   |
| Sonix Technology                       | 5         | 0.8%    |
| Lenovo                                 | 5         | 0.8%    |
| Apple                                  | 5         | 0.8%    |
| Silicon Motion                         | 4         | 0.64%   |
| Ricoh                                  | 3         | 0.48%   |
| Z-Star Microelectronics                | 2         | 0.32%   |
| Samsung Electronics                    | 2         | 0.32%   |
| Primax Electronics                     | 2         | 0.32%   |
| Importek                               | 2         | 0.32%   |
| Alpha Imaging Technology               | 2         | 0.32%   |
| ALi                                    | 2         | 0.32%   |
| Xiongmai                               | 1         | 0.16%   |
| Sunplus Technology                     | 1         | 0.16%   |
| OmniVision Technologies                | 1         | 0.16%   |
| Microsoft                              | 1         | 0.16%   |
| Hewlett-Packard                        | 1         | 0.16%   |
| Creative Technology                    | 1         | 0.16%   |
| Aveo Technology                        | 1         | 0.16%   |
| Arkmicro Technologies                  | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 37        | 5.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 24        | 3.82%   |
| IMC Networks Integrated Camera                      | 24        | 3.82%   |
| Microdia Integrated_Webcam_HD                       | 17        | 2.71%   |
| Chicony HD WebCam                                   | 16        | 2.55%   |
| Bison Integrated Camera                             | 16        | 2.55%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 2.07%   |
| Realtek Integrated_Webcam_HD                        | 13        | 2.07%   |
| Syntek Integrated Camera                            | 12        | 1.91%   |
| Quanta HP HD Camera                                 | 11        | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 1.59%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 1.43%   |
| Realtek Lenovo EasyCamera                           | 8         | 1.27%   |
| Bison SunplusIT Integrated Camera                   | 8         | 1.27%   |
| Bison HD Webcam                                     | 8         | 1.27%   |
| Quanta HD User Facing                               | 7         | 1.11%   |
| Chicony USB 2.0 Camera                              | 7         | 1.11%   |
| Microdia Integrated Webcam                          | 6         | 0.96%   |
| Quanta VGA WebCam                                   | 5         | 0.8%    |
| Quanta ACER HD User Facing                          | 5         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.8%    |
| Lite-On Integrated Camera                           | 5         | 0.8%    |
| Lite-On HP HD Webcam                                | 5         | 0.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 0.8%    |
| Chicony Lenovo EasyCamera                           | 5         | 0.8%    |
| Chicony HP HD Camera                                | 5         | 0.8%    |
| Chicony HD WebCam (Asus N-series)                   | 5         | 0.8%    |
| Bison Lenovo EasyCamera                             | 5         | 0.8%    |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 4         | 0.64%   |
| Sunplus Laptop Integrated Webcam HD                 | 4         | 0.64%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.64%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.64%   |
| Quanta HD Webcam                                    | 4         | 0.64%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.64%   |
| IMC Networks UVC VGA Webcam                         | 4         | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.64%   |
| Chicony HP Webcam [2 MP Macro]                      | 4         | 0.64%   |
| Chicony HP HD Webcam                                | 4         | 0.64%   |
| Alcor Micro Acer Integrated Webcam                  | 4         | 0.64%   |
| Acer Integrated Camera                              | 4         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 45        | 38.46%  |
| Synaptics                          | 34        | 29.06%  |
| AuthenTec                          | 15        | 12.82%  |
| Shenzhen Goodix Technology         | 7         | 5.98%   |
| Upek                               | 6         | 5.13%   |
| LighTuning Technology              | 4         | 3.42%   |
| Elan Microelectronics              | 4         | 3.42%   |
| STMicroelectronics                 | 1         | 0.85%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 12.82%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 10.26%  |
| AuthenTec AES2810                                                          | 8         | 6.84%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 5.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.27%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.42%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.42%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 3.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.71%   |
| Validity Sensors VFS491                                                    | 2         | 1.71%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.71%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.71%   |
| Synaptics WBDI                                                             | 2         | 1.71%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.71%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 1.71%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.71%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.71%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.71%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.85%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.85%   |
| Synaptics TouchPad                                                         | 1         | 0.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.85%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.85%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.85%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.85%   |
| AuthenTec AES1600                                                          | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 36.9%   |
| Alcor Micro           | 29        | 34.52%  |
| Upek                  | 8         | 9.52%   |
| O2 Micro              | 6         | 7.14%   |
| Lenovo                | 4         | 4.76%   |
| Advanced Card Systems | 3         | 3.57%   |
| SCM Microsystems      | 2         | 2.38%   |
| Clay Logic            | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 34.12%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 15.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 9.41%   |
| Broadcom 5880                                                                | 8         | 9.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 7.06%   |
| Broadcom 58200                                                               | 6         | 7.06%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.71%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.71%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.35%   |
| Advanced Card Systems ACR39U                                                 | 2         | 2.35%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.18%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.18%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.18%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 432       | 57.45%  |
| 1     | 250       | 33.24%  |
| 2     | 64        | 8.51%   |
| 3     | 5         | 0.66%   |
| 7     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 117       | 31.45%  |
| Graphics card            | 77        | 20.7%   |
| Chipcard                 | 70        | 18.82%  |
| Net/wireless             | 31        | 8.33%   |
| Multimedia controller    | 19        | 5.11%   |
| Bluetooth                | 19        | 5.11%   |
| Storage                  | 9         | 2.42%   |
| Camera                   | 9         | 2.42%   |
| Communication controller | 6         | 1.61%   |
| Card reader              | 4         | 1.08%   |
| Sound                    | 2         | 0.54%   |
| Network                  | 2         | 0.54%   |
| Net/ethernet             | 2         | 0.54%   |
| Modem                    | 2         | 0.54%   |
| Firewire controller      | 2         | 0.54%   |
| Flash memory             | 1         | 0.27%   |

