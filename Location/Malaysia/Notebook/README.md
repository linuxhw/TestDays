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

Total: 344

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E7450              | [6ba017a802](https://linux-hardware.org/?probe=6ba017a802) | Sep 23, 2023 |
| Lenovo        | ThinkPad E480 20KNS0MM00    | [ef56d33374](https://linux-hardware.org/?probe=ef56d33374) | Sep 19, 2023 |
| MSI           | Modern 14 C11M              | [4c6156df05](https://linux-hardware.org/?probe=4c6156df05) | Sep 18, 2023 |
| Dell          | Latitude E7470              | [8b06be8e07](https://linux-hardware.org/?probe=8b06be8e07) | Sep 18, 2023 |
| Dell          | Latitude E7470              | [c2acf11095](https://linux-hardware.org/?probe=c2acf11095) | Sep 18, 2023 |
| Fujitsu       | LIFEBOOK UH554              | [92f2e6135e](https://linux-hardware.org/?probe=92f2e6135e) | Sep 13, 2023 |
| Acer          | AOD270                      | [d7d4474d69](https://linux-hardware.org/?probe=d7d4474d69) | Sep 11, 2023 |
| Apple         | MacBookPro11,3              | [bfdd099826](https://linux-hardware.org/?probe=bfdd099826) | Sep 06, 2023 |
| HP            | EliteBook 830 G5            | [8a0ad0652e](https://linux-hardware.org/?probe=8a0ad0652e) | Sep 06, 2023 |
| Acer          | Aspire 4738Z                | [88b34596c0](https://linux-hardware.org/?probe=88b34596c0) | Sep 05, 2023 |
| Acer          | Aspire 4741                 | [2f2b673625](https://linux-hardware.org/?probe=2f2b673625) | Sep 04, 2023 |
| Dell          | Inspiron 15 3511            | [d53deba94a](https://linux-hardware.org/?probe=d53deba94a) | Aug 31, 2023 |
| Lenovo        | ThinkPad X201 36809D4       | [1e4311af0b](https://linux-hardware.org/?probe=1e4311af0b) | Aug 28, 2023 |
| Dell          | Latitude 5580               | [eb2a994e98](https://linux-hardware.org/?probe=eb2a994e98) | Aug 28, 2023 |
| Acer          | Aspire 4810T                | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | [d28f06dcc5](https://linux-hardware.org/?probe=d28f06dcc5) | Aug 25, 2023 |
| HP            | Notebook                    | [dd8c90afbe](https://linux-hardware.org/?probe=dd8c90afbe) | Aug 16, 2023 |
| HP            | EliteBook 2740p             | [b288a65e53](https://linux-hardware.org/?probe=b288a65e53) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1b9794e2e3](https://linux-hardware.org/?probe=1b9794e2e3) | Aug 06, 2023 |
| HP            | OMEN by Laptop              | [78566a197e](https://linux-hardware.org/?probe=78566a197e) | Aug 05, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| HP            | Laptop 14-bs0xx             | [e074ee90be](https://linux-hardware.org/?probe=e074ee90be) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [fee4019ae0](https://linux-hardware.org/?probe=fee4019ae0) | Jul 22, 2023 |
| HP            | ElitePad 1000 G2            | [0878c1fae6](https://linux-hardware.org/?probe=0878c1fae6) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [a8779931a8](https://linux-hardware.org/?probe=a8779931a8) | Jul 18, 2023 |
| Unknown       | Unknown                     | [85d7cb63b8](https://linux-hardware.org/?probe=85d7cb63b8) | Jul 16, 2023 |
| HP            | Notebook                    | [50376757dd](https://linux-hardware.org/?probe=50376757dd) | Jul 13, 2023 |
| HP            | OMEN by Laptop              | [87a1bbb5cc](https://linux-hardware.org/?probe=87a1bbb5cc) | Jul 08, 2023 |
| HP            | Laptop 14s-dk0xxx           | [8f01854bc7](https://linux-hardware.org/?probe=8f01854bc7) | Jul 07, 2023 |
| Dell          | Latitude E5440              | [03ed0e9ebb](https://linux-hardware.org/?probe=03ed0e9ebb) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [51d003ae6a](https://linux-hardware.org/?probe=51d003ae6a) | Jul 02, 2023 |
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
| Ubuntu 20.04        | 29        | 11.33%  |
| Ubuntu 22.04        | 16        | 6.25%   |
| Ubuntu 18.04        | 12        | 4.69%   |
| Pop!_OS 22.04       | 8         | 3.13%   |
| Pop!_OS 20.10       | 8         | 3.13%   |
| KDE neon 20.04      | 7         | 2.73%   |
| ArcoLinux Rolling   | 7         | 2.73%   |
| Pop!_OS 21.04       | 6         | 2.34%   |
| Arch Rolling        | 6         | 2.34%   |
| OpenMandriva 4.2    | 5         | 1.95%   |
| OpenMandriva 23.01  | 5         | 1.95%   |
| Zorin 16            | 4         | 1.56%   |
| Ubuntu 23.04        | 4         | 1.56%   |
| Ubuntu 16.04        | 4         | 1.56%   |
| OpenMandriva 4.50   | 4         | 1.56%   |
| OpenMandriva 4.3    | 4         | 1.56%   |
| OpenMandriva 23.08  | 4         | 1.56%   |
| Linux Mint 21.1     | 4         | 1.56%   |
| Fedora 33           | 4         | 1.56%   |
| EndeavourOS Rolling | 4         | 1.56%   |
| Xubuntu 22.04       | 3         | 1.17%   |
| Ubuntu 21.04        | 3         | 1.17%   |
| Ubuntu 19.04        | 3         | 1.17%   |
| Nobara 37           | 3         | 1.17%   |
| Manjaro             | 3         | 1.17%   |
| Linux Mint 20.2     | 3         | 1.17%   |
| Linux Mint 19.3     | 3         | 1.17%   |
| Fedora 38           | 3         | 1.17%   |
| Fedora 37           | 3         | 1.17%   |
| Fedora 35           | 3         | 1.17%   |
| Fedora 34           | 3         | 1.17%   |
| Debian 11           | 3         | 1.17%   |
| Arch                | 3         | 1.17%   |
| Zorin 15            | 2         | 0.78%   |
| Ubuntu Unity 16.04  | 2         | 0.78%   |
| Ubuntu 20.10        | 2         | 0.78%   |
| Ubuntu 19.10        | 2         | 0.78%   |
| Pop!_OS 20.04       | 2         | 0.78%   |
| Manjaro 21.0.7      | 2         | 0.78%   |
| Lubuntu 18.04       | 2         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 75        | 30.49%  |
| Pop!_OS       | 23        | 9.35%   |
| OpenMandriva  | 23        | 9.35%   |
| Fedora        | 16        | 6.5%    |
| Linux Mint    | 12        | 4.88%   |
| KDE neon      | 9         | 3.66%   |
| Arch          | 9         | 3.66%   |
| Manjaro       | 8         | 3.25%   |
| Zorin         | 7         | 2.85%   |
| ArcoLinux     | 7         | 2.85%   |
| Endless       | 5         | 2.03%   |
| Debian        | 5         | 2.03%   |
| Xubuntu       | 4         | 1.63%   |
| Kubuntu       | 4         | 1.63%   |
| EndeavourOS   | 4         | 1.63%   |
| Elementary    | 4         | 1.63%   |
| Nobara        | 3         | 1.22%   |
| Lubuntu       | 3         | 1.22%   |
| Kali          | 3         | 1.22%   |
| CentOS        | 3         | 1.22%   |
| Ubuntu Unity  | 2         | 0.81%   |
| Ubuntu Budgie | 2         | 0.81%   |
| SteamOS       | 2         | 0.81%   |
| Archcraft     | 2         | 0.81%   |
| Xero          | 1         | 0.41%   |
| Ultramarine   | 1         | 0.41%   |
| Ubuntu MATE   | 1         | 0.41%   |
| ROSA          | 1         | 0.41%   |
| Rocky Linux   | 1         | 0.41%   |
| Reborn OS     | 1         | 0.41%   |
| Peppermint    | 1         | 0.41%   |
| MX            | 1         | 0.41%   |
| LMDE          | 1         | 0.41%   |
| Gentoo        | 1         | 0.41%   |
| BuildRoot     | 1         | 0.41%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 5         | 1.81%   |
| 5.11.0-7620-generic      | 5         | 1.81%   |
| 6.3.9-arch1-1            | 4         | 1.45%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.45%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.45%   |
| 5.0.0-37-generic         | 4         | 1.45%   |
| 6.4.11-desktop-1omv2390  | 3         | 1.09%   |
| 6.2.6-76060206-generic   | 3         | 1.09%   |
| 5.8.0-7642-generic       | 3         | 1.09%   |
| 5.4.0-58-generic         | 3         | 1.09%   |
| 5.4.0-54-generic         | 3         | 1.09%   |
| 5.4.0-42-generic         | 3         | 1.09%   |
| 5.19.0-46-generic        | 3         | 1.09%   |
| 5.15.0-56-generic        | 3         | 1.09%   |
| 5.15.0-52-generic        | 3         | 1.09%   |
| 5.12.4-desktop-1omv4050  | 3         | 1.09%   |
| 5.11.0-46-generic        | 3         | 1.09%   |
| 5.0.0-23-generic         | 3         | 1.09%   |
| 4.15.0-45-generic        | 3         | 1.09%   |
| 6.2.0-33-generic         | 2         | 0.72%   |
| 5.8.0-7630-generic       | 2         | 0.72%   |
| 5.8.0-45-generic         | 2         | 0.72%   |
| 5.4.0-89-generic         | 2         | 0.72%   |
| 5.4.0-64-generic         | 2         | 0.72%   |
| 5.4.0-52-generic         | 2         | 0.72%   |
| 5.3.0-51-generic         | 2         | 0.72%   |
| 5.19.0-76051900-generic  | 2         | 0.72%   |
| 5.19.0-38-generic        | 2         | 0.72%   |
| 5.17.5-76051705-generic  | 2         | 0.72%   |
| 5.17.1-051701-generic    | 2         | 0.72%   |
| 5.15.0-58-generic        | 2         | 0.72%   |
| 5.15.0-46-generic        | 2         | 0.72%   |
| 5.15.0-40-generic        | 2         | 0.72%   |
| 5.15.0-25-generic        | 2         | 0.72%   |
| 5.13.0-7614-generic      | 2         | 0.72%   |
| 5.13.0-22-generic        | 2         | 0.72%   |
| 5.11.0-7614-generic      | 2         | 0.72%   |
| 5.11.0-40-generic        | 2         | 0.72%   |
| 5.11.0-27-generic        | 2         | 0.72%   |
| 5.10.79-1-lts            | 2         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 30        | 11.32%  |
| 5.15.0  | 21        | 7.92%   |
| 5.11.0  | 17        | 6.42%   |
| 5.8.0   | 15        | 5.66%   |
| 5.13.0  | 12        | 4.53%   |
| 4.15.0  | 12        | 4.53%   |
| 5.0.0   | 10        | 3.77%   |
| 5.3.0   | 9         | 3.4%    |
| 5.19.0  | 9         | 3.4%    |
| 6.1.1   | 6         | 2.26%   |
| 6.2.0   | 5         | 1.89%   |
| 6.4.11  | 4         | 1.51%   |
| 6.3.9   | 4         | 1.51%   |
| 6.2.6   | 4         | 1.51%   |
| 5.16.7  | 4         | 1.51%   |
| 5.10.14 | 4         | 1.51%   |
| 5.10.0  | 4         | 1.51%   |
| 4.18.0  | 4         | 1.51%   |
| 5.17.1  | 3         | 1.13%   |
| 5.16.15 | 3         | 1.13%   |
| 5.12.4  | 3         | 1.13%   |
| 6.4.8   | 2         | 0.75%   |
| 6.2.9   | 2         | 0.75%   |
| 6.2.8   | 2         | 0.75%   |
| 5.9.0   | 2         | 0.75%   |
| 5.18.0  | 2         | 0.75%   |
| 5.17.5  | 2         | 0.75%   |
| 5.12.9  | 2         | 0.75%   |
| 5.10.79 | 2         | 0.75%   |
| 5.10.42 | 2         | 0.75%   |
| 5.10.13 | 2         | 0.75%   |
| 4.4.0   | 2         | 0.75%   |
| 3.10.0  | 2         | 0.75%   |
| 6.4.7   | 1         | 0.38%   |
| 6.4.6   | 1         | 0.38%   |
| 6.4.2   | 1         | 0.38%   |
| 6.4.13  | 1         | 0.38%   |
| 6.4.10  | 1         | 0.38%   |
| 6.4.1   | 1         | 0.38%   |
| 6.4.0   | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 30        | 11.54%  |
| 5.15    | 24        | 9.23%   |
| 5.8     | 22        | 8.46%   |
| 5.11    | 20        | 7.69%   |
| 5.10    | 17        | 6.54%   |
| 6.2     | 14        | 5.38%   |
| 5.13    | 13        | 5%      |
| 6.4     | 12        | 4.62%   |
| 5.19    | 12        | 4.62%   |
| 4.15    | 12        | 4.62%   |
| 5.0     | 10        | 3.85%   |
| 6.1     | 9         | 3.46%   |
| 5.3     | 9         | 3.46%   |
| 6.3     | 7         | 2.69%   |
| 5.16    | 7         | 2.69%   |
| 5.12    | 7         | 2.69%   |
| 5.17    | 6         | 2.31%   |
| 5.18    | 5         | 1.92%   |
| 5.14    | 5         | 1.92%   |
| 4.18    | 4         | 1.54%   |
| 6.0     | 3         | 1.15%   |
| 5.9     | 3         | 1.15%   |
| 5.7     | 2         | 0.77%   |
| 4.4     | 2         | 0.77%   |
| 3.10    | 2         | 0.77%   |
| 5.6     | 1         | 0.38%   |
| 4.10    | 1         | 0.38%   |
| 4.1     | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 231       | 98.72%  |
| i686   | 3         | 1.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 117       | 47.37%  |
| KDE5          | 48        | 19.43%  |
| Unknown       | 22        | 8.91%   |
| XFCE          | 18        | 7.29%   |
| X-Cinnamon    | 11        | 4.45%   |
| KDE           | 8         | 3.24%   |
| Pantheon      | 4         | 1.62%   |
| MATE          | 4         | 1.62%   |
| Unity         | 2         | 0.81%   |
| openbox       | 2         | 0.81%   |
| LXQt          | 2         | 0.81%   |
| i3            | 2         | 0.81%   |
| Budgie        | 2         | 0.81%   |
| Peppermint    | 1         | 0.4%    |
| LXDE          | 1         | 0.4%    |
| Hyprland      | 1         | 0.4%    |
| GNOME Classic | 1         | 0.4%    |
| bspwm         | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 182       | 74.59%  |
| Wayland | 50        | 20.49%  |
| Unknown | 9         | 3.69%   |
| Tty     | 3         | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 116       | 48.13%  |
| SDDM    | 47        | 19.5%   |
| GDM3    | 35        | 14.52%  |
| GDM     | 25        | 10.37%  |
| LightDM | 16        | 6.64%   |
| TDM     | 2         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 190       | 79.83%  |
| Unknown | 17        | 7.14%   |
| en_GB   | 13        | 5.46%   |
| en_SG   | 8         | 3.36%   |
| C       | 3         | 1.26%   |
| ms_MY   | 2         | 0.84%   |
| zh_TW   | 1         | 0.42%   |
| ja_JP   | 1         | 0.42%   |
| id_ID   | 1         | 0.42%   |
| en_MY   | 1         | 0.42%   |
| de_DE   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 119       | 50.42%  |
| EFI  | 117       | 49.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 175       | 72.61%  |
| Btrfs   | 26        | 10.79%  |
| Overlay | 21        | 8.71%   |
| Xfs     | 5         | 2.07%   |
| Unknown | 5         | 2.07%   |
| Zfs     | 4         | 1.66%   |
| Tmpfs   | 4         | 1.66%   |
| Ext2    | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 125       | 52.08%  |
| GPT     | 86        | 35.83%  |
| MBR     | 29        | 12.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 203       | 85.29%  |
| Yes       | 35        | 14.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 70%     |
| Yes       | 72        | 30%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 47        | 20.09%  |
| Hewlett-Packard     | 44        | 18.8%   |
| ASUSTek Computer    | 37        | 15.81%  |
| Lenovo              | 32        | 13.68%  |
| Acer                | 23        | 9.83%   |
| MSI                 | 8         | 3.42%   |
| Apple               | 7         | 2.99%   |
| Fujitsu             | 5         | 2.14%   |
| Sony                | 4         | 1.71%   |
| Samsung Electronics | 3         | 1.28%   |
| HUAWEI              | 3         | 1.28%   |
| Unknown             | 3         | 1.28%   |
| NEC Computers       | 2         | 0.85%   |
| ILLEGEAR            | 2         | 0.85%   |
| Chuwi               | 2         | 0.85%   |
| Valve               | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| Timi                | 1         | 0.43%   |
| System76            | 1         | 0.43%   |
| SNS Network (M)     | 1         | 0.43%   |
| Infinix             | 1         | 0.43%   |
| HONOR               | 1         | 0.43%   |
| GPD                 | 1         | 0.43%   |
| Gigabyte Technology | 1         | 0.43%   |
| BUSH                | 1         | 0.43%   |
| AZW                 | 1         | 0.43%   |
| Alienware           | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Notebook                         | 5         | 2.14%   |
| Unknown                             | 3         | 1.28%   |
| MSI Modern 14 B5M                   | 2         | 0.85%   |
| HP Pavilion dv6                     | 2         | 0.85%   |
| HP Laptop 15-bs0xx                  | 2         | 0.85%   |
| HP ENVY 4                           | 2         | 0.85%   |
| HP EliteBook 8470p                  | 2         | 0.85%   |
| HP EliteBook 840 G2                 | 2         | 0.85%   |
| HP Compaq Presario CQ40             | 2         | 0.85%   |
| Dell XPS 15 7590                    | 2         | 0.85%   |
| Dell Latitude E6520                 | 2         | 0.85%   |
| Dell Latitude E6440                 | 2         | 0.85%   |
| Dell Latitude 3410                  | 2         | 0.85%   |
| ASUS K45VD                          | 2         | 0.85%   |
| ASUS K43SD                          | 2         | 0.85%   |
| Apple MacBookPro8,1                 | 2         | 0.85%   |
| Valve Jupiter                       | 1         | 0.43%   |
| Toshiba dynabook Satellite B552/H   | 1         | 0.43%   |
| Timi RedmiBook 14 II                | 1         | 0.43%   |
| System76 Galago Pro                 | 1         | 0.43%   |
| Sony VPCSB26FG                      | 1         | 0.43%   |
| Sony VPCEG16EG                      | 1         | 0.43%   |
| Sony VPCEA42EG                      | 1         | 0.43%   |
| Sony VGN-Z27GN_X                    | 1         | 0.43%   |
| SNS Network (M) JOI Book 150        | 1         | 0.43%   |
| Samsung RV413/RV513                 | 1         | 0.43%   |
| Samsung 730U3E/740U3E               | 1         | 0.43%   |
| Samsung 535U3C                      | 1         | 0.43%   |
| NEC Computers PC-VK27MXZCG          | 1         | 0.43%   |
| NEC Computers PC-VK27MCZCK          | 1         | 0.43%   |
| MSI Stealth 14Studio A13VE          | 1         | 0.43%   |
| MSI Prestige 15 A10SC               | 1         | 0.43%   |
| MSI Modern 14 C11M                  | 1         | 0.43%   |
| MSI GT70 2OC/2OD                    | 1         | 0.43%   |
| MSI GP70 2PE                        | 1         | 0.43%   |
| MSI GL62M 7RDX                      | 1         | 0.43%   |
| Lenovo Yoga 500-15IBD 80N6          | 1         | 0.43%   |
| Lenovo Y520-15IKBN 80WK             | 1         | 0.43%   |
| Lenovo XiaoXinAir 14+ ACN 2021 82L7 | 1         | 0.43%   |
| Lenovo U310                         | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 22        | 9.4%    |
| Lenovo ThinkPad            | 19        | 8.12%   |
| Dell Inspiron              | 14        | 5.98%   |
| Acer Aspire                | 14        | 5.98%   |
| HP EliteBook               | 9         | 3.85%   |
| HP Pavilion                | 7         | 2.99%   |
| HP Laptop                  | 7         | 2.99%   |
| ASUS VivoBook              | 6         | 2.56%   |
| HP Notebook                | 5         | 2.14%   |
| Dell XPS                   | 5         | 2.14%   |
| Lenovo IdeaPad             | 4         | 1.71%   |
| HP Compaq                  | 4         | 1.71%   |
| Fujitsu LIFEBOOK           | 4         | 1.71%   |
| MSI Modern                 | 3         | 1.28%   |
| HP ENVY                    | 3         | 1.28%   |
| Dell Precision             | 3         | 1.28%   |
| ASUS ROG                   | 3         | 1.28%   |
| Apple MacBookPro8          | 3         | 1.28%   |
| Acer Nitro                 | 3         | 1.28%   |
| Unknown                    | 3         | 1.28%   |
| HP ProBook                 | 2         | 0.85%   |
| ASUS K45VD                 | 2         | 0.85%   |
| ASUS K43SD                 | 2         | 0.85%   |
| Valve Jupiter              | 1         | 0.43%   |
| Toshiba dynabook           | 1         | 0.43%   |
| Timi RedmiBook             | 1         | 0.43%   |
| System76 Galago            | 1         | 0.43%   |
| Sony VPCSB26FG             | 1         | 0.43%   |
| Sony VPCEG16EG             | 1         | 0.43%   |
| Sony VPCEA42EG             | 1         | 0.43%   |
| Sony VGN-Z27GN             | 1         | 0.43%   |
| SNS Network (M) JOI        | 1         | 0.43%   |
| Samsung RV413              | 1         | 0.43%   |
| Samsung 730U3E             | 1         | 0.43%   |
| Samsung 535U3C             | 1         | 0.43%   |
| NEC Computers PC-VK27MXZCG | 1         | 0.43%   |
| NEC Computers PC-VK27MCZCK | 1         | 0.43%   |
| MSI Stealth                | 1         | 0.43%   |
| MSI Prestige               | 1         | 0.43%   |
| MSI GT70                   | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 29        | 12.39%  |
| 2013 | 23        | 9.83%   |
| 2020 | 22        | 9.4%    |
| 2021 | 21        | 8.97%   |
| 2019 | 19        | 8.12%   |
| 2012 | 17        | 7.26%   |
| 2018 | 16        | 6.84%   |
| 2015 | 15        | 6.41%   |
| 2010 | 15        | 6.41%   |
| 2017 | 14        | 5.98%   |
| 2014 | 12        | 5.13%   |
| 2016 | 8         | 3.42%   |
| 2008 | 8         | 3.42%   |
| 2009 | 7         | 2.99%   |
| 2022 | 5         | 2.14%   |
| 2007 | 2         | 0.85%   |
| 2023 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 234       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 213       | 90.64%  |
| Enabled  | 22        | 9.36%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 232       | 99.15%  |
| Yes  | 2         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 28.09%  |
| 3.01-4.0    | 58        | 24.68%  |
| 8.01-16.0   | 47        | 20%     |
| 16.01-24.0  | 32        | 13.62%  |
| 32.01-64.0  | 10        | 4.26%   |
| 1.01-2.0    | 8         | 3.4%    |
| 2.01-3.0    | 5         | 2.13%   |
| 24.01-32.0  | 4         | 1.7%    |
| 64.01-256.0 | 3         | 1.28%   |
| 0.51-1.0    | 2         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 88        | 33.98%  |
| 2.01-3.0  | 78        | 30.12%  |
| 3.01-4.0  | 36        | 13.9%   |
| 4.01-8.0  | 31        | 11.97%  |
| 0.51-1.0  | 18        | 6.95%   |
| 8.01-16.0 | 8         | 3.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 168       | 70.29%  |
| 2      | 61        | 25.52%  |
| 3      | 8         | 3.35%   |
| 4      | 2         | 0.84%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 66.67%  |
| Yes       | 78        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 83.76%  |
| No        | 38        | 16.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 96.15%  |
| No        | 9         | 3.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 80.43%  |
| No        | 46        | 19.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Malaysia | 234       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 87        | 34.66%  |
| Petaling Jaya          | 28        | 11.16%  |
| Shah Alam              | 12        | 4.78%   |
| Johor Bahru            | 12        | 4.78%   |
| Puchong Batu Dua Belas | 9         | 3.59%   |
| Ipoh                   | 9         | 3.59%   |
| Subang Jaya            | 8         | 3.19%   |
| Sungai Buloh           | 6         | 2.39%   |
| Seremban               | 6         | 2.39%   |
| Kota Kinabalu          | 6         | 2.39%   |
| Kajang                 | 6         | 2.39%   |
| Sungai Petani          | 5         | 1.99%   |
| Skudai                 | 4         | 1.59%   |
| Kulai                  | 4         | 1.59%   |
| Kota Bharu             | 4         | 1.59%   |
| Marabu                 | 3         | 1.2%    |
| Klang                  | 3         | 1.2%    |
| George Town            | 3         | 1.2%    |
| Cyberjaya              | 3         | 1.2%    |
| Tawau                  | 2         | 0.8%    |
| Nibong Tebal           | 2         | 0.8%    |
| Malacca                | 2         | 0.8%    |
| Kulim                  | 2         | 0.8%    |
| Kuching                | 2         | 0.8%    |
| Cheras                 | 2         | 0.8%    |
| Batu Pahat             | 2         | 0.8%    |
| Tangkak                | 1         | 0.4%    |
| Seri Kembangan         | 1         | 0.4%    |
| Sepang                 | 1         | 0.4%    |
| Semenyih               | 1         | 0.4%    |
| Rawang                 | 1         | 0.4%    |
| Putrajaya              | 1         | 0.4%    |
| Pasir Gudang           | 1         | 0.4%    |
| Long Seridan           | 1         | 0.4%    |
| Kuala Terengganu       | 1         | 0.4%    |
| Kuala Kangsar          | 1         | 0.4%    |
| Kota Tinggi            | 1         | 0.4%    |
| Kamunting              | 1         | 0.4%    |
| Jitra                  | 1         | 0.4%    |
| Hutan Melintang        | 1         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 41        | 47     | 13.44%  |
| WDC                         | 30        | 37     | 9.84%   |
| Samsung Electronics         | 29        | 38     | 9.51%   |
| Toshiba                     | 27        | 33     | 8.85%   |
| Sandisk                     | 21        | 28     | 6.89%   |
| Kingston                    | 21        | 24     | 6.89%   |
| HGST                        | 16        | 23     | 5.25%   |
| Unknown                     | 15        | 21     | 4.92%   |
| Micron Technology           | 8         | 9      | 2.62%   |
| SK hynix                    | 7         | 7      | 2.3%    |
| Hitachi                     | 7         | 12     | 2.3%    |
| A-DATA Technology           | 7         | 7      | 2.3%    |
| Intel                       | 6         | 12     | 1.97%   |
| KIOXIA                      | 5         | 6      | 1.64%   |
| Apacer                      | 5         | 5      | 1.64%   |
| Transcend                   | 4         | 5      | 1.31%   |
| SPCC                        | 4         | 5      | 1.31%   |
| China                       | 4         | 4      | 1.31%   |
| Team                        | 3         | 3      | 0.98%   |
| Phison                      | 3         | 5      | 0.98%   |
| Patriot                     | 3         | 4      | 0.98%   |
| Apple                       | 3         | 4      | 0.98%   |
| TO Exter                    | 2         | 2      | 0.66%   |
| Silicon Motion              | 2         | 2      | 0.66%   |
| Phison Electronics          | 2         | 2      | 0.66%   |
| Netac                       | 2         | 2      | 0.66%   |
| Kingston Technology Company | 2         | 2      | 0.66%   |
| Hewlett-Packard             | 2         | 2      | 0.66%   |
| Fujitsu                     | 2         | 2      | 0.66%   |
| Crucial                     | 2         | 2      | 0.66%   |
| ADATA Technology            | 2         | 2      | 0.66%   |
| winstar                     | 1         | 1      | 0.33%   |
| Western Digital             | 1         | 1      | 0.33%   |
| Verbatim                    | 1         | 1      | 0.33%   |
| USB3.0                      | 1         | 1      | 0.33%   |
| PNY                         | 1         | 1      | 0.33%   |
| Plextor                     | 1         | 1      | 0.33%   |
| Pioneer                     | 1         | 1      | 0.33%   |
| Morebeck-S100               | 1         | 1      | 0.33%   |
| Micron/Crucial Technology   | 1         | 2      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                      | 6         | 1.92%   |
| Toshiba MQ01ABD100 1TB                          | 5         | 1.6%    |
| Unknown MMC Card  32GB                          | 4         | 1.28%   |
| Toshiba MQ04ABF100 1TB                          | 4         | 1.28%   |
| Seagate ST500LT012-1DG142 500GB                 | 4         | 1.28%   |
| Seagate ST1000LM035-1RK172 1TB                  | 4         | 1.28%   |
| SK hynix NVMe SSD Drive 512GB                   | 3         | 0.96%   |
| Seagate ST9320325AS 320GB                       | 3         | 0.96%   |
| Seagate ST1000LM048-2E7172 1TB                  | 3         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 3         | 0.96%   |
| SanDisk SSD PLUS 240GB                          | 3         | 0.96%   |
| SanDisk NVMe SSD Drive 512GB                    | 3         | 0.96%   |
| HGST HTS725050A7E630 500GB                      | 3         | 0.96%   |
| HGST HTS721010A9E630 1TB                        | 3         | 0.96%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                | 2         | 0.64%   |
| WDC WD5000BPVT-24HXZT3 500GB                    | 2         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 2         | 0.64%   |
| WDC PC SN730 NVMe 1024GB                        | 2         | 0.64%   |
| Unknown MMC Card  64GB                          | 2         | 0.64%   |
| Unknown MMC Card  128GB                         | 2         | 0.64%   |
| Toshiba MK5065GSXF 500GB                        | 2         | 0.64%   |
| TO Exter nal USB 3.0 120GB                      | 2         | 0.64%   |
| Seagate ST9750420AS 752GB                       | 2         | 0.64%   |
| Seagate ST9500325AS 500GB                       | 2         | 0.64%   |
| Seagate ST500LM000-1EJ162 500GB                 | 2         | 0.64%   |
| Seagate ST320LT020-9YG142 320GB                 | 2         | 0.64%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 256GB | 2         | 0.64%   |
| Sandisk PC SN530 NVMe WDC 256GB                 | 2         | 0.64%   |
| Samsung SSD 860 EVO 500GB                       | 2         | 0.64%   |
| Samsung SSD 860 EVO 250GB                       | 2         | 0.64%   |
| Samsung NVMe SSD Drive 512GB                    | 2         | 0.64%   |
| Netac SSD 256GB                                 | 2         | 0.64%   |
| Micron 1100 SATA 512GB SSD                      | 2         | 0.64%   |
| KIOXIA NVMe SSD Drive 256GB                     | 2         | 0.64%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB         | 2         | 0.64%   |
| Kingston SH103S3120G 120GB SSD                  | 2         | 0.64%   |
| Kingston SA400S37240G 240GB SSD                 | 2         | 0.64%   |
| Intel SSD 660P Series 1024GB                    | 2         | 0.64%   |
| Intel NVMe SSD Drive 512GB                      | 2         | 0.64%   |
| Hitachi HTS723232A7A364 320GB                   | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 46     | 36.7%   |
| Toshiba             | 22        | 27     | 20.18%  |
| WDC                 | 19        | 26     | 17.43%  |
| HGST                | 16        | 23     | 14.68%  |
| Hitachi             | 7         | 12     | 6.42%   |
| Fujitsu             | 2         | 2      | 1.83%   |
| USB3.0              | 1         | 1      | 0.92%   |
| Unknown             | 1         | 1      | 0.92%   |
| Samsung Electronics | 1         | 3      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 18     | 17%     |
| Samsung Electronics | 15        | 21     | 15%     |
| SanDisk             | 9         | 9      | 9%      |
| Apacer              | 5         | 5      | 5%      |
| A-DATA Technology   | 5         | 5      | 5%      |
| Transcend           | 4         | 4      | 4%      |
| Micron Technology   | 4         | 5      | 4%      |
| China               | 4         | 4      | 4%      |
| WDC                 | 3         | 3      | 3%      |
| Team                | 3         | 3      | 3%      |
| SPCC                | 3         | 4      | 3%      |
| Patriot             | 3         | 4      | 3%      |
| Apple               | 3         | 4      | 3%      |
| Toshiba             | 2         | 2      | 2%      |
| TO Exter            | 2         | 2      | 2%      |
| Netac               | 2         | 2      | 2%      |
| Intel               | 2         | 2      | 2%      |
| Crucial             | 2         | 2      | 2%      |
| Verbatim            | 1         | 1      | 1%      |
| PNY                 | 1         | 1      | 1%      |
| Plextor             | 1         | 1      | 1%      |
| Pioneer             | 1         | 1      | 1%      |
| LS                  | 1         | 1      | 1%      |
| KimMiDi             | 1         | 1      | 1%      |
| JMicron Technology  | 1         | 1      | 1%      |
| Hewlett-Packard     | 1         | 1      | 1%      |
| Gigabyte Technology | 1         | 1      | 1%      |
| Colorful            | 1         | 1      | 1%      |
| ASMT                | 1         | 1      | 1%      |
| Unknown             | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 105       | 141    | 37.5%   |
| SSD     | 89        | 111    | 31.79%  |
| NVMe    | 67        | 98     | 23.93%  |
| MMC     | 14        | 21     | 5%      |
| Unknown | 5         | 6      | 1.79%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 177       | 248    | 66.04%  |
| NVMe | 67        | 98     | 25%     |
| MMC  | 14        | 21     | 5.22%   |
| SAS  | 10        | 10     | 3.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 175    | 69.79%  |
| 0.51-1.0   | 56        | 75     | 29.17%  |
| 1.01-2.0   | 2         | 2      | 1.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 69        | 27.49%  |
| 251-500        | 68        | 27.09%  |
| 501-1000       | 35        | 13.94%  |
| 1-20           | 26        | 10.36%  |
| 51-100         | 20        | 7.97%   |
| 21-50          | 14        | 5.58%   |
| 1001-2000      | 9         | 3.59%   |
| Unknown        | 6         | 2.39%   |
| More than 3000 | 2         | 0.8%    |
| 2001-3000      | 2         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 113       | 43.97%  |
| 21-50     | 50        | 19.46%  |
| 101-250   | 31        | 12.06%  |
| 51-100    | 26        | 10.12%  |
| 251-500   | 18        | 7%      |
| 501-1000  | 7         | 2.72%   |
| Unknown   | 6         | 2.33%   |
| 1001-2000 | 4         | 1.56%   |
| 2001-3000 | 1         | 0.39%   |
| 0         | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                      | 2         | 2      | 8.33%   |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4.17%   |
| WDC WD5000BPVT-24HXZT3 500GB                   | 1         | 1      | 4.17%   |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 4.17%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4.17%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 4.17%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 4.17%   |
| Toshiba MK1059GSMP 1TB                         | 1         | 1      | 4.17%   |
| SPCC Solid State Disk 256GB                    | 1         | 1      | 4.17%   |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 4.17%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 4.17%   |
| Samsung Electronics SSD PM830 2.5 7mm 512GB    | 1         | 1      | 4.17%   |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 2      | 4.17%   |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 4.17%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 4.17%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 3      | 4.17%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 4.17%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 4.17%   |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 4.17%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 4.17%   |
| Unknown                                        | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 5         | 5      | 20.83%  |
| Seagate                   | 4         | 4      | 16.67%  |
| HGST                      | 4         | 4      | 16.67%  |
| Toshiba                   | 3         | 3      | 12.5%   |
| Hitachi                   | 3         | 5      | 12.5%   |
| SPCC                      | 1         | 1      | 4.17%   |
| Samsung Electronics       | 1         | 1      | 4.17%   |
| Micron/Crucial Technology | 1         | 2      | 4.17%   |
| Micron Technology         | 1         | 1      | 4.17%   |
| Unknown                   | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 22.22%  |
| Seagate | 4         | 4      | 22.22%  |
| HGST    | 4         | 4      | 22.22%  |
| Toshiba | 3         | 3      | 16.67%  |
| Hitachi | 3         | 5      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 73.91%  |
| SSD  | 5         | 5      | 21.74%  |
| NVMe | 1         | 2      | 4.35%   |

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
| Detected | 143       | 228    | 56.52%  |
| Works    | 88        | 122    | 34.78%  |
| Malfunc  | 22        | 27     | 8.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 172       | 63.24%  |
| AMD                          | 23        | 8.46%   |
| SanDisk                      | 19        | 6.99%   |
| Samsung Electronics          | 14        | 5.15%   |
| SK hynix                     | 7         | 2.57%   |
| Phison Electronics           | 6         | 2.21%   |
| Kingston Technology Company  | 6         | 2.21%   |
| Silicon Motion               | 5         | 1.84%   |
| KIOXIA                       | 5         | 1.84%   |
| Micron Technology            | 4         | 1.47%   |
| Toshiba America Info Systems | 3         | 1.1%    |
| Nvidia                       | 3         | 1.1%    |
| ADATA Technology             | 2         | 0.74%   |
| Micron/Crucial Technology    | 1         | 0.37%   |
| Biwin Storage Technology     | 1         | 0.37%   |
| ASMedia Technology           | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 24        | 8.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 21        | 7.27%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 7.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 6.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 5.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 3.11%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 2.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 6         | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 2.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.38%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 1.38%   |
| Intel SSD 660P Series                                                            | 4         | 1.38%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 1.04%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 1.04%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                            | 3         | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 1.04%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.04%   |
| Phison E12 NVMe Controller                                                       | 3         | 1.04%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 3         | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.04%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.04%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.69%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.69%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 2         | 0.69%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.69%   |
| Kingston Company KC2000/KC2500 NVMe SSD                                          | 2         | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.69%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 163       | 60.59%  |
| NVMe | 66        | 24.54%  |
| RAID | 28        | 10.41%  |
| IDE  | 12        | 4.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 193       | 82.48%  |
| AMD    | 41        | 17.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 3.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 1.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.7%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.28%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.28%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.28%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.28%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.28%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.28%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.85%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.85%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.85%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.85%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 0.85%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.85%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 2         | 0.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.85%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.85%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.85%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.85%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 76        | 32.34%  |
| Intel Core i7           | 48        | 20.43%  |
| Intel Core i3           | 16        | 6.81%   |
| Intel Celeron           | 14        | 5.96%   |
| AMD Ryzen 5             | 14        | 5.96%   |
| Other                   | 13        | 5.53%   |
| Intel Core 2 Duo        | 10        | 4.26%   |
| Intel Atom              | 7         | 2.98%   |
| AMD Ryzen 7             | 5         | 2.13%   |
| Intel Pentium           | 4         | 1.7%    |
| AMD A6                  | 4         | 1.7%    |
| Intel Pentium Dual-Core | 3         | 1.28%   |
| AMD Ryzen 7 PRO         | 3         | 1.28%   |
| AMD Athlon              | 3         | 1.28%   |
| Intel Genuine           | 2         | 0.85%   |
| AMD Ryzen 9             | 2         | 0.85%   |
| AMD E                   | 2         | 0.85%   |
| AMD A4                  | 2         | 0.85%   |
| AMD A12                 | 2         | 0.85%   |
| Intel Xeon              | 1         | 0.43%   |
| Intel Core i9           | 1         | 0.43%   |
| AMD Ryzen 3             | 1         | 0.43%   |
| AMD FX                  | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 129       | 55.13%  |
| 4      | 65        | 27.78%  |
| 6      | 20        | 8.55%   |
| 8      | 11        | 4.7%    |
| 1      | 6         | 2.56%   |
| 14     | 3         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 234       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 189       | 80.43%  |
| 1      | 46        | 19.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 232       | 98.72%  |
| Unknown        | 3         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 29.63%  |
| 0x206a7    | 20        | 8.23%   |
| 0x306a9    | 17        | 7%      |
| 0x906ea    | 8         | 3.29%   |
| 0x40651    | 8         | 3.29%   |
| 0x306d4    | 7         | 2.88%   |
| 0x306c3    | 7         | 2.88%   |
| 0x20655    | 7         | 2.88%   |
| 0x806e9    | 6         | 2.47%   |
| 0x406e3    | 6         | 2.47%   |
| 0xa0652    | 5         | 2.06%   |
| 0x1067a    | 5         | 2.06%   |
| 0x806ec    | 4         | 1.65%   |
| 0x806ea    | 4         | 1.65%   |
| 0x30678    | 4         | 1.65%   |
| 0x20652    | 4         | 1.65%   |
| 0x08600104 | 4         | 1.65%   |
| 0x06001119 | 4         | 1.65%   |
| 0x806eb    | 3         | 1.23%   |
| 0x806d1    | 3         | 1.23%   |
| 0x806c1    | 3         | 1.23%   |
| 0x08108109 | 3         | 1.23%   |
| 0x906e9    | 2         | 0.82%   |
| 0x706e5    | 2         | 0.82%   |
| 0x706a8    | 2         | 0.82%   |
| 0x706a1    | 2         | 0.82%   |
| 0x406c4    | 2         | 0.82%   |
| 0x106ca    | 2         | 0.82%   |
| 0x10676    | 2         | 0.82%   |
| 0x0a50000d | 2         | 0.82%   |
| 0x0a50000b | 2         | 0.82%   |
| 0x08608103 | 2         | 0.82%   |
| 0x08108102 | 2         | 0.82%   |
| 0x0700010f | 2         | 0.82%   |
| 0xa0660    | 1         | 0.41%   |
| 0x906a3    | 1         | 0.41%   |
| 0x6fd      | 1         | 0.41%   |
| 0x6fb      | 1         | 0.41%   |
| 0x406c3    | 1         | 0.41%   |
| 0x0a50000c | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 15.81%  |
| SandyBridge      | 28        | 11.97%  |
| IvyBridge        | 22        | 9.4%    |
| Haswell          | 20        | 8.55%   |
| Westmere         | 14        | 5.98%   |
| Penryn           | 12        | 5.13%   |
| Zen+             | 10        | 4.27%   |
| Skylake          | 10        | 4.27%   |
| Silvermont       | 9         | 3.85%   |
| Broadwell        | 9         | 3.85%   |
| Zen 3            | 7         | 2.99%   |
| IceLake          | 7         | 2.99%   |
| Zen 2            | 6         | 2.56%   |
| TigerLake        | 6         | 2.56%   |
| CometLake        | 6         | 2.56%   |
| Piledriver       | 5         | 2.14%   |
| Goldmont plus    | 4         | 1.71%   |
| Core             | 3         | 1.28%   |
| Bonnell          | 3         | 1.28%   |
| Alderlake Hybrid | 3         | 1.28%   |
| Unknown          | 3         | 1.28%   |
| Zen              | 2         | 0.85%   |
| Jaguar           | 2         | 0.85%   |
| Excavator        | 2         | 0.85%   |
| Bobcat           | 2         | 0.85%   |
| Steamroller      | 1         | 0.43%   |
| K8 & K10 hybrid  | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 182       | 56.88%  |
| Nvidia | 77        | 24.06%  |
| AMD    | 61        | 19.06%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 8.21%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 6.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 3.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 3.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 2.74%   |
| Intel HD Graphics 5500                                                                   | 9         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.74%   |
| Intel HD Graphics 620                                                                    | 8         | 2.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 2.13%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 2.13%   |
| AMD Renoir                                                                               | 6         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.22%   |
| Intel HD Graphics 630                                                                    | 4         | 1.22%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.22%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.91%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.91%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.91%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.91%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.91%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.91%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.61%   |
| Nvidia GM108M [GeForce 930M]                                                             | 2         | 0.61%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.61%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.61%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 102       | 43.4%   |
| Intel + Nvidia | 61        | 25.96%  |
| 1 x AMD        | 29        | 12.34%  |
| Intel + AMD    | 18        | 7.66%   |
| 1 x Nvidia     | 9         | 3.83%   |
| 2 x AMD        | 8         | 3.4%    |
| AMD + Nvidia   | 7         | 2.98%   |
| 2 x Intel      | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 189       | 79.75%  |
| Proprietary | 44        | 18.57%  |
| Unknown     | 4         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 142       | 59.17%  |
| 1.01-2.0   | 39        | 16.25%  |
| 0.01-0.5   | 23        | 9.58%   |
| 3.01-4.0   | 19        | 7.92%   |
| 0.51-1.0   | 13        | 5.42%   |
| 7.01-8.0   | 2         | 0.83%   |
| 5.01-6.0   | 2         | 0.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 20.75%  |
| Chimei Innolux          | 42        | 15.85%  |
| LG Display              | 35        | 13.21%  |
| BOE                     | 35        | 13.21%  |
| Samsung Electronics     | 26        | 9.81%   |
| Dell                    | 12        | 4.53%   |
| Sharp                   | 8         | 3.02%   |
| Chi Mei Optoelectronics | 6         | 2.26%   |
| Apple                   | 5         | 1.89%   |
| Lenovo                  | 4         | 1.51%   |
| Acer                    | 4         | 1.51%   |
| PANDA                   | 3         | 1.13%   |
| Hewlett-Packard         | 3         | 1.13%   |
| Philips                 | 2         | 0.75%   |
| Panasonic               | 2         | 0.75%   |
| InnoLux Display         | 2         | 0.75%   |
| Goldstar                | 2         | 0.75%   |
| AOC                     | 2         | 0.75%   |
| Xiaomi                  | 1         | 0.38%   |
| ViewSonic               | 1         | 0.38%   |
| Valve                   | 1         | 0.38%   |
| Unknown                 | 1         | 0.38%   |
| TRI                     | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| Sony                    | 1         | 0.38%   |
| MStar                   | 1         | 0.38%   |
| MSI                     | 1         | 0.38%   |
| LTM                     | 1         | 0.38%   |
| LG Philips              | 1         | 0.38%   |
| InfoVision              | 1         | 0.38%   |
| HJC                     | 1         | 0.38%   |
| EXP                     | 1         | 0.38%   |
| BenQ                    | 1         | 0.38%   |
| Armaggeddon             | 1         | 0.38%   |
| Ancor Communications    | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 4         | 1.51%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 4         | 1.51%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 1.13%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 3         | 1.13%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 1.13%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 1.13%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.75%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 2         | 0.75%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.75%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.75%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.75%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 2         | 0.75%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 2         | 0.75%   |
| Acer ET241Y ACR056C 1920x1080 527x296mm 23.8-inch                         | 2         | 0.75%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                         | 1         | 0.38%   |
| ViewSonic V3D231 Series VSC4C29 1920x1080 510x290mm 23.1-inch             | 1         | 0.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 1         | 0.38%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1600x900               | 1         | 0.38%   |
| TRI TRI2400 TRI2400 1920x1080 530x300mm 24.0-inch                         | 1         | 0.38%   |
| Toshiba TV TSB010B 1920x1080 706x398mm 31.9-inch                          | 1         | 0.38%   |
| Sony TV SNY0902 1920x1080                                                 | 1         | 0.38%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 1         | 0.38%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                   | 1         | 0.38%   |
| Sharp LCD SHP10C9 1920x540                                                | 1         | 0.38%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch                   | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 103       | 40.87%  |
| 1920x1080 (FHD)    | 95        | 37.7%   |
| 1280x800 (WXGA)    | 11        | 4.37%   |
| 1600x900 (HD+)     | 9         | 3.57%   |
| 3840x2160 (4K)     | 6         | 2.38%   |
| 2560x1440 (QHD)    | 4         | 1.59%   |
| 1920x1200 (WUXGA)  | 4         | 1.59%   |
| 2160x1440          | 3         | 1.19%   |
| 2560x1080          | 2         | 0.79%   |
| 1440x900 (WXGA+)   | 2         | 0.79%   |
| 1360x768           | 2         | 0.79%   |
| 1024x768 (XGA)     | 2         | 0.79%   |
| 1024x600           | 2         | 0.79%   |
| 800x1280           | 1         | 0.4%    |
| 2880x1800          | 1         | 0.4%    |
| 2560x1600          | 1         | 0.4%    |
| 2240x1400          | 1         | 0.4%    |
| 1920x540           | 1         | 0.4%    |
| 1680x1050 (WSXGA+) | 1         | 0.4%    |
| 1280x720 (HD)      | 1         | 0.4%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 83        | 31.32%  |
| 14      | 59        | 22.26%  |
| 13      | 49        | 18.49%  |
| 23      | 12        | 4.53%   |
| 24      | 10        | 3.77%   |
| 12      | 8         | 3.02%   |
| 17      | 7         | 2.64%   |
| 27      | 5         | 1.89%   |
| 11      | 5         | 1.89%   |
| 31      | 4         | 1.51%   |
| 21      | 3         | 1.13%   |
| 10      | 3         | 1.13%   |
| 72      | 2         | 0.75%   |
| 52      | 2         | 0.75%   |
| 7       | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 84      | 1         | 0.38%   |
| 65      | 1         | 0.38%   |
| 34      | 1         | 0.38%   |
| 32      | 1         | 0.38%   |
| 28      | 1         | 0.38%   |
| 25      | 1         | 0.38%   |
| 19      | 1         | 0.38%   |
| 18      | 1         | 0.38%   |
| 16      | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 65.66%  |
| 201-300     | 31        | 11.7%   |
| 501-600     | 26        | 9.81%   |
| 351-400     | 10        | 3.77%   |
| 601-700     | 6         | 2.26%   |
| 401-500     | 6         | 2.26%   |
| 1501-2000   | 3         | 1.13%   |
| 1001-1500   | 3         | 1.13%   |
| 701-800     | 2         | 0.75%   |
| Unknown     | 2         | 0.75%   |
| 101-200     | 1         | 0.38%   |
| 1-100       | 1         | 0.38%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 197       | 86.03%  |
| 16/10   | 19        | 8.3%    |
| 3/2     | 6         | 2.62%   |
| 21/9    | 2         | 0.87%   |
| 4/3     | 1         | 0.44%   |
| 32/9    | 1         | 0.44%   |
| 1.00    | 1         | 0.44%   |
| 0.67    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 97        | 36.6%   |
| 101-110        | 82        | 30.94%  |
| 201-250        | 22        | 8.3%    |
| 71-80          | 10        | 3.77%   |
| 61-70          | 8         | 3.02%   |
| 121-130        | 7         | 2.64%   |
| More than 1000 | 6         | 2.26%   |
| 351-500        | 6         | 2.26%   |
| 51-60          | 5         | 1.89%   |
| 301-350        | 5         | 1.89%   |
| 251-300        | 4         | 1.51%   |
| 41-50          | 3         | 1.13%   |
| 1-40           | 2         | 0.75%   |
| 151-200        | 2         | 0.75%   |
| 91-100         | 2         | 0.75%   |
| Unknown        | 2         | 0.75%   |
| 141-150        | 1         | 0.38%   |
| 111-120        | 1         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 101       | 38.85%  |
| 121-160       | 98        | 37.69%  |
| 51-100        | 39        | 15%     |
| 161-240       | 13        | 5%      |
| 1-50          | 6         | 2.31%   |
| Unknown       | 2         | 0.77%   |
| More than 240 | 1         | 0.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 188       | 79.32%  |
| 2     | 45        | 18.99%  |
| 0     | 4         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 126       | 32.81%  |
| Intel                           | 118       | 30.73%  |
| Qualcomm Atheros                | 64        | 16.67%  |
| Broadcom                        | 25        | 6.51%   |
| MediaTek                        | 7         | 1.82%   |
| TP-Link                         | 5         | 1.3%    |
| Ralink Technology               | 5         | 1.3%    |
| Ralink                          | 4         | 1.04%   |
| Broadcom Limited                | 4         | 1.04%   |
| Xiaomi                          | 3         | 0.78%   |
| Huawei Technologies             | 3         | 0.78%   |
| ASIX Electronics                | 3         | 0.78%   |
| Samsung Electronics             | 2         | 0.52%   |
| Nvidia                          | 2         | 0.52%   |
| Dell                            | 2         | 0.52%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| OPPO Electronics                | 1         | 0.26%   |
| Microchip Technology            | 1         | 0.26%   |
| Marvell Technology Group        | 1         | 0.26%   |
| JMicron Technology              | 1         | 0.26%   |
| InterBiometrics                 | 1         | 0.26%   |
| Hewlett-Packard                 | 1         | 0.26%   |
| DisplayLink                     | 1         | 0.26%   |
| D-Link                          | 1         | 0.26%   |
| Attansic Technology             | 1         | 0.26%   |
| ASUSTek Computer                | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80        | 17.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 5.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 2.62%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.62%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.75%   |
| Intel Wireless 7265                                               | 8         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 1.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.31%   |
| Realtek 802.11ac NIC                                              | 6         | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.09%   |
| Intel Wireless 7260                                               | 5         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.09%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 0.87%   |
| Intel Wireless 3160                                               | 4         | 0.87%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.87%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.87%   |
| TP-Link 802.11n NIC                                               | 3         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.66%   |
| Intel Wireless-AC 9260                                            | 3         | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 44.94%  |
| Qualcomm Atheros                | 53        | 21.46%  |
| Realtek Semiconductor           | 35        | 14.17%  |
| Broadcom                        | 19        | 7.69%   |
| MediaTek                        | 7         | 2.83%   |
| TP-Link                         | 5         | 2.02%   |
| Ralink Technology               | 5         | 2.02%   |
| Ralink                          | 4         | 1.62%   |
| Broadcom Limited                | 3         | 1.21%   |
| Dell                            | 2         | 0.81%   |
| Qualcomm Atheros Communications | 1         | 0.4%    |
| D-Link                          | 1         | 0.4%    |
| ASUSTek Computer                | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 5.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 4.82%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.82%   |
| Intel Wireless 8265 / 8275                                     | 9         | 3.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.21%   |
| Intel Wireless 7265                                            | 8         | 3.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 3.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.41%   |
| Realtek 802.11ac NIC                                           | 6         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 2.01%   |
| Intel Wireless 7260                                            | 5         | 2.01%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 1.61%   |
| Intel Wireless 3160                                            | 4         | 1.61%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.61%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.61%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.61%   |
| TP-Link 802.11n NIC                                            | 3         | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.2%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.2%    |
| Intel Wireless-AC 9260                                         | 3         | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.2%    |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.2%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.2%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 1.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.8%    |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                | 2         | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 112       | 54.9%   |
| Intel                    | 46        | 22.55%  |
| Qualcomm Atheros         | 16        | 7.84%   |
| Broadcom                 | 10        | 4.9%    |
| Xiaomi                   | 3         | 1.47%   |
| Huawei Technologies      | 3         | 1.47%   |
| ASIX Electronics         | 3         | 1.47%   |
| Samsung Electronics      | 2         | 0.98%   |
| Nvidia                   | 2         | 0.98%   |
| OPPO Electronics         | 1         | 0.49%   |
| Microchip Technology     | 1         | 0.49%   |
| Marvell Technology Group | 1         | 0.49%   |
| JMicron Technology       | 1         | 0.49%   |
| DisplayLink              | 1         | 0.49%   |
| Broadcom Limited         | 1         | 0.49%   |
| Attansic Technology      | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 80        | 38.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 11.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 5.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.9%    |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 2.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 2.42%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 2.42%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 2.42%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.93%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.45%   |
| Huawei JKM-LX1                                                                 | 3         | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 1.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.97%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.48%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.48%   |
| OPPO 8                                                                         | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.48%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.48%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.48%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.48%   |
| Intel Raptor Lake PCH CNVi WiFi                                                | 1         | 0.48%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.48%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 225       | 53.19%  |
| Ethernet | 196       | 46.34%  |
| Modem    | 2         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 78.51%  |
| Ethernet | 52        | 21.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 175       | 74.79%  |
| 1     | 52        | 22.22%  |
| 0     | 5         | 2.14%   |
| 3     | 2         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 158       | 65.29%  |
| Yes  | 84        | 34.71%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 81        | 42.19%  |
| Realtek Semiconductor           | 18        | 9.38%   |
| Qualcomm Atheros Communications | 15        | 7.81%   |
| IMC Networks                    | 14        | 7.29%   |
| Foxconn / Hon Hai               | 13        | 6.77%   |
| Broadcom                        | 11        | 5.73%   |
| Lite-On Technology              | 10        | 5.21%   |
| Apple                           | 7         | 3.65%   |
| Hewlett-Packard                 | 5         | 2.6%    |
| Dell                            | 5         | 2.6%    |
| Realtek                         | 3         | 1.56%   |
| Ralink                          | 2         | 1.04%   |
| MediaTek                        | 2         | 1.04%   |
| Cambridge Silicon Radio         | 2         | 1.04%   |
| Ralink Technology               | 1         | 0.52%   |
| ASUSTek Computer                | 1         | 0.52%   |
| Askey Computer                  | 1         | 0.52%   |
| Alps Electric                   | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 15.63%  |
| Intel AX200 Bluetooth                                                               | 12        | 6.25%   |
| Intel AX201 Bluetooth                                                               | 11        | 5.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 5.21%   |
| Realtek Bluetooth Radio                                                             | 8         | 4.17%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 3.65%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 3.13%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 2.6%    |
| IMC Networks Bluetooth Device                                                       | 5         | 2.6%    |
| Apple Bluetooth Host Controller                                                     | 5         | 2.6%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.08%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 2.08%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 2.08%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.08%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.56%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.56%   |
| Intel Bluetooth Device                                                              | 3         | 1.56%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.04%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.04%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.04%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.04%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.04%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.04%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.04%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.04%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 1.04%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.04%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.04%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.04%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.52%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.52%   |
| Ralink CSR BS8510                                                                   | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 187       | 67.27%  |
| AMD                    | 43        | 15.47%  |
| Nvidia                 | 35        | 12.59%  |
| C-Media Electronics    | 3         | 1.08%   |
| Samsung Electronics    | 2         | 0.72%   |
| Realtek Semiconductor  | 2         | 0.72%   |
| RODE Microphones       | 1         | 0.36%   |
| Plantronics            | 1         | 0.36%   |
| MVSILICON.INC.         | 1         | 0.36%   |
| MosArt Semiconductor   | 1         | 0.36%   |
| Generalplus Technology | 1         | 0.36%   |
| Cambridge Audio        | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 7.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 7.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 7.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 7.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 4.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.22%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.63%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.63%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.46%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 1.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.17%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.17%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.88%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia Audio device                                                                               | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 27.11%  |
| Kingston            | 40        | 24.1%   |
| SK hynix            | 30        | 18.07%  |
| Micron Technology   | 13        | 7.83%   |
| Nanya Technology    | 8         | 4.82%   |
| A-DATA Technology   | 5         | 3.01%   |
| Ramaxel Technology  | 4         | 2.41%   |
| Apacer              | 4         | 2.41%   |
| Unknown             | 3         | 1.81%   |
| Elpida              | 3         | 1.81%   |
| Crucial             | 3         | 1.81%   |
| Unknown (ABCD)      | 2         | 1.2%    |
| Unknown (08AE)      | 1         | 0.6%    |
| Transcend           | 1         | 0.6%    |
| Team                | 1         | 0.6%    |
| Silicon Power       | 1         | 0.6%    |
| Kingmax             | 1         | 0.6%    |
| Unknown             | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.74%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 1.74%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.16%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.16%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.16%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 1.16%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.16%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.16%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.16%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.16%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.16%   |
| Samsung RAM M471B2873EH1-CF8 1GB SODIMM 1067MT/s                 | 2         | 1.16%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.16%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.16%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.16%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 2         | 1.16%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 1.16%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.58%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.58%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1333MT/s               | 1         | 0.58%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.58%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.58%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.58%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.58%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.58%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s           | 1         | 0.58%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 57        | 45.6%   |
| DDR4   | 55        | 44%     |
| LPDDR4 | 3         | 2.4%    |
| LPDDR3 | 3         | 2.4%    |
| SDRAM  | 2         | 1.6%    |
| DDR5   | 2         | 1.6%    |
| DDR2   | 2         | 1.6%    |
| DDR    | 1         | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 95.97%  |
| Row Of Chips | 5         | 4.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 56        | 38.62%  |
| 8192  | 46        | 31.72%  |
| 2048  | 17        | 11.72%  |
| 16384 | 15        | 10.34%  |
| 32768 | 6         | 4.14%   |
| 1024  | 5         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 21.23%  |
| 2667    | 28        | 19.18%  |
| 3200    | 21        | 14.38%  |
| 1334    | 18        | 12.33%  |
| 2400    | 11        | 7.53%   |
| 1333    | 9         | 6.16%   |
| 2133    | 7         | 4.79%   |
| 1067    | 5         | 3.42%   |
| 4800    | 2         | 1.37%   |
| 4199    | 2         | 1.37%   |
| 3266    | 2         | 1.37%   |
| 800     | 2         | 1.37%   |
| 667     | 2         | 1.37%   |
| 8400    | 1         | 0.68%   |
| 5600    | 1         | 0.68%   |
| 3333    | 1         | 0.68%   |
| 2134    | 1         | 0.68%   |
| 1066    | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

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
| Chicony Electronics                    | 42        | 21%     |
| Microdia                               | 25        | 12.5%   |
| IMC Networks                           | 22        | 11%     |
| Sunplus Innovation Technology          | 15        | 7.5%    |
| Realtek Semiconductor                  | 15        | 7.5%    |
| Suyin                                  | 14        | 7%      |
| Bison Electronics                      | 10        | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 9         | 4.5%    |
| Quanta                                 | 7         | 3.5%    |
| Apple                                  | 6         | 3%      |
| Acer                                   | 5         | 2.5%    |
| Alcor Micro                            | 4         | 2%      |
| Syntek                                 | 3         | 1.5%    |
| Silicon Motion                         | 3         | 1.5%    |
| Luxvisions Innotech Limited            | 3         | 1.5%    |
| Logitech                               | 2         | 1%      |
| Lite-On Technology                     | 2         | 1%      |
| Generalplus Technology                 | 2         | 1%      |
| Z-Star Microelectronics                | 1         | 0.5%    |
| Sonix Technology                       | 1         | 0.5%    |
| Samsung Electronics                    | 1         | 0.5%    |
| Ricoh                                  | 1         | 0.5%    |
| Primax Electronics                     | 1         | 0.5%    |
| OmniVision Technologies                | 1         | 0.5%    |
| Lenovo                                 | 1         | 0.5%    |
| icSpring                               | 1         | 0.5%    |
| Fifine K420                            | 1         | 0.5%    |
| eMPIA Technology                       | 1         | 0.5%    |
| Cubeternet                             | 1         | 0.5%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                               | 10        | 5%      |
| Chicony USB2.0 VGA UVC WebCam                               | 8         | 4%      |
| Chicony Integrated Camera                                   | 5         | 2.5%    |
| Sunplus Integrated_Webcam_HD                                | 4         | 2%      |
| IMC Networks USB2.0 UVC HD Webcam                           | 4         | 2%      |
| IMC Networks USB2.0 HD UVC WebCam                           | 4         | 2%      |
| Chicony USB2.0 HD UVC WebCam                                | 4         | 2%      |
| Chicony HD WebCam                                           | 4         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 4         | 2%      |
| Sunplus Laptop Integrated Webcam HD                         | 3         | 1.5%    |
| Realtek Integrated_Webcam_HD                                | 3         | 1.5%    |
| Microdia Laptop_Integrated_Webcam_HD                        | 3         | 1.5%    |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.5%    |
| IMC Networks Integrated Camera                              | 3         | 1.5%    |
| Chicony Integrated Camera (1280x720@30)                     | 3         | 1.5%    |
| Chicony HP HD Webcam                                        | 3         | 1.5%    |
| Bison Lenovo Integrated Webcam                              | 3         | 1.5%    |
| Apple FaceTime HD Camera                                    | 3         | 1.5%    |
| Suyin Laptop_Integrated_Webcam_HD                           | 2         | 1%      |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 2         | 1%      |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1%      |
| Suyin 1.3M HD WebCam                                        | 2         | 1%      |
| Sunplus HP HD Webcam [Fixed]                                | 2         | 1%      |
| Realtek USB Camera                                          | 2         | 1%      |
| Realtek HD WebCam                                           | 2         | 1%      |
| Quanta HP TrueVision HD Camera                              | 2         | 1%      |
| Quanta HD Webcam                                            | 2         | 1%      |
| Microdia Webcam Vitade AF                                   | 2         | 1%      |
| Microdia USB 2.0 Camera                                     | 2         | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 2         | 1%      |
| IMC Networks ov9734_azurewave_camera                        | 2         | 1%      |
| Chicony HP Webcam [2 MP Macro]                              | 2         | 1%      |
| Bison SunplusIT Integrated Camera                           | 2         | 1%      |
| Bison Integrated Camera                                     | 2         | 1%      |
| Bison HD Webcam                                             | 2         | 1%      |
| Alcor Micro Asus Integrated Webcam                          | 2         | 1%      |
| Acer BisonCam,NB Pro                                        | 2         | 1%      |
| Z-Star Sirius USB2.0 Camera                                 | 1         | 0.5%    |
| Syntek USB Camera Device                                    | 1         | 0.5%    |
| Syntek Lenovo EasyCamera                                    | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 27.27%  |
| Synaptics                  | 7         | 21.21%  |
| Shenzhen Goodix Technology | 6         | 18.18%  |
| Upek                       | 3         | 9.09%   |
| Elan Microelectronics      | 3         | 9.09%   |
| AuthenTec                  | 3         | 9.09%   |
| LighTuning Technology      | 1         | 3.03%   |
| Focal-systems.Corp         | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 3         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 9.09%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 6.06%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 6.06%   |
| Elan ELAN:ARM-M4                                       | 2         | 6.06%   |
| Validity Sensors VFS491                                | 1         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 3.03%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.03%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.03%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                            | 1         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.03%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 3.03%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.03%   |
| AuthenTec Fingerprint Sensor                           | 1         | 3.03%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 3.03%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 76.92%  |
| O2 Micro    | 1         | 7.69%   |
| Lenovo      | 1         | 7.69%   |
| Alcor Micro | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 15.38%  |
| Broadcom 5880                                                                | 2         | 15.38%  |
| Broadcom 58200                                                               | 2         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.69%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 158       | 66.39%  |
| 1     | 64        | 26.89%  |
| 2     | 14        | 5.88%   |
| 4     | 1         | 0.42%   |
| 3     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 34.74%  |
| Graphics card            | 19        | 20%     |
| Net/wireless             | 11        | 11.58%  |
| Chipcard                 | 11        | 11.58%  |
| Multimedia controller    | 6         | 6.32%   |
| Bluetooth                | 4         | 4.21%   |
| Storage                  | 3         | 3.16%   |
| Net/ethernet             | 2         | 2.11%   |
| Camera                   | 2         | 2.11%   |
| Storage/ide              | 1         | 1.05%   |
| Sound                    | 1         | 1.05%   |
| Communication controller | 1         | 1.05%   |
| Card reader              | 1         | 1.05%   |

