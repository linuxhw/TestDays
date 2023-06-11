Linux in Peru - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Peru.

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

Total: 339

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | ROG Zephyrus G14 GA401QC... | [57f37d5836](https://linux-hardware.org/?probe=57f37d5836) | Jun 10, 2023 |
| Lenovo     | IdeaPad L340-15API 81LW     | [1794287cf0](https://linux-hardware.org/?probe=1794287cf0) | Jun 09, 2023 |
| HP         | 14                          | [1540a787fb](https://linux-hardware.org/?probe=1540a787fb) | Jun 09, 2023 |
| HP         | 14                          | [1404218cab](https://linux-hardware.org/?probe=1404218cab) | Jun 09, 2023 |
| Apple      | MacBookPro9,2               | [c22081b097](https://linux-hardware.org/?probe=c22081b097) | Jun 09, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [97d002b53a](https://linux-hardware.org/?probe=97d002b53a) | Jun 08, 2023 |
| Lenovo     | Legion S7 15ACH6 82K8       | [8f160a999a](https://linux-hardware.org/?probe=8f160a999a) | Jun 08, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| Apple      | MacBookPro9,2               | [8d70c1dd42](https://linux-hardware.org/?probe=8d70c1dd42) | Jun 07, 2023 |
| Toshiba    | Satellite L45-B             | [a1bcda2245](https://linux-hardware.org/?probe=a1bcda2245) | Jun 05, 2023 |
| ASUSTek    | TUF Gaming FX505DT_FX505... | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP         | 14                          | [977d26c9b5](https://linux-hardware.org/?probe=977d26c9b5) | May 29, 2023 |
| Lenovo     | G400 20235                  | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP         | Laptop 15-dy5xxx            | [3ab3a101e8](https://linux-hardware.org/?probe=3ab3a101e8) | May 21, 2023 |
| Sony       | VPCEL36FJ                   | [c372bac204](https://linux-hardware.org/?probe=c372bac204) | May 21, 2023 |
| HP         | Victus by Gaming Laptop ... | [8f2ccf9c6d](https://linux-hardware.org/?probe=8f2ccf9c6d) | May 21, 2023 |
| Lenovo     | ThinkPad L460 20FVS3JK00    | [c812ee44af](https://linux-hardware.org/?probe=c812ee44af) | May 18, 2023 |
| Dell       | Latitude E7450              | [cb96fcfaff](https://linux-hardware.org/?probe=cb96fcfaff) | May 12, 2023 |
| Chuwi      | GemiBook Pro                | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Apple      | MacBookPro11,5              | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| MSI        | PS42 Modern 8RA             | [8371e35044](https://linux-hardware.org/?probe=8371e35044) | May 08, 2023 |
| Dell       | G5 5505                     | [94e01ce854](https://linux-hardware.org/?probe=94e01ce854) | May 07, 2023 |
| Dell       | G5 5505                     | [b484646926](https://linux-hardware.org/?probe=b484646926) | May 07, 2023 |
| HP         | Pavilion 11                 | [696ac990d2](https://linux-hardware.org/?probe=696ac990d2) | May 07, 2023 |
| HP         | Pavilion g4                 | [5e3bd3ea22](https://linux-hardware.org/?probe=5e3bd3ea22) | May 06, 2023 |
| ASUSTek    | ROG Strix G513RC_G513RC     | [d1dc588f69](https://linux-hardware.org/?probe=d1dc588f69) | May 05, 2023 |
| ASUSTek    | ROG Strix G513RC_G513RC     | [9d3ea79ded](https://linux-hardware.org/?probe=9d3ea79ded) | May 04, 2023 |
| HP         | Laptop 15-ef2xxx            | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| Chuwi      | GemiBook Pro                | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| Toshiba    | Satellite C45-A             | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| eMachines  | D725                        | [f3cdf26e60](https://linux-hardware.org/?probe=f3cdf26e60) | Apr 04, 2023 |
| HP         | 250 G7 Notebook PC          | [3995abb8b8](https://linux-hardware.org/?probe=3995abb8b8) | Apr 04, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| Lenovo     | IdeaPad Gaming 3 15ARH7 ... | [a6c0f30f2f](https://linux-hardware.org/?probe=a6c0f30f2f) | Apr 03, 2023 |
| ASUSTek    | T100TA                      | [5be9a0230e](https://linux-hardware.org/?probe=5be9a0230e) | Apr 01, 2023 |
| ASUSTek    | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Acer       | Aspire ES1-531              | [aedba72f70](https://linux-hardware.org/?probe=aedba72f70) | Mar 31, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [0d7e6b4a80](https://linux-hardware.org/?probe=0d7e6b4a80) | Mar 12, 2023 |
| Lenovo     | ThinkPad T450 20BUA05K00    | [a496755d7a](https://linux-hardware.org/?probe=a496755d7a) | Mar 10, 2023 |
| HP         | Laptop 15-gw0xxx            | [e05606240c](https://linux-hardware.org/?probe=e05606240c) | Feb 28, 2023 |
| HP         | EliteBook 8540p             | [9f543932d2](https://linux-hardware.org/?probe=9f543932d2) | Feb 26, 2023 |
| HP         | Notebook                    | [b929a8ff3c](https://linux-hardware.org/?probe=b929a8ff3c) | Feb 24, 2023 |
| MSI        | Modern 15 A5M               | [f6c80ff7a9](https://linux-hardware.org/?probe=f6c80ff7a9) | Feb 20, 2023 |
| HP         | 14                          | [0244e880e1](https://linux-hardware.org/?probe=0244e880e1) | Feb 19, 2023 |
| HP         | Laptop 15-gw0xxx            | [4bcd17d5a6](https://linux-hardware.org/?probe=4bcd17d5a6) | Feb 17, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Dell       | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo     | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Lenovo     | ThinkPad L15 Gen 1 20U3S... | [ad0b876d84](https://linux-hardware.org/?probe=ad0b876d84) | Feb 10, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [8d0a0a0422](https://linux-hardware.org/?probe=8d0a0a0422) | Feb 06, 2023 |
| HP         | Pavilion Laptop 15-cc1xx    | [d693442f27](https://linux-hardware.org/?probe=d693442f27) | Feb 03, 2023 |
| Lenovo     | IdeaPad 320-15IKB 80XL      | [5dbc5260b2](https://linux-hardware.org/?probe=5dbc5260b2) | Jan 29, 2023 |
| Lenovo     | IdeaPad 320-15IKB 80XL      | [7c0c804a3e](https://linux-hardware.org/?probe=7c0c804a3e) | Jan 29, 2023 |
| HP         | ProBook 640 G2              | [7b08eeb50c](https://linux-hardware.org/?probe=7b08eeb50c) | Jan 29, 2023 |
| HP         | Compaq Presario C700        | [d2ec58874c](https://linux-hardware.org/?probe=d2ec58874c) | Jan 21, 2023 |
| Lenovo     | IdeaPad 3 15IML05 81WR      | [07b3eb6453](https://linux-hardware.org/?probe=07b3eb6453) | Jan 20, 2023 |
| Toshiba    | Satellite C45-A             | [16f5bae11f](https://linux-hardware.org/?probe=16f5bae11f) | Jan 20, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [c16356f056](https://linux-hardware.org/?probe=c16356f056) | Jan 17, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [70b8007dcc](https://linux-hardware.org/?probe=70b8007dcc) | Jan 17, 2023 |
| HP         | ProBook 655 G1              | [1e3f42b7d1](https://linux-hardware.org/?probe=1e3f42b7d1) | Jan 10, 2023 |
| Toshiba    | Satellite P300              | [d35d765c2f](https://linux-hardware.org/?probe=d35d765c2f) | Jan 09, 2023 |
| Acer       | Aspire VN7-571G             | [88e5718807](https://linux-hardware.org/?probe=88e5718807) | Jan 03, 2023 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| HP         | Laptop 15-dy5xxx            | [d7daff3ed1](https://linux-hardware.org/?probe=d7daff3ed1) | Dec 27, 2022 |
| HP         | Compaq Mini CQ10-100        | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| HP         | 255 G8 Notebook PC          | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Lenovo     | IdeaPad U400 099342G        | [9ecbde32ab](https://linux-hardware.org/?probe=9ecbde32ab) | Dec 06, 2022 |
| HUAWEI     | CREM-WXX9                   | [2436f4cf5e](https://linux-hardware.org/?probe=2436f4cf5e) | Nov 30, 2022 |
| HP         | 255 G7 Notebook PC          | [0bd83a29f4](https://linux-hardware.org/?probe=0bd83a29f4) | Nov 29, 2022 |
| HP         | 250 G7 Notebook PC          | [10b5bb5eab](https://linux-hardware.org/?probe=10b5bb5eab) | Nov 17, 2022 |
| HP         | 250 G7 Notebook PC          | [c765249482](https://linux-hardware.org/?probe=c765249482) | Nov 17, 2022 |
| Lenovo     | Legion 7 16ITHg6 82K6       | [eebc3537d1](https://linux-hardware.org/?probe=eebc3537d1) | Nov 09, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| HP         | Pavilion Laptop 15-cc1xx    | [b97ba1d3f0](https://linux-hardware.org/?probe=b97ba1d3f0) | Nov 07, 2022 |
| Lenovo     | Legion 7 16ITHg6 82K6       | [88a69a9a20](https://linux-hardware.org/?probe=88a69a9a20) | Nov 05, 2022 |
| Dell       | Latitude E5470              | [4de6b7bdb8](https://linux-hardware.org/?probe=4de6b7bdb8) | Nov 04, 2022 |
| Dell       | Latitude 5420               | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Acer       | Aspire 5745                 | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| HP         | Pavilion Laptop 15-cc1xx    | [a977f9c3e9](https://linux-hardware.org/?probe=a977f9c3e9) | Oct 26, 2022 |
| ASUSTek    | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| ADVANCE    | PS5077                      | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE    | PS5077                      | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Lenovo     | ThinkBook 15-IIL 20SM       | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| Dell       | Latitude E5470              | [11ad7cd084](https://linux-hardware.org/?probe=11ad7cd084) | Oct 20, 2022 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop M350... | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| HUAWEI     | BOHB-WAX9                   | [6fec6456bc](https://linux-hardware.org/?probe=6fec6456bc) | Oct 07, 2022 |
| HUAWEI     | BOHB-WAX9                   | [fb954f84b4](https://linux-hardware.org/?probe=fb954f84b4) | Oct 07, 2022 |
| HUAWEI     | BOHB-WAX9                   | [d56cf9868c](https://linux-hardware.org/?probe=d56cf9868c) | Oct 07, 2022 |
| Lenovo     | IdeaPad 320-15ISK 80XH      | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| ASUSTek    | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| HP         | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Lenovo     | V330-15IKB 81AX             | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [2267f01dee](https://linux-hardware.org/?probe=2267f01dee) | Aug 27, 2022 |
| Lenovo     | G570 4334                   | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| HP         | 255 G7 Notebook PC          | [c001653a5a](https://linux-hardware.org/?probe=c001653a5a) | Aug 20, 2022 |
| Dell       | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Dell       | Latitude E6430              | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell       | Latitude E6430              | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo     | ThinkPad T60 1953D9U        | [1c31cb6b44](https://linux-hardware.org/?probe=1c31cb6b44) | Jul 21, 2022 |
| Acer       | Aspire A515-51G             | [4414dd4c1b](https://linux-hardware.org/?probe=4414dd4c1b) | Jul 19, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [b511d2883b](https://linux-hardware.org/?probe=b511d2883b) | Jul 16, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [8c160ae192](https://linux-hardware.org/?probe=8c160ae192) | Jul 12, 2022 |
| Acer       | Aspire ES1-512              | [aa2ad87835](https://linux-hardware.org/?probe=aa2ad87835) | Jul 08, 2022 |
| Acer       | Aspire V3-471               | [75664ddf0f](https://linux-hardware.org/?probe=75664ddf0f) | Jul 07, 2022 |
| ASUSTek    | S550CA                      | [8ed63bbdfd](https://linux-hardware.org/?probe=8ed63bbdfd) | Jul 01, 2022 |
| MSI        | GL65 Leopard 10SEK          | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [01fbfc98f8](https://linux-hardware.org/?probe=01fbfc98f8) | Jun 27, 2022 |
| Lenovo     | V15-IIL 82C5                | [1023ca742e](https://linux-hardware.org/?probe=1023ca742e) | Jun 27, 2022 |
| HP         | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell       | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Dell       | Inspiron 15 7000 Gaming     | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| HP         | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell       | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| ASUSTek    | S550CA                      | [c7c236e5a1](https://linux-hardware.org/?probe=c7c236e5a1) | Jun 23, 2022 |
| Dell       | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| Lenovo     | V15-IIL 82C5                | [47f52294bb](https://linux-hardware.org/?probe=47f52294bb) | Jun 14, 2022 |
| HUAWEI     | NBLB-WAX9N                  | [e24239a843](https://linux-hardware.org/?probe=e24239a843) | Jun 09, 2022 |
| ASUSTek    | S550CA                      | [9ba4a449c6](https://linux-hardware.org/?probe=9ba4a449c6) | Jun 09, 2022 |
| Dell       | Latitude E7450              | [29219339b2](https://linux-hardware.org/?probe=29219339b2) | Jun 05, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| ASUSTek    | X555UQ                      | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| Lenovo     | ThinkPad P52 20MAS3X200     | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Acer       | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| Lenovo     | ThinkPad P52 20MAS3X200     | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Dell       | Vostro 3405                 | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| ASUSTek    | ROG Strix G513QY_G513QY     | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Dell       | Vostro 3405                 | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| Lenovo     | Legion 5 17ITH6H 82JM       | [451c9ea765](https://linux-hardware.org/?probe=451c9ea765) | May 08, 2022 |
| Lenovo     | ThinkPad T530 24296G9       | [934e13a24c](https://linux-hardware.org/?probe=934e13a24c) | May 08, 2022 |
| HP         | ZBook 15                    | [bd8e2ed626](https://linux-hardware.org/?probe=bd8e2ed626) | May 07, 2022 |
| Compal     | QAQXX                       | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| HP         | Laptop 15-ef1xxx            | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| Lenovo     | V310-15ISK 80SY             | [1a791b0fd5](https://linux-hardware.org/?probe=1a791b0fd5) | May 04, 2022 |
| Lenovo     | V310-15ISK 80SY             | [3846d07c7f](https://linux-hardware.org/?probe=3846d07c7f) | May 04, 2022 |
| HP         | ENVY dv6                    | [23ad3290c2](https://linux-hardware.org/?probe=23ad3290c2) | May 03, 2022 |
| Lenovo     | ThinkPad L15 Gen 1 20U3S... | [74eec8c684](https://linux-hardware.org/?probe=74eec8c684) | May 01, 2022 |
| Lenovo     | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Lenovo     | IdeaPad S145-15IWL 81MV     | [05db30a69b](https://linux-hardware.org/?probe=05db30a69b) | Apr 30, 2022 |
| Acer       | Aspire E5-571               | [ebdc8b1380](https://linux-hardware.org/?probe=ebdc8b1380) | Apr 30, 2022 |
| Acer       | Aspire A315-23              | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer       | Aspire A315-23              | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| ASUSTek    | X556UR                      | [3f920954f7](https://linux-hardware.org/?probe=3f920954f7) | Apr 30, 2022 |
| HP         | Pavilion Sleekbook 15       | [0003f9342e](https://linux-hardware.org/?probe=0003f9342e) | Apr 30, 2022 |
| HP         | Laptop 14-dq1xxx            | [7c9e2f4d8f](https://linux-hardware.org/?probe=7c9e2f4d8f) | Apr 30, 2022 |
| HP         | Notebook                    | [94f0ce7610](https://linux-hardware.org/?probe=94f0ce7610) | Apr 26, 2022 |
| Dell       | Vostro 3405                 | [2d5bae0eeb](https://linux-hardware.org/?probe=2d5bae0eeb) | Apr 24, 2022 |
| HP         | Pavilion Laptop 15-cw1xx... | [a33d067e62](https://linux-hardware.org/?probe=a33d067e62) | Apr 18, 2022 |
| HP         | Compaq Mini CQ10-100        | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| Dell       | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| HP         | ZBook Firefly 15 G7 Mobi... | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| Lenovo     | ThinkPad X140e 20BLA00C0... | [9cad677222](https://linux-hardware.org/?probe=9cad677222) | Mar 24, 2022 |
| HP         | Stream Laptop 14-ax0XX      | [9b99145008](https://linux-hardware.org/?probe=9b99145008) | Mar 21, 2022 |
| HP         | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP         | 340 G2                      | [c4f663b37b](https://linux-hardware.org/?probe=c4f663b37b) | Mar 04, 2022 |
| HP         | Pavilion Laptop 15-cd0xx    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Acer       | Aspire 4750                 | [b8f02b07fb](https://linux-hardware.org/?probe=b8f02b07fb) | Feb 18, 2022 |
| Acer       | Aspire 4750                 | [3269f565c4](https://linux-hardware.org/?probe=3269f565c4) | Feb 18, 2022 |
| HP         | 240 G7 Notebook PC          | [03f63a3789](https://linux-hardware.org/?probe=03f63a3789) | Feb 09, 2022 |
| efirstview | v01099                      | [ed22d3c2b6](https://linux-hardware.org/?probe=ed22d3c2b6) | Feb 04, 2022 |
| Toshiba    | Satellite C645              | [d552c9b132](https://linux-hardware.org/?probe=d552c9b132) | Feb 04, 2022 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [b7cb93aff2](https://linux-hardware.org/?probe=b7cb93aff2) | Jan 25, 2022 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo     | IdeaPad S340-15API 81NC     | [1f065ea4dd](https://linux-hardware.org/?probe=1f065ea4dd) | Jan 12, 2022 |
| Sony       | VGN-FW56M                   | [9fb3fa0f32](https://linux-hardware.org/?probe=9fb3fa0f32) | Jan 09, 2022 |
| Lenovo     | IdeaPad S540-14API 81NH     | [eb23bd590c](https://linux-hardware.org/?probe=eb23bd590c) | Jan 07, 2022 |
| Toshiba    | Satellite E205              | [92431da366](https://linux-hardware.org/?probe=92431da366) | Dec 24, 2021 |
| Lenovo     | G400 20235                  | [c2bb5d0010](https://linux-hardware.org/?probe=c2bb5d0010) | Dec 18, 2021 |
| ASUSTek    | ASUS TUF Gaming A15 FA50... | [020b7460a1](https://linux-hardware.org/?probe=020b7460a1) | Dec 11, 2021 |
| HP         | Pavilion Gaming Laptop 1... | [fefa594281](https://linux-hardware.org/?probe=fefa594281) | Dec 10, 2021 |
| HP         | 250 G5 Notebook PC          | [3cd230924a](https://linux-hardware.org/?probe=3cd230924a) | Dec 04, 2021 |
| Lenovo     | ThinkPad X1 Carbon Gen 8... | [54f954491a](https://linux-hardware.org/?probe=54f954491a) | Nov 21, 2021 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [e085c7e42a](https://linux-hardware.org/?probe=e085c7e42a) | Nov 09, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Dell       | XPS 13 9360                 | [61db5bc9b5](https://linux-hardware.org/?probe=61db5bc9b5) | Nov 04, 2021 |
| Lenovo     | ThinkPad E15 Gen 2 20TES... | [df2d173d7c](https://linux-hardware.org/?probe=df2d173d7c) | Nov 01, 2021 |
| Lenovo     | V14-ARE 82DQ                | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP         | Laptop 15-db0xxx            | [f4d2f1104e](https://linux-hardware.org/?probe=f4d2f1104e) | Oct 28, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [87d959803d](https://linux-hardware.org/?probe=87d959803d) | Oct 15, 2021 |
| Dell       | XPS 13 9360                 | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HP         | Notebook                    | [36fd24364d](https://linux-hardware.org/?probe=36fd24364d) | Sep 24, 2021 |
| Advance    | AN-5431                     | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| HP         | Notebook                    | [2a564798fd](https://linux-hardware.org/?probe=2a564798fd) | Sep 11, 2021 |
| Lenovo     | ThinkPad T440 20B7A08500    | [b7e859020c](https://linux-hardware.org/?probe=b7e859020c) | Aug 26, 2021 |
| HP         | 450                         | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| Chuwi      | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [392df1ef2b](https://linux-hardware.org/?probe=392df1ef2b) | Aug 13, 2021 |
| ASUSTek    | X542UQ                      | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| Advance    | AN-5431                     | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| Lenovo     | ThinkPad T580 20LAS0XD00    | [36f1b3eb94](https://linux-hardware.org/?probe=36f1b3eb94) | Jul 31, 2021 |
| Dell       | Latitude E5540              | [44b8f3a781](https://linux-hardware.org/?probe=44b8f3a781) | Jul 23, 2021 |
| HP         | Pavilion dv6                | [3e69858907](https://linux-hardware.org/?probe=3e69858907) | Jul 09, 2021 |
| Lenovo     | ThinkPad L460 20FVA0G400    | [378021c178](https://linux-hardware.org/?probe=378021c178) | Jul 06, 2021 |
| ASUSTek    | ROG Strix G532LW_G532LWI    | [b36be47753](https://linux-hardware.org/?probe=b36be47753) | Jun 27, 2021 |
| HP         | Pavilion Notebook           | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Lenovo     | IdeaPad S540-14API 81NH     | [003f0d1c2a](https://linux-hardware.org/?probe=003f0d1c2a) | Jun 21, 2021 |
| ASUSTek    | ROG Strix G532LW_G532LWI    | [1344b72b26](https://linux-hardware.org/?probe=1344b72b26) | Jun 20, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [6670e1c145](https://linux-hardware.org/?probe=6670e1c145) | Jun 01, 2021 |
| ASUSTek    | VivoBook_ASUSLaptop X509... | [af8045a7b3](https://linux-hardware.org/?probe=af8045a7b3) | May 31, 2021 |
| ASUSTek    | X550LD                      | [89bed4ca0a](https://linux-hardware.org/?probe=89bed4ca0a) | May 28, 2021 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [ee9233be38](https://linux-hardware.org/?probe=ee9233be38) | May 26, 2021 |
| HP         | ProBook 450 G1              | [6d64546949](https://linux-hardware.org/?probe=6d64546949) | May 23, 2021 |
| HP         | ProBook 450 G1              | [1b52ac3979](https://linux-hardware.org/?probe=1b52ac3979) | May 23, 2021 |
| HP         | 240 G7                      | [9fff9c48ab](https://linux-hardware.org/?probe=9fff9c48ab) | May 16, 2021 |
| ASUSTek    | X550LC                      | [23a000c11b](https://linux-hardware.org/?probe=23a000c11b) | May 05, 2021 |
| ASUSTek    | X550LC                      | [d50b1f77d7](https://linux-hardware.org/?probe=d50b1f77d7) | May 05, 2021 |
| Toshiba    | Satellite L35               | [1abffa2c4c](https://linux-hardware.org/?probe=1abffa2c4c) | Apr 16, 2021 |
| HP         | 14                          | [9d65301476](https://linux-hardware.org/?probe=9d65301476) | Apr 09, 2021 |
| Lenovo     | IdeaPad S145-15IWL 81MV     | [14e58f968d](https://linux-hardware.org/?probe=14e58f968d) | Apr 07, 2021 |
| Toshiba    | Satellite C655D             | [1959880e8f](https://linux-hardware.org/?probe=1959880e8f) | Mar 28, 2021 |
| Dell       | Latitude E5470              | [6ade45ee37](https://linux-hardware.org/?probe=6ade45ee37) | Mar 21, 2021 |
| Lenovo     | V310-14ISK 80SX             | [529bb59872](https://linux-hardware.org/?probe=529bb59872) | Mar 12, 2021 |
| Toshiba    | Satellite A665              | [23143ad7ae](https://linux-hardware.org/?probe=23143ad7ae) | Mar 07, 2021 |
| Lenovo     | IdeaPad S145-14IWL 81MU     | [b2e0735680](https://linux-hardware.org/?probe=b2e0735680) | Feb 28, 2021 |
| MSI        | Prestige 14 A10SC           | [26f40cdcba](https://linux-hardware.org/?probe=26f40cdcba) | Feb 25, 2021 |
| HP         | ProBook 5330m               | [4a66a57a41](https://linux-hardware.org/?probe=4a66a57a41) | Feb 23, 2021 |
| Razer      | Blade                       | [58fcda1ac4](https://linux-hardware.org/?probe=58fcda1ac4) | Feb 18, 2021 |
| ASUSTek    | N56JN                       | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| Acer       | Aspire V5-471               | [3c0bc82dde](https://linux-hardware.org/?probe=3c0bc82dde) | Jan 16, 2021 |
| Lenovo     | V330-15IKB 81AX             | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| HP         | Pavilion dv7                | [7591424ea2](https://linux-hardware.org/?probe=7591424ea2) | Jan 06, 2021 |
| HP         | Pavilion dv7                | [d660b968a4](https://linux-hardware.org/?probe=d660b968a4) | Jan 06, 2021 |
| Dell       | Inspiron 14-3467            | [fe678ae6f5](https://linux-hardware.org/?probe=fe678ae6f5) | Jan 04, 2021 |
| Dell       | G5 5505                     | [156236cc47](https://linux-hardware.org/?probe=156236cc47) | Dec 30, 2020 |
| Dell       | Latitude E5470              | [f6a3bc1097](https://linux-hardware.org/?probe=f6a3bc1097) | Dec 28, 2020 |
| HP         | Pavilion Notebook           | [033a1ff3cd](https://linux-hardware.org/?probe=033a1ff3cd) | Dec 07, 2020 |
| ASUSTek    | N56JN                       | [776cb81132](https://linux-hardware.org/?probe=776cb81132) | Nov 25, 2020 |
| ASUSTek    | N56JN                       | [e14774acd5](https://linux-hardware.org/?probe=e14774acd5) | Nov 25, 2020 |
| HP         | 14                          | [918fb071c2](https://linux-hardware.org/?probe=918fb071c2) | Nov 22, 2020 |
| Dell       | Latitude 3440               | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP         | ProBook 440 G5              | [07ac3c5495](https://linux-hardware.org/?probe=07ac3c5495) | Oct 07, 2020 |
| HP         | ProBook 440 G5              | [123eb500e2](https://linux-hardware.org/?probe=123eb500e2) | Oct 06, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [735aea26c5](https://linux-hardware.org/?probe=735aea26c5) | Sep 28, 2020 |
| HP         | 240 G7                      | [2507cc1bc7](https://linux-hardware.org/?probe=2507cc1bc7) | Sep 28, 2020 |
| Lenovo     | ThinkPad T470 20HES0JQ00    | [4235f1fc42](https://linux-hardware.org/?probe=4235f1fc42) | Sep 20, 2020 |
| Acer       | Nitro AN515-54              | [60efe004ff](https://linux-hardware.org/?probe=60efe004ff) | Sep 19, 2020 |
| Lenovo     | Legion Y540-15IRH 81SX      | [123ba2dd21](https://linux-hardware.org/?probe=123ba2dd21) | Sep 15, 2020 |
| Lenovo     | Legion Y540-15IRH-PG0 81... | [e193207a8f](https://linux-hardware.org/?probe=e193207a8f) | Sep 14, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [d043bf1b42](https://linux-hardware.org/?probe=d043bf1b42) | Sep 06, 2020 |
| Lenovo     | ThinkPad T430 2349LRS       | [d886cd5c31](https://linux-hardware.org/?probe=d886cd5c31) | Sep 05, 2020 |
| Lenovo     | ThinkPad T430 2349LRS       | [38284d9848](https://linux-hardware.org/?probe=38284d9848) | Sep 05, 2020 |
| Lenovo     | V310-15ISK 80SY             | [fc06b19016](https://linux-hardware.org/?probe=fc06b19016) | Sep 05, 2020 |
| Lenovo     | IdeaPad S540-14API 81NH     | [395b3e9836](https://linux-hardware.org/?probe=395b3e9836) | Sep 05, 2020 |
| Lenovo     | ThinkPad T430s 23539KU      | [2f700d4f41](https://linux-hardware.org/?probe=2f700d4f41) | Sep 03, 2020 |
| Lenovo     | G475 20080                  | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Acer       | Aspire A515-52G             | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer       | Aspire A515-52G             | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Toshiba    | Satellite C845              | [7e218cb089](https://linux-hardware.org/?probe=7e218cb089) | Aug 22, 2020 |
| ASUSTek    | VivoBook_ASUS Laptop X50... | [26fe839699](https://linux-hardware.org/?probe=26fe839699) | Aug 14, 2020 |
| ASUSTek    | VivoBook_ASUS Laptop X50... | [55d2d92173](https://linux-hardware.org/?probe=55d2d92173) | Aug 14, 2020 |
| Lenovo     | ThinkPad P50 20EQA09900     | [4360f8c6a6](https://linux-hardware.org/?probe=4360f8c6a6) | Aug 12, 2020 |
| Lenovo     | ThinkPad P50 20EQA09900     | [76f4cf6487](https://linux-hardware.org/?probe=76f4cf6487) | Aug 12, 2020 |
| Toshiba    | Satellite L45-B             | [ce51a04f5d](https://linux-hardware.org/?probe=ce51a04f5d) | Aug 01, 2020 |
| Lenovo     | ThinkPad T60 1953D9U        | [45c01e0aca](https://linux-hardware.org/?probe=45c01e0aca) | Jul 30, 2020 |
| HP         | 245 G3                      | [044b206096](https://linux-hardware.org/?probe=044b206096) | Jul 26, 2020 |
| Lenovo     | G480 20149                  | [7fdfad1fc4](https://linux-hardware.org/?probe=7fdfad1fc4) | Jul 11, 2020 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [f0ed82358a](https://linux-hardware.org/?probe=f0ed82358a) | Jul 05, 2020 |
| Lenovo     | G480 20149                  | [c9d75e29d3](https://linux-hardware.org/?probe=c9d75e29d3) | Jun 30, 2020 |
| HP         | ProBook 645 G4              | [2fb2b6ad63](https://linux-hardware.org/?probe=2fb2b6ad63) | Jun 22, 2020 |
| HP         | Pavilion Laptop 15-cw1xx... | [844f7b115e](https://linux-hardware.org/?probe=844f7b115e) | Jun 21, 2020 |
| HP         | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| ASUSTek    | X540LA                      | [333139a886](https://linux-hardware.org/?probe=333139a886) | Jun 17, 2020 |
| HP         | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| Toshiba    | Satellite L855              | [adbdc1e191](https://linux-hardware.org/?probe=adbdc1e191) | Jun 13, 2020 |
| ASUSTek    | VivoBook 15_ASUS Laptop ... | [97237c08ac](https://linux-hardware.org/?probe=97237c08ac) | Jun 11, 2020 |
| Apple      | MacBookPro9,2               | [371c5ccd5a](https://linux-hardware.org/?probe=371c5ccd5a) | May 31, 2020 |
| HP         | ENVY 15                     | [9075368552](https://linux-hardware.org/?probe=9075368552) | May 29, 2020 |
| Lenovo     | G50-70 20351                | [fb33cd7cef](https://linux-hardware.org/?probe=fb33cd7cef) | May 26, 2020 |
| HP         | EliteBook 840 G6            | [07829f089a](https://linux-hardware.org/?probe=07829f089a) | May 24, 2020 |
| HP         | ENVY 15                     | [afcc7af453](https://linux-hardware.org/?probe=afcc7af453) | May 23, 2020 |
| Unknown    | Unknown                     | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Unknown    | Unknown                     | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Dell       | Precision M4600             | [7060267281](https://linux-hardware.org/?probe=7060267281) | May 08, 2020 |
| HP         | Pavilion Sleekbook 14 PC    | [c513103ac9](https://linux-hardware.org/?probe=c513103ac9) | May 05, 2020 |
| HP         | 450                         | [22b90eb634](https://linux-hardware.org/?probe=22b90eb634) | May 02, 2020 |
| HP         | 450                         | [0da93b6fce](https://linux-hardware.org/?probe=0da93b6fce) | May 02, 2020 |
| Dell       | System XPS L502X            | [939683d725](https://linux-hardware.org/?probe=939683d725) | Apr 27, 2020 |
| Dell       | System XPS L502X            | [c893f3f105](https://linux-hardware.org/?probe=c893f3f105) | Apr 24, 2020 |
| HP         | Pavilion Laptop 15-cs0xx... | [97261529e7](https://linux-hardware.org/?probe=97261529e7) | Apr 21, 2020 |
| HP         | Pavilion Laptop 15-cs0xx... | [babdfebf40](https://linux-hardware.org/?probe=babdfebf40) | Apr 17, 2020 |
| Lenovo     | Yoga 2 11 20332             | [bbd3b573e1](https://linux-hardware.org/?probe=bbd3b573e1) | Apr 05, 2020 |
| Lenovo     | Yoga 2 11 20332             | [51c0fd8c5c](https://linux-hardware.org/?probe=51c0fd8c5c) | Apr 05, 2020 |
| Toshiba    | NB505                       | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [b112c2d6c6](https://linux-hardware.org/?probe=b112c2d6c6) | Mar 30, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [7dee8ed61e](https://linux-hardware.org/?probe=7dee8ed61e) | Mar 26, 2020 |
| Samsung    | 300E5EV/300E4EV/270E5EV/... | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Sony       | SVF15A17CLB                 | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| Lenovo     | V310-15ISK 80SY             | [88cf0450ac](https://linux-hardware.org/?probe=88cf0450ac) | Mar 15, 2020 |
| Dell       | Inspiron 5567               | [e598212cee](https://linux-hardware.org/?probe=e598212cee) | Feb 28, 2020 |
| HP         | Pavilion Gaming Laptop 1... | [2eebfcd5e9](https://linux-hardware.org/?probe=2eebfcd5e9) | Feb 27, 2020 |
| HP         | Pavilion Gaming Laptop 1... | [1335c3693b](https://linux-hardware.org/?probe=1335c3693b) | Feb 27, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| Lenovo     | IdeaPad 330-15ARR 81D2      | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| Toshiba    | QOSMIO X775                 | [6abcb623e3](https://linux-hardware.org/?probe=6abcb623e3) | Feb 02, 2020 |
| Toshiba    | QOSMIO X775                 | [a2cf60ec44](https://linux-hardware.org/?probe=a2cf60ec44) | Feb 02, 2020 |
| Acer       | Aspire ES1-572              | [8bc74bd7fb](https://linux-hardware.org/?probe=8bc74bd7fb) | Dec 06, 2019 |
| Unknown    | Unknown                     | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| HP         | Pavilion g4                 | [cb1f2e06e7](https://linux-hardware.org/?probe=cb1f2e06e7) | Nov 28, 2019 |
| Dell       | Latitude 5580               | [7abf5fbce7](https://linux-hardware.org/?probe=7abf5fbce7) | Nov 21, 2019 |
| Dell       | Latitude 5580               | [521a1d30b6](https://linux-hardware.org/?probe=521a1d30b6) | Nov 21, 2019 |
| Lenovo     | Y70-70 Touch 80DU           | [dfa431bef9](https://linux-hardware.org/?probe=dfa431bef9) | Nov 13, 2019 |
| Toshiba    | Satellite C55-B             | [ef97116a29](https://linux-hardware.org/?probe=ef97116a29) | Nov 12, 2019 |
| Lenovo     | V330-15IKB 81AX             | [d0612d575f](https://linux-hardware.org/?probe=d0612d575f) | Nov 04, 2019 |
| Dell       | Inspiron 3443               | [daa04d519c](https://linux-hardware.org/?probe=daa04d519c) | Oct 15, 2019 |
| Sony       | VPCEC2JFX                   | [ad30a52539](https://linux-hardware.org/?probe=ad30a52539) | Oct 03, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [e486c2c05f](https://linux-hardware.org/?probe=e486c2c05f) | Sep 12, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [b09160e7cf](https://linux-hardware.org/?probe=b09160e7cf) | Sep 10, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [333fbc5a3b](https://linux-hardware.org/?probe=333fbc5a3b) | Aug 16, 2019 |
| Sony       | VPCEC2JFX                   | [f28ba85f16](https://linux-hardware.org/?probe=f28ba85f16) | Aug 04, 2019 |
| Acer       | Aspire ES1-572              | [432212e4c9](https://linux-hardware.org/?probe=432212e4c9) | Jul 31, 2019 |
| Acer       | Aspire ES1-572              | [8783b0d26c](https://linux-hardware.org/?probe=8783b0d26c) | Jul 31, 2019 |
| HP         | ProBook 440 G4              | [b0ae12ca81](https://linux-hardware.org/?probe=b0ae12ca81) | Jun 27, 2019 |
| Toshiba    | Satellite P755              | [8eaca3c3df](https://linux-hardware.org/?probe=8eaca3c3df) | Jun 13, 2019 |
| HP         | ProBook 645 G4              | [f2f88aaa9d](https://linux-hardware.org/?probe=f2f88aaa9d) | May 24, 2019 |
| HP         | ProBook 645 G4              | [049bd45822](https://linux-hardware.org/?probe=049bd45822) | May 24, 2019 |
| Lenovo     | IdeaPad 330S-14IKB 81F4     | [cdf8203e8f](https://linux-hardware.org/?probe=cdf8203e8f) | Apr 24, 2019 |
| Lenovo     | B50-80 80EW                 | [275d0c887d](https://linux-hardware.org/?probe=275d0c887d) | Dec 28, 2018 |
| Lenovo     | B50-80 80EW                 | [603e6d3da4](https://linux-hardware.org/?probe=603e6d3da4) | Dec 28, 2018 |
| HP         | 1000                        | [9bf9fc957a](https://linux-hardware.org/?probe=9bf9fc957a) | Sep 04, 2018 |
| HP         | 1000                        | [684f6b1db8](https://linux-hardware.org/?probe=684f6b1db8) | Jan 30, 2018 |
| Sony       | VGN-FW170J                  | [2ac505bc7b](https://linux-hardware.org/?probe=2ac505bc7b) | Jan 04, 2018 |
| HP         | 1000                        | [0e00b75fea](https://linux-hardware.org/?probe=0e00b75fea) | Dec 19, 2017 |
| Sony       | VGN-FW170J                  | [d2b4cdb291](https://linux-hardware.org/?probe=d2b4cdb291) | Nov 21, 2017 |
| Acer       | Aspire S3                   | [db53fb01bd](https://linux-hardware.org/?probe=db53fb01bd) | May 26, 2017 |
| Acer       | Aspire S3                   | [a3cfad5de1](https://linux-hardware.org/?probe=a3cfad5de1) | May 26, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 13.06%  |
| OpenMandriva 4.3             | 10        | 4.08%   |
| Arch Rolling                 | 10        | 4.08%   |
| Ubuntu 22.04                 | 9         | 3.67%   |
| Ubuntu 18.04                 | 9         | 3.67%   |
| Linux Mint 21.1              | 7         | 2.86%   |
| Zorin 15                     | 6         | 2.45%   |
| OpenMandriva 23.03           | 6         | 2.45%   |
| Linux Mint 20.3              | 6         | 2.45%   |
| Ubuntu 19.10                 | 5         | 2.04%   |
| Manjaro                      | 5         | 2.04%   |
| Fedora 38                    | 5         | 2.04%   |
| Fedora 37                    | 5         | 2.04%   |
| Arch                         | 5         | 2.04%   |
| Xubuntu 20.04                | 4         | 1.63%   |
| Ubuntu 21.04                 | 4         | 1.63%   |
| Pop!_OS 21.10                | 4         | 1.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 1.63%   |
| OpenMandriva 23.01           | 4         | 1.63%   |
| Debian 11                    | 4         | 1.63%   |
| Ubuntu 19.04                 | 3         | 1.22%   |
| Pop!_OS 20.10                | 3         | 1.22%   |
| OpenMandriva 4.2             | 3         | 1.22%   |
| Manjaro 20.1                 | 3         | 1.22%   |
| KDE neon 20.04               | 3         | 1.22%   |
| Fedora 35                    | 3         | 1.22%   |
| Elementary 5.1.7             | 3         | 1.22%   |
| Debian 10                    | 3         | 1.22%   |
| ArcoLinux Rolling            | 3         | 1.22%   |
| ROSA R9                      | 2         | 0.82%   |
| ROSA R10                     | 2         | 0.82%   |
| ROSA 12.3                    | 2         | 0.82%   |
| ROSA 12.2                    | 2         | 0.82%   |
| Pop!_OS 22.04                | 2         | 0.82%   |
| Pop!_OS 20.04                | 2         | 0.82%   |
| OpenMandriva 4.90            | 2         | 0.82%   |
| LMDE 5                       | 2         | 0.82%   |
| Linux Mint 20                | 2         | 0.82%   |
| Kubuntu 20.04                | 2         | 0.82%   |
| Fedora 34                    | 2         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 62        | 25.94%  |
| OpenMandriva  | 26        | 10.88%  |
| Fedora        | 19        | 7.95%   |
| Linux Mint    | 18        | 7.53%   |
| Arch          | 16        | 6.69%   |
| Pop!_OS       | 12        | 5.02%   |
| Manjaro       | 12        | 5.02%   |
| Debian        | 10        | 4.18%   |
| ROSA          | 9         | 3.77%   |
| Zorin         | 7         | 2.93%   |
| Xubuntu       | 4         | 1.67%   |
| openSUSE      | 4         | 1.67%   |
| KDE neon      | 4         | 1.67%   |
| Elementary    | 4         | 1.67%   |
| Endless       | 3         | 1.26%   |
| ArcoLinux     | 3         | 1.26%   |
| Ubuntu MATE   | 2         | 0.84%   |
| Parrot        | 2         | 0.84%   |
| Lubuntu       | 2         | 0.84%   |
| LMDE          | 2         | 0.84%   |
| Kubuntu       | 2         | 0.84%   |
| Kali          | 2         | 0.84%   |
| CentOS        | 2         | 0.84%   |
| Void Linux    | 1         | 0.42%   |
| Ubuntu Unity  | 1         | 0.42%   |
| Ubuntu Studio | 1         | 0.42%   |
| Ubuntu Budgie | 1         | 0.42%   |
| SteamOS       | 1         | 0.42%   |
| Peppermint    | 1         | 0.42%   |
| NixOS         | 1         | 0.42%   |
| MX            | 1         | 0.42%   |
| Laxer OS      | 1         | 0.42%   |
| EndeavourOS   | 1         | 0.42%   |
| Clear Linux   | 1         | 0.42%   |
| Artix         | 1         | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 10        | 3.72%   |
| 6.2.6-desktop-1omv2390          | 5         | 1.86%   |
| 5.13.0-40-generic               | 5         | 1.86%   |
| 5.4.0-42-generic                | 4         | 1.49%   |
| 6.3.5-200.fc38.x86_64           | 3         | 1.12%   |
| 5.4.0-26-generic                | 3         | 1.12%   |
| 5.3.0-40-generic                | 3         | 1.12%   |
| 5.15.0-71-generic               | 3         | 1.12%   |
| 5.13.0-51-generic               | 3         | 1.12%   |
| 5.11.0-25-generic               | 3         | 1.12%   |
| 5.10.0-13-amd64                 | 3         | 1.12%   |
| 6.3.6-arch1-1                   | 2         | 0.74%   |
| 6.1.4-desktop-1omv2301          | 2         | 0.74%   |
| 6.1.1-desktop-1omv2290          | 2         | 0.74%   |
| 5.8.0-44-generic                | 2         | 0.74%   |
| 5.4.0-7642-generic              | 2         | 0.74%   |
| 5.4.0-66-generic                | 2         | 0.74%   |
| 5.4.0-65-generic                | 2         | 0.74%   |
| 5.4.0-58-generic                | 2         | 0.74%   |
| 5.4.0-54-generic                | 2         | 0.74%   |
| 5.4.0-39-generic                | 2         | 0.74%   |
| 5.4.0-33-generic                | 2         | 0.74%   |
| 5.4.0-28-generic                | 2         | 0.74%   |
| 5.4.0-109-generic               | 2         | 0.74%   |
| 5.3.0-42-generic                | 2         | 0.74%   |
| 5.3.0-23-generic                | 2         | 0.74%   |
| 5.18.12-desktop-3omv4090        | 2         | 0.74%   |
| 5.17.5-arch1-1                  | 2         | 0.74%   |
| 5.16.19-76051619-generic        | 2         | 0.74%   |
| 5.15.49-1-lts                   | 2         | 0.74%   |
| 5.15.0-58-generic               | 2         | 0.74%   |
| 5.15.0-57-generic               | 2         | 0.74%   |
| 5.15.0-52-generic               | 2         | 0.74%   |
| 5.15.0-25-generic               | 2         | 0.74%   |
| 5.13.0-30-generic               | 2         | 0.74%   |
| 5.11.0-7614-generic             | 2         | 0.74%   |
| 5.10.14-desktop-1omv4002        | 2         | 0.74%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.74%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 0.74%   |
| 6.3.6-zen1-1-zen                | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 14.62%  |
| 5.15.0  | 19        | 7.31%   |
| 5.11.0  | 14        | 5.38%   |
| 5.13.0  | 13        | 5%      |
| 5.3.0   | 12        | 4.62%   |
| 5.16.7  | 10        | 3.85%   |
| 5.8.0   | 7         | 2.69%   |
| 5.10.0  | 7         | 2.69%   |
| 5.0.0   | 7         | 2.69%   |
| 4.15.0  | 7         | 2.69%   |
| 4.18.0  | 6         | 2.31%   |
| 6.2.6   | 5         | 1.92%   |
| 5.19.0  | 5         | 1.92%   |
| 6.3.5   | 4         | 1.54%   |
| 6.3.6   | 3         | 1.15%   |
| 6.0.0   | 3         | 1.15%   |
| 5.17.5  | 3         | 1.15%   |
| 4.9.60  | 3         | 1.15%   |
| 6.1.9   | 2         | 0.77%   |
| 6.1.4   | 2         | 0.77%   |
| 6.1.31  | 2         | 0.77%   |
| 6.1.11  | 2         | 0.77%   |
| 6.1.1   | 2         | 0.77%   |
| 6.0.7   | 2         | 0.77%   |
| 6.0.15  | 2         | 0.77%   |
| 5.18.12 | 2         | 0.77%   |
| 5.16.19 | 2         | 0.77%   |
| 5.15.49 | 2         | 0.77%   |
| 5.12.10 | 2         | 0.77%   |
| 5.10.14 | 2         | 0.77%   |
| 4.9.20  | 2         | 0.77%   |
| 4.19.0  | 2         | 0.77%   |
| 6.3.4   | 1         | 0.38%   |
| 6.2.9   | 1         | 0.38%   |
| 6.2.2   | 1         | 0.38%   |
| 6.2.15  | 1         | 0.38%   |
| 6.2.14  | 1         | 0.38%   |
| 6.2.11  | 1         | 0.38%   |
| 6.2.10  | 1         | 0.38%   |
| 6.2.0   | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 16.21%  |
| 5.15    | 31        | 12.25%  |
| 5.11    | 15        | 5.93%   |
| 5.13    | 14        | 5.53%   |
| 5.10    | 14        | 5.53%   |
| 6.1     | 13        | 5.14%   |
| 5.16    | 13        | 5.14%   |
| 6.2     | 12        | 4.74%   |
| 6.0     | 12        | 4.74%   |
| 5.3     | 12        | 4.74%   |
| 5.8     | 10        | 3.95%   |
| 6.3     | 7         | 2.77%   |
| 5.19    | 7         | 2.77%   |
| 5.17    | 7         | 2.77%   |
| 5.0     | 7         | 2.77%   |
| 4.15    | 7         | 2.77%   |
| 4.18    | 6         | 2.37%   |
| 5.18    | 4         | 1.58%   |
| 5.12    | 4         | 1.58%   |
| 4.9     | 4         | 1.58%   |
| 5.14    | 3         | 1.19%   |
| 5.9     | 2         | 0.79%   |
| 5.7     | 2         | 0.79%   |
| 5.6     | 2         | 0.79%   |
| 4.19    | 2         | 0.79%   |
| 5.1     | 1         | 0.4%    |
| 4.16    | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 222       | 96.52%  |
| i686   | 8         | 3.48%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 105       | 44.12%  |
| KDE5            | 45        | 18.91%  |
| XFCE            | 20        | 8.4%    |
| X-Cinnamon      | 15        | 6.3%    |
| Unknown         | 15        | 6.3%    |
| MATE            | 7         | 2.94%   |
| KDE             | 6         | 2.52%   |
| Pantheon        | 4         | 1.68%   |
| KDE4            | 4         | 1.68%   |
| i3              | 4         | 1.68%   |
| LXQt            | 3         | 1.26%   |
| sway            | 2         | 0.84%   |
| LXDE            | 2         | 0.84%   |
| Budgie          | 2         | 0.84%   |
| Unity           | 1         | 0.42%   |
| spectrwm        | 1         | 0.42%   |
| GNOME Flashback | 1         | 0.42%   |
| Deepin          | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 173       | 72.38%  |
| Wayland | 49        | 20.5%   |
| Unknown | 15        | 6.28%   |
| Tty     | 2         | 0.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 45.57%  |
| SDDM    | 39        | 16.46%  |
| GDM     | 38        | 16.03%  |
| LightDM | 27        | 11.39%  |
| GDM3    | 16        | 6.75%   |
| KDM     | 4         | 1.69%   |
| TDM     | 2         | 0.84%   |
| XDM     | 1         | 0.42%   |
| Ly      | 1         | 0.42%   |
| LXDM    | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 112       | 47.66%  |
| en_US   | 66        | 28.09%  |
| es_ES   | 20        | 8.51%   |
| Unknown | 16        | 6.81%   |
| es_MX   | 6         | 2.55%   |
| C       | 3         | 1.28%   |
| it_IT   | 2         | 0.85%   |
| fr_FR   | 2         | 0.85%   |
| en_GB   | 2         | 0.85%   |
| ca_ES   | 2         | 0.85%   |
| es_VE   | 1         | 0.43%   |
| es_CO   | 1         | 0.43%   |
| en_NZ   | 1         | 0.43%   |
| Default | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 133       | 57.08%  |
| BIOS | 100       | 42.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 178       | 75.42%  |
| Btrfs   | 23        | 9.75%   |
| Overlay | 21        | 8.9%    |
| Unknown | 7         | 2.97%   |
| Xfs     | 6         | 2.54%   |
| Ext3    | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 118       | 50.64%  |
| GPT     | 94        | 40.34%  |
| MBR     | 21        | 9.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 204       | 87.55%  |
| Yes       | 29        | 12.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 135       | 57.69%  |
| Yes       | 99        | 42.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 61        | 26.64%  |
| Lenovo              | 60        | 26.2%   |
| ASUSTek Computer    | 28        | 12.23%  |
| Dell                | 23        | 10.04%  |
| Toshiba             | 16        | 6.99%   |
| Acer                | 15        | 6.55%   |
| Sony                | 5         | 2.18%   |
| MSI                 | 4         | 1.75%   |
| HUAWEI              | 3         | 1.31%   |
| Chuwi               | 3         | 1.31%   |
| Apple               | 3         | 1.31%   |
| Advance             | 2         | 0.87%   |
| Samsung Electronics | 1         | 0.44%   |
| Razer               | 1         | 0.44%   |
| eMachines           | 1         | 0.44%   |
| efirstview          | 1         | 0.44%   |
| Compal              | 1         | 0.44%   |
| Unknown             | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V330-15IKB 81AX                   | 4         | 1.75%   |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 1.75%   |
| HP 14                                    | 4         | 1.75%   |
| Lenovo V310-15ISK 80SY                   | 3         | 1.31%   |
| Chuwi GemiBook Pro                       | 3         | 1.31%   |
| Toshiba Satellite L45-B                  | 2         | 0.87%   |
| Toshiba Satellite C45-A                  | 2         | 0.87%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.87%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.87%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.87%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 2         | 0.87%   |
| Lenovo G400 20235                        | 2         | 0.87%   |
| HP ProBook 645 G4                        | 2         | 0.87%   |
| HP Pavilion g4                           | 2         | 0.87%   |
| HP Notebook                              | 2         | 0.87%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.87%   |
| HP 450                                   | 2         | 0.87%   |
| HP 250 G7 Notebook PC                    | 2         | 0.87%   |
| Dell XPS 13 9360                         | 2         | 0.87%   |
| Dell Latitude E7450                      | 2         | 0.87%   |
| Dell G5 5505                             | 2         | 0.87%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 2         | 0.87%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR     | 2         | 0.87%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.87%   |
| Apple MacBookPro9,2                      | 2         | 0.87%   |
| Toshiba Satellite P755                   | 1         | 0.44%   |
| Toshiba Satellite P300                   | 1         | 0.44%   |
| Toshiba Satellite L855                   | 1         | 0.44%   |
| Toshiba Satellite L35                    | 1         | 0.44%   |
| Toshiba Satellite E205                   | 1         | 0.44%   |
| Toshiba Satellite C845                   | 1         | 0.44%   |
| Toshiba Satellite C655D                  | 1         | 0.44%   |
| Toshiba Satellite C645                   | 1         | 0.44%   |
| Toshiba Satellite C55-B                  | 1         | 0.44%   |
| Toshiba Satellite A665                   | 1         | 0.44%   |
| Toshiba QOSMIO X775                      | 1         | 0.44%   |
| Toshiba NB505                            | 1         | 0.44%   |
| Sony VPCEL36FJ                           | 1         | 0.44%   |
| Sony VPCEC2JFX                           | 1         | 0.44%   |
| Sony VGN-FW56M                           | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 18        | 7.86%   |
| Lenovo ThinkPad   | 17        | 7.42%   |
| HP Pavilion       | 17        | 7.42%   |
| Toshiba Satellite | 14        | 6.11%   |
| Acer Aspire       | 13        | 5.68%   |
| ASUS VivoBook     | 10        | 4.37%   |
| Dell Latitude     | 9         | 3.93%   |
| HP ProBook        | 8         | 3.49%   |
| HP Laptop         | 8         | 3.49%   |
| Dell Inspiron     | 7         | 3.06%   |
| Lenovo Legion     | 5         | 2.18%   |
| Lenovo V330-15IKB | 4         | 1.75%   |
| HP 14             | 4         | 1.75%   |
| ASUS ROG          | 4         | 1.75%   |
| Lenovo V310-15ISK | 3         | 1.31%   |
| HP 250            | 3         | 1.31%   |
| Chuwi GemiBook    | 3         | 1.31%   |
| ASUS ASUS         | 3         | 1.31%   |
| Lenovo G400       | 2         | 0.87%   |
| HP ZBook          | 2         | 0.87%   |
| HP Notebook       | 2         | 0.87%   |
| HP ENVY           | 2         | 0.87%   |
| HP EliteBook      | 2         | 0.87%   |
| HP Compaq         | 2         | 0.87%   |
| HP 450            | 2         | 0.87%   |
| HP 255            | 2         | 0.87%   |
| HP 240            | 2         | 0.87%   |
| Dell XPS          | 2         | 0.87%   |
| Dell G5           | 2         | 0.87%   |
| Apple MacBookPro9 | 2         | 0.87%   |
| Toshiba QOSMIO    | 1         | 0.44%   |
| Toshiba NB505     | 1         | 0.44%   |
| Sony VPCEL36FJ    | 1         | 0.44%   |
| Sony VPCEC2JFX    | 1         | 0.44%   |
| Sony VGN-FW56M    | 1         | 0.44%   |
| Sony VGN-FW170J   | 1         | 0.44%   |
| Sony SVF15A17CLB  | 1         | 0.44%   |
| Samsung 300E5EV   | 1         | 0.44%   |
| Razer Blade       | 1         | 0.44%   |
| MSI PS42          | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 26        | 11.35%  |
| 2019 | 25        | 10.92%  |
| 2018 | 21        | 9.17%   |
| 2012 | 20        | 8.73%   |
| 2021 | 19        | 8.3%    |
| 2016 | 19        | 8.3%    |
| 2017 | 18        | 7.86%   |
| 2014 | 18        | 7.86%   |
| 2013 | 18        | 7.86%   |
| 2011 | 16        | 6.99%   |
| 2015 | 6         | 2.62%   |
| 2010 | 6         | 2.62%   |
| 2022 | 5         | 2.18%   |
| 2009 | 4         | 1.75%   |
| 2008 | 4         | 1.75%   |
| 2007 | 3         | 1.31%   |
| 2006 | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 229       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 208       | 90.43%  |
| Enabled  | 22        | 9.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 229       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 71        | 30.21%  |
| 8.01-16.0   | 67        | 28.51%  |
| 3.01-4.0    | 42        | 17.87%  |
| 16.01-24.0  | 31        | 13.19%  |
| 1.01-2.0    | 8         | 3.4%    |
| 2.01-3.0    | 6         | 2.55%   |
| 32.01-64.0  | 5         | 2.13%   |
| 24.01-32.0  | 2         | 0.85%   |
| 0.51-1.0    | 2         | 0.85%   |
| 64.01-256.0 | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 79        | 31.1%   |
| 2.01-3.0  | 76        | 29.92%  |
| 4.01-8.0  | 39        | 15.35%  |
| 3.01-4.0  | 33        | 12.99%  |
| 0.51-1.0  | 17        | 6.69%   |
| 8.01-16.0 | 9         | 3.54%   |
| 0.01-0.5  | 1         | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 170       | 73.59%  |
| 2      | 56        | 24.24%  |
| 3      | 4         | 1.73%   |
| 0      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 150       | 65.5%   |
| Yes       | 79        | 34.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 84.42%  |
| No        | 36        | 15.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 98.69%  |
| No        | 3         | 1.31%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 83.48%  |
| No        | 38        | 16.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 229       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 153       | 64.56%  |
| Arequipa              | 23        | 9.7%    |
| Trujillo              | 15        | 6.33%   |
| Huancayo              | 7         | 2.95%   |
| Piura                 | 6         | 2.53%   |
| Cusco                 | 5         | 2.11%   |
| Chiclayo              | 4         | 1.69%   |
| Tacna                 | 2         | 0.84%   |
| La Victoria           | 2         | 0.84%   |
| Ica                   | 2         | 0.84%   |
| Callao                | 2         | 0.84%   |
| San Vicente de Canete | 1         | 0.42%   |
| San Isidro            | 1         | 0.42%   |
| San Borja             | 1         | 0.42%   |
| Punta Colorada        | 1         | 0.42%   |
| Puno                  | 1         | 0.42%   |
| Pisco                 | 1         | 0.42%   |
| Oxapampa              | 1         | 0.42%   |
| Moquegua              | 1         | 0.42%   |
| Juliaca               | 1         | 0.42%   |
| Iquitos               | 1         | 0.42%   |
| Huaraz                | 1         | 0.42%   |
| Distrito de Lima      | 1         | 0.42%   |
| Cajamarca             | 1         | 0.42%   |
| Barranco              | 1         | 0.42%   |
| Ayacucho              | 1         | 0.42%   |
| Abancay               | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 45        | 51     | 15.79%  |
| Toshiba                        | 43        | 52     | 15.09%  |
| Seagate                        | 38        | 44     | 13.33%  |
| Kingston                       | 33        | 40     | 11.58%  |
| Samsung Electronics            | 16        | 24     | 5.61%   |
| SanDisk                        | 12        | 15     | 4.21%   |
| Crucial                        | 11        | 16     | 3.86%   |
| Unknown                        | 7         | 7      | 2.46%   |
| SK hynix                       | 7         | 10     | 2.46%   |
| Intel                          | 7         | 9      | 2.46%   |
| Micron Technology              | 6         | 7      | 2.11%   |
| KIOXIA                         | 6         | 7      | 2.11%   |
| Hitachi                        | 6         | 8      | 2.11%   |
| HGST                           | 6         | 6      | 2.11%   |
| Hewlett-Packard                | 4         | 4      | 1.4%    |
| TO Exter                       | 3         | 7      | 1.05%   |
| Netac                          | 3         | 3      | 1.05%   |
| LITEON                         | 3         | 3      | 1.05%   |
| UMIS                           | 2         | 2      | 0.7%    |
| Silicon Motion                 | 2         | 2      | 0.7%    |
| Kingston Technology Company    | 2         | 2      | 0.7%    |
| Gigabyte Technology            | 2         | 2      | 0.7%    |
| China                          | 2         | 2      | 0.7%    |
| Apple                          | 2         | 2      | 0.7%    |
| Unknown                        | 2         | 2      | 0.7%    |
| Union Memory (Shenzhen)        | 1         | 1      | 0.35%   |
| SSSTC                          | 1         | 1      | 0.35%   |
| Solid State Storage Technology | 1         | 1      | 0.35%   |
| Reletech-P400                  | 1         | 1      | 0.35%   |
| Phison Electronics             | 1         | 1      | 0.35%   |
| Phison                         | 1         | 1      | 0.35%   |
| Micron/Crucial Technology      | 1         | 4      | 0.35%   |
| KingSpec                       | 1         | 1      | 0.35%   |
| ITHOO                          | 1         | 1      | 0.35%   |
| GLOWAY                         | 1         | 1      | 0.35%   |
| Fujitsu                        | 1         | 1      | 0.35%   |
| Dogfish                        | 1         | 1      | 0.35%   |
| Biwin Storage Technology       | 1         | 3      | 0.35%   |
| ACASIS                         | 1         | 1      | 0.35%   |
| A-DATA Technology              | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 15        | 5.12%   |
| Kingston SA400S37240G 240GB SSD      | 14        | 4.78%   |
| Toshiba MQ04ABF100 1TB               | 9         | 3.07%   |
| Toshiba MQ01ABD100 1TB               | 9         | 3.07%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 7         | 2.39%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.71%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.37%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 1.37%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 1.37%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 1.02%   |
| Toshiba MQ01ABD075 752GB             | 3         | 1.02%   |
| TO Exter nal USB 3.0 1TB             | 3         | 1.02%   |
| Seagate ST9500325AS 500GB            | 3         | 1.02%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.02%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.02%   |
| Netac SSD 256GB                      | 3         | 1.02%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 3         | 1.02%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.02%   |
| HP SSD S700 500GB                    | 3         | 1.02%   |
| Crucial CT500MX500SSD4 500GB         | 3         | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.68%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.68%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.68%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.68%   |
| Unknown SD32G  32GB                  | 2         | 0.68%   |
| Unknown MMC Card  32GB               | 2         | 0.68%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.68%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.68%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.68%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.68%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.68%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.68%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.68%   |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.68%   |
| Kingston SNVS500G 500GB              | 2         | 0.68%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.68%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.68%   |
| Unknown                              | 2         | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 41        | 50     | 34.17%  |
| Seagate | 38        | 43     | 31.67%  |
| WDC     | 26        | 29     | 21.67%  |
| Hitachi | 6         | 8      | 5%      |
| HGST    | 6         | 6      | 5%      |
| Fujitsu | 1         | 1      | 0.83%   |
| Apple   | 1         | 1      | 0.83%   |
| ACASIS  | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 28        | 33     | 31.46%  |
| WDC                 | 15        | 16     | 16.85%  |
| Crucial             | 10        | 14     | 11.24%  |
| SanDisk             | 5         | 7      | 5.62%   |
| Samsung Electronics | 4         | 4      | 4.49%   |
| Hewlett-Packard     | 4         | 4      | 4.49%   |
| TO Exter            | 3         | 7      | 3.37%   |
| Netac               | 3         | 3      | 3.37%   |
| LITEON              | 3         | 3      | 3.37%   |
| China               | 2         | 2      | 2.25%   |
| Toshiba             | 1         | 1      | 1.12%   |
| SSSTC               | 1         | 1      | 1.12%   |
| SK hynix            | 1         | 4      | 1.12%   |
| Seagate             | 1         | 1      | 1.12%   |
| Reletech-P400       | 1         | 1      | 1.12%   |
| KingSpec            | 1         | 1      | 1.12%   |
| GLOWAY              | 1         | 1      | 1.12%   |
| Gigabyte Technology | 1         | 1      | 1.12%   |
| Dogfish             | 1         | 1      | 1.12%   |
| Apple               | 1         | 1      | 1.12%   |
| A-DATA Technology   | 1         | 1      | 1.12%   |
| Unknown             | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 119       | 139    | 43.75%  |
| SSD     | 79        | 108    | 29.04%  |
| NVMe    | 66        | 92     | 24.26%  |
| MMC     | 7         | 7      | 2.57%   |
| Unknown | 1         | 1      | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 170       | 239    | 68.55%  |
| NVMe | 66        | 92     | 26.61%  |
| MMC  | 7         | 7      | 2.82%   |
| SAS  | 5         | 9      | 2.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 137    | 53.65%  |
| 0.51-1.0   | 86        | 104    | 44.79%  |
| 1.01-2.0   | 3         | 6      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 65        | 27.31%  |
| 251-500        | 57        | 23.95%  |
| 501-1000       | 48        | 20.17%  |
| 51-100         | 18        | 7.56%   |
| 21-50          | 16        | 6.72%   |
| 1-20           | 13        | 5.46%   |
| 1001-2000      | 12        | 5.04%   |
| More than 3000 | 4         | 1.68%   |
| 2001-3000      | 3         | 1.26%   |
| Unknown        | 2         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 93        | 37.8%   |
| 21-50          | 55        | 22.36%  |
| 101-250        | 31        | 12.6%   |
| 51-100         | 28        | 11.38%  |
| 251-500        | 19        | 7.72%   |
| 501-1000       | 12        | 4.88%   |
| 1001-2000      | 3         | 1.22%   |
| 2001-3000      | 2         | 0.81%   |
| Unknown        | 2         | 0.81%   |
| More than 3000 | 1         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2         | 2      | 8%      |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 2      | 8%      |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 4%      |
| WDC WD3200BEVT-22ZCT0 320GB      | 1         | 1      | 4%      |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 4%      |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 4%      |
| Toshiba MK5065GSXN 500GB         | 1         | 1      | 4%      |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 4%      |
| Toshiba MK2035GSS 200GB          | 1         | 1      | 4%      |
| Toshiba HDWJ110 1TB              | 1         | 1      | 4%      |
| SSSTC CVB-8D128-HP 128GB         | 1         | 1      | 4%      |
| Seagate ST9500325AS 500GB        | 1         | 1      | 4%      |
| Seagate ST9250315AS 250GB        | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 4%      |
| Seagate ST1000LM014-1EJ164 1TB   | 1         | 1      | 4%      |
| Kingston SA400S37480G 480GB SSD  | 1         | 1      | 4%      |
| Hitachi HTS725050A7E630 500GB    | 1         | 1      | 4%      |
| Hitachi HTS545050B9A300 500GB    | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB    | 1         | 3      | 4%      |
| Hitachi HTS545032B9A302 320GB    | 1         | 1      | 4%      |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 4%      |
| HGST HTS541010A9E680 1TB         | 1         | 1      | 4%      |
| Hewlett-Packard SSD S700 500GB   | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 25%     |
| Toshiba         | 5         | 6      | 20.83%  |
| Seagate         | 4         | 4      | 16.67%  |
| Hitachi         | 4         | 6      | 16.67%  |
| HGST            | 2         | 2      | 8.33%   |
| SSSTC           | 1         | 1      | 4.17%   |
| Kingston        | 1         | 1      | 4.17%   |
| Hewlett-Packard | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 6      | 27.78%  |
| Seagate | 4         | 4      | 22.22%  |
| Hitachi | 4         | 6      | 22.22%  |
| WDC     | 3         | 3      | 16.67%  |
| HGST    | 2         | 2      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 21     | 75%     |
| SSD  | 6         | 6      | 25%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK3252GSX 320GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 135       | 200    | 54.66%  |
| Works    | 88        | 118    | 35.63%  |
| Malfunc  | 23        | 27     | 9.31%   |
| Failed   | 1         | 2      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 160       | 61.78%  |
| AMD                              | 35        | 13.51%  |
| SanDisk                          | 13        | 5.02%   |
| Samsung Electronics              | 13        | 5.02%   |
| Kingston Technology Company      | 7         | 2.7%    |
| SK hynix                         | 6         | 2.32%   |
| Micron Technology                | 6         | 2.32%   |
| KIOXIA                           | 6         | 2.32%   |
| Union Memory (Shenzhen)          | 2         | 0.77%   |
| Silicon Motion                   | 2         | 0.77%   |
| Phison Electronics               | 2         | 0.77%   |
| Micron/Crucial Technology        | 2         | 0.77%   |
| Toshiba America Info Systems     | 1         | 0.39%   |
| Solid State Storage Technology   | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| INNOGRIT                         | 1         | 0.39%   |
| Biwin Storage Technology         | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 31        | 11.4%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 29        | 10.66%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 6.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 6.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 2.94%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.21%   |
| Micron NVMe Storage Controller                                                 | 6         | 2.21%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 6         | 2.21%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 2.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 2.21%   |
| Intel Non-Volatile memory controller                                           | 5         | 1.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.84%   |
| SK hynix BC511                                                                 | 4         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.47%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.1%    |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.1%    |
| Kingston Company NVMe Controller                                               | 3         | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.1%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.74%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.74%   |
| SanDisk NVMe Controller                                                        | 2         | 0.74%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.74%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.74%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 2         | 0.74%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 0.74%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 165       | 62.5%   |
| NVMe | 66        | 25%     |
| RAID | 25        | 9.47%   |
| IDE  | 8         | 3.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 76.86%  |
| AMD    | 53        | 23.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 3.93%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 7         | 3.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 6         | 2.62%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 6         | 2.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 5         | 2.18%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 5         | 2.18%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 5         | 2.18%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 5         | 2.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 4         | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 4         | 1.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 4         | 1.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 4         | 1.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 4         | 1.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 3         | 1.31%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 3         | 1.31%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 3         | 1.31%   |
| Intel Celeron J4115 CPU @ 1.80GHz               | 3         | 1.31%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.31%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 0.87%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 0.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.87%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 2         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 0.87%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 2         | 0.87%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 0.87%   |
| Intel Core i5 CPU M 480 @ 2.67GHz               | 2         | 0.87%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 2         | 0.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 2         | 0.87%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 0.87%   |
| Intel Core i3-2328M CPU @ 2.20GHz               | 2         | 0.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 0.87%   |
| Intel Celeron CPU 550 @ 2.00GHz                 | 2         | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 0.87%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 59        | 25.76%  |
| Intel Core i5           | 57        | 24.89%  |
| Intel Core i3           | 27        | 11.79%  |
| AMD Ryzen 7             | 16        | 6.99%   |
| AMD Ryzen 5             | 16        | 6.99%   |
| Other                   | 11        | 4.8%    |
| Intel Celeron           | 9         | 3.93%   |
| Intel Atom              | 5         | 2.18%   |
| Intel Core 2 Duo        | 3         | 1.31%   |
| AMD A8                  | 3         | 1.31%   |
| Intel Pentium           | 2         | 0.87%   |
| AMD Ryzen 9             | 2         | 0.87%   |
| AMD Ryzen 7 PRO         | 2         | 0.87%   |
| AMD Ryzen 3             | 2         | 0.87%   |
| AMD E1                  | 2         | 0.87%   |
| AMD E                   | 2         | 0.87%   |
| AMD Athlon              | 2         | 0.87%   |
| Intel Xeon              | 1         | 0.44%   |
| Intel Pentium Dual-Core | 1         | 0.44%   |
| Intel Pentium Dual      | 1         | 0.44%   |
| Intel Genuine           | 1         | 0.44%   |
| Intel Celeron M         | 1         | 0.44%   |
| AMD C-50                | 1         | 0.44%   |
| AMD A4                  | 1         | 0.44%   |
| AMD A12                 | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 111       | 48.47%  |
| 4       | 82        | 35.81%  |
| 8       | 17        | 7.42%   |
| 6       | 11        | 4.8%    |
| 1       | 6         | 2.62%   |
| 10      | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 229       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 193       | 84.28%  |
| 1       | 35        | 15.28%  |
| Unknown | 1         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 223       | 96.54%  |
| 64-bit         | 3         | 1.3%    |
| 32-bit         | 3         | 1.3%    |
| Unknown        | 2         | 0.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 22.46%  |
| 0x206a7    | 15        | 6.36%   |
| 0x306a9    | 12        | 5.08%   |
| 0x40651    | 11        | 4.66%   |
| 0x806ec    | 10        | 4.24%   |
| 0x806ea    | 10        | 4.24%   |
| 0x406e3    | 10        | 4.24%   |
| 0x806e9    | 8         | 3.39%   |
| 0x306d4    | 8         | 3.39%   |
| 0x08108109 | 8         | 3.39%   |
| 0x08108102 | 6         | 2.54%   |
| 0x906ea    | 5         | 2.12%   |
| 0x806c1    | 5         | 2.12%   |
| 0x706e5    | 5         | 2.12%   |
| 0x306c3    | 5         | 2.12%   |
| 0x0a50000c | 5         | 2.12%   |
| 0x20655    | 4         | 1.69%   |
| 0x806eb    | 3         | 1.27%   |
| 0x30678    | 3         | 1.27%   |
| 0x20652    | 3         | 1.27%   |
| 0x08608103 | 3         | 1.27%   |
| 0xa0652    | 2         | 0.85%   |
| 0x906e9    | 2         | 0.85%   |
| 0x1067a    | 2         | 0.85%   |
| 0x10661    | 2         | 0.85%   |
| 0x0a404101 | 2         | 0.85%   |
| 0x08600106 | 2         | 0.85%   |
| 0x08600104 | 2         | 0.85%   |
| 0x08600102 | 2         | 0.85%   |
| 0x05000029 | 2         | 0.85%   |
| 0x906a4    | 1         | 0.42%   |
| 0x906a3    | 1         | 0.42%   |
| 0x806d1    | 1         | 0.42%   |
| 0x706a1    | 1         | 0.42%   |
| 0x6fd      | 1         | 0.42%   |
| 0x6e8      | 1         | 0.42%   |
| 0x6d8      | 1         | 0.42%   |
| 0x506e3    | 1         | 0.42%   |
| 0x406c4    | 1         | 0.42%   |
| 0x30673    | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 22.27%  |
| Haswell          | 20        | 8.73%   |
| IvyBridge        | 18        | 7.86%   |
| Zen+             | 17        | 7.42%   |
| SandyBridge      | 16        | 6.99%   |
| Skylake          | 13        | 5.68%   |
| Broadwell        | 10        | 4.37%   |
| Zen 2            | 8         | 3.49%   |
| Westmere         | 8         | 3.49%   |
| Silvermont       | 7         | 3.06%   |
| Icelake          | 7         | 3.06%   |
| Unknown          | 7         | 3.06%   |
| Zen 3            | 5         | 2.18%   |
| TigerLake        | 5         | 2.18%   |
| Zen              | 4         | 1.75%   |
| Penryn           | 4         | 1.75%   |
| Piledriver       | 3         | 1.31%   |
| Goldmont plus    | 3         | 1.31%   |
| Excavator        | 3         | 1.31%   |
| Core             | 3         | 1.31%   |
| CometLake        | 3         | 1.31%   |
| Bobcat           | 3         | 1.31%   |
| Puma             | 2         | 0.87%   |
| P6               | 2         | 0.87%   |
| Jaguar           | 2         | 0.87%   |
| Bonnell          | 2         | 0.87%   |
| Alderlake Hybrid | 2         | 0.87%   |
| Nehalem          | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 164       | 54.85%  |
| AMD                              | 77        | 25.75%  |
| Nvidia                           | 57        | 19.06%  |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 17        | 5.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 17        | 5.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 15        | 4.84%   |
| Intel UHD Graphics 620                                                                | 14        | 4.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 14        | 4.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 3.55%   |
| Intel HD Graphics 620                                                                 | 11        | 3.55%   |
| Intel HD Graphics 5500                                                                | 10        | 3.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 2.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 2.9%    |
| AMD Renoir                                                                            | 8         | 2.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                   | 6         | 1.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 5         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.61%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 5         | 1.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 5         | 1.61%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 4         | 1.29%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 4         | 1.29%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 1.29%   |
| AMD Lucienne                                                                          | 4         | 1.29%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 0.97%   |
| Nvidia GM108M [GeForce MX110]                                                         | 3         | 0.97%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 3         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 3         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.65%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.65%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 2         | 0.65%   |
| Intel Iris Plus Graphics G7                                                           | 2         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 44.1%   |
| Intel + Nvidia | 42        | 18.34%  |
| 1 x AMD        | 42        | 18.34%  |
| Intel + AMD    | 19        | 8.3%    |
| AMD + Nvidia   | 9         | 3.93%   |
| 2 x AMD        | 7         | 3.06%   |
| 1 x Nvidia     | 6         | 2.62%   |
| 2 x Intel      | 2         | 0.87%   |
| 1 x SiS        | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 196       | 84.48%  |
| Proprietary | 31        | 13.36%  |
| Unknown     | 5         | 2.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 131       | 55.74%  |
| 1.01-2.0   | 41        | 17.45%  |
| 0.01-0.5   | 34        | 14.47%  |
| 3.01-4.0   | 13        | 5.53%   |
| 0.51-1.0   | 9         | 3.83%   |
| 5.01-6.0   | 5         | 2.13%   |
| 7.01-8.0   | 1         | 0.43%   |
| 8.01-16.0  | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 56        | 21.54%  |
| BOE                 | 47        | 18.08%  |
| Samsung Electronics | 39        | 15%     |
| AU Optronics        | 38        | 14.62%  |
| LG Display          | 28        | 10.77%  |
| PANDA               | 6         | 2.31%   |
| Goldstar            | 6         | 2.31%   |
| Sharp               | 3         | 1.15%   |
| Hewlett-Packard     | 3         | 1.15%   |
| Apple               | 3         | 1.15%   |
| AOC                 | 3         | 1.15%   |
| TMX                 | 2         | 0.77%   |
| Sony                | 2         | 0.77%   |
| Lenovo              | 2         | 0.77%   |
| JRY                 | 2         | 0.77%   |
| HannStar            | 2         | 0.77%   |
| Dell                | 2         | 0.77%   |
| Unknown             | 2         | 0.77%   |
| ViewSonic           | 1         | 0.38%   |
| Unknown (XXX)       | 1         | 0.38%   |
| Panasonic           | 1         | 0.38%   |
| Mi                  | 1         | 0.38%   |
| LGD                 | 1         | 0.38%   |
| LG Philips          | 1         | 0.38%   |
| InnoLux Display     | 1         | 0.38%   |
| InfoVision          | 1         | 0.38%   |
| Hitachi             | 1         | 0.38%   |
| EXP                 | 1         | 0.38%   |
| DZX                 | 1         | 0.38%   |
| CSO                 | 1         | 0.38%   |
| AGO                 | 1         | 0.38%   |
| Acer                | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 4.62%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 6         | 2.31%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 3         | 1.15%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 3         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 1.15%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 3         | 1.15%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.15%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.77%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.77%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.77%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 2         | 0.77%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.77%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 2         | 0.77%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.77%   |
| JRY HDMI JRY2380 1920x1080 530x290mm 23.8-inch                       | 2         | 0.77%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch      | 2         | 0.77%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.77%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.77%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.77%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.77%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.77%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.77%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                 | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.77%   |
| Unknown                                                              | 2         | 0.77%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch               | 1         | 0.38%   |
| Unknown (XXX) MS82PV XXX001A 1360x768 330x210mm 15.4-inch            | 1         | 0.38%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch              | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 130       | 52.21%  |
| 1920x1080 (FHD)   | 76        | 30.52%  |
| 1600x900 (HD+)    | 7         | 2.81%   |
| 3840x2160 (4K)    | 5         | 2.01%   |
| 1280x800 (WXGA)   | 5         | 2.01%   |
| 1360x768          | 4         | 1.61%   |
| 2160x1440         | 3         | 1.2%    |
| 1440x900 (WXGA+)  | 3         | 1.2%    |
| 3200x1800 (QHD+)  | 2         | 0.8%    |
| 1024x600          | 2         | 0.8%    |
| Unknown           | 2         | 0.8%    |
| 640x480           | 1         | 0.4%    |
| 3840x1080         | 1         | 0.4%    |
| 3200x2000         | 1         | 0.4%    |
| 2880x1800         | 1         | 0.4%    |
| 2560x1600         | 1         | 0.4%    |
| 2560x1440 (QHD)   | 1         | 0.4%    |
| 2520x1680         | 1         | 0.4%    |
| 1920x1200 (WUXGA) | 1         | 0.4%    |
| 1280x720 (HD)     | 1         | 0.4%    |
| 1024x768 (XGA)    | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 125       | 48.64%  |
| 13      | 43        | 16.73%  |
| 14      | 35        | 13.62%  |
| 23      | 10        | 3.89%   |
| 18      | 6         | 2.33%   |
| 17      | 6         | 2.33%   |
| 21      | 5         | 1.95%   |
| 11      | 4         | 1.56%   |
| Unknown | 3         | 1.17%   |
| 72      | 2         | 0.78%   |
| 31      | 2         | 0.78%   |
| 24      | 2         | 0.78%   |
| 12      | 2         | 0.78%   |
| 10      | 2         | 0.78%   |
| 84      | 1         | 0.39%   |
| 60      | 1         | 0.39%   |
| 54      | 1         | 0.39%   |
| 48      | 1         | 0.39%   |
| 46      | 1         | 0.39%   |
| 39      | 1         | 0.39%   |
| 27      | 1         | 0.39%   |
| 20      | 1         | 0.39%   |
| 19      | 1         | 0.39%   |
| 16      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 190       | 74.51%  |
| 201-300     | 18        | 7.06%   |
| 501-600     | 13        | 5.1%    |
| 401-500     | 13        | 5.1%    |
| 351-400     | 8         | 3.14%   |
| 1001-1500   | 4         | 1.57%   |
| 1501-2000   | 3         | 1.18%   |
| Unknown     | 3         | 1.18%   |
| 601-700     | 2         | 0.78%   |
| 801-900     | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 203       | 89.04%  |
| 16/10   | 15        | 6.58%   |
| 3/2     | 4         | 1.75%   |
| 4/3     | 3         | 1.32%   |
| Unknown | 3         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 125       | 48.64%  |
| 81-90          | 69        | 26.85%  |
| 201-250        | 15        | 5.84%   |
| 71-80          | 8         | 3.11%   |
| More than 1000 | 6         | 2.33%   |
| 151-200        | 5         | 1.95%   |
| 141-150        | 5         | 1.95%   |
| 51-60          | 4         | 1.56%   |
| 121-130        | 4         | 1.56%   |
| Unknown        | 3         | 1.17%   |
| 351-500        | 2         | 0.78%   |
| 41-50          | 2         | 0.78%   |
| 131-140        | 2         | 0.78%   |
| 501-1000       | 2         | 0.78%   |
| 91-100         | 2         | 0.78%   |
| 61-70          | 1         | 0.39%   |
| 301-350        | 1         | 0.39%   |
| 111-120        | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 129       | 50.99%  |
| 121-160       | 70        | 27.67%  |
| 51-100        | 31        | 12.25%  |
| 161-240       | 9         | 3.56%   |
| 1-50          | 7         | 2.77%   |
| More than 240 | 4         | 1.58%   |
| Unknown       | 3         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 188       | 80.34%  |
| 2     | 37        | 15.81%  |
| 0     | 7         | 2.99%   |
| 3     | 2         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 143       | 40.51%  |
| Intel                            | 82        | 23.23%  |
| Qualcomm Atheros                 | 67        | 18.98%  |
| Broadcom                         | 15        | 4.25%   |
| TP-Link                          | 8         | 2.27%   |
| Ralink                           | 7         | 1.98%   |
| MediaTek                         | 6         | 1.7%    |
| Xiaomi                           | 4         | 1.13%   |
| Marvell Technology Group         | 4         | 1.13%   |
| ASIX Electronics                 | 3         | 0.85%   |
| Samsung Electronics              | 2         | 0.57%   |
| Ralink Technology                | 2         | 0.57%   |
| Motorola PCS                     | 2         | 0.57%   |
| ICS Advent                       | 2         | 0.57%   |
| T & A Mobile Phones              | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Microsoft                        | 1         | 0.28%   |
| Lenovo                           | 1         | 0.28%   |
| Broadcom Limited                 | 1         | 0.28%   |
| Apple                            | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 21.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 6.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 5.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 16        | 3.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 3.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 1.37%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.37%   |
| Intel Wireless 8260                                               | 6         | 1.37%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.37%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.92%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 4         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 4         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.92%   |
| Intel Wireless 7265                                               | 4         | 0.92%   |
| Intel Wireless 7260                                               | 4         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.69%   |
| Intel WiFi Link 5100                                              | 3         | 0.69%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 3         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.69%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 80        | 34.63%  |
| Qualcomm Atheros      | 61        | 26.41%  |
| Realtek Semiconductor | 58        | 25.11%  |
| Broadcom              | 13        | 5.63%   |
| Ralink                | 7         | 3.03%   |
| MediaTek              | 6         | 2.6%    |
| TP-Link               | 3         | 1.3%    |
| Ralink Technology     | 2         | 0.87%   |
| Broadcom Limited      | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 10.82%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 6.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 6.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 3.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 2.6%    |
| Intel Wireless 8265 / 8275                                              | 6         | 2.6%    |
| Intel Wireless 8260                                                     | 6         | 2.6%    |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.16%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.73%   |
| Intel Wireless 7265                                                     | 4         | 1.73%   |
| Intel Wireless 7260                                                     | 4         | 1.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.3%    |
| Intel WiFi Link 5100                                                    | 3         | 1.3%    |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.3%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.87%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.87%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.87%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.87%   |
| TP-Link TL-WN8200ND [Realtek RTL8192CU]                                 | 1         | 0.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 128       | 63.05%  |
| Intel                            | 29        | 14.29%  |
| Qualcomm Atheros                 | 16        | 7.88%   |
| TP-Link                          | 5         | 2.46%   |
| Xiaomi                           | 4         | 1.97%   |
| Marvell Technology Group         | 4         | 1.97%   |
| Broadcom                         | 4         | 1.97%   |
| ASIX Electronics                 | 3         | 1.48%   |
| Motorola PCS                     | 2         | 0.99%   |
| ICS Advent                       | 2         | 0.99%   |
| T & A Mobile Phones              | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Samsung Electronics              | 1         | 0.49%   |
| Microsoft                        | 1         | 0.49%   |
| Lenovo                           | 1         | 0.49%   |
| Apple                            | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 93        | 45.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 13.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 2.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.95%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                            | 4         | 1.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.98%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.98%   |
| Motorola PCS moto g(40) fusion                                                 | 2         | 0.98%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.98%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.98%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.98%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.98%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.98%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.98%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.98%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.49%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.49%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.49%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.49%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.49%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 226       | 53.55%  |
| Ethernet | 195       | 46.21%  |
| Modem    | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 72.87%  |
| Ethernet | 67        | 27.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 175       | 76.42%  |
| 1     | 51        | 22.27%  |
| 0     | 3         | 1.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 185       | 78.72%  |
| Yes  | 50        | 21.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 31.77%  |
| Realtek Semiconductor           | 39        | 20.31%  |
| Qualcomm Atheros Communications | 32        | 16.67%  |
| IMC Networks                    | 15        | 7.81%   |
| Lite-On Technology              | 11        | 5.73%   |
| Toshiba                         | 7         | 3.65%   |
| Ralink                          | 6         | 3.13%   |
| Foxconn / Hon Hai               | 4         | 2.08%   |
| Broadcom                        | 4         | 2.08%   |
| Hewlett-Packard                 | 3         | 1.56%   |
| Apple                           | 3         | 1.56%   |
| Dell                            | 2         | 1.04%   |
| Cambridge Silicon Radio         | 2         | 1.04%   |
| Realtek                         | 1         | 0.52%   |
| Foxconn International           | 1         | 0.52%   |
| Alps Electric                   | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 11.46%  |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 9.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 9.9%    |
| Realtek Bluetooth Radio                             | 18        | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 7.29%   |
| Intel AX201 Bluetooth                               | 10        | 5.21%   |
| Ralink RT3290 Bluetooth                             | 6         | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 3.13%   |
| Intel AX200 Bluetooth                               | 6         | 3.13%   |
| IMC Networks Wireless_Device                        | 5         | 2.6%    |
| IMC Networks Bluetooth Radio                        | 5         | 2.6%    |
| Toshiba Bluetooth Device                            | 4         | 2.08%   |
| IMC Networks Bluetooth Device                       | 4         | 2.08%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.56%   |
| Lite-On Bluetooth Radio                             | 3         | 1.56%   |
| Lite-On Bluetooth Device                            | 3         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.56%   |
| Intel Bluetooth Device                              | 3         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 1.04%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.04%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.52%   |
| Toshiba BCM43142A0                                  | 1         | 0.52%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.52%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.52%   |
| Realtek Bluetooth Radio                             | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.52%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 171       | 63.33%  |
| AMD                              | 59        | 21.85%  |
| Nvidia                           | 28        | 10.37%  |
| Generalplus Technology           | 3         | 1.11%   |
| C-Media Electronics              | 3         | 1.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Razer USA                        | 1         | 0.37%   |
| Pixart Imaging                   | 1         | 0.37%   |
| Kingston Technology              | 1         | 0.37%   |
| Hewlett-Packard                  | 1         | 0.37%   |
| GN Netcom                        | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 11.46%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 10.6%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 5.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 4.58%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 4.01%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 3.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.87%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.29%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.86%   |
| Nvidia Audio device                                                                               | 3         | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.86%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.86%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 29.94%  |
| SK hynix            | 37        | 20.9%   |
| Micron Technology   | 27        | 15.25%  |
| Kingston            | 22        | 12.43%  |
| Unknown             | 10        | 5.65%   |
| Ramaxel Technology  | 10        | 5.65%   |
| Team                | 4         | 2.26%   |
| Unknown (ABCD)      | 3         | 1.69%   |
| Hewlett-Packard     | 2         | 1.13%   |
| Elpida              | 2         | 1.13%   |
| Crucial             | 2         | 1.13%   |
| Patriot             | 1         | 0.56%   |
| Kllisre             | 1         | 0.56%   |
| Goldkey             | 1         | 0.56%   |
| CSX                 | 1         | 0.56%   |
| Corsair             | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 3.19%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 2.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 2.66%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.6%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 3         | 1.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.6%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.6%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.6%    |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM 1600MT/s               | 3         | 1.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.06%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.06%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.06%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.06%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.06%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.06%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.06%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.06%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.53%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.53%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 63        | 47.37%  |
| DDR3    | 49        | 36.84%  |
| LPDDR4  | 9         | 6.77%   |
| DDR2    | 4         | 3.01%   |
| LPDDR3  | 3         | 2.26%   |
| SDRAM   | 2         | 1.5%    |
| DDR5    | 2         | 1.5%    |
| Unknown | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 126       | 94.74%  |
| Row Of Chips | 7         | 5.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 65        | 41.14%  |
| 4096  | 59        | 37.34%  |
| 16384 | 13        | 8.23%   |
| 2048  | 13        | 8.23%   |
| 1024  | 4         | 2.53%   |
| 32768 | 3         | 1.9%    |
| 512   | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 42        | 27.45%  |
| 1600    | 40        | 26.14%  |
| 3200    | 28        | 18.3%   |
| 2400    | 9         | 5.88%   |
| 3266    | 6         | 3.92%   |
| 1333    | 5         | 3.27%   |
| 1334    | 4         | 2.61%   |
| 2133    | 3         | 1.96%   |
| Unknown | 3         | 1.96%   |
| 4800    | 2         | 1.31%   |
| 1867    | 2         | 1.31%   |
| 1067    | 2         | 1.31%   |
| 4267    | 1         | 0.65%   |
| 4199    | 1         | 0.65%   |
| 2933    | 1         | 0.65%   |
| 1066    | 1         | 0.65%   |
| 800     | 1         | 0.65%   |
| 667     | 1         | 0.65%   |
| 533     | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon               | 2         | 33.33%  |
| Seiko Epson         | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |
| Hewlett-Packard     | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series       | 1         | 16.67%  |
| Prolific PL2305 Parallel Port    | 1         | 16.67%  |
| HP LaserJet Professional P 1102w | 1         | 16.67%  |
| Canon G2010 series               | 1         | 16.67%  |
| Canon E400 series                | 1         | 16.67%  |
| Brother DCP-T300                 | 1         | 16.67%  |

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


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 47        | 21.66%  |
| IMC Networks                           | 25        | 11.52%  |
| Microdia                               | 18        | 8.29%   |
| Realtek Semiconductor                  | 16        | 7.37%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 5.99%   |
| Bison Electronics                      | 13        | 5.99%   |
| Syntek                                 | 12        | 5.53%   |
| Sunplus Innovation Technology          | 11        | 5.07%   |
| Lite-On Technology                     | 11        | 5.07%   |
| Suyin                                  | 10        | 4.61%   |
| Quanta                                 | 10        | 4.61%   |
| Acer                                   | 9         | 4.15%   |
| Luxvisions Innotech Limited            | 4         | 1.84%   |
| Importek                               | 4         | 1.84%   |
| Sonix Technology                       | 3         | 1.38%   |
| Samsung Electronics                    | 2         | 0.92%   |
| Ricoh                                  | 2         | 0.92%   |
| Apple                                  | 2         | 0.92%   |
| Alcor Micro                            | 2         | 0.92%   |
| Logitech                               | 1         | 0.46%   |
| ASUSTek Computer                       | 1         | 0.46%   |
| ANYKA                                  | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                        | 9         | 4.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 8         | 3.67%   |
| Lite-On Integrated Camera                                       | 5         | 2.29%   |
| Chicony Integrated Camera                                       | 5         | 2.29%   |
| Chicony HP Truevision HD                                        | 5         | 2.29%   |
| Chicony EasyCamera                                              | 5         | 2.29%   |
| Acer Integrated Camera                                          | 5         | 2.29%   |
| Sunplus Integrated_Webcam_HD                                    | 4         | 1.83%   |
| Realtek Integrated_Webcam_HD                                    | 4         | 1.83%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 1.83%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 4         | 1.83%   |
| IMC Networks Integrated Camera                                  | 4         | 1.83%   |
| Chicony TOSHIBA Web Camera - HD                                 | 4         | 1.83%   |
| Chicony HP TrueVision HD Camera                                 | 4         | 1.83%   |
| Chicony HD WebCam                                               | 4         | 1.83%   |
| Bison Integrated Camera                                         | 4         | 1.83%   |
| Sonix USB2.0 HD UVC WebCam                                      | 3         | 1.38%   |
| Microdia Webcam Vitade AF                                       | 3         | 1.38%   |
| Lite-On HP HD Camera                                            | 3         | 1.38%   |
| IMC Networks HP TrueVision HD Camera                            | 3         | 1.38%   |
| Chicony Lenovo EasyCamera                                       | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 3         | 1.38%   |
| Suyin 1.3M HD WebCam                                            | 2         | 0.92%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 2         | 0.92%   |
| Ricoh Sony Vaio Integrated Webcam                               | 2         | 0.92%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 0.92%   |
| Realtek Integrated Webcam                                       | 2         | 0.92%   |
| Realtek HP Wide Vision HD Camera                                | 2         | 0.92%   |
| Quanta HP Webcam                                                | 2         | 0.92%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 0.92%   |
| IMC Networks HD Camera                                          | 2         | 0.92%   |
| Chicony VGA Webcam                                              | 2         | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 2         | 0.92%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 0.92%   |
| Chicony HP Webcam                                               | 2         | 0.92%   |
| Chicony HP HD Camera                                            | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 50%     |
| Synaptics                  | 12        | 26.09%  |
| Shenzhen Goodix Technology | 5         | 10.87%  |
| Elan Microelectronics      | 4         | 8.7%    |
| STMicroelectronics         | 1         | 2.17%   |
| AuthenTec                  | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 7         | 15.22%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 15.22%  |
| Synaptics  WBDI                                            | 4         | 8.7%    |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 6.52%   |
| Elan ELAN:Fingerprint                                      | 3         | 6.52%   |
| Validity Sensors Synaptics WBDI                            | 2         | 4.35%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                  | 2         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 2.17%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.17%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 2.17%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.17%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.17%   |
| Synaptics WBDI                                             | 1         | 2.17%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.17%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.17%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.17%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.17%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 33.33%  |
| Alcor Micro | 4         | 33.33%  |
| Upek        | 3         | 25%     |
| O2 Micro    | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 141       | 60.26%  |
| 1     | 76        | 32.48%  |
| 2     | 15        | 6.41%   |
| 3     | 2         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 42.2%   |
| Graphics card            | 19        | 17.43%  |
| Net/wireless             | 12        | 11.01%  |
| Chipcard                 | 11        | 10.09%  |
| Bluetooth                | 8         | 7.34%   |
| Multimedia controller    | 5         | 4.59%   |
| Storage                  | 2         | 1.83%   |
| Card reader              | 2         | 1.83%   |
| Camera                   | 2         | 1.83%   |
| Net/ethernet             | 1         | 0.92%   |
| Communication controller | 1         | 0.92%   |

