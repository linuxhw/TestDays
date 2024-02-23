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

Total: 404

| Vendor     | Model                       | Probe                                                      | Date         |
|------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek    | VivoBook_ASUSLaptop X160... | [6f80a7214c](https://linux-hardware.org/?probe=6f80a7214c) | Feb 01, 2024 |
| ASUSTek    | G75VX                       | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| Samsung    | 905S3G/906S3G/915S3G/930... | [8c1fb214b8](https://linux-hardware.org/?probe=8c1fb214b8) | Jan 25, 2024 |
| Samsung    | 905S3G/906S3G/915S3G/930... | [f3512d75e9](https://linux-hardware.org/?probe=f3512d75e9) | Jan 24, 2024 |
| Dell       | Latitude 7430               | [153f1a144c](https://linux-hardware.org/?probe=153f1a144c) | Jan 19, 2024 |
| Dell       | Latitude 7430               | [a05210eeb4](https://linux-hardware.org/?probe=a05210eeb4) | Jan 19, 2024 |
| System76   | Adder WS                    | [94120ee028](https://linux-hardware.org/?probe=94120ee028) | Jan 11, 2024 |
| ASUSTek    | UX510UXK                    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Toshiba    | Satellite P55-B             | [9a1e5dc1f6](https://linux-hardware.org/?probe=9a1e5dc1f6) | Dec 31, 2023 |
| ASUSTek    | VivoBook_ASUSLaptop X160... | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| Lenovo     | IdeaPad S340-15IML 81NA     | [1594f8077b](https://linux-hardware.org/?probe=1594f8077b) | Dec 27, 2023 |
| Sony       | SVS13A25PLB                 | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP         | Pavilion Gaming Laptop 1... | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| Dell       | Latitude E5470              | [9aa1f53217](https://linux-hardware.org/?probe=9aa1f53217) | Dec 18, 2023 |
| Toshiba    | Satellite A300              | [5e373b58ac](https://linux-hardware.org/?probe=5e373b58ac) | Dec 15, 2023 |
| ASRock     | B560M Pro4/ac               | [0dd2927c25](https://linux-hardware.org/?probe=0dd2927c25) | Dec 14, 2023 |
| Apple      | MacBookPro5,4               | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| Gigabyte   | B550M K                     | [989886ee56](https://linux-hardware.org/?probe=989886ee56) | Nov 19, 2023 |
| Lenovo     | ThinkPad T16 Gen 1 21BWS... | [f4de613bd5](https://linux-hardware.org/?probe=f4de613bd5) | Nov 15, 2023 |
| Dell       | Latitude 5490               | [ac938f1435](https://linux-hardware.org/?probe=ac938f1435) | Nov 08, 2023 |
| Dell       | Latitude E5470              | [bbbdcac07b](https://linux-hardware.org/?probe=bbbdcac07b) | Nov 07, 2023 |
| Dell       | Latitude E5470              | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
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
| Ubuntu 20.04                 | 32        | 10.74%  |
| Ubuntu 22.04                 | 14        | 4.7%    |
| Arch Rolling                 | 14        | 4.7%    |
| OpenMandriva 4.3             | 11        | 3.69%   |
| Ubuntu 18.04                 | 9         | 3.02%   |
| Linux Mint 21.1              | 9         | 3.02%   |
| Fedora 38                    | 8         | 2.68%   |
| OpenMandriva 23.03           | 7         | 2.35%   |
| Zorin 15                     | 6         | 2.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 2.01%   |
| Manjaro                      | 6         | 2.01%   |
| Linux Mint 20.3              | 6         | 2.01%   |
| Ubuntu 19.10                 | 5         | 1.68%   |
| Fedora 37                    | 5         | 1.68%   |
| Arch                         | 5         | 1.68%   |
| Xubuntu 20.04                | 4         | 1.34%   |
| Ubuntu 21.04                 | 4         | 1.34%   |
| Pop!_OS 22.04                | 4         | 1.34%   |
| Pop!_OS 21.10                | 4         | 1.34%   |
| OpenMandriva 23.01           | 4         | 1.34%   |
| Debian 11                    | 4         | 1.34%   |
| ArcoLinux Rolling            | 4         | 1.34%   |
| Zorin 16                     | 3         | 1.01%   |
| Ubuntu 19.04                 | 3         | 1.01%   |
| Pop!_OS 20.10                | 3         | 1.01%   |
| OpenMandriva 4.2             | 3         | 1.01%   |
| OpenMandriva 23.08           | 3         | 1.01%   |
| Manjaro 20.1                 | 3         | 1.01%   |
| KDE neon 20.04               | 3         | 1.01%   |
| Fedora 39                    | 3         | 1.01%   |
| Fedora 35                    | 3         | 1.01%   |
| EndeavourOS Rolling          | 3         | 1.01%   |
| Elementary 5.1.7             | 3         | 1.01%   |
| Debian 10                    | 3         | 1.01%   |
| Ubuntu Budgie 22.04          | 2         | 0.67%   |
| ROSA R9                      | 2         | 0.67%   |
| ROSA R10                     | 2         | 0.67%   |
| ROSA 12.3                    | 2         | 0.67%   |
| ROSA 12.2                    | 2         | 0.67%   |
| Pop!_OS 20.04                | 2         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 68        | 23.53%  |
| OpenMandriva  | 31        | 10.73%  |
| Fedora        | 25        | 8.65%   |
| Linux Mint    | 22        | 7.61%   |
| Arch          | 20        | 6.92%   |
| Pop!_OS       | 14        | 4.84%   |
| Manjaro       | 14        | 4.84%   |
| ROSA          | 10        | 3.46%   |
| Debian        | 10        | 3.46%   |
| Zorin         | 9         | 3.11%   |
| openSUSE      | 7         | 2.42%   |
| Kubuntu       | 5         | 1.73%   |
| KDE neon      | 5         | 1.73%   |
| Xubuntu       | 4         | 1.38%   |
| Elementary    | 4         | 1.38%   |
| ArcoLinux     | 4         | 1.38%   |
| Ubuntu MATE   | 3         | 1.04%   |
| Lubuntu       | 3         | 1.04%   |
| Kali          | 3         | 1.04%   |
| Endless       | 3         | 1.04%   |
| EndeavourOS   | 3         | 1.04%   |
| Ubuntu Budgie | 2         | 0.69%   |
| SteamOS       | 2         | 0.69%   |
| Parrot        | 2         | 0.69%   |
| LMDE          | 2         | 0.69%   |
| CentOS        | 2         | 0.69%   |
| Void Linux    | 1         | 0.35%   |
| Ubuntu Unity  | 1         | 0.35%   |
| Ubuntu Studio | 1         | 0.35%   |
| Peppermint    | 1         | 0.35%   |
| Oracle Linux  | 1         | 0.35%   |
| NixOS         | 1         | 0.35%   |
| MX            | 1         | 0.35%   |
| Laxer OS      | 1         | 0.35%   |
| Garuda Linux  | 1         | 0.35%   |
| Clear Linux   | 1         | 0.35%   |
| ChimeraOS     | 1         | 0.35%   |
| Artix         | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 11        | 3.38%   |
| 6.2.6-desktop-1omv2390   | 6         | 1.85%   |
| 5.13.0-40-generic        | 5         | 1.54%   |
| 5.4.0-42-generic         | 4         | 1.23%   |
| 6.3.5-desktop-3omv2390   | 3         | 0.92%   |
| 6.3.5-200.fc38.x86_64    | 3         | 0.92%   |
| 5.4.0-26-generic         | 3         | 0.92%   |
| 5.3.0-40-generic         | 3         | 0.92%   |
| 5.15.0-76-generic        | 3         | 0.92%   |
| 5.15.0-71-generic        | 3         | 0.92%   |
| 5.13.0-51-generic        | 3         | 0.92%   |
| 5.11.0-25-generic        | 3         | 0.92%   |
| 5.10.0-13-amd64          | 3         | 0.92%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.62%   |
| 6.3.6-arch1-1            | 2         | 0.62%   |
| 6.2.0-36-generic         | 2         | 0.62%   |
| 6.2.0-24-generic         | 2         | 0.62%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.62%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.62%   |
| 5.8.0-44-generic         | 2         | 0.62%   |
| 5.4.0-7642-generic       | 2         | 0.62%   |
| 5.4.0-66-generic         | 2         | 0.62%   |
| 5.4.0-65-generic         | 2         | 0.62%   |
| 5.4.0-58-generic         | 2         | 0.62%   |
| 5.4.0-54-generic         | 2         | 0.62%   |
| 5.4.0-39-generic         | 2         | 0.62%   |
| 5.4.0-33-generic         | 2         | 0.62%   |
| 5.4.0-28-generic         | 2         | 0.62%   |
| 5.4.0-109-generic        | 2         | 0.62%   |
| 5.3.0-42-generic         | 2         | 0.62%   |
| 5.3.0-23-generic         | 2         | 0.62%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.62%   |
| 5.17.5-arch1-1           | 2         | 0.62%   |
| 5.16.19-76051619-generic | 2         | 0.62%   |
| 5.15.49-1-lts            | 2         | 0.62%   |
| 5.15.0-91-generic        | 2         | 0.62%   |
| 5.15.0-58-generic        | 2         | 0.62%   |
| 5.15.0-57-generic        | 2         | 0.62%   |
| 5.15.0-52-generic        | 2         | 0.62%   |
| 5.15.0-25-generic        | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 12.06%  |
| 5.15.0  | 27        | 8.57%   |
| 5.13.0  | 14        | 4.44%   |
| 5.11.0  | 14        | 4.44%   |
| 5.3.0   | 12        | 3.81%   |
| 6.2.0   | 11        | 3.49%   |
| 5.16.7  | 11        | 3.49%   |
| 6.2.6   | 7         | 2.22%   |
| 5.8.0   | 7         | 2.22%   |
| 5.10.0  | 7         | 2.22%   |
| 5.0.0   | 7         | 2.22%   |
| 4.15.0  | 7         | 2.22%   |
| 6.3.5   | 6         | 1.9%    |
| 4.18.0  | 6         | 1.9%    |
| 5.19.0  | 5         | 1.59%   |
| 6.5.0   | 4         | 1.27%   |
| 6.3.6   | 4         | 1.27%   |
| 6.6.6   | 3         | 0.95%   |
| 6.4.11  | 3         | 0.95%   |
| 6.0.0   | 3         | 0.95%   |
| 5.17.5  | 3         | 0.95%   |
| 4.9.60  | 3         | 0.95%   |
| 6.1.9   | 2         | 0.63%   |
| 6.1.4   | 2         | 0.63%   |
| 6.1.31  | 2         | 0.63%   |
| 6.1.11  | 2         | 0.63%   |
| 6.1.1   | 2         | 0.63%   |
| 6.0.7   | 2         | 0.63%   |
| 6.0.15  | 2         | 0.63%   |
| 5.18.12 | 2         | 0.63%   |
| 5.16.19 | 2         | 0.63%   |
| 5.15.49 | 2         | 0.63%   |
| 5.12.10 | 2         | 0.63%   |
| 5.10.74 | 2         | 0.63%   |
| 5.10.14 | 2         | 0.63%   |
| 4.9.20  | 2         | 0.63%   |
| 4.19.0  | 2         | 0.63%   |
| 6.6.8   | 1         | 0.32%   |
| 6.6.4   | 1         | 0.32%   |
| 6.6.10  | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 13.31%  |
| 5.15    | 39        | 12.66%  |
| 6.2     | 24        | 7.79%   |
| 5.13    | 15        | 4.87%   |
| 5.11    | 15        | 4.87%   |
| 5.10    | 15        | 4.87%   |
| 5.16    | 14        | 4.55%   |
| 6.1     | 13        | 4.22%   |
| 6.3     | 12        | 3.9%    |
| 6.0     | 12        | 3.9%    |
| 5.3     | 12        | 3.9%    |
| 6.5     | 10        | 3.25%   |
| 6.4     | 10        | 3.25%   |
| 5.8     | 10        | 3.25%   |
| 5.19    | 7         | 2.27%   |
| 5.17    | 7         | 2.27%   |
| 5.0     | 7         | 2.27%   |
| 4.15    | 7         | 2.27%   |
| 6.6     | 6         | 1.95%   |
| 4.18    | 6         | 1.95%   |
| 5.18    | 4         | 1.3%    |
| 5.14    | 4         | 1.3%    |
| 5.12    | 4         | 1.3%    |
| 4.9     | 4         | 1.3%    |
| 5.9     | 2         | 0.65%   |
| 5.7     | 2         | 0.65%   |
| 5.6     | 2         | 0.65%   |
| 4.19    | 2         | 0.65%   |
| 5.1     | 1         | 0.32%   |
| 4.16    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 271       | 97.13%  |
| i686   | 8         | 2.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 124       | 43.06%  |
| KDE5            | 62        | 21.53%  |
| XFCE            | 24        | 8.33%   |
| X-Cinnamon      | 19        | 6.6%    |
| Unknown         | 16        | 5.56%   |
| MATE            | 8         | 2.78%   |
| KDE             | 7         | 2.43%   |
| Pantheon        | 4         | 1.39%   |
| LXQt            | 4         | 1.39%   |
| KDE4            | 4         | 1.39%   |
| i3              | 4         | 1.39%   |
| Budgie          | 3         | 1.04%   |
| sway            | 2         | 0.69%   |
| LXDE            | 2         | 0.69%   |
| Unity           | 1         | 0.35%   |
| spectrwm        | 1         | 0.35%   |
| Hyprland        | 1         | 0.35%   |
| GNOME Flashback | 1         | 0.35%   |
| Deepin          | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 205       | 70.69%  |
| Wayland | 67        | 23.1%   |
| Unknown | 15        | 5.17%   |
| Tty     | 3         | 1.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 128       | 44.44%  |
| SDDM    | 52        | 18.06%  |
| GDM     | 43        | 14.93%  |
| LightDM | 34        | 11.81%  |
| GDM3    | 22        | 7.64%   |
| KDM     | 4         | 1.39%   |
| TDM     | 2         | 0.69%   |
| XDM     | 1         | 0.35%   |
| Ly      | 1         | 0.35%   |
| LXDM    | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_PE   | 132       | 46.32%  |
| en_US   | 83        | 29.12%  |
| es_ES   | 25        | 8.77%   |
| Unknown | 16        | 5.61%   |
| es_MX   | 8         | 2.81%   |
| C       | 4         | 1.4%    |
| it_IT   | 2         | 0.7%    |
| fr_FR   | 2         | 0.7%    |
| en_GB   | 2         | 0.7%    |
| ca_ES   | 2         | 0.7%    |
| POSIX   | 1         | 0.35%   |
| es_VE   | 1         | 0.35%   |
| es_CO   | 1         | 0.35%   |
| es_AR   | 1         | 0.35%   |
| en_NZ   | 1         | 0.35%   |
| en_DK   | 1         | 0.35%   |
| en_CA   | 1         | 0.35%   |
| de_DE   | 1         | 0.35%   |
| Default | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 162       | 57.04%  |
| BIOS | 122       | 42.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 205       | 71.43%  |
| Btrfs   | 35        | 12.2%   |
| Overlay | 23        | 8.01%   |
| Xfs     | 8         | 2.79%   |
| Tmpfs   | 8         | 2.79%   |
| Unknown | 7         | 2.44%   |
| Ext3    | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 137       | 48.24%  |
| GPT     | 118       | 41.55%  |
| MBR     | 29        | 10.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 246       | 86.93%  |
| Yes       | 37        | 13.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 59.15%  |
| Yes       | 116       | 40.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 75        | 26.98%  |
| Lenovo              | 68        | 24.46%  |
| ASUSTek Computer    | 38        | 13.67%  |
| Dell                | 27        | 9.71%   |
| Toshiba             | 19        | 6.83%   |
| Acer                | 16        | 5.76%   |
| Sony                | 6         | 2.16%   |
| Chuwi               | 5         | 1.8%    |
| MSI                 | 4         | 1.44%   |
| Apple               | 4         | 1.44%   |
| HUAWEI              | 3         | 1.08%   |
| Samsung Electronics | 2         | 0.72%   |
| Advance             | 2         | 0.72%   |
| System76            | 1         | 0.36%   |
| Razer               | 1         | 0.36%   |
| Google              | 1         | 0.36%   |
| Gigabyte Technology | 1         | 0.36%   |
| eMachines           | 1         | 0.36%   |
| efirstview          | 1         | 0.36%   |
| Compal              | 1         | 0.36%   |
| ASRock              | 1         | 0.36%   |
| Unknown             | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chuwi GemiBook Pro                       | 5         | 1.8%    |
| Lenovo V330-15IKB 81AX                   | 4         | 1.44%   |
| HP Pavilion Laptop 15-cw1xxx             | 4         | 1.44%   |
| HP 14                                    | 4         | 1.44%   |
| Toshiba Satellite L45-B                  | 3         | 1.08%   |
| Lenovo V310-15ISK 80SY                   | 3         | 1.08%   |
| Lenovo IdeaPad 3 14ADA05 81W0            | 3         | 1.08%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA   | 3         | 1.08%   |
| Toshiba Satellite C45-A                  | 2         | 0.72%   |
| Lenovo IdeaPad S540-14API 81NH           | 2         | 0.72%   |
| Lenovo IdeaPad S145-15IWL 81MV           | 2         | 0.72%   |
| Lenovo IdeaPad 330S-14IKB 81F4           | 2         | 0.72%   |
| Lenovo G400 20235                        | 2         | 0.72%   |
| HP ProBook 645 G4                        | 2         | 0.72%   |
| HP Pavilion Gaming Laptop 15-dk1xxx      | 2         | 0.72%   |
| HP Pavilion g4                           | 2         | 0.72%   |
| HP Pavilion dv4                          | 2         | 0.72%   |
| HP Notebook                              | 2         | 0.72%   |
| HP Laptop 15-ef1xxx                      | 2         | 0.72%   |
| HP Compaq Presario C700                  | 2         | 0.72%   |
| HP 450                                   | 2         | 0.72%   |
| HP 250 G7 Notebook PC                    | 2         | 0.72%   |
| HP 250 G5 Notebook PC                    | 2         | 0.72%   |
| Dell XPS 13 9360                         | 2         | 0.72%   |
| Dell Latitude E7450                      | 2         | 0.72%   |
| Dell Latitude E5470                      | 2         | 0.72%   |
| Dell Latitude 5490                       | 2         | 0.72%   |
| Dell G5 5505                             | 2         | 0.72%   |
| ASUS X550LD                              | 2         | 0.72%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 2         | 0.72%   |
| ASUS VivoBook 15_ASUS Laptop X507UBR     | 2         | 0.72%   |
| ASUS ROG Strix G513RC_G513RC             | 2         | 0.72%   |
| ASUS ASUS TUF Gaming A15 FA506IV_FX506IV | 2         | 0.72%   |
| Apple MacBookPro9,2                      | 2         | 0.72%   |
| Toshiba Satellite P755                   | 1         | 0.36%   |
| Toshiba Satellite P55-B                  | 1         | 0.36%   |
| Toshiba Satellite P300                   | 1         | 0.36%   |
| Toshiba Satellite L855                   | 1         | 0.36%   |
| Toshiba Satellite L35                    | 1         | 0.36%   |
| Toshiba Satellite E205                   | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 25        | 8.99%   |
| HP Pavilion       | 20        | 7.19%   |
| Lenovo ThinkPad   | 18        | 6.47%   |
| Toshiba Satellite | 17        | 6.12%   |
| ASUS VivoBook     | 14        | 5.04%   |
| Dell Latitude     | 13        | 4.68%   |
| Acer Aspire       | 13        | 4.68%   |
| HP Laptop         | 11        | 3.96%   |
| HP ProBook        | 10        | 3.6%    |
| Dell Inspiron     | 7         | 2.52%   |
| Lenovo Legion     | 5         | 1.8%    |
| Chuwi GemiBook    | 5         | 1.8%    |
| ASUS ROG          | 5         | 1.8%    |
| Lenovo V330-15IKB | 4         | 1.44%   |
| HP 250            | 4         | 1.44%   |
| HP 14             | 4         | 1.44%   |
| Lenovo V310-15ISK | 3         | 1.08%   |
| HP OMEN           | 3         | 1.08%   |
| HP EliteBook      | 3         | 1.08%   |
| HP Compaq         | 3         | 1.08%   |
| ASUS ASUS         | 3         | 1.08%   |
| Lenovo G400       | 2         | 0.72%   |
| HP ZBook          | 2         | 0.72%   |
| HP Notebook       | 2         | 0.72%   |
| HP ENVY           | 2         | 0.72%   |
| HP 450            | 2         | 0.72%   |
| HP 255            | 2         | 0.72%   |
| HP 240            | 2         | 0.72%   |
| Dell XPS          | 2         | 0.72%   |
| Dell G5           | 2         | 0.72%   |
| ASUS X550LD       | 2         | 0.72%   |
| Apple MacBookPro9 | 2         | 0.72%   |
| Toshiba QOSMIO    | 1         | 0.36%   |
| Toshiba NB505     | 1         | 0.36%   |
| System76 Adder    | 1         | 0.36%   |
| Sony VPCEL36FJ    | 1         | 0.36%   |
| Sony VPCEC2JFX    | 1         | 0.36%   |
| Sony VGN-FW56M    | 1         | 0.36%   |
| Sony VGN-FW170J   | 1         | 0.36%   |
| Sony SVS13A25PLB  | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 30        | 10.79%  |
| 2019 | 27        | 9.71%   |
| 2021 | 26        | 9.35%   |
| 2018 | 26        | 9.35%   |
| 2016 | 23        | 8.27%   |
| 2014 | 23        | 8.27%   |
| 2013 | 21        | 7.55%   |
| 2012 | 21        | 7.55%   |
| 2017 | 18        | 6.47%   |
| 2011 | 17        | 6.12%   |
| 2022 | 10        | 3.6%    |
| 2015 | 8         | 2.88%   |
| 2008 | 7         | 2.52%   |
| 2010 | 6         | 2.16%   |
| 2023 | 5         | 1.8%    |
| 2009 | 5         | 1.8%    |
| 2007 | 4         | 1.44%   |
| 2006 | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 278       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 250       | 89.61%  |
| Enabled  | 29        | 10.39%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 276       | 99.28%  |
| Yes  | 2         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 83        | 29.12%  |
| 4.01-8.0    | 81        | 28.42%  |
| 3.01-4.0    | 51        | 17.89%  |
| 16.01-24.0  | 38        | 13.33%  |
| 1.01-2.0    | 9         | 3.16%   |
| 32.01-64.0  | 8         | 2.81%   |
| 2.01-3.0    | 6         | 2.11%   |
| 24.01-32.0  | 5         | 1.75%   |
| 64.01-256.0 | 2         | 0.7%    |
| 0.51-1.0    | 2         | 0.7%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 94        | 30.32%  |
| 1.01-2.0   | 87        | 28.06%  |
| 4.01-8.0   | 51        | 16.45%  |
| 3.01-4.0   | 42        | 13.55%  |
| 0.51-1.0   | 19        | 6.13%   |
| 8.01-16.0  | 14        | 4.52%   |
| 16.01-24.0 | 2         | 0.65%   |
| 0.01-0.5   | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 204       | 72.6%   |
| 2      | 70        | 24.91%  |
| 3      | 6         | 2.14%   |
| 0      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 181       | 65.11%  |
| Yes       | 97        | 34.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 82.8%   |
| No        | 48        | 17.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 273       | 98.2%   |
| No        | 5         | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 236       | 84.59%  |
| No        | 43        | 15.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Peru    | 278       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lima                  | 183       | 63.54%  |
| Arequipa              | 26        | 9.03%   |
| Trujillo              | 17        | 5.9%    |
| Huancayo              | 8         | 2.78%   |
| Piura                 | 6         | 2.08%   |
| Cusco                 | 6         | 2.08%   |
| Chiclayo              | 6         | 2.08%   |
| Ica                   | 4         | 1.39%   |
| La Victoria           | 3         | 1.04%   |
| Tacna                 | 2         | 0.69%   |
| San Isidro            | 2         | 0.69%   |
| Iquitos               | 2         | 0.69%   |
| Ilo                   | 2         | 0.69%   |
| Callao                | 2         | 0.69%   |
| Tarapoto              | 1         | 0.35%   |
| Santiago de Surco     | 1         | 0.35%   |
| San Vicente de Canete | 1         | 0.35%   |
| San Borja             | 1         | 0.35%   |
| Punta Colorada        | 1         | 0.35%   |
| Puno                  | 1         | 0.35%   |
| Pisco                 | 1         | 0.35%   |
| Oxapampa              | 1         | 0.35%   |
| Moquegua              | 1         | 0.35%   |
| Miraflores District   | 1         | 0.35%   |
| Lurin                 | 1         | 0.35%   |
| Juliaca               | 1         | 0.35%   |
| Huaraz                | 1         | 0.35%   |
| Distrito de Lima      | 1         | 0.35%   |
| Chimbote              | 1         | 0.35%   |
| Cajamarca             | 1         | 0.35%   |
| Barranco              | 1         | 0.35%   |
| Ayacucho              | 1         | 0.35%   |
| Abancay               | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 52        | 60     | 14.94%  |
| Toshiba                        | 45        | 55     | 12.93%  |
| Seagate                        | 42        | 51     | 12.07%  |
| Kingston                       | 41        | 50     | 11.78%  |
| Samsung Electronics            | 23        | 33     | 6.61%   |
| SanDisk                        | 18        | 21     | 5.17%   |
| Crucial                        | 14        | 20     | 4.02%   |
| Unknown                        | 12        | 13     | 3.45%   |
| Micron Technology              | 9         | 10     | 2.59%   |
| Intel                          | 9         | 11     | 2.59%   |
| SK hynix                       | 8         | 11     | 2.3%    |
| HGST                           | 8         | 8      | 2.3%    |
| KIOXIA                         | 6         | 7      | 1.72%   |
| Kingston Technology Company    | 6         | 8      | 1.72%   |
| Hitachi                        | 6         | 8      | 1.72%   |
| Hewlett-Packard                | 6         | 6      | 1.72%   |
| Netac                          | 5         | 5      | 1.44%   |
| TO Exter                       | 3         | 7      | 0.86%   |
| LITEON                         | 3         | 3      | 0.86%   |
| Gigabyte Technology            | 3         | 3      | 0.86%   |
| UMIS                           | 2         | 2      | 0.57%   |
| Silicon Motion                 | 2         | 2      | 0.57%   |
| Phison Electronics             | 2         | 2      | 0.57%   |
| China                          | 2         | 2      | 0.57%   |
| Apple                          | 2         | 2      | 0.57%   |
| A-DATA Technology              | 2         | 2      | 0.57%   |
| Unknown                        | 2         | 2      | 0.57%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.29%   |
| SSSTC                          | 1         | 1      | 0.29%   |
| Solid State Storage Technology | 1         | 1      | 0.29%   |
| Reletech-P400                  | 1         | 1      | 0.29%   |
| Phison                         | 1         | 1      | 0.29%   |
| MSI                            | 1         | 1      | 0.29%   |
| Micron/Crucial Technology      | 1         | 4      | 0.29%   |
| Lenovo                         | 1         | 1      | 0.29%   |
| KingSpec                       | 1         | 1      | 0.29%   |
| ITHOO                          | 1         | 1      | 0.29%   |
| GLOWAY                         | 1         | 1      | 0.29%   |
| Fujitsu                        | 1         | 1      | 0.29%   |
| Dogfish                        | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 17        | 4.75%   |
| Kingston SA400S37240G 240GB SSD                   | 16        | 4.47%   |
| Toshiba MQ04ABF100 1TB                            | 10        | 2.79%   |
| Toshiba MQ01ABD100 1TB                            | 9         | 2.51%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 7         | 1.96%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 1.4%    |
| Netac SSD 256GB                                   | 5         | 1.4%    |
| Kingston SA400S37480G 480GB SSD                   | 5         | 1.4%    |
| Crucial CT500MX500SSD4 500GB                      | 5         | 1.4%    |
| WDC WD10JPCX-24UE4T0 1TB                          | 4         | 1.12%   |
| Unknown SD32G  32GB                               | 4         | 1.12%   |
| Unknown MMC Card  32GB                            | 4         | 1.12%   |
| Seagate ST9500325AS 500GB                         | 4         | 1.12%   |
| Kingston Company SNV2S1000G 1TB                   | 4         | 1.12%   |
| Kingston SA400S37960G 960GB SSD                   | 4         | 1.12%   |
| Intel SSDPEKNU512GZ 512GB                         | 4         | 1.12%   |
| WDC WD10SPZX-24Z10 1TB                            | 3         | 0.84%   |
| Toshiba MQ01ABD075 752GB                          | 3         | 0.84%   |
| TO Exter nal USB 3.0 512GB                        | 3         | 0.84%   |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 0.84%   |
| Seagate ST1000LM049-2GH172 1TB                    | 3         | 0.84%   |
| SanDisk NVMe SSD Drive 1TB                        | 3         | 0.84%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                    | 3         | 0.84%   |
| Kingston SA400S37120G 120GB SSD                   | 3         | 0.84%   |
| HGST HTS721010A9E630 1TB                          | 3         | 0.84%   |
| HP SSD S700 500GB                                 | 3         | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 2         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.56%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 2         | 0.56%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB              | 2         | 0.56%   |
| Toshiba MK2565GSXN 250GB                          | 2         | 0.56%   |
| Toshiba HDWJ110 1TB                               | 2         | 0.56%   |
| Seagate ST500LT012-9WS142 500GB                   | 2         | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB                   | 2         | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB                    | 2         | 0.56%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB              | 2         | 0.56%   |
| SanDisk NVMe SSD Drive 512GB                      | 2         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 43        | 53     | 31.39%  |
| Seagate  | 42        | 49     | 30.66%  |
| WDC      | 32        | 35     | 23.36%  |
| HGST     | 8         | 8      | 5.84%   |
| Hitachi  | 6         | 8      | 4.38%   |
| TO Exter | 3         | 7      | 2.19%   |
| Fujitsu  | 1         | 1      | 0.73%   |
| Apple    | 1         | 1      | 0.73%   |
| ACASIS   | 1         | 1      | 0.73%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 34        | 41     | 31.78%  |
| WDC                 | 16        | 19     | 14.95%  |
| Crucial             | 13        | 18     | 12.15%  |
| Samsung Electronics | 6         | 6      | 5.61%   |
| Hewlett-Packard     | 6         | 6      | 5.61%   |
| SanDisk             | 5         | 7      | 4.67%   |
| Netac               | 5         | 5      | 4.67%   |
| LITEON              | 3         | 3      | 2.8%    |
| Gigabyte Technology | 2         | 2      | 1.87%   |
| China               | 2         | 2      | 1.87%   |
| A-DATA Technology   | 2         | 2      | 1.87%   |
| Toshiba             | 1         | 1      | 0.93%   |
| SSSTC               | 1         | 1      | 0.93%   |
| SK hynix            | 1         | 4      | 0.93%   |
| Seagate             | 1         | 1      | 0.93%   |
| Reletech-P400       | 1         | 1      | 0.93%   |
| MSI                 | 1         | 1      | 0.93%   |
| Lenovo              | 1         | 1      | 0.93%   |
| KingSpec            | 1         | 1      | 0.93%   |
| Intel               | 1         | 1      | 0.93%   |
| GLOWAY              | 1         | 1      | 0.93%   |
| Dogfish             | 1         | 1      | 0.93%   |
| Apple               | 1         | 1      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 136       | 163    | 40.72%  |
| SSD     | 97        | 127    | 29.04%  |
| NVMe    | 87        | 119    | 26.05%  |
| MMC     | 12        | 13     | 3.59%   |
| Unknown | 2         | 2      | 0.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 201       | 282    | 65.69%  |
| NVMe | 87        | 119    | 28.43%  |
| MMC  | 12        | 13     | 3.92%   |
| SAS  | 6         | 10     | 1.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 121       | 163    | 54.02%  |
| 0.51-1.0   | 100       | 121    | 44.64%  |
| 1.01-2.0   | 2         | 5      | 0.89%   |
| 4.01-10.0  | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 25.09%  |
| 251-500        | 68        | 23.69%  |
| 501-1000       | 59        | 20.56%  |
| 21-50          | 22        | 7.67%   |
| 51-100         | 20        | 6.97%   |
| 1001-2000      | 17        | 5.92%   |
| 1-20           | 17        | 5.92%   |
| 2001-3000      | 5         | 1.74%   |
| More than 3000 | 4         | 1.39%   |
| Unknown        | 3         | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 113       | 37.92%  |
| 21-50          | 64        | 21.48%  |
| 101-250        | 38        | 12.75%  |
| 51-100         | 35        | 11.74%  |
| 251-500        | 24        | 8.05%   |
| 501-1000       | 14        | 4.7%    |
| 1001-2000      | 4         | 1.34%   |
| Unknown        | 3         | 1.01%   |
| 2001-3000      | 2         | 0.67%   |
| More than 3000 | 1         | 0.34%   |

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
| Detected | 167       | 245    | 55.12%  |
| Works    | 108       | 145    | 35.64%  |
| Malfunc  | 27        | 32     | 8.91%   |
| Failed   | 1         | 2      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 197       | 60.99%  |
| AMD                              | 39        | 12.07%  |
| SanDisk                          | 19        | 5.88%   |
| Samsung Electronics              | 18        | 5.57%   |
| Kingston Technology Company      | 13        | 4.02%   |
| Micron Technology                | 9         | 2.79%   |
| SK hynix                         | 7         | 2.17%   |
| KIOXIA                           | 6         | 1.86%   |
| Phison Electronics               | 3         | 0.93%   |
| Union Memory (Shenzhen)          | 2         | 0.62%   |
| Silicon Motion                   | 2         | 0.62%   |
| Micron/Crucial Technology        | 2         | 0.62%   |
| Toshiba America Info Systems     | 1         | 0.31%   |
| Solid State Storage Technology   | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Nvidia                           | 1         | 0.31%   |
| INNOGRIT                         | 1         | 0.31%   |
| Biwin Storage Technology         | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 10.03%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 33        | 9.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 7.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 6.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 11        | 3.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 2.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 2.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.77%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 1.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 6         | 1.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.47%   |
| SK hynix BC511 NVMe SSD                                                        | 4         | 1.18%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 4         | 1.18%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 4         | 1.18%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.88%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 3         | 0.88%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 3         | 0.88%   |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                 | 3         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.88%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 0.59%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.59%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                          | 2         | 0.59%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 2         | 0.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.59%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.59%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.59%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 195       | 59.45%  |
| NVMe | 87        | 26.52%  |
| RAID | 36        | 10.98%  |
| IDE  | 10        | 3.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 216       | 77.7%   |
| AMD    | 62        | 22.3%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 2.52%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 2.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 2.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 2.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 1.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.8%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.8%    |
| Intel Celeron J4115 CPU @ 1.80GHz             | 5         | 1.8%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.8%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 1.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 1.08%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 1.08%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.08%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.08%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.08%   |
| Intel Celeron CPU 550 @ 2.00GHz               | 3         | 1.08%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 3         | 1.08%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.08%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 3         | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.72%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.72%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 69        | 24.82%  |
| Intel Core i5           | 67        | 24.1%   |
| Intel Core i3           | 31        | 11.15%  |
| Other                   | 21        | 7.55%   |
| AMD Ryzen 5             | 19        | 6.83%   |
| AMD Ryzen 7             | 18        | 6.47%   |
| Intel Celeron           | 13        | 4.68%   |
| Intel Atom              | 5         | 1.8%    |
| Intel Core 2 Duo        | 4         | 1.44%   |
| AMD Athlon              | 3         | 1.08%   |
| AMD A8                  | 3         | 1.08%   |
| AMD A4                  | 3         | 1.08%   |
| Intel Pentium Dual-Core | 2         | 0.72%   |
| Intel Pentium           | 2         | 0.72%   |
| AMD Ryzen 9             | 2         | 0.72%   |
| AMD Ryzen 7 PRO         | 2         | 0.72%   |
| AMD Ryzen 3             | 2         | 0.72%   |
| AMD E1                  | 2         | 0.72%   |
| AMD E                   | 2         | 0.72%   |
| Intel Xeon              | 1         | 0.36%   |
| Intel Pentium Dual      | 1         | 0.36%   |
| Intel Genuine           | 1         | 0.36%   |
| Intel Celeron M         | 1         | 0.36%   |
| AMD Quad-Core           | 1         | 0.36%   |
| AMD C-50                | 1         | 0.36%   |
| AMD A12                 | 1         | 0.36%   |
| AMD A10                 | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 130       | 46.76%  |
| 4       | 98        | 35.25%  |
| 8       | 21        | 7.55%   |
| 6       | 14        | 5.04%   |
| 1       | 7         | 2.52%   |
| 14      | 2         | 0.72%   |
| 10      | 2         | 0.72%   |
| 24      | 1         | 0.36%   |
| 16      | 1         | 0.36%   |
| 12      | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 278       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 230       | 82.73%  |
| 1       | 47        | 16.91%  |
| Unknown | 1         | 0.36%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 272       | 97.14%  |
| 64-bit         | 3         | 1.07%   |
| 32-bit         | 3         | 1.07%   |
| Unknown        | 2         | 0.71%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 31.96%  |
| 0x206a7    | 16        | 5.5%    |
| 0x306a9    | 12        | 4.12%   |
| 0x40651    | 11        | 3.78%   |
| 0x806ec    | 10        | 3.44%   |
| 0x806ea    | 10        | 3.44%   |
| 0x406e3    | 10        | 3.44%   |
| 0x806e9    | 9         | 3.09%   |
| 0x306d4    | 9         | 3.09%   |
| 0x08108109 | 8         | 2.75%   |
| 0x306c3    | 7         | 2.41%   |
| 0x08108102 | 6         | 2.06%   |
| 0x906ea    | 5         | 1.72%   |
| 0x806c1    | 5         | 1.72%   |
| 0x706e5    | 5         | 1.72%   |
| 0x0a50000c | 5         | 1.72%   |
| 0x20655    | 4         | 1.37%   |
| 0xa0652    | 3         | 1.03%   |
| 0x806eb    | 3         | 1.03%   |
| 0x30678    | 3         | 1.03%   |
| 0x20652    | 3         | 1.03%   |
| 0x1067a    | 3         | 1.03%   |
| 0x10661    | 3         | 1.03%   |
| 0x08608103 | 3         | 1.03%   |
| 0x08600106 | 3         | 1.03%   |
| 0x906e9    | 2         | 0.69%   |
| 0x906a3    | 2         | 0.69%   |
| 0x806d1    | 2         | 0.69%   |
| 0x0a404101 | 2         | 0.69%   |
| 0x08600104 | 2         | 0.69%   |
| 0x08600102 | 2         | 0.69%   |
| 0x06006704 | 2         | 0.69%   |
| 0x05000029 | 2         | 0.69%   |
| 0x906a4    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x6fd      | 1         | 0.34%   |
| 0x6e8      | 1         | 0.34%   |
| 0x6d8      | 1         | 0.34%   |
| 0x506e3    | 1         | 0.34%   |
| 0x406c4    | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 58        | 20.79%  |
| Haswell          | 25        | 8.96%   |
| IvyBridge        | 20        | 7.17%   |
| Zen+             | 18        | 6.45%   |
| SandyBridge      | 18        | 6.45%   |
| Skylake          | 17        | 6.09%   |
| Unknown          | 12        | 4.3%    |
| Broadwell        | 11        | 3.94%   |
| IceLake          | 10        | 3.58%   |
| Zen 2            | 9         | 3.23%   |
| Westmere         | 9         | 3.23%   |
| Silvermont       | 8         | 2.87%   |
| Zen 3            | 7         | 2.51%   |
| TigerLake        | 7         | 2.51%   |
| Penryn           | 6         | 2.15%   |
| Alderlake Hybrid | 6         | 2.15%   |
| Goldmont plus    | 5         | 1.79%   |
| Excavator        | 5         | 1.79%   |
| Zen              | 4         | 1.43%   |
| Core             | 4         | 1.43%   |
| CometLake        | 4         | 1.43%   |
| Piledriver       | 3         | 1.08%   |
| Jaguar           | 3         | 1.08%   |
| Bobcat           | 3         | 1.08%   |
| Puma             | 2         | 0.72%   |
| P6               | 2         | 0.72%   |
| Bonnell          | 2         | 0.72%   |
| Nehalem          | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 200       | 55.1%   |
| AMD                              | 88        | 24.24%  |
| Nvidia                           | 74        | 20.39%  |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 19        | 5.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 4.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 4.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 3.2%    |
| Intel HD Graphics 620                                                                    | 12        | 3.2%    |
| Intel HD Graphics 5500                                                                   | 11        | 2.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.4%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 9         | 2.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.87%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.87%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.33%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.33%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.07%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.07%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.07%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.07%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.07%   |
| AMD Lucienne                                                                             | 4         | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.8%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.8%    |
| Intel HD Graphics 530                                                                    | 3         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.8%    |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 0.8%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 124       | 44.6%   |
| Intel + Nvidia | 52        | 18.71%  |
| 1 x AMD        | 48        | 17.27%  |
| Intel + AMD    | 22        | 7.91%   |
| 1 x Nvidia     | 11        | 3.96%   |
| AMD + Nvidia   | 11        | 3.96%   |
| 2 x AMD        | 7         | 2.52%   |
| 2 x Intel      | 2         | 0.72%   |
| 1 x SiS        | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 235       | 83.63%  |
| Proprietary | 40        | 14.23%  |
| Unknown     | 6         | 2.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 165       | 58.1%   |
| 1.01-2.0   | 46        | 16.2%   |
| 0.01-0.5   | 38        | 13.38%  |
| 3.01-4.0   | 14        | 4.93%   |
| 0.51-1.0   | 9         | 3.17%   |
| 5.01-6.0   | 5         | 1.76%   |
| 7.01-8.0   | 4         | 1.41%   |
| 8.01-16.0  | 2         | 0.7%    |
| 2.01-3.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 71        | 22.12%  |
| BOE                     | 53        | 16.51%  |
| AU Optronics            | 47        | 14.64%  |
| Samsung Electronics     | 44        | 13.71%  |
| LG Display              | 36        | 11.21%  |
| Goldstar                | 12        | 3.74%   |
| PANDA                   | 7         | 2.18%   |
| Hewlett-Packard         | 5         | 1.56%   |
| Apple                   | 4         | 1.25%   |
| Sharp                   | 3         | 0.93%   |
| AOC                     | 3         | 0.93%   |
| TMX                     | 2         | 0.62%   |
| Sony                    | 2         | 0.62%   |
| LG Philips              | 2         | 0.62%   |
| Lenovo                  | 2         | 0.62%   |
| JRY                     | 2         | 0.62%   |
| HannStar                | 2         | 0.62%   |
| Dell                    | 2         | 0.62%   |
| AGO                     | 2         | 0.62%   |
| Unknown                 | 2         | 0.62%   |
| Yuraku                  | 1         | 0.31%   |
| ViewSonic               | 1         | 0.31%   |
| Unknown (XXX)           | 1         | 0.31%   |
| Sceptre Tech            | 1         | 0.31%   |
| Panasonic               | 1         | 0.31%   |
| MSI                     | 1         | 0.31%   |
| Mi                      | 1         | 0.31%   |
| LGD                     | 1         | 0.31%   |
| InnoLux Display         | 1         | 0.31%   |
| InfoVision              | 1         | 0.31%   |
| HUAWEI                  | 1         | 0.31%   |
| Hitachi                 | 1         | 0.31%   |
| EXP                     | 1         | 0.31%   |
| DZX                     | 1         | 0.31%   |
| CSO                     | 1         | 0.31%   |
| Chi Mei Optoelectronics | 1         | 0.31%   |
| BenQ                    | 1         | 0.31%   |
| Acer                    | 1         | 0.31%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 12        | 3.73%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 9         | 2.8%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 5         | 1.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 1.24%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 4         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 3         | 0.93%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 3         | 0.93%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 0.93%   |
| AU Optronics LCD Monitor AUO459D 1920x1200 344x215mm 16.0-inch       | 3         | 0.93%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch              | 2         | 0.62%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch     | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5142 1280x800 303x190mm 14.1-inch | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 2         | 0.62%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 2         | 0.62%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 2         | 0.62%   |
| LG Display LCD Monitor LGD062F 1920x1080 344x194mm 15.5-inch         | 2         | 0.62%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch         | 2         | 0.62%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 2         | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.62%   |
| JRY DX238A1 JRY2380 1920x1080 368x207mm 16.6-inch                    | 2         | 0.62%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 2         | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2         | 0.62%   |
| Goldstar E2351 GSM5872 1920x1080 510x290mm 23.1-inch                 | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 2         | 0.62%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch      | 2         | 0.62%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.62%   |
| BOE LCD Monitor BOE07C6 1366x768 309x173mm 13.9-inch                 | 2         | 0.62%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                 | 2         | 0.62%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 2         | 0.62%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.62%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 147       | 47.57%  |
| 1920x1080 (FHD)   | 101       | 32.69%  |
| 1600x900 (HD+)    | 10        | 3.24%   |
| 1280x800 (WXGA)   | 9         | 2.91%   |
| 3840x2160 (4K)    | 6         | 1.94%   |
| 2160x1440         | 5         | 1.62%   |
| 1920x1200 (WUXGA) | 5         | 1.62%   |
| 1440x900 (WXGA+)  | 5         | 1.62%   |
| 1360x768          | 4         | 1.29%   |
| 3200x1800 (QHD+)  | 2         | 0.65%   |
| 2560x1600         | 2         | 0.65%   |
| 2560x1440 (QHD)   | 2         | 0.65%   |
| 1024x600          | 2         | 0.65%   |
| Unknown           | 2         | 0.65%   |
| 640x480           | 1         | 0.32%   |
| 3840x1080         | 1         | 0.32%   |
| 3200x2000         | 1         | 0.32%   |
| 2880x1800         | 1         | 0.32%   |
| 2520x1680         | 1         | 0.32%   |
| 1280x720 (HD)     | 1         | 0.32%   |
| 1024x768 (XGA)    | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 146       | 46.06%  |
| 13      | 53        | 16.72%  |
| 14      | 40        | 12.62%  |
| 23      | 14        | 4.42%   |
| 21      | 9         | 2.84%   |
| 17      | 9         | 2.84%   |
| 18      | 6         | 1.89%   |
| 16      | 6         | 1.89%   |
| 11      | 5         | 1.58%   |
| 24      | 4         | 1.26%   |
| 12      | 4         | 1.26%   |
| Unknown | 3         | 0.95%   |
| 72      | 2         | 0.63%   |
| 31      | 2         | 0.63%   |
| 27      | 2         | 0.63%   |
| 20      | 2         | 0.63%   |
| 10      | 2         | 0.63%   |
| 84      | 1         | 0.32%   |
| 60      | 1         | 0.32%   |
| 54      | 1         | 0.32%   |
| 48      | 1         | 0.32%   |
| 46      | 1         | 0.32%   |
| 39      | 1         | 0.32%   |
| 22      | 1         | 0.32%   |
| 19      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 227       | 72.29%  |
| 201-300     | 24        | 7.64%   |
| 501-600     | 20        | 6.37%   |
| 401-500     | 19        | 6.05%   |
| 351-400     | 11        | 3.5%    |
| 1001-1500   | 4         | 1.27%   |
| 1501-2000   | 3         | 0.96%   |
| Unknown     | 3         | 0.96%   |
| 601-700     | 2         | 0.64%   |
| 801-900     | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 242       | 86.12%  |
| 16/10   | 26        | 9.25%   |
| 3/2     | 6         | 2.14%   |
| 4/3     | 4         | 1.42%   |
| Unknown | 3         | 1.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 146       | 46.06%  |
| 81-90          | 80        | 25.24%  |
| 201-250        | 26        | 8.2%    |
| 71-80          | 12        | 3.79%   |
| 121-130        | 7         | 2.21%   |
| More than 1000 | 6         | 1.89%   |
| 151-200        | 6         | 1.89%   |
| 111-120        | 6         | 1.89%   |
| 51-60          | 5         | 1.58%   |
| 141-150        | 5         | 1.58%   |
| 131-140        | 3         | 0.95%   |
| Unknown        | 3         | 0.95%   |
| 61-70          | 2         | 0.63%   |
| 351-500        | 2         | 0.63%   |
| 41-50          | 2         | 0.63%   |
| 301-350        | 2         | 0.63%   |
| 501-1000       | 2         | 0.63%   |
| 91-100         | 2         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 149       | 47.6%   |
| 121-160       | 92        | 29.39%  |
| 51-100        | 44        | 14.06%  |
| 161-240       | 14        | 4.47%   |
| 1-50          | 7         | 2.24%   |
| More than 240 | 4         | 1.28%   |
| Unknown       | 3         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 224       | 78.6%   |
| 2     | 51        | 17.89%  |
| 0     | 8         | 2.81%   |
| 3     | 2         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 171       | 39.95%  |
| Intel                            | 104       | 24.3%   |
| Qualcomm Atheros                 | 78        | 18.22%  |
| Broadcom                         | 19        | 4.44%   |
| MediaTek                         | 10        | 2.34%   |
| TP-Link                          | 9         | 2.1%    |
| Ralink                           | 7         | 1.64%   |
| Xiaomi                           | 6         | 1.4%    |
| Marvell Technology Group         | 4         | 0.93%   |
| ASIX Electronics                 | 3         | 0.7%    |
| Samsung Electronics              | 2         | 0.47%   |
| Ralink Technology                | 2         | 0.47%   |
| Motorola PCS                     | 2         | 0.47%   |
| ICS Advent                       | 2         | 0.47%   |
| T & A Mobile Phones              | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| OPPO Electronics                 | 1         | 0.23%   |
| Nvidia                           | 1         | 0.23%   |
| Microsoft                        | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| DisplayLink                      | 1         | 0.23%   |
| Broadcom Limited                 | 1         | 0.23%   |
| Apple                            | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 109       | 20.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 33        | 6.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 4.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.71%   |
| Intel Wireless 8260                                                     | 9         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.52%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 1.14%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 1.14%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.95%   |
| Intel Wireless 7265                                                     | 5         | 0.95%   |
| Intel Wireless 7260                                                     | 5         | 0.95%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 0.95%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.76%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.57%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 0.57%   |
| Intel WiFi Link 5100                                                    | 3         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.57%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 100       | 35.21%  |
| Qualcomm Atheros      | 70        | 24.65%  |
| Realtek Semiconductor | 69        | 24.3%   |
| Broadcom              | 17        | 5.99%   |
| MediaTek              | 10        | 3.52%   |
| TP-Link               | 8         | 2.82%   |
| Ralink                | 7         | 2.46%   |
| Ralink Technology     | 2         | 0.7%    |
| Broadcom Limited      | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 9.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 6.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 18        | 6.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.17%   |
| Intel Wireless 8260                                                     | 9         | 3.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 2.82%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 2.46%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 2.46%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 6         | 2.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 2.11%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.76%   |
| Intel Wireless 7265                                                     | 5         | 1.76%   |
| Intel Wireless 7260                                                     | 5         | 1.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 5         | 1.76%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 4         | 1.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.41%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.06%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 1.06%   |
| Intel WiFi Link 5100                                                    | 3         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 1.06%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.7%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 2         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.7%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.7%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.7%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 2         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 153       | 63.75%  |
| Intel                            | 37        | 15.42%  |
| Qualcomm Atheros                 | 18        | 7.5%    |
| Xiaomi                           | 6         | 2.5%    |
| Marvell Technology Group         | 4         | 1.67%   |
| Broadcom                         | 4         | 1.67%   |
| ASIX Electronics                 | 3         | 1.25%   |
| Samsung Electronics              | 2         | 0.83%   |
| Motorola PCS                     | 2         | 0.83%   |
| ICS Advent                       | 2         | 0.83%   |
| TP-Link                          | 1         | 0.42%   |
| T & A Mobile Phones              | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| OPPO Electronics                 | 1         | 0.42%   |
| Nvidia                           | 1         | 0.42%   |
| Microsoft                        | 1         | 0.42%   |
| Lenovo                           | 1         | 0.42%   |
| DisplayLink                      | 1         | 0.42%   |
| Apple                            | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 109       | 45.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 33        | 13.64%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 2.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 6         | 2.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 1.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.24%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.83%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.83%   |
| Motorola PCS moto g52                                                          | 2         | 0.83%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.83%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.83%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.83%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.83%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.83%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 2         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.83%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.83%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.41%   |
| T & A Mobile Phones ALCATEL ONE TOUCH POP C1                                   | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.41%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.41%   |
| OPPO SM8350-IDP _SN:361A1B3C                                                   | 1         | 0.41%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.41%   |
| Microsoft Ethernet Adapter                                                     | 1         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.41%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 273       | 54.17%  |
| Ethernet | 231       | 45.83%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 219       | 74.24%  |
| Ethernet | 76        | 25.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 208       | 74.82%  |
| 1     | 67        | 24.1%   |
| 0     | 3         | 1.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 220       | 77.19%  |
| Yes  | 65        | 22.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 34.18%  |
| Realtek Semiconductor           | 49        | 20.68%  |
| Qualcomm Atheros Communications | 37        | 15.61%  |
| IMC Networks                    | 20        | 8.44%   |
| Lite-On Technology              | 12        | 5.06%   |
| Toshiba                         | 8         | 3.38%   |
| Ralink                          | 6         | 2.53%   |
| Foxconn / Hon Hai               | 5         | 2.11%   |
| Broadcom                        | 5         | 2.11%   |
| Apple                           | 4         | 1.69%   |
| Hewlett-Packard                 | 3         | 1.27%   |
| Dell                            | 2         | 0.84%   |
| Cambridge Silicon Radio         | 2         | 0.84%   |
| Realtek                         | 1         | 0.42%   |
| Foxconn International           | 1         | 0.42%   |
| Alps Electric                   | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 29        | 12.24%  |
| Realtek Bluetooth Radio                             | 27        | 11.39%  |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 9.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 8.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 8.44%   |
| Intel AX201 Bluetooth                               | 10        | 4.22%   |
| Intel Bluetooth Device                              | 8         | 3.38%   |
| IMC Networks Wireless_Device                        | 8         | 3.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 2.95%   |
| Ralink RT3290 Bluetooth                             | 6         | 2.53%   |
| Intel AX200 Bluetooth                               | 6         | 2.53%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.53%   |
| Toshiba Bluetooth Device                            | 5         | 2.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.69%   |
| IMC Networks Bluetooth Device                       | 4         | 1.69%   |
| Lite-On Bluetooth Radio                             | 3         | 1.27%   |
| Lite-On Bluetooth Device                            | 3         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.27%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.84%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.84%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.84%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.84%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.84%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.84%   |
| Apple Bluetooth Host Controller                     | 2         | 0.84%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.42%   |
| Toshiba BCM43142A0                                  | 1         | 0.42%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.42%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.42%   |
| Realtek Bluetooth Radio                             | 1         | 0.42%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.42%   |
| Intel AX210 Bluetooth                               | 1         | 0.42%   |
| IMC Networks BCM20702A0                             | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 210       | 62.5%   |
| AMD                              | 68        | 20.24%  |
| Nvidia                           | 40        | 11.9%   |
| Generalplus Technology           | 3         | 0.89%   |
| C-Media Electronics              | 3         | 0.89%   |
| Sony                             | 2         | 0.6%    |
| Kingston Technology              | 2         | 0.6%    |
| GN Netcom                        | 2         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Razer USA                        | 1         | 0.3%    |
| Pixart Imaging                   | 1         | 0.3%    |
| Panasonic (Matsushita)           | 1         | 0.3%    |
| Logitech                         | 1         | 0.3%    |
| Hewlett-Packard                  | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 45        | 10.56%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 44        | 10.33%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 4.93%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 3.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 3.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.05%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.58%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 2.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 1.88%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.41%   |
| Nvidia Audio device                                                                               | 6         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.41%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.94%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.7%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.7%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.7%    |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 30%     |
| SK hynix            | 44        | 20.95%  |
| Micron Technology   | 29        | 13.81%  |
| Kingston            | 25        | 11.9%   |
| Ramaxel Technology  | 11        | 5.24%   |
| Unknown             | 10        | 4.76%   |
| Unknown (ABCD)      | 5         | 2.38%   |
| Team                | 5         | 2.38%   |
| Crucial             | 4         | 1.9%    |
| Hewlett-Packard     | 3         | 1.43%   |
| Elpida              | 3         | 1.43%   |
| Patriot             | 2         | 0.95%   |
| Kllisre             | 1         | 0.48%   |
| Goldkey             | 1         | 0.48%   |
| CSX                 | 1         | 0.48%   |
| Corsair             | 1         | 0.48%   |
| A-DATA Technology   | 1         | 0.48%   |
| Unknown             | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 6         | 2.68%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 2.68%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 5         | 2.23%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 2.23%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 4         | 1.79%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 1.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 1.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 1.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.34%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 1.34%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.34%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 1.34%   |
| Kingston RAM 99U5428-046.A00LF 4GB SODIMM DDR3 1600MT/s             | 3         | 1.34%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 2         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.89%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.89%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.89%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 0.89%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 0.89%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 0.89%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.89%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.89%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.89%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.89%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.89%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.89%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 76        | 47.2%   |
| DDR3    | 58        | 36.02%  |
| LPDDR4  | 12        | 7.45%   |
| DDR2    | 4         | 2.48%   |
| LPDDR3  | 3         | 1.86%   |
| DDR5    | 3         | 1.86%   |
| SDRAM   | 2         | 1.24%   |
| LPDDR5  | 2         | 1.24%   |
| Unknown | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 151       | 94.38%  |
| Row Of Chips | 8         | 5%      |
| Unknown      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 80        | 42.55%  |
| 4096  | 65        | 34.57%  |
| 16384 | 19        | 10.11%  |
| 2048  | 15        | 7.98%   |
| 32768 | 4         | 2.13%   |
| 1024  | 4         | 2.13%   |
| 512   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 25.14%  |
| 2667    | 45        | 24.59%  |
| 3200    | 37        | 20.22%  |
| 2400    | 13        | 7.1%    |
| 3266    | 6         | 3.28%   |
| 2133    | 6         | 3.28%   |
| 1334    | 6         | 3.28%   |
| 1333    | 5         | 2.73%   |
| 4800    | 3         | 1.64%   |
| Unknown | 3         | 1.64%   |
| 1867    | 2         | 1.09%   |
| 1067    | 2         | 1.09%   |
| 6400    | 1         | 0.55%   |
| 5500    | 1         | 0.55%   |
| 4267    | 1         | 0.55%   |
| 4199    | 1         | 0.55%   |
| 2933    | 1         | 0.55%   |
| 1066    | 1         | 0.55%   |
| 800     | 1         | 0.55%   |
| 667     | 1         | 0.55%   |
| 533     | 1         | 0.55%   |

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
| Seiko Epson L3150 Series                      | 1         | 14.29%  |
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
| Chicony Electronics                    | 58        | 21.97%  |
| IMC Networks                           | 28        | 10.61%  |
| Realtek Semiconductor                  | 22        | 8.33%   |
| Microdia                               | 22        | 8.33%   |
| Bison Electronics                      | 18        | 6.82%   |
| Syntek                                 | 17        | 6.44%   |
| Quanta                                 | 14        | 5.3%    |
| Cheng Uei Precision Industry (Foxlink) | 14        | 5.3%    |
| Sunplus Innovation Technology          | 13        | 4.92%   |
| Suyin                                  | 11        | 4.17%   |
| Lite-On Technology                     | 11        | 4.17%   |
| Acer                                   | 5         | 1.89%   |
| Sonix Technology                       | 4         | 1.52%   |
| Luxvisions Innotech Limited            | 4         | 1.52%   |
| Importek                               | 4         | 1.52%   |
| Apple                                  | 4         | 1.52%   |
| ShineTech                              | 2         | 0.76%   |
| Samsung Electronics                    | 2         | 0.76%   |
| Ricoh                                  | 2         | 0.76%   |
| Logitech                               | 2         | 0.76%   |
| Alcor Micro                            | 2         | 0.76%   |
| Silicon Motion                         | 1         | 0.38%   |
| Jieli Technology                       | 1         | 0.38%   |
| ASUSTek Computer                       | 1         | 0.38%   |
| ANYKA                                  | 1         | 0.38%   |
| 8SSC20F27114V1SR0BK1X4S                | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 12        | 4.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 3.02%   |
| Bison Integrated Camera                                                    | 8         | 3.02%   |
| Chicony Integrated Camera                                                  | 6         | 2.26%   |
| Chicony HP Truevision HD                                                   | 6         | 2.26%   |
| Chicony EasyCamera                                                         | 6         | 2.26%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 1.89%   |
| Microdia Webcam Vitade AF                                                  | 5         | 1.89%   |
| Microdia Integrated_Webcam_HD                                              | 5         | 1.89%   |
| Lite-On Integrated Camera                                                  | 5         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 1.89%   |
| IMC Networks Integrated Camera                                             | 5         | 1.89%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.51%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 4         | 1.51%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 1.51%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.51%   |
| Chicony TOSHIBA Web Camera - HD                                            | 4         | 1.51%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.51%   |
| Chicony HD WebCam                                                          | 4         | 1.51%   |
| Realtek USB Camera                                                         | 3         | 1.13%   |
| Lite-On HP HD Camera                                                       | 3         | 1.13%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.13%   |
| Chicony HP HD Webcam                                                       | 3         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 3         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 1.13%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.13%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.75%   |
| Sunplus Integrated Webcam                                                  | 2         | 0.75%   |
| ShineTech USB2.0 HD UVC WebCam                                             | 2         | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 2         | 0.75%   |
| Ricoh Sony Vaio Integrated Webcam                                          | 2         | 0.75%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.75%   |
| Realtek Integrated Webcam                                                  | 2         | 0.75%   |
| Realtek HP Wide Vision HD Camera                                           | 2         | 0.75%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.75%   |
| Quanta HP Webcam                                                           | 2         | 0.75%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.75%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.75%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 48.98%  |
| Synaptics                  | 13        | 26.53%  |
| Shenzhen Goodix Technology | 5         | 10.2%   |
| Elan Microelectronics      | 4         | 8.16%   |
| AuthenTec                  | 2         | 4.08%   |
| STMicroelectronics         | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 8         | 16.33%  |
| Validity Sensors VFS5011 Fingerprint Reader               | 7         | 14.29%  |
| Synaptics  WBDI                                           | 4         | 8.16%   |
| Shenzhen Goodix  FingerPrint Device                       | 3         | 6.12%   |
| Elan ELAN:Fingerprint                                     | 3         | 6.12%   |
| Validity Sensors Synaptics WBDI                           | 2         | 4.08%   |
| Validity Sensors Fingerprint scanner                      | 2         | 4.08%   |
| Synaptics WBDI Fingerprint Reader USB 086                 | 2         | 4.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.08%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 4.08%   |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.04%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 2.04%   |
| Synaptics WBDI                                            | 1         | 2.04%   |
| Synaptics UWP WBDI Device                                 | 1         | 2.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 2.04%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 2.04%   |
| STMicroelectronics Fingerprint Reader                     | 1         | 2.04%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 7         | 46.67%  |
| Alcor Micro | 4         | 26.67%  |
| Upek        | 3         | 20%     |
| O2 Micro    | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 20%     |
| Broadcom 5880                                                                | 3         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 6.67%   |
| Broadcom 58200                                                               | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 174       | 61.05%  |
| 1     | 88        | 30.88%  |
| 2     | 20        | 7.02%   |
| 3     | 3         | 1.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 37.12%  |
| Graphics card            | 29        | 21.97%  |
| Net/wireless             | 17        | 12.88%  |
| Chipcard                 | 13        | 9.85%   |
| Bluetooth                | 8         | 6.06%   |
| Multimedia controller    | 5         | 3.79%   |
| Storage                  | 2         | 1.52%   |
| Sound                    | 2         | 1.52%   |
| Communication controller | 2         | 1.52%   |
| Card reader              | 2         | 1.52%   |
| Camera                   | 2         | 1.52%   |
| Net/ethernet             | 1         | 0.76%   |

