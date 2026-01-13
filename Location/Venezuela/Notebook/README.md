Linux in Venezuela - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Venezuela.

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

Total: 450

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| VIT           | P2400                       | [06b4179915](https://linux-hardware.org/?probe=06b4179915) | Dec 28, 2025 |
| Lenovo        | G570 4334                   | [c01a5acaba](https://linux-hardware.org/?probe=c01a5acaba) | Dec 27, 2025 |
| Google        | Kefka                       | [ab86cb8b18](https://linux-hardware.org/?probe=ab86cb8b18) | Dec 15, 2025 |
| Google        | Snappy                      | [030aaf60c7](https://linux-hardware.org/?probe=030aaf60c7) | Dec 11, 2025 |
| Google        | Kip                         | [9e9179cdfa](https://linux-hardware.org/?probe=9e9179cdfa) | Dec 02, 2025 |
| Intel         | powered classmate PC        | [908b265f69](https://linux-hardware.org/?probe=908b265f69) | Nov 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [ec48295277](https://linux-hardware.org/?probe=ec48295277) | Nov 26, 2025 |
| Acer          | Aspire E5-772G              | [3fa36dfc52](https://linux-hardware.org/?probe=3fa36dfc52) | Nov 25, 2025 |
| Lenovo        | 3000 C200 8922A11           | [d73699a81d](https://linux-hardware.org/?probe=d73699a81d) | Nov 24, 2025 |
| VIT           | P2423                       | [3c0d5f3fd5](https://linux-hardware.org/?probe=3c0d5f3fd5) | Nov 24, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [c631ddabce](https://linux-hardware.org/?probe=c631ddabce) | Nov 19, 2025 |
| Intel         | powered classmate PC        | [d7748a0615](https://linux-hardware.org/?probe=d7748a0615) | Nov 18, 2025 |
| VIT           | P2400                       | [fd53bea2e1](https://linux-hardware.org/?probe=fd53bea2e1) | Nov 17, 2025 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [51b6a544ae](https://linux-hardware.org/?probe=51b6a544ae) | Nov 14, 2025 |
| VIT           | P2402                       | [ddeae1a037](https://linux-hardware.org/?probe=ddeae1a037) | Nov 09, 2025 |
| VIT           | P2402                       | [84f67246f0](https://linux-hardware.org/?probe=84f67246f0) | Nov 09, 2025 |
| Acer          | Aspire 4738                 | [1285b4747a](https://linux-hardware.org/?probe=1285b4747a) | Nov 07, 2025 |
| Google        | Snappy                      | [c8c1a089bc](https://linux-hardware.org/?probe=c8c1a089bc) | Nov 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [e467785208](https://linux-hardware.org/?probe=e467785208) | Nov 04, 2025 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [0e1f1d4129](https://linux-hardware.org/?probe=0e1f1d4129) | Nov 02, 2025 |
| HP            | Notebook                    | [bc93d021e5](https://linux-hardware.org/?probe=bc93d021e5) | Nov 01, 2025 |
| Intel         | powered classmate PC        | [90449b5651](https://linux-hardware.org/?probe=90449b5651) | Oct 31, 2025 |
| Intel         | powered classmate PC        | [3d6aac569c](https://linux-hardware.org/?probe=3d6aac569c) | Oct 31, 2025 |
| Dell          | Latitude E5450              | [7db3cec12e](https://linux-hardware.org/?probe=7db3cec12e) | Oct 30, 2025 |
| Sragon        | LNS-35                      | [c139009876](https://linux-hardware.org/?probe=c139009876) | Oct 26, 2025 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [5ec78f225c](https://linux-hardware.org/?probe=5ec78f225c) | Oct 19, 2025 |
| VIT           | P2400                       | [b9faaf3b3b](https://linux-hardware.org/?probe=b9faaf3b3b) | Oct 19, 2025 |
| HP            | 240 14 inch G9 Notebook ... | [3067d71c0b](https://linux-hardware.org/?probe=3067d71c0b) | Oct 10, 2025 |
| Lenovo        | ThinkPad T460s 20F9003GU... | [d448919f4c](https://linux-hardware.org/?probe=d448919f4c) | Oct 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [98ff2b5e5a](https://linux-hardware.org/?probe=98ff2b5e5a) | Oct 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f3b787b4aa](https://linux-hardware.org/?probe=f3b787b4aa) | Oct 02, 2025 |
| Dell          | Inspiron 3593               | [2dcedfbc0b](https://linux-hardware.org/?probe=2dcedfbc0b) | Sep 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [6006d93c61](https://linux-hardware.org/?probe=6006d93c61) | Sep 24, 2025 |
| Intel         | powered classmate PC        | [8ce9d4faa7](https://linux-hardware.org/?probe=8ce9d4faa7) | Sep 17, 2025 |
| Lenovo        | ThinkPad SL 2743A64         | [c15fa15fb8](https://linux-hardware.org/?probe=c15fa15fb8) | Sep 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [bbaabb417a](https://linux-hardware.org/?probe=bbaabb417a) | Sep 16, 2025 |
| Toshiba       | Satellite L745              | [6483d48ae3](https://linux-hardware.org/?probe=6483d48ae3) | Sep 10, 2025 |
| Toshiba       | Satellite L745              | [7734659711](https://linux-hardware.org/?probe=7734659711) | Sep 10, 2025 |
| Pegatron      | T14AF                       | [7a2ea20409](https://linux-hardware.org/?probe=7a2ea20409) | Sep 08, 2025 |
| Acer          | Aspire 4349                 | [92f5c5cdb4](https://linux-hardware.org/?probe=92f5c5cdb4) | Sep 07, 2025 |
| Intel         | powered classmate PC        | [b67e49d0c4](https://linux-hardware.org/?probe=b67e49d0c4) | Sep 06, 2025 |
| Intel         | powered classmate PC        | [6607a895a8](https://linux-hardware.org/?probe=6607a895a8) | Sep 06, 2025 |
| Acer          | Aspire F5-573               | [93776373e9](https://linux-hardware.org/?probe=93776373e9) | Sep 04, 2025 |
| Google        | Snappy                      | [e0eb2fda47](https://linux-hardware.org/?probe=e0eb2fda47) | Sep 01, 2025 |
| Dell          | Latitude 5590               | [48ff62fa3d](https://linux-hardware.org/?probe=48ff62fa3d) | Sep 01, 2025 |
| Google        | Kip                         | [554ee0ddc2](https://linux-hardware.org/?probe=554ee0ddc2) | Sep 01, 2025 |
| Intel         | powered classmate PC        | [bb1166fdbb](https://linux-hardware.org/?probe=bb1166fdbb) | Aug 28, 2025 |
| Acer          | Acadia V1.42                | [7e8fb653ba](https://linux-hardware.org/?probe=7e8fb653ba) | Aug 26, 2025 |
| Google        | Kefka                       | [5a32bb48b8](https://linux-hardware.org/?probe=5a32bb48b8) | Aug 22, 2025 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [be9c88e521](https://linux-hardware.org/?probe=be9c88e521) | Aug 20, 2025 |
| Acer          | Nitro AN515-55              | [50c8188f48](https://linux-hardware.org/?probe=50c8188f48) | Aug 19, 2025 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [e08ef990bf](https://linux-hardware.org/?probe=e08ef990bf) | Aug 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [08b194d993](https://linux-hardware.org/?probe=08b194d993) | Aug 16, 2025 |
| Acer          | Aspire 4820T                | [842c09a29e](https://linux-hardware.org/?probe=842c09a29e) | Aug 02, 2025 |
| Google        | Snappy                      | [48014ee2d3](https://linux-hardware.org/?probe=48014ee2d3) | Aug 01, 2025 |
| Acer          | Nitro AN515-54              | [99d2dfe2c6](https://linux-hardware.org/?probe=99d2dfe2c6) | Jul 30, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [d3f704d7d4](https://linux-hardware.org/?probe=d3f704d7d4) | Jul 29, 2025 |
| Dell          | Inspiron 14-3452            | [4d999de986](https://linux-hardware.org/?probe=4d999de986) | Jul 29, 2025 |
| Samsung       | 700T                        | [7ee6eef65e](https://linux-hardware.org/?probe=7ee6eef65e) | Jul 22, 2025 |
| Samsung       | 700T                        | [336a818b03](https://linux-hardware.org/?probe=336a818b03) | Jul 22, 2025 |
| Google        | Snappy                      | [f89d21f82d](https://linux-hardware.org/?probe=f89d21f82d) | Jul 13, 2025 |
| VIT           | M2420                       | [0c5032bd9c](https://linux-hardware.org/?probe=0c5032bd9c) | Jul 07, 2025 |
| Google        | Snappy                      | [95aa640646](https://linux-hardware.org/?probe=95aa640646) | Jul 03, 2025 |
| GPD           | G1618-04                    | [c6f5267a38](https://linux-hardware.org/?probe=c6f5267a38) | Jul 02, 2025 |
| Google        | Snappy                      | [688518658e](https://linux-hardware.org/?probe=688518658e) | Jun 29, 2025 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | [90ac1e0838](https://linux-hardware.org/?probe=90ac1e0838) | Jun 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [cde4bff7fb](https://linux-hardware.org/?probe=cde4bff7fb) | Jun 23, 2025 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [f462643005](https://linux-hardware.org/?probe=f462643005) | Jun 21, 2025 |
| Intel         | powered classmate PC        | [3ecfa42007](https://linux-hardware.org/?probe=3ecfa42007) | Jun 14, 2025 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [0b76d41f56](https://linux-hardware.org/?probe=0b76d41f56) | Jun 10, 2025 |
| Apple         | MacBook5,1                  | [f3336d6280](https://linux-hardware.org/?probe=f3336d6280) | Jun 09, 2025 |
| Toshiba       | Satellite L755              | [71bdfd3432](https://linux-hardware.org/?probe=71bdfd3432) | Jun 04, 2025 |
| VIT           | P2400                       | [b9eb70e6ff](https://linux-hardware.org/?probe=b9eb70e6ff) | Jun 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [5dd519b897](https://linux-hardware.org/?probe=5dd519b897) | May 30, 2025 |
| Lenovo        | 3000 N200 0769AL3           | [1cc8a86b76](https://linux-hardware.org/?probe=1cc8a86b76) | May 29, 2025 |
| MSI           | CR420                       | [81e0b6440d](https://linux-hardware.org/?probe=81e0b6440d) | May 27, 2025 |
| HP            | 240 G5 Notebook PC          | [5a8a63d14c](https://linux-hardware.org/?probe=5a8a63d14c) | May 27, 2025 |
| Acer          | Aspire A315-44P             | [d05868bfa0](https://linux-hardware.org/?probe=d05868bfa0) | May 14, 2025 |
| Acer          | AOD255E                     | [0189da59d8](https://linux-hardware.org/?probe=0189da59d8) | May 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [bd6350f646](https://linux-hardware.org/?probe=bd6350f646) | May 02, 2025 |
| GPU Compan... | GWTN156-11                  | [c03e880a2f](https://linux-hardware.org/?probe=c03e880a2f) | Apr 29, 2025 |
| ISONIC        | ISO-A1005                   | [cd33e5e059](https://linux-hardware.org/?probe=cd33e5e059) | Apr 28, 2025 |
| VIT           | P2412                       | [c8da164f1d](https://linux-hardware.org/?probe=c8da164f1d) | Apr 26, 2025 |
| Intel         | powered classmate PC        | [c6aa177848](https://linux-hardware.org/?probe=c6aa177848) | Apr 25, 2025 |
| Google        | Barla                       | [f2ed311b61](https://linux-hardware.org/?probe=f2ed311b61) | Apr 18, 2025 |
| Intel         | powered classmate PC        | [1264aeb13a](https://linux-hardware.org/?probe=1264aeb13a) | Apr 18, 2025 |
| Dell          | Latitude 5580               | [2066503c1a](https://linux-hardware.org/?probe=2066503c1a) | Apr 11, 2025 |
| Apple         | MacBookPro8,1               | [f5d98800c2](https://linux-hardware.org/?probe=f5d98800c2) | Apr 10, 2025 |
| Apple         | MacBookPro8,1               | [c9dceddcc8](https://linux-hardware.org/?probe=c9dceddcc8) | Apr 10, 2025 |
| Intel         | powered classmate PC        | [f073e0851e](https://linux-hardware.org/?probe=f073e0851e) | Apr 06, 2025 |
| PCSMART       | Cherry Trail CR             | [3ef82b97d3](https://linux-hardware.org/?probe=3ef82b97d3) | Apr 05, 2025 |
| HP            | Presario CQ42               | [6c3e4078ad](https://linux-hardware.org/?probe=6c3e4078ad) | Apr 03, 2025 |
| HP            | Notebook                    | [7238df7ac9](https://linux-hardware.org/?probe=7238df7ac9) | Apr 03, 2025 |
| HP            | 245 14 inch G9              | [9f79bf7878](https://linux-hardware.org/?probe=9f79bf7878) | Mar 25, 2025 |
| Dell          | Precision M4800             | [6661a2373d](https://linux-hardware.org/?probe=6661a2373d) | Mar 21, 2025 |
| Intel         | powered classmate PC        | [2b17e2c3d9](https://linux-hardware.org/?probe=2b17e2c3d9) | Mar 13, 2025 |
| Lenovo        | G570 4334                   | [60c4807171](https://linux-hardware.org/?probe=60c4807171) | Feb 23, 2025 |
| Acer          | Aspire E5-772G              | [d2f93afa88](https://linux-hardware.org/?probe=d2f93afa88) | Feb 23, 2025 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [2300a9dd81](https://linux-hardware.org/?probe=2300a9dd81) | Feb 21, 2025 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [322d6f53a4](https://linux-hardware.org/?probe=322d6f53a4) | Feb 21, 2025 |
| HP            | Compaq Presario CQ40        | [dacc554bff](https://linux-hardware.org/?probe=dacc554bff) | Feb 20, 2025 |
| HP            | Presario CQ43               | [996b08ec2c](https://linux-hardware.org/?probe=996b08ec2c) | Feb 19, 2025 |
| HP            | Unknown                     | [8f410bfcf9](https://linux-hardware.org/?probe=8f410bfcf9) | Feb 19, 2025 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [45d322e8e8](https://linux-hardware.org/?probe=45d322e8e8) | Feb 17, 2025 |
| Dell          | Latitude E5450              | [a184aa95e7](https://linux-hardware.org/?probe=a184aa95e7) | Feb 11, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [85aa7e8c1c](https://linux-hardware.org/?probe=85aa7e8c1c) | Feb 10, 2025 |
| HP            | Laptop 15-ef2xxx            | [2cd35b297c](https://linux-hardware.org/?probe=2cd35b297c) | Feb 05, 2025 |
| Acer          | AOD257                      | [a7bbedaebd](https://linux-hardware.org/?probe=a7bbedaebd) | Jan 27, 2025 |
| Dell          | Latitude 5280               | [2e94dd1fd8](https://linux-hardware.org/?probe=2e94dd1fd8) | Jan 25, 2025 |
| VIT           | M2420                       | [88b7e0cc41](https://linux-hardware.org/?probe=88b7e0cc41) | Jan 23, 2025 |
| HP            | Notebook                    | [78a7d38606](https://linux-hardware.org/?probe=78a7d38606) | Jan 23, 2025 |
| Lenovo        | 3000 V200 07642XU           | [9b8864c4e8](https://linux-hardware.org/?probe=9b8864c4e8) | Jan 17, 2025 |
| Lenovo        | G570 4334                   | [f0ba2c6a10](https://linux-hardware.org/?probe=f0ba2c6a10) | Jan 14, 2025 |
| Toshiba       | Satellite S55t-A            | [38b2d5c6be](https://linux-hardware.org/?probe=38b2d5c6be) | Jan 12, 2025 |
| Shanghai Z... | ZXE CRB                     | [efd56260d6](https://linux-hardware.org/?probe=efd56260d6) | Jan 09, 2025 |
| Lenovo        | ThinkPad T500 205663S       | [24065ecc35](https://linux-hardware.org/?probe=24065ecc35) | Jan 09, 2025 |
| HP            | 15                          | [103fcc3bea](https://linux-hardware.org/?probe=103fcc3bea) | Jan 09, 2025 |
| Unknown       | Unknown                     | [d526621027](https://linux-hardware.org/?probe=d526621027) | Jan 05, 2025 |
| HP            | Pavilion Laptop 15t-eg30... | [a2b911a2d0](https://linux-hardware.org/?probe=a2b911a2d0) | Jan 02, 2025 |
| Lenovo        | G570 4334                   | [3348b2741c](https://linux-hardware.org/?probe=3348b2741c) | Dec 30, 2024 |
| Lenovo        | G570 4334                   | [e3535c8fe8](https://linux-hardware.org/?probe=e3535c8fe8) | Dec 30, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [ccee342e62](https://linux-hardware.org/?probe=ccee342e62) | Dec 18, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [428715e96d](https://linux-hardware.org/?probe=428715e96d) | Dec 17, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [46f8c1934d](https://linux-hardware.org/?probe=46f8c1934d) | Dec 17, 2024 |
| Toshiba       | Satellite L645              | [8ce1185c95](https://linux-hardware.org/?probe=8ce1185c95) | Nov 30, 2024 |
| HP            | ProBook 650 G1              | [f75dc49b84](https://linux-hardware.org/?probe=f75dc49b84) | Nov 23, 2024 |
| HP            | ProBook 6450b               | [1dbb3a5dd9](https://linux-hardware.org/?probe=1dbb3a5dd9) | Nov 21, 2024 |
| Unknown       | Unknown                     | [1e1c1f6c27](https://linux-hardware.org/?probe=1e1c1f6c27) | Nov 19, 2024 |
| ASUSTek       | ROG Strix G614JI_G614JI     | [b73f3d838f](https://linux-hardware.org/?probe=b73f3d838f) | Nov 13, 2024 |
| Dell          | XPS MXC062                  | [971fc4620d](https://linux-hardware.org/?probe=971fc4620d) | Nov 11, 2024 |
| Siragon       | MN-50                       | [31e300c3fb](https://linux-hardware.org/?probe=31e300c3fb) | Oct 28, 2024 |
| UNIQCELL      | Q15.6                       | [18be8c706d](https://linux-hardware.org/?probe=18be8c706d) | Oct 11, 2024 |
| Dell          | Latitude E5450              | [6843a865fe](https://linux-hardware.org/?probe=6843a865fe) | Oct 07, 2024 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [34c10e27fb](https://linux-hardware.org/?probe=34c10e27fb) | Oct 03, 2024 |
| Toshiba       | Satellite C645              | [1a789a141f](https://linux-hardware.org/?probe=1a789a141f) | Sep 21, 2024 |
| Lenovo        | ThinkPad T410 2522G18       | [1165597d26](https://linux-hardware.org/?probe=1165597d26) | Sep 16, 2024 |
| VIT           | M2420                       | [6b9697ca39](https://linux-hardware.org/?probe=6b9697ca39) | Sep 11, 2024 |
| VIT           | M2420                       | [f36595500f](https://linux-hardware.org/?probe=f36595500f) | Sep 11, 2024 |
| Samsung       | 905S3G/906S3G/915S3G        | [b8407fb3c6](https://linux-hardware.org/?probe=b8407fb3c6) | Sep 08, 2024 |
| Google        | Relm                        | [a69f9fe43f](https://linux-hardware.org/?probe=a69f9fe43f) | Sep 05, 2024 |
| Acer          | Predator PT315-53           | [636347c33f](https://linux-hardware.org/?probe=636347c33f) | Sep 01, 2024 |
| MSI           | Cyborg 15 A12VF             | [f3409a16bc](https://linux-hardware.org/?probe=f3409a16bc) | Aug 21, 2024 |
| MSI           | Cyborg 15 A12VF             | [e8712ff63e](https://linux-hardware.org/?probe=e8712ff63e) | Aug 21, 2024 |
| Lenovo        | ThinkPad SL 2743A65         | [0ee47e6c13](https://linux-hardware.org/?probe=0ee47e6c13) | Aug 12, 2024 |
| VIT           | P2400                       | [b103ea6da4](https://linux-hardware.org/?probe=b103ea6da4) | Aug 12, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [636fdb4075](https://linux-hardware.org/?probe=636fdb4075) | Aug 05, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [14fae8137f](https://linux-hardware.org/?probe=14fae8137f) | Jul 25, 2024 |
| Dell          | Inspiron 5520               | [617fd7c71a](https://linux-hardware.org/?probe=617fd7c71a) | Jul 11, 2024 |
| Google        | Reks                        | [91715e189c](https://linux-hardware.org/?probe=91715e189c) | Jul 07, 2024 |
| Dell          | Latitude 5590               | [649a21d948](https://linux-hardware.org/?probe=649a21d948) | Jul 06, 2024 |
| Dell          | Precision 7720              | [26f2413f41](https://linux-hardware.org/?probe=26f2413f41) | Jul 04, 2024 |
| Dell          | Precision M4800             | [43ecd5fec8](https://linux-hardware.org/?probe=43ecd5fec8) | Jul 03, 2024 |
| Dell          | Latitude E6420              | [b39cf47b19](https://linux-hardware.org/?probe=b39cf47b19) | Jun 25, 2024 |
| Lenovo        | 3000 N200 0769AL3           | [47b20e869d](https://linux-hardware.org/?probe=47b20e869d) | Jun 22, 2024 |
| Dell          | Precision M4800             | [ef1ba678a3](https://linux-hardware.org/?probe=ef1ba678a3) | Jun 22, 2024 |
| VENEZOLANA... | VIT P2460-02                | [01054473b9](https://linux-hardware.org/?probe=01054473b9) | Jun 19, 2024 |
| Dell          | Latitude E6420              | [07364acb42](https://linux-hardware.org/?probe=07364acb42) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [b1f2bd7ee5](https://linux-hardware.org/?probe=b1f2bd7ee5) | Jun 11, 2024 |
| VENEZOLANA... | VIT P2460-02                | [6177f7ad15](https://linux-hardware.org/?probe=6177f7ad15) | Jun 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a639c86fe2](https://linux-hardware.org/?probe=a639c86fe2) | May 24, 2024 |
| Gigabyte      | AORUS 5 KB                  | [0083b70388](https://linux-hardware.org/?probe=0083b70388) | May 23, 2024 |
| HP            | 3115m                       | [45bdc53959](https://linux-hardware.org/?probe=45bdc53959) | May 14, 2024 |
| Notebook      | W54BL                       | [adb804fa7f](https://linux-hardware.org/?probe=adb804fa7f) | Apr 27, 2024 |
| Unknown       | Unknown                     | [5fda06b27d](https://linux-hardware.org/?probe=5fda06b27d) | Apr 26, 2024 |
| HP            | Pavilion m6                 | [7573d33d4f](https://linux-hardware.org/?probe=7573d33d4f) | Apr 04, 2024 |
| Toshiba       | Satellite A205              | [4fcbf3184c](https://linux-hardware.org/?probe=4fcbf3184c) | Apr 02, 2024 |
| VENEZOLANA... | VIT P2460-02                | [c6fc091713](https://linux-hardware.org/?probe=c6fc091713) | Mar 24, 2024 |
| Dell          | Precision M4800             | [9a66a454e2](https://linux-hardware.org/?probe=9a66a454e2) | Mar 17, 2024 |
| Dell          | Precision M4800             | [c38442b3dc](https://linux-hardware.org/?probe=c38442b3dc) | Mar 17, 2024 |
| Unknown       | Unknown                     | [d00c774230](https://linux-hardware.org/?probe=d00c774230) | Mar 16, 2024 |
| Google        | Kip                         | [3da64ae4ad](https://linux-hardware.org/?probe=3da64ae4ad) | Mar 11, 2024 |
| Google        | Kip                         | [a08197fa56](https://linux-hardware.org/?probe=a08197fa56) | Mar 11, 2024 |
| Acer          | Aspire A515-43              | [054ae2a4a5](https://linux-hardware.org/?probe=054ae2a4a5) | Mar 09, 2024 |
| Dell          | Inspiron N4010              | [0d25733cfa](https://linux-hardware.org/?probe=0d25733cfa) | Feb 27, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [46990d3920](https://linux-hardware.org/?probe=46990d3920) | Feb 17, 2024 |
| HP            | ProBook 650 G1              | [9b6886b2f0](https://linux-hardware.org/?probe=9b6886b2f0) | Feb 16, 2024 |
| HP            | ProBook 650 G1              | [d3d2fd6bda](https://linux-hardware.org/?probe=d3d2fd6bda) | Feb 16, 2024 |
| Lenovo        | 3000 N500 42336DS           | [7c23ebf66b](https://linux-hardware.org/?probe=7c23ebf66b) | Feb 13, 2024 |
| VIT           | P1400                       | [8cb8362e24](https://linux-hardware.org/?probe=8cb8362e24) | Feb 10, 2024 |
| VIT           | P3400                       | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| VIT           | P3400                       | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Dell          | Inspiron MXC061             | [a134206781](https://linux-hardware.org/?probe=a134206781) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [1ebab4d906](https://linux-hardware.org/?probe=1ebab4d906) | Jan 30, 2024 |
| Dell          | Inspiron 3531               | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| Google        | Fleex                       | [100ab93f52](https://linux-hardware.org/?probe=100ab93f52) | Jan 09, 2024 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [45b99e2412](https://linux-hardware.org/?probe=45b99e2412) | Jan 08, 2024 |
| Dell          | G16 7630                    | [71f36f8ed0](https://linux-hardware.org/?probe=71f36f8ed0) | Dec 24, 2023 |
| HP            | Pavilion dv5                | [cf88cdfeb2](https://linux-hardware.org/?probe=cf88cdfeb2) | Dec 18, 2023 |
| Google        | Candy                       | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| VIT           | P3400                       | [0564cdc52e](https://linux-hardware.org/?probe=0564cdc52e) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [55a44e9a14](https://linux-hardware.org/?probe=55a44e9a14) | Dec 05, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [88fba30cec](https://linux-hardware.org/?probe=88fba30cec) | Nov 21, 2023 |
| Notebook      | NL40_50CU                   | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| Dell          | Inspiron 15 3511            | [79b891b4df](https://linux-hardware.org/?probe=79b891b4df) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9c9733a5c4](https://linux-hardware.org/?probe=9c9733a5c4) | Nov 07, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e4d524b5b8](https://linux-hardware.org/?probe=e4d524b5b8) | Nov 07, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Intel         | powered classmate PC        | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| VIT           | P1400                       | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| Gateway       | NV57H                       | [141355e1e3](https://linux-hardware.org/?probe=141355e1e3) | Oct 09, 2023 |
| HP            | Compaq Presario C768        | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| VIT           | P2400                       | [1896f1962a](https://linux-hardware.org/?probe=1896f1962a) | Oct 06, 2023 |
| HP            | Pavilion m6                 | [2fb7dbd455](https://linux-hardware.org/?probe=2fb7dbd455) | Sep 09, 2023 |
| Acer          | Aspire A315-42              | [a0abff6d5f](https://linux-hardware.org/?probe=a0abff6d5f) | Sep 08, 2023 |
| VIT           | P2400                       | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| VENEZOLANA... | VIT P2460-02                | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| ASUSTek       | X540SA                      | [71b31f4a43](https://linux-hardware.org/?probe=71b31f4a43) | Aug 31, 2023 |
| Panasonic     | CF-31RECAXDR                | [2c021f93de](https://linux-hardware.org/?probe=2c021f93de) | Aug 30, 2023 |
| ASUSTek       | X540SA                      | [dd6f1d7cac](https://linux-hardware.org/?probe=dd6f1d7cac) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [fc59d4358f](https://linux-hardware.org/?probe=fc59d4358f) | Aug 26, 2023 |
| HP            | Pavilion dv5                | [8e621682ec](https://linux-hardware.org/?probe=8e621682ec) | Aug 25, 2023 |
| VIT           | P2402                       | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| HP            | Laptop 15-fc0xxx            | [52c59bb799](https://linux-hardware.org/?probe=52c59bb799) | Aug 16, 2023 |
| Siragon       | MN-50                       | [8eafa43cb5](https://linux-hardware.org/?probe=8eafa43cb5) | Aug 09, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Shanghai Z... | ZXE CRB                     | [da6bb4265c](https://linux-hardware.org/?probe=da6bb4265c) | Jul 20, 2023 |
| Acer          | Aspire 4750                 | [d1ef43e488](https://linux-hardware.org/?probe=d1ef43e488) | Jul 16, 2023 |
| SIRAGON       | LM-C100                     | [daef084233](https://linux-hardware.org/?probe=daef084233) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f2887fc32](https://linux-hardware.org/?probe=2f2887fc32) | Jul 15, 2023 |
| Lenovo        | G570 4334                   | [27a207ead6](https://linux-hardware.org/?probe=27a207ead6) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [c1da8fb79e](https://linux-hardware.org/?probe=c1da8fb79e) | Jul 08, 2023 |
| Dell          | Inspiron N4050              | [d5fa70cfda](https://linux-hardware.org/?probe=d5fa70cfda) | Jul 08, 2023 |
| Dell          | Latitude 7490               | [3734a0a9bf](https://linux-hardware.org/?probe=3734a0a9bf) | Jul 07, 2023 |
| Acer          | Aspire 6930                 | [772d3d7f4a](https://linux-hardware.org/?probe=772d3d7f4a) | Jul 04, 2023 |
| VIT           | P2423                       | [19242b2ddb](https://linux-hardware.org/?probe=19242b2ddb) | Jun 23, 2023 |
| Intel         | powered classmate PC        | [e530f037c6](https://linux-hardware.org/?probe=e530f037c6) | Jun 09, 2023 |
| VIT           | P2402                       | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| VIT           | P2400                       | [dca6cca8a2](https://linux-hardware.org/?probe=dca6cca8a2) | May 26, 2023 |
| Acer          | Aspire A514-55              | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| HP            | Laptop 17-cp0xxx            | [7f1bc5a99c](https://linux-hardware.org/?probe=7f1bc5a99c) | May 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [701fb0df1b](https://linux-hardware.org/?probe=701fb0df1b) | Apr 26, 2023 |
| HP            | Laptop 17-cp0xxx            | [7ba77e1842](https://linux-hardware.org/?probe=7ba77e1842) | Apr 23, 2023 |
| Dell          | Latitude E6430              | [e844bce31c](https://linux-hardware.org/?probe=e844bce31c) | Apr 23, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Samsung       | 905S3G/906S3G/915S3G        | [54af26ce93](https://linux-hardware.org/?probe=54af26ce93) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [98121ef614](https://linux-hardware.org/?probe=98121ef614) | Apr 14, 2023 |
| Lenovo        | 3000 V200 07642XU           | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| VIT           | P2402                       | [1c25795c2f](https://linux-hardware.org/?probe=1c25795c2f) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | EliteBook 840 G3            | [36f4574fd4](https://linux-hardware.org/?probe=36f4574fd4) | Apr 03, 2023 |
| Notebook      | W54BL                       | [5e3ba9b128](https://linux-hardware.org/?probe=5e3ba9b128) | Apr 01, 2023 |
| Intel         | powered classmate PC        | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Pegatron      | H36Y                        | [1757156f40](https://linux-hardware.org/?probe=1757156f40) | Mar 11, 2023 |
| Acer          | Aspire A715-76              | [c0c0d5447d](https://linux-hardware.org/?probe=c0c0d5447d) | Mar 09, 2023 |
| Pegatron      | H36Y                        | [8d9c3ebbc8](https://linux-hardware.org/?probe=8d9c3ebbc8) | Mar 09, 2023 |
| MSI           | GL73 9SD                    | [0913746f16](https://linux-hardware.org/?probe=0913746f16) | Mar 07, 2023 |
| VIT           | P1400                       | [3d31270e0d](https://linux-hardware.org/?probe=3d31270e0d) | Mar 07, 2023 |
| VIT           | P1400                       | [bed6aed6fa](https://linux-hardware.org/?probe=bed6aed6fa) | Mar 07, 2023 |
| Acer          | Aspire A715-76              | [b9f52dc0f3](https://linux-hardware.org/?probe=b9f52dc0f3) | Feb 27, 2023 |
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Dell          | Latitude E6430              | [23c0ff9281](https://linux-hardware.org/?probe=23c0ff9281) | Feb 19, 2023 |
| Dell          | Latitude E6430              | [d97087b55f](https://linux-hardware.org/?probe=d97087b55f) | Feb 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7fd55795a0](https://linux-hardware.org/?probe=7fd55795a0) | Feb 15, 2023 |
| Google        | Candy                       | [b2f2862759](https://linux-hardware.org/?probe=b2f2862759) | Feb 13, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Aspire 4739Z                | [cc795627da](https://linux-hardware.org/?probe=cc795627da) | Feb 10, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [c20b6ee7d2](https://linux-hardware.org/?probe=c20b6ee7d2) | Feb 04, 2023 |
| Dell          | Latitude E6430              | [10b3b0cfbb](https://linux-hardware.org/?probe=10b3b0cfbb) | Feb 03, 2023 |
| Dell          | Latitude E6430              | [55c398146b](https://linux-hardware.org/?probe=55c398146b) | Feb 01, 2023 |
| Lenovo        | ThinkPad SL 2743A65         | [89f744ff83](https://linux-hardware.org/?probe=89f744ff83) | Jan 22, 2023 |
| Dell          | Vostro 1220                 | [6cd42b6be3](https://linux-hardware.org/?probe=6cd42b6be3) | Jan 19, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Pegatron      | B74                         | [3e721dbe13](https://linux-hardware.org/?probe=3e721dbe13) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z580                | [6cb922bbdf](https://linux-hardware.org/?probe=6cb922bbdf) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [8e885883c6](https://linux-hardware.org/?probe=8e885883c6) | Jan 03, 2023 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [e0584a11c0](https://linux-hardware.org/?probe=e0584a11c0) | Dec 10, 2022 |
| Acer          | Aspire A315-42              | [68f683d29e](https://linux-hardware.org/?probe=68f683d29e) | Dec 06, 2022 |
| HP            | Mini 110-1100               | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| Lenovo        | 3000 N500 42336DS           | [f3d917b782](https://linux-hardware.org/?probe=f3d917b782) | Nov 26, 2022 |
| Intel         | powered classmate PC        | [d74f69f66a](https://linux-hardware.org/?probe=d74f69f66a) | Nov 22, 2022 |
| Dell          | Vostro 3550                 | [a195c7598f](https://linux-hardware.org/?probe=a195c7598f) | Nov 14, 2022 |
| Dell          | Vostro 3550                 | [2176ff6bc0](https://linux-hardware.org/?probe=2176ff6bc0) | Nov 14, 2022 |
| Acer          | Aspire 4739Z                | [d3ef4a43db](https://linux-hardware.org/?probe=d3ef4a43db) | Nov 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Google        | Candy                       | [af2c0be6ca](https://linux-hardware.org/?probe=af2c0be6ca) | Oct 17, 2022 |
| Google        | Candy                       | [ec740507fd](https://linux-hardware.org/?probe=ec740507fd) | Oct 17, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Toshiba       | ENCORE 2 WT8-B              | [b9cd7b49d3](https://linux-hardware.org/?probe=b9cd7b49d3) | Sep 23, 2022 |
| HP            | EliteBook 8760w             | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Gateway       | NV57H                       | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| Clevo         | W54xEU                      | [bd0c5962bd](https://linux-hardware.org/?probe=bd0c5962bd) | Sep 15, 2022 |
| Acer          | Aspire A515-44              | [ac687f4dcd](https://linux-hardware.org/?probe=ac687f4dcd) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| Dell          | Inspiron 3180               | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| VIT           | P2402                       | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| HP            | ProBook 440 G1              | [fc4f66c2de](https://linux-hardware.org/?probe=fc4f66c2de) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| VIT           | P2402                       | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| HP            | ProBook 440 G1              | [a0ebe8cf5a](https://linux-hardware.org/?probe=a0ebe8cf5a) | Jul 20, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b846c98a96](https://linux-hardware.org/?probe=b846c98a96) | Jul 08, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [dee20b535f](https://linux-hardware.org/?probe=dee20b535f) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eef50332e8](https://linux-hardware.org/?probe=eef50332e8) | Jul 02, 2022 |
| HP            | EliteBook 840 G3            | [d7282a0f61](https://linux-hardware.org/?probe=d7282a0f61) | Jun 29, 2022 |
| Dell          | Inspiron 5502               | [c3e90d4ebd](https://linux-hardware.org/?probe=c3e90d4ebd) | Jun 26, 2022 |
| Google        | Cyan                        | [7b82520717](https://linux-hardware.org/?probe=7b82520717) | Jun 13, 2022 |
| VIT           | M2420                       | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| VIT           | M2420                       | [c2ea650175](https://linux-hardware.org/?probe=c2ea650175) | Jun 01, 2022 |
| Dell          | Precision 7710              | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Acer          | TravelMate 5742Z            | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| Dell          | Inspiron 5520               | [0e7bf88677](https://linux-hardware.org/?probe=0e7bf88677) | May 19, 2022 |
| Dell          | XPS 15 7590                 | [8dc1b9cd87](https://linux-hardware.org/?probe=8dc1b9cd87) | May 14, 2022 |
| Unknown       | Unknown                     | [ff32f84c4e](https://linux-hardware.org/?probe=ff32f84c4e) | Apr 23, 2022 |
| Dell          | Inspiron 1545               | [8869defd9c](https://linux-hardware.org/?probe=8869defd9c) | Apr 22, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8510a8836c](https://linux-hardware.org/?probe=8510a8836c) | Apr 18, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [6c3ed980a1](https://linux-hardware.org/?probe=6c3ed980a1) | Apr 18, 2022 |
| Clevo         | W54xEU                      | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude 5590               | [ade3f33fb9](https://linux-hardware.org/?probe=ade3f33fb9) | Apr 16, 2022 |
| HP            | Pavilion dv5                | [22aa828b2f](https://linux-hardware.org/?probe=22aa828b2f) | Apr 16, 2022 |
| HP            | Compaq Presario C700        | [4f723964d5](https://linux-hardware.org/?probe=4f723964d5) | Apr 15, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3f66b1cb5c](https://linux-hardware.org/?probe=3f66b1cb5c) | Apr 13, 2022 |
| Dell          | Latitude 5590               | [1638db9ad7](https://linux-hardware.org/?probe=1638db9ad7) | Apr 13, 2022 |
| HP            | EliteBook 840 G3            | [659999d04a](https://linux-hardware.org/?probe=659999d04a) | Apr 11, 2022 |
| HP            | EliteBook 840 G3            | [227c3936b8](https://linux-hardware.org/?probe=227c3936b8) | Apr 09, 2022 |
| Dell          | Vostro 5402                 | [6cb82accd9](https://linux-hardware.org/?probe=6cb82accd9) | Apr 07, 2022 |
| Gateway       | NV57H                       | [ce2e78a407](https://linux-hardware.org/?probe=ce2e78a407) | Mar 31, 2022 |
| HP            | Laptop 15-ef2xxx            | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| VIT           | P2402                       | [5d9e3733ea](https://linux-hardware.org/?probe=5d9e3733ea) | Mar 21, 2022 |
| Dell          | Inspiron 5502               | [3dcc73772f](https://linux-hardware.org/?probe=3dcc73772f) | Mar 12, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [5fa0d18666](https://linux-hardware.org/?probe=5fa0d18666) | Mar 04, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| VIT           | P3400                       | [b90c32748d](https://linux-hardware.org/?probe=b90c32748d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X201 3680AE2       | [cb777c91bc](https://linux-hardware.org/?probe=cb777c91bc) | Feb 13, 2022 |
| HP            | Pavilion dv6500             | [16dbcf63f1](https://linux-hardware.org/?probe=16dbcf63f1) | Feb 12, 2022 |
| Gateway       | NV57H                       | [9d59228f90](https://linux-hardware.org/?probe=9d59228f90) | Feb 09, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [ac9ed3224d](https://linux-hardware.org/?probe=ac9ed3224d) | Feb 01, 2022 |
| MSI           | MS-1454                     | [1cb9a056e7](https://linux-hardware.org/?probe=1cb9a056e7) | Jan 14, 2022 |
| VIT           | M2421                       | [c6cc8a474d](https://linux-hardware.org/?probe=c6cc8a474d) | Jan 10, 2022 |
| UNIQCELL      | Q15.6                       | [d21e7048e1](https://linux-hardware.org/?probe=d21e7048e1) | Dec 20, 2021 |
| GPU Compan... | GWTN156-11                  | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| Intel         | powered classmate PC        | [0585f5b715](https://linux-hardware.org/?probe=0585f5b715) | Dec 12, 2021 |
| Intel         | powered classmate PC        | [9416f348e4](https://linux-hardware.org/?probe=9416f348e4) | Dec 12, 2021 |
| Lenovo        | B40-70 20392                | [4f4458d61a](https://linux-hardware.org/?probe=4f4458d61a) | Nov 23, 2021 |
| HP            | Pavilion dv6                | [2f83ccbc4f](https://linux-hardware.org/?probe=2f83ccbc4f) | Nov 21, 2021 |
| HP            | Pavilion dv6                | [a492e3e1ff](https://linux-hardware.org/?probe=a492e3e1ff) | Nov 21, 2021 |
| Unknown       | Unknown                     | [381b31199f](https://linux-hardware.org/?probe=381b31199f) | Nov 18, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [b37e3324e3](https://linux-hardware.org/?probe=b37e3324e3) | Nov 05, 2021 |
| VIT           | P3400                       | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Lenovo        | G570 4334                   | [d1d57448c4](https://linux-hardware.org/?probe=d1d57448c4) | Oct 29, 2021 |
| Lenovo        | G570 4334                   | [f5112dbf47](https://linux-hardware.org/?probe=f5112dbf47) | Oct 29, 2021 |
| Dell          | Latitude E7450              | [9cbd7f01e8](https://linux-hardware.org/?probe=9cbd7f01e8) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| ASUSTek       | X555DA                      | [903dc4ef05](https://linux-hardware.org/?probe=903dc4ef05) | Oct 13, 2021 |
| Clevo         | W54xEU                      | [a6732ab721](https://linux-hardware.org/?probe=a6732ab721) | Sep 30, 2021 |
| VIT           | P3400                       | [22260810d1](https://linux-hardware.org/?probe=22260810d1) | Sep 27, 2021 |
| ASUSTek       | TUF Gaming FA506IH_FA506... | [5854fbcaed](https://linux-hardware.org/?probe=5854fbcaed) | Sep 17, 2021 |
| Pegatron      | T14AF                       | [46067ec02a](https://linux-hardware.org/?probe=46067ec02a) | Sep 07, 2021 |
| Lenovo        | ThinkPad Edge 01962AS       | [8ccb24d0d8](https://linux-hardware.org/?probe=8ccb24d0d8) | Aug 24, 2021 |
| VIT           | P2400                       | [f844ffff09](https://linux-hardware.org/?probe=f844ffff09) | Aug 11, 2021 |
| Acer          | Aspire VX5-591G             | [c726cd767b](https://linux-hardware.org/?probe=c726cd767b) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c468ca84d3](https://linux-hardware.org/?probe=c468ca84d3) | Jun 30, 2021 |
| HP            | Pavilion dv6700             | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fc58981ecd](https://linux-hardware.org/?probe=fc58981ecd) | Jun 27, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bce9c74edb](https://linux-hardware.org/?probe=bce9c74edb) | Jun 27, 2021 |
| VIT           | P2400                       | [295d4d5a47](https://linux-hardware.org/?probe=295d4d5a47) | Jun 17, 2021 |
| VIT           | P1400                       | [129d543695](https://linux-hardware.org/?probe=129d543695) | Jun 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [423b514d2b](https://linux-hardware.org/?probe=423b514d2b) | May 30, 2021 |
| VIT           | P2400                       | [f39537fca1](https://linux-hardware.org/?probe=f39537fca1) | May 28, 2021 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [0f12ef1983](https://linux-hardware.org/?probe=0f12ef1983) | May 25, 2021 |
| VIT           | P2400                       | [4fa6d109de](https://linux-hardware.org/?probe=4fa6d109de) | May 25, 2021 |
| Sony          | VGN-FW510F                  | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| Intel         | powered classmate PC        | [a3b0d4e33e](https://linux-hardware.org/?probe=a3b0d4e33e) | May 12, 2021 |
| Lenovo        | G570 4334                   | [f16304ca03](https://linux-hardware.org/?probe=f16304ca03) | May 04, 2021 |
| Lenovo        | G570 4334                   | [8eca6b6f79](https://linux-hardware.org/?probe=8eca6b6f79) | May 04, 2021 |
| Lenovo        | G570 4334                   | [bef0f33897](https://linux-hardware.org/?probe=bef0f33897) | May 02, 2021 |
| Acer          | Aspire 4935                 | [cbe6a288f1](https://linux-hardware.org/?probe=cbe6a288f1) | Apr 06, 2021 |
| Toshiba       | Satellite E55t-A            | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Dell          | Vostro 1500                 | [76ade477e8](https://linux-hardware.org/?probe=76ade477e8) | Mar 28, 2021 |
| ASUSTek       | X555DA                      | [28996604f4](https://linux-hardware.org/?probe=28996604f4) | Mar 27, 2021 |
| ASUSTek       | X555DA                      | [e90c94fd9d](https://linux-hardware.org/?probe=e90c94fd9d) | Mar 27, 2021 |
| Dell          | Inspiron 5437               | [918f841c61](https://linux-hardware.org/?probe=918f841c61) | Mar 12, 2021 |
| HP            | 2000                        | [736561e497](https://linux-hardware.org/?probe=736561e497) | Mar 07, 2021 |
| Dell          | Inspiron 5437               | [4883c81a02](https://linux-hardware.org/?probe=4883c81a02) | Feb 07, 2021 |
| AVITA         | NS14A1US                    | [63ab85aac6](https://linux-hardware.org/?probe=63ab85aac6) | Feb 05, 2021 |
| Dell          | Inspiron 1018               | [570fb5f20b](https://linux-hardware.org/?probe=570fb5f20b) | Jan 27, 2021 |
| Dell          | Inspiron 1018               | [b481e5f8d2](https://linux-hardware.org/?probe=b481e5f8d2) | Jan 27, 2021 |
| Dell          | Inspiron 3180               | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [1d1e7e6236](https://linux-hardware.org/?probe=1d1e7e6236) | Nov 07, 2020 |
| Dell          | Inspiron 1545               | [31fa456854](https://linux-hardware.org/?probe=31fa456854) | Nov 07, 2020 |
| Exo           | AIO A210                    | [2082cc5386](https://linux-hardware.org/?probe=2082cc5386) | Nov 02, 2020 |
| Lenovo        | IdeaPad S110 20126          | [c172177266](https://linux-hardware.org/?probe=c172177266) | Oct 31, 2020 |
| ASUSTek       | X553MA                      | [8de08ff7ac](https://linux-hardware.org/?probe=8de08ff7ac) | Oct 24, 2020 |
| ASUSTek       | X553MA                      | [46849fa419](https://linux-hardware.org/?probe=46849fa419) | Oct 24, 2020 |
| Dell          | Inspiron 5437               | [0fa1b76517](https://linux-hardware.org/?probe=0fa1b76517) | Oct 15, 2020 |
| Lenovo        | G460 20041                  | [6944572eca](https://linux-hardware.org/?probe=6944572eca) | Oct 02, 2020 |
| Lenovo        | G460 20041                  | [1f4ffcafa7](https://linux-hardware.org/?probe=1f4ffcafa7) | Oct 02, 2020 |
| Dell          | Inspiron 5570               | [0d9041893c](https://linux-hardware.org/?probe=0d9041893c) | Sep 15, 2020 |
| Unknown       | Unknown                     | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | Presario V2000 (EW997LA#... | [77a2a0c00f](https://linux-hardware.org/?probe=77a2a0c00f) | Aug 15, 2020 |
| Alienware     | 17 R4                       | [c1a871b29b](https://linux-hardware.org/?probe=c1a871b29b) | Aug 14, 2020 |
| VIT           | M2421                       | [451969e0fc](https://linux-hardware.org/?probe=451969e0fc) | Jul 27, 2020 |
| Intel         | powered classmate PC        | [1ffa275c8b](https://linux-hardware.org/?probe=1ffa275c8b) | Jul 12, 2020 |
| Intel         | powered classmate PC        | [49442bdbca](https://linux-hardware.org/?probe=49442bdbca) | Jul 11, 2020 |
| HP            | Presario C700               | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| Unknown       | Unknown                     | [e8a608f296](https://linux-hardware.org/?probe=e8a608f296) | May 23, 2020 |
| VIT           | P3400                       | [48c981187d](https://linux-hardware.org/?probe=48c981187d) | May 18, 2020 |
| VIT           | P3400                       | [f9be2de38c](https://linux-hardware.org/?probe=f9be2de38c) | May 14, 2020 |
| HP            | Pavilion dv4                | [2efd349a3f](https://linux-hardware.org/?probe=2efd349a3f) | May 13, 2020 |
| VIT           | P2402                       | [bacbeb66bd](https://linux-hardware.org/?probe=bacbeb66bd) | May 07, 2020 |
| VIT           | P3400                       | [cd75b7e2c3](https://linux-hardware.org/?probe=cd75b7e2c3) | Apr 24, 2020 |
| VIT           | P2400                       | [4acb382140](https://linux-hardware.org/?probe=4acb382140) | Apr 23, 2020 |
| VIT           | M2420                       | [a7535d12dc](https://linux-hardware.org/?probe=a7535d12dc) | Apr 13, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [ebbf8f7b4e](https://linux-hardware.org/?probe=ebbf8f7b4e) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [e39e92a6f9](https://linux-hardware.org/?probe=e39e92a6f9) | Mar 20, 2020 |
| Lenovo        | ThinkPad SL400 2743A48      | [b9d2e7e174](https://linux-hardware.org/?probe=b9d2e7e174) | Mar 20, 2020 |
| VIT           | P2402                       | [9f90b82033](https://linux-hardware.org/?probe=9f90b82033) | Mar 10, 2020 |
| VIT           | P2402                       | [ea6b959930](https://linux-hardware.org/?probe=ea6b959930) | Mar 03, 2020 |
| Lenovo        | Z50-75 80EC                 | [79f0a68dd3](https://linux-hardware.org/?probe=79f0a68dd3) | Feb 26, 2020 |
| Lenovo        | IdeaPad S100c 20194         | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| Dell          | Inspiron 3421               | [17f334232d](https://linux-hardware.org/?probe=17f334232d) | Jan 01, 2020 |
| Intel         | powered classmate PC        | [b772cf9349](https://linux-hardware.org/?probe=b772cf9349) | Dec 11, 2019 |
| Intel         | powered classmate PC        | [b66f15db35](https://linux-hardware.org/?probe=b66f15db35) | Dec 11, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [7c2893dba4](https://linux-hardware.org/?probe=7c2893dba4) | Nov 15, 2019 |
| Lenovo        | IdeaPad S100c 20194         | [530c41513b](https://linux-hardware.org/?probe=530c41513b) | Sep 20, 2019 |
| Lenovo        | G480 20150                  | [1b7e674c82](https://linux-hardware.org/?probe=1b7e674c82) | May 08, 2019 |
| Lenovo        | G480 20150                  | [99198fbcfa](https://linux-hardware.org/?probe=99198fbcfa) | May 08, 2019 |
| HP            | Pavilion dv4                | [e59414c439](https://linux-hardware.org/?probe=e59414c439) | Apr 11, 2019 |
| Intel         | powered classmate PC        | [405f76133d](https://linux-hardware.org/?probe=405f76133d) | Oct 11, 2017 |
| Intel         | powered classmate PC        | [e79ec0466f](https://linux-hardware.org/?probe=e79ec0466f) | Oct 01, 2017 |
| Lenovo        | 3000 N200 0769ARS           | [1ada6660c3](https://linux-hardware.org/?probe=1ada6660c3) | Aug 15, 2017 |
| Lenovo        | 3000 N200 0769ARS           | [5548cd964f](https://linux-hardware.org/?probe=5548cd964f) | Jul 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 22.04       | 19        | 5.56%   |
| Debian 11          | 17        | 4.97%   |
| OpenMandriva 6.0   | 14        | 4.09%   |
| Ubuntu 20.04       | 13        | 3.8%    |
| Debian 12          | 10        | 2.92%   |
| OpenMandriva 4.3   | 8         | 2.34%   |
| Zorin 17           | 7         | 2.05%   |
| Fedora 41          | 7         | 2.05%   |
| OpenMandriva 23.08 | 6         | 1.75%   |
| Linux Mint 21.1    | 6         | 1.75%   |
| KDE neon 22.04     | 6         | 1.75%   |
| Debian 13          | 6         | 1.75%   |
| Debian 10          | 6         | 1.75%   |
| Arch Rolling       | 6         | 1.75%   |
| Zorin 16           | 5         | 1.46%   |
| Ubuntu 24.04       | 5         | 1.46%   |
| Ubuntu 18.04       | 5         | 1.46%   |
| OpenMandriva 25.90 | 5         | 1.46%   |
| Linux Mint 22.1    | 5         | 1.46%   |
| Kubuntu 20.04      | 5         | 1.46%   |
| KDE neon 20.04     | 5         | 1.46%   |
| Pop!_OS 22.04      | 4         | 1.17%   |
| OpenMandriva 4.2   | 4         | 1.17%   |
| OpenMandriva 24.12 | 4         | 1.17%   |
| OpenMandriva 24.07 | 4         | 1.17%   |
| Linux Mint 22.2    | 4         | 1.17%   |
| Linux Mint 21.3    | 4         | 1.17%   |
| Debian 23          | 4         | 1.17%   |
| Zorin 18           | 3         | 0.88%   |
| Xubuntu 22.04      | 3         | 0.88%   |
| Xubuntu 18.04      | 3         | 0.88%   |
| Ubuntu 23.10       | 3         | 0.88%   |
| ROSA R9            | 3         | 0.88%   |
| OpenMandriva 23.03 | 3         | 0.88%   |
| Linux Mint 21.2    | 3         | 0.88%   |
| Linux Mint 20.3    | 3         | 0.88%   |
| Fedora 39          | 3         | 0.88%   |
| Zorin 15           | 2         | 0.58%   |
| Ubuntu Unity 16.04 | 2         | 0.58%   |
| Ubuntu 21.10       | 2         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| OpenMandriva  | 55        | 17.19%  |
| Ubuntu        | 48        | 15%     |
| Debian        | 40        | 12.5%   |
| Linux Mint    | 29        | 9.06%   |
| Fedora        | 21        | 6.56%   |
| Zorin         | 17        | 5.31%   |
| KDE neon      | 12        | 3.75%   |
| Xubuntu       | 10        | 3.13%   |
| ROSA          | 8         | 2.5%    |
| Manjaro       | 7         | 2.19%   |
| Kubuntu       | 7         | 2.19%   |
| Arch          | 7         | 2.19%   |
| Pop!_OS       | 6         | 1.88%   |
| MX            | 4         | 1.25%   |
| Elementary    | 4         | 1.25%   |
| Ubuntu MATE   | 3         | 0.94%   |
| openSUSE      | 3         | 0.94%   |
| Nobara        | 3         | 0.94%   |
| Kali          | 3         | 0.94%   |
| Ubuntu Unity  | 2         | 0.63%   |
| TUXEDO OS     | 2         | 0.63%   |
| Lubuntu       | 2         | 0.63%   |
| LMDE          | 2         | 0.63%   |
| Linux Lite    | 2         | 0.63%   |
| EndeavourOS   | 2         | 0.63%   |
| Deepin        | 2         | 0.63%   |
| BigLinux      | 2         | 0.63%   |
| Bazzite       | 2         | 0.63%   |
| ArcoLinux     | 2         | 0.63%   |
| Xero          | 1         | 0.31%   |
| Ubuntu Budgie | 1         | 0.31%   |
| Solus         | 1         | 0.31%   |
| Rocky Linux   | 1         | 0.31%   |
| Q4OS          | 1         | 0.31%   |
| NixOS         | 1         | 0.31%   |
| Mabox         | 1         | 0.31%   |
| Lilidog       | 1         | 0.31%   |
| Garuda Linux  | 1         | 0.31%   |
| Feren OS      | 1         | 0.31%   |
| BunsenLabs    | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590  | 21        | 5.57%   |
| 5.16.7-desktop-1omv4003  | 8         | 2.12%   |
| 6.8.0-51-generic         | 4         | 1.06%   |
| 6.5.0-41-generic         | 4         | 1.06%   |
| 6.4.8-desktop-2omv2390   | 4         | 1.06%   |
| 6.14.0-35-generic        | 4         | 1.06%   |
| 6.12.48+deb13-amd64      | 4         | 1.06%   |
| 6.10.0-desktop-1omv2490  | 4         | 1.06%   |
| 5.4.0-42-generic         | 4         | 1.06%   |
| 5.15.0-46-generic        | 4         | 1.06%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.06%   |
| 5.10.0-23-amd64          | 4         | 1.06%   |
| 6.8.0-52-generic         | 3         | 0.8%    |
| 6.4.11-desktop-1omv2390  | 3         | 0.8%    |
| 6.2.6-desktop-1omv2390   | 3         | 0.8%    |
| 6.12.1-desktop-1omv2490  | 3         | 0.8%    |
| 5.4.0-73-generic         | 3         | 0.8%    |
| 5.4.0-52-generic         | 3         | 0.8%    |
| 5.3.0-40-generic         | 3         | 0.8%    |
| 5.15.0-76-generic        | 3         | 0.8%    |
| 5.15.0-67-generic        | 3         | 0.8%    |
| 5.15.0-56-generic        | 3         | 0.8%    |
| 5.13.0-39-generic        | 3         | 0.8%    |
| 5.10.0-13-amd64          | 3         | 0.8%    |
| 4.19.0-17-amd64          | 3         | 0.8%    |
| 6.8.0-79-generic         | 2         | 0.53%   |
| 6.8.0-53-generic         | 2         | 0.53%   |
| 6.8.0-48-generic         | 2         | 0.53%   |
| 6.8.0-40-generic         | 2         | 0.53%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.53%   |
| 6.4.11-arch2-1           | 2         | 0.53%   |
| 6.3.5-desktop-3omv2390   | 2         | 0.53%   |
| 6.2.0-26-generic         | 2         | 0.53%   |
| 6.14.0-34-generic        | 2         | 0.53%   |
| 6.14.0-33-generic        | 2         | 0.53%   |
| 6.13.9-200.fc41.x86_64   | 2         | 0.53%   |
| 6.12.48-1-MANJARO        | 2         | 0.53%   |
| 6.12.10-76061203-generic | 2         | 0.53%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.53%   |
| 6.1.0-22-amd64           | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 37        | 10.51%  |
| 6.8.0   | 24        | 6.82%   |
| 6.14.2  | 21        | 5.97%   |
| 5.4.0   | 20        | 5.68%   |
| 5.10.0  | 18        | 5.11%   |
| 6.5.0   | 11        | 3.13%   |
| 6.2.0   | 10        | 2.84%   |
| 6.1.0   | 10        | 2.84%   |
| 5.13.0  | 10        | 2.84%   |
| 6.14.0  | 9         | 2.56%   |
| 5.16.7  | 8         | 2.27%   |
| 4.19.0  | 8         | 2.27%   |
| 6.12.48 | 7         | 1.99%   |
| 5.19.0  | 7         | 1.99%   |
| 6.11.0  | 6         | 1.7%    |
| 5.11.0  | 6         | 1.7%    |
| 6.4.11  | 5         | 1.42%   |
| 5.3.0   | 5         | 1.42%   |
| 6.4.8   | 4         | 1.14%   |
| 6.10.0  | 4         | 1.14%   |
| 5.8.0   | 4         | 1.14%   |
| 5.10.14 | 4         | 1.14%   |
| 4.15.0  | 4         | 1.14%   |
| 6.6.2   | 3         | 0.85%   |
| 6.2.6   | 3         | 0.85%   |
| 6.12.9  | 3         | 0.85%   |
| 6.12.1  | 3         | 0.85%   |
| 6.4.2   | 2         | 0.57%   |
| 6.3.5   | 2         | 0.57%   |
| 6.14.6  | 2         | 0.57%   |
| 6.13.9  | 2         | 0.57%   |
| 6.12.6  | 2         | 0.57%   |
| 6.12.12 | 2         | 0.57%   |
| 6.12.10 | 2         | 0.57%   |
| 6.1.1   | 2         | 0.57%   |
| 5.18.0  | 2         | 0.57%   |
| 5.15.2  | 2         | 0.57%   |
| 5.14.10 | 2         | 0.57%   |
| 5.0.0   | 2         | 0.57%   |
| 4.9.20  | 2         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 46        | 13.22%  |
| 6.14    | 34        | 9.77%   |
| 5.10    | 30        | 8.62%   |
| 6.8     | 25        | 7.18%   |
| 6.12    | 22        | 6.32%   |
| 5.4     | 22        | 6.32%   |
| 6.1     | 17        | 4.89%   |
| 6.2     | 15        | 4.31%   |
| 6.5     | 14        | 4.02%   |
| 6.4     | 12        | 3.45%   |
| 5.13    | 11        | 3.16%   |
| 6.11    | 8         | 2.3%    |
| 5.16    | 8         | 2.3%    |
| 4.19    | 8         | 2.3%    |
| 6.6     | 7         | 2.01%   |
| 5.19    | 7         | 2.01%   |
| 6.10    | 6         | 1.72%   |
| 5.11    | 6         | 1.72%   |
| 5.8     | 5         | 1.44%   |
| 5.3     | 5         | 1.44%   |
| 6.3     | 4         | 1.15%   |
| 5.17    | 4         | 1.15%   |
| 4.9     | 4         | 1.15%   |
| 4.15    | 4         | 1.15%   |
| 5.14    | 3         | 0.86%   |
| 6.9     | 2         | 0.57%   |
| 6.13    | 2         | 0.57%   |
| 6.0     | 2         | 0.57%   |
| 5.6     | 2         | 0.57%   |
| 5.18    | 2         | 0.57%   |
| 5.12    | 2         | 0.57%   |
| 5.0     | 2         | 0.57%   |
| 6.7     | 1         | 0.29%   |
| 6.17    | 1         | 0.29%   |
| 6.16    | 1         | 0.29%   |
| 6.15    | 1         | 0.29%   |
| 5.9     | 1         | 0.29%   |
| 5.5     | 1         | 0.29%   |
| 4.18    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 289       | 95.07%  |
| i686   | 15        | 4.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| GNOME               | 101       | 30.7%   |
| KDE5                | 60        | 18.24%  |
| XFCE                | 48        | 14.59%  |
| KDE6                | 34        | 10.33%  |
| X-Cinnamon          | 16        | 4.86%   |
| Unknown             | 16        | 4.86%   |
| MATE                | 11        | 3.34%   |
| LXQt                | 8         | 2.43%   |
| KDE                 | 7         | 2.13%   |
| Pantheon            | 4         | 1.22%   |
| KDE4                | 4         | 1.22%   |
| LXDE                | 3         | 0.91%   |
| Cinnamon            | 3         | 0.91%   |
| Budgie              | 3         | 0.91%   |
| Unity               | 2         | 0.61%   |
| Trinity             | 1         | 0.3%    |
| sway:wlroots:swayfx | 1         | 0.3%    |
| Openbox             | 1         | 0.3%    |
| lightdm-xsession    | 1         | 0.3%    |
| GNOME Classic       | 1         | 0.3%    |
| Enlightenment       | 1         | 0.3%    |
| Deepin              | 1         | 0.3%    |
| DDE                 | 1         | 0.3%    |
| awesome             | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 233       | 72.59%  |
| Wayland | 83        | 25.86%  |
| Tty     | 3         | 0.93%   |
| Unknown | 2         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 33.75%  |
| SDDM    | 79        | 24.69%  |
| LightDM | 52        | 16.25%  |
| GDM3    | 41        | 12.81%  |
| GDM     | 33        | 10.31%  |
| KDM     | 4         | 1.25%   |
| TDM     | 3         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_VE   | 164       | 51.09%  |
| en_US   | 85        | 26.48%  |
| es_ES   | 30        | 9.35%   |
| es_MX   | 24        | 7.48%   |
| Unknown | 8         | 2.49%   |
| es_US   | 4         | 1.25%   |
| C       | 4         | 1.25%   |
| en_GB   | 1         | 0.31%   |
| en_CA   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 188       | 60.26%  |
| EFI  | 124       | 39.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 225       | 71.2%   |
| Btrfs   | 37        | 11.71%  |
| Overlay | 35        | 11.08%  |
| Tmpfs   | 10        | 3.16%   |
| Xfs     | 5         | 1.58%   |
| Unknown | 3         | 0.95%   |
| F2fs    | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 139       | 43.71%  |
| Unknown | 113       | 35.53%  |
| MBR     | 66        | 20.75%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 265       | 83.86%  |
| Yes       | 51        | 16.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 70.65%  |
| Yes       | 91        | 29.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo                                   | 45        | 14.8%   |
| Hewlett-Packard                          | 41        | 13.49%  |
| Dell                                     | 41        | 13.49%  |
| VIT                                      | 37        | 12.17%  |
| Acer                                     | 24        | 7.89%   |
| Google                                   | 20        | 6.58%   |
| Intel                                    | 19        | 6.25%   |
| ASUSTek Computer                         | 19        | 6.25%   |
| Unknown                                  | 9         | 2.96%   |
| Toshiba                                  | 8         | 2.63%   |
| Shanghai Zhaoxin Semiconductor           | 4         | 1.32%   |
| Pegatron                                 | 4         | 1.32%   |
| MSI                                      | 4         | 1.32%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. | 3         | 0.99%   |
| SIRAGON                                  | 3         | 0.99%   |
| Samsung Electronics                      | 3         | 0.99%   |
| Notebook                                 | 3         | 0.99%   |
| GPU Company                              | 2         | 0.66%   |
| Apple                                    | 2         | 0.66%   |
| UNIQCELL                                 | 1         | 0.33%   |
| Sragon                                   | 1         | 0.33%   |
| Sony                                     | 1         | 0.33%   |
| PCSMART                                  | 1         | 0.33%   |
| Panasonic                                | 1         | 0.33%   |
| ISONIC                                   | 1         | 0.33%   |
| GPD                                      | 1         | 0.33%   |
| Gigabyte Technology                      | 1         | 0.33%   |
| Gateway                                  | 1         | 0.33%   |
| Exo                                      | 1         | 0.33%   |
| Clevo                                    | 1         | 0.33%   |
| AVITA                                    | 1         | 0.33%   |
| Alienware                                | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel powered classmate PC                            | 19        | 6.25%   |
| VIT P2400                                             | 12        | 3.95%   |
| Unknown                                               | 10        | 3.29%   |
| Google Snappy                                         | 7         | 2.3%    |
| VIT P2402                                             | 6         | 1.97%   |
| VIT M2420                                             | 6         | 1.97%   |
| VIT P3400                                             | 5         | 1.64%   |
| Shanghai Zhaoxin ZXE CRB                              | 4         | 1.32%   |
| VIT P1400                                             | 3         | 0.99%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT P2460-02 | 3         | 0.99%   |
| HP Pavilion dv5                                       | 3         | 0.99%   |
| HP Notebook                                           | 3         | 0.99%   |
| Google Kip                                            | 3         | 0.99%   |
| Google Candy                                          | 3         | 0.99%   |
| Dell Latitude 5590                                    | 3         | 0.99%   |
| ASUS VivoBook_ASUSLaptop K3605VC_K3605VC              | 3         | 0.99%   |
| VIT P2423                                             | 2         | 0.66%   |
| VIT M2421                                             | 2         | 0.66%   |
| Siragon MN-50                                         | 2         | 0.66%   |
| Pegatron T14AF                                        | 2         | 0.66%   |
| Notebook W54BL                                        | 2         | 0.66%   |
| Lenovo ThinkPad SL 2743A65                            | 2         | 0.66%   |
| Lenovo ThinkPad E560 20EV002FUS                       | 2         | 0.66%   |
| Lenovo IdeaPad S100c 20194                            | 2         | 0.66%   |
| Lenovo IdeaPad 1 14IGL7 82V6                          | 2         | 0.66%   |
| Lenovo G570 4334                                      | 2         | 0.66%   |
| Lenovo 3000 N200 0769ARS                              | 2         | 0.66%   |
| HP Laptop 15-ef2xxx                                   | 2         | 0.66%   |
| HP Compaq Presario C700                               | 2         | 0.66%   |
| GPU Company GWTN156-11                                | 2         | 0.66%   |
| Google Kefka                                          | 2         | 0.66%   |
| Dell Latitude E6420                                   | 2         | 0.66%   |
| Dell Latitude E5450                                   | 2         | 0.66%   |
| Dell Inspiron 1545                                    | 2         | 0.66%   |
| ASUS VivoBook_ASUSLaptop X1404ZA_X1404ZA              | 2         | 0.66%   |
| ASUS ASUS TUF Gaming F17 FX706HM_TUF706HM             | 2         | 0.66%   |
| Acer Aspire 4739Z                                     | 2         | 0.66%   |
| VIT P2412                                             | 1         | 0.33%   |
| UNIQCELL Q15.6                                        | 1         | 0.33%   |
| Toshiba Satellite S55t-A                              | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel powered                                | 19        | 6.25%   |
| Dell Inspiron                                | 18        | 5.92%   |
| Acer Aspire                                  | 18        | 5.92%   |
| Lenovo IdeaPad                               | 16        | 5.26%   |
| Lenovo ThinkPad                              | 13        | 4.28%   |
| Dell Latitude                                | 13        | 4.28%   |
| VIT P2400                                    | 12        | 3.95%   |
| HP Pavilion                                  | 12        | 3.95%   |
| Unknown                                      | 10        | 3.29%   |
| ASUS VivoBook                                | 9         | 2.96%   |
| Toshiba Satellite                            | 7         | 2.3%    |
| Google Snappy                                | 7         | 2.3%    |
| VIT P2402                                    | 6         | 1.97%   |
| VIT M2420                                    | 6         | 1.97%   |
| Lenovo 3000                                  | 6         | 1.97%   |
| VIT P3400                                    | 5         | 1.64%   |
| HP Laptop                                    | 5         | 1.64%   |
| ASUS ASUS                                    | 5         | 1.64%   |
| Shanghai Zhaoxin ZXE                         | 4         | 1.32%   |
| HP Presario                                  | 4         | 1.32%   |
| HP Compaq                                    | 4         | 1.32%   |
| Dell Vostro                                  | 4         | 1.32%   |
| VIT P1400                                    | 3         | 0.99%   |
| VENEZOLANA DE INDUSTRIA TECNOLOGICA C.A. VIT | 3         | 0.99%   |
| HP ProBook                                   | 3         | 0.99%   |
| HP Notebook                                  | 3         | 0.99%   |
| Google Kip                                   | 3         | 0.99%   |
| Google Candy                                 | 3         | 0.99%   |
| Dell Precision                               | 3         | 0.99%   |
| VIT P2423                                    | 2         | 0.66%   |
| VIT M2421                                    | 2         | 0.66%   |
| Siragon MN-50                                | 2         | 0.66%   |
| Pegatron T14AF                               | 2         | 0.66%   |
| Notebook W54BL                               | 2         | 0.66%   |
| Lenovo Legion                                | 2         | 0.66%   |
| Lenovo G570                                  | 2         | 0.66%   |
| HP EliteBook                                 | 2         | 0.66%   |
| HP 240                                       | 2         | 0.66%   |
| GPU Company GWTN156-11                       | 2         | 0.66%   |
| Google Kefka                                 | 2         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 39        | 12.83%  |
| 2013    | 33        | 10.86%  |
| 2022    | 27        | 8.88%   |
| 2012    | 27        | 8.88%   |
| 2023    | 19        | 6.25%   |
| 2010    | 18        | 5.92%   |
| 2008    | 16        | 5.26%   |
| 2019    | 15        | 4.93%   |
| 2007    | 14        | 4.61%   |
| 2021    | 12        | 3.95%   |
| 2020    | 12        | 3.95%   |
| 2014    | 12        | 3.95%   |
| 2018    | 11        | 3.62%   |
| 2016    | 11        | 3.62%   |
| 2015    | 9         | 2.96%   |
| 2009    | 9         | 2.96%   |
| 2025    | 6         | 1.97%   |
| 2017    | 5         | 1.64%   |
| 2024    | 3         | 0.99%   |
| 2006    | 3         | 0.99%   |
| Unknown | 3         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 304       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 295       | 96.41%  |
| Enabled  | 11        | 3.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 284       | 93.42%  |
| Yes  | 20        | 6.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 83        | 26.86%  |
| 4.01-8.0    | 73        | 23.62%  |
| 1.01-2.0    | 52        | 16.83%  |
| 8.01-16.0   | 47        | 15.21%  |
| 16.01-24.0  | 24        | 7.77%   |
| 2.01-3.0    | 16        | 5.18%   |
| 32.01-64.0  | 9         | 2.91%   |
| 24.01-32.0  | 2         | 0.65%   |
| 0.51-1.0    | 2         | 0.65%   |
| 64.01-256.0 | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 118       | 33.71%  |
| 2.01-3.0   | 85        | 24.29%  |
| 0.51-1.0   | 50        | 14.29%  |
| 4.01-8.0   | 41        | 11.71%  |
| 3.01-4.0   | 37        | 10.57%  |
| 8.01-16.0  | 14        | 4%      |
| 0.01-0.5   | 4         | 1.14%   |
| 16.01-24.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 212       | 68.17%  |
| 2      | 89        | 28.62%  |
| 3      | 9         | 2.89%   |
| 0      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 58.31%  |
| Yes       | 128       | 41.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 248       | 80.78%  |
| No        | 59        | 19.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 96.38%  |
| No        | 11        | 3.62%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 62.14%  |
| No        | 117       | 37.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Venezuela | 304       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Caracas                    | 106       | 32.12%  |
| Maracaibo                  | 32        | 9.7%    |
| Barquisimeto               | 17        | 5.15%   |
| Valencia                   | 14        | 4.24%   |
| Vigia                      | 12        | 3.64%   |
| Mérida                    | 12        | 3.64%   |
| Maracay                    | 12        | 3.64%   |
| Porlamar                   | 7         | 2.12%   |
| Barcelona                  | 7         | 2.12%   |
| Mariara                    | 5         | 1.52%   |
| Ciudad Guayana             | 5         | 1.52%   |
| San Carlos del Zulia       | 4         | 1.21%   |
| Maturín                   | 4         | 1.21%   |
| Lecherias                  | 4         | 1.21%   |
| Cua                        | 4         | 1.21%   |
| Barinas                    | 4         | 1.21%   |
| Turmero                    | 3         | 0.91%   |
| San Juan de los Morros     | 3         | 0.91%   |
| San Cristóbal             | 3         | 0.91%   |
| Petare                     | 3         | 0.91%   |
| Naguanagua                 | 3         | 0.91%   |
| La Guaira                  | 3         | 0.91%   |
| Distrito Federal           | 3         | 0.91%   |
| Coro                       | 3         | 0.91%   |
| Acarigua                   | 3         | 0.91%   |
| San Antonio de Los Altos   | 2         | 0.61%   |
| Punto Fijo                 | 2         | 0.61%   |
| Puerto Ordaz and San Felix | 2         | 0.61%   |
| Miranda                    | 2         | 0.61%   |
| Maiquetia                  | 2         | 0.61%   |
| Guatire                    | 2         | 0.61%   |
| Ciudad Ojeda               | 2         | 0.61%   |
| Ciudad Bolívar            | 2         | 0.61%   |
| Carora                     | 2         | 0.61%   |
| Cambural                   | 2         | 0.61%   |
| Cagua                      | 2         | 0.61%   |
| Araure                     | 2         | 0.61%   |
| Anaco                      | 2         | 0.61%   |
| Villa de Cura              | 1         | 0.3%    |
| Tucape                     | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                                    | Notebooks | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate                                   | 61        | 66     | 16.8%   |
| WDC                                       | 43        | 57     | 11.85%  |
| Unknown                                   | 38        | 47     | 10.47%  |
| Toshiba                                   | 30        | 32     | 8.26%   |
| Samsung Electronics                       | 26        | 30     | 7.16%   |
| Sandisk                                   | 18        | 25     | 4.96%   |
| Hitachi                                   | 15        | 17     | 4.13%   |
| Intel                                     | 12        | 21     | 3.31%   |
| Micron Technology                         | 10        | 13     | 2.75%   |
| Kingston                                  | 10        | 13     | 2.75%   |
| Crucial                                   | 9         | 12     | 2.48%   |
| addlink                                   | 9         | 11     | 2.48%   |
| SK hynix                                  | 7         | 10     | 1.93%   |
| LITEONIT                                  | 6         | 10     | 1.65%   |
| SPCC                                      | 5         | 8      | 1.38%   |
| PNY                                       | 5         | 5      | 1.38%   |
| HGST                                      | 5         | 5      | 1.38%   |
| Patriot                                   | 4         | 4      | 1.1%    |
| HS-SSD-WAVE(S)                            | 3         | 3      | 0.83%   |
| Team                                      | 2         | 2      | 0.55%   |
| Silicon Motion                            | 2         | 3      | 0.55%   |
| Netac                                     | 2         | 2      | 0.55%   |
| Micron/Crucial Technology                 | 2         | 2      | 0.55%   |
| Lexar                                     | 2         | 3      | 0.55%   |
| Kingston Technology Company               | 2         | 2      | 0.55%   |
| HUAWEI                                    | 2         | 2      | 0.55%   |
| Fujitsu                                   | 2         | 2      | 0.55%   |
| Dahua                                     | 2         | 2      | 0.55%   |
| China                                     | 2         | 2      | 0.55%   |
| BIWIN                                     | 2         | 3      | 0.55%   |
| A-DATA Technology                         | 2         | 2      | 0.55%   |
| Unknown                                   | 2         | 2      | 0.55%   |
| WALRAM                                    | 1         | 1      | 0.28%   |
| Vaseky                                    | 1         | 2      | 0.28%   |
| UMIS                                      | 1         | 8      | 0.28%   |
| Tata Power Strategic Electronics Division | 1         | 1      | 0.28%   |
| Shenzhen Unionmemory Information System   | 1         | 1      | 0.28%   |
| Shenzhen Longsys Electronics              | 1         | 1      | 0.28%   |
| Saichi                                    | 1         | 2      | 0.28%   |
| PUSKILL                                   | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  16GB              | 13        | 3.48%   |
| Seagate ST320LT012-1DG14C 320GB     | 11        | 2.94%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 6         | 1.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB        | 5         | 1.34%   |
| Seagate ST320LT012-9WS14C 320GB     | 5         | 1.34%   |
| LITEONIT LMS-32L6M 32GB SSD         | 5         | 1.34%   |
| WDC WD10JPVX-22JC3T0 1TB            | 4         | 1.07%   |
| Unknown NVMe SSD Drive 512GB        | 4         | 1.07%   |
| Unknown MMC Card  64GB              | 4         | 1.07%   |
| Toshiba MQ04ABF100 1TB              | 4         | 1.07%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.07%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.07%   |
| Seagate ST500LM021-1KJ152 500GB     | 4         | 1.07%   |
| Seagate ST320LM000 HM321HI 320GB    | 4         | 1.07%   |
| addlink SATA SSD 120GB              | 4         | 1.07%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.8%    |
| WDC WD5000LPCX-22VHAT0 500GB        | 3         | 0.8%    |
| WDC WD1600BEVT-22ZCT0 160GB         | 3         | 0.8%    |
| Unknown MMC Card  128GB             | 3         | 0.8%    |
| Unknown HAG2e  16GB                 | 3         | 0.8%    |
| Toshiba MQ01ABF032 320GB            | 3         | 0.8%    |
| SPCC Solid State Disk 512GB         | 3         | 0.8%    |
| Seagate ST9320423AS 320GB           | 3         | 0.8%    |
| Seagate ST250LM004 HN-M250MBB 250GB | 3         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.8%    |
| Micron 2450_MTFDKBA1T0TFK 1TB       | 3         | 0.8%    |
| Hitachi HTS725050A9A364 500GB       | 3         | 0.8%    |
| WDC WD5000LPVT-08G33T1 500GB        | 2         | 0.53%   |
| WDC WD3200BEVT-00A0RT0 320GB        | 2         | 0.53%   |
| WDC WD1200BEVS-60UST0 120GB         | 2         | 0.53%   |
| Unknown MMC Card  32GB              | 2         | 0.53%   |
| Toshiba MQ01ABD050 500GB            | 2         | 0.53%   |
| Toshiba MK3276GSX 320GB             | 2         | 0.53%   |
| Toshiba MK3275GSX 320GB             | 2         | 0.53%   |
| SK hynix HFM001TD3JX013N 1024GB     | 2         | 0.53%   |
| Seagate ST9500325AS 500GB           | 2         | 0.53%   |
| Seagate ST9320325AS 320GB           | 2         | 0.53%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.53%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 62     | 35.8%   |
| WDC                 | 41        | 52     | 25.31%  |
| Toshiba             | 28        | 30     | 17.28%  |
| Hitachi             | 15        | 17     | 9.26%   |
| Samsung Electronics | 9         | 9      | 5.56%   |
| HGST                | 5         | 5      | 3.09%   |
| Unknown             | 2         | 2      | 1.23%   |
| Fujitsu             | 2         | 2      | 1.23%   |
| Min Yi U            | 1         | 1      | 0.62%   |
| ASMT                | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 9         | 12     | 11.39%  |
| Samsung Electronics | 7         | 11     | 8.86%   |
| Kingston            | 7         | 10     | 8.86%   |
| addlink             | 7         | 9      | 8.86%   |
| LITEONIT            | 6         | 10     | 7.59%   |
| PNY                 | 5         | 5      | 6.33%   |
| SPCC                | 4         | 6      | 5.06%   |
| Patriot             | 4         | 4      | 5.06%   |
| SanDisk             | 3         | 4      | 3.8%    |
| Toshiba             | 2         | 2      | 2.53%   |
| Netac               | 2         | 2      | 2.53%   |
| Lexar               | 2         | 3      | 2.53%   |
| Intel               | 2         | 5      | 2.53%   |
| HS-SSD-WAVE(S)      | 2         | 2      | 2.53%   |
| China               | 2         | 2      | 2.53%   |
| A-DATA Technology   | 2         | 2      | 2.53%   |
| WALRAM              | 1         | 1      | 1.27%   |
| Vaseky              | 1         | 2      | 1.27%   |
| Team                | 1         | 1      | 1.27%   |
| Saichi              | 1         | 2      | 1.27%   |
| PUSKILL             | 1         | 1      | 1.27%   |
| Micron Technology   | 1         | 3      | 1.27%   |
| KingFast            | 1         | 3      | 1.27%   |
| Intenso             | 1         | 1      | 1.27%   |
| Emtec               | 1         | 2      | 1.27%   |
| Dell                | 1         | 2      | 1.27%   |
| Dahua               | 1         | 1      | 1.27%   |
| BIWIN               | 1         | 2      | 1.27%   |
| ACCLAMATOR          | 1         | 1      | 1.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 159       | 181    | 45.82%  |
| SSD     | 76        | 111    | 21.9%   |
| NVMe    | 70        | 113    | 20.17%  |
| MMC     | 33        | 41     | 9.51%   |
| Unknown | 9         | 10     | 2.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 216       | 288    | 65.06%  |
| NVMe | 70        | 113    | 21.08%  |
| MMC  | 33        | 41     | 9.94%   |
| SAS  | 13        | 14     | 3.92%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 187       | 236    | 80.26%  |
| 0.51-1.0   | 42        | 52     | 18.03%  |
| 1.01-2.0   | 4         | 4      | 1.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 98        | 30.34%  |
| 101-250        | 85        | 26.32%  |
| 501-1000       | 45        | 13.93%  |
| 1-20           | 38        | 11.76%  |
| 51-100         | 18        | 5.57%   |
| 21-50          | 14        | 4.33%   |
| 1001-2000      | 12        | 3.72%   |
| Unknown        | 8         | 2.48%   |
| 2001-3000      | 3         | 0.93%   |
| More than 3000 | 2         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 134       | 38.95%  |
| 21-50     | 66        | 19.19%  |
| 51-100    | 48        | 13.95%  |
| 101-250   | 47        | 13.66%  |
| 251-500   | 24        | 6.98%   |
| 501-1000  | 14        | 4.07%   |
| Unknown   | 8         | 2.33%   |
| 2001-3000 | 1         | 0.29%   |
| 1001-2000 | 1         | 0.29%   |
| 0         | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST320LT012-1DG14C 320GB      | 3         | 3      | 5.45%   |
| Hitachi HTS725050A9A364 500GB        | 3         | 4      | 5.45%   |
| WDC WD1200BEVS-60UST0 120GB          | 2         | 2      | 3.64%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 3.64%   |
| Seagate ST9320423AS 320GB            | 2         | 2      | 3.64%   |
| Samsung Electronics HM250HI 250GB    | 2         | 2      | 3.64%   |
| WDC WD5000BPVT-24HXZT3 500GB         | 1         | 1      | 1.82%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 1      | 1.82%   |
| WDC WD3200BEVT-00A0RT0 320GB         | 1         | 1      | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 2      | 1.82%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 1.82%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.82%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1      | 1.82%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 1.82%   |
| Toshiba MK3276GSX 320GB              | 1         | 1      | 1.82%   |
| Toshiba MK3275GSX 320GB              | 1         | 2      | 1.82%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 1.82%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1      | 1.82%   |
| Toshiba MK2565GSX 250GB              | 1         | 1      | 1.82%   |
| Toshiba MK1032GSX 100GB              | 1         | 1      | 1.82%   |
| SPCC Solid State Disk 512GB          | 1         | 1      | 1.82%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.82%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 1.82%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.82%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 1.82%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 1.82%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.82%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 1.82%   |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 1      | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 1.82%   |
| Samsung Electronics HN-M320MBB 320GB | 1         | 1      | 1.82%   |
| Samsung Electronics HM321HI 320GB    | 1         | 1      | 1.82%   |
| Samsung Electronics HM160HI 160GB    | 1         | 1      | 1.82%   |
| Samsung Electronics HM121HI 120GB    | 1         | 1      | 1.82%   |
| Intel SSDSA2M080G2GC 80GB            | 1         | 2      | 1.82%   |
| Intel SSDPEKKW256G7 256GB            | 1         | 1      | 1.82%   |
| Intel SSDPEKKF512G7L 512GB           | 1         | 2      | 1.82%   |
| Hitachi HTS543232L9A300 320GB        | 1         | 1      | 1.82%   |
| Hitachi HTS543232A7A384 320GB        | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 29.09%  |
| Toshiba             | 10        | 11     | 18.18%  |
| Hitachi             | 9         | 10     | 16.36%  |
| WDC                 | 6         | 7      | 10.91%  |
| Samsung Electronics | 6         | 6      | 10.91%  |
| Intel               | 3         | 5      | 5.45%   |
| HGST                | 2         | 2      | 3.64%   |
| SPCC                | 1         | 1      | 1.82%   |
| SK hynix            | 1         | 1      | 1.82%   |
| ASMT                | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 32%     |
| Toshiba             | 10        | 11     | 20%     |
| Hitachi             | 9         | 10     | 18%     |
| WDC                 | 6         | 7      | 12%     |
| Samsung Electronics | 6         | 6      | 12%     |
| HGST                | 2         | 2      | 4%      |
| ASMT                | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 53     | 90.74%  |
| NVMe | 3         | 4      | 5.56%   |
| SSD  | 2         | 3      | 3.7%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM160HI 160GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 156       | 229    | 48.15%  |
| Works    | 113       | 166    | 34.88%  |
| Malfunc  | 54        | 60     | 16.67%  |
| Failed   | 1         | 1      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                    | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Intel                                     | 229       | 70.03%  |
| AMD                                       | 29        | 8.87%   |
| SanDisk                                   | 16        | 4.89%   |
| Samsung Electronics                       | 10        | 3.06%   |
| Micron Technology                         | 9         | 2.75%   |
| SK hynix                                  | 6         | 1.83%   |
| Kingston Technology Company               | 5         | 1.53%   |
| Phison Electronics                        | 4         | 1.22%   |
| Jiangsu Huacun Elec.                      | 4         | 1.22%   |
| Silicon Motion                            | 3         | 0.92%   |
| Union Memory (Shenzhen)                   | 2         | 0.61%   |
| Shenzhen Longsys Electronics              | 2         | 0.61%   |
| Nvidia                                    | 2         | 0.61%   |
| Micron/Crucial Technology                 | 2         | 0.61%   |
| Tata Power Strategic Electronics Division | 1         | 0.31%   |
| MAXIO Technology (Hangzhou)               | 1         | 0.31%   |
| KIOXIA                                    | 1         | 0.31%   |
| INNOGRIT                                  | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 38        | 10.58%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 28        | 7.8%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 6.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 4.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 15        | 4.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 3.9%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 13        | 3.62%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 3.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 3.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 12        | 3.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 9         | 2.51%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 6         | 1.67%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 6         | 1.67%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 5         | 1.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 1.39%   |
| Jiangsu Huacun Elec. MMY MMSP350 PCIe 3 NVMe SSD (DRAM-less)                   | 4         | 1.11%   |
| Intel RST Volume Management Device Controller                                  | 4         | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.11%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.11%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.84%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 3         | 0.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 3         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 0.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.84%   |
| Shenzhen Longsys FORESEE XP2000, Lexar NM760 NVME SSD (DRAM-less)              | 2         | 0.56%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.56%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 0.56%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.56%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 206       | 60.06%  |
| NVMe | 70        | 20.41%  |
| RAID | 35        | 10.2%   |
| IDE  | 32        | 9.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 260       | 85.53%  |
| AMD          | 40        | 13.16%  |
| CentaurHauls | 4         | 1.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz                | 15        | 4.93%   |
| Intel Atom CPU N455 @ 1.66GHz                  | 12        | 3.95%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 7         | 2.3%    |
| Intel Celeron CPU N3350 @ 1.10GHz              | 7         | 2.3%    |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz           | 6         | 1.97%   |
| Intel Core i5-7300U CPU @ 2.60GHz              | 5         | 1.64%   |
| Intel Core i3-3120M CPU @ 2.50GHz              | 5         | 1.64%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 5         | 1.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 5         | 1.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 5         | 1.64%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz         | 4         | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz              | 4         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 4         | 1.32%   |
| Intel Core i5-2430M CPU @ 2.40GHz              | 4         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 4         | 1.32%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz           | 4         | 1.32%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 4         | 1.32%   |
| AMD Ryzen 7 5700U with Radeon Graphics         | 4         | 1.32%   |
| Intel Pentium CPU P6200 @ 2.13GHz              | 3         | 0.99%   |
| Intel Core i7-3537U CPU @ 2.00GHz              | 3         | 0.99%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 3         | 0.99%   |
| Intel Core i5 CPU M 560 @ 2.67GHz              | 3         | 0.99%   |
| Intel Core i3-4000M CPU @ 2.40GHz              | 3         | 0.99%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 3         | 0.99%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 3         | 0.99%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 3         | 0.99%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 3         | 0.99%   |
| Intel 13th Gen Core i9-13900H                  | 3         | 0.99%   |
| Intel 12th Gen Core i5-1235U                   | 3         | 0.99%   |
| Intel 12th Gen Core i3-1215U                   | 3         | 0.99%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics         | 3         | 0.99%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz       | 2         | 0.66%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz    | 2         | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 2         | 0.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 2         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 2         | 0.66%   |
| Intel Core i5-3337U CPU @ 1.80GHz              | 2         | 0.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz              | 2         | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz              | 2         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 55        | 18.09%  |
| Intel Celeron                        | 45        | 14.8%   |
| Intel Core i3                        | 44        | 14.47%  |
| Other                                | 32        | 10.53%  |
| Intel Core i7                        | 23        | 7.57%   |
| Intel Core 2 Duo                     | 22        | 7.24%   |
| Intel Atom                           | 19        | 6.25%   |
| Intel Pentium                        | 9         | 2.96%   |
| AMD Ryzen 7                          | 9         | 2.96%   |
| AMD Ryzen 5                          | 9         | 2.96%   |
| Intel Pentium Dual                   | 5         | 1.64%   |
| Intel Pentium Dual-Core              | 3         | 0.99%   |
| Intel Core 2                         | 3         | 0.99%   |
| AMD Ryzen 3                          | 3         | 0.99%   |
| AMD E1                               | 3         | 0.99%   |
| Intel Pentium Silver                 | 2         | 0.66%   |
| Intel Genuine                        | 2         | 0.66%   |
| AMD E                                | 2         | 0.66%   |
| AMD C-70                             | 2         | 0.66%   |
| AMD A6                               | 2         | 0.66%   |
| AMD A10                              | 2         | 0.66%   |
| Intel Core i9                        | 1         | 0.33%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.33%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.33%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.33%   |
| AMD Quad-Core                        | 1         | 0.33%   |
| AMD Phenom II                        | 1         | 0.33%   |
| AMD Mobile Sempron                   | 1         | 0.33%   |
| AMD A4                               | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 205       | 67.43%  |
| 4       | 44        | 14.47%  |
| 1       | 15        | 4.93%   |
| 8       | 13        | 4.28%   |
| 6       | 13        | 4.28%   |
| 14      | 4         | 1.32%   |
| 10      | 4         | 1.32%   |
| 24      | 2         | 0.66%   |
| 12      | 2         | 0.66%   |
| Unknown | 2         | 0.66%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 304       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 188       | 61.84%  |
| 1       | 114       | 37.5%   |
| Unknown | 2         | 0.66%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 298       | 98.03%  |
| 64-bit         | 3         | 0.99%   |
| 32-bit         | 3         | 0.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 54.06%  |
| 0x206a7    | 18        | 5.63%   |
| 0x306a9    | 17        | 5.31%   |
| 0x1067a    | 12        | 3.75%   |
| 0x106ca    | 10        | 3.13%   |
| 0x6fd      | 8         | 2.5%    |
| 0x30678    | 7         | 2.19%   |
| 0x806e9    | 5         | 1.56%   |
| 0x20655    | 5         | 1.56%   |
| 0x806c1    | 4         | 1.25%   |
| 0x406e3    | 4         | 1.25%   |
| 0x806ec    | 3         | 0.94%   |
| 0x40651    | 3         | 0.94%   |
| 0x306c3    | 3         | 0.94%   |
| 0x05000119 | 3         | 0.94%   |
| 0x806ea    | 2         | 0.63%   |
| 0x806d1    | 2         | 0.63%   |
| 0x706a8    | 2         | 0.63%   |
| 0x306d4    | 2         | 0.63%   |
| 0x30673    | 2         | 0.63%   |
| 0x08608103 | 2         | 0.63%   |
| 0x08108102 | 2         | 0.63%   |
| 0x06006705 | 2         | 0.63%   |
| 0x0500010d | 2         | 0.63%   |
| 0x02000057 | 2         | 0.63%   |
| 0x906ea    | 1         | 0.31%   |
| 0x906e9    | 1         | 0.31%   |
| 0x906a4    | 1         | 0.31%   |
| 0x806eb    | 1         | 0.31%   |
| 0x806c2    | 1         | 0.31%   |
| 0x706e5    | 1         | 0.31%   |
| 0x6f6      | 1         | 0.31%   |
| 0x6ec      | 1         | 0.31%   |
| 0x506e3    | 1         | 0.31%   |
| 0x406c4    | 1         | 0.31%   |
| 0x30661    | 1         | 0.31%   |
| 0x20652    | 1         | 0.31%   |
| 0x106c2    | 1         | 0.31%   |
| 0x0a50000d | 1         | 0.31%   |
| 0x08608104 | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 46        | 15.13%  |
| IvyBridge        | 28        | 9.21%   |
| KabyLake         | 23        | 7.57%   |
| Westmere         | 19        | 6.25%   |
| Silvermont       | 19        | 6.25%   |
| Core             | 18        | 5.92%   |
| Bonnell          | 17        | 5.59%   |
| Unknown          | 17        | 5.59%   |
| Penryn           | 16        | 5.26%   |
| Alderlake Hybrid | 12        | 3.95%   |
| Skylake          | 9         | 2.96%   |
| Haswell          | 9         | 2.96%   |
| TigerLake        | 8         | 2.63%   |
| Goldmont         | 8         | 2.63%   |
| IceLake          | 7         | 2.3%    |
| Goldmont plus    | 6         | 1.97%   |
| Zen+             | 5         | 1.64%   |
| CometLake        | 5         | 1.64%   |
| Broadwell        | 5         | 1.64%   |
| Bobcat           | 5         | 1.64%   |
| Jaguar           | 4         | 1.32%   |
| Excavator        | 4         | 1.32%   |
| Zen 2            | 3         | 0.99%   |
| Zen 3            | 2         | 0.66%   |
| Zen              | 2         | 0.66%   |
| K8 Hammer        | 2         | 0.66%   |
| K8 & K10 hybrid  | 2         | 0.66%   |
| Steamroller      | 1         | 0.33%   |
| P6               | 1         | 0.33%   |
| K10              | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 254       | 76.28%  |
| AMD     | 44        | 13.21%  |
| Nvidia  | 31        | 9.31%   |
| Zhaoxin | 4         | 1.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 12.86%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 7.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 5.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 4.57%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 4.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 3.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 3.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 3.14%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 8         | 2.29%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 8         | 2.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 2.29%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 8         | 2.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2%      |
| AMD Lucienne                                                                             | 7         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.71%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 5         | 1.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.43%   |
| Zhaoxin KX-6000 C-960 GPU                                                                | 4         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.14%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 1.14%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.14%   |
| Nvidia GA107M [GeForce RTX 3050 4GB Laptop GPU]                                          | 3         | 0.86%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.86%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.86%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 3         | 0.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.86%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 3         | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.86%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.57%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.57%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 2         | 0.57%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 2         | 0.57%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 2         | 0.57%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 216       | 70.82%  |
| 1 x AMD        | 37        | 12.13%  |
| Intel + Nvidia | 21        | 6.89%   |
| 2 x Intel      | 10        | 3.28%   |
| 1 x Nvidia     | 8         | 2.62%   |
| Intel + AMD    | 5         | 1.64%   |
| 1 x Zhaoxin    | 4         | 1.31%   |
| Other          | 2         | 0.66%   |
| AMD + Nvidia   | 2         | 0.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 273       | 89.22%  |
| Proprietary | 19        | 6.21%   |
| Unknown     | 14        | 4.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 85.34%  |
| 0.01-0.5   | 29        | 9.45%   |
| 1.01-2.0   | 6         | 1.95%   |
| 3.01-4.0   | 4         | 1.3%    |
| 0.51-1.0   | 4         | 1.3%    |
| 5.01-6.0   | 2         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 57        | 16.96%  |
| Samsung Electronics     | 54        | 16.07%  |
| AU Optronics            | 50        | 14.88%  |
| Chimei Innolux          | 42        | 12.5%   |
| LG Display              | 40        | 11.9%   |
| InfoVision              | 13        | 3.87%   |
| Lenovo                  | 11        | 3.27%   |
| Chi Mei Optoelectronics | 10        | 2.98%   |
| LG Philips              | 7         | 2.08%   |
| Hewlett-Packard         | 7         | 2.08%   |
| HannStar                | 4         | 1.19%   |
| Goldstar                | 4         | 1.19%   |
| Dell                    | 4         | 1.19%   |
| PANDA                   | 3         | 0.89%   |
| InnoLux Display         | 3         | 0.89%   |
| Acer                    | 3         | 0.89%   |
| Vita                    | 2         | 0.6%    |
| ViewSonic               | 2         | 0.6%    |
| Toshiba                 | 2         | 0.6%    |
| Apple                   | 2         | 0.6%    |
| Vizio                   | 1         | 0.3%    |
| STA                     | 1         | 0.3%    |
| Skyworth                | 1         | 0.3%    |
| SKG                     | 1         | 0.3%    |
| Sharp                   | 1         | 0.3%    |
| Sceptre Tech            | 1         | 0.3%    |
| Philips                 | 1         | 0.3%    |
| MStar                   | 1         | 0.3%    |
| KTC                     | 1         | 0.3%    |
| IBM                     | 1         | 0.3%    |
| HKC                     | 1         | 0.3%    |
| GPD                     | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| BenQ                    | 1         | 0.3%    |
| ASUSTek Computer        | 1         | 0.3%    |
| AOC                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 15        | 4.41%   |
| Chimei Innolux LCD Monitor CMN1475 1366x768 309x174mm 14.0-inch          | 7         | 2.06%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 7         | 2.06%   |
| AU Optronics LCD Monitor AUO1B3C 1366x768 309x173mm 13.9-inch            | 6         | 1.76%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 5         | 1.47%   |
| Samsung Electronics T22C301 SAM0AD2 1920x1080 477x268mm 21.5-inch        | 4         | 1.18%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 4         | 1.18%   |
| InfoVision LCD Monitor IVO0579 1366x768 309x174mm 14.0-inch              | 4         | 1.18%   |
| BOE LCD Monitor BOE059F 1366x768 309x173mm 13.9-inch                     | 4         | 1.18%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.88%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch              | 3         | 0.88%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.88%   |
| Chimei Innolux N160JME-GL2 CMN1627 1920x1200 344x215mm 16.0-inch         | 3         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 3         | 0.88%   |
| BOE LCD Monitor BOE05C7 1366x768 309x173mm 13.9-inch                     | 3         | 0.88%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                     | 3         | 0.88%   |
| Vita V195EW-W VIT1950 1600x900 432x240mm 19.5-inch                       | 2         | 0.59%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch     | 2         | 0.59%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch     | 2         | 0.59%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch        | 2         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.59%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.59%   |
| LG Display LP116WH1-TLA1 LGD021C 1366x768 256x144mm 11.6-inch            | 2         | 0.59%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 2         | 0.59%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch             | 2         | 0.59%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 0.59%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 2         | 0.59%   |
| InnoLux Display LCD Monitor CMI001B 1366x768 309x174mm 14.0-inch         | 2         | 0.59%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch              | 2         | 0.59%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch          | 2         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 303x190mm 14.1-inch | 2         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 165       | 52.05%  |
| 1920x1080 (FHD)    | 76        | 23.97%  |
| 1280x800 (WXGA)    | 27        | 8.52%   |
| 1920x1200 (WUXGA)  | 9         | 2.84%   |
| 1600x900 (HD+)     | 7         | 2.21%   |
| 3840x2160 (4K)     | 5         | 1.58%   |
| 1440x900 (WXGA+)   | 5         | 1.58%   |
| 1024x600           | 5         | 1.58%   |
| 1280x1024 (SXGA)   | 4         | 1.26%   |
| 2240x1400          | 3         | 0.95%   |
| 1680x1050 (WSXGA+) | 3         | 0.95%   |
| 2560x1440 (QHD)    | 2         | 0.63%   |
| 1360x768           | 2         | 0.63%   |
| 1024x768 (XGA)     | 2         | 0.63%   |
| 2560x1600          | 1         | 0.32%   |
| 1280x720 (HD)      | 1         | 0.32%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 120       | 35.82%  |
| 14      | 67        | 20%     |
| 13      | 56        | 16.72%  |
| 11      | 13        | 3.88%   |
| 21      | 11        | 3.28%   |
| 18      | 10        | 2.99%   |
| 17      | 10        | 2.99%   |
| 10      | 8         | 2.39%   |
| 16      | 6         | 1.79%   |
| 19      | 5         | 1.49%   |
| 27      | 4         | 1.19%   |
| 23      | 4         | 1.19%   |
| 12      | 4         | 1.19%   |
| Unknown | 4         | 1.19%   |
| 31      | 3         | 0.9%    |
| 24      | 3         | 0.9%    |
| 32      | 2         | 0.6%    |
| 20      | 2         | 0.6%    |
| 54      | 1         | 0.3%    |
| 52      | 1         | 0.3%    |
| 22      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 243       | 72.75%  |
| 201-300     | 29        | 8.68%   |
| 401-500     | 27        | 8.08%   |
| 351-400     | 14        | 4.19%   |
| 501-600     | 10        | 2.99%   |
| Unknown     | 4         | 1.2%    |
| 601-700     | 3         | 0.9%    |
| 701-800     | 2         | 0.6%    |
| 1001-1500   | 2         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 246       | 81.73%  |
| 16/10 | 49        | 16.28%  |
| 5/4   | 3         | 1%      |
| 4/3   | 2         | 0.66%   |
| 3/2   | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 120       | 35.82%  |
| 101-110        | 120       | 35.82%  |
| 51-60          | 13        | 3.88%   |
| 151-200        | 13        | 3.88%   |
| 201-250        | 12        | 3.58%   |
| 141-150        | 9         | 2.69%   |
| 121-130        | 9         | 2.69%   |
| 41-50          | 8         | 2.39%   |
| 111-120        | 6         | 1.79%   |
| 351-500        | 5         | 1.49%   |
| 61-70          | 4         | 1.19%   |
| 301-350        | 4         | 1.19%   |
| Unknown        | 4         | 1.19%   |
| 71-80          | 3         | 0.9%    |
| 251-300        | 3         | 0.9%    |
| More than 1000 | 2         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 161       | 48.49%  |
| 121-160       | 96        | 28.92%  |
| 51-100        | 59        | 17.77%  |
| 161-240       | 6         | 1.81%   |
| 1-50          | 5         | 1.51%   |
| Unknown       | 4         | 1.2%    |
| More than 240 | 1         | 0.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 253       | 80.32%  |
| 2     | 48        | 15.24%  |
| 0     | 11        | 3.49%   |
| 3     | 3         | 0.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 182       | 36.77%  |
| Intel                           | 123       | 24.85%  |
| Qualcomm Atheros                | 94        | 18.99%  |
| Broadcom                        | 33        | 6.67%   |
| MediaTek                        | 14        | 2.83%   |
| Broadcom Limited                | 9         | 1.82%   |
| TP-Link                         | 7         | 1.41%   |
| Xiaomi                          | 4         | 0.81%   |
| JMicron Technology              | 4         | 0.81%   |
| Qualcomm Atheros Communications | 3         | 0.61%   |
| Marvell Technology Group        | 3         | 0.61%   |
| ASIX Electronics                | 3         | 0.61%   |
| Shenzhen Goodix Technology      | 2         | 0.4%    |
| Samsung Electronics             | 2         | 0.4%    |
| Ralink Technology               | 2         | 0.4%    |
| Nvidia                          | 2         | 0.4%    |
| Motorola PCS                    | 2         | 0.4%    |
| ZyXEL Communications            | 1         | 0.2%    |
| Trendchip Technologies          | 1         | 0.2%    |
| Ralink                          | 1         | 0.2%    |
| Huawei Technologies             | 1         | 0.2%    |
| D-Link System                   | 1         | 0.2%    |
| AMD                             | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 92        | 16.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 40        | 7.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 5.09%   |
| Intel Wireless 7265                                                     | 21        | 3.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 2.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 2.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 11        | 1.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.58%   |
| Intel Centrino Wireless-N 105                                           | 9         | 1.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 8         | 1.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 1.4%    |
| Intel Wireless 7260                                                     | 8         | 1.4%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 7         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.23%   |
| Intel Wireless 8265 / 8275                                              | 7         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                   | 7         | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 6         | 1.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 6         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.05%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 6         | 1.05%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 6         | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 0.88%   |
| Intel Wireless 3165                                                     | 5         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 0.7%    |
| Intel WiFi Link 5100                                                    | 4         | 0.7%    |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.7%    |
| Intel Centrino Wireless-N 100                                           | 4         | 0.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 0.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.7%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 3         | 0.53%   |
| Intel Wireless 8260                                                     | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 113       | 36.69%  |
| Realtek Semiconductor           | 70        | 22.73%  |
| Qualcomm Atheros                | 69        | 22.4%   |
| Broadcom                        | 26        | 8.44%   |
| MediaTek                        | 12        | 3.9%    |
| TP-Link                         | 6         | 1.95%   |
| Broadcom Limited                | 4         | 1.3%    |
| Qualcomm Atheros Communications | 3         | 0.97%   |
| Ralink Technology               | 2         | 0.65%   |
| Xiaomi                          | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| D-Link System                   | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 9.42%   |
| Intel Wireless 7265                                                     | 21        | 6.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 5.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 4.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 11        | 3.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.92%   |
| Intel Centrino Wireless-N 105                                           | 9         | 2.92%   |
| Intel Wireless 7260                                                     | 8         | 2.6%    |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 7         | 2.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 2.27%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.27%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 6         | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.95%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 6         | 1.95%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 6         | 1.95%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.62%   |
| Intel Wireless 3165                                                     | 5         | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.3%    |
| Intel WiFi Link 5100                                                    | 4         | 1.3%    |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.3%    |
| Intel Centrino Wireless-N 100                                           | 4         | 1.3%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 1.3%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 1.3%    |
| Intel Wireless 8260                                                     | 3         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.97%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.65%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.65%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.65%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 143       | 56.3%   |
| Qualcomm Atheros         | 36        | 14.17%  |
| Intel                    | 36        | 14.17%  |
| Broadcom                 | 9         | 3.54%   |
| Broadcom Limited         | 5         | 1.97%   |
| MediaTek                 | 4         | 1.57%   |
| JMicron Technology       | 4         | 1.57%   |
| Xiaomi                   | 3         | 1.18%   |
| Marvell Technology Group | 3         | 1.18%   |
| ASIX Electronics         | 3         | 1.18%   |
| Samsung Electronics      | 2         | 0.79%   |
| Nvidia                   | 2         | 0.79%   |
| ZyXEL Communications     | 1         | 0.39%   |
| Trendchip Technologies   | 1         | 0.39%   |
| TP-Link                  | 1         | 0.39%   |
| Motorola PCS             | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 92        | 35.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 15.56%  |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 3.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 3.11%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 2.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 2.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 1.17%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.17%   |
| Intel Ethernet Connection (13) I219-V                                  | 3         | 1.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 1.17%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 1.17%   |
| Broadcom Limited NetLink BCM5906M Fast Ethernet PCI Express            | 3         | 1.17%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 0.78%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.78%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 2         | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.78%   |
| MediaTek Infinix HOT 50i                                               | 2         | 0.78%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.78%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.78%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.78%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.78%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 2         | 0.78%   |
| ZyXEL ADSL Modem Prestige 600 series                                   | 1         | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.39%   |
| Trendchip Ethernet controller                                          | 1         | 0.39%   |
| TP-Link M7010                                                          | 1         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.39%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 293       | 53.96%  |
| Ethernet | 245       | 45.12%  |
| Modem    | 5         | 0.92%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 235       | 74.6%   |
| Ethernet | 80        | 25.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 226       | 74.34%  |
| 1     | 73        | 24.01%  |
| 0     | 5         | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 295       | 95.78%  |
| Yes  | 13        | 4.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 40.72%  |
| Realtek Semiconductor           | 27        | 13.92%  |
| IMC Networks                    | 24        | 12.37%  |
| Qualcomm Atheros Communications | 23        | 11.86%  |
| Broadcom                        | 14        | 7.22%   |
| Cambridge Silicon Radio         | 7         | 3.61%   |
| Lite-On Technology              | 6         | 3.09%   |
| Dell                            | 3         | 1.55%   |
| Hewlett-Packard                 | 2         | 1.03%   |
| Foxconn / Hon Hai               | 2         | 1.03%   |
| ASUSTek Computer                | 2         | 1.03%   |
| Apple                           | 2         | 1.03%   |
| SiW                             | 1         | 0.52%   |
| Ralink Technology               | 1         | 0.52%   |
| Alps Electric                   | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 44        | 22.68%  |
| Realtek Bluetooth Radio                                     | 20        | 10.31%  |
| Intel AX201 Bluetooth                                       | 13        | 6.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 5.15%   |
| Qualcomm Atheros  Bluetooth Device                          | 9         | 4.64%   |
| IMC Networks Wireless_Device                                | 9         | 4.64%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 7         | 3.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 7         | 3.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 7         | 3.61%   |
| IMC Networks Bluetooth                                      | 6         | 3.09%   |
| Realtek RTL8723B Bluetooth                                  | 4         | 2.06%   |
| Intel AX200 Bluetooth                                       | 4         | 2.06%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 4         | 2.06%   |
| Qualcomm Atheros Bluetooth (AR3011)                         | 3         | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 1.55%   |
| Lite-On Wireless_Device                                     | 3         | 1.55%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 3         | 1.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 3         | 1.55%   |
| Broadcom BCM2045 Bluetooth                                  | 3         | 1.55%   |
| Realtek RTL8723A Bluetooth                                  | 2         | 1.03%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.03%   |
| IMC Networks Bluetooth Radio                                | 2         | 1.03%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 1.03%   |
| ASUS BT-253 Bluetooth Adapter                               | 2         | 1.03%   |
| Apple Bluetooth Host Controller                             | 2         | 1.03%   |
| SiW SiW                                                     | 1         | 0.52%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 0.52%   |
| Ralink CSR BS8510                                           | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.52%   |
| Lite-On Bluetooth Device                                    | 1         | 0.52%   |
| Lite-On BCM20702A0                                          | 1         | 0.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.52%   |
| Intel Bluetooth Device                                      | 1         | 0.52%   |
| Intel AX210 Bluetooth                                       | 1         | 0.52%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.52%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                          | 1         | 0.52%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 258       | 77.48%  |
| AMD                   | 42        | 12.61%  |
| Nvidia                | 22        | 6.61%   |
| Zhaoxin               | 4         | 1.2%    |
| Texas Instruments     | 2         | 0.6%    |
| Realtek Semiconductor | 1         | 0.3%    |
| Microsoft             | 1         | 0.3%    |
| Logitech              | 1         | 0.3%    |
| Corsair               | 1         | 0.3%    |
| ASUSTek Computer      | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 46        | 11.92%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 28        | 7.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 5.44%   |
| AMD Ryzen HD Audio Controller                                                                     | 21        | 5.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 5.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 19        | 4.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 4.4%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 3.37%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 11        | 2.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 2.59%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 10        | 2.59%   |
| AMD FCH Azalia Controller                                                                         | 9         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.3%    |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.3%    |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.3%    |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 4         | 1.04%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 4         | 1.04%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 1.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.78%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 3         | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.78%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.78%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.78%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 55        | 21.32%  |
| Samsung Electronics | 53        | 20.54%  |
| Ramaxel Technology  | 32        | 12.4%   |
| Micron Technology   | 24        | 9.3%    |
| Unknown             | 23        | 8.91%   |
| Crucial             | 15        | 5.81%   |
| Kingston            | 13        | 5.04%   |
| fef5                | 6         | 2.33%   |
| Elpida              | 5         | 1.94%   |
| 48spaces            | 4         | 1.55%   |
| Unknown (ABCD)      | 3         | 1.16%   |
| PNY                 | 3         | 1.16%   |
| Timetec             | 2         | 0.78%   |
| Shenzhen WODPOSIT   | 2         | 0.78%   |
| Qimonda             | 2         | 0.78%   |
| Memox               | 2         | 0.78%   |
| A-DATA Technology   | 2         | 0.78%   |
| Unknown             | 2         | 0.78%   |
| Unknown (081A)      | 1         | 0.39%   |
| Unknown (07F7)      | 1         | 0.39%   |
| Transcend           | 1         | 0.39%   |
| Team                | 1         | 0.39%   |
| Hikvision           | 1         | 0.39%   |
| Gold Key            | 1         | 0.39%   |
| ff                  | 1         | 0.39%   |
| Corsair             | 1         | 0.39%   |
| <Invalid>           | 1         | 0.39%   |
| 4ea5                | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Ramaxel RAM RMT3150ED58E8W1600 2GB SODIMM DDR3 1600MT/s                   | 9         | 3.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 7         | 2.59%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                   | 7         | 2.59%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                                  | 6         | 2.22%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s                     | 6         | 2.22%   |
| Ramaxel RAM RMT3010EC58E8F1333 2GB SODIMM DDR3 1600MT/s                   | 6         | 2.22%   |
| fef5 RAM H9HCNNN8KUMLHR 1GB 2400MT/s                                      | 6         | 2.22%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 5         | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 5         | 1.85%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s                   | 5         | 1.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 4         | 1.48%   |
| Crucial RAM CT25664BF160B.D8FE 2GB SODIMM DDR3 1600MT/s                   | 4         | 1.48%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 4         | 1.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s                    | 3         | 1.11%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s                    | 3         | 1.11%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 3         | 1.11%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s                      | 3         | 1.11%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 2         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 2         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 2         | 0.74%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 2         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.74%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 2         | 0.74%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 2         | 0.74%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s                     | 2         | 0.74%   |
| Samsung RAM Module 4GB Row Of Chips DDR4 2400MT/s                         | 2         | 0.74%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 2         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 2         | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s                     | 2         | 0.74%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s                    | 2         | 0.74%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s                      | 2         | 0.74%   |
| Samsung RAM 4GB DDR3 HYNIX 4GB SODIMM DDR3 1333MT/s                       | 2         | 0.74%   |
| Ramaxel RAM RMT3170MK58F8F1600 2GB SODIMM DDR3 1600MT/s                   | 2         | 0.74%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s                   | 2         | 0.74%   |
| Micron RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 800MT/s                     | 2         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 81        | 39.51%  |
| DDR4    | 70        | 34.15%  |
| DDR2    | 22        | 10.73%  |
| LPDDR4  | 11        | 5.37%   |
| SDRAM   | 9         | 4.39%   |
| Unknown | 6         | 2.93%   |
| LPDDR3  | 2         | 0.98%   |
| DDR5    | 2         | 0.98%   |
| DDR     | 2         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 176       | 89.8%   |
| Unknown      | 9         | 4.59%   |
| Row Of Chips | 8         | 4.08%   |
| DIMM         | 2         | 1.02%   |
| Chip         | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 67        | 29.65%  |
| 8192  | 64        | 28.32%  |
| 4096  | 56        | 24.78%  |
| 1024  | 20        | 8.85%   |
| 16384 | 16        | 7.08%   |
| 32768 | 3         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 57        | 25.22%  |
| 3200    | 42        | 18.58%  |
| 2667    | 30        | 13.27%  |
| 2400    | 19        | 8.41%   |
| 667     | 17        | 7.52%   |
| 1333    | 12        | 5.31%   |
| 1334    | 7         | 3.1%    |
| 533     | 6         | 2.65%   |
| 4199    | 4         | 1.77%   |
| 2048    | 4         | 1.77%   |
| 1067    | 4         | 1.77%   |
| 800     | 4         | 1.77%   |
| 2666    | 3         | 1.33%   |
| 2133    | 3         | 1.33%   |
| Unknown | 3         | 1.33%   |
| 8400    | 2         | 0.88%   |
| 3266    | 2         | 0.88%   |
| 1867    | 2         | 0.88%   |
| 975     | 2         | 0.88%   |
| 5600    | 1         | 0.44%   |
| 4800    | 1         | 0.44%   |
| 1066    | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 66.67%  |
| Samsung Electronics | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung ML-1865        | 1         | 33.33%  |
| HP LaserJet 1018       | 1         | 33.33%  |
| HP DeskJet 2300 series | 1         | 33.33%  |

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
| Chicony Electronics                    | 48        | 19.67%  |
| Bison Electronics                      | 26        | 10.66%  |
| Microdia                               | 23        | 9.43%   |
| Realtek Semiconductor                  | 18        | 7.38%   |
| IMC Networks                           | 18        | 7.38%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 6.56%   |
| Suyin                                  | 15        | 6.15%   |
| Quanta                                 | 13        | 5.33%   |
| Sunplus Innovation Technology          | 12        | 4.92%   |
| Luxvisions Innotech Limited            | 9         | 3.69%   |
| Syntek                                 | 6         | 2.46%   |
| Sonix Technology                       | 6         | 2.46%   |
| ALi                                    | 6         | 2.46%   |
| Lenovo                                 | 4         | 1.64%   |
| Importek                               | 4         | 1.64%   |
| Silicon Motion                         | 3         | 1.23%   |
| Ricoh                                  | 3         | 1.23%   |
| Apple                                  | 3         | 1.23%   |
| Lite-On Technology                     | 2         | 0.82%   |
| Alcor Micro                            | 2         | 0.82%   |
| Tobii Technology AB                    | 1         | 0.41%   |
| OmniVision Technologies                | 1         | 0.41%   |
| Logitech                               | 1         | 0.41%   |
| icSpring                               | 1         | 0.41%   |
| Genesys Logic                          | 1         | 0.41%   |
| DigiTech                               | 1         | 0.41%   |
| Acer                                   | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                          | 11        | 4.51%   |
| Chicony Integrated Camera                                       | 10        | 4.1%    |
| Sunplus Integrated_Webcam_HD                                    | 8         | 3.28%   |
| Realtek Integrated_Webcam_HD                                    | 8         | 3.28%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 8         | 3.28%   |
| Microdia USB 2.0 Camera                                         | 7         | 2.87%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 7         | 2.87%   |
| Bison USB Camera                                                | 7         | 2.87%   |
| Sonix USB2.0 HD UVC WebCam                                      | 5         | 2.05%   |
| Microdia Integrated_Webcam_HD                                   | 5         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam   | 5         | 2.05%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 1.64%   |
| IMC Networks XHC Camera                                         | 4         | 1.64%   |
| Chicony Lenovo EasyCamera                                       | 4         | 1.64%   |
| Bison USB HD Webcam                                             | 4         | 1.64%   |
| Suyin HP Webcam 101                                             | 3         | 1.23%   |
| Quanta HP TrueVision HD Webcam                                  | 3         | 1.23%   |
| Quanta HD Webcam                                                | 3         | 1.23%   |
| Quanta HD User Facing                                           | 3         | 1.23%   |
| Luxvisions Innotech Limited Integrated RGB Camera               | 3         | 1.23%   |
| Lenovo CNF7237&CNF7238                                          | 3         | 1.23%   |
| IMC Networks Integrated Camera                                  | 3         | 1.23%   |
| Chicony HD WebCam                                               | 3         | 1.23%   |
| Bison Lenovo EasyCamera                                         | 3         | 1.23%   |
| Bison Integrated Camera                                         | 3         | 1.23%   |
| Bison HD Webcam                                                 | 3         | 1.23%   |
| ALi WebCam                                                      | 3         | 1.23%   |
| ALi Gateway Webcam                                              | 3         | 1.23%   |
| Syntek Integrated Camera                                        | 2         | 0.82%   |
| Suyin USB2.0 UVC 1.3M WebCam                                    | 2         | 0.82%   |
| Suyin Integrated_Webcam_HD                                      | 2         | 0.82%   |
| Suyin HP Webcam                                                 | 2         | 0.82%   |
| Suyin HP TrueVision HD                                          | 2         | 0.82%   |
| Ricoh Laptop_Integrated_Webcam_FHD                              | 2         | 0.82%   |
| Realtek Integrated Webcam HD                                    | 2         | 0.82%   |
| Microdia Integrated_Webcam_1.3M                                 | 2         | 0.82%   |
| Microdia Integrated Webcam                                      | 2         | 0.82%   |
| Importek 1.3Mega Web Camera                                     | 2         | 0.82%   |
| IMC Networks Lenovo EasyCamera                                  | 2         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam                                    | 2         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 42.31%  |
| Upek                       | 4         | 15.38%  |
| Shenzhen Goodix Technology | 3         | 11.54%  |
| AuthenTec                  | 3         | 11.54%  |
| Synaptics                  | 2         | 7.69%   |
| Elan Microelectronics      | 2         | 7.69%   |
| Futronic Technology        | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 4         | 15.38%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 15.38%  |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 7.69%   |
| Validity Sensors Fingerprint scanner                   | 2         | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 7.69%   |
| Elan ELAN:ARM-M4                                       | 2         | 7.69%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 7.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.85%   |
| Futronic Fingerprint Scanner Model FS88                | 1         | 3.85%   |
| AuthenTec AES1600                                      | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 83.33%  |
| Alcor Micro | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom 5880                                  | 6         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 4         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 226       | 73.14%  |
| 1     | 64        | 20.71%  |
| 2     | 16        | 5.18%   |
| 4     | 2         | 0.65%   |
| 3     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 34        | 33.33%  |
| Fingerprint reader       | 26        | 25.49%  |
| Net/wireless             | 12        | 11.76%  |
| Chipcard                 | 12        | 11.76%  |
| Sound                    | 6         | 5.88%   |
| Camera                   | 5         | 4.9%    |
| Storage                  | 2         | 1.96%   |
| Multimedia controller    | 2         | 1.96%   |
| Communication controller | 1         | 0.98%   |
| Card reader              | 1         | 0.98%   |
| Bluetooth                | 1         | 0.98%   |

