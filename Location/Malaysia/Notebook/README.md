Linux in Malaysia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

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

Total: 291

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5420               | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| Samsung       | 730U3E/740U3E               | [9763d78500](https://linux-hardware.org/?probe=9763d78500) | Feb 15, 2023 |
| Samsung       | 730U3E/740U3E               | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| HP            | ENVY 4                      | [0344f89eea](https://linux-hardware.org/?probe=0344f89eea) | Feb 07, 2023 |
| Acer          | Nitro AN515-54              | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | [5260560c15](https://linux-hardware.org/?probe=5260560c15) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| Dell          | Latitude E6400              | [a195487665](https://linux-hardware.org/?probe=a195487665) | Jan 30, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [d356c9846a](https://linux-hardware.org/?probe=d356c9846a) | Jan 30, 2023 |
| HP            | ENVY 4                      | [55ee9d4ca9](https://linux-hardware.org/?probe=55ee9d4ca9) | Jan 27, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [d3e44e2970](https://linux-hardware.org/?probe=d3e44e2970) | Jan 20, 2023 |
| Dell          | Latitude 3410               | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Valve         | Jupiter                     | [5d228e798d](https://linux-hardware.org/?probe=5d228e798d) | Jan 16, 2023 |
| Samsung       | RV413/RV513                 | [4acb924b75](https://linux-hardware.org/?probe=4acb924b75) | Jan 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | EliteBook 840 G2            | [72a6b9a90b](https://linux-hardware.org/?probe=72a6b9a90b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a712e2524b](https://linux-hardware.org/?probe=a712e2524b) | Jan 09, 2023 |
| Dell          | Latitude 5420               | [06dc453cbc](https://linux-hardware.org/?probe=06dc453cbc) | Dec 27, 2022 |
| HP            | Notebook                    | [8ba42c8ebc](https://linux-hardware.org/?probe=8ba42c8ebc) | Dec 27, 2022 |
| Dell          | Inspiron 3505               | [fd4611b301](https://linux-hardware.org/?probe=fd4611b301) | Dec 21, 2022 |
| Dell          | Inspiron 15 3511            | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Gigabyte      | G5 KC                       | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Acer          | Aspire V5-471G              | [10a6f30aeb](https://linux-hardware.org/?probe=10a6f30aeb) | Dec 04, 2022 |
| Acer          | Aspire V5-471G              | [725404aadb](https://linux-hardware.org/?probe=725404aadb) | Dec 04, 2022 |
| Sony          | VPCEG16EG                   | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Latitude E6220              | [c92cd25690](https://linux-hardware.org/?probe=c92cd25690) | Nov 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS1S81K    | [ee3fb9c9d2](https://linux-hardware.org/?probe=ee3fb9c9d2) | Nov 14, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Dell          | Latitude E6230              | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| Dell          | Latitude E5450              | [b39c12a9a4](https://linux-hardware.org/?probe=b39c12a9a4) | Nov 02, 2022 |
| ASUSTek       | X555QG                      | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| NEC Comput... | PC-VK27MXZCG                | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Precision 3561              | [dcf74e5715](https://linux-hardware.org/?probe=dcf74e5715) | Oct 22, 2022 |
| Dell          | Precision 3561              | [f514228295](https://linux-hardware.org/?probe=f514228295) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| ASUSTek       | X441SA                      | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| HP            | Victus by Gaming Laptop ... | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3e5af3e86c](https://linux-hardware.org/?probe=3e5af3e86c) | Sep 25, 2022 |
| Alienware     | M14xR1                      | [a4064c0342](https://linux-hardware.org/?probe=a4064c0342) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | [3162a68bf5](https://linux-hardware.org/?probe=3162a68bf5) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | [d764e72d74](https://linux-hardware.org/?probe=d764e72d74) | Sep 12, 2022 |
| Alienware     | M14xR1                      | [ea2adf914b](https://linux-hardware.org/?probe=ea2adf914b) | Sep 10, 2022 |
| Acer          | Aspire 4349                 | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| Alienware     | M14xR1                      | [498d5f5254](https://linux-hardware.org/?probe=498d5f5254) | Aug 27, 2022 |
| Dell          | Inspiron 5459               | [398f6d4b78](https://linux-hardware.org/?probe=398f6d4b78) | Aug 25, 2022 |
| ASUSTek       | X556UF                      | [23316377ee](https://linux-hardware.org/?probe=23316377ee) | Aug 23, 2022 |
| ASUSTek       | X556UF                      | [9630e2d4f5](https://linux-hardware.org/?probe=9630e2d4f5) | Aug 21, 2022 |
| HP            | EliteBook 6930p             | [ee6cfb6de5](https://linux-hardware.org/?probe=ee6cfb6de5) | Aug 19, 2022 |
| ASUSTek       | X441SA                      | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [66a759db9c](https://linux-hardware.org/?probe=66a759db9c) | Aug 14, 2022 |
| Acer          | Peppy                       | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| GPD           | G1619-02                    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Dell          | Latitude 3410               | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Dell          | XPS 13 7390                 | [82b077a668](https://linux-hardware.org/?probe=82b077a668) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| HP            | Laptop 14s-dq2xxx           | [616a2b7524](https://linux-hardware.org/?probe=616a2b7524) | Jul 12, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| Dell          | Latitude 3420               | [71758de9e1](https://linux-hardware.org/?probe=71758de9e1) | Jul 06, 2022 |
| ASUSTek       | K401UQK                     | [5540b74d09](https://linux-hardware.org/?probe=5540b74d09) | Jul 03, 2022 |
| ASUSTek       | K401UQK                     | [c793608515](https://linux-hardware.org/?probe=c793608515) | Jul 03, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| Acer          | Aspire E5-475G              | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASUSTek       | K42Jc                       | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d525e0eb0c](https://linux-hardware.org/?probe=d525e0eb0c) | May 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [0a9f8b0a4a](https://linux-hardware.org/?probe=0a9f8b0a4a) | May 09, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| Acer          | Nitro AN515-45              | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| ILLEGEAR      | ROGUE                       | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Apple         | MacBookPro5,5               | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Dell          | Latitude D630               | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Dell          | Precision 7730              | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| Dell          | Inspiron 5537               | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | GT70 2OC/2OD                | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| Dell          | Latitude E6520              | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ASUSTek       | T200TA                      | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| Lenovo        | U310                        | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Acer          | Nitro AN515-45              | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| ASUSTek       | GL553VD                     | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| ASUSTek       | X556UR                      | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| ASUSTek       | X550LC                      | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| HP            | EliteBook 8470p             | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| HP            | Notebook                    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| Lenovo        | G400s VILG1                 | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| HP            | Notebook                    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Apple         | MacBookAir3,2               | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| HP            | Pavilion 14                 | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| HP            | EliteBook 8470p             | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| ASUSTek       | X556UR                      | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| Dell          | Inspiron 5548               | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| Dell          | Inspiron 3443               | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| HP            | Notebook                    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| HP            | Pavilion dv6                | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| HP            | Pavilion dv6                | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| ASUSTek       | K45VD                       | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [6bb8ea7872](https://linux-hardware.org/?probe=6bb8ea7872) | Apr 23, 2021 |
| System76      | Galago Pro                  | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Dell          | XPS L412Z                   | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| Sony          | VPCEA42EG                   | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| HP            | Pavilion dv6                | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Dell          | Latitude E6440              | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| HP            | G42                         | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| HP            | Notebook                    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| HP            | Pavilion g4                 | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| HP            | EliteBook 840 G2            | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| HP            | Laptop 15s-eq0xxx           | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| Dell          | XPS 15 7590                 | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Acer          | TM4750                      | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| Acer          | Aspire V3-571G              | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Sony          | VGN-Z27GN_X                 | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| HP            | Pavilion dv6                | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| HP            | Presario CQ43               | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7480               | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Fujitsu       | LIFEBOOK LH531              | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Fujitsu       | LIFEBOOK LH531              | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Dell          | XPS 15 7590                 | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| ILLEGEAR      | RAVEN SE                    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Acer          | Aspire 4738                 | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Dell          | Venue 11 Pro 5130           | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| ASUSTek       | G551JM                      | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| HP            | 14                          | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| HP            | EliteBook 8470p             | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| Sony          | VPCSB26FG                   | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| SNS Networ... | JOI Book 150                | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | 14                          | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| BUSH          | Windows tablet              | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| Acer          | TM4750                      | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Acer          | Aspire 4736Z                | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| HP            | ProBook 645 G1              | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| Apple         | MacBookPro8,2               | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Chuwi         | LapBook Pro                 | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Dell          | Vostro V130                 | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| Acer          | Swift SF314-55G             | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| HP            | ZBook 15                    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| MSI           | GP70 2PE                    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | X450CP                      | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| Dell          | XPS L521X                   | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| Dell          | XPS L412Z                   | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 29        | 13.49%  |
| Ubuntu 18.04        | 12        | 5.58%   |
| Ubuntu 22.04        | 11        | 5.12%   |
| Pop!_OS 20.10       | 8         | 3.72%   |
| KDE neon 20.04      | 7         | 3.26%   |
| Pop!_OS 21.04       | 6         | 2.79%   |
| OpenMandriva 4.2    | 5         | 2.33%   |
| OpenMandriva 23.01  | 5         | 2.33%   |
| ArcoLinux Rolling   | 5         | 2.33%   |
| Ubuntu 16.04        | 4         | 1.86%   |
| Pop!_OS 22.04       | 4         | 1.86%   |
| OpenMandriva 4.50   | 4         | 1.86%   |
| Fedora 33           | 4         | 1.86%   |
| EndeavourOS Rolling | 4         | 1.86%   |
| Zorin 16            | 3         | 1.4%    |
| Xubuntu 22.04       | 3         | 1.4%    |
| Ubuntu 21.04        | 3         | 1.4%    |
| Ubuntu 19.04        | 3         | 1.4%    |
| OpenMandriva 4.3    | 3         | 1.4%    |
| Manjaro             | 3         | 1.4%    |
| Linux Mint 21.1     | 3         | 1.4%    |
| Linux Mint 20.2     | 3         | 1.4%    |
| Linux Mint 19.3     | 3         | 1.4%    |
| Fedora 34           | 3         | 1.4%    |
| Debian 11           | 3         | 1.4%    |
| Arch Rolling        | 3         | 1.4%    |
| Arch                | 3         | 1.4%    |
| Zorin 15            | 2         | 0.93%   |
| Ubuntu Unity 16.04  | 2         | 0.93%   |
| Ubuntu 20.10        | 2         | 0.93%   |
| Ubuntu 19.10        | 2         | 0.93%   |
| Pop!_OS 20.04       | 2         | 0.93%   |
| Manjaro 21.0.7      | 2         | 0.93%   |
| Lubuntu 18.04       | 2         | 0.93%   |
| Linux Mint 20.1     | 2         | 0.93%   |
| Fedora 35           | 2         | 0.93%   |
| Elementary 5.1.7    | 2         | 0.93%   |
| CentOS 7            | 2         | 0.93%   |
| Zorin 12            | 1         | 0.47%   |
| Xubuntu 19.10       | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 66        | 32.04%  |
| Pop!_OS           | 19        | 9.22%   |
| OpenMandriva      | 17        | 8.25%   |
| Linux Mint        | 11        | 5.34%   |
| Fedora            | 10        | 4.85%   |
| Manjaro           | 8         | 3.88%   |
| KDE neon          | 8         | 3.88%   |
| Zorin             | 6         | 2.91%   |
| Arch              | 6         | 2.91%   |
| Endless           | 5         | 2.43%   |
| ArcoLinux         | 5         | 2.43%   |
| Xubuntu           | 4         | 1.94%   |
| EndeavourOS       | 4         | 1.94%   |
| Elementary        | 4         | 1.94%   |
| Debian            | 4         | 1.94%   |
| Lubuntu           | 3         | 1.46%   |
| Kubuntu           | 3         | 1.46%   |
| CentOS            | 3         | 1.46%   |
| Ubuntu Unity      | 2         | 0.97%   |
| Ubuntu Budgie     | 2         | 0.97%   |
| SteamOS           | 2         | 0.97%   |
| Kali              | 2         | 0.97%   |
| Xero              | 1         | 0.49%   |
| Ultramarine Linux | 1         | 0.49%   |
| Ubuntu MATE       | 1         | 0.49%   |
| ROSA              | 1         | 0.49%   |
| Rocky Linux       | 1         | 0.49%   |
| Reborn OS         | 1         | 0.49%   |
| Peppermint        | 1         | 0.49%   |
| MX                | 1         | 0.49%   |
| LMDE              | 1         | 0.49%   |
| Gentoo            | 1         | 0.49%   |
| BuildRoot         | 1         | 0.49%   |
| Archcraft         | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 5         | 2.17%   |
| 5.11.0-7620-generic      | 5         | 2.17%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.74%   |
| 5.0.0-37-generic         | 4         | 1.74%   |
| 5.8.0-7642-generic       | 3         | 1.3%    |
| 5.4.0-58-generic         | 3         | 1.3%    |
| 5.4.0-54-generic         | 3         | 1.3%    |
| 5.4.0-42-generic         | 3         | 1.3%    |
| 5.16.7-desktop-1omv4003  | 3         | 1.3%    |
| 5.15.0-56-generic        | 3         | 1.3%    |
| 5.15.0-52-generic        | 3         | 1.3%    |
| 5.12.4-desktop-1omv4050  | 3         | 1.3%    |
| 5.11.0-46-generic        | 3         | 1.3%    |
| 5.0.0-23-generic         | 3         | 1.3%    |
| 4.15.0-45-generic        | 3         | 1.3%    |
| 5.8.0-7630-generic       | 2         | 0.87%   |
| 5.8.0-45-generic         | 2         | 0.87%   |
| 5.4.0-89-generic         | 2         | 0.87%   |
| 5.4.0-64-generic         | 2         | 0.87%   |
| 5.4.0-52-generic         | 2         | 0.87%   |
| 5.3.0-51-generic         | 2         | 0.87%   |
| 5.19.0-76051900-generic  | 2         | 0.87%   |
| 5.17.5-76051705-generic  | 2         | 0.87%   |
| 5.17.1-051701-generic    | 2         | 0.87%   |
| 5.15.0-58-generic        | 2         | 0.87%   |
| 5.15.0-46-generic        | 2         | 0.87%   |
| 5.15.0-40-generic        | 2         | 0.87%   |
| 5.15.0-25-generic        | 2         | 0.87%   |
| 5.13.0-7614-generic      | 2         | 0.87%   |
| 5.13.0-22-generic        | 2         | 0.87%   |
| 5.11.0-7614-generic      | 2         | 0.87%   |
| 5.11.0-40-generic        | 2         | 0.87%   |
| 5.11.0-27-generic        | 2         | 0.87%   |
| 5.10.79-1-lts            | 2         | 0.87%   |
| 5.10.42-1-MANJARO        | 2         | 0.87%   |
| 5.10.13-200.fc33.x86_64  | 2         | 0.87%   |
| 5.10.0-13-amd64          | 2         | 0.87%   |
| 5.0.0-25-generic         | 2         | 0.87%   |
| 4.15.0-72-generic        | 2         | 0.87%   |
| 6.1.9-arch1-1            | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 13.64%  |
| 5.15.0  | 19        | 8.64%   |
| 5.11.0  | 17        | 7.73%   |
| 5.8.0   | 15        | 6.82%   |
| 5.13.0  | 12        | 5.45%   |
| 4.15.0  | 12        | 5.45%   |
| 5.0.0   | 10        | 4.55%   |
| 5.3.0   | 9         | 4.09%   |
| 6.1.1   | 6         | 2.73%   |
| 5.10.14 | 4         | 1.82%   |
| 5.10.0  | 4         | 1.82%   |
| 4.18.0  | 4         | 1.82%   |
| 5.19.0  | 3         | 1.36%   |
| 5.17.1  | 3         | 1.36%   |
| 5.16.7  | 3         | 1.36%   |
| 5.16.15 | 3         | 1.36%   |
| 5.12.4  | 3         | 1.36%   |
| 5.9.0   | 2         | 0.91%   |
| 5.18.0  | 2         | 0.91%   |
| 5.17.5  | 2         | 0.91%   |
| 5.12.9  | 2         | 0.91%   |
| 5.10.79 | 2         | 0.91%   |
| 5.10.42 | 2         | 0.91%   |
| 5.10.13 | 2         | 0.91%   |
| 4.4.0   | 2         | 0.91%   |
| 3.10.0  | 2         | 0.91%   |
| 6.1.9   | 1         | 0.45%   |
| 6.1.6   | 1         | 0.45%   |
| 6.1.4   | 1         | 0.45%   |
| 6.0.9   | 1         | 0.45%   |
| 6.0.0   | 1         | 0.45%   |
| 5.9.1   | 1         | 0.45%   |
| 5.8.8   | 1         | 0.45%   |
| 5.8.6   | 1         | 0.45%   |
| 5.8.4   | 1         | 0.45%   |
| 5.8.17  | 1         | 0.45%   |
| 5.8.16  | 1         | 0.45%   |
| 5.8.11  | 1         | 0.45%   |
| 5.8.10  | 1         | 0.45%   |
| 5.7.7   | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 13.89%  |
| 5.8     | 22        | 10.19%  |
| 5.15    | 22        | 10.19%  |
| 5.11    | 20        | 9.26%   |
| 5.10    | 17        | 7.87%   |
| 5.13    | 13        | 6.02%   |
| 4.15    | 12        | 5.56%   |
| 5.0     | 10        | 4.63%   |
| 5.3     | 9         | 4.17%   |
| 6.1     | 8         | 3.7%    |
| 5.12    | 7         | 3.24%   |
| 5.19    | 6         | 2.78%   |
| 5.17    | 6         | 2.78%   |
| 5.16    | 6         | 2.78%   |
| 5.18    | 5         | 2.31%   |
| 5.14    | 5         | 2.31%   |
| 4.18    | 4         | 1.85%   |
| 5.9     | 3         | 1.39%   |
| 6.0     | 2         | 0.93%   |
| 5.7     | 2         | 0.93%   |
| 4.4     | 2         | 0.93%   |
| 3.10    | 2         | 0.93%   |
| 5.6     | 1         | 0.46%   |
| 4.10    | 1         | 0.46%   |
| 4.1     | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 191       | 98.45%  |
| i686   | 3         | 1.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 92        | 44.88%  |
| KDE5          | 39        | 19.02%  |
| Unknown       | 22        | 10.73%  |
| XFCE          | 14        | 6.83%   |
| X-Cinnamon    | 10        | 4.88%   |
| KDE           | 8         | 3.9%    |
| Pantheon      | 4         | 1.95%   |
| MATE          | 4         | 1.95%   |
| Unity         | 2         | 0.98%   |
| Budgie        | 2         | 0.98%   |
| Peppermint    | 1         | 0.49%   |
| openbox       | 1         | 0.49%   |
| LXQt          | 1         | 0.49%   |
| LXDE          | 1         | 0.49%   |
| i3            | 1         | 0.49%   |
| Hyprland      | 1         | 0.49%   |
| GNOME Classic | 1         | 0.49%   |
| bspwm         | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 161       | 78.92%  |
| Wayland | 31        | 15.2%   |
| Unknown | 9         | 4.41%   |
| Tty     | 3         | 1.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 106       | 52.74%  |
| SDDM    | 37        | 18.41%  |
| GDM3    | 23        | 11.44%  |
| GDM     | 21        | 10.45%  |
| LightDM | 12        | 5.97%   |
| TDM     | 2         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 158       | 80.2%   |
| Unknown | 17        | 8.63%   |
| en_GB   | 10        | 5.08%   |
| en_SG   | 5         | 2.54%   |
| ms_MY   | 2         | 1.02%   |
| C       | 2         | 1.02%   |
| ja_JP   | 1         | 0.51%   |
| id_ID   | 1         | 0.51%   |
| en_MY   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 100       | 51.02%  |
| EFI  | 96        | 48.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 152       | 76.38%  |
| Overlay | 18        | 9.05%   |
| Btrfs   | 14        | 7.04%   |
| Xfs     | 5         | 2.51%   |
| Unknown | 5         | 2.51%   |
| Zfs     | 4         | 2.01%   |
| Ext2    | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 115       | 57.5%   |
| GPT     | 61        | 30.5%   |
| MBR     | 24        | 12%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 84.26%  |
| Yes       | 31        | 15.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 141       | 70.85%  |
| Yes       | 58        | 29.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 43        | 22.16%  |
| Hewlett-Packard     | 36        | 18.56%  |
| ASUSTek Computer    | 33        | 17.01%  |
| Lenovo              | 25        | 12.89%  |
| Acer                | 18        | 9.28%   |
| MSI                 | 6         | 3.09%   |
| Apple               | 5         | 2.58%   |
| Sony                | 4         | 2.06%   |
| Fujitsu             | 3         | 1.55%   |
| Samsung Electronics | 2         | 1.03%   |
| ILLEGEAR            | 2         | 1.03%   |
| HUAWEI              | 2         | 1.03%   |
| Unknown             | 2         | 1.03%   |
| Valve               | 1         | 0.52%   |
| Toshiba             | 1         | 0.52%   |
| Timi                | 1         | 0.52%   |
| System76            | 1         | 0.52%   |
| SNS Network (M)     | 1         | 0.52%   |
| NEC Computers       | 1         | 0.52%   |
| HONOR               | 1         | 0.52%   |
| GPD                 | 1         | 0.52%   |
| Gigabyte Technology | 1         | 0.52%   |
| Chuwi               | 1         | 0.52%   |
| BUSH                | 1         | 0.52%   |
| AZW                 | 1         | 0.52%   |
| Alienware           | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Notebook                         | 4         | 2.06%   |
| MSI Modern 14 B5M                   | 2         | 1.03%   |
| HP Pavilion dv6                     | 2         | 1.03%   |
| HP Laptop 15-bs0xx                  | 2         | 1.03%   |
| HP ENVY 4                           | 2         | 1.03%   |
| HP EliteBook 8470p                  | 2         | 1.03%   |
| HP EliteBook 840 G2                 | 2         | 1.03%   |
| HP Compaq Presario CQ40             | 2         | 1.03%   |
| Dell XPS 15 7590                    | 2         | 1.03%   |
| Dell Latitude E6520                 | 2         | 1.03%   |
| Dell Latitude E6440                 | 2         | 1.03%   |
| Dell Latitude 3410                  | 2         | 1.03%   |
| ASUS K45VD                          | 2         | 1.03%   |
| ASUS K43SD                          | 2         | 1.03%   |
| Apple MacBookPro8,1                 | 2         | 1.03%   |
| Unknown                             | 2         | 1.03%   |
| Valve Jupiter                       | 1         | 0.52%   |
| Toshiba dynabook Satellite B552/H   | 1         | 0.52%   |
| Timi RedmiBook 14 II                | 1         | 0.52%   |
| System76 Galago Pro                 | 1         | 0.52%   |
| Sony VPCSB26FG                      | 1         | 0.52%   |
| Sony VPCEG16EG                      | 1         | 0.52%   |
| Sony VPCEA42EG                      | 1         | 0.52%   |
| Sony VGN-Z27GN_X                    | 1         | 0.52%   |
| SNS Network (M) JOI Book 150        | 1         | 0.52%   |
| Samsung RV413/RV513                 | 1         | 0.52%   |
| Samsung 730U3E/740U3E               | 1         | 0.52%   |
| NEC Computers PC-VK27MXZCG          | 1         | 0.52%   |
| MSI Prestige 15 A10SC               | 1         | 0.52%   |
| MSI GT70 2OC/2OD                    | 1         | 0.52%   |
| MSI GP70 2PE                        | 1         | 0.52%   |
| MSI GL62M 7RDX                      | 1         | 0.52%   |
| Lenovo Yoga 500-15IBD 80N6          | 1         | 0.52%   |
| Lenovo Y520-15IKBN 80WK             | 1         | 0.52%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7 | 1         | 0.52%   |
| Lenovo U310                         | 1         | 0.52%   |
| Lenovo ThinkPad X220 42912WA        | 1         | 0.52%   |
| Lenovo ThinkPad X220 4286PJ2        | 1         | 0.52%   |
| Lenovo ThinkPad X201 3626RZ4        | 1         | 0.52%   |
| Lenovo ThinkPad X201 3323LWA        | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 18        | 9.28%   |
| Lenovo ThinkPad            | 15        | 7.73%   |
| Dell Inspiron              | 14        | 7.22%   |
| Acer Aspire                | 11        | 5.67%   |
| HP Pavilion                | 7         | 3.61%   |
| HP EliteBook               | 7         | 3.61%   |
| HP Laptop                  | 5         | 2.58%   |
| Dell XPS                   | 5         | 2.58%   |
| HP Notebook                | 4         | 2.06%   |
| HP Compaq                  | 4         | 2.06%   |
| Fujitsu LIFEBOOK           | 3         | 1.55%   |
| Dell Precision             | 3         | 1.55%   |
| ASUS VivoBook              | 3         | 1.55%   |
| ASUS ROG                   | 3         | 1.55%   |
| Apple MacBookPro8          | 3         | 1.55%   |
| MSI Modern                 | 2         | 1.03%   |
| Lenovo IdeaPad             | 2         | 1.03%   |
| HP ProBook                 | 2         | 1.03%   |
| HP ENVY                    | 2         | 1.03%   |
| ASUS K45VD                 | 2         | 1.03%   |
| ASUS K43SD                 | 2         | 1.03%   |
| Acer Nitro                 | 2         | 1.03%   |
| Unknown                    | 2         | 1.03%   |
| Valve Jupiter              | 1         | 0.52%   |
| Toshiba dynabook           | 1         | 0.52%   |
| Timi RedmiBook             | 1         | 0.52%   |
| System76 Galago            | 1         | 0.52%   |
| Sony VPCSB26FG             | 1         | 0.52%   |
| Sony VPCEG16EG             | 1         | 0.52%   |
| Sony VPCEA42EG             | 1         | 0.52%   |
| Sony VGN-Z27GN             | 1         | 0.52%   |
| SNS Network (M) JOI        | 1         | 0.52%   |
| Samsung RV413              | 1         | 0.52%   |
| Samsung 730U3E             | 1         | 0.52%   |
| NEC Computers PC-VK27MXZCG | 1         | 0.52%   |
| MSI Prestige               | 1         | 0.52%   |
| MSI GT70                   | 1         | 0.52%   |
| MSI GP70                   | 1         | 0.52%   |
| MSI GL62M                  | 1         | 0.52%   |
| Lenovo Yoga                | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 28        | 14.43%  |
| 2013 | 21        | 10.82%  |
| 2020 | 18        | 9.28%   |
| 2019 | 18        | 9.28%   |
| 2021 | 16        | 8.25%   |
| 2012 | 13        | 6.7%    |
| 2018 | 12        | 6.19%   |
| 2015 | 12        | 6.19%   |
| 2010 | 11        | 5.67%   |
| 2017 | 10        | 5.15%   |
| 2016 | 8         | 4.12%   |
| 2014 | 8         | 4.12%   |
| 2008 | 8         | 4.12%   |
| 2009 | 6         | 3.09%   |
| 2022 | 3         | 1.55%   |
| 2007 | 2         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 194       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 178       | 91.75%  |
| Enabled  | 16        | 8.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 192       | 98.97%  |
| Yes  | 2         | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 26.15%  |
| 3.01-4.0    | 50        | 25.64%  |
| 8.01-16.0   | 42        | 21.54%  |
| 16.01-24.0  | 27        | 13.85%  |
| 32.01-64.0  | 8         | 4.1%    |
| 1.01-2.0    | 7         | 3.59%   |
| 2.01-3.0    | 3         | 1.54%   |
| 64.01-256.0 | 3         | 1.54%   |
| 24.01-32.0  | 2         | 1.03%   |
| 0.51-1.0    | 2         | 1.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 76        | 35.19%  |
| 2.01-3.0  | 60        | 27.78%  |
| 3.01-4.0  | 33        | 15.28%  |
| 4.01-8.0  | 23        | 10.65%  |
| 0.51-1.0  | 17        | 7.87%   |
| 8.01-16.0 | 7         | 3.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 134       | 67.68%  |
| 2      | 55        | 27.78%  |
| 3      | 7         | 3.54%   |
| 4      | 2         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 121       | 62.37%  |
| Yes       | 73        | 37.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 85.57%  |
| No        | 28        | 14.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 96.91%  |
| No        | 6         | 3.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 83.08%  |
| No        | 33        | 16.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Malaysia | 194       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 72        | 34.62%  |
| Petaling Jaya          | 23        | 11.06%  |
| Johor Bahru            | 11        | 5.29%   |
| Shah Alam              | 10        | 4.81%   |
| Puchong Batu Dua Belas | 9         | 4.33%   |
| Ipoh                   | 7         | 3.37%   |
| Sungai Buloh           | 6         | 2.88%   |
| Subang Jaya            | 5         | 2.4%    |
| Kota Kinabalu          | 5         | 2.4%    |
| Skudai                 | 4         | 1.92%   |
| Seremban               | 4         | 1.92%   |
| Kota Bharu             | 4         | 1.92%   |
| Kajang                 | 4         | 1.92%   |
| Marabu                 | 3         | 1.44%   |
| Kulai                  | 3         | 1.44%   |
| Klang                  | 3         | 1.44%   |
| Cyberjaya              | 3         | 1.44%   |
| Tawau                  | 2         | 0.96%   |
| Sungai Petani          | 2         | 0.96%   |
| Nibong Tebal           | 2         | 0.96%   |
| Malacca                | 2         | 0.96%   |
| Kulim                  | 2         | 0.96%   |
| George Town            | 2         | 0.96%   |
| Cheras                 | 2         | 0.96%   |
| Seri Kembangan         | 1         | 0.48%   |
| Sepang                 | 1         | 0.48%   |
| Rawang                 | 1         | 0.48%   |
| Putrajaya              | 1         | 0.48%   |
| Pasir Gudang           | 1         | 0.48%   |
| Long Seridan           | 1         | 0.48%   |
| Kuching                | 1         | 0.48%   |
| Kuala Terengganu       | 1         | 0.48%   |
| Kuala Kangsar          | 1         | 0.48%   |
| Kota Tinggi            | 1         | 0.48%   |
| Kamunting              | 1         | 0.48%   |
| Jitra                  | 1         | 0.48%   |
| Hutan Melintang        | 1         | 0.48%   |
| Gambang                | 1         | 0.48%   |
| Butterworth            | 1         | 0.48%   |
| Bayan Lepas            | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 38        | 44     | 14.79%  |
| WDC                         | 25        | 32     | 9.73%   |
| Toshiba                     | 25        | 31     | 9.73%   |
| Samsung Electronics         | 23        | 31     | 8.95%   |
| Kingston                    | 20        | 23     | 7.78%   |
| SanDisk                     | 15        | 20     | 5.84%   |
| Unknown                     | 14        | 20     | 5.45%   |
| HGST                        | 14        | 17     | 5.45%   |
| SK hynix                    | 7         | 7      | 2.72%   |
| A-DATA Technology           | 7         | 7      | 2.72%   |
| Intel                       | 6         | 9      | 2.33%   |
| Hitachi                     | 6         | 11     | 2.33%   |
| Micron Technology           | 5         | 5      | 1.95%   |
| KIOXIA                      | 5         | 6      | 1.95%   |
| Transcend                   | 4         | 5      | 1.56%   |
| SPCC                        | 3         | 4      | 1.17%   |
| Phison                      | 3         | 5      | 1.17%   |
| Patriot                     | 3         | 4      | 1.17%   |
| China                       | 3         | 3      | 1.17%   |
| Apacer                      | 3         | 3      | 1.17%   |
| TO Exter                    | 2         | 2      | 0.78%   |
| Silicon Motion              | 2         | 2      | 0.78%   |
| Kingston Technology Company | 2         | 2      | 0.78%   |
| Fujitsu                     | 2         | 2      | 0.78%   |
| Crucial                     | 2         | 2      | 0.78%   |
| winstar                     | 1         | 1      | 0.39%   |
| Western Digital             | 1         | 1      | 0.39%   |
| Verbatim                    | 1         | 1      | 0.39%   |
| USB3.0                      | 1         | 1      | 0.39%   |
| PNY                         | 1         | 1      | 0.39%   |
| Netac                       | 1         | 1      | 0.39%   |
| Morebeck-S100               | 1         | 1      | 0.39%   |
| Micron/Crucial Technology   | 1         | 2      | 0.39%   |
| LS                          | 1         | 1      | 0.39%   |
| Kingchuxing                 | 1         | 1      | 0.39%   |
| JMicron Technology          | 1         | 1      | 0.39%   |
| Hewlett-Packard             | 1         | 1      | 0.39%   |
| Gigabyte Technology         | 1         | 1      | 0.39%   |
| Colorful                    | 1         | 1      | 0.39%   |
| ASMT                        | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB              | 5         | 1.9%    |
| Unknown MMC Card  32GB                  | 4         | 1.52%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.52%   |
| Toshiba MQ01ABD100 1TB                  | 4         | 1.52%   |
| Seagate ST500LT012-1DG142 500GB         | 4         | 1.52%   |
| SK hynix NVMe SSD Drive 512GB           | 3         | 1.14%   |
| Seagate ST9320325AS 320GB               | 3         | 1.14%   |
| Seagate ST1000LM048-2E7172 1TB          | 3         | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.14%   |
| SanDisk SSD PLUS 240GB                  | 3         | 1.14%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 1.14%   |
| HGST HTS725050A7E630 500GB              | 3         | 1.14%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 2         | 0.76%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.76%   |
| WDC PC SN730 NVMe 1024GB                | 2         | 0.76%   |
| Unknown MMC Card  64GB                  | 2         | 0.76%   |
| Unknown MMC Card  128GB                 | 2         | 0.76%   |
| Toshiba MK5065GSXF 500GB                | 2         | 0.76%   |
| TO Exter nal USB 3.0 1TB                | 2         | 0.76%   |
| Seagate ST9750420AS 752GB               | 2         | 0.76%   |
| Seagate ST9500325AS 500GB               | 2         | 0.76%   |
| Seagate ST500LM000-1EJ162 500GB         | 2         | 0.76%   |
| Seagate ST320LT020-9YG142 320GB         | 2         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.76%   |
| Samsung SSD 860 EVO 500GB               | 2         | 0.76%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.76%   |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.76%   |
| Micron 1100 SATA 512GB SSD              | 2         | 0.76%   |
| KIOXIA NVMe SSD Drive 256GB             | 2         | 0.76%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB | 2         | 0.76%   |
| Kingston SH103S3120G 120GB SSD          | 2         | 0.76%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 0.76%   |
| Intel SSD 660P Series 512GB             | 2         | 0.76%   |
| Intel NVMe SSD Drive 512GB              | 2         | 0.76%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 0.76%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.76%   |
| HGST HTS541010A9E680 1TB                | 2         | 0.76%   |
| Apacer AS340 120GB SSD                  | 2         | 0.76%   |
| A-DATA SU650 240GB SSD                  | 2         | 0.76%   |
| winstar 120GB                           | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 43     | 37%     |
| Toshiba             | 21        | 26     | 21%     |
| WDC                 | 16        | 23     | 16%     |
| HGST                | 14        | 17     | 14%     |
| Hitachi             | 6         | 11     | 6%      |
| Fujitsu             | 2         | 2      | 2%      |
| USB3.0              | 1         | 1      | 1%      |
| Unknown             | 1         | 1      | 1%      |
| Samsung Electronics | 1         | 3      | 1%      |
| ASMT                | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 17     | 20%     |
| Samsung Electronics | 13        | 19     | 16.25%  |
| SanDisk             | 8         | 8      | 10%     |
| A-DATA Technology   | 5         | 5      | 6.25%   |
| Transcend           | 4         | 4      | 5%      |
| WDC                 | 3         | 3      | 3.75%   |
| SPCC                | 3         | 4      | 3.75%   |
| Patriot             | 3         | 4      | 3.75%   |
| Micron Technology   | 3         | 3      | 3.75%   |
| China               | 3         | 3      | 3.75%   |
| Apacer              | 3         | 3      | 3.75%   |
| TO Exter            | 2         | 2      | 2.5%    |
| Intel               | 2         | 2      | 2.5%    |
| Crucial             | 2         | 2      | 2.5%    |
| Verbatim            | 1         | 1      | 1.25%   |
| Toshiba             | 1         | 1      | 1.25%   |
| PNY                 | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| LS                  | 1         | 1      | 1.25%   |
| JMicron Technology  | 1         | 1      | 1.25%   |
| Gigabyte Technology | 1         | 1      | 1.25%   |
| Colorful            | 1         | 1      | 1.25%   |
| Apple               | 1         | 2      | 1.25%   |
| Unknown             | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 95        | 128    | 40.43%  |
| SSD     | 71        | 90     | 30.21%  |
| NVMe    | 51        | 75     | 21.7%   |
| MMC     | 13        | 19     | 5.53%   |
| Unknown | 5         | 6      | 2.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 150       | 214    | 66.96%  |
| NVMe | 51        | 75     | 22.77%  |
| MMC  | 13        | 19     | 5.8%    |
| SAS  | 10        | 10     | 4.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 114       | 149    | 68.67%  |
| 0.51-1.0   | 50        | 67     | 30.12%  |
| 1.01-2.0   | 2         | 2      | 1.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 61        | 29.05%  |
| 101-250        | 57        | 27.14%  |
| 501-1000       | 26        | 12.38%  |
| 1-20           | 23        | 10.95%  |
| 51-100         | 15        | 7.14%   |
| 21-50          | 12        | 5.71%   |
| 1001-2000      | 7         | 3.33%   |
| Unknown        | 5         | 2.38%   |
| More than 3000 | 2         | 0.95%   |
| 2001-3000      | 2         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 95        | 44.6%   |
| 21-50     | 40        | 18.78%  |
| 101-250   | 27        | 12.68%  |
| 51-100    | 19        | 8.92%   |
| 251-500   | 17        | 7.98%   |
| 501-1000  | 6         | 2.82%   |
| Unknown   | 5         | 2.35%   |
| 1001-2000 | 2         | 0.94%   |
| 2001-3000 | 1         | 0.47%   |
| 0         | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                      | 2         | 2      | 9.09%   |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4.55%   |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 4.55%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4.55%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 4.55%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 4.55%   |
| Toshiba MK1059GSMP 1TB                         | 1         | 1      | 4.55%   |
| SPCC Solid State Disk 256GB                    | 1         | 1      | 4.55%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 4.55%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 4.55%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB    | 1         | 1      | 4.55%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 2      | 4.55%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 4.55%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 4.55%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 3      | 4.55%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 4.55%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 4.55%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 4.55%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 4.55%   |
| Unknown                                        | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 4         | 4      | 18.18%  |
| Seagate                   | 4         | 4      | 18.18%  |
| Toshiba                   | 3         | 3      | 13.64%  |
| Hitachi                   | 3         | 5      | 13.64%  |
| HGST                      | 3         | 3      | 13.64%  |
| SPCC                      | 1         | 1      | 4.55%   |
| Samsung Electronics       | 1         | 1      | 4.55%   |
| Micron/Crucial Technology | 1         | 2      | 4.55%   |
| Micron Technology         | 1         | 1      | 4.55%   |
| Unknown                   | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 25%     |
| WDC     | 3         | 3      | 18.75%  |
| Toshiba | 3         | 3      | 18.75%  |
| Hitachi | 3         | 5      | 18.75%  |
| HGST    | 3         | 3      | 18.75%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 71.43%  |
| SSD  | 5         | 5      | 23.81%  |
| NVMe | 1         | 2      | 4.76%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 127       | 203    | 59.91%  |
| Works    | 65        | 90     | 30.66%  |
| Malfunc  | 20        | 25     | 9.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 142       | 63.96%  |
| AMD                          | 20        | 9.01%   |
| SanDisk                      | 13        | 5.86%   |
| Samsung Electronics          | 9         | 4.05%   |
| SK hynix                     | 7         | 3.15%   |
| Kingston Technology Company  | 6         | 2.7%    |
| Silicon Motion               | 5         | 2.25%   |
| KIOXIA                       | 5         | 2.25%   |
| Toshiba America Info Systems | 3         | 1.35%   |
| Phison Electronics           | 3         | 1.35%   |
| Nvidia                       | 3         | 1.35%   |
| Micron Technology            | 2         | 0.9%    |
| Micron/Crucial Technology    | 1         | 0.45%   |
| Biwin Storage Technology     | 1         | 0.45%   |
| ASMedia Technology           | 1         | 0.45%   |
| ADATA Technology             | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 9.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 7.63%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 18        | 7.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 6.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 6.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.54%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.54%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 2.12%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 2.12%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 4         | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.69%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.69%   |
| Intel SSD 660P Series                                                            | 4         | 1.69%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 1.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 1.27%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.85%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.85%   |
| Micron NVMe Storage Controller                                                   | 2         | 0.85%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.85%   |
| Kingston Company KC2000 NVMe SSD                                                 | 2         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.85%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.85%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 138       | 63.01%  |
| NVMe | 51        | 23.29%  |
| RAID | 20        | 9.13%   |
| IDE  | 10        | 4.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 158       | 81.44%  |
| AMD    | 36        | 18.56%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 4.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 2.05%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 2.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.54%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.03%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 1.03%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.03%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.03%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.03%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.03%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.03%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.03%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 2         | 1.03%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.03%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 1.03%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 1.03%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 1.03%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.03%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.03%   |
| AMD Athlon Silver 3050U with Radeon Graphics  | 2         | 1.03%   |
| AMD A6-5350M APU with Radeon HD Graphics      | 2         | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 59        | 30.26%  |
| Intel Core i7           | 42        | 21.54%  |
| Intel Core i3           | 16        | 8.21%   |
| AMD Ryzen 5             | 12        | 6.15%   |
| Intel Core 2 Duo        | 10        | 5.13%   |
| Intel Celeron           | 10        | 5.13%   |
| Other                   | 9         | 4.62%   |
| Intel Atom              | 5         | 2.56%   |
| AMD Ryzen 7             | 5         | 2.56%   |
| Intel Pentium Dual-Core | 3         | 1.54%   |
| Intel Pentium           | 3         | 1.54%   |
| AMD Athlon              | 3         | 1.54%   |
| AMD A6                  | 3         | 1.54%   |
| AMD Ryzen 9             | 2         | 1.03%   |
| AMD Ryzen 7 PRO         | 2         | 1.03%   |
| AMD E                   | 2         | 1.03%   |
| AMD A4                  | 2         | 1.03%   |
| AMD A12                 | 2         | 1.03%   |
| Intel Xeon              | 1         | 0.51%   |
| Intel Genuine           | 1         | 0.51%   |
| Intel Core i9           | 1         | 0.51%   |
| AMD FX                  | 1         | 0.51%   |
| AMD A10                 | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 108       | 55.67%  |
| 4      | 52        | 26.8%   |
| 6      | 18        | 9.28%   |
| 8      | 10        | 5.15%   |
| 1      | 5         | 2.58%   |
| 14     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 194       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 156       | 80%     |
| 1      | 39        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 192       | 98.46%  |
| Unknown        | 3         | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 21.39%  |
| 0x206a7    | 20        | 9.95%   |
| 0x306a9    | 15        | 7.46%   |
| 0x906ea    | 8         | 3.98%   |
| 0x40651    | 8         | 3.98%   |
| 0x306d4    | 7         | 3.48%   |
| 0x306c3    | 7         | 3.48%   |
| 0x806e9    | 6         | 2.99%   |
| 0x406e3    | 6         | 2.99%   |
| 0x20655    | 6         | 2.99%   |
| 0x1067a    | 5         | 2.49%   |
| 0xa0652    | 4         | 1.99%   |
| 0x20652    | 4         | 1.99%   |
| 0x08600104 | 4         | 1.99%   |
| 0x06001119 | 4         | 1.99%   |
| 0x806ec    | 3         | 1.49%   |
| 0x806eb    | 3         | 1.49%   |
| 0x806ea    | 3         | 1.49%   |
| 0x806c1    | 3         | 1.49%   |
| 0x30678    | 3         | 1.49%   |
| 0x906e9    | 2         | 1%      |
| 0x806d1    | 2         | 1%      |
| 0x706e5    | 2         | 1%      |
| 0x706a1    | 2         | 1%      |
| 0x406c4    | 2         | 1%      |
| 0x106ca    | 2         | 1%      |
| 0x10676    | 2         | 1%      |
| 0x0a50000b | 2         | 1%      |
| 0x08608103 | 2         | 1%      |
| 0x08108109 | 2         | 1%      |
| 0x08108102 | 2         | 1%      |
| 0x0700010f | 2         | 1%      |
| 0xa0660    | 1         | 0.5%    |
| 0x906a3    | 1         | 0.5%    |
| 0x706a8    | 1         | 0.5%    |
| 0x6fd      | 1         | 0.5%    |
| 0x6fb      | 1         | 0.5%    |
| 0x406c3    | 1         | 0.5%    |
| 0x0a50000d | 1         | 0.5%    |
| 0x0a50000c | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 29        | 14.95%  |
| SandyBridge      | 27        | 13.92%  |
| IvyBridge        | 19        | 9.79%   |
| Haswell          | 16        | 8.25%   |
| Penryn           | 11        | 5.67%   |
| Westmere         | 10        | 5.15%   |
| Skylake          | 9         | 4.64%   |
| Zen+             | 8         | 4.12%   |
| Silvermont       | 7         | 3.61%   |
| Broadwell        | 7         | 3.61%   |
| Zen 3            | 6         | 3.09%   |
| Zen 2            | 6         | 3.09%   |
| TigerLake        | 5         | 2.58%   |
| CometLake        | 5         | 2.58%   |
| Piledriver       | 4         | 2.06%   |
| IceLake          | 4         | 2.06%   |
| Goldmont plus    | 3         | 1.55%   |
| Core             | 3         | 1.55%   |
| Unknown          | 3         | 1.55%   |
| Jaguar           | 2         | 1.03%   |
| Excavator        | 2         | 1.03%   |
| Bonnell          | 2         | 1.03%   |
| Bobcat           | 2         | 1.03%   |
| Zen              | 1         | 0.52%   |
| Steamroller      | 1         | 0.52%   |
| K8 & K10 hybrid  | 1         | 0.52%   |
| Alderlake Hybrid | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 149       | 55.19%  |
| Nvidia | 66        | 24.44%  |
| AMD    | 55        | 20.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 9.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 6.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 3.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 3.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 3.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.24%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 2.52%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.52%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.16%   |
| Intel HD Graphics 620                                                                    | 6         | 2.16%   |
| AMD Renoir                                                                               | 6         | 2.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.44%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.44%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.08%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.08%   |
| Intel HD Graphics 630                                                                    | 3         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.08%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.72%   |
| Nvidia GM108M [GeForce 930M]                                                             | 2         | 0.72%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.72%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.72%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.72%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.72%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.72%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 79        | 40.51%  |
| Intel + Nvidia | 53        | 27.18%  |
| 1 x AMD        | 26        | 13.33%  |
| Intel + AMD    | 17        | 8.72%   |
| 2 x AMD        | 7         | 3.59%   |
| 1 x Nvidia     | 7         | 3.59%   |
| AMD + Nvidia   | 6         | 3.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 156       | 79.19%  |
| Proprietary | 39        | 19.8%   |
| Unknown     | 2         | 1.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 56.06%  |
| 1.01-2.0   | 34        | 17.17%  |
| 0.01-0.5   | 21        | 10.61%  |
| 3.01-4.0   | 17        | 8.59%   |
| 0.51-1.0   | 12        | 6.06%   |
| 7.01-8.0   | 2         | 1.01%   |
| 5.01-6.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 21%     |
| Chimei Innolux          | 35        | 15.98%  |
| LG Display              | 30        | 13.7%   |
| BOE                     | 26        | 11.87%  |
| Samsung Electronics     | 23        | 10.5%   |
| Dell                    | 9         | 4.11%   |
| Sharp                   | 7         | 3.2%    |
| Chi Mei Optoelectronics | 4         | 1.83%   |
| Apple                   | 4         | 1.83%   |
| Acer                    | 4         | 1.83%   |
| Lenovo                  | 3         | 1.37%   |
| Hewlett-Packard         | 3         | 1.37%   |
| PANDA                   | 2         | 0.91%   |
| InnoLux Display         | 2         | 0.91%   |
| AOC                     | 2         | 0.91%   |
| Xiaomi                  | 1         | 0.46%   |
| ViewSonic               | 1         | 0.46%   |
| Valve                   | 1         | 0.46%   |
| Unknown                 | 1         | 0.46%   |
| TRI                     | 1         | 0.46%   |
| Toshiba                 | 1         | 0.46%   |
| Sony                    | 1         | 0.46%   |
| Philips                 | 1         | 0.46%   |
| Panasonic               | 1         | 0.46%   |
| MStar                   | 1         | 0.46%   |
| MSI                     | 1         | 0.46%   |
| LTM                     | 1         | 0.46%   |
| LG Philips              | 1         | 0.46%   |
| InfoVision              | 1         | 0.46%   |
| Goldstar                | 1         | 0.46%   |
| EXP                     | 1         | 0.46%   |
| BenQ                    | 1         | 0.46%   |
| Armaggeddon             | 1         | 0.46%   |
| Ancor Communications    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 1.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 1.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.91%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.91%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.91%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 2         | 0.91%   |
| Acer ET241Y ACR056C 1920x1080 527x296mm 23.8-inch                         | 2         | 0.91%   |
| Xiaomi Mi TV XMD00E1 1360x768 708x398mm 32.0-inch                         | 1         | 0.46%   |
| ViewSonic V3D231 Series VSC4C29 1920x1080 510x290mm 23.1-inch             | 1         | 0.46%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 1         | 0.46%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1600x900               | 1         | 0.46%   |
| TRI TRI2400 TRI2400 1920x1080 530x300mm 24.0-inch                         | 1         | 0.46%   |
| Toshiba TV TSB010B 1920x1080 706x398mm 31.9-inch                          | 1         | 0.46%   |
| Sony TV SNY0902 1360x768                                                  | 1         | 0.46%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 1         | 0.46%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                   | 1         | 0.46%   |
| Sharp LCD SHP10C9 1920x540                                                | 1         | 0.46%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                   | 1         | 0.46%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.46%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 1         | 0.46%   |
| Sharp HDMI SHP10A1 1360x768 700x390mm 31.5-inch                           | 1         | 0.46%   |
| Samsung Electronics S24R35xFZ SAM71A8 1920x1080 527x296mm 23.8-inch       | 1         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 91        | 43.75%  |
| 1920x1080 (FHD)   | 79        | 37.98%  |
| 1280x800 (WXGA)   | 9         | 4.33%   |
| 1600x900 (HD+)    | 7         | 3.37%   |
| 3840x2160 (4K)    | 5         | 2.4%    |
| 2560x1440 (QHD)   | 4         | 1.92%   |
| 2160x1440         | 2         | 0.96%   |
| 1920x1200 (WUXGA) | 2         | 0.96%   |
| 1024x768 (XGA)    | 2         | 0.96%   |
| 800x1280          | 1         | 0.48%   |
| 2560x1080         | 1         | 0.48%   |
| 2240x1400         | 1         | 0.48%   |
| 1920x540          | 1         | 0.48%   |
| 1440x900 (WXGA+)  | 1         | 0.48%   |
| 1360x768          | 1         | 0.48%   |
| 1024x600          | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 73        | 33.33%  |
| 14      | 49        | 22.37%  |
| 13      | 35        | 15.98%  |
| 23      | 12        | 5.48%   |
| 24      | 7         | 3.2%    |
| 17      | 7         | 3.2%    |
| 12      | 6         | 2.74%   |
| 11      | 5         | 2.28%   |
| 27      | 4         | 1.83%   |
| 72      | 2         | 0.91%   |
| 52      | 2         | 0.91%   |
| 31      | 2         | 0.91%   |
| 21      | 2         | 0.91%   |
| 7       | 2         | 0.91%   |
| Unknown | 2         | 0.91%   |
| 84      | 1         | 0.46%   |
| 65      | 1         | 0.46%   |
| 32      | 1         | 0.46%   |
| 28      | 1         | 0.46%   |
| 25      | 1         | 0.46%   |
| 19      | 1         | 0.46%   |
| 18      | 1         | 0.46%   |
| 16      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 145       | 66.21%  |
| 501-600     | 22        | 10.05%  |
| 201-300     | 22        | 10.05%  |
| 351-400     | 10        | 4.57%   |
| 401-500     | 5         | 2.28%   |
| 601-700     | 4         | 1.83%   |
| 1501-2000   | 3         | 1.37%   |
| 1001-1500   | 3         | 1.37%   |
| Unknown     | 2         | 0.91%   |
| 701-800     | 1         | 0.46%   |
| 101-200     | 1         | 0.46%   |
| 1-100       | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 165       | 88.24%  |
| 16/10   | 12        | 6.42%   |
| 3/2     | 4         | 2.14%   |
| 4/3     | 1         | 0.53%   |
| 32/9    | 1         | 0.53%   |
| 21/9    | 1         | 0.53%   |
| 1.00    | 1         | 0.53%   |
| 0.67    | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 77        | 35.16%  |
| 101-110        | 74        | 33.79%  |
| 201-250        | 19        | 8.68%   |
| 71-80          | 7         | 3.2%    |
| 121-130        | 7         | 3.2%    |
| More than 1000 | 6         | 2.74%   |
| 61-70          | 6         | 2.74%   |
| 51-60          | 5         | 2.28%   |
| 301-350        | 4         | 1.83%   |
| 351-500        | 3         | 1.37%   |
| 251-300        | 3         | 1.37%   |
| 1-40           | 2         | 0.91%   |
| 151-200        | 2         | 0.91%   |
| Unknown        | 2         | 0.91%   |
| 41-50          | 1         | 0.46%   |
| 141-150        | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 88        | 40.74%  |
| 121-160       | 78        | 36.11%  |
| 51-100        | 34        | 15.74%  |
| 161-240       | 8         | 3.7%    |
| 1-50          | 5         | 2.31%   |
| Unknown       | 2         | 0.93%   |
| More than 240 | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 156       | 79.19%  |
| 2     | 38        | 19.29%  |
| 0     | 3         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 109       | 33.23%  |
| Intel                           | 95        | 28.96%  |
| Qualcomm Atheros                | 60        | 18.29%  |
| Broadcom                        | 19        | 5.79%   |
| MediaTek                        | 6         | 1.83%   |
| TP-Link                         | 5         | 1.52%   |
| Ralink Technology               | 5         | 1.52%   |
| Ralink                          | 4         | 1.22%   |
| Broadcom Limited                | 4         | 1.22%   |
| Xiaomi                          | 3         | 0.91%   |
| Huawei Technologies             | 3         | 0.91%   |
| ASIX Electronics                | 3         | 0.91%   |
| Nvidia                          | 2         | 0.61%   |
| Qualcomm Atheros Communications | 1         | 0.3%    |
| OPPO Electronics                | 1         | 0.3%    |
| Marvell Technology Group        | 1         | 0.3%    |
| JMicron Technology              | 1         | 0.3%    |
| InterBiometrics                 | 1         | 0.3%    |
| Hewlett-Packard                 | 1         | 0.3%    |
| DisplayLink                     | 1         | 0.3%    |
| D-Link                          | 1         | 0.3%    |
| Attansic Technology             | 1         | 0.3%    |
| ASUSTek Computer                | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 17.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 5.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 3.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6         | 1.56%   |
| Intel Wireless 7265                                               | 6         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.3%    |
| Intel Centrino Wireless-N 2230                                    | 5         | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.04%   |
| Intel Wireless 3160                                               | 4         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.04%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.04%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.04%   |
| TP-Link 802.11n NIC                                               | 3         | 0.78%   |
| Realtek 802.11ac NIC                                              | 3         | 0.78%   |
| Intel Wireless-AC 9260                                            | 3         | 0.78%   |
| Intel Wireless 7260                                               | 3         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.78%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.78%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.78%   |
| Huawei ANA-NX9                                                    | 3         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 0.78%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 43.2%   |
| Qualcomm Atheros                | 50        | 24.27%  |
| Realtek Semiconductor           | 27        | 13.11%  |
| Broadcom                        | 14        | 6.8%    |
| MediaTek                        | 6         | 2.91%   |
| TP-Link                         | 5         | 2.43%   |
| Ralink Technology               | 5         | 2.43%   |
| Ralink                          | 4         | 1.94%   |
| Broadcom Limited                | 3         | 1.46%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| D-Link                          | 1         | 0.49%   |
| ASUSTek Computer                | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 5.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 5.29%   |
| Intel Wi-Fi 6 AX200                                            | 11        | 5.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.85%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 2.88%   |
| Intel Wireless 7265                                            | 6         | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.4%    |
| Intel Centrino Wireless-N 2230                                 | 5         | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 1.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.92%   |
| Intel Wireless 3160                                            | 4         | 1.92%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.92%   |
| TP-Link 802.11n NIC                                            | 3         | 1.44%   |
| Realtek 802.11ac NIC                                           | 3         | 1.44%   |
| Intel Wireless-AC 9260                                         | 3         | 1.44%   |
| Intel Wireless 7260                                            | 3         | 1.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.44%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.44%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.44%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.44%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.96%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.96%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.96%   |
| Intel Wireless 3165                                            | 2         | 0.96%   |
| Intel WiFi Link 5100                                           | 2         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 96        | 55.49%  |
| Intel                    | 37        | 21.39%  |
| Qualcomm Atheros         | 15        | 8.67%   |
| Broadcom                 | 8         | 4.62%   |
| Xiaomi                   | 3         | 1.73%   |
| Huawei Technologies      | 3         | 1.73%   |
| ASIX Electronics         | 3         | 1.73%   |
| Nvidia                   | 2         | 1.16%   |
| OPPO Electronics         | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| DisplayLink              | 1         | 0.58%   |
| Broadcom Limited         | 1         | 0.58%   |
| Attansic Technology      | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 67        | 38.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 12.57%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 6.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.29%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 2.29%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.29%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 2.29%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.71%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.71%   |
| Huawei ANA-NX9                                                                 | 3         | 1.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 1.14%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.14%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.14%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.57%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.57%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.57%   |
| OPPO RMX3263                                                                   | 1         | 0.57%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.57%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.57%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 0.57%   |
| Intel Ethernet Connection (14) I219-V                                          | 1         | 0.57%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.57%   |
| Intel Centrino Advanced-N + WiMAX 6250                                         | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 188       | 52.81%  |
| Ethernet | 166       | 46.63%  |
| Modem    | 2         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 157       | 78.5%   |
| Ethernet | 43        | 21.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 78.35%  |
| 1     | 37        | 19.07%  |
| 0     | 4         | 2.06%   |
| 3     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 138       | 68.66%  |
| Yes  | 63        | 31.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 38.79%  |
| Qualcomm Atheros Communications | 15        | 9.09%   |
| Realtek Semiconductor           | 14        | 8.48%   |
| IMC Networks                    | 13        | 7.88%   |
| Foxconn / Hon Hai               | 11        | 6.67%   |
| Broadcom                        | 11        | 6.67%   |
| Lite-On Technology              | 10        | 6.06%   |
| Dell                            | 5         | 3.03%   |
| Apple                           | 5         | 3.03%   |
| Hewlett-Packard                 | 4         | 2.42%   |
| Realtek                         | 3         | 1.82%   |
| Ralink                          | 2         | 1.21%   |
| MediaTek                        | 2         | 1.21%   |
| Cambridge Silicon Radio         | 2         | 1.21%   |
| Ralink Technology               | 1         | 0.61%   |
| ASUSTek Computer                | 1         | 0.61%   |
| Askey Computer                  | 1         | 0.61%   |
| Alps Electric                   | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 13.33%  |
| Intel AX200 Bluetooth                                                               | 11        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 4.85%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 4.24%   |
| Intel AX201 Bluetooth                                                               | 7         | 4.24%   |
| Realtek Bluetooth Radio                                                             | 6         | 3.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.42%   |
| IMC Networks Bluetooth Device                                                       | 4         | 2.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 2.42%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.42%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.42%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.42%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.82%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.82%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.82%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.82%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.21%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.21%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.21%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.21%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.21%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.21%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.21%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.21%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 1.21%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.21%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.21%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.61%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.61%   |
| Ralink CSR BS8510                                                                   | 1         | 0.61%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.61%   |
| MediaTek Wireless_Device                                                            | 1         | 0.61%   |
| MediaTek BT                                                                         | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 153       | 65.95%  |
| AMD                    | 38        | 16.38%  |
| Nvidia                 | 28        | 12.07%  |
| C-Media Electronics    | 3         | 1.29%   |
| Samsung Electronics    | 2         | 0.86%   |
| Realtek Semiconductor  | 2         | 0.86%   |
| RODE Microphones       | 1         | 0.43%   |
| Plantronics            | 1         | 0.43%   |
| MVSILICON.INC.         | 1         | 0.43%   |
| MosArt Semiconductor   | 1         | 0.43%   |
| Generalplus Technology | 1         | 0.43%   |
| Cambridge Audio        | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 8.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 7.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 7.69%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 6.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 4.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 3.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.15%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.45%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.45%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.4%    |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.05%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.7%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 28.03%  |
| Kingston            | 30        | 22.73%  |
| SK hynix            | 25        | 18.94%  |
| Micron Technology   | 10        | 7.58%   |
| Nanya Technology    | 7         | 5.3%    |
| A-DATA Technology   | 5         | 3.79%   |
| Ramaxel Technology  | 4         | 3.03%   |
| Apacer              | 4         | 3.03%   |
| Unknown             | 2         | 1.52%   |
| Elpida              | 2         | 1.52%   |
| Crucial             | 2         | 1.52%   |
| Unknown (ABCD)      | 1         | 0.76%   |
| Team                | 1         | 0.76%   |
| Silicon Power       | 1         | 0.76%   |
| Kingmax             | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.92%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.19%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 2.19%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.46%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 1.46%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.46%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.46%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.46%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.46%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 1.46%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.46%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.73%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.73%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.73%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.73%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT325S6EFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.73%   |
| SK hynix RAM HMT112S6TFR8C-H9 1024MB SODIMM DDR3 1333MT/s        | 1         | 0.73%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.73%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.73%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.73%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 49        | 49.49%  |
| DDR4   | 40        | 40.4%   |
| LPDDR3 | 3         | 3.03%   |
| SDRAM  | 2         | 2.02%   |
| DDR2   | 2         | 2.02%   |
| LPDDR4 | 1         | 1.01%   |
| DDR5   | 1         | 1.01%   |
| DDR    | 1         | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 95.92%  |
| Row Of Chips | 4         | 4.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 50        | 43.86%  |
| 8192  | 32        | 28.07%  |
| 2048  | 13        | 11.4%   |
| 16384 | 11        | 9.65%   |
| 32768 | 4         | 3.51%   |
| 1024  | 4         | 3.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 25.89%  |
| 2667    | 19        | 16.96%  |
| 3200    | 16        | 14.29%  |
| 1334    | 15        | 13.39%  |
| 2400    | 7         | 6.25%   |
| 1333    | 7         | 6.25%   |
| 2133    | 6         | 5.36%   |
| 1067    | 3         | 2.68%   |
| 4199    | 2         | 1.79%   |
| 800     | 2         | 1.79%   |
| 667     | 2         | 1.79%   |
| 4800    | 1         | 0.89%   |
| 3266    | 1         | 0.89%   |
| 2134    | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson L210 Series    | 1         | 25%     |
| Seiko Epson ET-2710 Series | 1         | 25%     |
| Canon E410 series          | 1         | 25%     |
| Brother DCP-1510           | 1         | 25%     |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 19.64%  |
| Microdia                               | 23        | 13.69%  |
| IMC Networks                           | 17        | 10.12%  |
| Realtek Semiconductor                  | 14        | 8.33%   |
| Sunplus Innovation Technology          | 13        | 7.74%   |
| Suyin                                  | 11        | 6.55%   |
| Acer                                   | 10        | 5.95%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.17%   |
| Quanta                                 | 5         | 2.98%   |
| Apple                                  | 5         | 2.98%   |
| Alcor Micro                            | 4         | 2.38%   |
| Syntek                                 | 3         | 1.79%   |
| Luxvisions Innotech Limited            | 3         | 1.79%   |
| Silicon Motion                         | 2         | 1.19%   |
| Logitech                               | 2         | 1.19%   |
| Lite-On Technology                     | 2         | 1.19%   |
| Generalplus Technology                 | 2         | 1.19%   |
| Z-Star Microelectronics                | 1         | 0.6%    |
| YGTek                                  | 1         | 0.6%    |
| USB Camera                             | 1         | 0.6%    |
| Sonix Technology                       | 1         | 0.6%    |
| Samsung Electronics                    | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Primax Electronics                     | 1         | 0.6%    |
| OmniVision Technologies                | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| eMPIA Technology                       | 1         | 0.6%    |
| Cubeternet                             | 1         | 0.6%    |
| Bison Electronics                      | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 10        | 5.95%   |
| Chicony USB2.0 VGA UVC WebCam                           | 7         | 4.17%   |
| Chicony HD WebCam                                       | 5         | 2.98%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 2.38%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 2.38%   |
| Chicony Integrated Camera                               | 4         | 2.38%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 1.79%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.79%   |
| Chicony HP HD Webcam                                    | 3         | 1.79%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.79%   |
| Apple FaceTime HD Camera                                | 3         | 1.79%   |
| Acer Lenovo Integrated Webcam                           | 3         | 1.79%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 1.19%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 1.19%   |
| Suyin 1.3M HD WebCam                                    | 2         | 1.19%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.19%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.19%   |
| Realtek USB Camera                                      | 2         | 1.19%   |
| Realtek HD WebCam                                       | 2         | 1.19%   |
| Quanta HP TrueVision HD Camera                          | 2         | 1.19%   |
| Microdia USB 2.0 Camera                                 | 2         | 1.19%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.19%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.19%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 1.19%   |
| IMC Networks Integrated Camera                          | 2         | 1.19%   |
| IMC Networks HD Camera                                  | 2         | 1.19%   |
| Generalplus GENERAL WEBCAM                              | 2         | 1.19%   |
| Alcor Micro Asus Integrated Webcam                      | 2         | 1.19%   |
| Acer Integrated Camera                                  | 2         | 1.19%   |
| Acer BisonCam,NB Pro                                    | 2         | 1.19%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.6%    |
| YGTek Webcam                                            | 1         | 0.6%    |
| USB Camera USB Camera                                   | 1         | 0.6%    |
| Syntek USB Camera Device                                | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                                | 1         | 0.6%    |
| Syntek Laptop_Integrated_Webcam_1.3M                    | 1         | 0.6%    |
| Suyin WebCam                                            | 1         | 0.6%    |
| Suyin Integrated Webcam                                 | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 25%     |
| Synaptics                  | 6         | 21.43%  |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| Elan Microelectronics      | 3         | 10.71%  |
| AuthenTec                  | 3         | 10.71%  |
| Upek                       | 2         | 7.14%   |
| LighTuning Technology      | 1         | 3.57%   |
| Focal-systems.Corp         | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 10.71%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 7.14%   |
| Elan ELAN:ARM-M4                                       | 2         | 7.14%   |
| Validity Sensors VFS491                                | 1         | 3.57%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 3.57%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.57%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 3.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.57%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 3.57%   |
| Shenzhen Goodix FingerPrint                            | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.57%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 3.57%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.57%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.57%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 3.57%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 81.82%  |
| O2 Micro    | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 36.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 130       | 65.99%  |
| 1     | 56        | 28.43%  |
| 2     | 10        | 5.08%   |
| 4     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 36.36%  |
| Graphics card            | 14        | 18.18%  |
| Net/wireless             | 10        | 12.99%  |
| Chipcard                 | 9         | 11.69%  |
| Multimedia controller    | 5         | 6.49%   |
| Storage                  | 3         | 3.9%    |
| Bluetooth                | 3         | 3.9%    |
| Net/ethernet             | 2         | 2.6%    |
| Storage/ide              | 1         | 1.3%    |
| Communication controller | 1         | 1.3%    |
| Card reader              | 1         | 1.3%    |

