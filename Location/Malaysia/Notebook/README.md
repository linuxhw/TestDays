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

Total: 378

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 4750                 | [9f4b6b970d](https://linux-hardware.org/?probe=9f4b6b970d) | Dec 26, 2023 |
| Dell          | Latitude E5510              | [379ebf6111](https://linux-hardware.org/?probe=379ebf6111) | Dec 23, 2023 |
| Sony          | VPCEG18FG                   | [e1b5fa6cac](https://linux-hardware.org/?probe=e1b5fa6cac) | Dec 15, 2023 |
| Sony          | VPCEG18FG                   | [3cf20aa9ea](https://linux-hardware.org/?probe=3cf20aa9ea) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [68e68f1683](https://linux-hardware.org/?probe=68e68f1683) | Dec 13, 2023 |
| Dell          | Latitude E5510              | [1e0f4dcd24](https://linux-hardware.org/?probe=1e0f4dcd24) | Dec 13, 2023 |
| Dell          | Latitude E5510              | [a980a75837](https://linux-hardware.org/?probe=a980a75837) | Dec 12, 2023 |
| Acer          | AOD257                      | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Acer          | AOD257                      | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [31de30cc0e](https://linux-hardware.org/?probe=31de30cc0e) | Dec 06, 2023 |
| Fujitsu       | LIFEBOOK UH554              | [cfdc07bd6d](https://linux-hardware.org/?probe=cfdc07bd6d) | Dec 05, 2023 |
| HP            | EliteBook 2740p             | [796859e80e](https://linux-hardware.org/?probe=796859e80e) | Dec 05, 2023 |
| Lenovo        | G480                        | [e82d31d252](https://linux-hardware.org/?probe=e82d31d252) | Dec 05, 2023 |
| HP            | EliteBook 2740p             | [d6e3212623](https://linux-hardware.org/?probe=d6e3212623) | Dec 02, 2023 |
| Valve         | Jupiter                     | [e5546145aa](https://linux-hardware.org/?probe=e5546145aa) | Dec 02, 2023 |
| ILLEGEAR      | RAVEN SE                    | [3248206a01](https://linux-hardware.org/?probe=3248206a01) | Nov 30, 2023 |
| ILLEGEAR      | RAVEN SE                    | [f3b42d14f6](https://linux-hardware.org/?probe=f3b42d14f6) | Nov 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [11d4048dc9](https://linux-hardware.org/?probe=11d4048dc9) | Nov 28, 2023 |
| Samsung       | RV413/RV513                 | [42fb4ae911](https://linux-hardware.org/?probe=42fb4ae911) | Nov 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0390B    | [9b37545fa9](https://linux-hardware.org/?probe=9b37545fa9) | Nov 28, 2023 |
| Dell          | Latitude E5510              | [5f68594a94](https://linux-hardware.org/?probe=5f68594a94) | Nov 28, 2023 |
| IBM           | ThinkPad T42 2374GB1        | [455a2c937b](https://linux-hardware.org/?probe=455a2c937b) | Nov 19, 2023 |
| Lenovo        | ThinkPad Edge 03282XA       | [c46ed26c69](https://linux-hardware.org/?probe=c46ed26c69) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [98f59c07de](https://linux-hardware.org/?probe=98f59c07de) | Nov 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [386450b69c](https://linux-hardware.org/?probe=386450b69c) | Nov 15, 2023 |
| Dell          | Latitude E7250              | [265c13751a](https://linux-hardware.org/?probe=265c13751a) | Nov 10, 2023 |
| Toshiba       | Satellite L745              | [4dbd78f68d](https://linux-hardware.org/?probe=4dbd78f68d) | Nov 09, 2023 |
| HP            | Pavilion Notebook           | [8cf5696a9e](https://linux-hardware.org/?probe=8cf5696a9e) | Nov 07, 2023 |
| Toshiba       | Satellite L745              | [c126c9e041](https://linux-hardware.org/?probe=c126c9e041) | Oct 27, 2023 |
| HP            | Compaq Presario CQ40        | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| Acer          | Aspire VN7-592G             | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| HP            | Compaq Presario CQ40        | [f6373646f3](https://linux-hardware.org/?probe=f6373646f3) | Oct 14, 2023 |
| HP            | ElitePad 1000 G2            | [fcfe482832](https://linux-hardware.org/?probe=fcfe482832) | Oct 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T52R     | [39983ac5b1](https://linux-hardware.org/?probe=39983ac5b1) | Oct 04, 2023 |
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
| Ubuntu 20.04        | 30        | 10.71%  |
| Ubuntu 22.04        | 16        | 5.71%   |
| Ubuntu 18.04        | 13        | 4.64%   |
| Pop!_OS 22.04       | 8         | 2.86%   |
| Pop!_OS 20.10       | 8         | 2.86%   |
| KDE neon 20.04      | 7         | 2.5%    |
| ArcoLinux Rolling   | 7         | 2.5%    |
| Pop!_OS 21.04       | 6         | 2.14%   |
| Arch Rolling        | 6         | 2.14%   |
| Zorin 16            | 5         | 1.79%   |
| OpenMandriva 4.2    | 5         | 1.79%   |
| OpenMandriva 23.01  | 5         | 1.79%   |
| Xero Rolling        | 4         | 1.43%   |
| Ubuntu 23.04        | 4         | 1.43%   |
| Ubuntu 16.04        | 4         | 1.43%   |
| OpenMandriva 4.50   | 4         | 1.43%   |
| OpenMandriva 4.3    | 4         | 1.43%   |
| OpenMandriva 23.08  | 4         | 1.43%   |
| Linux Mint 21.2     | 4         | 1.43%   |
| Linux Mint 21.1     | 4         | 1.43%   |
| Fedora 38           | 4         | 1.43%   |
| Fedora 33           | 4         | 1.43%   |
| EndeavourOS Rolling | 4         | 1.43%   |
| Debian 12           | 4         | 1.43%   |
| Xubuntu 22.04       | 3         | 1.07%   |
| Ubuntu 21.04        | 3         | 1.07%   |
| Ubuntu 19.04        | 3         | 1.07%   |
| Nobara 37           | 3         | 1.07%   |
| Manjaro             | 3         | 1.07%   |
| Linux Mint 20.2     | 3         | 1.07%   |
| Linux Mint 19.3     | 3         | 1.07%   |
| Fedora 37           | 3         | 1.07%   |
| Fedora 35           | 3         | 1.07%   |
| Fedora 34           | 3         | 1.07%   |
| Debian 11           | 3         | 1.07%   |
| Arch                | 3         | 1.07%   |
| Zorin 15            | 2         | 0.71%   |
| Ubuntu Unity 16.04  | 2         | 0.71%   |
| Ubuntu 20.10        | 2         | 0.71%   |
| Ubuntu 19.10        | 2         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 76        | 28.36%  |
| OpenMandriva  | 24        | 8.96%   |
| Pop!_OS       | 23        | 8.58%   |
| Fedora        | 18        | 6.72%   |
| Linux Mint    | 16        | 5.97%   |
| KDE neon      | 9         | 3.36%   |
| Arch          | 9         | 3.36%   |
| Zorin         | 8         | 2.99%   |
| Manjaro       | 8         | 2.99%   |
| Debian        | 8         | 2.99%   |
| ArcoLinux     | 7         | 2.61%   |
| Endless       | 5         | 1.87%   |
| Xubuntu       | 4         | 1.49%   |
| Xero          | 4         | 1.49%   |
| Lubuntu       | 4         | 1.49%   |
| Kubuntu       | 4         | 1.49%   |
| Kali          | 4         | 1.49%   |
| EndeavourOS   | 4         | 1.49%   |
| Elementary    | 4         | 1.49%   |
| SteamOS       | 3         | 1.12%   |
| Nobara        | 3         | 1.12%   |
| CentOS        | 3         | 1.12%   |
| Ultramarine   | 2         | 0.75%   |
| Ubuntu Unity  | 2         | 0.75%   |
| Ubuntu Budgie | 2         | 0.75%   |
| LMDE          | 2         | 0.75%   |
| Archcraft     | 2         | 0.75%   |
| Ubuntu MATE   | 1         | 0.37%   |
| ROSA          | 1         | 0.37%   |
| Rocky Linux   | 1         | 0.37%   |
| Reborn OS     | 1         | 0.37%   |
| Peppermint    | 1         | 0.37%   |
| MX            | 1         | 0.37%   |
| Gentoo        | 1         | 0.37%   |
| BunsenLabs    | 1         | 0.37%   |
| BuildRoot     | 1         | 0.37%   |
| blendOS       | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.1-desktop-1omv2290   | 5         | 1.66%   |
| 5.11.0-7620-generic      | 5         | 1.66%   |
| 6.3.9-arch1-1            | 4         | 1.33%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.33%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.33%   |
| 5.0.0-37-generic         | 4         | 1.33%   |
| 6.4.11-desktop-1omv2390  | 3         | 1%      |
| 6.2.6-76060206-generic   | 3         | 1%      |
| 5.8.0-7642-generic       | 3         | 1%      |
| 5.4.0-58-generic         | 3         | 1%      |
| 5.4.0-54-generic         | 3         | 1%      |
| 5.4.0-42-generic         | 3         | 1%      |
| 5.19.0-46-generic        | 3         | 1%      |
| 5.15.0-91-generic        | 3         | 1%      |
| 5.15.0-56-generic        | 3         | 1%      |
| 5.15.0-52-generic        | 3         | 1%      |
| 5.12.4-desktop-1omv4050  | 3         | 1%      |
| 5.11.0-46-generic        | 3         | 1%      |
| 5.0.0-23-generic         | 3         | 1%      |
| 4.15.0-45-generic        | 3         | 1%      |
| 6.6.2-desktop-1omv2390   | 2         | 0.66%   |
| 6.5.5-arch1-1            | 2         | 0.66%   |
| 6.2.0-33-generic         | 2         | 0.66%   |
| 6.1.0-13-amd64           | 2         | 0.66%   |
| 5.8.0-7630-generic       | 2         | 0.66%   |
| 5.8.0-45-generic         | 2         | 0.66%   |
| 5.4.0-89-generic         | 2         | 0.66%   |
| 5.4.0-64-generic         | 2         | 0.66%   |
| 5.4.0-52-generic         | 2         | 0.66%   |
| 5.3.0-51-generic         | 2         | 0.66%   |
| 5.19.0-76051900-generic  | 2         | 0.66%   |
| 5.19.0-38-generic        | 2         | 0.66%   |
| 5.17.5-76051705-generic  | 2         | 0.66%   |
| 5.17.1-051701-generic    | 2         | 0.66%   |
| 5.15.0-89-generic        | 2         | 0.66%   |
| 5.15.0-58-generic        | 2         | 0.66%   |
| 5.15.0-46-generic        | 2         | 0.66%   |
| 5.15.0-40-generic        | 2         | 0.66%   |
| 5.15.0-25-generic        | 2         | 0.66%   |
| 5.13.0-7614-generic      | 2         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 31        | 10.69%  |
| 5.15.0  | 27        | 9.31%   |
| 5.11.0  | 17        | 5.86%   |
| 5.8.0   | 15        | 5.17%   |
| 5.13.0  | 12        | 4.14%   |
| 4.15.0  | 12        | 4.14%   |
| 5.0.0   | 10        | 3.45%   |
| 5.3.0   | 9         | 3.1%    |
| 5.19.0  | 9         | 3.1%    |
| 6.2.0   | 6         | 2.07%   |
| 6.1.1   | 6         | 2.07%   |
| 6.3.9   | 5         | 1.72%   |
| 6.1.0   | 5         | 1.72%   |
| 5.10.0  | 5         | 1.72%   |
| 6.4.11  | 4         | 1.38%   |
| 6.2.6   | 4         | 1.38%   |
| 5.16.7  | 4         | 1.38%   |
| 5.10.14 | 4         | 1.38%   |
| 4.18.0  | 4         | 1.38%   |
| 5.17.1  | 3         | 1.03%   |
| 5.16.15 | 3         | 1.03%   |
| 5.12.4  | 3         | 1.03%   |
| 6.6.2   | 2         | 0.69%   |
| 6.5.5   | 2         | 0.69%   |
| 6.4.8   | 2         | 0.69%   |
| 6.2.9   | 2         | 0.69%   |
| 6.2.8   | 2         | 0.69%   |
| 5.9.0   | 2         | 0.69%   |
| 5.18.0  | 2         | 0.69%   |
| 5.17.5  | 2         | 0.69%   |
| 5.12.9  | 2         | 0.69%   |
| 5.10.79 | 2         | 0.69%   |
| 5.10.42 | 2         | 0.69%   |
| 5.10.13 | 2         | 0.69%   |
| 4.4.0   | 2         | 0.69%   |
| 3.10.0  | 2         | 0.69%   |
| 6.6.4   | 1         | 0.34%   |
| 6.6.3   | 1         | 0.34%   |
| 6.5.6   | 1         | 0.34%   |
| 6.5.12  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 31        | 10.88%  |
| 5.15    | 30        | 10.53%  |
| 5.8     | 22        | 7.72%   |
| 5.11    | 20        | 7.02%   |
| 5.10    | 18        | 6.32%   |
| 6.2     | 15        | 5.26%   |
| 6.1     | 15        | 5.26%   |
| 5.13    | 13        | 4.56%   |
| 6.4     | 12        | 4.21%   |
| 5.19    | 12        | 4.21%   |
| 4.15    | 12        | 4.21%   |
| 5.0     | 10        | 3.51%   |
| 5.3     | 9         | 3.16%   |
| 6.3     | 8         | 2.81%   |
| 5.16    | 7         | 2.46%   |
| 5.12    | 7         | 2.46%   |
| 5.17    | 6         | 2.11%   |
| 6.5     | 5         | 1.75%   |
| 5.18    | 5         | 1.75%   |
| 5.14    | 5         | 1.75%   |
| 6.6     | 4         | 1.4%    |
| 4.18    | 4         | 1.4%    |
| 6.0     | 3         | 1.05%   |
| 5.9     | 3         | 1.05%   |
| 5.7     | 2         | 0.7%    |
| 4.4     | 2         | 0.7%    |
| 3.10    | 2         | 0.7%    |
| 5.6     | 1         | 0.35%   |
| 4.10    | 1         | 0.35%   |
| 4.1     | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 251       | 98.43%  |
| i686   | 4         | 1.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 122       | 45.19%  |
| KDE5          | 55        | 20.37%  |
| Unknown       | 23        | 8.52%   |
| XFCE          | 21        | 7.78%   |
| X-Cinnamon    | 15        | 5.56%   |
| KDE           | 8         | 2.96%   |
| MATE          | 5         | 1.85%   |
| Pantheon      | 4         | 1.48%   |
| LXQt          | 3         | 1.11%   |
| Budgie        | 3         | 1.11%   |
| Unity         | 2         | 0.74%   |
| openbox       | 2         | 0.74%   |
| i3            | 2         | 0.74%   |
| Peppermint    | 1         | 0.37%   |
| LXDE          | 1         | 0.37%   |
| Hyprland      | 1         | 0.37%   |
| GNOME Classic | 1         | 0.37%   |
| bspwm         | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 198       | 74.16%  |
| Wayland | 57        | 21.35%  |
| Unknown | 9         | 3.37%   |
| Tty     | 3         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 124       | 46.97%  |
| SDDM    | 52        | 19.7%   |
| GDM3    | 37        | 14.02%  |
| GDM     | 27        | 10.23%  |
| LightDM | 22        | 8.33%   |
| TDM     | 2         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 208       | 80.31%  |
| Unknown | 17        | 6.56%   |
| en_GB   | 13        | 5.02%   |
| en_SG   | 10        | 3.86%   |
| C       | 4         | 1.54%   |
| ms_MY   | 2         | 0.77%   |
| zh_TW   | 1         | 0.39%   |
| ja_JP   | 1         | 0.39%   |
| id_ID   | 1         | 0.39%   |
| en_MY   | 1         | 0.39%   |
| de_DE   | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 129       | 50.19%  |
| BIOS | 128       | 49.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 192       | 72.45%  |
| Btrfs   | 29        | 10.94%  |
| Overlay | 22        | 8.3%    |
| Tmpfs   | 6         | 2.26%   |
| Zfs     | 5         | 1.89%   |
| Xfs     | 5         | 1.89%   |
| Unknown | 5         | 1.89%   |
| Ext2    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 133       | 50.76%  |
| GPT     | 94        | 35.88%  |
| MBR     | 35        | 13.36%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 222       | 85.71%  |
| Yes       | 37        | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 182       | 69.73%  |
| Yes       | 79        | 30.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 49        | 19.22%  |
| Hewlett-Packard     | 48        | 18.82%  |
| ASUSTek Computer    | 39        | 15.29%  |
| Lenovo              | 37        | 14.51%  |
| Acer                | 26        | 10.2%   |
| MSI                 | 8         | 3.14%   |
| Apple               | 7         | 2.75%   |
| Sony                | 5         | 1.96%   |
| Fujitsu             | 5         | 1.96%   |
| Samsung Electronics | 3         | 1.18%   |
| ILLEGEAR            | 3         | 1.18%   |
| HUAWEI              | 3         | 1.18%   |
| Unknown             | 3         | 1.18%   |
| Valve               | 2         | 0.78%   |
| Toshiba             | 2         | 0.78%   |
| NEC Computers       | 2         | 0.78%   |
| Chuwi               | 2         | 0.78%   |
| Timi                | 1         | 0.39%   |
| System76            | 1         | 0.39%   |
| SNS Network (M)     | 1         | 0.39%   |
| Infinix             | 1         | 0.39%   |
| IBM                 | 1         | 0.39%   |
| HONOR               | 1         | 0.39%   |
| GPD                 | 1         | 0.39%   |
| Gigabyte Technology | 1         | 0.39%   |
| BUSH                | 1         | 0.39%   |
| AZW                 | 1         | 0.39%   |
| Alienware           | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| HP Notebook                       | 5         | 1.96%   |
| HP Compaq Presario CQ40           | 3         | 1.18%   |
| Unknown                           | 3         | 1.18%   |
| Valve Jupiter                     | 2         | 0.78%   |
| MSI Modern 14 B5M                 | 2         | 0.78%   |
| ILLEGEAR RAVEN SE                 | 2         | 0.78%   |
| HP Pavilion dv6                   | 2         | 0.78%   |
| HP Laptop 15-bs0xx                | 2         | 0.78%   |
| HP ENVY 4                         | 2         | 0.78%   |
| HP ElitePad 1000 G2               | 2         | 0.78%   |
| HP EliteBook 8470p                | 2         | 0.78%   |
| HP EliteBook 840 G2               | 2         | 0.78%   |
| Dell XPS 15 7590                  | 2         | 0.78%   |
| Dell Latitude E6520               | 2         | 0.78%   |
| Dell Latitude E6440               | 2         | 0.78%   |
| Dell Latitude 3410                | 2         | 0.78%   |
| ASUS K45VD                        | 2         | 0.78%   |
| ASUS K43SD                        | 2         | 0.78%   |
| Apple MacBookPro8,1               | 2         | 0.78%   |
| Toshiba Satellite L745            | 1         | 0.39%   |
| Toshiba dynabook Satellite B552/H | 1         | 0.39%   |
| Timi RedmiBook 14 II              | 1         | 0.39%   |
| System76 Galago Pro               | 1         | 0.39%   |
| Sony VPCSB26FG                    | 1         | 0.39%   |
| Sony VPCEG18FG                    | 1         | 0.39%   |
| Sony VPCEG16EG                    | 1         | 0.39%   |
| Sony VPCEA42EG                    | 1         | 0.39%   |
| Sony VGN-Z27GN_X                  | 1         | 0.39%   |
| SNS Network (M) JOI Book 150      | 1         | 0.39%   |
| Samsung RV413/RV513               | 1         | 0.39%   |
| Samsung 730U3E/740U3E             | 1         | 0.39%   |
| Samsung 535U3C                    | 1         | 0.39%   |
| NEC Computers PC-VK27MXZCG        | 1         | 0.39%   |
| NEC Computers PC-VK27MCZCK        | 1         | 0.39%   |
| MSI Stealth 14Studio A13VE        | 1         | 0.39%   |
| MSI Prestige 15 A10SC             | 1         | 0.39%   |
| MSI Modern 14 C11M                | 1         | 0.39%   |
| MSI GT70 2OC/2OD                  | 1         | 0.39%   |
| MSI GP70 2PE                      | 1         | 0.39%   |
| MSI GL62M 7RDX                    | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 24        | 9.41%   |
| Lenovo ThinkPad     | 22        | 8.63%   |
| Acer Aspire         | 16        | 6.27%   |
| Dell Inspiron       | 14        | 5.49%   |
| HP Pavilion         | 9         | 3.53%   |
| HP EliteBook        | 9         | 3.53%   |
| HP Laptop           | 7         | 2.75%   |
| ASUS VivoBook       | 7         | 2.75%   |
| HP Notebook         | 5         | 1.96%   |
| HP Compaq           | 5         | 1.96%   |
| Dell XPS            | 5         | 1.96%   |
| Lenovo IdeaPad      | 4         | 1.57%   |
| Fujitsu LIFEBOOK    | 4         | 1.57%   |
| MSI Modern          | 3         | 1.18%   |
| HP ENVY             | 3         | 1.18%   |
| Dell Precision      | 3         | 1.18%   |
| ASUS ROG            | 3         | 1.18%   |
| Apple MacBookPro8   | 3         | 1.18%   |
| Acer Nitro          | 3         | 1.18%   |
| Unknown             | 3         | 1.18%   |
| Valve Jupiter       | 2         | 0.78%   |
| ILLEGEAR RAVEN      | 2         | 0.78%   |
| HP ProBook          | 2         | 0.78%   |
| HP ElitePad         | 2         | 0.78%   |
| ASUS K45VD          | 2         | 0.78%   |
| ASUS K43SD          | 2         | 0.78%   |
| ASUS ASUS           | 2         | 0.78%   |
| Toshiba Satellite   | 1         | 0.39%   |
| Toshiba dynabook    | 1         | 0.39%   |
| Timi RedmiBook      | 1         | 0.39%   |
| System76 Galago     | 1         | 0.39%   |
| Sony VPCSB26FG      | 1         | 0.39%   |
| Sony VPCEG18FG      | 1         | 0.39%   |
| Sony VPCEG16EG      | 1         | 0.39%   |
| Sony VPCEA42EG      | 1         | 0.39%   |
| Sony VGN-Z27GN      | 1         | 0.39%   |
| SNS Network (M) JOI | 1         | 0.39%   |
| Samsung RV413       | 1         | 0.39%   |
| Samsung 730U3E      | 1         | 0.39%   |
| Samsung 535U3C      | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 33        | 12.94%  |
| 2021 | 23        | 9.02%   |
| 2013 | 23        | 9.02%   |
| 2020 | 22        | 8.63%   |
| 2019 | 21        | 8.24%   |
| 2012 | 18        | 7.06%   |
| 2015 | 17        | 6.67%   |
| 2010 | 17        | 6.67%   |
| 2018 | 16        | 6.27%   |
| 2014 | 15        | 5.88%   |
| 2017 | 14        | 5.49%   |
| 2016 | 9         | 3.53%   |
| 2008 | 9         | 3.53%   |
| 2009 | 7         | 2.75%   |
| 2022 | 5         | 1.96%   |
| 2023 | 3         | 1.18%   |
| 2007 | 2         | 0.78%   |
| 2004 | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 255       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 232       | 90.63%  |
| Enabled  | 24        | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 253       | 99.22%  |
| Yes  | 2         | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 70        | 27.34%  |
| 3.01-4.0    | 64        | 25%     |
| 8.01-16.0   | 50        | 19.53%  |
| 16.01-24.0  | 36        | 14.06%  |
| 32.01-64.0  | 10        | 3.91%   |
| 1.01-2.0    | 8         | 3.13%   |
| 2.01-3.0    | 7         | 2.73%   |
| 24.01-32.0  | 5         | 1.95%   |
| 64.01-256.0 | 3         | 1.17%   |
| 0.51-1.0    | 3         | 1.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 94        | 33.45%  |
| 2.01-3.0  | 86        | 30.6%   |
| 3.01-4.0  | 40        | 14.23%  |
| 4.01-8.0  | 32        | 11.39%  |
| 0.51-1.0  | 21        | 7.47%   |
| 8.01-16.0 | 8         | 2.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 179       | 68.58%  |
| 2      | 70        | 26.82%  |
| 3      | 10        | 3.83%   |
| 4      | 2         | 0.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 170       | 66.67%  |
| Yes       | 85        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 83.92%  |
| No        | 41        | 16.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 96.47%  |
| No        | 9         | 3.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 205       | 79.77%  |
| No        | 52        | 20.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Malaysia | 255       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 99        | 36%     |
| Petaling Jaya          | 32        | 11.64%  |
| Johor Bahru            | 14        | 5.09%   |
| Shah Alam              | 12        | 4.36%   |
| Ipoh                   | 10        | 3.64%   |
| Puchong Batu Dua Belas | 9         | 3.27%   |
| Subang Jaya            | 8         | 2.91%   |
| Sungai Buloh           | 6         | 2.18%   |
| Seremban               | 6         | 2.18%   |
| Kota Kinabalu          | 6         | 2.18%   |
| Kajang                 | 6         | 2.18%   |
| Sungai Petani          | 5         | 1.82%   |
| Skudai                 | 4         | 1.45%   |
| Kulai                  | 4         | 1.45%   |
| Kota Bharu             | 4         | 1.45%   |
| Klang                  | 4         | 1.45%   |
| Marabu                 | 3         | 1.09%   |
| Kuching                | 3         | 1.09%   |
| George Town            | 3         | 1.09%   |
| Cyberjaya              | 3         | 1.09%   |
| Tawau                  | 2         | 0.73%   |
| Seri Kembangan         | 2         | 0.73%   |
| Nibong Tebal           | 2         | 0.73%   |
| Malacca                | 2         | 0.73%   |
| Kulim                  | 2         | 0.73%   |
| Cheras                 | 2         | 0.73%   |
| Batu Pahat             | 2         | 0.73%   |
| Tuaran                 | 1         | 0.36%   |
| Tangkak                | 1         | 0.36%   |
| Serdang                | 1         | 0.36%   |
| Sepang                 | 1         | 0.36%   |
| Semenyih               | 1         | 0.36%   |
| Rawang                 | 1         | 0.36%   |
| Putrajaya              | 1         | 0.36%   |
| Pasir Gudang           | 1         | 0.36%   |
| Long Seridan           | 1         | 0.36%   |
| Kuala Terengganu       | 1         | 0.36%   |
| Kuala Kangsar          | 1         | 0.36%   |
| Kota Tinggi            | 1         | 0.36%   |
| Kamunting              | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 44        | 51     | 13.1%   |
| WDC                         | 35        | 42     | 10.42%  |
| Samsung Electronics         | 33        | 42     | 9.82%   |
| Toshiba                     | 27        | 34     | 8.04%   |
| SanDisk                     | 24        | 31     | 7.14%   |
| Kingston                    | 22        | 25     | 6.55%   |
| Unknown                     | 18        | 25     | 5.36%   |
| HGST                        | 16        | 23     | 4.76%   |
| Micron Technology           | 9         | 10     | 2.68%   |
| SK hynix                    | 8         | 8      | 2.38%   |
| A-DATA Technology           | 8         | 8      | 2.38%   |
| Hitachi                     | 7         | 13     | 2.08%   |
| Intel                       | 6         | 12     | 1.79%   |
| Apacer                      | 6         | 7      | 1.79%   |
| KIOXIA                      | 5         | 6      | 1.49%   |
| Transcend                   | 4         | 5      | 1.19%   |
| SPCC                        | 4         | 5      | 1.19%   |
| Kingston Technology Company | 4         | 4      | 1.19%   |
| China                       | 4         | 4      | 1.19%   |
| TO Exter                    | 3         | 3      | 0.89%   |
| Team                        | 3         | 3      | 0.89%   |
| Phison                      | 3         | 5      | 0.89%   |
| Patriot                     | 3         | 4      | 0.89%   |
| Kingchuxing                 | 3         | 4      | 0.89%   |
| Apple                       | 3         | 4      | 0.89%   |
| Silicon Motion              | 2         | 2      | 0.6%    |
| Phison Electronics          | 2         | 2      | 0.6%    |
| Netac                       | 2         | 2      | 0.6%    |
| JMicron Technology          | 2         | 2      | 0.6%    |
| Hewlett-Packard             | 2         | 2      | 0.6%    |
| Fujitsu                     | 2         | 2      | 0.6%    |
| Crucial                     | 2         | 2      | 0.6%    |
| ADATA Technology            | 2         | 2      | 0.6%    |
| Unknown                     | 2         | 2      | 0.6%    |
| Zheino                      | 1         | 1      | 0.3%    |
| winstar                     | 1         | 1      | 0.3%    |
| Western Digital             | 1         | 1      | 0.3%    |
| Verbatim                    | 1         | 1      | 0.3%    |
| USB3.0                      | 1         | 1      | 0.3%    |
| PNY                         | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB                          | 6         | 1.73%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 1.45%   |
| Unknown MMC Card  64GB                              | 4         | 1.16%   |
| Unknown MMC Card  32GB                              | 4         | 1.16%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 1.16%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 3         | 0.87%   |
| Unknown MMC Card  128GB                             | 3         | 0.87%   |
| TO Exter nal USB 3.0 480GB                          | 3         | 0.87%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.87%   |
| Seagate ST9320325AS 320GB                           | 3         | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.87%   |
| SanDisk SSD PLUS 240GB                              | 3         | 0.87%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 0.87%   |
| HGST HTS725050A7E630 500GB                          | 3         | 0.87%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.87%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 2         | 0.58%   |
| WDC WD5000BPVT-24HXZT3 500GB                        | 2         | 0.58%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 2         | 0.58%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 2         | 0.58%   |
| WDC PC SN730 NVMe 1024GB                            | 2         | 0.58%   |
| Toshiba MK5065GSXF 500GB                            | 2         | 0.58%   |
| Seagate ST9750420AS 752GB                           | 2         | 0.58%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.58%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2         | 0.58%   |
| Seagate ST320LT020-9YG142 320GB                     | 2         | 0.58%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB     | 2         | 0.58%   |
| Sandisk PC SN530 NVMe WDC 256GB                     | 2         | 0.58%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.58%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.58%   |
| Samsung NVMe SSD Drive 512GB                        | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 0.58%   |
| Netac SSD 256GB                                     | 2         | 0.58%   |
| Micron 2400_MTFDKBA512QFM 512GB                     | 2         | 0.58%   |
| Micron 1100 SATA 512GB SSD                          | 2         | 0.58%   |
| KIOXIA NVMe SSD Drive 256GB                         | 2         | 0.58%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB             | 2         | 0.58%   |
| Kingston SH103S3120G 120GB SSD                      | 2         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 50     | 35.83%  |
| WDC                 | 24        | 31     | 20%     |
| Toshiba             | 22        | 27     | 18.33%  |
| HGST                | 16        | 23     | 13.33%  |
| Hitachi             | 7         | 13     | 5.83%   |
| TO Exter            | 3         | 3      | 2.5%    |
| Fujitsu             | 2         | 2      | 1.67%   |
| USB3.0              | 1         | 1      | 0.83%   |
| Unknown             | 1         | 1      | 0.83%   |
| Samsung Electronics | 1         | 3      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 18        | 19     | 16.67%  |
| Samsung Electronics | 16        | 22     | 14.81%  |
| SanDisk             | 10        | 10     | 9.26%   |
| Apacer              | 6         | 7      | 5.56%   |
| A-DATA Technology   | 6         | 6      | 5.56%   |
| Transcend           | 4         | 4      | 3.7%    |
| Micron Technology   | 4         | 5      | 3.7%    |
| China               | 4         | 4      | 3.7%    |
| WDC                 | 3         | 3      | 2.78%   |
| Team                | 3         | 3      | 2.78%   |
| SPCC                | 3         | 4      | 2.78%   |
| Patriot             | 3         | 4      | 2.78%   |
| Apple               | 3         | 4      | 2.78%   |
| Toshiba             | 2         | 3      | 1.85%   |
| Netac               | 2         | 2      | 1.85%   |
| Kingchuxing         | 2         | 2      | 1.85%   |
| JMicron Technology  | 2         | 2      | 1.85%   |
| Intel               | 2         | 2      | 1.85%   |
| Crucial             | 2         | 2      | 1.85%   |
| Zheino              | 1         | 1      | 0.93%   |
| Verbatim            | 1         | 1      | 0.93%   |
| SK hynix            | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Plextor             | 1         | 1      | 0.93%   |
| Pioneer             | 1         | 1      | 0.93%   |
| LS                  | 1         | 1      | 0.93%   |
| KimMiDi             | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |
| Colorful            | 1         | 1      | 0.93%   |
| ASMT                | 1         | 1      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 114       | 154    | 36.66%  |
| SSD     | 99        | 121    | 31.83%  |
| NVMe    | 74        | 106    | 23.79%  |
| MMC     | 17        | 25     | 5.47%   |
| Unknown | 7         | 8      | 2.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 193       | 270    | 65.2%   |
| NVMe | 74        | 106    | 25%     |
| MMC  | 17        | 25     | 5.74%   |
| SAS  | 12        | 13     | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 144       | 187    | 68.25%  |
| 0.51-1.0   | 61        | 82     | 28.91%  |
| 1.01-2.0   | 6         | 6      | 2.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 78        | 28.47%  |
| 101-250        | 74        | 27.01%  |
| 501-1000       | 37        | 13.5%   |
| 1-20           | 28        | 10.22%  |
| 51-100         | 21        | 7.66%   |
| 21-50          | 14        | 5.11%   |
| 1001-2000      | 11        | 4.01%   |
| Unknown        | 6         | 2.19%   |
| 2001-3000      | 3         | 1.09%   |
| More than 3000 | 2         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 124       | 44.13%  |
| 21-50     | 54        | 19.22%  |
| 101-250   | 33        | 11.74%  |
| 51-100    | 30        | 10.68%  |
| 251-500   | 19        | 6.76%   |
| 501-1000  | 9         | 3.2%    |
| Unknown   | 6         | 2.14%   |
| 1001-2000 | 4         | 1.42%   |
| 2001-3000 | 1         | 0.36%   |
| 0         | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                      | 2         | 2      | 8%      |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 4%      |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 4%      |
| WDC WD5000BPVT-24HXZT3 500GB                   | 1         | 1      | 4%      |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 4%      |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 4%      |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 4%      |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 4%      |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 4%      |
| Toshiba MK1059GSMP 1TB                         | 1         | 1      | 4%      |
| SPCC Solid State Disk 256GB                    | 1         | 1      | 4%      |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 4%      |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 4%      |
| Samsung Electronics SSD PM830 2.5 7mm 512GB    | 1         | 1      | 4%      |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 2      | 4%      |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 4%      |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 4%      |
| Hitachi HTS547575A9E384 752GB                  | 1         | 3      | 4%      |
| Hitachi HTS545050B9A300 500GB                  | 1         | 2      | 4%      |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 4%      |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 4%      |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 4%      |
| Unknown                                        | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 6         | 6      | 24%     |
| Seagate                   | 4         | 4      | 16%     |
| HGST                      | 4         | 4      | 16%     |
| Toshiba                   | 3         | 3      | 12%     |
| Hitachi                   | 3         | 6      | 12%     |
| SPCC                      | 1         | 1      | 4%      |
| Samsung Electronics       | 1         | 1      | 4%      |
| Micron/Crucial Technology | 1         | 2      | 4%      |
| Micron Technology         | 1         | 1      | 4%      |
| Unknown                   | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 26.32%  |
| Seagate | 4         | 4      | 21.05%  |
| HGST    | 4         | 4      | 21.05%  |
| Toshiba | 3         | 3      | 15.79%  |
| Hitachi | 3         | 6      | 15.79%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 22     | 75%     |
| SSD  | 5         | 5      | 20.83%  |
| NVMe | 1         | 2      | 4.17%   |

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
| Detected | 156       | 248    | 56.12%  |
| Works    | 99        | 137    | 35.61%  |
| Malfunc  | 23        | 29     | 8.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 189       | 63.42%  |
| AMD                          | 24        | 8.05%   |
| SanDisk                      | 21        | 7.05%   |
| Samsung Electronics          | 17        | 5.7%    |
| Kingston Technology Company  | 8         | 2.68%   |
| SK hynix                     | 7         | 2.35%   |
| Phison Electronics           | 6         | 2.01%   |
| Silicon Motion               | 5         | 1.68%   |
| Micron Technology            | 5         | 1.68%   |
| KIOXIA                       | 5         | 1.68%   |
| Toshiba America Info Systems | 3         | 1.01%   |
| Nvidia                       | 3         | 1.01%   |
| ADATA Technology             | 2         | 0.67%   |
| Micron/Crucial Technology    | 1         | 0.34%   |
| Biwin Storage Technology     | 1         | 0.34%   |
| ASMedia Technology           | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 26        | 8.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 22        | 6.94%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 6.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 5.99%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 5.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 3.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 2.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 2.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 2.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 1.58%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.58%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.26%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 1.26%   |
| Intel SSD 660P Series                                                            | 4         | 1.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.26%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 0.95%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                            | 3         | 0.95%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 3         | 0.95%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.95%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.95%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 3         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.95%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.95%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.95%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 2         | 0.63%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.63%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 2         | 0.63%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 2         | 0.63%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.63%   |
| Kingston Company KC2000/KC2500 NVMe SSD SM2262EN                                 | 2         | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 175       | 59.32%  |
| NVMe | 74        | 25.08%  |
| RAID | 31        | 10.51%  |
| IDE  | 15        | 5.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 211       | 82.75%  |
| AMD    | 44        | 17.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 3.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 5         | 1.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.95%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 1.95%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 1.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.56%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.56%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 1.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.17%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.17%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.17%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 3         | 1.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.17%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.17%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.78%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.78%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 0.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.78%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 2         | 0.78%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.78%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 2         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.78%   |
| Intel Core i3-2367M CPU @ 1.40GHz             | 2         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.78%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 81        | 31.64%  |
| Intel Core i7           | 52        | 20.31%  |
| Intel Core i3           | 18        | 7.03%   |
| Other                   | 16        | 6.25%   |
| AMD Ryzen 5             | 15        | 5.86%   |
| Intel Celeron           | 14        | 5.47%   |
| Intel Core 2 Duo        | 10        | 3.91%   |
| Intel Atom              | 9         | 3.52%   |
| Intel Pentium           | 5         | 1.95%   |
| AMD Ryzen 7             | 5         | 1.95%   |
| Intel Pentium Dual-Core | 4         | 1.56%   |
| AMD A6                  | 4         | 1.56%   |
| AMD Ryzen 7 PRO         | 3         | 1.17%   |
| AMD Athlon              | 3         | 1.17%   |
| Intel Genuine           | 2         | 0.78%   |
| AMD Ryzen 9             | 2         | 0.78%   |
| AMD Ryzen 3             | 2         | 0.78%   |
| AMD E                   | 2         | 0.78%   |
| AMD A4                  | 2         | 0.78%   |
| AMD A12                 | 2         | 0.78%   |
| Intel Xeon              | 1         | 0.39%   |
| Intel Pentium M         | 1         | 0.39%   |
| Intel Core i9           | 1         | 0.39%   |
| AMD FX                  | 1         | 0.39%   |
| AMD A10                 | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 140       | 54.9%   |
| 4      | 72        | 28.24%  |
| 6      | 21        | 8.24%   |
| 8      | 11        | 4.31%   |
| 1      | 7         | 2.75%   |
| 14     | 3         | 1.18%   |
| 10     | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 255       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 206       | 80.47%  |
| 1      | 50        | 19.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 252       | 98.44%  |
| Unknown        | 3         | 1.17%   |
| 32-bit         | 1         | 0.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 30.94%  |
| 0x206a7    | 23        | 8.68%   |
| 0x306a9    | 18        | 6.79%   |
| 0x20655    | 10        | 3.77%   |
| 0x906ea    | 9         | 3.4%    |
| 0x40651    | 8         | 3.02%   |
| 0x306d4    | 7         | 2.64%   |
| 0x306c3    | 7         | 2.64%   |
| 0x806e9    | 6         | 2.26%   |
| 0x406e3    | 6         | 2.26%   |
| 0xa0652    | 5         | 1.89%   |
| 0x1067a    | 5         | 1.89%   |
| 0x806ec    | 4         | 1.51%   |
| 0x806ea    | 4         | 1.51%   |
| 0x30678    | 4         | 1.51%   |
| 0x20652    | 4         | 1.51%   |
| 0x08600104 | 4         | 1.51%   |
| 0x08108109 | 4         | 1.51%   |
| 0x06001119 | 4         | 1.51%   |
| 0x806eb    | 3         | 1.13%   |
| 0x806d1    | 3         | 1.13%   |
| 0x806c1    | 3         | 1.13%   |
| 0x106ca    | 3         | 1.13%   |
| 0x906e9    | 2         | 0.75%   |
| 0x706e5    | 2         | 0.75%   |
| 0x706a8    | 2         | 0.75%   |
| 0x706a1    | 2         | 0.75%   |
| 0x406c4    | 2         | 0.75%   |
| 0x10676    | 2         | 0.75%   |
| 0x0a50000d | 2         | 0.75%   |
| 0x0a50000b | 2         | 0.75%   |
| 0x08608103 | 2         | 0.75%   |
| 0x08108102 | 2         | 0.75%   |
| 0x0700010f | 2         | 0.75%   |
| 0xb06a3    | 1         | 0.38%   |
| 0xa0660    | 1         | 0.38%   |
| 0x906a3    | 1         | 0.38%   |
| 0x6fd      | 1         | 0.38%   |
| 0x6fb      | 1         | 0.38%   |
| 0x406c3    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 15.29%  |
| SandyBridge      | 31        | 12.16%  |
| IvyBridge        | 23        | 9.02%   |
| Haswell          | 20        | 7.84%   |
| Westmere         | 16        | 6.27%   |
| Penryn           | 13        | 5.1%    |
| Skylake          | 12        | 4.71%   |
| Zen+             | 11        | 4.31%   |
| Broadwell        | 11        | 4.31%   |
| Silvermont       | 10        | 3.92%   |
| Zen 3            | 7         | 2.75%   |
| TigerLake        | 7         | 2.75%   |
| IceLake          | 7         | 2.75%   |
| Zen 2            | 6         | 2.35%   |
| CometLake        | 6         | 2.35%   |
| Piledriver       | 5         | 1.96%   |
| Unknown          | 5         | 1.96%   |
| Goldmont plus    | 4         | 1.57%   |
| Bonnell          | 4         | 1.57%   |
| Alderlake Hybrid | 4         | 1.57%   |
| Core             | 3         | 1.18%   |
| Zen              | 2         | 0.78%   |
| Jaguar           | 2         | 0.78%   |
| Excavator        | 2         | 0.78%   |
| Bobcat           | 2         | 0.78%   |
| Steamroller      | 1         | 0.39%   |
| P6               | 1         | 0.39%   |
| K8 & K10 hybrid  | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 197       | 56.61%  |
| Nvidia | 86        | 24.71%  |
| AMD    | 65        | 18.68%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 28        | 7.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 6.44%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 3.92%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 12        | 3.36%   |
| Intel HD Graphics 5500                                                                   | 11        | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 2.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 2.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 2.52%   |
| Intel HD Graphics 620                                                                    | 9         | 2.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.24%   |
| Intel UHD Graphics 620                                                                   | 7         | 1.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.96%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.68%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.12%   |
| Intel HD Graphics 630                                                                    | 4         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.12%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.84%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.84%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.84%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.84%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.84%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.84%   |
| AMD Lucienne                                                                             | 3         | 0.84%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.56%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.56%   |
| Nvidia GM108M [GeForce 930M]                                                             | 2         | 0.56%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 43.36%  |
| Intel + Nvidia | 67        | 26.17%  |
| 1 x AMD        | 32        | 12.5%   |
| Intel + AMD    | 18        | 7.03%   |
| 1 x Nvidia     | 11        | 4.3%    |
| 2 x AMD        | 8         | 3.13%   |
| AMD + Nvidia   | 8         | 3.13%   |
| 2 x Intel      | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 208       | 80.62%  |
| Proprietary | 46        | 17.83%  |
| Unknown     | 4         | 1.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 59.77%  |
| 1.01-2.0   | 42        | 16.09%  |
| 0.01-0.5   | 24        | 9.2%    |
| 3.01-4.0   | 20        | 7.66%   |
| 0.51-1.0   | 14        | 5.36%   |
| 7.01-8.0   | 2         | 0.77%   |
| 5.01-6.0   | 2         | 0.77%   |
| 2.01-3.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 21.38%  |
| Chimei Innolux          | 43        | 14.83%  |
| LG Display              | 40        | 13.79%  |
| BOE                     | 38        | 13.1%   |
| Samsung Electronics     | 29        | 10%     |
| Dell                    | 12        | 4.14%   |
| Sharp                   | 8         | 2.76%   |
| Chi Mei Optoelectronics | 6         | 2.07%   |
| Apple                   | 5         | 1.72%   |
| Acer                    | 5         | 1.72%   |
| PANDA                   | 4         | 1.38%   |
| Lenovo                  | 4         | 1.38%   |
| Philips                 | 3         | 1.03%   |
| Hewlett-Packard         | 3         | 1.03%   |
| Valve                   | 2         | 0.69%   |
| Panasonic               | 2         | 0.69%   |
| InnoLux Display         | 2         | 0.69%   |
| Goldstar                | 2         | 0.69%   |
| EXP                     | 2         | 0.69%   |
| AOC                     | 2         | 0.69%   |
| Xiaomi                  | 1         | 0.34%   |
| ViewSonic               | 1         | 0.34%   |
| Unknown                 | 1         | 0.34%   |
| TRI                     | 1         | 0.34%   |
| Toshiba                 | 1         | 0.34%   |
| Sony                    | 1         | 0.34%   |
| MStar                   | 1         | 0.34%   |
| MSI                     | 1         | 0.34%   |
| LTM                     | 1         | 0.34%   |
| LG Philips              | 1         | 0.34%   |
| InfoVision              | 1         | 0.34%   |
| HJC                     | 1         | 0.34%   |
| CPT                     | 1         | 0.34%   |
| BenQ                    | 1         | 0.34%   |
| Armaggeddon             | 1         | 0.34%   |
| Ancor Communications    | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 5         | 1.72%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 4         | 1.38%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 1.03%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 1.03%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 1.03%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 2         | 0.69%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch               | 2         | 0.69%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 2         | 0.69%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch             | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch             | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO1AD8 1920x1200 216x136mm 10.0-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO10ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 2         | 0.69%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 2         | 0.69%   |
| Acer ET241Y ACR056C 1920x1080 527x296mm 23.8-inch                         | 2         | 0.69%   |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                        | 1         | 0.34%   |
| ViewSonic V3D231 Series VSC4C29 1920x1080 510x290mm 23.1-inch             | 1         | 0.34%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1600x900               | 1         | 0.34%   |
| TRI TRI2400 TRI2400 1920x1080 530x300mm 24.0-inch                         | 1         | 0.34%   |
| Toshiba TV TSB010B 1920x1080 706x398mm 31.9-inch                          | 1         | 0.34%   |
| Sony TV SNY0902 1920x1080                                                 | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 110       | 39.86%  |
| 1920x1080 (FHD)    | 105       | 38.04%  |
| 1280x800 (WXGA)    | 12        | 4.35%   |
| 1600x900 (HD+)     | 10        | 3.62%   |
| 3840x2160 (4K)     | 6         | 2.17%   |
| 1920x1200 (WUXGA)  | 5         | 1.81%   |
| 2560x1440 (QHD)    | 4         | 1.45%   |
| 2160x1440          | 3         | 1.09%   |
| 1024x600           | 3         | 1.09%   |
| 800x1280           | 2         | 0.72%   |
| 2560x1080          | 2         | 0.72%   |
| 1440x900 (WXGA+)   | 2         | 0.72%   |
| 1360x768           | 2         | 0.72%   |
| 1280x720 (HD)      | 2         | 0.72%   |
| 1024x768 (XGA)     | 2         | 0.72%   |
| 3440x1440          | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2560x1600          | 1         | 0.36%   |
| 2240x1400          | 1         | 0.36%   |
| 1920x540           | 1         | 0.36%   |
| 1680x1050 (WSXGA+) | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 92        | 31.72%  |
| 14      | 64        | 22.07%  |
| 13      | 52        | 17.93%  |
| 23      | 13        | 4.48%   |
| 24      | 10        | 3.45%   |
| 12      | 9         | 3.1%    |
| 17      | 7         | 2.41%   |
| 11      | 6         | 2.07%   |
| 27      | 5         | 1.72%   |
| 10      | 5         | 1.72%   |
| 31      | 4         | 1.38%   |
| 21      | 3         | 1.03%   |
| 7       | 3         | 1.03%   |
| Unknown | 3         | 1.03%   |
| 72      | 2         | 0.69%   |
| 52      | 2         | 0.69%   |
| 34      | 2         | 0.69%   |
| 84      | 1         | 0.34%   |
| 65      | 1         | 0.34%   |
| 32      | 1         | 0.34%   |
| 28      | 1         | 0.34%   |
| 25      | 1         | 0.34%   |
| 19      | 1         | 0.34%   |
| 18      | 1         | 0.34%   |
| 16      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 190       | 65.74%  |
| 201-300     | 35        | 12.11%  |
| 501-600     | 27        | 9.34%   |
| 351-400     | 10        | 3.46%   |
| 601-700     | 6         | 2.08%   |
| 401-500     | 6         | 2.08%   |
| 701-800     | 3         | 1.04%   |
| 1501-2000   | 3         | 1.04%   |
| 1001-1500   | 3         | 1.04%   |
| Unknown     | 3         | 1.04%   |
| 1-100       | 2         | 0.69%   |
| 101-200     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 214       | 85.26%  |
| 16/10   | 21        | 8.37%   |
| 3/2     | 6         | 2.39%   |
| 21/9    | 3         | 1.2%    |
| 4/3     | 2         | 0.8%    |
| 0.67    | 2         | 0.8%    |
| 32/9    | 1         | 0.4%    |
| 1.00    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 104       | 35.99%  |
| 101-110        | 91        | 31.49%  |
| 201-250        | 23        | 7.96%   |
| 71-80          | 10        | 3.46%   |
| 61-70          | 9         | 3.11%   |
| 351-500        | 7         | 2.42%   |
| 121-130        | 7         | 2.42%   |
| More than 1000 | 6         | 2.08%   |
| 51-60          | 6         | 2.08%   |
| 41-50          | 5         | 1.73%   |
| 301-350        | 5         | 1.73%   |
| 251-300        | 4         | 1.38%   |
| 1-40           | 3         | 1.04%   |
| Unknown        | 3         | 1.04%   |
| 151-200        | 2         | 0.69%   |
| 91-100         | 2         | 0.69%   |
| 141-150        | 1         | 0.35%   |
| 111-120        | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 109       | 38.38%  |
| 101-120       | 109       | 38.38%  |
| 51-100        | 41        | 14.44%  |
| 161-240       | 15        | 5.28%   |
| 1-50          | 6         | 2.11%   |
| Unknown       | 3         | 1.06%   |
| More than 240 | 1         | 0.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 207       | 79.92%  |
| 2     | 47        | 18.15%  |
| 0     | 4         | 1.54%   |
| 3     | 1         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 136       | 32.23%  |
| Intel                           | 125       | 29.62%  |
| Qualcomm Atheros                | 71        | 16.82%  |
| Broadcom                        | 28        | 6.64%   |
| TP-Link                         | 8         | 1.9%    |
| MediaTek                        | 8         | 1.9%    |
| Ralink Technology               | 6         | 1.42%   |
| Broadcom Limited                | 6         | 1.42%   |
| Xiaomi                          | 5         | 1.18%   |
| Ralink                          | 4         | 0.95%   |
| Huawei Technologies             | 3         | 0.71%   |
| ASIX Electronics                | 3         | 0.71%   |
| Samsung Electronics             | 2         | 0.47%   |
| Nvidia                          | 2         | 0.47%   |
| Microchip Technology            | 2         | 0.47%   |
| Dell                            | 2         | 0.47%   |
| Spreadtrum Communications       | 1         | 0.24%   |
| Qualcomm Atheros Communications | 1         | 0.24%   |
| OPPO Electronics                | 1         | 0.24%   |
| Marvell Technology Group        | 1         | 0.24%   |
| JMicron Technology              | 1         | 0.24%   |
| InterBiometrics                 | 1         | 0.24%   |
| Hewlett-Packard                 | 1         | 0.24%   |
| DisplayLink                     | 1         | 0.24%   |
| D-Link                          | 1         | 0.24%   |
| Attansic Technology             | 1         | 0.24%   |
| ASUSTek Computer                | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 85        | 16.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 5.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 2.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.57%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.38%   |
| Intel Wireless 7265                                               | 10        | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.19%   |
| Realtek 802.11ac NIC                                              | 6         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.99%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.99%   |
| Intel Wireless 7260                                               | 5         | 0.99%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.99%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.79%   |
| Intel Wireless 3160                                               | 4         | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.79%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.79%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 4         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.59%   |
| TP-Link 802.11n NIC                                               | 3         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.59%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.59%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 43.75%  |
| Qualcomm Atheros                | 59        | 21.69%  |
| Realtek Semiconductor           | 38        | 13.97%  |
| Broadcom                        | 21        | 7.72%   |
| TP-Link                         | 8         | 2.94%   |
| MediaTek                        | 8         | 2.94%   |
| Ralink Technology               | 6         | 2.21%   |
| Ralink                          | 4         | 1.47%   |
| Broadcom Limited                | 4         | 1.47%   |
| Dell                            | 2         | 0.74%   |
| Qualcomm Atheros Communications | 1         | 0.37%   |
| D-Link                          | 1         | 0.37%   |
| ASUSTek Computer                | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 5.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 4.74%   |
| Intel Wi-Fi 6 AX200                                            | 12        | 4.38%   |
| Intel Wireless 7265                                            | 10        | 3.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 3.28%   |
| Intel Wireless 8265 / 8275                                     | 9         | 3.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 2.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 2.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 2.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.19%   |
| Realtek 802.11ac NIC                                           | 6         | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 1.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.82%   |
| Intel Wireless 7260                                            | 5         | 1.82%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.82%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.46%   |
| Intel Wireless 3160                                            | 4         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.46%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.46%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.46%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 4         | 1.46%   |
| TP-Link 802.11n NIC                                            | 3         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.09%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.09%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 1.09%   |
| Intel Wireless-AC 9260                                         | 3         | 1.09%   |
| Intel Wireless 8260                                            | 3         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.09%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 1.09%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 1.09%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.09%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 121       | 54.02%  |
| Intel                     | 49        | 21.88%  |
| Qualcomm Atheros          | 19        | 8.48%   |
| Broadcom                  | 11        | 4.91%   |
| Xiaomi                    | 5         | 2.23%   |
| Huawei Technologies       | 3         | 1.34%   |
| ASIX Electronics          | 3         | 1.34%   |
| Nvidia                    | 2         | 0.89%   |
| Microchip Technology      | 2         | 0.89%   |
| Broadcom Limited          | 2         | 0.89%   |
| Spreadtrum Communications | 1         | 0.45%   |
| Samsung Electronics       | 1         | 0.45%   |
| OPPO Electronics          | 1         | 0.45%   |
| Marvell Technology Group  | 1         | 0.45%   |
| JMicron Technology        | 1         | 0.45%   |
| DisplayLink               | 1         | 0.45%   |
| Attansic Technology       | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 85        | 37.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 11.89%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 5.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 3.08%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 3.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.64%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 2.64%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 2.2%    |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.76%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.32%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.32%   |
| Huawei MAR-LX1M                                                                | 3         | 1.32%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 2         | 0.88%   |
| Realtek PCIe GbE Family Controller                                             | 2         | 0.88%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.88%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 2         | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.88%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.44%   |
| OPPO SM8350-IDP _SN:27BAACC8                                                   | 1         | 0.44%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.44%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.44%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.44%   |
| Intel Ethernet Controller I225-V                                               | 1         | 0.44%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 246       | 53.02%  |
| Ethernet | 214       | 46.12%  |
| Modem    | 4         | 0.86%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 208       | 79.09%  |
| Ethernet | 55        | 20.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 193       | 75.69%  |
| 1     | 54        | 21.18%  |
| 0     | 6         | 2.35%   |
| 3     | 2         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 169       | 64.02%  |
| Yes  | 95        | 35.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 40.87%  |
| Realtek Semiconductor           | 20        | 9.62%   |
| Qualcomm Atheros Communications | 18        | 8.65%   |
| IMC Networks                    | 16        | 7.69%   |
| Foxconn / Hon Hai               | 15        | 7.21%   |
| Broadcom                        | 12        | 5.77%   |
| Lite-On Technology              | 11        | 5.29%   |
| Apple                           | 7         | 3.37%   |
| Dell                            | 6         | 2.88%   |
| Hewlett-Packard                 | 5         | 2.4%    |
| Realtek                         | 3         | 1.44%   |
| Ralink                          | 2         | 0.96%   |
| MediaTek                        | 2         | 0.96%   |
| Cambridge Silicon Radio         | 2         | 0.96%   |
| Ralink Technology               | 1         | 0.48%   |
| ASUSTek Computer                | 1         | 0.48%   |
| Askey Computer                  | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 32        | 15.38%  |
| Intel Bluetooth Device                                                              | 15        | 7.21%   |
| Intel AX200 Bluetooth                                                               | 12        | 5.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 5.29%   |
| Realtek Bluetooth Radio                                                             | 10        | 4.81%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 3.37%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 3.37%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.88%   |
| IMC Networks Bluetooth Device                                                       | 5         | 2.4%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 2.4%    |
| Apple Bluetooth Host Controller                                                     | 5         | 2.4%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 1.92%   |
| Lite-On Bluetooth Device                                                            | 4         | 1.92%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.92%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.92%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.44%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.44%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.44%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.44%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 1.44%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.96%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.96%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.96%   |
| IMC Networks 802.11ac WLAN Adapter                                                  | 2         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 0.96%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.96%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.96%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 0.96%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.96%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.96%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.48%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.48%   |
| Ralink CSR BS8510                                                                   | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 204       | 66.89%  |
| AMD                    | 46        | 15.08%  |
| Nvidia                 | 42        | 13.77%  |
| C-Media Electronics    | 3         | 0.98%   |
| Samsung Electronics    | 2         | 0.66%   |
| Realtek Semiconductor  | 2         | 0.66%   |
| RODE Microphones       | 1         | 0.33%   |
| Plantronics            | 1         | 0.33%   |
| MVSILICON.INC.         | 1         | 0.33%   |
| MosArt Semiconductor   | 1         | 0.33%   |
| Generalplus Technology | 1         | 0.33%   |
| Cambridge Audio        | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 7.8%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 7.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 6.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 6.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 4.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 3.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.96%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.96%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.96%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 2.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.34%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.34%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.08%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.08%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.81%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.81%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.81%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.54%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.54%   |
| Nvidia Audio device                                                                               | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 26.63%  |
| Kingston            | 43        | 23.37%  |
| SK hynix            | 31        | 16.85%  |
| Micron Technology   | 16        | 8.7%    |
| Nanya Technology    | 9         | 4.89%   |
| A-DATA Technology   | 8         | 4.35%   |
| Unknown             | 4         | 2.17%   |
| Ramaxel Technology  | 4         | 2.17%   |
| Elpida              | 4         | 2.17%   |
| Apacer              | 4         | 2.17%   |
| Crucial             | 3         | 1.63%   |
| Unknown (ABCD)      | 2         | 1.09%   |
| Team                | 2         | 1.09%   |
| Unknown (08AE)      | 1         | 0.54%   |
| Transcend           | 1         | 0.54%   |
| Silicon Power       | 1         | 0.54%   |
| Kingmax             | 1         | 0.54%   |
| Unknown             | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.11%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 3         | 1.58%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 1.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.05%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 2         | 1.05%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.05%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.05%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 1.05%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.05%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.05%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 2         | 1.05%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471B2873EH1-CF8 1GB SODIMM 1067MT/s                 | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.05%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.05%   |
| Kingston RAM KF2666C15S4/8G 8GB SODIMM DDR4 2667MT/s             | 2         | 1.05%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 1.05%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.05%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.53%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.53%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1333MT/s               | 1         | 0.53%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.53%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.53%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.53%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.53%   |
| SK hynix RAM HYMP325S64AMP8-Y5 2GB SODIMM DDR2 667MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 61        | 44.2%   |
| DDR3   | 61        | 44.2%   |
| SDRAM  | 3         | 2.17%   |
| LPDDR4 | 3         | 2.17%   |
| LPDDR3 | 3         | 2.17%   |
| DDR2   | 3         | 2.17%   |
| DDR5   | 2         | 1.45%   |
| DDR    | 2         | 1.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 131       | 95.62%  |
| Row Of Chips | 6         | 4.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 58        | 36.25%  |
| 8192  | 52        | 32.5%   |
| 2048  | 21        | 13.13%  |
| 16384 | 15        | 9.38%   |
| 32768 | 7         | 4.38%   |
| 1024  | 7         | 4.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 32        | 19.88%  |
| 2667    | 29        | 18.01%  |
| 3200    | 24        | 14.91%  |
| 1334    | 19        | 11.8%   |
| 2400    | 11        | 6.83%   |
| 1333    | 11        | 6.83%   |
| 2133    | 9         | 5.59%   |
| 1067    | 6         | 3.73%   |
| 667     | 3         | 1.86%   |
| 4800    | 2         | 1.24%   |
| 4199    | 2         | 1.24%   |
| 3266    | 2         | 1.24%   |
| 1066    | 2         | 1.24%   |
| 800     | 2         | 1.24%   |
| Unknown | 2         | 1.24%   |
| 8400    | 1         | 0.62%   |
| 5600    | 1         | 0.62%   |
| 3333    | 1         | 0.62%   |
| 2134    | 1         | 0.62%   |
| 2048    | 1         | 0.62%   |

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


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3150 Series | 1         | 25%     |
| Seiko Epson L210 Series  | 1         | 25%     |
| Canon E410 series        | 1         | 25%     |
| Brother DCP-1510         | 1         | 25%     |

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
| Chicony Electronics                    | 46        | 21.4%   |
| Microdia                               | 25        | 11.63%  |
| IMC Networks                           | 23        | 10.7%   |
| Sunplus Innovation Technology          | 18        | 8.37%   |
| Suyin                                  | 15        | 6.98%   |
| Realtek Semiconductor                  | 15        | 6.98%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.65%   |
| Bison Electronics                      | 9         | 4.19%   |
| Quanta                                 | 8         | 3.72%   |
| Acer                                   | 7         | 3.26%   |
| Apple                                  | 6         | 2.79%   |
| Alcor Micro                            | 5         | 2.33%   |
| Syntek                                 | 4         | 1.86%   |
| Silicon Motion                         | 3         | 1.4%    |
| Luxvisions Innotech Limited            | 3         | 1.4%    |
| Logitech                               | 2         | 0.93%   |
| Lite-On Technology                     | 2         | 0.93%   |
| Generalplus Technology                 | 2         | 0.93%   |
| Z-Star Microelectronics                | 1         | 0.47%   |
| YGTek                                  | 1         | 0.47%   |
| Sonix Technology                       | 1         | 0.47%   |
| ShineTech                              | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| Ricoh                                  | 1         | 0.47%   |
| Primax Electronics                     | 1         | 0.47%   |
| OmniVision Technologies                | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| icSpring                               | 1         | 0.47%   |
| eMPIA Technology                       | 1         | 0.47%   |
| Cubeternet                             | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 10        | 4.65%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 8         | 3.72%   |
| Chicony Integrated Camera                                                  | 7         | 3.26%   |
| Chicony HD Webcam                                                          | 6         | 2.79%   |
| Sunplus Integrated_Webcam_HD                                               | 5         | 2.33%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 4         | 1.86%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 4         | 1.86%   |
| IMC Networks Integrated Camera                                             | 4         | 1.86%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.86%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 4         | 1.86%   |
| Suyin 1.3M HD WebCam                                                       | 3         | 1.4%    |
| Sunplus Laptop Integrated Webcam HD                                        | 3         | 1.4%    |
| Realtek Integrated_Webcam_HD                                               | 3         | 1.4%    |
| Quanta HP TrueVision HD Camera                                             | 3         | 1.4%    |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.4%    |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.4%    |
| Chicony HP HD Webcam                                                       | 3         | 1.4%    |
| Bison Lenovo Integrated Webcam                                             | 3         | 1.4%    |
| Apple FaceTime HD Camera                                                   | 3         | 1.4%    |
| Syntek USB Camera Device                                                   | 2         | 0.93%   |
| Suyin WebCam                                                               | 2         | 0.93%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 2         | 0.93%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 2         | 0.93%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 2         | 0.93%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.93%   |
| Sunplus HD WebCam                                                          | 2         | 0.93%   |
| Realtek USB Camera                                                         | 2         | 0.93%   |
| Realtek HD WebCam                                                          | 2         | 0.93%   |
| Quanta HD Webcam                                                           | 2         | 0.93%   |
| Microdia Webcam Vitade AF                                                  | 2         | 0.93%   |
| Microdia USB 2.0 Camera                                                    | 2         | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 0.93%   |
| IMC Networks HD Camera                                                     | 2         | 0.93%   |
| Chicony HP Webcam [2 MP Macro]                                             | 2         | 0.93%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 2         | 0.93%   |
| Bison SunplusIT Integrated Camera                                          | 2         | 0.93%   |
| Bison Integrated Camera                                                    | 2         | 0.93%   |
| Bison HD Webcam                                                            | 2         | 0.93%   |
| Alcor Micro Asus Integrated Webcam                                         | 2         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 29.41%  |
| Synaptics                  | 7         | 20.59%  |
| Shenzhen Goodix Technology | 6         | 17.65%  |
| Upek                       | 3         | 8.82%   |
| Elan Microelectronics      | 3         | 8.82%   |
| AuthenTec                  | 3         | 8.82%   |
| LighTuning Technology      | 1         | 2.94%   |
| Focal-systems.Corp         | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 8.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 8.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 3         | 8.82%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 8.82%   |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 5.88%   |
| Elan ELAN:ARM-M4                                       | 2         | 5.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.94%   |
| Validity Sensors VFS491                                | 1         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.94%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.94%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 2.94%   |
| Shenzhen Goodix FingerPrint                            | 1         | 2.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.94%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 2.94%   |
| Elan ELAN:Fingerprint                                  | 1         | 2.94%   |
| AuthenTec Fingerprint Sensor                           | 1         | 2.94%   |
| AuthenTec AES2550 Fingerprint Sensor                   | 1         | 2.94%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 78.57%  |
| O2 Micro    | 1         | 7.14%   |
| Lenovo      | 1         | 7.14%   |
| Alcor Micro | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 21.43%  |
| Broadcom 5880                                                                | 2         | 14.29%  |
| Broadcom 58200                                                               | 2         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.14%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 172       | 66.41%  |
| 1     | 71        | 27.41%  |
| 2     | 14        | 5.41%   |
| 4     | 1         | 0.39%   |
| 3     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 33.33%  |
| Graphics card            | 22        | 21.57%  |
| Net/wireless             | 13        | 12.75%  |
| Chipcard                 | 12        | 11.76%  |
| Multimedia controller    | 6         | 5.88%   |
| Bluetooth                | 4         | 3.92%   |
| Storage                  | 3         | 2.94%   |
| Net/ethernet             | 2         | 1.96%   |
| Camera                   | 2         | 1.96%   |
| Storage/ide              | 1         | 0.98%   |
| Sound                    | 1         | 0.98%   |
| Communication controller | 1         | 0.98%   |
| Card reader              | 1         | 0.98%   |

