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

Total: 377

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| HP         | EliteBook 2760p             | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| Toshiba    | Satellite L45-B             | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Lenovo     | IdeaPad 3 14IIL05 81WD      | [952169c1ce](https://linux-hardware.org/?probe=952169c1ce) | Sep 24, 2023 |
| HP         | Pavilion dv4                | [b1ee39c175](https://linux-hardware.org/?probe=b1ee39c175) | Sep 24, 2023 |
| ASUSTek    | X550LD                      | [9d8e946b59](https://linux-hardware.org/?probe=9d8e946b59) | Sep 21, 2023 |
| ASUSTek    | X550LD                      | [18a02021f6](https://linux-hardware.org/?probe=18a02021f6) | Sep 21, 2023 |
| Lenovo     | IdeaPad 3 14IIL05 81WD      | [e9c24b2427](https://linux-hardware.org/?probe=e9c24b2427) | Sep 18, 2023 |
| ASUSTek    | G752VY                      | [7d3353b537](https://linux-hardware.org/?probe=7d3353b537) | Sep 15, 2023 |
| HP         | OMEN by Laptop 17-ck0xxx    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| HP         | OMEN by Laptop 15-dc0xxx    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| Google     | Treeya                      | [a4db63abbe](https://linux-hardware.org/?probe=a4db63abbe) | Sep 10, 2023 |
| HP         | Pavilion dv4                | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Google     | Treeya                      | [fcc8d7d8a1](https://linux-hardware.org/?probe=fcc8d7d8a1) | Sep 05, 2023 |
| HP         | Notebook                    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell       | Latitude 5490               | [392d7335ed](https://linux-hardware.org/?probe=392d7335ed) | Sep 03, 2023 |
| HP         | OMEN Laptop 15-en0xxx       | [47ef8122dc](https://linux-hardware.org/?probe=47ef8122dc) | Sep 03, 2023 |
| HP         | Laptop 15-da0xxx            | [4c9a89e532](https://linux-hardware.org/?probe=4c9a89e532) | Aug 27, 2023 |
| HP         | ProBook 640 G1              | [c3b97aa105](https://linux-hardware.org/?probe=c3b97aa105) | Aug 27, 2023 |
| ASUSTek    | GL552VX                     | [fbe195ec09](https://linux-hardware.org/?probe=fbe195ec09) | Aug 17, 2023 |
| ASUSTek    | GL552VX                     | [37a66a073b](https://linux-hardware.org/?probe=37a66a073b) | Aug 17, 2023 |
| HP         | ZBook 15                    | [97923a8762](https://linux-hardware.org/?probe=97923a8762) | Aug 15, 2023 |
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
| Ubuntu 20.04                 | 32        | 11.55%  |
| Arch Rolling                 | 13        | 4.69%   |
| Ubuntu 22.04                 | 11        | 3.97%   |
| OpenMandriva 4.3             | 11        | 3.97%   |
| Ubuntu 18.04                 | 9         | 3.25%   |
| Linux Mint 21.1              | 9         | 3.25%   |
| OpenMandriva 23.03           | 7         | 2.53%   |
| Fedora 38                    | 7         | 2.53%   |
| Zorin 15                     | 6         | 2.17%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 2.17%   |
| Manjaro                      | 6         | 2.17%   |
| Linux Mint 20.3              | 6         | 2.17%   |
| Ubuntu 19.10                 | 5         | 1.81%   |
| Fedora 37                    | 5         | 1.81%   |
| Arch                         | 5         | 1.81%   |
| Xubuntu 20.04                | 4         | 1.44%   |
| Ubuntu 21.04                 | 4         | 1.44%   |
| Pop!_OS 21.10                | 4         | 1.44%   |
| OpenMandriva 23.01           | 4         | 1.44%   |
| Debian 11                    | 4         | 1.44%   |
| ArcoLinux Rolling            | 4         | 1.44%   |
| Ubuntu 19.04                 | 3         | 1.08%   |
| Pop!_OS 22.04                | 3         | 1.08%   |
| Pop!_OS 20.10                | 3         | 1.08%   |
| OpenMandriva 4.2             | 3         | 1.08%   |
| Manjaro 20.1                 | 3         | 1.08%   |
| KDE neon 20.04               | 3         | 1.08%   |
| Fedora 35                    | 3         | 1.08%   |
| Elementary 5.1.7             | 3         | 1.08%   |
| Debian 10                    | 3         | 1.08%   |
| ROSA R9                      | 2         | 0.72%   |
| ROSA R10                     | 2         | 0.72%   |
| ROSA 12.3                    | 2         | 0.72%   |
| ROSA 12.2                    | 2         | 0.72%   |
| Pop!_OS 20.04                | 2         | 0.72%   |
| OpenMandriva 4.90            | 2         | 0.72%   |
| OpenMandriva 23.08           | 2         | 0.72%   |
| OpenMandriva 23.06           | 2         | 0.72%   |
| LMDE 5                       | 2         | 0.72%   |
| Linux Mint 20                | 2         | 0.72%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 65        | 24.16%  |
| OpenMandriva  | 31        | 11.52%  |
| Linux Mint    | 21        | 7.81%   |
| Fedora        | 21        | 7.81%   |
| Arch          | 19        | 7.06%   |
| Pop!_OS       | 13        | 4.83%   |
| Manjaro       | 13        | 4.83%   |
| ROSA          | 10        | 3.72%   |
| Debian        | 10        | 3.72%   |
| Zorin         | 7         | 2.6%    |
| openSUSE      | 6         | 2.23%   |
| KDE neon      | 5         | 1.86%   |
| Xubuntu       | 4         | 1.49%   |
| Kubuntu       | 4         | 1.49%   |
| Elementary    | 4         | 1.49%   |
| ArcoLinux     | 4         | 1.49%   |
| Ubuntu MATE   | 3         | 1.12%   |
| Kali          | 3         | 1.12%   |
| Endless       | 3         | 1.12%   |
| SteamOS       | 2         | 0.74%   |
| Parrot        | 2         | 0.74%   |
| Lubuntu       | 2         | 0.74%   |
| LMDE          | 2         | 0.74%   |
| EndeavourOS   | 2         | 0.74%   |
| CentOS        | 2         | 0.74%   |
| Void Linux    | 1         | 0.37%   |
| Ubuntu Unity  | 1         | 0.37%   |
| Ubuntu Studio | 1         | 0.37%   |
| Ubuntu Budgie | 1         | 0.37%   |
| Peppermint    | 1         | 0.37%   |
| NixOS         | 1         | 0.37%   |
| MX            | 1         | 0.37%   |
| Laxer OS      | 1         | 0.37%   |
| Garuda Linux  | 1         | 0.37%   |
| Clear Linux   | 1         | 0.37%   |
| Artix         | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 11        | 3.65%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.99%   |
| 5.13.0-40-generic        | 5         | 1.66%   |
| 5.4.0-42-generic         | 4         | 1.33%   |
| 6.3.5-desktop-3omv2390   | 3         | 1%      |
| 6.3.5-200.fc38.x86_64    | 3         | 1%      |
| 5.4.0-26-generic         | 3         | 1%      |
| 5.3.0-40-generic         | 3         | 1%      |
| 5.15.0-76-generic        | 3         | 1%      |
| 5.15.0-71-generic        | 3         | 1%      |
| 5.13.0-51-generic        | 3         | 1%      |
| 5.11.0-25-generic        | 3         | 1%      |
| 5.10.0-13-amd64          | 3         | 1%      |
| 6.4.11-desktop-1omv2390  | 2         | 0.66%   |
| 6.3.6-arch1-1            | 2         | 0.66%   |
| 6.2.0-24-generic         | 2         | 0.66%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.66%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.66%   |
| 5.8.0-44-generic         | 2         | 0.66%   |
| 5.4.0-7642-generic       | 2         | 0.66%   |
| 5.4.0-66-generic         | 2         | 0.66%   |
| 5.4.0-65-generic         | 2         | 0.66%   |
| 5.4.0-58-generic         | 2         | 0.66%   |
| 5.4.0-54-generic         | 2         | 0.66%   |
| 5.4.0-39-generic         | 2         | 0.66%   |
| 5.4.0-33-generic         | 2         | 0.66%   |
| 5.4.0-28-generic         | 2         | 0.66%   |
| 5.4.0-109-generic        | 2         | 0.66%   |
| 5.3.0-42-generic         | 2         | 0.66%   |
| 5.3.0-23-generic         | 2         | 0.66%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.66%   |
| 5.17.5-arch1-1           | 2         | 0.66%   |
| 5.16.19-76051619-generic | 2         | 0.66%   |
| 5.15.49-1-lts            | 2         | 0.66%   |
| 5.15.0-58-generic        | 2         | 0.66%   |
| 5.15.0-57-generic        | 2         | 0.66%   |
| 5.15.0-52-generic        | 2         | 0.66%   |
| 5.15.0-25-generic        | 2         | 0.66%   |
| 5.13.0-30-generic        | 2         | 0.66%   |
| 5.11.0-7614-generic      | 2         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 13.01%  |
| 5.15.0  | 23        | 7.88%   |
| 5.13.0  | 14        | 4.79%   |
| 5.11.0  | 14        | 4.79%   |
| 5.3.0   | 12        | 4.11%   |
| 5.16.7  | 11        | 3.77%   |
| 6.2.6   | 7         | 2.4%    |
| 6.2.0   | 7         | 2.4%    |
| 5.8.0   | 7         | 2.4%    |
| 5.10.0  | 7         | 2.4%    |
| 5.0.0   | 7         | 2.4%    |
| 4.15.0  | 7         | 2.4%    |
| 6.3.5   | 6         | 2.05%   |
| 4.18.0  | 6         | 2.05%   |
| 5.19.0  | 5         | 1.71%   |
| 6.3.6   | 4         | 1.37%   |
| 6.4.11  | 3         | 1.03%   |
| 6.0.0   | 3         | 1.03%   |
| 5.17.5  | 3         | 1.03%   |
| 4.9.60  | 3         | 1.03%   |
| 6.5.0   | 2         | 0.68%   |
| 6.1.9   | 2         | 0.68%   |
| 6.1.4   | 2         | 0.68%   |
| 6.1.31  | 2         | 0.68%   |
| 6.1.11  | 2         | 0.68%   |
| 6.1.1   | 2         | 0.68%   |
| 6.0.7   | 2         | 0.68%   |
| 6.0.15  | 2         | 0.68%   |
| 5.18.12 | 2         | 0.68%   |
| 5.16.19 | 2         | 0.68%   |
| 5.15.49 | 2         | 0.68%   |
| 5.12.10 | 2         | 0.68%   |
| 5.10.74 | 2         | 0.68%   |
| 5.10.14 | 2         | 0.68%   |
| 4.9.20  | 2         | 0.68%   |
| 4.19.0  | 2         | 0.68%   |
| 6.5.3   | 1         | 0.34%   |
| 6.4.6   | 1         | 0.34%   |
| 6.4.5   | 1         | 0.34%   |
| 6.4.3   | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 14.39%  |
| 5.15    | 35        | 12.28%  |
| 6.2     | 20        | 7.02%   |
| 5.13    | 15        | 5.26%   |
| 5.11    | 15        | 5.26%   |
| 5.10    | 15        | 5.26%   |
| 5.16    | 14        | 4.91%   |
| 6.1     | 13        | 4.56%   |
| 6.3     | 12        | 4.21%   |
| 6.0     | 12        | 4.21%   |
| 5.3     | 12        | 4.21%   |
| 5.8     | 10        | 3.51%   |
| 6.4     | 9         | 3.16%   |
| 5.19    | 7         | 2.46%   |
| 5.17    | 7         | 2.46%   |
| 5.0     | 7         | 2.46%   |
| 4.15    | 7         | 2.46%   |
| 4.18    | 6         | 2.11%   |
| 5.18    | 4         | 1.4%    |
| 5.12    | 4         | 1.4%    |
| 4.9     | 4         | 1.4%    |
| 6.5     | 3         | 1.05%   |
| 5.14    | 3         | 1.05%   |
| 5.9     | 2         | 0.7%    |
| 5.7     | 2         | 0.7%    |
| 5.6     | 2         | 0.7%    |
| 4.19    | 2         | 0.7%    |
| 5.1     | 1         | 0.35%   |
| 4.16    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 251       | 96.91%  |
| i686   | 8         | 3.09%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 113       | 42.16%  |
| KDE5            | 58        | 21.64%  |
| XFCE            | 22        | 8.21%   |
| X-Cinnamon      | 18        | 6.72%   |
| Unknown         | 16        | 5.97%   |
| MATE            | 8         | 2.99%   |
| KDE             | 7         | 2.61%   |
| Pantheon        | 4         | 1.49%   |
| KDE4            | 4         | 1.49%   |
| i3              | 4         | 1.49%   |
| LXQt            | 3         | 1.12%   |
| sway            | 2         | 0.75%   |
| LXDE            | 2         | 0.75%   |
| Budgie          | 2         | 0.75%   |
| Unity           | 1         | 0.37%   |
| spectrwm        | 1         | 0.37%   |
| Hyprland        | 1         | 0.37%   |
| GNOME Flashback | 1         | 0.37%   |
| Deepin          | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 192       | 71.38%  |
| Wayland | 59        | 21.93%  |
| Unknown | 15        | 5.58%   |
| Tty     | 3         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 120       | 44.94%  |
| SDDM    | 49        | 18.35%  |
| GDM     | 39        | 14.61%  |
| LightDM | 31        | 11.61%  |
| GDM3    | 19        | 7.12%   |
| KDM     | 4         | 1.5%    |
| TDM     | 2         | 0.75%   |
| XDM     | 1         | 0.37%   |
| Ly      | 1         | 0.37%   |
| LXDM    | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 125       | 47.17%  |
| en_US   | 75        | 28.3%   |
| es_ES   | 24        | 9.06%   |
| Unknown | 16        | 6.04%   |
| es_MX   | 7         | 2.64%   |
| C       | 4         | 1.51%   |
| it_IT   | 2         | 0.75%   |
| fr_FR   | 2         | 0.75%   |
| en_GB   | 2         | 0.75%   |
| ca_ES   | 2         | 0.75%   |
| es_VE   | 1         | 0.38%   |
| es_CO   | 1         | 0.38%   |
| en_NZ   | 1         | 0.38%   |
| en_CA   | 1         | 0.38%   |
| de_DE   | 1         | 0.38%   |
| Default | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 147       | 55.89%  |
| BIOS | 116       | 44.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 196       | 73.41%  |
| Btrfs   | 29        | 10.86%  |
| Overlay | 23        | 8.61%   |
| Xfs     | 7         | 2.62%   |
| Unknown | 7         | 2.62%   |
| Tmpfs   | 4         | 1.5%    |
| Ext3    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 129       | 48.86%  |
| GPT     | 107       | 40.53%  |
| MBR     | 28        | 10.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 228       | 86.69%  |
| Yes       | 35        | 13.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 57.58%  |
| Yes       | 112       | 42.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 73        | 28.29%  |
| Lenovo              | 65        | 25.19%  |
| ASUSTek Computer    | 34        | 13.18%  |
| Dell                | 24        | 9.3%    |
| Toshiba             | 17        | 6.59%   |
| Acer                | 16        | 6.2%    |
| Sony                | 5         | 1.94%   |
| Chuwi               | 5         | 1.94%   |
| MSI                 | 4         | 1.55%   |
| HUAWEI              | 3         | 1.16%   |
| Apple               | 3         | 1.16%   |
| ADVANCE             | 2         | 0.78%   |
| Samsung Electronics | 1         | 0.39%   |
| Razer               | 1         | 0.39%   |
| Google              | 1         | 0.39%   |
| eMachines           | 1         | 0.39%   |
| efirstview          | 1         | 0.39%   |
| Compal              | 1         | 0.39%   |
| Unknown             | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                       | 5         | 1.94%   |
| Lenovo V330-15IKB 81AX                   | 4         | 1.55%   |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 1.55%   |
| HP 14                                    | 4         | 1.55%   |
| Toshiba Satellite L45-B                  | 3         | 1.16%   |
| Lenovo V310-15ISK 80SY                   | 3         | 1.16%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 3         | 1.16%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 1.16%   |
| Toshiba Satellite C45-A                  | 2         | 0.78%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.78%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.78%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.78%   |
| Lenovo G400 20235                        | 2         | 0.78%   |
| HP ProBook 645 G4                        | 2         | 0.78%   |
| HP Pavilion g4                           | 2         | 0.78%   |
| HP Pavilion dv4                          | 2         | 0.78%   |
| HP Notebook                              | 2         | 0.78%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.78%   |
| HP Compaq Presario C700                  | 2         | 0.78%   |
| HP 450                                   | 2         | 0.78%   |
| HP 250 G7 Notebook PC                    | 2         | 0.78%   |
| HP 250 G5 Notebook PC                    | 2         | 0.78%   |
| Dell XPS 13 9360                         | 2         | 0.78%   |
| Dell Latitude E7450                      | 2         | 0.78%   |
| Dell G5 5505                             | 2         | 0.78%   |
| ASUS X550LD                              | 2         | 0.78%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR     | 2         | 0.78%   |
| ASUS ROG Strix G513RC_G513RC             | 2         | 0.78%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.78%   |
| Apple MacBookPro9,2                      | 2         | 0.78%   |
| Toshiba Satellite P755                   | 1         | 0.39%   |
| Toshiba Satellite P300                   | 1         | 0.39%   |
| Toshiba Satellite L855                   | 1         | 0.39%   |
| Toshiba Satellite L35                    | 1         | 0.39%   |
| Toshiba Satellite E205                   | 1         | 0.39%   |
| Toshiba Satellite C845                   | 1         | 0.39%   |
| Toshiba Satellite C655D                  | 1         | 0.39%   |
| Toshiba Satellite C645                   | 1         | 0.39%   |
| Toshiba Satellite C55-B                  | 1         | 0.39%   |
| Toshiba Satellite A665                   | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 23        | 8.91%   |
| HP Pavilion       | 19        | 7.36%   |
| Lenovo ThinkPad   | 17        | 6.59%   |
| Toshiba Satellite | 15        | 5.81%   |
| Acer Aspire       | 13        | 5.04%   |
| ASUS VivoBook     | 12        | 4.65%   |
| HP ProBook        | 10        | 3.88%   |
| HP Laptop         | 10        | 3.88%   |
| Dell Latitude     | 10        | 3.88%   |
| Dell Inspiron     | 7         | 2.71%   |
| Lenovo Legion     | 5         | 1.94%   |
| Chuwi GemiBook    | 5         | 1.94%   |
| ASUS ROG          | 5         | 1.94%   |
| Lenovo V330-15IKB | 4         | 1.55%   |
| HP 250            | 4         | 1.55%   |
| HP 14             | 4         | 1.55%   |
| Lenovo V310-15ISK | 3         | 1.16%   |
| HP OMEN           | 3         | 1.16%   |
| HP EliteBook      | 3         | 1.16%   |
| HP Compaq         | 3         | 1.16%   |
| ASUS ASUS         | 3         | 1.16%   |
| Lenovo G400       | 2         | 0.78%   |
| HP ZBook          | 2         | 0.78%   |
| HP Notebook       | 2         | 0.78%   |
| HP ENVY           | 2         | 0.78%   |
| HP 450            | 2         | 0.78%   |
| HP 255            | 2         | 0.78%   |
| HP 240            | 2         | 0.78%   |
| Dell XPS          | 2         | 0.78%   |
| Dell G5           | 2         | 0.78%   |
| ASUS X550LD       | 2         | 0.78%   |
| Apple MacBookPro9 | 2         | 0.78%   |
| Toshiba QOSMIO    | 1         | 0.39%   |
| Toshiba NB505     | 1         | 0.39%   |
| Sony VPCEL36FJ    | 1         | 0.39%   |
| Sony VPCEC2JFX    | 1         | 0.39%   |
| Sony VGN-FW56M    | 1         | 0.39%   |
| Sony VGN-FW170J   | 1         | 0.39%   |
| Sony SVF15A17CLB  | 1         | 0.39%   |
| Samsung 300E5EV   | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 29        | 11.24%  |
| 2019 | 27        | 10.47%  |
| 2021 | 25        | 9.69%   |
| 2018 | 25        | 9.69%   |
| 2016 | 21        | 8.14%   |
| 2014 | 20        | 7.75%   |
| 2013 | 20        | 7.75%   |
| 2012 | 20        | 7.75%   |
| 2017 | 18        | 6.98%   |
| 2011 | 17        | 6.59%   |
| 2022 | 7         | 2.71%   |
| 2015 | 7         | 2.71%   |
| 2010 | 6         | 2.33%   |
| 2008 | 6         | 2.33%   |
| 2009 | 4         | 1.55%   |
| 2007 | 4         | 1.55%   |
| 2023 | 1         | 0.39%   |
| 2006 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 258       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 233       | 89.96%  |
| Enabled  | 26        | 10.04%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 257       | 99.61%  |
| Yes  | 1         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 78        | 29.43%  |
| 8.01-16.0   | 76        | 28.68%  |
| 3.01-4.0    | 47        | 17.74%  |
| 16.01-24.0  | 35        | 13.21%  |
| 1.01-2.0    | 9         | 3.4%    |
| 32.01-64.0  | 7         | 2.64%   |
| 2.01-3.0    | 6         | 2.26%   |
| 24.01-32.0  | 4         | 1.51%   |
| 0.51-1.0    | 2         | 0.75%   |
| 64.01-256.0 | 1         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 87        | 30.42%  |
| 1.01-2.0   | 84        | 29.37%  |
| 4.01-8.0   | 43        | 15.03%  |
| 3.01-4.0   | 40        | 13.99%  |
| 0.51-1.0   | 19        | 6.64%   |
| 8.01-16.0  | 11        | 3.85%   |
| 16.01-24.0 | 1         | 0.35%   |
| 0.01-0.5   | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 188       | 72.03%  |
| 2      | 66        | 25.29%  |
| 3      | 6         | 2.3%    |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 64.73%  |
| Yes       | 91        | 35.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 82.63%  |
| No        | 45        | 17.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 255       | 98.84%  |
| No        | 3         | 1.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 218       | 84.17%  |
| No        | 41        | 15.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 258       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 172       | 64.42%  |
| Arequipa              | 24        | 8.99%   |
| Trujillo              | 16        | 5.99%   |
| Huancayo              | 8         | 3%      |
| Piura                 | 6         | 2.25%   |
| Cusco                 | 6         | 2.25%   |
| Chiclayo              | 5         | 1.87%   |
| Ica                   | 4         | 1.5%    |
| Tacna                 | 2         | 0.75%   |
| La Victoria           | 2         | 0.75%   |
| Ilo                   | 2         | 0.75%   |
| Callao                | 2         | 0.75%   |
| Santiago de Surco     | 1         | 0.37%   |
| San Vicente de Canete | 1         | 0.37%   |
| San Isidro            | 1         | 0.37%   |
| San Borja             | 1         | 0.37%   |
| Punta Colorada        | 1         | 0.37%   |
| Puno                  | 1         | 0.37%   |
| Pisco                 | 1         | 0.37%   |
| Oxapampa              | 1         | 0.37%   |
| Moquegua              | 1         | 0.37%   |
| Lurin                 | 1         | 0.37%   |
| Juliaca               | 1         | 0.37%   |
| Iquitos               | 1         | 0.37%   |
| Huaraz                | 1         | 0.37%   |
| Distrito de Lima      | 1         | 0.37%   |
| Cajamarca             | 1         | 0.37%   |
| Barranco              | 1         | 0.37%   |
| Ayacucho              | 1         | 0.37%   |
| Abancay               | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 48        | 55     | 14.72%  |
| Toshiba                        | 45        | 55     | 13.8%   |
| Seagate                        | 42        | 49     | 12.88%  |
| Kingston                       | 39        | 48     | 11.96%  |
| Samsung Electronics            | 18        | 26     | 5.52%   |
| SanDisk                        | 17        | 20     | 5.21%   |
| Crucial                        | 13        | 19     | 3.99%   |
| Unknown                        | 11        | 11     | 3.37%   |
| Micron Technology              | 9         | 10     | 2.76%   |
| SK hynix                       | 8         | 11     | 2.45%   |
| Intel                          | 8         | 10     | 2.45%   |
| HGST                           | 8         | 8      | 2.45%   |
| KIOXIA                         | 6         | 7      | 1.84%   |
| Hitachi                        | 6         | 8      | 1.84%   |
| Netac                          | 5         | 5      | 1.53%   |
| Hewlett-Packard                | 5         | 5      | 1.53%   |
| TO Exter                       | 3         | 7      | 0.92%   |
| LITEON                         | 3         | 3      | 0.92%   |
| Kingston Technology Company    | 3         | 3      | 0.92%   |
| UMIS                           | 2         | 2      | 0.61%   |
| Silicon Motion                 | 2         | 2      | 0.61%   |
| Gigabyte Technology            | 2         | 2      | 0.61%   |
| China                          | 2         | 2      | 0.61%   |
| Apple                          | 2         | 2      | 0.61%   |
| A-DATA Technology              | 2         | 2      | 0.61%   |
| Unknown                        | 2         | 2      | 0.61%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.31%   |
| SSSTC                          | 1         | 1      | 0.31%   |
| Solid State Storage Technology | 1         | 1      | 0.31%   |
| Reletech-P400                  | 1         | 1      | 0.31%   |
| Phison Electronics             | 1         | 1      | 0.31%   |
| Phison                         | 1         | 1      | 0.31%   |
| Micron/Crucial Technology      | 1         | 4      | 0.31%   |
| Lenovo                         | 1         | 1      | 0.31%   |
| KingSpec                       | 1         | 1      | 0.31%   |
| ITHOO                          | 1         | 1      | 0.31%   |
| GLOWAY                         | 1         | 1      | 0.31%   |
| Fujitsu                        | 1         | 1      | 0.31%   |
| Dogfish                        | 1         | 1      | 0.31%   |
| Biwin Storage Technology       | 1         | 3      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 17        | 5.07%   |
| Kingston SA400S37240G 240GB SSD      | 16        | 4.78%   |
| Toshiba MQ04ABF100 1TB               | 10        | 2.99%   |
| Toshiba MQ01ABD100 1TB               | 9         | 2.69%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 7         | 2.09%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 1.49%   |
| Netac SSD 256GB                      | 5         | 1.49%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 1.49%   |
| Crucial CT500MX500SSD4 500GB         | 5         | 1.49%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 1.19%   |
| Unknown SD32G  32GB                  | 4         | 1.19%   |
| Seagate ST9500325AS 500GB            | 4         | 1.19%   |
| Kingston SA400S37960G 960GB SSD      | 4         | 1.19%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 1.19%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 0.9%    |
| Unknown MMC Card  32GB               | 3         | 0.9%    |
| Toshiba MQ01ABD075 752GB             | 3         | 0.9%    |
| TO Exter nal USB 3.0 120GB           | 3         | 0.9%    |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.9%    |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.9%    |
| SanDisk NVMe SSD Drive 1TB           | 3         | 0.9%    |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 3         | 0.9%    |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.9%    |
| HGST HTS721010A9E630 1TB             | 3         | 0.9%    |
| HP SSD S700 500GB                    | 3         | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.6%    |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.6%    |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.6%    |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.6%    |
| Toshiba MK2565GSXN 250GB             | 2         | 0.6%    |
| Toshiba HDWJ110 1TB                  | 2         | 0.6%    |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.6%    |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.6%    |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 512GB | 2         | 0.6%    |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.6%    |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.6%    |
| Kingston Company SNV2S1000G 1TB      | 2         | 0.6%    |
| Kingston SNVS500G 500GB              | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 43        | 53     | 32.82%  |
| Seagate | 42        | 47     | 32.06%  |
| WDC     | 29        | 32     | 22.14%  |
| HGST    | 8         | 8      | 6.11%   |
| Hitachi | 6         | 8      | 4.58%   |
| Fujitsu | 1         | 1      | 0.76%   |
| Apple   | 1         | 1      | 0.76%   |
| ACASIS  | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 34        | 41     | 33.01%  |
| WDC                 | 15        | 17     | 14.56%  |
| Crucial             | 12        | 17     | 11.65%  |
| SanDisk             | 5         | 7      | 4.85%   |
| Netac               | 5         | 5      | 4.85%   |
| Hewlett-Packard     | 5         | 5      | 4.85%   |
| Samsung Electronics | 4         | 4      | 3.88%   |
| TO Exter            | 3         | 7      | 2.91%   |
| LITEON              | 3         | 3      | 2.91%   |
| China               | 2         | 2      | 1.94%   |
| A-DATA Technology   | 2         | 2      | 1.94%   |
| Toshiba             | 1         | 1      | 0.97%   |
| SSSTC               | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 4      | 0.97%   |
| Seagate             | 1         | 1      | 0.97%   |
| Reletech-P400       | 1         | 1      | 0.97%   |
| Lenovo              | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 1      | 0.97%   |
| Intel               | 1         | 1      | 0.97%   |
| GLOWAY              | 1         | 1      | 0.97%   |
| Gigabyte Technology | 1         | 1      | 0.97%   |
| Dogfish             | 1         | 1      | 0.97%   |
| Apple               | 1         | 1      | 0.97%   |
| Unknown             | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 130       | 151    | 41.94%  |
| SSD     | 91        | 126    | 29.35%  |
| NVMe    | 76        | 104    | 24.52%  |
| MMC     | 11        | 11     | 3.55%   |
| Unknown | 2         | 2      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 191       | 269    | 67.25%  |
| NVMe | 76        | 104    | 26.76%  |
| MMC  | 11        | 11     | 3.87%   |
| SAS  | 6         | 10     | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 114       | 160    | 53.77%  |
| 0.51-1.0   | 94        | 110    | 44.34%  |
| 1.01-2.0   | 4         | 7      | 1.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 68        | 25.47%  |
| 251-500        | 62        | 23.22%  |
| 501-1000       | 56        | 20.97%  |
| 21-50          | 22        | 8.24%   |
| 51-100         | 19        | 7.12%   |
| 1001-2000      | 15        | 5.62%   |
| 1-20           | 15        | 5.62%   |
| More than 3000 | 4         | 1.5%    |
| 2001-3000      | 4         | 1.5%    |
| Unknown        | 2         | 0.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 107       | 38.91%  |
| 21-50          | 61        | 22.18%  |
| 101-250        | 34        | 12.36%  |
| 51-100         | 31        | 11.27%  |
| 251-500        | 21        | 7.64%   |
| 501-1000       | 13        | 4.73%   |
| 1001-2000      | 3         | 1.09%   |
| 2001-3000      | 2         | 0.73%   |
| Unknown        | 2         | 0.73%   |
| More than 3000 | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 2      | 6.9%    |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 6.9%    |
| Seagate ST9500325AS 500GB            | 2         | 2      | 6.9%    |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 1      | 3.45%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 3.45%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 3.45%   |
| Toshiba MK5065GSXN 500GB             | 1         | 1      | 3.45%   |
| Toshiba MK5056GSY 500GB              | 1         | 1      | 3.45%   |
| Toshiba MK4058GSX 400GB              | 1         | 1      | 3.45%   |
| Toshiba MK2035GSS 200GB              | 1         | 1      | 3.45%   |
| Toshiba HDWJ110 1TB                  | 1         | 1      | 3.45%   |
| SSSTC CVB-8D128-HP 128GB             | 1         | 1      | 3.45%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 3.45%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 3.45%   |
| Seagate ST1000LM014-1EJ164 1TB       | 1         | 1      | 3.45%   |
| Kingston SA400S37480G 480GB SSD      | 1         | 1      | 3.45%   |
| Hitachi HTS725050A7E630 500GB        | 1         | 1      | 3.45%   |
| Hitachi HTS545050B9A300 500GB        | 1         | 1      | 3.45%   |
| Hitachi HTS545050A7E380 500GB        | 1         | 3      | 3.45%   |
| Hitachi HTS545032B9A302 320GB        | 1         | 1      | 3.45%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 3.45%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 3.45%   |
| Hewlett-Packard SSD S700 500GB       | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| WDC             | 6         | 6      | 21.43%  |
| Toshiba         | 6         | 7      | 21.43%  |
| Seagate         | 6         | 6      | 21.43%  |
| Hitachi         | 4         | 6      | 14.29%  |
| HGST            | 2         | 2      | 7.14%   |
| SSSTC           | 1         | 1      | 3.57%   |
| SK hynix        | 1         | 1      | 3.57%   |
| Kingston        | 1         | 1      | 3.57%   |
| Hewlett-Packard | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 7      | 28.57%  |
| Seagate | 6         | 6      | 28.57%  |
| Hitachi | 4         | 6      | 19.05%  |
| WDC     | 3         | 3      | 14.29%  |
| HGST    | 2         | 2      | 9.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 75%     |
| SSD  | 6         | 6      | 21.43%  |
| NVMe | 1         | 1      | 3.57%   |

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
| Detected | 153       | 225    | 54.26%  |
| Works    | 101       | 136    | 35.82%  |
| Malfunc  | 27        | 31     | 9.57%   |
| Failed   | 1         | 2      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 183       | 61.82%  |
| AMD                              | 37        | 12.5%   |
| SanDisk                          | 18        | 6.08%   |
| Samsung Electronics              | 15        | 5.07%   |
| Micron Technology                | 9         | 3.04%   |
| Kingston Technology Company      | 8         | 2.7%    |
| SK hynix                         | 7         | 2.36%   |
| KIOXIA                           | 6         | 2.03%   |
| Union Memory (Shenzhen)          | 2         | 0.68%   |
| Silicon Motion                   | 2         | 0.68%   |
| Phison Electronics               | 2         | 0.68%   |
| Micron/Crucial Technology        | 2         | 0.68%   |
| Toshiba America Info Systems     | 1         | 0.34%   |
| Solid State Storage Technology   | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| INNOGRIT                         | 1         | 0.34%   |
| Biwin Storage Technology         | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 10.58%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 30        | 9.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 7.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 6.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 2.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 2.24%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 1.92%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.6%    |
| SK hynix BC511 NVMe SSD                                                        | 4         | 1.28%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.28%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.28%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.28%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.96%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.96%   |
| Kingston Company NVMe Controller                                               | 3         | 0.96%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.64%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 2         | 0.64%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.64%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.64%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.64%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.64%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 0.64%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.64%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.64%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 182       | 60.67%  |
| NVMe | 75        | 25%     |
| RAID | 33        | 11%     |
| IDE  | 10        | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 199       | 77.13%  |
| AMD    | 59        | 22.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 2.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 2.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.33%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 6         | 2.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.94%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 5         | 1.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.94%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.16%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 1.16%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.16%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.16%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.16%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 3         | 1.16%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.16%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 3         | 1.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.78%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.78%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 25.19%  |
| Intel Core i7           | 63        | 24.42%  |
| Intel Core i3           | 31        | 12.02%  |
| AMD Ryzen 7             | 18        | 6.98%   |
| AMD Ryzen 5             | 17        | 6.59%   |
| Other                   | 15        | 5.81%   |
| Intel Celeron           | 12        | 4.65%   |
| Intel Atom              | 5         | 1.94%   |
| Intel Core 2 Duo        | 3         | 1.16%   |
| AMD Athlon              | 3         | 1.16%   |
| AMD A8                  | 3         | 1.16%   |
| AMD A4                  | 3         | 1.16%   |
| Intel Pentium           | 2         | 0.78%   |
| AMD Ryzen 9             | 2         | 0.78%   |
| AMD Ryzen 7 PRO         | 2         | 0.78%   |
| AMD Ryzen 3             | 2         | 0.78%   |
| AMD E1                  | 2         | 0.78%   |
| AMD E                   | 2         | 0.78%   |
| Intel Xeon              | 1         | 0.39%   |
| Intel Pentium Dual-Core | 1         | 0.39%   |
| Intel Pentium Dual      | 1         | 0.39%   |
| Intel Genuine           | 1         | 0.39%   |
| Intel Celeron M         | 1         | 0.39%   |
| AMD C-50                | 1         | 0.39%   |
| AMD A12                 | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 124       | 48.06%  |
| 4       | 91        | 35.27%  |
| 8       | 20        | 7.75%   |
| 6       | 13        | 5.04%   |
| 1       | 7         | 2.71%   |
| 16      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 258       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 216       | 83.72%  |
| 1       | 41        | 15.89%  |
| Unknown | 1         | 0.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 252       | 96.92%  |
| 64-bit         | 3         | 1.15%   |
| 32-bit         | 3         | 1.15%   |
| Unknown        | 2         | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 29%     |
| 0x206a7    | 16        | 5.95%   |
| 0x306a9    | 12        | 4.46%   |
| 0x40651    | 11        | 4.09%   |
| 0x806ec    | 10        | 3.72%   |
| 0x806ea    | 10        | 3.72%   |
| 0x406e3    | 10        | 3.72%   |
| 0x306d4    | 9         | 3.35%   |
| 0x806e9    | 8         | 2.97%   |
| 0x08108109 | 8         | 2.97%   |
| 0x306c3    | 6         | 2.23%   |
| 0x08108102 | 6         | 2.23%   |
| 0x906ea    | 5         | 1.86%   |
| 0x806c1    | 5         | 1.86%   |
| 0x706e5    | 5         | 1.86%   |
| 0x0a50000c | 5         | 1.86%   |
| 0x20655    | 4         | 1.49%   |
| 0x806eb    | 3         | 1.12%   |
| 0x30678    | 3         | 1.12%   |
| 0x20652    | 3         | 1.12%   |
| 0x10661    | 3         | 1.12%   |
| 0x08608103 | 3         | 1.12%   |
| 0x08600106 | 3         | 1.12%   |
| 0xa0652    | 2         | 0.74%   |
| 0x906e9    | 2         | 0.74%   |
| 0x806d1    | 2         | 0.74%   |
| 0x1067a    | 2         | 0.74%   |
| 0x0a404101 | 2         | 0.74%   |
| 0x08600104 | 2         | 0.74%   |
| 0x08600102 | 2         | 0.74%   |
| 0x06006704 | 2         | 0.74%   |
| 0x05000029 | 2         | 0.74%   |
| 0x906a4    | 1         | 0.37%   |
| 0x906a3    | 1         | 0.37%   |
| 0x706a1    | 1         | 0.37%   |
| 0x6fd      | 1         | 0.37%   |
| 0x6e8      | 1         | 0.37%   |
| 0x6d8      | 1         | 0.37%   |
| 0x506e3    | 1         | 0.37%   |
| 0x406c4    | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 56        | 21.71%  |
| Haswell          | 24        | 9.3%    |
| Zen+             | 18        | 6.98%   |
| SandyBridge      | 18        | 6.98%   |
| IvyBridge        | 18        | 6.98%   |
| Skylake          | 15        | 5.81%   |
| Broadwell        | 11        | 4.26%   |
| Zen 2            | 9         | 3.49%   |
| Westmere         | 9         | 3.49%   |
| IceLake          | 9         | 3.49%   |
| Unknown          | 9         | 3.49%   |
| TigerLake        | 7         | 2.71%   |
| Silvermont       | 7         | 2.71%   |
| Zen 3            | 6         | 2.33%   |
| Goldmont plus    | 5         | 1.94%   |
| Excavator        | 5         | 1.94%   |
| Zen              | 4         | 1.55%   |
| Penryn           | 4         | 1.55%   |
| Core             | 4         | 1.55%   |
| Piledriver       | 3         | 1.16%   |
| CometLake        | 3         | 1.16%   |
| Bobcat           | 3         | 1.16%   |
| Puma             | 2         | 0.78%   |
| P6               | 2         | 0.78%   |
| Jaguar           | 2         | 0.78%   |
| Bonnell          | 2         | 0.78%   |
| Alderlake Hybrid | 2         | 0.78%   |
| Nehalem          | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 185       | 55.06%  |
| AMD                              | 84        | 25%     |
| Nvidia                           | 66        | 19.64%  |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 18        | 5.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 18        | 5.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 17        | 4.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 17        | 4.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 17        | 4.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 3.16%   |
| Intel HD Graphics 620                                                                 | 11        | 3.16%   |
| Intel HD Graphics 5500                                                                | 11        | 3.16%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 10        | 2.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 9         | 2.59%   |
| AMD Renoir                                                                            | 9         | 2.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 7         | 2.01%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 2.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 1.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 6         | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 1.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 5         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 5         | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 5         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 5         | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 5         | 1.44%   |
| Nvidia GM108M [GeForce MX110]                                                         | 4         | 1.15%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 4         | 1.15%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 4         | 1.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 4         | 1.15%   |
| AMD Lucienne                                                                          | 4         | 1.15%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 0.86%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 3         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 3         | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 3         | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 3         | 0.86%   |
| AMD Rembrandt [Radeon 680M]                                                           | 3         | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.57%   |
| Nvidia GM108M [GeForce MX130]                                                         | 2         | 0.57%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 2         | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 116       | 44.96%  |
| Intel + Nvidia | 47        | 18.22%  |
| 1 x AMD        | 46        | 17.83%  |
| Intel + AMD    | 20        | 7.75%   |
| AMD + Nvidia   | 11        | 4.26%   |
| 1 x Nvidia     | 8         | 3.1%    |
| 2 x AMD        | 7         | 2.71%   |
| 2 x Intel      | 2         | 0.78%   |
| 1 x SiS        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 219       | 83.91%  |
| Proprietary | 37        | 14.18%  |
| Unknown     | 5         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 57.95%  |
| 1.01-2.0   | 43        | 16.29%  |
| 0.01-0.5   | 36        | 13.64%  |
| 3.01-4.0   | 14        | 5.3%    |
| 0.51-1.0   | 9         | 3.41%   |
| 5.01-6.0   | 5         | 1.89%   |
| 7.01-8.0   | 3         | 1.14%   |
| 8.01-16.0  | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 66        | 22.3%   |
| BOE                 | 51        | 17.23%  |
| Samsung Electronics | 44        | 14.86%  |
| AU Optronics        | 42        | 14.19%  |
| LG Display          | 34        | 11.49%  |
| Goldstar            | 9         | 3.04%   |
| PANDA               | 7         | 2.36%   |
| Hewlett-Packard     | 4         | 1.35%   |
| Sharp               | 3         | 1.01%   |
| Apple               | 3         | 1.01%   |
| AOC                 | 3         | 1.01%   |
| TMX                 | 2         | 0.68%   |
| Sony                | 2         | 0.68%   |
| Lenovo              | 2         | 0.68%   |
| JRY                 | 2         | 0.68%   |
| HannStar            | 2         | 0.68%   |
| Dell                | 2         | 0.68%   |
| Unknown             | 2         | 0.68%   |
| ViewSonic           | 1         | 0.34%   |
| Unknown (XXX)       | 1         | 0.34%   |
| Panasonic           | 1         | 0.34%   |
| MSI                 | 1         | 0.34%   |
| Mi                  | 1         | 0.34%   |
| LGD                 | 1         | 0.34%   |
| LG Philips          | 1         | 0.34%   |
| InnoLux Display     | 1         | 0.34%   |
| InfoVision          | 1         | 0.34%   |
| HUAWEI              | 1         | 0.34%   |
| Hitachi             | 1         | 0.34%   |
| EXP                 | 1         | 0.34%   |
| DZX                 | 1         | 0.34%   |
| CSO                 | 1         | 0.34%   |
| AGO                 | 1         | 0.34%   |
| Acer                | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 4.04%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 9         | 3.03%   |
| Chimei Innolux P130ZDZ-EF1 CMN8201 2160x1440 275x183mm 13.0-inch     | 5         | 1.68%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 1.35%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 1.01%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 1.01%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 3         | 1.01%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 1.01%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 1.01%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.67%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.67%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 2         | 0.67%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.67%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch         | 2         | 0.67%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.67%   |
| JRY DX238A1 JRY2380 1920x1080 368x207mm 16.6-inch                    | 2         | 0.67%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.67%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                 | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch      | 2         | 0.67%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.67%   |
| BOE LCD Monitor BOE066E 1366x768 344x194mm 15.5-inch                 | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch        | 2         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 143       | 50.35%  |
| 1920x1080 (FHD)   | 89        | 31.34%  |
| 1600x900 (HD+)    | 8         | 2.82%   |
| 1280x800 (WXGA)   | 8         | 2.82%   |
| 3840x2160 (4K)    | 5         | 1.76%   |
| 2160x1440         | 5         | 1.76%   |
| 1360x768          | 4         | 1.41%   |
| 1440x900 (WXGA+)  | 3         | 1.06%   |
| 3200x1800 (QHD+)  | 2         | 0.7%    |
| 2560x1600         | 2         | 0.7%    |
| 2560x1440 (QHD)   | 2         | 0.7%    |
| 1920x1200 (WUXGA) | 2         | 0.7%    |
| 1024x600          | 2         | 0.7%    |
| Unknown           | 2         | 0.7%    |
| 640x480           | 1         | 0.35%   |
| 3840x1080         | 1         | 0.35%   |
| 3200x2000         | 1         | 0.35%   |
| 2880x1800         | 1         | 0.35%   |
| 2520x1680         | 1         | 0.35%   |
| 1280x720 (HD)     | 1         | 0.35%   |
| 1024x768 (XGA)    | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 137       | 46.76%  |
| 13      | 49        | 16.72%  |
| 14      | 40        | 13.65%  |
| 23      | 12        | 4.1%    |
| 17      | 8         | 2.73%   |
| 21      | 6         | 2.05%   |
| 18      | 6         | 2.05%   |
| 11      | 5         | 1.71%   |
| 24      | 4         | 1.37%   |
| 16      | 3         | 1.02%   |
| 12      | 3         | 1.02%   |
| Unknown | 3         | 1.02%   |
| 72      | 2         | 0.68%   |
| 31      | 2         | 0.68%   |
| 27      | 2         | 0.68%   |
| 20      | 2         | 0.68%   |
| 10      | 2         | 0.68%   |
| 84      | 1         | 0.34%   |
| 60      | 1         | 0.34%   |
| 54      | 1         | 0.34%   |
| 48      | 1         | 0.34%   |
| 46      | 1         | 0.34%   |
| 39      | 1         | 0.34%   |
| 19      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 213       | 73.2%   |
| 201-300     | 22        | 7.56%   |
| 501-600     | 18        | 6.19%   |
| 401-500     | 15        | 5.15%   |
| 351-400     | 10        | 3.44%   |
| 1001-1500   | 4         | 1.37%   |
| 1501-2000   | 3         | 1.03%   |
| Unknown     | 3         | 1.03%   |
| 601-700     | 2         | 0.69%   |
| 801-900     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 227       | 87.64%  |
| 16/10   | 20        | 7.72%   |
| 3/2     | 6         | 2.32%   |
| 4/3     | 3         | 1.16%   |
| Unknown | 3         | 1.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 137       | 46.76%  |
| 81-90          | 78        | 26.62%  |
| 201-250        | 20        | 6.83%   |
| 71-80          | 10        | 3.41%   |
| More than 1000 | 6         | 2.05%   |
| 151-200        | 6         | 2.05%   |
| 121-130        | 6         | 2.05%   |
| 51-60          | 5         | 1.71%   |
| 141-150        | 5         | 1.71%   |
| 111-120        | 3         | 1.02%   |
| Unknown        | 3         | 1.02%   |
| 61-70          | 2         | 0.68%   |
| 351-500        | 2         | 0.68%   |
| 41-50          | 2         | 0.68%   |
| 301-350        | 2         | 0.68%   |
| 131-140        | 2         | 0.68%   |
| 501-1000       | 2         | 0.68%   |
| 91-100         | 2         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 141       | 48.96%  |
| 121-160       | 81        | 28.13%  |
| 51-100        | 39        | 13.54%  |
| 161-240       | 13        | 4.51%   |
| 1-50          | 7         | 2.43%   |
| More than 240 | 4         | 1.39%   |
| Unknown       | 3         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 211       | 79.92%  |
| 2     | 44        | 16.67%  |
| 0     | 7         | 2.65%   |
| 3     | 2         | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 161       | 40.35%  |
| Intel                            | 95        | 23.81%  |
| Qualcomm Atheros                 | 74        | 18.55%  |
| Broadcom                         | 18        | 4.51%   |
| TP-Link                          | 8         | 2.01%   |
| MediaTek                         | 8         | 2.01%   |
| Ralink                           | 7         | 1.75%   |
| Xiaomi                           | 5         | 1.25%   |
| Marvell Technology Group         | 4         | 1%      |
| ASIX Electronics                 | 3         | 0.75%   |
| Samsung Electronics              | 2         | 0.5%    |
| Ralink Technology                | 2         | 0.5%    |
| Motorola PCS                     | 2         | 0.5%    |
| ICS Advent                       | 2         | 0.5%    |
| T & A Mobile Phones              | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| OPPO Electronics                 | 1         | 0.25%   |
| Microsoft                        | 1         | 0.25%   |
| Lenovo                           | 1         | 0.25%   |
| DisplayLink                      | 1         | 0.25%   |
| Broadcom Limited                 | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 104       | 21.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 30        | 6.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 5.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 3.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 3.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.63%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.43%   |
| Intel Wireless 8260                                                     | 7         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.22%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 5         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.02%   |
| Intel Wireless 7265                                                     | 5         | 1.02%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.02%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.82%   |
| Intel Wireless 7260                                                     | 4         | 0.82%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.61%   |
| Intel WiFi Link 5100                                                    | 3         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 91        | 34.34%  |
| Qualcomm Atheros      | 67        | 25.28%  |
| Realtek Semiconductor | 66        | 24.91%  |
| Broadcom              | 16        | 6.04%   |
| MediaTek              | 8         | 3.02%   |
| TP-Link               | 7         | 2.64%   |
| Ralink                | 7         | 2.64%   |
| Ralink Technology     | 2         | 0.75%   |
| Broadcom Limited      | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 9.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 6.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 6.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 3.02%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.64%   |
| Intel Wireless 8260                                                     | 7         | 2.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.64%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 2.64%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 2.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 2.26%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.89%   |
| Intel Wireless 7265                                                     | 5         | 1.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.89%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 1.51%   |
| Intel Wireless 7260                                                     | 4         | 1.51%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.13%   |
| Intel WiFi Link 5100                                                    | 3         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.13%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.75%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.75%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.75%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 144       | 64.57%  |
| Intel                            | 32        | 14.35%  |
| Qualcomm Atheros                 | 17        | 7.62%   |
| Xiaomi                           | 5         | 2.24%   |
| Marvell Technology Group         | 4         | 1.79%   |
| Broadcom                         | 4         | 1.79%   |
| ASIX Electronics                 | 3         | 1.35%   |
| Samsung Electronics              | 2         | 0.9%    |
| Motorola PCS                     | 2         | 0.9%    |
| ICS Advent                       | 2         | 0.9%    |
| TP-Link                          | 1         | 0.45%   |
| T & A Mobile Phones              | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| OPPO Electronics                 | 1         | 0.45%   |
| Microsoft                        | 1         | 0.45%   |
| Lenovo                           | 1         | 0.45%   |
| DisplayLink                      | 1         | 0.45%   |
| Apple                            | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 104       | 46.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 30        | 13.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 2.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.89%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.89%   |
| Motorola PCS moto g51 5G                                                       | 2         | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.89%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.89%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.89%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.89%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.89%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.89%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.89%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.44%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.44%   |
| OPPO 8                                                                         | 1         | 0.44%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.44%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.44%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.44%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 255       | 54.37%  |
| Ethernet | 214       | 45.63%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 74.28%  |
| Ethernet | 71        | 25.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 195       | 75.58%  |
| 1     | 60        | 23.26%  |
| 0     | 3         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 76.89%  |
| Yes  | 61        | 23.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 33.03%  |
| Realtek Semiconductor           | 45        | 20.64%  |
| Qualcomm Atheros Communications | 35        | 16.06%  |
| IMC Networks                    | 17        | 7.8%    |
| Lite-On Technology              | 12        | 5.5%    |
| Toshiba                         | 8         | 3.67%   |
| Ralink                          | 6         | 2.75%   |
| Foxconn / Hon Hai               | 5         | 2.29%   |
| Broadcom                        | 5         | 2.29%   |
| Hewlett-Packard                 | 3         | 1.38%   |
| Apple                           | 3         | 1.38%   |
| Dell                            | 2         | 0.92%   |
| Cambridge Silicon Radio         | 2         | 0.92%   |
| Realtek                         | 1         | 0.46%   |
| Foxconn International           | 1         | 0.46%   |
| Alps Electric                   | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 11.47%  |
| Realtek Bluetooth Radio                             | 22        | 10.09%  |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 9.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 9.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 8.72%   |
| Intel AX201 Bluetooth                               | 10        | 4.59%   |
| Ralink RT3290 Bluetooth                             | 6         | 2.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.75%   |
| Intel AX200 Bluetooth                               | 6         | 2.75%   |
| IMC Networks Wireless_Device                        | 6         | 2.75%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.75%   |
| Toshiba Bluetooth Device                            | 5         | 2.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 1.83%   |
| IMC Networks Bluetooth Device                       | 4         | 1.83%   |
| Lite-On Bluetooth Radio                             | 3         | 1.38%   |
| Lite-On Bluetooth Device                            | 3         | 1.38%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.38%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.92%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.92%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.92%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.46%   |
| Toshiba BCM43142A0                                  | 1         | 0.46%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.46%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.46%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.46%   |
| Realtek Bluetooth Radio                             | 1         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.46%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.46%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.46%   |
| Intel Bluetooth Device                              | 1         | 0.46%   |
| Intel AX210 Bluetooth                               | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 194       | 63.4%   |
| AMD                              | 65        | 21.24%  |
| Nvidia                           | 34        | 11.11%  |
| Generalplus Technology           | 3         | 0.98%   |
| C-Media Electronics              | 3         | 0.98%   |
| Kingston Technology              | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Razer USA                        | 1         | 0.33%   |
| Pixart Imaging                   | 1         | 0.33%   |
| Hewlett-Packard                  | 1         | 0.33%   |
| GN Netcom                        | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 44        | 11.2%   |
| Intel Sunrise Point-LP HD Audio                                            | 41        | 10.43%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23        | 5.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 21        | 5.34%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 4.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 4.33%   |
| Intel Haswell-ULT HD Audio Controller                                      | 16        | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 3.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 2.8%    |
| Intel Broadwell-U Audio Controller                                         | 11        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 2.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 2.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 1.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 1.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.78%   |
| AMD FCH Azalia Controller                                                  | 7         | 1.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.53%   |
| Nvidia Audio device                                                        | 5         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.02%   |
| AMD High Definition Audio Controller                                       | 4         | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.76%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.76%   |
| Generalplus Technology USB Audio Device                                    | 3         | 0.76%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.51%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 58        | 29.44%  |
| SK hynix            | 40        | 20.3%   |
| Micron Technology   | 28        | 14.21%  |
| Kingston            | 24        | 12.18%  |
| Ramaxel Technology  | 11        | 5.58%   |
| Unknown             | 10        | 5.08%   |
| Unknown (ABCD)      | 5         | 2.54%   |
| Team                | 5         | 2.54%   |
| Crucial             | 4         | 2.03%   |
| Hewlett-Packard     | 3         | 1.52%   |
| Elpida              | 3         | 1.52%   |
| Patriot             | 1         | 0.51%   |
| Kllisre             | 1         | 0.51%   |
| Goldkey             | 1         | 0.51%   |
| CSX                 | 1         | 0.51%   |
| Corsair             | 1         | 0.51%   |
| A-DATA Technology   | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.87%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 2.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 2.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 2.39%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 4         | 1.91%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 1.91%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.44%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.44%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 3         | 1.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.96%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.96%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.96%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.96%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.48%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 69        | 46%     |
| DDR3    | 57        | 38%     |
| LPDDR4  | 11        | 7.33%   |
| DDR2    | 4         | 2.67%   |
| LPDDR3  | 3         | 2%      |
| DDR5    | 3         | 2%      |
| SDRAM   | 2         | 1.33%   |
| Unknown | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 95.33%  |
| Row Of Chips | 7         | 4.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 75        | 42.13%  |
| 4096  | 63        | 35.39%  |
| 16384 | 17        | 9.55%   |
| 2048  | 14        | 7.87%   |
| 32768 | 4         | 2.25%   |
| 1024  | 4         | 2.25%   |
| 512   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 45        | 26.32%  |
| 2667    | 43        | 25.15%  |
| 3200    | 33        | 19.3%   |
| 2400    | 12        | 7.02%   |
| 3266    | 6         | 3.51%   |
| 1334    | 6         | 3.51%   |
| 1333    | 5         | 2.92%   |
| 2133    | 4         | 2.34%   |
| 4800    | 3         | 1.75%   |
| Unknown | 3         | 1.75%   |
| 1867    | 2         | 1.17%   |
| 1067    | 2         | 1.17%   |
| 4267    | 1         | 0.58%   |
| 4199    | 1         | 0.58%   |
| 2933    | 1         | 0.58%   |
| 1066    | 1         | 0.58%   |
| 800     | 1         | 0.58%   |
| 667     | 1         | 0.58%   |
| 533     | 1         | 0.58%   |

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
| Chicony Electronics                    | 56        | 22.95%  |
| IMC Networks                           | 27        | 11.07%  |
| Microdia                               | 20        | 8.2%    |
| Realtek Semiconductor                  | 19        | 7.79%   |
| Syntek                                 | 15        | 6.15%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.74%   |
| Bison Electronics                      | 13        | 5.33%   |
| Sunplus Innovation Technology          | 12        | 4.92%   |
| Quanta                                 | 12        | 4.92%   |
| Suyin                                  | 11        | 4.51%   |
| Lite-On Technology                     | 11        | 4.51%   |
| Acer                                   | 9         | 3.69%   |
| Luxvisions Innotech Limited            | 5         | 2.05%   |
| Sonix Technology                       | 4         | 1.64%   |
| Importek                               | 4         | 1.64%   |
| Samsung Electronics                    | 2         | 0.82%   |
| Ricoh                                  | 2         | 0.82%   |
| Apple                                  | 2         | 0.82%   |
| Alcor Micro                            | 2         | 0.82%   |
| Logitech                               | 1         | 0.41%   |
| Jieli Technology                       | 1         | 0.41%   |
| ASUSTek Computer                       | 1         | 0.41%   |
| ANYKA                                  | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 12        | 4.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 3.27%   |
| Chicony Integrated Camera                                                  | 6         | 2.45%   |
| Chicony HP Truevision HD                                                   | 6         | 2.45%   |
| Chicony EasyCamera                                                         | 6         | 2.45%   |
| Bison Integrated Camera                                                    | 6         | 2.45%   |
| Microdia Webcam Vitade AF                                                  | 5         | 2.04%   |
| Lite-On Integrated Camera                                                  | 5         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 2.04%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.63%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.63%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 1.63%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.63%   |
| IMC Networks Integrated Camera                                             | 4         | 1.63%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 1.63%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.63%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.63%   |
| Lite-On HP HD Camera                                                       | 3         | 1.22%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.22%   |
| Chicony HP HD Webcam                                                       | 3         | 1.22%   |
| Chicony HD WebCam                                                          | 3         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.22%   |
| Acer Integrated Camera                                                     | 3         | 1.22%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.82%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.82%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.82%   |
| Realtek Integrated Webcam                                                  | 2         | 0.82%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.82%   |
| Quanta HP Webcam                                                           | 2         | 0.82%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.82%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 0.82%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.82%   |
| IMC Networks HD Camera                                                     | 2         | 0.82%   |
| Chicony Web Camera - HD                                                    | 2         | 0.82%   |
| Chicony VGA Webcam                                                         | 2         | 0.82%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.82%   |

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
| 0     | 165       | 62.74%  |
| 1     | 79        | 30.04%  |
| 2     | 17        | 6.46%   |
| 3     | 2         | 0.76%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 40.87%  |
| Graphics card            | 21        | 18.26%  |
| Net/wireless             | 14        | 12.17%  |
| Chipcard                 | 11        | 9.57%   |
| Bluetooth                | 8         | 6.96%   |
| Multimedia controller    | 5         | 4.35%   |
| Storage                  | 2         | 1.74%   |
| Communication controller | 2         | 1.74%   |
| Card reader              | 2         | 1.74%   |
| Camera                   | 2         | 1.74%   |
| Net/ethernet             | 1         | 0.87%   |

