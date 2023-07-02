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

Total: 312

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-52              | [3932620fb9](https://linux-hardware.org/?probe=3932620fb9) | Jun 30, 2023 |
| HP            | OMEN by Laptop              | [971852cb38](https://linux-hardware.org/?probe=971852cb38) | Jun 28, 2023 |
| Infinix       | INBook X1 Pro               | [a03717af50](https://linux-hardware.org/?probe=a03717af50) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| AZW           | GT-R                        | [11f032f354](https://linux-hardware.org/?probe=11f032f354) | Jun 24, 2023 |
| Fujitsu       | FMVNA4NE-                   | [59c8fdd841](https://linux-hardware.org/?probe=59c8fdd841) | Jun 08, 2023 |
| Fujitsu       | FMVNA4NE-                   | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [83537861c1](https://linux-hardware.org/?probe=83537861c1) | May 14, 2023 |
| Chuwi         | GemiBook Pro                | [1f22322c4a](https://linux-hardware.org/?probe=1f22322c4a) | May 11, 2023 |
| MSI           | Stealth 14Studio A13VE      | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| Samsung       | 535U3C                      | [5f2e46be0a](https://linux-hardware.org/?probe=5f2e46be0a) | May 05, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [0a9bdb3cea](https://linux-hardware.org/?probe=0a9bdb3cea) | May 02, 2023 |
| ASUSTek       | X455LJ                      | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| HP            | Notebook                    | [5fc60b1d5f](https://linux-hardware.org/?probe=5fc60b1d5f) | Apr 13, 2023 |
| HP            | ENVY Laptop 15-ep0xxx       | [04eb10296f](https://linux-hardware.org/?probe=04eb10296f) | Apr 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| NEC Comput... | PC-VK27MCZCK                | [e9572ebd2e](https://linux-hardware.org/?probe=e9572ebd2e) | Apr 06, 2023 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | [f64cf6a2ae](https://linux-hardware.org/?probe=f64cf6a2ae) | Apr 02, 2023 |
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
| Ubuntu 20.04        | 29        | 12.5%   |
| Ubuntu 22.04        | 13        | 5.6%    |
| Ubuntu 18.04        | 12        | 5.17%   |
| Pop!_OS 20.10       | 8         | 3.45%   |
| KDE neon 20.04      | 7         | 3.02%   |
| Pop!_OS 22.04       | 6         | 2.59%   |
| Pop!_OS 21.04       | 6         | 2.59%   |
| ArcoLinux Rolling   | 6         | 2.59%   |
| OpenMandriva 4.2    | 5         | 2.16%   |
| OpenMandriva 23.01  | 5         | 2.16%   |
| Arch Rolling        | 5         | 2.16%   |
| Ubuntu 16.04        | 4         | 1.72%   |
| OpenMandriva 4.50   | 4         | 1.72%   |
| Linux Mint 21.1     | 4         | 1.72%   |
| Fedora 33           | 4         | 1.72%   |
| EndeavourOS Rolling | 4         | 1.72%   |
| Zorin 16            | 3         | 1.29%   |
| Xubuntu 22.04       | 3         | 1.29%   |
| Ubuntu 21.04        | 3         | 1.29%   |
| Ubuntu 19.04        | 3         | 1.29%   |
| OpenMandriva 4.3    | 3         | 1.29%   |
| Manjaro             | 3         | 1.29%   |
| Linux Mint 20.2     | 3         | 1.29%   |
| Linux Mint 19.3     | 3         | 1.29%   |
| Fedora 37           | 3         | 1.29%   |
| Fedora 35           | 3         | 1.29%   |
| Fedora 34           | 3         | 1.29%   |
| Debian 11           | 3         | 1.29%   |
| Arch                | 3         | 1.29%   |
| Zorin 15            | 2         | 0.86%   |
| Ubuntu Unity 16.04  | 2         | 0.86%   |
| Ubuntu 20.10        | 2         | 0.86%   |
| Ubuntu 19.10        | 2         | 0.86%   |
| Pop!_OS 20.04       | 2         | 0.86%   |
| Nobara 37           | 2         | 0.86%   |
| Manjaro 21.0.7      | 2         | 0.86%   |
| Lubuntu 18.04       | 2         | 0.86%   |
| Linux Mint 20.1     | 2         | 0.86%   |
| Kubuntu 22.10       | 2         | 0.86%   |
| Elementary 5.1.7    | 2         | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 69        | 30.94%  |
| Pop!_OS       | 21        | 9.42%   |
| OpenMandriva  | 17        | 7.62%   |
| Fedora        | 13        | 5.83%   |
| Linux Mint    | 12        | 5.38%   |
| Manjaro       | 8         | 3.59%   |
| KDE neon      | 8         | 3.59%   |
| Arch          | 8         | 3.59%   |
| Zorin         | 6         | 2.69%   |
| ArcoLinux     | 6         | 2.69%   |
| Endless       | 5         | 2.24%   |
| Debian        | 5         | 2.24%   |
| Xubuntu       | 4         | 1.79%   |
| Kubuntu       | 4         | 1.79%   |
| EndeavourOS   | 4         | 1.79%   |
| Elementary    | 4         | 1.79%   |
| Lubuntu       | 3         | 1.35%   |
| CentOS        | 3         | 1.35%   |
| Ubuntu Unity  | 2         | 0.9%    |
| Ubuntu Budgie | 2         | 0.9%    |
| SteamOS       | 2         | 0.9%    |
| Nobara        | 2         | 0.9%    |
| Kali          | 2         | 0.9%    |
| Archcraft     | 2         | 0.9%    |
| Xero          | 1         | 0.45%   |
| Ultramarine   | 1         | 0.45%   |
| Ubuntu MATE   | 1         | 0.45%   |
| ROSA          | 1         | 0.45%   |
| Rocky Linux   | 1         | 0.45%   |
| Reborn OS     | 1         | 0.45%   |
| Peppermint    | 1         | 0.45%   |
| MX            | 1         | 0.45%   |
| LMDE          | 1         | 0.45%   |
| Gentoo        | 1         | 0.45%   |
| BuildRoot     | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 5         | 2.02%   |
| 5.11.0-7620-generic      | 5         | 2.02%   |
| 6.3.9-arch1-1            | 4         | 1.61%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.61%   |
| 5.0.0-37-generic         | 4         | 1.61%   |
| 5.8.0-7642-generic       | 3         | 1.21%   |
| 5.4.0-58-generic         | 3         | 1.21%   |
| 5.4.0-54-generic         | 3         | 1.21%   |
| 5.4.0-42-generic         | 3         | 1.21%   |
| 5.16.7-desktop-1omv4003  | 3         | 1.21%   |
| 5.15.0-56-generic        | 3         | 1.21%   |
| 5.15.0-52-generic        | 3         | 1.21%   |
| 5.12.4-desktop-1omv4050  | 3         | 1.21%   |
| 5.11.0-46-generic        | 3         | 1.21%   |
| 5.0.0-23-generic         | 3         | 1.21%   |
| 4.15.0-45-generic        | 3         | 1.21%   |
| 6.2.6-76060206-generic   | 2         | 0.81%   |
| 5.8.0-7630-generic       | 2         | 0.81%   |
| 5.8.0-45-generic         | 2         | 0.81%   |
| 5.4.0-89-generic         | 2         | 0.81%   |
| 5.4.0-64-generic         | 2         | 0.81%   |
| 5.4.0-52-generic         | 2         | 0.81%   |
| 5.3.0-51-generic         | 2         | 0.81%   |
| 5.19.0-76051900-generic  | 2         | 0.81%   |
| 5.19.0-38-generic        | 2         | 0.81%   |
| 5.17.5-76051705-generic  | 2         | 0.81%   |
| 5.17.1-051701-generic    | 2         | 0.81%   |
| 5.15.0-58-generic        | 2         | 0.81%   |
| 5.15.0-46-generic        | 2         | 0.81%   |
| 5.15.0-40-generic        | 2         | 0.81%   |
| 5.15.0-25-generic        | 2         | 0.81%   |
| 5.13.0-7614-generic      | 2         | 0.81%   |
| 5.13.0-22-generic        | 2         | 0.81%   |
| 5.11.0-7614-generic      | 2         | 0.81%   |
| 5.11.0-40-generic        | 2         | 0.81%   |
| 5.11.0-27-generic        | 2         | 0.81%   |
| 5.10.79-1-lts            | 2         | 0.81%   |
| 5.10.42-1-MANJARO        | 2         | 0.81%   |
| 5.10.13-200.fc33.x86_64  | 2         | 0.81%   |
| 5.10.0-13-amd64          | 2         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 12.61%  |
| 5.15.0  | 20        | 8.4%    |
| 5.11.0  | 17        | 7.14%   |
| 5.8.0   | 15        | 6.3%    |
| 5.13.0  | 12        | 5.04%   |
| 4.15.0  | 12        | 5.04%   |
| 5.0.0   | 10        | 4.2%    |
| 5.3.0   | 9         | 3.78%   |
| 6.1.1   | 6         | 2.52%   |
| 5.19.0  | 6         | 2.52%   |
| 6.3.9   | 4         | 1.68%   |
| 5.10.14 | 4         | 1.68%   |
| 5.10.0  | 4         | 1.68%   |
| 4.18.0  | 4         | 1.68%   |
| 5.17.1  | 3         | 1.26%   |
| 5.16.7  | 3         | 1.26%   |
| 5.16.15 | 3         | 1.26%   |
| 5.12.4  | 3         | 1.26%   |
| 6.2.8   | 2         | 0.84%   |
| 6.2.6   | 2         | 0.84%   |
| 5.9.0   | 2         | 0.84%   |
| 5.18.0  | 2         | 0.84%   |
| 5.17.5  | 2         | 0.84%   |
| 5.12.9  | 2         | 0.84%   |
| 5.10.79 | 2         | 0.84%   |
| 5.10.42 | 2         | 0.84%   |
| 5.10.13 | 2         | 0.84%   |
| 4.4.0   | 2         | 0.84%   |
| 3.10.0  | 2         | 0.84%   |
| 6.3.6   | 1         | 0.42%   |
| 6.3.1   | 1         | 0.42%   |
| 6.2.9   | 1         | 0.42%   |
| 6.2.12  | 1         | 0.42%   |
| 6.1.9   | 1         | 0.42%   |
| 6.1.6   | 1         | 0.42%   |
| 6.1.4   | 1         | 0.42%   |
| 6.1.0   | 1         | 0.42%   |
| 6.0.9   | 1         | 0.42%   |
| 6.0.12  | 1         | 0.42%   |
| 6.0.0   | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 12.82%  |
| 5.15    | 23        | 9.83%   |
| 5.8     | 22        | 9.4%    |
| 5.11    | 20        | 8.55%   |
| 5.10    | 17        | 7.26%   |
| 5.13    | 13        | 5.56%   |
| 4.15    | 12        | 5.13%   |
| 5.0     | 10        | 4.27%   |
| 6.1     | 9         | 3.85%   |
| 5.3     | 9         | 3.85%   |
| 5.19    | 9         | 3.85%   |
| 5.12    | 7         | 2.99%   |
| 6.3     | 6         | 2.56%   |
| 6.2     | 6         | 2.56%   |
| 5.17    | 6         | 2.56%   |
| 5.16    | 6         | 2.56%   |
| 5.18    | 5         | 2.14%   |
| 5.14    | 5         | 2.14%   |
| 4.18    | 4         | 1.71%   |
| 6.0     | 3         | 1.28%   |
| 5.9     | 3         | 1.28%   |
| 5.7     | 2         | 0.85%   |
| 4.4     | 2         | 0.85%   |
| 3.10    | 2         | 0.85%   |
| 5.6     | 1         | 0.43%   |
| 4.10    | 1         | 0.43%   |
| 4.1     | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 208       | 98.58%  |
| i686   | 3         | 1.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 102       | 45.74%  |
| KDE5          | 43        | 19.28%  |
| Unknown       | 22        | 9.87%   |
| XFCE          | 16        | 7.17%   |
| X-Cinnamon    | 11        | 4.93%   |
| KDE           | 8         | 3.59%   |
| Pantheon      | 4         | 1.79%   |
| MATE          | 4         | 1.79%   |
| Unity         | 2         | 0.9%    |
| openbox       | 2         | 0.9%    |
| Budgie        | 2         | 0.9%    |
| Peppermint    | 1         | 0.45%   |
| LXQt          | 1         | 0.45%   |
| LXDE          | 1         | 0.45%   |
| i3            | 1         | 0.45%   |
| Hyprland      | 1         | 0.45%   |
| GNOME Classic | 1         | 0.45%   |
| bspwm         | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 170       | 76.92%  |
| Wayland | 39        | 17.65%  |
| Unknown | 9         | 4.07%   |
| Tty     | 3         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 111       | 50.92%  |
| SDDM    | 40        | 18.35%  |
| GDM3    | 26        | 11.93%  |
| GDM     | 24        | 11.01%  |
| LightDM | 15        | 6.88%   |
| TDM     | 2         | 0.92%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 171       | 79.91%  |
| Unknown | 17        | 7.94%   |
| en_GB   | 11        | 5.14%   |
| en_SG   | 6         | 2.8%    |
| C       | 3         | 1.4%    |
| ms_MY   | 2         | 0.93%   |
| zh_TW   | 1         | 0.47%   |
| ja_JP   | 1         | 0.47%   |
| id_ID   | 1         | 0.47%   |
| en_MY   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 107       | 50.23%  |
| BIOS | 106       | 49.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 163       | 75.46%  |
| Btrfs   | 20        | 9.26%   |
| Overlay | 18        | 8.33%   |
| Xfs     | 5         | 2.31%   |
| Unknown | 5         | 2.31%   |
| Zfs     | 4         | 1.85%   |
| Ext2    | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 120       | 55.3%   |
| GPT     | 73        | 33.64%  |
| MBR     | 24        | 11.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 183       | 85.12%  |
| Yes       | 32        | 14.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 153       | 70.83%  |
| Yes       | 63        | 29.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 43        | 20.38%  |
| Hewlett-Packard     | 39        | 18.48%  |
| ASUSTek Computer    | 34        | 16.11%  |
| Lenovo              | 30        | 14.22%  |
| Acer                | 19        | 9%      |
| MSI                 | 7         | 3.32%   |
| Apple               | 5         | 2.37%   |
| Sony                | 4         | 1.9%    |
| Fujitsu             | 4         | 1.9%    |
| Samsung Electronics | 3         | 1.42%   |
| HUAWEI              | 3         | 1.42%   |
| NEC Computers       | 2         | 0.95%   |
| ILLEGEAR            | 2         | 0.95%   |
| Chuwi               | 2         | 0.95%   |
| Unknown             | 2         | 0.95%   |
| Valve               | 1         | 0.47%   |
| Toshiba             | 1         | 0.47%   |
| Timi                | 1         | 0.47%   |
| System76            | 1         | 0.47%   |
| SNS Network (M)     | 1         | 0.47%   |
| Infinix             | 1         | 0.47%   |
| HONOR               | 1         | 0.47%   |
| GPD                 | 1         | 0.47%   |
| Gigabyte Technology | 1         | 0.47%   |
| BUSH                | 1         | 0.47%   |
| AZW                 | 1         | 0.47%   |
| Alienware           | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Notebook                         | 5         | 2.37%   |
| MSI Modern 14 B5M                   | 2         | 0.95%   |
| HP Pavilion dv6                     | 2         | 0.95%   |
| HP Laptop 15-bs0xx                  | 2         | 0.95%   |
| HP ENVY 4                           | 2         | 0.95%   |
| HP EliteBook 8470p                  | 2         | 0.95%   |
| HP EliteBook 840 G2                 | 2         | 0.95%   |
| HP Compaq Presario CQ40             | 2         | 0.95%   |
| Dell XPS 15 7590                    | 2         | 0.95%   |
| Dell Latitude E6520                 | 2         | 0.95%   |
| Dell Latitude E6440                 | 2         | 0.95%   |
| Dell Latitude 3410                  | 2         | 0.95%   |
| ASUS K45VD                          | 2         | 0.95%   |
| ASUS K43SD                          | 2         | 0.95%   |
| Apple MacBookPro8,1                 | 2         | 0.95%   |
| Unknown                             | 2         | 0.95%   |
| Valve Jupiter                       | 1         | 0.47%   |
| Toshiba dynabook Satellite B552/H   | 1         | 0.47%   |
| Timi RedmiBook 14 II                | 1         | 0.47%   |
| System76 Galago Pro                 | 1         | 0.47%   |
| Sony VPCSB26FG                      | 1         | 0.47%   |
| Sony VPCEG16EG                      | 1         | 0.47%   |
| Sony VPCEA42EG                      | 1         | 0.47%   |
| Sony VGN-Z27GN_X                    | 1         | 0.47%   |
| SNS Network (M) JOI Book 150        | 1         | 0.47%   |
| Samsung RV413/RV513                 | 1         | 0.47%   |
| Samsung 730U3E/740U3E               | 1         | 0.47%   |
| Samsung 535U3C                      | 1         | 0.47%   |
| NEC Computers PC-VK27MXZCG          | 1         | 0.47%   |
| NEC Computers PC-VK27MCZCK          | 1         | 0.47%   |
| MSI Stealth 14Studio A13VE          | 1         | 0.47%   |
| MSI Prestige 15 A10SC               | 1         | 0.47%   |
| MSI GT70 2OC/2OD                    | 1         | 0.47%   |
| MSI GP70 2PE                        | 1         | 0.47%   |
| MSI GL62M 7RDX                      | 1         | 0.47%   |
| Lenovo Yoga 500-15IBD 80N6          | 1         | 0.47%   |
| Lenovo Y520-15IKBN 80WK             | 1         | 0.47%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7 | 1         | 0.47%   |
| Lenovo U310                         | 1         | 0.47%   |
| Lenovo ThinkPad X220 42912WA        | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 18        | 8.53%   |
| Lenovo ThinkPad            | 17        | 8.06%   |
| Dell Inspiron              | 14        | 6.64%   |
| Acer Aspire                | 11        | 5.21%   |
| HP Pavilion                | 7         | 3.32%   |
| HP EliteBook               | 7         | 3.32%   |
| HP Notebook                | 5         | 2.37%   |
| HP Laptop                  | 5         | 2.37%   |
| Dell XPS                   | 5         | 2.37%   |
| Lenovo IdeaPad             | 4         | 1.9%    |
| HP Compaq                  | 4         | 1.9%    |
| HP ENVY                    | 3         | 1.42%   |
| Fujitsu LIFEBOOK           | 3         | 1.42%   |
| Dell Precision             | 3         | 1.42%   |
| ASUS VivoBook              | 3         | 1.42%   |
| ASUS ROG                   | 3         | 1.42%   |
| Apple MacBookPro8          | 3         | 1.42%   |
| Acer Nitro                 | 3         | 1.42%   |
| MSI Modern                 | 2         | 0.95%   |
| HP ProBook                 | 2         | 0.95%   |
| ASUS K45VD                 | 2         | 0.95%   |
| ASUS K43SD                 | 2         | 0.95%   |
| Unknown                    | 2         | 0.95%   |
| Valve Jupiter              | 1         | 0.47%   |
| Toshiba dynabook           | 1         | 0.47%   |
| Timi RedmiBook             | 1         | 0.47%   |
| System76 Galago            | 1         | 0.47%   |
| Sony VPCSB26FG             | 1         | 0.47%   |
| Sony VPCEG16EG             | 1         | 0.47%   |
| Sony VPCEA42EG             | 1         | 0.47%   |
| Sony VGN-Z27GN             | 1         | 0.47%   |
| SNS Network (M) JOI        | 1         | 0.47%   |
| Samsung RV413              | 1         | 0.47%   |
| Samsung 730U3E             | 1         | 0.47%   |
| Samsung 535U3C             | 1         | 0.47%   |
| NEC Computers PC-VK27MXZCG | 1         | 0.47%   |
| NEC Computers PC-VK27MCZCK | 1         | 0.47%   |
| MSI Stealth                | 1         | 0.47%   |
| MSI Prestige               | 1         | 0.47%   |
| MSI GT70                   | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 29        | 13.74%  |
| 2020 | 21        | 9.95%   |
| 2013 | 21        | 9.95%   |
| 2021 | 20        | 9.48%   |
| 2019 | 18        | 8.53%   |
| 2012 | 15        | 7.11%   |
| 2018 | 14        | 6.64%   |
| 2015 | 13        | 6.16%   |
| 2017 | 11        | 5.21%   |
| 2010 | 11        | 5.21%   |
| 2014 | 10        | 4.74%   |
| 2016 | 8         | 3.79%   |
| 2008 | 8         | 3.79%   |
| 2009 | 6         | 2.84%   |
| 2022 | 3         | 1.42%   |
| 2007 | 2         | 0.95%   |
| 2023 | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 211       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 192       | 91%     |
| Enabled  | 19        | 9%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 209       | 99.05%  |
| Yes  | 2         | 0.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 56        | 26.42%  |
| 3.01-4.0    | 53        | 25%     |
| 8.01-16.0   | 43        | 20.28%  |
| 16.01-24.0  | 31        | 14.62%  |
| 32.01-64.0  | 10        | 4.72%   |
| 1.01-2.0    | 7         | 3.3%    |
| 24.01-32.0  | 4         | 1.89%   |
| 2.01-3.0    | 3         | 1.42%   |
| 64.01-256.0 | 3         | 1.42%   |
| 0.51-1.0    | 2         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 79        | 33.76%  |
| 2.01-3.0  | 68        | 29.06%  |
| 3.01-4.0  | 34        | 14.53%  |
| 4.01-8.0  | 28        | 11.97%  |
| 0.51-1.0  | 17        | 7.26%   |
| 8.01-16.0 | 8         | 3.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 68.52%  |
| 2      | 58        | 26.85%  |
| 3      | 8         | 3.7%    |
| 4      | 2         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 137       | 64.93%  |
| Yes       | 74        | 35.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 84.36%  |
| No        | 33        | 15.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 97.16%  |
| No        | 6         | 2.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 82.08%  |
| No        | 38        | 17.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Malaysia | 211       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 77        | 33.92%  |
| Petaling Jaya          | 25        | 11.01%  |
| Shah Alam              | 11        | 4.85%   |
| Johor Bahru            | 11        | 4.85%   |
| Puchong Batu Dua Belas | 9         | 3.96%   |
| Ipoh                   | 9         | 3.96%   |
| Subang Jaya            | 8         | 3.52%   |
| Sungai Buloh           | 6         | 2.64%   |
| Seremban               | 6         | 2.64%   |
| Kota Kinabalu          | 6         | 2.64%   |
| Sungai Petani          | 4         | 1.76%   |
| Skudai                 | 4         | 1.76%   |
| Kota Bharu             | 4         | 1.76%   |
| Kajang                 | 4         | 1.76%   |
| Marabu                 | 3         | 1.32%   |
| Kulai                  | 3         | 1.32%   |
| Klang                  | 3         | 1.32%   |
| Cyberjaya              | 3         | 1.32%   |
| Tawau                  | 2         | 0.88%   |
| Nibong Tebal           | 2         | 0.88%   |
| Malacca                | 2         | 0.88%   |
| Kulim                  | 2         | 0.88%   |
| George Town            | 2         | 0.88%   |
| Cheras                 | 2         | 0.88%   |
| Seri Kembangan         | 1         | 0.44%   |
| Sepang                 | 1         | 0.44%   |
| Semenyih               | 1         | 0.44%   |
| Rawang                 | 1         | 0.44%   |
| Putrajaya              | 1         | 0.44%   |
| Pasir Gudang           | 1         | 0.44%   |
| Long Seridan           | 1         | 0.44%   |
| Kuching                | 1         | 0.44%   |
| Kuala Terengganu       | 1         | 0.44%   |
| Kuala Kangsar          | 1         | 0.44%   |
| Kota Tinggi            | 1         | 0.44%   |
| Kamunting              | 1         | 0.44%   |
| Jitra                  | 1         | 0.44%   |
| Hutan Melintang        | 1         | 0.44%   |
| Gambang                | 1         | 0.44%   |
| Butterworth            | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 38        | 44     | 13.62%  |
| WDC                         | 27        | 34     | 9.68%   |
| Samsung Electronics         | 27        | 36     | 9.68%   |
| Toshiba                     | 26        | 32     | 9.32%   |
| Kingston                    | 21        | 24     | 7.53%   |
| SanDisk                     | 16        | 21     | 5.73%   |
| HGST                        | 16        | 19     | 5.73%   |
| Unknown                     | 14        | 20     | 5.02%   |
| SK hynix                    | 7         | 7      | 2.51%   |
| A-DATA Technology           | 7         | 7      | 2.51%   |
| Micron Technology           | 6         | 6      | 2.15%   |
| Intel                       | 6         | 9      | 2.15%   |
| Hitachi                     | 6         | 11     | 2.15%   |
| KIOXIA                      | 5         | 6      | 1.79%   |
| Apacer                      | 5         | 5      | 1.79%   |
| Transcend                   | 4         | 5      | 1.43%   |
| SPCC                        | 3         | 4      | 1.08%   |
| Phison                      | 3         | 5      | 1.08%   |
| Patriot                     | 3         | 4      | 1.08%   |
| China                       | 3         | 3      | 1.08%   |
| TO Exter                    | 2         | 2      | 0.72%   |
| Team                        | 2         | 2      | 0.72%   |
| Silicon Motion              | 2         | 2      | 0.72%   |
| Netac                       | 2         | 2      | 0.72%   |
| Kingston Technology Company | 2         | 2      | 0.72%   |
| Hewlett-Packard             | 2         | 2      | 0.72%   |
| Fujitsu                     | 2         | 2      | 0.72%   |
| Crucial                     | 2         | 2      | 0.72%   |
| winstar                     | 1         | 1      | 0.36%   |
| Western Digital             | 1         | 1      | 0.36%   |
| Verbatim                    | 1         | 1      | 0.36%   |
| USB3.0                      | 1         | 1      | 0.36%   |
| PNY                         | 1         | 1      | 0.36%   |
| Pioneer                     | 1         | 1      | 0.36%   |
| Phison Electronics          | 1         | 1      | 0.36%   |
| Morebeck-S100               | 1         | 1      | 0.36%   |
| Micron/Crucial Technology   | 1         | 2      | 0.36%   |
| LS                          | 1         | 1      | 0.36%   |
| Kingchuxing                 | 1         | 1      | 0.36%   |
| KimMiDi                     | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB              | 6         | 2.1%    |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.75%   |
| Unknown MMC Card  32GB                  | 4         | 1.4%    |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.4%    |
| Seagate ST500LT012-1DG142 500GB         | 4         | 1.4%    |
| SK hynix NVMe SSD Drive 512GB           | 3         | 1.05%   |
| Seagate ST9320325AS 320GB               | 3         | 1.05%   |
| Seagate ST1000LM048-2E7172 1TB          | 3         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.05%   |
| SanDisk SSD PLUS 240GB                  | 3         | 1.05%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 1.05%   |
| HGST HTS725050A7E630 500GB              | 3         | 1.05%   |
| HGST HTS721010A9E630 1TB                | 3         | 1.05%   |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 2         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.7%    |
| WDC PC SN730 NVMe 1024GB                | 2         | 0.7%    |
| Unknown MMC Card  64GB                  | 2         | 0.7%    |
| Unknown MMC Card  128GB                 | 2         | 0.7%    |
| Toshiba MK5065GSXF 500GB                | 2         | 0.7%    |
| TO Exter nal USB 3.0 1TB                | 2         | 0.7%    |
| Seagate ST9750420AS 752GB               | 2         | 0.7%    |
| Seagate ST9500325AS 500GB               | 2         | 0.7%    |
| Seagate ST500LM000-1EJ162 500GB         | 2         | 0.7%    |
| Seagate ST320LT020-9YG142 320GB         | 2         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 0.7%    |
| Sandisk PC SN530 NVMe WDC 256GB         | 2         | 0.7%    |
| Samsung SSD 860 EVO 500GB               | 2         | 0.7%    |
| Samsung SSD 860 EVO 250GB               | 2         | 0.7%    |
| Samsung NVMe SSD Drive 512GB            | 2         | 0.7%    |
| Netac SSD 256GB                         | 2         | 0.7%    |
| Micron 1100 SATA 512GB SSD              | 2         | 0.7%    |
| KIOXIA NVMe SSD Drive 256GB             | 2         | 0.7%    |
| Kingston Company OM3PDP3 NVMe SSD 256GB | 2         | 0.7%    |
| Kingston SH103S3120G 120GB SSD          | 2         | 0.7%    |
| Kingston SA400S37240G 240GB SSD         | 2         | 0.7%    |
| Intel SSD 660P Series 512GB             | 2         | 0.7%    |
| Intel NVMe SSD Drive 512GB              | 2         | 0.7%    |
| Hitachi HTS723232A7A364 320GB           | 2         | 0.7%    |
| HGST HTS541010A9E680 1TB                | 2         | 0.7%    |
| Apacer AS340 120GB SSD                  | 2         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 43     | 35.92%  |
| Toshiba             | 22        | 27     | 21.36%  |
| WDC                 | 16        | 23     | 15.53%  |
| HGST                | 16        | 19     | 15.53%  |
| Hitachi             | 6         | 11     | 5.83%   |
| Fujitsu             | 2         | 2      | 1.94%   |
| USB3.0              | 1         | 1      | 0.97%   |
| Unknown             | 1         | 1      | 0.97%   |
| Samsung Electronics | 1         | 3      | 0.97%   |
| ASMT                | 1         | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 18     | 19.1%   |
| Samsung Electronics | 14        | 20     | 15.73%  |
| SanDisk             | 8         | 8      | 8.99%   |
| Apacer              | 5         | 5      | 5.62%   |
| A-DATA Technology   | 5         | 5      | 5.62%   |
| Transcend           | 4         | 4      | 4.49%   |
| WDC                 | 3         | 3      | 3.37%   |
| SPCC                | 3         | 4      | 3.37%   |
| Patriot             | 3         | 4      | 3.37%   |
| Micron Technology   | 3         | 3      | 3.37%   |
| China               | 3         | 3      | 3.37%   |
| TO Exter            | 2         | 2      | 2.25%   |
| Team                | 2         | 2      | 2.25%   |
| Netac               | 2         | 2      | 2.25%   |
| Intel               | 2         | 2      | 2.25%   |
| Crucial             | 2         | 2      | 2.25%   |
| Verbatim            | 1         | 1      | 1.12%   |
| Toshiba             | 1         | 1      | 1.12%   |
| PNY                 | 1         | 1      | 1.12%   |
| Pioneer             | 1         | 1      | 1.12%   |
| LS                  | 1         | 1      | 1.12%   |
| KimMiDi             | 1         | 1      | 1.12%   |
| Hewlett-Packard     | 1         | 1      | 1.12%   |
| Gigabyte Technology | 1         | 1      | 1.12%   |
| Colorful            | 1         | 1      | 1.12%   |
| Apple               | 1         | 2      | 1.12%   |
| Unknown             | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98        | 131    | 38.28%  |
| SSD     | 80        | 99     | 31.25%  |
| NVMe    | 60        | 86     | 23.44%  |
| MMC     | 13        | 19     | 5.08%   |
| Unknown | 5         | 6      | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 227    | 66.26%  |
| NVMe | 59        | 85     | 24.28%  |
| MMC  | 13        | 19     | 5.35%   |
| SAS  | 10        | 10     | 4.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 121       | 155    | 67.98%  |
| 0.51-1.0   | 56        | 74     | 31.46%  |
| 1.01-2.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 63        | 27.75%  |
| 251-500        | 62        | 27.31%  |
| 501-1000       | 31        | 13.66%  |
| 1-20           | 24        | 10.57%  |
| 51-100         | 18        | 7.93%   |
| 21-50          | 12        | 5.29%   |
| 1001-2000      | 8         | 3.52%   |
| Unknown        | 5         | 2.2%    |
| More than 3000 | 2         | 0.88%   |
| 2001-3000      | 2         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 100       | 43.29%  |
| 21-50     | 44        | 19.05%  |
| 101-250   | 29        | 12.55%  |
| 51-100    | 23        | 9.96%   |
| 251-500   | 18        | 7.79%   |
| 501-1000  | 7         | 3.03%   |
| Unknown   | 5         | 2.16%   |
| 1001-2000 | 3         | 1.3%    |
| 2001-3000 | 1         | 0.43%   |
| 0         | 1         | 0.43%   |

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
| Detected | 134       | 213    | 58.52%  |
| Works    | 75        | 103    | 32.75%  |
| Malfunc  | 20        | 25     | 8.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 154       | 62.86%  |
| AMD                          | 23        | 9.39%   |
| SanDisk                      | 16        | 6.53%   |
| Samsung Electronics          | 12        | 4.9%    |
| SK hynix                     | 7         | 2.86%   |
| Kingston Technology Company  | 6         | 2.45%   |
| Silicon Motion               | 5         | 2.04%   |
| KIOXIA                       | 5         | 2.04%   |
| Phison Electronics           | 4         | 1.63%   |
| Toshiba America Info Systems | 3         | 1.22%   |
| Nvidia                       | 3         | 1.22%   |
| Micron Technology            | 3         | 1.22%   |
| Micron/Crucial Technology    | 1         | 0.41%   |
| Biwin Storage Technology     | 1         | 0.41%   |
| ASMedia Technology           | 1         | 0.41%   |
| ADATA Technology             | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 8.85%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 8.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 6.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 18        | 6.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 15        | 5.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 2.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.31%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.54%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.54%   |
| Intel SSD 660P Series                                                            | 4         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 1.15%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 1.15%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 3         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.15%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.15%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 3         | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.15%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.77%   |
| Micron NVMe Storage Controller                                                   | 2         | 0.77%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.77%   |
| Kingston Company KC2000 NVMe SSD                                                 | 2         | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.77%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.77%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.77%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 148       | 61.16%  |
| NVMe | 59        | 24.38%  |
| RAID | 24        | 9.92%   |
| IDE  | 11        | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 81.04%  |
| AMD    | 40        | 18.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz               | 8         | 3.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 4         | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 4         | 1.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 4         | 1.89%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 4         | 1.89%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 4         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 4         | 1.89%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 3         | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 3         | 1.42%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 3         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 1.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 3         | 1.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 3         | 1.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 3         | 1.42%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.42%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 3         | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 1.42%   |
| AMD Ryzen 5 5600H with Radeon Graphics          | 3         | 1.42%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 2         | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 0.94%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 0.94%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 2         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 2         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 0.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 0.94%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 2         | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 0.94%   |
| Intel Core i5-2540M CPU @ 2.60GHz               | 2         | 0.94%   |
| Intel Core i5-2435M CPU @ 2.40GHz               | 2         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 2         | 0.94%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 0.94%   |
| Intel Core i3-2367M CPU @ 1.40GHz               | 2         | 0.94%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 0.94%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 0.94%   |
| Intel Core i3 CPU M 330 @ 2.13GHz               | 2         | 0.94%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 2         | 0.94%   |
| AMD Ryzen 7 PRO 2700U w/ Radeon Vega Mobile Gfx | 2         | 0.94%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 0.94%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 64        | 30.19%  |
| Intel Core i7           | 45        | 21.23%  |
| Intel Core i3           | 16        | 7.55%   |
| AMD Ryzen 5             | 14        | 6.6%    |
| Intel Celeron           | 13        | 6.13%   |
| Other                   | 11        | 5.19%   |
| Intel Core 2 Duo        | 10        | 4.72%   |
| Intel Atom              | 5         | 2.36%   |
| AMD Ryzen 7             | 5         | 2.36%   |
| AMD A6                  | 4         | 1.89%   |
| Intel Pentium Dual-Core | 3         | 1.42%   |
| Intel Pentium           | 3         | 1.42%   |
| AMD Ryzen 7 PRO         | 3         | 1.42%   |
| AMD Athlon              | 3         | 1.42%   |
| AMD Ryzen 9             | 2         | 0.94%   |
| AMD E                   | 2         | 0.94%   |
| AMD A4                  | 2         | 0.94%   |
| AMD A12                 | 2         | 0.94%   |
| Intel Xeon              | 1         | 0.47%   |
| Intel Genuine           | 1         | 0.47%   |
| Intel Core i9           | 1         | 0.47%   |
| AMD FX                  | 1         | 0.47%   |
| AMD A10                 | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 113       | 53.55%  |
| 4      | 59        | 27.96%  |
| 6      | 20        | 9.48%   |
| 8      | 11        | 5.21%   |
| 1      | 6         | 2.84%   |
| 14     | 2         | 0.95%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 211       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 170       | 80.19%  |
| 1      | 42        | 19.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 209       | 98.58%  |
| Unknown        | 3         | 1.42%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 24.2%   |
| 0x206a7    | 20        | 9.13%   |
| 0x306a9    | 15        | 6.85%   |
| 0x906ea    | 8         | 3.65%   |
| 0x40651    | 8         | 3.65%   |
| 0x306d4    | 7         | 3.2%    |
| 0x306c3    | 7         | 3.2%    |
| 0x806e9    | 6         | 2.74%   |
| 0x406e3    | 6         | 2.74%   |
| 0x20655    | 6         | 2.74%   |
| 0xa0652    | 5         | 2.28%   |
| 0x1067a    | 5         | 2.28%   |
| 0x806ea    | 4         | 1.83%   |
| 0x20652    | 4         | 1.83%   |
| 0x08600104 | 4         | 1.83%   |
| 0x06001119 | 4         | 1.83%   |
| 0x806ec    | 3         | 1.37%   |
| 0x806eb    | 3         | 1.37%   |
| 0x806d1    | 3         | 1.37%   |
| 0x806c1    | 3         | 1.37%   |
| 0x30678    | 3         | 1.37%   |
| 0x08108109 | 3         | 1.37%   |
| 0x906e9    | 2         | 0.91%   |
| 0x706e5    | 2         | 0.91%   |
| 0x706a8    | 2         | 0.91%   |
| 0x706a1    | 2         | 0.91%   |
| 0x406c4    | 2         | 0.91%   |
| 0x106ca    | 2         | 0.91%   |
| 0x10676    | 2         | 0.91%   |
| 0x0a50000d | 2         | 0.91%   |
| 0x0a50000b | 2         | 0.91%   |
| 0x08608103 | 2         | 0.91%   |
| 0x08108102 | 2         | 0.91%   |
| 0x0700010f | 2         | 0.91%   |
| 0xa0660    | 1         | 0.46%   |
| 0x906a3    | 1         | 0.46%   |
| 0x6fd      | 1         | 0.46%   |
| 0x6fb      | 1         | 0.46%   |
| 0x406c3    | 1         | 0.46%   |
| 0x0a50000c | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 32        | 15.17%  |
| SandyBridge      | 28        | 13.27%  |
| IvyBridge        | 20        | 9.48%   |
| Haswell          | 17        | 8.06%   |
| Penryn           | 11        | 5.21%   |
| Westmere         | 10        | 4.74%   |
| Zen+             | 9         | 4.27%   |
| Skylake          | 9         | 4.27%   |
| Silvermont       | 8         | 3.79%   |
| Broadwell        | 8         | 3.79%   |
| Zen 3            | 7         | 3.32%   |
| Zen 2            | 6         | 2.84%   |
| IceLake          | 6         | 2.84%   |
| CometLake        | 6         | 2.84%   |
| TigerLake        | 5         | 2.37%   |
| Piledriver       | 5         | 2.37%   |
| Goldmont plus    | 4         | 1.9%    |
| Core             | 3         | 1.42%   |
| Unknown          | 3         | 1.42%   |
| Zen              | 2         | 0.95%   |
| Jaguar           | 2         | 0.95%   |
| Excavator        | 2         | 0.95%   |
| Bonnell          | 2         | 0.95%   |
| Bobcat           | 2         | 0.95%   |
| Alderlake Hybrid | 2         | 0.95%   |
| Steamroller      | 1         | 0.47%   |
| K8 & K10 hybrid  | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 162       | 55.29%  |
| Nvidia | 72        | 24.57%  |
| AMD    | 59        | 20.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 8.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 6.64%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 3.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.99%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.33%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.99%   |
| Intel HD Graphics 620                                                                    | 6         | 1.99%   |
| AMD Renoir                                                                               | 6         | 1.99%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.33%   |
| Intel HD Graphics 630                                                                    | 4         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.33%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1%      |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1%      |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1%      |
| Intel Iris Plus Graphics G7                                                              | 3         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1%      |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.66%   |
| Nvidia GM108M [GeForce 930M]                                                             | 2         | 0.66%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.66%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.66%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.66%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.66%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.66%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 87        | 41.04%  |
| Intel + Nvidia | 58        | 27.36%  |
| 1 x AMD        | 29        | 13.68%  |
| Intel + AMD    | 17        | 8.02%   |
| 2 x AMD        | 7         | 3.3%    |
| 1 x Nvidia     | 7         | 3.3%    |
| AMD + Nvidia   | 7         | 3.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 169       | 78.97%  |
| Proprietary | 43        | 20.09%  |
| Unknown     | 2         | 0.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 123       | 56.94%  |
| 1.01-2.0   | 36        | 16.67%  |
| 0.01-0.5   | 22        | 10.19%  |
| 3.01-4.0   | 18        | 8.33%   |
| 0.51-1.0   | 13        | 6.02%   |
| 7.01-8.0   | 2         | 0.93%   |
| 5.01-6.0   | 2         | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 21.16%  |
| Chimei Innolux          | 39        | 16.18%  |
| LG Display              | 33        | 13.69%  |
| BOE                     | 29        | 12.03%  |
| Samsung Electronics     | 25        | 10.37%  |
| Dell                    | 11        | 4.56%   |
| Sharp                   | 7         | 2.9%    |
| Chi Mei Optoelectronics | 4         | 1.66%   |
| Apple                   | 4         | 1.66%   |
| Acer                    | 4         | 1.66%   |
| Lenovo                  | 3         | 1.24%   |
| Hewlett-Packard         | 3         | 1.24%   |
| Philips                 | 2         | 0.83%   |
| PANDA                   | 2         | 0.83%   |
| Panasonic               | 2         | 0.83%   |
| InnoLux Display         | 2         | 0.83%   |
| AOC                     | 2         | 0.83%   |
| Xiaomi                  | 1         | 0.41%   |
| ViewSonic               | 1         | 0.41%   |
| Valve                   | 1         | 0.41%   |
| Unknown                 | 1         | 0.41%   |
| TRI                     | 1         | 0.41%   |
| Toshiba                 | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| MStar                   | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| LTM                     | 1         | 0.41%   |
| LG Philips              | 1         | 0.41%   |
| InfoVision              | 1         | 0.41%   |
| HJC                     | 1         | 0.41%   |
| Goldstar                | 1         | 0.41%   |
| EXP                     | 1         | 0.41%   |
| BenQ                    | 1         | 0.41%   |
| Armaggeddon             | 1         | 0.41%   |
| Ancor Communications    | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 4         | 1.66%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 1.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 1.24%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 1.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 2         | 0.83%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.83%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 2         | 0.83%   |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                   | 2         | 0.83%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.83%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 2         | 0.83%   |
| Acer ET241Y ACR056C 1920x1080 527x296mm 23.8-inch                         | 2         | 0.83%   |
| Xiaomi Mi TV XMD00E1 3840x2160 950x540mm 43.0-inch                        | 1         | 0.41%   |
| ViewSonic V3D231 Series VSC4C29 1920x1080 510x290mm 23.1-inch             | 1         | 0.41%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 1         | 0.41%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1600x900               | 1         | 0.41%   |
| TRI TRI2400 TRI2400 1920x1080 530x300mm 24.0-inch                         | 1         | 0.41%   |
| Toshiba TV TSB010B 1920x1080 706x398mm 31.9-inch                          | 1         | 0.41%   |
| Sony TV SNY0902 1360x768                                                  | 1         | 0.41%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 1         | 0.41%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                   | 1         | 0.41%   |
| Sharp LCD SHP10C9 1920x540                                                | 1         | 0.41%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                   | 1         | 0.41%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.41%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 95        | 41.67%  |
| 1920x1080 (FHD)    | 88        | 38.6%   |
| 1600x900 (HD+)     | 9         | 3.95%   |
| 1280x800 (WXGA)    | 9         | 3.95%   |
| 3840x2160 (4K)     | 5         | 2.19%   |
| 2560x1440 (QHD)    | 4         | 1.75%   |
| 2160x1440          | 3         | 1.32%   |
| 1920x1200 (WUXGA)  | 3         | 1.32%   |
| 1024x768 (XGA)     | 2         | 0.88%   |
| 800x1280           | 1         | 0.44%   |
| 2560x1600          | 1         | 0.44%   |
| 2560x1080          | 1         | 0.44%   |
| 2240x1400          | 1         | 0.44%   |
| 1920x540           | 1         | 0.44%   |
| 1680x1050 (WSXGA+) | 1         | 0.44%   |
| 1440x900 (WXGA+)   | 1         | 0.44%   |
| 1360x768           | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |
| 1024x600           | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 81        | 33.61%  |
| 14      | 55        | 22.82%  |
| 13      | 38        | 15.77%  |
| 23      | 12        | 4.98%   |
| 24      | 9         | 3.73%   |
| 17      | 7         | 2.9%    |
| 12      | 6         | 2.49%   |
| 27      | 5         | 2.07%   |
| 11      | 5         | 2.07%   |
| 31      | 3         | 1.24%   |
| 21      | 3         | 1.24%   |
| 72      | 2         | 0.83%   |
| 52      | 2         | 0.83%   |
| 7       | 2         | 0.83%   |
| Unknown | 2         | 0.83%   |
| 84      | 1         | 0.41%   |
| 65      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |
| 18      | 1         | 0.41%   |
| 16      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 160       | 66.39%  |
| 501-600     | 25        | 10.37%  |
| 201-300     | 24        | 9.96%   |
| 351-400     | 10        | 4.15%   |
| 401-500     | 6         | 2.49%   |
| 601-700     | 5         | 2.07%   |
| 1501-2000   | 3         | 1.24%   |
| 1001-1500   | 3         | 1.24%   |
| Unknown     | 2         | 0.83%   |
| 701-800     | 1         | 0.41%   |
| 101-200     | 1         | 0.41%   |
| 1-100       | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 180       | 87.38%  |
| 16/10   | 15        | 7.28%   |
| 3/2     | 5         | 2.43%   |
| 4/3     | 1         | 0.49%   |
| 32/9    | 1         | 0.49%   |
| 21/9    | 1         | 0.49%   |
| 1.00    | 1         | 0.49%   |
| 0.67    | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 85        | 35.27%  |
| 101-110        | 81        | 33.61%  |
| 201-250        | 21        | 8.71%   |
| 71-80          | 8         | 3.32%   |
| 121-130        | 7         | 2.9%    |
| More than 1000 | 6         | 2.49%   |
| 61-70          | 6         | 2.49%   |
| 51-60          | 5         | 2.07%   |
| 301-350        | 5         | 2.07%   |
| 351-500        | 4         | 1.66%   |
| 251-300        | 4         | 1.66%   |
| 1-40           | 2         | 0.83%   |
| 151-200        | 2         | 0.83%   |
| Unknown        | 2         | 0.83%   |
| 41-50          | 1         | 0.41%   |
| 141-150        | 1         | 0.41%   |
| 111-120        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 92        | 38.82%  |
| 121-160       | 89        | 37.55%  |
| 51-100        | 37        | 15.61%  |
| 161-240       | 10        | 4.22%   |
| 1-50          | 6         | 2.53%   |
| Unknown       | 2         | 0.84%   |
| More than 240 | 1         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 168       | 78.5%   |
| 2     | 43        | 20.09%  |
| 0     | 3         | 1.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 120       | 33.99%  |
| Intel                           | 104       | 29.46%  |
| Qualcomm Atheros                | 62        | 17.56%  |
| Broadcom                        | 20        | 5.67%   |
| MediaTek                        | 7         | 1.98%   |
| TP-Link                         | 5         | 1.42%   |
| Ralink Technology               | 5         | 1.42%   |
| Ralink                          | 4         | 1.13%   |
| Broadcom Limited                | 4         | 1.13%   |
| Xiaomi                          | 3         | 0.85%   |
| Huawei Technologies             | 3         | 0.85%   |
| ASIX Electronics                | 3         | 0.85%   |
| Nvidia                          | 2         | 0.57%   |
| Samsung Electronics             | 1         | 0.28%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| OPPO Electronics                | 1         | 0.28%   |
| Marvell Technology Group        | 1         | 0.28%   |
| JMicron Technology              | 1         | 0.28%   |
| InterBiometrics                 | 1         | 0.28%   |
| Hewlett-Packard                 | 1         | 0.28%   |
| DisplayLink                     | 1         | 0.28%   |
| D-Link                          | 1         | 0.28%   |
| Attansic Technology             | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 18.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 5.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 1.68%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.68%   |
| Intel Wireless 7265                                               | 7         | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.2%    |
| Realtek 802.11ac NIC                                              | 5         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.2%    |
| Intel Centrino Wireless-N 2230                                    | 5         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.96%   |
| Intel Wireless 3160                                               | 4         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.96%   |
| TP-Link 802.11n NIC                                               | 3         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.72%   |
| Intel Wireless-AC 9260                                            | 3         | 0.72%   |
| Intel Wireless 7260                                               | 3         | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.72%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.72%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.72%   |
| Huawei LLD-L21                                                    | 3         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 43.75%  |
| Qualcomm Atheros                | 52        | 23.21%  |
| Realtek Semiconductor           | 32        | 14.29%  |
| Broadcom                        | 15        | 6.7%    |
| MediaTek                        | 7         | 3.13%   |
| TP-Link                         | 5         | 2.23%   |
| Ralink Technology               | 5         | 2.23%   |
| Ralink                          | 4         | 1.79%   |
| Broadcom Limited                | 3         | 1.34%   |
| Qualcomm Atheros Communications | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |
| ASUSTek Computer                | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 5.75%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 5.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 4.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 3.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 3.1%    |
| Intel Wireless 8265 / 8275                                     | 7         | 3.1%    |
| Intel Wireless 7265                                            | 7         | 3.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.21%   |
| Realtek 802.11ac NIC                                           | 5         | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 2.21%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 1.77%   |
| Intel Wireless 3160                                            | 4         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.77%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.77%   |
| TP-Link 802.11n NIC                                            | 3         | 1.33%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.33%   |
| Intel Wireless-AC 9260                                         | 3         | 1.33%   |
| Intel Wireless 7260                                            | 3         | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.33%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 1.33%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.33%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.88%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.88%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.88%   |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.88%   |
| Intel Wireless 3165                                            | 2         | 0.88%   |
| Intel WiFi Link 5100                                           | 2         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 57.3%   |
| Intel                    | 38        | 20.54%  |
| Qualcomm Atheros         | 15        | 8.11%   |
| Broadcom                 | 8         | 4.32%   |
| Xiaomi                   | 3         | 1.62%   |
| Huawei Technologies      | 3         | 1.62%   |
| ASIX Electronics         | 3         | 1.62%   |
| Nvidia                   | 2         | 1.08%   |
| Samsung Electronics      | 1         | 0.54%   |
| OPPO Electronics         | 1         | 0.54%   |
| Marvell Technology Group | 1         | 0.54%   |
| JMicron Technology       | 1         | 0.54%   |
| DisplayLink              | 1         | 0.54%   |
| Broadcom Limited         | 1         | 0.54%   |
| Attansic Technology      | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 76        | 40.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 12.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 6.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 2.66%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 2.13%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 2.13%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.6%    |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.6%    |
| Huawei LLD-L21                                                                 | 3         | 1.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 1.06%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.53%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.53%   |
| OPPO CPH2411                                                                   | 1         | 0.53%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.53%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.53%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (14) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 205       | 53.25%  |
| Ethernet | 178       | 46.23%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 79%     |
| Ethernet | 46        | 21%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 161       | 76.3%   |
| 1     | 44        | 20.85%  |
| 0     | 4         | 1.9%    |
| 3     | 2         | 0.95%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 146       | 66.97%  |
| Yes  | 72        | 33.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 40.68%  |
| Realtek Semiconductor           | 16        | 9.04%   |
| Qualcomm Atheros Communications | 15        | 8.47%   |
| IMC Networks                    | 14        | 7.91%   |
| Foxconn / Hon Hai               | 12        | 6.78%   |
| Broadcom                        | 11        | 6.21%   |
| Lite-On Technology              | 10        | 5.65%   |
| Dell                            | 5         | 2.82%   |
| Apple                           | 5         | 2.82%   |
| Hewlett-Packard                 | 4         | 2.26%   |
| Realtek                         | 3         | 1.69%   |
| Ralink                          | 2         | 1.13%   |
| MediaTek                        | 2         | 1.13%   |
| Cambridge Silicon Radio         | 2         | 1.13%   |
| Ralink Technology               | 1         | 0.56%   |
| ASUSTek Computer                | 1         | 0.56%   |
| Askey Computer                  | 1         | 0.56%   |
| Alps Electric                   | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 13.56%  |
| Intel AX200 Bluetooth                                                               | 12        | 6.78%   |
| Intel AX201 Bluetooth                                                               | 10        | 5.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 5.08%   |
| Realtek Bluetooth Radio                                                             | 8         | 4.52%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 3.95%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 2.82%   |
| IMC Networks Bluetooth Device                                                       | 5         | 2.82%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.26%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 2.26%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.26%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.26%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.26%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.69%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.69%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.69%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.13%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.13%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.13%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.13%   |
| Intel Bluetooth Device                                                              | 2         | 1.13%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.13%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.13%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.13%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.13%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.13%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 1.13%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.13%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.13%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.56%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.56%   |
| Ralink CSR BS8510                                                                   | 1         | 0.56%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 166       | 65.35%  |
| AMD                    | 42        | 16.54%  |
| Nvidia                 | 33        | 12.99%  |
| C-Media Electronics    | 3         | 1.18%   |
| Samsung Electronics    | 2         | 0.79%   |
| Realtek Semiconductor  | 2         | 0.79%   |
| RODE Microphones       | 1         | 0.39%   |
| Plantronics            | 1         | 0.39%   |
| MVSILICON.INC.         | 1         | 0.39%   |
| MosArt Semiconductor   | 1         | 0.39%   |
| Generalplus Technology | 1         | 0.39%   |
| Cambridge Audio        | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 7.96%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 7.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 7.32%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 6.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 4.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 3.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 10        | 3.18%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.55%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 2.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.55%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.59%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.27%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.27%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.96%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.64%   |
| Nvidia Audio device                                                                               | 2         | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 25.85%  |
| Kingston            | 36        | 24.49%  |
| SK hynix            | 28        | 19.05%  |
| Micron Technology   | 12        | 8.16%   |
| Nanya Technology    | 7         | 4.76%   |
| A-DATA Technology   | 5         | 3.4%    |
| Ramaxel Technology  | 4         | 2.72%   |
| Apacer              | 4         | 2.72%   |
| Unknown (ABCD)      | 2         | 1.36%   |
| Unknown             | 2         | 1.36%   |
| Elpida              | 2         | 1.36%   |
| Crucial             | 2         | 1.36%   |
| Unknown (08AE)      | 1         | 0.68%   |
| Transcend           | 1         | 0.68%   |
| Team                | 1         | 0.68%   |
| Silicon Power       | 1         | 0.68%   |
| Kingmax             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.97%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 1.97%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.32%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 1.32%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.32%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.32%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 2         | 1.32%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 1.32%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1333MT/s               | 1         | 0.66%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.66%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.66%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.66%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT325S6EFR8C-PB 2048MB SODIMM DDR3                 | 1         | 0.66%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT112S6TFR8C-H9 1024MB SODIMM DDR3 1333MT/s        | 1         | 0.66%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 50        | 45.45%  |
| DDR4   | 47        | 42.73%  |
| LPDDR4 | 3         | 2.73%   |
| LPDDR3 | 3         | 2.73%   |
| SDRAM  | 2         | 1.82%   |
| DDR5   | 2         | 1.82%   |
| DDR2   | 2         | 1.82%   |
| DDR    | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 95.41%  |
| Row Of Chips | 5         | 4.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 50        | 39.68%  |
| 8192  | 39        | 30.95%  |
| 16384 | 14        | 11.11%  |
| 2048  | 13        | 10.32%  |
| 32768 | 6         | 4.76%   |
| 1024  | 4         | 3.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 23.2%   |
| 2667    | 23        | 18.4%   |
| 3200    | 19        | 15.2%   |
| 1334    | 15        | 12%     |
| 2400    | 8         | 6.4%    |
| 1333    | 8         | 6.4%    |
| 2133    | 6         | 4.8%    |
| 1067    | 3         | 2.4%    |
| 4800    | 2         | 1.6%    |
| 4199    | 2         | 1.6%    |
| 800     | 2         | 1.6%    |
| 667     | 2         | 1.6%    |
| 8400    | 1         | 0.8%    |
| 5600    | 1         | 0.8%    |
| 3333    | 1         | 0.8%    |
| 3266    | 1         | 0.8%    |
| 2134    | 1         | 0.8%    |
| Unknown | 1         | 0.8%    |

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
| Chicony Electronics                    | 38        | 20.88%  |
| Microdia                               | 24        | 13.19%  |
| IMC Networks                           | 20        | 10.99%  |
| Realtek Semiconductor                  | 14        | 7.69%   |
| Sunplus Innovation Technology          | 13        | 7.14%   |
| Suyin                                  | 11        | 6.04%   |
| Bison Electronics                      | 9         | 4.95%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.4%    |
| Quanta                                 | 6         | 3.3%    |
| Apple                                  | 5         | 2.75%   |
| Alcor Micro                            | 4         | 2.2%    |
| Acer                                   | 4         | 2.2%    |
| Syntek                                 | 3         | 1.65%   |
| Silicon Motion                         | 3         | 1.65%   |
| Luxvisions Innotech Limited            | 3         | 1.65%   |
| Logitech                               | 2         | 1.1%    |
| Lite-On Technology                     | 2         | 1.1%    |
| Generalplus Technology                 | 2         | 1.1%    |
| Z-Star Microelectronics                | 1         | 0.55%   |
| YGTek                                  | 1         | 0.55%   |
| USB Camera                             | 1         | 0.55%   |
| Sonix Technology                       | 1         | 0.55%   |
| Samsung Electronics                    | 1         | 0.55%   |
| Ricoh                                  | 1         | 0.55%   |
| Primax Electronics                     | 1         | 0.55%   |
| OmniVision Technologies                | 1         | 0.55%   |
| Lenovo                                 | 1         | 0.55%   |
| eMPIA Technology                       | 1         | 0.55%   |
| Cubeternet                             | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 10        | 5.49%   |
| Chicony USB2.0 VGA UVC WebCam                           | 8         | 4.4%    |
| Chicony Integrated Camera                               | 5         | 2.75%   |
| Chicony HD WebCam                                       | 5         | 2.75%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 2.2%    |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 2.2%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 2.2%    |
| Chicony USB2.0 HD UVC WebCam                            | 4         | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 2.2%    |
| Realtek Integrated_Webcam_HD                            | 3         | 1.65%   |
| IMC Networks Integrated Camera                          | 3         | 1.65%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.65%   |
| Chicony HP HD Webcam                                    | 3         | 1.65%   |
| Apple FaceTime HD Camera                                | 3         | 1.65%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 1.1%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 1.1%    |
| Suyin 1.3M HD WebCam                                    | 2         | 1.1%    |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.1%    |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 1.1%    |
| Realtek USB Camera                                      | 2         | 1.1%    |
| Realtek HD WebCam                                       | 2         | 1.1%    |
| Quanta HP TrueVision HD Camera                          | 2         | 1.1%    |
| Quanta HD Webcam                                        | 2         | 1.1%    |
| Microdia Webcam Vitade AF                               | 2         | 1.1%    |
| Microdia USB 2.0 Camera                                 | 2         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 1.1%    |
| IMC Networks ov9734_azurewave_camera                    | 2         | 1.1%    |
| Bison Integrated Camera                                 | 2         | 1.1%    |
| Bison BisonCam,NB Pro                                   | 2         | 1.1%    |
| Alcor Micro Asus Integrated Webcam                      | 2         | 1.1%    |
| Acer Lenovo Integrated Webcam                           | 2         | 1.1%    |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.55%   |
| YGTek Webcam                                            | 1         | 0.55%   |
| USB Camera USB Camera                                   | 1         | 0.55%   |
| Syntek USB Camera Device                                | 1         | 0.55%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.55%   |
| Syntek Laptop_Integrated_Webcam_1.3M                    | 1         | 0.55%   |
| Suyin Webcam-101                                        | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 24.14%  |
| Synaptics                  | 6         | 20.69%  |
| Shenzhen Goodix Technology | 6         | 20.69%  |
| Elan Microelectronics      | 3         | 10.34%  |
| AuthenTec                  | 3         | 10.34%  |
| Upek                       | 2         | 6.9%    |
| LighTuning Technology      | 1         | 3.45%   |
| Focal-systems.Corp         | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                     | 3         | 10.34%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 6.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 6.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 6.9%    |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 6.9%    |
| Elan ELAN:ARM-M4                                       | 2         | 6.9%    |
| Validity Sensors VFS491                                | 1         | 3.45%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.45%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.45%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 3.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.45%   |
| Shenzhen Goodix FingerPrint                            | 1         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.45%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 3.45%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.45%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.45%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 75%     |
| O2 Micro    | 1         | 8.33%   |
| Lenovo      | 1         | 8.33%   |
| Alcor Micro | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 16.67%  |
| Broadcom 58200                                                               | 2         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 143       | 66.82%  |
| 1     | 59        | 27.57%  |
| 2     | 11        | 5.14%   |
| 4     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 35.37%  |
| Graphics card            | 15        | 18.29%  |
| Net/wireless             | 11        | 13.41%  |
| Chipcard                 | 10        | 12.2%   |
| Multimedia controller    | 5         | 6.1%    |
| Storage                  | 3         | 3.66%   |
| Bluetooth                | 3         | 3.66%   |
| Net/ethernet             | 2         | 2.44%   |
| Storage/ide              | 1         | 1.22%   |
| Communication controller | 1         | 1.22%   |
| Card reader              | 1         | 1.22%   |
| Camera                   | 1         | 1.22%   |

