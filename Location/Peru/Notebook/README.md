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

Total: 356

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Chuwi      | GemiBook Pro                | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| HP         | Laptop 15-dw0xxx            | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Lenovo     | IdeaPad S145-14AST 81ST     | [c51105da6a](https://linux-hardware.org/?probe=c51105da6a) | Jul 28, 2023 |
| Lenovo     | IdeaPad 330-15IKB 81DE      | [8cde0390c4](https://linux-hardware.org/?probe=8cde0390c4) | Jul 26, 2023 |
| HP         | ProBook 440 G2              | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP         | Compaq Presario C700        | [71ca83faee](https://linux-hardware.org/?probe=71ca83faee) | Jul 23, 2023 |
| Lenovo     | IdeaPad 3 15ITL6 82H8       | [c7a062709f](https://linux-hardware.org/?probe=c7a062709f) | Jul 17, 2023 |
| Lenovo     | IdeaPad 3 15ITL6 82H8       | [51128412d5](https://linux-hardware.org/?probe=51128412d5) | Jul 16, 2023 |
| Acer       | Predator PH16-71            | [1917d24a87](https://linux-hardware.org/?probe=1917d24a87) | Jul 15, 2023 |
| HP         | Compaq Presario C700        | [32659f379c](https://linux-hardware.org/?probe=32659f379c) | Jul 09, 2023 |
| HP         | 240 G7 Notebook PC          | [e7d87f5a64](https://linux-hardware.org/?probe=e7d87f5a64) | Jul 07, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop M160... | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X515... | [335f69285d](https://linux-hardware.org/?probe=335f69285d) | Jul 05, 2023 |
| HP         | 250 G5 Notebook PC          | [99c60820c5](https://linux-hardware.org/?probe=99c60820c5) | Jul 05, 2023 |
| Lenovo     | IdeaPad 3 14ADA05 81W0      | [2b4069db98](https://linux-hardware.org/?probe=2b4069db98) | Jun 25, 2023 |
| ASUSTek    | ROG Strix G513RC_G513RC     | [1d6a241c9e](https://linux-hardware.org/?probe=1d6a241c9e) | Jun 23, 2023 |
| Chuwi      | GemiBook Pro                | [34cfc4a037](https://linux-hardware.org/?probe=34cfc4a037) | Jun 13, 2023 |
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
| Ubuntu 20.04                 | 32        | 12.26%  |
| Arch Rolling                 | 11        | 4.21%   |
| OpenMandriva 4.3             | 10        | 3.83%   |
| Ubuntu 22.04                 | 9         | 3.45%   |
| Ubuntu 18.04                 | 9         | 3.45%   |
| Linux Mint 21.1              | 9         | 3.45%   |
| OpenMandriva 23.03           | 7         | 2.68%   |
| Zorin 15                     | 6         | 2.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 2.3%    |
| Manjaro                      | 6         | 2.3%    |
| Linux Mint 20.3              | 6         | 2.3%    |
| Fedora 38                    | 6         | 2.3%    |
| Ubuntu 19.10                 | 5         | 1.92%   |
| Fedora 37                    | 5         | 1.92%   |
| Arch                         | 5         | 1.92%   |
| Xubuntu 20.04                | 4         | 1.53%   |
| Ubuntu 21.04                 | 4         | 1.53%   |
| Pop!_OS 21.10                | 4         | 1.53%   |
| OpenMandriva 23.01           | 4         | 1.53%   |
| Debian 11                    | 4         | 1.53%   |
| Ubuntu 19.04                 | 3         | 1.15%   |
| Pop!_OS 22.04                | 3         | 1.15%   |
| Pop!_OS 20.10                | 3         | 1.15%   |
| OpenMandriva 4.2             | 3         | 1.15%   |
| Manjaro 20.1                 | 3         | 1.15%   |
| KDE neon 20.04               | 3         | 1.15%   |
| Fedora 35                    | 3         | 1.15%   |
| Elementary 5.1.7             | 3         | 1.15%   |
| Debian 10                    | 3         | 1.15%   |
| ArcoLinux Rolling            | 3         | 1.15%   |
| ROSA R9                      | 2         | 0.77%   |
| ROSA R10                     | 2         | 0.77%   |
| ROSA 12.3                    | 2         | 0.77%   |
| ROSA 12.2                    | 2         | 0.77%   |
| Pop!_OS 20.04                | 2         | 0.77%   |
| OpenMandriva 4.90            | 2         | 0.77%   |
| OpenMandriva 23.06           | 2         | 0.77%   |
| LMDE 5                       | 2         | 0.77%   |
| Linux Mint 20                | 2         | 0.77%   |
| Kubuntu 23.04                | 2         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 63        | 24.8%   |
| OpenMandriva  | 28        | 11.02%  |
| Linux Mint    | 20        | 7.87%   |
| Fedora        | 20        | 7.87%   |
| Arch          | 17        | 6.69%   |
| Pop!_OS       | 13        | 5.12%   |
| Manjaro       | 13        | 5.12%   |
| Debian        | 10        | 3.94%   |
| ROSA          | 9         | 3.54%   |
| Zorin         | 7         | 2.76%   |
| openSUSE      | 6         | 2.36%   |
| Xubuntu       | 4         | 1.57%   |
| Kubuntu       | 4         | 1.57%   |
| KDE neon      | 4         | 1.57%   |
| Elementary    | 4         | 1.57%   |
| Endless       | 3         | 1.18%   |
| ArcoLinux     | 3         | 1.18%   |
| Ubuntu MATE   | 2         | 0.79%   |
| SteamOS       | 2         | 0.79%   |
| Parrot        | 2         | 0.79%   |
| Lubuntu       | 2         | 0.79%   |
| LMDE          | 2         | 0.79%   |
| Kali          | 2         | 0.79%   |
| EndeavourOS   | 2         | 0.79%   |
| CentOS        | 2         | 0.79%   |
| Void Linux    | 1         | 0.39%   |
| Ubuntu Unity  | 1         | 0.39%   |
| Ubuntu Studio | 1         | 0.39%   |
| Ubuntu Budgie | 1         | 0.39%   |
| Peppermint    | 1         | 0.39%   |
| NixOS         | 1         | 0.39%   |
| MX            | 1         | 0.39%   |
| Laxer OS      | 1         | 0.39%   |
| Clear Linux   | 1         | 0.39%   |
| Artix         | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 10        | 3.51%   |
| 6.2.6-desktop-1omv2390   | 6         | 2.11%   |
| 5.13.0-40-generic        | 5         | 1.75%   |
| 5.4.0-42-generic         | 4         | 1.4%    |
| 6.3.5-desktop-3omv2390   | 3         | 1.05%   |
| 6.3.5-200.fc38.x86_64    | 3         | 1.05%   |
| 5.4.0-26-generic         | 3         | 1.05%   |
| 5.3.0-40-generic         | 3         | 1.05%   |
| 5.15.0-71-generic        | 3         | 1.05%   |
| 5.13.0-51-generic        | 3         | 1.05%   |
| 5.11.0-25-generic        | 3         | 1.05%   |
| 5.10.0-13-amd64          | 3         | 1.05%   |
| 6.3.6-arch1-1            | 2         | 0.7%    |
| 6.2.0-24-generic         | 2         | 0.7%    |
| 6.1.4-desktop-1omv2301   | 2         | 0.7%    |
| 6.1.1-desktop-1omv2290   | 2         | 0.7%    |
| 5.8.0-44-generic         | 2         | 0.7%    |
| 5.4.0-7642-generic       | 2         | 0.7%    |
| 5.4.0-66-generic         | 2         | 0.7%    |
| 5.4.0-65-generic         | 2         | 0.7%    |
| 5.4.0-58-generic         | 2         | 0.7%    |
| 5.4.0-54-generic         | 2         | 0.7%    |
| 5.4.0-39-generic         | 2         | 0.7%    |
| 5.4.0-33-generic         | 2         | 0.7%    |
| 5.4.0-28-generic         | 2         | 0.7%    |
| 5.4.0-109-generic        | 2         | 0.7%    |
| 5.3.0-42-generic         | 2         | 0.7%    |
| 5.3.0-23-generic         | 2         | 0.7%    |
| 5.18.12-desktop-3omv4090 | 2         | 0.7%    |
| 5.17.5-arch1-1           | 2         | 0.7%    |
| 5.16.19-76051619-generic | 2         | 0.7%    |
| 5.15.49-1-lts            | 2         | 0.7%    |
| 5.15.0-76-generic        | 2         | 0.7%    |
| 5.15.0-58-generic        | 2         | 0.7%    |
| 5.15.0-57-generic        | 2         | 0.7%    |
| 5.15.0-52-generic        | 2         | 0.7%    |
| 5.15.0-25-generic        | 2         | 0.7%    |
| 5.13.0-30-generic        | 2         | 0.7%    |
| 5.11.0-7614-generic      | 2         | 0.7%    |
| 5.10.14-desktop-1omv4002 | 2         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 13.77%  |
| 5.15.0  | 21        | 7.61%   |
| 5.13.0  | 14        | 5.07%   |
| 5.11.0  | 14        | 5.07%   |
| 5.3.0   | 12        | 4.35%   |
| 5.16.7  | 10        | 3.62%   |
| 6.2.6   | 7         | 2.54%   |
| 5.8.0   | 7         | 2.54%   |
| 5.10.0  | 7         | 2.54%   |
| 5.0.0   | 7         | 2.54%   |
| 4.15.0  | 7         | 2.54%   |
| 6.3.5   | 6         | 2.17%   |
| 4.18.0  | 6         | 2.17%   |
| 5.19.0  | 5         | 1.81%   |
| 6.3.6   | 4         | 1.45%   |
| 6.2.0   | 4         | 1.45%   |
| 6.0.0   | 3         | 1.09%   |
| 5.17.5  | 3         | 1.09%   |
| 4.9.60  | 3         | 1.09%   |
| 6.1.9   | 2         | 0.72%   |
| 6.1.4   | 2         | 0.72%   |
| 6.1.31  | 2         | 0.72%   |
| 6.1.11  | 2         | 0.72%   |
| 6.1.1   | 2         | 0.72%   |
| 6.0.7   | 2         | 0.72%   |
| 6.0.15  | 2         | 0.72%   |
| 5.18.12 | 2         | 0.72%   |
| 5.16.19 | 2         | 0.72%   |
| 5.15.49 | 2         | 0.72%   |
| 5.12.10 | 2         | 0.72%   |
| 5.10.14 | 2         | 0.72%   |
| 4.9.20  | 2         | 0.72%   |
| 4.19.0  | 2         | 0.72%   |
| 6.4.6   | 1         | 0.36%   |
| 6.4.5   | 1         | 0.36%   |
| 6.4.3   | 1         | 0.36%   |
| 6.3.9   | 1         | 0.36%   |
| 6.3.8   | 1         | 0.36%   |
| 6.3.4   | 1         | 0.36%   |
| 6.2.9   | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 15.24%  |
| 5.15    | 33        | 12.27%  |
| 6.2     | 17        | 6.32%   |
| 5.13    | 15        | 5.58%   |
| 5.11    | 15        | 5.58%   |
| 5.10    | 14        | 5.2%    |
| 6.1     | 13        | 4.83%   |
| 5.16    | 13        | 4.83%   |
| 6.3     | 12        | 4.46%   |
| 6.0     | 12        | 4.46%   |
| 5.3     | 12        | 4.46%   |
| 5.8     | 10        | 3.72%   |
| 5.19    | 7         | 2.6%    |
| 5.17    | 7         | 2.6%    |
| 5.0     | 7         | 2.6%    |
| 4.15    | 7         | 2.6%    |
| 4.18    | 6         | 2.23%   |
| 5.18    | 4         | 1.49%   |
| 5.12    | 4         | 1.49%   |
| 4.9     | 4         | 1.49%   |
| 6.4     | 3         | 1.12%   |
| 5.14    | 3         | 1.12%   |
| 5.9     | 2         | 0.74%   |
| 5.7     | 2         | 0.74%   |
| 5.6     | 2         | 0.74%   |
| 4.19    | 2         | 0.74%   |
| 5.1     | 1         | 0.37%   |
| 4.16    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 236       | 96.72%  |
| i686   | 8         | 3.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 109       | 43.08%  |
| KDE5            | 52        | 20.55%  |
| XFCE            | 20        | 7.91%   |
| X-Cinnamon      | 17        | 6.72%   |
| Unknown         | 16        | 6.32%   |
| MATE            | 7         | 2.77%   |
| KDE             | 7         | 2.77%   |
| Pantheon        | 4         | 1.58%   |
| KDE4            | 4         | 1.58%   |
| i3              | 4         | 1.58%   |
| LXQt            | 3         | 1.19%   |
| sway            | 2         | 0.79%   |
| LXDE            | 2         | 0.79%   |
| Budgie          | 2         | 0.79%   |
| Unity           | 1         | 0.4%    |
| spectrwm        | 1         | 0.4%    |
| GNOME Flashback | 1         | 0.4%    |
| Deepin          | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 184       | 72.73%  |
| Wayland | 51        | 20.16%  |
| Unknown | 15        | 5.93%   |
| Tty     | 3         | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 115       | 45.82%  |
| SDDM    | 44        | 17.53%  |
| GDM     | 38        | 15.14%  |
| LightDM | 28        | 11.16%  |
| GDM3    | 17        | 6.77%   |
| KDM     | 4         | 1.59%   |
| TDM     | 2         | 0.8%    |
| XDM     | 1         | 0.4%    |
| Ly      | 1         | 0.4%    |
| LXDM    | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 118       | 47.2%   |
| en_US   | 71        | 28.4%   |
| es_ES   | 23        | 9.2%    |
| Unknown | 16        | 6.4%    |
| es_MX   | 6         | 2.4%    |
| C       | 4         | 1.6%    |
| it_IT   | 2         | 0.8%    |
| fr_FR   | 2         | 0.8%    |
| en_GB   | 2         | 0.8%    |
| ca_ES   | 2         | 0.8%    |
| es_VE   | 1         | 0.4%    |
| es_CO   | 1         | 0.4%    |
| en_NZ   | 1         | 0.4%    |
| Default | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 140       | 56.68%  |
| BIOS | 107       | 43.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 187       | 74.5%   |
| Btrfs   | 27        | 10.76%  |
| Overlay | 21        | 8.37%   |
| Unknown | 7         | 2.79%   |
| Xfs     | 6         | 2.39%   |
| Tmpfs   | 2         | 0.8%    |
| Ext3    | 1         | 0.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 125       | 50.4%   |
| GPT     | 100       | 40.32%  |
| MBR     | 23        | 9.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 216       | 87.1%   |
| Yes       | 32        | 12.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 145       | 58.47%  |
| Yes       | 103       | 41.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 65        | 26.75%  |
| Lenovo              | 64        | 26.34%  |
| ASUSTek Computer    | 31        | 12.76%  |
| Dell                | 23        | 9.47%   |
| Toshiba             | 16        | 6.58%   |
| Acer                | 16        | 6.58%   |
| Sony                | 5         | 2.06%   |
| Chuwi               | 5         | 2.06%   |
| MSI                 | 4         | 1.65%   |
| HUAWEI              | 3         | 1.23%   |
| Apple               | 3         | 1.23%   |
| Advance             | 2         | 0.82%   |
| Samsung Electronics | 1         | 0.41%   |
| Razer               | 1         | 0.41%   |
| eMachines           | 1         | 0.41%   |
| efirstview          | 1         | 0.41%   |
| Compal              | 1         | 0.41%   |
| Unknown             | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                       | 5         | 2.06%   |
| Lenovo V330-15IKB 81AX                   | 4         | 1.65%   |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 1.65%   |
| HP 14                                    | 4         | 1.65%   |
| Lenovo V310-15ISK 80SY                   | 3         | 1.23%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 3         | 1.23%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 1.23%   |
| Toshiba Satellite L45-B                  | 2         | 0.82%   |
| Toshiba Satellite C45-A                  | 2         | 0.82%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.82%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.82%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.82%   |
| Lenovo G400 20235                        | 2         | 0.82%   |
| HP ProBook 645 G4                        | 2         | 0.82%   |
| HP Pavilion g4                           | 2         | 0.82%   |
| HP Notebook                              | 2         | 0.82%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.82%   |
| HP Compaq Presario C700                  | 2         | 0.82%   |
| HP 450                                   | 2         | 0.82%   |
| HP 250 G7 Notebook PC                    | 2         | 0.82%   |
| HP 250 G5 Notebook PC                    | 2         | 0.82%   |
| Dell XPS 13 9360                         | 2         | 0.82%   |
| Dell Latitude E7450                      | 2         | 0.82%   |
| Dell G5 5505                             | 2         | 0.82%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR     | 2         | 0.82%   |
| ASUS ROG Strix G513RC_G513RC             | 2         | 0.82%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.82%   |
| Apple MacBookPro9,2                      | 2         | 0.82%   |
| Toshiba Satellite P755                   | 1         | 0.41%   |
| Toshiba Satellite P300                   | 1         | 0.41%   |
| Toshiba Satellite L855                   | 1         | 0.41%   |
| Toshiba Satellite L35                    | 1         | 0.41%   |
| Toshiba Satellite E205                   | 1         | 0.41%   |
| Toshiba Satellite C845                   | 1         | 0.41%   |
| Toshiba Satellite C655D                  | 1         | 0.41%   |
| Toshiba Satellite C645                   | 1         | 0.41%   |
| Toshiba Satellite C55-B                  | 1         | 0.41%   |
| Toshiba Satellite A665                   | 1         | 0.41%   |
| Toshiba QOSMIO X775                      | 1         | 0.41%   |
| Toshiba NB505                            | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 22        | 9.05%   |
| Lenovo ThinkPad   | 17        | 7%      |
| HP Pavilion       | 17        | 7%      |
| Toshiba Satellite | 14        | 5.76%   |
| Acer Aspire       | 13        | 5.35%   |
| ASUS VivoBook     | 12        | 4.94%   |
| HP ProBook        | 9         | 3.7%    |
| HP Laptop         | 9         | 3.7%    |
| Dell Latitude     | 9         | 3.7%    |
| Dell Inspiron     | 7         | 2.88%   |
| Lenovo Legion     | 5         | 2.06%   |
| Chuwi GemiBook    | 5         | 2.06%   |
| ASUS ROG          | 5         | 2.06%   |
| Lenovo V330-15IKB | 4         | 1.65%   |
| HP 250            | 4         | 1.65%   |
| HP 14             | 4         | 1.65%   |
| Lenovo V310-15ISK | 3         | 1.23%   |
| HP Compaq         | 3         | 1.23%   |
| ASUS ASUS         | 3         | 1.23%   |
| Lenovo G400       | 2         | 0.82%   |
| HP ZBook          | 2         | 0.82%   |
| HP Notebook       | 2         | 0.82%   |
| HP ENVY           | 2         | 0.82%   |
| HP EliteBook      | 2         | 0.82%   |
| HP 450            | 2         | 0.82%   |
| HP 255            | 2         | 0.82%   |
| HP 240            | 2         | 0.82%   |
| Dell XPS          | 2         | 0.82%   |
| Dell G5           | 2         | 0.82%   |
| Apple MacBookPro9 | 2         | 0.82%   |
| Toshiba QOSMIO    | 1         | 0.41%   |
| Toshiba NB505     | 1         | 0.41%   |
| Sony VPCEL36FJ    | 1         | 0.41%   |
| Sony VPCEC2JFX    | 1         | 0.41%   |
| Sony VGN-FW56M    | 1         | 0.41%   |
| Sony VGN-FW170J   | 1         | 0.41%   |
| Sony SVF15A17CLB  | 1         | 0.41%   |
| Samsung 300E5EV   | 1         | 0.41%   |
| Razer Blade       | 1         | 0.41%   |
| MSI PS42          | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 27        | 11.11%  |
| 2019 | 27        | 11.11%  |
| 2021 | 24        | 9.88%   |
| 2018 | 22        | 9.05%   |
| 2016 | 20        | 8.23%   |
| 2012 | 20        | 8.23%   |
| 2014 | 19        | 7.82%   |
| 2017 | 18        | 7.41%   |
| 2013 | 18        | 7.41%   |
| 2011 | 16        | 6.58%   |
| 2022 | 6         | 2.47%   |
| 2015 | 6         | 2.47%   |
| 2010 | 6         | 2.47%   |
| 2009 | 4         | 1.65%   |
| 2008 | 4         | 1.65%   |
| 2007 | 4         | 1.65%   |
| 2023 | 1         | 0.41%   |
| 2006 | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 243       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 219       | 89.75%  |
| Enabled  | 25        | 10.25%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 243       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 30.12%  |
| 8.01-16.0   | 73        | 29.32%  |
| 3.01-4.0    | 43        | 17.27%  |
| 16.01-24.0  | 31        | 12.45%  |
| 1.01-2.0    | 9         | 3.61%   |
| 32.01-64.0  | 6         | 2.41%   |
| 2.01-3.0    | 6         | 2.41%   |
| 24.01-32.0  | 3         | 1.2%    |
| 0.51-1.0    | 2         | 0.8%    |
| 64.01-256.0 | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 82        | 30.48%  |
| 1.01-2.0   | 80        | 29.74%  |
| 4.01-8.0   | 42        | 15.61%  |
| 3.01-4.0   | 35        | 13.01%  |
| 0.51-1.0   | 19        | 7.06%   |
| 8.01-16.0  | 9         | 3.35%   |
| 16.01-24.0 | 1         | 0.37%   |
| 0.01-0.5   | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 180       | 73.47%  |
| 2      | 58        | 23.67%  |
| 3      | 6         | 2.45%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 159       | 65.43%  |
| Yes       | 84        | 34.57%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 81.97%  |
| No        | 44        | 18.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 240       | 98.77%  |
| No        | 3         | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 84.02%  |
| No        | 39        | 15.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 243       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 162       | 64.29%  |
| Arequipa              | 23        | 9.13%   |
| Trujillo              | 16        | 6.35%   |
| Huancayo              | 7         | 2.78%   |
| Piura                 | 6         | 2.38%   |
| Cusco                 | 6         | 2.38%   |
| Chiclayo              | 5         | 1.98%   |
| Ica                   | 3         | 1.19%   |
| Tacna                 | 2         | 0.79%   |
| La Victoria           | 2         | 0.79%   |
| Callao                | 2         | 0.79%   |
| Santiago de Surco     | 1         | 0.4%    |
| San Vicente de Canete | 1         | 0.4%    |
| San Isidro            | 1         | 0.4%    |
| San Borja             | 1         | 0.4%    |
| Punta Colorada        | 1         | 0.4%    |
| Puno                  | 1         | 0.4%    |
| Pisco                 | 1         | 0.4%    |
| Oxapampa              | 1         | 0.4%    |
| Moquegua              | 1         | 0.4%    |
| Lurin                 | 1         | 0.4%    |
| Juliaca               | 1         | 0.4%    |
| Iquitos               | 1         | 0.4%    |
| Huaraz                | 1         | 0.4%    |
| Distrito de Lima      | 1         | 0.4%    |
| Cajamarca             | 1         | 0.4%    |
| Barranco              | 1         | 0.4%    |
| Ayacucho              | 1         | 0.4%    |
| Abancay               | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 48        | 55     | 15.74%  |
| Toshiba                        | 43        | 53     | 14.1%   |
| Seagate                        | 39        | 45     | 12.79%  |
| Kingston                       | 35        | 43     | 11.48%  |
| Samsung Electronics            | 17        | 25     | 5.57%   |
| SanDisk                        | 15        | 18     | 4.92%   |
| Crucial                        | 13        | 18     | 4.26%   |
| Unknown                        | 9         | 9      | 2.95%   |
| Micron Technology              | 9         | 10     | 2.95%   |
| SK hynix                       | 7         | 10     | 2.3%    |
| Intel                          | 7         | 9      | 2.3%    |
| KIOXIA                         | 6         | 7      | 1.97%   |
| Hitachi                        | 6         | 8      | 1.97%   |
| HGST                           | 6         | 6      | 1.97%   |
| Netac                          | 5         | 5      | 1.64%   |
| Hewlett-Packard                | 5         | 5      | 1.64%   |
| TO Exter                       | 3         | 7      | 0.98%   |
| LITEON                         | 3         | 3      | 0.98%   |
| UMIS                           | 2         | 2      | 0.66%   |
| Silicon Motion                 | 2         | 2      | 0.66%   |
| Kingston Technology Company    | 2         | 2      | 0.66%   |
| Gigabyte Technology            | 2         | 2      | 0.66%   |
| China                          | 2         | 2      | 0.66%   |
| Apple                          | 2         | 2      | 0.66%   |
| Unknown                        | 2         | 2      | 0.66%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.33%   |
| SSSTC                          | 1         | 1      | 0.33%   |
| Solid State Storage Technology | 1         | 1      | 0.33%   |
| Reletech-P400                  | 1         | 1      | 0.33%   |
| Phison Electronics             | 1         | 1      | 0.33%   |
| Phison                         | 1         | 1      | 0.33%   |
| Micron/Crucial Technology      | 1         | 4      | 0.33%   |
| KingSpec                       | 1         | 1      | 0.33%   |
| ITHOO                          | 1         | 1      | 0.33%   |
| GLOWAY                         | 1         | 1      | 0.33%   |
| Fujitsu                        | 1         | 1      | 0.33%   |
| Dogfish                        | 1         | 1      | 0.33%   |
| Biwin Storage Technology       | 1         | 3      | 0.33%   |
| ACASIS                         | 1         | 1      | 0.33%   |
| A-DATA Technology              | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 16        | 5.11%   |
| Kingston SA400S37240G 240GB SSD      | 15        | 4.79%   |
| Toshiba MQ04ABF100 1TB               | 9         | 2.88%   |
| Toshiba MQ01ABD100 1TB               | 9         | 2.88%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 7         | 2.24%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.6%    |
| Netac SSD 256GB                      | 5         | 1.6%    |
| Crucial CT500MX500SSD4 500GB         | 5         | 1.6%    |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 1.28%   |
| Unknown SD32G  32GB                  | 4         | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.28%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 1.28%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 1.28%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 0.96%   |
| Toshiba MQ01ABD075 752GB             | 3         | 0.96%   |
| TO Exter nal USB 3.0 1TB             | 3         | 0.96%   |
| Seagate ST9500325AS 500GB            | 3         | 0.96%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.96%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.96%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 3         | 0.96%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.96%   |
| HP SSD S700 500GB                    | 3         | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.64%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.64%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.64%   |
| Unknown MMC Card  32GB               | 2         | 0.64%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.64%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.64%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.64%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.64%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.64%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.64%   |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.64%   |
| Kingston SNVS500G 500GB              | 2         | 0.64%   |
| Kingston SA400S37960G 960GB SSD      | 2         | 0.64%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.64%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.64%   |
| Unknown                              | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 41        | 51     | 33.06%  |
| Seagate | 39        | 44     | 31.45%  |
| WDC     | 29        | 32     | 23.39%  |
| Hitachi | 6         | 8      | 4.84%   |
| HGST    | 6         | 6      | 4.84%   |
| Fujitsu | 1         | 1      | 0.81%   |
| Apple   | 1         | 1      | 0.81%   |
| ACASIS  | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 30        | 36     | 31.25%  |
| WDC                 | 15        | 17     | 15.63%  |
| Crucial             | 12        | 16     | 12.5%   |
| SanDisk             | 5         | 7      | 5.21%   |
| Netac               | 5         | 5      | 5.21%   |
| Hewlett-Packard     | 5         | 5      | 5.21%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| TO Exter            | 3         | 7      | 3.13%   |
| LITEON              | 3         | 3      | 3.13%   |
| China               | 2         | 2      | 2.08%   |
| Toshiba             | 1         | 1      | 1.04%   |
| SSSTC               | 1         | 1      | 1.04%   |
| SK hynix            | 1         | 4      | 1.04%   |
| Seagate             | 1         | 1      | 1.04%   |
| Reletech-P400       | 1         | 1      | 1.04%   |
| KingSpec            | 1         | 1      | 1.04%   |
| GLOWAY              | 1         | 1      | 1.04%   |
| Gigabyte Technology | 1         | 1      | 1.04%   |
| Dogfish             | 1         | 1      | 1.04%   |
| Apple               | 1         | 1      | 1.04%   |
| A-DATA Technology   | 1         | 1      | 1.04%   |
| Unknown             | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 123       | 144    | 42.41%  |
| SSD     | 84        | 117    | 28.97%  |
| NVMe    | 73        | 99     | 25.17%  |
| MMC     | 9         | 9      | 3.1%    |
| Unknown | 1         | 1      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 179       | 253    | 67.29%  |
| NVMe | 73        | 99     | 27.44%  |
| MMC  | 9         | 9      | 3.38%   |
| SAS  | 5         | 9      | 1.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 108       | 146    | 53.73%  |
| 0.51-1.0   | 91        | 110    | 45.27%  |
| 1.01-2.0   | 2         | 5      | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 26.59%  |
| 251-500        | 60        | 23.81%  |
| 501-1000       | 53        | 21.03%  |
| 21-50          | 18        | 7.14%   |
| 51-100         | 18        | 7.14%   |
| 1001-2000      | 14        | 5.56%   |
| 1-20           | 13        | 5.16%   |
| More than 3000 | 4         | 1.59%   |
| 2001-3000      | 3         | 1.19%   |
| Unknown        | 2         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 99        | 38.08%  |
| 21-50          | 58        | 22.31%  |
| 101-250        | 32        | 12.31%  |
| 51-100         | 30        | 11.54%  |
| 251-500        | 21        | 8.08%   |
| 501-1000       | 12        | 4.62%   |
| 1001-2000      | 3         | 1.15%   |
| 2001-3000      | 2         | 0.77%   |
| Unknown        | 2         | 0.77%   |
| More than 3000 | 1         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Notebooks | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2         | 2      | 7.69%   |
| WDC WD10JPCX-24UE4T0 1TB         | 2         | 2      | 7.69%   |
| WDC WDS100T2G0A-00JH30 1TB SSD   | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-22ZCT0 320GB      | 1         | 1      | 3.85%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB         | 1         | 1      | 3.85%   |
| Toshiba MK5065GSXN 500GB         | 1         | 1      | 3.85%   |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 3.85%   |
| Toshiba MK2035GSS 200GB          | 1         | 1      | 3.85%   |
| Toshiba HDWJ110 1TB              | 1         | 1      | 3.85%   |
| SSSTC CVB-8D128-HP 128GB SSD     | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 3.85%   |
| Seagate ST9250315AS 250GB        | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 3.85%   |
| Seagate ST1000LM014-1EJ164 1TB   | 1         | 1      | 3.85%   |
| Kingston SA400S37480G 480GB SSD  | 1         | 1      | 3.85%   |
| Hitachi HTS725050A7E630 500GB    | 1         | 1      | 3.85%   |
| Hitachi HTS545050B9A300 500GB    | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB    | 1         | 3      | 3.85%   |
| Hitachi HTS545032B9A302 320GB    | 1         | 1      | 3.85%   |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 3.85%   |
| HGST HTS541010A9E680 1TB         | 1         | 1      | 3.85%   |
| Hewlett-Packard SSD S700 500GB   | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 24%     |
| Toshiba         | 5         | 6      | 20%     |
| Seagate         | 5         | 5      | 20%     |
| Hitachi         | 4         | 6      | 16%     |
| HGST            | 2         | 2      | 8%      |
| SSSTC           | 1         | 1      | 4%      |
| Kingston        | 1         | 1      | 4%      |
| Hewlett-Packard | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 5         | 6      | 26.32%  |
| Seagate | 5         | 5      | 26.32%  |
| Hitachi | 4         | 6      | 21.05%  |
| WDC     | 3         | 3      | 15.79%  |
| HGST    | 2         | 2      | 10.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 22     | 76%     |
| SSD  | 6         | 6      | 24%     |

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
| Detected | 146       | 214    | 55.3%   |
| Works    | 93        | 126    | 35.23%  |
| Malfunc  | 24        | 28     | 9.09%   |
| Failed   | 1         | 2      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 170       | 61.15%  |
| AMD                              | 37        | 13.31%  |
| SanDisk                          | 16        | 5.76%   |
| Samsung Electronics              | 14        | 5.04%   |
| Micron Technology                | 9         | 3.24%   |
| Kingston Technology Company      | 7         | 2.52%   |
| SK hynix                         | 6         | 2.16%   |
| KIOXIA                           | 6         | 2.16%   |
| Union Memory (Shenzhen)          | 2         | 0.72%   |
| Silicon Motion                   | 2         | 0.72%   |
| Phison Electronics               | 2         | 0.72%   |
| Micron/Crucial Technology        | 2         | 0.72%   |
| Toshiba America Info Systems     | 1         | 0.36%   |
| Solid State Storage Technology   | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] | 1         | 0.36%   |
| INNOGRIT                         | 1         | 0.36%   |
| Biwin Storage Technology         | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 11.26%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 30        | 10.24%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 6.83%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 6.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 3.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 3.07%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 2.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 2.05%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 2.05%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.71%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 1.02%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 1.02%   |
| Kingston Company NVMe Controller                                               | 3         | 1.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.02%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.68%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 2         | 0.68%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.68%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.68%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.68%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.68%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 0.68%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.68%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 175       | 61.4%   |
| NVMe | 73        | 25.61%  |
| RAID | 28        | 9.82%   |
| IDE  | 9         | 3.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 186       | 76.54%  |
| AMD    | 57        | 23.46%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 2.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.47%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 2.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 2.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 2.06%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 2.06%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 2.06%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 5         | 2.06%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 2.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.65%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 1.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.23%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.23%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.23%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.23%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 3         | 1.23%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.23%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 3         | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.82%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.82%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.82%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.82%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.82%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.82%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.82%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.82%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.82%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 2         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 59        | 24.28%  |
| Intel Core i5           | 58        | 23.87%  |
| Intel Core i3           | 30        | 12.35%  |
| AMD Ryzen 7             | 17        | 7%      |
| AMD Ryzen 5             | 17        | 7%      |
| Other                   | 14        | 5.76%   |
| Intel Celeron           | 12        | 4.94%   |
| Intel Atom              | 5         | 2.06%   |
| Intel Core 2 Duo        | 3         | 1.23%   |
| AMD Athlon              | 3         | 1.23%   |
| AMD A8                  | 3         | 1.23%   |
| Intel Pentium           | 2         | 0.82%   |
| AMD Ryzen 9             | 2         | 0.82%   |
| AMD Ryzen 7 PRO         | 2         | 0.82%   |
| AMD Ryzen 3             | 2         | 0.82%   |
| AMD E1                  | 2         | 0.82%   |
| AMD E                   | 2         | 0.82%   |
| AMD A4                  | 2         | 0.82%   |
| Intel Xeon              | 1         | 0.41%   |
| Intel Pentium Dual-Core | 1         | 0.41%   |
| Intel Pentium Dual      | 1         | 0.41%   |
| Intel Genuine           | 1         | 0.41%   |
| Intel Celeron M         | 1         | 0.41%   |
| AMD C-50                | 1         | 0.41%   |
| AMD A12                 | 1         | 0.41%   |
| AMD A10                 | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 117       | 48.15%  |
| 4       | 86        | 35.39%  |
| 8       | 18        | 7.41%   |
| 6       | 12        | 4.94%   |
| 1       | 7         | 2.88%   |
| 16      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 243       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 202       | 83.13%  |
| 1       | 40        | 16.46%  |
| Unknown | 1         | 0.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 237       | 96.73%  |
| 64-bit         | 3         | 1.22%   |
| 32-bit         | 3         | 1.22%   |
| Unknown        | 2         | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 26.19%  |
| 0x206a7    | 15        | 5.95%   |
| 0x306a9    | 12        | 4.76%   |
| 0x40651    | 11        | 4.37%   |
| 0x806ec    | 10        | 3.97%   |
| 0x806ea    | 10        | 3.97%   |
| 0x406e3    | 10        | 3.97%   |
| 0x306d4    | 9         | 3.57%   |
| 0x806e9    | 8         | 3.17%   |
| 0x08108109 | 8         | 3.17%   |
| 0x08108102 | 6         | 2.38%   |
| 0x906ea    | 5         | 1.98%   |
| 0x806c1    | 5         | 1.98%   |
| 0x706e5    | 5         | 1.98%   |
| 0x306c3    | 5         | 1.98%   |
| 0x0a50000c | 5         | 1.98%   |
| 0x20655    | 4         | 1.59%   |
| 0x806eb    | 3         | 1.19%   |
| 0x30678    | 3         | 1.19%   |
| 0x20652    | 3         | 1.19%   |
| 0x10661    | 3         | 1.19%   |
| 0x08608103 | 3         | 1.19%   |
| 0xa0652    | 2         | 0.79%   |
| 0x906e9    | 2         | 0.79%   |
| 0x1067a    | 2         | 0.79%   |
| 0x0a404101 | 2         | 0.79%   |
| 0x08600106 | 2         | 0.79%   |
| 0x08600104 | 2         | 0.79%   |
| 0x08600102 | 2         | 0.79%   |
| 0x05000029 | 2         | 0.79%   |
| 0x906a4    | 1         | 0.4%    |
| 0x906a3    | 1         | 0.4%    |
| 0x806d1    | 1         | 0.4%    |
| 0x706a1    | 1         | 0.4%    |
| 0x6fd      | 1         | 0.4%    |
| 0x6e8      | 1         | 0.4%    |
| 0x6d8      | 1         | 0.4%    |
| 0x506e3    | 1         | 0.4%    |
| 0x406c4    | 1         | 0.4%    |
| 0x30673    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 53        | 21.81%  |
| Haswell          | 21        | 8.64%   |
| Zen+             | 18        | 7.41%   |
| IvyBridge        | 18        | 7.41%   |
| SandyBridge      | 16        | 6.58%   |
| Skylake          | 13        | 5.35%   |
| Broadwell        | 11        | 4.53%   |
| Unknown          | 9         | 3.7%    |
| Zen 2            | 8         | 3.29%   |
| Westmere         | 8         | 3.29%   |
| TigerLake        | 7         | 2.88%   |
| Silvermont       | 7         | 2.88%   |
| IceLake          | 7         | 2.88%   |
| Zen 3            | 6         | 2.47%   |
| Goldmont plus    | 5         | 2.06%   |
| Zen              | 4         | 1.65%   |
| Penryn           | 4         | 1.65%   |
| Excavator        | 4         | 1.65%   |
| Core             | 4         | 1.65%   |
| Piledriver       | 3         | 1.23%   |
| CometLake        | 3         | 1.23%   |
| Bobcat           | 3         | 1.23%   |
| Puma             | 2         | 0.82%   |
| P6               | 2         | 0.82%   |
| Jaguar           | 2         | 0.82%   |
| Bonnell          | 2         | 0.82%   |
| Alderlake Hybrid | 2         | 0.82%   |
| Nehalem          | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 173       | 55.1%   |
| AMD                              | 81        | 25.8%   |
| Nvidia                           | 59        | 18.79%  |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 18        | 5.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 17        | 5.21%   |
| Intel UHD Graphics 620                                                                | 16        | 4.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 15        | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 15        | 4.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 3.37%   |
| Intel HD Graphics 620                                                                 | 11        | 3.37%   |
| Intel HD Graphics 5500                                                                | 11        | 3.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 2.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 2.76%   |
| AMD Renoir                                                                            | 8         | 2.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                                   | 6         | 1.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 1.84%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 1.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 1.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 5         | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 5         | 1.53%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 4         | 1.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 4         | 1.23%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.23%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 4         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 1.23%   |
| AMD Lucienne                                                                          | 4         | 1.23%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 0.92%   |
| Nvidia GM108M [GeForce MX110]                                                         | 3         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 3         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 3         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 3         | 0.92%   |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 0.92%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 2         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.61%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.61%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 0.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 110       | 45.27%  |
| 1 x AMD        | 45        | 18.52%  |
| Intel + Nvidia | 42        | 17.28%  |
| Intel + AMD    | 19        | 7.82%   |
| AMD + Nvidia   | 10        | 4.12%   |
| 2 x AMD        | 7         | 2.88%   |
| 1 x Nvidia     | 7         | 2.88%   |
| 2 x Intel      | 2         | 0.82%   |
| 1 x SiS        | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 209       | 84.96%  |
| Proprietary | 32        | 13.01%  |
| Unknown     | 5         | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 57.43%  |
| 1.01-2.0   | 41        | 16.47%  |
| 0.01-0.5   | 34        | 13.65%  |
| 3.01-4.0   | 14        | 5.62%   |
| 0.51-1.0   | 9         | 3.61%   |
| 5.01-6.0   | 5         | 2.01%   |
| 7.01-8.0   | 2         | 0.8%    |
| 8.01-16.0  | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 63        | 22.83%  |
| BOE                 | 49        | 17.75%  |
| AU Optronics        | 41        | 14.86%  |
| Samsung Electronics | 40        | 14.49%  |
| LG Display          | 28        | 10.14%  |
| PANDA               | 7         | 2.54%   |
| Goldstar            | 6         | 2.17%   |
| Sharp               | 3         | 1.09%   |
| Hewlett-Packard     | 3         | 1.09%   |
| Apple               | 3         | 1.09%   |
| AOC                 | 3         | 1.09%   |
| TMX                 | 2         | 0.72%   |
| Sony                | 2         | 0.72%   |
| Lenovo              | 2         | 0.72%   |
| JRY                 | 2         | 0.72%   |
| HannStar            | 2         | 0.72%   |
| Dell                | 2         | 0.72%   |
| Unknown             | 2         | 0.72%   |
| ViewSonic           | 1         | 0.36%   |
| Unknown (XXX)       | 1         | 0.36%   |
| Panasonic           | 1         | 0.36%   |
| MSI                 | 1         | 0.36%   |
| Mi                  | 1         | 0.36%   |
| LGD                 | 1         | 0.36%   |
| LG Philips          | 1         | 0.36%   |
| InnoLux Display     | 1         | 0.36%   |
| InfoVision          | 1         | 0.36%   |
| HUAWEI              | 1         | 0.36%   |
| Hitachi             | 1         | 0.36%   |
| EXP                 | 1         | 0.36%   |
| DZX                 | 1         | 0.36%   |
| CSO                 | 1         | 0.36%   |
| AGO                 | 1         | 0.36%   |
| Acer                | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 4.35%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 8         | 2.9%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 5         | 1.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 1.09%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 3         | 1.09%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.09%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.72%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.72%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.72%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.72%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 2         | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.72%   |
| JRY HDMI JRY2380 1920x1080 530x290mm 23.8-inch                       | 2         | 0.72%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch      | 2         | 0.72%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.72%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.72%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.72%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.72%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.72%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.72%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                 | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch        | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.72%   |
| Unknown                                                              | 2         | 0.72%   |
| ViewSonic VX2257 VSCB731 1920x1080 477x268mm 21.5-inch               | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 135       | 51.14%  |
| 1920x1080 (FHD)   | 81        | 30.68%  |
| 1600x900 (HD+)    | 7         | 2.65%   |
| 1280x800 (WXGA)   | 6         | 2.27%   |
| 3840x2160 (4K)    | 5         | 1.89%   |
| 2160x1440         | 5         | 1.89%   |
| 1360x768          | 4         | 1.52%   |
| 1440x900 (WXGA+)  | 3         | 1.14%   |
| 3200x1800 (QHD+)  | 2         | 0.76%   |
| 2560x1600         | 2         | 0.76%   |
| 1920x1200 (WUXGA) | 2         | 0.76%   |
| 1024x600          | 2         | 0.76%   |
| Unknown           | 2         | 0.76%   |
| 640x480           | 1         | 0.38%   |
| 3840x1080         | 1         | 0.38%   |
| 3200x2000         | 1         | 0.38%   |
| 2880x1800         | 1         | 0.38%   |
| 2560x1440 (QHD)   | 1         | 0.38%   |
| 2520x1680         | 1         | 0.38%   |
| 1280x720 (HD)     | 1         | 0.38%   |
| 1024x768 (XGA)    | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 132       | 48.35%  |
| 13      | 47        | 17.22%  |
| 14      | 36        | 13.19%  |
| 23      | 10        | 3.66%   |
| 18      | 6         | 2.2%    |
| 17      | 6         | 2.2%    |
| 21      | 5         | 1.83%   |
| 11      | 4         | 1.47%   |
| 24      | 3         | 1.1%    |
| 16      | 3         | 1.1%    |
| Unknown | 3         | 1.1%    |
| 72      | 2         | 0.73%   |
| 31      | 2         | 0.73%   |
| 27      | 2         | 0.73%   |
| 12      | 2         | 0.73%   |
| 10      | 2         | 0.73%   |
| 84      | 1         | 0.37%   |
| 60      | 1         | 0.37%   |
| 54      | 1         | 0.37%   |
| 48      | 1         | 0.37%   |
| 46      | 1         | 0.37%   |
| 39      | 1         | 0.37%   |
| 20      | 1         | 0.37%   |
| 19      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 202       | 74.54%  |
| 201-300     | 20        | 7.38%   |
| 501-600     | 15        | 5.54%   |
| 401-500     | 13        | 4.8%    |
| 351-400     | 8         | 2.95%   |
| 1001-1500   | 4         | 1.48%   |
| 1501-2000   | 3         | 1.11%   |
| Unknown     | 3         | 1.11%   |
| 601-700     | 2         | 0.74%   |
| 801-900     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 213       | 87.65%  |
| 16/10   | 18        | 7.41%   |
| 3/2     | 6         | 2.47%   |
| 4/3     | 3         | 1.23%   |
| Unknown | 3         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 132       | 48.35%  |
| 81-90          | 72        | 26.37%  |
| 201-250        | 16        | 5.86%   |
| 71-80          | 10        | 3.66%   |
| More than 1000 | 6         | 2.2%    |
| 151-200        | 5         | 1.83%   |
| 141-150        | 5         | 1.83%   |
| 51-60          | 4         | 1.47%   |
| 121-130        | 4         | 1.47%   |
| 111-120        | 3         | 1.1%    |
| Unknown        | 3         | 1.1%    |
| 351-500        | 2         | 0.73%   |
| 41-50          | 2         | 0.73%   |
| 301-350        | 2         | 0.73%   |
| 131-140        | 2         | 0.73%   |
| 501-1000       | 2         | 0.73%   |
| 91-100         | 2         | 0.73%   |
| 61-70          | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 134       | 49.81%  |
| 121-160       | 75        | 27.88%  |
| 51-100        | 34        | 12.64%  |
| 161-240       | 12        | 4.46%   |
| 1-50          | 7         | 2.6%    |
| More than 240 | 4         | 1.49%   |
| Unknown       | 3         | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 200       | 80.65%  |
| 2     | 39        | 15.73%  |
| 0     | 7         | 2.82%   |
| 3     | 2         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 152       | 40.86%  |
| Intel                            | 86        | 23.12%  |
| Qualcomm Atheros                 | 70        | 18.82%  |
| Broadcom                         | 15        | 4.03%   |
| TP-Link                          | 8         | 2.15%   |
| MediaTek                         | 8         | 2.15%   |
| Ralink                           | 7         | 1.88%   |
| Xiaomi                           | 4         | 1.08%   |
| Marvell Technology Group         | 4         | 1.08%   |
| ASIX Electronics                 | 3         | 0.81%   |
| Samsung Electronics              | 2         | 0.54%   |
| Ralink Technology                | 2         | 0.54%   |
| Motorola PCS                     | 2         | 0.54%   |
| ICS Advent                       | 2         | 0.54%   |
| T & A Mobile Phones              | 1         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.27%   |
| OPPO Electronics                 | 1         | 0.27%   |
| Microsoft                        | 1         | 0.27%   |
| Lenovo                           | 1         | 0.27%   |
| Broadcom Limited                 | 1         | 0.27%   |
| Apple                            | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 97        | 21.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 28        | 6.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 5.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 3.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.3%    |
| Intel Wireless 8265 / 8275                                              | 6         | 1.3%    |
| Intel Wireless 8260                                                     | 6         | 1.3%    |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 6         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.09%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.87%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.87%   |
| Intel Wireless 7265                                                     | 4         | 0.87%   |
| Intel Wireless 7260                                                     | 4         | 0.87%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.65%   |
| Intel WiFi Link 5100                                                    | 3         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.43%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 33.6%   |
| Realtek Semiconductor | 64        | 25.6%   |
| Qualcomm Atheros      | 64        | 25.6%   |
| Broadcom              | 13        | 5.2%    |
| MediaTek              | 8         | 3.2%    |
| TP-Link               | 7         | 2.8%    |
| Ralink                | 7         | 2.8%    |
| Ralink Technology     | 2         | 0.8%    |
| Broadcom Limited      | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 10.4%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 7.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 6.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 3.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 2.4%    |
| Intel Wireless 8265 / 8275                                              | 6         | 2.4%    |
| Intel Wireless 8260                                                     | 6         | 2.4%    |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.4%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 2%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 2%      |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 1.6%    |
| Intel Wireless 7265                                                     | 4         | 1.6%    |
| Intel Wireless 7260                                                     | 4         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.2%    |
| Intel WiFi Link 5100                                                    | 3         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.2%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.8%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.8%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.8%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.8%    |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.8%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 135       | 65.22%  |
| Intel                            | 29        | 14.01%  |
| Qualcomm Atheros                 | 16        | 7.73%   |
| Xiaomi                           | 4         | 1.93%   |
| Marvell Technology Group         | 4         | 1.93%   |
| Broadcom                         | 4         | 1.93%   |
| ASIX Electronics                 | 3         | 1.45%   |
| Motorola PCS                     | 2         | 0.97%   |
| ICS Advent                       | 2         | 0.97%   |
| TP-Link                          | 1         | 0.48%   |
| T & A Mobile Phones              | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Samsung Electronics              | 1         | 0.48%   |
| OPPO Electronics                 | 1         | 0.48%   |
| Microsoft                        | 1         | 0.48%   |
| Lenovo                           | 1         | 0.48%   |
| Apple                            | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 97        | 46.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 28        | 13.4%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 6         | 2.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 1.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.44%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.44%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.96%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.96%   |
| Motorola PCS XT1032                                                            | 2         | 0.96%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.96%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.96%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.96%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.96%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.96%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.96%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.96%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.48%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.48%   |
| OPPO SM6375-QRD _SN:F4A23F05                                                   | 1         | 0.48%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.48%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.48%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.48%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.48%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.48%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 240       | 54.42%  |
| Ethernet | 200       | 45.35%  |
| Modem    | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 195       | 74.71%  |
| Ethernet | 66        | 25.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 182       | 74.9%   |
| 1     | 58        | 23.87%  |
| 0     | 3         | 1.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 195       | 78.31%  |
| Yes  | 54        | 21.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 31.71%  |
| Realtek Semiconductor           | 43        | 20.98%  |
| Qualcomm Atheros Communications | 34        | 16.59%  |
| IMC Networks                    | 17        | 8.29%   |
| Lite-On Technology              | 11        | 5.37%   |
| Toshiba                         | 7         | 3.41%   |
| Ralink                          | 6         | 2.93%   |
| Foxconn / Hon Hai               | 5         | 2.44%   |
| Broadcom                        | 4         | 1.95%   |
| Hewlett-Packard                 | 3         | 1.46%   |
| Apple                           | 3         | 1.46%   |
| Dell                            | 2         | 0.98%   |
| Cambridge Silicon Radio         | 2         | 0.98%   |
| Realtek                         | 1         | 0.49%   |
| Foxconn International           | 1         | 0.49%   |
| Alps Electric                   | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 10.73%  |
| Realtek Bluetooth Radio                             | 21        | 10.24%  |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 10.24%  |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 9.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 8.29%   |
| Intel AX201 Bluetooth                               | 10        | 4.88%   |
| Ralink RT3290 Bluetooth                             | 6         | 2.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.93%   |
| Intel AX200 Bluetooth                               | 6         | 2.93%   |
| IMC Networks Wireless_Device                        | 6         | 2.93%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.93%   |
| Toshiba Bluetooth Device                            | 4         | 1.95%   |
| IMC Networks Bluetooth Device                       | 4         | 1.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.46%   |
| Lite-On Bluetooth Radio                             | 3         | 1.46%   |
| Lite-On Bluetooth Device                            | 3         | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.46%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.98%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.98%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.98%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.98%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.98%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.49%   |
| Toshiba BCM43142A0                                  | 1         | 0.49%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.49%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.49%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.49%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.49%   |
| Intel Bluetooth Device                              | 1         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 63.29%  |
| AMD                              | 63        | 22.03%  |
| Nvidia                           | 30        | 10.49%  |
| Generalplus Technology           | 3         | 1.05%   |
| C-Media Electronics              | 3         | 1.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Razer USA                        | 1         | 0.35%   |
| Pixart Imaging                   | 1         | 0.35%   |
| Kingston Technology              | 1         | 0.35%   |
| Hewlett-Packard                  | 1         | 0.35%   |
| GN Netcom                        | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 43        | 11.62%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 10.54%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 5.68%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 4.59%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 4.05%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.97%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 11        | 2.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 2.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.89%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.35%   |
| Nvidia Audio device                                                                               | 5         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.35%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.81%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.81%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.81%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.81%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 29.35%  |
| SK hynix            | 39        | 21.2%   |
| Micron Technology   | 27        | 14.67%  |
| Kingston            | 22        | 11.96%  |
| Unknown             | 10        | 5.43%   |
| Ramaxel Technology  | 10        | 5.43%   |
| Unknown (ABCD)      | 5         | 2.72%   |
| Team                | 4         | 2.17%   |
| Crucial             | 3         | 1.63%   |
| Hewlett-Packard     | 2         | 1.09%   |
| Elpida              | 2         | 1.09%   |
| Patriot             | 1         | 0.54%   |
| Kllisre             | 1         | 0.54%   |
| Goldkey             | 1         | 0.54%   |
| CSX                 | 1         | 0.54%   |
| Corsair             | 1         | 0.54%   |
| A-DATA Technology   | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 3.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 5         | 2.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 2.56%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 2.05%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 3         | 1.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.54%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM 1600MT/s               | 3         | 1.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.03%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 1.03%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.03%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.03%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.03%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.03%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.03%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.03%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.51%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.51%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.51%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 64        | 46.04%  |
| DDR3    | 51        | 36.69%  |
| LPDDR4  | 11        | 7.91%   |
| DDR2    | 4         | 2.88%   |
| LPDDR3  | 3         | 2.16%   |
| DDR5    | 3         | 2.16%   |
| SDRAM   | 2         | 1.44%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 132       | 94.96%  |
| Row Of Chips | 7         | 5.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 70        | 42.42%  |
| 4096  | 60        | 36.36%  |
| 16384 | 14        | 8.48%   |
| 2048  | 13        | 7.88%   |
| 1024  | 4         | 2.42%   |
| 32768 | 3         | 1.82%   |
| 512   | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 43        | 27.04%  |
| 1600    | 41        | 25.79%  |
| 3200    | 29        | 18.24%  |
| 2400    | 11        | 6.92%   |
| 3266    | 6         | 3.77%   |
| 1333    | 5         | 3.14%   |
| 1334    | 4         | 2.52%   |
| 4800    | 3         | 1.89%   |
| 2133    | 3         | 1.89%   |
| Unknown | 3         | 1.89%   |
| 1867    | 2         | 1.26%   |
| 1067    | 2         | 1.26%   |
| 4267    | 1         | 0.63%   |
| 4199    | 1         | 0.63%   |
| 2933    | 1         | 0.63%   |
| 1066    | 1         | 0.63%   |
| 800     | 1         | 0.63%   |
| 667     | 1         | 0.63%   |
| 533     | 1         | 0.63%   |

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
| Chicony Electronics                    | 51        | 22.08%  |
| IMC Networks                           | 27        | 11.69%  |
| Microdia                               | 20        | 8.66%   |
| Realtek Semiconductor                  | 17        | 7.36%   |
| Bison Electronics                      | 16        | 6.93%   |
| Syntek                                 | 14        | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 5.63%   |
| Sunplus Innovation Technology          | 11        | 4.76%   |
| Quanta                                 | 11        | 4.76%   |
| Lite-On Technology                     | 11        | 4.76%   |
| Suyin                                  | 10        | 4.33%   |
| Acer                                   | 6         | 2.6%    |
| Sonix Technology                       | 4         | 1.73%   |
| Luxvisions Innotech Limited            | 4         | 1.73%   |
| Importek                               | 4         | 1.73%   |
| Samsung Electronics                    | 2         | 0.87%   |
| Ricoh                                  | 2         | 0.87%   |
| Apple                                  | 2         | 0.87%   |
| Alcor Micro                            | 2         | 0.87%   |
| Logitech                               | 1         | 0.43%   |
| Jieli Technology                       | 1         | 0.43%   |
| ASUSTek Computer                       | 1         | 0.43%   |
| ANYKA                                  | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 11        | 4.74%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 3.45%   |
| Chicony Integrated Camera                                                  | 6         | 2.59%   |
| Chicony HP TrueVision HD                                                   | 6         | 2.59%   |
| Bison Integrated Camera                                                    | 6         | 2.59%   |
| Microdia Webcam Vitade AF                                                  | 5         | 2.16%   |
| Lite-On Integrated Camera                                                  | 5         | 2.16%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 2.16%   |
| Chicony EasyCamera                                                         | 5         | 2.16%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.72%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.72%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 1.72%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.72%   |
| IMC Networks Integrated Camera                                             | 4         | 1.72%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 1.72%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.72%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.72%   |
| Chicony HD WebCam                                                          | 4         | 1.72%   |
| Lite-On HP HD Camera                                                       | 3         | 1.29%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.29%   |
| Acer Integrated Camera                                                     | 3         | 1.29%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.86%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.86%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.86%   |
| Realtek Integrated Webcam                                                  | 2         | 0.86%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.86%   |
| Quanta HP Webcam                                                           | 2         | 0.86%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.86%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.86%   |
| IMC Networks HD Camera                                                     | 2         | 0.86%   |
| Chicony VGA Webcam                                                         | 2         | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.86%   |
| Chicony USB2.0 HD UVC WebCam                                               | 2         | 0.86%   |
| Chicony HP Webcam                                                          | 2         | 0.86%   |
| Chicony HP HD Webcam                                                       | 2         | 0.86%   |
| Chicony HP HD Camera                                                       | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 51.06%  |
| Synaptics                  | 12        | 25.53%  |
| Shenzhen Goodix Technology | 5         | 10.64%  |
| Elan Microelectronics      | 4         | 8.51%   |
| STMicroelectronics         | 1         | 2.13%   |
| AuthenTec                  | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 8         | 17.02%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 7         | 14.89%  |
| Synaptics  WBDI                                           | 4         | 8.51%   |
| Shenzhen Goodix  FingerPrint Device                       | 3         | 6.38%   |
| Elan ELAN:Fingerprint                                     | 3         | 6.38%   |
| Validity Sensors Synaptics WBDI                           | 2         | 4.26%   |
| Validity Sensors Fingerprint scanner                      | 2         | 4.26%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 4.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.26%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 4.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 2.13%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 2.13%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.13%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 2.13%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 2.13%   |
| Synaptics WBDI                                            | 1         | 2.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 2.13%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 2.13%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 2.13%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.13%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 2.13%   |

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
| 0     | 151       | 60.64%  |
| 1     | 81        | 32.53%  |
| 2     | 15        | 6.02%   |
| 3     | 2         | 0.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 41.23%  |
| Graphics card            | 22        | 19.3%   |
| Net/wireless             | 13        | 11.4%   |
| Chipcard                 | 11        | 9.65%   |
| Bluetooth                | 8         | 7.02%   |
| Multimedia controller    | 5         | 4.39%   |
| Storage                  | 2         | 1.75%   |
| Card reader              | 2         | 1.75%   |
| Camera                   | 2         | 1.75%   |
| Net/ethernet             | 1         | 0.88%   |
| Communication controller | 1         | 0.88%   |

