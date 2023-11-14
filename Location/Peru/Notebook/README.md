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

Total: 382

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo     | IdeaPad 110-15ISK 80UD      | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| HP         | Laptop 15-fc0xxx            | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| Lenovo     | ThinkPad T16 Gen 1 21BWS... | [8f20a345e3](https://linux-hardware.org/?probe=8f20a345e3) | Oct 24, 2023 |
| HP         | 14                          | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| Lenovo     | IdeaPad 110-15IBR 80T7      | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
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
| Ubuntu 20.04                 | 32        | 11.35%  |
| Arch Rolling                 | 13        | 4.61%   |
| Ubuntu 22.04                 | 12        | 4.26%   |
| OpenMandriva 4.3             | 11        | 3.9%    |
| Ubuntu 18.04                 | 9         | 3.19%   |
| Linux Mint 21.1              | 9         | 3.19%   |
| Fedora 38                    | 8         | 2.84%   |
| OpenMandriva 23.03           | 7         | 2.48%   |
| Zorin 15                     | 6         | 2.13%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 2.13%   |
| Manjaro                      | 6         | 2.13%   |
| Linux Mint 20.3              | 6         | 2.13%   |
| Ubuntu 19.10                 | 5         | 1.77%   |
| Fedora 37                    | 5         | 1.77%   |
| Arch                         | 5         | 1.77%   |
| Xubuntu 20.04                | 4         | 1.42%   |
| Ubuntu 21.04                 | 4         | 1.42%   |
| Pop!_OS 21.10                | 4         | 1.42%   |
| OpenMandriva 23.01           | 4         | 1.42%   |
| Debian 11                    | 4         | 1.42%   |
| ArcoLinux Rolling            | 4         | 1.42%   |
| Ubuntu 19.04                 | 3         | 1.06%   |
| Pop!_OS 22.04                | 3         | 1.06%   |
| Pop!_OS 20.10                | 3         | 1.06%   |
| OpenMandriva 4.2             | 3         | 1.06%   |
| OpenMandriva 23.08           | 3         | 1.06%   |
| Manjaro 20.1                 | 3         | 1.06%   |
| KDE neon 20.04               | 3         | 1.06%   |
| Fedora 35                    | 3         | 1.06%   |
| EndeavourOS Rolling          | 3         | 1.06%   |
| Elementary 5.1.7             | 3         | 1.06%   |
| Debian 10                    | 3         | 1.06%   |
| ROSA R9                      | 2         | 0.71%   |
| ROSA R10                     | 2         | 0.71%   |
| ROSA 12.3                    | 2         | 0.71%   |
| ROSA 12.2                    | 2         | 0.71%   |
| Pop!_OS 20.04                | 2         | 0.71%   |
| OpenMandriva 4.90            | 2         | 0.71%   |
| OpenMandriva 23.06           | 2         | 0.71%   |
| LMDE 5                       | 2         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 66        | 24.18%  |
| OpenMandriva  | 31        | 11.36%  |
| Fedora        | 22        | 8.06%   |
| Linux Mint    | 21        | 7.69%   |
| Arch          | 19        | 6.96%   |
| Pop!_OS       | 13        | 4.76%   |
| Manjaro       | 13        | 4.76%   |
| ROSA          | 10        | 3.66%   |
| Debian        | 10        | 3.66%   |
| Zorin         | 7         | 2.56%   |
| openSUSE      | 6         | 2.2%    |
| KDE neon      | 5         | 1.83%   |
| Xubuntu       | 4         | 1.47%   |
| Kubuntu       | 4         | 1.47%   |
| Elementary    | 4         | 1.47%   |
| ArcoLinux     | 4         | 1.47%   |
| Ubuntu MATE   | 3         | 1.1%    |
| Lubuntu       | 3         | 1.1%    |
| Kali          | 3         | 1.1%    |
| Endless       | 3         | 1.1%    |
| EndeavourOS   | 3         | 1.1%    |
| SteamOS       | 2         | 0.73%   |
| Parrot        | 2         | 0.73%   |
| LMDE          | 2         | 0.73%   |
| CentOS        | 2         | 0.73%   |
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
| 5.16.7-desktop-1omv4003  | 11        | 3.59%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.96%   |
| 5.13.0-40-generic        | 5         | 1.63%   |
| 5.4.0-42-generic         | 4         | 1.31%   |
| 6.3.5-desktop-3omv2390   | 3         | 0.98%   |
| 6.3.5-200.fc38.x86_64    | 3         | 0.98%   |
| 5.4.0-26-generic         | 3         | 0.98%   |
| 5.3.0-40-generic         | 3         | 0.98%   |
| 5.15.0-76-generic        | 3         | 0.98%   |
| 5.15.0-71-generic        | 3         | 0.98%   |
| 5.13.0-51-generic        | 3         | 0.98%   |
| 5.11.0-25-generic        | 3         | 0.98%   |
| 5.10.0-13-amd64          | 3         | 0.98%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.65%   |
| 6.3.6-arch1-1            | 2         | 0.65%   |
| 6.2.0-24-generic         | 2         | 0.65%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.65%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.65%   |
| 5.8.0-44-generic         | 2         | 0.65%   |
| 5.4.0-7642-generic       | 2         | 0.65%   |
| 5.4.0-66-generic         | 2         | 0.65%   |
| 5.4.0-65-generic         | 2         | 0.65%   |
| 5.4.0-58-generic         | 2         | 0.65%   |
| 5.4.0-54-generic         | 2         | 0.65%   |
| 5.4.0-39-generic         | 2         | 0.65%   |
| 5.4.0-33-generic         | 2         | 0.65%   |
| 5.4.0-28-generic         | 2         | 0.65%   |
| 5.4.0-109-generic        | 2         | 0.65%   |
| 5.3.0-42-generic         | 2         | 0.65%   |
| 5.3.0-23-generic         | 2         | 0.65%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.65%   |
| 5.17.5-arch1-1           | 2         | 0.65%   |
| 5.16.19-76051619-generic | 2         | 0.65%   |
| 5.15.49-1-lts            | 2         | 0.65%   |
| 5.15.0-58-generic        | 2         | 0.65%   |
| 5.15.0-57-generic        | 2         | 0.65%   |
| 5.15.0-52-generic        | 2         | 0.65%   |
| 5.15.0-25-generic        | 2         | 0.65%   |
| 5.13.0-30-generic        | 2         | 0.65%   |
| 5.11.0-7614-generic      | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 12.79%  |
| 5.15.0  | 23        | 7.74%   |
| 5.13.0  | 14        | 4.71%   |
| 5.11.0  | 14        | 4.71%   |
| 5.3.0   | 12        | 4.04%   |
| 5.16.7  | 11        | 3.7%    |
| 6.2.0   | 9         | 3.03%   |
| 6.2.6   | 7         | 2.36%   |
| 5.8.0   | 7         | 2.36%   |
| 5.10.0  | 7         | 2.36%   |
| 5.0.0   | 7         | 2.36%   |
| 4.15.0  | 7         | 2.36%   |
| 6.3.5   | 6         | 2.02%   |
| 4.18.0  | 6         | 2.02%   |
| 5.19.0  | 5         | 1.68%   |
| 6.3.6   | 4         | 1.35%   |
| 6.4.11  | 3         | 1.01%   |
| 6.0.0   | 3         | 1.01%   |
| 5.17.5  | 3         | 1.01%   |
| 4.9.60  | 3         | 1.01%   |
| 6.5.0   | 2         | 0.67%   |
| 6.1.9   | 2         | 0.67%   |
| 6.1.4   | 2         | 0.67%   |
| 6.1.31  | 2         | 0.67%   |
| 6.1.11  | 2         | 0.67%   |
| 6.1.1   | 2         | 0.67%   |
| 6.0.7   | 2         | 0.67%   |
| 6.0.15  | 2         | 0.67%   |
| 5.18.12 | 2         | 0.67%   |
| 5.16.19 | 2         | 0.67%   |
| 5.15.49 | 2         | 0.67%   |
| 5.12.10 | 2         | 0.67%   |
| 5.10.74 | 2         | 0.67%   |
| 5.10.14 | 2         | 0.67%   |
| 4.9.20  | 2         | 0.67%   |
| 4.19.0  | 2         | 0.67%   |
| 6.5.9   | 1         | 0.34%   |
| 6.5.8   | 1         | 0.34%   |
| 6.5.3   | 1         | 0.34%   |
| 6.4.8   | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 14.14%  |
| 5.15    | 35        | 12.07%  |
| 6.2     | 22        | 7.59%   |
| 5.13    | 15        | 5.17%   |
| 5.11    | 15        | 5.17%   |
| 5.10    | 15        | 5.17%   |
| 5.16    | 14        | 4.83%   |
| 6.1     | 13        | 4.48%   |
| 6.3     | 12        | 4.14%   |
| 6.0     | 12        | 4.14%   |
| 5.3     | 12        | 4.14%   |
| 6.4     | 10        | 3.45%   |
| 5.8     | 10        | 3.45%   |
| 5.19    | 7         | 2.41%   |
| 5.17    | 7         | 2.41%   |
| 5.0     | 7         | 2.41%   |
| 4.15    | 7         | 2.41%   |
| 4.18    | 6         | 2.07%   |
| 6.5     | 5         | 1.72%   |
| 5.18    | 4         | 1.38%   |
| 5.12    | 4         | 1.38%   |
| 4.9     | 4         | 1.38%   |
| 5.14    | 3         | 1.03%   |
| 5.9     | 2         | 0.69%   |
| 5.7     | 2         | 0.69%   |
| 5.6     | 2         | 0.69%   |
| 4.19    | 2         | 0.69%   |
| 5.1     | 1         | 0.34%   |
| 4.16    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 255       | 96.96%  |
| i686   | 8         | 3.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 114       | 41.91%  |
| KDE5            | 59        | 21.69%  |
| XFCE            | 23        | 8.46%   |
| X-Cinnamon      | 18        | 6.62%   |
| Unknown         | 16        | 5.88%   |
| MATE            | 8         | 2.94%   |
| KDE             | 7         | 2.57%   |
| Pantheon        | 4         | 1.47%   |
| LXQt            | 4         | 1.47%   |
| KDE4            | 4         | 1.47%   |
| i3              | 4         | 1.47%   |
| sway            | 2         | 0.74%   |
| LXDE            | 2         | 0.74%   |
| Budgie          | 2         | 0.74%   |
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
| X11     | 195       | 71.17%  |
| Wayland | 61        | 22.26%  |
| Unknown | 15        | 5.47%   |
| Tty     | 3         | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 121       | 44.65%  |
| SDDM    | 50        | 18.45%  |
| GDM     | 39        | 14.39%  |
| LightDM | 32        | 11.81%  |
| GDM3    | 20        | 7.38%   |
| KDM     | 4         | 1.48%   |
| TDM     | 2         | 0.74%   |
| XDM     | 1         | 0.37%   |
| Ly      | 1         | 0.37%   |
| LXDM    | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 127       | 47.21%  |
| en_US   | 76        | 28.25%  |
| es_ES   | 24        | 8.92%   |
| Unknown | 16        | 5.95%   |
| es_MX   | 8         | 2.97%   |
| C       | 4         | 1.49%   |
| it_IT   | 2         | 0.74%   |
| fr_FR   | 2         | 0.74%   |
| en_GB   | 2         | 0.74%   |
| ca_ES   | 2         | 0.74%   |
| es_VE   | 1         | 0.37%   |
| es_CO   | 1         | 0.37%   |
| en_NZ   | 1         | 0.37%   |
| en_CA   | 1         | 0.37%   |
| de_DE   | 1         | 0.37%   |
| Default | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 149       | 55.81%  |
| BIOS | 118       | 44.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 198       | 73.06%  |
| Btrfs   | 30        | 11.07%  |
| Overlay | 23        | 8.49%   |
| Xfs     | 7         | 2.58%   |
| Unknown | 7         | 2.58%   |
| Tmpfs   | 5         | 1.85%   |
| Ext3    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 130       | 48.51%  |
| GPT     | 110       | 41.04%  |
| MBR     | 28        | 10.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 232       | 86.89%  |
| Yes       | 35        | 13.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 155       | 57.84%  |
| Yes       | 113       | 42.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 74        | 28.24%  |
| Lenovo              | 68        | 25.95%  |
| ASUSTek Computer    | 34        | 12.98%  |
| Dell                | 24        | 9.16%   |
| Toshiba             | 17        | 6.49%   |
| Acer                | 16        | 6.11%   |
| Sony                | 5         | 1.91%   |
| Chuwi               | 5         | 1.91%   |
| MSI                 | 4         | 1.53%   |
| HUAWEI              | 3         | 1.15%   |
| Apple               | 3         | 1.15%   |
| Advance             | 2         | 0.76%   |
| Samsung Electronics | 1         | 0.38%   |
| Razer               | 1         | 0.38%   |
| Google              | 1         | 0.38%   |
| eMachines           | 1         | 0.38%   |
| efirstview          | 1         | 0.38%   |
| Compal              | 1         | 0.38%   |
| Unknown             | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                       | 5         | 1.91%   |
| Lenovo V330-15IKB 81AX                   | 4         | 1.53%   |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 1.53%   |
| HP 14                                    | 4         | 1.53%   |
| Toshiba Satellite L45-B                  | 3         | 1.15%   |
| Lenovo V310-15ISK 80SY                   | 3         | 1.15%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 3         | 1.15%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 1.15%   |
| Toshiba Satellite C45-A                  | 2         | 0.76%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.76%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.76%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.76%   |
| Lenovo G400 20235                        | 2         | 0.76%   |
| HP ProBook 645 G4                        | 2         | 0.76%   |
| HP Pavilion g4                           | 2         | 0.76%   |
| HP Pavilion dv4                          | 2         | 0.76%   |
| HP Notebook                              | 2         | 0.76%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.76%   |
| HP Compaq Presario C700                  | 2         | 0.76%   |
| HP 450                                   | 2         | 0.76%   |
| HP 250 G7 Notebook PC                    | 2         | 0.76%   |
| HP 250 G5 Notebook PC                    | 2         | 0.76%   |
| Dell XPS 13 9360                         | 2         | 0.76%   |
| Dell Latitude E7450                      | 2         | 0.76%   |
| Dell G5 5505                             | 2         | 0.76%   |
| ASUS X550LD                              | 2         | 0.76%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR     | 2         | 0.76%   |
| ASUS ROG Strix G513RC_G513RC             | 2         | 0.76%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.76%   |
| Apple MacBookPro9,2                      | 2         | 0.76%   |
| Toshiba Satellite P755                   | 1         | 0.38%   |
| Toshiba Satellite P300                   | 1         | 0.38%   |
| Toshiba Satellite L855                   | 1         | 0.38%   |
| Toshiba Satellite L35                    | 1         | 0.38%   |
| Toshiba Satellite E205                   | 1         | 0.38%   |
| Toshiba Satellite C845                   | 1         | 0.38%   |
| Toshiba Satellite C655D                  | 1         | 0.38%   |
| Toshiba Satellite C645                   | 1         | 0.38%   |
| Toshiba Satellite C55-B                  | 1         | 0.38%   |
| Toshiba Satellite A665                   | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 25        | 9.54%   |
| HP Pavilion       | 19        | 7.25%   |
| Lenovo ThinkPad   | 18        | 6.87%   |
| Toshiba Satellite | 15        | 5.73%   |
| Acer Aspire       | 13        | 4.96%   |
| ASUS VivoBook     | 12        | 4.58%   |
| HP Laptop         | 11        | 4.2%    |
| HP ProBook        | 10        | 3.82%   |
| Dell Latitude     | 10        | 3.82%   |
| Dell Inspiron     | 7         | 2.67%   |
| Lenovo Legion     | 5         | 1.91%   |
| Chuwi GemiBook    | 5         | 1.91%   |
| ASUS ROG          | 5         | 1.91%   |
| Lenovo V330-15IKB | 4         | 1.53%   |
| HP 250            | 4         | 1.53%   |
| HP 14             | 4         | 1.53%   |
| Lenovo V310-15ISK | 3         | 1.15%   |
| HP OMEN           | 3         | 1.15%   |
| HP EliteBook      | 3         | 1.15%   |
| HP Compaq         | 3         | 1.15%   |
| ASUS ASUS         | 3         | 1.15%   |
| Lenovo G400       | 2         | 0.76%   |
| HP ZBook          | 2         | 0.76%   |
| HP Notebook       | 2         | 0.76%   |
| HP ENVY           | 2         | 0.76%   |
| HP 450            | 2         | 0.76%   |
| HP 255            | 2         | 0.76%   |
| HP 240            | 2         | 0.76%   |
| Dell XPS          | 2         | 0.76%   |
| Dell G5           | 2         | 0.76%   |
| ASUS X550LD       | 2         | 0.76%   |
| Apple MacBookPro9 | 2         | 0.76%   |
| Toshiba QOSMIO    | 1         | 0.38%   |
| Toshiba NB505     | 1         | 0.38%   |
| Sony VPCEL36FJ    | 1         | 0.38%   |
| Sony VPCEC2JFX    | 1         | 0.38%   |
| Sony VGN-FW56M    | 1         | 0.38%   |
| Sony VGN-FW170J   | 1         | 0.38%   |
| Sony SVF15A17CLB  | 1         | 0.38%   |
| Samsung 300E5EV   | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 29        | 11.07%  |
| 2019 | 27        | 10.31%  |
| 2021 | 25        | 9.54%   |
| 2018 | 25        | 9.54%   |
| 2016 | 23        | 8.78%   |
| 2014 | 20        | 7.63%   |
| 2013 | 20        | 7.63%   |
| 2012 | 20        | 7.63%   |
| 2017 | 18        | 6.87%   |
| 2011 | 17        | 6.49%   |
| 2022 | 9         | 3.44%   |
| 2015 | 7         | 2.67%   |
| 2010 | 6         | 2.29%   |
| 2008 | 6         | 2.29%   |
| 2009 | 4         | 1.53%   |
| 2007 | 4         | 1.53%   |
| 2023 | 1         | 0.38%   |
| 2006 | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 262       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 236       | 89.73%  |
| Enabled  | 27        | 10.27%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 261       | 99.62%  |
| Yes  | 1         | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 29.37%  |
| 8.01-16.0   | 77        | 28.62%  |
| 3.01-4.0    | 48        | 17.84%  |
| 16.01-24.0  | 36        | 13.38%  |
| 1.01-2.0    | 9         | 3.35%   |
| 32.01-64.0  | 7         | 2.6%    |
| 2.01-3.0    | 6         | 2.23%   |
| 24.01-32.0  | 4         | 1.49%   |
| 0.51-1.0    | 2         | 0.74%   |
| 64.01-256.0 | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 89        | 30.58%  |
| 1.01-2.0   | 85        | 29.21%  |
| 4.01-8.0   | 44        | 15.12%  |
| 3.01-4.0   | 40        | 13.75%  |
| 0.51-1.0   | 19        | 6.53%   |
| 8.01-16.0  | 12        | 4.12%   |
| 16.01-24.0 | 1         | 0.34%   |
| 0.01-0.5   | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 192       | 72.45%  |
| 2      | 66        | 24.91%  |
| 3      | 6         | 2.26%   |
| 0      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 65.65%  |
| Yes       | 90        | 34.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 82.51%  |
| No        | 46        | 17.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 259       | 98.85%  |
| No        | 3         | 1.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 84.41%  |
| No        | 41        | 15.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 262       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 173       | 63.6%   |
| Arequipa              | 24        | 8.82%   |
| Trujillo              | 17        | 6.25%   |
| Huancayo              | 8         | 2.94%   |
| Piura                 | 6         | 2.21%   |
| Cusco                 | 6         | 2.21%   |
| Chiclayo              | 5         | 1.84%   |
| Ica                   | 4         | 1.47%   |
| La Victoria           | 3         | 1.1%    |
| Tacna                 | 2         | 0.74%   |
| Ilo                   | 2         | 0.74%   |
| Callao                | 2         | 0.74%   |
| Tarapoto              | 1         | 0.37%   |
| Santiago de Surco     | 1         | 0.37%   |
| San Vicente de Canete | 1         | 0.37%   |
| San Isidro            | 1         | 0.37%   |
| San Borja             | 1         | 0.37%   |
| Punta Colorada        | 1         | 0.37%   |
| Puno                  | 1         | 0.37%   |
| Pisco                 | 1         | 0.37%   |
| Oxapampa              | 1         | 0.37%   |
| Moquegua              | 1         | 0.37%   |
| Miraflores District   | 1         | 0.37%   |
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
| WDC                            | 49        | 56     | 14.85%  |
| Toshiba                        | 45        | 55     | 13.64%  |
| Seagate                        | 42        | 50     | 12.73%  |
| Kingston                       | 39        | 48     | 11.82%  |
| Samsung Electronics            | 18        | 26     | 5.45%   |
| SanDisk                        | 17        | 20     | 5.15%   |
| Crucial                        | 13        | 19     | 3.94%   |
| Unknown                        | 11        | 11     | 3.33%   |
| Micron Technology              | 9         | 10     | 2.73%   |
| Intel                          | 9         | 11     | 2.73%   |
| SK hynix                       | 8         | 11     | 2.42%   |
| HGST                           | 8         | 8      | 2.42%   |
| KIOXIA                         | 6         | 7      | 1.82%   |
| Hitachi                        | 6         | 8      | 1.82%   |
| Hewlett-Packard                | 6         | 6      | 1.82%   |
| Netac                          | 5         | 5      | 1.52%   |
| Kingston Technology Company    | 4         | 4      | 1.21%   |
| TO Exter                       | 3         | 7      | 0.91%   |
| LITEON                         | 3         | 3      | 0.91%   |
| UMIS                           | 2         | 2      | 0.61%   |
| Silicon Motion                 | 2         | 2      | 0.61%   |
| Gigabyte Technology            | 2         | 2      | 0.61%   |
| China                          | 2         | 2      | 0.61%   |
| Apple                          | 2         | 2      | 0.61%   |
| A-DATA Technology              | 2         | 2      | 0.61%   |
| Unknown                        | 2         | 2      | 0.61%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.3%    |
| SSSTC                          | 1         | 1      | 0.3%    |
| Solid State Storage Technology | 1         | 1      | 0.3%    |
| Reletech-P400                  | 1         | 1      | 0.3%    |
| Phison Electronics             | 1         | 1      | 0.3%    |
| Phison                         | 1         | 1      | 0.3%    |
| Micron/Crucial Technology      | 1         | 4      | 0.3%    |
| Lenovo                         | 1         | 1      | 0.3%    |
| KingSpec                       | 1         | 1      | 0.3%    |
| ITHOO                          | 1         | 1      | 0.3%    |
| GLOWAY                         | 1         | 1      | 0.3%    |
| Fujitsu                        | 1         | 1      | 0.3%    |
| Dogfish                        | 1         | 1      | 0.3%    |
| Biwin Storage Technology       | 1         | 3      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 17        | 5.01%   |
| Kingston SA400S37240G 240GB SSD      | 16        | 4.72%   |
| Toshiba MQ04ABF100 1TB               | 10        | 2.95%   |
| Toshiba MQ01ABD100 1TB               | 9         | 2.65%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 7         | 2.06%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 1.47%   |
| Netac SSD 256GB                      | 5         | 1.47%   |
| Kingston SA400S37480G 480GB SSD      | 5         | 1.47%   |
| Crucial CT500MX500SSD4 500GB         | 5         | 1.47%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 1.18%   |
| Unknown SD32G  32GB                  | 4         | 1.18%   |
| Seagate ST9500325AS 500GB            | 4         | 1.18%   |
| Kingston SA400S37960G 960GB SSD      | 4         | 1.18%   |
| Intel SSDPEKNU512GZ 512GB            | 4         | 1.18%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 0.88%   |
| Unknown MMC Card  32GB               | 3         | 0.88%   |
| Toshiba MQ01ABD075 752GB             | 3         | 0.88%   |
| TO Exter nal USB 3.0 2TB             | 3         | 0.88%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.88%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 0.88%   |
| SanDisk NVMe SSD Drive 1TB           | 3         | 0.88%   |
| KIOXIA KBG40ZNS512G NVMe 512GB       | 3         | 0.88%   |
| Kingston Company SNV2S1000G 1TB      | 3         | 0.88%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 0.88%   |
| HGST HTS721010A9E630 1TB             | 3         | 0.88%   |
| HP SSD S700 500GB                    | 3         | 0.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.59%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 2         | 0.59%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.59%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 2         | 0.59%   |
| Toshiba MK2565GSXN 250GB             | 2         | 0.59%   |
| Toshiba HDWJ110 1TB                  | 2         | 0.59%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.59%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 0.59%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB   | 2         | 0.59%   |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.59%   |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.59%   |
| Kingston SNVS500G 500GB              | 2         | 0.59%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 43        | 53     | 32.58%  |
| Seagate | 42        | 48     | 31.82%  |
| WDC     | 30        | 33     | 22.73%  |
| HGST    | 8         | 8      | 6.06%   |
| Hitachi | 6         | 8      | 4.55%   |
| Fujitsu | 1         | 1      | 0.76%   |
| Apple   | 1         | 1      | 0.76%   |
| ACASIS  | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 34        | 41     | 32.69%  |
| WDC                 | 15        | 17     | 14.42%  |
| Crucial             | 12        | 17     | 11.54%  |
| Hewlett-Packard     | 6         | 6      | 5.77%   |
| SanDisk             | 5         | 7      | 4.81%   |
| Netac               | 5         | 5      | 4.81%   |
| Samsung Electronics | 4         | 4      | 3.85%   |
| TO Exter            | 3         | 7      | 2.88%   |
| LITEON              | 3         | 3      | 2.88%   |
| China               | 2         | 2      | 1.92%   |
| A-DATA Technology   | 2         | 2      | 1.92%   |
| Toshiba             | 1         | 1      | 0.96%   |
| SSSTC               | 1         | 1      | 0.96%   |
| SK hynix            | 1         | 4      | 0.96%   |
| Seagate             | 1         | 1      | 0.96%   |
| Reletech-P400       | 1         | 1      | 0.96%   |
| Lenovo              | 1         | 1      | 0.96%   |
| KingSpec            | 1         | 1      | 0.96%   |
| Intel               | 1         | 1      | 0.96%   |
| GLOWAY              | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| Dogfish             | 1         | 1      | 0.96%   |
| Apple               | 1         | 1      | 0.96%   |
| Unknown             | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 131       | 153    | 41.72%  |
| SSD     | 92        | 127    | 29.3%   |
| NVMe    | 78        | 106    | 24.84%  |
| MMC     | 11        | 11     | 3.5%    |
| Unknown | 2         | 2      | 0.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 193       | 272    | 67.01%  |
| NVMe | 78        | 106    | 27.08%  |
| MMC  | 11        | 11     | 3.82%   |
| SAS  | 6         | 10     | 2.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 156    | 53.24%  |
| 0.51-1.0   | 95        | 111    | 43.98%  |
| 1.01-2.0   | 6         | 13     | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 68        | 25.09%  |
| 251-500        | 65        | 23.99%  |
| 501-1000       | 56        | 20.66%  |
| 21-50          | 22        | 8.12%   |
| 51-100         | 19        | 7.01%   |
| 1-20           | 16        | 5.9%    |
| 1001-2000      | 15        | 5.54%   |
| More than 3000 | 4         | 1.48%   |
| 2001-3000      | 4         | 1.48%   |
| Unknown        | 2         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 109       | 38.93%  |
| 21-50          | 62        | 22.14%  |
| 101-250        | 35        | 12.5%   |
| 51-100         | 32        | 11.43%  |
| 251-500        | 21        | 7.5%    |
| 501-1000       | 13        | 4.64%   |
| 1001-2000      | 3         | 1.07%   |
| 2001-3000      | 2         | 0.71%   |
| Unknown        | 2         | 0.71%   |
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
| Seagate ST500LT012-1DG142 500GB      | 1         | 2      | 3.45%   |
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
| Seagate         | 6         | 7      | 21.43%  |
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
| Seagate | 6         | 7      | 28.57%  |
| Hitachi | 4         | 6      | 19.05%  |
| WDC     | 3         | 3      | 14.29%  |
| HGST    | 2         | 2      | 9.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 25     | 75%     |
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
| Detected | 155       | 227    | 54.2%   |
| Works    | 103       | 138    | 36.01%  |
| Malfunc  | 27        | 32     | 9.44%   |
| Failed   | 1         | 2      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 186       | 62%     |
| AMD                              | 37        | 12.33%  |
| SanDisk                          | 18        | 6%      |
| Samsung Electronics              | 15        | 5%      |
| Micron Technology                | 9         | 3%      |
| Kingston Technology Company      | 9         | 3%      |
| SK hynix                         | 7         | 2.33%   |
| KIOXIA                           | 6         | 2%      |
| Union Memory (Shenzhen)          | 2         | 0.67%   |
| Silicon Motion                   | 2         | 0.67%   |
| Phison Electronics               | 2         | 0.67%   |
| Micron/Crucial Technology        | 2         | 0.67%   |
| Toshiba America Info Systems     | 1         | 0.33%   |
| Solid State Storage Technology   | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| INNOGRIT                         | 1         | 0.33%   |
| Biwin Storage Technology         | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 10.44%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 31        | 9.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 23        | 7.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 6.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 2.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 2.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.9%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 1.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 1.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.58%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.58%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 1.27%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 1.27%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.27%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.27%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.95%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.95%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                         | 3         | 0.95%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.63%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 2         | 0.63%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 2         | 0.63%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.63%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.63%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.63%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.63%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 0.63%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.63%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 2         | 0.63%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 184       | 60.53%  |
| NVMe | 77        | 25.33%  |
| RAID | 33        | 10.86%  |
| IDE  | 10        | 3.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 202       | 77.1%   |
| AMD    | 60        | 22.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 2.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 2.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 2.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.29%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.91%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.91%   |
| Intel Celeron J4115 CPU @ 1.80GHz             | 5         | 1.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.91%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.53%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.15%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 1.15%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.15%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.15%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.15%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.15%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.15%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 3         | 1.15%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.15%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.15%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 3         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.76%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.76%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.76%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.76%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 65        | 24.81%  |
| Intel Core i7           | 64        | 24.43%  |
| Intel Core i3           | 31        | 11.83%  |
| AMD Ryzen 7             | 18        | 6.87%   |
| AMD Ryzen 5             | 18        | 6.87%   |
| Other                   | 16        | 6.11%   |
| Intel Celeron           | 13        | 4.96%   |
| Intel Atom              | 5         | 1.91%   |
| Intel Core 2 Duo        | 3         | 1.15%   |
| AMD Athlon              | 3         | 1.15%   |
| AMD A8                  | 3         | 1.15%   |
| AMD A4                  | 3         | 1.15%   |
| Intel Pentium           | 2         | 0.76%   |
| AMD Ryzen 9             | 2         | 0.76%   |
| AMD Ryzen 7 PRO         | 2         | 0.76%   |
| AMD Ryzen 3             | 2         | 0.76%   |
| AMD E1                  | 2         | 0.76%   |
| AMD E                   | 2         | 0.76%   |
| Intel Xeon              | 1         | 0.38%   |
| Intel Pentium Dual-Core | 1         | 0.38%   |
| Intel Pentium Dual      | 1         | 0.38%   |
| Intel Genuine           | 1         | 0.38%   |
| Intel Celeron M         | 1         | 0.38%   |
| AMD C-50                | 1         | 0.38%   |
| AMD A12                 | 1         | 0.38%   |
| AMD A10                 | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 126       | 48.09%  |
| 4       | 92        | 35.11%  |
| 8       | 20        | 7.63%   |
| 6       | 13        | 4.96%   |
| 1       | 7         | 2.67%   |
| 10      | 2         | 0.76%   |
| 16      | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 262       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 218       | 83.21%  |
| 1       | 43        | 16.41%  |
| Unknown | 1         | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 256       | 96.97%  |
| 64-bit         | 3         | 1.14%   |
| 32-bit         | 3         | 1.14%   |
| Unknown        | 2         | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 29.93%  |
| 0x206a7    | 16        | 5.84%   |
| 0x306a9    | 12        | 4.38%   |
| 0x40651    | 11        | 4.01%   |
| 0x806ec    | 10        | 3.65%   |
| 0x806ea    | 10        | 3.65%   |
| 0x406e3    | 10        | 3.65%   |
| 0x306d4    | 9         | 3.28%   |
| 0x806e9    | 8         | 2.92%   |
| 0x08108109 | 8         | 2.92%   |
| 0x306c3    | 6         | 2.19%   |
| 0x08108102 | 6         | 2.19%   |
| 0x906ea    | 5         | 1.82%   |
| 0x806c1    | 5         | 1.82%   |
| 0x706e5    | 5         | 1.82%   |
| 0x0a50000c | 5         | 1.82%   |
| 0x20655    | 4         | 1.46%   |
| 0x806eb    | 3         | 1.09%   |
| 0x30678    | 3         | 1.09%   |
| 0x20652    | 3         | 1.09%   |
| 0x10661    | 3         | 1.09%   |
| 0x08608103 | 3         | 1.09%   |
| 0x08600106 | 3         | 1.09%   |
| 0xa0652    | 2         | 0.73%   |
| 0x906e9    | 2         | 0.73%   |
| 0x806d1    | 2         | 0.73%   |
| 0x1067a    | 2         | 0.73%   |
| 0x0a404101 | 2         | 0.73%   |
| 0x08600104 | 2         | 0.73%   |
| 0x08600102 | 2         | 0.73%   |
| 0x06006704 | 2         | 0.73%   |
| 0x05000029 | 2         | 0.73%   |
| 0x906a4    | 1         | 0.36%   |
| 0x906a3    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x6fd      | 1         | 0.36%   |
| 0x6e8      | 1         | 0.36%   |
| 0x6d8      | 1         | 0.36%   |
| 0x506e3    | 1         | 0.36%   |
| 0x406c4    | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 56        | 21.37%  |
| Haswell          | 24        | 9.16%   |
| Zen+             | 18        | 6.87%   |
| SandyBridge      | 18        | 6.87%   |
| IvyBridge        | 18        | 6.87%   |
| Skylake          | 16        | 6.11%   |
| Broadwell        | 11        | 4.2%    |
| Unknown          | 11        | 4.2%    |
| Zen 2            | 9         | 3.44%   |
| Westmere         | 9         | 3.44%   |
| IceLake          | 9         | 3.44%   |
| Silvermont       | 8         | 3.05%   |
| TigerLake        | 7         | 2.67%   |
| Zen 3            | 6         | 2.29%   |
| Goldmont plus    | 5         | 1.91%   |
| Excavator        | 5         | 1.91%   |
| Zen              | 4         | 1.53%   |
| Penryn           | 4         | 1.53%   |
| Core             | 4         | 1.53%   |
| Piledriver       | 3         | 1.15%   |
| CometLake        | 3         | 1.15%   |
| Bobcat           | 3         | 1.15%   |
| Puma             | 2         | 0.76%   |
| P6               | 2         | 0.76%   |
| Jaguar           | 2         | 0.76%   |
| Bonnell          | 2         | 0.76%   |
| Alderlake Hybrid | 2         | 0.76%   |
| Nehalem          | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 188       | 55.13%  |
| AMD                              | 86        | 25.22%  |
| Nvidia                           | 66        | 19.35%  |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 18        | 5.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 5.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 4.82%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 4.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 3.4%    |
| Intel HD Graphics 620                                                                    | 11        | 3.12%   |
| Intel HD Graphics 5500                                                                   | 11        | 3.12%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 2.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.55%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 2.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.98%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.42%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.42%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.13%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.13%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 1.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.13%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.13%   |
| AMD Lucienne                                                                             | 4         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.85%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.57%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.57%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 118       | 45.04%  |
| Intel + Nvidia | 47        | 17.94%  |
| 1 x AMD        | 47        | 17.94%  |
| Intel + AMD    | 21        | 8.02%   |
| AMD + Nvidia   | 11        | 4.2%    |
| 1 x Nvidia     | 8         | 3.05%   |
| 2 x AMD        | 7         | 2.67%   |
| 2 x Intel      | 2         | 0.76%   |
| 1 x SiS        | 1         | 0.38%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 223       | 84.15%  |
| Proprietary | 37        | 13.96%  |
| Unknown     | 5         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 155       | 57.84%  |
| 1.01-2.0   | 44        | 16.42%  |
| 0.01-0.5   | 37        | 13.81%  |
| 3.01-4.0   | 14        | 5.22%   |
| 0.51-1.0   | 9         | 3.36%   |
| 5.01-6.0   | 5         | 1.87%   |
| 7.01-8.0   | 3         | 1.12%   |
| 8.01-16.0  | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Chimei Innolux      | 68        | 22.59%  |
| BOE                 | 52        | 17.28%  |
| Samsung Electronics | 44        | 14.62%  |
| AU Optronics        | 42        | 13.95%  |
| LG Display          | 35        | 11.63%  |
| Goldstar            | 10        | 3.32%   |
| PANDA               | 7         | 2.33%   |
| Hewlett-Packard     | 4         | 1.33%   |
| Sharp               | 3         | 1%      |
| Apple               | 3         | 1%      |
| AOC                 | 3         | 1%      |
| TMX                 | 2         | 0.66%   |
| Sony                | 2         | 0.66%   |
| Lenovo              | 2         | 0.66%   |
| JRY                 | 2         | 0.66%   |
| HannStar            | 2         | 0.66%   |
| Dell                | 2         | 0.66%   |
| Unknown             | 2         | 0.66%   |
| ViewSonic           | 1         | 0.33%   |
| Unknown (XXX)       | 1         | 0.33%   |
| Panasonic           | 1         | 0.33%   |
| MSI                 | 1         | 0.33%   |
| Mi                  | 1         | 0.33%   |
| LGD                 | 1         | 0.33%   |
| LG Philips          | 1         | 0.33%   |
| InnoLux Display     | 1         | 0.33%   |
| InfoVision          | 1         | 0.33%   |
| HUAWEI              | 1         | 0.33%   |
| Hitachi             | 1         | 0.33%   |
| EXP                 | 1         | 0.33%   |
| DZX                 | 1         | 0.33%   |
| CSO                 | 1         | 0.33%   |
| AGO                 | 1         | 0.33%   |
| Acer                | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 3.97%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 9         | 2.98%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 5         | 1.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 1.32%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.99%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 0.99%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 3         | 0.99%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 0.99%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 3         | 0.99%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.66%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.66%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.66%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.66%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch         | 2         | 0.66%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 2         | 0.66%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.66%   |
| JRY DX238A1 JRY2380 1920x1080 368x207mm 16.6-inch                    | 2         | 0.66%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2         | 0.66%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                 | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch      | 2         | 0.66%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.66%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.66%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.66%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.66%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.66%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 2         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 145       | 50.17%  |
| 1920x1080 (FHD)   | 90        | 31.14%  |
| 1600x900 (HD+)    | 8         | 2.77%   |
| 1280x800 (WXGA)   | 8         | 2.77%   |
| 3840x2160 (4K)    | 6         | 2.08%   |
| 2160x1440         | 5         | 1.73%   |
| 1360x768          | 4         | 1.38%   |
| 1920x1200 (WUXGA) | 3         | 1.04%   |
| 1440x900 (WXGA+)  | 3         | 1.04%   |
| 3200x1800 (QHD+)  | 2         | 0.69%   |
| 2560x1600         | 2         | 0.69%   |
| 2560x1440 (QHD)   | 2         | 0.69%   |
| 1024x600          | 2         | 0.69%   |
| Unknown           | 2         | 0.69%   |
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
| 15      | 140       | 46.98%  |
| 13      | 49        | 16.44%  |
| 14      | 40        | 13.42%  |
| 23      | 12        | 4.03%   |
| 17      | 8         | 2.68%   |
| 21      | 7         | 2.35%   |
| 18      | 6         | 2.01%   |
| 11      | 5         | 1.68%   |
| 24      | 4         | 1.34%   |
| 16      | 4         | 1.34%   |
| 12      | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 72      | 2         | 0.67%   |
| 31      | 2         | 0.67%   |
| 27      | 2         | 0.67%   |
| 20      | 2         | 0.67%   |
| 10      | 2         | 0.67%   |
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
| 301-350     | 217       | 73.31%  |
| 201-300     | 22        | 7.43%   |
| 501-600     | 18        | 6.08%   |
| 401-500     | 16        | 5.41%   |
| 351-400     | 10        | 3.38%   |
| 1001-1500   | 4         | 1.35%   |
| 1501-2000   | 3         | 1.01%   |
| Unknown     | 3         | 1.01%   |
| 601-700     | 2         | 0.68%   |
| 801-900     | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 230       | 87.45%  |
| 16/10   | 21        | 7.98%   |
| 3/2     | 6         | 2.28%   |
| 4/3     | 3         | 1.14%   |
| Unknown | 3         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 140       | 46.98%  |
| 81-90          | 78        | 26.17%  |
| 201-250        | 21        | 7.05%   |
| 71-80          | 10        | 3.36%   |
| More than 1000 | 6         | 2.01%   |
| 151-200        | 6         | 2.01%   |
| 121-130        | 6         | 2.01%   |
| 51-60          | 5         | 1.68%   |
| 141-150        | 5         | 1.68%   |
| 111-120        | 4         | 1.34%   |
| Unknown        | 3         | 1.01%   |
| 61-70          | 2         | 0.67%   |
| 351-500        | 2         | 0.67%   |
| 41-50          | 2         | 0.67%   |
| 301-350        | 2         | 0.67%   |
| 131-140        | 2         | 0.67%   |
| 501-1000       | 2         | 0.67%   |
| 91-100         | 2         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 144       | 49.15%  |
| 121-160       | 83        | 28.33%  |
| 51-100        | 39        | 13.31%  |
| 161-240       | 13        | 4.44%   |
| 1-50          | 7         | 2.39%   |
| More than 240 | 4         | 1.37%   |
| Unknown       | 3         | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 214       | 79.85%  |
| 2     | 45        | 16.79%  |
| 0     | 7         | 2.61%   |
| 3     | 2         | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 164       | 40.59%  |
| Intel                            | 96        | 23.76%  |
| Qualcomm Atheros                 | 75        | 18.56%  |
| Broadcom                         | 18        | 4.46%   |
| TP-Link                          | 8         | 1.98%   |
| MediaTek                         | 8         | 1.98%   |
| Ralink                           | 7         | 1.73%   |
| Xiaomi                           | 5         | 1.24%   |
| Marvell Technology Group         | 4         | 0.99%   |
| ASIX Electronics                 | 3         | 0.74%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 104       | 20.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 32        | 6.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 5.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 3.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.41%   |
| Intel Wireless 8260                                                     | 7         | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.41%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.21%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.21%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 5         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.01%   |
| Intel Wireless 7265                                                     | 5         | 1.01%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.01%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.8%    |
| Intel Wireless 7260                                                     | 4         | 0.8%    |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.6%    |
| Intel WiFi Link 5100                                                    | 3         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.6%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.6%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 92        | 34.2%   |
| Realtek Semiconductor | 68        | 25.28%  |
| Qualcomm Atheros      | 68        | 25.28%  |
| Broadcom              | 16        | 5.95%   |
| MediaTek              | 8         | 2.97%   |
| TP-Link               | 7         | 2.6%    |
| Ralink                | 7         | 2.6%    |
| Ralink Technology     | 2         | 0.74%   |
| Broadcom Limited      | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 9.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 7.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 6.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 3.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 2.97%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.6%    |
| Intel Wireless 8260                                                     | 7         | 2.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.6%    |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 2.6%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 2.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 2.23%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.86%   |
| Intel Wireless 7265                                                     | 5         | 1.86%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.86%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 1.49%   |
| Intel Wireless 7260                                                     | 4         | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.12%   |
| Intel WiFi Link 5100                                                    | 3         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.12%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.12%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.74%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 146       | 64.6%   |
| Intel                            | 33        | 14.6%   |
| Qualcomm Atheros                 | 17        | 7.52%   |
| Xiaomi                           | 5         | 2.21%   |
| Marvell Technology Group         | 4         | 1.77%   |
| Broadcom                         | 4         | 1.77%   |
| ASIX Electronics                 | 3         | 1.33%   |
| Samsung Electronics              | 2         | 0.88%   |
| Motorola PCS                     | 2         | 0.88%   |
| ICS Advent                       | 2         | 0.88%   |
| TP-Link                          | 1         | 0.44%   |
| T & A Mobile Phones              | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| OPPO Electronics                 | 1         | 0.44%   |
| Microsoft                        | 1         | 0.44%   |
| Lenovo                           | 1         | 0.44%   |
| DisplayLink                      | 1         | 0.44%   |
| Apple                            | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 104       | 45.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 32        | 14.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 2.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.75%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.88%   |
| Motorola PCS motorola one macro                                                | 2         | 0.88%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.88%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.88%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.88%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.88%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.88%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.44%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.44%   |
| OPPO RMX2027                                                                   | 1         | 0.44%   |
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
| WiFi     | 259       | 54.41%  |
| Ethernet | 217       | 45.59%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 209       | 74.38%  |
| Ethernet | 72        | 25.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 198       | 75.57%  |
| 1     | 61        | 23.28%  |
| 0     | 3         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 206       | 76.58%  |
| Yes  | 63        | 23.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 32.88%  |
| Realtek Semiconductor           | 47        | 21.17%  |
| Qualcomm Atheros Communications | 36        | 16.22%  |
| IMC Networks                    | 17        | 7.66%   |
| Lite-On Technology              | 12        | 5.41%   |
| Toshiba                         | 8         | 3.6%    |
| Ralink                          | 6         | 2.7%    |
| Foxconn / Hon Hai               | 5         | 2.25%   |
| Broadcom                        | 5         | 2.25%   |
| Hewlett-Packard                 | 3         | 1.35%   |
| Apple                           | 3         | 1.35%   |
| Dell                            | 2         | 0.9%    |
| Cambridge Silicon Radio         | 2         | 0.9%    |
| Realtek                         | 1         | 0.45%   |
| Foxconn International           | 1         | 0.45%   |
| Alps Electric                   | 1         | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 11.26%  |
| Realtek Bluetooth Radio                             | 23        | 10.36%  |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 9.91%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 9.46%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 8.56%   |
| Intel AX201 Bluetooth                               | 10        | 4.5%    |
| Ralink RT3290 Bluetooth                             | 6         | 2.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.7%    |
| Intel Bluetooth Device                              | 6         | 2.7%    |
| Intel AX200 Bluetooth                               | 6         | 2.7%    |
| IMC Networks Wireless_Device                        | 6         | 2.7%    |
| IMC Networks Bluetooth Radio                        | 6         | 2.7%    |
| Toshiba Bluetooth Device                            | 5         | 2.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.8%    |
| IMC Networks Bluetooth Device                       | 4         | 1.8%    |
| Lite-On Bluetooth Radio                             | 3         | 1.35%   |
| Lite-On Bluetooth Device                            | 3         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.35%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.9%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.9%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.9%    |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.9%    |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.9%    |
| Apple Bluetooth USB Host Controller                 | 2         | 0.9%    |
| Toshiba RT Bluetooth Radio                          | 1         | 0.45%   |
| Toshiba BCM43142A0                                  | 1         | 0.45%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.45%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.45%   |
| Realtek Bluetooth Radio                             | 1         | 0.45%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.45%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.45%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.45%   |
| Intel AX210 Bluetooth                               | 1         | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 197       | 63.34%  |
| AMD                              | 66        | 21.22%  |
| Nvidia                           | 34        | 10.93%  |
| Generalplus Technology           | 3         | 0.96%   |
| C-Media Electronics              | 3         | 0.96%   |
| Kingston Technology              | 2         | 0.64%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Razer USA                        | 1         | 0.32%   |
| Pixart Imaging                   | 1         | 0.32%   |
| Logitech                         | 1         | 0.32%   |
| Hewlett-Packard                  | 1         | 0.32%   |
| GN Netcom                        | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 45        | 11.28%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 10.53%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 5.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 5.26%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 4.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 4.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 4.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.76%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 2.26%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.75%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.5%    |
| Nvidia Audio device                                                                               | 5         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1%      |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1%      |
| AMD High Definition Audio Controller                                                              | 4         | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.75%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 60        | 30%     |
| SK hynix            | 40        | 20%     |
| Micron Technology   | 28        | 14%     |
| Kingston            | 24        | 12%     |
| Ramaxel Technology  | 11        | 5.5%    |
| Unknown             | 10        | 5%      |
| Unknown (ABCD)      | 5         | 2.5%    |
| Team                | 5         | 2.5%    |
| Crucial             | 4         | 2%      |
| Hewlett-Packard     | 3         | 1.5%    |
| Elpida              | 3         | 1.5%    |
| Patriot             | 2         | 1%      |
| Kllisre             | 1         | 0.5%    |
| Goldkey             | 1         | 0.5%    |
| CSX                 | 1         | 0.5%    |
| Corsair             | 1         | 0.5%    |
| A-DATA Technology   | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 2.36%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 2.36%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 4         | 1.89%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.89%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.89%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 1.89%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.42%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.42%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.42%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.42%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 1.42%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s          | 3         | 1.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.94%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.94%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.94%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.94%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.47%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.47%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 70        | 46.05%  |
| DDR3    | 57        | 37.5%   |
| LPDDR4  | 11        | 7.24%   |
| DDR2    | 4         | 2.63%   |
| LPDDR3  | 3         | 1.97%   |
| DDR5    | 3         | 1.97%   |
| SDRAM   | 2         | 1.32%   |
| LPDDR5  | 1         | 0.66%   |
| Unknown | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 144       | 94.74%  |
| Row Of Chips | 7         | 4.61%   |
| Unknown      | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 76        | 42.22%  |
| 4096  | 64        | 35.56%  |
| 16384 | 17        | 9.44%   |
| 2048  | 14        | 7.78%   |
| 32768 | 4         | 2.22%   |
| 1024  | 4         | 2.22%   |
| 512   | 1         | 0.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 45        | 25.86%  |
| 2667    | 43        | 24.71%  |
| 3200    | 34        | 19.54%  |
| 2400    | 13        | 7.47%   |
| 3266    | 6         | 3.45%   |
| 1334    | 6         | 3.45%   |
| 1333    | 5         | 2.87%   |
| 2133    | 4         | 2.3%    |
| 4800    | 3         | 1.72%   |
| Unknown | 3         | 1.72%   |
| 1867    | 2         | 1.15%   |
| 1067    | 2         | 1.15%   |
| 5500    | 1         | 0.57%   |
| 4267    | 1         | 0.57%   |
| 4199    | 1         | 0.57%   |
| 2933    | 1         | 0.57%   |
| 1066    | 1         | 0.57%   |
| 800     | 1         | 0.57%   |
| 667     | 1         | 0.57%   |
| 533     | 1         | 0.57%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon                         | 2         | 28.57%  |
| Seiko Epson                   | 1         | 14.29%  |
| Samsung Info. Systems America | 1         | 14.29%  |
| Prolific Technology           | 1         | 14.29%  |
| Hewlett-Packard               | 1         | 14.29%  |
| Brother Industries            | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                    | 1         | 14.29%  |
| Samsung Info. Systems America SAMSUNG SRP-270 | 1         | 14.29%  |
| Prolific PL2305 Parallel Port                 | 1         | 14.29%  |
| HP LaserJet Professional P 1102w              | 1         | 14.29%  |
| Canon G2010 series                            | 1         | 14.29%  |
| Canon E400 series                             | 1         | 14.29%  |
| Brother DCP-T300                              | 1         | 14.29%  |

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
| Chicony Electronics                    | 56        | 22.58%  |
| IMC Networks                           | 28        | 11.29%  |
| Microdia                               | 20        | 8.06%   |
| Realtek Semiconductor                  | 19        | 7.66%   |
| Bison Electronics                      | 18        | 7.26%   |
| Syntek                                 | 16        | 6.45%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.65%   |
| Quanta                                 | 13        | 5.24%   |
| Sunplus Innovation Technology          | 12        | 4.84%   |
| Suyin                                  | 11        | 4.44%   |
| Lite-On Technology                     | 11        | 4.44%   |
| Acer                                   | 5         | 2.02%   |
| Sonix Technology                       | 4         | 1.61%   |
| Luxvisions Innotech Limited            | 4         | 1.61%   |
| Importek                               | 4         | 1.61%   |
| Samsung Electronics                    | 2         | 0.81%   |
| Ricoh                                  | 2         | 0.81%   |
| Apple                                  | 2         | 0.81%   |
| Alcor Micro                            | 2         | 0.81%   |
| Logitech                               | 1         | 0.4%    |
| Jieli Technology                       | 1         | 0.4%    |
| ASUSTek Computer                       | 1         | 0.4%    |
| ANYKA                                  | 1         | 0.4%    |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 12        | 4.82%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 3.21%   |
| Chicony Integrated Camera                                                  | 6         | 2.41%   |
| Chicony HP Truevision HD                                                   | 6         | 2.41%   |
| Chicony EasyCamera                                                         | 6         | 2.41%   |
| Microdia Webcam Vitade AF                                                  | 5         | 2.01%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 2.01%   |
| Lite-On Integrated Camera                                                  | 5         | 2.01%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 2.01%   |
| IMC Networks Integrated Camera                                             | 5         | 2.01%   |
| Bison Integrated Camera                                                    | 5         | 2.01%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.61%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.61%   |
| Realtek Integrated_Webcam_HD                                               | 4         | 1.61%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 1.61%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.61%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.61%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.61%   |
| Acer Integrated Camera                                                     | 4         | 1.61%   |
| Lite-On HP HD Camera                                                       | 3         | 1.2%    |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.2%    |
| Chicony HP HD Webcam                                                       | 3         | 1.2%    |
| Chicony HD WebCam                                                          | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.2%    |
| Bison EasyCamera                                                           | 3         | 1.2%    |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.8%    |
| Sunplus Integrated Webcam                                                  | 2         | 0.8%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.8%    |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.8%    |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.8%    |
| Realtek Integrated Webcam                                                  | 2         | 0.8%    |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.8%    |
| Quanta HP Webcam                                                           | 2         | 0.8%    |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.8%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 0.8%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.8%    |
| IMC Networks HD Camera                                                     | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 50%     |
| Synaptics                  | 13        | 27.08%  |
| Shenzhen Goodix Technology | 5         | 10.42%  |
| Elan Microelectronics      | 4         | 8.33%   |
| STMicroelectronics         | 1         | 2.08%   |
| AuthenTec                  | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 8         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 7         | 14.58%  |
| Synaptics  WBDI                                           | 4         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                       | 3         | 6.25%   |
| Elan ELAN:Fingerprint                                     | 3         | 6.25%   |
| Validity Sensors Synaptics WBDI                           | 2         | 4.17%   |
| Validity Sensors Fingerprint scanner                      | 2         | 4.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 4.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 4.17%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 2.08%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 2.08%   |
| Synaptics WBDI                                            | 1         | 2.08%   |
| Synaptics UWP WBDI Device                                 | 1         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 2.08%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 2.08%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 2.08%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.08%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 1         | 2.08%   |

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
| 0     | 168       | 62.92%  |
| 1     | 80        | 29.96%  |
| 2     | 17        | 6.37%   |
| 3     | 2         | 0.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 41.38%  |
| Graphics card            | 21        | 18.1%   |
| Net/wireless             | 14        | 12.07%  |
| Chipcard                 | 11        | 9.48%   |
| Bluetooth                | 8         | 6.9%    |
| Multimedia controller    | 5         | 4.31%   |
| Storage                  | 2         | 1.72%   |
| Communication controller | 2         | 1.72%   |
| Card reader              | 2         | 1.72%   |
| Camera                   | 2         | 1.72%   |
| Net/ethernet             | 1         | 0.86%   |

