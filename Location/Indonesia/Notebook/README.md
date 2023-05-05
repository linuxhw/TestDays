Linux in Indonesia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

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

Total: 1155

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A514-54G             | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Dell          | Latitude 7300               | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| HP            | Notebook                    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Toshiba       | Satellite L640              | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| Dell          | Latitude 3410               | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| MSI           | Bravo 15 B5DD               | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| Valve         | Jupiter                     | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| Acer          | Swift SF314-71              | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Acer          | AO756                       | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Acer          | TravelMate P214             | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | V310-14ISK 80SX             | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Lenovo        | IdeaPad S110 20126          | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Acer          | Swift SF314-71              | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| MSI           | Modern 14 B4MW              | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Acer          | EX-215-52                   | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| Dell          | Latitude 3420               | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | E203NAH                     | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Dell          | Inspiron 3521               | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Intel         | SandyBridge Platform        | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| Acer          | Swift SF314-71              | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| Acer          | Nitro AN515-43              | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Acer          | Aspire 4732Z                | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Sony          | VPCEA36FG                   | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Dell          | G3 3579                     | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| Toshiba       | Satellite C640              | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Acer          | Aspire A314-35              | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| Acer          | Aspire 4720Z                | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Acer          | Swift SF314-41              | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Acer          | Aspire 4720Z                | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Sony          | VPCSB35FG                   | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| Dell          | Latitude E7240              | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Dell          | Vostro 5470                 | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Fujitsu       | FMVNA1SE                    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Toshiba       | Satellite C840              | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Toshiba       | Satellite C800D             | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Acer          | Aspire 4720Z                | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Fujitsu       | FMVNA7BEC                   | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | X200MA                      | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| ASUSTek       | X455LD                      | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| Acer          | Swift SF514-53T             | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| HP            | Notebook                    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | G40-45 80E1                 | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| Dell          | Latitude E6440              | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Dell          | Inspiron 1440               | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| ASUSTek       | K43SV                       | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| HP            | Pavilion 14                 | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HP            | Laptop 14-bw0xx             | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| HP            | EliteBook 2560p             | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Acer          | Swift SFX14-41G             | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| ASUSTek       | GL553VD                     | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| HP            | ProBook 4430s               | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| Acer          | Swift SF314-41              | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| Toshiba       | Satellite R630              | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| HP            | ENVY Notebook               | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| Lenovo        | G40-45 80E1                 | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| ASUSTek       | X455YA                      | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Dell          | Inspiron 3458               | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| Apple         | MacBookPro6,2               | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Nitro AN515-45              | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| ASUSTek       | K84L                        | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Acer          | Aspire E5-475G              | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| HP            | EliteBook Folio 9470m       | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| ASUSTek       | X550JX                      | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Acer          | Okinawa                     | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Acer          | Aspire 4752                 | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| Acer          | Aspire 4750                 | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| Acer          | Aspire A514-53              | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Acer          | Swift SF314-41              | [fde9376452](https://linux-hardware.org/?probe=fde9376452) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | [9f50b41201](https://linux-hardware.org/?probe=9f50b41201) | Apr 16, 2021 |
| ASUSTek       | X441UV                      | [8ee5e69c11](https://linux-hardware.org/?probe=8ee5e69c11) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| Acer          | Aspire 4752                 | [dbc22d503d](https://linux-hardware.org/?probe=dbc22d503d) | Apr 12, 2021 |
| Acer          | Aspire 4752                 | [c6ef5b093d](https://linux-hardware.org/?probe=c6ef5b093d) | Apr 12, 2021 |
| HP            | EliteBook 840 G1            | [b14a1a07ac](https://linux-hardware.org/?probe=b14a1a07ac) | Apr 11, 2021 |
| Dell          | Inspiron 5570               | [059aa32bb7](https://linux-hardware.org/?probe=059aa32bb7) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [4a05cec425](https://linux-hardware.org/?probe=4a05cec425) | Apr 10, 2021 |
| Acer          | Aspire 4741                 | [cf750140a8](https://linux-hardware.org/?probe=cf750140a8) | Apr 10, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [156c9db184](https://linux-hardware.org/?probe=156c9db184) | Apr 10, 2021 |
| Lenovo        | IdeaPad Z410 20292          | [803bcbb44c](https://linux-hardware.org/?probe=803bcbb44c) | Apr 05, 2021 |
| HP            | EliteBook Folio 9470m       | [22fc47b193](https://linux-hardware.org/?probe=22fc47b193) | Apr 05, 2021 |
| HP            | Laptop 15-bw0xx             | [44efde8890](https://linux-hardware.org/?probe=44efde8890) | Apr 05, 2021 |
| HP            | 1000                        | [be995ccb43](https://linux-hardware.org/?probe=be995ccb43) | Apr 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [941b588cf9](https://linux-hardware.org/?probe=941b588cf9) | Apr 03, 2021 |
| Acer          | Aspire 4739                 | [19ba24510c](https://linux-hardware.org/?probe=19ba24510c) | Apr 02, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [c41ba66f79](https://linux-hardware.org/?probe=c41ba66f79) | Apr 01, 2021 |
| Lenovo        | V310-14ISK 80SX             | [463bdc0444](https://linux-hardware.org/?probe=463bdc0444) | Apr 01, 2021 |
| ASUSTek       | X550VX                      | [4d95cd31eb](https://linux-hardware.org/?probe=4d95cd31eb) | Mar 27, 2021 |
| Dell          | Latitude 5400               | [5cab0ca67e](https://linux-hardware.org/?probe=5cab0ca67e) | Mar 26, 2021 |
| ASUSTek       | K45VD                       | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Lenovo        | V310-14ISK 80SX             | [1ce5b4161e](https://linux-hardware.org/?probe=1ce5b4161e) | Mar 24, 2021 |
| ASUSTek       | X45U                        | [05632e634d](https://linux-hardware.org/?probe=05632e634d) | Mar 23, 2021 |
| Dell          | Vostro 3481                 | [63b8942776](https://linux-hardware.org/?probe=63b8942776) | Mar 12, 2021 |
| ASUSTek       | X441SA                      | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [cb688e237f](https://linux-hardware.org/?probe=cb688e237f) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [68d0129e2d](https://linux-hardware.org/?probe=68d0129e2d) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK AH544              | [80ce017529](https://linux-hardware.org/?probe=80ce017529) | Mar 04, 2021 |
| ASUSTek       | X442URR                     | [d8e04d832e](https://linux-hardware.org/?probe=d8e04d832e) | Mar 03, 2021 |
| ASUSTek       | UX303UB                     | [c4867a5743](https://linux-hardware.org/?probe=c4867a5743) | Mar 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a5f08bd719](https://linux-hardware.org/?probe=a5f08bd719) | Mar 01, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [d3f1f06d5d](https://linux-hardware.org/?probe=d3f1f06d5d) | Feb 22, 2021 |
| HP            | Notebook                    | [e718153751](https://linux-hardware.org/?probe=e718153751) | Feb 22, 2021 |
| ASUSTek       | K42F                        | [2380c82b48](https://linux-hardware.org/?probe=2380c82b48) | Feb 20, 2021 |
| HP            | Notebook                    | [326de2e4f5](https://linux-hardware.org/?probe=326de2e4f5) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f9abaeb3f9](https://linux-hardware.org/?probe=f9abaeb3f9) | Feb 18, 2021 |
| HP            | Laptop 14-bw0xx             | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Acer          | Aspire E5-471G              | [3b58cbf4e6](https://linux-hardware.org/?probe=3b58cbf4e6) | Feb 17, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [5a09ac2a06](https://linux-hardware.org/?probe=5a09ac2a06) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [9805e3bcb5](https://linux-hardware.org/?probe=9805e3bcb5) | Feb 16, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a0537ad7d5](https://linux-hardware.org/?probe=a0537ad7d5) | Feb 16, 2021 |
| Toshiba       | Satellite C855              | [60adcbc05d](https://linux-hardware.org/?probe=60adcbc05d) | Feb 16, 2021 |
| Timi          | TM1703                      | [4d64e40cca](https://linux-hardware.org/?probe=4d64e40cca) | Feb 14, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| ASUSTek       | X456UQK                     | [f0380f099d](https://linux-hardware.org/?probe=f0380f099d) | Feb 12, 2021 |
| ASUSTek       | K43E                        | [1604193c0f](https://linux-hardware.org/?probe=1604193c0f) | Feb 11, 2021 |
| Lenovo        | G50-80 80E5                 | [704dbacb0d](https://linux-hardware.org/?probe=704dbacb0d) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| Lenovo        | ThinkPad X131e 33741E0      | [4c52c9aa29](https://linux-hardware.org/?probe=4c52c9aa29) | Feb 06, 2021 |
| Acer          | NXHATSN00190808A906600      | [2ed3d18f0a](https://linux-hardware.org/?probe=2ed3d18f0a) | Feb 05, 2021 |
| ASUSTek       | N56VM                       | [d56280ec33](https://linux-hardware.org/?probe=d56280ec33) | Feb 05, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [f48cf2f332](https://linux-hardware.org/?probe=f48cf2f332) | Feb 05, 2021 |
| Compal        | PBL10                       | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [f79d79fd99](https://linux-hardware.org/?probe=f79d79fd99) | Feb 04, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| HP            | EliteBook Folio 9470m       | [15b84d2abc](https://linux-hardware.org/?probe=15b84d2abc) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | [9b722252fa](https://linux-hardware.org/?probe=9b722252fa) | Feb 04, 2021 |
| HP            | Laptop 14-cm0xxx            | [2365556c9d](https://linux-hardware.org/?probe=2365556c9d) | Jan 31, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | ZBook 15 G2                 | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Lenovo        | ThinkPad X280 20KES7YB00    | [b498c0fcba](https://linux-hardware.org/?probe=b498c0fcba) | Jan 29, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Acer          | Aspire 4752                 | [2e5b64f391](https://linux-hardware.org/?probe=2e5b64f391) | Jan 27, 2021 |
| Acer          | Aspire 4752                 | [f068345e45](https://linux-hardware.org/?probe=f068345e45) | Jan 27, 2021 |
| Acer          | AOD255E                     | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| ASUSTek       | N56VM                       | [e6d527734c](https://linux-hardware.org/?probe=e6d527734c) | Jan 27, 2021 |
| Acer          | One Z1402                   | [1b8a4dfe38](https://linux-hardware.org/?probe=1b8a4dfe38) | Jan 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d18f1e2124](https://linux-hardware.org/?probe=d18f1e2124) | Jan 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [16b5d3f4ca](https://linux-hardware.org/?probe=16b5d3f4ca) | Jan 23, 2021 |
| Acer          | Swift SF514-52T             | [be049e723f](https://linux-hardware.org/?probe=be049e723f) | Jan 21, 2021 |
| ASUSTek       | N56VM                       | [81c592d723](https://linux-hardware.org/?probe=81c592d723) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dc16c8d7a4](https://linux-hardware.org/?probe=dc16c8d7a4) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f9b1a75983](https://linux-hardware.org/?probe=f9b1a75983) | Jan 19, 2021 |
| Lenovo        | ThinkPad T480 20L5A02JID    | [0599ce4883](https://linux-hardware.org/?probe=0599ce4883) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [be559d7b11](https://linux-hardware.org/?probe=be559d7b11) | Jan 17, 2021 |
| Lenovo        | IdeaPad Z370                | [728438c7eb](https://linux-hardware.org/?probe=728438c7eb) | Jan 16, 2021 |
| Lenovo        | IdeaPad Z370                | [6e3c415308](https://linux-hardware.org/?probe=6e3c415308) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Dell          | Vostro 5470                 | [8e785a29dd](https://linux-hardware.org/?probe=8e785a29dd) | Jan 15, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [bb99db17ed](https://linux-hardware.org/?probe=bb99db17ed) | Jan 15, 2021 |
| HP            | G42                         | [63dd848e66](https://linux-hardware.org/?probe=63dd848e66) | Jan 14, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| HP            | ZBook 15 G2                 | [da387b9871](https://linux-hardware.org/?probe=da387b9871) | Jan 09, 2021 |
| ASUSTek       | G750JM                      | [794d86e07e](https://linux-hardware.org/?probe=794d86e07e) | Jan 07, 2021 |
| ASUSTek       | G750JM                      | [a32f193a0d](https://linux-hardware.org/?probe=a32f193a0d) | Jan 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [8a573087bd](https://linux-hardware.org/?probe=8a573087bd) | Jan 07, 2021 |
| MSI           | Modern 15 A10RBS            | [d4ded10aed](https://linux-hardware.org/?probe=d4ded10aed) | Jan 06, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| ASUSTek       | K43SD                       | [79f04bb2b4](https://linux-hardware.org/?probe=79f04bb2b4) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | [6ebc8c1b1c](https://linux-hardware.org/?probe=6ebc8c1b1c) | Jan 03, 2021 |
| ASUSTek       | X455LAB                     | [1c55bbde2e](https://linux-hardware.org/?probe=1c55bbde2e) | Jan 01, 2021 |
| HP            | 1000                        | [981fa79f13](https://linux-hardware.org/?probe=981fa79f13) | Jan 01, 2021 |
| ASUSTek       | X455LAB                     | [8cbb6c5afe](https://linux-hardware.org/?probe=8cbb6c5afe) | Dec 31, 2020 |
| Sole          | Unknown                     | [04bc36aa05](https://linux-hardware.org/?probe=04bc36aa05) | Dec 30, 2020 |
| HP            | ZBook 15 G2                 | [87757ee4f2](https://linux-hardware.org/?probe=87757ee4f2) | Dec 30, 2020 |
| Dell          | Vostro A840                 | [76e7e81662](https://linux-hardware.org/?probe=76e7e81662) | Dec 28, 2020 |
| Lenovo        | ThinkPad T530 24294V4       | [50625b08c9](https://linux-hardware.org/?probe=50625b08c9) | Dec 26, 2020 |
| HP            | EliteBook Folio 9470m       | [5bd5d77342](https://linux-hardware.org/?probe=5bd5d77342) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [a53bf69f31](https://linux-hardware.org/?probe=a53bf69f31) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | [7f1872861c](https://linux-hardware.org/?probe=7f1872861c) | Dec 24, 2020 |
| Acer          | Aspire 4738Z                | [26c4af7060](https://linux-hardware.org/?probe=26c4af7060) | Dec 22, 2020 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [be0654391c](https://linux-hardware.org/?probe=be0654391c) | Dec 21, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | C-Notebook XXXX 3000 G40... | [23766674a9](https://linux-hardware.org/?probe=23766674a9) | Dec 18, 2020 |
| ASUSTek       | K55DR                       | [86bca93d29](https://linux-hardware.org/?probe=86bca93d29) | Dec 16, 2020 |
| ASUSTek       | K55DR                       | [300d21973e](https://linux-hardware.org/?probe=300d21973e) | Dec 16, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| ASUSTek       | 1015BX                      | [5cb5d5f2a8](https://linux-hardware.org/?probe=5cb5d5f2a8) | Dec 15, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [406d93673b](https://linux-hardware.org/?probe=406d93673b) | Dec 13, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [785196a6d7](https://linux-hardware.org/?probe=785196a6d7) | Dec 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [8a32a0ec2e](https://linux-hardware.org/?probe=8a32a0ec2e) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | [318416a95a](https://linux-hardware.org/?probe=318416a95a) | Dec 08, 2020 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [d4c5036cd3](https://linux-hardware.org/?probe=d4c5036cd3) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [5f56870146](https://linux-hardware.org/?probe=5f56870146) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2a305a9be7](https://linux-hardware.org/?probe=2a305a9be7) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [cf81aea5fe](https://linux-hardware.org/?probe=cf81aea5fe) | Dec 02, 2020 |
| ASUSTek       | X456URK                     | [be6b2ec83a](https://linux-hardware.org/?probe=be6b2ec83a) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [b664b71a15](https://linux-hardware.org/?probe=b664b71a15) | Nov 28, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| Acer          | NXHATSN00190808A906600      | [402e6fe81a](https://linux-hardware.org/?probe=402e6fe81a) | Nov 26, 2020 |
| Toshiba       | Satellite L40               | [ffafc05e1f](https://linux-hardware.org/?probe=ffafc05e1f) | Nov 25, 2020 |
| HP            | 14                          | [1a02430025](https://linux-hardware.org/?probe=1a02430025) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [b17dd2d085](https://linux-hardware.org/?probe=b17dd2d085) | Nov 21, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| HP            | 14                          | [548056d4e9](https://linux-hardware.org/?probe=548056d4e9) | Nov 18, 2020 |
| HP            | 14                          | [a08766aff4](https://linux-hardware.org/?probe=a08766aff4) | Nov 18, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d65def3ce](https://linux-hardware.org/?probe=3d65def3ce) | Nov 16, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [82dbd47dff](https://linux-hardware.org/?probe=82dbd47dff) | Nov 15, 2020 |
| Dell          | XPS 13 7390                 | [8844beb362](https://linux-hardware.org/?probe=8844beb362) | Nov 14, 2020 |
| Lenovo        | ThinkPad T410s 2904CGU      | [271f9ac078](https://linux-hardware.org/?probe=271f9ac078) | Nov 14, 2020 |
| Acer          | Aspire V5-132               | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| Acer          | Aspire E5-421               | [625727a34f](https://linux-hardware.org/?probe=625727a34f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [0b2411ab89](https://linux-hardware.org/?probe=0b2411ab89) | Nov 12, 2020 |
| Lenovo        | G400 20235                  | [e8b5212a0b](https://linux-hardware.org/?probe=e8b5212a0b) | Nov 11, 2020 |
| Acer          | Aspire E5-475G              | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2342A19       | [579f942204](https://linux-hardware.org/?probe=579f942204) | Nov 09, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [923558f59a](https://linux-hardware.org/?probe=923558f59a) | Nov 08, 2020 |
| ASUSTek       | X453SA                      | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| ASUSTek       | X442UQR                     | [98225dbf74](https://linux-hardware.org/?probe=98225dbf74) | Nov 03, 2020 |
| Unknown       | Unknown                     | [4c80913adb](https://linux-hardware.org/?probe=4c80913adb) | Nov 02, 2020 |
| Lenovo        | G40-30 80FY                 | [7bc709a3cd](https://linux-hardware.org/?probe=7bc709a3cd) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [64b38989db](https://linux-hardware.org/?probe=64b38989db) | Oct 30, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | [516ff504f0](https://linux-hardware.org/?probe=516ff504f0) | Oct 29, 2020 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | [45b0065d49](https://linux-hardware.org/?probe=45b0065d49) | Oct 28, 2020 |
| HP            | Notebook                    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Clevo         | M7x0S                       | [8559d7b074](https://linux-hardware.org/?probe=8559d7b074) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Lenovo        | V330-14IKB 81B0             | [0a1f42ff5e](https://linux-hardware.org/?probe=0a1f42ff5e) | Oct 18, 2020 |
| Lenovo        | V330-14IKB 81B0             | [327a983226](https://linux-hardware.org/?probe=327a983226) | Oct 18, 2020 |
| Acer          | Nitro AN515-52              | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [646054c190](https://linux-hardware.org/?probe=646054c190) | Oct 08, 2020 |
| ASUSTek       | X442URR                     | [5e9f9ee314](https://linux-hardware.org/?probe=5e9f9ee314) | Oct 06, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Lenovo        | IdeaPad Z480                | [36a5cbc73c](https://linux-hardware.org/?probe=36a5cbc73c) | Oct 03, 2020 |
| Lenovo        | IdeaPad Z480                | [f7282459cf](https://linux-hardware.org/?probe=f7282459cf) | Oct 03, 2020 |
| Acer          | NXHATSN00190808A906600      | [ece82b096b](https://linux-hardware.org/?probe=ece82b096b) | Oct 01, 2020 |
| HP            | Pavilion x2 Detachable      | [d4078124eb](https://linux-hardware.org/?probe=d4078124eb) | Sep 30, 2020 |
| ASUSTek       | X450EA                      | [2646942e92](https://linux-hardware.org/?probe=2646942e92) | Sep 30, 2020 |
| HP            | 430                         | [9eef183864](https://linux-hardware.org/?probe=9eef183864) | Sep 27, 2020 |
| Toshiba       | Satellite L730              | [28ff46aa6b](https://linux-hardware.org/?probe=28ff46aa6b) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [24b078a7f0](https://linux-hardware.org/?probe=24b078a7f0) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| ASUSTek       | X455YA                      | [0959901fca](https://linux-hardware.org/?probe=0959901fca) | Sep 23, 2020 |
| HP            | ENVY Laptop 13-aq1xxx       | [ed83ee1e30](https://linux-hardware.org/?probe=ed83ee1e30) | Sep 22, 2020 |
| Acer          | Aspire ES1-111M             | [4a9dbc9937](https://linux-hardware.org/?probe=4a9dbc9937) | Sep 19, 2020 |
| Acer          | Aspire ES1-111M             | [0e2694227b](https://linux-hardware.org/?probe=0e2694227b) | Sep 19, 2020 |
| Apple         | MacBookPro12,1              | [d766064036](https://linux-hardware.org/?probe=d766064036) | Sep 17, 2020 |
| HP            | 430                         | [bfb152e615](https://linux-hardware.org/?probe=bfb152e615) | Sep 10, 2020 |
| ASUSTek       | GL503VD                     | [820f4da953](https://linux-hardware.org/?probe=820f4da953) | Sep 09, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d545f007f9](https://linux-hardware.org/?probe=d545f007f9) | Sep 05, 2020 |
| Acer          | Nitro AN515-43              | [7e0202ac18](https://linux-hardware.org/?probe=7e0202ac18) | Sep 04, 2020 |
| Acer          | Nitro AN515-43              | [152a400df9](https://linux-hardware.org/?probe=152a400df9) | Sep 04, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [712ec86d11](https://linux-hardware.org/?probe=712ec86d11) | Sep 04, 2020 |
| HP            | Pavilion Gaming Notebook    | [5bcdd6aa5a](https://linux-hardware.org/?probe=5bcdd6aa5a) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| Lenovo        | G405 20239                  | [518d27feca](https://linux-hardware.org/?probe=518d27feca) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2325WLB       | [e558c503f8](https://linux-hardware.org/?probe=e558c503f8) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2324AS7       | [676f1b8dce](https://linux-hardware.org/?probe=676f1b8dce) | Sep 03, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [24bdd07050](https://linux-hardware.org/?probe=24bdd07050) | Sep 02, 2020 |
| HP            | Pavilion dm1                | [1723b44134](https://linux-hardware.org/?probe=1723b44134) | Sep 02, 2020 |
| HP            | Pavilion Gaming Notebook    | [0c63fa76a6](https://linux-hardware.org/?probe=0c63fa76a6) | Sep 01, 2020 |
| HP            | EliteBook 2570p             | [a70aa343a9](https://linux-hardware.org/?probe=a70aa343a9) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [cf281b97df](https://linux-hardware.org/?probe=cf281b97df) | Aug 31, 2020 |
| HP            | Pavilion g4                 | [4ae31fc59f](https://linux-hardware.org/?probe=4ae31fc59f) | Aug 30, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | [687538cadf](https://linux-hardware.org/?probe=687538cadf) | Aug 24, 2020 |
| Lenovo        | G400 20235                  | [f209fc4fd1](https://linux-hardware.org/?probe=f209fc4fd1) | Aug 22, 2020 |
| ASUSTek       | X550IK                      | [70aa141880](https://linux-hardware.org/?probe=70aa141880) | Aug 21, 2020 |
| Dell          | Inspiron 3180               | [cd7328883c](https://linux-hardware.org/?probe=cd7328883c) | Aug 18, 2020 |
| Fujitsu       | LIFEBOOK E734               | [977a611718](https://linux-hardware.org/?probe=977a611718) | Aug 16, 2020 |
| Dell          | Latitude E6400              | [177b63fda5](https://linux-hardware.org/?probe=177b63fda5) | Aug 15, 2020 |
| HP            | ProBook 440 G7              | [5291acaadc](https://linux-hardware.org/?probe=5291acaadc) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| Dell          | Latitude E6230              | [da6d9fdf1d](https://linux-hardware.org/?probe=da6d9fdf1d) | Aug 14, 2020 |
| HP            | Notebook                    | [8e7a53706c](https://linux-hardware.org/?probe=8e7a53706c) | Aug 13, 2020 |
| HP            | ProBook 440 G4              | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| Fujitsu       | LIFEBOOK E734               | [74050bb5dd](https://linux-hardware.org/?probe=74050bb5dd) | Aug 10, 2020 |
| HP            | Pavilion g4                 | [0ea8276f60](https://linux-hardware.org/?probe=0ea8276f60) | Aug 07, 2020 |
| HP            | Pavilion g4                 | [227e2e8de7](https://linux-hardware.org/?probe=227e2e8de7) | Aug 07, 2020 |
| HP            | ProBook 440 G2              | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [8a63857dec](https://linux-hardware.org/?probe=8a63857dec) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [99bb1cd9d9](https://linux-hardware.org/?probe=99bb1cd9d9) | Aug 06, 2020 |
| Dell          | Latitude E6400              | [a1d10698bc](https://linux-hardware.org/?probe=a1d10698bc) | Aug 05, 2020 |
| Toshiba       | Satellite L745              | [4770498bee](https://linux-hardware.org/?probe=4770498bee) | Aug 02, 2020 |
| Toshiba       | Satellite L745              | [8f86800c3c](https://linux-hardware.org/?probe=8f86800c3c) | Aug 02, 2020 |
| ASUSTek       | N46VM                       | [d5866f9f0f](https://linux-hardware.org/?probe=d5866f9f0f) | Jul 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [81ca2030be](https://linux-hardware.org/?probe=81ca2030be) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| ASUSTek       | K43E                        | [47067cf62f](https://linux-hardware.org/?probe=47067cf62f) | Jul 29, 2020 |
| ASUSTek       | K43E                        | [5cc61ff85e](https://linux-hardware.org/?probe=5cc61ff85e) | Jul 29, 2020 |
| ASUSTek       | N46VM                       | [b9abcbb0ca](https://linux-hardware.org/?probe=b9abcbb0ca) | Jul 27, 2020 |
| ASUSTek       | N46VM                       | [864b3c0808](https://linux-hardware.org/?probe=864b3c0808) | Jul 27, 2020 |
| ASUSTek       | N43SN                       | [8652a9c307](https://linux-hardware.org/?probe=8652a9c307) | Jul 24, 2020 |
| ASUSTek       | N43SN                       | [6417be2a1c](https://linux-hardware.org/?probe=6417be2a1c) | Jul 24, 2020 |
| Dell          | Latitude E6420              | [2c5b59d1df](https://linux-hardware.org/?probe=2c5b59d1df) | Jul 22, 2020 |
| ASUSTek       | X451CAP                     | [b4a3b63689](https://linux-hardware.org/?probe=b4a3b63689) | Jul 21, 2020 |
| ASUSTek       | X451CAP                     | [948bec3418](https://linux-hardware.org/?probe=948bec3418) | Jul 21, 2020 |
| HP            | Laptop 14-bs0xx             | [be0c3117b4](https://linux-hardware.org/?probe=be0c3117b4) | Jul 20, 2020 |
| ASUSTek       | X451CAP                     | [9043a7e401](https://linux-hardware.org/?probe=9043a7e401) | Jul 20, 2020 |
| Lenovo        | ThinkPad W550s 20E2000CM... | [2db5fa6bb3](https://linux-hardware.org/?probe=2db5fa6bb3) | Jul 19, 2020 |
| HP            | Pavilion g4                 | [cfa0470ff1](https://linux-hardware.org/?probe=cfa0470ff1) | Jul 18, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [50272ea6ea](https://linux-hardware.org/?probe=50272ea6ea) | Jul 16, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2b9f97d49e](https://linux-hardware.org/?probe=2b9f97d49e) | Jul 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [acf40c367c](https://linux-hardware.org/?probe=acf40c367c) | Jul 14, 2020 |
| HP            | 14                          | [c49bc9fa04](https://linux-hardware.org/?probe=c49bc9fa04) | Jul 13, 2020 |
| HP            | 14                          | [16f518d4d1](https://linux-hardware.org/?probe=16f518d4d1) | Jul 12, 2020 |
| ASUSTek       | X550ZE                      | [95e148ab0b](https://linux-hardware.org/?probe=95e148ab0b) | Jul 11, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ce870d391e](https://linux-hardware.org/?probe=ce870d391e) | Jul 09, 2020 |
| Acer          | Aspire E1-451G              | [4765a08df1](https://linux-hardware.org/?probe=4765a08df1) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Lenovo        | IdeaPad S210 20256          | [31723f3abc](https://linux-hardware.org/?probe=31723f3abc) | Jul 04, 2020 |
| ASUSTek       | X555BP                      | [e34500bb1c](https://linux-hardware.org/?probe=e34500bb1c) | Jul 03, 2020 |
| Acer          | Aspire F5-571T              | [61e70ca838](https://linux-hardware.org/?probe=61e70ca838) | Jun 29, 2020 |
| Acer          | Aspire F5-571T              | [bfc16ddd86](https://linux-hardware.org/?probe=bfc16ddd86) | Jun 28, 2020 |
| Lenovo        | ThinkPad X131e 33684SU      | [1ed3f7e63d](https://linux-hardware.org/?probe=1ed3f7e63d) | Jun 28, 2020 |
| ASUSTek       | UX331UN                     | [3bf2e1fb3c](https://linux-hardware.org/?probe=3bf2e1fb3c) | Jun 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [20fe5eb234](https://linux-hardware.org/?probe=20fe5eb234) | Jun 27, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [34c449d22e](https://linux-hardware.org/?probe=34c449d22e) | Jun 26, 2020 |
| HP            | 14                          | [4de0326f3b](https://linux-hardware.org/?probe=4de0326f3b) | Jun 24, 2020 |
| Acer          | Swift SF314-54G             | [e69e144ab8](https://linux-hardware.org/?probe=e69e144ab8) | Jun 21, 2020 |
| Lenovo        | G400 20235                  | [b3d56039ce](https://linux-hardware.org/?probe=b3d56039ce) | Jun 20, 2020 |
| Dell          | Latitude E6420              | [f186fc19d1](https://linux-hardware.org/?probe=f186fc19d1) | Jun 20, 2020 |
| Dell          | Latitude E6420              | [f4a05ff8fe](https://linux-hardware.org/?probe=f4a05ff8fe) | Jun 19, 2020 |
| Lenovo        | ThinkPad Twist 33473BA      | [6af138a9a7](https://linux-hardware.org/?probe=6af138a9a7) | Jun 18, 2020 |
| Dell          | System Inspiron N4110       | [4d8d8ad86f](https://linux-hardware.org/?probe=4d8d8ad86f) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| Dell          | Latitude E6420              | [d7a5e67910](https://linux-hardware.org/?probe=d7a5e67910) | Jun 16, 2020 |
| Acer          | Aspire 4752                 | [c1bf847a06](https://linux-hardware.org/?probe=c1bf847a06) | Jun 15, 2020 |
| Dell          | Latitude E6420              | [b4e34247b1](https://linux-hardware.org/?probe=b4e34247b1) | Jun 14, 2020 |
| Dell          | Latitude E6420              | [9f81490571](https://linux-hardware.org/?probe=9f81490571) | Jun 12, 2020 |
| ASUSTek       | K46CM                       | [f50bd98e01](https://linux-hardware.org/?probe=f50bd98e01) | Jun 06, 2020 |
| Toshiba       | NB510                       | [034e807bf8](https://linux-hardware.org/?probe=034e807bf8) | Jun 05, 2020 |
| HP            | Pavilion g4                 | [a6a626b9ca](https://linux-hardware.org/?probe=a6a626b9ca) | Jun 04, 2020 |
| Acer          | Aspire 5050                 | [0c4de1a1a1](https://linux-hardware.org/?probe=0c4de1a1a1) | Jun 01, 2020 |
| Acer          | Aspire 5050                 | [ec8759bd69](https://linux-hardware.org/?probe=ec8759bd69) | Jun 01, 2020 |
| Acer          | Aspire A315-41              | [e91778b012](https://linux-hardware.org/?probe=e91778b012) | May 31, 2020 |
| ASUSTek       | K46CM                       | [b2b5f9db8d](https://linux-hardware.org/?probe=b2b5f9db8d) | May 31, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [dcc2d3e59f](https://linux-hardware.org/?probe=dcc2d3e59f) | May 31, 2020 |
| Lenovo        | G40-45 80E1                 | [4002bc5fb1](https://linux-hardware.org/?probe=4002bc5fb1) | May 30, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [b45d1eb089](https://linux-hardware.org/?probe=b45d1eb089) | May 28, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [00f65112c3](https://linux-hardware.org/?probe=00f65112c3) | May 28, 2020 |
| ASUSTek       | X200CA                      | [838a34d93c](https://linux-hardware.org/?probe=838a34d93c) | May 22, 2020 |
| MSI           | MS-1481                     | [e32bed7fb1](https://linux-hardware.org/?probe=e32bed7fb1) | May 15, 2020 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [412ba3814d](https://linux-hardware.org/?probe=412ba3814d) | May 15, 2020 |
| Lenovo        | IdeaPad S340-15IWLTouch ... | [ba05f4ff6a](https://linux-hardware.org/?probe=ba05f4ff6a) | May 15, 2020 |
| HP            | Pavilion 14                 | [f366f5c4e4](https://linux-hardware.org/?probe=f366f5c4e4) | May 11, 2020 |
| Lenovo        | G400s 20244                 | [c53de49fbc](https://linux-hardware.org/?probe=c53de49fbc) | May 10, 2020 |
| Lenovo        | ThinkPad T430 2349FC3       | [00f6deaf61](https://linux-hardware.org/?probe=00f6deaf61) | May 09, 2020 |
| Lenovo        | ThinkPad Twist 33473BA      | [3dee72a67f](https://linux-hardware.org/?probe=3dee72a67f) | May 08, 2020 |
| Apple         | MacBookPro12,1              | [b0c6f48549](https://linux-hardware.org/?probe=b0c6f48549) | May 08, 2020 |
| ASUSTek       | N46VM                       | [dac0d32083](https://linux-hardware.org/?probe=dac0d32083) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| Dell          | Vostro 14-3468              | [d1670dbbdd](https://linux-hardware.org/?probe=d1670dbbdd) | May 04, 2020 |
| Dell          | Vostro 14-3468              | [dbb1d688e9](https://linux-hardware.org/?probe=dbb1d688e9) | Apr 28, 2020 |
| Dell          | Vostro 14-3468              | [66350e55ef](https://linux-hardware.org/?probe=66350e55ef) | Apr 28, 2020 |
| Toshiba       | Satellite L510              | [a27037c0e1](https://linux-hardware.org/?probe=a27037c0e1) | Apr 26, 2020 |
| Lenovo        | ThinkPad T410 2522CTO       | [0342587f2b](https://linux-hardware.org/?probe=0342587f2b) | Apr 26, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [09b7ff4a7f](https://linux-hardware.org/?probe=09b7ff4a7f) | Apr 25, 2020 |
| HP            | EliteBook 840 G1            | [8d9870131a](https://linux-hardware.org/?probe=8d9870131a) | Apr 24, 2020 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [2aa0175c4b](https://linux-hardware.org/?probe=2aa0175c4b) | Apr 22, 2020 |
| ASUSTek       | X450CC                      | [8395776e77](https://linux-hardware.org/?probe=8395776e77) | Apr 21, 2020 |
| Acer          | Swift SF314-56G             | [f2608b9796](https://linux-hardware.org/?probe=f2608b9796) | Apr 18, 2020 |
| AXIOO         | NEON CNW                    | [64edfa7923](https://linux-hardware.org/?probe=64edfa7923) | Apr 18, 2020 |
| ASUSTek       | X442UR                      | [b96b676ec0](https://linux-hardware.org/?probe=b96b676ec0) | Apr 16, 2020 |
| Apple         | MacBook4,1                  | [17f5daf01e](https://linux-hardware.org/?probe=17f5daf01e) | Apr 16, 2020 |
| HP            | EliteBook 2560p             | [61ff7566f0](https://linux-hardware.org/?probe=61ff7566f0) | Apr 13, 2020 |
| HP            | EliteBook 2560p             | [e830e91c74](https://linux-hardware.org/?probe=e830e91c74) | Apr 13, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [15057e288d](https://linux-hardware.org/?probe=15057e288d) | Apr 11, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [90ca183e3d](https://linux-hardware.org/?probe=90ca183e3d) | Apr 10, 2020 |
| HP            | 540                         | [6fa99c27dd](https://linux-hardware.org/?probe=6fa99c27dd) | Apr 10, 2020 |
| AXIOO         | NEON CNW                    | [b31fc0c0dd](https://linux-hardware.org/?probe=b31fc0c0dd) | Apr 10, 2020 |
| Toshiba       | Satellite L510              | [659bf517f1](https://linux-hardware.org/?probe=659bf517f1) | Apr 08, 2020 |
| HP            | EliteBook 2560p             | [9e472a05c5](https://linux-hardware.org/?probe=9e472a05c5) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | [488c8306ff](https://linux-hardware.org/?probe=488c8306ff) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [6928abb72d](https://linux-hardware.org/?probe=6928abb72d) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [020c71d11e](https://linux-hardware.org/?probe=020c71d11e) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | [163b885549](https://linux-hardware.org/?probe=163b885549) | Apr 07, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 105       | 12.32%  |
| Ubuntu 18.04       | 59        | 6.92%   |
| Ubuntu 22.04       | 41        | 4.81%   |
| OpenMandriva 4.3   | 35        | 4.11%   |
| OpenMandriva 4.2   | 23        | 2.7%    |
| Arch Rolling       | 22        | 2.58%   |
| KDE neon 20.04     | 19        | 2.23%   |
| Fedora 36          | 18        | 2.11%   |
| Arch               | 17        | 2%      |
| Pop!_OS 20.04      | 14        | 1.64%   |
| Manjaro            | 14        | 1.64%   |
| Zorin 15           | 13        | 1.53%   |
| Ubuntu 19.10       | 12        | 1.41%   |
| Pop!_OS 22.04      | 12        | 1.41%   |
| Fedora 35          | 12        | 1.41%   |
| Elementary 6.1     | 12        | 1.41%   |
| Debian 11          | 12        | 1.41%   |
| Ubuntu 21.10       | 11        | 1.29%   |
| Linux Mint 20.3    | 11        | 1.29%   |
| Fedora 37          | 11        | 1.29%   |
| ArcoLinux Rolling  | 11        | 1.29%   |
| Zorin 16           | 9         | 1.06%   |
| Xubuntu 20.04      | 9         | 1.06%   |
| Kubuntu 20.04      | 9         | 1.06%   |
| OpenMandriva 23.03 | 8         | 0.94%   |
| OpenMandriva 23.01 | 8         | 0.94%   |
| Linux Mint 19.3    | 8         | 0.94%   |
| Kubuntu 22.04      | 8         | 0.94%   |
| Debian 10          | 8         | 0.94%   |
| Pop!_OS 21.04      | 7         | 0.82%   |
| Ubuntu MATE 20.04  | 6         | 0.7%    |
| Ubuntu 21.04       | 6         | 0.7%    |
| Ubuntu 19.04       | 6         | 0.7%    |
| Linux Mint 21      | 6         | 0.7%    |
| Linux Mint 20.2    | 6         | 0.7%    |
| Linux Mint 20      | 6         | 0.7%    |
| Fedora 34          | 6         | 0.7%    |
| Fedora 32          | 6         | 0.7%    |
| Xubuntu 18.04      | 5         | 0.59%   |
| Ubuntu 16.04       | 5         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 238       | 29.46%  |
| OpenMandriva  | 73        | 9.03%   |
| Fedora        | 55        | 6.81%   |
| Linux Mint    | 44        | 5.45%   |
| Arch          | 39        | 4.83%   |
| Pop!_OS       | 38        | 4.7%    |
| Manjaro       | 37        | 4.58%   |
| Zorin         | 25        | 3.09%   |
| Elementary    | 25        | 3.09%   |
| Debian        | 24        | 2.97%   |
| Kubuntu       | 23        | 2.85%   |
| KDE neon      | 23        | 2.85%   |
| Endless       | 20        | 2.48%   |
| Xubuntu       | 19        | 2.35%   |
| Kali          | 18        | 2.23%   |
| ArcoLinux     | 12        | 1.49%   |
| Lubuntu       | 11        | 1.36%   |
| ROSA          | 10        | 1.24%   |
| Ubuntu MATE   | 7         | 0.87%   |
| Ubuntu Unity  | 5         | 0.62%   |
| openSUSE      | 5         | 0.62%   |
| LMDE          | 5         | 0.62%   |
| EndeavourOS   | 5         | 0.62%   |
| Parrot        | 4         | 0.5%    |
| Deepin        | 4         | 0.5%    |
| Artix         | 4         | 0.5%    |
| Ubuntu Budgie | 3         | 0.37%   |
| Clear Linux   | 3         | 0.37%   |
| SteamOS       | 2         | 0.25%   |
| Solus         | 2         | 0.25%   |
| Nobara        | 2         | 0.25%   |
| MX            | 2         | 0.25%   |
| Gentoo        | 2         | 0.25%   |
| Chrome OS     | 2         | 0.25%   |
| CentOS        | 2         | 0.25%   |
| BlackPanther  | 2         | 0.25%   |
| Xero          | 1         | 0.12%   |
| Void Linux    | 1         | 0.12%   |
| UbuntuDDE     | 1         | 0.12%   |
| Ubuntu Studio | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 35        | 3.86%   |
| 5.10.14-desktop-1omv4002 | 23        | 2.54%   |
| 5.4.0-42-generic         | 16        | 1.76%   |
| 5.15.0-56-generic        | 13        | 1.43%   |
| 5.4.0-26-generic         | 11        | 1.21%   |
| 5.15.0-41-generic        | 10        | 1.1%    |
| 5.4.0-52-generic         | 9         | 0.99%   |
| 5.15.0-46-generic        | 9         | 0.99%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.88%   |
| 5.15.0-48-generic        | 8         | 0.88%   |
| 5.0.0-25-generic         | 8         | 0.88%   |
| 4.18.0-15-generic        | 8         | 0.88%   |
| 6.2.6-desktop-1omv2390   | 7         | 0.77%   |
| 5.4.0-58-generic         | 7         | 0.77%   |
| 5.4.0-54-generic         | 7         | 0.77%   |
| 5.15.0-47-generic        | 7         | 0.77%   |
| 5.11.0-37-generic        | 7         | 0.77%   |
| 5.8.0-48-generic         | 6         | 0.66%   |
| 5.3.0-46-generic         | 6         | 0.66%   |
| 5.19.0-35-generic        | 6         | 0.66%   |
| 5.15.0-58-generic        | 6         | 0.66%   |
| 5.15.0-52-generic        | 6         | 0.66%   |
| 5.15.0-43-generic        | 6         | 0.66%   |
| 5.8.0-41-generic         | 5         | 0.55%   |
| 5.4.0-80-generic         | 5         | 0.55%   |
| 5.4.0-45-generic         | 5         | 0.55%   |
| 5.15.0-53-generic        | 5         | 0.55%   |
| 5.11.0-7620-generic      | 5         | 0.55%   |
| 5.11.0-40-generic        | 5         | 0.55%   |
| 5.11.0-38-generic        | 5         | 0.55%   |
| 5.11.0-35-generic        | 5         | 0.55%   |
| 5.11.0-27-generic        | 5         | 0.55%   |
| 5.0.0-23-generic         | 5         | 0.55%   |
| 5.4.0-7634-generic       | 4         | 0.44%   |
| 5.4.0-33-generic         | 4         | 0.44%   |
| 5.3.0-26-generic         | 4         | 0.44%   |
| 5.15.0-60-generic        | 4         | 0.44%   |
| 5.13.0-30-generic        | 4         | 0.44%   |
| 5.11.0-41-generic        | 4         | 0.44%   |
| 5.0.0-37-generic         | 4         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 133       | 15.25%  |
| 5.15.0  | 90        | 10.32%  |
| 5.11.0  | 53        | 6.08%   |
| 5.8.0   | 41        | 4.7%    |
| 5.16.7  | 36        | 4.13%   |
| 5.13.0  | 36        | 4.13%   |
| 5.3.0   | 33        | 3.78%   |
| 5.0.0   | 30        | 3.44%   |
| 4.15.0  | 29        | 3.33%   |
| 5.10.14 | 24        | 2.75%   |
| 5.10.0  | 20        | 2.29%   |
| 4.18.0  | 17        | 1.95%   |
| 5.19.0  | 13        | 1.49%   |
| 4.19.0  | 13        | 1.49%   |
| 6.1.1   | 11        | 1.26%   |
| 6.2.6   | 8         | 0.92%   |
| 5.17.5  | 6         | 0.69%   |
| 5.16.0  | 6         | 0.69%   |
| 5.14.0  | 5         | 0.57%   |
| 6.1.0   | 4         | 0.46%   |
| 5.15.12 | 4         | 0.46%   |
| 5.14.16 | 4         | 0.46%   |
| 4.4.0   | 4         | 0.46%   |
| 6.2.8   | 3         | 0.34%   |
| 6.0.9   | 3         | 0.34%   |
| 6.0.12  | 3         | 0.34%   |
| 6.0.0   | 3         | 0.34%   |
| 5.9.11  | 3         | 0.34%   |
| 5.9.1   | 3         | 0.34%   |
| 5.19.16 | 3         | 0.34%   |
| 5.19.15 | 3         | 0.34%   |
| 5.18.0  | 3         | 0.34%   |
| 5.17.6  | 3         | 0.34%   |
| 5.16.12 | 3         | 0.34%   |
| 5.11.11 | 3         | 0.34%   |
| 5.10.53 | 3         | 0.34%   |
| 4.9.20  | 3         | 0.34%   |
| 6.2.9   | 2         | 0.23%   |
| 6.2.11  | 2         | 0.23%   |
| 6.2.0   | 2         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 141       | 16.41%  |
| 5.15    | 111       | 12.92%  |
| 5.10    | 69        | 8.03%   |
| 5.11    | 56        | 6.52%   |
| 5.16    | 55        | 6.4%    |
| 5.8     | 52        | 6.05%   |
| 5.13    | 40        | 4.66%   |
| 5.3     | 35        | 4.07%   |
| 5.0     | 32        | 3.73%   |
| 4.15    | 29        | 3.38%   |
| 6.1     | 28        | 3.26%   |
| 5.19    | 25        | 2.91%   |
| 6.2     | 20        | 2.33%   |
| 4.18    | 20        | 2.33%   |
| 6.0     | 19        | 2.21%   |
| 5.14    | 19        | 2.21%   |
| 5.17    | 18        | 2.1%    |
| 4.19    | 18        | 2.1%    |
| 5.18    | 15        | 1.75%   |
| 5.9     | 12        | 1.4%    |
| 5.6     | 7         | 0.81%   |
| 4.9     | 7         | 0.81%   |
| 5.12    | 6         | 0.7%    |
| 5.7     | 5         | 0.58%   |
| 5.5     | 5         | 0.58%   |
| 4.4     | 5         | 0.58%   |
| 5.2     | 2         | 0.23%   |
| 4.13    | 2         | 0.23%   |
| 4.10    | 2         | 0.23%   |
| 4.1     | 2         | 0.23%   |
| 5       | 1         | 0.12%   |
| 3.16    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 758       | 97.3%   |
| i686   | 21        | 2.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 339       | 41.96%  |
| KDE5            | 152       | 18.81%  |
| Unknown         | 77        | 9.53%   |
| XFCE            | 66        | 8.17%   |
| X-Cinnamon      | 44        | 5.45%   |
| Pantheon        | 24        | 2.97%   |
| MATE            | 19        | 2.35%   |
| KDE             | 18        | 2.23%   |
| LXQt            | 13        | 1.61%   |
| Cinnamon        | 10        | 1.24%   |
| Budgie          | 6         | 0.74%   |
| Unity           | 5         | 0.62%   |
| Deepin          | 5         | 0.62%   |
| sway            | 3         | 0.37%   |
| KDE4            | 3         | 0.37%   |
| i3              | 3         | 0.37%   |
| Hyprland        | 3         | 0.37%   |
| GNOME Flashback | 3         | 0.37%   |
| qtile           | 2         | 0.25%   |
| ICEWM           | 2         | 0.25%   |
| DWM             | 2         | 0.25%   |
| Cutefish        | 2         | 0.25%   |
| bspwm           | 2         | 0.25%   |
| xmonad          | 1         | 0.12%   |
| openbox         | 1         | 0.12%   |
| LXDE            | 1         | 0.12%   |
| Lubuntu         | 1         | 0.12%   |
| awesomeminimal  | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 621       | 77.82%  |
| Wayland | 119       | 14.91%  |
| Unknown | 53        | 6.64%   |
| Tty     | 5         | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 354       | 43.98%  |
| SDDM    | 144       | 17.89%  |
| GDM     | 118       | 14.66%  |
| LightDM | 82        | 10.19%  |
| GDM3    | 71        | 8.82%   |
| TDM     | 29        | 3.6%    |
| KDM     | 3         | 0.37%   |
| SLiM    | 2         | 0.25%   |
| Ly      | 1         | 0.12%   |
| LXDM    | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 632       | 79.9%   |
| Unknown | 76        | 9.61%   |
| id_ID   | 55        | 6.95%   |
| en_GB   | 8         | 1.01%   |
| C       | 8         | 1.01%   |
| en_SG   | 3         | 0.38%   |
| en_AU   | 2         | 0.25%   |
| en_AG   | 2         | 0.25%   |
| jv_ID   | 1         | 0.13%   |
| fr_FR   | 1         | 0.13%   |
| en_IN   | 1         | 0.13%   |
| de_DE   | 1         | 0.13%   |
| de_CH   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 464       | 58.29%  |
| BIOS | 332       | 41.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 620       | 77.89%  |
| Btrfs   | 73        | 9.17%   |
| Overlay | 59        | 7.41%   |
| Unknown | 25        | 3.14%   |
| Xfs     | 6         | 0.75%   |
| Ext2    | 5         | 0.63%   |
| Zfs     | 4         | 0.5%    |
| F2fs    | 2         | 0.25%   |
| Ext3    | 2         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 373       | 46.98%  |
| GPT     | 313       | 39.42%  |
| MBR     | 108       | 13.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 691       | 87.47%  |
| Yes       | 99        | 12.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 446       | 56.24%  |
| Yes       | 347       | 43.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 197       | 25.29%  |
| ASUSTek Computer    | 176       | 22.59%  |
| Acer                | 117       | 15.02%  |
| Hewlett-Packard     | 112       | 14.38%  |
| Dell                | 64        | 8.22%   |
| Toshiba             | 26        | 3.34%   |
| MSI                 | 20        | 2.57%   |
| Apple               | 12        | 1.54%   |
| AXIOO               | 10        | 1.28%   |
| Sony                | 8         | 1.03%   |
| Fujitsu             | 7         | 0.9%    |
| Samsung Electronics | 4         | 0.51%   |
| Clevo               | 3         | 0.39%   |
| Timi                | 2         | 0.26%   |
| Intel               | 2         | 0.26%   |
| Infinix             | 2         | 0.26%   |
| HUAWEI              | 2         | 0.26%   |
| Gigabyte Technology | 2         | 0.26%   |
| Unknown             | 2         | 0.26%   |
| Valve               | 1         | 0.13%   |
| Sole                | 1         | 0.13%   |
| Phoenix/SiS         | 1         | 0.13%   |
| Panasonic           | 1         | 0.13%   |
| Notebook            | 1         | 0.13%   |
| Hampoo              | 1         | 0.13%   |
| GPD                 | 1         | 0.13%   |
| Google              | 1         | 0.13%   |
| Compal              | 1         | 0.13%   |
| Chuwi               | 1         | 0.13%   |
| ADVAN               | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo IdeaPad 330-14AST 81D5           | 10        | 1.28%   |
| Lenovo G40-45 80E1                      | 10        | 1.28%   |
| HP Notebook                             | 9         | 1.16%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 8         | 1.03%   |
| HP 14                                   | 6         | 0.77%   |
| Acer Aspire 4752                        | 6         | 0.77%   |
| Lenovo IdeaPad S340-14API 81NB          | 5         | 0.64%   |
| Lenovo G400 20235                       | 5         | 0.64%   |
| HP Pavilion g4                          | 5         | 0.64%   |
| HP Laptop 14-bw0xx                      | 5         | 0.64%   |
| ASUS X455YA                             | 5         | 0.64%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.64%   |
| Apple MacBookPro12,1                    | 5         | 0.64%   |
| Acer Aspire 4750                        | 5         | 0.64%   |
| Unknown                                 | 5         | 0.64%   |
| Lenovo IdeaPad 320-14AST 80XU           | 4         | 0.51%   |
| Lenovo G40-30 80FY                      | 4         | 0.51%   |
| HP Pavilion 14                          | 4         | 0.51%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.51%   |
| HP Laptop 14-bs0xx                      | 4         | 0.51%   |
| HP 1000                                 | 4         | 0.51%   |
| ASUS X455LF                             | 4         | 0.51%   |
| ASUS X453SA                             | 4         | 0.51%   |
| ASUS X442URR                            | 4         | 0.51%   |
| ASUS X200MA                             | 4         | 0.51%   |
| ASUS GL553VD                            | 4         | 0.51%   |
| Acer Swift SF314-71                     | 4         | 0.51%   |
| Acer Aspire E5-475G                     | 4         | 0.51%   |
| Lenovo V310-14ISK 80SX                  | 3         | 0.39%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.39%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 3         | 0.39%   |
| Lenovo IdeaPad 3 14ARE05 81W3           | 3         | 0.39%   |
| Lenovo G400s 20244                      | 3         | 0.39%   |
| Dell Latitude E6230                     | 3         | 0.39%   |
| ASUS X456URK                            | 3         | 0.39%   |
| ASUS X455LD                             | 3         | 0.39%   |
| ASUS X450EA                             | 3         | 0.39%   |
| ASUS X441NA                             | 3         | 0.39%   |
| ASUS X441BA                             | 3         | 0.39%   |
| ASUS VivoBook_ASUSLaptop X412DA_A412DA  | 3         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 75        | 9.63%   |
| Acer Aspire        | 70        | 8.99%   |
| Lenovo ThinkPad    | 66        | 8.47%   |
| ASUS VivoBook      | 31        | 3.98%   |
| Dell Latitude      | 30        | 3.85%   |
| HP Pavilion        | 28        | 3.59%   |
| HP Laptop          | 27        | 3.47%   |
| Toshiba Satellite  | 18        | 2.31%   |
| Acer Swift         | 18        | 2.31%   |
| Dell Inspiron      | 16        | 2.05%   |
| HP EliteBook       | 13        | 1.67%   |
| Lenovo G40-45      | 10        | 1.28%   |
| Dell Vostro        | 10        | 1.28%   |
| Lenovo ThinkBook   | 9         | 1.16%   |
| HP Notebook        | 9         | 1.16%   |
| Acer Nitro         | 8         | 1.03%   |
| MSI Modern         | 6         | 0.77%   |
| HP 14              | 6         | 0.77%   |
| ASUS TUF           | 6         | 0.77%   |
| Toshiba PORTEGE    | 5         | 0.64%   |
| Lenovo Yoga        | 5         | 0.64%   |
| Lenovo G400        | 5         | 0.64%   |
| HP ProBook         | 5         | 0.64%   |
| ASUS X455YA        | 5         | 0.64%   |
| Apple MacBookPro12 | 5         | 0.64%   |
| Unknown            | 5         | 0.64%   |
| Lenovo G40-30      | 4         | 0.51%   |
| HP 1000            | 4         | 0.51%   |
| AXIOO Mybook       | 4         | 0.51%   |
| ASUS ZenBook       | 4         | 0.51%   |
| ASUS X455LF        | 4         | 0.51%   |
| ASUS X453SA        | 4         | 0.51%   |
| ASUS X442URR       | 4         | 0.51%   |
| ASUS X200MA        | 4         | 0.51%   |
| ASUS ROG           | 4         | 0.51%   |
| ASUS GL553VD       | 4         | 0.51%   |
| ASUS ASUS          | 4         | 0.51%   |
| Acer One           | 4         | 0.51%   |
| MSI GF63           | 3         | 0.39%   |
| Lenovo V310-14ISK  | 3         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 80        | 10.27%  |
| 2019 | 76        | 9.76%   |
| 2013 | 72        | 9.24%   |
| 2012 | 68        | 8.73%   |
| 2011 | 66        | 8.47%   |
| 2021 | 61        | 7.83%   |
| 2014 | 59        | 7.57%   |
| 2017 | 54        | 6.93%   |
| 2015 | 51        | 6.55%   |
| 2020 | 47        | 6.03%   |
| 2016 | 45        | 5.78%   |
| 2010 | 38        | 4.88%   |
| 2009 | 21        | 2.7%    |
| 2008 | 15        | 1.93%   |
| 2022 | 14        | 1.8%    |
| 2007 | 8         | 1.03%   |
| 2006 | 3         | 0.39%   |
| 2023 | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 779       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 717       | 90.76%  |
| Enabled  | 73        | 9.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 778       | 99.87%  |
| Yes  | 1         | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 254       | 32.23%  |
| 3.01-4.0    | 211       | 26.78%  |
| 8.01-16.0   | 129       | 16.37%  |
| 16.01-24.0  | 90        | 11.42%  |
| 1.01-2.0    | 75        | 9.52%   |
| 2.01-3.0    | 10        | 1.27%   |
| 32.01-64.0  | 8         | 1.02%   |
| 24.01-32.0  | 5         | 0.63%   |
| 0.51-1.0    | 5         | 0.63%   |
| 64.01-256.0 | 1         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 307       | 36.08%  |
| 2.01-3.0   | 242       | 28.44%  |
| 3.01-4.0   | 113       | 13.28%  |
| 4.01-8.0   | 110       | 12.93%  |
| 0.51-1.0   | 53        | 6.23%   |
| 8.01-16.0  | 21        | 2.47%   |
| 0.01-0.5   | 4         | 0.47%   |
| 16.01-24.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 572       | 72.22%  |
| 2      | 193       | 24.37%  |
| 3      | 20        | 2.53%   |
| 0      | 4         | 0.51%   |
| 4      | 3         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 484       | 61.66%  |
| Yes       | 301       | 38.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 645       | 82.69%  |
| No        | 135       | 17.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 766       | 98.21%  |
| No        | 14        | 1.79%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 602       | 76.69%  |
| No        | 183       | 23.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 779       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Jakarta         | 221       | 26.06%  |
| Surabaya        | 89        | 10.5%   |
| Bandung         | 60        | 7.08%   |
| Yogyakarta      | 37        | 4.36%   |
| Semarang        | 32        | 3.77%   |
| Bogor           | 32        | 3.77%   |
| Bekasi          | 22        | 2.59%   |
| Malang          | 21        | 2.48%   |
| Denpasar        | 18        | 2.12%   |
| Tangerang       | 15        | 1.77%   |
| Medan           | 14        | 1.65%   |
| Makassar        | 13        | 1.53%   |
| South Tangerang | 12        | 1.42%   |
| Palembang       | 11        | 1.3%    |
| Depok           | 10        | 1.18%   |
| Sleman          | 9         | 1.06%   |
| Tasikmalaya     | 7         | 0.83%   |
| Samarinda       | 7         | 0.83%   |
| Banjarmasin     | 7         | 0.83%   |
| Surakarta       | 6         | 0.71%   |
| Blitar          | 6         | 0.71%   |
| Banda Aceh      | 6         | 0.71%   |
| Balikpapan      | 6         | 0.71%   |
| Pontianak       | 5         | 0.59%   |
| Gresik          | 5         | 0.59%   |
| Brebes          | 5         | 0.59%   |
| Mataram         | 4         | 0.47%   |
| Kudus           | 4         | 0.47%   |
| Kediri          | 4         | 0.47%   |
| Cirebon         | 4         | 0.47%   |
| Tegal           | 3         | 0.35%   |
| Purwokerto      | 3         | 0.35%   |
| Pekan Baru      | 3         | 0.35%   |
| Pasuruan        | 3         | 0.35%   |
| Magelang        | 3         | 0.35%   |
| Jember          | 3         | 0.35%   |
| Jambi City      | 3         | 0.35%   |
| Demak           | 3         | 0.35%   |
| Buaran          | 3         | 0.35%   |
| Batam           | 3         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 166       | 213    | 16.97%  |
| WDC                   | 124       | 148    | 12.68%  |
| Toshiba               | 100       | 109    | 10.22%  |
| Samsung Electronics   | 89        | 117    | 9.1%    |
| HGST                  | 54        | 59     | 5.52%   |
| Hitachi               | 44        | 51     | 4.5%    |
| Unknown               | 35        | 41     | 3.58%   |
| Kingston              | 31        | 39     | 3.17%   |
| Intel                 | 31        | 49     | 3.17%   |
| SanDisk               | 27        | 36     | 2.76%   |
| SK hynix              | 25        | 30     | 2.56%   |
| Micron Technology     | 25        | 31     | 2.56%   |
| V-GeN                 | 24        | 25     | 2.45%   |
| A-DATA Technology     | 20        | 24     | 2.04%   |
| MidasForce            | 15        | 16     | 1.53%   |
| Fujitsu               | 10        | 11     | 1.02%   |
| China                 | 10        | 10     | 1.02%   |
| JMicron Technology    | 9         | 10     | 0.92%   |
| Unknown               | 9         | 10     | 0.92%   |
| Team                  | 8         | 11     | 0.82%   |
| Apacer                | 8         | 8      | 0.82%   |
| VISIPRO               | 7         | 10     | 0.72%   |
| Crucial               | 7         | 9      | 0.72%   |
| Apple                 | 7         | 8      | 0.72%   |
| Patriot               | 6         | 8      | 0.61%   |
| Silicon Motion        | 5         | 6      | 0.51%   |
| RX7                   | 4         | 4      | 0.41%   |
| Phison Electronics    | 4         | 5      | 0.41%   |
| Wellcomm              | 3         | 3      | 0.31%   |
| Pioneer               | 3         | 3      | 0.31%   |
| LITEONIT              | 3         | 4      | 0.31%   |
| LITEON                | 3         | 4      | 0.31%   |
| KIOXIA                | 3         | 3      | 0.31%   |
| EYOTA                 | 3         | 3      | 0.31%   |
| External              | 3         | 3      | 0.31%   |
| UMIS                  | 2         | 3      | 0.2%    |
| Transcend             | 2         | 3      | 0.2%    |
| Smart                 | 2         | 2      | 0.2%    |
| Realtek Semiconductor | 2         | 2      | 0.2%    |
| PNY                   | 2         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB    | 38        | 3.78%   |
| Seagate ST1000LM035-1RK172 970GB   | 36        | 3.58%   |
| Toshiba MQ01ABF050 500GB           | 21        | 2.09%   |
| Toshiba MQ04ABF100 1TB             | 20        | 1.99%   |
| Toshiba MQ01ABD100 1TB             | 18        | 1.79%   |
| HGST HTS545050A7E680 500GB         | 17        | 1.69%   |
| A-DATA SU650 120GB SSD             | 11        | 1.09%   |
| Seagate ST9500325AS 500GB          | 10        | 1%      |
| Hitachi HTS545050A7E380 500GB      | 10        | 1%      |
| HGST HTS725050A7E630 500GB         | 10        | 1%      |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.9%    |
| Unknown                            | 9         | 0.9%    |
| Seagate ST500LT012-9WS142 500GB    | 8         | 0.8%    |
| SanDisk NVMe SSD Drive 512GB       | 8         | 0.8%    |
| Hitachi HTS543232A7A384 320GB      | 8         | 0.8%    |
| WDC WD5000LPVX-22V0TT0 500GB       | 7         | 0.7%    |
| WDC WD10SPZX-21Z10T0 1TB           | 7         | 0.7%    |
| Seagate ST9320325AS 320GB          | 7         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB     | 7         | 0.7%    |
| Samsung SSD 850 EVO 250GB          | 7         | 0.7%    |
| HGST HTS721010A9E630 1TB           | 7         | 0.7%    |
| WDC WD5000LPVX-80V0TT0 500GB       | 6         | 0.6%    |
| Unknown MMC Card  32GB             | 6         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.6%    |
| MidasForce SSD 128GB               | 6         | 0.6%    |
| HGST HTS541010A9E680 1TB           | 6         | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 5         | 0.5%    |
| WDC WD10JPCX-24UE4T0 1TB           | 5         | 0.5%    |
| Seagate ST500LM021-1KJ152 500GB    | 5         | 0.5%    |
| Seagate ST1000LX015-1U7172 1TB     | 5         | 0.5%    |
| Samsung SSD 860 EVO 250GB          | 5         | 0.5%    |
| JMicron Generic 1TB                | 5         | 0.5%    |
| Intel NVMe SSD Drive 512GB         | 5         | 0.5%    |
| HGST HTS545050A7E380 500GB         | 5         | 0.5%    |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 4         | 0.4%    |
| WDC WD5000LPCX-24C6HT0 500GB       | 4         | 0.4%    |
| WDC WD10SPZX-24Z10 1TB             | 4         | 0.4%    |
| Unknown MMC Card  128GB            | 4         | 0.4%    |
| Toshiba MQ01ABD050 500GB           | 4         | 0.4%    |
| Toshiba MQ01ABD032 320GB           | 4         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 165       | 209    | 35.11%  |
| WDC                 | 92        | 104    | 19.57%  |
| Toshiba             | 88        | 97     | 18.72%  |
| HGST                | 54        | 59     | 11.49%  |
| Hitachi             | 44        | 51     | 9.36%   |
| Fujitsu             | 8         | 8      | 1.7%    |
| JMicron Technology  | 6         | 6      | 1.28%   |
| Samsung Electronics | 4         | 4      | 0.85%   |
| Unknown             | 3         | 3      | 0.64%   |
| Pioneer             | 2         | 2      | 0.43%   |
| USB3.0              | 1         | 1      | 0.21%   |
| HGST HTS            | 1         | 3      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 42        | 51     | 16.8%   |
| WDC                 | 18        | 27     | 7.2%    |
| Kingston            | 16        | 17     | 6.4%    |
| MidasForce          | 15        | 16     | 6%      |
| A-DATA Technology   | 15        | 19     | 6%      |
| V-GeN               | 14        | 15     | 5.6%    |
| SanDisk             | 12        | 19     | 4.8%    |
| China               | 10        | 10     | 4%      |
| Apacer              | 8         | 8      | 3.2%    |
| Intel               | 7         | 11     | 2.8%    |
| Crucial             | 7         | 9      | 2.8%    |
| Team                | 6         | 9      | 2.4%    |
| Patriot             | 6         | 8      | 2.4%    |
| Unknown             | 6         | 6      | 2.4%    |
| VISIPRO             | 5         | 8      | 2%      |
| Apple               | 5         | 5      | 2%      |
| Toshiba             | 4         | 4      | 1.6%    |
| Micron Technology   | 4         | 5      | 1.6%    |
| Wellcomm            | 3         | 3      | 1.2%    |
| Seagate             | 3         | 3      | 1.2%    |
| RX7                 | 3         | 3      | 1.2%    |
| LITEONIT            | 3         | 4      | 1.2%    |
| LITEON              | 3         | 4      | 1.2%    |
| External            | 3         | 3      | 1.2%    |
| Smart               | 2         | 2      | 0.8%    |
| SK hynix            | 2         | 2      | 0.8%    |
| Lexar               | 2         | 2      | 0.8%    |
| GALAX               | 2         | 2      | 0.8%    |
| EYOTA               | 2         | 2      | 0.8%    |
| XSTAR               | 1         | 1      | 0.4%    |
| WellcommMaster      | 1         | 1      | 0.4%    |
| Vaseky              | 1         | 2      | 0.4%    |
| Varro               | 1         | 1      | 0.4%    |
| UNIC2               | 1         | 1      | 0.4%    |
| Transcend           | 1         | 1      | 0.4%    |
| TO Exter            | 1         | 1      | 0.4%    |
| SPCC                | 1         | 1      | 0.4%    |
| Ramos Technology    | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| Pioneer             | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 452       | 549    | 47.93%  |
| SSD     | 239       | 300    | 25.34%  |
| NVMe    | 196       | 261    | 20.78%  |
| MMC     | 28        | 36     | 2.97%   |
| Unknown | 28        | 34     | 2.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 613       | 852    | 70.79%  |
| NVMe | 196       | 260    | 22.63%  |
| SAS  | 29        | 32     | 3.35%   |
| MMC  | 28        | 36     | 3.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 456       | 601    | 69.2%   |
| 0.51-1.0   | 188       | 225    | 28.53%  |
| 1.01-2.0   | 13        | 21     | 1.97%   |
| 3.01-4.0   | 2         | 2      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 231       | 28.27%  |
| 251-500        | 214       | 26.19%  |
| 501-1000       | 93        | 11.38%  |
| 51-100         | 88        | 10.77%  |
| 1-20           | 60        | 7.34%   |
| 1001-2000      | 57        | 6.98%   |
| 21-50          | 52        | 6.36%   |
| Unknown        | 10        | 1.22%   |
| More than 3000 | 6         | 0.73%   |
| 2001-3000      | 6         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 316       | 36.92%  |
| 21-50          | 165       | 19.28%  |
| 101-250        | 114       | 13.32%  |
| 51-100         | 108       | 12.62%  |
| 251-500        | 81        | 9.46%   |
| 501-1000       | 47        | 5.49%   |
| 1001-2000      | 12        | 1.4%    |
| Unknown        | 10        | 1.17%   |
| 2001-3000      | 2         | 0.23%   |
| More than 3000 | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB          | 8         | 8      | 7.92%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 5      | 4.95%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 5      | 4.95%   |
| Seagate ST9500325AS 500GB           | 4         | 4      | 3.96%   |
| Toshiba MQ01ABD032 320GB            | 3         | 3      | 2.97%   |
| Seagate ST1000LM035-1RK172 970GB    | 3         | 3      | 2.97%   |
| Hitachi HTS545050A7E380 500GB       | 3         | 3      | 2.97%   |
| HGST HTS725050A7E630 500GB          | 3         | 3      | 2.97%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 2      | 1.98%   |
| WDC WD3200BEKT-60V5T1 320GB         | 2         | 2      | 1.98%   |
| WDC WD10JPCX-24UE4T0 1TB            | 2         | 3      | 1.98%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 1.98%   |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 1.98%   |
| Toshiba MK3265GSX 320GB             | 2         | 3      | 1.98%   |
| Seagate ST1000LX015-1U7172 1TB      | 2         | 3      | 1.98%   |
| WellcommMaster 128GB SSD            | 1         | 1      | 0.99%   |
| Wellcomm Master 128GB SSD           | 1         | 1      | 0.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 1      | 0.99%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 1      | 0.99%   |
| WDC WD5000LPCX-22VHAT0 500GB        | 1         | 1      | 0.99%   |
| WDC WD5000L 500GB                   | 1         | 1      | 0.99%   |
| WDC WD5000BPVT-60HXZT3 500GB        | 1         | 1      | 0.99%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 1      | 0.99%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 1      | 0.99%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 0.99%   |
| VISIPRO SSD 256GB                   | 1         | 3      | 0.99%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 0.99%   |
| Toshiba MK7575GSX 752GB             | 1         | 2      | 0.99%   |
| Toshiba MK5075GSX 500GB             | 1         | 1      | 0.99%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 0.99%   |
| Toshiba MK3276GSX 320GB             | 1         | 1      | 0.99%   |
| Toshiba MK3275GSX 320GB             | 1         | 1      | 0.99%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 0.99%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 0.99%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 0.99%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 0.99%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 8      | 0.99%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 35     | 26.26%  |
| Toshiba             | 17        | 19     | 17.17%  |
| WDC                 | 14        | 15     | 14.14%  |
| HGST                | 14        | 15     | 14.14%  |
| Hitachi             | 11        | 11     | 11.11%  |
| Samsung Electronics | 3         | 4      | 3.03%   |
| SanDisk             | 2         | 2      | 2.02%   |
| Micron Technology   | 2         | 2      | 2.02%   |
| A-DATA Technology   | 2         | 3      | 2.02%   |
| WellcommMaster      | 1         | 1      | 1.01%   |
| Wellcomm            | 1         | 1      | 1.01%   |
| VISIPRO             | 1         | 3      | 1.01%   |
| RX7                 | 1         | 1      | 1.01%   |
| KLEVV               | 1         | 1      | 1.01%   |
| Intel               | 1         | 1      | 1.01%   |
| Crucial             | 1         | 1      | 1.01%   |
| China               | 1         | 1      | 1.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 35     | 31.71%  |
| Toshiba             | 17        | 19     | 20.73%  |
| HGST                | 14        | 15     | 17.07%  |
| WDC                 | 13        | 14     | 15.85%  |
| Hitachi             | 11        | 11     | 13.41%  |
| Samsung Electronics | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 95     | 82.83%  |
| SSD  | 15        | 18     | 15.15%  |
| NVMe | 2         | 3      | 2.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Notebooks | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB  | 1         | 1      | 50%     |
| Hitachi HTS545050A7E380 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 416       | 624    | 49.82%  |
| Works    | 321       | 438    | 38.44%  |
| Malfunc  | 96        | 116    | 11.5%   |
| Failed   | 2         | 2      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 543       | 60.33%  |
| AMD                              | 165       | 18.33%  |
| Samsung Electronics              | 50        | 5.56%   |
| SanDisk                          | 30        | 3.33%   |
| SK hynix                         | 22        | 2.44%   |
| Micron Technology                | 21        | 2.33%   |
| Kingston Technology Company      | 15        | 1.67%   |
| Phison Electronics               | 10        | 1.11%   |
| Silicon Motion                   | 9         | 1%      |
| ADATA Technology                 | 7         | 0.78%   |
| Toshiba America Info Systems     | 6         | 0.67%   |
| KIOXIA                           | 5         | 0.56%   |
| Union Memory (Shenzhen)          | 4         | 0.44%   |
| Silicon Integrated Systems [SiS] | 4         | 0.44%   |
| Realtek Semiconductor            | 3         | 0.33%   |
| Nvidia                           | 2         | 0.22%   |
| O2 Micro                         | 1         | 0.11%   |
| Lenovo                           | 1         | 0.11%   |
| ASMedia Technology               | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 155       | 16.13%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 72        | 7.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 69        | 7.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 49        | 5.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 42        | 4.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 40        | 4.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 30        | 3.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 24        | 2.5%    |
| Micron NVMe Storage Controller                                                   | 21        | 2.19%   |
| Samsung NVMe SSD Controller 980                                                  | 19        | 1.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 19        | 1.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 19        | 1.98%   |
| Intel Volume Management Device NVMe RAID Controller                              | 17        | 1.77%   |
| Intel SSD 660P Series                                                            | 15        | 1.56%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 15        | 1.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 14        | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 14        | 1.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 11        | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 10        | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 9         | 0.94%   |
| SK hynix BC511                                                                   | 8         | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 0.83%   |
| SanDisk PC SN520 NVMe SSD                                                        | 7         | 0.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 0.73%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 0.62%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 6         | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 6         | 0.62%   |
| Kingston Company Company Non-Volatile memory controller                          | 6         | 0.62%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 6         | 0.62%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 6         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.62%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.52%   |
| Samsung Electronics SATA controller                                              | 5         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 640       | 68.6%   |
| NVMe | 196       | 21.01%  |
| RAID | 57        | 6.11%   |
| IDE  | 40        | 4.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 584       | 74.97%  |
| AMD    | 195       | 25.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 2.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.67%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 13        | 1.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 12        | 1.54%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 12        | 1.54%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 12        | 1.54%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 11        | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 10        | 1.28%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 10        | 1.28%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 10        | 1.28%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 1.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 1.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.16%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 9         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 9         | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 1.16%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 9         | 1.16%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 1.03%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 8         | 1.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 8         | 1.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 8         | 1.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.9%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.9%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 0.77%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.77%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.77%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.77%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.77%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 0.77%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 0.77%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 6         | 0.77%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 199       | 25.55%  |
| Intel Core i3           | 110       | 14.12%  |
| Intel Core i7           | 105       | 13.48%  |
| Intel Celeron           | 65        | 8.34%   |
| Other                   | 59        | 7.57%   |
| AMD Ryzen 5             | 46        | 5.91%   |
| Intel Core 2 Duo        | 26        | 3.34%   |
| AMD A8                  | 22        | 2.82%   |
| AMD Ryzen 3             | 21        | 2.7%    |
| Intel Pentium           | 15        | 1.93%   |
| AMD Ryzen 7             | 15        | 1.93%   |
| AMD A4                  | 12        | 1.54%   |
| Intel Atom              | 10        | 1.28%   |
| AMD E1                  | 9         | 1.16%   |
| AMD E2                  | 7         | 0.9%    |
| AMD E                   | 7         | 0.9%    |
| AMD A6                  | 7         | 0.9%    |
| Intel Pentium Dual-Core | 6         | 0.77%   |
| Intel Pentium Dual      | 5         | 0.64%   |
| Intel Genuine           | 5         | 0.64%   |
| AMD A10                 | 5         | 0.64%   |
| AMD Ryzen 9             | 4         | 0.51%   |
| AMD FX                  | 3         | 0.39%   |
| AMD C-60                | 3         | 0.39%   |
| AMD Athlon              | 3         | 0.39%   |
| Intel Xeon              | 2         | 0.26%   |
| Intel Core 2            | 2         | 0.26%   |
| AMD A12                 | 2         | 0.26%   |
| AMD Turion 64 Mobile    | 1         | 0.13%   |
| AMD Ryzen 5 PRO         | 1         | 0.13%   |
| AMD PRO A10             | 1         | 0.13%   |
| AMD C-50                | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 508       | 65.21%  |
| 4      | 192       | 24.65%  |
| 6      | 46        | 5.91%   |
| 8      | 17        | 2.18%   |
| 1      | 9         | 1.16%   |
| 12     | 4         | 0.51%   |
| 10     | 2         | 0.26%   |
| 14     | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 779       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 549       | 70.47%  |
| 1      | 230       | 29.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 765       | 98.2%   |
| Unknown        | 11        | 1.41%   |
| 32-bit         | 3         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 130       | 16.07%  |
| 0x206a7    | 66        | 8.16%   |
| 0x306a9    | 51        | 6.3%    |
| 0x40651    | 38        | 4.7%    |
| 0x306d4    | 33        | 4.08%   |
| 0x806ea    | 28        | 3.46%   |
| 0x06006705 | 24        | 2.97%   |
| 0x806e9    | 23        | 2.84%   |
| 0x406e3    | 22        | 2.72%   |
| 0x20655    | 22        | 2.72%   |
| 0x806ec    | 21        | 2.6%    |
| 0x806c1    | 20        | 2.47%   |
| 0x1067a    | 19        | 2.35%   |
| 0x906ea    | 17        | 2.1%    |
| 0x08108109 | 17        | 2.1%    |
| 0x0a50000c | 15        | 1.85%   |
| 0x806eb    | 14        | 1.73%   |
| 0x07030105 | 14        | 1.73%   |
| 0x30678    | 13        | 1.61%   |
| 0x706e5    | 12        | 1.48%   |
| 0x6fd      | 11        | 1.36%   |
| 0x08108102 | 11        | 1.36%   |
| 0x306c3    | 10        | 1.24%   |
| 0x706a8    | 8         | 0.99%   |
| 0x406c3    | 8         | 0.99%   |
| 0x08608103 | 8         | 0.99%   |
| 0x08600104 | 8         | 0.99%   |
| 0x906e9    | 7         | 0.87%   |
| 0x406c4    | 7         | 0.87%   |
| 0x20652    | 7         | 0.87%   |
| 0x06001119 | 7         | 0.87%   |
| 0x05000119 | 7         | 0.87%   |
| 0x0810100b | 6         | 0.74%   |
| 0x0700010f | 6         | 0.74%   |
| 0x03000027 | 6         | 0.74%   |
| 0x906a3    | 5         | 0.62%   |
| 0x506e3    | 5         | 0.62%   |
| 0x10676    | 5         | 0.62%   |
| 0x06006704 | 5         | 0.62%   |
| 0x0600611a | 5         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 130       | 16.69%  |
| SandyBridge      | 75        | 9.63%   |
| IvyBridge        | 60        | 7.7%    |
| Haswell          | 57        | 7.32%   |
| Excavator        | 40        | 5.13%   |
| Westmere         | 37        | 4.75%   |
| Broadwell        | 37        | 4.75%   |
| Silvermont       | 36        | 4.62%   |
| Skylake          | 31        | 3.98%   |
| Zen+             | 30        | 3.85%   |
| Penryn           | 26        | 3.34%   |
| TigerLake        | 24        | 3.08%   |
| Puma             | 24        | 3.08%   |
| Zen 3            | 20        | 2.57%   |
| Zen 2            | 17        | 2.18%   |
| Core             | 16        | 2.05%   |
| IceLake          | 14        | 1.8%    |
| Bobcat           | 14        | 1.8%    |
| Unknown          | 14        | 1.8%    |
| Zen              | 12        | 1.54%   |
| Goldmont plus    | 12        | 1.54%   |
| Piledriver       | 8         | 1.03%   |
| Jaguar           | 8         | 1.03%   |
| Goldmont         | 7         | 0.9%    |
| Alderlake Hybrid | 7         | 0.9%    |
| K10 Llano        | 6         | 0.77%   |
| CometLake        | 6         | 0.77%   |
| Bonnell          | 5         | 0.64%   |
| Steamroller      | 2         | 0.26%   |
| P6               | 2         | 0.26%   |
| Tremont          | 1         | 0.13%   |
| K8 Hammer        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 564       | 55.68%  |
| AMD                              | 245       | 24.19%  |
| Nvidia                           | 199       | 19.64%  |
| Silicon Integrated Systems [SiS] | 4         | 0.39%   |
| Silicon Motion                   | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 72        | 6.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 58        | 5.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 44        | 4.12%   |
| Intel HD Graphics 5500                                                                   | 32        | 3%      |
| Intel Core Processor Integrated Graphics Controller                                      | 32        | 3%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 32        | 3%      |
| Intel UHD Graphics 620                                                                   | 31        | 2.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 31        | 2.91%   |
| Intel HD Graphics 620                                                                    | 27        | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 2.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 1.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 1.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 1.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 1.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 1.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 18        | 1.69%   |
| AMD Renoir                                                                               | 17        | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 1.12%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.03%   |
| AMD Lucienne                                                                             | 10        | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.84%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 9         | 0.84%   |
| Nvidia GP108M [GeForce MX250]                                                            | 8         | 0.75%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 0.75%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 8         | 0.75%   |
| Intel HD Graphics 630                                                                    | 8         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.75%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 353       | 45.08%  |
| Intel + Nvidia     | 167       | 21.33%  |
| 1 x AMD            | 143       | 18.26%  |
| Intel + AMD        | 44        | 5.62%   |
| 2 x AMD            | 35        | 4.47%   |
| AMD + Nvidia       | 23        | 2.94%   |
| 1 x Nvidia         | 7         | 0.89%   |
| 1 x SiS            | 4         | 0.51%   |
| 2 x Intel          | 3         | 0.38%   |
| 2 x Nvidia         | 2         | 0.26%   |
| Other              | 1         | 0.13%   |
| 1 x Silicon Motion | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 673       | 85.3%   |
| Proprietary | 101       | 12.8%   |
| Unknown     | 15        | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 476       | 59.2%   |
| 1.01-2.0   | 137       | 17.04%  |
| 0.01-0.5   | 101       | 12.56%  |
| 0.51-1.0   | 42        | 5.22%   |
| 3.01-4.0   | 39        | 4.85%   |
| 5.01-6.0   | 7         | 0.87%   |
| 7.01-8.0   | 2         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 181       | 21.73%  |
| Chimei Innolux          | 159       | 19.09%  |
| BOE                     | 130       | 15.61%  |
| LG Display              | 112       | 13.45%  |
| Samsung Electronics     | 67        | 8.04%   |
| Goldstar                | 33        | 3.96%   |
| Lenovo                  | 19        | 2.28%   |
| PANDA                   | 14        | 1.68%   |
| Apple                   | 12        | 1.44%   |
| InfoVision              | 11        | 1.32%   |
| Sharp                   | 10        | 1.2%    |
| Chi Mei Optoelectronics | 10        | 1.2%    |
| InnoLux Display         | 8         | 0.96%   |
| Acer                    | 6         | 0.72%   |
| ViewSonic               | 5         | 0.6%    |
| LG Philips              | 5         | 0.6%    |
| Dell                    | 5         | 0.6%    |
| AOC                     | 5         | 0.6%    |
| Philips                 | 4         | 0.48%   |
| Toshiba                 | 3         | 0.36%   |
| Sony                    | 3         | 0.36%   |
| Quanta Display          | 3         | 0.36%   |
| Hewlett-Packard         | 3         | 0.36%   |
| HannStar                | 3         | 0.36%   |
| CPT                     | 3         | 0.36%   |
| Seiko/Epson             | 2         | 0.24%   |
| Panasonic               | 2         | 0.24%   |
| KDC                     | 2         | 0.24%   |
| BenQ                    | 2         | 0.24%   |
| WST                     | 1         | 0.12%   |
| Valve                   | 1         | 0.12%   |
| Mi                      | 1         | 0.12%   |
| JDI                     | 1         | 0.12%   |
| HKC                     | 1         | 0.12%   |
| HJC                     | 1         | 0.12%   |
| HIC                     | 1         | 0.12%   |
| Gateway                 | 1         | 0.12%   |
| CSO                     | 1         | 0.12%   |
| Armaggeddon             | 1         | 0.12%   |
| Ancor Communications    | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 18        | 2.16%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 14        | 1.68%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 14        | 1.68%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 14        | 1.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 12        | 1.44%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 11        | 1.32%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 11        | 1.32%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 10        | 1.2%    |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 10        | 1.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 9         | 1.08%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 9         | 1.08%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 9         | 1.08%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 9         | 1.08%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                 | 8         | 0.96%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 8         | 0.96%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 7         | 0.84%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch      | 7         | 0.84%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 6         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch      | 6         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 6         | 0.72%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 6         | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch | 5         | 0.6%    |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch          | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 5         | 0.6%    |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                 | 5         | 0.6%    |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                | 5         | 0.6%    |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch        | 5         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch | 4         | 0.48%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 4         | 0.48%   |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch         | 4         | 0.48%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 4         | 0.48%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 4         | 0.48%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 4         | 0.48%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch              | 4         | 0.48%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 4         | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 4         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 440       | 55.28%  |
| 1920x1080 (FHD)   | 239       | 30.03%  |
| 1280x800 (WXGA)   | 24        | 3.02%   |
| 1600x900 (HD+)    | 20        | 2.51%   |
| 3840x2160 (4K)    | 12        | 1.51%   |
| 1920x1200 (WUXGA) | 10        | 1.26%   |
| 1440x900 (WXGA+)  | 9         | 1.13%   |
| 2560x1600         | 8         | 1.01%   |
| 2560x1440 (QHD)   | 8         | 1.01%   |
| 1360x768          | 6         | 0.75%   |
| 2880x1800         | 5         | 0.63%   |
| 1024x600          | 4         | 0.5%    |
| 3840x2400         | 2         | 0.25%   |
| 2560x1080         | 2         | 0.25%   |
| 800x1280          | 1         | 0.13%   |
| 3440x1440         | 1         | 0.13%   |
| 3200x1800 (QHD+)  | 1         | 0.13%   |
| 2966x900          | 1         | 0.13%   |
| 2736x1824         | 1         | 0.13%   |
| 1024x768 (XGA)    | 1         | 0.13%   |
| Unknown           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 253       | 30.41%  |
| 14      | 242       | 29.09%  |
| 15      | 169       | 20.31%  |
| 12      | 35        | 4.21%   |
| 23      | 26        | 3.13%   |
| 11      | 26        | 3.13%   |
| 18      | 20        | 2.4%    |
| 21      | 11        | 1.32%   |
| 24      | 8         | 0.96%   |
| 19      | 8         | 0.96%   |
| 17      | 6         | 0.72%   |
| 40      | 4         | 0.48%   |
| 10      | 4         | 0.48%   |
| 34      | 3         | 0.36%   |
| 27      | 3         | 0.36%   |
| Unknown | 3         | 0.36%   |
| 48      | 2         | 0.24%   |
| 31      | 2         | 0.24%   |
| 72      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 54      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |
| 16      | 1         | 0.12%   |
| 9       | 1         | 0.12%   |
| 7       | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 603       | 73%     |
| 201-300     | 115       | 13.92%  |
| 401-500     | 39        | 4.72%   |
| 501-600     | 36        | 4.36%   |
| 351-400     | 14        | 1.69%   |
| 801-900     | 4         | 0.48%   |
| 1001-1500   | 4         | 0.48%   |
| 701-800     | 3         | 0.36%   |
| 601-700     | 3         | 0.36%   |
| Unknown     | 3         | 0.36%   |
| 1501-2000   | 1         | 0.12%   |
| 1-100       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 691       | 91.04%  |
| 16/10   | 56        | 7.38%   |
| 3/2     | 3         | 0.4%    |
| 21/9    | 3         | 0.4%    |
| Unknown | 3         | 0.4%    |
| 4/3     | 2         | 0.26%   |
| 0.67    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 451       | 54.21%  |
| 101-110        | 167       | 20.07%  |
| 201-250        | 45        | 5.41%   |
| 71-80          | 40        | 4.81%   |
| 61-70          | 34        | 4.09%   |
| 51-60          | 26        | 3.13%   |
| 141-150        | 20        | 2.4%    |
| 151-200        | 9         | 1.08%   |
| 91-100         | 6         | 0.72%   |
| More than 1000 | 5         | 0.6%    |
| 351-500        | 5         | 0.6%    |
| 41-50          | 5         | 0.6%    |
| 121-130        | 4         | 0.48%   |
| 501-1000       | 4         | 0.48%   |
| 301-350        | 3         | 0.36%   |
| Unknown        | 3         | 0.36%   |
| 131-140        | 2         | 0.24%   |
| 111-120        | 2         | 0.24%   |
| 1-40           | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 398       | 48.3%   |
| 121-160       | 269       | 32.65%  |
| 51-100        | 92        | 11.17%  |
| 161-240       | 39        | 4.73%   |
| More than 240 | 16        | 1.94%   |
| 1-50          | 7         | 0.85%   |
| Unknown       | 3         | 0.36%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 692       | 86.83%  |
| 2     | 84        | 10.54%  |
| 0     | 18        | 2.26%   |
| 3     | 3         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 478       | 37.52%  |
| Intel                             | 285       | 22.37%  |
| Qualcomm Atheros                  | 279       | 21.9%   |
| Broadcom                          | 83        | 6.51%   |
| MediaTek                          | 27        | 2.12%   |
| Broadcom Limited                  | 16        | 1.26%   |
| Xiaomi                            | 13        | 1.02%   |
| Samsung Electronics               | 11        | 0.86%   |
| TP-Link                           | 9         | 0.71%   |
| Ralink Technology                 | 9         | 0.71%   |
| Marvell Technology Group          | 9         | 0.71%   |
| Ralink                            | 7         | 0.55%   |
| Qualcomm Atheros Communications   | 6         | 0.47%   |
| OPPO Electronics                  | 6         | 0.47%   |
| JMicron Technology                | 5         | 0.39%   |
| Huawei Technologies               | 4         | 0.31%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.24%   |
| Ericsson Business Mobile Networks | 3         | 0.24%   |
| Attansic Technology               | 3         | 0.24%   |
| ASIX Electronics                  | 3         | 0.24%   |
| Sierra Wireless                   | 2         | 0.16%   |
| Qualcomm                          | 2         | 0.16%   |
| Nvidia                            | 2         | 0.16%   |
| ICS Advent                        | 2         | 0.16%   |
| Hewlett-Packard                   | 2         | 0.16%   |
| Lenovo                            | 1         | 0.08%   |
| HTC (High Tech Computer)          | 1         | 0.08%   |
| Foxconn / Hon Hai                 | 1         | 0.08%   |
| ASUSTek Computer                  | 1         | 0.08%   |
| AboCom Systems                    | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 297       | 19.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 109       | 7.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 75        | 4.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 64        | 4.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 45        | 3%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 29        | 1.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 1.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 24        | 1.6%    |
| Intel Wireless 7265                                               | 23        | 1.53%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 22        | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 20        | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 17        | 1.13%   |
| Intel Wireless 7260                                               | 17        | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 1.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                     | 16        | 1.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 15        | 1%      |
| Intel Wi-Fi 6 AX200                                               | 15        | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 14        | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11        | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.73%   |
| Intel Wireless 8260                                               | 11        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 11        | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 9         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                   | 7         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 7         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 264       | 33.04%  |
| Qualcomm Atheros                | 255       | 31.91%  |
| Realtek Semiconductor           | 153       | 19.15%  |
| Broadcom                        | 65        | 8.14%   |
| MediaTek                        | 20        | 2.5%    |
| Broadcom Limited                | 12        | 1.5%    |
| Ralink Technology               | 9         | 1.13%   |
| Ralink                          | 7         | 0.88%   |
| TP-Link                         | 6         | 0.75%   |
| Qualcomm Atheros Communications | 6         | 0.75%   |
| Sierra Wireless                 | 1         | 0.13%   |
| AboCom Systems                  | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 75        | 9.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 64        | 7.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 45        | 5.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 32        | 3.98%   |
| Intel Wireless 8265 / 8275                                     | 29        | 3.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 24        | 2.98%   |
| Intel Wireless 7265                                            | 23        | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 22        | 2.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 2.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 2.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 20        | 2.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 17        | 2.11%   |
| Intel Wireless 7260                                            | 17        | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                  | 16        | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 1.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 1.86%   |
| Intel Wi-Fi 6 AX200                                            | 15        | 1.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 14        | 1.74%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 1.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 11        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 1.37%   |
| Intel Wireless 8260                                            | 11        | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 11        | 1.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 8         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                | 7         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7         | 0.87%   |
| Intel Wireless 3165                                            | 7         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 7         | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                | 6         | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 5         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 0.62%   |
| Realtek 802.11n WLAN Adapter                                   | 5         | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 0.62%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 420       | 61.31%  |
| Intel                            | 100       | 14.6%   |
| Qualcomm Atheros                 | 59        | 8.61%   |
| Broadcom                         | 27        | 3.94%   |
| Xiaomi                           | 13        | 1.9%    |
| Marvell Technology Group         | 9         | 1.31%   |
| Samsung Electronics              | 7         | 1.02%   |
| MediaTek                         | 7         | 1.02%   |
| OPPO Electronics                 | 6         | 0.88%   |
| Broadcom Limited                 | 6         | 0.88%   |
| JMicron Technology               | 5         | 0.73%   |
| TP-Link                          | 3         | 0.44%   |
| Silicon Integrated Systems [SiS] | 3         | 0.44%   |
| Attansic Technology              | 3         | 0.44%   |
| ASIX Electronics                 | 3         | 0.44%   |
| Qualcomm                         | 2         | 0.29%   |
| Nvidia                           | 2         | 0.29%   |
| ICS Advent                       | 2         | 0.29%   |
| Hewlett-Packard                  | 2         | 0.29%   |
| Sierra Wireless                  | 1         | 0.15%   |
| Lenovo                           | 1         | 0.15%   |
| Huawei Technologies              | 1         | 0.15%   |
| HTC (High Tech Computer)         | 1         | 0.15%   |
| Foxconn / Hon Hai                | 1         | 0.15%   |
| ASUSTek Computer                 | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 297       | 43.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 109       | 15.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 4.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 12        | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 1.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10        | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 1.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 0.87%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 6         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.73%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.73%   |
| MediaTek PRESIDENT_GOLD_10                                        | 5         | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.73%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 4         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3         | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.44%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.44%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.44%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 3         | 0.44%   |
| TP-Link USB 10/100 LAN                                            | 2         | 0.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.29%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.29%   |
| MediaTek BL8800Pro                                                | 2         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 766       | 53.94%  |
| Ethernet | 644       | 45.35%  |
| Modem    | 10        | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 667       | 86.62%  |
| Ethernet | 102       | 13.25%  |
| Modem    | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 602       | 77.08%  |
| 1     | 165       | 21.13%  |
| 0     | 11        | 1.41%   |
| 3     | 3         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 741       | 93.68%  |
| Yes  | 50        | 6.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 198       | 32.73%  |
| Realtek Semiconductor           | 97        | 16.03%  |
| Qualcomm Atheros Communications | 67        | 11.07%  |
| IMC Networks                    | 66        | 10.91%  |
| Lite-On Technology              | 55        | 9.09%   |
| Broadcom                        | 38        | 6.28%   |
| Foxconn / Hon Hai               | 24        | 3.97%   |
| Toshiba                         | 10        | 1.65%   |
| Cambridge Silicon Radio         | 10        | 1.65%   |
| Apple                           | 10        | 1.65%   |
| Dell                            | 7         | 1.16%   |
| Ralink                          | 5         | 0.83%   |
| Hewlett-Packard                 | 4         | 0.66%   |
| Foxconn International           | 4         | 0.66%   |
| Realtek                         | 3         | 0.5%    |
| Micro Star International        | 2         | 0.33%   |
| MediaTek                        | 2         | 0.33%   |
| ASUSTek Computer                | 2         | 0.33%   |
| Chicony Electronics             | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 84        | 13.88%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 52        | 8.6%    |
| Realtek Bluetooth Radio                             | 49        | 8.1%    |
| IMC Networks Bluetooth Device                       | 42        | 6.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 32        | 5.29%   |
| Intel AX201 Bluetooth                               | 24        | 3.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 3.8%    |
| Lite-On Bluetooth Device                            | 20        | 3.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 2.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.64%   |
| Intel AX200 Bluetooth                               | 15        | 2.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.98%   |
| Realtek RTL8821A Bluetooth                          | 10        | 1.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 1.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 1.65%   |
| Realtek RTL8723B Bluetooth                          | 9         | 1.49%   |
| Lite-On Wireless_Device                             | 9         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.32%   |
| IMC Networks Bluetooth Radio                        | 8         | 1.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.99%   |
| Lite-On Atheros Bluetooth                           | 6         | 0.99%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 6         | 0.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 0.99%   |
| Apple Bluetooth Host Controller                     | 6         | 0.99%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.83%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.66%   |
| Intel Bluetooth Device                              | 4         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.66%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.66%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.5%    |
| Intel AX210 Bluetooth                               | 3         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.5%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.5%    |
| Foxconn / Hon Hai Acer Module                       | 3         | 0.5%    |
| Broadcom HP Portable SoftSailing                    | 3         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 571       | 66.71%  |
| AMD                              | 199       | 23.25%  |
| Nvidia                           | 62        | 7.24%   |
| Silicon Integrated Systems [SiS] | 4         | 0.47%   |
| Samson Technologies              | 3         | 0.35%   |
| JMTek                            | 3         | 0.35%   |
| Generalplus Technology           | 3         | 0.35%   |
| Samsung Electronics              | 2         | 0.23%   |
| C-Media Electronics              | 2         | 0.23%   |
| SAVITECH                         | 1         | 0.12%   |
| Logitech                         | 1         | 0.12%   |
| FDUCE PRO AUDIO MADE             | 1         | 0.12%   |
| Cooler Master                    | 1         | 0.12%   |
| BR25                             | 1         | 0.12%   |
| Barco Display Systems            | 1         | 0.12%   |
| ASUSTek Computer                 | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 91        | 8.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 85        | 7.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 77        | 6.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 56        | 4.94%   |
| AMD FCH Azalia Controller                                                                         | 54        | 4.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 44        | 3.88%   |
| Intel 8 Series HD Audio Controller                                                                | 44        | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 40        | 3.53%   |
| AMD Kabini HDMI/DP Audio                                                                          | 40        | 3.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 40        | 3.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 39        | 3.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 37        | 3.27%   |
| Intel Broadwell-U Audio Controller                                                                | 37        | 3.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 37        | 3.27%   |
| AMD High Definition Audio Controller                                                              | 32        | 2.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 1.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 19        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 1.15%   |
| AMD Wrestler HDMI Audio                                                                           | 13        | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 12        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.06%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.71%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.53%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 6         | 0.53%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 181       | 30.83%  |
| SK hynix            | 121       | 20.61%  |
| Micron Technology   | 64        | 10.9%   |
| Kingston            | 50        | 8.52%   |
| Unknown             | 37        | 6.3%    |
| Team                | 19        | 3.24%   |
| Corsair             | 18        | 3.07%   |
| Ramaxel Technology  | 17        | 2.9%    |
| V-GeN               | 16        | 2.73%   |
| Elpida              | 12        | 2.04%   |
| Nanya Technology    | 9         | 1.53%   |
| A-DATA Technology   | 7         | 1.19%   |
| Unknown (ABCD)      | 6         | 1.02%   |
| Apacer              | 4         | 0.68%   |
| Transcend           | 3         | 0.51%   |
| Visipro             | 2         | 0.34%   |
| Crucial             | 2         | 0.34%   |
| ASint Technology    | 2         | 0.34%   |
| A Force             | 2         | 0.34%   |
| Unknown             | 2         | 0.34%   |
| Unknown (8A02)      | 1         | 0.17%   |
| Strontium           | 1         | 0.17%   |
| Silicon Power       | 1         | 0.17%   |
| SHARETRONIC         | 1         | 0.17%   |
| Qumo                | 1         | 0.17%   |
| Patriot             | 1         | 0.17%   |
| Lexar               | 1         | 0.17%   |
| Kingmax             | 1         | 0.17%   |
| GOODRAM             | 1         | 0.17%   |
| Goldkey             | 1         | 0.17%   |
| Foxline             | 1         | 0.17%   |
| ff                  | 1         | 0.17%   |
| 4ea5                | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 2.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.73%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 1.73%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 1.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.42%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 9         | 1.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 8         | 1.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.26%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 8         | 1.26%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 6         | 0.94%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 6         | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.94%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.94%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 5         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.79%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.79%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s             | 5         | 0.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.63%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 4         | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.63%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.63%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.63%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 4         | 0.63%   |
| Kingston RAM 9905625-004.A03LF 8GB SODIMM DDR4 3200MT/s          | 4         | 0.63%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.63%   |
| V-GeN RAM D4R8GS24A8R 8GB SODIMM DDR4 2400MT/s                   | 3         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 202       | 44.69%  |
| DDR4    | 199       | 44.03%  |
| LPDDR4  | 19        | 4.2%    |
| DDR2    | 13        | 2.88%   |
| SDRAM   | 7         | 1.55%   |
| LPDDR3  | 7         | 1.55%   |
| LPDDR5  | 3         | 0.66%   |
| DRAM    | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 424       | 92.37%  |
| Row Of Chips | 29        | 6.32%   |
| Chip         | 5         | 1.09%   |
| Unknown      | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 227       | 44.16%  |
| 8192  | 169       | 32.88%  |
| 2048  | 74        | 14.4%   |
| 16384 | 25        | 4.86%   |
| 1024  | 10        | 1.95%   |
| 32768 | 8         | 1.56%   |
| 512   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 151       | 28.76%  |
| 2667    | 91        | 17.33%  |
| 3200    | 71        | 13.52%  |
| 2400    | 51        | 9.71%   |
| 1334    | 29        | 5.52%   |
| 2133    | 26        | 4.95%   |
| 1333    | 23        | 4.38%   |
| 3266    | 13        | 2.48%   |
| 1067    | 11        | 2.1%    |
| 800     | 7         | 1.33%   |
| Unknown | 7         | 1.33%   |
| 8400    | 6         | 1.14%   |
| 4266    | 6         | 1.14%   |
| 667     | 6         | 1.14%   |
| 4267    | 5         | 0.95%   |
| 1867    | 5         | 0.95%   |
| 4199    | 4         | 0.76%   |
| 6400    | 3         | 0.57%   |
| 533     | 3         | 0.57%   |
| 2048    | 2         | 0.38%   |
| 1866    | 1         | 0.19%   |
| 1776    | 1         | 0.19%   |
| 1066    | 1         | 0.19%   |
| 975     | 1         | 0.19%   |
| 333     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 8         | 61.54%  |
| Canon              | 3         | 23.08%  |
| Brother Industries | 2         | 15.38%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L310 Series  | 2         | 15.38%  |
| Seiko Epson L222 Series  | 2         | 15.38%  |
| Canon iP2700 series      | 2         | 15.38%  |
| Brother DCP-T300         | 2         | 15.38%  |
| Seiko Epson L405 Series  | 1         | 7.69%   |
| Seiko Epson L355 Series  | 1         | 7.69%   |
| Seiko Epson L3210 Series | 1         | 7.69%   |
| Seiko Epson L120 Series  | 1         | 7.69%   |
| Canon LiDE 300           | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 199       | 28.59%  |
| IMC Networks                           | 99        | 14.22%  |
| Realtek Semiconductor                  | 67        | 9.63%   |
| Acer                                   | 43        | 6.18%   |
| Sunplus Innovation Technology          | 38        | 5.46%   |
| Quanta                                 | 38        | 5.46%   |
| Syntek                                 | 33        | 4.74%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.17%   |
| Microdia                               | 27        | 3.88%   |
| Alcor Micro                            | 21        | 3.02%   |
| Suyin                                  | 20        | 2.87%   |
| Bison Electronics                      | 19        | 2.73%   |
| Lite-On Technology                     | 9         | 1.29%   |
| Apple                                  | 7         | 1.01%   |
| Luxvisions Innotech Limited            | 6         | 0.86%   |
| Silicon Motion                         | 5         | 0.72%   |
| Ricoh                                  | 5         | 0.72%   |
| Importek                               | 5         | 0.72%   |
| Sonix Technology                       | 3         | 0.43%   |
| Lenovo                                 | 3         | 0.43%   |
| Primax Electronics                     | 2         | 0.29%   |
| Jieli Technology                       | 2         | 0.29%   |
| ALi                                    | 2         | 0.29%   |
| Unknown                                | 2         | 0.29%   |
| Tripath Technology                     | 1         | 0.14%   |
| Sunplus Technology                     | 1         | 0.14%   |
| Pixart Imaging                         | 1         | 0.14%   |
| OPPO Electronics                       | 1         | 0.14%   |
| Omnivision                             | 1         | 0.14%   |
| Logitech                               | 1         | 0.14%   |
| Huawei Technologies                    | 1         | 0.14%   |
| Genesys Logic                          | 1         | 0.14%   |
| GEMBIRD                                | 1         | 0.14%   |
| eMPIA Technology                       | 1         | 0.14%   |
| DigiTech                               | 1         | 0.14%   |
| 2M UVC CAMERA                          | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                               | 31        | 4.44%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 29        | 4.15%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 26        | 3.72%   |
| Chicony Integrated Camera                                       | 26        | 3.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 20        | 2.87%   |
| Syntek Integrated Camera                                        | 19        | 2.72%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 17        | 2.44%   |
| Chicony USB2.0 HD UVC WebCam                                    | 16        | 2.29%   |
| Acer Lenovo EasyCamera                                          | 16        | 2.29%   |
| Microdia Integrated_Webcam_HD                                   | 12        | 1.72%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.72%   |
| IMC Networks Integrated Camera                                  | 12        | 1.72%   |
| Chicony HP TrueVision HD Camera                                 | 12        | 1.72%   |
| Realtek Integrated_Webcam_HD                                    | 11        | 1.58%   |
| IMC Networks EasyCamera                                         | 11        | 1.58%   |
| Quanta HD User Facing                                           | 10        | 1.43%   |
| Sunplus Asus Webcam                                             | 9         | 1.29%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.29%   |
| Syntek EasyCamera                                               | 8         | 1.15%   |
| Realtek USB Camera                                              | 8         | 1.15%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 1%      |
| Microdia Integrated Webcam                                      | 7         | 1%      |
| Chicony HP Truevision HD                                        | 7         | 1%      |
| Chicony EasyCamera                                              | 7         | 1%      |
| Alcor Micro Asus Integrated Webcam                              | 7         | 1%      |
| Acer Integrated Camera                                          | 7         | 1%      |
| Suyin 1.3M HD WebCam                                            | 6         | 0.86%   |
| Sunplus Integrated_Webcam_HD                                    | 6         | 0.86%   |
| Realtek USB2.0 HD UVC WebCam                                    | 6         | 0.86%   |
| Quanta VGA WebCam                                               | 6         | 0.86%   |
| Chicony HD User Facing                                          | 6         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 6         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 6         | 0.86%   |
| Bison HD Webcam                                                 | 6         | 0.86%   |
| Syntek Lenovo EasyCamera                                        | 5         | 0.72%   |
| Sunplus HD Webcam                                               | 5         | 0.72%   |
| Quanta HD WebCam                                                | 5         | 0.72%   |
| Lite-On Integrated Camera                                       | 5         | 0.72%   |
| Chicony TOSHIBA Web Camera - HD                                 | 5         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 37        | 34.58%  |
| Elan Microelectronics      | 22        | 20.56%  |
| Synaptics                  | 15        | 14.02%  |
| LighTuning Technology      | 11        | 10.28%  |
| Shenzhen Goodix Technology | 9         | 8.41%   |
| AuthenTec                  | 6         | 5.61%   |
| Upek                       | 5         | 4.67%   |
| STMicroelectronics         | 2         | 1.87%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                           | 11        | 10.28%  |
| LighTuning EgisTec Touch Fingerprint Sensor                | 10        | 9.35%   |
| Elan ELAN:Fingerprint                                      | 10        | 9.35%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 8         | 7.48%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 6.54%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 6         | 5.61%   |
| Shenzhen Goodix  FingerPrint Device                        | 6         | 5.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 5         | 4.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 4.67%   |
| Validity Sensors VFS Fingerprint sensor                    | 4         | 3.74%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 4         | 3.74%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 2.8%    |
| Synaptics  WBDI                                            | 3         | 2.8%    |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 2.8%    |
| AuthenTec AES1600                                          | 3         | 2.8%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 1.87%   |
| Validity Sensors VFS491                                    | 2         | 1.87%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 1.87%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 1.87%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 1.87%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 0.93%   |
| Validity Sensors Synaptics WBDI                            | 1         | 0.93%   |
| Synaptics WBDI                                             | 1         | 0.93%   |
| Synaptics UWP WBDI                                         | 1         | 0.93%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 0.93%   |
| Elan fingerprint sensor [FeinTech FPS00200]                | 1         | 0.93%   |
| AuthenTec AES2810                                          | 1         | 0.93%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 51.72%  |
| O2 Micro    | 5         | 17.24%  |
| Upek        | 4         | 13.79%  |
| Alcor Micro | 3         | 10.34%  |
| Lenovo      | 2         | 6.9%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 27.59%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 17.24%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 13.79%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 13.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 10.34%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.9%    |
| Broadcom 58200                                                               | 2         | 6.9%    |
| Broadcom 5880                                                                | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 540       | 68.01%  |
| 1     | 196       | 24.69%  |
| 2     | 51        | 6.42%   |
| 3     | 6         | 0.76%   |
| 6     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 106       | 34.98%  |
| Graphics card            | 72        | 23.76%  |
| Net/wireless             | 30        | 9.9%    |
| Chipcard                 | 28        | 9.24%   |
| Multimedia controller    | 20        | 6.6%    |
| Bluetooth                | 18        | 5.94%   |
| Camera                   | 7         | 2.31%   |
| Net/ethernet             | 5         | 1.65%   |
| Communication controller | 5         | 1.65%   |
| Storage                  | 4         | 1.32%   |
| Sound                    | 2         | 0.66%   |
| Flash memory             | 2         | 0.66%   |
| Card reader              | 2         | 0.66%   |
| Video                    | 1         | 0.33%   |
| Network                  | 1         | 0.33%   |

